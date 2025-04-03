Comparison of 
Generated at Thursday, April 3, 2025 8:18:10 AM

### Detected Issue Category

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Detected Issue Category |
| Canonical URL | `http://hl7.org/fhir/ValueSet/detectedissue-category` |
| Version | 3.0.2 |
| Description | Kinds of issues or contraindications, such as 'drug-drug interaction', 'duplicate therapy', etc. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1180` |
| Database Concept Count | `27` |
| Database Active Concept Count | `27` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DetectedIssue` | `DetectedIssue.category` | `http://hl7.org/fhir/ValueSet/detectedissue-category` | `Preferred` | Issue Category, e.g. drug-drug, duplicate therapy, etc. |

### Referenced Systems

* `http://hl7.org/fhir/v3/ActCode`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/v3/ActCode` | `ALLDONE` | already performed |
| `http://hl7.org/fhir/v3/ActCode` | `ALRTENDLATE` | end too late alert |
| `http://hl7.org/fhir/v3/ActCode` | `ALRTSTRTLATE` | start too late alert |
| `http://hl7.org/fhir/v3/ActCode` | `DACT` | drug action detected issue |
| `http://hl7.org/fhir/v3/ActCode` | `DRG` | Drug Interaction Alert |
| `http://hl7.org/fhir/v3/ActCode` | `ENDLATE` | End Too Late Alert |
| `http://hl7.org/fhir/v3/ActCode` | `FOOD` | Food Interaction Alert |
| `http://hl7.org/fhir/v3/ActCode` | `FULFIL` | fulfillment alert |
| `http://hl7.org/fhir/v3/ActCode` | `HELD` | held/suspended alert |
| `http://hl7.org/fhir/v3/ActCode` | `HISTORIC` | record recorded as historical |
| `http://hl7.org/fhir/v3/ActCode` | `INTERVAL` | outside requested time |
| `http://hl7.org/fhir/v3/ActCode` | `MINFREQ` | too soon within frequency based on the usage |
| `http://hl7.org/fhir/v3/ActCode` | `NHP` | Natural Health Product Alert |
| `http://hl7.org/fhir/v3/ActCode` | `NONRX` | Non-Prescription Interaction Alert |
| `http://hl7.org/fhir/v3/ActCode` | `NOTACTN` | no longer actionable |
| `http://hl7.org/fhir/v3/ActCode` | `NOTEQUIV` | not equivalent alert |
| `http://hl7.org/fhir/v3/ActCode` | `NOTEQUIVGEN` | not generically equivalent alert |
| `http://hl7.org/fhir/v3/ActCode` | `NOTEQUIVTHER` | not therapeutically equivalent alert |
| `http://hl7.org/fhir/v3/ActCode` | `PATPREF` | violates stated preferences |
| `http://hl7.org/fhir/v3/ActCode` | `PATPREFALT` | violates stated preferences, alternate available |
| `http://hl7.org/fhir/v3/ActCode` | `PREVINEF` | previously ineffective |
| `http://hl7.org/fhir/v3/ActCode` | `STRTLATE` | Start Too Late Alert |
| `http://hl7.org/fhir/v3/ActCode` | `TIME` | timing detected issue |
| `http://hl7.org/fhir/v3/ActCode` | `TIMING` | event timing incorrect alert |
| `http://hl7.org/fhir/v3/ActCode` | `TOOLATE` | Refill Too Late Alert |
| `http://hl7.org/fhir/v3/ActCode` | `TOOSOON` | Refill Too Soon Alert |
| `http://hl7.org/fhir/v3/ActCode` | `TPROD` | Therapeutic Product Alert |
