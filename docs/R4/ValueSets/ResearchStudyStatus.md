Comparison of 
Generated at Monday, April 14, 2025 6:17:28 PM

### ResearchStudyStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ResearchStudyStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/research-study-status` |
| Version | 4.0.1 |
| Description | Codes that convey the current status of the research study. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2719` |
| Database Concept Count | `11` |
| Database Active Concept Count | `11` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ResearchStudy` | `ResearchStudy.status` | `http://hl7.org/fhir/ValueSet/research-study-status\|4.0.1` | `Required` | active \| administratively-completed \| approved \| closed-to-accrual \| closed-to-accrual-and-intervention \| completed \| disapproved \| in-review \| temporarily-closed-to-accrual \| temporarily-closed-to-accrual-and-intervention \| withdrawn |

### Referenced Systems

* `http://hl7.org/fhir/research-study-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [ResearchStudyStatus](/docs/R3/ValueSets/ResearchStudyStatus.md)<br/> `http://hl7.org/fhir/ValueSet/research-study-status\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `489`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `712`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ResearchStudyStatus](/docs/R4/ValueSets/ResearchStudyStatus.md)<br/> `http://hl7.org/fhir/ValueSet/research-study-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1707`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1708`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ResearchStudyStatus](/docs/R4B/ValueSets/ResearchStudyStatus.md)<br/> `http://hl7.org/fhir/ValueSet/research-study-status\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `973`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `1234`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [PublicationStatus](/docs/R5/ValueSets/PublicationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/publication-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ResearchStudyStatus from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 ResearchStudyStatus](/docs/R3/ValueSets/ResearchStudyStatus.md)| Relationship | R4 ResearchStudyStatus| Relationship | [R4B ResearchStudyStatus](/docs/R4B/ValueSets/ResearchStudyStatus.md)| Relationship | [R5 PublicationStatus](/docs/R5/ValueSets/PublicationStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4** System: `http://hl7.org/fhir/research-study-status`
| | | `in-progress`| →→→→ _Equivalent_ →→→→ <br/>(4576)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6889) | **`active`**| _Equivalent_ <br/>(17028/17029)| `active`| _Equivalent_ <br/>(9291/11635)| `active`
| | | `completed`| →→→→ _Equivalent_ →→→→ <br/>(4572)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6886) | **`administratively-completed`**| _Equivalent_ <br/>(17030/17031)| `administratively-completed`| | | 
| | | `in-progress`| →→→→ _Equivalent_ →→→→ <br/>(4577)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6885) | **`approved`**| _Equivalent_ <br/>(17032/17033)| `approved`| | | 
| | | `suspended`| →→→→ _Equivalent_ →→→→ <br/>(4580)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6892) | **`closed-to-accrual`**| _Equivalent_ <br/>(17034/17035)| `closed-to-accrual`| | | 
| | | `suspended`| →→→→ _Equivalent_ →→→→ <br/>(4581)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6884) | **`closed-to-accrual-and-intervention`**| _Equivalent_ <br/>(17036/17037)| `closed-to-accrual-and-intervention`| | | 
| | | `completed`| →→→→ _Equivalent_ →→→→ <br/>(4573)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6893) | **`completed`**| _Equivalent_ <br/>(17038/17039)| `completed`| | | 
| | | `suspended`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4582)<hr/>←←←← __ ←←←← <br/>() | **`disapproved`**| _Equivalent_ <br/>(17040/17041)| `disapproved`| | | 
| | | `stopped`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4578)<hr/>←←←← __ ←←←← <br/>() | **`disapproved`**| _Equivalent_ <br/>(17040/17041)| `disapproved`| | | 
| | | `draft`| _Equivalent_ <br/>(4574/6890)| **`in-review`**| _Equivalent_ <br/>(17042/17043)| `in-review`| | | 
| | | `suspended`| →→→→ _Equivalent_ →→→→ <br/>(4583)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6891) | **`temporarily-closed-to-accrual`**| _Equivalent_ <br/>(17044/17045)| `temporarily-closed-to-accrual`| | | 
| | | `suspended`| →→→→ _Equivalent_ →→→→ <br/>(4584)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6896) | **`temporarily-closed-to-accrual-and-intervention`**| _Equivalent_ <br/>(17046/17047)| `temporarily-closed-to-accrual-and-intervention`| | | 
| | | `stopped`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4579)<hr/>←←←← __ ←←←← <br/>() | **`withdrawn`**| _Equivalent_ <br/>(17048/17049)| `withdrawn`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9301)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11637) | `retired`
| | | `entered-in-error`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4575)<hr/>←←←← __ ←←←← <br/>() | **`withdrawn`**| _Equivalent_ <br/>(17048/17049)| `withdrawn`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9301)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11637) | `retired`
| | | *6 of 6 codes used* | | *11 of 11 codes used* | | *11 of 11 codes used* | | *2 of 4 codes used* <br/>remaining codes:<br/>`draft`, `unknown`

