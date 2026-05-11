---
title: DoW-UAP FOIA Release Series
category: entities
tags: [uap, organization, archive, dod, navy]
aliases: [DoW-UAP, dow-uap series]
sources: [sources/dow-uap-pr20.json, sources/dow-uap-d4-mission-report-arabian-gulf-2020.json, sources/dow-uap-d5-mission-report-arabian-gulf-2020.json]
summary: Provisional series-level anchor for the ~40-file "DoW-UAP" FOIA release tranche; mostly Navy-theater UAP mission reports and range-fouler debriefs 2016-2025, cleared through DoD prepublication review.
provenance:
  extracted: 0.25
  inferred: 0.72
  ambiguous: 0.03
base_confidence: 0.62
lifecycle: draft
lifecycle_changed: 2026-05-10
created: 2026-05-10T22:00:00Z
updated: 2026-05-11T05:00:00Z
---

# DoW-UAP FOIA Release Series

A **provisional series-level anchor** for the ~40-file FOIA release tranche whose source-file basenames carry the `dow-uap-` prefix. As of this writing, **3 of ~40 artifacts** are ingested: the opening prepublication clearance-stamp cover [[references/dow-uap-pr20-prepublication-clearance-2026-03|DoW-UAP-PR20]], the single-sighting mission-report [[references/dow-uap-d4-mission-arabian-gulf-2020|DoW-UAP-D4 (Arabian Gulf 2020)]], and the two-sighting mission-report [[references/dow-uap-d5-mission-arabian-gulf-2020|DoW-UAP-D5 (Arabian Gulf 2020)]].

This page exists so subsequent ingests have a stable target to cross-link to, and so the series-level inferences (provisional scope, theater coverage, document-class taxonomy, mission-report format) can be revised in place as the series is processed rather than re-derived each time.

## What "DoW" stands for — deferred

