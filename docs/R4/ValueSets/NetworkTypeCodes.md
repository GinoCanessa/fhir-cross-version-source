Comparison of 
Generated at Monday, April 14, 2025 6:17:28 PM

### NetworkTypeCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | NetworkTypeCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/benefit-network` |
| Version | 4.0.1 |
| Description | This value set includes a smattering of Network type codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2233` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityResponse` | `CoverageEligibilityResponse.insurance.item.network` | `http://hl7.org/fhir/ValueSet/benefit-network` | `Example` | In or out of network |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.benefitBalance.network` | `http://hl7.org/fhir/ValueSet/benefit-network` | `Example` | In or out of network |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/benefit-network`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/benefit-network` | `in` | In Network |
| `http://terminology.hl7.org/CodeSystem/benefit-network` | `out` | Out of Network |
