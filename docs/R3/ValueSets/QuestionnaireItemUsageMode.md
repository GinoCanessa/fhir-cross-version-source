Comparison of 
Generated at Tuesday, April 1, 2025 1:39:11 PM

### QuestionnaireItemUsageMode

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | QuestionnaireItemUsageMode |
| Canonical URL | `http://hl7.org/fhir/ValueSet/questionnaire-usage-mode` |
| Version | 3.0.2 |
| Description | Identifies the modes of usage of a questionnaire that should enable a particular questionnaire item |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1423` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/questionnaire-usageMode` | `Extension.valueCode` | `http://hl7.org/fhir/ValueSet/questionnaire-usage-mode` | `Required` | Value of extension |

### Referenced Systems

* `http://hl7.org/fhir/questionnaire-usage-mode`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/questionnaire-usage-mode` | `capture` | Capture Only |
| `http://hl7.org/fhir/questionnaire-usage-mode` | `capture-display` | Capture & Display |
| `http://hl7.org/fhir/questionnaire-usage-mode` | `capture-display-non-empty` | Capture or, if answered, Display |
| `http://hl7.org/fhir/questionnaire-usage-mode` | `display` | Display Only |
| `http://hl7.org/fhir/questionnaire-usage-mode` | `display-non-empty` | Display when Answered |
