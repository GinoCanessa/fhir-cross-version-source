Comparison of 
Generated at Monday, April 14, 2025 6:17:43 PM

### AdverseEventCausalityAssessment

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | AdverseEventCausalityAssessment |
| Canonical URL | `http://hl7.org/fhir/ValueSet/adverse-event-causality-assess` |
| Version | 5.0.0 |
| Description | Codes for the assessment of whether the entity caused the event. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4267` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AdverseEvent` | `AdverseEvent.suspectEntity.causality.entityRelatedness` | `http://hl7.org/fhir/ValueSet/adverse-event-causality-assess` | `Example` | Result of the assessment regarding the relatedness of the suspected entity to the event |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/adverse-event-causality-assess`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/adverse-event-causality-assess` | `certain` | Certain |
| `http://terminology.hl7.org/CodeSystem/adverse-event-causality-assess` | `conditional-classified` | Conditional/Classified |
| `http://terminology.hl7.org/CodeSystem/adverse-event-causality-assess` | `possible` | Possible |
| `http://terminology.hl7.org/CodeSystem/adverse-event-causality-assess` | `probably-likely` | Probably/Likely |
| `http://terminology.hl7.org/CodeSystem/adverse-event-causality-assess` | `unassessable-unclassifiable` | Unassessable/Unclassifiable |
| `http://terminology.hl7.org/CodeSystem/adverse-event-causality-assess` | `unlikely` | Unlikely |
