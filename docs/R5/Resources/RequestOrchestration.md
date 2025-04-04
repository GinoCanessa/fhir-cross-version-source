Comparison of 
Generated at Friday, April 4, 2025 2:59:00 PM

### RequestOrchestration

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | RequestOrchestration |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/RequestOrchestration` |
| Version | 5.0.0 |
| Description | A set of related requests that can be used to capture intended activities that have inter-dependencies such as "give this medication after that one". |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2373` |
| Database Snapshot Count | `95` |
| Database Differential Count | `66` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `RequestOrchestration` | `RequestOrchestration` | `RequestOrchestration` | RequestOrchestration | A set of related requests | 0..* | RequestOrchestration |  |  |
| `RequestOrchestration.action` | `RequestOrchestration.action` | `action` | RequestOrchestration.action | Proposed actions, if any | 0..* | BackboneElement |  |  |
| `RequestOrchestration.action.action` | `RequestOrchestration.action.action` | `action` | RequestOrchestration.action.action | Sub action | 0..* | RequestOrchestration.action |  |  |
| `RequestOrchestration.action.cardinalityBehavior` | `RequestOrchestration.action.cardinalityBehavior` | `cardinalityBehavior` | RequestOrchestration.action.cardinalityBehavior | single \| multiple | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/action-cardinality-behavior|5.0.0` |
| `RequestOrchestration.action.code` | `RequestOrchestration.action.code` | `code` | RequestOrchestration.action.code | Code representing the meaning of the action or sub-actions | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/action-code` |
| `RequestOrchestration.action.condition` | `RequestOrchestration.action.condition` | `condition` | RequestOrchestration.action.condition | Whether or not the action is applicable | 0..* | BackboneElement |  |  |
| `RequestOrchestration.action.condition.expression` | `RequestOrchestration.action.condition.expression` | `expression` | RequestOrchestration.action.condition.expression | Boolean-valued expression | 0..1 | Expression |  |  |
| `RequestOrchestration.action.condition.extension` | `RequestOrchestration.action.condition.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RequestOrchestration.action.condition.id` | `RequestOrchestration.action.condition.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `RequestOrchestration.action.condition.kind` | `RequestOrchestration.action.condition.kind` | `kind` | RequestOrchestration.action.condition.kind | applicability \| start \| stop | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/action-condition-kind|5.0.0` |
| `RequestOrchestration.action.condition.modifierExtension` | `RequestOrchestration.action.condition.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `RequestOrchestration.action.definition[x]` | `RequestOrchestration.action.definition[x]` | `definition[x]` | RequestOrchestration.action.definition[x] | Description of the activity to be performed | 0..1 | canonical(http://hl7.org/fhir/StructureDefinition/ActivityDefinition), canonical(http://hl7.org/fhir/StructureDefinition/ObservationDefinition), canonical(http://hl7.org/fhir/StructureDefinition/PlanDefinition), canonical(http://hl7.org/fhir/StructureDefinition/Questionnaire), canonical(http://hl7.org/fhir/StructureDefinition/SpecimenDefinition), uri |  |  |
| `RequestOrchestration.action.description` | `RequestOrchestration.action.description` | `description` | RequestOrchestration.action.description | Short description of the action | 0..1 | markdown |  |  |
| `RequestOrchestration.action.documentation` | `RequestOrchestration.action.documentation` | `documentation` | RequestOrchestration.action.documentation | Supporting documentation for the intended performer of the action | 0..* | RelatedArtifact |  |  |
| `RequestOrchestration.action.dynamicValue` | `RequestOrchestration.action.dynamicValue` | `dynamicValue` | RequestOrchestration.action.dynamicValue | Dynamic aspects of the definition | 0..* | BackboneElement |  |  |
| `RequestOrchestration.action.dynamicValue.expression` | `RequestOrchestration.action.dynamicValue.expression` | `expression` | RequestOrchestration.action.dynamicValue.expression | An expression that provides the dynamic value for the customization | 0..1 | Expression |  |  |
| `RequestOrchestration.action.dynamicValue.extension` | `RequestOrchestration.action.dynamicValue.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RequestOrchestration.action.dynamicValue.id` | `RequestOrchestration.action.dynamicValue.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `RequestOrchestration.action.dynamicValue.modifierExtension` | `RequestOrchestration.action.dynamicValue.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `RequestOrchestration.action.dynamicValue.path` | `RequestOrchestration.action.dynamicValue.path` | `path` | RequestOrchestration.action.dynamicValue.path | The path to the element to be set dynamically | 0..1 | string |  |  |
| `RequestOrchestration.action.extension` | `RequestOrchestration.action.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RequestOrchestration.action.goal` | `RequestOrchestration.action.goal` | `goal` | RequestOrchestration.action.goal | What goals | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Goal) |  |  |
| `RequestOrchestration.action.groupingBehavior` | `RequestOrchestration.action.groupingBehavior` | `groupingBehavior` | RequestOrchestration.action.groupingBehavior | visual-group \| logical-group \| sentence-group | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/action-grouping-behavior|5.0.0` |
| `RequestOrchestration.action.id` | `RequestOrchestration.action.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `RequestOrchestration.action.input` | `RequestOrchestration.action.input` | `input` | RequestOrchestration.action.input | Input data requirements | 0..* | BackboneElement |  |  |
| `RequestOrchestration.action.input.extension` | `RequestOrchestration.action.input.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RequestOrchestration.action.input.id` | `RequestOrchestration.action.input.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `RequestOrchestration.action.input.modifierExtension` | `RequestOrchestration.action.input.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `RequestOrchestration.action.input.relatedData` | `RequestOrchestration.action.input.relatedData` | `relatedData` | RequestOrchestration.action.input.relatedData | What data is provided | 0..1 | id |  |  |
| `RequestOrchestration.action.input.requirement` | `RequestOrchestration.action.input.requirement` | `requirement` | RequestOrchestration.action.input.requirement | What data is provided | 0..1 | DataRequirement |  |  |
| `RequestOrchestration.action.input.title` | `RequestOrchestration.action.input.title` | `title` | RequestOrchestration.action.input.title | User-visible title | 0..1 | string |  |  |
| `RequestOrchestration.action.linkId` | `RequestOrchestration.action.linkId` | `linkId` | RequestOrchestration.action.linkId | Pointer to specific item from the PlanDefinition | 0..1 | string |  |  |
| `RequestOrchestration.action.location` | `RequestOrchestration.action.location` | `location` | RequestOrchestration.action.location | Where it should happen | 0..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `RequestOrchestration.action.modifierExtension` | `RequestOrchestration.action.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `RequestOrchestration.action.output` | `RequestOrchestration.action.output` | `output` | RequestOrchestration.action.output | Output data definition | 0..* | BackboneElement |  |  |
| `RequestOrchestration.action.output.extension` | `RequestOrchestration.action.output.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RequestOrchestration.action.output.id` | `RequestOrchestration.action.output.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `RequestOrchestration.action.output.modifierExtension` | `RequestOrchestration.action.output.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `RequestOrchestration.action.output.relatedData` | `RequestOrchestration.action.output.relatedData` | `relatedData` | RequestOrchestration.action.output.relatedData | What data is provided | 0..1 | string |  |  |
| `RequestOrchestration.action.output.requirement` | `RequestOrchestration.action.output.requirement` | `requirement` | RequestOrchestration.action.output.requirement | What data is provided | 0..1 | DataRequirement |  |  |
| `RequestOrchestration.action.output.title` | `RequestOrchestration.action.output.title` | `title` | RequestOrchestration.action.output.title | User-visible title | 0..1 | string |  |  |
| `RequestOrchestration.action.participant` | `RequestOrchestration.action.participant` | `participant` | RequestOrchestration.action.participant | Who should perform the action | 0..* | BackboneElement |  |  |
| `RequestOrchestration.action.participant.actor[x]` | `RequestOrchestration.action.participant.actor[x]` | `actor[x]` | RequestOrchestration.action.participant.actor[x] | Who/what is participating? | 0..1 | canonical(http://hl7.org/fhir/StructureDefinition/CapabilityStatement), Reference(http://hl7.org/fhir/StructureDefinition/CareTeam), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/DeviceDefinition), Reference(http://hl7.org/fhir/StructureDefinition/Endpoint), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/HealthcareService), Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `RequestOrchestration.action.participant.extension` | `RequestOrchestration.action.participant.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RequestOrchestration.action.participant.function` | `RequestOrchestration.action.participant.function` | `function` | RequestOrchestration.action.participant.function | E.g. Author, Reviewer, Witness, etc | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/action-participant-function` |
| `RequestOrchestration.action.participant.id` | `RequestOrchestration.action.participant.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `RequestOrchestration.action.participant.modifierExtension` | `RequestOrchestration.action.participant.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `RequestOrchestration.action.participant.role` | `RequestOrchestration.action.participant.role` | `role` | RequestOrchestration.action.participant.role | E.g. Nurse, Surgeon, Parent, etc | 0..1 | CodeableConcept | `Example` | `http://terminology.hl7.org/ValueSet/action-participant-role` |
| `RequestOrchestration.action.participant.type` | `RequestOrchestration.action.participant.type` | `type` | RequestOrchestration.action.participant.type | careteam \| device \| group \| healthcareservice \| location \| organization \| patient \| practitioner \| practitionerrole \| relatedperson | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/action-participant-type|5.0.0` |
| `RequestOrchestration.action.participant.typeCanonical` | `RequestOrchestration.action.participant.typeCanonical` | `typeCanonical` | RequestOrchestration.action.participant.typeCanonical | Who or what can participate | 0..1 | canonical(http://hl7.org/fhir/StructureDefinition/CapabilityStatement) |  |  |
| `RequestOrchestration.action.participant.typeReference` | `RequestOrchestration.action.participant.typeReference` | `typeReference` | RequestOrchestration.action.participant.typeReference | Who or what can participate | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/CareTeam), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/DeviceDefinition), Reference(http://hl7.org/fhir/StructureDefinition/Endpoint), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/HealthcareService), Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `RequestOrchestration.action.precheckBehavior` | `RequestOrchestration.action.precheckBehavior` | `precheckBehavior` | RequestOrchestration.action.precheckBehavior | yes \| no | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/action-precheck-behavior|5.0.0` |
| `RequestOrchestration.action.prefix` | `RequestOrchestration.action.prefix` | `prefix` | RequestOrchestration.action.prefix | User-visible prefix for the action (e.g. 1. or A.) | 0..1 | string |  |  |
| `RequestOrchestration.action.priority` | `RequestOrchestration.action.priority` | `priority` | RequestOrchestration.action.priority | routine \| urgent \| asap \| stat | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/request-priority|5.0.0` |
| `RequestOrchestration.action.relatedAction` | `RequestOrchestration.action.relatedAction` | `relatedAction` | RequestOrchestration.action.relatedAction | Relationship to another action | 0..* | BackboneElement |  |  |
| `RequestOrchestration.action.relatedAction.endRelationship` | `RequestOrchestration.action.relatedAction.endRelationship` | `endRelationship` | RequestOrchestration.action.relatedAction.endRelationship | before \| before-start \| before-end \| concurrent \| concurrent-with-start \| concurrent-with-end \| after \| after-start \| after-end | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/action-relationship-type|5.0.0` |
| `RequestOrchestration.action.relatedAction.extension` | `RequestOrchestration.action.relatedAction.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RequestOrchestration.action.relatedAction.id` | `RequestOrchestration.action.relatedAction.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `RequestOrchestration.action.relatedAction.modifierExtension` | `RequestOrchestration.action.relatedAction.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `RequestOrchestration.action.relatedAction.offset[x]` | `RequestOrchestration.action.relatedAction.offset[x]` | `offset[x]` | RequestOrchestration.action.relatedAction.offset[x] | Time offset for the relationship | 0..1 | Duration, Range |  |  |
| `RequestOrchestration.action.relatedAction.relationship` | `RequestOrchestration.action.relatedAction.relationship` | `relationship` | RequestOrchestration.action.relatedAction.relationship | before \| before-start \| before-end \| concurrent \| concurrent-with-start \| concurrent-with-end \| after \| after-start \| after-end | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/action-relationship-type|5.0.0` |
| `RequestOrchestration.action.relatedAction.targetId` | `RequestOrchestration.action.relatedAction.targetId` | `targetId` | RequestOrchestration.action.relatedAction.targetId | What action this is related to | 1..1 | id |  |  |
| `RequestOrchestration.action.requiredBehavior` | `RequestOrchestration.action.requiredBehavior` | `requiredBehavior` | RequestOrchestration.action.requiredBehavior | must \| could \| must-unless-documented | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/action-required-behavior|5.0.0` |
| `RequestOrchestration.action.resource` | `RequestOrchestration.action.resource` | `resource` | RequestOrchestration.action.resource | The target of the action | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `RequestOrchestration.action.selectionBehavior` | `RequestOrchestration.action.selectionBehavior` | `selectionBehavior` | RequestOrchestration.action.selectionBehavior | any \| all \| all-or-none \| exactly-one \| at-most-one \| one-or-more | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/action-selection-behavior|5.0.0` |
| `RequestOrchestration.action.textEquivalent` | `RequestOrchestration.action.textEquivalent` | `textEquivalent` | RequestOrchestration.action.textEquivalent | Static text equivalent of the action, used if the dynamic aspects cannot be interpreted by the receiving system | 0..1 | markdown |  |  |
| `RequestOrchestration.action.timing[x]` | `RequestOrchestration.action.timing[x]` | `timing[x]` | RequestOrchestration.action.timing[x] | When the action should take place | 0..1 | Age, dateTime, Duration, Period, Range, Timing |  |  |
| `RequestOrchestration.action.title` | `RequestOrchestration.action.title` | `title` | RequestOrchestration.action.title | User-visible title | 0..1 | string |  |  |
| `RequestOrchestration.action.transform` | `RequestOrchestration.action.transform` | `transform` | RequestOrchestration.action.transform | Transform to apply the template | 0..1 | canonical(http://hl7.org/fhir/StructureDefinition/StructureMap) |  |  |
| `RequestOrchestration.action.type` | `RequestOrchestration.action.type` | `type` | RequestOrchestration.action.type | create \| update \| remove \| fire-event | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/action-type` |
| `RequestOrchestration.author` | `RequestOrchestration.author` | `author` | RequestOrchestration.author | Device or practitioner that authored the request orchestration | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `RequestOrchestration.authoredOn` | `RequestOrchestration.authoredOn` | `authoredOn` | RequestOrchestration.authoredOn | When the request orchestration was authored | 0..1 | dateTime |  |  |
| `RequestOrchestration.basedOn` | `RequestOrchestration.basedOn` | `basedOn` | RequestOrchestration.basedOn | Fulfills plan, proposal, or order | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `RequestOrchestration.code` | `RequestOrchestration.code` | `code` | RequestOrchestration.code | What's being requested/ordered | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/action-code` |
| `RequestOrchestration.contained` | `RequestOrchestration.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `RequestOrchestration.encounter` | `RequestOrchestration.encounter` | `encounter` | RequestOrchestration.encounter | Created as part of | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `RequestOrchestration.extension` | `RequestOrchestration.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RequestOrchestration.goal` | `RequestOrchestration.goal` | `goal` | RequestOrchestration.goal | What goals | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Goal) |  |  |
| `RequestOrchestration.groupIdentifier` | `RequestOrchestration.groupIdentifier` | `groupIdentifier` | RequestOrchestration.groupIdentifier | Composite request this is part of | 0..1 | Identifier |  |  |
| `RequestOrchestration.id` | `RequestOrchestration.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `RequestOrchestration.identifier` | `RequestOrchestration.identifier` | `identifier` | RequestOrchestration.identifier | Business identifier | 0..* | Identifier |  |  |
| `RequestOrchestration.implicitRules` | `RequestOrchestration.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `RequestOrchestration.instantiatesCanonical` | `RequestOrchestration.instantiatesCanonical` | `instantiatesCanonical` | RequestOrchestration.instantiatesCanonical | Instantiates FHIR protocol or definition | 0..* | canonical |  |  |
| `RequestOrchestration.instantiatesUri` | `RequestOrchestration.instantiatesUri` | `instantiatesUri` | RequestOrchestration.instantiatesUri | Instantiates external protocol or definition | 0..* | uri |  |  |
| `RequestOrchestration.intent` | `RequestOrchestration.intent` | `intent` | RequestOrchestration.intent | proposal \| plan \| directive \| order \| original-order \| reflex-order \| filler-order \| instance-order \| option | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/request-intent|5.0.0` |
| `RequestOrchestration.language` | `RequestOrchestration.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `RequestOrchestration.meta` | `RequestOrchestration.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `RequestOrchestration.modifierExtension` | `RequestOrchestration.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `RequestOrchestration.note` | `RequestOrchestration.note` | `note` | RequestOrchestration.note | Additional notes about the response | 0..* | Annotation |  |  |
| `RequestOrchestration.priority` | `RequestOrchestration.priority` | `priority` | RequestOrchestration.priority | routine \| urgent \| asap \| stat | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/request-priority|5.0.0` |
| `RequestOrchestration.reason` | `RequestOrchestration.reason` | `reason` | RequestOrchestration.reason | Why the request orchestration is needed | 0..* | CodeableReference(http://hl7.org/fhir/StructureDefinition/Condition), CodeableReference(http://hl7.org/fhir/StructureDefinition/DiagnosticReport), CodeableReference(http://hl7.org/fhir/StructureDefinition/DocumentReference), CodeableReference(http://hl7.org/fhir/StructureDefinition/Observation) | `Example` | `http://hl7.org/fhir/ValueSet/action-reason-code` |
| `RequestOrchestration.replaces` | `RequestOrchestration.replaces` | `replaces` | RequestOrchestration.replaces | Request(s) replaced by this request | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `RequestOrchestration.status` | `RequestOrchestration.status` | `status` | RequestOrchestration.status | draft \| active \| on-hold \| revoked \| completed \| entered-in-error \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/request-status|5.0.0` |
| `RequestOrchestration.subject` | `RequestOrchestration.subject` | `subject` | RequestOrchestration.subject | Who the request orchestration is about | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/CareTeam), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/HealthcareService), Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `RequestOrchestration.text` | `RequestOrchestration.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [RequestGroup](/docs/R3/Resources/RequestGroup.md)<br/> `http://hl7.org/fhir/StructureDefinition/RequestGroup\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `509`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `701`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestGroup](/docs/R4/Resources/RequestGroup.md)<br/> `http://hl7.org/fhir/StructureDefinition/RequestGroup\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1595`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1596`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestGroup](/docs/R4B/Resources/RequestGroup.md)<br/> `http://hl7.org/fhir/StructureDefinition/RequestGroup\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1034`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1263`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RequestOrchestration](/docs/R5/Resources/RequestOrchestration.md)<br/> `http://hl7.org/fhir/StructureDefinition/RequestOrchestration\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition RequestOrchestration from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | [R3 RequestGroup](/docs/R3/Resources/RequestGroup.md)| Relationship | [R4 RequestGroup](/docs/R4/Resources/RequestGroup.md)| Relationship | [R4B RequestGroup](/docs/R4B/Resources/RequestGroup.md)| Relationship | R5 RequestOrchestration
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | | | **`RequestOrchestration`**
| | | | | | | | | **`RequestOrchestration.id`**
| | | | | | | | | **`RequestOrchestration.meta`**
| | | | | | | | | **`RequestOrchestration.implicitRules`**
| | | | | | | | | **`RequestOrchestration.language`**
| | | | | | | | | **`RequestOrchestration.text`**
| | | | | | | | | **`RequestOrchestration.contained`**
| | | | | | | | | **`RequestOrchestration.extension`**
| | | | | | | | | **`RequestOrchestration.modifierExtension`**
| | | | | | | | | **`RequestOrchestration.identifier`**
| | | | | | | | | **`RequestOrchestration.instantiatesCanonical`**
| | | | | | | | | **`RequestOrchestration.instantiatesUri`**
| | | | | | | | | **`RequestOrchestration.basedOn`**
| | | | | | | | | **`RequestOrchestration.replaces`**
| | | | | | | | | **`RequestOrchestration.groupIdentifier`**
| | | | | | | | | **`RequestOrchestration.status`**
| | | | | | | | | **`RequestOrchestration.intent`**
| | | | | | | | | **`RequestOrchestration.priority`**
| | | | | | | | | **`RequestOrchestration.code`**
| | | | | | | | | **`RequestOrchestration.subject`**
| | | | | | | | | **`RequestOrchestration.encounter`**
| | | | | | | | | **`RequestOrchestration.authoredOn`**
| | | | | | | | | **`RequestOrchestration.author`**
| | | | | | | | | **`RequestOrchestration.reason`**
| | | | | | | | | **`RequestOrchestration.goal`**
| | | | | | | | | **`RequestOrchestration.note`**
| | | | | | | | | **`RequestOrchestration.action`**
| | | | | | | | | **`RequestOrchestration.action.id`**
| | | | | | | | | **`RequestOrchestration.action.extension`**
| | | | | | | | | **`RequestOrchestration.action.modifierExtension`**
| | | | | | | | | **`RequestOrchestration.action.linkId`**
| | | | | | | | | **`RequestOrchestration.action.prefix`**
| | | | | | | | | **`RequestOrchestration.action.title`**
| | | | | | | | | **`RequestOrchestration.action.description`**
| | | | | | | | | **`RequestOrchestration.action.textEquivalent`**
| | | | | | | | | **`RequestOrchestration.action.priority`**
| | | | | | | | | **`RequestOrchestration.action.code`**
| | | | | | | | | **`RequestOrchestration.action.documentation`**
| | | | | | | | | **`RequestOrchestration.action.goal`**
| | | | | | | | | **`RequestOrchestration.action.condition`**
| | | | | | | | | **`RequestOrchestration.action.condition.id`**
| | | | | | | | | **`RequestOrchestration.action.condition.extension`**
| | | | | | | | | **`RequestOrchestration.action.condition.modifierExtension`**
| | | | | | | | | **`RequestOrchestration.action.condition.kind`**
| | | | | | | | | **`RequestOrchestration.action.condition.expression`**
| | | | | | | | | **`RequestOrchestration.action.input`**
| | | | | | | | | **`RequestOrchestration.action.input.id`**
| | | | | | | | | **`RequestOrchestration.action.input.extension`**
| | | | | | | | | **`RequestOrchestration.action.input.modifierExtension`**
| | | | | | | | | **`RequestOrchestration.action.input.title`**
| | | | | | | | | **`RequestOrchestration.action.input.requirement`**
| | | | | | | | | **`RequestOrchestration.action.input.relatedData`**
| | | | | | | | | **`RequestOrchestration.action.output`**
| | | | | | | | | **`RequestOrchestration.action.output.id`**
| | | | | | | | | **`RequestOrchestration.action.output.extension`**
| | | | | | | | | **`RequestOrchestration.action.output.modifierExtension`**
| | | | | | | | | **`RequestOrchestration.action.output.title`**
| | | | | | | | | **`RequestOrchestration.action.output.requirement`**
| | | | | | | | | **`RequestOrchestration.action.output.relatedData`**
| | | | | | | | | **`RequestOrchestration.action.relatedAction`**
| | | | | | | | | **`RequestOrchestration.action.relatedAction.id`**
| | | | | | | | | **`RequestOrchestration.action.relatedAction.extension`**
| | | | | | | | | **`RequestOrchestration.action.relatedAction.modifierExtension`**
| | | | | | | | | **`RequestOrchestration.action.relatedAction.targetId`**
| | | | | | | | | **`RequestOrchestration.action.relatedAction.relationship`**
| | | | | | | | | **`RequestOrchestration.action.relatedAction.endRelationship`**
| | | | | | | | | **`RequestOrchestration.action.relatedAction.offset[x]`**
| | | | | | | | | **`RequestOrchestration.action.timing[x]`**
| | | | | | | | | **`RequestOrchestration.action.location`**
| | | | | | | | | **`RequestOrchestration.action.participant`**
| | | | | | | | | **`RequestOrchestration.action.participant.id`**
| | | | | | | | | **`RequestOrchestration.action.participant.extension`**
| | | | | | | | | **`RequestOrchestration.action.participant.modifierExtension`**
| | | | | | | | | **`RequestOrchestration.action.participant.type`**
| | | | | | | | | **`RequestOrchestration.action.participant.typeCanonical`**
| | | | | | | | | **`RequestOrchestration.action.participant.typeReference`**
| | | | | | | | | **`RequestOrchestration.action.participant.role`**
| | | | | | | | | **`RequestOrchestration.action.participant.function`**
| | | | | | | | | **`RequestOrchestration.action.participant.actor[x]`**
| | | | | | | | | **`RequestOrchestration.action.type`**
| | | | | | | | | **`RequestOrchestration.action.groupingBehavior`**
| | | | | | | | | **`RequestOrchestration.action.selectionBehavior`**
| | | | | | | | | **`RequestOrchestration.action.requiredBehavior`**
| | | | | | | | | **`RequestOrchestration.action.precheckBehavior`**
| | | | | | | | | **`RequestOrchestration.action.cardinalityBehavior`**
| | | | | | | | | **`RequestOrchestration.action.resource`**
| | | | | | | | | **`RequestOrchestration.action.definition[x]`**
| | | | | | | | | **`RequestOrchestration.action.transform`**
| | | | | | | | | **`RequestOrchestration.action.dynamicValue`**
| | | | | | | | | **`RequestOrchestration.action.dynamicValue.id`**
| | | | | | | | | **`RequestOrchestration.action.dynamicValue.extension`**
| | | | | | | | | **`RequestOrchestration.action.dynamicValue.modifierExtension`**
| | | | | | | | | **`RequestOrchestration.action.dynamicValue.path`**
| | | | | | | | | **`RequestOrchestration.action.dynamicValue.expression`**
| | | | | | | | | **`RequestOrchestration.action.action`**
| | | *0 of 58 elements used* <br/>remaining elements:<br/>`RequestGroup`, `RequestGroup.action`, `RequestGroup.action.action`, `RequestGroup.action.cardinalityBehavior`, `RequestGroup.action.code`, `RequestGroup.action.condition`, `RequestGroup.action.condition.description`, `RequestGroup.action.condition.expression`, `RequestGroup.action.condition.extension`, `RequestGroup.action.condition.id`, `RequestGroup.action.condition.kind`, `RequestGroup.action.condition.language`, `RequestGroup.action.condition.modifierExtension`, `RequestGroup.action.description`, `RequestGroup.action.documentation`, `RequestGroup.action.extension`, `RequestGroup.action.groupingBehavior`, `RequestGroup.action.id`, `RequestGroup.action.label`, `RequestGroup.action.modifierExtension`, `RequestGroup.action.participant`, `RequestGroup.action.precheckBehavior`, `RequestGroup.action.relatedAction`, `RequestGroup.action.relatedAction.actionId`, `RequestGroup.action.relatedAction.extension`, `RequestGroup.action.relatedAction.id`, `RequestGroup.action.relatedAction.modifierExtension`, `RequestGroup.action.relatedAction.offset[x]`, `RequestGroup.action.relatedAction.relationship`, `RequestGroup.action.requiredBehavior`, `RequestGroup.action.resource`, `RequestGroup.action.selectionBehavior`, `RequestGroup.action.textEquivalent`, `RequestGroup.action.timing[x]`, `RequestGroup.action.title`, `RequestGroup.action.type`, `RequestGroup.author`, `RequestGroup.authoredOn`, `RequestGroup.basedOn`, `RequestGroup.contained`, `RequestGroup.context`, `RequestGroup.definition`, `RequestGroup.extension`, `RequestGroup.groupIdentifier`, `RequestGroup.id`, `RequestGroup.identifier`, `RequestGroup.implicitRules`, `RequestGroup.intent`, `RequestGroup.language`, `RequestGroup.meta`, `RequestGroup.modifierExtension`, `RequestGroup.note`, `RequestGroup.priority`, `RequestGroup.reason[x]`, `RequestGroup.replaces`, `RequestGroup.status`, `RequestGroup.subject`, `RequestGroup.text`| | *0 of 60 elements used* <br/>remaining elements:<br/>`RequestGroup`, `RequestGroup.action`, `RequestGroup.action.action`, `RequestGroup.action.cardinalityBehavior`, `RequestGroup.action.code`, `RequestGroup.action.condition`, `RequestGroup.action.condition.expression`, `RequestGroup.action.condition.extension`, `RequestGroup.action.condition.id`, `RequestGroup.action.condition.kind`, `RequestGroup.action.condition.modifierExtension`, `RequestGroup.action.description`, `RequestGroup.action.documentation`, `RequestGroup.action.extension`, `RequestGroup.action.groupingBehavior`, `RequestGroup.action.id`, `RequestGroup.action.modifierExtension`, `RequestGroup.action.participant`, `RequestGroup.action.precheckBehavior`, `RequestGroup.action.prefix`, `RequestGroup.action.priority`, `RequestGroup.action.relatedAction`, `RequestGroup.action.relatedAction.actionId`, `RequestGroup.action.relatedAction.extension`, `RequestGroup.action.relatedAction.id`, `RequestGroup.action.relatedAction.modifierExtension`, `RequestGroup.action.relatedAction.offset[x]`, `RequestGroup.action.relatedAction.relationship`, `RequestGroup.action.requiredBehavior`, `RequestGroup.action.resource`, `RequestGroup.action.selectionBehavior`, `RequestGroup.action.textEquivalent`, `RequestGroup.action.timing[x]`, `RequestGroup.action.title`, `RequestGroup.action.type`, `RequestGroup.author`, `RequestGroup.authoredOn`, `RequestGroup.basedOn`, `RequestGroup.code`, `RequestGroup.contained`, `RequestGroup.encounter`, `RequestGroup.extension`, `RequestGroup.groupIdentifier`, `RequestGroup.id`, `RequestGroup.identifier`, `RequestGroup.implicitRules`, `RequestGroup.instantiatesCanonical`, `RequestGroup.instantiatesUri`, `RequestGroup.intent`, `RequestGroup.language`, `RequestGroup.meta`, `RequestGroup.modifierExtension`, `RequestGroup.note`, `RequestGroup.priority`, `RequestGroup.reasonCode`, `RequestGroup.reasonReference`, `RequestGroup.replaces`, `RequestGroup.status`, `RequestGroup.subject`, `RequestGroup.text`| | *0 of 60 elements used* <br/>remaining elements:<br/>`RequestGroup`, `RequestGroup.action`, `RequestGroup.action.action`, `RequestGroup.action.cardinalityBehavior`, `RequestGroup.action.code`, `RequestGroup.action.condition`, `RequestGroup.action.condition.expression`, `RequestGroup.action.condition.extension`, `RequestGroup.action.condition.id`, `RequestGroup.action.condition.kind`, `RequestGroup.action.condition.modifierExtension`, `RequestGroup.action.description`, `RequestGroup.action.documentation`, `RequestGroup.action.extension`, `RequestGroup.action.groupingBehavior`, `RequestGroup.action.id`, `RequestGroup.action.modifierExtension`, `RequestGroup.action.participant`, `RequestGroup.action.precheckBehavior`, `RequestGroup.action.prefix`, `RequestGroup.action.priority`, `RequestGroup.action.relatedAction`, `RequestGroup.action.relatedAction.actionId`, `RequestGroup.action.relatedAction.extension`, `RequestGroup.action.relatedAction.id`, `RequestGroup.action.relatedAction.modifierExtension`, `RequestGroup.action.relatedAction.offset[x]`, `RequestGroup.action.relatedAction.relationship`, `RequestGroup.action.requiredBehavior`, `RequestGroup.action.resource`, `RequestGroup.action.selectionBehavior`, `RequestGroup.action.textEquivalent`, `RequestGroup.action.timing[x]`, `RequestGroup.action.title`, `RequestGroup.action.type`, `RequestGroup.author`, `RequestGroup.authoredOn`, `RequestGroup.basedOn`, `RequestGroup.code`, `RequestGroup.contained`, `RequestGroup.encounter`, `RequestGroup.extension`, `RequestGroup.groupIdentifier`, `RequestGroup.id`, `RequestGroup.identifier`, `RequestGroup.implicitRules`, `RequestGroup.instantiatesCanonical`, `RequestGroup.instantiatesUri`, `RequestGroup.intent`, `RequestGroup.language`, `RequestGroup.meta`, `RequestGroup.modifierExtension`, `RequestGroup.note`, `RequestGroup.priority`, `RequestGroup.reasonCode`, `RequestGroup.reasonReference`, `RequestGroup.replaces`, `RequestGroup.status`, `RequestGroup.subject`, `RequestGroup.text`| | *95 of 95 elements used* 

