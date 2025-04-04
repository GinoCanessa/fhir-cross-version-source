Comparison of 
Generated at Friday, April 4, 2025 2:58:36 PM

### Procedure Performer Role Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Procedure Performer Role Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/performer-role` |
| Version | 3.0.2 |
| Description | This examples value set defines the set of codes that can be used to indicate a role of procedure performer. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `1391` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ChargeItem` | `ChargeItem.participant.role` | `http://hl7.org/fhir/ValueSet/performer-role` | `Example` | What type of performance was done |
| `http://hl7.org/fhir/StructureDefinition/DiagnosticReport` | `DiagnosticReport.performer.role` | `http://hl7.org/fhir/ValueSet/performer-role` | `Example` | Type of performer |
| `http://hl7.org/fhir/StructureDefinition/Procedure` | `Procedure.performer.role` | `http://hl7.org/fhir/ValueSet/performer-role` | `Example` | The role the actor was in |
| `http://hl7.org/fhir/StructureDefinition/event-performerRole` | `Extension.valueCodeableConcept` | `http://hl7.org/fhir/ValueSet/performer-role` | `Example` | Value of extension |

### Expansion Failure

Failed to expand this value set: Expansion is limited
