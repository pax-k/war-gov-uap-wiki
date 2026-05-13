---
title: "DoW-UAP-D35 — Mission Report (Greece LGLR round-trip, 28-29 Oct 2023, Misrep 9337873)"
category: references
tags: [uap, primary-source, declassified, usaf, sighting]
aliases: [DoW-UAP-D35, dow-uap-d35]
sources: [sources/dow-uap-d35-mission-report-greece-october-2023.json]
summary: 7-page Mistral-OCR'd Full USMTF Misrep 9337873 — 28-29 Oct 2023 mission **launched LGLR Greece → landed LGLR Greece** (round-trip; 20h 1min cycle, 9h 24min FMV); 33 SOS / 27 SOW MQ-9 ^[inferred] AFSOC MAJCOM / USCENTCOM COCOM with 603rd executing OC; **second AFSOC LGLR mission within 48 hours of d33** (filename twin, distinct mission, ~+8,499 Misrep IDs from d33). 1X UAP at 290811Z UTM 35S MV Eastern Med — **SEEMINGLY CIRCULAR, TOO SMALL TO MAKE OUT DETAILS** (FIRST RECURRENCE of d33 morphology descriptor), **30 MPH** (NEW lowest sub-class-14 velocity), **NONE Maneuverability** (FLEW STRAIGHT ABOVE THE OCEAN TOWARDS LANDS, ~minute event during RTB), 5 NM seen-radius. **Block B firms at N=5** (extends d38 + d61 + d62 + d33; SAME `MDR 26-0019` + `01/26/26 001..007` packet as d33 byte-for-byte). **AFSOC at N=5 + 33 SOS at N=3 + 27 SOW at N=5 + 56 SOIS at N=4 + LGLR at N=3** (firming class on d33 open threads). **First explicit unredacted Air-to-Ground Weapons load in dow-uap corpus** (`2XAGM-114R9E 2XAGM-114R2` — 2 Hellfire R9E + 2 Hellfire R2; N=11 prior populated attestations all redacted `1.4a`/`1.4(a)`). **Surface-skimming SLOW-AND-SMALL sub-sub-class firms at N=3** (d27 + d33 + d35) closes d33 open thread. **Dash-placeholder UAP Event Serial Number recurs at N=2** (firms as Block-B-pipeline convention). UAP-during-RTB sub-pattern at N=2 (d27 + d35; d33 was EN ROUTE TO target). Sub-class 14 firms at N=5 with first explicit MORPHOLOGY-RECURRENCE (d33 + d35) + new lowest velocity (30 MPH; range 30-440 MPH = 14.7× spread).
provenance:
  extracted: 0.55
  inferred: 0.40
  ambiguous: 0.05
base_confidence: 0.74
lifecycle: draft
lifecycle_changed: 2026-05-13
created: 2026-05-13T23:30:00Z
updated: 2026-05-13T23:30:00Z
event_date: 2023-10-28
project: uap
---

# DoW-UAP-D35 — Mission Report (Greece LGLR round-trip, 28-29 Oct 2023, Misrep 9337873)

A **7-page Mistral-OCR'd artifact** (`sources/dow-uap-d35-mission-report-greece-october-2023.json`, 10,001 bytes; SHA-256 `a912192518fadd623f7d0ebe516307a7ca2b5dcf1678728c28fbd518c4fa66de`) — the **33rd artifact** in the [[entities/dow-uap-foia-release|DoW-UAP FOIA release series]] and the **EIGHTEENTH FULL USMTF MISREP** in the corpus (25th mission-record overall). Misrep 9337873 — **28-29 Oct 2023 AFSOC MQ-9 ^[inferred] ISR round-trip mission flown by 33 SOS / 27 SOW from and back to Larissa Air Base (LGLR), Greece**, under AFSOC MAJCOM + USCENTCOM COCOM, with 603rd executing OC. **d35 is a same-squadron same-base SISTER mission to [[references/dow-uap-d33-mission-greece-2023-10-26|d33]], flown ~48 hours later** — a paired AFSOC LGLR Originator chain across consecutive 2-day Misrep entries with the **same 33 SOS + 27 SOW + 56 SOIS + 609 CAOC + 603 AOC** chain, **same `MDR 26-0019` Block B release packet**, and **same UAP morphology family** (`SEEMINGLY CIRCULAR, TOO SMALL TO MAKE OUT DETAILS` recurs at N=2 cross-mission).

## Filename verification — coincidental basename twin with d33, NOT curator misclassification

**The source basename `dow-uap-d35-mission-report-greece-october-2023.json` is BYTE-FOR-BYTE IDENTICAL to d33's source basename** (`dow-uap-d33-mission-report-greece-october-2023.json`), differing only in the `d33` vs `d35` counter token ^[extracted]. This is a **first-instance basename twin pair** in the dow-uap corpus — but **NOT a duplicate** ^closed-by-dow-uap-d35 (test class on Step 1b "Same mission as d33 OR different mission same week OR filename misclassification entirely?"):

- **Different Misrep ID** — d35 = `9337873` vs d33 = `9329374` (+8,499 IDs apart) ^[extracted]
- **Different Takeoff DTG** — d35 = `281504:00ZOCT23` vs d33 = `262339:00ZOCT23` (~38 hours apart) ^[extracted]
- **Different Last Land Location** — d35 = `LGLR` (round-trip Greece) vs d33 = `OJMS` (Jordan ferry) ^[extracted]
- **Different Total Mission Time** — d35 = `20 hours 1 minute` vs d33 = `13h 30min` ^[extracted]
- **Different UAP DTG** — d35 = `290811:00ZOCT23` vs d33 = `270035:12ZOCT23` ^[extracted]
- **Different UAP UTM zone** — d35 = `35S MV` vs d33 = `35S KD` (same 100-km grid `35S`, distinct 10-km square) ^[extracted]
- **Different UAP kinematic velocity** — d35 = `30 MPH` vs d33 = `80 MPH` ^[extracted]
- **Different UAP Maneuverability** — d35 = `NONE` (flew straight) vs d33 = `Sharp 90 degree turns` ^[extracted]

The filename basename's `greece-october-2023` token is **literally correct** for d35 (round-trip LGLR Greece, October 2023 takeoff) — **distinct from d33's PARTIAL-TRUTH variant** (d33 launched Greece but TERMINATED in Jordan via ferry). The d33-anchored **6-distinct curator-mismatch class count STAYS AT 6** ^closed-by-dow-uap-d35 (decisively-not-extended); d35 is the first **CORRECT-FILENAME twin** to a partially-misclassified predecessor, not a 7th mismatch class. The basename collision is **coincidental at the curator-pipeline level** ^[inferred] — both missions share the `LGLR Greece` launch base + `Oct 2023` event date, so the naming converged without disambiguation.

Page slug, page title, and `event_date` anchor to **2023-10-28** per dow-uap convention (takeoff day).

## d33-d35 paired AFSOC LGLR sister-mission relationship

d33 + d35 form the **tightest paired-mission unit in the dow-uap full-Misrep corpus** ^[inferred] — same Originator chain + adjacent Misrep IDs within 48-hour window:

