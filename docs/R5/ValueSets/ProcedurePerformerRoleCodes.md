Comparison of 
Generated at Thursday, April 3, 2025 8:18:31 AM

### ProcedurePerformerRoleCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ProcedurePerformerRoleCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/performer-role` |
| Version | 5.0.0 |
| Description | This example value set defines the set of codes that can be used to indicate a role of a procedure performer. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `4791` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ChargeItem` | `ChargeItem.performer.function` | `http://hl7.org/fhir/ValueSet/performer-role` | `Example` | What type of performance was done |
| `http://hl7.org/fhir/StructureDefinition/NutritionIntake` | `NutritionIntake.performer.function` | `http://hl7.org/fhir/ValueSet/performer-role` | `Example` | Type of performer |
| `http://hl7.org/fhir/StructureDefinition/Procedure` | `Procedure.performer.function` | `http://hl7.org/fhir/ValueSet/performer-role` | `Example` | Type of performance |
| `http://hl7.org/fhir/StructureDefinition/Task` | `Task.requestedPerformer` | `http://hl7.org/fhir/ValueSet/performer-role` | `Preferred` | Who should perform Task |
| `http://hl7.org/fhir/StructureDefinition/Transport` | `Transport.performerType` | `http://hl7.org/fhir/ValueSet/performer-role` | `Preferred` | Requested performer |

### Expansion Failure

Failed to expand this value set: Expansion is limited
