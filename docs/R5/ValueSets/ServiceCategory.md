Comparison of 
Generated at Thursday, April 3, 2025 8:18:32 AM

### ServiceCategory

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ServiceCategory |
| Canonical URL | `http://hl7.org/fhir/ValueSet/service-category` |
| Version | 5.0.0 |
| Description | This value set defines an example set of codes that can be used to classify groupings of service-types/specialties. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `4894` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Appointment` | `Appointment.serviceCategory` | `http://hl7.org/fhir/ValueSet/service-category` | `Example` | A broad categorization of the service that is to be performed during this appointment |
| `http://hl7.org/fhir/StructureDefinition/HealthcareService` | `HealthcareService.category` | `http://hl7.org/fhir/ValueSet/service-category` | `Example` | Broad category of service being performed or delivered |
| `http://hl7.org/fhir/StructureDefinition/Schedule` | `Schedule.serviceCategory` | `http://hl7.org/fhir/ValueSet/service-category` | `Example` | High-level category |
| `http://hl7.org/fhir/StructureDefinition/Slot` | `Slot.serviceCategory` | `http://hl7.org/fhir/ValueSet/service-category` | `Example` | A broad categorization of the service that is to be performed during this appointment |

### Expansion Failure

Failed to expand this value set: Error expanding http://hl7.org/fhir/ValueSet/service-category|5.0.0: Operation expand failed: creating the required expansion failed with message "The ValueSet expander cannot find codesystem 'http://terminology.hl7.org/CodeSystem/service-category', so the expansion cannot be completed.".
