Comparison of 
Generated at Friday, April 4, 2025 2:58:32 PM

### Vaccination Protocol Dose Status codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Vaccination Protocol Dose Status codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/vaccination-protocol-dose-status` |
| Version | 1.0.2 |
| Description | The value set to instantiate this attribute should be drawn from a terminologically robust code system that consists of or contains concepts to support the medication process, in particular the process and reasons for dispensing. This value set is provided as a suggestive example. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1006` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Immunization` | `Immunization.vaccinationProtocol.doseStatus` | `http://hl7.org/fhir/ValueSet/vaccination-protocol-dose-status` | `Example` | Indicates if dose counts towards immunity |

### Referenced Systems

* `http://hl7.org/fhir/vaccination-protocol-dose-status`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/vaccination-protocol-dose-status` | `count` | Counts |
| `http://hl7.org/fhir/vaccination-protocol-dose-status` | `nocount` | Does not Count |
