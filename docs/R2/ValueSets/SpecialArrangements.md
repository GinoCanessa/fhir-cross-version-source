Comparison of 
Generated at Tuesday, April 1, 2025 1:39:06 PM

### SpecialArrangements

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | SpecialArrangements |
| Canonical URL | `http://hl7.org/fhir/ValueSet/encounter-special-arrangements` |
| Version | 1.0.2 |
| Description | This value set defines a set of codes that can be used to indicate the kinds of special arrangements in place for a patients visit. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `150` |
| Database Concept Count | `5` |
| Database Active Concept Count | `5` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.hospitalization.specialArrangement` | `http://hl7.org/fhir/ValueSet/encounter-special-arrangements` | `Preferred` | Wheelchair, translator, stretcher, etc. |

### Referenced Systems

* `http://hl7.org/fhir/encounter-special-arrangements`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/encounter-special-arrangements` | `att` | Attendant |
| `http://hl7.org/fhir/encounter-special-arrangements` | `dog` | Guide dog |
| `http://hl7.org/fhir/encounter-special-arrangements` | `int` | Interpreter |
| `http://hl7.org/fhir/encounter-special-arrangements` | `stret` | Stretcher |
| `http://hl7.org/fhir/encounter-special-arrangements` | `wheel` | Wheelchair |
