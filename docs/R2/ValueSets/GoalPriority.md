Comparison of 
Generated at Tuesday, April 1, 2025 1:39:06 PM

### GoalPriority

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | GoalPriority |
| Canonical URL | `http://hl7.org/fhir/ValueSet/goal-priority` |
| Version | 1.0.2 |
| Description | Indicates the level of importance associated with reaching or sustaining a goal. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `178` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Goal` | `Goal.priority` | `http://hl7.org/fhir/ValueSet/goal-priority` | `Preferred` | high \| medium \|low |
| `http://hl7.org/fhir/StructureDefinition/goal-acceptance` | `Extension.extension.valueCodeableConcept` | `http://hl7.org/fhir/ValueSet/goal-priority` | `Example` | Value of extension |

### Referenced Systems

* `http://hl7.org/fhir/goal-priority`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/goal-priority` | `high` | high |
| `http://hl7.org/fhir/goal-priority` | `low` | low |
| `http://hl7.org/fhir/goal-priority` | `medium` | medium |
