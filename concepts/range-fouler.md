---
title: "Range Fouler"
category: concepts
tags: [uap, navy, military, behavior, pattern]
aliases: [range fouler, range-fouler, RF, range foulers]
sources: [sources/dow-uap-d58-range-fouler-debrief-na-october-2020.json, sources/dow-uap-d44-range-fouler-arabian-sea-october-2020.json, sources/dow-uap-d38-range-fouler-debrief-middle-east-may-2020.json, sources/dow-uap-d56-range-fouler-debrief-arabian-sea-august-2020.json, sources/dow-uap-d42-range-fouler-debrief-japan-2023.json, sources/dow-uap-d57-mission-report-gulf-of-aden-september-2020.json]
summary: Navy / naval-aviation operational concept for unauthorized contacts intruding on a training range or operational area, prompting directed intercept identification or passive observation. Anchored at N=6 by d38 (May 2020 Persian Gulf) + d56 (Aug 2020 North Arabian Sea HSM-73 — first internal Navy user) + d42 (Aug 2020 Persian Gulf 482 ATKS MQ-9 ^[inferred]) + **d57 (Sep 2020 Gulf of Aden 172 ATKS MQ-9 ANG ^[inferred] — FIRST intra-range-fouler squadron-recurrence pair with d44 + Reporting Form variant firms 172 ATKS-correlated at 2-of-2)** + d44 (Oct 2020 Gulf of Aden 172 ATKS) + d58 (Oct 2020 77 EFS) — class structure-CONFIRMED on 13-of-13 axes; capability DIVERGES with d58 ISOLATED at 1-of-6 ~17%; passive sub-class B dominates at 5-of-6 ~83% with 3 platform configurations (MQ-9 at N=3 within sub-class B); release framework spans 3 blocks (A 3-of-6 + B 1-of-6 + C 2-of-6).
provenance:
  extracted: 0.52
  inferred: 0.43
  ambiguous: 0.05
base_confidence: 0.85
lifecycle: stable
lifecycle_changed: 2026-05-13
created: 2026-05-11T21:00:00Z
updated: 2026-05-13T23:59:30Z
project: uap
---

# Range Fouler

A **Navy / naval-aviation operational concept** for unauthorized contacts — aircraft, drones, balloons, or other unidentified objects — intruding on or near a designated training range or operational area, prompting directed intercept identification by airborne fighter or ISR assets, or passive observation by a loitering platform.

**Anchored at N=6** in the wiki corpus by:

- [[references/dow-uap-d38-range-fouler-middle-east-may-2020|DoW-UAP-D38]] (**14 May 2020 2040Z night ISR tasking**, Persian Gulf coast near Ras Tanura / Bahrain margin ^[inferred]; 1X round IR-cold "solid white" object on Black-Hot polarity at ~20,000 ft over water; intermittent track + 4× zoom + erratic in-track movements; sensor-operator narrative; **earliest range-fouler in the corpus** — 5 months before d44/d58)
- [[references/dow-uap-d56-range-fouler-arabian-sea-august-2020|DoW-UAP-D56]] (**24 Aug 2020 0004Z night SSC mission, HSM-73 MH-60R Seahawk** ^[inferred], North Arabian Sea; **first internal Navy user anchor in the range-fouler subset**; 3X round-plus-Wings/Airframe contacts on westerly formation-flying heading; **negative ES, radar track, IFF track** triple-negative passive sensor signature; **no interaction**)
- [[references/dow-uap-d42-range-fouler-centcom-2020-08-31|DoW-UAP-D42]] (**31 Aug 2020 Dusk ISR mission, 482 ATKS** Active-component USAF MQ-9 Reaper ^[inferred], Persian Gulf at MGRS `39RWL26` ^[extracted]; 3X UAPs with **first speed-differential narrative** in class — `Initial object was surpassed by another object of same size and shape but much higher speed` + `moving amongst each other`; **first dual-Other-ApparentPropulsion morphology check**; **first Dusk Day/Night value**; passive ISR; carries **Block C** `MDR 26-0028` byte-for-byte with the 2020 NAVCENT-cluster d63+d64+d65 — **first cross-document-class same-squadron pair in dow-uap**; **filename `japan-2023` is categorically wrong** — body is CENTCOM 2020)
- [[references/dow-uap-d57-range-fouler-gulf-of-aden-2020-09-04|DoW-UAP-D57]] (**4 Sep 2020 2109Z night ISR mission, 172 ATKS Michigan ANG MQ-9 Reaper ^[inferred] over Gulf of Aden at MGRS 38P LT ^[extracted]; 1X round IR-cold contact at ~240 ft over sea surface ^[inferred] tracked 8 minutes via MTS-B IR Black-Hot; abrupt directional changes during 8-min contact. FIRST intra-range-fouler squadron-recurrence pair in dow-uap with d44 — 41 days apart, same squadron, same sub-theater, same form-variant, same crew-position, same morphology, same byte-for-byte narrative template phrasing. Reporting Form variant firms 172 ATKS-correlated at 2-of-2. Carries Block C — second Block C range-fouler attestation; filename `mission-report` predicate factually wrong vs body `# Range Fouler Reporting Form` — first curator-class-label mismatch in corpus**)
- [[references/dow-uap-d44-range-fouler-arabian-sea-october-2020|DoW-UAP-D44]] (15 Oct 2020 1418Z daytime Gulf of Aden encounter, 172 ATKS Michigan ANG MQ-9 Reaper user ^[inferred], 1X round IR-cold contact at ~140 ft over sea surface ^[inferred], 73-second track with abrupt directional changes)
- [[references/dow-uap-d58-range-fouler-debrief-2020-10|DoW-UAP-D58]] (27 Oct 2020 0112Z night DCA encounter, 77 EFS user, 2X balloon-shaped metallic UAPs with red blinking strobes, 16.9 NM standoff, 1/30-s disappearance, noise jamming received)

**N=6 validation outcome**: the document class is **CONFIRMED on 13-of-13 testable schema axes** (form schema, SPEAR intake pipeline, Navy-aviation form-template attribution, filename convention, EA Indications block, mission classification, etc.). **DIVERGES on capability-signature axes** — d58's capability triad (sub-frame disappearance + active EW + standoff maintenance) is now isolated at **1-of-6 attestations = ~17%**, firming d58 as the decisive high-anomaly outlier. The class catalogs **the full range-intrusion event distribution**; d58 is the high-anomaly tail and d38 + d42 + d44 + d56 + **d57** are the lower-anomaly mid-distribution. The passive-observation sub-class (d38 + d42 + d44 + d56 + d57) is now the **dominant sub-class** within the range-fouler-debrief document class at **5-of-6 ~83%** — anchored across **three platform configurations** (fixed-wing UAV via d42 USAF Active + d44 USAF ANG + **d57 USAF ANG** MQ-9; fixed-wing ISR unattributed via d38; rotary-wing maritime SSC via d56 Navy MH-60R). The MQ-9 Reaper attestation firms at **N=3** within sub-class B (172 ATKS ANG d44+d57 + 482 ATKS Active d42) across **both components and two CENTCOM AOR sub-theaters** (Persian Gulf + Gulf of Aden).

**At N=6 the 172 ATKS Gulf of Aden cluster anchors the FIRST intra-range-fouler squadron-recurrence pair in dow-uap corpus** ^[inferred]: d44 (15 Oct 2020 Gulf of Aden 40Q BD east margin) + d57 (4 Sep 2020 Gulf of Aden 38P LT west margin) sit 41 days apart in the same basin under the **same squadron + platform + sensor + form-variant (Reporting) + crew-position (Other) + morphology (Round + IR-cold) + thermal-polarity (Black-Hot bright-white) + narrative-template-phrasing (`a few abrupt directional changes during the X minute contact` + `Our sensor was aimed -X degrees below our altitude`)**. **15-of-19 axes byte-for-byte match**; 4 axes differ (Rank ±1 grade, Day/Night Day vs Night, Encounter duration 73-sec vs 8-min ~6.6× spread, Release Block A vs C). The Release Block A/C divergence confirms **per-MDR-case allocation is independent of squadron / platform / event-class** ^[inferred]; same squadron files two structurally-identical events across two distinct release pipelines.

