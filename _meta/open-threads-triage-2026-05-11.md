---
title: Open Threads Triage — 2026-05-11
category: _meta
tags: [meta/triage, project/uap]
sources: [.manifest.json, vault-wide grep]
created: 2026-05-11
updated: 2026-05-11
summary: One-shot mid-pipeline triage of all Open threads / Open questions sections before source 52 of 85.
provenance: vault-wide grep + manifest cross-reference, 2026-05-11
base_confidence: high
lifecycle: stable
---

# Open Threads Triage — 2026-05-11

## Summary

- Total bullets surveyed: 1401
- genuinely-open: 1385
- forward-anchored: 2
- stale: 14
- repair-backlog (closed): 0
- contradicts: 0
- Heading casings normalized: 17
- Pages touched: 30

## Scope

One-shot mid-pipeline pass executed immediately before source 52 of 85 (`sources/dow-uap-d54-mission-report-mediterranean-sea-na.json`). Sources 1-51 already ingested. The reactive Step 1c policy in the per-source ingest pipeline only touches QMD-hit pages; this triage is the proactive sweep.

Repair scopes consulted (from `.manifest.json`):

- `255_413270_ufo's_and_defense_what_should_we_prepare_for.json` — COMETA back-half pp 47-93 (repaired 2026-05-11T07:30Z)
- `38_143685_box7_incident_summaries_101-172.json` — mid-file triage gap at Inc 112/130/151 (repaired 2026-05-11T10:30Z)
- `65_hs1-834228961_62-hq-83894_section_10.json` — p45 youth correspondence + p92 international researcher roster (repaired 2026-05-11T09:00Z)

No open-thread bullets in the vault explicitly reference the now-repaired gaps; all three repair scopes have been folded internally into their anchor pages (`references/cometa-report-1999.md`, `references/project-sign-incident-summaries-101-172.md`, `references/fbi-hq-62-83894-section-10.md`). No bucket-4 closures applied.

## Forward-anchored (B bullets)

| Page | Bullet (truncated) | Expected source |
|---|---|---|
| [[entities/dow-uap-foia-release]] | "Confirm the email-correspondence document class at N≥2 (queue: `d50`, `d51`)." | `sources/dow-uap-d50-email-correspondence-indopacom-april-2025.json` |
| [[entities/dow-uap-foia-release]] | "Characterise the "range fouler" document class as a structural artifact type — fields, witness conventions, release-reda..." | `sources/dow-uap-d44-range-fouler-arabian-sea-october-2020.json` |

## Stale (C bullets)

