Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:50 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Communication |  | A clinical or business level record of information being transmitted or shared; e.g. an alert that was sent to a responsible provider, a public health agency communication to a provider/reporter in response to a case report for a reportable condition. | 35 | 24 |
| Target | Communication |  | An occurrence of information being transmitted; e.g. an alert that was sent to a responsible provider, a public health agency that was notified about a reportable condition. | 36 | 25 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 4 |
RelatedTo | 30 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Communication | Communication | Equivalent | R5 `Communication` maps as Equivalent to R4 `Communication` |
| Communication.about | Communication.about | Equivalent | R5 `Communication.about` maps as Equivalent to R4 `Communication.about` |
| Communication.basedOn | Communication.basedOn | Equivalent | R5 `Communication.basedOn` maps as Equivalent to R4 `Communication.basedOn` |
| Communication.category | Communication.category | Equivalent | R5 `Communication.category` maps as Equivalent to R4 `Communication.category` |
| Communication.contained | Communication.contained | Equivalent | R5 `Communication.contained` maps as Equivalent to R4 `Communication.contained` |
| Communication.encounter | Communication.encounter | Equivalent | R5 `Communication.encounter` maps as Equivalent to R4 `Communication.encounter` |
| Communication.extension | Communication.extension | SourceIsBroaderThanTarget | R5 `Communication.extension` maps as SourceIsBroaderThanTarget to R4 `Communication.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Communication.id | Communication.id | Equivalent | R5 `Communication.id` maps as Equivalent to R4 `Communication.id` |
| Communication.identifier | Communication.identifier | Equivalent | R5 `Communication.identifier` maps as Equivalent to R4 `Communication.identifier` |
| Communication.implicitRules | Communication.implicitRules | Equivalent | R5 `Communication.implicitRules` maps as Equivalent to R4 `Communication.implicitRules` |
| Communication.inResponseTo | Communication.inResponseTo | Equivalent | R5 `Communication.inResponseTo` maps as Equivalent to R4 `Communication.inResponseTo` |
| Communication.instantiatesCanonical | Communication.instantiatesCanonical | Equivalent | R5 `Communication.instantiatesCanonical` maps as Equivalent to R4 `Communication.instantiatesCanonical` |
| Communication.instantiatesUri | Communication.instantiatesUri | Equivalent | R5 `Communication.instantiatesUri` maps as Equivalent to R4 `Communication.instantiatesUri` |
| Communication.language | Communication.language | RelatedTo | R5 `Communication.language` maps as RelatedTo to R4 `Communication.language` - language changed the binding strength from Required to Preferred |
| Communication.medium | Communication.medium | Equivalent | R5 `Communication.medium` maps as Equivalent to R4 `Communication.medium` |
| Communication.meta | Communication.meta | Equivalent | R5 `Communication.meta` maps as Equivalent to R4 `Communication.meta` |
| Communication.modifierExtension | Communication.modifierExtension | SourceIsBroaderThanTarget | R5 `Communication.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Communication.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Communication.note | Communication.note | SourceIsBroaderThanTarget | R5 `Communication.note` maps as SourceIsBroaderThanTarget to R4 `Communication.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4 `note` |
| Communication.partOf | Communication.partOf | Equivalent | R5 `Communication.partOf` maps as Equivalent to R4 `Communication.partOf` |
| Communication.payload | Communication.payload | Equivalent | R5 `Communication.payload` maps as Equivalent to R4 `Communication.payload` |
| Communication.payload.content[x] | Communication.payload.content[x] | RelatedTo | R5 `Communication.payload.content[x]` maps as RelatedTo to R4 `Communication.payload.content[x]` - content[x] has change due to type change: R5 `content[x]` `Attachment` maps as RelatedTo for R4 `content[x]`; content[x] has change due to type change: R5 content[x] CodeableConcept has no equivalent or mapped type in R4 content[x] |
| Communication.payload.extension | Communication.payload.extension | SourceIsBroaderThanTarget | R5 `Communication.payload.extension` maps as SourceIsBroaderThanTarget to R4 `Communication.payload.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Communication.payload.id | Communication.payload.id | Equivalent | R5 `Communication.payload.id` maps as Equivalent to R4 `Communication.payload.id` |
| Communication.payload.modifierExtension | Communication.payload.modifierExtension | SourceIsBroaderThanTarget | R5 `Communication.payload.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Communication.payload.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Communication.priority | Communication.priority | Equivalent | R5 `Communication.priority` maps as Equivalent to R4 `Communication.priority` - priority has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-priority|5.0.0 and http://hl7.org/fhir/ValueSet/request-priority|4.0.1 (Equivalent) |
| Communication.reason | - | DoesNotExistInTarget | R5 `Communication.reason` does not appear in the target and has no mapping for `Communication`. |
| Communication.received | Communication.received | Equivalent | R5 `Communication.received` maps as Equivalent to R4 `Communication.received` |
| Communication.recipient | Communication.recipient | SourceIsBroaderThanTarget | R5 `Communication.recipient` maps as SourceIsBroaderThanTarget to R4 `Communication.recipient` - recipient has change due to type change: R5 `recipient` `Reference` maps as SourceIsBroaderThanTarget for R4 `recipient` |
| Communication.sender | Communication.sender | SourceIsBroaderThanTarget | R5 `Communication.sender` maps as SourceIsBroaderThanTarget to R4 `Communication.sender` - sender has change due to type change: R5 `sender` `Reference` maps as SourceIsBroaderThanTarget for R4 `sender` |
| Communication.sent | Communication.sent | Equivalent | R5 `Communication.sent` maps as Equivalent to R4 `Communication.sent` |
| Communication.status | Communication.status | Equivalent | R5 `Communication.status` maps as Equivalent to R4 `Communication.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/event-status|5.0.0 and http://hl7.org/fhir/ValueSet/event-status|4.0.1 (Equivalent) |
| Communication.statusReason | Communication.statusReason | Equivalent | R5 `Communication.statusReason` maps as Equivalent to R4 `Communication.statusReason` |
| Communication.subject | Communication.subject | Equivalent | R5 `Communication.subject` maps as Equivalent to R4 `Communication.subject` |
| Communication.text | Communication.text | Equivalent | R5 `Communication.text` maps as Equivalent to R4 `Communication.text` |
| Communication.topic | Communication.topic | Equivalent | R5 `Communication.topic` maps as Equivalent to R4 `Communication.topic` |

