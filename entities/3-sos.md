---
title: 3rd Special Operations Squadron (3 SOS)
category: entities
tags: [usaf, organization, military, uap, isr]
aliases: [3 SOS, 3rd SOS, 3d Special Operations Squadron, 3rd Special Operations Squadron]
sources: [sources/dow-uap-d27-mission-report-united-arab-emirates-october-2023.json]
summary: USAF / AFSOC Special Operations Squadron at Cannon AFB NM ^[inferred] under 27 SOW parent. MQ-9 Reaper ^[inferred] — supported by AN/DAS-1 TGT Pod + 10h+ mission cycle + AFSOC SOS standard. First 3 SOS attestation in dow-uap full-Misrep corpus (d27 Originator); sister AFSOC SOS to 33 SOS (d25 Originator).
provenance:
  extracted: 0.25
  inferred: 0.70
  ambiguous: 0.05
base_confidence: 0.45
lifecycle: draft
lifecycle_changed: 2026-05-13
created: 2026-05-13T18:00:00Z
updated: 2026-05-13T18:00:00Z
---

# 3rd Special Operations Squadron (3 SOS)

The **3rd Special Operations Squadron** — a USAF squadron under [[entities/afsoc|AFSOC]] (Air Force Special Operations Command), garrisoned at **Cannon AFB, New Mexico** ^[inferred — open-source standard attribution; the wiki's dow-uap d27 OCR names the squadron but not the garrison] and parented by the [[entities/27-sow|27th Special Operations Wing (27 SOW)]]. The 3 SOS is plausibly an **MQ-9 Reaper SOF community** for AFSOC organic ISR operations ^[inferred — based on AN/DAS-1 TGT Pod + 10h+ mission cycle from d27 + AFSOC SOS standard attribution].

This page is a **stub hub**. 3 SOS surfaces in the dow-uap corpus as the **Originator unit** of d27 — the second AFSOC ISR Misrep in the corpus and the first 3 SOS attestation.

## Role in the dow-uap corpus

[[references/dow-uap-d27-mission-uae-2024-06-06|d27]] (6-7 Jun 2024) is the dow-uap corpus's second AFSOC artifact. d27 MSGID Originator = `3 SOS` ^[extracted]; POC Unit unavailable; QC Unit = 56 SOIS (sister intelligence squadron in 27 SOW); POC Wing = 27 SOW ^[extracted]. The mission profile:

- **Launched from Al Dhafra AB (OMAM), UAE** — first AFSOC mission from CENTCOM-AOR launch base in dow-uap corpus ^[inferred].
- **USCENTCOM COCOM-tasked + AFSOC MAJCOM** — same-AOR (no EUCOM bridge) AFSOC ISR routing ^[extracted].
- **10h 13min WX-RTB-truncated mission cycle** — first WX-RTB-truncated MQ-9 ISR mission in dow-uap class; second-shortest mission overall after d19's 4h 55min F-15E DCA.
- **Bidirectional 4-OC chain (single-COCOM CENTCOM)**: POC home OC = 609 CAOC → QC = 609 AOC Det 1 → APPROVER Wing 379 AEW at 609 CAOC → executing 609th. First single-COCOM AFSOC mission in dow-uap.
- **1X UAP datum at 070457Z** at MGRS `40RFM60` — GLOWING HOT SPHERE with vertical cylindrical pole/bar appendage + water reflection; flying straight just over the water at 140 KNOTS.

## Significance for the corpus

- **First 3 SOS attestation in dow-uap full-Misrep class** — sister AFSOC SOS to 33 SOS within 27 SOW parent. d25 (33 SOS LGLR) + d27 (3 SOS OMAM) firms **AFSOC MQ-9 ISR cross-squadron cluster at N=2** within 27 SOW — first cross-squadron pattern within AFSOC class in dow-uap ^[inferred].
- **Cross-squadron + cross-launch-base operation pattern.** 33 SOS operates from LGLR Greece (EUCOM AOR) under cross-AOR tasking; 3 SOS operates from OMAM UAE (CENTCOM AOR) under same-AOR tasking — **two distinct operational profiles within same parent wing** ^[inferred]. The 27 SOW does not lock its MQ-9 ISR squadron pool to single launch base or cross-OC topology.
- **First AFSOC-CENTCOM-AOR-launched-CENTCOM-tasked mission** ^[inferred]. d25's bidirectional cross-COCOM 3-OC chain (Greece launch, CENTCOM-tasked, EUCOM-routed) is structurally distinct from d27's single-COCOM CENTCOM 4-role chain. 3 SOS anchors the CENTCOM-AOR-launched variant ^[inferred].

## Related entities and contexts

- [[entities/33-sos|33rd Special Operations Squadron]] — sister AFSOC SOS at d25; same 27 SOW parent.
- [[entities/27-sow|27th Special Operations Wing (27 SOW)]] — parent wing; d27 POC Wing.
- [[entities/afsoc|Air Force Special Operations Command (AFSOC)]] — parent MAJCOM (recurs at N=2).
- [[entities/609-caoc|609 CAOC / 609 AOC]] — POC home + APPROVER + executing OC at d27 (single-COCOM CENTCOM).
- [[entities/432-aew|432d Air Expeditionary Wing (432 AEW)]] — corpus's prior-dominant MQ-9 ISR pool; 12-of-14 = ~86% within MQ-9 ISR subset at d27 ingest.
- [[entities/mq-9-reaper|MQ-9 Reaper]] — d27 airframe ^[inferred].
- [[entities/dow-uap-foia-release]] — release context (Block F).
- [[references/dow-uap-d27-mission-uae-2024-06-06|DoW-UAP-D27]] — sole corpus attestation.

## Open threads

- **Cannon AFB garrison anchor.** Open-source standard; not literally stated in dow-uap OCR. ^[open]
- **MQ-9 platform attribution.** 3 SOS is an AFSOC SOS — open-source attribution of MQ-9 to 3 SOS is plausible per AN/DAS-1 TGT Pod + 10h+ mission cycle + SOS-MQ-9 standard. d27 OCR redacts MDS/Tail Number. ^[ambiguous] — 3 SOS may also be U-28A or AC-130 platform; MQ-9 reading preferred at N=1 per d27 anchors.
- **3 SOS at N≥2 — sustained cross-squadron AFSOC ISR.** Whether 3 SOS recurs in dow-uap (or another sister AFSOC SOS recurs) would firm cross-squadron AFSOC ISR cluster at N≥3. ^[open]

## See also

- [[projects/uap/uap]] — project overview.
- [[entities/dow-uap-foia-release]] — release context.
