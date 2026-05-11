---
title: "DoW-UAP-D7 — Weapons-Quality-Track Balloon-Like UAP Mission Report (Arabian Gulf, 2020)"
category: references
tags: [uap, primary-source, declassified, dod, military]
aliases: [DoW-UAP-D7, dow-uap-d7]
sources: [sources/dow-uap-d7-mission-report-arabian-gulf-2020.json]
summary: 6-page Mistral-OCR'd mission report; balloon-like UAP at 31,000 ft MSL bearing 323°, weapons-quality-1 track + NEXT TO SHOOT + TFLIR visual ID; cross-references "PREVIOUSLY REPORTED UAP FROM 48FW" — second USAF cross-reference in series.
provenance:
  extracted: 0.40
  inferred: 0.55
  ambiguous: 0.05
base_confidence: 0.62
lifecycle: draft
lifecycle_changed: 2026-05-11
created: 2026-05-11T11:24:17Z
updated: 2026-05-11T11:24:17Z
---

# DoW-UAP-D7 — Weapons-Quality-Track Balloon-Like UAP Mission Report (Arabian Gulf, 2020)

A 6-page Mistral-OCR'd artifact (`sources/dow-uap-d7-mission-report-arabian-gulf-2020.json`, 1,605 bytes; SHA-256 `60953738…`) — the **third substantive `d*`-prefixed mission-report ingest** of the [[entities/dow-uap-foia-release|DoW-UAP FOIA release series]] (series position **5-of-40**), following [[references/dow-uap-d4-mission-arabian-gulf-2020|D4]], [[references/dow-uap-d5-mission-arabian-gulf-2020|D5]], and [[references/dow-uap-d52-email-na-2024|D52]]. The artifact is a **single-sighting** GENTEXT/UAP mission-report record that introduces **three structural firsts** to the corpus: a **morphology descriptor** ("balloon"), a **weapons-quality fire-control track + NEXT TO SHOOT** call, and an **explicit cross-report citation** to a sister sighting from the **48th Fighter Wing** (USAF, RAF Lakenheath).

## What the source actually contains

The OCR pulls 6 pages (each `dpi: 93`, `1023 × 791` pixels). **Pages 0–4 are header-only** — each carries only the classification-marking string `# 1.4(a)` with no body text, tables, images, or hyperlinks (identical pattern to `d4`'s and `d5`'s header-only-prefix). **Page 5 is the only substantive page**, and structurally **differs** from `d4`/`d5` in carrying *two* `1.4(a)` strings at the top before the `# GENTEXT/UAP` header rather than a single `# 1.4(a)` heading:

```
1.4(a)

1.4(a)

# GENTEXT/UAP

- UAP Description (e.g., size, shape, color, markings, recognizable features):
  LOOKS LIKE A BALLOON, SIMILAR TO PREVIOUSLY REPORTED UAP FROM 48FW.
- Gentext (UAP Event Description): (SECRET) OBSERVED A WEAPONS QUALITY 1 TRACK
  OF A UAP TRAVELING WITH THE WINDS AT 31,000 FT MSL IVO 323'S, 1.4(a) WAS
  ABLE TO MAKE A NEXT TO SHOOT ON THE TRACK AND VISUALLY ID THE UAP IN THE
  TFLIR.

1.4(a)
```

The format introduces **a structural variation** from the `d4`/`d5` template:

- The portion-marking is **`(SECRET)`** in full rather than the `(S/REL)` portion-marking used in `d4` and `d5`. This may signal **no foreign-release authorization** on this datum (vs `SECRET/REL TO USA, FVEY` on `d4`) — i.e. a higher-restriction classification posture than the two sister Eastern-Med reports. ^[inferred]
- The substantive page is **structured around two named USMTF fields** (`UAP Description` and `Gentext (UAP Event Description)`) rather than a single free-text `Description` bullet. `d4`/`d5` collapsed all content into one `Description` bullet. This is the corpus's **first explicit-field GENTEXT/UAP form** — closer to a Navy/Joint structured UAP reporting form. ^[inferred]
- **No MGRS coordinate.** Position is given as **`IVO 323'S`** — *in vicinity of* a bearing/heading of **323°** (north-northwest). `d4` and `d5` both anchored position via MGRS grid; `d7` uses a **bearing-only** position anchor. The reference frame (bearing from where?) is not preserved in OCR. ^[ambiguous] Plausibly bearing from the reporting platform's own position at the time of track acquisition, but this is not stated.
- **`1.4(a) WAS ABLE TO MAKE A NEXT TO SHOOT`** — the leading `1.4(a)` substring at this position is **almost certainly an OCR/redaction artifact masking a unit, callsign, or platform identifier**. The §1.4(a) classification-category string is repeating into a body-text slot, suggesting the underlying document carried a redacted identifier here. ^[inferred]

