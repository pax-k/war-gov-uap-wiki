---
title: 33rd Special Operations Squadron (33 SOS)
category: entities
tags: [usaf, organization, military, uap, isr]
aliases: [33 SOS, 33rd SOS, 33d Special Operations Squadron, 33rd Special Operations Squadron]
sources: [sources/dow-uap-d25-mission-report-greece-january-2024.json]
summary: USAF / AFSOC MQ-9 Reaper Special Operations Squadron ^[inferred] at Cannon AFB NM, parented by 27 SOW. First non-432-AEW MQ-9 ISR Originator unit in the dow-uap full-Misrep mission-record class (d25).
provenance:
  extracted: 0.30
  inferred: 0.65
  ambiguous: 0.05
base_confidence: 0.55
lifecycle: draft
lifecycle_changed: 2026-05-13
created: 2026-05-13T12:00:00Z
updated: 2026-05-13T12:00:00Z
---

# 33rd Special Operations Squadron (33 SOS)

The **33rd Special Operations Squadron** — a USAF squadron under [[entities/afsoc|AFSOC]] (Air Force Special Operations Command), garrisoned at **Cannon AFB, New Mexico** ^[inferred — open-source standard attribution; the wiki's dow-uap d25 OCR names the squadron but not the garrison.] and parented by the [[entities/27-sow|27th Special Operations Wing (27 SOW)]]. The 33 SOS is the **MQ-9 Reaper SOF community** for AFSOC organic ISR-strike operations ^[inferred — Special Operations Squadron numbering, AN/DAS-4 TGT pod + 20:40 mission cycle from d25 strongly imply MQ-9].

This page is a **stub hub**. 33 SOS surfaces in the dow-uap corpus as the **Originator unit** of d25 — the first AFSOC ISR Misrep + first non-432-AEW MQ-9 ISR mission-report in the corpus.

## Role in the dow-uap corpus

[[references/dow-uap-d25-mission-greece-2024-01-25|d25]] (25 Jan 2024) is the dow-uap corpus's first AFSOC artifact. d25 MSGID Originator = `33 SOS`; POC Unit = `56 SOIS` (sister intelligence squadron in 27 SOW); POC Wing = `27 SOW` ^[extracted]. The mission profile:

- **Launched from Larissa Air Base (LGLR), Greece** — first dow-uap Misrep from a Greek launch base + first Eastern Aegean / Northern Med launch base in corpus ^[inferred].
- **USCENTCOM COCOM tasked + AFSOC MAJCOM** — first cross-MAJCOM-EUCOM-launched-CENTCOM-tasked mission in dow-uap corpus ^[inferred].
- **20h 40min mission cycle + 08:29 FMV + 08:27 SIGINT** — consistent with MQ-9 platform-endurance regime ^[inferred].
- **Bidirectional 3-OC chain**: POC home OC = 609 AOC Det 1 (CENTCOM) → QC = 609 CAOC (CENTCOM) → APPROVER = 603 AOC (EUCOM) → executing OC = 603rd (EUCOM). First four-role-chain across two COCOMs in single mission ^[inferred].
- **1X UAP datum at 250509Z** at MGRS `35SQT67` — diamond+probe morphology, SWIR-only, 434 KTS, 2-min duration; first 35S UTM + first single-sensor-exclusive UAP in corpus.

## Significance for the corpus

- **First non-432-AEW MQ-9 ISR Originator** ^[inferred]. The dow-uap full-Misrep mission-record class held a monolithic 432 AEW POC Wing dominance from d10 through d23 (12 attestations + 6 cluster). d19 broke the pattern at the platform-axis (332 AEW F-15E DCA). d25 breaks the pattern at the **MQ-9 ISR axis** — 27 SOW / 33 SOS is the first non-432-AEW MQ-9 ISR Originator. ^[inferred]
- **AFSOC organic ISR posture distinct from ACC/AFCENT-routed 432 AEW.** AFSOC's command structure (separate MAJCOM, separate wing class, separate squadron designation system — SOS vs ATKS) confirms that the dow-uap FOIA release is **NOT lane-locked at ACC/AFCENT-tasked 432 AEW** ^[inferred]. AFSOC routes Misreps through the same USMTF Misrep parent class under the same `JS-250710-TM8S` Joint Staff routing.
- **AFSOC + 27 SOW + 33 SOS + 56 SOIS unit chain extends MQ-9 community at corpus level** ^[inferred] to **two distinct AOC-routed pools**: 432 AEW (ACC/AFCENT-routed under 609 CAOC) + 27 SOW (AFSOC-routed under 603rd executing, with 609 AOC Det 1 POC home).

## Related entities and contexts

- [[entities/27-sow|27th Special Operations Wing (27 SOW)]] — parent wing; d25 POC Wing.
- [[entities/afsoc|Air Force Special Operations Command (AFSOC)]] — parent MAJCOM.
- [[entities/603-aoc|603 AOC]] — executing OC at d25 + APPROVER (fifth distinct 603 AOC role-attestation).
- [[entities/609-caoc|609 CAOC / 609 AOC]] — POC home OC via `609 AOC Det 1` (first Det 1 attestation) + QC at d25.
- [[entities/432-aew|432d Air Expeditionary Wing (432 AEW)]] — the 432 AEW MQ-9 community is the corpus's prior-dominant MQ-9 ISR pool; d25 anchors a parallel AFSOC pool.
- [[entities/mq-9-reaper|MQ-9 Reaper]] — airframe at d25 ^[inferred].
- [[entities/dow-uap-foia-release]] — release context.
- [[references/dow-uap-d25-mission-greece-2024-01-25|DoW-UAP-D25]] — sole corpus attestation.

## Open threads

- **Cannon AFB garrison anchor.** Open-source attribution standard; not literally stated in dow-uap OCR. ^[open]
- **MQ-9 platform attribution.** 33 SOS is an AFSOC SOS — open-source attribution of MQ-9 to 33 SOS is standard, but the d25 OCR redacts MDS/Tail Number. Inference relies on AN/DAS-4 TGT Pod (canonical Reaper MTS-B family) + 20:40 mission cycle + SOS-MQ-9 standard attribution. ^[inferred]
- **AFSOC mission-record cluster at N≥2.** d25 anchors AFSOC at N=1. Recurrence (another 27 SOW or 33 SOS or sister-AFSOC unit Misrep in dow-uap) would firm AFSOC's parallel ISR posture. ^[open]

## See also

- [[projects/uap/uap]] — project overview.
- [[entities/dow-uap-foia-release]] — release context.
