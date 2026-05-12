---
title: "DoW-UAP-D3 — Mission Report (Arabian Gulf, 2020, Misrep 8799515)"
category: references
tags: [uap, primary-source, declassified, usaf, sighting]
aliases: [DoW-UAP-D3, dow-uap-d3]
sources: [sources/dow-uap-d3-mission-report-arabian-gulf-2020.json]
summary: 7-page heavily-redacted single-segment GENTEXT/UAP extract. AT 1736Z, 4X UAP observed in 100% FOV under 100% cloud cover; 3 sub-observations at 17:36:22/17:36:30/17:36:49. AFCENT MAJCOM attribution; no bottom-of-page release block (distinct from Block A/B/C cluster); Misrep ID 8799515 outside cluster range — refutes linear-time Misrep-ID-per-day reading at squadron level.
provenance:
  extracted: 0.50
  inferred: 0.35
  ambiguous: 0.15
base_confidence: 0.60
lifecycle: active
lifecycle_changed: 2026-05-12
created: 2026-05-12T01:45:00Z
updated: 2026-05-12T01:45:00Z
project: uap
---

# DoW-UAP-D3 — Mission Report (Arabian Gulf, 2020, Misrep 8799515)

A **7-page Mistral-OCR'd artifact** (`sources/dow-uap-d3-mission-report-arabian-gulf-2020.json`, 7,060 bytes; SHA-256 `c3739f8943d57…`) — the **20th artifact** in the [[entities/dow-uap-foia-release|DoW-UAP FOIA release series]] and the **7th single-segment GENTEXT/UAP extract** sub-format (joining [[references/dow-uap-d4-mission-arabian-gulf-2020|d4]] + [[references/dow-uap-d5-mission-arabian-gulf-2020|d5]] + [[references/dow-uap-d7-mission-arabian-gulf-2020|d7]] + [[references/dow-uap-d54-mission-mediterranean-sea|d54]] + [[references/dow-uap-d8-mission-djibouti-2025|d8]] + [[references/dow-uap-d6-mission-arabian-gulf-2020|d6 implied]]). d3 carries **one structurally-complete GENTEXT/UAP datum on page 6** with a multi-object (4X UAP) observation under 100% cloud cover. ^[inferred]

The d3 ingest extends the corpus's multi-object UAP-observation count and **refutes the linear-time Misrep-ID-per-day reading at squadron level** anchored by the d60-d65 cluster: d3 Misrep ID `8799515` is **+4,327,001 IDs higher than [[references/dow-uap-d65-mission-persian-gulf-2020-07-16|d65]]'s `4472514`** — at the cluster's empirical ~5,200 IDs/day rate that would place d3 ~830 days (~2.3 years) AFTER d65 (i.e., ~2022-2023), contradicting the filename `2020` label. ^[inferred] Three readings live: (a) **per-squadron-counter** reading — d3 is from a different squadron than 482ATKS, with its own ID counter range; (b) **non-linear counter** reading — counter rate varies per squadron or per release event; (c) **filename-year mismatch** reading — d3 actual event year is 2022-2023 not 2020. ^[ambiguous] The body-text Operation field is portion-redacted `(b)(1).4a`; no body-text event-date anchor recoverable from OCR. Domain field shows `2016` and Operations Center field shows `2016` — both likely OCR-corruption / placeholder-fill artifacts ^[ambiguous].

## Document-class identification — single-segment extract sub-format

d3's structure is **single-segment GENTEXT/UAP extract**:

| Schema element | d3 | Cluster (d60-d65) | Sister extracts (d4/d5/d7/d54/d8) |
|---|---|---|---|
| Page count | 7 | 7-9 substantive | 5-7 (mostly blank) |
| Substantive page count | 2 (pages 5+6 carry mission timeline + UAP segment) | 6-9 (all substantive) | 1-2 (UAP page only) |
| Header banner | `(b)(1).4a` + `# Misrep 8799515` | `Declassified by MG Richard A. Harrison USCENTCOM` | absent or filename only |
| Multi-segment Timeline | absent | present (Takeoff / On Station / Landing / etc.) | absent |
| GENTEXT/OBSERVATION segment | absent | present | absent |
| GENTEXT/ISR segment | partial (page 3 has structural fields, all redacted) | present | absent |
| GENTEXT/UAP segment | present (page 6) | optional | present |
| GENTEXT/EMI segment | absent | optional ([[references/dow-uap-d62-mission-strait-of-hormuz-2020-09-16|d62]] only) | absent |
| Bottom-of-page release block | ABSENT | present (Block A/B/C: `MDR / 03/27/26 \| 01/26/26 \| 03/16/26` + `Approved for Release to AARO`) | ABSENT |
| Page-stamp digit-scheme | absent (no sequential page stamps) | present (6-digit or 3-digit) | absent |
| Per-page `1.4a` redactions | comprehensive — fills most data fields | minimal (POC/QC/APPROVER only) | comprehensive |

