Comparison of 
Generated at Tuesday, April 1, 2025 1:39:33 PM

### RiskProbability

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | RiskProbability |
| Canonical URL | `http://hl7.org/fhir/ValueSet/risk-probability` |
| Version | 5.0.0 |
| Description | Codes representing the likelihood of a particular outcome in a risk assessment. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4879` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/RiskAssessment` | `RiskAssessment.prediction.qualitativeRisk` | `http://hl7.org/fhir/ValueSet/risk-probability` | `Example` | Likelihood of specified outcome as a qualitative value |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/risk-probability`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/risk-probability` | `certain` | Certain |
| `http://terminology.hl7.org/CodeSystem/risk-probability` | `high` | High likelihood |
| `http://terminology.hl7.org/CodeSystem/risk-probability` | `low` | Low likelihood |
| `http://terminology.hl7.org/CodeSystem/risk-probability` | `moderate` | Moderate likelihood |
| `http://terminology.hl7.org/CodeSystem/risk-probability` | `negligible` | Negligible likelihood |
