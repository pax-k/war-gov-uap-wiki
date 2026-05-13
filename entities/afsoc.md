---
title: Air Force Special Operations Command (AFSOC)
category: entities
tags: [usaf, organization, military, uap, isr]
aliases: [AFSOC, Air Force Special Operations Command]
sources: [sources/dow-uap-d25-mission-report-greece-january-2024.json, sources/dow-uap-d27-mission-report-united-arab-emirates-october-2023.json, sources/dow-uap-d28-mission-report-east-china-sea-2024.json, sources/dow-uap-d33-mission-report-greece-october-2023.json, sources/dow-uap-d35-mission-report-greece-october-2023.json]
summary: USAF major command for Special Operations Forces (SOF) air component, HQ Hurlburt Field FL ^[inferred]. **AFSOC recurs at N=5** in dow-uap full-Misrep corpus (d33 LGLR→OJMS ferry + d35 LGLR round-trip + d25 LGLR round-trip + d27 OMAM UAE + d28 OKAS/AAAB Iraq) across 11-month window (Oct 2023 → Sep 2024). **AFSOC is now the largest single MAJCOM in dow-uap full-Misrep class** (5-of-17 ≈ 29%, overtaking ACC + AFCENT) ^[inferred]. Cross-squadron AFSOC cluster firms at N=3 cross-platform (33 SOS d33+d35+d25 + 3 SOS d27 + 16 SOS d28 under 27 SOW) — multi-platform AFSOC pattern (MQ-9 ISR d33/d35/d25/d27 ^[inferred] + AC-130J ARMED OVERWATCH d28 ^[inferred — strongly]). **d33 is first AFSOC by event date**; d25 was first by ingest order; d35 anchors the first intra-block same-Originator-chain consecutive-Misrep pair (with d33 in Block B).
provenance:
  extracted: 0.35
  inferred: 0.60
  ambiguous: 0.05
base_confidence: 0.68
lifecycle: draft
lifecycle_changed: 2026-05-13
created: 2026-05-13T12:00:00Z
updated: 2026-05-13T23:30:00Z
---

## [2026-05-13 update] d35 ingest — AFSOC AT N=5 + AFSOC now LARGEST single MAJCOM in dow-uap full-Misrep class + d33+d35 first intra-block consecutive-Misrep pair (Block B at N=2 within AFSOC sub-cluster)

[[references/dow-uap-d35-mission-greece-2023-10-28|DoW-UAP-D35]] (28-29 Oct 2023, Misrep 9337873) brings AFSOC to **N=5 in dow-uap full-Misrep corpus** ^[extracted]. AFSOC is now the **largest single MAJCOM in the class** (5-of-17 ≈ 29%) ^[inferred], decisively overtaking ACC (4) + AFCENT (3) + cluster-blank (6). The 5-doc AFSOC sub-cluster:

| Mission | Event date | Wing/Squadron | Mission Type | Platform ^[inferred] | Block | Launch → Land |
|---|---|---|---|---|---|---|
| **d33** | **26-27 Oct 2023** | 27 SOW / 33 SOS | ISR + ferry | MQ-9 | B (MDR 26-0019) | LGLR → OJMS |
| **d35** | **28-29 Oct 2023** | 27 SOW / 33 SOS | ISR | MQ-9 | **B (MDR 26-0019, SAME packet as d33 byte-for-byte)** | LGLR → LGLR |
| d25 | 25 Jan 2024 | 27 SOW / 33 SOS | ISR | MQ-9 | F (MDR 25-0100 / JS-250710-TM8S) | LGLR → LGLR |
| d27 | 6-7 Jun 2024 | 27 SOW / 3 SOS | ISR | MQ-9 | F (MDR 25-0100 / JS-250710-TM8S) | OMAM → OMAM |
| d28 | 20-21 Sep 2024 | 27 SOW / 16 SOS | ARMED OVERWATCH | AC-130J | F (MDR 25-0100 / JS-250710-TM8S) | OKAS → OKAS via AAAB |

