Comparison of 
Generated at Monday, April 14, 2025 6:17:42 PM

### EncounterType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | EncounterType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/encounter-type` |
| Version | 5.0.0 |
| Description | This example value set defines a set of codes that can be used to indicate the type of encounter: a specific code indicating type of service provided. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4530` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.type` | `http://hl7.org/fhir/ValueSet/encounter-type` | `Example` | Specific type of encounter (e.g. e-mail consultation, surgical day-care, ...) |
| `http://hl7.org/fhir/StructureDefinition/EncounterHistory` | `EncounterHistory.type` | `http://hl7.org/fhir/ValueSet/encounter-type` | `Example` | Specific type of encounter |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/encounter-type`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/encounter-type` | `ADMS` | Annual diabetes mellitus screening |
| `http://terminology.hl7.org/CodeSystem/encounter-type` | `BD/BM-clin` | Bone drilling/bone marrow punction in clinic |
| `http://terminology.hl7.org/CodeSystem/encounter-type` | `CCS60` | Infant colon screening - 60 minutes |
| `http://terminology.hl7.org/CodeSystem/encounter-type` | `OKI` | Outpatient Kenacort injection |
