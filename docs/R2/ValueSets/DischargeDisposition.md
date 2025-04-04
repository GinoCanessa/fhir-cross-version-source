Comparison of 
Generated at Friday, April 4, 2025 2:58:32 PM

### DischargeDisposition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | DischargeDisposition |
| Canonical URL | `http://hl7.org/fhir/ValueSet/encounter-discharge-disposition` |
| Version | 1.0.2 |
| Description | This value set defines a set of codes that can be used to where the patient left the hospital. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `145` |
| Database Concept Count | `9` |
| Database Active Concept Count | `9` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Encounter` | `Encounter.hospitalization.dischargeDisposition` | `http://hl7.org/fhir/ValueSet/encounter-discharge-disposition` | `Preferred` | Category or kind of location after discharge |

### Referenced Systems

* `http://hl7.org/fhir/discharge-disposition`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/discharge-disposition` | `aadvice` | Left against advice |
| `http://hl7.org/fhir/discharge-disposition` | `exp` | Expired |
| `http://hl7.org/fhir/discharge-disposition` | `home` | Home |
| `http://hl7.org/fhir/discharge-disposition` | `hosp` | Hospice |
| `http://hl7.org/fhir/discharge-disposition` | `long` | Long-term care |
| `http://hl7.org/fhir/discharge-disposition` | `oth` | Other |
| `http://hl7.org/fhir/discharge-disposition` | `other-hcf` | Other healthcare facility |
| `http://hl7.org/fhir/discharge-disposition` | `psy` | Psychiatric hospital |
| `http://hl7.org/fhir/discharge-disposition` | `rehab` | Rehabilitation |
