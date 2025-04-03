Comparison of 
Generated at Thursday, April 3, 2025 8:18:32 AM

### ImmunizationEvaluationDoseStatusReasonCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ImmunizationEvaluationDoseStatusReasonCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/immunization-evaluation-dose-status-reason` |
| Version | 5.0.0 |
| Description | The value set to instantiate this attribute should be drawn from a terminologically robust code system that consists of or contains concepts to support describing the reason why an administered dose has been assigned a particular status. Often, this reason describes why a dose is considered invalid. This value set is provided as a suggestive example. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4616` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ImmunizationEvaluation` | `ImmunizationEvaluation.doseStatusReason` | `http://hl7.org/fhir/ValueSet/immunization-evaluation-dose-status-reason` | `Example` | Reason why the doese is considered valid, invalid or some other status |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/immunization-evaluation-dose-status-reason`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/immunization-evaluation-dose-status-reason` | `adversestorage` | Adverse Storage |
| `http://terminology.hl7.org/CodeSystem/immunization-evaluation-dose-status-reason` | `coldchainbreak` | Cold Chain Break |
| `http://terminology.hl7.org/CodeSystem/immunization-evaluation-dose-status-reason` | `expired` | Expired Product |
| `http://terminology.hl7.org/CodeSystem/immunization-evaluation-dose-status-reason` | `outsideschedule` | Outside Schedule |
| `http://terminology.hl7.org/CodeSystem/immunization-evaluation-dose-status-reason` | `partialdose` | Partial Dose |
| `http://terminology.hl7.org/CodeSystem/immunization-evaluation-dose-status-reason` | `recall` | Manufacturer Recall |
