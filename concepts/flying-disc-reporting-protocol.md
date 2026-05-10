---
title: Flying Disc Reporting Protocol (1948 → 1949)
category: concepts
tags: [uap, history, intelligence, protocol, 1948]
aliases: [USAF 10-element sighting template, Cabell sighting template, AIRMEM 4 protocol]
sources: [_raw/18_6369445_general_1948_vol_1.json, sources/65_hs1-834228961_62-hq-83894_serial_164.json]
summary: The observational template for USAF "Flying Disc" sighting reports — 10-element 1948 Cabell template (27 Feb 1948 AFOIR-CO-5) that AIRMEM #4 (15 Feb 1949) expanded into a ~50-field 1949 schema with object/observer/radar/general sub-blocks.
provenance:
  extracted: 0.88
  inferred: 0.12
  ambiguous: 0.0
base_confidence: 0.7
lifecycle: draft
lifecycle_changed: 2026-05-09
created: 2026-05-09T12:58:46Z
updated: 2026-05-10T00:30:00Z
---

# Flying Disc Reporting Protocol (1948)

The standardized observational template every Air Force installation was required to use when filing a "Flying Disc" sighting report, codified in [[entities/c-p-cabell|Maj Gen C. P. Cabell's]] 27 February 1948 disposition form (file AFOIR-CO-5; later reissued as ADC Letter 45-5 on 25 March 1948).

## Required fields

For each report, the originator was to record:

a. **Location and time** of sighting
b. **Weather** at the time
c. **Names, occupations, and addresses of witnesses**
d. **Photographs** of objects, if available
e. **Object sighted** — itemized:
   1. Number
   2. Shape
   3. Size
   4. Color
   5. Speed
   6. Heading
   7. Maneuverability
   8. Altitude
   9. Sound
   10. Exhaust trail or not

g. **General remarks** (item "f" appears to have been folded into "e" in the original; the 10-element subsection is the canonical part). ^[ambiguous]

The Cabell directive routed all completed reports to the Commanding General, [[entities/air-materiel-command|Air Materiel Command]], [[entities/wright-patterson-afb|Wright-Patterson AFB]], Attn: MCI. ^[extracted]

## Field examples in the source

The May 1948 [[references/sighting-hobson-ohio-1948-05|Hobson, OH report]] is filed in this exact 10-element format — including "unknown by this Hq" stamped against the fields the originating headquarters could not fill in. ^[extracted]

## Why it mattered

This 1948 schema is, in effect, the prototype for every modern UAP report format. It privileges:

- **Multi-witness corroboration** (item c)
- **Physical signatures** that constrain conventional explanations: speed, altitude, maneuverability, exhaust (items e.5, e.7, e.8, e.10)
- **Sensory channels beyond vision** (sound: item e.9)

Subsequent USAF programs ([[concepts/project-sign|SIGN]], GRUDGE, BLUE BOOK) and the modern [[entities/aaro|AARO]] regime inherit the same observational backbone. ^[inferred]

## 1949 expansion: AIRMEM #4 takes the template from 10 fields to ~50

**Twelve months after** the original 27 Feb 1948 disposition, [[entities/c-p-cabell|Maj Gen Cabell]] — now **Director of Intelligence** — signs **AIR INTELLIGENCE REQUIREMENTS MEMORANDUM NUMBER 4 ("AIRMEM #4")** on **15 February 1949**, subject *"Unconventional Aircraft"* — see [[references/fbi-hq-62-83894-serial-164]]. AIRMEM #4 supersedes residual Army instruments (DA Coll Memo #7 of 21 Jan 1948 and CSGID 425.1 of 25 Mar 1948) and substantially **expands the 1948 template into a four-block ~50-field schema**: ^[extracted]

| Sub-block | 1948 fields | 1949 (AIRMEM #4) fields |
|---|---|---|
| **Object** | 10 (number, shape, size, color, speed, heading, maneuverability, altitude, sound, exhaust trail) | **20** — adds: distance/elevation/altitude split; tactics-or-maneuvers (vertical/horizontal/oscillating/fluttering/evasive/aggressive/erratic); exhaust-with-odor/evaporation/sound-correlation; effect-on-clouds; lights (reflected/luminous/blinking); support (wings/aerodynamic-list/vertical-jet/rotating-cylinder/aerostatic-lift); propulsion (propeller/jet/rotor/aerodynamic-vanes); control-and-stability (fins, horizontal & vertical stabilizers); air-ducts; manner-of-disappearance (explode-with-fragments / fade / disappear) |
| **Observer** | 1 line (name + occupation + reliability) | **10 fields** — name / address / occupation / place-of-business / pertinent hobbies (amateur astronomer, pilot, engineer + length of experience) / ability to determine (color, speed, size at distance) / **reliability of observer with explicit sources: neighbors, Police Dept, FBI records, employer** / how attention was drawn (sound/motion/glint) / fatigue and duration of flight / witnesses / **interrogator's comments on intelligence and character of person interrogated** |
| **Radar** | (absent) | **2-block radar sub-section** — ground-radar (range/speed/altitude/size, target-turn radius/speed, target-separation on approach) + airborne-radar (radar inductions, extra noise on radio circuits, size/speed/maneuvers) |
| **General** | 1 line (general remarks) | **10 numbered post-incident fields** — local weather teletype sequences; winds-aloft; local flight schedules of commercial / private / military / Canadian aircraft; possible testing-device releases by Ordnance / Navy / AF / Army / Weather Units / Research Orgs; **soil samples** within and without depression where object landed; **Geiger counter readings** for radioactivity comparing affected vs unaffected aircraft; **photographs (or original negatives) with sketches** of object / terrain / ground-contact / maneuvers / formation; signed statement; fragments or physical evidence; any radio antenna or projection |

The 1948 → 1949 expansion is structurally **3–5×** in field count and substantively introduces several methodologies not present in the 1948 template:

- **Physical-trace investigation** — soil samples, Geiger-counter readings, signed-statement procedures. The Geiger-counter requirement anticipates the on-scene physical-trace investigation later carried out by [[entities/d-arthur-byrnes-jr|SA Byrnes]] at Socorro NM in 1964 — see [[references/fbi-hq-62-83894-serial-438]]. ^[inferred]
- **FBI as named witness-credibility source** — the *"reliability of observer"* sub-section explicitly names *"FBI records"* as one of four credibility-check sources (alongside neighbors, police, and employer). This is the institutional reverse-pull from the Air Force onto the Bureau, partly explaining why the FBI maintained an indexed UAP-topic file ([[entities/fbi-hq-62-83894-file|62-HQ-83894]]) at HQ. ^[inferred]
- **Witness-character note** — the *"intelligence and character of person interrogated"* line **institutionalizes** the witness-character note that recurs in every substantive FBI artifact in the corpus (Rathbun on Krasuski 1957; Byrnes on Zamora 1964). ^[inferred]
- **Foreign-balloon hypothesis testing** — Part II GENERAL item 4 names testing-device releases by **Ordnance, Navy, AF, Army, Weather Units, Research Organizations**, *enabling* the [[references/usaf-flying-discs-1949|Moxon 8 Feb 49 San Andres Islands]] report's speculation about Russian sloops (Omar / Blesk) carrying free-flight balloons. ^[inferred]
- **Radar sub-block** — explicit ground/airborne radar fields are absent from the 1948 template; the 1949 schema treats radar as a co-equal sensor channel.

The **1948 template** governed the [[concepts/project-sign|Project SIGN]] year-one intake (e.g. the 10-element [[references/sighting-hobson-ohio-1948-05|Hobson, OH report]]). The **1949 template** governs the post-handover SIGN-mature / GRUDGE-prep era, sitting alongside [[concepts/fsr-200-4-reporting-regulation|FSR 200-4]] (which propagates the Cabell instrument into the Flight Service hierarchy on a different command channel).

## See also

- [[concepts/project-sign]]
- [[concepts/fsr-200-4-reporting-regulation]] — parallel Flight-Service instrument
- [[entities/c-p-cabell]]
- [[references/usaf-flying-discs-1948]]
- [[references/usaf-flying-discs-1949]]
- [[references/fbi-hq-62-83894-serial-164]] — AIRMEM #4 (15 Feb 1949), 17 OCR-identical carbons in FBI HQ file
- [[references/fbi-hq-62-83894-serial-438]] — 1964 Socorro investigation that exemplifies AIRMEM #4 Part II General-block methodology
- [[entities/fbi-hq-62-83894-file]] — FBI's HQ topic-file holding inbound USAF directives
