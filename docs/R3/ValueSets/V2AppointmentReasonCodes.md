Comparison of 
Generated at Tuesday, April 1, 2025 1:39:11 PM

### v2 Appointment reason codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | v2 Appointment reason codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/v2-0276` |
| Version | 2.8.2 |
| Description | FHIR Value set/code system definition for HL7 v2 table 0276 ( Appointment reason codes) |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `1698` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Appointment` | `Appointment.appointmentType` | `http://hl7.org/fhir/ValueSet/v2-0276` | `Preferred` | The style of appointment or patient that has been booked in the slot (not service type) |
| `http://hl7.org/fhir/StructureDefinition/Slot` | `Slot.appointmentType` | `http://hl7.org/fhir/ValueSet/v2-0276` | `Preferred` | The style of appointment or patient that may be booked in the slot (not service type) |

### Referenced Systems

* `http://hl7.org/fhir/v2/0276`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/v2/0276` | `CHECKUP` | A routine check-up, such as an annual physical |
| `http://hl7.org/fhir/v2/0276` | `EMERGENCY` | Emergency appointment |
| `http://hl7.org/fhir/v2/0276` | `FOLLOWUP` | A follow up visit from a previous appointment |
| `http://hl7.org/fhir/v2/0276` | `ROUTINE` | Routine appointment - default if not valued |
| `http://hl7.org/fhir/v2/0276` | `WALKIN` | A previously unscheduled walk-in visit |
