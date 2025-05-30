Comparison of 
Generated at Monday, April 14, 2025 6:17:31 PM

### ResearchSubject

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | ResearchSubject |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ResearchSubject` |
| Version | 4.0.1 |
| Description | A physical entity which is the primary unit of operational and/or administrative interest in a study. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1150` |
| Database Snapshot Count | `17` |
| Database Differential Count | `9` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ResearchSubject` | `ResearchSubject` | `ResearchSubject` | ResearchSubject | Physical entity which is the primary unit of interest in the study | 0..* | ResearchSubject |  |  |
| `ResearchSubject.actualArm` | `ResearchSubject.actualArm` | `actualArm` | ResearchSubject.actualArm | What path was followed | 0..1 | string |  |  |
| `ResearchSubject.assignedArm` | `ResearchSubject.assignedArm` | `assignedArm` | ResearchSubject.assignedArm | What path should be followed | 0..1 | string |  |  |
| `ResearchSubject.consent` | `ResearchSubject.consent` | `consent` | ResearchSubject.consent | Agreement to participate in study | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Consent) |  |  |
| `ResearchSubject.contained` | `ResearchSubject.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ResearchSubject.extension` | `ResearchSubject.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ResearchSubject.id` | `ResearchSubject.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ResearchSubject.identifier` | `ResearchSubject.identifier` | `identifier` | ResearchSubject.identifier | Business Identifier for research subject in a study | 0..* | Identifier |  |  |
| `ResearchSubject.implicitRules` | `ResearchSubject.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ResearchSubject.individual` | `ResearchSubject.individual` | `individual` | ResearchSubject.individual | Who is part of study | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `ResearchSubject.language` | `ResearchSubject.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `ResearchSubject.meta` | `ResearchSubject.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ResearchSubject.modifierExtension` | `ResearchSubject.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ResearchSubject.period` | `ResearchSubject.period` | `period` | ResearchSubject.period | Start and end of participation | 0..1 | Period |  |  |
| `ResearchSubject.status` | `ResearchSubject.status` | `status` | ResearchSubject.status | candidate \| eligible \| follow-up \| ineligible \| not-registered \| off-study \| on-study \| on-study-intervention \| on-study-observation \| pending-on-study \| potential-candidate \| screening \| withdrawn | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/research-subject-status|4.0.1` |
| `ResearchSubject.study` | `ResearchSubject.study` | `study` | ResearchSubject.study | Study subject is part of | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/ResearchStudy) |  |  |
| `ResearchSubject.text` | `ResearchSubject.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [ResearchSubject](/docs/R3/Resources/ResearchSubject.md)<br/> `http://hl7.org/fhir/StructureDefinition/ResearchSubject\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `511`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `703`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ResearchSubject](/docs/R4/Resources/ResearchSubject.md)<br/> `http://hl7.org/fhir/StructureDefinition/ResearchSubject\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1603`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1604`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ResearchSubject](/docs/R4B/Resources/ResearchSubject.md)<br/> `http://hl7.org/fhir/StructureDefinition/ResearchSubject\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1036`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1265`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ResearchSubject](/docs/R5/Resources/ResearchSubject.md)<br/> `http://hl7.org/fhir/StructureDefinition/ResearchSubject\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ResearchSubject from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | [R3 ResearchSubject](/docs/R3/Resources/ResearchSubject.md)| Relationship | R4 ResearchSubject| Relationship | [R4B ResearchSubject](/docs/R4B/Resources/ResearchSubject.md)| Relationship | [R5 ResearchSubject](/docs/R5/Resources/ResearchSubject.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `ResearchSubject`| _Equivalent_<br/>(18106/18107)| **`ResearchSubject`**| _Equivalent_<br/>(32746/32747)| `ResearchSubject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47080)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47081)| `ResearchSubject`
| | | `ResearchSubject.id`| _Equivalent_<br/>(18108/18109)| **`ResearchSubject.id`**| _Equivalent_<br/>(32748/32749)| `ResearchSubject.id`| _Equivalent_<br/>(47082/47083)| `ResearchSubject.id`
| | | `ResearchSubject.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18110)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18111)| **`ResearchSubject.meta`**| _Equivalent_<br/>(32750/32751)| `ResearchSubject.meta`| _Equivalent_<br/>(47084/47085)| `ResearchSubject.meta`
| | | `ResearchSubject.implicitRules`| _Equivalent_<br/>(18112/18113)| **`ResearchSubject.implicitRules`**| _Equivalent_<br/>(32752/32753)| `ResearchSubject.implicitRules`| _Equivalent_<br/>(47086/47087)| `ResearchSubject.implicitRules`
| | | `ResearchSubject.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18114)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18115)| **`ResearchSubject.language`**| _Equivalent_<br/>(32754/32755)| `ResearchSubject.language`| _Equivalent_<br/>(47088/47089)| `ResearchSubject.language`
| | | `ResearchSubject.text`| _Equivalent_<br/>(18116/18117)| **`ResearchSubject.text`**| _Equivalent_<br/>(32756/32757)| `ResearchSubject.text`| _Equivalent_<br/>(47090/47091)| `ResearchSubject.text`
| | | `ResearchSubject.contained`| _Equivalent_<br/>(18118/18119)| **`ResearchSubject.contained`**| _Equivalent_<br/>(32758/32759)| `ResearchSubject.contained`| _Equivalent_<br/>(47092/47093)| `ResearchSubject.contained`
| | | `ResearchSubject.extension`| _Equivalent_<br/>(18120/18121)| **`ResearchSubject.extension`**| _Equivalent_<br/>(32760/32761)| `ResearchSubject.extension`| _Equivalent_<br/>(47094/47095)| `ResearchSubject.extension`
| | | `ResearchSubject.modifierExtension`| _Equivalent_<br/>(18122/18123)| **`ResearchSubject.modifierExtension`**| _Equivalent_<br/>(32762/32763)| `ResearchSubject.modifierExtension`| _Equivalent_<br/>(47096/47097)| `ResearchSubject.modifierExtension`
| | | `ResearchSubject.identifier`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18124)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18125)| **`ResearchSubject.identifier`**| _Equivalent_<br/>(32764/32765)| `ResearchSubject.identifier`| _Equivalent_<br/>(47098/47099)| `ResearchSubject.identifier`
| | | `ResearchSubject.status`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(18126)<hr/>←←←← _RelatedTo_ ←←←← <br/>(18127)| **`ResearchSubject.status`**| _Equivalent_<br/>(32766/32767)| `ResearchSubject.status`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47100)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47101)| `ResearchSubject.status`
| | | `ResearchSubject.period`| _Equivalent_<br/>(18128/18129)| **`ResearchSubject.period`**| _Equivalent_<br/>(32768/32769)| `ResearchSubject.period`| _Equivalent_<br/>(47102/47103)| `ResearchSubject.period`
| | | `ResearchSubject.study`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18130)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18131)| **`ResearchSubject.study`**| _Equivalent_<br/>(32770/32771)| `ResearchSubject.study`| _Equivalent_<br/>(47104/47105)| `ResearchSubject.study`
| | | `ResearchSubject.individual`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18132)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18133)| **`ResearchSubject.individual`**| _Equivalent_<br/>(32772/32773)| `ResearchSubject.individual`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1942)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2179)| `ResearchSubject.subject`
| | | `ResearchSubject.assignedArm`| _Equivalent_<br/>(18134/18135)| **`ResearchSubject.assignedArm`**| _Equivalent_<br/>(32774/32775)| `ResearchSubject.assignedArm`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1943)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2180)| `ResearchSubject.assignedComparisonGroup`
| | | `ResearchSubject.actualArm`| _Equivalent_<br/>(18136/18137)| **`ResearchSubject.actualArm`**| _Equivalent_<br/>(32776/32777)| `ResearchSubject.actualArm`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1944)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2181)| `ResearchSubject.actualComparisonGroup`
| | | `ResearchSubject.consent`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18138)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18139)| **`ResearchSubject.consent`**| _Equivalent_<br/>(32778/32779)| `ResearchSubject.consent`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47106)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47107)| `ResearchSubject.consent`
| | | *17 of 17 elements used* | | *17 of 17 elements used* | | *17 of 17 elements used* | | *17 of 27 elements used* <br/>remaining elements:<br/>`ResearchSubject.progress`, `ResearchSubject.progress.endDate`, `ResearchSubject.progress.extension`, `ResearchSubject.progress.id`, `ResearchSubject.progress.milestone`, `ResearchSubject.progress.modifierExtension`, `ResearchSubject.progress.reason`, `ResearchSubject.progress.startDate`, `ResearchSubject.progress.subjectState`, `ResearchSubject.progress.type`

