Comparison of 
Generated at Thursday, April 3, 2025 8:18:09 AM

### Immunization Recommendation Status Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Immunization Recommendation Status Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/immunization-recommendation-status` |
| Version | 3.0.2 |
| Description | The value set to instantiate this attribute should be drawn from a terminologically robust code system that consists of or contains concepts to support describing the status of the patient towards perceived immunity against a vaccine preventable disease. This value set is provided as a suggestive example. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1276` |
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
