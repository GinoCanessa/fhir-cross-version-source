Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Appointment |  | A booking of a healthcare event among patient(s), practitioner(s), related person(s) and/or device(s) for a specific date/time. This may result in one or more Encounter(s). | 39 | 28 |
| Target | Appointment |  | A booking of a healthcare event among patient(s), practitioner(s), related person(s) and/or device(s) for a specific date/time. This may result in one or more Encounter(s). | 84 | 61 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 4 |
Equivalent | 4 |
RelatedTo | 31 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Appointment | Appointment | Equivalent | R4B `Appointment` maps as Equivalent to R5 `Appointment` |
| Appointment.appointmentType | Appointment.appointmentType | Equivalent | R4B `Appointment.appointmentType` maps as Equivalent to R5 `Appointment.appointmentType` |
| Appointment.basedOn | Appointment.basedOn | SourceIsNarrowerThanTarget | R4B `Appointment.basedOn` maps as SourceIsNarrowerThanTarget to R5 `Appointment.basedOn` - basedOn has change due to type change: R4B `basedOn` `Reference` maps as SourceIsNarrowerThanTarget for R5 `basedOn` |
| Appointment.cancelationReason | - | DoesNotExistInTarget | R4B `Appointment.cancelationReason` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.comment | - | DoesNotExistInTarget | R4B `Appointment.comment` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.contained | Appointment.contained | Equivalent | R4B `Appointment.contained` maps as Equivalent to R5 `Appointment.contained` |
| Appointment.created | Appointment.created | Equivalent | R4B `Appointment.created` maps as Equivalent to R5 `Appointment.created` |
| Appointment.description | Appointment.description | Equivalent | R4B `Appointment.description` maps as Equivalent to R5 `Appointment.description` |
| Appointment.end | Appointment.end | Equivalent | R4B `Appointment.end` maps as Equivalent to R5 `Appointment.end` |
| Appointment.extension | Appointment.extension | RelatedTo | R4B `Appointment.extension` maps as RelatedTo to R5 `Appointment.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Appointment.id | Appointment.id | Equivalent | R4B `Appointment.id` maps as Equivalent to R5 `Appointment.id` |
| Appointment.identifier | Appointment.identifier | Equivalent | R4B `Appointment.identifier` maps as Equivalent to R5 `Appointment.identifier` |
| Appointment.implicitRules | Appointment.implicitRules | Equivalent | R4B `Appointment.implicitRules` maps as Equivalent to R5 `Appointment.implicitRules` |
| Appointment.language | Appointment.language | RelatedTo | R4B `Appointment.language` maps as RelatedTo to R5 `Appointment.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Appointment.meta | Appointment.meta | Equivalent | R4B `Appointment.meta` maps as Equivalent to R5 `Appointment.meta` |
| Appointment.minutesDuration | Appointment.minutesDuration | Equivalent | R4B `Appointment.minutesDuration` maps as Equivalent to R5 `Appointment.minutesDuration` |
| Appointment.modifierExtension | Appointment.modifierExtension | RelatedTo | R4B `Appointment.modifierExtension` maps as RelatedTo to R5 `Appointment.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Appointment.participant | Appointment.participant | Equivalent | R4B `Appointment.participant` maps as Equivalent to R5 `Appointment.participant` |
| Appointment.participant.actor | Appointment.participant.actor | SourceIsNarrowerThanTarget | R4B `Appointment.participant.actor` maps as SourceIsNarrowerThanTarget to R5 `Appointment.participant.actor` - actor has change due to type change: R4B `actor` `Reference` maps as SourceIsNarrowerThanTarget for R5 `actor` |
| Appointment.participant.extension | Appointment.participant.extension | RelatedTo | R4B `Appointment.participant.extension` maps as RelatedTo to R5 `Appointment.participant.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Appointment.participant.id | Appointment.participant.id | Equivalent | R4B `Appointment.participant.id` maps as Equivalent to R5 `Appointment.participant.id` |
| Appointment.participant.modifierExtension | Appointment.participant.modifierExtension | RelatedTo | R4B `Appointment.participant.modifierExtension` maps as RelatedTo to R5 `Appointment.participant.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Appointment.participant.period | Appointment.participant.period | Equivalent | R4B `Appointment.participant.period` maps as Equivalent to R5 `Appointment.participant.period` |
| Appointment.participant.required | Appointment.participant.required | RelatedTo | R4B `Appointment.participant.required` maps as RelatedTo to R5 `Appointment.participant.required` - required removed a binding requirement - Required http://hl7.org/fhir/ValueSet/participantrequired|4.3.0; required has change due to type change: R4B required code has no equivalent or mapped type in R5 required |
| Appointment.participant.status | Appointment.participant.status | Equivalent | R4B `Appointment.participant.status` maps as Equivalent to R5 `Appointment.participant.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/participationstatus|4.3.0 and http://hl7.org/fhir/ValueSet/participationstatus|5.0.0 (Equivalent) |
| Appointment.participant.type | Appointment.participant.type | Equivalent | R4B `Appointment.participant.type` maps as Equivalent to R5 `Appointment.participant.type` |
| Appointment.patientInstruction | Appointment.patientInstruction | RelatedTo | R4B `Appointment.patientInstruction` maps as RelatedTo to R5 `Appointment.patientInstruction` - patientInstruction changed from scalar to array (max cardinality from 1 to *); patientInstruction has change due to type change: R4B patientInstruction string has no equivalent or mapped type in R5 patientInstruction |
| Appointment.priority | Appointment.priority | RelatedTo | R4B `Appointment.priority` maps as RelatedTo to R5 `Appointment.priority` - priority added a binding requirement - Example http://terminology.hl7.org/ValueSet/v3-ActPriority; priority has change due to type change: R4B priority unsignedInt has no equivalent or mapped type in R5 priority |
| Appointment.reasonCode | - | DoesNotExistInTarget | R4B `Appointment.reasonCode` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.reasonReference | - | DoesNotExistInTarget | R4B `Appointment.reasonReference` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.requestedPeriod | Appointment.requestedPeriod | Equivalent | R4B `Appointment.requestedPeriod` maps as Equivalent to R5 `Appointment.requestedPeriod` |
| Appointment.serviceCategory | Appointment.serviceCategory | Equivalent | R4B `Appointment.serviceCategory` maps as Equivalent to R5 `Appointment.serviceCategory` |
| Appointment.serviceType | Appointment.serviceType | SourceIsBroaderThanTarget | R4B `Appointment.serviceType` maps as SourceIsBroaderThanTarget to R5 `Appointment.serviceType` - serviceType has change due to type change: R4B serviceType CodeableConcept has no equivalent or mapped type in R5 serviceType |
| Appointment.slot | Appointment.slot | Equivalent | R4B `Appointment.slot` maps as Equivalent to R5 `Appointment.slot` |
| Appointment.specialty | Appointment.specialty | Equivalent | R4B `Appointment.specialty` maps as Equivalent to R5 `Appointment.specialty` |
| Appointment.start | Appointment.start | Equivalent | R4B `Appointment.start` maps as Equivalent to R5 `Appointment.start` |
| Appointment.status | Appointment.status | Equivalent | R4B `Appointment.status` maps as Equivalent to R5 `Appointment.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/appointmentstatus|4.3.0 and http://hl7.org/fhir/ValueSet/appointmentstatus|5.0.0 (Equivalent) |
| Appointment.supportingInformation | Appointment.supportingInformation | Equivalent | R4B `Appointment.supportingInformation` maps as Equivalent to R5 `Appointment.supportingInformation` |
| Appointment.text | Appointment.text | Equivalent | R4B `Appointment.text` maps as Equivalent to R5 `Appointment.text` |

