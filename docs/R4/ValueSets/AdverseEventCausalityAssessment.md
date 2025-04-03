Comparison of 
Generated at Thursday, April 3, 2025 8:18:16 AM

### AdverseEventCausalityAssessment

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | AdverseEventCausalityAssessment |
| Canonical URL | `http://hl7.org/fhir/ValueSet/adverse-event-causality-assess` |
| Version | 4.0.1 |
| Description | Codes for the assessment of whether the entity caused the event. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2197` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AdverseEvent` | `AdverseEvent.suspectEntity.causality.assessment` | `http://hl7.org/fhir/ValueSet/adverse-event-causality-assess` | `Example` | Assessment of if the entity caused the event |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/adverse-event-causality-assess`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/adverse-event-causality-assess` | `Certain` | Certain |
| `http://terminology.hl7.org/CodeSystem/adverse-event-causality-assess` | `Conditional-Classified` | Conditional/Classified |
| `http://terminology.hl7.org/CodeSystem/adverse-event-causality-assess` | `Possible` | Possible |
| `http://terminology.hl7.org/CodeSystem/adverse-event-causality-assess` | `Probably-Likely` | Probably/Likely |
| `http://terminology.hl7.org/CodeSystem/adverse-event-causality-assess` | `Unassessable-Unclassifiable` | Unassessable/Unclassifiable |
| `http://terminology.hl7.org/CodeSystem/adverse-event-causality-assess` | `Unlikely` | Unlikely |
