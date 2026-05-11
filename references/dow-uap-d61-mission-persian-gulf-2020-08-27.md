---
title: "DoW-UAP-D61 — Full Misrep 4685903 (482ATKS / 432 AEW MQ-9, 26-27 Aug 2020, Arabian Gulf)"
category: references
tags: [uap, primary-source, declassified, usaf, sighting]
aliases: [DoW-UAP-D61, dow-uap-d61]
sources: [sources/dow-uap-d61-mission-report-persian-gulf-august-2020.json]
summary: 7-page Mistral-OCR'd Misrep 4685903 — second FULL USMTF Misrep in dow-uap corpus; 26-27 Aug 2020 NAVCENT support over Arabian Gulf/Strait of Hormuz/Gulf of Oman by same 482ATKS/432 AEW MQ-9 as d60 (19 days later); FORMATION OF UNK FLYING OBJECTS at 1527Z bounded 2-min track; Iranian Air Defense GUARDCALL at 0532Z; carries Block B release framework (MDR 26-0019 + 001→007).
provenance:
  extracted: 0.62
  inferred: 0.33
  ambiguous: 0.05
base_confidence: 0.78
lifecycle: draft
lifecycle_changed: 2026-05-12
created: 2026-05-12T01:00:00Z
updated: 2026-05-12T01:00:00Z
event_date: 2020-08-27
project: uap
---

# DoW-UAP-D61 — Full Misrep 4685903 (482ATKS / 432 AEW MQ-9, 26-27 Aug 2020, Arabian Gulf)

A **7-page Mistral-OCR'd artifact** (`sources/dow-uap-d61-mission-report-persian-gulf-august-2020.json`, 9,694 bytes; SHA-256 `d81f857b10cfc708e30dd965032328c113c48159a0eccb14bde0c821aec3bd2c`) — the **fifteenth artifact** in the [[entities/dow-uap-foia-release|DoW-UAP FOIA release series]] (15-of-40) and the **second FULL USMTF Misrep ingest** in the corpus. d61 is the structural replicate of [[references/dow-uap-d60-mission-persian-gulf-2020-08-08|d60]] at the document-class level: all 7 pages substantive (zero header-only padding), complete USMTF segment set (Narrative + Admin + MSGID + MSNID + POC + QC + APPROVER + INGEST + ACEQUIP + Timeline {Landing + Takeoff + On Station + ISR + Off Station + GUARDCALL + GENTEXT/GUARDCALL + OBSERVATION + GENTEXT/OBSERVATION + WEATHER + EFFECTIVENESS} + GENTEXT/ISR + ISR ASSET UTILIZATION), and a **bounded 2-minute UAP-formation track** anchored on the same 482ATKS / 432 AEW MQ-9 ^[inferred] flown for the same NAVCENT-support tasking over the same Arabian Gulf / Strait of Hormuz / Gulf of Oman corridor as d60. Mission cycle 26-27 Aug 2020 (UAP datum on 27 Aug at 1527Z), **19 days after d60** (8 Aug 2020).

The d61 ingest delivers **three corpus-level headline findings** simultaneously, in priority order:

