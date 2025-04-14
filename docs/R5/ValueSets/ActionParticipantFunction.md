Comparison of 
Generated at Monday, April 14, 2025 6:17:42 PM

### ActionParticipantFunction

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ActionParticipantFunction |
| Canonical URL | `http://hl7.org/fhir/ValueSet/action-participant-function` |
| Version | 5.0.0 |
| Description | The function performed by the participant for the action. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4246` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ActivityDefinition` | `ActivityDefinition.participant.function` | `http://hl7.org/fhir/ValueSet/action-participant-function` | `Example` | E.g. Author, Reviewer, Witness, etc |
| `http://hl7.org/fhir/StructureDefinition/PlanDefinition` | `PlanDefinition.action.participant.function` | `http://hl7.org/fhir/ValueSet/action-participant-function` | `Example` | E.g. Author, Reviewer, Witness, etc |
| `http://hl7.org/fhir/StructureDefinition/RequestOrchestration` | `RequestOrchestration.action.participant.function` | `http://hl7.org/fhir/ValueSet/action-participant-function` | `Example` | E.g. Author, Reviewer, Witness, etc |

### Referenced Systems

* `http://hl7.org/fhir/action-participant-function`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/action-participant-function` | `author` | Author |
| `http://hl7.org/fhir/action-participant-function` | `performer` | Performer |
| `http://hl7.org/fhir/action-participant-function` | `reviewer` | Reviewer |
| `http://hl7.org/fhir/action-participant-function` | `witness` | Witness |
