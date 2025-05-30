Comparison of 
Generated at Monday, April 14, 2025 6:17:42 PM

### AdjudicationReasonCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | AdjudicationReasonCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/adjudication-reason` |
| Version | 5.0.0 |
| Description | This value set includes smattering of Adjudication Reason codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4260` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.item.adjudication.reason` | `http://hl7.org/fhir/ValueSet/adjudication-reason` | `Example` | Explanation of adjudication outcome |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.adjudication.reason` | `http://hl7.org/fhir/ValueSet/adjudication-reason` | `Example` | Explanation of adjudication outcome |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/adjudication-reason`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/adjudication-reason` | `ar001` | Not covered |
| `http://terminology.hl7.org/CodeSystem/adjudication-reason` | `ar002` | Plan Limit Reached |
