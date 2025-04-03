Comparison of 
Generated at Thursday, April 3, 2025 8:18:19 AM

### MedicinalProduct

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | MedicinalProduct |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/MedicinalProduct` |
| Version | 4.0.1 |
| Description | Detailed definition of a medicinal product, typically for uses other than direct patient care (e.g. regulatory use). |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1112` |
| Database Snapshot Count | `65` |
| Database Differential Count | `42` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `MedicinalProduct` | `MedicinalProduct` | `MedicinalProduct` | MedicinalProduct | Detailed definition of a medicinal product, typically for uses other than direct patient care (e.g. regulatory use) | 0..* | MedicinalProduct |  |  |
| `MedicinalProduct.additionalMonitoringIndicator` | `MedicinalProduct.additionalMonitoringIndicator` | `additionalMonitoringIndicator` | MedicinalProduct.additionalMonitoringIndicator | Whether the Medicinal Product is subject to additional monitoring for regulatory reasons | 0..1 | CodeableConcept |  |  |
| `MedicinalProduct.attachedDocument` | `MedicinalProduct.attachedDocument` | `attachedDocument` | MedicinalProduct.attachedDocument | Supporting documentation, typically for regulatory submission | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `MedicinalProduct.clinicalTrial` | `MedicinalProduct.clinicalTrial` | `clinicalTrial` | MedicinalProduct.clinicalTrial | Clinical trials or studies that this product is involved in | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ResearchStudy) |  |  |
| `MedicinalProduct.combinedPharmaceuticalDoseForm` | `MedicinalProduct.combinedPharmaceuticalDoseForm` | `combinedPharmaceuticalDoseForm` | MedicinalProduct.combinedPharmaceuticalDoseForm | The dose form for a single part product, or combined form of a multiple part product | 0..1 | CodeableConcept |  |  |
| `MedicinalProduct.contact` | `MedicinalProduct.contact` | `contact` | MedicinalProduct.contact | A product specific contact, person (in a role), or an organization | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `MedicinalProduct.contained` | `MedicinalProduct.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `MedicinalProduct.crossReference` | `MedicinalProduct.crossReference` | `crossReference` | MedicinalProduct.crossReference | Reference to another product, e.g. for linking authorised to investigational product | 0..* | Identifier |  |  |
| `MedicinalProduct.domain` | `MedicinalProduct.domain` | `domain` | MedicinalProduct.domain | If this medicine applies to human or veterinary uses | 0..1 | Coding |  |  |
| `MedicinalProduct.extension` | `MedicinalProduct.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProduct.id` | `MedicinalProduct.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `MedicinalProduct.identifier` | `MedicinalProduct.identifier` | `identifier` | MedicinalProduct.identifier | Business identifier for this product. Could be an MPID | 0..* | Identifier |  |  |
| `MedicinalProduct.implicitRules` | `MedicinalProduct.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `MedicinalProduct.language` | `MedicinalProduct.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `MedicinalProduct.legalStatusOfSupply` | `MedicinalProduct.legalStatusOfSupply` | `legalStatusOfSupply` | MedicinalProduct.legalStatusOfSupply | The legal status of supply of the medicinal product as classified by the regulator | 0..1 | CodeableConcept |  |  |
| `MedicinalProduct.manufacturingBusinessOperation` | `MedicinalProduct.manufacturingBusinessOperation` | `manufacturingBusinessOperation` | MedicinalProduct.manufacturingBusinessOperation | An operation applied to the product, for manufacturing or adminsitrative purpose | 0..* | BackboneElement |  |  |
| `MedicinalProduct.manufacturingBusinessOperation.authorisationReferenceNumber` | `MedicinalProduct.manufacturingBusinessOperation.authorisationReferenceNumber` | `authorisationReferenceNumber` | MedicinalProduct.manufacturingBusinessOperation.authorisationReferenceNumber | Regulatory authorization reference number | 0..1 | Identifier |  |  |
| `MedicinalProduct.manufacturingBusinessOperation.confidentialityIndicator` | `MedicinalProduct.manufacturingBusinessOperation.confidentialityIndicator` | `confidentialityIndicator` | MedicinalProduct.manufacturingBusinessOperation.confidentialityIndicator | To indicate if this proces is commercially confidential | 0..1 | CodeableConcept |  |  |
| `MedicinalProduct.manufacturingBusinessOperation.effectiveDate` | `MedicinalProduct.manufacturingBusinessOperation.effectiveDate` | `effectiveDate` | MedicinalProduct.manufacturingBusinessOperation.effectiveDate | Regulatory authorization date | 0..1 | dateTime |  |  |
| `MedicinalProduct.manufacturingBusinessOperation.extension` | `MedicinalProduct.manufacturingBusinessOperation.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProduct.manufacturingBusinessOperation.id` | `MedicinalProduct.manufacturingBusinessOperation.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProduct.manufacturingBusinessOperation.manufacturer` | `MedicinalProduct.manufacturingBusinessOperation.manufacturer` | `manufacturer` | MedicinalProduct.manufacturingBusinessOperation.manufacturer | The manufacturer or establishment associated with the process | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `MedicinalProduct.manufacturingBusinessOperation.modifierExtension` | `MedicinalProduct.manufacturingBusinessOperation.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProduct.manufacturingBusinessOperation.operationType` | `MedicinalProduct.manufacturingBusinessOperation.operationType` | `operationType` | MedicinalProduct.manufacturingBusinessOperation.operationType | The type of manufacturing operation | 0..1 | CodeableConcept |  |  |
| `MedicinalProduct.manufacturingBusinessOperation.regulator` | `MedicinalProduct.manufacturingBusinessOperation.regulator` | `regulator` | MedicinalProduct.manufacturingBusinessOperation.regulator | A regulator which oversees the operation | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `MedicinalProduct.marketingStatus` | `MedicinalProduct.marketingStatus` | `marketingStatus` | MedicinalProduct.marketingStatus | Marketing status of the medicinal product, in contrast to marketing authorizaton | 0..* | MarketingStatus |  |  |
| `MedicinalProduct.masterFile` | `MedicinalProduct.masterFile` | `masterFile` | MedicinalProduct.masterFile | A master file for to the medicinal product (e.g. Pharmacovigilance System Master File) | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `MedicinalProduct.meta` | `MedicinalProduct.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `MedicinalProduct.modifierExtension` | `MedicinalProduct.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MedicinalProduct.name` | `MedicinalProduct.name` | `name` | MedicinalProduct.name | The product's name, including full name and possibly coded parts | 1..* | BackboneElement |  |  |
| `MedicinalProduct.name.countryLanguage` | `MedicinalProduct.name.countryLanguage` | `countryLanguage` | MedicinalProduct.name.countryLanguage | Country where the name applies | 0..* | BackboneElement |  |  |
| `MedicinalProduct.name.countryLanguage.country` | `MedicinalProduct.name.countryLanguage.country` | `country` | MedicinalProduct.name.countryLanguage.country | Country code for where this name applies | 1..1 | CodeableConcept |  |  |
| `MedicinalProduct.name.countryLanguage.extension` | `MedicinalProduct.name.countryLanguage.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProduct.name.countryLanguage.id` | `MedicinalProduct.name.countryLanguage.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProduct.name.countryLanguage.jurisdiction` | `MedicinalProduct.name.countryLanguage.jurisdiction` | `jurisdiction` | MedicinalProduct.name.countryLanguage.jurisdiction | Jurisdiction code for where this name applies | 0..1 | CodeableConcept |  |  |
| `MedicinalProduct.name.countryLanguage.language` | `MedicinalProduct.name.countryLanguage.language` | `language` | MedicinalProduct.name.countryLanguage.language | Language code for this name | 1..1 | CodeableConcept |  |  |
| `MedicinalProduct.name.countryLanguage.modifierExtension` | `MedicinalProduct.name.countryLanguage.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProduct.name.extension` | `MedicinalProduct.name.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProduct.name.id` | `MedicinalProduct.name.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProduct.name.modifierExtension` | `MedicinalProduct.name.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProduct.name.namePart` | `MedicinalProduct.name.namePart` | `namePart` | MedicinalProduct.name.namePart | Coding words or phrases of the name | 0..* | BackboneElement |  |  |
| `MedicinalProduct.name.namePart.extension` | `MedicinalProduct.name.namePart.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProduct.name.namePart.id` | `MedicinalProduct.name.namePart.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProduct.name.namePart.modifierExtension` | `MedicinalProduct.name.namePart.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProduct.name.namePart.part` | `MedicinalProduct.name.namePart.part` | `part` | MedicinalProduct.name.namePart.part | A fragment of a product name | 1..1 | string |  |  |
| `MedicinalProduct.name.namePart.type` | `MedicinalProduct.name.namePart.type` | `type` | MedicinalProduct.name.namePart.type | Idenifying type for this part of the name (e.g. strength part) | 1..1 | Coding |  |  |
| `MedicinalProduct.name.productName` | `MedicinalProduct.name.productName` | `productName` | MedicinalProduct.name.productName | The full product name | 1..1 | string |  |  |
| `MedicinalProduct.packagedMedicinalProduct` | `MedicinalProduct.packagedMedicinalProduct` | `packagedMedicinalProduct` | MedicinalProduct.packagedMedicinalProduct | Package representation for the product | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProductPackaged) |  |  |
| `MedicinalProduct.paediatricUseIndicator` | `MedicinalProduct.paediatricUseIndicator` | `paediatricUseIndicator` | MedicinalProduct.paediatricUseIndicator | If authorised for use in children | 0..1 | CodeableConcept |  |  |
| `MedicinalProduct.pharmaceuticalProduct` | `MedicinalProduct.pharmaceuticalProduct` | `pharmaceuticalProduct` | MedicinalProduct.pharmaceuticalProduct | Pharmaceutical aspects of product | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProductPharmaceutical) |  |  |
| `MedicinalProduct.productClassification` | `MedicinalProduct.productClassification` | `productClassification` | MedicinalProduct.productClassification | Allows the product to be classified by various systems | 0..* | CodeableConcept |  |  |
| `MedicinalProduct.specialDesignation` | `MedicinalProduct.specialDesignation` | `specialDesignation` | MedicinalProduct.specialDesignation | Indicates if the medicinal product has an orphan designation for the treatment of a rare disease | 0..* | BackboneElement |  |  |
| `MedicinalProduct.specialDesignation.date` | `MedicinalProduct.specialDesignation.date` | `date` | MedicinalProduct.specialDesignation.date | Date when the designation was granted | 0..1 | dateTime |  |  |
| `MedicinalProduct.specialDesignation.extension` | `MedicinalProduct.specialDesignation.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProduct.specialDesignation.id` | `MedicinalProduct.specialDesignation.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProduct.specialDesignation.identifier` | `MedicinalProduct.specialDesignation.identifier` | `identifier` | MedicinalProduct.specialDesignation.identifier | Identifier for the designation, or procedure number | 0..* | Identifier |  |  |
| `MedicinalProduct.specialDesignation.indication[x]` | `MedicinalProduct.specialDesignation.indication[x]` | `indication[x]` | MedicinalProduct.specialDesignation.indication[x] | Condition for which the medicinal use applies | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProductIndication) |  |  |
| `MedicinalProduct.specialDesignation.intendedUse` | `MedicinalProduct.specialDesignation.intendedUse` | `intendedUse` | MedicinalProduct.specialDesignation.intendedUse | The intended use of the product, e.g. prevention, treatment | 0..1 | CodeableConcept |  |  |
| `MedicinalProduct.specialDesignation.modifierExtension` | `MedicinalProduct.specialDesignation.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProduct.specialDesignation.species` | `MedicinalProduct.specialDesignation.species` | `species` | MedicinalProduct.specialDesignation.species | Animal species for which this applies | 0..1 | CodeableConcept |  |  |
| `MedicinalProduct.specialDesignation.status` | `MedicinalProduct.specialDesignation.status` | `status` | MedicinalProduct.specialDesignation.status | For example granted, pending, expired or withdrawn | 0..1 | CodeableConcept |  |  |
| `MedicinalProduct.specialDesignation.type` | `MedicinalProduct.specialDesignation.type` | `type` | MedicinalProduct.specialDesignation.type | The type of special designation, e.g. orphan drug, minor use | 0..1 | CodeableConcept |  |  |
| `MedicinalProduct.specialMeasures` | `MedicinalProduct.specialMeasures` | `specialMeasures` | MedicinalProduct.specialMeasures | Whether the Medicinal Product is subject to special measures for regulatory reasons | 0..* | string |  |  |
| `MedicinalProduct.text` | `MedicinalProduct.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `MedicinalProduct.type` | `MedicinalProduct.type` | `type` | MedicinalProduct.type | Regulatory type, e.g. Investigational or Authorized | 0..1 | CodeableConcept |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

