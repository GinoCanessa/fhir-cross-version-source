Comparison of 
Generated at Thursday, April 3, 2025 8:18:31 AM

### ExampleProcedureTypeCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ExampleProcedureTypeCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/ex-procedure-type` |
| Version | 5.0.0 |
| Description | This value set includes example Procedure Type codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4554` |
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
