---
title: "FBI HQ File 62-HQ-83894"
category: entities
tags: [fbi, organization, primary-source, archive, uap]
sources: [sources/65_hs1-834228961_62-hq-83894_serial_403.json, sources/65_hs1-834228961_62-hq-83894_serial_220.json]
summary: FBI Headquarters Class-62 (administrative miscellaneous) file 62-HQ-83894 — multi-channel UAP-topic accumulation file at FBI HQ spanning at least 1950–1956; 17-serial wiki ingest series, 2 of 17 ingested (220, 403).
provenance:
  extracted: 0.45
  inferred: 0.5
  ambiguous: 0.05
base_confidence: 0.7
lifecycle: draft
lifecycle_changed: 2026-05-10
created: 2026-05-10T23:55:00Z
updated: 2026-05-10T23:58:00Z
---

# FBI HQ File 62-HQ-83894

A large, multi-year **FBI Headquarters file** under Class **62** (the FBI's catch-all *"administrative miscellaneous"* classification). ^[inferred] Indexed and serialized at FBI HQ in Washington — distinct from the field-office 100-class case files in the wiki's existing FBI corpus (e.g. Detroit `100-26505`, Detroit `100-18221`). ^[inferred] Declassification of the file's content is *"derived from the FBI Automatic Declassification Guide, issued 24 May 2007"*. ^[extracted]

This page is the **parent-file hub** for a planned **17-serial wiki ingest series**. Two serials are now ingested: **serial 220 (Apr 1950)** and **serial 403 (Sep 2022 release tranche of a 1956 artifact)**. The remaining ~15 serials (164, 438, 449, plus sections 1–10 and sub_a) will be ingested in subsequent passes.

## What 62-HQ-83894 appears to be — refined from 1 to 2 serials

From **serial 403 alone**, the most economical reading was that 62-HQ-83894 functions as a **content-monitoring / topic-clearinghouse file** at FBI HQ — i.e. a file in which HQ clips and serializes publicly-available materials (book jackets, magazine articles, newspaper clippings) about a topic the Bureau is tracking. ^[inferred]

**Serial 220 broadens this reading without contradicting it.** The serial-220 morphology is:

- An **unsolicited inbound foreign-language civilian saucer-letter** (Spanish, from Veracruz, Mexico, 19 Mar 1950) by [[entities/miguel-angel-garcia-macias|Miguel Ángel García Macías]];
- An **enclosed Mexican-newspaper clipping** reporting a photographed UAP sighting at Durango (18 Mar 1950, [[entities/german-horacio-robles-jr|Germán Horacio Robles Jr.]]'s photographs — see [[references/sighting-durango-mexico-1950-03]]);
- An **FBI in-house English translation** by Mrs. Sophia Saliba (no entity page warranted on the available evidence);
- The sender's **hand-drawn diagrams** of his proposed propulsion / stability mechanism;
- The Records Center cover slip — *DO NOT DESTROY*, FOIPA `#129A982`, declass 2007 Guide.

This is **content accumulation, not investigation** — the FBI's only operational gesture is **filing + translation**. ^[inferred] No FD-302, no SAC routing slip, no name-trace, no analytical narrative.

The two-serial spread therefore supports a **multi-channel UAP-topic accumulation file** reading: ^[inferred]

| Channel | Serial | Year | Content type |
|---|---|---|---|
| **(a) Clipped public publication** | 403 | 1956 | Publisher's book jacket of [[references/barker-1956-they-knew-too-much\|Barker's *They Knew Too Much About Flying Saucers*]] |
| **(b) Unsolicited inbound civilian correspondence** (foreign-language, FBI in-house translated) | 220 | Apr 1950 (intake) | Spanish-language saucer letter + enclosed Mexican press clipping + sender's diagrams |

The "topic-clearinghouse" framing **survives**; the **intake-channel count grows from 1 to 2**. The file is best read as accumulating **whatever UAP-topic paper crossed HQ's desk** — across multiple intake routes, across multiple decades, with no per-serial investigative work product. ^[inferred] Plausible additional channels the remaining serials may surface:

