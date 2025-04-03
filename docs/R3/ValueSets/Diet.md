Comparison of 
Generated at Thursday, April 3, 2025 8:18:09 AM

### Diet

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Diet |
| Canonical URL | `http://hl7.org/fhir/ValueSet/encounter-diet` |
| Version | 3.0.2 |
| Description | This value set defines a set of codes that can be used to indicate dietary preferences or restrictions a patient may have. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1205` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.hospitalization.dietPreference` | `http://hl7.org/fhir/ValueSet/encounter-diet` | `Example` | Diet preferences reported by the patient |
| `http://hl7.org/fhir/StructureDefinition/NutritionOrder` | `NutritionOrder.foodPreferenceModifier` | `http://hl7.org/fhir/ValueSet/encounter-diet` | `Example` | Order-specific modifier about the type of food that should be given |

### Referenced Systems

* `http://hl7.org/fhir/diet`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/diet` | `dairy-free` | Dairy Free |
| `http://hl7.org/fhir/diet` | `gluten-free` | Gluten Free |
| `http://hl7.org/fhir/diet` | `halal` | Halal |
| `http://hl7.org/fhir/diet` | `kosher` | Kosher |
| `http://hl7.org/fhir/diet` | `nut-free` | Nut Free |
| `http://hl7.org/fhir/diet` | `vegan` | Vegan |
| `http://hl7.org/fhir/diet` | `vegetarian` | Vegetarian |
