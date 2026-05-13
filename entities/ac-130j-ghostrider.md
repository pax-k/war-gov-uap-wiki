---
title: AC-130J Ghostrider
category: entities
tags: [usaf, aviation, military, uap]
aliases: [AC-130J, AC-130J Ghostrider, Ghostrider]
sources: [sources/dow-uap-d28-mission-report-east-china-sea-2024.json]
summary: USAF / AFSOC gunship variant of the C-130J Hercules — successor to AC-130H Spectre + AC-130W Stinger II. Signature fit 30mm GAU-23/A Bushmaster + 105mm M102 cannon + AGM-176 Griffin precision-guided munition + L3Harris WESCAM MX-20+MX-25 EO/IR TGT pods ^[inferred]. Flown by 16 SOS / 4 SOS / 73 SOS within 27 SOW + 1 SOW. First AC-130J attestation in dow-uap full-Misrep class at d28 (20-21 Sep 2024 Iraq AAAB) — first gunship / first kinetic-weapons-employment / first ARMED OVERWATCH / first UAP-PGM-shot-coincident encounter in corpus.
provenance:
  extracted: 0.2
  inferred: 0.75
  ambiguous: 0.05
base_confidence: 0.45
lifecycle: draft
lifecycle_changed: 2026-05-13
created: 2026-05-13T20:00:00Z
updated: 2026-05-13T20:00:00Z
---

# AC-130J Ghostrider

The **AC-130J Ghostrider** — the USAF's current-generation gunship, a variant of the **C-130J Super Hercules** with a side-firing weapons suite oriented for close air support, armed overwatch, and air interdiction in support of US Special Operations Forces ^[inferred — open-source standard attribution; the wiki's dow-uap d28 OCR does not name the airframe explicitly but its ACEQUIP signature is unambiguous]. The Ghostrider is operated by [[entities/afsoc|AFSOC]] and is the successor to the **AC-130H Spectre** and **AC-130W Stinger II** ^[inferred]. The AC-130J entered operational service in 2017 ^[inferred — open-source].

This page is a **stub hub**. AC-130J Ghostrider surfaces in the dow-uap corpus as the **airframe of [[references/dow-uap-d28-mission-iraq-2024-09-20|d28]]** ^[inferred — strongly] — the first gunship + first non-MQ-9-non-F-15E platform in the dow-uap full-Misrep class.

## Signature fit and identification

The AC-130J carries a distinct weapons + sensor signature unmistakable from MQ-9 Reaper, F-15E Strike Eagle, or P-8A Poseidon ^[inferred]:

**Gun systems** (side-firing, port side):
- **30mm GAU-23/A Bushmaster** (single-barrel chain gun) ^[inferred — open-source standard AC-130J fit]
- **105mm M102 howitzer** (single-shot cannon) ^[inferred — same]

**Air-to-ground munitions** (palletized launcher or wing pylons):
- **AGM-176 Griffin** (small, laser-guided precision-strike missile) ^[inferred — open-source standard AC-130J fit]
- **GBU-39 SDB** (Small Diameter Bomb) ^[inferred — variant-dependent]
- **GBU-49 Enhanced Paveway II** ^[inferred — variant-dependent]

**Sensor suite**:
- **L3Harris WESCAM MX-20** (long-range, high-resolution multi-spectral targeting/sensor pod) ^[inferred]
- **L3Harris WESCAM MX-25** (paired with MX-20 for multi-axis tracking) ^[inferred]

**Self-protection**:
- **AN/AAQ-24 LAIRCM** (Large Aircraft Infrared Countermeasures) ^[inferred]
- **ALE-47 chaff/flare dispenser** (RR-180 chaff + MJU-71/MJU-66/M206 flares) ^[inferred]
- **AAR-47 missile warning system** ^[inferred]
- **ALR-56M radar warning receiver** ^[inferred]

**Navigation/data**:
- **AN/APN-241** navigation radar ^[inferred]
- **GPS/SADL** (Situation Awareness Data Link, Link 16-compatible) ^[inferred]
- **GATEWAY** data link (d28 explicit token) ^[extracted]

The d28 ACEQUIP block matches this signature byte-for-byte ^[inferred — strongly]. The 30mm + 105mm gun combination + AGM-176 + MX-20/MX-25 fit is **unique to AC-130J Ghostrider and AC-130W Stinger II** within the USAF inventory ^[inferred]; the 16 SOS Originator + 27 SOW parent + Cannon AFB AFSOC garrison strongly favor AC-130J over the older AC-130W ^[inferred]. **Identification: AC-130J Ghostrider** ^[inferred — strongly].

## Role in the dow-uap corpus

[[references/dow-uap-d28-mission-iraq-2024-09-20|d28]] (20-21 Sep 2024) is the dow-uap corpus's **first AC-130J / first gunship platform attestation**.

