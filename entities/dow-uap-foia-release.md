---
title: DoW-UAP FOIA Release Series
category: entities
tags: [uap, organization, archive, dod, navy]
aliases: [DoW-UAP, dow-uap series]
sources: [sources/dow-uap-pr20.json, sources/dow-uap-d4-mission-report-arabian-gulf-2020.json, sources/dow-uap-d5-mission-report-arabian-gulf-2020.json, sources/dow-uap-d52-email-correspondance-na-august-2024.json, sources/dow-uap-d7-mission-report-arabian-gulf-2020.json, sources/dow-uap-d54-mission-report-mediterranean-sea-na.json]
summary: Provisional series-level anchor for the ~40-file "DoW-UAP" FOIA release tranche; multi-service (USAF anchored at 2 unit references; Navy hypothesised) UAP mission reports, range-fouler debriefs, and disclosure-workflow emails 2016-2025, cleared through DoD prepublication review.
provenance:
  extracted: 0.22
  inferred: 0.75
  ambiguous: 0.03
base_confidence: 0.65
lifecycle: draft
lifecycle_changed: 2026-05-10
created: 2026-05-10T22:00:00Z
updated: 2026-05-11T13:00:00Z
---

# DoW-UAP FOIA Release Series

A **provisional series-level anchor** for the ~40-file FOIA release tranche whose source-file basenames carry the `dow-uap-` prefix. As of this writing, **6 of ~40 artifacts** are ingested: the opening prepublication clearance-stamp cover [[references/dow-uap-pr20-prepublication-clearance-2026-03|DoW-UAP-PR20]], the single-sighting mission-report [[references/dow-uap-d4-mission-arabian-gulf-2020|DoW-UAP-D4 (Arabian Gulf 2020)]], the two-sighting mission-report [[references/dow-uap-d5-mission-arabian-gulf-2020|DoW-UAP-D5 (Arabian Gulf 2020)]], the **first non-mission-report artifact** — the tear-line clearance email thread [[references/dow-uap-d52-email-na-2024|DoW-UAP-D52 (15 AF / DET 1, 31 Oct 2024 sighting)]], the **first morphology-bearing + fire-control-engagement-pipeline mission-report** [[references/dow-uap-d7-mission-arabian-gulf-2020|DoW-UAP-D7 (Arabian Gulf 2020)]] which introduces a 48FW (USAF) cross-reference — and the **first internally-verifiable Mediterranean mission-report** [[references/dow-uap-d54-mission-mediterranean-sea|DoW-UAP-D54 (Mediterranean Sea)]] introducing triangular-and-metallic morphology + DMS lat-long position + Aegean Sea / Cyclades operational area.

This page exists so subsequent ingests have a stable target to cross-link to, and so the series-level inferences (provisional scope, theater coverage, document-class taxonomy, mission-report format) can be revised in place as the series is processed rather than re-derived each time.

## What "DoW" stands for — deferred (Navy hypothesis further weakened at N=6)

