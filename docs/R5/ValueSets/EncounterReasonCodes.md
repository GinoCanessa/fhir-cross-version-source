Comparison of 
Generated at Thursday, April 3, 2025 8:18:32 AM

### EncounterReasonCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | EncounterReasonCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/encounter-reason` |
| Version | 5.0.0 |
| Description | This examples value set defines the set of codes that can be used to indicate reasons for an encounter. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `4524` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Appointment` | `Appointment.reason` | `http://hl7.org/fhir/ValueSet/encounter-reason` | `Preferred` | Reason this appointment is scheduled |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.reason.value` | `http://hl7.org/fhir/ValueSet/encounter-reason` | `Preferred` | Reason the encounter takes place (core or reference) |
| `http://hl7.org/fhir/StructureDefinition/EpisodeOfCare` | `EpisodeOfCare.reason.value` | `http://hl7.org/fhir/ValueSet/encounter-reason` | `Example` | Medical reason to be addressed |

### Expansion Failure

Failed to expand this value set: Expansion is limited
