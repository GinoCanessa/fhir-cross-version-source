Comparison of 
Generated at Friday, April 4, 2025 2:58:31 PM

### Procedure Reason Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Procedure Reason Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/procedure-reason` |
| Version | 1.0.2 |
| Description | This examples value set defines the set of codes that can be used to indicate a reasons for a procedure. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `288` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Procedure` | `Procedure.reason[x]` | `http://hl7.org/fhir/ValueSet/procedure-reason` | `Example` | Reason procedure performed |
| `http://hl7.org/fhir/StructureDefinition/ProcedureRequest` | `ProcedureRequest.reason[x]` | `http://hl7.org/fhir/ValueSet/procedure-reason` | `Example` | Why procedure should occur |

### Expansion Failure

Failed to expand this value set: Error expanding http://hl7.org/fhir/ValueSet/procedure-reason|1.0.2: Operation expand failed: creating the required expansion failed with message "Cannot find codesystem 'http://snomed.info/sct', so the defined filter(s) cannot be applied.".
