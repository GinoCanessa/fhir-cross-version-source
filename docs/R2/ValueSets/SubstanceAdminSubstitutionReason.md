Comparison of 
Generated at Monday, April 14, 2025 6:17:15 PM

### SubstanceAdminSubstitutionReason

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | SubstanceAdminSubstitutionReason |
| Canonical URL | `http://hl7.org/fhir/ValueSet/v3-SubstanceAdminSubstitutionReason` |
| Version | 2014-03-26 |
| Description | No Description Provided |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `991` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/MedicationDispense` | `MedicationDispense.substitution.reason` | `http://hl7.org/fhir/ValueSet/v3-SubstanceAdminSubstitutionReason` | `Example` | Why was substitution made |
| `http://hl7.org/fhir/StructureDefinition/MedicationOrder` | `MedicationOrder.substitution.reason` | `http://hl7.org/fhir/ValueSet/v3-SubstanceAdminSubstitutionReason` | `Example` | Why should (not) substitution be made |

### Referenced Systems

* `http://hl7.org/fhir/v3/ActReason`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/v3/ActReason` | `CT` | continuing therapy |
| `http://hl7.org/fhir/v3/ActReason` | `FP` | formulary policy |
| `http://hl7.org/fhir/v3/ActReason` | `OS` | out of stock |
| `http://hl7.org/fhir/v3/ActReason` | `RR` | regulatory requirement |
