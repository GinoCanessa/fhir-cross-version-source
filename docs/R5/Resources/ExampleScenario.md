Comparison of 
Generated at Monday, April 14, 2025 6:17:45 PM

### ExampleScenario

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | ExampleScenario |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ExampleScenario` |
| Version | 5.0.0 |
| Description | A walkthrough of a workflow showing the interaction between systems and the instances shared, possibly including the evolution of instances over time. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2308` |
| Database Snapshot Count | `95` |
| Database Differential Count | `63` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ExampleScenario` | `ExampleScenario` | `ExampleScenario` | ExampleScenario | Example of workflow instance | 0..* | ExampleScenario |  |  |
| `ExampleScenario.actor` | `ExampleScenario.actor` | `actor` | ExampleScenario.actor | Individual involved in exchange | 0..* | BackboneElement |  |  |
| `ExampleScenario.actor.description` | `ExampleScenario.actor.description` | `description` | ExampleScenario.actor.description | Details about actor | 0..1 | markdown |  |  |
| `ExampleScenario.actor.extension` | `ExampleScenario.actor.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ExampleScenario.actor.id` | `ExampleScenario.actor.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ExampleScenario.actor.key` | `ExampleScenario.actor.key` | `key` | ExampleScenario.actor.key | ID or acronym of the actor | 1..1 | string |  |  |
| `ExampleScenario.actor.modifierExtension` | `ExampleScenario.actor.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ExampleScenario.actor.title` | `ExampleScenario.actor.title` | `title` | ExampleScenario.actor.title | Label for actor when rendering | 1..1 | string |  |  |
| `ExampleScenario.actor.type` | `ExampleScenario.actor.type` | `type` | ExampleScenario.actor.type | person \| system | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/examplescenario-actor-type|5.0.0` |
| `ExampleScenario.contact` | `ExampleScenario.contact` | `contact` | ExampleScenario.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `ExampleScenario.contained` | `ExampleScenario.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ExampleScenario.copyright` | `ExampleScenario.copyright` | `copyright` | ExampleScenario.copyright | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `ExampleScenario.copyrightLabel` | `ExampleScenario.copyrightLabel` | `copyrightLabel` | ExampleScenario.copyrightLabel | Copyright holder and year(s) | 0..1 | string |  |  |
| `ExampleScenario.date` | `ExampleScenario.date` | `date` | ExampleScenario.date | Date last changed | 0..1 | dateTime |  |  |
| `ExampleScenario.description` | `ExampleScenario.description` | `description` | ExampleScenario.description | Natural language description of the ExampleScenario | 0..1 | markdown |  |  |
| `ExampleScenario.experimental` | `ExampleScenario.experimental` | `experimental` | ExampleScenario.experimental | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `ExampleScenario.extension` | `ExampleScenario.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ExampleScenario.id` | `ExampleScenario.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ExampleScenario.identifier` | `ExampleScenario.identifier` | `identifier` | ExampleScenario.identifier | Additional identifier for the example scenario | 0..* | Identifier |  |  |
| `ExampleScenario.implicitRules` | `ExampleScenario.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ExampleScenario.instance` | `ExampleScenario.instance` | `instance` | ExampleScenario.instance | Data used in the scenario | 0..* | BackboneElement |  |  |
| `ExampleScenario.instance.containedInstance` | `ExampleScenario.instance.containedInstance` | `containedInstance` | ExampleScenario.instance.containedInstance | Resources contained in the instance | 0..* | BackboneElement |  |  |
| `ExampleScenario.instance.containedInstance.extension` | `ExampleScenario.instance.containedInstance.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ExampleScenario.instance.containedInstance.id` | `ExampleScenario.instance.containedInstance.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ExampleScenario.instance.containedInstance.instanceReference` | `ExampleScenario.instance.containedInstance.instanceReference` | `instanceReference` | ExampleScenario.instance.containedInstance.instanceReference | Key of contained instance | 1..1 | string |  |  |
| `ExampleScenario.instance.containedInstance.modifierExtension` | `ExampleScenario.instance.containedInstance.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ExampleScenario.instance.containedInstance.versionReference` | `ExampleScenario.instance.containedInstance.versionReference` | `versionReference` | ExampleScenario.instance.containedInstance.versionReference | Key of contained instance version | 0..1 | string |  |  |
| `ExampleScenario.instance.content` | `ExampleScenario.instance.content` | `content` | ExampleScenario.instance.content | Example instance data | 0..1 | Reference |  |  |
| `ExampleScenario.instance.description` | `ExampleScenario.instance.description` | `description` | ExampleScenario.instance.description | Human-friendly description of the instance | 0..1 | markdown |  |  |
| `ExampleScenario.instance.extension` | `ExampleScenario.instance.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ExampleScenario.instance.id` | `ExampleScenario.instance.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ExampleScenario.instance.key` | `ExampleScenario.instance.key` | `key` | ExampleScenario.instance.key | ID or acronym of the instance | 1..1 | string |  |  |
| `ExampleScenario.instance.modifierExtension` | `ExampleScenario.instance.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ExampleScenario.instance.structureProfile[x]` | `ExampleScenario.instance.structureProfile[x]` | `structureProfile[x]` | ExampleScenario.instance.structureProfile[x] | Rules instance adheres to | 0..1 | canonical, uri |  |  |
| `ExampleScenario.instance.structureType` | `ExampleScenario.instance.structureType` | `structureType` | ExampleScenario.instance.structureType | Data structure for example | 1..1 | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/examplescenario-instance-type` |
| `ExampleScenario.instance.structureVersion` | `ExampleScenario.instance.structureVersion` | `structureVersion` | ExampleScenario.instance.structureVersion | E.g. 4.0.1 | 0..1 | string |  |  |
| `ExampleScenario.instance.title` | `ExampleScenario.instance.title` | `title` | ExampleScenario.instance.title | Label for instance | 1..1 | string |  |  |
| `ExampleScenario.instance.version` | `ExampleScenario.instance.version` | `version` | ExampleScenario.instance.version | Snapshot of instance that changes | 0..* | BackboneElement |  |  |
| `ExampleScenario.instance.version.content` | `ExampleScenario.instance.version.content` | `content` | ExampleScenario.instance.version.content | Example instance version data | 0..1 | Reference |  |  |
| `ExampleScenario.instance.version.description` | `ExampleScenario.instance.version.description` | `description` | ExampleScenario.instance.version.description | Details about version | 0..1 | markdown |  |  |
| `ExampleScenario.instance.version.extension` | `ExampleScenario.instance.version.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ExampleScenario.instance.version.id` | `ExampleScenario.instance.version.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ExampleScenario.instance.version.key` | `ExampleScenario.instance.version.key` | `key` | ExampleScenario.instance.version.key | ID or acronym of the version | 1..1 | string |  |  |
| `ExampleScenario.instance.version.modifierExtension` | `ExampleScenario.instance.version.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ExampleScenario.instance.version.title` | `ExampleScenario.instance.version.title` | `title` | ExampleScenario.instance.version.title | Label for instance version | 1..1 | string |  |  |
| `ExampleScenario.jurisdiction` | `ExampleScenario.jurisdiction` | `jurisdiction` | ExampleScenario.jurisdiction | Intended jurisdiction for example scenario (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `ExampleScenario.language` | `ExampleScenario.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `ExampleScenario.meta` | `ExampleScenario.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ExampleScenario.modifierExtension` | `ExampleScenario.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ExampleScenario.name` | `ExampleScenario.name` | `name` | ExampleScenario.name | To be removed? | 0..1 | string |  |  |
| `ExampleScenario.process` | `ExampleScenario.process` | `process` | ExampleScenario.process | Major process within scenario | 0..* | BackboneElement |  |  |
| `ExampleScenario.process.description` | `ExampleScenario.process.description` | `description` | ExampleScenario.process.description | Human-friendly description of the process | 0..1 | markdown |  |  |
| `ExampleScenario.process.extension` | `ExampleScenario.process.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ExampleScenario.process.id` | `ExampleScenario.process.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ExampleScenario.process.modifierExtension` | `ExampleScenario.process.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ExampleScenario.process.postConditions` | `ExampleScenario.process.postConditions` | `postConditions` | ExampleScenario.process.postConditions | Status after successful completion | 0..1 | markdown |  |  |
| `ExampleScenario.process.preConditions` | `ExampleScenario.process.preConditions` | `preConditions` | ExampleScenario.process.preConditions | Status before process starts | 0..1 | markdown |  |  |
| `ExampleScenario.process.step` | `ExampleScenario.process.step` | `step` | ExampleScenario.process.step | Event within of the process | 0..* | BackboneElement |  |  |
| `ExampleScenario.process.step.alternative` | `ExampleScenario.process.step.alternative` | `alternative` | ExampleScenario.process.step.alternative | Alternate non-typical step action | 0..* | BackboneElement |  |  |
| `ExampleScenario.process.step.alternative.description` | `ExampleScenario.process.step.alternative.description` | `description` | ExampleScenario.process.step.alternative.description | Human-readable description of option | 0..1 | markdown |  |  |
| `ExampleScenario.process.step.alternative.extension` | `ExampleScenario.process.step.alternative.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ExampleScenario.process.step.alternative.id` | `ExampleScenario.process.step.alternative.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ExampleScenario.process.step.alternative.modifierExtension` | `ExampleScenario.process.step.alternative.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ExampleScenario.process.step.alternative.step` | `ExampleScenario.process.step.alternative.step` | `step` | ExampleScenario.process.step.alternative.step | Alternative action(s) | 0..* | ExampleScenario.process.step |  |  |
| `ExampleScenario.process.step.alternative.title` | `ExampleScenario.process.step.alternative.title` | `title` | ExampleScenario.process.step.alternative.title | Label for alternative | 1..1 | string |  |  |
| `ExampleScenario.process.step.extension` | `ExampleScenario.process.step.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ExampleScenario.process.step.id` | `ExampleScenario.process.step.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ExampleScenario.process.step.modifierExtension` | `ExampleScenario.process.step.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ExampleScenario.process.step.number` | `ExampleScenario.process.step.number` | `number` | ExampleScenario.process.step.number | Sequential number of the step | 0..1 | string |  |  |
| `ExampleScenario.process.step.operation` | `ExampleScenario.process.step.operation` | `operation` | ExampleScenario.process.step.operation | Step is simple action | 0..1 | BackboneElement |  |  |
| `ExampleScenario.process.step.operation.description` | `ExampleScenario.process.step.operation.description` | `description` | ExampleScenario.process.step.operation.description | Human-friendly description of the operation | 0..1 | markdown |  |  |
| `ExampleScenario.process.step.operation.extension` | `ExampleScenario.process.step.operation.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ExampleScenario.process.step.operation.id` | `ExampleScenario.process.step.operation.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ExampleScenario.process.step.operation.initiator` | `ExampleScenario.process.step.operation.initiator` | `initiator` | ExampleScenario.process.step.operation.initiator | Who starts the operation | 0..1 | string |  |  |
| `ExampleScenario.process.step.operation.initiatorActive` | `ExampleScenario.process.step.operation.initiatorActive` | `initiatorActive` | ExampleScenario.process.step.operation.initiatorActive | Initiator stays active? | 0..1 | boolean |  |  |
| `ExampleScenario.process.step.operation.modifierExtension` | `ExampleScenario.process.step.operation.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ExampleScenario.process.step.operation.receiver` | `ExampleScenario.process.step.operation.receiver` | `receiver` | ExampleScenario.process.step.operation.receiver | Who receives the operation | 0..1 | string |  |  |
| `ExampleScenario.process.step.operation.receiverActive` | `ExampleScenario.process.step.operation.receiverActive` | `receiverActive` | ExampleScenario.process.step.operation.receiverActive | Receiver stays active? | 0..1 | boolean |  |  |
| `ExampleScenario.process.step.operation.request` | `ExampleScenario.process.step.operation.request` | `request` | ExampleScenario.process.step.operation.request | Instance transmitted on invocation | 0..1 | ExampleScenario.instance.containedInstance |  |  |
| `ExampleScenario.process.step.operation.response` | `ExampleScenario.process.step.operation.response` | `response` | ExampleScenario.process.step.operation.response | Instance transmitted on invocation response | 0..1 | ExampleScenario.instance.containedInstance |  |  |
| `ExampleScenario.process.step.operation.title` | `ExampleScenario.process.step.operation.title` | `title` | ExampleScenario.process.step.operation.title | Label for step | 1..1 | string |  |  |
| `ExampleScenario.process.step.operation.type` | `ExampleScenario.process.step.operation.type` | `type` | ExampleScenario.process.step.operation.type | Kind of action | 0..1 | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/testscript-operation-codes` |
| `ExampleScenario.process.step.pause` | `ExampleScenario.process.step.pause` | `pause` | ExampleScenario.process.step.pause | Pause in the flow? | 0..1 | boolean |  |  |
| `ExampleScenario.process.step.process` | `ExampleScenario.process.step.process` | `process` | ExampleScenario.process.step.process | Step is nested process | 0..1 | ExampleScenario.process |  |  |
| `ExampleScenario.process.step.workflow` | `ExampleScenario.process.step.workflow` | `workflow` | ExampleScenario.process.step.workflow | Step is nested workflow | 0..1 | canonical(http://hl7.org/fhir/StructureDefinition/ExampleScenario) |  |  |
| `ExampleScenario.process.title` | `ExampleScenario.process.title` | `title` | ExampleScenario.process.title | Label for procss | 1..1 | string |  |  |
| `ExampleScenario.publisher` | `ExampleScenario.publisher` | `publisher` | ExampleScenario.publisher | Name of the publisher/steward (organization or individual) | 0..1 | string |  |  |
| `ExampleScenario.purpose` | `ExampleScenario.purpose` | `purpose` | ExampleScenario.purpose | The purpose of the example, e.g. to illustrate a scenario | 0..1 | markdown |  |  |
| `ExampleScenario.status` | `ExampleScenario.status` | `status` | ExampleScenario.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|5.0.0` |
| `ExampleScenario.text` | `ExampleScenario.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `ExampleScenario.title` | `ExampleScenario.title` | `title` | ExampleScenario.title | Name for this example scenario (human friendly) | 0..1 | string |  |  |
| `ExampleScenario.url` | `ExampleScenario.url` | `url` | ExampleScenario.url | Canonical identifier for this example scenario, represented as a URI (globally unique) | 0..1 | uri |  |  |
| `ExampleScenario.useContext` | `ExampleScenario.useContext` | `useContext` | ExampleScenario.useContext | The context that the content is intended to support | 0..* | UsageContext |  |  |
| `ExampleScenario.version` | `ExampleScenario.version` | `version` | ExampleScenario.version | Business version of the example scenario | 0..1 | string |  |  |
| `ExampleScenario.versionAlgorithm[x]` | `ExampleScenario.versionAlgorithm[x]` | `versionAlgorithm[x]` | ExampleScenario.versionAlgorithm[x] | How to compare versions | 0..1 | Coding, string | `Extensible` | `http://hl7.org/fhir/ValueSet/version-algorithm` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [ExampleScenario](/docs/R4/Resources/ExampleScenario.md)<br/> `http://hl7.org/fhir/StructureDefinition/ExampleScenario\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1489`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1490`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ExampleScenario](/docs/R4B/Resources/ExampleScenario.md)<br/> `http://hl7.org/fhir/StructureDefinition/ExampleScenario\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `978`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1207`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ExampleScenario](/docs/R5/Resources/ExampleScenario.md)<br/> `http://hl7.org/fhir/StructureDefinition/ExampleScenario\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ExampleScenario from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | [R4 ExampleScenario](/docs/R4/Resources/ExampleScenario.md)| Relationship | [R4B ExampleScenario](/docs/R4B/Resources/ExampleScenario.md)| Relationship | R5 ExampleScenario
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `ExampleScenario`| _Equivalent_<br/>(26687/26688)| `ExampleScenario`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(41762)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(41763)| **`ExampleScenario`**
| | | | | `ExampleScenario.id`| _Equivalent_<br/>(26689/26690)| `ExampleScenario.id`| _Equivalent_<br/>(41764/41765)| **`ExampleScenario.id`**
| | | | | `ExampleScenario.meta`| _Equivalent_<br/>(26691/26692)| `ExampleScenario.meta`| _Equivalent_<br/>(41766/41767)| **`ExampleScenario.meta`**
| | | | | `ExampleScenario.implicitRules`| _Equivalent_<br/>(26693/26694)| `ExampleScenario.implicitRules`| _Equivalent_<br/>(41768/41769)| **`ExampleScenario.implicitRules`**
| | | | | `ExampleScenario.language`| _Equivalent_<br/>(26695/26696)| `ExampleScenario.language`| _Equivalent_<br/>(41770/41771)| **`ExampleScenario.language`**
| | | | | `ExampleScenario.text`| _Equivalent_<br/>(26697/26698)| `ExampleScenario.text`| _Equivalent_<br/>(41772/41773)| **`ExampleScenario.text`**
| | | | | `ExampleScenario.contained`| _Equivalent_<br/>(26699/26700)| `ExampleScenario.contained`| _Equivalent_<br/>(41774/41775)| **`ExampleScenario.contained`**
| | | | | `ExampleScenario.extension`| _Equivalent_<br/>(26701/26702)| `ExampleScenario.extension`| _Equivalent_<br/>(41776/41777)| **`ExampleScenario.extension`**
| | | | | `ExampleScenario.modifierExtension`| _Equivalent_<br/>(26703/26704)| `ExampleScenario.modifierExtension`| _Equivalent_<br/>(41778/41779)| **`ExampleScenario.modifierExtension`**
| | | | | `ExampleScenario.url`| _Equivalent_<br/>(26705/26706)| `ExampleScenario.url`| _Equivalent_<br/>(41780/41781)| **`ExampleScenario.url`**
| | | | | `ExampleScenario.identifier`| _Equivalent_<br/>(26707/26708)| `ExampleScenario.identifier`| _Equivalent_<br/>(41782/41783)| **`ExampleScenario.identifier`**
| | | | | `ExampleScenario.version`| _Equivalent_<br/>(26709/26710)| `ExampleScenario.version`| _Equivalent_<br/>(41784/41785)| **`ExampleScenario.version`**
| | | | | | | | | **`ExampleScenario.versionAlgorithm[x]`**
| | | | | `ExampleScenario.name`| _Equivalent_<br/>(26711/26712)| `ExampleScenario.name`| _Equivalent_<br/>(41786/41787)| **`ExampleScenario.name`**
| | | | | | | | | **`ExampleScenario.title`**
| | | | | `ExampleScenario.status`| _Equivalent_<br/>(26713/26714)| `ExampleScenario.status`| _Equivalent_<br/>(41788/41789)| **`ExampleScenario.status`**
| | | | | `ExampleScenario.experimental`| _Equivalent_<br/>(26715/26716)| `ExampleScenario.experimental`| _Equivalent_<br/>(41790/41791)| **`ExampleScenario.experimental`**
| | | | | `ExampleScenario.date`| _Equivalent_<br/>(26717/26718)| `ExampleScenario.date`| _Equivalent_<br/>(41792/41793)| **`ExampleScenario.date`**
| | | | | `ExampleScenario.publisher`| _Equivalent_<br/>(26719/26720)| `ExampleScenario.publisher`| _Equivalent_<br/>(41794/41795)| **`ExampleScenario.publisher`**
| | | | | `ExampleScenario.contact`| _Equivalent_<br/>(26721/26722)| `ExampleScenario.contact`| _Equivalent_<br/>(41796/41797)| **`ExampleScenario.contact`**
| | | | | | | | | **`ExampleScenario.description`**
| | | | | `ExampleScenario.useContext`| _Equivalent_<br/>(26723/26724)| `ExampleScenario.useContext`| _Equivalent_<br/>(41798/41799)| **`ExampleScenario.useContext`**
| | | | | `ExampleScenario.jurisdiction`| _Equivalent_<br/>(26725/26726)| `ExampleScenario.jurisdiction`| _Equivalent_<br/>(41800/41801)| **`ExampleScenario.jurisdiction`**
| | | | | `ExampleScenario.purpose`| _Equivalent_<br/>(26729/26730)| `ExampleScenario.purpose`| _Equivalent_<br/>(41804/41805)| **`ExampleScenario.purpose`**
| | | | | `ExampleScenario.copyright`| _Equivalent_<br/>(26727/26728)| `ExampleScenario.copyright`| _Equivalent_<br/>(41802/41803)| **`ExampleScenario.copyright`**
| | | | | | | | | **`ExampleScenario.copyrightLabel`**
| | | | | `ExampleScenario.actor`| _Equivalent_<br/>(26731/26732)| `ExampleScenario.actor`| _Equivalent_<br/>(41806/41807)| **`ExampleScenario.actor`**
| | | | | `ExampleScenario.actor.id`| _Equivalent_<br/>(26733/26734)| `ExampleScenario.actor.id`| _Equivalent_<br/>(41808/41809)| **`ExampleScenario.actor.id`**
| | | | | `ExampleScenario.actor.extension`| _Equivalent_<br/>(26735/26736)| `ExampleScenario.actor.extension`| _Equivalent_<br/>(41810/41811)| **`ExampleScenario.actor.extension`**
| | | | | `ExampleScenario.actor.modifierExtension`| _Equivalent_<br/>(26737/26738)| `ExampleScenario.actor.modifierExtension`| _Equivalent_<br/>(41812/41813)| **`ExampleScenario.actor.modifierExtension`**
| | | | | `ExampleScenario.actor.actorId`| _Equivalent_<br/>(26739/26740)| `ExampleScenario.actor.actorId`| _Equivalent_<br/>(1786/2030)| **`ExampleScenario.actor.key`**
| | | | | `ExampleScenario.actor.type`| _Equivalent_<br/>(26741/26742)| `ExampleScenario.actor.type`| _Equivalent_<br/>(41814/41815)| **`ExampleScenario.actor.type`**
| | | | | `ExampleScenario.actor.name`| _Equivalent_<br/>(26743/26744)| `ExampleScenario.actor.name`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1787)<hr/>←←←← _Equivalent_ ←←←← <br/>(2031)| **`ExampleScenario.actor.title`**
| | | | | `ExampleScenario.actor.description`| _Equivalent_<br/>(26745/26746)| `ExampleScenario.actor.description`| _Equivalent_<br/>(41816/41817)| **`ExampleScenario.actor.description`**
| | | | | `ExampleScenario.instance`| _Equivalent_<br/>(26747/26748)| `ExampleScenario.instance`| _Equivalent_<br/>(41818/41819)| **`ExampleScenario.instance`**
| | | | | `ExampleScenario.instance.id`| _Equivalent_<br/>(26749/26750)| `ExampleScenario.instance.id`| _Equivalent_<br/>(41820/41821)| **`ExampleScenario.instance.id`**
| | | | | `ExampleScenario.instance.extension`| _Equivalent_<br/>(26751/26752)| `ExampleScenario.instance.extension`| _Equivalent_<br/>(41822/41823)| **`ExampleScenario.instance.extension`**
| | | | | `ExampleScenario.instance.modifierExtension`| _Equivalent_<br/>(26753/26754)| `ExampleScenario.instance.modifierExtension`| _Equivalent_<br/>(41824/41825)| **`ExampleScenario.instance.modifierExtension`**
| | | | | `ExampleScenario.instance.resourceId`| _Equivalent_<br/>(26755/26756)| `ExampleScenario.instance.resourceId`| _Equivalent_<br/>(1788/2032)| **`ExampleScenario.instance.key`**
| | | | | `ExampleScenario.instance.resourceType`| →→→→ _Equivalent_ →→→→ <br/>(26757)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(26758)| `ExampleScenario.instance.resourceType`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1789)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2033)| **`ExampleScenario.instance.structureType`**
| | | | | | | | | **`ExampleScenario.instance.structureVersion`**
| | | | | | | | | **`ExampleScenario.instance.structureProfile[x]`**
| | | | | `ExampleScenario.instance.name`| _Equivalent_<br/>(26759/26760)| `ExampleScenario.instance.name`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1790)<hr/>←←←← _Equivalent_ ←←←← <br/>(2034)| **`ExampleScenario.instance.title`**
| | | | | `ExampleScenario.instance.description`| _Equivalent_<br/>(26761/26762)| `ExampleScenario.instance.description`| _Equivalent_<br/>(41826/41827)| **`ExampleScenario.instance.description`**
| | | | | | | | | **`ExampleScenario.instance.content`**
| | | | | `ExampleScenario.instance.version`| _Equivalent_<br/>(26763/26764)| `ExampleScenario.instance.version`| _Equivalent_<br/>(41828/41829)| **`ExampleScenario.instance.version`**
| | | | | `ExampleScenario.instance.version.id`| _Equivalent_<br/>(26765/26766)| `ExampleScenario.instance.version.id`| _Equivalent_<br/>(41830/41831)| **`ExampleScenario.instance.version.id`**
| | | | | `ExampleScenario.instance.version.extension`| _Equivalent_<br/>(26767/26768)| `ExampleScenario.instance.version.extension`| _Equivalent_<br/>(41832/41833)| **`ExampleScenario.instance.version.extension`**
| | | | | `ExampleScenario.instance.version.modifierExtension`| _Equivalent_<br/>(26769/26770)| `ExampleScenario.instance.version.modifierExtension`| _Equivalent_<br/>(41834/41835)| **`ExampleScenario.instance.version.modifierExtension`**
| | | | | `ExampleScenario.instance.version.versionId`| _Equivalent_<br/>(26771/26772)| `ExampleScenario.instance.version.versionId`| _Equivalent_<br/>(1794/2038)| **`ExampleScenario.instance.version.key`**
| | | | | | | | | **`ExampleScenario.instance.version.title`**
| | | | | `ExampleScenario.instance.version.description`| _Equivalent_<br/>(26773/26774)| `ExampleScenario.instance.version.description`| →→→→ _Equivalent_ →→→→ <br/>(41836)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(41837)| **`ExampleScenario.instance.version.description`**
| | | | | | | | | **`ExampleScenario.instance.version.content`**
| | | | | `ExampleScenario.instance.containedInstance`| _Equivalent_<br/>(26775/26776)| `ExampleScenario.instance.containedInstance`| _Equivalent_<br/>(41838/41839)| **`ExampleScenario.instance.containedInstance`**
| | | | | `ExampleScenario.instance.containedInstance.id`| _Equivalent_<br/>(26777/26778)| `ExampleScenario.instance.containedInstance.id`| _Equivalent_<br/>(41840/41841)| **`ExampleScenario.instance.containedInstance.id`**
| | | | | `ExampleScenario.instance.containedInstance.extension`| _Equivalent_<br/>(26779/26780)| `ExampleScenario.instance.containedInstance.extension`| _Equivalent_<br/>(41842/41843)| **`ExampleScenario.instance.containedInstance.extension`**
| | | | | `ExampleScenario.instance.containedInstance.modifierExtension`| _Equivalent_<br/>(26781/26782)| `ExampleScenario.instance.containedInstance.modifierExtension`| _Equivalent_<br/>(41844/41845)| **`ExampleScenario.instance.containedInstance.modifierExtension`**
| | | | | `ExampleScenario.instance.containedInstance.resourceId`| _Equivalent_<br/>(26783/26784)| `ExampleScenario.instance.containedInstance.resourceId`| _Equivalent_<br/>(1791/2035)| **`ExampleScenario.instance.containedInstance.instanceReference`**
| | | | | `ExampleScenario.instance.containedInstance.versionId`| _Equivalent_<br/>(26785/26786)| `ExampleScenario.instance.containedInstance.versionId`| _Equivalent_<br/>(1792/2036)| **`ExampleScenario.instance.containedInstance.versionReference`**
| | | | | `ExampleScenario.process`| _Equivalent_<br/>(26787/26788)| `ExampleScenario.process`| _Equivalent_<br/>(41846/41847)| **`ExampleScenario.process`**
| | | | | `ExampleScenario.process.id`| _Equivalent_<br/>(26789/26790)| `ExampleScenario.process.id`| _Equivalent_<br/>(41848/41849)| **`ExampleScenario.process.id`**
| | | | | `ExampleScenario.process.extension`| _Equivalent_<br/>(26791/26792)| `ExampleScenario.process.extension`| _Equivalent_<br/>(41850/41851)| **`ExampleScenario.process.extension`**
| | | | | `ExampleScenario.process.modifierExtension`| _Equivalent_<br/>(26793/26794)| `ExampleScenario.process.modifierExtension`| _Equivalent_<br/>(41852/41853)| **`ExampleScenario.process.modifierExtension`**
| | | | | `ExampleScenario.process.title`| _Equivalent_<br/>(26795/26796)| `ExampleScenario.process.title`| _Equivalent_<br/>(41854/41855)| **`ExampleScenario.process.title`**
| | | | | `ExampleScenario.process.description`| _Equivalent_<br/>(26797/26798)| `ExampleScenario.process.description`| _Equivalent_<br/>(41856/41857)| **`ExampleScenario.process.description`**
| | | | | `ExampleScenario.process.preConditions`| _Equivalent_<br/>(26799/26800)| `ExampleScenario.process.preConditions`| _Equivalent_<br/>(41858/41859)| **`ExampleScenario.process.preConditions`**
| | | | | `ExampleScenario.process.postConditions`| _Equivalent_<br/>(26801/26802)| `ExampleScenario.process.postConditions`| _Equivalent_<br/>(41860/41861)| **`ExampleScenario.process.postConditions`**
| | | | | `ExampleScenario.process.step`| _Equivalent_<br/>(26803/26804)| `ExampleScenario.process.step`| _Equivalent_<br/>(41862/41863)| **`ExampleScenario.process.step`**
| | | | | `ExampleScenario.process.step.id`| _Equivalent_<br/>(26805/26806)| `ExampleScenario.process.step.id`| _Equivalent_<br/>(41864/41865)| **`ExampleScenario.process.step.id`**
| | | | | `ExampleScenario.process.step.extension`| _Equivalent_<br/>(26807/26808)| `ExampleScenario.process.step.extension`| _Equivalent_<br/>(41866/41867)| **`ExampleScenario.process.step.extension`**
| | | | | `ExampleScenario.process.step.modifierExtension`| _Equivalent_<br/>(26809/26810)| `ExampleScenario.process.step.modifierExtension`| _Equivalent_<br/>(41868/41869)| **`ExampleScenario.process.step.modifierExtension`**
| | | | | | | | | **`ExampleScenario.process.step.number`**
| | | | | `ExampleScenario.process.step.process`| _Equivalent_<br/>(26811/26812)| `ExampleScenario.process.step.process`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(41870)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(41871)| **`ExampleScenario.process.step.process`**
| | | | | | | | | **`ExampleScenario.process.step.workflow`**
| | | | | `ExampleScenario.process.step.operation`| _Equivalent_<br/>(26815/26816)| `ExampleScenario.process.step.operation`| _Equivalent_<br/>(41874/41875)| **`ExampleScenario.process.step.operation`**
| | | | | `ExampleScenario.process.step.operation.id`| _Equivalent_<br/>(26817/26818)| `ExampleScenario.process.step.operation.id`| _Equivalent_<br/>(41876/41877)| **`ExampleScenario.process.step.operation.id`**
| | | | | `ExampleScenario.process.step.operation.extension`| _Equivalent_<br/>(26819/26820)| `ExampleScenario.process.step.operation.extension`| _Equivalent_<br/>(41878/41879)| **`ExampleScenario.process.step.operation.extension`**
| | | | | `ExampleScenario.process.step.operation.modifierExtension`| _Equivalent_<br/>(26821/26822)| `ExampleScenario.process.step.operation.modifierExtension`| _Equivalent_<br/>(41880/41881)| **`ExampleScenario.process.step.operation.modifierExtension`**
| | | | | `ExampleScenario.process.step.operation.type`| _Equivalent_<br/>(26825/26826)| `ExampleScenario.process.step.operation.type`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(41883)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(41884)| **`ExampleScenario.process.step.operation.type`**
| | | | | `ExampleScenario.process.step.operation.name`| _Equivalent_<br/>(26827/26828)| `ExampleScenario.process.step.operation.name`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1793)<hr/>←←←← _Equivalent_ ←←←← <br/>(2037)| **`ExampleScenario.process.step.operation.title`**
| | | | | `ExampleScenario.process.step.operation.initiator`| _Equivalent_<br/>(26829/26830)| `ExampleScenario.process.step.operation.initiator`| _Equivalent_<br/>(41885/41886)| **`ExampleScenario.process.step.operation.initiator`**
| | | | | `ExampleScenario.process.step.operation.receiver`| _Equivalent_<br/>(26831/26832)| `ExampleScenario.process.step.operation.receiver`| _Equivalent_<br/>(41887/41888)| **`ExampleScenario.process.step.operation.receiver`**
| | | | | `ExampleScenario.process.step.operation.description`| _Equivalent_<br/>(26833/26834)| `ExampleScenario.process.step.operation.description`| _Equivalent_<br/>(41889/41890)| **`ExampleScenario.process.step.operation.description`**
| | | | | `ExampleScenario.process.step.operation.initiatorActive`| _Equivalent_<br/>(26835/26836)| `ExampleScenario.process.step.operation.initiatorActive`| _Equivalent_<br/>(41891/41892)| **`ExampleScenario.process.step.operation.initiatorActive`**
| | | | | `ExampleScenario.process.step.operation.receiverActive`| _Equivalent_<br/>(26837/26838)| `ExampleScenario.process.step.operation.receiverActive`| _Equivalent_<br/>(41893/41894)| **`ExampleScenario.process.step.operation.receiverActive`**
| | | | | `ExampleScenario.process.step.operation.request`| _Equivalent_<br/>(26839/26840)| `ExampleScenario.process.step.operation.request`| _Equivalent_<br/>(41895/41896)| **`ExampleScenario.process.step.operation.request`**
| | | | | `ExampleScenario.process.step.operation.response`| _Equivalent_<br/>(26841/26842)| `ExampleScenario.process.step.operation.response`| _Equivalent_<br/>(41897/41898)| **`ExampleScenario.process.step.operation.response`**
| | | | | `ExampleScenario.process.step.alternative`| _Equivalent_<br/>(26843/26844)| `ExampleScenario.process.step.alternative`| _Equivalent_<br/>(41899/41900)| **`ExampleScenario.process.step.alternative`**
| | | | | `ExampleScenario.process.step.alternative.id`| _Equivalent_<br/>(26845/26846)| `ExampleScenario.process.step.alternative.id`| _Equivalent_<br/>(41901/41902)| **`ExampleScenario.process.step.alternative.id`**
| | | | | `ExampleScenario.process.step.alternative.extension`| _Equivalent_<br/>(26847/26848)| `ExampleScenario.process.step.alternative.extension`| _Equivalent_<br/>(41903/41904)| **`ExampleScenario.process.step.alternative.extension`**
| | | | | `ExampleScenario.process.step.alternative.modifierExtension`| _Equivalent_<br/>(26849/26850)| `ExampleScenario.process.step.alternative.modifierExtension`| _Equivalent_<br/>(41905/41906)| **`ExampleScenario.process.step.alternative.modifierExtension`**
| | | | | `ExampleScenario.process.step.alternative.title`| _Equivalent_<br/>(26851/26852)| `ExampleScenario.process.step.alternative.title`| _Equivalent_<br/>(41907/41908)| **`ExampleScenario.process.step.alternative.title`**
| | | | | `ExampleScenario.process.step.alternative.description`| _Equivalent_<br/>(26853/26854)| `ExampleScenario.process.step.alternative.description`| _Equivalent_<br/>(41909/41910)| **`ExampleScenario.process.step.alternative.description`**
| | | | | `ExampleScenario.process.step.alternative.step`| _Equivalent_<br/>(26855/26856)| `ExampleScenario.process.step.alternative.step`| _Equivalent_<br/>(41911/41912)| **`ExampleScenario.process.step.alternative.step`**
| | | | | `ExampleScenario.process.step.pause`| _Equivalent_<br/>(26813/26814)| `ExampleScenario.process.step.pause`| _Equivalent_<br/>(41872/41873)| **`ExampleScenario.process.step.pause`**
| | | | | *84 of 86 elements used* <br/>remaining elements:<br/>`ExampleScenario.process.step.operation.number`, `ExampleScenario.workflow`| | *84 of 86 elements used* <br/>remaining elements:<br/>`ExampleScenario.process.step.operation.number`, `ExampleScenario.workflow`| | *95 of 95 elements used* 

