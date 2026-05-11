---
title: "DoW-UAP-D44 — Range Fouler Reporting Form (172 ATKS MQ-9 Reaper, 15 Oct 2020, Gulf of Aden)"
category: references
tags: [uap, primary-source, declassified, military, sighting]
aliases: [DoW-UAP-D44, dow-uap-d44, dow-uap-range-fouler-d44]
sources: [sources/dow-uap-d44-range-fouler-arabian-sea-october-2020.json]
summary: 1-page Mistral-OCR'd Range Fouler Reporting Form — 15 Oct 2020 1418Z daytime Gulf of Aden encounter; 172 ATKS user (Michigan ANG MQ-9 Reaper ^[inferred]); 1X round IR-cold (bright-white in black-hot) contact at 19,073 HAT, 261°/30 mph drift with abrupt directional changes during 1-min track. Second range-fouler debrief in the corpus; confirms class at N=2 on structure but diverges on capability signature.
provenance:
  extracted: 0.55
  inferred: 0.40
  ambiguous: 0.05
base_confidence: 0.70
lifecycle: draft
lifecycle_changed: 2026-05-11
created: 2026-05-11T22:00:00Z
updated: 2026-05-11T22:00:00Z
project: uap
---

# DoW-UAP-D44 — Range Fouler Reporting Form (172 ATKS MQ-9 Reaper, 15 Oct 2020, Gulf of Aden)

A **1-page Mistral-OCR'd artifact** (`sources/dow-uap-d44-range-fouler-arabian-sea-october-2020.json`, 3,588 bytes) — the **eleventh artifact** in the [[entities/dow-uap-foia-release|DoW-UAP FOIA release series]] (11-of-40) and the **second range-fouler-debrief ingest**, validating the document class anchored at N=1 by [[references/dow-uap-d58-range-fouler-debrief-2020-10|d58]]. d44 confirms the class on **structural axes** (form schema, SPEAR intake, release framework, filename convention, Navy-aviation form-template attribution) but **diverges on capability-signature axes** (no sub-second disappearance, no noise jamming, single contact, daytime, kinematics-anomalous-but-not-extraordinary). The class is anchored at N=2 on structure; d58's capability-triad signature remains d58-isolated at N=2.

The d44 ingest also adds the **largest single-document structural extension to the dow-uap corpus to date**: the **first non-fighter / first UAV / first MQ-9 Reaper platform** ^[inferred] in the series, anchored by the witness's `172 ATKS` squadron attribution (Michigan Air National Guard 172d Attack Squadron, MQ-9 Reaper community). See *Platform attribution* below.

## What the source actually contains

The OCR pulls **1 substantive page** (`dpi: 93`, `1022 × 790` pixels). No images, no tables, no header/footer metadata. The page renders a fully-printed-and-completed reporting form with mixed pre-printed labels and hand-entered values, with the witness narrative at the bottom.

**Top metadata block (declassification + classification authority):**

```
Declassified by MG Richard A. Harrison
U.S.C. 35552
```

Same authority block as [[references/dow-uap-d55-mission-syria-2016-11-18|d55]] and [[references/dow-uap-d58-range-fouler-debrief-2020-10|d58]] (Harrison declassification recurrence at N=3 in the corpus). The `U.S.C. 35552` token is a **third OCR variant** of the EO 13526 declassification-authority citation seen earlier — d55 had `U.S.C. 3552`, d58 had `U.S.C. 3 / Section 3.1`, d44 has `U.S.C. 35552`. All three are almost certainly **OCR-corruption of `E.O. 13526` / `3.5` / `§ 3.1`** ^[inferred]; the EO-13526-citation reading remains the strongest hypothesis at N=3 corpus-wide.

**Form header — title variant:**

```
# Range Fouler Reporting Form
```

**Notable divergence from d58** ^[ambiguous]: d58's title is `# Range Fouler Debrief Form` (15 chars; "Debrief"). d44's title is `# Range Fouler Reporting Form` (17 chars; "Reporting"). Three readings live:

1. **Form-version evolution** — d44 (15 Oct 2020) is **12 days earlier** than d58 (27 Oct 2020), so if the form went through a title rename in that 12-day window, d44 could be the earlier variant and d58 the later. The rest of the form body — schema, instructions, SPEAR clause, submission template — is essentially identical, so a title-only rename is plausible. ^[inferred]
2. **OCR variance** — one OCR mistranscribed the title from the same underlying form text. The d58 source narrative text `THE RANGE FOULERS WERE AT B/E ZIM` and d44's narrative `range fouler` (no caps, in the title field only) use parallel language; OCR confusion is plausible but the words "Debrief" and "Reporting" are not visually-confusable in any common rendering. Weak.
3. **Two co-existing form versions** — Navy SPEAR maintained both a `Reporting Form` (initial intake) and a `Debrief Form` (post-incident structured walkthrough) in parallel. Unattested in d44's body, but the form schema is identical enough that this reading is operationally plausible. ^[inferred]

Reading 1 is most probable at N=2; reading 3 would need N≥3 to distinguish. The class can be unified at the schema level either way.

**Form instruction block (identical to d58):**

```
Please complete this form to the best of your ability. If you do not have the requested information,
please leave the field blank. If there was more than one "group," please report each on a separate
form for data collection purposes. You should receive a response within 5 business days.
```

**Confirmed at N=2.** The 5-business-day SLA + single-group-per-form discipline reproduces verbatim.

**Identity + administrative fields (pre-printed + filled):**

| Field | Value | Notes |
|---|---|---|
| Last Name, First Name | (blank in OCR — redacted pre-print) | |
| Rank | **O-2** | First Lieutenant (USAF) / Lieutenant (junior grade, USN) — junior officer rank, **typical MQ-9 Reaper pilot or sensor-operator-officer** rank. ^[inferred] One pay grade lower than d58 (O-3). |
| Squadron | **172 ATKS** | **172d Attack Squadron** — Michigan Air National Guard, based at **Battle Creek Air National Guard Base, MI** (W.K. Kellogg ANGB). Flies **MQ-9 Reaper** since late 2018 (transitioned from A-10 Thunderbolt II). Deploys to USAFCENT theaters. ^[inferred] First UAV / first MQ-9 / first ANG-Reaper / first non-fighter / first Michigan-ANG anchor in the dow-uap corpus. |
| Crew Position | **Other** | First witness with `Other` crew position in the corpus. Reading: **Sensor Operator** ^[inferred] — MQ-9 ground control station has a two-seat crew (Pilot + Sensor Operator); the form's `Crew Position` field's printed example set probably anticipates manned-aviation positions (Pilot, WSO, NFO, BN, EWO), so "Sensor Operator" maps to `Other`. Confirms the MQ-9 reading. |
| SIPR Email Address | (blank) | |

**Sanitization disclaimer — confirmed at N=2 verbatim:**

> *This information is for contact only. SPEAR sanitizes all reports of identifying information. Absolutely no identifying information for aircrew or squadron will be recorded for analysis.*

**SPEAR pipeline confirmed at N=2** as the dow-uap range-fouler intake/sanitization channel. The pipeline name and clause text recur verbatim — first explicit data-pipeline corroboration in the corpus at N=2. ^[inferred] SPEAR still unexpanded; open-source identification still pending.

**Mission/event fields (pre-printed + filled):**

