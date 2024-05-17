Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | AdverseEvent |  | Actual or  potential/avoided event causing unintended physical injury resulting from or contributed to by medical care, a research study or other healthcare setting factors that requires additional monitoring, treatment, or hospitalization, or that results in death. | 41 | 27 |
| Target | AdverseEvent |  | An event (i.e. any change to current patient status) that may be related to unintended effects on a patient or research participant. The unintended effects may require additional monitoring, treatment, hospitalization, or may result in death. The AdverseEvent resource also extends to potential or avoided events that could have had such effects. There are two major domains where the AdverseEvent resource is expected to be used. One is in clinical care reported adverse events and the other is in reporting adverse events in clinical  research trial management.  Adverse events can be reported by healthcare providers, patients, caregivers or by medical products manufacturers.  Given the differences between these two concepts, we recommend consulting the domain specific implementation guides when implementing the AdverseEvent Resource. The implementation guides include specific extensions, value sets and constraints. | 65 | 36 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 11 |
Equivalent | 4 |
RelatedTo | 26 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| AdverseEvent | AdverseEvent | Equivalent | R4B `AdverseEvent` maps as Equivalent to R5 `AdverseEvent` |
| AdverseEvent.actuality | AdverseEvent.actuality | Equivalent | R4B `AdverseEvent.actuality` maps as Equivalent to R5 `AdverseEvent.actuality` - actuality has compatible required binding for code type: http://hl7.org/fhir/ValueSet/adverse-event-actuality|4.3.0 and http://hl7.org/fhir/ValueSet/adverse-event-actuality|5.0.0 (Equivalent) |
| AdverseEvent.category | AdverseEvent.category | RelatedTo | R4B `AdverseEvent.category` maps as RelatedTo to R5 `AdverseEvent.category` - category changed the binding strength from Extensible to Example |
| AdverseEvent.contained | AdverseEvent.contained | Equivalent | R4B `AdverseEvent.contained` maps as Equivalent to R5 `AdverseEvent.contained` |
| AdverseEvent.contributor | - | DoesNotExistInTarget | R4B `AdverseEvent.contributor` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.date | - | DoesNotExistInTarget | R4B `AdverseEvent.date` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.detected | AdverseEvent.detected | Equivalent | R4B `AdverseEvent.detected` maps as Equivalent to R5 `AdverseEvent.detected` |
| AdverseEvent.encounter | AdverseEvent.encounter | Equivalent | R4B `AdverseEvent.encounter` maps as Equivalent to R5 `AdverseEvent.encounter` |
| AdverseEvent.event | - | DoesNotExistInTarget | R4B `AdverseEvent.event` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.extension | AdverseEvent.extension | RelatedTo | R4B `AdverseEvent.extension` maps as RelatedTo to R5 `AdverseEvent.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| AdverseEvent.id | AdverseEvent.id | Equivalent | R4B `AdverseEvent.id` maps as Equivalent to R5 `AdverseEvent.id` |
| AdverseEvent.identifier | AdverseEvent.identifier | RelatedTo | R4B `AdverseEvent.identifier` maps as RelatedTo to R5 `AdverseEvent.identifier` - identifier changed from scalar to array (max cardinality from 1 to *) |
| AdverseEvent.implicitRules | AdverseEvent.implicitRules | Equivalent | R4B `AdverseEvent.implicitRules` maps as Equivalent to R5 `AdverseEvent.implicitRules` |
| AdverseEvent.language | AdverseEvent.language | RelatedTo | R4B `AdverseEvent.language` maps as RelatedTo to R5 `AdverseEvent.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| AdverseEvent.location | AdverseEvent.location | Equivalent | R4B `AdverseEvent.location` maps as Equivalent to R5 `AdverseEvent.location` |
| AdverseEvent.meta | AdverseEvent.meta | Equivalent | R4B `AdverseEvent.meta` maps as Equivalent to R5 `AdverseEvent.meta` |
| AdverseEvent.modifierExtension | AdverseEvent.modifierExtension | RelatedTo | R4B `AdverseEvent.modifierExtension` maps as RelatedTo to R5 `AdverseEvent.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| AdverseEvent.outcome | AdverseEvent.outcome | RelatedTo | R4B `AdverseEvent.outcome` maps as RelatedTo to R5 `AdverseEvent.outcome` - outcome changed from scalar to array (max cardinality from 1 to *); outcome changed the binding strength from Required to Example |
| AdverseEvent.recordedDate | AdverseEvent.recordedDate | Equivalent | R4B `AdverseEvent.recordedDate` maps as Equivalent to R5 `AdverseEvent.recordedDate` |
| AdverseEvent.recorder | AdverseEvent.recorder | SourceIsNarrowerThanTarget | R4B `AdverseEvent.recorder` maps as SourceIsNarrowerThanTarget to R5 `AdverseEvent.recorder` - recorder has change due to type change: R4B `recorder` `Reference` maps as SourceIsNarrowerThanTarget for R5 `recorder` |
| AdverseEvent.referenceDocument | - | DoesNotExistInTarget | R4B `AdverseEvent.referenceDocument` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.resultingCondition | - | DoesNotExistInTarget | R4B `AdverseEvent.resultingCondition` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.seriousness | AdverseEvent.seriousness | Equivalent | R4B `AdverseEvent.seriousness` maps as Equivalent to R5 `AdverseEvent.seriousness` |
| AdverseEvent.severity | - | DoesNotExistInTarget | R4B `AdverseEvent.severity` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.study | AdverseEvent.study | Equivalent | R4B `AdverseEvent.study` maps as Equivalent to R5 `AdverseEvent.study` |
| AdverseEvent.subject | AdverseEvent.subject | SourceIsNarrowerThanTarget | R4B `AdverseEvent.subject` maps as SourceIsNarrowerThanTarget to R5 `AdverseEvent.subject` - subject has change due to type change: R4B `subject` `Reference` maps as SourceIsNarrowerThanTarget for R5 `subject` |
| AdverseEvent.subjectMedicalHistory | - | DoesNotExistInTarget | R4B `AdverseEvent.subjectMedicalHistory` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.suspectEntity | AdverseEvent.suspectEntity | Equivalent | R4B `AdverseEvent.suspectEntity` maps as Equivalent to R5 `AdverseEvent.suspectEntity` |
| AdverseEvent.suspectEntity.causality | AdverseEvent.suspectEntity.causality | RelatedTo | R4B `AdverseEvent.suspectEntity.causality` maps as RelatedTo to R5 `AdverseEvent.suspectEntity.causality` - causality changed from array to scalar (max cardinality from * to 1) |
| AdverseEvent.suspectEntity.causality.assessment | - | DoesNotExistInTarget | R4B `AdverseEvent.suspectEntity.causality.assessment` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.suspectEntity.causality.author | AdverseEvent.suspectEntity.causality.author | SourceIsNarrowerThanTarget | R4B `AdverseEvent.suspectEntity.causality.author` maps as SourceIsNarrowerThanTarget to R5 `AdverseEvent.suspectEntity.causality.author` - author has change due to type change: R4B `author` `Reference` maps as SourceIsNarrowerThanTarget for R5 `author` |
| AdverseEvent.suspectEntity.causality.extension | AdverseEvent.suspectEntity.causality.extension | RelatedTo | R4B `AdverseEvent.suspectEntity.causality.extension` maps as RelatedTo to R5 `AdverseEvent.suspectEntity.causality.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| AdverseEvent.suspectEntity.causality.id | AdverseEvent.suspectEntity.causality.id | Equivalent | R4B `AdverseEvent.suspectEntity.causality.id` maps as Equivalent to R5 `AdverseEvent.suspectEntity.causality.id` |
| AdverseEvent.suspectEntity.causality.method | - | DoesNotExistInTarget | R4B `AdverseEvent.suspectEntity.causality.method` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.suspectEntity.causality.modifierExtension | AdverseEvent.suspectEntity.causality.modifierExtension | RelatedTo | R4B `AdverseEvent.suspectEntity.causality.modifierExtension` maps as RelatedTo to R5 `AdverseEvent.suspectEntity.causality.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| AdverseEvent.suspectEntity.causality.productRelatedness | - | DoesNotExistInTarget | R4B `AdverseEvent.suspectEntity.causality.productRelatedness` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.suspectEntity.extension | AdverseEvent.suspectEntity.extension | RelatedTo | R4B `AdverseEvent.suspectEntity.extension` maps as RelatedTo to R5 `AdverseEvent.suspectEntity.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| AdverseEvent.suspectEntity.id | AdverseEvent.suspectEntity.id | Equivalent | R4B `AdverseEvent.suspectEntity.id` maps as Equivalent to R5 `AdverseEvent.suspectEntity.id` |
| AdverseEvent.suspectEntity.instance | - | DoesNotExistInTarget | R4B `AdverseEvent.suspectEntity.instance` does not appear in the target and has no mapping for `AdverseEvent`. |
| AdverseEvent.suspectEntity.modifierExtension | AdverseEvent.suspectEntity.modifierExtension | RelatedTo | R4B `AdverseEvent.suspectEntity.modifierExtension` maps as RelatedTo to R5 `AdverseEvent.suspectEntity.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| AdverseEvent.text | AdverseEvent.text | Equivalent | R4B `AdverseEvent.text` maps as Equivalent to R5 `AdverseEvent.text` |

