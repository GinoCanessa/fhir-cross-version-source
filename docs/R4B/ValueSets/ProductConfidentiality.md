Comparison of 
Generated at Monday, April 14, 2025 6:17:36 PM

### ProductConfidentiality

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ProductConfidentiality |
| Canonical URL | `http://hl7.org/fhir/ValueSet/medicinal-product-confidentiality` |
| Version | 4.3.0 |
| Description | Confidentiality rating, e.g. commercial sensitivity for a Medicinal Product. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3921` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/MedicinalProductDefinition` | `MedicinalProductDefinition.operation.confidentialityIndicator` | `http://hl7.org/fhir/ValueSet/medicinal-product-confidentiality` | `Example` | Specifies whether this process is considered proprietary or confidential |

### Referenced Systems

* `http://hl7.org/fhir/medicinal-product-confidentiality`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/medicinal-product-confidentiality` | `CommerciallySensitive` | Commercially Sensitive |
| `http://hl7.org/fhir/medicinal-product-confidentiality` | `NotCommerciallySensitive` | Not Commercially Sensitive |
