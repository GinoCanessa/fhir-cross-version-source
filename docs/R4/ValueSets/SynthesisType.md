Comparison of 
Generated at Thursday, April 3, 2025 8:18:16 AM

### SynthesisType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | SynthesisType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/synthesis-type` |
| Version | 4.0.1 |
| Description | Types of combining results from a body of evidence (eg. summary data meta-analysis). |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2794` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/EffectEvidenceSynthesis` | `EffectEvidenceSynthesis.synthesisType` | `http://hl7.org/fhir/ValueSet/synthesis-type` | `Extensible` | Type of synthesis |
| `http://hl7.org/fhir/StructureDefinition/RiskEvidenceSynthesis` | `RiskEvidenceSynthesis.synthesisType` | `http://hl7.org/fhir/ValueSet/synthesis-type` | `Extensible` | Type of synthesis |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/synthesis-type`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/synthesis-type` | `IPD-MA` | individual patient data meta-analysis |
| `http://terminology.hl7.org/CodeSystem/synthesis-type` | `classification` | classifcation of results |
| `http://terminology.hl7.org/CodeSystem/synthesis-type` | `combined-NMA` | combined direct plus indirect network meta-analysis |
| `http://terminology.hl7.org/CodeSystem/synthesis-type` | `indirect-NMA` | indirect network meta-analysis |
| `http://terminology.hl7.org/CodeSystem/synthesis-type` | `range` | range of results |
| `http://terminology.hl7.org/CodeSystem/synthesis-type` | `std-MA` | summary data meta-analysis |
