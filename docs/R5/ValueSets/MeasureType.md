Comparison of 
Generated at Monday, April 14, 2025 6:17:43 PM

### MeasureType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | MeasureType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/measure-type` |
| Version | 5.0.0 |
| Description | The type of measure (includes codes from 2.16.840.1.113883.1.11.20368). |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4694` |
| Database Concept Count | `5` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Measure` | `Measure.type` | `http://hl7.org/fhir/ValueSet/measure-type` | `Extensible` | process \| outcome \| structure \| patient-reported-outcome \| composite |
| `http://hl7.org/fhir/StructureDefinition/Measure` | `Measure.group.type` | `http://hl7.org/fhir/ValueSet/measure-type` | `Extensible` | process \| outcome \| structure \| patient-reported-outcome \| composite |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/measure-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [MeasureType](/docs/R4B/ValueSets/MeasureType.md)<br/> `http://hl7.org/fhir/ValueSet/measure-type\|4.3.0` | →→→→→→→<br/>``<br/>- DBKey: `919`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1180`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [MeasureType](/docs/R5/ValueSets/MeasureType.md)<br/> `http://hl7.org/fhir/ValueSet/measure-type\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set MeasureType from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B MeasureType](/docs/R4B/ValueSets/MeasureType.md)| Relationship | R5 MeasureType
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://terminology.hl7.org/CodeSystem/measure-type`
| | | | | | | `process`| _Equivalent_ <br/>(8780/11089)| **`process`**
| | | | | | | `outcome`| _Equivalent_ <br/>(8778/11087)| **`outcome`**
| | | | | | | `structure`| _Equivalent_ <br/>(8781/11090)| **`structure`**
| | | | | | | `patient-reported-outcome`| _Equivalent_ <br/>(8779/11088)| **`patient-reported-outcome`**
| | | | | | | *4 of 5 codes used* <br/>remaining codes:<br/>`composite`| | *4 of 5 codes used* <br/>remaining codes:<br/>

