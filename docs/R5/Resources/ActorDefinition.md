Comparison of 
Generated at Monday, April 14, 2025 6:17:46 PM

### ActorDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | ActorDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ActorDefinition` |
| Version | 5.0.0 |
| Description | The ActorDefinition resource is used to describe an actor - a human or an application that plays a role in data exchange, and that may have obligations associated with the role the actor plays. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2250` |
| Database Snapshot Count | `31` |
| Database Differential Count | `23` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ActorDefinition` | `ActorDefinition` | `ActorDefinition` | ActorDefinition | An application that exchanges data | 0..* | ActorDefinition |  |  |
| `ActorDefinition.capabilities` | `ActorDefinition.capabilities` | `capabilities` | ActorDefinition.capabilities | CapabilityStatement for the actor (if applicable) | 0..1 | canonical(http://hl7.org/fhir/StructureDefinition/CapabilityStatement) |  |  |
| `ActorDefinition.contact` | `ActorDefinition.contact` | `contact` | ActorDefinition.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `ActorDefinition.contained` | `ActorDefinition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ActorDefinition.copyright` | `ActorDefinition.copyright` | `copyright` | ActorDefinition.copyright | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `ActorDefinition.copyrightLabel` | `ActorDefinition.copyrightLabel` | `copyrightLabel` | ActorDefinition.copyrightLabel | Copyright holder and year(s) | 0..1 | string |  |  |
| `ActorDefinition.date` | `ActorDefinition.date` | `date` | ActorDefinition.date | Date last changed | 0..1 | dateTime |  |  |
| `ActorDefinition.derivedFrom` | `ActorDefinition.derivedFrom` | `derivedFrom` | ActorDefinition.derivedFrom | Definition of this actor in another context / IG | 0..* | canonical(http://hl7.org/fhir/StructureDefinition/ActorDefinition) |  |  |
| `ActorDefinition.description` | `ActorDefinition.description` | `description` | ActorDefinition.description | Natural language description of the actor | 0..1 | markdown |  |  |
| `ActorDefinition.documentation` | `ActorDefinition.documentation` | `documentation` | ActorDefinition.documentation | Functionality associated with the actor | 0..1 | markdown |  |  |
| `ActorDefinition.experimental` | `ActorDefinition.experimental` | `experimental` | ActorDefinition.experimental | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `ActorDefinition.extension` | `ActorDefinition.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ActorDefinition.id` | `ActorDefinition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ActorDefinition.identifier` | `ActorDefinition.identifier` | `identifier` | ActorDefinition.identifier | Additional identifier for the actor definition (business identifier) | 0..* | Identifier |  |  |
| `ActorDefinition.implicitRules` | `ActorDefinition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ActorDefinition.jurisdiction` | `ActorDefinition.jurisdiction` | `jurisdiction` | ActorDefinition.jurisdiction | Intended jurisdiction for actor definition (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `ActorDefinition.language` | `ActorDefinition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `ActorDefinition.meta` | `ActorDefinition.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ActorDefinition.modifierExtension` | `ActorDefinition.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ActorDefinition.name` | `ActorDefinition.name` | `name` | ActorDefinition.name | Name for this actor definition (computer friendly) | 0..1 | string |  |  |
| `ActorDefinition.publisher` | `ActorDefinition.publisher` | `publisher` | ActorDefinition.publisher | Name of the publisher/steward (organization or individual) | 0..1 | string |  |  |
| `ActorDefinition.purpose` | `ActorDefinition.purpose` | `purpose` | ActorDefinition.purpose | Why this actor definition is defined | 0..1 | markdown |  |  |
| `ActorDefinition.reference` | `ActorDefinition.reference` | `reference` | ActorDefinition.reference | Reference to more information about the actor | 0..* | url |  |  |
| `ActorDefinition.status` | `ActorDefinition.status` | `status` | ActorDefinition.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|5.0.0` |
| `ActorDefinition.text` | `ActorDefinition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `ActorDefinition.title` | `ActorDefinition.title` | `title` | ActorDefinition.title | Name for this actor definition (human friendly) | 0..1 | string |  |  |
| `ActorDefinition.type` | `ActorDefinition.type` | `type` | ActorDefinition.type | person \| system | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/examplescenario-actor-type|5.0.0` |
| `ActorDefinition.url` | `ActorDefinition.url` | `url` | ActorDefinition.url | Canonical identifier for this actor definition, represented as a URI (globally unique) | 0..1 | uri |  |  |
| `ActorDefinition.useContext` | `ActorDefinition.useContext` | `useContext` | ActorDefinition.useContext | The context that the content is intended to support | 0..* | UsageContext |  |  |
| `ActorDefinition.version` | `ActorDefinition.version` | `version` | ActorDefinition.version | Business version of the actor definition | 0..1 | string |  |  |
| `ActorDefinition.versionAlgorithm[x]` | `ActorDefinition.versionAlgorithm[x]` | `versionAlgorithm[x]` | ActorDefinition.versionAlgorithm[x] | How to compare versions | 0..1 | Coding, string | `Extensible` | `http://hl7.org/fhir/ValueSet/version-algorithm` |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

