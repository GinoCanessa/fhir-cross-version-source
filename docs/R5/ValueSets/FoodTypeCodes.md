Comparison of 
Generated at Monday, April 14, 2025 6:17:42 PM

### FoodTypeCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | FoodTypeCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/food-type` |
| Version | 5.0.0 |
| Description | This value set represents codes for types of foods and is provided as a suggestive example. It include codes from [SNOMED CT](http://snomed.info/sct) where concept is-a 255620007 (Foods (substance)). |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `4578` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/NutritionIntake` | `NutritionIntake.consumedItem.nutritionProduct` | `http://hl7.org/fhir/ValueSet/food-type` | `Example` | Code that identifies the food or fluid product that was consumed |
| `http://hl7.org/fhir/StructureDefinition/NutritionOrder` | `NutritionOrder.excludeFoodModifier` | `http://hl7.org/fhir/ValueSet/food-type` | `Example` | Order-specific modifier about the type of food that should not be given |

### Expansion Failure

Failed to expand this value set: Expansion is limited
