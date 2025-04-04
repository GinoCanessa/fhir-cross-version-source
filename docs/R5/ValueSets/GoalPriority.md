Comparison of 
Generated at Friday, April 4, 2025 2:58:58 PM

### GoalPriority

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | GoalPriority |
| Canonical URL | `http://hl7.org/fhir/ValueSet/goal-priority` |
| Version | 5.0.0 |
| Description | Indicates the level of importance associated with reaching or sustaining a goal. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4589` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Goal` | `Goal.priority` | `http://hl7.org/fhir/ValueSet/goal-priority` | `Preferred` | high-priority \| medium-priority \| low-priority |
| `http://hl7.org/fhir/StructureDefinition/PlanDefinition` | `PlanDefinition.goal.priority` | `http://hl7.org/fhir/ValueSet/goal-priority` | `Preferred` | high-priority \| medium-priority \| low-priority |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/goal-priority`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/goal-priority` | `high-priority` | High Priority |
| `http://terminology.hl7.org/CodeSystem/goal-priority` | `low-priority` | Low Priority |
| `http://terminology.hl7.org/CodeSystem/goal-priority` | `medium-priority` | Medium Priority |
