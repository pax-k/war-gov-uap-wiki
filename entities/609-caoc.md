---
title: 609th Combined Air Operations Center (609 CAOC / 609 AOC)
category: entities
tags: [usaf, organization, military, uap, isr]
aliases: [609 CAOC, 609 AOC, 609th AOC, 609th CAOC, 609th Air and Space Operations Center, 609th Combined Air Operations Center]
sources: [sources/dow-uap-d60-mission-report-persian-gulf-august-2020.json, sources/dow-uap-d10-mission-report-middle-east-may-2022.json, sources/dow-uap-d12-mission-report-iraq-may-2022.json, sources/dow-uap-d25-mission-report-greece-january-2024.json, sources/dow-uap-d27-mission-report-united-arab-emirates-october-2023.json]
summary: USAF theater Combined Air Operations Center for USCENTCOM, headquartered at Al Udeid AB Qatar. Approving Operations Center for all dow-uap 2020 NAVCENT cluster Misreps and 2022 OIR Misreps; pooled-counter routing node for full USMTF Misreps. 609 AOC Det 1 recurs at N=2 cross-role (POC home d25 → QC home d27) — firms CENTCOM-forward AFSOC-liaison detachment reading.
provenance:
  extracted: 0.35
  inferred: 0.6
  ambiguous: 0.05
base_confidence: 0.60
lifecycle: draft
lifecycle_changed: 2026-05-13
created: 2026-05-12T05:45:00Z
updated: 2026-05-13T18:00:00Z
---

# 609th Combined Air Operations Center (609 CAOC / 609 AOC)

