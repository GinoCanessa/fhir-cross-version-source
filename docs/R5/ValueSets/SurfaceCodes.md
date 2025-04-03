Comparison of 
Generated at Thursday, April 3, 2025 8:18:31 AM

### SurfaceCodes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| VS Name | SurfaceCodes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/surface` |
| Version | 5.0.0 |
| Description | This value set includes a smattering of FDI tooth surface codes. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `4958` |
| Database Concept Count | `11` |
| Database Active Concept Count | `11` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Claim` | `Claim.item.bodySite.subSite` | `http://hl7.org/fhir/ValueSet/surface` | `Example` | Sub-location |
| `http://hl7.org/fhir/StructureDefinition/ClaimResponse` | `ClaimResponse.addItem.bodySite.subSite` | `http://hl7.org/fhir/ValueSet/surface` | `Example` | Sub-location |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.item.bodySite.subSite` | `http://hl7.org/fhir/ValueSet/surface` | `Example` | Sub-location |
| `http://hl7.org/fhir/StructureDefinition/ExplanationOfBenefit` | `ExplanationOfBenefit.addItem.bodySite.subSite` | `http://hl7.org/fhir/ValueSet/surface` | `Example` | Sub-location |

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