**Structural firsts at d35 ingest**:
- **First intra-block same-Originator-chain consecutive-Misrep pair** within dow-uap (d33 + d35 in Block B, both 33 SOS / 27 SOW / 56 SOIS / LGLR / `MDR 26-0019`) ^closed-by-dow-uap-d35
- **AFSOC LGLR sub-cluster firms at N=3** (d33 + d35 + d25) — all 33 SOS / 27 SOW / 56 SOIS / AN/DAS-4 / GET FMV exploitation / 603rd executing
- **AFSOC cross-block** firms at N=2 (Block B d33+d35 = 2/5 + Block F d25+d27+d28 = 3/5; AFSOC operates across both block conventions)
- **First explicit unredacted Air-to-Ground Weapons load in dow-uap corpus** within AFSOC sub-cluster: d35 carries `2XAGM-114R9E 2XAGM-114R2` (4 Hellfire missiles total) ^[extracted]

## [2026-05-13 update] d33 ingest — AFSOC AT N=4 + d33 PRECEDES d25 as event-date-first AFSOC + LGLR Greece launch at N=2 + 33 SOS at N=2 + cross-AOR ferry first attestation

[[references/dow-uap-d33-mission-greece-2023-10-26|DoW-UAP-D33]] (26-27 Oct 2023) carries `MAJCOM: AFSOC` ^[extracted] — **fourth AFSOC attestation** in dow-uap full-Misrep corpus, and **first AFSOC attestation by event date** (~91 days before d25's 25 Jan 2024 mission). AFSOC now recurs at N=4 within an 11-month event-date window (Oct 2023 → Sep 2024):

| Mission | Event date | Launch → Land | Wing/Squadron | Mission Type | Platform ^[inferred] | Block |
|---|---|---|---|---|---|---|
| **d33** | **26-27 Oct 2023** | **LGLR Greece → OJMS Jordan (cross-AOR ferry)** | **27 SOW / 33 SOS / 56 SOIS** | **ISR + ferry** | **MQ-9 Reaper** | **B (MDR 26-0019)** |
| d25 | 25 Jan 2024 | LGLR Greece → LGLR Greece (round-trip) | 27 SOW / 33 SOS / 56 SOIS | ISR | MQ-9 Reaper | F (MDR 25-0100..0103 / JS-250710-TM8S) |
| d27 | 6-7 Jun 2024 | OMAM UAE → OMAM UAE (round-trip; WX-RTB) | 27 SOW / 3 SOS / 56 SOIS | ISR | MQ-9 Reaper | F (MDR 25-0100..0103 / JS-250710-TM8S) |
| d28 | 20-21 Sep 2024 | OKAS Kuwait ^[inferred] → OKAS Kuwait (round-trip via AAAB) | 27 SOW / 16 SOS / 1 SOW QC | ARMED OVERWATCH | AC-130J Ghostrider ^[inferred — strongly] | F (MDR 25-0100..0103 / JS-250710-TM8S) |

**MAJCOM histogram refines** at d33 ingest across 15 mission-records: ACC 4 + AFCENT 3 + **AFSOC 4** + cluster-blank 6. 432-AEW MQ-9 ISR share refines to **12-of-16 = ~75%** within MQ-9 ISR + AC-130J subset.

**Framing refinement** ^closed-by-dow-uap-d33: d33 is **first AFSOC by event date**; d25 was **first AFSOC by ingest order**. The d25-anchored "FIRST AFSOC" + "FIRST 27 SOW" + "FIRST 33 SOS" + "FIRST 56 SOIS" + "FIRST Greece" + "FIRST LGLR" + "FIRST cross-MAJCOM-EUCOM-launched-CENTCOM-tasked" headlines all retro-shift: d25 retains the ingest-order-first qualifier; d33 carries the event-date-first qualifier.

**d33 anchors the AFSOC LGLR-OJMS rotational two-base sub-cluster** ^closed-by-dow-uap-d33 (anchoring class). Narrative explicitly attests `TRANSITED AND LANDING AT OJMS TO REPLACE THE LIGHTNING LINE THAT LANDED AT LGLR YESTERDAY` ^[extracted] — first cross-AOR ferry/repositioning mission in dow-uap. The LGLR ↔ OJMS lane covers both **single-direction ferry** (d33) + **round-trip ISR** (d25) variants within ~3 months under the same 33 SOS / 27 SOW Originator chain.

**Block recurrence**: d33 carries **Block B** (`MDR 26-0019`), distinct from d25 + d27 + d28's Block F. **AFSOC routes Misreps through multiple release blocks** ^closed-by-dow-uap-d33 (firming class). At d33 ingest: AFSOC class spans **Block B (d33) + Block F (d25 + d27 + d28)** — first cross-block AFSOC routing in dow-uap; AFSOC's release-block-attestation count is **2-of-22 release-block-testable artifacts at cross-block AFSOC routing** ^[inferred].

# Air Force Special Operations Command (AFSOC)

**AFSOC** — the USAF's **major command for Special Operations Forces (SOF) air component**, headquartered at **Hurlburt Field, Florida** ^[inferred — open-source standard attribution; the wiki's dow-uap d25 OCR names AFSOC as MAJCOM but not its HQ]. AFSOC provides the Air Force component of [[entities/socom|USSOCOM]] ^[inferred] and operates a diverse SOF air arsenal including MQ-9 Reaper (in SOS-designated squadrons), AC-130 gunships, MC-130 special operations transports, U-28A intelligence aircraft, and CV-22 tiltrotors ^[inferred].

