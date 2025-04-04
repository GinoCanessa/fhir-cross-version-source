Comparison of 
Generated at Friday, April 4, 2025 2:58:44 PM

### failure-action

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | failure-action |
| Canonical URL | `http://hl7.org/fhir/ValueSet/verificationresult-failure-action` |
| Version | 4.0.1 |
| Description | The result if validation fails |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2830` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/VerificationResult` | `VerificationResult.failureAction` | `http://hl7.org/fhir/ValueSet/verificationresult-failure-action` | `Preferred` | fatal \| warn \| rec-only \| none |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/failure-action`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/failure-action` | `fatal` | Fatal |
| `http://terminology.hl7.org/CodeSystem/failure-action` | `none` | None |
| `http://terminology.hl7.org/CodeSystem/failure-action` | `rec-only` | Record only |
| `http://terminology.hl7.org/CodeSystem/failure-action` | `warn` | Warning |
