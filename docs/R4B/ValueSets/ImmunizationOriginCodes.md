Comparison of 
Generated at Monday, April 14, 2025 6:17:35 PM

### ImmunizationOriginCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ImmunizationOriginCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/immunization-origin` |
| Version | 4.3.0 |
| Description | The value set to instantiate this attribute should be drawn from a terminologically robust code system that consists of or contains concepts to support describing the source of the data when the report of the immunization event is not based on information from the person, entity or organization who administered the vaccine. This value set is provided as a suggestive example. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3823` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Immunization` | `Immunization.reportOrigin` | `http://hl7.org/fhir/ValueSet/immunization-origin` | `Example` | Indicates the source of a secondarily reported record |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/immunization-origin`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/immunization-origin` | `provider` | Other Provider |
| `http://terminology.hl7.org/CodeSystem/immunization-origin` | `recall` | Parent/Guardian/Patient Recall |
| `http://terminology.hl7.org/CodeSystem/immunization-origin` | `record` | Written Record |
| `http://terminology.hl7.org/CodeSystem/immunization-origin` | `school` | School Record |
