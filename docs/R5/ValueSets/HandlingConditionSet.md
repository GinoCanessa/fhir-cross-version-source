Comparison of 
Generated at Tuesday, April 1, 2025 1:39:34 PM

### HandlingConditionSet

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | HandlingConditionSet |
| Canonical URL | `http://hl7.org/fhir/ValueSet/handling-condition` |
| Version | 5.0.0 |
| Description | Set of handling instructions prior testing of the specimen. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4600` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/SpecimenDefinition` | `SpecimenDefinition.typeTested.handling.temperatureQualifier` | `http://hl7.org/fhir/ValueSet/handling-condition` | `Example` | Qualifies the interval of temperature |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/handling-condition`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/handling-condition` | `frozen` | frozen |
| `http://terminology.hl7.org/CodeSystem/handling-condition` | `refrigerated` | refrigerated |
| `http://terminology.hl7.org/CodeSystem/handling-condition` | `room` | room temperature |
