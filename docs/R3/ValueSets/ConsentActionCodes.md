Comparison of 
Generated at Tuesday, April 1, 2025 1:39:10 PM

### Consent Action Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Consent Action Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/consent-action` |
| Version | 3.0.2 |
| Description | This value set includes sample Consent Action codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1140` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Consent` | `Consent.action` | `http://hl7.org/fhir/ValueSet/consent-action` | `Example` | Actions controlled by this consent |
| `http://hl7.org/fhir/StructureDefinition/Consent` | `Consent.except.action` | `http://hl7.org/fhir/ValueSet/consent-action` | `Example` | Actions controlled by this exception |

### Referenced Systems

* `http://hl7.org/fhir/consentaction`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/consentaction` | `access` | Access |
| `http://hl7.org/fhir/consentaction` | `collect` | Collect |
| `http://hl7.org/fhir/consentaction` | `correct` | Access and Correct |
| `http://hl7.org/fhir/consentaction` | `disclose` | Disclose |
| `http://hl7.org/fhir/consentaction` | `use` | Use |
