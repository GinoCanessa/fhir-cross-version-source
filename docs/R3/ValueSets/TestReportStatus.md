Comparison of 
Generated at Tuesday, April 1, 2025 1:39:12 PM

### TestReportStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | TestReportStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/report-status-codes` |
| Version | 3.0.2 |
| Description | The current status of the test report. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1443` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/TestReport` | `TestReport.status` | `http://hl7.org/fhir/ValueSet/report-status-codes` | `Required` | completed \| in-progress \| waiting \| stopped \| entered-in-error |

### Referenced Systems

* `http://hl7.org/fhir/report-status-codes`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [TestReportStatus](/docs/R3/ValueSets/TestReportStatus.md)<br/> `http://hl7.org/fhir/ValueSet/report-status-codes\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `530`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `752`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TestReportStatus](/docs/R4/ValueSets/TestReportStatus.md)<br/> `http://hl7.org/fhir/ValueSet/report-status-codes\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1693`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1694`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TestReportStatus](/docs/R4B/ValueSets/TestReportStatus.md)<br/> `http://hl7.org/fhir/ValueSet/report-status-codes\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1013`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1274`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TestReportStatus](/docs/R5/ValueSets/TestReportStatus.md)<br/> `http://hl7.org/fhir/ValueSet/report-status-codes\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set TestReportStatus from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | R3 TestReportStatus| Relationship | [R4 TestReportStatus](/docs/R4/ValueSets/TestReportStatus.md)| Relationship | [R4B TestReportStatus](/docs/R4B/ValueSets/TestReportStatus.md)| Relationship | [R5 TestReportStatus](/docs/R5/ValueSets/TestReportStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/report-status-codes`
| | | **`completed`**| _Equivalent_ <br/>(4950/7294)| `completed`| _Equivalent_ <br/>(16932/16933)| `completed`| _Equivalent_ <br/>(9534/11873)| `completed`
| | | **`in-progress`**| _Equivalent_ <br/>(4952/7296)| `in-progress`| _Equivalent_ <br/>(16934/16935)| `in-progress`| _Equivalent_ <br/>(9536/11875)| `in-progress`
| | | **`waiting`**| _Equivalent_ <br/>(4949/7293)| `waiting`| _Equivalent_ <br/>(16936/16937)| `waiting`| _Equivalent_ <br/>(9533/11872)| `waiting`
| | | **`stopped`**| _Equivalent_ <br/>(4948/7292)| `stopped`| _Equivalent_ <br/>(16938/16939)| `stopped`| _Equivalent_ <br/>(9532/11871)| `stopped`
| | | **`entered-in-error`**| _Equivalent_ <br/>(4951/7295)| `entered-in-error`| _Equivalent_ <br/>(16940/16941)| `entered-in-error`| _Equivalent_ <br/>(9535/11874)| `entered-in-error`
| | | *5 of 5 codes used* | | *5 of 5 codes used* | | *5 of 5 codes used* | | *5 of 5 codes used* 

