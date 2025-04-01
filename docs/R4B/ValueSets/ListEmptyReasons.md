Comparison of 
Generated at Tuesday, April 1, 2025 1:39:27 PM

### ListEmptyReasons

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ListEmptyReasons |
| Canonical URL | `http://hl7.org/fhir/ValueSet/list-empty-reason` |
| Version | 4.3.0 |
| Description | General reasons for a list to be empty. Reasons are either related to a summary list (i.e. problem or medication list) or to a workflow related list (i.e. consultation list). |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3866` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Composition` | `Composition.section.emptyReason` | `http://hl7.org/fhir/ValueSet/list-empty-reason` | `Preferred` | Why the section is empty |
| `http://hl7.org/fhir/StructureDefinition/EvidenceReport` | `EvidenceReport.section.emptyReason` | `http://hl7.org/fhir/ValueSet/list-empty-reason` | `Preferred` | Why the section is empty |
| `http://hl7.org/fhir/StructureDefinition/List` | `List.emptyReason` | `http://hl7.org/fhir/ValueSet/list-empty-reason` | `Preferred` | Why list is empty |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/list-empty-reason`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/list-empty-reason` | `closed` | Closed |
| `http://terminology.hl7.org/CodeSystem/list-empty-reason` | `nilknown` | Nil Known |
| `http://terminology.hl7.org/CodeSystem/list-empty-reason` | `notasked` | Not Asked |
| `http://terminology.hl7.org/CodeSystem/list-empty-reason` | `notstarted` | Not Started |
| `http://terminology.hl7.org/CodeSystem/list-empty-reason` | `unavailable` | Unavailable |
| `http://terminology.hl7.org/CodeSystem/list-empty-reason` | `withheld` | Information Withheld |
