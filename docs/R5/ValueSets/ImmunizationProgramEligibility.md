Comparison of 
Generated at Tuesday, April 1, 2025 1:39:34 PM

### ImmunizationProgramEligibility

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ImmunizationProgramEligibility |
| Canonical URL | `http://hl7.org/fhir/ValueSet/immunization-program-eligibility` |
| Version | 5.0.0 |
| Description | The value set to instantiate this attribute should be drawn from a terminologically robust code system that consists of or contains concepts to support describing the patient's eligibility for a vaccination program. This value set is provided as a suggestive example. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4621` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Immunization` | `Immunization.programEligibility.programStatus` | `http://hl7.org/fhir/ValueSet/immunization-program-eligibility` | `Example` | The patient's eligibility status for the program |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/immunization-program-eligibility`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/immunization-program-eligibility` | `ineligible` | Not Eligible |
| `http://terminology.hl7.org/CodeSystem/immunization-program-eligibility` | `uninsured` | Uninsured |