The abbreviation is **not resolved** from the only artifact ingested so far. Candidate expansions are catalogued at [[references/dow-uap-pr20-prepublication-clearance-2026-03#On the "DoW" filename prefix — explicitly deferred|DoW-UAP-PR20 § On the "DoW" filename prefix]]. The most-likely working hypothesis based on sibling-filename theater-and-document-class evidence is **Department of (the) Navy**, but no internal document evidence selects between candidates. ^[inferred] Final resolution awaits the next ingest in the series that carries an internal banner, FOIA case code, or originating-office header.

## Series-level filename signature (curator side)

The `sources/` directory carries 40 files with the prefix. Naming pattern (curator-applied — no internal-evidence anchor):

- `dow-uap-d<N>-<document-class>-<theater>-<period>.json` — appears to be the dominant pattern (39 of 40 files).
- `dow-uap-pr20.json` — the **lone `pr*`-prefixed file**; resolves to the DoD prepublication-clearance cover stamp (see [[references/dow-uap-pr20-prepublication-clearance-2026-03]]).

The split suggests **two artifact classes** in the release: the substantive `d*` documents and a small minority of `pr*` clearance-cover artefacts. ^[inferred] To be validated as the rest of the series is ingested.

## Document classes (inferred from filenames; not yet ingest-verified)

Three structurally distinct document classes are inferable from the `d*` filename payloads:

| Class | Filename signature | Count (est.) | Working description |
|---|---|---|---|
| Mission report | `*mission-report-*` | ~25 of 40 | Operational mission-level UAP encounter reports from a named theater + dated period |
| Range-fouler debrief | `*range-fouler-debrief-*` / `*range-fouler-*` | ~6 of 40 | Post-incident debriefs of "range fouler" encounters — Navy-aviation terminology for objects intruding on a training range |
| Other (email correspondence, launch summary, report) | `*email-correspondence-*` / `*launch-summary-*` / `*report-*` | ~7 of 40 | Mixed administrative / coordination / single-event artifacts |
| Prepublication clearance | `pr20` | 1 of 40 | The DOPSR cover stamp ([[references/dow-uap-pr20-prepublication-clearance-2026-03]]) |

The "range fouler" terminology is **Navy / Naval Aviation-specific** — it refers to objects/aircraft fouling a designated training range, a standing concept in carrier-air-wing range management. ^[inferred] Its appearance across multiple files in the series is the strongest filename-side indicator that the originating service is the Navy.

## Geographic coverage (inferred from filenames)

Listed in approximate frequency order:

- **Arabian Gulf / Persian Gulf / Strait of Hormuz / Gulf of Aden / Arabian Sea** — densest cluster (≥12 files); 2020–2024.
- **Iraq / Syria / United Arab Emirates / Middle East** — large cluster (≥9 files); 2016, 2022–2023.
- **Mediterranean Sea / Greece** — ~4 files; 2023–2024.
- **East China Sea / Japan / IndoPACOM / Pacific Time Zone** — ~5 files; 2023–2025.
- **Djibouti** — 1 file; 2025.
- **Iran** — 1 file; 2020.

Temporal span: ~2016 → ~2025. This places the series **chronologically downstream** of the [[entities/aaro|AARO]] mandate era and overlaps the active US-Navy UAP-reporting framework articulated by witnesses like [[entities/ryan-graves]]. ^[inferred]

## Date frame of containing release

The single ingested file carries a **10 Mar 2026** DoD prepublication clearance stamp ([[references/dow-uap-pr20-prepublication-clearance-2026-03]]). This is the **release-side timestamp**, not the document-event timestamp. Document events span 2016–2025. ^[inferred]

## Structural firsts the series will likely anchor (provisional)

Pending ingest of the substantive content:

- **First operational-era Navy-theater UAP-encounter cluster** in the wiki corpus. The existing corpus's modern witness-side anchor is [[references/usper-statement-2025]] (helicopter-orb encounter, single event); the DoW-UAP series would extend that anchor to a **multi-event multi-theater documented operational record** spanning roughly a decade. ^[inferred]
- **First range-fouler-debrief document class** in the corpus. Distinct artifact class from the mission-report family — to be characterised on ingest. ^[inferred]
- **First [[entities/aaro|AARO]]-era operational-intake corpus** — if AARO is the receiving authority for the series, this would be the wiki's first volume-class AARO-pipeline ingest. ^[inferred]
- **First DoD-prepublication-cleared corpus tranche** at this scale — the existing corpus carries declassified material from earlier eras (FBI HQ 62-83894, NARA RG 38/RG 341/RG 255), but DOPSR-cleared current-era operational material is a different release-pathway class. ^[inferred]

## Mission-report format (template anchored by `d4`, validated + extended by `d5`)

The first two substantive `d*` ingests ([[references/dow-uap-d4-mission-arabian-gulf-2020|DoW-UAP-D4]] and [[references/dow-uap-d5-mission-arabian-gulf-2020|DoW-UAP-D5]] — both filename-labeled "Arabian Gulf 2020") establish the working **structural template** for the ~25 mission-report files in the series. Elements **confirmed at N=2** (both files) below, with **`d5`-extended variations** explicitly noted:

- **Per-page header `# 1.4(a)`** — **Confirmed at N=2.** Recurs on every OCR'd page of both `d4` (5 pages) and `d5` (6 pages). This is the [Executive Order 13526](https://www.archives.gov/isoo/policy-documents/eo-13526.html) §1.4(a) classification-category marking (*military plans, weapons systems, or operations*). ^[inferred] Expected to recur across every `d*` mission-report and range-fouler file.
- **Header-only pages padded around substantive pages** — **Confirmed at N=2.** Pages 0–3 are header-only `# 1.4(a)` markings in both files. `d4` carries 1 substantive page (page 4); `d5` carries **2 substantive pages** (pages 4 + 5). The header-only-prefix is a banner artifact; substantive page count is per-report variable.
- **Sighting count is per-report variable** — **`d5`-extended.** A single `d*` file may carry **multiple GENTEXT/UAP segments** (`d5` has 2, separated by 8h 49m Zulu, in two different UTM zones). Working hypothesis: report length tracks the number of distinct sightings ingested into that report. ^[inferred] Range-fouler debriefs may show different patterns.
- **USMTF `GENTEXT/UAP` segment** — **Confirmed at N=2.** Substantive content sits inside a US Message Text Format general-text segment with `UAP` as the segment identifier. ^[inferred] Consistent with Navy / Joint formal-message conventions.
- **Portion marking `(S/REL)`** + **banner `SECRET/REL TO USA, FVEY`** — `(S/REL)` portion marking confirmed at N=2 (every sighting in both `d4` and `d5` carries it). Banner only captured in `d4` OCR (as `FVEV` — `Y → V` low-DPI confusion ^[inferred]); `d5` OCR does not capture the banner (likely cropped). Classification posture inferred consistent.
- **Witness-redaction pattern** — **`d5`-extended.** `d4` uses `PILOT: (b)(6)` block format. `d5` uses inline `[REDACTED]` for witness with one `(b)(6)` block. Both apply FOIA exemption b(6) (*personal-privacy*) to mask witness identity. The specific syntax (`PILOT:` block vs inline `[REDACTED]`) is per-report variable. ^[inferred] All `dow-uap-` material is pre-published-cleared per [[references/dow-uap-pr20-prepublication-clearance-2026-03]], so witness identities are systematically masked across the series.
- **MGRS coordinates** rather than lat/long; **knots** for velocity; **Zulu time** without a calendar date inside the substantive page — **Confirmed at N=2** (3 sightings total). The filename carries the year (`d4-…-2020`, `d5-…-2020`); GENTEXT bodies carry only Zulu times (`1258Z`, `1354Z`, `2243Z`) with no calendar date. **The filename year is the only date anchor** for these reports. ^[inferred]
- **Altitude reporting is sighting-variable** — **`d5`-extended.** `d4`'s sole sighting and `d5`'s Sighting B do **not** report altitude. `d5`'s Sighting A reports `FL160 TO FL170` (16,000–17,000 ft pressure altitude). Altitude is reported when the observation is sustained enough to derive it; brief sightings carry the explicit *"BRIEF OBSERVATION PRECLUDED UAP ALTITUDE ESTIMATES"* hedge (as in `d4`). ^[inferred]
- **Object count is sighting-variable** — **`d5`-extended.** `d5` Sighting B is the corpus's first multi-object datum (`2X POSS UAPS`). The `POSS` (possible) hedge is Navy-format hedging on positive UAP-class identification; absent in single-object reports of `d4` and `d5`-A.
- **Behavioral signatures so far span two sub-classes within brief-observation**: (a) **kinematic-anomaly** (speed-up + course-change) — `d4` (single, east, 321 kt), `d5`-B (multi, south, 278 kt); (b) **steady-state cruise at airliner-altitude band** — `d5`-A (40 kt at FL160-170; velocity-altitude mismatch with conventional platform envelopes). ^[inferred] No engagement-class signatures across N=2 reports / 3 datums.

### Filename-vs-internal-document discrepancy — **CONFIRMED at N=2** ^[ambiguous]

A **corpus-level observation confirmed across two consecutive `d*` ingests**: filename theater labels do **not** match internal MGRS coordinates. Both files filename-labeled "**Arabian Gulf 2020**" carry internal coordinates that decode **outside** the Arabian Gulf:

| File | Filename theater | Internal MGRS | Decoded region |
|---|---|---|---|
| `d4` | Arabian Gulf | `34SDG9041417044` | UTM 34S — Eastern Med / Aegean / NE Libya / Egypt |
| `d5`-A | Arabian Gulf | `34SCE7566990098` | UTM 34S — Eastern Med (same zone as d4) |
| `d5`-B | Arabian Gulf | `35TQK1580995057` | UTM 35T — Eastern Europe / Black Sea / Western Russia |
| *Arabian Gulf reference* | — | (would be UTM 39–40, band Q–R) | Persian Gulf / Strait of Hormuz |

**The hypothesis previously offered as `^[inferred]` (curator-applied filename labels are unreliable theater anchors) is now confirmed at N=2.** Going forward, ingests of `dow-uap-d*` files must **prefer internal MGRS coordinates as theater anchors** over curator filename labels. ^[inferred] See [[references/dow-uap-d5-mission-arabian-gulf-2020#Geographic decoding — coordinate vs. filename|D5 § Geographic decoding]] for the full N=2 decoding.

A **second observation surfaces in `d5`**: a single mission report can carry **two sightings in two different UTM zones** (here 34S Eastern Med and 35T Eastern Europe/Black Sea), separated by ~8h 49m. Working hypothesis: some `d*` files are **multi-theater transit-mission reports** or **multi-platform tasking rollups**. ^[inferred] To be characterized as more `d*` files are processed.

## Open questions

- Resolve "DoW" abbreviation (see above).
- Establish the FOIA case identifier, releasing component, and receiving FOIA-applicant party (if recoverable from internal headers in `d*` files).
- Confirm whether [[entities/aaro|AARO]] is the receiving / routing authority for the series, or whether the series originates from a different DoD-component intake pipeline.
- Confirm the `d*` / `pr*` artifact-class split with at least one more `pr*` file ingest.
- Characterise the "range fouler" document class as a structural artifact type — fields, witness conventions, release-redaction pattern.
- **Validate the mission-report template** above against the next 2–3 `d*` ingests.
- **Resolve the filename-theater-vs-internal-coordinate question** with at least one more `d*` ingest that carries an internal coordinate in the OCR.
- Confirm whether the per-page `# 1.4(a)` header recurs across all `d*` files (suggesting a banner artifact) or only across mission-report-class files specifically.

## See also

- [[references/dow-uap-pr20-prepublication-clearance-2026-03]] — Series's prepublication clearance-stamp cover artifact
- [[references/dow-uap-d4-mission-arabian-gulf-2020]] — First substantive `d*` mission report — establishes the format template (single-sighting)
- [[references/dow-uap-d5-mission-arabian-gulf-2020]] — Second substantive `d*` mission report — validates template, extends to multi-sighting + multi-theater + altitude reporting variants, confirms filename-vs-coordinate mismatch at N=2
- [[entities/aaro]] — Likely current-era DoD UAP receiving office
- [[entities/ryan-graves]] — Former US Navy F/A-18F pilot; modern Navy-aviation UAP-witness context for the series
- [[concepts/uap-aircraft-engagement]] — Modern Navy operational-encounter behavioral framing
- [[projects/uap/uap]]
