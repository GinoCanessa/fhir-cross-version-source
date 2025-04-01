Comparison of 
Generated at Tuesday, April 1, 2025 1:39:22 PM

### Evidence

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | Evidence |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Evidence` |
| Version | 4.0.1 |
| Description | The Evidence resource describes the conditional state (population and any exposures being compared within the population) and outcome (if specified) that the knowledge (evidence, assertion, recommendation) is about. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1081` |
| Database Snapshot Count | `37` |
| Database Differential Count | `29` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Evidence` | `Evidence` | `Evidence` | Evidence | A research context or question | 0..* | Evidence |  |  |
| `Evidence.approvalDate` | `Evidence.approvalDate` | `approvalDate` | Evidence.approvalDate | When the evidence was approved by publisher | 0..1 | date |  |  |
| `Evidence.author` | `Evidence.author` | `author` | Evidence.author | Who authored the content | 0..* | ContactDetail |  |  |
| `Evidence.contact` | `Evidence.contact` | `contact` | Evidence.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `Evidence.contained` | `Evidence.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Evidence.copyright` | `Evidence.copyright` | `copyright` | Evidence.copyright | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `Evidence.date` | `Evidence.date` | `date` | Evidence.date | Date last changed | 0..1 | dateTime |  |  |
| `Evidence.description` | `Evidence.description` | `description` | Evidence.description | Natural language description of the evidence | 0..1 | markdown |  |  |
| `Evidence.editor` | `Evidence.editor` | `editor` | Evidence.editor | Who edited the content | 0..* | ContactDetail |  |  |
| `Evidence.effectivePeriod` | `Evidence.effectivePeriod` | `effectivePeriod` | Evidence.effectivePeriod | When the evidence is expected to be used | 0..1 | Period |  |  |
| `Evidence.endorser` | `Evidence.endorser` | `endorser` | Evidence.endorser | Who endorsed the content | 0..* | ContactDetail |  |  |
| `Evidence.exposureBackground` | `Evidence.exposureBackground` | `exposureBackground` | Evidence.exposureBackground | What population? | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/EvidenceVariable) |  |  |
| `Evidence.exposureVariant` | `Evidence.exposureVariant` | `exposureVariant` | Evidence.exposureVariant | What exposure? | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/EvidenceVariable) |  |  |
| `Evidence.extension` | `Evidence.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Evidence.id` | `Evidence.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Evidence.identifier` | `Evidence.identifier` | `identifier` | Evidence.identifier | Additional identifier for the evidence | 0..* | Identifier |  |  |
| `Evidence.implicitRules` | `Evidence.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Evidence.jurisdiction` | `Evidence.jurisdiction` | `jurisdiction` | Evidence.jurisdiction | Intended jurisdiction for evidence (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `Evidence.language` | `Evidence.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `Evidence.lastReviewDate` | `Evidence.lastReviewDate` | `lastReviewDate` | Evidence.lastReviewDate | When the evidence was last reviewed | 0..1 | date |  |  |
| `Evidence.meta` | `Evidence.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Evidence.modifierExtension` | `Evidence.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Evidence.name` | `Evidence.name` | `name` | Evidence.name | Name for this evidence (computer friendly) | 0..1 | string |  |  |
| `Evidence.note` | `Evidence.note` | `note` | Evidence.note | Used for footnotes or explanatory notes | 0..* | Annotation |  |  |
| `Evidence.outcome` | `Evidence.outcome` | `outcome` | Evidence.outcome | What outcome? | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/EvidenceVariable) |  |  |
| `Evidence.publisher` | `Evidence.publisher` | `publisher` | Evidence.publisher | Name of the publisher (organization or individual) | 0..1 | string |  |  |
| `Evidence.relatedArtifact` | `Evidence.relatedArtifact` | `relatedArtifact` | Evidence.relatedArtifact | Additional documentation, citations, etc. | 0..* | RelatedArtifact |  |  |
| `Evidence.reviewer` | `Evidence.reviewer` | `reviewer` | Evidence.reviewer | Who reviewed the content | 0..* | ContactDetail |  |  |
| `Evidence.shortTitle` | `Evidence.shortTitle` | `shortTitle` | Evidence.shortTitle | Title for use in informal contexts | 0..1 | string |  |  |
| `Evidence.status` | `Evidence.status` | `status` | Evidence.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|4.0.1` |
| `Evidence.subtitle` | `Evidence.subtitle` | `subtitle` | Evidence.subtitle | Subordinate title of the Evidence | 0..1 | string |  |  |
| `Evidence.text` | `Evidence.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Evidence.title` | `Evidence.title` | `title` | Evidence.title | Name for this evidence (human friendly) | 0..1 | string |  |  |
| `Evidence.topic` | `Evidence.topic` | `topic` | Evidence.topic | The category of the Evidence, such as Education, Treatment, Assessment, etc. | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/definition-topic` |
| `Evidence.url` | `Evidence.url` | `url` | Evidence.url | Canonical identifier for this evidence, represented as a URI (globally unique) | 0..1 | uri |  |  |
| `Evidence.useContext` | `Evidence.useContext` | `useContext` | Evidence.useContext | The context that the content is intended to support | 0..* | UsageContext |  |  |
| `Evidence.version` | `Evidence.version` | `version` | Evidence.version | Business version of the evidence | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [Evidence](/docs/R4/Resources/Evidence.md)<br/> `http://hl7.org/fhir/StructureDefinition/Evidence\|4.0.1` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1485`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1486`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Evidence](/docs/R4B/Resources/Evidence.md)<br/> `http://hl7.org/fhir/StructureDefinition/Evidence\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `975`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1204`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Evidence](/docs/R5/Resources/Evidence.md)<br/> `http://hl7.org/fhir/StructureDefinition/Evidence\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Evidence from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | R4 Evidence| Relationship | [R4B Evidence](/docs/R4B/Resources/Evidence.md)| Relationship | [R5 Evidence](/docs/R5/Resources/Evidence.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | **`Evidence`**| _Equivalent_<br/>(26540/26541)| `Evidence`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(41342)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(41343)| `Evidence`
| | | | | **`Evidence.id`**| _Equivalent_<br/>(26542/26543)| `Evidence.id`| _Equivalent_<br/>(41344/41345)| `Evidence.id`
| | | | | **`Evidence.meta`**| _Equivalent_<br/>(26544/26545)| `Evidence.meta`| _Equivalent_<br/>(41346/41347)| `Evidence.meta`
| | | | | **`Evidence.implicitRules`**| _Equivalent_<br/>(26546/26547)| `Evidence.implicitRules`| _Equivalent_<br/>(41348/41349)| `Evidence.implicitRules`
| | | | | **`Evidence.language`**| _Equivalent_<br/>(26548/26549)| `Evidence.language`| _Equivalent_<br/>(41350/41351)| `Evidence.language`
| | | | | **`Evidence.text`**| _Equivalent_<br/>(26550/26551)| `Evidence.text`| _Equivalent_<br/>(41352/41353)| `Evidence.text`
| | | | | **`Evidence.contained`**| _Equivalent_<br/>(26552/26553)| `Evidence.contained`| _Equivalent_<br/>(41354/41355)| `Evidence.contained`
| | | | | **`Evidence.extension`**| _Equivalent_<br/>(26554/26555)| `Evidence.extension`| _Equivalent_<br/>(41356/41357)| `Evidence.extension`
| | | | | **`Evidence.modifierExtension`**| _Equivalent_<br/>(26556/26557)| `Evidence.modifierExtension`| _Equivalent_<br/>(41358/41359)| `Evidence.modifierExtension`
| | | | | **`Evidence.url`**| _Equivalent_<br/>(26558/26559)| `Evidence.url`| _Equivalent_<br/>(41360/41361)| `Evidence.url`
| | | | | **`Evidence.identifier`**| _Equivalent_<br/>(26560/26561)| `Evidence.identifier`| _Equivalent_<br/>(41362/41363)| `Evidence.identifier`
| | | | | **`Evidence.version`**| _Equivalent_<br/>(26562/26563)| `Evidence.version`| _Equivalent_<br/>(41364/41365)| `Evidence.version`
| | | | | **`Evidence.name`**| | | | | 
| | | | | **`Evidence.title`**| _Equivalent_<br/>(26565/26566)| `Evidence.title`| _Equivalent_<br/>(41366/41367)| `Evidence.title`
| | | | | **`Evidence.shortTitle`**| | | | | 
| | | | | **`Evidence.subtitle`**| | | | | 
| | | | | **`Evidence.status`**| _Equivalent_<br/>(26569/26570)| `Evidence.status`| _Equivalent_<br/>(41370/41371)| `Evidence.status`
| | | | | **`Evidence.date`**| _Equivalent_<br/>(26571/26572)| `Evidence.date`| _Equivalent_<br/>(41372/41373)| `Evidence.date`
| | | | | **`Evidence.publisher`**| _Equivalent_<br/>(26573/26574)| `Evidence.publisher`| _Equivalent_<br/>(41380/41381)| `Evidence.publisher`
| | | | | **`Evidence.contact`**| _Equivalent_<br/>(26575/26576)| `Evidence.contact`| _Equivalent_<br/>(41382/41383)| `Evidence.contact`
| | | | | **`Evidence.description`**| _Equivalent_<br/>(26577/26578)| `Evidence.description`| _Equivalent_<br/>(41394/41395)| `Evidence.description`
| | | | | **`Evidence.note`**| _Equivalent_<br/>(26579/26580)| `Evidence.note`| _Equivalent_<br/>(41398/41399)| `Evidence.note`
| | | | | **`Evidence.useContext`**| _Equivalent_<br/>(26581/26582)| `Evidence.useContext`| _Equivalent_<br/>(41374/41375)| `Evidence.useContext`
| | | | | **`Evidence.jurisdiction`**| | | | | 
| | | | | **`Evidence.copyright`**| | | | | 
| | | | | **`Evidence.approvalDate`**| _Equivalent_<br/>(26585/26586)| `Evidence.approvalDate`| _Equivalent_<br/>(41376/41377)| `Evidence.approvalDate`
| | | | | **`Evidence.lastReviewDate`**| _Equivalent_<br/>(26587/26588)| `Evidence.lastReviewDate`| _Equivalent_<br/>(41378/41379)| `Evidence.lastReviewDate`
| | | | | **`Evidence.effectivePeriod`**| | | | | 
| | | | | **`Evidence.topic`**| | | | | 
| | | | | **`Evidence.author`**| _Equivalent_<br/>(26591/26592)| `Evidence.author`| _Equivalent_<br/>(41384/41385)| `Evidence.author`
| | | | | **`Evidence.editor`**| _Equivalent_<br/>(26593/26594)| `Evidence.editor`| _Equivalent_<br/>(41386/41387)| `Evidence.editor`
| | | | | **`Evidence.reviewer`**| _Equivalent_<br/>(26595/26596)| `Evidence.reviewer`| _Equivalent_<br/>(41388/41389)| `Evidence.reviewer`
| | | | | **`Evidence.endorser`**| _Equivalent_<br/>(26597/26598)| `Evidence.endorser`| _Equivalent_<br/>(41390/41391)| `Evidence.endorser`
| | | | | **`Evidence.relatedArtifact`**| _Equivalent_<br/>(26599/26600)| `Evidence.relatedArtifact`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(41392)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(41393)| `Evidence.relatedArtifact`
| | | | | **`Evidence.exposureBackground`**| | | | | 
| | | | | **`Evidence.exposureVariant`**| | | | | 
| | | | | **`Evidence.outcome`**| | | | | 
| | | | | *37 of 37 elements used* | | *27 of 98 elements used* | | *27 of 104 elements used* 

