Comparison of 
Generated at Tuesday, April 1, 2025 1:39:34 PM

### AuditEventSourceType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | AuditEventSourceType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/security-source-type` |
| Version | 5.0.0 |
| Description | The type of process where the audit event originated from. Use of these codes is not required but is encouraged to maintain translation with DICOM AuditMessage schema. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `4891` |
| Database Concept Count | `8` |
| Database Active Concept Count | `8` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.source.type` | `http://hl7.org/fhir/ValueSet/security-source-type` | `Preferred` | The type of source where event originated |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/security-source-type`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/security-source-type` | `1` | User Device |
| `http://terminology.hl7.org/CodeSystem/security-source-type` | `2` | Data Interface |
| `http://terminology.hl7.org/CodeSystem/security-source-type` | `3` | Web Server |
| `http://terminology.hl7.org/CodeSystem/security-source-type` | `4` | Application Server |
| `http://terminology.hl7.org/CodeSystem/security-source-type` | `5` | Database Server |
| `http://terminology.hl7.org/CodeSystem/security-source-type` | `6` | Security Server |
| `http://terminology.hl7.org/CodeSystem/security-source-type` | `7` | Network Device |
| `http://terminology.hl7.org/CodeSystem/security-source-type` | `8` | Network Router |
