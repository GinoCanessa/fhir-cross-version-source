Comparison of 
Generated at Monday, April 14, 2025 6:17:14 PM

### Immunization Recommendation Status Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Immunization Recommendation Status Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/immunization-recommendation-status` |
| Version | 1.0.2 |
| Description | The value set to instantiate this attribute should be drawn from a terminologically robust code system that consists of or contains concepts to support the medication process, in particular the process and reasons for dispensing. This value set is provided as a suggestive example. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `195` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ImmunizationRecommendation` | `ImmunizationRecommendation.recommendation.forecastStatus` | `http://hl7.org/fhir/ValueSet/immunization-recommendation-status` | `Example` | Vaccine administration status |

### Referenced Systems

* `http://hl7.org/fhir/immunization-recommendation-status`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/immunization-recommendation-status` | `due` | Due |
| `http://hl7.org/fhir/immunization-recommendation-status` | `overdue` | Overdue |
