Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | SubscriptionStatus |  | The SubscriptionStatus resource describes the state of a Subscription during notifications. It is not persisted. | 23 | 12 |
| Target | SubscriptionStatus |  | The SubscriptionStatus resource describes the state of a Subscription during notifications. | 23 | 12 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 19 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| SubscriptionStatus | SubscriptionStatus | Equivalent | R5 `SubscriptionStatus` maps as Equivalent to R4B `SubscriptionStatus` |
| SubscriptionStatus.contained | SubscriptionStatus.contained | Equivalent | R5 `SubscriptionStatus.contained` maps as Equivalent to R4B `SubscriptionStatus.contained` |
| SubscriptionStatus.error | SubscriptionStatus.error | Equivalent | R5 `SubscriptionStatus.error` maps as Equivalent to R4B `SubscriptionStatus.error` |
| SubscriptionStatus.eventsSinceSubscriptionStart | SubscriptionStatus.eventsSinceSubscriptionStart | SourceIsBroaderThanTarget | R5 `SubscriptionStatus.eventsSinceSubscriptionStart` maps as SourceIsBroaderThanTarget to R4B `SubscriptionStatus.eventsSinceSubscriptionStart` - eventsSinceSubscriptionStart has change due to type change: R5 eventsSinceSubscriptionStart integer64 has no equivalent or mapped type in R4B eventsSinceSubscriptionStart |
| SubscriptionStatus.extension | SubscriptionStatus.extension | SourceIsBroaderThanTarget | R5 `SubscriptionStatus.extension` maps as SourceIsBroaderThanTarget to R4B `SubscriptionStatus.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| SubscriptionStatus.id | SubscriptionStatus.id | Equivalent | R5 `SubscriptionStatus.id` maps as Equivalent to R4B `SubscriptionStatus.id` |
| SubscriptionStatus.implicitRules | SubscriptionStatus.implicitRules | Equivalent | R5 `SubscriptionStatus.implicitRules` maps as Equivalent to R4B `SubscriptionStatus.implicitRules` |
| SubscriptionStatus.language | SubscriptionStatus.language | RelatedTo | R5 `SubscriptionStatus.language` maps as RelatedTo to R4B `SubscriptionStatus.language` - language changed the binding strength from Required to Preferred |
| SubscriptionStatus.meta | SubscriptionStatus.meta | Equivalent | R5 `SubscriptionStatus.meta` maps as Equivalent to R4B `SubscriptionStatus.meta` |
| SubscriptionStatus.modifierExtension | SubscriptionStatus.modifierExtension | SourceIsBroaderThanTarget | R5 `SubscriptionStatus.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `SubscriptionStatus.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| SubscriptionStatus.notificationEvent | SubscriptionStatus.notificationEvent | Equivalent | R5 `SubscriptionStatus.notificationEvent` maps as Equivalent to R4B `SubscriptionStatus.notificationEvent` |
| SubscriptionStatus.notificationEvent.additionalContext | SubscriptionStatus.notificationEvent.additionalContext | Equivalent | R5 `SubscriptionStatus.notificationEvent.additionalContext` maps as Equivalent to R4B `SubscriptionStatus.notificationEvent.additionalContext` |
| SubscriptionStatus.notificationEvent.eventNumber | SubscriptionStatus.notificationEvent.eventNumber | SourceIsBroaderThanTarget | R5 `SubscriptionStatus.notificationEvent.eventNumber` maps as SourceIsBroaderThanTarget to R4B `SubscriptionStatus.notificationEvent.eventNumber` - eventNumber has change due to type change: R5 eventNumber integer64 has no equivalent or mapped type in R4B eventNumber |
| SubscriptionStatus.notificationEvent.extension | SubscriptionStatus.notificationEvent.extension | SourceIsBroaderThanTarget | R5 `SubscriptionStatus.notificationEvent.extension` maps as SourceIsBroaderThanTarget to R4B `SubscriptionStatus.notificationEvent.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| SubscriptionStatus.notificationEvent.focus | SubscriptionStatus.notificationEvent.focus | Equivalent | R5 `SubscriptionStatus.notificationEvent.focus` maps as Equivalent to R4B `SubscriptionStatus.notificationEvent.focus` |
| SubscriptionStatus.notificationEvent.id | SubscriptionStatus.notificationEvent.id | Equivalent | R5 `SubscriptionStatus.notificationEvent.id` maps as Equivalent to R4B `SubscriptionStatus.notificationEvent.id` |
| SubscriptionStatus.notificationEvent.modifierExtension | SubscriptionStatus.notificationEvent.modifierExtension | SourceIsBroaderThanTarget | R5 `SubscriptionStatus.notificationEvent.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `SubscriptionStatus.notificationEvent.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| SubscriptionStatus.notificationEvent.timestamp | SubscriptionStatus.notificationEvent.timestamp | Equivalent | R5 `SubscriptionStatus.notificationEvent.timestamp` maps as Equivalent to R4B `SubscriptionStatus.notificationEvent.timestamp` |
| SubscriptionStatus.status | SubscriptionStatus.status | Equivalent | R5 `SubscriptionStatus.status` maps as Equivalent to R4B `SubscriptionStatus.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/subscription-status|5.0.0 and http://hl7.org/fhir/ValueSet/subscription-status|4.3.0 (Equivalent) |
| SubscriptionStatus.subscription | SubscriptionStatus.subscription | Equivalent | R5 `SubscriptionStatus.subscription` maps as Equivalent to R4B `SubscriptionStatus.subscription` |
| SubscriptionStatus.text | SubscriptionStatus.text | Equivalent | R5 `SubscriptionStatus.text` maps as Equivalent to R4B `SubscriptionStatus.text` |
| SubscriptionStatus.topic | SubscriptionStatus.topic | Equivalent | R5 `SubscriptionStatus.topic` maps as Equivalent to R4B `SubscriptionStatus.topic` |
| SubscriptionStatus.type | SubscriptionStatus.type | Equivalent | R5 `SubscriptionStatus.type` maps as Equivalent to R4B `SubscriptionStatus.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/subscription-notification-type|5.0.0 and http://hl7.org/fhir/ValueSet/subscription-notification-type|4.3.0 (Equivalent) |

