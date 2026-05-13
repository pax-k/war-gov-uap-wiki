---
title: MQ-9 Reaper (General Atomics)
category: entities
tags: [usaf, aviation, uap, isr]
aliases: [MQ-9, Reaper, MQ-9 Reaper, General Atomics MQ-9, GA MQ-9]
sources: [sources/dow-uap-d60-mission-report-persian-gulf-august-2020.json, sources/dow-uap-d10-mission-report-middle-east-may-2022.json, sources/dow-uap-d14-mission-report-iraq-may-2022.json, sources/dow-uap-d16-mission-report-syria-july-2022.json, sources/dow-uap-d18-mission-report-iraq-december-2022.json, sources/dow-uap-d23-mission-report-united-arab-emirates-october-2023.json, sources/dow-uap-d25-mission-report-greece-january-2024.json, sources/dow-uap-d27-mission-report-united-arab-emirates-october-2023.json, sources/dow-uap-d33-mission-report-greece-october-2023.json, sources/dow-uap-d35-mission-report-greece-october-2023.json, sources/dow-uap-d42-range-fouler-debrief-japan-2023.json]
summary: General Atomics medium-altitude long-endurance unmanned ISR/strike aircraft. Inferred platform behind almost every full USMTF Misrep in the dow-uap corpus (FMV signature; ~21h mission envelope) and behind the range-fouler debrief corpus. Now at N=15 MQ-9 ISR attestations cross-COCOM + cross-sub-theater + cross-MAJCOM (cluster 6 + d10 + d12 + d16 + d18 + d23 + d25 + d27 + d33 + d35; plus range-fouler d42 + d44); F-15E DCA (d19) and AC-130J ARMED OVERWATCH (d28) are the only non-MQ-9 full-Misrep attestations in the corpus.
provenance:
  extracted: 0.3
  inferred: 0.65
  ambiguous: 0.05
base_confidence: 0.5
lifecycle: draft
lifecycle_changed: 2026-05-12
created: 2026-05-12T05:45:00Z
updated: 2026-05-13T16:00:00Z
---

# MQ-9 Reaper (General Atomics)

