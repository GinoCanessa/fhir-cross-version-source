Comparison of 
Generated at Monday, April 14, 2025 6:17:20 PM

### Exception Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Exception Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/claim-exception` |
| Version | 3.0.2 |
| Description | This value set includes sample Exception codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1105` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.information.code` | `http://hl7.org/fhir/ValueSet/claim-exception` | `Example` | Type of information |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.information.code` | `http://hl7.org/fhir/ValueSet/claim-exception` | `Example` | Type of information |

### Referenced Systems

* `http://hl7.org/fhir/claim-exception`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/claim-exception` | `disabled` | Disabled |
| `http://hl7.org/fhir/claim-exception` | `student` | Student (Fulltime) |
