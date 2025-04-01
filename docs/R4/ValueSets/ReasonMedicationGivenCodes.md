Comparison of 
Generated at Tuesday, April 1, 2025 1:39:19 PM

### ReasonMedicationGivenCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ReasonMedicationGivenCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/reason-medication-given-codes` |
| Version | 4.0.1 |
| Description | This value set is provided as an example. The value set to instantiate this attribute should be drawn from a robust terminology code system that consists of or contains concepts to support the medication process. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2688` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/MedicationAdministration` | `MedicationAdministration.reasonCode` | `http://hl7.org/fhir/ValueSet/reason-medication-given-codes` | `Example` | Reason administration performed |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/reason-medication-given`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/reason-medication-given` | `a` | None |
| `http://terminology.hl7.org/CodeSystem/reason-medication-given` | `b` | Given as Ordered |
| `http://terminology.hl7.org/CodeSystem/reason-medication-given` | `c` | Emergency |
