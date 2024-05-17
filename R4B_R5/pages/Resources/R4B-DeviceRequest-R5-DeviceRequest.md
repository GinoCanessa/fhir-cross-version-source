Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | DeviceRequest |  | Represents a request for a patient to employ a medical device. The device may be an implantable device, or an external assistive device, such as a walker. | 38 | 27 |
| Target | DeviceRequest |  | Represents a request a device to be provided to a specific patient. The device may be an implantable device to be subsequently implanted, or an external assistive device, such as a walker, to be delivered and subsequently be used. | 40 | 29 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 5 |
Equivalent | 4 |
RelatedTo | 29 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| DeviceRequest | DeviceRequest | Equivalent | R4B `DeviceRequest` maps as Equivalent to R5 `DeviceRequest` |
| DeviceRequest.authoredOn | DeviceRequest.authoredOn | Equivalent | R4B `DeviceRequest.authoredOn` maps as Equivalent to R5 `DeviceRequest.authoredOn` |
| DeviceRequest.basedOn | DeviceRequest.basedOn | Equivalent | R4B `DeviceRequest.basedOn` maps as Equivalent to R5 `DeviceRequest.basedOn` |
| DeviceRequest.code[x] | - | DoesNotExistInTarget | R4B `DeviceRequest.code[x]` does not appear in the target and has no mapping for `DeviceRequest`. |
| DeviceRequest.contained | DeviceRequest.contained | Equivalent | R4B `DeviceRequest.contained` maps as Equivalent to R5 `DeviceRequest.contained` |
| DeviceRequest.encounter | DeviceRequest.encounter | Equivalent | R4B `DeviceRequest.encounter` maps as Equivalent to R5 `DeviceRequest.encounter` |
| DeviceRequest.extension | DeviceRequest.extension | RelatedTo | R4B `DeviceRequest.extension` maps as RelatedTo to R5 `DeviceRequest.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| DeviceRequest.groupIdentifier | DeviceRequest.groupIdentifier | Equivalent | R4B `DeviceRequest.groupIdentifier` maps as Equivalent to R5 `DeviceRequest.groupIdentifier` |
| DeviceRequest.id | DeviceRequest.id | Equivalent | R4B `DeviceRequest.id` maps as Equivalent to R5 `DeviceRequest.id` |
| DeviceRequest.identifier | DeviceRequest.identifier | Equivalent | R4B `DeviceRequest.identifier` maps as Equivalent to R5 `DeviceRequest.identifier` |
| DeviceRequest.implicitRules | DeviceRequest.implicitRules | Equivalent | R4B `DeviceRequest.implicitRules` maps as Equivalent to R5 `DeviceRequest.implicitRules` |
| DeviceRequest.instantiatesCanonical | DeviceRequest.instantiatesCanonical | Equivalent | R4B `DeviceRequest.instantiatesCanonical` maps as Equivalent to R5 `DeviceRequest.instantiatesCanonical` |
| DeviceRequest.instantiatesUri | DeviceRequest.instantiatesUri | Equivalent | R4B `DeviceRequest.instantiatesUri` maps as Equivalent to R5 `DeviceRequest.instantiatesUri` |
| DeviceRequest.insurance | DeviceRequest.insurance | Equivalent | R4B `DeviceRequest.insurance` maps as Equivalent to R5 `DeviceRequest.insurance` |
| DeviceRequest.intent | DeviceRequest.intent | Equivalent | R4B `DeviceRequest.intent` maps as Equivalent to R5 `DeviceRequest.intent` - intent has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-intent|4.3.0 and http://hl7.org/fhir/ValueSet/request-intent|5.0.0 (Equivalent) |
| DeviceRequest.language | DeviceRequest.language | RelatedTo | R4B `DeviceRequest.language` maps as RelatedTo to R5 `DeviceRequest.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| DeviceRequest.meta | DeviceRequest.meta | Equivalent | R4B `DeviceRequest.meta` maps as Equivalent to R5 `DeviceRequest.meta` |
| DeviceRequest.modifierExtension | DeviceRequest.modifierExtension | RelatedTo | R4B `DeviceRequest.modifierExtension` maps as RelatedTo to R5 `DeviceRequest.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| DeviceRequest.note | DeviceRequest.note | SourceIsNarrowerThanTarget | R4B `DeviceRequest.note` maps as SourceIsNarrowerThanTarget to R5 `DeviceRequest.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| DeviceRequest.occurrence[x] | DeviceRequest.occurrence[x] | Equivalent | R4B `DeviceRequest.occurrence[x]` maps as Equivalent to R5 `DeviceRequest.occurrence[x]` |
| DeviceRequest.parameter | DeviceRequest.parameter | Equivalent | R4B `DeviceRequest.parameter` maps as Equivalent to R5 `DeviceRequest.parameter` |
| DeviceRequest.parameter.code | DeviceRequest.parameter.code | Equivalent | R4B `DeviceRequest.parameter.code` maps as Equivalent to R5 `DeviceRequest.parameter.code` |
| DeviceRequest.parameter.extension | DeviceRequest.parameter.extension | RelatedTo | R4B `DeviceRequest.parameter.extension` maps as RelatedTo to R5 `DeviceRequest.parameter.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| DeviceRequest.parameter.id | DeviceRequest.parameter.id | Equivalent | R4B `DeviceRequest.parameter.id` maps as Equivalent to R5 `DeviceRequest.parameter.id` |
| DeviceRequest.parameter.modifierExtension | DeviceRequest.parameter.modifierExtension | RelatedTo | R4B `DeviceRequest.parameter.modifierExtension` maps as RelatedTo to R5 `DeviceRequest.parameter.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| DeviceRequest.parameter.value[x] | DeviceRequest.parameter.value[x] | Equivalent | R4B `DeviceRequest.parameter.value[x]` maps as Equivalent to R5 `DeviceRequest.parameter.value[x]` |
| DeviceRequest.performer | DeviceRequest.performer | SourceIsBroaderThanTarget | R4B `DeviceRequest.performer` maps as SourceIsBroaderThanTarget to R5 `DeviceRequest.performer` - performer has change due to type change: R4B performer Reference has no equivalent or mapped type in R5 performer |
| DeviceRequest.performerType | - | DoesNotExistInTarget | R4B `DeviceRequest.performerType` does not appear in the target and has no mapping for `DeviceRequest`. |
| DeviceRequest.priority | DeviceRequest.priority | Equivalent | R4B `DeviceRequest.priority` maps as Equivalent to R5 `DeviceRequest.priority` - priority has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-priority|4.3.0 and http://hl7.org/fhir/ValueSet/request-priority|5.0.0 (Equivalent) |
| DeviceRequest.priorRequest | - | DoesNotExistInTarget | R4B `DeviceRequest.priorRequest` does not appear in the target and has no mapping for `DeviceRequest`. |
| DeviceRequest.reasonCode | - | DoesNotExistInTarget | R4B `DeviceRequest.reasonCode` does not appear in the target and has no mapping for `DeviceRequest`. |
| DeviceRequest.reasonReference | - | DoesNotExistInTarget | R4B `DeviceRequest.reasonReference` does not appear in the target and has no mapping for `DeviceRequest`. |
| DeviceRequest.relevantHistory | DeviceRequest.relevantHistory | Equivalent | R4B `DeviceRequest.relevantHistory` maps as Equivalent to R5 `DeviceRequest.relevantHistory` |
| DeviceRequest.requester | DeviceRequest.requester | Equivalent | R4B `DeviceRequest.requester` maps as Equivalent to R5 `DeviceRequest.requester` |
| DeviceRequest.status | DeviceRequest.status | Equivalent | R4B `DeviceRequest.status` maps as Equivalent to R5 `DeviceRequest.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-status|4.3.0 and http://hl7.org/fhir/ValueSet/request-status|5.0.0 (Equivalent) |
| DeviceRequest.subject | DeviceRequest.subject | Equivalent | R4B `DeviceRequest.subject` maps as Equivalent to R5 `DeviceRequest.subject` |
| DeviceRequest.supportingInfo | DeviceRequest.supportingInfo | Equivalent | R4B `DeviceRequest.supportingInfo` maps as Equivalent to R5 `DeviceRequest.supportingInfo` |
| DeviceRequest.text | DeviceRequest.text | Equivalent | R4B `DeviceRequest.text` maps as Equivalent to R5 `DeviceRequest.text` |

