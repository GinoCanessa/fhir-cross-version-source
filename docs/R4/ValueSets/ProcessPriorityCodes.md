Comparison of 
Generated at Friday, April 4, 2025 2:58:44 PM

### ProcessPriorityCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ProcessPriorityCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/process-priority` |
| Version | 4.0.1 |
| Description | This value set includes the financial processing priority codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2658` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.priority` | `http://hl7.org/fhir/ValueSet/process-priority` | `Example` | Desired processing ugency |
| `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityRequest` | `CoverageEligibilityRequest.priority` | `http://hl7.org/fhir/ValueSet/process-priority` | `Example` | Desired processing priority |

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