The **MQ-9 Reaper** — a General Atomics Aeronautical Systems medium-altitude long-endurance (MALE) **unmanned aerial vehicle**, operated by USAF and allied air forces in **ISR / hunter-killer** roles since ~2007. ^[inferred — open-source standard background; the wiki's dow-uap sources never name `MQ-9` literally.]

This page is a **stub hub**. MQ-9 is the **inferred platform behind every full USMTF Misrep in the dow-uap corpus** based on the Misreps' **`Method of Observation: FMV`** (Full Motion Video) signature, **`MTS-B`** sensor turret references in adjacent dow-uap range-fouler debriefs, and the **~21-hour mission cycle envelope** consistent with MQ-9 endurance (typically 27 hr clean, 14 hr with stores).

## Role in the dow-uap corpus

The MQ-9 attribution is corpus-internal-corroborated at N=15 across the dow-uap full-Misrep set + d42 range-fouler:

- **2020 NAVCENT cluster (N=6)** — [[entities/482-atks|482 ATKS]] / [[entities/432-aew|432 AEW]], 8 Aug → 2 Nov 2020. `MTS-B` Method of Observation, FMV-only sensor profile, no radar track, no IFF, 20h 42min to 22h+ mission cycles. ^[extracted]
- **2022 USCENTCOM OIR-Iraq (N=3)** — [[references/dow-uap-d10-mission-middle-east-2022-05-06|d10]] (432 AEW) + [[references/dow-uap-d12-mission-iraq-2022-05-20|d12]] (163 AW ANG MQ-9) + [[references/dow-uap-d18-mission-iraq-2022-12-01|d18]] (482 ATKS / `20 FW` ^[ambiguous]). FMV signature, ~19-21h mission-cycle envelope. ^[extracted]
- **2022 USEUCOM Eastern Mediterranean (N=1)** — [[references/dow-uap-d14-mission-iraq-2022-05-29|d14]] (50 ATKS / 432 AEW, forward-deployed Sigonella AB Italy). FMV, 20h 30min cycle. ^[extracted]
- **2022 USCENTCOM OIR-Syria (N=1 MQ-9 only; d19 F-15E excluded)** — [[references/dow-uap-d16-mission-syria-2022-07-30|d16]] (89 ATKS / 432 AEW, OJMS Jordan, OP SPECTRE DAGGER, TF CHOSIN). FMV via DGS1, 20h 57min. ^[extracted]
- **2023 USCENTCOM NAVCENT-return (N=1)** — [[references/dow-uap-d23-mission-uae-2023-10-24|d23]] (50 ATKS / 432 AEW, OMAM UAE, OP SPARTAN SHIELD). FMV + first **AN/DAS-1** TGT-pod attestation (vs cluster's AN/DAS-4); FL243 + 20h 43min. ^[extracted]
- **2023-2024 AFSOC MQ-9 ISR (N=4)** — [[references/dow-uap-d33-mission-greece-2023-10-26|d33]] + [[references/dow-uap-d35-mission-greece-2023-10-28|d35]] + [[references/dow-uap-d25-mission-greece-2024-01-25|d25]] (33 SOS / 27 SOW, LGLR Greece) + [[references/dow-uap-d27-mission-uae-2024-06-06|d27]] (3 SOS / 27 SOW, OMAM UAE). All AFSOC-routed organic MQ-9 ISR with FMV signature; AN/DAS-1 (d27) + AN/DAS-4 (d25/d33/d35) TGT pods; novel AIRHANDLER configurations `_GMESH/SANTA FE/SF/BLASPHEMY`. ^[inferred — strongly]
- **Range-fouler debrief MQ-9 attestation (N=1)** — [[references/dow-uap-d42-range-fouler-centcom-2020-08-31|d42]] (482 ATKS / 432 AEW NAVCENT-cluster squadron filing via SPEAR pipeline on 31 Aug 2020, Persian Gulf MGRS 39RWL26). First cross-document-class MQ-9 attestation in dow-uap. ^[inferred]

Per-Misrep platform attribution chain (full-Misrep MQ-9 only): [[references/dow-uap-d60-mission-persian-gulf-2020-08-08|d60]] + [[references/dow-uap-d61-mission-persian-gulf-2020-08-27|d61]] + [[references/dow-uap-d62-mission-strait-of-hormuz-2020-09-16|d62]] + [[references/dow-uap-d63-mission-strait-of-hormuz-2020-10-02|d63]] + [[references/dow-uap-d64-mission-iran-2020-11-02|d64]] + [[references/dow-uap-d65-mission-persian-gulf-2020-07-16|d65]] + [[references/dow-uap-d10-mission-middle-east-2022-05-06|d10]] + [[references/dow-uap-d12-mission-iraq-2022-05-20|d12]] + [[references/dow-uap-d14-mission-iraq-2022-05-29|d14]] + [[references/dow-uap-d16-mission-syria-2022-07-30|d16]] + [[references/dow-uap-d18-mission-iraq-2022-12-01|d18]] + [[references/dow-uap-d23-mission-uae-2023-10-24|d23]] + [[references/dow-uap-d33-mission-greece-2023-10-26|d33]] + [[references/dow-uap-d35-mission-greece-2023-10-28|d35]] + [[references/dow-uap-d25-mission-greece-2024-01-25|d25]] + [[references/dow-uap-d27-mission-uae-2024-06-06|d27]].

The non-MQ-9 dow-uap full-Misreps: [[references/dow-uap-d19-mission-syria-2023-02-21|d19]] (F-15E DCA, 332 AEW / 389 EFS) + [[references/dow-uap-d28-mission-iraq-2024-09-20|d28]] ([[entities/ac-130j-ghostrider|AC-130J Ghostrider]] ARMED OVERWATCH, 27 SOW / 16 SOS).

## Significance for the corpus

- **The corpus's dominant 2020s UAP-observation platform.** MQ-9 is inferred behind 16-of-18 dow-uap full USMTF Misreps (all except d19 F-15E DCA + d28 AC-130J ARMED OVERWATCH) and behind several [[concepts/range-fouler|range-fouler]] debriefs (e.g., d38, d56, d44, d42 — paired with `MTS-B` / `AN/DAS-1` / `AN/DAS-4` / `XSPI` / Lightning Pod / AIRHANDLER sensor packages). ^[inferred]
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
- [[concepts/uap-aircraft-engagement]] — sub-class taxonomy where the MQ-9 dow-uap subset sits at sub-class 8 (cluster + most 2022 OIR) and sub-class 14 (d23/d25/d27/d33/d35 populated UAP-segment-field cohort).
- [[entities/27-sow|27th Special Operations Wing]] + [[entities/33-sos|33 SOS]] + [[entities/3-sos|3 SOS]] — AFSOC parent wing + sister MQ-9 SOSs that fly the parallel AFSOC organic MQ-9 ISR pool (d25/d27/d33/d35) distinct from 432 AEW's ACC/AFCENT-routed pool.
- [[entities/ac-130j-ghostrider|AC-130J Ghostrider]] — d28 non-MQ-9 AFSOC gunship platform; structurally distinct mission cycle and weapons-employment profile.

## Open threads

- **Literal `MQ-9` attestation.** No dow-uap source names the airframe by designator. The platform attribution rests on FMV + MTS-B + endurance + 432 AEW deployed-wing-MQ-9 inference. A future ingest of a dow-uap document that explicitly names `MQ-9` would firm the attribution. ^[open]
- **Allied operators.** USAF is the dow-uap corpus's only MQ-9 operator. Whether allied MQ-9 operators (UK, France, Italy, Netherlands, Australia) appear elsewhere in UAP-relevant releases is undetermined. ^[open]
- **2025 forward-deploy survey.** Whether 2025-era dow-uap MQ-9 missions (d8 = Djibouti 2025) carry the same FMV-only sensor profile is an open question for future ingests. ^[open]

## See also

- [[projects/uap/uap]] — project overview.
- [[entities/dow-uap-foia-release]] — release context.
