Comparison of 
Generated at Friday, April 4, 2025 2:58:38 PM

### DataRequirement

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | DataRequirement |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/DataRequirement` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for DataRequirement Type |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `451` |
| Database Snapshot Count | `19` |
| Database Differential Count | `13` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `DataRequirement` | `DataRequirement` | `DataRequirement` | DataRequirement | Describes a required data item | 0..* | DataRequirement |  |  |
| `DataRequirement.codeFilter` | `DataRequirement.codeFilter` | `codeFilter` |  | What codes are expected | 0..* | Element |  |  |
| `DataRequirement.codeFilter.extension` | `DataRequirement.codeFilter.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `DataRequirement.codeFilter.id` | `DataRequirement.codeFilter.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `DataRequirement.codeFilter.path` | `DataRequirement.codeFilter.path` | `path` |  | The code-valued attribute of the filter | 1..1 | string |  |  |
| `DataRequirement.codeFilter.valueCode` | `DataRequirement.codeFilter.valueCode` | `valueCode` |  | What code is expected | 0..* | code |  |  |
| `DataRequirement.codeFilter.valueCodeableConcept` | `DataRequirement.codeFilter.valueCodeableConcept` | `valueCodeableConcept` |  | What CodeableConcept is expected | 0..* | CodeableConcept |  |  |
| `DataRequirement.codeFilter.valueCoding` | `DataRequirement.codeFilter.valueCoding` | `valueCoding` |  | What Coding is expected | 0..* | Coding |  |  |
| `DataRequirement.codeFilter.valueSet[x]` | `DataRequirement.codeFilter.valueSet[x]` | `valueSet[x]` |  | Valueset for the filter | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/ValueSet), string |  |  |
| `DataRequirement.dateFilter` | `DataRequirement.dateFilter` | `dateFilter` |  | What dates/date ranges are expected | 0..* | Element |  |  |
| `DataRequirement.dateFilter.extension` | `DataRequirement.dateFilter.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `DataRequirement.dateFilter.id` | `DataRequirement.dateFilter.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `DataRequirement.dateFilter.path` | `DataRequirement.dateFilter.path` | `path` |  | The date-valued attribute of the filter | 1..1 | string |  |  |
| `DataRequirement.dateFilter.value[x]` | `DataRequirement.dateFilter.value[x]` | `value[x]` |  | The value of the filter, as a Period, DateTime, or Duration value | 0..1 | dateTime, Duration, Period |  |  |
| `DataRequirement.extension` | `DataRequirement.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `DataRequirement.id` | `DataRequirement.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `DataRequirement.mustSupport` | `DataRequirement.mustSupport` | `mustSupport` |  | Indicates that specific structure elements are referenced by the knowledge module | 0..* | string |  |  |
| `DataRequirement.profile` | `DataRequirement.profile` | `profile` |  | The profile of the required data | 0..* | uri |  |  |
| `DataRequirement.type` | `DataRequirement.type` | `type` |  | The type of the required data | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-types` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [DataRequirement](/docs/R3/ComplexTypes/DataRequirement.md)<br/> `http://hl7.org/fhir/StructureDefinition/DataRequirement\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `392`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `588`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DataRequirement](/docs/R4/ComplexTypes/DataRequirement.md)<br/> `http://hl7.org/fhir/StructureDefinition/DataRequirement\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1329`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1330`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DataRequirement](/docs/R4B/ComplexTypes/DataRequirement.md)<br/> `http://hl7.org/fhir/StructureDefinition/DataRequirement\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `900`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1129`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DataRequirement](/docs/R5/ComplexTypes/DataRequirement.md)<br/> `http://hl7.org/fhir/StructureDefinition/DataRequirement\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition DataRequirement from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | R3 DataRequirement| Relationship | [R4 DataRequirement](/docs/R4/ComplexTypes/DataRequirement.md)| Relationship | [R4B DataRequirement](/docs/R4B/ComplexTypes/DataRequirement.md)| Relationship | [R5 DataRequirement](/docs/R5/ComplexTypes/DataRequirement.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | **`DataRequirement`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9299)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9300)| `DataRequirement`| _Equivalent_<br/>(20653/20654)| `DataRequirement`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(35769)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(35770)| `DataRequirement`
| | | **`DataRequirement.id`**| _Equivalent_<br/>(9301/9302)| `DataRequirement.id`| _Equivalent_<br/>(20655/20656)| `DataRequirement.id`| _Equivalent_<br/>(35771/35772)| `DataRequirement.id`
| | | **`DataRequirement.extension`**| _Equivalent_<br/>(9303/9304)| `DataRequirement.extension`| _Equivalent_<br/>(20657/20658)| `DataRequirement.extension`| _Equivalent_<br/>(35773/35774)| `DataRequirement.extension`
| | | **`DataRequirement.type`**| →→→→ _Equivalent_ →→→→ <br/>(9305)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9306)| `DataRequirement.type`| →→→→ _Equivalent_ →→→→ <br/>(20659)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(20660)| `DataRequirement.type`| _Equivalent_<br/>(35775/35776)| `DataRequirement.type`
| | | **`DataRequirement.profile`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9307)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9308)| `DataRequirement.profile`| _Equivalent_<br/>(20661/20662)| `DataRequirement.profile`| _Equivalent_<br/>(35777/35778)| `DataRequirement.profile`
| | | **`DataRequirement.mustSupport`**| _Equivalent_<br/>(9309/9310)| `DataRequirement.mustSupport`| _Equivalent_<br/>(20665/20666)| `DataRequirement.mustSupport`| _Equivalent_<br/>(35781/35782)| `DataRequirement.mustSupport`
| | | **`DataRequirement.codeFilter`**| _Equivalent_<br/>(9311/9312)| `DataRequirement.codeFilter`| _Equivalent_<br/>(20667/20668)| `DataRequirement.codeFilter`| _Equivalent_<br/>(35783/35784)| `DataRequirement.codeFilter`
| | | **`DataRequirement.codeFilter.id`**| _Equivalent_<br/>(9313/9314)| `DataRequirement.codeFilter.id`| _Equivalent_<br/>(20669/20670)| `DataRequirement.codeFilter.id`| _Equivalent_<br/>(35785/35786)| `DataRequirement.codeFilter.id`
| | | **`DataRequirement.codeFilter.extension`**| _Equivalent_<br/>(9315/9316)| `DataRequirement.codeFilter.extension`| _Equivalent_<br/>(20671/20672)| `DataRequirement.codeFilter.extension`| _Equivalent_<br/>(35787/35788)| `DataRequirement.codeFilter.extension`
| | | **`DataRequirement.codeFilter.path`**| →→→→ _Equivalent_ →→→→ <br/>(9317)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9318)| `DataRequirement.codeFilter.path`| _Equivalent_<br/>(20673/20674)| `DataRequirement.codeFilter.path`| _Equivalent_<br/>(35789/35790)| `DataRequirement.codeFilter.path`
| | | **`DataRequirement.codeFilter.valueSet[x]`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(983)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1471)| `DataRequirement.codeFilter.valueSet`| _Equivalent_<br/>(20677/20678)| `DataRequirement.codeFilter.valueSet`| _Equivalent_<br/>(35793/35794)| `DataRequirement.codeFilter.valueSet`
| | | **`DataRequirement.codeFilter.valueCode`**| | | | | | | 
| | | **`DataRequirement.codeFilter.valueCoding`**| _Equivalent_<br/>(982/1470)| `DataRequirement.codeFilter.code`| _Equivalent_<br/>(20679/20680)| `DataRequirement.codeFilter.code`| _Equivalent_<br/>(35795/35796)| `DataRequirement.codeFilter.code`
| | | **`DataRequirement.codeFilter.valueCodeableConcept`**| | | | | | | 
| | | **`DataRequirement.dateFilter`**| _Equivalent_<br/>(9319/9320)| `DataRequirement.dateFilter`| _Equivalent_<br/>(20681/20682)| `DataRequirement.dateFilter`| _Equivalent_<br/>(35797/35798)| `DataRequirement.dateFilter`
| | | **`DataRequirement.dateFilter.id`**| _Equivalent_<br/>(9321/9322)| `DataRequirement.dateFilter.id`| _Equivalent_<br/>(20683/20684)| `DataRequirement.dateFilter.id`| _Equivalent_<br/>(35799/35800)| `DataRequirement.dateFilter.id`
| | | **`DataRequirement.dateFilter.extension`**| _Equivalent_<br/>(9323/9324)| `DataRequirement.dateFilter.extension`| _Equivalent_<br/>(20685/20686)| `DataRequirement.dateFilter.extension`| _Equivalent_<br/>(35801/35802)| `DataRequirement.dateFilter.extension`
| | | **`DataRequirement.dateFilter.path`**| →→→→ _Equivalent_ →→→→ <br/>(9325)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9326)| `DataRequirement.dateFilter.path`| _Equivalent_<br/>(20687/20688)| `DataRequirement.dateFilter.path`| _Equivalent_<br/>(35803/35804)| `DataRequirement.dateFilter.path`
| | | **`DataRequirement.dateFilter.value[x]`**| _Equivalent_<br/>(9327/9328)| `DataRequirement.dateFilter.value[x]`| _Equivalent_<br/>(20691/20692)| `DataRequirement.dateFilter.value[x]`| _Equivalent_<br/>(35807/35808)| `DataRequirement.dateFilter.value[x]`
| | | *19 of 19 elements used* | | *17 of 26 elements used* <br/>remaining elements:<br/>`DataRequirement.codeFilter.searchParam`, `DataRequirement.dateFilter.searchParam`, `DataRequirement.limit`, `DataRequirement.sort`, `DataRequirement.sort.direction`, `DataRequirement.sort.extension`, `DataRequirement.sort.id`, `DataRequirement.sort.path`, `DataRequirement.subject[x]`| | *17 of 26 elements used* <br/>remaining elements:<br/>`DataRequirement.codeFilter.searchParam`, `DataRequirement.dateFilter.searchParam`, `DataRequirement.limit`, `DataRequirement.sort`, `DataRequirement.sort.direction`, `DataRequirement.sort.extension`, `DataRequirement.sort.id`, `DataRequirement.sort.path`, `DataRequirement.subject[x]`| | *17 of 33 elements used* <br/>remaining elements:<br/>`DataRequirement.codeFilter.searchParam`, `DataRequirement.dateFilter.searchParam`, `DataRequirement.limit`, `DataRequirement.sort`, `DataRequirement.sort.direction`, `DataRequirement.sort.extension`, `DataRequirement.sort.id`, `DataRequirement.sort.path`, `DataRequirement.subject[x]`, `DataRequirement.valueFilter`, `DataRequirement.valueFilter.comparator`, `DataRequirement.valueFilter.extension`, `DataRequirement.valueFilter.id`, `DataRequirement.valueFilter.path`, `DataRequirement.valueFilter.searchParam`, `DataRequirement.valueFilter.value[x]`