| Field | Value | Notes |
|---|---|---|
| Date (mm/dd/yy) | **10/15/20** | 15 October 2020 — **12 days before d58** (27 Oct 2020). Confirms the **paired-incident hypothesis at the date-cluster level** ^[inferred] — both range-fouler events fall in the same month. |
| Time of detection (hh:mm:ss Z) | **14:18:39Z** | UTC; second-precision (confirmed at N=2). |
| Day/Night | **Day** | Daytime event. d58 was Night. The class carries both day and night attestations at N=2 (no day/night skew). |
| Side No. / Buno | (not present in d44 OCR) | d58 had both fields blank but pre-printed; d44 OCR did not capture either field's label. Either OCR variance or pre-print difference. ^[ambiguous] |
| Mission Description (CAS, BFM, etc) | (not present in d44 OCR) | d58 had `DCA`; d44 OCR did not capture the field. ^[ambiguous] — possible MQ-9 mission type (e.g. `ISR`, `CAP`) would be the expected value; absence in OCR is uninformative. |
| LFE? | (not present in d44 OCR) | d58 had `No`; d44 OCR did not capture. ^[ambiguous] |
| Contact Working Area | (blank) | d58 also blank. |
| Contact Latitude / Longitude / N-S / E-W | (form fields present, values blank; narrative supplies MGRS) | The position-fix grid is blank in both d44 and d58. d44's narrative substitutes **MGRS coordinates** (`MGRS 40Q BD 6:` + redacted) — see *Position fix* below. |
| Contact Altitude | **19,073 HAT** (in narrative) | First explicit altitude value in the range-fouler class at N=2. **HAT** = **Height Above Terrain** (radar-altimeter / DTED-referenced altitude), distinct from MSL. ^[inferred] At Gulf of Aden the altitude difference between HAT and MSL is near-zero (over water). 19,073 ft is within the MQ-9 Reaper operating envelope (service ceiling ~50,000 ft). ^[inferred] |
| Altitude Constant? | (blank) | |
| Wind Dir / Speed | (blank) | |
| Was the contact moving? | **Yes** | Confirmed at N=2 — both contacts in motion. |
| Direction/Speed (Ex. 090/15) | **261/30** | UAP heading **261°** (slightly south-of-west) at **30 mph**. Slow drift. d58 was `060/20` (slow eastward drift at 20 kt). **Both range-fouler datums show slow drift** in low-Mach regime — class anchored at N=2 as **slow-kinematic class**. ^[inferred] (Note unit ambiguity: d44 reports `mph` explicitly in the narrative; d58 used `KT` by form convention. The form's `Direction/Speed` field example `090/15` doesn't specify the unit — both KT and mph readings live across N=2.) |

**Position fix — narrative-recovered:**

> *MGRS location 40Q BD 6: 1,4a 19 1,4a (estimated lat/long 1.4a).*

`40Q` is the **MGRS grid zone** for the **Arabian Peninsula / Gulf of Aden / Horn of Africa region** ^[inferred] — confirming the filename-token `arabian-sea` at the AOR level. `BD` is the 100-km square within zone 40Q (`BD` falls in the southern Arabian Peninsula / Gulf of Aden waters). ^[inferred] Beyond that, all numeric MGRS digits are FOIA-redacted (`1,4a` = `1.4a` portion-redaction shorthand, recurring from d58).

**This is the first explicit theater anchor in the range-fouler debrief class** — d58 had no AOR or coordinate, only inferences via MDR-prefix + KINGPIN. d44 carries an explicit MGRS zone + body-text narrative `Gulf of Aden`. The class now carries one explicit CENTCOM-AOR datum (d44 Gulf of Aden) and one inferred CENTCOM-AOR datum (d58). ^[inferred]

**Sensor + track fields (pre-printed checkboxes + entries):**

