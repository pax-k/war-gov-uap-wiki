---
title: 33rd Special Operations Squadron (33 SOS)
category: entities
tags: [usaf, organization, military, uap, isr]
aliases: [33 SOS, 33rd SOS, 33d Special Operations Squadron, 33rd Special Operations Squadron]
sources: [sources/dow-uap-d25-mission-report-greece-january-2024.json, sources/dow-uap-d33-mission-report-greece-october-2023.json]
summary: USAF / AFSOC MQ-9 Reaper Special Operations Squadron ^[inferred] at Cannon AFB NM, parented by 27 SOW. **33 SOS recurs at N=2** in dow-uap full-Misrep class (d33 26-27 Oct 2023 + d25 25 Jan 2024 — both from LGLR Greece launch base with same 27 SOW + 56 SOIS unit chain); d33 is **first 33 SOS attestation by event date** (d25 first by ingest order). Sister AFSOC SOS to 3 SOS (d27 MQ-9 Originator ^[inferred]) + 16 SOS (d28 AC-130J Originator/POC ^[inferred — strongly]) within 27 SOW parent — AFSOC SOS-cluster firms at N=3 cross-platform (MQ-9 ISR + AC-130J ARMED OVERWATCH).
provenance:
  extracted: 0.30
  inferred: 0.65
  ambiguous: 0.05
base_confidence: 0.55
lifecycle: draft
lifecycle_changed: 2026-05-13
created: 2026-05-13T12:00:00Z
updated: 2026-05-13T22:00:00Z
---

## [2026-05-13 update] d33 ingest — 33 SOS RECURS AT N=2 + first 33 SOS by event date + LGLR Greece launch at N=2 + AFSOC LGLR-OJMS rotational two-base sub-cluster

