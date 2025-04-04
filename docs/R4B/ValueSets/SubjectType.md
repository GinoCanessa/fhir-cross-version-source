Comparison of 
Generated at Friday, April 4, 2025 2:58:51 PM

### SubjectType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | SubjectType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/subject-type` |
| Version | 4.3.0 |
| Description | Possible types of subjects. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4118` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DataRequirement` | `DataRequirement.subject[x]` | `http://hl7.org/fhir/ValueSet/subject-type` | `Extensible` | E.g. Patient, Practitioner, RelatedPerson, Organization, Location, Device |
| `http://hl7.org/fhir/StructureDefinition/ActivityDefinition` | `ActivityDefinition.subject[x]` | `http://hl7.org/fhir/ValueSet/subject-type` | `Extensible` | Type of individual the activity definition is intended for |
| `http://hl7.org/fhir/StructureDefinition/EventDefinition` | `EventDefinition.subject[x]` | `http://hl7.org/fhir/ValueSet/subject-type` | `Extensible` | Type of individual the event definition is focused on |
| `http://hl7.org/fhir/StructureDefinition/Library` | `Library.subject[x]` | `http://hl7.org/fhir/ValueSet/subject-type` | `Extensible` | Type of individual the library content is focused on |
| `http://hl7.org/fhir/StructureDefinition/Measure` | `Measure.subject[x]` | `http://hl7.org/fhir/ValueSet/subject-type` | `Extensible` | E.g. Patient, Practitioner, RelatedPerson, Organization, Location, Device |
| `http://hl7.org/fhir/StructureDefinition/PlanDefinition` | `PlanDefinition.subject[x]` | `http://hl7.org/fhir/ValueSet/subject-type` | `Extensible` | Type of individual the plan definition is focused on |
| `http://hl7.org/fhir/StructureDefinition/PlanDefinition` | `PlanDefinition.action.subject[x]` | `http://hl7.org/fhir/ValueSet/subject-type` | `Extensible` | Type of individual the action is focused on |
| `http://hl7.org/fhir/StructureDefinition/ResearchDefinition` | `ResearchDefinition.subject[x]` | `http://hl7.org/fhir/ValueSet/subject-type` | `Extensible` | E.g. Patient, Practitioner, RelatedPerson, Organization, Location, Device |
| `http://hl7.org/fhir/StructureDefinition/ResearchElementDefinition` | `ResearchElementDefinition.subject[x]` | `http://hl7.org/fhir/ValueSet/subject-type` | `Extensible` | E.g. Patient, Practitioner, RelatedPerson, Organization, Location, Device |

### Referenced Systems

* `http://hl7.org/fhir/resource-types`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/resource-types` | `Device` | Device |
| `http://hl7.org/fhir/resource-types` | `Location` | Location |
| `http://hl7.org/fhir/resource-types` | `Organization` | Organization |
| `http://hl7.org/fhir/resource-types` | `Patient` | Patient |
| `http://hl7.org/fhir/resource-types` | `Practitioner` | Practitioner |
