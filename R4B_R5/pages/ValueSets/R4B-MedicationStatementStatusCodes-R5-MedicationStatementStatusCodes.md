Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:03 AM

| Side | Url | Name | Title | Description |
| --- | --- | --- | --- | --- |
| Source | http://hl7.org/fhir/ValueSet/medication-statement-status | MedicationStatement Status Codes |  | MedicationStatement Status Codes |
| Target | http://hl7.org/fhir/ValueSet/medication-statement-status | MedicationStatementStatusCodes | MedicationStatement Status Codes | MedicationStatement Status Codes |


Comparison Result: SourceIsNarrowerThanTarget


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 1 |
SourceIsNarrowerThanTarget | 7 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| active | draft | SourceIsNarrowerThanTarget | R4B `active` is narrower than R5 `draft` and is compatible. `draft` is mapped from `active` and `intended` and `on-hold` and `unknown`. |
| completed | recorded | SourceIsNarrowerThanTarget | R4B `completed` is narrower than R5 `recorded` and is compatible. `recorded` is mapped from `completed` and `not-taken` and `stopped`. |
| entered-in-error | entered-in-error | Equivalent | R4B `entered-in-error` is equivalent to R5 `entered-in-error`. |
| intended | draft | SourceIsNarrowerThanTarget | R4B `intended` is narrower than R5 `draft` and is compatible. `draft` is mapped from `active` and `intended` and `on-hold` and `unknown`. |
| not-taken | recorded | SourceIsNarrowerThanTarget | R4B `not-taken` is narrower than R5 `recorded` and is compatible. `recorded` is mapped from `completed` and `not-taken` and `stopped`. |
| on-hold | draft | SourceIsNarrowerThanTarget | R4B `on-hold` is narrower than R5 `draft` and is compatible. `draft` is mapped from `active` and `intended` and `on-hold` and `unknown`. |
| stopped | recorded | SourceIsNarrowerThanTarget | R4B `stopped` is narrower than R5 `recorded` and is compatible. `recorded` is mapped from `completed` and `not-taken` and `stopped`. |
| unknown | draft | SourceIsNarrowerThanTarget | R4B `unknown` is narrower than R5 `draft` and is compatible. `draft` is mapped from `active` and `intended` and `on-hold` and `unknown`. |

