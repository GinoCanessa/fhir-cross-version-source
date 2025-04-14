Comparison of 
Generated at Monday, April 14, 2025 6:17:44 PM

### SecurityLabelExamples

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | SecurityLabelExamples |
| Canonical URL | `http://hl7.org/fhir/ValueSet/security-label-examples` |
| Version | 5.0.0 |
| Description | A sample of security labels from [Healthcare Privacy and Security Classification System](security-labels.html#hcs) as the combination of data and event codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4888` |
| Database Concept Count | `11` |
| Database Active Concept Count | `11` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AuditEvent` | `AuditEvent.entity.securityLabel` | `http://hl7.org/fhir/ValueSet/security-label-examples` | `Example` | Security labels on the entity |
| `http://hl7.org/fhir/StructureDefinition/Consent` | `Consent.provision.securityLabel` | `http://hl7.org/fhir/ValueSet/security-label-examples` | `Example` | Security Labels that define affected resources |
| `http://hl7.org/fhir/StructureDefinition/DocumentReference` | `DocumentReference.securityLabel` | `http://hl7.org/fhir/ValueSet/security-label-examples` | `Example` | Document security-tags |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-Confidentiality`
* `http://terminology.hl7.org/CodeSystem/v3-ActCode`
* `http://terminology.hl7.org/CodeSystem/v3-ActReason`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `DELAU` | delete after use |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `ETH` | substance abuse information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NOAUTH` | no disclosure without subject authorization |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `NORDSCLCD` | no redisclosure without consent directive |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `PSY` | psychiatry disorder information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActCode` | `STD` | sexually transmitted disease information sensitivity |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `ETREAT` | Emergency Treatment |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `HPAYMT` | healthcare payment |
| `http://terminology.hl7.org/CodeSystem/v3-ActReason` | `TREAT` | treatment |
| `http://terminology.hl7.org/CodeSystem/v3-Confidentiality` | `N` | normal |
| `http://terminology.hl7.org/CodeSystem/v3-Confidentiality` | `R` | restricted |
