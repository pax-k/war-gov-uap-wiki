---
title: "DoW-UAP-D62 — Full Misrep 4782130 (482ATKS / 432 AEW MQ-9, 15-16 Sep 2020, Strait of Hormuz)"
category: references
tags: [uap, primary-source, declassified, usaf, sighting]
aliases: [DoW-UAP-D62, dow-uap-d62]
sources: [sources/dow-uap-d62-mission-report-strait-of-hormuz-september-2020.json]
summary: 9-page Mistral-OCR'd Misrep 4782130 — third FULL USMTF Misrep in dow-uap corpus; 15-16 Sep 2020 NAVCENT support over Arabian Gulf / Strait of Hormuz / Gulf of Oman by same 482ATKS / 432 AEW MQ-9 as d60+d61 (20 days after d61); single UAP datum at 1732Z via FMV — sub-class 8 confirms at N=2; 3 Iranian GUARDCALLs (2 DIRECTIVE + 1 PROFESSIONAL); first EMI events in Misrep schema (2 lost-link MEDIUM-impact events).
provenance:
  extracted: 0.62
  inferred: 0.33
  ambiguous: 0.05
base_confidence: 0.80
lifecycle: draft
lifecycle_changed: 2026-05-11
created: 2026-05-11T18:00:00Z
updated: 2026-05-11T18:00:00Z
event_date: 2020-09-16
project: uap
---

# DoW-UAP-D62 — Full Misrep 4782130 (482ATKS / 432 AEW MQ-9, 15-16 Sep 2020, Strait of Hormuz)

A **9-page Mistral-OCR'd artifact** (`sources/dow-uap-d62-mission-report-strait-of-hormuz-september-2020.json`, 10,348 bytes; SHA-256 `27e87e30164213033730a9100e6da9ce6927a34a87de53b2d99ce3412bbc034a`) — the **sixteenth artifact** in the [[entities/dow-uap-foia-release|DoW-UAP FOIA release series]] (16-of-40) and the **third FULL USMTF Misrep ingest** in the corpus. d62 is the structural replicate of [[references/dow-uap-d60-mission-persian-gulf-2020-08-08|d60]] + [[references/dow-uap-d61-mission-persian-gulf-2020-08-27|d61]] at the document-class level: all 9 pages substantive (zero header-only padding), complete USMTF segment set, and the same 482ATKS / 432 AEW MQ-9 ^[inferred] flown for the same NAVCENT-support tasking over the same Arabian Gulf / Strait of Hormuz / Gulf of Oman corridor — now **20 days after d61** and **38 days after d60**. Mission cycle 15-16 Sep 2020 (UAP datum on 16 Sep at 1732Z).

The d62 ingest delivers **four corpus-level headline findings** simultaneously, in priority order:

1. **Same-unit-same-tasking cluster extends to N=3 triplet** — d60 (8 Aug) + d61 (26-27 Aug) + d62 (15-16 Sep 2020) form the corpus's first **3-document same-unit-same-tasking repeat-mission cluster**: same 482ATKS POC unit / 432 AEW wing / 609 CAOC APPROVER / NAVCENT supported command / `Operation 1.4a` (portion-redacted) / Arabian Gulf-Hormuz-Oman theater / OKAS Kuwait launch base / AREC mission type / ANDAS4 TGT pod / AH_GMESH avionics ^[inferred] across all three missions. The d61 reading "first same-unit-same-tasking repeat-mission pair" is **extended to triplet** at N=3 within 38 days. **The 482ATKS / 432 AEW MQ-9 deployment ran sustained Aug-Sep 2020 NAVCENT-support tasking, with three of those missions producing UAP observations.** ^[inferred] **Headline finding.** Closes [[references/dow-uap-d60-mission-persian-gulf-2020-08-08|d60]]'s open thread "Test for d62+ as another 482ATKS Aug-2020 mission" — extends the cluster from Aug-only to **Aug-Sep 2020 (38-day span)**.
2. **NEW STRUCTURAL ELEMENT — EMI events as Misrep schema axis** — d62 carries **two structured EMI (Electro-Magnetic Interference) segments** documenting **MEDIUM mission-impact lost-link events** at 1248Z-1259Z (11 min, JSIR ID330412, flight path deviation) and 1414Z-1441Z (27 min, JSIR ID330414, flight path deviation). Both incidents portion-redacted as `Type of EMI: UNKNOWN`, `Affected System: 1.4g`, `Frequency Affected: 1.4g` — likely Iranian electronic-warfare emissions ^[inferred] given the Iranian-airspace-transit context, but the OCR explicitly classifies the type as UNKNOWN. **First non-trivial mission-impact attestation in the 482ATKS cluster**; d60 + d61 both carry `NO IMPACT TO MISSION` / `NO MISSION IMPACTS` clauses, d62 carries `MEDIUM IMPACT TO THE MISSION` on both events. **First EMI-event attestation in the dow-uap mission-report sub-class.** ^[inferred] **Headline finding** — anchors EMI as a previously-unobserved canonical USMTF segment in the schema, with structured fields (DTG / Aircraft Callsign / Type / Duration / Location / Heading / Altitude / Airspeed / Mission Changed / Impact / System / Frequency / Mission Impact) + paired GENTEXT/EMI narrative + Joint Spectrum Interference Resolution (JSIR) ID anchors.
3. **Iranian Air Defense GUARDCALL — 3 per mission + DIRECTIVE tone introduced** — d62 carries **3 Iranian Air Defense GUARDCALL events** (vs d60 1, d61 1): 0408Z (DIRECTIVE tone), 0421Z (DIRECTIVE tone), 1141Z (PROFESSIONAL tone). **The first two hails 13 minutes apart at the same MGRS `40RCP76` and same FL180** constitute the corpus's first **same-location-multi-hail cluster**. **`DIRECTIVE` GUARDCALL tone is a structural first** — d60+d61 both `PROFESSIONAL`; d62's first two hails escalate to DIRECTIVE before reverting to PROFESSIONAL on the third hail (different altitude FL040). **Per-mission GUARDCALL count distribution is now 1+1+3** at N=3 — d62 anchors the upper tail. ^[inferred] **GUARDCALL recurrence anchored at N=3 ^closed-by-dow-uap-d62 on d60's "Test the Iranian Air Defense GUARDCALL recurrence pattern" thread (now class-level signature of CENTCOM-AOR MQ-9 ISR missions, with tone-and-count variance).** **Third headline finding** behind same-unit-cluster + EMI.
4. **Sub-class 8 confirms at N=2 — d60's bare-FMV signature is the dominant brief-observation mode, not d61's formation-track outlier** — d62's UAP datum is **explicit FMV method + single object (`A UAP`) + no morphology + no kinematics + no duration + no PID-loss + same MGRS coord as aircraft**, structurally **matching [[references/dow-uap-d60-mission-persian-gulf-2020-08-08|d60]]'s sub-class 8 (FMV-observation + zero-mission-impact-on-UAP + kinematics-blank + morphology-blank)** rather than [[references/dow-uap-d61-mission-persian-gulf-2020-08-27|d61]]'s sub-class 9 (formation-track + bounded-duration + heading-axis-only + sensor-PID-loss-on-weather). **Sub-class 8 firms to N=2 dominant at d60+d62; sub-class 9 isolated at N=1 d61.** The d61 ingest's reading of "anchors ninth distinct brief-observation sub-class" was correct as an order-of-discovery claim, but at N=3 of full-Misrep UAP datums **d61's formation signature is the outlier within the same-unit cluster, not d60's bare-FMV signature**. ^[inferred] Same-unit cluster predominantly produces bare-FMV brief observations; the formation-track datum is a single 2-minute deviation.

## What the source actually contains

