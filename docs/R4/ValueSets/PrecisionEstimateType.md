Comparison of 
Generated at Monday, April 14, 2025 6:17:27 PM

### PrecisionEstimateType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | PrecisionEstimateType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/precision-estimate-type` |
| Version | 4.0.1 |
| Description | Method of reporting variability of estimates, such as confidence intervals, interquartile range or standard deviation. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2648` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/EffectEvidenceSynthesis` | `EffectEvidenceSynthesis.effectEstimate.precisionEstimate.type` | `http://hl7.org/fhir/ValueSet/precision-estimate-type` | `Extensible` | Type of precision estimate |
| `http://hl7.org/fhir/StructureDefinition/RiskEvidenceSynthesis` | `RiskEvidenceSynthesis.riskEstimate.precisionEstimate.type` | `http://hl7.org/fhir/ValueSet/precision-estimate-type` | `Extensible` | Type of precision estimate |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/precision-estimate-type`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/precision-estimate-type` | `CI` | confidence interval |
| `http://terminology.hl7.org/CodeSystem/precision-estimate-type` | `IQR` | interquartile range |
| `http://terminology.hl7.org/CodeSystem/precision-estimate-type` | `SD` | standard deviation |
| `http://terminology.hl7.org/CodeSystem/precision-estimate-type` | `SE` | standard error |
