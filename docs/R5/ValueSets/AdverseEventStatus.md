Comparison of 
Generated at Friday, April 4, 2025 2:58:59 PM

### AdverseEventStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | AdverseEventStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/adverse-event-status` |
| Version | 5.0.0 |
| Description | Codes identifying the lifecycle stage of an adverse event. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `4275` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AdverseEvent` | `AdverseEvent.status` | `http://hl7.org/fhir/ValueSet/adverse-event-status\|5.0.0` | `Required` | in-progress \| completed \| entered-in-error \| unknown |

### Referenced Systems

* `http://hl7.org/fhir/event-status`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/event-status` | `completed` | Completed |
| `http://hl7.org/fhir/event-status` | `entered-in-error` | Entered in Error |
| `http://hl7.org/fhir/event-status` | `in-progress` | In Progress |
| `http://hl7.org/fhir/event-status` | `unknown` | Unknown |
