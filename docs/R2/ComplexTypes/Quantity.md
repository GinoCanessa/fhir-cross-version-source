Comparison of 
Generated at Tuesday, April 1, 2025 1:39:07 PM

### Quantity

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | Quantity |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Quantity` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for Quantity Type |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `34` |
| Database Snapshot Count | `8` |
| Database Differential Count | `6` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Quantity` | `Quantity` | `Quantity` | Quantity | A measured or measurable amount | 0..* | Quantity |  |  |
| `Quantity.code` | `Quantity.code` | `code` |  | Coded form of the unit | 0..1 | code |  |  |
| `Quantity.comparator` | `Quantity.comparator` | `comparator` |  | < \| <= \| >= \| > - how to understand the value | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/quantity-comparator` |
| `Quantity.extension` | `Quantity.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Quantity.id` | `Quantity.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Quantity.system` | `Quantity.system` | `system` |  | System that defines coded unit form | 0..1 | uri |  |  |
| `Quantity.unit` | `Quantity.unit` | `unit` |  | Unit representation | 0..1 | string |  |  |
| `Quantity.value` | `Quantity.value` | `value` |  | Numerical value (with implicit precision) | 0..1 | decimal |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Quantity](/docs/R2/ComplexTypes/Quantity.md)<br/> `http://hl7.org/fhir/StructureDefinition/Quantity\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `60`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `231`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Age](/docs/R3/ComplexTypes/Age.md)<br/> `http://hl7.org/fhir/StructureDefinition/Age\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `383`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `579`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Age](/docs/R4/ComplexTypes/Age.md)<br/> `http://hl7.org/fhir/StructureDefinition/Age\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1309`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1310`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Age](/docs/R4B/ComplexTypes/Age.md)<br/> `http://hl7.org/fhir/StructureDefinition/Age\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `890`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1119`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Age](/docs/R5/ComplexTypes/Age.md)<br/> `http://hl7.org/fhir/StructureDefinition/Age\|5.0.0` 
| [Quantity](/docs/R2/ComplexTypes/Quantity.md)<br/> `http://hl7.org/fhir/StructureDefinition/Quantity\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `60`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `231`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Count](/docs/R3/ComplexTypes/Count.md)<br/> `http://hl7.org/fhir/StructureDefinition/Count\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `391`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `587`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Count](/docs/R4/ComplexTypes/Count.md)<br/> `http://hl7.org/fhir/StructureDefinition/Count\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1327`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1328`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Count](/docs/R4B/ComplexTypes/Count.md)<br/> `http://hl7.org/fhir/StructureDefinition/Count\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `899`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1128`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Count](/docs/R5/ComplexTypes/Count.md)<br/> `http://hl7.org/fhir/StructureDefinition/Count\|5.0.0` 
| [Quantity](/docs/R2/ComplexTypes/Quantity.md)<br/> `http://hl7.org/fhir/StructureDefinition/Quantity\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `60`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `231`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Distance](/docs/R3/ComplexTypes/Distance.md)<br/> `http://hl7.org/fhir/StructureDefinition/Distance\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `393`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `589`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Distance](/docs/R4/ComplexTypes/Distance.md)<br/> `http://hl7.org/fhir/StructureDefinition/Distance\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1331`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1332`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Distance](/docs/R4B/ComplexTypes/Distance.md)<br/> `http://hl7.org/fhir/StructureDefinition/Distance\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `901`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1130`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Distance](/docs/R5/ComplexTypes/Distance.md)<br/> `http://hl7.org/fhir/StructureDefinition/Distance\|5.0.0` 
| [Quantity](/docs/R2/ComplexTypes/Quantity.md)<br/> `http://hl7.org/fhir/StructureDefinition/Quantity\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `60`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `231`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Duration](/docs/R3/ComplexTypes/Duration.md)<br/> `http://hl7.org/fhir/StructureDefinition/Duration\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `395`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `591`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Duration](/docs/R4/ComplexTypes/Duration.md)<br/> `http://hl7.org/fhir/StructureDefinition/Duration\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1335`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1336`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Duration](/docs/R4B/ComplexTypes/Duration.md)<br/> `http://hl7.org/fhir/StructureDefinition/Duration\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `903`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1132`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Duration](/docs/R5/ComplexTypes/Duration.md)<br/> `http://hl7.org/fhir/StructureDefinition/Duration\|5.0.0` 
| [Quantity](/docs/R2/ComplexTypes/Quantity.md)<br/> `http://hl7.org/fhir/StructureDefinition/Quantity\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `60`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `231`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Money](/docs/R3/ComplexTypes/Money.md)<br/> `http://hl7.org/fhir/StructureDefinition/Money\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `401`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `597`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Money](/docs/R4/ComplexTypes/Money.md)<br/> `http://hl7.org/fhir/StructureDefinition/Money\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1353`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1354`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Money](/docs/R4B/ComplexTypes/Money.md)<br/> `http://hl7.org/fhir/StructureDefinition/Money\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `910`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1139`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Money](/docs/R5/ComplexTypes/Money.md)<br/> `http://hl7.org/fhir/StructureDefinition/Money\|5.0.0` 
| [Quantity](/docs/R2/ComplexTypes/Quantity.md)<br/> `http://hl7.org/fhir/StructureDefinition/Quantity\|1.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `60`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `231`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Quantity](/docs/R3/ComplexTypes/Quantity.md)<br/> `http://hl7.org/fhir/StructureDefinition/Quantity\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `405`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `601`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Quantity](/docs/R4/ComplexTypes/Quantity.md)<br/> `http://hl7.org/fhir/StructureDefinition/Quantity\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1367`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1368`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Quantity](/docs/R4B/ComplexTypes/Quantity.md)<br/> `http://hl7.org/fhir/StructureDefinition/Quantity\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `915`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1144`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Quantity](/docs/R5/ComplexTypes/Quantity.md)<br/> `http://hl7.org/fhir/StructureDefinition/Quantity\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Quantity from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Quantity| Relationship | [R3 Age](/docs/R3/ComplexTypes/Age.md)| Relationship | [R4 Age](/docs/R4/ComplexTypes/Age.md)| Relationship | [R4B Age](/docs/R4B/ComplexTypes/Age.md)| Relationship | [R5 Age](/docs/R5/ComplexTypes/Age.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Quantity`**| _Equivalent_<br/>(2779/2780)| `Quantity`| | | | | | | 
| **`Quantity.id`**| _Equivalent_<br/>(2781/2782)| `Quantity.id`| | | | | | | 
| **`Quantity.extension`**| _Equivalent_<br/>(2783/2784)| `Quantity.extension`| | | | | | | 
| **`Quantity.value`**| _Equivalent_<br/>(2785/2786)| `Quantity.value`| | | | | | | 
| **`Quantity.comparator`**| _Equivalent_<br/>(2787/2788)| `Quantity.comparator`| | | | | | | 
| **`Quantity.unit`**| _Equivalent_<br/>(2789/2790)| `Quantity.unit`| | | | | | | 
| **`Quantity.system`**| _Equivalent_<br/>(2791/2792)| `Quantity.system`| | | | | | | 
| **`Quantity.code`**| _Equivalent_<br/>(2793/2794)| `Quantity.code`| | | | | | | 
| *8 of 8 elements used* | | *8 of 8 elements used* | | *0 of 8 elements used* | | *0 of 8 elements used* | | *0 of 8 elements used* 


