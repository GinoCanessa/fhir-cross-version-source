Comparison of 
Generated at Thursday, April 3, 2025 8:18:16 AM

### SmartCapabilities

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | SmartCapabilities |
| Canonical URL | `http://hl7.org/fhir/ValueSet/smart-capabilities` |
| Version | 4.0.1 |
| Description | Codes that define what the server is capable of. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2763` |
| Database Concept Count | `14` |
| Database Active Concept Count | `14` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://fhir-registry.smarthealthit.org/StructureDefinition/capabilities` | `Extension.value[x]` | `http://hl7.org/fhir/ValueSet/smart-capabilities\|4.0.1` | `Required` | Value of extension |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/smart-capabilities`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/smart-capabilities` | `client-confidential-symmetric` | Confidential Client Profile |
| `http://terminology.hl7.org/CodeSystem/smart-capabilities` | `client-public` | Public Client Profile |
| `http://terminology.hl7.org/CodeSystem/smart-capabilities` | `context-ehr-encounter` | Allows "Encounter Level Launch Context (EHR)" |
| `http://terminology.hl7.org/CodeSystem/smart-capabilities` | `context-ehr-patient` | Allows "Patient Level Launch Context (EHR)" |
| `http://terminology.hl7.org/CodeSystem/smart-capabilities` | `context-passthrough-banner` | Allows "Need Patient Banner" |
| `http://terminology.hl7.org/CodeSystem/smart-capabilities` | `context-passthrough-style` | Allows "Smart Style Style" |
| `http://terminology.hl7.org/CodeSystem/smart-capabilities` | `context-standalone-encounter` | Allows "Encounter Level Launch Context (STANDALONE)" |
| `http://terminology.hl7.org/CodeSystem/smart-capabilities` | `context-standalone-patient` | Allows "Patient Level Launch Context (STANDALONE)" |
| `http://terminology.hl7.org/CodeSystem/smart-capabilities` | `launch-ehr` | EHR Launch Mode |
| `http://terminology.hl7.org/CodeSystem/smart-capabilities` | `launch-standalone` | Standalone Launch Mode |
| `http://terminology.hl7.org/CodeSystem/smart-capabilities` | `permission-offline` | Supports Refresh Token |
| `http://terminology.hl7.org/CodeSystem/smart-capabilities` | `permission-patient` | Supports Patient Level Scopes |
| `http://terminology.hl7.org/CodeSystem/smart-capabilities` | `permission-user` | Supports User Level Scopes |
| `http://terminology.hl7.org/CodeSystem/smart-capabilities` | `sso-openid-connect` | Supports OpenID Connect |
