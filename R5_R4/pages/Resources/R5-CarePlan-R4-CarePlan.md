Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | CarePlan |  | Describes the intention of how one or more practitioners intend to deliver care for a particular patient, group or community for a period of time, possibly limited to care for a specific condition or set of conditions. | 38 | 27 |
| Target | CarePlan |  | Describes the intention of how one or more practitioners intend to deliver care for a particular patient, group or community for a period of time, possibly limited to care for a specific condition or set of conditions. | 60 | 46 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 27 |
RelatedTo | 3 |
SourceIsBroaderThanTarget | 7 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| CarePlan | CarePlan | Equivalent | R5 `CarePlan` maps as Equivalent to R4 `CarePlan` |
| CarePlan.activity | CarePlan.activity | Equivalent | R5 `CarePlan.activity` maps as Equivalent to R4 `CarePlan.activity` |
| CarePlan.activity.extension | CarePlan.activity.extension | SourceIsBroaderThanTarget | R5 `CarePlan.activity.extension` maps as SourceIsBroaderThanTarget to R4 `CarePlan.activity.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| CarePlan.activity.id | CarePlan.activity.id | Equivalent | R5 `CarePlan.activity.id` maps as Equivalent to R4 `CarePlan.activity.id` |
| CarePlan.activity.modifierExtension | CarePlan.activity.modifierExtension | SourceIsBroaderThanTarget | R5 `CarePlan.activity.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `CarePlan.activity.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| CarePlan.activity.performedActivity | CarePlan.activity.reference | RelatedTo | R5 `CarePlan.activity.performedActivity` maps as RelatedTo to R4 `CarePlan.activity.reference` - reference changed from array to scalar (max cardinality from * to 1); reference removed a binding requirement - Example http://hl7.org/fhir/ValueSet/care-plan-activity-performed; reference has change due to type change: R5 performedActivity CodeableReference has no equivalent or mapped type in R4 reference |
| CarePlan.activity.performedActivity | CarePlan.activity.outcomeCodeableConcept | SourceIsBroaderThanTarget | R5 `CarePlan.activity.performedActivity` maps as SourceIsBroaderThanTarget to R4 `CarePlan.activity.outcomeCodeableConcept` - outcomeCodeableConcept has change due to type change: R5 performedActivity CodeableReference has no equivalent or mapped type in R4 outcomeCodeableConcept |
| CarePlan.activity.performedActivity | CarePlan.activity.outcomeReference | RelatedTo | R5 `CarePlan.activity.performedActivity` maps as RelatedTo to R4 `CarePlan.activity.outcomeReference` - outcomeReference removed a binding requirement - Example http://hl7.org/fhir/ValueSet/care-plan-activity-performed; outcomeReference has change due to type change: R5 performedActivity CodeableReference has no equivalent or mapped type in R4 outcomeReference |
| CarePlan.activity.plannedActivityReference | CarePlan.activity.reference | RelatedTo | R5 `CarePlan.activity.plannedActivityReference` maps as RelatedTo to R4 `CarePlan.activity.reference` - reference has change due to type change: R5 `plannedActivityReference` `Reference` maps as RelatedTo for R4 `reference` |
| CarePlan.activity.progress | CarePlan.activity.progress | SourceIsBroaderThanTarget | R5 `CarePlan.activity.progress` maps as SourceIsBroaderThanTarget to R4 `CarePlan.activity.progress` - progress has change due to type change: R5 `progress` `Annotation` maps as SourceIsBroaderThanTarget for R4 `progress` |
| CarePlan.addresses | CarePlan.addresses | RelatedTo | R5 `CarePlan.addresses` maps as RelatedTo to R4 `CarePlan.addresses` - addresses removed a binding requirement - Example http://hl7.org/fhir/ValueSet/clinical-findings; addresses has change due to type change: R5 addresses CodeableReference has no equivalent or mapped type in R4 addresses |
| CarePlan.basedOn | CarePlan.basedOn | SourceIsBroaderThanTarget | R5 `CarePlan.basedOn` maps as SourceIsBroaderThanTarget to R4 `CarePlan.basedOn` - basedOn has change due to type change: R5 `basedOn` `Reference` maps as SourceIsBroaderThanTarget for R4 `basedOn` |
| CarePlan.careTeam | CarePlan.careTeam | Equivalent | R5 `CarePlan.careTeam` maps as Equivalent to R4 `CarePlan.careTeam` |
| CarePlan.category | CarePlan.category | Equivalent | R5 `CarePlan.category` maps as Equivalent to R4 `CarePlan.category` |
| CarePlan.contained | CarePlan.contained | Equivalent | R5 `CarePlan.contained` maps as Equivalent to R4 `CarePlan.contained` |
| CarePlan.contributor | CarePlan.contributor | Equivalent | R5 `CarePlan.contributor` maps as Equivalent to R4 `CarePlan.contributor` |
| CarePlan.created | CarePlan.created | Equivalent | R5 `CarePlan.created` maps as Equivalent to R4 `CarePlan.created` |
| CarePlan.custodian | CarePlan.author | Equivalent | R5 `CarePlan.custodian` maps as Equivalent to R4 `CarePlan.author` |
| CarePlan.description | CarePlan.description | Equivalent | R5 `CarePlan.description` maps as Equivalent to R4 `CarePlan.description` |
| CarePlan.encounter | CarePlan.encounter | Equivalent | R5 `CarePlan.encounter` maps as Equivalent to R4 `CarePlan.encounter` |
| CarePlan.extension | CarePlan.extension | SourceIsBroaderThanTarget | R5 `CarePlan.extension` maps as SourceIsBroaderThanTarget to R4 `CarePlan.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| CarePlan.goal | CarePlan.goal | Equivalent | R5 `CarePlan.goal` maps as Equivalent to R4 `CarePlan.goal` |
| CarePlan.id | CarePlan.id | Equivalent | R5 `CarePlan.id` maps as Equivalent to R4 `CarePlan.id` |
| CarePlan.identifier | CarePlan.identifier | Equivalent | R5 `CarePlan.identifier` maps as Equivalent to R4 `CarePlan.identifier` |
| CarePlan.implicitRules | CarePlan.implicitRules | Equivalent | R5 `CarePlan.implicitRules` maps as Equivalent to R4 `CarePlan.implicitRules` |
| CarePlan.instantiatesCanonical | CarePlan.instantiatesCanonical | Equivalent | R5 `CarePlan.instantiatesCanonical` maps as Equivalent to R4 `CarePlan.instantiatesCanonical` |
| CarePlan.instantiatesUri | CarePlan.instantiatesUri | Equivalent | R5 `CarePlan.instantiatesUri` maps as Equivalent to R4 `CarePlan.instantiatesUri` |
| CarePlan.intent | CarePlan.intent | Equivalent | R5 `CarePlan.intent` maps as Equivalent to R4 `CarePlan.intent` - intent has compatible required binding for code type: http://hl7.org/fhir/ValueSet/care-plan-intent|5.0.0 and http://hl7.org/fhir/ValueSet/care-plan-intent|4.0.1 (Equivalent) |
| CarePlan.language | CarePlan.language | SourceIsNarrowerThanTarget | R5 `CarePlan.language` maps as SourceIsNarrowerThanTarget to R4 `CarePlan.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| CarePlan.meta | CarePlan.meta | Equivalent | R5 `CarePlan.meta` maps as Equivalent to R4 `CarePlan.meta` |
| CarePlan.modifierExtension | CarePlan.modifierExtension | SourceIsBroaderThanTarget | R5 `CarePlan.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `CarePlan.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| CarePlan.note | CarePlan.note | SourceIsBroaderThanTarget | R5 `CarePlan.note` maps as SourceIsBroaderThanTarget to R4 `CarePlan.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4 `note` |
| CarePlan.partOf | CarePlan.partOf | Equivalent | R5 `CarePlan.partOf` maps as Equivalent to R4 `CarePlan.partOf` |
| CarePlan.period | CarePlan.period | Equivalent | R5 `CarePlan.period` maps as Equivalent to R4 `CarePlan.period` |
| CarePlan.replaces | CarePlan.replaces | Equivalent | R5 `CarePlan.replaces` maps as Equivalent to R4 `CarePlan.replaces` |
| CarePlan.status | CarePlan.status | Equivalent | R5 `CarePlan.status` maps as Equivalent to R4 `CarePlan.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-status|5.0.0 and http://hl7.org/fhir/ValueSet/request-status|4.0.1 (Equivalent) |
| CarePlan.subject | CarePlan.subject | Equivalent | R5 `CarePlan.subject` maps as Equivalent to R4 `CarePlan.subject` |
| CarePlan.supportingInfo | CarePlan.supportingInfo | Equivalent | R5 `CarePlan.supportingInfo` maps as Equivalent to R4 `CarePlan.supportingInfo` |
| CarePlan.text | CarePlan.text | Equivalent | R5 `CarePlan.text` maps as Equivalent to R4 `CarePlan.text` |
| CarePlan.title | CarePlan.title | Equivalent | R5 `CarePlan.title` maps as Equivalent to R4 `CarePlan.title` |

