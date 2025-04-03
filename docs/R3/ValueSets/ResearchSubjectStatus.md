Comparison of 
Generated at Thursday, April 3, 2025 8:18:09 AM

### ResearchSubjectStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | ResearchSubjectStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/research-subject-status` |
| Version | 3.0.2 |
| Description | Indicates the progression of a study subject through a study |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1449` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ResearchSubject` | `ResearchSubject.status` | `http://hl7.org/fhir/ValueSet/research-subject-status` | `Required` | candidate \| enrolled \| active \| suspended \| withdrawn \| completed |

### Referenced Systems

* `http://hl7.org/fhir/research-subject-status`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [ResearchSubjectStatus](/docs/R3/ValueSets/ResearchSubjectStatus.md)<br/> `http://hl7.org/fhir/ValueSet/research-subject-status\|3.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `488`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `711`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ResearchSubjectStatus](/docs/R4/ValueSets/ResearchSubjectStatus.md)<br/> `http://hl7.org/fhir/ValueSet/research-subject-status\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1709`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1710`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ResearchSubjectStatus](/docs/R4B/ValueSets/ResearchSubjectStatus.md)<br/> `http://hl7.org/fhir/ValueSet/research-subject-status\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `972`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1233`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [PublicationStatus](/docs/R5/ValueSets/PublicationStatus.md)<br/> `http://hl7.org/fhir/ValueSet/publication-status\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ResearchSubjectStatus from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | R3 ResearchSubjectStatus| Relationship | [R4 ResearchSubjectStatus](/docs/R4/ValueSets/ResearchSubjectStatus.md)| Relationship | [R4B ResearchSubjectStatus](/docs/R4B/ValueSets/ResearchSubjectStatus.md)| Relationship | [R5 PublicationStatus](/docs/R5/ValueSets/PublicationStatus.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R3** System: `http://hl7.org/fhir/research-subject-status`
| | | **`candidate`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4561)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6882) | `candidate`| _Equivalent_ <br/>(17050/17051)| `candidate`| | | 
| | | **`candidate`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4561)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6882) | `eligible`| _Equivalent_ <br/>(17052/17053)| `eligible`| | | 
| | | **`candidate`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4561)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6882) | `screening`| _Equivalent_ <br/>(17072/17073)| `screening`| | | 
| | | **`candidate`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4561)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6882) | `withdrawn`| _Equivalent_ <br/>(17074/17075)| `withdrawn`| _Equivalent_ <br/>(9281/11633)| `retired`
| | | **`enrolled`**| →→→→ _Equivalent_ →→→→ <br/>(4570)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6876) | `on-study`| _Equivalent_ <br/>(17062/17063)| `on-study`| | | 
| | | **`active`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4567)<hr/>←←←← _Equivalent_ ←←←← <br/>(6879) | `on-study`| _Equivalent_ <br/>(17062/17063)| `on-study`| | | 
| | | **`active`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4567)<hr/>←←←← _Equivalent_ ←←←← <br/>(6879) | `on-study-intervention`| _Equivalent_ <br/>(17064/17065)| `on-study-intervention`| | | 
| | | **`active`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4567)<hr/>←←←← _Equivalent_ ←←←← <br/>(6879) | `on-study-observation`| _Equivalent_ <br/>(17066/17067)| `on-study-observation`| | | 
| | | **`active`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4567)<hr/>←←←← _Equivalent_ ←←←← <br/>(6879) | `pending-on-study`| _Equivalent_ <br/>(17068/17069)| `pending-on-study`| | | 
| | | **`suspended`**| →→→→ _Equivalent_ →→→→ <br/>(4571)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6871) | `follow-up`| _Equivalent_ <br/>(17054/17055)| `follow-up`| | | 
| | | **`withdrawn`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4562)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6883) | `not-registered`| _Equivalent_ <br/>(17058/17059)| `not-registered`| | | 
| | | **`withdrawn`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4562)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(6883) | `withdrawn`| _Equivalent_ <br/>(17074/17075)| `withdrawn`| _Equivalent_ <br/>(9281/11633)| `retired`
| | | **`completed`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4569)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6874) | `follow-up`| _Equivalent_ <br/>(17054/17055)| `follow-up`| | | 
| | | **`completed`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4569)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6874) | `off-study`| _Equivalent_ <br/>(17060/17061)| `off-study`| | | 
| | | *6 of 6 codes used* | | *11 of 13 codes used* <br/>remaining codes:<br/>`ineligible`, `potential-candidate`| | *11 of 13 codes used* <br/>remaining codes:<br/>`ineligible`, `potential-candidate`| | *1 of 4 codes used* <br/>remaining codes:<br/>`active`, `draft`, `unknown`

