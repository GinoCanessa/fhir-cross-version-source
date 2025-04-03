Comparison of 
Generated at Thursday, April 3, 2025 8:18:32 AM

### ConsentActionCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ConsentActionCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/consent-action` |
| Version | 5.0.0 |
| Description | This value set includes sample Consent Action codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4408` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Consent` | `Consent.provision.action` | `http://hl7.org/fhir/ValueSet/consent-action` | `Example` | Actions controlled by this provision |
| `http://hl7.org/fhir/StructureDefinition/Permission` | `Permission.rule.activity.action` | `http://hl7.org/fhir/ValueSet/consent-action` | `Example` | Actions controlled by this rule |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/consentaction`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/consentaction` | `access` | Access |
| `http://terminology.hl7.org/CodeSystem/consentaction` | `collect` | Collect |
| `http://terminology.hl7.org/CodeSystem/consentaction` | `correct` | Access and Correct |
| `http://terminology.hl7.org/CodeSystem/consentaction` | `disclose` | Disclose |
| `http://terminology.hl7.org/CodeSystem/consentaction` | `use` | Use |
