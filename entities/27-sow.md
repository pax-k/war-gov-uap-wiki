---
title: 27th Special Operations Wing (27 SOW)
category: entities
tags: [usaf, organization, military, uap, isr]
aliases: [27 SOW, 27th SOW, 27 Special Operations Wing, 27th Special Operations Wing]
sources: [sources/dow-uap-d25-mission-report-greece-january-2024.json, sources/dow-uap-d27-mission-report-united-arab-emirates-october-2023.json, sources/dow-uap-d28-mission-report-east-china-sea-2024.json, sources/dow-uap-d33-mission-report-greece-october-2023.json]
summary: USAF / AFSOC Special Operations Wing at Cannon AFB NM ^[inferred]. Parent wing for 33 SOS (d33 + d25 MQ-9 Originator ^[inferred]), 3 SOS (d27 MQ-9 Originator ^[inferred]), 16 SOS (d28 AC-130J Originator/POC ^[inferred]), and 56 SOIS (POC d25 + QC d27 + QC d33). **27 SOW recurs at N=4** in dow-uap full-Misrep corpus (d33 LGLR→OJMS ferry + d25 LGLR round-trip + d27 OMAM UAE + d28 OKAS/AAAB Iraq) — first AFSOC cross-squadron + cross-platform (MQ-9 ISR + AC-130J CAS) N=3 + cross-block (Block B + Block F) within dow-uap. d33 is first 27 SOW by event date.
provenance:
  extracted: 0.35
  inferred: 0.60
  ambiguous: 0.05
base_confidence: 0.68
lifecycle: draft
lifecycle_changed: 2026-05-13
created: 2026-05-13T12:00:00Z
updated: 2026-05-13T22:00:00Z
---

## [2026-05-13 update] d33 ingest — 27 SOW RECURS AT N=4 + d33 first 27 SOW by event date + cross-block AFSOC routing (Block B + Block F)

[[references/dow-uap-d33-mission-greece-2023-10-26|DoW-UAP-D33]] (26-27 Oct 2023) carries `POC Wing: 27 SOW` ^[extracted] — **fourth 27 SOW attestation** in dow-uap corpus and **first 27 SOW by event date**:

