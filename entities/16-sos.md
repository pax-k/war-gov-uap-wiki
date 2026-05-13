---
title: 16th Special Operations Squadron (16 SOS)
category: entities
tags: [usaf, organization, military, uap, aviation]
aliases: [16 SOS, 16th SOS, 16 Special Operations Squadron, 16th Special Operations Squadron]
sources: [sources/dow-uap-d28-mission-report-east-china-sea-2024.json]
summary: USAF / AFSOC Special Operations Squadron at Cannon AFB NM ^[inferred] under 27 SOW parent. AC-130J Ghostrider gunship ^[inferred — strongly] per 105mm+30mm gun + AGM-176 Griffin + MX-20+MX-25 fit + ARMED OVERWATCH mission type + 7h cycle. First 16 SOS attestation in dow-uap (d28 POC/Originator); third AFSOC SOS in corpus after 33 SOS + 3 SOS — anchors AFSOC SOS-cluster cross-platform at N=3.
provenance:
  extracted: 0.25
  inferred: 0.70
  ambiguous: 0.05
base_confidence: 0.45
lifecycle: draft
lifecycle_changed: 2026-05-13
created: 2026-05-13T20:00:00Z
updated: 2026-05-13T20:00:00Z
---

# 16th Special Operations Squadron (16 SOS)

