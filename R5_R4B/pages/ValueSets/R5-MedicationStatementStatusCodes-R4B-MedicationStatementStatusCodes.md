Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Url | Name | Title | Description |
| --- | --- | --- | --- | --- |
| Source | http://hl7.org/fhir/ValueSet/medication-statement-status | MedicationStatementStatusCodes | MedicationStatement Status Codes | MedicationStatement Status Codes |
| Target | http://hl7.org/fhir/ValueSet/medication-statement-status | MedicationStatement Status Codes |  | MedicationStatement Status Codes |


Comparison Result: SourceIsBroaderThanTarget


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 1 |
SourceIsBroaderThanTarget | 2 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| draft | active | SourceIsBroaderThanTarget | R5 `draft` is broader than R4B active and requires mapping choice. `draft` maps to `active` and `intended` and `on-hold` and `unknown`. |
| draft | intended | SourceIsBroaderThanTarget | R5 `draft` is broader than R4B intended and requires mapping choice. `draft` maps to `active` and `intended` and `on-hold` and `unknown`. |
| draft | on-hold | SourceIsBroaderThanTarget | R5 `draft` is broader than R4B on-hold and requires mapping choice. `draft` maps to `active` and `intended` and `on-hold` and `unknown`. |
| draft | unknown | SourceIsBroaderThanTarget | R5 `draft` is broader than R4B unknown and requires mapping choice. `draft` maps to `active` and `intended` and `on-hold` and `unknown`. |
| entered-in-error | entered-in-error | Equivalent | R5 `entered-in-error` is equivalent to R4B `entered-in-error`. |
| recorded | completed | SourceIsBroaderThanTarget | R5 `recorded` is broader than R4B completed and requires mapping choice. `recorded` maps to `completed` and `not-taken` and `stopped`. |
| recorded | not-taken | SourceIsBroaderThanTarget | R5 `recorded` is broader than R4B not-taken and requires mapping choice. `recorded` maps to `completed` and `not-taken` and `stopped`. |
| recorded | stopped | SourceIsBroaderThanTarget | R5 `recorded` is broader than R4B stopped and requires mapping choice. `recorded` maps to `completed` and `not-taken` and `stopped`. |

