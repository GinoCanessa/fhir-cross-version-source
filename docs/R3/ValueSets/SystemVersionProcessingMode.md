Comparison of 
Generated at Tuesday, April 1, 2025 1:39:11 PM

### SystemVersionProcessingMode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | SystemVersionProcessingMode |
| Canonical URL | `http://hl7.org/fhir/ValueSet/system-version-processing-mode` |
| Version | 3.0.2 |
| Description | How to manage the intersection between a fixed version in a value set, and a fixed version of the system in the expansion profile |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1507` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ExpansionProfile` | `ExpansionProfile.fixedVersion.mode` | `http://hl7.org/fhir/ValueSet/system-version-processing-mode` | `Required` | default \| check \| override |

### Referenced Systems

* `http://hl7.org/fhir/system-version-processing-mode`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/system-version-processing-mode` | `check` | Check ValueSet Version |
| `http://hl7.org/fhir/system-version-processing-mode` | `default` | Default Version |
| `http://hl7.org/fhir/system-version-processing-mode` | `override` | Override ValueSet Version |
