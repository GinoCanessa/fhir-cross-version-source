Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Subscription |  | The subscription resource is used to define a push-based subscription from a server to another system. Once a subscription is registered with the server, the server checks every resource that is created or updated, and if the resource matches the given criteria, it sends a message on the defined "channel" so that another system can take an appropriate action. | 23 | 12 |
| Target | Subscription |  | The subscription resource describes a particular client's request to be notified about a SubscriptionTopic. | 39 | 25 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 10 |
Equivalent | 4 |
RelatedTo | 9 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Subscription | Subscription | Equivalent | R4B `Subscription` maps as Equivalent to R5 `Subscription` |
| Subscription.channel | - | DoesNotExistInTarget | R4B `Subscription.channel` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.channel.endpoint | - | DoesNotExistInTarget | R4B `Subscription.channel.endpoint` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.channel.extension | - | DoesNotExistInTarget | R4B `Subscription.channel.extension` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.channel.header | - | DoesNotExistInTarget | R4B `Subscription.channel.header` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.channel.id | - | DoesNotExistInTarget | R4B `Subscription.channel.id` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.channel.modifierExtension | - | DoesNotExistInTarget | R4B `Subscription.channel.modifierExtension` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.channel.payload | - | DoesNotExistInTarget | R4B `Subscription.channel.payload` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.channel.type | - | DoesNotExistInTarget | R4B `Subscription.channel.type` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.contact | Subscription.contact | Equivalent | R4B `Subscription.contact` maps as Equivalent to R5 `Subscription.contact` |
| Subscription.contained | Subscription.contained | Equivalent | R4B `Subscription.contained` maps as Equivalent to R5 `Subscription.contained` |
| Subscription.criteria | - | DoesNotExistInTarget | R4B `Subscription.criteria` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.end | Subscription.end | Equivalent | R4B `Subscription.end` maps as Equivalent to R5 `Subscription.end` |
| Subscription.error | - | DoesNotExistInTarget | R4B `Subscription.error` does not appear in the target and has no mapping for `Subscription`. |
| Subscription.extension | Subscription.extension | RelatedTo | R4B `Subscription.extension` maps as RelatedTo to R5 `Subscription.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Subscription.id | Subscription.id | Equivalent | R4B `Subscription.id` maps as Equivalent to R5 `Subscription.id` |
| Subscription.implicitRules | Subscription.implicitRules | Equivalent | R4B `Subscription.implicitRules` maps as Equivalent to R5 `Subscription.implicitRules` |
| Subscription.language | Subscription.language | RelatedTo | R4B `Subscription.language` maps as RelatedTo to R5 `Subscription.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Subscription.meta | Subscription.meta | Equivalent | R4B `Subscription.meta` maps as Equivalent to R5 `Subscription.meta` |
| Subscription.modifierExtension | Subscription.modifierExtension | RelatedTo | R4B `Subscription.modifierExtension` maps as RelatedTo to R5 `Subscription.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Subscription.reason | Subscription.reason | Equivalent | R4B `Subscription.reason` maps as Equivalent to R5 `Subscription.reason` |
| Subscription.status | Subscription.status | Equivalent | R4B `Subscription.status` maps as Equivalent to R5 `Subscription.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/subscription-status|4.3.0 and http://hl7.org/fhir/ValueSet/subscription-status|5.0.0 (Equivalent) |
| Subscription.text | Subscription.text | Equivalent | R4B `Subscription.text` maps as Equivalent to R5 `Subscription.text` |

