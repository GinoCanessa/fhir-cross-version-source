Comparison of 
Generated at Monday, April 14, 2025 6:17:15 PM

### SNOMED CT Anatomical Structure for Administration Site Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | SNOMED CT Anatomical Structure for Administration Site Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/approach-site-codes` |
| Version | 1.0.2 |
| Description | This value set includes Anatomical Structure codes from SNOMED CT - provided as an exemplar. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `23` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/MedicationAdministration` | `MedicationAdministration.dosage.site[x]` | `http://hl7.org/fhir/ValueSet/approach-site-codes` | `Example` | Body site administered to |
| `http://hl7.org/fhir/StructureDefinition/MedicationDispense` | `MedicationDispense.dosageInstruction.site[x]` | `http://hl7.org/fhir/ValueSet/approach-site-codes` | `Example` | Body site to administer to |
| `http://hl7.org/fhir/StructureDefinition/MedicationOrder` | `MedicationOrder.dosageInstruction.site[x]` | `http://hl7.org/fhir/ValueSet/approach-site-codes` | `Example` | Body site to administer to |
| `http://hl7.org/fhir/StructureDefinition/MedicationStatement` | `MedicationStatement.dosage.site[x]` | `http://hl7.org/fhir/ValueSet/approach-site-codes` | `Example` | Where (on body) medication is/was administered |

### Expansion Failure

Failed to expand this value set: Error expanding http://hl7.org/fhir/ValueSet/approach-site-codes|1.0.2: Operation expand failed: creating the required expansion failed with message "Cannot find codesystem 'http://snomed.info/sct', so the defined filter(s) cannot be applied.".
