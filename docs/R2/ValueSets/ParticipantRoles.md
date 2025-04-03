Comparison of 
Generated at Thursday, April 3, 2025 8:18:05 AM

### Participant Roles

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Participant Roles |
| Canonical URL | `http://hl7.org/fhir/ValueSet/participant-role` |
| Version | 1.0.2 |
| Description | Roles of Participants that may be included in a CarePlan.Participants, or in an EpisodeOfCare.CareTeam.  Defined as: Is a Person, Healthcare professional (occupation) or Healthcare related organization (qualifier value). |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `268` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/CarePlan` | `CarePlan.participant.role` | `http://hl7.org/fhir/ValueSet/participant-role` | `Example` | Type of involvement |
| `http://hl7.org/fhir/StructureDefinition/EpisodeOfCare` | `EpisodeOfCare.careTeam.role` | `http://hl7.org/fhir/ValueSet/participant-role` | `Example` | Role taken by this team member |

### Expansion Failure

Failed to expand this value set: Error expanding http://hl7.org/fhir/ValueSet/participant-role|1.0.2: Operation expand failed: creating the required expansion failed with message "Cannot find codesystem 'http://snomed.info/sct', so the defined filter(s) cannot be applied.".