1. **Block B doubles to 2-of-7 release-block-testable artifacts.** d61's release block carries `USCENTCOM MDR 26-0019` + `01/26/26 001 → 007` — byte-for-byte the **same Block B** as [[references/dow-uap-d38-range-fouler-middle-east-may-2020|d38]]'s. The d60 reading "**d38 Block B isolated at 1-of-6**" is **superseded**: Block B is no longer isolated. Block A = 5-of-7 (d55+d58+d44+d56+d60); Block B = **2-of-7** (d38+d61). Within Block B, **per-document sequential page-stamping is now anchored at N=2** with d38's `001` (single-page) and d61's `001→007` (7-page). The 3-digit page-stamp scheme is a **Block-B-internal convention** (vs Block A's 6-digit scheme); per-document-page-sequence reading holds in both blocks. ^[inferred] **Headline finding.**
2. **Three d60-anchored open threads close decisively at N=2.** The d60 ingest left the full-Misrep class as an N=1 anchor with three forward-anchored test points; d61 closes all three: (a) "Validate full-Misrep document class at N≥2" → CLOSED (d61 is full Misrep, 7 substantive pages, complete segment set; ^closed-by-dow-uap-d61); (b) "Test multi-segment-Timeline structure at N≥2" → CLOSED (d61 carries the same Landing / GUARDCALL / OBSERVATION / Takeoff / On Station / ISR / Off Station Timeline sub-segments; canonical USMTF-Misrep Timeline schema confirmed; ^closed-by-dow-uap-d61); (c) "Test Iranian Air Defense GUARDCALL recurrence pattern" → CLOSED (d61 carries Iranian Air Defense direct hail at 0532Z with `PROFESSIONAL` tone and standard exchange; foreign-state direct hail is now a **class-level signature of CENTCOM-AOR ISR missions**, not a d60 outlier; ^closed-by-dow-uap-d61). The full-Misrep class is **CONFIRMED at N=2** as the fourth top-level mission-record sub-class.
3. **Same-unit paired-mission cluster at 19-day separation.** d60 (8 Aug 2020) + d61 (26-27 Aug 2020) are flown by the **same 482ATKS / 432 AEW MQ-9 Reaper ^[inferred] flight**: same POC unit (482ATKS) / wing (432 AEW) / APPROVER (609th AOC / 609 CAOC) / QC role (PAROC / 12AF / DET 3) / supported command (NAVCENT) / operation (`Operation 1.4a` portion-redacted) / theater (Arabian Gulf / Strait of Hormuz / Gulf of Oman) / launch-and-recovery base (OKAS Kuwait ^[inferred]) / mission type (AREC) / sensor stack (`ANDAS4` TGT pod + `AH_GMESH` Additional Avionics) ^[inferred]. **The paired-mission cluster is the corpus's first internal evidence of same-unit-same-tasking repeat-incident dynamics** — same MQ-9 deployment flying back-to-back Arabian-Gulf NAVCENT-support missions across August 2020, both producing UAP observations during the supported tasking. ^[inferred] **Second headline finding** behind Block B doubling.

## What the source actually contains

The OCR pulls **7 pages**, each `dpi: 93`, all carrying explicit per-page declassification banners and **all substantive** (zero header-only padding pages — matches d60's structural pattern). Every page also carries the explicit `(b)(6)` redaction block + `USCENTCOM MDR 26-0019` + `Approved for Release to AARO` + `01/26/26 00N` (where `N` is the page index 1–7).

**Page-top metadata block (recurring on every page):**

```
Declassified by MG Richard A. Harrison
USCENTCOM Chief of Staff
Declassified on 22 January 2025
```

**OCR ambiguity at page 6 banner**: page 6 (the last page) reads `Declassified on: 22 January 2020` rather than `2025`. ^[ambiguous] Almost certainly an OCR digit-swap (2-vs-5) for `2025` — all other 6 pages render `2025` consistently, and `2020` is incompatible with the originating-event date (26-27 Aug 2020 mission) since declassification cannot precede classification. ^[inferred]

**Page-bottom release block (recurring on every page, with N = page index):**

```
3.5c. (b)(6)

USCENTCOM MDR 26-0019
Approved for Release to AARO
01/26/26 00N
```

The release-sequence number runs **`001` (page 0) → `007` (page 6)** — 3-digit-scheme sequential page-stamps. See *Release framework — Block B at N=2* below.

**Substantive content by page:**

| Page | Substantive segments |
|---|---|
| 0 | Document header `# Misrep 4685903` + `## Narrative` (free-text BLUF-equivalent) + `## Admin` (CLASSIFICATION + OPERATION + MSGID + MSNID start) |
| 1 | MSNID continuation (Mission Type / ATO Mission Number / Country Tasked / Service Tasked) + `## Poc` block (POC + QC + APPROVER blocks) + INGEST start |
| 2 | INGEST continuation + `# ACEQUIP` (full aircraft-equipment block) |
| 3 | Gentext (top) + `## Timeline` (Landing + Takeoff + On Station + ISR start) |
| 4 | ISR continuation + `## GENTEXT/ISR` (mission-narrative incl. UAS / Iranian-naval-port / NASER WAP / IL-76 Candid observations) + ISR ASSET UTILIZATION + WEATHER + EFFECTIVENESS |
| 5 | Off Station + `## GUARDCALL` + `## GENTEXT/GUARDCALL` + `## OBSERVATION` (the UAP-event structured block) + `## GENTEXT/OBSERVATION` start |
| 6 | GENTEXT/OBSERVATION end + WEATHER |

The **substantive UAP datum is in `GENTEXT/OBSERVATION`**, matching d60's segment placement — `GENTEXT/OBSERVATION` is now anchored at N=2 as the canonical USMTF segment for UAP datums within the full-Misrep sub-class. ^[inferred] See *Segment-name distinction firms at N=2* below.

## The UAP datum

The single UAP-event appears in the `OBSERVATION` structured block (page 5) and the `GENTEXT/OBSERVATION` narrative segment (page 5 → 6):

| Field | Value | Notes |
|---|---|---|
| Observation DTG | **271527:00ZAUG20** | **27 Aug 2020 at 1527Z** — second explicit calendar-date + UTC-time anchor on a UAP datum in the full-Misrep sub-class; 19 days after d60's 080726Z. |
| Aircraft Callsign | **1.4a** | Portion-redacted under EO 13526 §1.4(a) — same redaction pattern as d60. |
| Aircraft Location | **39RVM38 1.4a 5 1.4a** | MGRS UTM zone 39R square VM — Persian Gulf interior. ^[inferred] |
| Aircraft Heading / Altitude / Airspeed | (all blank — `-`) | Witness-aircraft kinematic state not preserved on the OBS line — same blanking pattern as d60. |
| Relative Bearing / Range / Killbox | (all blank — `-`) | UAP-relative geometry not preserved. |
| Observed Activity Location | **39RVM88 1.4a 5 1.4a** | UAP position MGRS — UTM zone 39R square VM, **same 100-km grid square as the aircraft (VM)**, ~50 km east of aircraft. ^[inferred] |
| Observed Activity Description | **FORMATION OF UNK FLYING OBJECTS** | **Distinct from d60's `TRANSITTING`** — d61 anchors a **multi-object formation** descriptor; first explicit `FORMATION OF UNK FLYING OBJECTS` activity descriptor in the dow-uap mission-report sub-class. ^[inferred] |
| Method of Observation | **1.4a SENSOR** | Portion-redacted sensor designator (likely MTS-B EO/IR turret ^[inferred] consistent with the MQ-9 platform attribution and DGS PED context, but the explicit `FMV` token from d60 is **absent**). ^[ambiguous] |
| GENTEXT/OBSERVATION | `(S/REL) FROM 1527Z TO 1529Z, 1.4a OBSERVED A FORMATION OF FLYING OBJECTS TRAVELING NE-NW ALONG THE COAST IVO 39RVM88 1.4a 5 1.4a 1.4a WAS TRACKING THIS FORMATION FOR APPROXIMATELY 2 MINUTES BEFORE PID WAS LOST IN CLOUD COVER. AIRCREW WAS UNABLE TO GAIN PID AGAIN ON THIS FORMATION` | Bounded 2-minute track; NE-to-NW heading along the coast (azimuth varying); positive-identification (PID) lost in cloud cover; aircrew unable to re-acquire. |
| WEATHER | `LIGHT CLOUD COVERAGE PREVENTED THE CONTINUOUS TRACKING OF THE FORMATION` | First explicit weather-as-tracking-obstacle attestation in dow-uap corpus. ^[inferred] |
| Portion marking | **`(S/REL)`** | First explicit `(S/REL)` (Secret / Releasable) portion-marking on a UAP datum in the full-Misrep sub-class; sixth distinct portion-marking state in the corpus (joins `(S/REL FVEY)` d4/d5, `(SECRET)`-only d7, absent d54, `(S/REL TO USA, FIN, SWE, FVEY, NATO)` d8, `SECRET/IREL TO USA, NATO` d55). |

**Multi-object formation, bounded 2-minute track, NE-NW azimuth, PID-loss-on-weather** — distinct from d60's bare-FMV-instant-observation signature. The d61 datum carries **partial kinematics** (heading axis explicit; speed implicit; altitude UNK), **explicit duration** (`APPROXIMATELY 2 MINUTES`), **explicit tracking-loss cause** (cloud cover), **morphology blank** (no shape descriptor beyond "FLYING OBJECTS"), and **count > 1** (FORMATION implies ≥2 objects ^[inferred]). The signature is **a bounded multi-object formation track terminated by weather-induced sensor loss**. ^[extracted]

## Multi-object datum-counting + sub-class assignment

d61's `FORMATION OF UNK FLYING OBJECTS` carries no explicit object count (vs d8's `2X UAPS` or d58's `2X UAPS`). Working count: **1 datum** (single event, formation-as-aggregate-object per d60-convention of single-event-per-record).

**Sub-class assignment within brief-observation** — the d61 datum carries qualitatively distinct properties from the prior 8 sub-classes catalogued at [[concepts/uap-aircraft-engagement|concepts/uap-aircraft-engagement.md]]:

- Distinct from `kinematic-anomaly` (d4 + d5-B + d8): no UAP speed reported; only heading-axis is given.
- Distinct from `steady-state cruise` (d5-A): no constant-velocity datum.
- Distinct from `prosaic-candidate wind-borne` (d7): no morphology call.
- Distinct from `morphology-rich kinematics-thin` (d54): no morphology call.
- Distinct from `prosaic-candidate-with-explicit-CTG-identification` (d55): no prosaic identification posture.
- Distinct from `range-fouler-attempted-ID` (d58) and `range-fouler-passive-ISR` (d38/d44/d56): mission-report not range-fouler-debrief class.
- Distinct from `FMV-observation + zero-mission-impact + kinematics-blank + morphology-blank` (d60): UAP duration bounded; tracking-loss-on-weather; formation count >1; method = `1.4a SENSOR` not explicit FMV.

**d61 anchors a ninth distinct brief-observation sub-class**: **formation-track + bounded-duration + heading-axis-only + sensor-PID-loss-on-weather**. ^[inferred] The signature is **a multi-object formation observed under deteriorating weather conditions, tracked for a bounded interval before the sensor lost positive identification**.

Alternative reading: extend sub-class 1 (kinematic-anomaly) with a multi-object-partial-kinematic variant. **Rejected**: kinematic-anomaly's anchor is *speed change* (d4 321 kt → speed-up; d5-B 278 kt → speed-up; d8 240 kt DYNAMIC SOUTH); d61 reports neither speed nor speed change, only a heading axis. The signature is morphologically dissimilar to sub-class 1. ^[inferred]

**Mission-report UAP-datum counter increments N=6 → N=7 records / 7 → 8 datums** at the dow-uap level. ^[inferred]

## Segment-name distinction firms at N=2

The d60 ingest raised two readings for the `GENTEXT/OBSERVATION` (d60) vs `GENTEXT/UAP` (d4/d5/d7/d8/d54) segment-name distinction:

1. **Reading 1 (full-Misrep vs extracted-segment, curator-renamed)**: `GENTEXT/OBSERVATION` is the canonical USMTF segment within full-Misrep parent documents; `GENTEXT/UAP` is the curator's rename applied to extracted single-segment UAP datums at release time.
2. **Reading 2 (originating-service convention)**: `GENTEXT/UAP` (Navy F/A-18 / fighter community) vs `GENTEXT/OBSERVATION` (USAF MQ-9 / ISR community).

**d61 firms Reading 1 at N=2** ^[inferred]: d61 is a second USAF MQ-9 full-Misrep parent document with the substantive UAP datum in `GENTEXT/OBSERVATION` — same segment placement as d60. The full-Misrep class consistently uses `GENTEXT/OBSERVATION`; the single-segment extracts (d4/d5/d7/d8/d54) consistently use `GENTEXT/UAP`. Under Reading 2, the segment-name correlates with originating service (USAF MQ-9 = OBSERVATION); under Reading 1, the segment-name correlates with document class (full Misrep = OBSERVATION). At N=2 full-Misrep ingests both from the same USAF MQ-9 unit (482ATKS), the two readings remain **observationally equivalent** — service and document-class are confounded in the sample. A future full-Misrep ingest from a Navy unit (e.g. an F/A-18 P-8A or MH-60R parent Misrep) would discriminate the two readings. ^[inferred] **Reading 1 remains operationally most coherent** at N=2 absent contrary evidence.

## Iranian Air Defense GUARDCALL — class-level recurrence at N=2

Page 5 carries an explicit **GUARDCALL** structured block + `GENTEXT/GUARDCALL` segment documenting a foreign-state radio hail of the aircraft — the **second Iranian Air Defense hail in the dow-uap corpus** after d60's 081250Z attestation:

| Field | Value | Notes vs d60 |
|---|---|---|
| GUARDCALL DTG | **270532:00ZAUG20** | 27 Aug 2020 at 0532Z — ~9 hr 55 min **before** the UAP OBS event (1527Z). d60: hail at 1250Z came ~5 hr 24 min **after** the UAP OBS event (0726Z). The temporal sequencing relative to UAP event is **opposite at N=2** — GUARDCALL precedes UAP at d61, follows UAP at d60. ^[inferred] |
| Aircraft Callsign | `1.4a` | Same redaction pattern. |
| Ground Station Callsign | **IRANIAN AIR DEFENSE** | d60 used `IRANIAN AIR DEFENSE GUARD`; d61 omits the trailing `GUARD` suffix. ^[ambiguous] OCR variance or document-internal phrasing variance. **Iranian Air Defense ground-station class confirmed at N=2.** ^[inferred] |
| Aircraft Location | **40RCP78 1.4a 5 1.4a** | **MGRS UTM zone 40R** — same eastern-Persian-Gulf / Strait-of-Hormuz approach as d60's 40RCP98. **Zone-and-square match (40R / CP)** at N=2; the GUARDCALL geometry is **anchored at the eastern Persian Gulf approach** as a structural pattern at N=2. ^[inferred] |
| Aircraft Heading | **018 M** | 018° Magnetic — northerly (slightly E of N). d60: HDG 200 (southerly). Opposite-direction at N=2 (consistent with the aircraft transiting the same eastern-Gulf airspace in different directions across the two missions). ^[inferred] |
| Aircraft Altitude | **FL150** | 15,000 ft pressure altitude. d60: FL170. **2,000 ft delta** within MQ-9 cruise envelope. ^[inferred] |
| Aircraft Airspeed | (blank — `-`) | d60: 110 KIAS. Not preserved on d61. |
| Number of Calls Noted | **1** | Single hail at d61. Same as d60. |
| Guardcall Tone | **PROFESSIONAL** | Same as d60. `PROFESSIONAL` tone is **anchored at N=2** as the class-level Iranian Air Defense / US ISR exchange tone. ^[inferred] |
| GENTEXT/GUARDCALL | `AT 0532Z, 1.4a WAS HAILED ON GUARD 1.4g FREQ BY IRANIAN AIR DEFENSE. ORDERS GIVEN: STANDARD CALL. 1.4a GAVE A STANDARD RESPONSE. NO MISSION IMPACTS` | Slightly different phrasing from d60 (`NO IMPACT TO THE MISSION` vs `NO MISSION IMPACTS`) but operationally identical: standard call → standard response → no mission impact. |

**The GUARDCALL recurrence is decisive at N=2.** Iranian Air Defense direct hails of US MQ-9 ISR assets in the eastern Persian Gulf / Strait of Hormuz approach are a **class-level signature of 482ATKS / 432 AEW NAVCENT-support tasking in the Aug 2020 window**. ^[inferred] The d60 reading "first foreign-state direct hail in dow-uap corpus" remains correct as an order-of-discovery claim, but at N=2 this is no longer an outlier — it is the **routine operational context** of CENTCOM-AOR MQ-9 ISR missions in the contested-airspace eastern Gulf. The temporal-sequencing variance (pre-UAP at d61, post-UAP at d60) suggests **no causal link between GUARDCALL and UAP events** — they are independent operational phenomena within the same mission profile. ^[inferred]

**This closes a d60 open thread** (^closed-by-dow-uap-d61): "Test the Iranian Air Defense GUARDCALL recurrence pattern — does the next dow-uap full-Misrep carry a foreign-state direct hail? If recurrent, GUARDCALL is a class-level signature of CENTCOM-AOR ISR missions, not a d60 outlier."

## Platform attribution — same 482ATKS / 432 AEW MQ-9 as d60

The d61 POC block (page 1) supplies a **byte-for-byte match** with d60 on every unit-attribution field:

| Role | d60 | d61 | Match? |
|---|---|---|---|
| POC Rank | 1st Lt | 1st Lt | **MATCH** |
| POC Unit | 482ATKS | 482ATKS | **MATCH** |
| POC Wing | 432 AEW | 432 AEW | **MATCH** |
| POC Service | Air Force | Air Force | **MATCH** |
| POC Operations Center | 609 CAOC | 609 CAOC | **MATCH** |
| QC Rank | Ctr (contractor) | Ctr | **MATCH** |
| QC Unit | (PAROC at 15 AF / DET 1 or similar) | 12AF, Det 3, PAROC | **MATCH on PAROC role** (d61 explicit `12AF, Det 3, PAROC`) |
| QC Wing | Other | Other | **MATCH** |
| APPROVER Rank | 1st Lt | 1st Lt | **MATCH** |
| APPROVER Unit | 609th AOC | 609th AOC | **MATCH** |
| APPROVER Service | Air Force | Air Force | **MATCH** |
| APPROVER Operations Center | 609 CAOC | 609 CAOC | **MATCH** |
| MSGID Originator | 482ATKS | 482ATKS | **MATCH** |
| Operation | 1.4a | 1.4a | **MATCH** (both portion-redacted; possibly same operation name) |
| Domain | AIR | AIR | **MATCH** |
| Operations Center (Admin) | 609th | 609th | **MATCH** |
| MAJCOM | ACC | ACC | **MATCH** |
| COCOM | USCENTCOM | USCENTCOM | **MATCH** |
| Report Type | MISREP | MISREP | **MATCH** |
| Mission Type | AREC | AREC | **MATCH** |
| Country Tasked | US - UNITED STATES | US - UNITED STATES | **MATCH** |
| Service Tasked | A - AIR FORCE | A - AIR FORCE | **MATCH** |
| Takeoff / Landing ICAO | OKAS | OKAS | **MATCH** (Ali Al Salem AB, Kuwait ^[inferred]) |
| TGT Pod | ANDAS4 | ANDAS4 | **MATCH** |
| Additional Avionics | AH_GMESH | AH_GMESH | **MATCH** |
| Supported Unit | NAVCENT | NAVCENT | **MATCH** |
| Supported Operation | OPERATION 1,4a | OPERATION 1,4a | **MATCH** (both portion-redacted) |
| Precoord Time | 24 HOURS | 24 HOURS | **MATCH** |
| Precoord Effectiveness | SATISFACTORY | SATISFACTORY | **MATCH** |

**31-axis match at the unit / platform / tasking level.** The d60 + d61 pair is the corpus's **first internally-attested same-unit-same-tasking repeat-mission cluster**. ^[inferred] The 482d Attack Squadron / 432 AEW MQ-9 deployment ^[inferred] at OKAS was flying recurring NAVCENT-support AREC tasking over the Arabian Gulf / Strait of Hormuz / Gulf of Oman corridor throughout August 2020, with both missions producing a UAP observation during the supported tasking.

**The d61 QC unit explicitly attests `12AF, Det 3, PAROC`** — this is the **same 12 AF / DET 3 PAROC role** attested at [[references/dow-uap-d50-email-indopacom-2025-04|d50]] (INDOPACOM email correspondence, Apr 2025). The 12 AF / DET 3 PAROC role now anchors at **two distinct operational contexts** in the dow-uap corpus: the d50 INDOPACOM tearline-clearance email (Apr 2025) and the d61 CENTCOM Misrep QC role (Aug 2020). ^[inferred] **The d60 ingest noted the QC role as `PAROC` without specifying the parent detachment** — d61's explicit `12AF, Det 3, PAROC` attests that the **12 AF / DET 3 PAROC** is the QC counterparty for the 482ATKS / 432 AEW MQ-9 mission stream. ^[inferred]

**PAROC IDAT triple-attestation extends to N=4** (counting d61): d52 (15 AF / DET 1 PAROC) + d50 (12 AF / DET 3 PAROL or PAROC) + d60 (PAROC unspecified parent) + d61 (12 AF / DET 3 PAROC explicit). **d61 partially resolves the d50 PAROC vs PAROL OCR ambiguity** — d61's clean `PAROC` attestation in the same 12 AF / DET 3 cell strengthens the PAROC reading over PAROL at 12 AF / DET 3. ^[inferred]

## Mission timeline — the full operational picture

The d61 Misrep Narrative + Timeline segments reconstruct the **complete 21h 5min mission cycle** (second complete operational timeline in the dow-uap corpus):

| Time (Z) | Event | Source |
|---|---|---|
| **262307:00Z** | Takeoff from OKAS (Ali Al Salem AB, Kuwait ^[inferred]) — **26 Aug 2020** | Takeoff block + Narrative |
| **262320:00Z** | Handed over from LRE | Narrative |
| **270003:00Z** | Started SIGINT collection via AIRHANDLER ^[inferred] | Narrative |
| **270041:00Z** | Arrived on station ISO NAVCENT, Operation 1.4a (IVO Arabian Gulf, Strait of Hormuz, Gulf of Oman) | On Station + ISR blocks + Narrative |
| **270532:00Z** | **Iranian Air Defense GUARDCALL — see § Iranian Air Defense GUARDCALL above** | GUARDCALL block |
| **270611:00Z** | 1X small vessel observed at Greater Tunb naval port IVO 40RCQ30 1,4a D 6 1,4a (Iranian-occupied Greater Tunb Island in the Strait of Hormuz ^[inferred]) | GENTEXT/ISR |
| **270700:00Z** | 1X POSS IL-76 Candid observed at Abu Musa Island AFLD IVO 40RCP02 1,4a 53 1,4a (Iranian-occupied Abu Musa Island ^[inferred]) | GENTEXT/ISR |
| **271527:00Z** | **UAP observation start — see § The UAP datum above** | GENTEXT/OBSERVATION |
| **271529:00Z** | UAP observation end — PID lost in cloud cover | GENTEXT/OBSERVATION |
| **271742:00Z** | 1X POSS Naser WAP + 2X adult males observed on rear deck, both DIW (dead in water) IVO 39RUN49 1,4a 12 1,4a | GENTEXT/ISR |
| **271840:00Z** | Cleared off tasking; RTB | ISR + Off Station blocks + Narrative |
| **271944:00Z** | Handed back to LRE | Off Station block + Narrative |
| **272012:00Z** | Landed at OKAS | Landing block + Narrative |
| **272022:00Z** | Last engine shutdown | Landing block |
| (totals) | **21h 5min mission time / 21 mission hr / 17.9 IMINT hr / 19.2 SIGINT hr / 1 IMINT tasking / 1 SIGINT tasking / 2 total taskings** | Narrative |

**Notable narrative anomaly**: the GENTEXT/ISR segment renders these events in a non-chronological order (1742Z appears before 0700Z in the OCR text — page 4). ^[ambiguous] This is almost certainly an OCR field-order scramble or in-document narrative re-ordering, not a real chronological anomaly. ^[inferred] The timestamps themselves remain reliable.

**Mission-cycle DTG anchor count at N=2**: d60 carried 8 distinct anchors; d61 carries **14 distinct DTG anchors** (incl. 4 collateral-ISR observations — 1 small vessel, 1 IL-76 Candid, 1 Naser WAP + 2 ADMs, plus the UAP and GUARDCALL events). d61 is **more operationally-detail-rich than d60** on the within-mission event timeline. ^[inferred]

## Collateral ISR observations — Iranian naval activity at three sites

The GENTEXT/ISR segment preserves **three Iranian-naval-activity observations** in addition to the UAP datum and GUARDCALL event:

1. **0611Z — 1X small vessel docked at Greater Tunb Naval Port** IVO MGRS `40RCQ30 1,4a D 6 1,4a`. Greater Tunb Island is an Iranian-occupied (Iranian-claimed) island in the Strait of Hormuz, disputed by the UAE. ^[inferred] The naval port is operated by the IRGCN (Islamic Revolutionary Guard Corps Navy). ^[inferred]
2. **0700Z — 1X POSS IL-76 Candid at Abu Musa Island AFLD** IVO MGRS `40RCP02 1,4a 53 1,4a`. Abu Musa Island is an Iranian-occupied (Iranian-claimed) island in the eastern Persian Gulf, disputed by the UAE. ^[inferred] The Ilyushin Il-76 Candid is a Russian-design heavy-lift transport aircraft, of which Iran operates a small fleet (~12 airframes). ^[inferred]
3. **1742Z — 1X POSS Naser WAP + 2X ADMs (adult males) on rear deck, both DIW (dead in water)** IVO MGRS `39RUN49 1,4a 12 1,4a`. The **Naser-class missile patrol boat** (`Naser WAP` = Weapon-Armed Patrol or similar) is an Iranian fast-attack craft operated by the IRIN (Islamic Republic of Iran Navy). ^[inferred] DIW status with 2 personnel on rear deck is consistent with a stationary patrol-boat-and-tender configuration. ^[inferred]

**Operational significance**: the three collateral observations explicitly target **Iranian-naval-presence pattern-of-life data** — the stated ISR objective (per GENTEXT/ISR: `TO CHARACTERIZE IRIN/IRGCN VESSELS, UAS ACTIVITY, ACTIVITY OUTSIDE OF PORTS, AND TO ESTABLISH PATTERN OF LIFE`) is **explicit anti-Iran maritime surveillance**. The UAP observation is **embedded within an explicit anti-Iran ISR mission**; the GUARDCALL is an Iranian-Air-Defense response to the surveillance posture; the collateral ISR observations document Iranian-naval-and-air assets on the same mission. ^[inferred] **First explicit explicit-anti-Iran-pattern-of-life-tasking attestation in the dow-uap corpus.** ^[inferred] (d60's GENTEXT/ISR was not similarly detailed — d61 supplies the operational-detail layer that d60 left implicit.)

## Geographic decoding — same theater as d60, refined eastern-Gulf coverage

The d61 internal MGRS coordinates supplement d60's 5-coord set with **7 additional coordinates** across UTM zones 39R + 40R:

| MGRS | UTM Zone / Square | Inferred sub-region | Block |
|---|---|---|---|
| **39RUN46 1,4a 38 1,4a** (Tasked Start Point, ISR block) | 39R / UN | Persian Gulf western interior ^[inferred] | ISR tasking |
| **40RCQ30 1,4a D 6 1,4a** (Greater Tunb Naval Port) | 40R / CQ | Strait of Hormuz — Iranian Greater Tunb Island ^[inferred] | Collateral ISR |
| **40RCP02 1,4a 53 1,4a** (Abu Musa Island AFLD, IL-76 Candid obs) | 40R / CP | Eastern Persian Gulf — Iranian Abu Musa Island ^[inferred] | Collateral ISR |
| **40RCP78 1.4a 5 1.4a** (Aircraft Location, GUARDCALL block) | 40R / CP | Eastern Persian Gulf / Strait of Hormuz approach ^[inferred] | GUARDCALL |
| **39RVM38 1.4a 5 1.4a** (Aircraft Location, OBS block) | 39R / VM | Persian Gulf interior ^[inferred] | **UAP event** |
| **39RVM88 1.4a 5 1.4a** (Observed Activity Location, OBS block) | 39R / VM | Persian Gulf interior, same 100-km square as aircraft ^[inferred] | **UAP event** |
| **39RUN49 1,4a 12 1,4a** (Naser WAP + 2 ADMs DIW) | 39R / UN | Persian Gulf interior ^[inferred] | Collateral ISR |

**All 7 internal MGRS coordinates decode inside the body-text-declared `IVO ARABIAN GULF, STRAIT OF HORMUZ AND GULF OF OMAN` operational area** (UTM zones 39R + 40R). ^[inferred] **d61 extends d60's filename-axis verification to N=2** at the internal-coord level for `*-persian-gulf*`-class filenames. **Combined d60 + d61 = 12-of-12 internal MGRS coordinates decode inside the body-text-declared Arabian Gulf area** — robust at N=2.

**The aircraft + UAP coordinates are in the same 100-km MGRS square (39RVM)** at d61 — the UAP was within ~50–80 km of the aircraft, **closer than d60's three-square spread (WK / WL / VL)**. ^[inferred] However, neither d60 nor d61 reports a witness-aircraft-to-UAP range or relative bearing — the close-co-location reading is from MGRS geometry alone.

**Filename-date axis**: filename `august-2020` ↔ body `262307Z AUG 20` (takeoff) + `27 AUG 2020 1527Z` (UAP) + `272012Z AUG 20` (landing). **MATCH at the month level** ^[inferred] — body events span 26-27 Aug 2020 mission cycle.

**Page filename convention**: per d60 precedent (filename `august-2020` → page `2020-08-08` anchored to UAP observation date), d61's page is `references/dow-uap-d61-mission-persian-gulf-2020-08-27.md` (UAP observation at 27 Aug 1527Z).

## Release framework — Block B at N=2; d38 no longer isolated

The d61 release block on every page carries **Block B**, matching [[references/dow-uap-d38-range-fouler-middle-east-may-2020|d38]] on all four shared axes:

| Field | Block B (d38) | d61 | Match? |
|---|---|---|---|
| Declassification authority | MG Richard A. Harrison | MG Richard A. Harrison | **MATCH** |
| MDR case | `26-0019` (single case) | `26-0019` (single case) | **MATCH** |
| Routing stamp | Approved for Release to AARO | Approved for Release to AARO | **MATCH** |
| Release-stamp date | `01/26/26` | `01/26/26` | **MATCH** |
| **Release sequence #** | `001` (single-page) | **`001 → 007`** (sequential 7-page) | **EXTENDS** (d38 was single-page; d61 multi-page; **per-document sequential page-stamping anchored within Block B at N=2 — 3-digit scheme**) |

**Critical findings flowing from d61's Block B attestation**:

1. **Block B doubles from 1-of-6 to 2-of-7 release-block-testable artifacts.** d38 is no longer isolated; d38 + d61 = Block B. Block A = d55 + d58 + d44 + d56 + d60 = 5-of-7. The asymmetric Block A dominance softens; Block B is anchored as a stable second allocation, not an outlier. ^[inferred] **Headline finding.**
2. **Per-document sequential page-stamping is confirmed in both Blocks at N=2 each.** Block A: d56 + d44 + d58 + d55 single-page = `000001`; d60 multi-page = `000001→000006`. Block B: d38 single-page = `001`; d61 multi-page = `001→007`. Within each Block the page-stamp scheme is consistent (Block A = 6-digit, Block B = 3-digit), and the per-document sequential reading holds. **Per-Block page-stamp scheme is a class-level signature** ^[inferred]: Block-A artifacts carry 6-digit page-stamps, Block-B artifacts carry 3-digit page-stamps. ^[inferred]
3. **The two Blocks differ on three orthogonal axes**:
    - MDR case allocation (`26-0019` vs `26-0038 to 26-0046`)
    - Release-stamp date (`01/26/26` vs `03/27/26` — 60 days apart)
    - Page-stamp digit scheme (3-digit vs 6-digit)
   All three axes are coherently correlated at N=2 each — Block B uses `26-0019` + `01/26/26` + 3-digit; Block A uses `26-0038-46` + `03/27/26` + 6-digit. The dow-uap release was a **multi-batch operation** with at least two distinct release events 60 days apart, each carrying its own page-stamp scheme. ^[inferred]
4. **Block B temporally precedes Block A**: d38 + d61 release stamp `01/26/26` (26 Jan 2026) is 60 days earlier than d55 + d58 + d44 + d56 + d60's `03/27/26` (27 Mar 2026). The Block B documents were released first, the Block A documents second. ^[inferred]
5. **Class distribution across Blocks**:
    - Block A range-fouler debriefs: d55 (CTG narrative) + d58 + d44 + d56
    - Block A full Misrep: d60
    - Block B range-fouler debrief: d38
    - Block B full Misrep: d61
   Both top-level mission-record classes (range-fouler debrief + full Misrep) appear in both Blocks. The Block split is **orthogonal to document class** ^[inferred] — Block assignment is driven by release-batch timing, not by document type.
6. **AARO-receiving-authority closure firms further at N=7 stamp-recurrence** across the corpus (5 Block A + 2 Block B). ^[inferred]

## Behavioral classification — N=7 mission-report UAP-datum counter increment

Per the [[concepts/uap-aircraft-engagement|UAP–Aircraft Engagement]] framework:

- **UAP-toward-aircraft engagement-class**: **negative datum** — no close approach (MGRS positions differ; no co-location to within engagement-class bounds); no target switching; no phase-of-flight correlation. The d61 UAP is observed at a separate MGRS coord from the witness aircraft (~50–80 km separation ^[inferred]) and described as `FORMATION OF UNK FLYING OBJECTS TRAVELING NE-NW ALONG THE COAST` — formation-track signature, no engagement.
- **Aircraft-toward-UAP engagement-pipeline**: **negative datum** — no weapons-quality track, no NTS, no TFLIR ID, no closure attempt. The MQ-9 observed via portion-redacted `1.4a SENSOR` (likely MTS-B EO/IR ^[inferred] consistent with d60); passive ISR observation only.
- **Sub-class within brief-observation**: **formation-track + bounded-duration + heading-axis-only + sensor-PID-loss-on-weather** — **a ninth distinct brief-observation sub-class** (see § Multi-object datum-counting + sub-class assignment).

**Mission-report UAP-datum counter increments N=6 → N=7 records / 7 → 8 datums** at the dow-uap level. ^[inferred] The renamed framing from d60 (`mission-report UAP-datum records`) persists.

## Bibliographic frame

| Field | Value |
|---|---|
| Source basename | `dow-uap-d61-mission-report-persian-gulf-august-2020.json` |
| Source bytes | 9,694 |
| Content SHA-256 | `d81f857b10cfc708e30dd965032328c113c48159a0eccb14bde0c821aec3bd2c` |
| OCR engine | `mistral-ocr-latest` ^[inferred] (series-wide pattern) |
| Pages OCR'd | **7 substantive pages (zero header-only)** — second all-substantive multi-page Misrep in dow-uap corpus |
| Document class | **Full USMTF Misrep — multi-segment** (same as d60; second attestation, class CONFIRMED at N=2) |
| Misrep identifier | **Misrep 4685903** — second explicit Misrep ID in dow-uap corpus; distinct from d60's `4592219` (Misrep IDs are per-event, not per-unit) |
| Classification (top) | Multiple Sources (Classification Source per Admin block); Declassification Date `20450301` (1 Mar 2045 — same as d60) ^[inferred] |
| Classification authority | EO 13526 §1.4(a) per-page ^[inferred]; `(b)(6)` redaction recurring |
| Release-block classification | **Block B** (Harrison + USCENTCOM MDR `26-0019` + AARO + `01/26/26`) — 2nd attestation of Block B in corpus (with d38) |
| Release-sequence | **`001 → 007`** (per-page sequential across 7 pages) — anchors 3-digit per-document page-stamp scheme as Block B convention ^[inferred] |
| Receiving authority | **AARO** (`Approved for Release to AARO`) |
| Originating service | **US Air Force** (Service Tasked `A - AIR FORCE`; Country Tasked `US - UNITED STATES`) |
| Originating MAJCOM | **ACC** (Air Combat Command) |
| Originating COCOM | **USCENTCOM** |
| Originating Operations Center | **609th** (per Operation block); **609 CAOC** (per POC + APPROVER) |
| Originating unit (POC) | **482ATKS / 432 AEW** — 482d Attack Squadron / 432d Air Expeditionary Wing ^[inferred] (same as d60; **single internally-attested same-unit-same-tasking repeat-mission pair** with d60) |
| QC role | **PAROC / 12AF, Det 3** — explicit (vs d60's unspecified PAROC parent); same role and parent detachment as d50 |
| Witness platform | **MQ-9 Reaper** ^[inferred] (21 mission hr + AIRHANDLER SIGINT + DGS1 FMV exploitation + ANDAS4 ^[inferred] sensor + OKAS Kuwait launch) |
| Mission type | **AREC** (Armed Reconnaissance) ^[inferred] |
| Supported unit | **NAVCENT** (US Naval Forces Central Command, 5th Fleet) ^[inferred] |
| Supported operation | `OPERATION 1.4a` (portion-redacted; possibly same operation as d60 — both `1.4a` redaction-token but identity not provable from OCR) ^[ambiguous] |
| LRE (Launch and Recovery Element) attestation | **N=2 in dow-uap corpus** (recurring with d60) |
| DGS1 attribution | **N=2 in dow-uap corpus** (recurring with d60) |
| AIRHANDLER attribution | **N=2 in dow-uap corpus** (recurring with d60) |
| Series | [[entities/dow-uap-foia-release\|DoW-UAP FOIA release]] |
| Series position | **15-of-40** by ingest order (7th substantive mission report; second full Misrep) |
| Event date | **27 Aug 2020** (UAP OBS at 271527Z; mission cycle 262307Z–272012Z) — body-text date verifies filename `august-2020` |
| Event night/day | UAP at 1527Z = ~18:27–19:27 local (UTC+3/+4: late afternoon / early evening) ^[inferred] |
| Theater | **Arabian / Persian Gulf, Strait of Hormuz, Gulf of Oman** (UTM zones 39R + 40R) — 7-of-7 internal MGRS coords decode inside operational area |
| Object count | **FORMATION** (≥2 objects implied; explicit count not stated) ^[inferred] |
| Object morphology | *not reported* — second morphology-blank full-Misrep datum |
| UAP-side kinematics | **partial** — heading axis NE-to-NW reported; speed UNK; altitude UNK; duration 2 minutes explicit |
| Encounter duration | **2 minutes (1527Z–1529Z)** — first explicit bounded encounter-duration in dow-uap mission-report sub-class ^[inferred] |
| Sensor channel | `1.4a SENSOR` portion-redacted — likely MTS-B EO/IR ^[inferred] but explicit `FMV` token absent ^[ambiguous] |
| PID loss cause | **Cloud cover** — first explicit weather-induced sensor-loss attestation in dow-uap mission-report sub-class ^[inferred] |
| Iranian Air Defense GUARDCALL | **N=2 in dow-uap corpus** (recurring with d60) — class-level signature of CENTCOM-AOR MQ-9 ISR missions ^[inferred] |
| Collateral ISR observations | **3 Iranian-naval-presence observations** (1 small vessel at Greater Tunb naval port; 1 POSS IL-76 Candid at Abu Musa Island AFLD; 1 POSS Naser WAP + 2 ADMs DIW) — first explicit explicit-anti-Iran-pattern-of-life-tasking attestation in dow-uap corpus ^[inferred] |

## Structural firsts the d61 ingest anchors

d61 introduces or extends the following in the dow-uap corpus (now N=15 ingests):

1. **Confirms FULL USMTF Misrep document class at N=2.** ^closed-by-dow-uap-d61 on d60's "Validate the full-Misrep document class at N≥2" open thread. The class is now stably anchored. **Headline finding.**
2. **Confirms multi-segment Timeline structure at N=2.** ^closed-by-dow-uap-d61 on d60's "Test the multi-segment-Timeline structure at N≥2" open thread. Same Landing / GUARDCALL / OBSERVATION / Takeoff / On Station / ISR / Off Station Timeline sub-segments.
3. **Confirms Iranian Air Defense GUARDCALL recurrence at N=2.** ^closed-by-dow-uap-d61 on d60's "Test the Iranian Air Defense GUARDCALL recurrence pattern" open thread. Foreign-state direct hails are a **class-level signature** of CENTCOM-AOR ISR missions, not a d60 outlier. ^[inferred]
4. **Block B doubles to N=2** — d38 + d61 share `26-0019` + `01/26/26` + 3-digit page-stamps. d38 is no longer isolated. Block A 5-of-7 + Block B **2-of-7**. **Headline finding.**
5. **Per-document sequential page-stamping confirmed in both Blocks**: Block A 6-digit (d60: 000001→000006); Block B 3-digit (d61: 001→007). Per-Block page-stamp digit-scheme is a class-level signature. ^[inferred]
6. **First internally-attested same-unit-same-tasking repeat-mission pair**: d60 (8 Aug 2020) + d61 (26-27 Aug 2020) — same 482ATKS / 432 AEW MQ-9 ^[inferred] / same NAVCENT support / same operation 1.4a / same OKAS launch / 19 days apart. **Headline finding.**
7. **PAROC role explicit attestation at 12 AF / DET 3** — d61 resolves d50's PAROC-vs-PAROL ambiguity in favor of PAROC (d50 spelled `PAROL` per OCR; d61's clean `PAROC` in the same 12 AF / DET 3 cell strengthens the PAROC reading). **Partial closure** of d50's "Resolve PAROC vs PAROL" open thread at the 12 AF / DET 3 attestation. ^[inferred]
8. **First explicit `FORMATION OF UNK FLYING OBJECTS` activity descriptor** in dow-uap mission-report sub-class — distinct from d60's `TRANSITTING`.
9. **First explicit bounded-encounter-duration datum** in dow-uap mission-report sub-class — `APPROXIMATELY 2 MINUTES` (1527Z–1529Z).
10. **First explicit weather-induced sensor-loss attestation** in dow-uap mission-report sub-class — `LIGHT CLOUD COVERAGE PREVENTED CONTINUOUS TRACKING`.
11. **First explicit `(S/REL)` portion-marking on a UAP datum** in the full-Misrep sub-class — sixth distinct portion-marking state in the corpus.
12. **First explicit explicit-anti-Iran-pattern-of-life-tasking attestation** — GENTEXT/ISR explicitly states `TO CHARACTERIZE IRIN/IRGCN VESSELS, UAS ACTIVITY, ACTIVITY OUTSIDE OF PORTS, AND TO ESTABLISH PATTERN OF LIFE`. ^[inferred]
13. **First explicit Iranian-naval-activity collateral observations** in dow-uap corpus — Greater Tunb naval port + Abu Musa Island AFLD (POSS IL-76 Candid) + Naser-class missile patrol boat DIW.
14. **First explicit Greater Tunb Island + Abu Musa Island geographic anchors** in dow-uap corpus.
15. **First explicit IL-76 Candid + Naser WAP foreign-aircraft / foreign-naval-platform identification** in dow-uap corpus.
16. **Mission-report UAP-datum counter increment to N=7 records / 8 datums** ^[inferred] — extends from d60's N=6 / 7.
17. **Anchors ninth distinct brief-observation sub-class** on [[concepts/uap-aircraft-engagement|concepts/uap-aircraft-engagement]] — *formation-track + bounded-duration + heading-axis-only + sensor-PID-loss-on-weather*. ^[inferred]
18. **N=2 filename-axis verification at internal-coord level** for `*-persian-gulf*`-class filename. Combined d60 + d61 = 12-of-12 internal MGRS coords decode inside body-text-declared operational area. ^[inferred]
19. **GUARDCALL temporal-sequencing variance at N=2** — d60 GUARDCALL post-UAP (1250Z after 0726Z); d61 GUARDCALL pre-UAP (0532Z before 1527Z). **No causal link between GUARDCALL and UAP events** ^[inferred]; they are independent operational phenomena within the same mission profile.
20. **No new multi-service originating-anchor count** — 482ATKS already attested at d60; d61 does not extend the unit-anchor list (count stays at 8 = 6 USAF + 2 Navy).
21. **First internally-attested same-MGRS-100-km-square aircraft-and-UAP geometry** in dow-uap corpus — d61 aircraft (39RVM38) and UAP (39RVM88) are in the same VM square (~50–80 km separation). d60's three-square spread (WK / WL / VL) was looser. ^[inferred]
22. **Mission-cycle DTG anchor count rises to 14 at N=2** (d61) vs d60's 8 — d61 includes 4 collateral-ISR observations. **Operational-detail layer richer at d61.** ^[inferred]
23. **First explicit Russian-design foreign-aircraft observation** in dow-uap corpus (POSS IL-76 Candid at Abu Musa Island).

## OCR ambiguities

- **Page 6 banner `Declassified on: 22 January 2020`** — almost certainly an OCR digit-swap for `2025`. All other 6 pages render `2025` consistently, and `2020` is incompatible with the originating-event date (declassification cannot precede classification). ^[inferred] ^[ambiguous]
- **`FORMATION OF UNK FLYING OBJECTS`** (page 5 OBS Activity Description) — clean OCR; no ambiguity. The activity descriptor is novel in the dow-uap mission-report sub-class.
- **`Method of Observation: 1.4a SENSOR`** (page 5 OBS block) — portion-redacted sensor designator. Likely MTS-B EO/IR ^[inferred] consistent with the MQ-9 platform attribution, but the explicit `FMV` token from d60 is absent. ^[ambiguous] Cannot confirm same sensor channel as d60.
- **GENTEXT/ISR narrative event-order scramble** — events at 0611Z + 0700Z appear AFTER 1742Z in the OCR-rendered narrative ordering. ^[ambiguous] Almost certainly an OCR field-order scramble or in-document narrative reflow, not a real chronological anomaly. ^[inferred] The timestamps themselves remain reliable.
- **`Naser WAP`** (page 4 GENTEXT/ISR) — Naser-class missile patrol boat ^[inferred]; `WAP` likely Weapon-Armed Patrol or similar acronym for the Iranian IRGCN/IRIN fast-attack-craft class. ^[ambiguous] OCR token may also be a unit designator (e.g. specific hull number) rather than class descriptor.
- **`POSS IL-76 CANDID`** (page 4 GENTEXT/ISR) — `POSS` is the Navy `POSSIBLE` hedge marker (anchored at d4/d5/d56 in the corpus); `IL-76 Candid` is the Ilyushin Il-76 heavy-lift transport NATO codename. Identification is hedged.
- **`1.4a SENSOR`** (page 5 OBS Method of Observation) — portion-redacted sensor designator under EO 13526 §1.4(a). Cannot decode the specific sensor system from OCR alone.
- **`OKAS`** (page 0 Narrative + page 3 Last Land Location + page 3 Takeoff) — ICAO 4-letter aerodrome identifier. **OKAS = Ali Al Salem AB, Kuwait** ^[inferred] (consistent with d60 attestation). ^[ambiguous]
- **`(b)(6)` cleanliness** — the redaction format on d61 is **clean `(b)(6)` throughout** with two `3.5c, (b)(6)` and one `3,5c. (b)(6)` variant (page 0 only — comma-vs-period OCR variance). The d54/d8 OCR-corruption pattern (`14(6)` / `1.4(6)`) does **not** recur on d61. ^[extracted]
- **Declassification Date `20450301`** (page 0 CLASSIFICATION block) — interpreted as `2045-03-01` ^[inferred]. Same date as d60's `20450301` — anchors a class-level 1-Mar-2045 declassification date for 482ATKS / 432 AEW MQ-9 Misreps in this window. ^[inferred]
- **Operations Center `609 CAOC` (POC + APPROVER) vs `609th` (Operation Admin)** — same dual rendering as d60. ^[inferred] No 603 AOC reference at d61 (vs d60's three-AOC-token mix); d61 is internally consistent at 609 CAOC / 609th.
- **`AT 0700Z`** appearing AFTER `AT 1742Z` in GENTEXT/ISR (page 4) — narrative event-order anomaly. ^[ambiguous] OCR field-order scramble most probable. ^[inferred]
- **MSGID Submit Date blank** — no submission timestamp preserved at d61 (same as d60). ^[ambiguous]

## Open threads

- **Validate full-Misrep document class at N≥3** — d60 + d61 now anchor the class at N=2. Does the class persist beyond same-unit (482ATKS) attestations? A Navy-unit full Misrep (e.g. an F/A-18 or P-8A Misrep) would discriminate between document-class-driven and originating-service-driven readings of the `GENTEXT/OBSERVATION` segment-name distinction.
- **Test for d62+ as another 482ATKS / 432 AEW August-2020 mission** — d60 + d61 are 19 days apart in the same Arabian-Gulf NAVCENT-support tasking window. Does the queue contain d62 / d63 / etc. with similar 482ATKS attestation? If so, the same-unit cluster extends. If not, d60 + d61 form a closed pair within Aug 2020.
- **Resolve `Operation 1.4a` portion-redaction at d60 + d61** — both Misreps name the supported operation as `1.4a`. Are these the **same operation** (suggesting both missions are sorties under one named USCENTCOM/NAVCENT operation) or **different operations sharing a redaction token**? The `1.4a` redaction may be a position-marker rather than a unique-name marker. ^[ambiguous]
- **Test the same-Block-same-unit pattern** — Block B contains d38 (range-fouler) + d61 (full Misrep). Does the same release-batch tend to hold same-AOR or same-unit artifacts? d38 (Persian Gulf coast, no unit attribution preserved) and d61 (Arabian Gulf, 482ATKS) are both CENTCOM-AOR. The Block-B batch may be a CENTCOM-AOR-specific release sub-batch. ^[inferred] To be tested at N≥3 Block-B artifacts.
- **Decode `Naser WAP`** — Naser-class missile patrol boat identification + WAP acronym expansion. Open-source IRGCN/IRIN order-of-battle references would close.
- **Verify Greater Tunb + Abu Musa Iranian-island context** — these are disputed Iranian-occupied islands in the Strait of Hormuz / eastern Persian Gulf. Open-source confirmation of naval-port + AFLD presence at these sites would firm the geographic decoding.
- **Resolve `1.4a SENSOR` vs explicit `FMV`** — d60's OBS Method of Observation is explicit `FMV`; d61's is `1.4a SENSOR` portion-redacted. Is this an OCR difference, a per-document redaction-policy difference, or evidence that d60 + d61 used different sensor channels?
- **Test the ninth brief-observation sub-class at N≥2** — d61 anchors *formation-track + bounded-duration + heading-axis-only + sensor-PID-loss-on-weather* as a distinct sub-class. Future ingests carrying similar formation-track + weather-induced-PID-loss signatures would firm the class.
- **Test the explicit-anti-Iran-pattern-of-life-tasking framing recurrence** — d61's GENTEXT/ISR is the first explicit anti-Iran ISR tasking attestation. Does the rest of the corpus carry similarly explicit anti-Iran tasking, or is d61's narrative detail an outlier? ^[inferred]
- **Decode Misrep ID numbering pattern** — d60 = `4592219`; d61 = `4685903`. Both 7-digit numbers, both rising. Is this a global USCENTCOM MISREP counter (every USCENTCOM MISREP gets a sequential ID across all classifications) or an AOR/unit-specific counter? The gap (4685903 - 4592219 = 93,684 IDs across 19 days) suggests a high-volume counter ^[inferred].
- **Test the page-6 `Declassified on: 22 January 2020` anomaly recurrence** — does any other dow-uap multi-page Misrep carry a digit-swapped declassification banner on a single page? If so, it's a class-level OCR or release-stamp anomaly; if isolated, it's a d61-specific OCR error.
- **Test the `(S/REL)` portion-marking variant** — d61 carries `(S/REL)` on the UAP GENTEXT (the only one in the corpus to date). Is this an abbreviated form of `(S/REL FVEY)` (d4/d5) or a distinct release-control variant?

## See also

- [[entities/dow-uap-foia-release]] — Series-level anchor (d61 is the 15-of-40 ingest, 7th substantive mission-record artifact, second FULL USMTF Misrep); confirms fourth top-level mission-report sub-class at N=2
- [[references/dow-uap-pr20-prepublication-clearance-2026-03]] — Series prepublication-clearance cover stamp (10 Mar 2026)
- [[references/dow-uap-d60-mission-persian-gulf-2020-08-08]] — **First FULL USMTF Misrep (Misrep 4592219, 8 Aug 2020); same 482ATKS / 432 AEW MQ-9 ^[inferred] / same NAVCENT support / same operation 1.4a / 19-day same-unit repeat-mission pair**; d61 closes 3 of d60's open threads
- [[references/dow-uap-d38-range-fouler-middle-east-may-2020]] — First Block B artifact (range-fouler, 14 May 2020, Persian Gulf coast); d61 doubles Block B to N=2; d38 no longer isolated
- [[references/dow-uap-d56-range-fouler-arabian-sea-august-2020]] — Range-fouler 24 Aug 2020 North Arabian Sea HSM-73 MH-60R; **3 days before d61's UAP event** — closest temporal sister artifact in dow-uap corpus
- [[references/dow-uap-d44-range-fouler-arabian-sea-october-2020]] — Range-fouler 15 Oct 2020 Gulf of Aden 172 ATKS MQ-9; same MQ-9 platform-class as d61 / d60 but different document class
- [[references/dow-uap-d58-range-fouler-debrief-2020-10]] — Range-fouler 27 Oct 2020 77 EFS CENTCOM
- [[references/dow-uap-d4-mission-arabian-gulf-2020]] — Single-segment GENTEXT/UAP extract — kinematic-anomaly sub-class
- [[references/dow-uap-d5-mission-arabian-gulf-2020]] — Two-sighting GENTEXT/UAP extract
- [[references/dow-uap-d7-mission-arabian-gulf-2020]] — Form-driven GENTEXT/UAP extract with TFLIR fire-control engagement-pipeline + 48FW USAF cross-reference
- [[references/dow-uap-d54-mission-mediterranean-sea]] — Triangular-and-metallic GENTEXT/UAP extract over Aegean Sea
- [[references/dow-uap-d8-mission-djibouti-2025]] — Round-white-hot GENTEXT/UAP extract; FIN+SWE+FVEY+NATO release authorization
- [[references/dow-uap-d55-mission-syria-2016-11-18]] — CTG-narrative mission report (P-8A / TF 67.1, 18 Nov 2016)
- [[references/dow-uap-d52-email-na-2024]] — Email-correspondence class (15 AF / DET 1 PAROC IDAT)
- [[references/dow-uap-d50-email-indopacom-2025-04]] — Email-correspondence class (12 AF / DET 3 PAROC/PAROL); d61 explicitly attests PAROC at 12 AF / DET 3
- [[concepts/uap-aircraft-engagement]] — Behavioral framing; d61 increments mission-report UAP-datum counter to N=7 / 8 datums; anchors 9th brief-observation sub-class (formation-track + bounded-duration + heading-axis-only + sensor-PID-loss-on-weather)
- [[concepts/orb-phenomenon]] — Adjacent; d61 is morphology-blank but formation-track is suggestive
- [[concepts/range-fouler]] — Adjacent; d61 is not a range-fouler, but same-Block sister artifact d38 is
- [[entities/aaro]] — d61 `Approved for Release to AARO` stamp recurrence (7th in corpus); firms AARO as dow-uap receiving authority
- [[projects/uap/uap]]
