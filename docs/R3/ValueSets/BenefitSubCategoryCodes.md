Comparison of 
Generated at Friday, April 4, 2025 2:58:37 PM

### Benefit SubCategory Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Benefit SubCategory Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/benefit-subcategory` |
| Version | 3.0.2 |
| Description | This value set includes a smattering of Benefit SubCategory codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1077` |
| Database Concept Count | `28` |
| Database Active Concept Count | `28` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.category` | `http://hl7.org/fhir/ValueSet/benefit-subcategory` | `Example` | Type of service or product |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.detail.category` | `http://hl7.org/fhir/ValueSet/benefit-subcategory` | `Example` | Type of service or product |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.detail.subDetail.category` | `http://hl7.org/fhir/ValueSet/benefit-subcategory` | `Example` | Type of service or product |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.addItem.category` | `http://hl7.org/fhir/ValueSet/benefit-subcategory` | `Example` | Type of service or product |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.addItem.detail.category` | `http://hl7.org/fhir/ValueSet/benefit-subcategory` | `Example` | Type of service or product |
| `http://hl7.org/fhir/StructureDefinition/EligibilityRequest` | `EligibilityRequest.benefitSubCategory` | `http://hl7.org/fhir/ValueSet/benefit-subcategory` | `Example` | Detailed services covered within the type |
| `http://hl7.org/fhir/StructureDefinition/EligibilityResponse` | `EligibilityResponse.insurance.benefitBalance.subCategory` | `http://hl7.org/fhir/ValueSet/benefit-subcategory` | `Example` | Detailed services covered within the type |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.category` | `http://hl7.org/fhir/ValueSet/benefit-subcategory` | `Example` | Type of service or product |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.detail.category` | `http://hl7.org/fhir/ValueSet/benefit-subcategory` | `Example` | Type of service or product |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.detail.subDetail.category` | `http://hl7.org/fhir/ValueSet/benefit-subcategory` | `Example` | Type of service or product |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.addItem.category` | `http://hl7.org/fhir/ValueSet/benefit-subcategory` | `Example` | Type of service or product |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.addItem.detail.category` | `http://hl7.org/fhir/ValueSet/benefit-subcategory` | `Example` | Type of service or product |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.benefitBalance.subCategory` | `http://hl7.org/fhir/ValueSet/benefit-subcategory` | `Example` | Detailed services covered within the type |

### Referenced Systems

* `http://hl7.org/fhir/benefit-subcategory`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/benefit-subcategory` | `1` | Medical Care |
| `http://hl7.org/fhir/benefit-subcategory` | `14` | Renal Supplies |
| `http://hl7.org/fhir/benefit-subcategory` | `2` | Surgical |
| `http://hl7.org/fhir/benefit-subcategory` | `23` | Diagnostic Dental |
| `http://hl7.org/fhir/benefit-subcategory` | `24` | Periodontics |
| `http://hl7.org/fhir/benefit-subcategory` | `25` | Restorative |
| `http://hl7.org/fhir/benefit-subcategory` | `26` | Endodontics |
| `http://hl7.org/fhir/benefit-subcategory` | `27` | Maxillofacilial Prosthetics |
| `http://hl7.org/fhir/benefit-subcategory` | `28` | Adjunctive Dental Services |
| `http://hl7.org/fhir/benefit-subcategory` | `3` | Consultation |
| `http://hl7.org/fhir/benefit-subcategory` | `30` | Health Benefit Plan Coverage |
| `http://hl7.org/fhir/benefit-subcategory` | `35` | Dental Care |
| `http://hl7.org/fhir/benefit-subcategory` | `36` | Dental Crowns |
| `http://hl7.org/fhir/benefit-subcategory` | `37` | Dental Accident |
| `http://hl7.org/fhir/benefit-subcategory` | `4` | Diagnostic XRay |
| `http://hl7.org/fhir/benefit-subcategory` | `49` | Hospital Room and Board |
| `http://hl7.org/fhir/benefit-subcategory` | `5` | Diagnostic Lab |
| `http://hl7.org/fhir/benefit-subcategory` | `55` | Major Medical |
| `http://hl7.org/fhir/benefit-subcategory` | `56` | Medically Related Transportation |
| `http://hl7.org/fhir/benefit-subcategory` | `61` | In-vitro Fertilization |
| `http://hl7.org/fhir/benefit-subcategory` | `62` | MRI Scan |
| `http://hl7.org/fhir/benefit-subcategory` | `63` | Donor Procedures |
| `http://hl7.org/fhir/benefit-subcategory` | `69` | Maternity |
| `http://hl7.org/fhir/benefit-subcategory` | `76` | Renal Dialysis |
| `http://hl7.org/fhir/benefit-subcategory` | `F1` | Medical Coverage |
| `http://hl7.org/fhir/benefit-subcategory` | `F3` | Dental Coverage |
| `http://hl7.org/fhir/benefit-subcategory` | `F4` | Hearing Coverage |
| `http://hl7.org/fhir/benefit-subcategory` | `F6` | Vision Coverage |
