Comparison of 
Generated at Friday, April 4, 2025 2:58:37 PM

### Benefit Type Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Benefit Type Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/benefit-type` |
| Version | 3.0.2 |
| Description | This value set includes a smattering of Benefit type codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1079` |
| Database Concept Count | `12` |
| Database Active Concept Count | `12` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/EligibilityResponse` | `EligibilityResponse.insurance.benefitBalance.financial.type` | `http://hl7.org/fhir/ValueSet/benefit-type` | `Example` | Deductable, visits, benefit amount |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.benefitBalance.financial.type` | `http://hl7.org/fhir/ValueSet/benefit-type` | `Example` | Deductable, visits, benefit amount |

### Referenced Systems

* `http://hl7.org/fhir/benefit-type`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/benefit-type` | `benefit` | Benefit |
| `http://hl7.org/fhir/benefit-type` | `copay` | Copayment per service |
| `http://hl7.org/fhir/benefit-type` | `copay-maximum` | Copayment maximum per service |
| `http://hl7.org/fhir/benefit-type` | `copay-percent` | Copayment Percent per service |
| `http://hl7.org/fhir/benefit-type` | `deductable` | Deductable |
| `http://hl7.org/fhir/benefit-type` | `medical-primarycare` | Medical Primary Health Coverage |
| `http://hl7.org/fhir/benefit-type` | `pharmacy-dispense` | Pharmacy Dispense Coverage |
| `http://hl7.org/fhir/benefit-type` | `room` | Room |
| `http://hl7.org/fhir/benefit-type` | `vision-contacts` | Vision Contacts Coverage |
| `http://hl7.org/fhir/benefit-type` | `vision-exam` | Vision Exam |
| `http://hl7.org/fhir/benefit-type` | `vision-glasses` | Vision Glasses |
| `http://hl7.org/fhir/benefit-type` | `visit` | Visit |
