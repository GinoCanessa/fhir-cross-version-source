Comparison of 
Generated at Friday, April 4, 2025 2:58:44 PM

### ICD-10Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ICD-10Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/icd-10` |
| Version | 4.0.1 |
| Description | This value set includes sample ICD-10 codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2491` |
| Database Concept Count | `7` |
| Database Active Concept Count | `7` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ChargeItem` | `ChargeItem.reason` | `http://hl7.org/fhir/ValueSet/icd-10` | `Example` | Why was the charged  service rendered? |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.diagnosis.diagnosis[x]` | `http://hl7.org/fhir/ValueSet/icd-10` | `Example` | Nature of illness or problem |
| `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityRequest` | `CoverageEligibilityRequest.item.diagnosis.diagnosis[x]` | `http://hl7.org/fhir/ValueSet/icd-10` | `Example` | Nature of illness or problem |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.diagnosis.diagnosis[x]` | `http://hl7.org/fhir/ValueSet/icd-10` | `Example` | Nature of illness or problem |

### Referenced Systems

* `http://hl7.org/fhir/sid/icd-10`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/sid/icd-10` | `112233` | DIAG-4 |
| `http://hl7.org/fhir/sid/icd-10` | `123456` | DIAG-1 |
| `http://hl7.org/fhir/sid/icd-10` | `123457` | DIAG-1a |
| `http://hl7.org/fhir/sid/icd-10` | `123987` | DIAG-3 |
| `http://hl7.org/fhir/sid/icd-10` | `321789` | DIAG-6 |
| `http://hl7.org/fhir/sid/icd-10` | `987654` | DIAG-2 |
| `http://hl7.org/fhir/sid/icd-10` | `997755` | DIAG-5 |
