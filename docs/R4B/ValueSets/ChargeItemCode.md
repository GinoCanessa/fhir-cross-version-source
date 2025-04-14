Comparison of 
Generated at Monday, April 14, 2025 6:17:34 PM

### ChargeItemCode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ChargeItemCode |
| Canonical URL | `http://hl7.org/fhir/ValueSet/chargeitem-billingcodes` |
| Version | 4.3.0 |
| Description | Example set of codes that can be used for billing purposes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3582` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ChargeItem` | `ChargeItem.code` | `http://hl7.org/fhir/ValueSet/chargeitem-billingcodes` | `Example` | A code that identifies the charge, like a billing code |
| `http://hl7.org/fhir/StructureDefinition/ChargeItemDefinition` | `ChargeItemDefinition.code` | `http://hl7.org/fhir/ValueSet/chargeitem-billingcodes` | `Example` | Billing codes or product types this definition applies to |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/chargeitem-billingcodes`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/chargeitem-billingcodes` | `1100` | Unvorhergesehene Inanspruchnahme |
| `http://terminology.hl7.org/CodeSystem/chargeitem-billingcodes` | `1210` | Notfallpauschale |
| `http://terminology.hl7.org/CodeSystem/chargeitem-billingcodes` | `1320` | Grundpauschale |