**Conclusion**: d3 is the single-segment GENTEXT/UAP extract sub-format. It belongs to the **pre-Block-A/B/C-framework release pipeline** (or an alternative release pipeline lacking the bottom-of-page block), consistent with [[references/dow-uap-d4-mission-arabian-gulf-2020|d4]] / [[references/dow-uap-d5-mission-arabian-gulf-2020|d5]] / [[references/dow-uap-d7-mission-arabian-gulf-2020|d7]] / [[references/dow-uap-d54-mission-mediterranean-sea|d54]] / [[references/dow-uap-d8-mission-djibouti-2025|d8]] structural pattern. ^[inferred]

## GENTEXT/UAP datum (page 6, verbatim)

```
- UAP Advanced Capabilities And/Or Materials (yes/no; if yes, describe): NO

GENTEXT/UAP
- UAP Description (e.g., size, shape, color, markings, recognizable features):
  4X UAP OBSERVED FLYING IN 100% FOV. CLOUD COVERAGE OBSTRUCTED FROM FOLLOWING
  AND GETTING A CLEAR VISUAL. (SEE ISR 1).
- Gentext (UAP Event Description):
  AT APPROX 1736Z 4 UAP WERE OBSERVED BENEATH 100% 1X UAP OBSERVED AT 17:36:22,
  2X UAP OBSERVED SIDE BY SIDE AT 17:36:30, AND 1X UAP OBSERVED AT 17:36:49.
```

**Three observation events within a 27-second window** (17:36:22 → 17:36:30 → 17:36:49):

| Event # | Time | Count | Configuration |
|---|---|---|---|
| 1 | 17:36:22 | 1X | single |
| 2 | 17:36:30 | 2X | side by side |
| 3 | 17:36:49 | 1X | single |

**Total = 4X UAP** with side-by-side intra-group geometry on event #2.

**100% cloud cover** prevented sustained tracking — first explicit "weather-prevented-following" cause-of-track-loss attestation in the dow-uap corpus. ^[inferred]

## UAP datum sub-class

The d3 datum fits **brief-observation sub-class with novel characteristics**:

- **sub-class 8 (bare FMV-observation)** at type level: zero kinematics, zero morphology, FMV-implied (no explicit FMV method token captured) — but the multi-object count (4X) departs from sub-class 8's typical single-object signature.
- **Multi-object brief-observation**: 4 UAP in 27 seconds across 3 sub-events; matches no existing sub-class directly. **Candidate 10th sub-class — multi-object-brief-observation-weather-obstructed**. ^[inferred]

**Mission-report counter** increments N=11 → **N=12 records / 15→19 datums** (d3 +4 datums).

**Mission-report counter discipline note**: the d3 multi-object event is a single mission-report record containing 4 UAP sub-events. Counter convention: **1 record + 4 datums**. Distribution shifts subclass-8 strict reading from 7-of-9 → 7-of-13 (54% if d3 datums are NOT sub-class 8 strict; or 11-of-13 = 85% if multi-object is classed as sub-class-8 with size multiplier). ^[ambiguous] Reading kept conservative: d3 anchors candidate 10th sub-class, sub-class 8 strict remains 7-of-9 (78%).

## Filename theater verification

| Filename axis | Filename token | Internal value | Match? |
|---|---|---|---|
| Theater | `arabian-gulf` | redacted `(b)(1).4a` (Tasked Start Point + UAP First Seen Location both portion-redacted) | **UNTESTABLE** |
| Date | `2020` | body-text `Domain: 2016`, `Operations Center: 2016`, declassification date `20480603` — none of these is the event date; event time `1736Z` captured without year/month/day anchor | **UNTESTABLE** (with possible 2016 indication from Domain/OC fields, but those are likely OCR-corruption) |

d3 is **doubly untestable** on the filename-axis verification. Consistent with d4/d5/d7 untestable patterns. ^[inferred]

## Multi-service originating-anchor

