Comparison of 
Generated at Friday, April 4, 2025 2:58:48 PM

### EffectEvidenceSynthesis

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | EffectEvidenceSynthesis |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/EffectEvidenceSynthesis` |
| Version | 4.0.1 |
| Description | The EffectEvidenceSynthesis resource describes the difference in an outcome between exposures states in a population where the effect estimate is derived from a combination of research studies. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1074` |
| Database Snapshot Count | `83` |
| Database Differential Count | `57` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `EffectEvidenceSynthesis` | `EffectEvidenceSynthesis` | `EffectEvidenceSynthesis` | EffectEvidenceSynthesis | A quantified estimate of effect based on a body of evidence | 0..* | EffectEvidenceSynthesis |  |  |
| `EffectEvidenceSynthesis.approvalDate` | `EffectEvidenceSynthesis.approvalDate` | `approvalDate` | EffectEvidenceSynthesis.approvalDate | When the effect evidence synthesis was approved by publisher | 0..1 | date |  |  |
| `EffectEvidenceSynthesis.author` | `EffectEvidenceSynthesis.author` | `author` | EffectEvidenceSynthesis.author | Who authored the content | 0..* | ContactDetail |  |  |
| `EffectEvidenceSynthesis.certainty` | `EffectEvidenceSynthesis.certainty` | `certainty` | EffectEvidenceSynthesis.certainty | How certain is the effect | 0..* | BackboneElement |  |  |
| `EffectEvidenceSynthesis.certainty.certaintySubcomponent` | `EffectEvidenceSynthesis.certainty.certaintySubcomponent` | `certaintySubcomponent` | EffectEvidenceSynthesis.certainty.certaintySubcomponent | A component that contributes to the overall certainty | 0..* | BackboneElement |  |  |
| `EffectEvidenceSynthesis.certainty.certaintySubcomponent.extension` | `EffectEvidenceSynthesis.certainty.certaintySubcomponent.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EffectEvidenceSynthesis.certainty.certaintySubcomponent.id` | `EffectEvidenceSynthesis.certainty.certaintySubcomponent.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `EffectEvidenceSynthesis.certainty.certaintySubcomponent.modifierExtension` | `EffectEvidenceSynthesis.certainty.certaintySubcomponent.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `EffectEvidenceSynthesis.certainty.certaintySubcomponent.note` | `EffectEvidenceSynthesis.certainty.certaintySubcomponent.note` | `note` | EffectEvidenceSynthesis.certainty.certaintySubcomponent.note | Used for footnotes or explanatory notes | 0..* | Annotation |  |  |
| `EffectEvidenceSynthesis.certainty.certaintySubcomponent.rating` | `EffectEvidenceSynthesis.certainty.certaintySubcomponent.rating` | `rating` | EffectEvidenceSynthesis.certainty.certaintySubcomponent.rating | Subcomponent certainty rating | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/certainty-subcomponent-rating` |
| `EffectEvidenceSynthesis.certainty.certaintySubcomponent.type` | `EffectEvidenceSynthesis.certainty.certaintySubcomponent.type` | `type` | EffectEvidenceSynthesis.certainty.certaintySubcomponent.type | Type of subcomponent of certainty rating | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/certainty-subcomponent-type` |
| `EffectEvidenceSynthesis.certainty.extension` | `EffectEvidenceSynthesis.certainty.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EffectEvidenceSynthesis.certainty.id` | `EffectEvidenceSynthesis.certainty.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `EffectEvidenceSynthesis.certainty.modifierExtension` | `EffectEvidenceSynthesis.certainty.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `EffectEvidenceSynthesis.certainty.note` | `EffectEvidenceSynthesis.certainty.note` | `note` | EffectEvidenceSynthesis.certainty.note | Used for footnotes or explanatory notes | 0..* | Annotation |  |  |
| `EffectEvidenceSynthesis.certainty.rating` | `EffectEvidenceSynthesis.certainty.rating` | `rating` | EffectEvidenceSynthesis.certainty.rating | Certainty rating | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/evidence-quality` |
| `EffectEvidenceSynthesis.contact` | `EffectEvidenceSynthesis.contact` | `contact` | EffectEvidenceSynthesis.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `EffectEvidenceSynthesis.contained` | `EffectEvidenceSynthesis.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `EffectEvidenceSynthesis.copyright` | `EffectEvidenceSynthesis.copyright` | `copyright` | EffectEvidenceSynthesis.copyright | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `EffectEvidenceSynthesis.date` | `EffectEvidenceSynthesis.date` | `date` | EffectEvidenceSynthesis.date | Date last changed | 0..1 | dateTime |  |  |
| `EffectEvidenceSynthesis.description` | `EffectEvidenceSynthesis.description` | `description` | EffectEvidenceSynthesis.description | Natural language description of the effect evidence synthesis | 0..1 | markdown |  |  |
| `EffectEvidenceSynthesis.editor` | `EffectEvidenceSynthesis.editor` | `editor` | EffectEvidenceSynthesis.editor | Who edited the content | 0..* | ContactDetail |  |  |
| `EffectEvidenceSynthesis.effectEstimate` | `EffectEvidenceSynthesis.effectEstimate` | `effectEstimate` | EffectEvidenceSynthesis.effectEstimate | What was the estimated effect | 0..* | BackboneElement |  |  |
| `EffectEvidenceSynthesis.effectEstimate.description` | `EffectEvidenceSynthesis.effectEstimate.description` | `description` | EffectEvidenceSynthesis.effectEstimate.description | Description of effect estimate | 0..1 | string |  |  |
| `EffectEvidenceSynthesis.effectEstimate.extension` | `EffectEvidenceSynthesis.effectEstimate.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EffectEvidenceSynthesis.effectEstimate.id` | `EffectEvidenceSynthesis.effectEstimate.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `EffectEvidenceSynthesis.effectEstimate.modifierExtension` | `EffectEvidenceSynthesis.effectEstimate.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `EffectEvidenceSynthesis.effectEstimate.precisionEstimate` | `EffectEvidenceSynthesis.effectEstimate.precisionEstimate` | `precisionEstimate` | EffectEvidenceSynthesis.effectEstimate.precisionEstimate | How precise the estimate is | 0..* | BackboneElement |  |  |
| `EffectEvidenceSynthesis.effectEstimate.precisionEstimate.extension` | `EffectEvidenceSynthesis.effectEstimate.precisionEstimate.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EffectEvidenceSynthesis.effectEstimate.precisionEstimate.from` | `EffectEvidenceSynthesis.effectEstimate.precisionEstimate.from` | `from` | EffectEvidenceSynthesis.effectEstimate.precisionEstimate.from | Lower bound | 0..1 | decimal |  |  |
| `EffectEvidenceSynthesis.effectEstimate.precisionEstimate.id` | `EffectEvidenceSynthesis.effectEstimate.precisionEstimate.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `EffectEvidenceSynthesis.effectEstimate.precisionEstimate.level` | `EffectEvidenceSynthesis.effectEstimate.precisionEstimate.level` | `level` | EffectEvidenceSynthesis.effectEstimate.precisionEstimate.level | Level of confidence interval | 0..1 | decimal |  |  |
| `EffectEvidenceSynthesis.effectEstimate.precisionEstimate.modifierExtension` | `EffectEvidenceSynthesis.effectEstimate.precisionEstimate.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `EffectEvidenceSynthesis.effectEstimate.precisionEstimate.to` | `EffectEvidenceSynthesis.effectEstimate.precisionEstimate.to` | `to` | EffectEvidenceSynthesis.effectEstimate.precisionEstimate.to | Upper bound | 0..1 | decimal |  |  |
| `EffectEvidenceSynthesis.effectEstimate.precisionEstimate.type` | `EffectEvidenceSynthesis.effectEstimate.precisionEstimate.type` | `type` | EffectEvidenceSynthesis.effectEstimate.precisionEstimate.type | Type of precision estimate | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/precision-estimate-type` |
| `EffectEvidenceSynthesis.effectEstimate.type` | `EffectEvidenceSynthesis.effectEstimate.type` | `type` | EffectEvidenceSynthesis.effectEstimate.type | Type of efffect estimate | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/effect-estimate-type` |
| `EffectEvidenceSynthesis.effectEstimate.unitOfMeasure` | `EffectEvidenceSynthesis.effectEstimate.unitOfMeasure` | `unitOfMeasure` | EffectEvidenceSynthesis.effectEstimate.unitOfMeasure | What unit is the outcome described in? | 0..1 | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/ucum-units|4.0.1` |
| `EffectEvidenceSynthesis.effectEstimate.value` | `EffectEvidenceSynthesis.effectEstimate.value` | `value` | EffectEvidenceSynthesis.effectEstimate.value | Point estimate | 0..1 | decimal |  |  |
| `EffectEvidenceSynthesis.effectEstimate.variantState` | `EffectEvidenceSynthesis.effectEstimate.variantState` | `variantState` | EffectEvidenceSynthesis.effectEstimate.variantState | Variant exposure states | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/evidence-variant-state` |
| `EffectEvidenceSynthesis.effectivePeriod` | `EffectEvidenceSynthesis.effectivePeriod` | `effectivePeriod` | EffectEvidenceSynthesis.effectivePeriod | When the effect evidence synthesis is expected to be used | 0..1 | Period |  |  |
| `EffectEvidenceSynthesis.endorser` | `EffectEvidenceSynthesis.endorser` | `endorser` | EffectEvidenceSynthesis.endorser | Who endorsed the content | 0..* | ContactDetail |  |  |
| `EffectEvidenceSynthesis.exposure` | `EffectEvidenceSynthesis.exposure` | `exposure` | EffectEvidenceSynthesis.exposure | What exposure? | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/EvidenceVariable) |  |  |
| `EffectEvidenceSynthesis.exposureAlternative` | `EffectEvidenceSynthesis.exposureAlternative` | `exposureAlternative` | EffectEvidenceSynthesis.exposureAlternative | What comparison exposure? | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/EvidenceVariable) |  |  |
| `EffectEvidenceSynthesis.extension` | `EffectEvidenceSynthesis.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EffectEvidenceSynthesis.id` | `EffectEvidenceSynthesis.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `EffectEvidenceSynthesis.identifier` | `EffectEvidenceSynthesis.identifier` | `identifier` | EffectEvidenceSynthesis.identifier | Additional identifier for the effect evidence synthesis | 0..* | Identifier |  |  |
| `EffectEvidenceSynthesis.implicitRules` | `EffectEvidenceSynthesis.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `EffectEvidenceSynthesis.jurisdiction` | `EffectEvidenceSynthesis.jurisdiction` | `jurisdiction` | EffectEvidenceSynthesis.jurisdiction | Intended jurisdiction for effect evidence synthesis (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `EffectEvidenceSynthesis.language` | `EffectEvidenceSynthesis.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `EffectEvidenceSynthesis.lastReviewDate` | `EffectEvidenceSynthesis.lastReviewDate` | `lastReviewDate` | EffectEvidenceSynthesis.lastReviewDate | When the effect evidence synthesis was last reviewed | 0..1 | date |  |  |
| `EffectEvidenceSynthesis.meta` | `EffectEvidenceSynthesis.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `EffectEvidenceSynthesis.modifierExtension` | `EffectEvidenceSynthesis.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `EffectEvidenceSynthesis.name` | `EffectEvidenceSynthesis.name` | `name` | EffectEvidenceSynthesis.name | Name for this effect evidence synthesis (computer friendly) | 0..1 | string |  |  |
| `EffectEvidenceSynthesis.note` | `EffectEvidenceSynthesis.note` | `note` | EffectEvidenceSynthesis.note | Used for footnotes or explanatory notes | 0..* | Annotation |  |  |
| `EffectEvidenceSynthesis.outcome` | `EffectEvidenceSynthesis.outcome` | `outcome` | EffectEvidenceSynthesis.outcome | What outcome? | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/EvidenceVariable) |  |  |
| `EffectEvidenceSynthesis.population` | `EffectEvidenceSynthesis.population` | `population` | EffectEvidenceSynthesis.population | What population? | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/EvidenceVariable) |  |  |
| `EffectEvidenceSynthesis.publisher` | `EffectEvidenceSynthesis.publisher` | `publisher` | EffectEvidenceSynthesis.publisher | Name of the publisher (organization or individual) | 0..1 | string |  |  |
| `EffectEvidenceSynthesis.relatedArtifact` | `EffectEvidenceSynthesis.relatedArtifact` | `relatedArtifact` | EffectEvidenceSynthesis.relatedArtifact | Additional documentation, citations, etc. | 0..* | RelatedArtifact |  |  |
| `EffectEvidenceSynthesis.resultsByExposure` | `EffectEvidenceSynthesis.resultsByExposure` | `resultsByExposure` | EffectEvidenceSynthesis.resultsByExposure | What was the result per exposure? | 0..* | BackboneElement |  |  |
| `EffectEvidenceSynthesis.resultsByExposure.description` | `EffectEvidenceSynthesis.resultsByExposure.description` | `description` | EffectEvidenceSynthesis.resultsByExposure.description | Description of results by exposure | 0..1 | string |  |  |
| `EffectEvidenceSynthesis.resultsByExposure.exposureState` | `EffectEvidenceSynthesis.resultsByExposure.exposureState` | `exposureState` | EffectEvidenceSynthesis.resultsByExposure.exposureState | exposure \| exposure-alternative | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/exposure-state|4.0.1` |
| `EffectEvidenceSynthesis.resultsByExposure.extension` | `EffectEvidenceSynthesis.resultsByExposure.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EffectEvidenceSynthesis.resultsByExposure.id` | `EffectEvidenceSynthesis.resultsByExposure.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `EffectEvidenceSynthesis.resultsByExposure.modifierExtension` | `EffectEvidenceSynthesis.resultsByExposure.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `EffectEvidenceSynthesis.resultsByExposure.riskEvidenceSynthesis` | `EffectEvidenceSynthesis.resultsByExposure.riskEvidenceSynthesis` | `riskEvidenceSynthesis` | EffectEvidenceSynthesis.resultsByExposure.riskEvidenceSynthesis | Risk evidence synthesis | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/RiskEvidenceSynthesis) |  |  |
| `EffectEvidenceSynthesis.resultsByExposure.variantState` | `EffectEvidenceSynthesis.resultsByExposure.variantState` | `variantState` | EffectEvidenceSynthesis.resultsByExposure.variantState | Variant exposure states | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/evidence-variant-state` |
| `EffectEvidenceSynthesis.reviewer` | `EffectEvidenceSynthesis.reviewer` | `reviewer` | EffectEvidenceSynthesis.reviewer | Who reviewed the content | 0..* | ContactDetail |  |  |
| `EffectEvidenceSynthesis.sampleSize` | `EffectEvidenceSynthesis.sampleSize` | `sampleSize` | EffectEvidenceSynthesis.sampleSize | What sample size was involved? | 0..1 | BackboneElement |  |  |
| `EffectEvidenceSynthesis.sampleSize.description` | `EffectEvidenceSynthesis.sampleSize.description` | `description` | EffectEvidenceSynthesis.sampleSize.description | Description of sample size | 0..1 | string |  |  |
| `EffectEvidenceSynthesis.sampleSize.extension` | `EffectEvidenceSynthesis.sampleSize.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EffectEvidenceSynthesis.sampleSize.id` | `EffectEvidenceSynthesis.sampleSize.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `EffectEvidenceSynthesis.sampleSize.modifierExtension` | `EffectEvidenceSynthesis.sampleSize.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `EffectEvidenceSynthesis.sampleSize.numberOfParticipants` | `EffectEvidenceSynthesis.sampleSize.numberOfParticipants` | `numberOfParticipants` | EffectEvidenceSynthesis.sampleSize.numberOfParticipants | How many participants? | 0..1 | integer |  |  |
| `EffectEvidenceSynthesis.sampleSize.numberOfStudies` | `EffectEvidenceSynthesis.sampleSize.numberOfStudies` | `numberOfStudies` | EffectEvidenceSynthesis.sampleSize.numberOfStudies | How many studies? | 0..1 | integer |  |  |
| `EffectEvidenceSynthesis.status` | `EffectEvidenceSynthesis.status` | `status` | EffectEvidenceSynthesis.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|4.0.1` |
| `EffectEvidenceSynthesis.studyType` | `EffectEvidenceSynthesis.studyType` | `studyType` | EffectEvidenceSynthesis.studyType | Type of study | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/study-type` |
| `EffectEvidenceSynthesis.synthesisType` | `EffectEvidenceSynthesis.synthesisType` | `synthesisType` | EffectEvidenceSynthesis.synthesisType | Type of synthesis | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/synthesis-type` |
| `EffectEvidenceSynthesis.text` | `EffectEvidenceSynthesis.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `EffectEvidenceSynthesis.title` | `EffectEvidenceSynthesis.title` | `title` | EffectEvidenceSynthesis.title | Name for this effect evidence synthesis (human friendly) | 0..1 | string |  |  |
| `EffectEvidenceSynthesis.topic` | `EffectEvidenceSynthesis.topic` | `topic` | EffectEvidenceSynthesis.topic | The category of the EffectEvidenceSynthesis, such as Education, Treatment, Assessment, etc. | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/definition-topic` |
| `EffectEvidenceSynthesis.url` | `EffectEvidenceSynthesis.url` | `url` | EffectEvidenceSynthesis.url | Canonical identifier for this effect evidence synthesis, represented as a URI (globally unique) | 0..1 | uri |  |  |
| `EffectEvidenceSynthesis.useContext` | `EffectEvidenceSynthesis.useContext` | `useContext` | EffectEvidenceSynthesis.useContext | The context that the content is intended to support | 0..* | UsageContext |  |  |
| `EffectEvidenceSynthesis.version` | `EffectEvidenceSynthesis.version` | `version` | EffectEvidenceSynthesis.version | Business version of the effect evidence synthesis | 0..1 | string |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

