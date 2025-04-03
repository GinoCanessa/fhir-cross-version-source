Comparison of 
Generated at Thursday, April 3, 2025 8:18:32 AM

### ActionReasonCode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ActionReasonCode |
| Canonical URL | `http://hl7.org/fhir/ValueSet/action-reason-code` |
| Version | 5.0.0 |
| Description | Provides examples of reasons for actions to be performed. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4249` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/PlanDefinition` | `PlanDefinition.action.reason` | `http://hl7.org/fhir/ValueSet/action-reason-code` | `Example` | Why the action should be performed |
| `http://hl7.org/fhir/StructureDefinition/RequestOrchestration` | `RequestOrchestration.reason` | `http://hl7.org/fhir/ValueSet/action-reason-code` | `Example` | Why the request orchestration is needed |

### Referenced Systems

* `http://hl7.org/fhir/action-reason-code`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/action-reason-code` | `care-gap` | Care gap detected |
| `http://hl7.org/fhir/action-reason-code` | `drug-drug-interaction` | Drug-drug interaction |
| `http://hl7.org/fhir/action-reason-code` | `off-pathway` | Off pathway |
| `http://hl7.org/fhir/action-reason-code` | `quality-measure` | Quality measure |
| `http://hl7.org/fhir/action-reason-code` | `risk-assessment` | Risk assessment |
