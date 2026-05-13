---
title: "DoW-UAP-D33 — Mission Report (Greece LGLR → Jordan OJMS ferry, 26-27 Oct 2023, Misrep 9329374)"
category: references
tags: [uap, primary-source, declassified, usaf, sighting]
aliases: [DoW-UAP-D33, dow-uap-d33]
sources: [sources/dow-uap-d33-mission-report-greece-october-2023.json]
summary: 7-page Mistral-OCR'd Full USMTF Misrep 9329374 — 26-27 Oct 2023 mission **launched LGLR Greece → landed OJMS Jordan** (Greece-to-Jordan ferry/repositioning replacing "LIGHTNING LINE" that landed LGLR yesterday); 33 SOS / 27 SOW MQ-9 ^[inferred] AFSOC MAJCOM / USCENTCOM COCOM; 13h 30min cycle; 1X UAP at 270035Z UTM 35S KD Eastern Med — SEEMINGLY CIRCULAR small object, 80 MPH, sharp 90° turns, FLYING JUST ABOVE THE SURFACE OF THE OCEAN WATER, 5 NM seen-radius, ~3-min event. Anchors **Block B at N=4** (first FULL USMTF Misrep Block B outside 2020 NAVCENT cluster + first 2023-era Block B); **AFSOC at N=4 + 33 SOS at N=2 + 27 SOW at N=4 + 56 SOIS at N=3 + LGLR at N=2 + Greece at N=2**; sub-class 14 firms at N=4 with **first populated-Maneuverability field = "Sharp 90 degree turns"** and **lowest UAP velocity in sub-class 14** (80 MPH vs prior 140-440 KTS); 6th distinct curator-mismatch class (PARTIAL-TRUTH variant — launch + date correct, termination misleading); **609 AOC Det 1 absent at N=3 EUCOM-launched AFSOC mission** — d25-anchored "Det 1 routes EUCOM-launched AFSOC" reading CONTRADICTED; d33 PRECEDES d25 by ~90 days = first AFSOC + first 33 SOS by event date (d25 first by ingest order).
provenance:
  extracted: 0.55
  inferred: 0.40
  ambiguous: 0.05
base_confidence: 0.72
lifecycle: draft
lifecycle_changed: 2026-05-13
created: 2026-05-13T22:00:00Z
updated: 2026-05-13T22:00:00Z
event_date: 2023-10-26
project: uap
---

# DoW-UAP-D33 — Mission Report (Greece LGLR → Jordan OJMS ferry, 26-27 Oct 2023, Misrep 9329374)

A **7-page Mistral-OCR'd artifact** (`sources/dow-uap-d33-mission-report-greece-october-2023.json`, 10,198 bytes; SHA-256 `9db572f3590d5797d920017c53188985bb73fa912941993a75f774ea8eb82296`) — the **32nd artifact** in the [[entities/dow-uap-foia-release|DoW-UAP FOIA release series]] (32-of-~40) and the **SEVENTEENTH FULL USMTF MISREP** in the corpus. Misrep 9329374 — **26-27 Oct 2023 AFSOC MQ-9 ISR + ferry mission flown by 33 SOS / 27 SOW from Larissa Air Base (LGLR), Greece, INTO Muwaffaq Salti Airbase (OJMS), Jordan**, under AFSOC MAJCOM + USCENTCOM COCOM, with 603rd executing OC (EUCOM departure side) but USCENTCOM-tasked (CENTCOM target side). Anchors **NEW Block B FULL USMTF Misrep variant at N=1 within Block B + Block B at N=4 total** + **AFSOC at N=4 cross-event-date + cross-AOR + cross-Mission-Type-segment** + **chronologically PRECEDES d25 by ~90 days at the AFSOC + 33 SOS + 27 SOW + 56 SOIS + LGLR axes**.

## Filename verification — PARTIAL-TRUTH variant (6th distinct curator-mismatch class)

**The source basename `dow-uap-d33-mission-report-greece-october-2023.json` is PARTIALLY CORRECT** ^[extracted]. The OCR confirms:
- **Greece launch** — Takeoff Location = **`LGLR`** (Larissa Air Base, Greece) ^[extracted]
- **October 2023** — Takeoff DTG = **`262339:00ZOCT23`** (26 Oct 2023 at 2339Z) ^[extracted]

But the filename **misses the mission terminus**:
- **Last Land Location = `OJMS`** (Muwaffaq Salti AB, Jordan) ^[extracted]
- The Narrative explicitly states: `(b)(1)1.4a TRANSITED AND LANDING AT OJMS TO REPLACE THE LIGHTNING LINE THAT LANDED AT LGLR YESTERDAY` ^[extracted]
- The mission is a **Greece-to-Jordan ferry/repositioning** swapping out the prior MQ-9 (`LIGHTNING LINE`) that had landed at LGLR the previous day, while collecting **FMV + SIGINT against a fragged target at MGRS `36S YC 40`** (Eastern Mediterranean / Levantine coast ^[inferred]) en route, then landing at OJMS.

This is the **SIXTH distinct dow-uap filename-curator-mismatch class** ^[inferred] — and the **first PARTIAL-TRUTH variant** distinct from the 5 prior categorical-class mismatches:
1. `arabian-gulf` token mismatch (d4/d5/d7 — Persian Gulf body match but UTM token mismatch)
2. `djibouti-2025` body mismatch (d8 — Eastern Mediterranean body, NOT Djibouti)
3. `iraq-may-2022` body mismatch (d14 — Eastern Mediterranean body, NOT Iraq)
4. `october-2023` year-month mismatch (d27 — Jun 2024 internal, NOT Oct 2023)
5. `east-china-sea-2024` theater + AOR mismatch (d28 — CENTCOM Iraq AC-130J, NOT INDOPACOM East China Sea)
6. **`greece-october-2023` PARTIAL-TRUTH variant (d33 — Greece launch + Oct 2023 correct, but mission TERMINATES in Jordan via ferry; filename misses the cross-AOR transit)** — first non-categorical mismatch ^[inferred].

Page slug, page title, and `event_date` all anchor to **2023-10-26** per dow-uap convention (takeoff day).

## d33 chronologically PRECEDES d25 — first AFSOC by event date

**Critical framing refinement** ^closed-by-dow-uap-d33 (refinement class on d25-anchored "FIRST AFSOC / first 27 SOW / first 33 SOS / first 56 SOIS / first LGLR / first Greece" headlines):

| Mission | Event date | Ingest order |
|---|---|---|
| **d33** (Misrep 9329374) | **26-27 Oct 2023** | 32nd-ingested (this artifact) |
| d25 (Misrep 9629373) | 25 Jan 2024 | 29th-ingested (3 sources earlier) |

