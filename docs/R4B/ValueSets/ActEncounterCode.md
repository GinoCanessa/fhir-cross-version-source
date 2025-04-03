Comparison of 
Generated at Thursday, April 3, 2025 8:18:25 AM

### ActEncounterCode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ActEncounterCode |
| Canonical URL | `http://terminology.hl7.org/ValueSet/v3-ActEncounterCode` |
| Version | 2.0.0 |
| Description | Domain provides codes that qualify the ActEncounterClass (ENC) |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `4220` |
| Database Concept Count | `11` |
| Database Active Concept Count | `11` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.class` | `http://terminology.hl7.org/ValueSet/v3-ActEncounterCode` | `Extensible` | Classification of patient encounter |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.classHistory.class` | `http://terminology.hl7.org/ValueSet/v3-ActEncounterCode` | `Extensible` | inpatient \| outpatient \| ambulatory \| emergency + |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-ActCode`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ACUTE` | inpatient acute |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `AMB` | ambulatory |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `EMER` | emergency |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `FLD` | field |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `HH` | home health |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `IMP` | inpatient encounter |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NONAC` | inpatient non-acute |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `OBSENC` | observation encounter |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PRENC` | pre-admission |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SS` | short stay |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `VR` | virtual |
