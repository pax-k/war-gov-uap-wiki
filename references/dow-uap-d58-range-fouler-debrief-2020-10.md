---
title: "DoW-UAP-D58 — Range Fouler Debrief Form (77 EFS, 27 Oct 2020)"
category: references
tags: [uap, primary-source, declassified, military, sighting]
aliases: [DoW-UAP-D58, dow-uap-d58, dow-uap-range-fouler-d58]
sources: [sources/dow-uap-d58-range-fouler-debrief-na-october-2020.json]
summary: 1-page Mistral-OCR'd Range Fouler Debrief Form — 27 Oct 2020 0112Z night DCA mission; 2X balloon-shaped metallic-opaque-reflective UAPs at radar lock with target-pod IR confirmation; vanish in 1/30 s; noise jamming received. First range-fouler document class in the dow-uap corpus.
provenance:
  extracted: 0.55
  inferred: 0.40
  ambiguous: 0.05
base_confidence: 0.70
lifecycle: draft
lifecycle_changed: 2026-05-11
created: 2026-05-11T21:00:00Z
updated: 2026-05-11T21:00:00Z
project: uap
---

# DoW-UAP-D58 — Range Fouler Debrief Form (77 EFS, 27 Oct 2020)

A **1-page Mistral-OCR'd artifact** (`sources/dow-uap-d58-range-fouler-debrief-na-october-2020.json`, 3,416 bytes) — the **tenth artifact** in the [[entities/dow-uap-foia-release|DoW-UAP FOIA release series]] and the **first ingest of the "range-fouler debrief" document class** anchored on `*-range-fouler-debrief-*` filenames (~6 of 40 files in the tranche). The artifact establishes the document class's structural template at N=1: a **fielded debrief form** with a defined schema (squadron / rank / time / position / radar+sensor / morphology checkboxes / free-text narrative) followed by a centralized **SPEAR**-pipeline submission instruction block.

The same source resolves a **major series-level open question**: d58 carries the **identical USCENTCOM MDR case range (`26-0038 to MDR 26-0046`), Approved-for-Release-to-AARO routing stamp, MG Richard A. Harrison declassification block, `03/27/26` release-stamp date, and `000001` release-sequence number** as [[references/dow-uap-d55-mission-syria-2016-11-18|d55]]. The AARO-receiving-authority closure on [[entities/dow-uap-foia-release]] (^closed-by-dow-uap-d55, originally annotated "contingent on stamp recurrence") **firms at N=2** with d58 as the recurrence anchor.

## What the source actually contains

The OCR pulls **1 substantive page** (`dpi: 93`, `1023 × 791` pixels). No images, no tables, no header/footer metadata. The page renders a fully-printed-and-completed debrief form with mixed pre-printed labels and hand-entered values, with the witness narrative at the bottom.

**Top metadata block (declassification + classification authority):**

```
Declassified by MG Richard A. Harrison
U.S.C. 3
Section 3.1
```

Same authority block as [[references/dow-uap-d55-mission-syria-2016-11-18|d55]]. **`U.S.C. 3` + `Section 3.1`** are new — the citation reads as **50 U.S.C. § 3** (Foreign Relations and Intercourse / National Security) **§ 3.1** but is more probably the **Executive Order 13526 §3.1** ("authority for declassification") citation rendered with an OCR-confused `U.S.C.` for `E.O.`. ^[inferred] Either reading aligns with the existing per-page `# 1.4(a)` classification-marking convention in the series.

**Form header:**

```
# Range Fouler Debrief Form

Please complete this form to the best of your ability. If you do not have the requested information,
please leave the field blank. If there was more than one "group," please report each on a separate
form for data collection purposes. You should receive a response within 5 business days.
```

The instruction `"please report each [group] on a separate form"` confirms the **form is designed for single-group capture** — the d58 datum captures one group (2 contacts), and a hypothetical multi-group encounter would generate multiple forms. ^[inferred] The 5-business-day response SLA implies a **centralized intake operator** that triages each form.

**Identity + administrative fields (pre-printed + filled):**

| Field | Value |
|---|---|
| Last Name, First Name | (blank in OCR — likely redacted pre-print) |
| Rank | **O-3** (Captain-equivalent; for USAF or USN this is Capt / Lt USN) |
| Squadron | **77 EFS** (USAF 77th Expeditionary Fighter Squadron — see *Service attribution ambiguity* below) |
| Crew Position | (blank) |
| SIPR Email Address | (blank) |

