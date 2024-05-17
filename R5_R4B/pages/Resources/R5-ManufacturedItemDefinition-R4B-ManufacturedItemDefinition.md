Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ManufacturedItemDefinition |  | The definition and characteristics of a medicinal manufactured item, such as a tablet or capsule, as contained in a packaged medicinal product. | 40 | 23 |
| Target | ManufacturedItemDefinition |  | The definition and characteristics of a medicinal manufactured item, such as a tablet or capsule, as contained in a packaged medicinal product. | 21 | 10 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 19 |
Equivalent | 4 |
RelatedTo | 17 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ManufacturedItemDefinition | ManufacturedItemDefinition | Equivalent | R5 `ManufacturedItemDefinition` maps as Equivalent to R4B `ManufacturedItemDefinition` |
| ManufacturedItemDefinition.component | - | DoesNotExistInTarget | R5 `ManufacturedItemDefinition.component` does not appear in the target and has no mapping for `ManufacturedItemDefinition`. |
| ManufacturedItemDefinition.component.amount | - | DoesNotExistInTarget | R5 `ManufacturedItemDefinition.component.amount` does not appear in the target and has no mapping for `ManufacturedItemDefinition`. |
| ManufacturedItemDefinition.component.component | - | DoesNotExistInTarget | R5 `ManufacturedItemDefinition.component.component` does not appear in the target and has no mapping for `ManufacturedItemDefinition`. |
| ManufacturedItemDefinition.component.constituent | - | DoesNotExistInTarget | R5 `ManufacturedItemDefinition.component.constituent` does not appear in the target and has no mapping for `ManufacturedItemDefinition`. |
| ManufacturedItemDefinition.component.constituent.amount | - | DoesNotExistInTarget | R5 `ManufacturedItemDefinition.component.constituent.amount` does not appear in the target and has no mapping for `ManufacturedItemDefinition`. |
| ManufacturedItemDefinition.component.constituent.extension | - | DoesNotExistInTarget | R5 `ManufacturedItemDefinition.component.constituent.extension` does not appear in the target and has no mapping for `ManufacturedItemDefinition`. |
| ManufacturedItemDefinition.component.constituent.function | - | DoesNotExistInTarget | R5 `ManufacturedItemDefinition.component.constituent.function` does not appear in the target and has no mapping for `ManufacturedItemDefinition`. |
| ManufacturedItemDefinition.component.constituent.hasIngredient | - | DoesNotExistInTarget | R5 `ManufacturedItemDefinition.component.constituent.hasIngredient` does not appear in the target and has no mapping for `ManufacturedItemDefinition`. |
| ManufacturedItemDefinition.component.constituent.id | - | DoesNotExistInTarget | R5 `ManufacturedItemDefinition.component.constituent.id` does not appear in the target and has no mapping for `ManufacturedItemDefinition`. |
| ManufacturedItemDefinition.component.constituent.location | - | DoesNotExistInTarget | R5 `ManufacturedItemDefinition.component.constituent.location` does not appear in the target and has no mapping for `ManufacturedItemDefinition`. |
| ManufacturedItemDefinition.component.constituent.modifierExtension | - | DoesNotExistInTarget | R5 `ManufacturedItemDefinition.component.constituent.modifierExtension` does not appear in the target and has no mapping for `ManufacturedItemDefinition`. |
| ManufacturedItemDefinition.component.extension | - | DoesNotExistInTarget | R5 `ManufacturedItemDefinition.component.extension` does not appear in the target and has no mapping for `ManufacturedItemDefinition`. |
| ManufacturedItemDefinition.component.function | - | DoesNotExistInTarget | R5 `ManufacturedItemDefinition.component.function` does not appear in the target and has no mapping for `ManufacturedItemDefinition`. |
| ManufacturedItemDefinition.component.id | - | DoesNotExistInTarget | R5 `ManufacturedItemDefinition.component.id` does not appear in the target and has no mapping for `ManufacturedItemDefinition`. |
| ManufacturedItemDefinition.component.modifierExtension | - | DoesNotExistInTarget | R5 `ManufacturedItemDefinition.component.modifierExtension` does not appear in the target and has no mapping for `ManufacturedItemDefinition`. |
| ManufacturedItemDefinition.component.property | - | DoesNotExistInTarget | R5 `ManufacturedItemDefinition.component.property` does not appear in the target and has no mapping for `ManufacturedItemDefinition`. |
| ManufacturedItemDefinition.component.type | - | DoesNotExistInTarget | R5 `ManufacturedItemDefinition.component.type` does not appear in the target and has no mapping for `ManufacturedItemDefinition`. |
| ManufacturedItemDefinition.contained | ManufacturedItemDefinition.contained | Equivalent | R5 `ManufacturedItemDefinition.contained` maps as Equivalent to R4B `ManufacturedItemDefinition.contained` |
| ManufacturedItemDefinition.extension | ManufacturedItemDefinition.extension | SourceIsBroaderThanTarget | R5 `ManufacturedItemDefinition.extension` maps as SourceIsBroaderThanTarget to R4B `ManufacturedItemDefinition.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| ManufacturedItemDefinition.id | ManufacturedItemDefinition.id | Equivalent | R5 `ManufacturedItemDefinition.id` maps as Equivalent to R4B `ManufacturedItemDefinition.id` |
| ManufacturedItemDefinition.identifier | ManufacturedItemDefinition.identifier | Equivalent | R5 `ManufacturedItemDefinition.identifier` maps as Equivalent to R4B `ManufacturedItemDefinition.identifier` |
| ManufacturedItemDefinition.implicitRules | ManufacturedItemDefinition.implicitRules | Equivalent | R5 `ManufacturedItemDefinition.implicitRules` maps as Equivalent to R4B `ManufacturedItemDefinition.implicitRules` |
| ManufacturedItemDefinition.ingredient | ManufacturedItemDefinition.ingredient | Equivalent | R5 `ManufacturedItemDefinition.ingredient` maps as Equivalent to R4B `ManufacturedItemDefinition.ingredient` |
| ManufacturedItemDefinition.language | ManufacturedItemDefinition.language | RelatedTo | R5 `ManufacturedItemDefinition.language` maps as RelatedTo to R4B `ManufacturedItemDefinition.language` - language changed the binding strength from Required to Preferred |
| ManufacturedItemDefinition.manufacturedDoseForm | ManufacturedItemDefinition.manufacturedDoseForm | Equivalent | R5 `ManufacturedItemDefinition.manufacturedDoseForm` maps as Equivalent to R4B `ManufacturedItemDefinition.manufacturedDoseForm` |
| ManufacturedItemDefinition.manufacturer | ManufacturedItemDefinition.manufacturer | Equivalent | R5 `ManufacturedItemDefinition.manufacturer` maps as Equivalent to R4B `ManufacturedItemDefinition.manufacturer` |
| ManufacturedItemDefinition.marketingStatus | - | DoesNotExistInTarget | R5 `ManufacturedItemDefinition.marketingStatus` does not appear in the target and has no mapping for `ManufacturedItemDefinition`. |
| ManufacturedItemDefinition.meta | ManufacturedItemDefinition.meta | Equivalent | R5 `ManufacturedItemDefinition.meta` maps as Equivalent to R4B `ManufacturedItemDefinition.meta` |
| ManufacturedItemDefinition.modifierExtension | ManufacturedItemDefinition.modifierExtension | SourceIsBroaderThanTarget | R5 `ManufacturedItemDefinition.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `ManufacturedItemDefinition.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| ManufacturedItemDefinition.name | - | DoesNotExistInTarget | R5 `ManufacturedItemDefinition.name` does not appear in the target and has no mapping for `ManufacturedItemDefinition`. |
| ManufacturedItemDefinition.property | ManufacturedItemDefinition.property | Equivalent | R5 `ManufacturedItemDefinition.property` maps as Equivalent to R4B `ManufacturedItemDefinition.property` |
| ManufacturedItemDefinition.property.extension | ManufacturedItemDefinition.property.extension | SourceIsBroaderThanTarget | R5 `ManufacturedItemDefinition.property.extension` maps as SourceIsBroaderThanTarget to R4B `ManufacturedItemDefinition.property.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| ManufacturedItemDefinition.property.id | ManufacturedItemDefinition.property.id | Equivalent | R5 `ManufacturedItemDefinition.property.id` maps as Equivalent to R4B `ManufacturedItemDefinition.property.id` |
| ManufacturedItemDefinition.property.modifierExtension | ManufacturedItemDefinition.property.modifierExtension | SourceIsBroaderThanTarget | R5 `ManufacturedItemDefinition.property.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `ManufacturedItemDefinition.property.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| ManufacturedItemDefinition.property.type | ManufacturedItemDefinition.property.type | Equivalent | R5 `ManufacturedItemDefinition.property.type` maps as Equivalent to R4B `ManufacturedItemDefinition.property.type` |
| ManufacturedItemDefinition.property.value[x] | ManufacturedItemDefinition.property.value[x] | RelatedTo | R5 `ManufacturedItemDefinition.property.value[x]` maps as RelatedTo to R4B `ManufacturedItemDefinition.property.value[x]` - value[x] has change due to type change: R5 value[x] markdown has no equivalent or mapped type in R4B value[x]; value[x] has change due to type change: R5 `value[x]` `Attachment` maps as RelatedTo for R4B `value[x]`; value[x] has change due to type change: R5 value[x] Reference has no equivalent or mapped type in R4B value[x] |
| ManufacturedItemDefinition.status | ManufacturedItemDefinition.status | Equivalent | R5 `ManufacturedItemDefinition.status` maps as Equivalent to R4B `ManufacturedItemDefinition.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.3.0 (Equivalent) |
| ManufacturedItemDefinition.text | ManufacturedItemDefinition.text | Equivalent | R5 `ManufacturedItemDefinition.text` maps as Equivalent to R4B `ManufacturedItemDefinition.text` |
| ManufacturedItemDefinition.unitOfPresentation | ManufacturedItemDefinition.unitOfPresentation | Equivalent | R5 `ManufacturedItemDefinition.unitOfPresentation` maps as Equivalent to R4B `ManufacturedItemDefinition.unitOfPresentation` |

