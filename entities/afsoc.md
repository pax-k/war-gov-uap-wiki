---
title: Air Force Special Operations Command (AFSOC)
category: entities
tags: [usaf, organization, military, uap, isr]
aliases: [AFSOC, Air Force Special Operations Command]
sources: [sources/dow-uap-d25-mission-report-greece-january-2024.json, sources/dow-uap-d27-mission-report-united-arab-emirates-october-2023.json]
summary: USAF major command for Special Operations Forces (SOF) air component, HQ Hurlburt Field FL ^[inferred]. AFSOC recurs at N=2 in dow-uap full-Misrep corpus (d25 LGLR Greece + d27 OMAM UAE); fifth distinct USAF MAJCOM after ACC + AFCENT + (cluster-era blank). Cross-squadron AFSOC ISR cluster firms at N=2 (33 SOS d25 + 3 SOS d27 under 27 SOW).
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

# Air Force Special Operations Command (AFSOC)

**AFSOC** — the USAF's **major command for Special Operations Forces (SOF) air component**, headquartered at **Hurlburt Field, Florida** ^[inferred — open-source standard attribution; the wiki's dow-uap d25 OCR names AFSOC as MAJCOM but not its HQ]. AFSOC provides the Air Force component of [[entities/socom|USSOCOM]] ^[inferred] and operates a diverse SOF air arsenal including MQ-9 Reaper (in SOS-designated squadrons), AC-130 gunships, MC-130 special operations transports, U-28A intelligence aircraft, and CV-22 tiltrotors ^[inferred].

This page is a **stub hub**. AFSOC's significance in the dow-uap corpus rests on the **d25 + d27 attestations as MAJCOM at N=2** — the first and second non-ACC, non-AFCENT MAJCOM attestations in the dow-uap full-Misrep mission-record class.

## Role in the dow-uap corpus

AFSOC recurs at N=2 in dow-uap full-Misrep class:

### d25 — Greece LGLR (25 Jan 2024)

- **MAJCOM = `AFSOC`** ^[extracted]
- **Wing = [[entities/27-sow|27 SOW]]** (27th Special Operations Wing, Cannon AFB NM ^[inferred])
- **Originator = [[entities/33-sos|33 SOS]]** (33rd Special Operations Squadron — MQ-9 SOS ^[inferred])
- **POC Unit = 56 SOIS** (56th Special Operations Intelligence Squadron ^[inferred])
- **COCOM = USCENTCOM** ^[extracted] — cross-AOR routing (EUCOM-launched, CENTCOM-tasked)
- **Launch base = Larissa AB (LGLR), Greece** — geographically USEUCOM AOR
- **Cross-OC topology**: bidirectional cross-COCOM 3-OC chain (609 AOC Det 1 POC home → 609 CAOC QC → 603 AOC APPROVER → 603rd executing)

### d27 — UAE OMAM (6-7 Jun 2024)