The abbreviation is **not resolved** from the artifacts ingested so far. Candidate expansions are catalogued at [[references/dow-uap-pr20-prepublication-clearance-2026-03#On the "DoW" filename prefix — explicitly deferred|DoW-UAP-PR20 § On the "DoW" filename prefix]].

**At N=6 ingests** the *"Department of the Navy"* working hypothesis remains **weakened** — d54 adds no new originating-unit anchor (no service / squadron / callsign in the OCR), so the multi-service evidence count is unchanged: two USAF-anchored unit references and zero internal Navy unit anchors. Two USAF-anchored unit references now in the corpus:

1. [[references/dow-uap-d52-email-na-2024|DoW-UAP-D52]]'s `15 AF / DET 1` line — **internal originating-unit** evidence (USAF Fifteenth Air Force, Detachment 1). ^[inferred]
2. [[references/dow-uap-d7-mission-arabian-gulf-2020|DoW-UAP-D7]]'s `"PREVIOUSLY REPORTED UAP FROM 48FW"` cross-reference — **prior-report citation** to the USAF 48th Fighter Wing (RAF Lakenheath; F-15E Strike Eagle). ^[inferred] Second USAF unit reference.

Together these anchor the **multi-service-content hypothesis** at N=2 USAF unit references vs zero internal-document Navy unit references at this ingest depth. ^[inferred] The "Department of the Navy" reading remains compatible with a *FOIA-release-tracking* interpretation in which the releasing component is DoN but originating units span multiple services, but not with an *originating-component* exclusivity claim.

Working revised view: treat `DoW` as a **release-tracking convention** rather than an originating-component initialism. ^[inferred] Final resolution awaits the next ingest that carries an internal banner, FOIA case code, or originating-office header that names the releasing component.

## Series-level filename signature (curator side)

The `sources/` directory carries 40 files with the prefix. Naming pattern (curator-applied — no internal-evidence anchor):

- `dow-uap-d<N>-<document-class>-<theater>-<period>.json` — appears to be the dominant pattern (39 of 40 files).
- `dow-uap-pr20.json` — the **lone `pr*`-prefixed file**; resolves to the DoD prepublication-clearance cover stamp (see [[references/dow-uap-pr20-prepublication-clearance-2026-03]]).

The split suggests **two artifact classes** in the release: the substantive `d*` documents and a small minority of `pr*` clearance-cover artefacts. ^[inferred] To be validated as the rest of the series is ingested.

## Document classes (4 of 4 ingested classes now characterised; 4 inferable from filenames)

Four structurally distinct document classes are inferable from the `d*` filename payloads; **two are now ingest-verified** at N≥1:

| Class | Filename signature | Count (est.) | Status | Working description |
|---|---|---|---|---|
| Mission report | `*mission-report-*` | ~25 of 40 | **ingest-verified at N=4** ([[references/dow-uap-d4-mission-arabian-gulf-2020\|d4]], [[references/dow-uap-d5-mission-arabian-gulf-2020\|d5]], [[references/dow-uap-d7-mission-arabian-gulf-2020\|d7]], [[references/dow-uap-d54-mission-mediterranean-sea\|d54]]) | Operational mission-level UAP encounter reports from a named theater + dated period — USMTF GENTEXT/UAP segment + per-page `# 1.4(a)` header + portion marking `(S/REL)` *or* `(SECRET)` (d7-revised) or **absent** (d54-revised) |
| Range-fouler debrief | `*range-fouler-debrief-*` / `*range-fouler-*` | ~6 of 40 | filename-inferred only | Post-incident debriefs of "range fouler" encounters — Navy-aviation terminology for objects intruding on a training range |
| Email correspondence (disclosure-workflow) | `*email-correspondence-*` | ~3 of 40 (`d50`, `d51`, `d52`) | **ingest-verified at N=1** ([[references/dow-uap-d52-email-na-2024\|d52]]) | Intra-DoD email threads negotiating UNCLASS tear-line data points (month/day/year approvals) for a paired content artifact; SECRET//NOFORN with embedded UNCLASS tear lines; FOIA `(b)(6)` redaction on both correspondents |
| Other content document | `*launch-summary-*` / `*report-*` | ~4 of 40 | filename-inferred only | Mixed administrative / coordination / single-event artifacts |
| Prepublication clearance | `pr20` | 1 of 40 | **ingest-verified at N=1** ([[references/dow-uap-pr20-prepublication-clearance-2026-03]]) | The DOPSR cover stamp |

The "range fouler" terminology is **Navy / Naval Aviation-specific** — it refers to objects/aircraft fouling a designated training range, a standing concept in carrier-air-wing range management. ^[inferred] At N=6 ingests, **two USAF unit references** confirm the series carries **multi-service material**: `d52`'s internal `15 AF / DET 1` originating-unit + `d7`'s cross-reference to a prior `48FW` report. The range-fouler material may still be Navy-originated specifically; the series as a whole is now multi-service. ^[inferred] `d54` adds no new unit anchor (OCR preserves no service / unit / callsign for the reporting platform).

### Email-correspondence document class — anchored at N=1 ([[references/dow-uap-d52-email-na-2024|d52]])

The `*-email-correspondence-*` document class is a **second-order metadata artifact** within the series: emails about the declassification of *other* documents, not UAP-narrative content directly. Structural elements observed at N=1:

- **Reverse-chronological thread layout** — newest reply on top page, older request on bottom.
- **Dual classification banners** — full thread at `SECRET//NOFORN`, embedded tear line at `//UNCLASSIFIED//`.
- **Two-role disclosure-workflow loop** — *PAROC Intel Data Analysis Technician* (data originator) ↔ *Information Disclosure Analyst* (clearance reviewer).
- **Per-data-point iterative clearance** — month, day, and year approved separately; this loop is the *pre-terminal* counterpart to the *whole-document terminal* DOPSR clearance attested in [[references/dow-uap-pr20-prepublication-clearance-2026-03|PR20]]. ^[inferred]
- **Witness-side redaction (FOIA `b(6)`)** applied **also to correspondents** — not just to UAP witnesses, but to the DoD personnel handling the disclosure pipeline. The release scheme masks the whole human chain.
- **Null `image_base64` content in the OCR JSON** — bounding boxes preserved but image bytes discarded. Banners and stamps rendered as images are lost in this OCR pass.
- **Filename date token unreliable** — `d52` filename says `august-2024`, internal date is `31 OCT 24` ^[inferred]. **Extends the d4/d5 filename-vs-internal-document discrepancy** from the theater axis to the **date axis**: curator-applied filename tokens are unreliable on multiple axes.

The `d50` and `d51` siblings (also `*-email-correspondence-*`) are queued for ingest and will validate or extend this class template at N=2 / N=3.

## Geographic coverage (inferred from filenames)

Listed in approximate frequency order:

- **Arabian Gulf / Persian Gulf / Strait of Hormuz / Gulf of Aden / Arabian Sea** — densest cluster (≥12 files); 2020–2024.
- **Iraq / Syria / United Arab Emirates / Middle East** — large cluster (≥9 files); 2016, 2022–2023.
- **Mediterranean Sea / Greece** — ~4 files; 2023–2024. **One ingested at N=6** ([[references/dow-uap-d54-mission-mediterranean-sea|d54]]) — internally verified to decode to the **Aegean Sea / Cyclades** (lat 36°34'53"N, lon 25°59'43"E). The "Mediterranean Sea" curator label is **internally consistent** at N=1; the Aegean / Eastern-Mediterranean is now the *dominant* internal-coordinate region across all four substantive mission-report ingests (d4 + d5-A in 34S Eastern Med; d5-B in 35T Eastern Europe/Black Sea margin; d54 in Aegean Sea proper), regardless of filename theater label. ^[inferred]
- **East China Sea / Japan / IndoPACOM / Pacific Time Zone** — ~5 files; 2023–2025.
- **Djibouti** — 1 file; 2025.
- **Iran** — 1 file; 2020.

Temporal span: ~2016 → ~2025. This places the series **chronologically downstream** of the [[entities/aaro|AARO]] mandate era and overlaps the active US-Navy UAP-reporting framework articulated by witnesses like [[entities/ryan-graves]]. ^[inferred]

## Date frame of containing release

The single ingested file carries a **10 Mar 2026** DoD prepublication clearance stamp ([[references/dow-uap-pr20-prepublication-clearance-2026-03]]). This is the **release-side timestamp**, not the document-event timestamp. Document events span 2016–2025. ^[inferred]

## Structural firsts the series will likely anchor (provisional)

Pending ingest of the substantive content:

- **First operational-era Navy-theater UAP-encounter cluster** in the wiki corpus. The existing corpus's modern witness-side anchor is [[references/usper-statement-2025]] (helicopter-orb encounter, single event); the DoW-UAP series would extend that anchor to a **multi-event multi-theater documented operational record** spanning roughly a decade. ^[inferred]
- **First range-fouler-debrief document class** in the corpus. Distinct artifact class from the mission-report family — to be characterised on ingest. ^[inferred]
- **First [[entities/aaro|AARO]]-era operational-intake corpus** — if AARO is the receiving authority for the series, this would be the wiki's first volume-class AARO-pipeline ingest. ^[inferred]
- **First DoD-prepublication-cleared corpus tranche** at this scale — the existing corpus carries declassified material from earlier eras (FBI HQ 62-83894, NARA RG 38/RG 341/RG 255), but DOPSR-cleared current-era operational material is a different release-pathway class. ^[inferred]

## Mission-report format (template anchored by `d4`, validated + extended by `d5`, revised by `d7`, extended by `d54`)

The four substantive mission-report ingests ([[references/dow-uap-d4-mission-arabian-gulf-2020|DoW-UAP-D4]], [[references/dow-uap-d5-mission-arabian-gulf-2020|DoW-UAP-D5]], [[references/dow-uap-d7-mission-arabian-gulf-2020|DoW-UAP-D7]] — all filename-labeled "Arabian Gulf 2020" — and [[references/dow-uap-d54-mission-mediterranean-sea|DoW-UAP-D54]] — filename-labeled "Mediterranean Sea") establish the working **structural template** for the ~25 mission-report files in the series. Elements **confirmed at N=4** below, with **`d5`-extended**, **`d7`-revised**, and **`d54`-extended** variations explicitly noted:

- **Per-page header `# 1.4(a)`** — **Confirmed at N=4.** Recurs on every OCR'd page of `d4` (5 pages), `d5` (6 pages), `d7` (6 pages), and `d54` (7 pages). This is the [Executive Order 13526](https://www.archives.gov/isoo/policy-documents/eo-13526.html) §1.4(a) classification-category marking (*military plans, weapons systems, or operations*). ^[inferred] Expected to recur across every `d*` mission-report and range-fouler file.
- **Header-only pages padded around substantive pages** — **Confirmed at N=4.** Pad count is per-report variable: `d4`+`d5` carry 4 header-only pages; `d7` carries 5; `d54` carries 6. Substantive page count is per-report variable too: `d4`, `d7`, and `d54` carry 1 substantive page; `d5` carries 2. **`d54`-confirmed: pad-count ceiling rises to 6 header-only pages around a single substantive page.**
- **Sighting count is per-report variable** — **`d5`-extended.** A single `d*` file may carry **multiple GENTEXT/UAP segments** (`d5` has 2, separated by 8h 49m Zulu, in two different UTM zones). `d7` and `d54` revert to single-sighting. Working hypothesis: report length tracks the number of distinct sightings ingested into that report. ^[inferred]
- **USMTF `GENTEXT/UAP` segment** — **Confirmed at N=4.** Substantive content sits inside a US Message Text Format general-text segment with `UAP` as the segment identifier. ^[inferred] **`d7`-extended + `d54`-confirmed:** the GENTEXT/UAP segment may use **explicit USMTF named-field bullets** (`UAP Description:`, `Gentext (UAP Event Description):`) rather than a single free-text `Description` bullet (as in `d4`/`d5`). **`d54` confirms the form-driven template at N=2** — d7 + d54 use the named-field template; d4 + d5 use the free-text template. The form-driven template is a real per-report variant, not an isolated d7 feature. ^[inferred]
- **Portion marking** — **`d7`-REVISED + `d54`-EXTENDED.** `(S/REL)` portion-marking confirmed in `d4`+`d5` (3 sightings total). `d7` uses **`(SECRET)` only** (no foreign-release authorization) — a more-restrictive posture. **`d54` carries no portion-marking at all on the substantive content** — neither `(S/REL)` nor `(SECRET)` — only the per-page `# 1.4(a)` classification-category header. Portion-marking is per-report variable across at least three states (S/REL, SECRET-only, absent). ^[inferred]
- **Banner `SECRET/REL TO USA, FVEY`** — captured in `d4` OCR only (as `FVEV` — `Y → V` low-DPI confusion ^[inferred]); `d5`, `d7`, and `d54` OCRs do not capture the banner (likely cropped or absent in non-(S/REL) releases, or rendered as image bytes that are not captured by the OCR pass).
- **Witness-redaction pattern** — **per-report variable; `d54`-EXTENDED.** `d4` uses `PILOT: (b)(6)` block; `d5` uses inline `[REDACTED]`; `d7` has no `(b)(6)` block on the substantive page and instead carries a `1.4(a)` substring at the platform-identifier position; `d54` carries **OCR-corrupted `(b)(6)` ↔ `14(6)`** at both the witness position and a second standalone line. ^[inferred] All `dow-uap-` material is pre-published-cleared per [[references/dow-uap-pr20-prepublication-clearance-2026-03]], so witness/platform identities are systematically masked across the series — the *format* of the mask varies per-report.
- **Position anchor** — **`d7`-REVISED + `d54`-EXTENDED.** `d4` and `d5` both use **MGRS** coordinates (UTM 34S/35T). `d7` uses **bearing-only** position anchor (`IVO 323'S`) with no reference-frame origin captured. **`d54` uses DMS lat-long** (`363453N 0255943E`) — a third position-anchor format. ^[ambiguous] Position-anchor convention is per-report variable across at least three formats (MGRS, bearing, lat-long).
- **Time anchor** — **`d7`-REVISED + `d54`-EXTENDED.** `d4` and `d5` carry **Zulu time without calendar date** (`1258Z`, `1354Z`, `2243Z`); the filename year is the only date anchor. `d7` carries **no time at all** on the substantive page — neither Zulu nor calendar date. `d54` carries **Zulu time without calendar date** (`1319Z`) and **also no internal date anchor** (filename ends `-na`, not `-2020`). ^[inferred] Time anchor presence is per-report variable; **`d54` is the first dow-uap mission report where neither filename nor body carries a date** — the report is calendrically anchorless.
- **Altitude reporting** — **per-report variable.** `d4` and `d5`-B don't report altitude (brief observations); `d5`-A reports `FL160 TO FL170` (pressure altitude / flight level); `d7` reports `31,000 FT MSL` (mean sea level); `d54` reports `24,989 FT MSL` (mean sea level). **`d54` extends MSL reporting to N=2** — d7 + d54 both use MSL; only d5-A uses flight-level reference. The MSL convention may be the default; FL the variant. ^[inferred]
- **Velocity reporting** — **`d7`-REVISED + `d54`-EXTENDED.** `d4` and `d5` quantify velocity in **knots** (`321 KT`, `40 KT`, `278 KT`) — for the UAP. `d7` qualifies UAP velocity as **"TRAVELING WITH THE WINDS"** — wind-coupled drift, no numeric value. **`d54` quantifies velocity in knots (`168 KT`) but attaches it to the witness aircraft, not the UAP** — UAP-side velocity is unreported. Velocity-reporting convention is per-report variable across *what the velocity describes* (UAP vs witness) as well as *how it's quantified* (knots vs descriptor vs unreported). ^[inferred]
- **Object count is sighting-variable** — **`d5`-extended.** `d5` Sighting B is the corpus's first multi-object datum (`2X POSS UAPS`). The `POSS` (possible) hedge is Navy-format hedging on positive UAP-class identification; absent in single-object reports of `d4`, `d5`-A, `d7`, and `d54` (`1X UAP` in d54).
- **Morphology reporting** — **`d7`-INTRODUCED + `d54`-EXTENDED.** `d4` and `d5` carry zero morphology descriptors across 3 datums. `d7` introduces the corpus's first morphology call: **"LOOKS LIKE A BALLOON"**. **`d54` extends morphology at N=2 with "TRIANGULAR AND METALLIC"** — the corpus's first triangle-shape call (consistent with the classic "black triangle" UAP class in civilian-research literature). ^[inferred] Both morphology-bearing reports use the form-driven named-field template (which explicitly carries a `UAP Description (e.g., size, shape, color, markings, recognizable features)` field), strengthening the hypothesis that **morphology reporting is form-driven** — the named-field template prompts the morphology call. ^[inferred]
- **Cross-report references** — **`d7`-INTRODUCED.** `d4`, `d5`, `d52`, and `d54` carry zero cross-references to other UAP reports. `d7` introduces **"PREVIOUSLY REPORTED UAP FROM 48FW"** — the corpus's first explicit cross-report citation, implying an internal multi-report cross-referencing network among reporting platforms. ^[inferred] `d54` does **not** strengthen this pattern.
- **Track-quality + fire-control vocabulary** — **`d7`-INTRODUCED.** `d4`/`d5`/`d54` document witness observation only. `d7` introduces **"WEAPONS QUALITY 1 TRACK"** + **"NEXT TO SHOOT"** + **"TFLIR" visual ID** — the corpus's first fire-control-pipeline UAP datum. ^[inferred] The reporting aircraft entered weapons-engagement state against the UAP track but did not fire. `d54` does **not** strengthen this pattern — it is a brief-observation record without engagement-pipeline vocabulary.
- **Operational-phase tag** — **`d54`-INTRODUCED.** `d4`/`d5`/`d7` carry no phase-of-flight context. `d54` introduces **"DURING RTB"** (Return To Base) as the first explicit operational-phase tag in the dow-uap mission-report corpus. ^[inferred]
- **Witness-aircraft kinematic state** — **`d54`-INTRODUCED.** `d4`/`d5`/`d7` quantify UAP kinematics and stay silent on witness-aircraft state. `d54` **inverts the pattern**: quantifies witness-aircraft altitude (24,989 ft MSL) + velocity (168 KT) + transit position (lat-long) and stays silent on UAP-side kinematics (no UAP altitude, no UAP velocity). ^[inferred] Whether the inversion is per-report-variable or signals a different operational-reporting subclass (e.g. ISR/patrol-aircraft template vs fighter template) is open. The 168-KT witness-aircraft speed is **notably low for a fighter** and most plausibly indicates a maritime-patrol / ISR / helicopter platform. ^[inferred]
- **Behavioral signatures now span four sub-classes**: (a) **kinematic-anomaly** (speed-up + course-change) — `d4`, `d5`-B; (b) **steady-state cruise at airliner-altitude band** — `d5`-A (velocity-altitude mismatch with conventional envelopes); (c) **prosaic-candidate wind-borne drift at airliner-stratum altitude** — `d7` (balloon-class, 31K ft MSL, wind-coupled); **(d) `d54`-INTRODUCED: morphology-rich kinematics-thin** — `d54` (triangular and metallic morphology; no UAP-side motion quantified). ^[inferred] Across N=4 reports / 5 datums there is still no UAP-toward-aircraft engagement-class signature; `d7` introduces the complementary **aircraft-toward-UAP engagement-pipeline** datum (track + fire-control commit + TFLIR ID without weapons release); `d54` introduces a fourth brief-observation sub-class that *inverts* the kinematics/morphology balance of the others.

### Filename-vs-internal-document discrepancy — **CONFIRMED at N=2 for "Arabian Gulf" mismatch; CONFIRMED at N=1 for "Mediterranean Sea" match (d54)** ^[ambiguous]

A **corpus-level observation across four `d*` mission-report ingests**: filename theater labels are **unreliable for "Arabian Gulf"-labeled reports specifically** (3 of 3 testable reports mismatch), and **internally consistent for the one "Mediterranean Sea"-labeled report**. All three "Arabian Gulf" sightings carry internal coordinates outside the Arabian Gulf; the one "Mediterranean Sea" sighting carries an internal coordinate that decodes inside the Mediterranean. ^[inferred]

| File | Filename theater | Internal anchor | Decoded region | Match? |
| --- | --- | --- | --- | --- |
| `d4` | Arabian Gulf | MGRS `34SDG9041417044` | UTM 34S — Eastern Med / Aegean / NE Libya / Egypt | **NO** |
| `d5`-A | Arabian Gulf | MGRS `34SCE7566990098` | UTM 34S — Eastern Med (same zone as d4) | **NO** |
| `d5`-B | Arabian Gulf | MGRS `35TQK1580995057` | UTM 35T — Eastern Europe / Black Sea / Western Russia | **NO** |
| `d7` | Arabian Gulf | **bearing-only `323'S`** (no MGRS) | **UNDECIDABLE** — no reference frame | n/a |
| **`d54`** | **Mediterranean Sea** | **DMS `363453N 0255943E`** | **Aegean Sea (Cyclades, ~17 km SE of Naxos)** | **YES** |
| *Arabian Gulf reference* | — | (would be UTM 39–40, band Q–R) | Persian Gulf / Strait of Hormuz | n/a |

**The hypothesis "curator-applied filename labels are unreliable theater anchors" is now refined at N=4**: the curator label is **systematically wrong for "Arabian Gulf"** (3-of-3 testable mismatch) and **correct for "Mediterranean Sea"** (1-of-1 match). ^[inferred] Working revised hypothesis: the curator may have **mis-applied "Arabian Gulf" as a default theater** for reports whose internal coordinates actually placed them in the Eastern Mediterranean / Aegean — and `d54` is the first report where the curator label was correctly applied. ^[inferred] If this is true, the entire dow-uap mission-report corpus may be **predominantly Mediterranean / Aegean** operationally, with d4/d5 reports having originated from Mediterranean-theater operations *mis-labeled* by the curator. To be tested against the next `*-mediterranean-*` and `*-arabian-gulf-*` ingests. See [[references/dow-uap-d5-mission-arabian-gulf-2020#Geographic decoding — coordinate vs. filename|D5 § Geographic decoding]] for the full N=2 decoding, [[references/dow-uap-d7-mission-arabian-gulf-2020#Filename vs. internal-document — UNDECIDABLE at N=3 for theater axis|D7 § Filename vs. internal-document UNDECIDABLE]] for the bearing-only case, and [[references/dow-uap-d54-mission-mediterranean-sea#Filename-vs-internal-document — d54 *confirms* the filename for the first time|D54 § Filename-vs-internal-document]] for the first verified match.

**Eastern-Mediterranean / Aegean is now the dominant internal-coordinate region across the entire substantive mission-report set** — 4 of 5 testable sightings (d4 + d5-A + d5-B + d54; d7 is bearing-only). The Aegean (d54), the Eastern Mediterranean broadly (d4 + d5-A), and the Black Sea / Eastern Europe margin (d5-B) all decode within ~1500 km of each other. ^[inferred] Persian Gulf coordinates remain absent.

A **second observation surfaces in `d5`**: a single mission report can carry **two sightings in two different UTM zones** (here 34S Eastern Med and 35T Eastern Europe/Black Sea), separated by ~8h 49m. Working hypothesis: some `d*` files are **multi-theater transit-mission reports** or **multi-platform tasking rollups**. ^[inferred] To be characterized as more `d*` files are processed.

**Date-axis filename unreliability** extends at N=5 substantive ingests: `d52` filename `august-2024` carries internal `31 OCT 24`; `d7` filename `2020` has **no internal date anchor at all**; `d54` filename ends `-na` (filename is honest about not knowing the date) and carries **no internal date anchor**. ^[inferred] Across N=5 substantive ingests, only `d4` + `d5` + `d54` carry internal time anchors (Zulu times only, no calendar date); `d52` carries an internal calendar date that contradicts the filename; `d7` carries no internal date; **`d54` is the first dow-uap mission report where both filename and body are calendrically anchorless**.

## Open questions

- Resolve "DoW" abbreviation (Navy-originating hypothesis weakened by `d52` USAF unit evidence; see above).
- Establish the FOIA case identifier, releasing component, and receiving FOIA-applicant party (if recoverable from internal headers).
- Confirm whether [[entities/aaro|AARO]] is the receiving / routing authority for the series, or whether the series originates from a different DoD-component intake pipeline.
- Resolve **PAROC** initialism (introduced in `d52`); resolve whether *Information Disclosure Analyst* sits inside DOPSR, USAF FOIA, AARO, or a separate component.
- Confirm the email-correspondence document class at N≥2 (queue: `d50`, `d51`).
  <br/>**[expected-source: sources/dow-uap-d50-email-correspondence-indopacom-april-2025.json]**
- Confirm the `d*` / `pr*` artifact-class split with at least one more `pr*` file ingest.
- Characterise the "range fouler" document class as a structural artifact type — fields, witness conventions, release-redaction pattern.
  <br/>**[expected-source: sources/dow-uap-d44-range-fouler-arabian-sea-october-2020.json]**
- **Validate the mission-report template** above against the next 2–3 mission-report ingests. (Now at N=4 with `d54`'s confirmation of the form-driven named-field template at N=2 + DMS lat-long position + RTB operational-phase tag + witness-aircraft kinematic state + triangular morphology + filename-internal-coord match.)
- **Resolve the filename-theater-vs-internal-coordinate question** with the next `d*` ingest. **Now refined at N=4**: 3-of-3 "Arabian Gulf" mismatch + 1-of-1 "Mediterranean Sea" match + 1 untestable. Working hypothesis: curator mis-applied "Arabian Gulf" as a default theater for actually-Mediterranean reports. To be tested against the next `*-mediterranean-*` and `*-arabian-gulf-*` ingests.
- **Resolve the filename-date-vs-internal-date question** (introduced by `d52`: filename `august-2024` vs internal `31 OCT 24`; `d7` extends to filename-only-date with no internal date; `d54` extends to filename-`-na`-token + no internal date — calendrically anchorless).
- Confirm whether the per-page `# 1.4(a)` header recurs across all mission-report `d*` files or only a subset. (Confirmed at N=4 across 24 OCR pages.)
- **Confirm multi-service originating-unit pattern** at N=6: still two USAF unit anchors (`15 AF / DET 1` internal at d52; `48FW` cross-reference at d7) and zero internal Navy unit anchors. `d54` adds no unit anchor (OCR preserves no service / unit / callsign). Does the next ingest add a Navy unit reference, or strengthen the USAF pattern further?
- **Recover the cited 48FW prior report** — likely preserved in one of the unread `d*` files; resolution would validate `d7`'s cross-reference and characterize the 48FW theater + behavior pattern.
- **Characterize aircraft-side engagement-pipeline frequency** — does the WQT + NTS + TFLIR signature in `d7` recur in later `d*` ingests, or is it isolated? `d54` did not strengthen the pattern. If recurrent, the series contains a fire-control-grade sub-stream distinct from the brief-observation stream.
- **Characterize the `(SECRET)` vs `(S/REL)` vs absent portion-marking split** — at N=4, two reports are `(S/REL)` (d4+d5 across 3 sightings), one is `(SECRET)` (d7), and **one carries no portion-marking at all** (d54). Does the split track theater, service, sighting class, or release pathway?
- **Recover d54's calendar date** — the report is the first calendrically anchorless dow-uap mission report (neither filename nor body carries a date). The date may be in an unpreserved image-rendered banner / footer or in a paired email-correspondence artifact (d50/d51-class).
- **Recover d54's reporting-platform type** — 168 KT at 25K ft MSL is anomalously low for a fighter and most plausibly indicates a maritime-patrol / ISR / helicopter platform. If confirmed, this is the corpus's first non-fighter dow-uap mission-report platform anchor.
- **Validate the triangular-and-metallic UAP morphology class** against later `d*` ingests — if triangular morphology recurs, the dow-uap series anchors a triangle-class behavioral cluster distinct from orb / balloon / brief-kinematic-anomaly classes already documented.
- **Test the "morphology reporting is form-driven" hypothesis** — both morphology-bearing dow-uap reports (d7 balloon + d54 triangular-metallic) use the form-driven named-field template; both non-morphology-bearing reports (d4 + d5) use the free-text template. Does the next form-driven-template ingest carry morphology, and the next free-text-template ingest omit it?

## See also

- [[references/dow-uap-pr20-prepublication-clearance-2026-03]] — Series's prepublication clearance-stamp cover artifact (whole-document terminal clearance)
- [[references/dow-uap-d4-mission-arabian-gulf-2020]] — First substantive `d*` mission report — establishes the format template (single-sighting)
- [[references/dow-uap-d5-mission-arabian-gulf-2020]] — Second substantive `d*` mission report — validates template, extends to multi-sighting + multi-theater + altitude reporting variants, confirms filename-vs-coordinate mismatch at N=2
- [[references/dow-uap-d7-mission-arabian-gulf-2020]] — Third substantive `d*` mission report — first morphology ("balloon"), first fire-control engagement-pipeline (WQT + NTS + TFLIR), first cross-report reference (48FW USAF), revises portion-marking + position-anchor + velocity-anchor format
- [[references/dow-uap-d54-mission-mediterranean-sea]] — Fourth substantive `d*` mission report — first triangular-and-metallic morphology, first DMS lat-long position (Aegean Sea / Cyclades), first internally-verifiable filename match ("Mediterranean Sea"), first RTB operational-phase tag, first witness-aircraft-kinematics-quantified-and-UAP-kinematics-omitted record, first calendrically-anchorless mission report; confirms form-driven named-field template at N=2
- [[references/dow-uap-d52-email-na-2024]] — First non-mission-report artifact — tear-line clearance email thread; anchors the email-correspondence document class; supplies first USAF-originating-unit evidence (15 AF / DET 1)
- [[entities/aaro]] — Likely current-era DoD UAP receiving office
- [[entities/ryan-graves]] — Former US Navy F/A-18F pilot; modern Navy-aviation UAP-witness context for the series
- [[concepts/uap-aircraft-engagement]] — Modern Navy operational-encounter behavioral framing
- [[concepts/orb-phenomenon]] — Orb-class morphology framing (d52's 2-hour sustained orb is a different sub-class from d4/d5 brief observations)
- [[projects/uap/uap]]
