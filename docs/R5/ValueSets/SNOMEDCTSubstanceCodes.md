Comparison of 
Generated at Tuesday, April 1, 2025 1:39:34 PM

### SNOMEDCTSubstanceCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | SNOMEDCTSubstanceCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/substance-codes` |
| Version | 5.0.0 |
| Description | This value set includes all substance codes from SNOMED CT - provided as an exemplar value set. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `4932` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/AdministrableProductDefinition` | `AdministrableProductDefinition.ingredient` | `http://hl7.org/fhir/ValueSet/substance-codes` | `Example` | The ingredients of this administrable medicinal product. This is only needed if the ingredients are not specified either using ManufacturedItemDefiniton, or using by incoming references from the Ingredient resource |
| `http://hl7.org/fhir/StructureDefinition/Ingredient` | `Ingredient.substance.code` | `http://hl7.org/fhir/ValueSet/substance-codes` | `Example` | A code or full resource that represents the ingredient substance |
| `http://hl7.org/fhir/StructureDefinition/Ingredient` | `Ingredient.substance.strength.referenceStrength.substance` | `http://hl7.org/fhir/ValueSet/substance-codes` | `Example` | Relevant reference substance |
| `http://hl7.org/fhir/StructureDefinition/ManufacturedItemDefinition` | `ManufacturedItemDefinition.ingredient` | `http://hl7.org/fhir/ValueSet/substance-codes` | `Example` | The ingredients of this manufactured item. Only needed if these are not specified by incoming references from the Ingredient resource |
| `http://hl7.org/fhir/StructureDefinition/MedicinalProductDefinition` | `MedicinalProductDefinition.ingredient` | `http://hl7.org/fhir/ValueSet/substance-codes` | `Example` | The ingredients of this medicinal product - when not detailed in other resources |
| `http://hl7.org/fhir/StructureDefinition/MedicinalProductDefinition` | `MedicinalProductDefinition.impurity` | `http://hl7.org/fhir/ValueSet/substance-codes` | `Example` | Any component of the drug product which is not the chemical entity defined as the drug substance, or an excipient in the drug product |

### Expansion Failure

Failed to expand this value set: Expansion is limited
