Comparison of 
Generated at Friday, April 4, 2025 2:58:58 PM

### ExampleProviderQualificationCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ExampleProviderQualificationCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/provider-qualification` |
| Version | 5.0.0 |
| Description | This value set includes sample Provider Qualification codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4816` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.careTeam.specialty` | `http://hl7.org/fhir/ValueSet/provider-qualification` | `Example` | Practitioner or provider specialization |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.careTeam.specialty` | `http://hl7.org/fhir/ValueSet/provider-qualification` | `Example` | Practitioner or provider specialization |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/ex-providerqualification`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/ex-providerqualification` | `311405` | Dentist |
| `http://terminology.hl7.org/CodeSystem/ex-providerqualification` | `604210` | Optometrist |
| `http://terminology.hl7.org/CodeSystem/ex-providerqualification` | `604215` | Ophthalmologist |
