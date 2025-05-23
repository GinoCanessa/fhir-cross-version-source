Comparison of 
Generated at Monday, April 14, 2025 6:17:28 PM

### ExampleRelatedClaimRelationshipCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ExampleRelatedClaimRelationshipCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/related-claim-relationship` |
| Version | 4.0.1 |
| Description | This value set includes sample Related Claim Relationship codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2699` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.related.relationship` | `http://hl7.org/fhir/ValueSet/related-claim-relationship` | `Example` | How the reference claim is related |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.related.relationship` | `http://hl7.org/fhir/ValueSet/related-claim-relationship` | `Example` | How the reference claim is related |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/ex-relatedclaimrelationship`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/ex-relatedclaimrelationship` | `associated` | Associated Claim |
| `http://terminology.hl7.org/CodeSystem/ex-relatedclaimrelationship` | `prior` | Prior Claim |
