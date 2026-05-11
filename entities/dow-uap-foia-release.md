---
title: DoW-UAP FOIA Release Series
category: entities
tags: [uap, organization, archive, dod, navy]
aliases: [DoW-UAP, dow-uap series]
sources: [sources/dow-uap-pr20.json, sources/dow-uap-d4-mission-report-arabian-gulf-2020.json, sources/dow-uap-d5-mission-report-arabian-gulf-2020.json, sources/dow-uap-d52-email-correspondance-na-august-2024.json]
summary: Provisional series-level anchor for the ~40-file "DoW-UAP" FOIA release tranche; multi-service (Navy + USAF attested at N=3) UAP mission reports, range-fouler debriefs, and disclosure-workflow emails 2016-2025, cleared through DoD prepublication review.
provenance:
  extracted: 0.23
  inferred: 0.74
  ambiguous: 0.03
base_confidence: 0.62
lifecycle: draft
lifecycle_changed: 2026-05-10
created: 2026-05-10T22:00:00Z
updated: 2026-05-11T06:00:00Z
---

# DoW-UAP FOIA Release Series

A **provisional series-level anchor** for the ~40-file FOIA release tranche whose source-file basenames carry the `dow-uap-` prefix. As of this writing, **4 of ~40 artifacts** are ingested: the opening prepublication clearance-stamp cover [[references/dow-uap-pr20-prepublication-clearance-2026-03|DoW-UAP-PR20]], the single-sighting mission-report [[references/dow-uap-d4-mission-arabian-gulf-2020|DoW-UAP-D4 (Arabian Gulf 2020)]], the two-sighting mission-report [[references/dow-uap-d5-mission-arabian-gulf-2020|DoW-UAP-D5 (Arabian Gulf 2020)]], and the **first non-mission-report artifact** — the tear-line clearance email thread [[references/dow-uap-d52-email-na-2024|DoW-UAP-D52 (15 AF / DET 1, 31 Oct 2024 sighting)]].

This page exists so subsequent ingests have a stable target to cross-link to, and so the series-level inferences (provisional scope, theater coverage, document-class taxonomy, mission-report format) can be revised in place as the series is processed rather than re-derived each time.

## What "DoW" stands for — deferred (Navy hypothesis weakened at N=4)

