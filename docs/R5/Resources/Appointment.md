Comparison of 
Generated at Friday, April 4, 2025 2:59:01 PM

### Appointment

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Appointment |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Appointment` |
| Version | 5.0.0 |
| Description | A booking of a healthcare event among patient(s), practitioner(s), related person(s) and/or device(s) for a specific date/time. This may result in one or more Encounter(s). |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2254` |
| Database Snapshot Count | `84` |
| Database Differential Count | `61` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Appointment` | `Appointment` | `Appointment` | Appointment | A booking of a healthcare event among patient(s), practitioner(s), related person(s) and/or device(s) for a specific date/time. This may result in one or more Encounter(s) | 0..* | Appointment |  |  |
| `Appointment.account` | `Appointment.account` | `account` | Appointment.account | The set of accounts that may be used for billing for this Appointment | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Account) |  |  |
| `Appointment.appointmentType` | `Appointment.appointmentType` | `appointmentType` | Appointment.appointmentType | The style of appointment or patient that has been booked in the slot (not service type) | 0..1 | CodeableConcept | `Preferred` | `http://terminology.hl7.org/ValueSet/v2-0276` |
| `Appointment.basedOn` | `Appointment.basedOn` | `basedOn` | Appointment.basedOn | The request this appointment is allocated to assess | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/CarePlan), Reference(http://hl7.org/fhir/StructureDefinition/DeviceRequest), Reference(http://hl7.org/fhir/StructureDefinition/MedicationRequest), Reference(http://hl7.org/fhir/StructureDefinition/ServiceRequest) |  |  |
| `Appointment.cancellationDate` | `Appointment.cancellationDate` | `cancellationDate` | Appointment.cancellationDate | When the appointment was cancelled | 0..1 | dateTime |  |  |
| `Appointment.cancellationReason` | `Appointment.cancellationReason` | `cancellationReason` | Appointment.cancellationReason | The coded reason for the appointment being cancelled | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/appointment-cancellation-reason` |
| `Appointment.class` | `Appointment.class` | `class` | Appointment.class | Classification when becoming an encounter | 0..* | CodeableConcept | `Preferred` | `http://terminology.hl7.org/ValueSet/EncounterClass` |
| `Appointment.contained` | `Appointment.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Appointment.created` | `Appointment.created` | `created` | Appointment.created | The date that this appointment was initially created | 0..1 | dateTime |  |  |
| `Appointment.description` | `Appointment.description` | `description` | Appointment.description | Shown on a subject line in a meeting request, or appointment list | 0..1 | string |  |  |
| `Appointment.end` | `Appointment.end` | `end` | Appointment.end | When appointment is to conclude | 0..1 | instant |  |  |
| `Appointment.extension` | `Appointment.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Appointment.id` | `Appointment.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Appointment.identifier` | `Appointment.identifier` | `identifier` | Appointment.identifier | External Ids for this item | 0..* | Identifier |  |  |
| `Appointment.implicitRules` | `Appointment.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Appointment.language` | `Appointment.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `Appointment.meta` | `Appointment.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Appointment.minutesDuration` | `Appointment.minutesDuration` | `minutesDuration` | Appointment.minutesDuration | Can be less than start/end (e.g. estimate) | 0..1 | positiveInt |  |  |
| `Appointment.modifierExtension` | `Appointment.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Appointment.note` | `Appointment.note` | `note` | Appointment.note | Additional comments | 0..* | Annotation |  |  |
| `Appointment.occurrenceChanged` | `Appointment.occurrenceChanged` | `occurrenceChanged` | Appointment.occurrenceChanged | Indicates that this appointment varies from a recurrence pattern | 0..1 | boolean |  |  |
| `Appointment.originatingAppointment` | `Appointment.originatingAppointment` | `originatingAppointment` | Appointment.originatingAppointment | The originating appointment in a recurring set of appointments | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Appointment) |  |  |
| `Appointment.participant` | `Appointment.participant` | `participant` | Appointment.participant | Participants involved in appointment | 1..* | BackboneElement |  |  |
| `Appointment.participant.actor` | `Appointment.participant.actor` | `actor` | Appointment.participant.actor | The individual, device, location, or service participating in the appointment | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/CareTeam), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/HealthcareService), Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Appointment.participant.extension` | `Appointment.participant.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Appointment.participant.id` | `Appointment.participant.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Appointment.participant.modifierExtension` | `Appointment.participant.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Appointment.participant.period` | `Appointment.participant.period` | `period` | Appointment.participant.period | Participation period of the actor | 0..1 | Period |  |  |
| `Appointment.participant.required` | `Appointment.participant.required` | `required` | Appointment.participant.required | The participant is required to attend (optional when false) | 0..1 | boolean |  |  |
| `Appointment.participant.status` | `Appointment.participant.status` | `status` | Appointment.participant.status | accepted \| declined \| tentative \| needs-action | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/participationstatus|5.0.0` |
| `Appointment.participant.type` | `Appointment.participant.type` | `type` | Appointment.participant.type | Role of participant in the appointment | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/encounter-participant-type` |
| `Appointment.patientInstruction` | `Appointment.patientInstruction` | `patientInstruction` | Appointment.patientInstruction | Detailed information and instructions for the patient | 0..* | CodeableReference(http://hl7.org/fhir/StructureDefinition/Binary), CodeableReference(http://hl7.org/fhir/StructureDefinition/Communication), CodeableReference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `Appointment.previousAppointment` | `Appointment.previousAppointment` | `previousAppointment` | Appointment.previousAppointment | The previous appointment in a series | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Appointment) |  |  |
| `Appointment.priority` | `Appointment.priority` | `priority` | Appointment.priority | Used to make informed decisions if needing to re-prioritize | 0..1 | CodeableConcept | `Example` | `http://terminology.hl7.org/ValueSet/v3-ActPriority` |
| `Appointment.reason` | `Appointment.reason` | `reason` | Appointment.reason | Reason this appointment is scheduled | 0..* | CodeableReference(http://hl7.org/fhir/StructureDefinition/Condition), CodeableReference(http://hl7.org/fhir/StructureDefinition/ImmunizationRecommendation), CodeableReference(http://hl7.org/fhir/StructureDefinition/Observation), CodeableReference(http://hl7.org/fhir/StructureDefinition/Procedure) | `Preferred` | `http://hl7.org/fhir/ValueSet/encounter-reason` |
| `Appointment.recurrenceId` | `Appointment.recurrenceId` | `recurrenceId` | Appointment.recurrenceId | The sequence number in the recurrence | 0..1 | positiveInt |  |  |
| `Appointment.recurrenceTemplate` | `Appointment.recurrenceTemplate` | `recurrenceTemplate` | Appointment.recurrenceTemplate | Details of the recurrence pattern/template used to generate occurrences | 0..* | BackboneElement |  |  |
| `Appointment.recurrenceTemplate.excludingDate` | `Appointment.recurrenceTemplate.excludingDate` | `excludingDate` | Appointment.recurrenceTemplate.excludingDate | Any dates that should be excluded from the series | 0..* | date |  |  |
| `Appointment.recurrenceTemplate.excludingRecurrenceId` | `Appointment.recurrenceTemplate.excludingRecurrenceId` | `excludingRecurrenceId` | Appointment.recurrenceTemplate.excludingRecurrenceId | Any recurrence IDs that should be excluded from the recurrence | 0..* | positiveInt |  |  |
| `Appointment.recurrenceTemplate.extension` | `Appointment.recurrenceTemplate.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Appointment.recurrenceTemplate.id` | `Appointment.recurrenceTemplate.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Appointment.recurrenceTemplate.lastOccurrenceDate` | `Appointment.recurrenceTemplate.lastOccurrenceDate` | `lastOccurrenceDate` | Appointment.recurrenceTemplate.lastOccurrenceDate | The date when the recurrence should end | 0..1 | date |  |  |
| `Appointment.recurrenceTemplate.modifierExtension` | `Appointment.recurrenceTemplate.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Appointment.recurrenceTemplate.monthlyTemplate` | `Appointment.recurrenceTemplate.monthlyTemplate` | `monthlyTemplate` | Appointment.recurrenceTemplate.monthlyTemplate | Information about monthly recurring appointments | 0..1 | BackboneElement |  |  |
| `Appointment.recurrenceTemplate.monthlyTemplate.dayOfMonth` | `Appointment.recurrenceTemplate.monthlyTemplate.dayOfMonth` | `dayOfMonth` | Appointment.recurrenceTemplate.monthlyTemplate.dayOfMonth | Recurs on a specific day of the month | 0..1 | positiveInt |  |  |
| `Appointment.recurrenceTemplate.monthlyTemplate.dayOfWeek` | `Appointment.recurrenceTemplate.monthlyTemplate.dayOfWeek` | `dayOfWeek` | Appointment.recurrenceTemplate.monthlyTemplate.dayOfWeek | Indicates which day of the week the appointment should occur | 0..1 | Coding | `Required` | `http://hl7.org/fhir/ValueSet/days-of-week|5.0.0` |
| `Appointment.recurrenceTemplate.monthlyTemplate.extension` | `Appointment.recurrenceTemplate.monthlyTemplate.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Appointment.recurrenceTemplate.monthlyTemplate.id` | `Appointment.recurrenceTemplate.monthlyTemplate.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Appointment.recurrenceTemplate.monthlyTemplate.modifierExtension` | `Appointment.recurrenceTemplate.monthlyTemplate.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Appointment.recurrenceTemplate.monthlyTemplate.monthInterval` | `Appointment.recurrenceTemplate.monthlyTemplate.monthInterval` | `monthInterval` | Appointment.recurrenceTemplate.monthlyTemplate.monthInterval | Recurs every nth month | 1..1 | positiveInt |  |  |
| `Appointment.recurrenceTemplate.monthlyTemplate.nthWeekOfMonth` | `Appointment.recurrenceTemplate.monthlyTemplate.nthWeekOfMonth` | `nthWeekOfMonth` | Appointment.recurrenceTemplate.monthlyTemplate.nthWeekOfMonth | Indicates which week of the month the appointment should occur | 0..1 | Coding | `Required` | `http://hl7.org/fhir/ValueSet/week-of-month|5.0.0` |
| `Appointment.recurrenceTemplate.occurrenceCount` | `Appointment.recurrenceTemplate.occurrenceCount` | `occurrenceCount` | Appointment.recurrenceTemplate.occurrenceCount | The number of planned occurrences | 0..1 | positiveInt |  |  |
| `Appointment.recurrenceTemplate.occurrenceDate` | `Appointment.recurrenceTemplate.occurrenceDate` | `occurrenceDate` | Appointment.recurrenceTemplate.occurrenceDate | Specific dates for a recurring set of appointments (no template) | 0..* | date |  |  |
| `Appointment.recurrenceTemplate.recurrenceType` | `Appointment.recurrenceTemplate.recurrenceType` | `recurrenceType` | Appointment.recurrenceTemplate.recurrenceType | The frequency of the recurrence | 1..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/appointment-recurrrence-type` |
| `Appointment.recurrenceTemplate.timezone` | `Appointment.recurrenceTemplate.timezone` | `timezone` | Appointment.recurrenceTemplate.timezone | The timezone of the occurrences | 0..1 | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/timezones|5.0.0` |
| `Appointment.recurrenceTemplate.weeklyTemplate` | `Appointment.recurrenceTemplate.weeklyTemplate` | `weeklyTemplate` | Appointment.recurrenceTemplate.weeklyTemplate | Information about weekly recurring appointments | 0..1 | BackboneElement |  |  |
| `Appointment.recurrenceTemplate.weeklyTemplate.extension` | `Appointment.recurrenceTemplate.weeklyTemplate.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Appointment.recurrenceTemplate.weeklyTemplate.friday` | `Appointment.recurrenceTemplate.weeklyTemplate.friday` | `friday` | Appointment.recurrenceTemplate.weeklyTemplate.friday | Recurs on Friday | 0..1 | boolean |  |  |
| `Appointment.recurrenceTemplate.weeklyTemplate.id` | `Appointment.recurrenceTemplate.weeklyTemplate.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Appointment.recurrenceTemplate.weeklyTemplate.modifierExtension` | `Appointment.recurrenceTemplate.weeklyTemplate.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Appointment.recurrenceTemplate.weeklyTemplate.monday` | `Appointment.recurrenceTemplate.weeklyTemplate.monday` | `monday` | Appointment.recurrenceTemplate.weeklyTemplate.monday | Recurs on Mondays | 0..1 | boolean |  |  |
| `Appointment.recurrenceTemplate.weeklyTemplate.saturday` | `Appointment.recurrenceTemplate.weeklyTemplate.saturday` | `saturday` | Appointment.recurrenceTemplate.weeklyTemplate.saturday | Recurs on Saturday | 0..1 | boolean |  |  |
| `Appointment.recurrenceTemplate.weeklyTemplate.sunday` | `Appointment.recurrenceTemplate.weeklyTemplate.sunday` | `sunday` | Appointment.recurrenceTemplate.weeklyTemplate.sunday | Recurs on Sunday | 0..1 | boolean |  |  |
| `Appointment.recurrenceTemplate.weeklyTemplate.thursday` | `Appointment.recurrenceTemplate.weeklyTemplate.thursday` | `thursday` | Appointment.recurrenceTemplate.weeklyTemplate.thursday | Recurs on Thursday | 0..1 | boolean |  |  |
| `Appointment.recurrenceTemplate.weeklyTemplate.tuesday` | `Appointment.recurrenceTemplate.weeklyTemplate.tuesday` | `tuesday` | Appointment.recurrenceTemplate.weeklyTemplate.tuesday | Recurs on Tuesday | 0..1 | boolean |  |  |
| `Appointment.recurrenceTemplate.weeklyTemplate.wednesday` | `Appointment.recurrenceTemplate.weeklyTemplate.wednesday` | `wednesday` | Appointment.recurrenceTemplate.weeklyTemplate.wednesday | Recurs on Wednesday | 0..1 | boolean |  |  |
| `Appointment.recurrenceTemplate.weeklyTemplate.weekInterval` | `Appointment.recurrenceTemplate.weeklyTemplate.weekInterval` | `weekInterval` | Appointment.recurrenceTemplate.weeklyTemplate.weekInterval | Recurs every nth week | 0..1 | positiveInt |  |  |
| `Appointment.recurrenceTemplate.yearlyTemplate` | `Appointment.recurrenceTemplate.yearlyTemplate` | `yearlyTemplate` | Appointment.recurrenceTemplate.yearlyTemplate | Information about yearly recurring appointments | 0..1 | BackboneElement |  |  |
| `Appointment.recurrenceTemplate.yearlyTemplate.extension` | `Appointment.recurrenceTemplate.yearlyTemplate.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Appointment.recurrenceTemplate.yearlyTemplate.id` | `Appointment.recurrenceTemplate.yearlyTemplate.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Appointment.recurrenceTemplate.yearlyTemplate.modifierExtension` | `Appointment.recurrenceTemplate.yearlyTemplate.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Appointment.recurrenceTemplate.yearlyTemplate.yearInterval` | `Appointment.recurrenceTemplate.yearlyTemplate.yearInterval` | `yearInterval` | Appointment.recurrenceTemplate.yearlyTemplate.yearInterval | Recurs every nth year | 1..1 | positiveInt |  |  |
| `Appointment.replaces` | `Appointment.replaces` | `replaces` | Appointment.replaces | Appointment replaced by this Appointment | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Appointment) |  |  |
| `Appointment.requestedPeriod` | `Appointment.requestedPeriod` | `requestedPeriod` | Appointment.requestedPeriod | Potential date/time interval(s) requested to allocate the appointment within | 0..* | Period |  |  |
| `Appointment.serviceCategory` | `Appointment.serviceCategory` | `serviceCategory` | Appointment.serviceCategory | A broad categorization of the service that is to be performed during this appointment | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/service-category` |
| `Appointment.serviceType` | `Appointment.serviceType` | `serviceType` | Appointment.serviceType | The specific service that is to be performed during this appointment | 0..* | CodeableReference(http://hl7.org/fhir/StructureDefinition/HealthcareService) | `Example` | `http://hl7.org/fhir/ValueSet/service-type` |
| `Appointment.slot` | `Appointment.slot` | `slot` | Appointment.slot | The slots that this appointment is filling | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Slot) |  |  |
| `Appointment.specialty` | `Appointment.specialty` | `specialty` | Appointment.specialty | The specialty of a practitioner that would be required to perform the service requested in this appointment | 0..* | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/c80-practice-codes` |
| `Appointment.start` | `Appointment.start` | `start` | Appointment.start | When appointment is to take place | 0..1 | instant |  |  |
| `Appointment.status` | `Appointment.status` | `status` | Appointment.status | proposed \| pending \| booked \| arrived \| fulfilled \| cancelled \| noshow \| entered-in-error \| checked-in \| waitlist | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/appointmentstatus|5.0.0` |
| `Appointment.subject` | `Appointment.subject` | `subject` | Appointment.subject | The patient or group associated with the appointment | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `Appointment.supportingInformation` | `Appointment.supportingInformation` | `supportingInformation` | Appointment.supportingInformation | Additional information to support the appointment | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `Appointment.text` | `Appointment.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Appointment.virtualService` | `Appointment.virtualService` | `virtualService` | Appointment.virtualService | Connection details of a virtual service (e.g. conference call) | 0..* | VirtualServiceDetail |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Appointment](/docs/R2/Resources/Appointment.md)<br/> `http://hl7.org/fhir/StructureDefinition/Appointment\|1.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `74`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `240`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Appointment](/docs/R3/Resources/Appointment.md)<br/> `http://hl7.org/fhir/StructureDefinition/Appointment\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `419`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `615`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Appointment](/docs/R4/Resources/Appointment.md)<br/> `http://hl7.org/fhir/StructureDefinition/Appointment\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1395`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1396`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Appointment](/docs/R4B/Resources/Appointment.md)<br/> `http://hl7.org/fhir/StructureDefinition/Appointment\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `933`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1162`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Appointment](/docs/R5/Resources/Appointment.md)<br/> `http://hl7.org/fhir/StructureDefinition/Appointment\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Appointment from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Appointment](/docs/R2/Resources/Appointment.md)| Relationship | [R3 Appointment](/docs/R3/Resources/Appointment.md)| Relationship | [R4 Appointment](/docs/R4/Resources/Appointment.md)| Relationship | [R4B Appointment](/docs/R4B/Resources/Appointment.md)| Relationship | R5 Appointment
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Appointment`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(2983)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2984)| `Appointment`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10184)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10185)| `Appointment`| _Equivalent_<br/>(21735/21736)| `Appointment`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36846)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36847)| **`Appointment`**
| `Appointment.id`| _Equivalent_<br/>(2985/2986)| `Appointment.id`| _Equivalent_<br/>(10186/10187)| `Appointment.id`| _Equivalent_<br/>(21737/21738)| `Appointment.id`| _Equivalent_<br/>(36848/36849)| **`Appointment.id`**
| `Appointment.meta`| _Equivalent_<br/>(2987/2988)| `Appointment.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10188)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10189)| `Appointment.meta`| _Equivalent_<br/>(21739/21740)| `Appointment.meta`| _Equivalent_<br/>(36850/36851)| **`Appointment.meta`**
| `Appointment.implicitRules`| _Equivalent_<br/>(2989/2990)| `Appointment.implicitRules`| _Equivalent_<br/>(10190/10191)| `Appointment.implicitRules`| _Equivalent_<br/>(21741/21742)| `Appointment.implicitRules`| _Equivalent_<br/>(36852/36853)| **`Appointment.implicitRules`**
| `Appointment.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(2991)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2992)| `Appointment.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10192)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(10193)| `Appointment.language`| _Equivalent_<br/>(21743/21744)| `Appointment.language`| _Equivalent_<br/>(36854/36855)| **`Appointment.language`**
| `Appointment.text`| _Equivalent_<br/>(2993/2994)| `Appointment.text`| _Equivalent_<br/>(10194/10195)| `Appointment.text`| _Equivalent_<br/>(21745/21746)| `Appointment.text`| _Equivalent_<br/>(36856/36857)| **`Appointment.text`**
| `Appointment.contained`| _Equivalent_<br/>(2995/2996)| `Appointment.contained`| _Equivalent_<br/>(10196/10197)| `Appointment.contained`| _Equivalent_<br/>(21747/21748)| `Appointment.contained`| _Equivalent_<br/>(36858/36859)| **`Appointment.contained`**
| `Appointment.extension`| _Equivalent_<br/>(2997/2998)| `Appointment.extension`| _Equivalent_<br/>(10198/10199)| `Appointment.extension`| _Equivalent_<br/>(21749/21750)| `Appointment.extension`| _Equivalent_<br/>(36860/36861)| **`Appointment.extension`**
| `Appointment.modifierExtension`| _Equivalent_<br/>(2999/3000)| `Appointment.modifierExtension`| _Equivalent_<br/>(10200/10201)| `Appointment.modifierExtension`| _Equivalent_<br/>(21751/21752)| `Appointment.modifierExtension`| _Equivalent_<br/>(36862/36863)| **`Appointment.modifierExtension`**
| `Appointment.identifier`| _Equivalent_<br/>(3001/3002)| `Appointment.identifier`| _Equivalent_<br/>(10202/10203)| `Appointment.identifier`| _Equivalent_<br/>(21753/21754)| `Appointment.identifier`| _Equivalent_<br/>(36864/36865)| **`Appointment.identifier`**
| `Appointment.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3003)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3004)| `Appointment.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10204)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10205)| `Appointment.status`| _Equivalent_<br/>(21755/21756)| `Appointment.status`| _Equivalent_<br/>(36866/36867)| **`Appointment.status`**
| | | | | `Appointment.cancelationReason`| _Equivalent_<br/>(21757/21758)| `Appointment.cancelationReason`| _Equivalent_<br/>(1721/1965)| **`Appointment.cancellationReason`**
| | | | | | | | | **`Appointment.class`**
| | | `Appointment.serviceCategory`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10206)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10207)| `Appointment.serviceCategory`| _Equivalent_<br/>(21759/21760)| `Appointment.serviceCategory`| _Equivalent_<br/>(36868/36869)| **`Appointment.serviceCategory`**
| `Appointment.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(467)| `Appointment.serviceType`| _Equivalent_<br/>(10208/10209)| `Appointment.serviceType`| _Equivalent_<br/>(21761/21762)| `Appointment.serviceType`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(36870)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36871)| **`Appointment.serviceType`**
| | | `Appointment.specialty`| _Equivalent_<br/>(10210/10211)| `Appointment.specialty`| _Equivalent_<br/>(21763/21764)| `Appointment.specialty`| _Equivalent_<br/>(36872/36873)| **`Appointment.specialty`**
| | | `Appointment.appointmentType`| _Equivalent_<br/>(10212/10213)| `Appointment.appointmentType`| _Equivalent_<br/>(21765/21766)| `Appointment.appointmentType`| _Equivalent_<br/>(36874/36875)| **`Appointment.appointmentType`**
| `Appointment.reason`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3005)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(3006)| `Appointment.reason`| _Equivalent_<br/>(813/1350)| `Appointment.reasonCode`| _Equivalent_<br/>(21767/21768)| `Appointment.reasonCode`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1722)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1966)| **`Appointment.reason`**
| `Appointment.priority`| _Equivalent_<br/>(3007/3008)| `Appointment.priority`| _Equivalent_<br/>(10214/10215)| `Appointment.priority`| _Equivalent_<br/>(21771/21772)| `Appointment.priority`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(36877)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36878)| **`Appointment.priority`**
| `Appointment.description`| _Equivalent_<br/>(3009/3010)| `Appointment.description`| _Equivalent_<br/>(10216/10217)| `Appointment.description`| _Equivalent_<br/>(21773/21774)| `Appointment.description`| _Equivalent_<br/>(36879/36880)| **`Appointment.description`**
| | | | | | | | | **`Appointment.replaces`**
| | | | | | | | | **`Appointment.virtualService`**
| | | `Appointment.supportingInformation`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10218)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10219)| `Appointment.supportingInformation`| _Equivalent_<br/>(21775/21776)| `Appointment.supportingInformation`| _Equivalent_<br/>(36881/36882)| **`Appointment.supportingInformation`**
| | | | | | | | | **`Appointment.previousAppointment`**
| | | | | | | | | **`Appointment.originatingAppointment`**
| `Appointment.start`| _Equivalent_<br/>(3011/3012)| `Appointment.start`| _Equivalent_<br/>(10220/10221)| `Appointment.start`| _Equivalent_<br/>(21777/21778)| `Appointment.start`| _Equivalent_<br/>(36883/36884)| **`Appointment.start`**
| `Appointment.end`| _Equivalent_<br/>(3013/3014)| `Appointment.end`| _Equivalent_<br/>(10222/10223)| `Appointment.end`| _Equivalent_<br/>(21779/21780)| `Appointment.end`| _Equivalent_<br/>(36885/36886)| **`Appointment.end`**
| `Appointment.minutesDuration`| _Equivalent_<br/>(3015/3016)| `Appointment.minutesDuration`| _Equivalent_<br/>(10224/10225)| `Appointment.minutesDuration`| _Equivalent_<br/>(21781/21782)| `Appointment.minutesDuration`| _Equivalent_<br/>(36887/36888)| **`Appointment.minutesDuration`**
| | | `Appointment.requestedPeriod`| _Equivalent_<br/>(10248/10249)| `Appointment.requestedPeriod`| _Equivalent_<br/>(21811/21812)| `Appointment.requestedPeriod`| _Equivalent_<br/>(36915/36916)| **`Appointment.requestedPeriod`**
| `Appointment.slot`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3017)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3018)| `Appointment.slot`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10226)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10227)| `Appointment.slot`| _Equivalent_<br/>(21783/21784)| `Appointment.slot`| _Equivalent_<br/>(36889/36890)| **`Appointment.slot`**
| | | | | | | | | **`Appointment.account`**
| | | `Appointment.created`| _Equivalent_<br/>(10228/10229)| `Appointment.created`| _Equivalent_<br/>(21785/21786)| `Appointment.created`| _Equivalent_<br/>(36891/36892)| **`Appointment.created`**
| | | | | | | | | **`Appointment.cancellationDate`**
| `Appointment.comment`| _Equivalent_<br/>(3019/3020)| `Appointment.comment`| _Equivalent_<br/>(10230/10231)| `Appointment.comment`| _Equivalent_<br/>(21787/21788)| `Appointment.comment`| →→→→ _RelatedTo_ →→→→ <br/>(1723)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1967)| **`Appointment.note`**
| | | | | `Appointment.patientInstruction`| _Equivalent_<br/>(21789/21790)| `Appointment.patientInstruction`| →→→→ _RelatedTo_ →→→→ <br/>(36893)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36894)| **`Appointment.patientInstruction`**
| | | `Appointment.incomingReferral`| →→→→ _RelatedTo_ →→→→ <br/>(811)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1349)| `Appointment.basedOn`| _Equivalent_<br/>(21791/21792)| `Appointment.basedOn`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(36895)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36896)| **`Appointment.basedOn`**
| | | | | | | | | **`Appointment.subject`**
| `Appointment.participant`| _Equivalent_<br/>(3021/3022)| `Appointment.participant`| _Equivalent_<br/>(10232/10233)| `Appointment.participant`| _Equivalent_<br/>(21793/21794)| `Appointment.participant`| _Equivalent_<br/>(36897/36898)| **`Appointment.participant`**
| `Appointment.participant.id`| _Equivalent_<br/>(3023/3024)| `Appointment.participant.id`| _Equivalent_<br/>(10234/10235)| `Appointment.participant.id`| _Equivalent_<br/>(21795/21796)| `Appointment.participant.id`| _Equivalent_<br/>(36899/36900)| **`Appointment.participant.id`**
| `Appointment.participant.extension`| _Equivalent_<br/>(3025/3026)| `Appointment.participant.extension`| _Equivalent_<br/>(10236/10237)| `Appointment.participant.extension`| _Equivalent_<br/>(21797/21798)| `Appointment.participant.extension`| _Equivalent_<br/>(36901/36902)| **`Appointment.participant.extension`**
| `Appointment.participant.modifierExtension`| _Equivalent_<br/>(3027/3028)| `Appointment.participant.modifierExtension`| _Equivalent_<br/>(10238/10239)| `Appointment.participant.modifierExtension`| _Equivalent_<br/>(21799/21800)| `Appointment.participant.modifierExtension`| _Equivalent_<br/>(36903/36904)| **`Appointment.participant.modifierExtension`**
| `Appointment.participant.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3029)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(3030)| `Appointment.participant.type`| _Equivalent_<br/>(10240/10241)| `Appointment.participant.type`| _Equivalent_<br/>(21801/21802)| `Appointment.participant.type`| _Equivalent_<br/>(36905/36906)| **`Appointment.participant.type`**
| | | | | `Appointment.participant.period`| _Equivalent_<br/>(21809/21810)| `Appointment.participant.period`| _Equivalent_<br/>(36913/36914)| **`Appointment.participant.period`**
| `Appointment.participant.actor`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3031)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3032)| `Appointment.participant.actor`| →→→→ _RelatedTo_ →→→→ <br/>(10242)<hr/>←←←← _RelatedTo_ ←←←← <br/>(10243)| `Appointment.participant.actor`| _Equivalent_<br/>(21803/21804)| `Appointment.participant.actor`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(36907)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36908)| **`Appointment.participant.actor`**
| `Appointment.participant.required`| _Equivalent_<br/>(3033/3034)| `Appointment.participant.required`| _Equivalent_<br/>(10244/10245)| `Appointment.participant.required`| _Equivalent_<br/>(21805/21806)| `Appointment.participant.required`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36909)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36910)| **`Appointment.participant.required`**
| `Appointment.participant.status`| _Equivalent_<br/>(3035/3036)| `Appointment.participant.status`| _Equivalent_<br/>(10246/10247)| `Appointment.participant.status`| _Equivalent_<br/>(21807/21808)| `Appointment.participant.status`| _Equivalent_<br/>(36911/36912)| **`Appointment.participant.status`**
| | | | | | | | | **`Appointment.recurrenceId`**
| | | | | | | | | **`Appointment.occurrenceChanged`**
| | | | | | | | | **`Appointment.recurrenceTemplate`**
| | | | | | | | | **`Appointment.recurrenceTemplate.id`**
| | | | | | | | | **`Appointment.recurrenceTemplate.extension`**
| | | | | | | | | **`Appointment.recurrenceTemplate.modifierExtension`**
| | | | | | | | | **`Appointment.recurrenceTemplate.timezone`**
| | | | | | | | | **`Appointment.recurrenceTemplate.recurrenceType`**
| | | | | | | | | **`Appointment.recurrenceTemplate.lastOccurrenceDate`**
| | | | | | | | | **`Appointment.recurrenceTemplate.occurrenceCount`**
| | | | | | | | | **`Appointment.recurrenceTemplate.occurrenceDate`**
| | | | | | | | | **`Appointment.recurrenceTemplate.weeklyTemplate`**
| | | | | | | | | **`Appointment.recurrenceTemplate.weeklyTemplate.id`**
| | | | | | | | | **`Appointment.recurrenceTemplate.weeklyTemplate.extension`**
| | | | | | | | | **`Appointment.recurrenceTemplate.weeklyTemplate.modifierExtension`**
| | | | | | | | | **`Appointment.recurrenceTemplate.weeklyTemplate.monday`**
| | | | | | | | | **`Appointment.recurrenceTemplate.weeklyTemplate.tuesday`**
| | | | | | | | | **`Appointment.recurrenceTemplate.weeklyTemplate.wednesday`**
| | | | | | | | | **`Appointment.recurrenceTemplate.weeklyTemplate.thursday`**
| | | | | | | | | **`Appointment.recurrenceTemplate.weeklyTemplate.friday`**
| | | | | | | | | **`Appointment.recurrenceTemplate.weeklyTemplate.saturday`**
| | | | | | | | | **`Appointment.recurrenceTemplate.weeklyTemplate.sunday`**
| | | | | | | | | **`Appointment.recurrenceTemplate.weeklyTemplate.weekInterval`**
| | | | | | | | | **`Appointment.recurrenceTemplate.monthlyTemplate`**
| | | | | | | | | **`Appointment.recurrenceTemplate.monthlyTemplate.id`**
| | | | | | | | | **`Appointment.recurrenceTemplate.monthlyTemplate.extension`**
| | | | | | | | | **`Appointment.recurrenceTemplate.monthlyTemplate.modifierExtension`**
| | | | | | | | | **`Appointment.recurrenceTemplate.monthlyTemplate.dayOfMonth`**
| | | | | | | | | **`Appointment.recurrenceTemplate.monthlyTemplate.nthWeekOfMonth`**
| | | | | | | | | **`Appointment.recurrenceTemplate.monthlyTemplate.dayOfWeek`**
| | | | | | | | | **`Appointment.recurrenceTemplate.monthlyTemplate.monthInterval`**
| | | | | | | | | **`Appointment.recurrenceTemplate.yearlyTemplate`**
| | | | | | | | | **`Appointment.recurrenceTemplate.yearlyTemplate.id`**
| | | | | | | | | **`Appointment.recurrenceTemplate.yearlyTemplate.extension`**
| | | | | | | | | **`Appointment.recurrenceTemplate.yearlyTemplate.modifierExtension`**
| | | | | | | | | **`Appointment.recurrenceTemplate.yearlyTemplate.yearInterval`**
| | | | | | | | | **`Appointment.recurrenceTemplate.excludingDate`**
| | | | | | | | | **`Appointment.recurrenceTemplate.excludingRecurrenceId`**
| *28 of 28 elements used* | | *35 of 36 elements used* <br/>remaining elements:<br/>`Appointment.indication`| | *38 of 39 elements used* <br/>remaining elements:<br/>`Appointment.reasonReference`| | *38 of 39 elements used* <br/>remaining elements:<br/>`Appointment.reasonReference`| | *84 of 84 elements used* 

