Comparison of 
Generated at Monday, April 14, 2025 6:17:15 PM

### CarePlanRelationship

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | CarePlanRelationship |
| Canonical URL | `http://hl7.org/fhir/ValueSet/care-plan-relationship` |
| Version | 1.0.2 |
| Description | Codes identifying the types of relationships between two plans. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `46` |
| Database Concept Count | `3` |
| Database Active Concept Count | `3` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/CarePlan` | `CarePlan.relatedPlan.code` | `http://hl7.org/fhir/ValueSet/care-plan-relationship` | `Required` | includes \| replaces \| fulfills |

### Referenced Systems

* `http://hl7.org/fhir/care-plan-relationship`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/care-plan-relationship` | `fulfills` | Fulfills |
| `http://hl7.org/fhir/care-plan-relationship` | `includes` | Includes |
| `http://hl7.org/fhir/care-plan-relationship` | `replaces` | Replaces |
