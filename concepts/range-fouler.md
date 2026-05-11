---
title: "Range Fouler"
category: concepts
tags: [uap, navy, military, behavior, pattern]
aliases: [range fouler, range-fouler, RF, range foulers]
sources: [sources/dow-uap-d58-range-fouler-debrief-na-october-2020.json, sources/dow-uap-d44-range-fouler-arabian-sea-october-2020.json, sources/dow-uap-d38-range-fouler-debrief-middle-east-may-2020.json]
summary: Navy / naval-aviation operational concept for unauthorized contacts intruding on a training range or operational area, prompting directed intercept identification or passive ISR observation. Anchored at N=3 by d38 (14 May 2020 Persian Gulf) + d44 (15 Oct 2020 Gulf of Aden) + d58 (27 Oct 2020) — class confirmed on structural axes; capability signature DIVERGES with d58 isolated at 1-of-3; passive-ISR sub-class dominates at 2-of-3.
provenance:
  extracted: 0.50
  inferred: 0.45
  ambiguous: 0.05
base_confidence: 0.75
lifecycle: stable
lifecycle_changed: 2026-05-11
created: 2026-05-11T21:00:00Z
updated: 2026-05-11T23:00:00Z
project: uap
---

# Range Fouler

A **Navy / naval-aviation operational concept** for unauthorized contacts — aircraft, drones, balloons, or other unidentified objects — intruding on or near a designated training range or operational area, prompting directed intercept identification by airborne fighter or ISR assets, or passive ISR observation by a loitering platform.

**Anchored at N=3** in the wiki corpus by:

- [[references/dow-uap-d38-range-fouler-middle-east-may-2020|DoW-UAP-D38]] (**14 May 2020 2040Z night ISR tasking**, Persian Gulf coast near Ras Tanura / Bahrain margin ^[inferred]; 1X round IR-cold "solid white" object on Black-Hot polarity at ~20,000 ft over water; intermittent track + 4× zoom + erratic in-track movements; sensor-operator narrative; **earliest range-fouler in the corpus** — 5 months before d44/d58)
- [[references/dow-uap-d44-range-fouler-arabian-sea-october-2020|DoW-UAP-D44]] (15 Oct 2020 1418Z daytime Gulf of Aden encounter, 172 ATKS Michigan ANG MQ-9 Reaper user ^[inferred], 1X round IR-cold contact at ~140 ft over sea surface ^[inferred], 73-second track with abrupt directional changes)
- [[references/dow-uap-d58-range-fouler-debrief-2020-10|DoW-UAP-D58]] (27 Oct 2020 0112Z night DCA encounter, 77 EFS user, 2X balloon-shaped metallic UAPs with red blinking strobes, 16.9 NM standoff, 1/30-s disappearance, noise jamming received)

**N=3 validation outcome**: the document class is **CONFIRMED on structural axes** (form schema, SPEAR intake pipeline, Navy-aviation form-template attribution, filename convention) and **DIVERGES further on capability-signature axes** at N=3 — d58's capability triad (sub-frame disappearance + active EW + standoff maintenance) is now isolated at **1-of-3 attestations**. The class catalogs **the full range-intrusion event distribution**; d58 is the high-anomaly tail and d38 + d44 are the lower-anomaly mid-distribution. The passive-ISR-observation sub-class (d38 + d44) is now the **dominant sub-class** within the range-fouler-debrief document class at 2-of-3.

**At N=3 the release framework is no longer byte-for-byte uniform within the class.** d55 + d58 + d44 share `MDR 26-0038 to 26-0046` + `03/27/26 000001`; **d38 carries a distinct block** `MDR 26-0019` + `01/26/26 001`. The "byte-for-byte recurrence at N=3" finding previously committed to the corpus (from the d44 ingest) is **partial at N=4** of release-block-testable artifacts. The release framework is per-MDR-case-allocation, not per-tranche-uniform. ^[inferred]

## Working definition

A **range fouler** is, in Navy / naval-aviation usage:

