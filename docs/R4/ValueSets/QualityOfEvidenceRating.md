Comparison of 
Generated at Thursday, April 3, 2025 8:18:17 AM

### QualityOfEvidenceRating

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | QualityOfEvidenceRating |
| Canonical URL | `http://hl7.org/fhir/ValueSet/evidence-quality` |
| Version | 4.0.1 |
| Description | A rating system that describes the quality of evidence such as the GRADE, DynaMed, or Oxford CEBM systems. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2427` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/EffectEvidenceSynthesis` | `EffectEvidenceSynthesis.certainty.rating` | `http://hl7.org/fhir/ValueSet/evidence-quality` | `Extensible` | Certainty rating |
| `http://hl7.org/fhir/StructureDefinition/RiskEvidenceSynthesis` | `RiskEvidenceSynthesis.certainty.rating` | `http://hl7.org/fhir/ValueSet/evidence-quality` | `Extensible` | Certainty rating |
| `http://hl7.org/fhir/StructureDefinition/cqf-qualityOfEvidence` | `Extension.value[x]` | `http://hl7.org/fhir/ValueSet/evidence-quality` | `Example` | Value of extension |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/evidence-quality`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/evidence-quality` | `high` | High quality |
| `http://terminology.hl7.org/CodeSystem/evidence-quality` | `low` | Low quality |
| `http://terminology.hl7.org/CodeSystem/evidence-quality` | `moderate` | Moderate quality |
| `http://terminology.hl7.org/CodeSystem/evidence-quality` | `very-low` | Very low quality |
