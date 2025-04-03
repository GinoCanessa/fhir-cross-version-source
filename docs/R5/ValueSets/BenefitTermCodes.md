Comparison of 
Generated at Thursday, April 3, 2025 8:18:31 AM

### BenefitTermCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | BenefitTermCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/benefit-term` |
| Version | 5.0.0 |
| Description | This value set includes a smattering of Benefit Term codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4316` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Coverage` | `Coverage.costToBeneficiary.term` | `http://hl7.org/fhir/ValueSet/benefit-term` | `Example` | Annual or lifetime |
| `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityResponse` | `CoverageEligibilityResponse.insurance.item.term` | `http://hl7.org/fhir/ValueSet/benefit-term` | `Example` | Annual or lifetime |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.benefitBalance.term` | `http://hl7.org/fhir/ValueSet/benefit-term` | `Example` | Annual or lifetime |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/benefit-term`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/benefit-term` | `annual` | Annual |
| `http://terminology.hl7.org/CodeSystem/benefit-term` | `day` | Day |
| `http://terminology.hl7.org/CodeSystem/benefit-term` | `lifetime` | Lifetime |
