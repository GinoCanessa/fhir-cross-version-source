Comparison of 
Generated at Monday, April 14, 2025 6:17:32 PM

### SubstancePolymer

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | SubstancePolymer |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/SubstancePolymer` |
| Version | 4.0.1 |
| Description | Todo. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1165` |
| Database Snapshot Count | `53` |
| Database Differential Count | `27` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `SubstancePolymer` | `SubstancePolymer` | `SubstancePolymer` | SubstancePolymer | Todo | 0..* | SubstancePolymer |  |  |
| `SubstancePolymer.class` | `SubstancePolymer.class` | `class` | SubstancePolymer.class | Todo | 0..1 | CodeableConcept |  |  |
| `SubstancePolymer.contained` | `SubstancePolymer.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `SubstancePolymer.copolymerConnectivity` | `SubstancePolymer.copolymerConnectivity` | `copolymerConnectivity` | SubstancePolymer.copolymerConnectivity | Todo | 0..* | CodeableConcept |  |  |
| `SubstancePolymer.extension` | `SubstancePolymer.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstancePolymer.geometry` | `SubstancePolymer.geometry` | `geometry` | SubstancePolymer.geometry | Todo | 0..1 | CodeableConcept |  |  |
| `SubstancePolymer.id` | `SubstancePolymer.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `SubstancePolymer.implicitRules` | `SubstancePolymer.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `SubstancePolymer.language` | `SubstancePolymer.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `SubstancePolymer.meta` | `SubstancePolymer.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `SubstancePolymer.modification` | `SubstancePolymer.modification` | `modification` | SubstancePolymer.modification | Todo | 0..* | string |  |  |
| `SubstancePolymer.modifierExtension` | `SubstancePolymer.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `SubstancePolymer.monomerSet` | `SubstancePolymer.monomerSet` | `monomerSet` | SubstancePolymer.monomerSet | Todo | 0..* | BackboneElement |  |  |
| `SubstancePolymer.monomerSet.extension` | `SubstancePolymer.monomerSet.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstancePolymer.monomerSet.id` | `SubstancePolymer.monomerSet.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstancePolymer.monomerSet.modifierExtension` | `SubstancePolymer.monomerSet.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstancePolymer.monomerSet.ratioType` | `SubstancePolymer.monomerSet.ratioType` | `ratioType` | SubstancePolymer.monomerSet.ratioType | Todo | 0..1 | CodeableConcept |  |  |
| `SubstancePolymer.monomerSet.startingMaterial` | `SubstancePolymer.monomerSet.startingMaterial` | `startingMaterial` | SubstancePolymer.monomerSet.startingMaterial | Todo | 0..* | BackboneElement |  |  |
| `SubstancePolymer.monomerSet.startingMaterial.amount` | `SubstancePolymer.monomerSet.startingMaterial.amount` | `amount` | SubstancePolymer.monomerSet.startingMaterial.amount | Todo | 0..1 | SubstanceAmount |  |  |
| `SubstancePolymer.monomerSet.startingMaterial.extension` | `SubstancePolymer.monomerSet.startingMaterial.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstancePolymer.monomerSet.startingMaterial.id` | `SubstancePolymer.monomerSet.startingMaterial.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstancePolymer.monomerSet.startingMaterial.isDefining` | `SubstancePolymer.monomerSet.startingMaterial.isDefining` | `isDefining` | SubstancePolymer.monomerSet.startingMaterial.isDefining | Todo | 0..1 | boolean |  |  |
| `SubstancePolymer.monomerSet.startingMaterial.material` | `SubstancePolymer.monomerSet.startingMaterial.material` | `material` | SubstancePolymer.monomerSet.startingMaterial.material | Todo | 0..1 | CodeableConcept |  |  |
| `SubstancePolymer.monomerSet.startingMaterial.modifierExtension` | `SubstancePolymer.monomerSet.startingMaterial.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstancePolymer.monomerSet.startingMaterial.type` | `SubstancePolymer.monomerSet.startingMaterial.type` | `type` | SubstancePolymer.monomerSet.startingMaterial.type | Todo | 0..1 | CodeableConcept |  |  |
| `SubstancePolymer.repeat` | `SubstancePolymer.repeat` | `repeat` | SubstancePolymer.repeat | Todo | 0..* | BackboneElement |  |  |
| `SubstancePolymer.repeat.averageMolecularFormula` | `SubstancePolymer.repeat.averageMolecularFormula` | `averageMolecularFormula` | SubstancePolymer.repeat.averageMolecularFormula | Todo | 0..1 | string |  |  |
| `SubstancePolymer.repeat.extension` | `SubstancePolymer.repeat.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstancePolymer.repeat.id` | `SubstancePolymer.repeat.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstancePolymer.repeat.modifierExtension` | `SubstancePolymer.repeat.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstancePolymer.repeat.numberOfUnits` | `SubstancePolymer.repeat.numberOfUnits` | `numberOfUnits` | SubstancePolymer.repeat.numberOfUnits | Todo | 0..1 | integer |  |  |
| `SubstancePolymer.repeat.repeatUnit` | `SubstancePolymer.repeat.repeatUnit` | `repeatUnit` | SubstancePolymer.repeat.repeatUnit | Todo | 0..* | BackboneElement |  |  |
| `SubstancePolymer.repeat.repeatUnit.amount` | `SubstancePolymer.repeat.repeatUnit.amount` | `amount` | SubstancePolymer.repeat.repeatUnit.amount | Todo | 0..1 | SubstanceAmount |  |  |
| `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation` | `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation` | `degreeOfPolymerisation` | SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation | Todo | 0..* | BackboneElement |  |  |
| `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.amount` | `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.amount` | `amount` | SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.amount | Todo | 0..1 | SubstanceAmount |  |  |
| `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.degree` | `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.degree` | `degree` | SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.degree | Todo | 0..1 | CodeableConcept |  |  |
| `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.extension` | `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.id` | `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.modifierExtension` | `SubstancePolymer.repeat.repeatUnit.degreeOfPolymerisation.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstancePolymer.repeat.repeatUnit.extension` | `SubstancePolymer.repeat.repeatUnit.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstancePolymer.repeat.repeatUnit.id` | `SubstancePolymer.repeat.repeatUnit.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstancePolymer.repeat.repeatUnit.modifierExtension` | `SubstancePolymer.repeat.repeatUnit.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstancePolymer.repeat.repeatUnit.orientationOfPolymerisation` | `SubstancePolymer.repeat.repeatUnit.orientationOfPolymerisation` | `orientationOfPolymerisation` | SubstancePolymer.repeat.repeatUnit.orientationOfPolymerisation | Todo | 0..1 | CodeableConcept |  |  |
| `SubstancePolymer.repeat.repeatUnit.repeatUnit` | `SubstancePolymer.repeat.repeatUnit.repeatUnit` | `repeatUnit` | SubstancePolymer.repeat.repeatUnit.repeatUnit | Todo | 0..1 | string |  |  |
| `SubstancePolymer.repeat.repeatUnit.structuralRepresentation` | `SubstancePolymer.repeat.repeatUnit.structuralRepresentation` | `structuralRepresentation` | SubstancePolymer.repeat.repeatUnit.structuralRepresentation | Todo | 0..* | BackboneElement |  |  |
| `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.attachment` | `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.attachment` | `attachment` | SubstancePolymer.repeat.repeatUnit.structuralRepresentation.attachment | Todo | 0..1 | Attachment |  |  |
| `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.extension` | `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.id` | `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.modifierExtension` | `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.representation` | `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.representation` | `representation` | SubstancePolymer.repeat.repeatUnit.structuralRepresentation.representation | Todo | 0..1 | string |  |  |
| `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.type` | `SubstancePolymer.repeat.repeatUnit.structuralRepresentation.type` | `type` | SubstancePolymer.repeat.repeatUnit.structuralRepresentation.type | Todo | 0..1 | CodeableConcept |  |  |
| `SubstancePolymer.repeat.repeatUnitAmountType` | `SubstancePolymer.repeat.repeatUnitAmountType` | `repeatUnitAmountType` | SubstancePolymer.repeat.repeatUnitAmountType | Todo | 0..1 | CodeableConcept |  |  |
| `SubstancePolymer.text` | `SubstancePolymer.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

