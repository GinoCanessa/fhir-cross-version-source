Comparison of 
Generated at Thursday, April 3, 2025 8:18:32 AM

### DatesTypeCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | DatesTypeCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/datestype` |
| Version | 5.0.0 |
| Description | This value set includes sample Dates Type codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4463` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.event.type` | `http://hl7.org/fhir/ValueSet/datestype` | `Example` | Specific event |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.event.type` | `http://hl7.org/fhir/ValueSet/datestype` | `Example` | Specific event |
| `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityRequest` | `CoverageEligibilityRequest.event.type` | `http://hl7.org/fhir/ValueSet/datestype` | `Example` | Specific event |
| `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityResponse` | `CoverageEligibilityResponse.event.type` | `http://hl7.org/fhir/ValueSet/datestype` | `Example` | Specific event |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.event.type` | `http://hl7.org/fhir/ValueSet/datestype` | `Example` | Specific event |

### Referenced Systems

* `http://hl7.org/fhir/datestype`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/datestype` | `card-issued` | Card Issued |
| `http://hl7.org/fhir/datestype` | `claim-received` | Claim Received |
| `http://hl7.org/fhir/datestype` | `service-expected` | Service Expected |
