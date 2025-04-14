Comparison of 
Generated at Monday, April 14, 2025 6:17:35 PM

### TherapyRelationshipType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | TherapyRelationshipType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/therapy-relationship-type` |
| Version | 4.3.0 |
| Description | Classification of relationship between a therapy and a contraindication or an indication. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4166` |
| Database Concept Count | `9` |
| Database Active Concept Count | `9` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ClinicalUseDefinition` | `ClinicalUseDefinition.contraindication.otherTherapy.relationshipType` | `http://hl7.org/fhir/ValueSet/therapy-relationship-type` | `Preferred` | The type of relationship between the product indication/contraindication and another therapy |

### Referenced Systems

* `http://hl7.org/fhir/therapy-relationship-type`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/therapy-relationship-type` | `contraindicated-except-with` | Contraindicated unless the other therapy is given |
| `http://hl7.org/fhir/therapy-relationship-type` | `contraindicated-only-with` | Only contraindicated if the other therapy is given |
| `http://hl7.org/fhir/therapy-relationship-type` | `indicated-except-with` | Indicated except when the other therapy is given |
| `http://hl7.org/fhir/therapy-relationship-type` | `indicated-only-before` | Indicated only if the other therapy is planned to be given afterwards (prep) |
| `http://hl7.org/fhir/therapy-relationship-type` | `indicated-only-with` | Indicated only when the other therapy is given (co-occurrent) |
| `http://hl7.org/fhir/therapy-relationship-type` | `replace-other-therapy` | Indicated to replace the other therapy |
| `http://hl7.org/fhir/therapy-relationship-type` | `replace-other-therapy-contraindicated` | Indicated to replace the other contraindicated therapy |
| `http://hl7.org/fhir/therapy-relationship-type` | `replace-other-therapy-not-effective` | Indicated to replace the other therapy not effective on patient |
| `http://hl7.org/fhir/therapy-relationship-type` | `replace-other-therapy-not-tolerated` | Indicated to replace the other therapy not well tolerated by patient |
