Comparison of 
Generated at Monday, April 14, 2025 6:17:34 PM

### ExampleServicePlaceCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ExampleServicePlaceCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/service-place` |
| Version | 4.3.0 |
| Description | This value set includes a smattering of Service Place codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4091` |
| Database Concept Count | `17` |
| Database Active Concept Count | `17` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.location[x]` | `http://hl7.org/fhir/ValueSet/service-place` | `Example` | Place of service or where product was supplied |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.addItem.location[x]` | `http://hl7.org/fhir/ValueSet/service-place` | `Example` | Place of service or where product was supplied |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.location[x]` | `http://hl7.org/fhir/ValueSet/service-place` | `Example` | Place of service or where product was supplied |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.addItem.location[x]` | `http://hl7.org/fhir/ValueSet/service-place` | `Example` | Place of service or where product was supplied |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/ex-serviceplace`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/ex-serviceplace` | `01` | Pharmacy |
| `http://terminology.hl7.org/CodeSystem/ex-serviceplace` | `03` | School |
| `http://terminology.hl7.org/CodeSystem/ex-serviceplace` | `04` | Homeless Shelter |
| `http://terminology.hl7.org/CodeSystem/ex-serviceplace` | `05` | Indian Health Service Free-standing Facility |
| `http://terminology.hl7.org/CodeSystem/ex-serviceplace` | `06` | Indian Health Service Provider-based Facility |
| `http://terminology.hl7.org/CodeSystem/ex-serviceplace` | `07` | Tribal 638 Free-Standing Facility |
| `http://terminology.hl7.org/CodeSystem/ex-serviceplace` | `08` | Tribal 638 Provider-Based Facility |
| `http://terminology.hl7.org/CodeSystem/ex-serviceplace` | `09` | Prison/Correctional Facility |
| `http://terminology.hl7.org/CodeSystem/ex-serviceplace` | `11` | Office |
| `http://terminology.hl7.org/CodeSystem/ex-serviceplace` | `12` | Home |
| `http://terminology.hl7.org/CodeSystem/ex-serviceplace` | `13` | Assisted Living Fa |
| `http://terminology.hl7.org/CodeSystem/ex-serviceplace` | `14` | Group Home |
| `http://terminology.hl7.org/CodeSystem/ex-serviceplace` | `15` | Mobile Unit |
| `http://terminology.hl7.org/CodeSystem/ex-serviceplace` | `19` | Off Campus-Outpatient Hospital |
| `http://terminology.hl7.org/CodeSystem/ex-serviceplace` | `20` | Urgent Care Facility |
| `http://terminology.hl7.org/CodeSystem/ex-serviceplace` | `21` | Inpatient Hospital |
| `http://terminology.hl7.org/CodeSystem/ex-serviceplace` | `41` | Ambulance—Land |
