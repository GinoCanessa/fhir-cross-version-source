Comparison of 
Generated at Monday, April 14, 2025 6:17:20 PM

### Payment Adjustment Reason Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Payment Adjustment Reason Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/payment-adjustment-reason` |
| Version | 3.0.2 |
| Description | This value set includes smattering of Payment Adjustment Reason codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1388` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.payment.adjustmentReason` | `http://hl7.org/fhir/ValueSet/payment-adjustment-reason` | `Example` | Explanation for the non-claim adjustment |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.payment.adjustmentReason` | `http://hl7.org/fhir/ValueSet/payment-adjustment-reason` | `Example` | Explanation for the non-claim adjustment |

### Referenced Systems

* `http://hl7.org/fhir/payment-adjustment-reason`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/payment-adjustment-reason` | `a001` | Prior Payment Reversal |
| `http://hl7.org/fhir/payment-adjustment-reason` | `a002` | Prior Overpayment |
