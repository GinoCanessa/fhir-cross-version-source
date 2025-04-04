Comparison of 
Generated at Friday, April 4, 2025 2:58:59 PM

### PermissionRuleCombining

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | PermissionRuleCombining |
| Canonical URL | `http://hl7.org/fhir/ValueSet/permission-rule-combining` |
| Version | 5.0.0 |
| Description | Codes identifying rule combining algorithm. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4792` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Permission` | `Permission.combining` | `http://hl7.org/fhir/ValueSet/permission-rule-combining\|5.0.0` | `Required` | deny-overrides \| permit-overrides \| ordered-deny-overrides \| ordered-permit-overrides \| deny-unless-permit \| permit-unless-deny |

### Referenced Systems

* `http://hl7.org/fhir/permission-rule-combining`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/permission-rule-combining` | `deny-overrides` | Deny-overrides |
| `http://hl7.org/fhir/permission-rule-combining` | `deny-unless-permit` | Deny-unless-permit |
| `http://hl7.org/fhir/permission-rule-combining` | `ordered-deny-overrides` | Ordered-deny-overrides |
| `http://hl7.org/fhir/permission-rule-combining` | `ordered-permit-overrides` | Ordered-permit-overrides |
| `http://hl7.org/fhir/permission-rule-combining` | `permit-overrides` | Permit-overrides |
| `http://hl7.org/fhir/permission-rule-combining` | `permit-unless-deny` | Permit-unless-deny |
