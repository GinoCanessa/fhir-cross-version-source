Comparison of 
Generated at Tuesday, April 1, 2025 1:39:35 PM

### MarketingStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | MarketingStatus |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/MarketingStatus` |
| Version | 5.0.0 |
| Description | MarketingStatus Type: The marketing status describes the date when a medicinal product is actually put on the market or the date as of which it is no longer available. |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `2227` |
| Database Snapshot Count | `9` |
| Database Differential Count | `6` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `MarketingStatus` | `MarketingStatus` | `MarketingStatus` | MarketingStatus | The marketing status describes the date when a medicinal product is actually put on the market or the date as of which it is no longer available | 0..* | MarketingStatus |  |  |
| `MarketingStatus.country` | `MarketingStatus.country` | `country` | MarketingStatus.country | The country in which the marketing authorization has been granted shall be specified It should be specified using the ISO 3166 ‑ 1 alpha-2 code elements | 0..1 | CodeableConcept |  |  |
| `MarketingStatus.dateRange` | `MarketingStatus.dateRange` | `dateRange` | MarketingStatus.dateRange | The date when the Medicinal Product is placed on the market by the Marketing Authorization Holder (or where applicable, the manufacturer/distributor) in a country and/or jurisdiction shall be provided A complete date consisting of day, month and year shall be specified using the ISO 8601 date format NOTE “Placed on the market” refers to the release of the Medicinal Product into the distribution chain | 0..1 | Period |  |  |
| `MarketingStatus.extension` | `MarketingStatus.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MarketingStatus.id` | `MarketingStatus.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MarketingStatus.jurisdiction` | `MarketingStatus.jurisdiction` | `jurisdiction` | MarketingStatus.jurisdiction | Where a Medicines Regulatory Agency has granted a marketing authorization for which specific provisions within a jurisdiction apply, the jurisdiction can be specified using an appropriate controlled terminology The controlled term and the controlled term identifier shall be specified | 0..1 | CodeableConcept |  |  |
| `MarketingStatus.modifierExtension` | `MarketingStatus.modifierExtension` | `modifierExtension` | BackboneType.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MarketingStatus.restoreDate` | `MarketingStatus.restoreDate` | `restoreDate` | MarketingStatus.restoreDate | The date when the Medicinal Product is placed on the market by the Marketing Authorization Holder (or where applicable, the manufacturer/distributor) in a country and/or jurisdiction shall be provided A complete date consisting of day, month and year shall be specified using the ISO 8601 date format NOTE “Placed on the market” refers to the release of the Medicinal Product into the distribution chain | 0..1 | dateTime |  |  |
| `MarketingStatus.status` | `MarketingStatus.status` | `status` | MarketingStatus.status | This attribute provides information on the status of the marketing of the medicinal product See ISO/TS 20443 for more information and examples | 1..1 | CodeableConcept |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [MarketingStatus](/docs/R4/ComplexTypes/MarketingStatus.md)<br/> `http://hl7.org/fhir/StructureDefinition/MarketingStatus\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1349`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1350`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MarketingStatus](/docs/R4B/ComplexTypes/MarketingStatus.md)<br/> `http://hl7.org/fhir/StructureDefinition/MarketingStatus\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1653`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1654`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [MarketingStatus](/docs/R5/ComplexTypes/MarketingStatus.md)<br/> `http://hl7.org/fhir/StructureDefinition/MarketingStatus\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition MarketingStatus from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | [R4 MarketingStatus](/docs/R4/ComplexTypes/MarketingStatus.md)| Relationship | [R4B MarketingStatus](/docs/R4B/ComplexTypes/MarketingStatus.md)| Relationship | R5 MarketingStatus
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `MarketingStatus`| _Equivalent_<br/>(21027/21028)| `MarketingStatus`| _Equivalent_<br/>(36138/36139)| **`MarketingStatus`**
| | | | | `MarketingStatus.id`| _Equivalent_<br/>(21029/21030)| `MarketingStatus.id`| _Equivalent_<br/>(36140/36141)| **`MarketingStatus.id`**
| | | | | `MarketingStatus.extension`| _Equivalent_<br/>(21031/21032)| `MarketingStatus.extension`| _Equivalent_<br/>(36142/36143)| **`MarketingStatus.extension`**
| | | | | `MarketingStatus.modifierExtension`| _Equivalent_<br/>(21033/21034)| `MarketingStatus.modifierExtension`| _Equivalent_<br/>(36144/36145)| **`MarketingStatus.modifierExtension`**
| | | | | `MarketingStatus.country`| →→→→ _Equivalent_ →→→→ <br/>(21035)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(21036)| `MarketingStatus.country`| _Equivalent_<br/>(36146/36147)| **`MarketingStatus.country`**
| | | | | `MarketingStatus.jurisdiction`| _Equivalent_<br/>(21037/21038)| `MarketingStatus.jurisdiction`| _Equivalent_<br/>(36148/36149)| **`MarketingStatus.jurisdiction`**
| | | | | `MarketingStatus.status`| _Equivalent_<br/>(21039/21040)| `MarketingStatus.status`| _Equivalent_<br/>(36150/36151)| **`MarketingStatus.status`**
| | | | | `MarketingStatus.dateRange`| →→→→ _Equivalent_ →→→→ <br/>(21041)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(21042)| `MarketingStatus.dateRange`| _Equivalent_<br/>(36152/36153)| **`MarketingStatus.dateRange`**
| | | | | `MarketingStatus.restoreDate`| _Equivalent_<br/>(21043/21044)| `MarketingStatus.restoreDate`| _Equivalent_<br/>(36154/36155)| **`MarketingStatus.restoreDate`**
| | | | | *9 of 9 elements used* | | *9 of 9 elements used* | | *9 of 9 elements used* 

