Comparison of 
Generated at Monday, April 14, 2025 6:17:22 PM

### ProcessRequest

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | ProcessRequest |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ProcessRequest` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for ProcessRequest Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `565` |
| Database Snapshot Count | `28` |
| Database Differential Count | `17` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ProcessRequest` | `ProcessRequest` | `ProcessRequest` | ProcessRequest | Request to perform some action on or in regards to an existing resource | 0..* | ProcessRequest |  |  |
| `ProcessRequest.action` | `ProcessRequest.action` | `action` |  | cancel \| poll \| reprocess \| status | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/actionlist` |
| `ProcessRequest.contained` | `ProcessRequest.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ProcessRequest.created` | `ProcessRequest.created` | `created` |  | Creation date | 0..1 | dateTime |  |  |
| `ProcessRequest.exclude` | `ProcessRequest.exclude` | `exclude` |  | Resource type(s) to exclude | 0..* | string |  |  |
| `ProcessRequest.extension` | `ProcessRequest.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ProcessRequest.id` | `ProcessRequest.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ProcessRequest.identifier` | `ProcessRequest.identifier` | `identifier` |  | Business Identifier | 0..* | Identifier |  |  |
| `ProcessRequest.implicitRules` | `ProcessRequest.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ProcessRequest.include` | `ProcessRequest.include` | `include` |  | Resource type(s) to include | 0..* | string |  |  |
| `ProcessRequest.item` | `ProcessRequest.item` | `item` |  | Items to re-adjudicate | 0..* | BackboneElement |  |  |
| `ProcessRequest.item.extension` | `ProcessRequest.item.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ProcessRequest.item.id` | `ProcessRequest.item.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ProcessRequest.item.modifierExtension` | `ProcessRequest.item.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ProcessRequest.item.sequenceLinkId` | `ProcessRequest.item.sequenceLinkId` | `sequenceLinkId` |  | Service instance | 1..1 | integer |  |  |
| `ProcessRequest.language` | `ProcessRequest.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `ProcessRequest.meta` | `ProcessRequest.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ProcessRequest.modifierExtension` | `ProcessRequest.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ProcessRequest.nullify` | `ProcessRequest.nullify` | `nullify` |  | Remove history | 0..1 | boolean |  |  |
| `ProcessRequest.organization` | `ProcessRequest.organization` | `organization` |  | Responsible organization | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `ProcessRequest.period` | `ProcessRequest.period` | `period` |  | Selection period | 0..1 | Period |  |  |
| `ProcessRequest.provider` | `ProcessRequest.provider` | `provider` |  | Responsible practitioner | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `ProcessRequest.reference` | `ProcessRequest.reference` | `reference` |  | Reference number/string | 0..1 | string |  |  |
| `ProcessRequest.request` | `ProcessRequest.request` | `request` |  | Reference to the Request resource | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `ProcessRequest.response` | `ProcessRequest.response` | `response` |  | Reference to the Response resource | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `ProcessRequest.status` | `ProcessRequest.status` | `status` |  | active \| cancelled \| draft \| entered-in-error | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/fm-status` |
| `ProcessRequest.target` | `ProcessRequest.target` | `target` |  | Party which is the target of the request | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `ProcessRequest.text` | `ProcessRequest.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ProcessRequest](/docs/R2/Resources/ProcessRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ProcessRequest\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `145`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `311`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ProcessRequest](/docs/R3/Resources/ProcessRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ProcessRequest\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `502`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `719`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Task](/docs/R4/Resources/Task.md)<br/> `http://hl7.org/fhir/StructureDefinition/Task\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1633`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1634`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Task](/docs/R4B/Resources/Task.md)<br/> `http://hl7.org/fhir/StructureDefinition/Task\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1053`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1282`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Task](/docs/R5/Resources/Task.md)<br/> `http://hl7.org/fhir/StructureDefinition/Task\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ProcessRequest from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 ProcessRequest](/docs/R2/Resources/ProcessRequest.md)| Relationship | R3 ProcessRequest| Relationship | [R4 Task](/docs/R4/Resources/Task.md)| Relationship | [R4B Task](/docs/R4B/Resources/Task.md)| Relationship | [R5 Task](/docs/R5/Resources/Task.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `ProcessRequest`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(7342)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7343)| **`ProcessRequest`**| | | | | | | 
| `ProcessRequest.id`| _Equivalent_<br/>(7344/7345)| **`ProcessRequest.id`**| | | | | | | 
| `ProcessRequest.meta`| _Equivalent_<br/>(7346/7347)| **`ProcessRequest.meta`**| | | | | | | 
| `ProcessRequest.implicitRules`| _Equivalent_<br/>(7348/7349)| **`ProcessRequest.implicitRules`**| | | | | | | 
| `ProcessRequest.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7350)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7351)| **`ProcessRequest.language`**| | | | | | | 
| `ProcessRequest.text`| _Equivalent_<br/>(7352/7353)| **`ProcessRequest.text`**| | | | | | | 
| `ProcessRequest.contained`| _Equivalent_<br/>(7354/7355)| **`ProcessRequest.contained`**| | | | | | | 
| `ProcessRequest.extension`| _Equivalent_<br/>(7356/7357)| **`ProcessRequest.extension`**| | | | | | | 
| `ProcessRequest.modifierExtension`| _Equivalent_<br/>(7358/7359)| **`ProcessRequest.modifierExtension`**| | | | | | | 
| `ProcessRequest.identifier`| _Equivalent_<br/>(7362/7363)| **`ProcessRequest.identifier`**| | | | | | | 
| | | **`ProcessRequest.status`**| | | | | | | 
| `ProcessRequest.action`| →→→→ _Equivalent_ →→→→ <br/>(7360)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7361)| **`ProcessRequest.action`**| | | | | | | 
| `ProcessRequest.target`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7366)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7367)| **`ProcessRequest.target`**| | | | | | | 
| `ProcessRequest.created`| _Equivalent_<br/>(7364/7365)| **`ProcessRequest.created`**| | | | | | | 
| `ProcessRequest.provider`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7368)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7369)| **`ProcessRequest.provider`**| | | | | | | 
| `ProcessRequest.organization`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7370)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7371)| **`ProcessRequest.organization`**| | | | | | | 
| `ProcessRequest.request`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7372)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7373)| **`ProcessRequest.request`**| | | | | | | 
| `ProcessRequest.response`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7374)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7375)| **`ProcessRequest.response`**| | | | | | | 
| `ProcessRequest.nullify`| _Equivalent_<br/>(7376/7377)| **`ProcessRequest.nullify`**| | | | | | | 
| `ProcessRequest.reference`| _Equivalent_<br/>(7378/7379)| **`ProcessRequest.reference`**| | | | | | | 
| `ProcessRequest.item`| _Equivalent_<br/>(7380/7381)| **`ProcessRequest.item`**| | | | | | | 
| `ProcessRequest.item.id`| _Equivalent_<br/>(7382/7383)| **`ProcessRequest.item.id`**| | | | | | | 
| `ProcessRequest.item.extension`| _Equivalent_<br/>(7384/7385)| **`ProcessRequest.item.extension`**| | | | | | | 
| `ProcessRequest.item.modifierExtension`| _Equivalent_<br/>(7386/7387)| **`ProcessRequest.item.modifierExtension`**| | | | | | | 
| `ProcessRequest.item.sequenceLinkId`| _Equivalent_<br/>(7388/7389)| **`ProcessRequest.item.sequenceLinkId`**| | | | | | | 
| `ProcessRequest.include`| _Equivalent_<br/>(7390/7391)| **`ProcessRequest.include`**| | | | | | | 
| `ProcessRequest.exclude`| _Equivalent_<br/>(7392/7393)| **`ProcessRequest.exclude`**| | | | | | | 
| `ProcessRequest.period`| _Equivalent_<br/>(7394/7395)| **`ProcessRequest.period`**| | | | | | | 
| *27 of 29 elements used* <br/>remaining elements:<br/>`ProcessRequest.originalRuleset`, `ProcessRequest.ruleset`| | *28 of 28 elements used* | | *0 of 56 elements used* <br/>remaining elements:<br/>`Task`, `Task.authoredOn`, `Task.basedOn`, `Task.businessStatus`, `Task.code`, `Task.contained`, `Task.description`, `Task.encounter`, `Task.executionPeriod`, `Task.extension`, `Task.focus`, `Task.for`, `Task.groupIdentifier`, `Task.id`, `Task.identifier`, `Task.implicitRules`, `Task.input`, `Task.input.extension`, `Task.input.id`, `Task.input.modifierExtension`, `Task.input.type`, `Task.input.value[x]`, `Task.instantiatesCanonical`, `Task.instantiatesUri`, `Task.insurance`, `Task.intent`, `Task.language`, `Task.lastModified`, `Task.location`, `Task.meta`, `Task.modifierExtension`, `Task.note`, `Task.output`, `Task.output.extension`, `Task.output.id`, `Task.output.modifierExtension`, `Task.output.type`, `Task.output.value[x]`, `Task.owner`, `Task.partOf`, `Task.performerType`, `Task.priority`, `Task.reasonCode`, `Task.reasonReference`, `Task.relevantHistory`, `Task.requester`, `Task.restriction`, `Task.restriction.extension`, `Task.restriction.id`, `Task.restriction.modifierExtension`, `Task.restriction.period`, `Task.restriction.recipient`, `Task.restriction.repetitions`, `Task.status`, `Task.statusReason`, `Task.text`| | *0 of 56 elements used* <br/>remaining elements:<br/>`Task`, `Task.authoredOn`, `Task.basedOn`, `Task.businessStatus`, `Task.code`, `Task.contained`, `Task.description`, `Task.encounter`, `Task.executionPeriod`, `Task.extension`, `Task.focus`, `Task.for`, `Task.groupIdentifier`, `Task.id`, `Task.identifier`, `Task.implicitRules`, `Task.input`, `Task.input.extension`, `Task.input.id`, `Task.input.modifierExtension`, `Task.input.type`, `Task.input.value[x]`, `Task.instantiatesCanonical`, `Task.instantiatesUri`, `Task.insurance`, `Task.intent`, `Task.language`, `Task.lastModified`, `Task.location`, `Task.meta`, `Task.modifierExtension`, `Task.note`, `Task.output`, `Task.output.extension`, `Task.output.id`, `Task.output.modifierExtension`, `Task.output.type`, `Task.output.value[x]`, `Task.owner`, `Task.partOf`, `Task.performerType`, `Task.priority`, `Task.reasonCode`, `Task.reasonReference`, `Task.relevantHistory`, `Task.requester`, `Task.restriction`, `Task.restriction.extension`, `Task.restriction.id`, `Task.restriction.modifierExtension`, `Task.restriction.period`, `Task.restriction.recipient`, `Task.restriction.repetitions`, `Task.status`, `Task.statusReason`, `Task.text`| | *0 of 63 elements used* <br/>remaining elements:<br/>`Task`, `Task.authoredOn`, `Task.basedOn`, `Task.businessStatus`, `Task.code`, `Task.contained`, `Task.description`, `Task.doNotPerform`, `Task.encounter`, `Task.executionPeriod`, `Task.extension`, `Task.focus`, `Task.for`, `Task.groupIdentifier`, `Task.id`, `Task.identifier`, `Task.implicitRules`, `Task.input`, `Task.input.extension`, `Task.input.id`, `Task.input.modifierExtension`, `Task.input.type`, `Task.input.value[x]`, `Task.instantiatesCanonical`, `Task.instantiatesUri`, `Task.insurance`, `Task.intent`, `Task.language`, `Task.lastModified`, `Task.location`, `Task.meta`, `Task.modifierExtension`, `Task.note`, `Task.output`, `Task.output.extension`, `Task.output.id`, `Task.output.modifierExtension`, `Task.output.type`, `Task.output.value[x]`, `Task.owner`, `Task.partOf`, `Task.performer`, `Task.performer.actor`, `Task.performer.extension`, `Task.performer.function`, `Task.performer.id`, `Task.performer.modifierExtension`, `Task.priority`, `Task.reason`, `Task.relevantHistory`, `Task.requestedPerformer`, `Task.requestedPeriod`, `Task.requester`, `Task.restriction`, `Task.restriction.extension`, `Task.restriction.id`, `Task.restriction.modifierExtension`, `Task.restriction.period`, `Task.restriction.recipient`, `Task.restriction.repetitions`, `Task.status`, `Task.statusReason`, `Task.text`

