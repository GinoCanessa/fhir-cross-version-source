Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Substance |  | A homogeneous material with a definite composition. | 23 | 12 |
| Target | Substance |  | A homogeneous material with a definite composition. | 27 | 13 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 14 |
RelatedTo | 1 |
SourceIsBroaderThanTarget | 7 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Substance | Substance | Equivalent | R5 `Substance` maps as Equivalent to R4 `Substance` |
| Substance.category | Substance.category | Equivalent | R5 `Substance.category` maps as Equivalent to R4 `Substance.category` |
| Substance.code | Substance.code | SourceIsBroaderThanTarget | R5 `Substance.code` maps as SourceIsBroaderThanTarget to R4 `Substance.code` - code has change due to type change: R5 code CodeableReference has no equivalent or mapped type in R4 code |
| Substance.contained | Substance.contained | Equivalent | R5 `Substance.contained` maps as Equivalent to R4 `Substance.contained` |
| Substance.description | Substance.description | SourceIsBroaderThanTarget | R5 `Substance.description` maps as SourceIsBroaderThanTarget to R4 `Substance.description` - description has change due to type change: R5 description markdown has no equivalent or mapped type in R4 description |
| Substance.expiry | Substance.instance.expiry | Equivalent | R5 `Substance.expiry` maps as Equivalent to R4 `Substance.instance.expiry` |
| Substance.extension | Substance.extension | SourceIsBroaderThanTarget | R5 `Substance.extension` maps as SourceIsBroaderThanTarget to R4 `Substance.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Substance.id | Substance.id | Equivalent | R5 `Substance.id` maps as Equivalent to R4 `Substance.id` |
| Substance.identifier | Substance.identifier | Equivalent | R5 `Substance.identifier` maps as Equivalent to R4 `Substance.identifier` |
| Substance.implicitRules | Substance.implicitRules | Equivalent | R5 `Substance.implicitRules` maps as Equivalent to R4 `Substance.implicitRules` |
| Substance.ingredient | Substance.ingredient | Equivalent | R5 `Substance.ingredient` maps as Equivalent to R4 `Substance.ingredient` |
| Substance.ingredient.extension | Substance.ingredient.extension | SourceIsBroaderThanTarget | R5 `Substance.ingredient.extension` maps as SourceIsBroaderThanTarget to R4 `Substance.ingredient.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Substance.ingredient.id | Substance.ingredient.id | Equivalent | R5 `Substance.ingredient.id` maps as Equivalent to R4 `Substance.ingredient.id` |
| Substance.ingredient.modifierExtension | Substance.ingredient.modifierExtension | SourceIsBroaderThanTarget | R5 `Substance.ingredient.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Substance.ingredient.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Substance.ingredient.quantity | Substance.ingredient.quantity | SourceIsBroaderThanTarget | R5 `Substance.ingredient.quantity` maps as SourceIsBroaderThanTarget to R4 `Substance.ingredient.quantity` - quantity has change due to type change: R5 `quantity` `Ratio` maps as SourceIsBroaderThanTarget for R4 `quantity` |
| Substance.ingredient.substance[x] | Substance.ingredient.substance[x] | Equivalent | R5 `Substance.ingredient.substance[x]` maps as Equivalent to R4 `Substance.ingredient.substance[x]` |
| Substance.instance | Substance.instance | RelatedTo | R5 `Substance.instance` maps as RelatedTo to R4 `Substance.instance` - instance changed from scalar to array (max cardinality from 1 to *); instance has change due to type change: R5 instance boolean has no equivalent or mapped type in R4 instance |
| Substance.language | Substance.language | SourceIsNarrowerThanTarget | R5 `Substance.language` maps as SourceIsNarrowerThanTarget to R4 `Substance.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| Substance.meta | Substance.meta | Equivalent | R5 `Substance.meta` maps as Equivalent to R4 `Substance.meta` |
| Substance.modifierExtension | Substance.modifierExtension | SourceIsBroaderThanTarget | R5 `Substance.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Substance.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Substance.quantity | Substance.instance.quantity | Equivalent | R5 `Substance.quantity` maps as Equivalent to R4 `Substance.instance.quantity` |
| Substance.status | Substance.status | Equivalent | R5 `Substance.status` maps as Equivalent to R4 `Substance.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/substance-status|5.0.0 and http://hl7.org/fhir/ValueSet/substance-status|4.0.1 (Equivalent) |
| Substance.text | Substance.text | Equivalent | R5 `Substance.text` maps as Equivalent to R4 `Substance.text` |

