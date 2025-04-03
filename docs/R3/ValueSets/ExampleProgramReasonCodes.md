Comparison of 
Generated at Thursday, April 3, 2025 8:18:09 AM

### Example Program Reason Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Example Program Reason Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/ex-program-code` |
| Version | 3.0.2 |
| Description | This value set includes sample Program Reason Span codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1230` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.programCode` | `http://hl7.org/fhir/ValueSet/ex-program-code` | `Example` | Program specific reason for item inclusion |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.detail.programCode` | `http://hl7.org/fhir/ValueSet/ex-program-code` | `Example` | Program specific reason for item inclusion |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.detail.subDetail.programCode` | `http://hl7.org/fhir/ValueSet/ex-program-code` | `Example` | Program specific reason for item inclusion |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.programCode` | `http://hl7.org/fhir/ValueSet/ex-program-code` | `Example` | Program specific reason for item inclusion |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.detail.programCode` | `http://hl7.org/fhir/ValueSet/ex-program-code` | `Example` | Program specific reason for item inclusion |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.detail.subDetail.programCode` | `http://hl7.org/fhir/ValueSet/ex-program-code` | `Example` | Program specific reason for item inclusion |

### Referenced Systems

* `http://hl7.org/fhir/ex-programcode`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/ex-programcode` | `as` | Child Asthma |
| `http://hl7.org/fhir/ex-programcode` | `auscr` | Autism Screening |
| `http://hl7.org/fhir/ex-programcode` | `hd` | Heamodialisis |
| `http://hl7.org/fhir/ex-programcode` | `none` | None |
