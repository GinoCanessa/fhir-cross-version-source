Comparison of 
Generated at Friday, April 4, 2025 2:58:51 PM

### Claim Payee Type Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | Claim Payee Type Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/payeetype` |
| Version | 4.3.0 |
| Description | This value set includes sample Payee Type codes. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `3982` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.payee.type` | `http://hl7.org/fhir/ValueSet/payeetype` | `Example` | Category of recipient |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.payeeType` | `http://hl7.org/fhir/ValueSet/payeetype` | `Example` | Party to be paid any benefits payable |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.payee.type` | `http://hl7.org/fhir/ValueSet/payeetype` | `Example` | Category of recipient |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/payeetype`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/payeetype` | `other` | Provider |
| `http://terminology.hl7.org/CodeSystem/payeetype` | `provider` | Provider |
| `http://terminology.hl7.org/CodeSystem/payeetype` | `subscriber` | Subscriber |
