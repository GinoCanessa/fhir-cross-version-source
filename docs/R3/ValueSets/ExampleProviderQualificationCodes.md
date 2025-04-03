Comparison of 
Generated at Thursday, April 3, 2025 8:18:10 AM

### Example Provider Qualification Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Example Provider Qualification Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/provider-qualification` |
| Version | 3.0.2 |
| Description | This value set includes sample Provider Qualification codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1411` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.careTeam.qualification` | `http://hl7.org/fhir/ValueSet/provider-qualification` | `Example` | Type, classification or Specialization |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.careTeam.qualification` | `http://hl7.org/fhir/ValueSet/provider-qualification` | `Example` | Type, classification or Specialization |

### Referenced Systems

* `http://hl7.org/fhir/ex-providerqualification`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/ex-providerqualification` | `311405` | Dentist |
| `http://hl7.org/fhir/ex-providerqualification` | `604210` | Optometrist |
| `http://hl7.org/fhir/ex-providerqualification` | `604215` | Ophthalmologist |
