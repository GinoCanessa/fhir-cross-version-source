Comparison of 
Generated at Tuesday, April 1, 2025 1:39:12 PM

### DiagnosisRole

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | DiagnosisRole |
| Canonical URL | `http://hl7.org/fhir/ValueSet/diagnosis-role` |
| Version | 3.0.2 |
| Description | This value set defines a set of codes that can be used to express the role of a diagnosis on the Encounter or EpisodeOfCare record. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1189` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.diagnosis.role` | `http://hl7.org/fhir/ValueSet/diagnosis-role` | `Preferred` | Role that this diagnosis has within the encounter (e.g. admission, billing, discharge …) |
| `http://hl7.org/fhir/StructureDefinition/EpisodeOfCare` | `EpisodeOfCare.diagnosis.role` | `http://hl7.org/fhir/ValueSet/diagnosis-role` | `Preferred` | Role that this diagnosis has within the episode of care (e.g. admission, billing, discharge …) |

### Referenced Systems

* `http://hl7.org/fhir/diagnosis-role`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/diagnosis-role` | `AD` | Admission diagnosis |
| `http://hl7.org/fhir/diagnosis-role` | `CC` | Chief complaint |
| `http://hl7.org/fhir/diagnosis-role` | `CM` | Comorbidity diagnosis |
| `http://hl7.org/fhir/diagnosis-role` | `DD` | Discharge diagnosis |
| `http://hl7.org/fhir/diagnosis-role` | `billing` | Billing |
| `http://hl7.org/fhir/diagnosis-role` | `post-op` | post-op diagnosis |
| `http://hl7.org/fhir/diagnosis-role` | `pre-op` | pre-op diagnosis |
