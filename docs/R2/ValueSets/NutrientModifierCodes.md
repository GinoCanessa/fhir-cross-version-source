Comparison of 
Generated at Tuesday, April 1, 2025 1:39:07 PM

### Nutrient Modifier Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Nutrient Modifier Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/nutrient-code` |
| Version | 1.0.2 |
| Description | NutrientModifier :  Codes for types of nutrient that is being modified such as carbohydrate or sodium.  This value set includes all the children of SNOMED CT Concepts from SCTID 226355009 Nutrients (substance), Sodium, Potassium and Fluid and is provided as a suggestive example. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `248` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/NutritionOrder` | `NutritionOrder.oralDiet.nutrient.modifier` | `http://hl7.org/fhir/ValueSet/nutrient-code` | `Example` | Type of nutrient that is being modified |

### Expansion Failure

Failed to expand this value set: Error expanding http://hl7.org/fhir/ValueSet/nutrient-code|1.0.2: Operation expand failed: creating the required expansion failed with message "Cannot find codesystem 'http://snomed.info/sct', so the defined filter(s) cannot be applied.".