#### Map Group 1

This group is centered on the Structure Definition Quantity from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Quantity| Relationship | [R3 Count](/docs/R3/ComplexTypes/Count.md)| Relationship | [R4 Count](/docs/R4/ComplexTypes/Count.md)| Relationship | [R4B Count](/docs/R4B/ComplexTypes/Count.md)| Relationship | [R5 Count](/docs/R5/ComplexTypes/Count.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Quantity`**| _Equivalent_<br/>(2779/2780)| `Quantity`| | | | | | | 
| **`Quantity.id`**| _Equivalent_<br/>(2781/2782)| `Quantity.id`| | | | | | | 
| **`Quantity.extension`**| _Equivalent_<br/>(2783/2784)| `Quantity.extension`| | | | | | | 
| **`Quantity.value`**| _Equivalent_<br/>(2785/2786)| `Quantity.value`| | | | | | | 
| **`Quantity.comparator`**| _Equivalent_<br/>(2787/2788)| `Quantity.comparator`| | | | | | | 
| **`Quantity.unit`**| _Equivalent_<br/>(2789/2790)| `Quantity.unit`| | | | | | | 
| **`Quantity.system`**| _Equivalent_<br/>(2791/2792)| `Quantity.system`| | | | | | | 
| **`Quantity.code`**| _Equivalent_<br/>(2793/2794)| `Quantity.code`| | | | | | | 
| *8 of 8 elements used* | | *8 of 8 elements used* | | *0 of 8 elements used* | | *0 of 8 elements used* | | *0 of 8 elements used* 


#### Map Group 2

This group is centered on the Structure Definition Quantity from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Quantity| Relationship | [R3 Distance](/docs/R3/ComplexTypes/Distance.md)| Relationship | [R4 Distance](/docs/R4/ComplexTypes/Distance.md)| Relationship | [R4B Distance](/docs/R4B/ComplexTypes/Distance.md)| Relationship | [R5 Distance](/docs/R5/ComplexTypes/Distance.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Quantity`**| _Equivalent_<br/>(2779/2780)| `Quantity`| | | | | | | 
| **`Quantity.id`**| _Equivalent_<br/>(2781/2782)| `Quantity.id`| | | | | | | 
| **`Quantity.extension`**| _Equivalent_<br/>(2783/2784)| `Quantity.extension`| | | | | | | 
| **`Quantity.value`**| _Equivalent_<br/>(2785/2786)| `Quantity.value`| | | | | | | 
| **`Quantity.comparator`**| _Equivalent_<br/>(2787/2788)| `Quantity.comparator`| | | | | | | 
| **`Quantity.unit`**| _Equivalent_<br/>(2789/2790)| `Quantity.unit`| | | | | | | 
| **`Quantity.system`**| _Equivalent_<br/>(2791/2792)| `Quantity.system`| | | | | | | 
| **`Quantity.code`**| _Equivalent_<br/>(2793/2794)| `Quantity.code`| | | | | | | 
| *8 of 8 elements used* | | *8 of 8 elements used* | | *0 of 8 elements used* | | *0 of 8 elements used* | | *0 of 8 elements used* 


#### Map Group 3

This group is centered on the Structure Definition Quantity from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Quantity| Relationship | [R3 Duration](/docs/R3/ComplexTypes/Duration.md)| Relationship | [R4 Duration](/docs/R4/ComplexTypes/Duration.md)| Relationship | [R4B Duration](/docs/R4B/ComplexTypes/Duration.md)| Relationship | [R5 Duration](/docs/R5/ComplexTypes/Duration.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Quantity`**| _Equivalent_<br/>(2779/2780)| `Quantity`| | | | | | | 
| **`Quantity.id`**| _Equivalent_<br/>(2781/2782)| `Quantity.id`| | | | | | | 
| **`Quantity.extension`**| _Equivalent_<br/>(2783/2784)| `Quantity.extension`| | | | | | | 
| **`Quantity.value`**| _Equivalent_<br/>(2785/2786)| `Quantity.value`| | | | | | | 
| **`Quantity.comparator`**| _Equivalent_<br/>(2787/2788)| `Quantity.comparator`| | | | | | | 
| **`Quantity.unit`**| _Equivalent_<br/>(2789/2790)| `Quantity.unit`| | | | | | | 
| **`Quantity.system`**| _Equivalent_<br/>(2791/2792)| `Quantity.system`| | | | | | | 
| **`Quantity.code`**| _Equivalent_<br/>(2793/2794)| `Quantity.code`| | | | | | | 
| *8 of 8 elements used* | | *8 of 8 elements used* | | *0 of 8 elements used* | | *0 of 8 elements used* | | *0 of 8 elements used* 


#### Map Group 4

This group is centered on the Structure Definition Quantity from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Quantity| Relationship | [R3 Money](/docs/R3/ComplexTypes/Money.md)| Relationship | [R4 Money](/docs/R4/ComplexTypes/Money.md)| Relationship | [R4B Money](/docs/R4B/ComplexTypes/Money.md)| Relationship | [R5 Money](/docs/R5/ComplexTypes/Money.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Quantity`**| _Equivalent_<br/>(2779/2780)| `Quantity`| | | | | | | 
| **`Quantity.id`**| _Equivalent_<br/>(2781/2782)| `Quantity.id`| | | | | | | 
| **`Quantity.extension`**| _Equivalent_<br/>(2783/2784)| `Quantity.extension`| | | | | | | 
| **`Quantity.value`**| _Equivalent_<br/>(2785/2786)| `Quantity.value`| | | | | | | 
| **`Quantity.comparator`**| _Equivalent_<br/>(2787/2788)| `Quantity.comparator`| | | | | | | 
| **`Quantity.unit`**| _Equivalent_<br/>(2789/2790)| `Quantity.unit`| | | | | | | 
| **`Quantity.system`**| _Equivalent_<br/>(2791/2792)| `Quantity.system`| | | | | | | 
| **`Quantity.code`**| _Equivalent_<br/>(2793/2794)| `Quantity.code`| | | | | | | 
| *8 of 8 elements used* | | *8 of 8 elements used* | | *0 of 5 elements used* | | *0 of 5 elements used* | | *0 of 5 elements used* 


#### Map Group 5

This group is centered on the Structure Definition Quantity from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Quantity| Relationship | [R3 Quantity](/docs/R3/ComplexTypes/Quantity.md)| Relationship | [R4 Quantity](/docs/R4/ComplexTypes/Quantity.md)| Relationship | [R4B Quantity](/docs/R4B/ComplexTypes/Quantity.md)| Relationship | [R5 Quantity](/docs/R5/ComplexTypes/Quantity.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Quantity`**| _Equivalent_<br/>(2779/2780)| `Quantity`| _Equivalent_<br/>(9711/9712)| `Quantity`| _Equivalent_<br/>(21177/21178)| `Quantity`| _Equivalent_<br/>(36237/36238)| `Quantity`
| **`Quantity.id`**| _Equivalent_<br/>(2781/2782)| `Quantity.id`| _Equivalent_<br/>(9713/9714)| `Quantity.id`| _Equivalent_<br/>(21179/21180)| `Quantity.id`| _Equivalent_<br/>(36239/36240)| `Quantity.id`
| **`Quantity.extension`**| _Equivalent_<br/>(2783/2784)| `Quantity.extension`| _Equivalent_<br/>(9715/9716)| `Quantity.extension`| _Equivalent_<br/>(21181/21182)| `Quantity.extension`| _Equivalent_<br/>(36241/36242)| `Quantity.extension`
| **`Quantity.value`**| _Equivalent_<br/>(2785/2786)| `Quantity.value`| _Equivalent_<br/>(9717/9718)| `Quantity.value`| _Equivalent_<br/>(21183/21184)| `Quantity.value`| _Equivalent_<br/>(36243/36244)| `Quantity.value`
| **`Quantity.comparator`**| _Equivalent_<br/>(2787/2788)| `Quantity.comparator`| _Equivalent_<br/>(9719/9720)| `Quantity.comparator`| _Equivalent_<br/>(21185/21186)| `Quantity.comparator`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36245)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36246)| `Quantity.comparator`
| **`Quantity.unit`**| _Equivalent_<br/>(2789/2790)| `Quantity.unit`| _Equivalent_<br/>(9721/9722)| `Quantity.unit`| _Equivalent_<br/>(21187/21188)| `Quantity.unit`| _Equivalent_<br/>(36247/36248)| `Quantity.unit`
| **`Quantity.system`**| _Equivalent_<br/>(2791/2792)| `Quantity.system`| _Equivalent_<br/>(9723/9724)| `Quantity.system`| _Equivalent_<br/>(21189/21190)| `Quantity.system`| _Equivalent_<br/>(36249/36250)| `Quantity.system`
| **`Quantity.code`**| _Equivalent_<br/>(2793/2794)| `Quantity.code`| _Equivalent_<br/>(9725/9726)| `Quantity.code`| _Equivalent_<br/>(21191/21192)| `Quantity.code`| _Equivalent_<br/>(36251/36252)| `Quantity.code`
| *8 of 8 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* 

