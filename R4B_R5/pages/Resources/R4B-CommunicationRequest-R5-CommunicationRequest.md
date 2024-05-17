Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

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
| CommunicationRequest | CommunicationRequest | Equivalent | R4B `CommunicationRequest` maps as Equivalent to R5 `CommunicationRequest` |
| CommunicationRequest.about | CommunicationRequest.about | Equivalent | R4B `CommunicationRequest.about` maps as Equivalent to R5 `CommunicationRequest.about` |
| CommunicationRequest.authoredOn | CommunicationRequest.authoredOn | Equivalent | R4B `CommunicationRequest.authoredOn` maps as Equivalent to R5 `CommunicationRequest.authoredOn` |
| CommunicationRequest.basedOn | CommunicationRequest.basedOn | Equivalent | R4B `CommunicationRequest.basedOn` maps as Equivalent to R5 `CommunicationRequest.basedOn` |
| CommunicationRequest.category | CommunicationRequest.category | Equivalent | R4B `CommunicationRequest.category` maps as Equivalent to R5 `CommunicationRequest.category` |
| CommunicationRequest.contained | CommunicationRequest.contained | Equivalent | R4B `CommunicationRequest.contained` maps as Equivalent to R5 `CommunicationRequest.contained` |
| CommunicationRequest.doNotPerform | CommunicationRequest.doNotPerform | Equivalent | R4B `CommunicationRequest.doNotPerform` maps as Equivalent to R5 `CommunicationRequest.doNotPerform` |
| CommunicationRequest.encounter | CommunicationRequest.encounter | Equivalent | R4B `CommunicationRequest.encounter` maps as Equivalent to R5 `CommunicationRequest.encounter` |
| CommunicationRequest.extension | CommunicationRequest.extension | RelatedTo | R4B `CommunicationRequest.extension` maps as RelatedTo to R5 `CommunicationRequest.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| CommunicationRequest.groupIdentifier | CommunicationRequest.groupIdentifier | Equivalent | R4B `CommunicationRequest.groupIdentifier` maps as Equivalent to R5 `CommunicationRequest.groupIdentifier` |
| CommunicationRequest.id | CommunicationRequest.id | Equivalent | R4B `CommunicationRequest.id` maps as Equivalent to R5 `CommunicationRequest.id` |
| CommunicationRequest.identifier | CommunicationRequest.identifier | Equivalent | R4B `CommunicationRequest.identifier` maps as Equivalent to R5 `CommunicationRequest.identifier` |
| CommunicationRequest.implicitRules | CommunicationRequest.implicitRules | Equivalent | R4B `CommunicationRequest.implicitRules` maps as Equivalent to R5 `CommunicationRequest.implicitRules` |
| CommunicationRequest.language | CommunicationRequest.language | RelatedTo | R4B `CommunicationRequest.language` maps as RelatedTo to R5 `CommunicationRequest.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| CommunicationRequest.medium | CommunicationRequest.medium | Equivalent | R4B `CommunicationRequest.medium` maps as Equivalent to R5 `CommunicationRequest.medium` |
| CommunicationRequest.meta | CommunicationRequest.meta | Equivalent | R4B `CommunicationRequest.meta` maps as Equivalent to R5 `CommunicationRequest.meta` |
| CommunicationRequest.modifierExtension | CommunicationRequest.modifierExtension | RelatedTo | R4B `CommunicationRequest.modifierExtension` maps as RelatedTo to R5 `CommunicationRequest.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| CommunicationRequest.note | CommunicationRequest.note | SourceIsNarrowerThanTarget | R4B `CommunicationRequest.note` maps as SourceIsNarrowerThanTarget to R5 `CommunicationRequest.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| CommunicationRequest.occurrence[x] | CommunicationRequest.occurrence[x] | Equivalent | R4B `CommunicationRequest.occurrence[x]` maps as Equivalent to R5 `CommunicationRequest.occurrence[x]` |
| CommunicationRequest.payload | CommunicationRequest.payload | Equivalent | R4B `CommunicationRequest.payload` maps as Equivalent to R5 `CommunicationRequest.payload` |
| CommunicationRequest.payload.content[x] | CommunicationRequest.payload.content[x] | RelatedTo | R4B `CommunicationRequest.payload.content[x]` maps as RelatedTo to R5 `CommunicationRequest.payload.content[x]` - content[x] has change due to type change: R4B content[x] string has no equivalent or mapped type in R5 content[x]; content[x] has change due to type change: R4B `content[x]` `Attachment` maps as RelatedTo for R5 `content[x]` |
| CommunicationRequest.payload.extension | CommunicationRequest.payload.extension | RelatedTo | R4B `CommunicationRequest.payload.extension` maps as RelatedTo to R5 `CommunicationRequest.payload.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| CommunicationRequest.payload.id | CommunicationRequest.payload.id | Equivalent | R4B `CommunicationRequest.payload.id` maps as Equivalent to R5 `CommunicationRequest.payload.id` |
| CommunicationRequest.payload.modifierExtension | CommunicationRequest.payload.modifierExtension | RelatedTo | R4B `CommunicationRequest.payload.modifierExtension` maps as RelatedTo to R5 `CommunicationRequest.payload.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| CommunicationRequest.priority | CommunicationRequest.priority | Equivalent | R4B `CommunicationRequest.priority` maps as Equivalent to R5 `CommunicationRequest.priority` - priority has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-priority|4.3.0 and http://hl7.org/fhir/ValueSet/request-priority|5.0.0 (Equivalent) |
| CommunicationRequest.reasonCode | - | DoesNotExistInTarget | R4B `CommunicationRequest.reasonCode` does not appear in the target and has no mapping for `CommunicationRequest`. |
| CommunicationRequest.reasonReference | - | DoesNotExistInTarget | R4B `CommunicationRequest.reasonReference` does not appear in the target and has no mapping for `CommunicationRequest`. |
| CommunicationRequest.recipient | CommunicationRequest.recipient | SourceIsNarrowerThanTarget | R4B `CommunicationRequest.recipient` maps as SourceIsNarrowerThanTarget to R5 `CommunicationRequest.recipient` - recipient has change due to type change: R4B `recipient` `Reference` maps as SourceIsNarrowerThanTarget for R5 `recipient` |
| CommunicationRequest.replaces | CommunicationRequest.replaces | Equivalent | R4B `CommunicationRequest.replaces` maps as Equivalent to R5 `CommunicationRequest.replaces` |
| CommunicationRequest.requester | CommunicationRequest.requester | Equivalent | R4B `CommunicationRequest.requester` maps as Equivalent to R5 `CommunicationRequest.requester` |
| CommunicationRequest.sender | - | DoesNotExistInTarget | R4B `CommunicationRequest.sender` does not appear in the target and has no mapping for `CommunicationRequest`. |
| CommunicationRequest.status | CommunicationRequest.status | Equivalent | R4B `CommunicationRequest.status` maps as Equivalent to R5 `CommunicationRequest.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-status|4.3.0 and http://hl7.org/fhir/ValueSet/request-status|5.0.0 (Equivalent) |
| CommunicationRequest.statusReason | CommunicationRequest.statusReason | Equivalent | R4B `CommunicationRequest.statusReason` maps as Equivalent to R5 `CommunicationRequest.statusReason` |
| CommunicationRequest.subject | CommunicationRequest.subject | Equivalent | R4B `CommunicationRequest.subject` maps as Equivalent to R5 `CommunicationRequest.subject` |
| CommunicationRequest.text | CommunicationRequest.text | Equivalent | R4B `CommunicationRequest.text` maps as Equivalent to R5 `CommunicationRequest.text` |

