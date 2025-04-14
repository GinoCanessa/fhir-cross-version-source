Comparison of 
Generated at Monday, April 14, 2025 6:17:45 PM

### InventoryReport

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | InventoryReport |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/InventoryReport` |
| Version | 5.0.0 |
| Description | A report of inventory or stock items. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2328` |
| Database Snapshot Count | `32` |
| Database Differential Count | `18` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `InventoryReport` | `InventoryReport` | `InventoryReport` | InventoryReport | A report of inventory or stock items | 0..* | InventoryReport |  |  |
| `InventoryReport.contained` | `InventoryReport.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `InventoryReport.countType` | `InventoryReport.countType` | `countType` | InventoryReport.countType | snapshot \| difference | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/inventoryreport-counttype|5.0.0` |
| `InventoryReport.extension` | `InventoryReport.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `InventoryReport.id` | `InventoryReport.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `InventoryReport.identifier` | `InventoryReport.identifier` | `identifier` | InventoryReport.identifier | Business identifier for the report | 0..* | Identifier |  |  |
| `InventoryReport.implicitRules` | `InventoryReport.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `InventoryReport.inventoryListing` | `InventoryReport.inventoryListing` | `inventoryListing` | InventoryReport.inventoryListing | An inventory listing section (grouped by any of the attributes) | 0..* | BackboneElement |  |  |
| `InventoryReport.inventoryListing.countingDateTime` | `InventoryReport.inventoryListing.countingDateTime` | `countingDateTime` | InventoryReport.inventoryListing.countingDateTime | The date and time when the items were counted | 0..1 | dateTime |  |  |
| `InventoryReport.inventoryListing.extension` | `InventoryReport.inventoryListing.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `InventoryReport.inventoryListing.id` | `InventoryReport.inventoryListing.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `InventoryReport.inventoryListing.item` | `InventoryReport.inventoryListing.item` | `item` | InventoryReport.inventoryListing.item | The item or items in this listing | 0..* | BackboneElement |  |  |
| `InventoryReport.inventoryListing.item.category` | `InventoryReport.inventoryListing.item.category` | `category` | InventoryReport.inventoryListing.item.category | The inventory category or classification of the items being reported | 0..1 | CodeableConcept |  |  |
| `InventoryReport.inventoryListing.item.extension` | `InventoryReport.inventoryListing.item.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `InventoryReport.inventoryListing.item.id` | `InventoryReport.inventoryListing.item.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `InventoryReport.inventoryListing.item.item` | `InventoryReport.inventoryListing.item.item` | `item` | InventoryReport.inventoryListing.item.item | The code or reference to the item type | 1..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct), CodeableReference(http://hl7.org/fhir/StructureDefinition/Device), CodeableReference(http://hl7.org/fhir/StructureDefinition/InventoryItem), CodeableReference(http://hl7.org/fhir/StructureDefinition/InventoryItem), CodeableReference(http://hl7.org/fhir/StructureDefinition/Medication), CodeableReference(http://hl7.org/fhir/StructureDefinition/Medication), CodeableReference(http://hl7.org/fhir/StructureDefinition/NutritionProduct) |  |  |
| `InventoryReport.inventoryListing.item.modifierExtension` | `InventoryReport.inventoryListing.item.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `InventoryReport.inventoryListing.item.quantity` | `InventoryReport.inventoryListing.item.quantity` | `quantity` | InventoryReport.inventoryListing.item.quantity | The quantity of the item or items being reported | 1..1 | Quantity |  |  |
| `InventoryReport.inventoryListing.itemStatus` | `InventoryReport.inventoryListing.itemStatus` | `itemStatus` | InventoryReport.inventoryListing.itemStatus | The status of the items that are being reported | 0..1 | CodeableConcept |  |  |
| `InventoryReport.inventoryListing.location` | `InventoryReport.inventoryListing.location` | `location` | InventoryReport.inventoryListing.location | Location of the inventory items | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `InventoryReport.inventoryListing.modifierExtension` | `InventoryReport.inventoryListing.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `InventoryReport.language` | `InventoryReport.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `InventoryReport.meta` | `InventoryReport.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `InventoryReport.modifierExtension` | `InventoryReport.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `InventoryReport.note` | `InventoryReport.note` | `note` | InventoryReport.note | A note associated with the InventoryReport | 0..* | Annotation |  |  |
| `InventoryReport.operationType` | `InventoryReport.operationType` | `operationType` | InventoryReport.operationType | addition \| subtraction | 0..1 | CodeableConcept |  |  |
| `InventoryReport.operationTypeReason` | `InventoryReport.operationTypeReason` | `operationTypeReason` | InventoryReport.operationTypeReason | The reason for this count - regular count, ad-hoc count, new arrivals, etc | 0..1 | CodeableConcept |  |  |
| `InventoryReport.reportedDateTime` | `InventoryReport.reportedDateTime` | `reportedDateTime` | InventoryReport.reportedDateTime | When the report has been submitted | 1..1 | dateTime |  |  |
| `InventoryReport.reporter` | `InventoryReport.reporter` | `reporter` | InventoryReport.reporter | Who submits the report | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `InventoryReport.reportingPeriod` | `InventoryReport.reportingPeriod` | `reportingPeriod` | InventoryReport.reportingPeriod | The period the report refers to | 0..1 | Period |  |  |
| `InventoryReport.status` | `InventoryReport.status` | `status` | InventoryReport.status | draft \| requested \| active \| entered-in-error | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/inventoryreport-status|5.0.0` |
| `InventoryReport.text` | `InventoryReport.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

