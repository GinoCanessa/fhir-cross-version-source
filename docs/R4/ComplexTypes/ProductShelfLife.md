Comparison of 
Generated at Tuesday, April 1, 2025 1:39:20 PM

### ProductShelfLife

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | ProductShelfLife |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ProductShelfLife` |
| Version | 4.0.1 |
| Description | Base StructureDefinition for ProductShelfLife Type: The shelf-life and storage information for a medicinal product item or container can be described using this class. |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `1019` |
| Database Snapshot Count | `8` |
| Database Differential Count | `5` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ProductShelfLife` | `ProductShelfLife` | `ProductShelfLife` | ProductShelfLife | The shelf-life and storage information for a medicinal product item or container can be described using this class | 0..* | ProductShelfLife |  |  |
| `ProductShelfLife.extension` | `ProductShelfLife.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ProductShelfLife.id` | `ProductShelfLife.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ProductShelfLife.identifier` | `ProductShelfLife.identifier` | `identifier` | ProductShelfLife.identifier | Unique identifier for the packaged Medicinal Product | 0..1 | Identifier |  |  |
| `ProductShelfLife.modifierExtension` | `ProductShelfLife.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ProductShelfLife.period` | `ProductShelfLife.period` | `period` | ProductShelfLife.period | The shelf life time period can be specified using a numerical value for the period of time and its unit of time measurement The unit of measurement shall be specified in accordance with ISO 11240 and the resulting terminology The symbol and the symbol identifier shall be used | 1..1 | Quantity |  |  |
| `ProductShelfLife.specialPrecautionsForStorage` | `ProductShelfLife.specialPrecautionsForStorage` | `specialPrecautionsForStorage` | ProductShelfLife.specialPrecautionsForStorage | Special precautions for storage, if any, can be specified using an appropriate controlled vocabulary The controlled term and the controlled term identifier shall be specified | 0..* | CodeableConcept |  |  |
| `ProductShelfLife.type` | `ProductShelfLife.type` | `type` | ProductShelfLife.type | This describes the shelf life, taking into account various scenarios such as shelf life of the packaged Medicinal Product itself, shelf life after transformation where necessary and shelf life after the first opening of a bottle, etc. The shelf life type shall be specified using an appropriate controlled vocabulary The controlled term and the controlled term identifier shall be specified | 1..1 | CodeableConcept |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [ProductShelfLife](/docs/R4/ComplexTypes/ProductShelfLife.md)<br/> `http://hl7.org/fhir/StructureDefinition/ProductShelfLife\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1365`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1366`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ProductShelfLife](/docs/R4B/ComplexTypes/ProductShelfLife.md)<br/> `http://hl7.org/fhir/StructureDefinition/ProductShelfLife\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `914`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1143`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ProductShelfLife](/docs/R5/ComplexTypes/ProductShelfLife.md)<br/> `http://hl7.org/fhir/StructureDefinition/ProductShelfLife\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ProductShelfLife from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | R4 ProductShelfLife| Relationship | [R4B ProductShelfLife](/docs/R4B/ComplexTypes/ProductShelfLife.md)| Relationship | [R5 ProductShelfLife](/docs/R5/ComplexTypes/ProductShelfLife.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | **`ProductShelfLife`**| _Equivalent_<br/>(21161/21162)| `ProductShelfLife`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(36224)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36225)| `ProductShelfLife`
| | | | | **`ProductShelfLife.id`**| _Equivalent_<br/>(21163/21164)| `ProductShelfLife.id`| _Equivalent_<br/>(36226/36227)| `ProductShelfLife.id`
| | | | | **`ProductShelfLife.extension`**| _Equivalent_<br/>(21165/21166)| `ProductShelfLife.extension`| _Equivalent_<br/>(36228/36229)| `ProductShelfLife.extension`
| | | | | **`ProductShelfLife.modifierExtension`**| _Equivalent_<br/>(21167/21168)| `ProductShelfLife.modifierExtension`| _Equivalent_<br/>(36230/36231)| `ProductShelfLife.modifierExtension`
| | | | | **`ProductShelfLife.identifier`**| _Equivalent_<br/>(21169/21170)| `ProductShelfLife.identifier`| | | 
| | | | | **`ProductShelfLife.type`**| _Equivalent_<br/>(21171/21172)| `ProductShelfLife.type`| →→→→ _Equivalent_ →→→→ <br/>(36233)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36234)| `ProductShelfLife.type`
| | | | | **`ProductShelfLife.period`**| _Equivalent_<br/>(21173/21174)| `ProductShelfLife.period`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1713)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1957)| `ProductShelfLife.period[x]`
| | | | | **`ProductShelfLife.specialPrecautionsForStorage`**| _Equivalent_<br/>(21175/21176)| `ProductShelfLife.specialPrecautionsForStorage`| _Equivalent_<br/>(36235/36236)| `ProductShelfLife.specialPrecautionsForStorage`
| | | | | *8 of 8 elements used* | | *8 of 8 elements used* | | *7 of 7 elements used* 

