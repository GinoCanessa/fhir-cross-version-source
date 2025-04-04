Comparison of 
Generated at Friday, April 4, 2025 2:58:43 PM

### BenefitTypeCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | BenefitTypeCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/benefit-type` |
| Version | 4.0.1 |
| Description | This value set includes a smattering of Benefit type codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2235` |
| Database Concept Count | `12` |
| Database Active Concept Count | `12` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityResponse` | `CoverageEligibilityResponse.insurance.item.benefit.type` | `http://hl7.org/fhir/ValueSet/benefit-type` | `Example` | Benefit classification |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.benefitBalance.financial.type` | `http://hl7.org/fhir/ValueSet/benefit-type` | `Example` | Benefit classification |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/benefit-type`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/benefit-type` | `benefit` | Benefit |
| `http://terminology.hl7.org/CodeSystem/benefit-type` | `copay` | Copayment per service |
| `http://terminology.hl7.org/CodeSystem/benefit-type` | `copay-maximum` | Copayment maximum per service |
| `http://terminology.hl7.org/CodeSystem/benefit-type` | `copay-percent` | Copayment Percent per service |
| `http://terminology.hl7.org/CodeSystem/benefit-type` | `deductible` | Deductible |
| `http://terminology.hl7.org/CodeSystem/benefit-type` | `medical-primarycare` | Medical Primary Health Coverage |
| `http://terminology.hl7.org/CodeSystem/benefit-type` | `pharmacy-dispense` | Pharmacy Dispense Coverage |
| `http://terminology.hl7.org/CodeSystem/benefit-type` | `room` | Room |
| `http://terminology.hl7.org/CodeSystem/benefit-type` | `vision-contacts` | Vision Contacts Coverage |
| `http://terminology.hl7.org/CodeSystem/benefit-type` | `vision-exam` | Vision Exam |
| `http://terminology.hl7.org/CodeSystem/benefit-type` | `vision-glasses` | Vision Glasses |
| `http://terminology.hl7.org/CodeSystem/benefit-type` | `visit` | Visit |
