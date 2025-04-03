Comparison of 
Generated at Thursday, April 3, 2025 8:18:17 AM

### RejectionCriterion

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | RejectionCriterion |
| Canonical URL | `http://hl7.org/fhir/ValueSet/rejection-criteria` |
| Version | 4.0.1 |
| Description | Criterion for rejection of the specimen by laboratory. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2697` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/SpecimenDefinition` | `SpecimenDefinition.typeTested.rejectionCriterion` | `http://hl7.org/fhir/ValueSet/rejection-criteria` | `Example` | Rejection criterion |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/rejection-criteria`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/rejection-criteria` | `broken` | broken specimen container |
| `http://terminology.hl7.org/CodeSystem/rejection-criteria` | `clotted` | specimen clotted |
| `http://terminology.hl7.org/CodeSystem/rejection-criteria` | `hemolized` | hemolized specimen |
| `http://terminology.hl7.org/CodeSystem/rejection-criteria` | `insufficient` | insufficient specimen volume |
| `http://terminology.hl7.org/CodeSystem/rejection-criteria` | `wrong-temperature` | specimen temperature inappropriate |
