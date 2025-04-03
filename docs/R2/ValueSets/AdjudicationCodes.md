Comparison of 
Generated at Thursday, April 3, 2025 8:18:04 AM

### Adjudication Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Adjudication Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/adjudication` |
| Version | 1.0.2 |
| Description | This value set includes a smattering of Adjudication codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `7` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.item.adjudication.code` | `http://hl7.org/fhir/ValueSet/adjudication` | `Extensible` | Adjudication category such as co-pay, eligible, benefit, etc. |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.item.detail.adjudication.code` | `http://hl7.org/fhir/ValueSet/adjudication` | `Extensible` | Adjudication category such as co-pay, eligible, benefit, etc. |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.item.detail.subDetail.adjudication.code` | `http://hl7.org/fhir/ValueSet/adjudication` | `Extensible` | Adjudication category such as co-pay, eligible, benefit, etc. |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.addItem.adjudication.code` | `http://hl7.org/fhir/ValueSet/adjudication` | `Extensible` | Adjudication category such as co-pay, eligible, benefit, etc. |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.addItem.detail.adjudication.code` | `http://hl7.org/fhir/ValueSet/adjudication` | `Extensible` | Adjudication category such as co-pay, eligible, benefit, etc. |

### Referenced Systems

* `http://hl7.org/fhir/adjudication`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/adjudication` | `benefit` |  |
| `http://hl7.org/fhir/adjudication` | `copay` |  |
| `http://hl7.org/fhir/adjudication` | `deductible` |  |
| `http://hl7.org/fhir/adjudication` | `eligible` |  |
| `http://hl7.org/fhir/adjudication` | `eligpercent` |  |
| `http://hl7.org/fhir/adjudication` | `tax` |  |
| `http://hl7.org/fhir/adjudication` | `total` |  |
