Comparison of 
Generated at Friday, April 4, 2025 2:59:02 PM

### Measure

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Measure |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Measure` |
| Version | 5.0.0 |
| Description | The Measure resource provides the definition of a quality measure. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2335` |
| Database Snapshot Count | `110` |
| Database Differential Count | `84` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Measure` | `Measure` | `Measure` | Measure | A quality measure definition | 0..* | Measure |  |  |
| `Measure.approvalDate` | `Measure.approvalDate` | `approvalDate` | Measure.approvalDate | When the measure was approved by publisher | 0..1 | date |  |  |
| `Measure.author` | `Measure.author` | `author` | Measure.author | Who authored the content | 0..* | ContactDetail |  |  |
| `Measure.basis` | `Measure.basis` | `basis` | Measure.basis | Population basis | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/fhir-types|5.0.0` |
| `Measure.clinicalRecommendationStatement` | `Measure.clinicalRecommendationStatement` | `clinicalRecommendationStatement` | Measure.clinicalRecommendationStatement | Summary of clinical guidelines | 0..1 | markdown |  |  |
| `Measure.compositeScoring` | `Measure.compositeScoring` | `compositeScoring` | Measure.compositeScoring | opportunity \| all-or-nothing \| linear \| weighted | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/composite-measure-scoring` |
| `Measure.contact` | `Measure.contact` | `contact` | Measure.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `Measure.contained` | `Measure.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Measure.copyright` | `Measure.copyright` | `copyright` | Measure.copyright | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `Measure.copyrightLabel` | `Measure.copyrightLabel` | `copyrightLabel` | Measure.copyrightLabel | Copyright holder and year(s) | 0..1 | string |  |  |
| `Measure.date` | `Measure.date` | `date` | Measure.date | Date last changed | 0..1 | dateTime |  |  |
| `Measure.description` | `Measure.description` | `description` | Measure.description | Natural language description of the measure | 0..1 | markdown |  |  |
| `Measure.disclaimer` | `Measure.disclaimer` | `disclaimer` | Measure.disclaimer | Disclaimer for use of the measure or its referenced content | 0..1 | markdown |  |  |
| `Measure.editor` | `Measure.editor` | `editor` | Measure.editor | Who edited the content | 0..* | ContactDetail |  |  |
| `Measure.effectivePeriod` | `Measure.effectivePeriod` | `effectivePeriod` | Measure.effectivePeriod | When the measure is expected to be used | 0..1 | Period |  |  |
| `Measure.endorser` | `Measure.endorser` | `endorser` | Measure.endorser | Who endorsed the content | 0..* | ContactDetail |  |  |
| `Measure.experimental` | `Measure.experimental` | `experimental` | Measure.experimental | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `Measure.extension` | `Measure.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Measure.group` | `Measure.group` | `group` | Measure.group | Population criteria group | 0..* | BackboneElement |  |  |
| `Measure.group.basis` | `Measure.group.basis` | `basis` | Measure.group.basis | Population basis | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/fhir-types|5.0.0` |
| `Measure.group.code` | `Measure.group.code` | `code` | Measure.group.code | Meaning of the group | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/measure-group-example` |
| `Measure.group.description` | `Measure.group.description` | `description` | Measure.group.description | Summary description | 0..1 | markdown |  |  |
| `Measure.group.extension` | `Measure.group.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Measure.group.id` | `Measure.group.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Measure.group.improvementNotation` | `Measure.group.improvementNotation` | `improvementNotation` | Measure.group.improvementNotation | increase \| decrease | 0..1 | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/measure-improvement-notation|5.0.0` |
| `Measure.group.library` | `Measure.group.library` | `library` | Measure.group.library | Logic used by the measure group | 0..* | canonical(http://hl7.org/fhir/StructureDefinition/Library) |  |  |
| `Measure.group.linkId` | `Measure.group.linkId` | `linkId` | Measure.group.linkId | Unique id for group in measure | 0..1 | string |  |  |
| `Measure.group.modifierExtension` | `Measure.group.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Measure.group.population` | `Measure.group.population` | `population` | Measure.group.population | Population criteria | 0..* | BackboneElement |  |  |
| `Measure.group.population.aggregateMethod` | `Measure.group.population.aggregateMethod` | `aggregateMethod` | Measure.group.population.aggregateMethod | Aggregation method for a measure score (e.g. sum, average, median, minimum, maximum, count) | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/measure-aggregate-method` |
| `Measure.group.population.code` | `Measure.group.population.code` | `code` | Measure.group.population.code | initial-population \| numerator \| numerator-exclusion \| denominator \| denominator-exclusion \| denominator-exception \| measure-population \| measure-population-exclusion \| measure-observation | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/measure-population` |
| `Measure.group.population.criteria` | `Measure.group.population.criteria` | `criteria` | Measure.group.population.criteria | The criteria that defines this population | 0..1 | Expression |  |  |
| `Measure.group.population.description` | `Measure.group.population.description` | `description` | Measure.group.population.description | The human readable description of this population criteria | 0..1 | markdown |  |  |
| `Measure.group.population.extension` | `Measure.group.population.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Measure.group.population.groupDefinition` | `Measure.group.population.groupDefinition` | `groupDefinition` | Measure.group.population.groupDefinition | A group resource that defines this population | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Group) |  |  |
| `Measure.group.population.id` | `Measure.group.population.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Measure.group.population.inputPopulationId` | `Measure.group.population.inputPopulationId` | `inputPopulationId` | Measure.group.population.inputPopulationId | Which population | 0..1 | string |  |  |
| `Measure.group.population.linkId` | `Measure.group.population.linkId` | `linkId` | Measure.group.population.linkId | Unique id for population in measure | 0..1 | string |  |  |
| `Measure.group.population.modifierExtension` | `Measure.group.population.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Measure.group.rateAggregation` | `Measure.group.rateAggregation` | `rateAggregation` | Measure.group.rateAggregation | How is rate aggregation performed for this measure | 0..1 | markdown |  |  |
| `Measure.group.scoring` | `Measure.group.scoring` | `scoring` | Measure.group.scoring | proportion \| ratio \| continuous-variable \| cohort | 0..1 | CodeableConcept | `Extensible` | `http://terminology.hl7.org/ValueSet/measure-scoring` |
| `Measure.group.scoringUnit` | `Measure.group.scoringUnit` | `scoringUnit` | Measure.group.scoringUnit | What units? | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/measure-scoring-unit` |
| `Measure.group.stratifier` | `Measure.group.stratifier` | `stratifier` | Measure.group.stratifier | Stratifier criteria for the measure | 0..* | BackboneElement |  |  |
| `Measure.group.stratifier.code` | `Measure.group.stratifier.code` | `code` | Measure.group.stratifier.code | Meaning of the stratifier | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/measure-stratifier-example` |
| `Measure.group.stratifier.component` | `Measure.group.stratifier.component` | `component` | Measure.group.stratifier.component | Stratifier criteria component for the measure | 0..* | BackboneElement |  |  |
| `Measure.group.stratifier.component.code` | `Measure.group.stratifier.component.code` | `code` | Measure.group.stratifier.component.code | Meaning of the stratifier component | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/measure-stratifier-example` |
| `Measure.group.stratifier.component.criteria` | `Measure.group.stratifier.component.criteria` | `criteria` | Measure.group.stratifier.component.criteria | Component of how the measure should be stratified | 0..1 | Expression |  |  |
| `Measure.group.stratifier.component.description` | `Measure.group.stratifier.component.description` | `description` | Measure.group.stratifier.component.description | The human readable description of this stratifier component | 0..1 | markdown |  |  |
| `Measure.group.stratifier.component.extension` | `Measure.group.stratifier.component.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Measure.group.stratifier.component.groupDefinition` | `Measure.group.stratifier.component.groupDefinition` | `groupDefinition` | Measure.group.stratifier.component.groupDefinition | A group resource that defines this population | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Group) |  |  |
| `Measure.group.stratifier.component.id` | `Measure.group.stratifier.component.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Measure.group.stratifier.component.linkId` | `Measure.group.stratifier.component.linkId` | `linkId` | Measure.group.stratifier.component.linkId | Unique id for stratifier component in measure | 0..1 | string |  |  |
| `Measure.group.stratifier.component.modifierExtension` | `Measure.group.stratifier.component.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Measure.group.stratifier.criteria` | `Measure.group.stratifier.criteria` | `criteria` | Measure.group.stratifier.criteria | How the measure should be stratified | 0..1 | Expression |  |  |
| `Measure.group.stratifier.description` | `Measure.group.stratifier.description` | `description` | Measure.group.stratifier.description | The human readable description of this stratifier | 0..1 | markdown |  |  |
| `Measure.group.stratifier.extension` | `Measure.group.stratifier.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Measure.group.stratifier.groupDefinition` | `Measure.group.stratifier.groupDefinition` | `groupDefinition` | Measure.group.stratifier.groupDefinition | A group resource that defines this population | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Group) |  |  |
| `Measure.group.stratifier.id` | `Measure.group.stratifier.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Measure.group.stratifier.linkId` | `Measure.group.stratifier.linkId` | `linkId` | Measure.group.stratifier.linkId | Unique id for stratifier in measure | 0..1 | string |  |  |
| `Measure.group.stratifier.modifierExtension` | `Measure.group.stratifier.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Measure.group.subject[x]` | `Measure.group.subject[x]` | `subject[x]` | Measure.group.subject[x] | E.g. Patient, Practitioner, RelatedPerson, Organization, Location, Device | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Group) | `Extensible` | `http://hl7.org/fhir/ValueSet/participant-resource-types` |
| `Measure.group.type` | `Measure.group.type` | `type` | Measure.group.type | process \| outcome \| structure \| patient-reported-outcome \| composite | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/measure-type` |
| `Measure.guidance` | `Measure.guidance` | `guidance` | Measure.guidance | Additional guidance for implementers (deprecated) | 0..1 | markdown |  |  |
| `Measure.id` | `Measure.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Measure.identifier` | `Measure.identifier` | `identifier` | Measure.identifier | Additional identifier for the measure | 0..* | Identifier |  |  |
| `Measure.implicitRules` | `Measure.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Measure.improvementNotation` | `Measure.improvementNotation` | `improvementNotation` | Measure.improvementNotation | increase \| decrease | 0..1 | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/measure-improvement-notation|5.0.0` |
| `Measure.jurisdiction` | `Measure.jurisdiction` | `jurisdiction` | Measure.jurisdiction | Intended jurisdiction for measure (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `Measure.language` | `Measure.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `Measure.lastReviewDate` | `Measure.lastReviewDate` | `lastReviewDate` | Measure.lastReviewDate | When the measure was last reviewed by the publisher | 0..1 | date |  |  |
| `Measure.library` | `Measure.library` | `library` | Measure.library | Logic used by the measure | 0..* | canonical(http://hl7.org/fhir/StructureDefinition/Library) |  |  |
| `Measure.meta` | `Measure.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Measure.modifierExtension` | `Measure.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Measure.name` | `Measure.name` | `name` | Measure.name | Name for this measure (computer friendly) | 0..1 | string |  |  |
| `Measure.publisher` | `Measure.publisher` | `publisher` | Measure.publisher | Name of the publisher/steward (organization or individual) | 0..1 | string |  |  |
| `Measure.purpose` | `Measure.purpose` | `purpose` | Measure.purpose | Why this measure is defined | 0..1 | markdown |  |  |
| `Measure.rateAggregation` | `Measure.rateAggregation` | `rateAggregation` | Measure.rateAggregation | How is rate aggregation performed for this measure | 0..1 | markdown |  |  |
| `Measure.rationale` | `Measure.rationale` | `rationale` | Measure.rationale | Detailed description of why the measure exists | 0..1 | markdown |  |  |
| `Measure.relatedArtifact` | `Measure.relatedArtifact` | `relatedArtifact` | Measure.relatedArtifact | Additional documentation, citations, etc | 0..* | RelatedArtifact |  |  |
| `Measure.reviewer` | `Measure.reviewer` | `reviewer` | Measure.reviewer | Who reviewed the content | 0..* | ContactDetail |  |  |
| `Measure.riskAdjustment` | `Measure.riskAdjustment` | `riskAdjustment` | Measure.riskAdjustment | How risk adjustment is applied for this measure | 0..1 | markdown |  |  |
| `Measure.scoring` | `Measure.scoring` | `scoring` | Measure.scoring | proportion \| ratio \| continuous-variable \| cohort | 0..1 | CodeableConcept | `Extensible` | `http://terminology.hl7.org/ValueSet/measure-scoring` |
| `Measure.scoringUnit` | `Measure.scoringUnit` | `scoringUnit` | Measure.scoringUnit | What units? | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/measure-scoring-unit` |
| `Measure.status` | `Measure.status` | `status` | Measure.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|5.0.0` |
| `Measure.subject[x]` | `Measure.subject[x]` | `subject[x]` | Measure.subject[x] | E.g. Patient, Practitioner, RelatedPerson, Organization, Location, Device | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Group) | `Extensible` | `http://hl7.org/fhir/ValueSet/participant-resource-types` |
| `Measure.subtitle` | `Measure.subtitle` | `subtitle` | Measure.subtitle | Subordinate title of the measure | 0..1 | string |  |  |
| `Measure.supplementalData` | `Measure.supplementalData` | `supplementalData` | Measure.supplementalData | What other data should be reported with the measure | 0..* | BackboneElement |  |  |
| `Measure.supplementalData.code` | `Measure.supplementalData.code` | `code` | Measure.supplementalData.code | Meaning of the supplemental data | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/measure-supplemental-data-example` |
| `Measure.supplementalData.criteria` | `Measure.supplementalData.criteria` | `criteria` | Measure.supplementalData.criteria | Expression describing additional data to be reported | 1..1 | Expression |  |  |
| `Measure.supplementalData.description` | `Measure.supplementalData.description` | `description` | Measure.supplementalData.description | The human readable description of this supplemental data | 0..1 | markdown |  |  |
| `Measure.supplementalData.extension` | `Measure.supplementalData.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Measure.supplementalData.id` | `Measure.supplementalData.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Measure.supplementalData.linkId` | `Measure.supplementalData.linkId` | `linkId` | Measure.supplementalData.linkId | Unique id for supplementalData in measure | 0..1 | string |  |  |
| `Measure.supplementalData.modifierExtension` | `Measure.supplementalData.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Measure.supplementalData.usage` | `Measure.supplementalData.usage` | `usage` | Measure.supplementalData.usage | supplemental-data \| risk-adjustment-factor | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/measure-data-usage` |
| `Measure.term` | `Measure.term` | `term` | Measure.term | Defined terms used in the measure documentation | 0..* | BackboneElement |  |  |
| `Measure.term.code` | `Measure.term.code` | `code` | Measure.term.code | What term? | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/measure-definition-example` |
| `Measure.term.definition` | `Measure.term.definition` | `definition` | Measure.term.definition | Meaning of the term | 0..1 | markdown |  |  |
| `Measure.term.extension` | `Measure.term.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Measure.term.id` | `Measure.term.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Measure.term.modifierExtension` | `Measure.term.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Measure.text` | `Measure.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Measure.title` | `Measure.title` | `title` | Measure.title | Name for this measure (human friendly) | 0..1 | string |  |  |
| `Measure.topic` | `Measure.topic` | `topic` | Measure.topic | The category of the measure, such as Education, Treatment, Assessment, etc | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/definition-topic` |
| `Measure.type` | `Measure.type` | `type` | Measure.type | process \| outcome \| structure \| patient-reported-outcome \| composite | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/measure-type` |
| `Measure.url` | `Measure.url` | `url` | Measure.url | Canonical identifier for this measure, represented as a URI (globally unique) | 0..1 | uri |  |  |
| `Measure.usage` | `Measure.usage` | `usage` | Measure.usage | Describes the clinical usage of the measure | 0..1 | markdown |  |  |
| `Measure.useContext` | `Measure.useContext` | `useContext` | Measure.useContext | The context that the content is intended to support | 0..* | UsageContext |  |  |
| `Measure.version` | `Measure.version` | `version` | Measure.version | Business version of the measure | 0..1 | string |  |  |
| `Measure.versionAlgorithm[x]` | `Measure.versionAlgorithm[x]` | `versionAlgorithm[x]` | Measure.versionAlgorithm[x] | How to compare versions | 0..1 | Coding, string | `Extensible` | `http://hl7.org/fhir/ValueSet/version-algorithm` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [Measure](/docs/R3/Resources/Measure.md)<br/> `http://hl7.org/fhir/StructureDefinition/Measure\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `476`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `670`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Measure](/docs/R4/Resources/Measure.md)<br/> `http://hl7.org/fhir/StructureDefinition/Measure\|4.0.1` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1529`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1530`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Measure](/docs/R4B/Resources/Measure.md)<br/> `http://hl7.org/fhir/StructureDefinition/Measure\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1000`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1229`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Measure](/docs/R5/Resources/Measure.md)<br/> `http://hl7.org/fhir/StructureDefinition/Measure\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Measure from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | [R3 Measure](/docs/R3/Resources/Measure.md)| Relationship | [R4 Measure](/docs/R4/Resources/Measure.md)| Relationship | [R4B Measure](/docs/R4B/Resources/Measure.md)| Relationship | R5 Measure
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `Measure`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15400)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15401)| `Measure`| _Equivalent_<br/>(29080/29081)| `Measure`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(43955)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(43956)| **`Measure`**
| | | `Measure.id`| _Equivalent_<br/>(15402/15403)| `Measure.id`| _Equivalent_<br/>(29082/29083)| `Measure.id`| _Equivalent_<br/>(43957/43958)| **`Measure.id`**
| | | `Measure.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15404)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15405)| `Measure.meta`| _Equivalent_<br/>(29084/29085)| `Measure.meta`| _Equivalent_<br/>(43959/43960)| **`Measure.meta`**
| | | `Measure.implicitRules`| _Equivalent_<br/>(15406/15407)| `Measure.implicitRules`| _Equivalent_<br/>(29086/29087)| `Measure.implicitRules`| _Equivalent_<br/>(43961/43962)| **`Measure.implicitRules`**
| | | `Measure.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15408)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(15409)| `Measure.language`| _Equivalent_<br/>(29088/29089)| `Measure.language`| _Equivalent_<br/>(43963/43964)| **`Measure.language`**
| | | `Measure.text`| _Equivalent_<br/>(15410/15411)| `Measure.text`| _Equivalent_<br/>(29090/29091)| `Measure.text`| _Equivalent_<br/>(43965/43966)| **`Measure.text`**
| | | `Measure.contained`| _Equivalent_<br/>(15412/15413)| `Measure.contained`| _Equivalent_<br/>(29092/29093)| `Measure.contained`| _Equivalent_<br/>(43967/43968)| **`Measure.contained`**
| | | `Measure.extension`| _Equivalent_<br/>(15414/15415)| `Measure.extension`| _Equivalent_<br/>(29094/29095)| `Measure.extension`| _Equivalent_<br/>(43969/43970)| **`Measure.extension`**
| | | `Measure.modifierExtension`| _Equivalent_<br/>(15416/15417)| `Measure.modifierExtension`| _Equivalent_<br/>(29096/29097)| `Measure.modifierExtension`| _Equivalent_<br/>(43971/43972)| **`Measure.modifierExtension`**
| | | `Measure.url`| _Equivalent_<br/>(15418/15419)| `Measure.url`| _Equivalent_<br/>(29098/29099)| `Measure.url`| _Equivalent_<br/>(43973/43974)| **`Measure.url`**
| | | `Measure.identifier`| _Equivalent_<br/>(15420/15421)| `Measure.identifier`| _Equivalent_<br/>(29100/29101)| `Measure.identifier`| _Equivalent_<br/>(43975/43976)| **`Measure.identifier`**
| | | `Measure.version`| _Equivalent_<br/>(15422/15423)| `Measure.version`| _Equivalent_<br/>(29102/29103)| `Measure.version`| _Equivalent_<br/>(43977/43978)| **`Measure.version`**
| | | | | | | | | **`Measure.versionAlgorithm[x]`**
| | | `Measure.name`| _Equivalent_<br/>(15424/15425)| `Measure.name`| _Equivalent_<br/>(29104/29105)| `Measure.name`| _Equivalent_<br/>(43979/43980)| **`Measure.name`**
| | | `Measure.title`| _Equivalent_<br/>(15426/15427)| `Measure.title`| _Equivalent_<br/>(29106/29107)| `Measure.title`| _Equivalent_<br/>(43981/43982)| **`Measure.title`**
| | | | | `Measure.subtitle`| _Equivalent_<br/>(29108/29109)| `Measure.subtitle`| _Equivalent_<br/>(43983/43984)| **`Measure.subtitle`**
| | | `Measure.status`| _Equivalent_<br/>(15428/15429)| `Measure.status`| _Equivalent_<br/>(29110/29111)| `Measure.status`| _Equivalent_<br/>(43985/43986)| **`Measure.status`**
| | | `Measure.experimental`| _Equivalent_<br/>(15430/15431)| `Measure.experimental`| _Equivalent_<br/>(29112/29113)| `Measure.experimental`| _Equivalent_<br/>(43987/43988)| **`Measure.experimental`**
| | | | | `Measure.subject[x]`| _Equivalent_<br/>(29114/29115)| `Measure.subject[x]`| _Equivalent_<br/>(43989/43990)| **`Measure.subject[x]`**
| | | | | | | | | **`Measure.basis`**
| | | `Measure.date`| _Equivalent_<br/>(15432/15433)| `Measure.date`| _Equivalent_<br/>(29116/29117)| `Measure.date`| _Equivalent_<br/>(43991/43992)| **`Measure.date`**
| | | `Measure.publisher`| _Equivalent_<br/>(15434/15435)| `Measure.publisher`| _Equivalent_<br/>(29118/29119)| `Measure.publisher`| _Equivalent_<br/>(43993/43994)| **`Measure.publisher`**
| | | `Measure.contact`| _Equivalent_<br/>(15454/15455)| `Measure.contact`| _Equivalent_<br/>(29120/29121)| `Measure.contact`| _Equivalent_<br/>(43995/43996)| **`Measure.contact`**
| | | `Measure.description`| _Equivalent_<br/>(15436/15437)| `Measure.description`| _Equivalent_<br/>(29122/29123)| `Measure.description`| _Equivalent_<br/>(43997/43998)| **`Measure.description`**
| | | `Measure.useContext`| _Equivalent_<br/>(15448/15449)| `Measure.useContext`| _Equivalent_<br/>(29124/29125)| `Measure.useContext`| _Equivalent_<br/>(43999/44000)| **`Measure.useContext`**
| | | `Measure.jurisdiction`| _Equivalent_<br/>(15450/15451)| `Measure.jurisdiction`| _Equivalent_<br/>(29126/29127)| `Measure.jurisdiction`| _Equivalent_<br/>(44001/44002)| **`Measure.jurisdiction`**
| | | `Measure.purpose`| _Equivalent_<br/>(15438/15439)| `Measure.purpose`| _Equivalent_<br/>(29128/29129)| `Measure.purpose`| _Equivalent_<br/>(44003/44004)| **`Measure.purpose`**
| | | `Measure.usage`| _Equivalent_<br/>(15440/15441)| `Measure.usage`| _Equivalent_<br/>(29130/29131)| `Measure.usage`| _Equivalent_<br/>(44005/44006)| **`Measure.usage`**
| | | `Measure.copyright`| _Equivalent_<br/>(15456/15457)| `Measure.copyright`| _Equivalent_<br/>(29132/29133)| `Measure.copyright`| _Equivalent_<br/>(44007/44008)| **`Measure.copyright`**
| | | | | | | | | **`Measure.copyrightLabel`**
| | | `Measure.approvalDate`| _Equivalent_<br/>(15442/15443)| `Measure.approvalDate`| _Equivalent_<br/>(29134/29135)| `Measure.approvalDate`| _Equivalent_<br/>(44009/44010)| **`Measure.approvalDate`**
| | | `Measure.lastReviewDate`| _Equivalent_<br/>(15444/15445)| `Measure.lastReviewDate`| _Equivalent_<br/>(29136/29137)| `Measure.lastReviewDate`| _Equivalent_<br/>(44011/44012)| **`Measure.lastReviewDate`**
| | | `Measure.effectivePeriod`| _Equivalent_<br/>(15446/15447)| `Measure.effectivePeriod`| _Equivalent_<br/>(29138/29139)| `Measure.effectivePeriod`| _Equivalent_<br/>(44013/44014)| **`Measure.effectivePeriod`**
| | | `Measure.topic`| _Equivalent_<br/>(15452/15453)| `Measure.topic`| _Equivalent_<br/>(29140/29141)| `Measure.topic`| _Equivalent_<br/>(44015/44016)| **`Measure.topic`**
| | | `Measure.contributor`| →→→→ _Equivalent_ →→→→ <br/>(29064)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1582)| `Measure.author`| _Equivalent_<br/>(29142/29143)| `Measure.author`| _Equivalent_<br/>(44017/44018)| **`Measure.author`**
| | | `Measure.contributor`| →→→→ _Equivalent_ →→→→ <br/>(29065)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1583)| `Measure.editor`| _Equivalent_<br/>(29144/29145)| `Measure.editor`| _Equivalent_<br/>(44019/44020)| **`Measure.editor`**
| | | `Measure.contributor`| →→→→ _Equivalent_ →→→→ <br/>(29066)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1584)| `Measure.reviewer`| _Equivalent_<br/>(29146/29147)| `Measure.reviewer`| _Equivalent_<br/>(44021/44022)| **`Measure.reviewer`**
| | | `Measure.contributor`| →→→→ _Equivalent_ →→→→ <br/>(29067)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1585)| `Measure.endorser`| _Equivalent_<br/>(29148/29149)| `Measure.endorser`| _Equivalent_<br/>(44023/44024)| **`Measure.endorser`**
| | | `Measure.relatedArtifact`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15458)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15459)| `Measure.relatedArtifact`| _Equivalent_<br/>(29150/29151)| `Measure.relatedArtifact`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(44025)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(44026)| **`Measure.relatedArtifact`**
| | | `Measure.library`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(15460)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15461)| `Measure.library`| _Equivalent_<br/>(29152/29153)| `Measure.library`| _Equivalent_<br/>(44027/44028)| **`Measure.library`**
| | | `Measure.disclaimer`| _Equivalent_<br/>(15462/15463)| `Measure.disclaimer`| _Equivalent_<br/>(29154/29155)| `Measure.disclaimer`| _Equivalent_<br/>(44029/44030)| **`Measure.disclaimer`**
| | | `Measure.scoring`| _Equivalent_<br/>(15464/15465)| `Measure.scoring`| _Equivalent_<br/>(29156/29157)| `Measure.scoring`| _Equivalent_<br/>(44031/44032)| **`Measure.scoring`**
| | | | | | | | | **`Measure.scoringUnit`**
| | | `Measure.compositeScoring`| _Equivalent_<br/>(15466/15467)| `Measure.compositeScoring`| _Equivalent_<br/>(29158/29159)| `Measure.compositeScoring`| _Equivalent_<br/>(44033/44034)| **`Measure.compositeScoring`**
| | | `Measure.type`| _Equivalent_<br/>(15468/15469)| `Measure.type`| _Equivalent_<br/>(29160/29161)| `Measure.type`| _Equivalent_<br/>(44035/44036)| **`Measure.type`**
| | | `Measure.riskAdjustment`| _Equivalent_<br/>(15470/15471)| `Measure.riskAdjustment`| _Equivalent_<br/>(29162/29163)| `Measure.riskAdjustment`| _Equivalent_<br/>(44037/44038)| **`Measure.riskAdjustment`**
| | | `Measure.rateAggregation`| _Equivalent_<br/>(15472/15473)| `Measure.rateAggregation`| _Equivalent_<br/>(29164/29165)| `Measure.rateAggregation`| _Equivalent_<br/>(44039/44040)| **`Measure.rateAggregation`**
| | | `Measure.rationale`| _Equivalent_<br/>(15474/15475)| `Measure.rationale`| _Equivalent_<br/>(29166/29167)| `Measure.rationale`| _Equivalent_<br/>(44041/44042)| **`Measure.rationale`**
| | | `Measure.clinicalRecommendationStatement`| _Equivalent_<br/>(15476/15477)| `Measure.clinicalRecommendationStatement`| _Equivalent_<br/>(29168/29169)| `Measure.clinicalRecommendationStatement`| _Equivalent_<br/>(44043/44044)| **`Measure.clinicalRecommendationStatement`**
| | | `Measure.improvementNotation`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15478)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(15479)| `Measure.improvementNotation`| _Equivalent_<br/>(29170/29171)| `Measure.improvementNotation`| _Equivalent_<br/>(44045/44046)| **`Measure.improvementNotation`**
| | | | | | | | | **`Measure.term`**
| | | | | | | | | **`Measure.term.id`**
| | | | | | | | | **`Measure.term.extension`**
| | | | | | | | | **`Measure.term.modifierExtension`**
| | | | | | | | | **`Measure.term.code`**
| | | | | | | | | **`Measure.term.definition`**
| | | `Measure.guidance`| _Equivalent_<br/>(15482/15483)| `Measure.guidance`| _Equivalent_<br/>(29174/29175)| `Measure.guidance`| _Equivalent_<br/>(44048/44049)| **`Measure.guidance`**
| | | `Measure.group`| _Equivalent_<br/>(15484/15485)| `Measure.group`| _Equivalent_<br/>(29176/29177)| `Measure.group`| _Equivalent_<br/>(44050/44051)| **`Measure.group`**
| | | `Measure.group.id`| _Equivalent_<br/>(15486/15487)| `Measure.group.id`| _Equivalent_<br/>(29178/29179)| `Measure.group.id`| _Equivalent_<br/>(44052/44053)| **`Measure.group.id`**
| | | `Measure.group.extension`| _Equivalent_<br/>(15488/15489)| `Measure.group.extension`| _Equivalent_<br/>(29180/29181)| `Measure.group.extension`| _Equivalent_<br/>(44054/44055)| **`Measure.group.extension`**
| | | `Measure.group.modifierExtension`| _Equivalent_<br/>(15490/15491)| `Measure.group.modifierExtension`| _Equivalent_<br/>(29182/29183)| `Measure.group.modifierExtension`| _Equivalent_<br/>(44056/44057)| **`Measure.group.modifierExtension`**
| | | | | | | | | **`Measure.group.linkId`**
| | | `Measure.group.identifier`| →→→→ _Equivalent_ →→→→ <br/>(29068)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1586)| `Measure.group.code`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(29184)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(29185)| `Measure.group.code`| _Equivalent_<br/>(44058/44059)| **`Measure.group.code`**
| | | `Measure.group.description`| _Equivalent_<br/>(15492/15493)| `Measure.group.description`| _Equivalent_<br/>(29186/29187)| `Measure.group.description`| _Equivalent_<br/>(44060/44061)| **`Measure.group.description`**
| | | | | | | | | **`Measure.group.type`**
| | | | | | | | | **`Measure.group.subject[x]`**
| | | | | | | | | **`Measure.group.basis`**
| | | | | | | | | **`Measure.group.scoring`**
| | | | | | | | | **`Measure.group.scoringUnit`**
| | | | | | | | | **`Measure.group.rateAggregation`**
| | | | | | | | | **`Measure.group.improvementNotation`**
| | | | | | | | | **`Measure.group.library`**
| | | `Measure.group.population`| _Equivalent_<br/>(15494/15495)| `Measure.group.population`| _Equivalent_<br/>(29188/29189)| `Measure.group.population`| _Equivalent_<br/>(44062/44063)| **`Measure.group.population`**
| | | `Measure.group.population.id`| _Equivalent_<br/>(15496/15497)| `Measure.group.population.id`| _Equivalent_<br/>(29190/29191)| `Measure.group.population.id`| _Equivalent_<br/>(44064/44065)| **`Measure.group.population.id`**
| | | `Measure.group.population.extension`| _Equivalent_<br/>(15498/15499)| `Measure.group.population.extension`| _Equivalent_<br/>(29192/29193)| `Measure.group.population.extension`| _Equivalent_<br/>(44066/44067)| **`Measure.group.population.extension`**
| | | `Measure.group.population.modifierExtension`| _Equivalent_<br/>(15500/15501)| `Measure.group.population.modifierExtension`| _Equivalent_<br/>(29194/29195)| `Measure.group.population.modifierExtension`| _Equivalent_<br/>(44068/44069)| **`Measure.group.population.modifierExtension`**
| | | | | | | | | **`Measure.group.population.linkId`**
| | | `Measure.group.population.code`| _Equivalent_<br/>(15502/15503)| `Measure.group.population.code`| _Equivalent_<br/>(29196/29197)| `Measure.group.population.code`| _Equivalent_<br/>(44070/44071)| **`Measure.group.population.code`**
| | | `Measure.group.population.description`| _Equivalent_<br/>(15504/15505)| `Measure.group.population.description`| _Equivalent_<br/>(29198/29199)| `Measure.group.population.description`| _Equivalent_<br/>(44072/44073)| **`Measure.group.population.description`**
| | | `Measure.group.population.criteria`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(15506)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15507)| `Measure.group.population.criteria`| _Equivalent_<br/>(29200/29201)| `Measure.group.population.criteria`| →→→→ _Equivalent_ →→→→ <br/>(44074)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(44075)| **`Measure.group.population.criteria`**
| | | | | | | | | **`Measure.group.population.groupDefinition`**
| | | | | | | | | **`Measure.group.population.inputPopulationId`**
| | | | | | | | | **`Measure.group.population.aggregateMethod`**
| | | `Measure.group.stratifier`| _Equivalent_<br/>(15508/15509)| `Measure.group.stratifier`| _Equivalent_<br/>(29202/29203)| `Measure.group.stratifier`| _Equivalent_<br/>(44076/44077)| **`Measure.group.stratifier`**
| | | `Measure.group.stratifier.id`| _Equivalent_<br/>(15510/15511)| `Measure.group.stratifier.id`| _Equivalent_<br/>(29204/29205)| `Measure.group.stratifier.id`| _Equivalent_<br/>(44078/44079)| **`Measure.group.stratifier.id`**
| | | `Measure.group.stratifier.extension`| →→→→ _Equivalent_ →→→→ <br/>(15512)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15518)| `Measure.group.stratifier.extension`| _Equivalent_<br/>(29206/29207)| `Measure.group.stratifier.extension`| _Equivalent_<br/>(44080/44081)| **`Measure.group.stratifier.extension`**
| | | `Measure.group.stratifier.path`| →→→→ _RelatedTo_ →→→→ <br/>(1154)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15518)| `Measure.group.stratifier.extension`| _Equivalent_<br/>(29206/29207)| `Measure.group.stratifier.extension`| _Equivalent_<br/>(44080/44081)| **`Measure.group.stratifier.extension`**
| | | `Measure.group.stratifier.modifierExtension`| _Equivalent_<br/>(15514/15515)| `Measure.group.stratifier.modifierExtension`| _Equivalent_<br/>(29208/29209)| `Measure.group.stratifier.modifierExtension`| _Equivalent_<br/>(44082/44083)| **`Measure.group.stratifier.modifierExtension`**
| | | | | | | | | **`Measure.group.stratifier.linkId`**
| | | `Measure.group.stratifier.identifier`| →→→→ _Equivalent_ →→→→ <br/>(29069)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1587)| `Measure.group.stratifier.code`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(29210)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(29211)| `Measure.group.stratifier.code`| _Equivalent_<br/>(44084/44085)| **`Measure.group.stratifier.code`**
| | | | | `Measure.group.stratifier.description`| _Equivalent_<br/>(29212/29213)| `Measure.group.stratifier.description`| _Equivalent_<br/>(44086/44087)| **`Measure.group.stratifier.description`**
| | | `Measure.group.stratifier.criteria`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(15516)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15517)| `Measure.group.stratifier.criteria`| _Equivalent_<br/>(29214/29215)| `Measure.group.stratifier.criteria`| _Equivalent_<br/>(44088/44089)| **`Measure.group.stratifier.criteria`**
| | | | | | | | | **`Measure.group.stratifier.groupDefinition`**
| | | | | `Measure.group.stratifier.component`| _Equivalent_<br/>(29216/29217)| `Measure.group.stratifier.component`| _Equivalent_<br/>(44090/44091)| **`Measure.group.stratifier.component`**
| | | | | `Measure.group.stratifier.component.id`| _Equivalent_<br/>(29218/29219)| `Measure.group.stratifier.component.id`| _Equivalent_<br/>(44092/44093)| **`Measure.group.stratifier.component.id`**
| | | | | `Measure.group.stratifier.component.extension`| _Equivalent_<br/>(29220/29221)| `Measure.group.stratifier.component.extension`| _Equivalent_<br/>(44094/44095)| **`Measure.group.stratifier.component.extension`**
| | | | | `Measure.group.stratifier.component.modifierExtension`| _Equivalent_<br/>(29222/29223)| `Measure.group.stratifier.component.modifierExtension`| _Equivalent_<br/>(44096/44097)| **`Measure.group.stratifier.component.modifierExtension`**
| | | | | | | | | **`Measure.group.stratifier.component.linkId`**
| | | | | `Measure.group.stratifier.component.code`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(29224)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(29225)| `Measure.group.stratifier.component.code`| _Equivalent_<br/>(44098/44099)| **`Measure.group.stratifier.component.code`**
| | | | | `Measure.group.stratifier.component.description`| _Equivalent_<br/>(29226/29227)| `Measure.group.stratifier.component.description`| _Equivalent_<br/>(44100/44101)| **`Measure.group.stratifier.component.description`**
| | | | | `Measure.group.stratifier.component.criteria`| _Equivalent_<br/>(29228/29229)| `Measure.group.stratifier.component.criteria`| →→→→ _Equivalent_ →→→→ <br/>(44102)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(44103)| **`Measure.group.stratifier.component.criteria`**
| | | | | | | | | **`Measure.group.stratifier.component.groupDefinition`**
| | | `Measure.supplementalData`| _Equivalent_<br/>(15519/15520)| `Measure.supplementalData`| _Equivalent_<br/>(29230/29231)| `Measure.supplementalData`| _Equivalent_<br/>(44104/44105)| **`Measure.supplementalData`**
| | | `Measure.supplementalData.id`| _Equivalent_<br/>(15521/15522)| `Measure.supplementalData.id`| _Equivalent_<br/>(29232/29233)| `Measure.supplementalData.id`| _Equivalent_<br/>(44106/44107)| **`Measure.supplementalData.id`**
| | | `Measure.supplementalData.extension`| →→→→ _Equivalent_ →→→→ <br/>(15523)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15531)| `Measure.supplementalData.extension`| _Equivalent_<br/>(29234/29235)| `Measure.supplementalData.extension`| _Equivalent_<br/>(44108/44109)| **`Measure.supplementalData.extension`**
| | | `Measure.supplementalData.path`| →→→→ _RelatedTo_ →→→→ <br/>(1157)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15531)| `Measure.supplementalData.extension`| _Equivalent_<br/>(29234/29235)| `Measure.supplementalData.extension`| _Equivalent_<br/>(44108/44109)| **`Measure.supplementalData.extension`**
| | | `Measure.supplementalData.modifierExtension`| _Equivalent_<br/>(15525/15526)| `Measure.supplementalData.modifierExtension`| _Equivalent_<br/>(29236/29237)| `Measure.supplementalData.modifierExtension`| _Equivalent_<br/>(44110/44111)| **`Measure.supplementalData.modifierExtension`**
| | | | | | | | | **`Measure.supplementalData.linkId`**
| | | `Measure.supplementalData.identifier`| →→→→ _Equivalent_ →→→→ <br/>(29078)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1588)| `Measure.supplementalData.code`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(29238)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(29239)| `Measure.supplementalData.code`| _Equivalent_<br/>(44112/44113)| **`Measure.supplementalData.code`**
| | | `Measure.supplementalData.usage`| _Equivalent_<br/>(15527/15528)| `Measure.supplementalData.usage`| _Equivalent_<br/>(29240/29241)| `Measure.supplementalData.usage`| _Equivalent_<br/>(44114/44115)| **`Measure.supplementalData.usage`**
| | | | | `Measure.supplementalData.description`| _Equivalent_<br/>(29242/29243)| `Measure.supplementalData.description`| _Equivalent_<br/>(44116/44117)| **`Measure.supplementalData.description`**
| | | `Measure.supplementalData.criteria`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15529)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15530)| `Measure.supplementalData.criteria`| _Equivalent_<br/>(29244/29245)| `Measure.supplementalData.criteria`| _Equivalent_<br/>(44118/44119)| **`Measure.supplementalData.criteria`**
| | | *70 of 75 elements used* <br/>remaining elements:<br/>`Measure.definition`, `Measure.group.name`, `Measure.group.population.identifier`, `Measure.group.population.name`, `Measure.set`| | *82 of 83 elements used* <br/>remaining elements:<br/>`Measure.definition`| | *82 of 83 elements used* <br/>remaining elements:<br/>`Measure.definition`| | *110 of 110 elements used* 

