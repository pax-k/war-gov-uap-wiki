---
title: "DoW-UAP-D54 — Triangular Metallic UAP Mission Report (Mediterranean Sea)"
category: references
tags: [uap, primary-source, declassified, military, sighting]
aliases: [DoW-UAP-D54, dow-uap-d54]
sources: [sources/dow-uap-d54-mission-report-mediterranean-sea-na.json]
summary: 7-page Mistral-OCR'd mission report — single 1319Z GENTEXT/UAP datum, "triangular and metallic" 1X UAP during RTB at FL249 / 168 KT; lat-long position 36°34'53"N 25°59'43"E — Aegean Sea (Cyclades). First triangular-morphology + first internal-Mediterranean-coord ingest in the dow-uap series.
provenance:
  extracted: 0.40
  inferred: 0.55
  ambiguous: 0.05
base_confidence: 0.62
lifecycle: draft
lifecycle_changed: 2026-05-11
created: 2026-05-11T13:00:00Z
updated: 2026-05-11T13:00:00Z
project: uap
---

# DoW-UAP-D54 — Triangular Metallic UAP Mission Report (Mediterranean Sea)

A 7-page Mistral-OCR'd artifact (`sources/dow-uap-d54-mission-report-mediterranean-sea-na.json`, 1894 bytes; SHA-256 `36e82cce…`) — the **fourth substantive mission-report ingest** and **sixth artifact overall** in the [[entities/dow-uap-foia-release|DoW-UAP FOIA release series]]. This is the corpus's **first dow-uap mission report with a Mediterranean-theater filename label that is internally verifiable** — the document carries explicit decimal-DMS lat-long that decodes to the **Aegean Sea south of Naxos / east of Santorini**, reversing the d4 + d5 filename-vs-coordinate discrepancy pattern (where "Arabian Gulf"-labeled reports carried Eastern-Mediterranean coordinates anyway).

## What the source actually contains