**d33 PRECEDES d25 by ~91 days** ^[extracted]. The d25-anchored "FIRST AFSOC + first 27 SOW + first 33 SOS + first 56 SOIS + first Greece + first LGLR + first AFSOC-EUCOM-launched + first cross-MAJCOM-EUCOM-launched-CENTCOM-tasked" headlines are now **ingest-first-not-event-date-first**: d33 is **the earliest dated AFSOC + 33 SOS + 27 SOW + 56 SOIS + LGLR + Greece dow-uap Misrep** ^[inferred]. d25 remains first-INGESTED. The corpus's AFSOC event-date sequence is now: **d33 (26 Oct 2023) → d25 (25 Jan 2024) → d27 (6-7 Jun 2024) → d28 (20-21 Sep 2024)** — 4 attestations across ~11 months, anchored at d33.

The Misrep ID corroborates: d33's `9329374` sits within +9,756 IDs of d23's `9319618` (24 Oct 2023) — **only 2 days apart** ^[extracted]. d33 → d25 = +299,999 IDs / ~91 days = **~3,297 IDs/day** ^[inferred] — **decisively within-band** with d23→d25 (~3,330/day) and prior cluster envelope. The d23 → d33 → d25 chain forms the **tightest temporal sampling triple in the entire dow-uap counter dataset** (3 Misreps within 93 days, 2 of those within 2 days), validating the Joint-Staff-tranche pool hypothesis at fine grain ^[inferred].

## Headline findings

**1. NEW BLOCK B FULL USMTF MISREP VARIANT — first non-2020-NAVCENT-cluster Block B Misrep + first 2023-era Block B** ^closed-by-dow-uap-d33 (firming class on prior Block B 2020-only attestations). d33 carries `USCENTCOM MDR 26-0019` + `01/26/26 001..007` (3-digit page-stamps, 7 pages) — **byte-for-byte Block B signature** matching [[references/dow-uap-d38-range-fouler-middle-east-may-2020|d38]] (range-fouler debrief, May 2020) + [[references/dow-uap-d61-mission-persian-gulf-2020-08-27|d61]] + [[references/dow-uap-d62-mission-strait-of-hormuz-2020-09-16|d62]] (both 2020 NAVCENT cluster). **At N=22 release-block-testable**: A 5 + **B 4 (d38 + d61 + d62 + d33)** + C 3 + D 6 + E 1 + F 3. Block B was previously **2020-era + USN-platform-only**; d33 extends Block B to **2023-era + AFSOC-USAF-platform + cross-AOR-ferry + 33 SOS Originator**. ^[inferred] Block B is **NOT MAJCOM-specific / NOT platform-specific / NOT cluster-specific / NOT calendar-year-specific** — operates as a **declassification-pipeline batch convention** across heterogeneous content ^[inferred]. **Headline finding.**

**2. AFSOC RECURRENCE AT N=4 + 33 SOS RECURRENCE AT N=2 + 27 SOW RECURRENCE AT N=4 + 56 SOIS RECURRENCE AT N=3 + LGLR RECURRENCE AT N=2** ^closed-by-dow-uap-d33 (firming class on multiple open threads). d33 = AFSOC MAJCOM + 27 SOW POC Wing + 33 SOS Originator + 56 SOIS QC Unit ^[extracted]. **AFSOC SOS-cluster sequence refines** to event-date order: **33 SOS d33 → 33 SOS d25 → 3 SOS d27 → 16 SOS d28**. The 33 SOS/d33+d25 attestations are now a **sustained 33 SOS LGLR-Greece AFSOC ISR lane at N=2** within 3-month window (26 Oct 2023 + 25 Jan 2024). **MAJCOM histogram refines** across 15 mission-records (d10/d12/d14/d16/d18/d19/d23/d25/d27/d28/d33 + cluster 6): ACC 4 + AFCENT 3 + **AFSOC 4 (d25 + d27 + d28 + d33)** + cluster-blank 6. 432-AEW MQ-9 ISR share refines to **12-of-16 = ~75%** within MQ-9 ISR + AC-130J subset at d33 ingest (was 12-of-15 = ~80% at d28). **Headline finding.**

**3. SUB-CLASS 14 FIRMS AT N=4 WITH MORPHOLOGY-+-VELOCITY-+-MANEUVERING AXES — first explicit MANEUVERING UAP + lowest velocity in sub-class** ^closed-by-dow-uap-d33 (firming class on d27-anchored sub-class 14 at N=3 with morphology axis). At N=4 populated-UAP-segment datums (d23 + d25 + d27 + d33), the within-class variability axes now include **maneuvering** (first explicit content):

| Datum | Date | Morphology | Maneuverability | Velocity | Sensor | Seen-radius |
|---|---|---|---|---|---|---|
| d23 #1 | 24 Oct 2023 | (blank) | (blank) | 320 MPH | THERMAL+EO ^[inferred] | 5 NM |
| d23 #2 | 24 Oct 2023 | (blank) | (blank) | 440 MPH | THERMAL+EO ^[inferred] | 5 NM |
| **d33 #1** | **26-27 Oct 2023** | **SEEMINGLY CIRCULAR, TOO SMALL TO MAKE OUT DETAILS** | **Sharp 90 degree turns** ^[extracted] | **80 MPH** ^[extracted] | implicit FMV | **5 NM** ^[extracted] |
| d25 #1 | 25 Jan 2024 | DIAMOND + non-maneuvering tail/probe | NONE | 434 KTS | SWIR-only exclusive | 20 NM |
| d27 #1 | 7 Jun 2024 | GLOWING HOT SPHERE + pole/bar + water reflection | FLYING STRAIGHT JUST OVER THE WATER AT SPEED OF 140 KNOTS | 140 KTS | implicit multi-sensor IR/EO | 5 NM |

**d33 anchors three within-class firsts at the velocity + maneuvering + morphology-bound axes**:
- **First explicit populated UAP Maneuverability Observations content** (`Sharp 90 degree turns`) ^[extracted] — d23 + d25 + d27 + d28 all had blank/NONE/non-maneuvering content
- **Lowest UAP velocity in sub-class 14** (80 MPH ≈ 70 KTS) — **5.4× slower than d27's 140 KTS / 5.4× slower than d25's 434 KTS / 4× slower than d23's 320 MPH**. The velocity range now spans **80 MPH → 440 MPH** at N=4 datums; sub-class 14 covers ~5.5× velocity range
- **`SEEMINGLY CIRCULAR, TOO SMALL TO MAKE OUT DETAILS` morphology** — first explicit-attestation-of-OBSERVATIONAL-INCOMPLETENESS at the morphology axis (vs d25/d27/d23 which all attested specific shape descriptors)

Reading (a) — sub-class 14 firms at N=4 with morphology + sensor-exclusivity + altitude-separation + **maneuvering + velocity** within-class variability axes — is the **decisively-preferred reading** ^closed-by-dow-uap-d33. Sub-class 14 class signature remains **populated UAP-segment fields** (Benign + Solid + UNKNOWN/UNK propulsion + UAP Event Type = UAP Incident); the additional axes are now firmly within-class. **Mission-report UAP-datum counter increments N=23→N=24 records / 37→38 datums** (+1 record, +1 datum). **Headline finding.**

