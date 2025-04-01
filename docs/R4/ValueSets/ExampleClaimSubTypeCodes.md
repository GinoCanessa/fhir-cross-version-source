Comparison of 
Generated at Tuesday, April 1, 2025 1:39:17 PM

### ExampleClaimSubTypeCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ExampleClaimSubTypeCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/claim-subtype` |
| Version | 4.0.1 |
| Description | This value set includes sample Claim SubType codes which are used to distinguish the claim types for example within type institutional there may be subtypes for emergency services, bed stay and transportation. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2266` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.subType` | `http://hl7.org/fhir/ValueSet/claim-subtype` | `Example` | More granular claim type |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.subType` | `http://hl7.org/fhir/ValueSet/claim-subtype` | `Example` | More granular claim type |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.subType` | `http://hl7.org/fhir/ValueSet/claim-subtype` | `Example` | More granular claim type |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/ex-claimsubtype`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/ex-claimsubtype` | `emergency` | Emergency Claim |
| `http://terminology.hl7.org/CodeSystem/ex-claimsubtype` | `ortho` | Orthodontic Claim |
