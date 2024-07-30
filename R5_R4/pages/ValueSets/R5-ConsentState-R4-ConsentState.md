Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Url | Name | Title | Description |
| --- | --- | --- | --- | --- |
| Source | http://hl7.org/fhir/ValueSet/consent-state-codes | ConsentState | Consent State | Indicates the state of the consent. |
| Target | http://hl7.org/fhir/ValueSet/consent-state-codes | ConsentState | ConsentState | Indicates the state of the consent. |


Comparison Result: Equivalent


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 5 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| active | active | Equivalent | R5 `active` is equivalent to R4 `active`. |
| draft | draft | Equivalent | R5 `draft` is equivalent to R4 `draft`. |
| entered-in-error | entered-in-error | Equivalent | R5 `entered-in-error` is equivalent to R4 `entered-in-error`. |
| inactive | inactive | Equivalent | R5 `inactive` is equivalent to R4 `inactive`. |
| not-done | rejected | Equivalent | R5 `not-done` is equivalent to R4 `rejected`. |
| unknown | - | DoesNotExistInTarget | R5 `unknown` does not appear in the target and has no mapping for http://hl7.org/fhir/ValueSet/consent-state-codes. |

