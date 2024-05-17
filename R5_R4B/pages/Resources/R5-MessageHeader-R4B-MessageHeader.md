Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | MessageHeader |  | The header for a message exchange that is either requesting or responding to an action.  The reference(s) that are the subject of the action as well as other information related to the action are typically transmitted in a bundle in which the MessageHeader resource instance is the first resource in the bundle. | 40 | 23 |
| Target | MessageHeader |  | The header for a message exchange that is either requesting or responding to an action.  The reference(s) that are the subject of the action as well as other information related to the action are typically transmitted in a bundle in which the MessageHeader resource instance is the first resource in the bundle. | 41 | 24 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 2 |
Equivalent | 4 |
RelatedTo | 34 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| MessageHeader | MessageHeader | Equivalent | R5 `MessageHeader` maps as Equivalent to R4B `MessageHeader` |
| MessageHeader.author | MessageHeader.author | SourceIsBroaderThanTarget | R5 `MessageHeader.author` maps as SourceIsBroaderThanTarget to R4B `MessageHeader.author` - author has change due to type change: R5 `author` `Reference` maps as SourceIsBroaderThanTarget for R4B `author` |
| MessageHeader.contained | MessageHeader.contained | Equivalent | R5 `MessageHeader.contained` maps as Equivalent to R4B `MessageHeader.contained` |
| MessageHeader.definition | MessageHeader.definition | Equivalent | R5 `MessageHeader.definition` maps as Equivalent to R4B `MessageHeader.definition` |
| MessageHeader.destination | MessageHeader.destination | Equivalent | R5 `MessageHeader.destination` maps as Equivalent to R4B `MessageHeader.destination` |
| MessageHeader.destination.endpoint[x] | - | DoesNotExistInTarget | R5 `MessageHeader.destination.endpoint[x]` does not appear in the target and has no mapping for `MessageHeader`. |
| MessageHeader.destination.extension | MessageHeader.destination.extension | SourceIsBroaderThanTarget | R5 `MessageHeader.destination.extension` maps as SourceIsBroaderThanTarget to R4B `MessageHeader.destination.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| MessageHeader.destination.id | MessageHeader.destination.id | Equivalent | R5 `MessageHeader.destination.id` maps as Equivalent to R4B `MessageHeader.destination.id` |
| MessageHeader.destination.modifierExtension | MessageHeader.destination.modifierExtension | SourceIsBroaderThanTarget | R5 `MessageHeader.destination.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `MessageHeader.destination.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| MessageHeader.destination.name | MessageHeader.destination.name | Equivalent | R5 `MessageHeader.destination.name` maps as Equivalent to R4B `MessageHeader.destination.name` |
| MessageHeader.destination.receiver | MessageHeader.destination.receiver | Equivalent | R5 `MessageHeader.destination.receiver` maps as Equivalent to R4B `MessageHeader.destination.receiver` |
| MessageHeader.destination.target | MessageHeader.destination.target | Equivalent | R5 `MessageHeader.destination.target` maps as Equivalent to R4B `MessageHeader.destination.target` |
| MessageHeader.event[x] | MessageHeader.event[x] | SourceIsBroaderThanTarget | R5 `MessageHeader.event[x]` maps as SourceIsBroaderThanTarget to R4B `MessageHeader.event[x]` - event[x] has change due to type change: R5 event[x] canonical has no equivalent or mapped type in R4B event[x] |
| MessageHeader.extension | MessageHeader.extension | SourceIsBroaderThanTarget | R5 `MessageHeader.extension` maps as SourceIsBroaderThanTarget to R4B `MessageHeader.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| MessageHeader.focus | MessageHeader.focus | Equivalent | R5 `MessageHeader.focus` maps as Equivalent to R4B `MessageHeader.focus` |
| MessageHeader.id | MessageHeader.id | Equivalent | R5 `MessageHeader.id` maps as Equivalent to R4B `MessageHeader.id` |
| MessageHeader.implicitRules | MessageHeader.implicitRules | Equivalent | R5 `MessageHeader.implicitRules` maps as Equivalent to R4B `MessageHeader.implicitRules` |
| MessageHeader.language | MessageHeader.language | RelatedTo | R5 `MessageHeader.language` maps as RelatedTo to R4B `MessageHeader.language` - language changed the binding strength from Required to Preferred |
| MessageHeader.meta | MessageHeader.meta | Equivalent | R5 `MessageHeader.meta` maps as Equivalent to R4B `MessageHeader.meta` |
| MessageHeader.modifierExtension | MessageHeader.modifierExtension | SourceIsBroaderThanTarget | R5 `MessageHeader.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `MessageHeader.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| MessageHeader.reason | MessageHeader.reason | Equivalent | R5 `MessageHeader.reason` maps as Equivalent to R4B `MessageHeader.reason` |
| MessageHeader.response | MessageHeader.response | Equivalent | R5 `MessageHeader.response` maps as Equivalent to R4B `MessageHeader.response` |
| MessageHeader.response.code | MessageHeader.response.code | Equivalent | R5 `MessageHeader.response.code` maps as Equivalent to R4B `MessageHeader.response.code` - code has compatible required binding for code type: http://hl7.org/fhir/ValueSet/response-code|5.0.0 and http://hl7.org/fhir/ValueSet/response-code|4.3.0 (Equivalent) |
| MessageHeader.response.details | MessageHeader.response.details | Equivalent | R5 `MessageHeader.response.details` maps as Equivalent to R4B `MessageHeader.response.details` |
| MessageHeader.response.extension | MessageHeader.response.extension | SourceIsBroaderThanTarget | R5 `MessageHeader.response.extension` maps as SourceIsBroaderThanTarget to R4B `MessageHeader.response.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| MessageHeader.response.id | MessageHeader.response.id | Equivalent | R5 `MessageHeader.response.id` maps as Equivalent to R4B `MessageHeader.response.id` |
| MessageHeader.response.identifier | MessageHeader.response.identifier | SourceIsBroaderThanTarget | R5 `MessageHeader.response.identifier` maps as SourceIsBroaderThanTarget to R4B `MessageHeader.response.identifier` - identifier has change due to type change: R5 identifier Identifier has no equivalent or mapped type in R4B identifier |
| MessageHeader.response.modifierExtension | MessageHeader.response.modifierExtension | SourceIsBroaderThanTarget | R5 `MessageHeader.response.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `MessageHeader.response.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| MessageHeader.responsible | MessageHeader.responsible | Equivalent | R5 `MessageHeader.responsible` maps as Equivalent to R4B `MessageHeader.responsible` |
| MessageHeader.sender | MessageHeader.sender | SourceIsBroaderThanTarget | R5 `MessageHeader.sender` maps as SourceIsBroaderThanTarget to R4B `MessageHeader.sender` - sender has change due to type change: R5 `sender` `Reference` maps as SourceIsBroaderThanTarget for R4B `sender` |
| MessageHeader.source | MessageHeader.source | Equivalent | R5 `MessageHeader.source` maps as Equivalent to R4B `MessageHeader.source` |
| MessageHeader.source.contact | MessageHeader.source.contact | Equivalent | R5 `MessageHeader.source.contact` maps as Equivalent to R4B `MessageHeader.source.contact` |
| MessageHeader.source.endpoint[x] | - | DoesNotExistInTarget | R5 `MessageHeader.source.endpoint[x]` does not appear in the target and has no mapping for `MessageHeader`. |
| MessageHeader.source.extension | MessageHeader.source.extension | SourceIsBroaderThanTarget | R5 `MessageHeader.source.extension` maps as SourceIsBroaderThanTarget to R4B `MessageHeader.source.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| MessageHeader.source.id | MessageHeader.source.id | Equivalent | R5 `MessageHeader.source.id` maps as Equivalent to R4B `MessageHeader.source.id` |
| MessageHeader.source.modifierExtension | MessageHeader.source.modifierExtension | SourceIsBroaderThanTarget | R5 `MessageHeader.source.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `MessageHeader.source.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| MessageHeader.source.name | MessageHeader.source.name | Equivalent | R5 `MessageHeader.source.name` maps as Equivalent to R4B `MessageHeader.source.name` |
| MessageHeader.source.software | MessageHeader.source.software | Equivalent | R5 `MessageHeader.source.software` maps as Equivalent to R4B `MessageHeader.source.software` |
| MessageHeader.source.version | MessageHeader.source.version | Equivalent | R5 `MessageHeader.source.version` maps as Equivalent to R4B `MessageHeader.source.version` |
| MessageHeader.text | MessageHeader.text | Equivalent | R5 `MessageHeader.text` maps as Equivalent to R4B `MessageHeader.text` |

