Comparison of 
Generated at Monday, April 14, 2025 6:17:42 PM

### AccountAggregate

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | AccountAggregate |
| Canonical URL | `http://hl7.org/fhir/ValueSet/account-aggregate` |
| Version | 5.0.0 |
| Description | Indicates who is expected to pay a part of the account balance. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4236` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Account` | `Account.balance.aggregate` | `http://hl7.org/fhir/ValueSet/account-aggregate` | `Extensible` | Who is expected to pay this part of the balance |

### Referenced Systems

* `http://hl7.org/fhir/account-aggregate`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/account-aggregate` | `insurance` | Insurance |
| `http://hl7.org/fhir/account-aggregate` | `patient` | Patient |
| `http://hl7.org/fhir/account-aggregate` | `total` | Total |
