Comparison of 
Generated at Monday, April 14, 2025 6:17:35 PM

### ImmunizationEvaluationDoseStatusReasonCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ImmunizationEvaluationDoseStatusReasonCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/immunization-evaluation-dose-status-reason` |
| Version | 4.3.0 |
| Description | The value set to instantiate this attribute should be drawn from a terminologically robust code system that consists of or contains concepts to support describing the reason why an administered dose has been assigned a particular status. Often, this reason describes why a dose is considered invalid. This value set is provided as a suggestive example. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3818` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ImmunizationEvaluation` | `ImmunizationEvaluation.doseStatusReason` | `http://hl7.org/fhir/ValueSet/immunization-evaluation-dose-status-reason` | `Example` | Reason for the dose status |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/immunization-evaluation-dose-status-reason`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/immunization-evaluation-dose-status-reason` | `advstorage` | Adverse storage condition |
| `http://terminology.hl7.org/CodeSystem/immunization-evaluation-dose-status-reason` | `coldchbrk` | Cold chain break |
| `http://terminology.hl7.org/CodeSystem/immunization-evaluation-dose-status-reason` | `explot` | Expired lot |
| `http://terminology.hl7.org/CodeSystem/immunization-evaluation-dose-status-reason` | `outsidesched` | Administered outside recommended schedule |
| `http://terminology.hl7.org/CodeSystem/immunization-evaluation-dose-status-reason` | `prodrecall` | Product recall |
