Comparison of 
Generated at Monday, April 14, 2025 6:17:30 PM

### ResearchElementDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | ResearchElementDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ResearchElementDefinition` |
| Version | 4.0.1 |
| Description | The ResearchElementDefinition resource describes a "PICO" element that knowledge (evidence, assertion, recommendation) is about. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1148` |
| Database Snapshot Count | `57` |
| Database Differential Count | `46` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ResearchElementDefinition` | `ResearchElementDefinition` | `ResearchElementDefinition` | ResearchElementDefinition | A population, intervention, or exposure definition | 0..* | ResearchElementDefinition |  |  |
| `ResearchElementDefinition.approvalDate` | `ResearchElementDefinition.approvalDate` | `approvalDate` | ResearchElementDefinition.approvalDate | When the research element definition was approved by publisher | 0..1 | date |  |  |
| `ResearchElementDefinition.author` | `ResearchElementDefinition.author` | `author` | ResearchElementDefinition.author | Who authored the content | 0..* | ContactDetail |  |  |
| `ResearchElementDefinition.characteristic` | `ResearchElementDefinition.characteristic` | `characteristic` | ResearchElementDefinition.characteristic | What defines the members of the research element | 1..* | BackboneElement |  |  |
| `ResearchElementDefinition.characteristic.definition[x]` | `ResearchElementDefinition.characteristic.definition[x]` | `definition[x]` | ResearchElementDefinition.characteristic.definition[x] | What code or expression defines members? | 1..1 | canonical(http://hl7.org/fhir/StructureDefinition/ValueSet), CodeableConcept, DataRequirement, Expression |  |  |
| `ResearchElementDefinition.characteristic.exclude` | `ResearchElementDefinition.characteristic.exclude` | `exclude` | ResearchElementDefinition.characteristic.exclude | Whether the characteristic includes or excludes members | 0..1 | boolean |  |  |
| `ResearchElementDefinition.characteristic.extension` | `ResearchElementDefinition.characteristic.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ResearchElementDefinition.characteristic.id` | `ResearchElementDefinition.characteristic.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ResearchElementDefinition.characteristic.modifierExtension` | `ResearchElementDefinition.characteristic.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ResearchElementDefinition.characteristic.participantEffectiveDescription` | `ResearchElementDefinition.characteristic.participantEffectiveDescription` | `participantEffectiveDescription` | ResearchElementDefinition.characteristic.participantEffectiveDescription | What time period do participants cover | 0..1 | string |  |  |
| `ResearchElementDefinition.characteristic.participantEffectiveGroupMeasure` | `ResearchElementDefinition.characteristic.participantEffectiveGroupMeasure` | `participantEffectiveGroupMeasure` | ResearchElementDefinition.characteristic.participantEffectiveGroupMeasure | mean \| median \| mean-of-mean \| mean-of-median \| median-of-mean \| median-of-median | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/group-measure|4.0.1` |
| `ResearchElementDefinition.characteristic.participantEffectiveTimeFromStart` | `ResearchElementDefinition.characteristic.participantEffectiveTimeFromStart` | `participantEffectiveTimeFromStart` | ResearchElementDefinition.characteristic.participantEffectiveTimeFromStart | Observation time from study start | 0..1 | Duration |  |  |
| `ResearchElementDefinition.characteristic.participantEffective[x]` | `ResearchElementDefinition.characteristic.participantEffective[x]` | `participantEffective[x]` | ResearchElementDefinition.characteristic.participantEffective[x] | What time period do participants cover | 0..1 | dateTime, Duration, Period, Timing |  |  |
| `ResearchElementDefinition.characteristic.studyEffectiveDescription` | `ResearchElementDefinition.characteristic.studyEffectiveDescription` | `studyEffectiveDescription` | ResearchElementDefinition.characteristic.studyEffectiveDescription | What time period does the study cover | 0..1 | string |  |  |
| `ResearchElementDefinition.characteristic.studyEffectiveGroupMeasure` | `ResearchElementDefinition.characteristic.studyEffectiveGroupMeasure` | `studyEffectiveGroupMeasure` | ResearchElementDefinition.characteristic.studyEffectiveGroupMeasure | mean \| median \| mean-of-mean \| mean-of-median \| median-of-mean \| median-of-median | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/group-measure|4.0.1` |
| `ResearchElementDefinition.characteristic.studyEffectiveTimeFromStart` | `ResearchElementDefinition.characteristic.studyEffectiveTimeFromStart` | `studyEffectiveTimeFromStart` | ResearchElementDefinition.characteristic.studyEffectiveTimeFromStart | Observation time from study start | 0..1 | Duration |  |  |
| `ResearchElementDefinition.characteristic.studyEffective[x]` | `ResearchElementDefinition.characteristic.studyEffective[x]` | `studyEffective[x]` | ResearchElementDefinition.characteristic.studyEffective[x] | What time period does the study cover | 0..1 | dateTime, Duration, Period, Timing |  |  |
| `ResearchElementDefinition.characteristic.unitOfMeasure` | `ResearchElementDefinition.characteristic.unitOfMeasure` | `unitOfMeasure` | ResearchElementDefinition.characteristic.unitOfMeasure | What unit is the outcome described in? | 0..1 | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/ucum-units|4.0.1` |
| `ResearchElementDefinition.characteristic.usageContext` | `ResearchElementDefinition.characteristic.usageContext` | `usageContext` | ResearchElementDefinition.characteristic.usageContext | What code/value pairs define members? | 0..* | UsageContext |  |  |
| `ResearchElementDefinition.comment` | `ResearchElementDefinition.comment` | `comment` | ResearchElementDefinition.comment | Used for footnotes or explanatory notes | 0..* | string |  |  |
| `ResearchElementDefinition.contact` | `ResearchElementDefinition.contact` | `contact` | ResearchElementDefinition.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `ResearchElementDefinition.contained` | `ResearchElementDefinition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ResearchElementDefinition.copyright` | `ResearchElementDefinition.copyright` | `copyright` | ResearchElementDefinition.copyright | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `ResearchElementDefinition.date` | `ResearchElementDefinition.date` | `date` | ResearchElementDefinition.date | Date last changed | 0..1 | dateTime |  |  |
| `ResearchElementDefinition.description` | `ResearchElementDefinition.description` | `description` | ResearchElementDefinition.description | Natural language description of the research element definition | 0..1 | markdown |  |  |
| `ResearchElementDefinition.editor` | `ResearchElementDefinition.editor` | `editor` | ResearchElementDefinition.editor | Who edited the content | 0..* | ContactDetail |  |  |
| `ResearchElementDefinition.effectivePeriod` | `ResearchElementDefinition.effectivePeriod` | `effectivePeriod` | ResearchElementDefinition.effectivePeriod | When the research element definition is expected to be used | 0..1 | Period |  |  |
| `ResearchElementDefinition.endorser` | `ResearchElementDefinition.endorser` | `endorser` | ResearchElementDefinition.endorser | Who endorsed the content | 0..* | ContactDetail |  |  |
| `ResearchElementDefinition.experimental` | `ResearchElementDefinition.experimental` | `experimental` | ResearchElementDefinition.experimental | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `ResearchElementDefinition.extension` | `ResearchElementDefinition.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ResearchElementDefinition.id` | `ResearchElementDefinition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ResearchElementDefinition.identifier` | `ResearchElementDefinition.identifier` | `identifier` | ResearchElementDefinition.identifier | Additional identifier for the research element definition | 0..* | Identifier |  |  |
| `ResearchElementDefinition.implicitRules` | `ResearchElementDefinition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ResearchElementDefinition.jurisdiction` | `ResearchElementDefinition.jurisdiction` | `jurisdiction` | ResearchElementDefinition.jurisdiction | Intended jurisdiction for research element definition (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `ResearchElementDefinition.language` | `ResearchElementDefinition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `ResearchElementDefinition.lastReviewDate` | `ResearchElementDefinition.lastReviewDate` | `lastReviewDate` | ResearchElementDefinition.lastReviewDate | When the research element definition was last reviewed | 0..1 | date |  |  |
| `ResearchElementDefinition.library` | `ResearchElementDefinition.library` | `library` | ResearchElementDefinition.library | Logic used by the ResearchElementDefinition | 0..* | canonical(http://hl7.org/fhir/StructureDefinition/Library) |  |  |
| `ResearchElementDefinition.meta` | `ResearchElementDefinition.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ResearchElementDefinition.modifierExtension` | `ResearchElementDefinition.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ResearchElementDefinition.name` | `ResearchElementDefinition.name` | `name` | ResearchElementDefinition.name | Name for this research element definition (computer friendly) | 0..1 | string |  |  |
| `ResearchElementDefinition.publisher` | `ResearchElementDefinition.publisher` | `publisher` | ResearchElementDefinition.publisher | Name of the publisher (organization or individual) | 0..1 | string |  |  |
| `ResearchElementDefinition.purpose` | `ResearchElementDefinition.purpose` | `purpose` | ResearchElementDefinition.purpose | Why this research element definition is defined | 0..1 | markdown |  |  |
| `ResearchElementDefinition.relatedArtifact` | `ResearchElementDefinition.relatedArtifact` | `relatedArtifact` | ResearchElementDefinition.relatedArtifact | Additional documentation, citations, etc. | 0..* | RelatedArtifact |  |  |
| `ResearchElementDefinition.reviewer` | `ResearchElementDefinition.reviewer` | `reviewer` | ResearchElementDefinition.reviewer | Who reviewed the content | 0..* | ContactDetail |  |  |
| `ResearchElementDefinition.shortTitle` | `ResearchElementDefinition.shortTitle` | `shortTitle` | ResearchElementDefinition.shortTitle | Title for use in informal contexts | 0..1 | string |  |  |
| `ResearchElementDefinition.status` | `ResearchElementDefinition.status` | `status` | ResearchElementDefinition.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|4.0.1` |
| `ResearchElementDefinition.subject[x]` | `ResearchElementDefinition.subject[x]` | `subject[x]` | ResearchElementDefinition.subject[x] | E.g. Patient, Practitioner, RelatedPerson, Organization, Location, Device | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Group) | `Extensible` | `http://hl7.org/fhir/ValueSet/subject-type` |
| `ResearchElementDefinition.subtitle` | `ResearchElementDefinition.subtitle` | `subtitle` | ResearchElementDefinition.subtitle | Subordinate title of the ResearchElementDefinition | 0..1 | string |  |  |
| `ResearchElementDefinition.text` | `ResearchElementDefinition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `ResearchElementDefinition.title` | `ResearchElementDefinition.title` | `title` | ResearchElementDefinition.title | Name for this research element definition (human friendly) | 0..1 | string |  |  |
| `ResearchElementDefinition.topic` | `ResearchElementDefinition.topic` | `topic` | ResearchElementDefinition.topic | The category of the ResearchElementDefinition, such as Education, Treatment, Assessment, etc. | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/definition-topic` |
| `ResearchElementDefinition.type` | `ResearchElementDefinition.type` | `type` | ResearchElementDefinition.type | population \| exposure \| outcome | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/research-element-type|4.0.1` |
| `ResearchElementDefinition.url` | `ResearchElementDefinition.url` | `url` | ResearchElementDefinition.url | Canonical identifier for this research element definition, represented as a URI (globally unique) | 0..1 | uri |  |  |
| `ResearchElementDefinition.usage` | `ResearchElementDefinition.usage` | `usage` | ResearchElementDefinition.usage | Describes the clinical usage of the ResearchElementDefinition | 0..1 | string |  |  |
| `ResearchElementDefinition.useContext` | `ResearchElementDefinition.useContext` | `useContext` | ResearchElementDefinition.useContext | The context that the content is intended to support | 0..* | UsageContext |  |  |
| `ResearchElementDefinition.variableType` | `ResearchElementDefinition.variableType` | `variableType` | ResearchElementDefinition.variableType | dichotomous \| continuous \| descriptive | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/variable-type|4.0.1` |
| `ResearchElementDefinition.version` | `ResearchElementDefinition.version` | `version` | ResearchElementDefinition.version | Business version of the research element definition | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [ResearchElementDefinition](/docs/R4/Resources/ResearchElementDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ResearchElementDefinition\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1599`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1600`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ResearchElementDefinition](/docs/R4B/Resources/ResearchElementDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ResearchElementDefinition\|4.3.0` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | 
### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ResearchElementDefinition from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | R4 ResearchElementDefinition| Relationship | [R4B ResearchElementDefinition](/docs/R4B/Resources/ResearchElementDefinition.md)| Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | **`ResearchElementDefinition`**| _Equivalent_<br/>(32535/32536)| `ResearchElementDefinition`| | | 
| | | | | **`ResearchElementDefinition.id`**| _Equivalent_<br/>(32537/32538)| `ResearchElementDefinition.id`| | | 
| | | | | **`ResearchElementDefinition.meta`**| _Equivalent_<br/>(32539/32540)| `ResearchElementDefinition.meta`| | | 
| | | | | **`ResearchElementDefinition.implicitRules`**| _Equivalent_<br/>(32541/32542)| `ResearchElementDefinition.implicitRules`| | | 
| | | | | **`ResearchElementDefinition.language`**| _Equivalent_<br/>(32543/32544)| `ResearchElementDefinition.language`| | | 
| | | | | **`ResearchElementDefinition.text`**| _Equivalent_<br/>(32545/32546)| `ResearchElementDefinition.text`| | | 
| | | | | **`ResearchElementDefinition.contained`**| _Equivalent_<br/>(32547/32548)| `ResearchElementDefinition.contained`| | | 
| | | | | **`ResearchElementDefinition.extension`**| _Equivalent_<br/>(32549/32550)| `ResearchElementDefinition.extension`| | | 
| | | | | **`ResearchElementDefinition.modifierExtension`**| _Equivalent_<br/>(32551/32552)| `ResearchElementDefinition.modifierExtension`| | | 
| | | | | **`ResearchElementDefinition.url`**| _Equivalent_<br/>(32553/32554)| `ResearchElementDefinition.url`| | | 
| | | | | **`ResearchElementDefinition.identifier`**| _Equivalent_<br/>(32555/32556)| `ResearchElementDefinition.identifier`| | | 
| | | | | **`ResearchElementDefinition.version`**| _Equivalent_<br/>(32557/32558)| `ResearchElementDefinition.version`| | | 
| | | | | **`ResearchElementDefinition.name`**| _Equivalent_<br/>(32559/32560)| `ResearchElementDefinition.name`| | | 
| | | | | **`ResearchElementDefinition.title`**| _Equivalent_<br/>(32561/32562)| `ResearchElementDefinition.title`| | | 
| | | | | **`ResearchElementDefinition.shortTitle`**| _Equivalent_<br/>(32563/32564)| `ResearchElementDefinition.shortTitle`| | | 
| | | | | **`ResearchElementDefinition.subtitle`**| _Equivalent_<br/>(32565/32566)| `ResearchElementDefinition.subtitle`| | | 
| | | | | **`ResearchElementDefinition.status`**| _Equivalent_<br/>(32567/32568)| `ResearchElementDefinition.status`| | | 
| | | | | **`ResearchElementDefinition.experimental`**| _Equivalent_<br/>(32569/32570)| `ResearchElementDefinition.experimental`| | | 
| | | | | **`ResearchElementDefinition.subject[x]`**| _Equivalent_<br/>(32571/32572)| `ResearchElementDefinition.subject[x]`| | | 
| | | | | **`ResearchElementDefinition.date`**| _Equivalent_<br/>(32573/32574)| `ResearchElementDefinition.date`| | | 
| | | | | **`ResearchElementDefinition.publisher`**| _Equivalent_<br/>(32575/32576)| `ResearchElementDefinition.publisher`| | | 
| | | | | **`ResearchElementDefinition.contact`**| _Equivalent_<br/>(32577/32578)| `ResearchElementDefinition.contact`| | | 
| | | | | **`ResearchElementDefinition.description`**| _Equivalent_<br/>(32579/32580)| `ResearchElementDefinition.description`| | | 
| | | | | **`ResearchElementDefinition.comment`**| _Equivalent_<br/>(32581/32582)| `ResearchElementDefinition.comment`| | | 
| | | | | **`ResearchElementDefinition.useContext`**| _Equivalent_<br/>(32583/32584)| `ResearchElementDefinition.useContext`| | | 
| | | | | **`ResearchElementDefinition.jurisdiction`**| _Equivalent_<br/>(32585/32586)| `ResearchElementDefinition.jurisdiction`| | | 
| | | | | **`ResearchElementDefinition.purpose`**| _Equivalent_<br/>(32587/32588)| `ResearchElementDefinition.purpose`| | | 
| | | | | **`ResearchElementDefinition.usage`**| _Equivalent_<br/>(32589/32590)| `ResearchElementDefinition.usage`| | | 
| | | | | **`ResearchElementDefinition.copyright`**| _Equivalent_<br/>(32591/32592)| `ResearchElementDefinition.copyright`| | | 
| | | | | **`ResearchElementDefinition.approvalDate`**| _Equivalent_<br/>(32593/32594)| `ResearchElementDefinition.approvalDate`| | | 
| | | | | **`ResearchElementDefinition.lastReviewDate`**| _Equivalent_<br/>(32595/32596)| `ResearchElementDefinition.lastReviewDate`| | | 
| | | | | **`ResearchElementDefinition.effectivePeriod`**| _Equivalent_<br/>(32597/32598)| `ResearchElementDefinition.effectivePeriod`| | | 
| | | | | **`ResearchElementDefinition.topic`**| _Equivalent_<br/>(32599/32600)| `ResearchElementDefinition.topic`| | | 
| | | | | **`ResearchElementDefinition.author`**| _Equivalent_<br/>(32601/32602)| `ResearchElementDefinition.author`| | | 
| | | | | **`ResearchElementDefinition.editor`**| _Equivalent_<br/>(32603/32604)| `ResearchElementDefinition.editor`| | | 
| | | | | **`ResearchElementDefinition.reviewer`**| _Equivalent_<br/>(32605/32606)| `ResearchElementDefinition.reviewer`| | | 
| | | | | **`ResearchElementDefinition.endorser`**| _Equivalent_<br/>(32607/32608)| `ResearchElementDefinition.endorser`| | | 
| | | | | **`ResearchElementDefinition.relatedArtifact`**| _Equivalent_<br/>(32609/32610)| `ResearchElementDefinition.relatedArtifact`| | | 
| | | | | **`ResearchElementDefinition.library`**| _Equivalent_<br/>(32611/32612)| `ResearchElementDefinition.library`| | | 
| | | | | **`ResearchElementDefinition.type`**| _Equivalent_<br/>(32613/32614)| `ResearchElementDefinition.type`| | | 
| | | | | **`ResearchElementDefinition.variableType`**| _Equivalent_<br/>(32615/32616)| `ResearchElementDefinition.variableType`| | | 
| | | | | **`ResearchElementDefinition.characteristic`**| _Equivalent_<br/>(32617/32618)| `ResearchElementDefinition.characteristic`| | | 
| | | | | **`ResearchElementDefinition.characteristic.id`**| _Equivalent_<br/>(32619/32620)| `ResearchElementDefinition.characteristic.id`| | | 
| | | | | **`ResearchElementDefinition.characteristic.extension`**| _Equivalent_<br/>(32621/32622)| `ResearchElementDefinition.characteristic.extension`| | | 
| | | | | **`ResearchElementDefinition.characteristic.modifierExtension`**| _Equivalent_<br/>(32623/32624)| `ResearchElementDefinition.characteristic.modifierExtension`| | | 
| | | | | **`ResearchElementDefinition.characteristic.definition[x]`**| _Equivalent_<br/>(32625/32626)| `ResearchElementDefinition.characteristic.definition[x]`| | | 
| | | | | **`ResearchElementDefinition.characteristic.usageContext`**| _Equivalent_<br/>(32627/32628)| `ResearchElementDefinition.characteristic.usageContext`| | | 
| | | | | **`ResearchElementDefinition.characteristic.exclude`**| _Equivalent_<br/>(32629/32630)| `ResearchElementDefinition.characteristic.exclude`| | | 
| | | | | **`ResearchElementDefinition.characteristic.unitOfMeasure`**| _Equivalent_<br/>(32631/32632)| `ResearchElementDefinition.characteristic.unitOfMeasure`| | | 
| | | | | **`ResearchElementDefinition.characteristic.studyEffectiveDescription`**| _Equivalent_<br/>(32633/32634)| `ResearchElementDefinition.characteristic.studyEffectiveDescription`| | | 
| | | | | **`ResearchElementDefinition.characteristic.studyEffective[x]`**| _Equivalent_<br/>(32635/32636)| `ResearchElementDefinition.characteristic.studyEffective[x]`| | | 
| | | | | **`ResearchElementDefinition.characteristic.studyEffectiveTimeFromStart`**| _Equivalent_<br/>(32637/32638)| `ResearchElementDefinition.characteristic.studyEffectiveTimeFromStart`| | | 
| | | | | **`ResearchElementDefinition.characteristic.studyEffectiveGroupMeasure`**| _Equivalent_<br/>(32639/32640)| `ResearchElementDefinition.characteristic.studyEffectiveGroupMeasure`| | | 
| | | | | **`ResearchElementDefinition.characteristic.participantEffectiveDescription`**| _Equivalent_<br/>(32641/32642)| `ResearchElementDefinition.characteristic.participantEffectiveDescription`| | | 
| | | | | **`ResearchElementDefinition.characteristic.participantEffective[x]`**| _Equivalent_<br/>(32643/32644)| `ResearchElementDefinition.characteristic.participantEffective[x]`| | | 
| | | | | **`ResearchElementDefinition.characteristic.participantEffectiveTimeFromStart`**| _Equivalent_<br/>(32645/32646)| `ResearchElementDefinition.characteristic.participantEffectiveTimeFromStart`| | | 
| | | | | **`ResearchElementDefinition.characteristic.participantEffectiveGroupMeasure`**| _Equivalent_<br/>(32647/32648)| `ResearchElementDefinition.characteristic.participantEffectiveGroupMeasure`| | | 
| | | | | *57 of 57 elements used* | | *57 of 57 elements used* | | 

