Comparison of 
Generated at Tuesday, April 1, 2025 1:39:06 PM

### GoalStatusReason

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | GoalStatusReason |
| Canonical URL | `http://hl7.org/fhir/ValueSet/goal-status-reason` |
| Version | 1.0.2 |
| Description | Example codes indicating the reason for a current status.  Note that these are in no way complete and may not even be appropriate for some uses. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `182` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/CarePlan` | `CarePlan.activity.detail.statusReason` | `http://hl7.org/fhir/ValueSet/goal-status-reason` | `Example` | Reason for current status |
| `http://hl7.org/fhir/StructureDefinition/Goal` | `Goal.statusReason` | `http://hl7.org/fhir/ValueSet/goal-status-reason` | `Example` | Reason for current status |

### Referenced Systems

* `http://hl7.org/fhir/goal-status-reason`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/goal-status-reason` | `life-event` | life event |
| `http://hl7.org/fhir/goal-status-reason` | `patient-request` | patient request |
| `http://hl7.org/fhir/goal-status-reason` | `replaced` | replaced |
| `http://hl7.org/fhir/goal-status-reason` | `surgery` | surgery |
