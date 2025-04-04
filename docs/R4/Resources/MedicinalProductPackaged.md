Comparison of 
Generated at Friday, April 4, 2025 2:58:45 PM

### MedicinalProductPackaged

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | MedicinalProductPackaged |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/MedicinalProductPackaged` |
| Version | 4.0.1 |
| Description | A medicinal product in a container or package. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1119` |
| Database Snapshot Count | `38` |
| Database Differential Count | `24` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `MedicinalProductPackaged` | `MedicinalProductPackaged` | `MedicinalProductPackaged` | MedicinalProductPackaged | A medicinal product in a container or package | 0..* | MedicinalProductPackaged |  |  |
| `MedicinalProductPackaged.batchIdentifier` | `MedicinalProductPackaged.batchIdentifier` | `batchIdentifier` | MedicinalProductPackaged.batchIdentifier | Batch numbering | 0..* | BackboneElement |  |  |
| `MedicinalProductPackaged.batchIdentifier.extension` | `MedicinalProductPackaged.batchIdentifier.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductPackaged.batchIdentifier.id` | `MedicinalProductPackaged.batchIdentifier.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProductPackaged.batchIdentifier.immediatePackaging` | `MedicinalProductPackaged.batchIdentifier.immediatePackaging` | `immediatePackaging` | MedicinalProductPackaged.batchIdentifier.immediatePackaging | A number appearing on the immediate packaging (and not the outer packaging) | 0..1 | Identifier |  |  |
| `MedicinalProductPackaged.batchIdentifier.modifierExtension` | `MedicinalProductPackaged.batchIdentifier.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProductPackaged.batchIdentifier.outerPackaging` | `MedicinalProductPackaged.batchIdentifier.outerPackaging` | `outerPackaging` | MedicinalProductPackaged.batchIdentifier.outerPackaging | A number appearing on the outer packaging of a specific batch | 1..1 | Identifier |  |  |
| `MedicinalProductPackaged.contained` | `MedicinalProductPackaged.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `MedicinalProductPackaged.description` | `MedicinalProductPackaged.description` | `description` | MedicinalProductPackaged.description | Textual description | 0..1 | string |  |  |
| `MedicinalProductPackaged.extension` | `MedicinalProductPackaged.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductPackaged.id` | `MedicinalProductPackaged.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `MedicinalProductPackaged.identifier` | `MedicinalProductPackaged.identifier` | `identifier` | MedicinalProductPackaged.identifier | Unique identifier | 0..* | Identifier |  |  |
| `MedicinalProductPackaged.implicitRules` | `MedicinalProductPackaged.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `MedicinalProductPackaged.language` | `MedicinalProductPackaged.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `MedicinalProductPackaged.legalStatusOfSupply` | `MedicinalProductPackaged.legalStatusOfSupply` | `legalStatusOfSupply` | MedicinalProductPackaged.legalStatusOfSupply | The legal status of supply of the medicinal product as classified by the regulator | 0..1 | CodeableConcept |  |  |
| `MedicinalProductPackaged.manufacturer` | `MedicinalProductPackaged.manufacturer` | `manufacturer` | MedicinalProductPackaged.manufacturer | Manufacturer of this Package Item | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `MedicinalProductPackaged.marketingAuthorization` | `MedicinalProductPackaged.marketingAuthorization` | `marketingAuthorization` | MedicinalProductPackaged.marketingAuthorization | Manufacturer of this Package Item | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProductAuthorization) |  |  |
| `MedicinalProductPackaged.marketingStatus` | `MedicinalProductPackaged.marketingStatus` | `marketingStatus` | MedicinalProductPackaged.marketingStatus | Marketing information | 0..* | MarketingStatus |  |  |
| `MedicinalProductPackaged.meta` | `MedicinalProductPackaged.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `MedicinalProductPackaged.modifierExtension` | `MedicinalProductPackaged.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MedicinalProductPackaged.packageItem` | `MedicinalProductPackaged.packageItem` | `packageItem` | MedicinalProductPackaged.packageItem | A packaging item, as a contained for medicine, possibly with other packaging items within | 1..* | BackboneElement |  |  |
| `MedicinalProductPackaged.packageItem.alternateMaterial` | `MedicinalProductPackaged.packageItem.alternateMaterial` | `alternateMaterial` | MedicinalProductPackaged.packageItem.alternateMaterial | A possible alternate material for the packaging | 0..* | CodeableConcept |  |  |
| `MedicinalProductPackaged.packageItem.device` | `MedicinalProductPackaged.packageItem.device` | `device` | MedicinalProductPackaged.packageItem.device | A device accompanying a medicinal product | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DeviceDefinition) |  |  |
| `MedicinalProductPackaged.packageItem.extension` | `MedicinalProductPackaged.packageItem.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductPackaged.packageItem.id` | `MedicinalProductPackaged.packageItem.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProductPackaged.packageItem.identifier` | `MedicinalProductPackaged.packageItem.identifier` | `identifier` | MedicinalProductPackaged.packageItem.identifier | Including possibly Data Carrier Identifier | 0..* | Identifier |  |  |
| `MedicinalProductPackaged.packageItem.manufacturedItem` | `MedicinalProductPackaged.packageItem.manufacturedItem` | `manufacturedItem` | MedicinalProductPackaged.packageItem.manufacturedItem | The manufactured item as contained in the packaged medicinal product | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProductManufactured) |  |  |
| `MedicinalProductPackaged.packageItem.manufacturer` | `MedicinalProductPackaged.packageItem.manufacturer` | `manufacturer` | MedicinalProductPackaged.packageItem.manufacturer | Manufacturer of this Package Item | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `MedicinalProductPackaged.packageItem.material` | `MedicinalProductPackaged.packageItem.material` | `material` | MedicinalProductPackaged.packageItem.material | Material type of the package item | 0..* | CodeableConcept |  |  |
| `MedicinalProductPackaged.packageItem.modifierExtension` | `MedicinalProductPackaged.packageItem.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProductPackaged.packageItem.otherCharacteristics` | `MedicinalProductPackaged.packageItem.otherCharacteristics` | `otherCharacteristics` | MedicinalProductPackaged.packageItem.otherCharacteristics | Other codeable characteristics | 0..* | CodeableConcept |  |  |
| `MedicinalProductPackaged.packageItem.packageItem` | `MedicinalProductPackaged.packageItem.packageItem` | `packageItem` | MedicinalProductPackaged.packageItem.packageItem | Allows containers within containers | 0..* | MedicinalProductPackaged.packageItem |  |  |
| `MedicinalProductPackaged.packageItem.physicalCharacteristics` | `MedicinalProductPackaged.packageItem.physicalCharacteristics` | `physicalCharacteristics` | MedicinalProductPackaged.packageItem.physicalCharacteristics | Dimensions, color etc. | 0..1 | ProdCharacteristic |  |  |
| `MedicinalProductPackaged.packageItem.quantity` | `MedicinalProductPackaged.packageItem.quantity` | `quantity` | MedicinalProductPackaged.packageItem.quantity | The quantity of this package in the medicinal product, at the current level of packaging. The outermost is always 1 | 1..1 | Quantity |  |  |
| `MedicinalProductPackaged.packageItem.shelfLifeStorage` | `MedicinalProductPackaged.packageItem.shelfLifeStorage` | `shelfLifeStorage` | MedicinalProductPackaged.packageItem.shelfLifeStorage | Shelf Life and storage information | 0..* | ProductShelfLife |  |  |
| `MedicinalProductPackaged.packageItem.type` | `MedicinalProductPackaged.packageItem.type` | `type` | MedicinalProductPackaged.packageItem.type | The physical type of the container of the medicine | 1..1 | CodeableConcept |  |  |
| `MedicinalProductPackaged.subject` | `MedicinalProductPackaged.subject` | `subject` | MedicinalProductPackaged.subject | The product with this is a pack for | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProduct) |  |  |
| `MedicinalProductPackaged.text` | `MedicinalProductPackaged.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

