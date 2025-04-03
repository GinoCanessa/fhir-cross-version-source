Comparison of 
Generated at Thursday, April 3, 2025 8:18:09 AM

### v2 Response Level

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | v2 Response Level |
| Canonical URL | `http://hl7.org/fhir/ValueSet/v2-0179` |
| Version | 2.8.2 |
| Description | FHIR Value set/code system definition for HL7 v2 table 0179 ( Response Level) |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `1626` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |

### Referenced Systems

* `http://hl7.org/fhir/v2/0179`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/v2/0179` | `AL` | Always.  All MFA segments (whether denoting errors or not) must be returned via the application-level acknowledgment message |
| `http://hl7.org/fhir/v2/0179` | `ER` | Error/Reject conditions only.  Only MFA segments denoting errors must be returned via the application-level acknowledgment for this message |
| `http://hl7.org/fhir/v2/0179` | `NE` | Never.  No application-level response needed |
| `http://hl7.org/fhir/v2/0179` | `SU` | Success.  Only MFA segments denoting success must be returned via the application-level acknowledgment for this message |
