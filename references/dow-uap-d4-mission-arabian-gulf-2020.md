---
title: "DoW-UAP-D4 — Brief UAP Observation Mission Report (Arabian Gulf, 2020)"
category: references
tags: [uap, primary-source, declassified, navy, dod]
aliases: [DoW-UAP-D4, dow-uap-d4]
sources: [sources/dow-uap-d4-mission-report-arabian-gulf-2020.json]
summary: 5-page Mistral-OCR'd Navy mission report (filename-labeled "Arabian Gulf, 2020"); single GENTEXT/UAP datum — 1258Z brief observation, 321 kt, speed-up + eastward turn, pilot identity redacted (b)(6).
provenance:
  extracted: 0.45
  inferred: 0.50
  ambiguous: 0.05
base_confidence: 0.62
lifecycle: draft
lifecycle_changed: 2026-05-11
created: 2026-05-11T04:00:00Z
updated: 2026-05-11T04:00:00Z
---

# DoW-UAP-D4 — Brief UAP Observation Mission Report (Arabian Gulf, 2020)

A 5-page Mistral-OCR'd artifact (`sources/dow-uap-d4-mission-report-arabian-gulf-2020.json`, 1315 bytes; SHA-256 `beccf415…`) — the **first substantive document** ingested from the [[entities/dow-uap-foia-release|DoW-UAP FOIA release series]] following the opening [[references/dow-uap-pr20-prepublication-clearance-2026-03|prepublication clearance cover stamp]]. The artifact is a Navy-format **GENTEXT/UAP mission-report record** with a single substantive datum.

## What the source actually contains

The OCR pulls 5 pages (each `dpi: 93`, `1023 × 791` pixels). **Pages 0–3 are header-only** — each carries only the classification-marking string `# 1.4(a)` with no body text, tables, images, or hyperlinks. **Page 4 is the only substantive page**, carrying the operational record:

```
# 1.4(a)

## GENTEXT/UAP

- Description: (S/REL) AT 1258Z, [REDACTED] OBSERVED POSS UAP IVO 34SDG9041417044.
  BRIEF OBSERVATION PRECLUDED UAP ALTITUDE ESTIMATES.
  VELOCITY ESTIMATED AT 321 KNOTS.
  UAP INCREASED SPEED AND CHANGED DIRECTION TOWARDS THE EAST.

PILOT: (b) (6)

(b) (6)

SECRET/REL TO USA, FVEV
```

The format is unmistakably a US-military formal message:

- **`# 1.4(a)`** — Executive Order 13526 §1.4(a) classification-category marking; §1.4(a) covers *military plans, weapons systems, or operations*. ^[inferred] Recurs as the per-page header across all 5 OCR pages and is expected to recur across other `d*` files in the series.
- **`GENTEXT/UAP`** — USMTF (US Message Text Format) general-text segment header, with `UAP` as the segment identifier. ^[inferred] The format is the Navy/Joint standard for unformatted free-text inside an otherwise structured message.
- **`(S/REL)`** portion-marking — Secret, Releasable; pairs with the banner `SECRET/REL TO USA, FVEV`.
- **`(b) (6)`** — FOIA exemption b(6) (*personal-privacy* redaction) — masks the pilot identity (and a second `(b)(6)` line, plausibly aircraft-side identifier or co-witness).
- **`SECRET/REL TO USA, FVEV`** — classification banner; **`FVEV` is almost certainly OCR of `FVEY`** (Five Eyes — USA, UK, Canada, Australia, New Zealand). ^[inferred] No DoD release marking uses the string `FVEV`; the `Y → V` OCR confusion is plausible at this scan DPI.

No images, tables, hyperlinks, headers, or footers in any page.

## The encounter datum

| Field | Value | Notes |
|---|---|---|
| Time | **1258Z** | UTC; corresponds to ~16:58 local in the Arabian Gulf (UTC+4), or ~14:58 local in the Eastern Mediterranean (UTC+2). |
| Witness | `[REDACTED]` + pilot `(b)(6)` | Identity redacted per FOIA b(6). |
| Position (UAP, *in vicinity of*) | **MGRS `34SDG9041417044`** | See coordinate-vs-filename ambiguity below. |
| Altitude (UAP) | not estimated | "BRIEF OBSERVATION PRECLUDED UAP ALTITUDE ESTIMATES." |
| Velocity (UAP) | **321 knots** (~369 mph / ~595 km/h) | Within commercial-aircraft envelope; the kinematic *signature* is the change, not the absolute speed. |
| Behavior | **Speed-up + eastward turn** | "UAP INCREASED SPEED AND CHANGED DIRECTION TOWARDS THE EAST." |
| Morphology | *none reported* | No shape, color, lighting, sound, or size descriptors in the record. |
| Duration | *brief* (no quantification) | The brevity is itself the explanation given for missing altitude. |

The record is **a short, kinematics-only observation** — no morphology, no sustained observation, no co-platform corroboration in the OCR'd content. The notable behavioral signature is the **acceleration + course change**, not the absolute velocity.

## Coordinate vs. filename — geographic ambiguity ^[ambiguous]

