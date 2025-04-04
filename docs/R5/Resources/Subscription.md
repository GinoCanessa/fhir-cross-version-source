Comparison of 
Generated at Friday, April 4, 2025 2:59:05 PM

### Subscription

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Subscription |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Subscription` |
| Version | 5.0.0 |
| Description | The subscription resource describes a particular client's request to be notified about a SubscriptionTopic. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2387` |
| Database Snapshot Count | `39` |
| Database Differential Count | `25` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Subscription` | `Subscription` | `Subscription` | Subscription | Notification about a SubscriptionTopic | 0..* | Subscription |  |  |
| `Subscription.channelType` | `Subscription.channelType` | `channelType` | Subscription.channelType | Channel type for notifications | 1..1 | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/subscription-channel-type` |
| `Subscription.contact` | `Subscription.contact` | `contact` | Subscription.contact | Contact details for source (e.g. troubleshooting) | 0..* | ContactPoint |  |  |
| `Subscription.contained` | `Subscription.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Subscription.content` | `Subscription.content` | `content` | Subscription.content | empty \| id-only \| full-resource | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/subscription-payload-content|5.0.0` |
| `Subscription.contentType` | `Subscription.contentType` | `contentType` | Subscription.contentType | MIME type to send, or omit for no payload | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/mimetypes|5.0.0` |
| `Subscription.end` | `Subscription.end` | `end` | Subscription.end | When to automatically delete the subscription | 0..1 | instant |  |  |
| `Subscription.endpoint` | `Subscription.endpoint` | `endpoint` | Subscription.endpoint | Where the channel points to | 0..1 | url |  |  |
| `Subscription.extension` | `Subscription.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Subscription.filterBy` | `Subscription.filterBy` | `filterBy` | Subscription.filterBy | Criteria for narrowing the subscription topic stream | 0..* | BackboneElement |  |  |
| `Subscription.filterBy.comparator` | `Subscription.filterBy.comparator` | `comparator` | Subscription.filterBy.comparator | eq \| ne \| gt \| lt \| ge \| le \| sa \| eb \| ap | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/search-comparator|5.0.0` |
| `Subscription.filterBy.extension` | `Subscription.filterBy.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Subscription.filterBy.filterParameter` | `Subscription.filterBy.filterParameter` | `filterParameter` | Subscription.filterBy.filterParameter | Filter label defined in SubscriptionTopic | 1..1 | string |  |  |
| `Subscription.filterBy.id` | `Subscription.filterBy.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Subscription.filterBy.modifier` | `Subscription.filterBy.modifier` | `modifier` | Subscription.filterBy.modifier | missing \| exact \| contains \| not \| text \| in \| not-in \| below \| above \| type \| identifier \| of-type \| code-text \| text-advanced \| iterate | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/search-modifier-code|5.0.0` |
| `Subscription.filterBy.modifierExtension` | `Subscription.filterBy.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Subscription.filterBy.resourceType` | `Subscription.filterBy.resourceType` | `resourceType` | Subscription.filterBy.resourceType | Allowed Resource (reference to definition) for this Subscription filter | 0..1 | uri | `Extensible` | `http://hl7.org/fhir/ValueSet/subscription-types` |
| `Subscription.filterBy.value` | `Subscription.filterBy.value` | `value` | Subscription.filterBy.value | Literal value or resource path | 1..1 | string |  |  |
| `Subscription.heartbeatPeriod` | `Subscription.heartbeatPeriod` | `heartbeatPeriod` | Subscription.heartbeatPeriod | Interval in seconds to send 'heartbeat' notification | 0..1 | unsignedInt |  |  |
| `Subscription.id` | `Subscription.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Subscription.identifier` | `Subscription.identifier` | `identifier` | Subscription.identifier | Additional identifiers (business identifier) | 0..* | Identifier |  |  |
| `Subscription.implicitRules` | `Subscription.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Subscription.language` | `Subscription.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `Subscription.managingEntity` | `Subscription.managingEntity` | `managingEntity` | Subscription.managingEntity | Entity responsible for Subscription changes | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/CareTeam), Reference(http://hl7.org/fhir/StructureDefinition/HealthcareService), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Subscription.maxCount` | `Subscription.maxCount` | `maxCount` | Subscription.maxCount | Maximum number of events that can be combined in a single notification | 0..1 | positiveInt |  |  |
| `Subscription.meta` | `Subscription.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Subscription.modifierExtension` | `Subscription.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Subscription.name` | `Subscription.name` | `name` | Subscription.name | Human readable name for this subscription | 0..1 | string |  |  |
| `Subscription.parameter` | `Subscription.parameter` | `parameter` | Subscription.parameter | Channel type | 0..* | BackboneElement |  |  |
| `Subscription.parameter.extension` | `Subscription.parameter.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Subscription.parameter.id` | `Subscription.parameter.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Subscription.parameter.modifierExtension` | `Subscription.parameter.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Subscription.parameter.name` | `Subscription.parameter.name` | `name` | Subscription.parameter.name | Name (key) of the parameter | 1..1 | string |  |  |
| `Subscription.parameter.value` | `Subscription.parameter.value` | `value` | Subscription.parameter.value | Value of the parameter to use or pass through | 1..1 | string |  |  |
| `Subscription.reason` | `Subscription.reason` | `reason` | Subscription.reason | Description of why this subscription was created | 0..1 | string |  |  |
| `Subscription.status` | `Subscription.status` | `status` | Subscription.status | requested \| active \| error \| off \| entered-in-error | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/subscription-status|5.0.0` |
| `Subscription.text` | `Subscription.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Subscription.timeout` | `Subscription.timeout` | `timeout` | Subscription.timeout | Timeout in seconds to attempt notification delivery | 0..1 | unsignedInt |  |  |
| `Subscription.topic` | `Subscription.topic` | `topic` | Subscription.topic | Reference to the subscription topic being subscribed to | 1..1 | canonical(http://hl7.org/fhir/StructureDefinition/SubscriptionTopic) |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Subscription](/docs/R2/Resources/Subscription.md)<br/> `http://hl7.org/fhir/StructureDefinition/Subscription\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `159`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `326`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Subscription](/docs/R3/Resources/Subscription.md)<br/> `http://hl7.org/fhir/StructureDefinition/Subscription\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `520`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `714`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Subscription](/docs/R4/Resources/Subscription.md)<br/> `http://hl7.org/fhir/StructureDefinition/Subscription\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1625`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1626`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Subscription](/docs/R4B/Resources/Subscription.md)<br/> `http://hl7.org/fhir/StructureDefinition/Subscription\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1046`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1275`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Subscription](/docs/R5/Resources/Subscription.md)<br/> `http://hl7.org/fhir/StructureDefinition/Subscription\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Subscription from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Subscription](/docs/R2/Resources/Subscription.md)| Relationship | [R3 Subscription](/docs/R3/Resources/Subscription.md)| Relationship | [R4 Subscription](/docs/R4/Resources/Subscription.md)| Relationship | [R4B Subscription](/docs/R4B/Resources/Subscription.md)| Relationship | R5 Subscription
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Subscription`| _Equivalent_<br/>(7975/7976)| `Subscription`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(18848)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18849)| `Subscription`| _Equivalent_<br/>(33729/33730)| `Subscription`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47889)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47890)| **`Subscription`**
| `Subscription.id`| _Equivalent_<br/>(7977/7978)| `Subscription.id`| _Equivalent_<br/>(18850/18851)| `Subscription.id`| _Equivalent_<br/>(33731/33732)| `Subscription.id`| _Equivalent_<br/>(47891/47892)| **`Subscription.id`**
| `Subscription.meta`| _Equivalent_<br/>(7979/7980)| `Subscription.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18852)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18853)| `Subscription.meta`| _Equivalent_<br/>(33733/33734)| `Subscription.meta`| _Equivalent_<br/>(47893/47894)| **`Subscription.meta`**
| `Subscription.implicitRules`| _Equivalent_<br/>(7981/7982)| `Subscription.implicitRules`| _Equivalent_<br/>(18854/18855)| `Subscription.implicitRules`| _Equivalent_<br/>(33735/33736)| `Subscription.implicitRules`| _Equivalent_<br/>(47895/47896)| **`Subscription.implicitRules`**
| `Subscription.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7983)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7984)| `Subscription.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18856)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18857)| `Subscription.language`| _Equivalent_<br/>(33737/33738)| `Subscription.language`| _Equivalent_<br/>(47897/47898)| **`Subscription.language`**
| `Subscription.text`| _Equivalent_<br/>(7985/7986)| `Subscription.text`| _Equivalent_<br/>(18858/18859)| `Subscription.text`| _Equivalent_<br/>(33739/33740)| `Subscription.text`| _Equivalent_<br/>(47899/47900)| **`Subscription.text`**
| `Subscription.contained`| _Equivalent_<br/>(7987/7988)| `Subscription.contained`| _Equivalent_<br/>(18860/18861)| `Subscription.contained`| _Equivalent_<br/>(33741/33742)| `Subscription.contained`| _Equivalent_<br/>(47901/47902)| **`Subscription.contained`**
| `Subscription.extension`| _Equivalent_<br/>(7989/7990)| `Subscription.extension`| _Equivalent_<br/>(18862/18863)| `Subscription.extension`| _Equivalent_<br/>(33743/33744)| `Subscription.extension`| _Equivalent_<br/>(47903/47904)| **`Subscription.extension`**
| `Subscription.modifierExtension`| _Equivalent_<br/>(7991/7992)| `Subscription.modifierExtension`| _Equivalent_<br/>(18864/18865)| `Subscription.modifierExtension`| _Equivalent_<br/>(33745/33746)| `Subscription.modifierExtension`| _Equivalent_<br/>(47905/47906)| **`Subscription.modifierExtension`**
| | | | | | | | | **`Subscription.identifier`**
| | | | | | | | | **`Subscription.name`**
| `Subscription.status`| _Equivalent_<br/>(7999/8000)| `Subscription.status`| _Equivalent_<br/>(18866/18867)| `Subscription.status`| _Equivalent_<br/>(33747/33748)| `Subscription.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47907)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47908)| **`Subscription.status`**
| | | | | | | | | **`Subscription.topic`**
| `Subscription.contact`| _Equivalent_<br/>(7995/7996)| `Subscription.contact`| _Equivalent_<br/>(18868/18869)| `Subscription.contact`| _Equivalent_<br/>(33749/33750)| `Subscription.contact`| _Equivalent_<br/>(47909/47910)| **`Subscription.contact`**
| `Subscription.end`| _Equivalent_<br/>(8019/8020)| `Subscription.end`| _Equivalent_<br/>(18870/18871)| `Subscription.end`| _Equivalent_<br/>(33751/33752)| `Subscription.end`| _Equivalent_<br/>(47911/47912)| **`Subscription.end`**
| | | | | | | | | **`Subscription.managingEntity`**
| `Subscription.reason`| _Equivalent_<br/>(7997/7998)| `Subscription.reason`| _Equivalent_<br/>(18872/18873)| `Subscription.reason`| _Equivalent_<br/>(33753/33754)| `Subscription.reason`| →→→→ _Equivalent_ →→→→ <br/>(47913)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(47914)| **`Subscription.reason`**
| | | | | | | | | **`Subscription.filterBy`**
| | | | | | | | | **`Subscription.filterBy.id`**
| | | | | | | | | **`Subscription.filterBy.extension`**
| | | | | | | | | **`Subscription.filterBy.modifierExtension`**
| | | | | | | | | **`Subscription.filterBy.resourceType`**
| | | | | | | | | **`Subscription.filterBy.filterParameter`**
| | | | | | | | | **`Subscription.filterBy.comparator`**
| | | | | | | | | **`Subscription.filterBy.modifier`**
| | | | | | | | | **`Subscription.filterBy.value`**
| | | | | | | | | **`Subscription.channelType`**
| | | | | | | | | **`Subscription.endpoint`**
| | | | | | | | | **`Subscription.parameter`**
| | | | | | | | | **`Subscription.parameter.id`**
| | | | | | | | | **`Subscription.parameter.extension`**
| | | | | | | | | **`Subscription.parameter.modifierExtension`**
| | | | | | | | | **`Subscription.parameter.name`**
| | | | | | | | | **`Subscription.parameter.value`**
| | | | | | | | | **`Subscription.heartbeatPeriod`**
| | | | | | | | | **`Subscription.timeout`**
| | | | | | | | | **`Subscription.contentType`**
| | | | | | | | | **`Subscription.content`**
| | | | | | | | | **`Subscription.maxCount`**
| *13 of 24 elements used* <br/>remaining elements:<br/>`Subscription.channel`, `Subscription.channel.endpoint`, `Subscription.channel.extension`, `Subscription.channel.header`, `Subscription.channel.id`, `Subscription.channel.modifierExtension`, `Subscription.channel.payload`, `Subscription.channel.type`, `Subscription.criteria`, `Subscription.error`, `Subscription.tag`| | *13 of 24 elements used* <br/>remaining elements:<br/>`Subscription.channel`, `Subscription.channel.endpoint`, `Subscription.channel.extension`, `Subscription.channel.header`, `Subscription.channel.id`, `Subscription.channel.modifierExtension`, `Subscription.channel.payload`, `Subscription.channel.type`, `Subscription.criteria`, `Subscription.error`, `Subscription.tag`| | *13 of 23 elements used* <br/>remaining elements:<br/>`Subscription.channel`, `Subscription.channel.endpoint`, `Subscription.channel.extension`, `Subscription.channel.header`, `Subscription.channel.id`, `Subscription.channel.modifierExtension`, `Subscription.channel.payload`, `Subscription.channel.type`, `Subscription.criteria`, `Subscription.error`| | *13 of 23 elements used* <br/>remaining elements:<br/>`Subscription.channel`, `Subscription.channel.endpoint`, `Subscription.channel.extension`, `Subscription.channel.header`, `Subscription.channel.id`, `Subscription.channel.modifierExtension`, `Subscription.channel.payload`, `Subscription.channel.type`, `Subscription.criteria`, `Subscription.error`| | *39 of 39 elements used* 

