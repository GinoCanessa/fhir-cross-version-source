Comparison of 
Generated at Monday, April 14, 2025 6:17:21 PM

### Money

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | Money |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Money` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for Money Type |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `461` |
| Database Snapshot Count | `8` |
| Database Differential Count | `1` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Money` | `Money` | `Money` | Money | An amount of economic utility in some recognized currency | 0..* | Money |  |  |
| `Money.code` | `Money.code` | `code` | Quantity.code | Coded form of the unit | 0..1 | code |  |  |
| `Money.comparator` | `Money.comparator` | `comparator` | Quantity.comparator | < \| <= \| >= \| > - how to understand the value | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/quantity-comparator` |
| `Money.extension` | `Money.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Money.id` | `Money.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Money.system` | `Money.system` | `system` | Quantity.system | System that defines coded unit form | 0..1 | uri |  |  |
| `Money.unit` | `Money.unit` | `unit` | Quantity.unit | Unit representation | 0..1 | string |  |  |
| `Money.value` | `Money.value` | `value` | Quantity.value | Numerical value (with implicit precision) | 0..1 | decimal |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Quantity](/docs/R2/ComplexTypes/Quantity.md)<br/> `http://hl7.org/fhir/StructureDefinition/Quantity\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `64`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `228`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Money](/docs/R3/ComplexTypes/Money.md)<br/> `http://hl7.org/fhir/StructureDefinition/Money\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `401`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `597`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Money](/docs/R4/ComplexTypes/Money.md)<br/> `http://hl7.org/fhir/StructureDefinition/Money\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1353`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1354`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Money](/docs/R4B/ComplexTypes/Money.md)<br/> `http://hl7.org/fhir/StructureDefinition/Money\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `910`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1139`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Money](/docs/R5/ComplexTypes/Money.md)<br/> `http://hl7.org/fhir/StructureDefinition/Money\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Money from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Quantity](/docs/R2/ComplexTypes/Quantity.md)| Relationship | R3 Money| Relationship | [R4 Money](/docs/R4/ComplexTypes/Money.md)| Relationship | [R4B Money](/docs/R4B/ComplexTypes/Money.md)| Relationship | [R5 Money](/docs/R5/ComplexTypes/Money.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | **`Money`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9660)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9661)| `Money`| _Equivalent_<br/>(21065/21066)| `Money`| _Equivalent_<br/>(36174/36175)| `Money`
| | | **`Money.id`**| _Equivalent_<br/>(9662/9663)| `Money.id`| _Equivalent_<br/>(21067/21068)| `Money.id`| _Equivalent_<br/>(36176/36177)| `Money.id`
| | | **`Money.extension`**| _Equivalent_<br/>(9664/9665)| `Money.extension`| _Equivalent_<br/>(21069/21070)| `Money.extension`| _Equivalent_<br/>(36178/36179)| `Money.extension`
| | | **`Money.value`**| _Equivalent_<br/>(9666/9667)| `Money.value`| _Equivalent_<br/>(21071/21072)| `Money.value`| _Equivalent_<br/>(36180/36181)| `Money.value`
| | | **`Money.comparator`**| | | | | | | 
| | | **`Money.unit`**| →→→→ __ →→→→ <br/>(9669)<hr/>←←←← __ ←←←← <br/>()| `base64Binary`| | | | | 
| | | **`Money.unit`**| →→→→ _Equivalent_ →→→→ <br/>(21064)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1710)| `Money.currency`| _Equivalent_<br/>(21073/21074)| `Money.currency`| _Equivalent_<br/>(36182/36183)| `Money.currency`
| | | **`Money.system`**| | | | | | | 
| | | **`Money.code`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1334)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1709)| `Money.currency`| _Equivalent_<br/>(21073/21074)| `Money.currency`| _Equivalent_<br/>(36182/36183)| `Money.currency`
| *0 of 8 elements used* <br/>remaining elements:<br/>`Quantity`, `Quantity.code`, `Quantity.comparator`, `Quantity.extension`, `Quantity.id`, `Quantity.system`, `Quantity.unit`, `Quantity.value`| | *8 of 8 elements used* | | *6 of 5 elements used* | | *5 of 5 elements used* | | *5 of 5 elements used* 

