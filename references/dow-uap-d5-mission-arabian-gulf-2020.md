---
title: "DoW-UAP-D5 — Two-Sighting UAP Mission Report (Arabian Gulf, 2020)"
category: references
tags: [uap, primary-source, declassified, navy, dod]
aliases: [DoW-UAP-D5, dow-uap-d5]
sources: [sources/dow-uap-d5-mission-report-arabian-gulf-2020.json]
summary: 6-page Mistral-OCR'd Navy mission report (filename "Arabian Gulf, 2020"); two GENTEXT/UAP datums — 1354Z 40-kt constant-velocity single-object at FL160-170, and 2243Z 278-kt two-object speed-up + southward turn.
provenance:
  extracted: 0.45
  inferred: 0.50
  ambiguous: 0.05
base_confidence: 0.62
lifecycle: draft
lifecycle_changed: 2026-05-11
created: 2026-05-11T05:00:00Z
updated: 2026-05-11T05:00:00Z
---

# DoW-UAP-D5 — Two-Sighting UAP Mission Report (Arabian Gulf, 2020)

A 6-page Mistral-OCR'd artifact (`sources/dow-uap-d5-mission-report-arabian-gulf-2020.json`, 1,585 bytes; SHA-256 `58a40d60…`) — the **second substantive `d*`-prefixed ingest** of the [[entities/dow-uap-foia-release|DoW-UAP FOIA release series]] (series position **3-of-40**), following [[references/dow-uap-d4-mission-arabian-gulf-2020|DoW-UAP-D4]]. The artifact is a Navy-format **GENTEXT/UAP mission-report record** carrying **two distinct sightings** in the same report, distinguishing it structurally from `d4`'s single-sighting format.

## What the source actually contains

The OCR pulls 6 pages (each `dpi: 93`, `1023 × 791` pixels). **Pages 0–3 are header-only** — each carries only the classification-marking string `# 1.4(a)` with no body text, tables, images, or hyperlinks (identical to `d4` pages 0–3). **Pages 4 and 5 are the substantive pages**, each carrying one GENTEXT/UAP datum:

**Page 4 (Sighting A):**

```
# 1.4(a)

GENTEXT/UAP

- Description: (S/REL) AT 1354Z, [REDACTED] OBSERVED 1X UAP IVO 34SCE7566990098.
  VELOCITY WAS 40 KNOTS AT FL160 TO FL170. UAP SPEED REMAINED CONSTANT.

# 1.4(a)
```

**Page 5 (Sighting B):**

```
# 1.4(a)

## GENTEXT/UAP

- Description: (S/REL) AT 2243Z, [REDACTED] OBSERVED 2X POSS UAPS IVO 35TQK1580995057.
  VELOCITY WAS ESTIMATED AT 278 KNOTS. UAPS INCREASED SPEED AND CHANGED DIRECTION
  TOWARDS THE SOUTH.

(b) (6)

1.4(a)
```

The format is identical to `d4`'s in every structural respect: `# 1.4(a)` EO 13526 §1.4(a) per-page header, USMTF `GENTEXT/UAP` segment, `(S/REL)` portion marking, MGRS coordinates, knots velocity, Zulu time without calendar date, FOIA `(b)(6)` redaction. The **only structural difference**: `d5` carries **two GENTEXT/UAP segments on two substantive pages** rather than `d4`'s single segment on one page.

No images, tables, hyperlinks, headers, or footers in any page. No `SECRET/REL TO USA, FVEY` banner captured in the OCR — likely cropped or in a non-OCR'd region; the per-page `# 1.4(a)` marking and `(S/REL)` portion marking establish the same classification posture as `d4`.

## The encounter datums

### Sighting A — 1354Z slow constant-velocity single-object

