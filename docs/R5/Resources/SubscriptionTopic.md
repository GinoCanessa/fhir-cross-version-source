Comparison of 
Generated at Tuesday, April 1, 2025 1:39:36 PM

### SubscriptionTopic

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | SubscriptionTopic |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/SubscriptionTopic` |
| Version | 5.0.0 |
| Description | Describes a stream of resource state changes identified by trigger criteria and annotated with labels useful to filter projections from this topic. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2389` |
| Database Snapshot Count | `71` |
| Database Differential Count | `48` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `SubscriptionTopic` | `SubscriptionTopic` | `SubscriptionTopic` | SubscriptionTopic | The definition of a specific topic for triggering events within the Subscriptions framework | 0..* | SubscriptionTopic |  |  |
| `SubscriptionTopic.approvalDate` | `SubscriptionTopic.approvalDate` | `approvalDate` | SubscriptionTopic.approvalDate | When SubscriptionTopic is/was approved by publisher | 0..1 | date |  |  |
| `SubscriptionTopic.canFilterBy` | `SubscriptionTopic.canFilterBy` | `canFilterBy` | SubscriptionTopic.canFilterBy | Properties by which a Subscription can filter notifications from the SubscriptionTopic | 0..* | BackboneElement |  |  |
| `SubscriptionTopic.canFilterBy.comparator` | `SubscriptionTopic.canFilterBy.comparator` | `comparator` | SubscriptionTopic.canFilterBy.comparator | eq \| ne \| gt \| lt \| ge \| le \| sa \| eb \| ap | 0..* | code | `Required` | `http://hl7.org/fhir/ValueSet/search-comparator|5.0.0` |
| `SubscriptionTopic.canFilterBy.description` | `SubscriptionTopic.canFilterBy.description` | `description` | SubscriptionTopic.canFilterBy.description | Description of this filter parameter | 0..1 | markdown |  |  |
| `SubscriptionTopic.canFilterBy.extension` | `SubscriptionTopic.canFilterBy.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubscriptionTopic.canFilterBy.filterDefinition` | `SubscriptionTopic.canFilterBy.filterDefinition` | `filterDefinition` | SubscriptionTopic.canFilterBy.filterDefinition | Canonical URL for a filterParameter definition | 0..1 | uri |  |  |
| `SubscriptionTopic.canFilterBy.filterParameter` | `SubscriptionTopic.canFilterBy.filterParameter` | `filterParameter` | SubscriptionTopic.canFilterBy.filterParameter | Human-readable and computation-friendly name for a filter parameter usable by subscriptions on this topic, via Subscription.filterBy.filterParameter | 1..1 | string |  |  |
| `SubscriptionTopic.canFilterBy.id` | `SubscriptionTopic.canFilterBy.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubscriptionTopic.canFilterBy.modifier` | `SubscriptionTopic.canFilterBy.modifier` | `modifier` | SubscriptionTopic.canFilterBy.modifier | missing \| exact \| contains \| not \| text \| in \| not-in \| below \| above \| type \| identifier \| of-type \| code-text \| text-advanced \| iterate | 0..* | code | `Required` | `http://hl7.org/fhir/ValueSet/search-modifier-code|5.0.0` |
| `SubscriptionTopic.canFilterBy.modifierExtension` | `SubscriptionTopic.canFilterBy.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubscriptionTopic.canFilterBy.resource` | `SubscriptionTopic.canFilterBy.resource` | `resource` | SubscriptionTopic.canFilterBy.resource | URL of the triggering Resource that this filter applies to | 0..1 | uri | `Extensible` | `http://hl7.org/fhir/ValueSet/subscription-types` |
| `SubscriptionTopic.contact` | `SubscriptionTopic.contact` | `contact` | SubscriptionTopic.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `SubscriptionTopic.contained` | `SubscriptionTopic.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `SubscriptionTopic.copyright` | `SubscriptionTopic.copyright` | `copyright` | SubscriptionTopic.copyright | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `SubscriptionTopic.copyrightLabel` | `SubscriptionTopic.copyrightLabel` | `copyrightLabel` | SubscriptionTopic.copyrightLabel | Copyright holder and year(s) | 0..1 | string |  |  |
| `SubscriptionTopic.date` | `SubscriptionTopic.date` | `date` | SubscriptionTopic.date | Date status first applied | 0..1 | dateTime |  |  |
| `SubscriptionTopic.derivedFrom` | `SubscriptionTopic.derivedFrom` | `derivedFrom` | SubscriptionTopic.derivedFrom | Based on FHIR protocol or definition | 0..* | canonical(http://hl7.org/fhir/StructureDefinition/SubscriptionTopic) |  |  |
| `SubscriptionTopic.description` | `SubscriptionTopic.description` | `description` | SubscriptionTopic.description | Natural language description of the SubscriptionTopic | 0..1 | markdown |  |  |
| `SubscriptionTopic.effectivePeriod` | `SubscriptionTopic.effectivePeriod` | `effectivePeriod` | SubscriptionTopic.effectivePeriod | The effective date range for the SubscriptionTopic | 0..1 | Period |  |  |
| `SubscriptionTopic.eventTrigger` | `SubscriptionTopic.eventTrigger` | `eventTrigger` | SubscriptionTopic.eventTrigger | Event definitions the SubscriptionTopic | 0..* | BackboneElement |  |  |
| `SubscriptionTopic.eventTrigger.description` | `SubscriptionTopic.eventTrigger.description` | `description` | SubscriptionTopic.eventTrigger.description | Text representation of the event trigger | 0..1 | markdown |  |  |
| `SubscriptionTopic.eventTrigger.event` | `SubscriptionTopic.eventTrigger.event` | `event` | SubscriptionTopic.eventTrigger.event | Event which can trigger a notification from the SubscriptionTopic | 1..1 | CodeableConcept | `Example` | `http://terminology.hl7.org/ValueSet/v2-0003` |
| `SubscriptionTopic.eventTrigger.extension` | `SubscriptionTopic.eventTrigger.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubscriptionTopic.eventTrigger.id` | `SubscriptionTopic.eventTrigger.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubscriptionTopic.eventTrigger.modifierExtension` | `SubscriptionTopic.eventTrigger.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubscriptionTopic.eventTrigger.resource` | `SubscriptionTopic.eventTrigger.resource` | `resource` | SubscriptionTopic.eventTrigger.resource | Data Type or Resource (reference to definition) for this trigger definition | 1..1 | uri | `Extensible` | `http://hl7.org/fhir/ValueSet/subscription-types` |
| `SubscriptionTopic.experimental` | `SubscriptionTopic.experimental` | `experimental` | SubscriptionTopic.experimental | If for testing purposes, not real usage | 0..1 | boolean |  |  |
| `SubscriptionTopic.extension` | `SubscriptionTopic.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubscriptionTopic.id` | `SubscriptionTopic.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `SubscriptionTopic.identifier` | `SubscriptionTopic.identifier` | `identifier` | SubscriptionTopic.identifier | Business identifier for subscription topic | 0..* | Identifier |  |  |
| `SubscriptionTopic.implicitRules` | `SubscriptionTopic.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `SubscriptionTopic.jurisdiction` | `SubscriptionTopic.jurisdiction` | `jurisdiction` | SubscriptionTopic.jurisdiction | Intended jurisdiction of the SubscriptionTopic (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `SubscriptionTopic.language` | `SubscriptionTopic.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `SubscriptionTopic.lastReviewDate` | `SubscriptionTopic.lastReviewDate` | `lastReviewDate` | SubscriptionTopic.lastReviewDate | Date the Subscription Topic was last reviewed by the publisher | 0..1 | date |  |  |
| `SubscriptionTopic.meta` | `SubscriptionTopic.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `SubscriptionTopic.modifierExtension` | `SubscriptionTopic.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `SubscriptionTopic.name` | `SubscriptionTopic.name` | `name` | SubscriptionTopic.name | Name for this subscription topic (computer friendly) | 0..1 | string |  |  |
| `SubscriptionTopic.notificationShape` | `SubscriptionTopic.notificationShape` | `notificationShape` | SubscriptionTopic.notificationShape | Properties for describing the shape of notifications generated by this topic | 0..* | BackboneElement |  |  |
| `SubscriptionTopic.notificationShape.extension` | `SubscriptionTopic.notificationShape.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubscriptionTopic.notificationShape.id` | `SubscriptionTopic.notificationShape.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubscriptionTopic.notificationShape.include` | `SubscriptionTopic.notificationShape.include` | `include` | SubscriptionTopic.notificationShape.include | Include directives, rooted in the resource for this shape | 0..* | string |  |  |
| `SubscriptionTopic.notificationShape.modifierExtension` | `SubscriptionTopic.notificationShape.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubscriptionTopic.notificationShape.resource` | `SubscriptionTopic.notificationShape.resource` | `resource` | SubscriptionTopic.notificationShape.resource | URL of the Resource that is the focus (main) resource in a notification shape | 1..1 | uri | `Extensible` | `http://hl7.org/fhir/ValueSet/subscription-types` |
| `SubscriptionTopic.notificationShape.revInclude` | `SubscriptionTopic.notificationShape.revInclude` | `revInclude` | SubscriptionTopic.notificationShape.revInclude | Reverse include directives, rooted in the resource for this shape | 0..* | string |  |  |
| `SubscriptionTopic.publisher` | `SubscriptionTopic.publisher` | `publisher` | SubscriptionTopic.publisher | The name of the individual or organization that published the SubscriptionTopic | 0..1 | string |  |  |
| `SubscriptionTopic.purpose` | `SubscriptionTopic.purpose` | `purpose` | SubscriptionTopic.purpose | Why this SubscriptionTopic is defined | 0..1 | markdown |  |  |
| `SubscriptionTopic.resourceTrigger` | `SubscriptionTopic.resourceTrigger` | `resourceTrigger` | SubscriptionTopic.resourceTrigger | Definition of a resource-based trigger for the subscription topic | 0..* | BackboneElement |  |  |
| `SubscriptionTopic.resourceTrigger.description` | `SubscriptionTopic.resourceTrigger.description` | `description` | SubscriptionTopic.resourceTrigger.description | Text representation of the resource trigger | 0..1 | markdown |  |  |
| `SubscriptionTopic.resourceTrigger.extension` | `SubscriptionTopic.resourceTrigger.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubscriptionTopic.resourceTrigger.fhirPathCriteria` | `SubscriptionTopic.resourceTrigger.fhirPathCriteria` | `fhirPathCriteria` | SubscriptionTopic.resourceTrigger.fhirPathCriteria | FHIRPath based trigger rule | 0..1 | string |  |  |
| `SubscriptionTopic.resourceTrigger.id` | `SubscriptionTopic.resourceTrigger.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubscriptionTopic.resourceTrigger.modifierExtension` | `SubscriptionTopic.resourceTrigger.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubscriptionTopic.resourceTrigger.queryCriteria` | `SubscriptionTopic.resourceTrigger.queryCriteria` | `queryCriteria` | SubscriptionTopic.resourceTrigger.queryCriteria | Query based trigger rule | 0..1 | BackboneElement |  |  |
| `SubscriptionTopic.resourceTrigger.queryCriteria.current` | `SubscriptionTopic.resourceTrigger.queryCriteria.current` | `current` | SubscriptionTopic.resourceTrigger.queryCriteria.current | Rule applied to current resource state | 0..1 | string |  |  |
| `SubscriptionTopic.resourceTrigger.queryCriteria.extension` | `SubscriptionTopic.resourceTrigger.queryCriteria.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubscriptionTopic.resourceTrigger.queryCriteria.id` | `SubscriptionTopic.resourceTrigger.queryCriteria.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubscriptionTopic.resourceTrigger.queryCriteria.modifierExtension` | `SubscriptionTopic.resourceTrigger.queryCriteria.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubscriptionTopic.resourceTrigger.queryCriteria.previous` | `SubscriptionTopic.resourceTrigger.queryCriteria.previous` | `previous` | SubscriptionTopic.resourceTrigger.queryCriteria.previous | Rule applied to previous resource state | 0..1 | string |  |  |
| `SubscriptionTopic.resourceTrigger.queryCriteria.requireBoth` | `SubscriptionTopic.resourceTrigger.queryCriteria.requireBoth` | `requireBoth` | SubscriptionTopic.resourceTrigger.queryCriteria.requireBoth | Both must be true flag | 0..1 | boolean |  |  |
| `SubscriptionTopic.resourceTrigger.queryCriteria.resultForCreate` | `SubscriptionTopic.resourceTrigger.queryCriteria.resultForCreate` | `resultForCreate` | SubscriptionTopic.resourceTrigger.queryCriteria.resultForCreate | test-passes \| test-fails | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/subscriptiontopic-cr-behavior|5.0.0` |
| `SubscriptionTopic.resourceTrigger.queryCriteria.resultForDelete` | `SubscriptionTopic.resourceTrigger.queryCriteria.resultForDelete` | `resultForDelete` | SubscriptionTopic.resourceTrigger.queryCriteria.resultForDelete | test-passes \| test-fails | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/subscriptiontopic-cr-behavior|5.0.0` |
| `SubscriptionTopic.resourceTrigger.resource` | `SubscriptionTopic.resourceTrigger.resource` | `resource` | SubscriptionTopic.resourceTrigger.resource | Data Type or Resource (reference to definition) for this trigger definition | 1..1 | uri | `Extensible` | `http://hl7.org/fhir/ValueSet/subscription-types` |
| `SubscriptionTopic.resourceTrigger.supportedInteraction` | `SubscriptionTopic.resourceTrigger.supportedInteraction` | `supportedInteraction` | SubscriptionTopic.resourceTrigger.supportedInteraction | create \| update \| delete | 0..* | code | `Required` | `http://hl7.org/fhir/ValueSet/interaction-trigger|5.0.0` |
| `SubscriptionTopic.status` | `SubscriptionTopic.status` | `status` | SubscriptionTopic.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|5.0.0` |
| `SubscriptionTopic.text` | `SubscriptionTopic.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `SubscriptionTopic.title` | `SubscriptionTopic.title` | `title` | SubscriptionTopic.title | Name for this subscription topic (human friendly) | 0..1 | string |  |  |
| `SubscriptionTopic.url` | `SubscriptionTopic.url` | `url` | SubscriptionTopic.url | Canonical identifier for this subscription topic, represented as an absolute URI (globally unique) | 1..1 | uri |  |  |
| `SubscriptionTopic.useContext` | `SubscriptionTopic.useContext` | `useContext` | SubscriptionTopic.useContext | Content intends to support these contexts | 0..* | UsageContext |  |  |
| `SubscriptionTopic.version` | `SubscriptionTopic.version` | `version` | SubscriptionTopic.version | Business version of the subscription topic | 0..1 | string |  |  |
| `SubscriptionTopic.versionAlgorithm[x]` | `SubscriptionTopic.versionAlgorithm[x]` | `versionAlgorithm[x]` | SubscriptionTopic.versionAlgorithm[x] | How to compare versions | 0..1 | Coding, string | `Extensible` | `http://hl7.org/fhir/ValueSet/version-algorithm` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [SubscriptionTopic](/docs/R4B/Resources/SubscriptionTopic.md)<br/> `http://hl7.org/fhir/StructureDefinition/SubscriptionTopic\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1048`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1277`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SubscriptionTopic](/docs/R5/Resources/SubscriptionTopic.md)<br/> `http://hl7.org/fhir/StructureDefinition/SubscriptionTopic\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition SubscriptionTopic from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B SubscriptionTopic](/docs/R4B/Resources/SubscriptionTopic.md)| Relationship | R5 SubscriptionTopic
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | `SubscriptionTopic`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47971)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47972)| **`SubscriptionTopic`**
| | | | | | | `SubscriptionTopic.id`| _Equivalent_<br/>(47973/47974)| **`SubscriptionTopic.id`**
| | | | | | | `SubscriptionTopic.meta`| _Equivalent_<br/>(47975/47976)| **`SubscriptionTopic.meta`**
| | | | | | | `SubscriptionTopic.implicitRules`| _Equivalent_<br/>(47977/47978)| **`SubscriptionTopic.implicitRules`**
| | | | | | | `SubscriptionTopic.language`| _Equivalent_<br/>(47979/47980)| **`SubscriptionTopic.language`**
| | | | | | | `SubscriptionTopic.text`| _Equivalent_<br/>(47981/47982)| **`SubscriptionTopic.text`**
| | | | | | | `SubscriptionTopic.contained`| _Equivalent_<br/>(47983/47984)| **`SubscriptionTopic.contained`**
| | | | | | | `SubscriptionTopic.extension`| _Equivalent_<br/>(47985/47986)| **`SubscriptionTopic.extension`**
| | | | | | | `SubscriptionTopic.modifierExtension`| _Equivalent_<br/>(47987/47988)| **`SubscriptionTopic.modifierExtension`**
| | | | | | | `SubscriptionTopic.url`| _Equivalent_<br/>(47989/47990)| **`SubscriptionTopic.url`**
| | | | | | | `SubscriptionTopic.identifier`| _Equivalent_<br/>(47991/47992)| **`SubscriptionTopic.identifier`**
| | | | | | | `SubscriptionTopic.version`| _Equivalent_<br/>(47993/47994)| **`SubscriptionTopic.version`**
| | | | | | | | | **`SubscriptionTopic.versionAlgorithm[x]`**
| | | | | | | | | **`SubscriptionTopic.name`**
| | | | | | | `SubscriptionTopic.title`| _Equivalent_<br/>(47995/47996)| **`SubscriptionTopic.title`**
| | | | | | | `SubscriptionTopic.derivedFrom`| _Equivalent_<br/>(47997/47998)| **`SubscriptionTopic.derivedFrom`**
| | | | | | | `SubscriptionTopic.status`| _Equivalent_<br/>(47999/48000)| **`SubscriptionTopic.status`**
| | | | | | | `SubscriptionTopic.experimental`| _Equivalent_<br/>(48001/48002)| **`SubscriptionTopic.experimental`**
| | | | | | | `SubscriptionTopic.date`| _Equivalent_<br/>(48003/48004)| **`SubscriptionTopic.date`**
| | | | | | | `SubscriptionTopic.publisher`| _Equivalent_<br/>(48005/48006)| **`SubscriptionTopic.publisher`**
| | | | | | | `SubscriptionTopic.contact`| _Equivalent_<br/>(48007/48008)| **`SubscriptionTopic.contact`**
| | | | | | | `SubscriptionTopic.description`| _Equivalent_<br/>(48009/48010)| **`SubscriptionTopic.description`**
| | | | | | | `SubscriptionTopic.useContext`| _Equivalent_<br/>(48011/48012)| **`SubscriptionTopic.useContext`**
| | | | | | | `SubscriptionTopic.jurisdiction`| _Equivalent_<br/>(48013/48014)| **`SubscriptionTopic.jurisdiction`**
| | | | | | | `SubscriptionTopic.purpose`| _Equivalent_<br/>(48015/48016)| **`SubscriptionTopic.purpose`**
| | | | | | | `SubscriptionTopic.copyright`| _Equivalent_<br/>(48017/48018)| **`SubscriptionTopic.copyright`**
| | | | | | | | | **`SubscriptionTopic.copyrightLabel`**
| | | | | | | `SubscriptionTopic.approvalDate`| _Equivalent_<br/>(48019/48020)| **`SubscriptionTopic.approvalDate`**
| | | | | | | `SubscriptionTopic.lastReviewDate`| _Equivalent_<br/>(48021/48022)| **`SubscriptionTopic.lastReviewDate`**
| | | | | | | `SubscriptionTopic.effectivePeriod`| _Equivalent_<br/>(48023/48024)| **`SubscriptionTopic.effectivePeriod`**
| | | | | | | `SubscriptionTopic.resourceTrigger`| _Equivalent_<br/>(48025/48026)| **`SubscriptionTopic.resourceTrigger`**
| | | | | | | `SubscriptionTopic.resourceTrigger.id`| _Equivalent_<br/>(48027/48028)| **`SubscriptionTopic.resourceTrigger.id`**
| | | | | | | `SubscriptionTopic.resourceTrigger.extension`| _Equivalent_<br/>(48029/48030)| **`SubscriptionTopic.resourceTrigger.extension`**
| | | | | | | `SubscriptionTopic.resourceTrigger.modifierExtension`| _Equivalent_<br/>(48031/48032)| **`SubscriptionTopic.resourceTrigger.modifierExtension`**
| | | | | | | `SubscriptionTopic.resourceTrigger.description`| _Equivalent_<br/>(48033/48034)| **`SubscriptionTopic.resourceTrigger.description`**
| | | | | | | `SubscriptionTopic.resourceTrigger.resource`| _Equivalent_<br/>(48035/48036)| **`SubscriptionTopic.resourceTrigger.resource`**
| | | | | | | `SubscriptionTopic.resourceTrigger.supportedInteraction`| _Equivalent_<br/>(48037/48038)| **`SubscriptionTopic.resourceTrigger.supportedInteraction`**
| | | | | | | `SubscriptionTopic.resourceTrigger.queryCriteria`| _Equivalent_<br/>(48039/48040)| **`SubscriptionTopic.resourceTrigger.queryCriteria`**
| | | | | | | `SubscriptionTopic.resourceTrigger.queryCriteria.id`| _Equivalent_<br/>(48041/48042)| **`SubscriptionTopic.resourceTrigger.queryCriteria.id`**
| | | | | | | `SubscriptionTopic.resourceTrigger.queryCriteria.extension`| _Equivalent_<br/>(48043/48044)| **`SubscriptionTopic.resourceTrigger.queryCriteria.extension`**
| | | | | | | `SubscriptionTopic.resourceTrigger.queryCriteria.modifierExtension`| _Equivalent_<br/>(48045/48046)| **`SubscriptionTopic.resourceTrigger.queryCriteria.modifierExtension`**
| | | | | | | `SubscriptionTopic.resourceTrigger.queryCriteria.previous`| _Equivalent_<br/>(48047/48048)| **`SubscriptionTopic.resourceTrigger.queryCriteria.previous`**
| | | | | | | `SubscriptionTopic.resourceTrigger.queryCriteria.resultForCreate`| _Equivalent_<br/>(48049/48050)| **`SubscriptionTopic.resourceTrigger.queryCriteria.resultForCreate`**
| | | | | | | `SubscriptionTopic.resourceTrigger.queryCriteria.current`| _Equivalent_<br/>(48051/48052)| **`SubscriptionTopic.resourceTrigger.queryCriteria.current`**
| | | | | | | `SubscriptionTopic.resourceTrigger.queryCriteria.resultForDelete`| _Equivalent_<br/>(48053/48054)| **`SubscriptionTopic.resourceTrigger.queryCriteria.resultForDelete`**
| | | | | | | `SubscriptionTopic.resourceTrigger.queryCriteria.requireBoth`| _Equivalent_<br/>(48055/48056)| **`SubscriptionTopic.resourceTrigger.queryCriteria.requireBoth`**
| | | | | | | `SubscriptionTopic.resourceTrigger.fhirPathCriteria`| _Equivalent_<br/>(48057/48058)| **`SubscriptionTopic.resourceTrigger.fhirPathCriteria`**
| | | | | | | `SubscriptionTopic.eventTrigger`| _Equivalent_<br/>(48059/48060)| **`SubscriptionTopic.eventTrigger`**
| | | | | | | `SubscriptionTopic.eventTrigger.id`| _Equivalent_<br/>(48061/48062)| **`SubscriptionTopic.eventTrigger.id`**
| | | | | | | `SubscriptionTopic.eventTrigger.extension`| _Equivalent_<br/>(48063/48064)| **`SubscriptionTopic.eventTrigger.extension`**
| | | | | | | `SubscriptionTopic.eventTrigger.modifierExtension`| _Equivalent_<br/>(48065/48066)| **`SubscriptionTopic.eventTrigger.modifierExtension`**
| | | | | | | `SubscriptionTopic.eventTrigger.description`| _Equivalent_<br/>(48067/48068)| **`SubscriptionTopic.eventTrigger.description`**
| | | | | | | `SubscriptionTopic.eventTrigger.event`| _Equivalent_<br/>(48069/48070)| **`SubscriptionTopic.eventTrigger.event`**
| | | | | | | `SubscriptionTopic.eventTrigger.resource`| _Equivalent_<br/>(48071/48072)| **`SubscriptionTopic.eventTrigger.resource`**
| | | | | | | `SubscriptionTopic.canFilterBy`| _Equivalent_<br/>(48073/48074)| **`SubscriptionTopic.canFilterBy`**
| | | | | | | `SubscriptionTopic.canFilterBy.id`| _Equivalent_<br/>(48075/48076)| **`SubscriptionTopic.canFilterBy.id`**
| | | | | | | `SubscriptionTopic.canFilterBy.extension`| _Equivalent_<br/>(48077/48078)| **`SubscriptionTopic.canFilterBy.extension`**
| | | | | | | `SubscriptionTopic.canFilterBy.modifierExtension`| _Equivalent_<br/>(48079/48080)| **`SubscriptionTopic.canFilterBy.modifierExtension`**
| | | | | | | `SubscriptionTopic.canFilterBy.description`| _Equivalent_<br/>(48081/48082)| **`SubscriptionTopic.canFilterBy.description`**
| | | | | | | `SubscriptionTopic.canFilterBy.resource`| _Equivalent_<br/>(48083/48084)| **`SubscriptionTopic.canFilterBy.resource`**
| | | | | | | `SubscriptionTopic.canFilterBy.filterParameter`| _Equivalent_<br/>(48085/48086)| **`SubscriptionTopic.canFilterBy.filterParameter`**
| | | | | | | `SubscriptionTopic.canFilterBy.filterDefinition`| _Equivalent_<br/>(48087/48088)| **`SubscriptionTopic.canFilterBy.filterDefinition`**
| | | | | | | | | **`SubscriptionTopic.canFilterBy.comparator`**
| | | | | | | `SubscriptionTopic.canFilterBy.modifier`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(48089)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(48090)| **`SubscriptionTopic.canFilterBy.modifier`**
| | | | | | | `SubscriptionTopic.notificationShape`| _Equivalent_<br/>(48091/48092)| **`SubscriptionTopic.notificationShape`**
| | | | | | | `SubscriptionTopic.notificationShape.id`| _Equivalent_<br/>(48093/48094)| **`SubscriptionTopic.notificationShape.id`**
| | | | | | | `SubscriptionTopic.notificationShape.extension`| _Equivalent_<br/>(48095/48096)| **`SubscriptionTopic.notificationShape.extension`**
| | | | | | | `SubscriptionTopic.notificationShape.modifierExtension`| _Equivalent_<br/>(48097/48098)| **`SubscriptionTopic.notificationShape.modifierExtension`**
| | | | | | | `SubscriptionTopic.notificationShape.resource`| _Equivalent_<br/>(48099/48100)| **`SubscriptionTopic.notificationShape.resource`**
| | | | | | | `SubscriptionTopic.notificationShape.include`| _Equivalent_<br/>(48101/48102)| **`SubscriptionTopic.notificationShape.include`**
| | | | | | | `SubscriptionTopic.notificationShape.revInclude`| _Equivalent_<br/>(48103/48104)| **`SubscriptionTopic.notificationShape.revInclude`**
| | | | | | | *67 of 67 elements used* | | *71 of 71 elements used* 

