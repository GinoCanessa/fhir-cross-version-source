Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | NutritionOrder |  | A request to supply a diet, formula feeding (enteral) or oral nutritional supplement to a patient/resident. | 71 | 45 |
| Target | NutritionOrder |  | A request to supply a diet, formula feeding (enteral) or oral nutritional supplement to a patient/resident. | 101 | 63 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 4 |
Equivalent | 4 |
RelatedTo | 63 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| NutritionOrder | NutritionOrder | Equivalent | R4B `NutritionOrder` maps as Equivalent to R5 `NutritionOrder` |
| NutritionOrder.allergyIntolerance | NutritionOrder.allergyIntolerance | Equivalent | R4B `NutritionOrder.allergyIntolerance` maps as Equivalent to R5 `NutritionOrder.allergyIntolerance` |
| NutritionOrder.contained | NutritionOrder.contained | Equivalent | R4B `NutritionOrder.contained` maps as Equivalent to R5 `NutritionOrder.contained` |
| NutritionOrder.dateTime | NutritionOrder.dateTime | Equivalent | R4B `NutritionOrder.dateTime` maps as Equivalent to R5 `NutritionOrder.dateTime` |
| NutritionOrder.encounter | NutritionOrder.encounter | Equivalent | R4B `NutritionOrder.encounter` maps as Equivalent to R5 `NutritionOrder.encounter` |
| NutritionOrder.enteralFormula | NutritionOrder.enteralFormula | Equivalent | R4B `NutritionOrder.enteralFormula` maps as Equivalent to R5 `NutritionOrder.enteralFormula` |
| NutritionOrder.enteralFormula.additiveProductName | - | DoesNotExistInTarget | R4B `NutritionOrder.enteralFormula.additiveProductName` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.enteralFormula.additiveType | - | DoesNotExistInTarget | R4B `NutritionOrder.enteralFormula.additiveType` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.enteralFormula.administration | NutritionOrder.enteralFormula.administration | Equivalent | R4B `NutritionOrder.enteralFormula.administration` maps as Equivalent to R5 `NutritionOrder.enteralFormula.administration` |
| NutritionOrder.enteralFormula.administration.extension | NutritionOrder.enteralFormula.administration.extension | RelatedTo | R4B `NutritionOrder.enteralFormula.administration.extension` maps as RelatedTo to R5 `NutritionOrder.enteralFormula.administration.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| NutritionOrder.enteralFormula.administration.id | NutritionOrder.enteralFormula.administration.id | Equivalent | R4B `NutritionOrder.enteralFormula.administration.id` maps as Equivalent to R5 `NutritionOrder.enteralFormula.administration.id` |
| NutritionOrder.enteralFormula.administration.modifierExtension | NutritionOrder.enteralFormula.administration.modifierExtension | RelatedTo | R4B `NutritionOrder.enteralFormula.administration.modifierExtension` maps as RelatedTo to R5 `NutritionOrder.enteralFormula.administration.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| NutritionOrder.enteralFormula.administration.quantity | NutritionOrder.enteralFormula.administration.quantity | Equivalent | R4B `NutritionOrder.enteralFormula.administration.quantity` maps as Equivalent to R5 `NutritionOrder.enteralFormula.administration.quantity` |
| NutritionOrder.enteralFormula.administration.rate[x] | NutritionOrder.enteralFormula.administration.rate[x] | SourceIsNarrowerThanTarget | R4B `NutritionOrder.enteralFormula.administration.rate[x]` maps as SourceIsNarrowerThanTarget to R5 `NutritionOrder.enteralFormula.administration.rate[x]` - rate[x] has change due to type change: R4B `rate[x]` `Ratio` maps as SourceIsNarrowerThanTarget for R5 `rate[x]` |
| NutritionOrder.enteralFormula.administration.schedule | NutritionOrder.enteralFormula.administration.schedule | SourceIsBroaderThanTarget | R4B `NutritionOrder.enteralFormula.administration.schedule` maps as SourceIsBroaderThanTarget to R5 `NutritionOrder.enteralFormula.administration.schedule` - schedule has change due to type change: R4B schedule Timing has no equivalent or mapped type in R5 schedule |
| NutritionOrder.enteralFormula.administrationInstruction | NutritionOrder.enteralFormula.administrationInstruction | SourceIsBroaderThanTarget | R4B `NutritionOrder.enteralFormula.administrationInstruction` maps as SourceIsBroaderThanTarget to R5 `NutritionOrder.enteralFormula.administrationInstruction` - administrationInstruction has change due to type change: R4B administrationInstruction string has no equivalent or mapped type in R5 administrationInstruction |
| NutritionOrder.enteralFormula.baseFormulaProductName | NutritionOrder.enteralFormula.baseFormulaProductName | Equivalent | R4B `NutritionOrder.enteralFormula.baseFormulaProductName` maps as Equivalent to R5 `NutritionOrder.enteralFormula.baseFormulaProductName` |
| NutritionOrder.enteralFormula.baseFormulaType | NutritionOrder.enteralFormula.baseFormulaType | SourceIsBroaderThanTarget | R4B `NutritionOrder.enteralFormula.baseFormulaType` maps as SourceIsBroaderThanTarget to R5 `NutritionOrder.enteralFormula.baseFormulaType` - baseFormulaType has change due to type change: R4B baseFormulaType CodeableConcept has no equivalent or mapped type in R5 baseFormulaType |
| NutritionOrder.enteralFormula.caloricDensity | NutritionOrder.enteralFormula.caloricDensity | Equivalent | R4B `NutritionOrder.enteralFormula.caloricDensity` maps as Equivalent to R5 `NutritionOrder.enteralFormula.caloricDensity` |
| NutritionOrder.enteralFormula.extension | NutritionOrder.enteralFormula.extension | RelatedTo | R4B `NutritionOrder.enteralFormula.extension` maps as RelatedTo to R5 `NutritionOrder.enteralFormula.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| NutritionOrder.enteralFormula.id | NutritionOrder.enteralFormula.id | Equivalent | R4B `NutritionOrder.enteralFormula.id` maps as Equivalent to R5 `NutritionOrder.enteralFormula.id` |
| NutritionOrder.enteralFormula.maxVolumeToDeliver | NutritionOrder.enteralFormula.maxVolumeToDeliver | Equivalent | R4B `NutritionOrder.enteralFormula.maxVolumeToDeliver` maps as Equivalent to R5 `NutritionOrder.enteralFormula.maxVolumeToDeliver` |
| NutritionOrder.enteralFormula.modifierExtension | NutritionOrder.enteralFormula.modifierExtension | RelatedTo | R4B `NutritionOrder.enteralFormula.modifierExtension` maps as RelatedTo to R5 `NutritionOrder.enteralFormula.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| NutritionOrder.enteralFormula.routeofAdministration | - | DoesNotExistInTarget | R4B `NutritionOrder.enteralFormula.routeofAdministration` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.excludeFoodModifier | NutritionOrder.excludeFoodModifier | Equivalent | R4B `NutritionOrder.excludeFoodModifier` maps as Equivalent to R5 `NutritionOrder.excludeFoodModifier` |
| NutritionOrder.extension | NutritionOrder.extension | RelatedTo | R4B `NutritionOrder.extension` maps as RelatedTo to R5 `NutritionOrder.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| NutritionOrder.foodPreferenceModifier | NutritionOrder.foodPreferenceModifier | Equivalent | R4B `NutritionOrder.foodPreferenceModifier` maps as Equivalent to R5 `NutritionOrder.foodPreferenceModifier` |
| NutritionOrder.id | NutritionOrder.id | Equivalent | R4B `NutritionOrder.id` maps as Equivalent to R5 `NutritionOrder.id` |
| NutritionOrder.identifier | NutritionOrder.identifier | Equivalent | R4B `NutritionOrder.identifier` maps as Equivalent to R5 `NutritionOrder.identifier` |
| NutritionOrder.implicitRules | NutritionOrder.implicitRules | Equivalent | R4B `NutritionOrder.implicitRules` maps as Equivalent to R5 `NutritionOrder.implicitRules` |
| NutritionOrder.instantiates | NutritionOrder.instantiates | Equivalent | R4B `NutritionOrder.instantiates` maps as Equivalent to R5 `NutritionOrder.instantiates` |
| NutritionOrder.instantiatesCanonical | NutritionOrder.instantiatesCanonical | Equivalent | R4B `NutritionOrder.instantiatesCanonical` maps as Equivalent to R5 `NutritionOrder.instantiatesCanonical` |
| NutritionOrder.instantiatesUri | NutritionOrder.instantiatesUri | Equivalent | R4B `NutritionOrder.instantiatesUri` maps as Equivalent to R5 `NutritionOrder.instantiatesUri` |
| NutritionOrder.intent | NutritionOrder.intent | Equivalent | R4B `NutritionOrder.intent` maps as Equivalent to R5 `NutritionOrder.intent` - intent has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-intent|4.3.0 and http://hl7.org/fhir/ValueSet/request-intent|5.0.0 (Equivalent) |
| NutritionOrder.language | NutritionOrder.language | RelatedTo | R4B `NutritionOrder.language` maps as RelatedTo to R5 `NutritionOrder.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| NutritionOrder.meta | NutritionOrder.meta | Equivalent | R4B `NutritionOrder.meta` maps as Equivalent to R5 `NutritionOrder.meta` |
| NutritionOrder.modifierExtension | NutritionOrder.modifierExtension | RelatedTo | R4B `NutritionOrder.modifierExtension` maps as RelatedTo to R5 `NutritionOrder.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| NutritionOrder.note | NutritionOrder.note | SourceIsNarrowerThanTarget | R4B `NutritionOrder.note` maps as SourceIsNarrowerThanTarget to R5 `NutritionOrder.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| NutritionOrder.oralDiet | NutritionOrder.oralDiet | Equivalent | R4B `NutritionOrder.oralDiet` maps as Equivalent to R5 `NutritionOrder.oralDiet` |
| NutritionOrder.oralDiet.extension | NutritionOrder.oralDiet.extension | RelatedTo | R4B `NutritionOrder.oralDiet.extension` maps as RelatedTo to R5 `NutritionOrder.oralDiet.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| NutritionOrder.oralDiet.fluidConsistencyType | NutritionOrder.oralDiet.fluidConsistencyType | Equivalent | R4B `NutritionOrder.oralDiet.fluidConsistencyType` maps as Equivalent to R5 `NutritionOrder.oralDiet.fluidConsistencyType` |
| NutritionOrder.oralDiet.id | NutritionOrder.oralDiet.id | Equivalent | R4B `NutritionOrder.oralDiet.id` maps as Equivalent to R5 `NutritionOrder.oralDiet.id` |
| NutritionOrder.oralDiet.instruction | NutritionOrder.oralDiet.instruction | Equivalent | R4B `NutritionOrder.oralDiet.instruction` maps as Equivalent to R5 `NutritionOrder.oralDiet.instruction` |
| NutritionOrder.oralDiet.modifierExtension | NutritionOrder.oralDiet.modifierExtension | RelatedTo | R4B `NutritionOrder.oralDiet.modifierExtension` maps as RelatedTo to R5 `NutritionOrder.oralDiet.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| NutritionOrder.oralDiet.nutrient | NutritionOrder.oralDiet.nutrient | Equivalent | R4B `NutritionOrder.oralDiet.nutrient` maps as Equivalent to R5 `NutritionOrder.oralDiet.nutrient` |
| NutritionOrder.oralDiet.nutrient.amount | NutritionOrder.oralDiet.nutrient.amount | Equivalent | R4B `NutritionOrder.oralDiet.nutrient.amount` maps as Equivalent to R5 `NutritionOrder.oralDiet.nutrient.amount` |
| NutritionOrder.oralDiet.nutrient.extension | NutritionOrder.oralDiet.nutrient.extension | RelatedTo | R4B `NutritionOrder.oralDiet.nutrient.extension` maps as RelatedTo to R5 `NutritionOrder.oralDiet.nutrient.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| NutritionOrder.oralDiet.nutrient.id | NutritionOrder.oralDiet.nutrient.id | Equivalent | R4B `NutritionOrder.oralDiet.nutrient.id` maps as Equivalent to R5 `NutritionOrder.oralDiet.nutrient.id` |
| NutritionOrder.oralDiet.nutrient.modifier | NutritionOrder.oralDiet.nutrient.modifier | Equivalent | R4B `NutritionOrder.oralDiet.nutrient.modifier` maps as Equivalent to R5 `NutritionOrder.oralDiet.nutrient.modifier` |
| NutritionOrder.oralDiet.nutrient.modifierExtension | NutritionOrder.oralDiet.nutrient.modifierExtension | RelatedTo | R4B `NutritionOrder.oralDiet.nutrient.modifierExtension` maps as RelatedTo to R5 `NutritionOrder.oralDiet.nutrient.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| NutritionOrder.oralDiet.schedule | NutritionOrder.oralDiet.schedule | RelatedTo | R4B `NutritionOrder.oralDiet.schedule` maps as RelatedTo to R5 `NutritionOrder.oralDiet.schedule` - schedule changed from array to scalar (max cardinality from * to 1); schedule has change due to type change: R4B schedule Timing has no equivalent or mapped type in R5 schedule |
| NutritionOrder.oralDiet.texture | NutritionOrder.oralDiet.texture | Equivalent | R4B `NutritionOrder.oralDiet.texture` maps as Equivalent to R5 `NutritionOrder.oralDiet.texture` |
| NutritionOrder.oralDiet.texture.extension | NutritionOrder.oralDiet.texture.extension | RelatedTo | R4B `NutritionOrder.oralDiet.texture.extension` maps as RelatedTo to R5 `NutritionOrder.oralDiet.texture.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| NutritionOrder.oralDiet.texture.foodType | NutritionOrder.oralDiet.texture.foodType | Equivalent | R4B `NutritionOrder.oralDiet.texture.foodType` maps as Equivalent to R5 `NutritionOrder.oralDiet.texture.foodType` |
| NutritionOrder.oralDiet.texture.id | NutritionOrder.oralDiet.texture.id | Equivalent | R4B `NutritionOrder.oralDiet.texture.id` maps as Equivalent to R5 `NutritionOrder.oralDiet.texture.id` |
| NutritionOrder.oralDiet.texture.modifier | NutritionOrder.oralDiet.texture.modifier | Equivalent | R4B `NutritionOrder.oralDiet.texture.modifier` maps as Equivalent to R5 `NutritionOrder.oralDiet.texture.modifier` |
| NutritionOrder.oralDiet.texture.modifierExtension | NutritionOrder.oralDiet.texture.modifierExtension | RelatedTo | R4B `NutritionOrder.oralDiet.texture.modifierExtension` maps as RelatedTo to R5 `NutritionOrder.oralDiet.texture.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| NutritionOrder.oralDiet.type | NutritionOrder.oralDiet.type | Equivalent | R4B `NutritionOrder.oralDiet.type` maps as Equivalent to R5 `NutritionOrder.oralDiet.type` |
| NutritionOrder.orderer | NutritionOrder.orderer | Equivalent | R4B `NutritionOrder.orderer` maps as Equivalent to R5 `NutritionOrder.orderer` |
| NutritionOrder.patient | - | DoesNotExistInTarget | R4B `NutritionOrder.patient` does not appear in the target and has no mapping for `NutritionOrder`. |
| NutritionOrder.status | NutritionOrder.status | Equivalent | R4B `NutritionOrder.status` maps as Equivalent to R5 `NutritionOrder.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-status|4.3.0 and http://hl7.org/fhir/ValueSet/request-status|5.0.0 (Equivalent) |
| NutritionOrder.supplement | NutritionOrder.supplement | Equivalent | R4B `NutritionOrder.supplement` maps as Equivalent to R5 `NutritionOrder.supplement` |
| NutritionOrder.supplement.extension | NutritionOrder.supplement.extension | RelatedTo | R4B `NutritionOrder.supplement.extension` maps as RelatedTo to R5 `NutritionOrder.supplement.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| NutritionOrder.supplement.id | NutritionOrder.supplement.id | Equivalent | R4B `NutritionOrder.supplement.id` maps as Equivalent to R5 `NutritionOrder.supplement.id` |
| NutritionOrder.supplement.instruction | NutritionOrder.supplement.instruction | Equivalent | R4B `NutritionOrder.supplement.instruction` maps as Equivalent to R5 `NutritionOrder.supplement.instruction` |
| NutritionOrder.supplement.modifierExtension | NutritionOrder.supplement.modifierExtension | RelatedTo | R4B `NutritionOrder.supplement.modifierExtension` maps as RelatedTo to R5 `NutritionOrder.supplement.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| NutritionOrder.supplement.productName | NutritionOrder.supplement.productName | Equivalent | R4B `NutritionOrder.supplement.productName` maps as Equivalent to R5 `NutritionOrder.supplement.productName` |
| NutritionOrder.supplement.quantity | NutritionOrder.supplement.quantity | Equivalent | R4B `NutritionOrder.supplement.quantity` maps as Equivalent to R5 `NutritionOrder.supplement.quantity` |
| NutritionOrder.supplement.schedule | NutritionOrder.supplement.schedule | RelatedTo | R4B `NutritionOrder.supplement.schedule` maps as RelatedTo to R5 `NutritionOrder.supplement.schedule` - schedule changed from array to scalar (max cardinality from * to 1); schedule has change due to type change: R4B schedule Timing has no equivalent or mapped type in R5 schedule |
| NutritionOrder.supplement.type | NutritionOrder.supplement.type | SourceIsBroaderThanTarget | R4B `NutritionOrder.supplement.type` maps as SourceIsBroaderThanTarget to R5 `NutritionOrder.supplement.type` - type has change due to type change: R4B type CodeableConcept has no equivalent or mapped type in R5 type |
| NutritionOrder.text | NutritionOrder.text | Equivalent | R4B `NutritionOrder.text` maps as Equivalent to R5 `NutritionOrder.text` |

