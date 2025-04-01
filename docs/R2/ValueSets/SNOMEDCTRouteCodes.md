Comparison of 
Generated at Tuesday, April 1, 2025 1:39:06 PM

### SNOMED CT Route Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | SNOMED CT Route Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/route-codes` |
| Version | 1.0.2 |
| Description | This value set includes all Route codes from SNOMED CT - provided as an exemplar. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `350` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AllergyIntolerance` | `AllergyIntolerance.reaction.exposureRoute` | `http://hl7.org/fhir/ValueSet/route-codes` | `Example` | How the subject was exposed to the substance |
| `http://hl7.org/fhir/StructureDefinition/MedicationAdministration` | `MedicationAdministration.dosage.route` | `http://hl7.org/fhir/ValueSet/route-codes` | `Example` | Path of substance into body |
| `http://hl7.org/fhir/StructureDefinition/MedicationDispense` | `MedicationDispense.dosageInstruction.route` | `http://hl7.org/fhir/ValueSet/route-codes` | `Example` | How drug should enter body |
| `http://hl7.org/fhir/StructureDefinition/MedicationOrder` | `MedicationOrder.dosageInstruction.route` | `http://hl7.org/fhir/ValueSet/route-codes` | `Example` | How drug should enter body |
| `http://hl7.org/fhir/StructureDefinition/MedicationStatement` | `MedicationStatement.dosage.route` | `http://hl7.org/fhir/ValueSet/route-codes` | `Example` | How the medication entered the body |

### Expansion Failure

Failed to expand this value set: Error expanding http://hl7.org/fhir/ValueSet/route-codes|1.0.2: Operation expand failed: creating the required expansion failed with message "Cannot find codesystem 'http://snomed.info/sct', so the defined filter(s) cannot be applied.".
