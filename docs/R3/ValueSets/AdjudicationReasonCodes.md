Comparison of 
Generated at Monday, April 14, 2025 6:17:19 PM

### Adjudication Reason Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Adjudication Reason Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/adjudication-reason` |
| Version | 3.0.2 |
| Description | This value set includes smattering of Adjudication Reason codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1039` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.item.adjudication.reason` | `http://hl7.org/fhir/ValueSet/adjudication-reason` | `Example` | Explanation of Adjudication outcome |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.adjudication.reason` | `http://hl7.org/fhir/ValueSet/adjudication-reason` | `Example` | Explanation of Adjudication outcome |

### Referenced Systems

* `http://hl7.org/fhir/adjudication-reason`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/adjudication-reason` | `ar001` | Not covered |
| `http://hl7.org/fhir/adjudication-reason` | `ar002` | Plan Limit Reached |