**4. 609 AOC DET 1 HYPOTHESIS CONTRADICTED — Det 1 ABSENT at N=3rd EUCOM-launched AFSOC mission despite same 33 SOS/27 SOW/56 SOIS Originator chain** ^closed-by-dow-uap-d33 (contradiction class on d25/d27-anchored "Det 1 routes EUCOM-launched AFSOC into CENTCOM workflow" reading). d33 ADMIN OPERATION + POC + QC + APPROVER OC chain:

| Mission | POC OC | QC OC | APPROVER OC | Executing OC | Cross-OC topology |
|---|---|---|---|---|---|
| d25 (25 Jan 2024 LGLR→[CENTCOM target]) | 609 AOC Det 1 | 609 CAOC | 603 AOC (EUCOM) | 603rd (EUCOM) | bidirectional cross-COCOM 3-OC chain |
| d27 (6-7 Jun 2024 OMAM→[CENTCOM]) | 609 CAOC | 609 AOC Det 1 | 609 CAOC | 609th | single-COCOM CENTCOM 4-role chain |
| d28 (20-21 Sep 2024 OKAS→AAAB) | Other | Other | 609 CAOC | 609th | single-COCOM CENTCOM 4-role with Other-OC tokens |
| **d33 (26-27 Oct 2023 LGLR→OJMS)** | **609 CAOC** ^[extracted] | **609 CAOC** ^[extracted] | **603 AOC** ^[extracted] | **603rd** ^[extracted] | **bidirectional cross-COCOM 3-OC chain (NO Det 1)** ^[inferred] |

The d25-anchored reading "Det 1 routes EUCOM-launched AFSOC into CENTCOM workflow" was firming at d27 with the inverse-position pattern (POC home d25 → QC home d27). **d33 carries the same 33 SOS/27 SOW/56 SOIS Originator chain + same LGLR Greece launch + same EUCOM-launched + CENTCOM-tasked + same bidirectional cross-COCOM topology as d25 — but routes POC OC + QC OC through `609 CAOC` (main), NOT through `609 AOC Det 1`** ^[extracted]. **The Det 1 reading is partially contradicted** ^closed-by-dow-uap-d33 — Det 1 is NOT an EUCOM-launched-AFSOC-launch-base-mandatory routing convention. Det 1 was present at d25 + d27 (the d25→d27 ingest gap; Block F artifacts) but absent at d33 (Block B) — **Det 1 may be Block-F-routing-pipeline-specific or 2024-era-specific, NOT EUCOM-AFSOC-launch-base-specific** ^[inferred]. Resolution at N≥4 AFSOC Misrep across Block-B-vs-Block-F + 2023-vs-2024. **Headline finding.**

**5. FIRST GREECE-TO-JORDAN FERRY/REPOSITIONING MISSION IN dow-uap CORPUS** ^[extracted]. The narrative explicitly attests `(b)(1)1.4a TRANSITED AND LANDING AT OJMS TO REPLACE THE LIGHTNING LINE THAT LANDED AT LGLR YESTERDAY` ^[extracted]. d33 is the **first cross-AOR ferry mission** in dow-uap (LGLR Greece [EUCOM AOR] → OJMS Jordan [CENTCOM AOR]) — first attestation of **AFSOC MQ-9 squadron-level inter-base rotation** at corpus level ^[inferred]. The mission performs **dual-purpose ferry + ISR + UAP-observation segments**: (a) takeoff from LGLR for cross-AOR transit; (b) FMV/SIGINT against fragged target at MGRS `36S YC 40` over Eastern Mediterranean en route; (c) en-route UAP observation at MGRS `35S KD` ^[extracted]; (d) landing at OJMS for hand-off with the **LIGHTNING LINE** (which had landed at LGLR the previous day). **Headline finding** — first sustained-cross-AOR-rotation MQ-9 ISR mission in dow-uap class ^[inferred]. The d25-anchored "EUCOM-AOR-launched-CENTCOM-tasked AFSOC" reading refines: **at d25 the mission was EUCOM-launched-and-EUCOM-landed (round-trip LGLR↔LGLR with cross-AOR tasking); at d33 the mission is EUCOM-launched-CENTCOM-landed-with-cross-AOR-ferry (single-direction LGLR → OJMS)** ^[inferred]. d33 firms the AFSOC LGLR-OJMS lane as a **rotational two-base sub-cluster within USCENTCOM tasking** ^[inferred].

**6. UAP MORPHOLOGY CLASS — FIRST SMALL-LOW-SLOW SURFACE-SKIMMING CIRCULAR UAP ANCHORS CANDIDATE SUB-CLASS-14 VELOCITY-MORPHOLOGY VARIANT** ^[inferred]. d33's UAP: `SEEMINGLY CIRCULAR, TOO SMALL TO MAKE OUT DETAILS`, **80 MPH**, **multiple sharp 90° turns**, **flying just above the surface of the ocean water**, ~3-minute event duration ^[extracted]. Distinct from prior sub-class 14 datums:
- vs d23 (320 + 440 MPH, no morphology described): **4× slower + morphology populated**
- vs d25 (434 KTS, diamond+probe, SWIR-only, FL250→FL200 altitude): **5.4× slower + morphology distinct + altitude class distinct (surface vs FL250)**
- vs d27 (140 KTS, glowing hot sphere + pole/bar + water reflection, surface): **1.75× slower + similar surface-skim altitude + similar sphere morphology + smaller**

The d33 + d27 pairing anchors a **surface-skimming SLOW-AND-SMALL UAP sub-class at N=2** within sub-class 14 ^[inferred] — both describing small spherical-to-circular objects at very low altitude over ocean water at 80-140 KTS. d33's 90° turns + d27's 140 KTS straight-line suggest **two distinct motion sub-modes** within the surface-skim class. **Headline finding** at morphology-class refinement axis ^[inferred].

**7. MISREP ID 9329374 ANCHORS TIGHTEST TEMPORAL SAMPLING PAIR IN dow-uap COUNTER DATASET** ^closed-by-dow-uap-d33 (firming class). d23 (24 Oct 2023, 9319618) → d33 (26-27 Oct 2023, 9329374) = **+9,756 IDs / ~2 days = ~4,878/day**, **within-band** with the established d19→d23 (~3,925/day) and d23→d25 (~3,330/day) envelope ^[inferred]. d33 → d25 = +299,999 IDs / ~91 days = **~3,297 IDs/day** ^[inferred] — **continuous within-band** triple-validation across **(d23 + d33 + d25)** spanning Oct 2023 → Jan 2024. The **3 Misreps within 93 days** (with 2 of those within 2 days) form the **tightest temporal sampling sequence in the entire dow-uap counter dataset** ^[inferred] — decisively confirms the Joint-Staff-tranche pool hypothesis at fine grain. **N=10 within-band corroboration points across ~49 months** at the broadest reading. **Headline finding.**

