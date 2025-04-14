Comparison of 
Generated at Monday, April 14, 2025 6:17:30 PM

### RiskEvidenceSynthesis

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | RiskEvidenceSynthesis |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/RiskEvidenceSynthesis` |
| Version | 4.0.1 |
| Description | The RiskEvidenceSynthesis resource describes the likelihood of an outcome in a population plus exposure state where the risk estimate is derived from a combination of research studies. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1153` |
| Database Snapshot Count | `75` |
| Database Differential Count | `52` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `RiskEvidenceSynthesis` | `RiskEvidenceSynthesis` | `RiskEvidenceSynthesis` | RiskEvidenceSynthesis | A quantified estimate of risk based on a body of evidence | 0..* | RiskEvidenceSynthesis |  |  |
| `RiskEvidenceSynthesis.approvalDate` | `RiskEvidenceSynthesis.approvalDate` | `approvalDate` | RiskEvidenceSynthesis.approvalDate | When the risk evidence synthesis was approved by publisher | 0..1 | date |  |  |
| `RiskEvidenceSynthesis.author` | `RiskEvidenceSynthesis.author` | `author` | RiskEvidenceSynthesis.author | Who authored the content | 0..* | ContactDetail |  |  |
| `RiskEvidenceSynthesis.certainty` | `RiskEvidenceSynthesis.certainty` | `certainty` | RiskEvidenceSynthesis.certainty | How certain is the risk | 0..* | BackboneElement |  |  |
| `RiskEvidenceSynthesis.certainty.certaintySubcomponent` | `RiskEvidenceSynthesis.certainty.certaintySubcomponent` | `certaintySubcomponent` | RiskEvidenceSynthesis.certainty.certaintySubcomponent | A component that contributes to the overall certainty | 0..* | BackboneElement |  |  |
| `RiskEvidenceSynthesis.certainty.certaintySubcomponent.extension` | `RiskEvidenceSynthesis.certainty.certaintySubcomponent.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RiskEvidenceSynthesis.certainty.certaintySubcomponent.id` | `RiskEvidenceSynthesis.certainty.certaintySubcomponent.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `RiskEvidenceSynthesis.certainty.certaintySubcomponent.modifierExtension` | `RiskEvidenceSynthesis.certainty.certaintySubcomponent.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `RiskEvidenceSynthesis.certainty.certaintySubcomponent.note` | `RiskEvidenceSynthesis.certainty.certaintySubcomponent.note` | `note` | RiskEvidenceSynthesis.certainty.certaintySubcomponent.note | Used for footnotes or explanatory notes | 0..* | Annotation |  |  |
| `RiskEvidenceSynthesis.certainty.certaintySubcomponent.rating` | `RiskEvidenceSynthesis.certainty.certaintySubcomponent.rating` | `rating` | RiskEvidenceSynthesis.certainty.certaintySubcomponent.rating | Subcomponent certainty rating | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/certainty-subcomponent-rating` |
| `RiskEvidenceSynthesis.certainty.certaintySubcomponent.type` | `RiskEvidenceSynthesis.certainty.certaintySubcomponent.type` | `type` | RiskEvidenceSynthesis.certainty.certaintySubcomponent.type | Type of subcomponent of certainty rating | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/certainty-subcomponent-type` |
| `RiskEvidenceSynthesis.certainty.extension` | `RiskEvidenceSynthesis.certainty.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RiskEvidenceSynthesis.certainty.id` | `RiskEvidenceSynthesis.certainty.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `RiskEvidenceSynthesis.certainty.modifierExtension` | `RiskEvidenceSynthesis.certainty.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `RiskEvidenceSynthesis.certainty.note` | `RiskEvidenceSynthesis.certainty.note` | `note` | RiskEvidenceSynthesis.certainty.note | Used for footnotes or explanatory notes | 0..* | Annotation |  |  |
| `RiskEvidenceSynthesis.certainty.rating` | `RiskEvidenceSynthesis.certainty.rating` | `rating` | RiskEvidenceSynthesis.certainty.rating | Certainty rating | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/evidence-quality` |
| `RiskEvidenceSynthesis.contact` | `RiskEvidenceSynthesis.contact` | `contact` | RiskEvidenceSynthesis.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `RiskEvidenceSynthesis.contained` | `RiskEvidenceSynthesis.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `RiskEvidenceSynthesis.copyright` | `RiskEvidenceSynthesis.copyright` | `copyright` | RiskEvidenceSynthesis.copyright | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `RiskEvidenceSynthesis.date` | `RiskEvidenceSynthesis.date` | `date` | RiskEvidenceSynthesis.date | Date last changed | 0..1 | dateTime |  |  |
| `RiskEvidenceSynthesis.description` | `RiskEvidenceSynthesis.description` | `description` | RiskEvidenceSynthesis.description | Natural language description of the risk evidence synthesis | 0..1 | markdown |  |  |
| `RiskEvidenceSynthesis.editor` | `RiskEvidenceSynthesis.editor` | `editor` | RiskEvidenceSynthesis.editor | Who edited the content | 0..* | ContactDetail |  |  |
| `RiskEvidenceSynthesis.effectivePeriod` | `RiskEvidenceSynthesis.effectivePeriod` | `effectivePeriod` | RiskEvidenceSynthesis.effectivePeriod | When the risk evidence synthesis is expected to be used | 0..1 | Period |  |  |
| `RiskEvidenceSynthesis.endorser` | `RiskEvidenceSynthesis.endorser` | `endorser` | RiskEvidenceSynthesis.endorser | Who endorsed the content | 0..* | ContactDetail |  |  |
| `RiskEvidenceSynthesis.exposure` | `RiskEvidenceSynthesis.exposure` | `exposure` | RiskEvidenceSynthesis.exposure | What exposure? | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/EvidenceVariable) |  |  |
| `RiskEvidenceSynthesis.extension` | `RiskEvidenceSynthesis.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RiskEvidenceSynthesis.id` | `RiskEvidenceSynthesis.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `RiskEvidenceSynthesis.identifier` | `RiskEvidenceSynthesis.identifier` | `identifier` | RiskEvidenceSynthesis.identifier | Additional identifier for the risk evidence synthesis | 0..* | Identifier |  |  |
| `RiskEvidenceSynthesis.implicitRules` | `RiskEvidenceSynthesis.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `RiskEvidenceSynthesis.jurisdiction` | `RiskEvidenceSynthesis.jurisdiction` | `jurisdiction` | RiskEvidenceSynthesis.jurisdiction | Intended jurisdiction for risk evidence synthesis (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `RiskEvidenceSynthesis.language` | `RiskEvidenceSynthesis.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `RiskEvidenceSynthesis.lastReviewDate` | `RiskEvidenceSynthesis.lastReviewDate` | `lastReviewDate` | RiskEvidenceSynthesis.lastReviewDate | When the risk evidence synthesis was last reviewed | 0..1 | date |  |  |
| `RiskEvidenceSynthesis.meta` | `RiskEvidenceSynthesis.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `RiskEvidenceSynthesis.modifierExtension` | `RiskEvidenceSynthesis.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `RiskEvidenceSynthesis.name` | `RiskEvidenceSynthesis.name` | `name` | RiskEvidenceSynthesis.name | Name for this risk evidence synthesis (computer friendly) | 0..1 | string |  |  |
| `RiskEvidenceSynthesis.note` | `RiskEvidenceSynthesis.note` | `note` | RiskEvidenceSynthesis.note | Used for footnotes or explanatory notes | 0..* | Annotation |  |  |
| `RiskEvidenceSynthesis.outcome` | `RiskEvidenceSynthesis.outcome` | `outcome` | RiskEvidenceSynthesis.outcome | What outcome? | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/EvidenceVariable) |  |  |
| `RiskEvidenceSynthesis.population` | `RiskEvidenceSynthesis.population` | `population` | RiskEvidenceSynthesis.population | What population? | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/EvidenceVariable) |  |  |
| `RiskEvidenceSynthesis.publisher` | `RiskEvidenceSynthesis.publisher` | `publisher` | RiskEvidenceSynthesis.publisher | Name of the publisher (organization or individual) | 0..1 | string |  |  |
| `RiskEvidenceSynthesis.relatedArtifact` | `RiskEvidenceSynthesis.relatedArtifact` | `relatedArtifact` | RiskEvidenceSynthesis.relatedArtifact | Additional documentation, citations, etc. | 0..* | RelatedArtifact |  |  |
| `RiskEvidenceSynthesis.reviewer` | `RiskEvidenceSynthesis.reviewer` | `reviewer` | RiskEvidenceSynthesis.reviewer | Who reviewed the content | 0..* | ContactDetail |  |  |
| `RiskEvidenceSynthesis.riskEstimate` | `RiskEvidenceSynthesis.riskEstimate` | `riskEstimate` | RiskEvidenceSynthesis.riskEstimate | What was the estimated risk | 0..1 | BackboneElement |  |  |
| `RiskEvidenceSynthesis.riskEstimate.denominatorCount` | `RiskEvidenceSynthesis.riskEstimate.denominatorCount` | `denominatorCount` | RiskEvidenceSynthesis.riskEstimate.denominatorCount | Sample size for group measured | 0..1 | integer |  |  |
| `RiskEvidenceSynthesis.riskEstimate.description` | `RiskEvidenceSynthesis.riskEstimate.description` | `description` | RiskEvidenceSynthesis.riskEstimate.description | Description of risk estimate | 0..1 | string |  |  |
| `RiskEvidenceSynthesis.riskEstimate.extension` | `RiskEvidenceSynthesis.riskEstimate.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RiskEvidenceSynthesis.riskEstimate.id` | `RiskEvidenceSynthesis.riskEstimate.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `RiskEvidenceSynthesis.riskEstimate.modifierExtension` | `RiskEvidenceSynthesis.riskEstimate.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `RiskEvidenceSynthesis.riskEstimate.numeratorCount` | `RiskEvidenceSynthesis.riskEstimate.numeratorCount` | `numeratorCount` | RiskEvidenceSynthesis.riskEstimate.numeratorCount | Number with the outcome | 0..1 | integer |  |  |
| `RiskEvidenceSynthesis.riskEstimate.precisionEstimate` | `RiskEvidenceSynthesis.riskEstimate.precisionEstimate` | `precisionEstimate` | RiskEvidenceSynthesis.riskEstimate.precisionEstimate | How precise the estimate is | 0..* | BackboneElement |  |  |
| `RiskEvidenceSynthesis.riskEstimate.precisionEstimate.extension` | `RiskEvidenceSynthesis.riskEstimate.precisionEstimate.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RiskEvidenceSynthesis.riskEstimate.precisionEstimate.from` | `RiskEvidenceSynthesis.riskEstimate.precisionEstimate.from` | `from` | RiskEvidenceSynthesis.riskEstimate.precisionEstimate.from | Lower bound | 0..1 | decimal |  |  |
| `RiskEvidenceSynthesis.riskEstimate.precisionEstimate.id` | `RiskEvidenceSynthesis.riskEstimate.precisionEstimate.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `RiskEvidenceSynthesis.riskEstimate.precisionEstimate.level` | `RiskEvidenceSynthesis.riskEstimate.precisionEstimate.level` | `level` | RiskEvidenceSynthesis.riskEstimate.precisionEstimate.level | Level of confidence interval | 0..1 | decimal |  |  |
| `RiskEvidenceSynthesis.riskEstimate.precisionEstimate.modifierExtension` | `RiskEvidenceSynthesis.riskEstimate.precisionEstimate.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `RiskEvidenceSynthesis.riskEstimate.precisionEstimate.to` | `RiskEvidenceSynthesis.riskEstimate.precisionEstimate.to` | `to` | RiskEvidenceSynthesis.riskEstimate.precisionEstimate.to | Upper bound | 0..1 | decimal |  |  |
| `RiskEvidenceSynthesis.riskEstimate.precisionEstimate.type` | `RiskEvidenceSynthesis.riskEstimate.precisionEstimate.type` | `type` | RiskEvidenceSynthesis.riskEstimate.precisionEstimate.type | Type of precision estimate | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/precision-estimate-type` |
| `RiskEvidenceSynthesis.riskEstimate.type` | `RiskEvidenceSynthesis.riskEstimate.type` | `type` | RiskEvidenceSynthesis.riskEstimate.type | Type of risk estimate | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/risk-estimate-type` |
| `RiskEvidenceSynthesis.riskEstimate.unitOfMeasure` | `RiskEvidenceSynthesis.riskEstimate.unitOfMeasure` | `unitOfMeasure` | RiskEvidenceSynthesis.riskEstimate.unitOfMeasure | What unit is the outcome described in? | 0..1 | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/ucum-units|4.0.1` |
| `RiskEvidenceSynthesis.riskEstimate.value` | `RiskEvidenceSynthesis.riskEstimate.value` | `value` | RiskEvidenceSynthesis.riskEstimate.value | Point estimate | 0..1 | decimal |  |  |
| `RiskEvidenceSynthesis.sampleSize` | `RiskEvidenceSynthesis.sampleSize` | `sampleSize` | RiskEvidenceSynthesis.sampleSize | What sample size was involved? | 0..1 | BackboneElement |  |  |
| `RiskEvidenceSynthesis.sampleSize.description` | `RiskEvidenceSynthesis.sampleSize.description` | `description` | RiskEvidenceSynthesis.sampleSize.description | Description of sample size | 0..1 | string |  |  |
| `RiskEvidenceSynthesis.sampleSize.extension` | `RiskEvidenceSynthesis.sampleSize.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RiskEvidenceSynthesis.sampleSize.id` | `RiskEvidenceSynthesis.sampleSize.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `RiskEvidenceSynthesis.sampleSize.modifierExtension` | `RiskEvidenceSynthesis.sampleSize.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `RiskEvidenceSynthesis.sampleSize.numberOfParticipants` | `RiskEvidenceSynthesis.sampleSize.numberOfParticipants` | `numberOfParticipants` | RiskEvidenceSynthesis.sampleSize.numberOfParticipants | How many participants? | 0..1 | integer |  |  |
| `RiskEvidenceSynthesis.sampleSize.numberOfStudies` | `RiskEvidenceSynthesis.sampleSize.numberOfStudies` | `numberOfStudies` | RiskEvidenceSynthesis.sampleSize.numberOfStudies | How many studies? | 0..1 | integer |  |  |
| `RiskEvidenceSynthesis.status` | `RiskEvidenceSynthesis.status` | `status` | RiskEvidenceSynthesis.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|4.0.1` |
| `RiskEvidenceSynthesis.studyType` | `RiskEvidenceSynthesis.studyType` | `studyType` | RiskEvidenceSynthesis.studyType | Type of study | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/study-type` |
| `RiskEvidenceSynthesis.synthesisType` | `RiskEvidenceSynthesis.synthesisType` | `synthesisType` | RiskEvidenceSynthesis.synthesisType | Type of synthesis | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/synthesis-type` |
| `RiskEvidenceSynthesis.text` | `RiskEvidenceSynthesis.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `RiskEvidenceSynthesis.title` | `RiskEvidenceSynthesis.title` | `title` | RiskEvidenceSynthesis.title | Name for this risk evidence synthesis (human friendly) | 0..1 | string |  |  |
| `RiskEvidenceSynthesis.topic` | `RiskEvidenceSynthesis.topic` | `topic` | RiskEvidenceSynthesis.topic | The category of the EffectEvidenceSynthesis, such as Education, Treatment, Assessment, etc. | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/definition-topic` |
| `RiskEvidenceSynthesis.url` | `RiskEvidenceSynthesis.url` | `url` | RiskEvidenceSynthesis.url | Canonical identifier for this risk evidence synthesis, represented as a URI (globally unique) | 0..1 | uri |  |  |
| `RiskEvidenceSynthesis.useContext` | `RiskEvidenceSynthesis.useContext` | `useContext` | RiskEvidenceSynthesis.useContext | The context that the content is intended to support | 0..* | UsageContext |  |  |
| `RiskEvidenceSynthesis.version` | `RiskEvidenceSynthesis.version` | `version` | RiskEvidenceSynthesis.version | Business version of the risk evidence synthesis | 0..1 | string |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

