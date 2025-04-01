Comparison of 
Generated at Tuesday, April 1, 2025 1:39:34 PM

### AccountBillingStatus

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | AccountBillingStatus |
| Canonical URL | `http://hl7.org/fhir/ValueSet/account-billing-status` |
| Version | 5.0.0 |
| Description | Indicates whether the account is available to be used for billing purposes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4238` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Account` | `Account.billingStatus` | `http://hl7.org/fhir/ValueSet/account-billing-status` | `Example` | Tracks the lifecycle of the account through the billing process |

### Referenced Systems

* `http://hl7.org/fhir/account-billing-status`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/account-billing-status` | `billing` | Billing |
| `http://hl7.org/fhir/account-billing-status` | `carecomplete-notbilled` | CareComplete/Not Billed |
| `http://hl7.org/fhir/account-billing-status` | `closed-baddebt` | Closed-Bad Debt |
| `http://hl7.org/fhir/account-billing-status` | `closed-combined` | Closed-Combined |
| `http://hl7.org/fhir/account-billing-status` | `closed-completed` | Closed-Completed |
| `http://hl7.org/fhir/account-billing-status` | `closed-voided` | Closed-Voided |
| `http://hl7.org/fhir/account-billing-status` | `open` | Open |
