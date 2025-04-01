Comparison of 
Generated at Tuesday, April 1, 2025 1:39:11 PM

### v2 Observation Result Status Codes Interpretation

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| VS Name | v2 Observation Result Status Codes Interpretation |
| Canonical URL | `http://hl7.org/fhir/ValueSet/v2-0085` |
| Version | 2.8.2 |
| Description | FHIR Value set/code system definition for HL7 v2 table 0085 ( Observation Result Status Codes Interpretation) |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `1565` |
| Database Concept Count | `15` |
| Database Active Concept Count | `15` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |

### Referenced Systems

* `http://hl7.org/fhir/v2/0085`
### Empty Projection

This Value Set resulted in no projection (no mappings to other packages).

### Codes

| System | Code | Display |
| ------ | ---- | ------- |
| `http://hl7.org/fhir/v2/0085` | `A` | Amended based on adjustments provided by the Placer (Physician) regarding patient demographics (such as age and/or gender or other patient specific information |
| `http://hl7.org/fhir/v2/0085` | `B` | Appended Report - Final results reviewed and further information provided for clarity without change to the original result values. |
| `http://hl7.org/fhir/v2/0085` | `C` | Record coming over is a correction and thus replaces a final result |
| `http://hl7.org/fhir/v2/0085` | `D` | Deletes the OBX record |
| `http://hl7.org/fhir/v2/0085` | `F` | Final results |
| `http://hl7.org/fhir/v2/0085` | `I` | Specimen in lab; results pending |
| `http://hl7.org/fhir/v2/0085` | `N` | Not asked; used to affirmatively document that the observation identified in the OBX was not sought when the universal service ID in OBR-4 implies that it would be sought. |
| `http://hl7.org/fhir/v2/0085` | `O` | Order detail description only (no result) |
| `http://hl7.org/fhir/v2/0085` | `P` | Preliminary results |
| `http://hl7.org/fhir/v2/0085` | `R` | Results entered -- not verified |
| `http://hl7.org/fhir/v2/0085` | `S` | Partial results.   Deprecated. Retained only for backward compatibility as of V2.6. |
| `http://hl7.org/fhir/v2/0085` | `U` | Results status change to final without retransmitting results already sent as 'preliminary.'  E.g. radiology changes status from preliminary to final |
| `http://hl7.org/fhir/v2/0085` | `V` | Verified - Final results reviewed and confirmed to be correct, no change to result value, normal range or abnormal flag |
| `http://hl7.org/fhir/v2/0085` | `W` | Post original as wrong, e.g. transmitted for wrong patient |
| `http://hl7.org/fhir/v2/0085` | `X` | Results cannot be obtained for this observation |
