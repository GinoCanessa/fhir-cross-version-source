Comparison of 
Generated at Monday, April 14, 2025 6:17:43 PM

### SubscriptionNotificationType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | SubscriptionNotificationType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/subscription-notification-type` |
| Version | 5.0.0 |
| Description | The type of notification represented by the status message. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4924` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/SubscriptionStatus` | `SubscriptionStatus.type` | `http://hl7.org/fhir/ValueSet/subscription-notification-type\|5.0.0` | `Required` | handshake \| heartbeat \| event-notification \| query-status \| query-event |

### Referenced Systems

* `http://hl7.org/fhir/subscription-notification-type`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [SubscriptionNotificationType](/docs/R4B/ValueSets/SubscriptionNotificationType.md)<br/> `http://hl7.org/fhir/ValueSet/subscription-notification-type\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `975`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1236`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [SubscriptionNotificationType](/docs/R5/ValueSets/SubscriptionNotificationType.md)<br/> `http://hl7.org/fhir/ValueSet/subscription-notification-type\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set SubscriptionNotificationType from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B SubscriptionNotificationType](/docs/R4B/ValueSets/SubscriptionNotificationType.md)| Relationship | R5 SubscriptionNotificationType
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/subscription-notification-type`
| | | | | | | `handshake`| _Equivalent_ <br/>(9307/11645)| **`handshake`**
| | | | | | | `heartbeat`| _Equivalent_ <br/>(9308/11646)| **`heartbeat`**
| | | | | | | `event-notification`| _Equivalent_ <br/>(9309/11647)| **`event-notification`**
| | | | | | | `query-status`| _Equivalent_ <br/>(9306/11644)| **`query-status`**
| | | | | | | `query-event`| _Equivalent_ <br/>(9310/11648)| **`query-event`**
| | | | | | | *5 of 5 codes used* | | *5 of 5 codes used* 