The **609th Combined Air Operations Center** — the USAF / USCENTCOM theater **Combined Air Operations Center** at **Al Udeid AB, Qatar** ^[inferred — open-source standard attribution; the wiki's dow-uap sources do not state the AB by name.]. The AOC is the centralized command-and-control node for air operations across the **USCENTCOM AOR**, including the Persian Gulf, Strait of Hormuz, Gulf of Oman, Levant, Iraq, and Syria theaters.

This page is a **stub hub**. 609 CAOC anchors the dow-uap mission-report APPROVER chain for the entire 2020 NAVCENT cluster and the 2022 USCENTCOM Operation INHERENT RESOLVE cluster. The variant string `609 AOC` and `609 CAOC` both appear in dow-uap OCR — the same institution, with `AOC` and `CAOC` used interchangeably across documents.

## Role in the dow-uap corpus

The 609 CAOC surfaces as **Operations Center** and/or **APPROVER Unit** on every full USMTF Misrep in the USCENTCOM AOR:

- **2020 NAVCENT cluster (N=6)** — [[references/dow-uap-d60-mission-persian-gulf-2020-08-08|d60]] through [[references/dow-uap-d64-mission-iran-2020-11-02|d64]] all carry `609 CAOC` or `609 AOC` as APPROVER Unit. ^[extracted]
- **2022 OIR cluster (N=2)** — [[references/dow-uap-d10-mission-middle-east-2022-05-06|d10]] + [[references/dow-uap-d12-mission-iraq-2022-05-20|d12]] share `609 CAOC` Operations Center. d12 splits APPROVER between `609 AOC` and `609 CAOC` within the same Misrep, supporting the **AOC-vs-CAOC organizational nesting** hypothesis (AOC = parent, CAOC = component) at the 609 routing chain. ^[inferred]
- **Multi-component MQ-9 pool.** Under 609 CAOC's OIR umbrella, both active-component ([[entities/432-aew|432 AEW]] / 482ATKS) and ANG units (163 AW / 196 ATKS) fly concurrent missions. ^[inferred]

## 609 AOC Det 1 — recurs at N=2 cross-role (d25 POC home + d27 QC home)

[[references/dow-uap-d25-mission-greece-2024-01-25|d25]] (25 Jan 2024) introduced the **first `609 AOC Det 1` detachment attestation** in dow-uap corpus; [[references/dow-uap-d27-mission-uae-2024-06-06|d27]] (6-7 Jun 2024) attests Det 1 at N=2 in an INVERSE position ^closed-by-dow-uap-d27 (firming class):

| Mission | POC home OC | QC OC | APPROVER OC | Executing OC | Cross-OC topology |
|---|---|---|---|---|---|
| d25 (Greece LGLR) | **609 AOC Det 1** | 609 CAOC | 603 AOC (EUCOM) | 603rd (EUCOM) | bidirectional cross-COCOM 3-OC chain |
| d27 (UAE OMAM) | 609 CAOC | **609 AOC Det 1** | 609 CAOC | 609th | single-COCOM CENTCOM 4-role chain |

**The Det 1 designator is structurally distinct from `609 CAOC` or `609 AOC` main**: a `Det 1` typically denotes a forward-deployed detachment of the parent unit attached to a specific tasking, supported unit, or AOR ^[inferred]. d25 + d27 anchor `609 AOC Det 1` as the **CENTCOM-forward AFSOC-liaison detachment** of 609 CAOC at N=2 cross-role ^closed-by-dow-uap-d27 (firming class) — Det 1 routes AFSOC organic ISR into USCENTCOM-AOR Misrep workflow regardless of which role (POC home, QC, etc.) the detachment fills within a given mission.

**Cross-role refinement**: Det 1's role within a mission tracks **the AFSOC squadron's launch-base-AOR** ^[inferred]:
- d25 launched from EUCOM AOR (LGLR Greece) → Det 1 = POC home (intake/processing handoff to CENTCOM-tasking workflow)
- d27 launched from CENTCOM AOR (OMAM UAE) → Det 1 = QC home (mid-pipeline review without intake gate, since launch is within same COCOM)

The flexibility supports Det 1 as a **dedicated AFSOC-to-CENTCOM intelligence-routing cell** rather than a fixed-role detachment ^[inferred]. Resolution at N≥3 would firm or refine.

### d25 mission summary

AFSOC 27 SOW / 33 SOS MQ-9 ^[inferred] launched from Larissa AB (LGLR) Greece for USCENTCOM-tasked ISR; bidirectional cross-COCOM 3-OC chain (609 AOC Det 1 POC home → 609 CAOC QC → 603 AOC APPROVER → 603rd executing); 1X UAP at 250509Z UTM 35S Eastern Aegean.

### d27 mission summary

AFSOC 27 SOW / 3 SOS MQ-9 ^[inferred] launched from Al Dhafra AB (OMAM) UAE for USCENTCOM-tasked ISR under Op ENDURING SENTINEL; single-COCOM CENTCOM 4-role chain (609 CAOC POC + 609 AOC Det 1 QC + 379 AEW APPROVER at 609 CAOC + 609th executing); 10h 13min WX-RTB-truncated cycle; 1X UAP at 070457Z UTM 40R Persian Gulf UAE coast (glowing hot sphere + pole/bar appendage).

## Contradiction-axis: 609 (USCENTCOM) vs 603 (USEUCOM)

[[references/dow-uap-d14-mission-iraq-2022-05-29|d14]] is the dow-uap corpus's first attestation of a **non-609 AOC** dow-uap Misrep: its Operations Center is **[[entities/603-aoc|603 AOC]]** (Ramstein-based, USAFE/AFRICOM) with COCOM `USEUCOM`, not `USCENTCOM`. The d10-anchored "OIR May-2022 cluster validation at N≥3 (d12 / d14 / d16 queued)" open thread was **CONTRADICTED** by d14 — d14 is NOT an OIR cluster member but rather a **distinct EUCOM Eastern Mediterranean cluster at N=1**. ^[extracted; closed-by-dow-uap-d14]

The d14 contradiction is decisive: **OIR cluster remains at N=2 (d10 + d12)** and the 432 AEW POC Wing operates **cross-COCOM** (USCENTCOM via 609 CAOC + USEUCOM via 603 AOC).

## Significance for the corpus

- **Approving authority for USCENTCOM dow-uap UAP observations.** 609 CAOC is the institutional node where dow-uap UAP sightings receive intra-Air-Force approval before downstream MDR coordination. ^[inferred]
- **Pooled-counter node.** The dow-uap full Misrep ID counter (d60 4592219 → d10 7473483 → d12 7528881) advances at a within-band ~3,900–5,200 IDs/day across 22 months for missions routed through 609 CAOC — supports the reading that the counter is **pooled at 609 AOC / AFCENT level (or higher)**, NOT 432-AEW-rooted. d14's 603 AOC routing also returns a within-band counter increment (7561279, +32,398 from d12 over 8-9 days = ~4,049/day) — refining the pooling-level upward to **Joint-Staff-tranche / Harrison-MDR-coordinator level**, not 609-rooted. ^[inferred]
- **Two-letter MAJCOM split.** Active-component 432 AEW reports through MAJCOM = `AFCENT` (theater); ANG 163 AW reports through MAJCOM = `ACC` (Air Combat Command — the gaining major command for ANG units). The 609 CAOC routes both. ^[inferred from d10 vs d12 MAJCOM fields.]

## Related entities and contexts

- [[entities/432-aew|432 AEW]] — most-active POC Wing under 609 CAOC.
- [[entities/482-atks|482 ATKS]] — 2020 NAVCENT cluster POC Unit.
- [[entities/603-aoc|603 AOC]] — sister AOC for USEUCOM (the d14 contradiction axis).
- [[entities/afcent|AFCENT]] — theater MAJCOM under whose remit 609 CAOC operates.
- [[entities/usaf|USAF]] — parent service.
- [[entities/mq-9-reaper|MQ-9 Reaper]] — primary airframe operated under 609 CAOC tasking in dow-uap.
- [[entities/dow-uap-foia-release]] — release context.
- [[entities/27-sow|27th Special Operations Wing]] — d25 + d27 POC Wing under AFSOC; cross-MAJCOM routing through 609 AOC Det 1 at N=2 cross-role.
- [[entities/33-sos|33rd Special Operations Squadron]] — d25 Originator under AFSOC.
- [[entities/3-sos|3rd Special Operations Squadron]] — d27 Originator under AFSOC; sister to 33 SOS within 27 SOW parent.
- [[entities/afsoc|Air Force Special Operations Command]] — d25 + d27 MAJCOM (parallel to ACC/AFCENT 432 AEW MAJCOM); recurs at N=2.
- [[references/dow-uap-d25-mission-greece-2024-01-25|DoW-UAP-D25]] — first 609 AOC Det 1 attestation (POC home).
- [[references/dow-uap-d27-mission-uae-2024-06-06|DoW-UAP-D27]] — second 609 AOC Det 1 attestation (QC home); firms CENTCOM-forward AFSOC-liaison detachment reading.

## Open threads

- **Al Udeid AB anchor.** The Al Udeid AB Qatar garrison attribution is open-source standard but not literally stated in dow-uap OCR. ^[open]
- **AOC vs CAOC.** Whether `609 AOC` and `609 CAOC` denote distinct sub-organs (AOC = parent operations center; CAOC = combined/coalition tier) or are interchangeable OCR variants is undetermined at N=2 splits within d12. ^[open]
- **2021 gap.** No 2021 609 CAOC dow-uap Misrep is currently in the corpus. ^[open]
- ~~**609 AOC Det 1 detachment status.**~~ ^closed-by-dow-uap-d27 (firming class on d25-anchored Det 1 status thread) — Det 1 firms at N=2 cross-role as the CENTCOM-forward AFSOC-liaison detachment; not d25-specific. Det 1 role within mission tracks AFSOC squadron's launch-base-AOR (EUCOM-launched → Det 1 POC home; CENTCOM-launched → Det 1 QC home).

## See also

- [[projects/uap/uap]] — project overview.
- [[entities/dow-uap-foia-release]] — release context.
