Comparison of 
Generated at Thursday, April 3, 2025 8:18:16 AM

### DiagnosisRole

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | DiagnosisRole |
| Canonical URL | `http://hl7.org/fhir/ValueSet/diagnosis-role` |
| Version | 4.0.1 |
| Description | This value set defines a set of codes that can be used to express the role of a diagnosis on the Encounter or EpisodeOfCare record. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2384` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.diagnosis.use` | `http://hl7.org/fhir/ValueSet/diagnosis-role` | `Preferred` | Role that this diagnosis has within the encounter (e.g. admission, billing, discharge …) |
| `http://hl7.org/fhir/StructureDefinition/EpisodeOfCare` | `EpisodeOfCare.diagnosis.role` | `http://hl7.org/fhir/ValueSet/diagnosis-role` | `Preferred` | Role that this diagnosis has within the episode of care (e.g. admission, billing, discharge …) |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/diagnosis-role`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/diagnosis-role` | `AD` | Admission diagnosis |
| `http://terminology.hl7.org/CodeSystem/diagnosis-role` | `CC` | Chief complaint |
| `http://terminology.hl7.org/CodeSystem/diagnosis-role` | `CM` | Comorbidity diagnosis |
| `http://terminology.hl7.org/CodeSystem/diagnosis-role` | `DD` | Discharge diagnosis |
| `http://terminology.hl7.org/CodeSystem/diagnosis-role` | `billing` | Billing |
| `http://terminology.hl7.org/CodeSystem/diagnosis-role` | `post-op` | post-op diagnosis |
| `http://terminology.hl7.org/CodeSystem/diagnosis-role` | `pre-op` | pre-op diagnosis |
