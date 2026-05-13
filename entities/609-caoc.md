---
title: 609th Combined Air Operations Center (609 CAOC / 609 AOC)
category: entities
tags: [usaf, organization, military, uap, isr]
aliases: [609 CAOC, 609 AOC, 609th AOC, 609th CAOC, 609th Air and Space Operations Center, 609th Combined Air Operations Center]
sources: [sources/dow-uap-d60-mission-report-persian-gulf-august-2020.json, sources/dow-uap-d10-mission-report-middle-east-may-2022.json, sources/dow-uap-d12-mission-report-iraq-may-2022.json, sources/dow-uap-d25-mission-report-greece-january-2024.json]
summary: USAF theater Combined Air Operations Center for USCENTCOM, headquartered at Al Udeid AB Qatar. Approving Operations Center for all dow-uap 2020 NAVCENT cluster Misreps and 2022 OIR Misreps; pooled-counter routing node for full USMTF Misreps. d25 anchors first 609 AOC Det 1 detachment attestation (cross-MAJCOM AFSOC POC home).
provenance:
  extracted: 0.35
  inferred: 0.6
  ambiguous: 0.05
base_confidence: 0.55
lifecycle: draft
lifecycle_changed: 2026-05-12
created: 2026-05-12T05:45:00Z
updated: 2026-05-13T12:00:00Z
---

# 609th Combined Air Operations Center (609 CAOC / 609 AOC)

The **609th Combined Air Operations Center** — the USAF / USCENTCOM theater **Combined Air Operations Center** at **Al Udeid AB, Qatar** ^[inferred — open-source standard attribution; the wiki's dow-uap sources do not state the AB by name.]. The AOC is the centralized command-and-control node for air operations across the **USCENTCOM AOR**, including the Persian Gulf, Strait of Hormuz, Gulf of Oman, Levant, Iraq, and Syria theaters.

This page is a **stub hub**. 609 CAOC anchors the dow-uap mission-report APPROVER chain for the entire 2020 NAVCENT cluster and the 2022 USCENTCOM Operation INHERENT RESOLVE cluster. The variant string `609 AOC` and `609 CAOC` both appear in dow-uap OCR — the same institution, with `AOC` and `CAOC` used interchangeably across documents.

## Role in the dow-uap corpus

The 609 CAOC surfaces as **Operations Center** and/or **APPROVER Unit** on every full USMTF Misrep in the USCENTCOM AOR:

- **2020 NAVCENT cluster (N=6)** — [[references/dow-uap-d60-mission-persian-gulf-2020-08-08|d60]] through [[references/dow-uap-d64-mission-iran-2020-11-02|d64]] all carry `609 CAOC` or `609 AOC` as APPROVER Unit. ^[extracted]
- **2022 OIR cluster (N=2)** — [[references/dow-uap-d10-mission-middle-east-2022-05-06|d10]] + [[references/dow-uap-d12-mission-iraq-2022-05-20|d12]] share `609 CAOC` Operations Center. d12 splits APPROVER between `609 AOC` and `609 CAOC` within the same Misrep, supporting the **AOC-vs-CAOC organizational nesting** hypothesis (AOC = parent, CAOC = component) at the 609 routing chain. ^[inferred]
- **Multi-component MQ-9 pool.** Under 609 CAOC's OIR umbrella, both active-component ([[entities/432-aew|432 AEW]] / 482ATKS) and ANG units (163 AW / 196 ATKS) fly concurrent missions. ^[inferred]

## d25 — 609 AOC Det 1 attestation (25 Jan 2024)

[[references/dow-uap-d25-mission-greece-2024-01-25|d25]] (25 Jan 2024) introduces the **first `609 AOC Det 1` detachment attestation** in dow-uap corpus ^[extracted]:

- **POC** = A1C, 56 SOIS, 27 SOW, **`609 AOC Det 1`** (POC home OC at d25)
- **QC** = SrA, 27 SOW, **`609 CAOC`** (main 609 CAOC, distinct from Det 1)

**The Det 1 designator is structurally distinct from `609 CAOC` or `609 AOC` main**: a `Det 1` typically denotes a forward-deployed detachment of the parent unit attached to a specific tasking, supported unit, or AOR ^[inferred]. d25's AFSOC mission profile + USCENTCOM tasking + USEUCOM-AOR launch base suggests `609 AOC Det 1` is plausibly a **CENTCOM-forward AFSOC-liaison detachment** of 609 CAOC ^[inferred] — supporting cross-MAJCOM tasking that routes AFSOC organic ISR into USCENTCOM AOR theater requirements.

Mission summary: AFSOC 27 SOW / 33 SOS MQ-9 ^[inferred] launched from Larissa AB (LGLR) Greece for USCENTCOM-tasked ISR; bidirectional cross-COCOM 3-OC chain (609 AOC Det 1 POC home → 609 CAOC QC → 603 AOC APPROVER → 603rd executing); 1X UAP at 250509Z UTM 35S Eastern Aegean.

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
- [[entities/27-sow|27th Special Operations Wing]] — d25 POC Wing under AFSOC; cross-MAJCOM routing through 609 AOC Det 1.
- [[entities/33-sos|33rd Special Operations Squadron]] — d25 Originator under AFSOC.
- [[entities/afsoc|Air Force Special Operations Command]] — d25 MAJCOM (parallel to ACC/AFCENT 432 AEW MAJCOM).
- [[references/dow-uap-d25-mission-greece-2024-01-25|DoW-UAP-D25]] — first 609 AOC Det 1 attestation.

## Open threads

- **Al Udeid AB anchor.** The Al Udeid AB Qatar garrison attribution is open-source standard but not literally stated in dow-uap OCR. ^[open]
- **AOC vs CAOC.** Whether `609 AOC` and `609 CAOC` denote distinct sub-organs (AOC = parent operations center; CAOC = combined/coalition tier) or are interchangeable OCR variants is undetermined at N=2 splits within d12. ^[open]
- **2021 gap.** No 2021 609 CAOC dow-uap Misrep is currently in the corpus. ^[open]

## See also

- [[projects/uap/uap]] — project overview.
- [[entities/dow-uap-foia-release]] — release context.
