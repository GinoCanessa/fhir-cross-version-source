Comparison of 
Generated at Monday, April 14, 2025 6:17:47 PM

### ConditionDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | ConditionDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ConditionDefinition` |
| Version | 5.0.0 |
| Description | A definition of a condition and information relevant to managing it. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2281` |
| Database Snapshot Count | `64` |
| Database Differential Count | `41` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ConditionDefinition` | `ConditionDefinition` | `ConditionDefinition` | ConditionDefinition | A definition of a condition | 0..* | ConditionDefinition |  |  |
| `ConditionDefinition.bodySite` | `ConditionDefinition.bodySite` | `bodySite` | ConditionDefinition.bodySite | Anatomical location, if relevant | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/body-site` |
| `ConditionDefinition.code` | `ConditionDefinition.code` | `code` | ConditionDefinition.code | Identification of the condition, problem or diagnosis | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/condition-code` |
| `ConditionDefinition.contact` | `ConditionDefinition.contact` | `contact` | ConditionDefinition.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `ConditionDefinition.contained` | `ConditionDefinition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ConditionDefinition.date` | `ConditionDefinition.date` | `date` | ConditionDefinition.date | Date last changed | 0..1 | dateTime |  |  |
| `ConditionDefinition.definition` | `ConditionDefinition.definition` | `definition` | ConditionDefinition.definition | Formal Definition for the condition | 0..* | uri |  |  |
| `ConditionDefinition.description` | `ConditionDefinition.description` | `description` | ConditionDefinition.description | Natural language description of the condition definition | 0..1 | markdown |  |  |
| `ConditionDefinition.experimental` | `ConditionDefinition.experimental` | `experimental` | ConditionDefinition.experimental | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `ConditionDefinition.extension` | `ConditionDefinition.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ConditionDefinition.hasBodySite` | `ConditionDefinition.hasBodySite` | `hasBodySite` | ConditionDefinition.hasBodySite | Whether bodySite is appropriate | 0..1 | boolean |  |  |
| `ConditionDefinition.hasSeverity` | `ConditionDefinition.hasSeverity` | `hasSeverity` | ConditionDefinition.hasSeverity | Whether Severity is appropriate | 0..1 | boolean |  |  |
| `ConditionDefinition.hasStage` | `ConditionDefinition.hasStage` | `hasStage` | ConditionDefinition.hasStage | Whether stage is appropriate | 0..1 | boolean |  |  |
| `ConditionDefinition.id` | `ConditionDefinition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ConditionDefinition.identifier` | `ConditionDefinition.identifier` | `identifier` | ConditionDefinition.identifier | Additional identifier for the condition definition | 0..* | Identifier |  |  |
| `ConditionDefinition.implicitRules` | `ConditionDefinition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ConditionDefinition.jurisdiction` | `ConditionDefinition.jurisdiction` | `jurisdiction` | ConditionDefinition.jurisdiction | Intended jurisdiction for condition definition (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `ConditionDefinition.language` | `ConditionDefinition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `ConditionDefinition.medication` | `ConditionDefinition.medication` | `medication` | ConditionDefinition.medication | Medications particularly relevant for this condition | 0..* | BackboneElement |  |  |
| `ConditionDefinition.medication.category` | `ConditionDefinition.medication.category` | `category` | ConditionDefinition.medication.category | Category that is relevant | 0..1 | CodeableConcept | `Example` | `http://terminology.hl7.org/ValueSet/medicationrequest-category` |
| `ConditionDefinition.medication.code` | `ConditionDefinition.medication.code` | `code` | ConditionDefinition.medication.code | Code for relevant Medication | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/medication-codes` |
| `ConditionDefinition.medication.extension` | `ConditionDefinition.medication.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ConditionDefinition.medication.id` | `ConditionDefinition.medication.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ConditionDefinition.medication.modifierExtension` | `ConditionDefinition.medication.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ConditionDefinition.meta` | `ConditionDefinition.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ConditionDefinition.modifierExtension` | `ConditionDefinition.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ConditionDefinition.name` | `ConditionDefinition.name` | `name` | ConditionDefinition.name | Name for this condition definition (computer friendly) | 0..1 | string |  |  |
| `ConditionDefinition.observation` | `ConditionDefinition.observation` | `observation` | ConditionDefinition.observation | Observations particularly relevant to this condition | 0..* | BackboneElement |  |  |
| `ConditionDefinition.observation.category` | `ConditionDefinition.observation.category` | `category` | ConditionDefinition.observation.category | Category that is relevant | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/observation-category` |
| `ConditionDefinition.observation.code` | `ConditionDefinition.observation.code` | `code` | ConditionDefinition.observation.code | Code for relevant Observation | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/observation-codes` |
| `ConditionDefinition.observation.extension` | `ConditionDefinition.observation.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ConditionDefinition.observation.id` | `ConditionDefinition.observation.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ConditionDefinition.observation.modifierExtension` | `ConditionDefinition.observation.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ConditionDefinition.plan` | `ConditionDefinition.plan` | `plan` | ConditionDefinition.plan | Plan that is appropriate | 0..* | BackboneElement |  |  |
| `ConditionDefinition.plan.extension` | `ConditionDefinition.plan.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ConditionDefinition.plan.id` | `ConditionDefinition.plan.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ConditionDefinition.plan.modifierExtension` | `ConditionDefinition.plan.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ConditionDefinition.plan.reference` | `ConditionDefinition.plan.reference` | `reference` | ConditionDefinition.plan.reference | The actual plan | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/PlanDefinition) |  |  |
| `ConditionDefinition.plan.role` | `ConditionDefinition.plan.role` | `role` | ConditionDefinition.plan.role | Use for the plan | 0..1 | CodeableConcept |  |  |
| `ConditionDefinition.precondition` | `ConditionDefinition.precondition` | `precondition` | ConditionDefinition.precondition | Observation that suggets this condition | 0..* | BackboneElement |  |  |
| `ConditionDefinition.precondition.code` | `ConditionDefinition.precondition.code` | `code` | ConditionDefinition.precondition.code | Code for relevant Observation | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/observation-codes` |
| `ConditionDefinition.precondition.extension` | `ConditionDefinition.precondition.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ConditionDefinition.precondition.id` | `ConditionDefinition.precondition.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ConditionDefinition.precondition.modifierExtension` | `ConditionDefinition.precondition.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ConditionDefinition.precondition.type` | `ConditionDefinition.precondition.type` | `type` | ConditionDefinition.precondition.type | sensitive \| specific | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/condition-precondition-type|5.0.0` |
| `ConditionDefinition.precondition.value[x]` | `ConditionDefinition.precondition.value[x]` | `value[x]` | ConditionDefinition.precondition.value[x] | Value of Observation | 0..1 | CodeableConcept, Quantity |  |  |
| `ConditionDefinition.publisher` | `ConditionDefinition.publisher` | `publisher` | ConditionDefinition.publisher | Name of the publisher/steward (organization or individual) | 0..1 | string |  |  |
| `ConditionDefinition.questionnaire` | `ConditionDefinition.questionnaire` | `questionnaire` | ConditionDefinition.questionnaire | Questionnaire for this condition | 0..* | BackboneElement |  |  |
| `ConditionDefinition.questionnaire.extension` | `ConditionDefinition.questionnaire.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ConditionDefinition.questionnaire.id` | `ConditionDefinition.questionnaire.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ConditionDefinition.questionnaire.modifierExtension` | `ConditionDefinition.questionnaire.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ConditionDefinition.questionnaire.purpose` | `ConditionDefinition.questionnaire.purpose` | `purpose` | ConditionDefinition.questionnaire.purpose | preadmit \| diff-diagnosis \| outcome | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/condition-questionnaire-purpose|5.0.0` |
| `ConditionDefinition.questionnaire.reference` | `ConditionDefinition.questionnaire.reference` | `reference` | ConditionDefinition.questionnaire.reference | Specific Questionnaire | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Questionnaire) |  |  |
| `ConditionDefinition.severity` | `ConditionDefinition.severity` | `severity` | ConditionDefinition.severity | Subjective severity of condition | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/condition-severity` |
| `ConditionDefinition.stage` | `ConditionDefinition.stage` | `stage` | ConditionDefinition.stage | Stage/grade, usually assessed formally | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/condition-stage` |
| `ConditionDefinition.status` | `ConditionDefinition.status` | `status` | ConditionDefinition.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|5.0.0` |
| `ConditionDefinition.subtitle` | `ConditionDefinition.subtitle` | `subtitle` | ConditionDefinition.subtitle | Subordinate title of the event definition | 0..1 | string |  |  |
| `ConditionDefinition.team` | `ConditionDefinition.team` | `team` | ConditionDefinition.team | Appropriate team for this condition | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/CareTeam) |  |  |
| `ConditionDefinition.text` | `ConditionDefinition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `ConditionDefinition.title` | `ConditionDefinition.title` | `title` | ConditionDefinition.title | Name for this condition definition (human friendly) | 0..1 | string |  |  |
| `ConditionDefinition.url` | `ConditionDefinition.url` | `url` | ConditionDefinition.url | Canonical identifier for this condition definition, represented as a URI (globally unique) | 0..1 | uri |  |  |
| `ConditionDefinition.useContext` | `ConditionDefinition.useContext` | `useContext` | ConditionDefinition.useContext | The context that the content is intended to support | 0..* | UsageContext |  |  |
| `ConditionDefinition.version` | `ConditionDefinition.version` | `version` | ConditionDefinition.version | Business version of the condition definition | 0..1 | string |  |  |
| `ConditionDefinition.versionAlgorithm[x]` | `ConditionDefinition.versionAlgorithm[x]` | `versionAlgorithm[x]` | ConditionDefinition.versionAlgorithm[x] | How to compare versions | 0..1 | Coding, string | `Extensible` | `http://hl7.org/fhir/ValueSet/version-algorithm` |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

