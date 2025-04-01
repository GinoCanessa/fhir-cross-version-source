Comparison of 
Generated at Tuesday, April 1, 2025 1:39:40 PM

### EvidenceVariable

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | EvidenceVariable |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/EvidenceVariable` |
| Version | 5.0.0 |
| Description | The EvidenceVariable resource describes an element that knowledge (Evidence) is about. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2307` |
| Database Snapshot Count | `83` |
| Database Differential Count | `60` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `EvidenceVariable` | `EvidenceVariable` | `EvidenceVariable` | EvidenceVariable | A definition of an exposure, outcome, or other variable | 0..* | EvidenceVariable |  |  |
| `EvidenceVariable.actual` | `EvidenceVariable.actual` | `actual` | EvidenceVariable.actual | Actual or conceptual | 0..1 | boolean |  |  |
| `EvidenceVariable.approvalDate` | `EvidenceVariable.approvalDate` | `approvalDate` | EvidenceVariable.approvalDate | When the resource was approved by publisher | 0..1 | date |  |  |
| `EvidenceVariable.author` | `EvidenceVariable.author` | `author` | EvidenceVariable.author | Who authored the content | 0..* | ContactDetail |  |  |
| `EvidenceVariable.category` | `EvidenceVariable.category` | `category` | EvidenceVariable.category | A grouping for ordinal or polychotomous variables | 0..* | BackboneElement |  |  |
| `EvidenceVariable.category.extension` | `EvidenceVariable.category.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EvidenceVariable.category.id` | `EvidenceVariable.category.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `EvidenceVariable.category.modifierExtension` | `EvidenceVariable.category.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `EvidenceVariable.category.name` | `EvidenceVariable.category.name` | `name` | EvidenceVariable.category.name | Description of the grouping | 0..1 | string |  |  |
| `EvidenceVariable.category.value[x]` | `EvidenceVariable.category.value[x]` | `value[x]` | EvidenceVariable.category.value[x] | Definition of the grouping | 0..1 | CodeableConcept, Quantity, Range |  |  |
| `EvidenceVariable.characteristic` | `EvidenceVariable.characteristic` | `characteristic` | EvidenceVariable.characteristic | A defining factor of the EvidenceVariable | 0..* | BackboneElement |  |  |
| `EvidenceVariable.characteristic.definitionByCombination` | `EvidenceVariable.characteristic.definitionByCombination` | `definitionByCombination` | EvidenceVariable.characteristic.definitionByCombination | Used to specify how two or more characteristics are combined | 0..1 | BackboneElement |  |  |
| `EvidenceVariable.characteristic.definitionByCombination.characteristic` | `EvidenceVariable.characteristic.definitionByCombination.characteristic` | `characteristic` | EvidenceVariable.characteristic.definitionByCombination.characteristic | A defining factor of the characteristic | 1..* | EvidenceVariable.characteristic |  |  |
| `EvidenceVariable.characteristic.definitionByCombination.code` | `EvidenceVariable.characteristic.definitionByCombination.code` | `code` | EvidenceVariable.characteristic.definitionByCombination.code | all-of \| any-of \| at-least \| at-most \| statistical \| net-effect \| dataset | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/characteristic-combination|5.0.0` |
| `EvidenceVariable.characteristic.definitionByCombination.extension` | `EvidenceVariable.characteristic.definitionByCombination.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EvidenceVariable.characteristic.definitionByCombination.id` | `EvidenceVariable.characteristic.definitionByCombination.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `EvidenceVariable.characteristic.definitionByCombination.modifierExtension` | `EvidenceVariable.characteristic.definitionByCombination.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `EvidenceVariable.characteristic.definitionByCombination.threshold` | `EvidenceVariable.characteristic.definitionByCombination.threshold` | `threshold` | EvidenceVariable.characteristic.definitionByCombination.threshold | Provides the value of "n" when "at-least" or "at-most" codes are used | 0..1 | positiveInt |  |  |
| `EvidenceVariable.characteristic.definitionByTypeAndValue` | `EvidenceVariable.characteristic.definitionByTypeAndValue` | `definitionByTypeAndValue` | EvidenceVariable.characteristic.definitionByTypeAndValue | Defines the characteristic using type and value | 0..1 | BackboneElement |  |  |
| `EvidenceVariable.characteristic.definitionByTypeAndValue.device` | `EvidenceVariable.characteristic.definitionByTypeAndValue.device` | `device` | EvidenceVariable.characteristic.definitionByTypeAndValue.device | Device used for determining characteristic | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/DeviceMetric) |  |  |
| `EvidenceVariable.characteristic.definitionByTypeAndValue.extension` | `EvidenceVariable.characteristic.definitionByTypeAndValue.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EvidenceVariable.characteristic.definitionByTypeAndValue.id` | `EvidenceVariable.characteristic.definitionByTypeAndValue.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `EvidenceVariable.characteristic.definitionByTypeAndValue.method` | `EvidenceVariable.characteristic.definitionByTypeAndValue.method` | `method` | EvidenceVariable.characteristic.definitionByTypeAndValue.method | Method for how the characteristic value was determined | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/definition-method` |
| `EvidenceVariable.characteristic.definitionByTypeAndValue.modifierExtension` | `EvidenceVariable.characteristic.definitionByTypeAndValue.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `EvidenceVariable.characteristic.definitionByTypeAndValue.offset` | `EvidenceVariable.characteristic.definitionByTypeAndValue.offset` | `offset` | EvidenceVariable.characteristic.definitionByTypeAndValue.offset | Reference point for valueQuantity or valueRange | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/characteristic-offset` |
| `EvidenceVariable.characteristic.definitionByTypeAndValue.type` | `EvidenceVariable.characteristic.definitionByTypeAndValue.type` | `type` | EvidenceVariable.characteristic.definitionByTypeAndValue.type | Expresses the type of characteristic | 1..1 | CodeableConcept | `Example` | `http://terminology.hl7.org/ValueSet/usage-context-type` |
| `EvidenceVariable.characteristic.definitionByTypeAndValue.value[x]` | `EvidenceVariable.characteristic.definitionByTypeAndValue.value[x]` | `value[x]` | EvidenceVariable.characteristic.definitionByTypeAndValue.value[x] | Defines the characteristic when coupled with characteristic.type | 1..1 | boolean, CodeableConcept, id, Quantity, Range, Reference |  |  |
| `EvidenceVariable.characteristic.definitionCanonical` | `EvidenceVariable.characteristic.definitionCanonical` | `definitionCanonical` | EvidenceVariable.characteristic.definitionCanonical | Defines the characteristic (without using type and value) by a Canonical | 0..1 | canonical(http://hl7.org/fhir/StructureDefinition/Evidence), canonical(http://hl7.org/fhir/StructureDefinition/EvidenceVariable) |  |  |
| `EvidenceVariable.characteristic.definitionCodeableConcept` | `EvidenceVariable.characteristic.definitionCodeableConcept` | `definitionCodeableConcept` | EvidenceVariable.characteristic.definitionCodeableConcept | Defines the characteristic (without using type and value) by a CodeableConcept | 0..1 | CodeableConcept |  |  |
| `EvidenceVariable.characteristic.definitionExpression` | `EvidenceVariable.characteristic.definitionExpression` | `definitionExpression` | EvidenceVariable.characteristic.definitionExpression | Defines the characteristic (without using type and value) by an expression | 0..1 | Expression |  |  |
| `EvidenceVariable.characteristic.definitionId` | `EvidenceVariable.characteristic.definitionId` | `definitionId` | EvidenceVariable.characteristic.definitionId | Defines the characteristic (without using type and value) by an id | 0..1 | id |  |  |
| `EvidenceVariable.characteristic.definitionReference` | `EvidenceVariable.characteristic.definitionReference` | `definitionReference` | EvidenceVariable.characteristic.definitionReference | Defines the characteristic (without using type and value) by a Reference | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Evidence), Reference(http://hl7.org/fhir/StructureDefinition/EvidenceVariable), Reference(http://hl7.org/fhir/StructureDefinition/Group) |  |  |
| `EvidenceVariable.characteristic.description` | `EvidenceVariable.characteristic.description` | `description` | EvidenceVariable.characteristic.description | Natural language description of the characteristic | 0..1 | markdown |  |  |
| `EvidenceVariable.characteristic.duration[x]` | `EvidenceVariable.characteristic.duration[x]` | `duration[x]` | EvidenceVariable.characteristic.duration[x] | Length of time in which the characteristic is met | 0..1 | Quantity, Range |  |  |
| `EvidenceVariable.characteristic.exclude` | `EvidenceVariable.characteristic.exclude` | `exclude` | EvidenceVariable.characteristic.exclude | Whether the characteristic is an inclusion criterion or exclusion criterion | 0..1 | boolean |  |  |
| `EvidenceVariable.characteristic.extension` | `EvidenceVariable.characteristic.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EvidenceVariable.characteristic.id` | `EvidenceVariable.characteristic.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `EvidenceVariable.characteristic.instances[x]` | `EvidenceVariable.characteristic.instances[x]` | `instances[x]` | EvidenceVariable.characteristic.instances[x] | Number of occurrences meeting the characteristic | 0..1 | Quantity, Range |  |  |
| `EvidenceVariable.characteristic.linkId` | `EvidenceVariable.characteristic.linkId` | `linkId` | EvidenceVariable.characteristic.linkId | Label for internal linking | 0..1 | id |  |  |
| `EvidenceVariable.characteristic.modifierExtension` | `EvidenceVariable.characteristic.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `EvidenceVariable.characteristic.note` | `EvidenceVariable.characteristic.note` | `note` | EvidenceVariable.characteristic.note | Used for footnotes or explanatory notes | 0..* | Annotation |  |  |
| `EvidenceVariable.characteristic.timeFromEvent` | `EvidenceVariable.characteristic.timeFromEvent` | `timeFromEvent` | EvidenceVariable.characteristic.timeFromEvent | Timing in which the characteristic is determined | 0..* | BackboneElement |  |  |
| `EvidenceVariable.characteristic.timeFromEvent.description` | `EvidenceVariable.characteristic.timeFromEvent.description` | `description` | EvidenceVariable.characteristic.timeFromEvent.description | Human readable description | 0..1 | markdown |  |  |
| `EvidenceVariable.characteristic.timeFromEvent.event[x]` | `EvidenceVariable.characteristic.timeFromEvent.event[x]` | `event[x]` | EvidenceVariable.characteristic.timeFromEvent.event[x] | The event used as a base point (reference point) in time | 0..1 | CodeableConcept, dateTime, id, Reference | `Example` | `http://hl7.org/fhir/ValueSet/evidence-variable-event` |
| `EvidenceVariable.characteristic.timeFromEvent.extension` | `EvidenceVariable.characteristic.timeFromEvent.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EvidenceVariable.characteristic.timeFromEvent.id` | `EvidenceVariable.characteristic.timeFromEvent.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `EvidenceVariable.characteristic.timeFromEvent.modifierExtension` | `EvidenceVariable.characteristic.timeFromEvent.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `EvidenceVariable.characteristic.timeFromEvent.note` | `EvidenceVariable.characteristic.timeFromEvent.note` | `note` | EvidenceVariable.characteristic.timeFromEvent.note | Used for footnotes or explanatory notes | 0..* | Annotation |  |  |
| `EvidenceVariable.characteristic.timeFromEvent.quantity` | `EvidenceVariable.characteristic.timeFromEvent.quantity` | `quantity` | EvidenceVariable.characteristic.timeFromEvent.quantity | Used to express the observation at a defined amount of time before or after the event | 0..1 | Quantity |  |  |
| `EvidenceVariable.characteristic.timeFromEvent.range` | `EvidenceVariable.characteristic.timeFromEvent.range` | `range` | EvidenceVariable.characteristic.timeFromEvent.range | Used to express the observation within a period before and/or after the event | 0..1 | Range |  |  |
| `EvidenceVariable.contact` | `EvidenceVariable.contact` | `contact` | EvidenceVariable.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `EvidenceVariable.contained` | `EvidenceVariable.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `EvidenceVariable.copyright` | `EvidenceVariable.copyright` | `copyright` | EvidenceVariable.copyright | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `EvidenceVariable.copyrightLabel` | `EvidenceVariable.copyrightLabel` | `copyrightLabel` | EvidenceVariable.copyrightLabel | Copyright holder and year(s) | 0..1 | string |  |  |
| `EvidenceVariable.date` | `EvidenceVariable.date` | `date` | EvidenceVariable.date | Date last changed | 0..1 | dateTime |  |  |
| `EvidenceVariable.description` | `EvidenceVariable.description` | `description` | EvidenceVariable.description | Natural language description of the evidence variable | 0..1 | markdown |  |  |
| `EvidenceVariable.editor` | `EvidenceVariable.editor` | `editor` | EvidenceVariable.editor | Who edited the content | 0..* | ContactDetail |  |  |
| `EvidenceVariable.effectivePeriod` | `EvidenceVariable.effectivePeriod` | `effectivePeriod` | EvidenceVariable.effectivePeriod | When the resource is expected to be used | 0..1 | Period |  |  |
| `EvidenceVariable.endorser` | `EvidenceVariable.endorser` | `endorser` | EvidenceVariable.endorser | Who endorsed the content | 0..* | ContactDetail |  |  |
| `EvidenceVariable.experimental` | `EvidenceVariable.experimental` | `experimental` | EvidenceVariable.experimental | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `EvidenceVariable.extension` | `EvidenceVariable.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EvidenceVariable.handling` | `EvidenceVariable.handling` | `handling` | EvidenceVariable.handling | continuous \| dichotomous \| ordinal \| polychotomous | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/variable-handling|5.0.0` |
| `EvidenceVariable.id` | `EvidenceVariable.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `EvidenceVariable.identifier` | `EvidenceVariable.identifier` | `identifier` | EvidenceVariable.identifier | Additional identifier for the evidence variable | 0..* | Identifier |  |  |
| `EvidenceVariable.implicitRules` | `EvidenceVariable.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `EvidenceVariable.language` | `EvidenceVariable.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `EvidenceVariable.lastReviewDate` | `EvidenceVariable.lastReviewDate` | `lastReviewDate` | EvidenceVariable.lastReviewDate | When the resource was last reviewed by the publisher | 0..1 | date |  |  |
| `EvidenceVariable.meta` | `EvidenceVariable.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `EvidenceVariable.modifierExtension` | `EvidenceVariable.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `EvidenceVariable.name` | `EvidenceVariable.name` | `name` | EvidenceVariable.name | Name for this evidence variable (computer friendly) | 0..1 | string |  |  |
| `EvidenceVariable.note` | `EvidenceVariable.note` | `note` | EvidenceVariable.note | Used for footnotes or explanatory notes | 0..* | Annotation |  |  |
| `EvidenceVariable.publisher` | `EvidenceVariable.publisher` | `publisher` | EvidenceVariable.publisher | Name of the publisher/steward (organization or individual) | 0..1 | string |  |  |
| `EvidenceVariable.purpose` | `EvidenceVariable.purpose` | `purpose` | EvidenceVariable.purpose | Why this EvidenceVariable is defined | 0..1 | markdown |  |  |
| `EvidenceVariable.relatedArtifact` | `EvidenceVariable.relatedArtifact` | `relatedArtifact` | EvidenceVariable.relatedArtifact | Additional documentation, citations, etc | 0..* | RelatedArtifact |  |  |
| `EvidenceVariable.reviewer` | `EvidenceVariable.reviewer` | `reviewer` | EvidenceVariable.reviewer | Who reviewed the content | 0..* | ContactDetail |  |  |
| `EvidenceVariable.shortTitle` | `EvidenceVariable.shortTitle` | `shortTitle` | EvidenceVariable.shortTitle | Title for use in informal contexts | 0..1 | string |  |  |
| `EvidenceVariable.status` | `EvidenceVariable.status` | `status` | EvidenceVariable.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|5.0.0` |
| `EvidenceVariable.text` | `EvidenceVariable.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `EvidenceVariable.title` | `EvidenceVariable.title` | `title` | EvidenceVariable.title | Name for this evidence variable (human friendly) | 0..1 | string |  |  |
| `EvidenceVariable.url` | `EvidenceVariable.url` | `url` | EvidenceVariable.url | Canonical identifier for this evidence variable, represented as a URI (globally unique) | 0..1 | uri |  |  |
| `EvidenceVariable.useContext` | `EvidenceVariable.useContext` | `useContext` | EvidenceVariable.useContext | The context that the content is intended to support | 0..* | UsageContext |  |  |
| `EvidenceVariable.version` | `EvidenceVariable.version` | `version` | EvidenceVariable.version | Business version of the evidence variable | 0..1 | string |  |  |
| `EvidenceVariable.versionAlgorithm[x]` | `EvidenceVariable.versionAlgorithm[x]` | `versionAlgorithm[x]` | EvidenceVariable.versionAlgorithm[x] | How to compare versions | 0..1 | Coding, string | `Extensible` | `http://hl7.org/fhir/ValueSet/version-algorithm` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [EvidenceVariable](/docs/R4/Resources/EvidenceVariable.md)<br/> `http://hl7.org/fhir/StructureDefinition/EvidenceVariable\|4.0.1` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1487`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1488`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EvidenceVariable](/docs/R4B/Resources/EvidenceVariable.md)<br/> `http://hl7.org/fhir/StructureDefinition/EvidenceVariable\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `977`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1206`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EvidenceVariable](/docs/R5/Resources/EvidenceVariable.md)<br/> `http://hl7.org/fhir/StructureDefinition/EvidenceVariable\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition EvidenceVariable from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | [R4 EvidenceVariable](/docs/R4/Resources/EvidenceVariable.md)| Relationship | [R4B EvidenceVariable](/docs/R4B/Resources/EvidenceVariable.md)| Relationship | R5 EvidenceVariable
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `EvidenceVariable`| _Equivalent_<br/>(26604/26605)| `EvidenceVariable`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(41671)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(41672)| **`EvidenceVariable`**
| | | | | `EvidenceVariable.id`| _Equivalent_<br/>(26606/26607)| `EvidenceVariable.id`| _Equivalent_<br/>(41673/41674)| **`EvidenceVariable.id`**
| | | | | `EvidenceVariable.meta`| _Equivalent_<br/>(26608/26609)| `EvidenceVariable.meta`| _Equivalent_<br/>(41675/41676)| **`EvidenceVariable.meta`**
| | | | | `EvidenceVariable.implicitRules`| _Equivalent_<br/>(26610/26611)| `EvidenceVariable.implicitRules`| _Equivalent_<br/>(41677/41678)| **`EvidenceVariable.implicitRules`**
| | | | | `EvidenceVariable.language`| _Equivalent_<br/>(26612/26613)| `EvidenceVariable.language`| _Equivalent_<br/>(41679/41680)| **`EvidenceVariable.language`**
| | | | | `EvidenceVariable.text`| _Equivalent_<br/>(26614/26615)| `EvidenceVariable.text`| _Equivalent_<br/>(41681/41682)| **`EvidenceVariable.text`**
| | | | | `EvidenceVariable.contained`| _Equivalent_<br/>(26616/26617)| `EvidenceVariable.contained`| _Equivalent_<br/>(41683/41684)| **`EvidenceVariable.contained`**
| | | | | `EvidenceVariable.extension`| _Equivalent_<br/>(26618/26619)| `EvidenceVariable.extension`| _Equivalent_<br/>(41685/41686)| **`EvidenceVariable.extension`**
| | | | | `EvidenceVariable.modifierExtension`| _Equivalent_<br/>(26620/26621)| `EvidenceVariable.modifierExtension`| _Equivalent_<br/>(41687/41688)| **`EvidenceVariable.modifierExtension`**
| | | | | `EvidenceVariable.url`| _Equivalent_<br/>(26622/26623)| `EvidenceVariable.url`| _Equivalent_<br/>(41689/41690)| **`EvidenceVariable.url`**
| | | | | `EvidenceVariable.identifier`| _Equivalent_<br/>(26624/26625)| `EvidenceVariable.identifier`| _Equivalent_<br/>(41691/41692)| **`EvidenceVariable.identifier`**
| | | | | `EvidenceVariable.version`| _Equivalent_<br/>(26626/26627)| `EvidenceVariable.version`| _Equivalent_<br/>(41693/41694)| **`EvidenceVariable.version`**
| | | | | | | | | **`EvidenceVariable.versionAlgorithm[x]`**
| | | | | `EvidenceVariable.name`| _Equivalent_<br/>(26628/26629)| `EvidenceVariable.name`| _Equivalent_<br/>(41695/41696)| **`EvidenceVariable.name`**
| | | | | `EvidenceVariable.title`| _Equivalent_<br/>(26630/26631)| `EvidenceVariable.title`| _Equivalent_<br/>(41697/41698)| **`EvidenceVariable.title`**
| | | | | `EvidenceVariable.shortTitle`| _Equivalent_<br/>(26632/26633)| `EvidenceVariable.shortTitle`| _Equivalent_<br/>(41699/41700)| **`EvidenceVariable.shortTitle`**
| | | | | `EvidenceVariable.status`| _Equivalent_<br/>(26636/26637)| `EvidenceVariable.status`| _Equivalent_<br/>(41702/41703)| **`EvidenceVariable.status`**
| | | | | | | | | **`EvidenceVariable.experimental`**
| | | | | `EvidenceVariable.date`| _Equivalent_<br/>(26638/26639)| `EvidenceVariable.date`| _Equivalent_<br/>(41704/41705)| **`EvidenceVariable.date`**
| | | | | `EvidenceVariable.publisher`| _Equivalent_<br/>(26640/26641)| `EvidenceVariable.publisher`| _Equivalent_<br/>(41712/41713)| **`EvidenceVariable.publisher`**
| | | | | `EvidenceVariable.contact`| _Equivalent_<br/>(26642/26643)| `EvidenceVariable.contact`| _Equivalent_<br/>(41714/41715)| **`EvidenceVariable.contact`**
| | | | | `EvidenceVariable.description`| _Equivalent_<br/>(26644/26645)| `EvidenceVariable.description`| _Equivalent_<br/>(41706/41707)| **`EvidenceVariable.description`**
| | | | | `EvidenceVariable.note`| _Equivalent_<br/>(26646/26647)| `EvidenceVariable.note`| _Equivalent_<br/>(41708/41709)| **`EvidenceVariable.note`**
| | | | | `EvidenceVariable.useContext`| _Equivalent_<br/>(26648/26649)| `EvidenceVariable.useContext`| _Equivalent_<br/>(41710/41711)| **`EvidenceVariable.useContext`**
| | | | | | | | | **`EvidenceVariable.purpose`**
| | | | | | | | | **`EvidenceVariable.copyright`**
| | | | | | | | | **`EvidenceVariable.copyrightLabel`**
| | | | | | | | | **`EvidenceVariable.approvalDate`**
| | | | | | | | | **`EvidenceVariable.lastReviewDate`**
| | | | | | | | | **`EvidenceVariable.effectivePeriod`**
| | | | | `EvidenceVariable.author`| _Equivalent_<br/>(26656/26657)| `EvidenceVariable.author`| _Equivalent_<br/>(41716/41717)| **`EvidenceVariable.author`**
| | | | | `EvidenceVariable.editor`| _Equivalent_<br/>(26658/26659)| `EvidenceVariable.editor`| _Equivalent_<br/>(41718/41719)| **`EvidenceVariable.editor`**
| | | | | `EvidenceVariable.reviewer`| _Equivalent_<br/>(26660/26661)| `EvidenceVariable.reviewer`| _Equivalent_<br/>(41720/41721)| **`EvidenceVariable.reviewer`**
| | | | | `EvidenceVariable.endorser`| _Equivalent_<br/>(26662/26663)| `EvidenceVariable.endorser`| _Equivalent_<br/>(41722/41723)| **`EvidenceVariable.endorser`**
| | | | | `EvidenceVariable.relatedArtifact`| _Equivalent_<br/>(26664/26665)| `EvidenceVariable.relatedArtifact`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(41724)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(41725)| **`EvidenceVariable.relatedArtifact`**
| | | | | | | `EvidenceVariable.actual`| _Equivalent_<br/>(41726/41727)| **`EvidenceVariable.actual`**
| | | | | `EvidenceVariable.characteristic`| →→→→ _Equivalent_ →→→→ <br/>(26667)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(26668)| `EvidenceVariable.characteristic`| _Equivalent_<br/>(41729/41730)| **`EvidenceVariable.characteristic`**
| | | | | `EvidenceVariable.characteristic.id`| _Equivalent_<br/>(26669/26670)| `EvidenceVariable.characteristic.id`| _Equivalent_<br/>(41731/41732)| **`EvidenceVariable.characteristic.id`**
| | | | | `EvidenceVariable.characteristic.extension`| _Equivalent_<br/>(26671/26672)| `EvidenceVariable.characteristic.extension`| _Equivalent_<br/>(41733/41734)| **`EvidenceVariable.characteristic.extension`**
| | | | | `EvidenceVariable.characteristic.modifierExtension`| _Equivalent_<br/>(26673/26674)| `EvidenceVariable.characteristic.modifierExtension`| _Equivalent_<br/>(41735/41736)| **`EvidenceVariable.characteristic.modifierExtension`**
| | | | | | | | | **`EvidenceVariable.characteristic.linkId`**
| | | | | `EvidenceVariable.characteristic.description`| _Equivalent_<br/>(26675/26676)| `EvidenceVariable.characteristic.description`| _Equivalent_<br/>(41737/41738)| **`EvidenceVariable.characteristic.description`**
| | | | | | | | | **`EvidenceVariable.characteristic.note`**
| | | | | `EvidenceVariable.characteristic.exclude`| _Equivalent_<br/>(26680/26681)| `EvidenceVariable.characteristic.exclude`| _Equivalent_<br/>(41741/41742)| **`EvidenceVariable.characteristic.exclude`**
| | | | | `EvidenceVariable.characteristic.definition[x]`| →→→→ _RelatedTo_ →→→→ <br/>(26677)<hr/>←←←← _RelatedTo_ ←←←← <br/>(26678)| `EvidenceVariable.characteristic.definition[x]`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1871)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2113)| **`EvidenceVariable.characteristic.definitionReference`**
| | | | | `EvidenceVariable.characteristic.definition[x]`| →→→→ _RelatedTo_ →→→→ <br/>(26677)<hr/>←←←← _RelatedTo_ ←←←← <br/>(26678)| `EvidenceVariable.characteristic.definition[x]`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1872)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2114)| **`EvidenceVariable.characteristic.definitionCanonical`**
| | | | | `EvidenceVariable.characteristic.definition[x]`| →→→→ _RelatedTo_ →→→→ <br/>(26677)<hr/>←←←← _RelatedTo_ ←←←← <br/>(26678)| `EvidenceVariable.characteristic.definition[x]`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1873)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2115)| **`EvidenceVariable.characteristic.definitionCodeableConcept`**
| | | | | `EvidenceVariable.characteristic.definition[x]`| →→→→ _RelatedTo_ →→→→ <br/>(26677)<hr/>←←←← _RelatedTo_ ←←←← <br/>(26678)| `EvidenceVariable.characteristic.definition[x]`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1874)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2116)| **`EvidenceVariable.characteristic.definitionExpression`**
| | | | | | | | | **`EvidenceVariable.characteristic.definitionId`**
| | | | | | | | | **`EvidenceVariable.characteristic.definitionByTypeAndValue`**
| | | | | | | | | **`EvidenceVariable.characteristic.definitionByTypeAndValue.id`**
| | | | | | | | | **`EvidenceVariable.characteristic.definitionByTypeAndValue.extension`**
| | | | | | | | | **`EvidenceVariable.characteristic.definitionByTypeAndValue.modifierExtension`**
| | | | | | | | | **`EvidenceVariable.characteristic.definitionByTypeAndValue.type`**
| | | | | | | | | **`EvidenceVariable.characteristic.definitionByTypeAndValue.method`**
| | | | | | | | | **`EvidenceVariable.characteristic.definitionByTypeAndValue.device`**
| | | | | | | | | **`EvidenceVariable.characteristic.definitionByTypeAndValue.value[x]`**
| | | | | | | | | **`EvidenceVariable.characteristic.definitionByTypeAndValue.offset`**
| | | | | | | | | **`EvidenceVariable.characteristic.definitionByCombination`**
| | | | | | | | | **`EvidenceVariable.characteristic.definitionByCombination.id`**
| | | | | | | | | **`EvidenceVariable.characteristic.definitionByCombination.extension`**
| | | | | | | | | **`EvidenceVariable.characteristic.definitionByCombination.modifierExtension`**
| | | | | | | | | **`EvidenceVariable.characteristic.definitionByCombination.code`**
| | | | | | | | | **`EvidenceVariable.characteristic.definitionByCombination.threshold`**
| | | | | | | | | **`EvidenceVariable.characteristic.definitionByCombination.characteristic`**
| | | | | | | | | **`EvidenceVariable.characteristic.instances[x]`**
| | | | | | | | | **`EvidenceVariable.characteristic.duration[x]`**
| | | | | | | | | **`EvidenceVariable.characteristic.timeFromEvent`**
| | | | | | | | | **`EvidenceVariable.characteristic.timeFromEvent.id`**
| | | | | | | | | **`EvidenceVariable.characteristic.timeFromEvent.extension`**
| | | | | | | | | **`EvidenceVariable.characteristic.timeFromEvent.modifierExtension`**
| | | | | | | `EvidenceVariable.characteristic.timeFromStart.description`| _Equivalent_<br/>(1875/2117)| **`EvidenceVariable.characteristic.timeFromEvent.description`**
| | | | | | | `EvidenceVariable.characteristic.timeFromStart.note`| _Equivalent_<br/>(1876/2118)| **`EvidenceVariable.characteristic.timeFromEvent.note`**
| | | | | | | | | **`EvidenceVariable.characteristic.timeFromEvent.event[x]`**
| | | | | | | `EvidenceVariable.characteristic.timeFromStart.quantity`| _Equivalent_<br/>(1877/2119)| **`EvidenceVariable.characteristic.timeFromEvent.quantity`**
| | | | | | | `EvidenceVariable.characteristic.timeFromStart.range`| _Equivalent_<br/>(1878/2120)| **`EvidenceVariable.characteristic.timeFromEvent.range`**
| | | | | | | `EvidenceVariable.handling`| _Equivalent_<br/>(41748/41749)| **`EvidenceVariable.handling`**
| | | | | | | `EvidenceVariable.category`| _Equivalent_<br/>(41750/41751)| **`EvidenceVariable.category`**
| | | | | | | `EvidenceVariable.category.id`| _Equivalent_<br/>(41752/41753)| **`EvidenceVariable.category.id`**
| | | | | | | `EvidenceVariable.category.extension`| _Equivalent_<br/>(41754/41755)| **`EvidenceVariable.category.extension`**
| | | | | | | `EvidenceVariable.category.modifierExtension`| _Equivalent_<br/>(41756/41757)| **`EvidenceVariable.category.modifierExtension`**
| | | | | | | `EvidenceVariable.category.name`| _Equivalent_<br/>(41758/41759)| **`EvidenceVariable.category.name`**
| | | | | | | `EvidenceVariable.category.value[x]`| _Equivalent_<br/>(41760/41761)| **`EvidenceVariable.category.value[x]`**
| | | | | *34 of 46 elements used* | | *46 of 55 elements used* | | *83 of 83 elements used* 

