Comparison of 
Generated at Tuesday, April 1, 2025 1:39:35 PM

### Duration

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Duration |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Duration` |
| Version | 5.0.0 |
| Description | Duration Type: A length of time. |
| Status | `Active` |
| Artifact Class | `ComplexType` |
| Database Key | `2219` |
| Database Snapshot Count | `8` |
| Database Differential Count | `1` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Duration` | `Duration` | `Duration` | Duration | A length of time | 0..* | Duration | `Required` | `http://hl7.org/fhir/ValueSet/all-time-units` |
| `Duration.code` | `Duration.code` | `code` | Quantity.code | Coded form of the unit | 0..1 | code |  |  |
| `Duration.comparator` | `Duration.comparator` | `comparator` | Quantity.comparator | < \| <= \| >= \| > \| ad - how to understand the value | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/quantity-comparator|5.0.0` |
| `Duration.extension` | `Duration.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Duration.id` | `Duration.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Duration.system` | `Duration.system` | `system` | Quantity.system | System that defines coded unit form | 0..1 | uri |  |  |
| `Duration.unit` | `Duration.unit` | `unit` | Quantity.unit | Unit representation | 0..1 | string |  |  |
| `Duration.value` | `Duration.value` | `value` | Quantity.value | Numerical value (with implicit precision) | 0..1 | decimal |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Quantity](/docs/R2/ComplexTypes/Quantity.md)<br/> `http://hl7.org/fhir/StructureDefinition/Quantity\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `65`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `222`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Duration](/docs/R3/ComplexTypes/Duration.md)<br/> `http://hl7.org/fhir/StructureDefinition/Duration\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `395`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `591`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Duration](/docs/R4/ComplexTypes/Duration.md)<br/> `http://hl7.org/fhir/StructureDefinition/Duration\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1335`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1336`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Duration](/docs/R4B/ComplexTypes/Duration.md)<br/> `http://hl7.org/fhir/StructureDefinition/Duration\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `903`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1132`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Duration](/docs/R5/ComplexTypes/Duration.md)<br/> `http://hl7.org/fhir/StructureDefinition/Duration\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Duration from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Quantity](/docs/R2/ComplexTypes/Quantity.md)| Relationship | [R3 Duration](/docs/R3/ComplexTypes/Duration.md)| Relationship | [R4 Duration](/docs/R4/ComplexTypes/Duration.md)| Relationship | [R4B Duration](/docs/R4B/ComplexTypes/Duration.md)| Relationship | R5 Duration
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `Duration`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9391)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9392)| `Duration`| _Equivalent_<br/>(20770/20771)| `Duration`| _Equivalent_<br/>(35885/35886)| **`Duration`**
| | | `Duration.id`| _Equivalent_<br/>(9393/9394)| `Duration.id`| _Equivalent_<br/>(20772/20773)| `Duration.id`| _Equivalent_<br/>(35887/35888)| **`Duration.id`**
| | | `Duration.extension`| _Equivalent_<br/>(9395/9396)| `Duration.extension`| _Equivalent_<br/>(20774/20775)| `Duration.extension`| _Equivalent_<br/>(35889/35890)| **`Duration.extension`**
| | | `Duration.value`| _Equivalent_<br/>(9397/9398)| `Duration.value`| _Equivalent_<br/>(20776/20777)| `Duration.value`| _Equivalent_<br/>(35891/35892)| **`Duration.value`**
| | | `Duration.comparator`| _Equivalent_<br/>(9399/9400)| `Duration.comparator`| _Equivalent_<br/>(20778/20779)| `Duration.comparator`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(35893)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(35894)| **`Duration.comparator`**
| | | `Duration.unit`| _Equivalent_<br/>(9401/9402)| `Duration.unit`| _Equivalent_<br/>(20780/20781)| `Duration.unit`| _Equivalent_<br/>(35895/35896)| **`Duration.unit`**
| | | `Duration.system`| _Equivalent_<br/>(9403/9404)| `Duration.system`| _Equivalent_<br/>(20782/20783)| `Duration.system`| _Equivalent_<br/>(35897/35898)| **`Duration.system`**
| | | `Duration.code`| _Equivalent_<br/>(9405/9406)| `Duration.code`| _Equivalent_<br/>(20784/20785)| `Duration.code`| _Equivalent_<br/>(35899/35900)| **`Duration.code`**
| *0 of 8 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* 

