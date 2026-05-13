---
title: Operation Inherent Resolve (OIR)
category: entities
tags: [military, uap, isr]
aliases: [OIR, Operation Inherent Resolve, Op INHERENT RESOLVE, INHERENT RESOLVE]
sources: [sources/dow-uap-d10-mission-report-middle-east-may-2022.json, sources/dow-uap-d12-mission-report-iraq-may-2022.json, sources/dow-uap-d16-mission-report-syria-july-2022.json, sources/dow-uap-d19-mission-report-syria-february-21-2023.json, sources/dow-uap-d18-mission-report-iraq-december-2022.json]
summary: USCENTCOM coalition campaign against ISIS, active since Oct 2014. The dow-uap corpus anchors OIR at N=5+ within the full-Misrep class as a recurring `Mission Type` / parent-operation token covering Iraq + Syria sub-theaters; OIR cluster bifurcates into OIR-Iraq (d10/d12/d18) + OIR-Syria (d16/d19) under shared 609 CAOC / 432 AEW / AFCENT routing. ^[inferred — institutional context not stated in OCR]
provenance:
  extracted: 0.4
  inferred: 0.55
  ambiguous: 0.05
base_confidence: 0.6
lifecycle: draft
lifecycle_changed: 2026-05-13
created: 2026-05-13T14:00:00Z
updated: 2026-05-13T16:15:00Z
---

# Operation Inherent Resolve (OIR)

