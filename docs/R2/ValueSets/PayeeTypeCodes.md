Comparison of 
Generated at Thursday, April 3, 2025 8:18:05 AM

### Payee Type Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Payee Type Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/payeetype` |
| Version | 1.0.2 |
| Description | This value set includes sample Payee Type codes. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `274` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.payee.type` | `http://hl7.org/fhir/ValueSet/payeetype` | `Example` | Party to be paid any benefits payable |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.payeeType` | `http://hl7.org/fhir/ValueSet/payeetype` | `Example` | Party to be paid any benefits payable |

### Referenced Systems

* `http://hl7.org/fhir/payeetype`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/payeetype` | `other` |  |
| `http://hl7.org/fhir/payeetype` | `provider` |  |
| `http://hl7.org/fhir/payeetype` | `subscriber` |  |
