Comparison of 
Generated at Friday, April 4, 2025 2:58:34 PM

### AuditEvent

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | AuditEvent |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/AuditEvent` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for AuditEvent Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `45` |
| Database Snapshot Count | `66` |
| Database Differential Count | `40` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `AuditEvent` | `AuditEvent` | `AuditEvent` | AuditEvent | Event record kept for security purposes | 0..* | AuditEvent |  |  |
| `AuditEvent.contained` | `AuditEvent.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `AuditEvent.event` | `AuditEvent.event` | `event` |  | What was done | 1..1 | BackboneElement |  |  |
| `AuditEvent.event.action` | `AuditEvent.event.action` | `action` |  | Type of action performed during the event | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/audit-event-action` |
| `AuditEvent.event.dateTime` | `AuditEvent.event.dateTime` | `dateTime` |  | Time when the event occurred on source | 1..1 | instant |  |  |
| `AuditEvent.event.extension` | `AuditEvent.event.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `AuditEvent.event.id` | `AuditEvent.event.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `AuditEvent.event.modifierExtension` | `AuditEvent.event.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `AuditEvent.event.outcome` | `AuditEvent.event.outcome` | `outcome` |  | Whether the event succeeded or failed | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/audit-event-outcome` |
| `AuditEvent.event.outcomeDesc` | `AuditEvent.event.outcomeDesc` | `outcomeDesc` |  | Description of the event outcome | 0..1 | string |  |  |
| `AuditEvent.event.purposeOfEvent` | `AuditEvent.event.purposeOfEvent` | `purposeOfEvent` |  | The purposeOfUse of the event | 0..* | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/v3-PurposeOfUse` |
| `AuditEvent.event.subtype` | `AuditEvent.event.subtype` | `subtype` |  | More specific type/id for the event | 0..* | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/audit-event-sub-type` |
| `AuditEvent.event.type` | `AuditEvent.event.type` | `type` |  | Type/identifier of event | 1..1 | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/audit-event-type` |
| `AuditEvent.extension` | `AuditEvent.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `AuditEvent.id` | `AuditEvent.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `AuditEvent.implicitRules` | `AuditEvent.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `AuditEvent.language` | `AuditEvent.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `AuditEvent.meta` | `AuditEvent.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `AuditEvent.modifierExtension` | `AuditEvent.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `AuditEvent.object` | `AuditEvent.object` | `object` |  | Specific instances of data or objects that have been accessed | 0..* | BackboneElement |  |  |
| `AuditEvent.object.description` | `AuditEvent.object.description` | `description` |  | Descriptive text | 0..1 | string |  |  |
| `AuditEvent.object.detail` | `AuditEvent.object.detail` | `detail` |  | Additional Information about the Object | 0..* | BackboneElement |  |  |
| `AuditEvent.object.detail.extension` | `AuditEvent.object.detail.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `AuditEvent.object.detail.id` | `AuditEvent.object.detail.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `AuditEvent.object.detail.modifierExtension` | `AuditEvent.object.detail.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `AuditEvent.object.detail.type` | `AuditEvent.object.detail.type` | `type` |  | Name of the property | 1..1 | string |  |  |
| `AuditEvent.object.detail.value` | `AuditEvent.object.detail.value` | `value` |  | Property value | 1..1 | base64Binary |  |  |
| `AuditEvent.object.extension` | `AuditEvent.object.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `AuditEvent.object.id` | `AuditEvent.object.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `AuditEvent.object.identifier` | `AuditEvent.object.identifier` | `identifier` |  | Specific instance of object (e.g. versioned) | 0..1 | Identifier |  |  |
| `AuditEvent.object.lifecycle` | `AuditEvent.object.lifecycle` | `lifecycle` |  | Life-cycle stage for the object | 0..1 | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/object-lifecycle` |
| `AuditEvent.object.modifierExtension` | `AuditEvent.object.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `AuditEvent.object.name` | `AuditEvent.object.name` | `name` |  | Instance-specific descriptor for Object | 0..1 | string |  |  |
| `AuditEvent.object.query` | `AuditEvent.object.query` | `query` |  | Actual query for object | 0..1 | base64Binary |  |  |
| `AuditEvent.object.reference` | `AuditEvent.object.reference` | `reference` |  | Specific instance of resource (e.g. versioned) | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `AuditEvent.object.role` | `AuditEvent.object.role` | `role` |  | What role the Object played | 0..1 | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/object-role` |
| `AuditEvent.object.securityLabel` | `AuditEvent.object.securityLabel` | `securityLabel` |  | Security labels applied to the object | 0..* | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/security-labels` |
| `AuditEvent.object.type` | `AuditEvent.object.type` | `type` |  | Type of object involved | 0..1 | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/object-type` |
| `AuditEvent.participant` | `AuditEvent.participant` | `participant` |  | A person, a hardware device or software process | 1..* | BackboneElement |  |  |
| `AuditEvent.participant.altId` | `AuditEvent.participant.altId` | `altId` |  | Alternative User id e.g. authentication | 0..1 | string |  |  |
| `AuditEvent.participant.extension` | `AuditEvent.participant.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `AuditEvent.participant.id` | `AuditEvent.participant.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `AuditEvent.participant.location` | `AuditEvent.participant.location` | `location` |  | Where | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `AuditEvent.participant.media` | `AuditEvent.participant.media` | `media` |  | Type of media | 0..1 | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/dicm-405-mediatype` |
| `AuditEvent.participant.modifierExtension` | `AuditEvent.participant.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `AuditEvent.participant.name` | `AuditEvent.participant.name` | `name` |  | Human-meaningful name for the user | 0..1 | string |  |  |
| `AuditEvent.participant.network` | `AuditEvent.participant.network` | `network` |  | Logical network location for application activity | 0..1 | BackboneElement |  |  |
| `AuditEvent.participant.network.address` | `AuditEvent.participant.network.address` | `address` |  | Identifier for the network access point of the user device | 0..1 | string |  |  |
| `AuditEvent.participant.network.extension` | `AuditEvent.participant.network.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `AuditEvent.participant.network.id` | `AuditEvent.participant.network.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `AuditEvent.participant.network.modifierExtension` | `AuditEvent.participant.network.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `AuditEvent.participant.network.type` | `AuditEvent.participant.network.type` | `type` |  | The type of network access point | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/network-type` |
| `AuditEvent.participant.policy` | `AuditEvent.participant.policy` | `policy` |  | Policy that authorized event | 0..* | uri |  |  |
| `AuditEvent.participant.purposeOfUse` | `AuditEvent.participant.purposeOfUse` | `purposeOfUse` |  | Reason given for this user | 0..* | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/v3-PurposeOfUse` |
| `AuditEvent.participant.reference` | `AuditEvent.participant.reference` | `reference` |  | Direct reference to resource | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `AuditEvent.participant.requestor` | `AuditEvent.participant.requestor` | `requestor` |  | Whether user is initiator | 1..1 | boolean |  |  |
| `AuditEvent.participant.role` | `AuditEvent.participant.role` | `role` |  | User roles (e.g. local RBAC codes) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/dicm-402-roleid` |
| `AuditEvent.participant.userId` | `AuditEvent.participant.userId` | `userId` |  | Unique identifier for the user | 0..1 | Identifier |  |  |
| `AuditEvent.source` | `AuditEvent.source` | `source` |  | Application systems and processes | 1..1 | BackboneElement |  |  |
| `AuditEvent.source.extension` | `AuditEvent.source.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `AuditEvent.source.id` | `AuditEvent.source.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `AuditEvent.source.identifier` | `AuditEvent.source.identifier` | `identifier` |  | The identity of source detecting the event | 1..1 | Identifier |  |  |
| `AuditEvent.source.modifierExtension` | `AuditEvent.source.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `AuditEvent.source.site` | `AuditEvent.source.site` | `site` |  | Logical source location within the enterprise | 0..1 | string |  |  |
| `AuditEvent.source.type` | `AuditEvent.source.type` | `type` |  | The type of source where event originated | 0..* | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/audit-source-type` |
| `AuditEvent.text` | `AuditEvent.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [AuditEvent](/docs/R2/Resources/AuditEvent.md)<br/> `http://hl7.org/fhir/StructureDefinition/AuditEvent\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `76`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `242`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AuditEvent](/docs/R3/Resources/AuditEvent.md)<br/> `http://hl7.org/fhir/StructureDefinition/AuditEvent\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `421`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `617`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AuditEvent](/docs/R4/Resources/AuditEvent.md)<br/> `http://hl7.org/fhir/StructureDefinition/AuditEvent\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1399`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1400`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AuditEvent](/docs/R4B/Resources/AuditEvent.md)<br/> `http://hl7.org/fhir/StructureDefinition/AuditEvent\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `935`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1164`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AuditEvent](/docs/R5/Resources/AuditEvent.md)<br/> `http://hl7.org/fhir/StructureDefinition/AuditEvent\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition AuditEvent from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 AuditEvent| Relationship | [R3 AuditEvent](/docs/R3/Resources/AuditEvent.md)| Relationship | [R4 AuditEvent](/docs/R4/Resources/AuditEvent.md)| Relationship | [R4B AuditEvent](/docs/R4B/Resources/AuditEvent.md)| Relationship | [R5 AuditEvent](/docs/R5/Resources/AuditEvent.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`AuditEvent`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3071)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3072)| `AuditEvent`| _Equivalent_<br/>(10296/10297)| `AuditEvent`| _Equivalent_<br/>(21850/21851)| `AuditEvent`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(36951)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36952)| `AuditEvent`
| **`AuditEvent.id`**| _Equivalent_<br/>(3073/3074)| `AuditEvent.id`| _Equivalent_<br/>(10298/10299)| `AuditEvent.id`| _Equivalent_<br/>(21852/21853)| `AuditEvent.id`| _Equivalent_<br/>(36953/36954)| `AuditEvent.id`
| **`AuditEvent.meta`**| _Equivalent_<br/>(3075/3076)| `AuditEvent.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10300)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10301)| `AuditEvent.meta`| _Equivalent_<br/>(21854/21855)| `AuditEvent.meta`| _Equivalent_<br/>(36955/36956)| `AuditEvent.meta`
| **`AuditEvent.implicitRules`**| _Equivalent_<br/>(3077/3078)| `AuditEvent.implicitRules`| _Equivalent_<br/>(10302/10303)| `AuditEvent.implicitRules`| _Equivalent_<br/>(21856/21857)| `AuditEvent.implicitRules`| _Equivalent_<br/>(36957/36958)| `AuditEvent.implicitRules`
| **`AuditEvent.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3079)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(3080)| `AuditEvent.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10304)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(10305)| `AuditEvent.language`| _Equivalent_<br/>(21858/21859)| `AuditEvent.language`| _Equivalent_<br/>(36959/36960)| `AuditEvent.language`
| **`AuditEvent.text`**| _Equivalent_<br/>(3081/3082)| `AuditEvent.text`| _Equivalent_<br/>(10306/10307)| `AuditEvent.text`| _Equivalent_<br/>(21860/21861)| `AuditEvent.text`| _Equivalent_<br/>(36961/36962)| `AuditEvent.text`
| **`AuditEvent.contained`**| _Equivalent_<br/>(3083/3084)| `AuditEvent.contained`| _Equivalent_<br/>(10308/10309)| `AuditEvent.contained`| _Equivalent_<br/>(21862/21863)| `AuditEvent.contained`| _Equivalent_<br/>(36963/36964)| `AuditEvent.contained`
| **`AuditEvent.extension`**| _Equivalent_<br/>(3085/3086)| `AuditEvent.extension`| _Equivalent_<br/>(10310/10311)| `AuditEvent.extension`| _Equivalent_<br/>(21864/21865)| `AuditEvent.extension`| _Equivalent_<br/>(36965/36966)| `AuditEvent.extension`
| **`AuditEvent.modifierExtension`**| _Equivalent_<br/>(3087/3088)| `AuditEvent.modifierExtension`| _Equivalent_<br/>(10312/10313)| `AuditEvent.modifierExtension`| _Equivalent_<br/>(21866/21867)| `AuditEvent.modifierExtension`| _Equivalent_<br/>(36967/36968)| `AuditEvent.modifierExtension`
| **`AuditEvent.event`**| →→→→ _RelatedTo_ →→→→ <br/>(13)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(468)| `AuditEvent`| _Equivalent_<br/>(10296/10297)| `AuditEvent`| _Equivalent_<br/>(21850/21851)| `AuditEvent`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(36951)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36952)| `AuditEvent`
| **`AuditEvent.event.id`**| | | | | | | | | 
| **`AuditEvent.event.extension`**| | | | | | | | | 
| **`AuditEvent.event.modifierExtension`**| | | | | | | | | 
| **`AuditEvent.event.type`**| _Equivalent_<br/>(20/502)| `AuditEvent.type`| _Equivalent_<br/>(10314/10315)| `AuditEvent.type`| _Equivalent_<br/>(21868/21869)| `AuditEvent.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1724)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1968)| `AuditEvent.category`
| **`AuditEvent.event.subtype`**| _Equivalent_<br/>(19/501)| `AuditEvent.subtype`| _Equivalent_<br/>(10316/10317)| `AuditEvent.subtype`| _Equivalent_<br/>(21870/21871)| `AuditEvent.subtype`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1725)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1969)| `AuditEvent.code`
| **`AuditEvent.event.action`**| _Equivalent_<br/>(14/469)| `AuditEvent.action`| _Equivalent_<br/>(10318/10319)| `AuditEvent.action`| _Equivalent_<br/>(21872/21873)| `AuditEvent.action`| _Equivalent_<br/>(36969/36970)| `AuditEvent.action`
| **`AuditEvent.event.dateTime`**| _Equivalent_<br/>(15/500)| `AuditEvent.recorded`| _Equivalent_<br/>(10320/10321)| `AuditEvent.recorded`| _Equivalent_<br/>(21876/21877)| `AuditEvent.recorded`| _Equivalent_<br/>(36972/36973)| `AuditEvent.recorded`
| **`AuditEvent.event.outcome`**| _Equivalent_<br/>(16/497)| `AuditEvent.outcome`| _Equivalent_<br/>(10322/10323)| `AuditEvent.outcome`| _Equivalent_<br/>(21878/21879)| `AuditEvent.outcome`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36974)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36975)| `AuditEvent.outcome`
| **`AuditEvent.event.outcomeDesc`**| _Equivalent_<br/>(17/498)| `AuditEvent.outcomeDesc`| _Equivalent_<br/>(10324/10325)| `AuditEvent.outcomeDesc`| _Equivalent_<br/>(21880/21881)| `AuditEvent.outcomeDesc`| | | 
| **`AuditEvent.event.purposeOfEvent`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(18)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(499)| `AuditEvent.purposeOfEvent`| _Equivalent_<br/>(10326/10327)| `AuditEvent.purposeOfEvent`| _Equivalent_<br/>(21882/21883)| `AuditEvent.purposeOfEvent`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1726)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1970)| `AuditEvent.authorization`
| **`AuditEvent.participant`**| _Equivalent_<br/>(34/470)| `AuditEvent.agent`| _Equivalent_<br/>(10328/10329)| `AuditEvent.agent`| _Equivalent_<br/>(21884/21885)| `AuditEvent.agent`| _Equivalent_<br/>(36977/36978)| `AuditEvent.agent`
| **`AuditEvent.participant.id`**| | | | | | | | | 
| **`AuditEvent.participant.extension`**| | | | | | | | | 
| **`AuditEvent.participant.modifierExtension`**| | | | | | | | | 
| **`AuditEvent.participant.role`**| _Equivalent_<br/>(46/482)| `AuditEvent.agent.role`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10336)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10337)| `AuditEvent.agent.role`| _Equivalent_<br/>(21894/21895)| `AuditEvent.agent.role`| _Equivalent_<br/>(36987/36988)| `AuditEvent.agent.role`
| **`AuditEvent.participant.reference`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(44)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(480)| `AuditEvent.agent.reference`| →→→→ _RelatedTo_ →→→→ <br/>(814)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1352)| `AuditEvent.agent.who`| _Equivalent_<br/>(21896/21897)| `AuditEvent.agent.who`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36989)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36990)| `AuditEvent.agent.who`
| **`AuditEvent.participant.userId`**| _Equivalent_<br/>(47/483)| `AuditEvent.agent.userId`| →→→→ _Equivalent_ →→→→ <br/>(21849)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1353)| `base64Binary`| | | | | 
| **`AuditEvent.participant.userId`**| _Equivalent_<br/>(47/483)| `AuditEvent.agent.userId`| →→→→ _Equivalent_ →→→→ <br/>(21849)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1353)| `AuditEvent.agent.who`| _Equivalent_<br/>(21896/21897)| `AuditEvent.agent.who`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36989)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36990)| `AuditEvent.agent.who`
| **`AuditEvent.participant.altId`**| _Equivalent_<br/>(35/471)| `AuditEvent.agent.altId`| _Equivalent_<br/>(10338/10339)| `AuditEvent.agent.altId`| _Equivalent_<br/>(21898/21899)| `AuditEvent.agent.altId`| | | 
| **`AuditEvent.participant.name`**| _Equivalent_<br/>(38/474)| `AuditEvent.agent.name`| _Equivalent_<br/>(10340/10341)| `AuditEvent.agent.name`| _Equivalent_<br/>(21900/21901)| `AuditEvent.agent.name`| | | 
| **`AuditEvent.participant.requestor`**| _Equivalent_<br/>(45/481)| `AuditEvent.agent.requestor`| _Equivalent_<br/>(10342/10343)| `AuditEvent.agent.requestor`| _Equivalent_<br/>(21902/21903)| `AuditEvent.agent.requestor`| →→→→ _Equivalent_ →→→→ <br/>(36993)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36994)| `AuditEvent.agent.requestor`
| **`AuditEvent.participant.location`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(472)| `AuditEvent.agent.location`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10344)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10345)| `AuditEvent.agent.location`| _Equivalent_<br/>(21904/21905)| `AuditEvent.agent.location`| _Equivalent_<br/>(36995/36996)| `AuditEvent.agent.location`
| **`AuditEvent.participant.policy`**| _Equivalent_<br/>(42/478)| `AuditEvent.agent.policy`| _Equivalent_<br/>(10346/10347)| `AuditEvent.agent.policy`| _Equivalent_<br/>(21906/21907)| `AuditEvent.agent.policy`| _Equivalent_<br/>(36997/36998)| `AuditEvent.agent.policy`
| **`AuditEvent.participant.media`**| _Equivalent_<br/>(37/473)| `AuditEvent.agent.media`| _Equivalent_<br/>(10348/10349)| `AuditEvent.agent.media`| _Equivalent_<br/>(21908/21909)| `AuditEvent.agent.media`| | | 
| **`AuditEvent.participant.network`**| _Equivalent_<br/>(39/475)| `AuditEvent.agent.network`| _Equivalent_<br/>(10350/10351)| `AuditEvent.agent.network`| _Equivalent_<br/>(21910/21911)| `AuditEvent.agent.network`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1727)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1971)| `AuditEvent.agent.network[x]`
| **`AuditEvent.participant.network.id`**| | | | | | | | | 
| **`AuditEvent.participant.network.extension`**| | | | | | | | | 
| **`AuditEvent.participant.network.modifierExtension`**| | | | | | | | | 
| **`AuditEvent.participant.network.address`**| _Equivalent_<br/>(40/476)| `AuditEvent.agent.network.address`| _Equivalent_<br/>(10358/10359)| `AuditEvent.agent.network.address`| _Equivalent_<br/>(21918/21919)| `AuditEvent.agent.network.address`| | | 
| **`AuditEvent.participant.network.type`**| _Equivalent_<br/>(41/477)| `AuditEvent.agent.network.type`| _Equivalent_<br/>(10360/10361)| `AuditEvent.agent.network.type`| _Equivalent_<br/>(21920/21921)| `AuditEvent.agent.network.type`| | | 
| **`AuditEvent.participant.purposeOfUse`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(43)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(479)| `AuditEvent.agent.purposeOfUse`| _Equivalent_<br/>(10362/10363)| `AuditEvent.agent.purposeOfUse`| _Equivalent_<br/>(21922/21923)| `AuditEvent.agent.purposeOfUse`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1728)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1972)| `AuditEvent.agent.authorization`
| **`AuditEvent.source`**| _Equivalent_<br/>(3098/3099)| `AuditEvent.source`| _Equivalent_<br/>(10364/10365)| `AuditEvent.source`| _Equivalent_<br/>(21924/21925)| `AuditEvent.source`| _Equivalent_<br/>(37005/37006)| `AuditEvent.source`
| **`AuditEvent.source.id`**| _Equivalent_<br/>(3100/3101)| `AuditEvent.source.id`| _Equivalent_<br/>(10366/10367)| `AuditEvent.source.id`| _Equivalent_<br/>(21926/21927)| `AuditEvent.source.id`| _Equivalent_<br/>(37007/37008)| `AuditEvent.source.id`
| **`AuditEvent.source.extension`**| _Equivalent_<br/>(3102/3103)| `AuditEvent.source.extension`| _Equivalent_<br/>(10368/10369)| `AuditEvent.source.extension`| _Equivalent_<br/>(21928/21929)| `AuditEvent.source.extension`| _Equivalent_<br/>(37009/37010)| `AuditEvent.source.extension`
| **`AuditEvent.source.modifierExtension`**| _Equivalent_<br/>(3104/3105)| `AuditEvent.source.modifierExtension`| _Equivalent_<br/>(10370/10371)| `AuditEvent.source.modifierExtension`| _Equivalent_<br/>(21930/21931)| `AuditEvent.source.modifierExtension`| _Equivalent_<br/>(37011/37012)| `AuditEvent.source.modifierExtension`
| **`AuditEvent.source.site`**| _Equivalent_<br/>(3106/3107)| `AuditEvent.source.site`| _Equivalent_<br/>(10372/10373)| `AuditEvent.source.site`| _Equivalent_<br/>(21932/21933)| `AuditEvent.source.site`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(37013)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(37014)| `AuditEvent.source.site`
| **`AuditEvent.source.identifier`**| _Equivalent_<br/>(3108/3109)| `AuditEvent.source.identifier`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(819)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1355)| `AuditEvent.source.observer`| _Equivalent_<br/>(21934/21935)| `AuditEvent.source.observer`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(37015)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(37016)| `AuditEvent.source.observer`
| **`AuditEvent.source.type`**| _Equivalent_<br/>(3110/3111)| `AuditEvent.source.type`| _Equivalent_<br/>(10374/10375)| `AuditEvent.source.type`| _Equivalent_<br/>(21936/21937)| `AuditEvent.source.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(37017)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(37018)| `AuditEvent.source.type`
| **`AuditEvent.object`**| _Equivalent_<br/>(21/484)| `AuditEvent.entity`| _Equivalent_<br/>(10376/10377)| `AuditEvent.entity`| _Equivalent_<br/>(21938/21939)| `AuditEvent.entity`| _Equivalent_<br/>(37019/37020)| `AuditEvent.entity`
| **`AuditEvent.object.id`**| | | | | | | | | 
| **`AuditEvent.object.extension`**| | | | | | | | | 
| **`AuditEvent.object.modifierExtension`**| | | | | | | | | 
| **`AuditEvent.object.identifier`**| _Equivalent_<br/>(26/489)| `AuditEvent.entity.identifier`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(817)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1356)| `AuditEvent.entity.what`| _Equivalent_<br/>(21946/21947)| `AuditEvent.entity.what`| _Equivalent_<br/>(37027/37028)| `AuditEvent.entity.what`
| **`AuditEvent.object.reference`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(30)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(493)| `AuditEvent.entity.reference`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(818)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1357)| `AuditEvent.entity.what`| _Equivalent_<br/>(21946/21947)| `AuditEvent.entity.what`| _Equivalent_<br/>(37027/37028)| `AuditEvent.entity.what`
| **`AuditEvent.object.type`**| _Equivalent_<br/>(33/496)| `AuditEvent.entity.type`| _Equivalent_<br/>(10384/10385)| `AuditEvent.entity.type`| _Equivalent_<br/>(21948/21949)| `AuditEvent.entity.type`| | | 
| **`AuditEvent.object.role`**| _Equivalent_<br/>(31/494)| `AuditEvent.entity.role`| _Equivalent_<br/>(10386/10387)| `AuditEvent.entity.role`| _Equivalent_<br/>(21950/21951)| `AuditEvent.entity.role`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(37030)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(37031)| `AuditEvent.entity.role`
| **`AuditEvent.object.lifecycle`**| _Equivalent_<br/>(27/490)| `AuditEvent.entity.lifecycle`| _Equivalent_<br/>(10388/10389)| `AuditEvent.entity.lifecycle`| _Equivalent_<br/>(21952/21953)| `AuditEvent.entity.lifecycle`| | | 
| **`AuditEvent.object.securityLabel`**| _Equivalent_<br/>(32/495)| `AuditEvent.entity.securityLabel`| _Equivalent_<br/>(10390/10391)| `AuditEvent.entity.securityLabel`| _Equivalent_<br/>(21954/21955)| `AuditEvent.entity.securityLabel`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(37033)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(37034)| `AuditEvent.entity.securityLabel`
| **`AuditEvent.object.name`**| _Equivalent_<br/>(28/491)| `AuditEvent.entity.name`| _Equivalent_<br/>(10392/10393)| `AuditEvent.entity.name`| _Equivalent_<br/>(21956/21957)| `AuditEvent.entity.name`| | | 
| **`AuditEvent.object.description`**| _Equivalent_<br/>(22/485)| `AuditEvent.entity.description`| _Equivalent_<br/>(10394/10395)| `AuditEvent.entity.description`| _Equivalent_<br/>(21958/21959)| `AuditEvent.entity.description`| | | 
| **`AuditEvent.object.query`**| _Equivalent_<br/>(29/492)| `AuditEvent.entity.query`| _Equivalent_<br/>(10396/10397)| `AuditEvent.entity.query`| _Equivalent_<br/>(21960/21961)| `AuditEvent.entity.query`| _Equivalent_<br/>(37037/37038)| `AuditEvent.entity.query`
| **`AuditEvent.object.detail`**| _Equivalent_<br/>(23/486)| `AuditEvent.entity.detail`| _Equivalent_<br/>(10398/10399)| `AuditEvent.entity.detail`| _Equivalent_<br/>(21962/21963)| `AuditEvent.entity.detail`| _Equivalent_<br/>(37039/37040)| `AuditEvent.entity.detail`
| **`AuditEvent.object.detail.id`**| | | | | | | | | 
| **`AuditEvent.object.detail.extension`**| | | | | | | | | 
| **`AuditEvent.object.detail.modifierExtension`**| | | | | | | | | 
| **`AuditEvent.object.detail.type`**| _Equivalent_<br/>(24/487)| `AuditEvent.entity.detail.type`| _Equivalent_<br/>(10406/10407)| `AuditEvent.entity.detail.type`| _Equivalent_<br/>(21970/21971)| `AuditEvent.entity.detail.type`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(37047)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(37048)| `AuditEvent.entity.detail.type`
| **`AuditEvent.object.detail.value`**| _Equivalent_<br/>(25/488)| `AuditEvent.entity.detail.value`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(816)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1354)| `AuditEvent.entity.detail.value[x]`| _Equivalent_<br/>(21972/21973)| `AuditEvent.entity.detail.value[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(37049)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(37050)| `AuditEvent.entity.detail.value[x]`
| *66 of 66 elements used* | | *50 of 62 elements used* <br/>remaining elements:<br/>`AuditEvent.agent.extension`, `AuditEvent.agent.id`, `AuditEvent.agent.modifierExtension`, `AuditEvent.agent.network.extension`, `AuditEvent.agent.network.id`, `AuditEvent.agent.network.modifierExtension`, `AuditEvent.entity.detail.extension`, `AuditEvent.entity.detail.id`, `AuditEvent.entity.detail.modifierExtension`, `AuditEvent.entity.extension`, `AuditEvent.entity.id`, `AuditEvent.entity.modifierExtension`| | *49 of 62 elements used* <br/>remaining elements:<br/>`AuditEvent.agent.extension`, `AuditEvent.agent.id`, `AuditEvent.agent.modifierExtension`, `AuditEvent.agent.network.extension`, `AuditEvent.agent.network.id`, `AuditEvent.agent.network.modifierExtension`, `AuditEvent.agent.type`, `AuditEvent.entity.detail.extension`, `AuditEvent.entity.detail.id`, `AuditEvent.entity.detail.modifierExtension`, `AuditEvent.entity.extension`, `AuditEvent.entity.id`, `AuditEvent.entity.modifierExtension`, `AuditEvent.period`| | *48 of 62 elements used* <br/>remaining elements:<br/>`AuditEvent.agent.extension`, `AuditEvent.agent.id`, `AuditEvent.agent.modifierExtension`, `AuditEvent.agent.network.extension`, `AuditEvent.agent.network.id`, `AuditEvent.agent.network.modifierExtension`, `AuditEvent.agent.type`, `AuditEvent.entity.detail.extension`, `AuditEvent.entity.detail.id`, `AuditEvent.entity.detail.modifierExtension`, `AuditEvent.entity.extension`, `AuditEvent.entity.id`, `AuditEvent.entity.modifierExtension`, `AuditEvent.period`| | *38 of 59 elements used* <br/>remaining elements:<br/>`AuditEvent.agent.extension`, `AuditEvent.agent.id`, `AuditEvent.agent.modifierExtension`, `AuditEvent.agent.type`, `AuditEvent.basedOn`, `AuditEvent.encounter`, `AuditEvent.entity.agent`, `AuditEvent.entity.detail.extension`, `AuditEvent.entity.detail.id`, `AuditEvent.entity.detail.modifierExtension`, `AuditEvent.entity.extension`, `AuditEvent.entity.id`, `AuditEvent.entity.modifierExtension`, `AuditEvent.occurred[x]`, `AuditEvent.outcome.code`, `AuditEvent.outcome.detail`, `AuditEvent.outcome.extension`, `AuditEvent.outcome.id`, `AuditEvent.outcome.modifierExtension`, `AuditEvent.patient`, `AuditEvent.severity`

