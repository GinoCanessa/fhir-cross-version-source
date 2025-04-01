Comparison of 
Generated at Tuesday, April 1, 2025 1:39:18 PM

### ExampleRevenueCenterCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | ExampleRevenueCenterCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/ex-revenue-center` |
| Version | 4.0.1 |
| Description | This value set includes sample Revenue Center codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2438` |
| Database Concept Count | `9` |
| Database Active Concept Count | `9` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.detail.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.detail.subDetail.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.detail.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.detail.subDetail.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/ex-revenue-center`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/ex-revenue-center` | `0010` | Vision Clinic |
| `http://terminology.hl7.org/CodeSystem/ex-revenue-center` | `0370` | Anaesthesia |
| `http://terminology.hl7.org/CodeSystem/ex-revenue-center` | `0420` | Physical Therapy |
| `http://terminology.hl7.org/CodeSystem/ex-revenue-center` | `0421` | Physical Therapy - |
| `http://terminology.hl7.org/CodeSystem/ex-revenue-center` | `0440` | Speech-Language Pathology |
| `http://terminology.hl7.org/CodeSystem/ex-revenue-center` | `0441` | Speech-Language Pathology - Visit |
| `http://terminology.hl7.org/CodeSystem/ex-revenue-center` | `0450` | Emergency Room |
| `http://terminology.hl7.org/CodeSystem/ex-revenue-center` | `0451` | Emergency Room - EM/EMTALA |
| `http://terminology.hl7.org/CodeSystem/ex-revenue-center` | `0452` | Emergency Room - beyond EMTALA |
