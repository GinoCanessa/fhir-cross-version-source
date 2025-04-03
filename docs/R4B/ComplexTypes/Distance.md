Comparison of 
Generated at Thursday, April 3, 2025 8:18:25 AM

### Distance

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | Distance |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Distance` |
| Version | 4.3.0 |
| Description | Base StructureDefinition for Distance Type: A length - a value with a unit that is a physical distance. |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `1609` |
| Database Snapshot Count | `8` |
| Database Differential Count | `1` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Distance` | `Distance` | `Distance` | Distance | A length - a value with a unit that is a physical distance | 0..* | Distance | `Required` | `http://hl7.org/fhir/ValueSet/all-distance-units` |
| `Distance.code` | `Distance.code` | `code` | Quantity.code | Coded form of the unit | 0..1 | code |  |  |
| `Distance.comparator` | `Distance.comparator` | `comparator` | Quantity.comparator | < \| <= \| >= \| > - how to understand the value | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/quantity-comparator|4.3.0` |
| `Distance.extension` | `Distance.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Distance.id` | `Distance.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Distance.system` | `Distance.system` | `system` | Quantity.system | System that defines coded unit form | 0..1 | uri |  |  |
| `Distance.unit` | `Distance.unit` | `unit` | Quantity.unit | Unit representation | 0..1 | string |  |  |
| `Distance.value` | `Distance.value` | `value` | Quantity.value | Numerical value (with implicit precision) | 0..1 | decimal |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Quantity](/docs/R2/ComplexTypes/Quantity.md)<br/> `http://hl7.org/fhir/StructureDefinition/Quantity\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `63`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `221`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Distance](/docs/R3/ComplexTypes/Distance.md)<br/> `http://hl7.org/fhir/StructureDefinition/Distance\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `393`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `589`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Distance](/docs/R4/ComplexTypes/Distance.md)<br/> `http://hl7.org/fhir/StructureDefinition/Distance\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1331`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1332`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Distance](/docs/R4B/ComplexTypes/Distance.md)<br/> `http://hl7.org/fhir/StructureDefinition/Distance\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `901`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1130`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Distance](/docs/R5/ComplexTypes/Distance.md)<br/> `http://hl7.org/fhir/StructureDefinition/Distance\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Distance from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Quantity](/docs/R2/ComplexTypes/Quantity.md)| Relationship | [R3 Distance](/docs/R3/ComplexTypes/Distance.md)| Relationship | [R4 Distance](/docs/R4/ComplexTypes/Distance.md)| Relationship | R4B Distance| Relationship | [R5 Distance](/docs/R5/ComplexTypes/Distance.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `Distance`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9337)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9338)| `Distance`| _Equivalent_<br/>(20705/20706)| **`Distance`**| _Equivalent_<br/>(35827/35828)| `Distance`
| | | `Distance.id`| _Equivalent_<br/>(9339/9340)| `Distance.id`| _Equivalent_<br/>(20707/20708)| **`Distance.id`**| _Equivalent_<br/>(35829/35830)| `Distance.id`
| | | `Distance.extension`| _Equivalent_<br/>(9341/9342)| `Distance.extension`| _Equivalent_<br/>(20709/20710)| **`Distance.extension`**| _Equivalent_<br/>(35831/35832)| `Distance.extension`
| | | `Distance.value`| _Equivalent_<br/>(9343/9344)| `Distance.value`| _Equivalent_<br/>(20711/20712)| **`Distance.value`**| _Equivalent_<br/>(35833/35834)| `Distance.value`
| | | `Distance.comparator`| _Equivalent_<br/>(9345/9346)| `Distance.comparator`| _Equivalent_<br/>(20713/20714)| **`Distance.comparator`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(35835)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(35836)| `Distance.comparator`
| | | `Distance.unit`| _Equivalent_<br/>(9347/9348)| `Distance.unit`| _Equivalent_<br/>(20715/20716)| **`Distance.unit`**| _Equivalent_<br/>(35837/35838)| `Distance.unit`
| | | `Distance.system`| _Equivalent_<br/>(9349/9350)| `Distance.system`| _Equivalent_<br/>(20717/20718)| **`Distance.system`**| _Equivalent_<br/>(35839/35840)| `Distance.system`
| | | `Distance.code`| _Equivalent_<br/>(9351/9352)| `Distance.code`| _Equivalent_<br/>(20719/20720)| **`Distance.code`**| _Equivalent_<br/>(35841/35842)| `Distance.code`
| *0 of 8 elements used* <br/>remaining elements:<br/>`Quantity`, `Quantity.code`, `Quantity.comparator`, `Quantity.extension`, `Quantity.id`, `Quantity.system`, `Quantity.unit`, `Quantity.value`| | *8 of 8 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* 

