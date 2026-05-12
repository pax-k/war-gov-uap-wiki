---
title: 482d Attack Squadron (482 ATKS)
category: entities
tags: [usaf, organization, military, uap, isr]
aliases: [482ATKS, 482 ATKS, 482d ATKS, 482nd Attack Squadron, 482d Attack Squadron]
sources: [sources/dow-uap-d60-mission-report-persian-gulf-august-2020.json, sources/dow-uap-d61-mission-report-persian-gulf-august-2020.json, sources/dow-uap-d62-mission-report-strait-of-hormuz-september-2020.json, sources/dow-uap-d63-mission-report-strait-of-hormuz-october-2020.json, sources/dow-uap-d64-mission-report-iran-november-2020.json, sources/dow-uap-d65-mission-report-persian-gulf-july-2020.json]
summary: USAF MQ-9 Reaper attack squadron under 432d Air Expeditionary Wing. POC Unit on the dow-uap 2020 NAVCENT MQ-9 mission-cluster sextuplet (Jul–Nov 2020 Persian Gulf / Strait of Hormuz / Iran AOR).
provenance:
  extracted: 0.4
  inferred: 0.55
  ambiguous: 0.05
base_confidence: 0.55
lifecycle: draft
lifecycle_changed: 2026-05-12
created: 2026-05-12T05:45:00Z
updated: 2026-05-12T05:45:00Z
---

# 482d Attack Squadron (482 ATKS)

The **482d Attack Squadron** — a USAF active-component **MQ-9 Reaper** attack squadron, attested in the dow-uap corpus as the **POC Unit** under [[entities/432-aew|432d Air Expeditionary Wing]] for the **2020 NAVCENT-support mission cluster sextuplet** (Jul → Nov 2020). ^[inferred — squadron type as MQ-9 attack squadron is taxonomically standard for `ATKS` USAF units; the wiki's dow-uap sources state `482ATKS` repeatedly without expansion.]

This page is a **stub hub**. 482 ATKS is the most heavily-cited operational USAF squadron in the dow-uap 2020 corpus, anchoring six consecutive same-unit Misreps that establish a sustained MQ-9 ISR tasking regime over the Persian Gulf and Strait of Hormuz under [[entities/609-caoc|609 CAOC]] command.

## Role in the dow-uap corpus

The 2020 NAVCENT-cluster sextuplet — every full USMTF Misrep in the corpus from 16 Jul through 2 Nov 2020 carries `482ATKS` (or the OCR variant `482 ATKS`) as the POC Unit:

| Misrep | Date | Mission | Reference |
|---|---|---|---|
| 4592219 | 8 Aug 2020 | Arabian Gulf NAVCENT support | [[references/dow-uap-d60-mission-persian-gulf-2020-08-08|d60]] |
| 4685903 | 27 Aug 2020 | Persian Gulf NAVCENT support | [[references/dow-uap-d61-mission-persian-gulf-2020-08-27|d61]] |
| 4782130 | 16 Sep 2020 | Strait of Hormuz NAVCENT support | [[references/dow-uap-d62-mission-strait-of-hormuz-2020-09-16|d62]] |
| 4871281 | 2 Oct 2020 | Strait of Hormuz NAVCENT support | [[references/dow-uap-d63-mission-strait-of-hormuz-2020-10-02|d63]] |
| 5039166 | 2 Nov 2020 | Iran AOR NAVCENT support | [[references/dow-uap-d64-mission-iran-2020-11-02|d64]] |
| earlier | 16 Jul 2020 | Persian Gulf NAVCENT support | [[references/dow-uap-d65-mission-persian-gulf-2020-07-16|d65]] |

Same squadron, same Wing, same Operations Center, same NAVCENT-support tasking, same MQ-9 platform, same ~21-hour mission cycle envelope, ~110-day span across 5 calendar months. ^[extracted across the 6 Misrep POC blocks.]

## Significance for the corpus

- **First sustained same-unit dow-uap ISR cluster.** The 482 ATKS / 432 AEW / 609 CAOC / NAVCENT lane is the corpus's first multi-month repeat-mission UAP-observation cluster from a single attributable squadron. ^[inferred]
- **MQ-9 attribution chain.** All six 482 ATKS missions share the **`Method of Observation: FMV`** signature (Full Motion Video) ^[extracted] consistent with MQ-9 MTS-B / DGS-exploited FMV streams ^[inferred]. The platform = MQ-9 reading is therefore corpus-internal-corroborated at N=6 within the sextuplet, even though no Misrep names `MQ-9` literally. See [[entities/mq-9-reaper|MQ-9 Reaper]].
- **Not OIR.** The 2020 NAVCENT cluster's tasking field is portion-redacted (`1.4a`) but is distinct from the 2022 USCENTCOM Operation INHERENT RESOLVE missions ([[references/dow-uap-d10-mission-middle-east-2022-05-06|d10]]) where the POC Unit is itself redacted (`1.4a`) — the cluster's identity is **482 ATKS NAVCENT-support**, structurally distinct from 432 AEW's OIR lane.

## Related entities and contexts

- [[entities/432-aew|432d Air Expeditionary Wing]] — POC Wing under which 482 ATKS deploys.
- [[entities/609-caoc|609 CAOC]] — USCENTCOM theater Operations Center that approves 482 ATKS Misreps.
- [[entities/afcent|AFCENT]] — theater MAJCOM.
- [[entities/mq-9-reaper|MQ-9 Reaper]] — operating platform across the cluster.
- [[entities/dow-uap-foia-release]] — release context.
- [[concepts/range-fouler]] — adjacent USAF MQ-9 reporting class.

## Open threads

- **Squadron type and garrison.** `ATKS` is the corpus-standard abbreviation for Attack Squadron; squadron type and parent garrison are not stated in the OCR. ^[open]
- **PAROC routing.** All six 482 ATKS missions route QC through `12 AF PAROC` ^[extracted] — the same Intel Data Analysis Technician office that handles other CENTCOM-AOR dow-uap artifacts. The 12 AF PAROC ↔ 482 ATKS routing is a multi-document multi-month stable lane. ^[inferred]
- **2021 gap.** No 2021 482 ATKS Misrep is currently in the dow-uap corpus, leaving a 2020 → 2022 gap in same-squadron observation tempo. ^[open]

## See also

- [[projects/uap/uap]] — project overview.
- [[entities/dow-uap-foia-release]] — release context.
