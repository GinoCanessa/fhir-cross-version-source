Comparison of 
Generated at Thursday, April 3, 2025 8:18:19 AM

### MedicinalProductContraindication

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | MedicinalProductContraindication |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/MedicinalProductContraindication` |
| Version | 4.0.1 |
| Description | The clinical particulars - indications, contraindications etc. of a medicinal product, including for regulatory purposes. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1114` |
| Database Snapshot Count | `21` |
| Database Differential Count | `10` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `MedicinalProductContraindication` | `MedicinalProductContraindication` | `MedicinalProductContraindication` | MedicinalProductContraindication | MedicinalProductContraindication | 0..* | MedicinalProductContraindication |  |  |
| `MedicinalProductContraindication.comorbidity` | `MedicinalProductContraindication.comorbidity` | `comorbidity` | MedicinalProductContraindication.comorbidity | A comorbidity (concurrent condition) or coinfection | 0..* | CodeableConcept |  |  |
| `MedicinalProductContraindication.contained` | `MedicinalProductContraindication.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `MedicinalProductContraindication.disease` | `MedicinalProductContraindication.disease` | `disease` | MedicinalProductContraindication.disease | The disease, symptom or procedure for the contraindication | 0..1 | CodeableConcept |  |  |
| `MedicinalProductContraindication.diseaseStatus` | `MedicinalProductContraindication.diseaseStatus` | `diseaseStatus` | MedicinalProductContraindication.diseaseStatus | The status of the disease or symptom for the contraindication | 0..1 | CodeableConcept |  |  |
| `MedicinalProductContraindication.extension` | `MedicinalProductContraindication.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductContraindication.id` | `MedicinalProductContraindication.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `MedicinalProductContraindication.implicitRules` | `MedicinalProductContraindication.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `MedicinalProductContraindication.language` | `MedicinalProductContraindication.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `MedicinalProductContraindication.meta` | `MedicinalProductContraindication.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `MedicinalProductContraindication.modifierExtension` | `MedicinalProductContraindication.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MedicinalProductContraindication.otherTherapy` | `MedicinalProductContraindication.otherTherapy` | `otherTherapy` | MedicinalProductContraindication.otherTherapy | Information about the use of the medicinal product in relation to other therapies described as part of the indication | 0..* | BackboneElement |  |  |
| `MedicinalProductContraindication.otherTherapy.extension` | `MedicinalProductContraindication.otherTherapy.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductContraindication.otherTherapy.id` | `MedicinalProductContraindication.otherTherapy.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProductContraindication.otherTherapy.medication[x]` | `MedicinalProductContraindication.otherTherapy.medication[x]` | `medication[x]` | MedicinalProductContraindication.otherTherapy.medication[x] | Reference to a specific medication (active substance, medicinal product or class of products) as part of an indication or contraindication | 1..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Medication), Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProduct), Reference(http://hl7.org/fhir/StructureDefinition/Substance), Reference(http://hl7.org/fhir/StructureDefinition/SubstanceSpecification) |  |  |
| `MedicinalProductContraindication.otherTherapy.modifierExtension` | `MedicinalProductContraindication.otherTherapy.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProductContraindication.otherTherapy.therapyRelationshipType` | `MedicinalProductContraindication.otherTherapy.therapyRelationshipType` | `therapyRelationshipType` | MedicinalProductContraindication.otherTherapy.therapyRelationshipType | The type of relationship between the medicinal product indication or contraindication and another therapy | 1..1 | CodeableConcept |  |  |
| `MedicinalProductContraindication.population` | `MedicinalProductContraindication.population` | `population` | MedicinalProductContraindication.population | The population group to which this applies | 0..* | Population |  |  |
| `MedicinalProductContraindication.subject` | `MedicinalProductContraindication.subject` | `subject` | MedicinalProductContraindication.subject | The medication for which this is an indication | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Medication), Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProduct) |  |  |
| `MedicinalProductContraindication.text` | `MedicinalProductContraindication.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `MedicinalProductContraindication.therapeuticIndication` | `MedicinalProductContraindication.therapeuticIndication` | `therapeuticIndication` | MedicinalProductContraindication.therapeuticIndication | Information about the use of the medicinal product in relation to other therapies as part of the indication | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProductIndication) |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

