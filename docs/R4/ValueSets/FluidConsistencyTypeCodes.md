Comparison of 
Generated at Monday, April 14, 2025 6:17:27 PM

### FluidConsistencyTypeCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | FluidConsistencyTypeCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/consistency-type` |
| Version | 4.0.1 |
| Description | FluidConsistencyType :  Codes used to represent the consistency of fluids and liquids provided to the patient. This value set includes concepts from [SNOMED CT](http://snomed.info/sct)(US Extension) where concept is a 435681000124103  (Dietary liquid consistency diet (regime/therapy)). It is provided as a suggestive example. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2314` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/NutritionOrder` | `NutritionOrder.oralDiet.fluidConsistencyType` | `http://hl7.org/fhir/ValueSet/consistency-type` | `Example` | The required consistency of fluids and liquids provided to the patient |

### Referenced Systems

* `http://snomed.info/sct`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://snomed.info/sct` | `439021000124105` | nectar thick liquid |
| `http://snomed.info/sct` | `439031000124108` | honey thick liquid |
| `http://snomed.info/sct` | `439041000124103` | spoon thick liquid |
| `http://snomed.info/sct` | `439081000124109` | thin liquid |