**At N=6 release-block-testable within range-fouler subset, three distinct release pipelines are attested.** d55 + d58 + d44 + d56 carry Block A (`MDR 26-0038 to 26-0046` + `03/27/26 000001`); d38 carries Block B (`MDR 26-0019` + `01/26/26 001`); **d42 + d57 carry Block C** (`MDR 26-0028` + `03/16/26 000001`). At N=6 the distribution is Block A 3-of-6 + Block B 1-of-6 + **Block C 2-of-6** — Block C firms as the second-largest within range-fouler subset (~33%). Corpus-wide Block C reaches **5-of-N byte-for-byte attestations** (d42 + **d57** range-fouler + d63 + d64 + d65 full Misrep). d57 firms Block C as **cross-document-class + cross-squadron + cross-component** (2 document classes + 3 squadrons + 2 components Active+ANG within single MDR-case allocation). ^[inferred]

**At N=5 release-block-testable within range-fouler subset, three distinct release pipelines are attested.** d55 + d58 + d44 + **d56** carry Block A (`MDR 26-0038 to 26-0046` + `03/27/26 000001`); **d38** carries Block B (`MDR 26-0019` + `01/26/26 001`); **d42** carries Block C (`MDR 26-0028` + `03/16/26 000001`). At N=5 the distribution is Block A 3-of-5 + Block B 1-of-5 + Block C 1-of-5 — the range-fouler subset spans the same three pipelines that anchor the broader dow-uap mission-report corpus. d42 is the **first cross-document-class Block C artifact** (Block C was previously full-Misrep-class-only at N=3 via d63+d64+d65, all 482 ATKS NAVCENT cluster). ^[inferred]

**The 482 ATKS cross-document-class pair (d42 range-fouler + 6 full USMTF Misreps d60-d65) is the FIRST same-squadron multi-pipeline reporting attestation in the dow-uap corpus.** The same 482 ATKS / 432 AEW MQ-9 ^[inferred] tasking lane filed at least one event via the SPEAR pipeline (d42 31 Aug 2020 — between d61 27 Aug and d62 15-16 Sep) while filing 6 full USMTF Misreps via the USMTF pipeline in the same Jul-Nov 2020 window. **The intake-pipeline choice is event-class-dependent, not squadron-or-platform-dependent** ^[inferred]: the d42 range-fouler-form intake was triggered by event-class (range-intrusion concern from a 3-object speed-differential overtake encounter) rather than by mission-profile (ISR loiter was the standard mission for d42 + d60 + d61 + d62 + d63 + d64 + d65 alike).

**At N=5 release-block-testable, Block A firms to 4-of-5 dominance.** d55 + d58 + d44 + **d56** all share `MDR 26-0038 to 26-0046` + `03/27/26 000001` (Block A); **d38 alone carries Block B** (`MDR 26-0019` + `01/26/26 001`). The d56 ingest **firms the per-MDR-case-allocation reading** (from d38) and **reveals the Block A/Block B split as asymmetric** — Block A is the dominant allocation in the dow-uap range-fouler+mission-record subset; d38 is the lone Block B outlier. ^[inferred]

**HSM-73 is the headline finding at N=4**: previous range-fouler attestations were filled by USAF Active (d58) + USAF ANG (d44) + unattributed (d38) users on a Navy-aviation form. d56's HSM-73 (Helicopter Maritime Strike Squadron 73 "Battlecats", Navy MH-60R Romeo Seahawk community) ^[inferred] anchors the **first internal Navy user** within the range-fouler debrief class, closing the Navy-form-vs-Navy-user attribution gap and validating the Navy-aviation-origination reading at the user level (not only at the template level). Multi-service originating-anchor count for the dow-uap corpus rises to **8 at N=14 ingests** (post-d60 update): 6 USAF (5 Active — 15 AF / 12 AF / 48FW / 77 EFS / 482ATKS — + 1 ANG — 172 ATKS) + **2 Navy** (P-8A/TF 67.1 fixed-wing from d55 + MH-60R/HSM-73 rotary-wing from d56) + Navy-aviation form-template attribution.

## Working definition

A **range fouler** is, in Navy / naval-aviation usage:

