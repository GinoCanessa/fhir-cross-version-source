Comparison of 
Generated at Tuesday, April 1, 2025 1:39:29 PM

### EvidenceReport

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | EvidenceReport |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/EvidenceReport` |
| Version | 4.3.0 |
| Description | The EvidenceReport Resource is a specialized container for a collection of resources and codable concepts, adapted to support compositions of Evidence, EvidenceVariable, and Citation resources and related concepts. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1691` |
| Database Snapshot Count | `59` |
| Database Differential Count | `39` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `EvidenceReport` | `EvidenceReport` | `EvidenceReport` | EvidenceReport | A EvidenceReport | 0..* | EvidenceReport |  |  |
| `EvidenceReport.author` | `EvidenceReport.author` | `author` | EvidenceReport.author | Who authored the content | 0..* | ContactDetail |  |  |
| `EvidenceReport.citeAs[x]` | `EvidenceReport.citeAs[x]` | `citeAs[x]` | EvidenceReport.citeAs[x] | Citation for this report | 0..1 | markdown, Reference(http://hl7.org/fhir/StructureDefinition/Citation) |  |  |
| `EvidenceReport.contact` | `EvidenceReport.contact` | `contact` | EvidenceReport.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `EvidenceReport.contained` | `EvidenceReport.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `EvidenceReport.editor` | `EvidenceReport.editor` | `editor` | EvidenceReport.editor | Who edited the content | 0..* | ContactDetail |  |  |
| `EvidenceReport.endorser` | `EvidenceReport.endorser` | `endorser` | EvidenceReport.endorser | Who endorsed the content | 0..* | ContactDetail |  |  |
| `EvidenceReport.extension` | `EvidenceReport.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EvidenceReport.id` | `EvidenceReport.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `EvidenceReport.identifier` | `EvidenceReport.identifier` | `identifier` | EvidenceReport.identifier | Unique identifier for the evidence report | 0..* | Identifier |  |  |
| `EvidenceReport.implicitRules` | `EvidenceReport.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `EvidenceReport.language` | `EvidenceReport.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `EvidenceReport.meta` | `EvidenceReport.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `EvidenceReport.modifierExtension` | `EvidenceReport.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `EvidenceReport.note` | `EvidenceReport.note` | `note` | EvidenceReport.note | Used for footnotes and annotations | 0..* | Annotation |  |  |
| `EvidenceReport.publisher` | `EvidenceReport.publisher` | `publisher` | EvidenceReport.publisher | Name of the publisher (organization or individual) | 0..1 | string |  |  |
| `EvidenceReport.relatedArtifact` | `EvidenceReport.relatedArtifact` | `relatedArtifact` | EvidenceReport.relatedArtifact | Link, description or reference to artifact associated with the report | 0..* | RelatedArtifact |  |  |
| `EvidenceReport.relatedIdentifier` | `EvidenceReport.relatedIdentifier` | `relatedIdentifier` | EvidenceReport.relatedIdentifier | Identifiers for articles that may relate to more than one evidence report | 0..* | Identifier |  |  |
| `EvidenceReport.relatesTo` | `EvidenceReport.relatesTo` | `relatesTo` | EvidenceReport.relatesTo | Relationships to other compositions/documents | 0..* | BackboneElement |  |  |
| `EvidenceReport.relatesTo.code` | `EvidenceReport.relatesTo.code` | `code` | EvidenceReport.relatesTo.code | replaces \| amends \| appends \| transforms \| replacedWith \| amendedWith \| appendedWith \| transformedWith | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/report-relation-type|4.3.0` |
| `EvidenceReport.relatesTo.extension` | `EvidenceReport.relatesTo.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EvidenceReport.relatesTo.id` | `EvidenceReport.relatesTo.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `EvidenceReport.relatesTo.modifierExtension` | `EvidenceReport.relatesTo.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `EvidenceReport.relatesTo.target[x]` | `EvidenceReport.relatesTo.target[x]` | `target[x]` | EvidenceReport.relatesTo.target[x] | Target of the relationship | 1..1 | Identifier, Reference(http://hl7.org/fhir/StructureDefinition/EvidenceReport) |  |  |
| `EvidenceReport.reviewer` | `EvidenceReport.reviewer` | `reviewer` | EvidenceReport.reviewer | Who reviewed the content | 0..* | ContactDetail |  |  |
| `EvidenceReport.section` | `EvidenceReport.section` | `section` | EvidenceReport.section | Composition is broken into sections | 0..* | BackboneElement |  |  |
| `EvidenceReport.section.author` | `EvidenceReport.section.author` | `author` | EvidenceReport.section.author | Who and/or what authored the section | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Person) |  |  |
| `EvidenceReport.section.emptyReason` | `EvidenceReport.section.emptyReason` | `emptyReason` | EvidenceReport.section.emptyReason | Why the section is empty | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/list-empty-reason` |
| `EvidenceReport.section.entryClassifier` | `EvidenceReport.section.entryClassifier` | `entryClassifier` | EvidenceReport.section.entryClassifier | Extensible classifiers as content | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/evidence-classifier-code` |
| `EvidenceReport.section.entryQuantity` | `EvidenceReport.section.entryQuantity` | `entryQuantity` | EvidenceReport.section.entryQuantity | Quantity as content | 0..* | Quantity |  |  |
| `EvidenceReport.section.entryReference` | `EvidenceReport.section.entryReference` | `entryReference` | EvidenceReport.section.entryReference | Reference to resources as content | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `EvidenceReport.section.extension` | `EvidenceReport.section.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EvidenceReport.section.focus` | `EvidenceReport.section.focus` | `focus` | EvidenceReport.section.focus | Classification of section (recommended) | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/evidence-report-section` |
| `EvidenceReport.section.focusReference` | `EvidenceReport.section.focusReference` | `focusReference` | EvidenceReport.section.focusReference | Classification of section by Resource | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `EvidenceReport.section.id` | `EvidenceReport.section.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `EvidenceReport.section.mode` | `EvidenceReport.section.mode` | `mode` | EvidenceReport.section.mode | working \| snapshot \| changes | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/list-mode|4.3.0` |
| `EvidenceReport.section.modifierExtension` | `EvidenceReport.section.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `EvidenceReport.section.orderedBy` | `EvidenceReport.section.orderedBy` | `orderedBy` | EvidenceReport.section.orderedBy | Order of section entries | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/list-order` |
| `EvidenceReport.section.section` | `EvidenceReport.section.section` | `section` | EvidenceReport.section.section | Nested Section | 0..* | EvidenceReport.section |  |  |
| `EvidenceReport.section.text` | `EvidenceReport.section.text` | `text` | EvidenceReport.section.text | Text summary of the section, for human interpretation | 0..1 | Narrative |  |  |
| `EvidenceReport.section.title` | `EvidenceReport.section.title` | `title` | EvidenceReport.section.title | Label for section (e.g. for ToC) | 0..1 | string |  |  |
| `EvidenceReport.status` | `EvidenceReport.status` | `status` | EvidenceReport.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|4.3.0` |
| `EvidenceReport.subject` | `EvidenceReport.subject` | `subject` | EvidenceReport.subject | Focus of the report | 1..1 | BackboneElement |  |  |
| `EvidenceReport.subject.characteristic` | `EvidenceReport.subject.characteristic` | `characteristic` | EvidenceReport.subject.characteristic | Characteristic | 0..* | BackboneElement |  |  |
| `EvidenceReport.subject.characteristic.code` | `EvidenceReport.subject.characteristic.code` | `code` | EvidenceReport.subject.characteristic.code | Characteristic code | 1..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/focus-characteristic-code` |
| `EvidenceReport.subject.characteristic.exclude` | `EvidenceReport.subject.characteristic.exclude` | `exclude` | EvidenceReport.subject.characteristic.exclude | Is used to express not the characteristic | 0..1 | boolean |  |  |
| `EvidenceReport.subject.characteristic.extension` | `EvidenceReport.subject.characteristic.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EvidenceReport.subject.characteristic.id` | `EvidenceReport.subject.characteristic.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `EvidenceReport.subject.characteristic.modifierExtension` | `EvidenceReport.subject.characteristic.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `EvidenceReport.subject.characteristic.period` | `EvidenceReport.subject.characteristic.period` | `period` | EvidenceReport.subject.characteristic.period | Timeframe for the characteristic | 0..1 | Period |  |  |
| `EvidenceReport.subject.characteristic.value[x]` | `EvidenceReport.subject.characteristic.value[x]` | `value[x]` | EvidenceReport.subject.characteristic.value[x] | Characteristic value | 1..1 | boolean, CodeableConcept, Quantity, Range, Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `EvidenceReport.subject.extension` | `EvidenceReport.subject.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `EvidenceReport.subject.id` | `EvidenceReport.subject.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `EvidenceReport.subject.modifierExtension` | `EvidenceReport.subject.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `EvidenceReport.subject.note` | `EvidenceReport.subject.note` | `note` | EvidenceReport.subject.note | Footnotes and/or explanatory notes | 0..* | Annotation |  |  |
| `EvidenceReport.text` | `EvidenceReport.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `EvidenceReport.type` | `EvidenceReport.type` | `type` | EvidenceReport.type | Kind of report | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/evidence-report-type` |
| `EvidenceReport.url` | `EvidenceReport.url` | `url` | EvidenceReport.url | Canonical identifier for this EvidenceReport, represented as a globally unique URI | 0..1 | uri |  |  |
| `EvidenceReport.useContext` | `EvidenceReport.useContext` | `useContext` | EvidenceReport.useContext | The context that the content is intended to support | 0..* | UsageContext |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [EvidenceReport](/docs/R4B/Resources/EvidenceReport.md)<br/> `http://hl7.org/fhir/StructureDefinition/EvidenceReport\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `976`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1205`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EvidenceReport](/docs/R5/Resources/EvidenceReport.md)<br/> `http://hl7.org/fhir/StructureDefinition/EvidenceReport\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition EvidenceReport from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | R4B EvidenceReport| Relationship | [R5 EvidenceReport](/docs/R5/Resources/EvidenceReport.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | **`EvidenceReport`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(41537)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(41538)| `EvidenceReport`
| | | | | | | **`EvidenceReport.id`**| _Equivalent_<br/>(41539/41540)| `EvidenceReport.id`
| | | | | | | **`EvidenceReport.meta`**| _Equivalent_<br/>(41541/41542)| `EvidenceReport.meta`
| | | | | | | **`EvidenceReport.implicitRules`**| _Equivalent_<br/>(41543/41544)| `EvidenceReport.implicitRules`
| | | | | | | **`EvidenceReport.language`**| _Equivalent_<br/>(41545/41546)| `EvidenceReport.language`
| | | | | | | **`EvidenceReport.text`**| _Equivalent_<br/>(41547/41548)| `EvidenceReport.text`
| | | | | | | **`EvidenceReport.contained`**| _Equivalent_<br/>(41549/41550)| `EvidenceReport.contained`
| | | | | | | **`EvidenceReport.extension`**| _Equivalent_<br/>(41551/41552)| `EvidenceReport.extension`
| | | | | | | **`EvidenceReport.modifierExtension`**| _Equivalent_<br/>(41553/41554)| `EvidenceReport.modifierExtension`
| | | | | | | **`EvidenceReport.url`**| _Equivalent_<br/>(41555/41556)| `EvidenceReport.url`
| | | | | | | **`EvidenceReport.status`**| _Equivalent_<br/>(41557/41558)| `EvidenceReport.status`
| | | | | | | **`EvidenceReport.useContext`**| _Equivalent_<br/>(41559/41560)| `EvidenceReport.useContext`
| | | | | | | **`EvidenceReport.identifier`**| _Equivalent_<br/>(41561/41562)| `EvidenceReport.identifier`
| | | | | | | **`EvidenceReport.relatedIdentifier`**| _Equivalent_<br/>(41563/41564)| `EvidenceReport.relatedIdentifier`
| | | | | | | **`EvidenceReport.citeAs[x]`**| _Equivalent_<br/>(41565/41566)| `EvidenceReport.citeAs[x]`
| | | | | | | **`EvidenceReport.type`**| _Equivalent_<br/>(41567/41568)| `EvidenceReport.type`
| | | | | | | **`EvidenceReport.note`**| _Equivalent_<br/>(41569/41570)| `EvidenceReport.note`
| | | | | | | **`EvidenceReport.relatedArtifact`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(41571)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(41572)| `EvidenceReport.relatedArtifact`
| | | | | | | **`EvidenceReport.subject`**| _Equivalent_<br/>(41573/41574)| `EvidenceReport.subject`
| | | | | | | **`EvidenceReport.subject.id`**| _Equivalent_<br/>(41575/41576)| `EvidenceReport.subject.id`
| | | | | | | **`EvidenceReport.subject.extension`**| _Equivalent_<br/>(41577/41578)| `EvidenceReport.subject.extension`
| | | | | | | **`EvidenceReport.subject.modifierExtension`**| _Equivalent_<br/>(41579/41580)| `EvidenceReport.subject.modifierExtension`
| | | | | | | **`EvidenceReport.subject.characteristic`**| _Equivalent_<br/>(41581/41582)| `EvidenceReport.subject.characteristic`
| | | | | | | **`EvidenceReport.subject.characteristic.id`**| _Equivalent_<br/>(41583/41584)| `EvidenceReport.subject.characteristic.id`
| | | | | | | **`EvidenceReport.subject.characteristic.extension`**| _Equivalent_<br/>(41585/41586)| `EvidenceReport.subject.characteristic.extension`
| | | | | | | **`EvidenceReport.subject.characteristic.modifierExtension`**| _Equivalent_<br/>(41587/41588)| `EvidenceReport.subject.characteristic.modifierExtension`
| | | | | | | **`EvidenceReport.subject.characteristic.code`**| _Equivalent_<br/>(41589/41590)| `EvidenceReport.subject.characteristic.code`
| | | | | | | **`EvidenceReport.subject.characteristic.value[x]`**| _Equivalent_<br/>(41591/41592)| `EvidenceReport.subject.characteristic.value[x]`
| | | | | | | **`EvidenceReport.subject.characteristic.exclude`**| _Equivalent_<br/>(41593/41594)| `EvidenceReport.subject.characteristic.exclude`
| | | | | | | **`EvidenceReport.subject.characteristic.period`**| _Equivalent_<br/>(41595/41596)| `EvidenceReport.subject.characteristic.period`
| | | | | | | **`EvidenceReport.subject.note`**| _Equivalent_<br/>(41597/41598)| `EvidenceReport.subject.note`
| | | | | | | **`EvidenceReport.publisher`**| _Equivalent_<br/>(41599/41600)| `EvidenceReport.publisher`
| | | | | | | **`EvidenceReport.contact`**| _Equivalent_<br/>(41601/41602)| `EvidenceReport.contact`
| | | | | | | **`EvidenceReport.author`**| _Equivalent_<br/>(41603/41604)| `EvidenceReport.author`
| | | | | | | **`EvidenceReport.editor`**| _Equivalent_<br/>(41605/41606)| `EvidenceReport.editor`
| | | | | | | **`EvidenceReport.reviewer`**| _Equivalent_<br/>(41607/41608)| `EvidenceReport.reviewer`
| | | | | | | **`EvidenceReport.endorser`**| _Equivalent_<br/>(41609/41610)| `EvidenceReport.endorser`
| | | | | | | **`EvidenceReport.relatesTo`**| _Equivalent_<br/>(41611/41612)| `EvidenceReport.relatesTo`
| | | | | | | **`EvidenceReport.relatesTo.id`**| _Equivalent_<br/>(41613/41614)| `EvidenceReport.relatesTo.id`
| | | | | | | **`EvidenceReport.relatesTo.extension`**| _Equivalent_<br/>(41615/41616)| `EvidenceReport.relatesTo.extension`
| | | | | | | **`EvidenceReport.relatesTo.modifierExtension`**| _Equivalent_<br/>(41617/41618)| `EvidenceReport.relatesTo.modifierExtension`
| | | | | | | **`EvidenceReport.relatesTo.code`**| _Equivalent_<br/>(41619/41620)| `EvidenceReport.relatesTo.code`
| | | | | | | **`EvidenceReport.relatesTo.target[x]`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1785)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2029)| `EvidenceReport.relatesTo.target`
| | | | | | | **`EvidenceReport.section`**| _Equivalent_<br/>(41621/41622)| `EvidenceReport.section`
| | | | | | | **`EvidenceReport.section.id`**| _Equivalent_<br/>(41623/41624)| `EvidenceReport.section.id`
| | | | | | | **`EvidenceReport.section.extension`**| _Equivalent_<br/>(41625/41626)| `EvidenceReport.section.extension`
| | | | | | | **`EvidenceReport.section.modifierExtension`**| _Equivalent_<br/>(41627/41628)| `EvidenceReport.section.modifierExtension`
| | | | | | | **`EvidenceReport.section.title`**| _Equivalent_<br/>(41629/41630)| `EvidenceReport.section.title`
| | | | | | | **`EvidenceReport.section.focus`**| _Equivalent_<br/>(41631/41632)| `EvidenceReport.section.focus`
| | | | | | | **`EvidenceReport.section.focusReference`**| _Equivalent_<br/>(41633/41634)| `EvidenceReport.section.focusReference`
| | | | | | | **`EvidenceReport.section.author`**| →→→→ _RelatedTo_ →→→→ <br/>(41635)<hr/>←←←← _RelatedTo_ ←←←← <br/>(41636)| `EvidenceReport.section.author`
| | | | | | | **`EvidenceReport.section.text`**| _Equivalent_<br/>(41637/41638)| `EvidenceReport.section.text`
| | | | | | | **`EvidenceReport.section.mode`**| _Equivalent_<br/>(41639/41640)| `EvidenceReport.section.mode`
| | | | | | | **`EvidenceReport.section.orderedBy`**| _Equivalent_<br/>(41641/41642)| `EvidenceReport.section.orderedBy`
| | | | | | | **`EvidenceReport.section.entryClassifier`**| _Equivalent_<br/>(41643/41644)| `EvidenceReport.section.entryClassifier`
| | | | | | | **`EvidenceReport.section.entryReference`**| _Equivalent_<br/>(41645/41646)| `EvidenceReport.section.entryReference`
| | | | | | | **`EvidenceReport.section.entryQuantity`**| _Equivalent_<br/>(41647/41648)| `EvidenceReport.section.entryQuantity`
| | | | | | | **`EvidenceReport.section.emptyReason`**| _Equivalent_<br/>(41649/41650)| `EvidenceReport.section.emptyReason`
| | | | | | | **`EvidenceReport.section.section`**| _Equivalent_<br/>(41651/41652)| `EvidenceReport.section.section`
| | | | | | | *59 of 59 elements used* | | *59 of 66 elements used* 

