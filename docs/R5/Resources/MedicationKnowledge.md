Comparison of 
Generated at Monday, April 14, 2025 6:17:48 PM

### MedicationKnowledge

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | MedicationKnowledge |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/MedicationKnowledge` |
| Version | 5.0.0 |
| Description | Information about a medication that is used to support knowledge. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2340` |
| Database Snapshot Count | `132` |
| Database Differential Count | `70` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `MedicationKnowledge` | `MedicationKnowledge` | `MedicationKnowledge` | MedicationKnowledge | Definition of Medication Knowledge | 0..* | MedicationKnowledge |  |  |
| `MedicationKnowledge.associatedMedication` | `MedicationKnowledge.associatedMedication` | `associatedMedication` | MedicationKnowledge.associatedMedication | The set of medication resources that are associated with this medication | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Medication) |  |  |
| `MedicationKnowledge.author` | `MedicationKnowledge.author` | `author` | MedicationKnowledge.author | Creator or owner of the knowledge or information about the medication | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `MedicationKnowledge.clinicalUseIssue` | `MedicationKnowledge.clinicalUseIssue` | `clinicalUseIssue` | MedicationKnowledge.clinicalUseIssue | Potential clinical issue with or between medication(s) | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ClinicalUseDefinition) |  |  |
| `MedicationKnowledge.code` | `MedicationKnowledge.code` | `code` | MedicationKnowledge.code | Code that identifies this medication | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/medication-codes` |
| `MedicationKnowledge.contained` | `MedicationKnowledge.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `MedicationKnowledge.cost` | `MedicationKnowledge.cost` | `cost` | MedicationKnowledge.cost | The pricing of the medication | 0..* | BackboneElement |  |  |
| `MedicationKnowledge.cost.cost[x]` | `MedicationKnowledge.cost.cost[x]` | `cost[x]` | MedicationKnowledge.cost.cost[x] | The price or category of the cost of the medication | 1..1 | CodeableConcept, Money | `Example` | `http://hl7.org/fhir/ValueSet/medication-cost-category` |
| `MedicationKnowledge.cost.effectiveDate` | `MedicationKnowledge.cost.effectiveDate` | `effectiveDate` | MedicationKnowledge.cost.effectiveDate | The date range for which the cost is effective | 0..* | Period |  |  |
| `MedicationKnowledge.cost.extension` | `MedicationKnowledge.cost.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicationKnowledge.cost.id` | `MedicationKnowledge.cost.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicationKnowledge.cost.modifierExtension` | `MedicationKnowledge.cost.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicationKnowledge.cost.source` | `MedicationKnowledge.cost.source` | `source` | MedicationKnowledge.cost.source | The source or owner for the price information | 0..1 | string |  |  |
| `MedicationKnowledge.cost.type` | `MedicationKnowledge.cost.type` | `type` | MedicationKnowledge.cost.type | The category of the cost information | 1..1 | CodeableConcept |  |  |
| `MedicationKnowledge.definitional` | `MedicationKnowledge.definitional` | `definitional` | MedicationKnowledge.definitional | Minimal definition information about the medication | 0..1 | BackboneElement |  |  |
| `MedicationKnowledge.definitional.definition` | `MedicationKnowledge.definitional.definition` | `definition` | MedicationKnowledge.definitional.definition | Definitional resources that provide more information about this medication | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/MedicinalProductDefinition) |  |  |
| `MedicationKnowledge.definitional.doseForm` | `MedicationKnowledge.definitional.doseForm` | `doseForm` | MedicationKnowledge.definitional.doseForm | powder \| tablets \| capsule + | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/medication-form-codes` |
| `MedicationKnowledge.definitional.drugCharacteristic` | `MedicationKnowledge.definitional.drugCharacteristic` | `drugCharacteristic` | MedicationKnowledge.definitional.drugCharacteristic | Specifies descriptive properties of the medicine | 0..* | BackboneElement |  |  |
| `MedicationKnowledge.definitional.drugCharacteristic.extension` | `MedicationKnowledge.definitional.drugCharacteristic.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicationKnowledge.definitional.drugCharacteristic.id` | `MedicationKnowledge.definitional.drugCharacteristic.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicationKnowledge.definitional.drugCharacteristic.modifierExtension` | `MedicationKnowledge.definitional.drugCharacteristic.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicationKnowledge.definitional.drugCharacteristic.type` | `MedicationKnowledge.definitional.drugCharacteristic.type` | `type` | MedicationKnowledge.definitional.drugCharacteristic.type | Code specifying the type of characteristic of medication | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/medicationknowledge-characteristic` |
| `MedicationKnowledge.definitional.drugCharacteristic.value[x]` | `MedicationKnowledge.definitional.drugCharacteristic.value[x]` | `value[x]` | MedicationKnowledge.definitional.drugCharacteristic.value[x] | Description of the characteristic | 0..1 | Attachment, base64Binary, CodeableConcept, Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity], string |  |  |
| `MedicationKnowledge.definitional.extension` | `MedicationKnowledge.definitional.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicationKnowledge.definitional.id` | `MedicationKnowledge.definitional.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicationKnowledge.definitional.ingredient` | `MedicationKnowledge.definitional.ingredient` | `ingredient` | MedicationKnowledge.definitional.ingredient | Active or inactive ingredient | 0..* | BackboneElement |  |  |
| `MedicationKnowledge.definitional.ingredient.extension` | `MedicationKnowledge.definitional.ingredient.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicationKnowledge.definitional.ingredient.id` | `MedicationKnowledge.definitional.ingredient.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicationKnowledge.definitional.ingredient.item` | `MedicationKnowledge.definitional.ingredient.item` | `item` | MedicationKnowledge.definitional.ingredient.item | Substances contained in the medication | 1..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/Substance) |  |  |
| `MedicationKnowledge.definitional.ingredient.modifierExtension` | `MedicationKnowledge.definitional.ingredient.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicationKnowledge.definitional.ingredient.strength[x]` | `MedicationKnowledge.definitional.ingredient.strength[x]` | `strength[x]` | MedicationKnowledge.definitional.ingredient.strength[x] | Quantity of ingredient present | 0..1 | CodeableConcept, Quantity, Ratio | `Example` | `http://hl7.org/fhir/ValueSet/medication-ingredientstrength` |
| `MedicationKnowledge.definitional.ingredient.type` | `MedicationKnowledge.definitional.ingredient.type` | `type` | MedicationKnowledge.definitional.ingredient.type | A code that defines the type of ingredient, active, base, etc | 0..1 | CodeableConcept | `Example` | `http://terminology.hl7.org/ValueSet/v3-RoleClassIngredientEntity` |
| `MedicationKnowledge.definitional.intendedRoute` | `MedicationKnowledge.definitional.intendedRoute` | `intendedRoute` | MedicationKnowledge.definitional.intendedRoute | The intended or approved route of administration | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/route-codes` |
| `MedicationKnowledge.definitional.modifierExtension` | `MedicationKnowledge.definitional.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicationKnowledge.extension` | `MedicationKnowledge.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicationKnowledge.id` | `MedicationKnowledge.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `MedicationKnowledge.identifier` | `MedicationKnowledge.identifier` | `identifier` | MedicationKnowledge.identifier | Business identifier for this medication | 0..* | Identifier |  |  |
| `MedicationKnowledge.implicitRules` | `MedicationKnowledge.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `MedicationKnowledge.indicationGuideline` | `MedicationKnowledge.indicationGuideline` | `indicationGuideline` | MedicationKnowledge.indicationGuideline | Guidelines or protocols for administration of the medication for an indication | 0..* | BackboneElement |  |  |
| `MedicationKnowledge.indicationGuideline.dosingGuideline` | `MedicationKnowledge.indicationGuideline.dosingGuideline` | `dosingGuideline` | MedicationKnowledge.indicationGuideline.dosingGuideline | Guidelines for dosage of the medication | 0..* | BackboneElement |  |  |
| `MedicationKnowledge.indicationGuideline.dosingGuideline.administrationTreatment` | `MedicationKnowledge.indicationGuideline.dosingGuideline.administrationTreatment` | `administrationTreatment` | MedicationKnowledge.indicationGuideline.dosingGuideline.administrationTreatment | Type of treatment the guideline applies to | 0..1 | CodeableConcept |  |  |
| `MedicationKnowledge.indicationGuideline.dosingGuideline.dosage` | `MedicationKnowledge.indicationGuideline.dosingGuideline.dosage` | `dosage` | MedicationKnowledge.indicationGuideline.dosingGuideline.dosage | Dosage for the medication for the specific guidelines | 0..* | BackboneElement |  |  |
| `MedicationKnowledge.indicationGuideline.dosingGuideline.dosage.dosage` | `MedicationKnowledge.indicationGuideline.dosingGuideline.dosage.dosage` | `dosage` | MedicationKnowledge.indicationGuideline.dosingGuideline.dosage.dosage | Dosage for the medication for the specific guidelines | 1..* | Dosage |  |  |
| `MedicationKnowledge.indicationGuideline.dosingGuideline.dosage.extension` | `MedicationKnowledge.indicationGuideline.dosingGuideline.dosage.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicationKnowledge.indicationGuideline.dosingGuideline.dosage.id` | `MedicationKnowledge.indicationGuideline.dosingGuideline.dosage.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicationKnowledge.indicationGuideline.dosingGuideline.dosage.modifierExtension` | `MedicationKnowledge.indicationGuideline.dosingGuideline.dosage.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicationKnowledge.indicationGuideline.dosingGuideline.dosage.type` | `MedicationKnowledge.indicationGuideline.dosingGuideline.dosage.type` | `type` | MedicationKnowledge.indicationGuideline.dosingGuideline.dosage.type | Category of dosage for a medication | 1..1 | CodeableConcept |  |  |
| `MedicationKnowledge.indicationGuideline.dosingGuideline.extension` | `MedicationKnowledge.indicationGuideline.dosingGuideline.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicationKnowledge.indicationGuideline.dosingGuideline.id` | `MedicationKnowledge.indicationGuideline.dosingGuideline.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicationKnowledge.indicationGuideline.dosingGuideline.modifierExtension` | `MedicationKnowledge.indicationGuideline.dosingGuideline.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicationKnowledge.indicationGuideline.dosingGuideline.patientCharacteristic` | `MedicationKnowledge.indicationGuideline.dosingGuideline.patientCharacteristic` | `patientCharacteristic` | MedicationKnowledge.indicationGuideline.dosingGuideline.patientCharacteristic | Characteristics of the patient that are relevant to the administration guidelines | 0..* | BackboneElement |  |  |
| `MedicationKnowledge.indicationGuideline.dosingGuideline.patientCharacteristic.extension` | `MedicationKnowledge.indicationGuideline.dosingGuideline.patientCharacteristic.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicationKnowledge.indicationGuideline.dosingGuideline.patientCharacteristic.id` | `MedicationKnowledge.indicationGuideline.dosingGuideline.patientCharacteristic.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicationKnowledge.indicationGuideline.dosingGuideline.patientCharacteristic.modifierExtension` | `MedicationKnowledge.indicationGuideline.dosingGuideline.patientCharacteristic.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicationKnowledge.indicationGuideline.dosingGuideline.patientCharacteristic.type` | `MedicationKnowledge.indicationGuideline.dosingGuideline.patientCharacteristic.type` | `type` | MedicationKnowledge.indicationGuideline.dosingGuideline.patientCharacteristic.type | Categorization of specific characteristic that is relevant to the administration guideline | 1..1 | CodeableConcept |  |  |
| `MedicationKnowledge.indicationGuideline.dosingGuideline.patientCharacteristic.value[x]` | `MedicationKnowledge.indicationGuideline.dosingGuideline.patientCharacteristic.value[x]` | `value[x]` | MedicationKnowledge.indicationGuideline.dosingGuideline.patientCharacteristic.value[x] | The specific characteristic | 0..1 | CodeableConcept, Quantity, Range |  |  |
| `MedicationKnowledge.indicationGuideline.dosingGuideline.treatmentIntent` | `MedicationKnowledge.indicationGuideline.dosingGuideline.treatmentIntent` | `treatmentIntent` | MedicationKnowledge.indicationGuideline.dosingGuideline.treatmentIntent | Intention of the treatment | 0..1 | CodeableConcept |  |  |
| `MedicationKnowledge.indicationGuideline.extension` | `MedicationKnowledge.indicationGuideline.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicationKnowledge.indicationGuideline.id` | `MedicationKnowledge.indicationGuideline.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicationKnowledge.indicationGuideline.indication` | `MedicationKnowledge.indicationGuideline.indication` | `indication` | MedicationKnowledge.indicationGuideline.indication | Indication for use that applies to the specific administration guideline | 0..* | CodeableReference(http://hl7.org/fhir/StructureDefinition/ClinicalUseDefinition) |  |  |
| `MedicationKnowledge.indicationGuideline.modifierExtension` | `MedicationKnowledge.indicationGuideline.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicationKnowledge.intendedJurisdiction` | `MedicationKnowledge.intendedJurisdiction` | `intendedJurisdiction` | MedicationKnowledge.intendedJurisdiction | Codes that identify the different jurisdictions for which the information of this resource was created | 0..* | CodeableConcept |  |  |
| `MedicationKnowledge.language` | `MedicationKnowledge.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `MedicationKnowledge.medicineClassification` | `MedicationKnowledge.medicineClassification` | `medicineClassification` | MedicationKnowledge.medicineClassification | Categorization of the medication within a formulary or classification system | 0..* | BackboneElement |  |  |
| `MedicationKnowledge.medicineClassification.classification` | `MedicationKnowledge.medicineClassification.classification` | `classification` | MedicationKnowledge.medicineClassification.classification | Specific category assigned to the medication | 0..* | CodeableConcept |  |  |
| `MedicationKnowledge.medicineClassification.extension` | `MedicationKnowledge.medicineClassification.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicationKnowledge.medicineClassification.id` | `MedicationKnowledge.medicineClassification.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicationKnowledge.medicineClassification.modifierExtension` | `MedicationKnowledge.medicineClassification.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicationKnowledge.medicineClassification.source[x]` | `MedicationKnowledge.medicineClassification.source[x]` | `source[x]` | MedicationKnowledge.medicineClassification.source[x] | The source of the classification | 0..1 | string, uri |  |  |
| `MedicationKnowledge.medicineClassification.type` | `MedicationKnowledge.medicineClassification.type` | `type` | MedicationKnowledge.medicineClassification.type | The type of category for the medication (for example, therapeutic classification, therapeutic sub-classification) | 1..1 | CodeableConcept |  |  |
| `MedicationKnowledge.meta` | `MedicationKnowledge.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `MedicationKnowledge.modifierExtension` | `MedicationKnowledge.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `MedicationKnowledge.monitoringProgram` | `MedicationKnowledge.monitoringProgram` | `monitoringProgram` | MedicationKnowledge.monitoringProgram | Program under which a medication is reviewed | 0..* | BackboneElement |  |  |
| `MedicationKnowledge.monitoringProgram.extension` | `MedicationKnowledge.monitoringProgram.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicationKnowledge.monitoringProgram.id` | `MedicationKnowledge.monitoringProgram.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicationKnowledge.monitoringProgram.modifierExtension` | `MedicationKnowledge.monitoringProgram.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicationKnowledge.monitoringProgram.name` | `MedicationKnowledge.monitoringProgram.name` | `name` | MedicationKnowledge.monitoringProgram.name | Name of the reviewing program | 0..1 | string |  |  |
| `MedicationKnowledge.monitoringProgram.type` | `MedicationKnowledge.monitoringProgram.type` | `type` | MedicationKnowledge.monitoringProgram.type | Type of program under which the medication is monitored | 0..1 | CodeableConcept |  |  |
| `MedicationKnowledge.monograph` | `MedicationKnowledge.monograph` | `monograph` | MedicationKnowledge.monograph | Associated documentation about the medication | 0..* | BackboneElement |  |  |
| `MedicationKnowledge.monograph.extension` | `MedicationKnowledge.monograph.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicationKnowledge.monograph.id` | `MedicationKnowledge.monograph.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicationKnowledge.monograph.modifierExtension` | `MedicationKnowledge.monograph.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicationKnowledge.monograph.source` | `MedicationKnowledge.monograph.source` | `source` | MedicationKnowledge.monograph.source | Associated documentation about the medication | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `MedicationKnowledge.monograph.type` | `MedicationKnowledge.monograph.type` | `type` | MedicationKnowledge.monograph.type | The category of medication document | 0..1 | CodeableConcept |  |  |
| `MedicationKnowledge.name` | `MedicationKnowledge.name` | `name` | MedicationKnowledge.name | A name associated with the medication being described | 0..* | string |  |  |
| `MedicationKnowledge.packaging` | `MedicationKnowledge.packaging` | `packaging` | MedicationKnowledge.packaging | Details about packaged medications | 0..* | BackboneElement |  |  |
| `MedicationKnowledge.packaging.cost` | `MedicationKnowledge.packaging.cost` | `cost` | MedicationKnowledge.packaging.cost | Cost of the packaged medication | 0..* | MedicationKnowledge.cost |  |  |
| `MedicationKnowledge.packaging.extension` | `MedicationKnowledge.packaging.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicationKnowledge.packaging.id` | `MedicationKnowledge.packaging.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicationKnowledge.packaging.modifierExtension` | `MedicationKnowledge.packaging.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicationKnowledge.packaging.packagedProduct` | `MedicationKnowledge.packaging.packagedProduct` | `packagedProduct` | MedicationKnowledge.packaging.packagedProduct | The packaged medication that is being priced | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/PackagedProductDefinition) |  |  |
| `MedicationKnowledge.preparationInstruction` | `MedicationKnowledge.preparationInstruction` | `preparationInstruction` | MedicationKnowledge.preparationInstruction | The instructions for preparing the medication | 0..1 | markdown |  |  |
| `MedicationKnowledge.productType` | `MedicationKnowledge.productType` | `productType` | MedicationKnowledge.productType | Category of the medication or product | 0..* | CodeableConcept |  |  |
| `MedicationKnowledge.regulatory` | `MedicationKnowledge.regulatory` | `regulatory` | MedicationKnowledge.regulatory | Regulatory information about a medication | 0..* | BackboneElement |  |  |
| `MedicationKnowledge.regulatory.extension` | `MedicationKnowledge.regulatory.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicationKnowledge.regulatory.id` | `MedicationKnowledge.regulatory.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicationKnowledge.regulatory.maxDispense` | `MedicationKnowledge.regulatory.maxDispense` | `maxDispense` | MedicationKnowledge.regulatory.maxDispense | The maximum number of units of the medication that can be dispensed in a period | 0..1 | BackboneElement |  |  |
| `MedicationKnowledge.regulatory.maxDispense.extension` | `MedicationKnowledge.regulatory.maxDispense.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicationKnowledge.regulatory.maxDispense.id` | `MedicationKnowledge.regulatory.maxDispense.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicationKnowledge.regulatory.maxDispense.modifierExtension` | `MedicationKnowledge.regulatory.maxDispense.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicationKnowledge.regulatory.maxDispense.period` | `MedicationKnowledge.regulatory.maxDispense.period` | `period` | MedicationKnowledge.regulatory.maxDispense.period | The period that applies to the maximum number of units | 0..1 | Duration |  |  |
| `MedicationKnowledge.regulatory.maxDispense.quantity` | `MedicationKnowledge.regulatory.maxDispense.quantity` | `quantity` | MedicationKnowledge.regulatory.maxDispense.quantity | The maximum number of units of the medication that can be dispensed | 1..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `MedicationKnowledge.regulatory.modifierExtension` | `MedicationKnowledge.regulatory.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicationKnowledge.regulatory.regulatoryAuthority` | `MedicationKnowledge.regulatory.regulatoryAuthority` | `regulatoryAuthority` | MedicationKnowledge.regulatory.regulatoryAuthority | Specifies the authority of the regulation | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `MedicationKnowledge.regulatory.schedule` | `MedicationKnowledge.regulatory.schedule` | `schedule` | MedicationKnowledge.regulatory.schedule | Specifies the schedule of a medication in jurisdiction | 0..* | CodeableConcept |  |  |
| `MedicationKnowledge.regulatory.substitution` | `MedicationKnowledge.regulatory.substitution` | `substitution` | MedicationKnowledge.regulatory.substitution | Specifies if changes are allowed when dispensing a medication from a regulatory perspective | 0..* | BackboneElement |  |  |
| `MedicationKnowledge.regulatory.substitution.allowed` | `MedicationKnowledge.regulatory.substitution.allowed` | `allowed` | MedicationKnowledge.regulatory.substitution.allowed | Specifies if regulation allows for changes in the medication when dispensing | 1..1 | boolean |  |  |
| `MedicationKnowledge.regulatory.substitution.extension` | `MedicationKnowledge.regulatory.substitution.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicationKnowledge.regulatory.substitution.id` | `MedicationKnowledge.regulatory.substitution.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicationKnowledge.regulatory.substitution.modifierExtension` | `MedicationKnowledge.regulatory.substitution.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicationKnowledge.regulatory.substitution.type` | `MedicationKnowledge.regulatory.substitution.type` | `type` | MedicationKnowledge.regulatory.substitution.type | Specifies the type of substitution allowed | 1..1 | CodeableConcept |  |  |
| `MedicationKnowledge.relatedMedicationKnowledge` | `MedicationKnowledge.relatedMedicationKnowledge` | `relatedMedicationKnowledge` | MedicationKnowledge.relatedMedicationKnowledge | Associated or related medication information | 0..* | BackboneElement |  |  |
| `MedicationKnowledge.relatedMedicationKnowledge.extension` | `MedicationKnowledge.relatedMedicationKnowledge.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicationKnowledge.relatedMedicationKnowledge.id` | `MedicationKnowledge.relatedMedicationKnowledge.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicationKnowledge.relatedMedicationKnowledge.modifierExtension` | `MedicationKnowledge.relatedMedicationKnowledge.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicationKnowledge.relatedMedicationKnowledge.reference` | `MedicationKnowledge.relatedMedicationKnowledge.reference` | `reference` | MedicationKnowledge.relatedMedicationKnowledge.reference | Associated documentation about the associated medication knowledge | 1..* | Reference(http://hl7.org/fhir/StructureDefinition/MedicationKnowledge) |  |  |
| `MedicationKnowledge.relatedMedicationKnowledge.type` | `MedicationKnowledge.relatedMedicationKnowledge.type` | `type` | MedicationKnowledge.relatedMedicationKnowledge.type | Category of medicationKnowledge | 1..1 | CodeableConcept |  |  |
| `MedicationKnowledge.status` | `MedicationKnowledge.status` | `status` | MedicationKnowledge.status | active \| entered-in-error \| inactive | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/medicationknowledge-status|5.0.0` |
| `MedicationKnowledge.storageGuideline` | `MedicationKnowledge.storageGuideline` | `storageGuideline` | MedicationKnowledge.storageGuideline | How the medication should be stored | 0..* | BackboneElement |  |  |
| `MedicationKnowledge.storageGuideline.environmentalSetting` | `MedicationKnowledge.storageGuideline.environmentalSetting` | `environmentalSetting` | MedicationKnowledge.storageGuideline.environmentalSetting | Setting or value of environment for adequate storage | 0..* | BackboneElement |  |  |
| `MedicationKnowledge.storageGuideline.environmentalSetting.extension` | `MedicationKnowledge.storageGuideline.environmentalSetting.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicationKnowledge.storageGuideline.environmentalSetting.id` | `MedicationKnowledge.storageGuideline.environmentalSetting.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicationKnowledge.storageGuideline.environmentalSetting.modifierExtension` | `MedicationKnowledge.storageGuideline.environmentalSetting.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicationKnowledge.storageGuideline.environmentalSetting.type` | `MedicationKnowledge.storageGuideline.environmentalSetting.type` | `type` | MedicationKnowledge.storageGuideline.environmentalSetting.type | Categorization of the setting | 1..1 | CodeableConcept |  |  |
| `MedicationKnowledge.storageGuideline.environmentalSetting.value[x]` | `MedicationKnowledge.storageGuideline.environmentalSetting.value[x]` | `value[x]` | MedicationKnowledge.storageGuideline.environmentalSetting.value[x] | Value of the setting | 1..1 | CodeableConcept, Quantity, Range |  |  |
| `MedicationKnowledge.storageGuideline.extension` | `MedicationKnowledge.storageGuideline.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MedicationKnowledge.storageGuideline.id` | `MedicationKnowledge.storageGuideline.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MedicationKnowledge.storageGuideline.modifierExtension` | `MedicationKnowledge.storageGuideline.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `MedicationKnowledge.storageGuideline.note` | `MedicationKnowledge.storageGuideline.note` | `note` | MedicationKnowledge.storageGuideline.note | Additional storage notes | 0..* | Annotation |  |  |
| `MedicationKnowledge.storageGuideline.reference` | `MedicationKnowledge.storageGuideline.reference` | `reference` | MedicationKnowledge.storageGuideline.reference | Reference to additional information | 0..1 | uri |  |  |
| `MedicationKnowledge.storageGuideline.stabilityDuration` | `MedicationKnowledge.storageGuideline.stabilityDuration` | `stabilityDuration` | MedicationKnowledge.storageGuideline.stabilityDuration | Duration remains stable | 0..1 | Duration |  |  |
| `MedicationKnowledge.text` | `MedicationKnowledge.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [MedicationKnowledge](/docs/R4/Resources/MedicationKnowledge.md)<br/> `http://hl7.org/fhir/StructureDefinition/MedicationKnowledge\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1541`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1542`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [MedicationKnowledge](/docs/R4B/Resources/MedicationKnowledge.md)<br/> `http://hl7.org/fhir/StructureDefinition/MedicationKnowledge\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1005`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1234`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [MedicationKnowledge](/docs/R5/Resources/MedicationKnowledge.md)<br/> `http://hl7.org/fhir/StructureDefinition/MedicationKnowledge\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition MedicationKnowledge from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | [R4 MedicationKnowledge](/docs/R4/Resources/MedicationKnowledge.md)| Relationship | [R4B MedicationKnowledge](/docs/R4B/Resources/MedicationKnowledge.md)| Relationship | R5 MedicationKnowledge
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `MedicationKnowledge`| _Equivalent_<br/>(29680/29681)| `MedicationKnowledge`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(44427)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(44428)| **`MedicationKnowledge`**
| | | | | `MedicationKnowledge.id`| _Equivalent_<br/>(29682/29683)| `MedicationKnowledge.id`| _Equivalent_<br/>(44429/44430)| **`MedicationKnowledge.id`**
| | | | | `MedicationKnowledge.meta`| _Equivalent_<br/>(29684/29685)| `MedicationKnowledge.meta`| _Equivalent_<br/>(44431/44432)| **`MedicationKnowledge.meta`**
| | | | | `MedicationKnowledge.implicitRules`| _Equivalent_<br/>(29686/29687)| `MedicationKnowledge.implicitRules`| _Equivalent_<br/>(44433/44434)| **`MedicationKnowledge.implicitRules`**
| | | | | `MedicationKnowledge.language`| _Equivalent_<br/>(29688/29689)| `MedicationKnowledge.language`| _Equivalent_<br/>(44435/44436)| **`MedicationKnowledge.language`**
| | | | | `MedicationKnowledge.text`| _Equivalent_<br/>(29690/29691)| `MedicationKnowledge.text`| _Equivalent_<br/>(44437/44438)| **`MedicationKnowledge.text`**
| | | | | `MedicationKnowledge.contained`| _Equivalent_<br/>(29692/29693)| `MedicationKnowledge.contained`| _Equivalent_<br/>(44439/44440)| **`MedicationKnowledge.contained`**
| | | | | `MedicationKnowledge.extension`| _Equivalent_<br/>(29694/29695)| `MedicationKnowledge.extension`| _Equivalent_<br/>(44441/44442)| **`MedicationKnowledge.extension`**
| | | | | `MedicationKnowledge.modifierExtension`| _Equivalent_<br/>(29696/29697)| `MedicationKnowledge.modifierExtension`| _Equivalent_<br/>(44443/44444)| **`MedicationKnowledge.modifierExtension`**
| | | | | | | | | **`MedicationKnowledge.identifier`**
| | | | | `MedicationKnowledge.code`| _Equivalent_<br/>(29698/29699)| `MedicationKnowledge.code`| _Equivalent_<br/>(44445/44446)| **`MedicationKnowledge.code`**
| | | | | `MedicationKnowledge.status`| _Equivalent_<br/>(29700/29701)| `MedicationKnowledge.status`| _Equivalent_<br/>(44447/44448)| **`MedicationKnowledge.status`**
| | | | | | | | | **`MedicationKnowledge.author`**
| | | | | | | | | **`MedicationKnowledge.intendedJurisdiction`**
| | | | | `MedicationKnowledge.synonym`| _Equivalent_<br/>(29708/29709)| `MedicationKnowledge.synonym`| _Equivalent_<br/>(1833/2076)| **`MedicationKnowledge.name`**
| | | | | `MedicationKnowledge.relatedMedicationKnowledge`| _Equivalent_<br/>(29710/29711)| `MedicationKnowledge.relatedMedicationKnowledge`| _Equivalent_<br/>(44452/44453)| **`MedicationKnowledge.relatedMedicationKnowledge`**
| | | | | `MedicationKnowledge.relatedMedicationKnowledge.id`| _Equivalent_<br/>(29712/29713)| `MedicationKnowledge.relatedMedicationKnowledge.id`| _Equivalent_<br/>(44454/44455)| **`MedicationKnowledge.relatedMedicationKnowledge.id`**
| | | | | `MedicationKnowledge.relatedMedicationKnowledge.extension`| _Equivalent_<br/>(29714/29715)| `MedicationKnowledge.relatedMedicationKnowledge.extension`| _Equivalent_<br/>(44456/44457)| **`MedicationKnowledge.relatedMedicationKnowledge.extension`**
| | | | | `MedicationKnowledge.relatedMedicationKnowledge.modifierExtension`| _Equivalent_<br/>(29716/29717)| `MedicationKnowledge.relatedMedicationKnowledge.modifierExtension`| _Equivalent_<br/>(44458/44459)| **`MedicationKnowledge.relatedMedicationKnowledge.modifierExtension`**
| | | | | `MedicationKnowledge.relatedMedicationKnowledge.type`| _Equivalent_<br/>(29718/29719)| `MedicationKnowledge.relatedMedicationKnowledge.type`| _Equivalent_<br/>(44460/44461)| **`MedicationKnowledge.relatedMedicationKnowledge.type`**
| | | | | `MedicationKnowledge.relatedMedicationKnowledge.reference`| _Equivalent_<br/>(29720/29721)| `MedicationKnowledge.relatedMedicationKnowledge.reference`| _Equivalent_<br/>(44462/44463)| **`MedicationKnowledge.relatedMedicationKnowledge.reference`**
| | | | | `MedicationKnowledge.associatedMedication`| _Equivalent_<br/>(29722/29723)| `MedicationKnowledge.associatedMedication`| _Equivalent_<br/>(44464/44465)| **`MedicationKnowledge.associatedMedication`**
| | | | | `MedicationKnowledge.productType`| _Equivalent_<br/>(29724/29725)| `MedicationKnowledge.productType`| _Equivalent_<br/>(44466/44467)| **`MedicationKnowledge.productType`**
| | | | | `MedicationKnowledge.monograph`| _Equivalent_<br/>(29726/29727)| `MedicationKnowledge.monograph`| _Equivalent_<br/>(44468/44469)| **`MedicationKnowledge.monograph`**
| | | | | `MedicationKnowledge.monograph.id`| _Equivalent_<br/>(29728/29729)| `MedicationKnowledge.monograph.id`| _Equivalent_<br/>(44470/44471)| **`MedicationKnowledge.monograph.id`**
| | | | | `MedicationKnowledge.monograph.extension`| _Equivalent_<br/>(29730/29731)| `MedicationKnowledge.monograph.extension`| _Equivalent_<br/>(44472/44473)| **`MedicationKnowledge.monograph.extension`**
| | | | | `MedicationKnowledge.monograph.modifierExtension`| _Equivalent_<br/>(29732/29733)| `MedicationKnowledge.monograph.modifierExtension`| _Equivalent_<br/>(44474/44475)| **`MedicationKnowledge.monograph.modifierExtension`**
| | | | | `MedicationKnowledge.monograph.type`| _Equivalent_<br/>(29734/29735)| `MedicationKnowledge.monograph.type`| _Equivalent_<br/>(44476/44477)| **`MedicationKnowledge.monograph.type`**
| | | | | `MedicationKnowledge.monograph.source`| _Equivalent_<br/>(29736/29737)| `MedicationKnowledge.monograph.source`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(44478)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(44479)| **`MedicationKnowledge.monograph.source`**
| | | | | `MedicationKnowledge.preparationInstruction`| _Equivalent_<br/>(29752/29753)| `MedicationKnowledge.preparationInstruction`| _Equivalent_<br/>(44487/44488)| **`MedicationKnowledge.preparationInstruction`**
| | | | | `MedicationKnowledge.cost`| _Equivalent_<br/>(29756/29757)| `MedicationKnowledge.cost`| _Equivalent_<br/>(44490/44491)| **`MedicationKnowledge.cost`**
| | | | | `MedicationKnowledge.cost.id`| _Equivalent_<br/>(29758/29759)| `MedicationKnowledge.cost.id`| _Equivalent_<br/>(44492/44493)| **`MedicationKnowledge.cost.id`**
| | | | | `MedicationKnowledge.cost.extension`| _Equivalent_<br/>(29760/29761)| `MedicationKnowledge.cost.extension`| _Equivalent_<br/>(44494/44495)| **`MedicationKnowledge.cost.extension`**
| | | | | `MedicationKnowledge.cost.modifierExtension`| _Equivalent_<br/>(29762/29763)| `MedicationKnowledge.cost.modifierExtension`| _Equivalent_<br/>(44496/44497)| **`MedicationKnowledge.cost.modifierExtension`**
| | | | | | | | | **`MedicationKnowledge.cost.effectiveDate`**
| | | | | `MedicationKnowledge.cost.type`| _Equivalent_<br/>(29764/29765)| `MedicationKnowledge.cost.type`| _Equivalent_<br/>(44498/44499)| **`MedicationKnowledge.cost.type`**
| | | | | `MedicationKnowledge.cost.source`| _Equivalent_<br/>(29766/29767)| `MedicationKnowledge.cost.source`| _Equivalent_<br/>(44500/44501)| **`MedicationKnowledge.cost.source`**
| | | | | `MedicationKnowledge.cost.cost`| _Equivalent_<br/>(29768/29769)| `MedicationKnowledge.cost.cost`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1832)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2075)| **`MedicationKnowledge.cost.cost[x]`**
| | | | | `MedicationKnowledge.monitoringProgram`| _Equivalent_<br/>(29770/29771)| `MedicationKnowledge.monitoringProgram`| _Equivalent_<br/>(44502/44503)| **`MedicationKnowledge.monitoringProgram`**
| | | | | `MedicationKnowledge.monitoringProgram.id`| _Equivalent_<br/>(29772/29773)| `MedicationKnowledge.monitoringProgram.id`| _Equivalent_<br/>(44504/44505)| **`MedicationKnowledge.monitoringProgram.id`**
| | | | | `MedicationKnowledge.monitoringProgram.extension`| _Equivalent_<br/>(29774/29775)| `MedicationKnowledge.monitoringProgram.extension`| _Equivalent_<br/>(44506/44507)| **`MedicationKnowledge.monitoringProgram.extension`**
| | | | | `MedicationKnowledge.monitoringProgram.modifierExtension`| _Equivalent_<br/>(29776/29777)| `MedicationKnowledge.monitoringProgram.modifierExtension`| _Equivalent_<br/>(44508/44509)| **`MedicationKnowledge.monitoringProgram.modifierExtension`**
| | | | | `MedicationKnowledge.monitoringProgram.type`| _Equivalent_<br/>(29778/29779)| `MedicationKnowledge.monitoringProgram.type`| _Equivalent_<br/>(44510/44511)| **`MedicationKnowledge.monitoringProgram.type`**
| | | | | `MedicationKnowledge.monitoringProgram.name`| _Equivalent_<br/>(29780/29781)| `MedicationKnowledge.monitoringProgram.name`| _Equivalent_<br/>(44512/44513)| **`MedicationKnowledge.monitoringProgram.name`**
| | | | | | | | | **`MedicationKnowledge.indicationGuideline`**
| | | | | | | | | **`MedicationKnowledge.indicationGuideline.id`**
| | | | | | | | | **`MedicationKnowledge.indicationGuideline.extension`**
| | | | | | | | | **`MedicationKnowledge.indicationGuideline.modifierExtension`**
| | | | | `MedicationKnowledge.administrationGuidelines.indication[x]`| _Equivalent_<br/>(29802/29803)| `MedicationKnowledge.administrationGuidelines.indication[x]`| →→→→ _RelatedTo_ →→→→ <br/>(1834)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2077)| **`MedicationKnowledge.indicationGuideline.indication`**
| | | | | | | | | **`MedicationKnowledge.indicationGuideline.dosingGuideline`**
| | | | | | | | | **`MedicationKnowledge.indicationGuideline.dosingGuideline.id`**
| | | | | | | | | **`MedicationKnowledge.indicationGuideline.dosingGuideline.extension`**
| | | | | | | | | **`MedicationKnowledge.indicationGuideline.dosingGuideline.modifierExtension`**
| | | | | | | | | **`MedicationKnowledge.indicationGuideline.dosingGuideline.treatmentIntent`**
| | | | | | | | | **`MedicationKnowledge.indicationGuideline.dosingGuideline.dosage`**
| | | | | | | | | **`MedicationKnowledge.indicationGuideline.dosingGuideline.dosage.id`**
| | | | | | | | | **`MedicationKnowledge.indicationGuideline.dosingGuideline.dosage.extension`**
| | | | | | | | | **`MedicationKnowledge.indicationGuideline.dosingGuideline.dosage.modifierExtension`**
| | | | | | | | | **`MedicationKnowledge.indicationGuideline.dosingGuideline.dosage.type`**
| | | | | | | | | **`MedicationKnowledge.indicationGuideline.dosingGuideline.dosage.dosage`**
| | | | | | | | | **`MedicationKnowledge.indicationGuideline.dosingGuideline.administrationTreatment`**
| | | | | | | | | **`MedicationKnowledge.indicationGuideline.dosingGuideline.patientCharacteristic`**
| | | | | | | | | **`MedicationKnowledge.indicationGuideline.dosingGuideline.patientCharacteristic.id`**
| | | | | | | | | **`MedicationKnowledge.indicationGuideline.dosingGuideline.patientCharacteristic.extension`**
| | | | | | | | | **`MedicationKnowledge.indicationGuideline.dosingGuideline.patientCharacteristic.modifierExtension`**
| | | | | | | | | **`MedicationKnowledge.indicationGuideline.dosingGuideline.patientCharacteristic.type`**
| | | | | | | | | **`MedicationKnowledge.indicationGuideline.dosingGuideline.patientCharacteristic.value[x]`**
| | | | | `MedicationKnowledge.medicineClassification`| _Equivalent_<br/>(29816/29817)| `MedicationKnowledge.medicineClassification`| _Equivalent_<br/>(44530/44531)| **`MedicationKnowledge.medicineClassification`**
| | | | | `MedicationKnowledge.medicineClassification.id`| _Equivalent_<br/>(29818/29819)| `MedicationKnowledge.medicineClassification.id`| _Equivalent_<br/>(44532/44533)| **`MedicationKnowledge.medicineClassification.id`**
| | | | | `MedicationKnowledge.medicineClassification.extension`| _Equivalent_<br/>(29820/29821)| `MedicationKnowledge.medicineClassification.extension`| _Equivalent_<br/>(44534/44535)| **`MedicationKnowledge.medicineClassification.extension`**
| | | | | `MedicationKnowledge.medicineClassification.modifierExtension`| _Equivalent_<br/>(29822/29823)| `MedicationKnowledge.medicineClassification.modifierExtension`| _Equivalent_<br/>(44536/44537)| **`MedicationKnowledge.medicineClassification.modifierExtension`**
| | | | | `MedicationKnowledge.medicineClassification.type`| _Equivalent_<br/>(29824/29825)| `MedicationKnowledge.medicineClassification.type`| _Equivalent_<br/>(44538/44539)| **`MedicationKnowledge.medicineClassification.type`**
| | | | | | | | | **`MedicationKnowledge.medicineClassification.source[x]`**
| | | | | `MedicationKnowledge.medicineClassification.classification`| _Equivalent_<br/>(29826/29827)| `MedicationKnowledge.medicineClassification.classification`| _Equivalent_<br/>(44540/44541)| **`MedicationKnowledge.medicineClassification.classification`**
| | | | | `MedicationKnowledge.packaging`| _Equivalent_<br/>(29828/29829)| `MedicationKnowledge.packaging`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(44542)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(44543)| **`MedicationKnowledge.packaging`**
| | | | | `MedicationKnowledge.packaging.id`| _Equivalent_<br/>(29830/29831)| `MedicationKnowledge.packaging.id`| _Equivalent_<br/>(44544/44545)| **`MedicationKnowledge.packaging.id`**
| | | | | `MedicationKnowledge.packaging.extension`| _Equivalent_<br/>(29832/29833)| `MedicationKnowledge.packaging.extension`| _Equivalent_<br/>(44546/44547)| **`MedicationKnowledge.packaging.extension`**
| | | | | `MedicationKnowledge.packaging.modifierExtension`| _Equivalent_<br/>(29834/29835)| `MedicationKnowledge.packaging.modifierExtension`| _Equivalent_<br/>(44548/44549)| **`MedicationKnowledge.packaging.modifierExtension`**
| | | | | | | | | **`MedicationKnowledge.packaging.cost`**
| | | | | | | | | **`MedicationKnowledge.packaging.packagedProduct`**
| | | | | | | | | **`MedicationKnowledge.clinicalUseIssue`**
| | | | | | | | | **`MedicationKnowledge.storageGuideline`**
| | | | | | | | | **`MedicationKnowledge.storageGuideline.id`**
| | | | | | | | | **`MedicationKnowledge.storageGuideline.extension`**
| | | | | | | | | **`MedicationKnowledge.storageGuideline.modifierExtension`**
| | | | | | | | | **`MedicationKnowledge.storageGuideline.reference`**
| | | | | | | | | **`MedicationKnowledge.storageGuideline.note`**
| | | | | | | | | **`MedicationKnowledge.storageGuideline.stabilityDuration`**
| | | | | | | | | **`MedicationKnowledge.storageGuideline.environmentalSetting`**
| | | | | | | | | **`MedicationKnowledge.storageGuideline.environmentalSetting.id`**
| | | | | | | | | **`MedicationKnowledge.storageGuideline.environmentalSetting.extension`**
| | | | | | | | | **`MedicationKnowledge.storageGuideline.environmentalSetting.modifierExtension`**
| | | | | | | | | **`MedicationKnowledge.storageGuideline.environmentalSetting.type`**
| | | | | | | | | **`MedicationKnowledge.storageGuideline.environmentalSetting.value[x]`**
| | | | | `MedicationKnowledge.regulatory`| _Equivalent_<br/>(29854/29855)| `MedicationKnowledge.regulatory`| _Equivalent_<br/>(44559/44560)| **`MedicationKnowledge.regulatory`**
| | | | | `MedicationKnowledge.regulatory.id`| _Equivalent_<br/>(29856/29857)| `MedicationKnowledge.regulatory.id`| _Equivalent_<br/>(44561/44562)| **`MedicationKnowledge.regulatory.id`**
| | | | | `MedicationKnowledge.regulatory.extension`| _Equivalent_<br/>(29858/29859)| `MedicationKnowledge.regulatory.extension`| _Equivalent_<br/>(44563/44564)| **`MedicationKnowledge.regulatory.extension`**
| | | | | `MedicationKnowledge.regulatory.modifierExtension`| _Equivalent_<br/>(29860/29861)| `MedicationKnowledge.regulatory.modifierExtension`| _Equivalent_<br/>(44565/44566)| **`MedicationKnowledge.regulatory.modifierExtension`**
| | | | | `MedicationKnowledge.regulatory.regulatoryAuthority`| _Equivalent_<br/>(29862/29863)| `MedicationKnowledge.regulatory.regulatoryAuthority`| _Equivalent_<br/>(44567/44568)| **`MedicationKnowledge.regulatory.regulatoryAuthority`**
| | | | | `MedicationKnowledge.regulatory.substitution`| _Equivalent_<br/>(29864/29865)| `MedicationKnowledge.regulatory.substitution`| _Equivalent_<br/>(44569/44570)| **`MedicationKnowledge.regulatory.substitution`**
| | | | | `MedicationKnowledge.regulatory.substitution.id`| _Equivalent_<br/>(29866/29867)| `MedicationKnowledge.regulatory.substitution.id`| _Equivalent_<br/>(44571/44572)| **`MedicationKnowledge.regulatory.substitution.id`**
| | | | | `MedicationKnowledge.regulatory.substitution.extension`| _Equivalent_<br/>(29868/29869)| `MedicationKnowledge.regulatory.substitution.extension`| _Equivalent_<br/>(44573/44574)| **`MedicationKnowledge.regulatory.substitution.extension`**
| | | | | `MedicationKnowledge.regulatory.substitution.modifierExtension`| _Equivalent_<br/>(29870/29871)| `MedicationKnowledge.regulatory.substitution.modifierExtension`| _Equivalent_<br/>(44575/44576)| **`MedicationKnowledge.regulatory.substitution.modifierExtension`**
| | | | | `MedicationKnowledge.regulatory.substitution.type`| _Equivalent_<br/>(29872/29873)| `MedicationKnowledge.regulatory.substitution.type`| _Equivalent_<br/>(44577/44578)| **`MedicationKnowledge.regulatory.substitution.type`**
| | | | | `MedicationKnowledge.regulatory.substitution.allowed`| _Equivalent_<br/>(29874/29875)| `MedicationKnowledge.regulatory.substitution.allowed`| _Equivalent_<br/>(44579/44580)| **`MedicationKnowledge.regulatory.substitution.allowed`**
| | | | | `MedicationKnowledge.regulatory.schedule`| _Equivalent_<br/>(29876/29877)| `MedicationKnowledge.regulatory.schedule`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(44581)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(44582)| **`MedicationKnowledge.regulatory.schedule`**
| | | | | `MedicationKnowledge.regulatory.maxDispense`| _Equivalent_<br/>(29886/29887)| `MedicationKnowledge.regulatory.maxDispense`| _Equivalent_<br/>(44587/44588)| **`MedicationKnowledge.regulatory.maxDispense`**
| | | | | `MedicationKnowledge.regulatory.maxDispense.id`| _Equivalent_<br/>(29888/29889)| `MedicationKnowledge.regulatory.maxDispense.id`| _Equivalent_<br/>(44589/44590)| **`MedicationKnowledge.regulatory.maxDispense.id`**
| | | | | `MedicationKnowledge.regulatory.maxDispense.extension`| _Equivalent_<br/>(29890/29891)| `MedicationKnowledge.regulatory.maxDispense.extension`| _Equivalent_<br/>(44591/44592)| **`MedicationKnowledge.regulatory.maxDispense.extension`**
| | | | | `MedicationKnowledge.regulatory.maxDispense.modifierExtension`| _Equivalent_<br/>(29892/29893)| `MedicationKnowledge.regulatory.maxDispense.modifierExtension`| _Equivalent_<br/>(44593/44594)| **`MedicationKnowledge.regulatory.maxDispense.modifierExtension`**
| | | | | `MedicationKnowledge.regulatory.maxDispense.quantity`| _Equivalent_<br/>(29894/29895)| `MedicationKnowledge.regulatory.maxDispense.quantity`| _Equivalent_<br/>(44595/44596)| **`MedicationKnowledge.regulatory.maxDispense.quantity`**
| | | | | `MedicationKnowledge.regulatory.maxDispense.period`| _Equivalent_<br/>(29896/29897)| `MedicationKnowledge.regulatory.maxDispense.period`| _Equivalent_<br/>(44597/44598)| **`MedicationKnowledge.regulatory.maxDispense.period`**
| | | | | | | | | **`MedicationKnowledge.definitional`**
| | | | | | | | | **`MedicationKnowledge.definitional.id`**
| | | | | | | | | **`MedicationKnowledge.definitional.extension`**
| | | | | | | | | **`MedicationKnowledge.definitional.modifierExtension`**
| | | | | | | | | **`MedicationKnowledge.definitional.definition`**
| | | | | | | | | **`MedicationKnowledge.definitional.doseForm`**
| | | | | | | | | **`MedicationKnowledge.definitional.intendedRoute`**
| | | | | | | | | **`MedicationKnowledge.definitional.ingredient`**
| | | | | | | | | **`MedicationKnowledge.definitional.ingredient.id`**
| | | | | | | | | **`MedicationKnowledge.definitional.ingredient.extension`**
| | | | | | | | | **`MedicationKnowledge.definitional.ingredient.modifierExtension`**
| | | | | | | | | **`MedicationKnowledge.definitional.ingredient.item`**
| | | | | | | | | **`MedicationKnowledge.definitional.ingredient.type`**
| | | | | | | | | **`MedicationKnowledge.definitional.ingredient.strength[x]`**
| | | | | | | | | **`MedicationKnowledge.definitional.drugCharacteristic`**
| | | | | | | | | **`MedicationKnowledge.definitional.drugCharacteristic.id`**
| | | | | | | | | **`MedicationKnowledge.definitional.drugCharacteristic.extension`**
| | | | | | | | | **`MedicationKnowledge.definitional.drugCharacteristic.modifierExtension`**
| | | | | | | | | **`MedicationKnowledge.definitional.drugCharacteristic.type`**
| | | | | | | | | **`MedicationKnowledge.definitional.drugCharacteristic.value[x]`**
| | | | | *69 of 116 elements used* <br/>remaining elements:<br/>`MedicationKnowledge.administrationGuidelines`, `MedicationKnowledge.administrationGuidelines.dosage`, `MedicationKnowledge.administrationGuidelines.dosage.dosage`, `MedicationKnowledge.administrationGuidelines.dosage.extension`, `MedicationKnowledge.administrationGuidelines.dosage.id`, `MedicationKnowledge.administrationGuidelines.dosage.modifierExtension`, `MedicationKnowledge.administrationGuidelines.dosage.type`, `MedicationKnowledge.administrationGuidelines.extension`, `MedicationKnowledge.administrationGuidelines.id`, `MedicationKnowledge.administrationGuidelines.modifierExtension`, `MedicationKnowledge.administrationGuidelines.patientCharacteristics`, `MedicationKnowledge.administrationGuidelines.patientCharacteristics.characteristic[x]`, `MedicationKnowledge.administrationGuidelines.patientCharacteristics.extension`, `MedicationKnowledge.administrationGuidelines.patientCharacteristics.id`, `MedicationKnowledge.administrationGuidelines.patientCharacteristics.modifierExtension`, `MedicationKnowledge.administrationGuidelines.patientCharacteristics.value`, `MedicationKnowledge.amount`, `MedicationKnowledge.contraindication`, `MedicationKnowledge.doseForm`, `MedicationKnowledge.drugCharacteristic`, `MedicationKnowledge.drugCharacteristic.extension`, `MedicationKnowledge.drugCharacteristic.id`, `MedicationKnowledge.drugCharacteristic.modifierExtension`, `MedicationKnowledge.drugCharacteristic.type`, `MedicationKnowledge.drugCharacteristic.value[x]`, `MedicationKnowledge.ingredient`, `MedicationKnowledge.ingredient.extension`, `MedicationKnowledge.ingredient.id`, `MedicationKnowledge.ingredient.isActive`, `MedicationKnowledge.ingredient.item[x]`, `MedicationKnowledge.ingredient.modifierExtension`, `MedicationKnowledge.ingredient.strength`, `MedicationKnowledge.intendedRoute`, `MedicationKnowledge.kinetics`, `MedicationKnowledge.kinetics.areaUnderCurve`, `MedicationKnowledge.kinetics.extension`, `MedicationKnowledge.kinetics.halfLifePeriod`, `MedicationKnowledge.kinetics.id`, `MedicationKnowledge.kinetics.lethalDose50`, `MedicationKnowledge.kinetics.modifierExtension`, `MedicationKnowledge.manufacturer`, `MedicationKnowledge.packaging.quantity`, `MedicationKnowledge.packaging.type`, `MedicationKnowledge.regulatory.schedule.extension`, `MedicationKnowledge.regulatory.schedule.id`, `MedicationKnowledge.regulatory.schedule.modifierExtension`, `MedicationKnowledge.regulatory.schedule.schedule`| | *69 of 116 elements used* <br/>remaining elements:<br/>`MedicationKnowledge.administrationGuidelines`, `MedicationKnowledge.administrationGuidelines.dosage`, `MedicationKnowledge.administrationGuidelines.dosage.dosage`, `MedicationKnowledge.administrationGuidelines.dosage.extension`, `MedicationKnowledge.administrationGuidelines.dosage.id`, `MedicationKnowledge.administrationGuidelines.dosage.modifierExtension`, `MedicationKnowledge.administrationGuidelines.dosage.type`, `MedicationKnowledge.administrationGuidelines.extension`, `MedicationKnowledge.administrationGuidelines.id`, `MedicationKnowledge.administrationGuidelines.modifierExtension`, `MedicationKnowledge.administrationGuidelines.patientCharacteristics`, `MedicationKnowledge.administrationGuidelines.patientCharacteristics.characteristic[x]`, `MedicationKnowledge.administrationGuidelines.patientCharacteristics.extension`, `MedicationKnowledge.administrationGuidelines.patientCharacteristics.id`, `MedicationKnowledge.administrationGuidelines.patientCharacteristics.modifierExtension`, `MedicationKnowledge.administrationGuidelines.patientCharacteristics.value`, `MedicationKnowledge.amount`, `MedicationKnowledge.contraindication`, `MedicationKnowledge.doseForm`, `MedicationKnowledge.drugCharacteristic`, `MedicationKnowledge.drugCharacteristic.extension`, `MedicationKnowledge.drugCharacteristic.id`, `MedicationKnowledge.drugCharacteristic.modifierExtension`, `MedicationKnowledge.drugCharacteristic.type`, `MedicationKnowledge.drugCharacteristic.value[x]`, `MedicationKnowledge.ingredient`, `MedicationKnowledge.ingredient.extension`, `MedicationKnowledge.ingredient.id`, `MedicationKnowledge.ingredient.isActive`, `MedicationKnowledge.ingredient.item[x]`, `MedicationKnowledge.ingredient.modifierExtension`, `MedicationKnowledge.ingredient.strength`, `MedicationKnowledge.intendedRoute`, `MedicationKnowledge.kinetics`, `MedicationKnowledge.kinetics.areaUnderCurve`, `MedicationKnowledge.kinetics.extension`, `MedicationKnowledge.kinetics.halfLifePeriod`, `MedicationKnowledge.kinetics.id`, `MedicationKnowledge.kinetics.lethalDose50`, `MedicationKnowledge.kinetics.modifierExtension`, `MedicationKnowledge.manufacturer`, `MedicationKnowledge.packaging.quantity`, `MedicationKnowledge.packaging.type`, `MedicationKnowledge.regulatory.schedule.extension`, `MedicationKnowledge.regulatory.schedule.id`, `MedicationKnowledge.regulatory.schedule.modifierExtension`, `MedicationKnowledge.regulatory.schedule.schedule`| | *132 of 132 elements used* 

