Comparison of 
Generated at Tuesday, April 1, 2025 1:39:06 PM

### Encounter Reason Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Encounter Reason Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/encounter-reason` |
| Version | 1.0.2 |
| Description | This examples value set defines the set of codes that can be used to indicate reasons for an encounter. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `149` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Appointment` | `Appointment.reason` | `http://hl7.org/fhir/ValueSet/encounter-reason` | `Required` | Reason this appointment is scheduled |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.reason` | `http://hl7.org/fhir/ValueSet/encounter-reason` | `Example` | Reason the encounter takes place (code) |

### Expansion Failure

Failed to expand this value set: Error expanding http://hl7.org/fhir/ValueSet/encounter-reason|1.0.2: Operation expand failed: creating the required expansion failed with message "Cannot find codesystem 'http://snomed.info/sct', so the defined filter(s) cannot be applied.".
