Comparison of 
Generated at Tuesday, April 1, 2025 1:39:26 PM

### ContactEntityType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ContactEntityType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/contactentity-type` |
| Version | 4.3.0 |
| Description | This example value set defines a set of codes that can be used to indicate the purpose for which you would contact a contact party. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `3648` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/InsurancePlan` | `InsurancePlan.contact.purpose` | `http://hl7.org/fhir/ValueSet/contactentity-type` | `Extensible` | The type of contact |
| `http://hl7.org/fhir/StructureDefinition/Organization` | `Organization.contact.purpose` | `http://hl7.org/fhir/ValueSet/contactentity-type` | `Extensible` | The type of contact |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/contactentity-type`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/contactentity-type` | `ADMIN` | Administrative |
| `http://terminology.hl7.org/CodeSystem/contactentity-type` | `BILL` | Billing |
| `http://terminology.hl7.org/CodeSystem/contactentity-type` | `HR` | Human Resource |
| `http://terminology.hl7.org/CodeSystem/contactentity-type` | `PATINF` | Patient |
| `http://terminology.hl7.org/CodeSystem/contactentity-type` | `PAYOR` | Payor |
| `http://terminology.hl7.org/CodeSystem/contactentity-type` | `PRESS` | Press |
