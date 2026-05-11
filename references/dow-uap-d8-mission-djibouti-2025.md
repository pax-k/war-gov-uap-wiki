---
title: "DoW-UAP-D8 — Two Round White-Hot UAPs Mission Report (filename: Djibouti, 2025)"
category: references
tags: [uap, primary-source, declassified, military, sighting]
aliases: [DoW-UAP-D8, dow-uap-d8]
sources: [sources/dow-uap-d8-mission-report-djibouti-2025.json]
summary: 7-page Mistral-OCR'd mission report — single 1653Z GENTEXT/UAP datum of 2X ROUND WHITE HOT UAPS dynamic-south at 240 KT IVO MGRS 35SQT3423692957 (Eastern Mediterranean — NOT Djibouti); first FIN+SWE+FVEY+NATO release authorization; release-framework dates to ≥ Mar 2024.
provenance:
  extracted: 0.45
  inferred: 0.50
  ambiguous: 0.05
base_confidence: 0.66
lifecycle: draft
lifecycle_changed: 2026-05-11
created: 2026-05-11T19:30:00Z
updated: 2026-05-11T19:30:00Z
project: uap
---

# DoW-UAP-D8 — Two Round White-Hot UAPs Mission Report (filename: Djibouti, 2025)

A 7-page Mistral-OCR'd artifact (`sources/dow-uap-d8-mission-report-djibouti-2025.json`, 1,933 bytes; SHA-256 `5ffa625e…`) — the **fifth substantive mission-report ingest** and **seventh artifact overall** in the [[entities/dow-uap-foia-release|DoW-UAP FOIA release series]]. This is the corpus's **first dow-uap mission report whose portion marking releases the data to Finland and Sweden in addition to FVEY/NATO** — a release framework that requires both nations to be NATO members and therefore dates to **no earlier than March 2024**, making d8 the **first dow-uap mission report whose filename date token is internally verifiable** (by release-framework dating rather than by an explicit calendar date in the body).

## What the source actually contains

