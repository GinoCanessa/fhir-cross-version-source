Comparison of 
Generated at Thursday, April 3, 2025 8:18:23 AM

### Funds Reservation Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | Funds Reservation Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/fundsreserve` |
| Version | 4.3.0 |
| Description | This value set includes sample funds reservation type codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3791` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.fundsReserve` | `http://hl7.org/fhir/ValueSet/fundsreserve` | `Example` | For whom to reserve funds |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.fundsReserve` | `http://hl7.org/fhir/ValueSet/fundsreserve` | `Example` | Funds reserved status |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.fundsReserveRequested` | `http://hl7.org/fhir/ValueSet/fundsreserve` | `Example` | For whom to reserve funds |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.fundsReserve` | `http://hl7.org/fhir/ValueSet/fundsreserve` | `Example` | Funds reserved status |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/fundsreserve`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/fundsreserve` | `none` | None |
| `http://terminology.hl7.org/CodeSystem/fundsreserve` | `patient` | Patient |
| `http://terminology.hl7.org/CodeSystem/fundsreserve` | `provider` | Provider |
