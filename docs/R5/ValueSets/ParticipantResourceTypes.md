Comparison of 
Generated at Friday, April 4, 2025 2:58:58 PM

### ParticipantResourceTypes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ParticipantResourceTypes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/participant-resource-types` |
| Version | 5.0.0 |
| Description | All Resource Types that represent participant resources |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `4778` |
| Database Concept Count | `10` |
| Database Active Concept Count | `10` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DataRequirement` | `DataRequirement.subject[x]` | `http://hl7.org/fhir/ValueSet/participant-resource-types` | `Extensible` | E.g. Patient, Practitioner, RelatedPerson, Organization, Location, Device |
| `http://hl7.org/fhir/StructureDefinition/ActivityDefinition` | `ActivityDefinition.subject[x]` | `http://hl7.org/fhir/ValueSet/participant-resource-types` | `Extensible` | Type of individual the activity definition is intended for |
| `http://hl7.org/fhir/StructureDefinition/EventDefinition` | `EventDefinition.subject[x]` | `http://hl7.org/fhir/ValueSet/participant-resource-types` | `Extensible` | Type of individual the event definition is focused on |
| `http://hl7.org/fhir/StructureDefinition/Library` | `Library.subject[x]` | `http://hl7.org/fhir/ValueSet/participant-resource-types` | `Extensible` | Type of individual the library content is focused on |
| `http://hl7.org/fhir/StructureDefinition/Measure` | `Measure.subject[x]` | `http://hl7.org/fhir/ValueSet/participant-resource-types` | `Extensible` | E.g. Patient, Practitioner, RelatedPerson, Organization, Location, Device |
| `http://hl7.org/fhir/StructureDefinition/Measure` | `Measure.group.subject[x]` | `http://hl7.org/fhir/ValueSet/participant-resource-types` | `Extensible` | E.g. Patient, Practitioner, RelatedPerson, Organization, Location, Device |
| `http://hl7.org/fhir/StructureDefinition/PlanDefinition` | `PlanDefinition.subject[x]` | `http://hl7.org/fhir/ValueSet/participant-resource-types` | `Extensible` | Type of individual the plan definition is focused on |
| `http://hl7.org/fhir/StructureDefinition/PlanDefinition` | `PlanDefinition.action.subject[x]` | `http://hl7.org/fhir/ValueSet/participant-resource-types` | `Extensible` | Type of individual the action is focused on |

### Referenced Systems

* `http://hl7.org/fhir/fhir-types`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/fhir-types` | `CareTeam` | CareTeam |
| `http://hl7.org/fhir/fhir-types` | `Device` | Device |
| `http://hl7.org/fhir/fhir-types` | `Group` | Group |
| `http://hl7.org/fhir/fhir-types` | `HealthcareService` | HealthcareService |
| `http://hl7.org/fhir/fhir-types` | `Location` | Location |
| `http://hl7.org/fhir/fhir-types` | `Organization` | Organization |
| `http://hl7.org/fhir/fhir-types` | `Patient` | Patient |
| `http://hl7.org/fhir/fhir-types` | `Practitioner` | Practitioner |
| `http://hl7.org/fhir/fhir-types` | `PractitionerRole` | PractitionerRole |
| `http://hl7.org/fhir/fhir-types` | `RelatedPerson` | RelatedPerson |
