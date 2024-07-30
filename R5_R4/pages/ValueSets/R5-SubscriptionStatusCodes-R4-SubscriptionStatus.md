Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Url | Name | Title | Description |
| --- | --- | --- | --- | --- |
| Source | http://hl7.org/fhir/ValueSet/subscription-status | SubscriptionStatusCodes | Subscription Status | State values for FHIR Subscriptions. |
| Target | http://hl7.org/fhir/ValueSet/subscription-status | SubscriptionStatus | SubscriptionStatus | The status of a subscription. |


Comparison Result: Equivalent


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 4 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| active | active | Equivalent | R5 `active` is equivalent to R4 `active`. |
| entered-in-error | - | DoesNotExistInTarget | R5 `entered-in-error` does not appear in the target and has no mapping for http://hl7.org/fhir/ValueSet/subscription-status. |
| error | error | Equivalent | R5 `error` is equivalent to R4 `error`. |
| off | off | Equivalent | R5 `off` is equivalent to R4 `off`. |
| requested | requested | Equivalent | R5 `requested` is equivalent to R4 `requested`. |

