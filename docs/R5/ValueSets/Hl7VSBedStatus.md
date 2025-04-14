Comparison of 
Generated at Monday, April 14, 2025 6:17:43 PM

### Hl7VSBedStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | Hl7VSBedStatus |
| Canonical URL | `http://terminology.hl7.org/ValueSet/v2-0116` |
| Version | 2.0.0 |
| Description | Value Set of codes that specify the state of a bed in an inpatient setting, and is used to determine if a patient may be assigned to it or not. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `5036` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Location` | `Location.operationalStatus` | `http://terminology.hl7.org/ValueSet/v2-0116` | `Preferred` | The operational status of the location (typically only for a bed/room) |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v2-0116`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v2-0116` | `C` | Closed |
| `http://terminology.hl7.org/CodeSystem/v2-0116` | `H` | Housekeeping |
| `http://terminology.hl7.org/CodeSystem/v2-0116` | `I` | Isolated |
| `http://terminology.hl7.org/CodeSystem/v2-0116` | `K` | Contaminated |
| `http://terminology.hl7.org/CodeSystem/v2-0116` | `O` | Occupied |
| `http://terminology.hl7.org/CodeSystem/v2-0116` | `U` | Unoccupied |
