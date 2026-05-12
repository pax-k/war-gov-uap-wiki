---
title: Tag Taxonomy
category: meta
tags: [taxonomy, meta]
sources: []
summary: Canonical controlled vocabulary for tags across the wiki. Source of truth for the tag-taxonomy skill.
created: 2026-05-09
updated: 2026-05-12T16:00:00Z
---

# Tag Taxonomy

Controlled vocabulary for the wiki. The current corpus is **UAP-archives** focused (353 wiki pages from 70 declassified-document / archival-conversation ingests, 1944–2026). Tags below are organized by axis. Use this file as the source of truth before adding tags to any new page.

## Rules

- **Max 5 domain/type tags per page.** `visibility/` tags are system tags and do not count.
- **Lowercase, hyphenated.** `papua-new-guinea`, not `Papua New Guinea` or `papua_new_guinea`.
- **ASCII only.** No diacritics in tags. (Use diacritics in `title:` and body text.)
- **Singular by default.** `concept` not `concepts`; `entity` not `entities`. Exceptions: collective nouns where plural is the natural form (`balls-of-fire`, `flying-discs`).
- **Prefer broad over narrow.** A page about a specific NASA mission gets `nasa`, `mission` — not a per-mission tag.
- **Use category to disambiguate.** A page in `entities/` doesn't need an `entity` tag.
- **Never alias.** Pick the canonical form below.

## Reserved System Tags — `visibility/`

These mark a page's intended reach. **Optional.** Untagged pages default to public.

| Tag | Meaning |
|---|---|
| `visibility/public` | Explicitly public — same as no tag |
| `visibility/internal` | Team-only — excluded in filtered query/export mode |
| `visibility/pii` | Sensitive — excluded in filtered query/export mode |

Rules: do **not** count toward 5-tag limit; one per page; never aliased; leave untouched in audits.

Current corpus: **0 pages tagged**. All 353 pages default to public, which matches an open-source declassified-archive vault.

## Domain Tags

The subject matter axis — what the page is about.

### Core domain

| Tag | Use for |
|---|---|
| `uap` | Anything in the UAP / unidentified-aerial-phenomena domain. The corpus's anchor tag (328 pages). |

### History / era

| Tag | Use for |
|---|---|
| `history` | Historical analysis or context (broad). |
| `ww2` | World War II (1939–1945) era specifically. |
| `1947` … `1994` | Year of source-event when narrowly anchored. Use sparingly — prefer `history` + `ww2` etc. when an era covers it. |
| `1940s`, `1950s`, `1960s` | Decade-level when year is unknown or pattern spans years. Use the decade tag (not a year tag) when the page covers a multi-year span within a single decade — e.g. BSRA 1945–1952, IFSB 1952–1962. |

### Geography

| Tag | Use for |
|---|---|
| `france`, `georgia`, `germany`, `japan`, `kazakhstan`, `mexico`, `netherlands`, `papua-new-guinea`, `russia`, `sweden`, `tajikistan`, `turkmenistan`, `ussr` | Country of source-event or affiliation. (Note: `russia` for post-1991 Russian Federation; `ussr` for pre-1991 Soviet Union — keep both to preserve the political-era distinction.) |
| `alaska`, `arizona`, `california`, `idaho`, `kansas`, `kentucky`, `michigan`, `nevada`, `new-mexico`, `ohio`, `oregon`, `washington` | US state of source-event. Add when sighting/event is geographically anchored. |

### Institutional / agency

| Tag | Use for |
|---|---|
| `usaf` | US Air Force (post-1947). |
| `usaaf` | US Army Air Forces (1941–1947). |
| `us-army` | US Army (excluding USAAF). |
| `navy` | US Navy. |
| `raf` | UK Royal Air Force. |
| `nasa` | NASA / civilian US space agency. |
| `nasc` | National Aeronautics and Space Council (EOP). |
| `fbi` | Federal Bureau of Investigation. |
| `state-department` | US Department of State. |
| `dod` | Department of Defense umbrella. |
| `eop` | Executive Office of the President. |
| `military` | Military domain at large (use when no more specific service tag fits, or for cross-service points). |
| `federal-le` | Federal law enforcement (FBI + other federal LE). Distinct from `fbi`-only items. |
| `foreign-government` | Non-US government as actor. |
| `civil-agency` | Civil (non-military) government agency. |
| `civilian-research` | Civilian (non-government) research orgs (e.g., OUFORA). |
| `intelligence` | Intelligence-community framing, sources, or methods. |
| `humint` | Human intelligence collection specifically. |
| `attache` | Defense / Air Attaché reporting channel. (No diacritic.) |
| `embassy` | US embassy as originating post. |
| `diplomacy` | Diplomatic (state-to-state) framing or channel. |

