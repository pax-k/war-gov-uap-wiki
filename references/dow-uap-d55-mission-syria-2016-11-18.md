---
title: "DoW-UAP-D55 — CTG 67.1 P-8A Possible Missile Observation NW of Latakia, Syria (18 Nov 2016)"
category: references
tags: [uap, primary-source, declassified, military, sighting]
aliases: [DoW-UAP-D55, dow-uap-d55]
sources: [sources/dow-uap-d55-mission-report-syria-november-2016.json]
summary: 1-page Mistral-OCR'd USCENTCOM/CTG-67.1 narrative report (BLUF+Timeline+Weather+Comments) — 18 Nov 2016 1310Z P-8A observation of low-flying object 55 NM NW of Latakia, Syria; CTG assesses as KCTG missile activity. Earliest dated dow-uap artifact in the corpus.
provenance:
  extracted: 0.55
  inferred: 0.40
  ambiguous: 0.05
base_confidence: 0.66
lifecycle: draft
lifecycle_changed: 2026-05-11
created: 2026-05-11T20:45:00Z
updated: 2026-05-11T20:45:00Z
project: uap
---

# DoW-UAP-D55 — CTG 67.1 P-8A Possible Missile Observation NW of Latakia, Syria (18 Nov 2016)

A 1-page Mistral-OCR'd artifact (`sources/dow-uap-d55-mission-report-syria-november-2016.json`, 2,205 bytes; SHA-256 `52634e19…`) — the **ninth artifact overall** and **sixth substantive mission-record ingest** in the [[entities/dow-uap-foia-release|DoW-UAP FOIA release series]]. This is the corpus's **earliest dated dow-uap artifact** (18 Nov 2016) — predating d4/d5/d7 (2020), d54 (undated), d52 (31 Oct 2024), d8 (≥Mar 2024, filename 2025), and d50 (10–11 Apr 2025) by ~3.5 years. d55 is also the corpus's **first non-GENTEXT/UAP mission-record format** — a CTG-67.1 narrative report with explicit `BLUF / Timeline / Weather / CTG Comments` sections rather than the USMTF `GENTEXT/UAP` segment used by all prior mission reports — and the corpus's **first artifact carrying an explicit prosaic-candidate identification in the report body** (the CTG assesses the encounter as standard KCTG missile activity, not a UAP).

## What the source actually contains

The OCR pulls **a single page** (`dpi: 93`, `1023 × 791` pixels). Unlike d4/d5/d7/d54/d8's 5-to-7-page structure with 4-to-6 header-only padding pages, **d55 is a single substantive page** with no `# 1.4(a)` per-page padding — a structural break from the GENTEXT/UAP mission-report template. The page body:

```
SECRET/IREL TO USA, NATO
Declassified by MG Richard A, Harrison
USCENTCOM Chief of Staff
Declassified on: 20 May 2016

# 67.1 P-8A OBSERVES UNIDENTIFIED LOW-FLYING OBJECT 55 NM NORTHWEST OF LATAKIA, SYRIA

18 NOV 2016

**BLUF**: While monitoring KCTG activity in the Eastern Mediterranean, P-8A,
observed an unidentified low-flying object 55 nm northwest of Latakia from an
unknown origin, traveling at approx 500KTS on a southeasterly heading outbound
from KCTG, for ~2 minutes.

## Timeline (Z):

1. (G/REL) 18/1310Z: P-8 observed a possible missile launch IVO 1,4a from an
   origin unknown detected via the EO/IR sensor. The possible missile appeared
   to be in sea skim mode traveling at approximately 500KTS on a southeasterly
   heading outbound from KCTG. P-8 position was 26NM S of object detection at
   16121 FT 1,4a

2. (G/REL) 18/1312Z: P-8 lost visual of the object IVO 1,4a approx. 40 NM
   northwest of Latakia. The missile was observed to pass between (RUS) INGUL
   ARS and 1x U/I vessel.

## Weather:

(U) P-8 aircrew characterized visibility as clear, no range limitations.

**CTG 67.1 Comments**: The mission commander for P-8 characterized the
interaction as safe. While this was the first observed occurrence of possible
missile activity by P-8 aircraft in the Eastern Mediterranean it is assessed
to be standard activity consistent with the assessed activity of the KCTG.
Video footage can be found at this link: (b)(6)

SECRET/IREL TO USA, NATO
USCENTCOM MDR 26-0038 to MDR 26-0046
Approved for Release to AARO
03/27/26 000001
```

