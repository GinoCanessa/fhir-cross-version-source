Comparison of 
Generated at Tuesday, April 1, 2025 1:39:34 PM

### EncounterDiagnosisUse

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | EncounterDiagnosisUse |
| Canonical URL | `http://hl7.org/fhir/ValueSet/encounter-diagnosis-use` |
| Version | 5.0.0 |
| Description | What a specific Encounter/EpisodeOfCare `diagnosis.condition` is to be used for. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4519` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Account` | `Account.diagnosis.type` | `http://hl7.org/fhir/ValueSet/encounter-diagnosis-use` | `Preferred` | Type that this diagnosis has relevant to the account (e.g. admission, billing, discharge …) |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.diagnosis.use` | `http://hl7.org/fhir/ValueSet/encounter-diagnosis-use` | `Preferred` | Role that this diagnosis has within the encounter (e.g. admission, billing, discharge …) |
| `http://hl7.org/fhir/StructureDefinition/EpisodeOfCare` | `EpisodeOfCare.diagnosis.use` | `http://hl7.org/fhir/ValueSet/encounter-diagnosis-use` | `Preferred` | Role that this diagnosis has within the episode of care (e.g. admission, billing, discharge …) |

### Referenced Systems

* `http://hl7.org/fhir/encounter-diagnosis-use`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/encounter-diagnosis-use` | `final` | Final |
| `http://hl7.org/fhir/encounter-diagnosis-use` | `working` | Working |
