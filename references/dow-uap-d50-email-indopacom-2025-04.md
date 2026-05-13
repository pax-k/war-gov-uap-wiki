---
title: "DoW-UAP-D50 — Tear-Line Clearance Email Thread (12 AF / DET 3, INDOPACOM AOR, 10–11 Apr 2025 sightings)"
category: references
tags: [uap, primary-source, declassified, usaf, sighting]
aliases: [DoW-UAP-D50, dow-uap-d50, dow-uap-d50-email]
sources: [sources/dow-uap-d50-email-correspondence-indopacom-april-2025.json]
summary: 2-page Mistral-OCR'd intra-DoD email thread negotiating UNCLASS tear-line classification + AOR INDOPACOM approval for 10–11 Apr 2025 USAF UAP sightings; PAROL Intel Data Analysis Technician (12 AF / DET 3) ↔ OUSD(I&S) Information Disclosure Analyst.
event_date: 2025-04-10
provenance:
  extracted: 0.50
  inferred: 0.47
  ambiguous: 0.03
base_confidence: 0.65
lifecycle: draft
lifecycle_changed: 2026-05-11
created: 2026-05-11T20:30:00Z
updated: 2026-05-11T20:30:00Z
---

# DoW-UAP-D50 — Tear-Line Clearance Email Thread (12 AF / DET 3, INDOPACOM AOR, 10–11 Apr 2025 sightings)

A 2-OCR-page Mistral-OCR'd artifact (`sources/dow-uap-d50-email-correspondence-indopacom-april-2025.json`, 2,034 bytes; SHA-256 `3be6a437…`) — **the second non-mission-report and second email-correspondence ingest** of the [[entities/dow-uap-foia-release|DoW-UAP FOIA release series]], **confirming the email-correspondence document class at N=2** after [[references/dow-uap-d52-email-na-2024|D52]]. The artifact is an **intra-DoD email thread** between a **PAROL Intel Data Analysis Technician at 12 AF / DET 3** and an **Information Disclosure Analyst inside the Office of the Undersecretary of Defense for Intelligence and Security (OUSD(I&S))**, negotiating **UNCLASS tear-line classification** + **AOR INDOPACOM** approval for two consecutive sightings on **10 APR 25** and **11 APR 25**.

