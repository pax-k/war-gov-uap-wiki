---
title: "Range Fouler"
category: concepts
tags: [uap, navy, military, behavior, pattern]
aliases: [range fouler, range-fouler, RF, range foulers]
sources: [sources/dow-uap-d58-range-fouler-debrief-na-october-2020.json]
summary: Navy / naval-aviation operational concept for unauthorized contacts intruding on a training range or operational area, prompting directed intercept identification. Anchored at N=1 by d58 (27 Oct 2020); to be validated at N=2 by d44.
provenance:
  extracted: 0.40
  inferred: 0.55
  ambiguous: 0.05
base_confidence: 0.55
lifecycle: draft
lifecycle_changed: 2026-05-11
created: 2026-05-11T21:00:00Z
updated: 2026-05-11T21:00:00Z
project: uap
---

# Range Fouler

A **Navy / naval-aviation operational concept** for unauthorized contacts — aircraft, drones, balloons, or other unidentified objects — intruding on or near a designated training range or operational area, prompting directed intercept identification by airborne fighter assets.

**Anchored at N=1** in the wiki corpus by [[references/dow-uap-d58-range-fouler-debrief-2020-10|DoW-UAP-D58]] (27 Oct 2020 0112Z night DCA encounter, 77 EFS user, 2X balloon-shaped metallic UAPs with red blinking strobes, 16.9 NM standoff, 1/30-s disappearance, noise jamming received). The concept-page treatment is deliberately provisional pending the [[references/dow-uap-d44-range-fouler-arabian-sea-october-2020|d44]] ingest at N=2.

## Working definition

A **range fouler** is, in Navy / naval-aviation usage:

