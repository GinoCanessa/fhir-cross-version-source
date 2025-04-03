Comparison of 
Generated at Thursday, April 3, 2025 8:18:31 AM

### PaymentStatusCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | PaymentStatusCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/payment-status` |
| Version | 5.0.0 |
| Description | This value set includes a sample set of Payment Status codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4788` |
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
