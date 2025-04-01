Comparison of 
Generated at Tuesday, April 1, 2025 1:39:34 PM

### SNOMEDCTMedicationCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | SNOMEDCTMedicationCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/medication-codes` |
| Version | 5.0.0 |
| Description | This value set includes all drug or medicament substance codes and all pharmaceutical/biologic products from SNOMED CT - provided as an exemplar value set. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `4701` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ActivityDefinition` | `ActivityDefinition.product[x]` | `http://hl7.org/fhir/ValueSet/medication-codes` | `Example` | What's administered/supplied |
| `http://hl7.org/fhir/StructureDefinition/ConditionDefinition` | `ConditionDefinition.medication.code` | `http://hl7.org/fhir/ValueSet/medication-codes` | `Example` | Code for relevant Medication |
| `http://hl7.org/fhir/StructureDefinition/FormularyItem` | `FormularyItem.code` | `http://hl7.org/fhir/ValueSet/medication-codes` | `Example` | Codes that identify this formulary item |
| `http://hl7.org/fhir/StructureDefinition/Medication` | `Medication.code` | `http://hl7.org/fhir/ValueSet/medication-codes` | `Example` | Codes that identify this medication |
| `http://hl7.org/fhir/StructureDefinition/Medication` | `Medication.ingredient.item` | `http://hl7.org/fhir/ValueSet/medication-codes` | `Example` | The ingredient (substance or medication) that the ingredient.strength relates to |
| `http://hl7.org/fhir/StructureDefinition/MedicationAdministration` | `MedicationAdministration.medication` | `http://hl7.org/fhir/ValueSet/medication-codes` | `Example` | What was administered |
| `http://hl7.org/fhir/StructureDefinition/MedicationDispense` | `MedicationDispense.medication` | `http://hl7.org/fhir/ValueSet/medication-codes` | `Example` | What medication was supplied |
| `http://hl7.org/fhir/StructureDefinition/MedicationKnowledge` | `MedicationKnowledge.code` | `http://hl7.org/fhir/ValueSet/medication-codes` | `Example` | Code that identifies this medication |
| `http://hl7.org/fhir/StructureDefinition/MedicationRequest` | `MedicationRequest.medication` | `http://hl7.org/fhir/ValueSet/medication-codes` | `Example` | Medication to be taken |
| `http://hl7.org/fhir/StructureDefinition/MedicationStatement` | `MedicationStatement.medication` | `http://hl7.org/fhir/ValueSet/medication-codes` | `Example` | What medication was taken |
| `http://hl7.org/fhir/StructureDefinition/MedicinalProductDefinition` | `MedicinalProductDefinition.code` | `http://hl7.org/fhir/ValueSet/medication-codes` | `Example` | A code that this product is known by, within some formal terminology |

### Expansion Failure

Failed to expand this value set: Expansion is limited