The abbreviation is **not resolved** from the artifacts ingested so far. Candidate expansions are catalogued at [[references/dow-uap-pr20-prepublication-clearance-2026-03#On the "DoW" filename prefix — explicitly deferred|DoW-UAP-PR20 § On the "DoW" filename prefix]].

**At N=4 ingests** the *"Department of the Navy"* working hypothesis is **weakened but not refuted**. The first internal-document originating-unit evidence in the series — [[references/dow-uap-d52-email-na-2024|DoW-UAP-D52]]'s `15 AF / DET 1` line — is **USAF, not Navy**. ^[inferred] This makes the *originating-component* "Department of the Navy" read implausible as an *exclusive* claim over the series content (the series carries multi-service material). It is still compatible with a *case-code or FOIA-release-tracking* interpretation in which the releasing component is DoN even though originating units span multiple services. ^[inferred]

Working revised view: treat `DoW` as a **release-tracking convention** rather than an originating-component initialism. ^[inferred] Final resolution awaits the next ingest that carries an internal banner, FOIA case code, or originating-office header that names the releasing component.

## Series-level filename signature (curator side)

The `sources/` directory carries 40 files with the prefix. Naming pattern (curator-applied — no internal-evidence anchor):

- `dow-uap-d<N>-<document-class>-<theater>-<period>.json` — appears to be the dominant pattern (39 of 40 files).
- `dow-uap-pr20.json` — the **lone `pr*`-prefixed file**; resolves to the DoD prepublication-clearance cover stamp (see [[references/dow-uap-pr20-prepublication-clearance-2026-03]]).

The split suggests **two artifact classes** in the release: the substantive `d*` documents and a small minority of `pr*` clearance-cover artefacts. ^[inferred] To be validated as the rest of the series is ingested.

## Document classes (4 of 4 ingested classes now characterised; 4 inferable from filenames)

Four structurally distinct document classes are inferable from the `d*` filename payloads; **two are now ingest-verified** at N≥1:

| Class | Filename signature | Count (est.) | Status | Working description |
|---|---|---|---|---|
| Mission report | `*mission-report-*` | ~25 of 40 | **ingest-verified at N=2** ([[references/dow-uap-d4-mission-arabian-gulf-2020\|d4]], [[references/dow-uap-d5-mission-arabian-gulf-2020\|d5]]) | Operational mission-level UAP encounter reports from a named theater + dated period — USMTF GENTEXT/UAP segment + per-page `# 1.4(a)` header + portion marking `(S/REL)` |
| Range-fouler debrief | `*range-fouler-debrief-*` / `*range-fouler-*` | ~6 of 40 | filename-inferred only | Post-incident debriefs of "range fouler" encounters — Navy-aviation terminology for objects intruding on a training range |
| Email correspondence (disclosure-workflow) | `*email-correspondence-*` | ~3 of 40 (`d50`, `d51`, `d52`) | **ingest-verified at N=1** ([[references/dow-uap-d52-email-na-2024\|d52]]) | Intra-DoD email threads negotiating UNCLASS tear-line data points (month/day/year approvals) for a paired content artifact; SECRET//NOFORN with embedded UNCLASS tear lines; FOIA `(b)(6)` redaction on both correspondents |
| Other content document | `*launch-summary-*` / `*report-*` | ~4 of 40 | filename-inferred only | Mixed administrative / coordination / single-event artifacts |
| Prepublication clearance | `pr20` | 1 of 40 | **ingest-verified at N=1** ([[references/dow-uap-pr20-prepublication-clearance-2026-03]]) | The DOPSR cover stamp |

The "range fouler" terminology is **Navy / Naval Aviation-specific** — it refers to objects/aircraft fouling a designated training range, a standing concept in carrier-air-wing range management. ^[inferred] At N=4 ingests, the `d52` email confirms the series carries **multi-service material** (USAF unit `15 AF / DET 1` is the first internal-document originating-unit evidence). The range-fouler material may still be Navy-originated specifically; the series as a whole is now multi-service. ^[inferred]

### Email-correspondence document class — anchored at N=1 ([[references/dow-uap-d52-email-na-2024|d52]])

The `*-email-correspondence-*` document class is a **second-order metadata artifact** within the series: emails about the declassification of *other* documents, not UAP-narrative content directly. Structural elements observed at N=1:

- **Reverse-chronological thread layout** — newest reply on top page, older request on bottom.
- **Dual classification banners** — full thread at `SECRET//NOFORN`, embedded tear line at `//UNCLASSIFIED//`.
- **Two-role disclosure-workflow loop** — *PAROC Intel Data Analysis Technician* (data originator) ↔ *Information Disclosure Analyst* (clearance reviewer).
- **Per-data-point iterative clearance** — month, day, and year approved separately; this loop is the *pre-terminal* counterpart to the *whole-document terminal* DOPSR clearance attested in [[references/dow-uap-pr20-prepublication-clearance-2026-03|PR20]]. ^[inferred]
- **Witness-side redaction (FOIA `b(6)`)** applied **also to correspondents** — not just to UAP witnesses, but to the DoD personnel handling the disclosure pipeline. The release scheme masks the whole human chain.
- **Null `image_base64` content in the OCR JSON** — bounding boxes preserved but image bytes discarded. Banners and stamps rendered as images are lost in this OCR pass.
- **Filename date token unreliable** — `d52` filename says `august-2024`, internal date is `31 OCT 24` ^[inferred]. **Extends the d4/d5 filename-vs-internal-document discrepancy** from the theater axis to the **date axis**: curator-applied filename tokens are unreliable on multiple axes.

The `d50` and `d51` siblings (also `*-email-correspondence-*`) are queued for ingest and will validate or extend this class template at N=2 / N=3.

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

- Resolve "DoW" abbreviation (Navy-originating hypothesis weakened by `d52` USAF unit evidence; see above).
- Establish the FOIA case identifier, releasing component, and receiving FOIA-applicant party (if recoverable from internal headers).
- Confirm whether [[entities/aaro|AARO]] is the receiving / routing authority for the series, or whether the series originates from a different DoD-component intake pipeline.
- Resolve **PAROC** initialism (introduced in `d52`); resolve whether *Information Disclosure Analyst* sits inside DOPSR, USAF FOIA, AARO, or a separate component.
- Confirm the email-correspondence document class at N≥2 (queue: `d50`, `d51`).
- Confirm the `d*` / `pr*` artifact-class split with at least one more `pr*` file ingest.
- Characterise the "range fouler" document class as a structural artifact type — fields, witness conventions, release-redaction pattern.
- **Validate the mission-report template** above against the next 2–3 mission-report ingests.
- **Resolve the filename-theater-vs-internal-coordinate question** with at least one more `d*` ingest that carries an internal coordinate.
- **Resolve the filename-date-vs-internal-date question** (introduced by `d52`: filename `august-2024` vs internal `31 OCT 24`).
- Confirm whether the per-page `# 1.4(a)` header recurs across all mission-report `d*` files or only a subset.
- **Confirm multi-service originating-unit pattern** at N≥4: is the series a release-side gather across services, or does the next ingest revert to Navy-only?

## See also

- [[references/dow-uap-pr20-prepublication-clearance-2026-03]] — Series's prepublication clearance-stamp cover artifact (whole-document terminal clearance)
- [[references/dow-uap-d4-mission-arabian-gulf-2020]] — First substantive `d*` mission report — establishes the format template (single-sighting)
- [[references/dow-uap-d5-mission-arabian-gulf-2020]] — Second substantive `d*` mission report — validates template, extends to multi-sighting + multi-theater + altitude reporting variants, confirms filename-vs-coordinate mismatch at N=2
- [[references/dow-uap-d52-email-na-2024]] — First non-mission-report artifact — tear-line clearance email thread; anchors the email-correspondence document class; supplies first USAF-originating-unit evidence (15 AF / DET 1)
- [[entities/aaro]] — Likely current-era DoD UAP receiving office
- [[entities/ryan-graves]] — Former US Navy F/A-18F pilot; modern Navy-aviation UAP-witness context for the series
- [[concepts/uap-aircraft-engagement]] — Modern Navy operational-encounter behavioral framing
- [[concepts/orb-phenomenon]] — Orb-class morphology framing (d52's 2-hour sustained orb is a different sub-class from d4/d5 brief observations)
- [[projects/uap/uap]]
