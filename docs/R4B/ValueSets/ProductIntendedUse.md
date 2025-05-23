Comparison of 
Generated at Monday, April 14, 2025 6:17:34 PM

### ProductIntendedUse

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ProductIntendedUse |
| Canonical URL | `http://hl7.org/fhir/ValueSet/product-intended-use` |
| Version | 4.3.0 |
| Description | The overall intended use of a product. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4002` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ClinicalUseDefinition` | `ClinicalUseDefinition.indication.intendedEffect` | `http://hl7.org/fhir/ValueSet/product-intended-use` | `Preferred` | The intended effect, aim or strategy to be achieved |
| `http://hl7.org/fhir/StructureDefinition/RegulatedAuthorization` | `RegulatedAuthorization.intendedUse` | `http://hl7.org/fhir/ValueSet/product-intended-use` | `Preferred` | The intended use of the product, e.g. prevention, treatment |

### Referenced Systems

* `http://hl7.org/fhir/product-intended-use`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/product-intended-use` | `Alleviation` | Alleviation |
| `http://hl7.org/fhir/product-intended-use` | `Diagnosis` | Diagnosis |
| `http://hl7.org/fhir/product-intended-use` | `Monitoring` | Monitoring |
| `http://hl7.org/fhir/product-intended-use` | `Prevention` | Prevention |
| `http://hl7.org/fhir/product-intended-use` | `Treatment` | Treatment |