### Phenomenology

| Tag | Use for |
|---|---|
| `morphology` | Object form / shape signatures (discs, orbs, kites, cylinders). |
| `behavior` | Object behavioral signatures (pacing, suppression, formation flying). |
| `pattern` | Recurring cross-page pattern. |
| `orb` | Orb-class morphology. |
| `electromagnetic` | EM-effect signatures (engine stall, equipment fail). |
| `optical` | Optical / visibility anomalies (transparency, beam-blocking). |
| `transparent` | Partial-transparency reports specifically. |
| `low-altitude` | Low-altitude encounters (~ground level). |
| `anomaly` | Generic anomaly framing where finer tags don't apply. |

### Policy / institutional

| Tag | Use for |
|---|---|
| `policy` | Policy framings, doctrine, recommendations. |
| `protocol` | Specific reporting / observational protocols (e.g., Cabell 10-element template). |
| `institutional` | Institutional posture, framing, or behavior. |
| `contact` | First-contact / ETI policy framings. |
| `eti-attribution` | Pages where the extraterrestrial-intelligence attribution itself is the analytical lens (distinct from `contact`'s policy/first-contact framing). |
| `rhetoric` | Discourse / framing analysis. |

### Domain-specific

| Tag | Use for |
|---|---|
| `aviation` | General aviation (military or civil). |
| `commercial-aviation` | Commercial / airline operations. |
| `airline` | Airline as entity. |
| `astronaut` | Astronaut as person/role. |
| `mission` | Specific space/aviation mission. |
| `spacecraft` | Spacecraft class/instance. |
| `senator` | US Senator as role. |
| `senate-staff` | Senate committee staff role. |
| `eisenhower` | Eisenhower-era / administration framing. |
| `white-house` | White House staff / routing. |
| `public-affairs` | Public-affairs / press function. |
| `archive` | Archival project framing. |
| `taxonomy` | This page or pages about taxonomy. |

## Type Tags

The "what kind of page is this" axis. Most pages are sufficiently typed by their `category:` frontmatter and folder, so type tags are sparse.

| Tag | Use for |
|---|---|
| `analysis` | Cross-cutting analytical synthesis (synthesis/ pages). |
| `sighting` | A specific dated/located UAP observation (references/sighting-*). |
| `primary-source` | Pages built directly from a declassified document. |
| `declassified` | Source was formally declassified (often pairs with `primary-source`). |
| `witness` | Witness-testimony framing or analysis. |
| `intel-witness` | Intelligence-community witness specifically (subtype of `witness`). |
| `person` | Person entity (entities/ pages — usually redundant with category, but kept for graph clarity). |
| `organization` | Organization entity (entities/ pages). |
| `location` | Location entity. |
| `drone-pilot` | Drone-pilot witness role. |

## Metadata Tags

Operational / quality flags.

| Tag | Use for |
|---|---|
| `ambiguous` | Source/identification ambiguity in the page. |
| `ocr` | OCR-related issues or evidence noted on the page. |

## Migration Guide — Aliases

Tags below are **non-canonical**. Replace with the canonical form when found.

| Alias (old) | Canonical (new) | Notes |
|---|---|---|
| `military-org` | `military` | "Org" is implied by category=entities; consolidating military-domain tags. |
| `military-unit` | `military` | Same — units fold into `military`. |
| `diplomatic` | `diplomacy` | Use the noun form consistently. |
| `federal` | *(drop)* | Redundant alongside `state-department` + `organization` or `federal-le`. |

## Frequency Reference (post-normalization)

**As of 2026-05-12 batch-7 audit:** 109 unique tags across 353 wiki pages (70 sources / 341 manifest pages + 12 non-manifest pages — synthesis/projects/journal). Near-equilibrium — **zero** page-level normalizations applied; **two** taxonomy additions (`1940s` + `1950s` as canonical decade-slots, parallel to existing `1960s`, formalizing pre-existing usage on 3 entity pages introduced in the batch-5/6 FBI HQ section ingests). Zero alias usage, zero non-ASCII / whitespace / case / underscore issues, zero pages over the 5-tag limit. Top tags:

```
328 uap                130 primary-source    100 sighting           79 fbi
 75 declassified        71 person             51 history            50 usaf
 40 nasa                39 1947               39 witness            38 organization
 34 intelligence        34 policy             33 1948               28 astronaut
 28 civilian-research   23 1950               23 military           20 pattern
 19 morphology          19 rhetoric           15 state-department   15 ww2
 13 aviation            13 navy               10 1949               10 1957
 10 federal-le          10 france              9 1952                9 usaaf
  8 diplomacy            8 dod                 7 california          7 eti-attribution
  7 new-mexico           7 spacecraft          6 analysis            6 mexico
  5 1964                 5 behavior            5 embassy             5 mission
  5 russia               5 us-army
```

Notable shifts from batch-6 audit (343 → 353 pages, +10; tags 109 → 109, ±0 net; 111 unique observed pre-normalization → 109 after the two decade-slot promotions absorbed `1940s` + `1950s` into the canonical vocabulary):

- `uap` 318 → 328 (+10, exactly tracking new pages — anchor invariant).
- `primary-source` 120 → 130 (+10), `declassified` 65 → 75 (+10), `sighting` 90 → 100 (+10) — d61-d65 cluster (5 full USMTF Misreps) + d10 OIR Misrep + d6 + d12 + d14 + d3 ingests all carry the canonical `[uap, primary-source, declassified, navy|usaf|military, sighting]` artifact-class set. Zero tag-set drift across the batch.
- `usaf` 41 → 50 (+9), `military` 23 → 23 (±0), `navy` 12 → 13 (+1) — batch-7 is heavily USAF-anchored (d61-d65 + d10 are all 432 AEW / 482ATKS / 609 CAOC MQ-9 missions; the d61-d65 quintuplet alone accounts for +5 USAF mission-report pages).
- `fbi` 79 → 79 (±0) — FBI HQ ingest fully absorbed at batch-5/6; batch-7 is exclusively dow-uap.
- `history` 51 → 51, `policy` 34 → 34, `nasa` 40 → 40 (all ±0) — no NASA / policy-domain ingests this batch; growth is exclusively in the dow-uap mission-report corner.
- TWO **decade-slot canonical promotions** (`1940s` 1 use on `entities/borderland-sciences-research-associates.md`; `1950s` 2 uses on `entities/international-flying-saucer-bureau.md` + `entities/albert-k-bender.md`). All three pages were created 2026-05-10 during the FBI HQ Section-7/9 ingest batch (pre-batch-7); the decade tags weren't caught in batch-5/6 audits because the FBI HQ section ingest finished mid-batch-5 and the entity pages were created concurrent with the audit pass. Promotion rationale: `1960s` is already canonical with the documented decade-rationale (`Decade-level when year is unknown or pattern spans years`); BSRA spans 1945-1952, Bender ~1952-1953, IFSB ~1952-1962 — all genuinely decade-spanning; year-tags would lose precision. Per skill's "2+ pages → add to taxonomy" rule (`1950s` qualifies cleanly), and per single-use-replace-or-drop rule for `1940s` the closest canonical alternative would be a 1945/1946/etc. year tag which is less informative than the decade tag, so promotion is the most-informative move. Pages were NOT modified; promotions formalize pre-existing canonical-equivalent usage.
- No new domain/type/phenomenology/policy tags introduced from d10-d14 ingests. d10's `OIR` (Operation Inherent Resolve) + `MAG` (Marine Aircraft Group) + `XCAS` mission-type are captured in title + body + entity-link prose, not as tags; existing `[uap, primary-source, declassified, usaf, sighting]` covers the artifact class for all of d10-d65 batch entries.
- No year-slot activations this pass. The reserved 1947–1994 range remains stable. 2020/2022 event-dates (d61-d65 + d10) fall outside the reserved year-tag range and are anchored via filename-date suffix + `event_date` frontmatter, not via year-tag — consistent with the taxonomy's reserved-year-slot scope.

The long tail (1–4 uses) remains dominated by year tags, US state tags, and country tags — narrow but uniformly applied. Acceptable.

**Canonical-but-unused tags** (zero pages): `georgia`, `nevada`, `meta`, `balls-of-fire`, `flying-discs`, plus unused year-slots in the `1947 … 1994` range. Retention rationale unchanged: `georgia` for future Russia-Georgia content; `nevada` as standard US-state slot; `meta` implicit via folder placement; `balls-of-fire` and `flying-discs` as collective-noun morphology slots; year slots filled lazily as source-events anchor to them.

## Adding a New Tag

Before adding a tag:

1. Search this file — does an existing canonical tag cover it?
2. Search the corpus — has anyone already used a related tag form?
3. If genuinely new, place it in the right axis above and add a one-line description.
4. If you're introducing it on a single page only, prefer to omit; add only when it'll see ≥ 2 uses.