- **Service Tasked**: A — AIR FORCE
- **MAJCOM**: AFCENT (United States Air Forces Central Command)
- **COCOM**: portion-redacted `(b)(1).4a` (likely CENTCOM ^[inferred])

**First explicit AFCENT MAJCOM attestation in dow-uap corpus** — distinct from cluster's `609 CAOC` Combined Air Operations Center attestation (which sits inside AFCENT command structure but is named at the AOC level on cluster artifacts). ^[inferred] Multi-service originating-anchor count unchanged at 8 (482ATKS already attested in cluster; d3 squadron field redacted).

## Bibliographic frame

| Field | Value |
|---|---|
| Source basename | `dow-uap-d3-mission-report-arabian-gulf-2020.json` |
| Source bytes | 7,060 |
| OCR engine | `mistral-ocr-latest` ^[inferred] |
| Pages OCR'd | 7 (~5,242 chars total) |
| Substantive pages | 2 (pages 5+6 carry the timeline + UAP segment) |
| Images / tables / hyperlinks | 2 images on pages 0+4 (FOIA-redaction visual artifacts); no tables |
| Misrep ID | **8799515** — outside cluster range; refutes linear-time Misrep-ID-per-day reading at squadron level |
| Declassification banner | ABSENT (no Harrison + USCENTCOM attribution) |
| Bottom-of-page release block | ABSENT (no Block A/B/C stamp) |
| Document-level declassification date | `20480603` (3 June 2048) — far-future declassification consistent with SECRET 25-year-rule |
| Document class | Single-segment GENTEXT/UAP extract (matches d4/d5/d7/d54/d8) |
| Originating service | Air Force (explicit) |
| MAJCOM | AFCENT |
| COCOM | redacted (likely CENTCOM ^[inferred]) |
| Originating unit | redacted `(b)(1).4a` (POC/QC/APPROVER all redacted with OCR-corrupted `00055@1300` template-placeholder fill) |
| Mission classification | ISR (Activity Description: `ISR`) |
| Event date | UNTESTABLE (filename `2020`; body-text date redacted; Domain/OC fields show suspicious `2016` likely OCR artifact) |
| Event time | 1736:22 → 1736:49Z (27-second bracket) |
| Theater | UNTESTABLE (Tasked Start Point + UAP First Seen Location both redacted) |
| Object count | 4 (3 events across 27 seconds: 1+2+1) |
| Object morphology | none captured (UAP Description names "UAP" only — no shape/color/markings) |
| Sensor | FMV-implied (Activity Description ISR + Primary Sensor field redacted) |
| Kinematic anomaly | NONE captured |
| Active EA signature | NONE captured |
| Closest approach | NONE captured |
| Aircraft posture | passive ISR (Activity Description = ISR; UAP advanced-capabilities = NO) |
| Mission impact | implied none (cloud cover prevented following, but no impact statement) |

## Structural firsts the d3 ingest anchors

