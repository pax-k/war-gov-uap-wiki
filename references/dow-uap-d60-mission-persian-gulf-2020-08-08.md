---
title: "DoW-UAP-D60 — Full Misrep 4592219 (482ATKS / 432 AEW MQ-9, 8 Aug 2020, Arabian Gulf)"
category: references
tags: [uap, primary-source, declassified, usaf, sighting]
aliases: [DoW-UAP-D60, dow-uap-d60]
sources: [sources/dow-uap-d60-mission-report-persian-gulf-august-2020.json]
summary: 6-page Mistral-OCR'd Misrep 4592219 — first FULL USMTF mission report in dow-uap corpus; 8 Aug 2020 NAVCENT support over Arabian Gulf, Strait of Hormuz, Gulf of Oman; 482ATKS / 432 AEW MQ-9 ^[inferred]; single GENTEXT/OBSERVATION UAP datum at 0726Z IVO 39RWL08; Iranian Air Defense GUARDCALL at 1250Z.
provenance:
  extracted: 0.60
  inferred: 0.35
  ambiguous: 0.05
base_confidence: 0.78
lifecycle: draft
lifecycle_changed: 2026-05-11
created: 2026-05-11T23:50:00Z
updated: 2026-05-12T01:00:00Z
event_date: 2020-08-08
project: uap
---

# DoW-UAP-D60 — Full Misrep 4592219 (482ATKS / 432 AEW MQ-9, 8 Aug 2020, Arabian Gulf)

A **6-page Mistral-OCR'd artifact** (`sources/dow-uap-d60-mission-report-persian-gulf-august-2020.json`, 8,480 bytes; SHA-256 `59390e95933d13b7…`) — the **fourteenth artifact** in the [[entities/dow-uap-foia-release|DoW-UAP FOIA release series]] (14-of-40) and the **first FULL USMTF Mission Report (Misrep) ingest** in the corpus. d60 is structurally distinct from every prior mission-record ingest: all 6 pages are substantive (zero header-only padding), and the document carries the **complete USMTF mission-report segment set** (Narrative + Admin/Classification/Operation + MSGID + MSNID + POC + QC + APPROVER + INGEST + ACEQUIP + Timeline with Landing/GUARDCALL/OBSERVATION/Takeoff/On Station/ISR/Off Station sub-segments + multiple GENTEXT segments + WEATHER + EFFECTIVENESS). d60 is therefore the **parent multi-segment Misrep document** of which d4/d5/d7/d8/d54 (single-segment GENTEXT/UAP extracts on 1 substantive page) are excerpts. ^[inferred]

The d60 ingest **anchors a third top-level mission-report sub-class** in the dow-uap corpus alongside the USMTF GENTEXT/UAP single-segment extract sub-class (d4/d5/d7/d8/d54) and the CTG-narrative format ([[references/dow-uap-d55-mission-syria-2016-11-18|d55]]): **full multi-segment USMTF Misrep**. ^[inferred] The class shift is **the headline finding** of the d60 ingest.

## What the source actually contains

The OCR pulls **6 pages**, each `dpi: 93`, all carrying explicit per-page declassification banners and **all substantive** (zero header-only `# 1.4(a)` padding pages — a structural break from the d4/d5/d7/d8/d54 GENTEXT/UAP extract template). Every page also carries the explicit `(b)(6)` redaction block + `USCENTCOM MDR 26-0038 to MDR 26-0046` + `Approved for Release to AARO` + `03/27/26 00000N` (where N is the page index 1–6).

**Page-top metadata block (recurring on every page):**

```
Declassified by MG Richard A. Harrison
USCENTCOM Chief of Staff
Declassified on: 20 March 2026
```

**Page-bottom release block (recurring on every page, with N = page index):**

```
(b)(6)

USCENTCOM MDR 26-0038 to MDR 26-0046
Approved for Release to AARO
03/27/26 00000N
```

The release-sequence number runs **`000001` (page 0) → `000006` (page 5)** — see *Release framework — closes 000001 ambiguity* below.

**Substantive content by page:**

| Page | Substantive segments |
|---|---|
| 0 | Document header `# Misrep 4592219` + `## Narrative` (free-text BLUF-equivalent) + `## Admin` (CLASSIFICATION + OPERATION + MSGID + MSNID start) |
| 1 | MSNID continuation (Mission Type / ATO Mission Number / Country Tasked / Service Tasked) + `## Poc` (POC + QC + APPROVER + INGEST blocks) |
| 2 | INGEST continuation + `# ACEQUIP` (full aircraft-equipment block: radar / RWR / MWS / IRCM / ECM / CMD / chaff / flare / decoys / AAM / gun / A-G weapon / TGT pod / data link) |
| 3 | Gentext (top) + `# Timeline` (Landing + GUARDCALL + GENTEXT/GUARDCALL + OBSERVATION start) |
| 4 | OBSERVATION fields + **`## GENTEXT/OBSERVATION`** (the substantive UAP datum) + WEATHER + Takeoff + On Station + ISR start |
| 5 | ISR continuation + `## GENTEXT/ISR` (mission-narrative) + ISR ASSET UTILIZATION + WEATHER + EFFECTIVENESS + Off Station |

**The substantive UAP datum is in `GENTEXT/OBSERVATION`, not `GENTEXT/UAP`** — a structural distinction from d4/d5/d7/d8/d54 (all `GENTEXT/UAP` headers). ^[inferred] See *UAP datum* and *Segment-name distinction* below.

## The UAP datum

The single UAP observation appears in the `GENTEXT/OBSERVATION` segment on page 4:

```
## GENTEXT/OBSERVATION

- Gentext: AT 0726Z, 1.4a OBSERVED 1X UAP IVO 39RWL08 1.4a 2 1.4a NO IMPACT TO MISSION.
```

The corresponding structured OBSERVATION block (page 3 → 4) supplies the surrounding geometry:

| Field | Value | Notes |
|---|---|---|
| Observation DTG | **080726:00ZAUG20** | **8 Aug 2020 at 0726Z** — first explicit calendar-date + UTC-time anchor on a UAP datum in the dow-uap mission-report sub-class (d4/d5/d7/d8/d54 carried Zulu times only, no calendar dates; d55 had Nov 2016; d50 had Apr 2025). ^[inferred] |
| Aircraft Callsign | **1,4a** | Portion-redacted under EO 13526 §1.4(a). |
| Aircraft Location | **39RWK95 1,4a 53 1,4a** | MGRS coordinate, partially portion-redacted; UTM zone 39R covers Persian Gulf / Strait of Hormuz / Gulf of Oman corridor. ^[inferred] |
| Aircraft Heading / Altitude / Airspeed | (all blank) | Witness-aircraft kinematic state not preserved on the OBS line. |
| Observed Activity Location | **39RVL90 1,4a 53 1,4a** | UAP position MGRS, also partially redacted; same UTM 39R zone. ^[inferred] |
| Observed Activity Description | **TRANSITTING** | (OCR "TRANSITTING" — almost certainly **TRANSITING** with single T). ^[inferred] First explicit `TRANSITING` activity descriptor in the dow-uap mission-report sub-class. |
| Method of Observation | **FMV** | **Full Motion Video** — first explicit FMV method-of-observation token in the dow-uap corpus. ^[inferred] Compatible with MQ-9 MTS-B / DGS-exploited FMV streams. |
| GENTEXT/OBSERVATION | `AT 0726Z, 1.4a OBSERVED 1X UAP IVO 39RWL08 1.4a 2 1.4a NO IMPACT TO MISSION.` | The body datum. Position `39RWL08` differs from both the aircraft position `39RWK95` (KW square) and the Observed Activity Location `39RVL90` (VL square). The three MGRS positions describe **two different 100-km grid squares** (WK / WL / VL) all in zone 39R. ^[inferred] |

