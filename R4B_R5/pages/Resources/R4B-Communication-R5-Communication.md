Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Communication |  | An occurrence of information being transmitted; e.g. an alert that was sent to a responsible provider, a public health agency that was notified about a reportable condition. | 36 | 25 |
| Target | Communication |  | A clinical or business level record of information being transmitted or shared; e.g. an alert that was sent to a responsible provider, a public health agency communication to a provider/reporter in response to a case report for a reportable condition. | 35 | 24 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 2 |
Equivalent | 4 |
RelatedTo | 30 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Communication | Communication | Equivalent | R4B `Communication` maps as Equivalent to R5 `Communication` |
| Communication.about | Communication.about | Equivalent | R4B `Communication.about` maps as Equivalent to R5 `Communication.about` |
| Communication.basedOn | Communication.basedOn | Equivalent | R4B `Communication.basedOn` maps as Equivalent to R5 `Communication.basedOn` |
| Communication.category | Communication.category | Equivalent | R4B `Communication.category` maps as Equivalent to R5 `Communication.category` |
| Communication.contained | Communication.contained | Equivalent | R4B `Communication.contained` maps as Equivalent to R5 `Communication.contained` |
| Communication.encounter | Communication.encounter | Equivalent | R4B `Communication.encounter` maps as Equivalent to R5 `Communication.encounter` |
| Communication.extension | Communication.extension | RelatedTo | R4B `Communication.extension` maps as RelatedTo to R5 `Communication.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Communication.id | Communication.id | Equivalent | R4B `Communication.id` maps as Equivalent to R5 `Communication.id` |
| Communication.identifier | Communication.identifier | Equivalent | R4B `Communication.identifier` maps as Equivalent to R5 `Communication.identifier` |
| Communication.implicitRules | Communication.implicitRules | Equivalent | R4B `Communication.implicitRules` maps as Equivalent to R5 `Communication.implicitRules` |
| Communication.inResponseTo | Communication.inResponseTo | Equivalent | R4B `Communication.inResponseTo` maps as Equivalent to R5 `Communication.inResponseTo` |
| Communication.instantiatesCanonical | Communication.instantiatesCanonical | Equivalent | R4B `Communication.instantiatesCanonical` maps as Equivalent to R5 `Communication.instantiatesCanonical` |
| Communication.instantiatesUri | Communication.instantiatesUri | Equivalent | R4B `Communication.instantiatesUri` maps as Equivalent to R5 `Communication.instantiatesUri` |
| Communication.language | Communication.language | RelatedTo | R4B `Communication.language` maps as RelatedTo to R5 `Communication.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Communication.medium | Communication.medium | Equivalent | R4B `Communication.medium` maps as Equivalent to R5 `Communication.medium` |
| Communication.meta | Communication.meta | Equivalent | R4B `Communication.meta` maps as Equivalent to R5 `Communication.meta` |
| Communication.modifierExtension | Communication.modifierExtension | RelatedTo | R4B `Communication.modifierExtension` maps as RelatedTo to R5 `Communication.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Communication.note | Communication.note | SourceIsNarrowerThanTarget | R4B `Communication.note` maps as SourceIsNarrowerThanTarget to R5 `Communication.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| Communication.partOf | Communication.partOf | Equivalent | R4B `Communication.partOf` maps as Equivalent to R5 `Communication.partOf` |
| Communication.payload | Communication.payload | Equivalent | R4B `Communication.payload` maps as Equivalent to R5 `Communication.payload` |
| Communication.payload.content[x] | Communication.payload.content[x] | RelatedTo | R4B `Communication.payload.content[x]` maps as RelatedTo to R5 `Communication.payload.content[x]` - content[x] has change due to type change: R4B content[x] string has no equivalent or mapped type in R5 content[x]; content[x] has change due to type change: R4B `content[x]` `Attachment` maps as RelatedTo for R5 `content[x]` |
| Communication.payload.extension | Communication.payload.extension | RelatedTo | R4B `Communication.payload.extension` maps as RelatedTo to R5 `Communication.payload.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Communication.payload.id | Communication.payload.id | Equivalent | R4B `Communication.payload.id` maps as Equivalent to R5 `Communication.payload.id` |
| Communication.payload.modifierExtension | Communication.payload.modifierExtension | RelatedTo | R4B `Communication.payload.modifierExtension` maps as RelatedTo to R5 `Communication.payload.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Communication.priority | Communication.priority | Equivalent | R4B `Communication.priority` maps as Equivalent to R5 `Communication.priority` - priority has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-priority|4.3.0 and http://hl7.org/fhir/ValueSet/request-priority|5.0.0 (Equivalent) |
| Communication.reasonCode | - | DoesNotExistInTarget | R4B `Communication.reasonCode` does not appear in the target and has no mapping for `Communication`. |
| Communication.reasonReference | - | DoesNotExistInTarget | R4B `Communication.reasonReference` does not appear in the target and has no mapping for `Communication`. |
| Communication.received | Communication.received | Equivalent | R4B `Communication.received` maps as Equivalent to R5 `Communication.received` |
| Communication.recipient | Communication.recipient | SourceIsNarrowerThanTarget | R4B `Communication.recipient` maps as SourceIsNarrowerThanTarget to R5 `Communication.recipient` - recipient has change due to type change: R4B `recipient` `Reference` maps as SourceIsNarrowerThanTarget for R5 `recipient` |
| Communication.sender | Communication.sender | SourceIsNarrowerThanTarget | R4B `Communication.sender` maps as SourceIsNarrowerThanTarget to R5 `Communication.sender` - sender has change due to type change: R4B `sender` `Reference` maps as SourceIsNarrowerThanTarget for R5 `sender` |
| Communication.sent | Communication.sent | Equivalent | R4B `Communication.sent` maps as Equivalent to R5 `Communication.sent` |
| Communication.status | Communication.status | Equivalent | R4B `Communication.status` maps as Equivalent to R5 `Communication.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/event-status|4.3.0 and http://hl7.org/fhir/ValueSet/event-status|5.0.0 (Equivalent) |
| Communication.statusReason | Communication.statusReason | Equivalent | R4B `Communication.statusReason` maps as Equivalent to R5 `Communication.statusReason` |
| Communication.subject | Communication.subject | Equivalent | R4B `Communication.subject` maps as Equivalent to R5 `Communication.subject` |
| Communication.text | Communication.text | Equivalent | R4B `Communication.text` maps as Equivalent to R5 `Communication.text` |
| Communication.topic | Communication.topic | Equivalent | R4B `Communication.topic` maps as Equivalent to R5 `Communication.topic` |

