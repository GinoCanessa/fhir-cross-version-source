Comparison of 
Generated at Friday, April 4, 2025 2:58:46 PM

### MedicinalProductManufactured

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | MedicinalProductManufactured |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/MedicinalProductManufactured` |
| Version | 4.0.1 |
| Description | The manufactured item as contained in the packaged medicinal product. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1118` |
| Database Snapshot Count | `16` |
| Database Differential Count | `8` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `MedicinalProductManufactured` | `MedicinalProductManufactured` | `MedicinalProductManufactured` | MedicinalProductManufactured | The manufactured item as contained in the packaged medicinal product | 0..* | MedicinalProductManufactured |  |  |
| `MedicinalProductManufactured.contained` | `MedicinalProductManufactured.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `MedicinalProductManufactured.extension` | `MedicinalProductManufactured.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductManufactured.id` | `MedicinalProductManufactured.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `MedicinalProductManufactured.implicitRules` | `MedicinalProductManufactured.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `MedicinalProductManufactured.ingredient` | `MedicinalProductManufactured.ingredient` | `ingredient` | MedicinalProductManufactured.ingredient | Ingredient | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProductIngredient) |  |  |
| `MedicinalProductManufactured.language` | `MedicinalProductManufactured.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `MedicinalProductManufactured.manufacturedDoseForm` | `MedicinalProductManufactured.manufacturedDoseForm` | `manufacturedDoseForm` | MedicinalProductManufactured.manufacturedDoseForm | Dose form as manufactured and before any transformation into the pharmaceutical product | 1..1 | CodeableConcept |  |  |
| `MedicinalProductManufactured.manufacturer` | `MedicinalProductManufactured.manufacturer` | `manufacturer` | MedicinalProductManufactured.manufacturer | Manufacturer of the item (Note that this should be named "manufacturer" but it currently causes technical issues) | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `MedicinalProductManufactured.meta` | `MedicinalProductManufactured.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `MedicinalProductManufactured.modifierExtension` | `MedicinalProductManufactured.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MedicinalProductManufactured.otherCharacteristics` | `MedicinalProductManufactured.otherCharacteristics` | `otherCharacteristics` | MedicinalProductManufactured.otherCharacteristics | Other codeable characteristics | 0..* | CodeableConcept |  |  |
| `MedicinalProductManufactured.physicalCharacteristics` | `MedicinalProductManufactured.physicalCharacteristics` | `physicalCharacteristics` | MedicinalProductManufactured.physicalCharacteristics | Dimensions, color etc. | 0..1 | ProdCharacteristic |  |  |
| `MedicinalProductManufactured.quantity` | `MedicinalProductManufactured.quantity` | `quantity` | MedicinalProductManufactured.quantity | The quantity or "count number" of the manufactured item | 1..1 | Quantity |  |  |
| `MedicinalProductManufactured.text` | `MedicinalProductManufactured.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `MedicinalProductManufactured.unitOfPresentation` | `MedicinalProductManufactured.unitOfPresentation` | `unitOfPresentation` | MedicinalProductManufactured.unitOfPresentation | The “real world” units in which the quantity of the manufactured item is described | 0..1 | CodeableConcept |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

