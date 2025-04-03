Comparison of 
Generated at Thursday, April 3, 2025 8:18:25 AM

### NutritionProduct

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | NutritionProduct |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/NutritionProduct` |
| Version | 4.3.0 |
| Description | A food or fluid product that is consumed by patients. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1730` |
| Database Snapshot Count | `42` |
| Database Differential Count | `22` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `NutritionProduct` | `NutritionProduct` | `NutritionProduct` | NutritionProduct | A product used for nutritional purposes | 0..* | NutritionProduct |  |  |
| `NutritionProduct.category` | `NutritionProduct.category` | `category` | NutritionProduct.category | A category or class of the nutrition product (halal, kosher, gluten free, vegan, etc) | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/nutrition-product-category` |
| `NutritionProduct.code` | `NutritionProduct.code` | `code` | NutritionProduct.code | A code designating a specific type of nutritional product | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/edible-substance-type` |
| `NutritionProduct.contained` | `NutritionProduct.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `NutritionProduct.extension` | `NutritionProduct.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `NutritionProduct.id` | `NutritionProduct.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `NutritionProduct.implicitRules` | `NutritionProduct.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `NutritionProduct.ingredient` | `NutritionProduct.ingredient` | `ingredient` | NutritionProduct.ingredient | Ingredients contained in this product | 0..* | BackboneElement |  |  |
| `NutritionProduct.ingredient.amount` | `NutritionProduct.ingredient.amount` | `amount` | NutritionProduct.ingredient.amount | The amount of ingredient that is in the product | 0..* | Ratio |  |  |
| `NutritionProduct.ingredient.extension` | `NutritionProduct.ingredient.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `NutritionProduct.ingredient.id` | `NutritionProduct.ingredient.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `NutritionProduct.ingredient.item` | `NutritionProduct.ingredient.item` | `item` | NutritionProduct.ingredient.item | The ingredient contained in the product | 1..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/NutritionProduct) |  |  |
| `NutritionProduct.ingredient.modifierExtension` | `NutritionProduct.ingredient.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `NutritionProduct.instance` | `NutritionProduct.instance` | `instance` | NutritionProduct.instance | One or several physical instances or occurrences of the nutrition product | 0..1 | BackboneElement |  |  |
| `NutritionProduct.instance.expiry` | `NutritionProduct.instance.expiry` | `expiry` | NutritionProduct.instance.expiry | The expiry date or date and time for the product | 0..1 | dateTime |  |  |
| `NutritionProduct.instance.extension` | `NutritionProduct.instance.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `NutritionProduct.instance.id` | `NutritionProduct.instance.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `NutritionProduct.instance.identifier` | `NutritionProduct.instance.identifier` | `identifier` | NutritionProduct.instance.identifier | The identifier for the physical instance, typically a serial number | 0..* | Identifier |  |  |
| `NutritionProduct.instance.lotNumber` | `NutritionProduct.instance.lotNumber` | `lotNumber` | NutritionProduct.instance.lotNumber | The identification of the batch or lot of the product | 0..1 | string |  |  |
| `NutritionProduct.instance.modifierExtension` | `NutritionProduct.instance.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `NutritionProduct.instance.quantity` | `NutritionProduct.instance.quantity` | `quantity` | NutritionProduct.instance.quantity | The amount of items or instances | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `NutritionProduct.instance.useBy` | `NutritionProduct.instance.useBy` | `useBy` | NutritionProduct.instance.useBy | The date until which the product is expected to be good for consumption | 0..1 | dateTime |  |  |
| `NutritionProduct.knownAllergen` | `NutritionProduct.knownAllergen` | `knownAllergen` | NutritionProduct.knownAllergen | Known or suspected allergens that are a part of this product | 0..* | CodeableReference(http://hl7.org/fhir/StructureDefinition/Substance) | `Example` | `http://hl7.org/fhir/ValueSet/allergen-class` |
| `NutritionProduct.language` | `NutritionProduct.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `NutritionProduct.manufacturer` | `NutritionProduct.manufacturer` | `manufacturer` | NutritionProduct.manufacturer | Manufacturer, representative or officially responsible for the product | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `NutritionProduct.meta` | `NutritionProduct.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `NutritionProduct.modifierExtension` | `NutritionProduct.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `NutritionProduct.note` | `NutritionProduct.note` | `note` | NutritionProduct.note | Comments made about the product | 0..* | Annotation |  |  |
| `NutritionProduct.nutrient` | `NutritionProduct.nutrient` | `nutrient` | NutritionProduct.nutrient | The product's nutritional information expressed by the nutrients | 0..* | BackboneElement |  |  |
| `NutritionProduct.nutrient.amount` | `NutritionProduct.nutrient.amount` | `amount` | NutritionProduct.nutrient.amount | The amount of nutrient expressed in one or more units: X per pack / per serving / per dose | 0..* | Ratio |  |  |
| `NutritionProduct.nutrient.extension` | `NutritionProduct.nutrient.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `NutritionProduct.nutrient.id` | `NutritionProduct.nutrient.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `NutritionProduct.nutrient.item` | `NutritionProduct.nutrient.item` | `item` | NutritionProduct.nutrient.item | The (relevant) nutrients in the product | 0..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/Substance) | `Example` | `http://hl7.org/fhir/ValueSet/nutrition-product-nutrient` |
| `NutritionProduct.nutrient.modifierExtension` | `NutritionProduct.nutrient.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `NutritionProduct.productCharacteristic` | `NutritionProduct.productCharacteristic` | `productCharacteristic` | NutritionProduct.productCharacteristic | Specifies descriptive properties of the nutrition product | 0..* | BackboneElement |  |  |
| `NutritionProduct.productCharacteristic.extension` | `NutritionProduct.productCharacteristic.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `NutritionProduct.productCharacteristic.id` | `NutritionProduct.productCharacteristic.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `NutritionProduct.productCharacteristic.modifierExtension` | `NutritionProduct.productCharacteristic.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `NutritionProduct.productCharacteristic.type` | `NutritionProduct.productCharacteristic.type` | `type` | NutritionProduct.productCharacteristic.type | Code specifying the type of characteristic | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/measurement-property` |
| `NutritionProduct.productCharacteristic.value[x]` | `NutritionProduct.productCharacteristic.value[x]` | `value[x]` | NutritionProduct.productCharacteristic.value[x] | The value of the characteristic | 1..1 | Attachment, base64Binary, boolean, CodeableConcept, Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity], string |  |  |
| `NutritionProduct.status` | `NutritionProduct.status` | `status` | NutritionProduct.status | active \| inactive \| entered-in-error | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/nutritionproduct-status|4.3.0` |
| `NutritionProduct.text` | `NutritionProduct.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [NutritionProduct](/docs/R4B/Resources/NutritionProduct.md)<br/> `http://hl7.org/fhir/StructureDefinition/NutritionProduct\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1014`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1243`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [NutritionProduct](/docs/R5/Resources/NutritionProduct.md)<br/> `http://hl7.org/fhir/StructureDefinition/NutritionProduct\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition NutritionProduct from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | R4B NutritionProduct| Relationship | [R5 NutritionProduct](/docs/R5/Resources/NutritionProduct.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | **`NutritionProduct`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(45370)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(45371)| `NutritionProduct`
| | | | | | | **`NutritionProduct.id`**| _Equivalent_<br/>(45372/45373)| `NutritionProduct.id`
| | | | | | | **`NutritionProduct.meta`**| _Equivalent_<br/>(45374/45375)| `NutritionProduct.meta`
| | | | | | | **`NutritionProduct.implicitRules`**| _Equivalent_<br/>(45376/45377)| `NutritionProduct.implicitRules`
| | | | | | | **`NutritionProduct.language`**| _Equivalent_<br/>(45378/45379)| `NutritionProduct.language`
| | | | | | | **`NutritionProduct.text`**| _Equivalent_<br/>(45380/45381)| `NutritionProduct.text`
| | | | | | | **`NutritionProduct.contained`**| _Equivalent_<br/>(45382/45383)| `NutritionProduct.contained`
| | | | | | | **`NutritionProduct.extension`**| _Equivalent_<br/>(45384/45385)| `NutritionProduct.extension`
| | | | | | | **`NutritionProduct.modifierExtension`**| _Equivalent_<br/>(45386/45387)| `NutritionProduct.modifierExtension`
| | | | | | | **`NutritionProduct.status`**| _Equivalent_<br/>(45388/45389)| `NutritionProduct.status`
| | | | | | | **`NutritionProduct.category`**| _Equivalent_<br/>(45390/45391)| `NutritionProduct.category`
| | | | | | | **`NutritionProduct.code`**| _Equivalent_<br/>(45392/45393)| `NutritionProduct.code`
| | | | | | | **`NutritionProduct.manufacturer`**| _Equivalent_<br/>(45394/45395)| `NutritionProduct.manufacturer`
| | | | | | | **`NutritionProduct.nutrient`**| _Equivalent_<br/>(45396/45397)| `NutritionProduct.nutrient`
| | | | | | | **`NutritionProduct.nutrient.id`**| _Equivalent_<br/>(45398/45399)| `NutritionProduct.nutrient.id`
| | | | | | | **`NutritionProduct.nutrient.extension`**| _Equivalent_<br/>(45400/45401)| `NutritionProduct.nutrient.extension`
| | | | | | | **`NutritionProduct.nutrient.modifierExtension`**| _Equivalent_<br/>(45402/45403)| `NutritionProduct.nutrient.modifierExtension`
| | | | | | | **`NutritionProduct.nutrient.item`**| _Equivalent_<br/>(45404/45405)| `NutritionProduct.nutrient.item`
| | | | | | | **`NutritionProduct.nutrient.amount`**| _Equivalent_<br/>(45406/45407)| `NutritionProduct.nutrient.amount`
| | | | | | | **`NutritionProduct.ingredient`**| _Equivalent_<br/>(45408/45409)| `NutritionProduct.ingredient`
| | | | | | | **`NutritionProduct.ingredient.id`**| _Equivalent_<br/>(45410/45411)| `NutritionProduct.ingredient.id`
| | | | | | | **`NutritionProduct.ingredient.extension`**| _Equivalent_<br/>(45412/45413)| `NutritionProduct.ingredient.extension`
| | | | | | | **`NutritionProduct.ingredient.modifierExtension`**| _Equivalent_<br/>(45414/45415)| `NutritionProduct.ingredient.modifierExtension`
| | | | | | | **`NutritionProduct.ingredient.item`**| _Equivalent_<br/>(45416/45417)| `NutritionProduct.ingredient.item`
| | | | | | | **`NutritionProduct.ingredient.amount`**| _Equivalent_<br/>(45418/45419)| `NutritionProduct.ingredient.amount`
| | | | | | | **`NutritionProduct.knownAllergen`**| _Equivalent_<br/>(45420/45421)| `NutritionProduct.knownAllergen`
| | | | | | | **`NutritionProduct.productCharacteristic`**| | | 
| | | | | | | **`NutritionProduct.productCharacteristic.id`**| | | 
| | | | | | | **`NutritionProduct.productCharacteristic.extension`**| | | 
| | | | | | | **`NutritionProduct.productCharacteristic.modifierExtension`**| | | 
| | | | | | | **`NutritionProduct.productCharacteristic.type`**| | | 
| | | | | | | **`NutritionProduct.productCharacteristic.value[x]`**| | | 
| | | | | | | **`NutritionProduct.instance`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(45428)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(45429)| `NutritionProduct.instance`
| | | | | | | **`NutritionProduct.instance.id`**| _Equivalent_<br/>(45430/45431)| `NutritionProduct.instance.id`
| | | | | | | **`NutritionProduct.instance.extension`**| _Equivalent_<br/>(45432/45433)| `NutritionProduct.instance.extension`
| | | | | | | **`NutritionProduct.instance.modifierExtension`**| _Equivalent_<br/>(45434/45435)| `NutritionProduct.instance.modifierExtension`
| | | | | | | **`NutritionProduct.instance.quantity`**| _Equivalent_<br/>(45436/45437)| `NutritionProduct.instance.quantity`
| | | | | | | **`NutritionProduct.instance.identifier`**| _Equivalent_<br/>(45438/45439)| `NutritionProduct.instance.identifier`
| | | | | | | **`NutritionProduct.instance.lotNumber`**| _Equivalent_<br/>(45440/45441)| `NutritionProduct.instance.lotNumber`
| | | | | | | **`NutritionProduct.instance.expiry`**| _Equivalent_<br/>(45442/45443)| `NutritionProduct.instance.expiry`
| | | | | | | **`NutritionProduct.instance.useBy`**| _Equivalent_<br/>(45444/45445)| `NutritionProduct.instance.useBy`
| | | | | | | **`NutritionProduct.note`**| _Equivalent_<br/>(45446/45447)| `NutritionProduct.note`
| | | | | | | *42 of 42 elements used* | | *36 of 44 elements used* <br/>remaining elements:<br/>`NutritionProduct.characteristic`, `NutritionProduct.characteristic.extension`, `NutritionProduct.characteristic.id`, `NutritionProduct.characteristic.modifierExtension`, `NutritionProduct.characteristic.type`, `NutritionProduct.characteristic.value[x]`, `NutritionProduct.instance.biologicalSourceEvent`, `NutritionProduct.instance.name`

