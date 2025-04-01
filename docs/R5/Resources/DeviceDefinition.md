Comparison of 
Generated at Tuesday, April 1, 2025 1:39:38 PM

### DeviceDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | DeviceDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/DeviceDefinition` |
| Version | 5.0.0 |
| Description | This is a specialized resource that defines the characteristics and capabilities of a device. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2290` |
| Database Snapshot Count | `135` |
| Database Differential Count | `79` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `DeviceDefinition` | `DeviceDefinition` | `DeviceDefinition` | DeviceDefinition | An instance of a medical-related component of a medical device | 0..* | DeviceDefinition |  |  |
| `DeviceDefinition.chargeItem` | `DeviceDefinition.chargeItem` | `chargeItem` | DeviceDefinition.chargeItem | Billing code or reference associated with the device | 0..* | BackboneElement |  |  |
| `DeviceDefinition.chargeItem.chargeItemCode` | `DeviceDefinition.chargeItem.chargeItemCode` | `chargeItemCode` | DeviceDefinition.chargeItem.chargeItemCode | The code or reference for the charge item | 1..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/ChargeItemDefinition) |  |  |
| `DeviceDefinition.chargeItem.count` | `DeviceDefinition.chargeItem.count` | `count` | DeviceDefinition.chargeItem.count | Coefficient applicable to the billing code | 1..1 | Quantity |  |  |
| `DeviceDefinition.chargeItem.effectivePeriod` | `DeviceDefinition.chargeItem.effectivePeriod` | `effectivePeriod` | DeviceDefinition.chargeItem.effectivePeriod | A specific time period in which this charge item applies | 0..1 | Period |  |  |
| `DeviceDefinition.chargeItem.extension` | `DeviceDefinition.chargeItem.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDefinition.chargeItem.id` | `DeviceDefinition.chargeItem.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceDefinition.chargeItem.modifierExtension` | `DeviceDefinition.chargeItem.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceDefinition.chargeItem.useContext` | `DeviceDefinition.chargeItem.useContext` | `useContext` | DeviceDefinition.chargeItem.useContext | The context to which this charge item applies | 0..* | UsageContext |  |  |
| `DeviceDefinition.classification` | `DeviceDefinition.classification` | `classification` | DeviceDefinition.classification | What kind of device or device system this is | 0..* | BackboneElement |  |  |
| `DeviceDefinition.classification.extension` | `DeviceDefinition.classification.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDefinition.classification.id` | `DeviceDefinition.classification.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceDefinition.classification.justification` | `DeviceDefinition.classification.justification` | `justification` | DeviceDefinition.classification.justification | Further information qualifying this classification of the device model | 0..* | RelatedArtifact |  |  |
| `DeviceDefinition.classification.modifierExtension` | `DeviceDefinition.classification.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceDefinition.classification.type` | `DeviceDefinition.classification.type` | `type` | DeviceDefinition.classification.type | A classification or risk class of the device model | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/device-type` |
| `DeviceDefinition.conformsTo` | `DeviceDefinition.conformsTo` | `conformsTo` | DeviceDefinition.conformsTo | Identifies the standards, specifications, or formal guidances for the capabilities supported by the device | 0..* | BackboneElement |  |  |
| `DeviceDefinition.conformsTo.category` | `DeviceDefinition.conformsTo.category` | `category` | DeviceDefinition.conformsTo.category | Describes the common type of the standard, specification, or formal guidance | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/device-specification-category` |
| `DeviceDefinition.conformsTo.extension` | `DeviceDefinition.conformsTo.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDefinition.conformsTo.id` | `DeviceDefinition.conformsTo.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceDefinition.conformsTo.modifierExtension` | `DeviceDefinition.conformsTo.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceDefinition.conformsTo.source` | `DeviceDefinition.conformsTo.source` | `source` | DeviceDefinition.conformsTo.source | Standard, regulation, certification, or guidance website, document, or other publication, or similar, supporting the conformance | 0..* | RelatedArtifact |  |  |
| `DeviceDefinition.conformsTo.specification` | `DeviceDefinition.conformsTo.specification` | `specification` | DeviceDefinition.conformsTo.specification | Identifies the standard, specification, or formal guidance that the device adheres to the Device Specification type | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/device-specification-type` |
| `DeviceDefinition.conformsTo.version` | `DeviceDefinition.conformsTo.version` | `version` | DeviceDefinition.conformsTo.version | The specific form or variant of the standard, specification or formal guidance | 0..* | string |  |  |
| `DeviceDefinition.contact` | `DeviceDefinition.contact` | `contact` | DeviceDefinition.contact | Details for human/organization for support | 0..* | ContactPoint |  |  |
| `DeviceDefinition.contained` | `DeviceDefinition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `DeviceDefinition.correctiveAction` | `DeviceDefinition.correctiveAction` | `correctiveAction` | DeviceDefinition.correctiveAction | Tracking of latest field safety corrective action | 0..1 | BackboneElement |  |  |
| `DeviceDefinition.correctiveAction.extension` | `DeviceDefinition.correctiveAction.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDefinition.correctiveAction.id` | `DeviceDefinition.correctiveAction.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceDefinition.correctiveAction.modifierExtension` | `DeviceDefinition.correctiveAction.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceDefinition.correctiveAction.period` | `DeviceDefinition.correctiveAction.period` | `period` | DeviceDefinition.correctiveAction.period | Start and end dates of the  corrective action | 1..1 | Period |  |  |
| `DeviceDefinition.correctiveAction.recall` | `DeviceDefinition.correctiveAction.recall` | `recall` | DeviceDefinition.correctiveAction.recall | Whether the corrective action was a recall | 1..1 | boolean |  |  |
| `DeviceDefinition.correctiveAction.scope` | `DeviceDefinition.correctiveAction.scope` | `scope` | DeviceDefinition.correctiveAction.scope | model \| lot-numbers \| serial-numbers | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/device-correctiveactionscope|5.0.0` |
| `DeviceDefinition.description` | `DeviceDefinition.description` | `description` | DeviceDefinition.description | Additional information to describe the device | 0..1 | markdown |  |  |
| `DeviceDefinition.deviceName` | `DeviceDefinition.deviceName` | `deviceName` | DeviceDefinition.deviceName | The name or names of the device as given by the manufacturer | 0..* | BackboneElement |  |  |
| `DeviceDefinition.deviceName.extension` | `DeviceDefinition.deviceName.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDefinition.deviceName.id` | `DeviceDefinition.deviceName.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceDefinition.deviceName.modifierExtension` | `DeviceDefinition.deviceName.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceDefinition.deviceName.name` | `DeviceDefinition.deviceName.name` | `name` | DeviceDefinition.deviceName.name | A name that is used to refer to the device | 1..1 | string |  |  |
| `DeviceDefinition.deviceName.type` | `DeviceDefinition.deviceName.type` | `type` | DeviceDefinition.deviceName.type | registered-name \| user-friendly-name \| patient-reported-name | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/device-nametype|5.0.0` |
| `DeviceDefinition.extension` | `DeviceDefinition.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDefinition.guideline` | `DeviceDefinition.guideline` | `guideline` | DeviceDefinition.guideline | Information aimed at providing directions for the usage of this model of device | 0..1 | BackboneElement |  |  |
| `DeviceDefinition.guideline.contraindication` | `DeviceDefinition.guideline.contraindication` | `contraindication` | DeviceDefinition.guideline.contraindication | A specific situation when a device should not be used because it may cause harm | 0..* | CodeableConcept |  |  |
| `DeviceDefinition.guideline.extension` | `DeviceDefinition.guideline.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDefinition.guideline.id` | `DeviceDefinition.guideline.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceDefinition.guideline.indication` | `DeviceDefinition.guideline.indication` | `indication` | DeviceDefinition.guideline.indication | A clinical condition for which the device was designed to be used | 0..* | CodeableConcept |  |  |
| `DeviceDefinition.guideline.intendedUse` | `DeviceDefinition.guideline.intendedUse` | `intendedUse` | DeviceDefinition.guideline.intendedUse | A description of the general purpose or medical use of the device or its function | 0..1 | string |  |  |
| `DeviceDefinition.guideline.modifierExtension` | `DeviceDefinition.guideline.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceDefinition.guideline.relatedArtifact` | `DeviceDefinition.guideline.relatedArtifact` | `relatedArtifact` | DeviceDefinition.guideline.relatedArtifact | A source of information or reference for this guideline | 0..* | RelatedArtifact |  |  |
| `DeviceDefinition.guideline.usageInstruction` | `DeviceDefinition.guideline.usageInstruction` | `usageInstruction` | DeviceDefinition.guideline.usageInstruction | Detailed written and visual directions for the user on how to use the device | 0..1 | markdown |  |  |
| `DeviceDefinition.guideline.useContext` | `DeviceDefinition.guideline.useContext` | `useContext` | DeviceDefinition.guideline.useContext | The circumstances that form the setting for using the device | 0..* | UsageContext |  |  |
| `DeviceDefinition.guideline.warning` | `DeviceDefinition.guideline.warning` | `warning` | DeviceDefinition.guideline.warning | Specific hazard alert information that a user needs to know before using the device | 0..* | CodeableConcept |  |  |
| `DeviceDefinition.hasPart` | `DeviceDefinition.hasPart` | `hasPart` | DeviceDefinition.hasPart | A device, part of the current one | 0..* | BackboneElement |  |  |
| `DeviceDefinition.hasPart.count` | `DeviceDefinition.hasPart.count` | `count` | DeviceDefinition.hasPart.count | Number of occurrences of the part | 0..1 | integer |  |  |
| `DeviceDefinition.hasPart.extension` | `DeviceDefinition.hasPart.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDefinition.hasPart.id` | `DeviceDefinition.hasPart.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceDefinition.hasPart.modifierExtension` | `DeviceDefinition.hasPart.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceDefinition.hasPart.reference` | `DeviceDefinition.hasPart.reference` | `reference` | DeviceDefinition.hasPart.reference | Reference to the part | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/DeviceDefinition) |  |  |
| `DeviceDefinition.id` | `DeviceDefinition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `DeviceDefinition.identifier` | `DeviceDefinition.identifier` | `identifier` | DeviceDefinition.identifier | Instance identifier | 0..* | Identifier |  |  |
| `DeviceDefinition.implicitRules` | `DeviceDefinition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `DeviceDefinition.language` | `DeviceDefinition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `DeviceDefinition.languageCode` | `DeviceDefinition.languageCode` | `languageCode` | DeviceDefinition.languageCode | Language code for the human-readable text strings produced by the device (all supported) | 0..* | CodeableConcept |  |  |
| `DeviceDefinition.link` | `DeviceDefinition.link` | `link` | DeviceDefinition.link | An associated device, attached to, used with, communicating with or linking a previous or new device model to the focal device | 0..* | BackboneElement |  |  |
| `DeviceDefinition.link.extension` | `DeviceDefinition.link.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDefinition.link.id` | `DeviceDefinition.link.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceDefinition.link.modifierExtension` | `DeviceDefinition.link.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceDefinition.link.relatedDevice` | `DeviceDefinition.link.relatedDevice` | `relatedDevice` | DeviceDefinition.link.relatedDevice | A reference to the linked device | 1..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/DeviceDefinition) |  |  |
| `DeviceDefinition.link.relation` | `DeviceDefinition.link.relation` | `relation` | DeviceDefinition.link.relation | The type indicates the relationship of the related device to the device instance | 1..1 | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/devicedefinition-relationtype` |
| `DeviceDefinition.manufacturer` | `DeviceDefinition.manufacturer` | `manufacturer` | DeviceDefinition.manufacturer | Name of device manufacturer | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `DeviceDefinition.material` | `DeviceDefinition.material` | `material` | DeviceDefinition.material | A substance used to create the material(s) of which the device is made | 0..* | BackboneElement |  |  |
| `DeviceDefinition.material.allergenicIndicator` | `DeviceDefinition.material.allergenicIndicator` | `allergenicIndicator` | DeviceDefinition.material.allergenicIndicator | Whether the substance is a known or suspected allergen | 0..1 | boolean |  |  |
| `DeviceDefinition.material.alternate` | `DeviceDefinition.material.alternate` | `alternate` | DeviceDefinition.material.alternate | Indicates an alternative material of the device | 0..1 | boolean |  |  |
| `DeviceDefinition.material.extension` | `DeviceDefinition.material.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDefinition.material.id` | `DeviceDefinition.material.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceDefinition.material.modifierExtension` | `DeviceDefinition.material.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceDefinition.material.substance` | `DeviceDefinition.material.substance` | `substance` | DeviceDefinition.material.substance | A relevant substance that the device contains, may contain, or is made of | 1..1 | CodeableConcept |  |  |
| `DeviceDefinition.meta` | `DeviceDefinition.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `DeviceDefinition.modelNumber` | `DeviceDefinition.modelNumber` | `modelNumber` | DeviceDefinition.modelNumber | The catalog or model number for the device for example as defined by the manufacturer | 0..1 | string |  |  |
| `DeviceDefinition.modifierExtension` | `DeviceDefinition.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DeviceDefinition.note` | `DeviceDefinition.note` | `note` | DeviceDefinition.note | Device notes and comments | 0..* | Annotation |  |  |
| `DeviceDefinition.owner` | `DeviceDefinition.owner` | `owner` | DeviceDefinition.owner | Organization responsible for device | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `DeviceDefinition.packaging` | `DeviceDefinition.packaging` | `packaging` | DeviceDefinition.packaging | Information about the packaging of the device, i.e. how the device is packaged | 0..* | BackboneElement |  |  |
| `DeviceDefinition.packaging.count` | `DeviceDefinition.packaging.count` | `count` | DeviceDefinition.packaging.count | The number of items contained in the package (devices or sub-packages) | 0..1 | integer |  |  |
| `DeviceDefinition.packaging.distributor` | `DeviceDefinition.packaging.distributor` | `distributor` | DeviceDefinition.packaging.distributor | An organization that distributes the packaged device | 0..* | BackboneElement |  |  |
| `DeviceDefinition.packaging.distributor.extension` | `DeviceDefinition.packaging.distributor.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDefinition.packaging.distributor.id` | `DeviceDefinition.packaging.distributor.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceDefinition.packaging.distributor.modifierExtension` | `DeviceDefinition.packaging.distributor.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceDefinition.packaging.distributor.name` | `DeviceDefinition.packaging.distributor.name` | `name` | DeviceDefinition.packaging.distributor.name | Distributor's human-readable name | 0..1 | string |  |  |
| `DeviceDefinition.packaging.distributor.organizationReference` | `DeviceDefinition.packaging.distributor.organizationReference` | `organizationReference` | DeviceDefinition.packaging.distributor.organizationReference | Distributor as an Organization resource | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `DeviceDefinition.packaging.extension` | `DeviceDefinition.packaging.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDefinition.packaging.id` | `DeviceDefinition.packaging.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceDefinition.packaging.identifier` | `DeviceDefinition.packaging.identifier` | `identifier` | DeviceDefinition.packaging.identifier | Business identifier of the packaged medication | 0..1 | Identifier |  |  |
| `DeviceDefinition.packaging.modifierExtension` | `DeviceDefinition.packaging.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceDefinition.packaging.packaging` | `DeviceDefinition.packaging.packaging` | `packaging` | DeviceDefinition.packaging.packaging | Allows packages within packages | 0..* | DeviceDefinition.packaging |  |  |
| `DeviceDefinition.packaging.type` | `DeviceDefinition.packaging.type` | `type` | DeviceDefinition.packaging.type | A code that defines the specific type of packaging | 0..1 | CodeableConcept |  |  |
| `DeviceDefinition.packaging.udiDeviceIdentifier` | `DeviceDefinition.packaging.udiDeviceIdentifier` | `udiDeviceIdentifier` | DeviceDefinition.packaging.udiDeviceIdentifier | Unique Device Identifier (UDI) Barcode string on the packaging | 0..* | DeviceDefinition.udiDeviceIdentifier |  |  |
| `DeviceDefinition.partNumber` | `DeviceDefinition.partNumber` | `partNumber` | DeviceDefinition.partNumber | The part number or catalog number of the device | 0..1 | string |  |  |
| `DeviceDefinition.productionIdentifierInUDI` | `DeviceDefinition.productionIdentifierInUDI` | `productionIdentifierInUDI` | DeviceDefinition.productionIdentifierInUDI | lot-number \| manufactured-date \| serial-number \| expiration-date \| biological-source \| software-version | 0..* | code | `Required` | `http://hl7.org/fhir/ValueSet/device-productidentifierinudi|5.0.0` |
| `DeviceDefinition.property` | `DeviceDefinition.property` | `property` | DeviceDefinition.property | Inherent, essentially fixed, characteristics of this kind of device, e.g., time properties, size, etc | 0..* | BackboneElement |  |  |
| `DeviceDefinition.property.extension` | `DeviceDefinition.property.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDefinition.property.id` | `DeviceDefinition.property.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceDefinition.property.modifierExtension` | `DeviceDefinition.property.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceDefinition.property.type` | `DeviceDefinition.property.type` | `type` | DeviceDefinition.property.type | Code that specifies the property being represented | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/device-property-type` |
| `DeviceDefinition.property.value[x]` | `DeviceDefinition.property.value[x]` | `value[x]` | DeviceDefinition.property.value[x] | Value of the property | 1..1 | Attachment, boolean, CodeableConcept, integer, Quantity, Range, string |  |  |
| `DeviceDefinition.regulatoryIdentifier` | `DeviceDefinition.regulatoryIdentifier` | `regulatoryIdentifier` | DeviceDefinition.regulatoryIdentifier | Regulatory identifier(s) associated with this device | 0..* | BackboneElement |  |  |
| `DeviceDefinition.regulatoryIdentifier.deviceIdentifier` | `DeviceDefinition.regulatoryIdentifier.deviceIdentifier` | `deviceIdentifier` | DeviceDefinition.regulatoryIdentifier.deviceIdentifier | The identifier itself | 1..1 | string |  |  |
| `DeviceDefinition.regulatoryIdentifier.extension` | `DeviceDefinition.regulatoryIdentifier.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDefinition.regulatoryIdentifier.id` | `DeviceDefinition.regulatoryIdentifier.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceDefinition.regulatoryIdentifier.issuer` | `DeviceDefinition.regulatoryIdentifier.issuer` | `issuer` | DeviceDefinition.regulatoryIdentifier.issuer | The organization that issued this identifier | 1..1 | uri |  |  |
| `DeviceDefinition.regulatoryIdentifier.jurisdiction` | `DeviceDefinition.regulatoryIdentifier.jurisdiction` | `jurisdiction` | DeviceDefinition.regulatoryIdentifier.jurisdiction | The jurisdiction to which the deviceIdentifier applies | 1..1 | uri |  |  |
| `DeviceDefinition.regulatoryIdentifier.modifierExtension` | `DeviceDefinition.regulatoryIdentifier.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceDefinition.regulatoryIdentifier.type` | `DeviceDefinition.regulatoryIdentifier.type` | `type` | DeviceDefinition.regulatoryIdentifier.type | basic \| master \| license | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/devicedefinition-regulatory-identifier-type|5.0.0` |
| `DeviceDefinition.safety` | `DeviceDefinition.safety` | `safety` | DeviceDefinition.safety | Safety characteristics of the device | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/device-safety` |
| `DeviceDefinition.shelfLifeStorage` | `DeviceDefinition.shelfLifeStorage` | `shelfLifeStorage` | DeviceDefinition.shelfLifeStorage | Shelf Life and storage information | 0..* | ProductShelfLife |  |  |
| `DeviceDefinition.text` | `DeviceDefinition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `DeviceDefinition.udiDeviceIdentifier` | `DeviceDefinition.udiDeviceIdentifier` | `udiDeviceIdentifier` | DeviceDefinition.udiDeviceIdentifier | Unique Device Identifier (UDI) Barcode string | 0..* | BackboneElement |  |  |
| `DeviceDefinition.udiDeviceIdentifier.deviceIdentifier` | `DeviceDefinition.udiDeviceIdentifier.deviceIdentifier` | `deviceIdentifier` | DeviceDefinition.udiDeviceIdentifier.deviceIdentifier | The identifier that is to be associated with every Device that references this DeviceDefintiion for the issuer and jurisdiction provided in the DeviceDefinition.udiDeviceIdentifier | 1..1 | string |  |  |
| `DeviceDefinition.udiDeviceIdentifier.extension` | `DeviceDefinition.udiDeviceIdentifier.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDefinition.udiDeviceIdentifier.id` | `DeviceDefinition.udiDeviceIdentifier.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceDefinition.udiDeviceIdentifier.issuer` | `DeviceDefinition.udiDeviceIdentifier.issuer` | `issuer` | DeviceDefinition.udiDeviceIdentifier.issuer | The organization that assigns the identifier algorithm | 1..1 | uri |  |  |
| `DeviceDefinition.udiDeviceIdentifier.jurisdiction` | `DeviceDefinition.udiDeviceIdentifier.jurisdiction` | `jurisdiction` | DeviceDefinition.udiDeviceIdentifier.jurisdiction | The jurisdiction to which the deviceIdentifier applies | 1..1 | uri |  |  |
| `DeviceDefinition.udiDeviceIdentifier.marketDistribution` | `DeviceDefinition.udiDeviceIdentifier.marketDistribution` | `marketDistribution` | DeviceDefinition.udiDeviceIdentifier.marketDistribution | Indicates whether and when the device is available on the market | 0..* | BackboneElement |  |  |
| `DeviceDefinition.udiDeviceIdentifier.marketDistribution.extension` | `DeviceDefinition.udiDeviceIdentifier.marketDistribution.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDefinition.udiDeviceIdentifier.marketDistribution.id` | `DeviceDefinition.udiDeviceIdentifier.marketDistribution.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceDefinition.udiDeviceIdentifier.marketDistribution.marketPeriod` | `DeviceDefinition.udiDeviceIdentifier.marketDistribution.marketPeriod` | `marketPeriod` | DeviceDefinition.udiDeviceIdentifier.marketDistribution.marketPeriod | Begin and end dates for the commercial distribution of the device | 1..1 | Period |  |  |
| `DeviceDefinition.udiDeviceIdentifier.marketDistribution.modifierExtension` | `DeviceDefinition.udiDeviceIdentifier.marketDistribution.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceDefinition.udiDeviceIdentifier.marketDistribution.subJurisdiction` | `DeviceDefinition.udiDeviceIdentifier.marketDistribution.subJurisdiction` | `subJurisdiction` | DeviceDefinition.udiDeviceIdentifier.marketDistribution.subJurisdiction | National state or territory where the device is commercialized | 1..1 | uri |  |  |
| `DeviceDefinition.udiDeviceIdentifier.modifierExtension` | `DeviceDefinition.udiDeviceIdentifier.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceDefinition.version` | `DeviceDefinition.version` | `version` | DeviceDefinition.version | The version of the device or software | 0..* | BackboneElement |  |  |
| `DeviceDefinition.version.component` | `DeviceDefinition.version.component` | `component` | DeviceDefinition.version.component | The hardware or software module of the device to which the version applies | 0..1 | Identifier |  |  |
| `DeviceDefinition.version.extension` | `DeviceDefinition.version.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDefinition.version.id` | `DeviceDefinition.version.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceDefinition.version.modifierExtension` | `DeviceDefinition.version.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceDefinition.version.type` | `DeviceDefinition.version.type` | `type` | DeviceDefinition.version.type | The type of the device version, e.g. manufacturer, approved, internal | 0..1 | CodeableConcept |  |  |
| `DeviceDefinition.version.value` | `DeviceDefinition.version.value` | `value` | DeviceDefinition.version.value | The version text | 1..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [DeviceDefinition](/docs/R4/Resources/DeviceDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceDefinition\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1457`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1458`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceDefinition](/docs/R4B/Resources/DeviceDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceDefinition\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `963`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1192`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceDefinition](/docs/R5/Resources/DeviceDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceDefinition\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition DeviceDefinition from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | [R4 DeviceDefinition](/docs/R4/Resources/DeviceDefinition.md)| Relationship | [R4B DeviceDefinition](/docs/R4B/Resources/DeviceDefinition.md)| Relationship | R5 DeviceDefinition
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `DeviceDefinition`| _Equivalent_<br/>(25608/25609)| `DeviceDefinition`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(40535)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40536)| **`DeviceDefinition`**
| | | | | `DeviceDefinition.id`| _Equivalent_<br/>(25610/25611)| `DeviceDefinition.id`| _Equivalent_<br/>(40537/40538)| **`DeviceDefinition.id`**
| | | | | `DeviceDefinition.meta`| _Equivalent_<br/>(25612/25613)| `DeviceDefinition.meta`| _Equivalent_<br/>(40539/40540)| **`DeviceDefinition.meta`**
| | | | | `DeviceDefinition.implicitRules`| _Equivalent_<br/>(25614/25615)| `DeviceDefinition.implicitRules`| _Equivalent_<br/>(40541/40542)| **`DeviceDefinition.implicitRules`**
| | | | | `DeviceDefinition.language`| _Equivalent_<br/>(25616/25617)| `DeviceDefinition.language`| _Equivalent_<br/>(40543/40544)| **`DeviceDefinition.language`**
| | | | | `DeviceDefinition.text`| _Equivalent_<br/>(25618/25619)| `DeviceDefinition.text`| _Equivalent_<br/>(40545/40546)| **`DeviceDefinition.text`**
| | | | | `DeviceDefinition.contained`| _Equivalent_<br/>(25620/25621)| `DeviceDefinition.contained`| _Equivalent_<br/>(40547/40548)| **`DeviceDefinition.contained`**
| | | | | `DeviceDefinition.extension`| _Equivalent_<br/>(25622/25623)| `DeviceDefinition.extension`| _Equivalent_<br/>(40549/40550)| **`DeviceDefinition.extension`**
| | | | | `DeviceDefinition.modifierExtension`| _Equivalent_<br/>(25624/25625)| `DeviceDefinition.modifierExtension`| _Equivalent_<br/>(40551/40552)| **`DeviceDefinition.modifierExtension`**
| | | | | | | | | **`DeviceDefinition.description`**
| | | | | `DeviceDefinition.identifier`| _Equivalent_<br/>(25626/25627)| `DeviceDefinition.identifier`| _Equivalent_<br/>(40553/40554)| **`DeviceDefinition.identifier`**
| | | | | `DeviceDefinition.udiDeviceIdentifier`| _Equivalent_<br/>(25628/25629)| `DeviceDefinition.udiDeviceIdentifier`| _Equivalent_<br/>(40555/40556)| **`DeviceDefinition.udiDeviceIdentifier`**
| | | | | `DeviceDefinition.udiDeviceIdentifier.id`| _Equivalent_<br/>(25630/25631)| `DeviceDefinition.udiDeviceIdentifier.id`| _Equivalent_<br/>(40557/40558)| **`DeviceDefinition.udiDeviceIdentifier.id`**
| | | | | `DeviceDefinition.udiDeviceIdentifier.extension`| _Equivalent_<br/>(25632/25633)| `DeviceDefinition.udiDeviceIdentifier.extension`| _Equivalent_<br/>(40559/40560)| **`DeviceDefinition.udiDeviceIdentifier.extension`**
| | | | | `DeviceDefinition.udiDeviceIdentifier.modifierExtension`| _Equivalent_<br/>(25634/25635)| `DeviceDefinition.udiDeviceIdentifier.modifierExtension`| _Equivalent_<br/>(40561/40562)| **`DeviceDefinition.udiDeviceIdentifier.modifierExtension`**
| | | | | `DeviceDefinition.udiDeviceIdentifier.deviceIdentifier`| _Equivalent_<br/>(25636/25637)| `DeviceDefinition.udiDeviceIdentifier.deviceIdentifier`| _Equivalent_<br/>(40563/40564)| **`DeviceDefinition.udiDeviceIdentifier.deviceIdentifier`**
| | | | | `DeviceDefinition.udiDeviceIdentifier.issuer`| _Equivalent_<br/>(25638/25639)| `DeviceDefinition.udiDeviceIdentifier.issuer`| _Equivalent_<br/>(40565/40566)| **`DeviceDefinition.udiDeviceIdentifier.issuer`**
| | | | | `DeviceDefinition.udiDeviceIdentifier.jurisdiction`| _Equivalent_<br/>(25640/25641)| `DeviceDefinition.udiDeviceIdentifier.jurisdiction`| _Equivalent_<br/>(40567/40568)| **`DeviceDefinition.udiDeviceIdentifier.jurisdiction`**
| | | | | | | | | **`DeviceDefinition.udiDeviceIdentifier.marketDistribution`**
| | | | | | | | | **`DeviceDefinition.udiDeviceIdentifier.marketDistribution.id`**
| | | | | | | | | **`DeviceDefinition.udiDeviceIdentifier.marketDistribution.extension`**
| | | | | | | | | **`DeviceDefinition.udiDeviceIdentifier.marketDistribution.modifierExtension`**
| | | | | | | | | **`DeviceDefinition.udiDeviceIdentifier.marketDistribution.marketPeriod`**
| | | | | | | | | **`DeviceDefinition.udiDeviceIdentifier.marketDistribution.subJurisdiction`**
| | | | | | | | | **`DeviceDefinition.regulatoryIdentifier`**
| | | | | | | | | **`DeviceDefinition.regulatoryIdentifier.id`**
| | | | | | | | | **`DeviceDefinition.regulatoryIdentifier.extension`**
| | | | | | | | | **`DeviceDefinition.regulatoryIdentifier.modifierExtension`**
| | | | | | | | | **`DeviceDefinition.regulatoryIdentifier.type`**
| | | | | | | | | **`DeviceDefinition.regulatoryIdentifier.deviceIdentifier`**
| | | | | | | | | **`DeviceDefinition.regulatoryIdentifier.issuer`**
| | | | | | | | | **`DeviceDefinition.regulatoryIdentifier.jurisdiction`**
| | | | | | | | | **`DeviceDefinition.partNumber`**
| | | | | `DeviceDefinition.manufacturer[x]`| _Equivalent_<br/>(25642/25643)| `DeviceDefinition.manufacturer[x]`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1763)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2006)| **`DeviceDefinition.manufacturer`**
| | | | | `DeviceDefinition.deviceName`| _Equivalent_<br/>(25644/25645)| `DeviceDefinition.deviceName`| _Equivalent_<br/>(40569/40570)| **`DeviceDefinition.deviceName`**
| | | | | `DeviceDefinition.deviceName.id`| _Equivalent_<br/>(25646/25647)| `DeviceDefinition.deviceName.id`| _Equivalent_<br/>(40571/40572)| **`DeviceDefinition.deviceName.id`**
| | | | | `DeviceDefinition.deviceName.extension`| _Equivalent_<br/>(25648/25649)| `DeviceDefinition.deviceName.extension`| _Equivalent_<br/>(40573/40574)| **`DeviceDefinition.deviceName.extension`**
| | | | | `DeviceDefinition.deviceName.modifierExtension`| _Equivalent_<br/>(25650/25651)| `DeviceDefinition.deviceName.modifierExtension`| _Equivalent_<br/>(40575/40576)| **`DeviceDefinition.deviceName.modifierExtension`**
| | | | | `DeviceDefinition.deviceName.name`| _Equivalent_<br/>(25652/25653)| `DeviceDefinition.deviceName.name`| _Equivalent_<br/>(40577/40578)| **`DeviceDefinition.deviceName.name`**
| | | | | `DeviceDefinition.deviceName.type`| _Equivalent_<br/>(25654/25655)| `DeviceDefinition.deviceName.type`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(40579)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(40580)| **`DeviceDefinition.deviceName.type`**
| | | | | `DeviceDefinition.modelNumber`| _Equivalent_<br/>(25656/25657)| `DeviceDefinition.modelNumber`| _Equivalent_<br/>(40581/40582)| **`DeviceDefinition.modelNumber`**
| | | | | | | | | **`DeviceDefinition.classification`**
| | | | | | | | | **`DeviceDefinition.classification.id`**
| | | | | | | | | **`DeviceDefinition.classification.extension`**
| | | | | | | | | **`DeviceDefinition.classification.modifierExtension`**
| | | | | | | | | **`DeviceDefinition.classification.type`**
| | | | | | | | | **`DeviceDefinition.classification.justification`**
| | | | | `DeviceDefinition.specialization`| _Equivalent_<br/>(25660/25661)| `DeviceDefinition.specialization`| _Equivalent_<br/>(1764/2007)| **`DeviceDefinition.conformsTo`**
| | | | | | | | | **`DeviceDefinition.conformsTo.id`**
| | | | | | | | | **`DeviceDefinition.conformsTo.extension`**
| | | | | | | | | **`DeviceDefinition.conformsTo.modifierExtension`**
| | | | | | | | | **`DeviceDefinition.conformsTo.category`**
| | | | | | | | | **`DeviceDefinition.conformsTo.specification`**
| | | | | `DeviceDefinition.specialization.version`| _Equivalent_<br/>(25670/25671)| `DeviceDefinition.specialization.version`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1765)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2008)| **`DeviceDefinition.conformsTo.version`**
| | | | | | | | | **`DeviceDefinition.conformsTo.source`**
| | | | | | | | | **`DeviceDefinition.hasPart`**
| | | | | | | | | **`DeviceDefinition.hasPart.id`**
| | | | | | | | | **`DeviceDefinition.hasPart.extension`**
| | | | | | | | | **`DeviceDefinition.hasPart.modifierExtension`**
| | | | | | | | | **`DeviceDefinition.hasPart.reference`**
| | | | | | | | | **`DeviceDefinition.hasPart.count`**
| | | | | | | | | **`DeviceDefinition.packaging`**
| | | | | | | | | **`DeviceDefinition.packaging.id`**
| | | | | | | | | **`DeviceDefinition.packaging.extension`**
| | | | | | | | | **`DeviceDefinition.packaging.modifierExtension`**
| | | | | | | | | **`DeviceDefinition.packaging.identifier`**
| | | | | | | | | **`DeviceDefinition.packaging.type`**
| | | | | | | | | **`DeviceDefinition.packaging.count`**
| | | | | | | | | **`DeviceDefinition.packaging.distributor`**
| | | | | | | | | **`DeviceDefinition.packaging.distributor.id`**
| | | | | | | | | **`DeviceDefinition.packaging.distributor.extension`**
| | | | | | | | | **`DeviceDefinition.packaging.distributor.modifierExtension`**
| | | | | | | | | **`DeviceDefinition.packaging.distributor.name`**
| | | | | | | | | **`DeviceDefinition.packaging.distributor.organizationReference`**
| | | | | | | | | **`DeviceDefinition.packaging.udiDeviceIdentifier`**
| | | | | | | | | **`DeviceDefinition.packaging.packaging`**
| | | | | `DeviceDefinition.version`| _Equivalent_<br/>(25672/25673)| `DeviceDefinition.version`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(40588)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40589)| **`DeviceDefinition.version`**
| | | | | | | | | **`DeviceDefinition.version.id`**
| | | | | | | | | **`DeviceDefinition.version.extension`**
| | | | | | | | | **`DeviceDefinition.version.modifierExtension`**
| | | | | | | | | **`DeviceDefinition.version.type`**
| | | | | | | | | **`DeviceDefinition.version.component`**
| | | | | | | | | **`DeviceDefinition.version.value`**
| | | | | `DeviceDefinition.safety`| _Equivalent_<br/>(25674/25675)| `DeviceDefinition.safety`| _Equivalent_<br/>(40590/40591)| **`DeviceDefinition.safety`**
| | | | | `DeviceDefinition.shelfLifeStorage`| _Equivalent_<br/>(25676/25677)| `DeviceDefinition.shelfLifeStorage`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(40592)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(40593)| **`DeviceDefinition.shelfLifeStorage`**
| | | | | `DeviceDefinition.languageCode`| _Equivalent_<br/>(25680/25681)| `DeviceDefinition.languageCode`| _Equivalent_<br/>(40595/40596)| **`DeviceDefinition.languageCode`**
| | | | | `DeviceDefinition.property`| _Equivalent_<br/>(25694/25695)| `DeviceDefinition.property`| _Equivalent_<br/>(40603/40604)| **`DeviceDefinition.property`**
| | | | | `DeviceDefinition.property.id`| _Equivalent_<br/>(25696/25697)| `DeviceDefinition.property.id`| _Equivalent_<br/>(40605/40606)| **`DeviceDefinition.property.id`**
| | | | | `DeviceDefinition.property.extension`| _Equivalent_<br/>(25698/25699)| `DeviceDefinition.property.extension`| _Equivalent_<br/>(40607/40608)| **`DeviceDefinition.property.extension`**
| | | | | `DeviceDefinition.property.modifierExtension`| _Equivalent_<br/>(25700/25701)| `DeviceDefinition.property.modifierExtension`| _Equivalent_<br/>(40609/40610)| **`DeviceDefinition.property.modifierExtension`**
| | | | | `DeviceDefinition.property.type`| _Equivalent_<br/>(25702/25703)| `DeviceDefinition.property.type`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(40611)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(40612)| **`DeviceDefinition.property.type`**
| | | | | `DeviceDefinition.property.valueQuantity`| _Equivalent_<br/>(25704/25705)| `DeviceDefinition.property.valueQuantity`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1766)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2010)| **`DeviceDefinition.property.value[x]`**
| | | | | `DeviceDefinition.property.valueCode`| _Equivalent_<br/>(25706/25707)| `DeviceDefinition.property.valueCode`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1767)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2010)| **`DeviceDefinition.property.value[x]`**
| | | | | `DeviceDefinition.owner`| _Equivalent_<br/>(25708/25709)| `DeviceDefinition.owner`| _Equivalent_<br/>(40613/40614)| **`DeviceDefinition.owner`**
| | | | | `DeviceDefinition.contact`| _Equivalent_<br/>(25710/25711)| `DeviceDefinition.contact`| _Equivalent_<br/>(40615/40616)| **`DeviceDefinition.contact`**
| | | | | | | | | **`DeviceDefinition.link`**
| | | | | | | | | **`DeviceDefinition.link.id`**
| | | | | | | | | **`DeviceDefinition.link.extension`**
| | | | | | | | | **`DeviceDefinition.link.modifierExtension`**
| | | | | | | | | **`DeviceDefinition.link.relation`**
| | | | | | | | | **`DeviceDefinition.link.relatedDevice`**
| | | | | `DeviceDefinition.note`| _Equivalent_<br/>(25716/25717)| `DeviceDefinition.note`| _Equivalent_<br/>(40619/40620)| **`DeviceDefinition.note`**
| | | | | `DeviceDefinition.material`| _Equivalent_<br/>(25722/25723)| `DeviceDefinition.material`| _Equivalent_<br/>(40623/40624)| **`DeviceDefinition.material`**
| | | | | `DeviceDefinition.material.id`| _Equivalent_<br/>(25724/25725)| `DeviceDefinition.material.id`| _Equivalent_<br/>(40625/40626)| **`DeviceDefinition.material.id`**
| | | | | `DeviceDefinition.material.extension`| _Equivalent_<br/>(25726/25727)| `DeviceDefinition.material.extension`| _Equivalent_<br/>(40627/40628)| **`DeviceDefinition.material.extension`**
| | | | | `DeviceDefinition.material.modifierExtension`| _Equivalent_<br/>(25728/25729)| `DeviceDefinition.material.modifierExtension`| _Equivalent_<br/>(40629/40630)| **`DeviceDefinition.material.modifierExtension`**
| | | | | `DeviceDefinition.material.substance`| _Equivalent_<br/>(25730/25731)| `DeviceDefinition.material.substance`| _Equivalent_<br/>(40631/40632)| **`DeviceDefinition.material.substance`**
| | | | | `DeviceDefinition.material.alternate`| _Equivalent_<br/>(25732/25733)| `DeviceDefinition.material.alternate`| _Equivalent_<br/>(40633/40634)| **`DeviceDefinition.material.alternate`**
| | | | | `DeviceDefinition.material.allergenicIndicator`| _Equivalent_<br/>(25734/25735)| `DeviceDefinition.material.allergenicIndicator`| _Equivalent_<br/>(40635/40636)| **`DeviceDefinition.material.allergenicIndicator`**
| | | | | | | | | **`DeviceDefinition.productionIdentifierInUDI`**
| | | | | | | | | **`DeviceDefinition.guideline`**
| | | | | | | | | **`DeviceDefinition.guideline.id`**
| | | | | | | | | **`DeviceDefinition.guideline.extension`**
| | | | | | | | | **`DeviceDefinition.guideline.modifierExtension`**
| | | | | | | | | **`DeviceDefinition.guideline.useContext`**
| | | | | | | | | **`DeviceDefinition.guideline.usageInstruction`**
| | | | | | | | | **`DeviceDefinition.guideline.relatedArtifact`**
| | | | | | | | | **`DeviceDefinition.guideline.indication`**
| | | | | | | | | **`DeviceDefinition.guideline.contraindication`**
| | | | | | | | | **`DeviceDefinition.guideline.warning`**
| | | | | | | | | **`DeviceDefinition.guideline.intendedUse`**
| | | | | | | | | **`DeviceDefinition.correctiveAction`**
| | | | | | | | | **`DeviceDefinition.correctiveAction.id`**
| | | | | | | | | **`DeviceDefinition.correctiveAction.extension`**
| | | | | | | | | **`DeviceDefinition.correctiveAction.modifierExtension`**
| | | | | | | | | **`DeviceDefinition.correctiveAction.recall`**
| | | | | | | | | **`DeviceDefinition.correctiveAction.scope`**
| | | | | | | | | **`DeviceDefinition.correctiveAction.period`**
| | | | | | | | | **`DeviceDefinition.chargeItem`**
| | | | | | | | | **`DeviceDefinition.chargeItem.id`**
| | | | | | | | | **`DeviceDefinition.chargeItem.extension`**
| | | | | | | | | **`DeviceDefinition.chargeItem.modifierExtension`**
| | | | | | | | | **`DeviceDefinition.chargeItem.chargeItemCode`**
| | | | | | | | | **`DeviceDefinition.chargeItem.count`**
| | | | | | | | | **`DeviceDefinition.chargeItem.effectivePeriod`**
| | | | | | | | | **`DeviceDefinition.chargeItem.useContext`**
| | | | | *48 of 64 elements used* | | *48 of 64 elements used* | | *135 of 135 elements used* 

