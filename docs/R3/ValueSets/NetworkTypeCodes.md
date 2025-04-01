Comparison of 
Generated at Tuesday, April 1, 2025 1:39:12 PM

### Network Type Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Network Type Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/benefit-network` |
| Version | 3.0.2 |
| Description | This value set includes a smattering of Network type codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1076` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/EligibilityResponse` | `EligibilityResponse.insurance.benefitBalance.network` | `http://hl7.org/fhir/ValueSet/benefit-network` | `Example` | In or out of network |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.benefitBalance.network` | `http://hl7.org/fhir/ValueSet/benefit-network` | `Example` | In or out of network |

### Referenced Systems

* `http://hl7.org/fhir/benefit-network`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/benefit-network` | `in` | In Network |
| `http://hl7.org/fhir/benefit-network` | `out` | Out of Network |