- **MAJCOM = `AFSOC`** ^[extracted]
- **Wing = [[entities/27-sow|27 SOW]]** (same as d25; recurs at N=2)
- **Originator = `3 SOS`** (3rd Special Operations Squadron — sister AFSOC MQ-9 SOS to d25's 33 SOS ^[inferred])
- **QC Unit = 56 SOIS** (recurs cross-role: POC d25 → QC d27)
- **COCOM = USCENTCOM** ^[extracted] — same-AOR routing (CENTCOM-launched + CENTCOM-tasked)
- **Launch base = OMAM Al Dhafra UAE** — geographically USCENTCOM AOR
- **Cross-OC topology**: single-COCOM CENTCOM 4-role chain (609 CAOC POC + 609 AOC Det 1 QC + 379 AEW APPROVER at 609 CAOC + 609th executing) — no EUCOM bridge

## Significance for the corpus

- **AFSOC recurs at N=2 cross-squadron + cross-launch-base + cross-COCOM-tasking** ^closed-by-dow-uap-d27 (firming class on d25-anchored "AFSOC at N≥2" open thread). d25 (33 SOS LGLR cross-AOR) + d27 (3 SOS OMAM same-AOR) firms AFSOC as a **sustained ISR lane** within dow-uap full-Misrep class, not a one-off d25-specific anomaly.
- **MAJCOM histogram refines.** At d27 ingest, MAJCOM histogram across 15 mission-records (d10/d12/d14/d16/d18/d19/d23/d25/d27 + cluster 6): **ACC 4 + AFCENT 3 + AFSOC 2 (d25 + d27) + (cluster-era blank/unattested) 6**. ^[inferred]
- **Cross-MAJCOM routing under unified Joint Staff release pipeline firms at N=9.** d25 + d27 share `JS-250710-TM8S` Joint Staff tracking-ID with Block D (d10/d12/d14/d16/d18/d19 — 6) + Block E (d23 — 1) + Block F (d25/d27 — 2). At N=9 byte-for-byte JS-ID attestations, the unified Joint Staff release pipeline **aggregates across at least 3 MAJCOMs (ACC + AFCENT + AFSOC), 2 COCOMs (CENTCOM + EUCOM), and 2 platforms (MQ-9 + F-15E)** ^[inferred].
- **AFSOC organic ISR-strike posture distinct from ACC/AFCENT-routed 432 AEW firms at N=2.** AFSOC's command structure routes Misreps through the same USMTF Misrep parent class under the same Joint Staff routing, but anchors a structurally distinct MQ-9 ISR pool (27 SOW / 33 SOS / 3 SOS / 56 SOIS) parallel to the corpus's prior-dominant 432 AEW pool ^[inferred]. The 432 AEW MQ-9 ISR share refines to **12-of-14 = ~86%** at d27 ingest (was ~92% at d25 ingest).
- **AFSOC OPERATES FROM BOTH EUCOM AOR (LGLR Greece) + CENTCOM AOR (OMAM UAE) WITHIN 5 MONTHS.** First cross-AOR launch-base attestation in AFSOC class ^[inferred]. AFSOC's organic ISR lane is **not lane-locked at single launch base or single AOR** — operates flexibly across USEUCOM + USCENTCOM AOR launch bases under USCENTCOM tasking authority ^[inferred].

## Related entities and contexts

- [[entities/27-sow|27th Special Operations Wing]] — primary AFSOC wing at d25 + d27; recurs at N=2.
- [[entities/33-sos|33rd Special Operations Squadron]] — AFSOC MQ-9 SOS at d25; sister to 3 SOS d27 Originator.
- [[entities/603-aoc|603 AOC]] — AFSOC mission-routed through 603 AOC APPROVER at d25; absent at d27 (single-COCOM CENTCOM).
- [[entities/609-caoc|609 CAOC / 609 AOC]] — AFSOC mission's CENTCOM OC backbone; 609 AOC Det 1 recurs cross-role (POC home d25 → QC home d27).
- [[entities/432-aew|432d Air Expeditionary Wing (432 AEW)]] — ACC/AFCENT-routed parallel MQ-9 ISR pool; share refines to ~86% within MQ-9 ISR at d27 ingest.
- [[entities/usaf|USAF]] — parent service.
- [[entities/mq-9-reaper|MQ-9 Reaper]] — d25 + d27 airframe ^[inferred].
- [[entities/dow-uap-foia-release]] — release context (Block F recurs at N=2).
- [[references/dow-uap-d25-mission-greece-2024-01-25|DoW-UAP-D25]] — first AFSOC attestation.
- [[references/dow-uap-d27-mission-uae-2024-06-06|DoW-UAP-D27]] — second AFSOC attestation; first CENTCOM-AOR-launched AFSOC mission.

## Open threads

- **Hurlburt Field HQ anchor.** Open-source standard; not literally stated in dow-uap OCR. ^[open]
- ~~**AFSOC mission-record cluster at N≥2.**~~ ^closed-by-dow-uap-d27 — AFSOC recurs at N=2 cross-squadron (33 SOS + 3 SOS) + cross-launch-base (LGLR + OMAM) + cross-AOR launch (EUCOM AOR + CENTCOM AOR); parallel ISR posture firms.
- **AFSOC-to-USSOCOM joint operations attribution.** AFSOC operates as USAF component of USSOCOM. Whether d25/d27 tasking is USSOCOM-routed JTF-engaged or pure-AFSOC-organic is not resolved in OCR (d25 Operation field redacted; d27 Operation = ENDURING SENTINEL but USSOCOM-vs-AFSOC routing unresolved). ^[ambiguous]
- **AFSOC at N≥3 — sustained ISR lane.** Whether AFSOC continues to anchor dow-uap full-Misrep beyond N=2 (third Misrep with 27 SOW or sister SOW; or another SOW under AFSOC) is open. ^[open]
- **Op ENDURING SENTINEL recurrence at N≥2.** d27 anchors first ENDURING SENTINEL in dow-uap corpus. Whether another AFSOC mission under same Operation recurs (firming ENDURING SENTINEL as AFSOC-specific tasking line) is open. ^[open]

## See also

- [[projects/uap/uap]] — project overview.
- [[entities/dow-uap-foia-release]] — release context.
