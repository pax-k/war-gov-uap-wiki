---
title: "DoW-UAP-D6 — Mission Report (Arabian Gulf, 2020, single-datum extract)"
category: references
tags: [uap, primary-source, declassified, navy, sighting]
aliases: [DoW-UAP-D6, dow-uap-d6]
sources: [sources/dow-uap-d6-mission-report-arabian-gulf-2020.json]
summary: 7-page near-empty Mistral-OCR'd mission report (1,686 bytes; 233 chars total content). Pages 0-5 carry only `# 1.4(a)` redaction placeholders. Page 6 carries one substantive GENTEXT/UAP datum: AT 1246Z 1X PROB UAP observed IVO 3SKT4255899519, NO MISSION IMPACT, CONTINUED ORIGINAL TASKING. 8th member of single-segment GENTEXT/UAP extract sub-format.
provenance:
  extracted: 0.40
  inferred: 0.50
  ambiguous: 0.10
base_confidence: 0.55
lifecycle: active
lifecycle_changed: 2026-05-12
created: 2026-05-12T02:15:00Z
updated: 2026-05-12T02:15:00Z
project: uap
---

# DoW-UAP-D6 — Mission Report (Arabian Gulf, 2020, single-datum extract)

A **7-page Mistral-OCR'd artifact** (`sources/dow-uap-d6-mission-report-arabian-gulf-2020.json`, 1,686 bytes; SHA-256 `5e0bb9de5808d1ce…`) — the **21st artifact** in the [[entities/dow-uap-foia-release|DoW-UAP FOIA release series]] and the **8th single-segment GENTEXT/UAP extract** sub-format (with [[references/dow-uap-d3-mission-arabian-gulf-2020|d3]] + [[references/dow-uap-d4-mission-arabian-gulf-2020|d4]] + [[references/dow-uap-d5-mission-arabian-gulf-2020|d5]] + [[references/dow-uap-d7-mission-arabian-gulf-2020|d7]] + [[references/dow-uap-d54-mission-mediterranean-sea|d54]] + [[references/dow-uap-d8-mission-djibouti-2025|d8]]).

**Lowest-content artifact in dow-uap corpus**: pages 0–5 carry only `# 1.4(a)` redaction placeholders (one heading per page, no other text). Page 6 carries **a single substantive GENTEXT/UAP-style description line** plus an embedded image reference:

```
1.4(a)

![img-0.jpeg](img-0.jpeg)

1.4(a)

- Description: (S/REL) AT 1246Z, 1.4(a) OBSERVED 1X PROB UAP
  IVO 3SKT4255899519. NO MISSION IMPACT, 1.4(a) CONTINUED ORIGINAL
  TASKING.

1.4(a)
```

**Verbatim datum**: AT 1246Z, 1.4(a) OBSERVED 1X PROB UAP IVO 3SKT4255899519. NO MISSION IMPACT, 1.4(a) CONTINUED ORIGINAL TASKING.

## UAP datum analysis

| Field | Value | Notes |
|---|---|---|
| Time | **1246Z** | second precision absent; minute precision only |
| Object count | **1X** | single contact |
| Identification confidence | **PROB UAP** | `Probable UAP` — uncertainty hedge; matches Navy USMTF tearline vocabulary used in [[references/dow-uap-d50-email-indopacom-2025-04|d50]] (`POSS UAP`) and [[references/dow-uap-d52-email-na-2024|d52]] (`POSS UAP`) ^[inferred] |
| Position | **IVO 3SKT4255899519** | MGRS-style 13+ digit position string. `3SKT` parses as **UTM 3S grid zone (S latitude band, between 24°S and 32°S)** with grid square `KT` — this places the datum in **South Atlantic / South Pacific / South Indian Ocean (~24-32°S latitude)** ^[inferred], NOT Arabian Gulf. Alternative reading: `3SKT` is OCR-corruption of `38SKT` or `39SKT` (Eastern Med / Levant), or `40SKT` is the original MGRS prefix with leading digit dropped ^[ambiguous]. The remaining digits `4255899519` parse as 10-digit easting+northing within the grid square (1-m precision) — `42558` E + `99519` N ^[inferred] |
| Engagement | **NO MISSION IMPACT** | first explicit `NO MISSION IMPACT` clause in the single-segment-extract sub-format; matches [[references/dow-uap-d60-mission-persian-gulf-2020-08-08|d60]]'s `NO IMPACT TO MISSION` cluster-mission attestation phrasing (full-Misrep parent class) |
| Posture | **CONTINUED ORIGINAL TASKING** | passive observation; no closure, no intercept, no fire-control pipeline. Matches sub-class 8 strict (FMV-observation + zero-mission-impact + kinematics-blank + morphology-blank) ^[inferred] |
| Morphology | none captured | `PROB UAP` only — no shape, color, markings, recognizable features |
| Kinematics | none captured | no speed, altitude, heading, trajectory |
| Sensor | redacted | (S/REL) classification marking implies sensor capture, but the sensor channel field is portion-redacted |
| Classification | (S/REL) | first explicit `S/REL` portion-marking in the d3/d4/d5/d6/d7/d54/d8 single-segment-extract sub-format ^[inferred] |

