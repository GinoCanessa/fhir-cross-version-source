Comparison of 
Generated at Monday, April 14, 2025 6:17:20 PM

### Example Claim SubType Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Example Claim SubType Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/claim-subtype` |
| Version | 3.0.2 |
| Description | This value set includes sample Claim SubType codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1108` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.subType` | `http://hl7.org/fhir/ValueSet/claim-subtype` | `Example` | Finer grained claim type information |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.subType` | `http://hl7.org/fhir/ValueSet/claim-subtype` | `Example` | Finer grained claim type information |

### Referenced Systems

* `http://hl7.org/fhir/ex-claimsubtype`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/ex-claimsubtype` | `emergency` | Emergency Claim |
| `http://hl7.org/fhir/ex-claimsubtype` | `ortho` | Orthodontic Claim |
