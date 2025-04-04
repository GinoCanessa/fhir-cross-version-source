Comparison of 
Generated at Friday, April 4, 2025 2:58:36 PM

### v3 Code System ActPriority

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | v3 Code System ActPriority |
| Canonical URL | `http://hl7.org/fhir/ValueSet/v3-ActPriority` |
| Version | 2016-11-11 |
| Description | A set of codes (e.g., for routine, emergency), specifying the urgency under which the Act happened, can happen, is happening, is intended to happen, or is requested/demanded to happen. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `1988` |
| Database Concept Count | `15` |
| Database Active Concept Count | `15` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.priority` | `http://hl7.org/fhir/ValueSet/v3-ActPriority` | `Example` | Indicates the urgency of the encounter |

### Referenced Systems

* `http://hl7.org/fhir/v3/ActPriority`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/v3/ActPriority` | `A` | ASAP |
| `http://hl7.org/fhir/v3/ActPriority` | `CR` | callback results |
| `http://hl7.org/fhir/v3/ActPriority` | `CS` | callback for scheduling |
| `http://hl7.org/fhir/v3/ActPriority` | `CSP` | callback placer for scheduling |
| `http://hl7.org/fhir/v3/ActPriority` | `CSR` | contact recipient for scheduling |
| `http://hl7.org/fhir/v3/ActPriority` | `EL` | elective |
| `http://hl7.org/fhir/v3/ActPriority` | `EM` | emergency |
| `http://hl7.org/fhir/v3/ActPriority` | `P` | preop |
| `http://hl7.org/fhir/v3/ActPriority` | `PRN` | as needed |
| `http://hl7.org/fhir/v3/ActPriority` | `R` | routine |
| `http://hl7.org/fhir/v3/ActPriority` | `RR` | rush reporting |
| `http://hl7.org/fhir/v3/ActPriority` | `S` | stat |
| `http://hl7.org/fhir/v3/ActPriority` | `T` | timing critical |
| `http://hl7.org/fhir/v3/ActPriority` | `UD` | use as directed |
| `http://hl7.org/fhir/v3/ActPriority` | `UR` | urgent |
