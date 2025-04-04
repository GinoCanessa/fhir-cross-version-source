Comparison of 
Generated at Friday, April 4, 2025 2:58:44 PM

### PaymentStatusCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | PaymentStatusCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/payment-status` |
| Version | 4.0.1 |
| Description | This value set includes a sample set of Payment Status codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2639` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/PaymentNotice` | `PaymentNotice.paymentStatus` | `http://hl7.org/fhir/ValueSet/payment-status` | `Example` | Issued or cleared Status of the payment |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/paymentstatus`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/paymentstatus` | `cleared` | Cleared |
| `http://terminology.hl7.org/CodeSystem/paymentstatus` | `paid` | Paid |
