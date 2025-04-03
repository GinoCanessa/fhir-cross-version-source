Comparison of 
Generated at Thursday, April 3, 2025 8:18:33 AM

### DataRequirement

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | DataRequirement |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/DataRequirement` |
| Version | 5.0.0 |
| Description | DataRequirement Type: Describes a required data item for evaluation in terms of the type of data, and optional code or date-based filters of the data. |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `2215` |
| Database Snapshot Count | `33` |
| Database Differential Count | `23` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `DataRequirement` | `DataRequirement` | `DataRequirement` | DataRequirement | Describes a required data item | 0..* | DataRequirement |  |  |
| `DataRequirement.codeFilter` | `DataRequirement.codeFilter` | `codeFilter` | DataRequirement.codeFilter | What codes are expected | 0..* | Element |  |  |
| `DataRequirement.codeFilter.code` | `DataRequirement.codeFilter.code` | `code` | DataRequirement.codeFilter.code | What code is expected | 0..* | Coding |  |  |
| `DataRequirement.codeFilter.extension` | `DataRequirement.codeFilter.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DataRequirement.codeFilter.id` | `DataRequirement.codeFilter.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DataRequirement.codeFilter.path` | `DataRequirement.codeFilter.path` | `path` | DataRequirement.codeFilter.path | A code-valued attribute to filter on | 0..1 | string |  |  |
| `DataRequirement.codeFilter.searchParam` | `DataRequirement.codeFilter.searchParam` | `searchParam` | DataRequirement.codeFilter.searchParam | A coded (token) parameter to search on | 0..1 | string |  |  |
| `DataRequirement.codeFilter.valueSet` | `DataRequirement.codeFilter.valueSet` | `valueSet` | DataRequirement.codeFilter.valueSet | ValueSet for the filter | 0..1 | canonical(http://hl7.org/fhir/StructureDefinition/ValueSet) |  |  |
| `DataRequirement.dateFilter` | `DataRequirement.dateFilter` | `dateFilter` | DataRequirement.dateFilter | What dates/date ranges are expected | 0..* | Element |  |  |
| `DataRequirement.dateFilter.extension` | `DataRequirement.dateFilter.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DataRequirement.dateFilter.id` | `DataRequirement.dateFilter.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DataRequirement.dateFilter.path` | `DataRequirement.dateFilter.path` | `path` | DataRequirement.dateFilter.path | A date-valued attribute to filter on | 0..1 | string |  |  |
| `DataRequirement.dateFilter.searchParam` | `DataRequirement.dateFilter.searchParam` | `searchParam` | DataRequirement.dateFilter.searchParam | A date valued parameter to search on | 0..1 | string |  |  |
| `DataRequirement.dateFilter.value[x]` | `DataRequirement.dateFilter.value[x]` | `value[x]` | DataRequirement.dateFilter.value[x] | The value of the filter, as a Period, DateTime, or Duration value | 0..1 | dateTime, Duration, Period |  |  |
| `DataRequirement.extension` | `DataRequirement.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DataRequirement.id` | `DataRequirement.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DataRequirement.limit` | `DataRequirement.limit` | `limit` | DataRequirement.limit | Number of results | 0..1 | positiveInt |  |  |
| `DataRequirement.mustSupport` | `DataRequirement.mustSupport` | `mustSupport` | DataRequirement.mustSupport | Indicates specific structure elements that are referenced by the knowledge module | 0..* | string |  |  |
| `DataRequirement.profile` | `DataRequirement.profile` | `profile` | DataRequirement.profile | The profile of the required data | 0..* | canonical(http://hl7.org/fhir/StructureDefinition/StructureDefinition) |  |  |
| `DataRequirement.sort` | `DataRequirement.sort` | `sort` | DataRequirement.sort | Order of the results | 0..* | Element |  |  |
| `DataRequirement.sort.direction` | `DataRequirement.sort.direction` | `direction` | DataRequirement.sort.direction | ascending \| descending | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/sort-direction|5.0.0` |
| `DataRequirement.sort.extension` | `DataRequirement.sort.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DataRequirement.sort.id` | `DataRequirement.sort.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DataRequirement.sort.path` | `DataRequirement.sort.path` | `path` | DataRequirement.sort.path | The name of the attribute to perform the sort | 1..1 | string |  |  |
| `DataRequirement.subject[x]` | `DataRequirement.subject[x]` | `subject[x]` | DataRequirement.subject[x] | E.g. Patient, Practitioner, RelatedPerson, Organization, Location, Device | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Group) | `Extensible` | `http://hl7.org/fhir/ValueSet/participant-resource-types` |
| `DataRequirement.type` | `DataRequirement.type` | `type` | DataRequirement.type | The type of the required data | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/fhir-types|5.0.0` |
| `DataRequirement.valueFilter` | `DataRequirement.valueFilter` | `valueFilter` | DataRequirement.valueFilter | What values are expected | 0..* | Element |  |  |
| `DataRequirement.valueFilter.comparator` | `DataRequirement.valueFilter.comparator` | `comparator` | DataRequirement.valueFilter.comparator | eq \| gt \| lt \| ge \| le \| sa \| eb | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/value-filter-comparator|5.0.0` |
| `DataRequirement.valueFilter.extension` | `DataRequirement.valueFilter.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DataRequirement.valueFilter.id` | `DataRequirement.valueFilter.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DataRequirement.valueFilter.path` | `DataRequirement.valueFilter.path` | `path` | DataRequirement.valueFilter.path | An attribute to filter on | 0..1 | string |  |  |
| `DataRequirement.valueFilter.searchParam` | `DataRequirement.valueFilter.searchParam` | `searchParam` | DataRequirement.valueFilter.searchParam | A parameter to search on | 0..1 | string |  |  |
| `DataRequirement.valueFilter.value[x]` | `DataRequirement.valueFilter.value[x]` | `value[x]` | DataRequirement.valueFilter.value[x] | The value of the filter, as a Period, DateTime, or Duration value | 0..1 | dateTime, Duration, Period |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [DataRequirement](/docs/R3/ComplexTypes/DataRequirement.md)<br/> `http://hl7.org/fhir/StructureDefinition/DataRequirement\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `392`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `588`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DataRequirement](/docs/R4/ComplexTypes/DataRequirement.md)<br/> `http://hl7.org/fhir/StructureDefinition/DataRequirement\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1329`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1330`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DataRequirement](/docs/R4B/ComplexTypes/DataRequirement.md)<br/> `http://hl7.org/fhir/StructureDefinition/DataRequirement\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `900`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1129`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DataRequirement](/docs/R5/ComplexTypes/DataRequirement.md)<br/> `http://hl7.org/fhir/StructureDefinition/DataRequirement\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition DataRequirement from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | [R3 DataRequirement](/docs/R3/ComplexTypes/DataRequirement.md)| Relationship | [R4 DataRequirement](/docs/R4/ComplexTypes/DataRequirement.md)| Relationship | [R4B DataRequirement](/docs/R4B/ComplexTypes/DataRequirement.md)| Relationship | R5 DataRequirement
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `DataRequirement`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9299)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9300)| `DataRequirement`| _Equivalent_<br/>(20653/20654)| `DataRequirement`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(35769)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(35770)| **`DataRequirement`**
| | | `DataRequirement.id`| _Equivalent_<br/>(9301/9302)| `DataRequirement.id`| _Equivalent_<br/>(20655/20656)| `DataRequirement.id`| _Equivalent_<br/>(35771/35772)| **`DataRequirement.id`**
| | | `DataRequirement.extension`| _Equivalent_<br/>(9303/9304)| `DataRequirement.extension`| _Equivalent_<br/>(20657/20658)| `DataRequirement.extension`| _Equivalent_<br/>(35773/35774)| **`DataRequirement.extension`**
| | | `DataRequirement.type`| →→→→ _Equivalent_ →→→→ <br/>(9305)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9306)| `DataRequirement.type`| →→→→ _Equivalent_ →→→→ <br/>(20659)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(20660)| `DataRequirement.type`| _Equivalent_<br/>(35775/35776)| **`DataRequirement.type`**
| | | `DataRequirement.profile`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9307)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9308)| `DataRequirement.profile`| _Equivalent_<br/>(20661/20662)| `DataRequirement.profile`| _Equivalent_<br/>(35777/35778)| **`DataRequirement.profile`**
| | | | | `DataRequirement.subject[x]`| _Equivalent_<br/>(20663/20664)| `DataRequirement.subject[x]`| _Equivalent_<br/>(35779/35780)| **`DataRequirement.subject[x]`**
| | | `DataRequirement.mustSupport`| _Equivalent_<br/>(9309/9310)| `DataRequirement.mustSupport`| _Equivalent_<br/>(20665/20666)| `DataRequirement.mustSupport`| _Equivalent_<br/>(35781/35782)| **`DataRequirement.mustSupport`**
| | | `DataRequirement.codeFilter`| _Equivalent_<br/>(9311/9312)| `DataRequirement.codeFilter`| _Equivalent_<br/>(20667/20668)| `DataRequirement.codeFilter`| _Equivalent_<br/>(35783/35784)| **`DataRequirement.codeFilter`**
| | | `DataRequirement.codeFilter.id`| _Equivalent_<br/>(9313/9314)| `DataRequirement.codeFilter.id`| _Equivalent_<br/>(20669/20670)| `DataRequirement.codeFilter.id`| _Equivalent_<br/>(35785/35786)| **`DataRequirement.codeFilter.id`**
| | | `DataRequirement.codeFilter.extension`| _Equivalent_<br/>(9315/9316)| `DataRequirement.codeFilter.extension`| _Equivalent_<br/>(20671/20672)| `DataRequirement.codeFilter.extension`| _Equivalent_<br/>(35787/35788)| **`DataRequirement.codeFilter.extension`**
| | | `DataRequirement.codeFilter.path`| →→→→ _Equivalent_ →→→→ <br/>(9317)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9318)| `DataRequirement.codeFilter.path`| _Equivalent_<br/>(20673/20674)| `DataRequirement.codeFilter.path`| _Equivalent_<br/>(35789/35790)| **`DataRequirement.codeFilter.path`**
| | | | | `DataRequirement.codeFilter.searchParam`| _Equivalent_<br/>(20675/20676)| `DataRequirement.codeFilter.searchParam`| _Equivalent_<br/>(35791/35792)| **`DataRequirement.codeFilter.searchParam`**
| | | `DataRequirement.codeFilter.valueSet[x]`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(983)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1471)| `DataRequirement.codeFilter.valueSet`| _Equivalent_<br/>(20677/20678)| `DataRequirement.codeFilter.valueSet`| _Equivalent_<br/>(35793/35794)| **`DataRequirement.codeFilter.valueSet`**
| | | `DataRequirement.codeFilter.valueCoding`| _Equivalent_<br/>(982/1470)| `DataRequirement.codeFilter.code`| _Equivalent_<br/>(20679/20680)| `DataRequirement.codeFilter.code`| _Equivalent_<br/>(35795/35796)| **`DataRequirement.codeFilter.code`**
| | | `DataRequirement.dateFilter`| _Equivalent_<br/>(9319/9320)| `DataRequirement.dateFilter`| _Equivalent_<br/>(20681/20682)| `DataRequirement.dateFilter`| _Equivalent_<br/>(35797/35798)| **`DataRequirement.dateFilter`**
| | | `DataRequirement.dateFilter.id`| _Equivalent_<br/>(9321/9322)| `DataRequirement.dateFilter.id`| _Equivalent_<br/>(20683/20684)| `DataRequirement.dateFilter.id`| _Equivalent_<br/>(35799/35800)| **`DataRequirement.dateFilter.id`**
| | | `DataRequirement.dateFilter.extension`| _Equivalent_<br/>(9323/9324)| `DataRequirement.dateFilter.extension`| _Equivalent_<br/>(20685/20686)| `DataRequirement.dateFilter.extension`| _Equivalent_<br/>(35801/35802)| **`DataRequirement.dateFilter.extension`**
| | | `DataRequirement.dateFilter.path`| →→→→ _Equivalent_ →→→→ <br/>(9325)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9326)| `DataRequirement.dateFilter.path`| _Equivalent_<br/>(20687/20688)| `DataRequirement.dateFilter.path`| _Equivalent_<br/>(35803/35804)| **`DataRequirement.dateFilter.path`**
| | | | | `DataRequirement.dateFilter.searchParam`| _Equivalent_<br/>(20689/20690)| `DataRequirement.dateFilter.searchParam`| _Equivalent_<br/>(35805/35806)| **`DataRequirement.dateFilter.searchParam`**
| | | `DataRequirement.dateFilter.value[x]`| _Equivalent_<br/>(9327/9328)| `DataRequirement.dateFilter.value[x]`| _Equivalent_<br/>(20691/20692)| `DataRequirement.dateFilter.value[x]`| _Equivalent_<br/>(35807/35808)| **`DataRequirement.dateFilter.value[x]`**
| | | | | | | | | **`DataRequirement.valueFilter`**
| | | | | | | | | **`DataRequirement.valueFilter.id`**
| | | | | | | | | **`DataRequirement.valueFilter.extension`**
| | | | | | | | | **`DataRequirement.valueFilter.path`**
| | | | | | | | | **`DataRequirement.valueFilter.searchParam`**
| | | | | | | | | **`DataRequirement.valueFilter.comparator`**
| | | | | | | | | **`DataRequirement.valueFilter.value[x]`**
| | | | | `DataRequirement.limit`| _Equivalent_<br/>(20693/20694)| `DataRequirement.limit`| _Equivalent_<br/>(35809/35810)| **`DataRequirement.limit`**
| | | | | `DataRequirement.sort`| _Equivalent_<br/>(20695/20696)| `DataRequirement.sort`| _Equivalent_<br/>(35811/35812)| **`DataRequirement.sort`**
| | | | | `DataRequirement.sort.id`| _Equivalent_<br/>(20697/20698)| `DataRequirement.sort.id`| _Equivalent_<br/>(35813/35814)| **`DataRequirement.sort.id`**
| | | | | `DataRequirement.sort.extension`| _Equivalent_<br/>(20699/20700)| `DataRequirement.sort.extension`| _Equivalent_<br/>(35815/35816)| **`DataRequirement.sort.extension`**
| | | | | `DataRequirement.sort.path`| _Equivalent_<br/>(20701/20702)| `DataRequirement.sort.path`| _Equivalent_<br/>(35817/35818)| **`DataRequirement.sort.path`**
| | | | | `DataRequirement.sort.direction`| _Equivalent_<br/>(20703/20704)| `DataRequirement.sort.direction`| _Equivalent_<br/>(35819/35820)| **`DataRequirement.sort.direction`**
| | | *17 of 19 elements used* <br/>remaining elements:<br/>`DataRequirement.codeFilter.valueCode`, `DataRequirement.codeFilter.valueCodeableConcept`| | *26 of 26 elements used* | | *26 of 26 elements used* | | *33 of 33 elements used* 

