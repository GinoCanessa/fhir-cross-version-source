Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | AppointmentResponse |  | A reply to an appointment request for a patient and/or practitioner(s), such as a confirmation or rejection. | 17 | 9 |
| Target | AppointmentResponse |  | A reply to an appointment request for a patient and/or practitioner(s), such as a confirmation or rejection. | 21 | 13 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 13 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| AppointmentResponse | AppointmentResponse | Equivalent | R4B `AppointmentResponse` maps as Equivalent to R5 `AppointmentResponse` |
| AppointmentResponse.actor | AppointmentResponse.actor | SourceIsNarrowerThanTarget | R4B `AppointmentResponse.actor` maps as SourceIsNarrowerThanTarget to R5 `AppointmentResponse.actor` - actor has change due to type change: R4B `actor` `Reference` maps as SourceIsNarrowerThanTarget for R5 `actor` |
| AppointmentResponse.appointment | AppointmentResponse.appointment | Equivalent | R4B `AppointmentResponse.appointment` maps as Equivalent to R5 `AppointmentResponse.appointment` |
| AppointmentResponse.comment | AppointmentResponse.comment | SourceIsBroaderThanTarget | R4B `AppointmentResponse.comment` maps as SourceIsBroaderThanTarget to R5 `AppointmentResponse.comment` - comment has change due to type change: R4B comment string has no equivalent or mapped type in R5 comment |
| AppointmentResponse.contained | AppointmentResponse.contained | Equivalent | R4B `AppointmentResponse.contained` maps as Equivalent to R5 `AppointmentResponse.contained` |
| AppointmentResponse.end | AppointmentResponse.end | Equivalent | R4B `AppointmentResponse.end` maps as Equivalent to R5 `AppointmentResponse.end` |
| AppointmentResponse.extension | AppointmentResponse.extension | RelatedTo | R4B `AppointmentResponse.extension` maps as RelatedTo to R5 `AppointmentResponse.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| AppointmentResponse.id | AppointmentResponse.id | Equivalent | R4B `AppointmentResponse.id` maps as Equivalent to R5 `AppointmentResponse.id` |
| AppointmentResponse.identifier | AppointmentResponse.identifier | Equivalent | R4B `AppointmentResponse.identifier` maps as Equivalent to R5 `AppointmentResponse.identifier` |
| AppointmentResponse.implicitRules | AppointmentResponse.implicitRules | Equivalent | R4B `AppointmentResponse.implicitRules` maps as Equivalent to R5 `AppointmentResponse.implicitRules` |
| AppointmentResponse.language | AppointmentResponse.language | RelatedTo | R4B `AppointmentResponse.language` maps as RelatedTo to R5 `AppointmentResponse.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| AppointmentResponse.meta | AppointmentResponse.meta | Equivalent | R4B `AppointmentResponse.meta` maps as Equivalent to R5 `AppointmentResponse.meta` |
| AppointmentResponse.modifierExtension | AppointmentResponse.modifierExtension | RelatedTo | R4B `AppointmentResponse.modifierExtension` maps as RelatedTo to R5 `AppointmentResponse.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| AppointmentResponse.participantStatus | AppointmentResponse.participantStatus | Equivalent | R4B `AppointmentResponse.participantStatus` maps as Equivalent to R5 `AppointmentResponse.participantStatus` - participantStatus has compatible required binding for code type: http://hl7.org/fhir/ValueSet/participationstatus|4.3.0 and http://hl7.org/fhir/ValueSet/appointmentresponse-status|5.0.0 (Equivalent) |
| AppointmentResponse.participantType | AppointmentResponse.participantType | Equivalent | R4B `AppointmentResponse.participantType` maps as Equivalent to R5 `AppointmentResponse.participantType` |
| AppointmentResponse.start | AppointmentResponse.start | Equivalent | R4B `AppointmentResponse.start` maps as Equivalent to R5 `AppointmentResponse.start` |
| AppointmentResponse.text | AppointmentResponse.text | Equivalent | R4B `AppointmentResponse.text` maps as Equivalent to R5 `AppointmentResponse.text` |

