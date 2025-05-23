Comparison of 
Generated at Monday, April 14, 2025 6:17:14 PM

### SNOMED CT Medication Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | SNOMED CT Medication Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/medication-codes` |
| Version | 1.0.2 |
| Description | This value set includes all Medication codes from SNOMED CT - provided as an exemplar. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `221` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/CarePlan` | `CarePlan.activity.detail.product[x]` | `http://hl7.org/fhir/ValueSet/medication-codes` | `Example` | What is to be administered/supplied |
| `http://hl7.org/fhir/StructureDefinition/Medication` | `Medication.code` | `http://hl7.org/fhir/ValueSet/medication-codes` | `Example` | Codes that identify this medication |

### Expansion Failure

Failed to expand this value set: Error expanding http://hl7.org/fhir/ValueSet/medication-codes|1.0.2: Operation expand failed: creating the required expansion failed with message "Cannot find codesystem 'http://snomed.info/sct', so the defined filter(s) cannot be applied.".
