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
