Comparison of 
Generated at Monday, April 14, 2025 6:17:35 PM

### ClaimCareTeamRoleCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ClaimCareTeamRoleCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/claim-careteamrole` |
| Version | 4.3.0 |
| Description | This value set includes sample Claim Care Team Role codes. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `3594` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.careTeam.role` | `http://hl7.org/fhir/ValueSet/claim-careteamrole` | `Example` | Function within the team |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.careTeam.role` | `http://hl7.org/fhir/ValueSet/claim-careteamrole` | `Example` | Function within the team |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/claimcareteamrole`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/claimcareteamrole` | `assist` | Assisting Provider |
| `http://terminology.hl7.org/CodeSystem/claimcareteamrole` | `other` | Other |
| `http://terminology.hl7.org/CodeSystem/claimcareteamrole` | `primary` | Primary provider |
| `http://terminology.hl7.org/CodeSystem/claimcareteamrole` | `supervisor` | Supervising Provider |
