Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:03 AM

| Side | Url | Name | Title | Description |
| --- | --- | --- | --- | --- |
| Source | http://hl7.org/fhir/ValueSet/medicationrequest-status | medicationrequest Status |  | MedicationRequest Status Codes |
| Target | http://hl7.org/fhir/ValueSet/medicationrequest-status | MedicationrequestStatus | medicationrequest Status | MedicationRequest Status Codes |


Comparison Result: SourceIsBroaderThanTarget


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 7 |
SourceIsBroaderThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| active | active | Equivalent | R4B `active` is equivalent to R5 `active`. |
| cancelled | cancelled | Equivalent | R4B `cancelled` is equivalent to R5 `cancelled`. |
| completed | completed | Equivalent | R4B `completed` is equivalent to R5 `completed`. |
| completed | ended | SourceIsBroaderThanTarget | R4B `completed` is broader than R5 ended and requires mapping choice. `completed` maps to `completed` and `ended`. |
| draft | draft | Equivalent | R4B `draft` is equivalent to R5 `draft`. |
| entered-in-error | entered-in-error | Equivalent | R4B `entered-in-error` is equivalent to R5 `entered-in-error`. |
| on-hold | on-hold | Equivalent | R4B `on-hold` is equivalent to R5 `on-hold`. |
| stopped | stopped | Equivalent | R4B `stopped` is equivalent to R5 `stopped`. |
| unknown | unknown | Equivalent | R4B `unknown` is equivalent to R5 `unknown`. |

