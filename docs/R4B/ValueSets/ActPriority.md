Comparison of 
Generated at Monday, April 14, 2025 6:17:34 PM

### ActPriority

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ActPriority |
| Canonical URL | `http://terminology.hl7.org/ValueSet/v3-ActPriority` |
| Version | 2.0.0 |
| Description | A code or set of codes (e.g., for routine, emergency,) specifying the urgency under which the Act happened, can happen, is happening, is intended to happen, or is requested/demanded to happen.<br/><br/><br/><br/>*Discussion:* This attribute is used in orders to indicate the ordered priority, and in event documentation it indicates the actual priority used to perform the act. In definition mood it indicates the available priorities. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `4223` |
| Database Concept Count | `15` |
| Database Active Concept Count | `15` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.priority` | `http://terminology.hl7.org/ValueSet/v3-ActPriority` | `Example` | Indicates the urgency of the encounter |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-ActPriority`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v3-ActPriority` | `A` | ASAP |
| `http://terminology.hl7.org/CodeSystem/v3-ActPriority` | `CR` | callback results |
| `http://terminology.hl7.org/CodeSystem/v3-ActPriority` | `CS` | callback for scheduling |
| `http://terminology.hl7.org/CodeSystem/v3-ActPriority` | `CSP` | callback placer for scheduling |
| `http://terminology.hl7.org/CodeSystem/v3-ActPriority` | `CSR` | contact recipient for scheduling |
| `http://terminology.hl7.org/CodeSystem/v3-ActPriority` | `EL` | elective |
| `http://terminology.hl7.org/CodeSystem/v3-ActPriority` | `EM` | emergency |
| `http://terminology.hl7.org/CodeSystem/v3-ActPriority` | `P` | preop |
| `http://terminology.hl7.org/CodeSystem/v3-ActPriority` | `PRN` | as needed |
| `http://terminology.hl7.org/CodeSystem/v3-ActPriority` | `R` | routine |
| `http://terminology.hl7.org/CodeSystem/v3-ActPriority` | `RR` | rush reporting |
| `http://terminology.hl7.org/CodeSystem/v3-ActPriority` | `S` | stat |
| `http://terminology.hl7.org/CodeSystem/v3-ActPriority` | `T` | timing critical |
| `http://terminology.hl7.org/CodeSystem/v3-ActPriority` | `UD` | use as directed |
| `http://terminology.hl7.org/CodeSystem/v3-ActPriority` | `UR` | urgent |
