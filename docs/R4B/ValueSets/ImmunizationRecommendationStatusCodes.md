Comparison of 
Generated at Monday, April 14, 2025 6:17:35 PM

### ImmunizationRecommendationStatusCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ImmunizationRecommendationStatusCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/immunization-recommendation-status` |
| Version | 4.3.0 |
| Description | The value set to instantiate this attribute should be drawn from a terminologically robust code system that consists of or contains concepts to support describing the status of the patient towards perceived immunity against a vaccine preventable disease. This value set is provided as a suggestive example. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3828` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ImmunizationRecommendation` | `ImmunizationRecommendation.recommendation.forecastStatus` | `http://hl7.org/fhir/ValueSet/immunization-recommendation-status` | `Example` | Vaccine recommendation status |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/immunization-recommendation-status`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/immunization-recommendation-status` | `complete` | Complete |
| `http://terminology.hl7.org/CodeSystem/immunization-recommendation-status` | `contraindicated` | Contraindicated |
| `http://terminology.hl7.org/CodeSystem/immunization-recommendation-status` | `due` | Due |
| `http://terminology.hl7.org/CodeSystem/immunization-recommendation-status` | `immune` | Immune |
| `http://terminology.hl7.org/CodeSystem/immunization-recommendation-status` | `overdue` | Overdue |
