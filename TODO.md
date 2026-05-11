# UAP Bulk Ingest — Plan Status

**Updated:** 2026-05-11

## Progress

**49 / 85 sources ingested (58%)** — 310 vault pages, ~60 commits ahead of `a028424 sources`.

```
Sources 1-10    DONE  ✓ (western, usper, 59, 331, 342, dos×2, serial×2, fbi-detroit-844)
Sources 11-14   DONE  ✓ (fbi-detroit-26505, 341×2, 255-T763)  + hygiene batch 1
Sources 15-20   DONE  ✓ (cometa, 059uap×3, 38_box7×2)         + hygiene batch 2
Sources 21-30   DONE  ✓ (38_box7-final, nasa d-cluster ×7, 65 fbi-hq serial-403 + 220)  + hygiene batch 3
Sources 31-40   DONE  ✓ (fbi-hq 62-83894: serials 438/449/164, sections 1/2/5/4/7 + sub_a)  + hygiene batch 4
Sources 41-49   DONE  ✓ (fbi-hq 62-83894 COMPLETE: sections 8/3/9/10/6 + dow-uap pr20/d4/d5/d52)
Sources 50-50   TODO  ⬜ (dow-uap-d7 — last of batch 5)
Sources 51-60   TODO  ⬜ + hygiene batch 5
Sources 61-70   TODO  ⬜ + hygiene batch 6
Sources 71-80   TODO  ⬜ + hygiene batch 7
Sources 81-85   TODO  ⬜ + hygiene batch 8
Final           TODO  ⬜ /wiki-synthesize + /wiki-dashboard + /wiki-export + /wiki-status
```

## Cadence (revised after batch 1)

- **Per source**: `/obsidian-wiki-ingest` (single-source via QMD-aware subagent) → verify manifest entry → `git commit -m "ingest: <name> (N/85)"`
- **Every 10 sources**: hygiene pass = `/cross-linker` + `/wiki-lint` + `/tag-taxonomy` → `git commit -m "hygiene: ..."`
- **At the end**: full hygiene + `/wiki-synthesize` + `/wiki-dashboard` + `/wiki-export` + `/wiki-status` summary report

## Major corpus anchors built so far

- **FBI HQ 62-HQ-83894** — COMPLETE 17/17 artifacts (6 Jul 1947 → 14 Jun 1977, ~30 yr, 2,159 OCR pages, 14 intake channels). The wiki's richest single-file structural history.
- **Project SIGN incident summaries** — 233 incidents across 3 box7 bundles (8 Jul 1947 Muroc → 1 Jan 1949 Jackson MS).
- **NASA d-cluster** — 7/7 files, 6-mechanism orbital UAP typology (A through F) across Gemini 7 / Apollo 11 / 12 / 17 / Skylab.
- **State Department cables** — 3 DOS cables (PNG 1985, Kazakhstan 1994, plus 2 boundary cases in 059uap00012/00011/00013).
- **COMETA Report (1999)** — French private-published policy paper, parallel to Hunter 1963 NASC memo.
- **Lonnie Zamora Socorro 1964** — FBI field investigation by SA Byrnes anchored.
- **dow-uap series** (in progress) — 4/40 ingested. Established a 2-class artifact frame: mission reports + email correspondence. Filename theater labels found unreliable (Arabian-Gulf-labeled reports decode to Eastern Mediterranean MGRS).

## Known broken-link forward placeholders (intentional)

- `entities/apollo-13`, `apollo-mesa`, `apollo-11-pao`, `gemini-8`, `gemini-10`, `gemini-12`, `jfk`, `uss-ticonderoga`, `alfmed-experiment`, `donald-l-springer`
- `references/sighting-trans-en-provence-1981`, `references/sighting-air-france-3532-1994`
- 4 small-fanout institutional placeholders: `oni`, `afswp`, `army-g-2`, `albert-chop` (1 ref each)

## Next-up sources (50-85)

