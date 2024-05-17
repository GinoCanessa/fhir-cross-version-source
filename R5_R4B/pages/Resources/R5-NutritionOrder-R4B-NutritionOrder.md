Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | NutritionOrder |  | A request to supply a diet, formula feeding (enteral) or oral nutritional supplement to a patient/resident. | 101 | 63 |
| Target | NutritionOrder |  | A request to supply a diet, formula feeding (enteral) or oral nutritional supplement to a patient/resident. | 71 | 45 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 34 |
Equivalent | 4 |
RelatedTo | 63 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| NutritionOrder | NutritionOrder | Equivalent | R5 `NutritionOrder` maps as Equivalent to R4B `NutritionOrder` |
| NutritionOrder.allergyIntolerance | NutritionOrder.allergyIntolerance | Equivalent | R5 `NutritionOrder.allergyIntolerance` maps as Equivalent to R4B `NutritionOrder.allergyIntolerance` |
| NutritionOrder.basedOn | - | DoesNotExistInTarget | R5 `NutritionOrder.basedOn` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.contained | NutritionOrder.contained | Equivalent | R5 `NutritionOrder.contained` maps as Equivalent to R4B `NutritionOrder.contained` |
| NutritionOrder.dateTime | NutritionOrder.dateTime | Equivalent | R5 `NutritionOrder.dateTime` maps as Equivalent to R4B `NutritionOrder.dateTime` |
| NutritionOrder.encounter | NutritionOrder.encounter | Equivalent | R5 `NutritionOrder.encounter` maps as Equivalent to R4B `NutritionOrder.encounter` |
| NutritionOrder.enteralFormula | NutritionOrder.enteralFormula | Equivalent | R5 `NutritionOrder.enteralFormula` maps as Equivalent to R4B `NutritionOrder.enteralFormula` |
| NutritionOrder.enteralFormula.additive | - | DoesNotExistInTarget | R5 `NutritionOrder.enteralFormula.additive` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.enteralFormula.additive.extension | - | DoesNotExistInTarget | R5 `NutritionOrder.enteralFormula.additive.extension` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.enteralFormula.additive.id | - | DoesNotExistInTarget | R5 `NutritionOrder.enteralFormula.additive.id` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.enteralFormula.additive.modifierExtension | - | DoesNotExistInTarget | R5 `NutritionOrder.enteralFormula.additive.modifierExtension` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.enteralFormula.additive.productName | - | DoesNotExistInTarget | R5 `NutritionOrder.enteralFormula.additive.productName` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.enteralFormula.additive.quantity | - | DoesNotExistInTarget | R5 `NutritionOrder.enteralFormula.additive.quantity` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.enteralFormula.additive.type | - | DoesNotExistInTarget | R5 `NutritionOrder.enteralFormula.additive.type` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.enteralFormula.administration | NutritionOrder.enteralFormula.administration | Equivalent | R5 `NutritionOrder.enteralFormula.administration` maps as Equivalent to R4B `NutritionOrder.enteralFormula.administration` |
| NutritionOrder.enteralFormula.administration.extension | NutritionOrder.enteralFormula.administration.extension | SourceIsBroaderThanTarget | R5 `NutritionOrder.enteralFormula.administration.extension` maps as SourceIsBroaderThanTarget to R4B `NutritionOrder.enteralFormula.administration.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| NutritionOrder.enteralFormula.administration.id | NutritionOrder.enteralFormula.administration.id | Equivalent | R5 `NutritionOrder.enteralFormula.administration.id` maps as Equivalent to R4B `NutritionOrder.enteralFormula.administration.id` |
| NutritionOrder.enteralFormula.administration.modifierExtension | NutritionOrder.enteralFormula.administration.modifierExtension | SourceIsBroaderThanTarget | R5 `NutritionOrder.enteralFormula.administration.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `NutritionOrder.enteralFormula.administration.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| NutritionOrder.enteralFormula.administration.quantity | NutritionOrder.enteralFormula.administration.quantity | Equivalent | R5 `NutritionOrder.enteralFormula.administration.quantity` maps as Equivalent to R4B `NutritionOrder.enteralFormula.administration.quantity` |
| NutritionOrder.enteralFormula.administration.rate[x] | NutritionOrder.enteralFormula.administration.rate[x] | SourceIsBroaderThanTarget | R5 `NutritionOrder.enteralFormula.administration.rate[x]` maps as SourceIsBroaderThanTarget to R4B `NutritionOrder.enteralFormula.administration.rate[x]` - rate[x] has change due to type change: R5 `rate[x]` `Ratio` maps as SourceIsBroaderThanTarget for R4B `rate[x]` |
| NutritionOrder.enteralFormula.administration.schedule | NutritionOrder.enteralFormula.administration.schedule | SourceIsBroaderThanTarget | R5 `NutritionOrder.enteralFormula.administration.schedule` maps as SourceIsBroaderThanTarget to R4B `NutritionOrder.enteralFormula.administration.schedule` - schedule has change due to type change: R5 schedule BackboneElement has no equivalent or mapped type in R4B schedule |
| NutritionOrder.enteralFormula.administration.schedule.asNeeded | - | DoesNotExistInTarget | R5 `NutritionOrder.enteralFormula.administration.schedule.asNeeded` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.enteralFormula.administration.schedule.asNeededFor | - | DoesNotExistInTarget | R5 `NutritionOrder.enteralFormula.administration.schedule.asNeededFor` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.enteralFormula.administration.schedule.extension | - | DoesNotExistInTarget | R5 `NutritionOrder.enteralFormula.administration.schedule.extension` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.enteralFormula.administration.schedule.id | - | DoesNotExistInTarget | R5 `NutritionOrder.enteralFormula.administration.schedule.id` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.enteralFormula.administration.schedule.modifierExtension | - | DoesNotExistInTarget | R5 `NutritionOrder.enteralFormula.administration.schedule.modifierExtension` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.enteralFormula.administration.schedule.timing | - | DoesNotExistInTarget | R5 `NutritionOrder.enteralFormula.administration.schedule.timing` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.enteralFormula.administrationInstruction | NutritionOrder.enteralFormula.administrationInstruction | SourceIsBroaderThanTarget | R5 `NutritionOrder.enteralFormula.administrationInstruction` maps as SourceIsBroaderThanTarget to R4B `NutritionOrder.enteralFormula.administrationInstruction` - administrationInstruction has change due to type change: R5 administrationInstruction markdown has no equivalent or mapped type in R4B administrationInstruction |
| NutritionOrder.enteralFormula.baseFormulaProductName | NutritionOrder.enteralFormula.baseFormulaProductName | Equivalent | R5 `NutritionOrder.enteralFormula.baseFormulaProductName` maps as Equivalent to R4B `NutritionOrder.enteralFormula.baseFormulaProductName` |
| NutritionOrder.enteralFormula.baseFormulaType | NutritionOrder.enteralFormula.baseFormulaType | SourceIsBroaderThanTarget | R5 `NutritionOrder.enteralFormula.baseFormulaType` maps as SourceIsBroaderThanTarget to R4B `NutritionOrder.enteralFormula.baseFormulaType` - baseFormulaType has change due to type change: R5 baseFormulaType CodeableReference has no equivalent or mapped type in R4B baseFormulaType |
| NutritionOrder.enteralFormula.caloricDensity | NutritionOrder.enteralFormula.caloricDensity | Equivalent | R5 `NutritionOrder.enteralFormula.caloricDensity` maps as Equivalent to R4B `NutritionOrder.enteralFormula.caloricDensity` |
| NutritionOrder.enteralFormula.deliveryDevice | - | DoesNotExistInTarget | R5 `NutritionOrder.enteralFormula.deliveryDevice` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.enteralFormula.extension | NutritionOrder.enteralFormula.extension | SourceIsBroaderThanTarget | R5 `NutritionOrder.enteralFormula.extension` maps as SourceIsBroaderThanTarget to R4B `NutritionOrder.enteralFormula.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| NutritionOrder.enteralFormula.id | NutritionOrder.enteralFormula.id | Equivalent | R5 `NutritionOrder.enteralFormula.id` maps as Equivalent to R4B `NutritionOrder.enteralFormula.id` |
| NutritionOrder.enteralFormula.maxVolumeToDeliver | NutritionOrder.enteralFormula.maxVolumeToDeliver | Equivalent | R5 `NutritionOrder.enteralFormula.maxVolumeToDeliver` maps as Equivalent to R4B `NutritionOrder.enteralFormula.maxVolumeToDeliver` |
| NutritionOrder.enteralFormula.modifierExtension | NutritionOrder.enteralFormula.modifierExtension | SourceIsBroaderThanTarget | R5 `NutritionOrder.enteralFormula.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `NutritionOrder.enteralFormula.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| NutritionOrder.enteralFormula.routeOfAdministration | - | DoesNotExistInTarget | R5 `NutritionOrder.enteralFormula.routeOfAdministration` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.excludeFoodModifier | NutritionOrder.excludeFoodModifier | Equivalent | R5 `NutritionOrder.excludeFoodModifier` maps as Equivalent to R4B `NutritionOrder.excludeFoodModifier` |
| NutritionOrder.extension | NutritionOrder.extension | SourceIsBroaderThanTarget | R5 `NutritionOrder.extension` maps as SourceIsBroaderThanTarget to R4B `NutritionOrder.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| NutritionOrder.foodPreferenceModifier | NutritionOrder.foodPreferenceModifier | Equivalent | R5 `NutritionOrder.foodPreferenceModifier` maps as Equivalent to R4B `NutritionOrder.foodPreferenceModifier` |
| NutritionOrder.groupIdentifier | - | DoesNotExistInTarget | R5 `NutritionOrder.groupIdentifier` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.id | NutritionOrder.id | Equivalent | R5 `NutritionOrder.id` maps as Equivalent to R4B `NutritionOrder.id` |
| NutritionOrder.identifier | NutritionOrder.identifier | Equivalent | R5 `NutritionOrder.identifier` maps as Equivalent to R4B `NutritionOrder.identifier` |
| NutritionOrder.implicitRules | NutritionOrder.implicitRules | Equivalent | R5 `NutritionOrder.implicitRules` maps as Equivalent to R4B `NutritionOrder.implicitRules` |
| NutritionOrder.instantiates | NutritionOrder.instantiates | Equivalent | R5 `NutritionOrder.instantiates` maps as Equivalent to R4B `NutritionOrder.instantiates` |
| NutritionOrder.instantiatesCanonical | NutritionOrder.instantiatesCanonical | Equivalent | R5 `NutritionOrder.instantiatesCanonical` maps as Equivalent to R4B `NutritionOrder.instantiatesCanonical` |
| NutritionOrder.instantiatesUri | NutritionOrder.instantiatesUri | Equivalent | R5 `NutritionOrder.instantiatesUri` maps as Equivalent to R4B `NutritionOrder.instantiatesUri` |
| NutritionOrder.intent | NutritionOrder.intent | Equivalent | R5 `NutritionOrder.intent` maps as Equivalent to R4B `NutritionOrder.intent` - intent has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-intent|5.0.0 and http://hl7.org/fhir/ValueSet/request-intent|4.3.0 (Equivalent) |
| NutritionOrder.language | NutritionOrder.language | RelatedTo | R5 `NutritionOrder.language` maps as RelatedTo to R4B `NutritionOrder.language` - language changed the binding strength from Required to Preferred |
| NutritionOrder.meta | NutritionOrder.meta | Equivalent | R5 `NutritionOrder.meta` maps as Equivalent to R4B `NutritionOrder.meta` |
| NutritionOrder.modifierExtension | NutritionOrder.modifierExtension | SourceIsBroaderThanTarget | R5 `NutritionOrder.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `NutritionOrder.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| NutritionOrder.note | NutritionOrder.note | SourceIsBroaderThanTarget | R5 `NutritionOrder.note` maps as SourceIsBroaderThanTarget to R4B `NutritionOrder.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| NutritionOrder.oralDiet | NutritionOrder.oralDiet | Equivalent | R5 `NutritionOrder.oralDiet` maps as Equivalent to R4B `NutritionOrder.oralDiet` |
| NutritionOrder.oralDiet.extension | NutritionOrder.oralDiet.extension | SourceIsBroaderThanTarget | R5 `NutritionOrder.oralDiet.extension` maps as SourceIsBroaderThanTarget to R4B `NutritionOrder.oralDiet.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| NutritionOrder.oralDiet.fluidConsistencyType | NutritionOrder.oralDiet.fluidConsistencyType | Equivalent | R5 `NutritionOrder.oralDiet.fluidConsistencyType` maps as Equivalent to R4B `NutritionOrder.oralDiet.fluidConsistencyType` |
| NutritionOrder.oralDiet.id | NutritionOrder.oralDiet.id | Equivalent | R5 `NutritionOrder.oralDiet.id` maps as Equivalent to R4B `NutritionOrder.oralDiet.id` |
| NutritionOrder.oralDiet.instruction | NutritionOrder.oralDiet.instruction | Equivalent | R5 `NutritionOrder.oralDiet.instruction` maps as Equivalent to R4B `NutritionOrder.oralDiet.instruction` |
| NutritionOrder.oralDiet.modifierExtension | NutritionOrder.oralDiet.modifierExtension | SourceIsBroaderThanTarget | R5 `NutritionOrder.oralDiet.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `NutritionOrder.oralDiet.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| NutritionOrder.oralDiet.nutrient | NutritionOrder.oralDiet.nutrient | Equivalent | R5 `NutritionOrder.oralDiet.nutrient` maps as Equivalent to R4B `NutritionOrder.oralDiet.nutrient` |
| NutritionOrder.oralDiet.nutrient.amount | NutritionOrder.oralDiet.nutrient.amount | Equivalent | R5 `NutritionOrder.oralDiet.nutrient.amount` maps as Equivalent to R4B `NutritionOrder.oralDiet.nutrient.amount` |
| NutritionOrder.oralDiet.nutrient.extension | NutritionOrder.oralDiet.nutrient.extension | SourceIsBroaderThanTarget | R5 `NutritionOrder.oralDiet.nutrient.extension` maps as SourceIsBroaderThanTarget to R4B `NutritionOrder.oralDiet.nutrient.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| NutritionOrder.oralDiet.nutrient.id | NutritionOrder.oralDiet.nutrient.id | Equivalent | R5 `NutritionOrder.oralDiet.nutrient.id` maps as Equivalent to R4B `NutritionOrder.oralDiet.nutrient.id` |
| NutritionOrder.oralDiet.nutrient.modifier | NutritionOrder.oralDiet.nutrient.modifier | Equivalent | R5 `NutritionOrder.oralDiet.nutrient.modifier` maps as Equivalent to R4B `NutritionOrder.oralDiet.nutrient.modifier` |
| NutritionOrder.oralDiet.nutrient.modifierExtension | NutritionOrder.oralDiet.nutrient.modifierExtension | SourceIsBroaderThanTarget | R5 `NutritionOrder.oralDiet.nutrient.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `NutritionOrder.oralDiet.nutrient.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| NutritionOrder.oralDiet.schedule | NutritionOrder.oralDiet.schedule | RelatedTo | R5 `NutritionOrder.oralDiet.schedule` maps as RelatedTo to R4B `NutritionOrder.oralDiet.schedule` - schedule changed from scalar to array (max cardinality from 1 to *); schedule has change due to type change: R5 schedule BackboneElement has no equivalent or mapped type in R4B schedule |
| NutritionOrder.oralDiet.schedule.asNeeded | - | DoesNotExistInTarget | R5 `NutritionOrder.oralDiet.schedule.asNeeded` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.oralDiet.schedule.asNeededFor | - | DoesNotExistInTarget | R5 `NutritionOrder.oralDiet.schedule.asNeededFor` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.oralDiet.schedule.extension | - | DoesNotExistInTarget | R5 `NutritionOrder.oralDiet.schedule.extension` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.oralDiet.schedule.id | - | DoesNotExistInTarget | R5 `NutritionOrder.oralDiet.schedule.id` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.oralDiet.schedule.modifierExtension | - | DoesNotExistInTarget | R5 `NutritionOrder.oralDiet.schedule.modifierExtension` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.oralDiet.schedule.timing | - | DoesNotExistInTarget | R5 `NutritionOrder.oralDiet.schedule.timing` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.oralDiet.texture | NutritionOrder.oralDiet.texture | Equivalent | R5 `NutritionOrder.oralDiet.texture` maps as Equivalent to R4B `NutritionOrder.oralDiet.texture` |
| NutritionOrder.oralDiet.texture.extension | NutritionOrder.oralDiet.texture.extension | SourceIsBroaderThanTarget | R5 `NutritionOrder.oralDiet.texture.extension` maps as SourceIsBroaderThanTarget to R4B `NutritionOrder.oralDiet.texture.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| NutritionOrder.oralDiet.texture.foodType | NutritionOrder.oralDiet.texture.foodType | Equivalent | R5 `NutritionOrder.oralDiet.texture.foodType` maps as Equivalent to R4B `NutritionOrder.oralDiet.texture.foodType` |
| NutritionOrder.oralDiet.texture.id | NutritionOrder.oralDiet.texture.id | Equivalent | R5 `NutritionOrder.oralDiet.texture.id` maps as Equivalent to R4B `NutritionOrder.oralDiet.texture.id` |
| NutritionOrder.oralDiet.texture.modifier | NutritionOrder.oralDiet.texture.modifier | Equivalent | R5 `NutritionOrder.oralDiet.texture.modifier` maps as Equivalent to R4B `NutritionOrder.oralDiet.texture.modifier` |
| NutritionOrder.oralDiet.texture.modifierExtension | NutritionOrder.oralDiet.texture.modifierExtension | SourceIsBroaderThanTarget | R5 `NutritionOrder.oralDiet.texture.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `NutritionOrder.oralDiet.texture.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| NutritionOrder.oralDiet.type | NutritionOrder.oralDiet.type | Equivalent | R5 `NutritionOrder.oralDiet.type` maps as Equivalent to R4B `NutritionOrder.oralDiet.type` |
| NutritionOrder.orderer | NutritionOrder.orderer | Equivalent | R5 `NutritionOrder.orderer` maps as Equivalent to R4B `NutritionOrder.orderer` |
| NutritionOrder.outsideFoodAllowed | - | DoesNotExistInTarget | R5 `NutritionOrder.outsideFoodAllowed` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.performer | - | DoesNotExistInTarget | R5 `NutritionOrder.performer` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.priority | - | DoesNotExistInTarget | R5 `NutritionOrder.priority` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.status | NutritionOrder.status | Equivalent | R5 `NutritionOrder.status` maps as Equivalent to R4B `NutritionOrder.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-status|5.0.0 and http://hl7.org/fhir/ValueSet/request-status|4.3.0 (Equivalent) |
| NutritionOrder.subject | - | DoesNotExistInTarget | R5 `NutritionOrder.subject` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.supplement | NutritionOrder.supplement | Equivalent | R5 `NutritionOrder.supplement` maps as Equivalent to R4B `NutritionOrder.supplement` |
| NutritionOrder.supplement.extension | NutritionOrder.supplement.extension | SourceIsBroaderThanTarget | R5 `NutritionOrder.supplement.extension` maps as SourceIsBroaderThanTarget to R4B `NutritionOrder.supplement.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| NutritionOrder.supplement.id | NutritionOrder.supplement.id | Equivalent | R5 `NutritionOrder.supplement.id` maps as Equivalent to R4B `NutritionOrder.supplement.id` |
| NutritionOrder.supplement.instruction | NutritionOrder.supplement.instruction | Equivalent | R5 `NutritionOrder.supplement.instruction` maps as Equivalent to R4B `NutritionOrder.supplement.instruction` |
| NutritionOrder.supplement.modifierExtension | NutritionOrder.supplement.modifierExtension | SourceIsBroaderThanTarget | R5 `NutritionOrder.supplement.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `NutritionOrder.supplement.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| NutritionOrder.supplement.productName | NutritionOrder.supplement.productName | Equivalent | R5 `NutritionOrder.supplement.productName` maps as Equivalent to R4B `NutritionOrder.supplement.productName` |
| NutritionOrder.supplement.quantity | NutritionOrder.supplement.quantity | Equivalent | R5 `NutritionOrder.supplement.quantity` maps as Equivalent to R4B `NutritionOrder.supplement.quantity` |
| NutritionOrder.supplement.schedule | NutritionOrder.supplement.schedule | RelatedTo | R5 `NutritionOrder.supplement.schedule` maps as RelatedTo to R4B `NutritionOrder.supplement.schedule` - schedule changed from scalar to array (max cardinality from 1 to *); schedule has change due to type change: R5 schedule BackboneElement has no equivalent or mapped type in R4B schedule |
| NutritionOrder.supplement.schedule.asNeeded | - | DoesNotExistInTarget | R5 `NutritionOrder.supplement.schedule.asNeeded` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.supplement.schedule.asNeededFor | - | DoesNotExistInTarget | R5 `NutritionOrder.supplement.schedule.asNeededFor` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.supplement.schedule.extension | - | DoesNotExistInTarget | R5 `NutritionOrder.supplement.schedule.extension` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.supplement.schedule.id | - | DoesNotExistInTarget | R5 `NutritionOrder.supplement.schedule.id` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.supplement.schedule.modifierExtension | - | DoesNotExistInTarget | R5 `NutritionOrder.supplement.schedule.modifierExtension` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.supplement.schedule.timing | - | DoesNotExistInTarget | R5 `NutritionOrder.supplement.schedule.timing` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.supplement.type | NutritionOrder.supplement.type | SourceIsBroaderThanTarget | R5 `NutritionOrder.supplement.type` maps as SourceIsBroaderThanTarget to R4B `NutritionOrder.supplement.type` - type has change due to type change: R5 type CodeableReference has no equivalent or mapped type in R4B type |
| NutritionOrder.supportingInformation | - | DoesNotExistInTarget | R5 `NutritionOrder.supportingInformation` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.text | NutritionOrder.text | Equivalent | R5 `NutritionOrder.text` maps as Equivalent to R4B `NutritionOrder.text` |

