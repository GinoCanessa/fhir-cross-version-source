Comparison of 
Generated at Friday, April 4, 2025 2:58:59 PM

### SubstanceCode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | SubstanceCode |
| Canonical URL | `http://hl7.org/fhir/ValueSet/substance-code` |
| Version | 5.0.0 |
| Description | This value set contains concept codes for specific substances. It includes codes from [SNOMED](http://snomed.info/sct) where concept is-a 105590001 (Substance (substance)) |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `4931` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AllergyIntolerance` | `AllergyIntolerance.reaction.substance` | `http://hl7.org/fhir/ValueSet/substance-code` | `Example` | Specific substance or pharmaceutical product considered to be responsible for event |
| `http://hl7.org/fhir/StructureDefinition/Substance` | `Substance.code` | `http://hl7.org/fhir/ValueSet/substance-code` | `Example` | What substance this is |
| `http://hl7.org/fhir/StructureDefinition/Substance` | `Substance.ingredient.substance[x]` | `http://hl7.org/fhir/ValueSet/substance-code` | `Example` | A component of the substance |

### Expansion Failure

Failed to expand this value set: Expansion is limited