```
50  dow-uap  1605  d7-mission-report-arabian-gulf-2020    [last of batch 5 → trigger hygiene]
51-65  dow-uap small mission reports (1.6-9KB each, theaters: arabian gulf, middle east, iran,
       iraq, syria, greece, east china sea, united arab emirates, gulf of aden, indopacom, persian gulf,
       strait of hormuz, mediterranean, djibouti, japan)
66+    dow-uap d3 7060B arabian gulf, ..., d49 264KB launch-summary feb 2000, d48 416KB sep 1996
       (the last 2 are the largest and likely have the most paradigm content)
81-85  remaining sources from order file
```

(Full ordering pinned at `/tmp/wiki_ingest_order.txt`.)

## Re-entrancy

Plan restart-able at any commit boundary. Each per-source commit is a clean checkpoint; `.manifest.json` is the single source of truth. To resume: read `/Users/pax/.claude/plans/i-want-to-run-virtual-toast.md` for the orchestration plan, this file for current state, and `/tmp/wiki_ingest_order.txt` for the source order.

## Per-source loop (main agent)

```text
1. qmd update && qmd embed                         # refresh QMD index over wiki collection
2. Read line N of /tmp/wiki_ingest_order.txt       # rank, cluster, size, basename
3. Dispatch ingest subagent with the prompt below
4. Verify manifest entry:
     jq '.stats, .sources["sources/<basename>"]' .manifest.json
   If null → SendMessage agent to finish (esp. manifest write, projects/uap/uap.md,
   index.md, log.md, hot.md). Common failure: subagent ends mid-flow before manifest.
5. git add .manifest.json index.md log.md hot.md _meta/taxonomy.md
   git add concepts/ entities/ references/ synthesis/ projects/ skills/ journal/ 2>/dev/null
   git commit -m "ingest: <short slug> (N/85)"
6. Every 10 sources: dispatch hygiene = cross-linker → (wiki-lint + tag-taxonomy in parallel)
                     → git add -A && git commit -m "hygiene: ... (sources X..Y)"
```

## Audit & repair plan (pre-resume)

Files >100KB ingested before the chunking protocol existed are at risk of silent truncation. The `Read` tool reads up to ~30K tokens of one-line minified JSON — Mistral OCR JSON is one line, so files >~50KB get truncated and the subagent gets partial content with no signal that more exists.

**Confirmed gap so far:**
- `255_413270_ufo's_and_defense_what_should_we_prepare_for.json` (COMETA Report, 94 pages) — pages 50-93 not in wiki. Missing: German pilots cold-war framing, moon-base discussion, Boston Globe May 2000 article, Russian airport Jan 2001 incident, Leslie Kean biographical entry, full appendix series.

**Suspect (needs probe):**
- All 17 other files >100KB. Section_7 had mixed results (p130 ✓, p180 ✗).

### Phase 1 — Audit subagent (one shot)

Dispatch a subagent to:
1. For every file with `size_bytes > 100000` in `.manifest.json`, compute `jq '.pages | length'`.
2. Sample 5 pages per file: indices 0, 25%, 50%, 75%, 95% of total.
3. Extract a distinctive 80-150 char phrase from each (skip pages that are pure OCR stamps / dates).
4. Grep the wiki (`concepts/ entities/ references/ synthesis/`) for each phrase.
5. Build coverage table: file × probe × found-in-wiki.
6. Flag files where ≥2 of 5 probes carry substantive content but aren't found.
7. Per flagged file, list specific missing content (names, events, dates, themes).

### Phase 2 — Repair dispatches

For each flagged file, a REPAIR subagent (different prompt from ingest):
- Read existing reference page for the file.
- Read full source via the chunking protocol (jq batches of 20 pages).
- Identify content present in source but absent from wiki coverage.
- Patch in-place: append to master table inside reference page, create new entity/sighting/concept pages only for paradigm content, cross-link.
- Update existing manifest entry's `pages_updated` / `pages_created` lists. Do NOT create a duplicate source entry.
- Log: `[ISO] REPAIR source="..." reason="..." pages_added=N pages_updated=M`.
- Same 15-page cap discipline as ingest.

