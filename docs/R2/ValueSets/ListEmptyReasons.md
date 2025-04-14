Comparison of 
Generated at Monday, April 14, 2025 6:17:15 PM

### List Empty Reasons

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | List Empty Reasons |
| Canonical URL | `http://hl7.org/fhir/ValueSet/list-empty-reason` |
| Version | 1.0.2 |
| Description | General reasons for a list to be empty. Reasons are either related to a summary list (i.e. problem or medication list) or to a workflow related list (i.e. consultation list). |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `206` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Composition` | `Composition.section.emptyReason` | `http://hl7.org/fhir/ValueSet/list-empty-reason` | `Preferred` | Why the section is empty |
| `http://hl7.org/fhir/StructureDefinition/List` | `List.emptyReason` | `http://hl7.org/fhir/ValueSet/list-empty-reason` | `Preferred` | Why list is empty |

### Referenced Systems

* `http://hl7.org/fhir/list-empty-reason`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/list-empty-reason` | `closed` | Closed |
| `http://hl7.org/fhir/list-empty-reason` | `nilknown` | Nil Known |
| `http://hl7.org/fhir/list-empty-reason` | `notasked` | Not Asked |
| `http://hl7.org/fhir/list-empty-reason` | `notstarted` | Not Started |
| `http://hl7.org/fhir/list-empty-reason` | `unavailable` | Unavailable |
| `http://hl7.org/fhir/list-empty-reason` | `withheld` | Information Withheld |
