Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Subscription |  | The subscription resource describes a particular client's request to be notified about a SubscriptionTopic. | 39 | 25 |
| Target | Subscription |  | The subscription resource is used to define a push-based subscription from a server to another system. Once a subscription is registered with the server, the server checks every resource that is created or updated, and if the resource matches the given criteria, it sends a message on the defined "channel" so that another system can take an appropriate action. | 23 | 12 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 23 |
Equivalent | 11 |
RelatedTo | 2 |
SourceIsBroaderThanTarget | 2 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Subscription | Subscription | Equivalent | R5 `Subscription` maps as Equivalent to R4 `Subscription` |
| Subscription.channelType | Subscription.channel.type | RelatedTo | R5 `Subscription.channelType` maps as RelatedTo to R4 `Subscription.channel.type` - type made the binding required (from Extensible) for http://hl7.org/fhir/ValueSet/subscription-channel-type|4.0.1; type has change due to type change: R5 channelType Coding has no equivalent or mapped type in R4 type |
| Subscription.contact | Subscription.contact | Equivalent | R5 `Subscription.contact` maps as Equivalent to R4 `Subscription.contact` |
| Subscription.contained | Subscription.contained | Equivalent | R5 `Subscription.contained` maps as Equivalent to R4 `Subscription.contained` |
| Subscription.content | - | DoesNotExistInTarget | R5 `Subscription.content` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.contentType | Subscription.channel.payload | Equivalent | R5 `Subscription.contentType` maps as Equivalent to R4 `Subscription.channel.payload` - payload using http://hl7.org/fhir/ValueSet/mimetypes is exempted and assumed equivalent |
| Subscription.end | Subscription.end | Equivalent | R5 `Subscription.end` maps as Equivalent to R4 `Subscription.end` |
| Subscription.endpoint | Subscription.channel.endpoint | Equivalent | R5 `Subscription.endpoint` maps as Equivalent to R4 `Subscription.channel.endpoint` |
| Subscription.extension | Subscription.extension | SourceIsBroaderThanTarget | R5 `Subscription.extension` maps as SourceIsBroaderThanTarget to R4 `Subscription.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Subscription.filterBy | - | DoesNotExistInTarget | R5 `Subscription.filterBy` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.filterBy.comparator | - | DoesNotExistInTarget | R5 `Subscription.filterBy.comparator` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.filterBy.extension | - | DoesNotExistInTarget | R5 `Subscription.filterBy.extension` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.filterBy.filterParameter | - | DoesNotExistInTarget | R5 `Subscription.filterBy.filterParameter` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.filterBy.id | - | DoesNotExistInTarget | R5 `Subscription.filterBy.id` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.filterBy.modifier | - | DoesNotExistInTarget | R5 `Subscription.filterBy.modifier` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.filterBy.modifierExtension | - | DoesNotExistInTarget | R5 `Subscription.filterBy.modifierExtension` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.filterBy.resourceType | - | DoesNotExistInTarget | R5 `Subscription.filterBy.resourceType` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.filterBy.value | - | DoesNotExistInTarget | R5 `Subscription.filterBy.value` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.heartbeatPeriod | - | DoesNotExistInTarget | R5 `Subscription.heartbeatPeriod` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.id | Subscription.id | Equivalent | R5 `Subscription.id` maps as Equivalent to R4 `Subscription.id` |
| Subscription.identifier | - | DoesNotExistInTarget | R5 `Subscription.identifier` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.implicitRules | Subscription.implicitRules | Equivalent | R5 `Subscription.implicitRules` maps as Equivalent to R4 `Subscription.implicitRules` |
| Subscription.language | Subscription.language | SourceIsNarrowerThanTarget | R5 `Subscription.language` maps as SourceIsNarrowerThanTarget to R4 `Subscription.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| Subscription.managingEntity | - | DoesNotExistInTarget | R5 `Subscription.managingEntity` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.maxCount | - | DoesNotExistInTarget | R5 `Subscription.maxCount` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.meta | Subscription.meta | Equivalent | R5 `Subscription.meta` maps as Equivalent to R4 `Subscription.meta` |
| Subscription.modifierExtension | Subscription.modifierExtension | SourceIsBroaderThanTarget | R5 `Subscription.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Subscription.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Subscription.name | - | DoesNotExistInTarget | R5 `Subscription.name` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.parameter | - | DoesNotExistInTarget | R5 `Subscription.parameter` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.parameter.extension | - | DoesNotExistInTarget | R5 `Subscription.parameter.extension` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.parameter.id | - | DoesNotExistInTarget | R5 `Subscription.parameter.id` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.parameter.modifierExtension | - | DoesNotExistInTarget | R5 `Subscription.parameter.modifierExtension` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.parameter.name | - | DoesNotExistInTarget | R5 `Subscription.parameter.name` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.parameter.value | - | DoesNotExistInTarget | R5 `Subscription.parameter.value` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.reason | Subscription.reason | RelatedTo | R5 `Subscription.reason` maps as RelatedTo to R4 `Subscription.reason` - reason made the element mandatory; reason increased the minimum cardinality from 0 to 1 |
| Subscription.status | Subscription.status | Equivalent | R5 `Subscription.status` maps as Equivalent to R4 `Subscription.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/subscription-status|5.0.0 and http://hl7.org/fhir/ValueSet/subscription-status|4.0.1 (Equivalent) |
| Subscription.text | Subscription.text | Equivalent | R5 `Subscription.text` maps as Equivalent to R4 `Subscription.text` |
| Subscription.timeout | - | DoesNotExistInTarget | R5 `Subscription.timeout` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.topic | - | DoesNotExistInTarget | R5 `Subscription.topic` does not appear in the target and has no mapping for `Subscription`. |

