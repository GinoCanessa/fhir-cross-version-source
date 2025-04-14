Comparison of 
Generated at Monday, April 14, 2025 6:17:43 PM

### ProductCrossReferenceType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ProductCrossReferenceType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/medicinal-product-cross-reference-type` |
| Version | 5.0.0 |
| Description | Relationship to another Medicinal Product. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4725` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/MedicinalProductDefinition` | `MedicinalProductDefinition.crossReference.type` | `http://hl7.org/fhir/ValueSet/medicinal-product-cross-reference-type` | `Example` | The type of relationship, for instance branded to generic or virtual to actual product |

### Referenced Systems

* `http://hl7.org/fhir/medicinal-product-cross-reference-type`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/medicinal-product-cross-reference-type` | `ActualProduct` | Link Virtual to Actual Product |
| `http://hl7.org/fhir/medicinal-product-cross-reference-type` | `BrandedProduct` | Link Generic to Branded Product |
| `http://hl7.org/fhir/medicinal-product-cross-reference-type` | `GenericProduct` | Link Branded to Generic Product |
| `http://hl7.org/fhir/medicinal-product-cross-reference-type` | `InvestigationalProduct` | Link to Investigational Product |
| `http://hl7.org/fhir/medicinal-product-cross-reference-type` | `Parallel` | Link to Parallel Import Product |
| `http://hl7.org/fhir/medicinal-product-cross-reference-type` | `VirtualProduct` | Link Actual to Virtual Product |
