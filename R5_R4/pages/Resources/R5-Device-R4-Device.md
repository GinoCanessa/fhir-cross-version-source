Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Device |  | This resource describes the properties (regulated, has real time clock, etc.), adminstrative (manufacturer name, model number, serial number, firmware, etc.), and type (knee replacement, blood pressure cuff, MRI, etc.) of a physical unit (these values do not change much within a given module, for example the serail number, manufacturer name, and model number). An actual unit may consist of several modules in a distinct hierarchy and these are represented by multiple Device resources and bound through the 'parent' element. | 74 | 51 |
| Target | Device |  | A type of a manufactured item that is used in the provision of healthcare without being substantially changed through that activity. The device may be a medical or non-medical device. | 66 | 43 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 20 |
Equivalent | 38 |
RelatedTo | 1 |
SourceIsBroaderThanTarget | 11 |
SourceIsNarrowerThanTarget | 4 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Device | Device | Equivalent | R5 `Device` maps as Equivalent to R4 `Device` |
| Device.availabilityStatus | - | DoesNotExistInTarget | R5 `Device.availabilityStatus` does not appear in the target and has no mapping for `Device`. |
| Device.biologicalSourceEvent | - | DoesNotExistInTarget | R5 `Device.biologicalSourceEvent` does not appear in the target and has no mapping for `Device`. |
| Device.category | - | DoesNotExistInTarget | R5 `Device.category` does not appear in the target and has no mapping for `Device`. |
| Device.conformsTo | Device.specialization | Equivalent | R5 `Device.conformsTo` maps as Equivalent to R4 `Device.specialization` |
| Device.conformsTo.category | - | DoesNotExistInTarget | R5 `Device.conformsTo.category` does not appear in the target and has no mapping for `Device`. |
| Device.conformsTo.extension | - | DoesNotExistInTarget | R5 `Device.conformsTo.extension` does not appear in the target and has no mapping for `Device`. |
| Device.conformsTo.id | - | DoesNotExistInTarget | R5 `Device.conformsTo.id` does not appear in the target and has no mapping for `Device`. |
| Device.conformsTo.modifierExtension | - | DoesNotExistInTarget | R5 `Device.conformsTo.modifierExtension` does not appear in the target and has no mapping for `Device`. |
| Device.conformsTo.specification | - | DoesNotExistInTarget | R5 `Device.conformsTo.specification` does not appear in the target and has no mapping for `Device`. |
| Device.conformsTo.version | - | DoesNotExistInTarget | R5 `Device.conformsTo.version` does not appear in the target and has no mapping for `Device`. |
| Device.contact | Device.contact | Equivalent | R5 `Device.contact` maps as Equivalent to R4 `Device.contact` |
| Device.contained | Device.contained | Equivalent | R5 `Device.contained` maps as Equivalent to R4 `Device.contained` |
| Device.cycle | - | DoesNotExistInTarget | R5 `Device.cycle` does not appear in the target and has no mapping for `Device`. |
| Device.definition | Device.definition | SourceIsBroaderThanTarget | R5 `Device.definition` maps as SourceIsBroaderThanTarget to R4 `Device.definition` - definition has change due to type change: R5 definition CodeableReference has no equivalent or mapped type in R4 definition |
| Device.displayName | - | DoesNotExistInTarget | R5 `Device.displayName` does not appear in the target and has no mapping for `Device`. |
| Device.duration | - | DoesNotExistInTarget | R5 `Device.duration` does not appear in the target and has no mapping for `Device`. |
| Device.endpoint | - | DoesNotExistInTarget | R5 `Device.endpoint` does not appear in the target and has no mapping for `Device`. |
| Device.expirationDate | Device.expirationDate | Equivalent | R5 `Device.expirationDate` maps as Equivalent to R4 `Device.expirationDate` |
| Device.extension | Device.extension | SourceIsBroaderThanTarget | R5 `Device.extension` maps as SourceIsBroaderThanTarget to R4 `Device.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Device.gateway | - | DoesNotExistInTarget | R5 `Device.gateway` does not appear in the target and has no mapping for `Device`. |
| Device.id | Device.id | Equivalent | R5 `Device.id` maps as Equivalent to R4 `Device.id` |
| Device.identifier | Device.identifier | Equivalent | R5 `Device.identifier` maps as Equivalent to R4 `Device.identifier` |
| Device.implicitRules | Device.implicitRules | Equivalent | R5 `Device.implicitRules` maps as Equivalent to R4 `Device.implicitRules` |
| Device.language | Device.language | SourceIsNarrowerThanTarget | R5 `Device.language` maps as SourceIsNarrowerThanTarget to R4 `Device.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| Device.location | Device.location | Equivalent | R5 `Device.location` maps as Equivalent to R4 `Device.location` |
| Device.lotNumber | Device.lotNumber | Equivalent | R5 `Device.lotNumber` maps as Equivalent to R4 `Device.lotNumber` |
| Device.manufactureDate | Device.manufactureDate | Equivalent | R5 `Device.manufactureDate` maps as Equivalent to R4 `Device.manufactureDate` |
| Device.manufacturer | Device.manufacturer | Equivalent | R5 `Device.manufacturer` maps as Equivalent to R4 `Device.manufacturer` |
| Device.meta | Device.meta | Equivalent | R5 `Device.meta` maps as Equivalent to R4 `Device.meta` |
| Device.mode | - | DoesNotExistInTarget | R5 `Device.mode` does not appear in the target and has no mapping for `Device`. |
| Device.modelNumber | Device.modelNumber | Equivalent | R5 `Device.modelNumber` maps as Equivalent to R4 `Device.modelNumber` |
| Device.modifierExtension | Device.modifierExtension | SourceIsBroaderThanTarget | R5 `Device.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Device.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Device.name | Device.deviceName | Equivalent | R5 `Device.name` maps as Equivalent to R4 `Device.deviceName` |
| Device.name.display | - | DoesNotExistInTarget | R5 `Device.name.display` does not appear in the target and has no mapping for `Device`. |
| Device.name.extension | - | DoesNotExistInTarget | R5 `Device.name.extension` does not appear in the target and has no mapping for `Device`. |
| Device.name.id | - | DoesNotExistInTarget | R5 `Device.name.id` does not appear in the target and has no mapping for `Device`. |
| Device.name.modifierExtension | - | DoesNotExistInTarget | R5 `Device.name.modifierExtension` does not appear in the target and has no mapping for `Device`. |
| Device.name.type | Device.deviceName.type | Equivalent | R5 `Device.name.type` maps as Equivalent to R4 `Device.deviceName.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/device-nametype|5.0.0 and http://hl7.org/fhir/ValueSet/device-nametype|4.0.1 (Equivalent) |
| Device.name.value | Device.deviceName.name | Equivalent | R5 `Device.name.value` maps as Equivalent to R4 `Device.deviceName.name` |
| Device.note | Device.note | SourceIsBroaderThanTarget | R5 `Device.note` maps as SourceIsBroaderThanTarget to R4 `Device.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4 `note` |
| Device.owner | Device.owner | Equivalent | R5 `Device.owner` maps as Equivalent to R4 `Device.owner` |
| Device.parent | Device.parent | Equivalent | R5 `Device.parent` maps as Equivalent to R4 `Device.parent` |
| Device.partNumber | Device.partNumber | Equivalent | R5 `Device.partNumber` maps as Equivalent to R4 `Device.partNumber` |
| Device.property | Device.property | Equivalent | R5 `Device.property` maps as Equivalent to R4 `Device.property` |
| Device.property.extension | Device.property.extension | SourceIsBroaderThanTarget | R5 `Device.property.extension` maps as SourceIsBroaderThanTarget to R4 `Device.property.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Device.property.id | Device.property.id | Equivalent | R5 `Device.property.id` maps as Equivalent to R4 `Device.property.id` |
| Device.property.modifierExtension | Device.property.modifierExtension | SourceIsBroaderThanTarget | R5 `Device.property.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Device.property.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Device.property.type | Device.property.type | SourceIsNarrowerThanTarget | R5 `Device.property.type` maps as SourceIsNarrowerThanTarget to R4 `Device.property.type` - type removed a binding requirement - Example http://hl7.org/fhir/ValueSet/device-property-type; type has change due to type change: R5 `type` `CodeableConcept` maps as SourceIsNarrowerThanTarget for R4 `type` |
| Device.property.value[x] | Device.property.valueCode | RelatedTo | R5 `Device.property.value[x]` maps as RelatedTo to R4 `Device.property.valueCode` - valueCode changed from scalar to array (max cardinality from 1 to *); valueCode has change due to type change: R5 value[x] Quantity has no equivalent or mapped type in R4 valueCode; valueCode has change due to type change: R5 value[x] string has no equivalent or mapped type in R4 valueCode; valueCode has change due to type change: R5 value[x] boolean has no equivalent or mapped type in R4 valueCode; valueCode has change due to type change: R5 value[x] integer has no equivalent or mapped type in R4 valueCode; valueCode has change due to type change: R5 value[x] Range has no equivalent or mapped type in R4 valueCode; valueCode has change due to type change: R5 value[x] Attachment has no equivalent or mapped type in R4 valueCode |
| Device.property.value[x] | Device.property.valueCode | RelatedTo | R5 `Device.property.value[x]` maps as RelatedTo to R4 `Device.property.valueCode` - valueCode changed from scalar to array (max cardinality from 1 to *); valueCode has change due to type change: R5 value[x] Quantity has no equivalent or mapped type in R4 valueCode; valueCode has change due to type change: R5 value[x] string has no equivalent or mapped type in R4 valueCode; valueCode has change due to type change: R5 value[x] boolean has no equivalent or mapped type in R4 valueCode; valueCode has change due to type change: R5 value[x] integer has no equivalent or mapped type in R4 valueCode; valueCode has change due to type change: R5 value[x] Range has no equivalent or mapped type in R4 valueCode; valueCode has change due to type change: R5 value[x] Attachment has no equivalent or mapped type in R4 valueCode |
| Device.property.value[x] | Device.property.valueQuantity | RelatedTo | R5 `Device.property.value[x]` maps as RelatedTo to R4 `Device.property.valueQuantity` - valueQuantity changed from scalar to array (max cardinality from 1 to *); valueQuantity has change due to type change: R5 value[x] CodeableConcept has no equivalent or mapped type in R4 valueQuantity; valueQuantity has change due to type change: R5 value[x] string has no equivalent or mapped type in R4 valueQuantity; valueQuantity has change due to type change: R5 value[x] boolean has no equivalent or mapped type in R4 valueQuantity; valueQuantity has change due to type change: R5 value[x] integer has no equivalent or mapped type in R4 valueQuantity; valueQuantity has change due to type change: R5 value[x] Range has no equivalent or mapped type in R4 valueQuantity; valueQuantity has change due to type change: R5 value[x] Attachment has no equivalent or mapped type in R4 valueQuantity |
| Device.safety | Device.safety | SourceIsNarrowerThanTarget | R5 `Device.safety` maps as SourceIsNarrowerThanTarget to R4 `Device.safety` - safety removed a binding requirement - Example http://hl7.org/fhir/ValueSet/device-safety; safety has change due to type change: R5 `safety` `CodeableConcept` maps as SourceIsNarrowerThanTarget for R4 `safety` |
| Device.serialNumber | Device.serialNumber | Equivalent | R5 `Device.serialNumber` maps as Equivalent to R4 `Device.serialNumber` |
| Device.status | Device.status | Equivalent | R5 `Device.status` maps as Equivalent to R4 `Device.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/device-status|5.0.0 and http://hl7.org/fhir/ValueSet/device-status|4.0.1 (Equivalent) |
| Device.text | Device.text | Equivalent | R5 `Device.text` maps as Equivalent to R4 `Device.text` |
| Device.type | Device.type | SourceIsBroaderThanTarget | R5 `Device.type` maps as SourceIsBroaderThanTarget to R4 `Device.type` - type changed from array to scalar (max cardinality from * to 1) |
| Device.udiCarrier | Device.udiCarrier | Equivalent | R5 `Device.udiCarrier` maps as Equivalent to R4 `Device.udiCarrier` |
| Device.udiCarrier.carrierAIDC | Device.udiCarrier.carrierAIDC | Equivalent | R5 `Device.udiCarrier.carrierAIDC` maps as Equivalent to R4 `Device.udiCarrier.carrierAIDC` |
| Device.udiCarrier.carrierHRF | Device.udiCarrier.carrierHRF | Equivalent | R5 `Device.udiCarrier.carrierHRF` maps as Equivalent to R4 `Device.udiCarrier.carrierHRF` |
| Device.udiCarrier.deviceIdentifier | Device.udiCarrier.deviceIdentifier | Equivalent | R5 `Device.udiCarrier.deviceIdentifier` maps as Equivalent to R4 `Device.udiCarrier.deviceIdentifier` |
| Device.udiCarrier.entryType | Device.udiCarrier.entryType | Equivalent | R5 `Device.udiCarrier.entryType` maps as Equivalent to R4 `Device.udiCarrier.entryType` - entryType has compatible required binding for code type: http://hl7.org/fhir/ValueSet/udi-entry-type|5.0.0 and http://hl7.org/fhir/ValueSet/udi-entry-type|4.0.1 (Equivalent) |
| Device.udiCarrier.extension | Device.udiCarrier.extension | SourceIsBroaderThanTarget | R5 `Device.udiCarrier.extension` maps as SourceIsBroaderThanTarget to R4 `Device.udiCarrier.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Device.udiCarrier.id | Device.udiCarrier.id | Equivalent | R5 `Device.udiCarrier.id` maps as Equivalent to R4 `Device.udiCarrier.id` |
| Device.udiCarrier.issuer | Device.udiCarrier.issuer | Equivalent | R5 `Device.udiCarrier.issuer` maps as Equivalent to R4 `Device.udiCarrier.issuer` |
| Device.udiCarrier.jurisdiction | Device.udiCarrier.jurisdiction | Equivalent | R5 `Device.udiCarrier.jurisdiction` maps as Equivalent to R4 `Device.udiCarrier.jurisdiction` |
| Device.udiCarrier.modifierExtension | Device.udiCarrier.modifierExtension | SourceIsBroaderThanTarget | R5 `Device.udiCarrier.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Device.udiCarrier.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Device.url | Device.url | Equivalent | R5 `Device.url` maps as Equivalent to R4 `Device.url` |
| Device.version | Device.version | Equivalent | R5 `Device.version` maps as Equivalent to R4 `Device.version` |
| Device.version.component | Device.version.component | Equivalent | R5 `Device.version.component` maps as Equivalent to R4 `Device.version.component` |
| Device.version.extension | Device.version.extension | SourceIsBroaderThanTarget | R5 `Device.version.extension` maps as SourceIsBroaderThanTarget to R4 `Device.version.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Device.version.id | Device.version.id | Equivalent | R5 `Device.version.id` maps as Equivalent to R4 `Device.version.id` |
| Device.version.installDate | - | DoesNotExistInTarget | R5 `Device.version.installDate` does not appear in the target and has no mapping for `Device`. |
| Device.version.modifierExtension | Device.version.modifierExtension | SourceIsBroaderThanTarget | R5 `Device.version.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Device.version.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Device.version.type | Device.version.type | SourceIsNarrowerThanTarget | R5 `Device.version.type` maps as SourceIsNarrowerThanTarget to R4 `Device.version.type` - type removed a binding requirement - Example http://hl7.org/fhir/ValueSet/device-versiontype; type has change due to type change: R5 `type` `CodeableConcept` maps as SourceIsNarrowerThanTarget for R4 `type` |
| Device.version.value | Device.version.value | Equivalent | R5 `Device.version.value` maps as Equivalent to R4 `Device.version.value` |