| Field | Value | Notes |
|---|---|---|
| Time | **1354Z** | UTC; calendar date not in OCR. |
| Witness | `[REDACTED]` | b(6) personal-privacy redaction. |
| Position (UAP, *in vicinity of*) | **MGRS `34SCE7566990098`** | UTM zone 34S — Eastern Mediterranean. See geographic note below. |
| Altitude (UAP) | **FL160 to FL170** | **16,000–17,000 ft pressure altitude.** First altitude datum in the `dow-uap-` corpus. |
| Velocity (UAP) | **40 knots** (~46 mph / ~74 km/h) | **Very slow.** Below typical helicopter cruise, well below fixed-wing aircraft envelope. |
| Behavior | **Constant velocity** | "UAP SPEED REMAINED CONSTANT." No course/altitude change. |
| Morphology | *none reported* | No shape, color, lighting, sound, or size descriptors. |
| Object count | **1** | Singular. |

The kinematic signature here is **steady-state slow cruise at typical airliner-stratum altitude**. 40 knots at 16-17,000 ft is **dramatically slower than any conventional aircraft** at that altitude — a Cessna 172 stalls at ~50 kt; a typical airliner at FL170 cruises at ~250-450 kt; military rotary-wing rarely operates above FL100. The 40-kt-at-FL170 datum is **anomalous for any known conventional platform** in that altitude band. ^[inferred]

### Sighting B — 2243Z fast multi-object kinematic anomaly

| Field | Value | Notes |
|---|---|---|
| Time | **2243Z** | UTC; **8h 49m after Sighting A**. Same calendar date inferred. ^[inferred] |
| Witness | `[REDACTED]` | b(6) personal-privacy redaction. |
| Position (UAPs, *in vicinity of*) | **MGRS `35TQK1580995057`** | UTM zone 35T — **Eastern Europe / Black Sea region**. Different zone from Sighting A. See geographic note. |
| Altitude (UAPs) | *not reported* | (Cf. `d4` which also lacked altitude. The altitude is the anomaly only when reported.) |
| Velocity (UAPs) | **278 knots** (~320 mph / ~515 km/h) estimated | Within commercial-aircraft envelope. |
| Behavior | **Speed-up + southward turn** | "UAPS INCREASED SPEED AND CHANGED DIRECTION TOWARDS THE SOUTH." Structurally identical to `d4`'s "INCREASED SPEED AND CHANGED DIRECTION TOWARDS THE EAST". |
| Morphology | *none reported* | No shape, color, lighting, sound, or size descriptors. |
| Object count | **2x POSS UAPS** | **First multi-object sighting in the `dow-uap-` corpus.** "POSS" = possible — Navy-format hedging on positive identification. |

The Sighting-B kinematic profile (speed-up + course-change at ~270 kt) closely **mirrors `d4`'s sole datum** (speed-up + course-change at 321 kt). The difference is **object count** (2 vs 1) and **course direction** (south vs east).

## Geographic decoding — coordinate vs. filename ^[ambiguous]

The filename labels the theater "**Arabian Gulf**". **Neither of the two internal MGRS coordinates decodes inside the Arabian Gulf:**

| Sighting | MGRS | UTM zone | Latitude band | Geographic region |
|---|---|---|---|---|
| A | `34SCE7566990098` | **34** (18°E–24°E) | **S** (32°N–40°N) | Eastern Mediterranean / Aegean / NE Libya / Egypt / Crete |
| B | `35TQK1580995057` | **35** (24°E–30°E) | **T** (40°N–48°N) | Eastern Europe / Black Sea / Western Russia / Ukraine / Romania / Bulgaria |
| (Arabian Gulf reference) | — | **39–40** (48°E–60°E) | **Q–R** (16°N–32°N) | Persian Gulf / Strait of Hormuz |

**This is the second `d*`-file in a row** where the curator-applied filename theater label does **not** match the internal-document MGRS coordinate. Where `d4`'s mismatch could be argued away as a single-file OCR artifact, **`d5` confirms it as a corpus-level pattern**: the `dow-uap-` curator-applied filenames are **not reliable theater anchors** to the underlying document content. ^[inferred]

Additionally, **`d5` documents two sightings in two different UTM zones** (34S vs 35T) within the same mission report, separated by ~8h 49m in time. Possible reconciliations, all `^[inferred]`:

1. **Transit mission** — a single platform transited from zone 34S to zone 35T over the day, with one sighting in each theater. Cross-zone transit from 34S to 35T requires northward movement (~600-800 km north) — plausible for a multi-hour flight.
2. **Multi-platform mission** — different aircraft or vessels in the same operational tasking observed UAPs in different theaters, rolled up into one mission report.
3. **OCR ambiguity** — possible but less likely given that the entire MGRS strings differ in zone, band, and 100-km-square digraph; a single OCR error would not produce this kind of coherent zone-shift.

