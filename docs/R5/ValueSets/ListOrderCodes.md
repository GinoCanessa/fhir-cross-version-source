Comparison of 
Generated at Tuesday, April 1, 2025 1:39:35 PM

### ListOrderCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ListOrderCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/list-order` |
| Version | 5.0.0 |
| Description | Base values for the order of the items in a list resource. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4668` |
| Database Concept Count | `8` |
| Database Active Concept Count | `8` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Composition` | `Composition.section.orderedBy` | `http://hl7.org/fhir/ValueSet/list-order` | `Preferred` | Order of section entries |
| `http://hl7.org/fhir/StructureDefinition/EvidenceReport` | `EvidenceReport.section.orderedBy` | `http://hl7.org/fhir/ValueSet/list-order` | `Preferred` | Order of section entries |
| `http://hl7.org/fhir/StructureDefinition/List` | `List.orderedBy` | `http://hl7.org/fhir/ValueSet/list-order` | `Preferred` | What order the list has |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/list-order`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/list-order` | `alphabetic` | Sorted Alphabetically |
| `http://terminology.hl7.org/CodeSystem/list-order` | `category` | Sorted by Category |
| `http://terminology.hl7.org/CodeSystem/list-order` | `entry-date` | Sorted by Item Date |
| `http://terminology.hl7.org/CodeSystem/list-order` | `event-date` | Sorted by Event Date |
| `http://terminology.hl7.org/CodeSystem/list-order` | `patient` | Sorted by Patient |
| `http://terminology.hl7.org/CodeSystem/list-order` | `priority` | Sorted by Priority |
| `http://terminology.hl7.org/CodeSystem/list-order` | `system` | Sorted by System |
| `http://terminology.hl7.org/CodeSystem/list-order` | `user` | Sorted by User |
