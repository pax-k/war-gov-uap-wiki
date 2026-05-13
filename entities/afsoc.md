---
title: Air Force Special Operations Command (AFSOC)
category: entities
tags: [usaf, organization, military, uap, isr]
aliases: [AFSOC, Air Force Special Operations Command]
sources: [sources/dow-uap-d25-mission-report-greece-january-2024.json]
summary: USAF major command for Special Operations Forces (SOF) air component, HQ Hurlburt Field FL ^[inferred]. First AFSOC MAJCOM attestation in the dow-uap full-Misrep corpus (d25); fifth distinct USAF MAJCOM after ACC + AFCENT + (cluster-era blank) + (composite/ANG categories).
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

# Air Force Special Operations Command (AFSOC)

**AFSOC** — the USAF's **major command for Special Operations Forces (SOF) air component**, headquartered at **Hurlburt Field, Florida** ^[inferred — open-source standard attribution; the wiki's dow-uap d25 OCR names AFSOC as MAJCOM but not its HQ]. AFSOC provides the Air Force component of [[entities/socom|USSOCOM]] ^[inferred] and operates a diverse SOF air arsenal including MQ-9 Reaper (in SOS-designated squadrons), AC-130 gunships, MC-130 special operations transports, U-28A intelligence aircraft, and CV-22 tiltrotors ^[inferred].

This page is a **stub hub**. AFSOC's significance in the dow-uap corpus rests on the **d25 attestation as MAJCOM** — the first non-ACC, non-AFCENT MAJCOM in the dow-uap full-Misrep mission-record class.

## Role in the dow-uap corpus

[[references/dow-uap-d25-mission-greece-2024-01-25|d25]] (25 Jan 2024) is the dow-uap corpus's first AFSOC artifact:

- **MAJCOM = `AFSOC`** ^[extracted] — first AFSOC attestation in any full-Misrep
- **Wing = [[entities/27-sow|27 SOW]]** (27th Special Operations Wing, Cannon AFB NM ^[inferred])
- **Originator = [[entities/33-sos|33 SOS]]** (33rd Special Operations Squadron — MQ-9 SOS ^[inferred])
- **POC Unit = 56 SOIS** (56th Special Operations Intelligence Squadron ^[inferred])
- **COCOM = USCENTCOM** ^[extracted] — AFSOC supports USCENTCOM tasking via cross-MAJCOM routing
- **Launch base = Larissa AB (LGLR), Greece** — geographically USEUCOM AOR

## Significance for the corpus

- **First MAJCOM distinct from ACC + AFCENT in dow-uap full-Misrep class.** At d25 ingest, MAJCOM histogram across 14 mission-records (d10/d12/d14/d16/d18/d19/d23/d25 + cluster 6): **ACC 4 + AFCENT 3 + AFSOC 1 (d25) + (cluster-era blank/unattested) 6**. ^[inferred]
- **Cross-MAJCOM routing under unified Joint Staff release pipeline.** d25's AFSOC MAJCOM + USCENTCOM COCOM + 603rd executing + 609 AOC Det 1 POC home + 603 AOC APPROVER combine to anchor a **bidirectional cross-COCOM 3-OC chain** in a single mission. The `JS-250710-TM8S` Joint Staff tracking-ID continues across Block D + E + F (d10-d25) — confirming **the unified Joint Staff release pipeline aggregates across MAJCOMs and COCOMs at corpus level** ^[inferred].
- **AFSOC organic ISR-strike posture distinct from ACC/AFCENT-routed 432 AEW.** AFSOC's command structure routes Misreps through the same USMTF Misrep parent class under the same Joint Staff routing, but anchors a structurally distinct MQ-9 ISR pool (27 SOW / 33 SOS / 56 SOIS) parallel to the corpus's prior-dominant 432 AEW pool ^[inferred].
- **MAJCOM-as-cross-COCOM-tasking-pivot vs MAJCOM-as-theater-tasking-pivot.** Where d10 (AFCENT) anchored MAJCOM = theater-OIR-tasking-MAJCOM and d14 (ACC) anchored MAJCOM = wing-owning-MAJCOM, d25 anchors MAJCOM = **AFSOC organic-SOF-air-component MAJCOM** — orthogonal to both theater-tasking and wing-owning axes. ^[inferred]

## Related entities and contexts

- [[entities/27-sow|27th Special Operations Wing]] — primary AFSOC wing at d25.
- [[entities/33-sos|33rd Special Operations Squadron]] — AFSOC MQ-9 SOS at d25.
- [[entities/603-aoc|603 AOC]] — AFSOC mission-routed through 603 AOC APPROVER at d25.
- [[entities/609-caoc|609 CAOC / 609 AOC]] — AFSOC mission's CENTCOM POC home OC at d25 (via Det 1).
- [[entities/432-aew|432d Air Expeditionary Wing (432 AEW)]] — ACC/AFCENT-routed parallel MQ-9 ISR pool.
- [[entities/usaf|USAF]] — parent service.
- [[entities/mq-9-reaper|MQ-9 Reaper]] — d25 airframe ^[inferred].
- [[entities/dow-uap-foia-release]] — release context (Block F).
- [[references/dow-uap-d25-mission-greece-2024-01-25|DoW-UAP-D25]] — sole corpus attestation.

## Open threads

- **Hurlburt Field HQ anchor.** Open-source standard; not literally stated in dow-uap OCR. ^[open]
- **AFSOC mission-record cluster at N≥2.** d25 anchors AFSOC at N=1. Recurrence in dow-uap corpus (another AFSOC Misrep) would firm AFSOC's parallel ISR posture at corpus level. ^[open]
- **AFSOC-to-USSOCOM joint operations attribution.** AFSOC operates as USAF component of USSOCOM. Whether d25's tasking is USSOCOM-routed JTF-engaged or pure-AFSOC-organic is not resolved in OCR (Operation field redacted). ^[ambiguous]

## See also

- [[projects/uap/uap]] — project overview.
- [[entities/dow-uap-foia-release]] — release context.