**Mission profile** ^[extracted]:
- **Operation**: INHERENT RESOLVE ^[extracted]
- **Mission Type**: **ARMED OVERWATCH** ^[extracted] — first ARMED OVERWATCH in dow-uap corpus; AC-130J Ghostrider's signature mission type ^[inferred]
- **Launch base**: OKAS Kuwait ^[inferred] → operational area Ayn Al Asad Airbase (AAAB) ROZ RAINDROP, west Iraq UTM 38S KC
- **Mission cycle**: **7h 6min total / 3h 53min on-station** ^[extracted] — consistent with AC-130J ARMED OVERWATCH profile (vs MQ-9 ISR's ~20-22h envelope and F-15E DCA's ~4-5h envelope) ^[inferred]
- **Weapons employed**: **20x 105mm + 101x 30mm + 1x AGM-176 Griffin** ^[extracted] — first kinetic-weapons-employment Misrep in dow-uap corpus
- **Altitude**: FL130 (~13,000 ft) ^[extracted] — distinct from MQ-9 ISR FL180-FL250 envelope ^[inferred]
- **Speed**: 170 KIAS ^[extracted]
- **Operating squadron**: [[entities/16-sos|16 SOS]] (POC unit + plausible Originator) under [[entities/27-sow|27 SOW]]

**UAP encounter**: 1X UAP at 202027Z **during the active AGM-176 PGM shot sequence** — UAP transited THROUGH the AC-130J's MX-20/MX-25 sensor field between munition release and impact ^[extracted]; the encounter created an **IR lens flare** on both EO/IR sensors, indicating a significant heat source ^[extracted]. The crew maintained laser energy through UAP transit; the AGM-176 impacted its intended target ^[extracted]. UAP morphology: primary + possibly-detaching-secondary object ^[extracted]; trajectory: predetermined and NOT in response to the AC-130J's detection ^[extracted].

## Significance for the corpus

- **First gunship + first non-MQ-9-non-F-15E platform** in the dow-uap full-Misrep class. d28 extends platform-class to **3 distinct platforms** in dow-uap (MQ-9 ISR + F-15E DCA + AC-130J ARMED OVERWATCH) ^[inferred].
- **First UAP-PGM-shot-coincident encounter in dow-uap corpus.** The AC-130J's sensor pod was actively tracking + laser-designating a ground target during AGM-176 release; the UAP transited the active fire-control geometry. First operational-engagement-coincident UAP attestation in dow-uap class ^[inferred]. The IR lens flare signature is characteristic of significant heat source crossing the MX-20/MX-25 sensor field of view ^[inferred].
- **Multi-sensor MX-20 + MX-25 detection geometry.** d28 establishes the **first AC-130J multi-EO/IR-pod-coincident UAP detection** in dow-uap corpus — distinct from MQ-9 ISR's MTS-B family (AN/DAS-1, AN/DAS-4) single-pod detection and F-15E's SNIPER-SE pod ^[inferred]. The MX-20 + MX-25 paired-pod configuration enables multi-axis simultaneous detection that other dow-uap platforms cannot replicate ^[inferred].
- **Kinetic-employment platform + UAP coincidence opens a distinct policy axis** ^[inferred]. The d28 UAP transit occurred during an active live-fire engagement — not a passive ISR encounter. The platform's standard operating posture (armed overwatch with weapons-release authority) makes UAP-class encounters during fire-control sequences a structurally novel observation context within dow-uap.

## Related entities and contexts

- [[entities/16-sos|16th Special Operations Squadron]] — d28 POC unit (AFSOC AC-130J operational squadron at Cannon AFB ^[inferred])
- [[entities/27-sow|27th Special Operations Wing]] — parent wing for 16 SOS at d28
- [[entities/afsoc|Air Force Special Operations Command (AFSOC)]] — operates the AC-130J fleet
- [[entities/mq-9-reaper|MQ-9 Reaper]] — corpus's dominant ISR platform; d28 anchors the structurally distinct gunship parallel
- [[entities/dow-uap-foia-release]] — release context (d28 = Block F #3)
- [[references/dow-uap-d28-mission-iraq-2024-09-20|DoW-UAP-D28]] — sole corpus attestation
- [[concepts/uap-aircraft-engagement]] — sub-class taxonomy; d28 anchors sub-class 16 candidate (PGM-shot-coincident UAP transit)

## Open threads

- **AC-130J vs AC-130W identification.** d28's weapons + sensor fit is consistent with both AC-130J and AC-130W; 16 SOS is the AFSOC AC-130J operational squadron per open-source attribution which favors AC-130J. ^[ambiguous]
- **AC-130J at N≥2 in dow-uap full-Misrep class.** d28 is first AC-130J attestation. Whether AC-130J recurs (firming gunship + ARMED OVERWATCH as a sustained pattern within AFSOC) is open ^[open].
- **Other AFSOC platforms (MC-130, U-28A, CV-22) in dow-uap.** Whether other AFSOC airframes also generate USMTF Misreps within the dow-uap tranche is open ^[open]. d28's AC-130J + d25/d27's plausibly-MQ-9 attribution suggests AFSOC routes multiple airframe classes through the same USMTF Misrep template, suggesting other airframes may also appear in future ingests ^[inferred].
- **Open-source open AC-130J operational basing.** Multiple operational AC-130J squadrons exist (16 SOS, 4 SOS, 73 SOS); d28 attests 16 SOS as POC unit; whether other squadrons recur in dow-uap is open ^[open].
- **PGM-shot-coincident UAP recurrence.** d28 first UAP within active fire-control sequence. Whether subsequent encounters during fire-control occur is open and would strongly anchor sub-class 16 candidate ^[open].

## See also

- [[projects/uap/uap]] — project overview.
- [[entities/dow-uap-foia-release]] — release context.
