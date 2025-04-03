Comparison of 
Generated at Thursday, April 3, 2025 8:18:31 AM

### TransportCode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | TransportCode |
| Canonical URL | `http://hl7.org/fhir/ValueSet/transport-code` |
| Version | 5.0.0 |
| Description | Codes indicating the type of action that is expected to be performed |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `4977` |
| Database Concept Count | `8` |
| Database Active Concept Count | `8` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Transport` | `Transport.code` | `http://hl7.org/fhir/ValueSet/transport-code` | `Example` | Transport Type |

### Referenced Systems

* `http://hl7.org/fhir/CodeSystem/transport-code`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/CodeSystem/transport-code` | `abort` | Mark the focal resource as no longer active |
| `http://hl7.org/fhir/CodeSystem/transport-code` | `approve` | Activate/approve the focal resource |
| `http://hl7.org/fhir/CodeSystem/transport-code` | `change` | Change the focal resource |
| `http://hl7.org/fhir/CodeSystem/transport-code` | `fulfill` | Fulfill the focal request |
| `http://hl7.org/fhir/CodeSystem/transport-code` | `instantiate` | Instantiate the focal definition |
| `http://hl7.org/fhir/CodeSystem/transport-code` | `replace` | Replace the focal resource with the input resource |
| `http://hl7.org/fhir/CodeSystem/transport-code` | `resume` | Re-activate the focal resource |
| `http://hl7.org/fhir/CodeSystem/transport-code` | `suspend` | Suspend the focal resource |
