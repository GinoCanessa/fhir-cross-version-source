Comparison of 
Generated at Tuesday, April 1, 2025 1:39:11 PM

### ServiceType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | ServiceType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/service-type` |
| Version | 3.0.2 |
| Description | This value set defines an example set of codes of service-types. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `1479` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Appointment` | `Appointment.serviceType` | `http://hl7.org/fhir/ValueSet/service-type` | `Example` | The specific service that is to be performed during this appointment |
| `http://hl7.org/fhir/StructureDefinition/HealthcareService` | `HealthcareService.type` | `http://hl7.org/fhir/ValueSet/service-type` | `Example` | Type of service that may be delivered or performed |
| `http://hl7.org/fhir/StructureDefinition/Schedule` | `Schedule.serviceType` | `http://hl7.org/fhir/ValueSet/service-type` | `Example` | The specific service that is to be performed during this appointment |
| `http://hl7.org/fhir/StructureDefinition/Slot` | `Slot.serviceType` | `http://hl7.org/fhir/ValueSet/service-type` | `Example` | The type of appointments that can be booked into this slot (ideally this would be an identifiable service - which is at a location, rather than the location itself). If provided then this overrides the value provided on the availability resource |

### Expansion Failure

Failed to expand this value set: Expansion is limited