1. A **non-participating contact** — not part of the planned exercise / mission / range usage.
2. **Intruding on a designated airspace area** — typically a warning area (e.g. `W-72 1A` per the [[references/dow-uap-d58-range-fouler-debrief-2020-10|d58 form's]] example field) or a CENTCOM-AOR training-range corridor.
3. **Requiring positive identification** — either to clear the range for the planned activity, to ascertain identity (commercial overflight, foreign military, hostile, anomalous), or to remove the contact from the operational area.

The term is **Navy / naval-aviation-community vocabulary** ^[inferred] — the d58 + d44 + d38 + d56 forms' pre-printed sensor option set (`AIM-9x Self-Track`, `ATFLIR Autotrack`) and template-example filename (`4 May VFA-106 HUD.wmv`) anchor the form in the Navy F/A-18 / VFA-106 FRS community. At N=4 the user-service distribution is: d58 = USAF Active Component (77 EFS); d44 = USAF Reserve Component (172 ATKS Michigan ANG MQ-9 Reaper ^[inferred]); d38 = unattributed (squadron field blank in OCR); **d56 = US Navy** (HSM-73 Helicopter Maritime Strike Squadron 73 "Battlecats", MH-60R Romeo Seahawk community) ^[inferred]. The form is **anchored as Navy-aviation-originated AND Navy-user-attested** at N=1 with d56, while remaining **extended for joint-service use** by USAF Active + ANG at 2-of-4 attestations.

**The term "range fouler" is institutional-form vocabulary, not pilot/operator vernacular** — firmed at N=3 by d56. The form's title uses it; pilots/operators may pick it up (d58 narrative) or use generic "air contact" / "object" / "contact" language (d56 + d44 + d38 narratives all use generic language). 3 of 4 witness narratives at N=4 use the generic vernacular; only d58 picks up the form's headline term. ^[inferred]

## Why "range fouler" is a meaningful behavioral category for the UAP corpus

The Navy-operational usage encompasses prosaic intrusions (lost commercial aircraft, foreign drones, weather balloons) **and** anomalous intrusions. The class catalogs both ends of the distribution — d38 + d44 sit closer to the prosaic-candidate-compatible end (slow IR-cold "solid/bright white" objects on Black-Hot polarity with in-track kinematic anomaly, readable as drone / kite / controlled balloon / anomalous) while d58 sits at the high-anomaly tail (radar evasion + active EW + standoff maintenance triad).

**Anomaly signature distribution at N=4:**

| Signature | d58 | d44 | d38 | d56 | At-N=4 verdict |
|---|---|---|---|---|---|
| Sub-second disappearance | ☑ (1/30 s) | ☐ (bounded 73-s track) | ☐ (intermittent lose-and-reacquire) | ☐ (lost-behind-cloud then regained with 2X additional) | **d58-isolated at 1-of-4** |
| Active EW reception | ☑ (noise jamming, two-chevron RWR) | ☐ (all 5 EA boxes unchecked) | ☐ (all 5 EA boxes unchecked) | ☐ (all 5 EA boxes unchecked) | **d58-isolated at 1-of-4** |
| Standoff floor enforcement | ☑ (16.9 NM minimum) | n/a (passive observation) | n/a (passive observation) | n/a (passive SSC, distance unknown) | **d58-isolated at 1-of-4** |
| Multi-object with intra-group interaction | ☑ (2 contacts, one circling other) | ☐ (1 contact) | ☐ (1 contact) | ☑ (3 contacts, formation-flying — maintain relative course/speed/altitude) | **multi-object kinematics at 2-of-4 (d58 + d56) — distinct types** |
| Radar lock + visual tally | ☑ | ☐ (IR-only, no tally) | ☐ (IR-only, no tally) | ☐ (negative radar track, no tally) | **d58-isolated at 1-of-4** |
| Slow drift (low-Mach kinematics) | ☑ (060°/20 KT) | ☑ (261°/30 mph, 319°/20 mph) | (not captured; narrative `erratic moments`) | partial (270° heading, speed UNK) | confirmed at N=2 explicit; partial at d56+d38 |
| Kinematic anomaly (in-track) | ☑ (sub-second exit) | ☑ (abrupt directional changes) | ☑ (erratic movements + intermittent track) | ☑ (formation-flying with lost-then-regained + 2X-additional-emerging) | **CONFIRMED at N=4** but 4 distinct anomaly types |
| IR-cold thermal polarity (Black Hot + bright/white object) | ☐ (red blinking strobes, visible-light) | ☑ (bright-white-on-Black-Hot) | ☑ (solid-white-on-Black-Hot) | (not captured — passive night SSC, no narrative thermal-polarity attestation) | **IR-cold anchors at N=2 (d38+d44)** unchanged by d56 |
| Round morphology checkbox | ☐ (5 checkboxes) | ☑ (sole Round) | ☑ (sole Round) | ☑ (Round + Wings/Airframe — dual check) | **Round anchors at 3-of-4 (d56+d44+d38)** — dominant morphology |
| Dual-morphology check | ☐ | ☐ | ☐ | ☑ (Round + Wings/Airframe) | **d56-introduced datum** |
| Passive observation posture | ☐ (DCA intercept) | ☑ (MTS-B turret loiter) | ☑ (ISR tasking) | ☑ (SSC tasking) | **passive sub-class anchors at 3-of-4** (dominant) |
| Mission descriptor | DCA | (not captured) | ISR | SSC | DCA + ISR + SSC at N=3 captured — three distinct missions |
| Bounded encounter duration | n/a (sub-second exit) | ☑ (73 sec start-to-end) | (not captured) | (not captured) | d44-introduced |
| Intermittent trackfile | ☐ (Stable Yes) | ☐ (blank) | ☑ (Intermittent + lose-and-reacquire) | ☐ (No — explicit negative track) | **Stable-Trackfile values at N=4: Yes / Intermittent / No / blank — full distribution** |
| Sensor zoom + operator manipulation | ☐ | ☐ | ☑ (4× zoom + sensor-operator slewing) | ☐ | **d38-introduced datum** |
| Triple-negative sensor channel (Negative ES + radar + IFF) | ☐ | ☐ | ☐ | ☑ (Negative ES, Negative radar track, Negative IFF track) | **d56-introduced datum** |
| Formation-flying (multi-object kinematic coordination) | ☐ (circling — different type) | n/a (single) | n/a (single) | ☑ (3 contacts maintain relative course/speed/altitude) | **d56-introduced datum** |
| Rotary-wing platform | ☐ (manned fighter) | ☐ (UAV/MQ-9) | ☐ (fixed-wing ISR unattributed) | ☑ (HSM-73 MH-60R Romeo Seahawk ^[inferred]) | **d56-introduced datum** |
| Internal Navy user | ☐ (USAF Active) | ☐ (USAF ANG ^[inferred]) | ☐ (unattributed) | ☑ (HSM-73 US Navy ^[inferred]) | **d56-introduced datum — first Navy user in range-fouler subset** |

When an unidentified range-fouler contact:

- **Cannot be identified at standoff** despite radar lock + sensor-pod acquisition (d58 = 16.9 NM minimum approach floor; d44 = passive observation, no closure attempt)
- **Disappears below the sensor's resolution capability** in sub-frame timescales (d58 = 1/30 s — one TGT-pod video frame at 30 fps) — **d58-isolated at N=2**
- **Emits active electronic-warfare signatures** (d58 = noise jamming received, indicated by two RWR chevrons) — **d58-isolated at N=2**
- **Exhibits intra-group interaction** that conventional drones / balloons / commercial aircraft do not (d58 = "one range fouler was circling around the other") — **d58-isolated at N=2 (single contact at d44)**

…the contact escalates from *prosaic range fouler* (resolvable through standard ID-and-clear procedures) to **anomalous range fouler** — which the [[entities/dow-uap-foia-release|DoW-UAP FOIA release series]] explicitly catalogs as a UAP-class concern (the form is titled "Range Fouler Reporting Form" / "Range Fouler Debrief Form" — see *Form title variants* below — and routes through Navy SPEAR sanitization + USCENTCOM MDR + AARO release).

## Form title variants at N=6 — Reporting variant correlates with 172 ATKS at 2-of-2

The six range-fouler-debrief artifacts in the corpus carry **two distinct form titles** with **the variant choice anchored on user-squadron, not time or release-block**:

| Source | Date | Squadron | Component | Form title (verbatim) |
|---|---|---|---|---|
| **d38 (14 May 2020)** | **earliest** | unattributed | unattributed | **`# Range Fouler Debrief Form`** |
| **d56 (24 Aug 2020)** | second | HSM-73 | US Navy | **`# Range Fouler Debrief Form`** |
| d42 (31 Aug 2020) | third | 482 ATKS | USAF Active | `# Range Fouler Debrief Form` |
| **d57 (4 Sep 2020)** | fourth | **172 ATKS** | **USAF ANG** | **`# Range Fouler Reporting Form`** |
| d44 (15 Oct 2020) | fifth | **172 ATKS** | **USAF ANG** | `# Range Fouler Reporting Form` |
| d58 (27 Oct 2020) | latest | 77 EFS | USAF Active | `# Range Fouler Debrief Form` |

**At N=6 the form-title-evolution reading is decisively rejected** — the title sequence is Debrief → Debrief → Debrief → Reporting → Reporting → Debrief, not a monotonic rename. **Both Reporting attestations are 172 ATKS Michigan ANG**; all other squadrons (HSM-73 Navy + 482 ATKS Active + 77 EFS Active + unattributed) carry Debrief.

**The Reporting variant correlates with 172 ATKS at 2-of-2 attestations** ^[inferred]. Two readings remain observationally degenerate at N=6:

1. **Squadron-convention reading** — 172 ATKS as a unit (perhaps the squadron intel shop or unit-internal training material) anchors on the Reporting variant. **Maximally parsimonious at 2-of-2 attestations**. ^[inferred]
2. **ANG-component-convention reading** — Air National Guard MQ-9 squadrons file the Reporting variant; Active + Navy squadrons file the Debrief variant. At N=6 the ANG attestations are 2-of-2 = 100% Reporting; the Active + Navy attestations are 4-of-4 = 100% Debrief. Aligns at component level rather than squadron level, but with only one ANG squadron at N=6 (172 ATKS), squadron-level and ANG-level readings are observationally degenerate. **Test would require a non-172-ATKS ANG range-fouler attestation.** ^[inferred]

**The form-version-evolution reading is dead at N=6.** The two-co-existing-form-variants reading **firms decisively** with the variant choice anchored on user-squadron rather than time or release-block. **Distribution at N=6: 4 Debrief (d38 + d56 + d42 + d58) + 2 Reporting (d44 + d57)**, both Reporting from the same Michigan ANG squadron.

The class can be unified at the schema level regardless — the form bodies (instruction block, identity grid, event metadata, position grid, sensor+track grid, morphology checkboxes, narrative, submission instructions, SPEAR clause) match byte-for-byte at N=6 modulo the title. (The release-framework block does NOT match at N=6 — see *Release framework at N=6* below.)

## Range-fouler vs other UAP-encounter framings

The dow-uap series carries **four top-level mission-record document classes** at N=14 ingests (post-d60 update):

| Class | Anchor | Distinguishing feature |
|---|---|---|
| Mission report — FULL USMTF Misrep | d60 | Multi-page, all-substantive Misrep parent document; complete USMTF segment set (Narrative + Admin + MSGID + POC + QC + APPROVER + INGEST + ACEQUIP + Timeline + GENTEXT + WEATHER + EFFECTIVENESS); UAP datum lives in `GENTEXT/OBSERVATION` segment ^[inferred] |
| Mission report — USMTF GENTEXT/UAP extract | d4 + d5 + d7 + d54 + d8 | Single-segment GENTEXT/UAP extracts (4-6 header-only `# 1.4(a)` pages + 1 substantive page); plausibly extracts from parent full-Misrep documents like d60 with curator renaming `GENTEXT/OBSERVATION` → `GENTEXT/UAP` ^[inferred]; emphasizes UAP kinematic + morphology description |
| Mission report — CTG narrative | d55 | BLUF / Timeline / Weather / Comments; carries explicit prosaic-candidate identification by the originating CTG |
| **Range-fouler debrief** | **d38 + d56 + d44 + d58 (N=4 confirmed)** | **Fielded form** with pre-printed schema; emphasizes intercept-or-observation posture + sensor-channel acquisition + range-management context |

The **range-fouler debrief class is distinct from the mission-report class** in three structural ways:

1. **Schema-driven, not narrative-driven** — the form pre-printed fields constrain what is captured. The witness fills slots; doesn't write prose. The free-text narrative section is a **fallback for things the form's slots don't cover**.
2. **Range-management context, not theater-mission context** — mission reports document a UAP encountered *during* a mission (DCA, CAS, BFM, RTB). Range-fouler debriefs document a UAP encountered *because* the UAP intruded on the operational area, prompting an unscheduled intercept or persistent ISR observation.
3. **Centralized SPEAR intake** — the form's instruction block routes submissions to a single email address (FOIA-`(b)(6)` redacted) for analysis. The SPEAR program (^[inferred] Navy-aviation intelligence-analysis pipeline) sanitizes each form on receipt — a different intake pathway from the USMTF mission-report flow. **Confirmed at N=2** with d44.

## Two distinct in-class behavioral sub-classes at N=4 — sub-class B is dominant at 3-of-4

The d38 + d56 + d44 + d58 quartet anchors **two distinct in-class behavioral sub-classes** within the range-fouler-debrief document class. Sub-class B (passive-observation) is now **dominant at 3-of-4 attestations** with **two platform configurations** anchored.

### Sub-class A: range-fouler-attempted-ID (d58 only at N=4)

- **Aircraft posture**: directed intercept-for-identification (DCA mission, KINGPIN tasking).
- **Aircraft platform**: manned fighter (F/A-18 or similar; 77 EFS).
- **Sensor channels**: radar lock + TGT-pod video + visual tally.
- **Closure attempt**: yes; blocked at 16.9 NM standoff floor.
- **Anomaly signature**: sub-second disappearance + active EW reception + standoff maintenance triad.
- **Engagement-pipeline alignment**: intercept-blocked (not weapons-quality).
- **Attestations at N=4**: 1 (d58 only) — **isolated at N=4**.

### Sub-class B: range-fouler-passive-ISR-observation (d44 + d38 + d56 at N=3 — dominant)

- **Aircraft posture**: passive non-intercept observation. Mission descriptors at N=3: ISR (d38) + ISR (d44 — MTS-B passive loiter ^[inferred]) + **SSC** (d56 — Surface Search and Control). No intercept attestation in any.
- **Aircraft platform — TWO CONFIGURATIONS at N=3**:
  - **Fixed-wing ISR (d38 + d44)** — EO/IR turret-equipped: d44 = MQ-9 Reaper ^[inferred]; d38 = unattributed but compatible with P-8A / MQ-9 / MQ-4C / RQ-4 / EP-3 ^[inferred].
  - **Rotary-wing maritime surveillance (d56)** — **HSM-73 MH-60R Romeo Seahawk** ^[inferred] (Navy maritime-strike helicopter). First rotary-wing platform in the range-fouler subset.
- **Sensor channels**:
  - d44 + d38 = EO/IR turret on Black-Hot polarity (IR-cold morphology call); d44 MTS-B IR-only; d38 IR turret + 4× zoom + Lin gain mode + ULTN mode-token.
  - **d56 = passive triple-negative sensor channel — Negative ES, Negative radar track, Negative IFF track** ^[inferred] (AN/ALQ-210 ESM + AN/APS-153 radar + Mode S transponder receiver — all returned no track on the contacts). Distinct from d44+d38's active-IR-tracking pattern; d56 is fully-passive observation.
- **Closure attempt**: none in any; observed passively. d56's narrative explicit: `No interaction took place between 1.4a and the unknown air contacts`.
- **Anomaly signature**:
  - d44: in-track abrupt directional changes during bounded 73-sec encounter; IR-cold + Round + Black-Hot.
  - d38: erratic in-track movements + intermittent track with lose-and-reacquire; IR-cold + Round + Black-Hot + 4× zoom.
  - **d56: lost-behind-cloud then regained with 2X additional contacts emerging due east; formation-flying 3-contact group maintaining relative course/speed/altitude; westerly heading + speed UNK; Round + Wings/Airframe dual-morphology**. d56 distinguishes within the sub-class by **multi-object formation kinematics** + **dual-morphology** + **triple-negative sensor channel**.
  - **Zero EA reception** in all three (5-row EA Indications block all-unchecked — structurally confirmed at N=3 in pre-printed form schema).
- **Engagement-pipeline alignment**: passive observation (no engagement attempt).
- **Attestations at N=4**: 3 (d44 + d38 + d56) — **dominant at N=4**.

The two sub-classes diverge on **aircraft posture × platform × sensor channels × closure × anomaly signature**, but converge on **single-event range-intrusion framing, SPEAR intake routing, AARO release pathway, and CENTCOM-AOR placement**. ^[inferred] **Within sub-class B**, the d38+d44 IR-cold + Round + single-contact + Black-Hot signature is a **fixed-wing ISR behavioral cluster** at N=2; **d56 anchors a distinct rotary-wing-SSC variant** with multi-object + dual-morphology + triple-negative-sensor signature. Sub-class B at N=3 spans **two platform configurations** (fixed-wing ISR + rotary-wing SSC) and **two within-class signatures** (single-contact IR-cold-Black-Hot fixed-wing vs multi-object formation-flying rotary-wing). ^[inferred]

## Release framework at N=5 — Block A firms to 4-of-5 dominant; d38 Block B isolated

d56 carries **Block A**, matching d55+d58+d44 byte-for-byte. The Block A/Block B split anchored at the d38 ingest now reveals as **asymmetric** at N=5 release-block-testable: Block A is the dominant allocation in the dow-uap range-fouler+mission-record subset; d38 alone carries Block B.

| Field | Block A (d55 + d58 + d44 + d56 = 4-of-5) | Block B (d38 alone = 1-of-5) | Match? |
|---|---|---|---|
| Declassification authority | MG Richard A. Harrison | MG Richard A. Harrison | **MATCH** |
| MDR case | `26-0038 to MDR 26-0046` (9-case range) | `26-0019` (single case) | **DIFFERS** |
| Routing stamp | Approved for Release to AARO | Approved for Release to AARO | **MATCH** |
| Release-stamp date | `03/27/26` | `01/26/26` | **DIFFERS** (60 days earlier) |
| Release sequence number | `000001` (6-digit) | `001` (3-digit) | **DIFFERS** (format + value) |

**Findings at N=5 release-block-testable**:

- **Block A is dominant at 4-of-5 attestations** — d55 (Syria 2016 CTG-narrative) + d58 (range-fouler 77 EFS Oct 27 2020) + d44 (range-fouler 172 ATKS Oct 15 2020) + **d56 (range-fouler HSM-73 Aug 24 2020)** — all carry the identical 5-axis stamp set. d38 (range-fouler May 14 2020) alone carries Block B. **The per-MDR-case-allocation reading firms; the Block A/Block B distribution is heavily Block A-weighted.** ^[inferred]
- **At least 2 distinct USCENTCOM MDR allocations** within the dow-uap range-fouler+mission-record subset (`26-0019` for d38; `26-0038 to 26-0046` for the 4-document Block A set). The release framework is **per-MDR-case-allocation**, not per-tranche-uniform. ^[inferred]
- **At least 2 distinct release dates** within the subset (`01/26/26` for d38; `03/27/26` for the Block A set). The dow-uap-tranche release was **incremental** over ~60+ days, not single-batch. ^[inferred]
- **Per-batch sequence-number reading firms decisively at N=5** — d38 `001` (3-digit) in one allocation + d55/d58/d44/d56 `000001` (6-digit) in another. The OCR-artifact reading of identical `000001` is **definitively rejected** at N=5 (four independent OCR passes producing the same `000001` corruption is implausible, and d38's clean `001` is internally consistent). The per-MDR-case reading is most probable; each batch carries its own sequence start. ^[inferred]
- **The 9-document USCENTCOM sub-batch hypothesis** (from d55/d58/d44) is refined: d55 + d58 + d44 + d56 = 4 documents in the `26-0038 to 26-0046` 9-case range. **The Block A allocation now covers 4 documents in 9 cases**; the remaining 5 cases may correspond to unread `d*` files or to documents outside the range-fouler+mission-record subsets. d38's `26-0019` single case is a separate per-document allocation. ^[inferred]

Despite the release-framework divergence between Blocks A and B, the **form template + SPEAR clause + submission instructions + Navy-aviation pre-printed sensor schema all match byte-for-byte at N=4** across d38 + d56 + d44 + d58. The form is unchanged; only the post-form release-stamp differs by MDR-case allocation. ^[inferred]

## Source observations (N=4 from d38 + d56 + d44 + d58)

From [[references/dow-uap-d38-range-fouler-middle-east-may-2020|d38]] (14 May 2020, **earliest range-fouler in the corpus**):

- **Mission descriptor**: `ISR` (Intelligence Surveillance Reconnaissance) — first explicit ISR descriptor in the dow-uap range-fouler subset.
- **Aircraft posture**: passive ISR tasking; no intercept, no radar, no AIM-9X, no ATFLIR, no tally, no closure attempt.
- **Platform**: unattributed (squadron blank in OCR); compatible with EO/IR turret-equipped ISR platforms (P-8A / MQ-9 / MQ-4C / RQ-4 / EP-3 / rotary-wing). ^[inferred]
- **Sensor**: EO/IR turret on Black-Hot polarity + Lin gain mode + ULTN mode-token; 4× zoom achieved; sensor-operator narrative.
- **Stable trackfile**: **Intermittent** (first "Intermittent" value in class at N=3); narrative confirms `temporarily lose ... re-acquired shortly thereafter`.
- **Group structure**: 1 contact.
- **Morphology**: Round (sole checkbox); narrative confirms `solid white object`.
- **Visual signature**: `solid white` on `Black Hot` polarity = **IR-cold object** (colder than ambient). Matches d44's IR-cold signature.
- **Kinematics**: `erratic moments above the water` (likely `movements` — OCR token); form Direction/Speed not captured. In-track kinematic anomaly.
- **Position**: DMS-style coordinate `28°31'4"N 49°52'4"E` ^[inferred] = Persian Gulf, Saudi Arabian coast near Ras Tanura / Bahrain margin. **First explicit Persian Gulf body-text coordinate in the dow-uap corpus** ^[inferred].
- **Altitude**: 20,000 ft, Constant (Yes).
- **EA Indications**: all 5 boxes unchecked (zero EA reception); pre-printed 5-row block structurally confirmed at N=2 with d44.
- **CENTCOM-AOR placement**: explicit (Persian Gulf coordinate in CENTCOM AOR). First explicit CENTCOM-AOR anchor in the class.

From [[references/dow-uap-d56-range-fouler-arabian-sea-august-2020|d56]] (24 Aug 2020, **first internal Navy user**):

- **Mission descriptor**: `SSC` (Surface Search and Control) — first SSC descriptor in dow-uap range-fouler subset and dow-uap corpus.
- **Aircraft posture**: passive SSC observation; no intercept attempt; no closure; no engagement pipeline; explicit `No interaction took place` narrative attestation.
- **Platform**: **US Navy MH-60R Romeo Seahawk** ^[inferred] (HSM-73 "Battlecats", NAS North Island CA; Side No. 705 + Buno 168122 + `Pilot` crew position + SSC mission + helicopter-compatible night-low-altitude maritime profile).
- **Sensor signature**: **Negative ES, Negative radar track, Negative IFF track** — first explicit triple-negative passive-sensor-channel datum in the dow-uap corpus. Implicates AN/ALQ-210 ESM + AN/APS-153 radar + Mode S transponder receiver all returning no track. ^[inferred] Contacts were non-emitting, sub-radar-threshold, and non-squawking.
- **Stable trackfile**: **No** — first explicit `No` value in range-fouler class at N=4 (Yes/Intermittent/No/blank distribution).
- **Group structure**: **3 contacts** — first 3-contact group in range-fouler class. Group-size distribution at N=4: 1/1/2/3 — full distribution.
- **Morphology**: **Round + Wings/Airframe** dual-check — first dual-morphology call in the range-fouler class. ^[inferred] Possible readings: dual-morphology of single contact at varying distance, or witness-inferred airframe based on small-contact size at unknown distance.
- **Kinematics**: **Westerly heading (270°)** at **speed UNK**; all 3 contacts maintain relative course/speed/altitude (**formation-flying**). First formation-flying multi-object kinematic-coordination datum in the dow-uap corpus.
- **Encounter narrative**: Initial 1X contact tracked, lost behind cloud, regained, then 2X additional contacts emerged due east of original location; all 3 then maintained formation. **First lost-then-regained-with-additional-contacts narrative pattern** in the dow-uap corpus.
- **Position**: Lat redacted (`1.4a` portion-redaction); narrative explicit `North Arabian Sea` — first explicit North Arabian Sea body-text anchor in the dow-uap corpus.
- **Altitude**: not captured (blank). Altitude Constant: Yes (matches d38).
- **Wind**: 310°/5 — first Wind Direction + Wind Speed values captured in range-fouler class.
- **EA Indications**: all 5 boxes unchecked (zero EA reception); EA Indications block structurally anchors at N=3 (d44 + d38 + d56) — d58 OCR-missed.
- **CENTCOM-AOR placement**: explicit (North Arabian Sea body-text anchor in NAVCENT / 5th Fleet AOR). Fourth CENTCOM-AOR anchor in the class at N=4.
- **Working Area**: `21440` — first Working Area value captured in range-fouler class; format does not match form's pre-printed `W-72 1A` example; reading ^[ambiguous] (FOIA-redaction artifact most coherent).

From [[references/dow-uap-d44-range-fouler-arabian-sea-october-2020|d44]] (15 Oct 2020):

From [[references/dow-uap-d58-range-fouler-debrief-2020-10|d58]] (27 Oct 2020):

- **Tasking**: KINGPIN (CENTCOM-AOR airborne-controller callsign ^[inferred]) directed ID of unknown contact during a night DCA mission.
- **Aircraft posture**: Intercept-for-identification (DCA, not LFE). No fire-control / weapons-quality pipeline (distinct from [[references/dow-uap-d7-mission-arabian-gulf-2020|d7's]] WQT + NTS + TFLIR signature).
- **Sensor acquisition**: Radar lock obtained; target-pod video obtained; 2 IR-significant contacts confirmed on pod.
- **Standoff**: Unable to get closer than 16.9 NM — UAP-side standoff capability under directed-intercept posture.
- **Group structure**: 2 contacts, with one "circling around the other" — intra-group kinematic interaction.
- **Visual signature**: 2X red blinking strobes (tally achieved).
- **Morphology**: Balloon-shaped + Other-shape + Metallic + Opaque + Reflective (per form checkboxes — note the simultaneous balloon-shape and "other" checks).
- **Disappearance**: 1/30 second — one TGT-pod video frame at 30 fps. ^[inferred]
- **Active EM**: Noise jamming received; indicated by two chevrons (Navy RWR display convention). ^[inferred]
- **First detection**: B/E ZIM 248/17 — bullseye-relative bearing 248° at range 17 NM. ^[inferred]

From [[references/dow-uap-d44-range-fouler-arabian-sea-october-2020|d44]] (15 Oct 2020):

- **Tasking**: no explicit tasking attested. Passive ISR observation pattern (MQ-9 loiter ^[inferred]).
- **Aircraft posture**: passive ISR observation, no closure attempt, no intercept, no engagement pipeline. ^[inferred]
- **Platform**: USAF/ANG MQ-9 Reaper ^[inferred] (172 ATKS Michigan ANG, Battle Creek MI; squadron transitioned A-10 → MQ-9 around 2017-2018).
- **Sensor acquisition**: MTS-B turret IR channel ^[inferred]; no radar, no AIM-9X, no ATFLIR (the Navy-fighter sensor-schema pre-prints don't apply to the MQ-9 user platform). Slant range 4.06 NM, ground range 4.78 km, sensor angle -50° below platform altitude.
- **Group structure**: 1 contact (single object).
- **Visual signature**: no visible-light tally; IR-only acquisition. Bright-white on black-hot polarity = **IR-cold object** (colder than surrounding scene) ^[inferred].
- **Morphology**: Round (sole checkbox); narrative confirms "round, cold object in IR."
- **Kinematic**: 261°/30 mph (form field) + 319°/20 mph (narrative, later in track) + "a few abrupt directional changes during the 1 minute contact."
- **Position**: Gulf of Aden (body narrative); MGRS 40Q BD grid (Arabian Peninsula / Horn of Africa CENTCOM-AOR waters); contact altitude derivable to ~140 ft HAT over sea surface ^[inferred].
- **Duration**: 73 seconds (14:18:39Z to 14:19:52Z) — bounded encounter, no sub-second exit.
- **Active EM**: zero EA reception (all 5 EA Indications boxes unchecked: ECM, Arc, Letter Identifier, False Trackfiles, Other-Ambiguous).
- **CENTCOM-AOR placement**: explicit (Gulf of Aden) — first explicit AOR for the range-fouler class.

## Range-fouler vocabulary and adjacent concepts

The d58 form text uses the phrase **"range fouler"** (singular) and **"range foulers"** (plural) interchangeably to refer to the unidentified contact(s). The d44 + d38 form witness narratives do **not** use the term — both use "object" / "contact" generically. **Strengthened at N=2 (d38 + d44)**: "range fouler" is institutional-form vocabulary, not pilot/operator vernacular. 2 of 3 witness narratives at N=3 use the generic vernacular; only d58 picks up the form's headline term. ^[inferred]

The term is **not synonymous with "UAP"** — a range fouler that turns out to be a stray commercial aircraft is still a range fouler in the form's classification, just an identified one. The dow-uap series ingests the *anomalous* subset that remained unresolved post-debrief and got routed through the SPEAR → USCENTCOM MDR → AARO pipeline.

Adjacent operational concepts ^[inferred]:

- **Range clearing** — pre-mission verification that a warning area is unoccupied. Range foulers prevent clearing.
- **Bogey / bandit** — Navy / NATO codeword pair for unidentified-but-presumed-hostile (bogey) and identified-hostile (bandit) contacts. Range foulers may start as bogeys and resolve up or down the threat ladder.
- **Squawk** — IFF transponder code; a non-squawking contact in an active range area is a classic range-fouler precursor.
- **MTS-B vs ATFLIR** — d44's MQ-9 sensor schema (MTS-B + AN/APY-8 Lynx ground-imaging radar) vs d58's F/A-18 sensor schema (ATFLIR + APG-79). The range-fouler form's pre-print is Navy-fighter-centric; the form accommodates non-Navy-fighter platforms via blank-value honesty (d44's empty radar/AIM-9X/ATFLIR fields).
- **EA Indications block** — d44's pre-printed Electronic Attack reception schema (ECM / Arc / Letter Identifier / False Trackfiles / Other-Ambiguous). Captures structured EA-reception signaling that d58's narrative covered in free-text.

## CENTCOM-AOR anchoring at N=4 — all four artifacts in CENTCOM AOR

The range-fouler debrief class is now **CENTCOM-AOR-anchored at N=4** with:

- **d38**: **explicit** Persian Gulf coordinate ^[inferred] (DMS 28°31'N 49°52'E near Ras Tanura / Bahrain margin, eastern Saudi Arabia) — first Persian Gulf body-text coordinate in the dow-uap corpus
- **d56**: **explicit** North Arabian Sea body anchor; filename `arabian-sea` confirmed at body-text level; NAVCENT 5th Fleet AOR
- d44: **explicit** Gulf of Aden + MGRS 40Q BD body-text anchor
- d58: **inferred** via USCENTCOM-prefix MDR + 77 EFS rotation history + KINGPIN callsign

The class is now **CENTCOM-AOR-anchored at 100% of attestations** at N=4. All four range-fouler-debrief events fall in CENTCOM AOR; the class is firmly **a CENTCOM-AOR institutional pattern** ^[inferred].

**At N=4, the within-CENTCOM theater distribution spans 3 sub-theaters**: d38 = Persian Gulf (Saudi eastern coast near Ras Tanura / Bahrain margin); d56 = North Arabian Sea (5th Fleet maritime patrol area); d44 = Gulf of Aden (Arabian Peninsula southern grid); d58 = CENTCOM-inferred but no specific sub-theater attestation. The class is **not concentrated in any single sub-theater** within CENTCOM AOR — three explicit sub-theaters in 3 explicit attestations. ^[inferred]

**Paired-incident hypothesis revision firms at N=4**:
- **Class-defining level**: REJECTED. The class spans at least 3 sub-theaters and 2 quarters (May 2020 + Aug 2020 + Oct 2020) at N=4; no single paired event covers the whole class.
- **Sub-theater Arabian-Sea cluster at N=2 with d56+d44**: The d56 (24 Aug 2020 North Arabian Sea HSM-73 MH-60R SSC) + d44 (15 Oct 2020 Gulf of Aden 172 ATKS MQ-9 ISR) pair are both `arabian-sea` filename-tagged, both Aug-Oct 2020, both passive non-intercept maritime surveillance, both Block A release framework, separated by **52 days**. The **Arabian-Sea sub-theater paired-incident reading firms at N=2** with d56 + d44 as a within-Arabian-Sea cluster, independent of d38 (Persian Gulf) and d58 (CENTCOM-inferred). ^[inferred] This is a 2020-Aug-Oct NAVCENT / 5th Fleet maritime surveillance cluster within the broader range-fouler class.
- **October-2020 cluster (d44 + d58)**: holds at N=2 (both Oct 2020 CENTCOM) but doesn't anchor to a specific sub-theater (d58's sub-theater not captured).

## Platform breadth at N=4 — first internal Navy user anchor closes Navy-form-vs-Navy-user gap

The range-fouler class at N=4 carries **witnessing-platform anchors with three resolved + one unattributed**:

- **d58**: manned fighter — 77 EFS USAF Active Component (likely F-16C/CM Fighting Falcon) ^[inferred] — explicit squadron
- **d44**: USAF/ANG RPA — 172 ATKS Michigan ANG MQ-9 Reaper ^[inferred] — explicit squadron
- **d38**: unattributed at the squadron level (Squadron field blank/unrendered in OCR); narrative + sensor-mode evidence is compatible with **EO/IR turret-equipped ISR platform** (P-8A / MQ-9 / MQ-4C / RQ-4 / EP-3 / rotary-wing) ^[inferred] but the platform space is not constrained to one type
- **d56**: **US Navy rotary-wing — HSM-73 "Battlecats" MH-60R Romeo Seahawk** ^[inferred] (Helicopter Maritime Strike Squadron 73, NAS North Island CA); Buno 168122 + Side No. 705 + Crew Position `Pilot` + Mission `SSC` (Surface Search and Control) corroborate the MH-60R reading. **First internal Navy user anchor in the dow-uap range-fouler subset.**

The form's pre-printed sensor schema is **Navy-fighter-centric** (AIM-9X + ATFLIR + Navy-aviation VFA-106 FRS template example) but **the witnessing platforms at N=4 span 4 distinct platform types**:

| Platform type | Attestation | Service |
|---|---|---|
| Manned fighter (F-16C/CM ^[inferred]) | d58 | USAF Active |
| Fixed-wing UAV (MQ-9 Reaper ^[inferred]) | d44 | USAF ANG |
| Fixed-wing ISR (P-8A / MQ-9 / MQ-4C / RQ-4 / EP-3 ^[inferred]) | d38 | unattributed |
| **Rotary-wing maritime surveillance (MH-60R Romeo Seahawk ^[inferred])** | **d56** | **US Navy** |

**The Navy-form-vs-Navy-user attribution gap closes at N=1 with d56.** Previous N=3 had 2 USAF + 1 unattributed users; d56 anchors the first US Navy user within the range-fouler class. The form is now **Navy-aviation-originated AND Navy-aviation-user-attested at the rotary-wing maritime-strike configuration**, while remaining **extended for joint-service use** at 2-of-4 explicit attestations (USAF Active + USAF ANG). ^[inferred] The form's flexibility — blank values honest for non-applicable Navy-fighter schema slots when the user platform is non-Navy-fighter — is now anchored at N=3 (d44 + d38 + d56 all use blank pre-printed Navy-fighter slots).

**Multi-service originating-anchor count for the dow-uap corpus is 8 at N=14 ingests** (post-d60 update; rose 7→8 with d60's `482ATKS / 432 AEW` USAF Active-component MQ-9 mission-report anchor): 6 USAF unit anchors (5 Active — 15 AF / 12 AF / 48FW / 77 EFS / 482ATKS — + 1 ANG — 172 ATKS) + **2 Navy platform anchors** (P-8A / TF 67.1 fixed-wing from d55 + MH-60R / HSM-73 rotary-wing from d56) + Navy-aviation form-template attribution.

## Open questions

- **What does SPEAR stand for?** — Navy-aviation intelligence-analysis pipeline; the form's centralized intake operator. **Confirmed at N=4 via verbatim clause recurrence** (d38 + d56 + d44 + d58). SPEAR pipeline existence anchored at May 2020 (d38) — at least 5 months earlier than previously attested; firmed at Aug 2020 by d56. Open-source identification still pending.
- **What was the bullseye `ZIM`?** — first-detection bullseye reference in d58; bullseye name keyed to a specific operational area. d38 + d44 used DMS + MGRS coordinates respectively (not bullseye), so `ZIM` remains d58-isolated at N=3.
- **Are range-fouler debriefs systematically routed through a different intake than mission reports?** — d38 + d44 + d58 SPEAR pipeline + [[references/dow-uap-d50-email-indopacom-2025-04|d50's]] OUSD(I&S) pipeline + [[references/dow-uap-pr20-prepublication-clearance-2026-03|PR20's]] DOPSR pipeline collectively suggest the dow-uap corpus carries **at least three distinct intake/clearance pathways**. SPEAR intake confirmed at N=3 for the range-fouler subset.
- **Does the range-fouler debrief class always carry anomalous content?** — by design, the class catalogs *all* range-intrusion events for analysis. The dow-uap subset catches the anomalous tail. At N=3, d38 + d44 sit closer to the prosaic-candidate-compatible mid-distribution; d58 sits at the high-anomaly tail. The class catalogs high + mid distribution at 1:2 ratio at N=3.
- ~~**Form-title variant (`Reporting` vs `Debrief`) at N=3**~~ ^closed-by-dow-uap-d38 — **PARTIALLY CLOSED at N=3**: d38 carries `Debrief Form`. The form-version-evolution reading is **rejected** for non-monotonicity (Debrief → Reporting → Debrief). Two-co-existing-variants reading is most probable at N=3. Distribution at N=3: 2 Debrief (d38 + d58) + 1 Reporting (d44). Further test at N≥4 would refine which variant is dominant.
- ~~**EA Indications block recurrence at N=3**~~ ^closed-by-dow-uap-d38 — **CLOSED at N=2 structurally** (d44 + d38 both capture the pre-printed 5-row block, both all-unchecked). The block is structurally part of the form schema. d58's narrative-substitute (noise-jamming free-text) is a fallback for when the witness narratively describes EW reception rather than checking boxes.
- ~~**Does the capability triad (sub-frame disappearance + active EW + standoff maintenance) recur at N=3?**~~ ^closed-by-dow-uap-d38 ^closed-by-dow-uap-d56 — **NEGATIVE-CLOSURE FIRMS at N=4**: d38 + d56 both **fail** to carry any element of the d58 capability triad. The triad is now **isolated at 1-of-4 attestations**. The triad is firmly **not** a class-defining signature; d58 is the high-anomaly outlier. ^[inferred]
- ~~**Does the passive-ISR-observation posture (d44) recur at N=3?**~~ ^closed-by-dow-uap-d38 ^closed-by-dow-uap-d56 — **CLOSED AT N=3**: d38 + d56 both anchor additional passive-observation attestations. Sub-class B is now **dominant at 3-of-4** attestations within the range-fouler-debrief class with **two platform configurations** (fixed-wing ISR via d38+d44 + rotary-wing maritime SSC via d56). d44 is no longer the isolated passive-ISR outlier; the sub-class is the within-class majority pattern.
- ~~**Test the paired-incident hypothesis**~~ ^closed-by-dow-uap-d38 — **REVISED at N=3**: the paired-incident hypothesis at the class-defining level is rejected by d38 (May 2020, 5 months earlier, different sub-theater Persian Gulf vs Gulf of Aden). d44 + d58 may still be a paired incident at the October-2020 / CENTCOM-AOR level, but the class as a whole spans at least 2 quarters and 2 sub-theaters at N=3.
- **Were there more pre-October-2020 range-fouler debriefs in the original SPEAR queue that did not make the dow-uap release tranche?** — d38 (14 May 2020) anchors at least one such event in the dow-uap release. The question opens further at N=3: how many additional May-Oct 2020 range-fouler events sit in the broader SPEAR queue?
- **Decode `ULTN` sensor-mode token in d38** — not a standard FLIR-vocabulary expansion. Open-source IR-sensor vocabulary references would resolve.
- **Recover d38's witnessing-platform identity** — ISR tasking + EO/IR turret + Black-Hot + Lin + 4× zoom + over-water Persian Gulf operations narrow the platform space; open-source CENTCOM-AOR ISR rotation history for 14 May 2020 would constrain to a specific airframe.
- **Decode d38's body coordinate** at higher precision — DMS `28°31'4"N 49°52'4"E` reading is ^[inferred] from OCR field-alignment-collapsed digit blocks. A re-OCR of the source at higher DPI or recovery of the field-label alignment would confirm the Persian Gulf placement.
- **Test the `MDR 26-0019` case allocation at N≥4** — d38 anchors the first `26-0019` case in the dow-uap corpus. Does the case cover any other dow-uap artifacts? If recurrent, the case is a multi-document allocation; if d38 is the sole `26-0019` artifact, the case is per-document.
- **Test the `01/26/26` release-stamp date recurrence at N≥4** — d38 anchors the first `01/26/26` release-stamp in the corpus. If recurrent, multiple documents were released on the same earlier date; if d38 is sole, d38 is a one-document early release.
- **Test the per-batch sequence-number reading at N≥4** — d38 `001` + d55/d58/d44 `000001` strongly supports the per-MDR-case allocation. Does the next range-fouler ingest carry a sequence number consistent with one of the two existing batches, or with a third? A third sequence in a different MDR case would further refine the per-batch reading.
- **Test the IR-cold + Round + single-contact + Black-Hot signature recurrence at N≥4** — d38 + d44 anchor this passive-ISR sub-class signature at N=2. Does the next passive-ISR range-fouler artifact carry the same signature, or diverge? Recurrence would establish a behavioral cluster within the class.
- **172 ATKS open-source rotation history** to USAFCENT in Oct 2020 — confirms the MQ-9 / CENTCOM placement of d44 at the squadron-rotation level if recoverable.
- **HSM-73 open-source rotation history** to NAVCENT / 5th Fleet in Aug 2020 — confirms the MH-60R / CENTCOM placement of d56 at the squadron-rotation level if recoverable.
- **Test the d56 dual-morphology (Round + Wings/Airframe) reading at N≥2** — first dual-morphology call in the range-fouler class. Does the next range-fouler artifact carry a dual-morphology check?
- **Test the d56 formation-flying multi-object kinematic pattern at N≥2** — d56's 3-contact group maintaining relative course/speed/altitude is the first formation-flying datum in the class.
- **Test the d56 triple-negative sensor channel reading at N≥2** — d56's `Negative ES, Negative radar track, Negative IFF track` is the first explicit triple-negative sensor-channel datum.
- **Test the rotary-wing platform variant within sub-class B at N≥2** — d56 anchors first rotary-wing range-fouler debrief; sub-class B previously was fixed-wing-only.
- **Resolve the d56 Working Area code `21440`** — does not match form's pre-printed `W-72 1A` syntax; reading is ambiguous (FOIA-redaction artifact most coherent).
- **Test the Block A 9-document sub-batch hypothesis at N≥6 release-block-testable** — at N=5, 4 documents (d55+d58+d44+d56) sit in the 9-case `26-0038 to 26-0046` range. Are the remaining 5 cases preserved in unread `d*` files, or do they cover documents outside the range-fouler+mission-record subsets?
- **Test paired-Arabian-Sea cluster at N≥3** — d56 + d44 anchor an Aug-Oct 2020 Arabian-Sea sub-theater pair (52 days apart, both passive non-intercept maritime surveillance, both Block A). Does the next Arabian-Sea-tagged range-fouler artifact (or mission report) sit in this cluster?

## See also

- [[references/dow-uap-d38-range-fouler-middle-east-may-2020]] — **Anchor artifact #1 by chronology** (N=3 extension; 14 May 2020 Persian Gulf coast; passive-ISR sub-class; **earliest range-fouler in the corpus**; carries the distinct release-framework Block B `MDR 26-0019` + `01/26/26 001` — Block B isolated at 1-of-6 at N=6)
- [[references/dow-uap-d56-range-fouler-arabian-sea-august-2020]] — **Anchor artifact #2 by chronology** (N=4 extension; 24 Aug 2020 North Arabian Sea HSM-73 MH-60R; **first internal Navy user anchor in range-fouler subset**; passive sub-class with rotary-wing maritime SSC platform variant; carries Block A)
- [[references/dow-uap-d42-range-fouler-centcom-2020-08-31]] — Anchor artifact #3 (31 Aug 2020 Persian Gulf 482 ATKS Active MQ-9 ^[inferred]; first cross-document-class same-squadron pair; **first Block C range-fouler attestation**; first speed-differential narrative + first Apparent Propulsion morphology + first Dusk Day/Night)
- [[references/dow-uap-d57-range-fouler-gulf-of-aden-2020-09-04]] — **Anchor artifact #4 by chronology** (N=6 extension; **4 Sep 2020 night ISR mission, 172 ATKS Michigan ANG MQ-9 ^[inferred] over Gulf of Aden at MGRS 38P LT**; 1X round IR-cold contact at ~240 ft over sea surface; 8-min bounded encounter with abrupt directional changes; passive ISR; carries Block C — second Block C range-fouler; **FIRST intra-range-fouler squadron-recurrence pair with d44 — 41 days apart, same squadron, same sub-theater Gulf of Aden, same form-variant Reporting, same crew-position Other, same morphology Round+IR-cold+Black-Hot, same byte-for-byte narrative template phrasing `a few abrupt directional changes during the X minute contact` + `Our sensor was aimed -X degrees below our altitude`**; Reporting Form variant firms as 172 ATKS-correlated at 2-of-2; first UTM 38P body anchor in corpus; first literal `gulf-of-aden` filename token in range-fouler subset; first curator-class-label filename mismatch in corpus (`mission-report` predicate ↔ `# Range Fouler Reporting Form` body))
- [[references/dow-uap-d44-range-fouler-arabian-sea-october-2020]] — Anchor artifact #5 (15 Oct 2020 Gulf of Aden 172 ATKS Michigan ANG MQ-9 ^[inferred]; passive-ISR sub-class; **first 172 ATKS attestation; sister to d57 in the 172 ATKS Gulf of Aden cluster**)
- [[references/dow-uap-d58-range-fouler-debrief-2020-10]] — Anchor artifact #6 (27 Oct 2020 intercept posture; **high-anomaly outlier** isolated at 1-of-6 ~17% with sub-second-disappearance + active-EW + standoff-maintenance triad)
- [[entities/dow-uap-foia-release]] — Series-level anchor; range-fouler debrief is the third top-level mission-record document class confirmed at N=6 (structure-CONFIRMED on 13-of-13 axes; release-framework spans 3 blocks A 3-of-6 + B 1-of-6 + C 2-of-6; Reporting Form firms as 172 ATKS-correlated)
- [[concepts/uap-aircraft-engagement]] — Behavioral framework — d58 anchors sub-class 6 (range-fouler-attempted-ID); d44 + d38 + d56 + d42 + d57 anchor sub-class 7 (range-fouler-passive-ISR-observation) at N=5 across three platform configurations
- [[references/dow-uap-d7-mission-arabian-gulf-2020]] — Closest behavioral analog on the aircraft-toward-UAP axis (d7 = WQT + NTS + TFLIR; d58 = radar lock + TGT-pod video + 16.9 NM standoff; d44 + d38 + d56 + d42 + d57 = passive observation)
- [[references/dow-uap-d55-mission-syria-2016-11-18]] — Release-framework Block A first attestation (now N=3 within Block A range-fouler subset)
- [[entities/aaro]] — Receiving authority for the dow-uap series; SPEAR may feed AARO downstream; AARO routing now anchored at N=6 corpus-wide range-fouler subset across three distinct MDR-case allocations (A/B/C)
- [[entities/ryan-graves]] — Navy F/A-18F pilot; operational analog for the form's AIM-9x + ATFLIR Navy-aviation template (now contrasted at N=6 attested with USAF Active + ANG users at 172 ATKS N=2 + first internal Navy user via d56 HSM-73 rotary-wing variant)
- [[projects/uap/uap]]
