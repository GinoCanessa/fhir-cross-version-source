Comparison of 
Generated at Monday, April 14, 2025 6:17:42 PM

### ClaimInformationCategoryCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | ClaimInformationCategoryCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/claim-informationcategory` |
| Version | 5.0.0 |
| Description | This value set includes sample Information Category codes. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `4362` |
| Database Concept Count | `14` |
| Database Active Concept Count | `14` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.supportingInfo.category` | `http://hl7.org/fhir/ValueSet/claim-informationcategory` | `Example` | Classification of the supplied information |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.supportingInfo.category` | `http://hl7.org/fhir/ValueSet/claim-informationcategory` | `Example` | Classification of the supplied information |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/claiminformationcategory`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/claiminformationcategory` | `attachment` | Attachment |
| `http://terminology.hl7.org/CodeSystem/claiminformationcategory` | `discharge` | Discharge |
| `http://terminology.hl7.org/CodeSystem/claiminformationcategory` | `employmentimpacted` | EmploymentImpacted |
| `http://terminology.hl7.org/CodeSystem/claiminformationcategory` | `exception` | Exception |
| `http://terminology.hl7.org/CodeSystem/claiminformationcategory` | `externalcause` | External Caause |
| `http://terminology.hl7.org/CodeSystem/claiminformationcategory` | `hospitalized` | Hospitalized |
| `http://terminology.hl7.org/CodeSystem/claiminformationcategory` | `info` | Information |
| `http://terminology.hl7.org/CodeSystem/claiminformationcategory` | `material` | Materials Forwarded |
| `http://terminology.hl7.org/CodeSystem/claiminformationcategory` | `missingtooth` | Missing Tooth |
| `http://terminology.hl7.org/CodeSystem/claiminformationcategory` | `onset` | Onset |
| `http://terminology.hl7.org/CodeSystem/claiminformationcategory` | `other` | Other |
| `http://terminology.hl7.org/CodeSystem/claiminformationcategory` | `patientreasonforvisit` | Patient Reason for Visit |
| `http://terminology.hl7.org/CodeSystem/claiminformationcategory` | `prosthesis` | Prosthesis |
| `http://terminology.hl7.org/CodeSystem/claiminformationcategory` | `related` | Related Services |
