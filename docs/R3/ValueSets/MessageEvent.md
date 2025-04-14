Comparison of 
Generated at Monday, April 14, 2025 6:17:20 PM

### MessageEvent

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | MessageEvent |
| Canonical URL | `http://hl7.org/fhir/ValueSet/message-events` |
| Version | 3.0.2 |
| Description | One of the message events defined as part of FHIR. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1340` |
| Database Concept Count | `12` |
| Database Active Concept Count | `12` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/CapabilityStatement` | `CapabilityStatement.messaging.event.code` | `http://hl7.org/fhir/ValueSet/message-events` | `Example` | Event type |
| `http://hl7.org/fhir/StructureDefinition/MessageDefinition` | `MessageDefinition.event` | `http://hl7.org/fhir/ValueSet/message-events` | `Example` | Event type |
| `http://hl7.org/fhir/StructureDefinition/MessageHeader` | `MessageHeader.event` | `http://hl7.org/fhir/ValueSet/message-events` | `Example` | Code for the event this message represents |

### Referenced Systems

* `http://hl7.org/fhir/message-events`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/message-events` | `CodeSystem-expand` | CodeSystem-expand |
| `http://hl7.org/fhir/message-events` | `MedicationAdministration-Complete` | MedicationAdministration-Complete |
| `http://hl7.org/fhir/message-events` | `MedicationAdministration-Nullification` | MedicationAdministration-Nullification |
| `http://hl7.org/fhir/message-events` | `MedicationAdministration-Recording` | MedicationAdministration-Recording |
| `http://hl7.org/fhir/message-events` | `MedicationAdministration-Update` | MedicationAdministration-Update |
| `http://hl7.org/fhir/message-events` | `admin-notify` | admin-notify |
| `http://hl7.org/fhir/message-events` | `communication-request` | communication-request |
| `http://hl7.org/fhir/message-events` | `diagnosticreport-provide` | diagnosticreport-provide |
| `http://hl7.org/fhir/message-events` | `observation-provide` | observation-provide |
| `http://hl7.org/fhir/message-events` | `patient-link` | patient-link |
| `http://hl7.org/fhir/message-events` | `patient-unlink` | patient-unlink |
| `http://hl7.org/fhir/message-events` | `valueset-expand` | valueset-expand |
