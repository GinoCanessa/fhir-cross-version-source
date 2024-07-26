Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:50 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | AppointmentResponse |  | A reply to an appointment request for a patient and/or practitioner(s), such as a confirmation or rejection. | 21 | 13 |
| Target | AppointmentResponse |  | A reply to an appointment request for a patient and/or practitioner(s), such as a confirmation or rejection. | 17 | 9 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 4 |
Equivalent | 4 |
RelatedTo | 13 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| AppointmentResponse | AppointmentResponse | Equivalent | R5 `AppointmentResponse` maps as Equivalent to R4 `AppointmentResponse` |
| AppointmentResponse.actor | AppointmentResponse.actor | SourceIsBroaderThanTarget | R5 `AppointmentResponse.actor` maps as SourceIsBroaderThanTarget to R4 `AppointmentResponse.actor` - actor has change due to type change: R5 `actor` `Reference` maps as SourceIsBroaderThanTarget for R4 `actor` |
| AppointmentResponse.appointment | AppointmentResponse.appointment | Equivalent | R5 `AppointmentResponse.appointment` maps as Equivalent to R4 `AppointmentResponse.appointment` |
| AppointmentResponse.comment | AppointmentResponse.comment | SourceIsBroaderThanTarget | R5 `AppointmentResponse.comment` maps as SourceIsBroaderThanTarget to R4 `AppointmentResponse.comment` - comment has change due to type change: R5 comment markdown has no equivalent or mapped type in R4 comment |
| AppointmentResponse.contained | AppointmentResponse.contained | Equivalent | R5 `AppointmentResponse.contained` maps as Equivalent to R4 `AppointmentResponse.contained` |
| AppointmentResponse.end | AppointmentResponse.end | Equivalent | R5 `AppointmentResponse.end` maps as Equivalent to R4 `AppointmentResponse.end` |
| AppointmentResponse.extension | AppointmentResponse.extension | SourceIsBroaderThanTarget | R5 `AppointmentResponse.extension` maps as SourceIsBroaderThanTarget to R4 `AppointmentResponse.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| AppointmentResponse.id | AppointmentResponse.id | Equivalent | R5 `AppointmentResponse.id` maps as Equivalent to R4 `AppointmentResponse.id` |
| AppointmentResponse.identifier | AppointmentResponse.identifier | Equivalent | R5 `AppointmentResponse.identifier` maps as Equivalent to R4 `AppointmentResponse.identifier` |
| AppointmentResponse.implicitRules | AppointmentResponse.implicitRules | Equivalent | R5 `AppointmentResponse.implicitRules` maps as Equivalent to R4 `AppointmentResponse.implicitRules` |
| AppointmentResponse.language | AppointmentResponse.language | RelatedTo | R5 `AppointmentResponse.language` maps as RelatedTo to R4 `AppointmentResponse.language` - language changed the binding strength from Required to Preferred |
| AppointmentResponse.meta | AppointmentResponse.meta | Equivalent | R5 `AppointmentResponse.meta` maps as Equivalent to R4 `AppointmentResponse.meta` |
| AppointmentResponse.modifierExtension | AppointmentResponse.modifierExtension | SourceIsBroaderThanTarget | R5 `AppointmentResponse.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `AppointmentResponse.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| AppointmentResponse.occurrenceDate | - | DoesNotExistInTarget | R5 `AppointmentResponse.occurrenceDate` does not appear in the target and has no mapping for `AppointmentResponse`. |
| AppointmentResponse.participantStatus | AppointmentResponse.participantStatus | RelatedTo | R5 `AppointmentResponse.participantStatus` maps as RelatedTo to R4 `AppointmentResponse.participantStatus` - (participantStatus failed to compare required binding of http://hl7.org/fhir/ValueSet/appointmentresponse-status|5.0.0 and http://hl7.org/fhir/ValueSet/participationstatus|4.0.1) |
| AppointmentResponse.participantType | AppointmentResponse.participantType | Equivalent | R5 `AppointmentResponse.participantType` maps as Equivalent to R4 `AppointmentResponse.participantType` |
| AppointmentResponse.proposedNewTime | - | DoesNotExistInTarget | R5 `AppointmentResponse.proposedNewTime` does not appear in the target and has no mapping for `AppointmentResponse`. |
| AppointmentResponse.recurrenceId | - | DoesNotExistInTarget | R5 `AppointmentResponse.recurrenceId` does not appear in the target and has no mapping for `AppointmentResponse`. |
| AppointmentResponse.recurring | - | DoesNotExistInTarget | R5 `AppointmentResponse.recurring` does not appear in the target and has no mapping for `AppointmentResponse`. |
| AppointmentResponse.start | AppointmentResponse.start | Equivalent | R5 `AppointmentResponse.start` maps as Equivalent to R4 `AppointmentResponse.start` |
| AppointmentResponse.text | AppointmentResponse.text | Equivalent | R5 `AppointmentResponse.text` maps as Equivalent to R4 `AppointmentResponse.text` |

