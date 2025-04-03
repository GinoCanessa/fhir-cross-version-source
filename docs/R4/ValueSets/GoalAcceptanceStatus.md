Comparison of 
Generated at Thursday, April 3, 2025 8:18:16 AM

### GoalAcceptanceStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | GoalAcceptanceStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/goal-acceptance-status` |
| Version | 4.0.1 |
| Description | Codes indicating whether the goal has been accepted by a stakeholder. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2470` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/goal-acceptance` | `Extension.extension.value[x]` | `http://hl7.org/fhir/ValueSet/goal-acceptance-status\|4.0.1` | `Required` | Value of extension |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/goal-acceptance-status`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/goal-acceptance-status` | `agree` | Agree |
| `http://terminology.hl7.org/CodeSystem/goal-acceptance-status` | `disagree` | Disagree |
| `http://terminology.hl7.org/CodeSystem/goal-acceptance-status` | `pending` | Pending |
