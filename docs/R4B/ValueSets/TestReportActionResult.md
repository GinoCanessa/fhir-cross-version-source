Comparison of 
Generated at Monday, April 14, 2025 6:17:35 PM

### TestReportActionResult

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | TestReportActionResult |
| Canonical URL | `http://hl7.org/fhir/ValueSet/report-action-result-codes` |
| Version | 4.3.0 |
| Description | The results of executing an action. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4048` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/TestReport` | `TestReport.setup.action.operation.result` | `http://hl7.org/fhir/ValueSet/report-action-result-codes\|4.3.0` | `Required` | pass \| skip \| fail \| warning \| error |
| `http://hl7.org/fhir/StructureDefinition/TestReport` | `TestReport.setup.action.assert.result` | `http://hl7.org/fhir/ValueSet/report-action-result-codes\|4.3.0` | `Required` | pass \| skip \| fail \| warning \| error |

### Referenced Systems

* `http://hl7.org/fhir/report-action-result-codes`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [TestReportActionResult](/docs/R3/ValueSets/TestReportActionResult.md)<br/> `http://hl7.org/fhir/ValueSet/report-action-result-codes\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `529`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `751`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [TestReportActionResult](/docs/R4/ValueSets/TestReportActionResult.md)<br/> `http://hl7.org/fhir/ValueSet/report-action-result-codes\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1687`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1688`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [TestReportActionResult](/docs/R4B/ValueSets/TestReportActionResult.md)<br/> `http://hl7.org/fhir/ValueSet/report-action-result-codes\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1012`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1273`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [TestReportActionResult](/docs/R5/ValueSets/TestReportActionResult.md)<br/> `http://hl7.org/fhir/ValueSet/report-action-result-codes\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set TestReportActionResult from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 TestReportActionResult](/docs/R3/ValueSets/TestReportActionResult.md)| Relationship | [R4 TestReportActionResult](/docs/R4/ValueSets/TestReportActionResult.md)| Relationship | R4B TestReportActionResult| Relationship | [R5 TestReportActionResult](/docs/R5/ValueSets/TestReportActionResult.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/report-action-result-codes`
| | | `pass`| _Equivalent_ <br/>(4944/7288)| `pass`| _Equivalent_ <br/>(16910/16911)| **`pass`**| _Equivalent_ <br/>(9528/11867)| `pass`
| | | `skip`| _Equivalent_ <br/>(4946/7290)| `skip`| _Equivalent_ <br/>(16912/16913)| **`skip`**| _Equivalent_ <br/>(9530/11869)| `skip`
| | | `fail`| _Equivalent_ <br/>(4943/7287)| `fail`| _Equivalent_ <br/>(16914/16915)| **`fail`**| _Equivalent_ <br/>(9527/11866)| `fail`
| | | `warning`| _Equivalent_ <br/>(4945/7289)| `warning`| _Equivalent_ <br/>(16916/16917)| **`warning`**| _Equivalent_ <br/>(9529/11868)| `warning`
| | | `error`| _Equivalent_ <br/>(4947/7291)| `error`| _Equivalent_ <br/>(16918/16919)| **`error`**| _Equivalent_ <br/>(9531/11870)| `error`
| | | *5 of 5 codes used* | | *5 of 5 codes used* | | *5 of 5 codes used* | | *5 of 5 codes used* 

