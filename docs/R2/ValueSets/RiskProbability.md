Comparison of 
Generated at Thursday, April 3, 2025 8:18:05 AM

### Risk Probability

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Risk Probability |
| Canonical URL | `http://hl7.org/fhir/ValueSet/risk-probability` |
| Version | 1.0.2 |
| Description | Codes representing the likelihood of a particular outcome in a risk assessment. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `349` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/RiskAssessment` | `RiskAssessment.prediction.probability[x]` | `http://hl7.org/fhir/ValueSet/risk-probability` | `Example` | Likelihood of specified outcome |

### Referenced Systems

* `http://hl7.org/fhir/risk-probability`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/risk-probability` | `certain` | Certain |
| `http://hl7.org/fhir/risk-probability` | `high` | High likelihood |
| `http://hl7.org/fhir/risk-probability` | `low` | Low likelihood |
| `http://hl7.org/fhir/risk-probability` | `moderate` | Moderate likelihood |
| `http://hl7.org/fhir/risk-probability` | `negligible` | Negligible likelihood |
