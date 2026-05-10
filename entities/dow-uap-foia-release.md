---
title: DoW-UAP FOIA Release Series
category: entities
tags: [uap, organization, archive, dod, navy]
aliases: [DoW-UAP, dow-uap series]
sources: [sources/dow-uap-pr20.json]
summary: Provisional series-level anchor for the ~40-file "DoW-UAP" FOIA release tranche; mostly Navy-theater UAP mission reports and range-fouler debriefs 2016-2025, cleared through DoD prepublication review.
provenance:
  extracted: 0.20
  inferred: 0.78
  ambiguous: 0.02
base_confidence: 0.62
lifecycle: draft
lifecycle_changed: 2026-05-10
created: 2026-05-10T22:00:00Z
updated: 2026-05-10T22:00:00Z
---

# DoW-UAP FOIA Release Series

A **provisional series-level anchor** for the ~40-file FOIA release tranche whose source-file basenames carry the `dow-uap-` prefix. As of this writing, only the prepublication clearance-stamp cover artifact [[references/dow-uap-pr20-prepublication-clearance-2026-03|DoW-UAP-PR20]] has been ingested into the wiki — the rest of the series is queued.

This page exists so subsequent ingests have a stable target to cross-link to, and so the series-level inferences (provisional scope, theater coverage, document-class taxonomy) can be revised in place as the series is processed rather than re-derived each time.

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

## Open questions

- Resolve "DoW" abbreviation (see above).
- Establish the FOIA case identifier, releasing component, and receiving FOIA-applicant party (if recoverable from internal headers in `d*` files).
- Confirm whether [[entities/aaro|AARO]] is the receiving / routing authority for the series, or whether the series originates from a different DoD-component intake pipeline.
- Confirm the `d*` / `pr*` artifact-class split with at least one more `pr*` file ingest.
- Characterise the "range fouler" document class as a structural artifact type — fields, witness conventions, release-redaction pattern.

## See also

- [[references/dow-uap-pr20-prepublication-clearance-2026-03]] — Series's prepublication clearance-stamp cover artifact (currently the only ingested file)
- [[entities/aaro]] — Likely current-era DoD UAP receiving office
- [[entities/ryan-graves]] — Former US Navy F/A-18F pilot; modern Navy-aviation UAP-witness context for the series
- [[projects/uap/uap]]
