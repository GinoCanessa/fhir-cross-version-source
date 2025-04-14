Comparison of 
Generated at Monday, April 14, 2025 6:17:22 PM

### MessageDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | MessageDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/MessageDefinition` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for MessageDefinition Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `547` |
| Database Snapshot Count | `44` |
| Database Differential Count | `30` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `MessageDefinition` | `MessageDefinition` | `MessageDefinition` | MessageDefinition | A resource that defines a type of message that can be exchanged between systems | 0..* | MessageDefinition |  |  |
| `MessageDefinition.allowedResponse` | `MessageDefinition.allowedResponse` | `allowedResponse` |  | Responses to this message | 0..* | BackboneElement |  |  |
| `MessageDefinition.allowedResponse.extension` | `MessageDefinition.allowedResponse.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `MessageDefinition.allowedResponse.id` | `MessageDefinition.allowedResponse.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `MessageDefinition.allowedResponse.message` | `MessageDefinition.allowedResponse.message` | `message` |  | Reference to allowed message definition response | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/MessageDefinition) |  |  |
| `MessageDefinition.allowedResponse.modifierExtension` | `MessageDefinition.allowedResponse.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MessageDefinition.allowedResponse.situation` | `MessageDefinition.allowedResponse.situation` | `situation` |  | When should this response be used | 0..1 | markdown |  |  |
| `MessageDefinition.base` | `MessageDefinition.base` | `base` |  | Definition this one is based on | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/MessageDefinition) |  |  |
| `MessageDefinition.category` | `MessageDefinition.category` | `category` |  | Consequence \| Currency \| Notification | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/message-significance-category` |
| `MessageDefinition.contact` | `MessageDefinition.contact` | `contact` |  | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `MessageDefinition.contained` | `MessageDefinition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `MessageDefinition.copyright` | `MessageDefinition.copyright` | `copyright` |  | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `MessageDefinition.date` | `MessageDefinition.date` | `date` |  | Date this was last changed | 1..1 | dateTime |  |  |
| `MessageDefinition.description` | `MessageDefinition.description` | `description` |  | Natural language description of the message definition | 0..1 | markdown |  |  |
| `MessageDefinition.event` | `MessageDefinition.event` | `event` |  | Event type | 1..1 | Coding | `Example` | `http://hl7.org/fhir/ValueSet/message-events` |
| `MessageDefinition.experimental` | `MessageDefinition.experimental` | `experimental` |  | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `MessageDefinition.extension` | `MessageDefinition.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `MessageDefinition.focus` | `MessageDefinition.focus` | `focus` |  | Resource(s) that are the subject of the event | 0..* | BackboneElement |  |  |
| `MessageDefinition.focus.code` | `MessageDefinition.focus.code` | `code` |  | Type of resource | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/resource-types` |
| `MessageDefinition.focus.extension` | `MessageDefinition.focus.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `MessageDefinition.focus.id` | `MessageDefinition.focus.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `MessageDefinition.focus.max` | `MessageDefinition.focus.max` | `max` |  | Maximum number of focuses of this type | 0..1 | string |  |  |
| `MessageDefinition.focus.min` | `MessageDefinition.focus.min` | `min` |  | Minimum number of focuses of this type | 0..1 | unsignedInt |  |  |
| `MessageDefinition.focus.modifierExtension` | `MessageDefinition.focus.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MessageDefinition.focus.profile` | `MessageDefinition.focus.profile` | `profile` |  | Profile that must be adhered to by focus | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/StructureDefinition) |  |  |
| `MessageDefinition.id` | `MessageDefinition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `MessageDefinition.identifier` | `MessageDefinition.identifier` | `identifier` |  | Additional identifier for the message definition | 0..1 | Identifier |  |  |
| `MessageDefinition.implicitRules` | `MessageDefinition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `MessageDefinition.jurisdiction` | `MessageDefinition.jurisdiction` | `jurisdiction` |  | Intended jurisdiction for message definition (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `MessageDefinition.language` | `MessageDefinition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `MessageDefinition.meta` | `MessageDefinition.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `MessageDefinition.modifierExtension` | `MessageDefinition.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MessageDefinition.name` | `MessageDefinition.name` | `name` |  | Name for this message definition (computer friendly) | 0..1 | string |  |  |
| `MessageDefinition.parent` | `MessageDefinition.parent` | `parent` |  | Protocol/workflow this is part of | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ActivityDefinition), Reference(http://hl7.org/fhir/StructureDefinition/PlanDefinition) |  |  |
| `MessageDefinition.publisher` | `MessageDefinition.publisher` | `publisher` |  | Name of the publisher (organization or individual) | 0..1 | string |  |  |
| `MessageDefinition.purpose` | `MessageDefinition.purpose` | `purpose` |  | Why this message definition is defined | 0..1 | markdown |  |  |
| `MessageDefinition.replaces` | `MessageDefinition.replaces` | `replaces` |  | Takes the place of | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/MessageDefinition) |  |  |
| `MessageDefinition.responseRequired` | `MessageDefinition.responseRequired` | `responseRequired` |  | Is a response required? | 0..1 | boolean |  |  |
| `MessageDefinition.status` | `MessageDefinition.status` | `status` |  | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status` |
| `MessageDefinition.text` | `MessageDefinition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `MessageDefinition.title` | `MessageDefinition.title` | `title` |  | Name for this message definition (human friendly) | 0..1 | string |  |  |
| `MessageDefinition.url` | `MessageDefinition.url` | `url` |  | Logical URI to reference this message definition (globally unique) | 0..1 | uri |  |  |
| `MessageDefinition.useContext` | `MessageDefinition.useContext` | `useContext` |  | Context the content is intended to support | 0..* | UsageContext |  |  |
| `MessageDefinition.version` | `MessageDefinition.version` | `version` |  | Business version of the message definition | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [MessageDefinition](/docs/R3/Resources/MessageDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/MessageDefinition\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `484`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `678`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [MessageDefinition](/docs/R4/Resources/MessageDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/MessageDefinition\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1547`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1548`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [MessageDefinition](/docs/R4B/Resources/MessageDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/MessageDefinition\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1009`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1238`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [MessageDefinition](/docs/R5/Resources/MessageDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/MessageDefinition\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition MessageDefinition from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | R3 MessageDefinition| Relationship | [R4 MessageDefinition](/docs/R4/Resources/MessageDefinition.md)| Relationship | [R4B MessageDefinition](/docs/R4B/Resources/MessageDefinition.md)| Relationship | [R5 MessageDefinition](/docs/R5/Resources/MessageDefinition.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | **`MessageDefinition`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16104)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16105)| `MessageDefinition`| _Equivalent_<br/>(30106/30107)| `MessageDefinition`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(44893)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(44894)| `MessageDefinition`
| | | **`MessageDefinition.id`**| _Equivalent_<br/>(16106/16107)| `MessageDefinition.id`| _Equivalent_<br/>(30108/30109)| `MessageDefinition.id`| _Equivalent_<br/>(44895/44896)| `MessageDefinition.id`
| | | **`MessageDefinition.meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16108)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16109)| `MessageDefinition.meta`| _Equivalent_<br/>(30110/30111)| `MessageDefinition.meta`| _Equivalent_<br/>(44897/44898)| `MessageDefinition.meta`
| | | **`MessageDefinition.implicitRules`**| _Equivalent_<br/>(16110/16111)| `MessageDefinition.implicitRules`| _Equivalent_<br/>(30112/30113)| `MessageDefinition.implicitRules`| _Equivalent_<br/>(44899/44900)| `MessageDefinition.implicitRules`
| | | **`MessageDefinition.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16112)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(16113)| `MessageDefinition.language`| _Equivalent_<br/>(30114/30115)| `MessageDefinition.language`| _Equivalent_<br/>(44901/44902)| `MessageDefinition.language`
| | | **`MessageDefinition.text`**| _Equivalent_<br/>(16114/16115)| `MessageDefinition.text`| _Equivalent_<br/>(30116/30117)| `MessageDefinition.text`| _Equivalent_<br/>(44903/44904)| `MessageDefinition.text`
| | | **`MessageDefinition.contained`**| _Equivalent_<br/>(16116/16117)| `MessageDefinition.contained`| _Equivalent_<br/>(30118/30119)| `MessageDefinition.contained`| _Equivalent_<br/>(44905/44906)| `MessageDefinition.contained`
| | | **`MessageDefinition.extension`**| _Equivalent_<br/>(16118/16119)| `MessageDefinition.extension`| _Equivalent_<br/>(30120/30121)| `MessageDefinition.extension`| _Equivalent_<br/>(44907/44908)| `MessageDefinition.extension`
| | | **`MessageDefinition.modifierExtension`**| _Equivalent_<br/>(16120/16121)| `MessageDefinition.modifierExtension`| _Equivalent_<br/>(30122/30123)| `MessageDefinition.modifierExtension`| _Equivalent_<br/>(44909/44910)| `MessageDefinition.modifierExtension`
| | | **`MessageDefinition.url`**| _Equivalent_<br/>(16122/16123)| `MessageDefinition.url`| _Equivalent_<br/>(30124/30125)| `MessageDefinition.url`| _Equivalent_<br/>(44911/44912)| `MessageDefinition.url`
| | | **`MessageDefinition.identifier`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16124)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16125)| `MessageDefinition.identifier`| _Equivalent_<br/>(30126/30127)| `MessageDefinition.identifier`| _Equivalent_<br/>(44913/44914)| `MessageDefinition.identifier`
| | | **`MessageDefinition.version`**| _Equivalent_<br/>(16126/16127)| `MessageDefinition.version`| _Equivalent_<br/>(30128/30129)| `MessageDefinition.version`| _Equivalent_<br/>(44915/44916)| `MessageDefinition.version`
| | | **`MessageDefinition.name`**| _Equivalent_<br/>(16128/16129)| `MessageDefinition.name`| _Equivalent_<br/>(30130/30131)| `MessageDefinition.name`| _Equivalent_<br/>(44917/44918)| `MessageDefinition.name`
| | | **`MessageDefinition.title`**| _Equivalent_<br/>(16130/16131)| `MessageDefinition.title`| _Equivalent_<br/>(30132/30133)| `MessageDefinition.title`| _Equivalent_<br/>(44919/44920)| `MessageDefinition.title`
| | | **`MessageDefinition.status`**| _Equivalent_<br/>(16132/16133)| `MessageDefinition.status`| _Equivalent_<br/>(30136/30137)| `MessageDefinition.status`| _Equivalent_<br/>(44923/44924)| `MessageDefinition.status`
| | | **`MessageDefinition.experimental`**| _Equivalent_<br/>(16134/16135)| `MessageDefinition.experimental`| _Equivalent_<br/>(30138/30139)| `MessageDefinition.experimental`| _Equivalent_<br/>(44925/44926)| `MessageDefinition.experimental`
| | | **`MessageDefinition.date`**| _Equivalent_<br/>(16136/16137)| `MessageDefinition.date`| _Equivalent_<br/>(30140/30141)| `MessageDefinition.date`| _Equivalent_<br/>(44927/44928)| `MessageDefinition.date`
| | | **`MessageDefinition.publisher`**| _Equivalent_<br/>(16138/16139)| `MessageDefinition.publisher`| _Equivalent_<br/>(30142/30143)| `MessageDefinition.publisher`| _Equivalent_<br/>(44929/44930)| `MessageDefinition.publisher`
| | | **`MessageDefinition.contact`**| _Equivalent_<br/>(16140/16141)| `MessageDefinition.contact`| _Equivalent_<br/>(30144/30145)| `MessageDefinition.contact`| _Equivalent_<br/>(44931/44932)| `MessageDefinition.contact`
| | | **`MessageDefinition.description`**| _Equivalent_<br/>(16142/16143)| `MessageDefinition.description`| _Equivalent_<br/>(30146/30147)| `MessageDefinition.description`| _Equivalent_<br/>(44933/44934)| `MessageDefinition.description`
| | | **`MessageDefinition.useContext`**| _Equivalent_<br/>(16144/16145)| `MessageDefinition.useContext`| _Equivalent_<br/>(30148/30149)| `MessageDefinition.useContext`| _Equivalent_<br/>(44935/44936)| `MessageDefinition.useContext`
| | | **`MessageDefinition.jurisdiction`**| _Equivalent_<br/>(16146/16147)| `MessageDefinition.jurisdiction`| _Equivalent_<br/>(30150/30151)| `MessageDefinition.jurisdiction`| _Equivalent_<br/>(44937/44938)| `MessageDefinition.jurisdiction`
| | | **`MessageDefinition.purpose`**| _Equivalent_<br/>(16148/16149)| `MessageDefinition.purpose`| _Equivalent_<br/>(30152/30153)| `MessageDefinition.purpose`| _Equivalent_<br/>(44939/44940)| `MessageDefinition.purpose`
| | | **`MessageDefinition.copyright`**| _Equivalent_<br/>(16150/16151)| `MessageDefinition.copyright`| _Equivalent_<br/>(30154/30155)| `MessageDefinition.copyright`| _Equivalent_<br/>(44941/44942)| `MessageDefinition.copyright`
| | | **`MessageDefinition.base`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(16152)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16153)| `MessageDefinition.base`| _Equivalent_<br/>(30156/30157)| `MessageDefinition.base`| _Equivalent_<br/>(44943/44944)| `MessageDefinition.base`
| | | **`MessageDefinition.parent`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(16154)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16155)| `MessageDefinition.parent`| _Equivalent_<br/>(30158/30159)| `MessageDefinition.parent`| _Equivalent_<br/>(44945/44946)| `MessageDefinition.parent`
| | | **`MessageDefinition.replaces`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(16156)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16157)| `MessageDefinition.replaces`| _Equivalent_<br/>(30134/30135)| `MessageDefinition.replaces`| _Equivalent_<br/>(44921/44922)| `MessageDefinition.replaces`
| | | **`MessageDefinition.event`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1198)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1609)| `MessageDefinition.event[x]`| _Equivalent_<br/>(30160/30161)| `MessageDefinition.event[x]`| _Equivalent_<br/>(44947/44948)| `MessageDefinition.event[x]`
| | | **`MessageDefinition.category`**| _Equivalent_<br/>(16158/16159)| `MessageDefinition.category`| _Equivalent_<br/>(30162/30163)| `MessageDefinition.category`| _Equivalent_<br/>(44949/44950)| `MessageDefinition.category`
| | | **`MessageDefinition.focus`**| _Equivalent_<br/>(16160/16161)| `MessageDefinition.focus`| _Equivalent_<br/>(30164/30165)| `MessageDefinition.focus`| _Equivalent_<br/>(44951/44952)| `MessageDefinition.focus`
| | | **`MessageDefinition.focus.id`**| _Equivalent_<br/>(16162/16163)| `MessageDefinition.focus.id`| _Equivalent_<br/>(30166/30167)| `MessageDefinition.focus.id`| _Equivalent_<br/>(44953/44954)| `MessageDefinition.focus.id`
| | | **`MessageDefinition.focus.extension`**| _Equivalent_<br/>(16164/16165)| `MessageDefinition.focus.extension`| _Equivalent_<br/>(30168/30169)| `MessageDefinition.focus.extension`| _Equivalent_<br/>(44955/44956)| `MessageDefinition.focus.extension`
| | | **`MessageDefinition.focus.modifierExtension`**| _Equivalent_<br/>(16166/16167)| `MessageDefinition.focus.modifierExtension`| _Equivalent_<br/>(30170/30171)| `MessageDefinition.focus.modifierExtension`| _Equivalent_<br/>(44957/44958)| `MessageDefinition.focus.modifierExtension`
| | | **`MessageDefinition.focus.code`**| →→→→ _Equivalent_ →→→→ <br/>(16168)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16169)| `MessageDefinition.focus.code`| →→→→ _Equivalent_ →→→→ <br/>(30172)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(30173)| `MessageDefinition.focus.code`| →→→→ _Equivalent_ →→→→ <br/>(44959)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(44960)| `MessageDefinition.focus.code`
| | | **`MessageDefinition.focus.profile`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(16170)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16171)| `MessageDefinition.focus.profile`| _Equivalent_<br/>(30174/30175)| `MessageDefinition.focus.profile`| _Equivalent_<br/>(44961/44962)| `MessageDefinition.focus.profile`
| | | **`MessageDefinition.focus.min`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16172)<hr/>←←←← _Equivalent_ ←←←← <br/>(16173)| `MessageDefinition.focus.min`| _Equivalent_<br/>(30176/30177)| `MessageDefinition.focus.min`| _Equivalent_<br/>(44963/44964)| `MessageDefinition.focus.min`
| | | **`MessageDefinition.focus.max`**| _Equivalent_<br/>(16174/16175)| `MessageDefinition.focus.max`| _Equivalent_<br/>(30178/30179)| `MessageDefinition.focus.max`| _Equivalent_<br/>(44965/44966)| `MessageDefinition.focus.max`
| | | **`MessageDefinition.responseRequired`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16176)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(16177)| `MessageDefinition.responseRequired`| _Equivalent_<br/>(30180/30181)| `MessageDefinition.responseRequired`| _Equivalent_<br/>(44967/44968)| `MessageDefinition.responseRequired`
| | | **`MessageDefinition.allowedResponse`**| _Equivalent_<br/>(16178/16179)| `MessageDefinition.allowedResponse`| _Equivalent_<br/>(30182/30183)| `MessageDefinition.allowedResponse`| _Equivalent_<br/>(44969/44970)| `MessageDefinition.allowedResponse`
| | | **`MessageDefinition.allowedResponse.id`**| _Equivalent_<br/>(16180/16181)| `MessageDefinition.allowedResponse.id`| _Equivalent_<br/>(30184/30185)| `MessageDefinition.allowedResponse.id`| _Equivalent_<br/>(44971/44972)| `MessageDefinition.allowedResponse.id`
| | | **`MessageDefinition.allowedResponse.extension`**| _Equivalent_<br/>(16182/16183)| `MessageDefinition.allowedResponse.extension`| _Equivalent_<br/>(30186/30187)| `MessageDefinition.allowedResponse.extension`| _Equivalent_<br/>(44973/44974)| `MessageDefinition.allowedResponse.extension`
| | | **`MessageDefinition.allowedResponse.modifierExtension`**| _Equivalent_<br/>(16184/16185)| `MessageDefinition.allowedResponse.modifierExtension`| _Equivalent_<br/>(30188/30189)| `MessageDefinition.allowedResponse.modifierExtension`| _Equivalent_<br/>(44975/44976)| `MessageDefinition.allowedResponse.modifierExtension`
| | | **`MessageDefinition.allowedResponse.message`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(16186)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16187)| `MessageDefinition.allowedResponse.message`| _Equivalent_<br/>(30190/30191)| `MessageDefinition.allowedResponse.message`| _Equivalent_<br/>(44977/44978)| `MessageDefinition.allowedResponse.message`
| | | **`MessageDefinition.allowedResponse.situation`**| _Equivalent_<br/>(16188/16189)| `MessageDefinition.allowedResponse.situation`| _Equivalent_<br/>(30192/30193)| `MessageDefinition.allowedResponse.situation`| _Equivalent_<br/>(44979/44980)| `MessageDefinition.allowedResponse.situation`
| | | *44 of 44 elements used* | | *44 of 45 elements used* <br/>remaining elements:<br/>`MessageDefinition.graph`| | *44 of 45 elements used* <br/>remaining elements:<br/>`MessageDefinition.graph`| | *44 of 47 elements used* <br/>remaining elements:<br/>`MessageDefinition.copyrightLabel`, `MessageDefinition.graph`, `MessageDefinition.versionAlgorithm[x]`

