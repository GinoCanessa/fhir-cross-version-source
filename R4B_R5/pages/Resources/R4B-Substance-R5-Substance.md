Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Substance |  | A homogeneous material with a definite composition. | 27 | 13 |
| Target | Substance |  | A homogeneous material with a definite composition. | 23 | 12 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 6 |
Equivalent | 4 |
RelatedTo | 17 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Substance | Substance | Equivalent | R4B `Substance` maps as Equivalent to R5 `Substance` |
| Substance.category | Substance.category | Equivalent | R4B `Substance.category` maps as Equivalent to R5 `Substance.category` |
| Substance.code | Substance.code | SourceIsBroaderThanTarget | R4B `Substance.code` maps as SourceIsBroaderThanTarget to R5 `Substance.code` - code has change due to type change: R4B code CodeableConcept has no equivalent or mapped type in R5 code |
| Substance.contained | Substance.contained | Equivalent | R4B `Substance.contained` maps as Equivalent to R5 `Substance.contained` |
| Substance.description | Substance.description | SourceIsBroaderThanTarget | R4B `Substance.description` maps as SourceIsBroaderThanTarget to R5 `Substance.description` - description has change due to type change: R4B description string has no equivalent or mapped type in R5 description |
| Substance.extension | Substance.extension | RelatedTo | R4B `Substance.extension` maps as RelatedTo to R5 `Substance.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Substance.id | Substance.id | Equivalent | R4B `Substance.id` maps as Equivalent to R5 `Substance.id` |
| Substance.identifier | Substance.identifier | Equivalent | R4B `Substance.identifier` maps as Equivalent to R5 `Substance.identifier` |
| Substance.implicitRules | Substance.implicitRules | Equivalent | R4B `Substance.implicitRules` maps as Equivalent to R5 `Substance.implicitRules` |
| Substance.ingredient | Substance.ingredient | Equivalent | R4B `Substance.ingredient` maps as Equivalent to R5 `Substance.ingredient` |
| Substance.ingredient.extension | Substance.ingredient.extension | RelatedTo | R4B `Substance.ingredient.extension` maps as RelatedTo to R5 `Substance.ingredient.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Substance.ingredient.id | Substance.ingredient.id | Equivalent | R4B `Substance.ingredient.id` maps as Equivalent to R5 `Substance.ingredient.id` |
| Substance.ingredient.modifierExtension | Substance.ingredient.modifierExtension | RelatedTo | R4B `Substance.ingredient.modifierExtension` maps as RelatedTo to R5 `Substance.ingredient.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Substance.ingredient.quantity | Substance.ingredient.quantity | SourceIsNarrowerThanTarget | R4B `Substance.ingredient.quantity` maps as SourceIsNarrowerThanTarget to R5 `Substance.ingredient.quantity` - quantity has change due to type change: R4B `quantity` `Ratio` maps as SourceIsNarrowerThanTarget for R5 `quantity` |
| Substance.ingredient.substance[x] | Substance.ingredient.substance[x] | Equivalent | R4B `Substance.ingredient.substance[x]` maps as Equivalent to R5 `Substance.ingredient.substance[x]` |
| Substance.instance | Substance.instance | RelatedTo | R4B `Substance.instance` maps as RelatedTo to R5 `Substance.instance` - instance made the element mandatory; instance increased the minimum cardinality from 0 to 1; instance changed from array to scalar (max cardinality from * to 1); instance has change due to type change: R4B instance BackboneElement has no equivalent or mapped type in R5 instance |
| Substance.instance.expiry | - | DoesNotExistInTarget | R4B `Substance.instance.expiry` does not appear in the target and has no mapping for `Substance`. |
| Substance.instance.extension | - | DoesNotExistInTarget | R4B `Substance.instance.extension` does not appear in the target and has no mapping for `Substance`. |
| Substance.instance.id | - | DoesNotExistInTarget | R4B `Substance.instance.id` does not appear in the target and has no mapping for `Substance`. |
| Substance.instance.identifier | - | DoesNotExistInTarget | R4B `Substance.instance.identifier` does not appear in the target and has no mapping for `Substance`. |
| Substance.instance.modifierExtension | - | DoesNotExistInTarget | R4B `Substance.instance.modifierExtension` does not appear in the target and has no mapping for `Substance`. |
| Substance.instance.quantity | - | DoesNotExistInTarget | R4B `Substance.instance.quantity` does not appear in the target and has no mapping for `Substance`. |
| Substance.language | Substance.language | RelatedTo | R4B `Substance.language` maps as RelatedTo to R5 `Substance.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Substance.meta | Substance.meta | Equivalent | R4B `Substance.meta` maps as Equivalent to R5 `Substance.meta` |
| Substance.modifierExtension | Substance.modifierExtension | RelatedTo | R4B `Substance.modifierExtension` maps as RelatedTo to R5 `Substance.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Substance.status | Substance.status | Equivalent | R4B `Substance.status` maps as Equivalent to R5 `Substance.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/substance-status|4.3.0 and http://hl7.org/fhir/ValueSet/substance-status|5.0.0 (Equivalent) |
| Substance.text | Substance.text | Equivalent | R4B `Substance.text` maps as Equivalent to R5 `Substance.text` |

