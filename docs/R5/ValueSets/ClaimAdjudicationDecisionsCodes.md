Comparison of 
Generated at Thursday, April 3, 2025 8:18:31 AM

### ClaimAdjudicationDecisionsCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ClaimAdjudicationDecisionsCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/claim-decision` |
| Version | 5.0.0 |
| Description | This value set includes Claim Adjudication Decision codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4359` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.decision` | `http://hl7.org/fhir/ValueSet/claim-decision` | `Example` | Result of the adjudication |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.item.reviewOutcome.decision` | `http://hl7.org/fhir/ValueSet/claim-decision` | `Example` | Result of the adjudication |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.decision` | `http://hl7.org/fhir/ValueSet/claim-decision` | `Example` | Result of the adjudication |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.reviewOutcome.decision` | `http://hl7.org/fhir/ValueSet/claim-decision` | `Example` | Result of the adjudication |

### Referenced Systems

* `http://hl7.org/fhir/claim-decision`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/claim-decision` | `approved` | Approved |
| `http://hl7.org/fhir/claim-decision` | `denied` | Denied |
| `http://hl7.org/fhir/claim-decision` | `partial` | Partial |
| `http://hl7.org/fhir/claim-decision` | `pending` | Pending |
