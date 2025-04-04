Comparison of 
Generated at Friday, April 4, 2025 2:58:51 PM

### AuditEventSourceType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | AuditEventSourceType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/audit-source-type` |
| Version | 4.3.0 |
| Description | The type of process where the audit event originated from. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `3553` |
| Database Concept Count | `9` |
| Database Active Concept Count | `9` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.source.type` | `http://hl7.org/fhir/ValueSet/audit-source-type` | `Extensible` | The type of source where event originated |

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
| `http://terminology.hl7.org/CodeSystem/security-source-type` | `9` | Other |
