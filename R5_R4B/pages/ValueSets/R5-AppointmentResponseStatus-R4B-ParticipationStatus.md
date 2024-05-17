Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Url | Name | Title | Description |
| --- | --- | --- | --- | --- |
| Source | http://hl7.org/fhir/ValueSet/appointmentresponse-status | AppointmentResponseStatus | Appointment Response Status | The Participation status for a participant in response to a request for an appointment. |
| Target | http://hl7.org/fhir/ValueSet/participationstatus | ParticipationStatus | ParticipationStatus | The Participation status of an appointment. |


Comparison Result: Equivalent


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 4 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| accepted | accepted | Equivalent | R5 `accepted` is equivalent to R4B `accepted`. |
| declined | declined | Equivalent | R5 `declined` is equivalent to R4B `declined`. |
| entered-in-error | - | DoesNotExistInTarget | R5 `entered-in-error` does not appear in the target and has no mapping for http://hl7.org/fhir/ValueSet/participationstatus. |
| needs-action | needs-action | Equivalent | R5 `needs-action` is equivalent to R4B `needs-action`. |
| tentative | tentative | Equivalent | R5 `tentative` is equivalent to R4B `tentative`. |