1. A **non-participating contact** — not part of the planned exercise / mission / range usage.
2. **Intruding on a designated airspace area** — typically a warning area (e.g. `W-72 1A` per the [[references/dow-uap-d58-range-fouler-debrief-2020-10|d58 form's]] example field) or a CENTCOM-AOR training-range corridor.
3. **Requiring positive identification** — either to clear the range for the planned activity, to ascertain identity (commercial overflight, foreign military, hostile, anomalous), or to remove the contact from the operational area.

The term is **Navy / naval-aviation-community vocabulary** ^[inferred] — the d58 + d44 + d38 forms' pre-printed sensor option set (`AIM-9x Self-Track`, `ATFLIR Autotrack`) and template-example filename (`4 May VFA-106 HUD.wmv`) anchor the form in the F/A-18 community. The d58 user is USAF Active Component (77 EFS Expeditionary Fighter Squadron); the d44 user is USAF Reserve Component (172 ATKS Michigan ANG MQ-9 Reaper community ^[inferred]); the d38 user is unattributed (squadron field blank in OCR). The form is **extended for joint-service use** in CENTCOM AOR across at least three components at N=2 ^[inferred].

**The term "range fouler" is institutional-form vocabulary, not pilot/operator vernacular** — strengthened at N=2 by d38. The form's title uses it; pilots/operators may pick it up (d58 narrative) or use generic "object/contact" language (d44 + d38 narratives both use generic language). 2 of 3 witness narratives at N=3 use the generic vernacular; only d58 picks up the form's headline term. ^[inferred]

## Why "range fouler" is a meaningful behavioral category for the UAP corpus

The Navy-operational usage encompasses prosaic intrusions (lost commercial aircraft, foreign drones, weather balloons) **and** anomalous intrusions. The class catalogs both ends of the distribution — d38 + d44 sit closer to the prosaic-candidate-compatible end (slow IR-cold "solid/bright white" objects on Black-Hot polarity with in-track kinematic anomaly, readable as drone / kite / controlled balloon / anomalous) while d58 sits at the high-anomaly tail (radar evasion + active EW + standoff maintenance triad).

**Anomaly signature distribution at N=3:**

| Signature | d58 | d44 | d38 | At-N=3 verdict |
|---|---|---|---|---|
| Sub-second disappearance | ☑ (1/30 s) | ☐ (bounded 73-s track) | ☐ (intermittent lose-and-reacquire) | **d58-isolated at 1-of-3** |
| Active EW reception | ☑ (noise jamming, two-chevron RWR) | ☐ (all 5 EA boxes unchecked) | ☐ (all 5 EA boxes unchecked) | **d58-isolated at 1-of-3** |
| Standoff floor enforcement | ☑ (16.9 NM minimum) | n/a (passive observation) | n/a (passive observation) | **d58-isolated at 1-of-3** |
| Multi-object with intra-group interaction | ☑ (2 contacts, one circling other) | ☐ (1 contact) | ☐ (1 contact) | **d58-isolated at 1-of-3** |
| Radar lock + visual tally | ☑ | ☐ (IR-only, no tally) | ☐ (IR-only, no tally) | **d58-isolated at 1-of-3** |
| Slow drift (low-Mach kinematics) | ☑ (060°/20 KT) | ☑ (261°/30 mph, 319°/20 mph) | (not captured; narrative `erratic moments`) | confirmed at N=2 (d44 + d58); d38 silent |
| Kinematic anomaly (in-track) | ☑ (sub-second exit) | ☑ (abrupt directional changes) | ☑ (erratic movements + intermittent track) | **CONFIRMED at N=3** but anomaly classes differ |
| IR-cold thermal polarity (Black Hot + bright/white object) | ☐ (red blinking strobes, visible-light) | ☑ (bright-white-on-Black-Hot) | ☑ (solid-white-on-Black-Hot) | **IR-cold anchors at N=2 (d38+d44)** |
| Round-only morphology checkbox | ☐ (5 checkboxes) | ☑ (sole Round) | ☑ (sole Round) | **Round-only anchors at N=2 (d38+d44)** |
| Passive ISR observation posture | ☐ (DCA intercept) | ☑ (MTS-B turret loiter) | ☑ (ISR tasking) | **passive-ISR anchors at N=2 (d38+d44)** |
| Mission descriptor | DCA | (not captured) | ISR | DCA + ISR at N=2 captured |
| Bounded encounter duration | n/a (sub-second exit) | ☑ (73 sec start-to-end) | (not captured) | d44-introduced |
| Intermittent trackfile | ☐ (Stable Yes) | ☐ (blank) | ☑ (Intermittent + lose-and-reacquire) | **d38-introduced datum** |
| Sensor zoom + operator manipulation | ☐ | ☐ | ☑ (4× zoom + sensor-operator slewing) | **d38-introduced datum** |

When an unidentified range-fouler contact:

- **Cannot be identified at standoff** despite radar lock + sensor-pod acquisition (d58 = 16.9 NM minimum approach floor; d44 = passive observation, no closure attempt)
- **Disappears below the sensor's resolution capability** in sub-frame timescales (d58 = 1/30 s — one TGT-pod video frame at 30 fps) — **d58-isolated at N=2**
- **Emits active electronic-warfare signatures** (d58 = noise jamming received, indicated by two RWR chevrons) — **d58-isolated at N=2**
- **Exhibits intra-group interaction** that conventional drones / balloons / commercial aircraft do not (d58 = "one range fouler was circling around the other") — **d58-isolated at N=2 (single contact at d44)**

…the contact escalates from *prosaic range fouler* (resolvable through standard ID-and-clear procedures) to **anomalous range fouler** — which the [[entities/dow-uap-foia-release|DoW-UAP FOIA release series]] explicitly catalogs as a UAP-class concern (the form is titled "Range Fouler Reporting Form" / "Range Fouler Debrief Form" — see *Form title variants* below — and routes through Navy SPEAR sanitization + USCENTCOM MDR + AARO release).

## Form title variants at N=3 — form-version-evolution reading rejected by non-monotonicity

The three range-fouler-debrief artifacts in the corpus carry **two distinct form titles in non-monotonic temporal order**:

| Source | Date | Form title (verbatim) |
|---|---|---|
| **d38 (14 May 2020)** | **earliest** | **`# Range Fouler Debrief Form`** |
| d44 (15 Oct 2020) | middle | `# Range Fouler Reporting Form` |
| d58 (27 Oct 2020) | latest | `# Range Fouler Debrief Form` |

**At N=3 the form-version-evolution reading is rejected for non-monotonicity** — the title sequence is Debrief → Reporting → Debrief, not a monotonic rename in either direction. The d44 page (and an earlier version of this concept page) had previously committed to "form-version evolution most probable given 12-day spread"; d38 falsifies that reading because the earliest artifact (May 2020) carries the same title as the latest (Oct 27) but not the middle (Oct 15) ^[inferred].

Two readings remain live ^[ambiguous]:

1. **Two co-existing form variants in parallel** — SPEAR maintained both a `Reporting Form` and a `Debrief Form` simultaneously through at least May–Oct 2020. The two variants were assigned to different events, different intake operators, or different witness contexts rather than evolved chronologically. **Most probable at N=3** ^[inferred] given the non-monotonic ordering. The two-variant distribution at N=3 is 2 Debrief (d38 + d58) + 1 Reporting (d44).
2. **OCR variance** — at least one of the three OCR passes mistranscribed the title; the underlying form text is identical. Three OCR passes producing two internally-consistent renderings (one Reporting, two Debrief) is less consistent with three independent OCR errors than with two genuine variants. Weak at N=3.

The class can be unified at the schema level regardless — the form bodies (instruction block, identity grid, event metadata, position grid, sensor+track grid, morphology checkboxes, narrative, submission instructions, SPEAR clause) match byte-for-byte at N=3 modulo the title. (The release-framework block does NOT match at N=3 — see *Release framework at N=4* below.)

## Range-fouler vs other UAP-encounter framings

The dow-uap series carries **three top-level mission-record document classes** at N=12 ingests:

| Class | Anchor | Distinguishing feature |
|---|---|---|
| Mission report — USMTF GENTEXT/UAP | d4 + d5 + d7 + d54 + d8 | Narrative segment in standard military-text format; emphasizes UAP kinematic + morphology description |
| Mission report — CTG narrative | d55 | BLUF / Timeline / Weather / Comments; carries explicit prosaic-candidate identification by the originating CTG |
| **Range-fouler debrief** | **d38 + d44 + d58 (N=3 confirmed)** | **Fielded form** with pre-printed schema; emphasizes intercept-or-observation posture + sensor-channel acquisition + range-management context |

The **range-fouler debrief class is distinct from the mission-report class** in three structural ways:

1. **Schema-driven, not narrative-driven** — the form pre-printed fields constrain what is captured. The witness fills slots; doesn't write prose. The free-text narrative section is a **fallback for things the form's slots don't cover**.
2. **Range-management context, not theater-mission context** — mission reports document a UAP encountered *during* a mission (DCA, CAS, BFM, RTB). Range-fouler debriefs document a UAP encountered *because* the UAP intruded on the operational area, prompting an unscheduled intercept or persistent ISR observation.
3. **Centralized SPEAR intake** — the form's instruction block routes submissions to a single email address (FOIA-`(b)(6)` redacted) for analysis. The SPEAR program (^[inferred] Navy-aviation intelligence-analysis pipeline) sanitizes each form on receipt — a different intake pathway from the USMTF mission-report flow. **Confirmed at N=2** with d44.

## Two distinct in-class behavioral sub-classes at N=3 — sub-class B is dominant

The d38 + d44 + d58 trio anchors **two distinct in-class behavioral sub-classes** within the range-fouler-debrief document class. Sub-class B (passive-ISR-observation) is now **dominant at 2-of-3 attestations**.

### Sub-class A: range-fouler-attempted-ID (d58 only at N=3)

- **Aircraft posture**: directed intercept-for-identification (DCA mission, KINGPIN tasking).
- **Aircraft platform**: manned fighter (F/A-18 or similar; 77 EFS).
- **Sensor channels**: radar lock + TGT-pod video + visual tally.
- **Closure attempt**: yes; blocked at 16.9 NM standoff floor.
- **Anomaly signature**: sub-second disappearance + active EW reception + standoff maintenance triad.
- **Engagement-pipeline alignment**: intercept-blocked (not weapons-quality).
- **Attestations at N=3**: 1 (d58 only) — **isolated at N=3**.

### Sub-class B: range-fouler-passive-ISR-observation (d44 + d38 at N=2 — dominant)

- **Aircraft posture**: passive ISR observation / ISR tasking. No intercept attestation.
- **Aircraft platform**: EO/IR turret-equipped ISR platform — d44 = MQ-9 Reaper ^[inferred]; d38 = unattributed but compatible with P-8A / MQ-9 / MQ-4C / RQ-4 / EP-3 / rotary-wing ISR ^[inferred].
- **Sensor channels**: EO/IR turret on Black-Hot polarity; d44 narrative confirms MTS-B IR-channel; d38 narrative confirms IR turret + 4× zoom + Lin gain mode + ULTN mode-token; no radar, no AIM-9X, no ATFLIR, no tally in either.
- **Closure attempt**: none in both; observed passively.
- **Anomaly signature**: in-track kinematic anomaly (d44 = abrupt directional changes during bounded 73-sec encounter; d38 = erratic movements + intermittent track with lose-and-reacquire); zero EA reception in both (5-row EA Indications block structurally confirmed at N=2 in pre-printed form schema); **IR-cold thermal polarity** in both (bright/solid-white on Black-Hot = colder-than-ambient).
- **Engagement-pipeline alignment**: passive observation (no engagement attempt).
- **Attestations at N=3**: 2 (d44 + d38) — **dominant at N=3**.

The two sub-classes diverge on **aircraft posture × platform × sensor channels × closure × anomaly signature**, but converge on **slow-kinematic baseline, single-event range-intrusion framing, SPEAR intake routing, AARO release pathway, and CENTCOM-AOR placement**. ^[inferred] The sub-class B IR-cold + round + single-contact + Black-Hot signature is a **within-class behavioral cluster** at N=2 attestations ^[inferred] — both passive-ISR-observation events in the corpus produce the same morphology + thermal-polarity signature.

## Release framework at N=4 — two distinct allocations within the dow-uap range-fouler subset

d38's release block **does not match** d44/d58's block. The "byte-for-byte release-block recurrence at N=3" finding (d55 + d58 + d44 share `MDR 26-0038 to 26-0046` + `03/27/26 000001`) is **partial at N=4** of release-block-testable artifacts:

| Field | d55 / d58 / d44 (Block A) | d38 (Block B) | Match? |
|---|---|---|---|
| Declassification authority | MG Richard A. Harrison | MG Richard A. Harrison | **MATCH** |
| MDR case | `26-0038 to MDR 26-0046` (9-case range) | `26-0019` (single case) | **DIFFERS** |
| Routing stamp | Approved for Release to AARO | Approved for Release to AARO | **MATCH** |
| Release-stamp date | `03/27/26` | `01/26/26` | **DIFFERS** (60 days earlier) |
| Release sequence number | `000001` (6-digit) | `001` (3-digit) | **DIFFERS** (format + value) |

**Findings at N=4**:

- **At least 2 distinct USCENTCOM MDR allocations** within the dow-uap range-fouler subset (`26-0019` for d38; `26-0038 to 26-0046` for d55/d58/d44 triplet). The release framework is **per-MDR-case-allocation**, not per-tranche-uniform. ^[inferred]
- **At least 2 distinct release dates** within the subset (`01/26/26` for d38; `03/27/26` for d55/d58/d44). The dow-uap-tranche release was **incremental** over ~60+ days, not single-batch. ^[inferred]
- **Per-batch sequence-number reading strengthens decisively** — d38 `001` (3-digit) in one allocation + d55/d58/d44 `000001` (6-digit) in another. The OCR-artifact reading of identical `000001` is now rejected (a uniform corruption pattern would produce `001` everywhere, or `000001` everywhere). The per-MDR-case reading is most probable; each batch carries its own sequence start. ^[inferred]
- **The 9-document USCENTCOM sub-batch hypothesis** (from d55/d58/d44) is refined: d55 + d58 + d44 are 3 of the 9 cases in their batch; d38 sits in a different batch (`26-0019` single case). The dow-uap range-fouler subset is **distributed across multiple MDR allocations**, not concentrated in one.

Despite the release-framework divergence, the **form template + SPEAR clause + submission instructions + Navy-aviation pre-printed sensor schema all match byte-for-byte at N=3** across d38 + d44 + d58. The form is unchanged; only the post-form release-stamp differs by MDR-case allocation. ^[inferred]

## Source observations (N=3 from d38 + d44 + d58)

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
- **CENTCOM-AOR placement**: explicit (Persian Gulf coordinate in CENTCOM AOR). Third CENTCOM-AOR anchor in the class at N=3.

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

## CENTCOM-AOR anchoring at N=3 — all three artifacts in CENTCOM AOR

The range-fouler debrief class is now **CENTCOM-AOR-anchored at N=3** with:

- **d38**: **explicit** Persian Gulf coordinate ^[inferred] (DMS 28°31'N 49°52'E near Ras Tanura / Bahrain margin, eastern Saudi Arabia) — first Persian Gulf body-text coordinate in the dow-uap corpus
- d44: **explicit** Gulf of Aden + MGRS 40Q BD body-text anchor
- d58: **inferred** via USCENTCOM-prefix MDR + 77 EFS rotation history + KINGPIN callsign

The class is now **CENTCOM-AOR-anchored at 100% of attestations**. All three range-fouler-debrief events fall in CENTCOM AOR; the class is implicitly **a CENTCOM-AOR institutional pattern** ^[inferred].

**At N=3, the within-CENTCOM theater distribution diverges**: d38 = Persian Gulf (Saudi eastern coast near Ras Tanura / Bahrain margin); d44 = Gulf of Aden (Arabian Peninsula southern grid); d58 = CENTCOM-inferred but no specific sub-theater attestation. The class is not concentrated in any single sub-theater within CENTCOM AOR. ^[inferred]

**Paired-incident hypothesis revision**: at N=2 the d44 + d58 October-2020 pair anchored the paired-incident reading at the operational-area level (both Oct 2020 CENTCOM). At N=3 with d38 (May 2020, 5 months earlier, different sub-theater Persian Gulf vs Gulf of Aden), **the paired-incident hypothesis is rejected as a class-defining pattern** — the class catalogs events distributed across at least 2 sub-theaters and 2 quarters within CENTCOM AOR. ^[inferred] d44 + d58 may still be a paired incident at the operational-area level, but the broader class is not. d38 sits as an independent earlier datum.

## Platform breadth at N=3 — 2-of-3 platforms unattributed at the squadron level

The range-fouler class at N=3 carries **witnessing-platform anchors with varying attribution depth**:

- **d58**: manned fighter — 77 EFS USAF Active Component (likely F-16C/CM Fighting Falcon) ^[inferred] — explicit squadron
- **d44**: USAF/ANG RPA — 172 ATKS Michigan ANG MQ-9 Reaper ^[inferred] — explicit squadron
- **d38**: unattributed at the squadron level (Squadron field blank/unrendered in OCR); narrative + sensor-mode evidence is compatible with **EO/IR turret-equipped ISR platform** (P-8A / MQ-9 / MQ-4C / RQ-4 / EP-3 / rotary-wing) ^[inferred] but the platform space is not constrained to one type

The form's pre-printed sensor schema is **Navy-fighter-centric** (AIM-9X + ATFLIR + Navy-aviation VFA-106 template example) but **the witnessing platforms at N=3 are non-Navy-fighter in 2 of 3 attestations** (d44 = USAF/ANG MQ-9; d58 = USAF F-16 ^[inferred]; d38 = compatible-with-non-Navy-fighter). The form is **Navy-template-but-multi-service-used** at N=2 confirmed via explicit attestation; d38 is **structurally compatible** with the multi-service-use reading but does not add a unit-anchor. ^[inferred] The form's flexibility in handling non-Navy-fighter platforms (blank values honest for non-applicable schema slots) is now anchored at N=3.

## Open questions

- **What does SPEAR stand for?** — Navy-aviation intelligence-analysis pipeline; the form's centralized intake operator. **Confirmed at N=3 via verbatim clause recurrence** (d38 + d44 + d58). SPEAR pipeline existence anchored at May 2020 (d38) — at least 5 months earlier than previously attested. Open-source identification still pending.
- **What was the bullseye `ZIM`?** — first-detection bullseye reference in d58; bullseye name keyed to a specific operational area. d38 + d44 used DMS + MGRS coordinates respectively (not bullseye), so `ZIM` remains d58-isolated at N=3.
- **Are range-fouler debriefs systematically routed through a different intake than mission reports?** — d38 + d44 + d58 SPEAR pipeline + [[references/dow-uap-d50-email-indopacom-2025-04|d50's]] OUSD(I&S) pipeline + [[references/dow-uap-pr20-prepublication-clearance-2026-03|PR20's]] DOPSR pipeline collectively suggest the dow-uap corpus carries **at least three distinct intake/clearance pathways**. SPEAR intake confirmed at N=3 for the range-fouler subset.
- **Does the range-fouler debrief class always carry anomalous content?** — by design, the class catalogs *all* range-intrusion events for analysis. The dow-uap subset catches the anomalous tail. At N=3, d38 + d44 sit closer to the prosaic-candidate-compatible mid-distribution; d58 sits at the high-anomaly tail. The class catalogs high + mid distribution at 1:2 ratio at N=3.
- ~~**Form-title variant (`Reporting` vs `Debrief`) at N=3**~~ ^closed-by-dow-uap-d38 — **PARTIALLY CLOSED at N=3**: d38 carries `Debrief Form`. The form-version-evolution reading is **rejected** for non-monotonicity (Debrief → Reporting → Debrief). Two-co-existing-variants reading is most probable at N=3. Distribution at N=3: 2 Debrief (d38 + d58) + 1 Reporting (d44). Further test at N≥4 would refine which variant is dominant.
- ~~**EA Indications block recurrence at N=3**~~ ^closed-by-dow-uap-d38 — **CLOSED at N=2 structurally** (d44 + d38 both capture the pre-printed 5-row block, both all-unchecked). The block is structurally part of the form schema. d58's narrative-substitute (noise-jamming free-text) is a fallback for when the witness narratively describes EW reception rather than checking boxes.
- ~~**Does the capability triad (sub-frame disappearance + active EW + standoff maintenance) recur at N=3?**~~ ^closed-by-dow-uap-d38 — **NEGATIVE-CLOSURE at N=3**: d38 does **not** carry any element of the d58 capability triad. The triad is now **isolated at 1-of-3 attestations**. The triad is **not** a class-defining signature; d58 is the high-anomaly outlier. ^[inferred]
- ~~**Does the passive-ISR-observation posture (d44) recur at N=3?**~~ ^closed-by-dow-uap-d38 — **CLOSED at N=2**: d38 anchors a second passive-ISR-observation attestation. Sub-class B is now dominant at 2-of-3 attestations within the range-fouler-debrief class. d44 is no longer the isolated passive-ISR outlier.
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

## See also

- [[references/dow-uap-d38-range-fouler-middle-east-may-2020]] — **Anchor artifact #1 by chronology** (N=3 extension; 14 May 2020 Persian Gulf coast; passive-ISR sub-class; **earliest range-fouler in the corpus**; carries the distinct release-framework Block B `MDR 26-0019` + `01/26/26 001` — falsifies byte-for-byte release-block recurrence)
- [[references/dow-uap-d44-range-fouler-arabian-sea-october-2020]] — Anchor artifact #2 (15 Oct 2020 Gulf of Aden; passive-ISR sub-class; sister to d38 in the dominant sub-class)
- [[references/dow-uap-d58-range-fouler-debrief-2020-10]] — Anchor artifact #3 (27 Oct 2020 intercept posture; **high-anomaly outlier** isolated at 1-of-3 with sub-second-disappearance + active-EW + standoff-maintenance triad)
- [[entities/dow-uap-foia-release]] — Series-level anchor; range-fouler debrief is the third top-level mission-record document class confirmed at N=3 (structure-CONFIRMED on 12-of-13 axes; release-framework PARTIAL at 2 distinct allocations)
- [[concepts/uap-aircraft-engagement]] — Behavioral framework — d58 anchors sub-class 6 (range-fouler-attempted-ID); d44 + d38 anchor sub-class 7 (range-fouler-passive-ISR-observation) at N=2
- [[references/dow-uap-d7-mission-arabian-gulf-2020]] — Closest behavioral analog on the aircraft-toward-UAP axis (d7 = WQT + NTS + TFLIR; d58 = radar lock + TGT-pod video + 16.9 NM standoff; d44 + d38 = EO/IR turret + passive observation)
- [[references/dow-uap-d55-mission-syria-2016-11-18]] — Release-framework Block A first attestation (now N=3 within Block A with d58 + d44; d38 carries distinct Block B)
- [[entities/aaro]] — Receiving authority for the dow-uap series; SPEAR may feed AARO downstream; AARO routing now anchored at N=4 across two distinct MDR-case allocations
- [[entities/ryan-graves]] — Navy F/A-18F pilot; operational analog for the form's AIM-9x + ATFLIR Navy-aviation template (now contrasted at N=2 attested with USAF Active + ANG users)
- [[projects/uap/uap]]
