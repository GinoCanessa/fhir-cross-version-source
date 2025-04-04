Comparison of 
Generated at Friday, April 4, 2025 2:58:44 PM

### EffectEstimateType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | EffectEstimateType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/effect-estimate-type` |
| Version | 4.0.1 |
| Description | Whether the effect estimate is an absolute effect estimate (absolute difference) or a relative effect estimate (relative difference), and the specific type of effect estimate (eg relative risk or median difference). |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2400` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/EffectEvidenceSynthesis` | `EffectEvidenceSynthesis.effectEstimate.type` | `http://hl7.org/fhir/ValueSet/effect-estimate-type` | `Extensible` | Type of efffect estimate |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/effect-estimate-type`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/effect-estimate-type` | `absolute-ARD` | absolute risk difference |
| `http://terminology.hl7.org/CodeSystem/effect-estimate-type` | `absolute-MeanDiff` | mean difference |
| `http://terminology.hl7.org/CodeSystem/effect-estimate-type` | `absolute-MedianDiff` | median difference |
| `http://terminology.hl7.org/CodeSystem/effect-estimate-type` | `absolute-SMD` | standardized mean difference |
| `http://terminology.hl7.org/CodeSystem/effect-estimate-type` | `relative-HR` | hazard ratio |
| `http://terminology.hl7.org/CodeSystem/effect-estimate-type` | `relative-OR` | odds ratio |
| `http://terminology.hl7.org/CodeSystem/effect-estimate-type` | `relative-RR` | relative risk |
