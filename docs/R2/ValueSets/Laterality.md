Comparison of 
Generated at Tuesday, April 1, 2025 1:39:06 PM

### Laterality

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Laterality |
| Canonical URL | `http://hl7.org/fhir/ValueSet/bodysite-laterality` |
| Version | 1.0.2 |
| Description | Laterality: SNOMED-CT concepts for 'left', 'right', and 'bilateral' |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `35` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ImagingStudy` | `ImagingStudy.series.laterality` | `http://hl7.org/fhir/ValueSet/bodysite-laterality` | `Example` | Body part laterality |

### Referenced Systems

* `http://snomed.info/sct`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://snomed.info/sct` | `419161000` | Unilateral left |
| `http://snomed.info/sct` | `419465000` | Unilateral right |
| `http://snomed.info/sct` | `51440002` | Bilateral |
