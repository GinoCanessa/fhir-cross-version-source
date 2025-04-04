Comparison of 
Generated at Friday, April 4, 2025 2:58:45 PM

### ResearchDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | ResearchDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ResearchDefinition` |
| Version | 4.0.1 |
| Description | The ResearchDefinition resource describes the conditional state (population and any exposures being compared within the population) and outcome (if specified) that the knowledge (evidence, assertion, recommendation) is about. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1147` |
| Database Snapshot Count | `43` |
| Database Differential Count | `35` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ResearchDefinition` | `ResearchDefinition` | `ResearchDefinition` | ResearchDefinition | A research context or question | 0..* | ResearchDefinition |  |  |
| `ResearchDefinition.approvalDate` | `ResearchDefinition.approvalDate` | `approvalDate` | ResearchDefinition.approvalDate | When the research definition was approved by publisher | 0..1 | date |  |  |
| `ResearchDefinition.author` | `ResearchDefinition.author` | `author` | ResearchDefinition.author | Who authored the content | 0..* | ContactDetail |  |  |
| `ResearchDefinition.comment` | `ResearchDefinition.comment` | `comment` | ResearchDefinition.comment | Used for footnotes or explanatory notes | 0..* | string |  |  |
| `ResearchDefinition.contact` | `ResearchDefinition.contact` | `contact` | ResearchDefinition.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `ResearchDefinition.contained` | `ResearchDefinition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ResearchDefinition.copyright` | `ResearchDefinition.copyright` | `copyright` | ResearchDefinition.copyright | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `ResearchDefinition.date` | `ResearchDefinition.date` | `date` | ResearchDefinition.date | Date last changed | 0..1 | dateTime |  |  |
| `ResearchDefinition.description` | `ResearchDefinition.description` | `description` | ResearchDefinition.description | Natural language description of the research definition | 0..1 | markdown |  |  |
| `ResearchDefinition.editor` | `ResearchDefinition.editor` | `editor` | ResearchDefinition.editor | Who edited the content | 0..* | ContactDetail |  |  |
| `ResearchDefinition.effectivePeriod` | `ResearchDefinition.effectivePeriod` | `effectivePeriod` | ResearchDefinition.effectivePeriod | When the research definition is expected to be used | 0..1 | Period |  |  |
| `ResearchDefinition.endorser` | `ResearchDefinition.endorser` | `endorser` | ResearchDefinition.endorser | Who endorsed the content | 0..* | ContactDetail |  |  |
| `ResearchDefinition.experimental` | `ResearchDefinition.experimental` | `experimental` | ResearchDefinition.experimental | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `ResearchDefinition.exposure` | `ResearchDefinition.exposure` | `exposure` | ResearchDefinition.exposure | What exposure? | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/ResearchElementDefinition) |  |  |
| `ResearchDefinition.exposureAlternative` | `ResearchDefinition.exposureAlternative` | `exposureAlternative` | ResearchDefinition.exposureAlternative | What alternative exposure state? | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/ResearchElementDefinition) |  |  |
| `ResearchDefinition.extension` | `ResearchDefinition.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ResearchDefinition.id` | `ResearchDefinition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ResearchDefinition.identifier` | `ResearchDefinition.identifier` | `identifier` | ResearchDefinition.identifier | Additional identifier for the research definition | 0..* | Identifier |  |  |
| `ResearchDefinition.implicitRules` | `ResearchDefinition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ResearchDefinition.jurisdiction` | `ResearchDefinition.jurisdiction` | `jurisdiction` | ResearchDefinition.jurisdiction | Intended jurisdiction for research definition (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `ResearchDefinition.language` | `ResearchDefinition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `ResearchDefinition.lastReviewDate` | `ResearchDefinition.lastReviewDate` | `lastReviewDate` | ResearchDefinition.lastReviewDate | When the research definition was last reviewed | 0..1 | date |  |  |
| `ResearchDefinition.library` | `ResearchDefinition.library` | `library` | ResearchDefinition.library | Logic used by the ResearchDefinition | 0..* | canonical(http://hl7.org/fhir/StructureDefinition/Library) |  |  |
| `ResearchDefinition.meta` | `ResearchDefinition.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ResearchDefinition.modifierExtension` | `ResearchDefinition.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ResearchDefinition.name` | `ResearchDefinition.name` | `name` | ResearchDefinition.name | Name for this research definition (computer friendly) | 0..1 | string |  |  |
| `ResearchDefinition.outcome` | `ResearchDefinition.outcome` | `outcome` | ResearchDefinition.outcome | What outcome? | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/ResearchElementDefinition) |  |  |
| `ResearchDefinition.population` | `ResearchDefinition.population` | `population` | ResearchDefinition.population | What population? | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/ResearchElementDefinition) |  |  |
| `ResearchDefinition.publisher` | `ResearchDefinition.publisher` | `publisher` | ResearchDefinition.publisher | Name of the publisher (organization or individual) | 0..1 | string |  |  |
| `ResearchDefinition.purpose` | `ResearchDefinition.purpose` | `purpose` | ResearchDefinition.purpose | Why this research definition is defined | 0..1 | markdown |  |  |
| `ResearchDefinition.relatedArtifact` | `ResearchDefinition.relatedArtifact` | `relatedArtifact` | ResearchDefinition.relatedArtifact | Additional documentation, citations, etc. | 0..* | RelatedArtifact |  |  |
| `ResearchDefinition.reviewer` | `ResearchDefinition.reviewer` | `reviewer` | ResearchDefinition.reviewer | Who reviewed the content | 0..* | ContactDetail |  |  |
| `ResearchDefinition.shortTitle` | `ResearchDefinition.shortTitle` | `shortTitle` | ResearchDefinition.shortTitle | Title for use in informal contexts | 0..1 | string |  |  |
| `ResearchDefinition.status` | `ResearchDefinition.status` | `status` | ResearchDefinition.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|4.0.1` |
| `ResearchDefinition.subject[x]` | `ResearchDefinition.subject[x]` | `subject[x]` | ResearchDefinition.subject[x] | E.g. Patient, Practitioner, RelatedPerson, Organization, Location, Device | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Group) | `Extensible` | `http://hl7.org/fhir/ValueSet/subject-type` |
| `ResearchDefinition.subtitle` | `ResearchDefinition.subtitle` | `subtitle` | ResearchDefinition.subtitle | Subordinate title of the ResearchDefinition | 0..1 | string |  |  |
| `ResearchDefinition.text` | `ResearchDefinition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `ResearchDefinition.title` | `ResearchDefinition.title` | `title` | ResearchDefinition.title | Name for this research definition (human friendly) | 0..1 | string |  |  |
| `ResearchDefinition.topic` | `ResearchDefinition.topic` | `topic` | ResearchDefinition.topic | The category of the ResearchDefinition, such as Education, Treatment, Assessment, etc. | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/definition-topic` |
| `ResearchDefinition.url` | `ResearchDefinition.url` | `url` | ResearchDefinition.url | Canonical identifier for this research definition, represented as a URI (globally unique) | 0..1 | uri |  |  |
| `ResearchDefinition.usage` | `ResearchDefinition.usage` | `usage` | ResearchDefinition.usage | Describes the clinical usage of the ResearchDefinition | 0..1 | string |  |  |
| `ResearchDefinition.useContext` | `ResearchDefinition.useContext` | `useContext` | ResearchDefinition.useContext | The context that the content is intended to support | 0..* | UsageContext |  |  |
| `ResearchDefinition.version` | `ResearchDefinition.version` | `version` | ResearchDefinition.version | Business version of the research definition | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [ResearchDefinition](/docs/R4/Resources/ResearchDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ResearchDefinition\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1597`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1598`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ResearchDefinition](/docs/R4B/Resources/ResearchDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ResearchDefinition\|4.3.0` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | 
### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ResearchDefinition from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | R4 ResearchDefinition| Relationship | [R4B ResearchDefinition](/docs/R4B/Resources/ResearchDefinition.md)| Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | **`ResearchDefinition`**| _Equivalent_<br/>(32449/32450)| `ResearchDefinition`| | | 
| | | | | **`ResearchDefinition.id`**| _Equivalent_<br/>(32451/32452)| `ResearchDefinition.id`| | | 
| | | | | **`ResearchDefinition.meta`**| _Equivalent_<br/>(32453/32454)| `ResearchDefinition.meta`| | | 
| | | | | **`ResearchDefinition.implicitRules`**| _Equivalent_<br/>(32455/32456)| `ResearchDefinition.implicitRules`| | | 
| | | | | **`ResearchDefinition.language`**| _Equivalent_<br/>(32457/32458)| `ResearchDefinition.language`| | | 
| | | | | **`ResearchDefinition.text`**| _Equivalent_<br/>(32459/32460)| `ResearchDefinition.text`| | | 
| | | | | **`ResearchDefinition.contained`**| _Equivalent_<br/>(32461/32462)| `ResearchDefinition.contained`| | | 
| | | | | **`ResearchDefinition.extension`**| _Equivalent_<br/>(32463/32464)| `ResearchDefinition.extension`| | | 
| | | | | **`ResearchDefinition.modifierExtension`**| _Equivalent_<br/>(32465/32466)| `ResearchDefinition.modifierExtension`| | | 
| | | | | **`ResearchDefinition.url`**| _Equivalent_<br/>(32467/32468)| `ResearchDefinition.url`| | | 
| | | | | **`ResearchDefinition.identifier`**| _Equivalent_<br/>(32469/32470)| `ResearchDefinition.identifier`| | | 
| | | | | **`ResearchDefinition.version`**| _Equivalent_<br/>(32471/32472)| `ResearchDefinition.version`| | | 
| | | | | **`ResearchDefinition.name`**| _Equivalent_<br/>(32473/32474)| `ResearchDefinition.name`| | | 
| | | | | **`ResearchDefinition.title`**| _Equivalent_<br/>(32475/32476)| `ResearchDefinition.title`| | | 
| | | | | **`ResearchDefinition.shortTitle`**| _Equivalent_<br/>(32477/32478)| `ResearchDefinition.shortTitle`| | | 
| | | | | **`ResearchDefinition.subtitle`**| _Equivalent_<br/>(32479/32480)| `ResearchDefinition.subtitle`| | | 
| | | | | **`ResearchDefinition.status`**| _Equivalent_<br/>(32481/32482)| `ResearchDefinition.status`| | | 
| | | | | **`ResearchDefinition.experimental`**| _Equivalent_<br/>(32483/32484)| `ResearchDefinition.experimental`| | | 
| | | | | **`ResearchDefinition.subject[x]`**| _Equivalent_<br/>(32485/32486)| `ResearchDefinition.subject[x]`| | | 
| | | | | **`ResearchDefinition.date`**| _Equivalent_<br/>(32487/32488)| `ResearchDefinition.date`| | | 
| | | | | **`ResearchDefinition.publisher`**| _Equivalent_<br/>(32489/32490)| `ResearchDefinition.publisher`| | | 
| | | | | **`ResearchDefinition.contact`**| _Equivalent_<br/>(32491/32492)| `ResearchDefinition.contact`| | | 
| | | | | **`ResearchDefinition.description`**| _Equivalent_<br/>(32493/32494)| `ResearchDefinition.description`| | | 
| | | | | **`ResearchDefinition.comment`**| _Equivalent_<br/>(32495/32496)| `ResearchDefinition.comment`| | | 
| | | | | **`ResearchDefinition.useContext`**| _Equivalent_<br/>(32497/32498)| `ResearchDefinition.useContext`| | | 
| | | | | **`ResearchDefinition.jurisdiction`**| _Equivalent_<br/>(32499/32500)| `ResearchDefinition.jurisdiction`| | | 
| | | | | **`ResearchDefinition.purpose`**| _Equivalent_<br/>(32501/32502)| `ResearchDefinition.purpose`| | | 
| | | | | **`ResearchDefinition.usage`**| _Equivalent_<br/>(32503/32504)| `ResearchDefinition.usage`| | | 
| | | | | **`ResearchDefinition.copyright`**| _Equivalent_<br/>(32505/32506)| `ResearchDefinition.copyright`| | | 
| | | | | **`ResearchDefinition.approvalDate`**| _Equivalent_<br/>(32507/32508)| `ResearchDefinition.approvalDate`| | | 
| | | | | **`ResearchDefinition.lastReviewDate`**| _Equivalent_<br/>(32509/32510)| `ResearchDefinition.lastReviewDate`| | | 
| | | | | **`ResearchDefinition.effectivePeriod`**| _Equivalent_<br/>(32511/32512)| `ResearchDefinition.effectivePeriod`| | | 
| | | | | **`ResearchDefinition.topic`**| _Equivalent_<br/>(32513/32514)| `ResearchDefinition.topic`| | | 
| | | | | **`ResearchDefinition.author`**| _Equivalent_<br/>(32515/32516)| `ResearchDefinition.author`| | | 
| | | | | **`ResearchDefinition.editor`**| _Equivalent_<br/>(32517/32518)| `ResearchDefinition.editor`| | | 
| | | | | **`ResearchDefinition.reviewer`**| _Equivalent_<br/>(32519/32520)| `ResearchDefinition.reviewer`| | | 
| | | | | **`ResearchDefinition.endorser`**| _Equivalent_<br/>(32521/32522)| `ResearchDefinition.endorser`| | | 
| | | | | **`ResearchDefinition.relatedArtifact`**| _Equivalent_<br/>(32523/32524)| `ResearchDefinition.relatedArtifact`| | | 
| | | | | **`ResearchDefinition.library`**| _Equivalent_<br/>(32525/32526)| `ResearchDefinition.library`| | | 
| | | | | **`ResearchDefinition.population`**| _Equivalent_<br/>(32527/32528)| `ResearchDefinition.population`| | | 
| | | | | **`ResearchDefinition.exposure`**| _Equivalent_<br/>(32529/32530)| `ResearchDefinition.exposure`| | | 
| | | | | **`ResearchDefinition.exposureAlternative`**| _Equivalent_<br/>(32531/32532)| `ResearchDefinition.exposureAlternative`| | | 
| | | | | **`ResearchDefinition.outcome`**| _Equivalent_<br/>(32533/32534)| `ResearchDefinition.outcome`| | | 
| | | | | *43 of 43 elements used* | | *43 of 43 elements used* | | 

