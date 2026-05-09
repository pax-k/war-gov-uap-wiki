---
title: Tag Taxonomy
category: meta
tags: [taxonomy, meta]
sources: []
summary: Canonical controlled vocabulary for tags across the wiki. Source of truth for the tag-taxonomy skill.
created: 2026-05-09
updated: 2026-05-10
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
| `alaska`, `arizona`, `california`, `idaho`, `kansas`, `kentucky`, `michigan`, `nevada`, `ohio`, `oregon`, `washington` | US state of source-event. Add when sighting/event is geographically anchored. |

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

**As of 2026-05-10 audit:** 93 unique tags across 140 wiki pages (138 content pages + 2 root). Zero drift — all tags map to canonical vocabulary; zero pages over the 5-tag limit; zero non-ASCII / whitespace / case issues. Top tags:

```
120 uap                38 sighting            33 history            30 primary-source
24 organization        23 1948                22 person             21 intelligence
18 policy              17 declassified        16 usaf               15 state-department
14 ww2                 12 morphology          12 witness            10 pattern
 9 france               8 aviation             8 diplomacy           8 federal-le
 8 military             8 nasa                 7 fbi                 5 analysis
```

The long tail (1–4 uses) is dominated by year tags, US state tags, and country tags — narrow but uniformly applied. Acceptable.

**Canonical-but-unused tags** (zero pages): `1950`, `georgia`. Both retained for future ingest — `georgia` is contextually applicable to `references/dos-cable-russia-georgia-2001-10.md` but that page is at the 5-tag limit; curatorial decision deferred.

## Adding a New Tag

Before adding a tag:

1. Search this file — does an existing canonical tag cover it?
2. Search the corpus — has anyone already used a related tag form?
3. If genuinely new, place it in the right axis above and add a one-line description.
4. If you're introducing it on a single page only, prefer to omit; add only when it'll see ≥ 2 uses.