Two `img-0.jpeg` and `img-1.jpeg` image blocks are captured (one ~416×123 px at top of page, one ~502×481 px middle-right) — no `image_base64` content (typical of the series' OCR pass). The page also carries no tables or hyperlinks.

The format is a **US Naval-Aviation / 6th Fleet CTG-67.1 narrative report** structured around four named sections:

- **BLUF** (Bottom Line Up Front) — single-paragraph executive summary; standard US military briefing convention. First BLUF in the dow-uap corpus.
- **Timeline (Z)** — numbered chronological events in Zulu time with portion-marking per item (`(G/REL)` = General/Releasable). First explicit numbered-timeline structure in the dow-uap corpus.
- **Weather** — environmental conditions per-aircrew assessment. First weather block in the dow-uap corpus.
- **CTG 67.1 Comments** — mission-commander assessment of the event; here, **an explicit prosaic-candidate identification** as KCTG missile activity. First CTG-commentary block in the dow-uap corpus.

## The encounter datum

| Field | Value | Notes |
|---|---|---|
| Date | **18 Nov 2016** | Explicit calendar date in body — **first explicit body-text calendar date in any dow-uap mission-record artifact** (d4/d5/d7/d8/d54 carry Zulu times only; d52 carries `31 OCT 24`; d50 carries `10APR25` / `11APR25`). |
| Time | **1310Z** (initial observation) → **1312Z** (loss of visual) | UTC, with explicit calendar date — full datetime anchor. Duration **~2 minutes**. |
| Witness platform | **P-8A** (Boeing P-8A Poseidon) | **First explicit platform-type identification** in the dow-uap mission-report corpus. d4 used `PILOT: (b)(6)`; d5 `[REDACTED]`; d7 `1.4(a)` substitution; d54 `14(6)`; d8 `1.4(6)`. d55 names the platform explicitly. |
| Witness mission | **Monitoring KCTG activity in the Eastern Mediterranean** | First explicit mission-objective statement in the dow-uap corpus — the P-8A was on a maritime patrol mission *specifically* tasked with KCTG (Kuznetsov Carrier Task Group) surveillance. |
| Witness position | **26 NM S of object detection at 16,121 FT** | Witness-aircraft position relative-to-object + altitude in feet (raw, not MSL/AGL specified — likely MSL). First relative-bearing-and-range witness anchor. ^[inferred] |
| Object position (initial) | **55 NM NW of Latakia, Syria** | Bearing-and-range from a named coastal landmark — Latakia is the principal Syrian Mediterranean port. **Position decodes to the Eastern Mediterranean coast of Syria.** Explicit theater anchor; **filename token `syria` is internally verifiable**. |
| Object position (final, loss of visual) | **40 NM NW of Latakia** | Object moved closer to Latakia between 1310Z and 1312Z (55→40 NM) — net inbound. ^[inferred] |
| Object heading | **Southeasterly, outbound from KCTG** | Toward the Syrian coast; consistent with KCTG-launched munition heading. ^[inferred] |
| Object altitude | **"Sea skim mode"** — low-flying / surface-skimming | Cruise-missile-class flight profile. First sea-skim-mode kinematic descriptor in the dow-uap corpus. |
| Object velocity | **~500 KTS** | Quantified in knots, attached to the object. Consistent with Russian Kh-35 / Kalibr / Oniks anti-ship cruise missile envelope. ^[inferred] |
| Sensor channel | **EO/IR sensor** | **First explicit EO/IR (Electro-Optical / Infrared) sensor attribution** in the dow-uap corpus. P-8A's standard MX-20HD or similar maritime ISR sensor turret. ^[inferred] |
| Object morphology | *not stated* | The CTG narrative does not describe shape or color — descriptive content limited to kinematic + sensor-channel + transit-path data. |
| Transit feature | **Passed between (RUS) INGUL ARS and 1x U/I vessel** | **First named third-party vessel reference** in the dow-uap corpus. INGUL is a Soviet-design naval auxiliary class; "ARS" is likely the NATO designator for an auxiliary rescue salvage ship — a Russian Black Sea Fleet auxiliary. ^[inferred] U/I = Unidentified. |
| Mission commander assessment | **"Safe interaction"** + **"first observed occurrence of possible missile activity by P-8 aircraft in the Eastern Mediterranean"** + **"assessed to be standard activity consistent with the assessed activity of the KCTG"** | **First explicit prosaic-candidate identification in the dow-uap corpus**: the CTG self-classifies this as conventional Russian missile activity, not a UAP. |
| Video footage | `(b)(6)` redacted link | **First reference to associated video footage** in the dow-uap mission-report corpus — preserved as a redacted link rather than embedded media. |

## Geographic decoding — filename "Syria" is internally verifiable

The internal anchor **"55 NM NW of Latakia, Syria"** decodes to the **Eastern Mediterranean coast of Syria**:

- Latakia is at approximately **35°31'N 35°47'E** on the Syrian Mediterranean coast.
- 55 NM (~102 km) northwest of Latakia places the initial-observation point at approximately **36°15'N 34°55'E** — in the **Eastern Mediterranean Sea**, ~150 km south of Cyprus and ~280 km southeast of the Turkish coast.
- 40 NM NW of Latakia (the loss-of-visual point) decodes to ~36°00'N 35°10'E — still over open water, ~75 km offshore. ^[inferred]

**The filename token `syria` is internally verifiable at the position level** — this is the corpus's **second internally-verifiable filename theater label** (after [[references/dow-uap-d54-mission-mediterranean-sea|d54]]'s "Mediterranean Sea" → Aegean Sea decode). ^[inferred]

