Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Url | Name | Title | Description |
| --- | --- | --- | --- | --- |
| Source | http://hl7.org/fhir/ValueSet/consent-state-codes | ConsentState | Consent State | Indicates the state of the consent. |
| Target | http://hl7.org/fhir/ValueSet/consent-state-codes | ConsentState | ConsentState | Indicates the state of the consent. |


Comparison Result: Equivalent


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 6 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| active | active | Equivalent | R5 `active` is equivalent to R4B `active`. |
| draft | draft | Equivalent | R5 `draft` is equivalent to R4B `draft`. |
| entered-in-error | entered-in-error | Equivalent | R5 `entered-in-error` is equivalent to R4B `entered-in-error`. |
| inactive | inactive | Equivalent | R5 `inactive` is equivalent to R4B `inactive`. |
| not-done | rejected | SourceIsBroaderThanTarget | R5 `not-done` is broader than R4B rejected and requires mapping choice. `not-done` maps to `rejected`. |
| unknown | proposed | Equivalent | R5 `unknown` is equivalent to R4B `proposed`. |

