Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Medication |  | This resource is primarily used for the identification and definition of a medication for the purposes of prescribing, dispensing, and administering a medication as well as for making statements about medication use. | 28 | 14 |
| Target | Medication |  | This resource is primarily used for the identification and definition of a medication, including ingredients, for the purposes of prescribing, dispensing, and administering a medication as well as for making statements about medication use. | 29 | 15 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 5 |
Equivalent | 4 |
RelatedTo | 19 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Medication | Medication | Equivalent | R4B `Medication` maps as Equivalent to R5 `Medication` |
| Medication.amount | - | DoesNotExistInTarget | R4B `Medication.amount` does not appear in the target and has no mapping for `Medication`. |
| Medication.batch | Medication.batch | Equivalent | R4B `Medication.batch` maps as Equivalent to R5 `Medication.batch` |
| Medication.batch.expirationDate | Medication.batch.expirationDate | Equivalent | R4B `Medication.batch.expirationDate` maps as Equivalent to R5 `Medication.batch.expirationDate` |
| Medication.batch.extension | Medication.batch.extension | RelatedTo | R4B `Medication.batch.extension` maps as RelatedTo to R5 `Medication.batch.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Medication.batch.id | Medication.batch.id | Equivalent | R4B `Medication.batch.id` maps as Equivalent to R5 `Medication.batch.id` |
| Medication.batch.lotNumber | Medication.batch.lotNumber | Equivalent | R4B `Medication.batch.lotNumber` maps as Equivalent to R5 `Medication.batch.lotNumber` |
| Medication.batch.modifierExtension | Medication.batch.modifierExtension | RelatedTo | R4B `Medication.batch.modifierExtension` maps as RelatedTo to R5 `Medication.batch.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Medication.code | Medication.code | Equivalent | R4B `Medication.code` maps as Equivalent to R5 `Medication.code` |
| Medication.contained | Medication.contained | Equivalent | R4B `Medication.contained` maps as Equivalent to R5 `Medication.contained` |
| Medication.extension | Medication.extension | RelatedTo | R4B `Medication.extension` maps as RelatedTo to R5 `Medication.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Medication.form | - | DoesNotExistInTarget | R4B `Medication.form` does not appear in the target and has no mapping for `Medication`. |
| Medication.id | Medication.id | Equivalent | R4B `Medication.id` maps as Equivalent to R5 `Medication.id` |
| Medication.identifier | Medication.identifier | Equivalent | R4B `Medication.identifier` maps as Equivalent to R5 `Medication.identifier` |
| Medication.implicitRules | Medication.implicitRules | Equivalent | R4B `Medication.implicitRules` maps as Equivalent to R5 `Medication.implicitRules` |
| Medication.ingredient | Medication.ingredient | Equivalent | R4B `Medication.ingredient` maps as Equivalent to R5 `Medication.ingredient` |
| Medication.ingredient.extension | Medication.ingredient.extension | RelatedTo | R4B `Medication.ingredient.extension` maps as RelatedTo to R5 `Medication.ingredient.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Medication.ingredient.id | Medication.ingredient.id | Equivalent | R4B `Medication.ingredient.id` maps as Equivalent to R5 `Medication.ingredient.id` |
| Medication.ingredient.isActive | Medication.ingredient.isActive | Equivalent | R4B `Medication.ingredient.isActive` maps as Equivalent to R5 `Medication.ingredient.isActive` |
| Medication.ingredient.item[x] | - | DoesNotExistInTarget | R4B `Medication.ingredient.item[x]` does not appear in the target and has no mapping for `Medication`. |
| Medication.ingredient.modifierExtension | Medication.ingredient.modifierExtension | RelatedTo | R4B `Medication.ingredient.modifierExtension` maps as RelatedTo to R5 `Medication.ingredient.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Medication.ingredient.strength | - | DoesNotExistInTarget | R4B `Medication.ingredient.strength` does not appear in the target and has no mapping for `Medication`. |
| Medication.language | Medication.language | RelatedTo | R4B `Medication.language` maps as RelatedTo to R5 `Medication.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Medication.manufacturer | - | DoesNotExistInTarget | R4B `Medication.manufacturer` does not appear in the target and has no mapping for `Medication`. |
| Medication.meta | Medication.meta | Equivalent | R4B `Medication.meta` maps as Equivalent to R5 `Medication.meta` |
| Medication.modifierExtension | Medication.modifierExtension | RelatedTo | R4B `Medication.modifierExtension` maps as RelatedTo to R5 `Medication.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Medication.status | Medication.status | Equivalent | R4B `Medication.status` maps as Equivalent to R5 `Medication.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/medication-status|4.3.0 and http://hl7.org/fhir/ValueSet/medication-status|5.0.0 (Equivalent) |
| Medication.text | Medication.text | Equivalent | R4B `Medication.text` maps as Equivalent to R5 `Medication.text` |

