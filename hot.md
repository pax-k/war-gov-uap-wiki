---
title: Hot Cache
updated: 2026-05-09T13:33:54Z
---

# Hot Cache

*A ~500-word semantic snapshot of recent activity. Updated after every major write operation.*

## Recent Activity

- [2026-05-09T13:33:54Z] INGEST (append mode) — Distilled `sources/western_us_event_slides_5.08.2026.json`, a 4-slide AARO-style briefing on a multi-day Western U.S. UAP cluster witnessed by federal LE special agents USPER1–USPER7. Created **9 pages** (5 references for the deck + 4 individual sightings: "Orbs Launching Orbs", "Large Fiery Orb", "Dark Kite", "Transparent Kite"; new entity `[[entities/aaro]]`; concepts `[[concepts/orb-phenomenon]]` and `[[concepts/transparent-uap]]`; synthesis `[[synthesis/federal-le-uap-witness-pattern]]`) and updated `projects/uap/uap.md` to fold the modern AARO-handled material in alongside the 1948 corpus.
- [2026-05-09T13:13:27Z] CROSS_LINK — Added 7 missing wikilinks across 6 pages. Wired `Wright-Patterson AFB` mentions into 4 pages (protocol, Cabell, Bakersfield, Hobson, synthesis), `AMC` into 2 sighting refs, `Horten Brothers` into the AMC entity page, and `Cabell` into the UAP project page. No orphans remain; vault is fully connected.
- [2026-05-09T12:58:46Z] INGEST (raw mode) — Promoted `_raw/18_6369445_general_1948_vol_1.json` (a Mistral-OCR'd 1948 USAF correspondence file on "Flying Discs"). Created **13 pages** under the new **`uap` project**: project overview, 3 concepts (`project-sign`, `horten-flying-wing`, `flying-disc-reporting-protocol`), 4 entities (`air-materiel-command`, `c-p-cabell`, `horten-brothers`, `wright-patterson-afb`), 4 references (`usaf-flying-discs-1948`, `loedding-flying-disc`, `sighting-bakersfield-1948-03`, `sighting-hobson-ohio-1948-05`), and 1 synthesis (`horten-thesis-vs-disc-sightings`).

## Active Threads

- **UAP archive ingest**: 1948 corpus (`_raw/18_..._vol_1`) and modern AARO-handled material (`sources/western_us_event_slides_*`) now both feed the `uap` project. Watch `_raw/` and `sources/` for additional volumes/slides.
- **Modern UAP morphologies**: `concepts/orb-phenomenon` (orange / red, mother-and-daughter, "zero resistance" hover) and `concepts/transparent-uap` (NVG-vs-bare-eye, beam-blocking) are new working anchors — every future ingest should check whether incoming sightings extend, contradict, or refine them.
- **AARO is a stub** — needs more material to flesh out statutory basis, methodology, and lineage from `concepts/project-sign`.
- **"Zero resistance" hover descriptor** appears in both [[references/sighting-fiery-orb-western-us]] and [[references/sighting-dark-kite-western-us]] — track recurrence across future ingests as a potentially load-bearing witness phrase.
- **Horten thesis** vs. modern luminous orbs / transparent kites: the 1948 conventional explanation framework does not extend cleanly to the modern morphologies. ^[inferred]

## Key Takeaways

- **Project SIGN's operational hub** in 1948 was Air Materiel Command at Wright-Patterson AFB; all USAF installations were ordered to route disc reports there directly via Maj Gen Cabell's 27 Feb 1948 directive (AFOIR-CO-5).
- **The 10-element 1948 sighting template** is the prototype for every later UAP report schema, including the structured intake AARO inherits today. ^[inferred]
- **Federal LE multi-team multi-vantage corroboration** (Western U.S. Event 1) significantly raises the credibility floor of a sighting compared to single-witness cases — but trained observers still systematically underestimate range/size, as AARO's Fiery Orb correction shows (witness 500–600 m → real ~1050 m; witness "small helicopter cockpit" → real 12–18 m diameter).
- **Partial transparency + beam-blocking + selective-witness visibility** stack in the "Transparent Kite" sighting into one of the more anomalous reports in the cluster.

## Flagged Contradictions

- **Hobson, OH sighting (8 May 1948)**: witness-reported size of "nine inches in diameter from ground level" at 6–8 miles altitude is internally inconsistent (implies a true diameter of hundreds of feet). Recorded but not resolved in source.
- **Soviet bomber claim**: 1947 Moscow attaché cable reports 1,800 jet-propelled aircraft based on the Horten VIII design under construction. No corroboration; almost certainly inflated. Flagged `^[ambiguous]` on `concepts/horten-flying-wing` and `synthesis/horten-thesis-vs-disc-sightings`.
- **Cabell rank in source**: the 1948 file shows him as both Brigadier General and Major General within the same date range — promotion happened mid-bundle.
- **Dark Kite shape**: same object described as "thin line" (USPER6, after lights off), "ill defined dark kite shape with rounded width to the sides" (USPER5), and "triangular" (later AARO discussion). Three coexisting descriptors — flagged on the sighting page as `^[ambiguous]`.
