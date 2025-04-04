Comparison of 
Generated at Friday, April 4, 2025 2:58:44 PM

### validation-status

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | validation-status |
| Canonical URL | `http://hl7.org/fhir/ValueSet/verificationresult-validation-status` |
| Version | 4.0.1 |
| Description | Status of the validation of the target against the primary source |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `2836` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/VerificationResult` | `VerificationResult.primarySource.validationStatus` | `http://hl7.org/fhir/ValueSet/verificationresult-validation-status` | `Preferred` | successful \| failed \| unknown |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/validation-status`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/validation-status` | `failed` | Failed |
| `http://terminology.hl7.org/CodeSystem/validation-status` | `successful` | Successful |
| `http://terminology.hl7.org/CodeSystem/validation-status` | `unknown` | Unknown |
