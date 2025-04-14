Comparison of 
Generated at Monday, April 14, 2025 6:17:43 PM

### SecurityLabelEventExamples

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | SecurityLabelEventExamples |
| Canonical URL | `http://hl7.org/fhir/ValueSet/security-label-event-examples` |
| Version | 5.0.0 |
| Description | A sample of security labels from [Healthcare Privacy and Security Classification System](security-labels.html#hcs) that are used on events and requests/responses (aka user context or organization context) made up of PurposeOfUse and maybe a refrain/obligation. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4887` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Permission` | `Permission.rule.limit` | `http://hl7.org/fhir/ValueSet/security-label-event-examples` | `Example` | What limits apply to the use of the data |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-ActReason`
* `http://terminology.hl7.org/CodeSystem/v3-ActCode`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DELAU` | delete after use |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOAUTH` | no disclosure without subject authorization |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NORDSCLCD` | no redisclosure without consent directive |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `ETREAT` | Emergency Treatment |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `HPAYMT` | healthcare payment |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `TREAT` | treatment |
