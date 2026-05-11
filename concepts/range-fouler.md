---
title: "Range Fouler"
category: concepts
tags: [uap, navy, military, behavior, pattern]
aliases: [range fouler, range-fouler, RF, range foulers]
sources: [sources/dow-uap-d58-range-fouler-debrief-na-october-2020.json, sources/dow-uap-d44-range-fouler-arabian-sea-october-2020.json]
summary: Navy / naval-aviation operational concept for unauthorized contacts intruding on a training range or operational area, prompting directed intercept identification. Anchored at N=2 by d58 (27 Oct 2020) + d44 (15 Oct 2020 Gulf of Aden) — class confirmed on structural axes, diverges on capability signature.
provenance:
  extracted: 0.50
  inferred: 0.45
  ambiguous: 0.05
base_confidence: 0.70
lifecycle: stable
lifecycle_changed: 2026-05-11
created: 2026-05-11T21:00:00Z
updated: 2026-05-11T22:00:00Z
project: uap
---

# Range Fouler

A **Navy / naval-aviation operational concept** for unauthorized contacts — aircraft, drones, balloons, or other unidentified objects — intruding on or near a designated training range or operational area, prompting directed intercept identification by airborne fighter or ISR assets.

**Anchored at N=2** in the wiki corpus by:

- [[references/dow-uap-d58-range-fouler-debrief-2020-10|DoW-UAP-D58]] (27 Oct 2020 0112Z night DCA encounter, 77 EFS user, 2X balloon-shaped metallic UAPs with red blinking strobes, 16.9 NM standoff, 1/30-s disappearance, noise jamming received)
- [[references/dow-uap-d44-range-fouler-arabian-sea-october-2020|DoW-UAP-D44]] (15 Oct 2020 1418Z daytime Gulf of Aden encounter, 172 ATKS Michigan ANG MQ-9 Reaper user ^[inferred], 1X round IR-cold contact at ~140 ft over sea surface ^[inferred], 73-second track with abrupt directional changes)

**N=2 validation outcome**: the document class is **CONFIRMED on structural axes** (form schema, SPEAR intake pipeline, release framework, filename convention, Navy-aviation form-template attribution) and **DIVERGES on capability-signature axes** (no sub-second disappearance in d44, no noise jamming in d44, single contact vs two, daytime vs night, kinematic anomalies of different classes). The class catalogs **the full range-intrusion event distribution**; d58 is the high-anomaly tail and d44 is the lower-anomaly mid-distribution. The d58-anchored capability triad (sub-frame disappearance + active EW + standoff maintenance) is **d58-isolated at N=2** — not a class-defining signature.

## Working definition

A **range fouler** is, in Navy / naval-aviation usage:

