Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | CommunicationRequest |  | A request to convey information; e.g. the CDS system proposes that an alert be sent to a responsible provider, the CDS system proposes that the public health agency be notified about a reportable condition. | 35 | 24 |
| Target | CommunicationRequest |  | A request to convey information; e.g. the CDS system proposes that an alert be sent to a responsible provider, the CDS system proposes that the public health agency be notified about a reportable condition. | 35 | 24 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 24 |
RelatedTo | 1 |
SourceIsBroaderThanTarget | 8 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| CommunicationRequest | CommunicationRequest | Equivalent | R5 `CommunicationRequest` maps as Equivalent to R4 `CommunicationRequest` |
| CommunicationRequest.about | CommunicationRequest.about | Equivalent | R5 `CommunicationRequest.about` maps as Equivalent to R4 `CommunicationRequest.about` |
| CommunicationRequest.authoredOn | CommunicationRequest.authoredOn | Equivalent | R5 `CommunicationRequest.authoredOn` maps as Equivalent to R4 `CommunicationRequest.authoredOn` |
| CommunicationRequest.basedOn | CommunicationRequest.basedOn | Equivalent | R5 `CommunicationRequest.basedOn` maps as Equivalent to R4 `CommunicationRequest.basedOn` |
| CommunicationRequest.category | CommunicationRequest.category | Equivalent | R5 `CommunicationRequest.category` maps as Equivalent to R4 `CommunicationRequest.category` |
| CommunicationRequest.contained | CommunicationRequest.contained | Equivalent | R5 `CommunicationRequest.contained` maps as Equivalent to R4 `CommunicationRequest.contained` |
| CommunicationRequest.doNotPerform | CommunicationRequest.doNotPerform | Equivalent | R5 `CommunicationRequest.doNotPerform` maps as Equivalent to R4 `CommunicationRequest.doNotPerform` |
| CommunicationRequest.encounter | CommunicationRequest.encounter | Equivalent | R5 `CommunicationRequest.encounter` maps as Equivalent to R4 `CommunicationRequest.encounter` |
| CommunicationRequest.extension | CommunicationRequest.extension | SourceIsBroaderThanTarget | R5 `CommunicationRequest.extension` maps as SourceIsBroaderThanTarget to R4 `CommunicationRequest.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| CommunicationRequest.groupIdentifier | CommunicationRequest.groupIdentifier | Equivalent | R5 `CommunicationRequest.groupIdentifier` maps as Equivalent to R4 `CommunicationRequest.groupIdentifier` |
| CommunicationRequest.id | CommunicationRequest.id | Equivalent | R5 `CommunicationRequest.id` maps as Equivalent to R4 `CommunicationRequest.id` |
| CommunicationRequest.identifier | CommunicationRequest.identifier | Equivalent | R5 `CommunicationRequest.identifier` maps as Equivalent to R4 `CommunicationRequest.identifier` |
| CommunicationRequest.implicitRules | CommunicationRequest.implicitRules | Equivalent | R5 `CommunicationRequest.implicitRules` maps as Equivalent to R4 `CommunicationRequest.implicitRules` |
| CommunicationRequest.informationProvider | CommunicationRequest.sender | SourceIsBroaderThanTarget | R5 `CommunicationRequest.informationProvider` maps as SourceIsBroaderThanTarget to R4 `CommunicationRequest.sender` - sender changed from array to scalar (max cardinality from * to 1); sender has change due to type change: R5 `informationProvider` `Reference` maps as SourceIsBroaderThanTarget for R4 `sender` |
| CommunicationRequest.intent | - | DoesNotExistInTarget | R5 `CommunicationRequest.intent` does not appear in the target and has no mapping for `CommunicationRequest`. |
| CommunicationRequest.language | CommunicationRequest.language | SourceIsNarrowerThanTarget | R5 `CommunicationRequest.language` maps as SourceIsNarrowerThanTarget to R4 `CommunicationRequest.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| CommunicationRequest.medium | CommunicationRequest.medium | Equivalent | R5 `CommunicationRequest.medium` maps as Equivalent to R4 `CommunicationRequest.medium` |
| CommunicationRequest.meta | CommunicationRequest.meta | Equivalent | R5 `CommunicationRequest.meta` maps as Equivalent to R4 `CommunicationRequest.meta` |
| CommunicationRequest.modifierExtension | CommunicationRequest.modifierExtension | SourceIsBroaderThanTarget | R5 `CommunicationRequest.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `CommunicationRequest.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| CommunicationRequest.note | CommunicationRequest.note | SourceIsBroaderThanTarget | R5 `CommunicationRequest.note` maps as SourceIsBroaderThanTarget to R4 `CommunicationRequest.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4 `note` |
| CommunicationRequest.occurrence[x] | CommunicationRequest.occurrence[x] | Equivalent | R5 `CommunicationRequest.occurrence[x]` maps as Equivalent to R4 `CommunicationRequest.occurrence[x]` |
| CommunicationRequest.payload | CommunicationRequest.payload | Equivalent | R5 `CommunicationRequest.payload` maps as Equivalent to R4 `CommunicationRequest.payload` |
| CommunicationRequest.payload.content[x] | CommunicationRequest.payload.content[x] | SourceIsBroaderThanTarget | R5 `CommunicationRequest.payload.content[x]` maps as SourceIsBroaderThanTarget to R4 `CommunicationRequest.payload.content[x]` - content[x] has change due to type change: R5 `content[x]` `Attachment` maps as RelatedTo for R4 `content[x]`; content[x] has change due to type change: R5 content[x] CodeableConcept has no equivalent or mapped type in R4 content[x] |
| CommunicationRequest.payload.extension | CommunicationRequest.payload.extension | SourceIsBroaderThanTarget | R5 `CommunicationRequest.payload.extension` maps as SourceIsBroaderThanTarget to R4 `CommunicationRequest.payload.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| CommunicationRequest.payload.id | CommunicationRequest.payload.id | Equivalent | R5 `CommunicationRequest.payload.id` maps as Equivalent to R4 `CommunicationRequest.payload.id` |
| CommunicationRequest.payload.modifierExtension | CommunicationRequest.payload.modifierExtension | SourceIsBroaderThanTarget | R5 `CommunicationRequest.payload.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `CommunicationRequest.payload.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| CommunicationRequest.priority | CommunicationRequest.priority | Equivalent | R5 `CommunicationRequest.priority` maps as Equivalent to R4 `CommunicationRequest.priority` - priority has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-priority|5.0.0 and http://hl7.org/fhir/ValueSet/request-priority|4.0.1 (Equivalent) |
| CommunicationRequest.reason | CommunicationRequest.reasonCode | SourceIsBroaderThanTarget | R5 `CommunicationRequest.reason` maps as SourceIsBroaderThanTarget to R4 `CommunicationRequest.reasonCode` - reasonCode has change due to type change: R5 reason CodeableReference has no equivalent or mapped type in R4 reasonCode |
| CommunicationRequest.reason | CommunicationRequest.reasonReference | RelatedTo | R5 `CommunicationRequest.reason` maps as RelatedTo to R4 `CommunicationRequest.reasonReference` - reasonReference removed a binding requirement - Example http://terminology.hl7.org/ValueSet/v3-ActReason; reasonReference has change due to type change: R5 reason CodeableReference has no equivalent or mapped type in R4 reasonReference |
| CommunicationRequest.recipient | CommunicationRequest.recipient | SourceIsBroaderThanTarget | R5 `CommunicationRequest.recipient` maps as SourceIsBroaderThanTarget to R4 `CommunicationRequest.recipient` - recipient has change due to type change: R5 `recipient` `Reference` maps as SourceIsBroaderThanTarget for R4 `recipient` |
| CommunicationRequest.replaces | CommunicationRequest.replaces | Equivalent | R5 `CommunicationRequest.replaces` maps as Equivalent to R4 `CommunicationRequest.replaces` |
| CommunicationRequest.requester | CommunicationRequest.requester | Equivalent | R5 `CommunicationRequest.requester` maps as Equivalent to R4 `CommunicationRequest.requester` |
| CommunicationRequest.status | CommunicationRequest.status | Equivalent | R5 `CommunicationRequest.status` maps as Equivalent to R4 `CommunicationRequest.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-status|5.0.0 and http://hl7.org/fhir/ValueSet/request-status|4.0.1 (Equivalent) |
| CommunicationRequest.statusReason | CommunicationRequest.statusReason | Equivalent | R5 `CommunicationRequest.statusReason` maps as Equivalent to R4 `CommunicationRequest.statusReason` |
| CommunicationRequest.subject | CommunicationRequest.subject | Equivalent | R5 `CommunicationRequest.subject` maps as Equivalent to R4 `CommunicationRequest.subject` |
| CommunicationRequest.text | CommunicationRequest.text | Equivalent | R5 `CommunicationRequest.text` maps as Equivalent to R4 `CommunicationRequest.text` |

