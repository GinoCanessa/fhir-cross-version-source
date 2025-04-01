Comparison of 
Generated at Tuesday, April 1, 2025 1:39:25 PM

### SNOMEDCTMedicationCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | SNOMEDCTMedicationCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/medication-codes` |
| Version | 4.3.0 |
| Description | This value set includes all drug or medicament substance codes and all pharmaceutical/biologic products from SNOMED CT - provided as an exemplar value set. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `3903` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ActivityDefinition` | `ActivityDefinition.product[x]` | `http://hl7.org/fhir/ValueSet/medication-codes` | `Example` | What's administered/supplied |
| `http://hl7.org/fhir/StructureDefinition/CarePlan` | `CarePlan.activity.detail.product[x]` | `http://hl7.org/fhir/ValueSet/medication-codes` | `Example` | What is to be administered/supplied |
| `http://hl7.org/fhir/StructureDefinition/Medication` | `Medication.code` | `http://hl7.org/fhir/ValueSet/medication-codes` | `Example` | Codes that identify this medication |
| `http://hl7.org/fhir/StructureDefinition/MedicationAdministration` | `MedicationAdministration.medication[x]` | `http://hl7.org/fhir/ValueSet/medication-codes` | `Example` | What was administered |
| `http://hl7.org/fhir/StructureDefinition/MedicationDispense` | `MedicationDispense.medication[x]` | `http://hl7.org/fhir/ValueSet/medication-codes` | `Example` | What medication was supplied |
| `http://hl7.org/fhir/StructureDefinition/MedicationKnowledge` | `MedicationKnowledge.code` | `http://hl7.org/fhir/ValueSet/medication-codes` | `Example` | Code that identifies this medication |
| `http://hl7.org/fhir/StructureDefinition/MedicationRequest` | `MedicationRequest.medication[x]` | `http://hl7.org/fhir/ValueSet/medication-codes` | `Example` | Medication to be taken |
| `http://hl7.org/fhir/StructureDefinition/MedicationStatement` | `MedicationStatement.medication[x]` | `http://hl7.org/fhir/ValueSet/medication-codes` | `Example` | What medication was taken |
| `http://hl7.org/fhir/StructureDefinition/MedicinalProductDefinition` | `MedicinalProductDefinition.code` | `http://hl7.org/fhir/ValueSet/medication-codes` | `Example` | A code that this product is known by, within some formal terminology |

### Expansion Failure

Failed to expand this value set: Expansion is limited
