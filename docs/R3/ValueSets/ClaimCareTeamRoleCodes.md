Comparison of 
Generated at Friday, April 4, 2025 2:58:36 PM

### Claim Care Team Role Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Claim Care Team Role Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/claim-careteamrole` |
| Version | 3.0.2 |
| Description | This value set includes sample Claim Care Team Role codes. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `1104` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.careTeam.role` | `http://hl7.org/fhir/ValueSet/claim-careteamrole` | `Example` | Role on the team |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.careTeam.role` | `http://hl7.org/fhir/ValueSet/claim-careteamrole` | `Example` | Role on the team |

### Referenced Systems

* `http://hl7.org/fhir/claimcareteamrole`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/claimcareteamrole` | `assist` | Assisting Provider |
| `http://hl7.org/fhir/claimcareteamrole` | `other` | Other |
| `http://hl7.org/fhir/claimcareteamrole` | `primary` | Primary provider |
| `http://hl7.org/fhir/claimcareteamrole` | `supervisor` | Supervising Provider |
