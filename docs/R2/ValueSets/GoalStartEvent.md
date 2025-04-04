Comparison of 
Generated at Friday, April 4, 2025 2:58:32 PM

### GoalStartEvent

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | GoalStartEvent |
| Canonical URL | `http://hl7.org/fhir/ValueSet/goal-start-event` |
| Version | 1.0.2 |
| Description | Identifies types of events that might trigger the start of a goal. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `180` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Goal` | `Goal.start[x]` | `http://hl7.org/fhir/ValueSet/goal-start-event` | `Example` | When goal pursuit begins |

### Referenced Systems

* `http://snomed.info/sct`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://snomed.info/sct` | `308283009` | Discharge from hospital |
| `http://snomed.info/sct` | `32485007` | Admission to hospital |
| `http://snomed.info/sct` | `386216000` | Childbirth |
| `http://snomed.info/sct` | `442137000` | Completion time of procedure |
