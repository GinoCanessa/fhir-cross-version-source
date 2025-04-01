Comparison of 
Generated at Tuesday, April 1, 2025 1:39:11 PM

### MeasureReportType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | MeasureReportType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/measure-report-type` |
| Version | 3.0.2 |
| Description | The type of the measure report |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1319` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/MeasureReport` | `MeasureReport.type` | `http://hl7.org/fhir/ValueSet/measure-report-type` | `Required` | individual \| patient-list \| summary |

### Referenced Systems

* `http://hl7.org/fhir/measure-report-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [MeasureReportType](/docs/R3/ValueSets/MeasureReportType.md)<br/> `http://hl7.org/fhir/ValueSet/measure-report-type\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `447`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `669`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MeasureReportType](/docs/R4/ValueSets/MeasureReportType.md)<br/> `http://hl7.org/fhir/ValueSet/measure-report-type\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1591`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1592`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MeasureReportType](/docs/R4B/ValueSets/MeasureReportType.md)<br/> `http://hl7.org/fhir/ValueSet/measure-report-type\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `927`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1188`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MeasureReportType](/docs/R5/ValueSets/MeasureReportType.md)<br/> `http://hl7.org/fhir/ValueSet/measure-report-type\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set MeasureReportType from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | R3 MeasureReportType| Relationship | [R4 MeasureReportType](/docs/R4/ValueSets/MeasureReportType.md)| Relationship | [R4B MeasureReportType](/docs/R4B/ValueSets/MeasureReportType.md)| Relationship | [R5 MeasureReportType](/docs/R5/ValueSets/MeasureReportType.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/measure-report-type`
| | | **`individual`**| _Equivalent_ <br/>(3990/6315)| `individual`| _Equivalent_ <br/>(16478/16479)| `individual`| _Equivalent_ <br/>(8991/11300)| `individual`
| | | **`patient-list`**| _Equivalent_ <br/>(3991/6317)| `subject-list`| _Equivalent_ <br/>(16480/16481)| `subject-list`| _Equivalent_ <br/>(8993/11301)| `subject-list`
| | | **`summary`**| _Equivalent_ <br/>(3992/6314)| `summary`| _Equivalent_ <br/>(16482/16483)| `summary`| _Equivalent_ <br/>(8990/11302)| `summary`
| | | *3 of 3 codes used* | | *3 of 4 codes used* | | *3 of 4 codes used* | | *3 of 4 codes used* 

