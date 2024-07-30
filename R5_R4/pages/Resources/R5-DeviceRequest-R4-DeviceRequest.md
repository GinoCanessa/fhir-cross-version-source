Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | DeviceRequest |  | Represents a request a device to be provided to a specific patient. The device may be an implantable device to be subsequently implanted, or an external assistive device, such as a walker, to be delivered and subsequently be used. | 40 | 29 |
| Target | DeviceRequest |  | Represents a request for a patient to employ a medical device. The device may be an implantable device, or an external assistive device, such as a walker. | 38 | 27 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 7 |
Equivalent | 4 |
RelatedTo | 29 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| DeviceRequest | DeviceRequest | Equivalent | R5 `DeviceRequest` maps as Equivalent to R4 `DeviceRequest` |
| DeviceRequest.asNeeded | - | DoesNotExistInTarget | R5 `DeviceRequest.asNeeded` does not appear in the target and has no mapping for `DeviceRequest`. |
| DeviceRequest.asNeededFor | - | DoesNotExistInTarget | R5 `DeviceRequest.asNeededFor` does not appear in the target and has no mapping for `DeviceRequest`. |
| DeviceRequest.authoredOn | DeviceRequest.authoredOn | Equivalent | R5 `DeviceRequest.authoredOn` maps as Equivalent to R4 `DeviceRequest.authoredOn` |
| DeviceRequest.basedOn | DeviceRequest.basedOn | Equivalent | R5 `DeviceRequest.basedOn` maps as Equivalent to R4 `DeviceRequest.basedOn` |
| DeviceRequest.code | - | DoesNotExistInTarget | R5 `DeviceRequest.code` does not appear in the target and has no mapping for `DeviceRequest`. |
| DeviceRequest.contained | DeviceRequest.contained | Equivalent | R5 `DeviceRequest.contained` maps as Equivalent to R4 `DeviceRequest.contained` |
| DeviceRequest.doNotPerform | - | DoesNotExistInTarget | R5 `DeviceRequest.doNotPerform` does not appear in the target and has no mapping for `DeviceRequest`. |
| DeviceRequest.encounter | DeviceRequest.encounter | Equivalent | R5 `DeviceRequest.encounter` maps as Equivalent to R4 `DeviceRequest.encounter` |
| DeviceRequest.extension | DeviceRequest.extension | SourceIsBroaderThanTarget | R5 `DeviceRequest.extension` maps as SourceIsBroaderThanTarget to R4 `DeviceRequest.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| DeviceRequest.groupIdentifier | DeviceRequest.groupIdentifier | Equivalent | R5 `DeviceRequest.groupIdentifier` maps as Equivalent to R4 `DeviceRequest.groupIdentifier` |
| DeviceRequest.id | DeviceRequest.id | Equivalent | R5 `DeviceRequest.id` maps as Equivalent to R4 `DeviceRequest.id` |
| DeviceRequest.identifier | DeviceRequest.identifier | Equivalent | R5 `DeviceRequest.identifier` maps as Equivalent to R4 `DeviceRequest.identifier` |
| DeviceRequest.implicitRules | DeviceRequest.implicitRules | Equivalent | R5 `DeviceRequest.implicitRules` maps as Equivalent to R4 `DeviceRequest.implicitRules` |
| DeviceRequest.instantiatesCanonical | DeviceRequest.instantiatesCanonical | Equivalent | R5 `DeviceRequest.instantiatesCanonical` maps as Equivalent to R4 `DeviceRequest.instantiatesCanonical` |
| DeviceRequest.instantiatesUri | DeviceRequest.instantiatesUri | Equivalent | R5 `DeviceRequest.instantiatesUri` maps as Equivalent to R4 `DeviceRequest.instantiatesUri` |
| DeviceRequest.insurance | DeviceRequest.insurance | Equivalent | R5 `DeviceRequest.insurance` maps as Equivalent to R4 `DeviceRequest.insurance` |
| DeviceRequest.intent | DeviceRequest.intent | Equivalent | R5 `DeviceRequest.intent` maps as Equivalent to R4 `DeviceRequest.intent` - intent has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-intent|5.0.0 and http://hl7.org/fhir/ValueSet/request-intent|4.0.1 (Equivalent) |
| DeviceRequest.language | DeviceRequest.language | RelatedTo | R5 `DeviceRequest.language` maps as RelatedTo to R4 `DeviceRequest.language` - language changed the binding strength from Required to Preferred |
| DeviceRequest.meta | DeviceRequest.meta | Equivalent | R5 `DeviceRequest.meta` maps as Equivalent to R4 `DeviceRequest.meta` |
| DeviceRequest.modifierExtension | DeviceRequest.modifierExtension | SourceIsBroaderThanTarget | R5 `DeviceRequest.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `DeviceRequest.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| DeviceRequest.note | DeviceRequest.note | SourceIsBroaderThanTarget | R5 `DeviceRequest.note` maps as SourceIsBroaderThanTarget to R4 `DeviceRequest.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4 `note` |
| DeviceRequest.occurrence[x] | DeviceRequest.occurrence[x] | Equivalent | R5 `DeviceRequest.occurrence[x]` maps as Equivalent to R4 `DeviceRequest.occurrence[x]` |
| DeviceRequest.parameter | DeviceRequest.parameter | Equivalent | R5 `DeviceRequest.parameter` maps as Equivalent to R4 `DeviceRequest.parameter` |
| DeviceRequest.parameter.code | DeviceRequest.parameter.code | Equivalent | R5 `DeviceRequest.parameter.code` maps as Equivalent to R4 `DeviceRequest.parameter.code` |
| DeviceRequest.parameter.extension | DeviceRequest.parameter.extension | SourceIsBroaderThanTarget | R5 `DeviceRequest.parameter.extension` maps as SourceIsBroaderThanTarget to R4 `DeviceRequest.parameter.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| DeviceRequest.parameter.id | DeviceRequest.parameter.id | Equivalent | R5 `DeviceRequest.parameter.id` maps as Equivalent to R4 `DeviceRequest.parameter.id` |
| DeviceRequest.parameter.modifierExtension | DeviceRequest.parameter.modifierExtension | SourceIsBroaderThanTarget | R5 `DeviceRequest.parameter.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `DeviceRequest.parameter.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| DeviceRequest.parameter.value[x] | DeviceRequest.parameter.value[x] | Equivalent | R5 `DeviceRequest.parameter.value[x]` maps as Equivalent to R4 `DeviceRequest.parameter.value[x]` |
| DeviceRequest.performer | DeviceRequest.performer | SourceIsBroaderThanTarget | R5 `DeviceRequest.performer` maps as SourceIsBroaderThanTarget to R4 `DeviceRequest.performer` - performer has change due to type change: R5 performer CodeableReference has no equivalent or mapped type in R4 performer |
| DeviceRequest.priority | DeviceRequest.priority | Equivalent | R5 `DeviceRequest.priority` maps as Equivalent to R4 `DeviceRequest.priority` - priority has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-priority|5.0.0 and http://hl7.org/fhir/ValueSet/request-priority|4.0.1 (Equivalent) |
| DeviceRequest.quantity | - | DoesNotExistInTarget | R5 `DeviceRequest.quantity` does not appear in the target and has no mapping for `DeviceRequest`. |
| DeviceRequest.reason | - | DoesNotExistInTarget | R5 `DeviceRequest.reason` does not appear in the target and has no mapping for `DeviceRequest`. |
| DeviceRequest.relevantHistory | DeviceRequest.relevantHistory | Equivalent | R5 `DeviceRequest.relevantHistory` maps as Equivalent to R4 `DeviceRequest.relevantHistory` |
| DeviceRequest.replaces | - | DoesNotExistInTarget | R5 `DeviceRequest.replaces` does not appear in the target and has no mapping for `DeviceRequest`. |
| DeviceRequest.requester | DeviceRequest.requester | Equivalent | R5 `DeviceRequest.requester` maps as Equivalent to R4 `DeviceRequest.requester` |
| DeviceRequest.status | DeviceRequest.status | Equivalent | R5 `DeviceRequest.status` maps as Equivalent to R4 `DeviceRequest.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-status|5.0.0 and http://hl7.org/fhir/ValueSet/request-status|4.0.1 (Equivalent) |
| DeviceRequest.subject | DeviceRequest.subject | Equivalent | R5 `DeviceRequest.subject` maps as Equivalent to R4 `DeviceRequest.subject` |
| DeviceRequest.supportingInfo | DeviceRequest.supportingInfo | Equivalent | R5 `DeviceRequest.supportingInfo` maps as Equivalent to R4 `DeviceRequest.supportingInfo` |
| DeviceRequest.text | DeviceRequest.text | Equivalent | R5 `DeviceRequest.text` maps as Equivalent to R4 `DeviceRequest.text` |

