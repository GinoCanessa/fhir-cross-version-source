Comparison of 
Generated at Thursday, April 3, 2025 8:18:18 AM

### Age

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | Age |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Age` |
| Version | 4.0.1 |
| Description | Base StructureDefinition for Age Type: A duration of time during which an organism (or a process) has existed. |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `991` |
| Database Snapshot Count | `8` |
| Database Differential Count | `1` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Age` | `Age` | `Age` | Age | A duration of time during which an organism (or a process) has existed | 0..* | Age | `Required` | `http://hl7.org/fhir/ValueSet/all-time-units` |
| `Age.code` | `Age.code` | `code` | Quantity.code | Coded form of the unit | 0..1 | code |  |  |
| `Age.comparator` | `Age.comparator` | `comparator` | Quantity.comparator | < \| <= \| >= \| > - how to understand the value | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/quantity-comparator|4.0.1` |
| `Age.extension` | `Age.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Age.id` | `Age.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Age.system` | `Age.system` | `system` | Quantity.system | System that defines coded unit form | 0..1 | uri |  |  |
| `Age.unit` | `Age.unit` | `unit` | Quantity.unit | Unit representation | 0..1 | string |  |  |
| `Age.value` | `Age.value` | `value` | Quantity.value | Numerical value (with implicit precision) | 0..1 | decimal |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Quantity](/docs/R2/ComplexTypes/Quantity.md)<br/> `http://hl7.org/fhir/StructureDefinition/Quantity\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `61`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `214`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Age](/docs/R3/ComplexTypes/Age.md)<br/> `http://hl7.org/fhir/StructureDefinition/Age\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `383`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `579`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Age](/docs/R4/ComplexTypes/Age.md)<br/> `http://hl7.org/fhir/StructureDefinition/Age\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1309`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1310`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Age](/docs/R4B/ComplexTypes/Age.md)<br/> `http://hl7.org/fhir/StructureDefinition/Age\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `890`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1119`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Age](/docs/R5/ComplexTypes/Age.md)<br/> `http://hl7.org/fhir/StructureDefinition/Age\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Age from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Quantity](/docs/R2/ComplexTypes/Quantity.md)| Relationship | [R3 Age](/docs/R3/ComplexTypes/Age.md)| Relationship | R4 Age| Relationship | [R4B Age](/docs/R4B/ComplexTypes/Age.md)| Relationship | [R5 Age](/docs/R5/ComplexTypes/Age.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `Age`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9154)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9155)| **`Age`**| _Equivalent_<br/>(20504/20505)| `Age`| _Equivalent_<br/>(35621/35622)| `Age`
| | | `Age.id`| _Equivalent_<br/>(9156/9157)| **`Age.id`**| _Equivalent_<br/>(20506/20507)| `Age.id`| _Equivalent_<br/>(35623/35624)| `Age.id`
| | | `Age.extension`| _Equivalent_<br/>(9158/9159)| **`Age.extension`**| _Equivalent_<br/>(20508/20509)| `Age.extension`| _Equivalent_<br/>(35625/35626)| `Age.extension`
| | | `Age.value`| _Equivalent_<br/>(9160/9161)| **`Age.value`**| _Equivalent_<br/>(20510/20511)| `Age.value`| _Equivalent_<br/>(35627/35628)| `Age.value`
| | | `Age.comparator`| _Equivalent_<br/>(9162/9163)| **`Age.comparator`**| _Equivalent_<br/>(20512/20513)| `Age.comparator`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(35629)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(35630)| `Age.comparator`
| | | `Age.unit`| _Equivalent_<br/>(9164/9165)| **`Age.unit`**| _Equivalent_<br/>(20514/20515)| `Age.unit`| _Equivalent_<br/>(35631/35632)| `Age.unit`
| | | `Age.system`| _Equivalent_<br/>(9166/9167)| **`Age.system`**| _Equivalent_<br/>(20516/20517)| `Age.system`| _Equivalent_<br/>(35633/35634)| `Age.system`
| | | `Age.code`| _Equivalent_<br/>(9168/9169)| **`Age.code`**| _Equivalent_<br/>(20518/20519)| `Age.code`| _Equivalent_<br/>(35635/35636)| `Age.code`
| *0 of 8 elements used* <br/>remaining elements:<br/>`Quantity`, `Quantity.code`, `Quantity.comparator`, `Quantity.extension`, `Quantity.id`, `Quantity.system`, `Quantity.unit`, `Quantity.value`| | *8 of 8 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* 

