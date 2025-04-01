Comparison of 
Generated at Tuesday, April 1, 2025 1:39:31 PM

### Citation

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | Citation |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Citation` |
| Version | 4.3.0 |
| Description | The Citation Resource enables reference to any knowledge artifact for purposes of identification and attribution. The Citation Resource supports existing reference structures and developing publication practices such as versioning, expressing complex contributorship roles, and referencing computable resources. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1657` |
| Database Snapshot Count | `210` |
| Database Differential Count | `133` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Citation` | `Citation` | `Citation` | Citation | A description of identification, location, or contributorship of a publication (article or artifact) | 0..* | Citation |  |  |
| `Citation.approvalDate` | `Citation.approvalDate` | `approvalDate` | Citation.approvalDate | When the citation was approved by publisher | 0..1 | date |  |  |
| `Citation.author` | `Citation.author` | `author` | Citation.author | Who authored the Citation | 0..* | ContactDetail |  |  |
| `Citation.citedArtifact` | `Citation.citedArtifact` | `citedArtifact` | Citation.citedArtifact | The article or artifact being described | 0..1 | BackboneElement |  |  |
| `Citation.citedArtifact.abstract` | `Citation.citedArtifact.abstract` | `abstract` | Citation.citedArtifact.abstract | Summary of the article or artifact | 0..* | BackboneElement |  |  |
| `Citation.citedArtifact.abstract.copyright` | `Citation.citedArtifact.abstract.copyright` | `copyright` | Citation.citedArtifact.abstract.copyright | Copyright notice for the abstract | 0..1 | markdown |  |  |
| `Citation.citedArtifact.abstract.extension` | `Citation.citedArtifact.abstract.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Citation.citedArtifact.abstract.id` | `Citation.citedArtifact.abstract.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Citation.citedArtifact.abstract.language` | `Citation.citedArtifact.abstract.language` | `language` | Citation.citedArtifact.abstract.language | Used to express the specific language | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/languages` |
| `Citation.citedArtifact.abstract.modifierExtension` | `Citation.citedArtifact.abstract.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Citation.citedArtifact.abstract.text` | `Citation.citedArtifact.abstract.text` | `text` | Citation.citedArtifact.abstract.text | Abstract content | 1..1 | markdown |  |  |
| `Citation.citedArtifact.abstract.type` | `Citation.citedArtifact.abstract.type` | `type` | Citation.citedArtifact.abstract.type | The kind of abstract | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/cited-artifact-abstract-type` |
| `Citation.citedArtifact.classification` | `Citation.citedArtifact.classification` | `classification` | Citation.citedArtifact.classification | The assignment to an organizing scheme | 0..* | BackboneElement |  |  |
| `Citation.citedArtifact.classification.classifier` | `Citation.citedArtifact.classification.classifier` | `classifier` | Citation.citedArtifact.classification.classifier | The specific classification value | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/citation-artifact-classifier` |
| `Citation.citedArtifact.classification.extension` | `Citation.citedArtifact.classification.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Citation.citedArtifact.classification.id` | `Citation.citedArtifact.classification.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Citation.citedArtifact.classification.modifierExtension` | `Citation.citedArtifact.classification.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Citation.citedArtifact.classification.type` | `Citation.citedArtifact.classification.type` | `type` | Citation.citedArtifact.classification.type | The kind of classifier (e.g. publication type, keyword) | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/cited-artifact-classification-type` |
| `Citation.citedArtifact.classification.whoClassified` | `Citation.citedArtifact.classification.whoClassified` | `whoClassified` | Citation.citedArtifact.classification.whoClassified | Provenance and copyright of classification | 0..1 | BackboneElement |  |  |
| `Citation.citedArtifact.classification.whoClassified.classifierCopyright` | `Citation.citedArtifact.classification.whoClassified.classifierCopyright` | `classifierCopyright` | Citation.citedArtifact.classification.whoClassified.classifierCopyright | Rights management statement for the classification | 0..1 | string |  |  |
| `Citation.citedArtifact.classification.whoClassified.extension` | `Citation.citedArtifact.classification.whoClassified.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Citation.citedArtifact.classification.whoClassified.freeToShare` | `Citation.citedArtifact.classification.whoClassified.freeToShare` | `freeToShare` | Citation.citedArtifact.classification.whoClassified.freeToShare | Acceptable to re-use the classification | 0..1 | boolean |  |  |
| `Citation.citedArtifact.classification.whoClassified.id` | `Citation.citedArtifact.classification.whoClassified.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Citation.citedArtifact.classification.whoClassified.modifierExtension` | `Citation.citedArtifact.classification.whoClassified.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Citation.citedArtifact.classification.whoClassified.organization` | `Citation.citedArtifact.classification.whoClassified.organization` | `organization` | Citation.citedArtifact.classification.whoClassified.organization | Organization who created the classification | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Citation.citedArtifact.classification.whoClassified.person` | `Citation.citedArtifact.classification.whoClassified.person` | `person` | Citation.citedArtifact.classification.whoClassified.person | Person who created the classification | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Person), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `Citation.citedArtifact.classification.whoClassified.publisher` | `Citation.citedArtifact.classification.whoClassified.publisher` | `publisher` | Citation.citedArtifact.classification.whoClassified.publisher | The publisher of the classification, not the publisher of the article or artifact being cited | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Citation.citedArtifact.contributorship` | `Citation.citedArtifact.contributorship` | `contributorship` | Citation.citedArtifact.contributorship | Attribution of authors and other contributors | 0..1 | BackboneElement |  |  |
| `Citation.citedArtifact.contributorship.complete` | `Citation.citedArtifact.contributorship.complete` | `complete` | Citation.citedArtifact.contributorship.complete | Indicates if the list includes all authors and/or contributors | 0..1 | boolean |  |  |
| `Citation.citedArtifact.contributorship.entry` | `Citation.citedArtifact.contributorship.entry` | `entry` | Citation.citedArtifact.contributorship.entry | An individual entity named in the list | 0..* | BackboneElement |  |  |
| `Citation.citedArtifact.contributorship.entry.address` | `Citation.citedArtifact.contributorship.entry.address` | `address` | Citation.citedArtifact.contributorship.entry.address | Physical mailing address | 0..* | Address |  |  |
| `Citation.citedArtifact.contributorship.entry.affiliationInfo` | `Citation.citedArtifact.contributorship.entry.affiliationInfo` | `affiliationInfo` | Citation.citedArtifact.contributorship.entry.affiliationInfo | Organizational affiliation | 0..* | BackboneElement |  |  |
| `Citation.citedArtifact.contributorship.entry.affiliationInfo.affiliation` | `Citation.citedArtifact.contributorship.entry.affiliationInfo.affiliation` | `affiliation` | Citation.citedArtifact.contributorship.entry.affiliationInfo.affiliation | Display for the organization | 0..1 | string |  |  |
| `Citation.citedArtifact.contributorship.entry.affiliationInfo.extension` | `Citation.citedArtifact.contributorship.entry.affiliationInfo.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Citation.citedArtifact.contributorship.entry.affiliationInfo.id` | `Citation.citedArtifact.contributorship.entry.affiliationInfo.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Citation.citedArtifact.contributorship.entry.affiliationInfo.identifier` | `Citation.citedArtifact.contributorship.entry.affiliationInfo.identifier` | `identifier` | Citation.citedArtifact.contributorship.entry.affiliationInfo.identifier | Identifier for the organization | 0..* | Identifier |  |  |
| `Citation.citedArtifact.contributorship.entry.affiliationInfo.modifierExtension` | `Citation.citedArtifact.contributorship.entry.affiliationInfo.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Citation.citedArtifact.contributorship.entry.affiliationInfo.role` | `Citation.citedArtifact.contributorship.entry.affiliationInfo.role` | `role` | Citation.citedArtifact.contributorship.entry.affiliationInfo.role | Role within the organization, such as professional title | 0..1 | string |  |  |
| `Citation.citedArtifact.contributorship.entry.collectiveName` | `Citation.citedArtifact.contributorship.entry.collectiveName` | `collectiveName` | Citation.citedArtifact.contributorship.entry.collectiveName | Used for collective or corporate name as an author | 0..1 | string |  |  |
| `Citation.citedArtifact.contributorship.entry.contributionInstance` | `Citation.citedArtifact.contributorship.entry.contributionInstance` | `contributionInstance` | Citation.citedArtifact.contributorship.entry.contributionInstance | Contributions with accounting for time or number | 0..* | BackboneElement |  |  |
| `Citation.citedArtifact.contributorship.entry.contributionInstance.extension` | `Citation.citedArtifact.contributorship.entry.contributionInstance.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Citation.citedArtifact.contributorship.entry.contributionInstance.id` | `Citation.citedArtifact.contributorship.entry.contributionInstance.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Citation.citedArtifact.contributorship.entry.contributionInstance.modifierExtension` | `Citation.citedArtifact.contributorship.entry.contributionInstance.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Citation.citedArtifact.contributorship.entry.contributionInstance.time` | `Citation.citedArtifact.contributorship.entry.contributionInstance.time` | `time` | Citation.citedArtifact.contributorship.entry.contributionInstance.time | The time that the contribution was made | 0..1 | dateTime |  |  |
| `Citation.citedArtifact.contributorship.entry.contributionInstance.type` | `Citation.citedArtifact.contributorship.entry.contributionInstance.type` | `type` | Citation.citedArtifact.contributorship.entry.contributionInstance.type | The specific contribution | 1..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/artifact-contribution-instance-type` |
| `Citation.citedArtifact.contributorship.entry.contributionType` | `Citation.citedArtifact.contributorship.entry.contributionType` | `contributionType` | Citation.citedArtifact.contributorship.entry.contributionType | The specific contribution | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/artifact-contribution-type` |
| `Citation.citedArtifact.contributorship.entry.correspondingContact` | `Citation.citedArtifact.contributorship.entry.correspondingContact` | `correspondingContact` | Citation.citedArtifact.contributorship.entry.correspondingContact | Indication of which contributor is the corresponding contributor for the role | 0..1 | boolean |  |  |
| `Citation.citedArtifact.contributorship.entry.extension` | `Citation.citedArtifact.contributorship.entry.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Citation.citedArtifact.contributorship.entry.id` | `Citation.citedArtifact.contributorship.entry.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Citation.citedArtifact.contributorship.entry.identifier` | `Citation.citedArtifact.contributorship.entry.identifier` | `identifier` | Citation.citedArtifact.contributorship.entry.identifier | Author identifier, eg ORCID | 0..* | Identifier |  |  |
| `Citation.citedArtifact.contributorship.entry.initials` | `Citation.citedArtifact.contributorship.entry.initials` | `initials` | Citation.citedArtifact.contributorship.entry.initials | Initials for forename | 0..1 | string |  |  |
| `Citation.citedArtifact.contributorship.entry.listOrder` | `Citation.citedArtifact.contributorship.entry.listOrder` | `listOrder` | Citation.citedArtifact.contributorship.entry.listOrder | Used to code order of authors | 0..1 | positiveInt |  |  |
| `Citation.citedArtifact.contributorship.entry.modifierExtension` | `Citation.citedArtifact.contributorship.entry.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Citation.citedArtifact.contributorship.entry.name` | `Citation.citedArtifact.contributorship.entry.name` | `name` | Citation.citedArtifact.contributorship.entry.name | A name associated with the person | 0..1 | HumanName |  |  |
| `Citation.citedArtifact.contributorship.entry.role` | `Citation.citedArtifact.contributorship.entry.role` | `role` | Citation.citedArtifact.contributorship.entry.role | The role of the contributor (e.g. author, editor, reviewer) | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/contributor-role` |
| `Citation.citedArtifact.contributorship.entry.telecom` | `Citation.citedArtifact.contributorship.entry.telecom` | `telecom` | Citation.citedArtifact.contributorship.entry.telecom | Email or telephone contact methods for the author or contributor | 0..* | ContactPoint |  |  |
| `Citation.citedArtifact.contributorship.extension` | `Citation.citedArtifact.contributorship.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Citation.citedArtifact.contributorship.id` | `Citation.citedArtifact.contributorship.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Citation.citedArtifact.contributorship.modifierExtension` | `Citation.citedArtifact.contributorship.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Citation.citedArtifact.contributorship.summary` | `Citation.citedArtifact.contributorship.summary` | `summary` | Citation.citedArtifact.contributorship.summary | Used to record a display of the author/contributor list without separate coding for each list member | 0..* | BackboneElement |  |  |
| `Citation.citedArtifact.contributorship.summary.extension` | `Citation.citedArtifact.contributorship.summary.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Citation.citedArtifact.contributorship.summary.id` | `Citation.citedArtifact.contributorship.summary.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Citation.citedArtifact.contributorship.summary.modifierExtension` | `Citation.citedArtifact.contributorship.summary.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Citation.citedArtifact.contributorship.summary.source` | `Citation.citedArtifact.contributorship.summary.source` | `source` | Citation.citedArtifact.contributorship.summary.source | Used to code the producer or rule for creating the display string | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/contributor-summary-source` |
| `Citation.citedArtifact.contributorship.summary.style` | `Citation.citedArtifact.contributorship.summary.style` | `style` | Citation.citedArtifact.contributorship.summary.style | The format for the display string | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/contributor-summary-style` |
| `Citation.citedArtifact.contributorship.summary.type` | `Citation.citedArtifact.contributorship.summary.type` | `type` | Citation.citedArtifact.contributorship.summary.type | Either authorList or contributorshipStatement | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/contributor-summary-type` |
| `Citation.citedArtifact.contributorship.summary.value` | `Citation.citedArtifact.contributorship.summary.value` | `value` | Citation.citedArtifact.contributorship.summary.value | The display string for the author list, contributor list, or contributorship statement | 1..1 | markdown |  |  |
| `Citation.citedArtifact.currentState` | `Citation.citedArtifact.currentState` | `currentState` | Citation.citedArtifact.currentState | The status of the cited artifact | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/cited-artifact-status-type` |
| `Citation.citedArtifact.dateAccessed` | `Citation.citedArtifact.dateAccessed` | `dateAccessed` | Citation.citedArtifact.dateAccessed | When the cited artifact was accessed | 0..1 | dateTime |  |  |
| `Citation.citedArtifact.extension` | `Citation.citedArtifact.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Citation.citedArtifact.id` | `Citation.citedArtifact.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Citation.citedArtifact.identifier` | `Citation.citedArtifact.identifier` | `identifier` | Citation.citedArtifact.identifier | May include DOI, PMID, PMCID, etc. | 0..* | Identifier |  |  |
| `Citation.citedArtifact.modifierExtension` | `Citation.citedArtifact.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Citation.citedArtifact.note` | `Citation.citedArtifact.note` | `note` | Citation.citedArtifact.note | Any additional information or content for the article or artifact | 0..* | Annotation |  |  |
| `Citation.citedArtifact.part` | `Citation.citedArtifact.part` | `part` | Citation.citedArtifact.part | The component of the article or artifact | 0..1 | BackboneElement |  |  |
| `Citation.citedArtifact.part.baseCitation` | `Citation.citedArtifact.part.baseCitation` | `baseCitation` | Citation.citedArtifact.part.baseCitation | The citation for the full article or artifact | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Citation) |  |  |
| `Citation.citedArtifact.part.extension` | `Citation.citedArtifact.part.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Citation.citedArtifact.part.id` | `Citation.citedArtifact.part.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Citation.citedArtifact.part.modifierExtension` | `Citation.citedArtifact.part.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Citation.citedArtifact.part.type` | `Citation.citedArtifact.part.type` | `type` | Citation.citedArtifact.part.type | The kind of component | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/cited-artifact-part-type` |
| `Citation.citedArtifact.part.value` | `Citation.citedArtifact.part.value` | `value` | Citation.citedArtifact.part.value | The specification of the component | 0..1 | string |  |  |
| `Citation.citedArtifact.publicationForm` | `Citation.citedArtifact.publicationForm` | `publicationForm` | Citation.citedArtifact.publicationForm | If multiple, used to represent alternative forms of the article that are not separate citations | 0..* | BackboneElement |  |  |
| `Citation.citedArtifact.publicationForm.accessionNumber` | `Citation.citedArtifact.publicationForm.accessionNumber` | `accessionNumber` | Citation.citedArtifact.publicationForm.accessionNumber | Entry number or identifier for inclusion in a database | 0..1 | string |  |  |
| `Citation.citedArtifact.publicationForm.articleDate` | `Citation.citedArtifact.publicationForm.articleDate` | `articleDate` | Citation.citedArtifact.publicationForm.articleDate | The date the article was added to the database, or the date the article was released | 0..1 | dateTime |  |  |
| `Citation.citedArtifact.publicationForm.copyright` | `Citation.citedArtifact.publicationForm.copyright` | `copyright` | Citation.citedArtifact.publicationForm.copyright | Copyright notice for the full article or artifact | 0..1 | markdown |  |  |
| `Citation.citedArtifact.publicationForm.extension` | `Citation.citedArtifact.publicationForm.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Citation.citedArtifact.publicationForm.firstPage` | `Citation.citedArtifact.publicationForm.firstPage` | `firstPage` | Citation.citedArtifact.publicationForm.firstPage | Used for isolated representation of first page | 0..1 | string |  |  |
| `Citation.citedArtifact.publicationForm.id` | `Citation.citedArtifact.publicationForm.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Citation.citedArtifact.publicationForm.language` | `Citation.citedArtifact.publicationForm.language` | `language` | Citation.citedArtifact.publicationForm.language | Language in which this form of the article is published | 0..* | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/languages` |
| `Citation.citedArtifact.publicationForm.lastPage` | `Citation.citedArtifact.publicationForm.lastPage` | `lastPage` | Citation.citedArtifact.publicationForm.lastPage | Used for isolated representation of last page | 0..1 | string |  |  |
| `Citation.citedArtifact.publicationForm.lastRevisionDate` | `Citation.citedArtifact.publicationForm.lastRevisionDate` | `lastRevisionDate` | Citation.citedArtifact.publicationForm.lastRevisionDate | The date the article was last revised or updated in the database | 0..1 | dateTime |  |  |
| `Citation.citedArtifact.publicationForm.modifierExtension` | `Citation.citedArtifact.publicationForm.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Citation.citedArtifact.publicationForm.pageCount` | `Citation.citedArtifact.publicationForm.pageCount` | `pageCount` | Citation.citedArtifact.publicationForm.pageCount | Number of pages or screens | 0..1 | string |  |  |
| `Citation.citedArtifact.publicationForm.pageString` | `Citation.citedArtifact.publicationForm.pageString` | `pageString` | Citation.citedArtifact.publicationForm.pageString | Used for full display of pagination | 0..1 | string |  |  |
| `Citation.citedArtifact.publicationForm.periodicRelease` | `Citation.citedArtifact.publicationForm.periodicRelease` | `periodicRelease` | Citation.citedArtifact.publicationForm.periodicRelease | The specific issue in which the cited article resides | 0..1 | BackboneElement |  |  |
| `Citation.citedArtifact.publicationForm.periodicRelease.citedMedium` | `Citation.citedArtifact.publicationForm.periodicRelease.citedMedium` | `citedMedium` | Citation.citedArtifact.publicationForm.periodicRelease.citedMedium | Internet or Print | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/cited-medium` |
| `Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication` | `Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication` | `dateOfPublication` | Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication | Defining the date on which the issue of the journal was published | 0..1 | BackboneElement |  |  |
| `Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.date` | `Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.date` | `date` | Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.date | Date on which the issue of the journal was published | 0..1 | date |  |  |
| `Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.day` | `Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.day` | `day` | Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.day | Day on which the issue of the journal was published | 0..1 | string |  |  |
| `Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.extension` | `Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.id` | `Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.modifierExtension` | `Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.month` | `Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.month` | `month` | Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.month | Month on which the issue of the journal was published | 0..1 | string |  |  |
| `Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.season` | `Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.season` | `season` | Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.season | Season on which the issue of the journal was published | 0..1 | string |  |  |
| `Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.text` | `Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.text` | `text` | Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.text | Text representation of the date of which the issue of the journal was published | 0..1 | string |  |  |
| `Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.year` | `Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.year` | `year` | Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.year | Year on which the issue of the journal was published | 0..1 | string |  |  |
| `Citation.citedArtifact.publicationForm.periodicRelease.extension` | `Citation.citedArtifact.publicationForm.periodicRelease.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Citation.citedArtifact.publicationForm.periodicRelease.id` | `Citation.citedArtifact.publicationForm.periodicRelease.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Citation.citedArtifact.publicationForm.periodicRelease.issue` | `Citation.citedArtifact.publicationForm.periodicRelease.issue` | `issue` | Citation.citedArtifact.publicationForm.periodicRelease.issue | Issue, part or supplement of journal in which the article is published | 0..1 | string |  |  |
| `Citation.citedArtifact.publicationForm.periodicRelease.modifierExtension` | `Citation.citedArtifact.publicationForm.periodicRelease.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Citation.citedArtifact.publicationForm.periodicRelease.volume` | `Citation.citedArtifact.publicationForm.periodicRelease.volume` | `volume` | Citation.citedArtifact.publicationForm.periodicRelease.volume | Volume number of journal in which the article is published | 0..1 | string |  |  |
| `Citation.citedArtifact.publicationForm.publishedIn` | `Citation.citedArtifact.publicationForm.publishedIn` | `publishedIn` | Citation.citedArtifact.publicationForm.publishedIn | The collection the cited article or artifact is published in | 0..1 | BackboneElement |  |  |
| `Citation.citedArtifact.publicationForm.publishedIn.extension` | `Citation.citedArtifact.publicationForm.publishedIn.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Citation.citedArtifact.publicationForm.publishedIn.id` | `Citation.citedArtifact.publicationForm.publishedIn.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Citation.citedArtifact.publicationForm.publishedIn.identifier` | `Citation.citedArtifact.publicationForm.publishedIn.identifier` | `identifier` | Citation.citedArtifact.publicationForm.publishedIn.identifier | Journal identifiers include ISSN, ISO Abbreviation and NLMuniqueID; Book identifiers include ISBN | 0..* | Identifier |  |  |
| `Citation.citedArtifact.publicationForm.publishedIn.modifierExtension` | `Citation.citedArtifact.publicationForm.publishedIn.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Citation.citedArtifact.publicationForm.publishedIn.publisher` | `Citation.citedArtifact.publicationForm.publishedIn.publisher` | `publisher` | Citation.citedArtifact.publicationForm.publishedIn.publisher | Name of the publisher | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Citation.citedArtifact.publicationForm.publishedIn.publisherLocation` | `Citation.citedArtifact.publicationForm.publishedIn.publisherLocation` | `publisherLocation` | Citation.citedArtifact.publicationForm.publishedIn.publisherLocation | Geographic location of the publisher | 0..1 | string |  |  |
| `Citation.citedArtifact.publicationForm.publishedIn.title` | `Citation.citedArtifact.publicationForm.publishedIn.title` | `title` | Citation.citedArtifact.publicationForm.publishedIn.title | Name of the database or title of the book or journal | 0..1 | string |  |  |
| `Citation.citedArtifact.publicationForm.publishedIn.type` | `Citation.citedArtifact.publicationForm.publishedIn.type` | `type` | Citation.citedArtifact.publicationForm.publishedIn.type | Kind of container (e.g. Periodical, database, or book) | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/published-in-type` |
| `Citation.citedArtifact.relatedIdentifier` | `Citation.citedArtifact.relatedIdentifier` | `relatedIdentifier` | Citation.citedArtifact.relatedIdentifier | May include trial registry identifiers | 0..* | Identifier |  |  |
| `Citation.citedArtifact.relatesTo` | `Citation.citedArtifact.relatesTo` | `relatesTo` | Citation.citedArtifact.relatesTo | The artifact related to the cited artifact | 0..* | BackboneElement |  |  |
| `Citation.citedArtifact.relatesTo.extension` | `Citation.citedArtifact.relatesTo.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Citation.citedArtifact.relatesTo.id` | `Citation.citedArtifact.relatesTo.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Citation.citedArtifact.relatesTo.modifierExtension` | `Citation.citedArtifact.relatesTo.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Citation.citedArtifact.relatesTo.relationshipType` | `Citation.citedArtifact.relatesTo.relationshipType` | `relationshipType` | Citation.citedArtifact.relatesTo.relationshipType | How the cited artifact relates to the target artifact | 1..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/artifact-relationship-type` |
| `Citation.citedArtifact.relatesTo.targetClassifier` | `Citation.citedArtifact.relatesTo.targetClassifier` | `targetClassifier` | Citation.citedArtifact.relatesTo.targetClassifier | The clasification of the related artifact | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/citation-artifact-classifier` |
| `Citation.citedArtifact.relatesTo.target[x]` | `Citation.citedArtifact.relatesTo.target[x]` | `target[x]` | Citation.citedArtifact.relatesTo.target[x] | The article or artifact that the cited artifact is related to | 1..1 | Attachment, Identifier, Reference(http://hl7.org/fhir/StructureDefinition/Resource), uri |  |  |
| `Citation.citedArtifact.statusDate` | `Citation.citedArtifact.statusDate` | `statusDate` | Citation.citedArtifact.statusDate | An effective date or period for a status of the cited artifact | 0..* | BackboneElement |  |  |
| `Citation.citedArtifact.statusDate.activity` | `Citation.citedArtifact.statusDate.activity` | `activity` | Citation.citedArtifact.statusDate.activity | Classification of the status | 1..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/cited-artifact-status-type` |
| `Citation.citedArtifact.statusDate.actual` | `Citation.citedArtifact.statusDate.actual` | `actual` | Citation.citedArtifact.statusDate.actual | Either occurred or expected | 0..1 | boolean |  |  |
| `Citation.citedArtifact.statusDate.extension` | `Citation.citedArtifact.statusDate.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Citation.citedArtifact.statusDate.id` | `Citation.citedArtifact.statusDate.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Citation.citedArtifact.statusDate.modifierExtension` | `Citation.citedArtifact.statusDate.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Citation.citedArtifact.statusDate.period` | `Citation.citedArtifact.statusDate.period` | `period` | Citation.citedArtifact.statusDate.period | When the status started and/or ended | 1..1 | Period |  |  |
| `Citation.citedArtifact.title` | `Citation.citedArtifact.title` | `title` | Citation.citedArtifact.title | The title details of the article or artifact | 0..* | BackboneElement |  |  |
| `Citation.citedArtifact.title.extension` | `Citation.citedArtifact.title.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Citation.citedArtifact.title.id` | `Citation.citedArtifact.title.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Citation.citedArtifact.title.language` | `Citation.citedArtifact.title.language` | `language` | Citation.citedArtifact.title.language | Used to express the specific language | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/languages` |
| `Citation.citedArtifact.title.modifierExtension` | `Citation.citedArtifact.title.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Citation.citedArtifact.title.text` | `Citation.citedArtifact.title.text` | `text` | Citation.citedArtifact.title.text | The title of the article or artifact | 1..1 | markdown |  |  |
| `Citation.citedArtifact.title.type` | `Citation.citedArtifact.title.type` | `type` | Citation.citedArtifact.title.type | The kind of title | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/title-type` |
| `Citation.citedArtifact.version` | `Citation.citedArtifact.version` | `version` | Citation.citedArtifact.version | The defined version of the cited artifact | 0..1 | BackboneElement |  |  |
| `Citation.citedArtifact.version.baseCitation` | `Citation.citedArtifact.version.baseCitation` | `baseCitation` | Citation.citedArtifact.version.baseCitation | Citation for the main version of the cited artifact | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Citation) |  |  |
| `Citation.citedArtifact.version.extension` | `Citation.citedArtifact.version.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Citation.citedArtifact.version.id` | `Citation.citedArtifact.version.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Citation.citedArtifact.version.modifierExtension` | `Citation.citedArtifact.version.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Citation.citedArtifact.version.value` | `Citation.citedArtifact.version.value` | `value` | Citation.citedArtifact.version.value | The version number or other version identifier | 1..1 | string |  |  |
| `Citation.citedArtifact.webLocation` | `Citation.citedArtifact.webLocation` | `webLocation` | Citation.citedArtifact.webLocation | Used for any URL for the article or artifact cited | 0..* | BackboneElement |  |  |
| `Citation.citedArtifact.webLocation.extension` | `Citation.citedArtifact.webLocation.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Citation.citedArtifact.webLocation.id` | `Citation.citedArtifact.webLocation.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Citation.citedArtifact.webLocation.modifierExtension` | `Citation.citedArtifact.webLocation.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Citation.citedArtifact.webLocation.type` | `Citation.citedArtifact.webLocation.type` | `type` | Citation.citedArtifact.webLocation.type | Code the reason for different URLs, e.g. abstract and full-text | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/article-url-type` |
| `Citation.citedArtifact.webLocation.url` | `Citation.citedArtifact.webLocation.url` | `url` | Citation.citedArtifact.webLocation.url | The specific URL | 0..1 | uri |  |  |
| `Citation.classification` | `Citation.classification` | `classification` | Citation.classification | The assignment to an organizing scheme | 0..* | BackboneElement |  |  |
| `Citation.classification.classifier` | `Citation.classification.classifier` | `classifier` | Citation.classification.classifier | The specific classification value | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/citation-artifact-classifier` |
| `Citation.classification.extension` | `Citation.classification.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Citation.classification.id` | `Citation.classification.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Citation.classification.modifierExtension` | `Citation.classification.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Citation.classification.type` | `Citation.classification.type` | `type` | Citation.classification.type | The kind of classifier (e.g. publication type, keyword) | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/citation-classification-type` |
| `Citation.contact` | `Citation.contact` | `contact` | Citation.contact | Contact details for the publisher of the Citation Resource | 0..* | ContactDetail |  |  |
| `Citation.contained` | `Citation.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Citation.copyright` | `Citation.copyright` | `copyright` | Citation.copyright | Use and/or publishing restrictions for the Citation, not for the cited artifact | 0..1 | markdown |  |  |
| `Citation.currentState` | `Citation.currentState` | `currentState` | Citation.currentState | The status of the citation | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/citation-status-type` |
| `Citation.date` | `Citation.date` | `date` | Citation.date | Date last changed | 0..1 | dateTime |  |  |
| `Citation.description` | `Citation.description` | `description` | Citation.description | Natural language description of the citation | 0..1 | markdown |  |  |
| `Citation.editor` | `Citation.editor` | `editor` | Citation.editor | Who edited the Citation | 0..* | ContactDetail |  |  |
| `Citation.effectivePeriod` | `Citation.effectivePeriod` | `effectivePeriod` | Citation.effectivePeriod | When the citation is expected to be used | 0..1 | Period |  |  |
| `Citation.endorser` | `Citation.endorser` | `endorser` | Citation.endorser | Who endorsed the Citation | 0..* | ContactDetail |  |  |
| `Citation.experimental` | `Citation.experimental` | `experimental` | Citation.experimental | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `Citation.extension` | `Citation.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Citation.id` | `Citation.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Citation.identifier` | `Citation.identifier` | `identifier` | Citation.identifier | Identifier for the Citation resource itself | 0..* | Identifier |  |  |
| `Citation.implicitRules` | `Citation.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Citation.jurisdiction` | `Citation.jurisdiction` | `jurisdiction` | Citation.jurisdiction | Intended jurisdiction for citation (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `Citation.language` | `Citation.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `Citation.lastReviewDate` | `Citation.lastReviewDate` | `lastReviewDate` | Citation.lastReviewDate | When the citation was last reviewed | 0..1 | date |  |  |
| `Citation.meta` | `Citation.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Citation.modifierExtension` | `Citation.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Citation.name` | `Citation.name` | `name` | Citation.name | Name for this citation (computer friendly) | 0..1 | string |  |  |
| `Citation.note` | `Citation.note` | `note` | Citation.note | Used for general notes and annotations not coded elsewhere | 0..* | Annotation |  |  |
| `Citation.publisher` | `Citation.publisher` | `publisher` | Citation.publisher | The publisher of the Citation, not the publisher of the article or artifact being cited | 0..1 | string |  |  |
| `Citation.purpose` | `Citation.purpose` | `purpose` | Citation.purpose | Why this citation is defined | 0..1 | markdown |  |  |
| `Citation.relatesTo` | `Citation.relatesTo` | `relatesTo` | Citation.relatesTo | Artifact related to the Citation Resource | 0..* | BackboneElement |  |  |
| `Citation.relatesTo.extension` | `Citation.relatesTo.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Citation.relatesTo.id` | `Citation.relatesTo.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Citation.relatesTo.modifierExtension` | `Citation.relatesTo.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Citation.relatesTo.relationshipType` | `Citation.relatesTo.relationshipType` | `relationshipType` | Citation.relatesTo.relationshipType | How the Citation resource relates to the target artifact | 1..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/artifact-relationship-type` |
| `Citation.relatesTo.targetClassifier` | `Citation.relatesTo.targetClassifier` | `targetClassifier` | Citation.relatesTo.targetClassifier | The clasification of the related artifact | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/citation-artifact-classifier` |
| `Citation.relatesTo.target[x]` | `Citation.relatesTo.target[x]` | `target[x]` | Citation.relatesTo.target[x] | The article or artifact that the Citation Resource is related to | 1..1 | Attachment, Identifier, Reference(http://hl7.org/fhir/StructureDefinition/Resource), uri |  |  |
| `Citation.reviewer` | `Citation.reviewer` | `reviewer` | Citation.reviewer | Who reviewed the Citation | 0..* | ContactDetail |  |  |
| `Citation.status` | `Citation.status` | `status` | Citation.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|4.3.0` |
| `Citation.statusDate` | `Citation.statusDate` | `statusDate` | Citation.statusDate | An effective date or period for a status of the citation | 0..* | BackboneElement |  |  |
| `Citation.statusDate.activity` | `Citation.statusDate.activity` | `activity` | Citation.statusDate.activity | Classification of the status | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/citation-status-type` |
| `Citation.statusDate.actual` | `Citation.statusDate.actual` | `actual` | Citation.statusDate.actual | Either occurred or expected | 0..1 | boolean |  |  |
| `Citation.statusDate.extension` | `Citation.statusDate.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Citation.statusDate.id` | `Citation.statusDate.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Citation.statusDate.modifierExtension` | `Citation.statusDate.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Citation.statusDate.period` | `Citation.statusDate.period` | `period` | Citation.statusDate.period | When the status started and/or ended | 1..1 | Period |  |  |
| `Citation.summary` | `Citation.summary` | `summary` | Citation.summary | A human-readable display of the citation | 0..* | BackboneElement |  |  |
| `Citation.summary.extension` | `Citation.summary.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Citation.summary.id` | `Citation.summary.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Citation.summary.modifierExtension` | `Citation.summary.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Citation.summary.style` | `Citation.summary.style` | `style` | Citation.summary.style | Format for display of the citation | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/citation-summary-style` |
| `Citation.summary.text` | `Citation.summary.text` | `text` | Citation.summary.text | The human-readable display of the citation | 1..1 | markdown |  |  |
| `Citation.text` | `Citation.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Citation.title` | `Citation.title` | `title` | Citation.title | Name for this citation (human friendly) | 0..1 | string |  |  |
| `Citation.url` | `Citation.url` | `url` | Citation.url | Canonical identifier for this citation, represented as a globally unique URI | 0..1 | uri |  |  |
| `Citation.useContext` | `Citation.useContext` | `useContext` | Citation.useContext | The context that the Citation Resource content is intended to support | 0..* | UsageContext |  |  |
| `Citation.version` | `Citation.version` | `version` | Citation.version | Business version of the citation | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [Citation](/docs/R4B/Resources/Citation.md)<br/> `http://hl7.org/fhir/StructureDefinition/Citation\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `944`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1173`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Citation](/docs/R5/Resources/Citation.md)<br/> `http://hl7.org/fhir/StructureDefinition/Citation\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Citation from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | R4B Citation| Relationship | [R5 Citation](/docs/R5/Resources/Citation.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | **`Citation`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(37854)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(37855)| `Citation`
| | | | | | | **`Citation.id`**| _Equivalent_<br/>(37856/37857)| `Citation.id`
| | | | | | | **`Citation.meta`**| _Equivalent_<br/>(37858/37859)| `Citation.meta`
| | | | | | | **`Citation.implicitRules`**| _Equivalent_<br/>(37860/37861)| `Citation.implicitRules`
| | | | | | | **`Citation.language`**| _Equivalent_<br/>(37862/37863)| `Citation.language`
| | | | | | | **`Citation.text`**| _Equivalent_<br/>(37864/37865)| `Citation.text`
| | | | | | | **`Citation.contained`**| _Equivalent_<br/>(37866/37867)| `Citation.contained`
| | | | | | | **`Citation.extension`**| _Equivalent_<br/>(37868/37869)| `Citation.extension`
| | | | | | | **`Citation.modifierExtension`**| _Equivalent_<br/>(37870/37871)| `Citation.modifierExtension`
| | | | | | | **`Citation.url`**| _Equivalent_<br/>(37872/37873)| `Citation.url`
| | | | | | | **`Citation.identifier`**| _Equivalent_<br/>(37874/37875)| `Citation.identifier`
| | | | | | | **`Citation.version`**| _Equivalent_<br/>(37876/37877)| `Citation.version`
| | | | | | | **`Citation.name`**| _Equivalent_<br/>(37878/37879)| `Citation.name`
| | | | | | | **`Citation.title`**| _Equivalent_<br/>(37880/37881)| `Citation.title`
| | | | | | | **`Citation.status`**| _Equivalent_<br/>(37882/37883)| `Citation.status`
| | | | | | | **`Citation.experimental`**| _Equivalent_<br/>(37884/37885)| `Citation.experimental`
| | | | | | | **`Citation.date`**| _Equivalent_<br/>(37886/37887)| `Citation.date`
| | | | | | | **`Citation.publisher`**| _Equivalent_<br/>(37888/37889)| `Citation.publisher`
| | | | | | | **`Citation.contact`**| _Equivalent_<br/>(37890/37891)| `Citation.contact`
| | | | | | | **`Citation.description`**| _Equivalent_<br/>(37892/37893)| `Citation.description`
| | | | | | | **`Citation.useContext`**| _Equivalent_<br/>(37894/37895)| `Citation.useContext`
| | | | | | | **`Citation.jurisdiction`**| _Equivalent_<br/>(37896/37897)| `Citation.jurisdiction`
| | | | | | | **`Citation.purpose`**| _Equivalent_<br/>(37898/37899)| `Citation.purpose`
| | | | | | | **`Citation.copyright`**| _Equivalent_<br/>(37900/37901)| `Citation.copyright`
| | | | | | | **`Citation.approvalDate`**| _Equivalent_<br/>(37902/37903)| `Citation.approvalDate`
| | | | | | | **`Citation.lastReviewDate`**| _Equivalent_<br/>(37904/37905)| `Citation.lastReviewDate`
| | | | | | | **`Citation.effectivePeriod`**| _Equivalent_<br/>(37906/37907)| `Citation.effectivePeriod`
| | | | | | | **`Citation.author`**| _Equivalent_<br/>(37908/37909)| `Citation.author`
| | | | | | | **`Citation.editor`**| _Equivalent_<br/>(37910/37911)| `Citation.editor`
| | | | | | | **`Citation.reviewer`**| _Equivalent_<br/>(37912/37913)| `Citation.reviewer`
| | | | | | | **`Citation.endorser`**| _Equivalent_<br/>(37914/37915)| `Citation.endorser`
| | | | | | | **`Citation.summary`**| _Equivalent_<br/>(37916/37917)| `Citation.summary`
| | | | | | | **`Citation.summary.id`**| _Equivalent_<br/>(37918/37919)| `Citation.summary.id`
| | | | | | | **`Citation.summary.extension`**| _Equivalent_<br/>(37920/37921)| `Citation.summary.extension`
| | | | | | | **`Citation.summary.modifierExtension`**| _Equivalent_<br/>(37922/37923)| `Citation.summary.modifierExtension`
| | | | | | | **`Citation.summary.style`**| _Equivalent_<br/>(37924/37925)| `Citation.summary.style`
| | | | | | | **`Citation.summary.text`**| _Equivalent_<br/>(37926/37927)| `Citation.summary.text`
| | | | | | | **`Citation.classification`**| _Equivalent_<br/>(37928/37929)| `Citation.classification`
| | | | | | | **`Citation.classification.id`**| _Equivalent_<br/>(37930/37931)| `Citation.classification.id`
| | | | | | | **`Citation.classification.extension`**| _Equivalent_<br/>(37932/37933)| `Citation.classification.extension`
| | | | | | | **`Citation.classification.modifierExtension`**| _Equivalent_<br/>(37934/37935)| `Citation.classification.modifierExtension`
| | | | | | | **`Citation.classification.type`**| _Equivalent_<br/>(37936/37937)| `Citation.classification.type`
| | | | | | | **`Citation.classification.classifier`**| _Equivalent_<br/>(37938/37939)| `Citation.classification.classifier`
| | | | | | | **`Citation.note`**| _Equivalent_<br/>(37940/37941)| `Citation.note`
| | | | | | | **`Citation.currentState`**| _Equivalent_<br/>(37942/37943)| `Citation.currentState`
| | | | | | | **`Citation.statusDate`**| _Equivalent_<br/>(37944/37945)| `Citation.statusDate`
| | | | | | | **`Citation.statusDate.id`**| _Equivalent_<br/>(37946/37947)| `Citation.statusDate.id`
| | | | | | | **`Citation.statusDate.extension`**| _Equivalent_<br/>(37948/37949)| `Citation.statusDate.extension`
| | | | | | | **`Citation.statusDate.modifierExtension`**| _Equivalent_<br/>(37950/37951)| `Citation.statusDate.modifierExtension`
| | | | | | | **`Citation.statusDate.activity`**| _Equivalent_<br/>(37952/37953)| `Citation.statusDate.activity`
| | | | | | | **`Citation.statusDate.actual`**| _Equivalent_<br/>(37954/37955)| `Citation.statusDate.actual`
| | | | | | | **`Citation.statusDate.period`**| _Equivalent_<br/>(37956/37957)| `Citation.statusDate.period`
| | | | | | | **`Citation.relatesTo`**| | | 
| | | | | | | **`Citation.relatesTo.id`**| | | 
| | | | | | | **`Citation.relatesTo.extension`**| | | 
| | | | | | | **`Citation.relatesTo.modifierExtension`**| | | 
| | | | | | | **`Citation.relatesTo.relationshipType`**| | | 
| | | | | | | **`Citation.relatesTo.targetClassifier`**| | | 
| | | | | | | **`Citation.relatesTo.target[x]`**| | | 
| | | | | | | **`Citation.citedArtifact`**| _Equivalent_<br/>(37965/37966)| `Citation.citedArtifact`
| | | | | | | **`Citation.citedArtifact.id`**| _Equivalent_<br/>(37967/37968)| `Citation.citedArtifact.id`
| | | | | | | **`Citation.citedArtifact.extension`**| _Equivalent_<br/>(37969/37970)| `Citation.citedArtifact.extension`
| | | | | | | **`Citation.citedArtifact.modifierExtension`**| _Equivalent_<br/>(37971/37972)| `Citation.citedArtifact.modifierExtension`
| | | | | | | **`Citation.citedArtifact.identifier`**| _Equivalent_<br/>(37973/37974)| `Citation.citedArtifact.identifier`
| | | | | | | **`Citation.citedArtifact.relatedIdentifier`**| _Equivalent_<br/>(37975/37976)| `Citation.citedArtifact.relatedIdentifier`
| | | | | | | **`Citation.citedArtifact.dateAccessed`**| _Equivalent_<br/>(37977/37978)| `Citation.citedArtifact.dateAccessed`
| | | | | | | **`Citation.citedArtifact.version`**| _Equivalent_<br/>(37979/37980)| `Citation.citedArtifact.version`
| | | | | | | **`Citation.citedArtifact.version.id`**| _Equivalent_<br/>(37981/37982)| `Citation.citedArtifact.version.id`
| | | | | | | **`Citation.citedArtifact.version.extension`**| _Equivalent_<br/>(37983/37984)| `Citation.citedArtifact.version.extension`
| | | | | | | **`Citation.citedArtifact.version.modifierExtension`**| _Equivalent_<br/>(37985/37986)| `Citation.citedArtifact.version.modifierExtension`
| | | | | | | **`Citation.citedArtifact.version.value`**| _Equivalent_<br/>(37987/37988)| `Citation.citedArtifact.version.value`
| | | | | | | **`Citation.citedArtifact.version.baseCitation`**| _Equivalent_<br/>(37989/37990)| `Citation.citedArtifact.version.baseCitation`
| | | | | | | **`Citation.citedArtifact.currentState`**| _Equivalent_<br/>(37991/37992)| `Citation.citedArtifact.currentState`
| | | | | | | **`Citation.citedArtifact.statusDate`**| _Equivalent_<br/>(37993/37994)| `Citation.citedArtifact.statusDate`
| | | | | | | **`Citation.citedArtifact.statusDate.id`**| _Equivalent_<br/>(37995/37996)| `Citation.citedArtifact.statusDate.id`
| | | | | | | **`Citation.citedArtifact.statusDate.extension`**| _Equivalent_<br/>(37997/37998)| `Citation.citedArtifact.statusDate.extension`
| | | | | | | **`Citation.citedArtifact.statusDate.modifierExtension`**| _Equivalent_<br/>(37999/38000)| `Citation.citedArtifact.statusDate.modifierExtension`
| | | | | | | **`Citation.citedArtifact.statusDate.activity`**| _Equivalent_<br/>(38001/38002)| `Citation.citedArtifact.statusDate.activity`
| | | | | | | **`Citation.citedArtifact.statusDate.actual`**| _Equivalent_<br/>(38003/38004)| `Citation.citedArtifact.statusDate.actual`
| | | | | | | **`Citation.citedArtifact.statusDate.period`**| _Equivalent_<br/>(38005/38006)| `Citation.citedArtifact.statusDate.period`
| | | | | | | **`Citation.citedArtifact.title`**| _Equivalent_<br/>(38007/38008)| `Citation.citedArtifact.title`
| | | | | | | **`Citation.citedArtifact.title.id`**| _Equivalent_<br/>(38009/38010)| `Citation.citedArtifact.title.id`
| | | | | | | **`Citation.citedArtifact.title.extension`**| _Equivalent_<br/>(38011/38012)| `Citation.citedArtifact.title.extension`
| | | | | | | **`Citation.citedArtifact.title.modifierExtension`**| _Equivalent_<br/>(38013/38014)| `Citation.citedArtifact.title.modifierExtension`
| | | | | | | **`Citation.citedArtifact.title.type`**| _Equivalent_<br/>(38015/38016)| `Citation.citedArtifact.title.type`
| | | | | | | **`Citation.citedArtifact.title.language`**| _Equivalent_<br/>(38017/38018)| `Citation.citedArtifact.title.language`
| | | | | | | **`Citation.citedArtifact.title.text`**| _Equivalent_<br/>(38019/38020)| `Citation.citedArtifact.title.text`
| | | | | | | **`Citation.citedArtifact.abstract`**| _Equivalent_<br/>(38021/38022)| `Citation.citedArtifact.abstract`
| | | | | | | **`Citation.citedArtifact.abstract.id`**| _Equivalent_<br/>(38023/38024)| `Citation.citedArtifact.abstract.id`
| | | | | | | **`Citation.citedArtifact.abstract.extension`**| _Equivalent_<br/>(38025/38026)| `Citation.citedArtifact.abstract.extension`
| | | | | | | **`Citation.citedArtifact.abstract.modifierExtension`**| _Equivalent_<br/>(38027/38028)| `Citation.citedArtifact.abstract.modifierExtension`
| | | | | | | **`Citation.citedArtifact.abstract.type`**| _Equivalent_<br/>(38029/38030)| `Citation.citedArtifact.abstract.type`
| | | | | | | **`Citation.citedArtifact.abstract.language`**| _Equivalent_<br/>(38031/38032)| `Citation.citedArtifact.abstract.language`
| | | | | | | **`Citation.citedArtifact.abstract.text`**| _Equivalent_<br/>(38033/38034)| `Citation.citedArtifact.abstract.text`
| | | | | | | **`Citation.citedArtifact.abstract.copyright`**| _Equivalent_<br/>(38035/38036)| `Citation.citedArtifact.abstract.copyright`
| | | | | | | **`Citation.citedArtifact.part`**| _Equivalent_<br/>(38037/38038)| `Citation.citedArtifact.part`
| | | | | | | **`Citation.citedArtifact.part.id`**| _Equivalent_<br/>(38039/38040)| `Citation.citedArtifact.part.id`
| | | | | | | **`Citation.citedArtifact.part.extension`**| _Equivalent_<br/>(38041/38042)| `Citation.citedArtifact.part.extension`
| | | | | | | **`Citation.citedArtifact.part.modifierExtension`**| _Equivalent_<br/>(38043/38044)| `Citation.citedArtifact.part.modifierExtension`
| | | | | | | **`Citation.citedArtifact.part.type`**| _Equivalent_<br/>(38045/38046)| `Citation.citedArtifact.part.type`
| | | | | | | **`Citation.citedArtifact.part.value`**| _Equivalent_<br/>(38047/38048)| `Citation.citedArtifact.part.value`
| | | | | | | **`Citation.citedArtifact.part.baseCitation`**| _Equivalent_<br/>(38049/38050)| `Citation.citedArtifact.part.baseCitation`
| | | | | | | **`Citation.citedArtifact.relatesTo`**| _Equivalent_<br/>(38051/38052)| `Citation.citedArtifact.relatesTo`
| | | | | | | **`Citation.citedArtifact.relatesTo.id`**| _Equivalent_<br/>(38053/38054)| `Citation.citedArtifact.relatesTo.id`
| | | | | | | **`Citation.citedArtifact.relatesTo.extension`**| _Equivalent_<br/>(38055/38056)| `Citation.citedArtifact.relatesTo.extension`
| | | | | | | **`Citation.citedArtifact.relatesTo.modifierExtension`**| _Equivalent_<br/>(38057/38058)| `Citation.citedArtifact.relatesTo.modifierExtension`
| | | | | | | **`Citation.citedArtifact.relatesTo.relationshipType`**| →→→→ _Equivalent_ →→→→ <br/>(49931)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2100)| `base64Binary`
| | | | | | | **`Citation.citedArtifact.relatesTo.relationshipType`**| →→→→ _Equivalent_ →→→→ <br/>(49931)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2100)| `Citation.citedArtifact.relatesTo.type`
| | | | | | | **`Citation.citedArtifact.relatesTo.targetClassifier`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1858)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2101)| `Citation.citedArtifact.relatesTo.classifier`
| | | | | | | **`Citation.citedArtifact.relatesTo.target[x]`**| →→→→ _RelatedTo_ →→→→ <br/>(1859)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2102)| `Citation.citedArtifact.relatesTo.resourceReference`
| | | | | | | **`Citation.citedArtifact.publicationForm`**| _Equivalent_<br/>(38060/38061)| `Citation.citedArtifact.publicationForm`
| | | | | | | **`Citation.citedArtifact.publicationForm.id`**| _Equivalent_<br/>(38062/38063)| `Citation.citedArtifact.publicationForm.id`
| | | | | | | **`Citation.citedArtifact.publicationForm.extension`**| _Equivalent_<br/>(38064/38065)| `Citation.citedArtifact.publicationForm.extension`
| | | | | | | **`Citation.citedArtifact.publicationForm.modifierExtension`**| _Equivalent_<br/>(38066/38067)| `Citation.citedArtifact.publicationForm.modifierExtension`
| | | | | | | **`Citation.citedArtifact.publicationForm.publishedIn`**| _Equivalent_<br/>(38068/38069)| `Citation.citedArtifact.publicationForm.publishedIn`
| | | | | | | **`Citation.citedArtifact.publicationForm.publishedIn.id`**| _Equivalent_<br/>(38070/38071)| `Citation.citedArtifact.publicationForm.publishedIn.id`
| | | | | | | **`Citation.citedArtifact.publicationForm.publishedIn.extension`**| _Equivalent_<br/>(38072/38073)| `Citation.citedArtifact.publicationForm.publishedIn.extension`
| | | | | | | **`Citation.citedArtifact.publicationForm.publishedIn.modifierExtension`**| _Equivalent_<br/>(38074/38075)| `Citation.citedArtifact.publicationForm.publishedIn.modifierExtension`
| | | | | | | **`Citation.citedArtifact.publicationForm.publishedIn.type`**| _Equivalent_<br/>(38076/38077)| `Citation.citedArtifact.publicationForm.publishedIn.type`
| | | | | | | **`Citation.citedArtifact.publicationForm.publishedIn.identifier`**| _Equivalent_<br/>(38078/38079)| `Citation.citedArtifact.publicationForm.publishedIn.identifier`
| | | | | | | **`Citation.citedArtifact.publicationForm.publishedIn.title`**| _Equivalent_<br/>(38080/38081)| `Citation.citedArtifact.publicationForm.publishedIn.title`
| | | | | | | **`Citation.citedArtifact.publicationForm.publishedIn.publisher`**| _Equivalent_<br/>(38082/38083)| `Citation.citedArtifact.publicationForm.publishedIn.publisher`
| | | | | | | **`Citation.citedArtifact.publicationForm.publishedIn.publisherLocation`**| _Equivalent_<br/>(38084/38085)| `Citation.citedArtifact.publicationForm.publishedIn.publisherLocation`
| | | | | | | **`Citation.citedArtifact.publicationForm.periodicRelease`**| | | 
| | | | | | | **`Citation.citedArtifact.publicationForm.periodicRelease.id`**| | | 
| | | | | | | **`Citation.citedArtifact.publicationForm.periodicRelease.extension`**| | | 
| | | | | | | **`Citation.citedArtifact.publicationForm.periodicRelease.modifierExtension`**| | | 
| | | | | | | **`Citation.citedArtifact.publicationForm.periodicRelease.citedMedium`**| | | 
| | | | | | | **`Citation.citedArtifact.publicationForm.periodicRelease.volume`**| | | 
| | | | | | | **`Citation.citedArtifact.publicationForm.periodicRelease.issue`**| | | 
| | | | | | | **`Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication`**| | | 
| | | | | | | **`Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.id`**| | | 
| | | | | | | **`Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.extension`**| | | 
| | | | | | | **`Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.modifierExtension`**| | | 
| | | | | | | **`Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.date`**| | | 
| | | | | | | **`Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.year`**| | | 
| | | | | | | **`Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.month`**| | | 
| | | | | | | **`Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.day`**| | | 
| | | | | | | **`Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.season`**| | | 
| | | | | | | **`Citation.citedArtifact.publicationForm.periodicRelease.dateOfPublication.text`**| | | 
| | | | | | | **`Citation.citedArtifact.publicationForm.articleDate`**| _Equivalent_<br/>(38103/38104)| `Citation.citedArtifact.publicationForm.articleDate`
| | | | | | | **`Citation.citedArtifact.publicationForm.lastRevisionDate`**| _Equivalent_<br/>(38105/38106)| `Citation.citedArtifact.publicationForm.lastRevisionDate`
| | | | | | | **`Citation.citedArtifact.publicationForm.language`**| _Equivalent_<br/>(38107/38108)| `Citation.citedArtifact.publicationForm.language`
| | | | | | | **`Citation.citedArtifact.publicationForm.accessionNumber`**| _Equivalent_<br/>(38109/38110)| `Citation.citedArtifact.publicationForm.accessionNumber`
| | | | | | | **`Citation.citedArtifact.publicationForm.pageString`**| _Equivalent_<br/>(38111/38112)| `Citation.citedArtifact.publicationForm.pageString`
| | | | | | | **`Citation.citedArtifact.publicationForm.firstPage`**| _Equivalent_<br/>(38113/38114)| `Citation.citedArtifact.publicationForm.firstPage`
| | | | | | | **`Citation.citedArtifact.publicationForm.lastPage`**| _Equivalent_<br/>(38115/38116)| `Citation.citedArtifact.publicationForm.lastPage`
| | | | | | | **`Citation.citedArtifact.publicationForm.pageCount`**| _Equivalent_<br/>(38117/38118)| `Citation.citedArtifact.publicationForm.pageCount`
| | | | | | | **`Citation.citedArtifact.publicationForm.copyright`**| _Equivalent_<br/>(38119/38120)| `Citation.citedArtifact.publicationForm.copyright`
| | | | | | | **`Citation.citedArtifact.webLocation`**| _Equivalent_<br/>(38121/38122)| `Citation.citedArtifact.webLocation`
| | | | | | | **`Citation.citedArtifact.webLocation.id`**| _Equivalent_<br/>(38123/38124)| `Citation.citedArtifact.webLocation.id`
| | | | | | | **`Citation.citedArtifact.webLocation.extension`**| _Equivalent_<br/>(38125/38126)| `Citation.citedArtifact.webLocation.extension`
| | | | | | | **`Citation.citedArtifact.webLocation.modifierExtension`**| _Equivalent_<br/>(38127/38128)| `Citation.citedArtifact.webLocation.modifierExtension`
| | | | | | | **`Citation.citedArtifact.webLocation.type`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1860)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2103)| `Citation.citedArtifact.webLocation.classifier`
| | | | | | | **`Citation.citedArtifact.webLocation.url`**| _Equivalent_<br/>(38129/38130)| `Citation.citedArtifact.webLocation.url`
| | | | | | | **`Citation.citedArtifact.classification`**| _Equivalent_<br/>(38131/38132)| `Citation.citedArtifact.classification`
| | | | | | | **`Citation.citedArtifact.classification.id`**| _Equivalent_<br/>(38133/38134)| `Citation.citedArtifact.classification.id`
| | | | | | | **`Citation.citedArtifact.classification.extension`**| _Equivalent_<br/>(38135/38136)| `Citation.citedArtifact.classification.extension`
| | | | | | | **`Citation.citedArtifact.classification.modifierExtension`**| _Equivalent_<br/>(38137/38138)| `Citation.citedArtifact.classification.modifierExtension`
| | | | | | | **`Citation.citedArtifact.classification.type`**| _Equivalent_<br/>(38139/38140)| `Citation.citedArtifact.classification.type`
| | | | | | | **`Citation.citedArtifact.classification.classifier`**| _Equivalent_<br/>(38141/38142)| `Citation.citedArtifact.classification.classifier`
| | | | | | | **`Citation.citedArtifact.classification.whoClassified`**| | | 
| | | | | | | **`Citation.citedArtifact.classification.whoClassified.id`**| | | 
| | | | | | | **`Citation.citedArtifact.classification.whoClassified.extension`**| | | 
| | | | | | | **`Citation.citedArtifact.classification.whoClassified.modifierExtension`**| | | 
| | | | | | | **`Citation.citedArtifact.classification.whoClassified.person`**| | | 
| | | | | | | **`Citation.citedArtifact.classification.whoClassified.organization`**| | | 
| | | | | | | **`Citation.citedArtifact.classification.whoClassified.publisher`**| | | 
| | | | | | | **`Citation.citedArtifact.classification.whoClassified.classifierCopyright`**| | | 
| | | | | | | **`Citation.citedArtifact.classification.whoClassified.freeToShare`**| | | 
| | | | | | | **`Citation.citedArtifact.contributorship`**| _Equivalent_<br/>(38152/38153)| `Citation.citedArtifact.contributorship`
| | | | | | | **`Citation.citedArtifact.contributorship.id`**| _Equivalent_<br/>(38154/38155)| `Citation.citedArtifact.contributorship.id`
| | | | | | | **`Citation.citedArtifact.contributorship.extension`**| _Equivalent_<br/>(38156/38157)| `Citation.citedArtifact.contributorship.extension`
| | | | | | | **`Citation.citedArtifact.contributorship.modifierExtension`**| _Equivalent_<br/>(38158/38159)| `Citation.citedArtifact.contributorship.modifierExtension`
| | | | | | | **`Citation.citedArtifact.contributorship.complete`**| _Equivalent_<br/>(38160/38161)| `Citation.citedArtifact.contributorship.complete`
| | | | | | | **`Citation.citedArtifact.contributorship.entry`**| _Equivalent_<br/>(38162/38163)| `Citation.citedArtifact.contributorship.entry`
| | | | | | | **`Citation.citedArtifact.contributorship.entry.id`**| _Equivalent_<br/>(38164/38165)| `Citation.citedArtifact.contributorship.entry.id`
| | | | | | | **`Citation.citedArtifact.contributorship.entry.extension`**| _Equivalent_<br/>(38166/38167)| `Citation.citedArtifact.contributorship.entry.extension`
| | | | | | | **`Citation.citedArtifact.contributorship.entry.modifierExtension`**| _Equivalent_<br/>(38168/38169)| `Citation.citedArtifact.contributorship.entry.modifierExtension`
| | | | | | | **`Citation.citedArtifact.contributorship.entry.name`**| | | 
| | | | | | | **`Citation.citedArtifact.contributorship.entry.initials`**| _Equivalent_<br/>(1861/2104)| `Citation.citedArtifact.contributorship.entry.forenameInitials`
| | | | | | | **`Citation.citedArtifact.contributorship.entry.collectiveName`**| | | 
| | | | | | | **`Citation.citedArtifact.contributorship.entry.identifier`**| | | 
| | | | | | | **`Citation.citedArtifact.contributorship.entry.affiliationInfo`**| | | 
| | | | | | | **`Citation.citedArtifact.contributorship.entry.affiliationInfo.id`**| | | 
| | | | | | | **`Citation.citedArtifact.contributorship.entry.affiliationInfo.extension`**| | | 
| | | | | | | **`Citation.citedArtifact.contributorship.entry.affiliationInfo.modifierExtension`**| | | 
| | | | | | | **`Citation.citedArtifact.contributorship.entry.affiliationInfo.affiliation`**| | | 
| | | | | | | **`Citation.citedArtifact.contributorship.entry.affiliationInfo.role`**| | | 
| | | | | | | **`Citation.citedArtifact.contributorship.entry.affiliationInfo.identifier`**| | | 
| | | | | | | **`Citation.citedArtifact.contributorship.entry.address`**| | | 
| | | | | | | **`Citation.citedArtifact.contributorship.entry.telecom`**| | | 
| | | | | | | **`Citation.citedArtifact.contributorship.entry.contributionType`**| _Equivalent_<br/>(38182/38183)| `Citation.citedArtifact.contributorship.entry.contributionType`
| | | | | | | **`Citation.citedArtifact.contributorship.entry.role`**| _Equivalent_<br/>(38184/38185)| `Citation.citedArtifact.contributorship.entry.role`
| | | | | | | **`Citation.citedArtifact.contributorship.entry.contributionInstance`**| _Equivalent_<br/>(38186/38187)| `Citation.citedArtifact.contributorship.entry.contributionInstance`
| | | | | | | **`Citation.citedArtifact.contributorship.entry.contributionInstance.id`**| _Equivalent_<br/>(38188/38189)| `Citation.citedArtifact.contributorship.entry.contributionInstance.id`
| | | | | | | **`Citation.citedArtifact.contributorship.entry.contributionInstance.extension`**| _Equivalent_<br/>(38190/38191)| `Citation.citedArtifact.contributorship.entry.contributionInstance.extension`
| | | | | | | **`Citation.citedArtifact.contributorship.entry.contributionInstance.modifierExtension`**| _Equivalent_<br/>(38192/38193)| `Citation.citedArtifact.contributorship.entry.contributionInstance.modifierExtension`
| | | | | | | **`Citation.citedArtifact.contributorship.entry.contributionInstance.type`**| _Equivalent_<br/>(38194/38195)| `Citation.citedArtifact.contributorship.entry.contributionInstance.type`
| | | | | | | **`Citation.citedArtifact.contributorship.entry.contributionInstance.time`**| _Equivalent_<br/>(38196/38197)| `Citation.citedArtifact.contributorship.entry.contributionInstance.time`
| | | | | | | **`Citation.citedArtifact.contributorship.entry.correspondingContact`**| _Equivalent_<br/>(38198/38199)| `Citation.citedArtifact.contributorship.entry.correspondingContact`
| | | | | | | **`Citation.citedArtifact.contributorship.entry.listOrder`**| _Equivalent_<br/>(1862/2105)| `Citation.citedArtifact.contributorship.entry.rankingOrder`
| | | | | | | **`Citation.citedArtifact.contributorship.summary`**| _Equivalent_<br/>(38200/38201)| `Citation.citedArtifact.contributorship.summary`
| | | | | | | **`Citation.citedArtifact.contributorship.summary.id`**| _Equivalent_<br/>(38202/38203)| `Citation.citedArtifact.contributorship.summary.id`
| | | | | | | **`Citation.citedArtifact.contributorship.summary.extension`**| _Equivalent_<br/>(38204/38205)| `Citation.citedArtifact.contributorship.summary.extension`
| | | | | | | **`Citation.citedArtifact.contributorship.summary.modifierExtension`**| _Equivalent_<br/>(38206/38207)| `Citation.citedArtifact.contributorship.summary.modifierExtension`
| | | | | | | **`Citation.citedArtifact.contributorship.summary.type`**| _Equivalent_<br/>(38208/38209)| `Citation.citedArtifact.contributorship.summary.type`
| | | | | | | **`Citation.citedArtifact.contributorship.summary.style`**| _Equivalent_<br/>(38210/38211)| `Citation.citedArtifact.contributorship.summary.style`
| | | | | | | **`Citation.citedArtifact.contributorship.summary.source`**| _Equivalent_<br/>(38212/38213)| `Citation.citedArtifact.contributorship.summary.source`
| | | | | | | **`Citation.citedArtifact.contributorship.summary.value`**| _Equivalent_<br/>(38214/38215)| `Citation.citedArtifact.contributorship.summary.value`
| | | | | | | **`Citation.citedArtifact.note`**| _Equivalent_<br/>(38216/38217)| `Citation.citedArtifact.note`
| | | | | | | *210 of 210 elements used* | | *166 of 181 elements used* 

