Comparison of 
Generated at Monday, April 14, 2025 6:17:28 PM

### MeasurePopulationType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | MeasurePopulationType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/measure-population` |
| Version | 4.0.1 |
| Description | The type of population. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2560` |
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
| | | [MeasurePopulationType](/docs/R3/ValueSets/MeasurePopulationType.md)<br/> `http://hl7.org/fhir/ValueSet/measure-population\|3.0.2` | →→→→→→→<br/>``<br/>- DBKey: `438`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `660`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [MeasurePopulationType](/docs/R4/ValueSets/MeasurePopulationType.md)<br/> `http://hl7.org/fhir/ValueSet/measure-population\|4.0.1` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | | | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set MeasurePopulationType from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 MeasurePopulationType](/docs/R3/ValueSets/MeasurePopulationType.md)| Relationship | R4 MeasurePopulationType| Relationship | *No Map* | Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://terminology.hl7.org/CodeSystem/measure-population`
| | | `initial-population`| _Equivalent_ <br/>(3953/6273)| **`initial-population`**| | | | | 
| | | `numerator`| _Equivalent_ <br/>(3954/6274)| **`numerator`**| | | | | 
| | | `numerator-exclusion`| _Equivalent_ <br/>(3950/6270)| **`numerator-exclusion`**| | | | | 
| | | `denominator`| _Equivalent_ <br/>(3955/6275)| **`denominator`**| | | | | 
| | | `denominator-exclusion`| _Equivalent_ <br/>(3948/6268)| **`denominator-exclusion`**| | | | | 
| | | `denominator-exception`| _Equivalent_ <br/>(3952/6272)| **`denominator-exception`**| | | | | 
| | | `measure-population`| _Equivalent_ <br/>(3951/6271)| **`measure-population`**| | | | | 
| | | `measure-population-exclusion`| _Equivalent_ <br/>(3956/6276)| **`measure-population-exclusion`**| | | | | 
| | | `measure-observation`| _Equivalent_ <br/>(3949/6269)| **`measure-observation`**| | | | | 
| | | *9 of 9 codes used* | | *9 of 9 codes used* | | | | 

