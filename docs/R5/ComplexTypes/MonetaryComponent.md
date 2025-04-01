Comparison of 
Generated at Tuesday, April 1, 2025 1:39:35 PM

### MonetaryComponent

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | MonetaryComponent |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/MonetaryComponent` |
| Version | 5.0.0 |
| Description | MonetaryComponent Type: Availability data for an {item}. |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `2229` |
| Database Snapshot Count | `7` |
| Database Differential Count | `5` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `MonetaryComponent` | `MonetaryComponent` | `MonetaryComponent` | MonetaryComponent | Availability data for an {item} | 0..* | MonetaryComponent |  |  |
| `MonetaryComponent.amount` | `MonetaryComponent.amount` | `amount` | MonetaryComponent.amount | Explicit value amount to be used | 0..1 | Money |  |  |
| `MonetaryComponent.code` | `MonetaryComponent.code` | `code` | MonetaryComponent.code | Codes may be used to differentiate between kinds of taxes, surcharges, discounts etc. | 0..1 | CodeableConcept | `Example` |  |
| `MonetaryComponent.extension` | `MonetaryComponent.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `MonetaryComponent.factor` | `MonetaryComponent.factor` | `factor` | MonetaryComponent.factor | Factor used for calculating this component | 0..1 | decimal |  |  |
| `MonetaryComponent.id` | `MonetaryComponent.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `MonetaryComponent.type` | `MonetaryComponent.type` | `type` | MonetaryComponent.type | base \| surcharge \| deduction \| discount \| tax \| informational | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/price-component-type|5.0.0` |
### Empty Projection

This Structure (ComplexType) resulted in no projection (no mappings to other packages).

