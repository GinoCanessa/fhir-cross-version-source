Comparison of 
Generated at Monday, April 14, 2025 6:17:20 PM

### Example Related Claim Relationship Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Example Related Claim Relationship Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/related-claim-relationship` |
| Version | 3.0.2 |
| Description | This value set includes sample Related Claim Relationship codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1435` |
| Database Concept Count | `2` |
| Database Active Concept Count | `2` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.related.relationship` | `http://hl7.org/fhir/ValueSet/related-claim-relationship` | `Example` | How the reference claim is related |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.related.relationship` | `http://hl7.org/fhir/ValueSet/related-claim-relationship` | `Example` | How the reference claim is related |

### Referenced Systems

* `http://hl7.org/fhir/ex-relatedclaimrelationship`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/ex-relatedclaimrelationship` | `associated` | Associated Claim |
| `http://hl7.org/fhir/ex-relatedclaimrelationship` | `prior` | Prior Claim |