[[references/dow-uap-d33-mission-greece-2023-10-26|DoW-UAP-D33]] (26-27 Oct 2023) carries `MSGID Originator: 33 SOS` ^[extracted] — **second 33 SOS attestation** in dow-uap corpus, and the **first 33 SOS attestation by event date** (~91 days before [[references/dow-uap-d25-mission-greece-2024-01-25|d25]]'s 25 Jan 2024 mission). 33 SOS now recurs at N=2 within a 3-month window, both from **Larissa Air Base (LGLR), Greece** launch base, both with the **same 27 SOW POC Wing + 56 SOIS POC/QC Unit + AN/DAS-4 TGT Pod + 603rd executing OC + GET FMV-exploitation-unit** Originator chain ^[extracted]:

| Mission | Date | Mission cycle | Launch base | Land base | UAP datum |
|---|---|---|---|---|---|
| **d33** | 26-27 Oct 2023 | 13h 30min (ferry + ISR) | LGLR Greece | **OJMS Jordan (cross-AOR ferry)** | 270035Z UTM 35S KD; circular small low-slow 80 MPH sharp-90°-turns over ocean |
| d25 | 25 Jan 2024 | 20h 40min (round-trip ISR) | LGLR Greece | LGLR Greece (round-trip) | 250509Z UTM 35S QT; diamond+probe SWIR-only 434 KTS FL250→FL200 |

d33 + d25 anchor the **AFSOC 33 SOS LGLR rotational sub-cluster** at N=2 cross-AOR within ~3 months ^[inferred]. The narrative attestation `TRANSITED AND LANDING AT OJMS TO REPLACE THE LIGHTNING LINE THAT LANDED AT LGLR YESTERDAY` ^[extracted] firms a **LGLR ↔ OJMS rotational two-base AFSOC lane** with at least one prior LIGHTNING-LINE rotation pre-d33. 33 SOS operates from LGLR Greece at both attestations — whether 33 SOS operates from other AFSOC launch bases (OMAM UAE, OKAS Kuwait) is open ^[open].

**Framing refinement** ^closed-by-dow-uap-d33 (refinement class on d25-anchored "first 33 SOS attestation" headline): d33 is **first 33 SOS by EVENT DATE**, d25 is **first 33 SOS by INGEST ORDER**. The d25-anchored "FIRST AFSOC + first 27 SOW + first 33 SOS + first 56 SOIS + first 609 AOC Det 1 + first Greece + first LGLR + first 35S UTM" headlines retain their ingest-order-first framing but now carry the event-date-first qualifier ^[inferred].

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

## d27 sister-squadron attestation — 3 SOS Originator at N=2 cross-squadron AFSOC

[[references/dow-uap-d27-mission-uae-2024-06-06|d27]] (6-7 Jun 2024) carries `MSGID Originator: 3 SOS` ^[extracted] — **first 3 SOS attestation** in dow-uap corpus, and **sister AFSOC SOS to 33 SOS** under the same 27 SOW parent wing ^[inferred]. d25 + d27 anchor **AFSOC MQ-9 ISR cross-squadron cluster at N=2** within 27 SOW — first cross-squadron pattern within AFSOC class in dow-uap.

- d25 (33 SOS, LGLR Greece, 25 Jan 2024): EUCOM-AOR-launched + CENTCOM-tasked, 20h 40min, diamond+probe morphology
- d27 (3 SOS, OMAM UAE, 6-7 Jun 2024): CENTCOM-AOR-launched + CENTCOM-tasked, 10h 13min (WX-RTB truncated), sphere+pole/bar morphology

The 33 SOS / 3 SOS sister-squadron pair operates **two distinct AOR launch bases within 5 months** under the same parent wing — first AFSOC MQ-9 ISR cross-squadron + cross-AOR pattern in corpus ^[inferred]. ^closed-by-dow-uap-d27 (firming class on d25-anchored "AFSOC mission-record cluster at N≥2" thread).

## d28 sister-squadron attestation — 16 SOS AC-130J at N=3 cross-platform AFSOC

[[references/dow-uap-d28-mission-iraq-2024-09-20|d28]] (20-21 Sep 2024) carries `POC Unit: 16 SOS` + `MSGID Originator: SOTU 016` ^[extracted; ^[ambiguous] — most parsimonious reading is OCR variant of `16 SOS`]. **16 SOS is the third AFSOC SOS in dow-uap corpus** and **sister to 33 SOS + 3 SOS** under the same 27 SOW parent wing ^[inferred]. d28 introduces a **cross-platform AFSOC SOS pattern** at N=3:

| SOS | Mission | Platform ^[inferred] | Mission Type |
|---|---|---|---|
| 33 SOS | d25 LGLR Greece (25 Jan 2024) | MQ-9 Reaper | ISR |
| 3 SOS | d27 OMAM UAE (6-7 Jun 2024) | MQ-9 Reaper | ISR |
| **16 SOS** | **d28 OKAS/AAAB Iraq (20-21 Sep 2024)** | **AC-130J Ghostrider ^[inferred — strongly]** | **ARMED OVERWATCH** |

The 16 SOS attribution to **AC-130J Ghostrider is decisive** ^[inferred — strongly] at d28 per weapons fit (105mm M102 + 30mm GAU-23/A + AGM-176 Griffin), sensor fit (MX-20 + MX-25), 7h 6min mission cycle (vs MQ-9 ISR's ~20-22h envelope), and ARMED OVERWATCH mission type. **AFSOC SOS-cluster firms at N=3 cross-platform within 27 SOW parent** ^closed-by-dow-uap-d28 (firming class). **Per-SOS platform-class scheme anchors** ^[inferred]: 33 SOS + 3 SOS = MQ-9 ^[inferred]; 16 SOS = AC-130J ^[inferred — strongly].

## Open threads

- **Cannon AFB garrison anchor.** Open-source attribution standard; not literally stated in dow-uap OCR. ^[open]
- **MQ-9 platform attribution.** 33 SOS is an AFSOC SOS — open-source attribution of MQ-9 to 33 SOS is standard, but the d25 OCR redacts MDS/Tail Number. Inference relies on AN/DAS-4 TGT Pod (canonical Reaper MTS-B family) + 20:40 mission cycle + SOS-MQ-9 standard attribution. ^[inferred] **d28 partially firms the per-SOS platform-class scheme** by anchoring 16 SOS = AC-130J ^[inferred — strongly], implying that AFSOC SOSs in dow-uap are individually platform-class-bound and 33 SOS / 3 SOS read MQ-9 within that scheme.
- ~~**AFSOC mission-record cluster at N≥2.**~~ ^closed-by-dow-uap-d27 — AFSOC recurs at N=2 cross-squadron (33 SOS d25 + 3 SOS d27).
- ~~**AFSOC SOS-cluster at N≥3 cross-squadron.**~~ ^closed-by-dow-uap-d28 (firming class) — AFSOC SOS-cluster firms at N=3 cross-platform (33 SOS MQ-9 + 3 SOS MQ-9 + 16 SOS AC-130J) within 27 SOW.
- **3 SOS platform attribution.** d27's 3 SOS may operate MQ-9 (matches d27 AN/DAS-1 TGT Pod + AFSOC SOS standard attribution) OR a different airframe (U-28A, AC-130, etc.) ^[ambiguous]; MQ-9 inference at d27 is preferred per AN/DAS-1 + 10h+ mission cycle envelope. **d28 marginally firms MQ-9 reading for 3 SOS** by anchoring 16 SOS = AC-130J in distinct mission-cycle envelope (7h 6min vs 3 SOS's 10h 13min); platform-class scheme firms ^[inferred].
- ~~**33 SOS at N≥2 in dow-uap.**~~ ^closed-by-dow-uap-d33 — 33 SOS recurs at N=2 within 3-month window (d33 26-27 Oct 2023 + d25 25 Jan 2024); both from LGLR Greece launch base with identical 27 SOW + 56 SOIS Originator chain. **AFSOC LGLR-OJMS rotational sub-cluster firms at N=2** with d33 ferry + d25 round-trip variants. d33 is **first 33 SOS attestation by event date**; d25 was first by ingest order.
- **33 SOS at N≥3 — sustained AFSOC MQ-9 ISR lane.** Whether 33 SOS recurs beyond N=2 (third attestation from LGLR or other AFSOC launch base) is open ^[open].
- **33 SOS launch-base diversity.** Both d33 + d25 launched from LGLR Greece. Whether 33 SOS operates from CENTCOM-AOR AFSOC launch bases (OMAM UAE, OKAS Kuwait) at sister-mission level is open ^[open]; alternatively 33 SOS may be LGLR-specific within dow-uap ^[ambiguous].

## See also

- [[entities/3-sos|3rd Special Operations Squadron (3 SOS)]] — sister AFSOC SOS; d27 Originator (MQ-9 ^[inferred]).
- [[entities/16-sos|16th Special Operations Squadron (16 SOS)]] — sister AFSOC SOS; d28 POC/Originator (AC-130J ^[inferred — strongly]).
- [[entities/ac-130j-ghostrider|AC-130J Ghostrider]] — d28 airframe; first non-MQ-9 AFSOC platform in dow-uap.
- [[references/dow-uap-d33-mission-greece-2023-10-26|DoW-UAP-D33]] — **first 33 SOS attestation by event date** (26-27 Oct 2023); LGLR Greece → OJMS Jordan ferry; sister-mission to d25 within ~3-month window.
- [[references/dow-uap-d27-mission-uae-2024-06-06|DoW-UAP-D27]] — second AFSOC attestation by ingest order; 3 SOS Originator under 27 SOW parent.
- [[references/dow-uap-d28-mission-iraq-2024-09-20|DoW-UAP-D28]] — third AFSOC attestation by ingest order; 16 SOS / first AC-130J / first ARMED OVERWATCH / first kinetic-weapons-employment in dow-uap.
- [[projects/uap/uap]] — project overview.
- [[entities/dow-uap-foia-release]] — release context.
