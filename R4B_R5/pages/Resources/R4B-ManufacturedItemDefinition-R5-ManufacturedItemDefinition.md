Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ManufacturedItemDefinition |  | The definition and characteristics of a medicinal manufactured item, such as a tablet or capsule, as contained in a packaged medicinal product. | 21 | 10 |
| Target | ManufacturedItemDefinition |  | The definition and characteristics of a medicinal manufactured item, such as a tablet or capsule, as contained in a packaged medicinal product. | 40 | 23 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 17 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ManufacturedItemDefinition | ManufacturedItemDefinition | Equivalent | R4B `ManufacturedItemDefinition` maps as Equivalent to R5 `ManufacturedItemDefinition` |
| ManufacturedItemDefinition.contained | ManufacturedItemDefinition.contained | Equivalent | R4B `ManufacturedItemDefinition.contained` maps as Equivalent to R5 `ManufacturedItemDefinition.contained` |
| ManufacturedItemDefinition.extension | ManufacturedItemDefinition.extension | RelatedTo | R4B `ManufacturedItemDefinition.extension` maps as RelatedTo to R5 `ManufacturedItemDefinition.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ManufacturedItemDefinition.id | ManufacturedItemDefinition.id | Equivalent | R4B `ManufacturedItemDefinition.id` maps as Equivalent to R5 `ManufacturedItemDefinition.id` |
| ManufacturedItemDefinition.identifier | ManufacturedItemDefinition.identifier | Equivalent | R4B `ManufacturedItemDefinition.identifier` maps as Equivalent to R5 `ManufacturedItemDefinition.identifier` |
| ManufacturedItemDefinition.implicitRules | ManufacturedItemDefinition.implicitRules | Equivalent | R4B `ManufacturedItemDefinition.implicitRules` maps as Equivalent to R5 `ManufacturedItemDefinition.implicitRules` |
| ManufacturedItemDefinition.ingredient | ManufacturedItemDefinition.ingredient | Equivalent | R4B `ManufacturedItemDefinition.ingredient` maps as Equivalent to R5 `ManufacturedItemDefinition.ingredient` |
| ManufacturedItemDefinition.language | ManufacturedItemDefinition.language | RelatedTo | R4B `ManufacturedItemDefinition.language` maps as RelatedTo to R5 `ManufacturedItemDefinition.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| ManufacturedItemDefinition.manufacturedDoseForm | ManufacturedItemDefinition.manufacturedDoseForm | Equivalent | R4B `ManufacturedItemDefinition.manufacturedDoseForm` maps as Equivalent to R5 `ManufacturedItemDefinition.manufacturedDoseForm` |
| ManufacturedItemDefinition.manufacturer | ManufacturedItemDefinition.manufacturer | Equivalent | R4B `ManufacturedItemDefinition.manufacturer` maps as Equivalent to R5 `ManufacturedItemDefinition.manufacturer` |
| ManufacturedItemDefinition.meta | ManufacturedItemDefinition.meta | Equivalent | R4B `ManufacturedItemDefinition.meta` maps as Equivalent to R5 `ManufacturedItemDefinition.meta` |
| ManufacturedItemDefinition.modifierExtension | ManufacturedItemDefinition.modifierExtension | RelatedTo | R4B `ManufacturedItemDefinition.modifierExtension` maps as RelatedTo to R5 `ManufacturedItemDefinition.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ManufacturedItemDefinition.property | ManufacturedItemDefinition.property | Equivalent | R4B `ManufacturedItemDefinition.property` maps as Equivalent to R5 `ManufacturedItemDefinition.property` |
| ManufacturedItemDefinition.property.extension | ManufacturedItemDefinition.property.extension | RelatedTo | R4B `ManufacturedItemDefinition.property.extension` maps as RelatedTo to R5 `ManufacturedItemDefinition.property.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ManufacturedItemDefinition.property.id | ManufacturedItemDefinition.property.id | Equivalent | R4B `ManufacturedItemDefinition.property.id` maps as Equivalent to R5 `ManufacturedItemDefinition.property.id` |
| ManufacturedItemDefinition.property.modifierExtension | ManufacturedItemDefinition.property.modifierExtension | RelatedTo | R4B `ManufacturedItemDefinition.property.modifierExtension` maps as RelatedTo to R5 `ManufacturedItemDefinition.property.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ManufacturedItemDefinition.property.type | ManufacturedItemDefinition.property.type | Equivalent | R4B `ManufacturedItemDefinition.property.type` maps as Equivalent to R5 `ManufacturedItemDefinition.property.type` |
| ManufacturedItemDefinition.property.value[x] | ManufacturedItemDefinition.property.value[x] | RelatedTo | R4B `ManufacturedItemDefinition.property.value[x]` maps as RelatedTo to R5 `ManufacturedItemDefinition.property.value[x]` - value[x] has change due to type change: R4B `value[x]` `Attachment` maps as RelatedTo for R5 `value[x]` |
| ManufacturedItemDefinition.status | ManufacturedItemDefinition.status | Equivalent | R4B `ManufacturedItemDefinition.status` maps as Equivalent to R5 `ManufacturedItemDefinition.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| ManufacturedItemDefinition.text | ManufacturedItemDefinition.text | Equivalent | R4B `ManufacturedItemDefinition.text` maps as Equivalent to R5 `ManufacturedItemDefinition.text` |
| ManufacturedItemDefinition.unitOfPresentation | ManufacturedItemDefinition.unitOfPresentation | Equivalent | R4B `ManufacturedItemDefinition.unitOfPresentation` maps as Equivalent to R5 `ManufacturedItemDefinition.unitOfPresentation` |

