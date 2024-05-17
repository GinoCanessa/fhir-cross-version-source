Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | DeviceDefinition |  | The characteristics, operational status and capabilities of a medical-related component of a medical device. | 64 | 38 |
| Target | DeviceDefinition |  | This is a specialized resource that defines the characteristics and capabilities of a device. | 135 | 79 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 21 |
Equivalent | 4 |
RelatedTo | 39 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| DeviceDefinition | DeviceDefinition | Equivalent | R4B `DeviceDefinition` maps as Equivalent to R5 `DeviceDefinition` |
| DeviceDefinition.capability | - | DoesNotExistInTarget | R4B `DeviceDefinition.capability` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.capability.description | - | DoesNotExistInTarget | R4B `DeviceDefinition.capability.description` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.capability.extension | - | DoesNotExistInTarget | R4B `DeviceDefinition.capability.extension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.capability.id | - | DoesNotExistInTarget | R4B `DeviceDefinition.capability.id` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.capability.modifierExtension | - | DoesNotExistInTarget | R4B `DeviceDefinition.capability.modifierExtension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.capability.type | - | DoesNotExistInTarget | R4B `DeviceDefinition.capability.type` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.contact | DeviceDefinition.contact | Equivalent | R4B `DeviceDefinition.contact` maps as Equivalent to R5 `DeviceDefinition.contact` |
| DeviceDefinition.contained | DeviceDefinition.contained | Equivalent | R4B `DeviceDefinition.contained` maps as Equivalent to R5 `DeviceDefinition.contained` |
| DeviceDefinition.deviceName | DeviceDefinition.deviceName | Equivalent | R4B `DeviceDefinition.deviceName` maps as Equivalent to R5 `DeviceDefinition.deviceName` |
| DeviceDefinition.deviceName.extension | DeviceDefinition.deviceName.extension | RelatedTo | R4B `DeviceDefinition.deviceName.extension` maps as RelatedTo to R5 `DeviceDefinition.deviceName.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| DeviceDefinition.deviceName.id | DeviceDefinition.deviceName.id | Equivalent | R4B `DeviceDefinition.deviceName.id` maps as Equivalent to R5 `DeviceDefinition.deviceName.id` |
| DeviceDefinition.deviceName.modifierExtension | DeviceDefinition.deviceName.modifierExtension | RelatedTo | R4B `DeviceDefinition.deviceName.modifierExtension` maps as RelatedTo to R5 `DeviceDefinition.deviceName.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| DeviceDefinition.deviceName.name | DeviceDefinition.deviceName.name | Equivalent | R4B `DeviceDefinition.deviceName.name` maps as Equivalent to R5 `DeviceDefinition.deviceName.name` |
| DeviceDefinition.deviceName.type | DeviceDefinition.deviceName.type | SourceIsNarrowerThanTarget | R4B `DeviceDefinition.deviceName.type` maps as SourceIsNarrowerThanTarget to R5 `DeviceDefinition.deviceName.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/device-nametype|4.3.0 and http://hl7.org/fhir/ValueSet/device-nametype|5.0.0 (SourceIsNarrowerThanTarget) |
| DeviceDefinition.extension | DeviceDefinition.extension | RelatedTo | R4B `DeviceDefinition.extension` maps as RelatedTo to R5 `DeviceDefinition.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| DeviceDefinition.id | DeviceDefinition.id | Equivalent | R4B `DeviceDefinition.id` maps as Equivalent to R5 `DeviceDefinition.id` |
| DeviceDefinition.identifier | DeviceDefinition.identifier | Equivalent | R4B `DeviceDefinition.identifier` maps as Equivalent to R5 `DeviceDefinition.identifier` |
| DeviceDefinition.implicitRules | DeviceDefinition.implicitRules | Equivalent | R4B `DeviceDefinition.implicitRules` maps as Equivalent to R5 `DeviceDefinition.implicitRules` |
| DeviceDefinition.language | DeviceDefinition.language | RelatedTo | R4B `DeviceDefinition.language` maps as RelatedTo to R5 `DeviceDefinition.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| DeviceDefinition.languageCode | DeviceDefinition.languageCode | Equivalent | R4B `DeviceDefinition.languageCode` maps as Equivalent to R5 `DeviceDefinition.languageCode` |
| DeviceDefinition.manufacturer[x] | - | DoesNotExistInTarget | R4B `DeviceDefinition.manufacturer[x]` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.material | DeviceDefinition.material | Equivalent | R4B `DeviceDefinition.material` maps as Equivalent to R5 `DeviceDefinition.material` |
| DeviceDefinition.material.allergenicIndicator | DeviceDefinition.material.allergenicIndicator | Equivalent | R4B `DeviceDefinition.material.allergenicIndicator` maps as Equivalent to R5 `DeviceDefinition.material.allergenicIndicator` |
| DeviceDefinition.material.alternate | DeviceDefinition.material.alternate | Equivalent | R4B `DeviceDefinition.material.alternate` maps as Equivalent to R5 `DeviceDefinition.material.alternate` |
| DeviceDefinition.material.extension | DeviceDefinition.material.extension | RelatedTo | R4B `DeviceDefinition.material.extension` maps as RelatedTo to R5 `DeviceDefinition.material.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| DeviceDefinition.material.id | DeviceDefinition.material.id | Equivalent | R4B `DeviceDefinition.material.id` maps as Equivalent to R5 `DeviceDefinition.material.id` |
| DeviceDefinition.material.modifierExtension | DeviceDefinition.material.modifierExtension | RelatedTo | R4B `DeviceDefinition.material.modifierExtension` maps as RelatedTo to R5 `DeviceDefinition.material.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| DeviceDefinition.material.substance | DeviceDefinition.material.substance | Equivalent | R4B `DeviceDefinition.material.substance` maps as Equivalent to R5 `DeviceDefinition.material.substance` |
| DeviceDefinition.meta | DeviceDefinition.meta | Equivalent | R4B `DeviceDefinition.meta` maps as Equivalent to R5 `DeviceDefinition.meta` |
| DeviceDefinition.modelNumber | DeviceDefinition.modelNumber | Equivalent | R4B `DeviceDefinition.modelNumber` maps as Equivalent to R5 `DeviceDefinition.modelNumber` |
| DeviceDefinition.modifierExtension | DeviceDefinition.modifierExtension | RelatedTo | R4B `DeviceDefinition.modifierExtension` maps as RelatedTo to R5 `DeviceDefinition.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| DeviceDefinition.note | DeviceDefinition.note | SourceIsNarrowerThanTarget | R4B `DeviceDefinition.note` maps as SourceIsNarrowerThanTarget to R5 `DeviceDefinition.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| DeviceDefinition.onlineInformation | - | DoesNotExistInTarget | R4B `DeviceDefinition.onlineInformation` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.owner | DeviceDefinition.owner | Equivalent | R4B `DeviceDefinition.owner` maps as Equivalent to R5 `DeviceDefinition.owner` |
| DeviceDefinition.parentDevice | - | DoesNotExistInTarget | R4B `DeviceDefinition.parentDevice` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.physicalCharacteristics | - | DoesNotExistInTarget | R4B `DeviceDefinition.physicalCharacteristics` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.property | DeviceDefinition.property | Equivalent | R4B `DeviceDefinition.property` maps as Equivalent to R5 `DeviceDefinition.property` |
| DeviceDefinition.property.extension | DeviceDefinition.property.extension | RelatedTo | R4B `DeviceDefinition.property.extension` maps as RelatedTo to R5 `DeviceDefinition.property.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| DeviceDefinition.property.id | DeviceDefinition.property.id | Equivalent | R4B `DeviceDefinition.property.id` maps as Equivalent to R5 `DeviceDefinition.property.id` |
| DeviceDefinition.property.modifierExtension | DeviceDefinition.property.modifierExtension | RelatedTo | R4B `DeviceDefinition.property.modifierExtension` maps as RelatedTo to R5 `DeviceDefinition.property.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| DeviceDefinition.property.type | DeviceDefinition.property.type | RelatedTo | R4B `DeviceDefinition.property.type` maps as RelatedTo to R5 `DeviceDefinition.property.type` - type added a binding requirement - Example http://hl7.org/fhir/ValueSet/device-property-type |
| DeviceDefinition.property.valueCode | - | DoesNotExistInTarget | R4B `DeviceDefinition.property.valueCode` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.property.valueQuantity | - | DoesNotExistInTarget | R4B `DeviceDefinition.property.valueQuantity` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.quantity | - | DoesNotExistInTarget | R4B `DeviceDefinition.quantity` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.safety | DeviceDefinition.safety | Equivalent | R4B `DeviceDefinition.safety` maps as Equivalent to R5 `DeviceDefinition.safety` |
| DeviceDefinition.shelfLifeStorage | DeviceDefinition.shelfLifeStorage | Equivalent | R4B `DeviceDefinition.shelfLifeStorage` maps as Equivalent to R5 `DeviceDefinition.shelfLifeStorage` |
| DeviceDefinition.specialization | - | DoesNotExistInTarget | R4B `DeviceDefinition.specialization` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.specialization.extension | - | DoesNotExistInTarget | R4B `DeviceDefinition.specialization.extension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.specialization.id | - | DoesNotExistInTarget | R4B `DeviceDefinition.specialization.id` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.specialization.modifierExtension | - | DoesNotExistInTarget | R4B `DeviceDefinition.specialization.modifierExtension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.specialization.systemType | - | DoesNotExistInTarget | R4B `DeviceDefinition.specialization.systemType` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.specialization.version | - | DoesNotExistInTarget | R4B `DeviceDefinition.specialization.version` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.text | DeviceDefinition.text | Equivalent | R4B `DeviceDefinition.text` maps as Equivalent to R5 `DeviceDefinition.text` |
| DeviceDefinition.type | - | DoesNotExistInTarget | R4B `DeviceDefinition.type` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.udiDeviceIdentifier | DeviceDefinition.udiDeviceIdentifier | Equivalent | R4B `DeviceDefinition.udiDeviceIdentifier` maps as Equivalent to R5 `DeviceDefinition.udiDeviceIdentifier` |
| DeviceDefinition.udiDeviceIdentifier.deviceIdentifier | DeviceDefinition.udiDeviceIdentifier.deviceIdentifier | Equivalent | R4B `DeviceDefinition.udiDeviceIdentifier.deviceIdentifier` maps as Equivalent to R5 `DeviceDefinition.udiDeviceIdentifier.deviceIdentifier` |
| DeviceDefinition.udiDeviceIdentifier.extension | DeviceDefinition.udiDeviceIdentifier.extension | RelatedTo | R4B `DeviceDefinition.udiDeviceIdentifier.extension` maps as RelatedTo to R5 `DeviceDefinition.udiDeviceIdentifier.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| DeviceDefinition.udiDeviceIdentifier.id | DeviceDefinition.udiDeviceIdentifier.id | Equivalent | R4B `DeviceDefinition.udiDeviceIdentifier.id` maps as Equivalent to R5 `DeviceDefinition.udiDeviceIdentifier.id` |
| DeviceDefinition.udiDeviceIdentifier.issuer | DeviceDefinition.udiDeviceIdentifier.issuer | Equivalent | R4B `DeviceDefinition.udiDeviceIdentifier.issuer` maps as Equivalent to R5 `DeviceDefinition.udiDeviceIdentifier.issuer` |
| DeviceDefinition.udiDeviceIdentifier.jurisdiction | DeviceDefinition.udiDeviceIdentifier.jurisdiction | Equivalent | R4B `DeviceDefinition.udiDeviceIdentifier.jurisdiction` maps as Equivalent to R5 `DeviceDefinition.udiDeviceIdentifier.jurisdiction` |
| DeviceDefinition.udiDeviceIdentifier.modifierExtension | DeviceDefinition.udiDeviceIdentifier.modifierExtension | RelatedTo | R4B `DeviceDefinition.udiDeviceIdentifier.modifierExtension` maps as RelatedTo to R5 `DeviceDefinition.udiDeviceIdentifier.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| DeviceDefinition.url | - | DoesNotExistInTarget | R4B `DeviceDefinition.url` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.version | DeviceDefinition.version | SourceIsBroaderThanTarget | R4B `DeviceDefinition.version` maps as SourceIsBroaderThanTarget to R5 `DeviceDefinition.version` - version has change due to type change: R4B version string has no equivalent or mapped type in R5 version |

