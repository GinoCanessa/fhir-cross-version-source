Comparison of 
Generated at Friday, April 4, 2025 2:58:52 PM

### Hl7VSAppointmentReasonCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | Hl7VSAppointmentReasonCodes |
| Canonical URL | `http://terminology.hl7.org/ValueSet/v2-0276` |
| Version | 2.0.0 |
| Description | Value Set of codes that describe the kind of appointment or the reason why an appointment has been scheduled. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `4213` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Appointment` | `Appointment.appointmentType` | `http://terminology.hl7.org/ValueSet/v2-0276` | `Preferred` | The style of appointment or patient that has been booked in the slot (not service type) |
| `http://hl7.org/fhir/StructureDefinition/Slot` | `Slot.appointmentType` | `http://terminology.hl7.org/ValueSet/v2-0276` | `Preferred` | The style of appointment or patient that may be booked in the slot (not service type) |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v2-0276`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v2-0276` | `CHECKUP` | A routine check-up, such as an annual physical |
| `http://terminology.hl7.org/CodeSystem/v2-0276` | `EMERGENCY` | Emergency appointment |
| `http://terminology.hl7.org/CodeSystem/v2-0276` | `FOLLOWUP` | A follow up visit from a previous appointment |
| `http://terminology.hl7.org/CodeSystem/v2-0276` | `ROUTINE` | Routine appointment - default if not valued |
| `http://terminology.hl7.org/CodeSystem/v2-0276` | `WALKIN` | A previously unscheduled walk-in visit |