**Single object, single observation, no morphology descriptor, no UAP-side kinematics, no encounter-duration timestamp** — kinematically thin, morphologically blank record. The signature is **a brief FMV-observed transit** with explicit zero-mission-impact attestation. ^[extracted] No interaction posture; no closure attempt; no engagement.

## Segment-name distinction — `GENTEXT/OBSERVATION` vs `GENTEXT/UAP`

The d60 substantive UAP datum lives in a `GENTEXT/OBSERVATION` segment, distinct from the d4/d5/d7/d8/d54 `GENTEXT/UAP` segment header. Two complementary readings:

1. **Full-Misrep vs extracted-segment**: d60 is the **complete USMTF mission report**; `GENTEXT/OBSERVATION` is the canonical USMTF observation segment (paired with the structured `## OBSERVATION` field block on pages 3–4). ^[inferred] The d4/d5/d7/d8/d54 extracts carry **only** the `GENTEXT/UAP` segment header — likely a curator-derived segment-name applied when the UAP datum was extracted from a parent Misrep for separate release. ^[inferred] Under this reading, **d4/d5/d7/d8/d54's `GENTEXT/UAP` is the curator's rename of `GENTEXT/OBSERVATION` content**, applied at release-time to flag the UAP nature of the extracted segment.
2. **Two distinct USMTF report variants**: some Misreps use `GENTEXT/UAP` natively (Navy F/A-18 / fighter community) and others use `GENTEXT/OBSERVATION` (USAF MQ-9 / ISR community). ^[inferred] Under this reading, the segment-name reflects the **originating-service convention**, with no curator intervention.

**Reading 1 is operationally most coherent** at N=1 ingest of full-Misrep class: the d60 Misrep carries a `Gentext: -` placeholder on page 3 (top of Timeline) indicating the canonical Gentext field is unused for non-event-text purposes, and the substantive UAP narrative lives in the appended `GENTEXT/OBSERVATION` sub-segment. If d4/d5/d7/d8/d54 are extracts of similar parent Misreps, the curator likely re-labeled the segment from `GENTEXT/OBSERVATION` (USMTF-internal) to `GENTEXT/UAP` (UAP-flag-at-release). ^[inferred] To be tested against future full-Misrep ingests.

**Mission-report UAP-datum counter implication** — the counter on [[concepts/uap-aircraft-engagement|concepts/uap-aircraft-engagement.md]] currently reads `N=5 GENTEXT/UAP reports / 6 datums`. At N=6 with d60 the counter becomes **N=6 mission-report UAP-datum records / 7 datums** (renamed framing) — see § Behavioral classification below for the sub-class assignment.

## Platform attribution — 482ATKS / 432 AEW / 603 AOC / 609 CAOC MQ-9 Reaper ^[inferred]

The d60 POC block (page 1) supplies the **first internally-preserved unit-attribution chain** in the dow-uap mission-report sub-class:

