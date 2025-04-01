Comparison of 
Generated at Tuesday, April 1, 2025 1:39:06 PM

### Fluid Consistency Type Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Fluid Consistency Type Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/consistency-type` |
| Version | 1.0.2 |
| Description | FluidConsistencyType :  Codes used to represent the consistency of fluids and liquids provided to the patient. This value set includes all the children of  SNOMED CT Concepts from SCTID(US Extension): 435681000124103  Dietary liquid consistency diet (regime/therapy) and is provided as a suggestive example. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `75` |
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
