Comparison of 
Generated at Friday, April 4, 2025 2:58:58 PM

### ExampleProgramReasonCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ExampleProgramReasonCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/ex-program-code` |
| Version | 5.0.0 |
| Description | This value set includes sample Program Reason Span codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4555` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.programCode` | `http://hl7.org/fhir/ValueSet/ex-program-code` | `Example` | Program the product or service is provided under |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.detail.programCode` | `http://hl7.org/fhir/ValueSet/ex-program-code` | `Example` | Program the product or service is provided under |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.detail.subDetail.programCode` | `http://hl7.org/fhir/ValueSet/ex-program-code` | `Example` | Program the product or service is provided under |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.addItem.programCode` | `http://hl7.org/fhir/ValueSet/ex-program-code` | `Example` | Program the product or service is provided under |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.programCode` | `http://hl7.org/fhir/ValueSet/ex-program-code` | `Example` | Program the product or service is provided under |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.detail.programCode` | `http://hl7.org/fhir/ValueSet/ex-program-code` | `Example` | Program the product or service is provided under |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.detail.subDetail.programCode` | `http://hl7.org/fhir/ValueSet/ex-program-code` | `Example` | Program the product or service is provided under |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.addItem.programCode` | `http://hl7.org/fhir/ValueSet/ex-program-code` | `Example` | Program the product or service is provided under |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/ex-programcode`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/ex-programcode` | `as` | Child Asthma |
| `http://terminology.hl7.org/CodeSystem/ex-programcode` | `auscr` | Autism Screening |
| `http://terminology.hl7.org/CodeSystem/ex-programcode` | `hd` | Hemodialysis |
| `http://terminology.hl7.org/CodeSystem/ex-programcode` | `none` | None |
