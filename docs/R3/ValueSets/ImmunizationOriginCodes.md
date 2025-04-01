Comparison of 
Generated at Tuesday, April 1, 2025 1:39:10 PM

### Immunization Origin Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Immunization Origin Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/immunization-origin` |
| Version | 3.0.2 |
| Description | The value set to instantiate this attribute should be drawn from a terminologically robust code system that consists of or contains concepts to support describing the source of the data when the report of the immunization event is not based on information from the person, entity or organization who administered the vaccine. This value set is provided as a suggestive example. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1273` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Immunization` | `Immunization.reportOrigin` | `http://hl7.org/fhir/ValueSet/immunization-origin` | `Example` | Indicates the source of a secondarily reported record |

### Referenced Systems

* `http://hl7.org/fhir/immunization-origin`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/immunization-origin` | `provider` | Other Provider |
| `http://hl7.org/fhir/immunization-origin` | `recall` | Parent/Guardian/Patient Recall |
| `http://hl7.org/fhir/immunization-origin` | `record` | Written Record |
| `http://hl7.org/fhir/immunization-origin` | `school` | School Record |
