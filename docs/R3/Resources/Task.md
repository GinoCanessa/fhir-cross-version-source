Comparison of 
Generated at Thursday, April 3, 2025 8:18:14 AM

### Task

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | Task |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Task` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for Task Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `589` |
| Database Snapshot Count | `57` |
| Database Differential Count | `37` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Task` | `Task` | `Task` | Task | A task to be performed | 0..* | Task |  |  |
| `Task.authoredOn` | `Task.authoredOn` | `authoredOn` |  | Task Creation Date | 0..1 | dateTime |  |  |
| `Task.basedOn` | `Task.basedOn` | `basedOn` |  | Request fulfilled by this task | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `Task.businessStatus` | `Task.businessStatus` | `businessStatus` |  | E.g. "Specimen collected", "IV prepped" | 0..1 | CodeableConcept | `Example` |  |
| `Task.code` | `Task.code` | `code` |  | Task Type | 0..1 | CodeableConcept | `Example` |  |
| `Task.contained` | `Task.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Task.context` | `Task.context` | `context` |  | Healthcare event during which this task originated | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter), Reference(http://hl7.org/fhir/StructureDefinition/EpisodeOfCare) |  |  |
| `Task.definition[x]` | `Task.definition[x]` | `definition[x]` |  | Formal definition of task | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/ActivityDefinition), uri |  |  |
| `Task.description` | `Task.description` | `description` |  | Human-readable explanation of task | 0..1 | string |  |  |
| `Task.executionPeriod` | `Task.executionPeriod` | `executionPeriod` |  | Start and end time of execution | 0..1 | Period |  |  |
| `Task.extension` | `Task.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Task.focus` | `Task.focus` | `focus` |  | What task is acting on | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `Task.for` | `Task.for` | `for` |  | Beneficiary of the Task | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `Task.groupIdentifier` | `Task.groupIdentifier` | `groupIdentifier` |  | Requisition or grouper id | 0..1 | Identifier |  |  |
| `Task.id` | `Task.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Task.identifier` | `Task.identifier` | `identifier` |  | Task Instance Identifier | 0..* | Identifier |  |  |
| `Task.implicitRules` | `Task.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Task.input` | `Task.input` | `input` |  | Information used to perform task | 0..* | BackboneElement |  |  |
| `Task.input.extension` | `Task.input.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Task.input.id` | `Task.input.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Task.input.modifierExtension` | `Task.input.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Task.input.type` | `Task.input.type` | `type` |  | Label for the input | 1..1 | CodeableConcept | `Example` |  |
| `Task.input.value[x]` | `Task.input.value[x]` | `value[x]` |  | Content to use in performing the task | 1..1 | Address, Age, Annotation, Attachment, base64Binary, boolean, code, CodeableConcept, Coding, ContactPoint, Count, date, dateTime, decimal, Distance, Duration, HumanName, id, Identifier, instant, integer, markdown, Meta, Money, oid, Period, positiveInt, Quantity, Range, Ratio, Reference, SampledData, Signature, string, time, Timing, unsignedInt, uri |  |  |
| `Task.intent` | `Task.intent` | `intent` |  | proposal \| plan \| order + | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/request-intent` |
| `Task.language` | `Task.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `Task.lastModified` | `Task.lastModified` | `lastModified` |  | Task Last Modified Date | 0..1 | dateTime |  |  |
| `Task.meta` | `Task.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Task.modifierExtension` | `Task.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Task.note` | `Task.note` | `note` |  | Comments made about the task | 0..* | Annotation |  |  |
| `Task.output` | `Task.output` | `output` |  | Information produced as part of task | 0..* | BackboneElement |  |  |
| `Task.output.extension` | `Task.output.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Task.output.id` | `Task.output.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Task.output.modifierExtension` | `Task.output.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Task.output.type` | `Task.output.type` | `type` |  | Label for output | 1..1 | CodeableConcept | `Example` |  |
| `Task.output.value[x]` | `Task.output.value[x]` | `value[x]` |  | Result of output | 1..1 | Address, Age, Annotation, Attachment, base64Binary, boolean, code, CodeableConcept, Coding, ContactPoint, Count, date, dateTime, decimal, Distance, Duration, HumanName, id, Identifier, instant, integer, markdown, Meta, Money, oid, Period, positiveInt, Quantity, Range, Ratio, Reference, SampledData, Signature, string, time, Timing, unsignedInt, uri |  |  |
| `Task.owner` | `Task.owner` | `owner` |  | Responsible individual | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Task.partOf` | `Task.partOf` | `partOf` |  | Composite task | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Task) |  |  |
| `Task.performerType` | `Task.performerType` | `performerType` |  | requester \| dispatcher \| scheduler \| performer \| monitor \| manager \| acquirer \| reviewer | 0..* | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/task-performer-type` |
| `Task.priority` | `Task.priority` | `priority` |  | normal \| urgent \| asap \| stat | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/request-priority` |
| `Task.reason` | `Task.reason` | `reason` |  | Why task is needed | 0..1 | CodeableConcept | `Example` |  |
| `Task.relevantHistory` | `Task.relevantHistory` | `relevantHistory` |  | Key events in history of the Task | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Provenance) |  |  |
| `Task.requester` | `Task.requester` | `requester` |  | Who is asking for task to be done | 0..1 | BackboneElement |  |  |
| `Task.requester.agent` | `Task.requester.agent` | `agent` |  | Individual asking for task | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Task.requester.extension` | `Task.requester.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Task.requester.id` | `Task.requester.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Task.requester.modifierExtension` | `Task.requester.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Task.requester.onBehalfOf` | `Task.requester.onBehalfOf` | `onBehalfOf` |  | Organization individual is acting for | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Task.restriction` | `Task.restriction` | `restriction` |  | Constraints on fulfillment tasks | 0..1 | BackboneElement |  |  |
| `Task.restriction.extension` | `Task.restriction.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Task.restriction.id` | `Task.restriction.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Task.restriction.modifierExtension` | `Task.restriction.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Task.restriction.period` | `Task.restriction.period` | `period` |  | When fulfillment sought | 0..1 | Period |  |  |
| `Task.restriction.recipient` | `Task.restriction.recipient` | `recipient` |  | For whom is fulfillment sought? | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Task.restriction.repetitions` | `Task.restriction.repetitions` | `repetitions` |  | How many times to repeat | 0..1 | positiveInt |  |  |
| `Task.status` | `Task.status` | `status` |  | draft \| requested \| received \| accepted \| + | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/task-status` |
| `Task.statusReason` | `Task.statusReason` | `statusReason` |  | Reason for current status | 0..1 | CodeableConcept | `Example` |  |
| `Task.text` | `Task.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Order](/docs/R2/Resources/Order.md)<br/> `http://hl7.org/fhir/StructureDefinition/Order\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `135`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `302`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Task](/docs/R3/Resources/Task.md)<br/> `http://hl7.org/fhir/StructureDefinition/Task\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `524`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `718`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Task](/docs/R4/Resources/Task.md)<br/> `http://hl7.org/fhir/StructureDefinition/Task\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1633`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1634`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Task](/docs/R4B/Resources/Task.md)<br/> `http://hl7.org/fhir/StructureDefinition/Task\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1053`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1282`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Task](/docs/R5/Resources/Task.md)<br/> `http://hl7.org/fhir/StructureDefinition/Task\|5.0.0` 
| [OrderResponse](/docs/R2/Resources/OrderResponse.md)<br/> `http://hl7.org/fhir/StructureDefinition/OrderResponse\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `136`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `302`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Task](/docs/R3/Resources/Task.md)<br/> `http://hl7.org/fhir/StructureDefinition/Task\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `524`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `718`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Task](/docs/R4/Resources/Task.md)<br/> `http://hl7.org/fhir/StructureDefinition/Task\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1633`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1634`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Task](/docs/R4B/Resources/Task.md)<br/> `http://hl7.org/fhir/StructureDefinition/Task\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1053`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1282`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Task](/docs/R5/Resources/Task.md)<br/> `http://hl7.org/fhir/StructureDefinition/Task\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Task from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Order](/docs/R2/Resources/Order.md)| Relationship | R3 Task| Relationship | [R4 Task](/docs/R4/Resources/Task.md)| Relationship | [R4B Task](/docs/R4B/Resources/Task.md)| Relationship | [R5 Task](/docs/R5/Resources/Task.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | **`Task`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(19172)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(19173)| `Task`| _Equivalent_<br/>(34060/34061)| `Task`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(48483)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(48484)| `Task`
| | | **`Task.id`**| _Equivalent_<br/>(19174/19175)| `Task.id`| _Equivalent_<br/>(34062/34063)| `Task.id`| _Equivalent_<br/>(48485/48486)| `Task.id`
| | | **`Task.meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19176)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19177)| `Task.meta`| _Equivalent_<br/>(34064/34065)| `Task.meta`| _Equivalent_<br/>(48487/48488)| `Task.meta`
| | | **`Task.implicitRules`**| _Equivalent_<br/>(19178/19179)| `Task.implicitRules`| _Equivalent_<br/>(34066/34067)| `Task.implicitRules`| _Equivalent_<br/>(48489/48490)| `Task.implicitRules`
| | | **`Task.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19180)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(19181)| `Task.language`| _Equivalent_<br/>(34068/34069)| `Task.language`| _Equivalent_<br/>(48491/48492)| `Task.language`
| | | **`Task.text`**| _Equivalent_<br/>(19182/19183)| `Task.text`| _Equivalent_<br/>(34070/34071)| `Task.text`| _Equivalent_<br/>(48493/48494)| `Task.text`
| | | **`Task.contained`**| _Equivalent_<br/>(19184/19185)| `Task.contained`| _Equivalent_<br/>(34072/34073)| `Task.contained`| _Equivalent_<br/>(48495/48496)| `Task.contained`
| | | **`Task.extension`**| _Equivalent_<br/>(19186/19187)| `Task.extension`| _Equivalent_<br/>(34074/34075)| `Task.extension`| _Equivalent_<br/>(48497/48498)| `Task.extension`
| | | **`Task.modifierExtension`**| _Equivalent_<br/>(19188/19189)| `Task.modifierExtension`| _Equivalent_<br/>(34076/34077)| `Task.modifierExtension`| _Equivalent_<br/>(48499/48500)| `Task.modifierExtension`
| | | **`Task.identifier`**| _Equivalent_<br/>(19190/19191)| `Task.identifier`| _Equivalent_<br/>(34078/34079)| `Task.identifier`| _Equivalent_<br/>(48501/48502)| `Task.identifier`
| | | **`Task.definition[x]`**| →→→→ _Equivalent_ →→→→ <br/>(34056)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1684)| `base64Binary`| | | | | 
| | | **`Task.definition[x]`**| →→→→ _Equivalent_ →→→→ <br/>(34056)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1684)| `Task.instantiatesCanonical`| _Equivalent_<br/>(34080/34081)| `Task.instantiatesCanonical`| _Equivalent_<br/>(48503/48504)| `Task.instantiatesCanonical`
| | | **`Task.definition[x]`**| →→→→ _Equivalent_ →→→→ <br/>(34056)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1684)| `Task.instantiatesUri`| _Equivalent_<br/>(34082/34083)| `Task.instantiatesUri`| _Equivalent_<br/>(48505/48506)| `Task.instantiatesUri`
| `OrderResponse.request`| →→→→ _RelatedTo_ →→→→ <br/>(315)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6861)| **`Task.basedOn`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19192)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19193)| `Task.basedOn`| _Equivalent_<br/>(34084/34085)| `Task.basedOn`| _Equivalent_<br/>(48507/48508)| `Task.basedOn`
| | | **`Task.groupIdentifier`**| _Equivalent_<br/>(19194/19195)| `Task.groupIdentifier`| _Equivalent_<br/>(34086/34087)| `Task.groupIdentifier`| _Equivalent_<br/>(48509/48510)| `Task.groupIdentifier`
| | | **`Task.partOf`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19196)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19197)| `Task.partOf`| _Equivalent_<br/>(34088/34089)| `Task.partOf`| _Equivalent_<br/>(48511/48512)| `Task.partOf`
| | | **`Task.status`**| _Equivalent_<br/>(19198/19199)| `Task.status`| _Equivalent_<br/>(34090/34091)| `Task.status`| _Equivalent_<br/>(48513/48514)| `Task.status`
| | | **`Task.statusReason`**| _Equivalent_<br/>(19200/19201)| `Task.statusReason`| _Equivalent_<br/>(34092/34093)| `Task.statusReason`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(48515)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(48516)| `Task.statusReason`
| | | **`Task.businessStatus`**| _Equivalent_<br/>(19202/19203)| `Task.businessStatus`| _Equivalent_<br/>(34094/34095)| `Task.businessStatus`| _Equivalent_<br/>(48517/48518)| `Task.businessStatus`
| | | **`Task.intent`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19204)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19205)| `Task.intent`| _Equivalent_<br/>(34096/34097)| `Task.intent`| _Equivalent_<br/>(48519/48520)| `Task.intent`
| | | **`Task.priority`**| _Equivalent_<br/>(19206/19207)| `Task.priority`| _Equivalent_<br/>(34098/34099)| `Task.priority`| _Equivalent_<br/>(48521/48522)| `Task.priority`
| | | **`Task.code`**| _Equivalent_<br/>(19208/19209)| `Task.code`| _Equivalent_<br/>(34100/34101)| `Task.code`| _Equivalent_<br/>(48523/48524)| `Task.code`
| | | **`Task.description`**| _Equivalent_<br/>(19210/19211)| `Task.description`| _Equivalent_<br/>(34102/34103)| `Task.description`| _Equivalent_<br/>(48525/48526)| `Task.description`
| | | **`Task.focus`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19212)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19213)| `Task.focus`| _Equivalent_<br/>(34104/34105)| `Task.focus`| _Equivalent_<br/>(48527/48528)| `Task.focus`
| | | **`Task.for`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19214)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19215)| `Task.for`| _Equivalent_<br/>(34106/34107)| `Task.for`| _Equivalent_<br/>(48529/48530)| `Task.for`
| | | **`Task.context`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1293)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1681)| `Task.encounter`| _Equivalent_<br/>(34108/34109)| `Task.encounter`| _Equivalent_<br/>(48531/48532)| `Task.encounter`
| | | **`Task.executionPeriod`**| _Equivalent_<br/>(19216/19217)| `Task.executionPeriod`| _Equivalent_<br/>(34110/34111)| `Task.executionPeriod`| _Equivalent_<br/>(48533/48534)| `Task.executionPeriod`
| `OrderResponse.date`| _Equivalent_<br/>(312/6862)| **`Task.authoredOn`**| _Equivalent_<br/>(19218/19219)| `Task.authoredOn`| _Equivalent_<br/>(34112/34113)| `Task.authoredOn`| _Equivalent_<br/>(48535/48536)| `Task.authoredOn`
| | | **`Task.lastModified`**| _Equivalent_<br/>(19220/19221)| `Task.lastModified`| _Equivalent_<br/>(34114/34115)| `Task.lastModified`| _Equivalent_<br/>(48537/48538)| `Task.lastModified`
| | | **`Task.requester`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(19222)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19223)| `Task.requester`| _Equivalent_<br/>(34116/34117)| `Task.requester`| _Equivalent_<br/>(48539/48540)| `Task.requester`
| | | **`Task.requester.id`**| | | | | | | 
| | | **`Task.requester.extension`**| | | | | | | 
| | | **`Task.requester.modifierExtension`**| | | | | | | 
| | | **`Task.requester.agent`**| →→→→ _RelatedTo_ →→→→ <br/>(1296)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1683)| `Task.requester`| _Equivalent_<br/>(34116/34117)| `Task.requester`| _Equivalent_<br/>(48539/48540)| `Task.requester`
| | | **`Task.requester.onBehalfOf`**| | | | | | | 
| | | **`Task.performerType`**| _Equivalent_<br/>(19227/19228)| `Task.performerType`| _Equivalent_<br/>(34118/34119)| `Task.performerType`| | | 
| | | **`Task.owner`**| →→→→ _RelatedTo_ →→→→ <br/>(19229)<hr/>←←←← _RelatedTo_ ←←←← <br/>(19230)| `Task.owner`| _Equivalent_<br/>(34120/34121)| `Task.owner`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(48542)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(48543)| `Task.owner`
| | | **`Task.reason`**| _Equivalent_<br/>(1295/1682)| `Task.reasonCode`| _Equivalent_<br/>(34124/34125)| `Task.reasonCode`| →→→→ _RelatedTo_ →→→→ <br/>(1954)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2190)| `Task.reason`
| | | **`Task.note`**| _Equivalent_<br/>(19231/19232)| `Task.note`| _Equivalent_<br/>(34130/34131)| `Task.note`| _Equivalent_<br/>(48549/48550)| `Task.note`
| | | **`Task.relevantHistory`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19233)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19234)| `Task.relevantHistory`| _Equivalent_<br/>(34132/34133)| `Task.relevantHistory`| _Equivalent_<br/>(48551/48552)| `Task.relevantHistory`
| | | **`Task.restriction`**| _Equivalent_<br/>(19235/19236)| `Task.restriction`| _Equivalent_<br/>(34134/34135)| `Task.restriction`| _Equivalent_<br/>(48553/48554)| `Task.restriction`
| | | **`Task.restriction.id`**| _Equivalent_<br/>(19237/19238)| `Task.restriction.id`| _Equivalent_<br/>(34136/34137)| `Task.restriction.id`| _Equivalent_<br/>(48555/48556)| `Task.restriction.id`
| | | **`Task.restriction.extension`**| _Equivalent_<br/>(19239/19240)| `Task.restriction.extension`| _Equivalent_<br/>(34138/34139)| `Task.restriction.extension`| _Equivalent_<br/>(48557/48558)| `Task.restriction.extension`
| | | **`Task.restriction.modifierExtension`**| _Equivalent_<br/>(19241/19242)| `Task.restriction.modifierExtension`| _Equivalent_<br/>(34140/34141)| `Task.restriction.modifierExtension`| _Equivalent_<br/>(48559/48560)| `Task.restriction.modifierExtension`
| | | **`Task.restriction.repetitions`**| _Equivalent_<br/>(19243/19244)| `Task.restriction.repetitions`| _Equivalent_<br/>(34142/34143)| `Task.restriction.repetitions`| _Equivalent_<br/>(48561/48562)| `Task.restriction.repetitions`
| | | **`Task.restriction.period`**| _Equivalent_<br/>(19245/19246)| `Task.restriction.period`| _Equivalent_<br/>(34144/34145)| `Task.restriction.period`| _Equivalent_<br/>(48563/48564)| `Task.restriction.period`
| | | **`Task.restriction.recipient`**| →→→→ _RelatedTo_ →→→→ <br/>(19247)<hr/>←←←← _RelatedTo_ ←←←← <br/>(19248)| `Task.restriction.recipient`| _Equivalent_<br/>(34146/34147)| `Task.restriction.recipient`| _Equivalent_<br/>(48565/48566)| `Task.restriction.recipient`
| | | **`Task.input`**| _Equivalent_<br/>(19249/19250)| `Task.input`| _Equivalent_<br/>(34148/34149)| `Task.input`| _Equivalent_<br/>(48567/48568)| `Task.input`
| | | **`Task.input.id`**| _Equivalent_<br/>(19251/19252)| `Task.input.id`| _Equivalent_<br/>(34150/34151)| `Task.input.id`| _Equivalent_<br/>(48569/48570)| `Task.input.id`
| | | **`Task.input.extension`**| _Equivalent_<br/>(19253/19254)| `Task.input.extension`| _Equivalent_<br/>(34152/34153)| `Task.input.extension`| _Equivalent_<br/>(48571/48572)| `Task.input.extension`
| | | **`Task.input.modifierExtension`**| _Equivalent_<br/>(19255/19256)| `Task.input.modifierExtension`| _Equivalent_<br/>(34154/34155)| `Task.input.modifierExtension`| _Equivalent_<br/>(48573/48574)| `Task.input.modifierExtension`
| | | **`Task.input.type`**| _Equivalent_<br/>(19257/19258)| `Task.input.type`| _Equivalent_<br/>(34156/34157)| `Task.input.type`| _Equivalent_<br/>(48575/48576)| `Task.input.type`
| | | **`Task.input.value[x]`**| →→→→ _RelatedTo_ →→→→ <br/>(19259)<hr/>←←←← _RelatedTo_ ←←←← <br/>(19260)| `Task.input.value[x]`| _Equivalent_<br/>(34158/34159)| `Task.input.value[x]`| →→→→ _RelatedTo_ →→→→ <br/>(48577)<hr/>←←←← _RelatedTo_ ←←←← <br/>(48578)| `Task.input.value[x]`
| | | **`Task.output`**| _Equivalent_<br/>(19261/19262)| `Task.output`| _Equivalent_<br/>(34160/34161)| `Task.output`| _Equivalent_<br/>(48579/48580)| `Task.output`
| | | **`Task.output.id`**| _Equivalent_<br/>(19263/19264)| `Task.output.id`| _Equivalent_<br/>(34162/34163)| `Task.output.id`| _Equivalent_<br/>(48581/48582)| `Task.output.id`
| | | **`Task.output.extension`**| _Equivalent_<br/>(19265/19266)| `Task.output.extension`| _Equivalent_<br/>(34164/34165)| `Task.output.extension`| _Equivalent_<br/>(48583/48584)| `Task.output.extension`
| | | **`Task.output.modifierExtension`**| _Equivalent_<br/>(19267/19268)| `Task.output.modifierExtension`| _Equivalent_<br/>(34166/34167)| `Task.output.modifierExtension`| _Equivalent_<br/>(48585/48586)| `Task.output.modifierExtension`
| | | **`Task.output.type`**| _Equivalent_<br/>(19269/19270)| `Task.output.type`| _Equivalent_<br/>(34168/34169)| `Task.output.type`| _Equivalent_<br/>(48587/48588)| `Task.output.type`
| | | **`Task.output.value[x]`**| →→→→ _RelatedTo_ →→→→ <br/>(19271)<hr/>←←←← _RelatedTo_ ←←←← <br/>(19272)| `Task.output.value[x]`| _Equivalent_<br/>(34170/34171)| `Task.output.value[x]`| →→→→ _RelatedTo_ →→→→ <br/>(48589)<hr/>←←←← _RelatedTo_ ←←←← <br/>(48590)| `Task.output.value[x]`
| *2 of 22 elements used* <br/>remaining elements:<br/>`Order`, `Order.contained`, `Order.date`, `Order.detail`, `Order.extension`, `Order.id`, `Order.identifier`, `Order.implicitRules`, `Order.language`, `Order.meta`, `Order.modifierExtension`, `Order.reason[x]`, `Order.source`, `Order.subject`, `Order.target`, `Order.text`, `Order.when`, `Order.when.code`, `Order.when.extension`, `Order.when.id`, `Order.when.modifierExtension`, `Order.when.schedule`| | *57 of 57 elements used* | | *54 of 56 elements used* <br/>remaining elements:<br/>`Task.insurance`, `Task.location`, `Task.reasonReference`| | *53 of 56 elements used* <br/>remaining elements:<br/>`Task.insurance`, `Task.location`, `Task.reasonReference`| | *52 of 63 elements used* <br/>remaining elements:<br/>`Task.doNotPerform`, `Task.insurance`, `Task.location`, `Task.performer`, `Task.performer.actor`, `Task.performer.extension`, `Task.performer.function`, `Task.performer.id`, `Task.performer.modifierExtension`, `Task.requestedPerformer`, `Task.requestedPeriod`


