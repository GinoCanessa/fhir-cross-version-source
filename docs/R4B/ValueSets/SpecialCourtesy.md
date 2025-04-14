Comparison of 
Generated at Monday, April 14, 2025 6:17:34 PM

### SpecialCourtesy

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | SpecialCourtesy |
| Canonical URL | `http://hl7.org/fhir/ValueSet/encounter-special-courtesy` |
| Version | 4.3.0 |
| Description | This value set defines a set of codes that can be used to indicate special courtesies provided to the patient. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `3739` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.hospitalization.specialCourtesy` | `http://hl7.org/fhir/ValueSet/encounter-special-courtesy` | `Preferred` | Special courtesies (VIP, board member) |

### Referenced Systems

* `http://terminology.hl7.org/CodeSystem/v3-EncounterSpecialCourtesy`
* `http://terminology.hl7.org/CodeSystem/v3-NullFlavor`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://terminology.hl7.org/CodeSystem/v3-EncounterSpecialCourtesy` | `EXT` | extended courtesy |
| `http://terminology.hl7.org/CodeSystem/v3-EncounterSpecialCourtesy` | `NRM` | normal courtesy |
| `http://terminology.hl7.org/CodeSystem/v3-EncounterSpecialCourtesy` | `PRF` | professional courtesy |
| `http://terminology.hl7.org/CodeSystem/v3-EncounterSpecialCourtesy` | `STF` | staff |
| `http://terminology.hl7.org/CodeSystem/v3-EncounterSpecialCourtesy` | `VIP` | very important person |
| `http://terminology.hl7.org/CodeSystem/v3-NullFlavor` | `UNK` | unknown |
