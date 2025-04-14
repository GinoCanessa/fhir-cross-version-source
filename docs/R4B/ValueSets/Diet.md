Comparison of 
Generated at Monday, April 14, 2025 6:17:35 PM

### Diet

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | Diet |
| Canonical URL | `http://hl7.org/fhir/ValueSet/encounter-diet` |
| Version | 4.3.0 |
| Description | This value set defines a set of codes that can be used to indicate dietary preferences or restrictions a patient may have. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3733` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.hospitalization.dietPreference` | `http://hl7.org/fhir/ValueSet/encounter-diet` | `Example` | Diet preferences reported by the patient |
| `http://hl7.org/fhir/StructureDefinition/NutritionOrder` | `NutritionOrder.foodPreferenceModifier` | `http://hl7.org/fhir/ValueSet/encounter-diet` | `Example` | Order-specific modifier about the type of food that should be given |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/diet`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/diet` | `dairy-free` | Dairy Free |
| `http://terminology.hl7.org/CodeSystem/diet` | `gluten-free` | Gluten Free |
| `http://terminology.hl7.org/CodeSystem/diet` | `halal` | Halal |
| `http://terminology.hl7.org/CodeSystem/diet` | `kosher` | Kosher |
| `http://terminology.hl7.org/CodeSystem/diet` | `nut-free` | Nut Free |
| `http://terminology.hl7.org/CodeSystem/diet` | `vegan` | Vegan |
| `http://terminology.hl7.org/CodeSystem/diet` | `vegetarian` | Vegetarian |
