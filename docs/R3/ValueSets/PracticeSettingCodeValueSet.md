Comparison of 
Generated at Monday, April 14, 2025 6:17:19 PM

### Practice Setting Code Value Set

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Practice Setting Code Value Set |
| Canonical URL | `http://hl7.org/fhir/ValueSet/c80-practice-codes` |
| Version | 20091109 |
| Description | This is the code representing the clinical specialty of the clinician or provider who interacted with, treated, or provided a service to/for the patient. The value set used for clinical specialty has been limited by HITSP to the value set reproduced from HITSP C80 Table 2-149 Clinical Specialty Value Set Definition. |
| Status | `Active` |
| Has Escape Valve Code | `` |
| Database Key | `1089` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Appointment` | `Appointment.specialty` | `http://hl7.org/fhir/ValueSet/c80-practice-codes` | `Preferred` | The specialty of a practitioner that would be required to perform the service requested in this appointment |
| `http://hl7.org/fhir/StructureDefinition/DocumentReference` | `DocumentReference.context.practiceSetting` | `http://hl7.org/fhir/ValueSet/c80-practice-codes` | `Example` | Additional details about where the content was created (e.g. clinical specialty) |
| `http://hl7.org/fhir/StructureDefinition/HealthcareService` | `HealthcareService.specialty` | `http://hl7.org/fhir/ValueSet/c80-practice-codes` | `Preferred` | Specialties handled by the HealthcareService |
| `http://hl7.org/fhir/StructureDefinition/PractitionerRole` | `PractitionerRole.specialty` | `http://hl7.org/fhir/ValueSet/c80-practice-codes` | `Preferred` | Specific specialty of the practitioner |
| `http://hl7.org/fhir/StructureDefinition/ReferralRequest` | `ReferralRequest.serviceRequested` | `http://hl7.org/fhir/ValueSet/c80-practice-codes` | `Example` | Actions requested as part of the referral |
| `http://hl7.org/fhir/StructureDefinition/Schedule` | `Schedule.specialty` | `http://hl7.org/fhir/ValueSet/c80-practice-codes` | `Preferred` | The specialty of a practitioner that would be required to perform the service requested in this appointment |
| `http://hl7.org/fhir/StructureDefinition/Slot` | `Slot.specialty` | `http://hl7.org/fhir/ValueSet/c80-practice-codes` | `Preferred` | The specialty of a practitioner that would be required to perform the service requested in this appointment |

### Expansion Failure

Failed to expand this value set: Expansion is limited
