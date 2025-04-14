Comparison of 
Generated at Monday, April 14, 2025 6:17:14 PM

### Substance Code

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Substance Code |
| Canonical URL | `http://hl7.org/fhir/ValueSet/substance-code` |
| Version | 1.0.2 |
| Description | This value set contains concept codes for specific substances. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `378` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AllergyIntolerance` | `AllergyIntolerance.reaction.substance` | `http://hl7.org/fhir/ValueSet/substance-code` | `Example` | Specific substance considered to be responsible for event |
| `http://hl7.org/fhir/StructureDefinition/Substance` | `Substance.code` | `http://hl7.org/fhir/ValueSet/substance-code` | `Example` | What substance this is |

### Expansion Failure

Failed to expand this value set: Error expanding http://hl7.org/fhir/ValueSet/substance-code|1.0.2: Operation expand failed: creating the required expansion failed with message "Cannot find codesystem 'http://snomed.info/sct', so the defined filter(s) cannot be applied.".
