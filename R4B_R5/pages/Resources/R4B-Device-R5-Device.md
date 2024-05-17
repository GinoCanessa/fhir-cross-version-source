Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Device |  | A type of a manufactured item that is used in the provision of healthcare without being substantially changed through that activity. The device may be a medical or non-medical device. | 66 | 43 |
| Target | Device |  | This resource describes the properties (regulated, has real time clock, etc.), adminstrative (manufacturer name, model number, serial number, firmware, etc.), and type (knee replacement, blood pressure cuff, MRI, etc.) of a physical unit (these values do not change much within a given module, for example the serail number, manufacturer name, and model number). An actual unit may consist of several modules in a distinct hierarchy and these are represented by multiple Device resources and bound through the 'parent' element. | 74 | 51 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 17 |
Equivalent | 4 |
RelatedTo | 45 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Device | Device | Equivalent | R4B `Device` maps as Equivalent to R5 `Device` |
| Device.contact | Device.contact | Equivalent | R4B `Device.contact` maps as Equivalent to R5 `Device.contact` |
| Device.contained | Device.contained | Equivalent | R4B `Device.contained` maps as Equivalent to R5 `Device.contained` |
| Device.definition | Device.definition | SourceIsBroaderThanTarget | R4B `Device.definition` maps as SourceIsBroaderThanTarget to R5 `Device.definition` - definition has change due to type change: R4B definition Reference has no equivalent or mapped type in R5 definition |
| Device.deviceName | - | DoesNotExistInTarget | R4B `Device.deviceName` does not appear in the target and has no mapping for `Device`. |
| Device.deviceName.extension | - | DoesNotExistInTarget | R4B `Device.deviceName.extension` does not appear in the target and has no mapping for `Device`. |
| Device.deviceName.id | - | DoesNotExistInTarget | R4B `Device.deviceName.id` does not appear in the target and has no mapping for `Device`. |
| Device.deviceName.modifierExtension | - | DoesNotExistInTarget | R4B `Device.deviceName.modifierExtension` does not appear in the target and has no mapping for `Device`. |
| Device.deviceName.name | - | DoesNotExistInTarget | R4B `Device.deviceName.name` does not appear in the target and has no mapping for `Device`. |
| Device.deviceName.type | - | DoesNotExistInTarget | R4B `Device.deviceName.type` does not appear in the target and has no mapping for `Device`. |
| Device.distinctIdentifier | - | DoesNotExistInTarget | R4B `Device.distinctIdentifier` does not appear in the target and has no mapping for `Device`. |
| Device.expirationDate | Device.expirationDate | Equivalent | R4B `Device.expirationDate` maps as Equivalent to R5 `Device.expirationDate` |
| Device.extension | Device.extension | RelatedTo | R4B `Device.extension` maps as RelatedTo to R5 `Device.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Device.id | Device.id | Equivalent | R4B `Device.id` maps as Equivalent to R5 `Device.id` |
| Device.identifier | Device.identifier | Equivalent | R4B `Device.identifier` maps as Equivalent to R5 `Device.identifier` |
| Device.implicitRules | Device.implicitRules | Equivalent | R4B `Device.implicitRules` maps as Equivalent to R5 `Device.implicitRules` |
| Device.language | Device.language | RelatedTo | R4B `Device.language` maps as RelatedTo to R5 `Device.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Device.location | Device.location | Equivalent | R4B `Device.location` maps as Equivalent to R5 `Device.location` |
| Device.lotNumber | Device.lotNumber | Equivalent | R4B `Device.lotNumber` maps as Equivalent to R5 `Device.lotNumber` |
| Device.manufactureDate | Device.manufactureDate | Equivalent | R4B `Device.manufactureDate` maps as Equivalent to R5 `Device.manufactureDate` |
| Device.manufacturer | Device.manufacturer | Equivalent | R4B `Device.manufacturer` maps as Equivalent to R5 `Device.manufacturer` |
| Device.meta | Device.meta | Equivalent | R4B `Device.meta` maps as Equivalent to R5 `Device.meta` |
| Device.modelNumber | Device.modelNumber | Equivalent | R4B `Device.modelNumber` maps as Equivalent to R5 `Device.modelNumber` |
| Device.modifierExtension | Device.modifierExtension | RelatedTo | R4B `Device.modifierExtension` maps as RelatedTo to R5 `Device.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Device.note | Device.note | SourceIsNarrowerThanTarget | R4B `Device.note` maps as SourceIsNarrowerThanTarget to R5 `Device.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| Device.owner | Device.owner | Equivalent | R4B `Device.owner` maps as Equivalent to R5 `Device.owner` |
| Device.parent | Device.parent | Equivalent | R4B `Device.parent` maps as Equivalent to R5 `Device.parent` |
| Device.partNumber | Device.partNumber | Equivalent | R4B `Device.partNumber` maps as Equivalent to R5 `Device.partNumber` |
| Device.patient | - | DoesNotExistInTarget | R4B `Device.patient` does not appear in the target and has no mapping for `Device`. |
| Device.property | Device.property | Equivalent | R4B `Device.property` maps as Equivalent to R5 `Device.property` |
| Device.property.extension | Device.property.extension | RelatedTo | R4B `Device.property.extension` maps as RelatedTo to R5 `Device.property.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Device.property.id | Device.property.id | Equivalent | R4B `Device.property.id` maps as Equivalent to R5 `Device.property.id` |
| Device.property.modifierExtension | Device.property.modifierExtension | RelatedTo | R4B `Device.property.modifierExtension` maps as RelatedTo to R5 `Device.property.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Device.property.type | Device.property.type | RelatedTo | R4B `Device.property.type` maps as RelatedTo to R5 `Device.property.type` - type added a binding requirement - Example http://hl7.org/fhir/ValueSet/device-property-type |
| Device.property.valueCode | - | DoesNotExistInTarget | R4B `Device.property.valueCode` does not appear in the target and has no mapping for `Device`. |
| Device.property.valueQuantity | - | DoesNotExistInTarget | R4B `Device.property.valueQuantity` does not appear in the target and has no mapping for `Device`. |
| Device.safety | Device.safety | RelatedTo | R4B `Device.safety` maps as RelatedTo to R5 `Device.safety` - safety added a binding requirement - Example http://hl7.org/fhir/ValueSet/device-safety |
| Device.serialNumber | Device.serialNumber | Equivalent | R4B `Device.serialNumber` maps as Equivalent to R5 `Device.serialNumber` |
| Device.specialization | - | DoesNotExistInTarget | R4B `Device.specialization` does not appear in the target and has no mapping for `Device`. |
| Device.specialization.extension | - | DoesNotExistInTarget | R4B `Device.specialization.extension` does not appear in the target and has no mapping for `Device`. |
| Device.specialization.id | - | DoesNotExistInTarget | R4B `Device.specialization.id` does not appear in the target and has no mapping for `Device`. |
| Device.specialization.modifierExtension | - | DoesNotExistInTarget | R4B `Device.specialization.modifierExtension` does not appear in the target and has no mapping for `Device`. |
| Device.specialization.systemType | - | DoesNotExistInTarget | R4B `Device.specialization.systemType` does not appear in the target and has no mapping for `Device`. |
| Device.specialization.version | - | DoesNotExistInTarget | R4B `Device.specialization.version` does not appear in the target and has no mapping for `Device`. |
| Device.status | Device.status | Equivalent | R4B `Device.status` maps as Equivalent to R5 `Device.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/device-status|4.3.0 and http://hl7.org/fhir/ValueSet/device-status|5.0.0 (Equivalent) |
| Device.statusReason | - | DoesNotExistInTarget | R4B `Device.statusReason` does not appear in the target and has no mapping for `Device`. |
| Device.text | Device.text | Equivalent | R4B `Device.text` maps as Equivalent to R5 `Device.text` |
| Device.type | Device.type | RelatedTo | R4B `Device.type` maps as RelatedTo to R5 `Device.type` - type changed from scalar to array (max cardinality from 1 to *) |
| Device.udiCarrier | Device.udiCarrier | Equivalent | R4B `Device.udiCarrier` maps as Equivalent to R5 `Device.udiCarrier` |
| Device.udiCarrier.carrierAIDC | Device.udiCarrier.carrierAIDC | Equivalent | R4B `Device.udiCarrier.carrierAIDC` maps as Equivalent to R5 `Device.udiCarrier.carrierAIDC` |
| Device.udiCarrier.carrierHRF | Device.udiCarrier.carrierHRF | Equivalent | R4B `Device.udiCarrier.carrierHRF` maps as Equivalent to R5 `Device.udiCarrier.carrierHRF` |
| Device.udiCarrier.deviceIdentifier | Device.udiCarrier.deviceIdentifier | RelatedTo | R4B `Device.udiCarrier.deviceIdentifier` maps as RelatedTo to R5 `Device.udiCarrier.deviceIdentifier` - deviceIdentifier made the element mandatory; deviceIdentifier increased the minimum cardinality from 0 to 1 |
| Device.udiCarrier.entryType | Device.udiCarrier.entryType | Equivalent | R4B `Device.udiCarrier.entryType` maps as Equivalent to R5 `Device.udiCarrier.entryType` - entryType has compatible required binding for code type: http://hl7.org/fhir/ValueSet/udi-entry-type|4.3.0 and http://hl7.org/fhir/ValueSet/udi-entry-type|5.0.0 (Equivalent) |
| Device.udiCarrier.extension | Device.udiCarrier.extension | RelatedTo | R4B `Device.udiCarrier.extension` maps as RelatedTo to R5 `Device.udiCarrier.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Device.udiCarrier.id | Device.udiCarrier.id | Equivalent | R4B `Device.udiCarrier.id` maps as Equivalent to R5 `Device.udiCarrier.id` |
| Device.udiCarrier.issuer | Device.udiCarrier.issuer | RelatedTo | R4B `Device.udiCarrier.issuer` maps as RelatedTo to R5 `Device.udiCarrier.issuer` - issuer made the element mandatory; issuer increased the minimum cardinality from 0 to 1 |
| Device.udiCarrier.jurisdiction | Device.udiCarrier.jurisdiction | Equivalent | R4B `Device.udiCarrier.jurisdiction` maps as Equivalent to R5 `Device.udiCarrier.jurisdiction` |
| Device.udiCarrier.modifierExtension | Device.udiCarrier.modifierExtension | RelatedTo | R4B `Device.udiCarrier.modifierExtension` maps as RelatedTo to R5 `Device.udiCarrier.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Device.url | Device.url | Equivalent | R4B `Device.url` maps as Equivalent to R5 `Device.url` |
| Device.version | Device.version | Equivalent | R4B `Device.version` maps as Equivalent to R5 `Device.version` |
| Device.version.component | Device.version.component | Equivalent | R4B `Device.version.component` maps as Equivalent to R5 `Device.version.component` |
| Device.version.extension | Device.version.extension | RelatedTo | R4B `Device.version.extension` maps as RelatedTo to R5 `Device.version.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Device.version.id | Device.version.id | Equivalent | R4B `Device.version.id` maps as Equivalent to R5 `Device.version.id` |
| Device.version.modifierExtension | Device.version.modifierExtension | RelatedTo | R4B `Device.version.modifierExtension` maps as RelatedTo to R5 `Device.version.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Device.version.type | Device.version.type | RelatedTo | R4B `Device.version.type` maps as RelatedTo to R5 `Device.version.type` - type added a binding requirement - Example http://hl7.org/fhir/ValueSet/device-versiontype |
| Device.version.value | Device.version.value | Equivalent | R4B `Device.version.value` maps as Equivalent to R5 `Device.version.value` |

