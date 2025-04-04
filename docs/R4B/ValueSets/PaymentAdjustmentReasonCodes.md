Comparison of 
Generated at Friday, April 4, 2025 2:58:51 PM

### PaymentAdjustmentReasonCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | PaymentAdjustmentReasonCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/payment-adjustment-reason` |
| Version | 4.3.0 |
| Description | This value set includes smattering of Payment Adjustment Reason codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3983` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.payment.adjustmentReason` | `http://hl7.org/fhir/ValueSet/payment-adjustment-reason` | `Example` | Explanation for the adjustment |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.payment.adjustmentReason` | `http://hl7.org/fhir/ValueSet/payment-adjustment-reason` | `Example` | Explanation for the variance |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/payment-adjustment-reason`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/payment-adjustment-reason` | `a001` | Prior Payment Reversal |
| `http://terminology.hl7.org/CodeSystem/payment-adjustment-reason` | `a002` | Prior Overpayment |
