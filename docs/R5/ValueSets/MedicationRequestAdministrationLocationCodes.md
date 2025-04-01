Comparison of 
Generated at Tuesday, April 1, 2025 1:39:34 PM

### MedicationRequestAdministrationLocationCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | MedicationRequestAdministrationLocationCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/medicationrequest-admin-location` |
| Version | 5.0.0 |
| Description | MedicationRequest Administration Location Codes |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4716` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/MedicationRequest` | `MedicationRequest.category` | `http://hl7.org/fhir/ValueSet/medicationrequest-admin-location` | `Example` | Grouping or category of medication request |
| `http://hl7.org/fhir/StructureDefinition/MedicationStatement` | `MedicationStatement.category` | `http://hl7.org/fhir/ValueSet/medicationrequest-admin-location` | `Example` | Type of medication statement |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/medicationrequest-admin-location`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/medicationrequest-admin-location` | `community` | Community |
| `http://terminology.hl7.org/CodeSystem/medicationrequest-admin-location` | `inpatient` | Inpatient |
| `http://terminology.hl7.org/CodeSystem/medicationrequest-admin-location` | `outpatient` | Outpatient |
