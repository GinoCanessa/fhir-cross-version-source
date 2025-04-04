Comparison of 
Generated at Friday, April 4, 2025 2:58:58 PM

### MedicinalProductDomain

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | MedicinalProductDomain |
| Canonical URL | `http://hl7.org/fhir/ValueSet/medicinal-product-domain` |
| Version | 5.0.0 |
| Description | Applicable domain for this product (e.g. human, veterinary) |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4726` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/MedicinalProductDefinition` | `MedicinalProductDefinition.domain` | `http://hl7.org/fhir/ValueSet/medicinal-product-domain` | `Example` | If this medicine applies to human or veterinary uses |
| `http://hl7.org/fhir/StructureDefinition/SubstanceDefinition` | `SubstanceDefinition.domain` | `http://hl7.org/fhir/ValueSet/medicinal-product-domain` | `Example` | If the substance applies to human or veterinary use |

### Referenced Systems

* `http://hl7.org/fhir/medicinal-product-domain`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/medicinal-product-domain` | `Human` | Human use |
| `http://hl7.org/fhir/medicinal-product-domain` | `HumanAndVeterinary` | Human and Veterinary use |
| `http://hl7.org/fhir/medicinal-product-domain` | `Veterinary` | Veterinary use |
