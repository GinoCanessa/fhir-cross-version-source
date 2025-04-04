Comparison of 
Generated at Friday, April 4, 2025 2:58:59 PM

### TriggeredBytype

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | TriggeredBytype |
| Canonical URL | `http://hl7.org/fhir/ValueSet/observation-triggeredbytype` |
| Version | 5.0.0 |
| Description | Codes providing the type of triggeredBy observation. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `4766` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Observation` | `Observation.triggeredBy.type` | `http://hl7.org/fhir/ValueSet/observation-triggeredbytype\|5.0.0` | `Required` | reflex \| repeat \| re-run |

### Referenced Systems

* `http://hl7.org/fhir/observation-triggeredbytype`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/observation-triggeredbytype` | `re-run` | Re-run (per policy) |
| `http://hl7.org/fhir/observation-triggeredbytype` | `reflex` | Reflex |
| `http://hl7.org/fhir/observation-triggeredbytype` | `repeat` | Repeat (per policy) |
