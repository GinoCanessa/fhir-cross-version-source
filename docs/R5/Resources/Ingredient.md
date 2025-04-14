Comparison of 
Generated at Monday, April 14, 2025 6:17:49 PM

### Ingredient

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Ingredient |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Ingredient` |
| Version | 5.0.0 |
| Description | An ingredient of a manufactured item or pharmaceutical product. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2325` |
| Database Snapshot Count | `47` |
| Database Differential Count | `27` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Ingredient` | `Ingredient` | `Ingredient` | Ingredient | An ingredient of a manufactured item or pharmaceutical product | 0..* | Ingredient |  |  |
| `Ingredient.allergenicIndicator` | `Ingredient.allergenicIndicator` | `allergenicIndicator` | Ingredient.allergenicIndicator | If the ingredient is a known or suspected allergen | 0..1 | boolean |  |  |
| `Ingredient.comment` | `Ingredient.comment` | `comment` | Ingredient.comment | A place for providing any notes that are relevant to the component, e.g. removed during process, adjusted for loss on drying | 0..1 | markdown |  |  |
| `Ingredient.contained` | `Ingredient.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Ingredient.extension` | `Ingredient.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Ingredient.for` | `Ingredient.for` | `for` | Ingredient.for | The product which this ingredient is a constituent part of | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/AdministrableProductDefinition), Reference(http://hl7.org/fhir/StructureDefinition/ManufacturedItemDefinition), Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProductDefinition) |  |  |
| `Ingredient.function` | `Ingredient.function` | `function` | Ingredient.function | Precise action within the drug product, e.g. antioxidant, alkalizing agent | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/ingredient-function` |
| `Ingredient.group` | `Ingredient.group` | `group` | Ingredient.group | A classification of the ingredient according to where in the physical item it tends to be used, such the outer shell of a tablet, inner body or ink | 0..1 | CodeableConcept |  |  |
| `Ingredient.id` | `Ingredient.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Ingredient.identifier` | `Ingredient.identifier` | `identifier` | Ingredient.identifier | An identifier or code by which the ingredient can be referenced | 0..1 | Identifier |  |  |
| `Ingredient.implicitRules` | `Ingredient.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Ingredient.language` | `Ingredient.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `Ingredient.manufacturer` | `Ingredient.manufacturer` | `manufacturer` | Ingredient.manufacturer | An organization that manufactures this ingredient | 0..* | BackboneElement |  |  |
| `Ingredient.manufacturer.extension` | `Ingredient.manufacturer.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Ingredient.manufacturer.id` | `Ingredient.manufacturer.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Ingredient.manufacturer.manufacturer` | `Ingredient.manufacturer.manufacturer` | `manufacturer` | Ingredient.manufacturer.manufacturer | An organization that manufactures this ingredient | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Ingredient.manufacturer.modifierExtension` | `Ingredient.manufacturer.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Ingredient.manufacturer.role` | `Ingredient.manufacturer.role` | `role` | Ingredient.manufacturer.role | allowed \| possible \| actual | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/ingredient-manufacturer-role|5.0.0` |
| `Ingredient.meta` | `Ingredient.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Ingredient.modifierExtension` | `Ingredient.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Ingredient.role` | `Ingredient.role` | `role` | Ingredient.role | Purpose of the ingredient within the product, e.g. active, inactive | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/ingredient-role` |
| `Ingredient.status` | `Ingredient.status` | `status` | Ingredient.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|5.0.0` |
| `Ingredient.substance` | `Ingredient.substance` | `substance` | Ingredient.substance | The substance that comprises this ingredient | 1..1 | BackboneElement |  |  |
| `Ingredient.substance.code` | `Ingredient.substance.code` | `code` | Ingredient.substance.code | A code or full resource that represents the ingredient substance | 1..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/SubstanceDefinition) | `Example` | `http://hl7.org/fhir/ValueSet/substance-codes` |
| `Ingredient.substance.extension` | `Ingredient.substance.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Ingredient.substance.id` | `Ingredient.substance.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Ingredient.substance.modifierExtension` | `Ingredient.substance.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Ingredient.substance.strength` | `Ingredient.substance.strength` | `strength` | Ingredient.substance.strength | The quantity of substance, per presentation, or per volume or mass, and type of quantity | 0..* | BackboneElement |  |  |
| `Ingredient.substance.strength.basis` | `Ingredient.substance.strength.basis` | `basis` | Ingredient.substance.strength.basis | A code that indicates if the strength is, for example, based on the ingredient substance as stated or on the substance base (when the ingredient is a salt) | 0..1 | CodeableConcept |  |  |
| `Ingredient.substance.strength.concentration[x]` | `Ingredient.substance.strength.concentration[x]` | `concentration[x]` | Ingredient.substance.strength.concentration[x] | The strength per unitary volume (or mass) | 0..1 | CodeableConcept, Quantity, Ratio, RatioRange |  |  |
| `Ingredient.substance.strength.country` | `Ingredient.substance.strength.country` | `country` | Ingredient.substance.strength.country | Where the strength range applies | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/country` |
| `Ingredient.substance.strength.extension` | `Ingredient.substance.strength.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Ingredient.substance.strength.id` | `Ingredient.substance.strength.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Ingredient.substance.strength.measurementPoint` | `Ingredient.substance.strength.measurementPoint` | `measurementPoint` | Ingredient.substance.strength.measurementPoint | When strength is measured at a particular point or distance | 0..1 | string |  |  |
| `Ingredient.substance.strength.modifierExtension` | `Ingredient.substance.strength.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Ingredient.substance.strength.presentation[x]` | `Ingredient.substance.strength.presentation[x]` | `presentation[x]` | Ingredient.substance.strength.presentation[x] | The quantity of substance in the unit of presentation | 0..1 | CodeableConcept, Quantity, Ratio, RatioRange |  |  |
| `Ingredient.substance.strength.referenceStrength` | `Ingredient.substance.strength.referenceStrength` | `referenceStrength` | Ingredient.substance.strength.referenceStrength | Strength expressed in terms of a reference substance | 0..* | BackboneElement |  |  |
| `Ingredient.substance.strength.referenceStrength.country` | `Ingredient.substance.strength.referenceStrength.country` | `country` | Ingredient.substance.strength.referenceStrength.country | Where the strength range applies | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/country` |
| `Ingredient.substance.strength.referenceStrength.extension` | `Ingredient.substance.strength.referenceStrength.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Ingredient.substance.strength.referenceStrength.id` | `Ingredient.substance.strength.referenceStrength.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Ingredient.substance.strength.referenceStrength.measurementPoint` | `Ingredient.substance.strength.referenceStrength.measurementPoint` | `measurementPoint` | Ingredient.substance.strength.referenceStrength.measurementPoint | When strength is measured at a particular point or distance | 0..1 | string |  |  |
| `Ingredient.substance.strength.referenceStrength.modifierExtension` | `Ingredient.substance.strength.referenceStrength.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Ingredient.substance.strength.referenceStrength.strength[x]` | `Ingredient.substance.strength.referenceStrength.strength[x]` | `strength[x]` | Ingredient.substance.strength.referenceStrength.strength[x] | Strength expressed in terms of a reference substance | 1..1 | Quantity, Ratio, RatioRange |  |  |
| `Ingredient.substance.strength.referenceStrength.substance` | `Ingredient.substance.strength.referenceStrength.substance` | `substance` | Ingredient.substance.strength.referenceStrength.substance | Relevant reference substance | 1..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/SubstanceDefinition) | `Example` | `http://hl7.org/fhir/ValueSet/substance-codes` |
| `Ingredient.substance.strength.textConcentration` | `Ingredient.substance.strength.textConcentration` | `textConcentration` | Ingredient.substance.strength.textConcentration | Text of either the whole concentration strength or a part of it (rest being in Strength.concentration as a ratio) | 0..1 | string |  |  |
| `Ingredient.substance.strength.textPresentation` | `Ingredient.substance.strength.textPresentation` | `textPresentation` | Ingredient.substance.strength.textPresentation | Text of either the whole presentation strength or a part of it (rest being in Strength.presentation as a ratio) | 0..1 | string |  |  |
| `Ingredient.text` | `Ingredient.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [Ingredient](/docs/R4B/Resources/Ingredient.md)<br/> `http://hl7.org/fhir/StructureDefinition/Ingredient\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `992`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1221`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Ingredient](/docs/R5/Resources/Ingredient.md)<br/> `http://hl7.org/fhir/StructureDefinition/Ingredient\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Ingredient from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B Ingredient](/docs/R4B/Resources/Ingredient.md)| Relationship | R5 Ingredient
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | `Ingredient`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(43354)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(43355)| **`Ingredient`**
| | | | | | | `Ingredient.id`| _Equivalent_<br/>(43356/43357)| **`Ingredient.id`**
| | | | | | | `Ingredient.meta`| _Equivalent_<br/>(43358/43359)| **`Ingredient.meta`**
| | | | | | | `Ingredient.implicitRules`| _Equivalent_<br/>(43360/43361)| **`Ingredient.implicitRules`**
| | | | | | | `Ingredient.language`| _Equivalent_<br/>(43362/43363)| **`Ingredient.language`**
| | | | | | | `Ingredient.text`| _Equivalent_<br/>(43364/43365)| **`Ingredient.text`**
| | | | | | | `Ingredient.contained`| _Equivalent_<br/>(43366/43367)| **`Ingredient.contained`**
| | | | | | | `Ingredient.extension`| _Equivalent_<br/>(43368/43369)| **`Ingredient.extension`**
| | | | | | | `Ingredient.modifierExtension`| _Equivalent_<br/>(43370/43371)| **`Ingredient.modifierExtension`**
| | | | | | | `Ingredient.identifier`| _Equivalent_<br/>(43372/43373)| **`Ingredient.identifier`**
| | | | | | | `Ingredient.status`| _Equivalent_<br/>(43374/43375)| **`Ingredient.status`**
| | | | | | | `Ingredient.for`| _Equivalent_<br/>(43376/43377)| **`Ingredient.for`**
| | | | | | | `Ingredient.role`| _Equivalent_<br/>(43378/43379)| **`Ingredient.role`**
| | | | | | | `Ingredient.function`| _Equivalent_<br/>(43380/43381)| **`Ingredient.function`**
| | | | | | | | | **`Ingredient.group`**
| | | | | | | `Ingredient.allergenicIndicator`| _Equivalent_<br/>(43382/43383)| **`Ingredient.allergenicIndicator`**
| | | | | | | | | **`Ingredient.comment`**
| | | | | | | `Ingredient.manufacturer`| _Equivalent_<br/>(43384/43385)| **`Ingredient.manufacturer`**
| | | | | | | `Ingredient.manufacturer.id`| _Equivalent_<br/>(43386/43387)| **`Ingredient.manufacturer.id`**
| | | | | | | `Ingredient.manufacturer.extension`| _Equivalent_<br/>(43388/43389)| **`Ingredient.manufacturer.extension`**
| | | | | | | `Ingredient.manufacturer.modifierExtension`| _Equivalent_<br/>(43390/43391)| **`Ingredient.manufacturer.modifierExtension`**
| | | | | | | `Ingredient.manufacturer.role`| _Equivalent_<br/>(43392/43393)| **`Ingredient.manufacturer.role`**
| | | | | | | `Ingredient.manufacturer.manufacturer`| _Equivalent_<br/>(43394/43395)| **`Ingredient.manufacturer.manufacturer`**
| | | | | | | `Ingredient.substance`| _Equivalent_<br/>(43396/43397)| **`Ingredient.substance`**
| | | | | | | `Ingredient.substance.id`| _Equivalent_<br/>(43398/43399)| **`Ingredient.substance.id`**
| | | | | | | `Ingredient.substance.extension`| _Equivalent_<br/>(43400/43401)| **`Ingredient.substance.extension`**
| | | | | | | `Ingredient.substance.modifierExtension`| _Equivalent_<br/>(43402/43403)| **`Ingredient.substance.modifierExtension`**
| | | | | | | `Ingredient.substance.code`| _Equivalent_<br/>(43404/43405)| **`Ingredient.substance.code`**
| | | | | | | `Ingredient.substance.strength`| _Equivalent_<br/>(43406/43407)| **`Ingredient.substance.strength`**
| | | | | | | `Ingredient.substance.strength.id`| _Equivalent_<br/>(43408/43409)| **`Ingredient.substance.strength.id`**
| | | | | | | `Ingredient.substance.strength.extension`| _Equivalent_<br/>(43410/43411)| **`Ingredient.substance.strength.extension`**
| | | | | | | `Ingredient.substance.strength.modifierExtension`| _Equivalent_<br/>(43412/43413)| **`Ingredient.substance.strength.modifierExtension`**
| | | | | | | `Ingredient.substance.strength.presentation[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(43414)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(43415)| **`Ingredient.substance.strength.presentation[x]`**
| | | | | | | `Ingredient.substance.strength.textPresentation`| _Equivalent_<br/>(43416/43417)| **`Ingredient.substance.strength.textPresentation`**
| | | | | | | `Ingredient.substance.strength.concentration[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(43418)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(43419)| **`Ingredient.substance.strength.concentration[x]`**
| | | | | | | `Ingredient.substance.strength.textConcentration`| _Equivalent_<br/>(43420/43421)| **`Ingredient.substance.strength.textConcentration`**
| | | | | | | | | **`Ingredient.substance.strength.basis`**
| | | | | | | `Ingredient.substance.strength.measurementPoint`| _Equivalent_<br/>(43422/43423)| **`Ingredient.substance.strength.measurementPoint`**
| | | | | | | `Ingredient.substance.strength.country`| _Equivalent_<br/>(43424/43425)| **`Ingredient.substance.strength.country`**
| | | | | | | `Ingredient.substance.strength.referenceStrength`| _Equivalent_<br/>(43426/43427)| **`Ingredient.substance.strength.referenceStrength`**
| | | | | | | `Ingredient.substance.strength.referenceStrength.id`| _Equivalent_<br/>(43428/43429)| **`Ingredient.substance.strength.referenceStrength.id`**
| | | | | | | `Ingredient.substance.strength.referenceStrength.extension`| _Equivalent_<br/>(43430/43431)| **`Ingredient.substance.strength.referenceStrength.extension`**
| | | | | | | `Ingredient.substance.strength.referenceStrength.modifierExtension`| _Equivalent_<br/>(43432/43433)| **`Ingredient.substance.strength.referenceStrength.modifierExtension`**
| | | | | | | `Ingredient.substance.strength.referenceStrength.substance`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(43434)<hr/>←←←← _Equivalent_ ←←←← <br/>(43435)| **`Ingredient.substance.strength.referenceStrength.substance`**
| | | | | | | `Ingredient.substance.strength.referenceStrength.strength[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(43436)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(43437)| **`Ingredient.substance.strength.referenceStrength.strength[x]`**
| | | | | | | `Ingredient.substance.strength.referenceStrength.measurementPoint`| _Equivalent_<br/>(43438/43439)| **`Ingredient.substance.strength.referenceStrength.measurementPoint`**
| | | | | | | `Ingredient.substance.strength.referenceStrength.country`| _Equivalent_<br/>(43440/43441)| **`Ingredient.substance.strength.referenceStrength.country`**
| | | | | | | *44 of 44 elements used* | | *47 of 47 elements used* 

