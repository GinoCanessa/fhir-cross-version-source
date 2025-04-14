Comparison of 
Generated at Monday, April 14, 2025 6:17:42 PM

### ClaimAdjudicationDecisionReasonCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ClaimAdjudicationDecisionReasonCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/claim-decision-reason` |
| Version | 5.0.0 |
| Description | This value set includes example Claim Adjudication Decision Reason codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4360` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.item.reviewOutcome.reason` | `http://hl7.org/fhir/ValueSet/claim-decision-reason` | `Example` | Reason for result of the adjudication |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.reviewOutcome.reason` | `http://hl7.org/fhir/ValueSet/claim-decision-reason` | `Example` | Reason for result of the adjudication |

### Referenced Systems

* `http://hl7.org/fhir/claim-decision-reason`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/claim-decision-reason` | `0001` | Not medically necessary |
| `http://hl7.org/fhir/claim-decision-reason` | `0002` | Prior authorization not obtained |
| `http://hl7.org/fhir/claim-decision-reason` | `0003` | Provider out-of-network |
| `http://hl7.org/fhir/claim-decision-reason` | `0004` | Service inconsistent with patient age |
| `http://hl7.org/fhir/claim-decision-reason` | `0005` | Benefit limits exceeded |