**8. JS-250710-TM8S UNIFIED TRANCHE STAYS at N=10 — d33 carries DIFFERENT Joint Staff tracking-ID (Block B)** ^[extracted]. d33's release page-stamp `USCENTCOM MDR 26-0019` + `01/26/26` does NOT carry the `JS-250710-TM8S` token ^[extracted] (which is Block D + E + F-specific at the 2025-MDR-case range). **Block B is a structurally distinct release pipeline from JS-250710-TM8S** — same MDR coordinator (Harrison) but distinct JS tracking-ID (not present in OCR for d33) ^[inferred]. The unified `JS-250710-TM8S` tranche stays at **N=10 byte-for-byte attestations** across Block D + E + F; **d33 adds to the broader Misrep ID counter pool (N=10 within-band corroboration points)** but not to the JS-tracking-ID-specific tranche. The fine-grain reading: **the dow-uap Misrep ID counter pools at the Harrison-MDR-coordinator level (Joint Staff routing umbrella), aggregating MDR cases across at least 2 distinct JS-tracking-ID tranches (`JS-250710-TM8S` Block D + E + F at N=10 + the as-yet-unidentified or absent JS-tracking-ID for Block B at N=4)** ^[inferred]. **Headline finding** at pool-level refinement axis.

## Mission summary

