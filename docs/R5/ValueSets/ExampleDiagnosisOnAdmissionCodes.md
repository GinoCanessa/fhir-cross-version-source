Comparison of 
Generated at Monday, April 14, 2025 6:17:44 PM

### ExampleDiagnosisOnAdmissionCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ExampleDiagnosisOnAdmissionCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/ex-diagnosis-on-admission` |
| Version | 5.0.0 |
| Description | This value set includes example Diagnosis on Admission codes. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `4550` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
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
| `http://terminology.hl7.org/CodeSystem/ex-diagnosis-on-admission` | `no` | No |
| `http://terminology.hl7.org/CodeSystem/ex-diagnosis-on-admission` | `unknown` | Unknown |
| `http://terminology.hl7.org/CodeSystem/ex-diagnosis-on-admission` | `yes` | Yes |
