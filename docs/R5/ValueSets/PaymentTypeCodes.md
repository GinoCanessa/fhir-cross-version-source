Comparison of 
Generated at Tuesday, April 1, 2025 1:39:34 PM

### PaymentTypeCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | PaymentTypeCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/payment-type` |
| Version | 5.0.0 |
| Description | This value set includes sample Payment Type codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4789` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/PaymentReconciliation` | `PaymentReconciliation.type` | `http://hl7.org/fhir/ValueSet/payment-type` | `Extensible` | Category of payment |
| `http://hl7.org/fhir/StructureDefinition/PaymentReconciliation` | `PaymentReconciliation.allocation.type` | `http://hl7.org/fhir/ValueSet/payment-type` | `Extensible` | Category of payment |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/payment-type`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/payment-type` | `adjustment` | Adjustment |
| `http://terminology.hl7.org/CodeSystem/payment-type` | `advance` | Advance |
| `http://terminology.hl7.org/CodeSystem/payment-type` | `payment` | Payment |
