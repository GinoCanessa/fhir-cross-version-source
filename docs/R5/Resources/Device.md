Comparison of 
Generated at Thursday, April 3, 2025 8:18:34 AM

### Device

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Device |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Device` |
| Version | 5.0.0 |
| Description | This resource describes the properties (regulated, has real time clock, etc.), adminstrative (manufacturer name, model number, serial number, firmware, etc.), and type (knee replacement, blood pressure cuff, MRI, etc.) of a physical unit (these values do not change much within a given module, for example the serail number, manufacturer name, and model number). An actual unit may consist of several modules in a distinct hierarchy and these are represented by multiple Device resources and bound through the 'parent' element. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2288` |
| Database Snapshot Count | `74` |
| Database Differential Count | `51` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Device` | `Device` | `Device` | Device | Item used in healthcare | 0..* | Device |  |  |
| `Device.availabilityStatus` | `Device.availabilityStatus` | `availabilityStatus` | Device.availabilityStatus | lost \| damaged \| destroyed \| available | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/device-availability-status` |
| `Device.biologicalSourceEvent` | `Device.biologicalSourceEvent` | `biologicalSourceEvent` | Device.biologicalSourceEvent | An identifier that supports traceability to the event during which material in this product from one or more biological entities was obtained or pooled | 0..1 | Identifier |  |  |
| `Device.category` | `Device.category` | `category` | Device.category | Indicates a high-level grouping of the device | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/device-category` |
| `Device.conformsTo` | `Device.conformsTo` | `conformsTo` | Device.conformsTo | Identifies the standards, specifications, or formal guidances for the capabilities supported by the device | 0..* | BackboneElement |  |  |
| `Device.conformsTo.category` | `Device.conformsTo.category` | `category` | Device.conformsTo.category | Describes the common type of the standard, specification, or formal guidance.  communication \| performance \| measurement | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/device-specification-category` |
| `Device.conformsTo.extension` | `Device.conformsTo.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Device.conformsTo.id` | `Device.conformsTo.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Device.conformsTo.modifierExtension` | `Device.conformsTo.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Device.conformsTo.specification` | `Device.conformsTo.specification` | `specification` | Device.conformsTo.specification | Identifies the standard, specification, or formal guidance that the device adheres to | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/device-specification-type` |
| `Device.conformsTo.version` | `Device.conformsTo.version` | `version` | Device.conformsTo.version | Specific form or variant of the standard | 0..1 | string |  |  |
| `Device.contact` | `Device.contact` | `contact` | Device.contact | Details for human/organization for support | 0..* | ContactPoint |  |  |
| `Device.contained` | `Device.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Device.cycle` | `Device.cycle` | `cycle` | Device.cycle | The series of occurrences that repeats during the operation of the device | 0..1 | Count |  |  |
| `Device.definition` | `Device.definition` | `definition` | Device.definition | The reference to the definition for the device | 0..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/DeviceDefinition) |  |  |
| `Device.displayName` | `Device.displayName` | `displayName` | Device.displayName | The name used to display by default when the device is referenced | 0..1 | string |  |  |
| `Device.duration` | `Device.duration` | `duration` | Device.duration | A measurement of time during the device's operation (e.g., days, hours, mins, etc.) | 0..1 | Duration |  |  |
| `Device.endpoint` | `Device.endpoint` | `endpoint` | Device.endpoint | Technical endpoints providing access to electronic services provided by the device | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Endpoint) |  |  |
| `Device.expirationDate` | `Device.expirationDate` | `expirationDate` | Device.expirationDate | Date and time of expiry of this device (if applicable) | 0..1 | dateTime |  |  |
| `Device.extension` | `Device.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Device.gateway` | `Device.gateway` | `gateway` | Device.gateway | Linked device acting as a communication/data collector, translator or controller | 0..* | CodeableReference(http://hl7.org/fhir/StructureDefinition/Device) |  |  |
| `Device.id` | `Device.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Device.identifier` | `Device.identifier` | `identifier` | Device.identifier | Instance identifier | 0..* | Identifier |  |  |
| `Device.implicitRules` | `Device.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Device.language` | `Device.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `Device.location` | `Device.location` | `location` | Device.location | Where the device is found | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `Device.lotNumber` | `Device.lotNumber` | `lotNumber` | Device.lotNumber | Lot number of manufacture | 0..1 | string |  |  |
| `Device.manufactureDate` | `Device.manufactureDate` | `manufactureDate` | Device.manufactureDate | Date when the device was made | 0..1 | dateTime |  |  |
| `Device.manufacturer` | `Device.manufacturer` | `manufacturer` | Device.manufacturer | Name of device manufacturer | 0..1 | string |  |  |
| `Device.meta` | `Device.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Device.mode` | `Device.mode` | `mode` | Device.mode | The designated condition for performing a task | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/device-operation-mode` |
| `Device.modelNumber` | `Device.modelNumber` | `modelNumber` | Device.modelNumber | The manufacturer's model number for the device | 0..1 | string |  |  |
| `Device.modifierExtension` | `Device.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Device.name` | `Device.name` | `name` | Device.name | The name or names of the device as known to the manufacturer and/or patient | 0..* | BackboneElement |  |  |
| `Device.name.display` | `Device.name.display` | `display` | Device.name.display | The preferred device name | 0..1 | boolean |  |  |
| `Device.name.extension` | `Device.name.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Device.name.id` | `Device.name.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Device.name.modifierExtension` | `Device.name.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Device.name.type` | `Device.name.type` | `type` | Device.name.type | registered-name \| user-friendly-name \| patient-reported-name | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/device-nametype|5.0.0` |
| `Device.name.value` | `Device.name.value` | `value` | Device.name.value | The term that names the device | 1..1 | string |  |  |
| `Device.note` | `Device.note` | `note` | Device.note | Device notes and comments | 0..* | Annotation |  |  |
| `Device.owner` | `Device.owner` | `owner` | Device.owner | Organization responsible for device | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Device.parent` | `Device.parent` | `parent` | Device.parent | The higher level or encompassing device that this device is a logical part of | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device) |  |  |
| `Device.partNumber` | `Device.partNumber` | `partNumber` | Device.partNumber | The part number or catalog number of the device | 0..1 | string |  |  |
| `Device.property` | `Device.property` | `property` | Device.property | Inherent, essentially fixed, characteristics of the device.  e.g., time properties, size, material, etc. | 0..* | BackboneElement |  |  |
| `Device.property.extension` | `Device.property.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Device.property.id` | `Device.property.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Device.property.modifierExtension` | `Device.property.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Device.property.type` | `Device.property.type` | `type` | Device.property.type | Code that specifies the property being represented | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/device-property-type` |
| `Device.property.value[x]` | `Device.property.value[x]` | `value[x]` | Device.property.value[x] | Value of the property | 1..1 | Attachment, boolean, CodeableConcept, integer, Quantity, Range, string |  |  |
| `Device.safety` | `Device.safety` | `safety` | Device.safety | Safety Characteristics of Device | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/device-safety` |
| `Device.serialNumber` | `Device.serialNumber` | `serialNumber` | Device.serialNumber | Serial number assigned by the manufacturer | 0..1 | string |  |  |
| `Device.status` | `Device.status` | `status` | Device.status | active \| inactive \| entered-in-error | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/device-status|5.0.0` |
| `Device.text` | `Device.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Device.type` | `Device.type` | `type` | Device.type | The kind or type of device | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/device-type` |
| `Device.udiCarrier` | `Device.udiCarrier` | `udiCarrier` | Device.udiCarrier | Unique Device Identifier (UDI) Barcode string | 0..* | BackboneElement |  |  |
| `Device.udiCarrier.carrierAIDC` | `Device.udiCarrier.carrierAIDC` | `carrierAIDC` | Device.udiCarrier.carrierAIDC | UDI Machine Readable Barcode String | 0..1 | base64Binary |  |  |
| `Device.udiCarrier.carrierHRF` | `Device.udiCarrier.carrierHRF` | `carrierHRF` | Device.udiCarrier.carrierHRF | UDI Human Readable Barcode String | 0..1 | string |  |  |
| `Device.udiCarrier.deviceIdentifier` | `Device.udiCarrier.deviceIdentifier` | `deviceIdentifier` | Device.udiCarrier.deviceIdentifier | Mandatory fixed portion of UDI | 1..1 | string |  |  |
| `Device.udiCarrier.entryType` | `Device.udiCarrier.entryType` | `entryType` | Device.udiCarrier.entryType | barcode \| rfid \| manual \| card \| self-reported \| electronic-transmission \| unknown | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/udi-entry-type|5.0.0` |
| `Device.udiCarrier.extension` | `Device.udiCarrier.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Device.udiCarrier.id` | `Device.udiCarrier.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Device.udiCarrier.issuer` | `Device.udiCarrier.issuer` | `issuer` | Device.udiCarrier.issuer | UDI Issuing Organization | 1..1 | uri |  |  |
| `Device.udiCarrier.jurisdiction` | `Device.udiCarrier.jurisdiction` | `jurisdiction` | Device.udiCarrier.jurisdiction | Regional UDI authority | 0..1 | uri |  |  |
| `Device.udiCarrier.modifierExtension` | `Device.udiCarrier.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Device.url` | `Device.url` | `url` | Device.url | Network address to contact device | 0..1 | uri |  |  |
| `Device.version` | `Device.version` | `version` | Device.version | The actual design of the device or software version running on the device | 0..* | BackboneElement |  |  |
| `Device.version.component` | `Device.version.component` | `component` | Device.version.component | The hardware or software module of the device to which the version applies | 0..1 | Identifier |  |  |
| `Device.version.extension` | `Device.version.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Device.version.id` | `Device.version.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Device.version.installDate` | `Device.version.installDate` | `installDate` | Device.version.installDate | The date the version was installed on the device | 0..1 | dateTime |  |  |
| `Device.version.modifierExtension` | `Device.version.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Device.version.type` | `Device.version.type` | `type` | Device.version.type | The type of the device version, e.g. manufacturer, approved, internal | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/device-versiontype` |
| `Device.version.value` | `Device.version.value` | `value` | Device.version.value | The version text | 1..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Device](/docs/R2/Resources/Device.md)<br/> `http://hl7.org/fhir/StructureDefinition/Device\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `97`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `264`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Device](/docs/R3/Resources/Device.md)<br/> `http://hl7.org/fhir/StructureDefinition/Device\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `447`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `642`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Device](/docs/R4/Resources/Device.md)<br/> `http://hl7.org/fhir/StructureDefinition/Device\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1455`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1456`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Device](/docs/R4B/Resources/Device.md)<br/> `http://hl7.org/fhir/StructureDefinition/Device\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `962`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1191`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Device](/docs/R5/Resources/Device.md)<br/> `http://hl7.org/fhir/StructureDefinition/Device\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Device from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Device](/docs/R2/Resources/Device.md)| Relationship | [R3 Device](/docs/R3/Resources/Device.md)| Relationship | [R4 Device](/docs/R4/Resources/Device.md)| Relationship | [R4B Device](/docs/R4B/Resources/Device.md)| Relationship | R5 Device
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Device`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4490)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4491)| `Device`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12878)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12879)| `Device`| _Equivalent_<br/>(25476/25477)| `Device`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(40426)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40427)| **`Device`**
| `Device.id`| _Equivalent_<br/>(4492/4493)| `Device.id`| _Equivalent_<br/>(12880/12881)| `Device.id`| _Equivalent_<br/>(25478/25479)| `Device.id`| _Equivalent_<br/>(40428/40429)| **`Device.id`**
| `Device.meta`| _Equivalent_<br/>(4494/4495)| `Device.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12882)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12883)| `Device.meta`| _Equivalent_<br/>(25480/25481)| `Device.meta`| _Equivalent_<br/>(40430/40431)| **`Device.meta`**
| `Device.implicitRules`| _Equivalent_<br/>(4496/4497)| `Device.implicitRules`| _Equivalent_<br/>(12884/12885)| `Device.implicitRules`| _Equivalent_<br/>(25482/25483)| `Device.implicitRules`| _Equivalent_<br/>(40432/40433)| **`Device.implicitRules`**
| `Device.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4498)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4499)| `Device.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12886)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12887)| `Device.language`| _Equivalent_<br/>(25484/25485)| `Device.language`| _Equivalent_<br/>(40434/40435)| **`Device.language`**
| `Device.text`| _Equivalent_<br/>(4500/4501)| `Device.text`| _Equivalent_<br/>(12888/12889)| `Device.text`| _Equivalent_<br/>(25486/25487)| `Device.text`| _Equivalent_<br/>(40436/40437)| **`Device.text`**
| `Device.contained`| _Equivalent_<br/>(4502/4503)| `Device.contained`| _Equivalent_<br/>(12890/12891)| `Device.contained`| _Equivalent_<br/>(25488/25489)| `Device.contained`| _Equivalent_<br/>(40438/40439)| **`Device.contained`**
| `Device.extension`| _Equivalent_<br/>(4504/4505)| `Device.extension`| _Equivalent_<br/>(12892/12893)| `Device.extension`| _Equivalent_<br/>(25490/25491)| `Device.extension`| _Equivalent_<br/>(40440/40441)| **`Device.extension`**
| `Device.modifierExtension`| _Equivalent_<br/>(4506/4507)| `Device.modifierExtension`| _Equivalent_<br/>(12894/12895)| `Device.modifierExtension`| _Equivalent_<br/>(25492/25493)| `Device.modifierExtension`| _Equivalent_<br/>(40442/40443)| **`Device.modifierExtension`**
| `Device.identifier`| _Equivalent_<br/>(4508/4509)| `Device.identifier`| _Equivalent_<br/>(12896/12897)| `Device.identifier`| _Equivalent_<br/>(25494/25495)| `Device.identifier`| _Equivalent_<br/>(40444/40445)| **`Device.identifier`**
| | | | | | | | | **`Device.displayName`**
| | | | | `Device.definition`| _Equivalent_<br/>(25496/25497)| `Device.definition`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(40446)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40447)| **`Device.definition`**
| `Device.udi`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4524)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4525)| `Device.udi`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(987)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1475)| `Device.udiCarrier`| _Equivalent_<br/>(25498/25499)| `Device.udiCarrier`| _Equivalent_<br/>(40448/40449)| **`Device.udiCarrier`**
| | | | | `Device.udiCarrier.id`| _Equivalent_<br/>(25500/25501)| `Device.udiCarrier.id`| _Equivalent_<br/>(40450/40451)| **`Device.udiCarrier.id`**
| | | | | `Device.udiCarrier.extension`| _Equivalent_<br/>(25502/25503)| `Device.udiCarrier.extension`| _Equivalent_<br/>(40452/40453)| **`Device.udiCarrier.extension`**
| | | | | `Device.udiCarrier.modifierExtension`| _Equivalent_<br/>(25504/25505)| `Device.udiCarrier.modifierExtension`| _Equivalent_<br/>(40454/40455)| **`Device.udiCarrier.modifierExtension`**
| | | `Device.udi.deviceIdentifier`| _Equivalent_<br/>(990/1478)| `Device.udiCarrier.deviceIdentifier`| _Equivalent_<br/>(25506/25507)| `Device.udiCarrier.deviceIdentifier`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(40456)<hr/>←←←← _Equivalent_ ←←←← <br/>(40457)| **`Device.udiCarrier.deviceIdentifier`**
| | | `Device.udi.issuer`| _Equivalent_<br/>(992/1480)| `Device.udiCarrier.issuer`| _Equivalent_<br/>(25508/25509)| `Device.udiCarrier.issuer`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(40458)<hr/>←←←← _Equivalent_ ←←←← <br/>(40459)| **`Device.udiCarrier.issuer`**
| | | `Device.udi.jurisdiction`| _Equivalent_<br/>(993/1481)| `Device.udiCarrier.jurisdiction`| _Equivalent_<br/>(25510/25511)| `Device.udiCarrier.jurisdiction`| _Equivalent_<br/>(40460/40461)| **`Device.udiCarrier.jurisdiction`**
| | | `Device.udi.carrierAIDC`| _Equivalent_<br/>(988/1476)| `Device.udiCarrier.carrierAIDC`| _Equivalent_<br/>(25512/25513)| `Device.udiCarrier.carrierAIDC`| _Equivalent_<br/>(40462/40463)| **`Device.udiCarrier.carrierAIDC`**
| | | `Device.udi.carrierHRF`| _Equivalent_<br/>(989/1477)| `Device.udiCarrier.carrierHRF`| _Equivalent_<br/>(25514/25515)| `Device.udiCarrier.carrierHRF`| _Equivalent_<br/>(40464/40465)| **`Device.udiCarrier.carrierHRF`**
| | | `Device.udi.entryType`| _Equivalent_<br/>(991/1479)| `Device.udiCarrier.entryType`| _Equivalent_<br/>(25516/25517)| `Device.udiCarrier.entryType`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(40466)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40467)| **`Device.udiCarrier.entryType`**
| `Device.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4514)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4515)| `Device.status`| _Equivalent_<br/>(12901/12902)| `Device.status`| _Equivalent_<br/>(25518/25519)| `Device.status`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(40468)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(40469)| **`Device.status`**
| | | | | | | | | **`Device.availabilityStatus`**
| | | | | | | | | **`Device.biologicalSourceEvent`**
| `Device.manufacturer`| _Equivalent_<br/>(4516/4517)| `Device.manufacturer`| _Equivalent_<br/>(12907/12908)| `Device.manufacturer`| _Equivalent_<br/>(25524/25525)| `Device.manufacturer`| _Equivalent_<br/>(40472/40473)| **`Device.manufacturer`**
| `Device.manufactureDate`| _Equivalent_<br/>(4522/4523)| `Device.manufactureDate`| _Equivalent_<br/>(12909/12910)| `Device.manufactureDate`| _Equivalent_<br/>(25526/25527)| `Device.manufactureDate`| _Equivalent_<br/>(40474/40475)| **`Device.manufactureDate`**
| `Device.expiry`| _Equivalent_<br/>(179/593)| `Device.expirationDate`| _Equivalent_<br/>(12911/12912)| `Device.expirationDate`| _Equivalent_<br/>(25528/25529)| `Device.expirationDate`| _Equivalent_<br/>(40476/40477)| **`Device.expirationDate`**
| `Device.lotNumber`| _Equivalent_<br/>(4526/4527)| `Device.lotNumber`| _Equivalent_<br/>(12905/12906)| `Device.lotNumber`| _Equivalent_<br/>(25530/25531)| `Device.lotNumber`| _Equivalent_<br/>(40478/40479)| **`Device.lotNumber`**
| | | | | `Device.serialNumber`| _Equivalent_<br/>(25532/25533)| `Device.serialNumber`| _Equivalent_<br/>(40480/40481)| **`Device.serialNumber`**
| | | | | `Device.deviceName`| _Equivalent_<br/>(25534/25535)| `Device.deviceName`| _Equivalent_<br/>(1757/2000)| **`Device.name`**
| | | | | | | | | **`Device.name.id`**
| | | | | | | | | **`Device.name.extension`**
| | | | | | | | | **`Device.name.modifierExtension`**
| | | | | `Device.deviceName.name`| _Equivalent_<br/>(25542/25543)| `Device.deviceName.name`| _Equivalent_<br/>(1760/2001)| **`Device.name.value`**
| | | | | `Device.deviceName.type`| _Equivalent_<br/>(25544/25545)| `Device.deviceName.type`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1758)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2002)| **`Device.name.type`**
| | | | | | | | | **`Device.name.display`**
| `Device.model`| _Equivalent_<br/>(4518/4519)| `Device.model`| _Equivalent_<br/>(986/1474)| `Device.modelNumber`| _Equivalent_<br/>(25546/25547)| `Device.modelNumber`| _Equivalent_<br/>(40485/40486)| **`Device.modelNumber`**
| | | | | `Device.partNumber`| _Equivalent_<br/>(25548/25549)| `Device.partNumber`| _Equivalent_<br/>(40487/40488)| **`Device.partNumber`**
| | | | | | | | | **`Device.category`**
| `Device.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4510)<hr/>←←←← _RelatedTo_ ←←←← <br/>(4511)| `Device.type`| _Equivalent_<br/>(12903/12904)| `Device.type`| _Equivalent_<br/>(25550/25551)| `Device.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(40489)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40490)| **`Device.type`**
| `Device.version`| _Equivalent_<br/>(4520/4521)| `Device.version`| →→→→ _RelatedTo_ →→→→ <br/>(12913)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12914)| `Device.version`| _Equivalent_<br/>(25564/25565)| `Device.version`| _Equivalent_<br/>(40496/40497)| **`Device.version`**
| | | | | `Device.version.id`| _Equivalent_<br/>(25566/25567)| `Device.version.id`| _Equivalent_<br/>(40498/40499)| **`Device.version.id`**
| | | | | `Device.version.extension`| _Equivalent_<br/>(25568/25569)| `Device.version.extension`| _Equivalent_<br/>(40500/40501)| **`Device.version.extension`**
| | | | | `Device.version.modifierExtension`| _Equivalent_<br/>(25570/25571)| `Device.version.modifierExtension`| _Equivalent_<br/>(40502/40503)| **`Device.version.modifierExtension`**
| | | | | `Device.version.type`| _Equivalent_<br/>(25572/25573)| `Device.version.type`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(40504)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(40505)| **`Device.version.type`**
| | | | | `Device.version.component`| _Equivalent_<br/>(25574/25575)| `Device.version.component`| _Equivalent_<br/>(40506/40507)| **`Device.version.component`**
| | | | | | | | | **`Device.version.installDate`**
| | | | | `Device.version.value`| _Equivalent_<br/>(25576/25577)| `Device.version.value`| _Equivalent_<br/>(40508/40509)| **`Device.version.value`**
| | | | | `Device.specialization`| _Equivalent_<br/>(25552/25553)| `Device.specialization`| _Equivalent_<br/>(1759/2003)| **`Device.conformsTo`**
| | | | | | | | | **`Device.conformsTo.id`**
| | | | | | | | | **`Device.conformsTo.extension`**
| | | | | | | | | **`Device.conformsTo.modifierExtension`**
| | | | | | | | | **`Device.conformsTo.category`**
| | | | | | | | | **`Device.conformsTo.specification`**
| | | | | | | | | **`Device.conformsTo.version`**
| | | | | `Device.property`| _Equivalent_<br/>(25578/25579)| `Device.property`| _Equivalent_<br/>(40510/40511)| **`Device.property`**
| | | | | `Device.property.id`| _Equivalent_<br/>(25580/25581)| `Device.property.id`| _Equivalent_<br/>(40512/40513)| **`Device.property.id`**
| | | | | `Device.property.extension`| _Equivalent_<br/>(25582/25583)| `Device.property.extension`| _Equivalent_<br/>(40514/40515)| **`Device.property.extension`**
| | | | | `Device.property.modifierExtension`| _Equivalent_<br/>(25584/25585)| `Device.property.modifierExtension`| _Equivalent_<br/>(40516/40517)| **`Device.property.modifierExtension`**
| | | | | `Device.property.type`| _Equivalent_<br/>(25586/25587)| `Device.property.type`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(40518)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(40519)| **`Device.property.type`**
| | | | | `Device.property.valueQuantity`| _Equivalent_<br/>(25588/25589)| `Device.property.valueQuantity`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1761)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2005)| **`Device.property.value[x]`**
| | | | | `Device.property.valueCode`| _Equivalent_<br/>(25590/25591)| `Device.property.valueCode`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1762)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2005)| **`Device.property.value[x]`**
| | | | | | | | | **`Device.mode`**
| | | | | | | | | **`Device.cycle`**
| | | | | | | | | **`Device.duration`**
| `Device.owner`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4528)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4529)| `Device.owner`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12917)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12918)| `Device.owner`| _Equivalent_<br/>(25594/25595)| `Device.owner`| _Equivalent_<br/>(40521/40522)| **`Device.owner`**
| `Device.contact`| _Equivalent_<br/>(4534/4535)| `Device.contact`| _Equivalent_<br/>(12919/12920)| `Device.contact`| _Equivalent_<br/>(25596/25597)| `Device.contact`| _Equivalent_<br/>(40523/40524)| **`Device.contact`**
| `Device.location`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4530)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4531)| `Device.location`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12921)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12922)| `Device.location`| _Equivalent_<br/>(25598/25599)| `Device.location`| _Equivalent_<br/>(40525/40526)| **`Device.location`**
| `Device.url`| _Equivalent_<br/>(4536/4537)| `Device.url`| _Equivalent_<br/>(12923/12924)| `Device.url`| _Equivalent_<br/>(25600/25601)| `Device.url`| _Equivalent_<br/>(40527/40528)| **`Device.url`**
| | | | | | | | | **`Device.endpoint`**
| | | | | | | | | **`Device.gateway`**
| `Device.note`| _Equivalent_<br/>(4512/4513)| `Device.note`| _Equivalent_<br/>(12925/12926)| `Device.note`| _Equivalent_<br/>(25602/25603)| `Device.note`| _Equivalent_<br/>(40529/40530)| **`Device.note`**
| | | `Device.safety`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12927)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12928)| `Device.safety`| _Equivalent_<br/>(25604/25605)| `Device.safety`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(40531)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(40532)| **`Device.safety`**
| | | | | `Device.parent`| _Equivalent_<br/>(25606/25607)| `Device.parent`| _Equivalent_<br/>(40533/40534)| **`Device.parent`**
| *24 of 25 elements used* <br/>remaining elements:<br/>`Device.patient`| | *31 of 36 elements used* <br/>remaining elements:<br/>`Device.patient`, `Device.udi.extension`, `Device.udi.id`, `Device.udi.modifierExtension`, `Device.udi.name`| | *55 of 66 elements used* <br/>remaining elements:<br/>`Device.deviceName.extension`, `Device.deviceName.id`, `Device.deviceName.modifierExtension`, `Device.distinctIdentifier`, `Device.patient`, `Device.specialization.extension`, `Device.specialization.id`, `Device.specialization.modifierExtension`, `Device.specialization.systemType`, `Device.specialization.version`, `Device.statusReason`| | *55 of 66 elements used* <br/>remaining elements:<br/>`Device.deviceName.extension`, `Device.deviceName.id`, `Device.deviceName.modifierExtension`, `Device.distinctIdentifier`, `Device.patient`, `Device.specialization.extension`, `Device.specialization.id`, `Device.specialization.modifierExtension`, `Device.specialization.systemType`, `Device.specialization.version`, `Device.statusReason`| | *74 of 74 elements used* 

