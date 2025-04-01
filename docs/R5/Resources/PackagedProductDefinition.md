Comparison of 
Generated at Tuesday, April 1, 2025 1:39:39 PM

### PackagedProductDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | PackagedProductDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/PackagedProductDefinition` |
| Version | 5.0.0 |
| Description | A medically related item or items, in a container or package. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2357` |
| Database Snapshot Count | `53` |
| Database Differential Count | `33` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `PackagedProductDefinition` | `PackagedProductDefinition` | `PackagedProductDefinition` | PackagedProductDefinition | A medically related item or items, in a container or package | 0..* | PackagedProductDefinition |  |  |
| `PackagedProductDefinition.attachedDocument` | `PackagedProductDefinition.attachedDocument` | `attachedDocument` | PackagedProductDefinition.attachedDocument | Additional information or supporting documentation about the packaged product | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `PackagedProductDefinition.characteristic` | `PackagedProductDefinition.characteristic` | `characteristic` | PackagedProductDefinition.characteristic | Allows the key features to be recorded, such as "hospital pack", "nurse prescribable" | 0..* | PackagedProductDefinition.packaging.property |  |  |
| `PackagedProductDefinition.contained` | `PackagedProductDefinition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `PackagedProductDefinition.containedItemQuantity` | `PackagedProductDefinition.containedItemQuantity` | `containedItemQuantity` | PackagedProductDefinition.containedItemQuantity | A total of the complete count of contained items of a particular type/form, independent of sub-packaging or organization. This can be considered as the pack size. See also packaging.containedItem.amount (especially the long definition) | 0..* | Quantity |  |  |
| `PackagedProductDefinition.copackagedIndicator` | `PackagedProductDefinition.copackagedIndicator` | `copackagedIndicator` | PackagedProductDefinition.copackagedIndicator | Identifies if the drug product is supplied with another item such as a diluent or adjuvant | 0..1 | boolean |  |  |
| `PackagedProductDefinition.description` | `PackagedProductDefinition.description` | `description` | PackagedProductDefinition.description | Textual description. Note that this is not the name of the package or product | 0..1 | markdown |  |  |
| `PackagedProductDefinition.extension` | `PackagedProductDefinition.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `PackagedProductDefinition.id` | `PackagedProductDefinition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `PackagedProductDefinition.identifier` | `PackagedProductDefinition.identifier` | `identifier` | PackagedProductDefinition.identifier | A unique identifier for this package as whole - not for the content of the package | 0..* | Identifier |  |  |
| `PackagedProductDefinition.implicitRules` | `PackagedProductDefinition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `PackagedProductDefinition.language` | `PackagedProductDefinition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `PackagedProductDefinition.legalStatusOfSupply` | `PackagedProductDefinition.legalStatusOfSupply` | `legalStatusOfSupply` | PackagedProductDefinition.legalStatusOfSupply | The legal status of supply of the packaged item as classified by the regulator | 0..* | BackboneElement |  |  |
| `PackagedProductDefinition.legalStatusOfSupply.code` | `PackagedProductDefinition.legalStatusOfSupply.code` | `code` | PackagedProductDefinition.legalStatusOfSupply.code | The actual status of supply. In what situation this package type may be supplied for use | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/legal-status-of-supply` |
| `PackagedProductDefinition.legalStatusOfSupply.extension` | `PackagedProductDefinition.legalStatusOfSupply.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `PackagedProductDefinition.legalStatusOfSupply.id` | `PackagedProductDefinition.legalStatusOfSupply.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `PackagedProductDefinition.legalStatusOfSupply.jurisdiction` | `PackagedProductDefinition.legalStatusOfSupply.jurisdiction` | `jurisdiction` | PackagedProductDefinition.legalStatusOfSupply.jurisdiction | The place where the legal status of supply applies | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `PackagedProductDefinition.legalStatusOfSupply.modifierExtension` | `PackagedProductDefinition.legalStatusOfSupply.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `PackagedProductDefinition.manufacturer` | `PackagedProductDefinition.manufacturer` | `manufacturer` | PackagedProductDefinition.manufacturer | Manufacturer of this package type (multiple means these are all possible manufacturers) | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `PackagedProductDefinition.marketingStatus` | `PackagedProductDefinition.marketingStatus` | `marketingStatus` | PackagedProductDefinition.marketingStatus | Allows specifying that an item is on the market for sale, or that it is not available, and the dates and locations associated | 0..* | MarketingStatus |  |  |
| `PackagedProductDefinition.meta` | `PackagedProductDefinition.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `PackagedProductDefinition.modifierExtension` | `PackagedProductDefinition.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `PackagedProductDefinition.name` | `PackagedProductDefinition.name` | `name` | PackagedProductDefinition.name | A name for this package. Typically as listed in a drug formulary, catalogue, inventory etc | 0..1 | string |  |  |
| `PackagedProductDefinition.packageFor` | `PackagedProductDefinition.packageFor` | `packageFor` | PackagedProductDefinition.packageFor | The product that this is a pack for | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProductDefinition) |  |  |
| `PackagedProductDefinition.packaging` | `PackagedProductDefinition.packaging` | `packaging` | PackagedProductDefinition.packaging | A packaging item, as a container for medically related items, possibly with other packaging items within, or a packaging component, such as bottle cap | 0..1 | BackboneElement |  |  |
| `PackagedProductDefinition.packaging.alternateMaterial` | `PackagedProductDefinition.packaging.alternateMaterial` | `alternateMaterial` | PackagedProductDefinition.packaging.alternateMaterial | A possible alternate material for this part of the packaging, that is allowed to be used instead of the usual material | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/package-material` |
| `PackagedProductDefinition.packaging.componentPart` | `PackagedProductDefinition.packaging.componentPart` | `componentPart` | PackagedProductDefinition.packaging.componentPart | Is this a part of the packaging (e.g. a cap or bottle stopper), rather than the packaging itself (e.g. a bottle or vial) | 0..1 | boolean |  |  |
| `PackagedProductDefinition.packaging.containedItem` | `PackagedProductDefinition.packaging.containedItem` | `containedItem` | PackagedProductDefinition.packaging.containedItem | The item(s) within the packaging | 0..* | BackboneElement |  |  |
| `PackagedProductDefinition.packaging.containedItem.amount` | `PackagedProductDefinition.packaging.containedItem.amount` | `amount` | PackagedProductDefinition.packaging.containedItem.amount | The number of this type of item within this packaging or for continuous items such as liquids it is the quantity (for example 25ml). See also PackagedProductDefinition.containedItemQuantity (especially the long definition) | 0..1 | Quantity |  |  |
| `PackagedProductDefinition.packaging.containedItem.extension` | `PackagedProductDefinition.packaging.containedItem.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `PackagedProductDefinition.packaging.containedItem.id` | `PackagedProductDefinition.packaging.containedItem.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `PackagedProductDefinition.packaging.containedItem.item` | `PackagedProductDefinition.packaging.containedItem.item` | `item` | PackagedProductDefinition.packaging.containedItem.item | The actual item(s) of medication, as manufactured, or a device, or other medically related item (food, biologicals, raw materials, medical fluids, gases etc.), as contained in the package | 1..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct), CodeableReference(http://hl7.org/fhir/StructureDefinition/DeviceDefinition), CodeableReference(http://hl7.org/fhir/StructureDefinition/ManufacturedItemDefinition), CodeableReference(http://hl7.org/fhir/StructureDefinition/NutritionProduct), CodeableReference(http://hl7.org/fhir/StructureDefinition/PackagedProductDefinition) |  |  |
| `PackagedProductDefinition.packaging.containedItem.modifierExtension` | `PackagedProductDefinition.packaging.containedItem.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `PackagedProductDefinition.packaging.extension` | `PackagedProductDefinition.packaging.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `PackagedProductDefinition.packaging.id` | `PackagedProductDefinition.packaging.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `PackagedProductDefinition.packaging.identifier` | `PackagedProductDefinition.packaging.identifier` | `identifier` | PackagedProductDefinition.packaging.identifier | An identifier that is specific to this particular part of the packaging. Including possibly a Data Carrier Identifier | 0..* | Identifier |  |  |
| `PackagedProductDefinition.packaging.manufacturer` | `PackagedProductDefinition.packaging.manufacturer` | `manufacturer` | PackagedProductDefinition.packaging.manufacturer | Manufacturer of this packaging item (multiple means these are all potential manufacturers) | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `PackagedProductDefinition.packaging.material` | `PackagedProductDefinition.packaging.material` | `material` | PackagedProductDefinition.packaging.material | Material type of the package item | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/package-material` |
| `PackagedProductDefinition.packaging.modifierExtension` | `PackagedProductDefinition.packaging.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `PackagedProductDefinition.packaging.packaging` | `PackagedProductDefinition.packaging.packaging` | `packaging` | PackagedProductDefinition.packaging.packaging | Allows containers (and parts of containers) within containers, still as a part of single packaged product | 0..* | PackagedProductDefinition.packaging |  |  |
| `PackagedProductDefinition.packaging.property` | `PackagedProductDefinition.packaging.property` | `property` | PackagedProductDefinition.packaging.property | General characteristics of this item | 0..* | BackboneElement |  |  |
| `PackagedProductDefinition.packaging.property.extension` | `PackagedProductDefinition.packaging.property.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `PackagedProductDefinition.packaging.property.id` | `PackagedProductDefinition.packaging.property.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `PackagedProductDefinition.packaging.property.modifierExtension` | `PackagedProductDefinition.packaging.property.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `PackagedProductDefinition.packaging.property.type` | `PackagedProductDefinition.packaging.property.type` | `type` | PackagedProductDefinition.packaging.property.type | A code expressing the type of characteristic | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/product-characteristic-codes` |
| `PackagedProductDefinition.packaging.property.value[x]` | `PackagedProductDefinition.packaging.property.value[x]` | `value[x]` | PackagedProductDefinition.packaging.property.value[x] | A value for the characteristic | 0..1 | Attachment, boolean, CodeableConcept, date, Quantity |  |  |
| `PackagedProductDefinition.packaging.quantity` | `PackagedProductDefinition.packaging.quantity` | `quantity` | PackagedProductDefinition.packaging.quantity | The quantity of this level of packaging in the package that contains it (with the outermost level being 1) | 0..1 | integer |  |  |
| `PackagedProductDefinition.packaging.shelfLifeStorage` | `PackagedProductDefinition.packaging.shelfLifeStorage` | `shelfLifeStorage` | PackagedProductDefinition.packaging.shelfLifeStorage | Shelf Life and storage information | 0..* | ProductShelfLife |  |  |
| `PackagedProductDefinition.packaging.type` | `PackagedProductDefinition.packaging.type` | `type` | PackagedProductDefinition.packaging.type | The physical type of the container of the items | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/packaging-type` |
| `PackagedProductDefinition.status` | `PackagedProductDefinition.status` | `status` | PackagedProductDefinition.status | The status within the lifecycle of this item. High level - not intended to duplicate details elsewhere e.g. legal status, or authorization/marketing status | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/publication-status` |
| `PackagedProductDefinition.statusDate` | `PackagedProductDefinition.statusDate` | `statusDate` | PackagedProductDefinition.statusDate | The date at which the given status became applicable | 0..1 | dateTime |  |  |
| `PackagedProductDefinition.text` | `PackagedProductDefinition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `PackagedProductDefinition.type` | `PackagedProductDefinition.type` | `type` | PackagedProductDefinition.type | A high level category e.g. medicinal product, raw material, shipping container etc | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/package-type` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [PackagedProductDefinition](/docs/R4B/Resources/PackagedProductDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/PackagedProductDefinition\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1020`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1249`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [PackagedProductDefinition](/docs/R5/Resources/PackagedProductDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/PackagedProductDefinition\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition PackagedProductDefinition from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B PackagedProductDefinition](/docs/R4B/Resources/PackagedProductDefinition.md)| Relationship | R5 PackagedProductDefinition
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | `PackagedProductDefinition`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(45846)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(45847)| **`PackagedProductDefinition`**
| | | | | | | `PackagedProductDefinition.id`| _Equivalent_<br/>(45848/45849)| **`PackagedProductDefinition.id`**
| | | | | | | `PackagedProductDefinition.meta`| _Equivalent_<br/>(45850/45851)| **`PackagedProductDefinition.meta`**
| | | | | | | `PackagedProductDefinition.implicitRules`| _Equivalent_<br/>(45852/45853)| **`PackagedProductDefinition.implicitRules`**
| | | | | | | `PackagedProductDefinition.language`| _Equivalent_<br/>(45854/45855)| **`PackagedProductDefinition.language`**
| | | | | | | `PackagedProductDefinition.text`| _Equivalent_<br/>(45856/45857)| **`PackagedProductDefinition.text`**
| | | | | | | `PackagedProductDefinition.contained`| _Equivalent_<br/>(45858/45859)| **`PackagedProductDefinition.contained`**
| | | | | | | `PackagedProductDefinition.extension`| _Equivalent_<br/>(45860/45861)| **`PackagedProductDefinition.extension`**
| | | | | | | `PackagedProductDefinition.modifierExtension`| _Equivalent_<br/>(45862/45863)| **`PackagedProductDefinition.modifierExtension`**
| | | | | | | `PackagedProductDefinition.identifier`| _Equivalent_<br/>(45864/45865)| **`PackagedProductDefinition.identifier`**
| | | | | | | `PackagedProductDefinition.name`| _Equivalent_<br/>(45866/45867)| **`PackagedProductDefinition.name`**
| | | | | | | `PackagedProductDefinition.type`| _Equivalent_<br/>(45868/45869)| **`PackagedProductDefinition.type`**
| | | | | | | `PackagedProductDefinition.packageFor`| _Equivalent_<br/>(45870/45871)| **`PackagedProductDefinition.packageFor`**
| | | | | | | `PackagedProductDefinition.status`| _Equivalent_<br/>(45872/45873)| **`PackagedProductDefinition.status`**
| | | | | | | `PackagedProductDefinition.statusDate`| _Equivalent_<br/>(45874/45875)| **`PackagedProductDefinition.statusDate`**
| | | | | | | `PackagedProductDefinition.containedItemQuantity`| _Equivalent_<br/>(45876/45877)| **`PackagedProductDefinition.containedItemQuantity`**
| | | | | | | `PackagedProductDefinition.description`| _Equivalent_<br/>(45878/45879)| **`PackagedProductDefinition.description`**
| | | | | | | `PackagedProductDefinition.legalStatusOfSupply`| _Equivalent_<br/>(45880/45881)| **`PackagedProductDefinition.legalStatusOfSupply`**
| | | | | | | `PackagedProductDefinition.legalStatusOfSupply.id`| _Equivalent_<br/>(45882/45883)| **`PackagedProductDefinition.legalStatusOfSupply.id`**
| | | | | | | `PackagedProductDefinition.legalStatusOfSupply.extension`| _Equivalent_<br/>(45884/45885)| **`PackagedProductDefinition.legalStatusOfSupply.extension`**
| | | | | | | `PackagedProductDefinition.legalStatusOfSupply.modifierExtension`| _Equivalent_<br/>(45886/45887)| **`PackagedProductDefinition.legalStatusOfSupply.modifierExtension`**
| | | | | | | `PackagedProductDefinition.legalStatusOfSupply.code`| _Equivalent_<br/>(45888/45889)| **`PackagedProductDefinition.legalStatusOfSupply.code`**
| | | | | | | `PackagedProductDefinition.legalStatusOfSupply.jurisdiction`| _Equivalent_<br/>(45890/45891)| **`PackagedProductDefinition.legalStatusOfSupply.jurisdiction`**
| | | | | | | `PackagedProductDefinition.marketingStatus`| _Equivalent_<br/>(45892/45893)| **`PackagedProductDefinition.marketingStatus`**
| | | | | | | `PackagedProductDefinition.copackagedIndicator`| _Equivalent_<br/>(45896/45897)| **`PackagedProductDefinition.copackagedIndicator`**
| | | | | | | `PackagedProductDefinition.manufacturer`| _Equivalent_<br/>(45898/45899)| **`PackagedProductDefinition.manufacturer`**
| | | | | | | | | **`PackagedProductDefinition.attachedDocument`**
| | | | | | | | | **`PackagedProductDefinition.packaging`**
| | | | | | | | | **`PackagedProductDefinition.packaging.id`**
| | | | | | | | | **`PackagedProductDefinition.packaging.extension`**
| | | | | | | | | **`PackagedProductDefinition.packaging.modifierExtension`**
| | | | | | | `PackagedProductDefinition.package.identifier`| _Equivalent_<br/>(1907/2145)| **`PackagedProductDefinition.packaging.identifier`**
| | | | | | | `PackagedProductDefinition.package.type`| _Equivalent_<br/>(1908/2146)| **`PackagedProductDefinition.packaging.type`**
| | | | | | | | | **`PackagedProductDefinition.packaging.componentPart`**
| | | | | | | `PackagedProductDefinition.package.quantity`| _Equivalent_<br/>(1909/2147)| **`PackagedProductDefinition.packaging.quantity`**
| | | | | | | `PackagedProductDefinition.package.material`| _Equivalent_<br/>(1910/2148)| **`PackagedProductDefinition.packaging.material`**
| | | | | | | `PackagedProductDefinition.package.alternateMaterial`| _Equivalent_<br/>(1911/2149)| **`PackagedProductDefinition.packaging.alternateMaterial`**
| | | | | | | | | **`PackagedProductDefinition.packaging.shelfLifeStorage`**
| | | | | | | `PackagedProductDefinition.package.manufacturer`| _Equivalent_<br/>(1912/2150)| **`PackagedProductDefinition.packaging.manufacturer`**
| | | | | | | | | **`PackagedProductDefinition.packaging.property`**
| | | | | | | | | **`PackagedProductDefinition.packaging.property.id`**
| | | | | | | | | **`PackagedProductDefinition.packaging.property.extension`**
| | | | | | | | | **`PackagedProductDefinition.packaging.property.modifierExtension`**
| | | | | | | `PackagedProductDefinition.package.property.type`| _Equivalent_<br/>(1913/2151)| **`PackagedProductDefinition.packaging.property.type`**
| | | | | | | `PackagedProductDefinition.package.property.value[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1914)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2152)| **`PackagedProductDefinition.packaging.property.value[x]`**
| | | | | | | | | **`PackagedProductDefinition.packaging.containedItem`**
| | | | | | | | | **`PackagedProductDefinition.packaging.containedItem.id`**
| | | | | | | | | **`PackagedProductDefinition.packaging.containedItem.extension`**
| | | | | | | | | **`PackagedProductDefinition.packaging.containedItem.modifierExtension`**
| | | | | | | `PackagedProductDefinition.package.containedItem.item`| _Equivalent_<br/>(1915/2153)| **`PackagedProductDefinition.packaging.containedItem.item`**
| | | | | | | `PackagedProductDefinition.package.containedItem.amount`| _Equivalent_<br/>(1916/2154)| **`PackagedProductDefinition.packaging.containedItem.amount`**
| | | | | | | | | **`PackagedProductDefinition.packaging.packaging`**
| | | | | | | `PackagedProductDefinition.characteristic`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(45894)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(45895)| **`PackagedProductDefinition.characteristic`**
| | | | | | | *37 of 57 elements used* | | *53 of 53 elements used* 

