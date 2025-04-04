Comparison of 
Generated at Friday, April 4, 2025 2:58:58 PM

### FundsReservationCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | FundsReservationCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/fundsreserve` |
| Version | 5.0.0 |
| Description | This value set includes sample funds reservation type codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4581` |
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
