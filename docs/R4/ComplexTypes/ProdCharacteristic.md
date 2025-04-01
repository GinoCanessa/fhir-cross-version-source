Comparison of 
Generated at Tuesday, April 1, 2025 1:39:20 PM

### ProdCharacteristic

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | ProdCharacteristic |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ProdCharacteristic` |
| Version | 4.0.1 |
| Description | Base StructureDefinition for ProdCharacteristic Type: The marketing status describes the date when a medicinal product is actually put on the market or the date as of which it is no longer available. |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `1018` |
| Database Snapshot Count | `15` |
| Database Differential Count | `12` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ProdCharacteristic` | `ProdCharacteristic` | `ProdCharacteristic` | ProdCharacteristic | The marketing status describes the date when a medicinal product is actually put on the market or the date as of which it is no longer available | 0..* | ProdCharacteristic |  |  |
| `ProdCharacteristic.color` | `ProdCharacteristic.color` | `color` | ProdCharacteristic.color | Where applicable, the color can be specified An appropriate controlled vocabulary shall be used The term and the term identifier shall be used | 0..* | string |  |  |
| `ProdCharacteristic.depth` | `ProdCharacteristic.depth` | `depth` | ProdCharacteristic.depth | Where applicable, the depth can be specified using a numerical value and its unit of measurement The unit of measurement shall be specified in accordance with ISO 11240 and the resulting terminology The symbol and the symbol identifier shall be used | 0..1 | Quantity |  |  |
| `ProdCharacteristic.extension` | `ProdCharacteristic.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ProdCharacteristic.externalDiameter` | `ProdCharacteristic.externalDiameter` | `externalDiameter` | ProdCharacteristic.externalDiameter | Where applicable, the external diameter can be specified using a numerical value and its unit of measurement The unit of measurement shall be specified in accordance with ISO 11240 and the resulting terminology The symbol and the symbol identifier shall be used | 0..1 | Quantity |  |  |
| `ProdCharacteristic.height` | `ProdCharacteristic.height` | `height` | ProdCharacteristic.height | Where applicable, the height can be specified using a numerical value and its unit of measurement The unit of measurement shall be specified in accordance with ISO 11240 and the resulting terminology The symbol and the symbol identifier shall be used | 0..1 | Quantity |  |  |
| `ProdCharacteristic.id` | `ProdCharacteristic.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ProdCharacteristic.image` | `ProdCharacteristic.image` | `image` | ProdCharacteristic.image | Where applicable, the image can be provided The format of the image attachment shall be specified by regional implementations | 0..* | Attachment |  |  |
| `ProdCharacteristic.imprint` | `ProdCharacteristic.imprint` | `imprint` | ProdCharacteristic.imprint | Where applicable, the imprint can be specified as text | 0..* | string |  |  |
| `ProdCharacteristic.modifierExtension` | `ProdCharacteristic.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ProdCharacteristic.nominalVolume` | `ProdCharacteristic.nominalVolume` | `nominalVolume` | ProdCharacteristic.nominalVolume | Where applicable, the nominal volume can be specified using a numerical value and its unit of measurement The unit of measurement shall be specified in accordance with ISO 11240 and the resulting terminology The symbol and the symbol identifier shall be used | 0..1 | Quantity |  |  |
| `ProdCharacteristic.scoring` | `ProdCharacteristic.scoring` | `scoring` | ProdCharacteristic.scoring | Where applicable, the scoring can be specified An appropriate controlled vocabulary shall be used The term and the term identifier shall be used | 0..1 | CodeableConcept |  |  |
| `ProdCharacteristic.shape` | `ProdCharacteristic.shape` | `shape` | ProdCharacteristic.shape | Where applicable, the shape can be specified An appropriate controlled vocabulary shall be used The term and the term identifier shall be used | 0..1 | string |  |  |
| `ProdCharacteristic.weight` | `ProdCharacteristic.weight` | `weight` | ProdCharacteristic.weight | Where applicable, the weight can be specified using a numerical value and its unit of measurement The unit of measurement shall be specified in accordance with ISO 11240 and the resulting terminology The symbol and the symbol identifier shall be used | 0..1 | Quantity |  |  |
| `ProdCharacteristic.width` | `ProdCharacteristic.width` | `width` | ProdCharacteristic.width | Where applicable, the width can be specified using a numerical value and its unit of measurement The unit of measurement shall be specified in accordance with ISO 11240 and the resulting terminology The symbol and the symbol identifier shall be used | 0..1 | Quantity |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [ProdCharacteristic](/docs/R4/ComplexTypes/ProdCharacteristic.md)<br/> `http://hl7.org/fhir/StructureDefinition/ProdCharacteristic\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1363`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1364`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ProdCharacteristic](/docs/R4B/ComplexTypes/ProdCharacteristic.md)<br/> `http://hl7.org/fhir/StructureDefinition/ProdCharacteristic\|4.3.0` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | 
### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ProdCharacteristic from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | R4 ProdCharacteristic| Relationship | [R4B ProdCharacteristic](/docs/R4B/ComplexTypes/ProdCharacteristic.md)| Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | **`ProdCharacteristic`**| _Equivalent_<br/>(21131/21132)| `ProdCharacteristic`| | | 
| | | | | **`ProdCharacteristic.id`**| _Equivalent_<br/>(21133/21134)| `ProdCharacteristic.id`| | | 
| | | | | **`ProdCharacteristic.extension`**| _Equivalent_<br/>(21135/21136)| `ProdCharacteristic.extension`| | | 
| | | | | **`ProdCharacteristic.modifierExtension`**| _Equivalent_<br/>(21137/21138)| `ProdCharacteristic.modifierExtension`| | | 
| | | | | **`ProdCharacteristic.height`**| _Equivalent_<br/>(21139/21140)| `ProdCharacteristic.height`| | | 
| | | | | **`ProdCharacteristic.width`**| _Equivalent_<br/>(21141/21142)| `ProdCharacteristic.width`| | | 
| | | | | **`ProdCharacteristic.depth`**| _Equivalent_<br/>(21143/21144)| `ProdCharacteristic.depth`| | | 
| | | | | **`ProdCharacteristic.weight`**| _Equivalent_<br/>(21145/21146)| `ProdCharacteristic.weight`| | | 
| | | | | **`ProdCharacteristic.nominalVolume`**| _Equivalent_<br/>(21147/21148)| `ProdCharacteristic.nominalVolume`| | | 
| | | | | **`ProdCharacteristic.externalDiameter`**| _Equivalent_<br/>(21149/21150)| `ProdCharacteristic.externalDiameter`| | | 
| | | | | **`ProdCharacteristic.shape`**| _Equivalent_<br/>(21151/21152)| `ProdCharacteristic.shape`| | | 
| | | | | **`ProdCharacteristic.color`**| _Equivalent_<br/>(21153/21154)| `ProdCharacteristic.color`| | | 
| | | | | **`ProdCharacteristic.imprint`**| _Equivalent_<br/>(21155/21156)| `ProdCharacteristic.imprint`| | | 
| | | | | **`ProdCharacteristic.image`**| _Equivalent_<br/>(21157/21158)| `ProdCharacteristic.image`| | | 
| | | | | **`ProdCharacteristic.scoring`**| _Equivalent_<br/>(21159/21160)| `ProdCharacteristic.scoring`| | | 
| | | | | *15 of 15 elements used* | | *15 of 15 elements used* | | 