1. **Misrep ID 8799515** outside d60-d65 cluster range — first evidence that the Misrep ID counter framework is per-squadron-pooled or per-release-event-pooled, not unified-linear-time at corpus level.
2. **First "weather-prevented-following" cause-of-track-loss attestation** in the dow-uap corpus — 100% cloud cover obstructed sustained tracking ^[extracted].
3. **First 4-UAP-multi-event observation** in a single dow-uap mission record — 3 sub-events at 17:36:22/30/49 (27-sec window).
4. **First side-by-side intra-group geometry datum** in the single-segment GENTEXT/UAP extract sub-format (sister format only — distinct from [[references/dow-uap-d58-range-fouler-debrief-2020-10|d58]]'s "one circling the other" range-fouler-class anchor).
5. **First explicit AFCENT MAJCOM attestation** in the dow-uap corpus (cluster uses 609 CAOC AOC-level only; d3 names the parent USAF Central Command).
6. **Candidate 10th brief-observation sub-class — multi-object-brief-observation-weather-obstructed** ^[inferred].

## OCR ambiguities

- **`(b)(1).4a` vs `(b)(1)1.4a` vs `01(1)1.4a` vs `b)(1)1.4a` portion-redaction renderings** — pages 0+1 use `(b)(1).4a`; pages 2-5 use `(b)(1)1.4a`; page 4 uses bare `b)(1)1.4a` (missing opening paren); page 6 uses `01(1)1.4a` (missing leading `(b)`). All same EO 13526 §1.4(a) portion-redaction stamp; OCR variance only. ^[inferred]
- **`Domain: 2016` and `Operations Center: 2016`** — these field values are most plausibly OCR-corruption / redaction-fill placeholders, not literal 2016 attestations. The cluster reference exemplars carry `Domain: ALL` or theater-name in this field. ^[ambiguous] If literal 2016, d3 event date is 2016 not 2020 — but the filename token `2020` and the much-higher Misrep ID 8799515 both work against this reading.
- **`00055@1300` template-placeholder fill values** across POC/QC/APPROVER blocks — possibly OCR-corruption of a redacted form-template, or a literal template-default value preserved through to the FOIA release. ^[ambiguous] Reading favors OCR-corruption: real submitter data was portion-redacted upstream and OCR recovered template-default text from underlying typesetter codepoints.
- **`Operation: (b)(1).4a` + `COCOM: (b)(1).4a`** — both redacted; CENTCOM inference comes from MAJCOM `AFCENT` attestation only.
- **`info@mail.com @mail.smil.mil` POC email** — partial-redaction fill artifact: `info@mail.com` is the template default, `@mail.smil.mil` is the SIPRNet routing suffix. Real submitter email was portion-redacted; OCR recovered the template stem.
- **No declassification banner at top of page 0** — distinct from cluster's `Declassified by MG Harrison` banner. d3 may belong to an earlier or distinct release pipeline.
- **`(SEE ISR 1)` cross-reference** in UAP Description field — the ISR segment on page 3 has all data fields portion-redacted. The "ISR 1" reference is unrecoverable from OCR.

## Open threads

- **Misrep ID counter framework reading** — is `8799515` per-squadron-counter (d3 is from a different squadron than 482ATKS), per-release-event-pooled, or non-linear within-squadron? Validate at N≥1 additional non-cluster mission-record artifact.
- **`Domain: 2016` and `Operations Center: 2016` field values** — literal 2016 indication or OCR-corruption placeholder? Test against d4/d5/d7 OCR (which should carry similar fields if same template).
- **Pre-Block-A/B/C release pipeline** — d3 + d4 + d5 + d7 + d54 + d8 all lack bottom-of-page release blocks. What declassification + AARO routing did they pass through? Distinct release tranche.
- **Multi-object-brief-observation-weather-obstructed sub-class candidate** — validate at N≥2 in the remaining queue.
- **Filename `arabian-gulf` curator-mismatch hypothesis** — d3's body coordinate is fully redacted; cannot test against d4/d5/d7 Eastern-Med-decode pattern. The pattern remains 4-of-4 untestable in the original ingest order if d3 + d4 are bundled at filename level.
- **AFCENT MAJCOM as parent of 609 CAOC** — does d3's AFCENT attestation imply same broader command structure as cluster's 609 CAOC AOC, despite different specific units?

## See also

- [[references/dow-uap-d4-mission-arabian-gulf-2020]] — single-segment extract sister; filename match; Eastern-Med-decode in d4 body
- [[references/dow-uap-d5-mission-arabian-gulf-2020]] — single-segment extract sister; filename match
- [[references/dow-uap-d7-mission-arabian-gulf-2020]] — single-segment extract sister; filename match; first 48FW fire-control pipeline anchor
- [[references/dow-uap-d6-mission-arabian-gulf-2020]] — implied single-segment extract sister with 1 PROB UAP datum on page 6 of 7
- [[references/dow-uap-d8-mission-djibouti-2025]] — single-segment extract; FIN+SWE+FVEY+NATO release; orb-class round morphology
- [[references/dow-uap-d54-mission-mediterranean-sea]] — single-segment extract; triangular-metallic morphology
- [[references/dow-uap-d65-mission-persian-gulf-2020-07-16]] — earliest full-Misrep cluster anchor; comparator for Misrep ID counter framework
- [[references/dow-uap-d60-mission-persian-gulf-2020-08-08]] — first ingested full-Misrep cluster artifact; Misrep ID 4592219
- [[entities/dow-uap-foia-release]] — series-level anchor
- [[concepts/uap-aircraft-engagement]] — behavioral framework; d3 anchors candidate 10th sub-class
- [[concepts/orb-phenomenon]] — 4X-UAP-multi-event-in-27-seconds parallels orb-class-formation events in broader corpus
- [[entities/aaro]] — AARO routing implied but no explicit stamp on d3 (distinct from cluster's bottom-of-page AARO stamp)
- [[projects/uap/uap]]
