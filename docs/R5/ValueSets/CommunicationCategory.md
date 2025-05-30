Comparison of 
Generated at Monday, April 14, 2025 6:17:43 PM

### CommunicationCategory

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | CommunicationCategory |
| Canonical URL | `http://hl7.org/fhir/ValueSet/communication-category` |
| Version | 5.0.0 |
| Description | Codes for general categories of communications such as alerts, instructions, etc. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4380` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Communication` | `Communication.category` | `http://hl7.org/fhir/ValueSet/communication-category` | `Example` | Message category |
| `http://hl7.org/fhir/StructureDefinition/CommunicationRequest` | `CommunicationRequest.category` | `http://hl7.org/fhir/ValueSet/communication-category` | `Example` | Message category |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/communication-category`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/communication-category` | `alert` | Alert |
| `http://terminology.hl7.org/CodeSystem/communication-category` | `instruction` | Instruction |
| `http://terminology.hl7.org/CodeSystem/communication-category` | `notification` | Notification |
| `http://terminology.hl7.org/CodeSystem/communication-category` | `reminder` | Reminder |
