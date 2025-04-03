Comparison of 
Generated at Thursday, April 3, 2025 8:18:31 AM

### AdjudicationErrorCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | AdjudicationErrorCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/adjudication-error` |
| Version | 5.0.0 |
| Description | This value set includes a smattering of adjudication codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4259` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.error.code` | `http://hl7.org/fhir/ValueSet/adjudication-error` | `Example` | Error code detailing processing issues |
| `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityResponse` | `CoverageEligibilityResponse.error.code` | `http://hl7.org/fhir/ValueSet/adjudication-error` | `Example` | Error code detailing processing issues |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/adjudication-error`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/adjudication-error` | `a001` | Missing Identifier |
| `http://terminology.hl7.org/CodeSystem/adjudication-error` | `a002` | Missing Creation Date |
