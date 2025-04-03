Comparison of 
Generated at Thursday, April 3, 2025 8:18:31 AM

### EncounterSubjectStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | EncounterSubjectStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/encounter-subject-status` |
| Version | 5.0.0 |
| Description | This example value set defines a set of codes that can be used to indicate the status of the subject within the encounter |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4529` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.subjectStatus` | `http://hl7.org/fhir/ValueSet/encounter-subject-status` | `Example` | The current status of the subject in relation to the Encounter |
| `http://hl7.org/fhir/StructureDefinition/EncounterHistory` | `EncounterHistory.subjectStatus` | `http://hl7.org/fhir/ValueSet/encounter-subject-status` | `Example` | The current status of the subject in relation to the Encounter |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/encounter-subject-status`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/encounter-subject-status` | `arrived` | Arrived |
| `http://terminology.hl7.org/CodeSystem/encounter-subject-status` | `departed` | Departed |
| `http://terminology.hl7.org/CodeSystem/encounter-subject-status` | `on-leave` | On Leave |
| `http://terminology.hl7.org/CodeSystem/encounter-subject-status` | `receiving-care` | Receiving Care |
| `http://terminology.hl7.org/CodeSystem/encounter-subject-status` | `triaged` | Triaged |
