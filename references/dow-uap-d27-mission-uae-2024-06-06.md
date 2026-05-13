---
title: "DoW-UAP-D27 — Mission Report (UAE Al Dhafra, 6-7 Jun 2024, Misrep 10055709)"
category: references
tags: [uap, primary-source, declassified, usaf, sighting]
aliases: [DoW-UAP-D27, dow-uap-d27]
sources: [sources/dow-uap-d27-mission-report-united-arab-emirates-october-2023.json]
summary: 8-page Mistral-OCR'd Full USMTF Misrep 10055709 — 6-7 Jun 2024 Op ENDURING SENTINEL ISR mission from Al Dhafra UAE (OMAM); 3 SOS / 27 SOW / 56 SOIS MQ-9 ^[inferred] under AFSOC MAJCOM + USCENTCOM COCOM; WX RTB truncated cycle 10h 13min; 1X UAP at 0457Z during RTB at UTM 40R UAE Persian Gulf — GLOWING HOT SPHERE with vertical pole/bar appendage, 140 KTS just-over-the-water, FL240 a/c above; Block F recurs at N=2 byte-for-byte; AFSOC at N=2.
provenance:
  extracted: 0.6
  inferred: 0.35
  ambiguous: 0.05
base_confidence: 0.74
lifecycle: draft
lifecycle_changed: 2026-05-13
created: 2026-05-13T18:00:00Z
updated: 2026-05-13T18:00:00Z
event_date: 2024-06-06
project: uap
---

# DoW-UAP-D27 — Mission Report (UAE Al Dhafra, 6-7 Jun 2024, Misrep 10055709)

An **8-page Mistral-OCR'd artifact** (`sources/dow-uap-d27-mission-report-united-arab-emirates-october-2023.json`, 12,508 bytes; SHA-256 `54c3fa4bd5ffe2415523d703035d2dceacd4ac79b6a196ccce6846615ed34563`) — the **30th artifact** in the [[entities/dow-uap-foia-release|DoW-UAP FOIA release series]] (30-of-~40) and the **FIFTEENTH FULL USMTF MISREP** in the corpus. Misrep 10055709 — **6-7 Jun 2024 Op ENDURING SENTINEL AFSOC MQ-9 ISR mission flown by 3 SOS / 27 SOW from Al Dhafra Air Base (OMAM), UAE**, anchors **Block F recurrence at N=2 byte-for-byte**, **AFSOC at N=2**, and **sub-class 14 firms at N=3 with morphology axis**.

## Filename-vs-event mismatch (curator error)

**The source basename `dow-uap-d27-mission-report-united-arab-emirates-october-2023.json` carries the WRONG year and month** ^[extracted]. The internal Takeoff Time DTG is **`062100:00ZJUN24`** (6 Jun 2024 at 2100Z) ^[extracted] and Landing Time DTG is **`070713:00ZJUN24`** (7 Jun 2024 at 0713Z) ^[extracted] — the mission is **6-7 Jun 2024**, NOT October 2023. UTM 40R coordinates decode correctly to the UAE Persian Gulf coast (matches the `united-arab-emirates` body of the filename, contradicts `october-2023`). Page slug + page title + event_date all anchor to **2024-06-06** per dow-uap convention (d23/d25 anchor to takeoff day). This is the **fourth dow-uap filename-curator-mismatch** in corpus after `arabian-gulf` (d4/d5/d7 Persian Gulf body match but token mismatch), `djibouti-2025` (d8 Eastern Mediterranean body, NOT Djibouti), and `iraq-may-2022` (d14 Eastern Mediterranean body, NOT Iraq) ^[inferred]. The filename-vs-internal mismatch firms as a **curator-pipeline-class artifact** at N=4 distinct mismatch types ^[inferred].

## Headline findings

**1. BLOCK F RECURRENCE AT N=2 BYTE-FOR-BYTE** ^closed-by-dow-uap-d27. d27 carries `USCENTCOM MDR 25-0100 thru 25-0103 / JS-250710-TM8S` + `10/28/25 001..008` (3-digit page-stamps, 8 pages) — **identical Block-F header signature to d25** (which had 001..007 3-digit, 7 pages, same MDR range + same JS-tracking + same 10/28/25 release date). **Block E (MDR 25-0104, d23) does NOT recur at d27** ^[extracted] (contradiction class for the d23/d25-flagged "Block E recurrence at N≥2" open thread — still OPEN). At N=20 release-block-testable artifacts:

| Block | MDR range | Release date | Page-stamp | N |
|---|---|---|---|---|
| A | 26-0038 to 26-0046 (9-case) | 03/27/26 | 6-digit | 5 |
| B | 26-0019 (single) | 01/26/26 | 3-digit | 3 |
| C | 26-0028 (single) | 03/16/26 | 6-digit | 3 |
| D | 25-0093 to 25-0099 (7-case) | 10/17/25 or 10/20/25 | 3-digit + 6-digit mixed | 6 |
| E | 25-0104 (single) | 09/12/25 | 6-digit | 1 |
| **F** | **25-0100 thru 25-0103 (4-case)** | **10/28/25** | **3-digit** | **2** |