The filename labels the theater "**Arabian Gulf**". The internal MGRS coordinate is **`34SDG9041417044`**, which decodes as:

- **Grid zone designator `34S`**: UTM zone 34 (longitude 18°E–24°E) + latitude band S (32°N–40°N). This covers the **Eastern Mediterranean / Aegean / NE Libya / Egypt / Crete** — **not** the Arabian Gulf. The Arabian Gulf sits at ~48°E–57°E, which falls in UTM zones **39–40**, latitude bands Q–R.
- **100km square `DG` + easting `90414` + northing `17044`** — pinpoints a location inside the 34S grid zone.

Three candidate reconciliations, all `^[inferred]`:

1. **OCR misread on the zone digits** — `34` could be a misread `39` or `40` at low DPI; the substring `DG` could also be miscaptured.
2. **Curator-applied filename mislabel** — the basename `dow-uap-d4-mission-report-arabian-gulf-2020.json` is curator-imposed; the underlying document may carry a different theater designation in its header (not preserved in this OCR pass).
3. **Vessel-or-airframe-in-Med, operationally-grouped-with-Arabian-Gulf** — the originating unit may operate across both theaters and the FOIA-release curator grouped the report under its parent operational area.

**No source-side evidence in the OCR resolves which of these is correct.** The coordinate-vs-filename discrepancy is a **corpus-level observation**: filename-encoded theater labels in the `dow-uap-` series **may not match** internal-document coordinates. ^[inferred] Worth re-checking on subsequent ingests — if a second `d*` file shows the same kind of mismatch, the working hypothesis shifts from "OCR error in this one file" to "curator labels are unreliable theater anchors."

## Bibliographic frame

| Field | Value |
|---|---|
| Source basename | `dow-uap-d4-mission-report-arabian-gulf-2020.json` |
| Source bytes | 1,315 |
| OCR engine | `mistral-ocr-latest` (`usage_info.pages_processed: 5`) |
| Original document size | 29,121 bytes (`usage_info.doc_size_bytes`) — modest single-page-substantive PDF |
| Pages OCR'd | 5 (4 header-only, 1 substantive) |
| Classification (extracted) | `SECRET/REL TO USA, FVEY` ^[inferred] (banner OCR'd as `FVEV`) |
| Classification authority | EO 13526 §1.4(a) (military plans/weapons/operations) ^[inferred] |
| Message format | USMTF; GENTEXT/UAP segment ^[inferred] |
| Originating service | US Navy ^[inferred] (filename + GENTEXT/UAP format + DoW-series hypothesis) |
| Series | [[entities/dow-uap-foia-release\|DoW-UAP FOIA release]] |
| Series position | 2-of-40 by ingest order (first substantive document; `d4` by filename-numbering) |

## Format observations the series will likely repeat

This artifact establishes the **structural template** for the ~25 mission-report files in the series. Working hypotheses to validate on the next ingest:

- **Per-page classification header `# 1.4(a)`** is expected to recur on every page of every `d*` mission-report file. ^[inferred]
- **One substantive page per report** is plausible but not certain — the 5-page document carries the body on the *fifth* page (with 4 header-only pages preceding); the body fits in ~6 OCR'd lines. Other mission reports may carry multi-page bodies if the report includes pre/post-flight context. ^[inferred]
- **GENTEXT/UAP** is expected as the substantive-content header. ^[inferred]
- **`PILOT: (b)(6)`** + a second `(b)(6)` line is the expected witness-block redaction pattern. ^[inferred]
- **`SECRET/REL TO USA, FVEY`** banner-and-portion-marking is expected as the standard release-level. ^[inferred]
- **MGRS** rather than lat/long for UAP position; **knots** for velocity. ^[inferred]

If the next `d*` ingest shows different per-page headers, classification banners, or body formats, the template hypothesis must be revised in place.

## Open questions

- Resolve the **MGRS-vs-filename geographic mismatch** with a second-`d*`-file ingest. If a second mission report shows the same kind of mismatch, the curator-label-unreliable hypothesis strengthens.
- Recover the **originating unit** — squadron, vessel, or air-wing. The OCR preserves none of this. ^[ambiguous]
- Recover the **date** — the filename says "2020" but the OCR carries only a 1258Z time, no Julian/calendar date. ^[ambiguous]
- Resolve the **FVEV → FVEY** OCR question by examining the underlying PDF if available.
- Did the Navy's standing UAP-reporting framework ([[entities/aaro|AARO]] / earlier UAP Task Force) receive this as a formal report, or is this an after-action mission-report extracted from a different operational reporting chain? ^[ambiguous]

## See also

- [[entities/dow-uap-foia-release]] — Series-level anchor (the format observations on this page feed back into the series-entity)
- [[references/dow-uap-pr20-prepublication-clearance-2026-03]] — Series prepublication-clearance cover stamp
- [[concepts/uap-aircraft-engagement]] — Behavioral framing; this datum is a *brief, kinematics-only observation*, not engagement-class
- [[entities/aaro]] — Modern US DoD UAP receiving office
- [[projects/uap/uap]]
