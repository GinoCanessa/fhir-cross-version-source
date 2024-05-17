Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | PackagedProductDefinition |  | A medically related item or items, in a container or package. | 53 | 33 |
| Target | PackagedProductDefinition |  | A medically related item or items, in a container or package. | 57 | 34 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 26 |
Equivalent | 4 |
RelatedTo | 23 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| PackagedProductDefinition | PackagedProductDefinition | Equivalent | R5 `PackagedProductDefinition` maps as Equivalent to R4B `PackagedProductDefinition` |
| PackagedProductDefinition.attachedDocument | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.attachedDocument` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.characteristic | PackagedProductDefinition.characteristic | RelatedTo | R5 `PackagedProductDefinition.characteristic` maps as RelatedTo to R4B `PackagedProductDefinition.characteristic` - characteristic added a binding requirement - Example http://hl7.org/fhir/ValueSet/package-characteristic |
| PackagedProductDefinition.contained | PackagedProductDefinition.contained | Equivalent | R5 `PackagedProductDefinition.contained` maps as Equivalent to R4B `PackagedProductDefinition.contained` |
| PackagedProductDefinition.containedItemQuantity | PackagedProductDefinition.containedItemQuantity | Equivalent | R5 `PackagedProductDefinition.containedItemQuantity` maps as Equivalent to R4B `PackagedProductDefinition.containedItemQuantity` |
| PackagedProductDefinition.copackagedIndicator | PackagedProductDefinition.copackagedIndicator | Equivalent | R5 `PackagedProductDefinition.copackagedIndicator` maps as Equivalent to R4B `PackagedProductDefinition.copackagedIndicator` |
| PackagedProductDefinition.description | PackagedProductDefinition.description | Equivalent | R5 `PackagedProductDefinition.description` maps as Equivalent to R4B `PackagedProductDefinition.description` |
| PackagedProductDefinition.extension | PackagedProductDefinition.extension | SourceIsBroaderThanTarget | R5 `PackagedProductDefinition.extension` maps as SourceIsBroaderThanTarget to R4B `PackagedProductDefinition.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| PackagedProductDefinition.id | PackagedProductDefinition.id | Equivalent | R5 `PackagedProductDefinition.id` maps as Equivalent to R4B `PackagedProductDefinition.id` |
| PackagedProductDefinition.identifier | PackagedProductDefinition.identifier | Equivalent | R5 `PackagedProductDefinition.identifier` maps as Equivalent to R4B `PackagedProductDefinition.identifier` |
| PackagedProductDefinition.implicitRules | PackagedProductDefinition.implicitRules | Equivalent | R5 `PackagedProductDefinition.implicitRules` maps as Equivalent to R4B `PackagedProductDefinition.implicitRules` |
| PackagedProductDefinition.language | PackagedProductDefinition.language | RelatedTo | R5 `PackagedProductDefinition.language` maps as RelatedTo to R4B `PackagedProductDefinition.language` - language changed the binding strength from Required to Preferred |
| PackagedProductDefinition.legalStatusOfSupply | PackagedProductDefinition.legalStatusOfSupply | Equivalent | R5 `PackagedProductDefinition.legalStatusOfSupply` maps as Equivalent to R4B `PackagedProductDefinition.legalStatusOfSupply` |
| PackagedProductDefinition.legalStatusOfSupply.code | PackagedProductDefinition.legalStatusOfSupply.code | Equivalent | R5 `PackagedProductDefinition.legalStatusOfSupply.code` maps as Equivalent to R4B `PackagedProductDefinition.legalStatusOfSupply.code` |
| PackagedProductDefinition.legalStatusOfSupply.extension | PackagedProductDefinition.legalStatusOfSupply.extension | SourceIsBroaderThanTarget | R5 `PackagedProductDefinition.legalStatusOfSupply.extension` maps as SourceIsBroaderThanTarget to R4B `PackagedProductDefinition.legalStatusOfSupply.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| PackagedProductDefinition.legalStatusOfSupply.id | PackagedProductDefinition.legalStatusOfSupply.id | Equivalent | R5 `PackagedProductDefinition.legalStatusOfSupply.id` maps as Equivalent to R4B `PackagedProductDefinition.legalStatusOfSupply.id` |
| PackagedProductDefinition.legalStatusOfSupply.jurisdiction | PackagedProductDefinition.legalStatusOfSupply.jurisdiction | Equivalent | R5 `PackagedProductDefinition.legalStatusOfSupply.jurisdiction` maps as Equivalent to R4B `PackagedProductDefinition.legalStatusOfSupply.jurisdiction` |
| PackagedProductDefinition.legalStatusOfSupply.modifierExtension | PackagedProductDefinition.legalStatusOfSupply.modifierExtension | SourceIsBroaderThanTarget | R5 `PackagedProductDefinition.legalStatusOfSupply.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `PackagedProductDefinition.legalStatusOfSupply.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| PackagedProductDefinition.manufacturer | PackagedProductDefinition.manufacturer | Equivalent | R5 `PackagedProductDefinition.manufacturer` maps as Equivalent to R4B `PackagedProductDefinition.manufacturer` |
| PackagedProductDefinition.marketingStatus | PackagedProductDefinition.marketingStatus | Equivalent | R5 `PackagedProductDefinition.marketingStatus` maps as Equivalent to R4B `PackagedProductDefinition.marketingStatus` |
| PackagedProductDefinition.meta | PackagedProductDefinition.meta | Equivalent | R5 `PackagedProductDefinition.meta` maps as Equivalent to R4B `PackagedProductDefinition.meta` |
| PackagedProductDefinition.modifierExtension | PackagedProductDefinition.modifierExtension | SourceIsBroaderThanTarget | R5 `PackagedProductDefinition.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `PackagedProductDefinition.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| PackagedProductDefinition.name | PackagedProductDefinition.name | Equivalent | R5 `PackagedProductDefinition.name` maps as Equivalent to R4B `PackagedProductDefinition.name` |
| PackagedProductDefinition.packageFor | PackagedProductDefinition.packageFor | Equivalent | R5 `PackagedProductDefinition.packageFor` maps as Equivalent to R4B `PackagedProductDefinition.packageFor` |
| PackagedProductDefinition.packaging | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packaging.alternateMaterial | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging.alternateMaterial` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packaging.componentPart | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging.componentPart` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packaging.containedItem | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging.containedItem` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packaging.containedItem.amount | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging.containedItem.amount` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packaging.containedItem.extension | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging.containedItem.extension` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packaging.containedItem.id | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging.containedItem.id` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packaging.containedItem.item | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging.containedItem.item` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packaging.containedItem.modifierExtension | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging.containedItem.modifierExtension` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packaging.extension | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging.extension` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packaging.id | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging.id` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packaging.identifier | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging.identifier` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packaging.manufacturer | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging.manufacturer` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packaging.material | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging.material` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packaging.modifierExtension | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging.modifierExtension` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packaging.packaging | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging.packaging` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packaging.property | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging.property` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packaging.property.extension | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging.property.extension` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packaging.property.id | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging.property.id` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packaging.property.modifierExtension | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging.property.modifierExtension` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packaging.property.type | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging.property.type` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packaging.property.value[x] | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging.property.value[x]` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packaging.quantity | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging.quantity` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packaging.shelfLifeStorage | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging.shelfLifeStorage` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.packaging.type | - | DoesNotExistInTarget | R5 `PackagedProductDefinition.packaging.type` does not appear in the target and has no mapping for `PackagedProductDefinition`. |
| PackagedProductDefinition.status | PackagedProductDefinition.status | Equivalent | R5 `PackagedProductDefinition.status` maps as Equivalent to R4B `PackagedProductDefinition.status` |
| PackagedProductDefinition.statusDate | PackagedProductDefinition.statusDate | Equivalent | R5 `PackagedProductDefinition.statusDate` maps as Equivalent to R4B `PackagedProductDefinition.statusDate` |
| PackagedProductDefinition.text | PackagedProductDefinition.text | Equivalent | R5 `PackagedProductDefinition.text` maps as Equivalent to R4B `PackagedProductDefinition.text` |
| PackagedProductDefinition.type | PackagedProductDefinition.type | Equivalent | R5 `PackagedProductDefinition.type` maps as Equivalent to R4B `PackagedProductDefinition.type` |