**Operation Inherent Resolve** — the US-led coalition combined joint task force operation against ISIS (Islamic State / Daesh), active since **October 2014** ^[inferred — open-source standard background; the wiki's dow-uap OCR names "Operation INHERENT RESOLVE" only as a parent-operation token without dating its origin]. The campaign covers operations in **Iraq + Syria** under [[entities/afcent|USCENTCOM]] tasking, with the Combined Joint Task Force HQ at **CJTF-OIR** ^[inferred]. The coalition includes US + UK + France + multiple regional partners ^[inferred].

This page is a **stub hub**. OIR appears in the dow-uap corpus as the **Mission Type / parent-operation token** of active-component and ANG USAF Misreps tasked across the 2022-2023 OIR sub-cluster — N=5+ documented attestations as of d35 ingest within the full-Misrep class (d10/d12/d14-contradicted/d16/d18/d19), routing through [[entities/609-caoc|609 CAOC]] and (when AFCENT-tasked) up to AFCENT MAJCOM.

## Role in the dow-uap corpus

OIR is the parent operation anchoring the **dow-uap 2022-2023 OIR cluster** — the second-largest within-corpus cluster after the 2020 NAVCENT cluster. The OIR cluster bifurcates into two sub-theater tracks:

### OIR-Iraq sub-cluster

- [[references/dow-uap-d10-mission-middle-east-2022-05-06|d10]] (6-7 May 2022) — first 2022-era dow-uap artifact + first OIR-tasking + first UTM 38S MGRS Levant + first MAG-supported Unit + first XCAS / REC\XCAS mission type. Active-component 432 AEW MQ-9, MAJCOM = AFCENT.
- [[references/dow-uap-d12-mission-iraq-2022-05-20|d12]] (20-21 May 2022) — anchors OIR May-2022 cluster at N=2 with d10 + first explicit named OIR sub-operation **OP PHANTOM FLEX** in corpus + first ANG full-Misrep + first ACC MAJCOM. ANG 163 AW / 196 ATKS California MQ-9, MAJCOM = ACC (gaining major command).
- [[references/dow-uap-d18-mission-iraq-2022-12-01|d18]] (1 Dec 2022) — OIR-Iraq-MB Dec 2022 + 482 ATKS / `20 FW` ^[ambiguous] MQ-9. MAJCOM = ACC (owning MAJCOM track).

### OIR-Syria sub-cluster

- [[references/dow-uap-d16-mission-syria-2022-07-30|d16]] (30-31 Jul 2022) — RESTORES OIR cluster at N=3 via sub-theater split + first OIR-Syria-interior + first 89 ATKS + first OJMS Muwaffaq Salti AB Jordan + first **TF CHOSIN** + first **OP SPECTRE DAGGER** + first UTM 37S OIR. Active 89 ATKS / 432 AEW MQ-9, MAJCOM = AFCENT.
- [[references/dow-uap-d19-mission-syria-2023-02-21|d19]] (21 Feb 2023) — first non-MQ-9 OIR platform: F-15E DCA. 389 EFS / 332 AEW F-15E, OJMS Jordan launch → ESSA Killbox, MAJCOM = AFCENT.

### EUCOM-tasked cousin (NOT OIR despite filename label)

- [[references/dow-uap-d14-mission-iraq-2022-05-29|d14]] (29-30 May 2022) — **CONTRADICTS** OIR May-2022 cluster at N=3. d14 is **USEUCOM-tasked** Eastern Mediterranean Russian-Mediterranean-Squadron watch, NOT OIR — despite `iraq` filename label decoding to Eastern Mediterranean MGRS coords (37SBV28). First **filename-curator-mismatch** in dow-uap series for the 2022 cluster (joins `arabian-gulf` + `djibouti` mismatches). MAJCOM = ACC (USEUCOM tasking, not AFCENT).

## OIR-class invariants (corpus-derived)

Across the 5 confirmed OIR-cluster Misreps:

| Field | Value | Attestation N |
|---|---|---|
| Parent operation | `Operation INHERENT RESOLVE` | N=5 byte-for-byte |
| Mission Type modifier | OIR appears as Mission Type qualifier or named sub-op (PHANTOM FLEX, SPECTRE DAGGER) | N=5 |
| 609 CAOC | Theater AOC | N=5 |
| 432 AEW (active-component subset) | POC Wing | N=4 (d10, d14-contradicted, d16, d18 ambiguous) |
| AFCENT (MAJCOM when active + AFCENT-tasked) | Theater MAJCOM | N=3 (d10 + d16 + d19) |
| ACC (MAJCOM when ANG or non-AFCENT) | Owning MAJCOM | N=3 (d12 + d18 + d14-contradicted) |
| Block D (`JS-250710-TM8S` release tranche) | Joint Staff release block | N=3 (d10 + d12 + d16); d14 also in Block D despite non-OIR tasking |

## Named OIR sub-operations attested in dow-uap

- **OP PHANTOM FLEX** — first explicit named OIR sub-operation in corpus (d12, 20 May 2022); supports MAG (Marine Aircraft Group ^[inferred]).
- **OP SPECTRE DAGGER** — second named OIR sub-operation (d16, 30 Jul 2022); supports **TF CHOSIN** (Task Force Chosin) over Dayr Az Zar UTM 37S eastern Syria.
- **OP HUMMER SICKLE** ^[ambiguous] — d14 names this sub-operation but d14 is USEUCOM-tasked (Russian-Mediterranean-Squadron watch), so it is **NOT** an OIR sub-operation; the same naming convention applies across both OIR and EUCOM theaters. ^[inferred]

## Significance for the corpus

- **OIR is the corpus's anchor for distinguishing theater-tasked OIR missions from EUCOM-tasked Eastern-Mediterranean missions** despite shared 432 AEW POC Wing + shared Joint Staff release block. The structural test is the **named parent-operation token** + **MAJCOM field**: OIR/AFCENT vs HUMMER SICKLE/ACC. ^[inferred]
- **OIR cluster contributes to Block D firming** at cross-COCOM N=4 byte-for-byte (`JS-250710-TM8S` aggregates CENTCOM-OIR + EUCOM watch under the same Joint Staff release tranche). Block D is decisively NOT operation-class specific. ^closed-by-dow-uap-d14
- **Sub-class 8 strict generalizes across OIR-tasking + NAVCENT-cluster + EUCOM watch** at 10-of-12 ≈ 83% within the d14 ingest window — OIR contributes 3 of those 10 attestations.

## Related entities and contexts

- [[entities/afcent|AFCENT]] — theater MAJCOM when OIR is active-component tasked.
- [[entities/609-caoc|609 CAOC]] — USCENTCOM AOC routing all OIR Misreps.
- [[entities/432-aew|432 AEW]] — primary active-component POC Wing in the OIR cluster.
- [[entities/482-atks|482 ATKS]] — d18 OIR-Iraq-MB squadron.
- [[entities/mq-9-reaper|MQ-9 Reaper]] — primary OIR ISR platform in the corpus.
- [[entities/dow-uap-foia-release|dow-uap FOIA release]] — release context.
- [[concepts/uap-aircraft-engagement|UAP-aircraft-engagement]] — sub-class 8 strict generalization across OIR + NAVCENT.
- [[concepts/range-fouler|range-fouler]] — adjacent dow-uap document class (no OIR range-fouler attested in dow-uap to date).

## Open threads

- **OIR start date in corpus.** dow-uap OCR does not date OIR's origin; standard attribution is Oct 2014 ^[open].
- **CJTF-OIR institutional structure.** Combined Joint Task Force HQ + coalition partner participation not stated in dow-uap OCR ^[open].
- **OIR end date.** OIR remained active as of the dow-uap latest event date (d19 Feb 2023) ^[extracted]; whether OIR is still active at corpus pre-publication date (2026) ^[open].
- **Named-sub-op enumeration.** Only PHANTOM FLEX + SPECTRE DAGGER attested in dow-uap; full OIR sub-operation roster is open ^[open].

## See also

- [[projects/uap/uap]] — project overview.
- [[entities/dow-uap-foia-release]] — release context.