#### Map Group 1

This group is centered on the Structure Definition Task from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 OrderResponse](/docs/R2/Resources/OrderResponse.md)| Relationship | R3 Task| Relationship | [R4 Task](/docs/R4/Resources/Task.md)| Relationship | [R4B Task](/docs/R4B/Resources/Task.md)| Relationship | [R5 Task](/docs/R5/Resources/Task.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | **`Task`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(19172)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(19173)| `Task`| _Equivalent_<br/>(34060/34061)| `Task`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(48483)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(48484)| `Task`
| | | **`Task.id`**| _Equivalent_<br/>(19174/19175)| `Task.id`| _Equivalent_<br/>(34062/34063)| `Task.id`| _Equivalent_<br/>(48485/48486)| `Task.id`
| | | **`Task.meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19176)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19177)| `Task.meta`| _Equivalent_<br/>(34064/34065)| `Task.meta`| _Equivalent_<br/>(48487/48488)| `Task.meta`
| | | **`Task.implicitRules`**| _Equivalent_<br/>(19178/19179)| `Task.implicitRules`| _Equivalent_<br/>(34066/34067)| `Task.implicitRules`| _Equivalent_<br/>(48489/48490)| `Task.implicitRules`
| | | **`Task.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19180)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(19181)| `Task.language`| _Equivalent_<br/>(34068/34069)| `Task.language`| _Equivalent_<br/>(48491/48492)| `Task.language`
| | | **`Task.text`**| _Equivalent_<br/>(19182/19183)| `Task.text`| _Equivalent_<br/>(34070/34071)| `Task.text`| _Equivalent_<br/>(48493/48494)| `Task.text`
| | | **`Task.contained`**| _Equivalent_<br/>(19184/19185)| `Task.contained`| _Equivalent_<br/>(34072/34073)| `Task.contained`| _Equivalent_<br/>(48495/48496)| `Task.contained`
| | | **`Task.extension`**| _Equivalent_<br/>(19186/19187)| `Task.extension`| _Equivalent_<br/>(34074/34075)| `Task.extension`| _Equivalent_<br/>(48497/48498)| `Task.extension`
| | | **`Task.modifierExtension`**| _Equivalent_<br/>(19188/19189)| `Task.modifierExtension`| _Equivalent_<br/>(34076/34077)| `Task.modifierExtension`| _Equivalent_<br/>(48499/48500)| `Task.modifierExtension`
| | | **`Task.identifier`**| _Equivalent_<br/>(19190/19191)| `Task.identifier`| _Equivalent_<br/>(34078/34079)| `Task.identifier`| _Equivalent_<br/>(48501/48502)| `Task.identifier`
| | | **`Task.definition[x]`**| →→→→ _Equivalent_ →→→→ <br/>(34056)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1684)| `base64Binary`| | | | | 
| | | **`Task.definition[x]`**| →→→→ _Equivalent_ →→→→ <br/>(34056)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1684)| `Task.instantiatesCanonical`| _Equivalent_<br/>(34080/34081)| `Task.instantiatesCanonical`| _Equivalent_<br/>(48503/48504)| `Task.instantiatesCanonical`
| | | **`Task.definition[x]`**| →→→→ _Equivalent_ →→→→ <br/>(34056)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1684)| `Task.instantiatesUri`| _Equivalent_<br/>(34082/34083)| `Task.instantiatesUri`| _Equivalent_<br/>(48505/48506)| `Task.instantiatesUri`
| `OrderResponse.request`| →→→→ _RelatedTo_ →→→→ <br/>(315)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6861)| **`Task.basedOn`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19192)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19193)| `Task.basedOn`| _Equivalent_<br/>(34084/34085)| `Task.basedOn`| _Equivalent_<br/>(48507/48508)| `Task.basedOn`
| | | **`Task.groupIdentifier`**| _Equivalent_<br/>(19194/19195)| `Task.groupIdentifier`| _Equivalent_<br/>(34086/34087)| `Task.groupIdentifier`| _Equivalent_<br/>(48509/48510)| `Task.groupIdentifier`
| | | **`Task.partOf`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19196)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19197)| `Task.partOf`| _Equivalent_<br/>(34088/34089)| `Task.partOf`| _Equivalent_<br/>(48511/48512)| `Task.partOf`
| | | **`Task.status`**| _Equivalent_<br/>(19198/19199)| `Task.status`| _Equivalent_<br/>(34090/34091)| `Task.status`| _Equivalent_<br/>(48513/48514)| `Task.status`
| | | **`Task.statusReason`**| _Equivalent_<br/>(19200/19201)| `Task.statusReason`| _Equivalent_<br/>(34092/34093)| `Task.statusReason`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(48515)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(48516)| `Task.statusReason`
| | | **`Task.businessStatus`**| _Equivalent_<br/>(19202/19203)| `Task.businessStatus`| _Equivalent_<br/>(34094/34095)| `Task.businessStatus`| _Equivalent_<br/>(48517/48518)| `Task.businessStatus`
| | | **`Task.intent`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19204)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19205)| `Task.intent`| _Equivalent_<br/>(34096/34097)| `Task.intent`| _Equivalent_<br/>(48519/48520)| `Task.intent`
| | | **`Task.priority`**| _Equivalent_<br/>(19206/19207)| `Task.priority`| _Equivalent_<br/>(34098/34099)| `Task.priority`| _Equivalent_<br/>(48521/48522)| `Task.priority`
| | | **`Task.code`**| _Equivalent_<br/>(19208/19209)| `Task.code`| _Equivalent_<br/>(34100/34101)| `Task.code`| _Equivalent_<br/>(48523/48524)| `Task.code`
| | | **`Task.description`**| _Equivalent_<br/>(19210/19211)| `Task.description`| _Equivalent_<br/>(34102/34103)| `Task.description`| _Equivalent_<br/>(48525/48526)| `Task.description`
| | | **`Task.focus`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19212)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19213)| `Task.focus`| _Equivalent_<br/>(34104/34105)| `Task.focus`| _Equivalent_<br/>(48527/48528)| `Task.focus`
| | | **`Task.for`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19214)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19215)| `Task.for`| _Equivalent_<br/>(34106/34107)| `Task.for`| _Equivalent_<br/>(48529/48530)| `Task.for`
| | | **`Task.context`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1293)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1681)| `Task.encounter`| _Equivalent_<br/>(34108/34109)| `Task.encounter`| _Equivalent_<br/>(48531/48532)| `Task.encounter`
| | | **`Task.executionPeriod`**| _Equivalent_<br/>(19216/19217)| `Task.executionPeriod`| _Equivalent_<br/>(34110/34111)| `Task.executionPeriod`| _Equivalent_<br/>(48533/48534)| `Task.executionPeriod`
| `OrderResponse.date`| _Equivalent_<br/>(312/6862)| **`Task.authoredOn`**| _Equivalent_<br/>(19218/19219)| `Task.authoredOn`| _Equivalent_<br/>(34112/34113)| `Task.authoredOn`| _Equivalent_<br/>(48535/48536)| `Task.authoredOn`
| | | **`Task.lastModified`**| _Equivalent_<br/>(19220/19221)| `Task.lastModified`| _Equivalent_<br/>(34114/34115)| `Task.lastModified`| _Equivalent_<br/>(48537/48538)| `Task.lastModified`
| | | **`Task.requester`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(19222)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19223)| `Task.requester`| _Equivalent_<br/>(34116/34117)| `Task.requester`| _Equivalent_<br/>(48539/48540)| `Task.requester`
| | | **`Task.requester.id`**| | | | | | | 
| | | **`Task.requester.extension`**| | | | | | | 
| | | **`Task.requester.modifierExtension`**| | | | | | | 
| | | **`Task.requester.agent`**| →→→→ _RelatedTo_ →→→→ <br/>(1296)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1683)| `Task.requester`| _Equivalent_<br/>(34116/34117)| `Task.requester`| _Equivalent_<br/>(48539/48540)| `Task.requester`
| | | **`Task.requester.onBehalfOf`**| | | | | | | 
| | | **`Task.performerType`**| _Equivalent_<br/>(19227/19228)| `Task.performerType`| _Equivalent_<br/>(34118/34119)| `Task.performerType`| | | 
| | | **`Task.owner`**| →→→→ _RelatedTo_ →→→→ <br/>(19229)<hr/>←←←← _RelatedTo_ ←←←← <br/>(19230)| `Task.owner`| _Equivalent_<br/>(34120/34121)| `Task.owner`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(48542)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(48543)| `Task.owner`
| | | **`Task.reason`**| _Equivalent_<br/>(1295/1682)| `Task.reasonCode`| _Equivalent_<br/>(34124/34125)| `Task.reasonCode`| →→→→ _RelatedTo_ →→→→ <br/>(1954)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2190)| `Task.reason`
| | | **`Task.note`**| _Equivalent_<br/>(19231/19232)| `Task.note`| _Equivalent_<br/>(34130/34131)| `Task.note`| _Equivalent_<br/>(48549/48550)| `Task.note`
| | | **`Task.relevantHistory`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19233)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19234)| `Task.relevantHistory`| _Equivalent_<br/>(34132/34133)| `Task.relevantHistory`| _Equivalent_<br/>(48551/48552)| `Task.relevantHistory`
| | | **`Task.restriction`**| _Equivalent_<br/>(19235/19236)| `Task.restriction`| _Equivalent_<br/>(34134/34135)| `Task.restriction`| _Equivalent_<br/>(48553/48554)| `Task.restriction`
| | | **`Task.restriction.id`**| _Equivalent_<br/>(19237/19238)| `Task.restriction.id`| _Equivalent_<br/>(34136/34137)| `Task.restriction.id`| _Equivalent_<br/>(48555/48556)| `Task.restriction.id`
| | | **`Task.restriction.extension`**| _Equivalent_<br/>(19239/19240)| `Task.restriction.extension`| _Equivalent_<br/>(34138/34139)| `Task.restriction.extension`| _Equivalent_<br/>(48557/48558)| `Task.restriction.extension`
| | | **`Task.restriction.modifierExtension`**| _Equivalent_<br/>(19241/19242)| `Task.restriction.modifierExtension`| _Equivalent_<br/>(34140/34141)| `Task.restriction.modifierExtension`| _Equivalent_<br/>(48559/48560)| `Task.restriction.modifierExtension`
| | | **`Task.restriction.repetitions`**| _Equivalent_<br/>(19243/19244)| `Task.restriction.repetitions`| _Equivalent_<br/>(34142/34143)| `Task.restriction.repetitions`| _Equivalent_<br/>(48561/48562)| `Task.restriction.repetitions`
| | | **`Task.restriction.period`**| _Equivalent_<br/>(19245/19246)| `Task.restriction.period`| _Equivalent_<br/>(34144/34145)| `Task.restriction.period`| _Equivalent_<br/>(48563/48564)| `Task.restriction.period`
| | | **`Task.restriction.recipient`**| →→→→ _RelatedTo_ →→→→ <br/>(19247)<hr/>←←←← _RelatedTo_ ←←←← <br/>(19248)| `Task.restriction.recipient`| _Equivalent_<br/>(34146/34147)| `Task.restriction.recipient`| _Equivalent_<br/>(48565/48566)| `Task.restriction.recipient`
| | | **`Task.input`**| _Equivalent_<br/>(19249/19250)| `Task.input`| _Equivalent_<br/>(34148/34149)| `Task.input`| _Equivalent_<br/>(48567/48568)| `Task.input`
| | | **`Task.input.id`**| _Equivalent_<br/>(19251/19252)| `Task.input.id`| _Equivalent_<br/>(34150/34151)| `Task.input.id`| _Equivalent_<br/>(48569/48570)| `Task.input.id`
| | | **`Task.input.extension`**| _Equivalent_<br/>(19253/19254)| `Task.input.extension`| _Equivalent_<br/>(34152/34153)| `Task.input.extension`| _Equivalent_<br/>(48571/48572)| `Task.input.extension`
| | | **`Task.input.modifierExtension`**| _Equivalent_<br/>(19255/19256)| `Task.input.modifierExtension`| _Equivalent_<br/>(34154/34155)| `Task.input.modifierExtension`| _Equivalent_<br/>(48573/48574)| `Task.input.modifierExtension`
| | | **`Task.input.type`**| _Equivalent_<br/>(19257/19258)| `Task.input.type`| _Equivalent_<br/>(34156/34157)| `Task.input.type`| _Equivalent_<br/>(48575/48576)| `Task.input.type`
| | | **`Task.input.value[x]`**| →→→→ _RelatedTo_ →→→→ <br/>(19259)<hr/>←←←← _RelatedTo_ ←←←← <br/>(19260)| `Task.input.value[x]`| _Equivalent_<br/>(34158/34159)| `Task.input.value[x]`| →→→→ _RelatedTo_ →→→→ <br/>(48577)<hr/>←←←← _RelatedTo_ ←←←← <br/>(48578)| `Task.input.value[x]`
| | | **`Task.output`**| _Equivalent_<br/>(19261/19262)| `Task.output`| _Equivalent_<br/>(34160/34161)| `Task.output`| _Equivalent_<br/>(48579/48580)| `Task.output`
| | | **`Task.output.id`**| _Equivalent_<br/>(19263/19264)| `Task.output.id`| _Equivalent_<br/>(34162/34163)| `Task.output.id`| _Equivalent_<br/>(48581/48582)| `Task.output.id`
| | | **`Task.output.extension`**| _Equivalent_<br/>(19265/19266)| `Task.output.extension`| _Equivalent_<br/>(34164/34165)| `Task.output.extension`| _Equivalent_<br/>(48583/48584)| `Task.output.extension`
| | | **`Task.output.modifierExtension`**| _Equivalent_<br/>(19267/19268)| `Task.output.modifierExtension`| _Equivalent_<br/>(34166/34167)| `Task.output.modifierExtension`| _Equivalent_<br/>(48585/48586)| `Task.output.modifierExtension`
| | | **`Task.output.type`**| _Equivalent_<br/>(19269/19270)| `Task.output.type`| _Equivalent_<br/>(34168/34169)| `Task.output.type`| _Equivalent_<br/>(48587/48588)| `Task.output.type`
| | | **`Task.output.value[x]`**| →→→→ _RelatedTo_ →→→→ <br/>(19271)<hr/>←←←← _RelatedTo_ ←←←← <br/>(19272)| `Task.output.value[x]`| _Equivalent_<br/>(34170/34171)| `Task.output.value[x]`| →→→→ _RelatedTo_ →→→→ <br/>(48589)<hr/>←←←← _RelatedTo_ ←←←← <br/>(48590)| `Task.output.value[x]`
| *2 of 16 elements used* <br/>remaining elements:<br/>`OrderResponse`, `OrderResponse.contained`, `OrderResponse.description`, `OrderResponse.extension`, `OrderResponse.fulfillment`, `OrderResponse.id`, `OrderResponse.identifier`, `OrderResponse.implicitRules`, `OrderResponse.language`, `OrderResponse.meta`, `OrderResponse.modifierExtension`, `OrderResponse.orderStatus`, `OrderResponse.text`, `OrderResponse.who`| | *57 of 57 elements used* | | *54 of 56 elements used* <br/>remaining elements:<br/>`Task.insurance`, `Task.location`, `Task.reasonReference`| | *53 of 56 elements used* <br/>remaining elements:<br/>`Task.insurance`, `Task.location`, `Task.reasonReference`| | *52 of 63 elements used* <br/>remaining elements:<br/>`Task.doNotPerform`, `Task.insurance`, `Task.location`, `Task.performer`, `Task.performer.actor`, `Task.performer.extension`, `Task.performer.function`, `Task.performer.id`, `Task.performer.modifierExtension`, `Task.requestedPerformer`, `Task.requestedPeriod`

