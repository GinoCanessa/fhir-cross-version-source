Comparison of 
Generated at Tuesday, April 1, 2025 1:39:17 PM

### FocalSubjectCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | FocalSubjectCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/focal-subject` |
| Version | 4.0.1 |
| Description | Example value set composed from SNOMED CT and HL7 V3 codes for observation targets such as donor, fetus or spouse. As use cases are discovered, more values may be added. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2463` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/observation-focusCode` | `Extension.value[x]` | `http://hl7.org/fhir/ValueSet/focal-subject` | `Example` | Value of extension |

### Referenced Systems

* `http://snomed.info/sct`
* `http://terminology.hl7.org/CodeSystem/v3-ParticipationType`
* `http://terminology.hl7.org/CodeSystem/v3-RoleCode`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://snomed.info/sct` | `83418008` | Fetus |
| `http://terminology.hl7.org/CodeSystem/v3-ParticipationType` | `DON` | donor |
| `http://terminology.hl7.org/CodeSystem/v3-RoleCode` | `SPS` | spouse |
