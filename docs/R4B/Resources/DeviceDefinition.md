Comparison of 
Generated at Friday, April 4, 2025 2:58:56 PM

### DeviceDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | DeviceDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/DeviceDefinition` |
| Version | 4.3.0 |
| Description | The characteristics, operational status and capabilities of a medical-related component of a medical device. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1676` |
| Database Snapshot Count | `64` |
| Database Differential Count | `38` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `DeviceDefinition` | `DeviceDefinition` | `DeviceDefinition` | DeviceDefinition | An instance of a medical-related component of a medical device | 0..* | DeviceDefinition |  |  |
| `DeviceDefinition.capability` | `DeviceDefinition.capability` | `capability` | DeviceDefinition.capability | Device capabilities | 0..* | BackboneElement |  |  |
| `DeviceDefinition.capability.description` | `DeviceDefinition.capability.description` | `description` | DeviceDefinition.capability.description | Description of capability | 0..* | CodeableConcept |  |  |
| `DeviceDefinition.capability.extension` | `DeviceDefinition.capability.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDefinition.capability.id` | `DeviceDefinition.capability.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceDefinition.capability.modifierExtension` | `DeviceDefinition.capability.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceDefinition.capability.type` | `DeviceDefinition.capability.type` | `type` | DeviceDefinition.capability.type | Type of capability | 1..1 | CodeableConcept |  |  |
| `DeviceDefinition.contact` | `DeviceDefinition.contact` | `contact` | DeviceDefinition.contact | Details for human/organization for support | 0..* | ContactPoint |  |  |
| `DeviceDefinition.contained` | `DeviceDefinition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `DeviceDefinition.deviceName` | `DeviceDefinition.deviceName` | `deviceName` | DeviceDefinition.deviceName | A name given to the device to identify it | 0..* | BackboneElement |  |  |
| `DeviceDefinition.deviceName.extension` | `DeviceDefinition.deviceName.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDefinition.deviceName.id` | `DeviceDefinition.deviceName.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceDefinition.deviceName.modifierExtension` | `DeviceDefinition.deviceName.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceDefinition.deviceName.name` | `DeviceDefinition.deviceName.name` | `name` | DeviceDefinition.deviceName.name | The name of the device | 1..1 | string |  |  |
| `DeviceDefinition.deviceName.type` | `DeviceDefinition.deviceName.type` | `type` | DeviceDefinition.deviceName.type | udi-label-name \| user-friendly-name \| patient-reported-name \| manufacturer-name \| model-name \| other | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/device-nametype|4.3.0` |
| `DeviceDefinition.extension` | `DeviceDefinition.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDefinition.id` | `DeviceDefinition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `DeviceDefinition.identifier` | `DeviceDefinition.identifier` | `identifier` | DeviceDefinition.identifier | Instance identifier | 0..* | Identifier |  |  |
| `DeviceDefinition.implicitRules` | `DeviceDefinition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `DeviceDefinition.language` | `DeviceDefinition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `DeviceDefinition.languageCode` | `DeviceDefinition.languageCode` | `languageCode` | DeviceDefinition.languageCode | Language code for the human-readable text strings produced by the device (all supported) | 0..* | CodeableConcept |  |  |
| `DeviceDefinition.manufacturer[x]` | `DeviceDefinition.manufacturer[x]` | `manufacturer[x]` | DeviceDefinition.manufacturer[x] | Name of device manufacturer | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), string |  |  |
| `DeviceDefinition.material` | `DeviceDefinition.material` | `material` | DeviceDefinition.material | A substance used to create the material(s) of which the device is made | 0..* | BackboneElement |  |  |
| `DeviceDefinition.material.allergenicIndicator` | `DeviceDefinition.material.allergenicIndicator` | `allergenicIndicator` | DeviceDefinition.material.allergenicIndicator | Whether the substance is a known or suspected allergen | 0..1 | boolean |  |  |
| `DeviceDefinition.material.alternate` | `DeviceDefinition.material.alternate` | `alternate` | DeviceDefinition.material.alternate | Indicates an alternative material of the device | 0..1 | boolean |  |  |
| `DeviceDefinition.material.extension` | `DeviceDefinition.material.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDefinition.material.id` | `DeviceDefinition.material.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceDefinition.material.modifierExtension` | `DeviceDefinition.material.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceDefinition.material.substance` | `DeviceDefinition.material.substance` | `substance` | DeviceDefinition.material.substance | The substance | 1..1 | CodeableConcept |  |  |
| `DeviceDefinition.meta` | `DeviceDefinition.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `DeviceDefinition.modelNumber` | `DeviceDefinition.modelNumber` | `modelNumber` | DeviceDefinition.modelNumber | The model number for the device | 0..1 | string |  |  |
| `DeviceDefinition.modifierExtension` | `DeviceDefinition.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DeviceDefinition.note` | `DeviceDefinition.note` | `note` | DeviceDefinition.note | Device notes and comments | 0..* | Annotation |  |  |
| `DeviceDefinition.onlineInformation` | `DeviceDefinition.onlineInformation` | `onlineInformation` | DeviceDefinition.onlineInformation | Access to on-line information | 0..1 | uri |  |  |
| `DeviceDefinition.owner` | `DeviceDefinition.owner` | `owner` | DeviceDefinition.owner | Organization responsible for device | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `DeviceDefinition.parentDevice` | `DeviceDefinition.parentDevice` | `parentDevice` | DeviceDefinition.parentDevice | The parent device it can be part of | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/DeviceDefinition) |  |  |
| `DeviceDefinition.physicalCharacteristics` | `DeviceDefinition.physicalCharacteristics` | `physicalCharacteristics` | DeviceDefinition.physicalCharacteristics | Dimensions, color etc. | 0..1 | ProdCharacteristic |  |  |
| `DeviceDefinition.property` | `DeviceDefinition.property` | `property` | DeviceDefinition.property | The actual configuration settings of a device as it actually operates, e.g., regulation status, time properties | 0..* | BackboneElement |  |  |
| `DeviceDefinition.property.extension` | `DeviceDefinition.property.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDefinition.property.id` | `DeviceDefinition.property.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceDefinition.property.modifierExtension` | `DeviceDefinition.property.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceDefinition.property.type` | `DeviceDefinition.property.type` | `type` | DeviceDefinition.property.type | Code that specifies the property DeviceDefinitionPropetyCode (Extensible) | 1..1 | CodeableConcept |  |  |
| `DeviceDefinition.property.valueCode` | `DeviceDefinition.property.valueCode` | `valueCode` | DeviceDefinition.property.valueCode | Property value as a code, e.g., NTP4 (synced to NTP) | 0..* | CodeableConcept |  |  |
| `DeviceDefinition.property.valueQuantity` | `DeviceDefinition.property.valueQuantity` | `valueQuantity` | DeviceDefinition.property.valueQuantity | Property value as a quantity | 0..* | Quantity |  |  |
| `DeviceDefinition.quantity` | `DeviceDefinition.quantity` | `quantity` | DeviceDefinition.quantity | The quantity of the device present in the packaging (e.g. the number of devices present in a pack, or the number of devices in the same package of the medicinal product) | 0..1 | Quantity |  |  |
| `DeviceDefinition.safety` | `DeviceDefinition.safety` | `safety` | DeviceDefinition.safety | Safety characteristics of the device | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/device-safety` |
| `DeviceDefinition.shelfLifeStorage` | `DeviceDefinition.shelfLifeStorage` | `shelfLifeStorage` | DeviceDefinition.shelfLifeStorage | Shelf Life and storage information | 0..* | ProductShelfLife |  |  |
| `DeviceDefinition.specialization` | `DeviceDefinition.specialization` | `specialization` | DeviceDefinition.specialization | The capabilities supported on a  device, the standards to which the device conforms for a particular purpose, and used for the communication | 0..* | BackboneElement |  |  |
| `DeviceDefinition.specialization.extension` | `DeviceDefinition.specialization.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDefinition.specialization.id` | `DeviceDefinition.specialization.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceDefinition.specialization.modifierExtension` | `DeviceDefinition.specialization.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceDefinition.specialization.systemType` | `DeviceDefinition.specialization.systemType` | `systemType` | DeviceDefinition.specialization.systemType | The standard that is used to operate and communicate | 1..1 | string |  |  |
| `DeviceDefinition.specialization.version` | `DeviceDefinition.specialization.version` | `version` | DeviceDefinition.specialization.version | The version of the standard that is used to operate and communicate | 0..1 | string |  |  |
| `DeviceDefinition.text` | `DeviceDefinition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `DeviceDefinition.type` | `DeviceDefinition.type` | `type` | DeviceDefinition.type | What kind of device or device system this is | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/device-kind` |
| `DeviceDefinition.udiDeviceIdentifier` | `DeviceDefinition.udiDeviceIdentifier` | `udiDeviceIdentifier` | DeviceDefinition.udiDeviceIdentifier | Unique Device Identifier (UDI) Barcode string | 0..* | BackboneElement |  |  |
| `DeviceDefinition.udiDeviceIdentifier.deviceIdentifier` | `DeviceDefinition.udiDeviceIdentifier.deviceIdentifier` | `deviceIdentifier` | DeviceDefinition.udiDeviceIdentifier.deviceIdentifier | The identifier that is to be associated with every Device that references this DeviceDefintiion for the issuer and jurisdication porvided in the DeviceDefinition.udiDeviceIdentifier | 1..1 | string |  |  |
| `DeviceDefinition.udiDeviceIdentifier.extension` | `DeviceDefinition.udiDeviceIdentifier.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceDefinition.udiDeviceIdentifier.id` | `DeviceDefinition.udiDeviceIdentifier.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceDefinition.udiDeviceIdentifier.issuer` | `DeviceDefinition.udiDeviceIdentifier.issuer` | `issuer` | DeviceDefinition.udiDeviceIdentifier.issuer | The organization that assigns the identifier algorithm | 1..1 | uri |  |  |
| `DeviceDefinition.udiDeviceIdentifier.jurisdiction` | `DeviceDefinition.udiDeviceIdentifier.jurisdiction` | `jurisdiction` | DeviceDefinition.udiDeviceIdentifier.jurisdiction | The jurisdiction to which the deviceIdentifier applies | 1..1 | uri |  |  |
| `DeviceDefinition.udiDeviceIdentifier.modifierExtension` | `DeviceDefinition.udiDeviceIdentifier.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceDefinition.url` | `DeviceDefinition.url` | `url` | DeviceDefinition.url | Network address to contact device | 0..1 | uri |  |  |
| `DeviceDefinition.version` | `DeviceDefinition.version` | `version` | DeviceDefinition.version | Available versions | 0..* | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [DeviceDefinition](/docs/R4/Resources/DeviceDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceDefinition\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1457`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1458`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceDefinition](/docs/R4B/Resources/DeviceDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceDefinition\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `963`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1192`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceDefinition](/docs/R5/Resources/DeviceDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceDefinition\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition DeviceDefinition from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | [R4 DeviceDefinition](/docs/R4/Resources/DeviceDefinition.md)| Relationship | R4B DeviceDefinition| Relationship | [R5 DeviceDefinition](/docs/R5/Resources/DeviceDefinition.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `DeviceDefinition`| _Equivalent_<br/>(25608/25609)| **`DeviceDefinition`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(40535)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40536)| `DeviceDefinition`
| | | | | `DeviceDefinition.id`| _Equivalent_<br/>(25610/25611)| **`DeviceDefinition.id`**| _Equivalent_<br/>(40537/40538)| `DeviceDefinition.id`
| | | | | `DeviceDefinition.meta`| _Equivalent_<br/>(25612/25613)| **`DeviceDefinition.meta`**| _Equivalent_<br/>(40539/40540)| `DeviceDefinition.meta`
| | | | | `DeviceDefinition.implicitRules`| _Equivalent_<br/>(25614/25615)| **`DeviceDefinition.implicitRules`**| _Equivalent_<br/>(40541/40542)| `DeviceDefinition.implicitRules`
| | | | | `DeviceDefinition.language`| _Equivalent_<br/>(25616/25617)| **`DeviceDefinition.language`**| _Equivalent_<br/>(40543/40544)| `DeviceDefinition.language`
| | | | | `DeviceDefinition.text`| _Equivalent_<br/>(25618/25619)| **`DeviceDefinition.text`**| _Equivalent_<br/>(40545/40546)| `DeviceDefinition.text`
| | | | | `DeviceDefinition.contained`| _Equivalent_<br/>(25620/25621)| **`DeviceDefinition.contained`**| _Equivalent_<br/>(40547/40548)| `DeviceDefinition.contained`
| | | | | `DeviceDefinition.extension`| _Equivalent_<br/>(25622/25623)| **`DeviceDefinition.extension`**| _Equivalent_<br/>(40549/40550)| `DeviceDefinition.extension`
| | | | | `DeviceDefinition.modifierExtension`| _Equivalent_<br/>(25624/25625)| **`DeviceDefinition.modifierExtension`**| _Equivalent_<br/>(40551/40552)| `DeviceDefinition.modifierExtension`
| | | | | `DeviceDefinition.identifier`| _Equivalent_<br/>(25626/25627)| **`DeviceDefinition.identifier`**| _Equivalent_<br/>(40553/40554)| `DeviceDefinition.identifier`
| | | | | `DeviceDefinition.udiDeviceIdentifier`| _Equivalent_<br/>(25628/25629)| **`DeviceDefinition.udiDeviceIdentifier`**| _Equivalent_<br/>(40555/40556)| `DeviceDefinition.udiDeviceIdentifier`
| | | | | `DeviceDefinition.udiDeviceIdentifier.id`| _Equivalent_<br/>(25630/25631)| **`DeviceDefinition.udiDeviceIdentifier.id`**| _Equivalent_<br/>(40557/40558)| `DeviceDefinition.udiDeviceIdentifier.id`
| | | | | `DeviceDefinition.udiDeviceIdentifier.extension`| _Equivalent_<br/>(25632/25633)| **`DeviceDefinition.udiDeviceIdentifier.extension`**| _Equivalent_<br/>(40559/40560)| `DeviceDefinition.udiDeviceIdentifier.extension`
| | | | | `DeviceDefinition.udiDeviceIdentifier.modifierExtension`| _Equivalent_<br/>(25634/25635)| **`DeviceDefinition.udiDeviceIdentifier.modifierExtension`**| _Equivalent_<br/>(40561/40562)| `DeviceDefinition.udiDeviceIdentifier.modifierExtension`
| | | | | `DeviceDefinition.udiDeviceIdentifier.deviceIdentifier`| _Equivalent_<br/>(25636/25637)| **`DeviceDefinition.udiDeviceIdentifier.deviceIdentifier`**| _Equivalent_<br/>(40563/40564)| `DeviceDefinition.udiDeviceIdentifier.deviceIdentifier`
| | | | | `DeviceDefinition.udiDeviceIdentifier.issuer`| _Equivalent_<br/>(25638/25639)| **`DeviceDefinition.udiDeviceIdentifier.issuer`**| _Equivalent_<br/>(40565/40566)| `DeviceDefinition.udiDeviceIdentifier.issuer`
| | | | | `DeviceDefinition.udiDeviceIdentifier.jurisdiction`| _Equivalent_<br/>(25640/25641)| **`DeviceDefinition.udiDeviceIdentifier.jurisdiction`**| _Equivalent_<br/>(40567/40568)| `DeviceDefinition.udiDeviceIdentifier.jurisdiction`
| | | | | `DeviceDefinition.manufacturer[x]`| _Equivalent_<br/>(25642/25643)| **`DeviceDefinition.manufacturer[x]`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1763)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2006)| `DeviceDefinition.manufacturer`
| | | | | `DeviceDefinition.deviceName`| _Equivalent_<br/>(25644/25645)| **`DeviceDefinition.deviceName`**| _Equivalent_<br/>(40569/40570)| `DeviceDefinition.deviceName`
| | | | | `DeviceDefinition.deviceName.id`| _Equivalent_<br/>(25646/25647)| **`DeviceDefinition.deviceName.id`**| _Equivalent_<br/>(40571/40572)| `DeviceDefinition.deviceName.id`
| | | | | `DeviceDefinition.deviceName.extension`| _Equivalent_<br/>(25648/25649)| **`DeviceDefinition.deviceName.extension`**| _Equivalent_<br/>(40573/40574)| `DeviceDefinition.deviceName.extension`
| | | | | `DeviceDefinition.deviceName.modifierExtension`| _Equivalent_<br/>(25650/25651)| **`DeviceDefinition.deviceName.modifierExtension`**| _Equivalent_<br/>(40575/40576)| `DeviceDefinition.deviceName.modifierExtension`
| | | | | `DeviceDefinition.deviceName.name`| _Equivalent_<br/>(25652/25653)| **`DeviceDefinition.deviceName.name`**| _Equivalent_<br/>(40577/40578)| `DeviceDefinition.deviceName.name`
| | | | | `DeviceDefinition.deviceName.type`| _Equivalent_<br/>(25654/25655)| **`DeviceDefinition.deviceName.type`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(40579)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(40580)| `DeviceDefinition.deviceName.type`
| | | | | `DeviceDefinition.modelNumber`| _Equivalent_<br/>(25656/25657)| **`DeviceDefinition.modelNumber`**| _Equivalent_<br/>(40581/40582)| `DeviceDefinition.modelNumber`
| | | | | `DeviceDefinition.type`| _Equivalent_<br/>(25658/25659)| **`DeviceDefinition.type`**| | | 
| | | | | `DeviceDefinition.specialization`| _Equivalent_<br/>(25660/25661)| **`DeviceDefinition.specialization`**| _Equivalent_<br/>(1764/2007)| `DeviceDefinition.conformsTo`
| | | | | `DeviceDefinition.specialization.id`| _Equivalent_<br/>(25662/25663)| **`DeviceDefinition.specialization.id`**| | | 
| | | | | `DeviceDefinition.specialization.extension`| _Equivalent_<br/>(25664/25665)| **`DeviceDefinition.specialization.extension`**| | | 
| | | | | `DeviceDefinition.specialization.modifierExtension`| _Equivalent_<br/>(25666/25667)| **`DeviceDefinition.specialization.modifierExtension`**| | | 
| | | | | `DeviceDefinition.specialization.systemType`| _Equivalent_<br/>(25668/25669)| **`DeviceDefinition.specialization.systemType`**| | | 
| | | | | `DeviceDefinition.specialization.version`| _Equivalent_<br/>(25670/25671)| **`DeviceDefinition.specialization.version`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1765)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2008)| `DeviceDefinition.conformsTo.version`
| | | | | `DeviceDefinition.version`| _Equivalent_<br/>(25672/25673)| **`DeviceDefinition.version`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(40588)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40589)| `DeviceDefinition.version`
| | | | | `DeviceDefinition.safety`| _Equivalent_<br/>(25674/25675)| **`DeviceDefinition.safety`**| _Equivalent_<br/>(40590/40591)| `DeviceDefinition.safety`
| | | | | `DeviceDefinition.shelfLifeStorage`| _Equivalent_<br/>(25676/25677)| **`DeviceDefinition.shelfLifeStorage`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(40592)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(40593)| `DeviceDefinition.shelfLifeStorage`
| | | | | `DeviceDefinition.physicalCharacteristics`| _Equivalent_<br/>(25678/25679)| **`DeviceDefinition.physicalCharacteristics`**| | | 
| | | | | `DeviceDefinition.languageCode`| _Equivalent_<br/>(25680/25681)| **`DeviceDefinition.languageCode`**| _Equivalent_<br/>(40595/40596)| `DeviceDefinition.languageCode`
| | | | | `DeviceDefinition.capability`| _Equivalent_<br/>(25682/25683)| **`DeviceDefinition.capability`**| | | 
| | | | | `DeviceDefinition.capability.id`| _Equivalent_<br/>(25684/25685)| **`DeviceDefinition.capability.id`**| | | 
| | | | | `DeviceDefinition.capability.extension`| _Equivalent_<br/>(25686/25687)| **`DeviceDefinition.capability.extension`**| | | 
| | | | | `DeviceDefinition.capability.modifierExtension`| _Equivalent_<br/>(25688/25689)| **`DeviceDefinition.capability.modifierExtension`**| | | 
| | | | | `DeviceDefinition.capability.type`| _Equivalent_<br/>(25690/25691)| **`DeviceDefinition.capability.type`**| | | 
| | | | | `DeviceDefinition.capability.description`| _Equivalent_<br/>(25692/25693)| **`DeviceDefinition.capability.description`**| | | 
| | | | | `DeviceDefinition.property`| _Equivalent_<br/>(25694/25695)| **`DeviceDefinition.property`**| _Equivalent_<br/>(40603/40604)| `DeviceDefinition.property`
| | | | | `DeviceDefinition.property.id`| _Equivalent_<br/>(25696/25697)| **`DeviceDefinition.property.id`**| _Equivalent_<br/>(40605/40606)| `DeviceDefinition.property.id`
| | | | | `DeviceDefinition.property.extension`| _Equivalent_<br/>(25698/25699)| **`DeviceDefinition.property.extension`**| _Equivalent_<br/>(40607/40608)| `DeviceDefinition.property.extension`
| | | | | `DeviceDefinition.property.modifierExtension`| _Equivalent_<br/>(25700/25701)| **`DeviceDefinition.property.modifierExtension`**| _Equivalent_<br/>(40609/40610)| `DeviceDefinition.property.modifierExtension`
| | | | | `DeviceDefinition.property.type`| _Equivalent_<br/>(25702/25703)| **`DeviceDefinition.property.type`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(40611)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(40612)| `DeviceDefinition.property.type`
| | | | | `DeviceDefinition.property.valueQuantity`| _Equivalent_<br/>(25704/25705)| **`DeviceDefinition.property.valueQuantity`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1766)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2009)| `DeviceDefinition.property.value[x]`
| | | | | `DeviceDefinition.property.valueCode`| _Equivalent_<br/>(25706/25707)| **`DeviceDefinition.property.valueCode`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1767)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2010)| `DeviceDefinition.property.value[x]`
| | | | | `DeviceDefinition.owner`| _Equivalent_<br/>(25708/25709)| **`DeviceDefinition.owner`**| _Equivalent_<br/>(40613/40614)| `DeviceDefinition.owner`
| | | | | `DeviceDefinition.contact`| _Equivalent_<br/>(25710/25711)| **`DeviceDefinition.contact`**| _Equivalent_<br/>(40615/40616)| `DeviceDefinition.contact`
| | | | | `DeviceDefinition.url`| _Equivalent_<br/>(25712/25713)| **`DeviceDefinition.url`**| | | 
| | | | | `DeviceDefinition.onlineInformation`| _Equivalent_<br/>(25714/25715)| **`DeviceDefinition.onlineInformation`**| | | 
| | | | | `DeviceDefinition.note`| _Equivalent_<br/>(25716/25717)| **`DeviceDefinition.note`**| _Equivalent_<br/>(40619/40620)| `DeviceDefinition.note`
| | | | | `DeviceDefinition.quantity`| _Equivalent_<br/>(25718/25719)| **`DeviceDefinition.quantity`**| | | 
| | | | | `DeviceDefinition.parentDevice`| _Equivalent_<br/>(25720/25721)| **`DeviceDefinition.parentDevice`**| | | 
| | | | | `DeviceDefinition.material`| _Equivalent_<br/>(25722/25723)| **`DeviceDefinition.material`**| _Equivalent_<br/>(40623/40624)| `DeviceDefinition.material`
| | | | | `DeviceDefinition.material.id`| _Equivalent_<br/>(25724/25725)| **`DeviceDefinition.material.id`**| _Equivalent_<br/>(40625/40626)| `DeviceDefinition.material.id`
| | | | | `DeviceDefinition.material.extension`| _Equivalent_<br/>(25726/25727)| **`DeviceDefinition.material.extension`**| _Equivalent_<br/>(40627/40628)| `DeviceDefinition.material.extension`
| | | | | `DeviceDefinition.material.modifierExtension`| _Equivalent_<br/>(25728/25729)| **`DeviceDefinition.material.modifierExtension`**| _Equivalent_<br/>(40629/40630)| `DeviceDefinition.material.modifierExtension`
| | | | | `DeviceDefinition.material.substance`| _Equivalent_<br/>(25730/25731)| **`DeviceDefinition.material.substance`**| _Equivalent_<br/>(40631/40632)| `DeviceDefinition.material.substance`
| | | | | `DeviceDefinition.material.alternate`| _Equivalent_<br/>(25732/25733)| **`DeviceDefinition.material.alternate`**| _Equivalent_<br/>(40633/40634)| `DeviceDefinition.material.alternate`
| | | | | `DeviceDefinition.material.allergenicIndicator`| _Equivalent_<br/>(25734/25735)| **`DeviceDefinition.material.allergenicIndicator`**| _Equivalent_<br/>(40635/40636)| `DeviceDefinition.material.allergenicIndicator`
| | | | | *64 of 64 elements used* | | *64 of 64 elements used* | | *47 of 135 elements used* <br/>remaining elements:<br/>`DeviceDefinition.chargeItem`, `DeviceDefinition.chargeItem.chargeItemCode`, `DeviceDefinition.chargeItem.count`, `DeviceDefinition.chargeItem.effectivePeriod`, `DeviceDefinition.chargeItem.extension`, `DeviceDefinition.chargeItem.id`, `DeviceDefinition.chargeItem.modifierExtension`, `DeviceDefinition.chargeItem.useContext`, `DeviceDefinition.classification`, `DeviceDefinition.classification.extension`, `DeviceDefinition.classification.id`, `DeviceDefinition.classification.justification`, `DeviceDefinition.classification.modifierExtension`, `DeviceDefinition.classification.type`, `DeviceDefinition.conformsTo.category`, `DeviceDefinition.conformsTo.extension`, `DeviceDefinition.conformsTo.id`, `DeviceDefinition.conformsTo.modifierExtension`, `DeviceDefinition.conformsTo.source`, `DeviceDefinition.conformsTo.specification`, `DeviceDefinition.correctiveAction`, `DeviceDefinition.correctiveAction.extension`, `DeviceDefinition.correctiveAction.id`, `DeviceDefinition.correctiveAction.modifierExtension`, `DeviceDefinition.correctiveAction.period`, `DeviceDefinition.correctiveAction.recall`, `DeviceDefinition.correctiveAction.scope`, `DeviceDefinition.description`, `DeviceDefinition.guideline`, `DeviceDefinition.guideline.contraindication`, `DeviceDefinition.guideline.extension`, `DeviceDefinition.guideline.id`, `DeviceDefinition.guideline.indication`, `DeviceDefinition.guideline.intendedUse`, `DeviceDefinition.guideline.modifierExtension`, `DeviceDefinition.guideline.relatedArtifact`, `DeviceDefinition.guideline.usageInstruction`, `DeviceDefinition.guideline.useContext`, `DeviceDefinition.guideline.warning`, `DeviceDefinition.hasPart`, `DeviceDefinition.hasPart.count`, `DeviceDefinition.hasPart.extension`, `DeviceDefinition.hasPart.id`, `DeviceDefinition.hasPart.modifierExtension`, `DeviceDefinition.hasPart.reference`, `DeviceDefinition.link`, `DeviceDefinition.link.extension`, `DeviceDefinition.link.id`, `DeviceDefinition.link.modifierExtension`, `DeviceDefinition.link.relatedDevice`, `DeviceDefinition.link.relation`, `DeviceDefinition.packaging`, `DeviceDefinition.packaging.count`, `DeviceDefinition.packaging.distributor`, `DeviceDefinition.packaging.distributor.extension`, `DeviceDefinition.packaging.distributor.id`, `DeviceDefinition.packaging.distributor.modifierExtension`, `DeviceDefinition.packaging.distributor.name`, `DeviceDefinition.packaging.distributor.organizationReference`, `DeviceDefinition.packaging.extension`, `DeviceDefinition.packaging.id`, `DeviceDefinition.packaging.identifier`, `DeviceDefinition.packaging.modifierExtension`, `DeviceDefinition.packaging.packaging`, `DeviceDefinition.packaging.type`, `DeviceDefinition.packaging.udiDeviceIdentifier`, `DeviceDefinition.partNumber`, `DeviceDefinition.productionIdentifierInUDI`, `DeviceDefinition.regulatoryIdentifier`, `DeviceDefinition.regulatoryIdentifier.deviceIdentifier`, `DeviceDefinition.regulatoryIdentifier.extension`, `DeviceDefinition.regulatoryIdentifier.id`, `DeviceDefinition.regulatoryIdentifier.issuer`, `DeviceDefinition.regulatoryIdentifier.jurisdiction`, `DeviceDefinition.regulatoryIdentifier.modifierExtension`, `DeviceDefinition.regulatoryIdentifier.type`, `DeviceDefinition.udiDeviceIdentifier.marketDistribution`, `DeviceDefinition.udiDeviceIdentifier.marketDistribution.extension`, `DeviceDefinition.udiDeviceIdentifier.marketDistribution.id`, `DeviceDefinition.udiDeviceIdentifier.marketDistribution.marketPeriod`, `DeviceDefinition.udiDeviceIdentifier.marketDistribution.modifierExtension`, `DeviceDefinition.udiDeviceIdentifier.marketDistribution.subJurisdiction`, `DeviceDefinition.version.component`, `DeviceDefinition.version.extension`, `DeviceDefinition.version.id`, `DeviceDefinition.version.modifierExtension`, `DeviceDefinition.version.type`, `DeviceDefinition.version.value`

