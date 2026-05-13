---
title: 609th Combined Air Operations Center (609 CAOC / 609 AOC)
category: entities
tags: [usaf, organization, military, uap, isr]
aliases: [609 CAOC, 609 AOC, 609th AOC, 609th CAOC, 609th Air and Space Operations Center, 609th Combined Air Operations Center]
sources: [sources/dow-uap-d60-mission-report-persian-gulf-august-2020.json, sources/dow-uap-d10-mission-report-middle-east-may-2022.json, sources/dow-uap-d12-mission-report-iraq-may-2022.json, sources/dow-uap-d25-mission-report-greece-january-2024.json, sources/dow-uap-d27-mission-report-united-arab-emirates-october-2023.json, sources/dow-uap-d28-mission-report-east-china-sea-2024.json, sources/dow-uap-d33-mission-report-greece-october-2023.json, sources/dow-uap-d35-mission-report-greece-october-2023.json]
summary: USAF theater Combined Air Operations Center for USCENTCOM, headquartered at Al Udeid AB Qatar. Approving Operations Center for all dow-uap 2020 NAVCENT cluster Misreps + 2022 OIR Misreps + 2023-2024 AFSOC Misreps; pooled-counter routing node for full USMTF Misreps. **609 AOC Det 1 reading partially contradicted at d33 then partially restored at d35** — Det 1 was N=2 cross-role (POC home d25 → QC home d27), absent at d33 (routes via `609 CAOC` main), but **RETURNS at d35 in POC home role** (same 33 SOS / 27 SOW / 56 SOIS chain as d33 but with Det 1 POC OC); Det 1 attestation pattern now at N=3 cross-block (Block F d25+d27 + Block B d35) — Det 1 is NOT block-specific. 609th executing OC recurs across 2022-2024 missions including d28 first AC-130J.
provenance:
  extracted: 0.35
  inferred: 0.6
  ambiguous: 0.05
base_confidence: 0.65
lifecycle: draft
lifecycle_changed: 2026-05-13
created: 2026-05-12T05:45:00Z
updated: 2026-05-13T23:30:00Z
---

## [2026-05-13 update] d35 ingest — Det 1 RETURNS at POC role + Det 1 NOT block-specific (N=3 cross-block: Block F d25+d27 + Block B d35)

[[references/dow-uap-d35-mission-greece-2023-10-28|DoW-UAP-D35]] (28-29 Oct 2023) carries `POC Operations Center: 609 AOC Det 1` ^[extracted] — **Det 1 returns** after d33's absence. The d33-anchored partial-contradiction of the "Det 1 routes EUCOM-launched AFSOC into CENTCOM workflow" reading **partially restores at d35**:

| Mission | POC OC | QC OC | APPROVER OC | Executing OC | Block | Det 1 present? |
|---|---|---|---|---|---|---|
| d25 (25 Jan 2024 LGLR→LGLR) | **609 AOC Det 1** | 609 CAOC | 603 AOC | 603rd | F | YES (POC) |
| d27 (6-7 Jun 2024 OMAM→OMAM) | 609 CAOC | **609 AOC Det 1** | 609 CAOC | 609th | F | YES (QC) |
| d28 (20-21 Sep 2024 OKAS→AAAB) | Other | Other | 609 CAOC | 609th | F | NO |
| d33 (26-27 Oct 2023 LGLR→OJMS) | 609 CAOC | 609 CAOC | 603 AOC | 603rd | B | NO |
| **d35 (28-29 Oct 2023 LGLR→LGLR)** | **609 AOC Det 1** ^[extracted] | 609 CAOC ^[extracted] | 603 AOC ^[extracted] | 603rd ^[extracted] | **B** | **YES (POC)** |

**Det 1 now attests at N=3 cross-block** (Block F d25 + d27 + Block B d35) — **Det 1 is NOT block-specific** ^closed-by-dow-uap-d35 (contradiction class on d33-anchored "Det 1 may be Block-F-routing-pipeline-specific" reading). The d33 absence + d35 presence within the SAME Block B sub-cluster decisively shows Det 1 routing is **per-mission discretionary, not block-allocated** ^[inferred]. Possible Det 1 selection criteria: mission complexity (cross-AOR ferry d33 vs round-trip d35 may differ — though counterintuitive that ferry has FEWER routing nodes), specific tasking source, daily detachment rotation, or workflow load-balancing. Resolution at N≥1 additional Det 1 attestation pattern.

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

## d33 — DET 1 ABSENT despite same 33 SOS/27 SOW/56 SOIS/LGLR chain as d25 — Det 1 hypothesis partially contradicted

