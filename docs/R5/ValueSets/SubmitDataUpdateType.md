Comparison of 
Generated at Friday, April 4, 2025 2:58:59 PM

### SubmitDataUpdateType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | SubmitDataUpdateType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/submit-data-update-type` |
| Version | 5.0.0 |
| Description | Concepts for how a measure report consumer and receiver coordinate data exchange updates. The choices are snapshot or incremental updates |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `4920` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/MeasureReport` | `MeasureReport.dataUpdateType` | `http://hl7.org/fhir/ValueSet/submit-data-update-type\|5.0.0` | `Required` | incremental \| snapshot |

### Referenced Systems

* `http://hl7.org/fhir/CodeSystem/submit-data-update-type`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/CodeSystem/submit-data-update-type` | `incremental` | Incremental |
| `http://hl7.org/fhir/CodeSystem/submit-data-update-type` | `snapshot` | Snapshot |
