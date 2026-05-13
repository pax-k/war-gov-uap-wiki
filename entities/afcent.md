---
title: Air Forces Central Command (AFCENT)
category: entities
tags: [usaf, organization, military, uap, isr]
aliases: [AFCENT, USAFCENT, Air Forces Central, Ninth Air Force, US Air Forces Central Command]
sources: [sources/dow-uap-d60-mission-report-persian-gulf-august-2020.json, sources/dow-uap-d10-mission-report-middle-east-may-2022.json, sources/dow-uap-d16-mission-report-syria-july-2022.json, sources/dow-uap-d19-mission-report-syria-february-21-2023.json]
summary: USAF theater MAJCOM for USCENTCOM AOR. Theater air-component command anchoring the dow-uap 2020 NAVCENT and 2022 OIR active-component mission MAJCOM attribution. Now corroborated at N=3 OIR within full-Misrep class (d10 OIR-Iraq + d16 OIR-Syria + d19 OIR-Syria F-15E DCA); AFCENT-vs-ACC split holds along theater-MAJCOM-vs-owning-MAJCOM axis. AFSOC (d25/d27/d28/d33/d35) replaces AFCENT as MAJCOM token for the parallel 27 SOW SOF organic ISR/CAS pool under the same USCENTCOM tasking, anchoring a corpus-level MAJCOM tri-class (ACC + AFCENT + AFSOC).
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

# Air Forces Central Command (AFCENT)

