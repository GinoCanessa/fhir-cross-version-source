Comparison of 
Generated at Friday, April 4, 2025 2:58:51 PM

### AdjudicationValueCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | AdjudicationValueCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/adjudication` |
| Version | 4.3.0 |
| Description | This value set includes a smattering of Adjudication Value codes which includes codes to indicate the amounts eligible under the plan, the amount of benefit, copays etc. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3505` |
| Database Concept Count | `8` |
| Database Active Concept Count | `8` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.item.adjudication.category` | `http://hl7.org/fhir/ValueSet/adjudication` | `Example` | Type of adjudication information |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.total.category` | `http://hl7.org/fhir/ValueSet/adjudication` | `Example` | Type of adjudication information |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.adjudication.category` | `http://hl7.org/fhir/ValueSet/adjudication` | `Example` | Type of adjudication information |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.total.category` | `http://hl7.org/fhir/ValueSet/adjudication` | `Example` | Type of adjudication information |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/adjudication`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/adjudication` | `benefit` | Benefit Amount |
| `http://terminology.hl7.org/CodeSystem/adjudication` | `copay` | CoPay |
| `http://terminology.hl7.org/CodeSystem/adjudication` | `deductible` | Deductible |
| `http://terminology.hl7.org/CodeSystem/adjudication` | `eligible` | Eligible Amount |
| `http://terminology.hl7.org/CodeSystem/adjudication` | `eligpercent` | Eligible % |
| `http://terminology.hl7.org/CodeSystem/adjudication` | `submitted` | Submitted Amount |
| `http://terminology.hl7.org/CodeSystem/adjudication` | `tax` | Tax |
| `http://terminology.hl7.org/CodeSystem/adjudication` | `unallocdeduct` | Unallocated Deductible |
