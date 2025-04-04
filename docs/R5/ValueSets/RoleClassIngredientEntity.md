Comparison of 
Generated at Friday, April 4, 2025 2:58:59 PM

### RoleClassIngredientEntity

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | RoleClassIngredientEntity |
| Canonical URL | `http://terminology.hl7.org/ValueSet/v3-RoleClassIngredientEntity` |
| Version | 2.0.0 |
| Description | Relates a component (player) to a mixture (scoper). E.g., Glucose and Water are ingredients of D5W, latex may be an ingredient in a tracheal tube. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `5057` |
| Database Concept Count | `15` |
| Database Active Concept Count | `15` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/MedicationKnowledge` | `MedicationKnowledge.definitional.ingredient.type` | `http://terminology.hl7.org/ValueSet/v3-RoleClassIngredientEntity` | `Example` | A code that defines the type of ingredient, active, base, etc |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-RoleClass`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `ACTI` | active ingredient |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `ACTIB` | active ingredient - basis of strength |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `ACTIM` | active ingredient - moiety is basis of strength |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `ACTIR` | active ingredient - reference substance is basis of strength |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `ADJV` | adjuvant |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `ADTV` | additive |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `BASE` | base |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `CNTM` | contaminant ingredient |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `COLR` | color additive |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `FLVR` | flavor additive |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `IACT` | inactive ingredient |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `INGR` | ingredient |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `MECH` | mechanical ingredient |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `PRSV` | preservative |
| `http://terminology.hl7.org/CodeSystem/v3-RoleClass` | `STBL` | stabilizer |
