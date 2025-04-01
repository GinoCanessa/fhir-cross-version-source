Comparison of 
Generated at Tuesday, April 1, 2025 1:39:11 PM

### Funds Reservation Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Funds Reservation Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/fundsreserve` |
| Version | 3.0.2 |
| Description | This value set includes sample funds reservation type codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1250` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.fundsReserve` | `http://hl7.org/fhir/ValueSet/fundsreserve` | `Example` | Funds requested to be reserved |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.reserved` | `http://hl7.org/fhir/ValueSet/fundsreserve` | `Example` | Funds reserved status |

### Referenced Systems

* `http://hl7.org/fhir/fundsreserve`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/fundsreserve` | `none` | None |
| `http://hl7.org/fhir/fundsreserve` | `patient` | Patient |
| `http://hl7.org/fhir/fundsreserve` | `provider` | Provider |
