---
title: 27th Special Operations Wing (27 SOW)
category: entities
tags: [usaf, organization, military, uap, isr]
aliases: [27 SOW, 27th SOW, 27 Special Operations Wing, 27th Special Operations Wing]
sources: [sources/dow-uap-d25-mission-report-greece-january-2024.json, sources/dow-uap-d27-mission-report-united-arab-emirates-october-2023.json]
summary: USAF / AFSOC Special Operations Wing at Cannon AFB NM ^[inferred]. Parent wing for 33 SOS (d25 MQ-9 Originator), 3 SOS (d27 MQ-9 Originator ^[inferred]), and 56 SOIS (Special Operations Intelligence Squadron — POC d25 + QC d27). 27 SOW recurs at N=2 in dow-uap full-Misrep corpus (d25 LGLR Greece + d27 OMAM UAE) — first AFSOC MQ-9 ISR cross-squadron N=2 within dow-uap.
provenance:
  extracted: 0.35
  inferred: 0.60
  ambiguous: 0.05
base_confidence: 0.62
lifecycle: draft
lifecycle_changed: 2026-05-13
created: 2026-05-13T12:00:00Z
updated: 2026-05-13T18:00:00Z
---

# 27th Special Operations Wing (27 SOW)

The **27th Special Operations Wing** — a USAF wing under [[entities/afsoc|AFSOC]], garrisoned at **Cannon AFB, New Mexico** ^[inferred — open-source standard attribution; not literally stated in dow-uap OCR]. The 27 SOW is one of the two principal AFSOC operational wings (alongside 1st Special Operations Wing at Hurlburt Field FL ^[inferred]), with subordinate squadrons spanning MQ-9 Reaper, AC-130, MC-130, U-28A, and intelligence functions ^[inferred].

This page is a **stub hub**. 27 SOW surfaces in the dow-uap corpus as the **POC Wing of d25** — the first AFSOC artifact and the first non-432-AEW POC Wing in the MQ-9 ISR mission-record subset of the corpus.

## Role in the dow-uap corpus

[[references/dow-uap-d25-mission-greece-2024-01-25|d25]] (25 Jan 2024) and [[references/dow-uap-d27-mission-uae-2024-06-06|d27]] (6-7 Jun 2024) carry the 27 SOW POC Wing attestation at N=2:

**d25 — Greece LGLR (25 Jan 2024):**
- **POC** = A1C, 56 SOIS, 27 SOW, 609 AOC Det 1 ^[extracted]
- **QC** = SrA, (unit unavailable), 27 SOW, 609 CAOC ^[extracted]
- **Originator** = 33 SOS ^[extracted]
- 20h 40min mission cycle, 1X UAP at UTM 35S (Eastern Aegean), diamond+probe morphology, SWIR-only

