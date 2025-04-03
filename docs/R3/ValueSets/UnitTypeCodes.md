Comparison of 
Generated at Thursday, April 3, 2025 8:18:10 AM

### Unit Type Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Unit Type Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/benefit-unit` |
| Version | 3.0.2 |
| Description | This value set includes a smattering of Unit type codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1080` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/EligibilityResponse` | `EligibilityResponse.insurance.benefitBalance.unit` | `http://hl7.org/fhir/ValueSet/benefit-unit` | `Example` | Individual or family |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.benefitBalance.unit` | `http://hl7.org/fhir/ValueSet/benefit-unit` | `Example` | Individual or family |

### Referenced Systems

* `http://hl7.org/fhir/benefit-unit`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/benefit-unit` | `family` | Family |
| `http://hl7.org/fhir/benefit-unit` | `individual` | Individual |
