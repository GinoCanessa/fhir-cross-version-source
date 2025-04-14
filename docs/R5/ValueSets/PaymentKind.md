Comparison of 
Generated at Monday, April 14, 2025 6:17:43 PM

### PaymentKind

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | PaymentKind |
| Canonical URL | `http://hl7.org/fhir/ValueSet/payment-kind` |
| Version | 5.0.0 |
| Description |  The type of workflow from which this payment arose. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4786` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/PaymentReconciliation` | `PaymentReconciliation.kind` | `http://hl7.org/fhir/ValueSet/payment-kind` | `Extensible` | Workflow originating payment |

### Referenced Systems

* `http://hl7.org/fhir/payment-kind`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/payment-kind` | `deposit` | Deposit on Account |
| `http://hl7.org/fhir/payment-kind` | `kiosk` | Kiosk Payment |
| `http://hl7.org/fhir/payment-kind` | `online` | Online Bill Payment |
| `http://hl7.org/fhir/payment-kind` | `periodic-payment` | Periodic Payment |
