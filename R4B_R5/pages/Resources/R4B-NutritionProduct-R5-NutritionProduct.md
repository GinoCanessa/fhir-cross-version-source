Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | NutritionProduct |  | A food or fluid product that is consumed by patients. | 42 | 22 |
| Target | NutritionProduct |  | A food or supplement that is consumed by patients. | 44 | 24 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 6 |
Equivalent | 4 |
RelatedTo | 32 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| NutritionProduct | NutritionProduct | Equivalent | R4B `NutritionProduct` maps as Equivalent to R5 `NutritionProduct` |
| NutritionProduct.category | NutritionProduct.category | Equivalent | R4B `NutritionProduct.category` maps as Equivalent to R5 `NutritionProduct.category` |
| NutritionProduct.code | NutritionProduct.code | Equivalent | R4B `NutritionProduct.code` maps as Equivalent to R5 `NutritionProduct.code` |
| NutritionProduct.contained | NutritionProduct.contained | Equivalent | R4B `NutritionProduct.contained` maps as Equivalent to R5 `NutritionProduct.contained` |
| NutritionProduct.extension | NutritionProduct.extension | RelatedTo | R4B `NutritionProduct.extension` maps as RelatedTo to R5 `NutritionProduct.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| NutritionProduct.id | NutritionProduct.id | Equivalent | R4B `NutritionProduct.id` maps as Equivalent to R5 `NutritionProduct.id` |
| NutritionProduct.implicitRules | NutritionProduct.implicitRules | Equivalent | R4B `NutritionProduct.implicitRules` maps as Equivalent to R5 `NutritionProduct.implicitRules` |
| NutritionProduct.ingredient | NutritionProduct.ingredient | Equivalent | R4B `NutritionProduct.ingredient` maps as Equivalent to R5 `NutritionProduct.ingredient` |
| NutritionProduct.ingredient.amount | NutritionProduct.ingredient.amount | SourceIsNarrowerThanTarget | R4B `NutritionProduct.ingredient.amount` maps as SourceIsNarrowerThanTarget to R5 `NutritionProduct.ingredient.amount` - amount has change due to type change: R4B `amount` `Ratio` maps as SourceIsNarrowerThanTarget for R5 `amount` |
| NutritionProduct.ingredient.extension | NutritionProduct.ingredient.extension | RelatedTo | R4B `NutritionProduct.ingredient.extension` maps as RelatedTo to R5 `NutritionProduct.ingredient.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| NutritionProduct.ingredient.id | NutritionProduct.ingredient.id | Equivalent | R4B `NutritionProduct.ingredient.id` maps as Equivalent to R5 `NutritionProduct.ingredient.id` |
| NutritionProduct.ingredient.item | NutritionProduct.ingredient.item | Equivalent | R4B `NutritionProduct.ingredient.item` maps as Equivalent to R5 `NutritionProduct.ingredient.item` |
| NutritionProduct.ingredient.modifierExtension | NutritionProduct.ingredient.modifierExtension | RelatedTo | R4B `NutritionProduct.ingredient.modifierExtension` maps as RelatedTo to R5 `NutritionProduct.ingredient.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| NutritionProduct.instance | NutritionProduct.instance | RelatedTo | R4B `NutritionProduct.instance` maps as RelatedTo to R5 `NutritionProduct.instance` - instance changed from scalar to array (max cardinality from 1 to *) |
| NutritionProduct.instance.expiry | NutritionProduct.instance.expiry | Equivalent | R4B `NutritionProduct.instance.expiry` maps as Equivalent to R5 `NutritionProduct.instance.expiry` |
| NutritionProduct.instance.extension | NutritionProduct.instance.extension | RelatedTo | R4B `NutritionProduct.instance.extension` maps as RelatedTo to R5 `NutritionProduct.instance.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| NutritionProduct.instance.id | NutritionProduct.instance.id | Equivalent | R4B `NutritionProduct.instance.id` maps as Equivalent to R5 `NutritionProduct.instance.id` |
| NutritionProduct.instance.identifier | NutritionProduct.instance.identifier | Equivalent | R4B `NutritionProduct.instance.identifier` maps as Equivalent to R5 `NutritionProduct.instance.identifier` |
| NutritionProduct.instance.lotNumber | NutritionProduct.instance.lotNumber | Equivalent | R4B `NutritionProduct.instance.lotNumber` maps as Equivalent to R5 `NutritionProduct.instance.lotNumber` |
| NutritionProduct.instance.modifierExtension | NutritionProduct.instance.modifierExtension | RelatedTo | R4B `NutritionProduct.instance.modifierExtension` maps as RelatedTo to R5 `NutritionProduct.instance.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| NutritionProduct.instance.quantity | NutritionProduct.instance.quantity | Equivalent | R4B `NutritionProduct.instance.quantity` maps as Equivalent to R5 `NutritionProduct.instance.quantity` |
| NutritionProduct.instance.useBy | NutritionProduct.instance.useBy | Equivalent | R4B `NutritionProduct.instance.useBy` maps as Equivalent to R5 `NutritionProduct.instance.useBy` |
| NutritionProduct.knownAllergen | NutritionProduct.knownAllergen | Equivalent | R4B `NutritionProduct.knownAllergen` maps as Equivalent to R5 `NutritionProduct.knownAllergen` |
| NutritionProduct.language | NutritionProduct.language | RelatedTo | R4B `NutritionProduct.language` maps as RelatedTo to R5 `NutritionProduct.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| NutritionProduct.manufacturer | NutritionProduct.manufacturer | Equivalent | R4B `NutritionProduct.manufacturer` maps as Equivalent to R5 `NutritionProduct.manufacturer` |
| NutritionProduct.meta | NutritionProduct.meta | Equivalent | R4B `NutritionProduct.meta` maps as Equivalent to R5 `NutritionProduct.meta` |
| NutritionProduct.modifierExtension | NutritionProduct.modifierExtension | RelatedTo | R4B `NutritionProduct.modifierExtension` maps as RelatedTo to R5 `NutritionProduct.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| NutritionProduct.note | NutritionProduct.note | SourceIsNarrowerThanTarget | R4B `NutritionProduct.note` maps as SourceIsNarrowerThanTarget to R5 `NutritionProduct.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| NutritionProduct.nutrient | NutritionProduct.nutrient | Equivalent | R4B `NutritionProduct.nutrient` maps as Equivalent to R5 `NutritionProduct.nutrient` |
| NutritionProduct.nutrient.amount | NutritionProduct.nutrient.amount | SourceIsNarrowerThanTarget | R4B `NutritionProduct.nutrient.amount` maps as SourceIsNarrowerThanTarget to R5 `NutritionProduct.nutrient.amount` - amount has change due to type change: R4B `amount` `Ratio` maps as SourceIsNarrowerThanTarget for R5 `amount` |
| NutritionProduct.nutrient.extension | NutritionProduct.nutrient.extension | RelatedTo | R4B `NutritionProduct.nutrient.extension` maps as RelatedTo to R5 `NutritionProduct.nutrient.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| NutritionProduct.nutrient.id | NutritionProduct.nutrient.id | Equivalent | R4B `NutritionProduct.nutrient.id` maps as Equivalent to R5 `NutritionProduct.nutrient.id` |
| NutritionProduct.nutrient.item | NutritionProduct.nutrient.item | Equivalent | R4B `NutritionProduct.nutrient.item` maps as Equivalent to R5 `NutritionProduct.nutrient.item` |
| NutritionProduct.nutrient.modifierExtension | NutritionProduct.nutrient.modifierExtension | RelatedTo | R4B `NutritionProduct.nutrient.modifierExtension` maps as RelatedTo to R5 `NutritionProduct.nutrient.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| NutritionProduct.productCharacteristic | - | DoesNotExistInTarget | R4B `NutritionProduct.productCharacteristic` does not appear in the target and has no mapping for `NutritionProduct`. |
| NutritionProduct.productCharacteristic.extension | - | DoesNotExistInTarget | R4B `NutritionProduct.productCharacteristic.extension` does not appear in the target and has no mapping for `NutritionProduct`. |
| NutritionProduct.productCharacteristic.id | - | DoesNotExistInTarget | R4B `NutritionProduct.productCharacteristic.id` does not appear in the target and has no mapping for `NutritionProduct`. |
| NutritionProduct.productCharacteristic.modifierExtension | - | DoesNotExistInTarget | R4B `NutritionProduct.productCharacteristic.modifierExtension` does not appear in the target and has no mapping for `NutritionProduct`. |
| NutritionProduct.productCharacteristic.type | - | DoesNotExistInTarget | R4B `NutritionProduct.productCharacteristic.type` does not appear in the target and has no mapping for `NutritionProduct`. |
| NutritionProduct.productCharacteristic.value[x] | - | DoesNotExistInTarget | R4B `NutritionProduct.productCharacteristic.value[x]` does not appear in the target and has no mapping for `NutritionProduct`. |
| NutritionProduct.status | NutritionProduct.status | Equivalent | R4B `NutritionProduct.status` maps as Equivalent to R5 `NutritionProduct.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/nutritionproduct-status|4.3.0 and http://hl7.org/fhir/ValueSet/nutritionproduct-status|5.0.0 (Equivalent) |
| NutritionProduct.text | NutritionProduct.text | Equivalent | R4B `NutritionProduct.text` maps as Equivalent to R5 `NutritionProduct.text` |