**Air Forces Central Command** — the USAF theater air-component MAJCOM for **USCENTCOM** AOR, also known as **USAFCENT** / **Ninth Air Force**. Headquartered at **Shaw AFB South Carolina** with forward HQ at **Al Udeid AB Qatar** ^[inferred — open-source standard background; the wiki's dow-uap sources name only `AFCENT` without garrison expansion.].

This page is a **stub hub**. AFCENT appears in the dow-uap corpus as the **MAJCOM field** of active-component USAF Misreps tasked under [[entities/609-caoc|609 CAOC]] / [[entities/432-aew|432 AEW]] / [[entities/482-atks|482 ATKS]] in the 2020 NAVCENT cluster and the 2022 OIR cluster.

## Role in the dow-uap corpus

- **2020 NAVCENT cluster.** Active-component MAJCOM attribution. Six 482 ATKS / 432 AEW MQ-9 Misreps over Persian Gulf, Strait of Hormuz, Iran AOR (8 Aug → 2 Nov 2020). All route through AFCENT → 609 CAOC. ^[extracted in d60 page 1 MAJCOM field; recurs across the cluster.]
- **2022 OIR cluster — MAJCOM split.** [[references/dow-uap-d10-mission-middle-east-2022-05-06|d10]] (active 432 AEW): `MAJCOM = AFCENT`. [[references/dow-uap-d12-mission-iraq-2022-05-20|d12]] (ANG 163 AW): `MAJCOM = ACC`. The split has an institutional mechanism: **ANG units report through ACC** (Air Combat Command — the gaining major command); **active-component theater units report through AFCENT** (theater MAJCOM). ^[inferred]
- **2022 EUCOM contradiction.** [[references/dow-uap-d14-mission-iraq-2022-05-29|d14]] is active-component 432 AEW but `MAJCOM = ACC` (not AFCENT) — because the d14 mission is **USEUCOM-tasked** (not USCENTCOM-tasked), the AFCENT field doesn't apply. This refines the `ACC = ANG-gaining-command` reading: **ACC is the owning MAJCOM** for both active-component and ANG wings under specific tasking; AFCENT is the **theater-active-component MAJCOM** that supplants ACC only when the wing flies under USCENTCOM theater command. ^[inferred; closed-by-dow-uap-d14]
- **2022 OIR-Syria recurrence.** [[references/dow-uap-d16-mission-syria-2022-07-30|d16]] (89 ATKS / 432 AEW MQ-9, OJMS Jordan) carries `MAJCOM = AFCENT` byte-for-byte d10's posture — firms AFCENT as the **theater MAJCOM for active-component OIR tasking** at N=2 within OIR class (cross-sub-theater Iraq d10 + Syria d16). [[references/dow-uap-d18-mission-iraq-2022-12-01|d18]] (482 ATKS / `20 FW` ^[ambiguous] MQ-9, OIR-Iraq-MB Dec 2022) flips back to `ACC` — refined reading: AFCENT tracks the **active-component-with-432-AEW-deployed-Wing-field** subset; the 482 ATKS / `20 FW` home-Wing rendering at d18 routes through ACC (owning MAJCOM), not AFCENT (theater MAJCOM). ^[inferred]
- **2023 OIR-Syria F-15E firms AFCENT under cross-platform.** [[references/dow-uap-d19-mission-syria-2023-02-21|d19]] (389 EFS / 332 AEW **F-15E DCA**, OJMS Jordan → ESSA Killbox) carries `MAJCOM = AFCENT` ^[extracted] — firms AFCENT at N=3 within OIR class and **at first non-MQ-9 platform** in dow-uap corpus. AFCENT is not platform-locked — covers MQ-9 ISR + F-15E DCA active-component USCENTCOM tasking. ^[inferred]
- **AFSOC-vs-AFCENT replacement.** [[references/dow-uap-d25-mission-greece-2024-01-25|d25]] + [[references/dow-uap-d27-mission-uae-2024-06-06|d27]] + [[references/dow-uap-d28-mission-iraq-2024-09-20|d28]] + [[references/dow-uap-d33-mission-greece-2023-10-26|d33]] + [[references/dow-uap-d35-mission-greece-2023-10-28|d35]] all carry `MAJCOM = AFSOC` ^[extracted] — the AFSOC 27 SOW SOF organic ISR/CAS pool **replaces AFCENT in the MAJCOM field** for AFSOC-routed USCENTCOM tasking, even when the mission is fully within CENTCOM AOR (d27 OMAM UAE, d28 OKAS Kuwait). MAJCOM histogram at d35 ingest: **AFSOC 5 (d25+d27+d28+d33+d35) + ACC 4 (d12+d14+d18+d23) + AFCENT 3 (d10+d16+d19)** — AFSOC is now the largest single MAJCOM in dow-uap full-Misrep class. ^[inferred]

## Significance for the corpus

- **AFCENT is the canonical MAJCOM for dow-uap NAVCENT-support and OIR-support active-component MQ-9 missions.** The MAJCOM field is the corpus's structural anchor for distinguishing **theater-tasked** missions from **gaining-command-tasked** missions. ^[inferred]
- **Pooled-counter routing.** The dow-uap full Misrep ID counter validates within-band across both AFCENT-routed (d60, d10) and ACC-routed (d12) Misreps — confirming the counter pooling sits **above MAJCOM level**, at the Joint-Staff-tranche / MDR-coordinator level. ^[inferred]

## Related entities and contexts

- [[entities/609-caoc|609 CAOC]] — USCENTCOM AOC operationally under AFCENT.
- [[entities/603-aoc|603 AOC]] — USEUCOM AOC operating outside AFCENT.
- [[entities/432-aew|432 AEW]] — active-component USAF Wing whose MAJCOM is AFCENT for USCENTCOM tasking and ACC for non-USCENTCOM tasking.
- [[entities/482-atks|482 ATKS]] — squadron under 432 AEW.
- [[entities/usaf|USAF]] — parent service.
- [[entities/usafe|USAFE]] — USEUCOM-side counterpart MAJCOM.
- [[entities/mq-9-reaper|MQ-9 Reaper]] — operating platform.
- [[entities/afsoc|AFSOC]] — parallel SOF-air MAJCOM that replaces AFCENT in the MAJCOM field for AFSOC-routed USCENTCOM tasking (d25/d27/d28/d33/d35).
- [[entities/27-sow|27th Special Operations Wing]] — AFSOC parent wing for d25/d27/d28/d33/d35 missions.
- [[entities/dow-uap-foia-release]] — release context.

## Open threads

- **Garrison and component structure.** Shaw AFB SC / Al Udeid AB Qatar forward HQ standard attribution is not stated in dow-uap OCR. ^[open]
- **AFCENT-vs-ACC field discipline.** Across N=2 AFCENT + N=2 ACC Misreps the split holds; need N=4+ to firm the active-component → AFCENT, gaining-major-command → ACC reading. ^[open]
- **AFRICOM overlap.** Whether AFCENT shares any tasking lane with USAFRICOM is open. ^[open]

## See also

- [[projects/uap/uap]] — project overview.
- [[entities/dow-uap-foia-release]] — release context.
