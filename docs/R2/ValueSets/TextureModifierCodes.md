Comparison of 
Generated at Thursday, April 3, 2025 8:18:05 AM

### Texture Modifier Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Texture Modifier Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/texture-code` |
| Version | 1.0.2 |
| Description | TextureModifier: Codes for food consistency types or texture modifications to apply to foods. This value set is composed of SNOMED CT (US Extension and Core) Concepts from SCTID 229961002 Food consistency types (substance) hierarchy and is provided as a suggestive example. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `395` |
| Database Concept Count | `14` |
| Database Active Concept Count | `14` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/NutritionOrder` | `NutritionOrder.oralDiet.texture.modifier` | `http://hl7.org/fhir/ValueSet/texture-code` | `Example` | Code to indicate how to alter the texture of the foods, e.g. pureed |

### Referenced Systems

* `http://snomed.info/sct`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://snomed.info/sct` | `228049004` | Chopped food |
| `http://snomed.info/sct` | `228053002` | Cut-up food |
| `http://snomed.info/sct` | `228055009` | Liquidized food |
| `http://snomed.info/sct` | `228056005` | Lumpy food |
| `http://snomed.info/sct` | `228057001` | Semi-solid food |
| `http://snomed.info/sct` | `228058006` | Single texture food |
| `http://snomed.info/sct` | `228059003` | Soft food |
| `http://snomed.info/sct` | `228060008` | Solid food |
| `http://snomed.info/sct` | `439091000124107` | Easy to chew food |
| `http://snomed.info/sct` | `441751000124100` | Mashed food |
| `http://snomed.info/sct` | `441761000124103` | Minced food |
| `http://snomed.info/sct` | `441771000124105` | Moist food |
| `http://snomed.info/sct` | `441791000124106` | Strained food |
| `http://snomed.info/sct` | `441881000124103` | Ground food |
