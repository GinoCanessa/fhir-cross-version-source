Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | SubscriptionTopic |  | Describes a stream of resource state changes identified by trigger criteria and annotated with labels useful to filter projections from this topic. | 71 | 48 |
| Target | SubscriptionTopic |  | Describes a stream of resource state changes identified by trigger criteria and annotated with labels useful to filter projections from this topic. | 67 | 44 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 4 |
Equivalent | 4 |
RelatedTo | 63 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| SubscriptionTopic | SubscriptionTopic | Equivalent | R5 `SubscriptionTopic` maps as Equivalent to R4B `SubscriptionTopic` |
| SubscriptionTopic.approvalDate | SubscriptionTopic.approvalDate | Equivalent | R5 `SubscriptionTopic.approvalDate` maps as Equivalent to R4B `SubscriptionTopic.approvalDate` |
| SubscriptionTopic.canFilterBy | SubscriptionTopic.canFilterBy | Equivalent | R5 `SubscriptionTopic.canFilterBy` maps as Equivalent to R4B `SubscriptionTopic.canFilterBy` |
| SubscriptionTopic.canFilterBy.comparator | - | DoesNotExistInTarget | R5 `SubscriptionTopic.canFilterBy.comparator` does not appear in the target and has no mapping for `SubscriptionTopic`. |
| SubscriptionTopic.canFilterBy.description | SubscriptionTopic.canFilterBy.description | Equivalent | R5 `SubscriptionTopic.canFilterBy.description` maps as Equivalent to R4B `SubscriptionTopic.canFilterBy.description` |
| SubscriptionTopic.canFilterBy.extension | SubscriptionTopic.canFilterBy.extension | SourceIsBroaderThanTarget | R5 `SubscriptionTopic.canFilterBy.extension` maps as SourceIsBroaderThanTarget to R4B `SubscriptionTopic.canFilterBy.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| SubscriptionTopic.canFilterBy.filterDefinition | SubscriptionTopic.canFilterBy.filterDefinition | Equivalent | R5 `SubscriptionTopic.canFilterBy.filterDefinition` maps as Equivalent to R4B `SubscriptionTopic.canFilterBy.filterDefinition` |
| SubscriptionTopic.canFilterBy.filterParameter | SubscriptionTopic.canFilterBy.filterParameter | Equivalent | R5 `SubscriptionTopic.canFilterBy.filterParameter` maps as Equivalent to R4B `SubscriptionTopic.canFilterBy.filterParameter` |
| SubscriptionTopic.canFilterBy.id | SubscriptionTopic.canFilterBy.id | Equivalent | R5 `SubscriptionTopic.canFilterBy.id` maps as Equivalent to R4B `SubscriptionTopic.canFilterBy.id` |
| SubscriptionTopic.canFilterBy.modifier | SubscriptionTopic.canFilterBy.modifier | Equivalent | R5 `SubscriptionTopic.canFilterBy.modifier` maps as Equivalent to R4B `SubscriptionTopic.canFilterBy.modifier` - modifier has compatible required binding for code type: http://hl7.org/fhir/ValueSet/search-modifier-code|5.0.0 and http://hl7.org/fhir/ValueSet/subscription-search-modifier|4.3.0 (Equivalent) |
| SubscriptionTopic.canFilterBy.modifierExtension | SubscriptionTopic.canFilterBy.modifierExtension | SourceIsBroaderThanTarget | R5 `SubscriptionTopic.canFilterBy.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `SubscriptionTopic.canFilterBy.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| SubscriptionTopic.canFilterBy.resource | SubscriptionTopic.canFilterBy.resource | Equivalent | R5 `SubscriptionTopic.canFilterBy.resource` maps as Equivalent to R4B `SubscriptionTopic.canFilterBy.resource` |
| SubscriptionTopic.contact | SubscriptionTopic.contact | Equivalent | R5 `SubscriptionTopic.contact` maps as Equivalent to R4B `SubscriptionTopic.contact` |
| SubscriptionTopic.contained | SubscriptionTopic.contained | Equivalent | R5 `SubscriptionTopic.contained` maps as Equivalent to R4B `SubscriptionTopic.contained` |
| SubscriptionTopic.copyright | SubscriptionTopic.copyright | Equivalent | R5 `SubscriptionTopic.copyright` maps as Equivalent to R4B `SubscriptionTopic.copyright` |
| SubscriptionTopic.copyrightLabel | - | DoesNotExistInTarget | R5 `SubscriptionTopic.copyrightLabel` does not appear in the target and has no mapping for `SubscriptionTopic`. |
| SubscriptionTopic.date | SubscriptionTopic.date | Equivalent | R5 `SubscriptionTopic.date` maps as Equivalent to R4B `SubscriptionTopic.date` |
| SubscriptionTopic.derivedFrom | SubscriptionTopic.derivedFrom | Equivalent | R5 `SubscriptionTopic.derivedFrom` maps as Equivalent to R4B `SubscriptionTopic.derivedFrom` |
| SubscriptionTopic.description | SubscriptionTopic.description | Equivalent | R5 `SubscriptionTopic.description` maps as Equivalent to R4B `SubscriptionTopic.description` |
| SubscriptionTopic.effectivePeriod | SubscriptionTopic.effectivePeriod | Equivalent | R5 `SubscriptionTopic.effectivePeriod` maps as Equivalent to R4B `SubscriptionTopic.effectivePeriod` |
| SubscriptionTopic.eventTrigger | SubscriptionTopic.eventTrigger | Equivalent | R5 `SubscriptionTopic.eventTrigger` maps as Equivalent to R4B `SubscriptionTopic.eventTrigger` |
| SubscriptionTopic.eventTrigger.description | SubscriptionTopic.eventTrigger.description | Equivalent | R5 `SubscriptionTopic.eventTrigger.description` maps as Equivalent to R4B `SubscriptionTopic.eventTrigger.description` |
| SubscriptionTopic.eventTrigger.event | SubscriptionTopic.eventTrigger.event | Equivalent | R5 `SubscriptionTopic.eventTrigger.event` maps as Equivalent to R4B `SubscriptionTopic.eventTrigger.event` |
| SubscriptionTopic.eventTrigger.extension | SubscriptionTopic.eventTrigger.extension | SourceIsBroaderThanTarget | R5 `SubscriptionTopic.eventTrigger.extension` maps as SourceIsBroaderThanTarget to R4B `SubscriptionTopic.eventTrigger.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| SubscriptionTopic.eventTrigger.id | SubscriptionTopic.eventTrigger.id | Equivalent | R5 `SubscriptionTopic.eventTrigger.id` maps as Equivalent to R4B `SubscriptionTopic.eventTrigger.id` |
| SubscriptionTopic.eventTrigger.modifierExtension | SubscriptionTopic.eventTrigger.modifierExtension | SourceIsBroaderThanTarget | R5 `SubscriptionTopic.eventTrigger.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `SubscriptionTopic.eventTrigger.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| SubscriptionTopic.eventTrigger.resource | SubscriptionTopic.eventTrigger.resource | Equivalent | R5 `SubscriptionTopic.eventTrigger.resource` maps as Equivalent to R4B `SubscriptionTopic.eventTrigger.resource` |
| SubscriptionTopic.experimental | SubscriptionTopic.experimental | Equivalent | R5 `SubscriptionTopic.experimental` maps as Equivalent to R4B `SubscriptionTopic.experimental` |
| SubscriptionTopic.extension | SubscriptionTopic.extension | SourceIsBroaderThanTarget | R5 `SubscriptionTopic.extension` maps as SourceIsBroaderThanTarget to R4B `SubscriptionTopic.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| SubscriptionTopic.id | SubscriptionTopic.id | Equivalent | R5 `SubscriptionTopic.id` maps as Equivalent to R4B `SubscriptionTopic.id` |
| SubscriptionTopic.identifier | SubscriptionTopic.identifier | Equivalent | R5 `SubscriptionTopic.identifier` maps as Equivalent to R4B `SubscriptionTopic.identifier` |
| SubscriptionTopic.implicitRules | SubscriptionTopic.implicitRules | Equivalent | R5 `SubscriptionTopic.implicitRules` maps as Equivalent to R4B `SubscriptionTopic.implicitRules` |
| SubscriptionTopic.jurisdiction | SubscriptionTopic.jurisdiction | Equivalent | R5 `SubscriptionTopic.jurisdiction` maps as Equivalent to R4B `SubscriptionTopic.jurisdiction` |
| SubscriptionTopic.language | SubscriptionTopic.language | RelatedTo | R5 `SubscriptionTopic.language` maps as RelatedTo to R4B `SubscriptionTopic.language` - language changed the binding strength from Required to Preferred |
| SubscriptionTopic.lastReviewDate | SubscriptionTopic.lastReviewDate | Equivalent | R5 `SubscriptionTopic.lastReviewDate` maps as Equivalent to R4B `SubscriptionTopic.lastReviewDate` |
| SubscriptionTopic.meta | SubscriptionTopic.meta | Equivalent | R5 `SubscriptionTopic.meta` maps as Equivalent to R4B `SubscriptionTopic.meta` |
| SubscriptionTopic.modifierExtension | SubscriptionTopic.modifierExtension | SourceIsBroaderThanTarget | R5 `SubscriptionTopic.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `SubscriptionTopic.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| SubscriptionTopic.name | - | DoesNotExistInTarget | R5 `SubscriptionTopic.name` does not appear in the target and has no mapping for `SubscriptionTopic`. |
| SubscriptionTopic.notificationShape | SubscriptionTopic.notificationShape | Equivalent | R5 `SubscriptionTopic.notificationShape` maps as Equivalent to R4B `SubscriptionTopic.notificationShape` |
| SubscriptionTopic.notificationShape.extension | SubscriptionTopic.notificationShape.extension | SourceIsBroaderThanTarget | R5 `SubscriptionTopic.notificationShape.extension` maps as SourceIsBroaderThanTarget to R4B `SubscriptionTopic.notificationShape.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| SubscriptionTopic.notificationShape.id | SubscriptionTopic.notificationShape.id | Equivalent | R5 `SubscriptionTopic.notificationShape.id` maps as Equivalent to R4B `SubscriptionTopic.notificationShape.id` |
| SubscriptionTopic.notificationShape.include | SubscriptionTopic.notificationShape.include | Equivalent | R5 `SubscriptionTopic.notificationShape.include` maps as Equivalent to R4B `SubscriptionTopic.notificationShape.include` |
| SubscriptionTopic.notificationShape.modifierExtension | SubscriptionTopic.notificationShape.modifierExtension | SourceIsBroaderThanTarget | R5 `SubscriptionTopic.notificationShape.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `SubscriptionTopic.notificationShape.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| SubscriptionTopic.notificationShape.resource | SubscriptionTopic.notificationShape.resource | Equivalent | R5 `SubscriptionTopic.notificationShape.resource` maps as Equivalent to R4B `SubscriptionTopic.notificationShape.resource` |
| SubscriptionTopic.notificationShape.revInclude | SubscriptionTopic.notificationShape.revInclude | Equivalent | R5 `SubscriptionTopic.notificationShape.revInclude` maps as Equivalent to R4B `SubscriptionTopic.notificationShape.revInclude` |
| SubscriptionTopic.publisher | SubscriptionTopic.publisher | Equivalent | R5 `SubscriptionTopic.publisher` maps as Equivalent to R4B `SubscriptionTopic.publisher` |
| SubscriptionTopic.purpose | SubscriptionTopic.purpose | Equivalent | R5 `SubscriptionTopic.purpose` maps as Equivalent to R4B `SubscriptionTopic.purpose` |
| SubscriptionTopic.resourceTrigger | SubscriptionTopic.resourceTrigger | Equivalent | R5 `SubscriptionTopic.resourceTrigger` maps as Equivalent to R4B `SubscriptionTopic.resourceTrigger` |
| SubscriptionTopic.resourceTrigger.description | SubscriptionTopic.resourceTrigger.description | Equivalent | R5 `SubscriptionTopic.resourceTrigger.description` maps as Equivalent to R4B `SubscriptionTopic.resourceTrigger.description` |
| SubscriptionTopic.resourceTrigger.extension | SubscriptionTopic.resourceTrigger.extension | SourceIsBroaderThanTarget | R5 `SubscriptionTopic.resourceTrigger.extension` maps as SourceIsBroaderThanTarget to R4B `SubscriptionTopic.resourceTrigger.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| SubscriptionTopic.resourceTrigger.fhirPathCriteria | SubscriptionTopic.resourceTrigger.fhirPathCriteria | Equivalent | R5 `SubscriptionTopic.resourceTrigger.fhirPathCriteria` maps as Equivalent to R4B `SubscriptionTopic.resourceTrigger.fhirPathCriteria` |
| SubscriptionTopic.resourceTrigger.id | SubscriptionTopic.resourceTrigger.id | Equivalent | R5 `SubscriptionTopic.resourceTrigger.id` maps as Equivalent to R4B `SubscriptionTopic.resourceTrigger.id` |
| SubscriptionTopic.resourceTrigger.modifierExtension | SubscriptionTopic.resourceTrigger.modifierExtension | SourceIsBroaderThanTarget | R5 `SubscriptionTopic.resourceTrigger.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `SubscriptionTopic.resourceTrigger.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| SubscriptionTopic.resourceTrigger.queryCriteria | SubscriptionTopic.resourceTrigger.queryCriteria | Equivalent | R5 `SubscriptionTopic.resourceTrigger.queryCriteria` maps as Equivalent to R4B `SubscriptionTopic.resourceTrigger.queryCriteria` |
| SubscriptionTopic.resourceTrigger.queryCriteria.current | SubscriptionTopic.resourceTrigger.queryCriteria.current | Equivalent | R5 `SubscriptionTopic.resourceTrigger.queryCriteria.current` maps as Equivalent to R4B `SubscriptionTopic.resourceTrigger.queryCriteria.current` |
| SubscriptionTopic.resourceTrigger.queryCriteria.extension | SubscriptionTopic.resourceTrigger.queryCriteria.extension | SourceIsBroaderThanTarget | R5 `SubscriptionTopic.resourceTrigger.queryCriteria.extension` maps as SourceIsBroaderThanTarget to R4B `SubscriptionTopic.resourceTrigger.queryCriteria.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| SubscriptionTopic.resourceTrigger.queryCriteria.id | SubscriptionTopic.resourceTrigger.queryCriteria.id | Equivalent | R5 `SubscriptionTopic.resourceTrigger.queryCriteria.id` maps as Equivalent to R4B `SubscriptionTopic.resourceTrigger.queryCriteria.id` |
| SubscriptionTopic.resourceTrigger.queryCriteria.modifierExtension | SubscriptionTopic.resourceTrigger.queryCriteria.modifierExtension | SourceIsBroaderThanTarget | R5 `SubscriptionTopic.resourceTrigger.queryCriteria.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `SubscriptionTopic.resourceTrigger.queryCriteria.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| SubscriptionTopic.resourceTrigger.queryCriteria.previous | SubscriptionTopic.resourceTrigger.queryCriteria.previous | Equivalent | R5 `SubscriptionTopic.resourceTrigger.queryCriteria.previous` maps as Equivalent to R4B `SubscriptionTopic.resourceTrigger.queryCriteria.previous` |
| SubscriptionTopic.resourceTrigger.queryCriteria.requireBoth | SubscriptionTopic.resourceTrigger.queryCriteria.requireBoth | Equivalent | R5 `SubscriptionTopic.resourceTrigger.queryCriteria.requireBoth` maps as Equivalent to R4B `SubscriptionTopic.resourceTrigger.queryCriteria.requireBoth` |
| SubscriptionTopic.resourceTrigger.queryCriteria.resultForCreate | SubscriptionTopic.resourceTrigger.queryCriteria.resultForCreate | Equivalent | R5 `SubscriptionTopic.resourceTrigger.queryCriteria.resultForCreate` maps as Equivalent to R4B `SubscriptionTopic.resourceTrigger.queryCriteria.resultForCreate` - resultForCreate has compatible required binding for code type: http://hl7.org/fhir/ValueSet/subscriptiontopic-cr-behavior|5.0.0 and http://hl7.org/fhir/ValueSet/subscriptiontopic-cr-behavior|4.3.0 (Equivalent) |
| SubscriptionTopic.resourceTrigger.queryCriteria.resultForDelete | SubscriptionTopic.resourceTrigger.queryCriteria.resultForDelete | Equivalent | R5 `SubscriptionTopic.resourceTrigger.queryCriteria.resultForDelete` maps as Equivalent to R4B `SubscriptionTopic.resourceTrigger.queryCriteria.resultForDelete` - resultForDelete has compatible required binding for code type: http://hl7.org/fhir/ValueSet/subscriptiontopic-cr-behavior|5.0.0 and http://hl7.org/fhir/ValueSet/subscriptiontopic-cr-behavior|4.3.0 (Equivalent) |
| SubscriptionTopic.resourceTrigger.resource | SubscriptionTopic.resourceTrigger.resource | Equivalent | R5 `SubscriptionTopic.resourceTrigger.resource` maps as Equivalent to R4B `SubscriptionTopic.resourceTrigger.resource` |
| SubscriptionTopic.resourceTrigger.supportedInteraction | SubscriptionTopic.resourceTrigger.supportedInteraction | Equivalent | R5 `SubscriptionTopic.resourceTrigger.supportedInteraction` maps as Equivalent to R4B `SubscriptionTopic.resourceTrigger.supportedInteraction` - supportedInteraction has compatible required binding for code type: http://hl7.org/fhir/ValueSet/interaction-trigger|5.0.0 and http://hl7.org/fhir/ValueSet/interaction-trigger|4.3.0 (Equivalent) |
| SubscriptionTopic.status | SubscriptionTopic.status | Equivalent | R5 `SubscriptionTopic.status` maps as Equivalent to R4B `SubscriptionTopic.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.3.0 (Equivalent) |
| SubscriptionTopic.text | SubscriptionTopic.text | Equivalent | R5 `SubscriptionTopic.text` maps as Equivalent to R4B `SubscriptionTopic.text` |
| SubscriptionTopic.title | SubscriptionTopic.title | Equivalent | R5 `SubscriptionTopic.title` maps as Equivalent to R4B `SubscriptionTopic.title` |
| SubscriptionTopic.url | SubscriptionTopic.url | Equivalent | R5 `SubscriptionTopic.url` maps as Equivalent to R4B `SubscriptionTopic.url` |
| SubscriptionTopic.useContext | SubscriptionTopic.useContext | Equivalent | R5 `SubscriptionTopic.useContext` maps as Equivalent to R4B `SubscriptionTopic.useContext` |
| SubscriptionTopic.version | SubscriptionTopic.version | Equivalent | R5 `SubscriptionTopic.version` maps as Equivalent to R4B `SubscriptionTopic.version` |
| SubscriptionTopic.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `SubscriptionTopic.versionAlgorithm[x]` does not appear in the target and has no mapping for `SubscriptionTopic`. |