The OCR pulls **9 pages**, each `dpi: 93`, all carrying explicit per-page declassification banners and **all substantive** (zero header-only padding pages — matches d60+d61's structural pattern). Every page also carries the explicit `(b)(6)` / `3.5c (b)(6)` redaction block + `USCENTCOM MDR 26-0019` + `Approved for Release to AARO` + `01/26/26 00N` (where `N` is the page index 1–9).

**Page-top metadata block — OCR digit-swap alternation pattern NEW at d62:**

The page-top banner alternates between two readings across the 9 pages:

```
Declassified by MG Richard A. Harrison
USCENTCOM Chief of Staff
Declassified on: 22 January [YYYY]
```

| Page | YYYY rendered |
|---|---|
| 0 | **2020** |
| 1 | 2020 |
| 2 | 2020 |
| 3 | **2025** |
| 4 | 2020 |
| 5 | **2025** |
| 6 | 2020 |
| 7 | **2025** |
| 8 | **2025** |

Roughly 5-of-9 pages render `2020` and 4-of-9 render `2025`. ^[ambiguous] This is **distinct from d61's isolated single-page swap** (page 6 only out of 7 pages reading `2020`); d62's pattern is closer to 50/50 alternation. The `2025` reading is almost certainly correct (declassification cannot precede classification — the originating event is 15-16 Sep 2020); the `2020` digit-swap is the recurring OCR failure. ^[inferred] **At N=3 full-Misrep ingests, the page-banner OCR digit-swap is now anchored as a class-level OCR signature** — d60 was clean (all pages `20 March 2026`), d61 had one swapped page, d62 has near-50% swapped pages. The swap rate is per-document variable but the swap class is recurrent. ^[inferred]

**Page-bottom release block (recurring on every page, with N = page index):**

```
3.5c. (b)(6)
USCENTCOM MDR 26-0019
Approved for Release to AARO
01/26/26 00N
```

The release-sequence number runs **`001` (page 0) → `009` (page 8)** — 3-digit Block-B page-stamps across 9 pages. **At N=3 Block-B testable artifacts (d38 single-page `001`; d61 multi-page `001→007`; d62 multi-page `001→009`), Block B's 3-digit sequential page-stamp scheme is anchored decisively.** ^[inferred] See *Release framework — Block B triples to 3-of-8* below.

**Substantive content by page:**

| Page | Substantive segments |
|---|---|
| 0 | Document header `# Misrep 4782130` + `## Narrative` (free-text BLUF-equivalent) + `## Admin` (CLASSIFICATION + OPERATION + MSGID) |
| 1 | MSNID + `# Poc` (POC + QC + APPROVER blocks) |
| 2 | INGEST + `## ACEQUIP` (full aircraft-equipment block) |
| 3 | ACEQUIP continuation + `## Timeline` (Landing + Takeoff + On Station + ISR start) |
| 4 | ISR continuation + `## GENTEXT/ISR` + ISR ASSET UTILIZATION + WEATHER + EFFECTIVENESS + Off Station |
| 5 | Off Station continuation + `## GUARDCALL` (1st) + `GENTEXT/GUARDCALL` + `## GUARDCALL` (2nd) + `GENTEXT/GUARDCALL` + `## GUARDCALL` (3rd start) |
| 6 | GUARDCALL (3rd continuation) + `GENTEXT/GUARDCALL` + `## EMI` (1st) + `GENTEXT/EMI` + `## EMI` (2nd start) |
| 7 | EMI (2nd continuation) + `GENTEXT/EMI` + `## OBSERVATION` (the UAP datum) + `GENTEXT/OBSERVATION` + `WEATHER` start |
| 8 | WEATHER end |

The **substantive UAP datum is in `GENTEXT/OBSERVATION` on page 7**, matching d60 + d61's segment placement. `GENTEXT/OBSERVATION` is now anchored at **N=3** as the canonical USMTF segment for UAP datums within the full-Misrep sub-class. ^[inferred]

## The UAP datum — sub-class 8 (bare FMV-observation) confirms at N=2 d60+d62

The single UAP-event appears in the `OBSERVATION` structured block (page 7) and the `GENTEXT/OBSERVATION` narrative segment (page 7):

| Field | Value | Notes |
|---|---|---|
| Observation DTG | **161732:00ZSEP20** | **16 Sep 2020 at 1732Z** — third explicit calendar-date + UTC-time anchor on a UAP datum in the full-Misrep sub-class; **20 days after d61** (271527Z AUG 20) and **38 days after d60** (080726Z AUG 20). |
| Aircraft Callsign | **1,4a** | Portion-redacted under EO 13526 §1.4(a) — same redaction pattern as d60/d61. |
| Aircraft Location | **39RVM51 1,4a70 1,4a** | MGRS UTM zone 39R / square VM — Persian Gulf interior. ^[inferred] |
| Aircraft Heading | (blank — `-`) | Witness-aircraft heading not preserved on the OBS line. |
| Aircraft Altitude | **FL180** | 18,000 ft pressure altitude. **First explicit witness-aircraft-altitude attestation in the d60+d61+d62 cluster at the OBS event** — d60 + d61 both left the OBS-line altitude blank. |
| Aircraft Airspeed | **90 KIAS** | 90 Knots Indicated Airspeed. **First explicit witness-aircraft-airspeed attestation in the d60+d61+d62 cluster at the OBS event** — d60 + d61 both left the OBS-line airspeed blank. |
| Relative Bearing / Range / Killbox | (all blank — `-`) | UAP-relative geometry not preserved. |
| Observed Activity Location | **39RVM51 1,4a70 1,4a** | UAP position MGRS — **SAME `39RVM51` AS AIRCRAFT POSITION**. Tightest co-located aircraft-and-UAP geometry in the dow-uap corpus to date — same 10-km MGRS sub-square, vs d61's same 100-km square at ~50-80 km separation and d60's three-square spread. ^[inferred] **First internally-attested same-10-km-MGRS-square aircraft-and-UAP geometry in the corpus.** |
| Observed Activity Description | **UAP** | Bare `UAP` descriptor (vs d60's `TRANSITTING` and d61's `FORMATION OF UNK FLYING OBJECTS`). No morphology, no kinematics, no action verb. Singular indefinite article — single object. ^[inferred] |
| Method of Observation | **FMV** | **Full Motion Video — explicit FMV token, matching d60.** Distinct from d61's portion-redacted `1.4a SENSOR`. Sub-class 8 sensor channel confirmed at N=2 (d60 + d62). ^[inferred] |
| GENTEXT/OBSERVATION | `AT 1732Z, 1,4a OBSERVED A UAP IVO 39RVM51 1,4a70 1,4a` | Single-line bare-observation datum — **structurally identical to d60's `AT 0726Z, 1.4a OBSERVED 1X UAP IVO 39RWL08 1.4a 2 1.4a NO IMPACT TO MISSION`**. No duration, no kinematics, no morphology, no PID-loss, no engagement. The `NO IMPACT TO MISSION` clause from d60 is **absent** at d62 — but d62 carries explicit **MEDIUM-impact EMI events earlier in the mission** (1248Z + 1414Z), so the mission-impact clauses are reserved for those EMI events not the UAP. ^[inferred] |

**Single object, single observation, no UAP-side kinematics, no morphology, no duration, no engagement** — structurally **identical to d60's sub-class 8 signature** (FMV-observation + kinematics-blank + morphology-blank). The signature is **a brief FMV-observed transit at the witness aircraft's own coordinates**. ^[extracted] No interaction posture; no closure attempt; no PID-loss event; no formation. The unique d62 wrinkle is the **same-MGRS aircraft-and-UAP geometry** — the witness aircraft and the UAP are recorded at the **same 10-km MGRS square**, which means the UAP was observed essentially co-located with the MQ-9 platform at the moment of FMV capture.

**Sub-class assignment within brief-observation** — d62 matches the [[references/dow-uap-d60-mission-persian-gulf-2020-08-08|d60]] sub-class 8 (FMV-observation + zero-mission-impact-on-UAP + kinematics-blank + morphology-blank). **Sub-class 8 firms to N=2 (d60+d62); sub-class 9 (d61 formation-track) isolated at N=1.** ^[inferred]

The d61 ingest's "anchors ninth distinct brief-observation sub-class" reading is **correct as an order-of-discovery claim** but **misframed at N=3**: at N=3 same-unit-same-tasking full-Misrep UAP datums, the bare-FMV signature (d60+d62) is the **dominant brief-observation mode** for the 482ATKS cluster, and the formation-track signature (d61) is **the within-cluster outlier**. ^[inferred] The 9-sub-class taxonomy on [[concepts/uap-aircraft-engagement|concepts/uap-aircraft-engagement]] remains correct at the type-level; only the **relative anchor weights within the dow-uap full-Misrep sub-class** shift — sub-class 8 (d60+d62) and sub-class 9 (d61 alone) are no longer co-equal N=1 entries, they are N=2 vs N=1 within the same-unit cluster.

**Mission-report UAP-datum counter increments N=7 → N=8 records / 8 → 9 datums** at the dow-uap level. ^[inferred] The 9th datum is single-object (d62 single UAP).

## Mission-cycle timeline — sustained anti-Iran ISR with EMI interruptions

The d62 Misrep Narrative + Timeline + GENTEXT/ISR + GUARDCALL + EMI + OBSERVATION + Off Station segments reconstruct the **complete ~20h 56min mission cycle**:

| Time (Z) | Event | Source |
|---|---|---|
| **152302:00Z** | Takeoff from OKAS (Ali Al Salem AB, Kuwait ^[inferred]) — **15 Sep 2020** | Takeoff block + Narrative |
| **152313:00Z** | Handed over from LRE | Narrative |
| **152346:00Z** | Started SIGINT collection via AIRHANDLER ^[inferred] | Narrative |
| **160318:00Z** | Arrived on station ISO NAVCENT, Operation 1.4a (IVO Arabian Gulf, Strait of Hormuz, Gulf of Oman) — **16 Sep 2020** | On Station + ISR blocks + Narrative |
| **160408:00Z** | **GUARDCALL #1 — Iranian Air Defense — DIRECTIVE tone — MGRS 40RCP76, FL180, HDG 360T** | GUARDCALL block #1 |
| **160421:00Z** | **GUARDCALL #2 — Iranian Air Defense — DIRECTIVE tone — MGRS 40RCP76, FL180, HDG 010M** (13 min after GUARDCALL #1, same MGRS sub-square) | GUARDCALL block #2 |
| **160930:00Z** | 1X IR-SA-5 launcher observed IVO 40RCP02 on Abu Musa Island | GENTEXT/ISR |
| **161141:00Z** | **GUARDCALL #3 — Iranian Air Defense — PROFESSIONAL tone — MGRS 40RCP2, FL040, HDG 277T** (~7 hr after #2; different MGRS sub-square + lower altitude + tone shift back to PROFESSIONAL) | GUARDCALL block #3 |
| **161248:00Z** | **EMI EVENT #1 START — UNKNOWN type, lost link — Aircraft Location 39RXK0, FL180, 89 KIAS — MEDIUM mission impact + Flight Path Deviation — JSIR ID330412** | EMI block #1 |
| **161259:00Z** | EMI EVENT #1 END (11 min duration; link regained) | EMI block #1 |
| **161321:00Z** | 2X POSS Houdong-class WPTG (Iranian fast-attack craft) observed docked pierside IVO 39RXL60 | GENTEXT/ISR |
| **161414:00Z** | **EMI EVENT #2 START — UNKNOWN type, lost link — Aircraft Location 39RVM92, FL180, 120 KIAS — MEDIUM mission impact + Flight Path Deviation — JSIR ID330414** | EMI block #2 |
| **161441:16Z** | EMI EVENT #2 END (27 min 16 sec duration; link regained) | EMI block #2 |
| **161732:00Z** | **UAP OBSERVATION — see § The UAP datum above** — single A UAP via FMV at 39RVM51 (~3 hr after EMI #2 end; ~6 hr 5 min before mission end) | GENTEXT/OBSERVATION |
| **161829:00Z** | Cleared off tasking; RTB (only ~57 min after UAP observation) | ISR + Narrative |
| **161923:00Z** | Handed back to LRE | Narrative |
| **161958:00Z** | Landed at OKAS | Landing block + Narrative |
| **162008:00Z** | Last engine shutdown | Landing block |
| (totals) | **20h 56min mission time / 20.9 mission hr / 15.2 IMINT hr / 1 IMINT tasking / 19.3 SIGINT hr / 1 SIGINT tasking / 2 total taskings** | Narrative |

**Notable narrative anomaly**: the GENTEXT/ISR segment renders these events in chronological order at d62 (unlike d61's event-order scramble) — `0318Z → 0930Z → 1321Z → 0408Z → 0421Z → 1141Z → 1732Z → 1829Z`, which is *not strictly chronological* but the major collateral-ISR observations are placed in order around the GUARDCALL group. ^[inferred] No major OCR field-order scramble at d62.

**Mission-cycle DTG anchor count at N=3 full-Misrep**: d60 carried 8 distinct anchors; d61 carried 14 anchors (+4 collateral-ISR + GUARDCALL); **d62 carries 18 distinct DTG anchors** (+2 EMI events + 3 GUARDCALLs + 2 collateral-ISR + UAP + mission-cycle bookends). **d62 is the operationally-most-detail-rich record in the dow-uap full-Misrep sub-class.** ^[inferred]

## EMI events — first non-trivial mission impact in the 482ATKS cluster

Pages 6-7 carry **two structured EMI segments** + paired **GENTEXT/EMI** narratives — both events flagged as **MEDIUM impact** with **flight path deviation** mission-changed flags:

| Field | EMI #1 | EMI #2 | Notes |
|---|---|---|---|
| EMI Start DTG | 161248:00ZSEP20 | 161414:00ZSEP20 | ~85 min apart |
| EMI End DTG | 161259:00ZSEP20 | 161441:16ZSEP20 | |
| Aircraft Callsign | 1.4a | 1,4a | |
| Type of EMI | **UNKNOWN** | **UNKNOWN** | Both events explicitly unknown-type ^[inferred] |
| EMI Duration | **11 minutes** | **27 minutes** | Total link-loss time = 38 min across both events |
| Aircraft Location | 39RXK0 1.4a 5 1.4a | 39RVM92 1,4a89 1,4a | UTM 39R; sub-squares XK and VM (~100-km apart on the grid ^[inferred]) |
| Aircraft Heading | 290 T | 264 T | Westerly both events |
| Aircraft Altitude | FL180 | FL180 | Same cruise altitude both events |
| Aircraft Airspeed | 89 KIAS | 120 KIAS | Slightly different airspeed |
| Mission Changed | **Flight Path Deviation** | **Flight Path Deviation** | Both forced flight-path changes |
| EMI Impact to System | Complete | Complete | Total system effect both events |
| EMI Location | (same as aircraft) | (same as aircraft) | Source not separately located |
| Affected System | **1.4g** (portion-redacted) | **1.4g** (portion-redacted) | EO 13526 §1.4(g) classification-category marking — *vulnerabilities or capabilities of systems, installations, infrastructures, projects, plans, or protection services relating to the national security* ^[inferred] |
| Frequency Affected | **1.4g** (portion-redacted) | **1.4g** (portion-redacted) | Specific frequency classified |
| Mission Impact | **MEDIUM** | **MEDIUM** | First MEDIUM mission-impact attestation in the 482ATKS cluster ^[inferred] |
| GENTEXT/EMI | `AT 1248Z, 1.4a EXPERIENCED LOST LINK TO POSSIBLE 1.4g 1.4a REGAINED LINK AT 1259Z. THIS RESULTED IN A MEDIUM IMPACT TO THE MISSION` | `AT 1414Z, 1,4a EXPERIENCED LOST LINK TO POSSIBLE 1,4g 1,4a / REGAINED 1441Z. THIS RESULTED IN A MEDIUM IMPACT TO THE MISSION` | "LOST LINK TO POSSIBLE [redacted]" — the link was to a portion-redacted system or frequency. ^[ambiguous] |
| JSIR ID | **JSIR ID330412** | **JSIR ID330414** | Joint Spectrum Interference Resolution case IDs — the DoD-wide EMI-event tracking system. Sequential IDs (330412 + 330414 = 2 apart in the global JSIR counter) suggest one intervening event globally between d62's two EMI cases. ^[inferred] |

**Operational significance**: the EMI events are the **first non-trivial mission-impact attestations in the dow-uap mission-report sub-class.** ^[inferred] Both events forced **flight path deviations** — the MQ-9 had to modify its routing in response to the link losses. The portion-redacted `1.4g` system + frequency designations indicate the OCR-rendered field values are classified at the EO 13526 §1.4(g) level (vulnerabilities/capabilities of national-security systems), not the §1.4(a) (military plans/weapons-systems/operations) used elsewhere in the document. ^[inferred] **The §1.4(g) classification of the EMI-affected system is the first §1.4(g)-marked field in the dow-uap corpus** — prior dow-uap redactions have been §1.4(a). ^[inferred]

**Iranian-EW-emission hypothesis** ^[ambiguous]: the EMI events occurred during transit through Iranian-airspace-margin regions (UTM 39R/XK and 39R/VM both inside the operational area where Iranian Air Defense was simultaneously hailing the aircraft on Guard freq). Iranian electronic-warfare emissions are a candidate explanation for the lost-link events, consistent with the d62 mission's anti-Iran ISR tasking profile + ongoing GUARDCALL contestation. However, the report's `Type of EMI: UNKNOWN` field explicitly does not commit to attribution. ^[inferred] An alternative reading is platform-side equipment failure (MQ-9 link reliability is sensitive to weather, satellite-uplink dropouts, and sub-system faults), but the 2-events-on-same-mission clustering favors an external interference reading. ^[inferred]

**JSIR ID anchoring**: the **JSIR ID330412 + JSIR ID330414 case anchors** are the corpus's **first explicit Joint Spectrum Interference Resolution case-number citations** ^[inferred] — the DoD-wide EMI-event tracking program operated under DoDI 4650.01. ^[inferred] These case IDs would, in principle, be cross-referenceable to JSIR-archived spectrum-analysis files for the Sep-2020 Persian Gulf window. ^[inferred]

**EMI-as-Misrep-schema-axis anchoring**: the structured `## EMI` segment + paired `## GENTEXT/EMI` narrative pattern is novel to the dow-uap corpus at d62 — d60 + d61 did not carry EMI events. ^[inferred] The **canonical USMTF Misrep schema apparently includes an EMI segment** when relevant; at N=3 d62 is the first to exercise this segment. **The EMI segment is therefore a newly-anchored canonical USMTF Misrep segment at N=1 of EMI-event-bearing Misreps**, with the full-Misrep schema now extended to include `Landing + Takeoff + On Station + ISR + Off Station + GUARDCALL + GENTEXT/GUARDCALL + OBSERVATION + GENTEXT/OBSERVATION + WEATHER + EFFECTIVENESS + EMI + GENTEXT/EMI`. ^[inferred] Future d-ingests will test whether EMI events recur within or outside the 482ATKS cluster.

## Iranian Air Defense GUARDCALL — class-level signature firms at N=3 with tone-and-count variance

Pages 5-6 carry **three explicit GUARDCALL structured blocks + three GENTEXT/GUARDCALL segments** documenting Iranian Air Defense radio hails of the aircraft — anchoring GUARDCALL at N=3 across the d60+d61+d62 cluster:

| Field | GUARDCALL #1 | GUARDCALL #2 | GUARDCALL #3 |
|---|---|---|---|
| GUARDCALL DTG | 160408:00ZSEP20 | 160421:00ZSEP20 | 161141:00ZSEP20 |
| Aircraft Callsign | 1.4a | 1.4a | 1.4a |
| Ground Station Callsign | **IRANIAN AIR DEFENSE** | **IRANIAN AIR DEFENSE** | **IRANIAN AIR DEFENSE** |
| Aircraft Location | **40RCP76 1.4a 96 1.4a** | **40RCP76 1.4a 96 1.4a** | **40RCP2 1.4a 8 1.4a** |
| Aircraft Heading | **360T** | **010M** | **277 T** |
| Aircraft Altitude | **FL180** | **FL180** | **FL040** |
| Aircraft Airspeed | (blank) | (blank) | (blank) |
| Number of Calls Noted | **1** | **1** | **1** |
| Guardcall Tone | **DIRECTIVE** | **DIRECTIVE** | **PROFESSIONAL** |
| GENTEXT/GUARDCALL | `AT 0408Z, 1.4a WAS HAILED ON GUARD 1.4g FREQ BY IRANIAN AIR DEFENSE. STANDARD ORDERS GIVEN, 1.4a RESPONDED WITH THE STANDARD RESPONSE. NO IMPACT TO MISSION` | `AT 0421Z, 1.4a WAS HAILED ON GUARD 1.4g FREQ BY IRANIAN AIR DEFENSE. STANDARD ORDERS GIVEN, 1.4a RESPONDED WITH THE STANDARD RESPONSE. NO IMPACT TO MISSION` | `AT 1141Z, 1.4a WAS HAILED ON GUARD 243.000 FREQ BY IRANIAN AIR DEFENSE. STANDARD ORDERS GIVEN. 1.4a RESPONDED WITH STANDARD RESPONSE. NO IMPACT TO MISSION` |

**Five novel signals at d62 vs d60+d61:**

1. **Per-mission GUARDCALL count = 3** (vs 1 at d60 + 1 at d61) — first multi-hail mission in the cluster. Distribution at N=3 is now `1, 1, 3` ranging across the lower and upper tails. ^[inferred] The "single hail per mission" reading from d60+d61 is **superseded at N=3** — Iranian Air Defense may issue multiple hails within a single mission depending on aircraft routing.
2. **`DIRECTIVE` tone introduced** — d60 + d61 both `PROFESSIONAL`; d62's first two hails carry `DIRECTIVE` tone before reverting to `PROFESSIONAL` on the third hail. **`DIRECTIVE` is a structural first at d62.** ^[inferred] The tone variance suggests Iranian Air Defense ground-station controllers vary their approach across hails — possibly correlating with airspace-encroachment severity or controller individual style. ^[inferred] The de-escalation from DIRECTIVE → DIRECTIVE → PROFESSIONAL across the three hails (13 min, 13 min, 7 hr 20 min separations) may reflect controller-shift change or post-routing-adjustment stand-down. ^[inferred]
3. **Same-MGRS multi-hail cluster** — GUARDCALLs #1 + #2 both occurred at **MGRS 40RCP76** at **FL180**, 13 minutes apart. The aircraft was loitering in the same 10-km sub-square between the two hails. ^[inferred] The 360T → 010M heading change (slight eastward turn) suggests minimal route adjustment between hails. **First same-MGRS multi-hail cluster in dow-uap corpus.** ^[inferred]
4. **Frequency citation explicit at GUARDCALL #3** — the GENTEXT/GUARDCALL narrative for hail #3 explicitly cites **`243.000 FREQ`** (243.000 MHz UHF Guard — the military emergency/guard frequency). Hails #1 + #2 carry portion-redacted `1.4g FREQ` instead. **The 243.000 MHz citation is the first explicit Guard frequency citation in the dow-uap corpus.** ^[inferred] The d60 GENTEXT/GUARDCALL also used `1.4g` (portion-redacted) without explicit frequency citation. **The d62 mix of `1.4g`-redacted (hails #1+#2) and `243.000`-explicit (hail #3) within the same document is a partial-redaction inconsistency** — possibly OCR variance, or the per-hail GENTEXT was redacted by different reviewers. ^[ambiguous]
5. **Altitude variance across hails** — hails #1 + #2 at **FL180** (18,000 ft cruise altitude); hail #3 at **FL040** (4,000 ft — significantly lower). The aircraft descended ~14,000 ft between the second and third hails over a ~7 hr interval. ^[inferred] The descent context is not preserved in OCR (no GENTEXT/EMI on descent; no Off Station event preceding hail #3 — hail #3 is at 1141Z, EMI #1 starts at 1248Z just 67 minutes later; descent likely for low-altitude pattern-of-life observation of Iranian naval assets ^[inferred]).

**The GUARDCALL recurrence is anchored decisively at N=3** with d62. ^closed-by-dow-uap-d62 on [[references/dow-uap-d60-mission-persian-gulf-2020-08-08|d60]]'s "Test the Iranian Air Defense GUARDCALL recurrence pattern" thread. Iranian Air Defense direct hails of US MQ-9 ISR assets in the eastern Persian Gulf / Strait of Hormuz approach are a **class-level signature of 482ATKS / 432 AEW NAVCENT-support tasking** in the Aug-Sep 2020 window, with **per-mission count + tone + frequency-citation + altitude variance**. ^[inferred] The pattern is firmly anchored at N=3.

## Platform attribution — same 482ATKS / 432 AEW MQ-9 as d60+d61, different aircrew filling form

The d62 POC block (page 1) supplies a **byte-for-byte match with d60+d61 on every unit-attribution axis**, but with **different ranks at POC and APPROVER** indicating different aircrew:

| Role | d60 | d61 | d62 | Match? |
|---|---|---|---|---|
| POC Rank | 1st Lt | 1st Lt | **SSgt** (enlisted Staff Sergeant) | **DIVERGES at d62** |
| POC Unit | 482ATKS | 482ATKS | **482ATKS** | **MATCH** |
| POC Wing | 432 AEW | 432 AEW | **432 AEW** | **MATCH** |
| POC Service | Air Force | Air Force | **Air Force** | **MATCH** |
| POC Operations Center | 609 CAOC | 609 CAOC | **609 CAOC** | **MATCH** |
| QC Rank | Ctr | Ctr | **Ctr** (contractor) | **MATCH** |
| QC Unit | (PAROC unspecified parent) | 12AF, Det 3, PAROC | **12AF, Det 3, PAROC** | **MATCH on PAROC at 12AF Det 3** (second explicit attestation at this parent — N=2 explicit) |
| QC Wing | Other | Other | **Other** | **MATCH** |
| APPROVER Rank | 1st Lt | 1st Lt | **SrA** (enlisted Senior Airman) | **DIVERGES at d62** |
| APPROVER Unit | 609th AOC | 609th AOC | **609th A0C** (OCR `A0C` likely AOC) | **MATCH** |
| APPROVER Service | Air Force | Air Force | (not preserved) | **MATCH on context** |
| APPROVER Operations Center | 609 CAOC | 609 CAOC | **609 CAOC** | **MATCH** |
| MSGID Originator | 482ATKS | 482ATKS | **482ATKS** | **MATCH** |
| Operation | 1.4a | 1.4a | **1.4a** | **MATCH** (all 3 portion-redacted) |
| Domain | AIR | AIR | **AIR** | **MATCH** |
| Operations Center (Admin) | 609th | 609th | **609th** | **MATCH** |
| MAJCOM | ACC | ACC | **ACC** | **MATCH** |
| COCOM | USCENTCOM | USCENTCOM | **USCENTCOM** | **MATCH** |
| Report Type | MISREP | MISREP | **MISREP** | **MATCH** |
| Mission Type | AREC | AREC | **AREC** | **MATCH** |
| Country Tasked | US - UNITED STATES | US - UNITED STATES | **US - UNITED STATES** | **MATCH** |
| Service Tasked | A - AIR FORCE | A - AIR FORCE | **A - AIR FORCE** | **MATCH** |
| Takeoff / Landing ICAO | OKAS | OKAS | **OKAS** | **MATCH** (Ali Al Salem AB, Kuwait ^[inferred]) |
| TGT Pod | ANDAS4 | ANDAS4 | **ANDAS4** | **MATCH** |
| Additional Avionics | AH_GMESH | AH_GMESH | **AH_GMESH** | **MATCH** |
| Supported Unit | NAVCENT | NAVCENT | **NAVCENT** | **MATCH** |
| Supported Operation | OPERATION 1,4a | OPERATION 1,4a | **OPERATION 1.4a** | **MATCH** (all 3 portion-redacted) |
| Precoord Time | 24 HOURS | 24 HOURS | **24 HOURS** | **MATCH** |
| Precoord Effectiveness | SATISFACTORY | SATISFACTORY | **SATISFACTORY** | **MATCH** |

**29-of-31 axis match** at the unit / platform / tasking level. The two divergence axes are **POC rank and APPROVER rank** — d60 + d61 both carried **1st Lt** (commissioned officer) at both POC and APPROVER, but **d62 carries SSgt (enlisted Staff Sergeant) at POC and SrA (enlisted Senior Airman) at APPROVER**. ^[inferred] This indicates a **different aircrew or different shift-of-operators filling out the form** for the d62 mission vs the d60+d61 pair. **The same-unit-same-tasking cluster is at the squadron-platform-tasking level (482ATKS / 432 AEW / MQ-9 at OKAS supporting NAVCENT Operation 1.4a), not at the person level.** ^[inferred] Within the 482ATKS rotation, different operators fly different sorties — the cluster captures a squadron deployment, not a single crew.

**Same operation `1.4a` portion-redaction token at N=3** strengthens the "same-named-operation" reading: three Misreps in a 38-day window all naming the supported operation as `1.4a` (portion-redacted). Reading 1 (same operation) most coherent at N=3 ^[inferred]; Reading 2 (different operations sharing a redaction position-marker) increasingly strained as the token recurrence anchors. ^[inferred]

**PAROC IDAT triple-attestation extends to N=5** (counting d62): d52 (15 AF / DET 1 PAROC) + d50 (12 AF / DET 3 PAROL/PAROC OCR-ambiguous) + d60 (PAROC unspecified parent) + d61 (12 AF / DET 3 PAROC explicit) + **d62 (12 AF / DET 3 PAROC explicit, second explicit attestation at this parent)**. **d62 decisively resolves the d50 PAROC-vs-PAROL OCR ambiguity in favor of PAROC** — at N=2 explicit clean-OCR attestations of `PAROC` at 12 AF / DET 3 (d61 + d62), the d50 `PAROL` reading is almost certainly OCR C↔L confusion. ^[inferred] **^closed-by-dow-uap-d62 on [[references/dow-uap-d50-email-indopacom-2025-04|d50]]'s "Resolve PAROC vs PAROL" open thread.**

## Collateral ISR observations — 3 Iranian-military-presence observations including IR-SA-5 launcher + Houdong WPTGs

The GENTEXT/ISR segment (page 4) preserves **three Iranian-military-presence observations** in addition to the UAP datum, GUARDCALL events, and EMI events:

1. **0930Z — 1X IR-SA-5 launcher observed IVO MGRS `40RCP02 1,4a D5 1,4a` on Abu Musa Island**. The **IR-SA-5** is the Iranian designation for the **S-200 / SA-5 Gammon long-range surface-to-air missile system** ^[inferred] — Soviet-design strategic-altitude SAM (operational range ~200 km, ceiling ~40 km), of which Iran operates a small fleet. ^[inferred] The Abu Musa Island AFLD location is consistent with the same Iranian-occupied island d61 observed an IL-76 Candid at. ^[inferred] **First IR-SA-5 / S-200 / SA-5 surface-to-air missile launcher observation in the dow-uap corpus.** ^[inferred]
2. **1321Z — 2X POSS Houdong WPTG (Houdong-class fast-attack missile boats) observed docked pierside IVO MGRS `39RXL60 1,4aD2 1,4a`**. The **Houdong class** (Chinese export designation) is the **Iranian Sina-class (formerly Houdong-class) missile patrol boat** ^[inferred] — Chinese-designed fast-attack craft armed with C-802 anti-ship missiles, operated by the IRGCN. ^[inferred] **WPTG** is plausibly **Watercraft / Patrol Type / Group** or similar IRGCN-class designator. ^[ambiguous] **First Houdong / Sina-class missile patrol boat observation in the dow-uap corpus.** ^[inferred]
3. **0930Z + 1321Z together** anchor the operational-detail layer for d62's anti-Iran ISR tasking — same as d61's anti-Iran pattern-of-life characterization but now extending to **Iranian strategic SAM systems (IR-SA-5) and Iranian fast-attack craft (Houdong / Sina)** in addition to the d61's Naser-class WAP + Greater Tunb naval-port small vessel + Abu Musa Island IL-76 Candid observations. ^[inferred] **First explicit Iranian strategic-SAM observation in dow-uap corpus.**

**Operational significance**: the collateral observations explicitly target Iranian military-presence pattern-of-life data — confirming the d61 reading "anti-Iran maritime + UAS + outside-port surveillance tasking" extends to N=2 of full-Misreps with operational-detail (d61 + d62; d60 GENTEXT/ISR was less detailed). ^[inferred] **The 482ATKS / 432 AEW MQ-9 cluster is firmly anti-Iran ISR by Aug-Sep 2020** at N=2 of detailed-narrative full-Misreps. ^[inferred]

The 0930Z IR-SA-5 launcher observation is **the operational-context match for the GUARDCALL events 4 hr 22 min earlier** (0408Z + 0421Z): the aircraft observed an Iranian SA-5 SAM launcher, and Iranian Air Defense had hailed the aircraft 4 hr earlier — a coherent picture of contested-airspace ISR with mutual surveillance. ^[inferred]

## Geographic decoding — same theater as d60+d61, refined Strait-of-Hormuz coverage

The d62 internal MGRS coordinates supplement the combined d60+d61 12-coord set with **9 additional coordinates** across UTM zone 39R + 40R:

| MGRS | UTM Zone / Square | Inferred sub-region | Block |
|---|---|---|---|
| **40RCQ3 1.4a D5 1.4a** (Tasked Start Point, ISR block) | 40R / CQ | Eastern Strait of Hormuz / Greater Tunb vicinity ^[inferred] | ISR tasking |
| **40RCP02 1.4a D5 1.4a** (Abu Musa Island, IR-SA-5 obs) | 40R / CP | Eastern Persian Gulf — Iranian Abu Musa Island ^[inferred] | Collateral ISR |
| **39RXL60 1,4aD2 1,4a** (Houdong WPTG pierside obs) | 39R / XL | Persian Gulf eastern interior / Strait of Hormuz approach ^[inferred] | Collateral ISR |
| **40RCP76 1.4a 96 1.4a** (Aircraft Location, GUARDCALL #1) | 40R / CP | Eastern Persian Gulf / Strait of Hormuz approach ^[inferred] | GUARDCALL #1 |
| **40RCP76 1.4a 96 1.4a** (Aircraft Location, GUARDCALL #2) | 40R / CP | Same 10-km sub-square as GUARDCALL #1 | GUARDCALL #2 |
| **40RCP2 1.4a 8 1.4a** (Aircraft Location, GUARDCALL #3) | 40R / CP | Eastern Persian Gulf — same 100-km square as GUARDCALL #1+#2 | GUARDCALL #3 |
| **39RXK0 1.4a 5 1.4a** (Aircraft Location, EMI #1) | 39R / XK | Persian Gulf eastern interior ^[inferred] | EMI #1 |
| **39RVM92 1,4a89 1,4a** (Aircraft Location, EMI #2) | 39R / VM | Persian Gulf interior — same 100-km square as UAP OBS event | EMI #2 |
| **39RVM51 1,4a70 1,4a** (Aircraft + UAP Location, OBS block) | 39R / VM | Persian Gulf interior, same 10-km MGRS sub-square ^[inferred] | **UAP event** |

**All 9 internal MGRS coordinates decode inside the body-text-declared `IVO ARABIAN GULF, STRAIT OF HORMUZ AND GULF OF OMAN` operational area** (UTM zones 39R + 40R). ^[inferred] **d62 extends d60+d61's filename-axis verification to N=3** at the internal-coord level for `*-arabian-*` / `*-persian-gulf*` / `*-strait-of-hormuz*`-class filenames. **Combined d60 + d61 + d62 = 21-of-21 internal MGRS coordinates decode inside the body-text-declared Arabian Gulf area** — robust at N=3.

**Same 10-km MGRS sub-square aircraft-and-UAP geometry at d62** — both the aircraft position and the UAP position record as `39RVM51 1,4a70 1,4a`. ^[inferred] This is the **tightest co-located aircraft-and-UAP geometry in the dow-uap corpus to date** — d61 had same-100-km-square at ~50-80 km separation (39RVM38 aircraft / 39RVM88 UAP); d62 has **same-10-km-square at ≤10 km separation**. ^[inferred] **First same-10-km-MGRS-square aircraft-and-UAP geometry in the dow-uap corpus.**

**The Tasked Start Point at `40RCQ3` is a structural first within the d60+d61+d62 cluster** — d60's Tasked Start Point was `39RVN34` (UTM 39R western interior); d61's was `39RUN46` (UTM 39R western interior); **d62's is `40RCQ3` (UTM 40R Strait-of-Hormuz / Greater Tunb vicinity, ~200 km eastward).** ^[inferred] The d62 mission was tasked to begin in the eastern Strait of Hormuz area — closer to the choke point + Iranian-occupied islands than the prior two missions started. **The 482ATKS cluster's tasked operational area shifted eastward at d62.** ^[inferred]

**Filename-date axis**: filename `september-2020` ↔ body `152302Z SEP 20` (takeoff) + `16 SEP 2020 1732Z` (UAP) + `161958Z SEP 20` (landing). **MATCH at the month level** ^[inferred] — body events span 15-16 Sep 2020 mission cycle.

**Page filename convention**: per d60+d61 precedent (filename `august-2020` → page anchored to body event date), d62's page is `references/dow-uap-d62-mission-strait-of-hormuz-2020-09-16.md` (UAP observation at 16 Sep 1732Z).

## Release framework — Block B triples to 3-of-8; d38 + d61 + d62 anchor the second allocation

The d62 release block on every page carries **Block B**, matching [[references/dow-uap-d38-range-fouler-middle-east-may-2020|d38]] + [[references/dow-uap-d61-mission-persian-gulf-2020-08-27|d61]] on all four shared axes:

| Field | Block B (d38, d61) | d62 | Match? |
|---|---|---|---|
| Declassification authority | MG Richard A. Harrison | MG Richard A. Harrison | **MATCH** |
| MDR case | `26-0019` (single case) | `26-0019` (single case) | **MATCH** |
| Routing stamp | Approved for Release to AARO | Approved for Release to AARO | **MATCH** |
| Release-stamp date | `01/26/26` | `01/26/26` | **MATCH** |
| **Release sequence #** | `001` (d38 single-page); `001 → 007` (d61 7-page) | **`001 → 009`** (sequential 9-page) | **EXTENDS** (per-document sequential page-stamping anchored within Block B at N=3 — 3-digit scheme decisively confirmed) |

**Critical findings flowing from d62's Block B attestation**:

1. **Block B triples from 2-of-7 to 3-of-8 release-block-testable artifacts.** d38 + d61 + d62 = Block B at N=3. Block A = d55 + d58 + d44 + d56 + d60 = 5-of-8. The Block A 5-of-8 = 62.5% / Block B 3-of-8 = 37.5% distribution **refines d61's "Block B doubles to 2-of-7" headline** — the Block-A-dominant asymmetry holds but Block B is now firmly anchored as a stable second allocation at N=3, not at N=2. ^[inferred] **This is a confirmation of d61's finding, not a paradigm shift** — the dow-uap release is a multi-batch operation with Block B covering a meaningful third of release-block-testable artifacts. ^[inferred]
2. **Per-document sequential page-stamping is decisively confirmed in Block B at N=3** — d38 single-page = `001`; d61 multi-page = `001→007`; d62 multi-page = **`001→009`**. Each Block-B artifact carries 3-digit per-page sequential page-stamps starting at `001`. ^[inferred] **The 3-digit scheme is now anchored at N=3 across single-page + 7-page + 9-page artifacts** — definitive.
3. **Block B precedes Block A by 60 days, confirmed at N=3.** Block B release date `01/26/26` (26 Jan 2026); Block A release date `03/27/26` (27 Mar 2026). The 60-day gap holds across all Block-B attestations (d38 + d61 + d62 all at `01/26/26`). ^[inferred]
4. **Mission-report sub-class distribution across Blocks at N=3 Block-B testable**:
    - Block A range-fouler debriefs: d55 (CTG narrative) + d58 + d44 + d56 (4 of 4 Block A range-foulers ^[inferred])
    - Block A full Misrep: d60 (1 of 1 Block A Misreps)
    - Block B range-fouler debrief: d38 (1 of 1 Block B range-foulers)
    - **Block B full Misreps: d61 + d62 (2 of 2 Block B Misreps)**
   The mission-record sub-classes appear in **different proportions across the Blocks**: range-fouler is Block A-dominant (4-of-5 d44+d56+d58+d55 vs 1-of-1 d38 in Block B); full-Misrep is Block B-dominant (2-of-3 d61+d62 vs 1-of-3 d60 in Block A). ^[inferred] **The Block split is NOT fully orthogonal to document class at N=3 Block-B** — there is a weak class-vs-block correlation emerging: full-Misreps tend toward Block B, range-foulers tend toward Block A. To be tested at higher N. ^[inferred]
5. **AARO-receiving-authority closure firms further at N=8 stamp-recurrence** across the corpus (5 Block A + 3 Block B). ^[inferred]

## Behavioral classification — N=8 mission-report UAP-datum counter increment

Per the [[concepts/uap-aircraft-engagement|UAP–Aircraft Engagement]] framework:

- **UAP-toward-aircraft engagement-class**: **negative datum** — the d62 UAP at MGRS `39RVM51` and the aircraft at MGRS `39RVM51` are co-located at the same 10-km sub-square, but there is **no close-approach + no target switching + no phase-of-flight correlation in the OBS record**. The same-MGRS co-location is a geometric coincidence at the 10-km grid level, not an engagement-class signature. ^[inferred] No close-proximity, co-location for non-trivial time, or selection between aircraft is attested. ^[inferred] The d62 record carries **no UAP-kinematics**, **no UAP-morphology**, **no duration**, **no proximity** — bare ISR-logged observation only.
- **Aircraft-toward-UAP engagement-pipeline**: **negative datum** — no weapons-quality track, no NTS, no TFLIR ID, no closure attempt. The MQ-9 observed via FMV (matching d60); passive FMV observation only.
- **Sub-class within brief-observation**: **sub-class 8 — FMV-observation + zero-mission-impact-on-UAP + kinematics-blank + morphology-blank** — same as d60. ^[inferred] **d62 confirms sub-class 8 at N=2 (d60+d62); sub-class 9 (formation-track) isolated at N=1 (d61).**

**Mission-report UAP-datum counter increments N=7 → N=8 records / 8 → 9 datums** at the dow-uap level. ^[inferred] The renamed framing (mission-report UAP-datum records) persists.

## Bibliographic frame

| Field | Value |
|---|---|
| Source basename | `dow-uap-d62-mission-report-strait-of-hormuz-september-2020.json` |
| Source bytes | 10,348 |
| Content SHA-256 | `27e87e30164213033730a9100e6da9ce6927a34a87de53b2d99ce3412bbc034a` |
| OCR engine | `mistral-ocr-latest` ^[inferred] (series-wide pattern) |
| Pages OCR'd | **9 substantive pages (zero header-only)** — third all-substantive multi-page Misrep in dow-uap corpus; **longest full-Misrep ingest in the corpus by page count** |
| Document class | **Full USMTF Misrep — multi-segment** (same as d60+d61; third attestation, class CONFIRMED at N=3) |
| Misrep identifier | **Misrep 4782130** — third explicit Misrep ID in dow-uap corpus; distinct from d60's `4592219` and d61's `4685903` (Misrep IDs are per-event, not per-unit; counter rising — 4782130 vs 4685903 = +96,227 IDs across 20 days; consistent with high-volume USCENTCOM MISREP counter ^[inferred]) |
| Classification (top) | Multiple Sources (Classification Source per Admin block); Declassification Date `20450301` (1 Mar 2045 — same as d60+d61) ^[inferred] |
| Classification authority | EO 13526 §1.4(a) per-page ^[inferred]; §1.4(g) on EMI-affected-system fields (first §1.4(g) attestation in dow-uap corpus); `(b)(6)` redaction recurring |
| Release-block classification | **Block B** (Harrison + USCENTCOM MDR `26-0019` + AARO + `01/26/26`) — 3rd attestation of Block B in corpus (with d38+d61) — **Block B triples** |
| Release-sequence | **`001 → 009`** (per-page sequential across 9 pages) — confirms 3-digit per-document page-stamp scheme as Block B convention at N=3 (single-page d38 + 7-page d61 + 9-page d62) ^[inferred] |
| Receiving authority | **AARO** (`Approved for Release to AARO`) |
| Originating service | **US Air Force** (Service Tasked `A - AIR FORCE`; Country Tasked `US - UNITED STATES`) |
| Originating MAJCOM | **ACC** (Air Combat Command) |
| Originating COCOM | **USCENTCOM** |
| Originating Operations Center | **609th** (per Operation block); **609 CAOC** (per POC + APPROVER) |
| Originating unit (POC) | **482ATKS / 432 AEW** — 482d Attack Squadron / 432d Air Expeditionary Wing ^[inferred] (same as d60+d61; **third member of the 19-day-then-20-day same-unit-same-tasking triplet** with d60 + d61) |
| QC role | **PAROC / 12AF, Det 3** — explicit (second explicit attestation at this parent after d61; **decisively resolves d50 PAROC-vs-PAROL ambiguity in favor of PAROC** ^closed-by-dow-uap-d62) |
| POC rank delta | **SSgt (enlisted Staff Sergeant)** vs d60+d61's 1st Lt — first enlisted POC in the cluster; different aircrew filling form within same squadron ^[inferred] |
| APPROVER rank delta | **SrA (enlisted Senior Airman)** vs d60+d61's 1st Lt — same aircrew-rotation reading ^[inferred] |
| Witness platform | **MQ-9 Reaper** ^[inferred] (20.9 mission hr + AIRHANDLER SIGINT ^[inferred] + FMV exploitation + ANDAS4 ^[inferred] sensor + AH_GMESH ^[inferred] avionics + OKAS Kuwait launch + AREC mission + DGS-PED ^[inferred] context) |
| Mission type | **AREC** (Armed Reconnaissance) ^[inferred] |
| Supported unit | **NAVCENT** (US Naval Forces Central Command, 5th Fleet) ^[inferred] |
| Supported operation | `OPERATION 1.4a` (portion-redacted; same operation token as d60+d61; same-operation reading firms at N=3 ^[inferred]) |
| LRE (Launch and Recovery Element) attestation | **N=3 in dow-uap corpus** (recurring with d60+d61) |
| DGS attribution | **N=3 in dow-uap corpus** (FMV exploitation context recurring with d60+d61; DGS1 explicit in d60) ^[inferred] |
| AIRHANDLER attribution | **N=3 in dow-uap corpus** (recurring with d60+d61) ^[inferred] |
| Series | [[entities/dow-uap-foia-release\|DoW-UAP FOIA release]] |
| Series position | **16-of-40** by ingest order (8th substantive mission report; third full Misrep) |
| Event date | **15-16 Sep 2020** (UAP OBS at 161732Z; mission cycle 152302Z–161958Z) — body-text date verifies filename `september-2020` |
| Event night/day | UAP at 1732Z = ~20:32–21:32 local (UTC+3/+4: early evening / sunset) ^[inferred] |
| Theater | **Arabian / Persian Gulf, Strait of Hormuz, Gulf of Oman** (UTM zones 39R + 40R) — 9-of-9 internal MGRS coords decode inside operational area; **Tasked Start Point shifted eastward to 40RCQ3 Strait-of-Hormuz / Greater Tunb vicinity** (vs d60+d61's western 39RVN/39RUN starts) |
| Object count | **1** (single UAP, indefinite article `A UAP`) ^[inferred] |
| Object morphology | *not reported* — third morphology-blank full-Misrep datum; matching d60 |
| UAP-side kinematics | *not reported* — matching d60 bare-FMV signature (vs d61's partial heading axis) |
| Encounter duration | *not reported* — matching d60 (vs d61's bounded 2-min track) |
| Aircraft state at OBS event | **FL180 / 90 KIAS** — first explicit witness-aircraft-altitude + airspeed on the OBS line within the d60+d61+d62 cluster ^[inferred] (d60 + d61 both left these blank) |
| Sensor channel | **FMV** explicit (matching d60; vs d61's portion-redacted `1.4a SENSOR`) — sub-class 8 sensor confirmed at N=2 ^[inferred] |
| Aircraft-and-UAP MGRS geometry | **SAME 10-km MGRS sub-square `39RVM51`** — first same-10-km-square attestation in corpus (vs d61 same-100-km / d60 three-square spread) ^[inferred] |
| GUARDCALL events | **3 per mission** — first multi-hail mission in cluster (vs 1 at d60 + 1 at d61); distribution at N=3 = 1+1+3; first DIRECTIVE tone (hails #1+#2); first same-MGRS multi-hail cluster (#1+#2 at 40RCP76); first 243.000 MHz Guard frequency explicit citation (hail #3); altitude variance FL180 → FL040 across mission ^[inferred] |
| EMI events | **2 per mission** — **NEW STRUCTURAL ELEMENT in dow-uap mission-report sub-class** (first EMI events in corpus); both MEDIUM mission impact + Flight Path Deviation; UNKNOWN type; total 38 min link-loss across 11 min + 27 min events; JSIR IDs 330412 + 330414 |
| Collateral ISR observations | **2 Iranian-military-presence observations** — 1X IR-SA-5 (S-200 / SA-5 Gammon SAM) launcher on Abu Musa Island + 2X POSS Houdong / Sina-class missile patrol boats pierside; first IR-SA-5 + first Houdong / Sina-class observations in dow-uap corpus ^[inferred] |
| Iranian Air Defense GUARDCALL | **N=3 in dow-uap corpus** (recurring with d60+d61) — class-level signature with tone-and-count variance ^closed-by-dow-uap-d62 |

## Structural firsts the d62 ingest anchors

d62 introduces or extends the following in the dow-uap corpus (now N=16 ingests):

1. **Confirms FULL USMTF Misrep document class at N=3.** ^closed-by-dow-uap-d62 on [[references/dow-uap-d60-mission-persian-gulf-2020-08-08|d60]]'s "Validate full-Misrep at N≥3" thread (which was already closed at N=2 by d61; d62 extends to N=3). The class is decisively anchored. **Headline finding.**
2. **Same-unit-same-tasking cluster extends to N=3 triplet** — d60 + d61 + d62 across 38 days; **the corpus's first 3-document same-unit-same-tasking repeat-mission cluster**. ^[inferred] Closes d61's "Test for d62+ as another 482ATKS Aug-2020 mission" thread (now extends to Aug-Sep 2020). **Headline finding.**
3. **NEW STRUCTURAL ELEMENT — EMI segment in USMTF Misrep schema** — d62 carries 2 structured EMI events + paired GENTEXT/EMI segments + JSIR ID anchors + MEDIUM mission-impact + Flight Path Deviation mission-changed flag. **First EMI-event attestation in dow-uap corpus** at any document class. ^[inferred] Anchors EMI as a canonical USMTF Misrep segment. **Headline finding.**
4. **Block B triples to N=3** — d38 + d61 + d62; refines d61's "Block B doubles" headline; Block A = 5-of-8 (62.5%), Block B = 3-of-8 (37.5%). 3-digit per-page sequential page-stamp scheme decisively anchored across single-page + 7-page + 9-page artifacts. ^[inferred]
5. **Iranian Air Defense GUARDCALL recurrence anchored at N=3** ^closed-by-dow-uap-d62 on d60's GUARDCALL-recurrence thread. **First multi-hail per mission (3 hails)**; **first DIRECTIVE tone** (vs d60+d61 PROFESSIONAL); **first same-MGRS multi-hail cluster** (hails #1+#2 at 40RCP76 13 min apart); **first explicit 243.000 MHz Guard frequency citation**. ^[inferred]
6. **PAROC vs PAROL OCR ambiguity decisively resolved** — d62 is the second explicit clean-OCR PAROC at 12 AF / DET 3 attestation (with d61); at N=2 explicit clean attestations, d50's PAROL reading is almost certainly OCR C↔L confusion. ^closed-by-dow-uap-d62 on [[references/dow-uap-d50-email-indopacom-2025-04|d50]]'s "Resolve PAROC vs PAROL" thread. ^[inferred]
7. **POC + APPROVER rank delta within same-unit cluster** — d62 SSgt + SrA (enlisted) vs d60+d61 1st Lt (commissioned) — **first within-cluster rank divergence; cluster continuity is at squadron-platform level not person level** ^[inferred]. The 482ATKS rotation captures different aircrews flying different sorties.
8. **First same-10-km-MGRS-square aircraft-and-UAP geometry in dow-uap corpus** — both at `39RVM51` at d62 (vs d61 same-100-km / d60 three-square spread). ^[inferred]
9. **First explicit witness-aircraft altitude (FL180) + airspeed (90 KIAS) on UAP OBS line** within the d60+d61+d62 cluster — d60+d61 both left these blank. ^[inferred]
10. **Sub-class 8 (FMV-observation + zero-mission-impact-on-UAP + kinematics-blank + morphology-blank) confirms at N=2** (d60+d62); sub-class 9 (formation-track + bounded-duration + heading-axis-only + sensor-PID-loss-on-weather) isolated at N=1 (d61). The d61 anchor reading remains correct at order-of-discovery but is reframed: at N=3 same-unit Misreps, bare-FMV is dominant and formation-track is the outlier. ^[inferred]
11. **Mission-report UAP-datum counter increment to N=8 records / 9 datums** ^[inferred] — extends from d61's N=7 / 8.
12. **First §1.4(g) classification-category marking in dow-uap corpus** — EMI-affected-system fields use `1.4g` portion-redaction (EO 13526 §1.4(g) vulnerabilities/capabilities of national-security systems) vs the §1.4(a) used elsewhere. ^[inferred]
13. **First Joint Spectrum Interference Resolution (JSIR) case-ID citations** in the dow-uap corpus — JSIR ID330412 + JSIR ID330414. ^[inferred]
14. **First IR-SA-5 (S-200 / SA-5 Gammon) Iranian SAM launcher observation** in dow-uap corpus. ^[inferred]
15. **First Houdong / Sina-class Iranian missile patrol boat observation** in dow-uap corpus. ^[inferred]
16. **N=3 filename-axis verification at internal-coord level** for `*-arabian-*` / `*-persian-gulf*` / `*-strait-of-hormuz*`-class filenames. Combined d60 + d61 + d62 = **21-of-21 internal MGRS coords decode inside body-text-declared operational area**. ^[inferred]
17. **Tasked Start Point shift to eastern Strait-of-Hormuz / Greater Tunb (40RCQ3)** — d60 + d61 both started at western Persian Gulf interior (39R VN/UN); d62 starts at eastern Strait-of-Hormuz approach. **The 482ATKS cluster's tasked AOR shifted eastward at d62.** ^[inferred]
18. **Mission-cycle DTG anchor count rises to 18 at N=3** (vs d60's 8; d61's 14) — **d62 is the operationally-most-detail-rich record in the dow-uap full-Misrep sub-class.** ^[inferred]
19. **GUARDCALL temporal-sequencing at N=3** — d60 hail POST-UAP (1250Z after 0726Z); d61 hail PRE-UAP (0532Z before 1527Z); d62 hails ALL PRE-UAP (0408Z + 0421Z + 1141Z all before 1732Z UAP). **GUARDCALL events not causally linked to UAP events** anchored at N=3 (the d62 hails occur 4-13 hr before the UAP observation; the EMI events occur 2-5 hr before; both classes of disturbance precede the UAP datum but with no consistent timing). ^[inferred]
20. **Same operation `1.4a` portion-redaction token at N=3** strengthens the "same-named-operation" reading; reading 1 (same operation) most coherent at N=3 ^[inferred].
21. **EMI events temporal context vis-à-vis Iranian Air Defense** — both EMI events (1248Z + 1414Z) occurred **between GUARDCALL #3 (1141Z) and the UAP OBS (1732Z)**; both at FL180; both during transit through Iranian-airspace-margin UTM 39R sub-squares. ^[inferred] Iranian-EW-emission hypothesis carries operational-context support but is not in-document attributed (`Type of EMI: UNKNOWN`). ^[ambiguous]
22. **OCR digit-swap alternation pattern at d62** (5-of-9 pages render `2020`, 4-of-9 render `2025`) — distinct from d61's isolated single-page swap; **anchors page-banner OCR digit-swap as class-level OCR signature** with per-document variable rate. ^[inferred]
23. **d62 is the longest full-Misrep ingest by page count** (9 pages vs d61 7 pages vs d60 6 pages) — page count tracks operational-detail richness; longer mission cycles → more events → more pages. ^[inferred]

## OCR ambiguities

- **Page-banner OCR digit-swap alternation pattern** — 5-of-9 pages render `Declassified on: 22 January 2020`; 4-of-9 render `22 January 2025`. ^[ambiguous] The `2025` reading is almost certainly correct (declassification cannot precede classification — originating event is 15-16 Sep 2020 with classification valid through `20450301` per Admin block). ^[inferred] **The OCR digit-swap pattern is now anchored at N=3 full-Misrep ingests with per-document variable rate** (d60 = 0/6 swapped; d61 = 1/7 swapped; d62 = 5/9 swapped). ^[inferred] Possible explanation: the OCR rendering of `5` vs `0` digits in the source banner is per-page variable depending on print quality / scan resolution / individual page degradation. ^[inferred]
- **OCR field-order at GENTEXT/ISR (page 4)** — d62's narrative renders events approximately chronologically with one near-anomaly: `0318Z → 0930Z → 1321Z → 0408Z → 0421Z → 1141Z → 1732Z → 1829Z` reads as a flat list rather than strict-time-order. The 0408Z + 0421Z GUARDCALL references appear AFTER 0930Z + 1321Z observations in the OCR rendering — likely OCR field-order or in-document narrative reflow, not real chronological anomaly. ^[inferred] No major event-ordering scramble at d62 like d61's.
- **`1.4g` portion-redaction on EMI fields** — Affected System + Frequency Affected both portion-redacted as `1.4g`. Plausibly **EO 13526 §1.4(g)** (vulnerabilities/capabilities of national-security systems) classification-category marking. ^[inferred] **First §1.4(g) attestation in dow-uap corpus.** Cannot decode specific affected system or frequency from OCR alone.
- **`IR-SA-5`** (page 4 GENTEXT/ISR, 0930Z obs) — Iranian designation for **S-200 / SA-5 Gammon strategic-altitude SAM system** ^[inferred] (Soviet-design long-range SAM, of which Iran operates a small fleet at ranges ~200 km and ceiling ~40 km). ^[ambiguous] OCR token clean; identification confident at the system-class level.
- **`Houdong WPTG`** (page 4 GENTEXT/ISR, 1321Z obs) — **Houdong-class** is the Chinese export designation for what Iran operates as the **Sina-class missile patrol boat** ^[inferred] (Chinese-designed fast-attack craft armed with C-802 anti-ship missiles). **`WPTG`** is plausibly **Watercraft / Patrol Type / Group** or similar IRGCN classification — meaning ^[ambiguous]; OCR token clean.
- **`AT 0700Z`-class anomaly absent at d62** — d61 had a 0700Z observation appearing in OCR after 1742Z (event-order scramble); d62 has no major event-order anomalies, only a minor flat-list narrative ordering issue noted above.
- **`OKAS`** (page 0 Narrative + page 3 Last Land Location + page 3 Takeoff) — ICAO 4-letter aerodrome identifier; **OKAS = Ali Al Salem AB, Kuwait** ^[inferred] (consistent with d60+d61 attestation; **third internal anchor for OKAS-as-MQ-9-base in dow-uap corpus**). ^[ambiguous]
- **`(b)(6)` cleanliness** — the redaction format on d62 is **clean `3.5c (b)(6)` throughout** all 9 pages — recurring pattern from d60+d61. The d54/d8 OCR-corruption pattern (`14(6)` / `1.4(6)`) does **not** recur on d62. ^[extracted]
- **Declassification Date `20450301`** (page 0 CLASSIFICATION block) — interpreted as `2045-03-01` ^[inferred]. Same date as d60+d61's `20450301` — **anchors a class-level 1-Mar-2045 declassification date for 482ATKS / 432 AEW MQ-9 Misreps in this window at N=3** ^[inferred].
- **`A0C`** (page 1 APPROVER Unit `609th A0C`) — almost certainly an OCR misread of `AOC` (Air Operations Center). ^[inferred] OCR digit-zero `0` substituted for letter-O `O`. The 609th AOC attestation pattern matches d60+d61.
- **`POSS Houdong WPTG`** — `POSS` is the Navy POSSIBLE hedge marker; identification hedged.
- **OCR token `(SECRET//IREL TO USA, NATO)` does NOT appear at d62** on the UAP-event narrative — d62's OBS GENTEXT carries no explicit portion-marking on the inline body, distinct from d61's `(S/REL)` marking on the formation-track datum. ^[inferred] Possible reasons: d62 is a bare-observation datum (no detail to release-mark); or per-document portion-marking variance within the cluster. ^[ambiguous]
- **`SECRET//NOFORN`** at the EMI events — the EMI segments do not carry visible inline portion-markings on the GENTEXT/EMI bodies; portion-marking deferred to the page-header / document-level classification scheme. ^[inferred]
- **MSGID Submit Date blank** — no submission timestamp preserved at d62 (same as d60+d61). ^[ambiguous]

## Open threads

- **Validate full-Misrep document class at N≥4** — d60 + d61 + d62 now anchor the class at N=3. Does the class persist beyond same-unit (482ATKS) attestations? A Navy-unit full Misrep (e.g. an F/A-18 or P-8A Misrep) would discriminate between document-class-driven and originating-service-driven readings of the `GENTEXT/OBSERVATION` segment-name distinction. ^[inferred]
- **Test for further d63+ 482ATKS missions in Sep-Oct 2020** — d60 + d61 + d62 are 38 days apart across Aug 8 → Aug 27 → Sep 16. Does the queue contain a d63 / d64 / etc with 482ATKS attestation in late-Sep or Oct 2020? If so, the same-unit cluster extends. If not, the d60+d61+d62 triplet is the closed cluster. ^[inferred]
- **Decode `Operation 1.4a` portion-redaction at d60+d61+d62** — three Misreps in 38 days name the supported operation as `1.4a`. Same-operation reading firms at N=3; remains open at the explicit-name level. ^[ambiguous]
- **Test EMI-event recurrence in dow-uap corpus** — d62 is the first EMI-event-bearing artifact. Does the EMI segment recur within or outside the 482ATKS cluster? If recurrent, the EMI segment is canonical in the USMTF Misrep schema; if isolated to d62, it is the within-cluster outlier akin to d61's formation-track. ^[inferred]
- **Resolve Iranian-EW-emission hypothesis for EMI events** — both EMI events (1248Z + 1414Z) occurred during transit through Iranian-airspace-margin UTM 39R sub-squares + during the same mission as 3 GUARDCALL events. Open-source Iranian-EW-capability references + JSIR ID330412 / ID330414 archive lookups could close the attribution gap. ^[inferred]
- **Decode `1.4g`-redacted Affected System + Frequency** — first §1.4(g) attestations in dow-uap corpus. The portion-redacted fields are classified at the vulnerabilities/capabilities-of-national-security-systems level. ^[inferred] Open-source MQ-9 link-system references (Ku-band / Predator Primary Satellite Link / Predator Surveillance Datalink) might suggest candidate systems. ^[inferred]
- **Test the GUARDCALL DIRECTIVE-tone recurrence pattern** — d62 introduces DIRECTIVE tone at hails #1 + #2; does DIRECTIVE tone recur in future ingests, or is it d62-isolated? If recurrent, the GUARDCALL tone is a per-event variable correlated with controller individual / airspace severity. ^[inferred]
- **Decode `WPTG` acronym** — Houdong / Sina-class Iranian missile patrol boat classification. Open-source IRGCN order-of-battle references would close. ^[ambiguous]
- **Test the page-banner OCR digit-swap alternation pattern at N≥4 Misreps** — d60 (0%) → d61 (14%) → d62 (56%) swap rate is increasing across the cluster. Is this a real per-document trend (newer scans / lower-quality batches) or sample noise? ^[inferred]
- **Test the Block-class-vs-document-class correlation at N≥4 Block-B Misreps** — d61 + d62 = Block B full-Misreps; d60 = Block A full-Misrep. At N=3 the full-Misrep class skews Block B (2-of-3); range-fouler skews Block A (4-of-5). Does this hold at higher N? ^[inferred]
- **Resolve aircrew rotation within 482ATKS** — d60 + d61 = 1st Lt POC + 1st Lt APPROVER; d62 = SSgt POC + SrA APPROVER. The squadron has multiple aircrews flying sorties. ^[inferred] No specific aircrew identification possible (all FOIA-`(b)(6)`-redacted), but the rank pattern suggests at least two distinct shift-of-operators within the cluster. ^[inferred]
- **Test the same-MGRS-square aircraft-and-UAP geometry at N≥2** — d62 is the first same-10-km-square attestation. If recurrent, the bare-FMV sub-class 8 may correlate with co-located observation geometry (the UAP is essentially on the aircraft's sensor footprint at observation time). ^[inferred] If isolated, d62 is a single-datum coincidence.

## See also

- [[entities/dow-uap-foia-release]] — Series-level anchor (d62 is the 16-of-40 ingest, 8th substantive mission-record artifact, **third FULL USMTF Misrep**); confirms fourth top-level mission-report sub-class at N=3
- [[references/dow-uap-pr20-prepublication-clearance-2026-03]] — Series prepublication-clearance cover stamp (10 Mar 2026)
- [[references/dow-uap-d60-mission-persian-gulf-2020-08-08]] — **First FULL USMTF Misrep (Misrep 4592219, 8 Aug 2020); first member of the same-unit triplet d60+d61+d62**; d62 confirms sub-class 8 (bare-FMV-observation) at N=2 with d60 ^closed-by-dow-uap-d62
- [[references/dow-uap-d61-mission-persian-gulf-2020-08-27]] — **Second FULL USMTF Misrep (Misrep 4685903, 26-27 Aug 2020); second member of the same-unit triplet d60+d61+d62, 20 days before d62**; d61's sub-class 9 (formation-track) isolated at N=1 within the cluster (vs sub-class 8 anchored at N=2 d60+d62); shares Block B + 12 AF Det 3 PAROC explicit attestation with d62
- [[references/dow-uap-d38-range-fouler-middle-east-may-2020]] — **First Block B artifact** (range-fouler, 14 May 2020, Persian Gulf coast); d62 triples Block B to N=3 (d38+d61+d62); confirms 3-digit per-page sequential page-stamping at N=3 across single-page + 7-page + 9-page artifacts
- [[references/dow-uap-d56-range-fouler-arabian-sea-august-2020]] — Range-fouler 24 Aug 2020 North Arabian Sea HSM-73 MH-60R; **sister Arabian-Sea-sub-theater artifact 23 days before d62**; both passive maritime surveillance over CENTCOM AOR; opposite Block allocations (d56 Block A, d62 Block B)
- [[references/dow-uap-d44-range-fouler-arabian-sea-october-2020]] — Range-fouler 15 Oct 2020 Gulf of Aden 172 ATKS MQ-9; **same MQ-9 platform-class as d62, 29 days after d62**; different document class (range-fouler-debrief vs full-Misrep) + different unit (ANG 172 ATKS vs Active 482ATKS)
- [[references/dow-uap-d58-range-fouler-debrief-2020-10]] — Range-fouler 27 Oct 2020 77 EFS CENTCOM
- [[references/dow-uap-d4-mission-arabian-gulf-2020]] — Single-segment GENTEXT/UAP extract — kinematic-anomaly sub-class
- [[references/dow-uap-d5-mission-arabian-gulf-2020]] — Two-sighting GENTEXT/UAP extract
- [[references/dow-uap-d7-mission-arabian-gulf-2020]] — Form-driven GENTEXT/UAP extract with TFLIR fire-control engagement-pipeline + 48FW USAF cross-reference
- [[references/dow-uap-d54-mission-mediterranean-sea]] — Triangular-and-metallic GENTEXT/UAP extract over Aegean Sea
- [[references/dow-uap-d8-mission-djibouti-2025]] — Round-white-hot GENTEXT/UAP extract; FIN+SWE+FVEY+NATO release authorization
- [[references/dow-uap-d55-mission-syria-2016-11-18]] — CTG-narrative mission report (P-8A / TF 67.1, 18 Nov 2016)
- [[references/dow-uap-d52-email-na-2024]] — Email-correspondence class (15 AF / DET 1 PAROC IDAT)
- [[references/dow-uap-d50-email-indopacom-2025-04]] — Email-correspondence class (12 AF / DET 3 PAROC/PAROL); **d62 + d61 explicit clean-OCR PAROC at 12 AF / DET 3 decisively resolve d50's PAROL OCR ambiguity in favor of PAROC** ^closed-by-dow-uap-d62
- [[concepts/uap-aircraft-engagement]] — Behavioral framing; d62 confirms sub-class 8 (FMV-observation + zero-mission-impact-on-UAP + kinematics-blank + morphology-blank) at N=2 with d60; sub-class 9 (formation-track) isolated at N=1 (d61); mission-report UAP-datum counter increments N=7→N=8 records / 8→9 datums
- [[concepts/orb-phenomenon]] — Adjacent; d62 is morphology-blank
- [[concepts/range-fouler]] — Adjacent; d62 is full-Misrep not range-fouler, but Block B sister d38 is
- [[entities/aaro]] — d62 `Approved for Release to AARO` stamp recurrence (8th in corpus); firms AARO as dow-uap receiving authority
- [[projects/uap/uap]]
