Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Observation |  | Measurements and simple assertions made about a patient, device or other subject. | 60 | 43 |
| Target | Observation |  | Measurements and simple assertions made about a patient, device or other subject. | 50 | 36 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 10 |
Equivalent | 4 |
RelatedTo | 46 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Observation | Observation | Equivalent | R5 `Observation` maps as Equivalent to R4B `Observation` |
| Observation.basedOn | Observation.basedOn | Equivalent | R5 `Observation.basedOn` maps as Equivalent to R4B `Observation.basedOn` |
| Observation.bodySite | Observation.bodySite | Equivalent | R5 `Observation.bodySite` maps as Equivalent to R4B `Observation.bodySite` |
| Observation.bodyStructure | - | DoesNotExistInTarget | R5 `Observation.bodyStructure` does not appear in the target and has no mapping for `Observation`. |
| Observation.category | Observation.category | Equivalent | R5 `Observation.category` maps as Equivalent to R4B `Observation.category` |
| Observation.code | Observation.code | Equivalent | R5 `Observation.code` maps as Equivalent to R4B `Observation.code` |
| Observation.component | Observation.component | Equivalent | R5 `Observation.component` maps as Equivalent to R4B `Observation.component` |
| Observation.component.code | Observation.component.code | Equivalent | R5 `Observation.component.code` maps as Equivalent to R4B `Observation.component.code` |
| Observation.component.dataAbsentReason | Observation.component.dataAbsentReason | Equivalent | R5 `Observation.component.dataAbsentReason` maps as Equivalent to R4B `Observation.component.dataAbsentReason` |
| Observation.component.extension | Observation.component.extension | SourceIsBroaderThanTarget | R5 `Observation.component.extension` maps as SourceIsBroaderThanTarget to R4B `Observation.component.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Observation.component.id | Observation.component.id | Equivalent | R5 `Observation.component.id` maps as Equivalent to R4B `Observation.component.id` |
| Observation.component.interpretation | Observation.component.interpretation | Equivalent | R5 `Observation.component.interpretation` maps as Equivalent to R4B `Observation.component.interpretation` |
| Observation.component.modifierExtension | Observation.component.modifierExtension | SourceIsBroaderThanTarget | R5 `Observation.component.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Observation.component.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Observation.component.referenceRange | Observation.component.referenceRange | Equivalent | R5 `Observation.component.referenceRange` maps as Equivalent to R4B `Observation.component.referenceRange` |
| Observation.component.value[x] | Observation.component.value[x] | SourceIsBroaderThanTarget | R5 `Observation.component.value[x]` maps as SourceIsBroaderThanTarget to R4B `Observation.component.value[x]` - value[x] has change due to type change: R5 `value[x]` `Ratio` maps as SourceIsBroaderThanTarget for R4B `value[x]`; value[x] has change due to type change: R5 value[x] Attachment has no equivalent or mapped type in R4B value[x]; value[x] has change due to type change: R5 value[x] Reference has no equivalent or mapped type in R4B value[x] |
| Observation.contained | Observation.contained | Equivalent | R5 `Observation.contained` maps as Equivalent to R4B `Observation.contained` |
| Observation.dataAbsentReason | Observation.dataAbsentReason | Equivalent | R5 `Observation.dataAbsentReason` maps as Equivalent to R4B `Observation.dataAbsentReason` |
| Observation.derivedFrom | Observation.derivedFrom | RelatedTo | R5 `Observation.derivedFrom` maps as RelatedTo to R4B `Observation.derivedFrom` - derivedFrom has change due to type change: R5 `derivedFrom` `Reference` maps as RelatedTo for R4B `derivedFrom` |
| Observation.device | Observation.device | Equivalent | R5 `Observation.device` maps as Equivalent to R4B `Observation.device` |
| Observation.effective[x] | Observation.effective[x] | Equivalent | R5 `Observation.effective[x]` maps as Equivalent to R4B `Observation.effective[x]` |
| Observation.encounter | Observation.encounter | Equivalent | R5 `Observation.encounter` maps as Equivalent to R4B `Observation.encounter` |
| Observation.extension | Observation.extension | SourceIsBroaderThanTarget | R5 `Observation.extension` maps as SourceIsBroaderThanTarget to R4B `Observation.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Observation.focus | Observation.focus | Equivalent | R5 `Observation.focus` maps as Equivalent to R4B `Observation.focus` |
| Observation.hasMember | Observation.hasMember | Equivalent | R5 `Observation.hasMember` maps as Equivalent to R4B `Observation.hasMember` |
| Observation.id | Observation.id | Equivalent | R5 `Observation.id` maps as Equivalent to R4B `Observation.id` |
| Observation.identifier | Observation.identifier | Equivalent | R5 `Observation.identifier` maps as Equivalent to R4B `Observation.identifier` |
| Observation.implicitRules | Observation.implicitRules | Equivalent | R5 `Observation.implicitRules` maps as Equivalent to R4B `Observation.implicitRules` |
| Observation.instantiates[x] | - | DoesNotExistInTarget | R5 `Observation.instantiates[x]` does not appear in the target and has no mapping for `Observation`. |
| Observation.interpretation | Observation.interpretation | Equivalent | R5 `Observation.interpretation` maps as Equivalent to R4B `Observation.interpretation` |
| Observation.issued | Observation.issued | Equivalent | R5 `Observation.issued` maps as Equivalent to R4B `Observation.issued` |
| Observation.language | Observation.language | RelatedTo | R5 `Observation.language` maps as RelatedTo to R4B `Observation.language` - language changed the binding strength from Required to Preferred |
| Observation.meta | Observation.meta | Equivalent | R5 `Observation.meta` maps as Equivalent to R4B `Observation.meta` |
| Observation.method | Observation.method | Equivalent | R5 `Observation.method` maps as Equivalent to R4B `Observation.method` |
| Observation.modifierExtension | Observation.modifierExtension | SourceIsBroaderThanTarget | R5 `Observation.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Observation.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Observation.note | Observation.note | SourceIsBroaderThanTarget | R5 `Observation.note` maps as SourceIsBroaderThanTarget to R4B `Observation.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| Observation.partOf | Observation.partOf | SourceIsBroaderThanTarget | R5 `Observation.partOf` maps as SourceIsBroaderThanTarget to R4B `Observation.partOf` - partOf has change due to type change: R5 `partOf` `Reference` maps as SourceIsBroaderThanTarget for R4B `partOf` |
| Observation.performer | Observation.performer | Equivalent | R5 `Observation.performer` maps as Equivalent to R4B `Observation.performer` |
| Observation.referenceRange | Observation.referenceRange | Equivalent | R5 `Observation.referenceRange` maps as Equivalent to R4B `Observation.referenceRange` |
| Observation.referenceRange.age | Observation.referenceRange.age | Equivalent | R5 `Observation.referenceRange.age` maps as Equivalent to R4B `Observation.referenceRange.age` |
| Observation.referenceRange.appliesTo | Observation.referenceRange.appliesTo | Equivalent | R5 `Observation.referenceRange.appliesTo` maps as Equivalent to R4B `Observation.referenceRange.appliesTo` |
| Observation.referenceRange.extension | Observation.referenceRange.extension | SourceIsBroaderThanTarget | R5 `Observation.referenceRange.extension` maps as SourceIsBroaderThanTarget to R4B `Observation.referenceRange.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Observation.referenceRange.high | Observation.referenceRange.high | Equivalent | R5 `Observation.referenceRange.high` maps as Equivalent to R4B `Observation.referenceRange.high` |
| Observation.referenceRange.id | Observation.referenceRange.id | Equivalent | R5 `Observation.referenceRange.id` maps as Equivalent to R4B `Observation.referenceRange.id` |
| Observation.referenceRange.low | Observation.referenceRange.low | Equivalent | R5 `Observation.referenceRange.low` maps as Equivalent to R4B `Observation.referenceRange.low` |
| Observation.referenceRange.modifierExtension | Observation.referenceRange.modifierExtension | SourceIsBroaderThanTarget | R5 `Observation.referenceRange.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Observation.referenceRange.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Observation.referenceRange.normalValue | - | DoesNotExistInTarget | R5 `Observation.referenceRange.normalValue` does not appear in the target and has no mapping for `Observation`. |
| Observation.referenceRange.text | Observation.referenceRange.text | SourceIsBroaderThanTarget | R5 `Observation.referenceRange.text` maps as SourceIsBroaderThanTarget to R4B `Observation.referenceRange.text` - text has change due to type change: R5 text markdown has no equivalent or mapped type in R4B text |
| Observation.referenceRange.type | Observation.referenceRange.type | Equivalent | R5 `Observation.referenceRange.type` maps as Equivalent to R4B `Observation.referenceRange.type` |
| Observation.specimen | Observation.specimen | SourceIsBroaderThanTarget | R5 `Observation.specimen` maps as SourceIsBroaderThanTarget to R4B `Observation.specimen` - specimen has change due to type change: R5 `specimen` `Reference` maps as SourceIsBroaderThanTarget for R4B `specimen` |
| Observation.status | Observation.status | Equivalent | R5 `Observation.status` maps as Equivalent to R4B `Observation.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/observation-status|5.0.0 and http://hl7.org/fhir/ValueSet/observation-status|4.3.0 (Equivalent) |
| Observation.subject | Observation.subject | SourceIsBroaderThanTarget | R5 `Observation.subject` maps as SourceIsBroaderThanTarget to R4B `Observation.subject` - subject has change due to type change: R5 `subject` `Reference` maps as SourceIsBroaderThanTarget for R4B `subject` |
| Observation.text | Observation.text | Equivalent | R5 `Observation.text` maps as Equivalent to R4B `Observation.text` |
| Observation.triggeredBy | - | DoesNotExistInTarget | R5 `Observation.triggeredBy` does not appear in the target and has no mapping for `Observation`. |
| Observation.triggeredBy.extension | - | DoesNotExistInTarget | R5 `Observation.triggeredBy.extension` does not appear in the target and has no mapping for `Observation`. |
| Observation.triggeredBy.id | - | DoesNotExistInTarget | R5 `Observation.triggeredBy.id` does not appear in the target and has no mapping for `Observation`. |
| Observation.triggeredBy.modifierExtension | - | DoesNotExistInTarget | R5 `Observation.triggeredBy.modifierExtension` does not appear in the target and has no mapping for `Observation`. |
| Observation.triggeredBy.observation | - | DoesNotExistInTarget | R5 `Observation.triggeredBy.observation` does not appear in the target and has no mapping for `Observation`. |
| Observation.triggeredBy.reason | - | DoesNotExistInTarget | R5 `Observation.triggeredBy.reason` does not appear in the target and has no mapping for `Observation`. |
| Observation.triggeredBy.type | - | DoesNotExistInTarget | R5 `Observation.triggeredBy.type` does not appear in the target and has no mapping for `Observation`. |
| Observation.value[x] | Observation.value[x] | SourceIsBroaderThanTarget | R5 `Observation.value[x]` maps as SourceIsBroaderThanTarget to R4B `Observation.value[x]` - value[x] has change due to type change: R5 `value[x]` `Ratio` maps as SourceIsBroaderThanTarget for R4B `value[x]`; value[x] has change due to type change: R5 value[x] Attachment has no equivalent or mapped type in R4B value[x]; value[x] has change due to type change: R5 value[x] Reference has no equivalent or mapped type in R4B value[x] |