Block F firms at **2-of-20 (~10%)** with d25 + d27 byte-for-byte. Block D stays at **6-of-20 (~30%)** and continues to lead Block A (~25%). The `JS-250710-TM8S` Joint Staff tracking-ID continues across Block D + E + F (d10-d27) at N=9 byte-for-byte attestations ^closed-by-dow-uap-d27 (firming class). **Headline finding.**

**2. AFSOC RECURRENCE AT N=2 + 27 SOW RECURRENCE AT N=2 + 56 SOIS RECURRENCE AT N=2 + 609 AOC DET 1 RECURRENCE AT N=2** ^closed-by-dow-uap-d27. d27 carries:

- **MAJCOM = AFSOC** ^[extracted] (d25 + d27 = N=2 cross-mission)
- **POC Wing = 27 SOW** ^[extracted] (d25 POC + d27 POC = N=2 within dow-uap full-Misrep class)
- **Originator = 3 SOS** ^[extracted] — **first 3 SOS attestation**; sister AFSOC SOS to d25's 33 SOS (both Cannon AFB-rooted ^[inferred]). **AFSOC SOS cluster firms at N=2 cross-squadron** within 27 SOW ^[inferred].
- **POC Unit = `Unavailable` (literal field token, page 1) / QC Unit = 56 SOIS (page 2)** ^[extracted] — d25 had 56 SOIS as POC unit (populated); d27 has explicit `Unavailable` POC unit token + 56 SOIS at QC. POC unit shift d25(populated)→d27(`Unavailable`) may be tasking-specific (d27's WX-RTB-truncated mission may have curtailed POC-unit-fill workflow) OR OCR-redaction-pipeline artifact ^[ambiguous]. **56 SOIS recurs at N=2 cross-role** (POC d25 + QC d27) ^[inferred] — same pattern as 89 ATKS (d16 POC → d19 APPROVER) for cross-squadron Misrep-role flexibility.
- **QC OC = 609 AOC Det 1** ^[extracted] — d25 had Det 1 as POC home; d27 has Det 1 as QC home. **609 AOC Det 1 recurs at N=2 in INVERSE positions** (POC d25 + QC d27); CENTCOM-forward AFSOC-liaison detachment reading firms ^closed-by-dow-uap-d27 (refinement class). Not d25-specific.

**The 432-AEW MQ-9 ISR monopoly stays broken** at corpus level; refined share now **12-of-14 = ~86%** within MQ-9 ISR subset (d10/d12/d14/d16/d18/d23 6 + cluster 6 = 12 within MQ-9 ISR; vs 27 SOW 2 within MQ-9 ISR). AFSOC's parallel ISR pool stays robust at corpus level. **Headline finding.**

**3. SUB-CLASS 14 FIRMS AT N=3 WITH MORPHOLOGY AXIS** ^closed-by-dow-uap-d27. The d23 → d25 ambiguity between sub-class 14 (populated UAP-segment fields) firming with morphology-axis variability vs new sub-class 15 (populated + morphology-described) anchoring at d25 is **decisively resolved at d27 to Reading (a) — sub-class 14 firms at N=3 with morphology axis**:

| Datum | Morphology | Populated-fields | Sensor |
|---|---|---|---|
| d23 datum 1 (240241Z) | BLANK | Yes (320 MPH, Benign, Solid, 5 NM, THERMAL COLD) | THERMAL + EO ^[inferred] |
| d23 datum 2 (240322Z) | BLANK | Yes (440 MPH, Benign, Solid, 5 NM) | THERMAL + EO ^[inferred] |
| d25 datum 1 (250509Z) | DIAMOND + non-maneuverable tail/probe | Yes (434 KTS, Benign, Solid, 20 NM, SWIR WHT) | **SWIR-only exclusive** |
| **d27 datum 1 (070457Z)** | **GLOWING HOT SPHERE + vertical cylindrical pole/bar appendage + water reflection** | **Yes (140 KTS, Benign, Solid, 5 NM, populated-Kinetic-Velocity-FIELD-with-KNOTS-unit)** | **Implicit IR/EO** ^[inferred] |

**Reading (a) — sub-class 14 with morphology axis — preferred** at N=3 ^[inferred]: d25 (diamond+probe) + d27 (sphere+pole/bar with water-reflection) share "morphology-described" but diverge on sensor exclusivity (SWIR-only d25 vs multi-sensor d27) AND morphology shape — so they do not jointly anchor a class distinct from d23. The "populated UAP-segment fields" axis is the **class signature** (sub-class 14); morphology + sensor-exclusivity are **within-class variability axes**. Reading (b) "new sub-class 15 anchored at d25 + d27" would require d25 + d27 to share a distinctive feature uncorrelated with d23 — but the only shared feature is "morphology described" which is the within-class axis, not a class. **Headline finding.**

**4. FIRST OP ENDURING SENTINEL ATTESTATION in dow-uap corpus** ^[extracted]. d27 ADMIN.OPERATION.Operation = `ENDURING SENTINEL`. **First ENDURING SENTINEL in dow-uap full-Misrep class**. Op SPARTAN SHIELD (d23 NAVCENT-supported UAE) and Op INHERENT RESOLVE (d10/d12/d16/d18/d19 OIR) remain at corpus level; d25 had a redacted Operation. **Operation token now extends to 4 distinct attestations** in dow-uap full-Misrep class (INHERENT RESOLVE + HUMMER SICKLE + SPECTRE DAGGER + SPARTAN SHIELD + **ENDURING SENTINEL** = 5 named operations within corpus). The exact tasking remit of ENDURING SENTINEL is not literally described in OCR ^[inferred — open-source attribution would place ENDURING SENTINEL as a US counter-VEO operation, but the dow-uap OCR does not state this]. **Headline finding** at operation-firsts axis.

**5. FIRST WX-RTB TRUNCATED MISSION IN MQ-9 ISR CLASS — 10h 13min CYCLE** ^[extracted]. d27 narrative attests `AT 1822Z, PRUVE WAS 7-LINED, PRUVE DID NOT ARRIVE ON-STATION DUE TO WX RTB` ^[extracted]. Total Mission Time = `10 hours 13 minutes` ^[extracted] vs MQ-9 ISR corpus envelope ~20-22h (d23 20h 43min + d25 20h 40min + cluster d60-d65 ~20-21h). **Second-shortest mission cycle in dow-uap full-Misrep class** after d19's 4h 55min F-15E DCA (which was a different platform-class envelope). **First MQ-9 ISR mission-cycle truncation by Weather-RTB in dow-uap corpus** ^[inferred]. The truncation is structurally distinct from d19's F-15E DCA short cycle (DCA mission envelope) and d62's mid-mission EMI (no RTB) — d27 establishes a **WX-RTB sub-class for MQ-9 ISR mission profiles**. ^[inferred] **Did Not Arrive On Station = On** ^[extracted] — first explicit non-arrival attestation in dow-uap full-Misrep class. **Headline finding.**

**6. FIRST 3 SOS ORIGINATOR + first AFSOC SOS-CLUSTER (3 SOS + 33 SOS) cross-squadron firms at N=2** ^[inferred]. 3 SOS (3rd Special Operations Squadron) and 33 SOS (33rd Special Operations Squadron) are both Cannon AFB-based AFSOC MQ-9 SOSs ^[inferred — open-source standard attribution; not literally in dow-uap OCR]. d25 + d27 firms **AFSOC-MQ-9-organic ISR cross-squadron at N=2** within 27 SOW parent wing. AFSOC ISR pool is structurally distinct from 432 AEW (ACC/AFCENT-routed) and operates at least **two MQ-9 SOSs in dow-uap full-Misrep class** within 5-month window (Jan 2024 LGLR + Jun 2024 OMAM) ^[inferred].

**7. UAE-OMAM SUB-CLUSTER ANCHORED AT N=2 — but only via OMAM-launch + UTM 40R UAE-side + 609 CAOC OC shared anchors; Operation/POC-unit/POC-Wing/MAJCOM/Block/duration ALL DIVERGE between d23 + d27** ^[inferred]. d23 + d27 share:

- **Launch base = OMAM Al Dhafra UAE** ^[extracted]
- **Body UTM = 40R/39R-Persian-Gulf** ^[inferred]
- **Operations Center = 609 CAOC / 609th** ^[extracted]
- **Mission Type = ISR** ^[extracted]
- **TGT Pod = AN/DAS-1 (d23 ANDAS1; d27 AN/DAS-1 — same pod, OCR-typeset variants)** ^[extracted]

But diverge on:

| Axis | d23 (24 Oct 2023) | d27 (6-7 Jun 2024) |
|---|---|---|
| Operation | OP SPARTAN SHIELD | OP ENDURING SENTINEL |
| POC Unit | 50 ATKS | (unit unavailable) / 56 SOIS QC |
| POC Wing | 432 AEW | **27 SOW** |
| MAJCOM | (ACC ^[inferred]) | **AFSOC** |
| Originator | (not extracted) | **3 SOS** |
| APPROVER | ISRD/ACF/UnitSupport | **379 AEW** |
| Block | E (`MDR 25-0104`, 09/12/25) | **F (`MDR 25-0100 thru 25-0103`, 10/28/25)** |
| Supported | NAVCENT | (not stated; tasking is DHOW-scan EEIs) |
| Duration | 20h 43min | **10h 13min (WX RTB truncated)** |
| UAP datum count | 2 | 1 |
| UAP morphology | (blank) | sphere + pole/bar |
| UAP altitude class | same-altitude (FL243 a/c + FL243 UAP) | a/c above (FL240) + UAP just-over-water |

**d27 is at best a UAE-OMAM sub-theater co-member, NOT a same-operation pair-mate with d23.** ^[inferred] d27 establishes a **parallel AFSOC-OMAM lane** within UAE-OMAM theater alongside the d23-anchored 432-AEW-OMAM lane — first dual-MAJCOM single-launch-base UAE-OMAM pattern in dow-uap corpus ^[inferred]. **Headline finding.**

**8. AFSOC OMAM ATTESTATION — first AFSOC-CENTCOM-AOR-launched-CENTCOM-tasked mission in corpus** ^[inferred]. d25 was EUCOM-AOR-launched (LGLR Greece) + CENTCOM-tasked (cross-AOR); d27 is **same-AOR CENTCOM-launched + CENTCOM-tasked** ^[extracted] — first single-COCOM AFSOC mission in dow-uap corpus. The 4-OC chain at d27 is fully CENTCOM-bound:

- POC home OC = **609 CAOC** (CENTCOM) ^[extracted]
- QC OC = **609 AOC Det 1** (CENTCOM-forward AFSOC liaison) ^[extracted]
- APPROVER Wing = **379 AEW** (Al Udeid AB Qatar ^[inferred]) + APPROVER OC = **609 CAOC** ^[extracted]
- Executing OC = **609th** ^[extracted]

**Cross-OC topology at d27 = single-COCOM (CENTCOM) + same-MAJCOM-headquarters routing** ^[inferred] — fourth distinct cross-OC topology after d14 (single-direction CENTCOM→EUCOM), d16/d18 (single-direction inverse EUCOM→CENTCOM), d25 (bidirectional cross-COCOM 3-OC). **No EUCOM bridge.** ^[inferred] **Headline finding.**

**9. MISREP ID COUNTER VALIDATES AT N=7 (d25→d27 ~3,205 IDs/day WITHIN-BAND)** ^closed-by-dow-uap-d27. d25 (9629373) → d27 (10055709) = +426,336 IDs / ~133 days = ~3,205 IDs/day, **within-band** with d23→d25 (~3,330/day), d18→d23 (~3,925/day), and prior cluster envelope. Reframes d19's out-of-band low (~1,659/day) decisively as a winter-2023 anomaly against **N=8 within-band cross-COCOM cross-MAJCOM cross-platform corroboration points** spanning d60 (8 Aug 2020) → d10 (6 May 2022) → d12 (20 May 2022) → d14 (29 May 2022) → d16 (30 Jul 2022) → d18 (1 Dec 2022) → d23 (24 Oct 2023) → d25 (25 Jan 2024) → d27 (6-7 Jun 2024) = ~46 months at within-band rate. **The counter is decisively pooled at Joint-Staff-tranche / Harrison-MDR-coordinator level**, not lane-specific. ^[inferred] Misrep 10055709 is **the first dow-uap full-Misrep with an 8-digit Misrep ID (≥10M)** — counter crosses the 10M boundary between d25 (9.6M) and d27 (10.05M). **Headline finding.**

**10. 379 AEW APPROVER LANE FIRMS AT N=3 — 50% LANE PREVALENCE** ^[inferred]. d27 APPROVER Wing = `379 AEW` ^[extracted]. 379 AEW APPROVER prior attestations: d10 + d64 = 2-of-5 within 432 AEW POC subset. d27 adds 3rd attestation = **3-of-6 = 50%** within corpus-testable APPROVER-Wing-attested missions. Refined reading: 379 AEW APPROVER lane is **OMAM/Al-Udeid-routed CENTCOM-AOR specific** (d10 OIR-Iraq forward-deployed + d64 2020 NAVCENT cluster + d27 OMAM-AFSOC) **regardless of POC Wing or MAJCOM** ^[inferred]. The 379 AEW APPROVER stays an Al-Udeid AB hub-routing convention for CENTCOM-AOR-completed missions, not a 432-AEW-specific or NAVCENT-specific lane. ^[inferred] **Headline finding.**

## Mission summary

- **DTGs**: takeoff **062100:00ZJUN24** OMAM → 7-line 1822Z (out-of-sequence in narrative; appears to be 06 Jun pre-take ^[ambiguous] OR OCR sequence-disorder) → DID NOT ARRIVE ON-STATION DUE TO WX RTB → NIB 1 062256-062330Z (DHOW scan) → NIB 2 070444-070548Z (DHOW scan) → **UAP 1 070457Z DURING RTB** → RTB 070405Z → SLR + Landing **070713:00ZJUN24** OMAM. Total Mission Time **10h 13min** + Last Engine Shutdown 070723Z (10h 23min engine-time). ^[extracted]
- **Operation**: **OP ENDURING SENTINEL** ^[extracted] — first attestation in dow-uap corpus
- **Domain / Operations Center**: AIR / **609th** ^[extracted]
- **MAJCOM**: **AFSOC** ^[extracted]
- **COCOM**: **USCENTCOM** ^[extracted]
- **Tasking Order (ATO)**: **`DK`** ^[extracted] — 8th distinct ATO format after AB/AP/DI/ID/LG/24-024/(blank)
- **Mission Type**: **ISR** ^[extracted]
- **Country Tasked / Service Tasked**: US / Air Force ^[extracted]
- **MSGID Originator**: **`3 SOS`** ^[extracted] — first 3 SOS in corpus
- **POC**: SrA, (unit unavailable), **27 SOW**, **609 CAOC** ^[extracted]
- **QC**: A1C, **56 SOIS**, 27 SOW, **609 AOC Det 1** ^[extracted]
- **APPROVER**: SrA, (unit unavailable), **379 AEW**, **609 CAOC** ^[extracted]
- **INGEST**: entirely blank (matches d25's blank-INGEST pattern at N=2) ^[extracted]
- **Aircraft Callsign**: `PRUVE` (4th distinct callsign-token-in-narrative; redacted in ACEQUIP fields) ^[extracted]
- **MDS/Tail Number**: redacted `1.4a, 1.4g` ^[extracted]
- **Takeoff Location**: `OMAM` (Al Dhafra AB, UAE — first AFSOC mission from OMAM in corpus) ^[extracted]
- **Mode 3 IFF**: `34563` ^[extracted] — first explicit IFF code in dow-uap full-Misrep class
- **TGT Pod**: **`AN/DAS-1`** ^[extracted] — recurs at N=2 in dow-uap (d23 ANDAS1 + d27 AN/DAS-1; OCR-typeset variants of same pod). Differs from d25's AN/DAS-4 (Reaper MTS-B family canonical).
- **Additional Avionics**: **`AH/GMESH/SF`** ^[extracted] — 4th-or-5th AIRHANDLER configuration variant (`_GMESH` + `v2` + `\SAR` + `BLASPHEMY` + `SANTA FE` + `SF`); whether `SF` abbreviates `SANTA FE` from d25 (NM tie to Cannon AFB) or denotes `Special Forces` or a separate sigint token is **^[ambiguous]** at N=1 d27-attestation
- **Data Link**: `LINK 16` ^[extracted]
- **JTAC Callsign**: `ITC` ^[extracted]
- **NIB 1**: 062256-062330Z DHOW scan at MGRS `40RGM85...` — EEIs verbatim block (A. SCANS AT 75NM W/N/E OF SP FOR DHOWS, B. SITREP FLAG STATUS, C. IDENTIFIABLE EQUIPMENT) ^[extracted]
- **NIB 2**: 070444-070548Z DHOW scan at MGRS `40RFM60...` — same EEI block ^[extracted]
- **No GUARDCALL, no EMI, no REACTION** — clean ISR mission profile (zero GUARDCALL extends N=8 cross-COCOM + cross-MAJCOM + cross-platform; zero EMI extends N=9; zero REACTION extends N=14)
- **MGRS coords**: UTM **40R FM** + **40R GM** (UAE Persian Gulf coast — same 100-km square family as d23's 39R variants, adjacent zone). UAP last coord `40Q FM9...` crosses into 40Q (S of 40R), within Persian Gulf interior ^[inferred].

## UAP datum — populated UAP-segment + morphology-described + multi-sensor (sub-class 14, N=3)

The single UAP encounter (page 5-6 UAP segment + page 6 GENTEXT/UAP):

| Field | Value |
|---|---|
| Initial Contact DTG | **070457:00ZJUN24** |
| UAP Event Type | **UAP Incident** (recurs at N=2 with d25; firms as explicit token) |
| UAP Maneuverability Observations | **FLYING STRAIGHT JUST OVER THE WATER AT SPEED OF 140 KNOTS** |
| UAP Response to Observer Actions | **NO CHANGE** |
| MDS Type / Asset Type | `1.4a, 1.4g` (redacted) |
| Tail Number | `1.4a, 1.4g` (redacted) |
| Friendly Aircraft Location | **`40RFM60 1.4a 1.4a`** (UAE Persian Gulf coast) |
| Friendly Aircraft Altitude | **23,999 FT** (effectively FL240) |
| Friendly Aircraft Trajectory | **294°** (WNW heading) |
| Observer Assessment of UAP | **Benign** (firms at N=3; d23 + d25 + d27) |
| Friendly Aircraft Speed | **163 KNOTS** |
| Number of UAP Sighted | (blank) |
| UAP Physical State | **Solid** (firms at N=3; d23 + d25 + d27) |
| UAP Propulsion Means | **UNKNOWN** |
| UAP Signatures | `-` (blank) — distinct from d25's `SWIR WHT` populated and from d23's THERMAL COLD narrative-only ^[inferred] |
| UAP Advanced Capabilities | **NO** |
| UAP RF Frequency | `-` (blank field — **first explicit UAP RF Frequency template field** in corpus, even if blank) ^[extracted] |
| UAP RF Duration | `-` (blank field — **first explicit UAP RF Duration template field** in corpus) ^[extracted] |
| UAP Event Serial Number | **`060457ZJUN2024-CENTCOM`** ^[extracted] — DTG-prefixed without trailing `001` counter (d25 had `CENTCOM 001`; d27 omits) |
| UAP Effects on Persons | **NO** |
| UAP Objects/Material Recovered | **NO** (first explicit attestation of this template field in dow-uap full-Misrep corpus) ^[extracted] |
| UAP Effects on Equipment | `-` (blank) |
| First Coordinate | **`40RFM60 1.4a 1.4a`** |
| First Seen Radius | (blank) |
| Last Accuracy | Estimated |
| Last Coordinate | **`40QFM9a 1.4a 1.4a`** (40Q = S of 40R, Persian Gulf interior) |
| Last Seen Radius | **5** NM (matches d23's 5 NM; distinct from d25's 20 NM) |
| Kinetic Altitude Accuracy | Estimated |
| Kinetic Altitude | `-` (blank) |
| Kinetic Depth Accuracy | Estimated |
| Kinetic Depth | `-` (blank) |
| Kinetic Velocity Accuracy | Estimated |
| **Kinetic Velocity** | **`140 KNOTS`** ^[extracted] — **first POPULATED Kinetic Velocity FIELD with explicit KNOTS unit** in dow-uap full-Misrep class (d23 had blank field + 320/440 MPH narrative; d25 had blank field + 434 KTS narrative; d27 populates field directly) |
| Kinetic Trajectory Accuracy | Estimated |
| Kinetic Trajectory | `-` (blank) |
| UAP Date of DoD Acquisition | **070457:00ZJUN24** |
| UAP Anomalous Characteristics | (blank — d25 had `MAINTAINED STEADY FLIGHT PATH...`; d27 leaves blank) |
| First Accuracy | Precise |
| Call Sign | `0)1.4a` (redacted) |
| UAP First/Last Seen Location | (in narrative) |
| **UAP Description** | **`GLOWING HOT SPHERICAL UNIDENTIFIED OBJECT WITH A VERTICAL UNWAVERING CYLINDRICAL POLE/BAR ATTACHED ON THE BOTTOM OF THE OBJECT POSS REFLECTION FROM THE OBJECT IN THE WATER, MOVING AT 140KNOTS`** ^[extracted] |
| GENTEXT/UAP | `(SECRET/NOFORM) DURING RTB AT 0457Z, (0)08, OBSERVED 1X UAP WHILE TRANSITING OVER 40RFM60, (1)1, (2)1, FLYING AT AN ALTITUDE OF 23,999FT MSL AND SPEED OF 163KTS. (SECRET/NOFORM)` ^[extracted] |

**Structural firsts within UAP segment**:
- First **GLOWING HOT SPHERICAL UAP morphology** ^[extracted] in dow-uap corpus (third distinct morphology after d54 triangular metallic + d25 diamond+probe + d8 round-white-hot; the glowing-hot-sphere distinct from d8 round-white-hot via vertical pole/bar appendage)
- First **VERTICAL UNWAVERING CYLINDRICAL POLE/BAR appendage** descriptor — semantically distinct from d25's non-maneuverable "tail/probe" (d25 ATTACHED below DIAMOND; d27 ATTACHED below SPHERE — possibly converging morphology class with "object + bottom-attached appendage" ^[inferred]; resolution at N≥3)
- First **POSS REFLECTION FROM THE OBJECT IN THE WATER** ^[extracted] — first explicit water-surface reflection annotation in dow-uap corpus; implies UAP altitude near water level (vs d25 FL250 + d23 FL243)
- First **JUST OVER THE WATER altitude descriptor** for UAP ^[extracted]
- First **a/c-above + UAP-at-surface altitude separation geometry** ^[inferred] — d23 had same-altitude (FL243 a/c + FL243 UAP); d25 had a/c-above + UAP-at-FL200 (50-deck delta); d27 has a/c-at-FL240 + UAP-at-surface (~240-deck delta)
- First **POPULATED Kinetic Velocity FIELD with KNOTS unit** (`140 KNOTS`) ^[extracted] — d23/d25 left field blank with narrative-only values; d27 populates directly
- First **explicit `UAP RF Frequency`** + **`UAP RF Duration`** template field anchors ^[extracted] — even blank, the field labels appear for first time in corpus; **expands the canonical UAP-segment template to RF-spectrum axis**
- First **DTG-prefixed UAP Event Serial Number WITHOUT trailing counter** (`060457ZJUN2024-CENTCOM` vs d25's `250509ZJAN2024-CENTCOM 001`) ^[extracted] — refines d25's `CENTCOM 001` reading: the `001` may be a non-mandatory mission-counter add-on (d27 omits it) OR `001` was CY2024-first-CENTCOM-event and d27 is CY2024-second-CENTCOM-event but the counter convention was discontinued mid-year ^[ambiguous]; **does NOT resolve the `001` reset basis but firms that the counter is NOT mandatory in the template**
- First **multi-NIB intra-mission segment count = 2** ^[extracted] — d27 carries NIB 1 + NIB 2 + UAP 1 segments within single mission (d23 had 1 NIB; d25 had POL/follow-on segments; d27 is **first to attest 2 distinct NIB segments**)
- First **explicit DHOW-scan EEI block verbatim** in dow-uap full-Misrep class ^[extracted] (A. scans at 75NM W/N/E of SP / B. SITREP flag status / C. identifiable equipment) — anchors maritime small-boat ISR tasking class within dow-uap
- 5 NM seen-radius firms at N=2 (d23 + d27); 20 NM at N=1 (d25); blank-radius at N=15 (cluster + OIR cohort)

## Sub-class 14 firms at N=3 (Reading (a) preferred)

| Datum | Date | Morphology described | Sensor exclusivity | Altitude geometry |
|---|---|---|---|---|
| d23 #1 | 24 Oct 2023 | BLANK | implicit THERMAL + EO ^[inferred] | same-altitude |
| d23 #2 | 24 Oct 2023 | BLANK | implicit THERMAL + EO ^[inferred] | same-altitude |
| d25 #1 | 25 Jan 2024 | DIAMOND + non-maneuverable tail/probe | **SWIR-only exclusive** | a/c above + UAP descending |
| d27 #1 | 7 Jun 2024 | **GLOWING HOT SPHERE + vertical pole/bar appendage + water reflection** | implicit multi-sensor IR/EO ^[inferred] | a/c-at-FL240 + UAP-at-surface |

**Reading (a) — sub-class 14 with morphology axis — preferred at N=3 corroboration points** ^closed-by-dow-uap-d27 (refinement class on d25-anchored sub-class-14-vs-15 open thread). Sub-class 14 anchors at **populated UAP-segment fields**; morphology + sensor-exclusivity + altitude-separation become **within-class variability axes**, not class-level signatures. The "object + bottom-attached appendage" sub-pattern firms at **N=2 across morphology variants** (d25 diamond+probe + d27 sphere+pole-bar) ^[inferred] and may anchor a **morphology-class candidate** (object-with-appendage) at corpus level ^[inferred]; resolution at N≥3 morphology-described datums. Mission-report UAP-datum counter increments **N=21→N=22 records / 35→36 datums** (+1 record, +1 datum).

## Block F structural attestation — second 25-0100..25-0103 case (d25 #1 + d27 #2)

d27 is the second Block F artifact at N=2 byte-for-byte. The 4-case range (`25-0100 thru 25-0103`) suggests **up to 4 Block F artifacts** are potentially eligible. Currently d25 + d27 = 2-of-4 eligible. The `JS-250710-TM8S` Joint Staff tracking-ID continues across Block D + E + F (d10-d27) — confirms **the entire MDR 25-0093..0104 case-block is a single unified Joint Staff release tranche** at N=9 byte-for-byte attestations ^closed-by-dow-uap-d27 (firming class). Release dates within the unified tranche span at least 09/12/25 → 10/28/25 (~46 days), consistent with **opportunistic per-case adjudication within a unified tranche** ^[inferred].

**3-digit page-stamps in Block F** continue to match Block D (3-digit) and Block B (3-digit) — page-stamp width is **release-event-batch-specific within a block** ^closed-by-dow-uap-d27 (firming class).

## OCR ambiguities

- `# Misrep undefined-10055709` — **9th `undefined-` prefix attestation** (Block D 6 + Block E 1 + Block F 2; firms cross-block at N=9 — **NOT Block-D-specific, NOT Block-F-specific; pipeline-class artifact**) ^closed-by-dow-uap-d27 (firming class)
- `SECRET/NOFORM` — recurs (d23 had `NOFORM` → `NOTORN` glyph swap; d27 is `NOFORM`) ^[ambiguous] glyph stability vs swap-instability
- `(b)(1)1.4a` redactions throughout — standard pipeline artifact ^[extracted]
- Narrative DTG sequence is **internally out-of-order** ^[ambiguous]: lists 1822Z (7-line WX RTB), 2256Z (NIB 1), 0444Z (NIB 2), 0457Z (UAP 1), 0405Z (RTB), 0713Z (Landing) — the 1822Z 7-line and 0405Z RTB appear out of natural chronological sequence given takeoff 2100Z. Plausible readings: (a) 1822Z is the PRE-take 7-line tasking-assignment time (not post-take) — Misrep OCR is bundling event-DTGs from the briefing phase; (b) OCR has reshuffled segments. Reading (a) most parsimonious ^[inferred] given the explicit `7-LINED` clause aligns with mission-tasking nomenclature.
- `40QFM9a(1)1.4a(1)1.4a` UAP last-coordinate — the `9a` glyph may be OCR-corrupted `91`/`92` or similar ^[ambiguous]
- `(0)08` and `(0)1.4a` in GENTEXT/UAP — partial redactions OR OCR-corrupted aircraft-callsign tokens ^[ambiguous]
- `AH/GMESH/SF` — `SF` token expansion ^[ambiguous]: candidate (a) abbreviated `SANTA FE` (matches d25's third-token `SANTA FE` at N=1; would firm a `SANTA FE` family at N=2 in AFSOC class with abbreviated-vs-full OCR forms); candidate (b) `Special Forces` or other AFSOC-specific abbreviation; candidate (c) AIRHANDLER suffix unique to 3 SOS vs 33 SOS configurations. Resolution at N≥3 cross-document attestation.
- `# Misrep undefined-10055709` Misrep ID has **8 digits (10,055,709)** — first 8-digit Misrep ID in dow-uap full-Misrep corpus (d25 was 7-digit 9.6M; the 10M threshold crossed between d25 and d27). ^[extracted]

## Open threads

- **Block E recurrence at N≥2.** d27 does NOT recur Block E (d23 stays at N=1 with MDR 25-0104). **Still OPEN.** Future ingest may carry MDR 25-0104 case-number anywhere from d28+ in the unbatched FOIA release.
- **Block F potential at N=3 / N=4.** d25 + d27 = 2-of-4 Block F eligibility (4-case range `25-0100 thru 25-0103`). Two more Block F artifacts predicted ^[inferred]; recurrence would firm Block F at the same level of corpus-aggregate as Block D.
- **3 SOS vs 33 SOS cross-squadron AFSOC role**. d25 had 33 SOS Originator; d27 has 3 SOS Originator. Whether 3 SOS and 33 SOS are sister AFSOC MQ-9 SOSs (parallel pool) OR distinct squadron-class assignments (3 SOS may be U-28A or AC-130 platform) is unresolved ^[ambiguous]. AN/DAS-1 TGT Pod + 10:13 mission cycle + 27 SOW parent wing all support MQ-9 attribution ^[inferred].
- **`AH/GMESH/SF` token expansion.** Whether `SF` = abbreviated `SANTA FE` (d25 + d27 family at N=2) or distinct AFSOC SIGINT token at N=1 d27-specific. Resolution at N≥3.
- **`UAP RF Frequency` + `UAP RF Duration` template fields recurrence at N≥2.** d27 first to populate field labels. Does d28+ also carry these? If YES, anchors template-expansion as systematic. If NO, d27 may be a one-off template-fill variant ^[ambiguous].
- **UAP Event Serial Number `001`-suffix optional vs mandatory.** d25 had `CENTCOM 001`; d27 omits the suffix entirely. Whether the `001` is a CY-2024-first-CENTCOM counter that incremented mid-year and the counter is just suppressed in d27 (Reading a) OR the `001` was a d25-specific Misrep-curator add-on (Reading b) ^[ambiguous]. Resolution at N≥3 in another 2024-2025 CENTCOM AFSOC Misrep.
- **Glowing-hot-sphere + bottom-attached-appendage morphology class recurrence at N≥2.** d27 anchors at N=1; d25's diamond+probe shares only the bottom-attached-appendage axis. Resolution at N≥3 in another full-Misrep with object+appendage morphology.
- **OMAM AFSOC at N≥2.** d27 is the first AFSOC mission from OMAM. Whether AFSOC routes additional missions from OMAM (firming AFSOC-OMAM as a sustained lane) vs LGLR-only-with-OMAM-one-off remains open ^[open].

## See also

- [[references/dow-uap-d23-mission-uae-2023-10-24]] — immediate prior UAE-OMAM mission (24 Oct 2023, 432 AEW / 50 ATKS, OP SPARTAN SHIELD); d27 anchors second OMAM mission at AFSOC parallel pool with shared OMAM + 609 CAOC + Mission-Type ISR + AN/DAS-1 anchors; diverges on Operation, POC unit, POC Wing, MAJCOM, Block, supported unit, duration
- [[references/dow-uap-d25-mission-greece-2024-01-25]] — immediate prior AFSOC mission (25 Jan 2024, 33 SOS / 27 SOW LGLR Greece); d27 anchors AFSOC at N=2 in dow-uap corpus, with d27 shifting AFSOC launch from LGLR to OMAM + Originator squadron from 33 SOS to 3 SOS within 27 SOW parent
- [[references/dow-uap-d19-mission-syria-2023-02-21]] — prior shortest-cycle mission in dow-uap full-Misrep class (4h 55min F-15E DCA); d27 anchors second-shortest at 10h 13min (first WX-RTB-truncated MQ-9 ISR)
- [[references/dow-uap-d18-mission-iraq-2022-12-01]] — prior 482ATKS OIR-Iraq-MB mission; d27 shifts MAJCOM/Wing class entirely away from 432-AEW continuum
- [[references/dow-uap-d10-mission-middle-east-2022-05-06]] — 379 AEW APPROVER lane prior attestation (d27 + d10 + d64 = 3-of-6 = 50% prevalence within corpus-testable)
- [[references/dow-uap-d64-mission-iran-2020-11-02]] — 379 AEW APPROVER lane prior attestation (NAVCENT cluster)
- [[entities/dow-uap-foia-release]] — series anchor; d27 brings count to 30-of-40, firms Block F at N=2 + AFSOC at N=2
- [[entities/27-sow]] — recurs at N=2 (d25 + d27)
- [[entities/33-sos]] — sister AFSOC SOS to d27's 3 SOS Originator
- [[entities/afsoc]] — recurs at N=2 (d25 + d27); MQ-9 ISR pool parallel to 432 AEW firms cross-squadron
- [[entities/609-caoc]] — 609 AOC Det 1 recurs at N=2 in INVERSE positions (d25 POC home → d27 QC home); CENTCOM-forward AFSOC-liaison detachment reading firms ^closed-by-dow-uap-d27
- [[entities/432-aew]] — d27 confirms broken monopoly (12-of-14 = ~86% retention within MQ-9 ISR subset at d27 ingest)
- [[concepts/uap-aircraft-engagement]] — sub-class taxonomy; sub-class 14 firms at N=3 with morphology axis
- [[projects/uap/uap]]
