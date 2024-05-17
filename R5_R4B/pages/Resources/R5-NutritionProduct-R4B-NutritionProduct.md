Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | NutritionProduct |  | A food or supplement that is consumed by patients. | 44 | 24 |
| Target | NutritionProduct |  | A food or fluid product that is consumed by patients. | 42 | 22 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 8 |
Equivalent | 4 |
RelatedTo | 32 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| NutritionProduct | NutritionProduct | Equivalent | R5 `NutritionProduct` maps as Equivalent to R4B `NutritionProduct` |
| NutritionProduct.category | NutritionProduct.category | Equivalent | R5 `NutritionProduct.category` maps as Equivalent to R4B `NutritionProduct.category` |
| NutritionProduct.characteristic | - | DoesNotExistInTarget | R5 `NutritionProduct.characteristic` does not appear in the target and has no mapping for `NutritionProduct`. |
| NutritionProduct.characteristic.extension | - | DoesNotExistInTarget | R5 `NutritionProduct.characteristic.extension` does not appear in the target and has no mapping for `NutritionProduct`. |
| NutritionProduct.characteristic.id | - | DoesNotExistInTarget | R5 `NutritionProduct.characteristic.id` does not appear in the target and has no mapping for `NutritionProduct`. |
| NutritionProduct.characteristic.modifierExtension | - | DoesNotExistInTarget | R5 `NutritionProduct.characteristic.modifierExtension` does not appear in the target and has no mapping for `NutritionProduct`. |
| NutritionProduct.characteristic.type | - | DoesNotExistInTarget | R5 `NutritionProduct.characteristic.type` does not appear in the target and has no mapping for `NutritionProduct`. |
| NutritionProduct.characteristic.value[x] | - | DoesNotExistInTarget | R5 `NutritionProduct.characteristic.value[x]` does not appear in the target and has no mapping for `NutritionProduct`. |
| NutritionProduct.code | NutritionProduct.code | Equivalent | R5 `NutritionProduct.code` maps as Equivalent to R4B `NutritionProduct.code` |
| NutritionProduct.contained | NutritionProduct.contained | Equivalent | R5 `NutritionProduct.contained` maps as Equivalent to R4B `NutritionProduct.contained` |
| NutritionProduct.extension | NutritionProduct.extension | SourceIsBroaderThanTarget | R5 `NutritionProduct.extension` maps as SourceIsBroaderThanTarget to R4B `NutritionProduct.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| NutritionProduct.id | NutritionProduct.id | Equivalent | R5 `NutritionProduct.id` maps as Equivalent to R4B `NutritionProduct.id` |
| NutritionProduct.implicitRules | NutritionProduct.implicitRules | Equivalent | R5 `NutritionProduct.implicitRules` maps as Equivalent to R4B `NutritionProduct.implicitRules` |
| NutritionProduct.ingredient | NutritionProduct.ingredient | Equivalent | R5 `NutritionProduct.ingredient` maps as Equivalent to R4B `NutritionProduct.ingredient` |
| NutritionProduct.ingredient.amount | NutritionProduct.ingredient.amount | SourceIsBroaderThanTarget | R5 `NutritionProduct.ingredient.amount` maps as SourceIsBroaderThanTarget to R4B `NutritionProduct.ingredient.amount` - amount has change due to type change: R5 `amount` `Ratio` maps as SourceIsBroaderThanTarget for R4B `amount` |
| NutritionProduct.ingredient.extension | NutritionProduct.ingredient.extension | SourceIsBroaderThanTarget | R5 `NutritionProduct.ingredient.extension` maps as SourceIsBroaderThanTarget to R4B `NutritionProduct.ingredient.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| NutritionProduct.ingredient.id | NutritionProduct.ingredient.id | Equivalent | R5 `NutritionProduct.ingredient.id` maps as Equivalent to R4B `NutritionProduct.ingredient.id` |
| NutritionProduct.ingredient.item | NutritionProduct.ingredient.item | Equivalent | R5 `NutritionProduct.ingredient.item` maps as Equivalent to R4B `NutritionProduct.ingredient.item` |
| NutritionProduct.ingredient.modifierExtension | NutritionProduct.ingredient.modifierExtension | SourceIsBroaderThanTarget | R5 `NutritionProduct.ingredient.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `NutritionProduct.ingredient.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| NutritionProduct.instance | NutritionProduct.instance | RelatedTo | R5 `NutritionProduct.instance` maps as RelatedTo to R4B `NutritionProduct.instance` - instance changed from array to scalar (max cardinality from * to 1) |
| NutritionProduct.instance.biologicalSourceEvent | - | DoesNotExistInTarget | R5 `NutritionProduct.instance.biologicalSourceEvent` does not appear in the target and has no mapping for `NutritionProduct`. |
| NutritionProduct.instance.expiry | NutritionProduct.instance.expiry | Equivalent | R5 `NutritionProduct.instance.expiry` maps as Equivalent to R4B `NutritionProduct.instance.expiry` |
| NutritionProduct.instance.extension | NutritionProduct.instance.extension | SourceIsBroaderThanTarget | R5 `NutritionProduct.instance.extension` maps as SourceIsBroaderThanTarget to R4B `NutritionProduct.instance.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| NutritionProduct.instance.id | NutritionProduct.instance.id | Equivalent | R5 `NutritionProduct.instance.id` maps as Equivalent to R4B `NutritionProduct.instance.id` |
| NutritionProduct.instance.identifier | NutritionProduct.instance.identifier | Equivalent | R5 `NutritionProduct.instance.identifier` maps as Equivalent to R4B `NutritionProduct.instance.identifier` |
| NutritionProduct.instance.lotNumber | NutritionProduct.instance.lotNumber | Equivalent | R5 `NutritionProduct.instance.lotNumber` maps as Equivalent to R4B `NutritionProduct.instance.lotNumber` |
| NutritionProduct.instance.modifierExtension | NutritionProduct.instance.modifierExtension | SourceIsBroaderThanTarget | R5 `NutritionProduct.instance.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `NutritionProduct.instance.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| NutritionProduct.instance.name | - | DoesNotExistInTarget | R5 `NutritionProduct.instance.name` does not appear in the target and has no mapping for `NutritionProduct`. |
| NutritionProduct.instance.quantity | NutritionProduct.instance.quantity | Equivalent | R5 `NutritionProduct.instance.quantity` maps as Equivalent to R4B `NutritionProduct.instance.quantity` |
| NutritionProduct.instance.useBy | NutritionProduct.instance.useBy | Equivalent | R5 `NutritionProduct.instance.useBy` maps as Equivalent to R4B `NutritionProduct.instance.useBy` |
| NutritionProduct.knownAllergen | NutritionProduct.knownAllergen | Equivalent | R5 `NutritionProduct.knownAllergen` maps as Equivalent to R4B `NutritionProduct.knownAllergen` |
| NutritionProduct.language | NutritionProduct.language | RelatedTo | R5 `NutritionProduct.language` maps as RelatedTo to R4B `NutritionProduct.language` - language changed the binding strength from Required to Preferred |
| NutritionProduct.manufacturer | NutritionProduct.manufacturer | Equivalent | R5 `NutritionProduct.manufacturer` maps as Equivalent to R4B `NutritionProduct.manufacturer` |
| NutritionProduct.meta | NutritionProduct.meta | Equivalent | R5 `NutritionProduct.meta` maps as Equivalent to R4B `NutritionProduct.meta` |
| NutritionProduct.modifierExtension | NutritionProduct.modifierExtension | SourceIsBroaderThanTarget | R5 `NutritionProduct.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `NutritionProduct.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| NutritionProduct.note | NutritionProduct.note | SourceIsBroaderThanTarget | R5 `NutritionProduct.note` maps as SourceIsBroaderThanTarget to R4B `NutritionProduct.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| NutritionProduct.nutrient | NutritionProduct.nutrient | Equivalent | R5 `NutritionProduct.nutrient` maps as Equivalent to R4B `NutritionProduct.nutrient` |
| NutritionProduct.nutrient.amount | NutritionProduct.nutrient.amount | SourceIsBroaderThanTarget | R5 `NutritionProduct.nutrient.amount` maps as SourceIsBroaderThanTarget to R4B `NutritionProduct.nutrient.amount` - amount has change due to type change: R5 `amount` `Ratio` maps as SourceIsBroaderThanTarget for R4B `amount` |
| NutritionProduct.nutrient.extension | NutritionProduct.nutrient.extension | SourceIsBroaderThanTarget | R5 `NutritionProduct.nutrient.extension` maps as SourceIsBroaderThanTarget to R4B `NutritionProduct.nutrient.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| NutritionProduct.nutrient.id | NutritionProduct.nutrient.id | Equivalent | R5 `NutritionProduct.nutrient.id` maps as Equivalent to R4B `NutritionProduct.nutrient.id` |
| NutritionProduct.nutrient.item | NutritionProduct.nutrient.item | Equivalent | R5 `NutritionProduct.nutrient.item` maps as Equivalent to R4B `NutritionProduct.nutrient.item` |
| NutritionProduct.nutrient.modifierExtension | NutritionProduct.nutrient.modifierExtension | SourceIsBroaderThanTarget | R5 `NutritionProduct.nutrient.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `NutritionProduct.nutrient.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| NutritionProduct.status | NutritionProduct.status | Equivalent | R5 `NutritionProduct.status` maps as Equivalent to R4B `NutritionProduct.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/nutritionproduct-status|5.0.0 and http://hl7.org/fhir/ValueSet/nutritionproduct-status|4.3.0 (Equivalent) |
| NutritionProduct.text | NutritionProduct.text | Equivalent | R5 `NutritionProduct.text` maps as Equivalent to R4B `NutritionProduct.text` |

