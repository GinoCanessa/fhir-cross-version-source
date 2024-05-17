Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Encounter |  | An interaction between healthcare provider(s), and/or patient(s) for the purpose of providing healthcare service(s) or assessing the health status of patient(s). | 69 | 46 |
| Target | Encounter |  | An interaction between a patient and healthcare provider(s) for the purpose of providing healthcare service(s) or assessing the health status of a patient. | 73 | 47 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 27 |
Equivalent | 4 |
RelatedTo | 38 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Encounter | Encounter | Equivalent | R5 `Encounter` maps as Equivalent to R4B `Encounter` |
| Encounter.account | Encounter.account | Equivalent | R5 `Encounter.account` maps as Equivalent to R4B `Encounter.account` |
| Encounter.actualPeriod | - | DoesNotExistInTarget | R5 `Encounter.actualPeriod` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.admission | - | DoesNotExistInTarget | R5 `Encounter.admission` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.admission.admitSource | - | DoesNotExistInTarget | R5 `Encounter.admission.admitSource` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.admission.destination | - | DoesNotExistInTarget | R5 `Encounter.admission.destination` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.admission.dischargeDisposition | - | DoesNotExistInTarget | R5 `Encounter.admission.dischargeDisposition` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.admission.extension | - | DoesNotExistInTarget | R5 `Encounter.admission.extension` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.admission.id | - | DoesNotExistInTarget | R5 `Encounter.admission.id` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.admission.modifierExtension | - | DoesNotExistInTarget | R5 `Encounter.admission.modifierExtension` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.admission.origin | - | DoesNotExistInTarget | R5 `Encounter.admission.origin` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.admission.preAdmissionIdentifier | - | DoesNotExistInTarget | R5 `Encounter.admission.preAdmissionIdentifier` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.admission.reAdmission | - | DoesNotExistInTarget | R5 `Encounter.admission.reAdmission` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.appointment | Encounter.appointment | Equivalent | R5 `Encounter.appointment` maps as Equivalent to R4B `Encounter.appointment` |
| Encounter.basedOn | Encounter.basedOn | SourceIsBroaderThanTarget | R5 `Encounter.basedOn` maps as SourceIsBroaderThanTarget to R4B `Encounter.basedOn` - basedOn has change due to type change: R5 `basedOn` `Reference` maps as SourceIsBroaderThanTarget for R4B `basedOn` |
| Encounter.careTeam | - | DoesNotExistInTarget | R5 `Encounter.careTeam` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.class | Encounter.class | RelatedTo | R5 `Encounter.class` maps as RelatedTo to R4B `Encounter.class` - class made the element mandatory; class increased the minimum cardinality from 0 to 1; class changed from array to scalar (max cardinality from * to 1); class changed the binding strength from Preferred to Extensible; class has change due to type change: R5 class CodeableConcept has no equivalent or mapped type in R4B class |
| Encounter.contained | Encounter.contained | Equivalent | R5 `Encounter.contained` maps as Equivalent to R4B `Encounter.contained` |
| Encounter.diagnosis | Encounter.diagnosis | Equivalent | R5 `Encounter.diagnosis` maps as Equivalent to R4B `Encounter.diagnosis` |
| Encounter.diagnosis.condition | Encounter.diagnosis.condition | RelatedTo | R5 `Encounter.diagnosis.condition` maps as RelatedTo to R4B `Encounter.diagnosis.condition` - condition made the element mandatory; condition increased the minimum cardinality from 0 to 1; condition changed from array to scalar (max cardinality from * to 1); condition removed a binding requirement - Example http://hl7.org/fhir/ValueSet/condition-code; condition has change due to type change: R5 condition CodeableReference has no equivalent or mapped type in R4B condition |
| Encounter.diagnosis.extension | Encounter.diagnosis.extension | SourceIsBroaderThanTarget | R5 `Encounter.diagnosis.extension` maps as SourceIsBroaderThanTarget to R4B `Encounter.diagnosis.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Encounter.diagnosis.id | Encounter.diagnosis.id | Equivalent | R5 `Encounter.diagnosis.id` maps as Equivalent to R4B `Encounter.diagnosis.id` |
| Encounter.diagnosis.modifierExtension | Encounter.diagnosis.modifierExtension | SourceIsBroaderThanTarget | R5 `Encounter.diagnosis.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Encounter.diagnosis.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Encounter.diagnosis.use | Encounter.diagnosis.use | RelatedTo | R5 `Encounter.diagnosis.use` maps as RelatedTo to R4B `Encounter.diagnosis.use` - use changed from array to scalar (max cardinality from * to 1) |
| Encounter.dietPreference | - | DoesNotExistInTarget | R5 `Encounter.dietPreference` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.episodeOfCare | Encounter.episodeOfCare | Equivalent | R5 `Encounter.episodeOfCare` maps as Equivalent to R4B `Encounter.episodeOfCare` |
| Encounter.extension | Encounter.extension | SourceIsBroaderThanTarget | R5 `Encounter.extension` maps as SourceIsBroaderThanTarget to R4B `Encounter.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Encounter.id | Encounter.id | Equivalent | R5 `Encounter.id` maps as Equivalent to R4B `Encounter.id` |
| Encounter.identifier | Encounter.identifier | Equivalent | R5 `Encounter.identifier` maps as Equivalent to R4B `Encounter.identifier` |
| Encounter.implicitRules | Encounter.implicitRules | Equivalent | R5 `Encounter.implicitRules` maps as Equivalent to R4B `Encounter.implicitRules` |
| Encounter.language | Encounter.language | RelatedTo | R5 `Encounter.language` maps as RelatedTo to R4B `Encounter.language` - language changed the binding strength from Required to Preferred |
| Encounter.length | Encounter.length | Equivalent | R5 `Encounter.length` maps as Equivalent to R4B `Encounter.length` |
| Encounter.location | Encounter.location | Equivalent | R5 `Encounter.location` maps as Equivalent to R4B `Encounter.location` |
| Encounter.location.extension | Encounter.location.extension | SourceIsBroaderThanTarget | R5 `Encounter.location.extension` maps as SourceIsBroaderThanTarget to R4B `Encounter.location.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Encounter.location.form | - | DoesNotExistInTarget | R5 `Encounter.location.form` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.location.id | Encounter.location.id | Equivalent | R5 `Encounter.location.id` maps as Equivalent to R4B `Encounter.location.id` |
| Encounter.location.location | Encounter.location.location | Equivalent | R5 `Encounter.location.location` maps as Equivalent to R4B `Encounter.location.location` |
| Encounter.location.modifierExtension | Encounter.location.modifierExtension | SourceIsBroaderThanTarget | R5 `Encounter.location.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Encounter.location.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Encounter.location.period | Encounter.location.period | Equivalent | R5 `Encounter.location.period` maps as Equivalent to R4B `Encounter.location.period` |
| Encounter.location.status | Encounter.location.status | Equivalent | R5 `Encounter.location.status` maps as Equivalent to R4B `Encounter.location.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/encounter-location-status|5.0.0 and http://hl7.org/fhir/ValueSet/encounter-location-status|4.3.0 (Equivalent) |
| Encounter.meta | Encounter.meta | Equivalent | R5 `Encounter.meta` maps as Equivalent to R4B `Encounter.meta` |
| Encounter.modifierExtension | Encounter.modifierExtension | SourceIsBroaderThanTarget | R5 `Encounter.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Encounter.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Encounter.participant | Encounter.participant | Equivalent | R5 `Encounter.participant` maps as Equivalent to R4B `Encounter.participant` |
| Encounter.participant.actor | - | DoesNotExistInTarget | R5 `Encounter.participant.actor` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.participant.extension | Encounter.participant.extension | SourceIsBroaderThanTarget | R5 `Encounter.participant.extension` maps as SourceIsBroaderThanTarget to R4B `Encounter.participant.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Encounter.participant.id | Encounter.participant.id | Equivalent | R5 `Encounter.participant.id` maps as Equivalent to R4B `Encounter.participant.id` |
| Encounter.participant.modifierExtension | Encounter.participant.modifierExtension | SourceIsBroaderThanTarget | R5 `Encounter.participant.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Encounter.participant.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Encounter.participant.period | Encounter.participant.period | Equivalent | R5 `Encounter.participant.period` maps as Equivalent to R4B `Encounter.participant.period` |
| Encounter.participant.type | Encounter.participant.type | Equivalent | R5 `Encounter.participant.type` maps as Equivalent to R4B `Encounter.participant.type` |
| Encounter.partOf | Encounter.partOf | Equivalent | R5 `Encounter.partOf` maps as Equivalent to R4B `Encounter.partOf` |
| Encounter.plannedEndDate | - | DoesNotExistInTarget | R5 `Encounter.plannedEndDate` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.plannedStartDate | - | DoesNotExistInTarget | R5 `Encounter.plannedStartDate` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.priority | Encounter.priority | Equivalent | R5 `Encounter.priority` maps as Equivalent to R4B `Encounter.priority` |
| Encounter.reason | - | DoesNotExistInTarget | R5 `Encounter.reason` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.reason.extension | - | DoesNotExistInTarget | R5 `Encounter.reason.extension` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.reason.id | - | DoesNotExistInTarget | R5 `Encounter.reason.id` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.reason.modifierExtension | - | DoesNotExistInTarget | R5 `Encounter.reason.modifierExtension` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.reason.use | - | DoesNotExistInTarget | R5 `Encounter.reason.use` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.reason.value | - | DoesNotExistInTarget | R5 `Encounter.reason.value` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.serviceProvider | Encounter.serviceProvider | Equivalent | R5 `Encounter.serviceProvider` maps as Equivalent to R4B `Encounter.serviceProvider` |
| Encounter.serviceType | Encounter.serviceType | RelatedTo | R5 `Encounter.serviceType` maps as RelatedTo to R4B `Encounter.serviceType` - serviceType changed from array to scalar (max cardinality from * to 1); serviceType has change due to type change: R5 serviceType CodeableReference has no equivalent or mapped type in R4B serviceType |
| Encounter.specialArrangement | - | DoesNotExistInTarget | R5 `Encounter.specialArrangement` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.specialCourtesy | - | DoesNotExistInTarget | R5 `Encounter.specialCourtesy` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.status | Encounter.status | RelatedTo | R5 `Encounter.status` maps as RelatedTo to R4B `Encounter.status` - status has INCOMPATIBLE required binding for code type: http://hl7.org/fhir/ValueSet/encounter-status|5.0.0 and http://hl7.org/fhir/ValueSet/encounter-status|4.3.0 |
| Encounter.subject | Encounter.subject | Equivalent | R5 `Encounter.subject` maps as Equivalent to R4B `Encounter.subject` |
| Encounter.subjectStatus | - | DoesNotExistInTarget | R5 `Encounter.subjectStatus` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.text | Encounter.text | Equivalent | R5 `Encounter.text` maps as Equivalent to R4B `Encounter.text` |
| Encounter.type | Encounter.type | Equivalent | R5 `Encounter.type` maps as Equivalent to R4B `Encounter.type` |
| Encounter.virtualService | - | DoesNotExistInTarget | R5 `Encounter.virtualService` does not appear in the target and has no mapping for `Encounter`. |

