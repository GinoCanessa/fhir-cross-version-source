Comparison of 
Generated at Thursday, April 3, 2025 8:18:09 AM

### SpecialCourtesy

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | SpecialCourtesy |
| Canonical URL | `http://hl7.org/fhir/ValueSet/encounter-special-courtesy` |
| Version | 3.0.2 |
| Description | This value set defines a set of codes that can be used to indicate special courtesies provided to the patient. |
| Status | `Draft` |
| Has Escape Valve Code | `True` |
| Database Key | `1211` |
| Database Concept Count | `6` |
| Database Active Concept Count | `6` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.hospitalization.specialCourtesy` | `http://hl7.org/fhir/ValueSet/encounter-special-courtesy` | `Preferred` | Special courtesies (VIP, board member) |

### Referenced Systems

* `http://hl7.org/fhir/v3/EncounterSpecialCourtesy`
* `http://hl7.org/fhir/v3/NullFlavor`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/v3/EncounterSpecialCourtesy` | `EXT` | extended courtesy |
| `http://hl7.org/fhir/v3/EncounterSpecialCourtesy` | `NRM` | normal courtesy |
| `http://hl7.org/fhir/v3/EncounterSpecialCourtesy` | `PRF` | professional courtesy |
| `http://hl7.org/fhir/v3/EncounterSpecialCourtesy` | `STF` | staff |
| `http://hl7.org/fhir/v3/EncounterSpecialCourtesy` | `VIP` | very important person |
| `http://hl7.org/fhir/v3/NullFlavor` | `UNK` | unknown |