[[references/dow-uap-d33-mission-greece-2023-10-26|d33]] (26-27 Oct 2023) is **chronologically the earliest 33 SOS / 27 SOW Misrep in dow-uap** (~91 days before d25), with **identical Originator chain to d25** ^[extracted]: AFSOC MAJCOM + 33 SOS Originator + 27 SOW POC Wing + 56 SOIS QC Unit + LGLR Greece launch + AN/DAS-4 TGT Pod + 603rd executing OC. The d33 + d25 pairing is **the tightest sister-mission pair in dow-uap AFSOC class** — same unit chain, same launch base, ~3 months apart.

**But d33 routes POC + QC OCs through `609 CAOC` (main), NOT `609 AOC Det 1`** ^[extracted]:

| Mission | POC OC | QC OC | APPROVER OC | Executing OC | Block | Originator | Launch base |
|---|---|---|---|---|---|---|---|
| **d33** (26-27 Oct 2023) | **`609 CAOC`** | **`609 CAOC`** | 603 AOC | 603rd | **B** | 33 SOS | LGLR Greece |
| d25 (25 Jan 2024) | **`609 AOC Det 1`** | 609 CAOC | 603 AOC | 603rd | F | 33 SOS | LGLR Greece |
| d27 (6-7 Jun 2024) | 609 CAOC | **`609 AOC Det 1`** | 609 CAOC | 609th | F | 3 SOS | OMAM UAE |
| d28 (20-21 Sep 2024) | Other | Other | 609 CAOC | 609th | F | 16 SOS / SOTU 016 | OKAS Kuwait |

**This is a partial contradiction of the d25/d27-anchored "Det 1 routes EUCOM-launched AFSOC into CENTCOM workflow" reading** ^closed-by-dow-uap-d33 (contradiction class). The prior reading was firming at N=2 cross-role (POC home d25 EUCOM-launched + QC home d27 CENTCOM-launched). d33 falsifies it: **same 33 SOS / 27 SOW / 56 SOIS chain + same LGLR launch base + same EUCOM-AOR launch + same CENTCOM-COCOM-tasking + same bidirectional cross-COCOM 3-OC topology as d25 — but d33 routes through `609 CAOC` main, not Det 1** ^[inferred].

**Most parsimonious refinements at d33** ^[inferred]:
- Det 1 may be **Block-F-routing-pipeline-specific** (present at d25 + d27 — both Block F; absent at d33 — Block B; absent at d28 — Block F but `Other` POC/QC OC tokens)
- Det 1 may be **2024-era-specific** (present at d25 + d27 — both 2024-era; absent at d33 — 2023-era)
- Det 1 may have been **created or activated between d33 (Oct 2023) and d25 (Jan 2024)** — first attestation in dow-uap full-Misrep class at d25, NOT at d33; possibly indicates **organizational reform within 609 AOC between Oct 2023 and Jan 2024** ^[inferred]

Resolution requires N≥4 AFSOC Misrep across Block-B-vs-Block-F + 2023-vs-2024 axes. Until then, the "Det 1 routes EUCOM-launched AFSOC into CENTCOM workflow" reading drops from ^closed (firming) to ^[ambiguous] at corpus level.

## d28 — first AC-130J gunship Misrep under 609 CAOC + 609th executing

[[references/dow-uap-d28-mission-iraq-2024-09-20|d28]] (20-21 Sep 2024) anchors the **first non-MQ-9-non-F-15E platform** in dow-uap class under 609 CAOC routing — AFSOC 27 SOW / 16 SOS [[entities/ac-130j-ghostrider|AC-130J Ghostrider]] ^[inferred — strongly] launched from OKAS Kuwait ^[inferred] for USCENTCOM-tasked Op INHERENT RESOLVE ARMED OVERWATCH into AAAB ROZ RAINDROP Iraq UTM 38S KC.

**d28 cross-OC chain** ^[extracted]:
- **POC OC** = **`Other`** (not labeled `609 CAOC` or other named OC; AFSOC-internal OC token ^[inferred])
- **QC OC** = **`Other`** (same)
- **APPROVER OC** = **`609 CAOC`** (recurs at corpus-level)
- **Executing OC** = **`609th`** (recurs across 2022 OIR + d27 + d28)

