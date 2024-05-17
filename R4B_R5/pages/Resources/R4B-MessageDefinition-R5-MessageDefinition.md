Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | MessageDefinition |  | Defines the characteristics of a message that can be shared between systems, including the type of event that initiates the message, the content to be transmitted and what response(s), if any, are permitted. | 45 | 31 |
| Target | MessageDefinition |  | Defines the characteristics of a message that can be shared between systems, including the type of event that initiates the message, the content to be transmitted and what response(s), if any, are permitted. | 47 | 33 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 41 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| MessageDefinition | MessageDefinition | Equivalent | R4B `MessageDefinition` maps as Equivalent to R5 `MessageDefinition` |
| MessageDefinition.allowedResponse | MessageDefinition.allowedResponse | Equivalent | R4B `MessageDefinition.allowedResponse` maps as Equivalent to R5 `MessageDefinition.allowedResponse` |
| MessageDefinition.allowedResponse.extension | MessageDefinition.allowedResponse.extension | RelatedTo | R4B `MessageDefinition.allowedResponse.extension` maps as RelatedTo to R5 `MessageDefinition.allowedResponse.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MessageDefinition.allowedResponse.id | MessageDefinition.allowedResponse.id | Equivalent | R4B `MessageDefinition.allowedResponse.id` maps as Equivalent to R5 `MessageDefinition.allowedResponse.id` |
| MessageDefinition.allowedResponse.message | MessageDefinition.allowedResponse.message | Equivalent | R4B `MessageDefinition.allowedResponse.message` maps as Equivalent to R5 `MessageDefinition.allowedResponse.message` |
| MessageDefinition.allowedResponse.modifierExtension | MessageDefinition.allowedResponse.modifierExtension | RelatedTo | R4B `MessageDefinition.allowedResponse.modifierExtension` maps as RelatedTo to R5 `MessageDefinition.allowedResponse.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MessageDefinition.allowedResponse.situation | MessageDefinition.allowedResponse.situation | Equivalent | R4B `MessageDefinition.allowedResponse.situation` maps as Equivalent to R5 `MessageDefinition.allowedResponse.situation` |
| MessageDefinition.base | MessageDefinition.base | Equivalent | R4B `MessageDefinition.base` maps as Equivalent to R5 `MessageDefinition.base` |
| MessageDefinition.category | MessageDefinition.category | Equivalent | R4B `MessageDefinition.category` maps as Equivalent to R5 `MessageDefinition.category` - category has compatible required binding for code type: http://hl7.org/fhir/ValueSet/message-significance-category|4.3.0 and http://hl7.org/fhir/ValueSet/message-significance-category|5.0.0 (Equivalent) |
| MessageDefinition.contact | MessageDefinition.contact | Equivalent | R4B `MessageDefinition.contact` maps as Equivalent to R5 `MessageDefinition.contact` |
| MessageDefinition.contained | MessageDefinition.contained | Equivalent | R4B `MessageDefinition.contained` maps as Equivalent to R5 `MessageDefinition.contained` |
| MessageDefinition.copyright | MessageDefinition.copyright | Equivalent | R4B `MessageDefinition.copyright` maps as Equivalent to R5 `MessageDefinition.copyright` |
| MessageDefinition.date | MessageDefinition.date | Equivalent | R4B `MessageDefinition.date` maps as Equivalent to R5 `MessageDefinition.date` |
| MessageDefinition.description | MessageDefinition.description | Equivalent | R4B `MessageDefinition.description` maps as Equivalent to R5 `MessageDefinition.description` |
| MessageDefinition.event[x] | MessageDefinition.event[x] | Equivalent | R4B `MessageDefinition.event[x]` maps as Equivalent to R5 `MessageDefinition.event[x]` |
| MessageDefinition.experimental | MessageDefinition.experimental | Equivalent | R4B `MessageDefinition.experimental` maps as Equivalent to R5 `MessageDefinition.experimental` |
| MessageDefinition.extension | MessageDefinition.extension | RelatedTo | R4B `MessageDefinition.extension` maps as RelatedTo to R5 `MessageDefinition.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MessageDefinition.focus | MessageDefinition.focus | Equivalent | R4B `MessageDefinition.focus` maps as Equivalent to R5 `MessageDefinition.focus` |
| MessageDefinition.focus.code | MessageDefinition.focus.code | Equivalent | R4B `MessageDefinition.focus.code` maps as Equivalent to R5 `MessageDefinition.focus.code` - code has compatible required binding for code type: http://hl7.org/fhir/ValueSet/resource-types|4.3.0 and http://hl7.org/fhir/ValueSet/resource-types|5.0.0 (Equivalent) |
| MessageDefinition.focus.extension | MessageDefinition.focus.extension | RelatedTo | R4B `MessageDefinition.focus.extension` maps as RelatedTo to R5 `MessageDefinition.focus.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| MessageDefinition.focus.id | MessageDefinition.focus.id | Equivalent | R4B `MessageDefinition.focus.id` maps as Equivalent to R5 `MessageDefinition.focus.id` |
| MessageDefinition.focus.max | MessageDefinition.focus.max | Equivalent | R4B `MessageDefinition.focus.max` maps as Equivalent to R5 `MessageDefinition.focus.max` |
| MessageDefinition.focus.min | MessageDefinition.focus.min | Equivalent | R4B `MessageDefinition.focus.min` maps as Equivalent to R5 `MessageDefinition.focus.min` |
| MessageDefinition.focus.modifierExtension | MessageDefinition.focus.modifierExtension | RelatedTo | R4B `MessageDefinition.focus.modifierExtension` maps as RelatedTo to R5 `MessageDefinition.focus.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MessageDefinition.focus.profile | MessageDefinition.focus.profile | Equivalent | R4B `MessageDefinition.focus.profile` maps as Equivalent to R5 `MessageDefinition.focus.profile` |
| MessageDefinition.graph | MessageDefinition.graph | RelatedTo | R4B `MessageDefinition.graph` maps as RelatedTo to R5 `MessageDefinition.graph` - graph changed from array to scalar (max cardinality from * to 1) |
| MessageDefinition.id | MessageDefinition.id | Equivalent | R4B `MessageDefinition.id` maps as Equivalent to R5 `MessageDefinition.id` |
| MessageDefinition.identifier | MessageDefinition.identifier | Equivalent | R4B `MessageDefinition.identifier` maps as Equivalent to R5 `MessageDefinition.identifier` |
| MessageDefinition.implicitRules | MessageDefinition.implicitRules | Equivalent | R4B `MessageDefinition.implicitRules` maps as Equivalent to R5 `MessageDefinition.implicitRules` |
| MessageDefinition.jurisdiction | MessageDefinition.jurisdiction | Equivalent | R4B `MessageDefinition.jurisdiction` maps as Equivalent to R5 `MessageDefinition.jurisdiction` |
| MessageDefinition.language | MessageDefinition.language | RelatedTo | R4B `MessageDefinition.language` maps as RelatedTo to R5 `MessageDefinition.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| MessageDefinition.meta | MessageDefinition.meta | Equivalent | R4B `MessageDefinition.meta` maps as Equivalent to R5 `MessageDefinition.meta` |
| MessageDefinition.modifierExtension | MessageDefinition.modifierExtension | RelatedTo | R4B `MessageDefinition.modifierExtension` maps as RelatedTo to R5 `MessageDefinition.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| MessageDefinition.name | MessageDefinition.name | Equivalent | R4B `MessageDefinition.name` maps as Equivalent to R5 `MessageDefinition.name` |
| MessageDefinition.parent | MessageDefinition.parent | Equivalent | R4B `MessageDefinition.parent` maps as Equivalent to R5 `MessageDefinition.parent` |
| MessageDefinition.publisher | MessageDefinition.publisher | Equivalent | R4B `MessageDefinition.publisher` maps as Equivalent to R5 `MessageDefinition.publisher` |
| MessageDefinition.purpose | MessageDefinition.purpose | Equivalent | R4B `MessageDefinition.purpose` maps as Equivalent to R5 `MessageDefinition.purpose` |
| MessageDefinition.replaces | MessageDefinition.replaces | Equivalent | R4B `MessageDefinition.replaces` maps as Equivalent to R5 `MessageDefinition.replaces` |
| MessageDefinition.responseRequired | MessageDefinition.responseRequired | Equivalent | R4B `MessageDefinition.responseRequired` maps as Equivalent to R5 `MessageDefinition.responseRequired` - responseRequired has compatible required binding for code type: http://hl7.org/fhir/ValueSet/messageheader-response-request|4.3.0 and http://hl7.org/fhir/ValueSet/messageheader-response-request|5.0.0 (Equivalent) |
| MessageDefinition.status | MessageDefinition.status | Equivalent | R4B `MessageDefinition.status` maps as Equivalent to R5 `MessageDefinition.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| MessageDefinition.text | MessageDefinition.text | Equivalent | R4B `MessageDefinition.text` maps as Equivalent to R5 `MessageDefinition.text` |
| MessageDefinition.title | MessageDefinition.title | Equivalent | R4B `MessageDefinition.title` maps as Equivalent to R5 `MessageDefinition.title` |
| MessageDefinition.url | MessageDefinition.url | Equivalent | R4B `MessageDefinition.url` maps as Equivalent to R5 `MessageDefinition.url` |
| MessageDefinition.useContext | MessageDefinition.useContext | Equivalent | R4B `MessageDefinition.useContext` maps as Equivalent to R5 `MessageDefinition.useContext` |
| MessageDefinition.version | MessageDefinition.version | Equivalent | R4B `MessageDefinition.version` maps as Equivalent to R5 `MessageDefinition.version` |