1. A **non-participating contact** — not part of the planned exercise / mission / range usage.
2. **Intruding on a designated airspace area** — typically a warning area (e.g. `W-72 1A` per the [[references/dow-uap-d58-range-fouler-debrief-2020-10|d58 form's]] example field) or a CENTCOM-AOR training-range corridor.
3. **Requiring positive identification** — either to clear the range for the planned activity, to ascertain identity (commercial overflight, foreign military, hostile, anomalous), or to remove the contact from the operational area.

The term is **Navy / naval-aviation-community vocabulary** ^[inferred] — the d58 + d44 forms' pre-printed sensor option set (`AIM-9x Self-Track`, `ATFLIR Autotrack`) and template-example filename (`4 May VFA-106 HUD.wmv`) anchor the form in the F/A-18 community. The d58 user is USAF Active Component (77 EFS Expeditionary Fighter Squadron); the d44 user is USAF Reserve Component (172 ATKS Michigan ANG MQ-9 Reaper community ^[inferred]). The form is **extended for joint-service use** in CENTCOM AOR across three components (Navy origination + Active USAF + ANG USAF) at N=2 ^[inferred].

**The term "range fouler" is institutional-form vocabulary, not pilot/operator vernacular** ^[inferred at N=2]. The form's title uses it; pilots/operators may pick it up (d58 narrative) or use generic "object/contact" language (d44 narrative).

## Why "range fouler" is a meaningful behavioral category for the UAP corpus

The Navy-operational usage encompasses prosaic intrusions (lost commercial aircraft, foreign drones, weather balloons) **and** anomalous intrusions. The class catalogs both ends of the distribution — d44 sits closer to the prosaic-candidate-compatible end (slow IR-cold low-altitude object with abrupt directional changes, readable as drone / kite / controlled balloon / anomalous) while d58 sits at the high-anomaly tail (radar evasion + active EW + standoff maintenance triad).

**Anomaly signature distribution at N=2:**

| Signature | d58 | d44 | At-N=2 verdict |
|---|---|---|---|
| Sub-second disappearance | ☑ (1/30 s) | ☐ (bounded 73-s track) | **d58-isolated** |
| Active EW reception | ☑ (noise jamming, two-chevron RWR) | ☐ (all 5 EA boxes unchecked) | **d58-isolated** |
| Standoff floor enforcement | ☑ (16.9 NM minimum) | n/a (passive observation, no closure attempt) | **d58-isolated** |
| Multi-object with intra-group interaction | ☑ (2 contacts, one circling other) | ☐ (1 contact) | **d58-isolated** |
| Radar lock + visual tally | ☑ | ☐ (IR-only, no tally) | **d58-isolated** |
| Slow drift (low-Mach kinematics) | ☑ (060°/20 KT) | ☑ (261°/30 mph, 319°/20 mph) | **CONFIRMED at N=2** |
| Kinematic anomaly (in-track) | ☑ (sub-second exit) | ☑ (abrupt directional changes) | **CONFIRMED at N=2** but anomaly classes differ |
| IR-channel signature | ☑ (2 IR-significant contacts on TGT pod) | ☑ (round IR-cold contact on MTS-B) | **CONFIRMED at N=2** but thermal polarity opposite (d58 hot-sig implied; d44 cold-sig explicit) |
| Bounded encounter duration | n/a (sub-second exit, total duration unbounded) | ☑ (73 sec start-to-end) | d44-introduced datum |

When an unidentified range-fouler contact:

- **Cannot be identified at standoff** despite radar lock + sensor-pod acquisition (d58 = 16.9 NM minimum approach floor; d44 = passive observation, no closure attempt)
- **Disappears below the sensor's resolution capability** in sub-frame timescales (d58 = 1/30 s — one TGT-pod video frame at 30 fps) — **d58-isolated at N=2**
- **Emits active electronic-warfare signatures** (d58 = noise jamming received, indicated by two RWR chevrons) — **d58-isolated at N=2**
- **Exhibits intra-group interaction** that conventional drones / balloons / commercial aircraft do not (d58 = "one range fouler was circling around the other") — **d58-isolated at N=2 (single contact at d44)**

…the contact escalates from *prosaic range fouler* (resolvable through standard ID-and-clear procedures) to **anomalous range fouler** — which the [[entities/dow-uap-foia-release|DoW-UAP FOIA release series]] explicitly catalogs as a UAP-class concern (the form is titled "Range Fouler Reporting Form" / "Range Fouler Debrief Form" — see *Form title variants* below — and routes through Navy SPEAR sanitization + USCENTCOM MDR + AARO release).

## Form title variants at N=2

The two range-fouler-debrief artifacts in the corpus carry **slightly different form titles**:

| Source | Form title (verbatim) |
|---|---|
| d44 (15 Oct 2020) | `# Range Fouler Reporting Form` |
| d58 (27 Oct 2020) | `# Range Fouler Debrief Form` |

Three readings live ^[ambiguous]:

1. **Form-version evolution** — d44 (15 Oct 2020) is 12 days earlier than d58 (27 Oct 2020); the form went through a title rename between the two events. Most probable at N=2 ^[inferred].
2. **OCR variance** — one OCR mistranscribed the title; the underlying form text is identical. The words "Debrief" and "Reporting" aren't visually-confusable in any common rendering, so this reading is weak.
3. **Two co-existing form variants** — SPEAR maintained both a *Reporting Form* (initial intake) and a *Debrief Form* (post-incident structured walkthrough) in parallel. Operationally plausible, but the form bodies are essentially identical so this would require unattested SPEAR-internal-process documentation.

The class can be unified at the schema level regardless — the form bodies (instruction block, identity grid, event metadata, position grid, sensor+track grid, morphology checkboxes, narrative, submission instructions, SPEAR clause, release framework) match byte-for-byte at N=2 modulo the title.

## Range-fouler vs other UAP-encounter framings

The dow-uap series carries **three top-level mission-record document classes** at N=11 ingests:

| Class | Anchor | Distinguishing feature |
|---|---|---|
| Mission report — USMTF GENTEXT/UAP | d4 + d5 + d7 + d54 + d8 | Narrative segment in standard military-text format; emphasizes UAP kinematic + morphology description |
| Mission report — CTG narrative | d55 | BLUF / Timeline / Weather / Comments; carries explicit prosaic-candidate identification by the originating CTG |
| **Range-fouler debrief** | **d58 + d44 (N=2 confirmed)** | **Fielded form** with pre-printed schema; emphasizes intercept-or-observation posture + sensor-channel acquisition + range-management context |

The **range-fouler debrief class is distinct from the mission-report class** in three structural ways:

1. **Schema-driven, not narrative-driven** — the form pre-printed fields constrain what is captured. The witness fills slots; doesn't write prose. The free-text narrative section is a **fallback for things the form's slots don't cover**.
2. **Range-management context, not theater-mission context** — mission reports document a UAP encountered *during* a mission (DCA, CAS, BFM, RTB). Range-fouler debriefs document a UAP encountered *because* the UAP intruded on the operational area, prompting an unscheduled intercept or persistent ISR observation.
3. **Centralized SPEAR intake** — the form's instruction block routes submissions to a single email address (FOIA-`(b)(6)` redacted) for analysis. The SPEAR program (^[inferred] Navy-aviation intelligence-analysis pipeline) sanitizes each form on receipt — a different intake pathway from the USMTF mission-report flow. **Confirmed at N=2** with d44.

## Two distinct in-class behavioral sub-classes at N=2

The d58 + d44 pair anchors **two distinct in-class behavioral sub-classes** within the range-fouler-debrief document class:

### Sub-class A: range-fouler-attempted-ID (d58 anchor)

- **Aircraft posture**: directed intercept-for-identification (DCA mission, KINGPIN tasking).
- **Aircraft platform**: manned fighter (F/A-18 or similar; 77 EFS).
- **Sensor channels**: radar lock + TGT-pod video + visual tally.
- **Closure attempt**: yes; blocked at 16.9 NM standoff floor.
- **Anomaly signature**: sub-second disappearance + active EW reception + standoff maintenance triad.
- **Engagement-pipeline alignment**: intercept-blocked (not weapons-quality).

### Sub-class B: range-fouler-passive-ISR-observation (d44 anchor)

- **Aircraft posture**: passive ISR observation (MQ-9 Reaper loiter ^[inferred]); no intercept tasking attested.
- **Aircraft platform**: USAF/ANG RPA (MQ-9 Reaper ^[inferred]; 172 ATKS).
- **Sensor channels**: MTS-B IR turret only ^[inferred]; no radar, no tally, no AIM-9X / ATFLIR.
- **Closure attempt**: none; observed at slant 4.06 NM throughout.
- **Anomaly signature**: abrupt directional changes during bounded 73-sec encounter; no EA reception; IR-cold (no propulsion heat plume) ^[inferred].
- **Engagement-pipeline alignment**: passive observation (no engagement attempt).

The two sub-classes diverge on **aircraft posture × platform × sensor channels × closure × anomaly signature**, but converge on **slow-kinematic baseline, range-intrusion framing, SPEAR intake routing, AARO release pathway, and CENTCOM-AOR placement**. ^[inferred]

## Source observations (N=2 from d58 + d44)

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

The d58 form text uses the phrase **"range fouler"** (singular) and **"range foulers"** (plural) interchangeably to refer to the unidentified contact(s). The d44 form's title uses "Range Fouler" but the d44 witness narrative does **not** use the term — instead uses "object" / "contact" generically. **First evidence at N=2 that "range fouler" is institutional-form vocabulary, not pilot/operator vernacular** ^[inferred].

The term is **not synonymous with "UAP"** — a range fouler that turns out to be a stray commercial aircraft is still a range fouler in the form's classification, just an identified one. The dow-uap series ingests the *anomalous* subset that remained unresolved post-debrief and got routed through the SPEAR → USCENTCOM MDR → AARO pipeline.

Adjacent operational concepts ^[inferred]:

- **Range clearing** — pre-mission verification that a warning area is unoccupied. Range foulers prevent clearing.
- **Bogey / bandit** — Navy / NATO codeword pair for unidentified-but-presumed-hostile (bogey) and identified-hostile (bandit) contacts. Range foulers may start as bogeys and resolve up or down the threat ladder.
- **Squawk** — IFF transponder code; a non-squawking contact in an active range area is a classic range-fouler precursor.
- **MTS-B vs ATFLIR** — d44's MQ-9 sensor schema (MTS-B + AN/APY-8 Lynx ground-imaging radar) vs d58's F/A-18 sensor schema (ATFLIR + APG-79). The range-fouler form's pre-print is Navy-fighter-centric; the form accommodates non-Navy-fighter platforms via blank-value honesty (d44's empty radar/AIM-9X/ATFLIR fields).
- **EA Indications block** — d44's pre-printed Electronic Attack reception schema (ECM / Arc / Letter Identifier / False Trackfiles / Other-Ambiguous). Captures structured EA-reception signaling that d58's narrative covered in free-text.

## CENTCOM-AOR anchoring at N=2

The range-fouler debrief class is now **CENTCOM-AOR-anchored at N=2** with:

- d44: **explicit** Gulf of Aden + MGRS 40Q BD body-text anchor
- d58: **inferred** via USCENTCOM-prefix MDR + 77 EFS rotation history + KINGPIN callsign

This supports the **paired-incident hypothesis at the operational-area level** ^[inferred]: both October 2020, both CENTCOM AOR, both range-fouler-class events 12 days apart. The hypothesis does **not** require d44 and d58 to document the same physical object — d44's single-object IR-cold round contact at ~140 ft over sea surface is morphologically distinct from d58's two-object metallic-balloon strobe-bearing tandem at higher altitude. The pairing operates at the **same-area same-month range-intrusion-cluster** level, not at the same-object level. ^[inferred]

## Platform breadth at N=2

The range-fouler class at N=2 carries **two distinct witnessing-platform anchors**:

- **d58**: manned fighter — 77 EFS USAF Active Component (likely F-16C/CM Fighting Falcon) ^[inferred]
- **d44**: USAF/ANG RPA — 172 ATKS Michigan ANG MQ-9 Reaper ^[inferred]

This is **operationally significant**: the form's pre-printed sensor schema is Navy-fighter-centric (AIM-9X + ATFLIR) but **the actual witnessing platforms at N=2 are both USAF — neither Navy fighter nor Navy P-8A**. The form is Navy-template-but-multi-service-used at N=2. ^[inferred] The d44 MQ-9 attribution extends the form's user-platform breadth to **non-fighter / non-manned / Reserve-Component USAF** — three structural firsts at one ingest.

## Open questions

- **What does SPEAR stand for?** — Navy-aviation intelligence-analysis pipeline; the form's centralized intake operator. Confirmed at N=2 via verbatim clause recurrence. Open-source identification still pending.
- **What was the bullseye `ZIM`?** — first-detection bullseye reference in d58; bullseye name keyed to a specific operational area. d44 used MGRS coordinates instead, so the bullseye `ZIM` remains d58-isolated.
- **Are range-fouler debriefs systematically routed through a different intake than mission reports?** — d58 + d44 SPEAR pipeline + [[references/dow-uap-d50-email-indopacom-2025-04|d50's]] OUSD(I&S) pipeline + [[references/dow-uap-pr20-prepublication-clearance-2026-03|PR20's]] DOPSR pipeline collectively suggest the dow-uap corpus carries **at least three distinct intake/clearance pathways**. SPEAR intake confirmed at N=2 for the range-fouler subset.
- **Does the range-fouler debrief class always carry anomalous content?** — by design, the class catalogs *all* range-intrusion events for analysis. The dow-uap subset of the class catches the anomalous tail. d44 sits closer to the prosaic-candidate-compatible end of the distribution; d58 sits at the high-anomaly tail. At N=2 the class carries both high and mid-distribution anomaly cases.
- **Form-title variant (`Reporting` vs `Debrief`) at N=3** — does the next range-fouler debrief carry one of the two variants attested at N=2, or a third? Resolution distinguishes form-version-evolution from OCR-variance from two-co-existing-variants.
- **EA Indications block recurrence at N=3** — does the next range-fouler debrief OCR capture the EA Indications block (as d44 did)? d58 OCR didn't capture it, but narrative-mentions of noise jamming suggest the block was present-but-unchecked-and-narratively-substituted.
- **Does the capability triad (sub-frame disappearance + active EW + standoff maintenance) recur at N=3?** — at N=2 the triad is d58-isolated. Recurrence at N=3 would establish a distinct **anomalous-tail sub-class** within the range-fouler class; non-recurrence would confirm d58 as an outlier event.
- **Does the passive-ISR-observation posture (d44) recur at N=3?** — if a third range-fouler debrief carries non-fighter / non-intercept posture, the class anchors a structurally-balanced fighter-vs-ISR-platform split. If all subsequent ingests revert to fighter / intercept posture, d44 is the MQ-9-isolated outlier.
- **Test the paired-incident hypothesis** — d58 + d44 are both October 2020 CENTCOM-AOR range-fouler events. Were they part of the same operational area / training-range / threat-actor cluster, or coincidental same-month observations? The bullseye `ZIM` (d58) and MGRS `40Q BD` (d44) might map to the same grid sector if recoverable.
- **Were there more October 2020 range-fouler debriefs in the original SPEAR queue that did not make the dow-uap release tranche?** — the question opens at N=2 with two same-month events in the corpus.
- **172 ATKS open-source rotation history** to USAFCENT in Oct 2020 — confirms the MQ-9 / CENTCOM placement of d44 at the squadron-rotation level if recoverable.

## See also

- [[references/dow-uap-d58-range-fouler-debrief-2020-10]] — Anchor artifact #1 (N=1, anomalous-tail sub-class)
- [[references/dow-uap-d44-range-fouler-arabian-sea-october-2020]] — Anchor artifact #2 (N=2 confirmation, mid-distribution sub-class)
- [[entities/dow-uap-foia-release]] — Series-level anchor; range-fouler debrief is the third top-level mission-record document class confirmed at N=2
- [[concepts/uap-aircraft-engagement]] — Behavioral framework — d58 anchors sub-class 6 (range-fouler-attempted-ID), d44 anchors sub-class 7 (range-fouler-passive-ISR-observation)
- [[references/dow-uap-d7-mission-arabian-gulf-2020]] — Closest behavioral analog on the aircraft-toward-UAP axis (d7 = WQT + NTS + TFLIR; d58 = radar lock + TGT-pod video + 16.9 NM standoff; d44 = MTS-B IR-only + passive observation)
- [[references/dow-uap-d55-mission-syria-2016-11-18]] — Release-framework triplet with d58 + d44 (identical MDR + AARO + Harrison + `03/27/26 000001` — N=3 confirmation)
- [[entities/aaro]] — Receiving authority for the dow-uap series; SPEAR may feed AARO downstream
- [[entities/ryan-graves]] — Navy F/A-18F pilot; operational analog for the form's AIM-9x + ATFLIR Navy-aviation template (now contrasted at N=2 with USAF Active and ANG users)
- [[projects/uap/uap]]
