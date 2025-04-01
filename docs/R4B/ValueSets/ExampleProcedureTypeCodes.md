Comparison of 
Generated at Tuesday, April 1, 2025 1:39:25 PM

### ExampleProcedureTypeCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ExampleProcedureTypeCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/ex-procedure-type` |
| Version | 4.3.0 |
| Description | This value set includes example Procedure Type codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3764` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.procedure.type` | `http://hl7.org/fhir/ValueSet/ex-procedure-type` | `Example` | Category of Procedure |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.procedure.type` | `http://hl7.org/fhir/ValueSet/ex-procedure-type` | `Example` | Category of Procedure |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/ex-procedure-type`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/ex-procedure-type` | `primary` | Primary procedure |
| `http://terminology.hl7.org/CodeSystem/ex-procedure-type` | `secondary` | Secondary procedure |
