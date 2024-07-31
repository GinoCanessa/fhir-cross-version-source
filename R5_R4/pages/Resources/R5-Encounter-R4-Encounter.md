Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Encounter |  | An interaction between healthcare provider(s), and/or patient(s) for the purpose of providing healthcare service(s) or assessing the health status of patient(s). | 69 | 46 |
| Target | Encounter |  | An interaction between a patient and healthcare provider(s) for the purpose of providing healthcare service(s) or assessing the health status of a patient. | 73 | 47 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 13 |
Equivalent | 38 |
RelatedTo | 3 |
SourceIsBroaderThanTarget | 13 |
SourceIsNarrowerThanTarget | 2 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Encounter | Encounter | SourceIsNarrowerThanTarget | R5 `Encounter` is narrower than R4 `Encounter` and is compatible. `Encounter` is mapped from `Encounter` and `Encounter.class`. |
| Encounter.account | Encounter.account | Equivalent | R5 `Encounter.account` maps as Equivalent to R4 `Encounter.account` |
| Encounter.actualPeriod | Encounter.period | Equivalent | R5 `Encounter.actualPeriod` maps as Equivalent to R4 `Encounter.period` |
| Encounter.admission | Encounter.hospitalization | Equivalent | R5 `Encounter.admission` maps as Equivalent to R4 `Encounter.hospitalization` |
| Encounter.admission.admitSource | Encounter.hospitalization.admitSource | Equivalent | R5 `Encounter.admission.admitSource` maps as Equivalent to R4 `Encounter.hospitalization.admitSource` |
| Encounter.admission.destination | Encounter.hospitalization.destination | Equivalent | R5 `Encounter.admission.destination` maps as Equivalent to R4 `Encounter.hospitalization.destination` |
| Encounter.admission.dischargeDisposition | Encounter.hospitalization.dischargeDisposition | Equivalent | R5 `Encounter.admission.dischargeDisposition` maps as Equivalent to R4 `Encounter.hospitalization.dischargeDisposition` |
| Encounter.admission.extension | - | DoesNotExistInTarget | R5 `Encounter.admission.extension` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.admission.id | - | DoesNotExistInTarget | R5 `Encounter.admission.id` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.admission.modifierExtension | - | DoesNotExistInTarget | R5 `Encounter.admission.modifierExtension` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.admission.origin | Encounter.hospitalization.origin | Equivalent | R5 `Encounter.admission.origin` maps as Equivalent to R4 `Encounter.hospitalization.origin` |
| Encounter.admission.preAdmissionIdentifier | Encounter.hospitalization.preAdmissionIdentifier | Equivalent | R5 `Encounter.admission.preAdmissionIdentifier` maps as Equivalent to R4 `Encounter.hospitalization.preAdmissionIdentifier` |
| Encounter.admission.reAdmission | Encounter.hospitalization.reAdmission | Equivalent | R5 `Encounter.admission.reAdmission` maps as Equivalent to R4 `Encounter.hospitalization.reAdmission` |
| Encounter.appointment | Encounter.appointment | Equivalent | R5 `Encounter.appointment` maps as Equivalent to R4 `Encounter.appointment` |
| Encounter.basedOn | Encounter.basedOn | SourceIsBroaderThanTarget | R5 `Encounter.basedOn` maps as SourceIsBroaderThanTarget to R4 `Encounter.basedOn` - basedOn has change due to type change: R5 `basedOn` `Reference` maps as SourceIsBroaderThanTarget for R4 `basedOn` |
| Encounter.careTeam | - | DoesNotExistInTarget | R5 `Encounter.careTeam` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.class | Encounter | RelatedTo | R5 `Encounter.class` maps as RelatedTo to R4 `Encounter` - Encounter removed a binding requirement - Preferred http://terminology.hl7.org/ValueSet/encounter-class; Encounter has change due to type change: R5 class CodeableConcept has no equivalent or mapped type in R4 Encounter |
| Encounter.contained | Encounter.contained | Equivalent | R5 `Encounter.contained` maps as Equivalent to R4 `Encounter.contained` |
| Encounter.diagnosis | Encounter.diagnosis | Equivalent | R5 `Encounter.diagnosis` maps as Equivalent to R4 `Encounter.diagnosis` |
| Encounter.diagnosis.condition | Encounter.diagnosis.condition | RelatedTo | R5 `Encounter.diagnosis.condition` maps as RelatedTo to R4 `Encounter.diagnosis.condition` - condition made the element mandatory; condition increased the minimum cardinality from 0 to 1; condition changed from array to scalar (max cardinality from * to 1); condition removed a binding requirement - Example http://hl7.org/fhir/ValueSet/condition-code; condition has change due to type change: R5 condition CodeableReference has no equivalent or mapped type in R4 condition |
| Encounter.diagnosis.extension | Encounter.diagnosis.extension | SourceIsBroaderThanTarget | R5 `Encounter.diagnosis.extension` maps as SourceIsBroaderThanTarget to R4 `Encounter.diagnosis.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Encounter.diagnosis.id | Encounter.diagnosis.id | Equivalent | R5 `Encounter.diagnosis.id` maps as Equivalent to R4 `Encounter.diagnosis.id` |
| Encounter.diagnosis.modifierExtension | Encounter.diagnosis.modifierExtension | SourceIsBroaderThanTarget | R5 `Encounter.diagnosis.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Encounter.diagnosis.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Encounter.diagnosis.use | Encounter.diagnosis.use | SourceIsBroaderThanTarget | R5 `Encounter.diagnosis.use` maps as SourceIsBroaderThanTarget to R4 `Encounter.diagnosis.use` - use changed from array to scalar (max cardinality from * to 1) |
| Encounter.dietPreference | Encounter.hospitalization.dietPreference | Equivalent | R5 `Encounter.dietPreference` maps as Equivalent to R4 `Encounter.hospitalization.dietPreference` |
| Encounter.episodeOfCare | Encounter.episodeOfCare | Equivalent | R5 `Encounter.episodeOfCare` maps as Equivalent to R4 `Encounter.episodeOfCare` |
| Encounter.extension | Encounter.extension | SourceIsBroaderThanTarget | R5 `Encounter.extension` maps as SourceIsBroaderThanTarget to R4 `Encounter.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Encounter.id | Encounter.id | Equivalent | R5 `Encounter.id` maps as Equivalent to R4 `Encounter.id` |
| Encounter.identifier | Encounter.identifier | Equivalent | R5 `Encounter.identifier` maps as Equivalent to R4 `Encounter.identifier` |
| Encounter.implicitRules | Encounter.implicitRules | Equivalent | R5 `Encounter.implicitRules` maps as Equivalent to R4 `Encounter.implicitRules` |
| Encounter.language | Encounter.language | SourceIsNarrowerThanTarget | R5 `Encounter.language` maps as SourceIsNarrowerThanTarget to R4 `Encounter.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| Encounter.length | Encounter.length | Equivalent | R5 `Encounter.length` maps as Equivalent to R4 `Encounter.length` |
| Encounter.location | Encounter.location | Equivalent | R5 `Encounter.location` maps as Equivalent to R4 `Encounter.location` |
| Encounter.location.extension | Encounter.location.extension | SourceIsBroaderThanTarget | R5 `Encounter.location.extension` maps as SourceIsBroaderThanTarget to R4 `Encounter.location.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Encounter.location.form | Encounter.location.physicalType | Equivalent | R5 `Encounter.location.form` maps as Equivalent to R4 `Encounter.location.physicalType` |
| Encounter.location.id | Encounter.location.id | Equivalent | R5 `Encounter.location.id` maps as Equivalent to R4 `Encounter.location.id` |
| Encounter.location.location | Encounter.location.location | Equivalent | R5 `Encounter.location.location` maps as Equivalent to R4 `Encounter.location.location` |
| Encounter.location.modifierExtension | Encounter.location.modifierExtension | SourceIsBroaderThanTarget | R5 `Encounter.location.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Encounter.location.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Encounter.location.period | Encounter.location.period | Equivalent | R5 `Encounter.location.period` maps as Equivalent to R4 `Encounter.location.period` |
| Encounter.location.status | Encounter.location.status | Equivalent | R5 `Encounter.location.status` maps as Equivalent to R4 `Encounter.location.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/encounter-location-status|5.0.0 and http://hl7.org/fhir/ValueSet/encounter-location-status|4.0.1 (Equivalent) |
| Encounter.meta | Encounter.meta | Equivalent | R5 `Encounter.meta` maps as Equivalent to R4 `Encounter.meta` |
| Encounter.modifierExtension | Encounter.modifierExtension | SourceIsBroaderThanTarget | R5 `Encounter.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Encounter.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Encounter.participant | Encounter.participant | Equivalent | R5 `Encounter.participant` maps as Equivalent to R4 `Encounter.participant` |
| Encounter.participant.actor | Encounter.participant.individual | SourceIsBroaderThanTarget | R5 `Encounter.participant.actor` maps as SourceIsBroaderThanTarget to R4 `Encounter.participant.individual` - individual has change due to type change: R5 `actor` `Reference` maps as SourceIsBroaderThanTarget for R4 `individual` |
| Encounter.participant.extension | Encounter.participant.extension | SourceIsBroaderThanTarget | R5 `Encounter.participant.extension` maps as SourceIsBroaderThanTarget to R4 `Encounter.participant.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Encounter.participant.id | Encounter.participant.id | Equivalent | R5 `Encounter.participant.id` maps as Equivalent to R4 `Encounter.participant.id` |
| Encounter.participant.modifierExtension | Encounter.participant.modifierExtension | SourceIsBroaderThanTarget | R5 `Encounter.participant.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Encounter.participant.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Encounter.participant.period | Encounter.participant.period | Equivalent | R5 `Encounter.participant.period` maps as Equivalent to R4 `Encounter.participant.period` |
| Encounter.participant.type | Encounter.participant.type | Equivalent | R5 `Encounter.participant.type` maps as Equivalent to R4 `Encounter.participant.type` |
| Encounter.partOf | Encounter.partOf | Equivalent | R5 `Encounter.partOf` maps as Equivalent to R4 `Encounter.partOf` |
| Encounter.plannedEndDate | - | DoesNotExistInTarget | R5 `Encounter.plannedEndDate` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.plannedStartDate | - | DoesNotExistInTarget | R5 `Encounter.plannedStartDate` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.priority | Encounter.priority | Equivalent | R5 `Encounter.priority` maps as Equivalent to R4 `Encounter.priority` |
| Encounter.reason | Encounter.reasonCode | SourceIsBroaderThanTarget | R5 `Encounter.reason` maps as SourceIsBroaderThanTarget to R4 `Encounter.reasonCode` - reasonCode added a binding requirement - Preferred http://hl7.org/fhir/ValueSet/encounter-reason; reasonCode has change due to type change: R5 reason BackboneElement has no equivalent or mapped type in R4 reasonCode |
| Encounter.reason.extension | - | DoesNotExistInTarget | R5 `Encounter.reason.extension` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.reason.id | - | DoesNotExistInTarget | R5 `Encounter.reason.id` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.reason.modifierExtension | - | DoesNotExistInTarget | R5 `Encounter.reason.modifierExtension` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.reason.use | - | DoesNotExistInTarget | R5 `Encounter.reason.use` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.reason.value | - | DoesNotExistInTarget | R5 `Encounter.reason.value` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.serviceProvider | Encounter.serviceProvider | Equivalent | R5 `Encounter.serviceProvider` maps as Equivalent to R4 `Encounter.serviceProvider` |
| Encounter.serviceType | Encounter.serviceType | SourceIsBroaderThanTarget | R5 `Encounter.serviceType` maps as SourceIsBroaderThanTarget to R4 `Encounter.serviceType` - serviceType changed from array to scalar (max cardinality from * to 1); serviceType has change due to type change: R5 serviceType CodeableReference has no equivalent or mapped type in R4 serviceType |
| Encounter.specialArrangement | Encounter.hospitalization.specialArrangement | Equivalent | R5 `Encounter.specialArrangement` maps as Equivalent to R4 `Encounter.hospitalization.specialArrangement` |
| Encounter.specialCourtesy | Encounter.hospitalization.specialCourtesy | Equivalent | R5 `Encounter.specialCourtesy` maps as Equivalent to R4 `Encounter.hospitalization.specialCourtesy` |
| Encounter.status | Encounter.status | RelatedTo | R5 `Encounter.status` maps as RelatedTo to R4 `Encounter.status` - status has INCOMPATIBLE required binding for code type: http://hl7.org/fhir/ValueSet/encounter-status|5.0.0 and http://hl7.org/fhir/ValueSet/encounter-status|4.0.1; status has change due to type change: R5 `status` `code` maps as RelatedTo for R4 `status` |
| Encounter.subject | Encounter.subject | Equivalent | R5 `Encounter.subject` maps as Equivalent to R4 `Encounter.subject` |
| Encounter.subjectStatus | - | DoesNotExistInTarget | R5 `Encounter.subjectStatus` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.text | Encounter.text | Equivalent | R5 `Encounter.text` maps as Equivalent to R4 `Encounter.text` |
| Encounter.type | Encounter.type | Equivalent | R5 `Encounter.type` maps as Equivalent to R4 `Encounter.type` |
| Encounter.virtualService | - | DoesNotExistInTarget | R5 `Encounter.virtualService` does not appear in the target and has no mapping for `Encounter`. |

