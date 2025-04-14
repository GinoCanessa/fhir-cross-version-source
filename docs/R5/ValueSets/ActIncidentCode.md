Comparison of 
Generated at Monday, April 14, 2025 6:17:44 PM

### ActIncidentCode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ActIncidentCode |
| Canonical URL | `http://terminology.hl7.org/ValueSet/v3-ActIncidentCode` |
| Version | 2.0.0 |
| Description | Set of codes indicating the type of incident or accident. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `5048` |
| Database Concept Count | `5` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.accident.type` | `http://terminology.hl7.org/ValueSet/v3-ActIncidentCode` | `Extensible` | The nature of the accident |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.accident.type` | `http://terminology.hl7.org/ValueSet/v3-ActIncidentCode` | `Extensible` | The nature of the accident |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-ActCode`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `MVA` | Motor vehicle accident |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SCHOOL` | School Accident |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `SPT` | Sporting Accident |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `WPA` | Workplace accident |
