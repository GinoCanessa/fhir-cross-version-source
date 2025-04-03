Comparison of 
Generated at Thursday, April 3, 2025 8:18:32 AM

### ResearchStudyObjectiveType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ResearchStudyObjectiveType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/research-study-objective-type` |
| Version | 5.0.0 |
| Description | Codes for the kind of study objective. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4861` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ResearchStudy` | `ResearchStudy.objective.type` | `http://hl7.org/fhir/ValueSet/research-study-objective-type` | `Preferred` | primary \| secondary \| exploratory |
| `http://hl7.org/fhir/StructureDefinition/ResearchStudy` | `ResearchStudy.outcomeMeasure.type` | `http://hl7.org/fhir/ValueSet/research-study-objective-type` | `Preferred` | primary \| secondary \| exploratory |

### Referenced Systems

* `http://hl7.org/fhir/research-study-objective-type`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/research-study-objective-type` | `exploratory` | Exploratory |
| `http://hl7.org/fhir/research-study-objective-type` | `primary` | Primary |
| `http://hl7.org/fhir/research-study-objective-type` | `secondary` | Secondary |
