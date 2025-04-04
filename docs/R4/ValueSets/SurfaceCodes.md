Comparison of 
Generated at Friday, April 4, 2025 2:58:43 PM

### SurfaceCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| VS Name | SurfaceCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/surface` |
| Version | 4.0.1 |
| Description | This value set includes a smattering of FDI tooth surface codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `2793` |
| Database Concept Count | `11` |
| Database Active Concept Count | `11` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.subSite` | `http://hl7.org/fhir/ValueSet/surface` | `Example` | Anatomical sub-location |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.addItem.subSite` | `http://hl7.org/fhir/ValueSet/surface` | `Example` | Anatomical sub-location |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.subSite` | `http://hl7.org/fhir/ValueSet/surface` | `Example` | Anatomical sub-location |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.addItem.subSite` | `http://hl7.org/fhir/ValueSet/surface` | `Example` | Anatomical sub-location |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/FDI-surface`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/FDI-surface` | `B` | Buccal |
| `http://terminology.hl7.org/CodeSystem/FDI-surface` | `D` | Distal |
| `http://terminology.hl7.org/CodeSystem/FDI-surface` | `DI` | Distoincisal |
| `http://terminology.hl7.org/CodeSystem/FDI-surface` | `DO` | Distoclusal |
| `http://terminology.hl7.org/CodeSystem/FDI-surface` | `I` | Incisal |
| `http://terminology.hl7.org/CodeSystem/FDI-surface` | `L` | Lingual |
| `http://terminology.hl7.org/CodeSystem/FDI-surface` | `M` | Mesial |
| `http://terminology.hl7.org/CodeSystem/FDI-surface` | `MO` | Mesioclusal |
| `http://terminology.hl7.org/CodeSystem/FDI-surface` | `MOD` | Mesioclusodistal |
| `http://terminology.hl7.org/CodeSystem/FDI-surface` | `O` | Occlusal |
| `http://terminology.hl7.org/CodeSystem/FDI-surface` | `V` | Ventral |
