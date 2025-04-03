Comparison of 
Generated at Thursday, April 3, 2025 8:18:18 AM

### MedicinalProductIngredient

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | MedicinalProductIngredient |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/MedicinalProductIngredient` |
| Version | 4.0.1 |
| Description | An ingredient of a manufactured item or pharmaceutical product. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1116` |
| Database Snapshot Count | `45` |
| Database Differential Count | `25` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `MedicinalProductIngredient` | `MedicinalProductIngredient` | `MedicinalProductIngredient` | MedicinalProductIngredient | An ingredient of a manufactured item or pharmaceutical product | 0..* | MedicinalProductIngredient |  |  |
| `MedicinalProductIngredient.allergenicIndicator` | `MedicinalProductIngredient.allergenicIndicator` | `allergenicIndicator` | MedicinalProductIngredient.allergenicIndicator | If the ingredient is a known or suspected allergen | 0..1 | boolean |  |  |
| `MedicinalProductIngredient.contained` | `MedicinalProductIngredient.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `MedicinalProductIngredient.extension` | `MedicinalProductIngredient.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductIngredient.id` | `MedicinalProductIngredient.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `MedicinalProductIngredient.identifier` | `MedicinalProductIngredient.identifier` | `identifier` | MedicinalProductIngredient.identifier | Identifier for the ingredient | 0..1 | Identifier |  |  |
| `MedicinalProductIngredient.implicitRules` | `MedicinalProductIngredient.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `MedicinalProductIngredient.language` | `MedicinalProductIngredient.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `MedicinalProductIngredient.manufacturer` | `MedicinalProductIngredient.manufacturer` | `manufacturer` | MedicinalProductIngredient.manufacturer | Manufacturer of this Ingredient | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `MedicinalProductIngredient.meta` | `MedicinalProductIngredient.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `MedicinalProductIngredient.modifierExtension` | `MedicinalProductIngredient.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MedicinalProductIngredient.role` | `MedicinalProductIngredient.role` | `role` | MedicinalProductIngredient.role | Ingredient role e.g. Active ingredient, excipient | 1..1 | CodeableConcept |  |  |
| `MedicinalProductIngredient.specifiedSubstance` | `MedicinalProductIngredient.specifiedSubstance` | `specifiedSubstance` | MedicinalProductIngredient.specifiedSubstance | A specified substance that comprises this ingredient | 0..* | BackboneElement |  |  |
| `MedicinalProductIngredient.specifiedSubstance.code` | `MedicinalProductIngredient.specifiedSubstance.code` | `code` | MedicinalProductIngredient.specifiedSubstance.code | The specified substance | 1..1 | CodeableConcept |  |  |
| `MedicinalProductIngredient.specifiedSubstance.confidentiality` | `MedicinalProductIngredient.specifiedSubstance.confidentiality` | `confidentiality` | MedicinalProductIngredient.specifiedSubstance.confidentiality | Confidentiality level of the specified substance as the ingredient | 0..1 | CodeableConcept |  |  |
| `MedicinalProductIngredient.specifiedSubstance.extension` | `MedicinalProductIngredient.specifiedSubstance.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductIngredient.specifiedSubstance.group` | `MedicinalProductIngredient.specifiedSubstance.group` | `group` | MedicinalProductIngredient.specifiedSubstance.group | The group of specified substance, e.g. group 1 to 4 | 1..1 | CodeableConcept |  |  |
| `MedicinalProductIngredient.specifiedSubstance.id` | `MedicinalProductIngredient.specifiedSubstance.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProductIngredient.specifiedSubstance.modifierExtension` | `MedicinalProductIngredient.specifiedSubstance.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProductIngredient.specifiedSubstance.strength` | `MedicinalProductIngredient.specifiedSubstance.strength` | `strength` | MedicinalProductIngredient.specifiedSubstance.strength | Quantity of the substance or specified substance present in the manufactured item or pharmaceutical product | 0..* | BackboneElement |  |  |
| `MedicinalProductIngredient.specifiedSubstance.strength.concentration` | `MedicinalProductIngredient.specifiedSubstance.strength.concentration` | `concentration` | MedicinalProductIngredient.specifiedSubstance.strength.concentration | The strength per unitary volume (or mass) | 0..1 | Ratio |  |  |
| `MedicinalProductIngredient.specifiedSubstance.strength.concentrationLowLimit` | `MedicinalProductIngredient.specifiedSubstance.strength.concentrationLowLimit` | `concentrationLowLimit` | MedicinalProductIngredient.specifiedSubstance.strength.concentrationLowLimit | A lower limit for the strength per unitary volume (or mass), for when there is a range. The concentration attribute then becomes the upper limit | 0..1 | Ratio |  |  |
| `MedicinalProductIngredient.specifiedSubstance.strength.country` | `MedicinalProductIngredient.specifiedSubstance.strength.country` | `country` | MedicinalProductIngredient.specifiedSubstance.strength.country | The country or countries for which the strength range applies | 0..* | CodeableConcept |  |  |
| `MedicinalProductIngredient.specifiedSubstance.strength.extension` | `MedicinalProductIngredient.specifiedSubstance.strength.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductIngredient.specifiedSubstance.strength.id` | `MedicinalProductIngredient.specifiedSubstance.strength.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProductIngredient.specifiedSubstance.strength.measurementPoint` | `MedicinalProductIngredient.specifiedSubstance.strength.measurementPoint` | `measurementPoint` | MedicinalProductIngredient.specifiedSubstance.strength.measurementPoint | For when strength is measured at a particular point or distance | 0..1 | string |  |  |
| `MedicinalProductIngredient.specifiedSubstance.strength.modifierExtension` | `MedicinalProductIngredient.specifiedSubstance.strength.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProductIngredient.specifiedSubstance.strength.presentation` | `MedicinalProductIngredient.specifiedSubstance.strength.presentation` | `presentation` | MedicinalProductIngredient.specifiedSubstance.strength.presentation | The quantity of substance in the unit of presentation, or in the volume (or mass) of the single pharmaceutical product or manufactured item | 1..1 | Ratio |  |  |
| `MedicinalProductIngredient.specifiedSubstance.strength.presentationLowLimit` | `MedicinalProductIngredient.specifiedSubstance.strength.presentationLowLimit` | `presentationLowLimit` | MedicinalProductIngredient.specifiedSubstance.strength.presentationLowLimit | A lower limit for the quantity of substance in the unit of presentation. For use when there is a range of strengths, this is the lower limit, with the presentation attribute becoming the upper limit | 0..1 | Ratio |  |  |
| `MedicinalProductIngredient.specifiedSubstance.strength.referenceStrength` | `MedicinalProductIngredient.specifiedSubstance.strength.referenceStrength` | `referenceStrength` | MedicinalProductIngredient.specifiedSubstance.strength.referenceStrength | Strength expressed in terms of a reference substance | 0..* | BackboneElement |  |  |
| `MedicinalProductIngredient.specifiedSubstance.strength.referenceStrength.country` | `MedicinalProductIngredient.specifiedSubstance.strength.referenceStrength.country` | `country` | MedicinalProductIngredient.specifiedSubstance.strength.referenceStrength.country | The country or countries for which the strength range applies | 0..* | CodeableConcept |  |  |
| `MedicinalProductIngredient.specifiedSubstance.strength.referenceStrength.extension` | `MedicinalProductIngredient.specifiedSubstance.strength.referenceStrength.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductIngredient.specifiedSubstance.strength.referenceStrength.id` | `MedicinalProductIngredient.specifiedSubstance.strength.referenceStrength.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProductIngredient.specifiedSubstance.strength.referenceStrength.measurementPoint` | `MedicinalProductIngredient.specifiedSubstance.strength.referenceStrength.measurementPoint` | `measurementPoint` | MedicinalProductIngredient.specifiedSubstance.strength.referenceStrength.measurementPoint | For when strength is measured at a particular point or distance | 0..1 | string |  |  |
| `MedicinalProductIngredient.specifiedSubstance.strength.referenceStrength.modifierExtension` | `MedicinalProductIngredient.specifiedSubstance.strength.referenceStrength.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProductIngredient.specifiedSubstance.strength.referenceStrength.strength` | `MedicinalProductIngredient.specifiedSubstance.strength.referenceStrength.strength` | `strength` | MedicinalProductIngredient.specifiedSubstance.strength.referenceStrength.strength | Strength expressed in terms of a reference substance | 1..1 | Ratio |  |  |
| `MedicinalProductIngredient.specifiedSubstance.strength.referenceStrength.strengthLowLimit` | `MedicinalProductIngredient.specifiedSubstance.strength.referenceStrength.strengthLowLimit` | `strengthLowLimit` | MedicinalProductIngredient.specifiedSubstance.strength.referenceStrength.strengthLowLimit | Strength expressed in terms of a reference substance | 0..1 | Ratio |  |  |
| `MedicinalProductIngredient.specifiedSubstance.strength.referenceStrength.substance` | `MedicinalProductIngredient.specifiedSubstance.strength.referenceStrength.substance` | `substance` | MedicinalProductIngredient.specifiedSubstance.strength.referenceStrength.substance | Relevant reference substance | 0..1 | CodeableConcept |  |  |
| `MedicinalProductIngredient.substance` | `MedicinalProductIngredient.substance` | `substance` | MedicinalProductIngredient.substance | The ingredient substance | 0..1 | BackboneElement |  |  |
| `MedicinalProductIngredient.substance.code` | `MedicinalProductIngredient.substance.code` | `code` | MedicinalProductIngredient.substance.code | The ingredient substance | 1..1 | CodeableConcept |  |  |
| `MedicinalProductIngredient.substance.extension` | `MedicinalProductIngredient.substance.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductIngredient.substance.id` | `MedicinalProductIngredient.substance.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProductIngredient.substance.modifierExtension` | `MedicinalProductIngredient.substance.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProductIngredient.substance.strength` | `MedicinalProductIngredient.substance.strength` | `strength` | MedicinalProductIngredient.substance.strength | Quantity of the substance or specified substance present in the manufactured item or pharmaceutical product | 0..* | MedicinalProductIngredient.specifiedSubstance.strength |  |  |
| `MedicinalProductIngredient.text` | `MedicinalProductIngredient.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

