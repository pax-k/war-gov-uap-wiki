---
title: US Department of State
category: entities
tags: [state-department, organization, diplomacy]
aliases: [DOS, State Department, Department of State, SECSTATE, US State Department, Foggy Bottom]
sources: [sources/dos-uap-d1-cable-1-papua-new-guinea-january-1985.json, sources/dos-uap-d2-cable-2-kazakhstan-january-1994.json, sources/059uap00012.json, sources/059uap00011.json]
summary: US Department of State — the diplomatic instrument of the United States; parent agency of all American embassies and the cable-traffic backbone of the wiki's diplomatic-channel UAP intake pattern.
provenance:
  extracted: 0.45
  inferred: 0.55
  ambiguous: 0.0
base_confidence: 0.75
lifecycle: draft
lifecycle_changed: 2026-05-10
created: 2026-05-09T20:30:00Z
updated: 2026-05-10T00:00:00Z
---

# US Department of State

The **United States Department of State** (DOS) is the federal executive department responsible for US foreign policy and diplomatic relations. It is the parent agency of every American embassy and consulate worldwide and operates the cable system that transports the wiki's diplomatic-channel UAP-adjacent traffic. ^[inferred]

## Why this page exists

Two declassified State Department cables anchor a distinct **diplomatic-channel** UAP intake pattern in the corpus, both originated by US embassies and addressed to `SECSTATE WASHDC` (the State Department headquarters cable address) — see [[concepts/diplomatic-channel-uap-reporting]] for the full pattern.

Both cables share the State Department cable system but route through **different sub-bureaus** within Foggy Bottom, indicating that State has no UAP-specific intake bureau and instead routes UAP-adjacent matters through whichever substantive bureau is the natural fit. ^[inferred]

## Cable instances in the corpus

| Cable | Bureau | Route | Tag set |
|---|---|---|---|
| [[references/dos-cable-papua-new-guinea-1985-01\|PORT M 00199 (28 Jan 1985)]] | **PM** (Bureau of Political-Military Affairs) | from [[entities/amembassy-port-moresby\|AMEMBASSY Port Moresby]] → action [[entities/uscincpac\|USCINCPAC]] / info SECSTATE | `MARR`/`PP` (military overflights) |
| [[references/dos-cable-kazakhstan-1994-01\|DUSHANBE 00259 (31 Jan 1994)]] | **OES/S** (Bureau of Oceans and International Environmental and Scientific Affairs, Science office) | from [[entities/amembassy-dushanbe\|AMEMBASSY Dushanbe]] → SECSTATE WASHDC | `TSAP, EAIR, KZ, TI, TAJIK AIR` (space-and-aviation phenomena) |
| [[references/dos-cable-russia-georgia-2001-10\|MOSCOW 13169 (30 Oct 2001)]] *(boundary case — figurative-UFO rhetoric, not a UAP narrative)* | **IO** (Bureau of International Organization Affairs) | from [[entities/amembassy-moscow\|AMEMBASSY Moscow]] → SECSTATE WASHDC PRIORITY; SECDEF + Joint Staff on INFO | `PREL, MARR, KCFE, UN, OSCE, GG, RS` (Russia-Georgia bilateral / CFE / UN-OSCE) |
| [[references/dos-cable-turkmenistan-2004-11\|ASHGABAT 1028 (12 Nov 2004)]] *(boundary case — NGO-name keyword, not a UAP narrative)* | **EUR/CACEN** (Bureau of European and Eurasian Affairs / Office of Caucasus and Central Asian Affairs) | from [[entities/amembassy-ashgabat\|AMEMBASSY Ashgabat]] → SECSTATE WASHDC | `AORC, TSPA, PREL, PGOV, EAID, OSCI, TX` (civil society / aid) |

