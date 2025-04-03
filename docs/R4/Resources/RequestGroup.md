Comparison of 
Generated at Thursday, April 3, 2025 8:18:21 AM

### RequestGroup

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | RequestGroup |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/RequestGroup` |
| Version | 4.0.1 |
| Description | A group of related requests that can be used to capture intended activities that have inter-dependencies such as "give this medication after that one". |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1146` |
| Database Snapshot Count | `60` |
| Database Differential Count | `43` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `RequestGroup` | `RequestGroup` | `RequestGroup` | RequestGroup | A group of related requests | 0..* | RequestGroup |  |  |
| `RequestGroup.action` | `RequestGroup.action` | `action` | RequestGroup.action | Proposed actions, if any | 0..* | BackboneElement |  |  |
| `RequestGroup.action.action` | `RequestGroup.action.action` | `action` | RequestGroup.action.action | Sub action | 0..* | RequestGroup.action |  |  |
| `RequestGroup.action.cardinalityBehavior` | `RequestGroup.action.cardinalityBehavior` | `cardinalityBehavior` | RequestGroup.action.cardinalityBehavior | single \| multiple | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/action-cardinality-behavior|4.0.1` |
| `RequestGroup.action.code` | `RequestGroup.action.code` | `code` | RequestGroup.action.code | Code representing the meaning of the action or sub-actions | 0..* | CodeableConcept |  |  |
| `RequestGroup.action.condition` | `RequestGroup.action.condition` | `condition` | RequestGroup.action.condition | Whether or not the action is applicable | 0..* | BackboneElement |  |  |
| `RequestGroup.action.condition.expression` | `RequestGroup.action.condition.expression` | `expression` | RequestGroup.action.condition.expression | Boolean-valued expression | 0..1 | Expression |  |  |
| `RequestGroup.action.condition.extension` | `RequestGroup.action.condition.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RequestGroup.action.condition.id` | `RequestGroup.action.condition.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `RequestGroup.action.condition.kind` | `RequestGroup.action.condition.kind` | `kind` | RequestGroup.action.condition.kind | applicability \| start \| stop | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/action-condition-kind|4.0.1` |
| `RequestGroup.action.condition.modifierExtension` | `RequestGroup.action.condition.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `RequestGroup.action.description` | `RequestGroup.action.description` | `description` | RequestGroup.action.description | Short description of the action | 0..1 | string |  |  |
| `RequestGroup.action.documentation` | `RequestGroup.action.documentation` | `documentation` | RequestGroup.action.documentation | Supporting documentation for the intended performer of the action | 0..* | RelatedArtifact |  |  |
| `RequestGroup.action.extension` | `RequestGroup.action.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RequestGroup.action.groupingBehavior` | `RequestGroup.action.groupingBehavior` | `groupingBehavior` | RequestGroup.action.groupingBehavior | visual-group \| logical-group \| sentence-group | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/action-grouping-behavior|4.0.1` |
| `RequestGroup.action.id` | `RequestGroup.action.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `RequestGroup.action.modifierExtension` | `RequestGroup.action.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `RequestGroup.action.participant` | `RequestGroup.action.participant` | `participant` | RequestGroup.action.participant | Who should perform the action | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `RequestGroup.action.precheckBehavior` | `RequestGroup.action.precheckBehavior` | `precheckBehavior` | RequestGroup.action.precheckBehavior | yes \| no | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/action-precheck-behavior|4.0.1` |
| `RequestGroup.action.prefix` | `RequestGroup.action.prefix` | `prefix` | RequestGroup.action.prefix | User-visible prefix for the action (e.g. 1. or A.) | 0..1 | string |  |  |
| `RequestGroup.action.priority` | `RequestGroup.action.priority` | `priority` | RequestGroup.action.priority | routine \| urgent \| asap \| stat | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/request-priority|4.0.1` |
| `RequestGroup.action.relatedAction` | `RequestGroup.action.relatedAction` | `relatedAction` | RequestGroup.action.relatedAction | Relationship to another action | 0..* | BackboneElement |  |  |
| `RequestGroup.action.relatedAction.actionId` | `RequestGroup.action.relatedAction.actionId` | `actionId` | RequestGroup.action.relatedAction.actionId | What action this is related to | 1..1 | id |  |  |
| `RequestGroup.action.relatedAction.extension` | `RequestGroup.action.relatedAction.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RequestGroup.action.relatedAction.id` | `RequestGroup.action.relatedAction.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `RequestGroup.action.relatedAction.modifierExtension` | `RequestGroup.action.relatedAction.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `RequestGroup.action.relatedAction.offset[x]` | `RequestGroup.action.relatedAction.offset[x]` | `offset[x]` | RequestGroup.action.relatedAction.offset[x] | Time offset for the relationship | 0..1 | Duration, Range |  |  |
| `RequestGroup.action.relatedAction.relationship` | `RequestGroup.action.relatedAction.relationship` | `relationship` | RequestGroup.action.relatedAction.relationship | before-start \| before \| before-end \| concurrent-with-start \| concurrent \| concurrent-with-end \| after-start \| after \| after-end | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/action-relationship-type|4.0.1` |
| `RequestGroup.action.requiredBehavior` | `RequestGroup.action.requiredBehavior` | `requiredBehavior` | RequestGroup.action.requiredBehavior | must \| could \| must-unless-documented | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/action-required-behavior|4.0.1` |
| `RequestGroup.action.resource` | `RequestGroup.action.resource` | `resource` | RequestGroup.action.resource | The target of the action | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `RequestGroup.action.selectionBehavior` | `RequestGroup.action.selectionBehavior` | `selectionBehavior` | RequestGroup.action.selectionBehavior | any \| all \| all-or-none \| exactly-one \| at-most-one \| one-or-more | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/action-selection-behavior|4.0.1` |
| `RequestGroup.action.textEquivalent` | `RequestGroup.action.textEquivalent` | `textEquivalent` | RequestGroup.action.textEquivalent | Static text equivalent of the action, used if the dynamic aspects cannot be interpreted by the receiving system | 0..1 | string |  |  |
| `RequestGroup.action.timing[x]` | `RequestGroup.action.timing[x]` | `timing[x]` | RequestGroup.action.timing[x] | When the action should take place | 0..1 | Age, dateTime, Duration, Period, Range, Timing |  |  |
| `RequestGroup.action.title` | `RequestGroup.action.title` | `title` | RequestGroup.action.title | User-visible title | 0..1 | string |  |  |
| `RequestGroup.action.type` | `RequestGroup.action.type` | `type` | RequestGroup.action.type | create \| update \| remove \| fire-event | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/action-type` |
| `RequestGroup.author` | `RequestGroup.author` | `author` | RequestGroup.author | Device or practitioner that authored the request group | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `RequestGroup.authoredOn` | `RequestGroup.authoredOn` | `authoredOn` | RequestGroup.authoredOn | When the request group was authored | 0..1 | dateTime |  |  |
| `RequestGroup.basedOn` | `RequestGroup.basedOn` | `basedOn` | RequestGroup.basedOn | Fulfills plan, proposal, or order | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `RequestGroup.code` | `RequestGroup.code` | `code` | RequestGroup.code | What's being requested/ordered | 0..1 | CodeableConcept |  |  |
| `RequestGroup.contained` | `RequestGroup.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `RequestGroup.encounter` | `RequestGroup.encounter` | `encounter` | RequestGroup.encounter | Created as part of | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `RequestGroup.extension` | `RequestGroup.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RequestGroup.groupIdentifier` | `RequestGroup.groupIdentifier` | `groupIdentifier` | RequestGroup.groupIdentifier | Composite request this is part of | 0..1 | Identifier |  |  |
| `RequestGroup.id` | `RequestGroup.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `RequestGroup.identifier` | `RequestGroup.identifier` | `identifier` | RequestGroup.identifier | Business identifier | 0..* | Identifier |  |  |
| `RequestGroup.implicitRules` | `RequestGroup.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `RequestGroup.instantiatesCanonical` | `RequestGroup.instantiatesCanonical` | `instantiatesCanonical` | RequestGroup.instantiatesCanonical | Instantiates FHIR protocol or definition | 0..* | canonical |  |  |
| `RequestGroup.instantiatesUri` | `RequestGroup.instantiatesUri` | `instantiatesUri` | RequestGroup.instantiatesUri | Instantiates external protocol or definition | 0..* | uri |  |  |
| `RequestGroup.intent` | `RequestGroup.intent` | `intent` | RequestGroup.intent | proposal \| plan \| directive \| order \| original-order \| reflex-order \| filler-order \| instance-order \| option | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/request-intent|4.0.1` |
| `RequestGroup.language` | `RequestGroup.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `RequestGroup.meta` | `RequestGroup.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `RequestGroup.modifierExtension` | `RequestGroup.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `RequestGroup.note` | `RequestGroup.note` | `note` | RequestGroup.note | Additional notes about the response | 0..* | Annotation |  |  |
| `RequestGroup.priority` | `RequestGroup.priority` | `priority` | RequestGroup.priority | routine \| urgent \| asap \| stat | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/request-priority|4.0.1` |
| `RequestGroup.reasonCode` | `RequestGroup.reasonCode` | `reasonCode` | RequestGroup.reasonCode | Why the request group is needed | 0..* | CodeableConcept |  |  |
| `RequestGroup.reasonReference` | `RequestGroup.reasonReference` | `reasonReference` | RequestGroup.reasonReference | Why the request group is needed | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Condition), Reference(http://hl7.org/fhir/StructureDefinition/DiagnosticReport), Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference), Reference(http://hl7.org/fhir/StructureDefinition/Observation) |  |  |
| `RequestGroup.replaces` | `RequestGroup.replaces` | `replaces` | RequestGroup.replaces | Request(s) replaced by this request | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `RequestGroup.status` | `RequestGroup.status` | `status` | RequestGroup.status | draft \| active \| on-hold \| revoked \| completed \| entered-in-error \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/request-status|4.0.1` |
| `RequestGroup.subject` | `RequestGroup.subject` | `subject` | RequestGroup.subject | Who the request group is about | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `RequestGroup.text` | `RequestGroup.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [RequestGroup](/docs/R3/Resources/RequestGroup.md)<br/> `http://hl7.org/fhir/StructureDefinition/RequestGroup\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `509`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `701`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestGroup](/docs/R4/Resources/RequestGroup.md)<br/> `http://hl7.org/fhir/StructureDefinition/RequestGroup\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1595`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1596`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestGroup](/docs/R4B/Resources/RequestGroup.md)<br/> `http://hl7.org/fhir/StructureDefinition/RequestGroup\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1034`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1263`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestOrchestration](/docs/R5/Resources/RequestOrchestration.md)<br/> `http://hl7.org/fhir/StructureDefinition/RequestOrchestration\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition RequestGroup from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | [R3 RequestGroup](/docs/R3/Resources/RequestGroup.md)| Relationship | R4 RequestGroup| Relationship | [R4B RequestGroup](/docs/R4B/Resources/RequestGroup.md)| Relationship | [R5 RequestOrchestration](/docs/R5/Resources/RequestOrchestration.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `RequestGroup`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17933)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17934)| **`RequestGroup`**| _Equivalent_<br/>(32329/32330)| `RequestGroup`| | | 
| | | `RequestGroup.id`| _Equivalent_<br/>(17935/17936)| **`RequestGroup.id`**| _Equivalent_<br/>(32331/32332)| `RequestGroup.id`| | | 
| | | `RequestGroup.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17937)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17938)| **`RequestGroup.meta`**| _Equivalent_<br/>(32333/32334)| `RequestGroup.meta`| | | 
| | | `RequestGroup.implicitRules`| _Equivalent_<br/>(17939/17940)| **`RequestGroup.implicitRules`**| _Equivalent_<br/>(32335/32336)| `RequestGroup.implicitRules`| | | 
| | | `RequestGroup.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17941)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(17942)| **`RequestGroup.language`**| _Equivalent_<br/>(32337/32338)| `RequestGroup.language`| | | 
| | | `RequestGroup.text`| _Equivalent_<br/>(17943/17944)| **`RequestGroup.text`**| _Equivalent_<br/>(32339/32340)| `RequestGroup.text`| | | 
| | | `RequestGroup.contained`| _Equivalent_<br/>(17945/17946)| **`RequestGroup.contained`**| _Equivalent_<br/>(32341/32342)| `RequestGroup.contained`| | | 
| | | `RequestGroup.extension`| _Equivalent_<br/>(17947/17948)| **`RequestGroup.extension`**| _Equivalent_<br/>(32343/32344)| `RequestGroup.extension`| | | 
| | | `RequestGroup.modifierExtension`| _Equivalent_<br/>(17949/17950)| **`RequestGroup.modifierExtension`**| _Equivalent_<br/>(32345/32346)| `RequestGroup.modifierExtension`| | | 
| | | `RequestGroup.identifier`| _Equivalent_<br/>(17951/17952)| **`RequestGroup.identifier`**| _Equivalent_<br/>(32347/32348)| `RequestGroup.identifier`| | | 
| | | `RequestGroup.definition`| →→→→ _Equivalent_ →→→→ <br/>(32325)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1657)| **`RequestGroup.instantiatesCanonical`**| _Equivalent_<br/>(32349/32350)| `RequestGroup.instantiatesCanonical`| | | 
| | | | | **`RequestGroup.instantiatesUri`**| _Equivalent_<br/>(32351/32352)| `RequestGroup.instantiatesUri`| | | 
| | | `RequestGroup.basedOn`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17953)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17954)| **`RequestGroup.basedOn`**| _Equivalent_<br/>(32353/32354)| `RequestGroup.basedOn`| | | 
| | | `RequestGroup.replaces`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17955)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17956)| **`RequestGroup.replaces`**| _Equivalent_<br/>(32355/32356)| `RequestGroup.replaces`| | | 
| | | `RequestGroup.groupIdentifier`| _Equivalent_<br/>(17957/17958)| **`RequestGroup.groupIdentifier`**| _Equivalent_<br/>(32357/32358)| `RequestGroup.groupIdentifier`| | | 
| | | `RequestGroup.status`| _Equivalent_<br/>(17959/17960)| **`RequestGroup.status`**| _Equivalent_<br/>(32359/32360)| `RequestGroup.status`| | | 
| | | `RequestGroup.intent`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17961)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17962)| **`RequestGroup.intent`**| _Equivalent_<br/>(32361/32362)| `RequestGroup.intent`| | | 
| | | `RequestGroup.priority`| _Equivalent_<br/>(17963/17964)| **`RequestGroup.priority`**| _Equivalent_<br/>(32363/32364)| `RequestGroup.priority`| | | 
| | | | | **`RequestGroup.code`**| _Equivalent_<br/>(32365/32366)| `RequestGroup.code`| | | 
| | | `RequestGroup.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17965)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17966)| **`RequestGroup.subject`**| _Equivalent_<br/>(32367/32368)| `RequestGroup.subject`| | | 
| | | `RequestGroup.context`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1269)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1654)| **`RequestGroup.encounter`**| _Equivalent_<br/>(32369/32370)| `RequestGroup.encounter`| | | 
| | | `RequestGroup.authoredOn`| _Equivalent_<br/>(17967/17968)| **`RequestGroup.authoredOn`**| _Equivalent_<br/>(32371/32372)| `RequestGroup.authoredOn`| | | 
| | | `RequestGroup.author`| →→→→ _RelatedTo_ →→→→ <br/>(17969)<hr/>←←←← _RelatedTo_ ←←←← <br/>(17970)| **`RequestGroup.author`**| _Equivalent_<br/>(32373/32374)| `RequestGroup.author`| | | 
| | | `RequestGroup.reason[x]`| →→→→ _RelatedTo_ →→→→ <br/>(1271)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1655)| **`RequestGroup.reasonCode`**| _Equivalent_<br/>(32375/32376)| `RequestGroup.reasonCode`| | | 
| | | `RequestGroup.reason[x]`| →→→→ _RelatedTo_ →→→→ <br/>(1272)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1656)| **`RequestGroup.reasonReference`**| _Equivalent_<br/>(32377/32378)| `RequestGroup.reasonReference`| | | 
| | | `RequestGroup.note`| _Equivalent_<br/>(17971/17972)| **`RequestGroup.note`**| _Equivalent_<br/>(32379/32380)| `RequestGroup.note`| | | 
| | | `RequestGroup.action`| _Equivalent_<br/>(17973/17974)| **`RequestGroup.action`**| _Equivalent_<br/>(32381/32382)| `RequestGroup.action`| | | 
| | | `RequestGroup.action.id`| _Equivalent_<br/>(17975/17976)| **`RequestGroup.action.id`**| _Equivalent_<br/>(32383/32384)| `RequestGroup.action.id`| | | 
| | | `RequestGroup.action.extension`| _Equivalent_<br/>(17977/17978)| **`RequestGroup.action.extension`**| _Equivalent_<br/>(32385/32386)| `RequestGroup.action.extension`| | | 
| | | `RequestGroup.action.modifierExtension`| _Equivalent_<br/>(17979/17980)| **`RequestGroup.action.modifierExtension`**| _Equivalent_<br/>(32387/32388)| `RequestGroup.action.modifierExtension`| | | 
| | | `RequestGroup.action.label`| _Equivalent_<br/>(1268/1653)| **`RequestGroup.action.prefix`**| _Equivalent_<br/>(32389/32390)| `RequestGroup.action.prefix`| | | 
| | | `RequestGroup.action.title`| _Equivalent_<br/>(17981/17982)| **`RequestGroup.action.title`**| _Equivalent_<br/>(32391/32392)| `RequestGroup.action.title`| | | 
| | | `RequestGroup.action.description`| _Equivalent_<br/>(17983/17984)| **`RequestGroup.action.description`**| _Equivalent_<br/>(32393/32394)| `RequestGroup.action.description`| | | 
| | | `RequestGroup.action.textEquivalent`| _Equivalent_<br/>(17985/17986)| **`RequestGroup.action.textEquivalent`**| _Equivalent_<br/>(32395/32396)| `RequestGroup.action.textEquivalent`| | | 
| | | | | **`RequestGroup.action.priority`**| _Equivalent_<br/>(32397/32398)| `RequestGroup.action.priority`| | | 
| | | `RequestGroup.action.code`| _Equivalent_<br/>(17987/17988)| **`RequestGroup.action.code`**| _Equivalent_<br/>(32399/32400)| `RequestGroup.action.code`| | | 
| | | `RequestGroup.action.documentation`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17989)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17990)| **`RequestGroup.action.documentation`**| _Equivalent_<br/>(32401/32402)| `RequestGroup.action.documentation`| | | 
| | | `RequestGroup.action.condition`| _Equivalent_<br/>(17991/17992)| **`RequestGroup.action.condition`**| _Equivalent_<br/>(32403/32404)| `RequestGroup.action.condition`| | | 
| | | `RequestGroup.action.condition.id`| _Equivalent_<br/>(17993/17994)| **`RequestGroup.action.condition.id`**| _Equivalent_<br/>(32405/32406)| `RequestGroup.action.condition.id`| | | 
| | | `RequestGroup.action.condition.extension`| _Equivalent_<br/>(17995/17996)| **`RequestGroup.action.condition.extension`**| _Equivalent_<br/>(32407/32408)| `RequestGroup.action.condition.extension`| | | 
| | | `RequestGroup.action.condition.modifierExtension`| _Equivalent_<br/>(17997/17998)| **`RequestGroup.action.condition.modifierExtension`**| _Equivalent_<br/>(32409/32410)| `RequestGroup.action.condition.modifierExtension`| | | 
| | | `RequestGroup.action.condition.kind`| _Equivalent_<br/>(17999/18000)| **`RequestGroup.action.condition.kind`**| _Equivalent_<br/>(32411/32412)| `RequestGroup.action.condition.kind`| | | 
| | | `RequestGroup.action.condition.description`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1266)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18004)| **`RequestGroup.action.condition.expression`**| _Equivalent_<br/>(32413/32414)| `RequestGroup.action.condition.expression`| | | 
| | | `RequestGroup.action.condition.language`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1267)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18004)| **`RequestGroup.action.condition.expression`**| _Equivalent_<br/>(32413/32414)| `RequestGroup.action.condition.expression`| | | 
| | | `RequestGroup.action.condition.expression`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(18003)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18004)| **`RequestGroup.action.condition.expression`**| _Equivalent_<br/>(32413/32414)| `RequestGroup.action.condition.expression`| | | 
| | | `RequestGroup.action.relatedAction`| _Equivalent_<br/>(18005/18006)| **`RequestGroup.action.relatedAction`**| _Equivalent_<br/>(32415/32416)| `RequestGroup.action.relatedAction`| | | 
| | | `RequestGroup.action.relatedAction.id`| _Equivalent_<br/>(18007/18008)| **`RequestGroup.action.relatedAction.id`**| _Equivalent_<br/>(32417/32418)| `RequestGroup.action.relatedAction.id`| | | 
| | | `RequestGroup.action.relatedAction.extension`| _Equivalent_<br/>(18009/18010)| **`RequestGroup.action.relatedAction.extension`**| _Equivalent_<br/>(32419/32420)| `RequestGroup.action.relatedAction.extension`| | | 
| | | `RequestGroup.action.relatedAction.modifierExtension`| _Equivalent_<br/>(18011/18012)| **`RequestGroup.action.relatedAction.modifierExtension`**| _Equivalent_<br/>(32421/32422)| `RequestGroup.action.relatedAction.modifierExtension`| | | 
| | | `RequestGroup.action.relatedAction.actionId`| _Equivalent_<br/>(18013/18014)| **`RequestGroup.action.relatedAction.actionId`**| _Equivalent_<br/>(32423/32424)| `RequestGroup.action.relatedAction.actionId`| | | 
| | | `RequestGroup.action.relatedAction.relationship`| _Equivalent_<br/>(18015/18016)| **`RequestGroup.action.relatedAction.relationship`**| _Equivalent_<br/>(32425/32426)| `RequestGroup.action.relatedAction.relationship`| | | 
| | | `RequestGroup.action.relatedAction.offset[x]`| _Equivalent_<br/>(18017/18018)| **`RequestGroup.action.relatedAction.offset[x]`**| _Equivalent_<br/>(32427/32428)| `RequestGroup.action.relatedAction.offset[x]`| | | 
| | | `RequestGroup.action.timing[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18019)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18020)| **`RequestGroup.action.timing[x]`**| _Equivalent_<br/>(32429/32430)| `RequestGroup.action.timing[x]`| | | 
| | | `RequestGroup.action.participant`| →→→→ _RelatedTo_ →→→→ <br/>(18021)<hr/>←←←← _RelatedTo_ ←←←← <br/>(18022)| **`RequestGroup.action.participant`**| _Equivalent_<br/>(32431/32432)| `RequestGroup.action.participant`| | | 
| | | `RequestGroup.action.type`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(18023)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18024)| **`RequestGroup.action.type`**| _Equivalent_<br/>(32433/32434)| `RequestGroup.action.type`| | | 
| | | `RequestGroup.action.groupingBehavior`| _Equivalent_<br/>(18025/18026)| **`RequestGroup.action.groupingBehavior`**| _Equivalent_<br/>(32435/32436)| `RequestGroup.action.groupingBehavior`| | | 
| | | `RequestGroup.action.selectionBehavior`| _Equivalent_<br/>(18027/18028)| **`RequestGroup.action.selectionBehavior`**| _Equivalent_<br/>(32437/32438)| `RequestGroup.action.selectionBehavior`| | | 
| | | `RequestGroup.action.requiredBehavior`| _Equivalent_<br/>(18029/18030)| **`RequestGroup.action.requiredBehavior`**| _Equivalent_<br/>(32439/32440)| `RequestGroup.action.requiredBehavior`| | | 
| | | `RequestGroup.action.precheckBehavior`| _Equivalent_<br/>(18031/18032)| **`RequestGroup.action.precheckBehavior`**| _Equivalent_<br/>(32441/32442)| `RequestGroup.action.precheckBehavior`| | | 
| | | `RequestGroup.action.cardinalityBehavior`| _Equivalent_<br/>(18033/18034)| **`RequestGroup.action.cardinalityBehavior`**| _Equivalent_<br/>(32443/32444)| `RequestGroup.action.cardinalityBehavior`| | | 
| | | `RequestGroup.action.resource`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18035)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18036)| **`RequestGroup.action.resource`**| _Equivalent_<br/>(32445/32446)| `RequestGroup.action.resource`| | | 
| | | `RequestGroup.action.action`| _Equivalent_<br/>(18037/18038)| **`RequestGroup.action.action`**| _Equivalent_<br/>(32447/32448)| `RequestGroup.action.action`| | | 
| | | *58 of 58 elements used* | | *60 of 60 elements used* | | *60 of 60 elements used* | | *0 of 95 elements used* <br/>remaining elements:<br/>`RequestOrchestration`, `RequestOrchestration.action`, `RequestOrchestration.action.action`, `RequestOrchestration.action.cardinalityBehavior`, `RequestOrchestration.action.code`, `RequestOrchestration.action.condition`, `RequestOrchestration.action.condition.expression`, `RequestOrchestration.action.condition.extension`, `RequestOrchestration.action.condition.id`, `RequestOrchestration.action.condition.kind`, `RequestOrchestration.action.condition.modifierExtension`, `RequestOrchestration.action.definition[x]`, `RequestOrchestration.action.description`, `RequestOrchestration.action.documentation`, `RequestOrchestration.action.dynamicValue`, `RequestOrchestration.action.dynamicValue.expression`, `RequestOrchestration.action.dynamicValue.extension`, `RequestOrchestration.action.dynamicValue.id`, `RequestOrchestration.action.dynamicValue.modifierExtension`, `RequestOrchestration.action.dynamicValue.path`, `RequestOrchestration.action.extension`, `RequestOrchestration.action.goal`, `RequestOrchestration.action.groupingBehavior`, `RequestOrchestration.action.id`, `RequestOrchestration.action.input`, `RequestOrchestration.action.input.extension`, `RequestOrchestration.action.input.id`, `RequestOrchestration.action.input.modifierExtension`, `RequestOrchestration.action.input.relatedData`, `RequestOrchestration.action.input.requirement`, `RequestOrchestration.action.input.title`, `RequestOrchestration.action.linkId`, `RequestOrchestration.action.location`, `RequestOrchestration.action.modifierExtension`, `RequestOrchestration.action.output`, `RequestOrchestration.action.output.extension`, `RequestOrchestration.action.output.id`, `RequestOrchestration.action.output.modifierExtension`, `RequestOrchestration.action.output.relatedData`, `RequestOrchestration.action.output.requirement`, `RequestOrchestration.action.output.title`, `RequestOrchestration.action.participant`, `RequestOrchestration.action.participant.actor[x]`, `RequestOrchestration.action.participant.extension`, `RequestOrchestration.action.participant.function`, `RequestOrchestration.action.participant.id`, `RequestOrchestration.action.participant.modifierExtension`, `RequestOrchestration.action.participant.role`, `RequestOrchestration.action.participant.type`, `RequestOrchestration.action.participant.typeCanonical`, `RequestOrchestration.action.participant.typeReference`, `RequestOrchestration.action.precheckBehavior`, `RequestOrchestration.action.prefix`, `RequestOrchestration.action.priority`, `RequestOrchestration.action.relatedAction`, `RequestOrchestration.action.relatedAction.endRelationship`, `RequestOrchestration.action.relatedAction.extension`, `RequestOrchestration.action.relatedAction.id`, `RequestOrchestration.action.relatedAction.modifierExtension`, `RequestOrchestration.action.relatedAction.offset[x]`, `RequestOrchestration.action.relatedAction.relationship`, `RequestOrchestration.action.relatedAction.targetId`, `RequestOrchestration.action.requiredBehavior`, `RequestOrchestration.action.resource`, `RequestOrchestration.action.selectionBehavior`, `RequestOrchestration.action.textEquivalent`, `RequestOrchestration.action.timing[x]`, `RequestOrchestration.action.title`, `RequestOrchestration.action.transform`, `RequestOrchestration.action.type`, `RequestOrchestration.author`, `RequestOrchestration.authoredOn`, `RequestOrchestration.basedOn`, `RequestOrchestration.code`, `RequestOrchestration.contained`, `RequestOrchestration.encounter`, `RequestOrchestration.extension`, `RequestOrchestration.goal`, `RequestOrchestration.groupIdentifier`, `RequestOrchestration.id`, `RequestOrchestration.identifier`, `RequestOrchestration.implicitRules`, `RequestOrchestration.instantiatesCanonical`, `RequestOrchestration.instantiatesUri`, `RequestOrchestration.intent`, `RequestOrchestration.language`, `RequestOrchestration.meta`, `RequestOrchestration.modifierExtension`, `RequestOrchestration.note`, `RequestOrchestration.priority`, `RequestOrchestration.reason`, `RequestOrchestration.replaces`, `RequestOrchestration.status`, `RequestOrchestration.subject`, `RequestOrchestration.text`

