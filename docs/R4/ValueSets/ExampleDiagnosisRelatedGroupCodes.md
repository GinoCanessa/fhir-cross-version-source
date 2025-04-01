Comparison of 
Generated at Tuesday, April 1, 2025 1:39:18 PM

### ExampleDiagnosisRelatedGroupCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ExampleDiagnosisRelatedGroupCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/ex-diagnosisrelatedgroup` |
| Version | 4.0.1 |
| Description | This value set includes example Diagnosis Related Group codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2431` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.diagnosis.packageCode` | `http://hl7.org/fhir/ValueSet/ex-diagnosisrelatedgroup` | `Example` | Package billing code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.diagnosis.packageCode` | `http://hl7.org/fhir/ValueSet/ex-diagnosisrelatedgroup` | `Example` | Package billing code |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/ex-diagnosisrelatedgroup`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/ex-diagnosisrelatedgroup` | `100` | Normal Vaginal Delivery |
| `http://terminology.hl7.org/CodeSystem/ex-diagnosisrelatedgroup` | `101` | Appendectomy - uncomplicated |
| `http://terminology.hl7.org/CodeSystem/ex-diagnosisrelatedgroup` | `300` | Tooth abscess |
| `http://terminology.hl7.org/CodeSystem/ex-diagnosisrelatedgroup` | `400` | Head trauma - concussion |
