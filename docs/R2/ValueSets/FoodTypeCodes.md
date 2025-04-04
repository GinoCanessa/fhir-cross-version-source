Comparison of 
Generated at Friday, April 4, 2025 2:58:32 PM

### Food Type Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Food Type Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/food-type` |
| Version | 1.0.2 |
| Description | FoodType : This value set represents SNOMED CT codes for types of foods. This value set includes all the children of SNOMED CT Concepts from SCTID 255620007 Foods (substance) and is provided as a suggestive example. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `172` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/NutritionOrder` | `NutritionOrder.excludeFoodModifier` | `http://hl7.org/fhir/ValueSet/food-type` | `Example` | Order-specific modifier about the type of food that should not be given |

### Expansion Failure

Failed to expand this value set: Error expanding http://hl7.org/fhir/ValueSet/food-type|1.0.2: Operation expand failed: creating the required expansion failed with message "Cannot find codesystem 'http://snomed.info/sct', so the defined filter(s) cannot be applied.".
