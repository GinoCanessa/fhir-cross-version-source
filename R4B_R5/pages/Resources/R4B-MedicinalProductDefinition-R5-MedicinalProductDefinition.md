Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | MedicinalProductDefinition |  | Detailed definition of a medicinal product, typically for uses other than direct patient care (e.g. regulatory use, drug catalogs, to support prescribing, adverse events management etc.). | 77 | 48 |
| Target | MedicinalProductDefinition |  | Detailed definition of a medicinal product, typically for uses other than direct patient care (e.g. regulatory use, drug catalogs, to support prescribing, adverse events management etc.). | 78 | 49 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 13 |
Equivalent | 4 |
RelatedTo | 60 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| MedicinalProductDefinition | MedicinalProductDefinition | Equivalent | R4B `MedicinalProductDefinition` maps as Equivalent to R5 `MedicinalProductDefinition` |
| MedicinalProductDefinition.additionalMonitoringIndicator | MedicinalProductDefinition.additionalMonitoringIndicator | Equivalent | R4B `MedicinalProductDefinition.additionalMonitoringIndicator` maps as Equivalent to R5 `MedicinalProductDefinition.additionalMonitoringIndicator` |
| MedicinalProductDefinition.attachedDocument | MedicinalProductDefinition.attachedDocument | Equivalent | R4B `MedicinalProductDefinition.attachedDocument` maps as Equivalent to R5 `MedicinalProductDefinition.attachedDocument` |
| MedicinalProductDefinition.characteristic | MedicinalProductDefinition.characteristic | Equivalent | R4B `MedicinalProductDefinition.characteristic` maps as Equivalent to R5 `MedicinalProductDefinition.characteristic` |
| MedicinalProductDefinition.characteristic.extension | MedicinalProductDefinition.characteristic.extension | RelatedTo | R4B `MedicinalProductDefinition.characteristic.extension` maps as RelatedTo to R5 `MedicinalProductDefinition.characteristic.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MedicinalProductDefinition.characteristic.id | MedicinalProductDefinition.characteristic.id | Equivalent | R4B `MedicinalProductDefinition.characteristic.id` maps as Equivalent to R5 `MedicinalProductDefinition.characteristic.id` |
| MedicinalProductDefinition.characteristic.modifierExtension | MedicinalProductDefinition.characteristic.modifierExtension | RelatedTo | R4B `MedicinalProductDefinition.characteristic.modifierExtension` maps as RelatedTo to R5 `MedicinalProductDefinition.characteristic.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MedicinalProductDefinition.characteristic.type | MedicinalProductDefinition.characteristic.type | Equivalent | R4B `MedicinalProductDefinition.characteristic.type` maps as Equivalent to R5 `MedicinalProductDefinition.characteristic.type` |
| MedicinalProductDefinition.characteristic.value[x] | MedicinalProductDefinition.characteristic.value[x] | RelatedTo | R4B `MedicinalProductDefinition.characteristic.value[x]` maps as RelatedTo to R5 `MedicinalProductDefinition.characteristic.value[x]` - value[x] has change due to type change: R4B `value[x]` `Attachment` maps as RelatedTo for R5 `value[x]` |
| MedicinalProductDefinition.classification | MedicinalProductDefinition.classification | Equivalent | R4B `MedicinalProductDefinition.classification` maps as Equivalent to R5 `MedicinalProductDefinition.classification` |
| MedicinalProductDefinition.clinicalTrial | MedicinalProductDefinition.clinicalTrial | Equivalent | R4B `MedicinalProductDefinition.clinicalTrial` maps as Equivalent to R5 `MedicinalProductDefinition.clinicalTrial` |
| MedicinalProductDefinition.code | MedicinalProductDefinition.code | Equivalent | R4B `MedicinalProductDefinition.code` maps as Equivalent to R5 `MedicinalProductDefinition.code` |
| MedicinalProductDefinition.combinedPharmaceuticalDoseForm | MedicinalProductDefinition.combinedPharmaceuticalDoseForm | Equivalent | R4B `MedicinalProductDefinition.combinedPharmaceuticalDoseForm` maps as Equivalent to R5 `MedicinalProductDefinition.combinedPharmaceuticalDoseForm` |
| MedicinalProductDefinition.contact | MedicinalProductDefinition.contact | Equivalent | R4B `MedicinalProductDefinition.contact` maps as Equivalent to R5 `MedicinalProductDefinition.contact` |
| MedicinalProductDefinition.contact.contact | MedicinalProductDefinition.contact.contact | Equivalent | R4B `MedicinalProductDefinition.contact.contact` maps as Equivalent to R5 `MedicinalProductDefinition.contact.contact` |
| MedicinalProductDefinition.contact.extension | MedicinalProductDefinition.contact.extension | RelatedTo | R4B `MedicinalProductDefinition.contact.extension` maps as RelatedTo to R5 `MedicinalProductDefinition.contact.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MedicinalProductDefinition.contact.id | MedicinalProductDefinition.contact.id | Equivalent | R4B `MedicinalProductDefinition.contact.id` maps as Equivalent to R5 `MedicinalProductDefinition.contact.id` |
| MedicinalProductDefinition.contact.modifierExtension | MedicinalProductDefinition.contact.modifierExtension | RelatedTo | R4B `MedicinalProductDefinition.contact.modifierExtension` maps as RelatedTo to R5 `MedicinalProductDefinition.contact.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MedicinalProductDefinition.contact.type | MedicinalProductDefinition.contact.type | Equivalent | R4B `MedicinalProductDefinition.contact.type` maps as Equivalent to R5 `MedicinalProductDefinition.contact.type` |
| MedicinalProductDefinition.contained | MedicinalProductDefinition.contained | Equivalent | R4B `MedicinalProductDefinition.contained` maps as Equivalent to R5 `MedicinalProductDefinition.contained` |
| MedicinalProductDefinition.crossReference | MedicinalProductDefinition.crossReference | Equivalent | R4B `MedicinalProductDefinition.crossReference` maps as Equivalent to R5 `MedicinalProductDefinition.crossReference` |
| MedicinalProductDefinition.crossReference.extension | MedicinalProductDefinition.crossReference.extension | RelatedTo | R4B `MedicinalProductDefinition.crossReference.extension` maps as RelatedTo to R5 `MedicinalProductDefinition.crossReference.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MedicinalProductDefinition.crossReference.id | MedicinalProductDefinition.crossReference.id | Equivalent | R4B `MedicinalProductDefinition.crossReference.id` maps as Equivalent to R5 `MedicinalProductDefinition.crossReference.id` |
| MedicinalProductDefinition.crossReference.modifierExtension | MedicinalProductDefinition.crossReference.modifierExtension | RelatedTo | R4B `MedicinalProductDefinition.crossReference.modifierExtension` maps as RelatedTo to R5 `MedicinalProductDefinition.crossReference.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MedicinalProductDefinition.crossReference.product | MedicinalProductDefinition.crossReference.product | Equivalent | R4B `MedicinalProductDefinition.crossReference.product` maps as Equivalent to R5 `MedicinalProductDefinition.crossReference.product` |
| MedicinalProductDefinition.crossReference.type | MedicinalProductDefinition.crossReference.type | Equivalent | R4B `MedicinalProductDefinition.crossReference.type` maps as Equivalent to R5 `MedicinalProductDefinition.crossReference.type` |
| MedicinalProductDefinition.description | MedicinalProductDefinition.description | Equivalent | R4B `MedicinalProductDefinition.description` maps as Equivalent to R5 `MedicinalProductDefinition.description` |
| MedicinalProductDefinition.domain | MedicinalProductDefinition.domain | Equivalent | R4B `MedicinalProductDefinition.domain` maps as Equivalent to R5 `MedicinalProductDefinition.domain` |
| MedicinalProductDefinition.extension | MedicinalProductDefinition.extension | RelatedTo | R4B `MedicinalProductDefinition.extension` maps as RelatedTo to R5 `MedicinalProductDefinition.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MedicinalProductDefinition.id | MedicinalProductDefinition.id | Equivalent | R4B `MedicinalProductDefinition.id` maps as Equivalent to R5 `MedicinalProductDefinition.id` |
| MedicinalProductDefinition.identifier | MedicinalProductDefinition.identifier | Equivalent | R4B `MedicinalProductDefinition.identifier` maps as Equivalent to R5 `MedicinalProductDefinition.identifier` |
| MedicinalProductDefinition.implicitRules | MedicinalProductDefinition.implicitRules | Equivalent | R4B `MedicinalProductDefinition.implicitRules` maps as Equivalent to R5 `MedicinalProductDefinition.implicitRules` |
| MedicinalProductDefinition.impurity | MedicinalProductDefinition.impurity | Equivalent | R4B `MedicinalProductDefinition.impurity` maps as Equivalent to R5 `MedicinalProductDefinition.impurity` |
| MedicinalProductDefinition.indication | MedicinalProductDefinition.indication | Equivalent | R4B `MedicinalProductDefinition.indication` maps as Equivalent to R5 `MedicinalProductDefinition.indication` |
| MedicinalProductDefinition.ingredient | MedicinalProductDefinition.ingredient | Equivalent | R4B `MedicinalProductDefinition.ingredient` maps as Equivalent to R5 `MedicinalProductDefinition.ingredient` |
| MedicinalProductDefinition.language | MedicinalProductDefinition.language | RelatedTo | R4B `MedicinalProductDefinition.language` maps as RelatedTo to R5 `MedicinalProductDefinition.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| MedicinalProductDefinition.legalStatusOfSupply | MedicinalProductDefinition.legalStatusOfSupply | Equivalent | R4B `MedicinalProductDefinition.legalStatusOfSupply` maps as Equivalent to R5 `MedicinalProductDefinition.legalStatusOfSupply` |
| MedicinalProductDefinition.marketingStatus | MedicinalProductDefinition.marketingStatus | Equivalent | R4B `MedicinalProductDefinition.marketingStatus` maps as Equivalent to R5 `MedicinalProductDefinition.marketingStatus` |
| MedicinalProductDefinition.masterFile | MedicinalProductDefinition.masterFile | Equivalent | R4B `MedicinalProductDefinition.masterFile` maps as Equivalent to R5 `MedicinalProductDefinition.masterFile` |
| MedicinalProductDefinition.meta | MedicinalProductDefinition.meta | Equivalent | R4B `MedicinalProductDefinition.meta` maps as Equivalent to R5 `MedicinalProductDefinition.meta` |
| MedicinalProductDefinition.modifierExtension | MedicinalProductDefinition.modifierExtension | RelatedTo | R4B `MedicinalProductDefinition.modifierExtension` maps as RelatedTo to R5 `MedicinalProductDefinition.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MedicinalProductDefinition.name | MedicinalProductDefinition.name | Equivalent | R4B `MedicinalProductDefinition.name` maps as Equivalent to R5 `MedicinalProductDefinition.name` |
| MedicinalProductDefinition.name.countryLanguage | - | DoesNotExistInTarget | R4B `MedicinalProductDefinition.name.countryLanguage` does not appear in the target and has no mapping for `MedicinalProductDefinition`. |
| MedicinalProductDefinition.name.countryLanguage.country | - | DoesNotExistInTarget | R4B `MedicinalProductDefinition.name.countryLanguage.country` does not appear in the target and has no mapping for `MedicinalProductDefinition`. |
| MedicinalProductDefinition.name.countryLanguage.extension | - | DoesNotExistInTarget | R4B `MedicinalProductDefinition.name.countryLanguage.extension` does not appear in the target and has no mapping for `MedicinalProductDefinition`. |
| MedicinalProductDefinition.name.countryLanguage.id | - | DoesNotExistInTarget | R4B `MedicinalProductDefinition.name.countryLanguage.id` does not appear in the target and has no mapping for `MedicinalProductDefinition`. |
| MedicinalProductDefinition.name.countryLanguage.jurisdiction | - | DoesNotExistInTarget | R4B `MedicinalProductDefinition.name.countryLanguage.jurisdiction` does not appear in the target and has no mapping for `MedicinalProductDefinition`. |
| MedicinalProductDefinition.name.countryLanguage.language | - | DoesNotExistInTarget | R4B `MedicinalProductDefinition.name.countryLanguage.language` does not appear in the target and has no mapping for `MedicinalProductDefinition`. |
| MedicinalProductDefinition.name.countryLanguage.modifierExtension | - | DoesNotExistInTarget | R4B `MedicinalProductDefinition.name.countryLanguage.modifierExtension` does not appear in the target and has no mapping for `MedicinalProductDefinition`. |
| MedicinalProductDefinition.name.extension | MedicinalProductDefinition.name.extension | RelatedTo | R4B `MedicinalProductDefinition.name.extension` maps as RelatedTo to R5 `MedicinalProductDefinition.name.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MedicinalProductDefinition.name.id | MedicinalProductDefinition.name.id | Equivalent | R4B `MedicinalProductDefinition.name.id` maps as Equivalent to R5 `MedicinalProductDefinition.name.id` |
| MedicinalProductDefinition.name.modifierExtension | MedicinalProductDefinition.name.modifierExtension | RelatedTo | R4B `MedicinalProductDefinition.name.modifierExtension` maps as RelatedTo to R5 `MedicinalProductDefinition.name.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MedicinalProductDefinition.name.namePart | - | DoesNotExistInTarget | R4B `MedicinalProductDefinition.name.namePart` does not appear in the target and has no mapping for `MedicinalProductDefinition`. |
| MedicinalProductDefinition.name.namePart.extension | - | DoesNotExistInTarget | R4B `MedicinalProductDefinition.name.namePart.extension` does not appear in the target and has no mapping for `MedicinalProductDefinition`. |
| MedicinalProductDefinition.name.namePart.id | - | DoesNotExistInTarget | R4B `MedicinalProductDefinition.name.namePart.id` does not appear in the target and has no mapping for `MedicinalProductDefinition`. |
| MedicinalProductDefinition.name.namePart.modifierExtension | - | DoesNotExistInTarget | R4B `MedicinalProductDefinition.name.namePart.modifierExtension` does not appear in the target and has no mapping for `MedicinalProductDefinition`. |
| MedicinalProductDefinition.name.namePart.part | - | DoesNotExistInTarget | R4B `MedicinalProductDefinition.name.namePart.part` does not appear in the target and has no mapping for `MedicinalProductDefinition`. |
| MedicinalProductDefinition.name.namePart.type | - | DoesNotExistInTarget | R4B `MedicinalProductDefinition.name.namePart.type` does not appear in the target and has no mapping for `MedicinalProductDefinition`. |
| MedicinalProductDefinition.name.productName | MedicinalProductDefinition.name.productName | Equivalent | R4B `MedicinalProductDefinition.name.productName` maps as Equivalent to R5 `MedicinalProductDefinition.name.productName` |
| MedicinalProductDefinition.name.type | MedicinalProductDefinition.name.type | Equivalent | R4B `MedicinalProductDefinition.name.type` maps as Equivalent to R5 `MedicinalProductDefinition.name.type` |
| MedicinalProductDefinition.operation | MedicinalProductDefinition.operation | Equivalent | R4B `MedicinalProductDefinition.operation` maps as Equivalent to R5 `MedicinalProductDefinition.operation` |
| MedicinalProductDefinition.operation.confidentialityIndicator | MedicinalProductDefinition.operation.confidentialityIndicator | Equivalent | R4B `MedicinalProductDefinition.operation.confidentialityIndicator` maps as Equivalent to R5 `MedicinalProductDefinition.operation.confidentialityIndicator` |
| MedicinalProductDefinition.operation.effectiveDate | MedicinalProductDefinition.operation.effectiveDate | Equivalent | R4B `MedicinalProductDefinition.operation.effectiveDate` maps as Equivalent to R5 `MedicinalProductDefinition.operation.effectiveDate` |
| MedicinalProductDefinition.operation.extension | MedicinalProductDefinition.operation.extension | RelatedTo | R4B `MedicinalProductDefinition.operation.extension` maps as RelatedTo to R5 `MedicinalProductDefinition.operation.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MedicinalProductDefinition.operation.id | MedicinalProductDefinition.operation.id | Equivalent | R4B `MedicinalProductDefinition.operation.id` maps as Equivalent to R5 `MedicinalProductDefinition.operation.id` |
| MedicinalProductDefinition.operation.modifierExtension | MedicinalProductDefinition.operation.modifierExtension | RelatedTo | R4B `MedicinalProductDefinition.operation.modifierExtension` maps as RelatedTo to R5 `MedicinalProductDefinition.operation.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MedicinalProductDefinition.operation.organization | MedicinalProductDefinition.operation.organization | Equivalent | R4B `MedicinalProductDefinition.operation.organization` maps as Equivalent to R5 `MedicinalProductDefinition.operation.organization` |
| MedicinalProductDefinition.operation.type | MedicinalProductDefinition.operation.type | Equivalent | R4B `MedicinalProductDefinition.operation.type` maps as Equivalent to R5 `MedicinalProductDefinition.operation.type` |
| MedicinalProductDefinition.packagedMedicinalProduct | MedicinalProductDefinition.packagedMedicinalProduct | Equivalent | R4B `MedicinalProductDefinition.packagedMedicinalProduct` maps as Equivalent to R5 `MedicinalProductDefinition.packagedMedicinalProduct` |
| MedicinalProductDefinition.pediatricUseIndicator | MedicinalProductDefinition.pediatricUseIndicator | Equivalent | R4B `MedicinalProductDefinition.pediatricUseIndicator` maps as Equivalent to R5 `MedicinalProductDefinition.pediatricUseIndicator` |
| MedicinalProductDefinition.route | MedicinalProductDefinition.route | Equivalent | R4B `MedicinalProductDefinition.route` maps as Equivalent to R5 `MedicinalProductDefinition.route` |
| MedicinalProductDefinition.specialMeasures | MedicinalProductDefinition.specialMeasures | Equivalent | R4B `MedicinalProductDefinition.specialMeasures` maps as Equivalent to R5 `MedicinalProductDefinition.specialMeasures` |
| MedicinalProductDefinition.status | MedicinalProductDefinition.status | Equivalent | R4B `MedicinalProductDefinition.status` maps as Equivalent to R5 `MedicinalProductDefinition.status` |
| MedicinalProductDefinition.statusDate | MedicinalProductDefinition.statusDate | Equivalent | R4B `MedicinalProductDefinition.statusDate` maps as Equivalent to R5 `MedicinalProductDefinition.statusDate` |
| MedicinalProductDefinition.text | MedicinalProductDefinition.text | Equivalent | R4B `MedicinalProductDefinition.text` maps as Equivalent to R5 `MedicinalProductDefinition.text` |
| MedicinalProductDefinition.type | MedicinalProductDefinition.type | Equivalent | R4B `MedicinalProductDefinition.type` maps as Equivalent to R5 `MedicinalProductDefinition.type` |
| MedicinalProductDefinition.version | MedicinalProductDefinition.version | Equivalent | R4B `MedicinalProductDefinition.version` maps as Equivalent to R5 `MedicinalProductDefinition.version` |

