Comparison of 
Generated at Tuesday, April 1, 2025 1:39:28 PM

### ManufacturedItemDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | ManufacturedItemDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ManufacturedItemDefinition` |
| Version | 4.3.0 |
| Description | The definition and characteristics of a medicinal manufactured item, such as a tablet or capsule, as contained in a packaged medicinal product. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1714` |
| Database Snapshot Count | `21` |
| Database Differential Count | `10` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ManufacturedItemDefinition` | `ManufacturedItemDefinition` | `ManufacturedItemDefinition` | ManufacturedItemDefinition | The definition and characteristics of a medicinal manufactured item, such as a tablet or capsule, as contained in a packaged medicinal product | 0..* | ManufacturedItemDefinition |  |  |
| `ManufacturedItemDefinition.contained` | `ManufacturedItemDefinition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ManufacturedItemDefinition.extension` | `ManufacturedItemDefinition.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ManufacturedItemDefinition.id` | `ManufacturedItemDefinition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ManufacturedItemDefinition.identifier` | `ManufacturedItemDefinition.identifier` | `identifier` | ManufacturedItemDefinition.identifier | Unique identifier | 0..* | Identifier |  |  |
| `ManufacturedItemDefinition.implicitRules` | `ManufacturedItemDefinition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ManufacturedItemDefinition.ingredient` | `ManufacturedItemDefinition.ingredient` | `ingredient` | ManufacturedItemDefinition.ingredient | The ingredients of this manufactured item. Only needed if these are not specified by incoming references from the Ingredient resource | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/substance-codes` |
| `ManufacturedItemDefinition.language` | `ManufacturedItemDefinition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `ManufacturedItemDefinition.manufacturedDoseForm` | `ManufacturedItemDefinition.manufacturedDoseForm` | `manufacturedDoseForm` | ManufacturedItemDefinition.manufacturedDoseForm | Dose form as manufactured (before any necessary transformation) | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/manufactured-dose-form` |
| `ManufacturedItemDefinition.manufacturer` | `ManufacturedItemDefinition.manufacturer` | `manufacturer` | ManufacturedItemDefinition.manufacturer | Manufacturer of the item (Note that this should be named "manufacturer" but it currently causes technical issues) | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `ManufacturedItemDefinition.meta` | `ManufacturedItemDefinition.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ManufacturedItemDefinition.modifierExtension` | `ManufacturedItemDefinition.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ManufacturedItemDefinition.property` | `ManufacturedItemDefinition.property` | `property` | ManufacturedItemDefinition.property | General characteristics of this item | 0..* | BackboneElement |  |  |
| `ManufacturedItemDefinition.property.extension` | `ManufacturedItemDefinition.property.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ManufacturedItemDefinition.property.id` | `ManufacturedItemDefinition.property.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ManufacturedItemDefinition.property.modifierExtension` | `ManufacturedItemDefinition.property.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ManufacturedItemDefinition.property.type` | `ManufacturedItemDefinition.property.type` | `type` | ManufacturedItemDefinition.property.type | A code expressing the type of characteristic | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/product-characteristic-codes` |
| `ManufacturedItemDefinition.property.value[x]` | `ManufacturedItemDefinition.property.value[x]` | `value[x]` | ManufacturedItemDefinition.property.value[x] | A value for the characteristic | 0..1 | Attachment, boolean, CodeableConcept, date, Quantity |  |  |
| `ManufacturedItemDefinition.status` | `ManufacturedItemDefinition.status` | `status` | ManufacturedItemDefinition.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|4.3.0` |
| `ManufacturedItemDefinition.text` | `ManufacturedItemDefinition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `ManufacturedItemDefinition.unitOfPresentation` | `ManufacturedItemDefinition.unitOfPresentation` | `unitOfPresentation` | ManufacturedItemDefinition.unitOfPresentation | The “real world” units in which the quantity of the item is described | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/unit-of-presentation` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [ManufacturedItemDefinition](/docs/R4B/Resources/ManufacturedItemDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ManufacturedItemDefinition\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `999`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1228`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ManufacturedItemDefinition](/docs/R5/Resources/ManufacturedItemDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ManufacturedItemDefinition\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ManufacturedItemDefinition from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | R4B ManufacturedItemDefinition| Relationship | [R5 ManufacturedItemDefinition](/docs/R5/Resources/ManufacturedItemDefinition.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | **`ManufacturedItemDefinition`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(43913)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(43914)| `ManufacturedItemDefinition`
| | | | | | | **`ManufacturedItemDefinition.id`**| _Equivalent_<br/>(43915/43916)| `ManufacturedItemDefinition.id`
| | | | | | | **`ManufacturedItemDefinition.meta`**| _Equivalent_<br/>(43917/43918)| `ManufacturedItemDefinition.meta`
| | | | | | | **`ManufacturedItemDefinition.implicitRules`**| _Equivalent_<br/>(43919/43920)| `ManufacturedItemDefinition.implicitRules`
| | | | | | | **`ManufacturedItemDefinition.language`**| _Equivalent_<br/>(43921/43922)| `ManufacturedItemDefinition.language`
| | | | | | | **`ManufacturedItemDefinition.text`**| _Equivalent_<br/>(43923/43924)| `ManufacturedItemDefinition.text`
| | | | | | | **`ManufacturedItemDefinition.contained`**| _Equivalent_<br/>(43925/43926)| `ManufacturedItemDefinition.contained`
| | | | | | | **`ManufacturedItemDefinition.extension`**| _Equivalent_<br/>(43927/43928)| `ManufacturedItemDefinition.extension`
| | | | | | | **`ManufacturedItemDefinition.modifierExtension`**| _Equivalent_<br/>(43929/43930)| `ManufacturedItemDefinition.modifierExtension`
| | | | | | | **`ManufacturedItemDefinition.identifier`**| _Equivalent_<br/>(43931/43932)| `ManufacturedItemDefinition.identifier`
| | | | | | | **`ManufacturedItemDefinition.status`**| _Equivalent_<br/>(43933/43934)| `ManufacturedItemDefinition.status`
| | | | | | | **`ManufacturedItemDefinition.manufacturedDoseForm`**| _Equivalent_<br/>(43935/43936)| `ManufacturedItemDefinition.manufacturedDoseForm`
| | | | | | | **`ManufacturedItemDefinition.unitOfPresentation`**| _Equivalent_<br/>(43937/43938)| `ManufacturedItemDefinition.unitOfPresentation`
| | | | | | | **`ManufacturedItemDefinition.manufacturer`**| _Equivalent_<br/>(43939/43940)| `ManufacturedItemDefinition.manufacturer`
| | | | | | | **`ManufacturedItemDefinition.ingredient`**| _Equivalent_<br/>(43941/43942)| `ManufacturedItemDefinition.ingredient`
| | | | | | | **`ManufacturedItemDefinition.property`**| _Equivalent_<br/>(43943/43944)| `ManufacturedItemDefinition.property`
| | | | | | | **`ManufacturedItemDefinition.property.id`**| _Equivalent_<br/>(43945/43946)| `ManufacturedItemDefinition.property.id`
| | | | | | | **`ManufacturedItemDefinition.property.extension`**| _Equivalent_<br/>(43947/43948)| `ManufacturedItemDefinition.property.extension`
| | | | | | | **`ManufacturedItemDefinition.property.modifierExtension`**| _Equivalent_<br/>(43949/43950)| `ManufacturedItemDefinition.property.modifierExtension`
| | | | | | | **`ManufacturedItemDefinition.property.type`**| _Equivalent_<br/>(43951/43952)| `ManufacturedItemDefinition.property.type`
| | | | | | | **`ManufacturedItemDefinition.property.value[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(43953)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(43954)| `ManufacturedItemDefinition.property.value[x]`
| | | | | | | *21 of 21 elements used* | | *21 of 40 elements used* 