### Phase 3 — Re-audit

Re-run audit subagent on repaired files to confirm coverage.

### Phase 4 — Resume forward ingestion

With Plan B chunking protocol applied to every subagent for the remaining 35 sources.

---

## Subagent prompt template (per-source ingest)

Hand this to a `general-purpose` subagent in isolation. Customize the marked `<...>` slots for the file at hand: size, sister-file context, QMD queries, paradigm-content hint.

```text
Single-source ingest into Obsidian wiki at /Users/pax/Documents/Obsidian/obsidian-wiki.
CWD = vault.

INGEST: sources/<filename>.json (<size> bytes — <one-line description>). No other sources.

## Step 0: Read framework
1. AGENTS.md
2. .skills/wiki-ingest/SKILL.md
3. .skills/llm-wiki/SKILL.md
4. _meta/taxonomy.md   # canonical tag vocabulary, includes eti-attribution

OBSIDIAN_LINK_FORMAT=wikilink. OBSIDIAN_MAX_PAGES_PER_INGEST=15. Project = uap
(frontmatter only — pages go in top-level category dirs, not under projects/uap/).

## Step 1: Read source with chunking discipline
Mistral OCR JSON is emitted as ONE LONG MINIFIED LINE — the Read tool's
offset/limit parameters operate on lines, so they don't chunk JSON. Files
>~50KB get truncated by the tool's result-size cap. Use jq instead:

1. Total pages: `jq '.pages | length' sources/<file>.json`
2. If total > 30, read in batches of 20:
     jq -r '.pages[0:20]  | .[] | "===PAGE \(.index)===\n\(.markdown)"' sources/<file>.json
     jq -r '.pages[20:40] | .[] | "===PAGE \(.index)===\n\(.markdown)"' sources/<file>.json
     ... continue until index >= total.
3. Tables: `jq -r '.pages[] | .tables[]?.content // empty' sources/<file>.json`
4. In your deliverable `notes:` field, explicitly state coverage:
   "Read all N pages in M batches" OR "Read M-of-N, gap at pages X-Y, reason: <why>".
5. SHA-256: `shasum -a 256 -- <path>`. Confirm not in .manifest.json.

## Step 1b: QMD wiki discovery (MANDATORY)
Sister-file context: <which series this belongs to, what was already ingested, what
hypotheses are currently live on the parent-file/concept pages>.

Call mcp__plugin_qmd_qmd__query with:
  collections=["wiki"]
  intent="<one-line topic of the source>"
  searches=[
    {type:"vec", query:"<semantic phrase — NO negation, no minus signs>"},
    {type:"lex", query:"<keywords for BM25 exact-match>"}
  ]
  limit:8

Skip the papers collection (sources are .json, not .md). Use the returned hits to
decide which existing pages to UPDATE vs which new pages to CREATE. Existing related
pages worth checking explicitly: <list known-relevant pages>.

## Steps 2–7: Distill, plan, write
Per .skills/wiki-ingest/SKILL.md. STRICT cap at 15 new pages.

Strategy:
- Always create a document-as-reference page (references/<source-slug>.md).
- For multi-document compilations (sections, large serials, mission-report digests):
  use a master TABLE inside the reference page; create dedicated sighting/entity
  pages ONLY for paradigm-defining events or recurring named individuals/orgs.
- Prefer UPDATING existing concept/synthesis/parent-file pages over creating duplicates.
- New sighting pages require morphology / duration / co-platform corroboration —
  not just a kinematic data point.

Use [[category/page-name]] wikilinks. Required frontmatter on every new page:
  title, category, tags (≤5, from canonical taxonomy),
  sources (use a stable source_id, not the raw filename),
  created, updated, summary (≤200 chars), provenance block,
  base_confidence, lifecycle: active, lifecycle_changed.
Project: uap.

## State files (atomic) — manifest LAST
Write the manifest entry as the FINAL step. Prior subagents have stopped mid-flow
before writing it; resume requests are expensive. Do .manifest.json absolutely last,
after index.md, log.md, hot.md, projects/uap/uap.md, and all page edits.

Manifest entry shape under sources["sources/<filename>.json"]:
  ingested_at (ISO now), size_bytes: <N>, modified_at (file mtime),
  content_hash: "sha256:<hex>", source_id, source_type:"document",
  source_quality:"official", project:"uap",
  pages_created:[<paths>], pages_updated:[<paths>].
Bump stats.total_sources_ingested by 1, stats.total_pages by the count of new pages,
projects.uap.last_ingested (ISO now), projects.uap.sources_ingested by 1.

Update:
- index.md (add new pages, refresh timestamp).
- log.md (append `[ISO] INGEST source="..." pages_created=N pages_updated=M mode=append`).
- hot.md (refresh Recent Activity to last 3 ops, refresh Active Threads if needed).

## Deliverable (return as your final message)
status: ok | skipped | failed
basename: <filename>.json
qmd_hits: [paths]
pages_created: [paths]
pages_updated: [paths]
manifest_entry_added: true | false
state_files_updated: [.manifest.json, index.md, log.md, hot.md, ...]
notes: <key paradigm content, file-function refinement, sister-file pattern updates,
        deferred work, OCR ambiguities flagged ^[ambiguous] vs ^[inferred] vs ^[extracted]>

Do NOT commit. Main agent commits.
```

