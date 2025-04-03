Comparison of 
Generated at Thursday, April 3, 2025 8:18:10 AM

### Benefit Category Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Benefit Category Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/benefit-category` |
| Version | 3.0.2 |
| Description | This value set includes a smattering of Benefit Category codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1075` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/EligibilityRequest` | `EligibilityRequest.benefitCategory` | `http://hl7.org/fhir/ValueSet/benefit-category` | `Example` | Type of services covered |
| `http://hl7.org/fhir/StructureDefinition/EligibilityResponse` | `EligibilityResponse.insurance.benefitBalance.category` | `http://hl7.org/fhir/ValueSet/benefit-category` | `Example` | Type of services covered |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.benefitBalance.category` | `http://hl7.org/fhir/ValueSet/benefit-category` | `Example` | Type of services covered |

### Referenced Systems

* `http://hl7.org/fhir/benefit-category`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/benefit-category` | `medical` | Medical Health Coverage |
| `http://hl7.org/fhir/benefit-category` | `oral` | Dental and Oral Health Coverage |
| `http://hl7.org/fhir/benefit-category` | `pharmacy` | Pharmacy Coverage |
| `http://hl7.org/fhir/benefit-category` | `vision` | Vision Health Coverage |
