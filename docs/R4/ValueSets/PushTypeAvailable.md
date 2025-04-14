Comparison of 
Generated at Monday, April 14, 2025 6:17:27 PM

### push-type-available

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | push-type-available |
| Canonical URL | `http://hl7.org/fhir/ValueSet/verificationresult-push-type-available` |
| Version | 4.0.1 |
| Description | Type of alerts/updates the primary source can send |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2833` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/VerificationResult` | `VerificationResult.primarySource.pushTypeAvailable` | `http://hl7.org/fhir/ValueSet/verificationresult-push-type-available` | `Preferred` | specific \| any \| source |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/push-type-available`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/push-type-available` | `any` | Any changes |
| `http://terminology.hl7.org/CodeSystem/push-type-available` | `source` | As defined by source |
| `http://terminology.hl7.org/CodeSystem/push-type-available` | `specific` | Specific requested changes |
