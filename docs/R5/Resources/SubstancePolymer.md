Comparison of 
Generated at Monday, April 14, 2025 6:17:45 PM

### SubstancePolymer

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | SubstancePolymer |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/SubstancePolymer` |
| Version | 5.0.0 |
| Description | Properties of a substance specific to it being a polymer. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2393` |
| Database Snapshot Count | `56` |
| Database Differential Count | `30` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `SubstancePolymer` | `SubstancePolymer` | `SubstancePolymer` | SubstancePolymer | Properties of a substance specific to it being a polymer | 0..* | SubstancePolymer |  |  |
| `SubstancePolymer.class` | `SubstancePolymer.class` | `class` | SubstancePolymer.class | Overall type of the polymer | 0..1 | CodeableConcept |  |  |
| `SubstancePolymer.contained` | `SubstancePolymer.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `SubstancePolymer.copolymerConnectivity` | `SubstancePolymer.copolymerConnectivity` | `copolymerConnectivity` | SubstancePolymer.copolymerConnectivity | Descrtibes the copolymer sequence type (polymer connectivity) | 0..* | CodeableConcept |  |  |
| `SubstancePolymer.extension` | `SubstancePolymer.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstancePolymer.geometry` | `SubstancePolymer.geometry` | `geometry` | SubstancePolymer.geometry | Polymer geometry, e.g. linear, branched, cross-linked, network or dendritic | 0..1 | CodeableConcept |  |  |
| `SubstancePolymer.id` | `SubstancePolymer.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `SubstancePolymer.identifier` | `SubstancePolymer.identifier` | `identifier` | SubstancePolymer.identifier | A business idenfier for this polymer, but typically this is handled by a SubstanceDefinition identifier | 0..1 | Identifier |  |  |
| `SubstancePolymer.implicitRules` | `SubstancePolymer.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `SubstancePolymer.language` | `SubstancePolymer.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `SubstancePolymer.meta` | `SubstancePolymer.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `SubstancePolymer.modification` | `SubstancePolymer.modification` | `modification` | SubstancePolymer.modification | Todo - this is intended to connect to a repeating full modification structure, also used by Protein and Nucleic Acid . String is just a placeholder | 0..1 | string |  |  |
| `SubstancePolymer.modifierExtension` | `SubstancePolymer.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `SubstancePolymer.monomerSet` | `SubstancePolymer.monomerSet` | `monomerSet` | SubstancePolymer.monomerSet | Todo | 0..* | BackboneElement |  |  |
| `SubstancePolymer.monomerSet.extension` | `SubstancePolymer.monomerSet.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstancePolymer.monomerSet.id` | `SubstancePolymer.monomerSet.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstancePolymer.monomerSet.modifierExtension` | `SubstancePolymer.monomerSet.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstancePolymer.monomerSet.ratioType` | `SubstancePolymer.monomerSet.ratioType` | `ratioType` | SubstancePolymer.monomerSet.ratioType | Captures the type of ratio to the entire polymer, e.g. Monomer/Polymer ratio, SRU/Polymer Ratio | 0..1 | CodeableConcept |  |  |
| `SubstancePolymer.monomerSet.startingMaterial` | `SubstancePolymer.monomerSet.startingMaterial` | `startingMaterial` | SubstancePolymer.monomerSet.startingMaterial | The starting materials - monomer(s) used in the synthesis of the polymer | 0..* | BackboneElement |  |  |
| `SubstancePolymer.monomerSet.startingMaterial.amount` | `SubstancePolymer.monomerSet.startingMaterial.amount` | `amount` | SubstancePolymer.monomerSet.startingMaterial.amount | A percentage | 0..1 | Quantity |  |  |
| `SubstancePolymer.monomerSet.startingMaterial.category` | `SubstancePolymer.monomerSet.startingMaterial.category` | `category` | SubstancePolymer.monomerSet.startingMaterial.category | Substance high level category, e.g. chemical substance | 0..1 | CodeableConcept |  |  |
| `SubstancePolymer.monomerSet.startingMaterial.code` | `SubstancePolymer.monomerSet.startingMaterial.code` | `code` | SubstancePolymer.monomerSet.startingMaterial.code | The type of substance for this starting material | 0..1 | CodeableConcept |  |  |
| `SubstancePolymer.monomerSet.startingMaterial.extension` | `SubstancePolymer.monomerSet.startingMaterial.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstancePolymer.monomerSet.startingMaterial.id` | `SubstancePolymer.monomerSet.startingMaterial.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstancePolymer.monomerSet.startingMaterial.isDefining` | `SubstancePolymer.monomerSet.startingMaterial.isDefining` | `isDefining` | SubstancePolymer.monomerSet.startingMaterial.isDefining | Used to specify whether the attribute described is a defining element for the unique identification of the polymer | 0..1 | boolean |  |  |
| `SubstancePolymer.monomerSet.startingMaterial.modifierExtension` | `SubstancePolymer.monomerSet.startingMaterial.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstancePolymer.repeat` | `SubstancePolymer.repeat` | `repeat` | SubstancePolymer.repeat | Specifies and quantifies the repeated units and their configuration | 0..* | BackboneElement |  |  |
| `SubstancePolymer.repeat.averageMolecularFormula` | `SubstancePolymer.repeat.averageMolecularFormula` | `averageMolecularFormula` | SubstancePolymer.repeat.averageMolecularFormula | A representation of an (average) molecular formula from a polymer | 0..1 | string |  |  |
| `SubstancePolymer.repeat.extension` | `SubstancePolymer.repeat.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstancePolymer.repeat.id` | `SubstancePolymer.repeat.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstancePolymer.repeat.modifierExtension` | `SubstancePolymer.repeat.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstancePolymer.repeat.repeatUnit` | `SubstancePolymer.repeat.repeatUnit` | `repeatUnit` | SubstancePolymer.repeat.repeatUnit | An SRU - Structural Repeat Unit | 0..* | BackboneElement |  |  |
| `SubstancePolymer.repeat.repeatUnit.amount` | `SubstancePolymer.repeat.repeatUnit.amount` | `amount` | SubstancePolymer.repeat.repeatUnit.amount | Number of repeats of this unit | 0..1 | integer |  |  |
| `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation` | `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation` | `degreeOfPolymerisation` | SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation | Applies to homopolymer and block co-polymers where the degree of polymerisation within a block can be described | 0..* | BackboneElement |  |  |
| `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.average` | `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.average` | `average` | SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.average | An average amount of polymerisation | 0..1 | integer |  |  |
| `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.extension` | `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.high` | `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.high` | `high` | SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.high | A high expected limit of the amount | 0..1 | integer |  |  |
| `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.id` | `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.low` | `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.low` | `low` | SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.low | A low expected limit of the amount | 0..1 | integer |  |  |
| `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.modifierExtension` | `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.type` | `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.type` | `type` | SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.type | The type of the degree of polymerisation shall be described, e.g. SRU/Polymer Ratio | 0..1 | CodeableConcept |  |  |
| `SubstancePolymer.repeat.repeatUnit.extension` | `SubstancePolymer.repeat.repeatUnit.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstancePolymer.repeat.repeatUnit.id` | `SubstancePolymer.repeat.repeatUnit.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstancePolymer.repeat.repeatUnit.modifierExtension` | `SubstancePolymer.repeat.repeatUnit.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstancePolymer.repeat.repeatUnit.orientation` | `SubstancePolymer.repeat.repeatUnit.orientation` | `orientation` | SubstancePolymer.repeat.repeatUnit.orientation | The orientation of the polymerisation, e.g. head-tail, head-head, random | 0..1 | CodeableConcept |  |  |
| `SubstancePolymer.repeat.repeatUnit.structuralRepresentation` | `SubstancePolymer.repeat.repeatUnit.structuralRepresentation` | `structuralRepresentation` | SubstancePolymer.repeat.repeatUnit.structuralRepresentation | A graphical structure for this SRU | 0..* | BackboneElement |  |  |
| `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.attachment` | `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.attachment` | `attachment` | SubstancePolymer.repeat.repeatUnit.structuralRepresentation.attachment | An attached file with the structural representation | 0..1 | Attachment |  |  |
| `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.extension` | `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.format` | `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.format` | `format` | SubstancePolymer.repeat.repeatUnit.structuralRepresentation.format | The format of the representation e.g. InChI, SMILES, MOLFILE, CDX, SDF, PDB, mmCIF | 0..1 | CodeableConcept |  |  |
| `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.id` | `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.modifierExtension` | `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.representation` | `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.representation` | `representation` | SubstancePolymer.repeat.repeatUnit.structuralRepresentation.representation | The structural representation as text string in a standard format e.g. InChI, SMILES, MOLFILE, CDX, SDF, PDB, mmCIF | 0..1 | string |  |  |
| `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.type` | `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.type` | `type` | SubstancePolymer.repeat.repeatUnit.structuralRepresentation.type | The type of structure (e.g. Full, Partial, Representative) | 0..1 | CodeableConcept |  |  |
| `SubstancePolymer.repeat.repeatUnit.unit` | `SubstancePolymer.repeat.repeatUnit.unit` | `unit` | SubstancePolymer.repeat.repeatUnit.unit | Structural repeat units are essential elements for defining polymers | 0..1 | string |  |  |
| `SubstancePolymer.repeat.repeatUnitAmountType` | `SubstancePolymer.repeat.repeatUnitAmountType` | `repeatUnitAmountType` | SubstancePolymer.repeat.repeatUnitAmountType | How the quantitative amount of Structural Repeat Units is captured (e.g. Exact, Numeric, Average) | 0..1 | CodeableConcept |  |  |
| `SubstancePolymer.text` | `SubstancePolymer.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

