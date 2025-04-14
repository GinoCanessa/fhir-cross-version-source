Comparison of 
Generated at Monday, April 14, 2025 6:17:38 PM

### PackagedProductDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | PackagedProductDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/PackagedProductDefinition` |
| Version | 4.3.0 |
| Description | A medically related item or items, in a container or package. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1737` |
| Database Snapshot Count | `57` |
| Database Differential Count | `34` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `PackagedProductDefinition` | `PackagedProductDefinition` | `PackagedProductDefinition` | PackagedProductDefinition | A medically related item or items, in a container or package | 0..* | PackagedProductDefinition |  |  |
| `PackagedProductDefinition.characteristic` | `PackagedProductDefinition.characteristic` | `characteristic` | PackagedProductDefinition.characteristic | Allows the key features to be recorded, such as "hospital pack", "nurse prescribable" | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/package-characteristic` |
| `PackagedProductDefinition.contained` | `PackagedProductDefinition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `PackagedProductDefinition.containedItemQuantity` | `PackagedProductDefinition.containedItemQuantity` | `containedItemQuantity` | PackagedProductDefinition.containedItemQuantity | A total of the complete count of contained items of a particular type/form, independent of sub-packaging or organization. This can be considered as the pack size | 0..* | Quantity |  |  |
| `PackagedProductDefinition.copackagedIndicator` | `PackagedProductDefinition.copackagedIndicator` | `copackagedIndicator` | PackagedProductDefinition.copackagedIndicator | If the drug product is supplied with another item such as a diluent or adjuvant | 0..1 | boolean |  |  |
| `PackagedProductDefinition.description` | `PackagedProductDefinition.description` | `description` | PackagedProductDefinition.description | Textual description. Note that this is not the name of the package or product | 0..1 | markdown |  |  |
| `PackagedProductDefinition.extension` | `PackagedProductDefinition.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `PackagedProductDefinition.id` | `PackagedProductDefinition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `PackagedProductDefinition.identifier` | `PackagedProductDefinition.identifier` | `identifier` | PackagedProductDefinition.identifier | A unique identifier for this package as whole | 0..* | Identifier |  |  |
| `PackagedProductDefinition.implicitRules` | `PackagedProductDefinition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `PackagedProductDefinition.language` | `PackagedProductDefinition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
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
| `PackagedProductDefinition.package` | `PackagedProductDefinition.package` | `package` | PackagedProductDefinition.package | A packaging item, as a container for medically related items, possibly with other packaging items within, or a packaging component, such as bottle cap | 0..1 | BackboneElement |  |  |
| `PackagedProductDefinition.package.alternateMaterial` | `PackagedProductDefinition.package.alternateMaterial` | `alternateMaterial` | PackagedProductDefinition.package.alternateMaterial | A possible alternate material for this part of the packaging, that is allowed to be used instead of the usual material | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/package-material` |
| `PackagedProductDefinition.package.containedItem` | `PackagedProductDefinition.package.containedItem` | `containedItem` | PackagedProductDefinition.package.containedItem | The item(s) within the packaging | 0..* | BackboneElement |  |  |
| `PackagedProductDefinition.package.containedItem.amount` | `PackagedProductDefinition.package.containedItem.amount` | `amount` | PackagedProductDefinition.package.containedItem.amount | The number of this type of item within this packaging | 0..1 | Quantity |  |  |
| `PackagedProductDefinition.package.containedItem.extension` | `PackagedProductDefinition.package.containedItem.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `PackagedProductDefinition.package.containedItem.id` | `PackagedProductDefinition.package.containedItem.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `PackagedProductDefinition.package.containedItem.item` | `PackagedProductDefinition.package.containedItem.item` | `item` | PackagedProductDefinition.package.containedItem.item | The actual item(s) of medication, as manufactured, or a device, or other medically related item (food, biologicals, raw materials, medical fluids, gases etc.), as contained in the package | 1..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct), CodeableReference(http://hl7.org/fhir/StructureDefinition/DeviceDefinition), CodeableReference(http://hl7.org/fhir/StructureDefinition/ManufacturedItemDefinition), CodeableReference(http://hl7.org/fhir/StructureDefinition/NutritionProduct), CodeableReference(http://hl7.org/fhir/StructureDefinition/PackagedProductDefinition) |  |  |
| `PackagedProductDefinition.package.containedItem.modifierExtension` | `PackagedProductDefinition.package.containedItem.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `PackagedProductDefinition.package.extension` | `PackagedProductDefinition.package.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `PackagedProductDefinition.package.id` | `PackagedProductDefinition.package.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `PackagedProductDefinition.package.identifier` | `PackagedProductDefinition.package.identifier` | `identifier` | PackagedProductDefinition.package.identifier | An identifier that is specific to this particular part of the packaging. Including possibly a Data Carrier Identifier | 0..* | Identifier |  |  |
| `PackagedProductDefinition.package.manufacturer` | `PackagedProductDefinition.package.manufacturer` | `manufacturer` | PackagedProductDefinition.package.manufacturer | Manufacturer of this package Item (multiple means these are all possible manufacturers) | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `PackagedProductDefinition.package.material` | `PackagedProductDefinition.package.material` | `material` | PackagedProductDefinition.package.material | Material type of the package item | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/package-material` |
| `PackagedProductDefinition.package.modifierExtension` | `PackagedProductDefinition.package.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `PackagedProductDefinition.package.package` | `PackagedProductDefinition.package.package` | `package` | PackagedProductDefinition.package.package | Allows containers (and parts of containers) within containers, still a single packaged product | 0..* | PackagedProductDefinition.package |  |  |
| `PackagedProductDefinition.package.property` | `PackagedProductDefinition.package.property` | `property` | PackagedProductDefinition.package.property | General characteristics of this item | 0..* | BackboneElement |  |  |
| `PackagedProductDefinition.package.property.extension` | `PackagedProductDefinition.package.property.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `PackagedProductDefinition.package.property.id` | `PackagedProductDefinition.package.property.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `PackagedProductDefinition.package.property.modifierExtension` | `PackagedProductDefinition.package.property.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `PackagedProductDefinition.package.property.type` | `PackagedProductDefinition.package.property.type` | `type` | PackagedProductDefinition.package.property.type | A code expressing the type of characteristic | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/product-characteristic-codes` |
| `PackagedProductDefinition.package.property.value[x]` | `PackagedProductDefinition.package.property.value[x]` | `value[x]` | PackagedProductDefinition.package.property.value[x] | A value for the characteristic | 0..1 | Attachment, boolean, CodeableConcept, date, Quantity |  |  |
| `PackagedProductDefinition.package.quantity` | `PackagedProductDefinition.package.quantity` | `quantity` | PackagedProductDefinition.package.quantity | The quantity of this level of packaging in the package that contains it (with the outermost level being 1) | 0..1 | integer |  |  |
| `PackagedProductDefinition.package.shelfLifeStorage` | `PackagedProductDefinition.package.shelfLifeStorage` | `shelfLifeStorage` | PackagedProductDefinition.package.shelfLifeStorage | Shelf Life and storage information | 0..* | BackboneElement |  |  |
| `PackagedProductDefinition.package.shelfLifeStorage.extension` | `PackagedProductDefinition.package.shelfLifeStorage.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `PackagedProductDefinition.package.shelfLifeStorage.id` | `PackagedProductDefinition.package.shelfLifeStorage.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `PackagedProductDefinition.package.shelfLifeStorage.modifierExtension` | `PackagedProductDefinition.package.shelfLifeStorage.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `PackagedProductDefinition.package.shelfLifeStorage.period[x]` | `PackagedProductDefinition.package.shelfLifeStorage.period[x]` | `period[x]` | PackagedProductDefinition.package.shelfLifeStorage.period[x] | The shelf life time period can be specified using a numerical value for the period of time and its unit of time measurement The unit of measurement shall be specified in accordance with ISO 11240 and the resulting terminology The symbol and the symbol identifier shall be used | 0..1 | Duration, string |  |  |
| `PackagedProductDefinition.package.shelfLifeStorage.specialPrecautionsForStorage` | `PackagedProductDefinition.package.shelfLifeStorage.specialPrecautionsForStorage` | `specialPrecautionsForStorage` | PackagedProductDefinition.package.shelfLifeStorage.specialPrecautionsForStorage | Special precautions for storage, if any, can be specified using an appropriate controlled vocabulary. The controlled term and the controlled term identifier shall be specified | 0..* | CodeableConcept |  |  |
| `PackagedProductDefinition.package.shelfLifeStorage.type` | `PackagedProductDefinition.package.shelfLifeStorage.type` | `type` | PackagedProductDefinition.package.shelfLifeStorage.type | This describes the shelf life, taking into account various scenarios such as shelf life of the packaged Medicinal Product itself, shelf life after transformation where necessary and shelf life after the first opening of a bottle, etc. The shelf life type shall be specified using an appropriate controlled vocabulary The controlled term and the controlled term identifier shall be specified | 0..1 | CodeableConcept |  |  |
| `PackagedProductDefinition.package.type` | `PackagedProductDefinition.package.type` | `type` | PackagedProductDefinition.package.type | The physical type of the container of the items | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/packaging-type` |
| `PackagedProductDefinition.packageFor` | `PackagedProductDefinition.packageFor` | `packageFor` | PackagedProductDefinition.packageFor | The product that this is a pack for | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProductDefinition) |  |  |
| `PackagedProductDefinition.status` | `PackagedProductDefinition.status` | `status` | PackagedProductDefinition.status | The status within the lifecycle of this item. High level - not intended to duplicate details elsewhere e.g. legal status, or authorization/marketing status | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/publication-status` |
| `PackagedProductDefinition.statusDate` | `PackagedProductDefinition.statusDate` | `statusDate` | PackagedProductDefinition.statusDate | The date at which the given status became applicable | 0..1 | dateTime |  |  |
| `PackagedProductDefinition.text` | `PackagedProductDefinition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `PackagedProductDefinition.type` | `PackagedProductDefinition.type` | `type` | PackagedProductDefinition.type | A high level category e.g. medicinal product, raw material, shipping container etc | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/package-type` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [PackagedProductDefinition](/docs/R4B/Resources/PackagedProductDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/PackagedProductDefinition\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1020`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1249`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [PackagedProductDefinition](/docs/R5/Resources/PackagedProductDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/PackagedProductDefinition\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition PackagedProductDefinition from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | R4B PackagedProductDefinition| Relationship | [R5 PackagedProductDefinition](/docs/R5/Resources/PackagedProductDefinition.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | **`PackagedProductDefinition`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(45846)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(45847)| `PackagedProductDefinition`
| | | | | | | **`PackagedProductDefinition.id`**| _Equivalent_<br/>(45848/45849)| `PackagedProductDefinition.id`
| | | | | | | **`PackagedProductDefinition.meta`**| _Equivalent_<br/>(45850/45851)| `PackagedProductDefinition.meta`
| | | | | | | **`PackagedProductDefinition.implicitRules`**| _Equivalent_<br/>(45852/45853)| `PackagedProductDefinition.implicitRules`
| | | | | | | **`PackagedProductDefinition.language`**| _Equivalent_<br/>(45854/45855)| `PackagedProductDefinition.language`
| | | | | | | **`PackagedProductDefinition.text`**| _Equivalent_<br/>(45856/45857)| `PackagedProductDefinition.text`
| | | | | | | **`PackagedProductDefinition.contained`**| _Equivalent_<br/>(45858/45859)| `PackagedProductDefinition.contained`
| | | | | | | **`PackagedProductDefinition.extension`**| _Equivalent_<br/>(45860/45861)| `PackagedProductDefinition.extension`
| | | | | | | **`PackagedProductDefinition.modifierExtension`**| _Equivalent_<br/>(45862/45863)| `PackagedProductDefinition.modifierExtension`
| | | | | | | **`PackagedProductDefinition.identifier`**| _Equivalent_<br/>(45864/45865)| `PackagedProductDefinition.identifier`
| | | | | | | **`PackagedProductDefinition.name`**| _Equivalent_<br/>(45866/45867)| `PackagedProductDefinition.name`
| | | | | | | **`PackagedProductDefinition.type`**| _Equivalent_<br/>(45868/45869)| `PackagedProductDefinition.type`
| | | | | | | **`PackagedProductDefinition.packageFor`**| _Equivalent_<br/>(45870/45871)| `PackagedProductDefinition.packageFor`
| | | | | | | **`PackagedProductDefinition.status`**| _Equivalent_<br/>(45872/45873)| `PackagedProductDefinition.status`
| | | | | | | **`PackagedProductDefinition.statusDate`**| _Equivalent_<br/>(45874/45875)| `PackagedProductDefinition.statusDate`
| | | | | | | **`PackagedProductDefinition.containedItemQuantity`**| _Equivalent_<br/>(45876/45877)| `PackagedProductDefinition.containedItemQuantity`
| | | | | | | **`PackagedProductDefinition.description`**| _Equivalent_<br/>(45878/45879)| `PackagedProductDefinition.description`
| | | | | | | **`PackagedProductDefinition.legalStatusOfSupply`**| _Equivalent_<br/>(45880/45881)| `PackagedProductDefinition.legalStatusOfSupply`
| | | | | | | **`PackagedProductDefinition.legalStatusOfSupply.id`**| _Equivalent_<br/>(45882/45883)| `PackagedProductDefinition.legalStatusOfSupply.id`
| | | | | | | **`PackagedProductDefinition.legalStatusOfSupply.extension`**| _Equivalent_<br/>(45884/45885)| `PackagedProductDefinition.legalStatusOfSupply.extension`
| | | | | | | **`PackagedProductDefinition.legalStatusOfSupply.modifierExtension`**| _Equivalent_<br/>(45886/45887)| `PackagedProductDefinition.legalStatusOfSupply.modifierExtension`
| | | | | | | **`PackagedProductDefinition.legalStatusOfSupply.code`**| _Equivalent_<br/>(45888/45889)| `PackagedProductDefinition.legalStatusOfSupply.code`
| | | | | | | **`PackagedProductDefinition.legalStatusOfSupply.jurisdiction`**| _Equivalent_<br/>(45890/45891)| `PackagedProductDefinition.legalStatusOfSupply.jurisdiction`
| | | | | | | **`PackagedProductDefinition.marketingStatus`**| _Equivalent_<br/>(45892/45893)| `PackagedProductDefinition.marketingStatus`
| | | | | | | **`PackagedProductDefinition.characteristic`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(45894)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(45895)| `PackagedProductDefinition.characteristic`
| | | | | | | **`PackagedProductDefinition.copackagedIndicator`**| _Equivalent_<br/>(45896/45897)| `PackagedProductDefinition.copackagedIndicator`
| | | | | | | **`PackagedProductDefinition.manufacturer`**| _Equivalent_<br/>(45898/45899)| `PackagedProductDefinition.manufacturer`
| | | | | | | **`PackagedProductDefinition.package`**| | | 
| | | | | | | **`PackagedProductDefinition.package.id`**| | | 
| | | | | | | **`PackagedProductDefinition.package.extension`**| | | 
| | | | | | | **`PackagedProductDefinition.package.modifierExtension`**| | | 
| | | | | | | **`PackagedProductDefinition.package.identifier`**| _Equivalent_<br/>(1907/2145)| `PackagedProductDefinition.packaging.identifier`
| | | | | | | **`PackagedProductDefinition.package.type`**| _Equivalent_<br/>(1908/2146)| `PackagedProductDefinition.packaging.type`
| | | | | | | **`PackagedProductDefinition.package.quantity`**| _Equivalent_<br/>(1909/2147)| `PackagedProductDefinition.packaging.quantity`
| | | | | | | **`PackagedProductDefinition.package.material`**| _Equivalent_<br/>(1910/2148)| `PackagedProductDefinition.packaging.material`
| | | | | | | **`PackagedProductDefinition.package.alternateMaterial`**| _Equivalent_<br/>(1911/2149)| `PackagedProductDefinition.packaging.alternateMaterial`
| | | | | | | **`PackagedProductDefinition.package.shelfLifeStorage`**| | | 
| | | | | | | **`PackagedProductDefinition.package.shelfLifeStorage.id`**| | | 
| | | | | | | **`PackagedProductDefinition.package.shelfLifeStorage.extension`**| | | 
| | | | | | | **`PackagedProductDefinition.package.shelfLifeStorage.modifierExtension`**| | | 
| | | | | | | **`PackagedProductDefinition.package.shelfLifeStorage.type`**| | | 
| | | | | | | **`PackagedProductDefinition.package.shelfLifeStorage.period[x]`**| | | 
| | | | | | | **`PackagedProductDefinition.package.shelfLifeStorage.specialPrecautionsForStorage`**| | | 
| | | | | | | **`PackagedProductDefinition.package.manufacturer`**| _Equivalent_<br/>(1912/2150)| `PackagedProductDefinition.packaging.manufacturer`
| | | | | | | **`PackagedProductDefinition.package.property`**| | | 
| | | | | | | **`PackagedProductDefinition.package.property.id`**| | | 
| | | | | | | **`PackagedProductDefinition.package.property.extension`**| | | 
| | | | | | | **`PackagedProductDefinition.package.property.modifierExtension`**| | | 
| | | | | | | **`PackagedProductDefinition.package.property.type`**| _Equivalent_<br/>(1913/2151)| `PackagedProductDefinition.packaging.property.type`
| | | | | | | **`PackagedProductDefinition.package.property.value[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1914)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2152)| `PackagedProductDefinition.packaging.property.value[x]`
| | | | | | | **`PackagedProductDefinition.package.containedItem`**| | | 
| | | | | | | **`PackagedProductDefinition.package.containedItem.id`**| | | 
| | | | | | | **`PackagedProductDefinition.package.containedItem.extension`**| | | 
| | | | | | | **`PackagedProductDefinition.package.containedItem.modifierExtension`**| | | 
| | | | | | | **`PackagedProductDefinition.package.containedItem.item`**| _Equivalent_<br/>(1915/2153)| `PackagedProductDefinition.packaging.containedItem.item`
| | | | | | | **`PackagedProductDefinition.package.containedItem.amount`**| _Equivalent_<br/>(1916/2154)| `PackagedProductDefinition.packaging.containedItem.amount`
| | | | | | | **`PackagedProductDefinition.package.package`**| | | 
| | | | | | | *57 of 57 elements used* | | *37 of 53 elements used* <br/>remaining elements:<br/>`PackagedProductDefinition.attachedDocument`, `PackagedProductDefinition.packaging`, `PackagedProductDefinition.packaging.componentPart`, `PackagedProductDefinition.packaging.containedItem`, `PackagedProductDefinition.packaging.containedItem.extension`, `PackagedProductDefinition.packaging.containedItem.id`, `PackagedProductDefinition.packaging.containedItem.modifierExtension`, `PackagedProductDefinition.packaging.extension`, `PackagedProductDefinition.packaging.id`, `PackagedProductDefinition.packaging.modifierExtension`, `PackagedProductDefinition.packaging.packaging`, `PackagedProductDefinition.packaging.property`, `PackagedProductDefinition.packaging.property.extension`, `PackagedProductDefinition.packaging.property.id`, `PackagedProductDefinition.packaging.property.modifierExtension`, `PackagedProductDefinition.packaging.shelfLifeStorage`