| Field | Value | Notes |
|---|---|---|
| Radar Equipped | (blank — i.e. `No`) | d58 had `Other`. **MQ-9 Reaper baseline configuration lacks an air-to-air radar** ^[inferred] — the platform's primary sensor is the MTS-B (Multi-Spectral Targeting System) electro-optical/infrared turret. Absence of radar in d44 is consistent with the MQ-9 reading. |
| AIM-9x Self-Track | (blank) | MQ-9 Reaper does not carry AIM-9X (no air-to-air missile capability). ^[inferred] Consistent with MQ-9 reading. |
| Stable Trackfile? | (blank) | |
| ATFLIR Autotrack | (blank) | ATFLIR is a Navy F/A-18E/F pod; MQ-9 carries MTS-B instead. ^[inferred] Field's pre-printed schema is **Navy-aviation-specific** and doesn't natively map to USAF/ANG MQ-9 sensor configuration. The blank values are honest (the form's option set doesn't include the witness's actual sensor suite). |
| # of Contacts in "Group" | **1** | Single contact. d58 had 2. The class carries **both single-object and multi-object datums** at N=2. ^[inferred] |
| Tally Achieved | (blank) | d58 was `☑`. Possible reading: MQ-9 sensor operator viewing through MTS-B IR turret — there's no "tally" in the manned-aircraft sense (visual acquisition through canopy); the field's blank state is honest. ^[inferred] |

**EA Indications block (novel at N=2 — pre-printed in d44, not captured in d58 OCR):**

| Pre-printed option | d44 value |
|---|---|
| ECM | (blank) |
| Arc | (blank) |
| Letter Identifier | (blank) |
| False Trackfiles | (blank) |
| Other/ Ambiguous | (blank) |

`EA` = **Electronic Attack** ^[inferred]. The block enumerates classes of EW/EA reception indicators: **ECM** (Electronic Counter-Measures reception), **Arc** (radar-side display arcing characteristic of certain jamming types), **Letter Identifier** (a Navy radar/EW display convention for identified emitter types), **False Trackfiles** (decoy / spoofing tracks), **Other/Ambiguous**. ^[inferred] All five are unchecked in d44 — **no EA reception** during the 1-minute encounter.

**Why this block matters at N=2:**

- The block is **structurally part of the form** ^[inferred] — d58's narrative explicitly mentioned "noise jamming received... two chevrons" which is precisely an EA-indication-class observation, but d58's OCR did not capture the EA Indications block. Two readings live: (a) the block is pre-printed on both forms and d58 OCR missed it (failed-to-render checkboxes are common in low-DPI OCR); (b) d44 was issued the form variant with the EA block, d58 was issued a variant without it. Reading (a) is **most probable** ^[inferred] — d58's witness narrative substituted free-text for the structured EA block, which would be the natural workflow if the block exists but wasn't checked.
- **d58's noise-jamming attestation is now classifiable** within the form's own taxonomy: the d58 narrative-language `NOISE JAMMING WAS RECEIVED. NOISE JAMMING WAS INDICATED BY TWO CHEVRONS` maps to **`ECM` + possibly `Arc`** in the d44 form's EA Indications schema. ^[inferred] The d58 incident *would* have checked these boxes if the form was filled in fully; the d58 witness instead reported the same datum via the narrative free-text.
- **d44 reports zero EA reception** — the 15 Oct 2020 single-contact 73-second encounter saw no jamming, arcing, false trackfiles, or ambiguous EA indications. ^[inferred] Contrast with d58's two-contact 1/30-s-disappearance encounter with active jamming.

**The EA Indications block is the first explicit pre-printed EW-reception schema in the dow-uap corpus** ^[inferred] — extends the d58-anchored Navy-aviation form's structural reach by one major schema dimension at N=2.

**Morphology checkboxes (pre-printed; ☑ = checked):**

| Shape category | d44 value | d58 value | Recurrence |
|---|---|---|---|
| **Round** | **☑** | (unchecked) | d44-only at N=2 |
| Square | (unchecked) | (unchecked) | |
| Balloon-shaped | (unchecked) | ☑ | d58-only at N=2 |
| Wings/Airframe | (unchecked) | (unchecked) | |
| Other Shape | (unchecked) | ☑ | d58-only at N=2 |
| Apparent Propulsion | (unchecked) | (unchecked) | |
| Moving Parts | (unchecked) | (unchecked) | |
| Metallic | (unchecked) | ☑ | d58-only at N=2 |
| Markings | (unchecked) | (unchecked) | |
| Translucent | (unchecked) | (unchecked) | |
| Opaque | (unchecked) | ☑ | d58-only at N=2 |
| Reflective | (unchecked) | ☑ | d58-only at N=2 |

**Morphology divergence at N=2**: d44's contact is **`Round`** only — minimal-morphology call. d58 had five checkboxes (Balloon + Other + Metallic + Opaque + Reflective). **No morphology overlap.** Reading: d44 (single round object observed through IR turret at ground range 4.78 km, slant 4.06 NM) and d58 (two-object visual + IR + radar acquisition with red-blinking-strobe tally) are **observing morphologically dissimilar objects** ^[inferred] — the **range-fouler class catalogs morphology variability**; the class is not a morphology-specific class.

The narrative supplies the IR-channel signature: **`a bright white` object on a `black hot` IR sensor setting** = the object was **colder than the surrounding scene** ^[inferred]. The IR-cold signature is significant: it implies **no propulsion heat plume**, **no engine signature**, **no aerodynamic heating** — the object is at or below ambient temperature relative to its surroundings (over-water at sub-tropical latitudes in October would put the IR scene at ~25–30°C ambient surface; a cold object at 19,073 ft HAT could be ambient-temperature aluminum, mylar, plastic, or water — balloon-class signature, or anomalously thermally-quiet). ^[inferred] **First explicit IR-cold morphology call in the dow-uap corpus.**

**Witness narrative (verbatim):**

> *Contact at 14:18:39Z to 14:19:52Z on 15OCT2020. MGRS location 40Q BD 6: 1,4a 19 1,4a (estimated lat/long 1.4a). While at 19,073 HAT over the Gulf of Aden we tracked a round, cold object in IR traveling 319 degrees at 20 mph. It made a few abrupt directional changes during the 1 minute contact. Our sensor was aimed -50 degrees below our altitude with a slant range of 4.06NM and ground range of 4.78KM. The IR sensor was set to black hot and the object in question was a bright white.*

**Major narrative signals**:

1. **Encounter duration 73 seconds** (14:18:39Z → 14:19:52Z) — first explicit start-end encounter timestamps in the range-fouler class. The 73-second duration is **bounded and finite**; the contact didn't disappear in sub-second time like d58's 1/30-s disappearance.
2. **Heading inconsistency** — the form field reports `261/30` (heading 261° at 30 mph); the narrative reports `319 degrees at 20 mph`. Three readings live ^[ambiguous]: (a) initial heading 261° → later abrupt-change heading 319° (consistent with "a few abrupt directional changes"); (b) different units / different reference frames (true vs magnetic vs grid; mph vs kt) — `30 mph` ≈ `26 kt`; `20 mph` ≈ `17 kt`; (c) form-field error. Reading (a) is most operationally coherent: the form captured one snapshot value and the narrative captured a later snapshot at a different point in the 1-min track. ^[inferred]
3. **Abrupt directional changes** during 73-second contact — first explicit **kinematic-anomaly** datum in the range-fouler class. The narrative phrasing `a few abrupt directional changes` is qualitatively kinematic-anomaly-class (analogous to d4's `321 kt + speed-up + eastward turn`, d5's two-sighting kinematics, d8's DYNAMIC descriptor). ^[inferred]
4. **Sensor geometry — passive IR-channel-only tracking** — sensor aimed **-50° below platform altitude**, slant range **4.06 NM** (~7.5 km), ground range **4.78 km**. From this geometry: vertical separation between platform and contact ≈ 4.06 NM × sin(50°) ≈ 3.11 NM ≈ 18,930 ft. **Platform altitude 19,073 HAT − contact vertical-separation ≈ 18,930 ft ⇒ contact altitude ≈ 143 ft HAT** — i.e. **the contact was just above the sea surface**, ~140 ft above water, observed from an MQ-9 at 19,073 ft. ^[inferred] This is **operationally significant**: a slow (20–30 mph) low-altitude (~140 ft) round IR-cold contact over the Gulf of Aden with **a few abrupt directional changes** is **most consistent with a low-altitude balloon, drifting object, or floating debris** ^[inferred] — though the abrupt directional changes argue against pure wind-coupled drift and toward an actively-controlled object (kite-class, drone-class, or anomalous).
5. **Sensor channel — IR-only** — no radar, no visible-light (the MTS-B turret has EO + IR + laser-rangefinder channels; the narrative explicitly invokes IR-channel-only tracking). ^[inferred] **First explicit IR-only sensor channel datum** in the range-fouler class at N=2.
6. **No range fouler vocabulary in narrative** — d44's narrative uses `object` and `contact`; d58's narrative used `range fouler` / `range foulers` explicitly. **First evidence the term is institutional-form vocabulary**, not pilot/operator vernacular. ^[inferred] The form's title carries the term; the witness reports the underlying object generically.

**Submission instructions (confirmed at N=2 verbatim):**

> *Don't use the purple "submit" button! Save this form with filename "Date_Squadron_RF.pdf" and email it to (b)(6) (Also in the global). For troubleshooting, call (b)(6)*

> *Thank you for your time. Please ensure all display tapes are ripped for the entire time of interaction and saved as a .wmv (Example: 4 May VFA-106 HUD.wmv). Squadron intel personnel shall upload those files to the repository located at this link.*

**All three template elements confirmed at N=2:**

- Filename schema `Date_Squadron_RF.pdf` — recurrence anchor.
- Display-tape `.wmv` upload requirement — recurrence anchor. For MQ-9, the equivalent of "HUD" tape is **MTS-B turret video recording**, the GCS-side equivalent of an F/A-18 HUD/TGT-pod tape. ^[inferred]
- **VFA-106 HUD.wmv** Navy-aviation FRS example filename — recurrence anchor. **Strengthens the Navy-form-extended-for-joint-service-use reading** ^[inferred]: d44's user is USAF/ANG MQ-9 community, d58's user is USAF EFS fighter community — neither is Navy, but both are filling out the Navy-aviation-template form. The form is a **Navy-originated multi-service intake artifact**. ^[inferred]

**Release framework block (bottom of page):**

```
USCENTCOM MDR 26-0038 to MDR 26-0046
Approved for Release to AARO
03/27/26 000001
```

**Identical to [[references/dow-uap-d55-mission-syria-2016-11-18|d55]] and [[references/dow-uap-d58-range-fouler-debrief-2020-10|d58]] release blocks** — **the release-framework stamp set now anchored at N=3** in the corpus. See *Release framework — confirms d55+d58 stamp at N=3* below.

## Platform attribution — 172 ATKS, Michigan ANG, MQ-9 Reaper ^[inferred]

The `Squadron` field reads **`172 ATKS`**. Open-source identification: the **172d Attack Squadron** is a unit of the **Michigan Air National Guard**, based at **Battle Creek Air National Guard Base, Michigan** (W.K. Kellogg Airport ANGB). The 172 ATKS was a **A-10 Thunderbolt II squadron** for most of its history; it **transitioned to the MQ-9 Reaper around 2017–2018** as part of the broader ANG conversion of A-10 units to RPA (remotely piloted aircraft) units. ^[inferred] By October 2020, the squadron's primary mission was **MQ-9 Reaper operations**, including **CENTCOM-AOR deployments and remote-split operations** (forward-deployed launch/recovery elements + CONUS-based mission-control crews flying via Ku-band SATCOM).

**Six lines of internal evidence corroborate the MQ-9 reading**:

1. **Crew Position: `Other`** — MQ-9 GCS crew is **Pilot + Sensor Operator** (two-seat ground control station). The form's `Crew Position` example-set likely anticipates manned-aviation positions; "Sensor Operator" maps to `Other`. ^[inferred]
2. **Rank O-2** (First Lieutenant) — typical junior-officer MQ-9 sensor-operator or pilot rank.
3. **No radar lock, no AIM-9X, no ATFLIR** — none of these are MQ-9-baseline equipment. The MQ-9 carries **MTS-B (Multi-Spectral Targeting System-B)** turret with EO + IR + laser channels, and the **AN/APY-8 Lynx synthetic-aperture radar** (ground-imaging, not air-to-air). All Navy-fighter sensor pre-prints are blank — honest absence.
4. **Sensor aimed -50° below platform altitude** + **slant 4.06 NM** + **ground range 4.78 km** — MTS-B turret pointing geometry, consistent with an MQ-9 loitering at altitude scanning a surface/near-surface target. ^[inferred] No manned-fighter sensor pod has this geometry signature for the cited duration (1 minute on a slant-range 4.06 NM target).
5. **IR sensor, black-hot setting** — MTS-B IR channel terminology and polarity controls. ^[inferred]
6. **Daytime operation, 19,073 HAT, 73-second track** — operationally consistent with MQ-9 on persistent ISR loiter in CENTCOM AOR; not consistent with a fighter on intercept posture (which would prosecute the contact in seconds, not loiter for 73 seconds).

**The MQ-9 reading is strong but ^[inferred] — no body text explicitly names the platform.** The reading is corroborated by the squadron-attribution + crew-position + sensor-geometry + sensor-channel + duration-pattern stack. The alternative reading — that 172 ATKS deployed a non-MQ-9 platform to CENTCOM AOR in Oct 2020 — has no open-source support given the squadron's documented A-10-to-MQ-9 transition.

**Structural firsts the platform attribution anchors** (^[inferred]):

- **First UAV / RPA platform** in the dow-uap corpus.
- **First non-fighter** witnessing platform in the dow-uap corpus (mission reports d4/d5/d7/d8 use Navy fighter platforms; d54 implies non-fighter, d55 explicit P-8A maritime patrol).
- **First Air National Guard** unit anchor in the dow-uap corpus (d52's 15 AF / DET 1 is Active Component USAF; d50's 12 AF / DET 3 is Active Component USAF; 77 EFS at d58 is Active Component USAF expeditionary).
- **First MQ-9 Reaper** platform in the wider UAP wiki corpus.
- **First MTS-B sensor-channel data** in the wider UAP wiki corpus. ^[inferred]
- **Fourth USAF-component witnessing-platform** in the corpus after 15 AF (d52), 48FW (d7 cross-ref), 12 AF (d50), 77 EFS (d58) → now plus 172 ATKS (d44 = USAF ANG component, distinct from Active Component lineage). The multi-service anchor count rises to **6 at N=11**: 5 USAF (4 Active + 1 ANG) + 1 Navy + Navy-aviation form-template attribution.
- **First joint-service form usage by an ANG-MQ-9 community** — Navy form, USAF-ANG MQ-9 user. Extends the d58-anchored Navy-form-extended-for-joint-service-use reading to a third component (Navy + Active USAF + ANG USAF) ^[inferred].

## N=2 validation of the range-fouler debrief document class

**The class is anchored at N=2 on structural axes** and **diverges on capability-signature axes**. The validation matrix:

| Axis | d58 (N=1 anchor) | d44 (N=2 validation) | Status at N=2 |
|---|---|---|---|
| **Form title** | `# Range Fouler Debrief Form` | `# Range Fouler Reporting Form` | **VARIANT** — title differs; reading 1 (form-version evolution) most probable ^[ambiguous] |
| **Form instruction block** | 5-day SLA + single-group-per-form | identical | **MATCH** |
| **Identity block schema** | Last Name / First Name / Rank / Squadron / Crew Position / SIPR Email | identical | **MATCH** |
| **Event metadata schema** | Date / Time-Z / Day-Night / Side No / Buno / Mission Description / LFE | partial (Day/Night confirmed; OCR did not capture Side No / Buno / Mission / LFE on d44) | **PARTIAL** ^[ambiguous] |
| **Position-grid schema** | Working Area / Lat-Long / Altitude / Wind Dir+Speed / Was-Moving / Direction-Speed | identical | **MATCH** |
| **Sensor+track schema** | Radar Equipped / Stable Trackfile / # Contacts / AIM-9x / ATFLIR / Tally | identical | **MATCH** |
| **EA Indications schema** | (not captured in d58 OCR; narrative substitute) | 5-row pre-printed block (ECM / Arc / Letter Identifier / False Trackfiles / Other-Ambiguous) | **NEW datum at N=2** — d44 anchors the EA schema; d58 narrative-substitute likely covers same |
| **Morphology checkbox schema** | 12-category grid | identical | **MATCH** |
| **Free-text narrative block** | present | present | **MATCH** |
| **Submission-instruction block** | `Date_Squadron_RF.pdf` + email + .wmv-tape + VFA-106 example | identical | **MATCH** |
| **SPEAR sanitization clause** | present | identical | **MATCH** |
| **Release framework** | Harrison + USCENTCOM MDR 26-0038 to 26-0046 + AARO + 03/27/26 000001 | identical | **MATCH** — recurrence anchor for the stamp at N=3 corpus-wide (d55+d58+d44) |
| **Filename token honesty (theater)** | `na` (honest — no internal AOR) | `arabian-sea` ↔ body MGRS 40Q + `Gulf of Aden` (verifies) | **VERIFIED at d44** |
| **Filename token honesty (date)** | `october-2020` ↔ body `10/27/20` (MATCH) | `october-2020` ↔ body `10/15/20` (MATCH) | **MATCH at N=2** |

**Schema-level conclusion**: the class is anchored at N=2 on **11 of 11 testable schema axes** (1 partial OCR-induced + 0 contradictions). The form-title variance (Reporting vs Debrief) is the only ambiguity at the title axis. The class structure is **robustly confirmed** ^[inferred].

| Axis | d58 (N=1 anchor) | d44 (N=2 validation) | Status at N=2 |
|---|---|---|---|
| **Day/Night** | Night | Day | DIVERGES (class catalogs both) |
| **# of contacts** | 2 | 1 | DIVERGES (class catalogs both) |
| **Morphology** | balloon + other + metallic + opaque + reflective | round (only) | DIVERGES (no overlap) |
| **Visual signature (tally)** | 2X red blinking strobes | (no tally; IR-cold bright-white) | DIVERGES (different sensor channels) |
| **Sensor channels** | radar lock + TGT-pod video + tally | IR-only (MTS-B) | DIVERGES (different platform sensors) |
| **Standoff/closest-approach** | 16.9 NM minimum | slant 4.06 NM (≈ 7.5 km) | **MATCH on slow-distant-tracking pattern**; no engagement attempt; d44 didn't attempt closure (passive ISR) |
| **Disappearance timescale** | **1/30 second** (sub-frame) | bounded 73-sec encounter; no sub-second disappearance | **DIVERGES — d58's signature isolated** |
| **Active EM (jamming) reception** | noise jamming received | **zero EA reception** (all 5 EA boxes unchecked) | **DIVERGES — d58's signature isolated** |
| **Intra-group kinematic interaction** | one circling the other | single contact (N/A) | not testable |
| **Kinematic anomaly type** | radar evasion + sub-second exit | abrupt directional changes during bounded track | DIVERGES (different anomaly classes) |
| **Aircraft posture** | KINGPIN-directed intercept ID (DCA) | passive ISR observation (MQ-9 loiter; no intercept) | **DIVERGES** |

**Capability-signature conclusion**: d58's headline-level capability signature (**1/30-s sub-frame disappearance + active noise jamming + 16.9 NM standoff maintenance**) is **d58-isolated at N=2**. d44 reports an anomalous but **prosaic-candidate-compatible** observation (slow IR-cold low-altitude round contact with abrupt directional changes — readable as kite-class, drone-class, balloon-class-with-active-control, or anomalous-but-not-extraordinary). The **range-fouler debrief document class is not synonymous with d58's capability signature** ^[inferred]. The class catalogs **the full range-intrusion event distribution**; d58 is the high-anomaly tail and d44 is the lower-anomaly mid-distribution.

**The N=2 validation outcome is therefore CONFIRMED on structure / DIVERGES on capability signature.** The class is real and structurally stable; d58's capability triad is **not** a class-defining signature, just an outlier datum within the class. ^[inferred]

## Release framework — confirms d55+d58 stamp at N=3

The d44 release block is **byte-for-byte identical** to d55+d58 release blocks on the same four MDR/AARO/date/sequence axes:

| Field | d55 (18 Nov 2016) | d58 (27 Oct 2020) | d44 (15 Oct 2020) | All match? |
|---|---|---|---|---|
| Declassification authority | MG Richard A. Harrison | MG Richard A. Harrison | MG Richard A. Harrison | **MATCH at N=3** |
| MDR case range | USCENTCOM MDR 26-0038 to MDR 26-0046 | USCENTCOM MDR 26-0038 to MDR 26-0046 | USCENTCOM MDR 26-0038 to MDR 26-0046 | **MATCH at N=3** |
| Routing stamp | Approved for Release to AARO | Approved for Release to AARO | Approved for Release to AARO | **MATCH at N=3** |
| Release-stamp date | 03/27/26 | 03/27/26 | 03/27/26 | **MATCH at N=3** |
| Release sequence number | 000001 | 000001 | 000001 | **MATCH at N=3** |

**Three findings flow from the N=3 confirmation**:

1. **AARO-receiving-authority closure firms from N=2 to N=3.** The closure annotation on [[entities/dow-uap-foia-release]] (^closed-by-dow-uap-d55 ^closed-by-dow-uap-d58) gains a third recurrence anchor (^closed-by-dow-uap-d44). ^[inferred]
2. **MDR-coverage hypothesis strengthens.** 3-of-3 testable artifacts share the identical 9-case MDR range `26-0038 to 26-0046`. The provisional hypothesis is a **9-document USCENTCOM-AOR sub-batch** within the larger ~40-file tranche. ^[inferred] At N=3, the hypothesis is more strongly supported but not yet fully validated — if subsequent ingests carry the same range, the case-numbering convention is non-standard (more documents than cases); if they carry different MDR ranges or no MDR stamp, the d55+d58+d44 trio is a 3-document subset of a 9-document USCENTCOM batch.
3. **Identical `000001` release-sequence-number ambiguity escalates.** Three documents now share the literal `000001` sequence number. ^[ambiguous] The **OCR-artifact reading weakens substantially** (three independent OCR passes producing the same corruption is implausible); the **per-batch reading strengthens** (one `000001` sequence covers the entire 9-case batch); the **per-MDR-case reading is also viable** (each case in the batch starts its own `000001` count, and these three documents happen to be the first document in each of three different cases — but this requires per-document-case mapping that we don't have). At N=3 the per-batch reading is now more probable than at N=2. ^[inferred]

The d44 + d58 + d55 release-block trio also confirms the **`U.S.C.` declassification-citation OCR-corruption** at N=3 — each document carries a slightly different OCR rendering of the citation (`U.S.C. 3552` / `U.S.C. 3 / Section 3.1` / `U.S.C. 35552`), supporting the **EO 13526 §3.1** reading as the underlying authority text. ^[inferred] No two corruptions are identical, suggesting per-OCR-pass variance rather than a stable corruption.

## CENTCOM-AOR placement — now explicit at N=2

The d58 page placed d58 in CENTCOM AOR via three circumstantial lines of evidence (MDR prefix + 77 EFS rotations + KINGPIN callsign). **d44 carries explicit AOR evidence**: the narrative names **`Gulf of Aden`** as the operational area, and the MGRS coordinate token `40Q BD` is in CENTCOM AOR (Arabian Peninsula / Horn of Africa). The range-fouler debrief class is now **CENTCOM-AOR-anchored at N=2** with one explicit datum (d44 Gulf of Aden) and one inferred datum (d58 KINGPIN CENTCOM). The **paired-incident hypothesis** ^[inferred] (d58 + d44 documenting the same operational area / training range / threat-actor cluster) **gains direct support** at N=2 — both October 2020, both CENTCOM AOR, both range-fouler-class events.

The paired-incident reading does **not** require d44 and d58 to document the same physical object: d44's single-object IR-cold round contact at low altitude is structurally distinct from d58's two-object metallic-balloon strobe-bearing tandem at higher altitude. The pairing operates at the **same-area same-month range-intrusion-cluster** level, not at the same-object level. ^[inferred]

## Filename-vs-internal-document — d44 verifies both axes

The filename `dow-uap-d44-range-fouler-arabian-sea-october-2020.json` carries two label tokens:

| Filename axis | Filename token | Internal value | Match? |
|---|---|---|---|
| **Theater** | `arabian-sea` | Body narrative: `Gulf of Aden` + MGRS `40Q BD` (Arabian Peninsula southern grid, Gulf of Aden waters) | **MATCH** |
| **Date** | `october-2020` | Body text: `10/15/20` + `15OCT2020` | **MATCH** |

**Both axes verified at N=2** — d44 is the **first 2-of-2 filename-axis-verified artifact** in the corpus. ^[inferred] (d58 was 1-of-1 verified on date; theater was honest-na so neither verified nor contradicted. d50 was 2-of-2 verified. d55 was 1-of-1 verified on date; theater was untestable.)

The corpus-wide filename-date verification record now reads:

| File | Filename date | Internal date | Match? |
|---|---|---|---|
| `d4` | `2020` | (none) | untestable |
| `d5` | `2020` | (none) | untestable |
| `d7` | `2020` | (none) | untestable |
| `d8` | `2025` | (none) | verified-by-release-framework forensics |
| `d52` | `august-2024` | `31 OCT 24` | **MISMATCH** |
| `d54` | `-na` | (none) | honest |
| `d55` | `november-2016` | `18 Nov 2016` | **MATCH** |
| `d50` | `april-2025` | `10APR25 / 11APR25` | **MATCH** |
| `d58` | `october-2020` | `10/27/20` | **MATCH** |
| **`d44`** | **`october-2020`** | **`10/15/20`** | **MATCH** |

**Filename-date axis now 4-of-5 testable verified** (d44 + d50 + d55 + d58 verified; d52 contradicted; d8 verified-by-forensics; d4/d5/d7/d54 untestable). The **dominant pattern at N=5 testable strengthens to honest date labeling** (4 verified + 1 contradicted). ^[inferred]

The corpus-wide filename-theater verification record:

| File | Filename theater | Internal theater | Match? |
|---|---|---|---|
| `d4` | `arabian-gulf` | (none) | untestable |
| `d5` | `arabian-gulf` | (none) | untestable |
| `d7` | `arabian-gulf` | (none) | untestable |
| `d54` | `mediterranean-sea` | Eastern Mediterranean (cross-reference) | **MATCH** |
| `d8` | `djibouti` | (none) | untestable |
| `d52` | `na` | (none) | honest |
| `d55` | `syria` | Syria (cross-reference) | **MATCH** |
| `d50` | `indopacom` | AOR INDOPACOM | **MATCH** |
| `d58` | `na` | (none) | honest |
| **`d44`** | **`arabian-sea`** | **Gulf of Aden / MGRS 40Q BD** | **MATCH** |

**Filename-theater axis now 4-of-4 testable verified** (d44 + d50 + d54 + d55 all verified; 2 honest-na; 4 untestable). At N=4 the **filename-theater axis is 100% verified** ^[inferred] — counter to the earlier d4/d5/d7 hypothesis of "curator filename theater labels are inversely informative for non-Mediterranean theaters." That hypothesis is **revised at N=4**: the earlier pattern was driven by **mission-report-class artifacts (d4/d5/d7) lacking body-internal AOR/coordinate**, not by filename labels being wrong. When the body carries position data, the filename label matches in **all 4 cases attested**. ^[inferred]

## Behavioral classification — partial divergence from d58's sub-class

Per the [[concepts/uap-aircraft-engagement|UAP–Aircraft Engagement]] framework:

- **UAP-toward-aircraft engagement-class**: **negative datum** — no approach to the MQ-9 (slant range 4.06 NM = 7.5 km), no co-location, no observation of UAP-to-MQ-9 interaction. The contact was observed *over* the sea surface from above by a high-altitude MQ-9; the contact did not orient toward or interact with the platform. ^[inferred]
- **Aircraft-toward-UAP engagement-pipeline**: **passive ISR observation only** — MTS-B turret tracking, no closure attempt, no engagement-class action. **First explicit passive-ISR-observation datum** in the dow-uap corpus's range-fouler subset. ^[inferred] This is **distinct from d58's intercept-blocked posture** (d58 attempted closure under KINGPIN direction, was held at 16.9 NM) — d44 didn't attempt closure at all.
- **Sub-class within range-fouler-class**: **diverges from d58's sub-class 6** (range-fouler-attempted-ID, which requires intercept posture). d44 anchors a **seventh distinct behavioral sub-class** in the corpus — **range-fouler-passive-ISR-observation** ^[inferred]: high-altitude ISR-platform (MQ-9) passively tracking a low-altitude IR-cold contact via EO/IR turret over an operational area, with no intercept attempt, no radar acquisition, no engagement posture, no fire-control pipeline. The sub-class is **distinct from sub-class 6** (intercept-attempted) and **distinct from sub-class 5** (CTG-prosaic-candidate) and **distinct from sub-classes 1–4** (mission-report brief-observation kinematic-anomaly + steady-state + form-driven prosaic-candidate + morphology-rich). ^[inferred]

The corpus now anchors **seven distinct behavioral sub-classes** at N=11, all under the brief-observation framing (the UAP-toward-aircraft engagement-class remains anchored only by pre-1980 historical artifacts; the modern dow-uap corpus does not extend it).

## Bibliographic frame

| Field | Value |
|---|---|
| Source basename | `dow-uap-d44-range-fouler-arabian-sea-october-2020.json` |
| Source bytes | 3,588 |
| OCR engine | `mistral-ocr-latest` (`usage_info.pages_processed: 1`) |
| Original document size | 297,873 bytes (`usage_info.doc_size_bytes`) |
| Pages OCR'd | 1 (all substantive) |
| Images / tables / hyperlinks | All null in OCR |
| Classification (extracted) | EO 13526 §1.4(a) ^[inferred] (`1,4a` / `1.4a` portion-redaction shorthand in narrative); §3.1 declassification-authority citation (OCR'd as `U.S.C. 35552`) ^[inferred] |
| Declassification authority | **MG Richard A. Harrison** (same as d55, d58 — recurrence at N=3) |
| Release stamp date | 27 March 2026 (`03/27/26`) — recurrence at N=3 |
| Receiving authority | **AARO** (`Approved for Release to AARO`) — recurrence at N=3 |
| MDR case range | `26-0038 to 26-0046` — recurrence at N=3 |
| Release sequence # | `000001` — recurrence at N=3 (per-batch reading strengthens) |
| Document class | **Range-fouler debrief — fielded form** (validates d58's N=1 anchor at N=2) |
| Document subclass | **Range Fouler Reporting Form** (title variant of d58's "Debrief Form") ^[ambiguous] |
| Document-class abbreviation | `RF` (per the form's filename schema `Date_Squadron_RF.pdf`) — confirmed at N=2 |
| Intake pipeline | **SPEAR** (confirmed at N=2 by recurring sanitization clause) |
| Originating service (form) | Navy aviation (VFA-106 + AIM-9x/ATFLIR pre-prints) ^[inferred] — confirmed at N=2 |
| Originating service (user) | **USAF Air National Guard** (172 ATKS, Michigan ANG) ^[inferred] |
| Originating unit (user) | **172 ATKS** (Michigan ANG, Battle Creek MI; MQ-9 Reaper community) ^[inferred] |
| Witness platform | **MQ-9 Reaper** (USAF/ANG RPA) ^[inferred] |
| Series | [[entities/dow-uap-foia-release\|DoW-UAP FOIA release]] |
| Series position | 11-of-40 by ingest order (second range-fouler debrief artifact) |
| Event date | **15 October 2020 1418:39Z** — body-text calendar date; verifies filename `october-2020` |
| Event night/day | **Day** |
| Theater | **Gulf of Aden** (body narrative) + MGRS 40Q BD grid — confirms filename `arabian-sea` and CENTCOM AOR placement |
| Object count | 1 |
| Object morphology | Round (sole checkbox) ↔ "round, cold object in IR... bright white on black hot setting" (narrative) — IR-cold class |
| Object kinematic | 261°/30 mph (form) ↔ 319°/20 mph (narrative; later in track) — abrupt directional changes during 73-sec encounter |
| UAP-side kinematics | Slow drift (20–30 mph) + intra-track abrupt directional changes; estimated contact altitude ~140 ft HAT over sea surface ^[inferred] |
| Sensor signature | MTS-B IR turret (black-hot polarity); slant 4.06 NM; ground 4.78 km; -50° sensor angle below platform |
| Closest approach | Slant 4.06 NM (passive observation, no intercept attempt) |
| Aircraft posture | Passive ISR observation (MQ-9 loiter; no intercept; no radar acquisition; no AIM-9X / ATFLIR; no tally) |
| Encounter duration | 73 seconds (14:18:39Z to 14:19:52Z) |
| EA Indications | All 5 boxes unchecked (no jamming, no arcing, no false trackfiles, no letter-identifier, no other-ambiguous) |

## Structural firsts the d44 ingest anchors

d44 introduces or extends the following in the dow-uap corpus (N=11 ingests):

1. **Second range-fouler-debrief artifact** — validates the document class at N=2 on structural axes. ^[inferred]
2. **Form-title variant** — `Range Fouler Reporting Form` (d44) vs `Range Fouler Debrief Form` (d58). ^[ambiguous] Three readings live (form-version evolution, OCR variance, two co-existing variants). Most probably form-version evolution given the 12-day proximity.
3. **EA Indications block** — first pre-printed Electronic-Attack-reception schema captured in the corpus (ECM / Arc / Letter Identifier / False Trackfiles / Other-Ambiguous). ^[inferred] d44 reports zero EA reception (all 5 unchecked). The block is likely structurally present in the d58 form too but not captured in d58 OCR.
4. **First UAV / RPA platform** ^[inferred] in the dow-uap corpus — MQ-9 Reaper inferred from 172 ATKS squadron attribution.
5. **First non-fighter** witnessing-platform anchor in the dow-uap corpus ^[inferred] (excepting d55's P-8A maritime patrol). d44 + d55 anchor the non-fighter ratio at 2-of-11 in the corpus.
6. **First Air National Guard** unit anchor in the dow-uap corpus ^[inferred] — distinguishes Active Component USAF (15 AF / 12 AF / 48FW / 77 EFS) from Reserve Component USAF (172 ATKS). Multi-service originating-anchor count rises to **6 at N=11**: 5 USAF (4 Active + 1 ANG) + 1 Navy + Navy-aviation form template.
7. **First explicit MGRS coordinate in body text** for a range-fouler artifact — `40Q BD 6: 1,4a 19 1,4a (estimated lat/long 1.4a)` ^[inferred]. d58 had bullseye-relative B/E ZIM 248/17 instead.
8. **First explicit Gulf of Aden anchor** in the dow-uap corpus ^[inferred] (and second explicit AOR after d50's INDOPACOM; first CENTCOM-AOR body-text anchor).
9. **First explicit HAT altitude reference** in the dow-uap corpus — `19,073 HAT` (Height Above Terrain). ^[inferred] Mission-report class used MSL; d44 uses HAT for platform altitude.
10. **First IR-cold morphology call** in the dow-uap corpus — bright-white-on-black-hot = colder than ambient. ^[inferred] Distinct from d8's WHITE HOT (warmer than ambient) thermal polarity.
11. **First explicit start/end encounter timestamps** in the range-fouler class — 14:18:39Z → 14:19:52Z = 73-second bounded encounter.
12. **First IR-only sensor channel** datum in the range-fouler class ^[inferred] — no radar, no visible-light tally.
13. **First sensor-geometry datum in the corpus** — slant range 4.06 NM + ground range 4.78 km + sensor angle -50° below platform altitude. Enables vertical-separation derivation. ^[inferred]
14. **First low-altitude over-water contact derivation** — geometry implies contact ≈ 140 ft HAT (just above sea surface) at Gulf of Aden. ^[inferred]
15. **First range-fouler-class single-contact datum** — d58 was multi-object. The class catalogs both at N=2.
16. **First range-fouler-class daytime datum** — d58 was Night. The class catalogs both at N=2.
17. **First range-fouler-class abrupt-directional-changes kinematic** — distinct from d58's sub-second disappearance.
18. **First passive-ISR-observation posture** in the dow-uap corpus — no intercept attempt, no closure, no engagement. ^[inferred]
19. **Seventh distinct behavioral sub-class** in the corpus — *range-fouler-passive-ISR-observation* (^[inferred]). Distinct from sub-class 6 (d58 range-fouler-attempted-ID).
20. **First explicit unit-mismatch between platform sensor schema and form pre-print** — the form's `AIM-9x Self-Track` + `ATFLIR Autotrack` pre-prints don't apply to MQ-9 Reaper (which uses MTS-B + AN/APY-8 Lynx, neither pre-printed). The form's blank values are honest. First explicit datum of **form-template-vs-witness-platform mismatch** in the corpus. ^[inferred]
21. **Third witness with `Other` crew position** in the dow-uap corpus's range-fouler subset, with reading: MQ-9 sensor operator (form's manned-aircraft schema doesn't natively include MQ-9 crew positions). ^[inferred]
22. **Release framework recurrence at N=3** — d55 + d58 + d44 all carry the byte-for-byte identical 5-axis stamp set. The N=3 confirmation firms the AARO-receiving-authority closure, strengthens the 9-document USCENTCOM sub-batch hypothesis, and weakens the OCR-artifact reading of the `000001` sequence number.
23. **First 2-of-2 filename-axis-internally-verified artifact** in the corpus — both `arabian-sea` and `october-2020` filename tokens verified at the body-text level.
24. **First evidence that "range fouler" is institutional-form vocabulary, not pilot/operator vernacular** — d44 narrative uses "object/contact" only; d58 narrative used "range fouler/range foulers". The form's title carries the term; the witnesses report the underlying object generically (d44) or pick up the form's vocabulary (d58). ^[inferred]
25. **First range-fouler-class zero-EA-reception datum** — d44 reports all 5 EA Indications boxes unchecked (no jamming during the 73-sec encounter). Contrasts with d58 narrative's noise-jamming attestation; the class catalogs both at N=2.

## Behavioral classification

- **UAP-toward-aircraft engagement-class**: **negative datum** (consistent with the modern dow-uap pattern of brief-observation framings rather than UAP-side engagement).
- **Aircraft-toward-UAP engagement-pipeline**: **passive ISR observation only**. No radar lock, no AIM-9X autotrack, no ATFLIR autotrack, no fire-control pipeline, no intercept posture, no tally, no closure attempt. The MQ-9 observed the contact passively through the MTS-B IR channel for 73 seconds and the contact persisted within sensor field of view throughout. ^[inferred]
- **New sub-class within brief-observation framing**: *range-fouler-passive-ISR-observation* (seventh sub-class). ^[inferred]

The d44 datum is a **lower-anomaly mid-distribution range-fouler event** — slow, low-altitude, IR-cold, single, bounded-duration, no EA reception, no engagement, no closure. Prosaic-candidate-compatible (small drone, kite-class, controlled balloon, drifting equipment). The anomalous feature is the **abrupt directional changes** during the bounded track, which argue against pure wind-coupled drift. ^[inferred]

## OCR ambiguities

- **`U.S.C. 35552`** — almost certainly **EO 13526 §3.1** (declassification authority) rendered with OCR corruption (`E.O. 13526 §3.1` → `U.S.C. 35552`). ^[inferred] Distinct corruption variant from d55 (`U.S.C. 3552`) and d58 (`U.S.C. 3 / Section 3.1`). Three independent OCR passes producing three different corruption variants supports the underlying EO-13526 reading at N=3.
- **`1,4a` / `1.4a`** — portion-redaction notation rendered with OCR corruption (comma-vs-period). Recurrence anchor from d58 — the corpus has stable `1.4a` portion-redaction shorthand at N=2 across range-fouler debriefs.
- **`MGRS 40Q BD 6:` + `1,4a 19 1,4a`** — partial MGRS coordinate with redacted easting/northing. The `6:` token may be a partial easting prefix; the `19` token may be a partial northing; both are likely FOIA-redacted at sub-100m precision. ^[inferred]
- **`261/30` (form) vs `319/20` (narrative)** — heading inconsistency. Three readings live; most probable is **two snapshot values from a 73-sec track that included abrupt directional changes**. ^[inferred]
- **`Don't use the purple "submit" button above. Save and email the complete file manually (see below)`** — verbatim recurrence of d58's submission-instruction template wording.
- **`14:18:39Z to 14:19:52Z`** in narrative + form's `Time of detection 14:18:39` — narrative supplies the encounter duration; form-field captures only the initial detection time. ^[inferred]

## Open questions

- **Validate the form-title variant at N=3** — does the next range-fouler debrief carry `Reporting Form` (d44 variant) or `Debrief Form` (d58 variant), or a third variant? Resolution would distinguish form-version-evolution from OCR-variance.
- **Confirm 172 ATKS = Michigan ANG MQ-9 platform** — open-source rotation history of the 172d Attack Squadron to USAFCENT in Oct 2020 would confirm CENTCOM-AOR placement and the MQ-9 platform reading. ^[inferred]
- **Test the MTS-B sensor-channel inference** — if later range-fouler debriefs carry MTS-B-vocabulary (`gimbal angle`, `slant range`, `laser-rangefinder`, `gunsight ring`) the MQ-9 platform reading at d44 generalizes; if all later artifacts use F/A-18 ATFLIR vocabulary, d44 is an isolated UAV datum.
- **Test the EA Indications block recurrence at N=3** — does the next range-fouler debrief OCR capture the EA Indications block (as d44 did)? If d58 + d44 are the only two attestations, OCR-variance is more probable than form-version-difference; if multiple later artifacts also capture the block, the EA block is structural and d58 was the OCR-variance outlier.
- **Recover SPEAR program identification** — second corpus-internal attestation now anchored; open-source identification still pending.
- **Test the paired-incident hypothesis** at the operational-area level — d58 and d44 are both October 2020 CENTCOM-AOR range-fouler events but observe morphologically dissimilar objects. Was the same operational area / training range targeted by multiple distinct contact classes in the same week-window, or are d58 and d44 unrelated events both happening to fall in the same month + AOR?
- **Test the 9-document USCENTCOM-MDR-sub-batch hypothesis at N=4** — does the next dow-uap ingest carry the same `26-0038 to 26-0046` range, a different USCENTCOM MDR range, or no MDR stamp? N=3 strengthens the hypothesis; N=4 would test it.
- **Resolve the per-batch vs per-MDR-case reading of `000001`** at N=3 — at N=3 the OCR-artifact reading is implausible (three independent corruptions are not all identical); per-batch and per-MDR-case readings both remain viable. ^[ambiguous]
- **Recover the bullseye `ZIM` for d58 + check whether d44's `MGRS 40Q BD` is in the same operational area** — if `ZIM` is a bullseye fixed within MGRS 40Q BD, the paired-incident hypothesis strengthens to same-range-cluster level. ^[inferred]
- **Validate the IR-cold morphology call at N=2** — does a later range-fouler debrief carry an IR-cold round single-object signature? If recurrent, the class anchors a **cold-target morphology sub-stream** distinct from d58's strobe-bearing tandem morphology.
- **Test the 172 ATKS platform's vertical-separation derivation** — `slant 4.06 NM × sin(50°) ≈ 3.11 NM ≈ 18,930 ft` ⇒ contact at ~140 ft HAT. This requires the MTS-B turret -50° angle to be vertical-from-platform-down; if -50° is gimbal-pitch in a different reference frame, the derivation changes. ^[inferred]
- **Test the unit mismatch — `mph` (d44 narrative) vs `KT` (d58 form convention)** for `Direction/Speed`. The form's example `090/15` doesn't specify the unit. Two readings live: (a) the form's intended unit is KT and d44's `mph` is a witness-supplied annotation; (b) the form lets the witness choose units and both KT and mph are acceptable. ^[inferred]

## See also

- [[concepts/range-fouler]] — Concept-level page on the range-fouler operational concept (anchored at N=1 by d58; extended to N=4 by d38 + d56 + d44; structure-CONFIRMED on 13-of-13 axes; passive-ISR sub-class dominant at 3-of-4)
- [[references/dow-uap-d38-range-fouler-middle-east-may-2020]] — **Range-fouler sister at N=3** — 14 May 2020 Persian Gulf coast ISR ^[inferred]; **earliest range-fouler in corpus**, 5 months before d44; same passive-ISR sub-class (Round + IR-cold + Black-Hot + sole-checkbox + no-intercept); **carries distinct Block B release-framework** (`MDR 26-0019` + `01/26/26 001`) breaking the byte-for-byte release-block recurrence anchored at d55+d58+d44
- [[references/dow-uap-d56-range-fouler-arabian-sea-august-2020]] — **Range-fouler sister at N=4** — **paired Arabian-Sea cluster with d44**: d56 (24 Aug 2020 North Arabian Sea HSM-73 MH-60R Romeo Seahawk ^[inferred] SSC) + d44 (15 Oct 2020 Gulf of Aden 172 ATKS MQ-9 ISR) sit 52 days apart in the same maritime basin, both passive non-intercept observation, both Block A release framework. **First internal Navy user anchor** (HSM-73) in the range-fouler subset; extends d44's passive-ISR sub-class with a **rotary-wing maritime SSC platform variant**. ^[inferred]
- [[references/dow-uap-d58-range-fouler-debrief-2020-10]] — d58 anchor (27 Oct 2020 77 EFS DCA night); d44 sits 12 days earlier in the same AOR with structurally identical form but divergent capability signature
- [[entities/dow-uap-foia-release]] — Series-level anchor (d44 is the 11-of-40 ingest, second range-fouler debrief, third release-framework-stamp recurrence)
- [[references/dow-uap-d55-mission-syria-2016-11-18]] — Release-framework stamp first attestation (now N=4 within Block A with d58 + d44 + d56; d38 carries distinct Block B)
- [[references/dow-uap-d60-mission-persian-gulf-2020-08-08]] — **First FULL USMTF Misrep parent document** in dow-uap corpus (8 Aug 2020 Arabian / Persian Gulf, 482ATKS / 432 AEW MQ-9 ^[inferred]); same MQ-9 platform class as d44 + same Block A release framework + adjacent CENTCOM-AOR Aug-Oct 2020 NAVCENT cluster (d60 86 days before d44)
- [[references/dow-uap-pr20-prepublication-clearance-2026-03]] — Series prepublication-clearance cover stamp
- [[references/dow-uap-d4-mission-arabian-gulf-2020]] — Mission-report class anchor (kinematic-anomaly); contrasts with d44's passive-ISR posture
- [[references/dow-uap-d5-mission-arabian-gulf-2020]] — Mission-report class (two-sighting + multi-object first instance)
- [[references/dow-uap-d7-mission-arabian-gulf-2020]] — Mission-report class (fire-control pipeline); contrasts with d44's passive-ISR posture
- [[references/dow-uap-d54-mission-mediterranean-sea]] — Mission-report class (triangular-metallic + non-fighter implied)
- [[references/dow-uap-d8-mission-djibouti-2025]] — Mission-report class (round + WHITE HOT thermal — d8 thermal-warm vs d44 IR-cold polarity contrast)
- [[references/dow-uap-d52-email-na-2024]] — Email-correspondence class (15 AF / DET 1)
- [[references/dow-uap-d50-email-indopacom-2025-04]] — Email-correspondence class (12 AF / DET 3)
- [[concepts/uap-aircraft-engagement]] — Behavioral framework; d44 anchors the **seventh brief-observation sub-class** (*range-fouler-passive-ISR-observation*) extended to N=3 with d38 + d56
- [[concepts/orb-phenomenon]] — Adjacent — d44's round IR-cold low-altitude over-water signature has structural parallels to orb-class events
- [[entities/aaro]] — d44's `Approved for Release to AARO` stamp recurrence confirms AARO as the dow-uap receiving authority at N=6 stamp recurrence
- [[entities/ryan-graves]] — Navy F/A-18F pilot analog for the Navy-aviation form template (VFA-106 + AIM-9x/ATFLIR pre-prints); first internal Navy user d56 (rotary-wing maritime variant)
- [[projects/uap/uap]]