| Page | Bullet (truncated) | Possibly answered by |
|---|---|---|
| [[concepts/cia-iac-uap-engagement]] | "**Track later IAC / USIB UAP discussions** in queued FBI sections 9-10 — section 8 closes Nov 1957, post-Sputnik; subseq..." | [[references/fbi-hq-62-83894-section-9]] |
| [[entities/aerial-phenomena-research-organization]] | "**Track APRO's later FBI-corpus appearances** in queued sections 9-10 of [[entities/fbi-hq-62-83894-file\|62-HQ-83894]] ..." | [[references/fbi-hq-62-83894-section-9]] |
| [[entities/d-arthur-byrnes-jr]] | "**Identify whether Byrnes filed any follow-on serial in 62-HQ-83894** (e.g. serial 449) on subsequent investigative work..." | [[references/fbi-hq-62-83894-serial-449]] |
| [[entities/nicap]] | "**NICAP-FBI direct correspondence**: queued sections 8-10 of the main file may yield Director-level NICAP correspondence..." | [[references/fbi-hq-62-83894-section-8]] |
| [[entities/wilbur-b-smith]] | "**Watch for additional Canadian-Project-Magnet correlates** in the wiki's queued sections 9-10 of [[entities/fbi-hq-62-8..." | [[references/fbi-hq-62-83894-section-9]] |
| [[references/fbi-hq-62-83894-section-5]] | "**Locate [[references/fbi-bureau-bulletin-57-1947\|Bureau Bulletin No. 57]] (1 Oct 1947)** — the closure-instrument refe..." | [[references/fbi-hq-62-83894-section-3]] |
| [[references/fbi-hq-62-83894-section-5]] | "**Identify "Coulter" / "Coulter from Denver Ford agency"** named in serial 203 OSI TWX as the Aztec-myth source — does t..." | [[references/fbi-hq-62-83894-section-10]] |
| [[references/fbi-hq-62-83894-section-7]] | "**Ingest section 6** to bridge sections 5 and 7 — recover serials 246-301 (Sep 1950 - Aug 1952), including serial 273 (M..." | [[references/fbi-hq-62-83894-section-6]] |
| [[references/fbi-hq-62-83894-section-8]] | "**Locate the NACA→NASA transition's effect on UAP institutional posture** — section 9-10 likely capture how NACA's Dryde..." | [[references/fbi-hq-62-83894-section-9]] |
| [[references/fbi-hq-62-83894-section-9]] | "**Section 6 (serials 246-301)** and **section 10** remain unscanned. Section 6 covers ~Sep 1950 – Aug 1952 (the [[concep..." | [[references/fbi-hq-62-83894-section-6]] |
| [[references/fbi-hq-62-83894-sub-a]] | "**Helena MT FBI investigation** (page 46, 1953-54) — explicit press citation of FBI investigation contradicts BB-57 stan..." | [[references/fbi-hq-62-83894-section-8]] |
| [[references/sighting-frances-swan-1954-07]] | "**Watch for the Swan case's later disposition** in the wiki's queued sections 9-10 of [[entities/fbi-hq-62-83894-file\|6..." | [[references/fbi-hq-62-83894-section-9]] |
| [[references/sighting-killian-dc6-1959-02-24]] | "**NICAP follow-up** — did Killian or the passengers contact NICAP under [[entities/delmer-s-fahrney\|Fahrney]]? Sub-A's ..." | [[references/fbi-hq-62-83894-section-8]] |
| [[references/sighting-socorro-nm-1964-04-24]] | "**Locate any FBI follow-on serial in 62-HQ-83894** by Byrnes or the Albuquerque field office — the queued ingest still i..." | [[references/fbi-hq-62-83894-serial-449]] |

## Repair-backlog closed (D bullets)

_(none — all three repairs in `.manifest.json` (cometa pp 47-93, box7 101-172 mid-file, section_10 mid-file) had been folded into their anchor pages by the repair pass; no orphan bullets in other pages referenced these gaps explicitly at survey time)_

## Genuinely open (1385 bullets) — for future ingest discovery

These bullets remain live. They are concentrated across 268 pages. Most are external-research / external-document targets (NARA series locators, named-officer identifications, follow-up FOIA traces) that lie outside the current `sources/` queue and will not be answered by any of the remaining 34 pending sources.

Top-bullet pages (page-grouped one-liners):