This page is a **stub hub**. AFSOC's significance in the dow-uap corpus rests on the **d25 + d27 + d28 attestations as MAJCOM at N=3** — the first three non-ACC, non-AFCENT MAJCOM attestations in the dow-uap full-Misrep mission-record class. d28 extends AFSOC to **multi-platform** (MQ-9 ISR d25/d27 ^[inferred] + AC-130J ARMED OVERWATCH d28 ^[inferred — strongly]).

## Role in the dow-uap corpus

AFSOC recurs at N=3 in dow-uap full-Misrep class:

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
- **Platform = MQ-9 Reaper** ^[inferred]
- **Mission Type = ISR** ^[extracted]
- **Cross-OC topology**: single-COCOM CENTCOM 4-role chain (609 CAOC POC + 609 AOC Det 1 QC + 379 AEW APPROVER at 609 CAOC + 609th executing) — no EUCOM bridge

### d28 — Iraq AAAB (20-21 Sep 2024)

- **MAJCOM = `AFSOC`** ^[extracted]
- **Wing = [[entities/27-sow|27 SOW]]** (POC; recurs at N=3) + **`1 SOW`** (QC — first 1 SOW attestation in dow-uap, AFSOC's other principal operational wing at Hurlburt Field FL ^[inferred])
- **POC Unit = [[entities/16-sos|16 SOS]]** (3rd Special Operations Squadron — first 16 SOS attestation; **AFSOC AC-130J operational squadron** at Cannon AFB ^[inferred — strongly])
- **Originator = `SOTU 016`** ^[extracted; ^[ambiguous] — most parsimonious reading is OCR variant of `16 SOS`]
- **COCOM = USCENTCOM** ^[extracted] — same-AOR routing (CENTCOM-launched + CENTCOM-tasked)
- **Launch base = OKAS Kuwait** ^[inferred] (Ali Al Salem AB Kuwait) → operational range **AAAB ROZ RAINDROP** (Ayn Al Asad Airbase Iraq UTM 38S KC)
- **Platform = [[entities/ac-130j-ghostrider|AC-130J Ghostrider]]** ^[inferred — strongly] per 105mm + 30mm + AGM-176 + MX-20/MX-25 fit
- **Mission Type = ARMED OVERWATCH** ^[extracted] — first ARMED OVERWATCH in dow-uap corpus
- **Cross-OC topology**: single-COCOM CENTCOM 4-role chain (POC `Other` + QC `Other` + APPROVER 379 AEW at 609 CAOC + 609th executing); the `Other` OC token at POC + QC may indicate AFSOC-internal OC routing distinct from 609 CAOC ^[inferred]

## Significance for the corpus

- **AFSOC recurs at N=3 cross-squadron + cross-launch-base + cross-COCOM-tasking + cross-platform** ^closed-by-dow-uap-d28 (firming class on d27-anchored "AFSOC at N≥3 — sustained ISR lane" open thread). d25 (33 SOS LGLR MQ-9 ISR cross-AOR) + d27 (3 SOS OMAM MQ-9 ISR same-AOR) + d28 (16 SOS OKAS/AAAB **AC-130J ARMED OVERWATCH** same-AOR) firms AFSOC as a **sustained multi-platform ISR/CAS lane** within dow-uap full-Misrep class.
- **First multi-platform AFSOC attestation in dow-uap.** d28 extends AFSOC class beyond MQ-9 ISR to **AC-130J ARMED OVERWATCH** — first non-MQ-9 AFSOC platform attestation in dow-uap class. The AFSOC SOS-cluster firms at N=3 cross-platform: 33 SOS (MQ-9 ^[inferred]) + 3 SOS (MQ-9 ^[inferred]) + **16 SOS (AC-130J ^[inferred — strongly])**. Per-SOS platform-class attribution scheme anchored ^[inferred].
- **MAJCOM histogram refines.** At d28 ingest, MAJCOM histogram across 14 mission-records (d10/d12/d14/d16/d18/d19/d23/d25/d27/d28 + cluster 6): **ACC 4 + AFCENT 3 + AFSOC 3 (d25 + d27 + d28) + (cluster-era blank/unattested) 6**. ^[inferred]
- **Cross-MAJCOM routing under unified Joint Staff release pipeline firms at N=10.** d25 + d27 + d28 share `JS-250710-TM8S` Joint Staff tracking-ID with Block D (d10/d12/d14/d16/d18/d19 — 6) + Block E (d23 — 1) + Block F (d25/d27/d28 — 3). At **N=10 byte-for-byte JS-ID attestations**, the unified Joint Staff release pipeline **aggregates across at least 3 MAJCOMs (ACC + AFCENT + AFSOC), 2 COCOMs (CENTCOM + EUCOM), and 3 platforms (MQ-9 + F-15E + AC-130J)** ^closed-by-dow-uap-d28 (firming class).
- **AFSOC organic ISR/CAS posture distinct from ACC/AFCENT-routed 432 AEW firms at N=3.** AFSOC's command structure routes Misreps through the same USMTF Misrep parent class under the same Joint Staff routing, but anchors a structurally distinct multi-platform pool (27 SOW / 33 SOS / 3 SOS / 16 SOS / 56 SOIS / 1 SOW QC) parallel to the corpus's prior-dominant 432 AEW pool ^[inferred]. The 432 AEW MQ-9 ISR share refines to **12-of-15 = ~80%** within MQ-9 ISR + AC-130J subset at d28 ingest (was ~86% at d27 ingest).
- **AFSOC OPERATES FROM EUCOM AOR (LGLR Greece) + CENTCOM AOR (OMAM UAE + OKAS Kuwait) WITHIN 8 MONTHS.** Cross-AOR launch-base attestation refines at AFSOC class ^[inferred]. AFSOC's organic ISR/CAS lane is **not lane-locked at single launch base or single AOR or single platform** — operates flexibly across USEUCOM + USCENTCOM AOR launch bases under USCENTCOM tasking authority with both MQ-9 ISR and AC-130J ARMED OVERWATCH platforms ^[inferred].
- **First UAP-during-active-PGM-engagement attestation in dow-uap class.** d28 anchors the first AFSOC-platform UAP encounter that intersects an active fire-control / laser-designation sequence ^[inferred] — adds a structurally novel observation context within dow-uap (vs prior 15 full-Misreps which were all ISR/DCA/RECCE).

## Related entities and contexts

- [[entities/27-sow|27th Special Operations Wing]] — primary AFSOC wing at d25 + d27 + d28; recurs at N=3.
- [[entities/33-sos|33rd Special Operations Squadron]] — AFSOC MQ-9 SOS at d25; sister to 3 SOS + 16 SOS.
- [[entities/3-sos|3rd Special Operations Squadron]] — AFSOC MQ-9 SOS at d27 ^[inferred]; sister to 33 SOS + 16 SOS.
- [[entities/16-sos|16th Special Operations Squadron]] — AFSOC AC-130J SOS at d28 ^[inferred — strongly]; sister to 33 SOS + 3 SOS within 27 SOW.
- [[entities/ac-130j-ghostrider|AC-130J Ghostrider]] — d28 airframe ^[inferred — strongly]; first non-MQ-9 AFSOC platform in dow-uap.
- [[entities/603-aoc|603 AOC]] — AFSOC mission-routed through 603 AOC APPROVER at d25; absent at d27 + d28 (single-COCOM CENTCOM).
- [[entities/609-caoc|609 CAOC / 609 AOC]] — AFSOC mission's CENTCOM OC backbone; 609 AOC Det 1 recurs cross-role; d28 APPROVER OC + executing 609th.
- [[entities/432-aew|432d Air Expeditionary Wing (432 AEW)]] — ACC/AFCENT-routed parallel MQ-9 ISR pool; share refines to ~80% within MQ-9 ISR + AC-130J subset at d28 ingest.
- [[entities/usaf|USAF]] — parent service.
- [[entities/mq-9-reaper|MQ-9 Reaper]] — d25 + d27 airframe ^[inferred]; complementary to d28 AC-130J.
- [[entities/dow-uap-foia-release]] — release context (Block F recurs at N=3).
- [[references/dow-uap-d33-mission-greece-2023-10-26|DoW-UAP-D33]] — **first AFSOC attestation by event date** (26-27 Oct 2023); first cross-AOR ferry mission (LGLR → OJMS); Block B class (vs Block F at d25/d27/d28).
- [[references/dow-uap-d25-mission-greece-2024-01-25|DoW-UAP-D25]] — first AFSOC attestation by ingest order.
- [[references/dow-uap-d27-mission-uae-2024-06-06|DoW-UAP-D27]] — second AFSOC attestation by ingest order; first CENTCOM-AOR-launched AFSOC mission.
- [[references/dow-uap-d28-mission-iraq-2024-09-20|DoW-UAP-D28]] — third AFSOC attestation by ingest order; first multi-platform AFSOC + first AC-130J / first gunship / first ARMED OVERWATCH / first kinetic-weapons-employment + first PGM-coincident UAP in dow-uap.

## Open threads

- **Hurlburt Field HQ anchor.** Open-source standard; not literally stated in dow-uap OCR. ^[open]
- ~~**AFSOC mission-record cluster at N≥2.**~~ ^closed-by-dow-uap-d27 — AFSOC recurs at N=2 cross-squadron (33 SOS + 3 SOS) + cross-launch-base (LGLR + OMAM) + cross-AOR launch (EUCOM AOR + CENTCOM AOR); parallel ISR posture firms.
- ~~**AFSOC at N≥3 — sustained ISR lane.**~~ ^closed-by-dow-uap-d28 — AFSOC recurs at N=3 cross-squadron (33 SOS + 3 SOS + 16 SOS) + cross-launch-base (LGLR + OMAM + OKAS/AAAB) + cross-platform (MQ-9 ISR d25/d27 + AC-130J ARMED OVERWATCH d28) + cross-Mission-Type (ISR + ARMED OVERWATCH); sustained multi-platform ISR/CAS posture firms.
- **AFSOC-to-USSOCOM joint operations attribution.** AFSOC operates as USAF component of USSOCOM. Whether d25/d27/d28 tasking is USSOCOM-routed JTF-engaged or pure-AFSOC-organic is not resolved in OCR (d25 Operation field redacted; d27 Operation = ENDURING SENTINEL; d28 Operation = INHERENT RESOLVE — same OIR umbrella as ACC/AFCENT-routed d10-d18 + d19 missions, suggesting AFSOC tasking flows through COCOM-driven joint-operation routing rather than AFSOC-organic ^[inferred]). ^[ambiguous]
- ~~**AFSOC at N≥4 — sustained multi-platform ISR/CAS lane.**~~ ^closed-by-dow-uap-d33 — AFSOC recurs at N=4 (d33 ferry + d25 round-trip + d27 round-trip + d28 ARMED OVERWATCH); d33 is first AFSOC by event date; cross-block routing firms (Block B + Block F); LGLR Greece at N=2; 33 SOS at N=2; 27 SOW at N=4.
- **AFSOC at N≥5 — sustained multi-platform multi-block ISR/CAS lane.** Whether AFSOC continues to anchor dow-uap full-Misrep beyond N=4 (fifth Misrep with 27 SOW or sister wing; MC-130 / U-28A / CV-22 Misreps; another LIGHTNING-LINE rotation mission) is open. ^[open]
- **Op ENDURING SENTINEL recurrence at N≥2.** d27 anchors first ENDURING SENTINEL in dow-uap corpus; d28 reverts to OIR. Whether ENDURING SENTINEL recurs (firming as a sustained AFSOC-tasking line) is open. ^[open]
- **Per-SOS platform-class attribution scheme firmness.** d28 anchors `16 SOS = AC-130J ^[inferred — strongly]` against d25/d27's `33 SOS / 3 SOS = MQ-9 ^[inferred]`. Whether this scheme holds at N≥4 across additional AFSOC SOS attestations is open ^[open].

## See also

- [[projects/uap/uap]] — project overview.
- [[entities/dow-uap-foia-release]] — release context.
