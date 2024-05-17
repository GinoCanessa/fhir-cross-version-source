Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | PackagedProductDefinition |  | A medically related item or items, in a container or package. | 57 | 34 |
| Target | PackagedProductDefinition |  | A medically related item or items, in a container or package. | 53 | 33 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 30 |
Equivalent | 4 |
RelatedTo | 23 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| PackagedProductDefinition | PackagedProductDefinition | Equivalent | R4B `PackagedProductDefinition` maps as Equivalent to R5 `PackagedProductDefinition` |
| PackagedProductDefinition.characteristic | PackagedProductDefinition.characteristic | RelatedTo | R4B `PackagedProductDefinition.characteristic` maps as RelatedTo to R5 `PackagedProductDefinition.characteristic` - characteristic removed a binding requirement - Example http://hl7.org/fhir/ValueSet/package-characteristic; characteristic has change due to type change: R4B characteristic CodeableConcept has no equivalent or mapped type in R5 characteristic |
| PackagedProductDefinition.contained | PackagedProductDefinition.contained | Equivalent | R4B `PackagedProductDefinition.contained` maps as Equivalent to R5 `PackagedProductDefinition.contained` |
| PackagedProductDefinition.containedItemQuantity | PackagedProductDefinition.containedItemQuantity | Equivalent | R4B `PackagedProductDefinition.containedItemQuantity` maps as Equivalent to R5 `PackagedProductDefinition.containedItemQuantity` |
| PackagedProductDefinition.copackagedIndicator | PackagedProductDefinition.copackagedIndicator | Equivalent | R4B `PackagedProductDefinition.copackagedIndicator` maps as Equivalent to R5 `PackagedProductDefinition.copackagedIndicator` |
| PackagedProductDefinition.description | PackagedProductDefinition.description | Equivalent | R4B `PackagedProductDefinition.description` maps as Equivalent to R5 `PackagedProductDefinition.description` |
| PackagedProductDefinition.extension | PackagedProductDefinition.extension | RelatedTo | R4B `PackagedProductDefinition.extension` maps as RelatedTo to R5 `PackagedProductDefinition.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| PackagedProductDefinition.id | PackagedProductDefinition.id | Equivalent | R4B `PackagedProductDefinition.id` maps as Equivalent to R5 `PackagedProductDefinition.id` |
| PackagedProductDefinition.identifier | PackagedProductDefinition.identifier | Equivalent | R4B `PackagedProductDefinition.identifier` maps as Equivalent to R5 `PackagedProductDefinition.identifier` |
| PackagedProductDefinition.implicitRules | PackagedProductDefinition.implicitRules | Equivalent | R4B `PackagedProductDefinition.implicitRules` maps as Equivalent to R5 `PackagedProductDefinition.implicitRules` |
| PackagedProductDefinition.language | PackagedProductDefinition.language | RelatedTo | R4B `PackagedProductDefinition.language` maps as RelatedTo to R5 `PackagedProductDefinition.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| PackagedProductDefinition.legalStatusOfSupply | PackagedProductDefinition.legalStatusOfSupply | Equivalent | R4B `PackagedProductDefinition.legalStatusOfSupply` maps as Equivalent to R5 `PackagedProductDefinition.legalStatusOfSupply` |
| PackagedProductDefinition.legalStatusOfSupply.code | PackagedProductDefinition.legalStatusOfSupply.code | Equivalent | R4B `PackagedProductDefinition.legalStatusOfSupply.code` maps as Equivalent to R5 `PackagedProductDefinition.legalStatusOfSupply.code` |
| PackagedProductDefinition.legalStatusOfSupply.extension | PackagedProductDefinition.legalStatusOfSupply.extension | RelatedTo | R4B `PackagedProductDefinition.legalStatusOfSupply.extension` maps as RelatedTo to R5 `PackagedProductDefinition.legalStatusOfSupply.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| PackagedProductDefinition.legalStatusOfSupply.id | PackagedProductDefinition.legalStatusOfSupply.id | Equivalent | R4B `PackagedProductDefinition.legalStatusOfSupply.id` maps as Equivalent to R5 `PackagedProductDefinition.legalStatusOfSupply.id` |
| PackagedProductDefinition.legalStatusOfSupply.jurisdiction | PackagedProductDefinition.legalStatusOfSupply.jurisdiction | Equivalent | R4B `PackagedProductDefinition.legalStatusOfSupply.jurisdiction` maps as Equivalent to R5 `PackagedProductDefinition.legalStatusOfSupply.jurisdiction` |
| PackagedProductDefinition.legalStatusOfSupply.modifierExtension | PackagedProductDefinition.legalStatusOfSupply.modifierExtension | RelatedTo | R4B `PackagedProductDefinition.legalStatusOfSupply.modifierExtension` maps as RelatedTo to R5 `PackagedProductDefinition.legalStatusOfSupply.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| PackagedProductDefinition.manufacturer | PackagedProductDefinition.manufacturer | Equivalent | R4B `PackagedProductDefinition.manufacturer` maps as Equivalent to R5 `PackagedProductDefinition.manufacturer` |
| PackagedProductDefinition.marketingStatus | PackagedProductDefinition.marketingStatus | Equivalent | R4B `PackagedProductDefinition.marketingStatus` maps as Equivalent to R5 `PackagedProductDefinition.marketingStatus` |
| PackagedProductDefinition.meta | PackagedProductDefinition.meta | Equivalent | R4B `PackagedProductDefinition.meta` maps as Equivalent to R5 `PackagedProductDefinition.meta` |
| PackagedProductDefinition.modifierExtension | PackagedProductDefinition.modifierExtension | RelatedTo | R4B `PackagedProductDefinition.modifierExtension` maps as RelatedTo to R5 `PackagedProductDefinition.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| PackagedProductDefinition.name | PackagedProductDefinition.name | Equivalent | R4B `PackagedProductDefinition.name` maps as Equivalent to R5 `PackagedProductDefinition.name` |
| PackagedProductDefinition.package | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.alternateMaterial | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.alternateMaterial` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.containedItem | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.containedItem` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.containedItem.amount | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.containedItem.amount` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.containedItem.extension | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.containedItem.extension` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.containedItem.id | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.containedItem.id` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.containedItem.item | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.containedItem.item` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.containedItem.modifierExtension | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.containedItem.modifierExtension` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.extension | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.extension` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.id | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.id` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.identifier | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.identifier` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.manufacturer | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.manufacturer` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.material | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.material` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.modifierExtension | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.modifierExtension` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.package | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.package` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.property | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.property` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.property.extension | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.property.extension` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.property.id | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.property.id` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.property.modifierExtension | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.property.modifierExtension` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.property.type | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.property.type` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.property.value[x] | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.property.value[x]` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.quantity | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.quantity` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.shelfLifeStorage | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.shelfLifeStorage` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.shelfLifeStorage.extension | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.shelfLifeStorage.extension` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.shelfLifeStorage.id | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.shelfLifeStorage.id` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.shelfLifeStorage.modifierExtension | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.shelfLifeStorage.modifierExtension` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.shelfLifeStorage.period[x] | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.shelfLifeStorage.period[x]` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.shelfLifeStorage.specialPrecautionsForStorage | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.shelfLifeStorage.specialPrecautionsForStorage` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.shelfLifeStorage.type | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.shelfLifeStorage.type` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.package.type | - | DoesNotExistInTarget | R4B `PackagedProductDefinition.package.type` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packageFor | PackagedProductDefinition.packageFor | Equivalent | R4B `PackagedProductDefinition.packageFor` maps as Equivalent to R5 `PackagedProductDefinition.packageFor` |
| PackagedProductDefinition.status | PackagedProductDefinition.status | Equivalent | R4B `PackagedProductDefinition.status` maps as Equivalent to R5 `PackagedProductDefinition.status` |
| PackagedProductDefinition.statusDate | PackagedProductDefinition.statusDate | Equivalent | R4B `PackagedProductDefinition.statusDate` maps as Equivalent to R5 `PackagedProductDefinition.statusDate` |
| PackagedProductDefinition.text | PackagedProductDefinition.text | Equivalent | R4B `PackagedProductDefinition.text` maps as Equivalent to R5 `PackagedProductDefinition.text` |
| PackagedProductDefinition.type | PackagedProductDefinition.type | Equivalent | R4B `PackagedProductDefinition.type` maps as Equivalent to R5 `PackagedProductDefinition.type` |

