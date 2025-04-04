Comparison of 
Generated at Friday, April 4, 2025 2:58:31 PM

### AnimalSpecies

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | AnimalSpecies |
| Canonical URL | `http://hl7.org/fhir/ValueSet/animal-species` |
| Version | 1.0.2 |
| Description | This example value set defines a set of codes that can be used to indicate species of animal patients. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `19` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Patient` | `Patient.animal.species` | `http://hl7.org/fhir/ValueSet/animal-species` | `Example` | E.g. Dog, Cow |
| `http://hl7.org/fhir/StructureDefinition/practitioner-animalSpecies` | `Extension.valueCodeableConcept` | `http://hl7.org/fhir/ValueSet/animal-species` | `Example` | Value of extension |

### Referenced Systems

* `http://hl7.org/fhir/animal-species`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/animal-species` | `canislf` | Dog |
| `http://hl7.org/fhir/animal-species` | `ovisa` | Sheep |
| `http://hl7.org/fhir/animal-species` | `serinuscd` | Domestic Canary |
