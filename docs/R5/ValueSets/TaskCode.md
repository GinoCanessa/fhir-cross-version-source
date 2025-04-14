Comparison of 
Generated at Monday, April 14, 2025 6:17:43 PM

### TaskCode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | TaskCode |
| Canonical URL | `http://hl7.org/fhir/ValueSet/task-code` |
| Version | 5.0.0 |
| Description | Codes indicating the type of action that is expected to be performed |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `4961` |
| Database Concept Count | `8` |
| Database Active Concept Count | `8` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Task` | `Task.code` | `http://hl7.org/fhir/ValueSet/task-code` | `Example` | Task Type |

### Referenced Systems

* `http://hl7.org/fhir/CodeSystem/task-code`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/CodeSystem/task-code` | `abort` | Mark the focal resource as no longer active |
| `http://hl7.org/fhir/CodeSystem/task-code` | `approve` | Activate/approve the focal resource |
| `http://hl7.org/fhir/CodeSystem/task-code` | `change` | Change the focal resource |
| `http://hl7.org/fhir/CodeSystem/task-code` | `fulfill` | Fulfill the focal request |
| `http://hl7.org/fhir/CodeSystem/task-code` | `instantiate` | Instantiate the focal definition |
| `http://hl7.org/fhir/CodeSystem/task-code` | `replace` | Replace the focal resource with the input resource |
| `http://hl7.org/fhir/CodeSystem/task-code` | `resume` | Re-activate the focal resource |
| `http://hl7.org/fhir/CodeSystem/task-code` | `suspend` | Suspend the focal resource |
