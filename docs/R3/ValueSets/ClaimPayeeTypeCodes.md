Comparison of 
Generated at Monday, April 14, 2025 6:17:20 PM

### Claim Payee Type Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Claim Payee Type Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/payeetype` |
| Version | 3.0.2 |
| Description | This value set includes sample Payee Type codes. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `1387` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.payee.type` | `http://hl7.org/fhir/ValueSet/payeetype` | `Example` | Type of party: Subscriber, Provider, other |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.payeeType` | `http://hl7.org/fhir/ValueSet/payeetype` | `Example` | Party to be paid any benefits payable |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.payee.type` | `http://hl7.org/fhir/ValueSet/payeetype` | `Example` | Type of party: Subscriber, Provider, other |

### Referenced Systems

* `http://hl7.org/fhir/payeetype`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/payeetype` | `other` | Provider |
| `http://hl7.org/fhir/payeetype` | `provider` | Provider |
| `http://hl7.org/fhir/payeetype` | `subscriber` | Subscriber |
