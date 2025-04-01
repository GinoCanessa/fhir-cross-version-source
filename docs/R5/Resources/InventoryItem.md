Comparison of 
Generated at Tuesday, April 1, 2025 1:39:40 PM

### InventoryItem

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | InventoryItem |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/InventoryItem` |
| Version | 5.0.0 |
| Description | functional description of an inventory item used in inventory and supply-related workflows. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2327` |
| Database Snapshot Count | `58` |
| Database Differential Count | `32` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `InventoryItem` | `InventoryItem` | `InventoryItem` | InventoryItem | A functional description of an inventory item used in inventory and supply-related workflows | 0..* | InventoryItem |  |  |
| `InventoryItem.association` | `InventoryItem.association` | `association` | InventoryItem.association | Association with other items or products | 0..* | BackboneElement |  |  |
| `InventoryItem.association.associationType` | `InventoryItem.association.associationType` | `associationType` | InventoryItem.association.associationType | The type of association between the device and the other item | 1..1 | CodeableConcept |  |  |
| `InventoryItem.association.extension` | `InventoryItem.association.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `InventoryItem.association.id` | `InventoryItem.association.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `InventoryItem.association.modifierExtension` | `InventoryItem.association.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `InventoryItem.association.quantity` | `InventoryItem.association.quantity` | `quantity` | InventoryItem.association.quantity | The quantity of the product in this product | 1..1 | Ratio |  |  |
| `InventoryItem.association.relatedItem` | `InventoryItem.association.relatedItem` | `relatedItem` | InventoryItem.association.relatedItem | The related item or product | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/DeviceDefinition), Reference(http://hl7.org/fhir/StructureDefinition/InventoryItem), Reference(http://hl7.org/fhir/StructureDefinition/Medication), Reference(http://hl7.org/fhir/StructureDefinition/MedicationKnowledge), Reference(http://hl7.org/fhir/StructureDefinition/NutritionProduct) |  |  |
| `InventoryItem.baseUnit` | `InventoryItem.baseUnit` | `baseUnit` | InventoryItem.baseUnit | The base unit of measure - the unit in which the product is used or counted | 0..1 | CodeableConcept |  |  |
| `InventoryItem.category` | `InventoryItem.category` | `category` | InventoryItem.category | Category or class of the item | 0..* | CodeableConcept |  |  |
| `InventoryItem.characteristic` | `InventoryItem.characteristic` | `characteristic` | InventoryItem.characteristic | Characteristic of the item | 0..* | BackboneElement |  |  |
| `InventoryItem.characteristic.characteristicType` | `InventoryItem.characteristic.characteristicType` | `characteristicType` | InventoryItem.characteristic.characteristicType | The characteristic that is being defined | 1..1 | CodeableConcept |  |  |
| `InventoryItem.characteristic.extension` | `InventoryItem.characteristic.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `InventoryItem.characteristic.id` | `InventoryItem.characteristic.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `InventoryItem.characteristic.modifierExtension` | `InventoryItem.characteristic.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `InventoryItem.characteristic.value[x]` | `InventoryItem.characteristic.value[x]` | `value[x]` | InventoryItem.characteristic.value[x] | The value of the attribute | 1..1 | Address, Annotation, boolean, CodeableConcept, dateTime, decimal, Duration, integer, Quantity, Range, Ratio, string, url |  |  |
| `InventoryItem.code` | `InventoryItem.code` | `code` | InventoryItem.code | Code designating the specific type of item | 0..* | CodeableConcept |  |  |
| `InventoryItem.contained` | `InventoryItem.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `InventoryItem.description` | `InventoryItem.description` | `description` | InventoryItem.description | Descriptive characteristics of the item | 0..1 | BackboneElement |  |  |
| `InventoryItem.description.description` | `InventoryItem.description.description` | `description` | InventoryItem.description.description | Textual description of the item | 0..1 | string |  |  |
| `InventoryItem.description.extension` | `InventoryItem.description.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `InventoryItem.description.id` | `InventoryItem.description.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `InventoryItem.description.language` | `InventoryItem.description.language` | `language` | InventoryItem.description.language | The language that is used in the item description | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/languages|5.0.0` |
| `InventoryItem.description.modifierExtension` | `InventoryItem.description.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `InventoryItem.extension` | `InventoryItem.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `InventoryItem.id` | `InventoryItem.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `InventoryItem.identifier` | `InventoryItem.identifier` | `identifier` | InventoryItem.identifier | Business identifier for the inventory item | 0..* | Identifier |  |  |
| `InventoryItem.implicitRules` | `InventoryItem.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `InventoryItem.instance` | `InventoryItem.instance` | `instance` | InventoryItem.instance | Instances or occurrences of the product | 0..1 | BackboneElement |  |  |
| `InventoryItem.instance.expiry` | `InventoryItem.instance.expiry` | `expiry` | InventoryItem.instance.expiry | The expiry date or date and time for the product | 0..1 | dateTime |  |  |
| `InventoryItem.instance.extension` | `InventoryItem.instance.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `InventoryItem.instance.id` | `InventoryItem.instance.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `InventoryItem.instance.identifier` | `InventoryItem.instance.identifier` | `identifier` | InventoryItem.instance.identifier | The identifier for the physical instance, typically a serial number | 0..* | Identifier |  |  |
| `InventoryItem.instance.location` | `InventoryItem.instance.location` | `location` | InventoryItem.instance.location | The location that the item is associated with | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `InventoryItem.instance.lotNumber` | `InventoryItem.instance.lotNumber` | `lotNumber` | InventoryItem.instance.lotNumber | The lot or batch number of the item | 0..1 | string |  |  |
| `InventoryItem.instance.modifierExtension` | `InventoryItem.instance.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `InventoryItem.instance.subject` | `InventoryItem.instance.subject` | `subject` | InventoryItem.instance.subject | The subject that the item is associated with | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `InventoryItem.inventoryStatus` | `InventoryItem.inventoryStatus` | `inventoryStatus` | InventoryItem.inventoryStatus | The usage status like recalled, in use, discarded | 0..* | CodeableConcept |  |  |
| `InventoryItem.language` | `InventoryItem.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `InventoryItem.meta` | `InventoryItem.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `InventoryItem.modifierExtension` | `InventoryItem.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `InventoryItem.name` | `InventoryItem.name` | `name` | InventoryItem.name | The item name(s) - the brand name, or common name, functional name, generic name or others | 0..* | BackboneElement |  |  |
| `InventoryItem.name.extension` | `InventoryItem.name.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `InventoryItem.name.id` | `InventoryItem.name.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `InventoryItem.name.language` | `InventoryItem.name.language` | `language` | InventoryItem.name.language | The language used to express the item name | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/languages|5.0.0` |
| `InventoryItem.name.modifierExtension` | `InventoryItem.name.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `InventoryItem.name.name` | `InventoryItem.name.name` | `name` | InventoryItem.name.name | The name or designation of the item | 1..1 | string |  |  |
| `InventoryItem.name.nameType` | `InventoryItem.name.nameType` | `nameType` | InventoryItem.name.nameType | The type of name e.g. 'brand-name', 'functional-name', 'common-name' | 1..1 | Coding | `Preferred` | `http://hl7.org/fhir/ValueSet/inventoryitem-nametype` |
| `InventoryItem.netContent` | `InventoryItem.netContent` | `netContent` | InventoryItem.netContent | Net content or amount present in the item | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `InventoryItem.productReference` | `InventoryItem.productReference` | `productReference` | InventoryItem.productReference | Link to a product resource used in clinical workflows | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Medication), Reference(http://hl7.org/fhir/StructureDefinition/NutritionProduct) |  |  |
| `InventoryItem.responsibleOrganization` | `InventoryItem.responsibleOrganization` | `responsibleOrganization` | InventoryItem.responsibleOrganization | Organization(s) responsible for the product | 0..* | BackboneElement |  |  |
| `InventoryItem.responsibleOrganization.extension` | `InventoryItem.responsibleOrganization.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `InventoryItem.responsibleOrganization.id` | `InventoryItem.responsibleOrganization.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `InventoryItem.responsibleOrganization.modifierExtension` | `InventoryItem.responsibleOrganization.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `InventoryItem.responsibleOrganization.organization` | `InventoryItem.responsibleOrganization.organization` | `organization` | InventoryItem.responsibleOrganization.organization | An organization that is associated with the item | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `InventoryItem.responsibleOrganization.role` | `InventoryItem.responsibleOrganization.role` | `role` | InventoryItem.responsibleOrganization.role | The role of the organization e.g. manufacturer, distributor, or other | 1..1 | CodeableConcept |  |  |
| `InventoryItem.status` | `InventoryItem.status` | `status` | InventoryItem.status | active \| inactive \| entered-in-error \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/inventoryitem-status|5.0.0` |
| `InventoryItem.text` | `InventoryItem.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