No images, tables, hyperlinks, headers, or footers in any page. No `SECRET/REL TO USA, FVEY` banner captured. No witness `(b)(6)` redaction-block on the substantive page (different from `d4`'s `PILOT: (b)(6)` and `d5`'s inline `[REDACTED]`).

## The encounter datum

| Field | Value | Notes |
|---|---|---|
| Time | *not preserved* | **First `d*` mission-report ingest with no Zulu time on the substantive page.** Neither calendar date nor UTC time captured. |
| Witness / platform | *redacted as `1.4(a)`* | OCR/redaction artifact masking the platform/unit identifier. ^[inferred] |
| Position (UAP) | **bearing `323'S`** | "IVO 323'S" — *in vicinity of* heading 323° (NNW). **First bearing-only position anchor in the `dow-uap-` corpus.** Reference frame not stated. ^[ambiguous] |
| Altitude (UAP) | **31,000 ft MSL** | First MSL (Mean Sea Level) altitude in the corpus; `d5`-A used FL160-170 (pressure altitude). 31,000 ft MSL ≈ FL310 in standard atmosphere. |
| Velocity (UAP) | *not specified numerically* | "TRAVELING WITH THE WINDS" — wind-borne drift implied. **First wind-coupled motion descriptor in the corpus.** |
| Behavior | **Wind-borne drift** | Consistent with the balloon morphology call. No course change, no speed change, no engagement-class behavior. |
| Morphology | **"LOOKS LIKE A BALLOON"** | **First morphology descriptor in the `d*` mission-report corpus.** `d4`/`d5` had zero morphology across 3 datums. |
| Object count | **1** | Single track. |
| Track quality | **WEAPONS QUALITY 1** | Fire-control-grade radar/sensor track. ^[inferred] |
| Engagement state | **NEXT TO SHOOT** | Aircraft is queued/positioned for weapons engagement. Did **not** fire. ^[inferred] |
| Sensor confirmation | **TFLIR visual ID** | Targeting Forward-Looking Infrared confirmed the target visually after track was acquired. |
| Cross-reference | **"SIMILAR TO PREVIOUSLY REPORTED UAP FROM 48FW"** | **First cross-report citation in the `d*` corpus.** 48FW = USAF [[entities/48th-fighter-wing|48th Fighter Wing]] (RAF Lakenheath UK; F-15E Strike Eagle). ^[inferred] |

The kinematic signature is **passive wind-borne drift at airliner-stratum altitude with balloon morphology** — substantively *different* from `d4`/`d5`'s kinematic-anomaly / steady-state-cruise sub-classes. The signal-class on its face is **prosaic-candidate (balloon)** rather than anomalous-kinematics. **What makes the report SECRET-class is not the kinematics — it is (a) the fire-control engagement posture, (b) the TFLIR visual confirmation, and (c) the cross-reference back to a 48FW report establishing a recurring pattern.** ^[inferred]

## Weapons-quality track + NEXT TO SHOOT — engagement-pipeline signature

The combination **WEAPONS QUALITY 1 TRACK** + **NEXT TO SHOOT** is the corpus's **first explicit fire-control-pipeline UAP datum**. ^[inferred] Working interpretation of the terms:

- **Weapons-quality track (WQT, "Cat 1"):** the highest fire-control track-quality grade — radar/sensor lock is stable enough to support weapons employment. Lower-grade ("track-quality") and ("search-only") returns are not weapons-employable. ^[inferred]
- **NEXT TO SHOOT (NTS):** an aircraft is the next platform queued/positioned in the engagement order to release weapons on the track. NTS is the immediate-precursor state to a weapons release; the aircraft has commit authority, an authorization channel, and a firing solution. ^[inferred]
- **The report explicitly notes the aircraft did *not* shoot** — the engagement was carried only as far as TFLIR visual ID. The decision-not-to-engage is itself the data point, since the kinematics + morphology call ("balloon, traveling with the winds") would not normally warrant a weapons-release order on a non-threatening target.

