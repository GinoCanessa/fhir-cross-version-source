Comparison of 
Generated at Monday, April 14, 2025 6:17:35 PM

### ProvenanceActivityType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ProvenanceActivityType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/provenance-activity-type` |
| Version | 4.3.0 |
| Description | This value set contains representative Activity Type codes, which includes codes from the HL7 DocumentCompletion, ActStatus, and DataOperations code system, W3C PROV-DM and PROV-N concepts and display names, several HL7 Lifecycle Event codes for which there are agreed upon definitions, and non-duplicated codes from the HL7 Security and Privacy Ontology Operations codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4007` |
| Database Concept Count | `72` |
| Database Active Concept Count | `69` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Provenance` | `Provenance.activity` | `http://hl7.org/fhir/ValueSet/provenance-activity-type` | `Extensible` | Activity that occurred |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-DocumentCompletion`
* `http://terminology.hl7.org/CodeSystem/v3-ActCode`
* `http://terminology.hl7.org/CodeSystem/v3-DataOperation`
* `http://terminology.hl7.org/CodeSystem/v3-ParticipationType`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ANONY` | anonymize |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DEID` | deidentify |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LABEL` | assign security label |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MASK` | mask |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PSEUD` | pseudonymize |
| `http://terminology.hl7.org/CodeSystem/v3-DataOperation` | `APPEND` | append |
| `http://terminology.hl7.org/CodeSystem/v3-DataOperation` | `CREATE` | create |
| `http://terminology.hl7.org/CodeSystem/v3-DataOperation` | `DELETE` | delete |
| `http://terminology.hl7.org/CodeSystem/v3-DataOperation` | `NULLIFY` | nullify |
| `http://terminology.hl7.org/CodeSystem/v3-DataOperation` | `UPDATE` | revise |
| `http://terminology.hl7.org/CodeSystem/v3-DocumentCompletion` | `LA` | legally authenticated |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `ADM` | admitter |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `ALY` | analyte |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `ATND` | attender |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `AUT` | author (originator) |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `AUTHEN` | authenticator |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `BBY` | baby |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `BEN` | beneficiary |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `CAGNT` | causative agent |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `CALLBCK` | callback contact |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `CAT` | catalyst |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `CON` | consultant |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `COV` | coverage target |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `CSM` | consumable |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `CST` | custodian |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `DEV` | device |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `DIR` | direct target |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `DIS` | discharger |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `DIST` | distributor |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `DON` | donor |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `DST` | destination |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `ELOC` | entry location |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `ENT` | data entry person |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `ESC` | escort |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `EXPAGNT` | ExposureAgent |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `EXPART` | ExposureParticipation |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `EXPTRGT` | ExposureTarget |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `EXSRC` | ExposureSource |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `GUAR` | guarantor party |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `HLD` | holder |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `IND` | indirect target |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `INF` | informant |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `IRCP` | information recipient |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `LA` | legal authenticator |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `LOC` | location |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `NOT` | ugent notification contact |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `NRD` | non-reuseable device |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `ORG` | origin |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `PART` | Participation |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `PPRF` | primary performer |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `PRCP` | primary information recipient |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `PRD` | product |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `PRF` | performer |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `RCT` | record target |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `RCV` | receiver |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `RDV` | reusable device |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `REF` | referrer |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `REFB` | Referred By |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `REFT` | Referred to |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `RESP` | responsible party |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `RML` | remote |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `SBJ` | subject |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `SPC` | specimen |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `SPRF` | secondary performer |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `TRANS` | Transcriber |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `TRC` | tracker |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `VIA` | via |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `VRF` | verifier |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `WIT` | witness |
