Comparison of 
Generated at Monday, April 14, 2025 6:17:30 PM

### EventDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | EventDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/EventDefinition` |
| Version | 4.0.1 |
| Description | The EventDefinition resource provides a reusable description of when a particular event can occur. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1080` |
| Database Snapshot Count | `37` |
| Database Differential Count | `29` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `EventDefinition` | `EventDefinition` | `EventDefinition` | EventDefinition | A description of when an event can occur | 0..* | EventDefinition |  |  |
| `EventDefinition.approvalDate` | `EventDefinition.approvalDate` | `approvalDate` | EventDefinition.approvalDate | When the event definition was approved by publisher | 0..1 | date |  |  |
| `EventDefinition.author` | `EventDefinition.author` | `author` | EventDefinition.author | Who authored the content | 0..* | ContactDetail |  |  |
| `EventDefinition.contact` | `EventDefinition.contact` | `contact` | EventDefinition.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `EventDefinition.contained` | `EventDefinition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `EventDefinition.copyright` | `EventDefinition.copyright` | `copyright` | EventDefinition.copyright | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `EventDefinition.date` | `EventDefinition.date` | `date` | EventDefinition.date | Date last changed | 0..1 | dateTime |  |  |
| `EventDefinition.description` | `EventDefinition.description` | `description` | EventDefinition.description | Natural language description of the event definition | 0..1 | markdown |  |  |
| `EventDefinition.editor` | `EventDefinition.editor` | `editor` | EventDefinition.editor | Who edited the content | 0..* | ContactDetail |  |  |
| `EventDefinition.effectivePeriod` | `EventDefinition.effectivePeriod` | `effectivePeriod` | EventDefinition.effectivePeriod | When the event definition is expected to be used | 0..1 | Period |  |  |
| `EventDefinition.endorser` | `EventDefinition.endorser` | `endorser` | EventDefinition.endorser | Who endorsed the content | 0..* | ContactDetail |  |  |
| `EventDefinition.experimental` | `EventDefinition.experimental` | `experimental` | EventDefinition.experimental | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `EventDefinition.extension` | `EventDefinition.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EventDefinition.id` | `EventDefinition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `EventDefinition.identifier` | `EventDefinition.identifier` | `identifier` | EventDefinition.identifier | Additional identifier for the event definition | 0..* | Identifier |  |  |
| `EventDefinition.implicitRules` | `EventDefinition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `EventDefinition.jurisdiction` | `EventDefinition.jurisdiction` | `jurisdiction` | EventDefinition.jurisdiction | Intended jurisdiction for event definition (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `EventDefinition.language` | `EventDefinition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `EventDefinition.lastReviewDate` | `EventDefinition.lastReviewDate` | `lastReviewDate` | EventDefinition.lastReviewDate | When the event definition was last reviewed | 0..1 | date |  |  |
| `EventDefinition.meta` | `EventDefinition.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `EventDefinition.modifierExtension` | `EventDefinition.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `EventDefinition.name` | `EventDefinition.name` | `name` | EventDefinition.name | Name for this event definition (computer friendly) | 0..1 | string |  |  |
| `EventDefinition.publisher` | `EventDefinition.publisher` | `publisher` | EventDefinition.publisher | Name of the publisher (organization or individual) | 0..1 | string |  |  |
| `EventDefinition.purpose` | `EventDefinition.purpose` | `purpose` | EventDefinition.purpose | Why this event definition is defined | 0..1 | markdown |  |  |
| `EventDefinition.relatedArtifact` | `EventDefinition.relatedArtifact` | `relatedArtifact` | EventDefinition.relatedArtifact | Additional documentation, citations, etc. | 0..* | RelatedArtifact |  |  |
| `EventDefinition.reviewer` | `EventDefinition.reviewer` | `reviewer` | EventDefinition.reviewer | Who reviewed the content | 0..* | ContactDetail |  |  |
| `EventDefinition.status` | `EventDefinition.status` | `status` | EventDefinition.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|4.0.1` |
| `EventDefinition.subject[x]` | `EventDefinition.subject[x]` | `subject[x]` | EventDefinition.subject[x] | Type of individual the event definition is focused on | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Group) | `Extensible` | `http://hl7.org/fhir/ValueSet/subject-type` |
| `EventDefinition.subtitle` | `EventDefinition.subtitle` | `subtitle` | EventDefinition.subtitle | Subordinate title of the event definition | 0..1 | string |  |  |
| `EventDefinition.text` | `EventDefinition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `EventDefinition.title` | `EventDefinition.title` | `title` | EventDefinition.title | Name for this event definition (human friendly) | 0..1 | string |  |  |
| `EventDefinition.topic` | `EventDefinition.topic` | `topic` | EventDefinition.topic | E.g. Education, Treatment, Assessment, etc. | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/definition-topic` |
| `EventDefinition.trigger` | `EventDefinition.trigger` | `trigger` | EventDefinition.trigger | "when" the event occurs (multiple = 'or') | 1..* | TriggerDefinition |  |  |
| `EventDefinition.url` | `EventDefinition.url` | `url` | EventDefinition.url | Canonical identifier for this event definition, represented as a URI (globally unique) | 0..1 | uri |  |  |
| `EventDefinition.usage` | `EventDefinition.usage` | `usage` | EventDefinition.usage | Describes the clinical usage of the event definition | 0..1 | string |  |  |
| `EventDefinition.useContext` | `EventDefinition.useContext` | `useContext` | EventDefinition.useContext | The context that the content is intended to support | 0..* | UsageContext |  |  |
| `EventDefinition.version` | `EventDefinition.version` | `version` | EventDefinition.version | Business version of the event definition | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [EventDefinition](/docs/R4/Resources/EventDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/EventDefinition\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1483`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1484`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [EventDefinition](/docs/R4B/Resources/EventDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/EventDefinition\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `974`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1203`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [EventDefinition](/docs/R5/Resources/EventDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/EventDefinition\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition EventDefinition from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | R4 EventDefinition| Relationship | [R4B EventDefinition](/docs/R4B/Resources/EventDefinition.md)| Relationship | [R5 EventDefinition](/docs/R5/Resources/EventDefinition.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | **`EventDefinition`**| _Equivalent_<br/>(26466/26467)| `EventDefinition`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(41197)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(41198)| `EventDefinition`
| | | | | **`EventDefinition.id`**| _Equivalent_<br/>(26468/26469)| `EventDefinition.id`| _Equivalent_<br/>(41199/41200)| `EventDefinition.id`
| | | | | **`EventDefinition.meta`**| _Equivalent_<br/>(26470/26471)| `EventDefinition.meta`| _Equivalent_<br/>(41201/41202)| `EventDefinition.meta`
| | | | | **`EventDefinition.implicitRules`**| _Equivalent_<br/>(26472/26473)| `EventDefinition.implicitRules`| _Equivalent_<br/>(41203/41204)| `EventDefinition.implicitRules`
| | | | | **`EventDefinition.language`**| _Equivalent_<br/>(26474/26475)| `EventDefinition.language`| _Equivalent_<br/>(41205/41206)| `EventDefinition.language`
| | | | | **`EventDefinition.text`**| _Equivalent_<br/>(26476/26477)| `EventDefinition.text`| _Equivalent_<br/>(41207/41208)| `EventDefinition.text`
| | | | | **`EventDefinition.contained`**| _Equivalent_<br/>(26478/26479)| `EventDefinition.contained`| _Equivalent_<br/>(41209/41210)| `EventDefinition.contained`
| | | | | **`EventDefinition.extension`**| _Equivalent_<br/>(26480/26481)| `EventDefinition.extension`| _Equivalent_<br/>(41211/41212)| `EventDefinition.extension`
| | | | | **`EventDefinition.modifierExtension`**| _Equivalent_<br/>(26482/26483)| `EventDefinition.modifierExtension`| _Equivalent_<br/>(41213/41214)| `EventDefinition.modifierExtension`
| | | | | **`EventDefinition.url`**| _Equivalent_<br/>(26484/26485)| `EventDefinition.url`| _Equivalent_<br/>(41215/41216)| `EventDefinition.url`
| | | | | **`EventDefinition.identifier`**| _Equivalent_<br/>(26486/26487)| `EventDefinition.identifier`| _Equivalent_<br/>(41217/41218)| `EventDefinition.identifier`
| | | | | **`EventDefinition.version`**| _Equivalent_<br/>(26488/26489)| `EventDefinition.version`| _Equivalent_<br/>(41219/41220)| `EventDefinition.version`
| | | | | **`EventDefinition.name`**| _Equivalent_<br/>(26490/26491)| `EventDefinition.name`| _Equivalent_<br/>(41221/41222)| `EventDefinition.name`
| | | | | **`EventDefinition.title`**| _Equivalent_<br/>(26492/26493)| `EventDefinition.title`| _Equivalent_<br/>(41223/41224)| `EventDefinition.title`
| | | | | **`EventDefinition.subtitle`**| _Equivalent_<br/>(26494/26495)| `EventDefinition.subtitle`| _Equivalent_<br/>(41225/41226)| `EventDefinition.subtitle`
| | | | | **`EventDefinition.status`**| _Equivalent_<br/>(26496/26497)| `EventDefinition.status`| _Equivalent_<br/>(41227/41228)| `EventDefinition.status`
| | | | | **`EventDefinition.experimental`**| _Equivalent_<br/>(26498/26499)| `EventDefinition.experimental`| _Equivalent_<br/>(41229/41230)| `EventDefinition.experimental`
| | | | | **`EventDefinition.subject[x]`**| _Equivalent_<br/>(26500/26501)| `EventDefinition.subject[x]`| _Equivalent_<br/>(41231/41232)| `EventDefinition.subject[x]`
| | | | | **`EventDefinition.date`**| _Equivalent_<br/>(26502/26503)| `EventDefinition.date`| _Equivalent_<br/>(41233/41234)| `EventDefinition.date`
| | | | | **`EventDefinition.publisher`**| _Equivalent_<br/>(26504/26505)| `EventDefinition.publisher`| _Equivalent_<br/>(41235/41236)| `EventDefinition.publisher`
| | | | | **`EventDefinition.contact`**| _Equivalent_<br/>(26506/26507)| `EventDefinition.contact`| _Equivalent_<br/>(41237/41238)| `EventDefinition.contact`
| | | | | **`EventDefinition.description`**| _Equivalent_<br/>(26508/26509)| `EventDefinition.description`| _Equivalent_<br/>(41239/41240)| `EventDefinition.description`
| | | | | **`EventDefinition.useContext`**| _Equivalent_<br/>(26510/26511)| `EventDefinition.useContext`| _Equivalent_<br/>(41241/41242)| `EventDefinition.useContext`
| | | | | **`EventDefinition.jurisdiction`**| _Equivalent_<br/>(26512/26513)| `EventDefinition.jurisdiction`| _Equivalent_<br/>(41243/41244)| `EventDefinition.jurisdiction`
| | | | | **`EventDefinition.purpose`**| _Equivalent_<br/>(26514/26515)| `EventDefinition.purpose`| _Equivalent_<br/>(41245/41246)| `EventDefinition.purpose`
| | | | | **`EventDefinition.usage`**| _Equivalent_<br/>(26516/26517)| `EventDefinition.usage`| _Equivalent_<br/>(41247/41248)| `EventDefinition.usage`
| | | | | **`EventDefinition.copyright`**| _Equivalent_<br/>(26518/26519)| `EventDefinition.copyright`| _Equivalent_<br/>(41249/41250)| `EventDefinition.copyright`
| | | | | **`EventDefinition.approvalDate`**| _Equivalent_<br/>(26520/26521)| `EventDefinition.approvalDate`| _Equivalent_<br/>(41251/41252)| `EventDefinition.approvalDate`
| | | | | **`EventDefinition.lastReviewDate`**| _Equivalent_<br/>(26522/26523)| `EventDefinition.lastReviewDate`| _Equivalent_<br/>(41253/41254)| `EventDefinition.lastReviewDate`
| | | | | **`EventDefinition.effectivePeriod`**| _Equivalent_<br/>(26524/26525)| `EventDefinition.effectivePeriod`| _Equivalent_<br/>(41255/41256)| `EventDefinition.effectivePeriod`
| | | | | **`EventDefinition.topic`**| _Equivalent_<br/>(26526/26527)| `EventDefinition.topic`| _Equivalent_<br/>(41257/41258)| `EventDefinition.topic`
| | | | | **`EventDefinition.author`**| _Equivalent_<br/>(26528/26529)| `EventDefinition.author`| _Equivalent_<br/>(41259/41260)| `EventDefinition.author`
| | | | | **`EventDefinition.editor`**| _Equivalent_<br/>(26530/26531)| `EventDefinition.editor`| _Equivalent_<br/>(41261/41262)| `EventDefinition.editor`
| | | | | **`EventDefinition.reviewer`**| _Equivalent_<br/>(26532/26533)| `EventDefinition.reviewer`| _Equivalent_<br/>(41263/41264)| `EventDefinition.reviewer`
| | | | | **`EventDefinition.endorser`**| _Equivalent_<br/>(26534/26535)| `EventDefinition.endorser`| _Equivalent_<br/>(41265/41266)| `EventDefinition.endorser`
| | | | | **`EventDefinition.relatedArtifact`**| _Equivalent_<br/>(26536/26537)| `EventDefinition.relatedArtifact`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(41267)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(41268)| `EventDefinition.relatedArtifact`
| | | | | **`EventDefinition.trigger`**| _Equivalent_<br/>(26538/26539)| `EventDefinition.trigger`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(41269)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(41270)| `EventDefinition.trigger`
| | | | | *37 of 37 elements used* | | *37 of 37 elements used* | | *37 of 39 elements used* <br/>remaining elements:<br/>`EventDefinition.copyrightLabel`, `EventDefinition.versionAlgorithm[x]`

