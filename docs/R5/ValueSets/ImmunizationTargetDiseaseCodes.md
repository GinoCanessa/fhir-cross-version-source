Comparison of 
Generated at Thursday, April 3, 2025 8:18:31 AM

### ImmunizationTargetDiseaseCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ImmunizationTargetDiseaseCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/immunization-target-disease` |
| Version | 5.0.0 |
| Description | The value set to instantiate this attribute should be drawn from a terminologically robust code system that consists of or contains concepts to support describing the disease that the dose is being administered against. This value set is provided as a suggestive example and includes SNOMED CT concepts from the 64572001 (Disease) hierarchy. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `4631` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Immunization` | `Immunization.protocolApplied.targetDisease` | `http://hl7.org/fhir/ValueSet/immunization-target-disease` | `Example` | Vaccine preventatable disease being targeted |
| `http://hl7.org/fhir/StructureDefinition/ImmunizationEvaluation` | `ImmunizationEvaluation.targetDisease` | `http://hl7.org/fhir/ValueSet/immunization-target-disease` | `Example` | The vaccine preventable disease schedule being evaluated |
| `http://hl7.org/fhir/StructureDefinition/ImmunizationRecommendation` | `ImmunizationRecommendation.recommendation.targetDisease` | `http://hl7.org/fhir/ValueSet/immunization-target-disease` | `Example` | Disease to be immunized against |

### Expansion Failure

Failed to expand this value set: Expansion is limited
