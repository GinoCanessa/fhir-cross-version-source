Comparison of 
Generated at Monday, April 14, 2025 6:17:22 PM

### Library

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | Library |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Library` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for Library Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `535` |
| Database Snapshot Count | `35` |
| Database Differential Count | `27` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Library` | `Library` | `Library` | Library | Represents a library of quality improvement components | 0..* | Library |  |  |
| `Library.approvalDate` | `Library.approvalDate` | `approvalDate` |  | When the library was approved by publisher | 0..1 | date |  |  |
| `Library.contact` | `Library.contact` | `contact` |  | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `Library.contained` | `Library.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Library.content` | `Library.content` | `content` |  | Contents of the library, either embedded or referenced | 0..* | Attachment |  |  |
| `Library.contributor` | `Library.contributor` | `contributor` |  | A content contributor | 0..* | Contributor |  |  |
| `Library.copyright` | `Library.copyright` | `copyright` |  | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `Library.dataRequirement` | `Library.dataRequirement` | `dataRequirement` |  | What data is referenced by this library | 0..* | DataRequirement |  |  |
| `Library.date` | `Library.date` | `date` |  | Date this was last changed | 0..1 | dateTime |  |  |
| `Library.description` | `Library.description` | `description` |  | Natural language description of the library | 0..1 | markdown |  |  |
| `Library.effectivePeriod` | `Library.effectivePeriod` | `effectivePeriod` |  | When the library is expected to be used | 0..1 | Period |  |  |
| `Library.experimental` | `Library.experimental` | `experimental` |  | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `Library.extension` | `Library.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Library.id` | `Library.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Library.identifier` | `Library.identifier` | `identifier` |  | Additional identifier for the library | 0..* | Identifier |  |  |
| `Library.implicitRules` | `Library.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Library.jurisdiction` | `Library.jurisdiction` | `jurisdiction` |  | Intended jurisdiction for library (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `Library.language` | `Library.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `Library.lastReviewDate` | `Library.lastReviewDate` | `lastReviewDate` |  | When the library was last reviewed | 0..1 | date |  |  |
| `Library.meta` | `Library.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Library.modifierExtension` | `Library.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Library.name` | `Library.name` | `name` |  | Name for this library (computer friendly) | 0..1 | string |  |  |
| `Library.parameter` | `Library.parameter` | `parameter` |  | Parameters defined by the library | 0..* | ParameterDefinition |  |  |
| `Library.publisher` | `Library.publisher` | `publisher` |  | Name of the publisher (organization or individual) | 0..1 | string |  |  |
| `Library.purpose` | `Library.purpose` | `purpose` |  | Why this library is defined | 0..1 | markdown |  |  |
| `Library.relatedArtifact` | `Library.relatedArtifact` | `relatedArtifact` |  | Additional documentation, citations, etc. | 0..* | RelatedArtifact |  |  |
| `Library.status` | `Library.status` | `status` |  | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status` |
| `Library.text` | `Library.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Library.title` | `Library.title` | `title` |  | Name for this library (human friendly) | 0..1 | string |  |  |
| `Library.topic` | `Library.topic` | `topic` |  | E.g. Education, Treatment, Assessment, etc | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/definition-topic` |
| `Library.type` | `Library.type` | `type` |  | logic-library \| model-definition \| asset-collection \| module-definition | 1..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/library-type` |
| `Library.url` | `Library.url` | `url` |  | Logical URI to reference this library (globally unique) | 0..1 | uri |  |  |
| `Library.usage` | `Library.usage` | `usage` |  | Describes the clinical usage of the library | 0..1 | string |  |  |
| `Library.useContext` | `Library.useContext` | `useContext` |  | Context the content is intended to support | 0..* | UsageContext |  |  |
| `Library.version` | `Library.version` | `version` |  | Business version of the library | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [Library](/docs/R3/Resources/Library.md)<br/> `http://hl7.org/fhir/StructureDefinition/Library\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `472`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `666`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Library](/docs/R4/Resources/Library.md)<br/> `http://hl7.org/fhir/StructureDefinition/Library\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1521`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1522`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Library](/docs/R4B/Resources/Library.md)<br/> `http://hl7.org/fhir/StructureDefinition/Library\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `995`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1224`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Library](/docs/R5/Resources/Library.md)<br/> `http://hl7.org/fhir/StructureDefinition/Library\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Library from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | R3 Library| Relationship | [R4 Library](/docs/R4/Resources/Library.md)| Relationship | [R4B Library](/docs/R4B/Resources/Library.md)| Relationship | [R5 Library](/docs/R5/Resources/Library.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | **`Library`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15177)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15178)| `Library`| _Equivalent_<br/>(28803/28804)| `Library`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(43674)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(43675)| `Library`
| | | **`Library.id`**| _Equivalent_<br/>(15179/15180)| `Library.id`| _Equivalent_<br/>(28805/28806)| `Library.id`| _Equivalent_<br/>(43676/43677)| `Library.id`
| | | **`Library.meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15181)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15182)| `Library.meta`| _Equivalent_<br/>(28807/28808)| `Library.meta`| _Equivalent_<br/>(43678/43679)| `Library.meta`
| | | **`Library.implicitRules`**| _Equivalent_<br/>(15183/15184)| `Library.implicitRules`| _Equivalent_<br/>(28809/28810)| `Library.implicitRules`| _Equivalent_<br/>(43680/43681)| `Library.implicitRules`
| | | **`Library.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15185)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(15186)| `Library.language`| _Equivalent_<br/>(28811/28812)| `Library.language`| _Equivalent_<br/>(43682/43683)| `Library.language`
| | | **`Library.text`**| _Equivalent_<br/>(15187/15188)| `Library.text`| _Equivalent_<br/>(28813/28814)| `Library.text`| _Equivalent_<br/>(43684/43685)| `Library.text`
| | | **`Library.contained`**| _Equivalent_<br/>(15189/15190)| `Library.contained`| _Equivalent_<br/>(28815/28816)| `Library.contained`| _Equivalent_<br/>(43686/43687)| `Library.contained`
| | | **`Library.extension`**| _Equivalent_<br/>(15191/15192)| `Library.extension`| _Equivalent_<br/>(28817/28818)| `Library.extension`| _Equivalent_<br/>(43688/43689)| `Library.extension`
| | | **`Library.modifierExtension`**| _Equivalent_<br/>(15193/15194)| `Library.modifierExtension`| _Equivalent_<br/>(28819/28820)| `Library.modifierExtension`| _Equivalent_<br/>(43690/43691)| `Library.modifierExtension`
| | | **`Library.url`**| _Equivalent_<br/>(15195/15196)| `Library.url`| _Equivalent_<br/>(28821/28822)| `Library.url`| _Equivalent_<br/>(43692/43693)| `Library.url`
| | | **`Library.identifier`**| _Equivalent_<br/>(15197/15198)| `Library.identifier`| _Equivalent_<br/>(28823/28824)| `Library.identifier`| _Equivalent_<br/>(43694/43695)| `Library.identifier`
| | | **`Library.version`**| _Equivalent_<br/>(15199/15200)| `Library.version`| _Equivalent_<br/>(28825/28826)| `Library.version`| _Equivalent_<br/>(43696/43697)| `Library.version`
| | | **`Library.name`**| _Equivalent_<br/>(15201/15202)| `Library.name`| _Equivalent_<br/>(28827/28828)| `Library.name`| _Equivalent_<br/>(43698/43699)| `Library.name`
| | | **`Library.title`**| _Equivalent_<br/>(15203/15204)| `Library.title`| _Equivalent_<br/>(28829/28830)| `Library.title`| _Equivalent_<br/>(43700/43701)| `Library.title`
| | | **`Library.status`**| _Equivalent_<br/>(15205/15206)| `Library.status`| _Equivalent_<br/>(28833/28834)| `Library.status`| _Equivalent_<br/>(43704/43705)| `Library.status`
| | | **`Library.experimental`**| _Equivalent_<br/>(15207/15208)| `Library.experimental`| _Equivalent_<br/>(28835/28836)| `Library.experimental`| _Equivalent_<br/>(43706/43707)| `Library.experimental`
| | | **`Library.type`**| _Equivalent_<br/>(15209/15210)| `Library.type`| _Equivalent_<br/>(28837/28838)| `Library.type`| _Equivalent_<br/>(43708/43709)| `Library.type`
| | | **`Library.date`**| _Equivalent_<br/>(15211/15212)| `Library.date`| _Equivalent_<br/>(28841/28842)| `Library.date`| _Equivalent_<br/>(43712/43713)| `Library.date`
| | | **`Library.publisher`**| _Equivalent_<br/>(15213/15214)| `Library.publisher`| _Equivalent_<br/>(28843/28844)| `Library.publisher`| _Equivalent_<br/>(43714/43715)| `Library.publisher`
| | | **`Library.description`**| _Equivalent_<br/>(15215/15216)| `Library.description`| _Equivalent_<br/>(28847/28848)| `Library.description`| _Equivalent_<br/>(43718/43719)| `Library.description`
| | | **`Library.purpose`**| _Equivalent_<br/>(15217/15218)| `Library.purpose`| _Equivalent_<br/>(28853/28854)| `Library.purpose`| _Equivalent_<br/>(43724/43725)| `Library.purpose`
| | | **`Library.usage`**| _Equivalent_<br/>(15219/15220)| `Library.usage`| _Equivalent_<br/>(28855/28856)| `Library.usage`| _Equivalent_<br/>(43726/43727)| `Library.usage`
| | | **`Library.approvalDate`**| _Equivalent_<br/>(15221/15222)| `Library.approvalDate`| _Equivalent_<br/>(28859/28860)| `Library.approvalDate`| _Equivalent_<br/>(43730/43731)| `Library.approvalDate`
| | | **`Library.lastReviewDate`**| _Equivalent_<br/>(15223/15224)| `Library.lastReviewDate`| _Equivalent_<br/>(28861/28862)| `Library.lastReviewDate`| _Equivalent_<br/>(43732/43733)| `Library.lastReviewDate`
| | | **`Library.effectivePeriod`**| _Equivalent_<br/>(15225/15226)| `Library.effectivePeriod`| _Equivalent_<br/>(28863/28864)| `Library.effectivePeriod`| _Equivalent_<br/>(43734/43735)| `Library.effectivePeriod`
| | | **`Library.useContext`**| _Equivalent_<br/>(15227/15228)| `Library.useContext`| _Equivalent_<br/>(28849/28850)| `Library.useContext`| _Equivalent_<br/>(43720/43721)| `Library.useContext`
| | | **`Library.jurisdiction`**| _Equivalent_<br/>(15229/15230)| `Library.jurisdiction`| _Equivalent_<br/>(28851/28852)| `Library.jurisdiction`| _Equivalent_<br/>(43722/43723)| `Library.jurisdiction`
| | | **`Library.topic`**| _Equivalent_<br/>(15231/15232)| `Library.topic`| _Equivalent_<br/>(28865/28866)| `Library.topic`| _Equivalent_<br/>(43736/43737)| `Library.topic`
| | | **`Library.contributor`**| →→→→ __ →→→→ <br/>(1147)<hr/>←←←← __ ←←←← <br/>()| `base64Binary`| | | | | 
| | | **`Library.contributor`**| →→→→ _Equivalent_ →→→→ <br/>(28799)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1705)| `Library.author`| _Equivalent_<br/>(28867/28868)| `Library.author`| _Equivalent_<br/>(43738/43739)| `Library.author`
| | | **`Library.contributor`**| →→→→ _Equivalent_ →→→→ <br/>(28800)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1706)| `Library.editor`| _Equivalent_<br/>(28869/28870)| `Library.editor`| _Equivalent_<br/>(43740/43741)| `Library.editor`
| | | **`Library.contributor`**| →→→→ _Equivalent_ →→→→ <br/>(28801)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1707)| `Library.reviewer`| _Equivalent_<br/>(28871/28872)| `Library.reviewer`| _Equivalent_<br/>(43742/43743)| `Library.reviewer`
| | | **`Library.contributor`**| →→→→ _Equivalent_ →→→→ <br/>(28802)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1708)| `Library.endorser`| _Equivalent_<br/>(28873/28874)| `Library.endorser`| _Equivalent_<br/>(43744/43745)| `Library.endorser`
| | | **`Library.contact`**| _Equivalent_<br/>(15233/15234)| `Library.contact`| _Equivalent_<br/>(28845/28846)| `Library.contact`| _Equivalent_<br/>(43716/43717)| `Library.contact`
| | | **`Library.copyright`**| _Equivalent_<br/>(15235/15236)| `Library.copyright`| _Equivalent_<br/>(28857/28858)| `Library.copyright`| _Equivalent_<br/>(43728/43729)| `Library.copyright`
| | | **`Library.relatedArtifact`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15237)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15238)| `Library.relatedArtifact`| _Equivalent_<br/>(28875/28876)| `Library.relatedArtifact`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(43746)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(43747)| `Library.relatedArtifact`
| | | **`Library.parameter`**| _Equivalent_<br/>(15239/15240)| `Library.parameter`| _Equivalent_<br/>(28877/28878)| `Library.parameter`| _Equivalent_<br/>(43748/43749)| `Library.parameter`
| | | **`Library.dataRequirement`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15241)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15242)| `Library.dataRequirement`| _Equivalent_<br/>(28879/28880)| `Library.dataRequirement`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(43750)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(43751)| `Library.dataRequirement`
| | | **`Library.content`**| _Equivalent_<br/>(15243/15244)| `Library.content`| _Equivalent_<br/>(28881/28882)| `Library.content`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(43752)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(43753)| `Library.content`
| | | *35 of 35 elements used* | | *39 of 40 elements used* <br/>remaining elements:<br/>`Library.subject[x]`, `Library.subtitle`| | *38 of 40 elements used* <br/>remaining elements:<br/>`Library.subject[x]`, `Library.subtitle`| | *38 of 42 elements used* <br/>remaining elements:<br/>`Library.copyrightLabel`, `Library.subject[x]`, `Library.subtitle`, `Library.versionAlgorithm[x]`

