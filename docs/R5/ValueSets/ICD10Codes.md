Comparison of 
Generated at Tuesday, April 1, 2025 1:39:34 PM

### ICD10Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ICD10Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/icd-10` |
| Version | 5.0.0 |
| Description | This value set includes sample ICD-10 codes. |
| Status | `Draft` |
| Has Escape Valve Code | `` |
| Database Key | `4606` |
| Database Concept Count | `0` |
| Database Active Concept Count | `0` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ChargeItem` | `ChargeItem.reason` | `http://hl7.org/fhir/ValueSet/icd-10` | `Example` | Why was the charged  service rendered? |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.diagnosis.diagnosis[x]` | `http://hl7.org/fhir/ValueSet/icd-10` | `Example` | Nature of illness or problem |
| `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityRequest` | `CoverageEligibilityRequest.item.diagnosis.diagnosis[x]` | `http://hl7.org/fhir/ValueSet/icd-10` | `Example` | Nature of illness or problem |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.diagnosis.diagnosis[x]` | `http://hl7.org/fhir/ValueSet/icd-10` | `Example` | Nature of illness or problem |

### Expansion Failure

Failed to expand this value set: Expansion is limited