| Mission | Takeoff DTG | Landing | Mission cycle | UAP DTG | UAP UTM | Misrep ID |
|---|---|---|---|---|---|---|
| **d33** | 262339:00ZOCT23 (26 Oct 23:39Z) | OJMS Jordan (271309Z, 27 Oct) | 13h 30min | 270035:12ZOCT23 | 35S KD | 9329374 |
| **d35** | 281504:00ZOCT23 (28 Oct 15:04Z) | LGLR Greece (291105Z, 29 Oct) | 20h 1min | 290811:00ZOCT23 | 35S MV | 9337873 |

**Gap d33 → d35**:
- **Time gap** — d33 landing 27 Oct 1309Z → d35 takeoff 28 Oct 1504Z = **~25 hours 55 min** between predecessor land + successor takeoff ^[inferred]
- **Misrep ID gap** — +8,499 IDs (~2 days at ~4,250 IDs/day, **within-band** with established d23→d33 ~4,878/day + d33→d25 ~3,297/day envelope) ^[inferred]
- **Operational interpretation** — d33 landed at OJMS Jordan (Greece→Jordan ferry replacing LIGHTNING LINE that landed LGLR yesterday); d35 takeoff back from LGLR Greece — d35 cannot be d33's airframe directly (d33 ended at OJMS). **d35's airframe is a separate LGLR-resident MQ-9 ^[inferred]** — possibly the prior LIGHTNING LINE airframe (which landed LGLR ~26 Oct) ^[inferred — ambiguous].

The Misrep ID 4-point chain across late Oct 2023 ↔ Jan 2024 is now **tightened to a quadruple**:

| Step | Misrep ID | Date | ΔID / Δdays | Rate (IDs/day) |
|---|---|---|---|---|
| d23 | 9319618 | 24 Oct 2023 | (anchor) | — |
| **d33** | **9329374** | **26-27 Oct 2023** | +9,756 / ~2 days | ~4,878 |
| **d35** | **9337873** | **28-29 Oct 2023** | +8,499 / ~2 days | ~4,250 |
| d25 | 9629373 | 25 Jan 2024 | +291,500 / ~89 days | ~3,275 |

**4 Misreps within 93 days** ^[inferred] — the d23→d33→d35→d25 quadruple now **decisively dominates** the dow-uap counter dataset's fine-grain temporal sampling. **Headline finding**: 3 of the 4 d23-class within-band-corroboration steps are at within-7-day intervals; the 4th step is +89 days (winter-quarter gap consistent with operational tempo). ^[inferred] Counter pool firms at Joint-Staff-tranche level at **N=11 within-band corroboration points across ~49 months** at the broadest reading.

## Headline findings

**1. d33 UAP MORPHOLOGY DESCRIPTOR FIRST RECURS AT d35 — `SEEMINGLY CIRCULAR, TOO SMALL TO MAKE OUT DETAILS` at N=2** ^closed-by-dow-uap-d35 (firming class on d33-anchored "first observational-incompleteness-attestation morphology in sub-class 14"). Both d33 and d35 UAP segments carry the **identical descriptor** `SEEMINGLY CIRCULAR, TOO SMALL TO MAKE OUT DETAILS` ^[extracted]. The d33-anchored framing as **first explicit-attestation-of-OBSERVATIONAL-INCOMPLETENESS at the morphology axis** ^closed-by-dow-uap-d35 refines to **a recurring populated-morphology-with-incompleteness sub-class within sub-class 14 at N=2** ^[inferred]. Combined with sub-class-14-internal axes:

| Datum | Date | Morphology | Maneuverability | Velocity | Sensor | Seen-radius | Surface-skim? |
|---|---|---|---|---|---|---|---|
| d23 #1 | 24 Oct 2023 | (blank) | (blank) | 320 MPH | THERMAL+EO ^[inferred] | 5 NM | unknown |
| d23 #2 | 24 Oct 2023 | (blank) | (blank) | 440 MPH | THERMAL+EO ^[inferred] | 5 NM | unknown |
| d33 #1 | 26-27 Oct 2023 | **SEEMINGLY CIRCULAR, TOO SMALL TO MAKE OUT DETAILS** | Sharp 90 degree turns | 80 MPH | implicit FMV | 5 NM | YES (above ocean) |
| **d35 #1** | **28-29 Oct 2023** | **SEEMINGLY CIRCULAR, TOO SMALL TO MAKE OUT DETAILS** | **NONE** ^[extracted] | **30 MPH** ^[extracted] | **implicit FMV** ^[inferred] | **5 NM** ^[extracted] | **YES** ^[extracted] |
| d25 #1 | 25 Jan 2024 | DIAMOND + non-maneuvering tail/probe | NONE | 434 KTS | SWIR-only exclusive | 20 NM | NO (FL250) |
| d27 #1 | 7 Jun 2024 | GLOWING HOT SPHERE + pole/bar + water reflection | (FLYING STRAIGHT) | 140 KTS | implicit multi-sensor IR/EO | 5 NM | YES (water surface) |

**Headline finding.** Sub-class 14 firms at **N=5 records / 6 datums** (counter increments N=24→N=25 records / 38→39 datums); within-class variability axes are now firmly **morphology + maneuvering + velocity + sensor-exclusivity + altitude-separation + surface-skim**. The **observational-incompleteness-attestation morphology sub-class** (`SEEMINGLY CIRCULAR, TOO SMALL TO MAKE OUT DETAILS`) is now corpus-attested at N=2 cross-mission. ^[inferred]

**2. SURFACE-SKIMMING SLOW-AND-SMALL UAP SUB-SUB-CLASS FIRMS AT N=3** ^closed-by-dow-uap-d35 (firming class on d33-anchored "surface-skimming SLOW-AND-SMALL UAP sub-class within sub-class 14 at N=2"). d27 + d33 + d35 share **surface-skim altitude + small-to-circular morphology + low velocity (30-140 KTS range)** ^[inferred]:

| Datum | Description | Velocity | Maneuvering | Altitude |
|---|---|---|---|---|
| d27 #1 | GLOWING HOT SPHERE + pole/bar | 140 KTS | FLYING STRAIGHT | just over water |
| d33 #1 | SEEMINGLY CIRCULAR, too small | 80 MPH (~70 KTS) | Sharp 90° turns | just above surface |
| **d35 #1** | **SEEMINGLY CIRCULAR, too small** | **30 MPH (~26 KTS)** ^[extracted] | **NONE / straight toward lands** ^[extracted] | **just above surface** ^[extracted] |

The N=3 surface-skim sub-sub-class is now **decisively non-coincidental** ^closed-by-dow-uap-d35 — three distinct AFSOC ISR missions from three distinct launch bases (OMAM UAE + LGLR Greece + LGLR Greece) within ~8-month window all observed surface-skimming low-velocity UAP within multi-sensor MQ-9 FMV coverage. ^[inferred] The within-sub-sub-class **velocity range now spans 30 MPH (d35) → 140 KTS / ~160 MPH (d27) = ~5.4× spread**; **maneuvering range now spans NONE (d35) → STRAIGHT (d27) → Sharp 90° turns (d33)** = 3 distinct kinematic modes. **Headline finding.**