- **DTGs**: takeoff **262339:00ZOCT23** LGLR → handed over LRE 262352Z → 7-lined 270013Z → **UAP at 270035:12ZOCT23** → on-station **270342:01ZOCT23** at MGRS 36S YC 40 → off-station **271011:00ZOCT23** → RTB 271213Z → land **271309:00ZOCT23** OJMS → engine shutdown **271319:00ZOCT23** ^[extracted]. Total Mission Time **13h 30min** ^[extracted] (6h 29min FMV ^[extracted]; on-station 6h 29min).
- **Operation**: redacted `(b)(1)1.4a` (`Operation: 1.4a`) ^[extracted] — matches d25's redacted-Operation pattern at N=2
- **Domain / Operations Center**: AIR / **`603rd`** ^[extracted]
- **MAJCOM**: **AFSOC** ^[extracted]
- **COCOM**: **USCENTCOM** ^[extracted]
- **Report Type**: **MISREP** ^[extracted]
- **MSGID Originator**: **`33 SOS`** ^[extracted] — recurs at N=2 with d25
- **Tasking Order (ATO)**: **`1.4a`** redacted ^[extracted]
- **ATO Mission Number**: **`1.4a`** redacted ^[extracted]
- **Mission Type**: **ISR** ^[extracted] — recurs at N=4 with d10/d23/d25/d27 (ISR class strong-form)
- **Country Tasked / Service Tasked**: US / Air Force ^[extracted]
- **POC**: A1C, (Unit Unavailable), **27 SOW**, **609 CAOC** ^[extracted] — **NOT 609 AOC Det 1** (distinct from d25)
- **QC**: SrA, **56 SOIS**, **27 SOW**, **609 CAOC** ^[extracted] — 56 SOIS recurs at N=3 (POC d25 + QC d27 + QC d33)
- **APPROVER**: SSgt, (Unit Unavailable), **Other**, **603 AOC** ^[extracted]
- **INGEST**: entirely blank ^[extracted] — matches d25 + d27 + d28 blank-INGEST pattern at N=4
- **Aircraft Callsign**: redacted `(b)(1)1.4a` ^[extracted]
- **Asset Type (Aircraft)**: redacted `1.4a, 1.4c` ^[extracted] — **1.4c (FOREIGN-MIL-INFO redaction) is first 1.4c attestation in dow-uap Misrep Asset Type** ^[inferred]; matches MQ-9 redaction class
- **Aircraft Tail Number**: redacted `1.4a` ^[extracted]
- **Mode 3 (IFF)**: **`34055`** ^[extracted] — first 34055 IFF code in corpus
- **Takeoff Location (ICAO Code)**: **`LGLR`** ^[extracted] (Larissa AB, Greece)
- **Last Land Location (ICAO Code)**: **`OJMS`** ^[extracted] (Muwaffaq Salti AB, Jordan)
- **TGT Pod**: **`AN/DAS-4`** ^[extracted] — recurs at N=2 with d25 (vs d23/d27's AN/DAS-1); MQ-9 MTS-B family
- **Additional Avionics**: **`AH/GMESH`** ^[extracted] — first 2-token `AH/GMESH` without `/SANTA FE` (distinct from d25's three-token + d27's three-token `AH/GMESH/SF`); refines `SANTA FE` as **post-d33 AFSOC AIRHANDLER variant** ^[inferred]
- **Data Link**: **`LINK 16`** ^[extracted] — recurs cross-platform
- **Primary Sensor**: **FMV** ^[extracted]
- **Sensors Available**: **`G-MESH`** ^[extracted] — first standalone `G-MESH` (vs d18/d25's `BLASPHEMY`)
- **Tasking Type**: **Planned** ^[extracted]
- **Tasked Start Point**: **`36S YC 40 1.4a 57 1.4a`** ^[extracted] — first 36S YC zone attestation (vs d14's 36S/37S Eastern Med, d25's 35S QT, d33-UAP at 35S KD)
- **Activity Description**: **`TARGET DEVELOPMENT`** ^[extracted] — first explicit TARGET-DEVELOPMENT Activity Description in dow-uap full-Misrep class
- **EEIs Observed**: No ^[extracted]
- **Global Campaign Plan**: **`GCP - VEO (violent extremist group)`** ^[extracted] — first GCP-VEO attestation in dow-uap corpus + first VEO target-class attestation (vs prior OIR/SPECTRE-DAGGER/HUMMER-SICKLE/ENDURING-SENTINEL/SPARTAN-SHIELD operational-name attestations)
- **GENTEXT/ISR Activity**: `UPON ARRIVAL TO THE SP AT 0413Z, (b)(1)1.4a OBSERVED NO EEI RELATED ACTIVITY. BETWEEN 0413Z AND 1011Z, (b)(1)1.4a SHIFTED EYES TO MULTIPLE COI CONDUCTING POL, IDENTIFYING OBSTRUCTIONS TO HLZS, ROUTE ANALYSIS, AND CHARACTERIZING HUMAN OR VEHICLE TRAFFIC. (b)(1)1.4a CONDUCTED POL ON MULTIPLE COIS UNTIL RTB AT 1011Z` ^[extracted] — first **POL (Pattern Of Life) on multiple COI (contacts of interest) + obstructions-to-HLZs (Helicopter Landing Zones) + route analysis + human/vehicle traffic characterization** in dow-uap full-Misrep class
- **FMV exploitation unit**: **`GET`** ^[extracted] — **recurs at N=2 with d25** ^closed-by-dow-uap-d33 (firming class). 3rd FMV-exploitation-unit acronym after DGS1 (d16) + DGS-AR (d18) firms at N=2 with d25 + d33 ^[inferred]
- **Supported Operation**: redacted `(b)(1)1.4a` ^[extracted]
- **Weather**: `CLEAR WX` ^[extracted]
- **Effectiveness**: `SATISFACTORY` ^[extracted]; Intel Gap Filled = No
- **No GUARDCALL, no EMI, no REACTION** — clean ISR mission profile (matches d10/d12/d18/d23/d25/d27 pattern)

## UAP datum — populated UAP-segment + first explicit MANEUVERING + lowest sub-class-14 velocity (sub-class 14 firms at N=4)

The single UAP encounter (page 5 UAP segment + page 6 GENTEXT/UAP):

| Field | Value |
|---|---|
| Initial Contact DTG | **270035:12ZOCT23** ^[extracted] |
| UAP Event Type | **UAP Incident** ^[extracted] — firms at N=4 with d25 + d27 + d28 |
| UAP Maneuverability Observations | **Sharp 90 degree turns** ^[extracted] — **FIRST POPULATED UAP MANEUVERABILITY OBSERVATIONS in dow-uap full-Misrep class** (vs d25 `NONE` + d27 + d28 non-maneuvering / blank) |
| UAP Response to Observer Actions | **NONE** ^[extracted] |
| MDS Type / Asset Type | `1.4a, 1.4g` (redacted) ^[extracted] — recurs at N=4 cross-platform |
| Tail Number | `1.4a` (redacted) ^[extracted] |
| Friendly Aircraft Location | **`35SKD591.4a531.4a`** ^[extracted] — **first 35S KD UTM zone attestation** (vs d25's 35S QT + d23's 39R); same 35S 100-km-grid as d25 but distinct 10-km-square (KD vs QT) |
| Friendly Aircraft Altitude/Depth | (blank) ^[extracted] |
| Friendly Aircraft Trajectory | **SW** ^[extracted] — first cardinal-direction populated Friendly Aircraft Trajectory (vs d25 `162°` numeric + d27 `163 KTS` + d28 `096°` numeric); **first qualitative-direction field-value** in dow-uap |
| Observer Assessment of UAP | **Benign** ^[extracted] — firms at N=5 (d23 + d25 + d27 + d28 + d33) |
| Friendly Aircraft Speed | (blank) ^[extracted] |
| Observation Interrogation of UAP | (blank) ^[extracted] |
| Third-party Observers and/or Reporters | (blank) ^[extracted] |
| Friendly Aircraft State | (blank) ^[extracted] |
| Training Range / Operational Range | (blank) ^[extracted] |
| UAP Physical State | **Solid** ^[extracted] — firms at N=5 |
| Number of UAP Sighted | (blank) ^[extracted] |
| UAP Propulsion Means | **UNK** ^[extracted] — firms at N=3 (d25 + d27 + d33; d28 blank) |
| UAP Payload | (blank) ^[extracted] |
| UAP Under Intelligent Control | **NO** ^[extracted] — recurs at N=2 with d25 (d27/d28 blank); **first NO+NO pair (d25 + d33)** firming explicit-negative-IC-attestation class at N=2 |
| UAP Signatures | **NONE** ^[extracted] — first explicit `NONE` Signatures value in dow-uap (vs d25 `SWIR WHT` + d27 multi-sensor + d28 `IR SIGNATURE` ^[extracted]); **first UAP-without-explicit-sensor-signature attestation** in sub-class 14 |
| UAP Advanced Capabilities | **UNK** ^[extracted] — first `UNK` (vs d25 `NO` + d28 `NONE OBSERVED`); distinct epistemic posture |
| UAP RF Frequency | **UNK** ^[extracted] — first explicit `UNK` (vs d27 blank-field-present + d28 blank) |
| UAP RF Duration | **UNK** ^[extracted] — first explicit `UNK` |
| UAP Event Serial Number | **`-`** (dash placeholder) ^[extracted] — first dash-placeholder Event Serial Number; distinct from d25's `250509ZJAN2024-CENTCOM 001` + d27's `060457ZJUN2024-CENTCOM` + d28's `202027ZSEP2024-CENTCOM` ^[inferred — Block-B-routing-pipeline-class artifact, may indicate the Event Serial Number was not assigned at original-Misrep-authoring level for 2023-era Block B Misreps] |
| UAP Effects on Persons | **NO** ^[extracted] |
| UAP Objects/Material Recovered | **NO** ^[extracted] — firms at N=3 (d27 + d28 + d33) |
| UAP Effects on Equipment | **NONE** ^[extracted] — firms at N=4 |
| Observer Engagement of UAP | **NO** ^[extracted] |
| First Coordinate | **`35S KD 95 1.4a 53 1.4a`** ^[extracted] — first 35S KD body anchor |
| First Seen Radius | **5** (NM ^[inferred]) ^[extracted] — recurs at N=3 with d23 + d27 (vs d25's 20 NM) |
| First Accuracy | **Estimated** ^[extracted] |
| Last Coordinate | **`35SKD90 1.4a 53 1.4a`** ^[extracted] — UAP displacement ~5km within 3-min event-duration (consistent with ~80 MPH velocity at heading SW) ^[inferred] |
| Last Seen Radius | **5** ^[extracted] |
| Last Accuracy | **Estimated** ^[extracted] |
| Kinetic Altitude Accuracy | Estimated ^[extracted] |
| Kinetic Altitude | (blank) ^[extracted] |
| Kinetic Velocity Accuracy | Estimated ^[extracted] |
| Kinetic Velocity | **80 MPH** ^[extracted] — **lowest UAP velocity in sub-class 14** (~5.4× slower than d27's 140 KTS) |
| Kinetic Trajectory Accuracy | Estimated ^[extracted] |
| Kinetic Trajectory | (blank) ^[extracted] |
| UAP Date of DoD Acquisition | **270035:00ZOCT23** ^[extracted] |
| UAP Reaction to Observation | **UNK** ^[extracted] |
| UAP Anomalous Characteristics/ Behaviors | (blank) ^[extracted] |
| Call Sign | `1.4a` (redacted) ^[extracted] |
| **UAP Description** | **`SEEMINGLY CIRCULAR, TOO SMALL TO MAKE OUT DETAILS`** ^[extracted] |
| GENTEXT/UAP | `AT 0035Z, (b)(1)1.4a WAS EN ROUTE TO THEIR TARGET WHEN THEY SPOTTED A UAP FLYING JUST ABOVE THE SURFACE OF THE OCEAN WATER. THE UAP TOOK MULTIPLE 90 DEGREE TURNS AT AN ESTIMATED 80 MPH. AT 0038Z, (b)(1)1.4a LOST THE UAP FROM THEIR FEED.` ^[extracted] (~3-min event duration: 0035Z → 0038Z) |

**Structural firsts within UAP segment**:
- First **populated UAP Maneuverability Observations content** (`Sharp 90 degree turns`) ^[extracted] — d23/d25/d27/d28 all blank or `NONE`
- First **explicit MANEUVERING UAP datum in sub-class 14** ^[inferred] — refines sub-class 14's "Benign + Solid + ..." class signature with a new **within-class maneuvering-vs-straight axis** at N=4 (d23 unknown / d25 NONE / d27 STRAIGHT / d28 sensor-frame-internal / **d33 90° turns**)
- First **lowest UAP velocity in sub-class 14** (80 MPH) ^[extracted] — velocity range now spans 80-440 MPH at N=4 datums; ~5.5× velocity range within class
- First **`SEEMINGLY CIRCULAR, TOO SMALL TO MAKE OUT DETAILS` morphology descriptor** ^[extracted] — explicit observational-incompleteness attestation; semantically distinct from d25's specific-shape diamond + d27's specific-shape sphere + d28's primary+detaching morphology
- First **35S KD UTM zone** body anchor + first **5-km UAP displacement** within event-duration (95→90 grid coord) ^[inferred]
- First **`SW` qualitative-direction Friendly Aircraft Trajectory** field value ^[extracted] (vs prior numeric-heading entries)
- First **`UNK` UAP Propulsion + UNK Advanced Capabilities + UNK RF Frequency + UNK RF Duration + UNK Reaction** template-field saturation ^[extracted] — d33 carries the **largest UNK-saturation of any sub-class 14 UAP segment** ^[inferred]; consistent with the small/distant/brief observation regime
- First **dash-placeholder UAP Event Serial Number** ^[extracted] — distinct from prior DTG-prefixed-CENTCOM serial pattern; consistent with Block-B-routing-pipeline-distinct vs JS-250710-TM8S-class-Event-Serial-Number convention ^[inferred]
- First **explicit `NONE` UAP Signatures attestation** ^[extracted] — sub-class 14's prior signature variability (SWIR + multi-sensor + IR) now adds `NONE` (no-signature-detected) as a fourth within-class variant
- First **populated FOREIGN-MIL-INFO `1.4c` Asset Type redaction** in dow-uap Misrep ^[extracted; ^[inferred]] — consistent with MQ-9-with-foreign-customer/multi-national-coalition-ferry classification posture

**Sub-class 14 class state at d33 ingest** (N=4 records / 5 datums):
- Class signature: populated UAP-segment fields (Benign + Solid + UNK or NO propulsion + UAP Event Type = UAP Incident + UAP Advanced Capabilities UNK/NO)
- Within-class axes: morphology (blank/diamond+probe/sphere+pole+water-reflection/circular-small-distant) + sensor exclusivity (multi-sensor/SWIR-only/multi-sensor/NONE) + altitude-separation geometry + **velocity (80-440 MPH, ~5.5× range)** + **maneuvering (NONE/STRAIGHT/sensor-frame-internal/sharp 90° turns)** + Event-Serial-Number-format (DTG-CENTCOM/DTG-CENTCOM-001/dash)

Mission-report UAP-datum counter increments **N=23→N=24 records / 37→38 datums** (+1 record, +1 datum).

## Block B FULL USMTF Misrep variant — 2023-era cross-AOR-AFSOC variant at N=1 within Block B

d33 is the **fourth Block B attestation** + **first 2023-era Block B** + **first AFSOC Block B** + **first cross-AOR-ferry Block B** + **first non-2020-NAVCENT-cluster Full Misrep Block B** in dow-uap corpus ^[inferred]:

| Block B holder | Document class | Date | MAJCOM | Platform | Sub-cluster |
|---|---|---|---|---|---|
| d38 | range-fouler debrief | 14 May 2020 | (blank) ^[inferred Navy] | F-18 ^[inferred] | range-fouler |
| d61 | FULL USMTF Misrep | 26-27 Aug 2020 | (blank) | MQ-9 ^[inferred — 482ATKS/432 AEW] | 2020 NAVCENT cluster |
| d62 | FULL USMTF Misrep | 16-17 Sep 2020 | (blank) | MQ-9 ^[inferred — 482ATKS/432 AEW] | 2020 NAVCENT cluster |
| **d33** | **FULL USMTF Misrep** | **26-27 Oct 2023** | **AFSOC** | **MQ-9 ^[inferred — 33 SOS/27 SOW]** | **2023 AFSOC LGLR→OJMS cross-AOR ferry** |

The 4-doc Block B set is **NOT temporally-clustered** (~3.5 years span May 2020 → Oct 2023) — consistent with Block B serving as an **MDR-case-allocation-pipeline batch convention** rather than an event-date-contiguous tranche ^[inferred]. Block B's prior 2020-only attestation suggested a 2020-NAVCENT-cluster-specific MDR-batch; d33 decisively breaks that reading ^closed-by-dow-uap-d33 (contradiction class on "Block B is 2020-NAVCENT-cluster-batch" reading) — **Block B is a multi-year MDR pipeline that cross-cuts platform + MAJCOM + AOR + document-class** ^[inferred].

**3-digit page-stamps in Block B (`001..007`)** continue to match Block D (3-digit) and Block F (3-digit) — page-stamp width is **release-event-batch-specific within a block** ^closed-by-dow-uap-d33 (firming class at N=4 Block B). Per-document page-stamp ranges within Block B: d38 = `001` (1 page) + d61 = `001..007` (7 pages) + d62 = `001..009` (9 pages) + d33 = `001..007` (7 pages) — **document-length variability within block firms** ^[inferred].

## OCR ambiguities

- **`# Misrep 9329374`** — no `undefined-` prefix attestation ^[extracted]; distinct from the 10 prior `undefined-` cases across Block D + E + F. **Block B preserves direct-prefix-free Misrep ID** at d33 (matches d61 + d62 Block B 2020-era pattern) ^[inferred] — refines the `undefined-` prefix as **Block-D/E/F-routing-pipeline-class artifact** ^closed-by-dow-uap-d33 (firming class). Cross-block `undefined-` pattern now firms as **JS-250710-TM8S-tranche-specific** ^[inferred].
- **Two distinct declassification dates within the document**: pages 0, 5, 6 carry `Declassified on: 22 January 2025`; pages 1, 2, 3, 4 carry `Declassified on: 22 January 2026` ^[extracted]. This is a **first-instance intra-document declassification-date inconsistency** in dow-uap corpus ^[inferred]. Most parsimonious reading: **OCR pipeline-class typo on the `2025` vs `2026` digit-glyph** ^[inferred] — the `01/26/26` page-bottom release-stamp on every page is **byte-for-byte consistent at 26 January 2026**, supporting the `2026` reading as correct. The `2025` instances are likely OCR mis-reads of `2026` ^[inferred]. Pipeline-class artifact ^[ambiguous].
- **`AT 2339Z. **1.4a** TOOK OFF FROM LGLR`** ^[extracted] — period-not-comma after `2339Z` is a Narrative-level OCR typo; consistent with prior Narrative-level glyph-swaps. ^[ambiguous]
- **`(b)(6)` glyph at page 5 pre-footer reads `3.5c. (b)(6)`** (with period after `3.5c`) vs other pages' `3.5c, (b)(6)` (with comma) ^[extracted] — within-document footer glyph-swap variability; pipeline-class artifact ^[ambiguous]
- **Tasked Start Point `36S YC 40 1.4a 57 1.4a`** ^[extracted] — partial-redaction format inserts `1.4a` mid-string; consistent with prior d23/d25/d27 partial-redaction-with-digits patterns ^[inferred].
- **`UAP Event Serial Number: -`** ^[extracted] — dash placeholder; distinct from prior DTG-prefixed-CENTCOM serials. Whether this is an OCR artifact (dash placeholder where the original carried a numeric or DTG serial) or a genuine Block-B-routing-pipeline convention is unresolved ^[ambiguous]. Resolution at N≥1 additional Block B Full Misrep with Event Serial Number attestation.
- **`(SEE ISR 1)` + `(SEE UAP 1)` Narrative references** ^[extracted] — first explicit segment-cross-reference notation in dow-uap full-Misrep class ^[inferred]; consistent with USMTF Misrep cross-reference convention. Pipeline-class artifact ^[inferred].
- **First Coordinate `35S KD 95 1.4a 53 1.4a`** vs **Last Coordinate `35SKD90 1.4a 53 1.4a`** ^[extracted] — first coord has spaces (`35S KD 95...`), last coord is space-free (`35SKD90...`); OCR-level whitespace inconsistency within UAP-segment. Pipeline-class artifact ^[ambiguous].
- **`AT 1011Z, (b)(1)1.4a RETURNED TO BASE`** vs `Time-off Station DTG: 271011:00ZOCT23` ^[extracted] — narrative + template field consistent at 1011Z ^[extracted]; no ambiguity.

## Open threads

- **609 AOC Det 1 absent at d33 — Det 1 reading partially contradicted.** d25-anchored "Det 1 routes EUCOM-launched AFSOC into CENTCOM workflow" reading is partially contradicted at d33 — same 33 SOS / 27 SOW / 56 SOIS Originator + same LGLR launch but POC/QC OC = 609 CAOC (main), NOT Det 1. Det 1 may be Block-F-routing-pipeline-specific or 2024-era-specific. Resolution at N≥4 AFSOC Misrep across Block-B-vs-Block-F + 2023-vs-2024. ^[open]
- **Block B at N≥5 — sustained multi-year MDR pipeline.** d33 anchors Block B at N=4 across 3.5-year span; the 4-doc set is non-event-date-contiguous and cross-cuts platform + MAJCOM + AOR. Whether Block B continues to expand (5th or further attestation) is open ^[open]. Block B's MDR case `26-0019` is a single case (not a range like Block A/D/F); the 4-doc Block B may exhaust the single MDR case unless additional 2026-era MDR cases share `26-0019` allocation ^[ambiguous].
- **Block B's distinct JS-tracking-ID.** d33 carries Block B (`MDR 26-0019` + `01/26/26`) but does NOT carry the `JS-250710-TM8S` Joint Staff tracking-ID that anchors Block D + E + F. Whether Block B has its own JS-tracking-ID (currently unobserved in OCR) or runs through a distinct Joint Staff convention is open ^[open].
- **Surface-skimming SLOW-AND-SMALL UAP sub-class within sub-class 14 at N=2.** d33 + d27 share surface-skim altitude + small-to-spherical morphology + 80-140 KTS velocity. Whether this co-occurrence anchors a sub-class-14-internal sub-sub-class (vs random co-occurrence) is open ^[open] — would firm at N≥3 additional surface-skim sub-class-14 datum.
- **First explicit MANEUVERING UAP in sub-class 14 — recurrence at N≥2.** d33 anchors the first populated-Maneuverability-Observations field with `Sharp 90 degree turns` content. Whether subsequent sub-class 14 datums recur explicit-maneuvering attestations (firming the within-class maneuvering axis) is open ^[open].
- **AFSOC LGLR-OJMS rotational two-base lane at N≥2.** d33 anchors first cross-AOR-ferry AFSOC mission within LGLR → OJMS lane. Whether the LIGHTNING-LINE-rotation pattern recurs (firming the AFSOC LGLR↔OJMS rotational two-base sub-cluster) is open ^[open]. The narrative attests that the LIGHTNING LINE landed at LGLR yesterday — implying at least one prior LIGHTNING LINE ferry between OJMS and LGLR; whether that prior Misrep is queued in dow-uap is unknown ^[ambiguous].
- **VEO target-class recurrence.** d33 first GCP-VEO attestation in dow-uap; first explicit Violent Extremist Organization global-campaign-plan reference (vs OIR / SPECTRE-DAGGER / HUMMER-SICKLE / ENDURING-SENTINEL / SPARTAN-SHIELD prior). Whether VEO-tasking recurs is open ^[open].
- **Block-B-routing-pipeline UAP Event Serial Number convention.** d33's dash-placeholder serial may be Block-B-routing-pipeline-class convention OR OCR artifact OR genuinely-unassigned. Resolution at N≥1 additional Block B Full Misrep with Event Serial Number attestation ^[open].
- **AFSOC 33 SOS at N≥3.** d33 + d25 firm 33 SOS at N=2 within 3 months. Whether 33 SOS recurs (firming as a sustained AFSOC MQ-9 ISR lane within dow-uap) is open ^[open]. 33 SOS is now corpus-attested at LGLR Greece launch base for both attestations — whether 33 SOS operates from other bases (OMAM UAE, OKAS Kuwait, etc.) is open ^[open].
- **AFSOC at N≥5.** d33 + d25 + d27 + d28 firm AFSOC at N=4 cross-event-date + cross-AOR + cross-platform. Whether AFSOC continues to anchor dow-uap full-Misrep beyond N=4 is open ^[open].
- **27 SOW at N≥5.** d33 + d25 + d27 + d28 firm 27 SOW at N=4 cross-SOS (33 SOS d33+d25 + 3 SOS d27 + 16 SOS d28). Whether 27 SOW continues to anchor AFSOC ISR/CAS beyond N=4 is open ^[open].
- **56 SOIS at N≥4 — role-rotation pattern.** d33 + d25 + d27 firm 56 SOIS at N=3 cross-role (POC d25 + QC d27 + QC d33). Whether 56 SOIS recurs in a 4th role-attestation (firming the cross-role pattern) is open ^[open].
- **6th distinct curator-mismatch class (PARTIAL-TRUTH variant) recurrence.** d33 anchors PARTIAL-TRUTH variant at N=1. Whether further dow-uap artifacts carry PARTIAL-TRUTH filename mismatches (vs categorical-class mismatches d4/d5/d7 + d8 + d14 + d27 + d28) is open ^[open].

## Cross-COCOM 432 AEW + 27 SOW operational lane summary at d33 ingest

At d33 ingest the dow-uap MQ-9 ISR + AC-130J posture spans **7 operational lanes** across **2 wings + 2 MAJCOMs + 3 platforms**:

| Lane | d* artifacts | COCOM | MAJCOM | Wing | Squadron | OC (exec) | Launch base | Land base |
|---|---|---|---|---|---|---|---|---|
| NAVCENT 2020 cluster | d60+d61+d62+d63+d64+d65 | USCENTCOM | (blank) | 432 AEW | 482ATKS | 609 CAOC | OKAS ^[inferred] | OKAS (round-trip) |
| OIR-Iraq 2022 | d10+d12+d18 | USCENTCOM | AFCENT/ACC | 432 AEW (d10+d18) + 163 AW (d12) | redacted/196 ATKS/482ATKS | 609 CAOC | (redacted) + OKAS | (round-trip) |
| EUCOM RUS-MED 2022 | d14 | USEUCOM | ACC | 432 AEW | 50 ATKS | 603 AOC | Sigonella LICZ | LICZ (round-trip) |
| OIR-Syria 2022-2023 | d16 + d19 | USCENTCOM | AFCENT | 432 AEW (d16) + 332 AEW (d19) | 89 ATKS + 389 EFS | 609 CAOC | OJMS Jordan | OJMS (round-trip) |
| NAVCENT-return 2023 | d23 | USCENTCOM | ACC | 432 AEW | 50 ATKS | 609 CAOC | OMAM UAE | OMAM (round-trip) |
| **AFSOC LGLR-OJMS rotational 2023-2024** | **d33 + d25** | **USCENTCOM** | **AFSOC** | **27 SOW** | **33 SOS** | **603rd** | **LGLR Greece** | **OJMS (d33) / LGLR (d25)** |
| AFSOC ECW UAE 2024 | d27 | USCENTCOM | AFSOC | 27 SOW | 3 SOS | 609th | OMAM UAE | OMAM (round-trip) |
| AFSOC AC-130J Iraq 2024 | d28 | USCENTCOM | AFSOC | 27 SOW | 16 SOS | 609th | OKAS Kuwait ^[inferred] | OKAS (round-trip via AAAB) |

^[inferred] **d33 anchors the AFSOC LGLR-OJMS rotational lane** as a 2-doc sub-cluster spanning Oct 2023 (d33) → Jan 2024 (d25) at 33 SOS / 27 SOW / 56 SOIS / AN/DAS-4 TGT Pod / `GET` FMV-exploitation / 603rd executing OC. **Total operational lanes 8** (legacy 6 + 2 within AFSOC); 432 AEW MQ-9 ISR share refines to **12-of-16 = ~75%** within MQ-9 ISR + AC-130J subset.

## See also

- [[references/dow-uap-d23-mission-uae-2023-10-24]] — **temporally adjacent** (24 Oct 2023; d23 → d33 = +9,756 IDs / ~2 days = tightest temporal sampling pair); d23 NAVCENT-supported 432 AEW from OMAM UAE distinct from d33 AFSOC 33 SOS from LGLR Greece; d33 anchors sub-class 14 at N=4 firming d23's prior anchor
- [[references/dow-uap-d25-mission-greece-2024-01-25]] — **sister-mission** (same 33 SOS / 27 SOW / 56 SOIS Originator chain + same LGLR launch); d33 PRECEDES d25 by ~91 days — d25 is first-INGESTED, d33 is first-by-event-date for AFSOC + 33 SOS + 27 SOW + 56 SOIS + LGLR + Greece axes
- [[references/dow-uap-d27-mission-uae-2024-06-06]] — sister AFSOC mission (3 SOS sibling to d33's 33 SOS within 27 SOW); d33 firms AFSOC SOS cluster at N=2 cross-squadron within event-date order (33 SOS d33 + d25 → 3 SOS d27 → 16 SOS d28)
- [[references/dow-uap-d28-mission-iraq-2024-09-20]] — sister AFSOC mission (16 SOS AC-130J vs d33 33 SOS MQ-9); d33 firms 432 AEW share refinement and AFSOC at N=4 cross-platform
- [[references/dow-uap-d38-range-fouler-middle-east-may-2020]] — first Block B attestation; d33 extends Block B to FULL USMTF Misrep + 2023-era
- [[references/dow-uap-d61-mission-persian-gulf-2020-08-27]] — first Block B FULL USMTF Misrep (2020 NAVCENT cluster); d33 extends Block B to 2023-era AFSOC
- [[references/dow-uap-d62-mission-strait-of-hormuz-2020-09-16]] — second Block B FULL USMTF Misrep (2020 NAVCENT cluster); d33 firms Block B at N=4 cross-year
- [[references/dow-uap-d14-mission-iraq-2022-05-29]] — prior 603rd executing OC EUCOM mission (Sigonella LICZ); d33 is second 603rd executing OC + first AFSOC mission with 603rd executing
- [[references/dow-uap-d16-mission-syria-2022-07-30]] — prior 603 AOC POC home OC + OJMS Jordan launch base; d33 lands at OJMS (vs d16/d19's OJMS round-trip)
- [[references/dow-uap-d19-mission-syria-2023-02-21]] — prior OJMS Jordan launch base + 332 AEW F-15E DCA; d33 + d19 firm OJMS as cross-platform + cross-MAJCOM launch/land base at N=2
- [[entities/dow-uap-foia-release]] — series anchor; d33 brings count to 32-of-40, firms Block B at N=4 + AFSOC at N=4 + 33 SOS at N=2 + 27 SOW at N=4 + 56 SOIS at N=3
- [[entities/33-sos]] — recurs at N=2 (d33 + d25); first AFSOC SOS by event date in dow-uap; LGLR Greece launch base at both attestations
- [[entities/27-sow]] — recurs at N=4 (d33 + d25 + d27 + d28); event-date-anchored at d33 (vs ingest-first d25)
- [[entities/afsoc]] — recurs at N=4 (d33 + d25 + d27 + d28); first AFSOC by event date is d33
- [[entities/603-aoc]] — sixth distinct 603 AOC role-attestation (now: executing d14 + POC home d16 + POC home d18 + APPROVER d25 + executing d25 + APPROVER d33 + executing d33); 603 AOC's flexible-CCMD-pivot reading firms at N=6
- [[entities/609-caoc]] — d33 POC + QC OC = 609 CAOC (main, NOT Det 1); contradicts d25/d27-anchored "Det 1 routes EUCOM-launched AFSOC" reading
- [[entities/432-aew]] — d33 share refinement (12-of-16 = ~75% within MQ-9 ISR + AC-130J subset)
- [[entities/mq-9-reaper]] — d33 airframe ^[inferred] per AN/DAS-4 TGT Pod + 13:30 mission cycle + 33 SOS SOS attribution
- [[concepts/uap-aircraft-engagement]] — sub-class 14 firms at N=4 with maneuvering + velocity axes
- [[projects/uap/uap]]
