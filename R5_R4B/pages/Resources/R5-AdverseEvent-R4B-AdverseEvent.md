Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | AdverseEvent |  | An event (i.e. any change to current patient status) that may be related to unintended effects on a patient or research participant. The unintended effects may require additional monitoring, treatment, hospitalization, or may result in death. The AdverseEvent resource also extends to potential or avoided events that could have had such effects. There are two major domains where the AdverseEvent resource is expected to be used. One is in clinical care reported adverse events and the other is in reporting adverse events in clinical  research trial management.  Adverse events can be reported by healthcare providers, patients, caregivers or by medical products manufacturers.  Given the differences between these two concepts, we recommend consulting the domain specific implementation guides when implementing the AdverseEvent Resource. The implementation guides include specific extensions, value sets and constraints. | 65 | 36 |
| Target | AdverseEvent |  | Actual or  potential/avoided event causing unintended physical injury resulting from or contributed to by medical care, a research study or other healthcare setting factors that requires additional monitoring, treatment, or hospitalization, or that results in death. | 41 | 27 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 35 |
Equivalent | 4 |
RelatedTo | 26 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| AdverseEvent | AdverseEvent | Equivalent | R5 `AdverseEvent` maps as Equivalent to R4B `AdverseEvent` |
| AdverseEvent.actuality | AdverseEvent.actuality | Equivalent | R5 `AdverseEvent.actuality` maps as Equivalent to R4B `AdverseEvent.actuality` - actuality has compatible required binding for code type: http://hl7.org/fhir/ValueSet/adverse-event-actuality|5.0.0 and http://hl7.org/fhir/ValueSet/adverse-event-actuality|4.3.0 (Equivalent) |
| AdverseEvent.category | AdverseEvent.category | RelatedTo | R5 `AdverseEvent.category` maps as RelatedTo to R4B `AdverseEvent.category` - category changed the binding strength from Example to Extensible |
| AdverseEvent.code | - | DoesNotExistInTarget | R5 `AdverseEvent.code` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.contained | AdverseEvent.contained | Equivalent | R5 `AdverseEvent.contained` maps as Equivalent to R4B `AdverseEvent.contained` |
| AdverseEvent.contributingFactor | - | DoesNotExistInTarget | R5 `AdverseEvent.contributingFactor` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.contributingFactor.extension | - | DoesNotExistInTarget | R5 `AdverseEvent.contributingFactor.extension` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.contributingFactor.id | - | DoesNotExistInTarget | R5 `AdverseEvent.contributingFactor.id` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.contributingFactor.item[x] | - | DoesNotExistInTarget | R5 `AdverseEvent.contributingFactor.item[x]` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.contributingFactor.modifierExtension | - | DoesNotExistInTarget | R5 `AdverseEvent.contributingFactor.modifierExtension` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.detected | AdverseEvent.detected | Equivalent | R5 `AdverseEvent.detected` maps as Equivalent to R4B `AdverseEvent.detected` |
| AdverseEvent.encounter | AdverseEvent.encounter | Equivalent | R5 `AdverseEvent.encounter` maps as Equivalent to R4B `AdverseEvent.encounter` |
| AdverseEvent.expectedInResearchStudy | - | DoesNotExistInTarget | R5 `AdverseEvent.expectedInResearchStudy` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.extension | AdverseEvent.extension | SourceIsBroaderThanTarget | R5 `AdverseEvent.extension` maps as SourceIsBroaderThanTarget to R4B `AdverseEvent.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| AdverseEvent.id | AdverseEvent.id | Equivalent | R5 `AdverseEvent.id` maps as Equivalent to R4B `AdverseEvent.id` |
| AdverseEvent.identifier | AdverseEvent.identifier | RelatedTo | R5 `AdverseEvent.identifier` maps as RelatedTo to R4B `AdverseEvent.identifier` - identifier changed from array to scalar (max cardinality from * to 1) |
| AdverseEvent.implicitRules | AdverseEvent.implicitRules | Equivalent | R5 `AdverseEvent.implicitRules` maps as Equivalent to R4B `AdverseEvent.implicitRules` |
| AdverseEvent.language | AdverseEvent.language | RelatedTo | R5 `AdverseEvent.language` maps as RelatedTo to R4B `AdverseEvent.language` - language changed the binding strength from Required to Preferred |
| AdverseEvent.location | AdverseEvent.location | Equivalent | R5 `AdverseEvent.location` maps as Equivalent to R4B `AdverseEvent.location` |
| AdverseEvent.meta | AdverseEvent.meta | Equivalent | R5 `AdverseEvent.meta` maps as Equivalent to R4B `AdverseEvent.meta` |
| AdverseEvent.mitigatingAction | - | DoesNotExistInTarget | R5 `AdverseEvent.mitigatingAction` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.mitigatingAction.extension | - | DoesNotExistInTarget | R5 `AdverseEvent.mitigatingAction.extension` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.mitigatingAction.id | - | DoesNotExistInTarget | R5 `AdverseEvent.mitigatingAction.id` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.mitigatingAction.item[x] | - | DoesNotExistInTarget | R5 `AdverseEvent.mitigatingAction.item[x]` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.mitigatingAction.modifierExtension | - | DoesNotExistInTarget | R5 `AdverseEvent.mitigatingAction.modifierExtension` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.modifierExtension | AdverseEvent.modifierExtension | SourceIsBroaderThanTarget | R5 `AdverseEvent.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `AdverseEvent.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| AdverseEvent.note | - | DoesNotExistInTarget | R5 `AdverseEvent.note` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.occurrence[x] | - | DoesNotExistInTarget | R5 `AdverseEvent.occurrence[x]` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.outcome | AdverseEvent.outcome | RelatedTo | R5 `AdverseEvent.outcome` maps as RelatedTo to R4B `AdverseEvent.outcome` - outcome changed from array to scalar (max cardinality from * to 1); outcome made the binding required (from Example) for http://hl7.org/fhir/ValueSet/adverse-event-outcome|4.3.0 |
| AdverseEvent.participant | - | DoesNotExistInTarget | R5 `AdverseEvent.participant` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.participant.actor | - | DoesNotExistInTarget | R5 `AdverseEvent.participant.actor` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.participant.extension | - | DoesNotExistInTarget | R5 `AdverseEvent.participant.extension` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.participant.function | - | DoesNotExistInTarget | R5 `AdverseEvent.participant.function` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.participant.id | - | DoesNotExistInTarget | R5 `AdverseEvent.participant.id` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.participant.modifierExtension | - | DoesNotExistInTarget | R5 `AdverseEvent.participant.modifierExtension` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.preventiveAction | - | DoesNotExistInTarget | R5 `AdverseEvent.preventiveAction` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.preventiveAction.extension | - | DoesNotExistInTarget | R5 `AdverseEvent.preventiveAction.extension` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.preventiveAction.id | - | DoesNotExistInTarget | R5 `AdverseEvent.preventiveAction.id` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.preventiveAction.item[x] | - | DoesNotExistInTarget | R5 `AdverseEvent.preventiveAction.item[x]` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.preventiveAction.modifierExtension | - | DoesNotExistInTarget | R5 `AdverseEvent.preventiveAction.modifierExtension` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.recordedDate | AdverseEvent.recordedDate | Equivalent | R5 `AdverseEvent.recordedDate` maps as Equivalent to R4B `AdverseEvent.recordedDate` |
| AdverseEvent.recorder | AdverseEvent.recorder | SourceIsBroaderThanTarget | R5 `AdverseEvent.recorder` maps as SourceIsBroaderThanTarget to R4B `AdverseEvent.recorder` - recorder has change due to type change: R5 `recorder` `Reference` maps as SourceIsBroaderThanTarget for R4B `recorder` |
| AdverseEvent.resultingEffect | - | DoesNotExistInTarget | R5 `AdverseEvent.resultingEffect` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.seriousness | AdverseEvent.seriousness | Equivalent | R5 `AdverseEvent.seriousness` maps as Equivalent to R4B `AdverseEvent.seriousness` |
| AdverseEvent.status | - | DoesNotExistInTarget | R5 `AdverseEvent.status` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.study | AdverseEvent.study | Equivalent | R5 `AdverseEvent.study` maps as Equivalent to R4B `AdverseEvent.study` |
| AdverseEvent.subject | AdverseEvent.subject | SourceIsBroaderThanTarget | R5 `AdverseEvent.subject` maps as SourceIsBroaderThanTarget to R4B `AdverseEvent.subject` - subject has change due to type change: R5 `subject` `Reference` maps as SourceIsBroaderThanTarget for R4B `subject` |
| AdverseEvent.supportingInfo | - | DoesNotExistInTarget | R5 `AdverseEvent.supportingInfo` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.supportingInfo.extension | - | DoesNotExistInTarget | R5 `AdverseEvent.supportingInfo.extension` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.supportingInfo.id | - | DoesNotExistInTarget | R5 `AdverseEvent.supportingInfo.id` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.supportingInfo.item[x] | - | DoesNotExistInTarget | R5 `AdverseEvent.supportingInfo.item[x]` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.supportingInfo.modifierExtension | - | DoesNotExistInTarget | R5 `AdverseEvent.supportingInfo.modifierExtension` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.suspectEntity | AdverseEvent.suspectEntity | Equivalent | R5 `AdverseEvent.suspectEntity` maps as Equivalent to R4B `AdverseEvent.suspectEntity` |
| AdverseEvent.suspectEntity.causality | AdverseEvent.suspectEntity.causality | RelatedTo | R5 `AdverseEvent.suspectEntity.causality` maps as RelatedTo to R4B `AdverseEvent.suspectEntity.causality` - causality changed from scalar to array (max cardinality from 1 to *) |
| AdverseEvent.suspectEntity.causality.assessmentMethod | - | DoesNotExistInTarget | R5 `AdverseEvent.suspectEntity.causality.assessmentMethod` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.suspectEntity.causality.author | AdverseEvent.suspectEntity.causality.author | SourceIsBroaderThanTarget | R5 `AdverseEvent.suspectEntity.causality.author` maps as SourceIsBroaderThanTarget to R4B `AdverseEvent.suspectEntity.causality.author` - author has change due to type change: R5 `author` `Reference` maps as SourceIsBroaderThanTarget for R4B `author` |
| AdverseEvent.suspectEntity.causality.entityRelatedness | - | DoesNotExistInTarget | R5 `AdverseEvent.suspectEntity.causality.entityRelatedness` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.suspectEntity.causality.extension | AdverseEvent.suspectEntity.causality.extension | SourceIsBroaderThanTarget | R5 `AdverseEvent.suspectEntity.causality.extension` maps as SourceIsBroaderThanTarget to R4B `AdverseEvent.suspectEntity.causality.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| AdverseEvent.suspectEntity.causality.id | AdverseEvent.suspectEntity.causality.id | Equivalent | R5 `AdverseEvent.suspectEntity.causality.id` maps as Equivalent to R4B `AdverseEvent.suspectEntity.causality.id` |
| AdverseEvent.suspectEntity.causality.modifierExtension | AdverseEvent.suspectEntity.causality.modifierExtension | SourceIsBroaderThanTarget | R5 `AdverseEvent.suspectEntity.causality.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `AdverseEvent.suspectEntity.causality.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| AdverseEvent.suspectEntity.extension | AdverseEvent.suspectEntity.extension | SourceIsBroaderThanTarget | R5 `AdverseEvent.suspectEntity.extension` maps as SourceIsBroaderThanTarget to R4B `AdverseEvent.suspectEntity.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| AdverseEvent.suspectEntity.id | AdverseEvent.suspectEntity.id | Equivalent | R5 `AdverseEvent.suspectEntity.id` maps as Equivalent to R4B `AdverseEvent.suspectEntity.id` |
| AdverseEvent.suspectEntity.instance[x] | - | DoesNotExistInTarget | R5 `AdverseEvent.suspectEntity.instance[x]` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.suspectEntity.modifierExtension | AdverseEvent.suspectEntity.modifierExtension | SourceIsBroaderThanTarget | R5 `AdverseEvent.suspectEntity.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `AdverseEvent.suspectEntity.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| AdverseEvent.text | AdverseEvent.text | Equivalent | R5 `AdverseEvent.text` maps as Equivalent to R4B `AdverseEvent.text` |

