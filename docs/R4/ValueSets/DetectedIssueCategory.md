Comparison of 
Generated at Tuesday, April 1, 2025 1:39:18 PM

### DetectedIssueCategory

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | DetectedIssueCategory |
| Canonical URL | `http://hl7.org/fhir/ValueSet/detectedissue-category` |
| Version | 4.0.1 |
| Description | Kinds of issues or contraindications, such as 'drug-drug interaction', 'duplicate therapy', etc. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2370` |
| Database Concept Count | `27` |
| Database Active Concept Count | `27` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DetectedIssue` | `DetectedIssue.code` | `http://hl7.org/fhir/ValueSet/detectedissue-category` | `Preferred` | Issue Category, e.g. drug-drug, duplicate therapy, etc. |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-ActCode`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ALLDONE` | already performed |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ALRTENDLATE` | end too late alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ALRTSTRTLATE` | start too late alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DACT` | drug action detected issue |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DRG` | Drug Interaction Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ENDLATE` | End Too Late Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FOOD` | Food Interaction Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FULFIL` | fulfillment alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HELD` | held/suspended alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HISTORIC` | record recorded as historical |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INTERVAL` | outside requested time |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MINFREQ` | too soon within frequency based on the usage |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NHP` | Natural Health Product Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NONRX` | Non-Prescription Interaction Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOTACTN` | no longer actionable |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOTEQUIV` | not equivalent alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOTEQUIVGEN` | not generically equivalent alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOTEQUIVTHER` | not therapeutically equivalent alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PATPREF` | violates stated preferences |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PATPREFALT` | violates stated preferences, alternate available |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PREVINEF` | previously ineffective |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `STRTLATE` | Start Too Late Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TIME` | timing detected issue |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TIMING` | event timing incorrect alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TOOLATE` | Refill Too Late Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TOOSOON` | Refill Too Soon Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TPROD` | Therapeutic Product Alert |
