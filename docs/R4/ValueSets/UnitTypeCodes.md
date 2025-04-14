Comparison of 
Generated at Monday, April 14, 2025 6:17:27 PM

### UnitTypeCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | UnitTypeCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/benefit-unit` |
| Version | 4.0.1 |
| Description | This value set includes a smattering of Unit type codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2236` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityResponse` | `CoverageEligibilityResponse.insurance.item.unit` | `http://hl7.org/fhir/ValueSet/benefit-unit` | `Example` | Individual or family |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.benefitBalance.unit` | `http://hl7.org/fhir/ValueSet/benefit-unit` | `Example` | Individual or family |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/benefit-unit`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/benefit-unit` | `family` | Family |
| `http://terminology.hl7.org/CodeSystem/benefit-unit` | `individual` | Individual |
