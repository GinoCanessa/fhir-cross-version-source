Comparison of 
Generated at Tuesday, April 1, 2025 1:39:10 PM

### Substance Code

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Substance Code |
| Canonical URL | `http://hl7.org/fhir/ValueSet/substance-code` |
| Version | 3.0.2 |
| Description | This value set contains concept codes for specific substances. It includes codes from [SNOMED](http://snomed.info/sct) where concept is-a 105590001 (Substance (substance)) adn where concept is-a 373873005 (Pharmaceutical / biologic product (product)) |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `1496` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AllergyIntolerance` | `AllergyIntolerance.reaction.substance` | `http://hl7.org/fhir/ValueSet/substance-code` | `Example` | Specific substance or pharmaceutical product considered to be responsible for event |
| `http://hl7.org/fhir/StructureDefinition/Substance` | `Substance.code` | `http://hl7.org/fhir/ValueSet/substance-code` | `Example` | What substance this is |
| `http://hl7.org/fhir/StructureDefinition/Substance` | `Substance.ingredient.substance[x]` | `http://hl7.org/fhir/ValueSet/substance-code` | `Example` | A component of the substance |
| `http://hl7.org/fhir/StructureDefinition/allergyintolerance-substanceExposureRisk` | `Extension.extension.valueCodeableConcept` | `http://hl7.org/fhir/ValueSet/substance-code` | `Example` | Value of extension |

### Expansion Failure

Failed to expand this value set: Expansion is limited
