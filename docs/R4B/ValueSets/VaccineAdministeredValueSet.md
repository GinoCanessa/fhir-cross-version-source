Comparison of 
Generated at Friday, April 4, 2025 2:58:52 PM

### VaccineAdministeredValueSet

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | VaccineAdministeredValueSet |
| Canonical URL | `http://hl7.org/fhir/ValueSet/vaccine-code` |
| Version | 4.3.0 |
| Description | This identifies the vaccine substance administered - CVX codes. |
| Status | `Active` |
| Has Escape Valve Code | `` |
| Database Key | `4188` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Immunization` | `Immunization.vaccineCode` | `http://hl7.org/fhir/ValueSet/vaccine-code` | `Example` | Vaccine product administered |
| `http://hl7.org/fhir/StructureDefinition/ImmunizationRecommendation` | `ImmunizationRecommendation.recommendation.vaccineCode` | `http://hl7.org/fhir/ValueSet/vaccine-code` | `Example` | Vaccine  or vaccine group recommendation applies to |
| `http://hl7.org/fhir/StructureDefinition/ImmunizationRecommendation` | `ImmunizationRecommendation.recommendation.contraindicatedVaccineCode` | `http://hl7.org/fhir/ValueSet/vaccine-code` | `Example` | Vaccine which is contraindicated to fulfill the recommendation |

### Expansion Failure

Failed to expand this value set: Expansion is limited
