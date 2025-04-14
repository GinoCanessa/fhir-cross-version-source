Comparison of 
Generated at Monday, April 14, 2025 6:17:15 PM

### LOINC Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | LOINC Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/observation-codes` |
| Version | 1.0.2 |
| Description | This value set includes all LOINC codes |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `254` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ElementDefinition` | `ElementDefinition.code` | `http://hl7.org/fhir/ValueSet/observation-codes` | `Example` | Defining code |
| `http://hl7.org/fhir/StructureDefinition/Observation` | `Observation.code` | `http://hl7.org/fhir/ValueSet/observation-codes` | `Example` | Type of observation (code / type) |
| `http://hl7.org/fhir/StructureDefinition/Observation` | `Observation.component.code` | `http://hl7.org/fhir/ValueSet/observation-codes` | `Example` | Type of component observation (code / type) |

### Expansion Failure

Failed to expand this value set: Error expanding http://hl7.org/fhir/ValueSet/observation-codes|1.0.2: Operation expand failed: creating the required expansion failed with message "The ValueSet expander cannot find codesystem 'http://loinc.org', so the expansion cannot be completed.".
