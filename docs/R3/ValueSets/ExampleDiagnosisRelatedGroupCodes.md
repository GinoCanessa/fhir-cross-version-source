Comparison of 
Generated at Monday, April 14, 2025 6:17:21 PM

### Example Diagnosis Related Group Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Example Diagnosis Related Group Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/ex-diagnosisrelatedgroup` |
| Version | 3.0.2 |
| Description | This value set includes example Diagnosis Related Group codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1225` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.diagnosis.packageCode` | `http://hl7.org/fhir/ValueSet/ex-diagnosisrelatedgroup` | `Example` | Package billing code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.diagnosis.packageCode` | `http://hl7.org/fhir/ValueSet/ex-diagnosisrelatedgroup` | `Example` | Package billing code |

### Referenced Systems

* `http://hl7.org/fhir/ex-diagnosisrelatedgroup`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/ex-diagnosisrelatedgroup` | `100` | Normal Vaginal Delivery |
| `http://hl7.org/fhir/ex-diagnosisrelatedgroup` | `101` | Appendectomy - uncomplicated |
| `http://hl7.org/fhir/ex-diagnosisrelatedgroup` | `300` | Tooth abcess |
| `http://hl7.org/fhir/ex-diagnosisrelatedgroup` | `400` | Head trauma - concussion |