## Document-class identification

d6 is **single-segment GENTEXT/UAP extract** sub-format, same as d3/d4/d5/d7/d54/d8. Structure:

- 6 pages of `# 1.4(a)` redaction placeholders + 1 page carrying the substantive UAP datum on bottom 6 lines + 1 image reference
- No declassification banner
- No bottom-of-page release block (no Block A/B/C stamp)
- No multi-segment USMTF Timeline / OBSERVATION / ISR / EMI segments
- No POC/QC/APPROVER blocks captured in OCR

**Distinct from d3** (which had 7 pages of more elaborate redaction-fill + 2 substantive pages including the full UAP segment template). d6 is the most degraded / heavily-redacted artifact in the sub-class.

## Sub-class assignment

The d6 datum fits **sub-class 8 (bare FMV-observation + zero-mission-impact + kinematics-blank + morphology-blank)** at type level:

- ✓ Zero kinematics (no speed/altitude/heading)
- ✓ Zero morphology (no shape/color/markings)
- ✓ Single-object (1X)
- ✓ Explicit zero-mission-impact (`NO MISSION IMPACT`)
- ✓ Passive non-engagement posture (`CONTINUED ORIGINAL TASKING`)
- ? FMV method (sensor channel redacted)
- + `PROB UAP` identification-confidence hedge (matches Navy USMTF tearline vocabulary; new variant in dow-uap corpus — first PROB rather than POSS or unhedged)

d6 fits sub-class 8 at 5-of-6 axes captured. With the FMV-method axis untestable (sensor redacted), d6 is sub-class 8 with PROB-vs-bare-UAP minor variant. Counter increments **N=12 → N=13 records / 19 → 20 datums** (+1 record, +1 datum).

## MGRS analysis

`3SKT4255899519` — non-standard MGRS rendering:

- **`3S`** = UTM grid zone 3, S latitude band (24-32°S) — South Hemisphere mid-latitude ^[inferred]
- **`KT`** = 100-km square within zone 3S
- Remaining digits `4255899519` = 10-digit easting+northing (1m precision)

UTM zone 3 covers longitude 168°W to 162°W (e.g., NW Hawaii region in the south, Aleutians in the north). 3S in S latitude band would be **central South Pacific** — does not match `arabian-gulf` filename label.

**Three OCR-correction readings** ^[ambiguous]:

