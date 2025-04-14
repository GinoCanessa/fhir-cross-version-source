Comparison of 
Generated at Monday, April 14, 2025 6:17:32 PM

### SubstanceSpecification

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | SubstanceSpecification |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/SubstanceSpecification` |
| Version | 4.0.1 |
| Description | The detailed description of a substance, typically at a level beyond what is used for prescribing. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1169` |
| Database Snapshot Count | `115` |
| Database Differential Count | `77` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `SubstanceSpecification` | `SubstanceSpecification` | `SubstanceSpecification` | SubstanceSpecification | The detailed description of a substance, typically at a level beyond what is used for prescribing | 0..* | SubstanceSpecification |  |  |
| `SubstanceSpecification.code` | `SubstanceSpecification.code` | `code` | SubstanceSpecification.code | Codes associated with the substance | 0..* | BackboneElement |  |  |
| `SubstanceSpecification.code.code` | `SubstanceSpecification.code.code` | `code` | SubstanceSpecification.code.code | The specific code | 0..1 | CodeableConcept |  |  |
| `SubstanceSpecification.code.comment` | `SubstanceSpecification.code.comment` | `comment` | SubstanceSpecification.code.comment | Any comment can be provided in this field, if necessary | 0..1 | string |  |  |
| `SubstanceSpecification.code.extension` | `SubstanceSpecification.code.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceSpecification.code.id` | `SubstanceSpecification.code.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceSpecification.code.modifierExtension` | `SubstanceSpecification.code.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceSpecification.code.source` | `SubstanceSpecification.code.source` | `source` | SubstanceSpecification.code.source | Supporting literature | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `SubstanceSpecification.code.status` | `SubstanceSpecification.code.status` | `status` | SubstanceSpecification.code.status | Status of the code assignment | 0..1 | CodeableConcept |  |  |
| `SubstanceSpecification.code.statusDate` | `SubstanceSpecification.code.statusDate` | `statusDate` | SubstanceSpecification.code.statusDate | The date at which the code status is changed as part of the terminology maintenance | 0..1 | dateTime |  |  |
| `SubstanceSpecification.comment` | `SubstanceSpecification.comment` | `comment` | SubstanceSpecification.comment | Textual comment about this record of a substance | 0..1 | string |  |  |
| `SubstanceSpecification.contained` | `SubstanceSpecification.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `SubstanceSpecification.description` | `SubstanceSpecification.description` | `description` | SubstanceSpecification.description | Textual description of the substance | 0..1 | string |  |  |
| `SubstanceSpecification.domain` | `SubstanceSpecification.domain` | `domain` | SubstanceSpecification.domain | If the substance applies to only human or veterinary use | 0..1 | CodeableConcept |  |  |
| `SubstanceSpecification.extension` | `SubstanceSpecification.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceSpecification.id` | `SubstanceSpecification.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `SubstanceSpecification.identifier` | `SubstanceSpecification.identifier` | `identifier` | SubstanceSpecification.identifier | Identifier by which this substance is known | 0..1 | Identifier |  |  |
| `SubstanceSpecification.implicitRules` | `SubstanceSpecification.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `SubstanceSpecification.language` | `SubstanceSpecification.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `SubstanceSpecification.meta` | `SubstanceSpecification.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `SubstanceSpecification.modifierExtension` | `SubstanceSpecification.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `SubstanceSpecification.moiety` | `SubstanceSpecification.moiety` | `moiety` | SubstanceSpecification.moiety | Moiety, for structural modifications | 0..* | BackboneElement |  |  |
| `SubstanceSpecification.moiety.amount[x]` | `SubstanceSpecification.moiety.amount[x]` | `amount[x]` | SubstanceSpecification.moiety.amount[x] | Quantitative value for this moiety | 0..1 | Quantity, string |  |  |
| `SubstanceSpecification.moiety.extension` | `SubstanceSpecification.moiety.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceSpecification.moiety.id` | `SubstanceSpecification.moiety.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceSpecification.moiety.identifier` | `SubstanceSpecification.moiety.identifier` | `identifier` | SubstanceSpecification.moiety.identifier | Identifier by which this moiety substance is known | 0..1 | Identifier |  |  |
| `SubstanceSpecification.moiety.modifierExtension` | `SubstanceSpecification.moiety.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceSpecification.moiety.molecularFormula` | `SubstanceSpecification.moiety.molecularFormula` | `molecularFormula` | SubstanceSpecification.moiety.molecularFormula | Molecular formula | 0..1 | string |  |  |
| `SubstanceSpecification.moiety.name` | `SubstanceSpecification.moiety.name` | `name` | SubstanceSpecification.moiety.name | Textual name for this moiety substance | 0..1 | string |  |  |
| `SubstanceSpecification.moiety.opticalActivity` | `SubstanceSpecification.moiety.opticalActivity` | `opticalActivity` | SubstanceSpecification.moiety.opticalActivity | Optical activity type | 0..1 | CodeableConcept |  |  |
| `SubstanceSpecification.moiety.role` | `SubstanceSpecification.moiety.role` | `role` | SubstanceSpecification.moiety.role | Role that the moiety is playing | 0..1 | CodeableConcept |  |  |
| `SubstanceSpecification.moiety.stereochemistry` | `SubstanceSpecification.moiety.stereochemistry` | `stereochemistry` | SubstanceSpecification.moiety.stereochemistry | Stereochemistry type | 0..1 | CodeableConcept |  |  |
| `SubstanceSpecification.molecularWeight` | `SubstanceSpecification.molecularWeight` | `molecularWeight` | SubstanceSpecification.molecularWeight | The molecular weight or weight range (for proteins, polymers or nucleic acids) | 0..* | SubstanceSpecification.structure.isotope.molecularWeight |  |  |
| `SubstanceSpecification.name` | `SubstanceSpecification.name` | `name` | SubstanceSpecification.name | Names applicable to this substance | 0..* | BackboneElement |  |  |
| `SubstanceSpecification.name.domain` | `SubstanceSpecification.name.domain` | `domain` | SubstanceSpecification.name.domain | The use context of this name for example if there is a different name a drug active ingredient as opposed to a food colour additive | 0..* | CodeableConcept |  |  |
| `SubstanceSpecification.name.extension` | `SubstanceSpecification.name.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceSpecification.name.id` | `SubstanceSpecification.name.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceSpecification.name.jurisdiction` | `SubstanceSpecification.name.jurisdiction` | `jurisdiction` | SubstanceSpecification.name.jurisdiction | The jurisdiction where this name applies | 0..* | CodeableConcept |  |  |
| `SubstanceSpecification.name.language` | `SubstanceSpecification.name.language` | `language` | SubstanceSpecification.name.language | Language of the name | 0..* | CodeableConcept |  |  |
| `SubstanceSpecification.name.modifierExtension` | `SubstanceSpecification.name.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceSpecification.name.name` | `SubstanceSpecification.name.name` | `name` | SubstanceSpecification.name.name | The actual name | 1..1 | string |  |  |
| `SubstanceSpecification.name.official` | `SubstanceSpecification.name.official` | `official` | SubstanceSpecification.name.official | Details of the official nature of this name | 0..* | BackboneElement |  |  |
| `SubstanceSpecification.name.official.authority` | `SubstanceSpecification.name.official.authority` | `authority` | SubstanceSpecification.name.official.authority | Which authority uses this official name | 0..1 | CodeableConcept |  |  |
| `SubstanceSpecification.name.official.date` | `SubstanceSpecification.name.official.date` | `date` | SubstanceSpecification.name.official.date | Date of official name change | 0..1 | dateTime |  |  |
| `SubstanceSpecification.name.official.extension` | `SubstanceSpecification.name.official.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceSpecification.name.official.id` | `SubstanceSpecification.name.official.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceSpecification.name.official.modifierExtension` | `SubstanceSpecification.name.official.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceSpecification.name.official.status` | `SubstanceSpecification.name.official.status` | `status` | SubstanceSpecification.name.official.status | The status of the official name | 0..1 | CodeableConcept |  |  |
| `SubstanceSpecification.name.preferred` | `SubstanceSpecification.name.preferred` | `preferred` | SubstanceSpecification.name.preferred | If this is the preferred name for this substance | 0..1 | boolean |  |  |
| `SubstanceSpecification.name.source` | `SubstanceSpecification.name.source` | `source` | SubstanceSpecification.name.source | Supporting literature | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `SubstanceSpecification.name.status` | `SubstanceSpecification.name.status` | `status` | SubstanceSpecification.name.status | The status of the name | 0..1 | CodeableConcept |  |  |
| `SubstanceSpecification.name.synonym` | `SubstanceSpecification.name.synonym` | `synonym` | SubstanceSpecification.name.synonym | A synonym of this name | 0..* | SubstanceSpecification.name |  |  |
| `SubstanceSpecification.name.translation` | `SubstanceSpecification.name.translation` | `translation` | SubstanceSpecification.name.translation | A translation for this name | 0..* | SubstanceSpecification.name |  |  |
| `SubstanceSpecification.name.type` | `SubstanceSpecification.name.type` | `type` | SubstanceSpecification.name.type | Name type | 0..1 | CodeableConcept |  |  |
| `SubstanceSpecification.nucleicAcid` | `SubstanceSpecification.nucleicAcid` | `nucleicAcid` | SubstanceSpecification.nucleicAcid | Data items specific to nucleic acids | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/SubstanceNucleicAcid) |  |  |
| `SubstanceSpecification.polymer` | `SubstanceSpecification.polymer` | `polymer` | SubstanceSpecification.polymer | Data items specific to polymers | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/SubstancePolymer) |  |  |
| `SubstanceSpecification.property` | `SubstanceSpecification.property` | `property` | SubstanceSpecification.property | General specifications for this substance, including how it is related to other substances | 0..* | BackboneElement |  |  |
| `SubstanceSpecification.property.amount[x]` | `SubstanceSpecification.property.amount[x]` | `amount[x]` | SubstanceSpecification.property.amount[x] | Quantitative value for this property | 0..1 | Quantity, string |  |  |
| `SubstanceSpecification.property.category` | `SubstanceSpecification.property.category` | `category` | SubstanceSpecification.property.category | A category for this property, e.g. Physical, Chemical, Enzymatic | 0..1 | CodeableConcept |  |  |
| `SubstanceSpecification.property.code` | `SubstanceSpecification.property.code` | `code` | SubstanceSpecification.property.code | Property type e.g. viscosity, pH, isoelectric point | 0..1 | CodeableConcept |  |  |
| `SubstanceSpecification.property.definingSubstance[x]` | `SubstanceSpecification.property.definingSubstance[x]` | `definingSubstance[x]` | SubstanceSpecification.property.definingSubstance[x] | A substance upon which a defining property depends (e.g. for solubility: in water, in alcohol) | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Substance), Reference(http://hl7.org/fhir/StructureDefinition/SubstanceSpecification) |  |  |
| `SubstanceSpecification.property.extension` | `SubstanceSpecification.property.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceSpecification.property.id` | `SubstanceSpecification.property.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceSpecification.property.modifierExtension` | `SubstanceSpecification.property.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceSpecification.property.parameters` | `SubstanceSpecification.property.parameters` | `parameters` | SubstanceSpecification.property.parameters | Parameters that were used in the measurement of a property (e.g. for viscosity: measured at 20C with a pH of 7.1) | 0..1 | string |  |  |
| `SubstanceSpecification.protein` | `SubstanceSpecification.protein` | `protein` | SubstanceSpecification.protein | Data items specific to proteins | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/SubstanceProtein) |  |  |
| `SubstanceSpecification.referenceInformation` | `SubstanceSpecification.referenceInformation` | `referenceInformation` | SubstanceSpecification.referenceInformation | General information detailing this substance | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/SubstanceReferenceInformation) |  |  |
| `SubstanceSpecification.relationship` | `SubstanceSpecification.relationship` | `relationship` | SubstanceSpecification.relationship | A link between this substance and another, with details of the relationship | 0..* | BackboneElement |  |  |
| `SubstanceSpecification.relationship.amountRatioLowLimit` | `SubstanceSpecification.relationship.amountRatioLowLimit` | `amountRatioLowLimit` | SubstanceSpecification.relationship.amountRatioLowLimit | For use when the numeric | 0..1 | Ratio |  |  |
| `SubstanceSpecification.relationship.amountType` | `SubstanceSpecification.relationship.amountType` | `amountType` | SubstanceSpecification.relationship.amountType | An operator for the amount, for example "average", "approximately", "less than" | 0..1 | CodeableConcept |  |  |
| `SubstanceSpecification.relationship.amount[x]` | `SubstanceSpecification.relationship.amount[x]` | `amount[x]` | SubstanceSpecification.relationship.amount[x] | A numeric factor for the relationship, for instance to express that the salt of a substance has some percentage of the active substance in relation to some other | 0..1 | Quantity, Range, Ratio, string |  |  |
| `SubstanceSpecification.relationship.extension` | `SubstanceSpecification.relationship.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceSpecification.relationship.id` | `SubstanceSpecification.relationship.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceSpecification.relationship.isDefining` | `SubstanceSpecification.relationship.isDefining` | `isDefining` | SubstanceSpecification.relationship.isDefining | For example where an enzyme strongly bonds with a particular substance, this is a defining relationship for that enzyme, out of several possible substance relationships | 0..1 | boolean |  |  |
| `SubstanceSpecification.relationship.modifierExtension` | `SubstanceSpecification.relationship.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceSpecification.relationship.relationship` | `SubstanceSpecification.relationship.relationship` | `relationship` | SubstanceSpecification.relationship.relationship | For example "salt to parent", "active moiety", "starting material" | 0..1 | CodeableConcept |  |  |
| `SubstanceSpecification.relationship.source` | `SubstanceSpecification.relationship.source` | `source` | SubstanceSpecification.relationship.source | Supporting literature | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `SubstanceSpecification.relationship.substance[x]` | `SubstanceSpecification.relationship.substance[x]` | `substance[x]` | SubstanceSpecification.relationship.substance[x] | A pointer to another substance, as a resource or just a representational code | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/SubstanceSpecification) |  |  |
| `SubstanceSpecification.source` | `SubstanceSpecification.source` | `source` | SubstanceSpecification.source | Supporting literature | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `SubstanceSpecification.sourceMaterial` | `SubstanceSpecification.sourceMaterial` | `sourceMaterial` | SubstanceSpecification.sourceMaterial | Material or taxonomic/anatomical source for the substance | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/SubstanceSourceMaterial) |  |  |
| `SubstanceSpecification.status` | `SubstanceSpecification.status` | `status` | SubstanceSpecification.status | Status of substance within the catalogue e.g. approved | 0..1 | CodeableConcept |  |  |
| `SubstanceSpecification.structure` | `SubstanceSpecification.structure` | `structure` | SubstanceSpecification.structure | Structural information | 0..1 | BackboneElement |  |  |
| `SubstanceSpecification.structure.extension` | `SubstanceSpecification.structure.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceSpecification.structure.id` | `SubstanceSpecification.structure.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceSpecification.structure.isotope` | `SubstanceSpecification.structure.isotope` | `isotope` | SubstanceSpecification.structure.isotope | Applicable for single substances that contain a radionuclide or a non-natural isotopic ratio | 0..* | BackboneElement |  |  |
| `SubstanceSpecification.structure.isotope.extension` | `SubstanceSpecification.structure.isotope.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceSpecification.structure.isotope.halfLife` | `SubstanceSpecification.structure.isotope.halfLife` | `halfLife` | SubstanceSpecification.structure.isotope.halfLife | Half life - for a non-natural nuclide | 0..1 | Quantity |  |  |
| `SubstanceSpecification.structure.isotope.id` | `SubstanceSpecification.structure.isotope.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceSpecification.structure.isotope.identifier` | `SubstanceSpecification.structure.isotope.identifier` | `identifier` | SubstanceSpecification.structure.isotope.identifier | Substance identifier for each non-natural or radioisotope | 0..1 | Identifier |  |  |
| `SubstanceSpecification.structure.isotope.modifierExtension` | `SubstanceSpecification.structure.isotope.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceSpecification.structure.isotope.molecularWeight` | `SubstanceSpecification.structure.isotope.molecularWeight` | `molecularWeight` | SubstanceSpecification.structure.isotope.molecularWeight | The molecular weight or weight range (for proteins, polymers or nucleic acids) | 0..1 | BackboneElement |  |  |
| `SubstanceSpecification.structure.isotope.molecularWeight.amount` | `SubstanceSpecification.structure.isotope.molecularWeight.amount` | `amount` | SubstanceSpecification.structure.isotope.molecularWeight.amount | Used to capture quantitative values for a variety of elements. If only limits are given, the arithmetic mean would be the average. If only a single definite value for a given element is given, it would be captured in this field | 0..1 | Quantity |  |  |
| `SubstanceSpecification.structure.isotope.molecularWeight.extension` | `SubstanceSpecification.structure.isotope.molecularWeight.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceSpecification.structure.isotope.molecularWeight.id` | `SubstanceSpecification.structure.isotope.molecularWeight.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceSpecification.structure.isotope.molecularWeight.method` | `SubstanceSpecification.structure.isotope.molecularWeight.method` | `method` | SubstanceSpecification.structure.isotope.molecularWeight.method | The method by which the molecular weight was determined | 0..1 | CodeableConcept |  |  |
| `SubstanceSpecification.structure.isotope.molecularWeight.modifierExtension` | `SubstanceSpecification.structure.isotope.molecularWeight.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceSpecification.structure.isotope.molecularWeight.type` | `SubstanceSpecification.structure.isotope.molecularWeight.type` | `type` | SubstanceSpecification.structure.isotope.molecularWeight.type | Type of molecular weight such as exact, average (also known as. number average), weight average | 0..1 | CodeableConcept |  |  |
| `SubstanceSpecification.structure.isotope.name` | `SubstanceSpecification.structure.isotope.name` | `name` | SubstanceSpecification.structure.isotope.name | Substance name for each non-natural or radioisotope | 0..1 | CodeableConcept |  |  |
| `SubstanceSpecification.structure.isotope.substitution` | `SubstanceSpecification.structure.isotope.substitution` | `substitution` | SubstanceSpecification.structure.isotope.substitution | The type of isotopic substitution present in a single substance | 0..1 | CodeableConcept |  |  |
| `SubstanceSpecification.structure.modifierExtension` | `SubstanceSpecification.structure.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceSpecification.structure.molecularFormula` | `SubstanceSpecification.structure.molecularFormula` | `molecularFormula` | SubstanceSpecification.structure.molecularFormula | Molecular formula | 0..1 | string |  |  |
| `SubstanceSpecification.structure.molecularFormulaByMoiety` | `SubstanceSpecification.structure.molecularFormulaByMoiety` | `molecularFormulaByMoiety` | SubstanceSpecification.structure.molecularFormulaByMoiety | Specified per moiety according to the Hill system, i.e. first C, then H, then alphabetical, each moiety separated by a dot | 0..1 | string |  |  |
| `SubstanceSpecification.structure.molecularWeight` | `SubstanceSpecification.structure.molecularWeight` | `molecularWeight` | SubstanceSpecification.structure.molecularWeight | The molecular weight or weight range (for proteins, polymers or nucleic acids) | 0..1 | SubstanceSpecification.structure.isotope.molecularWeight |  |  |
| `SubstanceSpecification.structure.opticalActivity` | `SubstanceSpecification.structure.opticalActivity` | `opticalActivity` | SubstanceSpecification.structure.opticalActivity | Optical activity type | 0..1 | CodeableConcept |  |  |
| `SubstanceSpecification.structure.representation` | `SubstanceSpecification.structure.representation` | `representation` | SubstanceSpecification.structure.representation | Molecular structural representation | 0..* | BackboneElement |  |  |
| `SubstanceSpecification.structure.representation.attachment` | `SubstanceSpecification.structure.representation.attachment` | `attachment` | SubstanceSpecification.structure.representation.attachment | An attached file with the structural representation | 0..1 | Attachment |  |  |
| `SubstanceSpecification.structure.representation.extension` | `SubstanceSpecification.structure.representation.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstanceSpecification.structure.representation.id` | `SubstanceSpecification.structure.representation.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstanceSpecification.structure.representation.modifierExtension` | `SubstanceSpecification.structure.representation.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstanceSpecification.structure.representation.representation` | `SubstanceSpecification.structure.representation.representation` | `representation` | SubstanceSpecification.structure.representation.representation | The structural representation as text string in a format e.g. InChI, SMILES, MOLFILE, CDX | 0..1 | string |  |  |
| `SubstanceSpecification.structure.representation.type` | `SubstanceSpecification.structure.representation.type` | `type` | SubstanceSpecification.structure.representation.type | The type of structure (e.g. Full, Partial, Representative) | 0..1 | CodeableConcept |  |  |
| `SubstanceSpecification.structure.source` | `SubstanceSpecification.structure.source` | `source` | SubstanceSpecification.structure.source | Supporting literature | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `SubstanceSpecification.structure.stereochemistry` | `SubstanceSpecification.structure.stereochemistry` | `stereochemistry` | SubstanceSpecification.structure.stereochemistry | Stereochemistry type | 0..1 | CodeableConcept |  |  |
| `SubstanceSpecification.text` | `SubstanceSpecification.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `SubstanceSpecification.type` | `SubstanceSpecification.type` | `type` | SubstanceSpecification.type | High level categorization, e.g. polymer or nucleic acid | 0..1 | CodeableConcept |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