## Subagent prompt template (per-10 hygiene)

Two subagents in parallel (wiki-lint + tag-taxonomy) after a serial cross-linker pass.

```text
# Cross-linker (run alone first)
Run /cross-linker on the vault. Apply EXTRACTED (score ≥6) + INFERRED (3-5) links
in-place. Flag AMBIGUOUS (1-2) and broken targets. Update log.md (CROSS_LINK)
and hot.md. Do NOT commit. Report links_added / pages_touched / broken_targets
(distinguishing intentional forward-placeholders).

# Wiki-lint (parallel with tag-taxonomy)
Run /wiki-lint. Repair broken wikilinks except intentional forward-placeholders.
Stub heavily-referenced institutional placeholders (e.g. usaf at 11 refs).
Flag contradictions; do not silently resolve unless a prior ingest already
established the corrected canonical version (then propagate to stale callers).
Do NOT commit.

# Tag-taxonomy (parallel with wiki-lint)
Run /tag-taxonomy. Scan all pages, compare against _meta/taxonomy.md. Apply
normalizations (singular/plural, diacritics, synonym splits, 5-tag-limit fixes).
Update _meta/taxonomy.md frequency reference. Do NOT commit. Note: prior 3 audits
found vault in equilibrium — be efficient.
```

## Key learnings (apply to every subagent dispatch)

- **Manifest LAST.** Multiple subagents have ended mid-flow before writing `.manifest.json`. Always make the manifest the absolute last write. Resume via `SendMessage <agent-id>` if it happens — the resume costs context but completes cleanly.
- **15-page cap is strict.** For 200K+ multi-document files, the temptation is to page-ify every incident. Don't — use a master table inside the reference page and reserve dedicated pages for paradigm content.
- **QMD vec queries reject negation.** Never use `-term` or `NOT term` in vec/hyde queries; use lex search for exclusions.
- **Sister-file context cuts subagent time in half.** Tell it which series this belongs to, what hypotheses are live, what existing pages cover the topic — otherwise it re-derives.
- **Filename theater labels are unreliable** (discovered in dow-uap series — Arabian-Gulf filenames decode to Eastern Mediterranean MGRS). Always verify internal metadata.
- **Project page is curated.** `projects/uap/uap.md` is a hub. Add to it but don't auto-link from cross-linker.
- **`_meta/taxonomy.md` is statistical metadata.** Cross-linker should skip it.
