Comparison of 
Generated at Friday, April 4, 2025 2:58:58 PM

### ExampleRevenueCenterCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ExampleRevenueCenterCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/ex-revenue-center` |
| Version | 5.0.0 |
| Description | This value set includes sample Revenue Center codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4556` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.detail.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.detail.subDetail.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.addItem.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.addItem.detail.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.addItem.detail.subDetail.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.detail.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.detail.subDetail.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.addItem.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.addItem.detail.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.addItem.detail.subDetail.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/ex-revenue-center`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/ex-revenue-center` | `0010` | Vision Clinic |
| `http://terminology.hl7.org/CodeSystem/ex-revenue-center` | `0011` | Dental Clinic |
| `http://terminology.hl7.org/CodeSystem/ex-revenue-center` | `1001` | Emergency |
