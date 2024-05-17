Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | SubscriptionStatus |  | The SubscriptionStatus resource describes the state of a Subscription during notifications. | 23 | 12 |
| Target | SubscriptionStatus |  | The SubscriptionStatus resource describes the state of a Subscription during notifications. It is not persisted. | 23 | 12 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 19 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| SubscriptionStatus | SubscriptionStatus | Equivalent | R4B `SubscriptionStatus` maps as Equivalent to R5 `SubscriptionStatus` |
| SubscriptionStatus.contained | SubscriptionStatus.contained | Equivalent | R4B `SubscriptionStatus.contained` maps as Equivalent to R5 `SubscriptionStatus.contained` |
| SubscriptionStatus.error | SubscriptionStatus.error | Equivalent | R4B `SubscriptionStatus.error` maps as Equivalent to R5 `SubscriptionStatus.error` |
| SubscriptionStatus.eventsSinceSubscriptionStart | SubscriptionStatus.eventsSinceSubscriptionStart | SourceIsBroaderThanTarget | R4B `SubscriptionStatus.eventsSinceSubscriptionStart` maps as SourceIsBroaderThanTarget to R5 `SubscriptionStatus.eventsSinceSubscriptionStart` - eventsSinceSubscriptionStart has change due to type change: R4B eventsSinceSubscriptionStart string has no equivalent or mapped type in R5 eventsSinceSubscriptionStart |
| SubscriptionStatus.extension | SubscriptionStatus.extension | RelatedTo | R4B `SubscriptionStatus.extension` maps as RelatedTo to R5 `SubscriptionStatus.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| SubscriptionStatus.id | SubscriptionStatus.id | Equivalent | R4B `SubscriptionStatus.id` maps as Equivalent to R5 `SubscriptionStatus.id` |
| SubscriptionStatus.implicitRules | SubscriptionStatus.implicitRules | Equivalent | R4B `SubscriptionStatus.implicitRules` maps as Equivalent to R5 `SubscriptionStatus.implicitRules` |
| SubscriptionStatus.language | SubscriptionStatus.language | RelatedTo | R4B `SubscriptionStatus.language` maps as RelatedTo to R5 `SubscriptionStatus.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| SubscriptionStatus.meta | SubscriptionStatus.meta | Equivalent | R4B `SubscriptionStatus.meta` maps as Equivalent to R5 `SubscriptionStatus.meta` |
| SubscriptionStatus.modifierExtension | SubscriptionStatus.modifierExtension | RelatedTo | R4B `SubscriptionStatus.modifierExtension` maps as RelatedTo to R5 `SubscriptionStatus.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| SubscriptionStatus.notificationEvent | SubscriptionStatus.notificationEvent | Equivalent | R4B `SubscriptionStatus.notificationEvent` maps as Equivalent to R5 `SubscriptionStatus.notificationEvent` |
| SubscriptionStatus.notificationEvent.additionalContext | SubscriptionStatus.notificationEvent.additionalContext | Equivalent | R4B `SubscriptionStatus.notificationEvent.additionalContext` maps as Equivalent to R5 `SubscriptionStatus.notificationEvent.additionalContext` |
| SubscriptionStatus.notificationEvent.eventNumber | SubscriptionStatus.notificationEvent.eventNumber | SourceIsBroaderThanTarget | R4B `SubscriptionStatus.notificationEvent.eventNumber` maps as SourceIsBroaderThanTarget to R5 `SubscriptionStatus.notificationEvent.eventNumber` - eventNumber has change due to type change: R4B eventNumber string has no equivalent or mapped type in R5 eventNumber |
| SubscriptionStatus.notificationEvent.extension | SubscriptionStatus.notificationEvent.extension | RelatedTo | R4B `SubscriptionStatus.notificationEvent.extension` maps as RelatedTo to R5 `SubscriptionStatus.notificationEvent.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| SubscriptionStatus.notificationEvent.focus | SubscriptionStatus.notificationEvent.focus | Equivalent | R4B `SubscriptionStatus.notificationEvent.focus` maps as Equivalent to R5 `SubscriptionStatus.notificationEvent.focus` |
| SubscriptionStatus.notificationEvent.id | SubscriptionStatus.notificationEvent.id | Equivalent | R4B `SubscriptionStatus.notificationEvent.id` maps as Equivalent to R5 `SubscriptionStatus.notificationEvent.id` |
| SubscriptionStatus.notificationEvent.modifierExtension | SubscriptionStatus.notificationEvent.modifierExtension | RelatedTo | R4B `SubscriptionStatus.notificationEvent.modifierExtension` maps as RelatedTo to R5 `SubscriptionStatus.notificationEvent.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| SubscriptionStatus.notificationEvent.timestamp | SubscriptionStatus.notificationEvent.timestamp | Equivalent | R4B `SubscriptionStatus.notificationEvent.timestamp` maps as Equivalent to R5 `SubscriptionStatus.notificationEvent.timestamp` |
| SubscriptionStatus.status | SubscriptionStatus.status | Equivalent | R4B `SubscriptionStatus.status` maps as Equivalent to R5 `SubscriptionStatus.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/subscription-status|4.3.0 and http://hl7.org/fhir/ValueSet/subscription-status|5.0.0 (Equivalent) |
| SubscriptionStatus.subscription | SubscriptionStatus.subscription | Equivalent | R4B `SubscriptionStatus.subscription` maps as Equivalent to R5 `SubscriptionStatus.subscription` |
| SubscriptionStatus.text | SubscriptionStatus.text | Equivalent | R4B `SubscriptionStatus.text` maps as Equivalent to R5 `SubscriptionStatus.text` |
| SubscriptionStatus.topic | SubscriptionStatus.topic | Equivalent | R4B `SubscriptionStatus.topic` maps as Equivalent to R5 `SubscriptionStatus.topic` |
| SubscriptionStatus.type | SubscriptionStatus.type | Equivalent | R4B `SubscriptionStatus.type` maps as Equivalent to R5 `SubscriptionStatus.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/subscription-notification-type|4.3.0 and http://hl7.org/fhir/ValueSet/subscription-notification-type|5.0.0 (Equivalent) |