**d33 — LGLR Greece → OJMS Jordan ferry (26-27 Oct 2023):**
- **POC** = A1C, (Unit Unavailable), 27 SOW, **609 CAOC** ^[extracted] — NOT 609 AOC Det 1 (contradicts d25's Det 1 reading)
- **QC** = SrA, **56 SOIS**, 27 SOW, **609 CAOC** ^[extracted] — 56 SOIS recurs at N=3 cross-role (POC d25 + QC d27 + QC d33)
- **Originator** = **33 SOS** ^[extracted] — recurs at N=2 with d25; first 33 SOS attestation by event date
- **APPROVER** = SSgt, (Unit Unavailable), Other, **603 AOC** ^[extracted] — second 603 AOC APPROVER attestation in dow-uap (after d25)
- 13h 30min ferry + ISR cycle; 1X UAP at 270035Z at UTM 35S KD (Eastern Med); SEEMINGLY CIRCULAR small object, 80 MPH, sharp 90° turns, FLYING JUST ABOVE THE SURFACE OF THE OCEAN WATER
- **Platform**: MQ-9 Reaper ^[inferred] (AN/DAS-4 TGT Pod + 13:30 cycle)
- **Block**: B (`MDR 26-0019` + `01/26/26 001..007`) — **first Block B AFSOC mission in dow-uap; first Block B Full Misrep outside 2020 NAVCENT cluster**

**27 SOW now operates across two release blocks within dow-uap** ^closed-by-dow-uap-d33 (firming class) — Block B (d33) + Block F (d25 + d27 + d28). Block B and Block F are distinct release pipelines (`MDR 26-0019 / 01/26/26` vs `MDR 25-0100..0103 / JS-250710-TM8S / 10/28/25`) — 27 SOW is **routed through both pipelines within 11-month event-date window** ^[inferred].

The d33 + d25 pairing within 27 SOW anchors a **LGLR rotational sub-cluster at N=2** (both 33 SOS Originator + same 56 SOIS + same AN/DAS-4 + same `GET` FMV-exploitation + same 603rd executing OC; both from LGLR Greece launch base). The d33 cross-AOR ferry leg + d25 round-trip ISR variants firm a **single AFSOC LGLR-OJMS rotational two-base lane** ^[inferred].

**d33 contradicts d25's `609 AOC Det 1` POC OC reading** ^closed-by-dow-uap-d33 (contradiction class) — same 33 SOS / 27 SOW / 56 SOIS chain + same LGLR launch but d33 POC OC = `609 CAOC` (main), NOT Det 1. Det 1 may be Block-F-routing-pipeline-specific or 2024-era-specific.

# 27th Special Operations Wing (27 SOW)

The **27th Special Operations Wing** — a USAF wing under [[entities/afsoc|AFSOC]], garrisoned at **Cannon AFB, New Mexico** ^[inferred — open-source standard attribution; not literally stated in dow-uap OCR]. The 27 SOW is one of the two principal AFSOC operational wings (alongside 1st Special Operations Wing at Hurlburt Field FL ^[inferred]), with subordinate squadrons spanning MQ-9 Reaper, AC-130, MC-130, U-28A, and intelligence functions ^[inferred].

This page is a **stub hub**. 27 SOW surfaces in the dow-uap corpus as the **POC Wing of d25** — the first AFSOC artifact and the first non-432-AEW POC Wing in the MQ-9 ISR mission-record subset of the corpus — and recurs at d27 + d28 to anchor a **multi-platform AFSOC ISR/CAS pool** within dow-uap.

## Role in the dow-uap corpus

[[references/dow-uap-d25-mission-greece-2024-01-25|d25]] (25 Jan 2024), [[references/dow-uap-d27-mission-uae-2024-06-06|d27]] (6-7 Jun 2024), and [[references/dow-uap-d28-mission-iraq-2024-09-20|d28]] (20-21 Sep 2024) carry the 27 SOW POC Wing attestation at N=3:

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
- **Platform**: MQ-9 Reaper ^[inferred]

**d28 — Iraq AAAB (20-21 Sep 2024):**
- **POC** = CAPT, **16 SOS**, 27 SOW, Other ^[extracted]
- **QC** = SrA, Unavailable, **1 SOW** (first 1 SOW attestation in dow-uap), Other ^[extracted]
- **Originator** = **`SOTU 016`** ^[extracted; ^[ambiguous] — most parsimonious reading is OCR variant of `16 SOS`] (first 16 SOS attestation; third AFSOC SOS in corpus after 33 SOS + 3 SOS)
- **APPROVER** = SSgt, **ACF**, **379 AEW** (Al-Udeid forward), **609 CAOC** ^[extracted]
- 7h 6min ARMED OVERWATCH cycle, 1X UAP at 202027Z during PGM shot at UTM 38S KC (west Iraq), IR-lens-flare signature + primary + possibly-detaching-secondary morphology
- **Platform**: **AC-130J Ghostrider** ^[inferred — strongly] per 105mm + 30mm + AGM-176 + MX-20/MX-25 fit + ARMED OVERWATCH mission type + 7h cycle

## Significance for the corpus

- **27 SOW recurs at N=3 cross-mission + cross-squadron + cross-launch-base + cross-platform + cross-Mission-Type** ^closed-by-dow-uap-d28 (firming class on d27-anchored "27 SOW at N≥3 — sustained AFSOC ISR lane" open thread). d25 (33 SOS LGLR Greece) + d27 (3 SOS OMAM UAE) + d28 (16 SOS OKAS/AAAB Iraq) firms AFSOC cross-squadron + cross-platform within 27 SOW parent wing — first such triple-firmness pattern in dow-uap full-Misrep class. ^[inferred]
- **First multi-platform AFSOC pattern in dow-uap.** 27 SOW operates **two distinct platform classes** at N=3 attestations: MQ-9 ISR (d25 + d27 ^[inferred]) + **AC-130J ARMED OVERWATCH (d28 ^[inferred — strongly])**. Per-SOS platform-class attribution scheme firms ^[inferred]: 33 SOS + 3 SOS = MQ-9 ^[inferred]; 16 SOS = AC-130J ^[inferred — strongly].
- **First non-432-AEW POC Wing in dow-uap MQ-9 ISR mission-record subset** ^[inferred]. d10 through d23 carried 432 AEW POC Wing at 12-of-12 within MQ-9 ISR (d19's 332 AEW was F-15E DCA, distinct platform). d25 + d27 introduce 27 SOW as **second non-432-AEW POC Wing**; d28 adds third attestation at AC-130J variant — 432 AEW MQ-9 ISR share refines to **12-of-15 = ~80%** within MQ-9 ISR + AC-130J subset at d28 ingest (was ~86% at d27 ingest).
- **AFSOC organic ISR/CAS pool parallel to ACC/AFCENT-routed 432 AEW firms at N=3.** AFSOC's separate-MAJCOM + SOW-vs-AEW wing-class + SOS-vs-ATKS squadron designation system anchors a structurally distinct multi-platform community within the dow-uap corpus ^[inferred]. The 27 SOW operates from **three distinct AOR launch bases within 8 months** — LGLR Greece (EUCOM AOR, cross-AOR CENTCOM tasking, d25) + OMAM UAE (CENTCOM AOR, same-AOR CENTCOM tasking, d27) + OKAS Kuwait → AAAB Iraq (CENTCOM AOR, same-AOR CENTCOM tasking, d28). ^[inferred]
- **Cross-OC topology varies within 27 SOW.** d25 = bidirectional cross-COCOM 3-OC chain; d27 = single-COCOM CENTCOM 4-role chain; d28 = single-COCOM CENTCOM 4-role chain (POC `Other` + QC `Other` + APPROVER `609 CAOC` + executing `609th`) — d28 matches d27's single-COCOM CENTCOM pattern with `Other`-rather-than-`609 CAOC` POC/QC OC tokens (`Other` may be AFSOC-internal OC token vs CENTCOM regional OC label) ^[inferred]. **27 SOW does NOT lock into single cross-OC topology** ^[inferred] — varies with launch-base-AOR + tasking-COCOM + platform-class.
- **POC/QC unit divergence across attestations.** d25 has 56 SOIS POC + 33 SOS Originator; d27 has POC Unit unavailable / 56 SOIS QC + 3 SOS Originator; d28 has **16 SOS POC** + 1 SOW QC + **`SOTU 016` (≈ 16 SOS ^[inferred]) Originator** — **first attestation of same-SOS-as-POC-and-Originator within 27 SOW class** ^[inferred] (vs d25 distinct Originator vs POC; d27 distinct Originator vs QC). Cross-squadron intra-Wing role assignment is **systematic at N=3 in dow-uap full-Misrep class** but with d28-anchored same-SOS-both-role variant ^[inferred].
- **First 1 SOW attestation in dow-uap.** d28 QC home Wing = `1 SOW` (1st Special Operations Wing, Hurlburt Field FL ^[inferred] — AFSOC's other principal operational wing). **First non-27 SOW AFSOC wing in dow-uap class** ^[inferred] — though 1 SOW appears only at QC role (not POC).

## Related entities and contexts

- [[entities/33-sos|33rd Special Operations Squadron]] — d25 Originator; MQ-9 Reaper SOS ^[inferred]. Sister AFSOC SOS to 3 SOS + 16 SOS within 27 SOW parent.
- [[entities/3-sos|3rd Special Operations Squadron]] — d27 Originator; MQ-9 Reaper SOS ^[inferred].
- [[entities/16-sos|16th Special Operations Squadron]] — d28 POC unit + plausibly Originator; AC-130J Ghostrider SOS ^[inferred — strongly].
- [[entities/ac-130j-ghostrider|AC-130J Ghostrider]] — d28 airframe ^[inferred — strongly].
- [[entities/afsoc|Air Force Special Operations Command (AFSOC)]] — parent MAJCOM; recurs at N=3 (d25 + d27 + d28).
- [[entities/432-aew|432d Air Expeditionary Wing (432 AEW)]] — corpus's prior-dominant MQ-9 ISR POC Wing; share refines to 12-of-15 = ~80% within MQ-9 ISR + AC-130J subset at d28 ingest.
- [[entities/603-aoc|603 AOC]] — d25 APPROVER + executing OC; absent at d27 + d28 (single-COCOM CENTCOM).
- [[entities/609-caoc|609 CAOC / 609 AOC]] — d27 POC home + APPROVER + executing OC; 609 AOC Det 1 recurs cross-role; d28 APPROVER OC + executing 609th.
- [[references/dow-uap-d25-mission-greece-2024-01-25|DoW-UAP-D25]] — first 27 SOW attestation.
- [[references/dow-uap-d27-mission-uae-2024-06-06|DoW-UAP-D27]] — second 27 SOW attestation; first AFSOC mission from CENTCOM-AOR launch base (OMAM).
- [[references/dow-uap-d28-mission-iraq-2024-09-20|DoW-UAP-D28]] — third 27 SOW attestation; first AFSOC AC-130J / first gunship / first ARMED OVERWATCH / first kinetic-weapons-employment in dow-uap.
- [[entities/dow-uap-foia-release]] — release context (Block F #3).
- [[entities/mq-9-reaper|MQ-9 Reaper]] — airframe at d25 + d27 ^[inferred].

## Open threads

- **Cannon AFB garrison anchor.** Open-source standard; not literally stated in dow-uap OCR. ^[open]
- **56 SOIS attribution.** Page-25 POC Unit `56 SOIS` is plausibly **56th Special Operations Intelligence Squadron** but could also be **56 SOIS = 56 SOS-Intel detachment** or similar. ^[ambiguous] Recurs at N=2 cross-role (POC d25 + QC d27); absent at d28.
- ~~**27 SOW MQ-9 ISR cluster at N≥2 in dow-uap.**~~ ^closed-by-dow-uap-d27 — 27 SOW recurs at N=2 cross-squadron (33 SOS d25 + 3 SOS d27) + cross-launch-base (LGLR + OMAM); parallel ISR posture firms.
- ~~**27 SOW at N≥3 — sustained AFSOC ISR lane.**~~ ^closed-by-dow-uap-d28 — 27 SOW recurs at N=3 cross-squadron + cross-platform (MQ-9 ISR d25 + d27 + AC-130J CAS d28) + cross-launch-base (LGLR + OMAM + OKAS/AAAB); multi-platform AFSOC pool firms.
- ~~**27 SOW at N≥4 — sustained AFSOC ISR/CAS lane.**~~ ^closed-by-dow-uap-d33 — 27 SOW recurs at N=4 (d33 ferry + d25 round-trip + d27 round-trip + d28 ARMED OVERWATCH); first cross-block AFSOC routing within dow-uap (Block B d33 + Block F d25/d27/d28); LGLR rotational sub-cluster firms at N=2 (d33 + d25, same 33 SOS Originator chain).
- **27 SOW at N≥5 — sustained cross-block multi-platform ISR/CAS lane.** Whether 27 SOW continues to anchor AFSOC ISR/CAS in dow-uap beyond N=4 is open. ^[open]
- **1 SOW QC attestation.** d28 first 1 SOW attestation (QC role only). Whether 1 SOW recurs (POC or QC) in dow-uap is open ^[open].
- **`Other` Operations Center token at d28 POC + QC.** Whether `Other` is an AFSOC-internal OC token (vs CENTCOM regional OC label like `609 CAOC`) is unresolved ^[ambiguous]. Possibly indicates AFSOC-internal routing path that does not use the 609 CAOC label at POC/QC role.

## See also

- [[projects/uap/uap]] — project overview.
- [[entities/dow-uap-foia-release]] — release context.