- HQ-side clipping of magazine / journal / newspaper articles (an extension of channel (a));
- Citizen letters routed via the White House (analogue of the [[references/fbi-detroit-100-26505-krasuski-1957|1957 Krasuski Detroit case]], but at HQ);
- US-citizen unsolicited mail (a domestic counterpart to channel (b)); ^[inferred]
- Inter-agency forwards (USAF, CIA, DOS) of UAP material that would naturally accumulate at HQ. ^[inferred]
- Files about specific individuals (e.g. Barker himself) folded into the topic file. ^[inferred]

The file's **date span is now 1950 → 1956 (≥ 6 years)** ^[inferred], with serial-number gaps suggesting many more serials originated across many years. ^[inferred]

## Provenance and filing

| Filing field | Value | Source |
|---|---|---|
| **Class** | 0062 (administrative miscellaneous) ^[inferred] | Records Center cover slips on serials 220 + 403; serial 220 cell OCR'd `0052` ^[ambiguous] |
| **Case** | 83894 | both cover slips |
| **Bureau / field office** | HQ (FBI HQ) | both cover slips — filed at FBI Central Records Center, HQ |
| **Sub** | (none) | both cover slips |
| **Vol** | `1` on serial 220; (blank) on serial 403 | possible volume-organized file ^[inferred] |
| **Highest known serial** | ≥ 449 ^[inferred] | scheduled-ingest set names 164, 220, 403, 438, 449 plus sections 1–10 + sub_a |
| **Earliest known serial date** | Apr 1950 (serial 220 intake stamp) ^[extracted] | FBI New York stamp on serial 220 |
| **Latest known serial date** | 1956 (serial 403's enclosed Barker book) ^[inferred] | Barker book publication date (1956); the FBI clipping itself is undated within the artifact |
| **Declassification authority** | FBI Automatic Declassification Guide, 24 May 2007 | both cover slips |
| **Records Center markers** | serial 220: FOIPA `#129A982` + processing tag `8/11/12 74164 RRP003IXG6`; serial 403: DIPA `#1142292` + processing tag `9/18/22 6771 RRP00A/1WL` | The **FOIPA vs DIPA** difference suggests **per-serial release-tranche** processing rather than a single bulk release. ^[inferred] |
| **Secondary-marker scheme** | serial 220: `62-HQ-83894-EBF 220 EBF`; serial 403: `62-HQ-83894-E483` | Two distinct secondary-marker formats — possibly per-tranche processing convention ^[inferred] |

The filename pattern `65_hs1-834228961_62-hq-83894_serial_<NNN>.json` for the source materials on disk matches the FBI Vault / `vault.fbi.gov` filename convention for declassified serials. ^[inferred] The `65_hs1-` prefix is consistent with the convention used on the prior FBI source `65_hs1-101634279_100-de-18221_serial_844.json` (= file 100-DE-18221 serial 844, Detroit) — but the file class (62 vs 100) and bureau (HQ vs Detroit) differ. ^[inferred]

## Serials in this file

| Serial | Status | Type | Wiki anchor |
|---|---|---|---|
| **220** | **Ingested 2026-05-10 (this ingest)** | **FBI Records Center cover slip + unsolicited Spanish-language Mexican civilian saucer-letter (García Macías, Veracruz, 19 Mar 1950) + FBI in-house English translation + enclosed Mexican-newspaper clipping (Robles Jr. Durango photographs, 18 Mar 1950) + sender diagrams** | [[references/fbi-hq-62-83894-serial-220]] |
| **403** | Ingested 2026-05-10 | FBI Records Center cover slip + clipped publisher's book jacket — Gray Barker, *They Knew Too Much About Flying Saucers*, University Books NYC, 1956 | [[references/fbi-hq-62-83894-serial-403]] |
| 164 | Queued | unknown | — |
| 438 | Queued | unknown | — |
| 449 | Queued | unknown | — |
| Sections 1–10 + sub_a | Queued | unknown | — |

The serial-403 / serial-220 / serial-164 / serial-438 / serial-449 spread implies the file holds **at least several hundred serials** spanning multiple years. ^[inferred] The intake span has now widened from a single 1956 anchor to **at least 1950 → 1956**. ^[inferred] Sizes in the queued ingest range from **~5 KB (a single-page clipping like serial 403) to ~408 KB** — consistent with a file that mixes brief clippings, longer reports, correspondence (like the 21 KB serial 220), and possibly memoranda. ^[inferred]

## Position in the FBI corpus

This file is the **earliest FBI-originated UAP-adjacent record location in the wiki**, displacing the 1957 Detroit Krasuski case as the corpus's earliest FBI artifact. ^[inferred] Serial 220's **April 1950 intake stamp** moves the FBI-corpus floor back from **November 1957** to **April 1950** — a ~7.5-year extension. ^[inferred] All prior FBI material in the wiki is **field-office product** — Detroit field-office files in 1957–66 ([[references/fbi-detroit-100-26505-krasuski-1957]], [[references/fbi-detroit-100-18221-serial-844-1958]]), and modern (2023) FD-302s of unknown field-office attribution. The HQ-level / Class-62 / content-accumulation function is structurally distinct from any prior FBI artifact in the corpus. ^[inferred] See [[entities/fbi]] for the full cross-era table.

The **content-accumulation** function (now confirmed across two serials) is structurally novel for the corpus. ^[inferred] The wiki's prior FBI artifacts all document **agent-driven action** — interviews, citizen-call routing, civilian-org redirects, evidentiary intake. A topic-accumulation file documents instead **HQ's choice of what to collect and keep**, which is a meaningfully different category of FBI behaviour to study.

## Open threads

- **Resolve file function** further from later serials (164, 438, 449, sections 1–10, sub_a). Reassess this entity page after each subsequent ingest. ^[open]
- Identify the **OPENING serial** of the file — would document the file's titular subject, e.g. *"FLYING SAUCERS"*, *"UNIDENTIFIED FLYING OBJECTS"*, or a specific person/organization name. ^[open]
- Determine the **full time span** of the file from the dates on multiple serials. ^[open]
- Cross-reference 62-HQ-83894 against any **FBI Vault** index entry to recover formal title and date range. ^[open]
- Determine whether **other persons / organizations** in the existing wiki corpus appear in 62-HQ-83894. ^[inferred]
- Determine whether the **62-HQ-83894 file references the Detroit 100-26505 / 100-18221 files** as related material — and vice versa. ^[open]
- Confirm whether the **`Vol 1`** marker on serial 220 implies later serials live in subsequent volumes. ^[open]
- Confirm the **FOIPA vs DIPA** prefix difference indicates per-serial release-tranche processing. ^[inferred]

## See also

- [[references/fbi-hq-62-83894-serial-220]] — second ingested serial (Apr 1950) **(NEW)**
- [[references/fbi-hq-62-83894-serial-403]] — first ingested serial (1956)
- [[entities/miguel-angel-garcia-macias]] — Mexican civilian correspondent on serial 220 **(NEW)**
- [[entities/german-horacio-robles-jr]] — Mexican photographer-witness on serial 220 **(NEW)**
- [[references/sighting-durango-mexico-1950-03]] — the Robles Durango sighting **(NEW)**
- [[entities/gray-barker]] — civilian saucer researcher, subject of serial 403's clipped book jacket
- [[references/barker-1956-they-knew-too-much]] — the Barker book whose jacket is filed
- [[entities/fbi]] — parent agency
- [[references/fbi-detroit-100-26505-krasuski-1957]] — sister Detroit field-office file (different class, different function)
- [[references/fbi-detroit-100-18221-serial-844-1958]] — sister Detroit field-office file
- [[projects/uap/uap]]