The artifact is **metadata about the declassification process**, not a UAP narrative. Its substantive value at the series level is fivefold: (1) **confirms the email-correspondence class** structurally at N=2 (same dual-banner SECRET//NOFORN + UNCLASS tearline, same two-role workflow, same `(b)(6)` correspondent redaction); (2) **third USAF unit anchor** in the series — `12 AF / DET 3` (Twelfth Air Force, Detachment 3) ^[inferred], adding to d52's `15 AF / DET 1` and d7's `48FW` cross-reference and strengthening the multi-service / no-internal-Navy-anchor pattern at N=8 ingests; (3) **names OUSD(I&S) as the disclosure-review office** — a substantive partial-closure of d52's open question about where the *Information Disclosure Analyst* role sits within the DoD disclosure pipeline; (4) **first internally-verifiable filename in the email-correspondence class on both date and theater axes** — `april-2025` matches internal `10APR25`/`11APR25`, and `indopacom` matches internal `AOR INDOPACOM`; (5) **confirms the canonical UNCLASS tearline template** ("US AIRCRAFT OBSERVED [N]X POSS UAP FOR [N] SECONDS AT [Z]") at N=2.

## What the source contains

Two OCR pages totaling ~24 lines of substantive text plus two images on page 1 (`img-0.jpeg`, `img-1.jpeg`) for which **base64 content is null** in the JSON — the images themselves are not recoverable, only their bounding boxes (likely DoD letterhead banners or classification stamps rendered as graphics).

The thread spans **three emails reverse-chronologically ordered** on page 0 (newest reply on top, oldest request on bottom) plus a **fourth follow-up clarification email** on page 1.

### Email 1 (oldest — bottom of page 0)

```
CLASSIFICATION: SECRET//NOFORN

Hello,

Per our conversation, can you please confirm that the 4(a) tearlines
below are at the UNCLASSIFIED level? Also, could you please confirm
that we can use the AOR INDOPACOM.

Thank you.

(b) (6)
```

An initial request from the (b)(6)-redacted sender — context establishes this is the PAROL Intel Data Analysis Technician (see Email 3) — asking the Information Disclosure Analyst to **confirm both the tearline classification and the AOR designator**. The `4(a)` token plausibly references **EO 13526 §1.4(a)** ("military plans, weapons systems, or operations") ^[ambiguous] — the same classification category that anchors the per-page header on the substantive `d*` mission reports ([[entities/dow-uap-foia-release#Mission-report format (template anchored by `d4`, validated + extended by `d5`, revised by `d7`, extended by `d54`, extended by `d8`)|series-level mission-report template]]). An alternative reading — `4(a)` as an asset/platform code rather than an EO citation — is consistent with the later phrase "the unit that flies 4(a)" (Email 2). Both readings are live; this artifact does not disambiguate. ^[ambiguous]

### Email 2 (middle — top of page 0)

```
1

(b) (6)

I just got off the phone with the unit that flies 4(a). They said to
me that the two lines listed are on the UNCLASSIFIED level and that
adding in the AOR as INDOPACOM is also at the UNCLASSIFIED level.

(b) (6)

PAROL Intel Data Analysis Technician
Team Lead
12 AF / DET 3
```

A reply from the **PAROL Intel Data Analysis Technician, Team Lead, 12 AF / DET 3** — reporting that "the unit that flies 4(a)" (a third party not directly visible in the thread) has confirmed both **the two tearline lines** and **the AOR INDOPACOM addition** are at the UNCLASSIFIED level. This establishes a **three-actor pre-terminal disclosure-clearance loop** in the email-correspondence class: (a) the **PAROL Intel Data Analysis Technician** (data originator, 12 AF / DET 3) — same role-name as d52's *PAROC Intel Data Analysis Technician* at 15 AF / DET 1; (b) the **Information Disclosure Analyst** (clearance reviewer, OUSD(I&S) per Email 3); and (c) **the unit that flies 4(a)** (third-party authority on what its own observations may be released at unclassified level) ^[inferred] — a new role not seen in d52. The d52 thread captured a two-actor loop only; d50 reveals the three-actor variant with the originating-asset unit as a third clearance gate.

### Email 3 (newest — top of page 1, with the answer rendered as tearlines)

```
CLASSIFICATION: SECRET//NOFORN

Hello,

I wanted to clarify that these tearlines are approved at the
UNCLASSIFIED level.

1.2(a) on 10APR25

//UNCLASSIFIED//

US AIRCRAFT OBSERVED 1X POSS UAP FOR 12 SECONDS AT 2353Z, FLYING AT
UNK ALTITUDE AND UNK SPEED, NO INTERFERENCE WAS NOTED.

//UNCLASSIFIED//

1.2(a) on 11APR25

//UNCLASSIFIED//

US AIRCRAFT OBSERVED 1X POSS UAP FOR 23 SECONDS AT 0007Z, FLYING AT
UNK ALTITUDE AND UNK SPEED, NO INTERFERENCE WAS NOTED.

//UNCLASSIFIED//

Thank you,

(b) (6)

Information Disclosure Analyst

Office of the Undersecretary of Defense for Intelligence and Security
```

The terminal clarification from the **Information Disclosure Analyst at OUSD(I&S)** — delivering the **approved UNCLASS tearlines** for both 10 APR 25 and 11 APR 25 events. The token `1.2(a)` prefixes each tearline. Two candidate readings: (i) reference to **EO 13526 §1.2(a) (TOP SECRET)** — implausible since the tearline content itself is marked `//UNCLASSIFIED//`; (ii) an internal document-paragraph numbering convention specific to the parent mission report (paragraph 1.2(a)) ^[inferred]. Reading (ii) is more plausible. ^[ambiguous]

## Reconstructed event datums

Two tearline-level UAP-encounter datums:

| Field | Event 1 (10 APR 25) | Event 2 (11 APR 25) |
|---|---|---|
| Date | **10 APR 25** | **11 APR 25** |
| Time | **2353Z** | **0007Z** |
| Observer | U.S. Aircraft | U.S. Aircraft |
| Phenomenon | "POSS UAP" | "POSS UAP" |
| Count | **1X** (single object) | **1X** (single object) |
| Duration | **12 seconds** | **23 seconds** |
| Altitude | **UNK** | **UNK** |
| Speed | **UNK** | **UNK** |
| Interference | **NO INTERFERENCE WAS NOTED** | **NO INTERFERENCE WAS NOTED** |
| AOR | **INDOPACOM** | **INDOPACOM** |

The two sightings are **~14 minutes apart in UTC** — 2353Z on 10 APR 25 → 0007Z on 11 APR 25 spans 14 minutes across midnight Zulu. They are plausibly the **same encounter split across a UTC date boundary**, the **same platform observing the same object on two passes**, or **two distinct encounters at the same theater within a 14-minute window**. ^[ambiguous] The tearlines do not state whether the two events are co-platform or co-coordinate.

Both events are **brief-observation kinematics-blank records** — duration on the order of seconds (12 / 23), with `UNK` for altitude and speed. The explicit **"NO INTERFERENCE WAS NOTED"** clause is **a novel element not seen in d4 / d5 / d7 / d52 / d54 / d8**: an explicit negative-engagement statement at the tearline level. ^[inferred] This is **not** a UAP-toward-aircraft engagement-class datum by the [[concepts/uap-aircraft-engagement|4-criterion definition]]; it is an explicit *negative datum* on the engagement axis stated at the disclosure-clearance level rather than inferred from omission. See [[concepts/uap-aircraft-engagement#Negative datum on UAP-toward-aircraft|the negative-datum section]] for the broader pattern.

## Multi-axis filename verifiability — d50 is the email-correspondence class's first internally-verifiable filename

The curator filename `dow-uap-d50-email-correspondence-indopacom-april-2025.json` carries two stamps the artifact internally verifies:

| Axis | Filename token | Internal anchor | Match? |
|---|---|---|---|
| Theater / AOR | `indopacom` | "AOR INDOPACOM" (Emails 1, 2) | **YES** |
| Date | `april-2025` | "10APR25" + "11APR25" (Email 3 tearlines) | **YES** |

**d50 is the first dow-uap email-correspondence artifact in which both filename tokens are internally verifiable.** ^[inferred] Compare:

- **d52** filename `na` / `august-2024` — date axis **CONTRADICTED** by internal `31 OCT 24`; theater axis **UNTESTABLE** (no internal coordinate / AOR / banner). See [[references/dow-uap-d52-email-na-2024#"August 2024" in the filename — discrepancy with internal event date|D52 § August 2024 in the filename]].
- **d50** filename `indopacom` / `april-2025` — **both verified** at N=1 in the class.

This **reverses the d52-anchored "curator filename tokens unreliable" pattern within the email-correspondence class** at the per-artifact level: the class now contains one mismatched and one matched artifact, so the pattern is not class-uniform. ^[inferred] At the **series level**, the new score across all classes is: filename-theater **5 mismatch (d4 + d5-A + d5-B + d8 + d52 untestable-coded-`na`) vs 2 match (d54 + d50)** + 1 untestable bearing-only (d7); filename-date **1 mismatch (d52) vs 1 release-framework-verified (d8) vs 1 body-text-verified (d50)** + 4 untestable. The filename-theater axis remains dominantly unreliable, but the email-correspondence class is **less systematically wrong** than the mission-report class at N=2 vs N=5. ^[inferred]

## OUSD(I&S) — the disclosure-review office anchored

**The most consequential institutional resolution from this artifact:** the Information Disclosure Analyst counterparty is **explicitly attributed to the Office of the Undersecretary of Defense for Intelligence and Security** (OUSD(I&S), commonly written as OUSD(I&S) or USD(I&S)) — the third-tier DoD intelligence-policy office under the Secretary of Defense.

This **partially closes [[references/dow-uap-d52-email-na-2024|d52]]'s open question** about whether the *Information Disclosure Analyst* role sits inside DOPSR, USAF FOIA, AARO, or another component: at N=2 in the class, **the role is attested at OUSD(I&S)** ^[inferred]. The disclosure pipeline in the dow-uap series is now anchored across **two distinct DoD offices**:

- **OUSD(I&S) — Information Disclosure Analyst** (d50, d52 likely) — handles **pre-terminal per-data-point UNCLASS tearline + AOR + classification approvals** on an iterative loop with originating units. **First-line disclosure-clearance for individual data points.**
- **DOPSR (DoD Office of Prepublication and Security Review) — Senior Director, Defense Office of Prepublication and Security Review** (PR20) — handles **terminal whole-document prepublication clearance** that authorizes release of an entire artifact. **Final clearance for the assembled document.** See [[references/dow-uap-pr20-prepublication-clearance-2026-03|DoW-UAP-PR20]].

These are **two separate DoD components** — OUSD(I&S) sits inside the Office of the Secretary of Defense / Intelligence; DOPSR sits inside Office of the Secretary of Defense / Public Affairs ^[inferred]. The series therefore documents a **two-component disclosure pipeline**: OUSD(I&S) for the per-tearline-data approval (pre-terminal, iterative), DOPSR for the whole-document terminal release. ^[inferred] Whether [[entities/aaro|AARO]] sits anywhere in this pipeline remains an open question — no AARO reference in d50 internal text.

## PAROC vs PAROL — initialism ambiguity extended, not resolved

**d52** carries the role title **"PAROC Intel Data Analysis Technician"** at 15 AF / DET 1. **d50** carries the role title **"PAROL Intel Data Analysis Technician"** at 12 AF / DET 3. The role-title body is identical; only the four-letter prefix differs (final letter: **C** vs **L**).

Two live readings, both ^[ambiguous]:

1. **OCR confusion** — `C` ↔ `L` glyph mis-binarisation at low DPI is a plausible character-class collision. One of the two transcriptions is wrong; the underlying role is a single program. **Mistral-OCR has been confused at the character level elsewhere in the series** (e.g., d4's FVEY → `FVEV` and d8's FVEY → `FVEN` Y-glyph corruptions documented at [[entities/dow-uap-foia-release#Mission-report format (template anchored by `d4`, validated + extended by `d5`, revised by `d7`, extended by `d54`, extended by `d8`)|the mission-report template section]]) — a C↔L confusion is similar in kind. ^[inferred]
2. **Two genuinely different programs** at two different USAF units (12 AF / DET 3 vs 15 AF / DET 1) — both reading as four-letter unit-designators or program-codes that happen to share three letters. **PAROC** and **PAROL** could be distinct USAF intelligence-data programs serving distinct numbered air forces.

The d52-anchored open question for the **PAROC** initialism (Persistent Air Reconnaissance Operations Center / Cell, Patrol Aircraft Reconnaissance Operations Center, Pacific Air Operations Center, or unit-specific designator) is **extended by d50** to admit **PAROL** as a sibling token with the same ambiguity. Resolution is **deferred** until a third artifact disambiguates. ^[ambiguous]

## Roles and the disclosure workflow — three-actor variant

The artifact names **three roles** in the DoD disclosure pipeline (vs the two-role pattern at d52):

- **PAROL Intel Data Analysis Technician, Team Lead, 12 AF / DET 3** — data originator. New unit anchor in the series; first instance of the **Team Lead** qualifier on the PAROC/PAROL role.
- **Information Disclosure Analyst, OUSD(I&S)** — clearance reviewer. Same role-title as d52; now explicitly attributed to OUSD(I&S).
- **"the unit that flies 4(a)"** — third-party authority on what its own observations may be released at the unclassified level. Not named, not visible in the thread. ^[inferred] If `4(a)` is a platform/asset code, this is the operating unit of the asset; if `4(a)` is an EO 13526 §1.4(a) reference, this reading collapses and the phrase becomes a less natural construction. The platform-code reading is favored by the phrase's grammar.

This is a **three-actor pre-terminal clearance loop**: originator → reviewer → owning unit. The d52 thread carried a two-actor loop (originator ↔ reviewer); d50 reveals the three-actor variant with the originating-asset owner as a third clearance gate. ^[inferred] The third actor appears when the data implicates a third-party owning unit's release equities.

## Canonical UNCLASS tearline template — confirmed at N=2

The two d50 tearlines plus the d52 tearline give **N=3 datums** of the same skeleton across the email-correspondence class:

```
US AIRCRAFT OBSERVED [N]X POSS UAP FOR [DURATION] [UNIT] AT [Z TIME],
[FLYING AT [ALTITUDE]] [AT [SPEED]], [INTERFERENCE STATEMENT].
```

| Datum | Source | N | Duration | Altitude | Speed | Morphology | Interference |
|---|---|---|---|---|---|---|---|
| 10 APR 25 | d50 | 1X | 12 sec | UNK | UNK | — | NO INTERFERENCE WAS NOTED |
| 11 APR 25 | d50 | 1X | 23 sec | UNK | UNK | — | NO INTERFERENCE WAS NOTED |
| 31 OCT 24 | d52 | 1X | >2 hours | — | low speed | oval / orb-shaped | — |

The skeleton fields **(count, duration, time)** appear in all three. The **(altitude, speed, morphology, interference)** fields are populated per-tearline based on what the underlying mission report contains and what is approved for release. ^[inferred] **d50 omits morphology** but adds the **explicit "NO INTERFERENCE WAS NOTED"** clause; **d52 omits the interference clause** but supplies **morphology** (oval/orb) and a duration that dwarfs d50 by **3 orders of magnitude** (>7200 sec vs 12–23 sec).

The d50 ↔ d52 contrast bounds the **brief-observation kinematics-blank** sub-class within the **tearline-disclosed UAP corpus**: 12 seconds and 23 seconds (d50) on the brief end; >2 hours (d52) on the sustained end. Two-axis sub-class space anchored: **brief / kinematics-blank / no-morphology / no-interference-noted** (d50) vs **sustained / morphology-rich / orb-class / low-speed** (d52). ^[inferred] Future email-correspondence ingests (d51 queued) will fill out the matrix.

## Bibliographic frame

| Field | Value |
|---|---|
| Source basename | `dow-uap-d50-email-correspondence-indopacom-april-2025.json` |
| Source bytes | 2,034 |
| OCR engine | `mistral-ocr-latest` (`usage_info.pages_processed: 2`) |
| Underlying document size | 312,451 bytes (`usage_info.doc_size_bytes`) — larger than d52's 66,874 bytes despite same OCR-page count, consistent with embedded image content (banners, classification stamps) being denser ^[inferred] |
| Classification | `SECRET//NOFORN` (full thread) / `//UNCLASSIFIED//` (tearlines only) |
| Document class | Email correspondence / disclosure-workflow artifact |
| Originating unit | **12 AF / DET 3** (USAF) |
| Originating role | **PAROL Intel Data Analysis Technician, Team Lead** |
| Counterparty role + office | **Information Disclosure Analyst, OUSD(I&S)** |
| Third-party role | "the unit that flies 4(a)" — originating-asset owning unit |
| AOR | **INDOPACOM** (Indo-Pacific Command) |
| Event dates | 10 APR 25 (2353Z) + 11 APR 25 (0007Z) |
| Email date | Apr 2025 per filename — internally consistent with event dates (likely Apr 2025 onward) ^[inferred] |
| Series position | 8-of-40 ingested (2nd email-correspondence ingest) |
| Witness redaction | FOIA `(b)(6)` on all correspondents |

## OCR confidence

The OCR pass carries no `confidence_scores`. Both pages show clean text-extraction with no visibly garbled segments. The two `image` regions on page 1 (`img-0.jpeg` at `(30,38)→(454,147)`, `img-1.jpeg` at `(17,203)→(541,488)`) carry **null base64 content** — image bytes were not preserved into the JSON. These bounding boxes likely contain DoD letterhead or classification banners rendered as graphics; their content is unrecoverable from this JSON.

The **PAROL** transcription at Email 2 is the highest-risk character-level reading in the artifact (see *PAROC vs PAROL* above); other tokens are clean.

## Structural firsts and corpus signal

- **First multi-event tearline** in the email-correspondence class — d50 carries 2 events vs d52's 1.
- **First explicit "NO INTERFERENCE WAS NOTED" clause** in the dow-uap corpus — novel tearline-level negative-engagement statement.
- **First explicit AOR/COCOM designator** in the dow-uap corpus — INDOPACOM. Mission reports use MGRS / DMS / bearing-only position anchors but no COCOM/AOR scope.
- **First internally-verifiable filename in the email-correspondence class** on both date and theater axes (d52 was unreliable on date, untestable on theater).
- **First explicit DoD-office attribution for the Information Disclosure Analyst role** — OUSD(I&S).
- **Third USAF unit anchor in the series** — 12 AF / DET 3 (after d52's 15 AF / DET 1 and d7's 48FW cross-reference); zero internal Navy unit anchors at N=8 ingests.
- **First three-actor pre-terminal disclosure-clearance loop** in the corpus — originator + reviewer + owning unit. d52 documented a two-actor loop.
- **First instance of the "Team Lead" qualifier** on the PAROC/PAROL role — suggests a hierarchical structure within the data-analysis-technician role at the unit level. ^[inferred]
- **Confirms the email-correspondence document class at N=2** — closes the d52-anchored forward-anchored open thread on [[entities/dow-uap-foia-release|the series anchor]]. ^closed-by-dow-uap-d50.

## Open questions

- **Resolve PAROC vs PAROL** — OCR C↔L confusion vs two distinct programs. ^closed-by-dow-uap-d61 ^closed-by-dow-uap-d62 — **DECISIVELY RESOLVED in favor of PAROC**. [[references/dow-uap-d61-mission-persian-gulf-2020-08-27|DoW-UAP-D61]] (26-27 Aug 2020) attests clean-OCR `PAROC` at 12 AF / DET 3 (the same parent detachment d50's PAROL reading was at); [[references/dow-uap-d62-mission-strait-of-hormuz-2020-09-16|DoW-UAP-D62]] (15-16 Sep 2020) attests a second clean-OCR `PAROC` at 12 AF / DET 3. At N=2 explicit clean-OCR attestations of `PAROC` at this exact parent detachment, the d50 `PAROL` reading is almost certainly OCR C↔L confusion. ^[inferred] The d50 transcription should be read as `PAROC` to align with the d61+d62 attestations.
- **Resolve `4(a)` token** — EO 13526 §1.4(a) reference vs asset/platform code. The "unit that flies 4(a)" grammar favors the platform-code reading; the per-page `# 1.4(a)` header pattern on mission reports favors the EO reading. ^[ambiguous]
- **Resolve `1.2(a)` tearline prefix** — EO 13526 §1.2(a) (TOP SECRET) reading is implausible given the //UNCLASSIFIED// content; internal document-paragraph numbering is the favored reading. ^[ambiguous]
- **Recover the underlying INDOPACOM 10–11 Apr 2025 mission report** — likely preserved in one of the unread `d*` files. If found, would supply the full GENTEXT/UAP segment + position anchor + platform identity that this tearline strips down.
- **Reconcile the two 14-minute-apart tearline events** — same encounter split across UTC midnight, same platform two passes, or two distinct encounters? Internal text does not state.
- **Map OUSD(I&S) ↔ AARO relationship** — does the OUSD(I&S) Information Disclosure Analyst role coordinate with [[entities/aaro|AARO]] (which sits inside OUSD(I&S))? AARO is part of OUSD(I&S) per its charter ^[inferred]; whether disclosure-pipeline traffic is routed through AARO or runs parallel to it is not visible in the d50 thread.
- **Resolve the "Team Lead" position** — d50 is the first instance; does the Team Lead qualifier recur, indicating a stable hierarchical role, or is it d50-unique?
- **Resolve the third-party "unit that flies 4(a)"** — what asset / platform / unit does `4(a)` denote? A future ingest that names the asset would close this.
- ~~**Map d51's place** — d51 (also `*-email-correspondence-*`) is queued. If d51 carries OUSD(I&S) attribution and 12 AF / DET 3 or 15 AF / DET 1 unit anchors, the email-correspondence class is internally consistent on both axes at N=3. If d51 introduces a third unit / third role, the variability widens.~~ ^closed-by-dow-uap-d51 — **CLOSED with variability-widens outcome**: [[references/dow-uap-d51-email-pacific-time-zone-2023-03|DoW-UAP-D51]] is **structurally orthogonal** to d50 + d52 on the role/workflow axis. d51 carries **OUSD(I&S) as ORIGINATOR** (not reviewer) and **AFOSI OSI CI Collections + Intelligence Oversight PM as REVIEWER** (no PAROC, no PAROL, no IDAT, no 12 AF / DET 3 / 15 AF / DET 1 unit anchor). Parent document is an **AFOSI IIR**, not a USMTF Misrep. Workflow is **derivative classification review of an UNCLASS summary**, not per-tearline-data-point approval. **The email-correspondence class bifurcates at N=3** into sub-class A (d50 + d52 — IDAT-originated tearline-clearance, Misrep parent) and sub-class B (d51 — OUSD(I&S)-originated derivative-classification-review, AFOSI IIR parent). OUSD(I&S) attestation extends to N=3 cross-document but with role inversion. The dual-PAROC-PAROL ambiguity ([[#PAROC vs PAROL — initialism ambiguity extended, not resolved|above]]) remains decisively closed by d61 + d62; d51 does not contribute to that axis. See [[references/dow-uap-d51-email-pacific-time-zone-2023-03|D51]].

## See also

- [[entities/dow-uap-foia-release]] — Series-level anchor; this artifact confirms the email-correspondence document class at N=2 and supplies the third USAF unit anchor + first OUSD(I&S) office attribution
- [[references/dow-uap-d51-email-pacific-time-zone-2023-03]] — **Third email-correspondence artifact** ^closed-by-dow-uap-d51 (firming-with-bifurcation class) — d51 widens the email-correspondence class at N=3 with **OUSD(I&S) as originator** (inverting d50's reviewer attestation) ↔ **AFOSI OSI CI** as reviewer (no PAROC/PAROL); **AFOSI IIR** parent document (vs d50's Misrep); **derivative classification review of an UNCLASS summary** workflow (vs d50's per-tearline-data-point approval); **first civilian witness + first ground-based observation + first AFOSI institutional anchor + first IIR parent document class** in the dow-uap corpus. d51's CONUS "Pacific Time Zone" placement firms d52's `NA` = North America reading at N=2 within the email-correspondence class; INDOPACOM AOR (d50) now isolated at 1-of-3.
- [[references/dow-uap-d52-email-na-2024]] — First email-correspondence ingest; structural sibling whose 2-role / 1-event template d50 extends to 3-role / 2-event + adds OUSD(I&S) anchor + adds internally-verifiable filename
- [[references/dow-uap-d60-mission-persian-gulf-2020-08-08]] — **First FULL USMTF Misrep parent document** in dow-uap corpus; **PAROC IDAT role triple-attested** at d60 (482ATKS / 432 AEW Active QC) + d50 (PAROL at 12 AF / DET 3) + d52 (PAROC at 15 AF / DET 1) — three different USAF units, same Intel Data Analysis Technician role, anchoring PAROC/IDAT as a recurring QC pattern across the corpus. ^[inferred] d60 also strengthens d50's `NO INTERFERENCE WAS NOTED` tearline-level negative-engagement clause at the witness-narrative level (d60's explicit `NO IMPACT TO MISSION` on the UAP datum).
- [[references/dow-uap-pr20-prepublication-clearance-2026-03]] — DOPSR terminal-clearance cover stamp; **second component of the two-component disclosure pipeline** — OUSD(I&S) (per-tearline pre-terminal) ↔ DOPSR (whole-document terminal)
- [[references/dow-uap-d4-mission-arabian-gulf-2020]] — Mission-report sibling; contrasts as the underlying *content* class to this artifact's *clearance-process metadata* class
- [[references/dow-uap-d7-mission-arabian-gulf-2020]] — Mission-report sibling; supplies the second USAF unit reference (48FW cross-reference) — complements d50's 12 AF / DET 3 originating-unit anchor
- [[references/dow-uap-d8-mission-djibouti-2025]] — Mission-report sibling; broadest release authorization (FIN+SWE+FVEY+NATO) — d50 sits at the other end of the disclosure-spectrum (UNCLASS tearline only)
- [[concepts/uap-aircraft-engagement]] — d50's "NO INTERFERENCE WAS NOTED" is a tearline-level explicit negative datum on the UAP-toward-aircraft engagement axis
- [[entities/aaro]] — AARO sits inside OUSD(I&S) per its charter; d50 anchors the parent office without naming AARO
- [[projects/uap/uap]]
