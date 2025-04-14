Comparison of 
Generated at Monday, April 14, 2025 6:17:35 PM

### ExampleProviderQualificationCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ExampleProviderQualificationCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/provider-qualification` |
| Version | 4.3.0 |
| Description | This value set includes sample Provider Qualification codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4014` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.careTeam.qualification` | `http://hl7.org/fhir/ValueSet/provider-qualification` | `Example` | Practitioner credential or specialization |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.careTeam.qualification` | `http://hl7.org/fhir/ValueSet/provider-qualification` | `Example` | Practitioner credential or specialization |

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
