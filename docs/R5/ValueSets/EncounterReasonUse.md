Comparison of 
Generated at Tuesday, April 1, 2025 1:39:34 PM

### EncounterReasonUse

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | EncounterReasonUse |
| Canonical URL | `http://hl7.org/fhir/ValueSet/encounter-reason-use` |
| Version | 5.0.0 |
| Description | What a specific Encounter/EpisodeOfCare `reason.value` is to be used for. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4525` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.reason.use` | `http://hl7.org/fhir/ValueSet/encounter-reason-use` | `Example` | What the reason value should be used for/as |
| `http://hl7.org/fhir/StructureDefinition/EpisodeOfCare` | `EpisodeOfCare.reason.use` | `http://hl7.org/fhir/ValueSet/encounter-reason-use` | `Example` | What the reason value should be used for/as |

### Referenced Systems

* `http://hl7.org/fhir/encounter-reason-use`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/encounter-reason-use` | `AD` | Admitting Diagnosis |
| `http://hl7.org/fhir/encounter-reason-use` | `CC` | Chief Complaint |
| `http://hl7.org/fhir/encounter-reason-use` | `HC` | Health Concern |
| `http://hl7.org/fhir/encounter-reason-use` | `HM` | Health Maintenance (including screening) |
| `http://hl7.org/fhir/encounter-reason-use` | `RV` | Reason for Visit |
