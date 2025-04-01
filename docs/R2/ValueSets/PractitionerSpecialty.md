Comparison of 
Generated at Tuesday, April 1, 2025 1:39:05 PM

### PractitionerSpecialty

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | PractitionerSpecialty |
| Canonical URL | `http://hl7.org/fhir/ValueSet/practitioner-specialty` |
| Version | 1.0.2 |
| Description | This example value set defines a set of codes that can be used to indicate the specialty of a Practitioner. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `280` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Practitioner` | `Practitioner.practitionerRole.specialty` | `http://hl7.org/fhir/ValueSet/practitioner-specialty` | `Example` | Specific specialty of the practitioner |
| `http://hl7.org/fhir/StructureDefinition/ReferralRequest` | `ReferralRequest.specialty` | `http://hl7.org/fhir/ValueSet/practitioner-specialty` | `Example` | The clinical specialty (discipline) that the referral is requested for |

### Referenced Systems

* `http://hl7.org/fhir/practitioner-specialty`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/practitioner-specialty` | `cardio` | Cardiologist |
| `http://hl7.org/fhir/practitioner-specialty` | `dent` | Dentist |
| `http://hl7.org/fhir/practitioner-specialty` | `dietary` | Dietary consultant |
| `http://hl7.org/fhir/practitioner-specialty` | `midw` | Midwife |
| `http://hl7.org/fhir/practitioner-specialty` | `sysarch` | Systems architect |
