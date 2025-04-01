Comparison of 
Generated at Tuesday, April 1, 2025 1:39:06 PM

### QuestionnaireStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | QuestionnaireStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/questionnaire-status` |
| Version | 1.0.2 |
| Description | Lifecycle status of the questionnaire. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `330` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Questionnaire` | `Questionnaire.status` | `http://hl7.org/fhir/ValueSet/questionnaire-status` | `Required` | draft \| published \| retired |

### Referenced Systems

* `http://hl7.org/fhir/questionnaire-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [QuestionnaireStatus](/docs/R2/ValueSets/QuestionnaireStatus.md)<br/> `http://hl7.org/fhir/ValueSet/questionnaire-status\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `128`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `286`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [PublicationStatus](/docs/R3/ValueSets/PublicationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/publication-status\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `325`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `547`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [PublicationStatus](/docs/R4/ValueSets/PublicationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/publication-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1663`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1664`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [PublicationStatus](/docs/R4B/ValueSets/PublicationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/publication-status\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `771`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1032`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [PublicationStatus](/docs/R5/ValueSets/PublicationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/publication-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set QuestionnaireStatus from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 QuestionnaireStatus| Relationship | [R3 PublicationStatus](/docs/R3/ValueSets/PublicationStatus.md)| Relationship | [R4 PublicationStatus](/docs/R4/ValueSets/PublicationStatus.md)| Relationship | [R4B PublicationStatus](/docs/R4B/ValueSets/PublicationStatus.md)| Relationship | [R5 PublicationStatus](/docs/R5/ValueSets/PublicationStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/questionnaire-status`
| **`draft`**| _Equivalent_ <br/>(1085/2502)| `draft`| _Equivalent_ <br/>(2889/5078)| `draft`| _Equivalent_ <br/>(16810/16811)| `draft`| _Equivalent_ <br/>(7429/9694)| `draft`
| **`published`**| _Equivalent_ <br/>(1086/2501)| `active`| _Equivalent_ <br/>(2890/5079)| `active`| _Equivalent_ <br/>(16812/16813)| `active`| _Equivalent_ <br/>(7430/9695)| `active`
| **`retired`**| _Equivalent_ <br/>(1087/2503)| `retired`| _Equivalent_ <br/>(2891/5080)| `retired`| _Equivalent_ <br/>(16814/16815)| `retired`| _Equivalent_ <br/>(7431/9696)| `retired`
| *3 of 3 codes used* | | *3 of 4 codes used* | | *3 of 4 codes used* | | *3 of 4 codes used* | | *3 of 4 codes used* 

