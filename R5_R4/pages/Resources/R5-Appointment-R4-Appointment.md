Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Appointment |  | A booking of a healthcare event among patient(s), practitioner(s), related person(s) and/or device(s) for a specific date/time. This may result in one or more Encounter(s). | 84 | 61 |
| Target | Appointment |  | A booking of a healthcare event among patient(s), practitioner(s), related person(s) and/or device(s) for a specific date/time. This may result in one or more Encounter(s). | 39 | 28 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 46 |
Equivalent | 25 |
RelatedTo | 2 |
SourceIsBroaderThanTarget | 10 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Appointment | Appointment | Equivalent | R5 `Appointment` maps as Equivalent to R4 `Appointment` |
| Appointment.account | - | DoesNotExistInTarget | R5 `Appointment.account` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.appointmentType | Appointment.appointmentType | Equivalent | R5 `Appointment.appointmentType` maps as Equivalent to R4 `Appointment.appointmentType` |
| Appointment.basedOn | Appointment.basedOn | SourceIsBroaderThanTarget | R5 `Appointment.basedOn` maps as SourceIsBroaderThanTarget to R4 `Appointment.basedOn` - basedOn has change due to type change: R5 `basedOn` `Reference` maps as SourceIsBroaderThanTarget for R4 `basedOn` |
| Appointment.cancellationDate | - | DoesNotExistInTarget | R5 `Appointment.cancellationDate` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.cancellationReason | Appointment.cancelationReason | Equivalent | R5 `Appointment.cancellationReason` maps as Equivalent to R4 `Appointment.cancelationReason` |
| Appointment.class | - | DoesNotExistInTarget | R5 `Appointment.class` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.contained | Appointment.contained | Equivalent | R5 `Appointment.contained` maps as Equivalent to R4 `Appointment.contained` |
| Appointment.created | Appointment.created | Equivalent | R5 `Appointment.created` maps as Equivalent to R4 `Appointment.created` |
| Appointment.description | Appointment.description | Equivalent | R5 `Appointment.description` maps as Equivalent to R4 `Appointment.description` |
| Appointment.end | Appointment.end | Equivalent | R5 `Appointment.end` maps as Equivalent to R4 `Appointment.end` |
| Appointment.extension | Appointment.extension | SourceIsBroaderThanTarget | R5 `Appointment.extension` maps as SourceIsBroaderThanTarget to R4 `Appointment.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Appointment.id | Appointment.id | Equivalent | R5 `Appointment.id` maps as Equivalent to R4 `Appointment.id` |
| Appointment.identifier | Appointment.identifier | Equivalent | R5 `Appointment.identifier` maps as Equivalent to R4 `Appointment.identifier` |
| Appointment.implicitRules | Appointment.implicitRules | Equivalent | R5 `Appointment.implicitRules` maps as Equivalent to R4 `Appointment.implicitRules` |
| Appointment.language | Appointment.language | SourceIsNarrowerThanTarget | R5 `Appointment.language` maps as SourceIsNarrowerThanTarget to R4 `Appointment.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| Appointment.meta | Appointment.meta | Equivalent | R5 `Appointment.meta` maps as Equivalent to R4 `Appointment.meta` |
| Appointment.minutesDuration | Appointment.minutesDuration | Equivalent | R5 `Appointment.minutesDuration` maps as Equivalent to R4 `Appointment.minutesDuration` |
| Appointment.modifierExtension | Appointment.modifierExtension | SourceIsBroaderThanTarget | R5 `Appointment.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Appointment.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Appointment.note | Appointment.comment | SourceIsBroaderThanTarget | R5 `Appointment.note` maps as SourceIsBroaderThanTarget to R4 `Appointment.comment` - comment changed from array to scalar (max cardinality from * to 1); comment has change due to type change: R5 note Annotation has no equivalent or mapped type in R4 comment |
| Appointment.occurrenceChanged | - | DoesNotExistInTarget | R5 `Appointment.occurrenceChanged` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.originatingAppointment | - | DoesNotExistInTarget | R5 `Appointment.originatingAppointment` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.participant | Appointment.participant | Equivalent | R5 `Appointment.participant` maps as Equivalent to R4 `Appointment.participant` |
| Appointment.participant.actor | Appointment.participant.actor | SourceIsBroaderThanTarget | R5 `Appointment.participant.actor` maps as SourceIsBroaderThanTarget to R4 `Appointment.participant.actor` - actor has change due to type change: R5 `actor` `Reference` maps as SourceIsBroaderThanTarget for R4 `actor` |
| Appointment.participant.extension | Appointment.participant.extension | SourceIsBroaderThanTarget | R5 `Appointment.participant.extension` maps as SourceIsBroaderThanTarget to R4 `Appointment.participant.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Appointment.participant.id | Appointment.participant.id | Equivalent | R5 `Appointment.participant.id` maps as Equivalent to R4 `Appointment.participant.id` |
| Appointment.participant.modifierExtension | Appointment.participant.modifierExtension | SourceIsBroaderThanTarget | R5 `Appointment.participant.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Appointment.participant.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Appointment.participant.period | Appointment.participant.period | Equivalent | R5 `Appointment.participant.period` maps as Equivalent to R4 `Appointment.participant.period` |
| Appointment.participant.required | Appointment.participant.required | RelatedTo | R5 `Appointment.participant.required` maps as RelatedTo to R4 `Appointment.participant.required` - required added a required binding to http://hl7.org/fhir/ValueSet/participantrequired|4.0.1; required has change due to type change: R5 required boolean has no equivalent or mapped type in R4 required |
| Appointment.participant.status | Appointment.participant.status | Equivalent | R5 `Appointment.participant.status` maps as Equivalent to R4 `Appointment.participant.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/participationstatus|5.0.0 and http://hl7.org/fhir/ValueSet/participationstatus|4.0.1 (Equivalent) |
| Appointment.participant.type | Appointment.participant.type | Equivalent | R5 `Appointment.participant.type` maps as Equivalent to R4 `Appointment.participant.type` |
| Appointment.patientInstruction | Appointment.patientInstruction | SourceIsBroaderThanTarget | R5 `Appointment.patientInstruction` maps as SourceIsBroaderThanTarget to R4 `Appointment.patientInstruction` - patientInstruction changed from array to scalar (max cardinality from * to 1); patientInstruction has change due to type change: R5 patientInstruction CodeableReference has no equivalent or mapped type in R4 patientInstruction |
| Appointment.previousAppointment | - | DoesNotExistInTarget | R5 `Appointment.previousAppointment` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.priority | Appointment.priority | RelatedTo | R5 `Appointment.priority` maps as RelatedTo to R4 `Appointment.priority` - priority removed a binding requirement - Example http://terminology.hl7.org/ValueSet/v3-ActPriority; priority has change due to type change: R5 priority CodeableConcept has no equivalent or mapped type in R4 priority |
| Appointment.reason | Appointment.reasonCode | SourceIsBroaderThanTarget | R5 `Appointment.reason` maps as SourceIsBroaderThanTarget to R4 `Appointment.reasonCode` - reasonCode has change due to type change: R5 reason CodeableReference has no equivalent or mapped type in R4 reasonCode |
| Appointment.recurrenceId | - | DoesNotExistInTarget | R5 `Appointment.recurrenceId` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.excludingDate | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.excludingDate` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.excludingRecurrenceId | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.excludingRecurrenceId` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.extension | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.extension` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.id | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.id` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.lastOccurrenceDate | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.lastOccurrenceDate` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.modifierExtension | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.modifierExtension` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.monthlyTemplate | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.monthlyTemplate` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.monthlyTemplate.dayOfMonth | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.monthlyTemplate.dayOfMonth` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.monthlyTemplate.dayOfWeek | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.monthlyTemplate.dayOfWeek` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.monthlyTemplate.extension | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.monthlyTemplate.extension` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.monthlyTemplate.id | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.monthlyTemplate.id` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.monthlyTemplate.modifierExtension | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.monthlyTemplate.modifierExtension` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.monthlyTemplate.monthInterval | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.monthlyTemplate.monthInterval` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.monthlyTemplate.nthWeekOfMonth | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.monthlyTemplate.nthWeekOfMonth` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.occurrenceCount | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.occurrenceCount` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.occurrenceDate | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.occurrenceDate` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.recurrenceType | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.recurrenceType` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.timezone | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.timezone` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.weeklyTemplate | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.weeklyTemplate` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.weeklyTemplate.extension | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.weeklyTemplate.extension` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.weeklyTemplate.friday | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.weeklyTemplate.friday` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.weeklyTemplate.id | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.weeklyTemplate.id` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.weeklyTemplate.modifierExtension | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.weeklyTemplate.modifierExtension` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.weeklyTemplate.monday | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.weeklyTemplate.monday` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.weeklyTemplate.saturday | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.weeklyTemplate.saturday` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.weeklyTemplate.sunday | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.weeklyTemplate.sunday` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.weeklyTemplate.thursday | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.weeklyTemplate.thursday` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.weeklyTemplate.tuesday | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.weeklyTemplate.tuesday` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.weeklyTemplate.wednesday | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.weeklyTemplate.wednesday` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.weeklyTemplate.weekInterval | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.weeklyTemplate.weekInterval` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.yearlyTemplate | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.yearlyTemplate` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.yearlyTemplate.extension | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.yearlyTemplate.extension` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.yearlyTemplate.id | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.yearlyTemplate.id` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.yearlyTemplate.modifierExtension | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.yearlyTemplate.modifierExtension` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.recurrenceTemplate.yearlyTemplate.yearInterval | - | DoesNotExistInTarget | R5 `Appointment.recurrenceTemplate.yearlyTemplate.yearInterval` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.replaces | - | DoesNotExistInTarget | R5 `Appointment.replaces` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.requestedPeriod | Appointment.requestedPeriod | Equivalent | R5 `Appointment.requestedPeriod` maps as Equivalent to R4 `Appointment.requestedPeriod` |
| Appointment.serviceCategory | Appointment.serviceCategory | Equivalent | R5 `Appointment.serviceCategory` maps as Equivalent to R4 `Appointment.serviceCategory` |
| Appointment.serviceType | Appointment.serviceType | SourceIsBroaderThanTarget | R5 `Appointment.serviceType` maps as SourceIsBroaderThanTarget to R4 `Appointment.serviceType` - serviceType has change due to type change: R5 serviceType CodeableReference has no equivalent or mapped type in R4 serviceType |
| Appointment.slot | Appointment.slot | Equivalent | R5 `Appointment.slot` maps as Equivalent to R4 `Appointment.slot` |
| Appointment.specialty | Appointment.specialty | Equivalent | R5 `Appointment.specialty` maps as Equivalent to R4 `Appointment.specialty` |
| Appointment.start | Appointment.start | Equivalent | R5 `Appointment.start` maps as Equivalent to R4 `Appointment.start` |
| Appointment.status | Appointment.status | Equivalent | R5 `Appointment.status` maps as Equivalent to R4 `Appointment.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/appointmentstatus|5.0.0 and http://hl7.org/fhir/ValueSet/appointmentstatus|4.0.1 (Equivalent) |
| Appointment.subject | - | DoesNotExistInTarget | R5 `Appointment.subject` does not appear in the target and has no mapping for `Appointment`. |
| Appointment.supportingInformation | Appointment.supportingInformation | Equivalent | R5 `Appointment.supportingInformation` maps as Equivalent to R4 `Appointment.supportingInformation` |
| Appointment.text | Appointment.text | Equivalent | R5 `Appointment.text` maps as Equivalent to R4 `Appointment.text` |
| Appointment.virtualService | - | DoesNotExistInTarget | R5 `Appointment.virtualService` does not appear in the target and has no mapping for `Appointment`. |

