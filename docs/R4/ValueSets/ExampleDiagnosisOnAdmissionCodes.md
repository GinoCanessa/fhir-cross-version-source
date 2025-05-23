Comparison of 
Generated at Monday, April 14, 2025 6:17:28 PM

### ExampleDiagnosisOnAdmissionCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ExampleDiagnosisOnAdmissionCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/ex-diagnosis-on-admission` |
| Version | 4.0.1 |
| Description | This value set includes example Diagnosis on Admission codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2430` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.diagnosis.onAdmission` | `http://hl7.org/fhir/ValueSet/ex-diagnosis-on-admission` | `Example` | Present on admission |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.diagnosis.onAdmission` | `http://hl7.org/fhir/ValueSet/ex-diagnosis-on-admission` | `Example` | Present on admission |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/ex-diagnosis-on-admission`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/ex-diagnosis-on-admission` | `n` | No |
| `http://terminology.hl7.org/CodeSystem/ex-diagnosis-on-admission` | `u` | Unknown |
| `http://terminology.hl7.org/CodeSystem/ex-diagnosis-on-admission` | `w` | Undetermined |
| `http://terminology.hl7.org/CodeSystem/ex-diagnosis-on-admission` | `y` | Yes |
