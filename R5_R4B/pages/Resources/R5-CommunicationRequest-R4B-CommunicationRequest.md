Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | CommunicationRequest |  | A request to convey information; e.g. the CDS system proposes that an alert be sent to a responsible provider, the CDS system proposes that the public health agency be notified about a reportable condition. | 35 | 24 |
| Target | CommunicationRequest |  | A request to convey information; e.g. the CDS system proposes that an alert be sent to a responsible provider, the CDS system proposes that the public health agency be notified about a reportable condition. | 35 | 24 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 3 |
Equivalent | 4 |
RelatedTo | 28 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| CommunicationRequest | CommunicationRequest | Equivalent | R5 `CommunicationRequest` maps as Equivalent to R4B `CommunicationRequest` |
| CommunicationRequest.about | CommunicationRequest.about | Equivalent | R5 `CommunicationRequest.about` maps as Equivalent to R4B `CommunicationRequest.about` |
| CommunicationRequest.authoredOn | CommunicationRequest.authoredOn | Equivalent | R5 `CommunicationRequest.authoredOn` maps as Equivalent to R4B `CommunicationRequest.authoredOn` |
| CommunicationRequest.basedOn | CommunicationRequest.basedOn | Equivalent | R5 `CommunicationRequest.basedOn` maps as Equivalent to R4B `CommunicationRequest.basedOn` |
| CommunicationRequest.category | CommunicationRequest.category | Equivalent | R5 `CommunicationRequest.category` maps as Equivalent to R4B `CommunicationRequest.category` |
| CommunicationRequest.contained | CommunicationRequest.contained | Equivalent | R5 `CommunicationRequest.contained` maps as Equivalent to R4B `CommunicationRequest.contained` |
| CommunicationRequest.doNotPerform | CommunicationRequest.doNotPerform | Equivalent | R5 `CommunicationRequest.doNotPerform` maps as Equivalent to R4B `CommunicationRequest.doNotPerform` |
| CommunicationRequest.encounter | CommunicationRequest.encounter | Equivalent | R5 `CommunicationRequest.encounter` maps as Equivalent to R4B `CommunicationRequest.encounter` |
| CommunicationRequest.extension | CommunicationRequest.extension | SourceIsBroaderThanTarget | R5 `CommunicationRequest.extension` maps as SourceIsBroaderThanTarget to R4B `CommunicationRequest.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| CommunicationRequest.groupIdentifier | CommunicationRequest.groupIdentifier | Equivalent | R5 `CommunicationRequest.groupIdentifier` maps as Equivalent to R4B `CommunicationRequest.groupIdentifier` |
| CommunicationRequest.id | CommunicationRequest.id | Equivalent | R5 `CommunicationRequest.id` maps as Equivalent to R4B `CommunicationRequest.id` |
| CommunicationRequest.identifier | CommunicationRequest.identifier | Equivalent | R5 `CommunicationRequest.identifier` maps as Equivalent to R4B `CommunicationRequest.identifier` |
| CommunicationRequest.implicitRules | CommunicationRequest.implicitRules | Equivalent | R5 `CommunicationRequest.implicitRules` maps as Equivalent to R4B `CommunicationRequest.implicitRules` |
| CommunicationRequest.informationProvider | - | DoesNotExistInTarget | R5 `CommunicationRequest.informationProvider` does not appear in the target and has no mapping for `CommunicationRequest`. |
| CommunicationRequest.intent | - | DoesNotExistInTarget | R5 `CommunicationRequest.intent` does not appear in the target and has no mapping for `CommunicationRequest`. |
| CommunicationRequest.language | CommunicationRequest.language | RelatedTo | R5 `CommunicationRequest.language` maps as RelatedTo to R4B `CommunicationRequest.language` - language changed the binding strength from Required to Preferred |
| CommunicationRequest.medium | CommunicationRequest.medium | Equivalent | R5 `CommunicationRequest.medium` maps as Equivalent to R4B `CommunicationRequest.medium` |
| CommunicationRequest.meta | CommunicationRequest.meta | Equivalent | R5 `CommunicationRequest.meta` maps as Equivalent to R4B `CommunicationRequest.meta` |
| CommunicationRequest.modifierExtension | CommunicationRequest.modifierExtension | SourceIsBroaderThanTarget | R5 `CommunicationRequest.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `CommunicationRequest.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| CommunicationRequest.note | CommunicationRequest.note | SourceIsBroaderThanTarget | R5 `CommunicationRequest.note` maps as SourceIsBroaderThanTarget to R4B `CommunicationRequest.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| CommunicationRequest.occurrence[x] | CommunicationRequest.occurrence[x] | Equivalent | R5 `CommunicationRequest.occurrence[x]` maps as Equivalent to R4B `CommunicationRequest.occurrence[x]` |
| CommunicationRequest.payload | CommunicationRequest.payload | Equivalent | R5 `CommunicationRequest.payload` maps as Equivalent to R4B `CommunicationRequest.payload` |
| CommunicationRequest.payload.content[x] | CommunicationRequest.payload.content[x] | RelatedTo | R5 `CommunicationRequest.payload.content[x]` maps as RelatedTo to R4B `CommunicationRequest.payload.content[x]` - content[x] has change due to type change: R5 `content[x]` `Attachment` maps as RelatedTo for R4B `content[x]`; content[x] has change due to type change: R5 content[x] CodeableConcept has no equivalent or mapped type in R4B content[x] |
| CommunicationRequest.payload.extension | CommunicationRequest.payload.extension | SourceIsBroaderThanTarget | R5 `CommunicationRequest.payload.extension` maps as SourceIsBroaderThanTarget to R4B `CommunicationRequest.payload.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| CommunicationRequest.payload.id | CommunicationRequest.payload.id | Equivalent | R5 `CommunicationRequest.payload.id` maps as Equivalent to R4B `CommunicationRequest.payload.id` |
| CommunicationRequest.payload.modifierExtension | CommunicationRequest.payload.modifierExtension | SourceIsBroaderThanTarget | R5 `CommunicationRequest.payload.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `CommunicationRequest.payload.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| CommunicationRequest.priority | CommunicationRequest.priority | Equivalent | R5 `CommunicationRequest.priority` maps as Equivalent to R4B `CommunicationRequest.priority` - priority has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-priority|5.0.0 and http://hl7.org/fhir/ValueSet/request-priority|4.3.0 (Equivalent) |
| CommunicationRequest.reason | - | DoesNotExistInTarget | R5 `CommunicationRequest.reason` does not appear in the target and has no mapping for `CommunicationRequest`. |
| CommunicationRequest.recipient | CommunicationRequest.recipient | SourceIsBroaderThanTarget | R5 `CommunicationRequest.recipient` maps as SourceIsBroaderThanTarget to R4B `CommunicationRequest.recipient` - recipient has change due to type change: R5 `recipient` `Reference` maps as SourceIsBroaderThanTarget for R4B `recipient` |
| CommunicationRequest.replaces | CommunicationRequest.replaces | Equivalent | R5 `CommunicationRequest.replaces` maps as Equivalent to R4B `CommunicationRequest.replaces` |
| CommunicationRequest.requester | CommunicationRequest.requester | Equivalent | R5 `CommunicationRequest.requester` maps as Equivalent to R4B `CommunicationRequest.requester` |
| CommunicationRequest.status | CommunicationRequest.status | Equivalent | R5 `CommunicationRequest.status` maps as Equivalent to R4B `CommunicationRequest.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-status|5.0.0 and http://hl7.org/fhir/ValueSet/request-status|4.3.0 (Equivalent) |
| CommunicationRequest.statusReason | CommunicationRequest.statusReason | Equivalent | R5 `CommunicationRequest.statusReason` maps as Equivalent to R4B `CommunicationRequest.statusReason` |
| CommunicationRequest.subject | CommunicationRequest.subject | Equivalent | R5 `CommunicationRequest.subject` maps as Equivalent to R4B `CommunicationRequest.subject` |
| CommunicationRequest.text | CommunicationRequest.text | Equivalent | R5 `CommunicationRequest.text` maps as Equivalent to R4B `CommunicationRequest.text` |

