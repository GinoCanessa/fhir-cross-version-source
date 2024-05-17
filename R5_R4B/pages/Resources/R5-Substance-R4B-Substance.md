Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Substance |  | A homogeneous material with a definite composition. | 23 | 12 |
| Target | Substance |  | A homogeneous material with a definite composition. | 27 | 13 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 2 |
Equivalent | 4 |
RelatedTo | 17 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Substance | Substance | Equivalent | R5 `Substance` maps as Equivalent to R4B `Substance` |
| Substance.category | Substance.category | Equivalent | R5 `Substance.category` maps as Equivalent to R4B `Substance.category` |
| Substance.code | Substance.code | SourceIsBroaderThanTarget | R5 `Substance.code` maps as SourceIsBroaderThanTarget to R4B `Substance.code` - code has change due to type change: R5 code CodeableReference has no equivalent or mapped type in R4B code |
| Substance.contained | Substance.contained | Equivalent | R5 `Substance.contained` maps as Equivalent to R4B `Substance.contained` |
| Substance.description | Substance.description | SourceIsBroaderThanTarget | R5 `Substance.description` maps as SourceIsBroaderThanTarget to R4B `Substance.description` - description has change due to type change: R5 description markdown has no equivalent or mapped type in R4B description |
| Substance.expiry | - | DoesNotExistInTarget | R5 `Substance.expiry` does not appear in the target and has no mapping for `Substance`. |
| Substance.extension | Substance.extension | SourceIsBroaderThanTarget | R5 `Substance.extension` maps as SourceIsBroaderThanTarget to R4B `Substance.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Substance.id | Substance.id | Equivalent | R5 `Substance.id` maps as Equivalent to R4B `Substance.id` |
| Substance.identifier | Substance.identifier | Equivalent | R5 `Substance.identifier` maps as Equivalent to R4B `Substance.identifier` |
| Substance.implicitRules | Substance.implicitRules | Equivalent | R5 `Substance.implicitRules` maps as Equivalent to R4B `Substance.implicitRules` |
| Substance.ingredient | Substance.ingredient | Equivalent | R5 `Substance.ingredient` maps as Equivalent to R4B `Substance.ingredient` |
| Substance.ingredient.extension | Substance.ingredient.extension | SourceIsBroaderThanTarget | R5 `Substance.ingredient.extension` maps as SourceIsBroaderThanTarget to R4B `Substance.ingredient.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Substance.ingredient.id | Substance.ingredient.id | Equivalent | R5 `Substance.ingredient.id` maps as Equivalent to R4B `Substance.ingredient.id` |
| Substance.ingredient.modifierExtension | Substance.ingredient.modifierExtension | SourceIsBroaderThanTarget | R5 `Substance.ingredient.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Substance.ingredient.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Substance.ingredient.quantity | Substance.ingredient.quantity | SourceIsBroaderThanTarget | R5 `Substance.ingredient.quantity` maps as SourceIsBroaderThanTarget to R4B `Substance.ingredient.quantity` - quantity has change due to type change: R5 `quantity` `Ratio` maps as SourceIsBroaderThanTarget for R4B `quantity` |
| Substance.ingredient.substance[x] | Substance.ingredient.substance[x] | Equivalent | R5 `Substance.ingredient.substance[x]` maps as Equivalent to R4B `Substance.ingredient.substance[x]` |
| Substance.instance | Substance.instance | RelatedTo | R5 `Substance.instance` maps as RelatedTo to R4B `Substance.instance` - instance changed from scalar to array (max cardinality from 1 to *); instance has change due to type change: R5 instance boolean has no equivalent or mapped type in R4B instance |
| Substance.language | Substance.language | RelatedTo | R5 `Substance.language` maps as RelatedTo to R4B `Substance.language` - language changed the binding strength from Required to Preferred |
| Substance.meta | Substance.meta | Equivalent | R5 `Substance.meta` maps as Equivalent to R4B `Substance.meta` |
| Substance.modifierExtension | Substance.modifierExtension | SourceIsBroaderThanTarget | R5 `Substance.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Substance.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Substance.quantity | - | DoesNotExistInTarget | R5 `Substance.quantity` does not appear in the target and has no mapping for `Substance`. |
| Substance.status | Substance.status | Equivalent | R5 `Substance.status` maps as Equivalent to R4B `Substance.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/substance-status|5.0.0 and http://hl7.org/fhir/ValueSet/substance-status|4.3.0 (Equivalent) |
| Substance.text | Substance.text | Equivalent | R5 `Substance.text` maps as Equivalent to R4B `Substance.text` |

