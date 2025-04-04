Comparison of 
Generated at Friday, April 4, 2025 2:58:51 PM

### MeasurePopulationType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | MeasurePopulationType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/measure-population` |
| Version | 4.3.0 |
| Description | The type of population. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3887` |
| Database Concept Count | `9` |
| Database Active Concept Count | `9` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Measure` | `Measure.group.population.code` | `http://hl7.org/fhir/ValueSet/measure-population` | `Extensible` | initial-population \| numerator \| numerator-exclusion \| denominator \| denominator-exclusion \| denominator-exception \| measure-population \| measure-population-exclusion \| measure-observation |
| `http://hl7.org/fhir/StructureDefinition/MeasureReport` | `MeasureReport.group.population.code` | `http://hl7.org/fhir/ValueSet/measure-population` | `Extensible` | initial-population \| numerator \| numerator-exclusion \| denominator \| denominator-exclusion \| denominator-exception \| measure-population \| measure-population-exclusion \| measure-observation |
| `http://hl7.org/fhir/StructureDefinition/MeasureReport` | `MeasureReport.group.stratifier.stratum.population.code` | `http://hl7.org/fhir/ValueSet/measure-population` | `Extensible` | initial-population \| numerator \| numerator-exclusion \| denominator \| denominator-exclusion \| denominator-exception \| measure-population \| measure-population-exclusion \| measure-observation |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/measure-population`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [MeasurePopulationType](/docs/R4B/ValueSets/MeasurePopulationType.md)<br/> `http://hl7.org/fhir/ValueSet/measure-population\|4.3.0` | →→→→→→→<br/>``<br/>- DBKey: `916`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1177`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MeasurePopulationType](/docs/R5/ValueSets/MeasurePopulationType.md)<br/> `http://hl7.org/fhir/ValueSet/measure-population\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set MeasurePopulationType from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | R4B MeasurePopulationType| Relationship | [R5 MeasurePopulationType](/docs/R5/ValueSets/MeasurePopulationType.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://terminology.hl7.org/CodeSystem/measure-population`
| | | | | | | **`initial-population`**| _Equivalent_ <br/>(8767/11076)| `initial-population`
| | | | | | | **`numerator`**| _Equivalent_ <br/>(8771/11080)| `numerator`
| | | | | | | **`numerator-exclusion`**| _Equivalent_ <br/>(8772/11081)| `numerator-exclusion`
| | | | | | | **`denominator`**| _Equivalent_ <br/>(8764/11073)| `denominator`
| | | | | | | **`denominator-exclusion`**| _Equivalent_ <br/>(8766/11075)| `denominator-exclusion`
| | | | | | | **`denominator-exception`**| _Equivalent_ <br/>(8765/11074)| `denominator-exception`
| | | | | | | **`measure-population`**| _Equivalent_ <br/>(8769/11078)| `measure-population`
| | | | | | | **`measure-population-exclusion`**| _Equivalent_ <br/>(8770/11079)| `measure-population-exclusion`
| | | | | | | **`measure-observation`**| _Equivalent_ <br/>(8768/11077)| `measure-observation`
| | | | | | | *9 of 9 codes used* | | *9 of 9 codes used* 