The **34S + 35T pair** is geographically adjacent (Eastern Mediterranean ↔ Black Sea region, separated by the Turkish Straits and Anatolian landmass). Both fall within plausible US-Navy / 6th-Fleet operational reach in the Eastern Mediterranean / NATO-aligned operations area. ^[inferred] **None of this is the Arabian Gulf.**

The corpus-level observation from `d4` is **upgraded** from *"to be re-validated"* to *"confirmed at N=2"* — see [[entities/dow-uap-foia-release#Filename-vs-internal-document discrepancy|series-entity § Filename-vs-internal-document discrepancy]].

## Format-template confirmation (cross-validation against `d4`)

`d5` validates the structural template anchored at [[references/dow-uap-d4-mission-arabian-gulf-2020|DoW-UAP-D4]]. Cross-checking:

| Template element (from d4) | d5 status | Notes |
|---|---|---|
| Per-page `# 1.4(a)` (EO 13526 §1.4(a)) header | **Confirmed** | Recurs on all 6 OCR pages of d5. |
| One substantive page with GENTEXT/UAP segment | **REVISED** — `d5` has **two** | Mission reports may carry multiple sightings; sighting count is per-report-variable, not fixed at 1. |
| USMTF `GENTEXT/UAP` segment header | **Confirmed** | Both pages use this segment marker. |
| `(S/REL)` portion marking | **Confirmed** | Both sightings carry it. |
| `SECRET/REL TO USA, FVEY` banner | **Unconfirmed** | Not captured in d5 OCR (likely cropped); per-page `# 1.4(a)` marking is consistent. |
| `PILOT: (b)(6)` witness redaction | **Partial** | d5 carries one `(b)(6)` on page 5 but no explicit `PILOT:` label; witnesses are `[REDACTED]` inline rather than in a separate block. |
| MGRS coordinates | **Confirmed** | Both sightings use MGRS. |
| Knots velocity | **Confirmed** | Both sightings give velocity in knots. |
| Zulu time without calendar date | **Confirmed** | 1354Z and 2243Z; calendar date in neither. |
| Filename year as only date anchor | **Confirmed** | Filename "2020" is the only year anchor for d5. |

**Newly anchored template variations from `d5`:**

- **Multi-sighting reports exist** — a single `d*` file may carry 2+ GENTEXT/UAP segments on 2+ substantive pages.
- **Cross-theater missions exist** — a single report may span two distinct UTM zones (here, 34S and 35T), separated by hours of Zulu time, suggesting either a transit mission or multi-platform tasking rolled into one report.
- **Altitude reporting is sighting-variable** — `d5` Sighting A reports FL160-170; `d5` Sighting B and `d4` do not report altitude. Altitude is reported when the observation is sustained enough to derive it.
- **Object count is sighting-variable** — `d5` Sighting B is the corpus's first multi-object datum (2x POSS UAPS).
- **The "POSS" (possible) hedge** — Navy-format formal-message hedging on positive identification; appears explicitly when the witness cannot positively confirm UAP class.

## Behavioral classes — both sightings remain brief-observation, not engagement

Neither `d5` sighting meets the engagement-class bar set on [[concepts/uap-aircraft-engagement]]:

- **Sighting A** — single object, no close approach, no co-location with the witness's platform for any reported duration, no target selection, no morphology, no phase-of-flight correlation. **Steady-state slow cruise observation.** Brief-observation class.
- **Sighting B** — multi-object, no close approach, no co-location for non-trivial time, no cross-aircraft target selection, no morphology. **Kinematic anomaly observation.** Brief-observation class.

`d5` confirms `d4`'s **negative datum** on engagement-class: the modern Navy mission-report corpus continues to produce brief-observation-class records at N=3 datums across 2 reports. See [[concepts/uap-aircraft-engagement#Negative datum — modern Navy mission-report corpus produces brief-observation-class records, not engagement-class|engagement-concept § Negative datum]] for the framing.

However, `d5` introduces **two new behavioral sub-classes within the brief-observation envelope**:

1. **Steady-state slow cruise at airliner-altitude band** (Sighting A — 40 kt at FL160-170). This is **distinct** from the kinematic-anomaly profile (`d4` and `d5`-B). The signature here is **the velocity-altitude mismatch with conventional-platform envelopes**, not a change in motion.
2. **Multi-object kinematic anomaly** (Sighting B — 2 objects, speed-up + course change). Distinct from single-object kinematic anomaly (`d4`). Multi-object signatures may be relevant to swarm/formation/coordinated-behavior hypotheses.

## Bibliographic frame

| Field | Value |
|---|---|
| Source basename | `dow-uap-d5-mission-report-arabian-gulf-2020.json` |
| Source bytes | 1,585 |
| OCR engine | `mistral-ocr-latest` (`usage_info.pages_processed: 6`) |
| Original document size | 30,588 bytes (`usage_info.doc_size_bytes`) — single-mission report with two sighting bodies |
| Pages OCR'd | 6 (4 header-only, 2 substantive) |
| Classification (extracted) | `(S/REL)` per portion marking; EO 13526 §1.4(a) per page header. Banner not captured. ^[inferred] |
| Classification authority | EO 13526 §1.4(a) (military plans/weapons/operations) ^[inferred] |
| Message format | USMTF; GENTEXT/UAP segments (×2) ^[inferred] |
| Originating service | US Navy ^[inferred] (filename + GENTEXT/UAP format + series hypothesis) |
| Series | [[entities/dow-uap-foia-release\|DoW-UAP FOIA release]] |
| Series position | **3-of-40** (second substantive `d*` document; `d5` by filename-numbering) |
| Sister | [[references/dow-uap-d4-mission-arabian-gulf-2020]] (`d4`, 2-of-40) — same filename theater label, single-sighting format |

## Open questions

- **Resolve the 34S + 35T cross-zone same-mission question** — is this a transit mission, multi-platform tasking, or other? Hopefully recoverable from internal headers in subsequent `d*` ingests. ^[ambiguous]
- **Recover calendar date** — both sightings are Zulu-time-only; filename year (2020) is the only date anchor.
- **Recover originating unit** — squadron, vessel, air-wing not preserved in OCR.
- Is the witness on Sighting A the **same** witness as Sighting B, or different? OCR redacts both inline; format does not preserve the distinction.
- Does the **POSS** (possible) hedge appear systematically in `d*`-corpus reports where the witness cannot positively confirm UAP class, or is it idiosyncratic to `d5`-B? Track across future `d*` ingests.
- Does the **40-kt-at-FL170 steady-state cruise** signature recur in later `d*` files? If so, it would establish a second brief-observation behavioral sub-class alongside kinematic-anomaly. ^[inferred]

## See also

- [[entities/dow-uap-foia-release]] — Series-level anchor (`d5` updates the format-template section + filename-vs-coordinate observation to N=2-confirmed)
- [[references/dow-uap-d4-mission-arabian-gulf-2020]] — Sister single-sighting report; same filename theater label, same internal-coordinate mismatch
- [[references/dow-uap-d60-mission-persian-gulf-2020-08-08]] — **First FULL USMTF Misrep parent document** (8 Aug 2020 NAVCENT-support over Arabian/Persian Gulf / Strait of Hormuz / Gulf of Oman); d60 verifies its `persian-gulf` filename at 5-of-5 internal MGRS coords — supports the **extract-vs-full-Misrep hypothesis** that d5's "Arabian Gulf" filename may correctly describe a parent-document AOR while the extracted UAP-event MGRS falls outside that AOR. ^[inferred]
- [[references/dow-uap-d7-mission-arabian-gulf-2020]] — Sister Arabian-Gulf-filename mission report
- [[references/dow-uap-pr20-prepublication-clearance-2026-03]] — Series prepublication-clearance cover stamp
- [[concepts/uap-aircraft-engagement]] — Behavioral framing; both `d5` sightings are brief-observation-class, not engagement-class
- [[entities/aaro]] — Modern US DoD UAP receiving office
- [[projects/uap/uap]]
