Comparison of 
Generated at Monday, April 14, 2025 6:17:36 PM

### Hl7VSReAdmissionIndicator

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | Hl7VSReAdmissionIndicator |
| Canonical URL | `http://terminology.hl7.org/ValueSet/v2-0092` |
| Version | 2.0.0 |
| Description | Value Set of codes which are used to specify that a patient is being re-admitted to a healthcare facility from which they were discharged, and indicates the circumstances around such re-admission. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `4211` |
| Database Concept Count | `1` |
| Database Active Concept Count | `1` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.hospitalization.reAdmission` | `http://terminology.hl7.org/ValueSet/v2-0092` | `Example` | The type of hospital re-admission that has occurred (if any). If the value is absent, then this is not identified as a readmission |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v2-0092`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v2-0092` | `R` | Re-admission |
