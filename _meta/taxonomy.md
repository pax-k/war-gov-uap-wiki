---
title: Tag Taxonomy
category: meta
tags: [taxonomy, meta]
sources: []
summary: Canonical controlled vocabulary for tags across the wiki. Source of truth for the tag-taxonomy skill.
created: 2026-05-09
updated: 2026-05-13T16:00:00Z
---

# Tag Taxonomy

Controlled vocabulary for the wiki. The current corpus is **UAP-archives** focused (376 wiki pages from 80 declassified-document / archival-conversation ingests, 1944–2026). Tags below are organized by axis. Use this file as the source of truth before adding tags to any new page.

## Rules

- **Max 5 domain/type tags per page.** `visibility/` tags are system tags and do not count.
- **Lowercase, hyphenated.** `papua-new-guinea`, not `Papua New Guinea` or `papua_new_guinea`.
- **ASCII only.** No diacritics in tags. (Use diacritics in `title:` and body text.)
- **Singular by default.** `concept` not `concepts`; `entity` not `entities`. Exceptions: collective nouns where plural is the natural form (`balls-of-fire`, `flying-discs`).
- **Prefer broad over narrow.** A page about a specific NASA mission gets `nasa`, `mission` — not a per-mission tag.
- **Use category to disambiguate.** A page in `entities/` doesn't need an `entity` tag.
- **Never alias.** Pick the canonical form below.

## Reserved System Tags — `visibility/`

These mark a page's intended reach. **Optional.** Untagged pages default to public.

| Tag | Meaning |
|---|---|
| `visibility/public` | Explicitly public — same as no tag |
| `visibility/internal` | Team-only — excluded in filtered query/export mode |
| `visibility/pii` | Sensitive — excluded in filtered query/export mode |

Rules: do **not** count toward 5-tag limit; one per page; never aliased; leave untouched in audits.

Current corpus: **0 pages tagged**. All 376 pages default to public, which matches an open-source declassified-archive vault.

## Domain Tags

The subject matter axis — what the page is about.

### Core domain

| Tag | Use for |
|---|---|
| `uap` | Anything in the UAP / unidentified-aerial-phenomena domain. The corpus's anchor tag (351 pages). |

### History / era

| Tag | Use for |
|---|---|
| `history` | Historical analysis or context (broad). |
| `ww2` | World War II (1939–1945) era specifically. |
| `1947` … `1994` | Year of source-event when narrowly anchored. Use sparingly — prefer `history` + `ww2` etc. when an era covers it. |
| `1940s`, `1950s`, `1960s` | Decade-level when year is unknown or pattern spans years. Use the decade tag (not a year tag) when the page covers a multi-year span within a single decade — e.g. BSRA 1945–1952, IFSB 1952–1962. |

### Geography

| Tag | Use for |
|---|---|
| `france`, `georgia`, `germany`, `japan`, `kazakhstan`, `mexico`, `netherlands`, `papua-new-guinea`, `russia`, `sweden`, `tajikistan`, `turkmenistan`, `ussr` | Country of source-event or affiliation. (Note: `russia` for post-1991 Russian Federation; `ussr` for pre-1991 Soviet Union — keep both to preserve the political-era distinction.) |
| `alaska`, `arizona`, `california`, `idaho`, `kansas`, `kentucky`, `michigan`, `nevada`, `new-mexico`, `ohio`, `oregon`, `washington` | US state of source-event. Add when sighting/event is geographically anchored. |

### Institutional / agency

