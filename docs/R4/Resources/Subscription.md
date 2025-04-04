Comparison of 
Generated at Friday, April 4, 2025 2:58:48 PM

### Subscription

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | Subscription |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Subscription` |
| Version | 4.0.1 |
| Description | The subscription resource is used to define a push-based subscription from a server to another system. Once a subscription is registered with the server, the server checks every resource that is created or updated, and if the resource matches the given criteria, it sends a message on the defined "channel" so that another system can take an appropriate action. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1162` |
| Database Snapshot Count | `23` |
| Database Differential Count | `12` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Subscription` | `Subscription` | `Subscription` | Subscription | Server push subscription criteria | 0..* | Subscription |  |  |
| `Subscription.channel` | `Subscription.channel` | `channel` | Subscription.channel | The channel on which to report matches to the criteria | 1..1 | BackboneElement |  |  |
| `Subscription.channel.endpoint` | `Subscription.channel.endpoint` | `endpoint` | Subscription.channel.endpoint | Where the channel points to | 0..1 | url |  |  |
| `Subscription.channel.extension` | `Subscription.channel.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Subscription.channel.header` | `Subscription.channel.header` | `header` | Subscription.channel.header | Usage depends on the channel type | 0..* | string |  |  |
| `Subscription.channel.id` | `Subscription.channel.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Subscription.channel.modifierExtension` | `Subscription.channel.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Subscription.channel.payload` | `Subscription.channel.payload` | `payload` | Subscription.channel.payload | MIME type to send, or omit for no payload | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/mimetypes|4.0.1` |
| `Subscription.channel.type` | `Subscription.channel.type` | `type` | Subscription.channel.type | rest-hook \| websocket \| email \| sms \| message | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/subscription-channel-type|4.0.1` |
| `Subscription.contact` | `Subscription.contact` | `contact` | Subscription.contact | Contact details for source (e.g. troubleshooting) | 0..* | ContactPoint |  |  |
| `Subscription.contained` | `Subscription.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Subscription.criteria` | `Subscription.criteria` | `criteria` | Subscription.criteria | Rule for server push | 1..1 | string |  |  |
| `Subscription.end` | `Subscription.end` | `end` | Subscription.end | When to automatically delete the subscription | 0..1 | instant |  |  |
| `Subscription.error` | `Subscription.error` | `error` | Subscription.error | Latest error note | 0..1 | string |  |  |
| `Subscription.extension` | `Subscription.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Subscription.id` | `Subscription.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Subscription.implicitRules` | `Subscription.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Subscription.language` | `Subscription.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `Subscription.meta` | `Subscription.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Subscription.modifierExtension` | `Subscription.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Subscription.reason` | `Subscription.reason` | `reason` | Subscription.reason | Description of why this subscription was created | 1..1 | string |  |  |
| `Subscription.status` | `Subscription.status` | `status` | Subscription.status | requested \| active \| error \| off | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/subscription-status|4.0.1` |
| `Subscription.text` | `Subscription.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Subscription](/docs/R2/Resources/Subscription.md)<br/> `http://hl7.org/fhir/StructureDefinition/Subscription\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `159`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `326`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Subscription](/docs/R3/Resources/Subscription.md)<br/> `http://hl7.org/fhir/StructureDefinition/Subscription\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `520`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `714`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Subscription](/docs/R4/Resources/Subscription.md)<br/> `http://hl7.org/fhir/StructureDefinition/Subscription\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1625`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1626`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Subscription](/docs/R4B/Resources/Subscription.md)<br/> `http://hl7.org/fhir/StructureDefinition/Subscription\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1046`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1275`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Subscription](/docs/R5/Resources/Subscription.md)<br/> `http://hl7.org/fhir/StructureDefinition/Subscription\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Subscription from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Subscription](/docs/R2/Resources/Subscription.md)| Relationship | [R3 Subscription](/docs/R3/Resources/Subscription.md)| Relationship | R4 Subscription| Relationship | [R4B Subscription](/docs/R4B/Resources/Subscription.md)| Relationship | [R5 Subscription](/docs/R5/Resources/Subscription.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Subscription`| _Equivalent_<br/>(7975/7976)| `Subscription`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(18848)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18849)| **`Subscription`**| _Equivalent_<br/>(33729/33730)| `Subscription`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47889)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47890)| `Subscription`
| `Subscription.id`| _Equivalent_<br/>(7977/7978)| `Subscription.id`| _Equivalent_<br/>(18850/18851)| **`Subscription.id`**| _Equivalent_<br/>(33731/33732)| `Subscription.id`| _Equivalent_<br/>(47891/47892)| `Subscription.id`
| `Subscription.meta`| _Equivalent_<br/>(7979/7980)| `Subscription.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18852)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18853)| **`Subscription.meta`**| _Equivalent_<br/>(33733/33734)| `Subscription.meta`| _Equivalent_<br/>(47893/47894)| `Subscription.meta`
| `Subscription.implicitRules`| _Equivalent_<br/>(7981/7982)| `Subscription.implicitRules`| _Equivalent_<br/>(18854/18855)| **`Subscription.implicitRules`**| _Equivalent_<br/>(33735/33736)| `Subscription.implicitRules`| _Equivalent_<br/>(47895/47896)| `Subscription.implicitRules`
| `Subscription.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7983)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7984)| `Subscription.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18856)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18857)| **`Subscription.language`**| _Equivalent_<br/>(33737/33738)| `Subscription.language`| _Equivalent_<br/>(47897/47898)| `Subscription.language`
| `Subscription.text`| _Equivalent_<br/>(7985/7986)| `Subscription.text`| _Equivalent_<br/>(18858/18859)| **`Subscription.text`**| _Equivalent_<br/>(33739/33740)| `Subscription.text`| _Equivalent_<br/>(47899/47900)| `Subscription.text`
| `Subscription.contained`| _Equivalent_<br/>(7987/7988)| `Subscription.contained`| _Equivalent_<br/>(18860/18861)| **`Subscription.contained`**| _Equivalent_<br/>(33741/33742)| `Subscription.contained`| _Equivalent_<br/>(47901/47902)| `Subscription.contained`
| `Subscription.extension`| _Equivalent_<br/>(7989/7990)| `Subscription.extension`| _Equivalent_<br/>(18862/18863)| **`Subscription.extension`**| _Equivalent_<br/>(33743/33744)| `Subscription.extension`| _Equivalent_<br/>(47903/47904)| `Subscription.extension`
| `Subscription.modifierExtension`| _Equivalent_<br/>(7991/7992)| `Subscription.modifierExtension`| _Equivalent_<br/>(18864/18865)| **`Subscription.modifierExtension`**| _Equivalent_<br/>(33745/33746)| `Subscription.modifierExtension`| _Equivalent_<br/>(47905/47906)| `Subscription.modifierExtension`
| `Subscription.status`| _Equivalent_<br/>(7999/8000)| `Subscription.status`| _Equivalent_<br/>(18866/18867)| **`Subscription.status`**| _Equivalent_<br/>(33747/33748)| `Subscription.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47907)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47908)| `Subscription.status`
| `Subscription.contact`| _Equivalent_<br/>(7995/7996)| `Subscription.contact`| _Equivalent_<br/>(18868/18869)| **`Subscription.contact`**| _Equivalent_<br/>(33749/33750)| `Subscription.contact`| _Equivalent_<br/>(47909/47910)| `Subscription.contact`
| `Subscription.end`| _Equivalent_<br/>(8019/8020)| `Subscription.end`| _Equivalent_<br/>(18870/18871)| **`Subscription.end`**| _Equivalent_<br/>(33751/33752)| `Subscription.end`| _Equivalent_<br/>(47911/47912)| `Subscription.end`
| `Subscription.reason`| _Equivalent_<br/>(7997/7998)| `Subscription.reason`| _Equivalent_<br/>(18872/18873)| **`Subscription.reason`**| _Equivalent_<br/>(33753/33754)| `Subscription.reason`| →→→→ _Equivalent_ →→→→ <br/>(47913)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(47914)| `Subscription.reason`
| `Subscription.criteria`| _Equivalent_<br/>(7993/7994)| `Subscription.criteria`| _Equivalent_<br/>(18874/18875)| **`Subscription.criteria`**| _Equivalent_<br/>(33755/33756)| `Subscription.criteria`| | | 
| `Subscription.error`| _Equivalent_<br/>(8001/8002)| `Subscription.error`| _Equivalent_<br/>(18876/18877)| **`Subscription.error`**| _Equivalent_<br/>(33757/33758)| `Subscription.error`| | | 
| `Subscription.channel`| _Equivalent_<br/>(8003/8004)| `Subscription.channel`| _Equivalent_<br/>(18878/18879)| **`Subscription.channel`**| _Equivalent_<br/>(33759/33760)| `Subscription.channel`| | | 
| `Subscription.channel.id`| _Equivalent_<br/>(8005/8006)| `Subscription.channel.id`| _Equivalent_<br/>(18880/18881)| **`Subscription.channel.id`**| _Equivalent_<br/>(33761/33762)| `Subscription.channel.id`| | | 
| `Subscription.channel.extension`| _Equivalent_<br/>(8007/8008)| `Subscription.channel.extension`| _Equivalent_<br/>(18882/18883)| **`Subscription.channel.extension`**| _Equivalent_<br/>(33763/33764)| `Subscription.channel.extension`| | | 
| `Subscription.channel.modifierExtension`| _Equivalent_<br/>(8009/8010)| `Subscription.channel.modifierExtension`| _Equivalent_<br/>(18884/18885)| **`Subscription.channel.modifierExtension`**| _Equivalent_<br/>(33765/33766)| `Subscription.channel.modifierExtension`| | | 
| `Subscription.channel.type`| _Equivalent_<br/>(8011/8012)| `Subscription.channel.type`| _Equivalent_<br/>(18886/18887)| **`Subscription.channel.type`**| _Equivalent_<br/>(33767/33768)| `Subscription.channel.type`| | | 
| `Subscription.channel.endpoint`| _Equivalent_<br/>(8013/8014)| `Subscription.channel.endpoint`| _Equivalent_<br/>(18888/18889)| **`Subscription.channel.endpoint`**| _Equivalent_<br/>(33769/33770)| `Subscription.channel.endpoint`| | | 
| `Subscription.channel.payload`| →→→→ _Equivalent_ →→→→ <br/>(8015)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(8016)| `Subscription.channel.payload`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18890)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18891)| **`Subscription.channel.payload`**| _Equivalent_<br/>(33771/33772)| `Subscription.channel.payload`| | | 
| `Subscription.channel.header`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8017)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8018)| `Subscription.channel.header`| _Equivalent_<br/>(18892/18893)| **`Subscription.channel.header`**| _Equivalent_<br/>(33773/33774)| `Subscription.channel.header`| | | 
| *23 of 24 elements used* <br/>remaining elements:<br/>`Subscription.tag`| | *23 of 24 elements used* <br/>remaining elements:<br/>`Subscription.tag`| | *23 of 23 elements used* | | *23 of 23 elements used* | | *13 of 39 elements used* <br/>remaining elements:<br/>`Subscription.channelType`, `Subscription.content`, `Subscription.contentType`, `Subscription.endpoint`, `Subscription.filterBy`, `Subscription.filterBy.comparator`, `Subscription.filterBy.extension`, `Subscription.filterBy.filterParameter`, `Subscription.filterBy.id`, `Subscription.filterBy.modifier`, `Subscription.filterBy.modifierExtension`, `Subscription.filterBy.resourceType`, `Subscription.filterBy.value`, `Subscription.heartbeatPeriod`, `Subscription.identifier`, `Subscription.managingEntity`, `Subscription.maxCount`, `Subscription.name`, `Subscription.parameter`, `Subscription.parameter.extension`, `Subscription.parameter.id`, `Subscription.parameter.modifierExtension`, `Subscription.parameter.name`, `Subscription.parameter.value`, `Subscription.timeout`, `Subscription.topic`