1. A **non-participating contact** — not part of the planned exercise / mission / range usage.
2. **Intruding on a designated airspace area** — typically a warning area (e.g. `W-72 1A` per the [[references/dow-uap-d58-range-fouler-debrief-2020-10|d58 form's]] example field) or a CENTCOM-AOR training-range corridor.
3. **Requiring positive identification** — either to clear the range for the planned activity, to ascertain identity (commercial overflight, foreign military, hostile, anomalous), or to remove the contact from the operational area.

The term is **Navy / naval-aviation-community vocabulary** ^[inferred] — the d58 form's pre-printed sensor option set (`AIM-9x Self-Track`, `ATFLIR Autotrack`) and template-example filename (`4 May VFA-106 HUD.wmv`) anchor the form in the F/A-18 community. The d58 *user* is USAF (77 EFS Expeditionary Fighter Squadron) which suggests the form has been **extended for joint-service use** in CENTCOM AOR. ^[inferred]

## Why "range fouler" is a meaningful behavioral category for the UAP corpus

The Navy-operational usage encompasses prosaic intrusions (lost commercial aircraft, foreign drones, weather balloons) **and** anomalous intrusions. When an unidentified contact:

- **Cannot be identified at standoff** despite radar lock + sensor-pod acquisition ([[references/dow-uap-d58-range-fouler-debrief-2020-10|d58]] = 16.9 NM minimum approach floor)
- **Disappears below the sensor's resolution capability** in sub-frame timescales (d58 = 1/30 s — one TGT-pod video frame at 30 fps)
- **Emits active electronic-warfare signatures** (d58 = noise jamming received, indicated by two RWR chevrons)
- **Exhibits intra-group interaction** that conventional drones / balloons / commercial aircraft do not (d58 = "one range fouler was circling around the other")

…the contact escalates from *prosaic range fouler* (resolvable through standard ID-and-clear procedures) to **anomalous range fouler** — which the [[entities/dow-uap-foia-release|DoW-UAP FOIA release series]] explicitly catalogs as a UAP-class concern (the form is titled "Range Fouler Debrief Form" not "Range Intrusion Form," and routes through Navy SPEAR sanitization + USCENTCOM MDR + AARO release).

## Range-fouler vs other UAP-encounter framings

The dow-uap series carries **three top-level mission-record document classes** at N=10 ingests:

| Class | Anchor | Distinguishing feature |
|---|---|---|
| Mission report — USMTF GENTEXT/UAP | d4 + d5 + d7 + d54 + d8 | Narrative segment in standard military-text format; emphasizes UAP kinematic + morphology description |
| Mission report — CTG narrative | d55 | BLUF / Timeline / Weather / Comments; carries explicit prosaic-candidate identification by the originating CTG |
| **Range-fouler debrief** | **d58 (this page)** | **Fielded form** with pre-printed schema; emphasizes intercept posture + sensor-channel acquisition + range-management context |

The **range-fouler debrief class is distinct from the mission-report class** in three structural ways:

1. **Schema-driven, not narrative-driven** — the form pre-printed fields constrain what is captured. The witness fills slots; doesn't write prose. The free-text narrative section is a **fallback for things the form's slots don't cover**.
2. **Range-management context, not theater-mission context** — mission reports document a UAP encountered *during* a mission (DCA, CAS, BFM, RTB). Range-fouler debriefs document a UAP encountered *because* the UAP intruded on the operational area, prompting an unscheduled intercept.
3. **Centralized SPEAR intake** — the form's instruction block routes submissions to a single email address (FOIA-`(b)(6)` redacted) for analysis. The SPEAR program (^[inferred] Navy-aviation intelligence-analysis pipeline) sanitizes each form on receipt — a different intake pathway from the USMTF mission-report flow.

## Source observations (N=1 from d58)

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

## Range-fouler vocabulary and adjacent concepts

The form text uses the phrase **"range fouler"** (singular) and **"range foulers"** (plural) interchangeably to refer to the unidentified contact(s). The term is **not synonymous with "UAP"** — a range fouler that turns out to be a stray commercial aircraft is still a range fouler in the form's classification, just an identified one. The dow-uap series ingests the *anomalous* subset that remained unresolved post-debrief and got routed through the SPEAR → USCENTCOM MDR → AARO pipeline.

Adjacent operational concepts ^[inferred]:

- **Range clearing** — pre-mission verification that a warning area is unoccupied. Range foulers prevent clearing.
- **Bogey / bandit** — Navy / NATO codeword pair for unidentified-but-presumed-hostile (bogey) and identified-hostile (bandit) contacts. Range foulers may start as bogeys and resolve up or down the threat ladder.
- **Squawk** — IFF transponder code; a non-squawking contact in an active range area is a classic range-fouler precursor.

## Why this is anchored on d58 and not deferred to d44

Per the d58 [[references/dow-uap-d58-range-fouler-debrief-2020-10|reference page]], the d58 artifact carries:

- **Explicit document header** (`# Range Fouler Debrief Form`)
- **Fully-populated schema** (identity / event metadata / position grid / sensor + track grid / morphology checkbox grid / free-text narrative / submission-instruction block)
- **Substantive narrative content** (KINGPIN tasking, 16.9 NM standoff, intra-group circling, 1/30-s disappearance, noise jamming, 2X red blinking strobes)
- **Class-internal abbreviation** (`_RF` filename suffix per the submission-filename schema)
- **First explicit data-pipeline name** (SPEAR centralized intake/sanitization)

This is enough to anchor the concept at N=1 with high confidence on the *form structure* axis. The d44 ingest (also October 2020, similar size) is expected to extend the template at N=2 and may carry **paired-incident** datums (the date proximity to d58 — both October 2020 — suggests d44 + d58 may document the same operational area / training range / threat-actor cluster). ^[inferred]

If d44 substantially extends or revises the d58-anchored class structure, **this page will be revised in place**, not appended.

## Open questions

- **What does SPEAR stand for?** — Navy-aviation intelligence-analysis pipeline; the form's centralized intake operator. Open-source identification pending.
- **What was the bullseye `ZIM`?** — first-detection bullseye reference in d58; bullseye name keyed to a specific operational area.
- **Are range-fouler debriefs systematically routed through a different intake than mission reports?** — d58 SPEAR pipeline + [[references/dow-uap-d50-email-indopacom-2025-04|d50's]] OUSD(I&S) pipeline + [[references/dow-uap-pr20-prepublication-clearance-2026-03|PR20's]] DOPSR pipeline collectively suggest the dow-uap corpus carries **at least three distinct intake/clearance pathways**. ^[inferred]
- **Does the range-fouler debrief class always carry anomalous content?** — by design, the class catalogs *all* range-intrusion events for analysis. The dow-uap subset of the class catches the anomalous tail; the prosaic tail is presumably routed elsewhere (and may not appear in this FOIA tranche at all). ^[inferred]
- **Does d44 corroborate the 1/30-s disappearance + noise-jamming signature?** — if yes, the range-fouler debrief class is anchoring a **capability signature** (radar evasion + active EW) distinct from the mission-report class's brief-observation kinematic-anomaly signature.

## See also

- [[references/dow-uap-d58-range-fouler-debrief-2020-10]] — Anchor artifact (N=1)
- [[entities/dow-uap-foia-release]] — Series-level anchor; range-fouler debrief is the third top-level mission-record document class at N=10 ingests
- [[concepts/uap-aircraft-engagement]] — Behavioral framework — d58's range-fouler-attempted-ID sub-class is the 6th brief-observation sub-class in the dow-uap corpus
- [[references/dow-uap-d7-mission-arabian-gulf-2020]] — Closest behavioral analog on the aircraft-toward-UAP axis (d7 = WQT + NTS + TFLIR; d58 = radar lock + TGT-pod video + 16.9 NM standoff; d58 stopped at intercept-blocked, d7 stopped at TFLIR-ID-and-decline)
- [[references/dow-uap-d55-mission-syria-2016-11-18]] — Release-framework twin to d58 (identical MDR + AARO + Harrison + `03/27/26 000001`)
- [[entities/aaro]] — Receiving authority for the dow-uap series; SPEAR may feed AARO downstream
- [[entities/ryan-graves]] — Navy F/A-18F pilot; operational analog for the form's AIM-9x + ATFLIR Navy-aviation template
- [[projects/uap/uap]]
