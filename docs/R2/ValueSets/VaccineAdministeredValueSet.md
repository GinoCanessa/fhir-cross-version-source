Comparison of 
Generated at Friday, April 4, 2025 2:58:32 PM

### Vaccine Administered Value Set

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Vaccine Administered Value Set |
| Canonical URL | `http://hl7.org/fhir/ValueSet/vaccine-code` |
| Version | 1.0.2 |
| Description | This identifies the vaccine substance administered - CVX codes. |
| Status | `Active` |
| Has Escape Valve Code | `` |
| Database Key | `1009` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Immunization` | `Immunization.vaccineCode` | `http://hl7.org/fhir/ValueSet/vaccine-code` | `Example` | Vaccine product administered |
| `http://hl7.org/fhir/StructureDefinition/ImmunizationRecommendation` | `ImmunizationRecommendation.recommendation.vaccineCode` | `http://hl7.org/fhir/ValueSet/vaccine-code` | `Example` | Vaccine recommendation applies to |

### Expansion Failure

Failed to expand this value set: Error expanding http://hl7.org/fhir/ValueSet/vaccine-code|1.0.2: Operation expand failed: creating the required expansion failed with message "The ValueSet expander cannot find codesystem 'http://hl7.org/fhir/sid/cvx', so the expansion cannot be completed.".