The OCR pulls 7 pages (each `dpi: 93`, `1023 × 791` pixels). **Pages 0–5 are header-only** — each carries only the classification-marking string `# 1.4(a)` with no body text, tables, images, or hyperlinks. **Page 6 is the only substantive page**, carrying the operational record alongside an `img-0.jpeg` image block (no `image_base64` captured — typical of the series' OCR pass):

```
# GENTEXT/UAP

- UAP Description (e.g., size, shape, color, markings, recognizable features):
  1X UAP DETECTED WITH DESCRIPTIVE INFORMATION SUCH AS BEING
  A TRIANGLUAR AND METALLIC UAP.

- Gentext (UAP Event Description):
  DURING RTB AT 1319Z, 14(6) OBSERVED 1X UAP WHILE TRANSITING OVER
  363453N 0255943E FLYING AT AN ALTITUDE OF 24,989FT MSL AND
  SPEED OF 168KTS.

14(6)
```

The report uses **explicit USMTF named-field bullets** (`UAP Description:` + `Gentext (UAP Event Description):`), matching the [[references/dow-uap-d7-mission-arabian-gulf-2020|d7]]-introduced form-driven template — **not** the single free-text `Description:` bullet of [[references/dow-uap-d4-mission-arabian-gulf-2020|d4]] / [[references/dow-uap-d5-mission-arabian-gulf-2020|d5]]. This is the **second form-driven mission-report record** in the corpus (d7 was the first), confirming a per-report variant rather than a series-wide single template.

The literal OCR carries **`TRIANGLUAR`** (transposed letters), almost certainly intended `TRIANGULAR`. ^[inferred]

## The encounter datum

| Field | Value | Notes |
|---|---|---|
| Time | **1319Z** | UTC. No calendar date in the OCR; filename carries no date (`-na` token where d4/d5/d7 carry `-2020`). |
| Operational phase | **RTB** (Return To Base) | First explicit phase-of-flight tag in the dow-uap mission-report corpus. ^[inferred] |
| Witness | `(b)(6)` (OCR'd as `14(6)`) | FOIA b(6) personal-privacy redaction; second `14(6)` line at end of page plausibly platform-identifier redaction. ^[inferred] |
| Position (witness, *transiting over*) | **lat 36°34'53"N, lon 25°59'43"E** | Decimal-DMS pair `363453N 0255943E`. **First lat-long-formatted internal position anchor in the `d*` corpus** (d4/d5 used MGRS; d7 used bearing-only). |
| Decoded location | **Aegean Sea (Cyclades)** | Approximately 17 km SE of Naxos / 32 km NE of Santorini / 110 km W of Bodrum (Turkey). Eastern Mediterranean. |
| Altitude (witness) | **24,989 ft MSL** | Mean sea level reference. Roughly FL250 if pressure altitude (likely the underlying MSL-equivalent at standard atmosphere). ^[inferred] |
| Velocity (witness) | **168 KT** (~310 km/h / ~193 mph) | Quantified in knots. Low for a fighter on RTB; consistent with a turboprop, helicopter, or fighter in conservative-fuel RTB profile. ^[inferred] |
| Morphology | **TRIANGULAR + METALLIC** | First triangular-morphology call in the dow-uap series; second morphology call overall (d7 = balloon). |
| UAP altitude / velocity | *not reported separately* | The OCR text grammatically attaches `FLYING AT ... 24,989FT MSL AND SPEED OF 168KTS` to the *witness aircraft* (the participle modifies the subject of "OBSERVED"). UAP altitude/velocity not independently quantified. ^[inferred] |
| Co-witnesses / aircraft count | *not reported* | No multi-aircraft or multi-witness corroboration in the OCR. |

The record is **a brief, morphology-bearing observation during RTB**, with the witness-aircraft state (position + altitude + speed) explicitly quantified but UAP-side kinematics omitted. The behavioral signature inverts d4/d5/d7: prior reports quantified UAP motion and stayed silent on witness-aircraft state; d54 quantifies witness state and stays silent on UAP motion. ^[inferred]

## Geographic decoding — lat-long resolves to Aegean Sea

The internal coordinate **`363453N 0255943E`** is unambiguously DMS-formatted latitude-longitude (degrees-minutes-seconds, north-east), decoding to:

- **Latitude**: 36° 34' 53" N → 36.581°N
- **Longitude**: 25° 59' 43" E → 25.995°E

This position sits in the **central Aegean Sea (Cyclades archipelago)**, approximately:

- ~17 km southeast of **Naxos** (largest Cycladic island)
- ~32 km northeast of **Santorini** (Thira)
- ~110 km west of **Bodrum** (Turkish coast)
- Well within the **Mediterranean Sea** as the filename promises

**The filename "Mediterranean Sea" is internally verified at the coordinate level.** This is the **first dow-uap mission-report ingest where the filename theater label matches an internal coordinate** — reversing the d4/d5 pattern (Arabian-Gulf-labeled, internally Eastern-Med) and the d7 untestability (no internal coordinate). ^[inferred]

The Aegean / Cyclades position has notable adjacencies:

- **NATO operational area** — Turkish, Greek, and US Sixth Fleet activity all pass through this corridor. ^[inferred]
- **Civilian commercial routes** — major airliner overflight corridor for Athens → Middle East / Asia routing. ^[inferred]
- **Adjacent to the 34S UTM grid zone** the d4 + d5 reports' MGRS coordinates decoded into — broader Eastern Mediterranean is now the *dominant* internal-coordinate region for the dow-uap series, regardless of filename theater label. ^[inferred] Four sightings across three reports now decode to the Eastern Mediterranean / Aegean: d4 (UTM 34S), d5-A (UTM 34S), d5-B (UTM 35T Eastern Europe / Black Sea margin), d54 (Aegean Sea proper).

## Filename-vs-internal-document — d54 *confirms* the filename for the first time

Across the four substantive ingests, the filename-vs-internal-coordinate record now reads:

| File | Filename theater | Internal anchor | Decoded region | Match? |
|---|---|---|---|---|
| `d4` | Arabian Gulf | MGRS `34SDG…` | UTM 34S — Eastern Med | **NO** |
| `d5`-A | Arabian Gulf | MGRS `34SCE…` | UTM 34S — Eastern Med | **NO** |
| `d5`-B | Arabian Gulf | MGRS `35TQK…` | UTM 35T — E Europe / Black Sea | **NO** |
| `d7` | Arabian Gulf | bearing `323'S` only | **UNDECIDABLE** | n/a |
| `d54` | **Mediterranean Sea** | **lat-long `363453N 0255943E`** | **Aegean Sea (Cyclades)** | **YES** |

**Key reading**: the curator filename label is **not uniformly unreliable** — it is *unreliable for "Arabian Gulf"-labeled reports specifically*, where 3 of 3 testable reports decode outside the Arabian Gulf. The d54 datum suggests the **"Mediterranean Sea" curator label may be internally consistent**, and by extension that the curator may have mis-applied "Arabian Gulf" as a default theater for reports whose internal coordinates actually placed them in the Eastern Mediterranean. ^[inferred] Working hypothesis: the d4/d5 reports may have *originated* from a Mediterranean-theater operation that the curator filename-tagged as "Arabian Gulf" in error, while d54 was filename-tagged correctly. ^[inferred] To be tested against more `*-mediterranean-*` filenames in the queue.

**Date axis remains unreliable**: d54's filename ends `-na` (no date token where d4/d5/d7 carry `-2020`), and the OCR carries **no calendar date** anywhere — only the 1319Z time. The filename is honest about not knowing the date, in contrast to d52 (filename `august-2024` vs internal `31 OCT 24`) and d7 (filename `2020` vs no internal date). ^[inferred]

## Witness-redaction OCR pattern — `(b)(6)` → `14(6)`

The OCR captures **`14(6)`** at the witness-identity position in the GENTEXT body and again on a standalone line at the end of the page. The string `14(6)` is **almost certainly a low-DPI OCR misread of `(b)(6)`** — the FOIA Exemption b(6) marker masking personal-privacy data. ^[inferred] Three lines of evidence:

1. **No FOIA exemption numbered 14 exists**; the relevant exemption set is b(1)–b(9). Exemption 1.4(a) is an Executive-Order-13526 *classification* category (not a FOIA exemption), and it already appears as the per-page `# 1.4(a)` header in this very document.
2. **The grammatical role** of `14(6)` at the witness position (`14(6) OBSERVED 1X UAP`) is precisely where d4 carries `(b)(6)` and d5 carries `[REDACTED]`. Series convention puts a witness/pilot redaction here.
3. **Low-DPI character-class confusion** at DPI 93 between `b` and `1` (or `b` and `14`) is plausible; `(b)(6)` could OCR as `14(6)` if the small `b` got binarised as `14` ligature. ^[inferred] The second standalone `14(6)` line at end-of-page mirrors the d4 pattern of a second `(b)(6)` line (plausibly aircraft-side identifier or co-witness redaction).

If correct, this is the **third witness-redaction format observed in the corpus**: d4 `PILOT: (b)(6)` block + d5 inline `[REDACTED]` + d7 no-redaction-block + d54 OCR-corrupted `(b)(6)` ↔ `14(6)`. Pattern: **all four reports systematically mask witness identity**, consistent with the [[references/dow-uap-pr20-prepublication-clearance-2026-03|DoD prepublication clearance]] convention.

## Velocity anomaly — 168 KT is unusually low for the dow-uap fighter envelope

The witness-aircraft state at **168 KT at 24,989 ft MSL** is **notably low** for a fighter on the dow-uap mission-report series, where:

- d4 reported UAP at 321 KT
- d5-A reported UAP at 40 KT (the anomalous-low for *that* report)
- d5-B reported UAP at 278 KT
- d7 reported UAP wind-coupled (no number)

168 KT is below typical fighter cruise-RTB envelope (~250–350 KT) but consistent with: ^[inferred]

- **Turboprop maritime patrol aircraft** (P-3 Orion / P-8 Poseidon at loiter speeds, ~200–250 KT)
- **Helicopter** (range-extended H-60 / SH-60 at ~140–160 KT cruise) — *low end of the envelope*
- **Fighter in conservative-fuel RTB profile** — possible but unusual at 25K MSL
- **Reconnaissance/ISR platform** at loiter speed

The most likely platform-class candidate is a **maritime patrol or ISR aircraft on a Mediterranean RTB profile** — consistent with the operational area (Sixth Fleet / NATO Mediterranean / NAVMED). ^[inferred] No platform identifier is preserved in the OCR.

## Bibliographic frame

| Field | Value |
|---|---|
| Source basename | `dow-uap-d54-mission-report-mediterranean-sea-na.json` |
| Source bytes | 1,894 |
| OCR engine | `mistral-ocr-latest` (`usage_info.pages_processed: 7`) |
| Original document size | 20,095 bytes (`usage_info.doc_size_bytes`) |
| Pages OCR'd | 7 (6 header-only `# 1.4(a)`, 1 substantive on page 6 with one image block) |
| Image block | `img-0.jpeg` at `(86, 43)–(633, 492)` on page 6 — `image_base64` is null (typical of series OCR pass) |
| Classification (extracted) | `1.4(a)` per-page header only; **no portion-marking, no banner captured** |
| Classification authority | EO 13526 §1.4(a) (military plans/weapons/operations) ^[inferred] |
| Message format | USMTF with named-field bullets ^[inferred] (matches d7 form-driven template) |
| Originating service | **NOT recoverable** from OCR — no unit, callsign, or platform identifier in the body |
| Series | [[entities/dow-uap-foia-release\|DoW-UAP FOIA release]] |
| Series position | 6-of-40 by ingest order (4th substantive mission report) |
| Date | **NOT recoverable** — filename `-na` token, no internal date anchor |
| Theater | **Aegean Sea (Cyclades) — internally verified** at lat 36°34'53"N, lon 25°59'43"E |

## Structural firsts and corpus signal

`d54` introduces or anchors the following in the dow-uap mission-report corpus (N=4 substantive reports):

1. **First triangular morphology** — `TRIANGULAR AND METALLIC` is the corpus's first triangle-shape call. d7 had "balloon" (prosaic-candidate); d4/d5 had no morphology. The triangular-and-metallic descriptor is **broadly consistent with the classic "black triangle" UAP class** in civilian-research literature, though no further morphology details (size, lighting, wingspan) are preserved. ^[inferred]
2. **First lat-long internal coordinate** — d4/d5 used MGRS; d7 used bearing-only; d54 uses DMS lat-long. Position-anchor convention is now **per-report variable across at least three formats** — MGRS, bearing, lat-long. ^[inferred]
3. **First filename-internal-coordinate MATCH** — d4/d5 reversed, d7 untestable, d54 verifies "Mediterranean Sea" filename. ^[inferred]
4. **First explicit operational-phase tag** — `DURING RTB` (Return To Base). d4/d5/d7 carried no phase-of-flight context. ^[inferred]
5. **First witness-aircraft kinematic state explicitly reported** while UAP-side kinematics are omitted — inverts the d4/d5/d7 pattern. ^[inferred]
6. **Second form-driven USMTF named-field bullet template** — d7 introduced; d54 confirms at N=2 the named-field template is a real per-report variant alongside the d4/d5 free-text Description template. ^[inferred]
7. **Third witness-redaction format observed** — OCR-corrupted `(b)(6)` ↔ `14(6)`. ^[inferred]
8. **Aegean / Eastern-Mediterranean dominance** in the dow-uap internal-coordinate set is now confirmed at 4 sightings / 3 reports — the series may be a *predominantly Mediterranean operational record* mislabeled with Arabian-Gulf curator metadata. ^[inferred]

## Behavioral classification

Per the [[concepts/uap-aircraft-engagement|UAP–Aircraft Engagement]] framework:

- **UAP-toward-aircraft engagement-class**: **no** — no close approach, no co-location, no target switching, no phase-of-flight correlation. Brief observation only.
- **Aircraft-toward-UAP engagement-pipeline**: **no** — no weapons-quality track, no NTS, no TFLIR ID. Not an engagement.
- **Behavioral sub-class within brief-observation**: **morphology-only / kinematics-omitted** — a new fourth sub-class within brief-observation, distinct from d4/d5-B kinematic-anomaly, d5-A steady-state-cruise, and d7 prosaic-candidate-wind-borne. ^[inferred] The signature is *what the UAP looked like*, with no quantified motion to support or refute a conventional-platform classification.

The triangular-and-metallic morphology is **not prosaic-candidate** in the d7 sense (balloon → conventional explanation available) — the triangular metallic-airframe morphology has no obvious conventional candidate in the Eastern-Mediterranean civilian fleet (no commercially-operated triangular airframes at the relevant size/altitude). ^[inferred] But the absence of UAP-side kinematic data prevents stronger classification. The report sits in **morphology-rich, kinematics-thin** epistemic territory — the inverse of d4/d5's **kinematics-rich, morphology-blank** records.

## Open questions

- **Recover the calendar date** — filename `-na` token and no internal date anchor. Date may be in unpreserved metadata (image-rendered banner / footer) or in a paired email-correspondence artifact (d50/d51-class). ^[inferred]
- **Recover the platform type** — 168 KT at 25K ft MSL most likely a maritime-patrol / ISR aircraft, but not confirmed.
- **Recover the originating unit** — no service, squadron, or callsign in the OCR. The Aegean operational area is compatible with Sixth Fleet, NATO Mediterranean, Greek/Turkish forces, or USAFE detachments. ^[inferred]
- **Validate the "Mediterranean Sea" filename-match hypothesis** — the next `*-mediterranean-*` filename ingest (the series carries ~4 such files per [[entities/dow-uap-foia-release]]'s geographic-coverage inventory) will confirm or refute whether the curator's "Mediterranean" label is consistently internally verifiable.
- **Test the "curator mis-applied Arabian Gulf" hypothesis** against the next `*-arabian-gulf-*` ingest that carries an internal coordinate.
- **Recover the page-6 `img-0.jpeg` content** — the OCR captures bounding-box but not bytes. If the image is a sensor capture (FLIR/TFLIR/radar return) it would constitute the corpus's first sensor-side UAP-image artifact in the dow-uap series. ^[inferred]
- **Validate the triangular-morphology UAP class** against later `d*` ingests — if triangular morphology recurs, the dow-uap series anchors a triangle-class behavioral cluster distinct from orb / balloon / brief-kinematic-anomaly classes already documented.

## See also

- [[entities/dow-uap-foia-release]] — Series-level anchor (this is the series' 6-of-40 ingest, 4th substantive mission report)
- [[references/dow-uap-pr20-prepublication-clearance-2026-03]] — Series prepublication-clearance cover stamp
- [[references/dow-uap-d4-mission-arabian-gulf-2020]] — First substantive `d*` mission report — MGRS / kinematic-anomaly
- [[references/dow-uap-d5-mission-arabian-gulf-2020]] — Second substantive `d*` mission report — two-sighting / MGRS / multi-zone
- [[references/dow-uap-d7-mission-arabian-gulf-2020]] — Third substantive `d*` mission report — bearing / prosaic-candidate / fire-control pipeline / form-driven template (first)
- [[references/dow-uap-d52-email-na-2024]] — First non-mission-report — USAF 15 AF / DET 1 originating unit; tear-line clearance email
- [[concepts/uap-aircraft-engagement]] — Behavioral framing; d54 sits in brief-observation morphology-rich-kinematics-thin sub-class
- [[entities/aaro]] — Modern US DoD UAP receiving office
- [[projects/uap/uap]]
