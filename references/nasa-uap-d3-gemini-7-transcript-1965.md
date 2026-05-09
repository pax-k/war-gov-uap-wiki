---
title: NASA d3 — Gemini 7 PAO Tape T-00763(R1b) Transcript (Variant OCR Pass, 1965)
category: references
tags: [uap, primary-source, nasa, 1965, ocr]
aliases: [nasa-uap-d3, d3 Gemini 7 transcript, T-00763 R1b variant OCR, GT-7 PAO transcript variant]
sources: [sources/nasa-uap-d3-gemini-7-transcript-1965.json]
summary: 3-page Mistral-OCR'd variant transcription of the same NASA PAO Tape T-00763(R1b) already canonically ingested as 255_t_763_r1b_transcripts.json — same audio, same exchange; this entry exists only to document the d3 ingest provenance and OCR-variant differences.
provenance:
  extracted: 0.55
  inferred: 0.42
  ambiguous: 0.03
base_confidence: 0.6
lifecycle: draft
lifecycle_changed: 2026-05-10
created: 2026-05-10T19:00:00Z
updated: 2026-05-10T19:00:00Z
---

# NASA d3 — Gemini 7 PAO Tape T-00763(R1b) Transcript (Variant OCR Pass, 1965)

A **3-page Mistral-OCR'd variant transcription** of the same underlying audio and tape already canonically ingested in the wiki as **[[references/nasa-pao-t-00763-r1b-gemini-7-1965|NASA PAO Tape T-00763(R1b) — Gemini 7 Bogey Release Commentary]]**. The d3 file is the third document in the wiki's NASA d-cluster (d1–d7) of crew-transcript / debriefing files, and is the **only d-cluster file to overlap an already-ingested artifact** at the source-tape level.

This page exists for **provenance tracking** of the d3 ingest. **No new sighting page, no new entity page, no new concept page is created from d3** — every UAP-relevant claim is already on the canonical [[references/nasa-pao-t-00763-r1b-gemini-7-1965]] and [[references/sighting-gemini-7-bogey-1965-12-04]] pages. d3's only knowledge-side contribution is as a **transcription-variance comparator** that reinforces the existing OCR-caveat block on the canonical reference.

## Why d3 is a duplicate, not a new artifact

| Field | d3 (this source) | Canonical (already-ingested) |
|---|---|---|
| Tape number | T-00763 (Rlb) | T-00763 (R1b) |
| Caption (page 1, handwritten) | *"UFO SIGHTING BY BORMAN" (GT-1)* | *"UFO SIGHTING BY BORMAN" (GT-7)* |
| Pages | **3** (1 typed + 2 handwritten) | **4** (1 typed + 3 handwritten) |
| Mission | GT-7 / GT-6A | GT-7 / GT-6A |
| MET marker | 04 hr 24 min | 04 hr 24 min |
| Speakers | HOUSTON, S/C BORMAN, S/C LOVELL, P.A.O. | HOUSTON, S/C BORMAN, S/C LOVELL, P.A.O. |
| Object classes | bogey + booster + particles | bogey + booster + particles |
| Underlying audio | identical | identical |
| Filename in source bundle | `nasa-uap-d3-gemini-7-transcript-1965.json` | `255_t_763_r1b_transcripts.json` |
| Mistral-OCR model | `mistral-ocr-latest` | `mistral-ocr-latest` |

The two files are the **same release tape transcribed twice**, almost certainly from the same physical NARA-RG-255 holding. d3 is a different OCR pass with **slightly fewer pages** (3 vs 4) and additional handwriting-recognition artifacts. ^[inferred] No claim from d3 changes the established knowledge layer.

## OCR-variant differences worth recording

These are the **only** content-side observations from d3 that aren't already on the canonical pages. They affect **transcription confidence**, not the underlying facts.

### Page 0 (typed) — confirms canonical

d3's page 0 is structurally identical to the canonical page 0 typed transcript. It uses **fully-uppercase speaker names** (`BORMAN`, `LOVELL`, `HOUSTON`) and a slightly different opening header — *"P.A.O. RELEASE COMMENTARY OF THE GT-7/6 FLIGHT."* — which matches the canonical mission designation. This independent OCR pass **confirms** the canonical typed transcript verbatim where it does not depart on punctuation. ^[extracted]

The d3 page 0 closing line preserves the same key PAO commentary: *"the third and unidentified object of course was or the third object was a bogey. There were several references to the bogey. At 4 Hrs 24 Min into the flight this is Gemini Control."* ^[extracted]

### Page 1 (handwritten variant)

