Comparison of 
Generated at Thursday, April 3, 2025 8:18:16 AM

### v3.ActSubstanceAdminSubstitutionCode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | v3.ActSubstanceAdminSubstitutionCode |
| Canonical URL | `http://terminology.hl7.org/ValueSet/v3-ActSubstanceAdminSubstitutionCode` |
| Version | 2014-03-26 |
| Description | No Description Provided |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `3310` |
| Database Concept Count | `9` |
| Database Active Concept Count | `9` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/MedicationDispense` | `MedicationDispense.substitution.type` | `http://terminology.hl7.org/ValueSet/v3-ActSubstanceAdminSubstitutionCode` | `Example` | Code signifying whether a different drug was dispensed from what was prescribed |
| `http://hl7.org/fhir/StructureDefinition/MedicationRequest` | `MedicationRequest.substitution.allowed[x]` | `http://terminology.hl7.org/ValueSet/v3-ActSubstanceAdminSubstitutionCode` | `Example` | Whether substitution is allowed or not |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-substanceAdminSubstitution`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v3-substanceAdminSubstitution` | `BC` | brand composition |
| `http://terminology.hl7.org/CodeSystem/v3-substanceAdminSubstitution` | `E` | equivalent |
| `http://terminology.hl7.org/CodeSystem/v3-substanceAdminSubstitution` | `EC` | equivalent composition |
| `http://terminology.hl7.org/CodeSystem/v3-substanceAdminSubstitution` | `F` | formulary |
| `http://terminology.hl7.org/CodeSystem/v3-substanceAdminSubstitution` | `G` | generic composition |
| `http://terminology.hl7.org/CodeSystem/v3-substanceAdminSubstitution` | `N` | none |
| `http://terminology.hl7.org/CodeSystem/v3-substanceAdminSubstitution` | `TB` | therapeutic brand |
| `http://terminology.hl7.org/CodeSystem/v3-substanceAdminSubstitution` | `TE` | therapeutic alternative |
| `http://terminology.hl7.org/CodeSystem/v3-substanceAdminSubstitution` | `TG` | therapeutic generic |
