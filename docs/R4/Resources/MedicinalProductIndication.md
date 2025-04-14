Comparison of 
Generated at Monday, April 14, 2025 6:17:29 PM

### MedicinalProductIndication

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | MedicinalProductIndication |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/MedicinalProductIndication` |
| Version | 4.0.1 |
| Description | Indication for the Medicinal Product. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1115` |
| Database Snapshot Count | `23` |
| Database Differential Count | `12` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `MedicinalProductIndication` | `MedicinalProductIndication` | `MedicinalProductIndication` | MedicinalProductIndication | MedicinalProductIndication | 0..* | MedicinalProductIndication |  |  |
| `MedicinalProductIndication.comorbidity` | `MedicinalProductIndication.comorbidity` | `comorbidity` | MedicinalProductIndication.comorbidity | Comorbidity (concurrent condition) or co-infection as part of the indication | 0..* | CodeableConcept |  |  |
| `MedicinalProductIndication.contained` | `MedicinalProductIndication.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `MedicinalProductIndication.diseaseStatus` | `MedicinalProductIndication.diseaseStatus` | `diseaseStatus` | MedicinalProductIndication.diseaseStatus | The status of the disease or symptom for which the indication applies | 0..1 | CodeableConcept |  |  |
| `MedicinalProductIndication.diseaseSymptomProcedure` | `MedicinalProductIndication.diseaseSymptomProcedure` | `diseaseSymptomProcedure` | MedicinalProductIndication.diseaseSymptomProcedure | The disease, symptom or procedure that is the indication for treatment | 0..1 | CodeableConcept |  |  |
| `MedicinalProductIndication.duration` | `MedicinalProductIndication.duration` | `duration` | MedicinalProductIndication.duration | Timing or duration information as part of the indication | 0..1 | Quantity |  |  |
| `MedicinalProductIndication.extension` | `MedicinalProductIndication.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductIndication.id` | `MedicinalProductIndication.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `MedicinalProductIndication.implicitRules` | `MedicinalProductIndication.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `MedicinalProductIndication.intendedEffect` | `MedicinalProductIndication.intendedEffect` | `intendedEffect` | MedicinalProductIndication.intendedEffect | The intended effect, aim or strategy to be achieved by the indication | 0..1 | CodeableConcept |  |  |
| `MedicinalProductIndication.language` | `MedicinalProductIndication.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `MedicinalProductIndication.meta` | `MedicinalProductIndication.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `MedicinalProductIndication.modifierExtension` | `MedicinalProductIndication.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MedicinalProductIndication.otherTherapy` | `MedicinalProductIndication.otherTherapy` | `otherTherapy` | MedicinalProductIndication.otherTherapy | Information about the use of the medicinal product in relation to other therapies described as part of the indication | 0..* | BackboneElement |  |  |
| `MedicinalProductIndication.otherTherapy.extension` | `MedicinalProductIndication.otherTherapy.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicinalProductIndication.otherTherapy.id` | `MedicinalProductIndication.otherTherapy.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicinalProductIndication.otherTherapy.medication[x]` | `MedicinalProductIndication.otherTherapy.medication[x]` | `medication[x]` | MedicinalProductIndication.otherTherapy.medication[x] | Reference to a specific medication (active substance, medicinal product or class of products) as part of an indication or contraindication | 1..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Medication), Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProduct), Reference(http://hl7.org/fhir/StructureDefinition/Substance), Reference(http://hl7.org/fhir/StructureDefinition/SubstanceSpecification) |  |  |
| `MedicinalProductIndication.otherTherapy.modifierExtension` | `MedicinalProductIndication.otherTherapy.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicinalProductIndication.otherTherapy.therapyRelationshipType` | `MedicinalProductIndication.otherTherapy.therapyRelationshipType` | `therapyRelationshipType` | MedicinalProductIndication.otherTherapy.therapyRelationshipType | The type of relationship between the medicinal product indication or contraindication and another therapy | 1..1 | CodeableConcept |  |  |
| `MedicinalProductIndication.population` | `MedicinalProductIndication.population` | `population` | MedicinalProductIndication.population | The population group to which this applies | 0..* | Population |  |  |
| `MedicinalProductIndication.subject` | `MedicinalProductIndication.subject` | `subject` | MedicinalProductIndication.subject | The medication for which this is an indication | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Medication), Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProduct) |  |  |
| `MedicinalProductIndication.text` | `MedicinalProductIndication.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `MedicinalProductIndication.undesirableEffect` | `MedicinalProductIndication.undesirableEffect` | `undesirableEffect` | MedicinalProductIndication.undesirableEffect | Describe the undesirable effects of the medicinal product | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProductUndesirableEffect) |  |  |
### Empty Projection

This Structure (Resource) resulted in no projection (no mappings to other packages).

