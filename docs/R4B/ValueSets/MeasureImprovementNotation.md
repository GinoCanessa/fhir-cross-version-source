Comparison of 
Generated at Monday, April 14, 2025 6:17:35 PM

### MeasureImprovementNotation

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | MeasureImprovementNotation |
| Canonical URL | `http://hl7.org/fhir/ValueSet/measure-improvement-notation` |
| Version | 4.3.0 |
| Description | Observation values that indicate what change in a measurement value or score is indicative of an improvement in the measured item or scored issue. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3886` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Measure` | `Measure.improvementNotation` | `http://hl7.org/fhir/ValueSet/measure-improvement-notation\|4.3.0` | `Required` | increase \| decrease |
| `http://hl7.org/fhir/StructureDefinition/MeasureReport` | `MeasureReport.improvementNotation` | `http://hl7.org/fhir/ValueSet/measure-improvement-notation\|4.3.0` | `Required` | increase \| decrease |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/measure-improvement-notation`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [MeasureImprovementNotation](/docs/R4/ValueSets/MeasureImprovementNotation.md)<br/> `http://hl7.org/fhir/ValueSet/measure-improvement-notation\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1587`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1588`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [MeasureImprovementNotation](/docs/R4B/ValueSets/MeasureImprovementNotation.md)<br/> `http://hl7.org/fhir/ValueSet/measure-improvement-notation\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `917`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1178`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [MeasureImprovementNotation](/docs/R5/ValueSets/MeasureImprovementNotation.md)<br/> `http://hl7.org/fhir/ValueSet/measure-improvement-notation\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set MeasureImprovementNotation from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | [R4 MeasureImprovementNotation](/docs/R4/ValueSets/MeasureImprovementNotation.md)| Relationship | R4B MeasureImprovementNotation| Relationship | [R5 MeasureImprovementNotation](/docs/R5/ValueSets/MeasureImprovementNotation.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://terminology.hl7.org/CodeSystem/measure-improvement-notation`
| | | | | `increase`| _Equivalent_ <br/>(16468/16469)| **`increase`**| _Equivalent_ <br/>(8774/11083)| `increase`
| | | | | `decrease`| _Equivalent_ <br/>(16470/16471)| **`decrease`**| _Equivalent_ <br/>(8773/11082)| `decrease`
| | | | | *2 of 2 codes used* | | *2 of 2 codes used* | | *2 of 2 codes used* 