**Sanitization disclaimer (form's own text):**

> *This information is for contact only. SPEAR sanitizes all reports of identifying information. Absolutely no identifying information for aircrew or squadron will be recorded for analysis.*

`SPEAR` is the **first explicit data-pipeline / intake-system name** in the dow-uap corpus. ^[inferred] The acronym is not expanded on the form. Working candidates (all ^[inferred]):

- **Strategic Pattern, Engagement, Analysis, and Reporting** (or similar Navy-aviation intelligence-analysis program name)
- **Sensor Pattern / Engagement / Analysis / Repository** style acronym
- A Navy-aviation-community SPEAR program separate from the Pentagon-OUSD(I&S) DOPSR / AARO pipelines

The form's centralized-intake + per-form-sanitization architecture is **structurally analogous to AARO's UAP intake** but the explicit attribution here is *SPEAR*, not AARO. ^[inferred] Whether SPEAR feeds AARO downstream is open.

**Mission/event fields (pre-printed + filled):**

| Field | Value | Notes |
|---|---|---|
| Date (mm/dd/yy) | **10/27/20** | 27 October 2020. **First explicit body-text calendar date** in a dow-uap *mission* artifact since [[references/dow-uap-d55-mission-syria-2016-11-18\|d55]] (the only other one). |
| Time of detection (hh:mm:ss Z) | **01:12:21Z** | UTC; precision to the second is novel in the corpus. |
| Day/Night | **Night** | First explicit day/night classification in the dow-uap corpus. |
| Side No. | (blank) | Buno (Bureau Number) field also blank. |
| Buno | (blank) | Navy aircraft serial-number field present but empty. |
| Mission Description (CAS, BFM, etc) | **DCA** | **Defensive Counter Air** — air-to-air defensive mission. ^[inferred] |
| LFE? | **No** | **Large Force Exercise** flag — negative. ^[inferred] |
| Contact Working Area (Ex: W-72 1A) | (blank) | The example `W-72 1A` is a US East Coast warning-area designator (Atlantic Test Range); the field is blank in d58, so the working area isn't recoverable from the form. ^[inferred] |
| Contact Latitude / N-S | (blank) | |
| Contact Longitude / E-W | (blank) | |
| Contact Altitude | (blank) | |
| Altitude Constant? | (blank) | |
| Wind Dir at Contact Alt (From) | (blank) | |
| Wind Speed | (blank) | |
| Was the contact moving? | **Yes** | |
| Direction/Speed | **060/20** | 060° at 20 KT — UAP-side kinematics. **Slow eastward drift**, comparable to a balloon's wind-coupled drift profile. ^[inferred] |

The position fields being blank is **diagnostic**: the witness completed the kinematic fields but did not have position fix data when filling the form. The free-text section below recovers a *bullseye-relative bearing/range* (`B/E ZIM 248/17`) — see below.

**Sensor + track fields (pre-printed checkboxes + entries):**

| Field | Value | Notes |
|---|---|---|
| Radar Equipped | **Other** | Not the standard F/A-18 APG-73 / -79 radar option set; "Other" implies an unconventional radar fit. ^[inferred] |
| Stable Trackfile? | **Yes** | Radar track was stable. |
| # of Contacts in "Group" | **2** | Two-object encounter. |
| AIM-9x Self-Track | (blank) | **AIM-9X Sidewinder IR seeker self-track** option (Navy-standard F/A-18E/F integration). ^[inferred] |
| ATFLIR Autotrack | (blank) | **Advanced Targeting Forward-Looking Infrared autotrack** (Navy-standard F/A-18E/F + EA-18G pod). ^[inferred] |
| Tally Achieved | **☑** (checked) | Visual acquisition confirmed. |

**Morphology checkboxes (pre-printed; ☑ = checked):**

| Shape category | Value |
|---|---|
| Round | (unchecked) |
| Square | (unchecked) |
| **Balloon-shaped** | **☑** |
| Wings/Airframe | (unchecked) |
| **Other Shape** | **☑** |
| Apparent Propulsion | (unchecked) |
| Moving Parts | (unchecked) |
| **Metallic** | **☑** |
| Markings | (unchecked) |
| Translucent | (unchecked) |
| **Opaque** | **☑** |
| **Reflective** | **☑** |

Four morphology characteristics checked: **balloon-shaped + other-shape + metallic + opaque + reflective** (with `Other Shape` and `Balloon-shaped` both checked — implying the form-completer is signaling "balloon-shaped" *and* something irreducibly other). The witness narrative below describes the visual signature as **`2X RED BLINKING STROBES`** — which is *neither* a balloon-class signature *nor* an obvious metallic-reflective surface, and may be the "other" feature the checkbox combination is gesturing at. ^[inferred]

**Witness narrative (verbatim, with `1,4a` / `1.4a` redaction notation expanded as `(b)(6)`-class FOIA portion redactions):**

> *KINGPIN DIRECTED ID OF UNKNOWN CONTACT. **1,4a** OBTAINED RADAR LOCK AND TARGET POD VIDEO BUT UNABLE TO GET CLOSER THAN 16.9NM TO GET A BETTER ID. THE TARGET POD SHOWN 2 IR SIGNIFICANT CONTACTS. ONE RANGE FOULER WAS CIRCLING AROUND THE OTHER. IN 1/30TH OF A SECOND, THEY WERE GONE. TALLY ACHIEVED WAS 2X RED BLINKING STROBES AND NOISE JAMMING WAS RECEIVED. NOISE JAMMING WAS INDICATED BY TWO CHEVRONS.*
>
> *FIRST DETECTION OF THE RANGE FOULERS WERE AT B/E ZIM 248/17. **1.4a***

**Submission instructions:**

> *Don't use the purple "submit" button! Save this form with filename "Date_Squadron_RF.pdf" and email it to **(b)(6)** (Also in the global). For troubleshooting, call **(b)(6)***

The filename schema **`Date_Squadron_RF.pdf`** is the **first explicit naming convention** captured in the dow-uap corpus. ^[inferred] The `_RF` suffix is the form's internal short-code for "Range Fouler" — establishing the **class-internal abbreviation**.

> *Thank you for your time. Please ensure all display tapes are ripped for the entire time of interaction and saved as a .wmv (Example: 4 May VFA-106 HUD.wmv). Squadron intel personnel shall upload those files to the repository located at this link.*

**`VFA-106`** is a real US Navy squadron — the **Fleet Replacement Squadron (FRS) for the F/A-18E/F Super Hornet community** based at NAS Oceana, Virginia. The example filename `4 May VFA-106 HUD.wmv` is a non-redacted Navy squadron reference embedded in the form's template — **a stronger Navy origination anchor than anything in the form's filled-in section**. ^[inferred] This strongly supports the **SPEAR-as-Navy-aviation-program** reading: the form is Navy-originated even if the d58 user (77 EFS) is USAF.

**Release framework block (bottom of page):**

```
USCENTCOM MDR 26-0038 to MDR 26-0046
Approved for Release to AARO
03/27/26 000001
```

**Identical to [[references/dow-uap-d55-mission-syria-2016-11-18|d55]]'s release block** — see § *Release framework — confirms d55's MDR + AARO stamp at N=2* below.

## Service attribution ambiguity — 77 EFS is USAF, but the form is Navy

The `Squadron` field reads **`77 EFS`** — the **77th Expeditionary Fighter Squadron**. Three competing readings:

1. **USAF reading (most probable, ^[inferred])** — *EFS* is the US Air Force's *Expeditionary Fighter Squadron* designator (e.g. **77th Fighter Squadron, "Gamblers"**, F-16C/CM, Shaw AFB SC, deploying as 77 EFS during USAFCENT rotations). If correct, d58 is the **fourth USAF unit anchor** in the dow-uap series after `15 AF / DET 1` (d52), `48FW` (d7 cross-reference), and `12 AF / DET 3` (d50). The multi-service originating-content count rises to **5: 4 USAF unit anchors + 1 Navy platform anchor**.

2. **Navy reading** — The US Navy does not use `EFS`; Navy fighter/attack squadrons are `VFA`, `VAQ`, `VFC`, etc. This reading would require treating `EFS` as an OCR error or a non-standard local designation. Weak.

3. **Joint reading** — `77 EFS` is the witness's USAF unit, but the witness is using a **Navy-issued debrief form** because the operational range/event involved Navy-administered intake. The form's example filename `VFA-106 HUD.wmv` + the AIM-9x/ATFLIR pre-printed sensor fields all anchor the form to Navy F/A-18 community origination — but the form's instruction `"please report each on a separate form for data collection purposes"` and the SPEAR sanitization clause suggest the form is **used by joint-service aircrew operating in the same training-range / theater environment**. ^[inferred]

**Reading 3 is the operationally most coherent**: the form is a Navy-aviation intake artifact extended for joint-service capture. The 77 EFS pilot completing it on 27 Oct 2020 was in a CENTCOM AOR (consistent with the d58 MDR case-number range being USCENTCOM-prefixed), and the resulting form was routed through the Navy SPEAR pipeline. ^[inferred]

The d55 P-8A / TF 67.1 anchor (first Navy platform) + d58 SPEAR + VFA-106 form-template + AIM-9x/ATFLIR sensor schema now **collectively strengthen** the Navy origination/anchor structure of the series, even where individual artifacts carry USAF user attribution. ^[inferred]

## Behavioral signature — neither pure brief-observation nor pure fire-control pipeline

The d58 datum carries an **operationally distinct signature** from the existing dow-uap behavioral classes:

| Element | d58 value | Compared to |
|---|---|---|
| Group size | 2 contacts | d5-B (2X POSS UAPS), d8 (2X UAPS) — **third multi-object datum** |
| Kinematic interaction within group | **one range fouler was circling around the other** | Novel — first **intra-group interaction** datum in the corpus |
| Disappearance | **gone in 1/30 second** | Novel — first **explicit sub-second-timescale disappearance** datum (compare d55's 2-minute loss-of-visual + d4/d5/d8 ambiguous departure) |
| Visual signature (tally) | 2X RED BLINKING STROBES | Novel — first explicit **strobe-light** morphology call in the dow-uap corpus |
| Radar | **stable trackfile + Cat-1-class lock implied** ("OBTAINED RADAR LOCK") | Anchor of fire-control pipeline analogous to d7's WQT but with attempted-ID closure prevented by 16.9 NM standoff floor |
| Target pod | **TGT POD video acquired; 2 IR significant contacts** | Second sensor-channel datum after d7 TFLIR + d8 implicit WHITE HOT thermal; first explicit `TGT POD video` capture artifact reference |
| Active EM signature | **noise jamming received; indicated by two chevrons** | **Novel — first explicit EW / countermeasures signature** in the dow-uap corpus. "Two chevrons" is a Navy radar warning receiver (RWR) display convention. ^[inferred] |
| Standoff floor | 16.9 NM minimum approach | Novel — first explicit closest-approach data (vs d7's bearing-only standoff) |
| Aircraft posture | KINGPIN-directed ID; DCA mission | Aircraft-side posture is **intercept / identification**, not weapons-quality engagement-pipeline (no NTS / no shoot stance) |

**The signature is a sixth distinct behavioral sub-class** within the dow-uap corpus — call it provisionally the **range-fouler-attempted-ID class**: radar-lock + sensor-pod-confirmed multi-object encounter with intra-group kinematic interaction, sub-second disappearance, and active electronic-warfare reception, conducted under directed-intercept posture (KINGPIN tasking) without a fire-control / weapons-employment pipeline. ^[inferred]

This is **neither** d7's aircraft-toward-UAP fire-control pipeline (no WQT / NTS / TFLIR-ID-and-decline) **nor** the d4/d5/d8 brief-observation kinematic-anomaly sub-class (which lacks sensor-pod confirmation, multi-radar-channel data, and explicit EW signature). The class is closer to the **multi-sensor proximity-encounter** lineage of [[references/sighting-helicopter-orb-encounter-2025|the 2025 helicopter-orb encounter]] — but in a 2020 Navy training-range / CENTCOM-AOR context with attempted-intercept posture.

The **1/30-second disappearance** + **noise-jamming reception** pairing is the **strongest UAP-side capability signature** in the dow-uap corpus so far. ^[inferred] The 1/30-second figure matches the **30-fps standard frame rate** of the era's TGT-pod video — the witness is plausibly reporting "one video frame to the next" as the resolution unit of the disappearance, which would imply a **between-frame departure faster than any conventional aircraft can perform** at the closest-approach floor (16.9 NM). ^[inferred] At 16.9 NM (~31.3 km), a between-frame disappearance implies an exit velocity **>30 km / 0.033 s ≈ 900 km/s ≈ Mach 2,650** if interpreted as linear motion — which it almost certainly is not; more probably the object went sub-radar / sub-sensor (cloaking, sensor occlusion, or genuinely-anomalous escape). ^[inferred]

## Release framework — confirms d55's MDR + AARO stamp at N=2

The d58 release block is **byte-for-byte identical** to d55's release block on the four MDR/AARO/date/sequence axes:

| Field | d55 (18 Nov 2016 P-8A Syria) | d58 (27 Oct 2020 77 EFS) | Match? |
|---|---|---|---|
| Declassification authority | MG Richard A. Harrison | MG Richard A. Harrison | **MATCH** |
| MDR case range | USCENTCOM MDR 26-0038 to MDR 26-0046 | USCENTCOM MDR 26-0038 to MDR 26-0046 | **MATCH** |
| Routing stamp | Approved for Release to AARO | Approved for Release to AARO | **MATCH** |
| Release-stamp date | 03/27/26 | 03/27/26 | **MATCH** |
| Release sequence number | 000001 | 000001 | **MATCH** |

**Three findings flow from this**:

1. **AARO-receiving-authority closure firms from partial to confirmed at N=2.** The ^closed-by-dow-uap-d55 annotation on [[entities/dow-uap-foia-release]] was conditional on stamp recurrence; d58 *is* that recurrence. The closure should be promoted with a `^closed-by-dow-uap-d58` recurrence anchor. ^[inferred]

2. **MDR scope partial-resolution: 2-of-2 testable artifacts carry the identical 9-case `26-0038 to 26-0046` range.** The d55 open question "Does the same MDR range cover all 40 dow-uap artifacts, or only the Eastern-Mediterranean / CENTCOM-AOR subset?" now has a partial answer: **the d55 (USCENTCOM AOR, P-8A Syria) and d58 (CENTCOM AOR likely — see below) range covers both artifacts**. ^[inferred] If the same range covers all 9 documents in the 9-case allocation, the dow-uap release tranche may include 9 of its ~40 artifacts under this one MDR.

3. **Identical `000001` release-sequence number on two different documents is ambiguous.** ^[ambiguous] Three readings live: (a) the sequence number is **per-MDR-case** (so each document under MDR 26-00xx gets its own `000001`); (b) the sequence number is **per-batch-release** (so the entire 9-case batch was released as one `000001` lot); (c) **OCR artifact** — the actual sequence numbers differ but rendered identically at this OCR DPI. Reading (a) is most consistent with FOIA / MDR-release practice; reading (b) would be unusual. ^[inferred] Reading (c) is implausible given the sharp rendering of other fields.

The d58 + d55 pair also confirms `U.S.C. 3 / Section 3.1` (d58 only) → almost certainly **EO 13526 §3.1 declassification-authority citation** rather than literal 50 U.S.C. § 3 ^[inferred] — see top-of-page reading above.

## CENTCOM-AOR inference — supporting evidence

The d58 form's filled-in fields don't carry an explicit AOR or theater designator. Three lines of circumstantial evidence place d58 in CENTCOM AOR:

1. **MDR case-number prefix `USCENTCOM`** — the case range originated in the USCENTCOM declassification pipeline, suggesting USCENTCOM-AOR equity. ^[inferred]
2. **77 EFS — USAF Expeditionary Fighter Squadron** designator implies forward deployment, and 77th FS rotations through USAFCENT (Al-Udeid, Al-Dhafra, Prince Sultan AB) are documented in open USAF rotation literature. ^[inferred]
3. **`KINGPIN`** — a CENTCOM-AOR airborne-controller / GCI callsign. ^[inferred] Cross-references in open military literature place `KINGPIN` as a controller callsign used in CENTCOM operations in the late-2010s / early-2020s window.

The filename token `na` (no theater) is **honest** — the form genuinely doesn't carry a recoverable AOR field. This is structurally analogous to [[references/dow-uap-d54-mission-mediterranean-sea|d54]]'s `-na` date token (also honest). ^[inferred]

## Filename-vs-internal-document — d58 verifies the date axis at N=2

The filename `dow-uap-d58-range-fouler-debrief-na-october-2020.json` carries two label tokens:

| Filename axis | Filename token | Internal value | Match? |
|---|---|---|---|
| Theater | `na` | No internal AOR/coordinate; CENTCOM-AOR inferred via MDR / KINGPIN | **honest "na"** — neither verifies nor contradicts |
| Date | `october-2020` | **10/27/20** (body text) | **MATCH** |

**Second filename-date-internally-verified artifact** in the corpus, after [[references/dow-uap-d55-mission-syria-2016-11-18|d55]] (`november-2016` ↔ internal `18 Nov 2016`). ^[inferred]

In the dow-uap mission-record / debrief subset, the date-axis verification record now reads:

| File | Filename date | Internal date | Match? |
|---|---|---|---|
| `d4` | `2020` | (none) | untestable |
| `d5` | `2020` | (none) | untestable |
| `d7` | `2020` | (none) | untestable |
| `d8` | `2025` | (none) | **verified via release-framework forensics** (FIN+SWE+FVEY+NATO ⇒ release floor ≥ Mar 2024) |
| `d52` | `august-2024` | `31 OCT 24` | **MISMATCH** |
| `d54` | `-na` | (none) | honest |
| `d55` | `november-2016` | `18 Nov 2016` | **MATCH** |
| `d50` | `april-2025` | `10APR25 / 11APR25` | **MATCH** |
| `d58` | `october-2020` | `10/27/20` | **MATCH** |

The filename **date** axis is now **3-of-4 verified** (d50 + d55 + d58 verified, d52 mismatched, d8 verified-by-forensics, d4/d5/d7/d54 untestable). The dominant pattern at N=4 testable is **honest date labeling** (3 verified + 1 contradicted). ^[inferred]

## Anchoring the document class: range-fouler debrief at N=1

The dow-uap series's **second top-level non-mission-report document class** is now anchored: **range-fouler debrief**. At N=1 the document-class template is:

- **Fielded form** (not free-text narrative) — pre-printed schema with witness-completed values
- **Defined identity block** (Last Name / First Name / Rank / Squadron / Crew Position / SIPR Email)
- **Defined event metadata** (Date / Time-Z / Day-Night / Side No / Buno / Mission Description / LFE flag)
- **Defined position grid** (Working Area / Lat-Long / Altitude + Altitude-Constant? / Wind Dir + Speed / Was-Moving + Direction-Speed)
- **Sensor + track grid** (Radar Equipped / Stable Trackfile / # Contacts in Group / AIM-9x Self-Track / ATFLIR Autotrack / Tally Achieved)
- **Morphology checkbox grid** (12 categories: Round / Square / Balloon / Wings / Other-shape / Propulsion / Moving-parts / Metallic / Markings / Translucent / Opaque / Reflective)
- **Free-text narrative block** (witness's own description)
- **Submission-instruction block** (`Date_Squadron_RF.pdf` filename schema + email-to address + display-tape `.wmv` upload requirement)
- **Centralized SPEAR sanitization** (all reports stripped of identifying information for analysis)
- **Standard dow-uap release framework** (USCENTCOM MDR + AARO routing + `03/27/26 000001`)

[[references/dow-uap-d44-range-fouler-arabian-sea-october-2020|d44]] (next in the size-ordered queue, also October 2020) is expected to **validate the class at N=2** and may extend the template with additional captured fields. ^[inferred]

The **mission-record / debrief document-class taxonomy** now stands at **three top-level classes ingest-verified**:

1. **Mission report — USMTF GENTEXT/UAP format** (d4 + d5 + d7 + d54 + d8 = 5 ingests, 6 datums)
2. **Mission report — CTG narrative format** (d55 = 1 ingest)
3. **Range-fouler debrief — fielded form** (d58 = 1 ingest; **NEW class anchor**)

…plus the **email-correspondence class** (d52 + d50) and the **prepublication-clearance class** (PR20) for cover-artifact types. The dow-uap corpus is now structurally taxonomized into **5 document classes** at N=10 ingests.

## Bibliographic frame

| Field | Value |
|---|---|
| Source basename | `dow-uap-d58-range-fouler-debrief-na-october-2020.json` |
| Source bytes | 3,416 |
| OCR engine | `mistral-ocr-latest` (`usage_info.pages_processed: 1`) |
| Original document size | 301,419 bytes (`usage_info.doc_size_bytes`) |
| Pages OCR'd | 1 (all substantive — no header-only padding around this class, unlike mission reports) |
| Images / tables / hyperlinks | All null in OCR |
| Classification (extracted) | EO 13526 §1.4(a) ^[inferred] (no per-page `# 1.4(a)` header on this 1-page artifact); §3.1 declassification-authority citation (OCR'd as `U.S.C. 3 / Section 3.1`) ^[inferred] |
| Declassification authority | **MG Richard A. Harrison, USCENTCOM Chief of Staff** (same as d55) |
| Release stamp date | 27 March 2026 (`03/27/26`) — same as d55 |
| Receiving authority | **AARO** (`Approved for Release to AARO`) |
| MDR case range | `26-0038 to 26-0046` — identical to d55 |
| Release sequence # | `000001` — identical to d55 (anomalous; flagged) |
| Document class | Range-fouler debrief — fielded form (NEW class anchor at N=1) |
| Document-class abbreviation | `RF` (per the form's filename schema `Date_Squadron_RF.pdf`) |
| Intake pipeline | **SPEAR** (first explicit data-pipeline / intake-system name in the dow-uap corpus) |
| Originating service | **Mixed** — 77 EFS (USAF) user; Navy-aviation-community form (VFA-106 example template, AIM-9x + ATFLIR sensor pre-prints); SPEAR centralized intake. ^[inferred] |
| Originating unit (user) | **77 EFS** (USAF 77th Expeditionary Fighter Squadron) ^[inferred] |
| Series | [[entities/dow-uap-foia-release\|DoW-UAP FOIA release]] |
| Series position | 10-of-40 by ingest order (first range-fouler debrief artifact) |
| Event date | **27 October 2020 0112:21Z** — body-text calendar date; verifies filename `october-2020` |
| Event night/day | **Night** |
| Theater | CENTCOM AOR ^[inferred] (no explicit AOR field; MDR-prefix + 77 EFS rotation history + KINGPIN callsign collectively imply CENTCOM) |
| Object count | 2 |
| Object morphology | Balloon-shaped + Other-shape + Metallic + Opaque + Reflective (checkboxes) ↔ Red blinking strobes (narrative) |
| Object kinematic | 060°/20 KT slow drift (form); one circling around the other (narrative); 1/30-s disappearance |
| UAP-side kinematics | Slow drift + intra-group circling + sub-second disappearance |
| Sensor signature | Radar lock (stable trackfile, "Other" radar type); target-pod video; 2 IR-significant contacts; noise jamming received (2 chevrons RWR display) |
| Closest approach | 16.9 NM minimum standoff |
| Aircraft posture | KINGPIN-directed intercept ID (DCA mission, not LFE); no fire-control / weapons pipeline |

## Structural firsts the d58 ingest anchors

d58 introduces or extends the following in the dow-uap corpus (N=10 ingests):

1. **First range-fouler debrief artifact** — anchors a new top-level document class (now 5 classes ingest-verified). ^[inferred]
2. **First fielded-form artifact** in the dow-uap corpus — non-narrative, schema-driven capture. Distinct from USMTF mission reports, CTG-narrative reports, email correspondence, and DOPSR clearance stamps. ^[inferred]
3. **First explicit data-pipeline name** — **SPEAR**. First named intake/sanitization pipeline in the corpus. ^[inferred]
4. **First explicit Navy-aviation FRS reference in template text** — `VFA-106 HUD.wmv` example filename. Strengthens the Navy-origination structural reading at the template level even where the user is USAF. ^[inferred]
5. **First explicit pre-printed sensor option set** — `AIM-9x Self-Track` + `ATFLIR Autotrack` checkboxes (Navy F/A-18 community). Confirms the Navy origination of the form. ^[inferred]
6. **First explicit class-abbreviation in a filename schema** — `_RF` in `Date_Squadron_RF.pdf`. ^[inferred]
7. **Confirms d55's release framework at N=2** — identical MDR / AARO / Harrison / date / sequence. **Firms the AARO-receiving-authority closure** (^closed-by-dow-uap-d58, recurrence anchor on top of d55's initial closure). ^[inferred]
8. **First multi-document attestation of `USCENTCOM MDR 26-0038 to MDR 26-0046`** — partial resolution of the d55 open question on whether the MDR range covers the whole tranche or just a CENTCOM sub-batch. 2-of-2 testable artifacts carry the same range. ^[inferred]
9. **First identical-`000001`-release-sequence-number datum across two documents** — ^[ambiguous] per-case vs per-batch vs OCR-artifact readings.
10. **First "Range Fouler" textual definition by usage** — the corpus now carries operational definition by example. Range fouler = unidentified contact intruding on/around a training-range or operational area requiring directed intercept identification, per Navy-aviation usage. ^[inferred] See [[concepts/range-fouler]] for the concept-level treatment.
11. **First explicit night-time UAP encounter** in the dow-uap corpus — `Day/Night: Night` field. d4 + d5 + d7 + d8 didn't carry day/night; d54 was during RTB (time unattested for day/night). d55 was daytime (1310Z + 18 Nov 2016 + Eastern Med = late morning local). ^[inferred]
12. **First explicit body-text calendar date in a 2020-event dow-uap artifact** — d4/d5/d7 carry the `2020` filename token but no internal date; d58 carries `10/27/20` body date, the corpus's earliest internal-date-bearing 2020-event artifact. ^[inferred]
13. **First multi-object datum with explicit intra-group kinematic interaction** — `ONE RANGE FOULER WAS CIRCLING AROUND THE OTHER`. d5-B and d8 reported multi-object UAPs but no within-group interaction. ^[inferred]
14. **First explicit sub-second-timescale disappearance** — `IN 1/30TH OF A SECOND, THEY WERE GONE`. The 30-fps TGT-pod frame-rate reading makes this an inter-frame disappearance, structurally the **strongest UAP-side anomalous-departure signature** in the corpus. ^[inferred]
15. **First explicit electronic-warfare / EW reception event** in the dow-uap corpus — `NOISE JAMMING WAS RECEIVED. NOISE JAMMING WAS INDICATED BY TWO CHEVRONS`. RWR-display two-chevron convention indicates a noise-jamming source bearing-localized by the aircraft's receiver. ^[inferred] First active EM signature attributed to the UAPs.
16. **First red-blinking-strobe morphology call** in the dow-uap corpus — `2X RED BLINKING STROBES`. Distinct from d8's white-hot thermal polarity, d54's triangular-metallic, d7's balloon, d4/d5's no-morphology. ^[inferred]
17. **First explicit closest-approach floor** in the corpus — `UNABLE TO GET CLOSER THAN 16.9NM`. Establishes UAP-side standoff capability against directed-intercept posture. ^[inferred]
18. **First explicit Navy-aviation tactical-controller callsign** — `KINGPIN`. ^[inferred]
19. **First explicit `DCA` mission classification** in the corpus — Defensive Counter Air. ^[inferred]
20. **Provisional fourth USAF unit anchor** — `77 EFS` (if the USAF reading holds; the joint-service reading remains open). ^[inferred]
21. **Sixth distinct behavioral sub-class** in the corpus — *range-fouler-attempted-ID class* (radar-lock + sensor-pod-confirmed multi-object + intra-group interaction + sub-second disappearance + noise jamming + KINGPIN-directed intercept + 16.9 NM standoff). Distinct from d7's fire-control pipeline and from d4/d5/d8's brief-observation kinematic-anomaly. ^[inferred]

## Behavioral classification

Per the [[concepts/uap-aircraft-engagement|UAP–Aircraft Engagement]] framework:

- **UAP-toward-aircraft engagement-class**: **partial** — no close approach (16.9 NM floor blocks the ≤30 m criterion), no co-location, no target switching across aircraft. Standoff floor + circling intra-group + sub-second disappearance is a **distinct close-encounter-prevention signature**, not engagement. ^[inferred]
- **Aircraft-toward-UAP engagement-pipeline**: **partial** — radar lock + target-pod video acquired + tally achieved, but the 16.9 NM standoff prevented "better ID" and there is **no weapons-quality / NTS / shoot-stance attestation**. Closer to d7's intercept posture than to a fire-control pipeline, but stopped at *intercept-blocked* rather than *fire-control-engaged*. ^[inferred]
- **New sub-class within brief-observation framing**: *range-fouler-attempted-ID class* (sixth sub-class). ^[inferred] Adds to: kinematic-anomaly (d4/d5-B/d8), steady-state cruise (d5-A), prosaic-candidate-wind-borne (d7), morphology-rich kinematics-thin (d54), prosaic-candidate-with-explicit-CTG-identification (d55).

The 1/30-second-disappearance + noise-jamming + 16.9-NM-standoff triad makes d58 the **most-capability-implying dow-uap datum to date** — the UAPs demonstrate radar-evasion (rapid departure), active-EW emission (noise jamming), and active-standoff maintenance (preventing closure) **simultaneously**. ^[inferred]

## OCR ambiguities

- **`1,4a` / `1.4a` redaction shorthand** — appears in two places in the narrative. Almost certainly the `(b)(6)` / `(b)(3)` / EO 13526 §1.4(a) portion-redaction notation rendered with OCR-corruption (comma-vs-period, missing parentheses). ^[ambiguous] Three readings live: (a) `1.4a` as EO 13526 §1.4(a) classification marking embedded as a portion-marker (consistent with the per-page `# 1.4(a)` convention in the mission-report class); (b) `(b)(6)` rendered ambiguously (witness-identity redaction); (c) a distinct local redaction shorthand specific to the range-fouler form. Reading (a) is most probable. ^[inferred]
- **`U.S.C. 3 / Section 3.1`** — almost certainly **EO 13526 §3.1** (declassification authority) rendered as `U.S.C. 3`. ^[inferred] No 50 U.S.C. § 3 / § 3.1 declassification authority exists in US Code that would apply to UAP-class records.
- **`B/E ZIM 248/17`** — bullseye-relative bearing 248° at range 17 (nautical miles, by convention). `ZIM` is the bullseye name/callsign — irrecoverable from this artifact (could be a fixed range-anchor point in CENTCOM AOR). ^[inferred] First explicit bullseye-coordinate datum in the corpus.
- **`TARGET POD SHOWN`** — almost certainly `TARGET POD SHOWED`. ^[inferred] Minor grammatical OCR artifact.
- **`TRIANGLUAR`** elsewhere in series (d54) → **`TRIANGULAR`** is a corpus-wide OCR pattern of transposed-letter corruption. d58 doesn't carry this specific token but the OCR-corruption discipline is similar.

## Open questions

- **Confirm 77 EFS as USAF Expeditionary Fighter Squadron** — open-source rotation history of USAF 77th FS deployments to USAFCENT (Al-Dhafra / Al-Udeid) would confirm CENTCOM-AOR placement in Oct 2020. ^[inferred]
- **Recover SPEAR program identification** — Navy-aviation intelligence-analysis pipeline likely related to ATFLIR sensor-data analysis or carrier-air-wing range-management. Open-source SPEAR references should be locatable. ^[inferred]
- **Recover the `KINGPIN` controller designation** — CENTCOM-AOR airborne-controller callsign; theater identification would tighten the d58 AOR inference.
- **Recover the bullseye `ZIM`** — bullseye name keyed to a specific operational area in CENTCOM AOR. ^[inferred]
- **Validate the document class at N=2** — [[references/dow-uap-d44-range-fouler-arabian-sea-october-2020|d44]] (next in queue, also October 2020) will confirm the schema, extend the morphology / sensor checkbox set, and may anchor a paired-incident dataset given the date proximity. ^[inferred]
- **Resolve `000001` release-sequence-number identicality** — per-MDR-case vs per-batch vs OCR-artifact. The next dow-uap ingest with a different release-stamp date or different MDR-case prefix will disambiguate. ^[ambiguous]
- **Test the "VFA-106 + AIM-9x + ATFLIR = Navy-aviation form-origination" reading** — if later range-fouler debriefs are filled by Navy aircrew (VFA squadrons), the joint-service-use hypothesis stabilizes; if all carry USAF-EFS user attribution, the form is *Navy-template / USAF-use* and the service-mixing is asymmetric. ^[inferred]
- **Test the multi-document-MDR coverage hypothesis** — d55 + d58 share the identical 9-case MDR range. Does the next dow-uap ingest carry the same range, a different USCENTCOM MDR range, or a different MDR pipeline entirely? If the same range covers more than 9 documents, the case-numbering convention is non-standard. ^[inferred]
- **Test the 1/30-second-disappearance pattern** — does this sub-frame-resolution signature recur in later range-fouler debriefs (where 30-fps TGT-pod video is the sensor-channel ground truth)?
- **Test the noise-jamming-from-UAP pattern** — does active-EW emission recur in later dow-uap ingests, or is d58 isolated? If recurrent, the dow-uap corpus carries an active-emitter UAP signature class distinct from passive sensor-channel observations.
- **Map the relationship between SPEAR and AARO** — both are centralized UAP intake/analysis pipelines. SPEAR (Navy-aviation, range-management, training-range-class events) may feed AARO downstream, or run parallel. ^[inferred]

## See also

- [[entities/dow-uap-foia-release]] — Series-level anchor (d58 is the 10-of-40 ingest, first range-fouler debrief artifact, anchors the third top-level mission-record document class)
- [[concepts/range-fouler]] — Concept-level page on the range-fouler operational concept (anchored at N=1 by d58; extended at N=4 with d38 + d56 + d44; d58 capability-triad isolated at 1-of-4)
- [[references/dow-uap-d38-range-fouler-middle-east-may-2020]] — **Range-fouler sister at N=2** — 14 May 2020 Persian Gulf coast ISR ^[inferred]; passive-ISR sub-class; **earliest range-fouler in the corpus** (5 months before d58); **carries distinct release-framework Block B** (`MDR 26-0019` + `01/26/26 001`) breaking the byte-for-byte release-block recurrence anchored at d55+d58
- [[references/dow-uap-d44-range-fouler-arabian-sea-october-2020]] — **Range-fouler sister at N=3** — 15 Oct 2020 Gulf of Aden daytime, 172 ATKS MQ-9 ^[inferred]; passive-ISR sub-class — sits 12 days earlier than d58 in same AOR with structurally identical form but divergent capability signature
- [[references/dow-uap-d56-range-fouler-arabian-sea-august-2020]] — **Range-fouler sister at N=4** — 24 Aug 2020 North Arabian Sea night SSC, **HSM-73 MH-60R Romeo Seahawk** ^[inferred] — **first internal Navy user anchor in range-fouler subset**; firms Block A 4-of-5 dominance with d55+d58+d44; structure-CONFIRMED at N=4 on 13-of-13 axes; isolates d58's capability triad at 1-of-4
- [[references/dow-uap-d55-mission-syria-2016-11-18]] — Sixth substantive mission-record ingest — **release-framework twin to d58** (identical MDR + AARO + Harrison + `03/27/26 000001`); the d55 + d58 pair firms the AARO-receiving-authority closure at N=2 and supplies first MDR-coverage datum
- [[references/dow-uap-d60-mission-persian-gulf-2020-08-08]] — **First FULL USMTF Misrep parent document** in dow-uap corpus (8 Aug 2020 Arabian / Persian Gulf, 482ATKS / 432 AEW MQ-9 ^[inferred] NAVCENT-support); same Block A release framework as d58. d60 **decisively closes the `000001` open question** at d58 — per-document page-sequence-number reading confirmed (d60 carries sequential `000001 → 000006` across 6 pages).
- [[references/dow-uap-pr20-prepublication-clearance-2026-03]] — Series prepublication-clearance cover stamp
- [[references/dow-uap-d4-mission-arabian-gulf-2020]] — First substantive mission report — kinematic-anomaly
- [[references/dow-uap-d5-mission-arabian-gulf-2020]] — Second substantive mission report — two-sighting + multi-object first instance
- [[references/dow-uap-d7-mission-arabian-gulf-2020]] — Third substantive mission report — first balloon-morphology + first aircraft-toward-UAP fire-control pipeline (closest behavioral analog to d58's intercept posture, but with weapons-quality pipeline that d58 lacks)
- [[references/dow-uap-d54-mission-mediterranean-sea]] — Fourth substantive mission report — first triangular-metallic morphology + first internally-verifiable filename
- [[references/dow-uap-d8-mission-djibouti-2025]] — Fifth substantive mission report — first FIN+SWE+FVEY+NATO release authorization + first round/orb-class morphology + first implicit thermal-sensor channel
- [[references/dow-uap-d52-email-na-2024]] — First email-correspondence artifact — first USAF unit anchor (15 AF / DET 1)
- [[references/dow-uap-d50-email-indopacom-2025-04]] — Second email-correspondence artifact — first OUSD(I&S) office attribution + third USAF unit anchor (12 AF / DET 3)
- [[concepts/uap-aircraft-engagement]] — Behavioral framing; d58 sits in the new **range-fouler-attempted-ID sub-class** (6th brief-observation sub-class)
- [[concepts/orb-phenomenon]] — Adjacent — d58's `2X RED BLINKING STROBES` morphology is not orb-class proper but shares the lighting-signature lineage
- [[entities/aaro]] — d58's `Approved for Release to AARO` stamp recurrence confirms AARO as the dow-uap receiving authority at N=2
- [[entities/ryan-graves]] — Former US Navy F/A-18F pilot; closest analog operational context for the Navy-aviation form template + AIM-9x/ATFLIR sensor schema
- [[projects/uap/uap]]
