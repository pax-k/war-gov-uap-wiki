---
title: MQ-9 Reaper (General Atomics)
category: entities
tags: [usaf, platform, aircraft, uap, isr]
aliases: [MQ-9, Reaper, MQ-9 Reaper, General Atomics MQ-9, GA MQ-9]
sources: [sources/dow-uap-d60-mission-report-persian-gulf-august-2020.json, sources/dow-uap-d10-mission-report-middle-east-may-2022.json, sources/dow-uap-d14-mission-report-iraq-may-2022.json]
summary: General Atomics medium-altitude long-endurance unmanned ISR/strike aircraft. Inferred platform behind every full USMTF Misrep in the dow-uap corpus (FMV signature; ~21h mission envelope) and behind the range-fouler debrief corpus.
provenance:
  extracted: 0.3
  inferred: 0.65
  ambiguous: 0.05
base_confidence: 0.5
lifecycle: draft
lifecycle_changed: 2026-05-12
created: 2026-05-12T05:45:00Z
updated: 2026-05-12T05:45:00Z
---

# MQ-9 Reaper (General Atomics)

The **MQ-9 Reaper** — a General Atomics Aeronautical Systems medium-altitude long-endurance (MALE) **unmanned aerial vehicle**, operated by USAF and allied air forces in **ISR / hunter-killer** roles since ~2007. ^[inferred — open-source standard background; the wiki's dow-uap sources never name `MQ-9` literally.]

This page is a **stub hub**. MQ-9 is the **inferred platform behind every full USMTF Misrep in the dow-uap corpus** based on the Misreps' **`Method of Observation: FMV`** (Full Motion Video) signature, **`MTS-B`** sensor turret references in adjacent dow-uap range-fouler debriefs, and the **~21-hour mission cycle envelope** consistent with MQ-9 endurance (typically 27 hr clean, 14 hr with stores).

## Role in the dow-uap corpus

The MQ-9 attribution is corpus-internal-corroborated at N=9 across the dow-uap full-Misrep set:

- **2020 NAVCENT cluster (N=6)** — [[entities/482-atks|482 ATKS]] / [[entities/432-aew|432 AEW]], 8 Aug → 2 Nov 2020. `MTS-B` Method of Observation, FMV-only sensor profile, no radar track, no IFF, 20h 42min to 22h+ mission cycles. ^[extracted]
- **2022 USCENTCOM OIR cluster (N=2)** — d10 (432 AEW) + d12 (163 AW ANG MQ-9). Same FMV signature, same mission-cycle envelope. ^[extracted]
- **2022 USEUCOM Eastern Mediterranean (N=1)** — d14 (50 ATKS / 432 AEW, forward-deployed Sigonella AB Italy). FMV, 20h 30min cycle. ^[extracted]

Per-Misrep platform attribution chain: [[references/dow-uap-d60-mission-persian-gulf-2020-08-08|d60]] + [[references/dow-uap-d61-mission-persian-gulf-2020-08-27|d61]] + [[references/dow-uap-d62-mission-strait-of-hormuz-2020-09-16|d62]] + [[references/dow-uap-d63-mission-strait-of-hormuz-2020-10-02|d63]] + [[references/dow-uap-d64-mission-iran-2020-11-02|d64]] + [[references/dow-uap-d65-mission-persian-gulf-2020-07-16|d65]] + [[references/dow-uap-d10-mission-middle-east-2022-05-06|d10]] + [[references/dow-uap-d12-mission-iraq-2022-05-20|d12]] + [[references/dow-uap-d14-mission-iraq-2022-05-29|d14]].

## Significance for the corpus

- **The corpus's dominant 2020s UAP-observation platform.** MQ-9 is inferred behind 9 of the 9 full USMTF Misreps and behind several [[concepts/range-fouler|range-fouler]] debriefs (e.g., d38, d56 — paired with `MTS-B` / `XSPI` / Lightning Pod sensor packages). ^[inferred]
- **FMV-only sensor profile breaks the radar-visual canonical UAP signature.** Historical UAP signatures emphasized radar + visual concurrence (e.g., Tehran 1976). The MQ-9 dow-uap subset records **Negative ES, Negative radar track, Negative IFF, IR-only / FMV-only** — anchored by [[references/dow-uap-d56-range-fouler-arabian-sea-august-2020|d56]] and validated across the 2020 NAVCENT cluster. The cluster now spans **radar-visual, IR-only, and FMV-only** modalities, with MQ-9 as the FMV-only platform-of-record. ^[inferred] See [[synthesis/uap-phenomenon-nature]] § 2.4.
- **Sub-class 8 strict dominance.** Across the MQ-9 dow-uap corpus, UAP records cluster at **sub-class 8 strict** (FMV-bare-observation, no kinematics, no morphology, no PID) — see [[concepts/uap-aircraft-engagement]]. The MQ-9 ISR platform appears structurally biased toward brief-observation records rather than engagement-class records.

## Related entities and contexts

- [[entities/432-aew|432 AEW]] — primary deployed Wing operating MQ-9 across the dow-uap corpus.
- [[entities/482-atks|482 ATKS]] — primary squadron operating MQ-9 in the 2020 NAVCENT cluster.
- [[entities/609-caoc|609 CAOC]] — Operations Center approving MQ-9 Misreps for USCENTCOM tasking.
- [[entities/603-aoc|603 AOC]] — Operations Center for the EUCOM MQ-9 mission (d14).
- [[entities/afcent|AFCENT]] — theater MAJCOM.
- [[entities/dow-uap-foia-release]] — FOIA release context.
- [[concepts/range-fouler]] — adjacent mission-record class also dominated by MQ-9.
- [[concepts/uap-aircraft-engagement]] — sub-class taxonomy where the MQ-9 dow-uap subset sits at sub-class 8.

## Open threads

- **Literal `MQ-9` attestation.** No dow-uap source names the airframe by designator. The platform attribution rests on FMV + MTS-B + endurance + 432 AEW deployed-wing-MQ-9 inference. A future ingest of a dow-uap document that explicitly names `MQ-9` would firm the attribution. ^[open]
- **Allied operators.** USAF is the dow-uap corpus's only MQ-9 operator. Whether allied MQ-9 operators (UK, France, Italy, Netherlands, Australia) appear elsewhere in UAP-relevant releases is undetermined. ^[open]
- **2025 forward-deploy survey.** Whether 2025-era dow-uap MQ-9 missions (d8 = Djibouti 2025) carry the same FMV-only sensor profile is an open question for future ingests. ^[open]

## See also

- [[projects/uap/uap]] — project overview.
- [[entities/dow-uap-foia-release]] — release context.
