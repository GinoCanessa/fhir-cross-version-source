Comparison of 
Generated at Thursday, April 3, 2025 8:18:09 AM

### Modifier type Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Modifier type Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/claim-modifiers` |
| Version | 3.0.2 |
| Description | This value set includes sample Modifier type codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1107` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.modifier` | `http://hl7.org/fhir/ValueSet/claim-modifiers` | `Example` | Service/Product billing modifiers |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.detail.modifier` | `http://hl7.org/fhir/ValueSet/claim-modifiers` | `Example` | Service/Product billing modifiers |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.detail.subDetail.modifier` | `http://hl7.org/fhir/ValueSet/claim-modifiers` | `Example` | Service/Product billing modifiers |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.addItem.modifier` | `http://hl7.org/fhir/ValueSet/claim-modifiers` | `Example` | Service/Product billing modifiers |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.addItem.detail.modifier` | `http://hl7.org/fhir/ValueSet/claim-modifiers` | `Example` | Service/Product billing modifiers |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.modifier` | `http://hl7.org/fhir/ValueSet/claim-modifiers` | `Example` | Service/Product billing modifiers |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.detail.modifier` | `http://hl7.org/fhir/ValueSet/claim-modifiers` | `Example` | Service/Product billing modifiers |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.detail.subDetail.modifier` | `http://hl7.org/fhir/ValueSet/claim-modifiers` | `Example` | Service/Product billing modifiers |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.addItem.modifier` | `http://hl7.org/fhir/ValueSet/claim-modifiers` | `Example` | Service/Product billing modifiers |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.addItem.detail.modifier` | `http://hl7.org/fhir/ValueSet/claim-modifiers` | `Example` | Service/Product billing modifiers |

### Referenced Systems

* `http://hl7.org/fhir/modifiers`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/modifiers` | `a` | Repair of prior service or installation |
| `http://hl7.org/fhir/modifiers` | `b` | Temporary service or installation |
| `http://hl7.org/fhir/modifiers` | `c` | TMJ treatment |
| `http://hl7.org/fhir/modifiers` | `e` | Implant or associated with an implant |
| `http://hl7.org/fhir/modifiers` | `rooh` | Rush or Outside of office hours |
| `http://hl7.org/fhir/modifiers` | `x` | None |
