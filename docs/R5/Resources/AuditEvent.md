Comparison of 
Generated at Tuesday, April 1, 2025 1:39:37 PM

### AuditEvent

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | AuditEvent |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/AuditEvent` |
| Version | 5.0.0 |
| Description | A record of an event relevant for purposes such as operations, privacy, security, maintenance, and performance analysis. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2257` |
| Database Snapshot Count | `59` |
| Database Differential Count | `36` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `AuditEvent` | `AuditEvent` | `AuditEvent` | AuditEvent | Record of an event | 0..* | AuditEvent |  |  |
| `AuditEvent.action` | `AuditEvent.action` | `action` | AuditEvent.action | Type of action performed during the event | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/audit-event-action|5.0.0` |
| `AuditEvent.agent` | `AuditEvent.agent` | `agent` | AuditEvent.agent | Actor involved in the event | 1..* | BackboneElement |  |  |
| `AuditEvent.agent.authorization` | `AuditEvent.agent.authorization` | `authorization` | AuditEvent.agent.authorization | Allowable authorization for this agent | 0..* | CodeableConcept | `Example` | `http://terminology.hl7.org/ValueSet/v3-PurposeOfUse` |
| `AuditEvent.agent.extension` | `AuditEvent.agent.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `AuditEvent.agent.id` | `AuditEvent.agent.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `AuditEvent.agent.location` | `AuditEvent.agent.location` | `location` | AuditEvent.agent.location | The agent location when the event occurred | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `AuditEvent.agent.modifierExtension` | `AuditEvent.agent.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `AuditEvent.agent.network[x]` | `AuditEvent.agent.network[x]` | `network[x]` | AuditEvent.agent.network[x] | This agent network location for the activity | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Endpoint), string, uri |  |  |
| `AuditEvent.agent.policy` | `AuditEvent.agent.policy` | `policy` | AuditEvent.agent.policy | Policy that authorized the agent participation in the event | 0..* | uri |  |  |
| `AuditEvent.agent.requestor` | `AuditEvent.agent.requestor` | `requestor` | AuditEvent.agent.requestor | Whether user is initiator | 0..1 | boolean |  |  |
| `AuditEvent.agent.role` | `AuditEvent.agent.role` | `role` | AuditEvent.agent.role | Agent role in the event | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/security-role-type` |
| `AuditEvent.agent.type` | `AuditEvent.agent.type` | `type` | AuditEvent.agent.type | How agent participated | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/participation-role-type` |
| `AuditEvent.agent.who` | `AuditEvent.agent.who` | `who` | AuditEvent.agent.who | Identifier of who | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/CareTeam), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `AuditEvent.authorization` | `AuditEvent.authorization` | `authorization` | AuditEvent.authorization | Authorization related to the event | 0..* | CodeableConcept | `Example` | `http://terminology.hl7.org/ValueSet/v3-PurposeOfUse` |
| `AuditEvent.basedOn` | `AuditEvent.basedOn` | `basedOn` | AuditEvent.basedOn | Workflow authorization within which this event occurred | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/CarePlan), Reference(http://hl7.org/fhir/StructureDefinition/DeviceRequest), Reference(http://hl7.org/fhir/StructureDefinition/ImmunizationRecommendation), Reference(http://hl7.org/fhir/StructureDefinition/MedicationRequest), Reference(http://hl7.org/fhir/StructureDefinition/NutritionOrder), Reference(http://hl7.org/fhir/StructureDefinition/ServiceRequest), Reference(http://hl7.org/fhir/StructureDefinition/Task) |  |  |
| `AuditEvent.category` | `AuditEvent.category` | `category` | AuditEvent.category | Type/identifier of event | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/audit-event-type` |
| `AuditEvent.code` | `AuditEvent.code` | `code` | AuditEvent.code | Specific type of event | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/audit-event-sub-type` |
| `AuditEvent.contained` | `AuditEvent.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `AuditEvent.encounter` | `AuditEvent.encounter` | `encounter` | AuditEvent.encounter | Encounter within which this event occurred or which the event is tightly associated | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `AuditEvent.entity` | `AuditEvent.entity` | `entity` | AuditEvent.entity | Data or objects used | 0..* | BackboneElement |  |  |
| `AuditEvent.entity.agent` | `AuditEvent.entity.agent` | `agent` | AuditEvent.entity.agent | Entity is attributed to this agent | 0..* | AuditEvent.agent |  |  |
| `AuditEvent.entity.detail` | `AuditEvent.entity.detail` | `detail` | AuditEvent.entity.detail | Additional Information about the entity | 0..* | BackboneElement |  |  |
| `AuditEvent.entity.detail.extension` | `AuditEvent.entity.detail.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `AuditEvent.entity.detail.id` | `AuditEvent.entity.detail.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `AuditEvent.entity.detail.modifierExtension` | `AuditEvent.entity.detail.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `AuditEvent.entity.detail.type` | `AuditEvent.entity.detail.type` | `type` | AuditEvent.entity.detail.type | Name of the property | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/audit-event-type` |
| `AuditEvent.entity.detail.value[x]` | `AuditEvent.entity.detail.value[x]` | `value[x]` | AuditEvent.entity.detail.value[x] | Property value | 1..1 | base64Binary, boolean, CodeableConcept, dateTime, integer, Period, Quantity, Range, Ratio, string, time |  |  |
| `AuditEvent.entity.extension` | `AuditEvent.entity.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `AuditEvent.entity.id` | `AuditEvent.entity.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `AuditEvent.entity.modifierExtension` | `AuditEvent.entity.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `AuditEvent.entity.query` | `AuditEvent.entity.query` | `query` | AuditEvent.entity.query | Query parameters | 0..1 | base64Binary |  |  |
| `AuditEvent.entity.role` | `AuditEvent.entity.role` | `role` | AuditEvent.entity.role | What role the entity played | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/object-role` |
| `AuditEvent.entity.securityLabel` | `AuditEvent.entity.securityLabel` | `securityLabel` | AuditEvent.entity.securityLabel | Security labels on the entity | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/security-label-examples` |
| `AuditEvent.entity.what` | `AuditEvent.entity.what` | `what` | AuditEvent.entity.what | Specific instance of resource | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `AuditEvent.extension` | `AuditEvent.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `AuditEvent.id` | `AuditEvent.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `AuditEvent.implicitRules` | `AuditEvent.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `AuditEvent.language` | `AuditEvent.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `AuditEvent.meta` | `AuditEvent.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `AuditEvent.modifierExtension` | `AuditEvent.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `AuditEvent.occurred[x]` | `AuditEvent.occurred[x]` | `occurred[x]` | AuditEvent.occurred[x] | When the activity occurred | 0..1 | dateTime, Period |  |  |
| `AuditEvent.outcome` | `AuditEvent.outcome` | `outcome` | AuditEvent.outcome | Whether the event succeeded or failed | 0..1 | BackboneElement |  |  |
| `AuditEvent.outcome.code` | `AuditEvent.outcome.code` | `code` | AuditEvent.outcome.code | Whether the event succeeded or failed | 1..1 | Coding | `Preferred` | `http://hl7.org/fhir/ValueSet/audit-event-outcome` |
| `AuditEvent.outcome.detail` | `AuditEvent.outcome.detail` | `detail` | AuditEvent.outcome.detail | Additional outcome detail | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/audit-event-outcome-detail` |
| `AuditEvent.outcome.extension` | `AuditEvent.outcome.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `AuditEvent.outcome.id` | `AuditEvent.outcome.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `AuditEvent.outcome.modifierExtension` | `AuditEvent.outcome.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `AuditEvent.patient` | `AuditEvent.patient` | `patient` | AuditEvent.patient | The patient is the subject of the data used/created/updated/deleted during the activity | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `AuditEvent.recorded` | `AuditEvent.recorded` | `recorded` | AuditEvent.recorded | Time when the event was recorded | 1..1 | instant |  |  |
| `AuditEvent.severity` | `AuditEvent.severity` | `severity` | AuditEvent.severity | emergency \| alert \| critical \| error \| warning \| notice \| informational \| debug | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/audit-event-severity|5.0.0` |
| `AuditEvent.source` | `AuditEvent.source` | `source` | AuditEvent.source | Audit Event Reporter | 1..1 | BackboneElement |  |  |
| `AuditEvent.source.extension` | `AuditEvent.source.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `AuditEvent.source.id` | `AuditEvent.source.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `AuditEvent.source.modifierExtension` | `AuditEvent.source.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `AuditEvent.source.observer` | `AuditEvent.source.observer` | `observer` | AuditEvent.source.observer | The identity of source detecting the event | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/CareTeam), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `AuditEvent.source.site` | `AuditEvent.source.site` | `site` | AuditEvent.source.site | Logical source location within the enterprise | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `AuditEvent.source.type` | `AuditEvent.source.type` | `type` | AuditEvent.source.type | The type of source where event originated | 0..* | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/security-source-type` |
| `AuditEvent.text` | `AuditEvent.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [AuditEvent](/docs/R2/Resources/AuditEvent.md)<br/> `http://hl7.org/fhir/StructureDefinition/AuditEvent\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `76`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `242`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AuditEvent](/docs/R3/Resources/AuditEvent.md)<br/> `http://hl7.org/fhir/StructureDefinition/AuditEvent\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `421`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `617`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AuditEvent](/docs/R4/Resources/AuditEvent.md)<br/> `http://hl7.org/fhir/StructureDefinition/AuditEvent\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1399`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1400`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AuditEvent](/docs/R4B/Resources/AuditEvent.md)<br/> `http://hl7.org/fhir/StructureDefinition/AuditEvent\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `935`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1164`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [AuditEvent](/docs/R5/Resources/AuditEvent.md)<br/> `http://hl7.org/fhir/StructureDefinition/AuditEvent\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition AuditEvent from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 AuditEvent](/docs/R2/Resources/AuditEvent.md)| Relationship | [R3 AuditEvent](/docs/R3/Resources/AuditEvent.md)| Relationship | [R4 AuditEvent](/docs/R4/Resources/AuditEvent.md)| Relationship | [R4B AuditEvent](/docs/R4B/Resources/AuditEvent.md)| Relationship | R5 AuditEvent
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `AuditEvent`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3071)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(468)| `AuditEvent`| _Equivalent_<br/>(10296/10297)| `AuditEvent`| _Equivalent_<br/>(21850/21851)| `AuditEvent`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(36951)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36952)| **`AuditEvent`**
| `AuditEvent.event`| →→→→ _RelatedTo_ →→→→ <br/>(13)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(468)| `AuditEvent`| _Equivalent_<br/>(10296/10297)| `AuditEvent`| _Equivalent_<br/>(21850/21851)| `AuditEvent`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(36951)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36952)| **`AuditEvent`**
| `AuditEvent.id`| _Equivalent_<br/>(3073/3074)| `AuditEvent.id`| _Equivalent_<br/>(10298/10299)| `AuditEvent.id`| _Equivalent_<br/>(21852/21853)| `AuditEvent.id`| _Equivalent_<br/>(36953/36954)| **`AuditEvent.id`**
| `AuditEvent.meta`| _Equivalent_<br/>(3075/3076)| `AuditEvent.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10300)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10301)| `AuditEvent.meta`| _Equivalent_<br/>(21854/21855)| `AuditEvent.meta`| _Equivalent_<br/>(36955/36956)| **`AuditEvent.meta`**
| `AuditEvent.implicitRules`| _Equivalent_<br/>(3077/3078)| `AuditEvent.implicitRules`| _Equivalent_<br/>(10302/10303)| `AuditEvent.implicitRules`| _Equivalent_<br/>(21856/21857)| `AuditEvent.implicitRules`| _Equivalent_<br/>(36957/36958)| **`AuditEvent.implicitRules`**
| `AuditEvent.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3079)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(3080)| `AuditEvent.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10304)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(10305)| `AuditEvent.language`| _Equivalent_<br/>(21858/21859)| `AuditEvent.language`| _Equivalent_<br/>(36959/36960)| **`AuditEvent.language`**
| `AuditEvent.text`| _Equivalent_<br/>(3081/3082)| `AuditEvent.text`| _Equivalent_<br/>(10306/10307)| `AuditEvent.text`| _Equivalent_<br/>(21860/21861)| `AuditEvent.text`| _Equivalent_<br/>(36961/36962)| **`AuditEvent.text`**
| `AuditEvent.contained`| _Equivalent_<br/>(3083/3084)| `AuditEvent.contained`| _Equivalent_<br/>(10308/10309)| `AuditEvent.contained`| _Equivalent_<br/>(21862/21863)| `AuditEvent.contained`| _Equivalent_<br/>(36963/36964)| **`AuditEvent.contained`**
| `AuditEvent.extension`| _Equivalent_<br/>(3085/3086)| `AuditEvent.extension`| _Equivalent_<br/>(10310/10311)| `AuditEvent.extension`| _Equivalent_<br/>(21864/21865)| `AuditEvent.extension`| _Equivalent_<br/>(36965/36966)| **`AuditEvent.extension`**
| `AuditEvent.modifierExtension`| _Equivalent_<br/>(3087/3088)| `AuditEvent.modifierExtension`| _Equivalent_<br/>(10312/10313)| `AuditEvent.modifierExtension`| _Equivalent_<br/>(21866/21867)| `AuditEvent.modifierExtension`| _Equivalent_<br/>(36967/36968)| **`AuditEvent.modifierExtension`**
| `AuditEvent.event.type`| _Equivalent_<br/>(20/502)| `AuditEvent.type`| _Equivalent_<br/>(10314/10315)| `AuditEvent.type`| _Equivalent_<br/>(21868/21869)| `AuditEvent.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1724)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1968)| **`AuditEvent.category`**
| `AuditEvent.event.subtype`| _Equivalent_<br/>(19/501)| `AuditEvent.subtype`| _Equivalent_<br/>(10316/10317)| `AuditEvent.subtype`| _Equivalent_<br/>(21870/21871)| `AuditEvent.subtype`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1725)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1969)| **`AuditEvent.code`**
| `AuditEvent.event.action`| _Equivalent_<br/>(14/469)| `AuditEvent.action`| _Equivalent_<br/>(10318/10319)| `AuditEvent.action`| _Equivalent_<br/>(21872/21873)| `AuditEvent.action`| _Equivalent_<br/>(36969/36970)| **`AuditEvent.action`**
| | | | | | | | | **`AuditEvent.severity`**
| | | | | | | | | **`AuditEvent.occurred[x]`**
| `AuditEvent.event.dateTime`| _Equivalent_<br/>(15/500)| `AuditEvent.recorded`| _Equivalent_<br/>(10320/10321)| `AuditEvent.recorded`| _Equivalent_<br/>(21876/21877)| `AuditEvent.recorded`| _Equivalent_<br/>(36972/36973)| **`AuditEvent.recorded`**
| `AuditEvent.event.outcome`| _Equivalent_<br/>(16/497)| `AuditEvent.outcome`| _Equivalent_<br/>(10322/10323)| `AuditEvent.outcome`| _Equivalent_<br/>(21878/21879)| `AuditEvent.outcome`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36974)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36975)| **`AuditEvent.outcome`**
| | | | | | | | | **`AuditEvent.outcome.id`**
| | | | | | | | | **`AuditEvent.outcome.extension`**
| | | | | | | | | **`AuditEvent.outcome.modifierExtension`**
| | | | | | | | | **`AuditEvent.outcome.code`**
| | | | | | | | | **`AuditEvent.outcome.detail`**
| `AuditEvent.event.purposeOfEvent`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(18)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(499)| `AuditEvent.purposeOfEvent`| _Equivalent_<br/>(10326/10327)| `AuditEvent.purposeOfEvent`| _Equivalent_<br/>(21882/21883)| `AuditEvent.purposeOfEvent`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1726)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1970)| **`AuditEvent.authorization`**
| | | | | | | | | **`AuditEvent.basedOn`**
| | | | | | | | | **`AuditEvent.patient`**
| | | | | | | | | **`AuditEvent.encounter`**
| `AuditEvent.participant`| _Equivalent_<br/>(34/470)| `AuditEvent.agent`| _Equivalent_<br/>(10328/10329)| `AuditEvent.agent`| _Equivalent_<br/>(21884/21885)| `AuditEvent.agent`| _Equivalent_<br/>(36977/36978)| **`AuditEvent.agent`**
| | | `AuditEvent.agent.id`| _Equivalent_<br/>(10330/10331)| `AuditEvent.agent.id`| _Equivalent_<br/>(21886/21887)| `AuditEvent.agent.id`| _Equivalent_<br/>(36979/36980)| **`AuditEvent.agent.id`**
| | | `AuditEvent.agent.extension`| _Equivalent_<br/>(10332/10333)| `AuditEvent.agent.extension`| _Equivalent_<br/>(21888/21889)| `AuditEvent.agent.extension`| _Equivalent_<br/>(36981/36982)| **`AuditEvent.agent.extension`**
| | | `AuditEvent.agent.modifierExtension`| _Equivalent_<br/>(10334/10335)| `AuditEvent.agent.modifierExtension`| _Equivalent_<br/>(21890/21891)| `AuditEvent.agent.modifierExtension`| _Equivalent_<br/>(36983/36984)| **`AuditEvent.agent.modifierExtension`**
| | | | | `AuditEvent.agent.type`| _Equivalent_<br/>(21892/21893)| `AuditEvent.agent.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36985)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36986)| **`AuditEvent.agent.type`**
| `AuditEvent.participant.role`| _Equivalent_<br/>(46/482)| `AuditEvent.agent.role`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10336)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10337)| `AuditEvent.agent.role`| _Equivalent_<br/>(21894/21895)| `AuditEvent.agent.role`| _Equivalent_<br/>(36987/36988)| **`AuditEvent.agent.role`**
| `AuditEvent.participant.reference`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(44)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(480)| `AuditEvent.agent.reference`| →→→→ _RelatedTo_ →→→→ <br/>(814)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1353)| `AuditEvent.agent.who`| _Equivalent_<br/>(21896/21897)| `AuditEvent.agent.who`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36989)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36990)| **`AuditEvent.agent.who`**
| `AuditEvent.participant.userId`| _Equivalent_<br/>(47/483)| `AuditEvent.agent.userId`| →→→→ _Equivalent_ →→→→ <br/>(21849)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1353)| `AuditEvent.agent.who`| _Equivalent_<br/>(21896/21897)| `AuditEvent.agent.who`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36989)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36990)| **`AuditEvent.agent.who`**
| `AuditEvent.participant.requestor`| _Equivalent_<br/>(45/481)| `AuditEvent.agent.requestor`| _Equivalent_<br/>(10342/10343)| `AuditEvent.agent.requestor`| _Equivalent_<br/>(21902/21903)| `AuditEvent.agent.requestor`| →→→→ _Equivalent_ →→→→ <br/>(36993)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36994)| **`AuditEvent.agent.requestor`**
| `AuditEvent.participant.location`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(472)| `AuditEvent.agent.location`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10344)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10345)| `AuditEvent.agent.location`| _Equivalent_<br/>(21904/21905)| `AuditEvent.agent.location`| _Equivalent_<br/>(36995/36996)| **`AuditEvent.agent.location`**
| `AuditEvent.participant.policy`| _Equivalent_<br/>(42/478)| `AuditEvent.agent.policy`| _Equivalent_<br/>(10346/10347)| `AuditEvent.agent.policy`| _Equivalent_<br/>(21906/21907)| `AuditEvent.agent.policy`| _Equivalent_<br/>(36997/36998)| **`AuditEvent.agent.policy`**
| `AuditEvent.participant.network`| _Equivalent_<br/>(39/475)| `AuditEvent.agent.network`| _Equivalent_<br/>(10350/10351)| `AuditEvent.agent.network`| _Equivalent_<br/>(21910/21911)| `AuditEvent.agent.network`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1727)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1971)| **`AuditEvent.agent.network[x]`**
| `AuditEvent.participant.purposeOfUse`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(43)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(479)| `AuditEvent.agent.purposeOfUse`| _Equivalent_<br/>(10362/10363)| `AuditEvent.agent.purposeOfUse`| _Equivalent_<br/>(21922/21923)| `AuditEvent.agent.purposeOfUse`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1728)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1972)| **`AuditEvent.agent.authorization`**
| `AuditEvent.source`| _Equivalent_<br/>(3098/3099)| `AuditEvent.source`| _Equivalent_<br/>(10364/10365)| `AuditEvent.source`| _Equivalent_<br/>(21924/21925)| `AuditEvent.source`| _Equivalent_<br/>(37005/37006)| **`AuditEvent.source`**
| `AuditEvent.source.id`| _Equivalent_<br/>(3100/3101)| `AuditEvent.source.id`| _Equivalent_<br/>(10366/10367)| `AuditEvent.source.id`| _Equivalent_<br/>(21926/21927)| `AuditEvent.source.id`| _Equivalent_<br/>(37007/37008)| **`AuditEvent.source.id`**
| `AuditEvent.source.extension`| _Equivalent_<br/>(3102/3103)| `AuditEvent.source.extension`| _Equivalent_<br/>(10368/10369)| `AuditEvent.source.extension`| _Equivalent_<br/>(21928/21929)| `AuditEvent.source.extension`| _Equivalent_<br/>(37009/37010)| **`AuditEvent.source.extension`**
| `AuditEvent.source.modifierExtension`| _Equivalent_<br/>(3104/3105)| `AuditEvent.source.modifierExtension`| _Equivalent_<br/>(10370/10371)| `AuditEvent.source.modifierExtension`| _Equivalent_<br/>(21930/21931)| `AuditEvent.source.modifierExtension`| _Equivalent_<br/>(37011/37012)| **`AuditEvent.source.modifierExtension`**
| `AuditEvent.source.site`| _Equivalent_<br/>(3106/3107)| `AuditEvent.source.site`| _Equivalent_<br/>(10372/10373)| `AuditEvent.source.site`| _Equivalent_<br/>(21932/21933)| `AuditEvent.source.site`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(37013)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(37014)| **`AuditEvent.source.site`**
| `AuditEvent.source.identifier`| _Equivalent_<br/>(3108/3109)| `AuditEvent.source.identifier`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(819)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1355)| `AuditEvent.source.observer`| _Equivalent_<br/>(21934/21935)| `AuditEvent.source.observer`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(37015)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(37016)| **`AuditEvent.source.observer`**
| `AuditEvent.source.type`| _Equivalent_<br/>(3110/3111)| `AuditEvent.source.type`| _Equivalent_<br/>(10374/10375)| `AuditEvent.source.type`| _Equivalent_<br/>(21936/21937)| `AuditEvent.source.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(37017)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(37018)| **`AuditEvent.source.type`**
| `AuditEvent.object`| _Equivalent_<br/>(21/484)| `AuditEvent.entity`| _Equivalent_<br/>(10376/10377)| `AuditEvent.entity`| _Equivalent_<br/>(21938/21939)| `AuditEvent.entity`| _Equivalent_<br/>(37019/37020)| **`AuditEvent.entity`**
| | | `AuditEvent.entity.id`| _Equivalent_<br/>(10378/10379)| `AuditEvent.entity.id`| _Equivalent_<br/>(21940/21941)| `AuditEvent.entity.id`| _Equivalent_<br/>(37021/37022)| **`AuditEvent.entity.id`**
| | | `AuditEvent.entity.extension`| _Equivalent_<br/>(10380/10381)| `AuditEvent.entity.extension`| _Equivalent_<br/>(21942/21943)| `AuditEvent.entity.extension`| _Equivalent_<br/>(37023/37024)| **`AuditEvent.entity.extension`**
| | | `AuditEvent.entity.modifierExtension`| _Equivalent_<br/>(10382/10383)| `AuditEvent.entity.modifierExtension`| _Equivalent_<br/>(21944/21945)| `AuditEvent.entity.modifierExtension`| _Equivalent_<br/>(37025/37026)| **`AuditEvent.entity.modifierExtension`**
| `AuditEvent.object.identifier`| _Equivalent_<br/>(26/489)| `AuditEvent.entity.identifier`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(817)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1357)| `AuditEvent.entity.what`| _Equivalent_<br/>(21946/21947)| `AuditEvent.entity.what`| _Equivalent_<br/>(37027/37028)| **`AuditEvent.entity.what`**
| `AuditEvent.object.reference`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(30)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(493)| `AuditEvent.entity.reference`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(818)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1357)| `AuditEvent.entity.what`| _Equivalent_<br/>(21946/21947)| `AuditEvent.entity.what`| _Equivalent_<br/>(37027/37028)| **`AuditEvent.entity.what`**
| `AuditEvent.object.role`| _Equivalent_<br/>(31/494)| `AuditEvent.entity.role`| _Equivalent_<br/>(10386/10387)| `AuditEvent.entity.role`| _Equivalent_<br/>(21950/21951)| `AuditEvent.entity.role`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(37030)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(37031)| **`AuditEvent.entity.role`**
| `AuditEvent.object.securityLabel`| _Equivalent_<br/>(32/495)| `AuditEvent.entity.securityLabel`| _Equivalent_<br/>(10390/10391)| `AuditEvent.entity.securityLabel`| _Equivalent_<br/>(21954/21955)| `AuditEvent.entity.securityLabel`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(37033)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(37034)| **`AuditEvent.entity.securityLabel`**
| `AuditEvent.object.query`| _Equivalent_<br/>(29/492)| `AuditEvent.entity.query`| _Equivalent_<br/>(10396/10397)| `AuditEvent.entity.query`| _Equivalent_<br/>(21960/21961)| `AuditEvent.entity.query`| _Equivalent_<br/>(37037/37038)| **`AuditEvent.entity.query`**
| `AuditEvent.object.detail`| _Equivalent_<br/>(23/486)| `AuditEvent.entity.detail`| _Equivalent_<br/>(10398/10399)| `AuditEvent.entity.detail`| _Equivalent_<br/>(21962/21963)| `AuditEvent.entity.detail`| _Equivalent_<br/>(37039/37040)| **`AuditEvent.entity.detail`**
| | | `AuditEvent.entity.detail.id`| _Equivalent_<br/>(10400/10401)| `AuditEvent.entity.detail.id`| _Equivalent_<br/>(21964/21965)| `AuditEvent.entity.detail.id`| _Equivalent_<br/>(37041/37042)| **`AuditEvent.entity.detail.id`**
| | | `AuditEvent.entity.detail.extension`| _Equivalent_<br/>(10402/10403)| `AuditEvent.entity.detail.extension`| _Equivalent_<br/>(21966/21967)| `AuditEvent.entity.detail.extension`| _Equivalent_<br/>(37043/37044)| **`AuditEvent.entity.detail.extension`**
| | | `AuditEvent.entity.detail.modifierExtension`| _Equivalent_<br/>(10404/10405)| `AuditEvent.entity.detail.modifierExtension`| _Equivalent_<br/>(21968/21969)| `AuditEvent.entity.detail.modifierExtension`| _Equivalent_<br/>(37045/37046)| **`AuditEvent.entity.detail.modifierExtension`**
| `AuditEvent.object.detail.type`| _Equivalent_<br/>(24/487)| `AuditEvent.entity.detail.type`| _Equivalent_<br/>(10406/10407)| `AuditEvent.entity.detail.type`| _Equivalent_<br/>(21970/21971)| `AuditEvent.entity.detail.type`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(37047)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(37048)| **`AuditEvent.entity.detail.type`**
| `AuditEvent.object.detail.value`| _Equivalent_<br/>(25/488)| `AuditEvent.entity.detail.value`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(816)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1354)| `AuditEvent.entity.detail.value[x]`| _Equivalent_<br/>(21972/21973)| `AuditEvent.entity.detail.value[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(37049)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(37050)| **`AuditEvent.entity.detail.value[x]`**
| | | | | | | | | **`AuditEvent.entity.agent`**
| *41 of 66 elements used* | | *49 of 62 elements used* | | *48 of 62 elements used* | | *48 of 62 elements used* | | *59 of 59 elements used* 

