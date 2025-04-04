Comparison of 
Generated at Friday, April 4, 2025 2:58:37 PM

### Example Revenue Center Codes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | Example Revenue Center Codes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/ex-revenue-center` |
| Version | 3.0.2 |
| Description | This value set includes sample Revenue Center codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `1231` |
| Database Concept Count | `9` |
| Database Active Concept Count | `9` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.detail.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.detail.subDetail.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.addItem.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.addItem.detail.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.detail.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.detail.subDetail.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.addItem.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.addItem.detail.revenue` | `http://hl7.org/fhir/ValueSet/ex-revenue-center` | `Example` | Revenue or cost center code |

### Referenced Systems

* `http://hl7.org/fhir/ex-revenue-center`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/ex-revenue-center` | `0010` | Vision Clinic |
| `http://hl7.org/fhir/ex-revenue-center` | `0370` | Anaesthesia |
| `http://hl7.org/fhir/ex-revenue-center` | `0420` | Physical Therapy |
| `http://hl7.org/fhir/ex-revenue-center` | `0421` | Physical Therapy - |
| `http://hl7.org/fhir/ex-revenue-center` | `0440` | Speech-Language Pathology |
| `http://hl7.org/fhir/ex-revenue-center` | `0441` | Speech-Language Pathology - Visit |
| `http://hl7.org/fhir/ex-revenue-center` | `0450` | Emergency Room |
| `http://hl7.org/fhir/ex-revenue-center` | `0451` | Emergency Room - EM/EMTALA |
| `http://hl7.org/fhir/ex-revenue-center` | `0452` | Emergency Room - beyond EMTALA |
