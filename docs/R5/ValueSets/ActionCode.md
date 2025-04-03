Comparison of 
Generated at Thursday, April 3, 2025 8:18:31 AM

### ActionCode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ActionCode |
| Canonical URL | `http://hl7.org/fhir/ValueSet/action-code` |
| Version | 5.0.0 |
| Description | Provides examples of actions to be performed. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4243` |
| Database Concept Count | `9` |
| Database Active Concept Count | `9` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/PlanDefinition` | `PlanDefinition.action.code` | `http://hl7.org/fhir/ValueSet/action-code` | `Example` | Code representing the meaning of the action or sub-actions |
| `http://hl7.org/fhir/StructureDefinition/RequestOrchestration` | `RequestOrchestration.code` | `http://hl7.org/fhir/ValueSet/action-code` | `Example` | What's being requested/ordered |
| `http://hl7.org/fhir/StructureDefinition/RequestOrchestration` | `RequestOrchestration.action.code` | `http://hl7.org/fhir/ValueSet/action-code` | `Example` | Code representing the meaning of the action or sub-actions |

### Referenced Systems

* `http://hl7.org/fhir/action-code`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/action-code` | `collect-information` | Collect information |
| `http://hl7.org/fhir/action-code` | `order-service` | Order a service |
| `http://hl7.org/fhir/action-code` | `prescribe-medication` | Prescribe a medication |
| `http://hl7.org/fhir/action-code` | `propose-diagnosis` | Propose a diagnosis |
| `http://hl7.org/fhir/action-code` | `recommend-immunization` | Recommend an immunization |
| `http://hl7.org/fhir/action-code` | `record-detected-issue` | Record a detected issue |
| `http://hl7.org/fhir/action-code` | `record-inference` | Record an inference |
| `http://hl7.org/fhir/action-code` | `report-flag` | Report a flag |
| `http://hl7.org/fhir/action-code` | `send-message` | Send a message |
