---
title: "DoW-UAP-D52 — Tear-Line Clearance Email Thread (15 AF / DET 1, 31 Oct 2024 sighting)"
category: references
tags: [uap, primary-source, declassified, usaf, sighting]
aliases: [DoW-UAP-D52, dow-uap-d52, dow-uap-d52-email]
sources: [sources/dow-uap-d52-email-correspondance-na-august-2024.json]
summary: 2-page Mistral-OCR'd intra-DoD email thread negotiating the UNCLASS tear line for a 31 Oct 2024 USAF UAP sighting; PAROC Intel Data Analysis Technician (15 AF / DET 1) requesting year-of-event approval from an Information Disclosure Analyst.
provenance:
  extracted: 0.45
  inferred: 0.52
  ambiguous: 0.03
base_confidence: 0.62
lifecycle: draft
lifecycle_changed: 2026-05-11
created: 2026-05-11T06:00:00Z
updated: 2026-05-11T06:00:00Z
---

# DoW-UAP-D52 — Tear-Line Clearance Email Thread (15 AF / DET 1, 31 Oct 2024 sighting)

A 2-OCR-page Mistral-OCR'd artifact (`sources/dow-uap-d52-email-correspondance-na-august-2024.json`, 1,588 bytes; SHA-256 `d9a8b853…`) — **the first non-mission-report ingest** of the [[entities/dow-uap-foia-release|DoW-UAP FOIA release series]]. The artifact is an **intra-DoD email thread** between two roles inside the prepublication / disclosure workflow, negotiating which data points may appear on the **UNCLASS tear line** of a 31 Oct 2024 USAF UAP-encounter report.

