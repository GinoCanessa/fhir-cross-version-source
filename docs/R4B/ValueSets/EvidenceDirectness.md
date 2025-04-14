Comparison of 
Generated at Monday, April 14, 2025 6:17:34 PM

### EvidenceDirectness

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | EvidenceDirectness |
| Canonical URL | `http://hl7.org/fhir/ValueSet/directness` |
| Version | 4.3.0 |
| Description | The quality of how direct the match is. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3717` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Evidence` | `Evidence.variableDefinition.directnessMatch` | `http://hl7.org/fhir/ValueSet/directness` | `Extensible` | low \| moderate \| high \| exact |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/directness`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/directness` | `exact` | Exact match between observed and intended variable |
| `http://terminology.hl7.org/CodeSystem/directness` | `high` | High quality match between observed and intended variable |
| `http://terminology.hl7.org/CodeSystem/directness` | `low` | Low quality match between observed and intended variable |
| `http://terminology.hl7.org/CodeSystem/directness` | `moderate` | Moderate quality match between observed and intended variable |
