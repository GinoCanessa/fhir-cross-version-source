Comparison of 
Generated at Monday, April 14, 2025 6:17:15 PM

### List Order Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | List Order Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/list-order` |
| Version | 1.0.2 |
| Description | Base values for the order of the items in a list resource. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `210` |
| Database Concept Count | `8` |
| Database Active Concept Count | `8` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Composition` | `Composition.section.orderedBy` | `http://hl7.org/fhir/ValueSet/list-order` | `Preferred` | Order of section entries |
| `http://hl7.org/fhir/StructureDefinition/List` | `List.orderedBy` | `http://hl7.org/fhir/ValueSet/list-order` | `Preferred` | What order the list has |

### Referenced Systems

* `http://hl7.org/fhir/list-order`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/list-order` | `alphabetic` | Sorted Alphabetically |
| `http://hl7.org/fhir/list-order` | `category` | Sorted by Category |
| `http://hl7.org/fhir/list-order` | `entry-date` | Sorted by Item Date |
| `http://hl7.org/fhir/list-order` | `event-date` | Sorted by Event Date |
| `http://hl7.org/fhir/list-order` | `patient` | Sorted by Patient |
| `http://hl7.org/fhir/list-order` | `priority` | Sorted by Priority |
| `http://hl7.org/fhir/list-order` | `system` | Sorted by System |
| `http://hl7.org/fhir/list-order` | `user` | Sorted by User |