The position is also consistent with **the Eastern Mediterranean dominance** observed across the dow-uap internal-coordinate corpus. d55 extends this pattern: **5 of 6 testable substantive ingests** now decode to the broader Eastern Mediterranean Basin (d4 + d5-A + d8 in UTM 34S/35S; d54 in Aegean; **d55 in Eastern Med coast of Syria**), with d5-B in UTM 35T (Eastern Europe / Black Sea margin) as a single transit-mission outlier. The Russian-naval-presence framing in d55 — explicit KCTG surveillance mission + INGUL ARS auxiliary reference — strongly anchors the **Russian-Mediterranean-operations** context that the other mission reports' coordinates point toward but do not name. ^[inferred]

## KCTG — the Kuznetsov Carrier Task Group context

The acronym **KCTG** (introduced 3× in d55 — BLUF + Timeline + CTG Comments) is **first attested in the dow-uap corpus at d55**. The plain-language decode: ^[inferred]

- **K** — Kuznetsov (the Russian Admiral Kuznetsov, Russia's sole aircraft carrier, in service 1990–present)
- **CTG** — Carrier Task Group (US Navy formation designator for a task group built around a carrier as the centerpiece)

Together: **Kuznetsov Carrier Task Group** — the Russian Northern Fleet's deployment task group around the carrier Admiral Kuznetsov.

**November 2016 contextual anchor**: the Admiral Kuznetsov was deployed to the Eastern Mediterranean (deployed from Severomorsk 15 Oct 2016, transit via English Channel + Strait of Gibraltar, on station off the Syrian coast Nov 2016 → Jan 2017) as part of Russia's intervention in the **Syrian Civil War**. The deployment supported Russian Aerospace Forces operations against Syrian opposition forces; Kuznetsov-borne Su-33 + MiG-29K aircraft flew sorties from the carrier. The deployment was the Kuznetsov's first combat deployment. ^[inferred]

The Russian Mediterranean naval presence during this period also included surface combatants (frigates, corvettes) and submarines capable of launching **Kalibr family land-attack and anti-ship cruise missiles**, plus the carrier-based combat aviation. The "possible missile launch" the P-8A observed is therefore plausibly: ^[inferred]

- A **Russian Kalibr / Oniks anti-ship cruise missile** test launch or training shot from a KCTG surface combatant
- A **Kalibr land-attack missile** strike against Syrian opposition targets ashore (operationally documented in 2015–2017)
- A **Kh-35 anti-ship** munition from a Russian surface unit

The 500-kt velocity + sea-skim flight profile + outbound-from-KCTG heading + transit-between-RUS-INGUL-ARS-and-U/I-vessel transit path are **all consistent with a Russian anti-ship cruise missile in mid-flight**. The CTG's assessment that this is *"standard activity consistent with the assessed activity of the KCTG"* is **internally coherent** with the cruise-missile candidate hypothesis. ^[inferred]

## CTG 67.1 — Commander Task Group designator

The phrase **"CTG 67.1"** appears as the title-line prefix (`# 67.1 P-8A OBSERVES…`) and as the section-heading attribution (`**CTG 67.1 Comments**`). The designator decodes:

- **CTG 67** — Commander, Task Group 67 — the US Navy patrol-reconnaissance task group historically responsible for **maritime patrol aviation in the Sixth Fleet AOR (Mediterranean)**. Task Force 67 / Task Group 67.1 has been the Sixth Fleet's organic maritime patrol wing across decades.
- **67.1** — sub-element of CTG 67; in 2016 the operational P-8A maritime-patrol detachment in the Mediterranean was assigned under TF 67.

The report is therefore an **internal US Sixth Fleet / TF 67 maritime patrol report** rather than a CENTCOM or CSG-level product, even though the declassification authority is USCENTCOM-side (see below). ^[inferred] This is the corpus's **first explicitly Sixth-Fleet / EUCOM-AOR / TF-67-anchored mission report** — geographically routed via USCENTCOM (Eastern Mediterranean falls in the seam between EUCOM and CENTCOM AORs and is often handled jointly).

## USCENTCOM declassification anchor

The page-top metadata block:

```
SECRET/IREL TO USA, NATO
Declassified by MG Richard A, Harrison
USCENTCOM Chief of Staff
Declassified on: 20 May 2016
```

**First explicit declassification-authority attribution** in the dow-uap corpus:

- **MG Richard A. Harrison** — US Army Major General; identified as **USCENTCOM Chief of Staff** at the time of declassification. ^[inferred]
- **USCENTCOM** — US Central Command, the geographic combatant command responsible for the Middle East / North Africa / Central Asia AOR. The Syrian theater falls within USCENTCOM AOR; the Eastern Mediterranean is the seam between EUCOM and CENTCOM.
- **Declassified on: 20 May 2016** — this is an **internal contradiction** with the event date (18 Nov 2016): the declassification date is *6 months before* the event it covers. ^[ambiguous] Two readings: (a) OCR error — the year may be `2026` not `2016` (consistent with the page-bottom MDR identifier `26-0038 to 26-0046` and the `03/27/26` release-stamp date, both of which point to 2026 as the declassification year); (b) the date as-OCR'd is correct but applies to a different document the metadata block was lifted from. **Reading (a) is the more probable** — the OCR captured a 2-digit `20 May 26` and rendered it as `20 May 2016`. ^[inferred] If correct, the declassification year is **2026**, consistent with the broader dow-uap release tranche dating ([[references/dow-uap-pr20-prepublication-clearance-2026-03|PR20]] = 10 Mar 2026; d55 release stamp = 27 Mar 2026; d50 release stamp = 27 Mar 2026).

## Release framework — IREL TO USA, NATO + USCENTCOM MDR + AARO routing

The portion marking and release stamps:

- **`SECRET/IREL TO USA, NATO`** — at page top + page bottom. **First "IREL" portion-marking** in the dow-uap corpus — IREL is the US-DoD release-marking for *Intelligence Releasable* (as distinct from REL). The `/IREL TO USA, NATO` formula authorizes release to NATO as an organization, without naming additional national lines (contrast d8's `SECRET/REL TO USA, FIN, SWE, FVEN, NATO` which names individual countries explicitly). ^[inferred]
- **`USCENTCOM MDR 26-0038 to MDR 26-0046`** — **first MDR (Mandatory Declassification Review) case-number reference** in the dow-uap corpus. MDR is a FOIA-adjacent declassification pathway under EO 13526 §3.5 for review of classified records. The range `26-0038 to 26-0046` (9 sequential cases) suggests d55 is part of a multi-document MDR submission rather than a single-case release. ^[inferred] The `26-` prefix is consistent with fiscal-year 2026 case numbering.
- **`Approved for Release to AARO`** — **first explicit AARO routing attribution** in the dow-uap corpus. d55 names [[entities/aaro|AARO]] as the receiving party for the release — closing the long-standing open question on the series-level anchor of *whether AARO is the receiving authority for the dow-uap series*. ^[inferred] If d55's AARO routing generalizes to the rest of the tranche, the dow-uap series is anchored at AARO at the receiving end. See [[entities/dow-uap-foia-release#Open questions]].
- **`03/27/26 000001`** — release-stamp date 27 March 2026 + sequence number `000001`. The `000001` suggests d55 is the **first document in the release sequence**, consistent with its earliest event date (18 Nov 2016) anchoring the chronological start of the tranche. ^[inferred]

## Structural firsts and corpus signal

d55 introduces or anchors the following in the dow-uap corpus (now N=9 ingests):

1. **First non-GENTEXT/UAP mission-record format** — CTG-67.1 narrative report with explicit `BLUF / Timeline (Z) / Weather / CTG Comments` sections. Establishes a **second mission-record document class** alongside the USMTF GENTEXT/UAP template that d4/d5/d7/d54/d8 share. ^[inferred] Working hypothesis: the dow-uap series may carry **at least two distinct mission-record artifact classes** distinguishable by US-military message format (USMTF GENTEXT/UAP vs CTG narrative report). ^[inferred] To be tested against the next non-d* / non-pr* / non-email-correspondence mission-record ingest.
2. **Earliest dated dow-uap artifact** — 18 Nov 2016. Predates d4/d5/d7 (2020) by ~3.5 years; predates d52 (Oct 2024), d8 (Mar 2024 release floor), d50 (Apr 2025) by ~8 years. **Extends the dow-uap corpus's temporal span from 2020–2025 to 2016–2025 (~9 years)**.
3. **First explicit body-text calendar date in any dow-uap mission-record artifact** — `18 NOV 2016`. d4/d5/d7/d8/d54 carry Zulu times without calendar dates; d52 + d50 (email-correspondence class) carry calendar dates in tearlines. d55 is the **first mission-record artifact** to carry an explicit calendar date in the body.
4. **First explicit platform-type identification** — P-8A. The Boeing P-8A Poseidon is the US Navy's primary maritime patrol aircraft (succeeding the P-3 Orion); operated by VP- patrol squadrons. **First Navy-platform anchor** in the dow-uap corpus, and **first non-fighter platform anchor** — supports the prior hypothesis (in [[references/dow-uap-d54-mission-mediterranean-sea|d54]]) that some dow-uap reports may originate from maritime-patrol / ISR platforms.
5. **First explicit prosaic-candidate identification in the report body** — the CTG-67.1 Comments section explicitly identifies the encounter as `"standard activity consistent with the assessed activity of the KCTG"` (Russian Kuznetsov Carrier Task Group missile activity). All prior dow-uap mission reports preserve UAP-class framing without an explicit prosaic identification in the body. d55 inverts this — the *body* of the report says *"this is probably a Russian missile launch"* while the *filename* still tags the artifact `dow-uap-d55`. **The framing mismatch is structural**: an artifact filed in the "DoW-UAP" tranche is internally classified as conventional munition activity. ^[inferred] This suggests the dow-uap series's curator taxonomy is **broader than UAP-narrative-content** — possibly *"observations of unidentified objects, including prosaic-candidate identifications"*. ^[inferred]
6. **First explicit Russian / KCTG attribution** in the dow-uap corpus — the Russian carrier task group (Admiral Kuznetsov Northern Fleet deployment Oct 2016–Jan 2017 to the Eastern Mediterranean during the Syrian intervention) is the named subject of the P-8A's surveillance mission. **First explicit foreign-military-actor attribution** in the corpus.
7. **First explicit AARO routing attribution** — `Approved for Release to AARO` page-bottom stamp. d52/d50/PR20 do not carry this attribution. **Closes the open question** in [[entities/dow-uap-foia-release]] on whether AARO is the receiving authority for the series (^closed-by-dow-uap-d55, assuming d55 generalizes).
8. **First USCENTCOM declassification-authority attribution** — MG Richard A. Harrison, USCENTCOM Chief of Staff. d52/d50/PR20/d4-8/54 do not carry explicit declassification-authority attribution at the artifact level. **First flag-officer name** in the dow-uap corpus.
9. **First "Syria" theater filename internally verified** — `syria` in the filename matches the explicit "northwest of Latakia, Syria" in the body. **Second internally-verifiable filename theater label** in the corpus (after d54's "Mediterranean Sea"). Extends the filename-vs-internal-coordinate analysis: **2-of-2 testable Eastern-Mediterranean-adjacent labels verify** (d54 Mediterranean Sea + d55 Syria), while **4-of-4 testable non-Mediterranean-adjacent labels still mismatch** (d4 + d5-A + d5-B "Arabian Gulf" + d8 "Djibouti"). Working revised hypothesis: **the curator filename theater label is reliable when it names a coastal Mediterranean theater, unreliable when it names an explicitly non-Mediterranean theater**. ^[inferred]
10. **First "sea skim mode" kinematic descriptor** — low-altitude surface-skimming cruise-missile flight-profile vocabulary. Distinct from d4/d5/d7/d8/d54's altitude+velocity quantification format. First explicit *flight-profile-class* descriptor in the corpus.
11. **First explicit EO/IR sensor attribution** — Electro-Optical / Infrared sensor on the P-8A. Distinct from d7's TFLIR + d8's implicit thermal-imagery (WHITE HOT polarity); d55 names the sensor channel explicitly without polarity vocabulary. **The third dow-uap mission report with sensor-channel evidence** (d7 explicit TFLIR + d8 implicit WHITE HOT + d55 explicit EO/IR).
12. **First numbered Zulu-timeline structure** — explicit `(G/REL) 18/1310Z: …` + `(G/REL) 18/1312Z: …` enumerated event sequence. Distinct from the single-Zulu-timestamp single-narrative format of d4/d5/d7/d54/d8. **First multi-event single-sighting record** in the dow-uap corpus — d5 is multi-event multi-sighting; d55 is multi-event single-sighting (initial observation + loss of visual).
13. **First named third-party vessel** — `(RUS) INGUL ARS` (Russian INGUL-class auxiliary rescue salvage ship). First explicit non-US naval-asset reference in the corpus.
14. **First reference to associated video footage** — `Video footage can be found at this link: (b)(6)` is the first preservation of *associated multimedia evidence* in the dow-uap corpus, even though the link itself is redacted.
15. **First MDR (Mandatory Declassification Review) case-number reference** — `USCENTCOM MDR 26-0038 to MDR 26-0046`. **First case-tracking identifier** in the dow-uap corpus, anchoring a 9-case range that may correspond to a multi-document MDR submission.
16. **First "IREL" portion-marking** — `SECRET/IREL TO USA, NATO`. Distinct from d4/d5/d8's `S/REL` family. Extends portion-marking-state count to **five**: `S/REL FVEY` (d4/d5), `SECRET`-only (d7), absent (d54), `S/REL TO USA, FIN, SWE, FVEN, NATO` (d8), `SECRET/IREL TO USA, NATO` (d55).
17. **Smallest dow-uap mission-record OCR by page count** — 1 substantive page vs d4/d5/d7's 5–6, d54/d8's 7. The CTG-narrative format compresses what the GENTEXT/UAP format pads with header-only pages.

## Bibliographic frame

| Field | Value |
|---|---|
| Source basename | `dow-uap-d55-mission-report-syria-november-2016.json` |
| Source bytes | 2,205 |
| OCR engine | `mistral-ocr-latest` (`usage_info.pages_processed: 1`) |
| Original document size | 207,227 bytes (`usage_info.doc_size_bytes`) |
| Pages OCR'd | 1 substantive page (no header-only padding) |
| Image blocks | `img-0.jpeg` (top of page, ~416×123 px) + `img-1.jpeg` (middle-right, ~502×481 px); `image_base64` is null (typical of series OCR pass) |
| Classification (banner) | `SECRET/IREL TO USA, NATO` (page top + page bottom) |
| Classification authority | Not stated — original-classification authority not preserved |
| Declassification authority | **MG Richard A. Harrison, USCENTCOM Chief of Staff** |
| Declassification date | `20 May 2016` (OCR) — almost certainly **20 May 2026** ^[ambiguous] (consistent with `26-`-prefix MDR cases + `03/27/26` release stamp + dow-uap release-tranche dating) |
| Receiving authority | **AARO** (`Approved for Release to AARO`) |
| Release stamp date | 27 March 2026 (page bottom — same date as [[references/dow-uap-d50-email-indopacom-2025-04|d50]]'s release stamp) |
| Release sequence # | `000001` — first document in the release sequence |
| MDR case range | `26-0038 to 26-0046` (9-case range) |
| Message format | **CTG-67.1 narrative report** (BLUF / Timeline / Weather / Comments) — not USMTF GENTEXT/UAP |
| Originating command | **CTG 67.1** (Commander Task Group 67.1; Sixth Fleet maritime patrol detachment) ^[inferred] |
| Witness platform | **P-8A Poseidon** (Boeing maritime patrol aircraft) |
| Series | [[entities/dow-uap-foia-release\|DoW-UAP FOIA release]] |
| Series position | **9-of-40** by ingest order (6th substantive mission-record artifact) |
| Date | **18 Nov 2016** (explicit body-text calendar date — first in the dow-uap mission-record corpus) |
| Theater | **Eastern Mediterranean coast of Syria — internally verified** (55 NM NW of Latakia, decoded to ~36°15'N 34°55'E in the Eastern Mediterranean Sea) |

## Behavioral classification

Per the [[concepts/uap-aircraft-engagement|UAP–Aircraft Engagement]] framework:

- **UAP-toward-aircraft engagement-class**: **no** — the object did not close on the P-8A; the witness aircraft was 26 NM south of object detection and watched a southeastward-transit. No close approach, no co-location, no target switching, no phase-of-flight correlation.
- **Aircraft-toward-UAP engagement-pipeline**: **no** — the P-8A is a maritime patrol aircraft, not a fighter; no weapons-quality track / NTS / TFLIR ID is recorded (the EO/IR sensor track is *observational*, not fire-control-grade). The CTG-Comments characterize the interaction as `"safe"` — no engagement-posture transition.
- **Sub-class within brief-observation**: **prosaic-candidate (positively identified by CTG)** — d55 anchors a **fifth brief-observation sub-class** in the dow-uap corpus: *prosaic-candidate-with-explicit-CTG-identification*. Distinct from d7's *prosaic-candidate-wind-borne-drift* (balloon, no explicit identification posture) — d55 carries an explicit *"this is KCTG missile activity"* call. ^[inferred] The signature is **a UAP-format-report whose body classifies the object as a Russian anti-ship cruise missile**.
- **Cross-class adjacent datum**: d55 is **adjacent to but not within** the engagement-class framework — it documents an *observer-from-the-side* relationship between US maritime-patrol aviation and Russian-naval missile activity, in a context where the observed object is *not* a UAP in the *anomalous-phenomenon* sense.

## The "DoW" prefix — d55 weakens the Navy-originating hypothesis further

[[entities/dow-uap-foia-release]]'s `DoW` prefix-meaning question — open since [[references/dow-uap-pr20-prepublication-clearance-2026-03|PR20]] — receives an additional data point at d55:

- d55 is a **Navy-platform (P-8A) Navy-task-group (TF 67.1) Navy-format (CTG narrative) report** — pulling the prefix toward *Department of the Navy* (DoN).
- BUT d55 also carries **USCENTCOM-side declassification authority** (MG Harrison) and **USCENTCOM MDR case numbers** (`26-00xx`) — pulling the prefix toward *USCENTCOM* or *DoD-tri-service* framing.
- AND d55 carries **AARO routing**, anchoring the receiving authority at a **tri-service OSD office** (AARO sits inside OUSD(I&S) per its charter) — incompatible with a Department-of-Navy-only originating-component reading.

The d55 datum is **mixed**: Navy-originating-content + USCENTCOM-declassification + AARO-receiving. ^[inferred] Working revised view: the **`DoW` prefix is a release-tracking convention** (not a Department-of-Navy code) that aggregates UAP and UAP-adjacent records from multiple originating components (Navy, USAF, joint) under a single AARO-routed release pipeline. d55 supplies the **first Navy-platform internal originating-unit anchor** in the corpus, sitting alongside the three USAF unit anchors (15 AF / DET 1 + 48FW + 12 AF / DET 3). **Multi-service originating-content count is now 4: 3 USAF unit anchors + 1 Navy platform anchor (d55 = P-8A / TF 67.1)** at N=9 ingests. ^[inferred] The series as a whole is now **firmly multi-service**.

## Open questions

- **Validate the CTG-narrative report format** at N≥2 — d55 establishes the format at N=1; the next non-d*-GENTEXT mission-record ingest will confirm or refute whether the CTG format recurs.
- **Recover the underlying classification banner originator** — the page-top banner names the declassification authority (Harrison/USCENTCOM) but not the original-classification authority.
- **Confirm the `20 May 2016` → `20 May 2026` OCR-reading** — almost certainly a 2-digit / 4-digit year-rendering error in the OCR. ^[ambiguous] To be resolved against any other artifact carrying the same MG-Harrison declassification block.
- **Recover the redacted video-footage link** — `(b)(6)` mask. If recoverable, this would be the first multimedia primary-source artifact attached to a dow-uap mission report.
- **Recover the P-8A patrol-squadron designator** — d55 names the platform-type (P-8A) but not the operating squadron / wing / detachment. ^[inferred] At ingest depth N=9, the originating-unit count for Navy-platform reports is 0 (only the platform-type, not the unit, is named).
- **Recover the `(RUS) INGUL ARS`-named vessel** — INGUL is a Soviet-design naval auxiliary class; the specific Russian Black Sea Fleet ship deployed alongside the Kuznetsov CTG in Nov 2016 is recoverable from open-source naval-deployment records but not preserved in the OCR.
- **Validate the AARO-routing pattern** — d55 carries `Approved for Release to AARO`. d50/d52/PR20 do not. Does the AARO-routing stamp recur on every later dow-uap ingest, or only on this earliest one?
- **Validate the "non-GENTEXT/UAP mission-record format" hypothesis** at N≥2 — d55 is the first CTG-narrative format ingest. The next CTG-narrative or non-GENTEXT mission-record ingest will confirm the second format class.
- **Test the prosaic-candidate-in-body pattern** — d55 is the first dow-uap mission report whose body explicitly identifies the object as a prosaic candidate (KCTG missile activity). Does the next mission-record ingest preserve the same explicit-CTG-identification posture, or revert to UAP-class framing without explicit identification?
- **Test the post-Russian-Kuznetsov-deployment hypothesis** — if the Kuznetsov deployment (Oct 2016 – Jan 2017) accounts for d55, are there other dow-uap artifacts dated within the same deployment window in the unread tranche?

## See also

- [[entities/dow-uap-foia-release]] — Series-level anchor (this is the series' 9-of-40 ingest; 6th substantive mission-record artifact; earliest dated dow-uap artifact in the corpus)
- [[references/dow-uap-pr20-prepublication-clearance-2026-03]] — Series prepublication-clearance cover stamp; release-tranche dating anchor
- [[references/dow-uap-d4-mission-arabian-gulf-2020]] — First GENTEXT/UAP mission report; ~3.5 years after d55
- [[references/dow-uap-d5-mission-arabian-gulf-2020]] — Two-sighting GENTEXT/UAP mission report
- [[references/dow-uap-d7-mission-arabian-gulf-2020]] — Form-driven GENTEXT/UAP mission report with TFLIR fire-control engagement-pipeline + 48FW USAF cross-reference
- [[references/dow-uap-d54-mission-mediterranean-sea]] — Triangular-and-metallic GENTEXT/UAP mission report over Aegean Sea; first internally-verifiable filename theater match
- [[references/dow-uap-d8-mission-djibouti-2025]] — Round-white-hot GENTEXT/UAP mission report in Eastern Med (filename "Djibouti"); first FIN+SWE+FVEY+NATO release authorization
- [[references/dow-uap-d52-email-na-2024]] — Email-correspondence tearline clearance thread (15 AF / DET 1)
- [[references/dow-uap-d50-email-indopacom-2025-04]] — Email-correspondence tearline clearance thread (12 AF / DET 3; OUSD(I&S) anchor)
- [[entities/aaro]] — Anti-Anomalous Resolution Office; d55 explicitly routes release to AARO — first explicit AARO-routing attribution in the dow-uap corpus
- [[concepts/uap-aircraft-engagement]] — Behavioral framing; d55 sits in *prosaic-candidate-with-explicit-CTG-identification* sub-class, distinct from d7's prosaic-candidate-wind-borne-drift
- [[concepts/orb-phenomenon]] — Orb-class morphology framing; d55 is morphology-blank
- [[projects/uap/uap]]
