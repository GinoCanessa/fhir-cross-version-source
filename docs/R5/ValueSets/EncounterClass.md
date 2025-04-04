Comparison of 
Generated at Friday, April 4, 2025 2:58:59 PM

### EncounterClass

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | EncounterClass |
| Canonical URL | `http://terminology.hl7.org/ValueSet/encounter-class` |
| Version | 1.0.0 |
| Description | This value set defines a set of codes that can be used to indicate the class of encounter: a specific code indicating class of service provided. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `5028` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.class` | `http://terminology.hl7.org/ValueSet/encounter-class` | `Preferred` | Classification of patient encounter context - e.g. Inpatient, outpatient |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-ActCode`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AMB` | ambulatory |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `EMER` | emergency |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HH` | home health |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `IMP` | inpatient encounter |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `OBSENC` | observation encounter |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `VR` | virtual |