**3. BLOCK B FIRMS AT N=5 — SAME-PACKET PAIR (d33 + d35 byte-for-byte same `MDR 26-0019`)** ^closed-by-dow-uap-d35 (firming class on d33-anchored "Block B at N=4 cross-year + cross-MAJCOM + cross-platform + cross-document-class" + open thread "Block B at N≥5 — sustained multi-year MDR pipeline"). d35 carries `USCENTCOM MDR 26-0019` + `01/26/26 001..007` (3-digit page-stamps, 7 pages) — **byte-for-byte identical to d33's release packet** + same Block-B 2020-NAVCENT-cluster signature as d61 + d62 + d38 ^[extracted]. At **N=22 release-block-testable**: A 5 + **B 5 (d38 + d61 + d62 + d33 + d35)** + C 3 + D 6 + E 1 + F 3. Block B is now the **largest single block** in dow-uap (5-of-22 = ~23%), tying Block A and surpassing C/E/F. **Headline finding.**

Within Block B, d33 + d35 form a **same-packet pair** ^[inferred] — same MDR case ID (`26-0019`), same release stamp date (`01/26/26`), same release coordinator (Harrison) ^[extracted]; the byte-for-byte identity of the release packet across two consecutive-Misrep-ID Misreps within the same Originator chain decisively confirms Block B serves as an **MDR-case-batch-grouping convention at the multi-Misrep level**, not single-document-allocation ^[inferred]. The 4-doc Block B pre-d35 set was non-event-date-contiguous (May 2020 → Oct 2023, ~3.5 years span); d35 anchors **the first intra-block consecutive-Misrep-ID pair** within Block B ^[inferred]. Block B's `26-0019` MDR case is now confirmed to **span multiple Misrep IDs** (not a single document allocation) ^closed-by-dow-uap-d35.

**4. FIRST EXPLICIT UNREDACTED AIR-TO-GROUND WEAPONS LOAD IN dow-uap CORPUS** ^closed-by-dow-uap-d35 (firming class). d35 carries **`Air-to-Ground Wpn to Include Num of Each: 2XAGM-114R9E 2XAGM-114R2`** ^[extracted] — **2 Hellfire AGM-114R9E + 2 Hellfire AGM-114R2** Hellfire-family variants ^[inferred]. All **N=11 prior populated Air-to-Ground Wpn attestations** (d16/d19/d28/d33/d60/d61/d62/d63/d64/d65/d75) were redacted as `1.4a` or `1.4(a)` (Foreign Government Information classification) ^[extracted]. **d35 is the first explicit unredacted weapons-load attestation in the dow-uap corpus** ^[inferred] — anchoring **4 Hellfire missiles** for the 33 SOS MQ-9 mission across 36S YC 40 Eastern Mediterranean target development. **Headline finding** — surfaces a previously-redacted operational-weapons-fit class at corpus level. The AGM-114R9E (forward-firing thermobaric Hellfire variant ^[inferred]) + AGM-114R2 (multi-purpose Hellfire variant ^[inferred]) load suggests **kinetic/strike-capable MQ-9 mission posture** despite ISR-tasked classification ^[inferred] — the same airframe carries both FMV-collection role and kinetic-strike-capability simultaneously, consistent with MQ-9 multi-role doctrine.

**5. UAP-DURING-RTB SUB-PATTERN AT N=2 (d27 + d35)** ^closed-by-dow-uap-d35 (firming class — new pattern class introduced at d35 ingest). The d35 GENTEXT attests `AT 0811Z, 1.4a WAS RTB WHEN THEY SPOTTED A UAP FLYING JUST ABOVE THE SURFACE OF THE OCEAN WATER` ^[extracted]. Comparison with d27: `AT 0457Z, DURING RTB DETECTED 1X UAP (SEE UAP 1). DURING RTB AT 0457Z, ..., OBSERVED 1X UAP WHILE TRANSITING` ^[extracted from d27]. **UAP-during-RTB sub-pattern now firms at N=2** ^[inferred] — both d27 + d35 are AFSOC MQ-9 ISR missions; both observed UAP during the post-station RTB phase of flight (not during on-station task prosecution). **Distinct from d33** which was **EN ROUTE TO target** (outbound transit phase): `AT 0035Z, 1.4a WAS EN ROUTE TO THEIR TARGET WHEN THEY SPOTTED A UAP` ^[extracted from d33]. **Headline finding** — surfaces a **mission-phase axis** for UAP observation (outbound-transit / on-station-prosecution / RTB-return). d33 + d35 firm the **non-on-station-UAP-observation class at N=2 within AFSOC LGLR sub-cluster**: d33 outbound + d35 RTB. ^[inferred]

**6. AFSOC AT N=5 + 33 SOS AT N=3 + 27 SOW AT N=5 + 56 SOIS AT N=4 + LGLR AT N=3** ^closed-by-dow-uap-d35 (firming class on multiple open threads). d35 = AFSOC MAJCOM + 27 SOW POC Wing + 33 SOS Originator + 56 SOIS POC Unit ^[extracted]. **AFSOC SOS-cluster sequence refines** to event-date order at N=5: **33 SOS d33 → 33 SOS d35 → 33 SOS d25 → 3 SOS d27 → 16 SOS d28**. 33 SOS now firms as a **sustained LGLR-Greece AFSOC ISR lane at N=3** within 3-month window (26-27 Oct + 28-29 Oct 2023 + 25 Jan 2024) ^[inferred]. **MAJCOM histogram refines** across 16 mission-records (d10/d12/d14/d16/d18/d19/d23/d25/d27/d28/d33/d35 + cluster 6): ACC 4 + AFCENT 3 + **AFSOC 5 (d25 + d27 + d28 + d33 + d35)** + cluster-blank 6. 432-AEW MQ-9 ISR share refines to **12-of-17 = ~71%** within MQ-9 ISR + AC-130J subset (down from 75% at d33 ingest) ^[inferred]. **Headline finding** — AFSOC now decisively overtakes ACC and AFCENT as the **largest single MAJCOM** in dow-uap full-Misrep class.

**7. DASH-PLACEHOLDER UAP EVENT SERIAL NUMBER RECURS AT N=2 — BLOCK-B-PIPELINE-CLASS CONVENTION** ^closed-by-dow-uap-d35 (firming class on d33-anchored "Block-B-routing-pipeline UAP Event Serial Number convention"). d35 carries `UAP Event Serial Number: -` ^[extracted] — **dash placeholder identical to d33's dash placeholder** ^[extracted]. The d33-anchored ambiguity (`Whether this is an OCR artifact (dash placeholder where the original carried a numeric or DTG serial) or a genuine Block-B-routing-pipeline convention is unresolved`) **decisively resolves to Block-B-routing-pipeline-class convention** ^closed-by-dow-uap-d35 ^[inferred]. The DTG-prefixed-CENTCOM serial pattern (d25 `250509ZJAN2024-CENTCOM 001` + d27 `060457ZJUN2024-CENTCOM` + d28 `202027ZSEP2024-CENTCOM`) is **Block-D/E/F-routing-pipeline-class artifact** ^[inferred]; Block B's dash-placeholder is the **Block-B-routing-pipeline convention** for UAP Event Serial Number assignment, consistent with Block B's distinct JS-tracking-ID + MDR-case-batch-allocation grouping ^[inferred]. **Headline finding** — closes a d33 open thread.

