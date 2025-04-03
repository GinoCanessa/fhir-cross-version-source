Comparison of 
Generated at Thursday, April 3, 2025 8:18:32 AM

### ImmunizationEvaluationDoseStatusCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ImmunizationEvaluationDoseStatusCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/immunization-evaluation-dose-status` |
| Version | 5.0.0 |
| Description | The value set to instantiate this attribute should be drawn from a terminologically robust code system that consists of or contains concepts to support describing the validity of a dose relative to a particular recommended schedule. This value set is provided as a suggestive example. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4615` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ImmunizationEvaluation` | `ImmunizationEvaluation.doseStatus` | `http://hl7.org/fhir/ValueSet/immunization-evaluation-dose-status` | `Example` | Status of the dose relative to published recommendations |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/immunization-evaluation-dose-status`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/immunization-evaluation-dose-status` | `notvalid` | Not valid |
| `http://terminology.hl7.org/CodeSystem/immunization-evaluation-dose-status` | `valid` | Valid |
