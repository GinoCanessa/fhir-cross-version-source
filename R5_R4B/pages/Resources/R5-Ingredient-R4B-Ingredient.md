Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Ingredient |  | An ingredient of a manufactured item or pharmaceutical product. | 47 | 27 |
| Target | Ingredient |  | An ingredient of a manufactured item or pharmaceutical product. | 44 | 24 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 3 |
Equivalent | 4 |
RelatedTo | 40 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Ingredient | Ingredient | Equivalent | R5 `Ingredient` maps as Equivalent to R4B `Ingredient` |
| Ingredient.allergenicIndicator | Ingredient.allergenicIndicator | Equivalent | R5 `Ingredient.allergenicIndicator` maps as Equivalent to R4B `Ingredient.allergenicIndicator` |
| Ingredient.comment | - | DoesNotExistInTarget | R5 `Ingredient.comment` does not appear in the target and has no mapping for `Ingredient`. |
| Ingredient.contained | Ingredient.contained | Equivalent | R5 `Ingredient.contained` maps as Equivalent to R4B `Ingredient.contained` |
| Ingredient.extension | Ingredient.extension | SourceIsBroaderThanTarget | R5 `Ingredient.extension` maps as SourceIsBroaderThanTarget to R4B `Ingredient.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Ingredient.for | Ingredient.for | Equivalent | R5 `Ingredient.for` maps as Equivalent to R4B `Ingredient.for` |
| Ingredient.function | Ingredient.function | Equivalent | R5 `Ingredient.function` maps as Equivalent to R4B `Ingredient.function` |
| Ingredient.group | - | DoesNotExistInTarget | R5 `Ingredient.group` does not appear in the target and has no mapping for `Ingredient`. |
| Ingredient.id | Ingredient.id | Equivalent | R5 `Ingredient.id` maps as Equivalent to R4B `Ingredient.id` |
| Ingredient.identifier | Ingredient.identifier | Equivalent | R5 `Ingredient.identifier` maps as Equivalent to R4B `Ingredient.identifier` |
| Ingredient.implicitRules | Ingredient.implicitRules | Equivalent | R5 `Ingredient.implicitRules` maps as Equivalent to R4B `Ingredient.implicitRules` |
| Ingredient.language | Ingredient.language | RelatedTo | R5 `Ingredient.language` maps as RelatedTo to R4B `Ingredient.language` - language changed the binding strength from Required to Preferred |
| Ingredient.manufacturer | Ingredient.manufacturer | Equivalent | R5 `Ingredient.manufacturer` maps as Equivalent to R4B `Ingredient.manufacturer` |
| Ingredient.manufacturer.extension | Ingredient.manufacturer.extension | SourceIsBroaderThanTarget | R5 `Ingredient.manufacturer.extension` maps as SourceIsBroaderThanTarget to R4B `Ingredient.manufacturer.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Ingredient.manufacturer.id | Ingredient.manufacturer.id | Equivalent | R5 `Ingredient.manufacturer.id` maps as Equivalent to R4B `Ingredient.manufacturer.id` |
| Ingredient.manufacturer.manufacturer | Ingredient.manufacturer.manufacturer | Equivalent | R5 `Ingredient.manufacturer.manufacturer` maps as Equivalent to R4B `Ingredient.manufacturer.manufacturer` |
| Ingredient.manufacturer.modifierExtension | Ingredient.manufacturer.modifierExtension | SourceIsBroaderThanTarget | R5 `Ingredient.manufacturer.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Ingredient.manufacturer.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Ingredient.manufacturer.role | Ingredient.manufacturer.role | Equivalent | R5 `Ingredient.manufacturer.role` maps as Equivalent to R4B `Ingredient.manufacturer.role` - role has compatible required binding for code type: http://hl7.org/fhir/ValueSet/ingredient-manufacturer-role|5.0.0 and http://hl7.org/fhir/ValueSet/ingredient-manufacturer-role|4.3.0 (Equivalent) |
| Ingredient.meta | Ingredient.meta | Equivalent | R5 `Ingredient.meta` maps as Equivalent to R4B `Ingredient.meta` |
| Ingredient.modifierExtension | Ingredient.modifierExtension | SourceIsBroaderThanTarget | R5 `Ingredient.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Ingredient.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Ingredient.role | Ingredient.role | Equivalent | R5 `Ingredient.role` maps as Equivalent to R4B `Ingredient.role` |
| Ingredient.status | Ingredient.status | Equivalent | R5 `Ingredient.status` maps as Equivalent to R4B `Ingredient.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.3.0 (Equivalent) |
| Ingredient.substance | Ingredient.substance | Equivalent | R5 `Ingredient.substance` maps as Equivalent to R4B `Ingredient.substance` |
| Ingredient.substance.code | Ingredient.substance.code | Equivalent | R5 `Ingredient.substance.code` maps as Equivalent to R4B `Ingredient.substance.code` |
| Ingredient.substance.extension | Ingredient.substance.extension | SourceIsBroaderThanTarget | R5 `Ingredient.substance.extension` maps as SourceIsBroaderThanTarget to R4B `Ingredient.substance.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Ingredient.substance.id | Ingredient.substance.id | Equivalent | R5 `Ingredient.substance.id` maps as Equivalent to R4B `Ingredient.substance.id` |
| Ingredient.substance.modifierExtension | Ingredient.substance.modifierExtension | SourceIsBroaderThanTarget | R5 `Ingredient.substance.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Ingredient.substance.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Ingredient.substance.strength | Ingredient.substance.strength | Equivalent | R5 `Ingredient.substance.strength` maps as Equivalent to R4B `Ingredient.substance.strength` |
| Ingredient.substance.strength.basis | - | DoesNotExistInTarget | R5 `Ingredient.substance.strength.basis` does not appear in the target and has no mapping for `Ingredient`. |
| Ingredient.substance.strength.concentration[x] | Ingredient.substance.strength.concentration[x] | SourceIsBroaderThanTarget | R5 `Ingredient.substance.strength.concentration[x]` maps as SourceIsBroaderThanTarget to R4B `Ingredient.substance.strength.concentration[x]` - concentration[x] has change due to type change: R5 `concentration[x]` `Ratio` maps as SourceIsBroaderThanTarget for R4B `concentration[x]`; concentration[x] has change due to type change: R5 concentration[x] CodeableConcept has no equivalent or mapped type in R4B concentration[x]; concentration[x] has change due to type change: R5 concentration[x] Quantity has no equivalent or mapped type in R4B concentration[x] |
| Ingredient.substance.strength.country | Ingredient.substance.strength.country | Equivalent | R5 `Ingredient.substance.strength.country` maps as Equivalent to R4B `Ingredient.substance.strength.country` |
| Ingredient.substance.strength.extension | Ingredient.substance.strength.extension | SourceIsBroaderThanTarget | R5 `Ingredient.substance.strength.extension` maps as SourceIsBroaderThanTarget to R4B `Ingredient.substance.strength.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Ingredient.substance.strength.id | Ingredient.substance.strength.id | Equivalent | R5 `Ingredient.substance.strength.id` maps as Equivalent to R4B `Ingredient.substance.strength.id` |
| Ingredient.substance.strength.measurementPoint | Ingredient.substance.strength.measurementPoint | Equivalent | R5 `Ingredient.substance.strength.measurementPoint` maps as Equivalent to R4B `Ingredient.substance.strength.measurementPoint` |
| Ingredient.substance.strength.modifierExtension | Ingredient.substance.strength.modifierExtension | SourceIsBroaderThanTarget | R5 `Ingredient.substance.strength.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Ingredient.substance.strength.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Ingredient.substance.strength.presentation[x] | Ingredient.substance.strength.presentation[x] | SourceIsBroaderThanTarget | R5 `Ingredient.substance.strength.presentation[x]` maps as SourceIsBroaderThanTarget to R4B `Ingredient.substance.strength.presentation[x]` - presentation[x] has change due to type change: R5 `presentation[x]` `Ratio` maps as SourceIsBroaderThanTarget for R4B `presentation[x]`; presentation[x] has change due to type change: R5 presentation[x] CodeableConcept has no equivalent or mapped type in R4B presentation[x]; presentation[x] has change due to type change: R5 presentation[x] Quantity has no equivalent or mapped type in R4B presentation[x] |
| Ingredient.substance.strength.referenceStrength | Ingredient.substance.strength.referenceStrength | Equivalent | R5 `Ingredient.substance.strength.referenceStrength` maps as Equivalent to R4B `Ingredient.substance.strength.referenceStrength` |
| Ingredient.substance.strength.referenceStrength.country | Ingredient.substance.strength.referenceStrength.country | Equivalent | R5 `Ingredient.substance.strength.referenceStrength.country` maps as Equivalent to R4B `Ingredient.substance.strength.referenceStrength.country` |
| Ingredient.substance.strength.referenceStrength.extension | Ingredient.substance.strength.referenceStrength.extension | SourceIsBroaderThanTarget | R5 `Ingredient.substance.strength.referenceStrength.extension` maps as SourceIsBroaderThanTarget to R4B `Ingredient.substance.strength.referenceStrength.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Ingredient.substance.strength.referenceStrength.id | Ingredient.substance.strength.referenceStrength.id | Equivalent | R5 `Ingredient.substance.strength.referenceStrength.id` maps as Equivalent to R4B `Ingredient.substance.strength.referenceStrength.id` |
| Ingredient.substance.strength.referenceStrength.measurementPoint | Ingredient.substance.strength.referenceStrength.measurementPoint | Equivalent | R5 `Ingredient.substance.strength.referenceStrength.measurementPoint` maps as Equivalent to R4B `Ingredient.substance.strength.referenceStrength.measurementPoint` |
| Ingredient.substance.strength.referenceStrength.modifierExtension | Ingredient.substance.strength.referenceStrength.modifierExtension | SourceIsBroaderThanTarget | R5 `Ingredient.substance.strength.referenceStrength.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Ingredient.substance.strength.referenceStrength.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Ingredient.substance.strength.referenceStrength.strength[x] | Ingredient.substance.strength.referenceStrength.strength[x] | SourceIsBroaderThanTarget | R5 `Ingredient.substance.strength.referenceStrength.strength[x]` maps as SourceIsBroaderThanTarget to R4B `Ingredient.substance.strength.referenceStrength.strength[x]` - strength[x] has change due to type change: R5 `strength[x]` `Ratio` maps as SourceIsBroaderThanTarget for R4B `strength[x]`; strength[x] has change due to type change: R5 strength[x] Quantity has no equivalent or mapped type in R4B strength[x] |
| Ingredient.substance.strength.referenceStrength.substance | Ingredient.substance.strength.referenceStrength.substance | Equivalent | R5 `Ingredient.substance.strength.referenceStrength.substance` maps as Equivalent to R4B `Ingredient.substance.strength.referenceStrength.substance` |
| Ingredient.substance.strength.textConcentration | Ingredient.substance.strength.textConcentration | Equivalent | R5 `Ingredient.substance.strength.textConcentration` maps as Equivalent to R4B `Ingredient.substance.strength.textConcentration` |
| Ingredient.substance.strength.textPresentation | Ingredient.substance.strength.textPresentation | Equivalent | R5 `Ingredient.substance.strength.textPresentation` maps as Equivalent to R4B `Ingredient.substance.strength.textPresentation` |
| Ingredient.text | Ingredient.text | Equivalent | R5 `Ingredient.text` maps as Equivalent to R4B `Ingredient.text` |

