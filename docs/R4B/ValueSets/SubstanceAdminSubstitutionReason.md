Comparison of 
Generated at Monday, April 14, 2025 6:17:35 PM

### SubstanceAdminSubstitutionReason

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | SubstanceAdminSubstitutionReason |
| Canonical URL | `http://terminology.hl7.org/ValueSet/v3-SubstanceAdminSubstitutionReason` |
| Version | 2.0.0 |
| Description |  |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `4232` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/MedicationDispense` | `MedicationDispense.substitution.reason` | `http://terminology.hl7.org/ValueSet/v3-SubstanceAdminSubstitutionReason` | `Example` | Why was substitution made |
| `http://hl7.org/fhir/StructureDefinition/MedicationRequest` | `MedicationRequest.substitution.reason` | `http://terminology.hl7.org/ValueSet/v3-SubstanceAdminSubstitutionReason` | `Example` | Why should (not) substitution be made |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-ActReason`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `CT` | continuing therapy |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `FP` | formulary policy |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `OS` | out of stock |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `RR` | regulatory requirement |
