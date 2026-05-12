---
title: Air Forces Central Command (AFCENT)
category: entities
tags: [usaf, organization, military, uap, isr]
aliases: [AFCENT, USAFCENT, Air Forces Central, Ninth Air Force, US Air Forces Central Command]
sources: [sources/dow-uap-d60-mission-report-persian-gulf-august-2020.json, sources/dow-uap-d10-mission-report-middle-east-may-2022.json]
summary: USAF theater MAJCOM for USCENTCOM AOR. Theater air-component command anchoring the dow-uap 2020 NAVCENT and 2022 OIR active-component mission MAJCOM attribution.
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
- [[entities/dow-uap-foia-release]] — release context.

## Open threads

- **Garrison and component structure.** Shaw AFB SC / Al Udeid AB Qatar forward HQ standard attribution is not stated in dow-uap OCR. ^[open]
- **AFCENT-vs-ACC field discipline.** Across N=2 AFCENT + N=2 ACC Misreps the split holds; need N=4+ to firm the active-component → AFCENT, gaining-major-command → ACC reading. ^[open]
- **AFRICOM overlap.** Whether AFCENT shares any tasking lane with USAFRICOM is open. ^[open]

## See also

- [[projects/uap/uap]] — project overview.
- [[entities/dow-uap-foia-release]] — release context.