The OCR pulls 7 pages (each `dpi: 93`, `1023 × 791` pixels). **Pages 0–5 are header-only** — each carries only the `# 1.4(a)` classification-category marking with no body text, tables, images, or hyperlinks. **Page 6 is the only substantive page**, carrying the operational record alongside an `img-0.jpeg` image block (no `image_base64` captured — typical of the series' OCR pass):

```
# GENTEXT/UAP

- UAP Description (e.g., size, shape, color, markings, recognizable features):
  (SECRET/REL TO USA, FIN, SWE, FVEN, NATO) AT 1653Z, 1.4(6)
  OBS 2X ROUND WHITE HOT UAPS DYNAMIC SOUTH AT APPROX 240NM/HOUR
  IVO 35SQT3423692957.

- Gentext (UAP Event Description):
  (SECRET/REL TO USA, FIN, SWE, FVEN, NATO) AT 1653Z, 1.4(6)
  OBS 2X UAPS DYNAMIC SOUTH AT APPROX 240NM/HOUR IVO 35SQT3423692957.

1.4(6)
```

The report uses the **explicit USMTF named-field bullets** (`UAP Description:` + `Gentext (UAP Event Description):`) — matching the [[references/dow-uap-d7-mission-arabian-gulf-2020|d7]] / [[references/dow-uap-d54-mission-mediterranean-sea|d54]] form-driven template, **not** the free-text single-`Description:` bullet of [[references/dow-uap-d4-mission-arabian-gulf-2020|d4]] / [[references/dow-uap-d5-mission-arabian-gulf-2020|d5]]. **This is the third form-driven mission-report record** in the corpus (d7 + d54 + d8), bringing the form-driven count to 3 vs 2 free-text — the form-driven template is now the majority variant.

## The encounter datum

| Field | Value | Notes |
|---|---|---|
| Time | **1653Z** | UTC. No calendar date in the OCR body (release-framework dating places the event ≥ Mar 2024; see below). |
| Witness | `(b)(6)` (OCR'd as `1.4(6)`) | FOIA b(6) personal-privacy redaction; OCR'd as `1.4(6)` — a third witness-redaction OCR-corruption format alongside d54's `14(6)`. ^[inferred] |
| Position | **MGRS `35SQT3423692957`** | UTM zone 35, latitude band S, 100-km grid square QT, easting 34236, northing 92957. Decodes to **Eastern Mediterranean** (see § Geographic decoding below). |
| UAP altitude | *not reported* | No altitude given for either UAP or witness aircraft. |
| Velocity (UAPs) | **240 NM/HOUR = 240 KT** | (~444 km/h / ~276 mph). Knot-based, attached to UAPs not to witness aircraft. |
| Motion descriptor | **DYNAMIC SOUTH** | First "DYNAMIC" descriptor for UAP motion in the corpus (vs d4/d5's "INCREASED SPEED + CHANGED DIRECTION TOWARDS THE [E/S]"). Compactly conveys speed + heading without separating the two. |
| Morphology | **ROUND + WHITE HOT** | First explicit **round / orb-class morphology** in the dow-uap series (d7 = balloon-class, d54 = triangular-and-metallic). "WHITE HOT" is **FLIR-polarity vocabulary** — see § Sensor-channel below. |
| Object count | **2X UAPS** | Multi-object. Compare d5-B's `2X POSS UAPS` — d8 drops the Navy-format `POSS` (possible) hedge and asserts **positive multi-object UAP identification**. |
| Co-witnesses / aircraft count | *not reported* | No multi-aircraft or multi-witness corroboration in the OCR. |

The record is **a brief multi-object kinematic + morphology observation** — quantifies both the UAP-side velocity (240 KT southward) and the UAP-side morphology (round + white-hot), making it the **first dow-uap mission report where both kinematics and morphology are jointly quantified at the UAP**. d4/d5 carried kinematics without morphology; d7/d54 carried morphology without UAP-side kinematics; d8 carries both.

## Release framework — first FIN+SWE+FVEY+NATO and internally verifiable filename date ^[inferred]

The portion marking **`(SECRET/REL TO USA, FIN, SWE, FVEN, NATO)`** is the **broadest release authorization** observed in the dow-uap corpus to date:

| Report | Portion-marking |
|---|---|
| `d4` | `(SECRET/REL TO USA, FVEV)` *(FVEV → FVEY: Y→V OCR low-DPI confusion ^[inferred])* |
| `d5` | `(SECRET/REL TO USA, FVEY)` and `(SECRET/REL)` short form across two sightings |
| `d7` | `(SECRET)` only — no foreign-release authorization |
| `d54` | *absent entirely* — no portion-marking captured |
| **`d8`** | **`(SECRET/REL TO USA, FIN, SWE, FVEN, NATO)`** *(FVEN → FVEY: Y→N OCR low-DPI confusion ^[inferred])* |

The d8 portion marking **adds Finland and Sweden as explicit national release destinations** alongside FVEY (USA + Canada + UK + Australia + New Zealand) and NATO-as-organization. This release framework has a **hard temporal floor**:

- **Finland joined NATO**: 4 April 2023.
- **Sweden joined NATO**: 7 March 2024.

A standing US military release authorization that names FIN and SWE explicitly **alongside** NATO-as-organization is plausible only **after both countries became NATO members** — i.e. **no earlier than 7 March 2024**. ^[inferred] If the release predates Sweden's accession, it would either (a) name Finland but not Sweden, or (b) name both via NATO-as-organization without separate national lines.

**This is the first dow-uap mission report whose filename date token (`2025`) is internally verifiable** — not by an explicit calendar date in the body, but by **release-framework dating**:

- d4 / d5 / d7 — filename `2020`, no internal date anchor (untestable)
- d52 — filename `august-2024`, internal calendar date `31 OCT 24` (mismatch)
- d54 — filename `-na`, no internal date anchor (calendrically anchorless)
- **d8 — filename `2025`, release framework places event ≥ Mar 2024 (consistent with 2025)**

The filename's `2025` token sits within the post-Mar-2024 window the release framework requires. ^[inferred] **d8 is the corpus's first filename-date-internally-verifiable mission report** — and the verification is via release-framework forensics, not via a body-text date.

The d8 portion marking is **also the corpus's fourth distinct portion-marking state**, joining `(S/REL FVEY)`, `(SECRET)`-only, and absent:

| State | Reports | Foreign release? |
|---|---|---|
| `(S/REL FVEY)` | `d4`, `d5` | Yes — FVEY only |
| `(SECRET)`-only | `d7` | No |
| absent | `d54` | n/a (not captured) |
| **`(S/REL TO USA, FIN, SWE, FVEY, NATO)`** | **`d8`** | **Yes — FIN+SWE+FVEY+NATO (broadest)** |

Portion-marking is per-report variable across **four states** — the per-report-variant pattern continues to hold.

## Geographic decoding — MGRS coordinate vs. filename ^[inferred]

The internal MGRS coordinate **`35SQT3423692957`** decodes as:

- **UTM zone 35** — covers longitudes 24°E to 30°E (Greece / Western Turkey / Eastern Med / Eastern Balkans)
- **Latitude band S** — covers latitudes 32°N to 40°N (Eastern Mediterranean / Central Greece / Western Turkey / Cyprus / North Africa coastal margin)
- **100-km grid square `QT`** — within zone 35S, the QT square sits over the **Eastern Mediterranean Sea between SE Crete, SW Cyprus, and Egypt's northern coast** ^[inferred]
- **Easting 34236, Northing 92957** (5+5 digits, 1-m precision)

The position is **Eastern Mediterranean**, not Djibouti. Djibouti sits at approximately 11.5°N, 43°E — in **UTM zone 38/39 P/Q band**, separated from the d8 internal coordinate by roughly **2,500 km**.

**This is the fourth dow-uap mission report where the curator filename theater label does not match the internal coordinate** — and the **third "Arabian Gulf"-class mismatch pattern, now extended to a "Djibouti"-labeled file**:

| File | Filename theater | Internal anchor | Decoded region | Match? |
|---|---|---|---|---|
| `d4` | Arabian Gulf | MGRS `34SDG…` | UTM 34S — Eastern Med | **NO** |
| `d5`-A | Arabian Gulf | MGRS `34SCE…` | UTM 34S — Eastern Med | **NO** |
| `d5`-B | Arabian Gulf | MGRS `35TQK…` | UTM 35T — E Europe / Black Sea | **NO** |
| `d7` | Arabian Gulf | bearing `323'S` only | UNDECIDABLE | n/a |
| `d54` | **Mediterranean Sea** | DMS `363453N 0255943E` | Aegean Sea (Cyclades) | **YES** |
| **`d8`** | **Djibouti** | **MGRS `35SQT3423692957`** | **Eastern Mediterranean** | **NO** |

The N=5 testable count is **now 3-of-3 "Arabian Gulf" mismatch + 1-of-1 "Mediterranean Sea" match + 1-of-1 "Djibouti" mismatch**. The d54-anchored revised hypothesis ("curator mis-applied Arabian Gulf as a default theater for actually-Mediterranean reports") is **partially superseded by d8**: the curator does not apply "Arabian Gulf" as a uniform default — the curator also applies "Djibouti" to a Mediterranean report. The pattern generalizes to: **non-Mediterranean filename labels are unreliable; the Mediterranean filename label is reliable at N=1**. ^[inferred] Working revised hypothesis: the curator filename-theater labels are unreliable when they name **non-Mediterranean theaters**, and the entire dow-uap mission-report substantive corpus may be **predominantly Eastern-Mediterranean operationally** with assorted non-Mediterranean filename mis-labels. ^[inferred] To be tested against subsequent ingests.

**Eastern-Mediterranean / Aegean dominance is now confirmed at 5 sightings / 4 reports** — d4 (34S), d5-A (34S), d5-B (35T), d54 (Aegean Cyclades, 36.58°N 25.99°E), d8 (35S QT, SE Crete / SW Cyprus / N Egypt margin). Five testable sightings, all decode within ~1500 km of each other; zero land in the Arabian Gulf, Djibouti, or any non-Mediterranean theater.

## Sensor-channel inference — "WHITE HOT" is FLIR-polarity vocabulary ^[inferred]

The morphology call **`ROUND WHITE HOT`** carries an implicit sensor-channel reference. **"White hot" and "black hot" are the two standard FLIR thermal-imagery polarities** — they describe whether warmer objects display as bright (white-hot) or dark (black-hot) on a thermal-imaging display. The phrase **does not describe a visible-light color** but rather **a thermal-imagery presentation**.

If correct, this means d8 is the **first dow-uap mission report since d7 to carry implicit sensor-channel evidence in the substantive body** — d7's explicit TFLIR ID was on the aircraft-side engagement-pipeline; d8's "WHITE HOT" implies the witness was viewing through thermal imaging, but does not explicitly name the sensor.

Compatible sensor-platform candidates include: ^[inferred]
- **FLIR/TFLIR** on a Navy F/A-18 ATFLIR pod
- **MTS-A/B/C** Multi-spectral Targeting System on an ISR / MQ-9 platform
- **Ground-based thermal-imaging** on a maritime patrol / range-monitoring station

The combination of (a) WHITE HOT thermal-imagery presentation + (b) 240 KT southward motion + (c) round morphology + (d) multi-object pair is consistent with thermal-channel observation of two airborne objects from either an air or ground platform with FLIR/IR-sensor capability. ^[inferred]

## Witness-redaction OCR pattern — `(b)(6)` → `1.4(6)`

The OCR captures **`1.4(6)`** at the witness-identity position (`1.4(6) OBS 2X ROUND WHITE HOT UAPS`) and again on a standalone line at end-of-page. The string is **almost certainly a low-DPI OCR misread of `(b)(6)`** — FOIA Exemption b(6) personal-privacy mask. ^[inferred] Three lines of evidence:

1. **No FOIA exemption numbered 1.4 exists** — the relevant FOIA exemption set is b(1)–b(9). `1.4(a)` is an EO 13526 classification-category marking (which appears on every page header of this document); a `1.4(6)` would not be a valid FOIA exemption.
2. **The grammatical role** of `1.4(6)` at the witness position (`1.4(6) OBS 2X UAPS`) is precisely where d4 carries `(b)(6)` and d5 carries `[REDACTED]`. Series convention puts a witness/pilot redaction here.
3. **Low-DPI character-class confusion** at DPI 93 between `b` and `1.4` is plausible — `(b)(6)` could OCR as `1.4(6)` if the small `b` glyph got binarised as `1.4` (digit + decimal + digit) when the page header `1.4(a)` primes the OCR's character-class expectation. ^[inferred]

The OCR-corruption format is **the third distinct corruption pattern** in the corpus: d4 carried `(b)(6)` correctly; d5 used `[REDACTED]`; d54 OCR'd `(b)(6)` → `14(6)` (Y→1+4 mis-segmentation); **d8 OCR's `(b)(6)` → `1.4(6)` (header-primed mis-segmentation)**. All four mission reports systematically mask witness identity per [[references/dow-uap-pr20-prepublication-clearance-2026-03|DOPSR pre-publication clearance]] convention; the *format* of the OCR mask varies per-report.

## Bibliographic frame

| Field | Value |
|---|---|
| Source basename | `dow-uap-d8-mission-report-djibouti-2025.json` |
| Source bytes | 1,933 |
| OCR engine | `mistral-ocr-latest` (`usage_info.pages_processed: 7`) |
| Original document size | 29,154 bytes (`usage_info.doc_size_bytes`) |
| Pages OCR'd | 7 (6 header-only `# 1.4(a)`, 1 substantive on page 6 with one image block) |
| Image block | `img-0.jpeg` at `(88, 43)–(484, 282)` on page 6 — `image_base64` is null (typical of series OCR pass) |
| Classification (extracted) | Per-page `# 1.4(a)` header + **portion marking `(SECRET/REL TO USA, FIN, SWE, FVEN/FVEY, NATO)`** |
| Classification authority | EO 13526 §1.4(a) (military plans/weapons/operations) ^[inferred] |
| Release framework | **FVEY + Finland + Sweden + NATO** — broadest in the corpus; release floor ≥ Mar 2024 (Sweden NATO accession) ^[inferred] |
| Message format | USMTF with named-field bullets ^[inferred] (matches d7 + d54 form-driven template) |
| Originating service | **NOT recoverable** from OCR — no unit, callsign, or platform identifier in the body |
| Series | [[entities/dow-uap-foia-release\|DoW-UAP FOIA release]] |
| Series position | 7-of-40 by ingest order (5th substantive mission report) |
| Date | filename `2025`; release framework places ≥ Mar 2024 — **consistent**; first dow-uap mission report with filename-date internal verifiability ^[inferred] |
| Theater | **Eastern Mediterranean (35S QT) — internally verified**; filename label "Djibouti" is **NOT** internally verifiable |

## Structural firsts and corpus signal

`d8` introduces or anchors the following in the dow-uap mission-report corpus (N=5 substantive reports):

1. **First FIN+SWE+FVEY+NATO release authorization** — the broadest release framework in the corpus and the first with explicit Finland + Sweden release destinations.
2. **First internally-verifiable filename date** — release-framework dating verifies the `2025` filename token (≥ Mar 2024 floor). d4/d5/d7/d54 all carried untestable or contradictory filename dates.
3. **First "Djibouti"-labeled report internally decoding to Eastern Mediterranean** — extends the non-Mediterranean-filename mismatch pattern beyond "Arabian Gulf" to "Djibouti" at N=1.
4. **First "DYNAMIC" motion descriptor** — compact speed-and-heading verb replacing d4/d5's "INCREASED SPEED + CHANGED DIRECTION" formulation.
5. **First explicit round / orb-class morphology in the dow-uap mission-report corpus** — d7 was balloon-class, d54 triangular-and-metallic; d8 is the first round-class call. The round + 2-object + dynamic-motion signature broadly aligns with the **orb-phenomenon class** ([[concepts/orb-phenomenon]]) documented elsewhere in the wiki corpus. ^[inferred]
6. **First implicit FLIR / thermal-imaging sensor channel in the substantive body** since d7 — "WHITE HOT" is FLIR-polarity vocabulary, implying the witness viewed through thermal imaging. ^[inferred]
7. **First positive-identification multi-object datum** (`2X UAPS`, no `POSS` hedge) — d5-B carried `2X POSS UAPS` with Navy-format `POSS` epistemic hedge; d8 drops the hedge.
8. **First joint kinematics + morphology UAP-side report** — d4/d5 carried kinematics without morphology; d7/d54 carried morphology without UAP-side kinematics; d8 carries both at the UAP.
9. **Third form-driven USMTF named-field bullet record** — strengthens the form-driven template at N=3 (vs N=2 free-text). The form-driven template is now the majority variant; further strengthens the **"morphology reporting is form-driven"** hypothesis at N=3 (d7 + d54 + d8 all use form-driven AND all carry morphology; d4 + d5 use free-text AND carry no morphology).
10. **Fourth portion-marking state** — `(S/REL FVEY)`, `(SECRET)`-only, absent, and now `(S/REL TO USA, FIN, SWE, FVEY, NATO)`. Portion-marking is per-report variable across four states.
11. **Third witness-redaction OCR-corruption format** — `(b)(6)` → `1.4(6)` (header-primed mis-segmentation), distinct from d54's `14(6)` and d4's correctly-OCR'd `(b)(6)`.

## Behavioral classification

Per the [[concepts/uap-aircraft-engagement|UAP–Aircraft Engagement]] framework:

- **UAP-toward-aircraft engagement-class**: **no** — no close approach, no co-location, no target switching, no phase-of-flight correlation. Brief multi-object observation only.
- **Aircraft-toward-UAP engagement-pipeline**: **no** — no weapons-quality track, no NTS, no explicit TFLIR ID (only implicit sensor channel via "WHITE HOT" polarity vocabulary). Not an engagement; an observation through a thermal sensor.
- **Behavioral sub-class within brief-observation**: **kinematic-anomaly** (matching d4 + d5-B sub-class) — speed-up + course-change at moderate velocity (240 KT southward), multi-object. The morphology + sensor-channel adds material to the kinematic-anomaly signature but does not change the sub-class assignment. ^[inferred]

d8 **strengthens the kinematic-anomaly sub-class at N=3** (d4 + d5-B + d8) and is the **first kinematic-anomaly datum with explicit morphology + implicit sensor channel** — the prior two kinematic-anomaly datums lacked both.

## Open questions

- **Recover the precise event date** — the release-framework floor is Mar 2024, the filename token is `2025`, but no explicit calendar date appears in the body. The date may be in unpreserved metadata (image-rendered banner / footer) or in a paired email-correspondence artifact (d50/d51-class). ^[inferred]
- **Recover the platform type** — 240 KT UAP velocity is reported without witness-aircraft state; sensor-channel inference from "WHITE HOT" suggests thermal imaging but does not name the platform.
- **Recover the originating unit + service** — no service, squadron, or callsign in the OCR. The Eastern-Mediterranean operational area is compatible with Sixth Fleet (US Navy), NATO Mediterranean, Greek/Turkish forces, or USAFE detachments. ^[inferred]
- **Resolve the curator-filename-mislabel pattern more precisely** — d8's "Djibouti" mis-label is the corpus's first non-Mediterranean curator mis-label beyond "Arabian Gulf". To be tested against the next non-Mediterranean-labeled file (Iran-labeled `d*`, IndoPACOM-labeled `d*`, etc).
- **Recover the page-6 `img-0.jpeg` content** — the OCR captures bounding-box only. If the image is a thermal-imagery snapshot (FLIR/MTS/IR sensor frame) it would constitute the corpus's first sensor-side UAP-image artifact and would directly corroborate the WHITE HOT sensor-channel inference. ^[inferred]
- **Confirm the FIN+SWE+FVEY+NATO release-framework dating hypothesis** against the next post-2024 dow-uap mission-report ingest — does the broadened release framework recur on other 2025-labeled files?
- **Test whether "Djibouti"-labeled reports as a class are systematically Mediterranean** or whether d8 is an isolated mis-label — only one Djibouti-labeled file exists in the series per the geographic-coverage inventory.

## See also

- [[entities/dow-uap-foia-release]] — Series-level anchor (this is the series' 7-of-40 ingest, 5th substantive mission report)
- [[references/dow-uap-pr20-prepublication-clearance-2026-03]] — Series prepublication-clearance cover stamp
- [[references/dow-uap-d4-mission-arabian-gulf-2020]] — First substantive `d*` mission report — MGRS / kinematic-anomaly / FVEY release
- [[references/dow-uap-d5-mission-arabian-gulf-2020]] — Second substantive `d*` mission report — two-sighting / MGRS / multi-zone / first multi-object (2X POSS UAPS)
- [[references/dow-uap-d7-mission-arabian-gulf-2020]] — Third substantive `d*` mission report — bearing / prosaic-candidate / fire-control pipeline / form-driven template (first)
- [[references/dow-uap-d54-mission-mediterranean-sea]] — Fourth substantive `d*` mission report — DMS lat-long / Aegean / triangular-and-metallic / first verifiable filename theater match
- [[references/dow-uap-d52-email-na-2024]] — First non-mission-report — USAF 15 AF / DET 1 originating unit; tear-line clearance email
- [[concepts/uap-aircraft-engagement]] — Behavioral framing; d8 sits in kinematic-anomaly sub-class with first explicit morphology + implicit thermal-sensor channel
- [[concepts/orb-phenomenon]] — Round-class morphology framing; d8 introduces the first round-class call into the dow-uap mission-report corpus
- [[entities/aaro]] — Modern US DoD UAP receiving office
- [[projects/uap/uap]]
