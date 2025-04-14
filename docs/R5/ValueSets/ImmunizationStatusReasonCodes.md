Comparison of 
Generated at Monday, April 14, 2025 6:17:42 PM

### ImmunizationStatusReasonCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ImmunizationStatusReasonCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/immunization-status-reason` |
| Version | 5.0.0 |
| Description | The value set to instantiate this attribute should be drawn from a terminologically robust code system that consists of or contains concepts to support describing the reason why a dose of vaccine was not administered. This value set is provided as a suggestive example. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4629` |
| Database Concept Count | `8` |
| Database Active Concept Count | `8` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Immunization` | `Immunization.statusReason` | `http://hl7.org/fhir/ValueSet/immunization-status-reason` | `Example` | Reason for current status |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-ActReason`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `IMMUNE` | immunity |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `MEDPREC` | medical precaution |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `OSTOCK` | product out of stock |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `PATOBJ` | patient objection |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `PHILISOP` | philosophical objection |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `RELIG` | religious objection |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `VACEFF` | vaccine efficacy concerns |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `VACSAF` | vaccine safety concerns |
