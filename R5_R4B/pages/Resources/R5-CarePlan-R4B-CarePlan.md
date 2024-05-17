Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | CarePlan |  | Describes the intention of how one or more practitioners intend to deliver care for a particular patient, group or community for a period of time, possibly limited to care for a specific condition or set of conditions. | 38 | 27 |
| Target | CarePlan |  | Describes the intention of how one or more practitioners intend to deliver care for a particular patient, group or community for a period of time, possibly limited to care for a specific condition or set of conditions. | 60 | 46 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 3 |
Equivalent | 4 |
RelatedTo | 31 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| CarePlan | CarePlan | Equivalent | R5 `CarePlan` maps as Equivalent to R4B `CarePlan` |
| CarePlan.activity | CarePlan.activity | Equivalent | R5 `CarePlan.activity` maps as Equivalent to R4B `CarePlan.activity` |
| CarePlan.activity.extension | CarePlan.activity.extension | SourceIsBroaderThanTarget | R5 `CarePlan.activity.extension` maps as SourceIsBroaderThanTarget to R4B `CarePlan.activity.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| CarePlan.activity.id | CarePlan.activity.id | Equivalent | R5 `CarePlan.activity.id` maps as Equivalent to R4B `CarePlan.activity.id` |
| CarePlan.activity.modifierExtension | CarePlan.activity.modifierExtension | SourceIsBroaderThanTarget | R5 `CarePlan.activity.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `CarePlan.activity.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| CarePlan.activity.performedActivity | - | DoesNotExistInTarget | R5 `CarePlan.activity.performedActivity` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.plannedActivityReference | - | DoesNotExistInTarget | R5 `CarePlan.activity.plannedActivityReference` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.activity.progress | CarePlan.activity.progress | SourceIsBroaderThanTarget | R5 `CarePlan.activity.progress` maps as SourceIsBroaderThanTarget to R4B `CarePlan.activity.progress` - progress has change due to type change: R5 `progress` `Annotation` maps as SourceIsBroaderThanTarget for R4B `progress` |
| CarePlan.addresses | CarePlan.addresses | RelatedTo | R5 `CarePlan.addresses` maps as RelatedTo to R4B `CarePlan.addresses` - addresses removed a binding requirement - Example http://hl7.org/fhir/ValueSet/clinical-findings; addresses has change due to type change: R5 addresses CodeableReference has no equivalent or mapped type in R4B addresses |
| CarePlan.basedOn | CarePlan.basedOn | SourceIsBroaderThanTarget | R5 `CarePlan.basedOn` maps as SourceIsBroaderThanTarget to R4B `CarePlan.basedOn` - basedOn has change due to type change: R5 `basedOn` `Reference` maps as SourceIsBroaderThanTarget for R4B `basedOn` |
| CarePlan.careTeam | CarePlan.careTeam | Equivalent | R5 `CarePlan.careTeam` maps as Equivalent to R4B `CarePlan.careTeam` |
| CarePlan.category | CarePlan.category | Equivalent | R5 `CarePlan.category` maps as Equivalent to R4B `CarePlan.category` |
| CarePlan.contained | CarePlan.contained | Equivalent | R5 `CarePlan.contained` maps as Equivalent to R4B `CarePlan.contained` |
| CarePlan.contributor | CarePlan.contributor | Equivalent | R5 `CarePlan.contributor` maps as Equivalent to R4B `CarePlan.contributor` |
| CarePlan.created | CarePlan.created | Equivalent | R5 `CarePlan.created` maps as Equivalent to R4B `CarePlan.created` |
| CarePlan.custodian | - | DoesNotExistInTarget | R5 `CarePlan.custodian` does not appear in the target and has no mapping for `CarePlan`. |
| CarePlan.description | CarePlan.description | Equivalent | R5 `CarePlan.description` maps as Equivalent to R4B `CarePlan.description` |
| CarePlan.encounter | CarePlan.encounter | Equivalent | R5 `CarePlan.encounter` maps as Equivalent to R4B `CarePlan.encounter` |
| CarePlan.extension | CarePlan.extension | SourceIsBroaderThanTarget | R5 `CarePlan.extension` maps as SourceIsBroaderThanTarget to R4B `CarePlan.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| CarePlan.goal | CarePlan.goal | Equivalent | R5 `CarePlan.goal` maps as Equivalent to R4B `CarePlan.goal` |
| CarePlan.id | CarePlan.id | Equivalent | R5 `CarePlan.id` maps as Equivalent to R4B `CarePlan.id` |
| CarePlan.identifier | CarePlan.identifier | Equivalent | R5 `CarePlan.identifier` maps as Equivalent to R4B `CarePlan.identifier` |
| CarePlan.implicitRules | CarePlan.implicitRules | Equivalent | R5 `CarePlan.implicitRules` maps as Equivalent to R4B `CarePlan.implicitRules` |
| CarePlan.instantiatesCanonical | CarePlan.instantiatesCanonical | Equivalent | R5 `CarePlan.instantiatesCanonical` maps as Equivalent to R4B `CarePlan.instantiatesCanonical` |
| CarePlan.instantiatesUri | CarePlan.instantiatesUri | Equivalent | R5 `CarePlan.instantiatesUri` maps as Equivalent to R4B `CarePlan.instantiatesUri` |
| CarePlan.intent | CarePlan.intent | Equivalent | R5 `CarePlan.intent` maps as Equivalent to R4B `CarePlan.intent` - intent has compatible required binding for code type: http://hl7.org/fhir/ValueSet/care-plan-intent|5.0.0 and http://hl7.org/fhir/ValueSet/care-plan-intent|4.3.0 (Equivalent) |
| CarePlan.language | CarePlan.language | RelatedTo | R5 `CarePlan.language` maps as RelatedTo to R4B `CarePlan.language` - language changed the binding strength from Required to Preferred |
| CarePlan.meta | CarePlan.meta | Equivalent | R5 `CarePlan.meta` maps as Equivalent to R4B `CarePlan.meta` |
| CarePlan.modifierExtension | CarePlan.modifierExtension | SourceIsBroaderThanTarget | R5 `CarePlan.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `CarePlan.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| CarePlan.note | CarePlan.note | SourceIsBroaderThanTarget | R5 `CarePlan.note` maps as SourceIsBroaderThanTarget to R4B `CarePlan.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4B `note` |
| CarePlan.partOf | CarePlan.partOf | Equivalent | R5 `CarePlan.partOf` maps as Equivalent to R4B `CarePlan.partOf` |
| CarePlan.period | CarePlan.period | Equivalent | R5 `CarePlan.period` maps as Equivalent to R4B `CarePlan.period` |
| CarePlan.replaces | CarePlan.replaces | Equivalent | R5 `CarePlan.replaces` maps as Equivalent to R4B `CarePlan.replaces` |
| CarePlan.status | CarePlan.status | Equivalent | R5 `CarePlan.status` maps as Equivalent to R4B `CarePlan.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-status|5.0.0 and http://hl7.org/fhir/ValueSet/request-status|4.3.0 (Equivalent) |
| CarePlan.subject | CarePlan.subject | Equivalent | R5 `CarePlan.subject` maps as Equivalent to R4B `CarePlan.subject` |
| CarePlan.supportingInfo | CarePlan.supportingInfo | Equivalent | R5 `CarePlan.supportingInfo` maps as Equivalent to R4B `CarePlan.supportingInfo` |
| CarePlan.text | CarePlan.text | Equivalent | R5 `CarePlan.text` maps as Equivalent to R4B `CarePlan.text` |
| CarePlan.title | CarePlan.title | Equivalent | R5 `CarePlan.title` maps as Equivalent to R4B `CarePlan.title` |

