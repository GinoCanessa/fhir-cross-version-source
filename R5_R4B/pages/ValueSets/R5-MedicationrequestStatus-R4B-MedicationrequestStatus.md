Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Url | Name | Title | Description |
| --- | --- | --- | --- | --- |
| Source | http://hl7.org/fhir/ValueSet/medicationrequest-status | MedicationrequestStatus | medicationrequest Status | MedicationRequest Status Codes |
| Target | http://hl7.org/fhir/ValueSet/medicationrequest-status | medicationrequest Status |  | MedicationRequest Status Codes |


Comparison Result: SourceIsNarrowerThanTarget


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 7 |
SourceIsNarrowerThanTarget | 2 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| active | active | Equivalent | R5 `active` is equivalent to R4B `active`. |
| cancelled | cancelled | Equivalent | R5 `cancelled` is equivalent to R4B `cancelled`. |
| completed | completed | SourceIsNarrowerThanTarget | R5 `completed` is narrower than R4B `completed` and is compatible. `completed` is mapped from `completed` and `ended`. |
| draft | draft | Equivalent | R5 `draft` is equivalent to R4B `draft`. |
| ended | completed | SourceIsNarrowerThanTarget | R5 `ended` is narrower than R4B `completed` and is compatible. `completed` is mapped from `completed` and `ended`. |
| entered-in-error | entered-in-error | Equivalent | R5 `entered-in-error` is equivalent to R4B `entered-in-error`. |
| on-hold | on-hold | Equivalent | R5 `on-hold` is equivalent to R4B `on-hold`. |
| stopped | stopped | Equivalent | R5 `stopped` is equivalent to R4B `stopped`. |
| unknown | unknown | Equivalent | R5 `unknown` is equivalent to R4B `unknown`. |

