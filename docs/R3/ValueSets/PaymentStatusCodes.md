Comparison of 
Generated at Friday, April 4, 2025 2:58:36 PM

### Payment Status Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Payment Status Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/payment-status` |
| Version | 3.0.2 |
| Description | This value set includes a sample set of Payment Status codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1389` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/PaymentNotice` | `PaymentNotice.paymentStatus` | `http://hl7.org/fhir/ValueSet/payment-status` | `Example` | Whether payment has been sent or cleared |

### Referenced Systems

* `http://hl7.org/fhir/paymentstatus`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/paymentstatus` | `cleared` | Cleared |
| `http://hl7.org/fhir/paymentstatus` | `paid` | Paid |
