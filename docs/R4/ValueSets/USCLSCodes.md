Comparison of 
Generated at Friday, April 4, 2025 2:58:43 PM

### USCLSCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | USCLSCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/service-uscls` |
| Version | 4.0.1 |
| Description | This value set includes a smattering of USCLS codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2757` |
| Database Concept Count | `20` |
| Database Active Concept Count | `20` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.productOrService` | `http://hl7.org/fhir/ValueSet/service-uscls` | `Example` | Billing, service, product, or drug code |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.detail.productOrService` | `http://hl7.org/fhir/ValueSet/service-uscls` | `Example` | Billing, service, product, or drug code |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.detail.subDetail.productOrService` | `http://hl7.org/fhir/ValueSet/service-uscls` | `Example` | Billing, service, product, or drug code |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.addItem.productOrService` | `http://hl7.org/fhir/ValueSet/service-uscls` | `Example` | Billing, service, product, or drug code |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.addItem.detail.productOrService` | `http://hl7.org/fhir/ValueSet/service-uscls` | `Example` | Billing, service, product, or drug code |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.addItem.detail.subDetail.productOrService` | `http://hl7.org/fhir/ValueSet/service-uscls` | `Example` | Billing, service, product, or drug code |
| `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityRequest` | `CoverageEligibilityRequest.item.productOrService` | `http://hl7.org/fhir/ValueSet/service-uscls` | `Example` | Billing, service, product, or drug code |
| `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityResponse` | `CoverageEligibilityResponse.insurance.item.productOrService` | `http://hl7.org/fhir/ValueSet/service-uscls` | `Example` | Billing, service, product, or drug code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.productOrService` | `http://hl7.org/fhir/ValueSet/service-uscls` | `Example` | Billing, service, product, or drug code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.detail.productOrService` | `http://hl7.org/fhir/ValueSet/service-uscls` | `Example` | Billing, service, product, or drug code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.detail.subDetail.productOrService` | `http://hl7.org/fhir/ValueSet/service-uscls` | `Example` | Billing, service, product, or drug code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.addItem.productOrService` | `http://hl7.org/fhir/ValueSet/service-uscls` | `Example` | Billing, service, product, or drug code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.addItem.detail.productOrService` | `http://hl7.org/fhir/ValueSet/service-uscls` | `Example` | Billing, service, product, or drug code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.addItem.detail.subDetail.productOrService` | `http://hl7.org/fhir/ValueSet/service-uscls` | `Example` | Billing, service, product, or drug code |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/ex-USCLS`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/ex-USCLS` | `1101` | Exam, comp, primary |
| `http://terminology.hl7.org/CodeSystem/ex-USCLS` | `1102` | Exam, comp, mixed |
| `http://terminology.hl7.org/CodeSystem/ex-USCLS` | `1103` | Exam, comp, permanent |
| `http://terminology.hl7.org/CodeSystem/ex-USCLS` | `11101` | Polishing, 1 unit |
| `http://terminology.hl7.org/CodeSystem/ex-USCLS` | `11102` | Polishing, 2 unit |
| `http://terminology.hl7.org/CodeSystem/ex-USCLS` | `11103` | Polishing, 3 unit |
| `http://terminology.hl7.org/CodeSystem/ex-USCLS` | `11104` | Polishing, 4 unit |
| `http://terminology.hl7.org/CodeSystem/ex-USCLS` | `1201` | Exam, recall |
| `http://terminology.hl7.org/CodeSystem/ex-USCLS` | `1205` | Exam, emergency |
| `http://terminology.hl7.org/CodeSystem/ex-USCLS` | `2101` | Radiograph, series (12) |
| `http://terminology.hl7.org/CodeSystem/ex-USCLS` | `2102` | Radiograph, series (16) |
| `http://terminology.hl7.org/CodeSystem/ex-USCLS` | `21211` | Amalgam, 1 surface |
| `http://terminology.hl7.org/CodeSystem/ex-USCLS` | `21212` | Amalgam, 2 surface |
| `http://terminology.hl7.org/CodeSystem/ex-USCLS` | `2141` | Radiograph, bitewing |
| `http://terminology.hl7.org/CodeSystem/ex-USCLS` | `2601` | Radiograph, panoramic |
| `http://terminology.hl7.org/CodeSystem/ex-USCLS` | `27211` | Crown, PFM |
| `http://terminology.hl7.org/CodeSystem/ex-USCLS` | `67211` | Maryland Bridge |
| `http://terminology.hl7.org/CodeSystem/ex-USCLS` | `99111` | Lab, commercial |
| `http://terminology.hl7.org/CodeSystem/ex-USCLS` | `99333` | Lab, in office |
| `http://terminology.hl7.org/CodeSystem/ex-USCLS` | `99555` | Expense |
