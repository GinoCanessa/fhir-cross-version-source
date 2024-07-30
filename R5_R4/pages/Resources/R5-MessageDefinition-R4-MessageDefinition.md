Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | MessageDefinition |  | Defines the characteristics of a message that can be shared between systems, including the type of event that initiates the message, the content to be transmitted and what response(s), if any, are permitted. | 47 | 33 |
| Target | MessageDefinition |  | Defines the characteristics of a message that can be shared between systems, including the type of event that initiates the message, the content to be transmitted and what response(s), if any, are permitted. | 45 | 31 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 2 |
Equivalent | 4 |
RelatedTo | 41 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| MessageDefinition | MessageDefinition | Equivalent | R5 `MessageDefinition` maps as Equivalent to R4 `MessageDefinition` |
| MessageDefinition.allowedResponse | MessageDefinition.allowedResponse | Equivalent | R5 `MessageDefinition.allowedResponse` maps as Equivalent to R4 `MessageDefinition.allowedResponse` |
| MessageDefinition.allowedResponse.extension | MessageDefinition.allowedResponse.extension | SourceIsBroaderThanTarget | R5 `MessageDefinition.allowedResponse.extension` maps as SourceIsBroaderThanTarget to R4 `MessageDefinition.allowedResponse.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| MessageDefinition.allowedResponse.id | MessageDefinition.allowedResponse.id | Equivalent | R5 `MessageDefinition.allowedResponse.id` maps as Equivalent to R4 `MessageDefinition.allowedResponse.id` |
| MessageDefinition.allowedResponse.message | MessageDefinition.allowedResponse.message | Equivalent | R5 `MessageDefinition.allowedResponse.message` maps as Equivalent to R4 `MessageDefinition.allowedResponse.message` |
| MessageDefinition.allowedResponse.modifierExtension | MessageDefinition.allowedResponse.modifierExtension | SourceIsBroaderThanTarget | R5 `MessageDefinition.allowedResponse.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `MessageDefinition.allowedResponse.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| MessageDefinition.allowedResponse.situation | MessageDefinition.allowedResponse.situation | Equivalent | R5 `MessageDefinition.allowedResponse.situation` maps as Equivalent to R4 `MessageDefinition.allowedResponse.situation` |
| MessageDefinition.base | MessageDefinition.base | Equivalent | R5 `MessageDefinition.base` maps as Equivalent to R4 `MessageDefinition.base` |
| MessageDefinition.category | MessageDefinition.category | Equivalent | R5 `MessageDefinition.category` maps as Equivalent to R4 `MessageDefinition.category` - category has compatible required binding for code type: http://hl7.org/fhir/ValueSet/message-significance-category|5.0.0 and http://hl7.org/fhir/ValueSet/message-significance-category|4.0.1 (Equivalent) |
| MessageDefinition.contact | MessageDefinition.contact | Equivalent | R5 `MessageDefinition.contact` maps as Equivalent to R4 `MessageDefinition.contact` |
| MessageDefinition.contained | MessageDefinition.contained | Equivalent | R5 `MessageDefinition.contained` maps as Equivalent to R4 `MessageDefinition.contained` |
| MessageDefinition.copyright | MessageDefinition.copyright | Equivalent | R5 `MessageDefinition.copyright` maps as Equivalent to R4 `MessageDefinition.copyright` |
| MessageDefinition.copyrightLabel | - | DoesNotExistInTarget | R5 `MessageDefinition.copyrightLabel` does not appear in the target and has no mapping for `MessageDefinition`. |
| MessageDefinition.date | MessageDefinition.date | Equivalent | R5 `MessageDefinition.date` maps as Equivalent to R4 `MessageDefinition.date` |
| MessageDefinition.description | MessageDefinition.description | Equivalent | R5 `MessageDefinition.description` maps as Equivalent to R4 `MessageDefinition.description` |
| MessageDefinition.event[x] | MessageDefinition.event[x] | Equivalent | R5 `MessageDefinition.event[x]` maps as Equivalent to R4 `MessageDefinition.event[x]` |
| MessageDefinition.experimental | MessageDefinition.experimental | Equivalent | R5 `MessageDefinition.experimental` maps as Equivalent to R4 `MessageDefinition.experimental` |
| MessageDefinition.extension | MessageDefinition.extension | SourceIsBroaderThanTarget | R5 `MessageDefinition.extension` maps as SourceIsBroaderThanTarget to R4 `MessageDefinition.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| MessageDefinition.focus | MessageDefinition.focus | Equivalent | R5 `MessageDefinition.focus` maps as Equivalent to R4 `MessageDefinition.focus` |
| MessageDefinition.focus.code | MessageDefinition.focus.code | Equivalent | R5 `MessageDefinition.focus.code` maps as Equivalent to R4 `MessageDefinition.focus.code` - code has compatible required binding for code type: http://hl7.org/fhir/ValueSet/resource-types|5.0.0 and http://hl7.org/fhir/ValueSet/resource-types|4.0.1 (Equivalent) |
| MessageDefinition.focus.extension | MessageDefinition.focus.extension | SourceIsBroaderThanTarget | R5 `MessageDefinition.focus.extension` maps as SourceIsBroaderThanTarget to R4 `MessageDefinition.focus.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| MessageDefinition.focus.id | MessageDefinition.focus.id | Equivalent | R5 `MessageDefinition.focus.id` maps as Equivalent to R4 `MessageDefinition.focus.id` |
| MessageDefinition.focus.max | MessageDefinition.focus.max | Equivalent | R5 `MessageDefinition.focus.max` maps as Equivalent to R4 `MessageDefinition.focus.max` |
| MessageDefinition.focus.min | MessageDefinition.focus.min | Equivalent | R5 `MessageDefinition.focus.min` maps as Equivalent to R4 `MessageDefinition.focus.min` |
| MessageDefinition.focus.modifierExtension | MessageDefinition.focus.modifierExtension | SourceIsBroaderThanTarget | R5 `MessageDefinition.focus.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `MessageDefinition.focus.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| MessageDefinition.focus.profile | MessageDefinition.focus.profile | Equivalent | R5 `MessageDefinition.focus.profile` maps as Equivalent to R4 `MessageDefinition.focus.profile` |
| MessageDefinition.graph | MessageDefinition.graph | RelatedTo | R5 `MessageDefinition.graph` maps as RelatedTo to R4 `MessageDefinition.graph` - graph changed from scalar to array (max cardinality from 1 to *) |
| MessageDefinition.id | MessageDefinition.id | Equivalent | R5 `MessageDefinition.id` maps as Equivalent to R4 `MessageDefinition.id` |
| MessageDefinition.identifier | MessageDefinition.identifier | Equivalent | R5 `MessageDefinition.identifier` maps as Equivalent to R4 `MessageDefinition.identifier` |
| MessageDefinition.implicitRules | MessageDefinition.implicitRules | Equivalent | R5 `MessageDefinition.implicitRules` maps as Equivalent to R4 `MessageDefinition.implicitRules` |
| MessageDefinition.jurisdiction | MessageDefinition.jurisdiction | Equivalent | R5 `MessageDefinition.jurisdiction` maps as Equivalent to R4 `MessageDefinition.jurisdiction` |
| MessageDefinition.language | MessageDefinition.language | RelatedTo | R5 `MessageDefinition.language` maps as RelatedTo to R4 `MessageDefinition.language` - language changed the binding strength from Required to Preferred |
| MessageDefinition.meta | MessageDefinition.meta | Equivalent | R5 `MessageDefinition.meta` maps as Equivalent to R4 `MessageDefinition.meta` |
| MessageDefinition.modifierExtension | MessageDefinition.modifierExtension | SourceIsBroaderThanTarget | R5 `MessageDefinition.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `MessageDefinition.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| MessageDefinition.name | MessageDefinition.name | Equivalent | R5 `MessageDefinition.name` maps as Equivalent to R4 `MessageDefinition.name` |
| MessageDefinition.parent | MessageDefinition.parent | Equivalent | R5 `MessageDefinition.parent` maps as Equivalent to R4 `MessageDefinition.parent` |
| MessageDefinition.publisher | MessageDefinition.publisher | Equivalent | R5 `MessageDefinition.publisher` maps as Equivalent to R4 `MessageDefinition.publisher` |
| MessageDefinition.purpose | MessageDefinition.purpose | Equivalent | R5 `MessageDefinition.purpose` maps as Equivalent to R4 `MessageDefinition.purpose` |
| MessageDefinition.replaces | MessageDefinition.replaces | Equivalent | R5 `MessageDefinition.replaces` maps as Equivalent to R4 `MessageDefinition.replaces` |
| MessageDefinition.responseRequired | MessageDefinition.responseRequired | Equivalent | R5 `MessageDefinition.responseRequired` maps as Equivalent to R4 `MessageDefinition.responseRequired` - responseRequired has compatible required binding for code type: http://hl7.org/fhir/ValueSet/messageheader-response-request|5.0.0 and http://hl7.org/fhir/ValueSet/messageheader-response-request|4.0.1 (Equivalent) |
| MessageDefinition.status | MessageDefinition.status | Equivalent | R5 `MessageDefinition.status` maps as Equivalent to R4 `MessageDefinition.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.0.1 (Equivalent) |
| MessageDefinition.text | MessageDefinition.text | Equivalent | R5 `MessageDefinition.text` maps as Equivalent to R4 `MessageDefinition.text` |
| MessageDefinition.title | MessageDefinition.title | Equivalent | R5 `MessageDefinition.title` maps as Equivalent to R4 `MessageDefinition.title` |
| MessageDefinition.url | MessageDefinition.url | Equivalent | R5 `MessageDefinition.url` maps as Equivalent to R4 `MessageDefinition.url` |
| MessageDefinition.useContext | MessageDefinition.useContext | Equivalent | R5 `MessageDefinition.useContext` maps as Equivalent to R4 `MessageDefinition.useContext` |
| MessageDefinition.version | MessageDefinition.version | Equivalent | R5 `MessageDefinition.version` maps as Equivalent to R4 `MessageDefinition.version` |
| MessageDefinition.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `MessageDefinition.versionAlgorithm[x]` does not appear in the target and has no mapping for `MessageDefinition`. |

