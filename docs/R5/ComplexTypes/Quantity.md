Comparison of 
Generated at Friday, April 4, 2025 2:59:00 PM

### Quantity

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Quantity |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Quantity` |
| Version | 5.0.0 |
| Description | Quantity Type: A measured amount (or an amount that can potentially be measured). Note that measured amounts include amounts that are not precisely quantified, including amounts involving arbitrary units and floating currencies. |
| Status | `Active` |
| Artifact Class | `ComplexType` |
| Database Key | `2236` |
| Database Snapshot Count | `8` |
| Database Differential Count | `6` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Quantity` | `Quantity` | `Quantity` | Quantity | A measured or measurable amount | 0..* | Quantity |  |  |
| `Quantity.code` | `Quantity.code` | `code` | Quantity.code | Coded form of the unit | 0..1 | code |  |  |
| `Quantity.comparator` | `Quantity.comparator` | `comparator` | Quantity.comparator | < \| <= \| >= \| > \| ad - how to understand the value | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/quantity-comparator|5.0.0` |
| `Quantity.extension` | `Quantity.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Quantity.id` | `Quantity.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Quantity.system` | `Quantity.system` | `system` | Quantity.system | System that defines coded unit form | 0..1 | uri |  |  |
| `Quantity.unit` | `Quantity.unit` | `unit` | Quantity.unit | Unit representation | 0..1 | string |  |  |
| `Quantity.value` | `Quantity.value` | `value` | Quantity.value | Numerical value (with implicit precision) | 0..1 | decimal |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Quantity](/docs/R2/ComplexTypes/Quantity.md)<br/> `http://hl7.org/fhir/StructureDefinition/Quantity\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `60`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `231`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Quantity](/docs/R3/ComplexTypes/Quantity.md)<br/> `http://hl7.org/fhir/StructureDefinition/Quantity\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `405`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `601`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Quantity](/docs/R4/ComplexTypes/Quantity.md)<br/> `http://hl7.org/fhir/StructureDefinition/Quantity\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1367`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1368`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Quantity](/docs/R4B/ComplexTypes/Quantity.md)<br/> `http://hl7.org/fhir/StructureDefinition/Quantity\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `915`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1144`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Quantity](/docs/R5/ComplexTypes/Quantity.md)<br/> `http://hl7.org/fhir/StructureDefinition/Quantity\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Quantity from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Quantity](/docs/R2/ComplexTypes/Quantity.md)| Relationship | [R3 Quantity](/docs/R3/ComplexTypes/Quantity.md)| Relationship | [R4 Quantity](/docs/R4/ComplexTypes/Quantity.md)| Relationship | [R4B Quantity](/docs/R4B/ComplexTypes/Quantity.md)| Relationship | R5 Quantity
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Quantity`| _Equivalent_<br/>(2779/2780)| `Quantity`| _Equivalent_<br/>(9711/9712)| `Quantity`| _Equivalent_<br/>(21177/21178)| `Quantity`| _Equivalent_<br/>(36237/36238)| **`Quantity`**
| `Quantity.id`| _Equivalent_<br/>(2781/2782)| `Quantity.id`| _Equivalent_<br/>(9713/9714)| `Quantity.id`| _Equivalent_<br/>(21179/21180)| `Quantity.id`| _Equivalent_<br/>(36239/36240)| **`Quantity.id`**
| `Quantity.extension`| _Equivalent_<br/>(2783/2784)| `Quantity.extension`| _Equivalent_<br/>(9715/9716)| `Quantity.extension`| _Equivalent_<br/>(21181/21182)| `Quantity.extension`| _Equivalent_<br/>(36241/36242)| **`Quantity.extension`**
| `Quantity.value`| _Equivalent_<br/>(2785/2786)| `Quantity.value`| _Equivalent_<br/>(9717/9718)| `Quantity.value`| _Equivalent_<br/>(21183/21184)| `Quantity.value`| _Equivalent_<br/>(36243/36244)| **`Quantity.value`**
| `Quantity.comparator`| _Equivalent_<br/>(2787/2788)| `Quantity.comparator`| _Equivalent_<br/>(9719/9720)| `Quantity.comparator`| _Equivalent_<br/>(21185/21186)| `Quantity.comparator`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36245)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36246)| **`Quantity.comparator`**
| `Quantity.unit`| _Equivalent_<br/>(2789/2790)| `Quantity.unit`| _Equivalent_<br/>(9721/9722)| `Quantity.unit`| _Equivalent_<br/>(21187/21188)| `Quantity.unit`| _Equivalent_<br/>(36247/36248)| **`Quantity.unit`**
| `Quantity.system`| _Equivalent_<br/>(2791/2792)| `Quantity.system`| _Equivalent_<br/>(9723/9724)| `Quantity.system`| _Equivalent_<br/>(21189/21190)| `Quantity.system`| _Equivalent_<br/>(36249/36250)| **`Quantity.system`**
| `Quantity.code`| _Equivalent_<br/>(2793/2794)| `Quantity.code`| _Equivalent_<br/>(9725/9726)| `Quantity.code`| _Equivalent_<br/>(21191/21192)| `Quantity.code`| _Equivalent_<br/>(36251/36252)| **`Quantity.code`**
| *8 of 8 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* 

