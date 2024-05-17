Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Encounter |  | An interaction between a patient and healthcare provider(s) for the purpose of providing healthcare service(s) or assessing the health status of a patient. | 73 | 47 |
| Target | Encounter |  | An interaction between healthcare provider(s), and/or patient(s) for the purpose of providing healthcare service(s) or assessing the health status of patient(s). | 69 | 46 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 31 |
Equivalent | 4 |
RelatedTo | 38 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Encounter | Encounter | Equivalent | R4B `Encounter` maps as Equivalent to R5 `Encounter` |
| Encounter.account | Encounter.account | Equivalent | R4B `Encounter.account` maps as Equivalent to R5 `Encounter.account` |
| Encounter.appointment | Encounter.appointment | Equivalent | R4B `Encounter.appointment` maps as Equivalent to R5 `Encounter.appointment` |
| Encounter.basedOn | Encounter.basedOn | SourceIsNarrowerThanTarget | R4B `Encounter.basedOn` maps as SourceIsNarrowerThanTarget to R5 `Encounter.basedOn` - basedOn has change due to type change: R4B `basedOn` `Reference` maps as SourceIsNarrowerThanTarget for R5 `basedOn` |
| Encounter.class | Encounter.class | RelatedTo | R4B `Encounter.class` maps as RelatedTo to R5 `Encounter.class` - class changed from scalar to array (max cardinality from 1 to *); class changed the binding strength from Extensible to Preferred; class has change due to type change: R4B class Coding has no equivalent or mapped type in R5 class |
| Encounter.classHistory | - | DoesNotExistInTarget | R4B `Encounter.classHistory` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.classHistory.class | - | DoesNotExistInTarget | R4B `Encounter.classHistory.class` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.classHistory.extension | - | DoesNotExistInTarget | R4B `Encounter.classHistory.extension` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.classHistory.id | - | DoesNotExistInTarget | R4B `Encounter.classHistory.id` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.classHistory.modifierExtension | - | DoesNotExistInTarget | R4B `Encounter.classHistory.modifierExtension` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.classHistory.period | - | DoesNotExistInTarget | R4B `Encounter.classHistory.period` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.contained | Encounter.contained | Equivalent | R4B `Encounter.contained` maps as Equivalent to R5 `Encounter.contained` |
| Encounter.diagnosis | Encounter.diagnosis | Equivalent | R4B `Encounter.diagnosis` maps as Equivalent to R5 `Encounter.diagnosis` |
| Encounter.diagnosis.condition | Encounter.diagnosis.condition | RelatedTo | R4B `Encounter.diagnosis.condition` maps as RelatedTo to R5 `Encounter.diagnosis.condition` - condition changed from scalar to array (max cardinality from 1 to *); condition added a binding requirement - Example http://hl7.org/fhir/ValueSet/condition-code; condition has change due to type change: R4B condition Reference has no equivalent or mapped type in R5 condition |
| Encounter.diagnosis.extension | Encounter.diagnosis.extension | RelatedTo | R4B `Encounter.diagnosis.extension` maps as RelatedTo to R5 `Encounter.diagnosis.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Encounter.diagnosis.id | Encounter.diagnosis.id | Equivalent | R4B `Encounter.diagnosis.id` maps as Equivalent to R5 `Encounter.diagnosis.id` |
| Encounter.diagnosis.modifierExtension | Encounter.diagnosis.modifierExtension | RelatedTo | R4B `Encounter.diagnosis.modifierExtension` maps as RelatedTo to R5 `Encounter.diagnosis.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Encounter.diagnosis.rank | - | DoesNotExistInTarget | R4B `Encounter.diagnosis.rank` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.diagnosis.use | Encounter.diagnosis.use | RelatedTo | R4B `Encounter.diagnosis.use` maps as RelatedTo to R5 `Encounter.diagnosis.use` - use changed from scalar to array (max cardinality from 1 to *) |
| Encounter.episodeOfCare | Encounter.episodeOfCare | Equivalent | R4B `Encounter.episodeOfCare` maps as Equivalent to R5 `Encounter.episodeOfCare` |
| Encounter.extension | Encounter.extension | RelatedTo | R4B `Encounter.extension` maps as RelatedTo to R5 `Encounter.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Encounter.hospitalization | - | DoesNotExistInTarget | R4B `Encounter.hospitalization` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.hospitalization.admitSource | - | DoesNotExistInTarget | R4B `Encounter.hospitalization.admitSource` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.hospitalization.destination | - | DoesNotExistInTarget | R4B `Encounter.hospitalization.destination` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.hospitalization.dietPreference | - | DoesNotExistInTarget | R4B `Encounter.hospitalization.dietPreference` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.hospitalization.dischargeDisposition | - | DoesNotExistInTarget | R4B `Encounter.hospitalization.dischargeDisposition` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.hospitalization.extension | - | DoesNotExistInTarget | R4B `Encounter.hospitalization.extension` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.hospitalization.id | - | DoesNotExistInTarget | R4B `Encounter.hospitalization.id` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.hospitalization.modifierExtension | - | DoesNotExistInTarget | R4B `Encounter.hospitalization.modifierExtension` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.hospitalization.origin | - | DoesNotExistInTarget | R4B `Encounter.hospitalization.origin` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.hospitalization.preAdmissionIdentifier | - | DoesNotExistInTarget | R4B `Encounter.hospitalization.preAdmissionIdentifier` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.hospitalization.reAdmission | - | DoesNotExistInTarget | R4B `Encounter.hospitalization.reAdmission` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.hospitalization.specialArrangement | - | DoesNotExistInTarget | R4B `Encounter.hospitalization.specialArrangement` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.hospitalization.specialCourtesy | - | DoesNotExistInTarget | R4B `Encounter.hospitalization.specialCourtesy` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.id | Encounter.id | Equivalent | R4B `Encounter.id` maps as Equivalent to R5 `Encounter.id` |
| Encounter.identifier | Encounter.identifier | Equivalent | R4B `Encounter.identifier` maps as Equivalent to R5 `Encounter.identifier` |
| Encounter.implicitRules | Encounter.implicitRules | Equivalent | R4B `Encounter.implicitRules` maps as Equivalent to R5 `Encounter.implicitRules` |
| Encounter.language | Encounter.language | RelatedTo | R4B `Encounter.language` maps as RelatedTo to R5 `Encounter.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Encounter.length | Encounter.length | Equivalent | R4B `Encounter.length` maps as Equivalent to R5 `Encounter.length` |
| Encounter.location | Encounter.location | Equivalent | R4B `Encounter.location` maps as Equivalent to R5 `Encounter.location` |
| Encounter.location.extension | Encounter.location.extension | RelatedTo | R4B `Encounter.location.extension` maps as RelatedTo to R5 `Encounter.location.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Encounter.location.id | Encounter.location.id | Equivalent | R4B `Encounter.location.id` maps as Equivalent to R5 `Encounter.location.id` |
| Encounter.location.location | Encounter.location.location | Equivalent | R4B `Encounter.location.location` maps as Equivalent to R5 `Encounter.location.location` |
| Encounter.location.modifierExtension | Encounter.location.modifierExtension | RelatedTo | R4B `Encounter.location.modifierExtension` maps as RelatedTo to R5 `Encounter.location.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Encounter.location.period | Encounter.location.period | Equivalent | R4B `Encounter.location.period` maps as Equivalent to R5 `Encounter.location.period` |
| Encounter.location.physicalType | - | DoesNotExistInTarget | R4B `Encounter.location.physicalType` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.location.status | Encounter.location.status | Equivalent | R4B `Encounter.location.status` maps as Equivalent to R5 `Encounter.location.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/encounter-location-status|4.3.0 and http://hl7.org/fhir/ValueSet/encounter-location-status|5.0.0 (Equivalent) |
| Encounter.meta | Encounter.meta | Equivalent | R4B `Encounter.meta` maps as Equivalent to R5 `Encounter.meta` |
| Encounter.modifierExtension | Encounter.modifierExtension | RelatedTo | R4B `Encounter.modifierExtension` maps as RelatedTo to R5 `Encounter.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Encounter.participant | Encounter.participant | Equivalent | R4B `Encounter.participant` maps as Equivalent to R5 `Encounter.participant` |
| Encounter.participant.extension | Encounter.participant.extension | RelatedTo | R4B `Encounter.participant.extension` maps as RelatedTo to R5 `Encounter.participant.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Encounter.participant.id | Encounter.participant.id | Equivalent | R4B `Encounter.participant.id` maps as Equivalent to R5 `Encounter.participant.id` |
| Encounter.participant.individual | - | DoesNotExistInTarget | R4B `Encounter.participant.individual` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.participant.modifierExtension | Encounter.participant.modifierExtension | RelatedTo | R4B `Encounter.participant.modifierExtension` maps as RelatedTo to R5 `Encounter.participant.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Encounter.participant.period | Encounter.participant.period | Equivalent | R4B `Encounter.participant.period` maps as Equivalent to R5 `Encounter.participant.period` |
| Encounter.participant.type | Encounter.participant.type | Equivalent | R4B `Encounter.participant.type` maps as Equivalent to R5 `Encounter.participant.type` |
| Encounter.partOf | Encounter.partOf | Equivalent | R4B `Encounter.partOf` maps as Equivalent to R5 `Encounter.partOf` |
| Encounter.period | - | DoesNotExistInTarget | R4B `Encounter.period` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.priority | Encounter.priority | Equivalent | R4B `Encounter.priority` maps as Equivalent to R5 `Encounter.priority` |
| Encounter.reasonCode | - | DoesNotExistInTarget | R4B `Encounter.reasonCode` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.reasonReference | - | DoesNotExistInTarget | R4B `Encounter.reasonReference` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.serviceProvider | Encounter.serviceProvider | Equivalent | R4B `Encounter.serviceProvider` maps as Equivalent to R5 `Encounter.serviceProvider` |
| Encounter.serviceType | Encounter.serviceType | RelatedTo | R4B `Encounter.serviceType` maps as RelatedTo to R5 `Encounter.serviceType` - serviceType changed from scalar to array (max cardinality from 1 to *); serviceType has change due to type change: R4B serviceType CodeableConcept has no equivalent or mapped type in R5 serviceType |
| Encounter.status | Encounter.status | RelatedTo | R4B `Encounter.status` maps as RelatedTo to R5 `Encounter.status` - status has INCOMPATIBLE required binding for code type: http://hl7.org/fhir/ValueSet/encounter-status|4.3.0 and http://hl7.org/fhir/ValueSet/encounter-status|5.0.0 |
| Encounter.statusHistory | - | DoesNotExistInTarget | R4B `Encounter.statusHistory` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.statusHistory.extension | - | DoesNotExistInTarget | R4B `Encounter.statusHistory.extension` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.statusHistory.id | - | DoesNotExistInTarget | R4B `Encounter.statusHistory.id` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.statusHistory.modifierExtension | - | DoesNotExistInTarget | R4B `Encounter.statusHistory.modifierExtension` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.statusHistory.period | - | DoesNotExistInTarget | R4B `Encounter.statusHistory.period` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.statusHistory.status | - | DoesNotExistInTarget | R4B `Encounter.statusHistory.status` does not appear in the target and has no mapping for `Encounter`. |
| Encounter.subject | Encounter.subject | Equivalent | R4B `Encounter.subject` maps as Equivalent to R5 `Encounter.subject` |
| Encounter.text | Encounter.text | Equivalent | R4B `Encounter.text` maps as Equivalent to R5 `Encounter.text` |
| Encounter.type | Encounter.type | Equivalent | R4B `Encounter.type` maps as Equivalent to R5 `Encounter.type` |

