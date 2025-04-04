Comparison of 
Generated at Friday, April 4, 2025 2:58:52 PM

### Hl7VSRelevantClincialInformation

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | Hl7VSRelevantClincialInformation |
| Canonical URL | `http://terminology.hl7.org/ValueSet/v2-0916` |
| Version | 2.0.0 |
| Description | Value Set of codes that specify additional clinical information about the patient or specimen to report the supporting and/or suspected diagnosis and clinical findings on requests for interpreted diagnostic studies. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `4217` |
| Database Concept Count | `4` |
| Database Active Concept Count | `4` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Specimen` | `Specimen.collection.fastingStatus[x]` | `http://terminology.hl7.org/ValueSet/v2-0916` | `Extensible` | Whether or how long patient abstained from food and/or drink |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v2-0916`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v2-0916` | `F` | Patient was fasting prior to the procedure. |
| `http://terminology.hl7.org/CodeSystem/v2-0916` | `FNA` | Fasting not asked of the patient at time of procedure. |
| `http://terminology.hl7.org/CodeSystem/v2-0916` | `NF` | The patient indicated they did not fast prior to the procedure. |
| `http://terminology.hl7.org/CodeSystem/v2-0916` | `NG` | Not Given - Patient was not asked at the time of the procedure. |
