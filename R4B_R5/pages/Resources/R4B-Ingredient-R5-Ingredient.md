Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Ingredient |  | An ingredient of a manufactured item or pharmaceutical product. | 44 | 24 |
| Target | Ingredient |  | An ingredient of a manufactured item or pharmaceutical product. | 47 | 27 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 40 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Ingredient | Ingredient | Equivalent | R4B `Ingredient` maps as Equivalent to R5 `Ingredient` |
| Ingredient.allergenicIndicator | Ingredient.allergenicIndicator | Equivalent | R4B `Ingredient.allergenicIndicator` maps as Equivalent to R5 `Ingredient.allergenicIndicator` |
| Ingredient.contained | Ingredient.contained | Equivalent | R4B `Ingredient.contained` maps as Equivalent to R5 `Ingredient.contained` |
| Ingredient.extension | Ingredient.extension | RelatedTo | R4B `Ingredient.extension` maps as RelatedTo to R5 `Ingredient.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Ingredient.for | Ingredient.for | Equivalent | R4B `Ingredient.for` maps as Equivalent to R5 `Ingredient.for` |
| Ingredient.function | Ingredient.function | Equivalent | R4B `Ingredient.function` maps as Equivalent to R5 `Ingredient.function` |
| Ingredient.id | Ingredient.id | Equivalent | R4B `Ingredient.id` maps as Equivalent to R5 `Ingredient.id` |
| Ingredient.identifier | Ingredient.identifier | Equivalent | R4B `Ingredient.identifier` maps as Equivalent to R5 `Ingredient.identifier` |
| Ingredient.implicitRules | Ingredient.implicitRules | Equivalent | R4B `Ingredient.implicitRules` maps as Equivalent to R5 `Ingredient.implicitRules` |
| Ingredient.language | Ingredient.language | RelatedTo | R4B `Ingredient.language` maps as RelatedTo to R5 `Ingredient.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Ingredient.manufacturer | Ingredient.manufacturer | Equivalent | R4B `Ingredient.manufacturer` maps as Equivalent to R5 `Ingredient.manufacturer` |
| Ingredient.manufacturer.extension | Ingredient.manufacturer.extension | RelatedTo | R4B `Ingredient.manufacturer.extension` maps as RelatedTo to R5 `Ingredient.manufacturer.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Ingredient.manufacturer.id | Ingredient.manufacturer.id | Equivalent | R4B `Ingredient.manufacturer.id` maps as Equivalent to R5 `Ingredient.manufacturer.id` |
| Ingredient.manufacturer.manufacturer | Ingredient.manufacturer.manufacturer | Equivalent | R4B `Ingredient.manufacturer.manufacturer` maps as Equivalent to R5 `Ingredient.manufacturer.manufacturer` |
| Ingredient.manufacturer.modifierExtension | Ingredient.manufacturer.modifierExtension | RelatedTo | R4B `Ingredient.manufacturer.modifierExtension` maps as RelatedTo to R5 `Ingredient.manufacturer.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Ingredient.manufacturer.role | Ingredient.manufacturer.role | Equivalent | R4B `Ingredient.manufacturer.role` maps as Equivalent to R5 `Ingredient.manufacturer.role` - role has compatible required binding for code type: http://hl7.org/fhir/ValueSet/ingredient-manufacturer-role|4.3.0 and http://hl7.org/fhir/ValueSet/ingredient-manufacturer-role|5.0.0 (Equivalent) |
| Ingredient.meta | Ingredient.meta | Equivalent | R4B `Ingredient.meta` maps as Equivalent to R5 `Ingredient.meta` |
| Ingredient.modifierExtension | Ingredient.modifierExtension | RelatedTo | R4B `Ingredient.modifierExtension` maps as RelatedTo to R5 `Ingredient.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Ingredient.role | Ingredient.role | Equivalent | R4B `Ingredient.role` maps as Equivalent to R5 `Ingredient.role` |
| Ingredient.status | Ingredient.status | Equivalent | R4B `Ingredient.status` maps as Equivalent to R5 `Ingredient.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| Ingredient.substance | Ingredient.substance | Equivalent | R4B `Ingredient.substance` maps as Equivalent to R5 `Ingredient.substance` |
| Ingredient.substance.code | Ingredient.substance.code | Equivalent | R4B `Ingredient.substance.code` maps as Equivalent to R5 `Ingredient.substance.code` |
| Ingredient.substance.extension | Ingredient.substance.extension | RelatedTo | R4B `Ingredient.substance.extension` maps as RelatedTo to R5 `Ingredient.substance.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Ingredient.substance.id | Ingredient.substance.id | Equivalent | R4B `Ingredient.substance.id` maps as Equivalent to R5 `Ingredient.substance.id` |
| Ingredient.substance.modifierExtension | Ingredient.substance.modifierExtension | RelatedTo | R4B `Ingredient.substance.modifierExtension` maps as RelatedTo to R5 `Ingredient.substance.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Ingredient.substance.strength | Ingredient.substance.strength | Equivalent | R4B `Ingredient.substance.strength` maps as Equivalent to R5 `Ingredient.substance.strength` |
| Ingredient.substance.strength.concentration[x] | Ingredient.substance.strength.concentration[x] | SourceIsNarrowerThanTarget | R4B `Ingredient.substance.strength.concentration[x]` maps as SourceIsNarrowerThanTarget to R5 `Ingredient.substance.strength.concentration[x]` - concentration[x] has change due to type change: R4B `concentration[x]` `Ratio` maps as SourceIsNarrowerThanTarget for R5 `concentration[x]` |
| Ingredient.substance.strength.country | Ingredient.substance.strength.country | Equivalent | R4B `Ingredient.substance.strength.country` maps as Equivalent to R5 `Ingredient.substance.strength.country` |
| Ingredient.substance.strength.extension | Ingredient.substance.strength.extension | RelatedTo | R4B `Ingredient.substance.strength.extension` maps as RelatedTo to R5 `Ingredient.substance.strength.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Ingredient.substance.strength.id | Ingredient.substance.strength.id | Equivalent | R4B `Ingredient.substance.strength.id` maps as Equivalent to R5 `Ingredient.substance.strength.id` |
| Ingredient.substance.strength.measurementPoint | Ingredient.substance.strength.measurementPoint | Equivalent | R4B `Ingredient.substance.strength.measurementPoint` maps as Equivalent to R5 `Ingredient.substance.strength.measurementPoint` |
| Ingredient.substance.strength.modifierExtension | Ingredient.substance.strength.modifierExtension | RelatedTo | R4B `Ingredient.substance.strength.modifierExtension` maps as RelatedTo to R5 `Ingredient.substance.strength.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Ingredient.substance.strength.presentation[x] | Ingredient.substance.strength.presentation[x] | SourceIsNarrowerThanTarget | R4B `Ingredient.substance.strength.presentation[x]` maps as SourceIsNarrowerThanTarget to R5 `Ingredient.substance.strength.presentation[x]` - presentation[x] has change due to type change: R4B `presentation[x]` `Ratio` maps as SourceIsNarrowerThanTarget for R5 `presentation[x]` |
| Ingredient.substance.strength.referenceStrength | Ingredient.substance.strength.referenceStrength | Equivalent | R4B `Ingredient.substance.strength.referenceStrength` maps as Equivalent to R5 `Ingredient.substance.strength.referenceStrength` |
| Ingredient.substance.strength.referenceStrength.country | Ingredient.substance.strength.referenceStrength.country | Equivalent | R4B `Ingredient.substance.strength.referenceStrength.country` maps as Equivalent to R5 `Ingredient.substance.strength.referenceStrength.country` |
| Ingredient.substance.strength.referenceStrength.extension | Ingredient.substance.strength.referenceStrength.extension | RelatedTo | R4B `Ingredient.substance.strength.referenceStrength.extension` maps as RelatedTo to R5 `Ingredient.substance.strength.referenceStrength.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Ingredient.substance.strength.referenceStrength.id | Ingredient.substance.strength.referenceStrength.id | Equivalent | R4B `Ingredient.substance.strength.referenceStrength.id` maps as Equivalent to R5 `Ingredient.substance.strength.referenceStrength.id` |
| Ingredient.substance.strength.referenceStrength.measurementPoint | Ingredient.substance.strength.referenceStrength.measurementPoint | Equivalent | R4B `Ingredient.substance.strength.referenceStrength.measurementPoint` maps as Equivalent to R5 `Ingredient.substance.strength.referenceStrength.measurementPoint` |
| Ingredient.substance.strength.referenceStrength.modifierExtension | Ingredient.substance.strength.referenceStrength.modifierExtension | RelatedTo | R4B `Ingredient.substance.strength.referenceStrength.modifierExtension` maps as RelatedTo to R5 `Ingredient.substance.strength.referenceStrength.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Ingredient.substance.strength.referenceStrength.strength[x] | Ingredient.substance.strength.referenceStrength.strength[x] | SourceIsNarrowerThanTarget | R4B `Ingredient.substance.strength.referenceStrength.strength[x]` maps as SourceIsNarrowerThanTarget to R5 `Ingredient.substance.strength.referenceStrength.strength[x]` - strength[x] has change due to type change: R4B `strength[x]` `Ratio` maps as SourceIsNarrowerThanTarget for R5 `strength[x]` |
| Ingredient.substance.strength.referenceStrength.substance | Ingredient.substance.strength.referenceStrength.substance | RelatedTo | R4B `Ingredient.substance.strength.referenceStrength.substance` maps as RelatedTo to R5 `Ingredient.substance.strength.referenceStrength.substance` - substance made the element mandatory; substance increased the minimum cardinality from 0 to 1 |
| Ingredient.substance.strength.textConcentration | Ingredient.substance.strength.textConcentration | Equivalent | R4B `Ingredient.substance.strength.textConcentration` maps as Equivalent to R5 `Ingredient.substance.strength.textConcentration` |
| Ingredient.substance.strength.textPresentation | Ingredient.substance.strength.textPresentation | Equivalent | R4B `Ingredient.substance.strength.textPresentation` maps as Equivalent to R5 `Ingredient.substance.strength.textPresentation` |
| Ingredient.text | Ingredient.text | Equivalent | R4B `Ingredient.text` maps as Equivalent to R5 `Ingredient.text` |

