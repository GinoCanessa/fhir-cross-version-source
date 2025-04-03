Comparison of 
Generated at Thursday, April 3, 2025 8:18:24 AM

### ContributorSummaryType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ContributorSummaryType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/contributor-summary-type` |
| Version | 4.3.0 |
| Description | Used to code author list statement, contributorship statement, and such. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3679` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Citation` | `Citation.citedArtifact.contributorship.summary.type` | `http://hl7.org/fhir/ValueSet/contributor-summary-type` | `Extensible` | Either authorList or contributorshipStatement |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/contributor-summary-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [ContributorSummaryType](/docs/R4B/ValueSets/ContributorSummaryType.md)<br/> `http://hl7.org/fhir/ValueSet/contributor-summary-type\|4.3.0` | →→→→→→→<br/>``<br/>- DBKey: `839`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>``<br/>- DBKey: `1100`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ContributorSummaryType](/docs/R5/ValueSets/ContributorSummaryType.md)<br/> `http://hl7.org/fhir/ValueSet/contributor-summary-type\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ContributorSummaryType from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | R4B ContributorSummaryType| Relationship | [R5 ContributorSummaryType](/docs/R5/ValueSets/ContributorSummaryType.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://terminology.hl7.org/CodeSystem/contributor-summary-type`
| | | | | | | **`author-string`**| _Equivalent_ <br/>(7826/10130)| `author-string`
| | | | | | | **`contributorship-list`**| _Equivalent_ <br/>(7825/10129)| `contributorship-list`
| | | | | | | **`contributorship-statement`**| _Equivalent_ <br/>(7821/10125)| `contributorship-statement`
| | | | | | | **`acknowledgement-list`**| _Equivalent_ <br/>(7822/10126)| `acknowledgement-list`
| | | | | | | **`acknowledgment-statement`**| _Equivalent_ <br/>(7823/10127)| `acknowledgment-statement`
| | | | | | | **`funding-statement`**| _Equivalent_ <br/>(7824/10128)| `funding-statement`
| | | | | | | **`competing-interests-statement`**| _Equivalent_ <br/>(7820/10124)| `competing-interests-statement`
| | | | | | | *7 of 7 codes used* | | *7 of 7 codes used* 

