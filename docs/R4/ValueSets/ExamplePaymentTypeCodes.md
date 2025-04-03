Comparison of 
Generated at Thursday, April 3, 2025 8:18:17 AM

### ExamplePaymentTypeCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ExamplePaymentTypeCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/ex-paymenttype` |
| Version | 4.0.1 |
| Description | This value set includes example Payment Type codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2435` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.payment.type` | `http://hl7.org/fhir/ValueSet/ex-paymenttype` | `Example` | Partial or complete payment |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.payment.type` | `http://hl7.org/fhir/ValueSet/ex-paymenttype` | `Example` | Partial or complete payment |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/ex-paymenttype`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/ex-paymenttype` | `complete` | Complete |
| `http://terminology.hl7.org/CodeSystem/ex-paymenttype` | `partial` | Partial |
