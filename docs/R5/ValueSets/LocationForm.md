Comparison of 
Generated at Thursday, April 3, 2025 8:18:32 AM

### LocationForm

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | LocationForm |
| Canonical URL | `http://hl7.org/fhir/ValueSet/location-form` |
| Version | 5.0.0 |
| Description | This example value set defines a set of codes that can be used to indicate the physical form of the Location. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4671` |
| Database Concept Count | `15` |
| Database Active Concept Count | `15` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.location.form` | `http://hl7.org/fhir/ValueSet/location-form` | `Example` | The physical type of the location (usually the level in the location hierarchy - bed, room, ward, virtual etc.) |
| `http://hl7.org/fhir/StructureDefinition/EncounterHistory` | `EncounterHistory.location.form` | `http://hl7.org/fhir/ValueSet/location-form` | `Example` | The physical type of the location (usually the level in the location hierarchy - bed, room, ward, virtual etc.) |
| `http://hl7.org/fhir/StructureDefinition/Location` | `Location.form` | `http://hl7.org/fhir/ValueSet/location-form` | `Example` | Physical form of the location |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/location-physical-type`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/location-physical-type` | `area` | Area |
| `http://terminology.hl7.org/CodeSystem/location-physical-type` | `bd` | Bed |
| `http://terminology.hl7.org/CodeSystem/location-physical-type` | `bu` | Building |
| `http://terminology.hl7.org/CodeSystem/location-physical-type` | `ca` | Cabinet |
| `http://terminology.hl7.org/CodeSystem/location-physical-type` | `co` | Corridor |
| `http://terminology.hl7.org/CodeSystem/location-physical-type` | `ho` | House |
| `http://terminology.hl7.org/CodeSystem/location-physical-type` | `jdn` | Jurisdiction |
| `http://terminology.hl7.org/CodeSystem/location-physical-type` | `lvl` | Level |
| `http://terminology.hl7.org/CodeSystem/location-physical-type` | `rd` | Road |
| `http://terminology.hl7.org/CodeSystem/location-physical-type` | `ro` | Room |
| `http://terminology.hl7.org/CodeSystem/location-physical-type` | `si` | Site |
| `http://terminology.hl7.org/CodeSystem/location-physical-type` | `ve` | Vehicle |
| `http://terminology.hl7.org/CodeSystem/location-physical-type` | `vi` | Virtual |
| `http://terminology.hl7.org/CodeSystem/location-physical-type` | `wa` | Ward |
| `http://terminology.hl7.org/CodeSystem/location-physical-type` | `wi` | Wing |
