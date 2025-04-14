Comparison of 
Generated at Monday, April 14, 2025 6:17:43 PM

### ICD10ProcedureCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ICD10ProcedureCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/icd-10-procedures` |
| Version | 5.0.0 |
| Description | This value set includes sample ICD-10 Procedure codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4607` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.procedure.procedure[x]` | `http://hl7.org/fhir/ValueSet/icd-10-procedures` | `Example` | Specific clinical procedure |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.procedure.procedure[x]` | `http://hl7.org/fhir/ValueSet/icd-10-procedures` | `Example` | Specific clinical procedure |

### Referenced Systems

* `http://hl7.org/fhir/sid/ex-icd-10-procedures`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/sid/ex-icd-10-procedures` | `123001` | PROC-1 |
| `http://hl7.org/fhir/sid/ex-icd-10-procedures` | `123002` | PROC-2 |
| `http://hl7.org/fhir/sid/ex-icd-10-procedures` | `123003` | PROC-3 |