The **16th Special Operations Squadron** — a USAF squadron under [[entities/afsoc|AFSOC]] (Air Force Special Operations Command), garrisoned at **Cannon AFB, New Mexico** ^[inferred — open-source standard attribution; the wiki's dow-uap d28 OCR names the squadron but not the garrison] and parented by the [[entities/27-sow|27th Special Operations Wing (27 SOW)]]. The 16 SOS is the **AFSOC AC-130J Ghostrider operational squadron** ^[inferred — strongly per d28 weapons fit + sensor fit + mission cycle + ARMED OVERWATCH mission type]. The 16 SOS has a long lineage — it was historically the AC-130H Spectre squadron (Hurlburt Field, FL) before transitioning to AC-130J at Cannon AFB ^[inferred — open-source standard attribution; not in d28 OCR].

This page is a **stub hub**. 16 SOS surfaces in the dow-uap corpus as the **POC Unit + plausibly the Originator (`SOTU 016` ^[ambiguous] OCR variant)** of [[references/dow-uap-d28-mission-iraq-2024-09-20|d28]] — the first AC-130J / first gunship / first ARMED OVERWATCH / first kinetic-weapons-employment Misrep in the corpus.

## Role in the dow-uap corpus

[[references/dow-uap-d28-mission-iraq-2024-09-20|d28]] (20-21 Sep 2024) is the dow-uap corpus's **third AFSOC artifact** and **first AC-130J / first gunship platform**. d28 attributions:

- **POC Unit = `16 SOS`** ^[extracted] (Rank CAPT, Wing 27 SOW, Operations Center "Other")
- **MSGID Originator = `SOTU 016`** ^[extracted; ^[ambiguous] — most parsimonious reading is OCR variant of `16 SOS`, alternative reading is `Special Operations Tactical Unit 016`]
- **POC Wing = 27 SOW** ^[extracted]
- **APPROVER OC = 609 CAOC** ^[extracted] (CENTCOM)

The mission profile:

- **Op INHERENT RESOLVE / ARMED OVERWATCH / 7h 6min mission cycle** ^[extracted] — first OIR AC-130J mission in dow-uap corpus
- **Launched from OKAS Kuwait ^[inferred] → arrived ROZ RAINDROP at Ayn Al Asad Airbase (AAAB) Iraq UTM 38S KC** — first 38S KC sub-square attestation in OIR-Iraq sub-cluster
- **AC-130J ACEQUIP fit** ^[inferred — strongly]:
  - **Guns**: 30mm GAU-23/A Bushmaster + 105mm M102 ^[inferred] (d28 narrative confirms `20x105mm` + `101x30mm` + `1xAGM-176` released; ACEQUIP attests `30MM, 105MM` gun designators)
  - **Air-to-ground weapons**: AGM-176 Griffin (1 released during overwatch) ^[extracted]
  - **TGT Pods**: L3Harris WESCAM **MX-25** + **MX-20** ^[inferred — strongly] (UAP segment text: `IR LENS FLARE ON MX-20 & MX-25`)
  - **IRCM**: AN-AAQ-24 LAIRCM (Large Aircraft Infrared Countermeasures) ^[extracted]
  - **CMD**: ALE-47 chaff/flare dispenser ^[extracted]
  - **MWS**: AAR-47 missile warning system ^[extracted]
  - **Radar**: AN/APN-241 navigation radar ^[extracted]
  - **RWR**: ALR-56M ^[extracted]
  - **Avionics**: GPS/SADL (Situation Awareness Data Link, Link 16-compatible) ^[extracted]
  - **Data Link**: GATEWAY (IF BOTH) ^[extracted] — first GATEWAY-token in dow-uap
- **1X UAP datum at 202027Z** at MGRS `38SKC59...` during PGM shot — UAP flew THROUGH sensor field of view between AGM-176 release and impact; IR lens flare on MX-20 & MX-25 indicating significant heat source; primary + possibly-detaching-secondary morphology; predetermined trajectory; AC-130J at FL130 170 KIAS heading 096° STRAIGHT AND LEVEL ^[extracted]

## Significance for the corpus

- **First 16 SOS attestation in dow-uap full-Misrep class.** d28 introduces the third AFSOC SOS in the corpus after 33 SOS (d25) and 3 SOS (d27). **AFSOC SOS-cluster firms at N=3 cross-platform** within 27 SOW parent wing — first multi-platform AFSOC pattern in dow-uap class ^[inferred]. The MQ-9-platform-attribution ambiguity on 3 SOS / 33 SOS pages **partially resolves** at d28: 16 SOS is **unambiguously AC-130J** (weapons fit + sensor fit + mission cycle + ARMED OVERWATCH leave no MQ-9 reading), anchoring a per-SOS platform-class attribution scheme where 3 SOS + 33 SOS read MQ-9 ^[inferred] and 16 SOS reads AC-130J ^[inferred — strongly].
- **First AC-130J gunship Misrep in dow-uap corpus.** d28 extends platform-class to **3 distinct platforms** (MQ-9 at N=13 + F-15E at N=1 + AC-130J at N=1) ^[inferred]. The 7h 6min mission cycle is consistent with AC-130J ARMED OVERWATCH profile (vs MQ-9 ISR ~20-22h envelope + F-15E DCA ~4-5h envelope) ^[inferred].
- **First ARMED OVERWATCH Mission Type in dow-uap.** 7th distinct Mission Type in corpus after AREC + XCAS/REC\XCAS + RECONNAISSANCE + ARMED RECCE + ISR + DCA + **ARMED OVERWATCH**. ARMED OVERWATCH is the AC-130J Ghostrider's signature mission type (close air support with persistent overwatch + on-call PGM employment) ^[inferred].
- **First kinetic-weapons-employment Misrep in dow-uap.** d28 explicitly attests `HAVING RELEASED 20x105mm, 101x30mm, 1xAGM-176` ^[extracted] — first weapons-release attestation in dow-uap full-Misrep class. All 15 prior full-Misreps (d10-d27 + cluster d60-d65) were ISR/DCA/RECCE with zero weapons employment.
- **First UAP-PGM-shot-coincident encounter in corpus.** UAP transits the live AGM-176 Griffin engagement geometry between weapons release and impact; crew maintained laser energy through UAP transit; AGM-176 impacted intended target; no engagement of the UAP. ^[extracted] First operational-engagement-coincident UAP attestation in dow-uap class ^[inferred].

## Related entities and contexts

- [[entities/27-sow|27th Special Operations Wing (27 SOW)]] — parent wing; recurs at N=3 (d25 + d27 + d28); first multi-platform 27 SOW attestation
- [[entities/afsoc|Air Force Special Operations Command (AFSOC)]] — parent MAJCOM (recurs at N=3); first multi-platform AFSOC attestation in corpus
- [[entities/3-sos|3rd Special Operations Squadron]] — sister AFSOC SOS at d27 (MQ-9 ^[inferred]); same 27 SOW parent
- [[entities/33-sos|33rd Special Operations Squadron]] — sister AFSOC SOS at d25 (MQ-9 ^[inferred]); same 27 SOW parent
- [[entities/609-caoc|609 CAOC / 609 AOC]] — APPROVER OC + executing 609th at d28 (single-COCOM CENTCOM)
- [[entities/ac-130j-ghostrider|AC-130J Ghostrider]] — d28 airframe ^[inferred — strongly]
- [[entities/dow-uap-foia-release]] — release context (Block F #3)
- [[references/dow-uap-d28-mission-iraq-2024-09-20|DoW-UAP-D28]] — sole corpus attestation

## Open threads

- **Cannon AFB garrison anchor.** Open-source standard; not literally stated in dow-uap OCR. ^[open]
- **AC-130J platform attribution.** 16 SOS is unambiguously a gunship squadron per d28 weapons fit (105mm + 30mm + AGM-176) + sensor fit (MX-20 + MX-25) + mission cycle + ARMED OVERWATCH; whether the airframe is specifically AC-130J Ghostrider (vs AC-130W Stinger II) is plausible at high confidence — 16 SOS is the AFSOC AC-130J operational squadron at Cannon AFB per open-source ^[inferred]. ^[open]
- **`SOTU 016` MSGID Originator expansion.** Most parsimonious reading: OCR variant of `16 SOS`. Alternative: `Special Operations Tactical Unit 016` — a distinct AFSOC entity. Resolution at N≥2 SOTU-prefixed Originator attestations ^[ambiguous].
- **16 SOS at N≥2 — sustained AFSOC AC-130J lane.** Whether 16 SOS recurs in dow-uap (firming AC-130J + ARMED OVERWATCH as a sustained AFSOC ISR/CAS pattern) is open ^[open].

## See also

- [[projects/uap/uap]] — project overview.
- [[entities/dow-uap-foia-release]] — release context.
