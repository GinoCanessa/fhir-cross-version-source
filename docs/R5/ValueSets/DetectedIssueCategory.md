Comparison of 
Generated at Monday, April 14, 2025 6:17:44 PM

### DetectedIssueCategory

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | DetectedIssueCategory |
| Canonical URL | `http://hl7.org/fhir/ValueSet/detectedissue-category` |
| Version | 5.0.0 |
| Description | Kinds of issues or contraindications, such as 'drug-drug interaction', 'duplicate therapy', etc. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4470` |
| Database Concept Count | `86` |
| Database Active Concept Count | `78` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DetectedIssue` | `DetectedIssue.category` | `http://hl7.org/fhir/ValueSet/detectedissue-category` | `Preferred` | Type of detected issue, e.g. drug-drug, duplicate therapy, etc |
| `http://hl7.org/fhir/StructureDefinition/DetectedIssue` | `DetectedIssue.code` | `http://hl7.org/fhir/ValueSet/detectedissue-category` | `Preferred` | Specific type of detected issue, e.g. drug-drug, duplicate therapy, etc |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-ActCode`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ABUSE` | commonly abused/misused alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ADALRT` | adult alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AGE` | Age Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ALGY` | Allergy Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ALLDONE` | already performed |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ALRTENDLATE` | end too late alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ALRTSTRTLATE` | start too late alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CAREGAP` | Caregap |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CODINGGAP` | Codinggap |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `COMPLY` | Compliance Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `COND` | Condition Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `CREACT` | common reaction alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DACT` | drug action detected issue |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSE` | Dosage problem |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSECOND` | dosage-condition alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEDUR` | Dose-Duration Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEDURH` | Dose-Duration High Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEDURHIND` | Dose-Duration High for Indication Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEDURL` | Dose-Duration Low Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEDURLIND` | Dose-Duration Low for Indication Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEH` | High Dose Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEHIND` | High Dose for Indication Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEHINDA` | High Dose for Age Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEHINDSA` | High Dose for Height/Surface Area Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEHINDW` | High Dose for Weight Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEIVL` | Dose-Interval Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEIVLIND` | Dose-Interval for Indication Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSEL` | Low Dose Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSELIND` | Low Dose for Indication Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSELINDA` | Low Dose for Age Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSELINDSA` | Low Dose for Height/Surface Area Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DOSELINDW` | Low Dose for Weight Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DRG` | Drug Interaction Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DUPTHPCLS` | duplicate therapeutic alass alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DUPTHPGEN` | duplicate generic alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DUPTHPY` | Duplicate Therapy Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ENDLATE` | End Too Late Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FOOD` | Food Interaction Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FRAUD` | potential fraud |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FULFIL` | fulfillment alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `GEALRT` | geriatric alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `GEN` | Genetic Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `GEND` | Gender Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HELD` | held/suspended alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HGHT` |  |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HISTORIC` | record recorded as historical |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INT` | Intolerance Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `INTERVAL` | outside requested time |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LAB` | Lab Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `LACT` | Lactation Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MDOSE` | maximum dosage reached |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MINFREQ` | too soon within frequency based on the usage |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NHP` | Natural Health Product Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NONRX` | Non-Prescription Interaction Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOTACTN` | no longer actionable |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOTEQUIV` | not equivalent alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOTEQUIVGEN` | not generically equivalent alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOTEQUIVTHER` | not therapeutically equivalent alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `OBSA` | Observation Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PATPREF` | violates stated preferences |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PATPREFALT` | violates stated preferences, alternate available |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PEALRT` | pediatric alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PLYDOC` | Poly-orderer Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PLYPHRM` | Poly-supplier Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PREG` | Pregnancy Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PREVINEF` | previously ineffective |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RALG` | Related Allergy Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RAR` | Related Prior Reaction Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `REACT` | Reaction Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RINT` | Related Intolerance Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `RREACT` | Related Reaction Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `STRTLATE` | Start Too Late Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TIME` | timing detected issue |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TIMING` | event timing incorrect alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TOOLATE` | Refill Too Late Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TOOSOON` | Refill Too Soon Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `TPROD` | Therapeutic Product Alert |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `WGHT` |  |
