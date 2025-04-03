Comparison of 
Generated at Thursday, April 3, 2025 8:18:09 AM

### ICD-10 Procedure Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | ICD-10 Procedure Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/icd-10-procedures` |
| Version | 3.0.2 |
| Description | This value set includes sample ICD-10 Procedure codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1269` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.procedure.procedure[x]` | `http://hl7.org/fhir/ValueSet/icd-10-procedures` | `Example` | Patient's list of procedures performed |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.procedure.procedure[x]` | `http://hl7.org/fhir/ValueSet/icd-10-procedures` | `Example` | Patient's list of procedures performed |

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
