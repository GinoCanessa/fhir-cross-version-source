Comparison of 
Generated at Thursday, April 3, 2025 8:18:24 AM

### MeasureStratifierExample

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | MeasureStratifierExample |
| Canonical URL | `http://hl7.org/fhir/ValueSet/measure-stratifier-example` |
| Version | 4.3.0 |
| Description | Identifier subgroups in a population for measuring purposes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3891` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Measure` | `Measure.group.stratifier.code` | `http://hl7.org/fhir/ValueSet/measure-stratifier-example` | `Example` | Meaning of the stratifier |
| `http://hl7.org/fhir/StructureDefinition/Measure` | `Measure.group.stratifier.component.code` | `http://hl7.org/fhir/ValueSet/measure-stratifier-example` | `Example` | Meaning of the stratifier component |
| `http://hl7.org/fhir/StructureDefinition/MeasureReport` | `MeasureReport.group.stratifier.code` | `http://hl7.org/fhir/ValueSet/measure-stratifier-example` | `Example` | What stratifier of the group |
| `http://hl7.org/fhir/StructureDefinition/MeasureReport` | `MeasureReport.group.stratifier.stratum.component.code` | `http://hl7.org/fhir/ValueSet/measure-stratifier-example` | `Example` | What stratifier component of the group |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/measure-stratifier-example`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/measure-stratifier-example` | `age` | Age |
| `http://terminology.hl7.org/CodeSystem/measure-stratifier-example` | `gender` | Gender |
| `http://terminology.hl7.org/CodeSystem/measure-stratifier-example` | `region` | Region |