1. **OCR-leading-digit-strip**: original prefix was `38SKT`, `39SKT`, or `40SKT` (Eastern Med / Levant). With `38SKT`/`39SKT` prefix, the datum lands in Eastern Mediterranean — matching the d4/d5/d7 filename-vs-internal-coordinate mismatch pattern. ^[inferred] Highest plausibility given sister extracts.
2. **OCR-glyph-substitution**: `3SKT` is corruption of `38KT` or `39KT` (less likely; doesn't change zone).
3. **Original MGRS is correct**: datum is genuinely in UTM zone 3, S latitude band (central South Pacific). Filename `arabian-gulf` mismatch would extend the d4/d5/d7 pattern at scale — first non-Eastern-Med non-Mediterranean coordinate.

Reading 1 is operationally most coherent. **OCR-leading-digit-strip extends to d6 if confirmed at N=2** — would refine the d4/d5/d7 Eastern Med decode by anchoring an OCR-corruption mechanism.

## Bibliographic frame

| Field | Value |
|---|---|
| Source basename | `dow-uap-d6-mission-report-arabian-gulf-2020.json` |
| Source bytes | 1,686 |
| OCR engine | `mistral-ocr-latest` ^[inferred] |
| Pages OCR'd | 7 (6 blank placeholders + 1 substantive) |
| Substantive page count | 1 (page 6 only) |
| Content character count | 233 chars (lowest in dow-uap corpus) |
| Images / tables | 1 image on page 6 (FOIA-redaction visual); no tables |
| Misrep ID | NOT captured in OCR (no `# Misrep NNNNNNN` header rendered; absent or redacted) |
| Declassification banner | ABSENT |
| Bottom-of-page release block | ABSENT |
| Document class | Single-segment GENTEXT/UAP extract (8th in sub-class) |
| Originating unit | NOT captured |
| Mission classification | NOT captured |
| Event date | UNTESTABLE (filename `2020`; no body-text date anchor) |
| Event time | **1246Z** (minute precision) |
| Theater | UNTESTABLE at filename level (`arabian-gulf`); MGRS `3SKT...` ambiguous due to OCR-leading-digit-strip candidate ^[ambiguous] |
| Object count | 1 (`1X PROB UAP`) |
| Object morphology | none captured |
| Identification confidence | `PROB UAP` (first PROB in dow-uap sub-class extract) |
| Sensor | redacted |
| Kinematic anomaly | NONE captured |
| Active EA signature | NONE captured |
| Aircraft posture | passive; `CONTINUED ORIGINAL TASKING` |
| Mission impact | `NO MISSION IMPACT` (first explicit attestation in single-segment-extract sub-format) |

## Structural firsts the d6 ingest anchors

1. **Lowest-content artifact in dow-uap corpus** — 233 chars total, 6-of-7 pages blank-redaction-only.
2. **First `PROB UAP` identification-confidence hedge** in dow-uap single-segment-extract sub-format (cluster uses `1X UAP` unhedged; d50/d52 emails use `POSS UAP`).
3. **First `NO MISSION IMPACT` clause** in the single-segment-extract sub-format (matches d60 full-Misrep cluster `NO IMPACT TO MISSION` phrasing).
4. **First `CONTINUED ORIGINAL TASKING` posture clause** in the single-segment-extract sub-format.
5. **First `(S/REL)` portion-marking** in d3/d4/d5/d6/d7/d54/d8 sub-class (per UAP description preamble).
6. **First MGRS-leading-digit-strip OCR-corruption candidate** in dow-uap corpus — `3SKT...` likely `38SKT` or `39SKT` with leading digit dropped ^[ambiguous].

## Open threads

- **MGRS `3SKT4255899519` decode** — confirm OCR-leading-digit-strip reading at N≥2 by examining d3/d4/d5/d7 OCR for similar partial-MGRS renderings.
- **`PROB UAP` vs `POSS UAP` vs unhedged distribution** in dow-uap corpus — d6 is the first PROB attestation; build distribution at N≥10.
- **Misrep ID for d6** — entirely absent from OCR or redacted? Test against the Misrep-counter framework (d3 = 8799515 outside cluster; d6 could be near d3 or could be in the cluster range).
- **6-of-7-pages-blank redaction pattern** — does this represent the most heavily-redacted state at the single-segment-extract sub-class, or are there sister artifacts with even less content?

## See also

- [[references/dow-uap-d3-mission-arabian-gulf-2020]] — single-segment-extract sister; just-ingested; 4X UAP multi-event under cloud cover; first weather-prevented-following attestation; refutes corpus-linear Misrep ID counter
- [[references/dow-uap-d4-mission-arabian-gulf-2020]] — single-segment-extract sister; filename match; Eastern-Med-decode in body
- [[references/dow-uap-d5-mission-arabian-gulf-2020]] — single-segment-extract sister; filename match; two-datum extract
- [[references/dow-uap-d7-mission-arabian-gulf-2020]] — single-segment-extract sister; filename match; fire-control pipeline anchor
- [[references/dow-uap-d8-mission-djibouti-2025]] — single-segment-extract sister; orb-class round morphology
- [[references/dow-uap-d54-mission-mediterranean-sea]] — single-segment-extract sister; triangular-metallic morphology
- [[references/dow-uap-d60-mission-persian-gulf-2020-08-08]] — full-Misrep cluster anchor; comparator for `NO IMPACT TO MISSION` phrasing
- [[references/dow-uap-d50-email-indopacom-2025-04]] — email-class artifact with `POSS UAP` identification-confidence hedge (comparator for d6 `PROB UAP`)
- [[entities/dow-uap-foia-release]] — series-level anchor
- [[concepts/uap-aircraft-engagement]] — behavioral framework; d6 extends sub-class 8 with PROB-UAP-variant
- [[entities/aaro]] — implied AARO routing but no explicit stamp on d6 (consistent with single-segment-extract sub-class lacking bottom-of-page block)
- [[projects/uap/uap]]
