Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | CarePlan |  | Describes the intention of how one or more practitioners intend to deliver care for a particular patient, group or community for a period of time, possibly limited to care for a specific condition or set of conditions. | 60 | 46 |
| Target | CarePlan |  | Describes the intention of how one or more practitioners intend to deliver care for a particular patient, group or community for a period of time, possibly limited to care for a specific condition or set of conditions. | 38 | 27 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 25 |
Equivalent | 4 |
RelatedTo | 31 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| CarePlan | CarePlan | Equivalent | R4B `CarePlan` maps as Equivalent to R5 `CarePlan` |
| CarePlan.activity | CarePlan.activity | Equivalent | R4B `CarePlan.activity` maps as Equivalent to R5 `CarePlan.activity` |
| CarePlan.activity.detail | - | DoesNotExistInTarget | R4B `CarePlan.activity.detail` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.detail.code | - | DoesNotExistInTarget | R4B `CarePlan.activity.detail.code` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.detail.dailyAmount | - | DoesNotExistInTarget | R4B `CarePlan.activity.detail.dailyAmount` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.detail.description | - | DoesNotExistInTarget | R4B `CarePlan.activity.detail.description` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.detail.doNotPerform | - | DoesNotExistInTarget | R4B `CarePlan.activity.detail.doNotPerform` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.detail.extension | - | DoesNotExistInTarget | R4B `CarePlan.activity.detail.extension` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.detail.goal | - | DoesNotExistInTarget | R4B `CarePlan.activity.detail.goal` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.detail.id | - | DoesNotExistInTarget | R4B `CarePlan.activity.detail.id` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.detail.instantiatesCanonical | - | DoesNotExistInTarget | R4B `CarePlan.activity.detail.instantiatesCanonical` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.detail.instantiatesUri | - | DoesNotExistInTarget | R4B `CarePlan.activity.detail.instantiatesUri` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.detail.kind | - | DoesNotExistInTarget | R4B `CarePlan.activity.detail.kind` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.detail.location | - | DoesNotExistInTarget | R4B `CarePlan.activity.detail.location` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.detail.modifierExtension | - | DoesNotExistInTarget | R4B `CarePlan.activity.detail.modifierExtension` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.detail.performer | - | DoesNotExistInTarget | R4B `CarePlan.activity.detail.performer` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.detail.product[x] | - | DoesNotExistInTarget | R4B `CarePlan.activity.detail.product[x]` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.detail.quantity | - | DoesNotExistInTarget | R4B `CarePlan.activity.detail.quantity` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.detail.reasonCode | - | DoesNotExistInTarget | R4B `CarePlan.activity.detail.reasonCode` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.detail.reasonReference | - | DoesNotExistInTarget | R4B `CarePlan.activity.detail.reasonReference` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.detail.scheduled[x] | - | DoesNotExistInTarget | R4B `CarePlan.activity.detail.scheduled[x]` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.detail.status | - | DoesNotExistInTarget | R4B `CarePlan.activity.detail.status` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.detail.statusReason | - | DoesNotExistInTarget | R4B `CarePlan.activity.detail.statusReason` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.extension | CarePlan.activity.extension | RelatedTo | R4B `CarePlan.activity.extension` maps as RelatedTo to R5 `CarePlan.activity.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| CarePlan.activity.id | CarePlan.activity.id | Equivalent | R4B `CarePlan.activity.id` maps as Equivalent to R5 `CarePlan.activity.id` |
| CarePlan.activity.modifierExtension | CarePlan.activity.modifierExtension | RelatedTo | R4B `CarePlan.activity.modifierExtension` maps as RelatedTo to R5 `CarePlan.activity.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| CarePlan.activity.outcomeCodeableConcept | - | DoesNotExistInTarget | R4B `CarePlan.activity.outcomeCodeableConcept` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.outcomeReference | - | DoesNotExistInTarget | R4B `CarePlan.activity.outcomeReference` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.progress | CarePlan.activity.progress | SourceIsNarrowerThanTarget | R4B `CarePlan.activity.progress` maps as SourceIsNarrowerThanTarget to R5 `CarePlan.activity.progress` - progress has change due to type change: R4B `progress` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `progress` |
| CarePlan.activity.reference | - | DoesNotExistInTarget | R4B `CarePlan.activity.reference` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.addresses | CarePlan.addresses | RelatedTo | R4B `CarePlan.addresses` maps as RelatedTo to R5 `CarePlan.addresses` - addresses added a binding requirement - Example http://hl7.org/fhir/ValueSet/clinical-findings; addresses has change due to type change: R4B addresses Reference has no equivalent or mapped type in R5 addresses |
| CarePlan.author | - | DoesNotExistInTarget | R4B `CarePlan.author` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.basedOn | CarePlan.basedOn | SourceIsNarrowerThanTarget | R4B `CarePlan.basedOn` maps as SourceIsNarrowerThanTarget to R5 `CarePlan.basedOn` - basedOn has change due to type change: R4B `basedOn` `Reference` maps as SourceIsNarrowerThanTarget for R5 `basedOn` |
| CarePlan.careTeam | CarePlan.careTeam | Equivalent | R4B `CarePlan.careTeam` maps as Equivalent to R5 `CarePlan.careTeam` |
| CarePlan.category | CarePlan.category | Equivalent | R4B `CarePlan.category` maps as Equivalent to R5 `CarePlan.category` |
| CarePlan.contained | CarePlan.contained | Equivalent | R4B `CarePlan.contained` maps as Equivalent to R5 `CarePlan.contained` |
| CarePlan.contributor | CarePlan.contributor | Equivalent | R4B `CarePlan.contributor` maps as Equivalent to R5 `CarePlan.contributor` |
| CarePlan.created | CarePlan.created | Equivalent | R4B `CarePlan.created` maps as Equivalent to R5 `CarePlan.created` |
| CarePlan.description | CarePlan.description | Equivalent | R4B `CarePlan.description` maps as Equivalent to R5 `CarePlan.description` |
| CarePlan.encounter | CarePlan.encounter | Equivalent | R4B `CarePlan.encounter` maps as Equivalent to R5 `CarePlan.encounter` |
| CarePlan.extension | CarePlan.extension | RelatedTo | R4B `CarePlan.extension` maps as RelatedTo to R5 `CarePlan.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| CarePlan.goal | CarePlan.goal | Equivalent | R4B `CarePlan.goal` maps as Equivalent to R5 `CarePlan.goal` |
| CarePlan.id | CarePlan.id | Equivalent | R4B `CarePlan.id` maps as Equivalent to R5 `CarePlan.id` |
| CarePlan.identifier | CarePlan.identifier | Equivalent | R4B `CarePlan.identifier` maps as Equivalent to R5 `CarePlan.identifier` |
| CarePlan.implicitRules | CarePlan.implicitRules | Equivalent | R4B `CarePlan.implicitRules` maps as Equivalent to R5 `CarePlan.implicitRules` |
| CarePlan.instantiatesCanonical | CarePlan.instantiatesCanonical | Equivalent | R4B `CarePlan.instantiatesCanonical` maps as Equivalent to R5 `CarePlan.instantiatesCanonical` |
| CarePlan.instantiatesUri | CarePlan.instantiatesUri | Equivalent | R4B `CarePlan.instantiatesUri` maps as Equivalent to R5 `CarePlan.instantiatesUri` |
| CarePlan.intent | CarePlan.intent | Equivalent | R4B `CarePlan.intent` maps as Equivalent to R5 `CarePlan.intent` - intent has compatible required binding for code type: http://hl7.org/fhir/ValueSet/care-plan-intent|4.3.0 and http://hl7.org/fhir/ValueSet/care-plan-intent|5.0.0 (Equivalent) |
| CarePlan.language | CarePlan.language | RelatedTo | R4B `CarePlan.language` maps as RelatedTo to R5 `CarePlan.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| CarePlan.meta | CarePlan.meta | Equivalent | R4B `CarePlan.meta` maps as Equivalent to R5 `CarePlan.meta` |
| CarePlan.modifierExtension | CarePlan.modifierExtension | RelatedTo | R4B `CarePlan.modifierExtension` maps as RelatedTo to R5 `CarePlan.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| CarePlan.note | CarePlan.note | SourceIsNarrowerThanTarget | R4B `CarePlan.note` maps as SourceIsNarrowerThanTarget to R5 `CarePlan.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| CarePlan.partOf | CarePlan.partOf | Equivalent | R4B `CarePlan.partOf` maps as Equivalent to R5 `CarePlan.partOf` |
| CarePlan.period | CarePlan.period | Equivalent | R4B `CarePlan.period` maps as Equivalent to R5 `CarePlan.period` |
| CarePlan.replaces | CarePlan.replaces | Equivalent | R4B `CarePlan.replaces` maps as Equivalent to R5 `CarePlan.replaces` |
| CarePlan.status | CarePlan.status | Equivalent | R4B `CarePlan.status` maps as Equivalent to R5 `CarePlan.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-status|4.3.0 and http://hl7.org/fhir/ValueSet/request-status|5.0.0 (Equivalent) |
| CarePlan.subject | CarePlan.subject | Equivalent | R4B `CarePlan.subject` maps as Equivalent to R5 `CarePlan.subject` |
| CarePlan.supportingInfo | CarePlan.supportingInfo | Equivalent | R4B `CarePlan.supportingInfo` maps as Equivalent to R5 `CarePlan.supportingInfo` |
| CarePlan.text | CarePlan.text | Equivalent | R4B `CarePlan.text` maps as Equivalent to R5 `CarePlan.text` |
| CarePlan.title | CarePlan.title | Equivalent | R4B `CarePlan.title` maps as Equivalent to R5 `CarePlan.title` |

