Comparison of 
Generated at Thursday, April 3, 2025 8:18:05 AM

### Funds Reservation Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Funds Reservation Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/fundsreserve` |
| Version | 1.0.2 |
| Description | This value set includes sample funds reservation type codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `175` |
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
| `http://hl7.org/fhir/fundsreserve` | `none` |  |
| `http://hl7.org/fhir/fundsreserve` | `patient` |  |
| `http://hl7.org/fhir/fundsreserve` | `provider` |  |