**Significance for 609 CAOC**: d28 firms 609 CAOC's role as the **invariant APPROVER + executing OC across MAJCOM (ACC + AFCENT + AFSOC) + platform (MQ-9 + F-15E + AC-130J) + Mission Type (ISR + ARMED RECCE + DCA + ARMED OVERWATCH) within CENTCOM AOR** ^closed-by-dow-uap-d28 (firming class). The d28 POC/QC OC token `Other` is structurally distinct from prior 609 CAOC patterns ^[inferred] — first attestation of AFSOC-internal OC routing on the POC/QC side while 609 CAOC retains APPROVER + executing roles. 609 AOC Det 1 absent at d28 (only 609 CAOC at APPROVER + 609th executing) — Det 1's POC/QC role at d25/d27 is **AFSOC-launched-mission-specific**, not all-AFSOC-mission-specific ^[inferred].

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
- [[entities/ac-130j-ghostrider|AC-130J Ghostrider]] — d28 airframe ^[inferred — strongly]; first non-MQ-9-non-F-15E platform under 609 CAOC routing.
- [[entities/dow-uap-foia-release]] — release context.
- [[entities/27-sow|27th Special Operations Wing]] — d25 + d27 + d28 POC Wing under AFSOC; cross-MAJCOM routing through 609 AOC Det 1 at N=2 + direct 609 CAOC APPROVER at N=3.
- [[entities/33-sos|33rd Special Operations Squadron]] — d25 Originator under AFSOC.
- [[entities/3-sos|3rd Special Operations Squadron]] — d27 Originator under AFSOC.
- [[entities/16-sos|16th Special Operations Squadron]] — d28 POC unit + plausibly Originator under AFSOC (AC-130J SOS ^[inferred — strongly]).
- [[entities/afsoc|Air Force Special Operations Command]] — d25 + d27 + d28 MAJCOM (parallel to ACC/AFCENT 432 AEW MAJCOM); recurs at N=3.
- [[references/dow-uap-d25-mission-greece-2024-01-25|DoW-UAP-D25]] — first 609 AOC Det 1 attestation (POC home).
- [[references/dow-uap-d27-mission-uae-2024-06-06|DoW-UAP-D27]] — second 609 AOC Det 1 attestation (QC home); firms CENTCOM-forward AFSOC-liaison detachment reading (later partially contradicted at d33).
- [[references/dow-uap-d28-mission-iraq-2024-09-20|DoW-UAP-D28]] — first AC-130J / first gunship / first ARMED OVERWATCH / first kinetic-weapons-employment in dow-uap under 609 CAOC APPROVER + 609th executing; first `Other`-OC POC/QC token (AFSOC-internal OC routing).
- [[references/dow-uap-d33-mission-greece-2023-10-26|DoW-UAP-D33]] — **Det 1 hypothesis partially contradicted** — same 33 SOS / 27 SOW / 56 SOIS / LGLR chain as d25 but POC + QC routed through 609 CAOC main, NOT Det 1; Det 1 may be Block-F-routing-pipeline-specific or 2024-era-specific.

## Open threads

- **Al Udeid AB anchor.** The Al Udeid AB Qatar garrison attribution is open-source standard but not literally stated in dow-uap OCR. ^[open]
- **AOC vs CAOC.** Whether `609 AOC` and `609 CAOC` denote distinct sub-organs (AOC = parent operations center; CAOC = combined/coalition tier) or are interchangeable OCR variants is undetermined at N=2 splits within d12. ^[open]
- **2021 gap.** No 2021 609 CAOC dow-uap Misrep is currently in the corpus. ^[open]
- ~~**609 AOC Det 1 detachment status.**~~ ^closed-by-dow-uap-d27 (firming class on d25-anchored Det 1 status thread) — Det 1 firms at N=2 cross-role as the CENTCOM-forward AFSOC-liaison detachment; not d25-specific. Det 1 role within mission tracks AFSOC squadron's launch-base-AOR (EUCOM-launched → Det 1 POC home; CENTCOM-launched → Det 1 QC home). **REOPENED at d33** ^[ambiguous] — d33 (same 33 SOS / 27 SOW / 56 SOIS chain + same LGLR launch + same EUCOM-launched-CENTCOM-tasked as d25) routes POC + QC through 609 CAOC main, NOT Det 1. The Det 1 reading is partially contradicted: Det 1 may be Block-F-routing-pipeline-specific or 2024-era-specific rather than EUCOM-launched-AFSOC-launch-base-specific. Resolution at N≥4 AFSOC Misrep across Block-B-vs-Block-F + 2023-vs-2024 axes. ^[open]

## See also

- [[projects/uap/uap]] — project overview.
- [[entities/dow-uap-foia-release]] — release context.