| Tag | Use for |
|---|---|
| `usaf` | US Air Force (post-1947). |
| `usaaf` | US Army Air Forces (1941–1947). |
| `us-army` | US Army (excluding USAAF). |
| `navy` | US Navy. |
| `raf` | UK Royal Air Force. |
| `nasa` | NASA / civilian US space agency. |
| `nasc` | National Aeronautics and Space Council (EOP). |
| `fbi` | Federal Bureau of Investigation. |
| `state-department` | US Department of State. |
| `dod` | Department of Defense umbrella. |
| `eop` | Executive Office of the President. |
| `military` | Military domain at large (use when no more specific service tag fits, or for cross-service points). |
| `federal-le` | Federal law enforcement (FBI + other federal LE). Distinct from `fbi`-only items. |
| `foreign-government` | Non-US government as actor. |
| `civil-agency` | Civil (non-military) government agency. |
| `civilian-research` | Civilian (non-government) research orgs (e.g., OUFORA). |
| `intelligence` | Intelligence-community framing, sources, or methods. |
| `humint` | Human intelligence collection specifically. |
| `isr` | Intelligence, Surveillance, Reconnaissance — operational collection mission-type (distinct from `intelligence`'s IC framing axis). Used for ISR platforms (MQ-9 Reaper), ISR-mission-type institutional units (432 AEW, 482 ATKS, 33/3 SOS, 27 SOW, AFSOC MAJCOM, 603/609 AOCs, AFCENT), and ISR-anchored operations (OIR). |
| `attache` | Defense / Air Attaché reporting channel. (No diacritic.) |
| `embassy` | US embassy as originating post. |
| `diplomacy` | Diplomatic (state-to-state) framing or channel. |

### Phenomenology

| Tag | Use for |
|---|---|
| `morphology` | Object form / shape signatures (discs, orbs, kites, cylinders). |
| `behavior` | Object behavioral signatures (pacing, suppression, formation flying). |
| `pattern` | Recurring cross-page pattern. |
| `orb` | Orb-class morphology. |
| `electromagnetic` | EM-effect signatures (engine stall, equipment fail). |
| `optical` | Optical / visibility anomalies (transparency, beam-blocking). |
| `transparent` | Partial-transparency reports specifically. |
| `low-altitude` | Low-altitude encounters (~ground level). |
| `anomaly` | Generic anomaly framing where finer tags don't apply. |

### Policy / institutional

| Tag | Use for |
|---|---|
| `policy` | Policy framings, doctrine, recommendations. |
| `protocol` | Specific reporting / observational protocols (e.g., Cabell 10-element template). |
| `institutional` | Institutional posture, framing, or behavior. |
| `contact` | First-contact / ETI policy framings. |
| `eti-attribution` | Pages where the extraterrestrial-intelligence attribution itself is the analytical lens (distinct from `contact`'s policy/first-contact framing). |
| `rhetoric` | Discourse / framing analysis. |

### Domain-specific

| Tag | Use for |
|---|---|
| `aviation` | General aviation (military or civil). |
| `commercial-aviation` | Commercial / airline operations. |
| `airline` | Airline as entity. |
| `astronaut` | Astronaut as person/role. |
| `mission` | Specific space/aviation mission. |
| `spacecraft` | Spacecraft class/instance. |
| `senator` | US Senator as role. |
| `senate-staff` | Senate committee staff role. |
| `eisenhower` | Eisenhower-era / administration framing. |
| `white-house` | White House staff / routing. |
| `public-affairs` | Public-affairs / press function. |
| `archive` | Archival project framing. |
| `taxonomy` | This page or pages about taxonomy. |

## Type Tags

The "what kind of page is this" axis. Most pages are sufficiently typed by their `category:` frontmatter and folder, so type tags are sparse.

| Tag | Use for |
|---|---|
| `analysis` | Cross-cutting analytical synthesis (synthesis/ pages). |
| `sighting` | A specific dated/located UAP observation (references/sighting-*). |
| `primary-source` | Pages built directly from a declassified document. |
| `declassified` | Source was formally declassified (often pairs with `primary-source`). |
| `witness` | Witness-testimony framing or analysis. |
| `intel-witness` | Intelligence-community witness specifically (subtype of `witness`). |
| `person` | Person entity (entities/ pages — usually redundant with category, but kept for graph clarity). |
| `organization` | Organization entity (entities/ pages). |
| `location` | Location entity. |
| `drone-pilot` | Drone-pilot witness role. |

## Metadata Tags

Operational / quality flags.

| Tag | Use for |
|---|---|
| `ambiguous` | Source/identification ambiguity in the page. |
| `ocr` | OCR-related issues or evidence noted on the page. |

## Migration Guide — Aliases

Tags below are **non-canonical**. Replace with the canonical form when found.

| Alias (old) | Canonical (new) | Notes |
|---|---|---|
| `military-org` | `military` | "Org" is implied by category=entities; consolidating military-domain tags. |
| `military-unit` | `military` | Same — units fold into `military`. |
| `diplomatic` | `diplomacy` | Use the noun form consistently. |
| `federal` | *(drop)* | Redundant alongside `state-department` + `organization` or `federal-le`. |

## Frequency Reference (post-normalization)

**As of 2026-05-13 batch-8 audit:** 110 unique tags across 376 wiki pages (80 sources / 364 manifest pages + 12 non-manifest pages — synthesis/projects/journal). Near-equilibrium — **two** page-level normalizations applied (`entities/mq-9-reaper.md`: `[usaf, platform, aircraft, uap, isr]` → `[usaf, aviation, uap, isr]`, dropping `platform` and folding `aircraft` into canonical `aviation`; `entities/operation-inherent-resolve.md`: `[centcom, operation, military, uap, isr]` → `[military, uap, isr]`, dropping single-use unknowns `centcom` and `operation`); **one** taxonomy addition (`isr` promoted to canonical under Institutional/agency, distinct from `intelligence`'s IC framing axis, formalizing pre-existing 10-use cluster on USAF MQ-9 ISR-mission-type institutional units). Zero alias usage, zero non-ASCII / whitespace / case / underscore issues, zero pages over the 5-tag limit. Top tags:

```
351 uap                140 primary-source    110 sighting           85 declassified
 79 fbi                 72 usaf               71 person              51 history
 48 organization        40 nasa               39 1947                39 witness
 35 military            34 intelligence       34 policy              33 1948
 28 astronaut           28 civilian-research  23 1950                20 pattern
 19 morphology          19 rhetoric           16 aviation            15 state-department
 15 ww2                 13 navy               10 1949                10 1957
 10 federal-le          10 france             10 isr                  9 1952
  9 usaaf                8 diplomacy           8 dod                  7 california
  7 eti-attribution      7 new-mexico          7 spacecraft           6 analysis
  6 mexico               5 1964                5 behavior             5 embassy
  5 mission              5 russia              5 us-army
```

Notable shifts from batch-7 audit (353 → 376 pages, +23; tags 109 → 110, +1 net; 112 unique observed pre-normalization → 110 after the `isr` promotion + the `platform`/`aircraft`/`centcom`/`operation` removals):

- `uap` 328 → 351 (+23, exactly tracking new pages — anchor invariant).
- `primary-source` 130 → 140 (+10), `declassified` 75 → 85 (+10), `sighting` 100 → 110 (+10) — d16-d42 cluster (d16/d18/d19/d23/d25/d27/d28/d33/d35/d42 — 10 full USMTF Misreps + 1 range-fouler debrief) all carry the canonical `[uap, primary-source, declassified, usaf, sighting]` artifact-class set. Zero tag-set drift across the dow-uap mission-report ingests this batch.
- `usaf` 50 → 72 (+22), `military` 23 → 35 (+12), `navy` 13 → 13 (±0) — batch-8 is overwhelmingly USAF-anchored (d16-d42 are all 432 AEW MQ-9 OIR missions + AFSOC MQ-9/AC-130J SOF missions); the +22 USAF reflects both the mission-report pages and the 6 new institutional-stub entity pages introduced this batch (`afsoc`, `27-sow`, `33-sos`, `3-sos`, `16-sos`, `ac-130j-ghostrider`). `military` 23 → 35 (+12) tracks the 5 institutional stubs (afsoc/27-sow/33-sos/3-sos/16-sos/ac-130j) + d-mission-report ingest tags + the operation-inherent-resolve page.
- `fbi` 79 → 79 (±0) — FBI HQ ingest fully absorbed at batch-5/6; batch-8 is exclusively dow-uap.
- `history` 51 → 51, `policy` 34 → 34, `nasa` 40 → 40 (all ±0) — no NASA / policy-domain ingests this batch; growth is exclusively in the dow-uap mission-report corner.
- `aviation` 13 → 16 (+3) — `ac-130j-ghostrider` and `16-sos` (AC-130J ARMED OVERWATCH SOF pages) both adopted `aviation` over `isr` (mission-type-aware tagging: ARMED OVERWATCH/CAS is not ISR); also picks up `entities/mq-9-reaper.md` post-normalization (replacing `aircraft`).
- `isr` 0 → 10 (NEW canonical) — promoted from unknown-tag status. 10 uses anchored on USAF MQ-9 ISR-mission-type institutional stubs (`afcent`, `432-aew`, `482-atks`, `603-aoc`, `609-caoc`, `mq-9-reaper`, plus this batch's `afsoc`, `27-sow`, `33-sos`, `3-sos`, plus `operation-inherent-resolve`). The `isr` cluster is **disjoint** from the `intelligence` cluster (zero pages carry both), confirming the categorical-distinction rationale — `isr` is operational mission-type (collection lane), `intelligence` is IC framing (analytical lane).
- TWO **page normalizations**: (1) `entities/mq-9-reaper.md` dropped `platform` (single-use, no canonical equivalent) + `aircraft` → `aviation` (single-use → canonical merge); resulting tag set `[usaf, aviation, uap, isr]` aligns with sister AC-130J + 16 SOS pages' `aviation`-anchored tagging. (2) `entities/operation-inherent-resolve.md` dropped `centcom` (single-use, closest canonical `military` already present) + `operation` (single-use, no canonical equivalent; closest canonical `mission` is "Specific space/aviation mission" — too narrow for military campaign tagging); resulting tag set `[military, uap, isr]`. The operation-class is encoded via title + category + body. **Forward-looking note**: 5+ additional operation-class entity stubs are queued (Op SPARTAN SHIELD, ENDURING SENTINEL, PHANTOM FLEX, SPECTRE DAGGER, HUMMER-SICKLE per the batch-8 cross-link pass) — if those pages get created and uniformly adopt `operation`, the tag will qualify for promotion at N≥2 in a future audit.
- No year-slot activations this pass. The reserved 1947–1994 range remains stable. 2020-2024 event-dates (d16-d42) fall outside the reserved year-tag range and are anchored via filename-date suffix + `event_date` frontmatter, not via year-tag — consistent with the taxonomy's reserved-year-slot scope.

The long tail (1–4 uses) remains dominated by year tags, US state tags, and country tags — narrow but uniformly applied. Acceptable.

**Canonical-but-unused tags** (zero pages): `georgia`, `nevada`, `meta`, `balls-of-fire`, `flying-discs`, plus unused year-slots in the `1947 … 1994` range. Retention rationale unchanged: `georgia` for future Russia-Georgia content; `nevada` as standard US-state slot; `meta` implicit via folder placement; `balls-of-fire` and `flying-discs` as collective-noun morphology slots; year slots filled lazily as source-events anchor to them.

**Methodology note** (batch-8): the `isr` tag escaped the batch-7 audit's unknown-tag flag despite already standing at 6 uses on the d10/d60-d65-cluster pages. Mid-frequency unknowns (3–10 uses) sit below the visible top-of-frequency-table threshold and above the single-use floor where the "1 page → replace" rule auto-catches them. Batch-8 confirms the full-frequency-table scan (not just top-N eyeballing) is the right default for catching these. Batch-8 also caught a mid-pass page-creation race (the `operation-inherent-resolve.md` page was created between the initial scan and the final verify-pass), reinforcing the value of a final verification rescan after applying normalizations.

## Adding a New Tag

Before adding a tag:

1. Search this file — does an existing canonical tag cover it?
2. Search the corpus — has anyone already used a related tag form?
3. If genuinely new, place it in the right axis above and add a one-line description.
4. If you're introducing it on a single page only, prefer to omit; add only when it'll see ≥ 2 uses.
