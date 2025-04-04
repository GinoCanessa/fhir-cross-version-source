Comparison of 
Generated at Friday, April 4, 2025 2:58:37 PM

### USCLS Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | USCLS Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/service-uscls` |
| Version | 3.0.2 |
| Description | This value set includes a smattering of USCLS codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1480` |
| Database Concept Count | `20` |
| Database Active Concept Count | `20` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.service` | `http://hl7.org/fhir/ValueSet/service-uscls` | `Example` | Billing Code |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.detail.service` | `http://hl7.org/fhir/ValueSet/service-uscls` | `Example` | Billing Code |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.detail.subDetail.service` | `http://hl7.org/fhir/ValueSet/service-uscls` | `Example` | Billing Code |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.addItem.service` | `http://hl7.org/fhir/ValueSet/service-uscls` | `Example` | Group, Service or Product |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.addItem.detail.service` | `http://hl7.org/fhir/ValueSet/service-uscls` | `Example` | Service or Product |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.service` | `http://hl7.org/fhir/ValueSet/service-uscls` | `Example` | Billing Code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.detail.service` | `http://hl7.org/fhir/ValueSet/service-uscls` | `Example` | Billing Code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.detail.subDetail.service` | `http://hl7.org/fhir/ValueSet/service-uscls` | `Example` | Billing Code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.addItem.service` | `http://hl7.org/fhir/ValueSet/service-uscls` | `Example` | Billing Code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.addItem.detail.service` | `http://hl7.org/fhir/ValueSet/service-uscls` | `Example` | Billing Code |

### Referenced Systems

* `http://hl7.org/fhir/ex-USCLS`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/ex-USCLS` | `1101` | Exam, comp, primary |
| `http://hl7.org/fhir/ex-USCLS` | `1102` | Exam, comp, mixed |
| `http://hl7.org/fhir/ex-USCLS` | `1103` | Exam, comp, permanent |
| `http://hl7.org/fhir/ex-USCLS` | `11101` | Polishing, 1 unit |
| `http://hl7.org/fhir/ex-USCLS` | `11102` | Polishing, 2 unit |
| `http://hl7.org/fhir/ex-USCLS` | `11103` | Polishing, 3 unit |
| `http://hl7.org/fhir/ex-USCLS` | `11104` | Polishing, 4 unit |
| `http://hl7.org/fhir/ex-USCLS` | `1201` | Exam, recall |
| `http://hl7.org/fhir/ex-USCLS` | `1205` | Exam, emergency |
| `http://hl7.org/fhir/ex-USCLS` | `2101` | Radiograph, series (12) |
| `http://hl7.org/fhir/ex-USCLS` | `2102` | Radiograph, series (16) |
| `http://hl7.org/fhir/ex-USCLS` | `21211` | Amalgam, 1 surface |
| `http://hl7.org/fhir/ex-USCLS` | `21212` | Amalgam, 2 surface |
| `http://hl7.org/fhir/ex-USCLS` | `2141` | Radiograph, bytewing |
| `http://hl7.org/fhir/ex-USCLS` | `2601` | Radiograph, panoramic |
| `http://hl7.org/fhir/ex-USCLS` | `27211` | Crown, PFM |
| `http://hl7.org/fhir/ex-USCLS` | `67211` | Maryland Bridge |
| `http://hl7.org/fhir/ex-USCLS` | `99111` | Lab, commercial |
| `http://hl7.org/fhir/ex-USCLS` | `99333` | Lab, in office |
| `http://hl7.org/fhir/ex-USCLS` | `99555` | Expense |
