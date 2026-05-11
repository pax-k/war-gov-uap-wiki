---
title: DoW-UAP FOIA Release Series
category: entities
tags: [uap, organization, archive, dod, navy]
aliases: [DoW-UAP, dow-uap series]
sources: [sources/dow-uap-pr20.json, sources/dow-uap-d4-mission-report-arabian-gulf-2020.json]
summary: Provisional series-level anchor for the ~40-file "DoW-UAP" FOIA release tranche; mostly Navy-theater UAP mission reports and range-fouler debriefs 2016-2025, cleared through DoD prepublication review.
provenance:
  extracted: 0.25
  inferred: 0.72
  ambiguous: 0.03
base_confidence: 0.62
lifecycle: draft
lifecycle_changed: 2026-05-10
created: 2026-05-10T22:00:00Z
updated: 2026-05-11T04:00:00Z
---

# DoW-UAP FOIA Release Series

A **provisional series-level anchor** for the ~40-file FOIA release tranche whose source-file basenames carry the `dow-uap-` prefix. As of this writing, **2 of ~40 artifacts** are ingested: the opening prepublication clearance-stamp cover [[references/dow-uap-pr20-prepublication-clearance-2026-03|DoW-UAP-PR20]] and the first substantive mission-report [[references/dow-uap-d4-mission-arabian-gulf-2020|DoW-UAP-D4 (Arabian Gulf 2020)]].

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

## Mission-report format (first substantive observation, from `d4`)

The first substantive `d*` ingest ([[references/dow-uap-d4-mission-arabian-gulf-2020|DoW-UAP-D4 — Arabian Gulf 2020]]) establishes the working **structural template** for the ~25 mission-report files in the series. To be validated and revised in place as more `d*` files are processed:

- **Per-page header `# 1.4(a)`** — recurs on every OCR'd page. This is the [Executive Order 13526](https://www.archives.gov/isoo/policy-documents/eo-13526.html) §1.4(a) classification-category marking (*military plans, weapons systems, or operations*). ^[inferred] Expected to recur across every `d*` mission-report and range-fouler file.
- **Sparse OCR content** — `d4` carries 5 OCR pages but only **1 substantive page** (the rest are header-only). The underlying PDF (29 KB) is correspondingly small. Working hypothesis: a single-encounter mission report = ~5 OCR pages of which 1 carries the GENTEXT/UAP body. ^[inferred] Range-fouler debriefs and multi-event reports may carry larger bodies.
- **USMTF `GENTEXT/UAP` segment** — substantive content sits inside a US Message Text Format general-text segment with `UAP` as the segment identifier. ^[inferred] This is consistent with Navy / Joint formal-message conventions.
- **Portion marking `(S/REL)`** + **banner `SECRET/REL TO USA, FVEY`** — Five Eyes releasability. (The `d4` OCR captures the banner as `FVEV`; the `Y → V` confusion is plausible at this DPI. ^[inferred])
- **Witness-redaction pattern `PILOT: (b)(6)`** + a second `(b)(6)` line — FOIA exemption b(6) (*personal-privacy*) masks the pilot identity (and likely a second witness or airframe ID). ^[inferred] Expect this pattern to recur — the entire `dow-uap-` corpus is pre-published-cleared per [[references/dow-uap-pr20-prepublication-clearance-2026-03]], so witness identities are systematically masked.
- **MGRS coordinates** rather than lat/long; **knots** for velocity; **Zulu time** without a calendar date inside the substantive page. ^[inferred] The filename carries the year (`d4-…-2020`); the GENTEXT body in `d4` carries only `1258Z` with no date — meaning **the filename year may be the only date anchor** for some reports if no header survives the OCR.

### Filename-vs-internal-document discrepancy ^[ambiguous]

A **first-instance corpus-level observation**: in `d4`, the filename labels the theater "**Arabian Gulf**" but the internal MGRS coordinate `34SDG9041417044` decodes to UTM zone 34 / band S — i.e. the **Eastern Mediterranean / Aegean / NE Libya / Egypt** area, **not** the Persian Gulf (which falls in UTM zones 39–40). See [[references/dow-uap-d4-mission-arabian-gulf-2020#Coordinate vs. filename — geographic ambiguity|D4 § Coordinate vs. filename]] for the full decoding and candidate reconciliations. ^[inferred]

This means the **curator-applied filename theater labels may not be reliable anchors** to the internal-document content. If a second `d*` ingest shows the same kind of mismatch, the working hypothesis shifts from *"OCR error in this one file"* to *"curator labels are unreliable theater anchors and must be corroborated against in-document coordinates."* ^[inferred] Tracking this explicitly.

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
- [[references/dow-uap-d4-mission-arabian-gulf-2020]] — First substantive `d*` mission report — establishes the format template
- [[entities/aaro]] — Likely current-era DoD UAP receiving office
- [[entities/ryan-graves]] — Former US Navy F/A-18F pilot; modern Navy-aviation UAP-witness context for the series
- [[concepts/uap-aircraft-engagement]] — Modern Navy operational-encounter behavioral framing
- [[projects/uap/uap]]
