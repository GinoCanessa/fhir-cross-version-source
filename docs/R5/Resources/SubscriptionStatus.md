Comparison of 
Generated at Friday, April 4, 2025 2:59:00 PM

### SubscriptionStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | SubscriptionStatus |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/SubscriptionStatus` |
| Version | 5.0.0 |
| Description | The SubscriptionStatus resource describes the state of a Subscription during notifications. It is not persisted. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2388` |
| Database Snapshot Count | `23` |
| Database Differential Count | `12` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `SubscriptionStatus` | `SubscriptionStatus` | `SubscriptionStatus` | SubscriptionStatus | Status information about a Subscription provided during event notification | 0..* | SubscriptionStatus |  |  |
| `SubscriptionStatus.contained` | `SubscriptionStatus.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `SubscriptionStatus.error` | `SubscriptionStatus.error` | `error` | SubscriptionStatus.error | List of errors on the subscription | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/subscription-error` |
| `SubscriptionStatus.eventsSinceSubscriptionStart` | `SubscriptionStatus.eventsSinceSubscriptionStart` | `eventsSinceSubscriptionStart` | SubscriptionStatus.eventsSinceSubscriptionStart | Events since the Subscription was created | 0..1 | integer64 |  |  |
| `SubscriptionStatus.extension` | `SubscriptionStatus.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubscriptionStatus.id` | `SubscriptionStatus.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `SubscriptionStatus.implicitRules` | `SubscriptionStatus.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `SubscriptionStatus.language` | `SubscriptionStatus.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `SubscriptionStatus.meta` | `SubscriptionStatus.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `SubscriptionStatus.modifierExtension` | `SubscriptionStatus.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `SubscriptionStatus.notificationEvent` | `SubscriptionStatus.notificationEvent` | `notificationEvent` | SubscriptionStatus.notificationEvent | Detailed information about any events relevant to this notification | 0..* | BackboneElement |  |  |
| `SubscriptionStatus.notificationEvent.additionalContext` | `SubscriptionStatus.notificationEvent.additionalContext` | `additionalContext` | SubscriptionStatus.notificationEvent.additionalContext | References related to the focus resource and/or context of this event | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `SubscriptionStatus.notificationEvent.eventNumber` | `SubscriptionStatus.notificationEvent.eventNumber` | `eventNumber` | SubscriptionStatus.notificationEvent.eventNumber | Sequencing index of this event | 1..1 | integer64 |  |  |
| `SubscriptionStatus.notificationEvent.extension` | `SubscriptionStatus.notificationEvent.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubscriptionStatus.notificationEvent.focus` | `SubscriptionStatus.notificationEvent.focus` | `focus` | SubscriptionStatus.notificationEvent.focus | Reference to the primary resource or information of this event | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `SubscriptionStatus.notificationEvent.id` | `SubscriptionStatus.notificationEvent.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubscriptionStatus.notificationEvent.modifierExtension` | `SubscriptionStatus.notificationEvent.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubscriptionStatus.notificationEvent.timestamp` | `SubscriptionStatus.notificationEvent.timestamp` | `timestamp` | SubscriptionStatus.notificationEvent.timestamp | The instant this event occurred | 0..1 | instant |  |  |
| `SubscriptionStatus.status` | `SubscriptionStatus.status` | `status` | SubscriptionStatus.status | requested \| active \| error \| off \| entered-in-error | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/subscription-status|5.0.0` |
| `SubscriptionStatus.subscription` | `SubscriptionStatus.subscription` | `subscription` | SubscriptionStatus.subscription | Reference to the Subscription responsible for this notification | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Subscription) |  |  |
| `SubscriptionStatus.text` | `SubscriptionStatus.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `SubscriptionStatus.topic` | `SubscriptionStatus.topic` | `topic` | SubscriptionStatus.topic | Reference to the SubscriptionTopic this notification relates to | 0..1 | canonical(http://hl7.org/fhir/StructureDefinition/SubscriptionTopic) |  |  |
| `SubscriptionStatus.type` | `SubscriptionStatus.type` | `type` | SubscriptionStatus.type | handshake \| heartbeat \| event-notification \| query-status \| query-event | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/subscription-notification-type|5.0.0` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [SubscriptionStatus](/docs/R4B/Resources/SubscriptionStatus.md)<br/> `http://hl7.org/fhir/StructureDefinition/SubscriptionStatus\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1047`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1276`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SubscriptionStatus](/docs/R5/Resources/SubscriptionStatus.md)<br/> `http://hl7.org/fhir/StructureDefinition/SubscriptionStatus\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition SubscriptionStatus from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B SubscriptionStatus](/docs/R4B/Resources/SubscriptionStatus.md)| Relationship | R5 SubscriptionStatus
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | `SubscriptionStatus`| _Equivalent_<br/>(47925/47926)| **`SubscriptionStatus`**
| | | | | | | `SubscriptionStatus.id`| _Equivalent_<br/>(47927/47928)| **`SubscriptionStatus.id`**
| | | | | | | `SubscriptionStatus.meta`| _Equivalent_<br/>(47929/47930)| **`SubscriptionStatus.meta`**
| | | | | | | `SubscriptionStatus.implicitRules`| _Equivalent_<br/>(47931/47932)| **`SubscriptionStatus.implicitRules`**
| | | | | | | `SubscriptionStatus.language`| _Equivalent_<br/>(47933/47934)| **`SubscriptionStatus.language`**
| | | | | | | `SubscriptionStatus.text`| _Equivalent_<br/>(47935/47936)| **`SubscriptionStatus.text`**
| | | | | | | `SubscriptionStatus.contained`| _Equivalent_<br/>(47937/47938)| **`SubscriptionStatus.contained`**
| | | | | | | `SubscriptionStatus.extension`| _Equivalent_<br/>(47939/47940)| **`SubscriptionStatus.extension`**
| | | | | | | `SubscriptionStatus.modifierExtension`| _Equivalent_<br/>(47941/47942)| **`SubscriptionStatus.modifierExtension`**
| | | | | | | `SubscriptionStatus.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47943)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47944)| **`SubscriptionStatus.status`**
| | | | | | | `SubscriptionStatus.type`| _Equivalent_<br/>(47945/47946)| **`SubscriptionStatus.type`**
| | | | | | | `SubscriptionStatus.eventsSinceSubscriptionStart`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47947)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(47948)| **`SubscriptionStatus.eventsSinceSubscriptionStart`**
| | | | | | | `SubscriptionStatus.notificationEvent`| _Equivalent_<br/>(47949/47950)| **`SubscriptionStatus.notificationEvent`**
| | | | | | | `SubscriptionStatus.notificationEvent.id`| _Equivalent_<br/>(47951/47952)| **`SubscriptionStatus.notificationEvent.id`**
| | | | | | | `SubscriptionStatus.notificationEvent.extension`| _Equivalent_<br/>(47953/47954)| **`SubscriptionStatus.notificationEvent.extension`**
| | | | | | | `SubscriptionStatus.notificationEvent.modifierExtension`| _Equivalent_<br/>(47955/47956)| **`SubscriptionStatus.notificationEvent.modifierExtension`**
| | | | | | | `SubscriptionStatus.notificationEvent.eventNumber`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47957)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(47958)| **`SubscriptionStatus.notificationEvent.eventNumber`**
| | | | | | | `SubscriptionStatus.notificationEvent.timestamp`| _Equivalent_<br/>(47959/47960)| **`SubscriptionStatus.notificationEvent.timestamp`**
| | | | | | | `SubscriptionStatus.notificationEvent.focus`| _Equivalent_<br/>(47961/47962)| **`SubscriptionStatus.notificationEvent.focus`**
| | | | | | | `SubscriptionStatus.notificationEvent.additionalContext`| _Equivalent_<br/>(47963/47964)| **`SubscriptionStatus.notificationEvent.additionalContext`**
| | | | | | | `SubscriptionStatus.subscription`| _Equivalent_<br/>(47965/47966)| **`SubscriptionStatus.subscription`**
| | | | | | | `SubscriptionStatus.topic`| _Equivalent_<br/>(47967/47968)| **`SubscriptionStatus.topic`**
| | | | | | | `SubscriptionStatus.error`| _Equivalent_<br/>(47969/47970)| **`SubscriptionStatus.error`**
| | | | | | | *23 of 23 elements used* | | *23 of 23 elements used* 