| Role | Unit | Inferred decoded entity |
|---|---|---|
| **POC** | `482ATKS` / `432 AEW` / `603 AOC` | **482d Attack Squadron** (USAF) — MQ-9 Reaper community ^[inferred]; under **432d Air Expeditionary Wing** (Creech AFB-anchored deployed MQ-9 wing) ^[inferred]; **603rd Air and Space Operations Center** (Ramstein-based for USAFE/AFRICOM, but the form's `603 AOC` placement under USCENTCOM COCOM ^[inferred] suggests USCENTCOM-AOR MQ-9 ops centre, plausibly a 609th sub-element). ^[ambiguous] |
| **QC** | `PAROC IDAT` / `Other` | **PAROC** = same Intel-Data-Analysis-Technician role first attested in [[references/dow-uap-d52-email-na-2024|d52]] (PAROC at 15 AF / DET 1); **IDAT** = Intel Data Analysis Technician (recurring d52 + d50 attestation). ^[inferred] First QC-block attestation of PAROC in the dow-uap mission-report sub-class. |
| **APPROVER** | `609th AOC` / `Other` / `609 CAOC` | **609th Air and Space Operations Center / 609th Combined Air Operations Center** — the USAF/USCENTCOM theater AOC at Al Udeid AB, Qatar. ^[inferred] The **609 CAOC anchors the USCENTCOM/AFCENT air operations centre** for the Persian Gulf / Levant theaters. First explicit 609th AOC attestation in the dow-uap corpus. |

**Six lines of internal evidence corroborate the MQ-9 Reaper reading** ^[inferred]:

1. **20.3 mission hours** (Narrative §1) — RPA-class persistent ISR loiter time; consistent with MQ-9 endurance envelope (~27–30 hrs). Manned fighter sortie hours are ~4–8 hr maximum even with refueling.
2. **18.4 SIGINT hours + 17.7 IMINT hours + AIRHANDLER + DGS1 FMV exploitation** — DGS1 (Distributed Common Ground System Site 1, at Langley AFB, the USAF/ISR PED node) processes FMV streams from MQ-9 / RQ-4 / U-2 platforms. ^[inferred] **First DGS1 attestation in the dow-uap corpus** ^[inferred]; the AIRHANDLER SIGINT capability is an MQ-9 / RC-135 ISR signature. ^[inferred]
3. **AREC mission type** — **Armed Reconnaissance** (USAF mission-type designator) ^[inferred]; consistent with MQ-9 mission profile.
4. **TGT pod `ANDAS4`** + **Additional Avionics `AH_GMESH`** — **ANDAS4** is plausibly **AN/DAS-4** (the L3Harris MS-177 / DAS-4 SAR/EO/IR sensor family used on MQ-9 ER/Block-5) ^[inferred]; **AH_GMESH** is plausibly an AirHandler GMESH ^[inferred] sub-payload (the AIRHANDLER ISR/SIGINT mention in the Narrative supports this). Multiple readings live ^[ambiguous]; resolution requires open-source MQ-9 sensor-suite tables.
5. **OKAS** ICAO = **Ali Al Salem Air Base, Kuwait** ^[inferred] — a USAFCENT MQ-9 launch/recovery node in CENTCOM AOR. Takeoff and landing from OKAS at 080337Z and 090045Z respectively (UTC; 21h 8min total mission time) anchors the MQ-9 reading at the launch-base level.
6. **Tasked supporting NAVCENT to Operation 1,4a** in `IVO ARABIAN GULF, STRAIT OF HORMUZ AND GULF OF OMAN` — a USAFCENT 432 AEW MQ-9 task in support of US Naval Forces Central Command. ^[inferred] Consistent with the Kuwait-launched MQ-9 supporting USNAVCENT 5th Fleet maritime-surveillance / pattern-of-life tasking.

**Open-source corroboration**: 432 AEW is the USAF parent expeditionary wing for forward-deployed MQ-9 operations; 482ATKS as a 432 AEW deployed squadron in 2020 is a plausible reading but not directly attested in OCR. ^[inferred] PAROC/IDAT role anchored at d52 (15 AF / DET 1) + d50 (12 AF / DET 3 — there spelled PAROL); d60 anchors the **fourth USAF Active-component unit** with PAROC/IDAT QC at 482ATKS / 432 AEW.

## Iranian Air Defense GUARDCALL — first foreign-state direct hail in the dow-uap corpus

Page 3 carries an explicit **GUARDCALL** structured block + `GENTEXT/GUARDCALL` segment documenting a foreign-state radio hail of the aircraft:

| Field | Value | Notes |
|---|---|---|
| GUARDCALL DTG | **081250:00ZAUG20** | 8 Aug 2020 at 1250Z — ~5 hr 24 min after the UAP OBS event (0726Z). |
| Aircraft Callsign | `1,4a` | Portion-redacted. |
| Ground Station Callsign | **IRANIAN AIR DEFENSE GUARD** | **First explicit foreign-state direct-hail attribution in the dow-uap corpus.** ^[inferred] Iranian Air Defense ground station challenges the MQ-9 over **243.0 / 121.5 MHz** UHF/VHF Guard frequency. ^[inferred] |
| Aircraft Location | `40RCP98 1,4a 97 1,4a` | **MGRS UTM zone 40R** — the **eastern Persian Gulf / Strait of Hormuz / Gulf of Oman corridor** (zone 40 covers longitudes 54°E–60°E, latitude band R covers 24°N–32°N) ^[inferred]. **DIFFERENT MGRS zone from the OBS event** (UTM 39R) — the MQ-9 had transited from UTM 39R westward-Persian-Gulf to UTM 40R eastward-Persian-Gulf in the ~5 hr between events. ^[inferred] |
| Aircraft Heading | **HDG 200** | Southerly (slightly W of S). |
| Aircraft Altitude | **FL 170** | Flight Level 170 = 17,000 ft pressure altitude. Within the MQ-9 cruise envelope. ^[inferred] |
| Aircraft Airspeed | **110 KIAS** | Knots Indicated Airspeed; consistent with MQ-9 cruise speed at FL170. ^[inferred] |
| Number of Calls Noted from the Same Agency | **1** | Single hail. |
| Guardcall Tone | **PROFESSIONAL** | First explicit GUARDCALL Tone descriptor in the dow-uap corpus. |
| GENTEXT/GUARDCALL | `AT 1250Z, 1,4a WAS HAILED ON GUARD 1,4a BY IRANIAN AIR DEFENSE. ORDERS GIVEN: STANDARD CALL. 1,4a RESPONDED STANDARD RESPONSE. NO IMPACT TO THE MISSION` | Standard call-response exchange. |

**Operational significance**: the GUARDCALL event documents Iranian Air Defense surveillance of a US ISR asset operating in or near Iranian-claimed airspace in the eastern Persian Gulf / Strait of Hormuz region. ^[inferred] The encounter is **routine** (`PROFESSIONAL` tone, single call, standard exchange, no mission impact) but **politically significant**: it is the **first explicit foreign-state direct radio hail of a US asset** in the dow-uap corpus, and it places the d60 mission inside a contested-airspace operational context. ^[inferred] The Strait of Hormuz region in 2020 was a high-tension Iran-vs-US maritime confrontation zone (Operation Sentinel / International Maritime Security Construct anchored at the 5th Fleet response to Iranian harassment of merchant shipping). ^[inferred]

**The GUARDCALL is the second-most-novel d60 finding** after the full-Misrep class anchor. ^[inferred]

## Mission timeline — the full operational picture

The d60 Misrep narrative + Timeline segments reconstruct the **complete 21h 8min mission cycle** (first complete operational timeline in the dow-uap corpus):

| Time (Z) | Event | Source |
|---|---|---|
| **080337:00Z** | Takeoff from OKAS (Ali Al Salem AB, Kuwait ^[inferred]) | Takeoff block + Narrative |
| **080359:00Z** | Handed over from LRE (Launch and Recovery Element) — first explicit LRE attestation in dow-uap corpus ^[inferred] | Narrative |
| **080434:00Z** | Started SIGINT collection via AIRHANDLER | Narrative |
| **080513:00Z** | Arrived on station ISO NAVCENT, Operation 1,4a (IVO Arabian Gulf, Strait of Hormuz, Gulf of Oman) | On Station + ISR blocks + Narrative |
| **0726Z** | **UAP observation — see § The UAP datum above** | GENTEXT/OBSERVATION |
| **1250Z** | **Iranian Air Defense GUARDCALL — see § Iranian Air Defense GUARDCALL above** | GUARDCALL block |
| **082256:00Z** | Cleared off tasking; RTB | ISR + Off Station blocks + Narrative |
| **090017:00Z** | Handed back to LRE | Off Station block + Narrative |
| **090045:00Z** | Landed at OKAS | Landing block + Narrative |
| **090055:00Z** | Last engine shutdown | Landing block |
| (totals) | **21h 8min mission time / 20.3 mission hr / 17.7 IMINT hr / 18.4 SIGINT hr / 1 IMINT tasking / 1 SIGINT tasking / 2 total taskings** | Narrative |

**Structural firsts in operational-detail capture** (vs prior dow-uap mission reports d4/d5/d7/d8/d54, none of which preserve more than the single UAP-event Zulu timestamp):

- **First complete mission timeline** (takeoff → handover → on station → events → RTB → handback → landing → shutdown) — 8 distinct DTG anchors vs prior single-Zulu records. ^[inferred]
- **First LRE (Launch and Recovery Element) attestation** — the MQ-9 split-operation model (forward-deployed LRE flies takeoff/landing; CONUS or other forward MOC flies en route + on-station). ^[inferred]
- **First mission-hours-and-taskings utilization breakout** (20.3 / 17.7 / 18.4 hr; 1 IMINT + 1 SIGINT taskings). ^[inferred]
- **First explicit DGS-PED attribution** — FMV exploited by DGS1. ^[inferred]
- **First explicit ISR PED-and-collection mission framework** in the dow-uap corpus. ^[inferred]

## Geographic decoding — `persian-gulf` filename ↔ `ARABIAN GULF` body MATCH

The filename token `persian-gulf` (curator-applied) corresponds to the body-text reference `ARABIAN GULF` (operationally USCENTCOM/DoD-preferred nomenclature). **The two terms refer to the same body of water** — the political naming distinction is between international convention (Persian Gulf) and US/Iran political framing (Arabian Gulf, used by US DoD since the 1990s in deference to Gulf Cooperation Council allies). ^[inferred] **Filename ↔ body MATCH** at the theater level.

The narrative explicitly names **`IVO ARABIAN GULF, STRAIT OF HORMUZ AND GULF OF OMAN`** as the operational area — three adjoining bodies of water bounded by the Arabian Peninsula (Saudi Arabia / UAE / Oman) on the west/south and Iran on the north/east. ^[inferred] The internal MGRS coordinates supplement this:

| MGRS | UTM Zone | Inferred sub-region |
|---|---|---|
| **39RVN34 1,4a 32 1,4a** (Tasked Start Point, ISR block) | 39R (UTM zone 39, lat band R = 24°N–32°N; longitudes 48°E–54°E) | Persian Gulf / Strait of Hormuz western margin ^[inferred] |
| **39RWK95 1,4a 53 1,4a** (Aircraft Location, OBS block) | 39R, square WK | Persian Gulf interior ^[inferred] |
| **39RVL90 1,4a 53 1,4a** (Observed Activity Location, OBS block) | 39R, square VL | Persian Gulf interior, west of aircraft ^[inferred] |
| **39RWL08 1,4a 2 1,4a** (GENTEXT/OBSERVATION body coord) | 39R, square WL | Persian Gulf interior, between aircraft and target ^[inferred] |
| **40RCP98 1,4a 97 1,4a** (Aircraft Location, GUARDCALL block) | 40R (UTM zone 40, lat band R; longitudes 54°E–60°E) | Eastern Persian Gulf / Strait of Hormuz approach ^[inferred] |

**All five MGRS coordinates decode inside the explicit body-text operational area** (Arabian Gulf / Strait of Hormuz / Gulf of Oman corridor across UTM zones 39R + 40R). ^[inferred] This is the **first mission-report ingest in the corpus with internal-coordinate verification of the curator filename theater label**.

**Filename-axis verification record at N=6 testable mission-reports**:

| File | Filename theater | Internal anchor | Decoded region | Match? |
|---|---|---|---|---|
| `d4` | `arabian-gulf` | MGRS `34SDG…` | UTM 34S — Eastern Med | **NO** |
| `d5`-A | `arabian-gulf` | MGRS `34SCE…` | UTM 34S — Eastern Med | **NO** |
| `d5`-B | `arabian-gulf` | MGRS `35TQK…` | UTM 35T — E Europe / Black Sea | **NO** |
| `d7` | `arabian-gulf` | bearing `323'S` only | UNDECIDABLE | n/a |
| `d54` | `mediterranean-sea` | DMS `363453N 0255943E` | Aegean Sea (Cyclades) | **YES** |
| `d8` | `djibouti` | MGRS `35SQT…` | Eastern Mediterranean | **NO** |
| `d55` | `syria` | "55 NM NW of Latakia" | Eastern Med coast of Syria | **YES** |
| **`d60`** | **`persian-gulf`** | **MGRS `39R*` + `40R*` + body `ARABIAN GULF`** | **Persian / Arabian Gulf, Strait of Hormuz, Gulf of Oman** | **YES** |

**d60 is the first `*-arabian-*`-class filename token in the corpus to verify at the internal-coordinate level.** ^[inferred] Three readings of the prior d4/d5 "Arabian Gulf"-mismatch pattern now require revision:

1. **Curator-mis-label hypothesis (prior reading)**: the curator applied "Arabian Gulf" as a default label to Eastern-Mediterranean reports. **Partially refuted** — d60 confirms that a "Persian Gulf"-labeled Misrep can correctly decode to the Persian/Arabian Gulf. ^[inferred] But d4/d5's "Arabian Gulf" labels remain mismatched.
2. **Token-distinction hypothesis (new at d60)**: `persian-gulf` (d60) and `arabian-gulf` (d4/d5/d7) may be **different curator tokens** despite naming the same body of water — `persian-gulf` for genuinely Persian/Arabian Gulf reports, `arabian-gulf` for the broader (and possibly Mediterranean-mislabeled) artifacts. ^[inferred] To be tested against any future `arabian-gulf`-labeled ingest with internal coordinates.
3. **Extract-vs-full-Misrep hypothesis (new at d60)**: d60 is a full Misrep with multiple internal coordinates; d4/d5/d7 are single-segment extracts with no internal coordinate context. The "Arabian Gulf"-mismatch may be an artifact of the **extraction process**, not of the curator-applied label — the parent Misreps may originally have decoded to the Eastern Mediterranean, and the curator filename token "Arabian Gulf" is honest at the parent-document level. ^[inferred]

**Reading 3 is operationally most coherent given the d60 ingest** ^[inferred]: full-Misrep d60 verifies its filename token; single-extract d4/d5 contain only a UAP-event MGRS coord that may be from a different operational area than the parent Misrep's primary AOR. To be tested.

**Filename-date axis**: filename `august-2020` ↔ body `080726:00ZAUG20` + `081250:00ZAUG20` + `090045:00ZAUG20`. **MATCH at the month level** ^[inferred] — body events span 8–9 Aug 2020 mission cycle.

## Release framework — Block A firms to 5-of-6; closes `000001` ambiguity

The d60 release block on every page matches d55 / d58 / d44 / d56 Block A on the four shared axes:

| Field | Block A (d55/d58/d44/d56) | d60 | Match? |
|---|---|---|---|
| Declassification authority | MG Richard A. Harrison | MG Richard A. Harrison | **MATCH** |
| MDR case | `26-0038 to MDR 26-0046` (9-case range) | `26-0038 to MDR 26-0046` | **MATCH** |
| Routing stamp | Approved for Release to AARO | Approved for Release to AARO | **MATCH** |
| Release-stamp date | `03/27/26` | `03/27/26` | **MATCH** |
| **Release sequence #** | `000001` (always — d55/d58/d44/d56 each single-page) | **`000001 → 000006`** (one per page, sequential) | **EXTENDS** |

**Critical finding — closes the `000001` open question**: d55 / d58 / d44 / d56 each carry the literal `000001` 6-digit sequence number, leading to three competing readings (per-batch / per-MDR-case / OCR-artifact) at N=4 attestations. d60 is a **6-page document carrying sequential `000001 → 000006`** — one per page, monotonic ascending. This **decisively confirms the per-document page-sequence-number reading**: each page of a multi-page release artifact gets a sequential page-stamp; single-page artifacts carry only `000001`. ^[inferred] The OCR-artifact reading is **definitively rejected**. The per-MDR-case reading is **refined** to per-document-page-sequence within an MDR case allocation. ^[inferred]

**Findings flowing from the d60 release-block confirmation**:

1. **Block A firms to 5-of-6** release-block-testable artifacts (d55 + d58 + d44 + d56 + d60); d38's Block B (`26-0019` + `01/26/26 001`) remains isolated at 1-of-6. The asymmetric Block-A-dominant allocation strengthens. ^[inferred]
2. **`000001` ambiguity decisively closed** — per-document-page-sequence reading is correct. d56 / d44 / d58 / d55 were all single-page artifacts carrying the natural page-1 stamp; d60 is the first multi-page artifact within Block A demonstrating sequential page-stamping.
3. **AARO-receiving-authority closure firms further at N=6 stamp-recurrence** across the corpus. ^[inferred]
4. **9-case MDR range `26-0038 to 26-0046`** now covers 5 documents (d55 + d58 + d44 + d56 + d60). At N=5 documents in 9 cases, the per-MDR-case reading holds with room for 4 additional documents in the same range. ^[inferred]

## Behavioral classification — N=6 mission-report UAP-datum counter increment

Per the [[concepts/uap-aircraft-engagement|UAP–Aircraft Engagement]] framework:

- **UAP-toward-aircraft engagement-class**: **negative datum** — no close approach (MGRS positions differ; no co-location); no target switching; no phase-of-flight correlation; explicit `NO IMPACT TO MISSION` clause. The d60 UAP is observed at a separate MGRS coord from the witness aircraft and described as `TRANSITTING` — no engagement signature.
- **Aircraft-toward-UAP engagement-pipeline**: **negative datum** — no weapons-quality track, no NTS, no TFLIR ID, no closure attempt. The MQ-9 observed via FMV (MTS-B EO/IR turret stream); passive FMV observation only.
- **Sub-class within brief-observation**: **kinematics-blank + morphology-blank with explicit FMV method + zero-mission-impact** — a new behavioral signature **distinct from prior brief-observation sub-classes** ^[inferred]:
  - Distinct from `kinematic-anomaly` (d4 + d5-B + d8): no UAP-side speed or heading reported.
  - Distinct from `steady-state cruise` (d5-A): no constant-velocity datum.
  - Distinct from `prosaic-candidate wind-borne` (d7): no morphology call.
  - Distinct from `morphology-rich kinematics-thin` (d54): no morphology call.
  - Distinct from `prosaic-candidate-with-explicit-CTG-identification` (d55): no prosaic identification posture.
  - **Anchors an eighth distinct brief-observation sub-class**: **kinematics-blank + morphology-blank + FMV-observation + ISR-mission-context + zero-mission-impact**. ^[inferred] The signature is **a bare observational record** — the UAP is logged on the OBS line because it was detected, but no kinematic or morphological data justifies a richer entry. The framing inverts the d4–d8 pattern: prior records carry rich UAP-side data (kinematics or morphology) in a thin Misrep extract; d60 carries thin UAP-side data in a rich full-Misrep parent document.

**Mission-report UAP-datum counter increments N=5 → N=6** at the dow-uap level. ^[inferred] The counter framing on [[concepts/uap-aircraft-engagement|concepts/uap-aircraft-engagement]] needs renaming from `GENTEXT/UAP reports` to **`mission-report UAP-datum records`** to accommodate d60's `GENTEXT/OBSERVATION` segment-name (see § Segment-name distinction). The 7th datum (one new datum from d60) brings the total to **6 mission-report records / 7 datums**.

## Bibliographic frame

| Field | Value |
|---|---|
| Source basename | `dow-uap-d60-mission-report-persian-gulf-august-2020.json` |
| Source bytes | 8,480 |
| Content SHA-256 | `59390e95933d13b79b3a55077e204df1527d106615043aa01c71668445a09c93` |
| OCR engine | `mistral-ocr-latest` ^[inferred] (series-wide pattern) |
| Pages OCR'd | **6 substantive pages (zero header-only)** — first all-substantive multi-page Misrep in dow-uap corpus |
| Document class | **Full USMTF Misrep — multi-segment** (Narrative + Admin + MSGID + MSNID + POC + QC + APPROVER + INGEST + ACEQUIP + Timeline {Landing + GUARDCALL + OBSERVATION + Takeoff + On Station + ISR + Off Station} + multiple GENTEXT + WEATHER + EFFECTIVENESS) |
| Document subclass | **New mission-report sub-class** — anchors third top-level mission-record class alongside USMTF GENTEXT/UAP extracts (d4/d5/d7/d8/d54) and CTG narrative (d55) |
| Misrep identifier | **Misrep 4592219** — first explicit Misrep ID in dow-uap corpus ^[inferred] |
| Classification (top) | Multiple Sources (Classification Source per Admin block); Declassification Date `20450301` (1 Mar 2045) ^[inferred] |
| Classification authority | EO 13526 §1.4(a) per-page ^[inferred]; `(b)(6)` redaction recurring |
| Release-block classification | **Block A** (Harrison + USCENTCOM MDR `26-0038 to 26-0046` + AARO + `03/27/26`) — 5th attestation of Block A in corpus |
| Release-sequence | **`000001 → 000006`** (per-page sequential across 6 pages) — **closes the `000001` open question** ^[inferred] |
| Receiving authority | **AARO** (`Approved for Release to AARO`) |
| Originating service | **US Air Force** (Service Tasked `A - AIR FORCE`; Country Tasked `US - UNITED STATES`) |
| Originating MAJCOM | **ACC** (Air Combat Command) |
| Originating COCOM | **USCENTCOM** |
| Originating Operations Center | **609th** (per Operation block); **609 CAOC** (per APPROVER block) — first 609 AOC / 609 CAOC anchor in dow-uap corpus ^[inferred] |
| Originating unit (POC) | **482ATKS / 432 AEW / 603 AOC** — 482d Attack Squadron / 432d Air Expeditionary Wing / 603rd AOC ^[inferred] |
| Witness platform | **MQ-9 Reaper** ^[inferred] (20.3 mission hr + AIRHANDLER SIGINT + DGS1 FMV exploitation + ANDAS4 ^[inferred] MS-177/DAS-4 sensor family + OKAS Kuwait launch) |
| Mission type | **AREC** (Armed Reconnaissance) ^[inferred] |
| Tasking Order | **BP** (Battle Plan / numbered ATO) ^[inferred] |
| Supported unit | **NAVCENT** (US Naval Forces Central Command, 5th Fleet) ^[inferred] |
| Supported operation | `OPERATION 1,4a` (portion-redacted) |
| LRE (Launch and Recovery Element) attestation | **First in dow-uap corpus** ^[inferred] |
| DGS1 attribution | **First Distributed Common Ground System Site 1 attestation in dow-uap corpus** ^[inferred] |
| AIRHANDLER attribution | **First AIRHANDLER SIGINT-payload attestation in dow-uap corpus** ^[inferred] |
| Series | [[entities/dow-uap-foia-release\|DoW-UAP FOIA release]] |
| Series position | **14-of-40** by ingest order (6th substantive mission report; first full Misrep) |
| Event date | **8 Aug 2020** (UAP OBS at 080726Z; GUARDCALL at 081250Z; mission cycle 080337Z–090045Z) — body-text date verifies filename `august-2020` |
| Event night/day | Daytime in Arabian Gulf local (UTC+3/+4: 0726Z = ~10:26–11:26 local AM) ^[inferred] |
| Theater | **Arabian / Persian Gulf, Strait of Hormuz, Gulf of Oman** (UTM zones 39R + 40R) — body-text + MGRS-coordinate verified at 5-of-5 coords |
| Object count | 1 |
| Object morphology | *not reported* — first morphology-blank d* mission report since d4/d5 |
| UAP-side kinematics | *not reported* — `TRANSITTING` activity descriptor + FMV method only |
| Encounter duration | Not quantified ("brief") |
| Iranian Air Defense GUARDCALL | **First explicit foreign-state direct-hail attribution in dow-uap corpus** ^[inferred] — 081250Z; tone `PROFESSIONAL`; standard exchange |

## Structural firsts the d60 ingest anchors

d60 introduces or extends the following in the dow-uap corpus (now N=14 ingests):

1. **First FULL USMTF Misrep ingest** — all 6 pages substantive; complete multi-segment structure (Narrative + Admin + MSGID + MSNID + POC + QC + APPROVER + INGEST + ACEQUIP + Timeline {7 sub-segments} + multiple GENTEXT + WEATHER + EFFECTIVENESS); anchors a **third top-level mission-record sub-class** in the corpus (alongside USMTF GENTEXT/UAP single-segment extracts and CTG narrative). ^[inferred] **Headline finding.**
2. **First explicit Misrep identifier** — `Misrep 4592219`. ^[inferred]
3. **First multi-page release-sequence-stamping** — `000001 → 000006` sequentially across 6 pages. **Closes the `000001` open question** at N=4 (decisively confirms per-document page-sequence reading; rejects OCR-artifact reading). ^[inferred]
4. **First `GENTEXT/OBSERVATION` segment** for a UAP datum — distinct from d4/d5/d7/d8/d54's `GENTEXT/UAP` extract header; reframes the mission-report-counter terminology. ^[inferred]
5. **First explicit USAF unit attribution for a mission report** in the corpus — `482ATKS / 432 AEW / 603 AOC` POC + `PAROC IDAT` QC + `609 CAOC` APPROVER. Prior mission reports (d4/d5/d7/d8/d54) preserved no unit attribution. ^[inferred]
6. **First explicit operations-center attribution** — 603 AOC + 609th AOC + 609 CAOC — three distinct AOC tokens in a single artifact. ^[inferred]
7. **First explicit 609 CAOC** (Combined Air Operations Center, Al Udeid AB Qatar — USCENTCOM theater air-operations centre) attestation in dow-uap corpus. ^[inferred]
8. **First MAJCOM + COCOM explicit attribution** — `ACC` (Air Combat Command) + `USCENTCOM`. ^[inferred]
9. **First explicit AREC mission type** in dow-uap mission-report sub-class. ^[inferred] (d44 = passive ISR; d56 = SSC; d38 = ISR; d58 = DCA — d60 adds AREC to the dow-uap mission-classification distribution.)
10. **First MQ-9 Reaper on a mission report** — d44 was MQ-9 but in the range-fouler-debrief class. ^[inferred] First USAF / 432 AEW / 482ATKS MQ-9 anchor for a mission-report-class ingest.
11. **First USAF-Active-component (not ANG) MQ-9 anchor** in dow-uap corpus — d44's 172 ATKS is ANG; d60's 482ATKS is Active ^[inferred].
12. **First OKAS (Ali Al Salem AB, Kuwait) launch-base anchor** in dow-uap corpus. ^[inferred]
13. **First LRE (Launch and Recovery Element) attestation** in dow-uap corpus — anchors the MQ-9 split-operation model. ^[inferred]
14. **First DGS1 (Distributed Common Ground System Site 1) PED attribution** in dow-uap corpus — Langley AFB-anchored ISR PED node. ^[inferred]
15. **First AIRHANDLER SIGINT-payload attestation** in dow-uap corpus. ^[inferred]
16. **First ANDAS4 / AH_GMESH TGT-pod and Additional-Avionics attestation** in dow-uap corpus — MS-177 / DAS-4 sensor family ^[inferred] ^[ambiguous]; first sensor-suite naming in the mission-report sub-class.
17. **First explicit FMV (Full Motion Video) method-of-observation token** in dow-uap corpus. ^[inferred]
18. **First explicit `TRANSITTING` activity descriptor** for a UAP datum in dow-uap corpus.
19. **First explicit Iranian Air Defense GUARDCALL** — first foreign-state direct radio hail of a US asset in dow-uap corpus. ^[inferred] **Second-most-novel d60 finding.**
20. **First explicit GUARDCALL DTG / Aircraft Location / Heading / Altitude / Airspeed / Tone fields** captured in dow-uap corpus.
21. **First explicit FL170 + 110 KIAS witness-aircraft state datum** in dow-uap mission-report sub-class — first quantified witness-aircraft cruise envelope.
22. **First multi-segment Timeline structure** in dow-uap corpus — Landing / GUARDCALL / GENTEXT/GUARDCALL / OBSERVATION / GENTEXT/OBSERVATION / WEATHER / Takeoff / On Station / ISR / GENTEXT/ISR / ISR ASSET UTILIZATION / WEATHER / EFFECTIVENESS / Off Station. ^[inferred] 14 distinct Timeline sub-segments.
23. **First complete mission-cycle DTG-anchor set** in dow-uap corpus — 8 distinct DTG anchors (takeoff + handover + on-station + UAP + GUARDCALL + off-station + handback + landing) anchoring a 21h 8min mission cycle.
24. **First quantified mission-hours-and-taskings breakout** — 20.3 mission hr / 17.7 IMINT hr / 18.4 SIGINT hr / 1 IMINT tasking / 1 SIGINT tasking / 2 total taskings. ^[inferred]
25. **First explicit declassification-date field at the document level** — `Declassification Date (YYYYMMDD): 20450301` (1 Mar 2045 — 25-year DoD-standard window from a presumed 2020 originating-classification event). ^[inferred] Distinct from the Harrison Declassified-on 20 Mar 2026 page-banner — the document carries **two distinct declassification dates** (one as ORIGINAL classification metadata, one as APPLIED declassification authority). ^[inferred] First document-internal-classification-metadata + applied-declassification dual datum in dow-uap corpus.
26. **First explicit ATO (Air Tasking Order) reference** — Tasking Order `BP` (Battle Plan / numbered ATO). ^[inferred]
27. **First explicit POC + QC + APPROVER + INGEST four-role role-assignment chain** in dow-uap corpus.
28. **First mission-report UAP-datum count increment to N=6** — extends dow-uap mission-report counter from N=5 to N=6 (or, on the renamed-framing reading, 6 mission-report UAP-datum records / 7 datums). ^[inferred]
29. **First filename-axis verification at the internal-coordinate level for an `*-arabian-*` / `*-persian-gulf*`-class filename** — 5-of-5 internal MGRS coordinates decode inside the body-text-declared Arabian-Gulf-Hormuz-Oman operational area. ^[inferred] Revises the d4/d5/d7 "Arabian Gulf"-mismatch hypothesis (extract-vs-full-Misrep reading now most coherent).
30. **First explicit USAF Active-component mission-report anchor** (482ATKS / 432 AEW Active) — multi-service originating-anchor count rises from 7 to **8** at N=14 ingests: **6 USAF (5 Active — 15 AF / 12 AF / 48FW / 77 EFS + 482ATKS — + 1 ANG — 172 ATKS — ) + 2 Navy** (P-8A/TF 67.1 fixed-wing from d55 + MH-60R/HSM-73 rotary-wing from d56). ^[inferred]

## OCR ambiguities

- **`TRANSITTING`** (page 4 OBS Activity Description) — almost certainly **TRANSITING** with single T. ^[inferred] Standard USMTF / aviation vernacular for an aircraft passing through an area without engagement.
- **`ANDAS4`** (page 2 ACEQUIP TGT Pod) — plausibly **AN/DAS-4** (the L3Harris MS-177 / DAS-4 SAR/EO/IR sensor family used on MQ-9 ER/Block-5) ^[inferred]. ^[ambiguous] — multiple sensor families could match this OCR token.
- **`AH_GMESH`** (page 2 ACEQUIP Additional Avionics) — plausibly **AirHandler GMESH** ^[inferred] (an AIRHANDLER ISR/SIGINT sub-payload). ^[ambiguous].
- **`AIRHANDLER`** (Narrative page 0) — capitalized as a single proper noun; plausibly the named SIGINT payload identifier ^[inferred]. ^[ambiguous].
- **`OKAS`** (page 0 Narrative + page 3 Last Land Location + page 4 Takeoff) — ICAO 4-letter aerodrome identifier. **OKAS = Ali Al Salem AB, Kuwait** ^[inferred] (the Kuwait Air Force base, since 2020-era USAFCENT MQ-9 operations are anchored at Ali Al Salem). ^[ambiguous] — could be a different `O`-prefix ICAO if OCR misread.
- **`DGS1`** (page 0 Narrative) — Distributed Common Ground System Site 1 ^[inferred], the USAF/ISR PED node at Langley AFB VA. ^[ambiguous].
- **`PAROC IDAT`** (page 1 QC block) — plausibly **PAROC Intel Data Analysis Technician** ^[inferred], extending the PAROC role attested at [[references/dow-uap-d52-email-na-2024|d52]] (15 AF / DET 1 PAROC IDAT). ^[ambiguous].
- **`1,4a` / `1.4a`** — portion-redaction notation; comma-vs-period OCR variance; standard pattern from prior dow-uap ingests.
- **`14(6)`** — does not appear in d60; the witness-redaction-OCR-corruption pattern documented at d54 (`14(6)` for `(b)(6)`) and d8 (`1.4(6)` for `(b)(6)`) does **not** recur on d60. d60 uses clean `(b)(6)` redaction throughout. ^[extracted]
- **`Classification:` (blank value)** + **`Associated Caveats: ~~(illegible text)~~`** (page 0 CLASSIFICATION block) — the Classification field is blank in the OCR and the Associated Caveats field carries an illegible-text strikethrough. ^[ambiguous] The classification level (Secret? Top Secret? Confidential?) is **not preserved** in the OCR at the document-level — only the per-page `# 1.4(a)` portion-redaction marker is preserved.
- **Declassification Date `20450301`** (page 0 CLASSIFICATION block) — interpreted as `2045-03-01` (1 March 2045). ^[inferred] A 25-year window from a presumed 2020 originating-classification event places the Declassification Date Apr 2045 ^[inferred]; the field's `20450301` rendering is consistent.
- **`(b)(6)` cleanliness** — the redaction format on d60 is **clean** `(b)(6)` throughout, **distinct from the d54 (`14(6)`) + d8 (`1.4(6)`) OCR-corruption pattern**. ^[extracted] The d60 OCR pass on this artifact preserves redaction syntax better than the prior single-segment d* extract OCR passes. ^[inferred]

## Open questions

- **Validate the full-Misrep document class at N≥2** — ^closed-by-dow-uap-d61. [[references/dow-uap-d61-mission-persian-gulf-2020-08-27|DoW-UAP-D61]] (26-27 Aug 2020, Misrep 4685903) is a second full-Misrep with 7 substantive pages and complete USMTF segment set — class CONFIRMED at N=2. **Extended to N=3 ^closed-by-dow-uap-d62**: [[references/dow-uap-d62-mission-strait-of-hormuz-2020-09-16|DoW-UAP-D62]] (15-16 Sep 2020, Misrep 4782130) is the **third full-Misrep with 9 substantive pages + same complete USMTF segment set + EMI segment NEW** — class anchored decisively at N=3 across 38-day same-unit-same-tasking triplet.
- **Test the extract-vs-full-Misrep hypothesis** — are d4/d5/d7/d8/d54 (single-substantive-page-with-header-padding) extracts of parent multi-page Misreps like d60? If subsequent ingests carry full-Misrep parent documents whose extracted GENTEXT segments match d4/d5/d7/d8/d54's UAP datums, the extract hypothesis is confirmed.
- **Resolve the segment-name distinction** — `GENTEXT/OBSERVATION` (d60) vs `GENTEXT/UAP` (d4/d5/d7/d8/d54). Is the d60 reading (curator-renamed `GENTEXT/OBSERVATION` → `GENTEXT/UAP` at release) correct, or do the two segment-names reflect different originating-service conventions?
- **Confirm 482ATKS / 432 AEW MQ-9 attribution** — open-source unit-history validation of 482ATKS as a 432 AEW Active-component MQ-9 squadron in Aug 2020 would firm the platform reading.
- **Decode `ANDAS4` and `AH_GMESH`** — sensor-suite token decoding via open-source MQ-9 hardware references. If ANDAS4 = MS-177 / DAS-4, the platform reading anchors at MQ-9 Block 5 / MQ-9 ER. If AH_GMESH = AirHandler GMESH, the platform carries an AIRHANDLER SIGINT sub-payload.
- **Confirm `OKAS` ICAO = Ali Al Salem AB, Kuwait** — open-source ICAO database verification.
- **Decode `DGS1` and `AIRHANDLER`** — DGS1 likely the Langley AFB PED node; AIRHANDLER likely a named SIGINT payload. Both first-attestations in dow-uap corpus; both warrant entity-level pages if recurrent.
- **Resolve `603 AOC` vs `609 AOC`** — page 0 Operation block lists `Operations Center: 609th`; page 1 POC block lists `Operations Center: 603 AOC`; page 1 APPROVER block lists `Operations Center: 609 CAOC`. ^[ambiguous] The 603 AOC is USAFE/AFRICOM-anchored, while the 609 CAOC is USCENTCOM-anchored. Three readings: (a) OCR error; (b) the POC was administratively assigned to 603 AOC at a different point in their career; (c) joint 603 + 609 routing of the mission record. ^[ambiguous]
- **Test the multi-segment-Timeline structure at N≥2** — ^closed-by-dow-uap-d61. d61 carries the same Landing / GUARDCALL / OBSERVATION / Takeoff / On Station / ISR / Off Station Timeline sub-segments. The d60 schema firms as the canonical USMTF-Misrep Timeline schema at N=2. **Extended at d62 ^closed-by-dow-uap-d62** — d62 carries the same canonical schema PLUS the corpus's first **EMI / GENTEXT/EMI** segments (2 MEDIUM-impact lost-link events with structured fields + JSIR ID anchors + paired narrative), anchoring EMI as an additional canonical USMTF Misrep segment when applicable. ^[inferred]
- **Decode the redacted `Operation 1,4a` name** — the Narrative explicitly names the supported NAVCENT operation but portion-redacts the operation name. Open-source 5th Fleet Aug 2020 operational history might recover the name.
- **Test the Iranian Air Defense GUARDCALL recurrence pattern** — ^closed-by-dow-uap-d61. d61 carries an Iranian Air Defense direct hail at 270532Z with `PROFESSIONAL` tone and standard exchange (UTM 40R / CP — same eastern-Persian-Gulf approach as d60's hail at 081250Z UTM 40R / CP). Foreign-state direct hails are now a **class-level signature** of CENTCOM-AOR MQ-9 ISR missions, not a d60 outlier. Temporal sequencing relative to UAP event varies (post-UAP at d60; pre-UAP at d61) — no causal link between GUARDCALL and UAP events. ^[inferred] **Extended at d62 ^closed-by-dow-uap-d62** — d62 carries **3 GUARDCALL events per mission** (vs 1 at d60 + 1 at d61): 0408Z DIRECTIVE + 0421Z DIRECTIVE + 1141Z PROFESSIONAL. Per-mission count distribution at N=3 is now 1+1+3; **first DIRECTIVE tone in the cluster** (escalation signature, possibly correlated with airspace-encroachment severity or controller individual style); **first same-MGRS multi-hail cluster** (#1+#2 at 40RCP76 13 min apart); **first explicit 243.000 MHz Guard frequency citation** (hail #3); altitude variance FL180 → FL040 across mission. All 3 d62 hails occur pre-UAP. ^[inferred]
- **Resolve the `Declassification Date 20450301`** — is this a 2045-Mar-01 future declassification date (i.e. document still classified through 2045 at originating time, with applied Harrison declassification authority overriding to 2026), or an OCR error?
- **Decode `Tasking Order: BP`** — Battle Plan / numbered ATO. The 2-letter `BP` token may map to an open-source USAFCENT 2020 ATO designator.
- **Validate the `IVO 39RWL08` body-coord precision** — partial portion-redaction prevents exact decoding; full MGRS would supply ~5–10 km precision instead of the inferred ~100-km square level.

## See also

- [[entities/dow-uap-foia-release]] — Series-level anchor (d60 is the 14-of-40 ingest, 6th substantive mission-record artifact, **first-INGESTED FULL USMTF Misrep** — reframed by [[references/dow-uap-d65-mission-persian-gulf-2020-07-16|d65]] from "earliest dated" to "first-ingested-but-second-earliest" ^closed-by-dow-uap-d65; d65 (16-17 Jul 2020) is the earliest dated cluster member at 23 days BEFORE d60); anchors third top-level mission-report sub-class
- [[references/dow-uap-d65-mission-persian-gulf-2020-07-16]] — **Sixth FULL USMTF Misrep (Misrep 4472514, 16-17 Jul 2020) — EARLIEST DATED CLUSTER MEMBER, 23 days BEFORE d60**; same 482ATKS / 432 AEW MQ-9 cluster member; first 3-UAP-datum full-Misrep; cluster span extends to ~110 days Jul-Nov 2020 across 5 calendar months
- [[references/dow-uap-pr20-prepublication-clearance-2026-03]] — Series prepublication-clearance cover stamp (10 Mar 2026)
- [[references/dow-uap-d4-mission-arabian-gulf-2020]] — First single-segment GENTEXT/UAP extract mission report — kinematic-anomaly sub-class; d60 may be the parent-Misrep-class analog
- [[references/dow-uap-d5-mission-arabian-gulf-2020]] — Two-sighting GENTEXT/UAP extract
- [[references/dow-uap-d7-mission-arabian-gulf-2020]] — Form-driven GENTEXT/UAP extract with TFLIR fire-control engagement-pipeline + 48FW USAF cross-reference
- [[references/dow-uap-d54-mission-mediterranean-sea]] — Triangular-and-metallic GENTEXT/UAP extract over Aegean Sea
- [[references/dow-uap-d8-mission-djibouti-2025]] — Round-white-hot GENTEXT/UAP extract; first FIN+SWE+FVEY+NATO release authorization
- [[references/dow-uap-d55-mission-syria-2016-11-18]] — CTG-narrative mission report (P-8A / TF 67.1, 18 Nov 2016); second top-level mission-record sub-class
- [[references/dow-uap-d38-range-fouler-middle-east-may-2020]] — Earliest range-fouler in corpus (Persian Gulf coast); sister Persian-Gulf-theater artifact 86 days before d60
- [[references/dow-uap-d56-range-fouler-arabian-sea-august-2020]] — Range-fouler 24 Aug 2020 North Arabian Sea HSM-73 MH-60R; sister Aug-2020 artifact 16 days after d60; both Block A
- [[references/dow-uap-d44-range-fouler-arabian-sea-october-2020]] — Range-fouler 15 Oct 2020 Gulf of Aden 172 ATKS MQ-9; same MQ-9 platform-class as d60 but different document class
- [[references/dow-uap-d58-range-fouler-debrief-2020-10]] — Range-fouler 27 Oct 2020 77 EFS CENTCOM; sister CENTCOM-AOR 2020 artifact
- [[references/dow-uap-d61-mission-persian-gulf-2020-08-27]] — **Second FULL USMTF Misrep (Misrep 4685903, 26-27 Aug 2020); same 482ATKS / 432 AEW MQ-9 ^[inferred] / same NAVCENT support / same operation 1.4a — 19-day same-unit repeat-mission pair with d60; closes 3 of d60's open threads**
- [[references/dow-uap-d62-mission-strait-of-hormuz-2020-09-16]] — **Third FULL USMTF Misrep (Misrep 4782130, 15-16 Sep 2020); same 482ATKS / 432 AEW MQ-9 ^[inferred] / same NAVCENT support / same operation 1.4a — third member of the corpus's first same-unit-same-tasking triplet (38-day Aug-Sep 2020 span); confirms sub-class 8 (bare FMV-observation) at N=2 with d60 — d60 is no longer the sole sub-class 8 anchor**. d62 anchors EMI events as a NEW canonical USMTF Misrep schema axis (2 MEDIUM-impact lost-link events with paired GENTEXT/EMI + JSIR ID330412+330414); 3 Iranian GUARDCALLs (first DIRECTIVE tone, first multi-hail mission); first IR-SA-5 SAM launcher + Houdong/Sina-class missile-patrol-boat observations; first same-10-km-MGRS-square aircraft-and-UAP geometry; Block B (vs d60's Block A) — class spans both Blocks at N=3
- [[references/dow-uap-d52-email-na-2024]] — Email-correspondence class (15 AF / DET 1 PAROC IDAT)
- [[references/dow-uap-d50-email-indopacom-2025-04]] — Email-correspondence class (12 AF / DET 3)
- [[concepts/uap-aircraft-engagement]] — Behavioral framing; d60 increments mission-report UAP-datum counter to N=6 / 7 datums; anchors 8th brief-observation sub-class (kinematics-blank + morphology-blank + FMV-observation + ISR-mission-context + zero-mission-impact)
- [[concepts/orb-phenomenon]] — Adjacent; d60 is morphology-blank
- [[entities/aaro]] — d60 `Approved for Release to AARO` stamp recurrence (6th in corpus); firms AARO as dow-uap receiving authority
- [[projects/uap/uap]]
