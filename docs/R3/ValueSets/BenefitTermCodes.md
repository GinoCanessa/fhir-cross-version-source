Comparison of 
Generated at Monday, April 14, 2025 6:17:21 PM

### Benefit Term Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Benefit Term Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/benefit-term` |
| Version | 3.0.2 |
| Description | This value set includes a smattering of Benefit Term codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1078` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/EligibilityResponse` | `EligibilityResponse.insurance.benefitBalance.term` | `http://hl7.org/fhir/ValueSet/benefit-term` | `Example` | Annual or lifetime |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.benefitBalance.term` | `http://hl7.org/fhir/ValueSet/benefit-term` | `Example` | Annual or lifetime |

### Referenced Systems

* `http://hl7.org/fhir/benefit-term`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/benefit-term` | `annual` | Annual |
| `http://hl7.org/fhir/benefit-term` | `day` | Day |
| `http://hl7.org/fhir/benefit-term` | `lifetime` | Lifetime |
