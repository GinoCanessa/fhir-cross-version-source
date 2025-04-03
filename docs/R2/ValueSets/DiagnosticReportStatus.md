Comparison of 
Generated at Thursday, April 3, 2025 8:18:04 AM

### DiagnosticReportStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | DiagnosticReportStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/diagnostic-report-status` |
| Version | 1.0.2 |
| Description | The status of the diagnostic report as a whole. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `126` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DiagnosticReport` | `DiagnosticReport.status` | `http://hl7.org/fhir/ValueSet/diagnostic-report-status` | `Required` | registered \| partial \| final \| corrected \| appended \| cancelled \| entered-in-error |

### Referenced Systems

* `http://hl7.org/fhir/diagnostic-report-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DiagnosticReportStatus](/docs/R2/ValueSets/DiagnosticReportStatus.md)<br/> `http://hl7.org/fhir/ValueSet/diagnostic-report-status\|1.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `58`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `214`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DiagnosticReportStatus](/docs/R3/ValueSets/DiagnosticReportStatus.md)<br/> `http://hl7.org/fhir/ValueSet/diagnostic-report-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `392`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `615`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DiagnosticReportStatus](/docs/R4/ValueSets/DiagnosticReportStatus.md)<br/> `http://hl7.org/fhir/ValueSet/diagnostic-report-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1475`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1476`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DiagnosticReportStatus](/docs/R4B/ValueSets/DiagnosticReportStatus.md)<br/> `http://hl7.org/fhir/ValueSet/diagnostic-report-status\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `855`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1116`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DiagnosticReportStatus](/docs/R5/ValueSets/DiagnosticReportStatus.md)<br/> `http://hl7.org/fhir/ValueSet/diagnostic-report-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set DiagnosticReportStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 DiagnosticReportStatus| Relationship | [R3 DiagnosticReportStatus](/docs/R3/ValueSets/DiagnosticReportStatus.md)| Relationship | [R4 DiagnosticReportStatus](/docs/R4/ValueSets/DiagnosticReportStatus.md)| Relationship | [R4B DiagnosticReportStatus](/docs/R4B/ValueSets/DiagnosticReportStatus.md)| Relationship | [R5 DiagnosticReportStatus](/docs/R5/ValueSets/DiagnosticReportStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/diagnostic-report-status`
| **`registered`**| _Equivalent_ <br/>(457/1804)| `registered`| _Equivalent_ <br/>(3564/5850)| `registered`| _Equivalent_ <br/>(15780/15781)| `registered`| _Equivalent_ <br/>(7962/10268)| `registered`
| **`partial`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(461)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1803) | `partial`| _Equivalent_ <br/>(3568/5854)| `partial`| _Equivalent_ <br/>(15782/15783)| `partial`| _Equivalent_ <br/>(7966/10273)| `partial`
| **`partial`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(461)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1803) | `preliminary`| _Equivalent_ <br/>(3566/5852)| `preliminary`| _Equivalent_ <br/>(15784/15785)| `preliminary`| _Equivalent_ <br/>(7964/10271)| `preliminary`
| **`final`**| _Equivalent_ <br/>(456/1801)| `final`| _Equivalent_ <br/>(3563/5849)| `final`| _Equivalent_ <br/>(15786/15787)| `final`| _Equivalent_ <br/>(7961/10267)| `final`
| **`corrected`**| _Equivalent_ <br/>(462/1799)| `corrected`| _Equivalent_ <br/>(3569/5855)| `corrected`| _Equivalent_ <br/>(15790/15791)| `corrected`| _Equivalent_ <br/>(7967/10274)| `corrected`
| **`appended`**| _Equivalent_ <br/>(455/1797)| `appended`| _Equivalent_ <br/>(3562/5848)| `appended`| _Equivalent_ <br/>(15792/15793)| `appended`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(7959)<hr/>←←←← _Equivalent_ ←←←← <br/>(10266) | `modified`
| **`appended`**| _Equivalent_ <br/>(455/1797)| `appended`| _Equivalent_ <br/>(3562/5848)| `appended`| _Equivalent_ <br/>(15792/15793)| `appended`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(7959)<hr/>←←←← _Equivalent_ ←←←← <br/>(10266) | `appended`
| **`cancelled`**| _Equivalent_ <br/>(458/1798)| `cancelled`| _Equivalent_ <br/>(3565/5851)| `cancelled`| _Equivalent_ <br/>(15794/15795)| `cancelled`| _Equivalent_ <br/>(7963/10270)| `cancelled`
| **`entered-in-error`**| _Equivalent_ <br/>(459/1800)| `entered-in-error`| _Equivalent_ <br/>(3567/5853)| `entered-in-error`| _Equivalent_ <br/>(15796/15797)| `entered-in-error`| _Equivalent_ <br/>(7965/10272)| `entered-in-error`
| *7 of 7 codes used* | | *8 of 10 codes used* <br/>remaining codes:<br/>`amended`, `unknown`| | *8 of 10 codes used* <br/>remaining codes:<br/>`amended`, `unknown`| | *8 of 10 codes used* <br/>remaining codes:<br/>`amended`, `unknown`| | *9 of 11 codes used* <br/>remaining codes:<br/>`amended`, `unknown`

