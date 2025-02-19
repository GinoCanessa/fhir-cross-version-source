Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Medication |  | This resource is primarily used for the identification and definition of a medication, including ingredients, for the purposes of prescribing, dispensing, and administering a medication as well as for making statements about medication use. | 29 | 15 |
| Target | Medication |  | This resource is primarily used for the identification and definition of a medication for the purposes of prescribing, dispensing, and administering a medication as well as for making statements about medication use. | 28 | 14 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 18 |
RelatedTo | 2 |
SourceIsBroaderThanTarget | 7 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Medication | Medication | Equivalent | R5 `Medication` maps as Equivalent to R4 `Medication` |
| Medication.batch | Medication.batch | Equivalent | R5 `Medication.batch` maps as Equivalent to R4 `Medication.batch` |
| Medication.batch.expirationDate | Medication.batch.expirationDate | Equivalent | R5 `Medication.batch.expirationDate` maps as Equivalent to R4 `Medication.batch.expirationDate` |
| Medication.batch.extension | Medication.batch.extension | SourceIsBroaderThanTarget | R5 `Medication.batch.extension` maps as SourceIsBroaderThanTarget to R4 `Medication.batch.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Medication.batch.id | Medication.batch.id | Equivalent | R5 `Medication.batch.id` maps as Equivalent to R4 `Medication.batch.id` |
| Medication.batch.lotNumber | Medication.batch.lotNumber | Equivalent | R5 `Medication.batch.lotNumber` maps as Equivalent to R4 `Medication.batch.lotNumber` |
| Medication.batch.modifierExtension | Medication.batch.modifierExtension | SourceIsBroaderThanTarget | R5 `Medication.batch.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Medication.batch.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Medication.code | Medication.code | Equivalent | R5 `Medication.code` maps as Equivalent to R4 `Medication.code` |
| Medication.contained | Medication.contained | Equivalent | R5 `Medication.contained` maps as Equivalent to R4 `Medication.contained` |
| Medication.definition | - | DoesNotExistInTarget | R5 `Medication.definition` does not appear in the target and has no mapping for `Medication`. |
| Medication.doseForm | Medication.form | Equivalent | R5 `Medication.doseForm` maps as Equivalent to R4 `Medication.form` |
| Medication.extension | Medication.extension | SourceIsBroaderThanTarget | R5 `Medication.extension` maps as SourceIsBroaderThanTarget to R4 `Medication.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Medication.id | Medication.id | Equivalent | R5 `Medication.id` maps as Equivalent to R4 `Medication.id` |
| Medication.identifier | Medication.identifier | Equivalent | R5 `Medication.identifier` maps as Equivalent to R4 `Medication.identifier` |
| Medication.implicitRules | Medication.implicitRules | Equivalent | R5 `Medication.implicitRules` maps as Equivalent to R4 `Medication.implicitRules` |
| Medication.ingredient | Medication.ingredient | Equivalent | R5 `Medication.ingredient` maps as Equivalent to R4 `Medication.ingredient` |
| Medication.ingredient.extension | Medication.ingredient.extension | SourceIsBroaderThanTarget | R5 `Medication.ingredient.extension` maps as SourceIsBroaderThanTarget to R4 `Medication.ingredient.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Medication.ingredient.id | Medication.ingredient.id | Equivalent | R5 `Medication.ingredient.id` maps as Equivalent to R4 `Medication.ingredient.id` |
| Medication.ingredient.isActive | Medication.ingredient.isActive | Equivalent | R5 `Medication.ingredient.isActive` maps as Equivalent to R4 `Medication.ingredient.isActive` |
| Medication.ingredient.item | Medication.ingredient.item[x] | RelatedTo | R5 `Medication.ingredient.item` maps as RelatedTo to R4 `Medication.ingredient.item[x]` - item[x] removed a binding requirement - Example http://hl7.org/fhir/ValueSet/medication-codes; item[x] has change due to type change: R5 item CodeableReference has no equivalent or mapped type in R4 item[x] |
| Medication.ingredient.modifierExtension | Medication.ingredient.modifierExtension | SourceIsBroaderThanTarget | R5 `Medication.ingredient.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Medication.ingredient.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Medication.ingredient.strength[x] | Medication.ingredient.strength | RelatedTo | R5 `Medication.ingredient.strength[x]` maps as RelatedTo to R4 `Medication.ingredient.strength` - strength removed a binding requirement - Preferred http://hl7.org/fhir/ValueSet/medication-ingredientstrength; strength has change due to type change: R5 `strength[x]` `Ratio` maps as RelatedTo for R4 `strength`; strength has change due to type change: R5 strength[x] CodeableConcept has no equivalent or mapped type in R4 strength; strength has change due to type change: R5 strength[x] Quantity has no equivalent or mapped type in R4 strength |
| Medication.language | Medication.language | SourceIsNarrowerThanTarget | R5 `Medication.language` maps as SourceIsNarrowerThanTarget to R4 `Medication.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| Medication.marketingAuthorizationHolder | Medication.manufacturer | Equivalent | R5 `Medication.marketingAuthorizationHolder` maps as Equivalent to R4 `Medication.manufacturer` |
| Medication.meta | Medication.meta | Equivalent | R5 `Medication.meta` maps as Equivalent to R4 `Medication.meta` |
| Medication.modifierExtension | Medication.modifierExtension | SourceIsBroaderThanTarget | R5 `Medication.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Medication.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Medication.status | Medication.status | Equivalent | R5 `Medication.status` maps as Equivalent to R4 `Medication.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/medication-status|5.0.0 and http://hl7.org/fhir/ValueSet/medication-status|4.0.1 (Equivalent) |
| Medication.text | Medication.text | Equivalent | R5 `Medication.text` maps as Equivalent to R4 `Medication.text` |
| Medication.totalVolume | Medication.amount | SourceIsBroaderThanTarget | R5 `Medication.totalVolume` maps as SourceIsBroaderThanTarget to R4 `Medication.amount` - amount has change due to type change: R5 totalVolume Quantity has no equivalent or mapped type in R4 amount |

