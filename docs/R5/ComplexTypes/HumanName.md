Comparison of 
Generated at Monday, April 14, 2025 6:17:45 PM

### HumanName

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | HumanName |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/HumanName` |
| Version | 5.0.0 |
| Description | HumanName Type: A name, normally of a human, that can be used for other living entities (e.g. animals but not organizations) that have been assigned names by a human and may need the use of name parts or the need for usage information. |
| Status | `Active` |
| Artifact Class | `ComplexType` |
| Database Key | `2225` |
| Database Snapshot Count | `10` |
| Database Differential Count | `8` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `HumanName` | `HumanName` | `HumanName` | HumanName | Name of a human or other living entity - parts and usage | 0..* | HumanName |  |  |
| `HumanName.extension` | `HumanName.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `HumanName.family` | `HumanName.family` | `family` | HumanName.family | Family name (often called 'Surname') | 0..1 | string |  |  |
| `HumanName.given` | `HumanName.given` | `given` | HumanName.given | Given names (not always 'first'). Includes middle names | 0..* | string |  |  |
| `HumanName.id` | `HumanName.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `HumanName.period` | `HumanName.period` | `period` | HumanName.period | Time period when name was/is in use | 0..1 | Period |  |  |
| `HumanName.prefix` | `HumanName.prefix` | `prefix` | HumanName.prefix | Parts that come before the name | 0..* | string |  |  |
| `HumanName.suffix` | `HumanName.suffix` | `suffix` | HumanName.suffix | Parts that come after the name | 0..* | string |  |  |
| `HumanName.text` | `HumanName.text` | `text` | HumanName.text | Text representation of the full name | 0..1 | string |  |  |
| `HumanName.use` | `HumanName.use` | `use` | HumanName.use | usual \| official \| temp \| nickname \| anonymous \| old \| maiden | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/name-use|5.0.0` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [HumanName](/docs/R2/ComplexTypes/HumanName.md)<br/> `http://hl7.org/fhir/StructureDefinition/HumanName\|1.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `55`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `225`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [HumanName](/docs/R3/ComplexTypes/HumanName.md)<br/> `http://hl7.org/fhir/StructureDefinition/HumanName\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `398`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `594`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [HumanName](/docs/R4/ComplexTypes/HumanName.md)<br/> `http://hl7.org/fhir/StructureDefinition/HumanName\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1345`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1346`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [HumanName](/docs/R4B/ComplexTypes/HumanName.md)<br/> `http://hl7.org/fhir/StructureDefinition/HumanName\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `907`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1136`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [HumanName](/docs/R5/ComplexTypes/HumanName.md)<br/> `http://hl7.org/fhir/StructureDefinition/HumanName\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition HumanName from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 HumanName](/docs/R2/ComplexTypes/HumanName.md)| Relationship | [R3 HumanName](/docs/R3/ComplexTypes/HumanName.md)| Relationship | [R4 HumanName](/docs/R4/ComplexTypes/HumanName.md)| Relationship | [R4B HumanName](/docs/R4B/ComplexTypes/HumanName.md)| Relationship | R5 HumanName
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `HumanName`| _Equivalent_<br/>(2667/2668)| `HumanName`| _Equivalent_<br/>(9598/9599)| `HumanName`| _Equivalent_<br/>(20989/20990)| `HumanName`| _Equivalent_<br/>(36100/36101)| **`HumanName`**
| `HumanName.id`| _Equivalent_<br/>(2669/2670)| `HumanName.id`| _Equivalent_<br/>(9600/9601)| `HumanName.id`| _Equivalent_<br/>(20991/20992)| `HumanName.id`| _Equivalent_<br/>(36102/36103)| **`HumanName.id`**
| `HumanName.extension`| →→→→ _Equivalent_ →→→→ <br/>(2671)<hr/>←←←← __ ←←←← <br/>()| `HumanName.extension`| _Equivalent_<br/>(9602/9603)| `HumanName.extension`| _Equivalent_<br/>(20993/20994)| `HumanName.extension`| _Equivalent_<br/>(36104/36105)| **`HumanName.extension`**
| `HumanName.family`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(457)<hr/>←←←← __ ←←←← <br/>()| `HumanName.extension`| _Equivalent_<br/>(9602/9603)| `HumanName.extension`| _Equivalent_<br/>(20993/20994)| `HumanName.extension`| _Equivalent_<br/>(36104/36105)| **`HumanName.extension`**
| `HumanName.use`| _Equivalent_<br/>(2673/2674)| `HumanName.use`| _Equivalent_<br/>(9604/9605)| `HumanName.use`| _Equivalent_<br/>(20995/20996)| `HumanName.use`| _Equivalent_<br/>(36106/36107)| **`HumanName.use`**
| `HumanName.text`| _Equivalent_<br/>(2675/2676)| `HumanName.text`| _Equivalent_<br/>(9606/9607)| `HumanName.text`| _Equivalent_<br/>(20997/20998)| `HumanName.text`| _Equivalent_<br/>(36108/36109)| **`HumanName.text`**
| `HumanName.family`| →→→→ _Equivalent_ →→→→ <br/>(9597)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9596)| `HumanName.family`| _Equivalent_<br/>(9608/9609)| `HumanName.family`| _Equivalent_<br/>(20999/21000)| `HumanName.family`| _Equivalent_<br/>(36110/36111)| **`HumanName.family`**
| `HumanName.given`| _Equivalent_<br/>(2677/2678)| `HumanName.given`| _Equivalent_<br/>(9610/9611)| `HumanName.given`| _Equivalent_<br/>(21001/21002)| `HumanName.given`| _Equivalent_<br/>(36112/36113)| **`HumanName.given`**
| `HumanName.prefix`| _Equivalent_<br/>(2679/2680)| `HumanName.prefix`| _Equivalent_<br/>(9612/9613)| `HumanName.prefix`| _Equivalent_<br/>(21003/21004)| `HumanName.prefix`| _Equivalent_<br/>(36114/36115)| **`HumanName.prefix`**
| `HumanName.suffix`| _Equivalent_<br/>(2681/2682)| `HumanName.suffix`| _Equivalent_<br/>(9614/9615)| `HumanName.suffix`| _Equivalent_<br/>(21005/21006)| `HumanName.suffix`| _Equivalent_<br/>(36116/36117)| **`HumanName.suffix`**
| `HumanName.period`| _Equivalent_<br/>(2683/2684)| `HumanName.period`| _Equivalent_<br/>(9616/9617)| `HumanName.period`| _Equivalent_<br/>(21007/21008)| `HumanName.period`| _Equivalent_<br/>(36118/36119)| **`HumanName.period`**
| *10 of 10 elements used* | | *10 of 10 elements used* | | *10 of 10 elements used* | | *10 of 10 elements used* | | *10 of 10 elements used* 

