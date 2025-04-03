Comparison of 
Generated at Thursday, April 3, 2025 8:18:31 AM

### NutrientModifierCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | NutrientModifierCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/nutrient-code` |
| Version | 5.0.0 |
| Description | NutrientModifier :  Codes for types of nutrients that are being modified such as carbohydrate or sodium.  This value set includes codes from [SNOMED CT](http://snomed.info/sct) where concept is-a 226355009 (Nutrients(substance)), and the concepts for Sodium, Potassium and Fluid. This is provided as a suggestive example. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `4753` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/NutritionIntake` | `NutritionIntake.ingredientLabel.nutrient` | `http://hl7.org/fhir/ValueSet/nutrient-code` | `Example` | Total nutrient consumed |
| `http://hl7.org/fhir/StructureDefinition/NutritionOrder` | `NutritionOrder.oralDiet.nutrient.modifier` | `http://hl7.org/fhir/ValueSet/nutrient-code` | `Example` | Type of nutrient that is being modified |

### Expansion Failure

Failed to expand this value set: Expansion is limited
