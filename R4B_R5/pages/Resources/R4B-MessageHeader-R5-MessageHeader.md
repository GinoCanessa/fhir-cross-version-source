Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | MessageHeader |  | The header for a message exchange that is either requesting or responding to an action.  The reference(s) that are the subject of the action as well as other information related to the action are typically transmitted in a bundle in which the MessageHeader resource instance is the first resource in the bundle. | 41 | 24 |
| Target | MessageHeader |  | The header for a message exchange that is either requesting or responding to an action.  The reference(s) that are the subject of the action as well as other information related to the action are typically transmitted in a bundle in which the MessageHeader resource instance is the first resource in the bundle. | 40 | 23 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 3 |
Equivalent | 4 |
RelatedTo | 34 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| MessageHeader | MessageHeader | Equivalent | R4B `MessageHeader` maps as Equivalent to R5 `MessageHeader` |
| MessageHeader.author | MessageHeader.author | SourceIsNarrowerThanTarget | R4B `MessageHeader.author` maps as SourceIsNarrowerThanTarget to R5 `MessageHeader.author` - author has change due to type change: R4B `author` `Reference` maps as SourceIsNarrowerThanTarget for R5 `author` |
| MessageHeader.contained | MessageHeader.contained | Equivalent | R4B `MessageHeader.contained` maps as Equivalent to R5 `MessageHeader.contained` |
| MessageHeader.definition | MessageHeader.definition | Equivalent | R4B `MessageHeader.definition` maps as Equivalent to R5 `MessageHeader.definition` |
| MessageHeader.destination | MessageHeader.destination | Equivalent | R4B `MessageHeader.destination` maps as Equivalent to R5 `MessageHeader.destination` |
| MessageHeader.destination.endpoint | - | DoesNotExistInTarget | R4B `MessageHeader.destination.endpoint` does not appear in the target and has no mapping for `MessageHeader`. |
| MessageHeader.destination.extension | MessageHeader.destination.extension | RelatedTo | R4B `MessageHeader.destination.extension` maps as RelatedTo to R5 `MessageHeader.destination.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MessageHeader.destination.id | MessageHeader.destination.id | Equivalent | R4B `MessageHeader.destination.id` maps as Equivalent to R5 `MessageHeader.destination.id` |
| MessageHeader.destination.modifierExtension | MessageHeader.destination.modifierExtension | RelatedTo | R4B `MessageHeader.destination.modifierExtension` maps as RelatedTo to R5 `MessageHeader.destination.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MessageHeader.destination.name | MessageHeader.destination.name | Equivalent | R4B `MessageHeader.destination.name` maps as Equivalent to R5 `MessageHeader.destination.name` |
| MessageHeader.destination.receiver | MessageHeader.destination.receiver | Equivalent | R4B `MessageHeader.destination.receiver` maps as Equivalent to R5 `MessageHeader.destination.receiver` |
| MessageHeader.destination.target | MessageHeader.destination.target | Equivalent | R4B `MessageHeader.destination.target` maps as Equivalent to R5 `MessageHeader.destination.target` |
| MessageHeader.enterer | - | DoesNotExistInTarget | R4B `MessageHeader.enterer` does not appear in the target and has no mapping for `MessageHeader`. |
| MessageHeader.event[x] | MessageHeader.event[x] | SourceIsBroaderThanTarget | R4B `MessageHeader.event[x]` maps as SourceIsBroaderThanTarget to R5 `MessageHeader.event[x]` - event[x] has change due to type change: R4B event[x] uri has no equivalent or mapped type in R5 event[x] |
| MessageHeader.extension | MessageHeader.extension | RelatedTo | R4B `MessageHeader.extension` maps as RelatedTo to R5 `MessageHeader.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MessageHeader.focus | MessageHeader.focus | Equivalent | R4B `MessageHeader.focus` maps as Equivalent to R5 `MessageHeader.focus` |
| MessageHeader.id | MessageHeader.id | Equivalent | R4B `MessageHeader.id` maps as Equivalent to R5 `MessageHeader.id` |
| MessageHeader.implicitRules | MessageHeader.implicitRules | Equivalent | R4B `MessageHeader.implicitRules` maps as Equivalent to R5 `MessageHeader.implicitRules` |
| MessageHeader.language | MessageHeader.language | RelatedTo | R4B `MessageHeader.language` maps as RelatedTo to R5 `MessageHeader.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| MessageHeader.meta | MessageHeader.meta | Equivalent | R4B `MessageHeader.meta` maps as Equivalent to R5 `MessageHeader.meta` |
| MessageHeader.modifierExtension | MessageHeader.modifierExtension | RelatedTo | R4B `MessageHeader.modifierExtension` maps as RelatedTo to R5 `MessageHeader.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MessageHeader.reason | MessageHeader.reason | Equivalent | R4B `MessageHeader.reason` maps as Equivalent to R5 `MessageHeader.reason` |
| MessageHeader.response | MessageHeader.response | Equivalent | R4B `MessageHeader.response` maps as Equivalent to R5 `MessageHeader.response` |
| MessageHeader.response.code | MessageHeader.response.code | Equivalent | R4B `MessageHeader.response.code` maps as Equivalent to R5 `MessageHeader.response.code` - code has compatible required binding for code type: http://hl7.org/fhir/ValueSet/response-code|4.3.0 and http://hl7.org/fhir/ValueSet/response-code|5.0.0 (Equivalent) |
| MessageHeader.response.details | MessageHeader.response.details | Equivalent | R4B `MessageHeader.response.details` maps as Equivalent to R5 `MessageHeader.response.details` |
| MessageHeader.response.extension | MessageHeader.response.extension | RelatedTo | R4B `MessageHeader.response.extension` maps as RelatedTo to R5 `MessageHeader.response.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MessageHeader.response.id | MessageHeader.response.id | Equivalent | R4B `MessageHeader.response.id` maps as Equivalent to R5 `MessageHeader.response.id` |
| MessageHeader.response.identifier | MessageHeader.response.identifier | SourceIsBroaderThanTarget | R4B `MessageHeader.response.identifier` maps as SourceIsBroaderThanTarget to R5 `MessageHeader.response.identifier` - identifier has change due to type change: R4B identifier id has no equivalent or mapped type in R5 identifier |
| MessageHeader.response.modifierExtension | MessageHeader.response.modifierExtension | RelatedTo | R4B `MessageHeader.response.modifierExtension` maps as RelatedTo to R5 `MessageHeader.response.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MessageHeader.responsible | MessageHeader.responsible | Equivalent | R4B `MessageHeader.responsible` maps as Equivalent to R5 `MessageHeader.responsible` |
| MessageHeader.sender | MessageHeader.sender | SourceIsNarrowerThanTarget | R4B `MessageHeader.sender` maps as SourceIsNarrowerThanTarget to R5 `MessageHeader.sender` - sender has change due to type change: R4B `sender` `Reference` maps as SourceIsNarrowerThanTarget for R5 `sender` |
| MessageHeader.source | MessageHeader.source | Equivalent | R4B `MessageHeader.source` maps as Equivalent to R5 `MessageHeader.source` |
| MessageHeader.source.contact | MessageHeader.source.contact | Equivalent | R4B `MessageHeader.source.contact` maps as Equivalent to R5 `MessageHeader.source.contact` |
| MessageHeader.source.endpoint | - | DoesNotExistInTarget | R4B `MessageHeader.source.endpoint` does not appear in the target and has no mapping for `MessageHeader`. |
| MessageHeader.source.extension | MessageHeader.source.extension | RelatedTo | R4B `MessageHeader.source.extension` maps as RelatedTo to R5 `MessageHeader.source.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MessageHeader.source.id | MessageHeader.source.id | Equivalent | R4B `MessageHeader.source.id` maps as Equivalent to R5 `MessageHeader.source.id` |
| MessageHeader.source.modifierExtension | MessageHeader.source.modifierExtension | RelatedTo | R4B `MessageHeader.source.modifierExtension` maps as RelatedTo to R5 `MessageHeader.source.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MessageHeader.source.name | MessageHeader.source.name | Equivalent | R4B `MessageHeader.source.name` maps as Equivalent to R5 `MessageHeader.source.name` |
| MessageHeader.source.software | MessageHeader.source.software | Equivalent | R4B `MessageHeader.source.software` maps as Equivalent to R5 `MessageHeader.source.software` |
| MessageHeader.source.version | MessageHeader.source.version | Equivalent | R4B `MessageHeader.source.version` maps as Equivalent to R5 `MessageHeader.source.version` |
| MessageHeader.text | MessageHeader.text | Equivalent | R4B `MessageHeader.text` maps as Equivalent to R5 `MessageHeader.text` |

