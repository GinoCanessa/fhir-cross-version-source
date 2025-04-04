Comparison of 
Generated at Friday, April 4, 2025 2:58:36 PM

### Adjudication Value Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Adjudication Value Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/adjudication` |
| Version | 3.0.2 |
| Description | This value set includes a smattering of Adjudication Value codes which includes codes to indicate the amounts eligible under the plan, the amount of benefit, copays etc. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1037` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.item.adjudication.category` | `http://hl7.org/fhir/ValueSet/adjudication` | `Example` | Adjudication category such as co-pay, eligible, benefit, etc. |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.adjudication.category` | `http://hl7.org/fhir/ValueSet/adjudication` | `Example` | Adjudication category such as co-pay, eligible, benefit, etc. |

### Referenced Systems

* `http://hl7.org/fhir/adjudication`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/adjudication` | `benefit` | Benefit Amount |
| `http://hl7.org/fhir/adjudication` | `copay` | CoPay |
| `http://hl7.org/fhir/adjudication` | `deductible` | Deductable |
| `http://hl7.org/fhir/adjudication` | `eligible` | Eligible Amount |
| `http://hl7.org/fhir/adjudication` | `eligpercent` | Eligible % |
| `http://hl7.org/fhir/adjudication` | `tax` | Emergency Department |
| `http://hl7.org/fhir/adjudication` | `total` | Total |
