Comparison of 
Generated at Thursday, April 3, 2025 8:18:31 AM

### ProcessPriorityCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ProcessPriorityCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/process-priority` |
| Version | 5.0.0 |
| Description | This value set includes the financial processing priority codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4805` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.priority` | `http://hl7.org/fhir/ValueSet/process-priority` | `Example` | Desired processing urgency |
| `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityRequest` | `CoverageEligibilityRequest.priority` | `http://hl7.org/fhir/ValueSet/process-priority` | `Example` | Desired processing priority |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.priority` | `http://hl7.org/fhir/ValueSet/process-priority` | `Example` | Desired processing urgency |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/processpriority`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/processpriority` | `deferred` | Deferred |
| `http://terminology.hl7.org/CodeSystem/processpriority` | `normal` | Normal |
| `http://terminology.hl7.org/CodeSystem/processpriority` | `stat` | Immediate |
