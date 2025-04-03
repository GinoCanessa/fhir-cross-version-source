Comparison of 
Generated at Thursday, April 3, 2025 8:18:16 AM

### ExceptionCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ExceptionCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/claim-exception` |
| Version | 4.0.1 |
| Description | This value set includes sample Exception codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2263` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.supportingInfo.code` | `http://hl7.org/fhir/ValueSet/claim-exception` | `Example` | Type of information |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.supportingInfo.code` | `http://hl7.org/fhir/ValueSet/claim-exception` | `Example` | Type of information |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/claim-exception`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/claim-exception` | `disabled` | Disabled |
| `http://terminology.hl7.org/CodeSystem/claim-exception` | `student` | Student (Fulltime) |
