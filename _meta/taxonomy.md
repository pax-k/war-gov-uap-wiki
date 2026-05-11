---
title: Tag Taxonomy
category: meta
tags: [taxonomy, meta]
sources: []
summary: Canonical controlled vocabulary for tags across the wiki. Source of truth for the tag-taxonomy skill.
created: 2026-05-09
updated: 2026-05-11T12:07:34Z
---

# Tag Taxonomy

Controlled vocabulary for the wiki. The current corpus is **UAP-archives** focused (105 pages from 14 declassified-document ingests, 1944–2026). Tags below are organized by axis. Use this file as the source of truth before adding tags to any new page.

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

Current corpus: **0 pages tagged**. All pages default to public, which matches an open-source declassified-archive vault.

## Domain Tags

The subject matter axis — what the page is about.

### Core domain

| Tag | Use for |
|---|---|
| `uap` | Anything in the UAP / unidentified-aerial-phenomena domain. The corpus's anchor tag (91 pages). |

### History / era

| Tag | Use for |
|---|---|
| `history` | Historical analysis or context (broad). |
| `ww2` | World War II (1939–1945) era specifically. |
| `1947` … `1994` | Year of source-event when narrowly anchored. Use sparingly — prefer `history` + `ww2` etc. when an era covers it. |
| `1960s` | Decade-level when year is unknown or pattern spans years. |

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

**As of 2026-05-11 batch-5 audit:** 109 unique tags across 325 wiki pages (51 sources / 321 manifest pages + 4 infrastructure). Equilibrium holds — zero alias usage, zero non-ASCII / whitespace / case / underscore issues, zero pages over the 5-tag limit, zero normalizations applied, zero new tags introduced. Top tags:

```
300 uap                111 primary-source      81 sighting           78 fbi
 69 person              56 declassified        46 history            40 nasa
 39 1947                38 usaf                38 witness            34 organization
 33 1948                32 intelligence        31 policy             28 astronaut
 27 civilian-research   23 1950                19 morphology         19 pattern
 19 rhetoric            15 ww2                 15 state-department   13 aviation
 11 military            10 france              10 1949               10 1957
 10 federal-le           9 usaaf                9 1952                9 navy
  8 diplomacy            7 spacecraft           7 new-mexico          7 eti-attribution
  7 california           6 mexico               6 dod                 5 mission
```

Notable shifts from batch-4 audit (260 → 325 pages, +65; tags 107 → 109, +2):

- `fbi` jumped from **44 → 78** — the batch-5 signature, driven by the completed FBI HQ 62-83894 ingest (sections 8/3/9/10/6 plus the three repair passes).
- `primary-source` 74 → 111, `declassified` 36 → 56, `sighting` 65 → 81, `witness` 35 → 38 — all reflect the FBI HQ tail and the dow-uap mission-report series.
- `uap` 235 → 300 (+65, exactly tracking the new-page count), confirming `uap` remains the universal anchor.
- `rhetoric` 13 → 19, `pattern` 14 → 19, `morphology` 17 → 19 — modest growth from the contactee/MIB framing pages and the repair passes (Leslie Kean, Hynek, Vallée, ICUFON).
- `eti-attribution` count corrected to **7** (vs. 24 claimed in batch-4 reference). The prior figure appears to have been over-counted from body-text occurrences; the canonical metric is "pages where the tag appears in the YAML `tags` array", which gives 7. Tag remains canonical and broadly distributed (concepts + entities + references); just a one-time numeric correction, not drift. ^[ambiguous]
- New year-slot activations: `1965`, `1966`, `1969` (and `1985`, `1994` continue from prior batches) — all instantiations of the documented `1947 … 1994` year-tag pattern. Not new tags, just new uses of the slot.
- Tag-inventory growth was +2 (107 → 109): two year-slots (`1965`, `1966`) appearing as active for the first time. (`1967`/`1968` remain unused but reserved.)

The long tail (1–4 uses) remains dominated by year tags, US state tags, and country tags — narrow but uniformly applied. Acceptable.

**Canonical-but-unused tags** (zero pages): `georgia`, `nevada`, `meta`, `balls-of-fire`, `flying-discs`, plus unused year-slots in the `1947 … 1994` range. Retention rationale unchanged: `georgia` for future Russia-Georgia content; `nevada` as standard US-state slot; `meta` implicit via folder placement; `balls-of-fire` and `flying-discs` as collective-noun morphology slots; year slots filled lazily as source-events anchor to them.

## Adding a New Tag

Before adding a tag:

1. Search this file — does an existing canonical tag cover it?
2. Search the corpus — has anyone already used a related tag form?
3. If genuinely new, place it in the right axis above and add a one-line description.
4. If you're introducing it on a single page only, prefer to omit; add only when it'll see ≥ 2 uses.
