Comparison of 
Generated at Friday, April 4, 2025 2:58:51 PM

### ResourceSecurityCategory

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ResourceSecurityCategory |
| Canonical URL | `http://hl7.org/fhir/ValueSet/resource-security-category` |
| Version | 4.3.0 |
| Description | Codes indicating how resources behave from a security perspective |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `4067` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/structuredefinition-security-category` | `Extension.value[x]` | `http://hl7.org/fhir/ValueSet/resource-security-category` | `Required` | Value of extension |

### Referenced Systems

* `http://hl7.org/fhir/resource-security-category`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/resource-security-category` | `anonymous` | Anonymous READ Access Resource |
| `http://hl7.org/fhir/resource-security-category` | `business` | Business Sensitive Resource |
| `http://hl7.org/fhir/resource-security-category` | `individual` | Individual Sensitive Resource |
| `http://hl7.org/fhir/resource-security-category` | `not-classified` | Not classified |
| `http://hl7.org/fhir/resource-security-category` | `patient` | Patient Sensitive |
