Comparison of 
Generated at Friday, April 4, 2025 2:58:58 PM

### IngredientManufacturerRole

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | IngredientManufacturerRole |
| Canonical URL | `http://hl7.org/fhir/ValueSet/ingredient-manufacturer-role` |
| Version | 5.0.0 |
| Description | The way in which this manufacturer is associated with the ingredient. For example whether it is a possible one (others allowed), or an exclusive authorized one for this ingredient. Note that this is not the manufacturing process role. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4635` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Ingredient` | `Ingredient.manufacturer.role` | `http://hl7.org/fhir/ValueSet/ingredient-manufacturer-role\|5.0.0` | `Required` | allowed \| possible \| actual |

### Referenced Systems

* `http://hl7.org/fhir/ingredient-manufacturer-role`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | | | [IngredientManufacturerRole](/docs/R4B/ValueSets/IngredientManufacturerRole.md)<br/> `http://hl7.org/fhir/ValueSet/ingredient-manufacturer-role\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `905`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1166`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [IngredientManufacturerRole](/docs/R5/ValueSets/IngredientManufacturerRole.md)<br/> `http://hl7.org/fhir/ValueSet/ingredient-manufacturer-role\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set IngredientManufacturerRole from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | *No Map* | Relationship | *No Map* | Relationship | [R4B IngredientManufacturerRole](/docs/R4B/ValueSets/IngredientManufacturerRole.md)| Relationship | R5 IngredientManufacturerRole
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R5** System: `http://hl7.org/fhir/ingredient-manufacturer-role`
| | | | | | | `allowed`| _Equivalent_ <br/>(8719/11028)| **`allowed`**
| | | | | | | `possible`| _Equivalent_ <br/>(8720/11029)| **`possible`**
| | | | | | | `actual`| _Equivalent_ <br/>(8718/11027)| **`actual`**
| | | | | | | *3 of 3 codes used* | | *3 of 3 codes used* 

