Comparison of 
Generated at Monday, April 14, 2025 6:17:35 PM

### ProcedurePerformerRoleCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ProcedurePerformerRoleCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/performer-role` |
| Version | 4.3.0 |
| Description | This example value set defines the set of codes that can be used to indicate a role of a procedure performer. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `3987` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ChargeItem` | `ChargeItem.performer.function` | `http://hl7.org/fhir/ValueSet/performer-role` | `Example` | What type of performance was done |
| `http://hl7.org/fhir/StructureDefinition/MedicationRequest` | `MedicationRequest.performerType` | `http://hl7.org/fhir/ValueSet/performer-role` | `Example` | Desired kind of performer of the medication administration |
| `http://hl7.org/fhir/StructureDefinition/Procedure` | `Procedure.performer.function` | `http://hl7.org/fhir/ValueSet/performer-role` | `Example` | Type of performance |
| `http://hl7.org/fhir/StructureDefinition/Task` | `Task.performerType` | `http://hl7.org/fhir/ValueSet/performer-role` | `Preferred` | Requested performer |

### Expansion Failure

Failed to expand this value set: Expansion is limited
