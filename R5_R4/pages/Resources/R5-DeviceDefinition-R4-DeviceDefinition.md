Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | DeviceDefinition |  | This is a specialized resource that defines the characteristics and capabilities of a device. | 135 | 79 |
| Target | DeviceDefinition |  | The characteristics, operational status and capabilities of a medical-related component of a medical device. | 64 | 38 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 88 |
Equivalent | 30 |
RelatedTo | 2 |
SourceIsBroaderThanTarget | 13 |
SourceIsNarrowerThanTarget | 2 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| DeviceDefinition | DeviceDefinition | Equivalent | R5 `DeviceDefinition` maps as Equivalent to R4 `DeviceDefinition` |
| DeviceDefinition.chargeItem | - | DoesNotExistInTarget | R5 `DeviceDefinition.chargeItem` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.chargeItem.chargeItemCode | - | DoesNotExistInTarget | R5 `DeviceDefinition.chargeItem.chargeItemCode` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.chargeItem.count | - | DoesNotExistInTarget | R5 `DeviceDefinition.chargeItem.count` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.chargeItem.effectivePeriod | - | DoesNotExistInTarget | R5 `DeviceDefinition.chargeItem.effectivePeriod` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.chargeItem.extension | - | DoesNotExistInTarget | R5 `DeviceDefinition.chargeItem.extension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.chargeItem.id | - | DoesNotExistInTarget | R5 `DeviceDefinition.chargeItem.id` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.chargeItem.modifierExtension | - | DoesNotExistInTarget | R5 `DeviceDefinition.chargeItem.modifierExtension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.chargeItem.useContext | - | DoesNotExistInTarget | R5 `DeviceDefinition.chargeItem.useContext` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.classification | - | DoesNotExistInTarget | R5 `DeviceDefinition.classification` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.classification.extension | - | DoesNotExistInTarget | R5 `DeviceDefinition.classification.extension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.classification.id | - | DoesNotExistInTarget | R5 `DeviceDefinition.classification.id` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.classification.justification | - | DoesNotExistInTarget | R5 `DeviceDefinition.classification.justification` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.classification.modifierExtension | - | DoesNotExistInTarget | R5 `DeviceDefinition.classification.modifierExtension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.classification.type | - | DoesNotExistInTarget | R5 `DeviceDefinition.classification.type` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.conformsTo | DeviceDefinition.specialization | Equivalent | R5 `DeviceDefinition.conformsTo` maps as Equivalent to R4 `DeviceDefinition.specialization` |
| DeviceDefinition.conformsTo.category | - | DoesNotExistInTarget | R5 `DeviceDefinition.conformsTo.category` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.conformsTo.extension | - | DoesNotExistInTarget | R5 `DeviceDefinition.conformsTo.extension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.conformsTo.id | - | DoesNotExistInTarget | R5 `DeviceDefinition.conformsTo.id` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.conformsTo.modifierExtension | - | DoesNotExistInTarget | R5 `DeviceDefinition.conformsTo.modifierExtension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.conformsTo.source | - | DoesNotExistInTarget | R5 `DeviceDefinition.conformsTo.source` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.conformsTo.specification | - | DoesNotExistInTarget | R5 `DeviceDefinition.conformsTo.specification` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.conformsTo.version | DeviceDefinition.specialization.version | SourceIsBroaderThanTarget | R5 `DeviceDefinition.conformsTo.version` maps as SourceIsBroaderThanTarget to R4 `DeviceDefinition.specialization.version` - version changed from array to scalar (max cardinality from * to 1) |
| DeviceDefinition.contact | DeviceDefinition.contact | Equivalent | R5 `DeviceDefinition.contact` maps as Equivalent to R4 `DeviceDefinition.contact` |
| DeviceDefinition.contained | DeviceDefinition.contained | Equivalent | R5 `DeviceDefinition.contained` maps as Equivalent to R4 `DeviceDefinition.contained` |
| DeviceDefinition.correctiveAction | - | DoesNotExistInTarget | R5 `DeviceDefinition.correctiveAction` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.correctiveAction.extension | - | DoesNotExistInTarget | R5 `DeviceDefinition.correctiveAction.extension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.correctiveAction.id | - | DoesNotExistInTarget | R5 `DeviceDefinition.correctiveAction.id` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.correctiveAction.modifierExtension | - | DoesNotExistInTarget | R5 `DeviceDefinition.correctiveAction.modifierExtension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.correctiveAction.period | - | DoesNotExistInTarget | R5 `DeviceDefinition.correctiveAction.period` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.correctiveAction.recall | - | DoesNotExistInTarget | R5 `DeviceDefinition.correctiveAction.recall` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.correctiveAction.scope | - | DoesNotExistInTarget | R5 `DeviceDefinition.correctiveAction.scope` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.description | - | DoesNotExistInTarget | R5 `DeviceDefinition.description` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.deviceName | DeviceDefinition.deviceName | Equivalent | R5 `DeviceDefinition.deviceName` maps as Equivalent to R4 `DeviceDefinition.deviceName` |
| DeviceDefinition.deviceName.extension | DeviceDefinition.deviceName.extension | SourceIsBroaderThanTarget | R5 `DeviceDefinition.deviceName.extension` maps as SourceIsBroaderThanTarget to R4 `DeviceDefinition.deviceName.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| DeviceDefinition.deviceName.id | DeviceDefinition.deviceName.id | Equivalent | R5 `DeviceDefinition.deviceName.id` maps as Equivalent to R4 `DeviceDefinition.deviceName.id` |
| DeviceDefinition.deviceName.modifierExtension | DeviceDefinition.deviceName.modifierExtension | SourceIsBroaderThanTarget | R5 `DeviceDefinition.deviceName.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `DeviceDefinition.deviceName.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| DeviceDefinition.deviceName.name | DeviceDefinition.deviceName.name | Equivalent | R5 `DeviceDefinition.deviceName.name` maps as Equivalent to R4 `DeviceDefinition.deviceName.name` |
| DeviceDefinition.deviceName.type | DeviceDefinition.deviceName.type | Equivalent | R5 `DeviceDefinition.deviceName.type` maps as Equivalent to R4 `DeviceDefinition.deviceName.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/device-nametype|5.0.0 and http://hl7.org/fhir/ValueSet/device-nametype|4.0.1 (Equivalent) |
| DeviceDefinition.extension | DeviceDefinition.extension | SourceIsBroaderThanTarget | R5 `DeviceDefinition.extension` maps as SourceIsBroaderThanTarget to R4 `DeviceDefinition.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| DeviceDefinition.guideline | - | DoesNotExistInTarget | R5 `DeviceDefinition.guideline` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.guideline.contraindication | - | DoesNotExistInTarget | R5 `DeviceDefinition.guideline.contraindication` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.guideline.extension | - | DoesNotExistInTarget | R5 `DeviceDefinition.guideline.extension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.guideline.id | - | DoesNotExistInTarget | R5 `DeviceDefinition.guideline.id` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.guideline.indication | - | DoesNotExistInTarget | R5 `DeviceDefinition.guideline.indication` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.guideline.intendedUse | - | DoesNotExistInTarget | R5 `DeviceDefinition.guideline.intendedUse` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.guideline.modifierExtension | - | DoesNotExistInTarget | R5 `DeviceDefinition.guideline.modifierExtension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.guideline.relatedArtifact | - | DoesNotExistInTarget | R5 `DeviceDefinition.guideline.relatedArtifact` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.guideline.usageInstruction | - | DoesNotExistInTarget | R5 `DeviceDefinition.guideline.usageInstruction` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.guideline.useContext | - | DoesNotExistInTarget | R5 `DeviceDefinition.guideline.useContext` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.guideline.warning | - | DoesNotExistInTarget | R5 `DeviceDefinition.guideline.warning` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.hasPart | - | DoesNotExistInTarget | R5 `DeviceDefinition.hasPart` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.hasPart.count | - | DoesNotExistInTarget | R5 `DeviceDefinition.hasPart.count` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.hasPart.extension | - | DoesNotExistInTarget | R5 `DeviceDefinition.hasPart.extension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.hasPart.id | - | DoesNotExistInTarget | R5 `DeviceDefinition.hasPart.id` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.hasPart.modifierExtension | - | DoesNotExistInTarget | R5 `DeviceDefinition.hasPart.modifierExtension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.hasPart.reference | - | DoesNotExistInTarget | R5 `DeviceDefinition.hasPart.reference` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.id | DeviceDefinition.id | Equivalent | R5 `DeviceDefinition.id` maps as Equivalent to R4 `DeviceDefinition.id` |
| DeviceDefinition.identifier | DeviceDefinition.identifier | Equivalent | R5 `DeviceDefinition.identifier` maps as Equivalent to R4 `DeviceDefinition.identifier` |
| DeviceDefinition.implicitRules | DeviceDefinition.implicitRules | Equivalent | R5 `DeviceDefinition.implicitRules` maps as Equivalent to R4 `DeviceDefinition.implicitRules` |
| DeviceDefinition.language | DeviceDefinition.language | SourceIsNarrowerThanTarget | R5 `DeviceDefinition.language` maps as SourceIsNarrowerThanTarget to R4 `DeviceDefinition.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| DeviceDefinition.languageCode | DeviceDefinition.languageCode | Equivalent | R5 `DeviceDefinition.languageCode` maps as Equivalent to R4 `DeviceDefinition.languageCode` |
| DeviceDefinition.link | - | DoesNotExistInTarget | R5 `DeviceDefinition.link` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.link.extension | - | DoesNotExistInTarget | R5 `DeviceDefinition.link.extension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.link.id | - | DoesNotExistInTarget | R5 `DeviceDefinition.link.id` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.link.modifierExtension | - | DoesNotExistInTarget | R5 `DeviceDefinition.link.modifierExtension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.link.relatedDevice | - | DoesNotExistInTarget | R5 `DeviceDefinition.link.relatedDevice` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.link.relation | - | DoesNotExistInTarget | R5 `DeviceDefinition.link.relation` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.manufacturer | DeviceDefinition.manufacturer[x] | Equivalent | R5 `DeviceDefinition.manufacturer` maps as Equivalent to R4 `DeviceDefinition.manufacturer[x]` |
| DeviceDefinition.material | DeviceDefinition.material | Equivalent | R5 `DeviceDefinition.material` maps as Equivalent to R4 `DeviceDefinition.material` |
| DeviceDefinition.material.allergenicIndicator | DeviceDefinition.material.allergenicIndicator | Equivalent | R5 `DeviceDefinition.material.allergenicIndicator` maps as Equivalent to R4 `DeviceDefinition.material.allergenicIndicator` |
| DeviceDefinition.material.alternate | DeviceDefinition.material.alternate | Equivalent | R5 `DeviceDefinition.material.alternate` maps as Equivalent to R4 `DeviceDefinition.material.alternate` |
| DeviceDefinition.material.extension | DeviceDefinition.material.extension | SourceIsBroaderThanTarget | R5 `DeviceDefinition.material.extension` maps as SourceIsBroaderThanTarget to R4 `DeviceDefinition.material.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| DeviceDefinition.material.id | DeviceDefinition.material.id | Equivalent | R5 `DeviceDefinition.material.id` maps as Equivalent to R4 `DeviceDefinition.material.id` |
| DeviceDefinition.material.modifierExtension | DeviceDefinition.material.modifierExtension | SourceIsBroaderThanTarget | R5 `DeviceDefinition.material.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `DeviceDefinition.material.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| DeviceDefinition.material.substance | DeviceDefinition.material.substance | Equivalent | R5 `DeviceDefinition.material.substance` maps as Equivalent to R4 `DeviceDefinition.material.substance` |
| DeviceDefinition.meta | DeviceDefinition.meta | Equivalent | R5 `DeviceDefinition.meta` maps as Equivalent to R4 `DeviceDefinition.meta` |
| DeviceDefinition.modelNumber | DeviceDefinition.modelNumber | Equivalent | R5 `DeviceDefinition.modelNumber` maps as Equivalent to R4 `DeviceDefinition.modelNumber` |
| DeviceDefinition.modifierExtension | DeviceDefinition.modifierExtension | SourceIsBroaderThanTarget | R5 `DeviceDefinition.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `DeviceDefinition.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| DeviceDefinition.note | DeviceDefinition.note | SourceIsBroaderThanTarget | R5 `DeviceDefinition.note` maps as SourceIsBroaderThanTarget to R4 `DeviceDefinition.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4 `note` |
| DeviceDefinition.owner | DeviceDefinition.owner | Equivalent | R5 `DeviceDefinition.owner` maps as Equivalent to R4 `DeviceDefinition.owner` |
| DeviceDefinition.packaging | - | DoesNotExistInTarget | R5 `DeviceDefinition.packaging` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.packaging.count | - | DoesNotExistInTarget | R5 `DeviceDefinition.packaging.count` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.packaging.distributor | - | DoesNotExistInTarget | R5 `DeviceDefinition.packaging.distributor` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.packaging.distributor.extension | - | DoesNotExistInTarget | R5 `DeviceDefinition.packaging.distributor.extension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.packaging.distributor.id | - | DoesNotExistInTarget | R5 `DeviceDefinition.packaging.distributor.id` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.packaging.distributor.modifierExtension | - | DoesNotExistInTarget | R5 `DeviceDefinition.packaging.distributor.modifierExtension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.packaging.distributor.name | - | DoesNotExistInTarget | R5 `DeviceDefinition.packaging.distributor.name` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.packaging.distributor.organizationReference | - | DoesNotExistInTarget | R5 `DeviceDefinition.packaging.distributor.organizationReference` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.packaging.extension | - | DoesNotExistInTarget | R5 `DeviceDefinition.packaging.extension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.packaging.id | - | DoesNotExistInTarget | R5 `DeviceDefinition.packaging.id` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.packaging.identifier | - | DoesNotExistInTarget | R5 `DeviceDefinition.packaging.identifier` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.packaging.modifierExtension | - | DoesNotExistInTarget | R5 `DeviceDefinition.packaging.modifierExtension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.packaging.packaging | - | DoesNotExistInTarget | R5 `DeviceDefinition.packaging.packaging` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.packaging.type | - | DoesNotExistInTarget | R5 `DeviceDefinition.packaging.type` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.packaging.udiDeviceIdentifier | - | DoesNotExistInTarget | R5 `DeviceDefinition.packaging.udiDeviceIdentifier` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.partNumber | - | DoesNotExistInTarget | R5 `DeviceDefinition.partNumber` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.productionIdentifierInUDI | - | DoesNotExistInTarget | R5 `DeviceDefinition.productionIdentifierInUDI` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.property | DeviceDefinition.property | Equivalent | R5 `DeviceDefinition.property` maps as Equivalent to R4 `DeviceDefinition.property` |
| DeviceDefinition.property.extension | DeviceDefinition.property.extension | SourceIsBroaderThanTarget | R5 `DeviceDefinition.property.extension` maps as SourceIsBroaderThanTarget to R4 `DeviceDefinition.property.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| DeviceDefinition.property.id | DeviceDefinition.property.id | Equivalent | R5 `DeviceDefinition.property.id` maps as Equivalent to R4 `DeviceDefinition.property.id` |
| DeviceDefinition.property.modifierExtension | DeviceDefinition.property.modifierExtension | SourceIsBroaderThanTarget | R5 `DeviceDefinition.property.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `DeviceDefinition.property.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| DeviceDefinition.property.type | DeviceDefinition.property.type | SourceIsNarrowerThanTarget | R5 `DeviceDefinition.property.type` maps as SourceIsNarrowerThanTarget to R4 `DeviceDefinition.property.type` - type removed a binding requirement - Example http://hl7.org/fhir/ValueSet/device-property-type; type has change due to type change: R5 `type` `CodeableConcept` maps as SourceIsNarrowerThanTarget for R4 `type` |
| DeviceDefinition.property.value[x] | DeviceDefinition.property.valueCode | RelatedTo | R5 `DeviceDefinition.property.value[x]` maps as RelatedTo to R4 `DeviceDefinition.property.valueCode` - valueCode changed from scalar to array (max cardinality from 1 to *); valueCode has change due to type change: R5 value[x] Quantity has no equivalent or mapped type in R4 valueCode; valueCode has change due to type change: R5 value[x] string has no equivalent or mapped type in R4 valueCode; valueCode has change due to type change: R5 value[x] boolean has no equivalent or mapped type in R4 valueCode; valueCode has change due to type change: R5 value[x] integer has no equivalent or mapped type in R4 valueCode; valueCode has change due to type change: R5 value[x] Range has no equivalent or mapped type in R4 valueCode; valueCode has change due to type change: R5 value[x] Attachment has no equivalent or mapped type in R4 valueCode |
| DeviceDefinition.property.value[x] | DeviceDefinition.property.valueCode | RelatedTo | R5 `DeviceDefinition.property.value[x]` maps as RelatedTo to R4 `DeviceDefinition.property.valueCode` - valueCode changed from scalar to array (max cardinality from 1 to *); valueCode has change due to type change: R5 value[x] Quantity has no equivalent or mapped type in R4 valueCode; valueCode has change due to type change: R5 value[x] string has no equivalent or mapped type in R4 valueCode; valueCode has change due to type change: R5 value[x] boolean has no equivalent or mapped type in R4 valueCode; valueCode has change due to type change: R5 value[x] integer has no equivalent or mapped type in R4 valueCode; valueCode has change due to type change: R5 value[x] Range has no equivalent or mapped type in R4 valueCode; valueCode has change due to type change: R5 value[x] Attachment has no equivalent or mapped type in R4 valueCode |
| DeviceDefinition.property.value[x] | DeviceDefinition.property.valueQuantity | RelatedTo | R5 `DeviceDefinition.property.value[x]` maps as RelatedTo to R4 `DeviceDefinition.property.valueQuantity` - valueQuantity changed from scalar to array (max cardinality from 1 to *); valueQuantity has change due to type change: R5 value[x] CodeableConcept has no equivalent or mapped type in R4 valueQuantity; valueQuantity has change due to type change: R5 value[x] string has no equivalent or mapped type in R4 valueQuantity; valueQuantity has change due to type change: R5 value[x] boolean has no equivalent or mapped type in R4 valueQuantity; valueQuantity has change due to type change: R5 value[x] integer has no equivalent or mapped type in R4 valueQuantity; valueQuantity has change due to type change: R5 value[x] Range has no equivalent or mapped type in R4 valueQuantity; valueQuantity has change due to type change: R5 value[x] Attachment has no equivalent or mapped type in R4 valueQuantity |
| DeviceDefinition.regulatoryIdentifier | - | DoesNotExistInTarget | R5 `DeviceDefinition.regulatoryIdentifier` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.regulatoryIdentifier.deviceIdentifier | - | DoesNotExistInTarget | R5 `DeviceDefinition.regulatoryIdentifier.deviceIdentifier` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.regulatoryIdentifier.extension | - | DoesNotExistInTarget | R5 `DeviceDefinition.regulatoryIdentifier.extension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.regulatoryIdentifier.id | - | DoesNotExistInTarget | R5 `DeviceDefinition.regulatoryIdentifier.id` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.regulatoryIdentifier.issuer | - | DoesNotExistInTarget | R5 `DeviceDefinition.regulatoryIdentifier.issuer` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.regulatoryIdentifier.jurisdiction | - | DoesNotExistInTarget | R5 `DeviceDefinition.regulatoryIdentifier.jurisdiction` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.regulatoryIdentifier.modifierExtension | - | DoesNotExistInTarget | R5 `DeviceDefinition.regulatoryIdentifier.modifierExtension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.regulatoryIdentifier.type | - | DoesNotExistInTarget | R5 `DeviceDefinition.regulatoryIdentifier.type` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.safety | DeviceDefinition.safety | Equivalent | R5 `DeviceDefinition.safety` maps as Equivalent to R4 `DeviceDefinition.safety` |
| DeviceDefinition.shelfLifeStorage | DeviceDefinition.shelfLifeStorage | RelatedTo | R5 `DeviceDefinition.shelfLifeStorage` maps as RelatedTo to R4 `DeviceDefinition.shelfLifeStorage` - shelfLifeStorage has change due to type change: R5 `shelfLifeStorage` `ProductShelfLife` maps as RelatedTo for R4 `shelfLifeStorage` |
| DeviceDefinition.text | DeviceDefinition.text | Equivalent | R5 `DeviceDefinition.text` maps as Equivalent to R4 `DeviceDefinition.text` |
| DeviceDefinition.udiDeviceIdentifier | DeviceDefinition.udiDeviceIdentifier | Equivalent | R5 `DeviceDefinition.udiDeviceIdentifier` maps as Equivalent to R4 `DeviceDefinition.udiDeviceIdentifier` |
| DeviceDefinition.udiDeviceIdentifier.deviceIdentifier | DeviceDefinition.udiDeviceIdentifier.deviceIdentifier | Equivalent | R5 `DeviceDefinition.udiDeviceIdentifier.deviceIdentifier` maps as Equivalent to R4 `DeviceDefinition.udiDeviceIdentifier.deviceIdentifier` |
| DeviceDefinition.udiDeviceIdentifier.extension | DeviceDefinition.udiDeviceIdentifier.extension | SourceIsBroaderThanTarget | R5 `DeviceDefinition.udiDeviceIdentifier.extension` maps as SourceIsBroaderThanTarget to R4 `DeviceDefinition.udiDeviceIdentifier.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| DeviceDefinition.udiDeviceIdentifier.id | DeviceDefinition.udiDeviceIdentifier.id | Equivalent | R5 `DeviceDefinition.udiDeviceIdentifier.id` maps as Equivalent to R4 `DeviceDefinition.udiDeviceIdentifier.id` |
| DeviceDefinition.udiDeviceIdentifier.issuer | DeviceDefinition.udiDeviceIdentifier.issuer | Equivalent | R5 `DeviceDefinition.udiDeviceIdentifier.issuer` maps as Equivalent to R4 `DeviceDefinition.udiDeviceIdentifier.issuer` |
| DeviceDefinition.udiDeviceIdentifier.jurisdiction | DeviceDefinition.udiDeviceIdentifier.jurisdiction | Equivalent | R5 `DeviceDefinition.udiDeviceIdentifier.jurisdiction` maps as Equivalent to R4 `DeviceDefinition.udiDeviceIdentifier.jurisdiction` |
| DeviceDefinition.udiDeviceIdentifier.marketDistribution | - | DoesNotExistInTarget | R5 `DeviceDefinition.udiDeviceIdentifier.marketDistribution` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.udiDeviceIdentifier.marketDistribution.extension | - | DoesNotExistInTarget | R5 `DeviceDefinition.udiDeviceIdentifier.marketDistribution.extension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.udiDeviceIdentifier.marketDistribution.id | - | DoesNotExistInTarget | R5 `DeviceDefinition.udiDeviceIdentifier.marketDistribution.id` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.udiDeviceIdentifier.marketDistribution.marketPeriod | - | DoesNotExistInTarget | R5 `DeviceDefinition.udiDeviceIdentifier.marketDistribution.marketPeriod` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.udiDeviceIdentifier.marketDistribution.modifierExtension | - | DoesNotExistInTarget | R5 `DeviceDefinition.udiDeviceIdentifier.marketDistribution.modifierExtension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.udiDeviceIdentifier.marketDistribution.subJurisdiction | - | DoesNotExistInTarget | R5 `DeviceDefinition.udiDeviceIdentifier.marketDistribution.subJurisdiction` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.udiDeviceIdentifier.modifierExtension | DeviceDefinition.udiDeviceIdentifier.modifierExtension | SourceIsBroaderThanTarget | R5 `DeviceDefinition.udiDeviceIdentifier.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `DeviceDefinition.udiDeviceIdentifier.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| DeviceDefinition.version | DeviceDefinition.version | SourceIsBroaderThanTarget | R5 `DeviceDefinition.version` maps as SourceIsBroaderThanTarget to R4 `DeviceDefinition.version` - version has change due to type change: R5 version BackboneElement has no equivalent or mapped type in R4 version |
| DeviceDefinition.version.component | - | DoesNotExistInTarget | R5 `DeviceDefinition.version.component` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.version.extension | - | DoesNotExistInTarget | R5 `DeviceDefinition.version.extension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.version.id | - | DoesNotExistInTarget | R5 `DeviceDefinition.version.id` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.version.modifierExtension | - | DoesNotExistInTarget | R5 `DeviceDefinition.version.modifierExtension` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.version.type | - | DoesNotExistInTarget | R5 `DeviceDefinition.version.type` does not appear in the target and has no mapping for `DeviceDefinition`. |
| DeviceDefinition.version.value | - | DoesNotExistInTarget | R5 `DeviceDefinition.version.value` does not appear in the target and has no mapping for `DeviceDefinition`. |