- [[projects/uap/uap]] (78 bullets) — Locate / ingest **A.D.I.(K) Report No. 562/1944 ¶128–129** (the Flak Bombe description Fel...
- [[references/fbi-hq-62-83894-serial-449]] (15 bullets) — **OCR digit-confusion on the cover slip** — the cover OCR'd as `G2-HQ-33394` rather than `...
- [[entities/fbi]] (14 bullets) — Locate / ingest **other serials in FBI Detroit file 100-18221** — the marker `100-18221-84...
- [[entities/dow-uap-foia-release]] (13 bullets) — Resolve "DoW" abbreviation (Navy-originating hypothesis weakened by `d52` USAF unit eviden...
- [[references/dos-cable-mexico-2023-09]] (10 bullets) — Confirm `SALAZAR` (signature on MEXICO 2544) = **Ambassador Ken Salazar**, US Ambassador t...
- [[references/iaf-ir-193-55-russell-1955]] (10 bullets) — Locate **USAIRA Cable C-103, 13 Oct 1955** as a standalone TS-classified message (the body...
- [[references/nasa-uap-d1-apollo-12-transcript-1969]] (10 bullets) — Locate the **complete Apollo 12 air-to-ground voice loop** to verify whether the d1 OCR bu...
- [[references/usafe-tt1524-1948-11]] (10 bullets) — Locate any **Cabell reply** to USAFE 14 ("What are your reactions?"). The bundle contains ...
- [[concepts/cosmic-ray-light-flashes]] (9 bullets) — Locate the **ALFMED experiment final report** (post-Apollo 17 debrief publication) and the...
- [[entities/apollo-11]] (9 bullets) — Locate the **complete Apollo 11 Technical Crew Debriefing Vol I (251 pp) and Vol II (216 p...
- [[entities/fbi-hq-62-83894-file]] (9 bullets) — **Resolve file function** further from later serials (sections 1–10, sub_a). Reassess this...
- [[references/fbi-detroit-100-26505-krasuski-1957]] (9 bullets) — Locate any **USAF / Project BLUE BOOK** parallel case file on Krasuski (BLUE BOOK opened 1...
- [[references/fbi-hq-62-83894-section-3]] (9 bullets) — **Recover the literal text of BB-57** — the proposed Bulletin attached to the Ladd 25 Sep ...
- [[references/fbi-hq-62-83894-serial-220]] (9 bullets) — **Locate the FBI Vault entry** for 62-HQ-83894 to recover the formal title and date range....
- [[references/fbi-hq-62-83894-serial-403]] (9 bullets) — **What is 62-HQ-83894?** Topic / clearinghouse file on civilian UAP-research-as-public-dis...
- [[references/fbi-hq-62-83894-serial-438]] (9 bullets) — **Confirm `62-83894-738` vs `62-83894-438`** — page 38 footer reads `738` while page 0 cov...
- [[references/nasa-pao-t-00763-r1b-gemini-7-1965]] (9 bullets) — Locate the **NASA mission transcript** for GT-7 day 1, ~04:24 MET, in [NTRS / NASA Technic...
- [[references/nasa-uap-d4-apollo-11-technical-crew-debriefing-1969]] (9 bullets) — Locate the **complete Apollo 11 Technical Crew Debriefing Vol I and Vol II** to verify (a)...
- [[entities/nasa]] (8 bullets) — Whether NASA's release-by-default posture in 1965 was **routinely consulted** with USAF in...
- [[references/fbi-hq-62-83894-section-5]] (8 bullets) — **Ingest sections 3-4** to recover serials 101-185 — including the 62-83894-141-160 Bureau...
- [[references/fbi-hq-62-83894-section-8]] (8 bullets) — **Identify the Wilbur B. Smith / Project Magnet correlate** — Smith's unofficial 24-26 Jul...
- [[references/nasa-apollo-17-science-debriefing-1973]] (8 bullets) — **Identify "HENRY" definitively.** Working hypothesis is **Richard C. Henry** (Johns Hopki...
- [[references/nasa-apollo-17-technical-crew-debriefing-1973]] (8 bullets) — Locate the **complete MSC-07631 Apollo 17 Technical Crew Debriefing** to verify whether ot...
- [[references/nasa-uap-d7-skylab-technical-crew-debriefing-1973]] (8 bullets) — Identify the **specific satellite or debris object** the SL-3 crew observed (~Sep 1973). C...
- [[entities/apollo-17]] (7 bullets) — Locate the **complete MSC-07631 Apollo 17 Technical Crew Debriefing** (the corpus has only...

_(243 more pages have genuinely-open bullets; full inventory in `/tmp/classified.json` at triage time.)_

## Contradicts (E bullets)

_(none)_

## Method notes

- **Classifier**: keyword-based. Bucket-2 (forward-anchored) restricted to bullets with explicit DoW-UAP context AND a pending d-number not appearing inside a range listing (e.g. excludes `d1-d75` enumerations). Bucket-3 (stale) keyed on `queued section N`, `section N remain unscanned`, `section N likely capture`, `ingest section N` patterns where N ∈ {1..10} (all FBI HQ 62-83894 sections are now in the vault), plus serial-449 (now ingested).
- **Bucket-4 (repair-backlog)** was conservative: only the three named repair scopes were checked; no bullet across 268 pages explicitly named the repaired-gap content (pp 47-93 of COMETA, Inc 112/130/151 of box7, p45/p92 of section_10), so no closures applied.
- **QMD MCP** was not invoked because the lexical pass surfaced sufficient stale candidates; remaining ambiguous bullets defaulted to bucket-1 per task spec ("better silent than wrong").
- **Heading normalization**: 17 pages carried `## Open Threads` / `## Open Questions` (title case); all normalized to sentence case `## Open threads` / `## Open questions`.
