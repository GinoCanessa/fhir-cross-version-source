Comparison of 
Generated at Thursday, April 3, 2025 8:18:31 AM

### SNOMEDCTRouteCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | SNOMEDCTRouteCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/route-codes` |
| Version | 5.0.0 |
| Description | This value set includes all Route codes from SNOMED CT - provided as an exemplar. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `4880` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Dosage` | `Dosage.route` | `http://hl7.org/fhir/ValueSet/route-codes` | `Example` | How drug should enter body |
| `http://hl7.org/fhir/StructureDefinition/AdministrableProductDefinition` | `AdministrableProductDefinition.routeOfAdministration.code` | `http://hl7.org/fhir/ValueSet/route-codes` | `Example` | Coded expression for the route |
| `http://hl7.org/fhir/StructureDefinition/AllergyIntolerance` | `AllergyIntolerance.reaction.exposureRoute` | `http://hl7.org/fhir/ValueSet/route-codes` | `Example` | How the subject was exposed to the substance |
| `http://hl7.org/fhir/StructureDefinition/MedicationAdministration` | `MedicationAdministration.dosage.route` | `http://hl7.org/fhir/ValueSet/route-codes` | `Example` | Path of substance into body |
| `http://hl7.org/fhir/StructureDefinition/MedicationKnowledge` | `MedicationKnowledge.definitional.intendedRoute` | `http://hl7.org/fhir/ValueSet/route-codes` | `Example` | The intended or approved route of administration |
| `http://hl7.org/fhir/StructureDefinition/MedicinalProductDefinition` | `MedicinalProductDefinition.route` | `http://hl7.org/fhir/ValueSet/route-codes` | `Example` | The path by which the product is taken into or makes contact with the body |

### Expansion Failure

Failed to expand this value set: Expansion is limited
