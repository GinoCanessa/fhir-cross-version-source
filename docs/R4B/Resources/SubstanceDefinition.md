Comparison of 
Generated at Thursday, April 3, 2025 8:18:30 AM

### SubstanceDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | SubstanceDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/SubstanceDefinition` |
| Version | 4.3.0 |
| Description | The detailed description of a substance, typically at a level beyond what is used for prescribing. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1771` |
| Database Snapshot Count | `114` |
| Database Differential Count | `76` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `SubstanceDefinition` | `SubstanceDefinition` | `SubstanceDefinition` | SubstanceDefinition | The detailed description of a substance, typically at a level beyond what is used for prescribing | 0..* | SubstanceDefinition |  |  |
| `SubstanceDefinition.classification` | `SubstanceDefinition.classification` | `classification` | SubstanceDefinition.classification | A categorization, high level e.g. polymer or nucleic acid, or food, chemical, biological, or lower e.g. polymer linear or branch chain, or type of impurity | 0..* | CodeableConcept |  |  |
| `SubstanceDefinition.code` | `SubstanceDefinition.code` | `code` | SubstanceDefinition.code | Codes associated with the substance | 0..* | BackboneElement |  |  |
| `SubstanceDefinition.code.code` | `SubstanceDefinition.code.code` | `code` | SubstanceDefinition.code.code | The specific code | 0..1 | CodeableConcept |  |  |
| `SubstanceDefinition.code.extension` | `SubstanceDefinition.code.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceDefinition.code.id` | `SubstanceDefinition.code.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceDefinition.code.modifierExtension` | `SubstanceDefinition.code.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceDefinition.code.note` | `SubstanceDefinition.code.note` | `note` | SubstanceDefinition.code.note | Any comment can be provided in this field | 0..* | Annotation |  |  |
| `SubstanceDefinition.code.source` | `SubstanceDefinition.code.source` | `source` | SubstanceDefinition.code.source | Supporting literature | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `SubstanceDefinition.code.status` | `SubstanceDefinition.code.status` | `status` | SubstanceDefinition.code.status | Status of the code assignment, for example 'provisional', 'approved' | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/publication-status` |
| `SubstanceDefinition.code.statusDate` | `SubstanceDefinition.code.statusDate` | `statusDate` | SubstanceDefinition.code.statusDate | The date at which the code status was changed | 0..1 | dateTime |  |  |
| `SubstanceDefinition.contained` | `SubstanceDefinition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `SubstanceDefinition.description` | `SubstanceDefinition.description` | `description` | SubstanceDefinition.description | Textual description of the substance | 0..1 | markdown |  |  |
| `SubstanceDefinition.domain` | `SubstanceDefinition.domain` | `domain` | SubstanceDefinition.domain | If the substance applies to human or veterinary use | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/medicinal-product-domain` |
| `SubstanceDefinition.extension` | `SubstanceDefinition.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceDefinition.grade` | `SubstanceDefinition.grade` | `grade` | SubstanceDefinition.grade | The quality standard, established benchmark, to which substance complies (e.g. USP/NF, BP) | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/substance-grade` |
| `SubstanceDefinition.id` | `SubstanceDefinition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `SubstanceDefinition.identifier` | `SubstanceDefinition.identifier` | `identifier` | SubstanceDefinition.identifier | Identifier by which this substance is known | 0..* | Identifier |  |  |
| `SubstanceDefinition.implicitRules` | `SubstanceDefinition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `SubstanceDefinition.informationSource` | `SubstanceDefinition.informationSource` | `informationSource` | SubstanceDefinition.informationSource | Supporting literature | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Citation) |  |  |
| `SubstanceDefinition.language` | `SubstanceDefinition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `SubstanceDefinition.manufacturer` | `SubstanceDefinition.manufacturer` | `manufacturer` | SubstanceDefinition.manufacturer | The entity that creates, makes, produces or fabricates the substance | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `SubstanceDefinition.meta` | `SubstanceDefinition.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `SubstanceDefinition.modifierExtension` | `SubstanceDefinition.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `SubstanceDefinition.moiety` | `SubstanceDefinition.moiety` | `moiety` | SubstanceDefinition.moiety | Moiety, for structural modifications | 0..* | BackboneElement |  |  |
| `SubstanceDefinition.moiety.amount[x]` | `SubstanceDefinition.moiety.amount[x]` | `amount[x]` | SubstanceDefinition.moiety.amount[x] | Quantitative value for this moiety | 0..1 | Quantity, string |  |  |
| `SubstanceDefinition.moiety.extension` | `SubstanceDefinition.moiety.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceDefinition.moiety.id` | `SubstanceDefinition.moiety.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceDefinition.moiety.identifier` | `SubstanceDefinition.moiety.identifier` | `identifier` | SubstanceDefinition.moiety.identifier | Identifier by which this moiety substance is known | 0..1 | Identifier |  |  |
| `SubstanceDefinition.moiety.measurementType` | `SubstanceDefinition.moiety.measurementType` | `measurementType` | SubstanceDefinition.moiety.measurementType | The measurement type of the quantitative value | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/substance-amount-type` |
| `SubstanceDefinition.moiety.modifierExtension` | `SubstanceDefinition.moiety.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceDefinition.moiety.molecularFormula` | `SubstanceDefinition.moiety.molecularFormula` | `molecularFormula` | SubstanceDefinition.moiety.molecularFormula | Molecular formula for this moiety (e.g. with the Hill system) | 0..1 | string |  |  |
| `SubstanceDefinition.moiety.name` | `SubstanceDefinition.moiety.name` | `name` | SubstanceDefinition.moiety.name | Textual name for this moiety substance | 0..1 | string |  |  |
| `SubstanceDefinition.moiety.opticalActivity` | `SubstanceDefinition.moiety.opticalActivity` | `opticalActivity` | SubstanceDefinition.moiety.opticalActivity | Optical activity type | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/substance-optical-activity` |
| `SubstanceDefinition.moiety.role` | `SubstanceDefinition.moiety.role` | `role` | SubstanceDefinition.moiety.role | Role that the moiety is playing | 0..1 | CodeableConcept |  |  |
| `SubstanceDefinition.moiety.stereochemistry` | `SubstanceDefinition.moiety.stereochemistry` | `stereochemistry` | SubstanceDefinition.moiety.stereochemistry | Stereochemistry type | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/substance-stereochemistry` |
| `SubstanceDefinition.molecularWeight` | `SubstanceDefinition.molecularWeight` | `molecularWeight` | SubstanceDefinition.molecularWeight | The molecular weight or weight range | 0..* | BackboneElement |  |  |
| `SubstanceDefinition.molecularWeight.amount` | `SubstanceDefinition.molecularWeight.amount` | `amount` | SubstanceDefinition.molecularWeight.amount | Used to capture quantitative values for a variety of elements | 1..1 | Quantity |  |  |
| `SubstanceDefinition.molecularWeight.extension` | `SubstanceDefinition.molecularWeight.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceDefinition.molecularWeight.id` | `SubstanceDefinition.molecularWeight.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceDefinition.molecularWeight.method` | `SubstanceDefinition.molecularWeight.method` | `method` | SubstanceDefinition.molecularWeight.method | The method by which the weight was determined | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/substance-weight-method` |
| `SubstanceDefinition.molecularWeight.modifierExtension` | `SubstanceDefinition.molecularWeight.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceDefinition.molecularWeight.type` | `SubstanceDefinition.molecularWeight.type` | `type` | SubstanceDefinition.molecularWeight.type | Type of molecular weight e.g. exact, average, weight average | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/substance-weight-type` |
| `SubstanceDefinition.name` | `SubstanceDefinition.name` | `name` | SubstanceDefinition.name | Names applicable to this substance | 0..* | BackboneElement |  |  |
| `SubstanceDefinition.name.domain` | `SubstanceDefinition.name.domain` | `domain` | SubstanceDefinition.name.domain | The use context of this name e.g. as an active ingredient or as a food colour additive | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/substance-name-domain` |
| `SubstanceDefinition.name.extension` | `SubstanceDefinition.name.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceDefinition.name.id` | `SubstanceDefinition.name.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceDefinition.name.jurisdiction` | `SubstanceDefinition.name.jurisdiction` | `jurisdiction` | SubstanceDefinition.name.jurisdiction | The jurisdiction where this name applies | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `SubstanceDefinition.name.language` | `SubstanceDefinition.name.language` | `language` | SubstanceDefinition.name.language | Human language that the name is written in | 0..* | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `SubstanceDefinition.name.modifierExtension` | `SubstanceDefinition.name.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceDefinition.name.name` | `SubstanceDefinition.name.name` | `name` | SubstanceDefinition.name.name | The actual name | 1..1 | string |  |  |
| `SubstanceDefinition.name.official` | `SubstanceDefinition.name.official` | `official` | SubstanceDefinition.name.official | Details of the official nature of this name | 0..* | BackboneElement |  |  |
| `SubstanceDefinition.name.official.authority` | `SubstanceDefinition.name.official.authority` | `authority` | SubstanceDefinition.name.official.authority | Which authority uses this official name | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/substance-name-authority` |
| `SubstanceDefinition.name.official.date` | `SubstanceDefinition.name.official.date` | `date` | SubstanceDefinition.name.official.date | Date of official name change | 0..1 | dateTime |  |  |
| `SubstanceDefinition.name.official.extension` | `SubstanceDefinition.name.official.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceDefinition.name.official.id` | `SubstanceDefinition.name.official.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceDefinition.name.official.modifierExtension` | `SubstanceDefinition.name.official.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceDefinition.name.official.status` | `SubstanceDefinition.name.official.status` | `status` | SubstanceDefinition.name.official.status | The status of the official name, for example 'draft', 'active' | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/publication-status` |
| `SubstanceDefinition.name.preferred` | `SubstanceDefinition.name.preferred` | `preferred` | SubstanceDefinition.name.preferred | If this is the preferred name for this substance | 0..1 | boolean |  |  |
| `SubstanceDefinition.name.source` | `SubstanceDefinition.name.source` | `source` | SubstanceDefinition.name.source | Supporting literature | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `SubstanceDefinition.name.status` | `SubstanceDefinition.name.status` | `status` | SubstanceDefinition.name.status | The status of the name e.g. 'current', 'proposed' | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/publication-status` |
| `SubstanceDefinition.name.synonym` | `SubstanceDefinition.name.synonym` | `synonym` | SubstanceDefinition.name.synonym | A synonym of this particular name, by which the substance is also known | 0..* | SubstanceDefinition.name |  |  |
| `SubstanceDefinition.name.translation` | `SubstanceDefinition.name.translation` | `translation` | SubstanceDefinition.name.translation | A translation for this name into another human language | 0..* | SubstanceDefinition.name |  |  |
| `SubstanceDefinition.name.type` | `SubstanceDefinition.name.type` | `type` | SubstanceDefinition.name.type | Name type e.g. 'systematic',  'scientific, 'brand' | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/substance-name-type` |
| `SubstanceDefinition.note` | `SubstanceDefinition.note` | `note` | SubstanceDefinition.note | Textual comment about the substance's catalogue or registry record | 0..* | Annotation |  |  |
| `SubstanceDefinition.property` | `SubstanceDefinition.property` | `property` | SubstanceDefinition.property | General specifications for this substance | 0..* | BackboneElement |  |  |
| `SubstanceDefinition.property.extension` | `SubstanceDefinition.property.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceDefinition.property.id` | `SubstanceDefinition.property.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceDefinition.property.modifierExtension` | `SubstanceDefinition.property.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceDefinition.property.type` | `SubstanceDefinition.property.type` | `type` | SubstanceDefinition.property.type | A code expressing the type of property | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/product-characteristic-codes` |
| `SubstanceDefinition.property.value[x]` | `SubstanceDefinition.property.value[x]` | `value[x]` | SubstanceDefinition.property.value[x] | A value for the property | 0..1 | Attachment, boolean, CodeableConcept, date, Quantity |  |  |
| `SubstanceDefinition.relationship` | `SubstanceDefinition.relationship` | `relationship` | SubstanceDefinition.relationship | A link between this substance and another | 0..* | BackboneElement |  |  |
| `SubstanceDefinition.relationship.amount[x]` | `SubstanceDefinition.relationship.amount[x]` | `amount[x]` | SubstanceDefinition.relationship.amount[x] | A numeric factor for the relationship, e.g. that a substance salt has some percentage of active substance in relation to some other | 0..1 | Quantity, Ratio, string |  |  |
| `SubstanceDefinition.relationship.comparator` | `SubstanceDefinition.relationship.comparator` | `comparator` | SubstanceDefinition.relationship.comparator | An operator for the amount, for example "average", "approximately", "less than" | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/substance-amount-type` |
| `SubstanceDefinition.relationship.extension` | `SubstanceDefinition.relationship.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceDefinition.relationship.id` | `SubstanceDefinition.relationship.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceDefinition.relationship.isDefining` | `SubstanceDefinition.relationship.isDefining` | `isDefining` | SubstanceDefinition.relationship.isDefining | For example where an enzyme strongly bonds with a particular substance, this is a defining relationship for that enzyme, out of several possible relationships | 0..1 | boolean |  |  |
| `SubstanceDefinition.relationship.modifierExtension` | `SubstanceDefinition.relationship.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceDefinition.relationship.ratioHighLimitAmount` | `SubstanceDefinition.relationship.ratioHighLimitAmount` | `ratioHighLimitAmount` | SubstanceDefinition.relationship.ratioHighLimitAmount | For use when the numeric has an uncertain range | 0..1 | Ratio |  |  |
| `SubstanceDefinition.relationship.source` | `SubstanceDefinition.relationship.source` | `source` | SubstanceDefinition.relationship.source | Supporting literature | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `SubstanceDefinition.relationship.substanceDefinition[x]` | `SubstanceDefinition.relationship.substanceDefinition[x]` | `substanceDefinition[x]` | SubstanceDefinition.relationship.substanceDefinition[x] | A pointer to another substance, as a resource or a representational code | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/SubstanceDefinition) |  |  |
| `SubstanceDefinition.relationship.type` | `SubstanceDefinition.relationship.type` | `type` | SubstanceDefinition.relationship.type | For example "salt to parent", "active moiety" | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/substance-relationship-type` |
| `SubstanceDefinition.sourceMaterial` | `SubstanceDefinition.sourceMaterial` | `sourceMaterial` | SubstanceDefinition.sourceMaterial | Material or taxonomic/anatomical source | 0..1 | BackboneElement |  |  |
| `SubstanceDefinition.sourceMaterial.countryOfOrigin` | `SubstanceDefinition.sourceMaterial.countryOfOrigin` | `countryOfOrigin` | SubstanceDefinition.sourceMaterial.countryOfOrigin | The country or countries where the material is harvested | 0..* | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/country|4.3.0` |
| `SubstanceDefinition.sourceMaterial.extension` | `SubstanceDefinition.sourceMaterial.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceDefinition.sourceMaterial.genus` | `SubstanceDefinition.sourceMaterial.genus` | `genus` | SubstanceDefinition.sourceMaterial.genus | The genus of an organism e.g. the Latin epithet of the plant/animal scientific name | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/substance-source-material-genus` |
| `SubstanceDefinition.sourceMaterial.id` | `SubstanceDefinition.sourceMaterial.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceDefinition.sourceMaterial.modifierExtension` | `SubstanceDefinition.sourceMaterial.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceDefinition.sourceMaterial.part` | `SubstanceDefinition.sourceMaterial.part` | `part` | SubstanceDefinition.sourceMaterial.part | An anatomical origin of the source material within an organism | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/substance-source-material-part` |
| `SubstanceDefinition.sourceMaterial.species` | `SubstanceDefinition.sourceMaterial.species` | `species` | SubstanceDefinition.sourceMaterial.species | The species of an organism e.g. the Latin epithet of the species of the plant/animal | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/substance-source-material-species` |
| `SubstanceDefinition.sourceMaterial.type` | `SubstanceDefinition.sourceMaterial.type` | `type` | SubstanceDefinition.sourceMaterial.type | Classification of the origin of the raw material. e.g. cat hair is an Animal source type | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/substance-source-material-type` |
| `SubstanceDefinition.status` | `SubstanceDefinition.status` | `status` | SubstanceDefinition.status | Status of substance within the catalogue e.g. active, retired | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/publication-status` |
| `SubstanceDefinition.structure` | `SubstanceDefinition.structure` | `structure` | SubstanceDefinition.structure | Structural information | 0..1 | BackboneElement |  |  |
| `SubstanceDefinition.structure.extension` | `SubstanceDefinition.structure.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceDefinition.structure.id` | `SubstanceDefinition.structure.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceDefinition.structure.modifierExtension` | `SubstanceDefinition.structure.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceDefinition.structure.molecularFormula` | `SubstanceDefinition.structure.molecularFormula` | `molecularFormula` | SubstanceDefinition.structure.molecularFormula | Molecular formula (e.g. using the Hill system) | 0..1 | string |  |  |
| `SubstanceDefinition.structure.molecularFormulaByMoiety` | `SubstanceDefinition.structure.molecularFormulaByMoiety` | `molecularFormulaByMoiety` | SubstanceDefinition.structure.molecularFormulaByMoiety | Specified per moiety according to the Hill system | 0..1 | string |  |  |
| `SubstanceDefinition.structure.molecularWeight` | `SubstanceDefinition.structure.molecularWeight` | `molecularWeight` | SubstanceDefinition.structure.molecularWeight | The molecular weight or weight range | 0..1 | SubstanceDefinition.molecularWeight |  |  |
| `SubstanceDefinition.structure.opticalActivity` | `SubstanceDefinition.structure.opticalActivity` | `opticalActivity` | SubstanceDefinition.structure.opticalActivity | Optical activity type | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/substance-optical-activity` |
| `SubstanceDefinition.structure.representation` | `SubstanceDefinition.structure.representation` | `representation` | SubstanceDefinition.structure.representation | A depiction of the structure or characterization of the substance | 0..* | BackboneElement |  |  |
| `SubstanceDefinition.structure.representation.document` | `SubstanceDefinition.structure.representation.document` | `document` | SubstanceDefinition.structure.representation.document | An attachment with the structural representation e.g. a structure graphic or AnIML file | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `SubstanceDefinition.structure.representation.extension` | `SubstanceDefinition.structure.representation.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceDefinition.structure.representation.format` | `SubstanceDefinition.structure.representation.format` | `format` | SubstanceDefinition.structure.representation.format | The format of the representation e.g. InChI, SMILES, MOLFILE (note: not the physical file format) | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/substance-representation-format` |
| `SubstanceDefinition.structure.representation.id` | `SubstanceDefinition.structure.representation.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceDefinition.structure.representation.modifierExtension` | `SubstanceDefinition.structure.representation.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceDefinition.structure.representation.representation` | `SubstanceDefinition.structure.representation.representation` | `representation` | SubstanceDefinition.structure.representation.representation | The structural representation or characterization as a text string in a standard format | 0..1 | string |  |  |
| `SubstanceDefinition.structure.representation.type` | `SubstanceDefinition.structure.representation.type` | `type` | SubstanceDefinition.structure.representation.type | The kind of structural representation (e.g. full, partial) | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/substance-representation-type` |
| `SubstanceDefinition.structure.sourceDocument` | `SubstanceDefinition.structure.sourceDocument` | `sourceDocument` | SubstanceDefinition.structure.sourceDocument | Source of information for the structure | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `SubstanceDefinition.structure.stereochemistry` | `SubstanceDefinition.structure.stereochemistry` | `stereochemistry` | SubstanceDefinition.structure.stereochemistry | Stereochemistry type | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/substance-stereochemistry` |
| `SubstanceDefinition.structure.technique` | `SubstanceDefinition.structure.technique` | `technique` | SubstanceDefinition.structure.technique | The method used to find the structure e.g. X-ray, NMR | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/substance-structure-technique` |
| `SubstanceDefinition.supplier` | `SubstanceDefinition.supplier` | `supplier` | SubstanceDefinition.supplier | An entity that is the source for the substance. It may be different from the manufacturer | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `SubstanceDefinition.text` | `SubstanceDefinition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `SubstanceDefinition.version` | `SubstanceDefinition.version` | `version` | SubstanceDefinition.version | A business level version identifier of the substance | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [SubstanceDefinition](/docs/R4B/Resources/SubstanceDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/SubstanceDefinition\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1050`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1279`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SubstanceDefinition](/docs/R5/Resources/SubstanceDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/SubstanceDefinition\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition SubstanceDefinition from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | R4B SubstanceDefinition| Relationship | [R5 SubstanceDefinition](/docs/R5/Resources/SubstanceDefinition.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | **`SubstanceDefinition`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(48153)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(48154)| `SubstanceDefinition`
| | | | | | | **`SubstanceDefinition.id`**| _Equivalent_<br/>(48155/48156)| `SubstanceDefinition.id`
| | | | | | | **`SubstanceDefinition.meta`**| _Equivalent_<br/>(48157/48158)| `SubstanceDefinition.meta`
| | | | | | | **`SubstanceDefinition.implicitRules`**| _Equivalent_<br/>(48159/48160)| `SubstanceDefinition.implicitRules`
| | | | | | | **`SubstanceDefinition.language`**| _Equivalent_<br/>(48161/48162)| `SubstanceDefinition.language`
| | | | | | | **`SubstanceDefinition.text`**| _Equivalent_<br/>(48163/48164)| `SubstanceDefinition.text`
| | | | | | | **`SubstanceDefinition.contained`**| _Equivalent_<br/>(48165/48166)| `SubstanceDefinition.contained`
| | | | | | | **`SubstanceDefinition.extension`**| _Equivalent_<br/>(48167/48168)| `SubstanceDefinition.extension`
| | | | | | | **`SubstanceDefinition.modifierExtension`**| _Equivalent_<br/>(48169/48170)| `SubstanceDefinition.modifierExtension`
| | | | | | | **`SubstanceDefinition.identifier`**| _Equivalent_<br/>(48171/48172)| `SubstanceDefinition.identifier`
| | | | | | | **`SubstanceDefinition.version`**| _Equivalent_<br/>(48173/48174)| `SubstanceDefinition.version`
| | | | | | | **`SubstanceDefinition.status`**| _Equivalent_<br/>(48175/48176)| `SubstanceDefinition.status`
| | | | | | | **`SubstanceDefinition.classification`**| _Equivalent_<br/>(48177/48178)| `SubstanceDefinition.classification`
| | | | | | | **`SubstanceDefinition.domain`**| _Equivalent_<br/>(48179/48180)| `SubstanceDefinition.domain`
| | | | | | | **`SubstanceDefinition.grade`**| _Equivalent_<br/>(48181/48182)| `SubstanceDefinition.grade`
| | | | | | | **`SubstanceDefinition.description`**| _Equivalent_<br/>(48183/48184)| `SubstanceDefinition.description`
| | | | | | | **`SubstanceDefinition.informationSource`**| _Equivalent_<br/>(48185/48186)| `SubstanceDefinition.informationSource`
| | | | | | | **`SubstanceDefinition.note`**| _Equivalent_<br/>(48187/48188)| `SubstanceDefinition.note`
| | | | | | | **`SubstanceDefinition.manufacturer`**| _Equivalent_<br/>(48189/48190)| `SubstanceDefinition.manufacturer`
| | | | | | | **`SubstanceDefinition.supplier`**| _Equivalent_<br/>(48191/48192)| `SubstanceDefinition.supplier`
| | | | | | | **`SubstanceDefinition.moiety`**| _Equivalent_<br/>(48193/48194)| `SubstanceDefinition.moiety`
| | | | | | | **`SubstanceDefinition.moiety.id`**| _Equivalent_<br/>(48195/48196)| `SubstanceDefinition.moiety.id`
| | | | | | | **`SubstanceDefinition.moiety.extension`**| _Equivalent_<br/>(48197/48198)| `SubstanceDefinition.moiety.extension`
| | | | | | | **`SubstanceDefinition.moiety.modifierExtension`**| _Equivalent_<br/>(48199/48200)| `SubstanceDefinition.moiety.modifierExtension`
| | | | | | | **`SubstanceDefinition.moiety.role`**| _Equivalent_<br/>(48201/48202)| `SubstanceDefinition.moiety.role`
| | | | | | | **`SubstanceDefinition.moiety.identifier`**| _Equivalent_<br/>(48203/48204)| `SubstanceDefinition.moiety.identifier`
| | | | | | | **`SubstanceDefinition.moiety.name`**| _Equivalent_<br/>(48205/48206)| `SubstanceDefinition.moiety.name`
| | | | | | | **`SubstanceDefinition.moiety.stereochemistry`**| _Equivalent_<br/>(48207/48208)| `SubstanceDefinition.moiety.stereochemistry`
| | | | | | | **`SubstanceDefinition.moiety.opticalActivity`**| _Equivalent_<br/>(48209/48210)| `SubstanceDefinition.moiety.opticalActivity`
| | | | | | | **`SubstanceDefinition.moiety.molecularFormula`**| _Equivalent_<br/>(48211/48212)| `SubstanceDefinition.moiety.molecularFormula`
| | | | | | | **`SubstanceDefinition.moiety.amount[x]`**| _Equivalent_<br/>(48213/48214)| `SubstanceDefinition.moiety.amount[x]`
| | | | | | | **`SubstanceDefinition.moiety.measurementType`**| _Equivalent_<br/>(48215/48216)| `SubstanceDefinition.moiety.measurementType`
| | | | | | | **`SubstanceDefinition.property`**| _Equivalent_<br/>(48217/48218)| `SubstanceDefinition.property`
| | | | | | | **`SubstanceDefinition.property.id`**| _Equivalent_<br/>(48219/48220)| `SubstanceDefinition.property.id`
| | | | | | | **`SubstanceDefinition.property.extension`**| _Equivalent_<br/>(48221/48222)| `SubstanceDefinition.property.extension`
| | | | | | | **`SubstanceDefinition.property.modifierExtension`**| _Equivalent_<br/>(48223/48224)| `SubstanceDefinition.property.modifierExtension`
| | | | | | | **`SubstanceDefinition.property.type`**| _Equivalent_<br/>(48225/48226)| `SubstanceDefinition.property.type`
| | | | | | | **`SubstanceDefinition.property.value[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(48227)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(48228)| `SubstanceDefinition.property.value[x]`
| | | | | | | **`SubstanceDefinition.molecularWeight`**| _Equivalent_<br/>(48229/48230)| `SubstanceDefinition.molecularWeight`
| | | | | | | **`SubstanceDefinition.molecularWeight.id`**| _Equivalent_<br/>(48231/48232)| `SubstanceDefinition.molecularWeight.id`
| | | | | | | **`SubstanceDefinition.molecularWeight.extension`**| _Equivalent_<br/>(48233/48234)| `SubstanceDefinition.molecularWeight.extension`
| | | | | | | **`SubstanceDefinition.molecularWeight.modifierExtension`**| _Equivalent_<br/>(48235/48236)| `SubstanceDefinition.molecularWeight.modifierExtension`
| | | | | | | **`SubstanceDefinition.molecularWeight.method`**| _Equivalent_<br/>(48237/48238)| `SubstanceDefinition.molecularWeight.method`
| | | | | | | **`SubstanceDefinition.molecularWeight.type`**| _Equivalent_<br/>(48239/48240)| `SubstanceDefinition.molecularWeight.type`
| | | | | | | **`SubstanceDefinition.molecularWeight.amount`**| _Equivalent_<br/>(48241/48242)| `SubstanceDefinition.molecularWeight.amount`
| | | | | | | **`SubstanceDefinition.structure`**| _Equivalent_<br/>(48243/48244)| `SubstanceDefinition.structure`
| | | | | | | **`SubstanceDefinition.structure.id`**| _Equivalent_<br/>(48245/48246)| `SubstanceDefinition.structure.id`
| | | | | | | **`SubstanceDefinition.structure.extension`**| _Equivalent_<br/>(48247/48248)| `SubstanceDefinition.structure.extension`
| | | | | | | **`SubstanceDefinition.structure.modifierExtension`**| _Equivalent_<br/>(48249/48250)| `SubstanceDefinition.structure.modifierExtension`
| | | | | | | **`SubstanceDefinition.structure.stereochemistry`**| _Equivalent_<br/>(48251/48252)| `SubstanceDefinition.structure.stereochemistry`
| | | | | | | **`SubstanceDefinition.structure.opticalActivity`**| _Equivalent_<br/>(48253/48254)| `SubstanceDefinition.structure.opticalActivity`
| | | | | | | **`SubstanceDefinition.structure.molecularFormula`**| _Equivalent_<br/>(48255/48256)| `SubstanceDefinition.structure.molecularFormula`
| | | | | | | **`SubstanceDefinition.structure.molecularFormulaByMoiety`**| _Equivalent_<br/>(48257/48258)| `SubstanceDefinition.structure.molecularFormulaByMoiety`
| | | | | | | **`SubstanceDefinition.structure.molecularWeight`**| _Equivalent_<br/>(48259/48260)| `SubstanceDefinition.structure.molecularWeight`
| | | | | | | **`SubstanceDefinition.structure.technique`**| _Equivalent_<br/>(48261/48262)| `SubstanceDefinition.structure.technique`
| | | | | | | **`SubstanceDefinition.structure.sourceDocument`**| _Equivalent_<br/>(48263/48264)| `SubstanceDefinition.structure.sourceDocument`
| | | | | | | **`SubstanceDefinition.structure.representation`**| _Equivalent_<br/>(48265/48266)| `SubstanceDefinition.structure.representation`
| | | | | | | **`SubstanceDefinition.structure.representation.id`**| _Equivalent_<br/>(48267/48268)| `SubstanceDefinition.structure.representation.id`
| | | | | | | **`SubstanceDefinition.structure.representation.extension`**| _Equivalent_<br/>(48269/48270)| `SubstanceDefinition.structure.representation.extension`
| | | | | | | **`SubstanceDefinition.structure.representation.modifierExtension`**| _Equivalent_<br/>(48271/48272)| `SubstanceDefinition.structure.representation.modifierExtension`
| | | | | | | **`SubstanceDefinition.structure.representation.type`**| _Equivalent_<br/>(48273/48274)| `SubstanceDefinition.structure.representation.type`
| | | | | | | **`SubstanceDefinition.structure.representation.representation`**| _Equivalent_<br/>(48275/48276)| `SubstanceDefinition.structure.representation.representation`
| | | | | | | **`SubstanceDefinition.structure.representation.format`**| _Equivalent_<br/>(48277/48278)| `SubstanceDefinition.structure.representation.format`
| | | | | | | **`SubstanceDefinition.structure.representation.document`**| _Equivalent_<br/>(48279/48280)| `SubstanceDefinition.structure.representation.document`
| | | | | | | **`SubstanceDefinition.code`**| _Equivalent_<br/>(48281/48282)| `SubstanceDefinition.code`
| | | | | | | **`SubstanceDefinition.code.id`**| _Equivalent_<br/>(48283/48284)| `SubstanceDefinition.code.id`
| | | | | | | **`SubstanceDefinition.code.extension`**| _Equivalent_<br/>(48285/48286)| `SubstanceDefinition.code.extension`
| | | | | | | **`SubstanceDefinition.code.modifierExtension`**| _Equivalent_<br/>(48287/48288)| `SubstanceDefinition.code.modifierExtension`
| | | | | | | **`SubstanceDefinition.code.code`**| _Equivalent_<br/>(48289/48290)| `SubstanceDefinition.code.code`
| | | | | | | **`SubstanceDefinition.code.status`**| _Equivalent_<br/>(48291/48292)| `SubstanceDefinition.code.status`
| | | | | | | **`SubstanceDefinition.code.statusDate`**| _Equivalent_<br/>(48293/48294)| `SubstanceDefinition.code.statusDate`
| | | | | | | **`SubstanceDefinition.code.note`**| _Equivalent_<br/>(48295/48296)| `SubstanceDefinition.code.note`
| | | | | | | **`SubstanceDefinition.code.source`**| _Equivalent_<br/>(48297/48298)| `SubstanceDefinition.code.source`
| | | | | | | **`SubstanceDefinition.name`**| _Equivalent_<br/>(48299/48300)| `SubstanceDefinition.name`
| | | | | | | **`SubstanceDefinition.name.id`**| _Equivalent_<br/>(48301/48302)| `SubstanceDefinition.name.id`
| | | | | | | **`SubstanceDefinition.name.extension`**| _Equivalent_<br/>(48303/48304)| `SubstanceDefinition.name.extension`
| | | | | | | **`SubstanceDefinition.name.modifierExtension`**| _Equivalent_<br/>(48305/48306)| `SubstanceDefinition.name.modifierExtension`
| | | | | | | **`SubstanceDefinition.name.name`**| _Equivalent_<br/>(48307/48308)| `SubstanceDefinition.name.name`
| | | | | | | **`SubstanceDefinition.name.type`**| _Equivalent_<br/>(48309/48310)| `SubstanceDefinition.name.type`
| | | | | | | **`SubstanceDefinition.name.status`**| _Equivalent_<br/>(48311/48312)| `SubstanceDefinition.name.status`
| | | | | | | **`SubstanceDefinition.name.preferred`**| _Equivalent_<br/>(48313/48314)| `SubstanceDefinition.name.preferred`
| | | | | | | **`SubstanceDefinition.name.language`**| _Equivalent_<br/>(48315/48316)| `SubstanceDefinition.name.language`
| | | | | | | **`SubstanceDefinition.name.domain`**| _Equivalent_<br/>(48317/48318)| `SubstanceDefinition.name.domain`
| | | | | | | **`SubstanceDefinition.name.jurisdiction`**| _Equivalent_<br/>(48319/48320)| `SubstanceDefinition.name.jurisdiction`
| | | | | | | **`SubstanceDefinition.name.synonym`**| _Equivalent_<br/>(48321/48322)| `SubstanceDefinition.name.synonym`
| | | | | | | **`SubstanceDefinition.name.translation`**| _Equivalent_<br/>(48323/48324)| `SubstanceDefinition.name.translation`
| | | | | | | **`SubstanceDefinition.name.official`**| _Equivalent_<br/>(48325/48326)| `SubstanceDefinition.name.official`
| | | | | | | **`SubstanceDefinition.name.official.id`**| _Equivalent_<br/>(48327/48328)| `SubstanceDefinition.name.official.id`
| | | | | | | **`SubstanceDefinition.name.official.extension`**| _Equivalent_<br/>(48329/48330)| `SubstanceDefinition.name.official.extension`
| | | | | | | **`SubstanceDefinition.name.official.modifierExtension`**| _Equivalent_<br/>(48331/48332)| `SubstanceDefinition.name.official.modifierExtension`
| | | | | | | **`SubstanceDefinition.name.official.authority`**| _Equivalent_<br/>(48333/48334)| `SubstanceDefinition.name.official.authority`
| | | | | | | **`SubstanceDefinition.name.official.status`**| _Equivalent_<br/>(48335/48336)| `SubstanceDefinition.name.official.status`
| | | | | | | **`SubstanceDefinition.name.official.date`**| _Equivalent_<br/>(48337/48338)| `SubstanceDefinition.name.official.date`
| | | | | | | **`SubstanceDefinition.name.source`**| _Equivalent_<br/>(48339/48340)| `SubstanceDefinition.name.source`
| | | | | | | **`SubstanceDefinition.relationship`**| _Equivalent_<br/>(48341/48342)| `SubstanceDefinition.relationship`
| | | | | | | **`SubstanceDefinition.relationship.id`**| _Equivalent_<br/>(48343/48344)| `SubstanceDefinition.relationship.id`
| | | | | | | **`SubstanceDefinition.relationship.extension`**| _Equivalent_<br/>(48345/48346)| `SubstanceDefinition.relationship.extension`
| | | | | | | **`SubstanceDefinition.relationship.modifierExtension`**| _Equivalent_<br/>(48347/48348)| `SubstanceDefinition.relationship.modifierExtension`
| | | | | | | **`SubstanceDefinition.relationship.substanceDefinition[x]`**| _Equivalent_<br/>(48349/48350)| `SubstanceDefinition.relationship.substanceDefinition[x]`
| | | | | | | **`SubstanceDefinition.relationship.type`**| _Equivalent_<br/>(48351/48352)| `SubstanceDefinition.relationship.type`
| | | | | | | **`SubstanceDefinition.relationship.isDefining`**| _Equivalent_<br/>(48353/48354)| `SubstanceDefinition.relationship.isDefining`
| | | | | | | **`SubstanceDefinition.relationship.amount[x]`**| _Equivalent_<br/>(48355/48356)| `SubstanceDefinition.relationship.amount[x]`
| | | | | | | **`SubstanceDefinition.relationship.ratioHighLimitAmount`**| _Equivalent_<br/>(48357/48358)| `SubstanceDefinition.relationship.ratioHighLimitAmount`
| | | | | | | **`SubstanceDefinition.relationship.comparator`**| _Equivalent_<br/>(48359/48360)| `SubstanceDefinition.relationship.comparator`
| | | | | | | **`SubstanceDefinition.relationship.source`**| _Equivalent_<br/>(48361/48362)| `SubstanceDefinition.relationship.source`
| | | | | | | **`SubstanceDefinition.sourceMaterial`**| _Equivalent_<br/>(48363/48364)| `SubstanceDefinition.sourceMaterial`
| | | | | | | **`SubstanceDefinition.sourceMaterial.id`**| _Equivalent_<br/>(48365/48366)| `SubstanceDefinition.sourceMaterial.id`
| | | | | | | **`SubstanceDefinition.sourceMaterial.extension`**| _Equivalent_<br/>(48367/48368)| `SubstanceDefinition.sourceMaterial.extension`
| | | | | | | **`SubstanceDefinition.sourceMaterial.modifierExtension`**| _Equivalent_<br/>(48369/48370)| `SubstanceDefinition.sourceMaterial.modifierExtension`
| | | | | | | **`SubstanceDefinition.sourceMaterial.type`**| _Equivalent_<br/>(48371/48372)| `SubstanceDefinition.sourceMaterial.type`
| | | | | | | **`SubstanceDefinition.sourceMaterial.genus`**| _Equivalent_<br/>(48373/48374)| `SubstanceDefinition.sourceMaterial.genus`
| | | | | | | **`SubstanceDefinition.sourceMaterial.species`**| _Equivalent_<br/>(48375/48376)| `SubstanceDefinition.sourceMaterial.species`
| | | | | | | **`SubstanceDefinition.sourceMaterial.part`**| _Equivalent_<br/>(48377/48378)| `SubstanceDefinition.sourceMaterial.part`
| | | | | | | **`SubstanceDefinition.sourceMaterial.countryOfOrigin`**| _Equivalent_<br/>(48379/48380)| `SubstanceDefinition.sourceMaterial.countryOfOrigin`
| | | | | | | *114 of 114 elements used* | | *114 of 126 elements used* <br/>remaining elements:<br/>`SubstanceDefinition.characterization`, `SubstanceDefinition.characterization.description`, `SubstanceDefinition.characterization.extension`, `SubstanceDefinition.characterization.file`, `SubstanceDefinition.characterization.form`, `SubstanceDefinition.characterization.id`, `SubstanceDefinition.characterization.modifierExtension`, `SubstanceDefinition.characterization.technique`, `SubstanceDefinition.nucleicAcid`, `SubstanceDefinition.polymer`, `SubstanceDefinition.protein`, `SubstanceDefinition.referenceInformation`

