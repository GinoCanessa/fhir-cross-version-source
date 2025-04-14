Comparison of 
Generated at Monday, April 14, 2025 6:17:27 PM

### GoalPriority

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | GoalPriority |
| Canonical URL | `http://hl7.org/fhir/ValueSet/goal-priority` |
| Version | 4.0.1 |
| Description | Indicates the level of importance associated with reaching or sustaining a goal. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2473` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Goal` | `Goal.priority` | `http://hl7.org/fhir/ValueSet/goal-priority` | `Preferred` | high-priority \| medium-priority \| low-priority |
| `http://hl7.org/fhir/StructureDefinition/PlanDefinition` | `PlanDefinition.goal.priority` | `http://hl7.org/fhir/ValueSet/goal-priority` | `Preferred` | high-priority \| medium-priority \| low-priority |
| `http://hl7.org/fhir/StructureDefinition/goal-acceptance` | `Extension.extension.value[x]` | `http://hl7.org/fhir/ValueSet/goal-priority` | `Example` | Value of extension |

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
