---
title: "DoW-UAP-PR20 — DoD Prepublication Clearance Stamp (10 Mar 2026)"
category: references
tags: [uap, primary-source, declassified, dod, ocr]
aliases: [DoW-UAP-PR20, dow-uap-pr20]
sources: [sources/dow-uap-pr20.json]
summary: 1-page Mistral-OCR'd DoD Office of Prepublication and Security Review clearance stamp dated 10 Mar 2026; cover artifact for the otherwise-unannotated "DoW-UAP" FOIA-release series.
provenance:
  extracted: 0.40
  inferred: 0.55
  ambiguous: 0.05
base_confidence: 0.62
lifecycle: draft
lifecycle_changed: 2026-05-10
created: 2026-05-10T22:00:00Z
updated: 2026-05-10T22:00:00Z
---

# DoW-UAP-PR20 — DoD Prepublication Clearance Stamp (10 Mar 2026)

A 1-page Mistral-OCR'd artifact (`sources/dow-uap-pr20.json`, 787 bytes; SHA-256 `70036d98…`) — the **prepublication-and-security-review clearance cover stamp** for an item in a forthcoming "DoW-UAP" FOIA-release series. This page exists as the **opening anchor** for that series in the wiki corpus; it is not a UAP-narrative record in itself.

## What the source actually contains

The OCR pulls a single page (`dpi: 93`, `1023 × 791` pixels) carrying ~5 lines of recognizable text:

```
CLEARED
For Open Publication
Mar 10, 2026
Department of Defense
OFFICE OF PREPUBLICATION AND SECURITY REVIEW
```

followed by ~3 lines of OCR-garbled artefactual text — *"U.S. Department of the Interior"* repeated, with long runs of `1020…000` zero-padding strings, no images, no tables, no hyperlinks, no header/footer. The "Interior" repetition and the zero-padding are **OCR table-extraction artefacts** on a low-DPI scan of a stamp + adjacent ruled fields, not substantive document content. ^[inferred]

No images, no body text, no signatures, no FOIA-control identifiers are recoverable from this OCR pass.

## Bibliographic frame

| Field | Value |
|---|---|
| Source basename | `dow-uap-pr20.json` |
| Source bytes | 787 |
| OCR engine | `mistral-ocr-latest` (`usage_info.pages_processed: 1`) |
| Original document size | 2,292,342 bytes (`usage_info.doc_size_bytes`) |
| Clearance authority | **[[entities/dod\|Department of Defense]] Office of Prepublication and Security Review** (DOPSR ^[inferred]) |
| Clearance stamp date | 10 March 2026 |
| Clearance status | `CLEARED — For Open Publication` |
| Series filename prefix | `dow-uap-` |
| Series position | item `pr20` (precise numbering convention unknown) ^[ambiguous] |

The Office of Prepublication and Security Review is the **DoD-level component** through which DoD personnel and DoD-derived material pass before authorized public release. ^[inferred] (The stamp itself is unambiguous on the office name and the cleared-for-open-publication status; the routing function is general knowledge, not extracted from this single-page artifact.)

## On the "DoW" filename prefix — explicitly deferred

The 40-file `dow-uap-` filename family is a **curator-side convention** applied to the FOIA release tranche; this artifact carries no internal banner, header, or routing line resolving the abbreviation. **Three candidate expansions** with no source-side evidence to choose between them:

1. **Department of (the) Navy** — supported circumstantially by sibling filenames in the series referencing Navy-aviation operational artifacts (mission reports, range-fouler debriefs, Arabian Gulf / Strait of Hormuz / Gulf of Aden / Mediterranean theaters, ~2016–2025). Suggests Navy-originated material released through DoD-level review. ^[inferred]
2. **Department of War** — recent DoD rebrand context; no source-side anchor in this artifact. ^[inferred]
3. **A FOIA-tracking case code** assigned by the releasing office — no internal evidence either way. ^[inferred]

**Resolution deferred** to subsequent ingests in the series — later files may carry origin-office headers, routing lines, or FOIA-control prefixes that resolve the abbreviation. See [[entities/dow-uap-foia-release]] for the series-level placeholder.

## Why this page exists

- **Provenance anchor**: every subsequent DoW-UAP source file ingested into the wiki cross-references this clearance-cover artifact, establishing that the entire series passes through the same DoD prepublication-review gate. ^[inferred]
- **Series cataloguing**: documents the series filename convention, the OCR engine used across the batch, and the per-file OCR-artefact pattern (Mistral-OCR scan-page table extraction noise on stamp-only pages) so later ingests can recognise structurally similar empty/cover artefacts in the series without re-deriving the diagnosis.
- **Negative evidence preserved**: the artifact's near-empty OCR is itself the substantive observation — confirming the prepublication stamp's existence and date while the underlying full document body (2.29 MB) is not part of this 787-byte JSON. ^[inferred]

## Open questions

- What is the underlying full document this stamp belongs to? The 2.29 MB `doc_size_bytes` suggests the parent PDF is substantial — perhaps a multi-page mission report or witness debrief — but is not in this OCR file. ^[inferred]
- Does "pr20" indicate a numbered prepublication-review case (1, 2, 3, … 20+) within the series, or a different scheme? ^[ambiguous]
- Why are the other 39 series files named `d1`–`d75` while this one alone is `pr20`? **Working hypothesis**: the `d*` files are the released documents; `pr*` files (likely a small minority — possibly only this one) carry the corresponding clearance-stamp cover pages as separate OCR artefacts. ^[inferred] To be validated as further `pr*`-prefixed files (if any) appear, or by paired `pr` ↔ `d` numbering across the series.
- Is the [[entities/aaro|AARO]] in the receiving / routing chain for this series? AARO is the standing DoD-affiliated UAP-receiving office in the current era. ^[inferred]

## See also

- [[entities/dow-uap-foia-release]] — Series-level provisional anchor for the DoW-UAP FOIA tranche
- [[entities/aaro]] — Current-era DoD UAP receiving office (likely receiving authority for series content); confirmed via [[references/dow-uap-d55-mission-syria-2016-11-18|d55]] + [[references/dow-uap-d58-range-fouler-debrief-2020-10|d58]] + [[references/dow-uap-d44-range-fouler-arabian-sea-october-2020|d44]] + [[references/dow-uap-d56-range-fouler-arabian-sea-august-2020|d56]] + [[references/dow-uap-d60-mission-persian-gulf-2020-08-08|d60]] **Block A** stamp (`MDR 26-0038 to 26-0046` + `03/27/26`) at 5-of-6 recurrence + [[references/dow-uap-d38-range-fouler-middle-east-may-2020|d38]] **Block B** stamp (`MDR 26-0019` + `01/26/26 001`) isolated at 1-of-6. PR20 (DOPSR clearance) date `10 Mar 2026` sits **between** the two release dates (`01/26/26` and `03/27/26`) — consistent with PR20 DOPSR clearance applying to the whole tranche and AARO-side releases stamping individual MDR allocations as the cases clear. ^[inferred]
- [[projects/uap/uap]]
