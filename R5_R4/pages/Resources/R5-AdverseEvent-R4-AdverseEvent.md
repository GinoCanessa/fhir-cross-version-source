Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | AdverseEvent |  | An event (i.e. any change to current patient status) that may be related to unintended effects on a patient or research participant. The unintended effects may require additional monitoring, treatment, hospitalization, or may result in death. The AdverseEvent resource also extends to potential or avoided events that could have had such effects. There are two major domains where the AdverseEvent resource is expected to be used. One is in clinical care reported adverse events and the other is in reporting adverse events in clinical  research trial management.  Adverse events can be reported by healthcare providers, patients, caregivers or by medical products manufacturers.  Given the differences between these two concepts, we recommend consulting the domain specific implementation guides when implementing the AdverseEvent Resource. The implementation guides include specific extensions, value sets and constraints. | 65 | 36 |
| Target | AdverseEvent |  | Actual or  potential/avoided event causing unintended physical injury resulting from or contributed to by medical care, a research study or other healthcare setting factors that requires additional monitoring, treatment, or hospitalization, or that results in death. | 41 | 27 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 25 |
Equivalent | 17 |
RelatedTo | 6 |
SourceIsBroaderThanTarget | 14 |
SourceIsNarrowerThanTarget | 3 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| AdverseEvent | AdverseEvent | SourceIsNarrowerThanTarget | R5 `AdverseEvent` is narrower than R4 `AdverseEvent` and is compatible. `AdverseEvent` is mapped from `AdverseEvent` and `AdverseEvent.supportingInfo`. |
| AdverseEvent.actuality | AdverseEvent.actuality | Equivalent | R5 `AdverseEvent.actuality` maps as Equivalent to R4 `AdverseEvent.actuality` - actuality has compatible required binding for code type: http://hl7.org/fhir/ValueSet/adverse-event-actuality|5.0.0 and http://hl7.org/fhir/ValueSet/adverse-event-actuality|4.0.1 (Equivalent) |
| AdverseEvent.category | AdverseEvent.category | SourceIsBroaderThanTarget | R5 `AdverseEvent.category` maps as SourceIsBroaderThanTarget to R4 `AdverseEvent.category` - category changed the binding strength from Example to Extensible; category has change due to type change: R5 `category` `CodeableConcept` maps as SourceIsBroaderThanTarget for R4 `category` |
| AdverseEvent.code | AdverseEvent.event | Equivalent | R5 `AdverseEvent.code` maps as Equivalent to R4 `AdverseEvent.event` |
| AdverseEvent.contained | AdverseEvent.contained | Equivalent | R5 `AdverseEvent.contained` maps as Equivalent to R4 `AdverseEvent.contained` |
| AdverseEvent.contributingFactor | - | DoesNotExistInTarget | R5 `AdverseEvent.contributingFactor` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.contributingFactor.extension | - | DoesNotExistInTarget | R5 `AdverseEvent.contributingFactor.extension` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.contributingFactor.id | - | DoesNotExistInTarget | R5 `AdverseEvent.contributingFactor.id` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.contributingFactor.item[x] | AdverseEvent.subjectMedicalHistory | RelatedTo | R5 `AdverseEvent.contributingFactor.item[x]` maps as RelatedTo to R4 `AdverseEvent.subjectMedicalHistory` - subjectMedicalHistory changed from scalar to array (max cardinality from 1 to *); subjectMedicalHistory removed a binding requirement - Example http://hl7.org/fhir/ValueSet/adverse-event-contributing-factor; subjectMedicalHistory has change due to type change: R5 `item[x]` `Reference` maps as RelatedTo for R4 `subjectMedicalHistory`; subjectMedicalHistory has change due to type change: R5 item[x] CodeableConcept has no equivalent or mapped type in R4 subjectMedicalHistory |
| AdverseEvent.contributingFactor.modifierExtension | - | DoesNotExistInTarget | R5 `AdverseEvent.contributingFactor.modifierExtension` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.detected | AdverseEvent.detected | Equivalent | R5 `AdverseEvent.detected` maps as Equivalent to R4 `AdverseEvent.detected` |
| AdverseEvent.encounter | AdverseEvent.encounter | Equivalent | R5 `AdverseEvent.encounter` maps as Equivalent to R4 `AdverseEvent.encounter` |
| AdverseEvent.expectedInResearchStudy | - | DoesNotExistInTarget | R5 `AdverseEvent.expectedInResearchStudy` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.extension | AdverseEvent.extension | SourceIsBroaderThanTarget | R5 `AdverseEvent.extension` maps as SourceIsBroaderThanTarget to R4 `AdverseEvent.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| AdverseEvent.id | AdverseEvent.id | Equivalent | R5 `AdverseEvent.id` maps as Equivalent to R4 `AdverseEvent.id` |
| AdverseEvent.identifier | AdverseEvent.identifier | SourceIsBroaderThanTarget | R5 `AdverseEvent.identifier` maps as SourceIsBroaderThanTarget to R4 `AdverseEvent.identifier` - identifier changed from array to scalar (max cardinality from * to 1) |
| AdverseEvent.implicitRules | AdverseEvent.implicitRules | Equivalent | R5 `AdverseEvent.implicitRules` maps as Equivalent to R4 `AdverseEvent.implicitRules` |
| AdverseEvent.language | AdverseEvent.language | SourceIsNarrowerThanTarget | R5 `AdverseEvent.language` maps as SourceIsNarrowerThanTarget to R4 `AdverseEvent.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| AdverseEvent.location | AdverseEvent.location | Equivalent | R5 `AdverseEvent.location` maps as Equivalent to R4 `AdverseEvent.location` |
| AdverseEvent.meta | AdverseEvent.meta | Equivalent | R5 `AdverseEvent.meta` maps as Equivalent to R4 `AdverseEvent.meta` |
| AdverseEvent.mitigatingAction | - | DoesNotExistInTarget | R5 `AdverseEvent.mitigatingAction` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.mitigatingAction.extension | - | DoesNotExistInTarget | R5 `AdverseEvent.mitigatingAction.extension` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.mitigatingAction.id | - | DoesNotExistInTarget | R5 `AdverseEvent.mitigatingAction.id` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.mitigatingAction.item[x] | - | DoesNotExistInTarget | R5 `AdverseEvent.mitigatingAction.item[x]` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.mitigatingAction.modifierExtension | - | DoesNotExistInTarget | R5 `AdverseEvent.mitigatingAction.modifierExtension` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.modifierExtension | AdverseEvent.modifierExtension | SourceIsBroaderThanTarget | R5 `AdverseEvent.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `AdverseEvent.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| AdverseEvent.note | - | DoesNotExistInTarget | R5 `AdverseEvent.note` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.occurrence[x] | AdverseEvent.date | SourceIsBroaderThanTarget | R5 `AdverseEvent.occurrence[x]` maps as SourceIsBroaderThanTarget to R4 `AdverseEvent.date` - date has change due to type change: R5 occurrence[x] Period has no equivalent or mapped type in R4 date; date has change due to type change: R5 occurrence[x] Timing has no equivalent or mapped type in R4 date |
| AdverseEvent.outcome | AdverseEvent.outcome | RelatedTo | R5 `AdverseEvent.outcome` maps as RelatedTo to R4 `AdverseEvent.outcome` - outcome changed from array to scalar (max cardinality from * to 1); outcome made the binding required (from Example) for http://hl7.org/fhir/ValueSet/adverse-event-outcome|4.0.1; outcome has change due to type change: R5 `outcome` `CodeableConcept` maps as SourceIsNarrowerThanTarget for R4 `outcome` |
| AdverseEvent.participant | - | DoesNotExistInTarget | R5 `AdverseEvent.participant` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.participant.actor | AdverseEvent.contributor | RelatedTo | R5 `AdverseEvent.participant.actor` maps as RelatedTo to R4 `AdverseEvent.contributor` - contributor changed from scalar to array (max cardinality from 1 to *); contributor has change due to type change: R5 `actor` `Reference` maps as SourceIsBroaderThanTarget for R4 `contributor` |
| AdverseEvent.participant.extension | - | DoesNotExistInTarget | R5 `AdverseEvent.participant.extension` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.participant.function | - | DoesNotExistInTarget | R5 `AdverseEvent.participant.function` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.participant.id | - | DoesNotExistInTarget | R5 `AdverseEvent.participant.id` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.participant.modifierExtension | - | DoesNotExistInTarget | R5 `AdverseEvent.participant.modifierExtension` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.preventiveAction | - | DoesNotExistInTarget | R5 `AdverseEvent.preventiveAction` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.preventiveAction.extension | - | DoesNotExistInTarget | R5 `AdverseEvent.preventiveAction.extension` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.preventiveAction.id | - | DoesNotExistInTarget | R5 `AdverseEvent.preventiveAction.id` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.preventiveAction.item[x] | - | DoesNotExistInTarget | R5 `AdverseEvent.preventiveAction.item[x]` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.preventiveAction.modifierExtension | - | DoesNotExistInTarget | R5 `AdverseEvent.preventiveAction.modifierExtension` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.recordedDate | AdverseEvent.recordedDate | Equivalent | R5 `AdverseEvent.recordedDate` maps as Equivalent to R4 `AdverseEvent.recordedDate` |
| AdverseEvent.recorder | AdverseEvent.recorder | SourceIsBroaderThanTarget | R5 `AdverseEvent.recorder` maps as SourceIsBroaderThanTarget to R4 `AdverseEvent.recorder` - recorder has change due to type change: R5 `recorder` `Reference` maps as SourceIsBroaderThanTarget for R4 `recorder` |
| AdverseEvent.resultingEffect | AdverseEvent.resultingCondition | SourceIsBroaderThanTarget | R5 `AdverseEvent.resultingEffect` maps as SourceIsBroaderThanTarget to R4 `AdverseEvent.resultingCondition` - resultingCondition has change due to type change: R5 `resultingEffect` `Reference` maps as SourceIsBroaderThanTarget for R4 `resultingCondition` |
| AdverseEvent.seriousness | AdverseEvent.seriousness | Equivalent | R5 `AdverseEvent.seriousness` maps as Equivalent to R4 `AdverseEvent.seriousness` |
| AdverseEvent.status | - | DoesNotExistInTarget | R5 `AdverseEvent.status` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.study | AdverseEvent.study | Equivalent | R5 `AdverseEvent.study` maps as Equivalent to R4 `AdverseEvent.study` |
| AdverseEvent.subject | AdverseEvent.subject | SourceIsBroaderThanTarget | R5 `AdverseEvent.subject` maps as SourceIsBroaderThanTarget to R4 `AdverseEvent.subject` - subject has change due to type change: R5 `subject` `Reference` maps as SourceIsBroaderThanTarget for R4 `subject` |
| AdverseEvent.supportingInfo | AdverseEvent | RelatedTo | R5 `AdverseEvent.supportingInfo` maps as RelatedTo to R4 `AdverseEvent` - AdverseEvent has change due to type change: R5 supportingInfo BackboneElement has no equivalent or mapped type in R4 AdverseEvent |
| AdverseEvent.supportingInfo.extension | - | DoesNotExistInTarget | R5 `AdverseEvent.supportingInfo.extension` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.supportingInfo.id | - | DoesNotExistInTarget | R5 `AdverseEvent.supportingInfo.id` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.supportingInfo.item[x] | AdverseEvent.subjectMedicalHistory | RelatedTo | R5 `AdverseEvent.supportingInfo.item[x]` maps as RelatedTo to R4 `AdverseEvent.subjectMedicalHistory` - subjectMedicalHistory changed from scalar to array (max cardinality from 1 to *); subjectMedicalHistory removed a binding requirement - Example http://hl7.org/fhir/ValueSet/adverse-event-supporting-info; subjectMedicalHistory has change due to type change: R5 `item[x]` `Reference` maps as RelatedTo for R4 `subjectMedicalHistory`; subjectMedicalHistory has change due to type change: R5 item[x] CodeableConcept has no equivalent or mapped type in R4 subjectMedicalHistory |
| AdverseEvent.supportingInfo.modifierExtension | - | DoesNotExistInTarget | R5 `AdverseEvent.supportingInfo.modifierExtension` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.suspectEntity | AdverseEvent.suspectEntity | Equivalent | R5 `AdverseEvent.suspectEntity` maps as Equivalent to R4 `AdverseEvent.suspectEntity` |
| AdverseEvent.suspectEntity.causality | AdverseEvent.suspectEntity.causality | SourceIsNarrowerThanTarget | R5 `AdverseEvent.suspectEntity.causality` maps as SourceIsNarrowerThanTarget to R4 `AdverseEvent.suspectEntity.causality` - causality changed from scalar to array (max cardinality from 1 to *) |
| AdverseEvent.suspectEntity.causality.assessmentMethod | AdverseEvent.suspectEntity.causality.assessment | Equivalent | R5 `AdverseEvent.suspectEntity.causality.assessmentMethod` maps as Equivalent to R4 `AdverseEvent.suspectEntity.causality.assessment` |
| AdverseEvent.suspectEntity.causality.author | AdverseEvent.suspectEntity.causality.author | SourceIsBroaderThanTarget | R5 `AdverseEvent.suspectEntity.causality.author` maps as SourceIsBroaderThanTarget to R4 `AdverseEvent.suspectEntity.causality.author` - author has change due to type change: R5 `author` `Reference` maps as SourceIsBroaderThanTarget for R4 `author` |
| AdverseEvent.suspectEntity.causality.entityRelatedness | AdverseEvent.suspectEntity.causality.productRelatedness | RelatedTo | R5 `AdverseEvent.suspectEntity.causality.entityRelatedness` maps as RelatedTo to R4 `AdverseEvent.suspectEntity.causality.productRelatedness` - productRelatedness removed a binding requirement - Example http://hl7.org/fhir/ValueSet/adverse-event-causality-assess; productRelatedness has change due to type change: R5 entityRelatedness CodeableConcept has no equivalent or mapped type in R4 productRelatedness |
| AdverseEvent.suspectEntity.causality.extension | AdverseEvent.suspectEntity.causality.extension | SourceIsBroaderThanTarget | R5 `AdverseEvent.suspectEntity.causality.extension` maps as SourceIsBroaderThanTarget to R4 `AdverseEvent.suspectEntity.causality.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| AdverseEvent.suspectEntity.causality.id | AdverseEvent.suspectEntity.causality.id | Equivalent | R5 `AdverseEvent.suspectEntity.causality.id` maps as Equivalent to R4 `AdverseEvent.suspectEntity.causality.id` |
| AdverseEvent.suspectEntity.causality.modifierExtension | AdverseEvent.suspectEntity.causality.modifierExtension | SourceIsBroaderThanTarget | R5 `AdverseEvent.suspectEntity.causality.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `AdverseEvent.suspectEntity.causality.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| AdverseEvent.suspectEntity.extension | AdverseEvent.suspectEntity.extension | SourceIsBroaderThanTarget | R5 `AdverseEvent.suspectEntity.extension` maps as SourceIsBroaderThanTarget to R4 `AdverseEvent.suspectEntity.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| AdverseEvent.suspectEntity.id | AdverseEvent.suspectEntity.id | Equivalent | R5 `AdverseEvent.suspectEntity.id` maps as Equivalent to R4 `AdverseEvent.suspectEntity.id` |
| AdverseEvent.suspectEntity.instance[x] | AdverseEvent.suspectEntity.instance | SourceIsBroaderThanTarget | R5 `AdverseEvent.suspectEntity.instance[x]` maps as SourceIsBroaderThanTarget to R4 `AdverseEvent.suspectEntity.instance` - instance has change due to type change: R5 instance[x] CodeableConcept has no equivalent or mapped type in R4 instance; instance has change due to type change: R5 `instance[x]` `Reference` maps as SourceIsBroaderThanTarget for R4 `instance` |
| AdverseEvent.suspectEntity.modifierExtension | AdverseEvent.suspectEntity.modifierExtension | SourceIsBroaderThanTarget | R5 `AdverseEvent.suspectEntity.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `AdverseEvent.suspectEntity.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| AdverseEvent.text | AdverseEvent.text | Equivalent | R5 `AdverseEvent.text` maps as Equivalent to R4 `AdverseEvent.text` |

