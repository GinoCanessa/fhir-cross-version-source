Comparison of 
Generated at Tuesday, April 1, 2025 1:39:18 PM

### QuestionnaireItemUsageMode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | QuestionnaireItemUsageMode |
| Canonical URL | `http://hl7.org/fhir/ValueSet/questionnaire-usage-mode` |
| Version | 4.0.1 |
| Description | Identifies the modes of usage of a questionnaire that should enable a particular questionnaire item. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2684` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/questionnaire-usageMode` | `Extension.value[x]` | `http://hl7.org/fhir/ValueSet/questionnaire-usage-mode\|4.0.1` | `Required` | Value of extension |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/questionnaire-usage-mode`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/questionnaire-usage-mode` | `capture` | Capture Only |
| `http://terminology.hl7.org/CodeSystem/questionnaire-usage-mode` | `capture-display` | Capture & Display |
| `http://terminology.hl7.org/CodeSystem/questionnaire-usage-mode` | `capture-display-non-empty` | Capture or, if answered, Display |
| `http://terminology.hl7.org/CodeSystem/questionnaire-usage-mode` | `display` | Display Only |
| `http://terminology.hl7.org/CodeSystem/questionnaire-usage-mode` | `display-non-empty` | Display when Answered |