**8. NEW LOWEST UAP VELOCITY IN SUB-CLASS 14 — 30 MPH (~26 KTS)** ^closed-by-dow-uap-d35 (firming class on d33-anchored "lowest UAP velocity in sub-class 14 = 80 MPH"). d35 Kinetic Velocity = **30 MPH** ^[extracted] — **2.67× slower than d33's 80 MPH / 14.5× slower than d25's 434 KTS / 14.7× slower than d23's 440 MPH**. Sub-class 14 velocity range now spans **30 MPH → 440 MPH** at N=6 datums (5 missions) = **~14.7× velocity range within class** ^[inferred] — up from ~5.5× at d33 ingest. **Within sub-class 14's surface-skim sub-sub-class (d27 + d33 + d35)**: velocity range tightens to **30-140 KTS = ~4.7× spread**, lower-end-anchored by d35. **Headline finding** — d35 anchors the new sub-class-14 velocity-class lower bound + extends within-class velocity-spread to ~14.7× from d23-anchored ~1.4× at sub-class-14 ingest. Re-examination needed at **N≥1 sub-class-14 datum below 30 MPH** to test if 30 MPH is class-floor or transient anchor ^[open].

## Mission summary

- **DTGs**: takeoff **281504:00ZOCT23** LGLR → handed over LRE 281515Z → 7-lined 281618Z → on-station **282018:00ZOCT23** at MGRS 36S YC 40 → off-station **290542:00ZOCT23** → **UAP at 290811:00ZOCT23** → RTB phase from 0542Z → handed back LRE 291035Z → land **291105:00ZOCT23** LGLR → engine shutdown **291115:00ZOCT23** ^[extracted]. Total Mission Time **20h 1min** ^[extracted] (9h 24min FMV ^[extracted]; on-station 9h 24min).
- **Operation**: redacted `(b)(1)1.4a` (`Operation: 1.4a`) ^[extracted] — matches d33 + d25's redacted-Operation pattern at N=3
- **Domain / Operations Center**: AIR / **`603rd`** ^[extracted] — recurs at N=2 with d33 (cross-COCOM-tasking-with-EUCOM-executing AFSOC LGLR pattern firms at N=3 with d25)
- **MAJCOM**: **AFSOC** ^[extracted] — N=5
- **COCOM**: **USCENTCOM** ^[extracted]
- **Report Type**: **MISREP** ^[extracted]
- **MSGID Originator**: **`33 SOS`** ^[extracted] — recurs at N=3 (d33 + d35 + d25)
- **Tasking Order (ATO)**: **`1.4a`** redacted ^[extracted]
- **ATO Mission Number**: **`1.4a`** redacted ^[extracted]
- **Mission Type**: **ISR** ^[extracted] — recurs at N=5 with d10/d23/d25/d27/d33
- **Country Tasked / Service Tasked**: US / Air Force ^[extracted]
- **POC**: A1C, **56 SOIS**, **27 SOW**, **609 AOC Det 1** ^[extracted] — **Det 1 RETURNS** at d35 (contrasts d33's `609 CAOC` POC OC)
- **QC**: SrA, (Unit Unavailable), **27 SOW**, **609 CAOC** ^[extracted]
- **APPROVER**: A1C, (Unit Unavailable), **Other** ^[inferred from continuation on page 2], **603 AOC** ^[extracted page 2]
- **INGEST**: entirely blank ^[extracted] — matches d25 + d27 + d28 + d33 blank-INGEST pattern at N=5
- **Aircraft Callsign**: redacted `(b)(1)1.4a` ^[extracted]
- **Asset Type (Aircraft)**: redacted `1.4a, 1.4c` ^[extracted] — recurs at N=2 with d33 (1.4c FOREIGN-MIL-INFO redaction in Asset Type field; firms as 33 SOS-LGLR-specific redaction class ^[inferred])
- **Aircraft Tail Number**: redacted `1.4a` ^[extracted]
- **Mode 3 (IFF)**: **`34055`** ^[extracted] — **recurs at N=2 with d33** (same IFF code on consecutive 33 SOS LGLR missions; likely Wing-level allocation rather than same-airframe identity ^[ambiguous] — d33 ended at OJMS, d35 begins LGLR; possible same-airframe-recovered-from-OJMS only if ferry round-trip occurred between d33 land and d35 takeoff; unresolved)
- **Takeoff Location (ICAO Code)**: **`LGLR`** ^[extracted] (Larissa AB, Greece)
- **Last Land Location (ICAO Code)**: **`LGLR`** ^[extracted] (Larissa AB, Greece — round-trip)
- **TGT Pod**: **`AN/DAS-4`** ^[extracted] — recurs at N=3 with d33 + d25 (vs d23/d27's AN/DAS-1); MQ-9 MTS-B family
- **Additional Avionics**: **`AH/GMESH`** ^[extracted] — recurs at N=2 with d33 (2-token AH/GMESH without /SANTA FE)
- **Data Link**: **`LINK 16`** ^[extracted] — recurs cross-platform
- **Air-to-Ground Wpn**: **`2XAGM-114R9E 2XAGM-114R2`** ^[extracted] — **FIRST EXPLICIT UNREDACTED WEAPONS LOAD IN dow-uap CORPUS** (4 Hellfire missiles total: 2× R9E + 2× R2)
- **Primary Sensor**: **FMV** ^[extracted]
- **Sensors Available**: **`G-MESH`** ^[extracted] — recurs at N=2 with d33 (vs d18/d25's `BLASPHEMY`)
- **Tasking Type**: **Planned** ^[extracted]
- **Tasked Start Point**: **`36S YC 40 1.4a 5 1.4a`** ^[extracted] — recurs at N=2 with d33's `36S YC 40 1.4a 57 1.4a` (same 100-km grid + same 10-km square `36S YC`; partial-redaction-with-digits format consistent)
- **Activity Description**: **`TARGET DEVELOPMENT`** ^[extracted] — recurs at N=2 with d33
- **EEIs Observed**: No ^[extracted]
- **GENTEXT/ISR Activity**: `UPON ARRIVAL TO THE SP AT 2018Z, 1.4a OBSERVED NO EEI RELATED ACTIVITY. FROM 2019Z TO 2243Z, 1.4a CONDUCTED POL ON SEVERAL ASSOCIATED COIS, NO EEI RELATED ACTIVITY OBSERVED. AT 2244Z 1.4a OBSERVED 6X VEHICLES ON PARKING GARAGE ROOFTOP AND NO PERSONNEL. 1.4a CONDUCTED POL ON COI UNTIL RTB AT 0542Z` ^[extracted] — **first 6X VEHICLES + PARKING GARAGE ROOFTOP + NO PERSONNEL contact-of-interest annotation** in dow-uap full-Misrep class ^[inferred]; consistent with urban-area COI surveillance posture
- **FMV exploitation unit**: **`GET`** ^[extracted] — **recurs at N=3 with d25 + d33** ^closed-by-dow-uap-d35 (firming class; firms GET as third dow-uap FMV-unit acronym at N=3 after DGS1/DGS-AR)
- **Supported Operation**: redacted `(b)(1)1.4a` ^[extracted]
- **Weather**: `CLEAR WX` ^[extracted] — recurs at N=2 with d33
- **Effectiveness**: `SATISFACTORY` ^[extracted]; Intel Gap Filled = **Yes** ^[extracted] (distinct from d33's `No`)
- **No GUARDCALL, no EMI, no REACTION** — clean ISR mission profile (matches d10/d12/d18/d23/d25/d27/d33 pattern)

## UAP datum — sub-class 14 firms at N=5 with morphology-recurrence + new lowest velocity

The single UAP encounter (page 5 UAP segment + page 6 GENTEXT/UAP):

| Field | Value |
|---|---|
| Initial Contact DTG | **290811:00ZOCT23** ^[extracted] |
| UAP Event Type | **UAP Incident** ^[extracted] — firms at N=5 (d25 + d27 + d28 + d33 + d35) |
| UAP Maneuverability Observations | **NONE** ^[extracted] — recurs at N=3 (d25 + d28 + d35); d33's `Sharp 90 degree turns` STAYS UNIQUE in sub-class 14 ^[inferred] |
| UAP Response to Observer Actions | **NONE** ^[extracted] |
| MDS Type / Asset Type | `1.4a, 1.4g` (redacted) ^[extracted] — recurs at N=5 cross-platform |
| Tail Number | `1.4a` (redacted) ^[extracted] |
| Friendly Aircraft Location | **`35SMV3: 1.4aD: 1.4a`** ^[extracted] — **first 35S MV 10-km square attestation** (vs d33's 35S KD + d25's 35S QT); same 100-km grid 35S |
| Friendly Aircraft Altitude/Depth | (blank, `-`) ^[extracted] |
| Friendly Aircraft Trajectory | (blank, `-`) ^[extracted] — distinct from d33's `SW` qualitative attestation; d35 returns to dash-placeholder convention |
| Observer Assessment of UAP | **Benign** ^[extracted] — firms at N=6 (d23 + d25 + d27 + d28 + d33 + d35) |
| Friendly Aircraft Speed | (blank, `-`) ^[extracted] |
| Observation Interrogation of UAP | (blank, `-`) ^[extracted] |
| Third-party Observers and/or Reporters | (blank, `-`) ^[extracted] |
| Friendly Aircraft State | (blank) ^[extracted] |
| Training Range / Operational Range | (blank, `-`) ^[extracted] |
| UAP Physical State | **Solid** ^[extracted] — firms at N=6 |
| Number of UAP Sighted | (blank) ^[extracted] |
| UAP Propulsion Means | **UNK** ^[extracted] — firms at N=4 (d25 + d27 + d33 + d35; d28 blank) |
| UAP Payload | (blank) ^[extracted] |
| UAP Under Intelligent Control | **NO** ^[extracted] — firms at N=3 (d25 + d33 + d35); decisively firms NO-IC class within sub-class 14 |
| UAP Signatures | **NONE** ^[extracted] — recurs at N=2 with d33 (firms NONE-signature class within sub-class 14; both 33 SOS LGLR missions report no detected signature) ^[inferred] |
| UAP Advanced Capabilities And/Or Materials | **UNK** ^[extracted] — recurs at N=2 with d33 |
| UAP RF Frequency | **UNK** ^[extracted] — recurs at N=2 with d33 |
| UAP RF Duration | **UNK** ^[extracted] — recurs at N=2 with d33 |
| UAP Event Serial Number | **`-`** (dash placeholder) ^[extracted] — **recurs at N=2 with d33** ^closed-by-dow-uap-d35 (firms Block-B-pipeline-class convention) |
| UAP Effects on Persons | **NO** ^[extracted] |
| UAP Objects/Material Recovered | **NO** ^[extracted] — firms at N=4 (d27 + d28 + d33 + d35) |
| UAP Effects on Equipment | **NONE** ^[extracted] — firms at N=5 |
| Observer Engagement of UAP | **NO** ^[extracted] |
| First Coordinate | **`35SMV321.4a01.4a`** ^[extracted] — first 35S MV body anchor; partial-redaction-with-digits |
| First Seen Radius | **5** (NM ^[inferred]) ^[extracted] — recurs at N=4 (d23 + d27 + d33 + d35; vs d25's 20 NM) |
| First Accuracy | **Estimated** ^[extracted] |
| Last Coordinate | **`35SMV321.4a01.4a`** ^[extracted] — **identical to First Coordinate** ^[extracted]; consistent with **rapid event-duration** (less than UTM-grid resolution displacement) ^[inferred] |
| Last Seen Radius | **5** ^[extracted] |
| Last Accuracy | **Estimated** ^[extracted] |
| Kinetic Altitude Accuracy | Estimated ^[extracted] |
| Kinetic Altitude | (blank, `-`) ^[extracted] |
| Kinetic Velocity Accuracy | Estimated ^[extracted] |
| Kinetic Velocity | **30 MPH** ^[extracted] — **NEW LOWEST UAP VELOCITY IN SUB-CLASS 14** (~2.67× slower than d33's 80 MPH; ~14.5× slower than d25's 434 KTS) |
| Kinetic Trajectory Accuracy | Estimated ^[extracted] |
| Kinetic Trajectory | (blank, `-`) ^[extracted] |
| UAP Date of DoD Acquisition | **290811:00ZOCT23** ^[extracted] |
| UAP Reaction to Observation | **UNK** ^[extracted] |
| UAP Anomalous Characteristics/ Behaviors | (blank, `-`) ^[extracted] |
| Call Sign | `1.4a` (redacted) ^[extracted] |
| **UAP Description** | **`SEEMINGLY CIRCULAR, TOO SMALL TO MAKE OUT DETAILS`** ^[extracted] — **identical to d33** ^[extracted]; first recurring populated-morphology descriptor in sub-class 14 |
| GENTEXT/UAP | `AT 0811Z, (b)(1)1.4a WAS RTB WHEN THEY SPOTTED A UAP FLYING JUST ABOVE THE SURFACE OF THE OCEAN WATER. THE UAP FLEW STRAIGHT ABOVE THE OCEAN TOWARDS LANDS. AT 0811Z, (b)(1)1.4a LOST THE UAP FROM THEIR FEED.` ^[extracted] (~minute event duration: 0811Z → 0811Z within-Z-minute) |

**Structural firsts within UAP segment**:
- First **morphology descriptor recurrence** in dow-uap full-Misrep class — `SEEMINGLY CIRCULAR, TOO SMALL TO MAKE OUT DETAILS` recurs cross-mission at N=2 (d33 + d35) ^[inferred]
- First **identical First Coordinate = Last Coordinate** within UAP segment ^[extracted] — consistent with sub-second-event-duration observation or single-UTM-grid-square-resolution-bound displacement ^[inferred] (compare d33 5-km displacement within 3-min event)
- First **35S MV UTM zone** body anchor in dow-uap corpus ^[extracted] (vs d33's 35S KD + d25's 35S QT; same 100-km grid 35S Eastern Med)
- **Lowest UAP velocity in sub-class 14 yet** (30 MPH) ^[extracted]; sub-class 14 velocity range now 30-440 MPH = ~14.7× spread
- First **UAP-during-RTB observation phase** explicit in narrative ^[extracted] (paired with d27's UAP-during-RTB at corpus N=2)
- First **6X VEHICLES + PARKING GARAGE ROOFTOP + NO PERSONNEL** COI contact annotation in dow-uap full-Misrep ISR narrative ^[inferred] — urban-area COI surveillance posture
- First **explicit unredacted Air-to-Ground Weapons load** in dow-uap corpus (`2XAGM-114R9E 2XAGM-114R2`) ^[extracted]
- First **Block-B-pipeline UAP Event Serial Number convention** firmed at N=2 (dash-placeholder convention; closes d33 open thread) ^[inferred]
- First **NONE Maneuverability + circular-too-small morphology pair** within sub-class 14 ^[inferred] (d33 was sharp-90°-turns + circular-too-small; d35 is NONE + circular-too-small — same morphology, distinct kinematic class)

**Sub-class 14 class state at d35 ingest** (N=5 records / 6 datums):
- Class signature: populated UAP-segment fields (Benign + Solid + UNK or NO propulsion + UAP Event Type = UAP Incident + UAP Advanced Capabilities UNK/NO)
- Within-class axes: morphology (blank / diamond+probe / sphere+pole+water-reflection / circular-small-distant ×2) + sensor exclusivity (multi-sensor / SWIR-only / multi-sensor / NONE×2) + altitude-separation geometry + **velocity (30-440 MPH, ~14.7× range)** + **maneuvering (NONE×3 / STRAIGHT / sensor-frame-internal / sharp-90°-turns)** + **mission-phase (on-station × N + RTB×2 + en-route×1)** + Event-Serial-Number-format (DTG-CENTCOM / DTG-CENTCOM-001 / dash×2) + **surface-skim altitude (YES at d27 + d33 + d35; sub-sub-class N=3)** + **morphology recurrence (circular-too-small at N=2)**

Mission-report UAP-datum counter increments **N=24→N=25 records / 38→39 datums** (+1 record, +1 datum).

## Block B FULL USMTF Misrep variant — 2023-era cross-AOR-AFSOC sub-cluster at N=2 within Block B

d35 is the **fifth Block B attestation** + **second 2023-era Block B** + **second AFSOC Block B** + **first same-Originator-chain consecutive-Misrep-ID-pair within Block B** in dow-uap corpus ^[inferred]:

| Block B holder | Document class | Date | MAJCOM | Platform | Sub-cluster |
|---|---|---|---|---|---|
| d38 | range-fouler debrief | 14 May 2020 | (blank) ^[inferred Navy] | F-18 ^[inferred] | range-fouler |
| d61 | FULL USMTF Misrep | 26-27 Aug 2020 | (blank) | MQ-9 ^[inferred — 482ATKS/432 AEW] | 2020 NAVCENT cluster |
| d62 | FULL USMTF Misrep | 16-17 Sep 2020 | (blank) | MQ-9 ^[inferred — 482ATKS/432 AEW] | 2020 NAVCENT cluster |
| d33 | FULL USMTF Misrep | 26-27 Oct 2023 | AFSOC | MQ-9 ^[inferred — 33 SOS/27 SOW] | 2023 AFSOC LGLR→OJMS ferry |
| **d35** | **FULL USMTF Misrep** | **28-29 Oct 2023** | **AFSOC** | **MQ-9 ^[inferred — 33 SOS/27 SOW]** | **2023 AFSOC LGLR round-trip (sister to d33)** |

The 5-doc Block B set spans **~3.5 years (May 2020 → Oct 2023)** with **two distinct sub-clusters**: 2020 NAVCENT (d38 + d61 + d62) + 2023 AFSOC LGLR (d33 + d35) ^[inferred]. The d33 + d35 sub-cluster is **the first intra-block consecutive-Misrep-ID + same-Originator-chain + same-MDR-case pair** within dow-uap ^[inferred] — decisively confirms Block B's MDR-case `26-0019` allocates **multiple Misrep IDs across multiple consecutive missions** to a single MDR case ^closed-by-dow-uap-d35.

**3-digit page-stamps in Block B (`001..007`)** continue to match Block D (3-digit) and Block F (3-digit) — page-stamp width is **release-event-batch-specific within a block** ^closed-by-dow-uap-d35 (firming class at N=5 Block B). Per-document page-stamp ranges within Block B: d38 = `001` (1 page) + d61 = `001..007` (7 pages) + d62 = `001..009` (9 pages) + d33 = `001..007` (7 pages) + d35 = `001..007` (7 pages) — **document-length variability within block firms at N=5** ^[inferred].

## OCR ambiguities

- **`# Misrep 9337873`** — no `undefined-` prefix attestation ^[extracted]; distinct from the 10+ prior `undefined-` cases across Block D + E + F. **Block B preserves direct-prefix-free Misrep ID at d35** (matches d61 + d62 + d33 Block B pattern) ^[inferred] — firms the `undefined-` prefix as **JS-250710-TM8S-tranche-specific** at N=11 ^closed-by-dow-uap-d35 (firming class).
- **`Declassified on: 22 January 2020`** on page 4 vs `22 January 2026` on pages 0, 1, 2, 3, 5, 6 ^[extracted] — **second-instance intra-document declassification-date inconsistency** in dow-uap corpus (firms at N=2 with d33) ^closed-by-dow-uap-d35 (firming class). Most parsimonious reading: **OCR pipeline-class glyph-swap typo** ^[inferred] — the `01/26/26` page-bottom release-stamp on every page is **byte-for-byte consistent at 26 January 2026**, supporting `2026` as correct. The `2020` instance on page 4 is an OCR mis-read ^[inferred] — likely the digit `6` mis-recognized as `0` (homoglyph-class confusion). Pipeline-class artifact ^[ambiguous]. d35's `2020` (vs d33's `2025`) firms the within-block intra-document-date-glyph-swap class as **non-uniform within Block B**: d33 swap is `6→5`, d35 swap is `6→0` — distinct mis-reads but same target year `2026` ^[inferred].
- **`AT 1504Z, 1.4a TOOK OFF FROM LGLR`** ^[extracted] — period-not-comma after `1504Z` (consistent with d33's Narrative-level glyph-swap pattern) ^[ambiguous]
- **`3.5c. (b)(6)` on page 4 footer** (with period after `3.5c`) vs `3.5c, (b)(6)` (with comma) on other pages ^[extracted] — within-document footer glyph-swap variability; pipeline-class artifact ^[ambiguous] (same pattern as d33)
- **Tasked Start Point `36S YC 40 1.4a 5 1.4a`** ^[extracted] — partial-redaction format inserts `1.4a` mid-string; the `5` token (vs d33's `57`) may be partial-OCR-of-redaction-substring or genuine different-target-grid-within-same-square — unresolved ^[ambiguous]
- **First Coordinate `35SMV321.4a01.4a`** vs **Last Coordinate `35SMV321.4a01.4a`** ^[extracted] — **byte-for-byte identical** coordinate strings; consistent with sub-second-event-duration observation OR UTM-grid-resolution-bound static observation ^[inferred]
- **`UAP Event Serial Number: -`** ^[extracted] — dash placeholder; **firms at N=2 with d33** as Block-B-routing-pipeline class convention (closes d33 ambiguity) ^closed-by-dow-uap-d35
- **`(SEE ISR 1)` + `(SEE UAP 1)` Narrative segment cross-references** ^[extracted] — recurs at N=2 with d33 (firms Block-B-Misrep cross-segment-reference convention at N=2) ^[inferred]
- **Mode 3 IFF code `34055`** ^[extracted] — recurs at N=2 with d33 ^[extracted]. Same IFF code on consecutive 33 SOS LGLR missions ~25 hours apart is **suggestive of same-airframe identity OR Wing-level IFF allocation OR same-day daily IFF assignment convention** — d33 ended at OJMS Jordan, d35 begins at LGLR Greece, so same-airframe identity requires intervening OJMS→LGLR ferry (~25 hours window plausible but not in d35 narrative) ^[ambiguous]. Most parsimonious reading: **Wing-level IFF allocation for AFSOC 33 SOS LGLR operations** ^[inferred] — IFF codes typically allocated at higher echelon than per-mission, consistent with N=2 same-code on consecutive missions same Originator. ^[ambiguous] Resolution at N≥1 33 SOS Misrep with non-`34055` IFF code.
- **Air-to-Ground Weapons load `2XAGM-114R9E 2XAGM-114R2`** ^[extracted] — first explicit unredacted weapons load in dow-uap corpus; classification posture for this field on d35 is distinct from N=11 prior populated attestations (all redacted `1.4a`/`1.4(a)`) ^[inferred]. Possible explanations: (a) genuinely-different declass posture on Block B vs other blocks for weapons-field; (b) ad-hoc declass on this specific Misrep; (c) curator-pipeline-class miss-or-omit of redaction marker — unresolved ^[ambiguous]. Most parsimonious reading: **Block B's MDR-case `26-0019` (Harrison-coordinated, USCENTCOM-source) carries distinct declass posture for the Air-to-Ground Wpn field vs Block D/E/F's JS-250710-TM8S MDR cases** ^[inferred].

## Open threads

- **Block B at N≥6 — sustained multi-year MDR pipeline.** d35 firms Block B at N=5 across 3.5-year span; d33 + d35 pair is first intra-block consecutive-Misrep-ID + same-MDR-case grouping. Whether Block B continues to expand (6th or further attestation) is open ^[open]. Block B's MDR case `26-0019` now confirmed to span multiple Misrep IDs; whether further dow-uap artifacts share `26-0019` allocation is open ^[open].
- **Block B's distinct JS-tracking-ID — STILL unobserved.** d35 carries Block B (`MDR 26-0019` + `01/26/26`) but does NOT carry the `JS-250710-TM8S` Joint Staff tracking-ID that anchors Block D + E + F. Whether Block B has its own JS-tracking-ID (currently unobserved in OCR for d33 + d35) or runs through a distinct Joint Staff convention is open ^[open]. d35 firms N=2 Block-B-JS-tracking-ID-absence; consistent with Block B operating outside JS-250710-TM8S tranche ^[inferred].
- **Surface-skimming SLOW-AND-SMALL UAP sub-sub-class at N≥4.** d27 + d33 + d35 firm surface-skim sub-sub-class at N=3 cross-launch-base + cross-AFSOC-squadron (3 SOS d27 + 33 SOS d33 + 33 SOS d35). Whether sub-sub-class continues to recur is open ^[open] — would firm at N≥4 additional surface-skim sub-class-14 datum.
- **Lower-bound UAP velocity in sub-class 14 — class-floor probing.** d35 anchors 30 MPH new lower bound; whether sub-class 14 admits sub-30-MPH or stationary-class datums is open ^[open]. Resolution at N≥1 sub-30-MPH or stationary-class sub-class-14 datum.
- **d33-class explicit-MANEUVERING UAP recurrence — STAYS UNIQUE.** d35 returned to NONE Maneuverability; d33's `Sharp 90 degree turns` is still **single-attestation within sub-class 14**. Whether subsequent sub-class 14 datums recur explicit-maneuvering attestations remains open ^[open] (extends d33's open thread).
- **AFSOC LGLR rotational two-base lane at N≥3.** d33 ferry + d35 round-trip + d25 round-trip firm AFSOC LGLR-OJMS rotational at N=3 (1 ferry + 2 round-trip); whether further LIGHTNING-LINE-rotation pattern recurs (additional ferry attestation between LGLR and OJMS) is open ^[open]. d35's GENTEXT does NOT attest a LIGHTNING-LINE handover (distinct from d33).
- **VEO target-class recurrence — STILL N=1.** d35 source does NOT attest a GCP-VEO Global Campaign Plan field value (the field is absent from the OCR'd template) ^[extracted]. d33 remains the sole GCP-VEO attestation in dow-uap. Whether VEO-tasking recurs is open ^[open].
- **`2XAGM-114R9E 2XAGM-114R2` Hellfire load — class recurrence.** d35 first unredacted weapons load; whether further Block B (or other-block) Misreps carry similar unredacted weapons-load patterns is open ^[open]. The R9E (forward-firing thermobaric ^[inferred]) + R2 (multi-purpose ^[inferred]) mix is a SPECIFIC tactical load that may recur in 33 SOS LGLR sub-cluster ^[inferred].
- **AFSOC 33 SOS at N≥4.** d33 + d35 + d25 firm 33 SOS at N=3 within 3 months. Whether 33 SOS recurs (firming as a sustained AFSOC MQ-9 ISR lane within dow-uap) is open ^[open]. 33 SOS now corpus-attested at LGLR Greece launch base for all 3 attestations — whether 33 SOS operates from other bases is open ^[open].
- **AFSOC at N≥6.** d33 + d35 + d25 + d27 + d28 firm AFSOC at N=5 cross-event-date + cross-AOR + cross-platform. Whether AFSOC continues to anchor dow-uap full-Misrep beyond N=5 is open ^[open]. AFSOC is now the largest single MAJCOM in dow-uap full-Misrep class ^[inferred].
- **27 SOW at N≥6.** d33 + d35 + d25 + d27 + d28 firm 27 SOW at N=5 cross-SOS (33 SOS d33+d35+d25 + 3 SOS d27 + 16 SOS d28). Whether 27 SOW continues to anchor AFSOC ISR/CAS beyond N=5 is open ^[open].
- **56 SOIS at N≥5 — role-rotation pattern.** d33 + d35 + d25 + d27 firm 56 SOIS at N=4 cross-role (POC d25 + QC d27 + QC d33 + POC d35). Whether 56 SOIS recurs in a 5th role-attestation (firming the cross-role pattern) is open ^[open].
- **609 AOC Det 1 role-recurrence pattern.** d35 POC OC = **609 AOC Det 1** ^[extracted] — Det 1 RETURNS at d35 (after d33 absence). Det 1 cross-mission attestations now: d25 (POC home) + d27 (QC home) + d28 (absent) + d33 (absent) + d35 (POC home). The d33-anchored "Det 1 may be Block-F-routing-pipeline-specific" reading is **partially contradicted at d35** — d35 is Block B but carries Det 1 in POC OC role ^[extracted]. Det 1 reading at N=3 attestations across Block-F (d25 + d27) + Block-B (d35) ^[inferred] — Det 1 is **NOT block-specific**. Resolution at N≥1 additional AFSOC LGLR/EUCOM-launched Misrep with Det 1 attestation pattern ^[open].
- **UAP-during-RTB sub-pattern at N≥3.** d27 + d35 firm UAP-during-RTB at N=2 cross-launch-base. Whether further UAP observations occur during the RTB phase (vs on-station-task-prosecution) is open ^[open] — would firm at N≥3 RTB-phase UAP observation.
- **6X VEHICLES + PARKING GARAGE ROOFTOP COI annotation recurrence.** d35 first urban-area-COI-surveillance attestation with vehicle-count + structure-class annotation in dow-uap full-Misrep. Whether COI-on-rooftop / urban-COI-structure annotations recur is open ^[open].
- **Block-B Air-to-Ground Wpn declass posture cross-block.** d35 first explicit unredacted Air-to-Ground Wpn load (`2XAGM-114R9E 2XAGM-114R2`). Whether Block B's MDR-case `26-0019` consistently carries unredacted weapons-field declass posture across additional Block-B attestations is open ^[open]. Resolution at N≥1 additional Block B Full Misrep with weapons-field attestation.

## Cross-COCOM 432 AEW + 27 SOW operational lane summary at d35 ingest

At d35 ingest the dow-uap MQ-9 ISR + AC-130J posture spans **8 operational lanes** across **2 wings + 2 MAJCOMs + 3 platforms**:

| Lane | d* artifacts | COCOM | MAJCOM | Wing | Squadron | OC (exec) | Launch base | Land base |
|---|---|---|---|---|---|---|---|---|
| NAVCENT 2020 cluster | d60+d61+d62+d63+d64+d65 | USCENTCOM | (blank) | 432 AEW | 482ATKS | 609 CAOC | OKAS ^[inferred] | OKAS (round-trip) |
| OIR-Iraq 2022 | d10+d12+d18 | USCENTCOM | AFCENT/ACC | 432 AEW (d10+d18) + 163 AW (d12) | redacted/196 ATKS/482ATKS | 609 CAOC | (redacted) + OKAS | (round-trip) |
| EUCOM RUS-MED 2022 | d14 | USEUCOM | ACC | 432 AEW | 50 ATKS | 603 AOC | Sigonella LICZ | LICZ (round-trip) |
| OIR-Syria 2022-2023 | d16 + d19 | USCENTCOM | AFCENT | 432 AEW (d16) + 332 AEW (d19) | 89 ATKS + 389 EFS | 609 CAOC | OJMS Jordan | OJMS (round-trip) |
| NAVCENT-return 2023 | d23 | USCENTCOM | ACC | 432 AEW | 50 ATKS | 609 CAOC | OMAM UAE | OMAM (round-trip) |
| **AFSOC LGLR-OJMS rotational 2023-2024** | **d33 + d35 + d25** | **USCENTCOM** | **AFSOC** | **27 SOW** | **33 SOS** | **603rd** | **LGLR Greece** | **OJMS (d33) / LGLR (d35, d25)** |
| AFSOC ECW UAE 2024 | d27 | USCENTCOM | AFSOC | 27 SOW | 3 SOS | 609th | OMAM UAE | OMAM (round-trip) |
| AFSOC AC-130J Iraq 2024 | d28 | USCENTCOM | AFSOC | 27 SOW | 16 SOS | 609th | OKAS Kuwait ^[inferred] | OKAS (round-trip via AAAB) |

^[inferred] **d35 firms the AFSOC LGLR-OJMS rotational lane at N=3** (d33 1× ferry + d35 1× round-trip + d25 1× round-trip), all 33 SOS / 27 SOW / 56 SOIS / AN/DAS-4 TGT Pod / `GET` FMV-exploitation / 603rd executing OC. **Total operational lanes 8** (legacy 6 + 2 within AFSOC); 432 AEW MQ-9 ISR share refines to **12-of-17 = ~71%** within MQ-9 ISR + AC-130J subset.

## See also

- [[references/dow-uap-d33-mission-greece-2023-10-26]] — **sister mission** (filename twin, same 33 SOS Originator chain, same MDR 26-0019 Block B packet, same UAP morphology descriptor); d35 follows d33 by ~25h 55min between landings + ~38h between takeoffs; UAP morphology recurs at N=2
- [[references/dow-uap-d25-mission-greece-2024-01-25]] — third 33 SOS / 27 SOW / 56 SOIS / LGLR mission; d35 firms 33 SOS at N=3 + LGLR at N=3; d25 is +89 days after d35
- [[references/dow-uap-d27-mission-uae-2024-06-06]] — sister AFSOC mission + first UAP-during-RTB attestation; d35 firms UAP-during-RTB sub-pattern at N=2 cross-launch-base (3 SOS OMAM vs 33 SOS LGLR)
- [[references/dow-uap-d28-mission-iraq-2024-09-20]] — sister AFSOC mission (16 SOS AC-130J vs d35 33 SOS MQ-9); d35 firms AFSOC at N=5 cross-platform
- [[references/dow-uap-d23-mission-uae-2023-10-24]] — temporally adjacent d23 + d33 + d35 + d25 quadruple = tightest 4-Misrep sampling in dow-uap (~93 days span)
- [[references/dow-uap-d38-range-fouler-middle-east-may-2020]] — first Block B attestation
- [[references/dow-uap-d61-mission-persian-gulf-2020-08-27]] — second Block B FULL USMTF Misrep (2020 NAVCENT)
- [[references/dow-uap-d62-mission-strait-of-hormuz-2020-09-16]] — third Block B FULL USMTF Misrep (2020 NAVCENT)
- [[entities/dow-uap-foia-release]] — series anchor; d35 brings count to 33-of-~85, firms Block B at N=5 + AFSOC at N=5 + 33 SOS at N=3 + 27 SOW at N=5 + 56 SOIS at N=4
- [[entities/33-sos]] — recurs at N=3 (d33 + d35 + d25); LGLR Greece launch base at all 3 attestations
- [[entities/27-sow]] — recurs at N=5 (d33 + d35 + d25 + d27 + d28)
- [[entities/afsoc]] — recurs at N=5; now largest single MAJCOM in dow-uap full-Misrep class
- [[entities/603-aoc]] — seventh distinct 603 AOC role-attestation; d35 carries 603 AOC as APPROVER + 603rd executing (same as d33)
- [[entities/609-caoc]] — d35 QC OC = 609 CAOC; Det 1 returns at POC role (after d33 absence)
- [[entities/432-aew]] — d35 share refinement (12-of-17 = ~71% within MQ-9 ISR + AC-130J subset)
- [[entities/mq-9-reaper]] — d35 airframe ^[inferred] per AN/DAS-4 TGT Pod + 20:01 mission cycle + 33 SOS SOS attribution + 4× Hellfire AGM-114 weapons fit (Hellfire is MQ-9 primary kinetic loadout)
- [[concepts/uap-aircraft-engagement]] — sub-class 14 firms at N=5 with morphology-recurrence axis
- [[projects/uap/uap]]
