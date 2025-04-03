Comparison of 
Generated at Thursday, April 3, 2025 8:18:10 AM

### SNOMED CT Route Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | SNOMED CT Route Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/route-codes` |
| Version | 3.0.2 |
| Description | This value set includes all Route codes from SNOMED CT - provided as an exemplar. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `1459` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Dosage` | `Dosage.route` | `http://hl7.org/fhir/ValueSet/route-codes` | `Example` | How drug should enter body |
| `http://hl7.org/fhir/StructureDefinition/AllergyIntolerance` | `AllergyIntolerance.reaction.exposureRoute` | `http://hl7.org/fhir/ValueSet/route-codes` | `Example` | How the subject was exposed to the substance |
| `http://hl7.org/fhir/StructureDefinition/MedicationAdministration` | `MedicationAdministration.dosage.route` | `http://hl7.org/fhir/ValueSet/route-codes` | `Example` | Path of substance into body |

### Expansion Failure

Failed to expand this value set: Expansion is limited
