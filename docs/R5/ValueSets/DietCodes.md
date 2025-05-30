Comparison of 
Generated at Monday, April 14, 2025 6:17:43 PM

### DietCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | DietCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/diet-type` |
| Version | 5.0.0 |
| Description | Codes that can be used to indicate the type of food being ordered for a patient. This value set is provided as a suggestive example. It includes codes from [SNOMED CT](http://snomed.info/sct) where concept is-a 182922004 (Dietary regime (regime/therapy)) |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `4502` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/NutritionIntake` | `NutritionIntake.code` | `http://hl7.org/fhir/ValueSet/diet-type` | `Example` | Code representing an overall type of nutrition intake |
| `http://hl7.org/fhir/StructureDefinition/NutritionOrder` | `NutritionOrder.oralDiet.type` | `http://hl7.org/fhir/ValueSet/diet-type` | `Example` | Type of oral diet or diet restrictions that describe what can be consumed orally |

### Expansion Failure

Failed to expand this value set: Expansion is limited
