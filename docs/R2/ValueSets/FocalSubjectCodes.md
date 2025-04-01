Comparison of 
Generated at Tuesday, April 1, 2025 1:39:06 PM

### Focal Subject Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Focal Subject Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/focal-subject` |
| Version | 1.0.2 |
| Description | Example VS composed from SNOMED CT and HL7 v3 codes for observation targets: donor, fetus, spouse. As use cases are discovered more values may be added. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `171` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/observation-focal-subject` | `Extension.valueCodeableConcept` | `http://hl7.org/fhir/ValueSet/focal-subject` | `Example` | Value of extension |

### Referenced Systems

* `http://snomed.info/sct`
* `http://hl7.org/fhir/v3/ParticipationType`
* `http://hl7.org/fhir/v3/RoleCode`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/v3/ParticipationType` | `DON` | donor |
| `http://hl7.org/fhir/v3/RoleCode` | `SPS` | spouse |
| `http://snomed.info/sct` | `83418008` | Fetus |