This datum **breaks the negative-engagement pattern** anchored at N=2 ([[concepts/uap-aircraft-engagement#Negative datum — modern Navy mission-report corpus produces brief-observation-class records, not engagement-class|engagement-concept § Negative datum]]) **only in the operational-state sense** — the reporting aircraft entered the engagement pipeline against a UAP track. It does **not** meet the four-criterion engagement-class behavioral bar (no close approach, no co-location, no target switching, no phase-of-flight correlation) — those criteria characterize **UAP behavior toward aircraft**, whereas `d7` documents **aircraft behavior toward UAP**. The two directions of the engagement axis are **distinct**: `d7` is the corpus's first datum on the **aircraft-side engagement posture against a UAP**.

This justifies splitting [[concepts/uap-aircraft-engagement]]'s axis-of-engagement into **two complementary classes**: (i) **UAP-toward-aircraft engagement** (target selection, cross-aircraft pursuit; anchored at Mantell/Chiles-Whitted/Gorman/Andrews 1948; modern: helicopter-orb 2025); (ii) **aircraft-toward-UAP engagement-pipeline** (track acquisition, fire-control commit, NEXT TO SHOOT, TFLIR ID; anchored at `d7`). ^[inferred]

## 48FW cross-reference — multi-service pattern strengthens at N≥5

The phrase **"SIMILAR TO PREVIOUSLY REPORTED UAP FROM 48FW"** is the **first cross-report citation in the `d*` mission-report corpus** — `d4` and `d5` carried zero references to other reports. Two structural inferences from this single phrase:

1. **48FW = USAF 48th Fighter Wing**, the F-15E Strike Eagle wing at RAF Lakenheath UK (3rd Air Force, USAFE). ^[inferred] The "48FW" abbreviation is unambiguous in modern USAF usage. This is the **second USAF originating-unit anchor in the dow-uap series** (after `d52`'s `15 AF / DET 1`).
2. **A prior 48FW UAP-mission-report exists** — and was apparently in circulation across reporting platforms at the time `d7` was produced. This is **inferred internal-document-stream evidence that the series carries a multi-report cross-referencing network**, not isolated sightings. ^[inferred] If preserved in the unreleased `d*` files, a 48FW report would resolve the cross-reference.

Combined with `d52`'s `15 AF / DET 1` evidence ([[entities/dow-uap-foia-release#Email-correspondence document class — anchored at N=1|series § Email-correspondence document class]]) and the multi-service framing currently held at N=4, the **48FW reference is the second USAF unit-name anchor in the series** — confirming that the series is **release-side-multi-service**. ^[inferred] The Navy-originating hypothesis for the series is further weakened.

The 48FW unit-reference also raises a **theater question**: 48FW is forward-deployed to RAF Lakenheath in the UK, but participates in CENTCOM rotations (Operation Inherent Resolve, Operation Spartan Shield, etc.) including Arabian Gulf / Middle East / Eastern Mediterranean operations. ^[inferred] **Both `d7`'s reporting platform and 48FW could plausibly have been operating in any of those theaters** when their respective UAP encounters were recorded. The filename "Arabian Gulf 2020" is therefore not necessarily wrong for `d7` — but it provides no internal verification either, since there are no MGRS coordinates.

## Filename vs. internal-document — UNDECIDABLE at N=3 for theater axis

Unlike `d4` and `d5` (both filename-labeled "Arabian Gulf" but internal-MGRS-labeled UTM 34S/35T = Eastern Med/Black Sea), **`d7` carries no MGRS coordinate** to compare against the filename. The bearing-only position anchor (`323'S`) is uninterpretable without a reference-frame origin. ^[ambiguous]

This **does not refute** the filename-vs-internal-coordinate discrepancy confirmed at N=2 by `d4`+`d5`; it simply **lacks a discriminating internal anchor**. The corpus-level observation that **curator-applied filename theater labels are unreliable** is maintained at N=2 (where MGRS data is present) and is **untestable** for `d7`. ^[inferred]

The filename **year** (`2020`) likewise has **no internal verification** in `d7` — there is no Zulu time, no calendar date, no document-creation date captured in the substantive page. This **extends the date-axis filename-unreliability** observation from `d52` (filename `august-2024`, internal `31 OCT 24`) to a *missing-internal-date* case in `d7`. ^[inferred] **Across N=4 ingested `d*` files, only `d4` and `d5` carry internal time anchors; `d52` and `d7` do not preserve the date axis in OCR.**

## Format-template confirmation + revision (cross-validation against `d4`, `d5`)

`d7` validates **most** of the structural template anchored at [[references/dow-uap-d4-mission-arabian-gulf-2020|D4]] and extended by [[references/dow-uap-d5-mission-arabian-gulf-2020|D5]], with one **format revision**:

| Template element | d7 status | Notes |
|---|---|---|
| Per-page `# 1.4(a)` (EO 13526 §1.4(a)) header | **Confirmed at N=3** | Recurs on all 6 OCR pages; pages 0-4 are header-only. |
| Header-only pages padded around substantive pages | **Confirmed-with-variation** | `d7` carries **5 header-only pages** before the single substantive page (vs `d4`'s 4 and `d5`'s 4). Pre-padding count is per-report variable. |
| One or more substantive page(s) with GENTEXT/UAP segment(s) | **Confirmed** | `d7` carries 1 substantive page with 1 GENTEXT/UAP segment (like `d4`); `d5` carried 2. Sighting count is per-report variable. |
| USMTF `GENTEXT/UAP` segment header | **Confirmed at N=3** | `d7` uses `# GENTEXT/UAP` as a top-level heading (like `d4`); `d5`-B used `## GENTEXT/UAP`. Heading-level is OCR-variable. |
| `(S/REL)` portion marking | **REVISED — d7 uses `(SECRET)` instead** | First `d*` mission-report ingest with non-`(S/REL)` portion-marking. `(SECRET)` implies no foreign-release authorization — a more-restrictive posture than `d4`/`d5`. ^[inferred] |
| `SECRET/REL TO USA, FVEY` banner | **Unconfirmed in d7** | Not captured. Consistent with `(SECRET)`-only portion-marking. |
| MGRS coordinates | **REVISED — d7 uses bearing-only** | First `d*` mission-report ingest without MGRS. Bearing `323'S` with no reference-frame origin. |
| Knots velocity | **N/A in d7** | Velocity is qualitative ("traveling with the winds") rather than knots-quantified. |
| Zulu time without calendar date | **REVISED — d7 has no time at all** | First `d*` mission-report ingest with no time anchor. |
| Altitude reporting | **`d7`-extended: MSL units** | `d5`-A used `FL` (flight level / pressure altitude); `d7` uses `MSL` (mean sea level). Both ~17K-31K ft band but different reference systems. |
| FOIA `(b)(6)` witness redaction | **Absent on substantive page** | First `d*` mission-report substantive page without a `(b)(6)` block. The platform/unit identifier appears OCR-masked as `1.4(a)` instead. ^[inferred] |
| Morphology descriptor | **`d7`-INTRODUCED** | First morphology call in the `d*` corpus: "LOOKS LIKE A BALLOON". |
| Cross-report reference | **`d7`-INTRODUCED** | First explicit cross-report citation in the `d*` corpus: "PREVIOUSLY REPORTED UAP FROM 48FW". |
| Track-quality + fire-control language | **`d7`-INTRODUCED** | "WEAPONS QUALITY 1 TRACK" + "NEXT TO SHOOT" + "TFLIR" — first fire-control-pipeline vocabulary in the `d*` corpus. |
| Explicit USMTF named fields | **`d7`-INTRODUCED** | First substantive page using explicit `UAP Description:` and `Gentext (UAP Event Description):` named-field bullets. ^[inferred] |

The **revision count at N=3** is now material: `(SECRET)` vs `(S/REL)`, bearing vs MGRS, no-time vs Zulu-time, MSL vs FL. The working hypothesis that the `d*` mission-report family is a single tight USMTF template is now **weakened** — the family appears to admit **per-report format variants**, plausibly because reporting platforms / theaters / time-periods used different USMTF templates or different intake-form versions. ^[inferred]

## Behavioral class — prosaic-candidate (balloon) + first aircraft-side engagement-pipeline

`d7`'s sighting splits across two analytical axes:

1. **Phenomenology axis** — the morphology + behavior reads **prosaic** ("balloon" + "traveling with the winds"). On phenomenology alone, this is a **balloon-class candidate**, not an anomalous-physics UAP. This is the corpus's **first prosaic-candidate datum in the `d*` mission-report family** (the [[references/usaf-flying-discs-1948|1948 USAF FBI-corpus]] has prosaic candidates; the `d*` corpus had none at N=2). ^[inferred] However, the report still passed UAP-class reporting threshold and entered the FOIA-cleared `dow-uap` release tranche — suggesting the **routing decision was driven by the engagement posture and 48FW cross-reference, not the phenomenology**. ^[inferred]
2. **Engagement axis (aircraft-side)** — the aircraft entered **fire-control engagement state** (weapons-quality track + NEXT TO SHOOT + TFLIR ID). This is the **first aircraft-side engagement-pipeline datum** in the corpus.

Both axes are **first-of-kind** in the `d*` mission-report family at N=3 mission-reports / 4 datums.

## Bibliographic frame

| Field | Value |
|---|---|
| Source basename | `dow-uap-d7-mission-report-arabian-gulf-2020.json` |
| Source bytes | 1,605 |
| SHA-256 | `60953738d34fcec11bfd152607e4c7e369c617fb1342cb8a3ac45e230e222ecd` |
| OCR engine | `mistral-ocr-latest` (inferred from sister artifacts) ^[inferred] |
| Pages OCR'd | 6 (5 header-only, 1 substantive) |
| Classification (extracted) | `(SECRET)` per portion marking; EO 13526 §1.4(a) per page header. Banner not captured. ^[inferred] |
| Classification authority | EO 13526 §1.4(a) (military plans/weapons/operations) ^[inferred] |
| Message format | USMTF; single GENTEXT/UAP segment with named-field bullets ^[inferred] |
| Originating service | **Ambiguous** — neither Navy nor USAF directly anchored; 48FW (USAF) is cited as a **prior** report, not as `d7`'s own originator. ^[inferred] |
| Series | [[entities/dow-uap-foia-release\|DoW-UAP FOIA release]] |
| Series position | **5-of-40** (third substantive `d*` mission-report; `d7` by filename-numbering — `d6` not yet ingested) |
| Sisters | [[references/dow-uap-d4-mission-arabian-gulf-2020]] (`d4`, 2-of-40, single-sighting), [[references/dow-uap-d5-mission-arabian-gulf-2020]] (`d5`, 3-of-40, two-sighting), [[references/dow-uap-d52-email-na-2024]] (`d52`, USAF-anchored email-correspondence) |

## Open questions

- **Recover the 48FW prior report.** A `dow-uap-` `d*` file presumably preserves the cited 48FW UAP sighting; identifying it would validate the cross-reference and characterize the 48FW theater + behavior pattern. ^[ambiguous]
- **Resolve the OCR-masked `1.4(a) WAS ABLE TO MAKE A NEXT TO SHOOT` substring.** Almost certainly a redaction artifact masking a platform/unit identifier (callsign, squadron, or aircraft tail). ^[inferred]
- **Recover position reference frame.** Bearing `323'S` is uninterpretable without an origin; not preserved in OCR.
- **Recover date.** `d7` has no internal date anchor at all — extending the unreliable-filename pattern from theater-only (d4/d5) and date-only (d52) to **both axes simultaneously** in `d7`. ^[inferred]
- **Confirm `(SECRET)` vs `(S/REL)` posture pattern** — does `d7`'s no-foreign-release posture recur in later `d*` ingests, or is it specific to this report?
- **Resolve track-quality + engagement-pipeline vocabulary across future ingests.** If WQT + NTS recurs in later `d*` files, the corpus contains a sub-stream of fire-control-grade UAP tracks distinct from the brief-observation stream.
- **Was the 48FW prior report also balloon-morphology?** The phrase "similar to" is ambiguous as to which dimension of similarity (morphology vs kinematics vs both).

## See also

- [[entities/dow-uap-foia-release]] — Series-level anchor (`d7` extends format template + introduces morphology + fire-control engagement-pipeline + 48FW USAF anchor)
- [[references/dow-uap-d4-mission-arabian-gulf-2020]] — First substantive `d*` mission-report (single-sighting, kinematic-anomaly, MGRS-34S)
- [[references/dow-uap-d5-mission-arabian-gulf-2020]] — Second substantive `d*` mission-report (two-sighting, multi-zone, kinematic-anomaly + steady-state)
- [[references/dow-uap-d52-email-na-2024]] — First USAF unit anchor in the series (`15 AF / DET 1`); `d7`'s 48FW reference is the second USAF anchor
- [[references/dow-uap-pr20-prepublication-clearance-2026-03]] — Series prepublication-clearance cover stamp
- [[concepts/uap-aircraft-engagement]] — Behavioral framing; `d7` introduces the **aircraft-side engagement-pipeline** complement to UAP-side engagement-class
- [[entities/ryan-graves]] — Modern Navy-aviation context; ATFLIR / TFLIR sensor family
- [[projects/uap/uap]]
