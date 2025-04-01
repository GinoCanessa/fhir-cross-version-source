Comparison of 
Generated at Tuesday, April 1, 2025 1:39:34 PM

### MeasureScoring

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | MeasureScoring |
| Canonical URL | `http://terminology.hl7.org/ValueSet/measure-scoring` |
| Version | 0.2.0 |
| Description | The scoring type of the measure. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `5029` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Measure` | `Measure.scoring` | `http://terminology.hl7.org/ValueSet/measure-scoring` | `Extensible` | proportion \| ratio \| continuous-variable \| cohort |
| `http://hl7.org/fhir/StructureDefinition/Measure` | `Measure.group.scoring` | `http://terminology.hl7.org/ValueSet/measure-scoring` | `Extensible` | proportion \| ratio \| continuous-variable \| cohort |
| `http://hl7.org/fhir/StructureDefinition/MeasureReport` | `MeasureReport.scoring` | `http://terminology.hl7.org/ValueSet/measure-scoring` | `Extensible` | What scoring method (e.g. proportion, ratio, continuous-variable) |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/measure-scoring`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/measure-scoring` | `cohort` | Cohort |
| `http://terminology.hl7.org/CodeSystem/measure-scoring` | `composite` | Composite |
| `http://terminology.hl7.org/CodeSystem/measure-scoring` | `continuous-variable` | Continuous Variable |
| `http://terminology.hl7.org/CodeSystem/measure-scoring` | `proportion` | Proportion |
| `http://terminology.hl7.org/CodeSystem/measure-scoring` | `ratio` | Ratio |
