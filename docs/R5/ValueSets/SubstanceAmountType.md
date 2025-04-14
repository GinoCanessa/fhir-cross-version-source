Comparison of 
Generated at Monday, April 14, 2025 6:17:43 PM

### SubstanceAmountType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | SubstanceAmountType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/substance-amount-type` |
| Version | 5.0.0 |
| Description | The relationship between two substance types. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4929` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/SubstanceDefinition` | `SubstanceDefinition.moiety.measurementType` | `http://hl7.org/fhir/ValueSet/substance-amount-type` | `Example` | The measurement type of the quantitative value |
| `http://hl7.org/fhir/StructureDefinition/SubstanceDefinition` | `SubstanceDefinition.relationship.comparator` | `http://hl7.org/fhir/ValueSet/substance-amount-type` | `Example` | An operator for the amount, for example "average", "approximately", "less than" |

### Referenced Systems

* `http://hl7.org/fhir/substance-amount-type`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/substance-amount-type` | `Approximately` | Approximately |
| `http://hl7.org/fhir/substance-amount-type` | `Average` | Average |
| `http://hl7.org/fhir/substance-amount-type` | `LessThan` | Less Than |
| `http://hl7.org/fhir/substance-amount-type` | `MoreThan` | More Than |
