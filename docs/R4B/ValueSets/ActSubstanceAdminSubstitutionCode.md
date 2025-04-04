Comparison of 
Generated at Friday, April 4, 2025 2:58:51 PM

### ActSubstanceAdminSubstitutionCode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ActSubstanceAdminSubstitutionCode |
| Canonical URL | `http://terminology.hl7.org/ValueSet/v3-ActSubstanceAdminSubstitutionCode` |
| Version | 2.0.0 |
| Description |  |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `4225` |
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