**d27 — UAE OMAM (6-7 Jun 2024):**
- **POC** = SrA, (unit unavailable), 27 SOW, 609 CAOC ^[extracted]
- **QC** = A1C, **56 SOIS**, 27 SOW, **609 AOC Det 1** ^[extracted] (cross-role: POC d25 → QC d27 — 56 SOIS recurs across roles)
- **Originator** = **3 SOS** ^[extracted] (first 3 SOS attestation; sister AFSOC SOS to d25's 33 SOS)
- **APPROVER** = SrA, (unit unavailable), **379 AEW** (Al-Udeid forward), 609 CAOC
- 10h 13min WX-RTB-truncated cycle, 1X UAP at UTM 40R (UAE Persian Gulf coast), glowing-hot sphere + vertical pole/bar appendage

## Significance for the corpus

- **27 SOW recurs at N=2 cross-mission + cross-squadron + cross-launch-base** ^[inferred]. d25 (33 SOS LGLR Greece) + d27 (3 SOS OMAM UAE) firms AFSOC-MQ-9-organic ISR cross-squadron within 27 SOW parent wing — first such cross-squadron pattern in dow-uap full-Misrep class. ^[inferred]
- **First non-432-AEW POC Wing in dow-uap MQ-9 ISR mission-record subset** ^[inferred]. d10 through d23 carried 432 AEW POC Wing at 12-of-12 within MQ-9 ISR (d19's 332 AEW was F-15E DCA, distinct platform). d25 + d27 introduce 27 SOW as **second non-432-AEW POC Wing at N=2** + **first MQ-9-platform non-432-AEW POC Wing at N=2**. ^[inferred] 432 AEW MQ-9 ISR share refines to **12-of-14 = ~86%** within MQ-9 ISR subset at d27 ingest (was ~92% at d25 ingest).
- **AFSOC organic ISR pool parallel to ACC/AFCENT-routed 432 AEW firms at N=2.** AFSOC's separate-MAJCOM + SOW-vs-AEW wing-class + SOS-vs-ATKS squadron designation system anchors a structurally distinct MQ-9 community within the dow-uap corpus ^[inferred]. The 27 SOW operates from **two distinct AOR launch bases within 5 months** — LGLR Greece (EUCOM AOR, cross-AOR CENTCOM tasking, d25) + OMAM UAE (CENTCOM AOR, same-AOR CENTCOM tasking, d27). ^[inferred]
- **Cross-OC topology varies within 27 SOW.** d25 = bidirectional cross-COCOM 3-OC chain (609 AOC Det 1 POC home → 609 CAOC QC → 603 AOC APPROVER → 603rd executing); d27 = single-COCOM CENTCOM 4-role chain (609 CAOC POC + 609 AOC Det 1 QC + 379 AEW APPROVER at 609 CAOC + 609th executing). **27 SOW does NOT lock into single cross-OC topology** ^[inferred] — varies with launch-base-AOR + tasking-COCOM.
- **POC unit and Originator unit diverge within 27 SOW at both attestations.** d25 has 56 SOIS as POC Unit + 33 SOS as Originator; d27 has POC Unit unavailable / 56 SOIS as QC + 3 SOS as Originator — **two different 27 SOW squadrons in POC/QC + Originator role chains at both d25 and d27**. ^[inferred] Cross-squadron intra-Wing role assignment is **systematic at N=2 in dow-uap full-Misrep class** ^[inferred].

## Related entities and contexts

- [[entities/33-sos|33rd Special Operations Squadron]] — d25 Originator; MQ-9 Reaper SOS ^[inferred]. Sister AFSOC SOS to d27's 3 SOS within 27 SOW parent.
- [[entities/afsoc|Air Force Special Operations Command (AFSOC)]] — parent MAJCOM; recurs at N=2 (d25 + d27).
- [[entities/432-aew|432d Air Expeditionary Wing (432 AEW)]] — corpus's prior-dominant MQ-9 ISR POC Wing; d25 + d27 firm broken monopoly at N=2.
- [[entities/603-aoc|603 AOC]] — d25 APPROVER + executing OC; absent at d27 (single-COCOM CENTCOM).
- [[entities/609-caoc|609 CAOC / 609 AOC]] — d27 POC home + APPROVER + executing OC; 609 AOC Det 1 recurs across roles (POC home d25 + QC home d27).
- [[references/dow-uap-d25-mission-greece-2024-01-25|DoW-UAP-D25]] — first 27 SOW attestation.
- [[references/dow-uap-d27-mission-uae-2024-06-06|DoW-UAP-D27]] — second 27 SOW attestation; first AFSOC mission from CENTCOM-AOR launch base (OMAM).
- [[entities/dow-uap-foia-release]] — release context.
- [[entities/mq-9-reaper|MQ-9 Reaper]] — airframe at d25 + d27 ^[inferred].

## Open threads

- **Cannon AFB garrison anchor.** Open-source standard; not literally stated in dow-uap OCR. ^[open]
- **56 SOIS attribution.** Page-25 POC Unit `56 SOIS` is plausibly **56th Special Operations Intelligence Squadron** but could also be **56 SOIS = 56 SOS-Intel detachment** or similar. ^[ambiguous] Recurs at N=2 cross-role (POC d25 + QC d27).
- ~~**27 SOW MQ-9 ISR cluster at N≥2 in dow-uap.**~~ ^closed-by-dow-uap-d27 — 27 SOW recurs at N=2 cross-squadron (33 SOS d25 + 3 SOS d27) + cross-launch-base (LGLR + OMAM); parallel ISR posture firms.
- **27 SOW at N≥3 — sustained AFSOC ISR lane.** Whether 27 SOW continues to anchor AFSOC ISR-strike in dow-uap beyond N=2 (third attestation or another sister Wing-class SOW) is open. ^[open]

## See also

- [[projects/uap/uap]] — project overview.
- [[entities/dow-uap-foia-release]] — release context.
