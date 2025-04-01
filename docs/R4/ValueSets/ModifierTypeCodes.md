Comparison of 
Generated at Tuesday, April 1, 2025 1:39:17 PM

### ModifierTypeCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ModifierTypeCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/claim-modifiers` |
| Version | 4.0.1 |
| Description | This value set includes sample Modifier type codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2265` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.modifier` | `http://hl7.org/fhir/ValueSet/claim-modifiers` | `Example` | Product or service billing modifiers |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.detail.modifier` | `http://hl7.org/fhir/ValueSet/claim-modifiers` | `Example` | Service/Product billing modifiers |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.detail.subDetail.modifier` | `http://hl7.org/fhir/ValueSet/claim-modifiers` | `Example` | Service/Product billing modifiers |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.addItem.modifier` | `http://hl7.org/fhir/ValueSet/claim-modifiers` | `Example` | Service/Product billing modifiers |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.addItem.detail.modifier` | `http://hl7.org/fhir/ValueSet/claim-modifiers` | `Example` | Service/Product billing modifiers |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.addItem.detail.subDetail.modifier` | `http://hl7.org/fhir/ValueSet/claim-modifiers` | `Example` | Service/Product billing modifiers |
| `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityRequest` | `CoverageEligibilityRequest.item.modifier` | `http://hl7.org/fhir/ValueSet/claim-modifiers` | `Example` | Product or service billing modifiers |
| `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityResponse` | `CoverageEligibilityResponse.insurance.item.modifier` | `http://hl7.org/fhir/ValueSet/claim-modifiers` | `Example` | Product or service billing modifiers |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.modifier` | `http://hl7.org/fhir/ValueSet/claim-modifiers` | `Example` | Product or service billing modifiers |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.detail.modifier` | `http://hl7.org/fhir/ValueSet/claim-modifiers` | `Example` | Service/Product billing modifiers |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.detail.subDetail.modifier` | `http://hl7.org/fhir/ValueSet/claim-modifiers` | `Example` | Service/Product billing modifiers |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.addItem.modifier` | `http://hl7.org/fhir/ValueSet/claim-modifiers` | `Example` | Service/Product billing modifiers |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.addItem.detail.modifier` | `http://hl7.org/fhir/ValueSet/claim-modifiers` | `Example` | Service/Product billing modifiers |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.addItem.detail.subDetail.modifier` | `http://hl7.org/fhir/ValueSet/claim-modifiers` | `Example` | Service/Product billing modifiers |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/modifiers`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/modifiers` | `a` | Repair of prior service or installation |
| `http://terminology.hl7.org/CodeSystem/modifiers` | `b` | Temporary service or installation |
| `http://terminology.hl7.org/CodeSystem/modifiers` | `c` | TMJ treatment |
| `http://terminology.hl7.org/CodeSystem/modifiers` | `e` | Implant or associated with an implant |
| `http://terminology.hl7.org/CodeSystem/modifiers` | `rooh` | Rush or Outside of office hours |
| `http://terminology.hl7.org/CodeSystem/modifiers` | `x` | None |