The artifact is **metadata about the declassification process**, not a UAP narrative. Its substantive value is twofold: (1) it instantiates the **tear-line clearance negotiation** as a documented institutional workflow inside the DoW-UAP corpus; (2) the originating unit identifier (**15 AF / DET 1**) is **USAF, not Navy** — the first internal-document evidence in the series that contradicts the [[entities/dow-uap-foia-release#What "DoW" stands for — deferred|"Department of the Navy" working hypothesis]] for the `dow-uap-` filename prefix. ^[inferred]

## What the source contains

Two OCR pages totaling ~14 lines of substantive text plus two images (`img-0.jpeg`, `img-1.jpeg`) for which **base64 content is null** in the JSON — the images themselves are not recoverable, only their bounding boxes (likely DoD/USAF email-header banners or the underlying tear-line graphic).

The thread is presented in **reverse-chronological order** (standard email-client convention — newest reply on top). Chronological reconstruction:

### Email 1 (older — appears bottom of page 1)

```
CLASSIFICATION: SECRET//NOFORN

Hello,

Could you please approve the use of the year this incident took place?
Currently you have approved the month and the day, we request it
includes the year.

Thank for your assistance.

V/r
(b) (6)
Information Disclosure Analyst
```

A request from an **Information Disclosure Analyst** (sender redacted via FOIA `(b)(6)` *personal privacy*) escalating an open clearance question: the **year** of the event is not yet approved for release on the UNCLASS tear line, though the **month and day** already are. ^[inferred] The classification banner is `SECRET//NOFORN` (not releasable to foreign nationals).

### Email 2 (newer — appears top of page 0)

```
(b) (6)
CLASSIFICATION: SECRET//NOFORN

Good morning,

Below is the requested additional information (include the year) to
the UNCLASS tear line.

Let us know if you have any questions, comments or concerns.

v/r
(b) (6)
PAROC Intel Data Analysis Technician
15 AF / DET 1

//UNCLASSIFIED//

31 OCT 24, U.S Aircraft observed a possible UAP. It appeared to be oval/orb
shaped, likely moving at a low speed. The U.S Aircraft had eyes on the poss
UAP for over 2 hours.

//UNCLASSIFIED//
```

The reply — from a **PAROC Intel Data Analysis Technician at 15 AF / DET 1** (sender redacted via FOIA `(b)(6)`) — answers the Email 1 request by delivering the **year-inclusive UNCLASS tear line**. The substantive payload is a single short paragraph wrapped in `//UNCLASSIFIED//` portion markings.

## Reconstructed event datum

The tear line itself is the only substantive UAP-narrative content in the artifact:

| Field | Value |
|---|---|
| Date | **31 OCT 24** (31 October 2024) |
| Observer | U.S. Aircraft (platform not specified) |
| Phenomenon | "possible UAP" (Navy-style `POSS` hedge mirrored in USAF prose) ^[inferred] |
| Morphology | **oval / orb-shaped** ([[concepts/orb-phenomenon]] class) |
| Kinematics | "likely moving at a low speed" — sustained, not transient |
| Duration | **>2 hours** eyes-on |
| Theater | curator-filename: "NA"; internal-document: not stated ^[ambiguous] |

This is a **sustained sighting** — the duration alone (>2 hours) sets it apart from the brief-observation sub-class established by [[references/dow-uap-d4-mission-arabian-gulf-2020|D4]] and [[references/dow-uap-d5-mission-arabian-gulf-2020|D5]] (seconds-to-minutes observations). ^[inferred] The combination of *orb morphology + low speed + long dwell* is also a different behavioral signature from the *kinematic-anomaly (speed-up + course-change)* and *steady-state-cruise-at-airliner-altitude-band* sub-classes captured in [[entities/dow-uap-foia-release#Mission-report format (template anchored by `d4`, validated + extended by `d5`)|the d4/d5 template]].

## "NA" in the filename — resolution

The curator filename `dow-uap-d52-email-correspondance-na-august-2024.json` carries the theater token `na`. Three candidate expansions:

1. **North America** ^[inferred] — favored. The originating unit (**15 AF / DET 1**) is **15th Air Force (Numbered Air Force)** — historically the USAF NAF under Air Combat Command at Davis-Monthan AFB (and previously affiliated with US Strategic Command / continental-defense missions). ^[inferred] DET 1 (Detachment 1) routing structures attached to 15 AF have a CONUS / North America operational footprint. ^[inferred]
2. **Not Applicable** — possible. The artifact carries no internal MGRS, no theater banner, no place name. A curator who could not derive a theater from internals may have stamped `na`.
3. **A FOIA case code or routing token** — possible but weakest, no internal anchor either way.

**Working resolution: North America** ^[inferred], with the dual-interpretation flagged. The `d4` and `d5` filename-vs-internal-coordinate mismatch ([[entities/dow-uap-foia-release#Filename-vs-internal-document discrepancy — **CONFIRMED at N=2**|series-level observation confirmed at N=2]]) suggests **curator filename theater tokens are unreliable** in this series; for `d52` no internal coordinate exists to overrule, so the token stands provisionally.

## "August 2024" in the filename — discrepancy with internal event date

The filename carries `august-2024` as the date token, but the only internal date is **31 OCT 24** in the tear line. Three reconciliation paths:

1. The **email correspondence** (the artifact) is dated August 2024 and the event is dated 31 October 2024 — **impossible** as written, since the email replies to a request that itself follows the event ^[ambiguous].
2. The **email correspondence** is from after 31 Oct 2024 (probably Nov 2024 onward); the curator stamped `august-2024` in error or by referencing the FOIA-batch month rather than the email date. ^[inferred]
3. The "24" in the tear line is **not** 2024 — but `31 OCT 24` in a tear-line context written in 2024 cannot plausibly mean 1924.

**Working resolution**: option 2 — the curator filename date is a **batch- or release-side timestamp**, not the email-correspondence timestamp. The internal event date `31 OCT 24` is the only canonical date anchor in the artifact. ^[inferred]

This **mirrors the d4/d5 pattern** ([[entities/dow-uap-foia-release#Filename-vs-internal-document discrepancy — **CONFIRMED at N=2**|filename theater token unreliable]]) and **extends it to filename date tokens**: curator-applied filename date tokens are now suspect as event-date anchors. Future ingests in the series should prefer internal date markings over filename tokens. ^[inferred]

## Roles and the disclosure workflow

The artifact names **two roles** in the DoD disclosure / declassification pipeline:

- **Information Disclosure Analyst** — an information-review staff role responsible for vetting what may appear on an UNCLASS tear line. Likely sitting in the prepublication-or-FOIA-disclosure chain (parallel to but possibly distinct from DOPSR — see [[references/dow-uap-pr20-prepublication-clearance-2026-03|DoW-UAP-PR20]] for the DOPSR cover stamp ingest). ^[inferred]
- **PAROC Intel Data Analysis Technician** — the **PAROC** initialism is not internally expanded in the artifact. Candidate expansions ^[ambiguous]:
  - *Persistent Air Reconnaissance Operations Center* / *Cell* — plausible for a 15 AF / DET 1 intelligence-data role processing surveillance-platform observations. ^[inferred]
  - *Patrol Aircraft Reconnaissance Operations Center* — possible but more typically Navy-aviation phrasing.
  - *Pacific Air Operations Center* — does not match 15 AF's CONUS / NORTHCOM affiliation.
  - Unit-specific designator not in open vocabulary — possible.

**Resolution deferred** pending other DoW-UAP series ingests that may reference the same role or unit. Resolution should not be guessed from a single artifact.

The interaction itself documents a **two-actor declassification-clearance loop**: the analyst originates the tear line, the disclosure analyst approves data points one-by-one (month, day, year separately), and additional data points require re-submission. This is a **finer-grained workflow** than the single-stamp DOPSR clearance seen in [[references/dow-uap-pr20-prepublication-clearance-2026-03|D52's sibling PR20]]: PR20 is the *terminal* prepublication clearance for the whole document; this thread is a *pre-terminal iterative* clearance for an individual data point. ^[inferred]

## Originating-service inference — USAF, not Navy

The most consequential series-level observation from this artifact:

**The unit identifier `15 AF / DET 1` is USAF.** The DoW-UAP series has, prior to this ingest, looked Navy-coded from filename evidence alone (Arabian Gulf / Persian Gulf theaters, *range-fouler* terminology, Mediterranean / IndoPACOM). The first **internal-document originating-unit** evidence in the series is **USAF**, not Navy. ^[inferred]

This **does not refute** the working "Department of the Navy" hypothesis for the `DoW` filename prefix — a USAF-originated artifact can still be released through a Department-of-the-Navy FOIA case — but it **does refute** the implicit assumption that *every artifact* in the series is Navy-originated. The series is now confirmed as **multi-service at the originating-unit level**. ^[inferred]

Reinforces the case ([[entities/dow-uap-foia-release#What "DoW" stands for — deferred|see series entity]]) for treating the `DoW` abbreviation as a **case-code or release-tracking convention** rather than an originating-component initialism. ^[inferred] At N=3 substantive `d*` ingests, two different services are now attested (Navy-coded `d4`/`d5` content + USAF-coded `d52`).

## OCR confidence

The OCR pass carries no `confidence_scores`. Both pages show clean text-extraction with no garbled segments. The two `image` regions (`img-0.jpeg` at `(33,666)→(397,879)` on page 0; `img-1.jpeg` at `(35,126)→(537,571)` on page 1) carry **null base64 content** — image bytes were not preserved into the JSON. These bounding boxes likely contain DoD letterhead, classification banners as graphics, or the visual rendering of the tear line as a stamp.

Bottom line: text content is high-confidence; **image content is unrecoverable from this JSON** and any details inside the banners are lost.

## Bibliographic frame

| Field | Value |
|---|---|
| Source basename | `dow-uap-d52-email-correspondance-na-august-2024.json` |
| Source bytes | 1,588 |
| OCR engine | `mistral-ocr-latest` (`usage_info.pages_processed: 2`) |
| Underlying document size | 66,874 bytes (`usage_info.doc_size_bytes`) — small PDF, consistent with a 2-page email export |
| Classification | `SECRET//NOFORN` (full thread) / `//UNCLASSIFIED//` (tear line only) |
| Document class | Email correspondence / disclosure-workflow artifact |
| Originating unit | 15 AF / DET 1 (USAF) |
| Originating role | PAROC Intel Data Analysis Technician |
| Counterparty role | Information Disclosure Analyst |
| Event date | 31 October 2024 |
| Email date | Aug 2024 per filename ^[ambiguous] — internally undated |
| Series position | 4-of-40 ingested (1st non-mission-report ingest) |
| Witness redaction | FOIA `(b)(6)` on both correspondents |

## Open questions

- **Resolve PAROC** initialism with at least one more series artifact that uses the term or expands it.
- **Resolve the event-platform**: "U.S Aircraft" could be USAF (consistent with 15 AF / DET 1 routing), Navy, or joint-task-force. Internal text does not specify.
- **Resolve "DET 1" attachment**: which higher headquarters owns the detachment? — 15 AF / DET 1 implies a unit attached to 15th Air Force, but DET 1 designations are reused across the USAF. ^[ambiguous]
- **Reconcile filename `august-2024` with internal `31 OCT 24`** — confirm via release-batch metadata (if any further DoW-UAP ingest exposes the release-batch date convention).
- **Resolve `NA` token**: with a USAF / 15 AF unit, *North America* is the natural read, but the internal text places no geographic anchor on the sighting. If a future ingest places this same event with a specific geography, update.
- **Map the disclosure workflow**: does *Information Disclosure Analyst* sit inside DOPSR ([[references/dow-uap-pr20-prepublication-clearance-2026-03|the office named on PR20]]), inside the USAF FOIA office, inside [[entities/aaro|AARO]] disclosure-channels, or in a separate component? ^[ambiguous]
- **Is the underlying full document the `d52` mission-report or witness-debrief** to which this email's tear line attaches? — i.e., is there a paired `d52` content-document elsewhere in the 40-file release that this email clearance-threads? Pattern-matching to PR20's role suggests yes. ^[inferred]

## See also

- [[entities/dow-uap-foia-release]] — Series-level anchor; this artifact establishes the second artifact class (email-correspondence / disclosure-workflow) and supplies the first internal-document USAF-originating evidence
- [[references/dow-uap-pr20-prepublication-clearance-2026-03]] — DOPSR terminal-clearance cover stamp; structural sibling at the *whole-document* level to this artifact's *single-data-point* level
- [[references/dow-uap-d4-mission-arabian-gulf-2020]] — Mission-report sibling; contrast: that artifact is the *content*, this one is the *clearance-process metadata about content*
- [[references/dow-uap-d5-mission-arabian-gulf-2020]] — Mission-report sibling
- [[concepts/orb-phenomenon]] — Behavioral framing for orb/oval-shaped phenomena
- [[concepts/uap-aircraft-engagement]] — Aircraft-encounter framing; this 2-hour orb-class encounter is a different sub-class from the brief-observation kinematic-anomaly cluster
- [[projects/uap/uap]]
