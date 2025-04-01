Comparison of 
Generated at Tuesday, April 1, 2025 1:39:34 PM

### Hl7VSVSObservationType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | Hl7VSVSObservationType |
| Canonical URL | `http://terminology.hl7.org/ValueSet/v2-0936` |
| Version | 2.0.0 |
| Description | Value Set of codes that specify types of observations to enable systems to distinguish between observations sent along with an order, versus observations sent as the result to an order. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `5044` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DiagnosticReport` | `DiagnosticReport.supportingInfo.type` | `http://terminology.hl7.org/ValueSet/v2-0936` | `Example` | Supporting information role code |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v2-0936`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v2-0936` | `QST` | Question |
| `http://terminology.hl7.org/CodeSystem/v2-0936` | `RSLT` | Result |
| `http://terminology.hl7.org/CodeSystem/v2-0936` | `SCI` | Supporting Clinical Information |
