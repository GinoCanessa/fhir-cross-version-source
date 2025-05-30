Comparison of 
Generated at Monday, April 14, 2025 6:17:39 PM

### EvidenceVariable

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | EvidenceVariable |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/EvidenceVariable` |
| Version | 4.3.0 |
| Description | The EvidenceVariable resource describes an element that knowledge (Evidence) is about. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1692` |
| Database Snapshot Count | `55` |
| Database Differential Count | `38` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `EvidenceVariable` | `EvidenceVariable` | `EvidenceVariable` | EvidenceVariable | A definition of an exposure, outcome, or other variable | 0..* | EvidenceVariable |  |  |
| `EvidenceVariable.actual` | `EvidenceVariable.actual` | `actual` | EvidenceVariable.actual | Actual or conceptual | 0..1 | boolean |  |  |
| `EvidenceVariable.author` | `EvidenceVariable.author` | `author` | EvidenceVariable.author | Who authored the content | 0..* | ContactDetail |  |  |
| `EvidenceVariable.category` | `EvidenceVariable.category` | `category` | EvidenceVariable.category | A grouping for ordinal or polychotomous variables | 0..* | BackboneElement |  |  |
| `EvidenceVariable.category.extension` | `EvidenceVariable.category.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EvidenceVariable.category.id` | `EvidenceVariable.category.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `EvidenceVariable.category.modifierExtension` | `EvidenceVariable.category.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `EvidenceVariable.category.name` | `EvidenceVariable.category.name` | `name` | EvidenceVariable.category.name | Description of the grouping | 0..1 | string |  |  |
| `EvidenceVariable.category.value[x]` | `EvidenceVariable.category.value[x]` | `value[x]` | EvidenceVariable.category.value[x] | Definition of the grouping | 0..1 | CodeableConcept, Quantity, Range |  |  |
| `EvidenceVariable.characteristic` | `EvidenceVariable.characteristic` | `characteristic` | EvidenceVariable.characteristic | What defines the members of the evidence element | 0..* | BackboneElement |  |  |
| `EvidenceVariable.characteristic.definition[x]` | `EvidenceVariable.characteristic.definition[x]` | `definition[x]` | EvidenceVariable.characteristic.definition[x] | What code or expression defines members? | 1..1 | canonical(http://hl7.org/fhir/StructureDefinition/Resource), CodeableConcept, Expression, Reference(http://hl7.org/fhir/StructureDefinition/EvidenceVariable), Reference(http://hl7.org/fhir/StructureDefinition/Group) |  |  |
| `EvidenceVariable.characteristic.description` | `EvidenceVariable.characteristic.description` | `description` | EvidenceVariable.characteristic.description | Natural language description of the characteristic | 0..1 | string |  |  |
| `EvidenceVariable.characteristic.device` | `EvidenceVariable.characteristic.device` | `device` | EvidenceVariable.characteristic.device | Device used for determining characteristic | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/DeviceMetric) |  |  |
| `EvidenceVariable.characteristic.exclude` | `EvidenceVariable.characteristic.exclude` | `exclude` | EvidenceVariable.characteristic.exclude | Whether the characteristic includes or excludes members | 0..1 | boolean |  |  |
| `EvidenceVariable.characteristic.extension` | `EvidenceVariable.characteristic.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EvidenceVariable.characteristic.groupMeasure` | `EvidenceVariable.characteristic.groupMeasure` | `groupMeasure` | EvidenceVariable.characteristic.groupMeasure | mean \| median \| mean-of-mean \| mean-of-median \| median-of-mean \| median-of-median | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/group-measure|4.3.0` |
| `EvidenceVariable.characteristic.id` | `EvidenceVariable.characteristic.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `EvidenceVariable.characteristic.method` | `EvidenceVariable.characteristic.method` | `method` | EvidenceVariable.characteristic.method | Method used for describing characteristic | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/characteristic-method` |
| `EvidenceVariable.characteristic.modifierExtension` | `EvidenceVariable.characteristic.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `EvidenceVariable.characteristic.timeFromStart` | `EvidenceVariable.characteristic.timeFromStart` | `timeFromStart` | EvidenceVariable.characteristic.timeFromStart | Observation time from study start | 0..1 | BackboneElement |  |  |
| `EvidenceVariable.characteristic.timeFromStart.description` | `EvidenceVariable.characteristic.timeFromStart.description` | `description` | EvidenceVariable.characteristic.timeFromStart.description | Human readable description | 0..1 | string |  |  |
| `EvidenceVariable.characteristic.timeFromStart.extension` | `EvidenceVariable.characteristic.timeFromStart.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EvidenceVariable.characteristic.timeFromStart.id` | `EvidenceVariable.characteristic.timeFromStart.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `EvidenceVariable.characteristic.timeFromStart.modifierExtension` | `EvidenceVariable.characteristic.timeFromStart.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `EvidenceVariable.characteristic.timeFromStart.note` | `EvidenceVariable.characteristic.timeFromStart.note` | `note` | EvidenceVariable.characteristic.timeFromStart.note | Used for footnotes or explanatory notes | 0..* | Annotation |  |  |
| `EvidenceVariable.characteristic.timeFromStart.quantity` | `EvidenceVariable.characteristic.timeFromStart.quantity` | `quantity` | EvidenceVariable.characteristic.timeFromStart.quantity | Used to express the observation at a defined amount of time after the study start | 0..1 | Quantity |  |  |
| `EvidenceVariable.characteristic.timeFromStart.range` | `EvidenceVariable.characteristic.timeFromStart.range` | `range` | EvidenceVariable.characteristic.timeFromStart.range | Used to express the observation within a period after the study start | 0..1 | Range |  |  |
| `EvidenceVariable.characteristicCombination` | `EvidenceVariable.characteristicCombination` | `characteristicCombination` | EvidenceVariable.characteristicCombination | intersection \| union | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/characteristic-combination|4.3.0` |
| `EvidenceVariable.contact` | `EvidenceVariable.contact` | `contact` | EvidenceVariable.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `EvidenceVariable.contained` | `EvidenceVariable.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `EvidenceVariable.date` | `EvidenceVariable.date` | `date` | EvidenceVariable.date | Date last changed | 0..1 | dateTime |  |  |
| `EvidenceVariable.description` | `EvidenceVariable.description` | `description` | EvidenceVariable.description | Natural language description of the evidence variable | 0..1 | markdown |  |  |
| `EvidenceVariable.editor` | `EvidenceVariable.editor` | `editor` | EvidenceVariable.editor | Who edited the content | 0..* | ContactDetail |  |  |
| `EvidenceVariable.endorser` | `EvidenceVariable.endorser` | `endorser` | EvidenceVariable.endorser | Who endorsed the content | 0..* | ContactDetail |  |  |
| `EvidenceVariable.extension` | `EvidenceVariable.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EvidenceVariable.handling` | `EvidenceVariable.handling` | `handling` | EvidenceVariable.handling | continuous \| dichotomous \| ordinal \| polychotomous | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/variable-handling|4.3.0` |
| `EvidenceVariable.id` | `EvidenceVariable.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `EvidenceVariable.identifier` | `EvidenceVariable.identifier` | `identifier` | EvidenceVariable.identifier | Additional identifier for the evidence variable | 0..* | Identifier |  |  |
| `EvidenceVariable.implicitRules` | `EvidenceVariable.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `EvidenceVariable.language` | `EvidenceVariable.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `EvidenceVariable.meta` | `EvidenceVariable.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `EvidenceVariable.modifierExtension` | `EvidenceVariable.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `EvidenceVariable.name` | `EvidenceVariable.name` | `name` | EvidenceVariable.name | Name for this evidence variable (computer friendly) | 0..1 | string |  |  |
| `EvidenceVariable.note` | `EvidenceVariable.note` | `note` | EvidenceVariable.note | Used for footnotes or explanatory notes | 0..* | Annotation |  |  |
| `EvidenceVariable.publisher` | `EvidenceVariable.publisher` | `publisher` | EvidenceVariable.publisher | Name of the publisher (organization or individual) | 0..1 | string |  |  |
| `EvidenceVariable.relatedArtifact` | `EvidenceVariable.relatedArtifact` | `relatedArtifact` | EvidenceVariable.relatedArtifact | Additional documentation, citations, etc. | 0..* | RelatedArtifact |  |  |
| `EvidenceVariable.reviewer` | `EvidenceVariable.reviewer` | `reviewer` | EvidenceVariable.reviewer | Who reviewed the content | 0..* | ContactDetail |  |  |
| `EvidenceVariable.shortTitle` | `EvidenceVariable.shortTitle` | `shortTitle` | EvidenceVariable.shortTitle | Title for use in informal contexts | 0..1 | string |  |  |
| `EvidenceVariable.status` | `EvidenceVariable.status` | `status` | EvidenceVariable.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|4.3.0` |
| `EvidenceVariable.subtitle` | `EvidenceVariable.subtitle` | `subtitle` | EvidenceVariable.subtitle | Subordinate title of the EvidenceVariable | 0..1 | string |  |  |
| `EvidenceVariable.text` | `EvidenceVariable.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `EvidenceVariable.title` | `EvidenceVariable.title` | `title` | EvidenceVariable.title | Name for this evidence variable (human friendly) | 0..1 | string |  |  |
| `EvidenceVariable.url` | `EvidenceVariable.url` | `url` | EvidenceVariable.url | Canonical identifier for this evidence variable, represented as a URI (globally unique) | 0..1 | uri |  |  |
| `EvidenceVariable.useContext` | `EvidenceVariable.useContext` | `useContext` | EvidenceVariable.useContext | The context that the content is intended to support | 0..* | UsageContext |  |  |
| `EvidenceVariable.version` | `EvidenceVariable.version` | `version` | EvidenceVariable.version | Business version of the evidence variable | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [EvidenceVariable](/docs/R4/Resources/EvidenceVariable.md)<br/> `http://hl7.org/fhir/StructureDefinition/EvidenceVariable\|4.0.1` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1487`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1488`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [EvidenceVariable](/docs/R4B/Resources/EvidenceVariable.md)<br/> `http://hl7.org/fhir/StructureDefinition/EvidenceVariable\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `977`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1206`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [EvidenceVariable](/docs/R5/Resources/EvidenceVariable.md)<br/> `http://hl7.org/fhir/StructureDefinition/EvidenceVariable\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition EvidenceVariable from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | [R4 EvidenceVariable](/docs/R4/Resources/EvidenceVariable.md)| Relationship | R4B EvidenceVariable| Relationship | [R5 EvidenceVariable](/docs/R5/Resources/EvidenceVariable.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `EvidenceVariable`| _Equivalent_<br/>(26604/26605)| **`EvidenceVariable`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(41671)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(41672)| `EvidenceVariable`
| | | | | `EvidenceVariable.id`| _Equivalent_<br/>(26606/26607)| **`EvidenceVariable.id`**| _Equivalent_<br/>(41673/41674)| `EvidenceVariable.id`
| | | | | `EvidenceVariable.meta`| _Equivalent_<br/>(26608/26609)| **`EvidenceVariable.meta`**| _Equivalent_<br/>(41675/41676)| `EvidenceVariable.meta`
| | | | | `EvidenceVariable.implicitRules`| _Equivalent_<br/>(26610/26611)| **`EvidenceVariable.implicitRules`**| _Equivalent_<br/>(41677/41678)| `EvidenceVariable.implicitRules`
| | | | | `EvidenceVariable.language`| _Equivalent_<br/>(26612/26613)| **`EvidenceVariable.language`**| _Equivalent_<br/>(41679/41680)| `EvidenceVariable.language`
| | | | | `EvidenceVariable.text`| _Equivalent_<br/>(26614/26615)| **`EvidenceVariable.text`**| _Equivalent_<br/>(41681/41682)| `EvidenceVariable.text`
| | | | | `EvidenceVariable.contained`| _Equivalent_<br/>(26616/26617)| **`EvidenceVariable.contained`**| _Equivalent_<br/>(41683/41684)| `EvidenceVariable.contained`
| | | | | `EvidenceVariable.extension`| _Equivalent_<br/>(26618/26619)| **`EvidenceVariable.extension`**| _Equivalent_<br/>(41685/41686)| `EvidenceVariable.extension`
| | | | | `EvidenceVariable.modifierExtension`| _Equivalent_<br/>(26620/26621)| **`EvidenceVariable.modifierExtension`**| _Equivalent_<br/>(41687/41688)| `EvidenceVariable.modifierExtension`
| | | | | `EvidenceVariable.url`| _Equivalent_<br/>(26622/26623)| **`EvidenceVariable.url`**| _Equivalent_<br/>(41689/41690)| `EvidenceVariable.url`
| | | | | `EvidenceVariable.identifier`| _Equivalent_<br/>(26624/26625)| **`EvidenceVariable.identifier`**| _Equivalent_<br/>(41691/41692)| `EvidenceVariable.identifier`
| | | | | `EvidenceVariable.version`| _Equivalent_<br/>(26626/26627)| **`EvidenceVariable.version`**| _Equivalent_<br/>(41693/41694)| `EvidenceVariable.version`
| | | | | `EvidenceVariable.name`| _Equivalent_<br/>(26628/26629)| **`EvidenceVariable.name`**| _Equivalent_<br/>(41695/41696)| `EvidenceVariable.name`
| | | | | `EvidenceVariable.title`| _Equivalent_<br/>(26630/26631)| **`EvidenceVariable.title`**| _Equivalent_<br/>(41697/41698)| `EvidenceVariable.title`
| | | | | `EvidenceVariable.shortTitle`| _Equivalent_<br/>(26632/26633)| **`EvidenceVariable.shortTitle`**| _Equivalent_<br/>(41699/41700)| `EvidenceVariable.shortTitle`
| | | | | `EvidenceVariable.subtitle`| _Equivalent_<br/>(26634/26635)| **`EvidenceVariable.subtitle`**| | | 
| | | | | `EvidenceVariable.status`| _Equivalent_<br/>(26636/26637)| **`EvidenceVariable.status`**| _Equivalent_<br/>(41702/41703)| `EvidenceVariable.status`
| | | | | `EvidenceVariable.date`| _Equivalent_<br/>(26638/26639)| **`EvidenceVariable.date`**| _Equivalent_<br/>(41704/41705)| `EvidenceVariable.date`
| | | | | `EvidenceVariable.description`| _Equivalent_<br/>(26644/26645)| **`EvidenceVariable.description`**| _Equivalent_<br/>(41706/41707)| `EvidenceVariable.description`
| | | | | `EvidenceVariable.note`| _Equivalent_<br/>(26646/26647)| **`EvidenceVariable.note`**| _Equivalent_<br/>(41708/41709)| `EvidenceVariable.note`
| | | | | `EvidenceVariable.useContext`| _Equivalent_<br/>(26648/26649)| **`EvidenceVariable.useContext`**| _Equivalent_<br/>(41710/41711)| `EvidenceVariable.useContext`
| | | | | `EvidenceVariable.publisher`| _Equivalent_<br/>(26640/26641)| **`EvidenceVariable.publisher`**| _Equivalent_<br/>(41712/41713)| `EvidenceVariable.publisher`
| | | | | `EvidenceVariable.contact`| _Equivalent_<br/>(26642/26643)| **`EvidenceVariable.contact`**| _Equivalent_<br/>(41714/41715)| `EvidenceVariable.contact`
| | | | | `EvidenceVariable.author`| _Equivalent_<br/>(26656/26657)| **`EvidenceVariable.author`**| _Equivalent_<br/>(41716/41717)| `EvidenceVariable.author`
| | | | | `EvidenceVariable.editor`| _Equivalent_<br/>(26658/26659)| **`EvidenceVariable.editor`**| _Equivalent_<br/>(41718/41719)| `EvidenceVariable.editor`
| | | | | `EvidenceVariable.reviewer`| _Equivalent_<br/>(26660/26661)| **`EvidenceVariable.reviewer`**| _Equivalent_<br/>(41720/41721)| `EvidenceVariable.reviewer`
| | | | | `EvidenceVariable.endorser`| _Equivalent_<br/>(26662/26663)| **`EvidenceVariable.endorser`**| _Equivalent_<br/>(41722/41723)| `EvidenceVariable.endorser`
| | | | | `EvidenceVariable.relatedArtifact`| _Equivalent_<br/>(26664/26665)| **`EvidenceVariable.relatedArtifact`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(41724)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(41725)| `EvidenceVariable.relatedArtifact`
| | | | | | | **`EvidenceVariable.actual`**| _Equivalent_<br/>(41726/41727)| `EvidenceVariable.actual`
| | | | | | | **`EvidenceVariable.characteristicCombination`**| | | 
| | | | | `EvidenceVariable.characteristic`| →→→→ _Equivalent_ →→→→ <br/>(26667)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(26668)| **`EvidenceVariable.characteristic`**| _Equivalent_<br/>(41729/41730)| `EvidenceVariable.characteristic`
| | | | | `EvidenceVariable.characteristic.id`| _Equivalent_<br/>(26669/26670)| **`EvidenceVariable.characteristic.id`**| _Equivalent_<br/>(41731/41732)| `EvidenceVariable.characteristic.id`
| | | | | `EvidenceVariable.characteristic.extension`| _Equivalent_<br/>(26671/26672)| **`EvidenceVariable.characteristic.extension`**| _Equivalent_<br/>(41733/41734)| `EvidenceVariable.characteristic.extension`
| | | | | `EvidenceVariable.characteristic.modifierExtension`| _Equivalent_<br/>(26673/26674)| **`EvidenceVariable.characteristic.modifierExtension`**| _Equivalent_<br/>(41735/41736)| `EvidenceVariable.characteristic.modifierExtension`
| | | | | `EvidenceVariable.characteristic.description`| _Equivalent_<br/>(26675/26676)| **`EvidenceVariable.characteristic.description`**| _Equivalent_<br/>(41737/41738)| `EvidenceVariable.characteristic.description`
| | | | | `EvidenceVariable.characteristic.definition[x]`| →→→→ _RelatedTo_ →→→→ <br/>(26677)<hr/>←←←← _RelatedTo_ ←←←← <br/>(26678)| **`EvidenceVariable.characteristic.definition[x]`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1871)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2113)| `EvidenceVariable.characteristic.definitionReference`
| | | | | `EvidenceVariable.characteristic.definition[x]`| →→→→ _RelatedTo_ →→→→ <br/>(26677)<hr/>←←←← _RelatedTo_ ←←←← <br/>(26678)| **`EvidenceVariable.characteristic.definition[x]`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1872)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2114)| `EvidenceVariable.characteristic.definitionCanonical`
| | | | | `EvidenceVariable.characteristic.definition[x]`| →→→→ _RelatedTo_ →→→→ <br/>(26677)<hr/>←←←← _RelatedTo_ ←←←← <br/>(26678)| **`EvidenceVariable.characteristic.definition[x]`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1873)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2115)| `EvidenceVariable.characteristic.definitionCodeableConcept`
| | | | | `EvidenceVariable.characteristic.definition[x]`| →→→→ _RelatedTo_ →→→→ <br/>(26677)<hr/>←←←← _RelatedTo_ ←←←← <br/>(26678)| **`EvidenceVariable.characteristic.definition[x]`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1874)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2116)| `EvidenceVariable.characteristic.definitionExpression`
| | | | | | | **`EvidenceVariable.characteristic.method`**| | | 
| | | | | | | **`EvidenceVariable.characteristic.device`**| | | 
| | | | | `EvidenceVariable.characteristic.exclude`| _Equivalent_<br/>(26680/26681)| **`EvidenceVariable.characteristic.exclude`**| _Equivalent_<br/>(41741/41742)| `EvidenceVariable.characteristic.exclude`
| | | | | `EvidenceVariable.characteristic.timeFromStart`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(26683)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(26684)| **`EvidenceVariable.characteristic.timeFromStart`**| | | 
| | | | | | | **`EvidenceVariable.characteristic.timeFromStart.id`**| | | 
| | | | | | | **`EvidenceVariable.characteristic.timeFromStart.extension`**| | | 
| | | | | | | **`EvidenceVariable.characteristic.timeFromStart.modifierExtension`**| | | 
| | | | | | | **`EvidenceVariable.characteristic.timeFromStart.description`**| _Equivalent_<br/>(1875/2117)| `EvidenceVariable.characteristic.timeFromEvent.description`
| | | | | | | **`EvidenceVariable.characteristic.timeFromStart.quantity`**| _Equivalent_<br/>(1877/2119)| `EvidenceVariable.characteristic.timeFromEvent.quantity`
| | | | | | | **`EvidenceVariable.characteristic.timeFromStart.range`**| _Equivalent_<br/>(1878/2120)| `EvidenceVariable.characteristic.timeFromEvent.range`
| | | | | | | **`EvidenceVariable.characteristic.timeFromStart.note`**| _Equivalent_<br/>(1876/2118)| `EvidenceVariable.characteristic.timeFromEvent.note`
| | | | | `EvidenceVariable.characteristic.groupMeasure`| _Equivalent_<br/>(26685/26686)| **`EvidenceVariable.characteristic.groupMeasure`**| | | 
| | | | | | | **`EvidenceVariable.handling`**| _Equivalent_<br/>(41748/41749)| `EvidenceVariable.handling`
| | | | | | | **`EvidenceVariable.category`**| _Equivalent_<br/>(41750/41751)| `EvidenceVariable.category`
| | | | | | | **`EvidenceVariable.category.id`**| _Equivalent_<br/>(41752/41753)| `EvidenceVariable.category.id`
| | | | | | | **`EvidenceVariable.category.extension`**| _Equivalent_<br/>(41754/41755)| `EvidenceVariable.category.extension`
| | | | | | | **`EvidenceVariable.category.modifierExtension`**| _Equivalent_<br/>(41756/41757)| `EvidenceVariable.category.modifierExtension`
| | | | | | | **`EvidenceVariable.category.name`**| _Equivalent_<br/>(41758/41759)| `EvidenceVariable.category.name`
| | | | | | | **`EvidenceVariable.category.value[x]`**| _Equivalent_<br/>(41760/41761)| `EvidenceVariable.category.value[x]`
| | | | | *37 of 46 elements used* <br/>remaining elements:<br/>`EvidenceVariable.approvalDate`, `EvidenceVariable.characteristic.participantEffective[x]`, `EvidenceVariable.characteristic.usageContext`, `EvidenceVariable.copyright`, `EvidenceVariable.effectivePeriod`, `EvidenceVariable.jurisdiction`, `EvidenceVariable.lastReviewDate`, `EvidenceVariable.topic`, `EvidenceVariable.type`| | *55 of 55 elements used* | | *49 of 83 elements used* <br/>remaining elements:<br/>`EvidenceVariable.approvalDate`, `EvidenceVariable.characteristic.definitionByCombination`, `EvidenceVariable.characteristic.definitionByCombination.characteristic`, `EvidenceVariable.characteristic.definitionByCombination.code`, `EvidenceVariable.characteristic.definitionByCombination.extension`, `EvidenceVariable.characteristic.definitionByCombination.id`, `EvidenceVariable.characteristic.definitionByCombination.modifierExtension`, `EvidenceVariable.characteristic.definitionByCombination.threshold`, `EvidenceVariable.characteristic.definitionByTypeAndValue`, `EvidenceVariable.characteristic.definitionByTypeAndValue.device`, `EvidenceVariable.characteristic.definitionByTypeAndValue.extension`, `EvidenceVariable.characteristic.definitionByTypeAndValue.id`, `EvidenceVariable.characteristic.definitionByTypeAndValue.method`, `EvidenceVariable.characteristic.definitionByTypeAndValue.modifierExtension`, `EvidenceVariable.characteristic.definitionByTypeAndValue.offset`, `EvidenceVariable.characteristic.definitionByTypeAndValue.type`, `EvidenceVariable.characteristic.definitionByTypeAndValue.value[x]`, `EvidenceVariable.characteristic.definitionId`, `EvidenceVariable.characteristic.duration[x]`, `EvidenceVariable.characteristic.instances[x]`, `EvidenceVariable.characteristic.linkId`, `EvidenceVariable.characteristic.note`, `EvidenceVariable.characteristic.timeFromEvent`, `EvidenceVariable.characteristic.timeFromEvent.event[x]`, `EvidenceVariable.characteristic.timeFromEvent.extension`, `EvidenceVariable.characteristic.timeFromEvent.id`, `EvidenceVariable.characteristic.timeFromEvent.modifierExtension`, `EvidenceVariable.copyright`, `EvidenceVariable.copyrightLabel`, `EvidenceVariable.effectivePeriod`, `EvidenceVariable.experimental`, `EvidenceVariable.lastReviewDate`, `EvidenceVariable.purpose`, `EvidenceVariable.versionAlgorithm[x]`

