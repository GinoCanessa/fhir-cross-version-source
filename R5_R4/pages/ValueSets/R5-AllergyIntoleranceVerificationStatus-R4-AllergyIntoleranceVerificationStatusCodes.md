Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Url | Name | Title | Description |
| --- | --- | --- | --- | --- |
| Source | http://hl7.org/fhir/ValueSet/allergyintolerance-verification | AllergyIntoleranceVerificationStatus | AllergyIntolerance Verification Status | The verification status to support or decline the clinical status of the allergy or intolerance. |
| Target | http://hl7.org/fhir/ValueSet/allergyintolerance-verification | AllergyIntoleranceVerificationStatusCodes | AllergyIntolerance Verification Status Codes | Preferred value set for AllergyIntolerance Verification Status. |


Comparison Result: Equivalent


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 4 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| confirmed | confirmed | Equivalent | R5 `confirmed` is assumed equivalent to R4 `confirmed` (no map, but codes match) |
| entered-in-error | entered-in-error | Equivalent | R5 `entered-in-error` is assumed equivalent to R4 `entered-in-error` (no map, but codes match) |
| presumed | - | DoesNotExistInTarget | R5 `presumed` does not appear in the target and has no mapping for http://hl7.org/fhir/ValueSet/allergyintolerance-verification. |
| refuted | refuted | Equivalent | R5 `refuted` is assumed equivalent to R4 `refuted` (no map, but codes match) |
| unconfirmed | unconfirmed | Equivalent | R5 `unconfirmed` is assumed equivalent to R4 `unconfirmed` (no map, but codes match) |

