Comparison of 
Generated at Thursday, April 3, 2025 8:18:31 AM

### TransportIntent

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | TransportIntent |
| Canonical URL | `http://hl7.org/fhir/ValueSet/transport-intent` |
| Version | 5.0.0 |
| Description | Distinguishes whether the transport is a proposal, plan or full order. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `4978` |
| Database Concept Count | `9` |
| Database Active Concept Count | `9` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Transport` | `Transport.intent` | `http://hl7.org/fhir/ValueSet/transport-intent\|5.0.0` | `Required` | unknown \| proposal \| plan \| order \| original-order \| reflex-order \| filler-order \| instance-order \| option |

### Referenced Systems

* `http://hl7.org/fhir/transport-intent`
* `http://hl7.org/fhir/request-intent`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/request-intent` | `filler-order` | Filler Order |
| `http://hl7.org/fhir/request-intent` | `instance-order` | Instance Order |
| `http://hl7.org/fhir/request-intent` | `option` | Option |
| `http://hl7.org/fhir/request-intent` | `order` | Order |
| `http://hl7.org/fhir/request-intent` | `original-order` | Original Order |
| `http://hl7.org/fhir/request-intent` | `plan` | Plan |
| `http://hl7.org/fhir/request-intent` | `proposal` | Proposal |
| `http://hl7.org/fhir/request-intent` | `reflex-order` | Reflex Order |
| `http://hl7.org/fhir/transport-intent` | `unknown` | Unknown |
