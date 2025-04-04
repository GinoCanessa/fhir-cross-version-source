Comparison of 
Generated at Friday, April 4, 2025 2:58:31 PM

### Priority Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Priority Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/process-priority` |
| Version | 1.0.2 |
| Description | This value set includes the financial processing priority codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `294` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.priority` | `http://hl7.org/fhir/ValueSet/process-priority` | `Example` | Desired processing priority |

### Referenced Systems

* `http://hl7.org/fhir/processpriority`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/processpriority` | `deferred` | Deferred |
| `http://hl7.org/fhir/processpriority` | `normal` | Normal |
| `http://hl7.org/fhir/processpriority` | `stat` | Immediate |
