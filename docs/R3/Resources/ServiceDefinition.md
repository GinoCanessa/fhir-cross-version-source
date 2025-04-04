Comparison of 
Generated at Friday, April 4, 2025 2:58:40 PM

### ServiceDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | ServiceDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ServiceDefinition` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for ServiceDefinition Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `580` |
| Database Snapshot Count | `34` |
| Database Differential Count | `26` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ServiceDefinition` | `ServiceDefinition` | `ServiceDefinition` | ServiceDefinition | A description of decision support service functionality | 0..* | ServiceDefinition |  |  |
| `ServiceDefinition.approvalDate` | `ServiceDefinition.approvalDate` | `approvalDate` |  | When the service definition was approved by publisher | 0..1 | date |  |  |
| `ServiceDefinition.contact` | `ServiceDefinition.contact` | `contact` |  | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `ServiceDefinition.contained` | `ServiceDefinition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ServiceDefinition.contributor` | `ServiceDefinition.contributor` | `contributor` |  | A content contributor | 0..* | Contributor |  |  |
| `ServiceDefinition.copyright` | `ServiceDefinition.copyright` | `copyright` |  | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `ServiceDefinition.dataRequirement` | `ServiceDefinition.dataRequirement` | `dataRequirement` |  | What data is used by the module | 0..* | DataRequirement |  |  |
| `ServiceDefinition.date` | `ServiceDefinition.date` | `date` |  | Date this was last changed | 0..1 | dateTime |  |  |
| `ServiceDefinition.description` | `ServiceDefinition.description` | `description` |  | Natural language description of the service definition | 0..1 | markdown |  |  |
| `ServiceDefinition.effectivePeriod` | `ServiceDefinition.effectivePeriod` | `effectivePeriod` |  | When the service definition is expected to be used | 0..1 | Period |  |  |
| `ServiceDefinition.experimental` | `ServiceDefinition.experimental` | `experimental` |  | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `ServiceDefinition.extension` | `ServiceDefinition.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ServiceDefinition.id` | `ServiceDefinition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ServiceDefinition.identifier` | `ServiceDefinition.identifier` | `identifier` |  | Additional identifier for the service definition | 0..* | Identifier |  |  |
| `ServiceDefinition.implicitRules` | `ServiceDefinition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ServiceDefinition.jurisdiction` | `ServiceDefinition.jurisdiction` | `jurisdiction` |  | Intended jurisdiction for service definition (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `ServiceDefinition.language` | `ServiceDefinition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `ServiceDefinition.lastReviewDate` | `ServiceDefinition.lastReviewDate` | `lastReviewDate` |  | When the service definition was last reviewed | 0..1 | date |  |  |
| `ServiceDefinition.meta` | `ServiceDefinition.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ServiceDefinition.modifierExtension` | `ServiceDefinition.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ServiceDefinition.name` | `ServiceDefinition.name` | `name` |  | Name for this service definition (computer friendly) | 0..1 | string |  |  |
| `ServiceDefinition.operationDefinition` | `ServiceDefinition.operationDefinition` | `operationDefinition` |  | Operation to invoke | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/OperationDefinition) |  |  |
| `ServiceDefinition.publisher` | `ServiceDefinition.publisher` | `publisher` |  | Name of the publisher (organization or individual) | 0..1 | string |  |  |
| `ServiceDefinition.purpose` | `ServiceDefinition.purpose` | `purpose` |  | Why this service definition is defined | 0..1 | markdown |  |  |
| `ServiceDefinition.relatedArtifact` | `ServiceDefinition.relatedArtifact` | `relatedArtifact` |  | Additional documentation, citations, etc | 0..* | RelatedArtifact |  |  |
| `ServiceDefinition.status` | `ServiceDefinition.status` | `status` |  | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status` |
| `ServiceDefinition.text` | `ServiceDefinition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `ServiceDefinition.title` | `ServiceDefinition.title` | `title` |  | Name for this service definition (human friendly) | 0..1 | string |  |  |
| `ServiceDefinition.topic` | `ServiceDefinition.topic` | `topic` |  | E.g. Education, Treatment, Assessment, etc | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/definition-topic` |
| `ServiceDefinition.trigger` | `ServiceDefinition.trigger` | `trigger` |  | "when" the module should be invoked | 0..* | TriggerDefinition |  |  |
| `ServiceDefinition.url` | `ServiceDefinition.url` | `url` |  | Logical URI to reference this service definition (globally unique) | 0..1 | uri |  |  |
| `ServiceDefinition.usage` | `ServiceDefinition.usage` | `usage` |  | Describes the clinical usage of the module | 0..1 | string |  |  |
| `ServiceDefinition.useContext` | `ServiceDefinition.useContext` | `useContext` |  | Context the content is intended to support | 0..* | UsageContext |  |  |
| `ServiceDefinition.version` | `ServiceDefinition.version` | `version` |  | Business version of the service definition | 0..1 | string |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

