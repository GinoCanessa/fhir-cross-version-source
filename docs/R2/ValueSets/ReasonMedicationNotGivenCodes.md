Comparison of 
Generated at Friday, April 4, 2025 2:58:31 PM

### Reason Medication Not Given Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | Reason Medication Not Given Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/reason-medication-not-given-codes` |
| Version | 1.0.2 |
| Description | This value set is provided as an exemplar. The value set to instantiate this attribute should be drawn from a terminologically robust code system that consists of or contains concepts to support the medication process. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `334` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/MedicationAdministration` | `MedicationAdministration.reasonNotGiven` | `http://hl7.org/fhir/ValueSet/reason-medication-not-given-codes` | `Example` | Reason administration not performed |
| `http://hl7.org/fhir/StructureDefinition/MedicationStatement` | `MedicationStatement.reasonNotTaken` | `http://hl7.org/fhir/ValueSet/reason-medication-not-given-codes` | `Example` | True if asserting medication was not given |

### Referenced Systems

* `http://hl7.org/fhir/reason-medication-not-given`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/reason-medication-not-given` | `a` | None |
| `http://hl7.org/fhir/reason-medication-not-given` | `b` | Away |
| `http://hl7.org/fhir/reason-medication-not-given` | `c` | Asleep |
| `http://hl7.org/fhir/reason-medication-not-given` | `d` | Vomit |