The substantive pair (1985, 1994) shows that the same parent department (State) treats UAP traffic through whichever substantive lens fits the case — military overflights vs. space-and-aviation phenomena — rather than through a UAP-specific tag or sub-bureau. ^[inferred] The 2001 Moscow and 2004 Ashgabat rows extend the observation through **two structurally distinct boundary cases** (figurative-UFO rhetoric and NGO-name keyword respectively — see [[concepts/figurative-ufo-rhetoric]]): even when the cable's *subject-line text* contains "UFO," the TAGS field still routes through the substantive bureau. None of the four cables carries a `UFO` tag (**4-of-4** in the corpus). ^[extracted] All four cables route through **distinct action bureaus** (PM, OES/S, IO, EUR/CACEN) — consistent with the bureau-routing-by-question-class hypothesis. ^[inferred] Both the 2001 Moscow cable and the 2004 Ashgabat cable are **not** UAP-substantive records and are included here only to anchor the schema and bureau-routing observations. See [[references/dos-cable-russia-georgia-2001-10]] and [[references/dos-cable-turkmenistan-2004-11]] for the boundary-case framings.

## Institutional position (background)

State is one of the four oldest cabinet departments of the US executive branch. Its principal officer is the **Secretary of State** (`SECSTATE`), whose Washington headquarters cable address `SECSTATE WASHDC` appears as the action / info addressee on every diplomatic cable in the corpus. ^[inferred] Cables originate from US embassies abroad (signed by the Chief of Mission or designate), route through State's cable centre at headquarters, and from there to substantive bureaus by sub-address (`PM`, `OES/S`, etc.). ^[inferred]

## Why this matters for the corpus

- **Diplomatic-channel UAP intake** — State is the only federal department in the corpus whose intake apparatus is **a global cable network** rather than a bounded set of HQ offices. Every embassy is a potential intake node.
- **Two of the corpus's institutional intake nodes are State sub-units** — see [[entities/amembassy-port-moresby]] and [[entities/amembassy-dushanbe]].
- **State as recipient, not originator**: the 1963 [[references/hunter-1963-space-alien-race-memo|NASC alien-policy memo]] is **addressed to** State (specifically [[entities/robert-f-packard|Robert F. Packard]] at the Office of International Scientific Affairs) — i.e. the Executive Office of the President's policy staff treated State as the diplomatic instrument the contact-policy question would devolve onto. State is treated as the natural addressee for "what would US policy be if first contact happened?" three decades before the first archived cable.
- **No UAP-specific State bureau or tag exists in the corpus** — UAP matters surface under whichever substantive bureau owns the underlying activity (military / space-and-aviation).

## Open threads

- Locate / ingest State's 1985 reply traffic to PORT M 00199 and 1994 traffic following DUSHANBE 00259. ^[open]
- Identify any State Department UFO desk officer or standing intake procedure (none visible in the corpus). ^[open]
- Locate any 1970s–80s State Department UAP-adjacent traffic that would bridge the 1963 NASC policy artifact and the 1985 PNG cable. ^[open]
- Resolve the State Department reply (if any) to the 1963 [[entities/maxwell-w-hunter|Hunter]] memo addressed to OISA. ^[open]

## Sources

- [[references/dos-cable-papua-new-guinea-1985-01]] — PM-routed cable.
- [[references/dos-cable-kazakhstan-1994-01]] — OES/S-routed cable.
- [[references/dos-cable-russia-georgia-2001-10]] — IO-routed cable (boundary case; figurative-UFO rhetoric).
- [[references/dos-cable-turkmenistan-2004-11]] — EUR/CACEN-routed cable (boundary case; NGO-name keyword).
- [[references/hunter-1963-space-alien-race-memo]] — addressed to State/OISA.

## See also

- [[concepts/diplomatic-channel-uap-reporting]]
- [[concepts/figurative-ufo-rhetoric]] — typology covering the two boundary-case cables.
- [[entities/amembassy-port-moresby]]
- [[entities/amembassy-dushanbe]]
- [[entities/amembassy-moscow]] — boundary-case originating post (2001 cable; figurative)
- [[entities/amembassy-ashgabat]] — boundary-case originating post (2004 cable; referential)
- [[entities/alexander-vershbow]] — Ambassador / signer of MOSCOW 13169
- [[entities/george-krol]] — POLMINCOUNS / classifying officer of MOSCOW 13169
- [[entities/russia-mfa]] — counterparty in MOSCOW 13169
- [[entities/union-of-ufologists-turkmenabat]] — boundary-case subject of the 2004 cable
- [[entities/robert-f-packard]]
- [[entities/uscincpac]]
- [[projects/uap/uap]]
