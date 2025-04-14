Comparison of 
Generated at Monday, April 14, 2025 6:17:28 PM

### ResourceSecurityCategory

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ResourceSecurityCategory |
| Canonical URL | `http://hl7.org/fhir/ValueSet/resource-security-category` |
| Version | 4.0.1 |
| Description | Provides general guidance around the kind of access Control to Read, Search, Create, Update, or Delete a resource. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2722` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/structuredefinition-security-category` | `Extension.value[x]` | `http://hl7.org/fhir/ValueSet/resource-security-category\|4.0.1` | `Required` | Value of extension |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/resource-security-category`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/resource-security-category` | `anonymous` | Anonymous READ Access Resource |
| `http://terminology.hl7.org/CodeSystem/resource-security-category` | `business` | Business Sensitive Resource |
| `http://terminology.hl7.org/CodeSystem/resource-security-category` | `individual` | Individual Sensitive Resource |
| `http://terminology.hl7.org/CodeSystem/resource-security-category` | `not-classified` | Not classified |
| `http://terminology.hl7.org/CodeSystem/resource-security-category` | `patient` | Patient Sensitive |