d3's page 1 is captioned *"UFO SIGHTING BY BORMAN" (**GT-1**)* — a **transcription error** (or OCR slip) for **GT-7** in the existing canonical's page 1 caption. The "1" reading is implausible (GT-1 was an unmanned 1964 launch test of the launch vehicle, not a Borman flight); this is an OCR / handwriting reading error in either the original notebook or the OCR pass. ^[ambiguous]

Notable handwritten-OCR artifacts unique to d3 page 1:

- *"Gemme 7 here Houston"* — for *"Gemini 7 here Houston"*
- *"Borman now done debs up here"* — for *"we have debris up here"* (severe OCR breakdown)
- *"hundreds of a going little a particles"* — duplicated articles "a" inserted as OCR noise

### Page 2 (handwritten variant)

d3's page 2 contains the most informative OCR breakdowns:

- *"a small pail, a small pail, a small pail, a small pail, a small pail, a small pail, a small pail, a small pail, a pail of the vehicle at 90 degrees"* — runaway repetition followed by *"pail of the vehicle"* for the canonical *"path of the vehicle"*. The "pail" / "path" reading is notable: in handwriting, *path* and *pail* differ only in the final stroke. This is **almost certainly OCR error**, but the duplication pattern suggests the OCR pipeline got stuck in a loop, then resolved to a wrong word. ^[inferred]
- *"tuthers of particles on it"* — for *"trillions of particles on it"* (Lovell's booster description). "Tuthers" is not a word; canonical reads "trillions." ^[ambiguous]
- *"Jim Control here again"* — for *"Gemini Control here again"*. d3 page 2 reads the PAO speaker label as *"P.H.O."* (vs canonical *"P.A.O."*) and writes *"Jim Control"* in the body. Again, handwritten short-form for *"Gemini"* misread as *"Jim"*. ^[inferred]
- *"slowly (crossed out) tumbling"* — d3 explicitly notes a crossed-out / overwritten word before *"tumbling"*, which the canonical's variant pages 1–3 also flag. ^[extracted]

These artifacts **do not change** any wiki claim. They strengthen the canonical OCR-caveat block by showing a **second independent OCR pass produces a similar but distinct error profile** on the same handwritten variant pages — meaning the underlying handwriting (not the OCR engine alone) is the source of low transcription confidence on the variant pages. ^[inferred]

## What d3 does NOT add

- **No new speaker** beyond HOUSTON / BORMAN / LOVELL / P.A.O.
- **No new object class** beyond bogey / booster / particles
- **No new mission-elapsed-time stamp** — both files give 04 hr 24 min.
- **No new identification of the bogey** — the bogey-vs-booster ambiguity is unchanged.
- **No new physical evidence reference** — no photo, no on-board recorder, no debrief mention.
- **No new institutional metadata** — same NARA RG 255, same PAO release commentary, same dub-off-the-master-tape provenance line.

The d3 source is therefore a **provenance-only ingest**: the wiki gains a second `sources/` entry on every page that already cited `255_t_763_r1b_transcripts.json`, but no factual content changes.

## Cross-corpus structural note

d3 is the wiki's **first explicit duplicate-source ingest** at the audio-tape level. Every prior ingest expanded the corpus's source-set to a new artifact; d3 expands the corpus's evidence-redundancy on a single artifact. This is the model for what to do when **a second OCR pass of an already-ingested document arrives**: do not double the page count, do **not** create new sighting/entity/concept pages, **do** add the source path to every relevant page's `sources:` frontmatter, and **do** create a small reference page like this one to document the duplication. ^[inferred]

The d3 ingest also closes out the **NASA d-cluster (d1–d7) overlap-check** flagged in the d6 and d5 ingest notes: d3 was the only file in the d-cluster expected to overlap an already-ingested NASA artifact, and it does. ^[extracted]

## Open questions

- Locate the **physical T-00763 master tape** at NARA RG 255, plus any **R1a / R0** revisions that may exist alongside R1b. ^[open] (Inherited from canonical reference page.)
- Compare the d3 OCR pipeline's word-confidence output (if available) against the canonical's, to identify which variant readings are most reliable on the handwritten pages. ^[open]
- Cross-check whether the **GT-1 caption error** on d3 page 1 originates in the OCR pass or in the original handwritten notebook. ^[open]

## See also

- [[references/nasa-pao-t-00763-r1b-gemini-7-1965]] — **canonical reference page** for this tape; reads as the primary source-of-truth.
- [[references/sighting-gemini-7-bogey-1965-12-04]] — the consolidated sighting page; cites both d3 and the canonical source.
- [[entities/frank-borman]] — primary witness.
- [[entities/jim-lovell]] — secondary witness.
- [[entities/gemini-7]] — the mission.
- [[entities/nasa-pao]] — release channel.
- [[concepts/orbital-uap-sighting]] — orbital-witness pattern; first instance frame.
- [[projects/uap/uap]] — project overview.
