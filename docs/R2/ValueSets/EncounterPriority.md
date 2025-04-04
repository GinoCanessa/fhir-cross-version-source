Comparison of 
Generated at Friday, April 4, 2025 2:58:32 PM

### Encounter Priority

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Encounter Priority |
| Canonical URL | `http://hl7.org/fhir/ValueSet/encounter-priority` |
| Version | 1.0.2 |
| Description | This is an example value set defined by the FHIR project, that could be used in Emergency to indicate the encounter priority as determined by triage. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `148` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.priority` | `http://hl7.org/fhir/ValueSet/encounter-priority` | `Example` | Indicates the urgency of the encounter |

### Referenced Systems

* `http://hl7.org/fhir/encounter-priority`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/encounter-priority` | `emg` | Emergency |
| `http://hl7.org/fhir/encounter-priority` | `imm` | Immediate |
| `http://hl7.org/fhir/encounter-priority` | `no-urg` | Non-urgent |
| `http://hl7.org/fhir/encounter-priority` | `s-urg` | Semi-urgent |
| `http://hl7.org/fhir/encounter-priority` | `urg` | Urgent |
