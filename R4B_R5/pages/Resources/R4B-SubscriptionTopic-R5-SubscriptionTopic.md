Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | SubscriptionTopic |  | Describes a stream of resource state changes identified by trigger criteria and annotated with labels useful to filter projections from this topic. | 67 | 44 |
| Target | SubscriptionTopic |  | Describes a stream of resource state changes identified by trigger criteria and annotated with labels useful to filter projections from this topic. | 71 | 48 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 63 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| SubscriptionTopic | SubscriptionTopic | Equivalent | R4B `SubscriptionTopic` maps as Equivalent to R5 `SubscriptionTopic` |
| SubscriptionTopic.approvalDate | SubscriptionTopic.approvalDate | Equivalent | R4B `SubscriptionTopic.approvalDate` maps as Equivalent to R5 `SubscriptionTopic.approvalDate` |
| SubscriptionTopic.canFilterBy | SubscriptionTopic.canFilterBy | Equivalent | R4B `SubscriptionTopic.canFilterBy` maps as Equivalent to R5 `SubscriptionTopic.canFilterBy` |
| SubscriptionTopic.canFilterBy.description | SubscriptionTopic.canFilterBy.description | Equivalent | R4B `SubscriptionTopic.canFilterBy.description` maps as Equivalent to R5 `SubscriptionTopic.canFilterBy.description` |
| SubscriptionTopic.canFilterBy.extension | SubscriptionTopic.canFilterBy.extension | RelatedTo | R4B `SubscriptionTopic.canFilterBy.extension` maps as RelatedTo to R5 `SubscriptionTopic.canFilterBy.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| SubscriptionTopic.canFilterBy.filterDefinition | SubscriptionTopic.canFilterBy.filterDefinition | Equivalent | R4B `SubscriptionTopic.canFilterBy.filterDefinition` maps as Equivalent to R5 `SubscriptionTopic.canFilterBy.filterDefinition` |
| SubscriptionTopic.canFilterBy.filterParameter | SubscriptionTopic.canFilterBy.filterParameter | Equivalent | R4B `SubscriptionTopic.canFilterBy.filterParameter` maps as Equivalent to R5 `SubscriptionTopic.canFilterBy.filterParameter` |
| SubscriptionTopic.canFilterBy.id | SubscriptionTopic.canFilterBy.id | Equivalent | R4B `SubscriptionTopic.canFilterBy.id` maps as Equivalent to R5 `SubscriptionTopic.canFilterBy.id` |
| SubscriptionTopic.canFilterBy.modifier | SubscriptionTopic.canFilterBy.modifier | Equivalent | R4B `SubscriptionTopic.canFilterBy.modifier` maps as Equivalent to R5 `SubscriptionTopic.canFilterBy.modifier` - modifier has compatible required binding for code type: http://hl7.org/fhir/ValueSet/subscription-search-modifier|4.3.0 and http://hl7.org/fhir/ValueSet/search-modifier-code|5.0.0 (Equivalent) |
| SubscriptionTopic.canFilterBy.modifierExtension | SubscriptionTopic.canFilterBy.modifierExtension | RelatedTo | R4B `SubscriptionTopic.canFilterBy.modifierExtension` maps as RelatedTo to R5 `SubscriptionTopic.canFilterBy.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| SubscriptionTopic.canFilterBy.resource | SubscriptionTopic.canFilterBy.resource | Equivalent | R4B `SubscriptionTopic.canFilterBy.resource` maps as Equivalent to R5 `SubscriptionTopic.canFilterBy.resource` |
| SubscriptionTopic.contact | SubscriptionTopic.contact | Equivalent | R4B `SubscriptionTopic.contact` maps as Equivalent to R5 `SubscriptionTopic.contact` |
| SubscriptionTopic.contained | SubscriptionTopic.contained | Equivalent | R4B `SubscriptionTopic.contained` maps as Equivalent to R5 `SubscriptionTopic.contained` |
| SubscriptionTopic.copyright | SubscriptionTopic.copyright | Equivalent | R4B `SubscriptionTopic.copyright` maps as Equivalent to R5 `SubscriptionTopic.copyright` |
| SubscriptionTopic.date | SubscriptionTopic.date | Equivalent | R4B `SubscriptionTopic.date` maps as Equivalent to R5 `SubscriptionTopic.date` |
| SubscriptionTopic.derivedFrom | SubscriptionTopic.derivedFrom | Equivalent | R4B `SubscriptionTopic.derivedFrom` maps as Equivalent to R5 `SubscriptionTopic.derivedFrom` |
| SubscriptionTopic.description | SubscriptionTopic.description | Equivalent | R4B `SubscriptionTopic.description` maps as Equivalent to R5 `SubscriptionTopic.description` |
| SubscriptionTopic.effectivePeriod | SubscriptionTopic.effectivePeriod | Equivalent | R4B `SubscriptionTopic.effectivePeriod` maps as Equivalent to R5 `SubscriptionTopic.effectivePeriod` |
| SubscriptionTopic.eventTrigger | SubscriptionTopic.eventTrigger | Equivalent | R4B `SubscriptionTopic.eventTrigger` maps as Equivalent to R5 `SubscriptionTopic.eventTrigger` |
| SubscriptionTopic.eventTrigger.description | SubscriptionTopic.eventTrigger.description | Equivalent | R4B `SubscriptionTopic.eventTrigger.description` maps as Equivalent to R5 `SubscriptionTopic.eventTrigger.description` |
| SubscriptionTopic.eventTrigger.event | SubscriptionTopic.eventTrigger.event | Equivalent | R4B `SubscriptionTopic.eventTrigger.event` maps as Equivalent to R5 `SubscriptionTopic.eventTrigger.event` |
| SubscriptionTopic.eventTrigger.extension | SubscriptionTopic.eventTrigger.extension | RelatedTo | R4B `SubscriptionTopic.eventTrigger.extension` maps as RelatedTo to R5 `SubscriptionTopic.eventTrigger.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| SubscriptionTopic.eventTrigger.id | SubscriptionTopic.eventTrigger.id | Equivalent | R4B `SubscriptionTopic.eventTrigger.id` maps as Equivalent to R5 `SubscriptionTopic.eventTrigger.id` |
| SubscriptionTopic.eventTrigger.modifierExtension | SubscriptionTopic.eventTrigger.modifierExtension | RelatedTo | R4B `SubscriptionTopic.eventTrigger.modifierExtension` maps as RelatedTo to R5 `SubscriptionTopic.eventTrigger.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| SubscriptionTopic.eventTrigger.resource | SubscriptionTopic.eventTrigger.resource | Equivalent | R4B `SubscriptionTopic.eventTrigger.resource` maps as Equivalent to R5 `SubscriptionTopic.eventTrigger.resource` |
| SubscriptionTopic.experimental | SubscriptionTopic.experimental | Equivalent | R4B `SubscriptionTopic.experimental` maps as Equivalent to R5 `SubscriptionTopic.experimental` |
| SubscriptionTopic.extension | SubscriptionTopic.extension | RelatedTo | R4B `SubscriptionTopic.extension` maps as RelatedTo to R5 `SubscriptionTopic.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| SubscriptionTopic.id | SubscriptionTopic.id | Equivalent | R4B `SubscriptionTopic.id` maps as Equivalent to R5 `SubscriptionTopic.id` |
| SubscriptionTopic.identifier | SubscriptionTopic.identifier | Equivalent | R4B `SubscriptionTopic.identifier` maps as Equivalent to R5 `SubscriptionTopic.identifier` |
| SubscriptionTopic.implicitRules | SubscriptionTopic.implicitRules | Equivalent | R4B `SubscriptionTopic.implicitRules` maps as Equivalent to R5 `SubscriptionTopic.implicitRules` |
| SubscriptionTopic.jurisdiction | SubscriptionTopic.jurisdiction | Equivalent | R4B `SubscriptionTopic.jurisdiction` maps as Equivalent to R5 `SubscriptionTopic.jurisdiction` |
| SubscriptionTopic.language | SubscriptionTopic.language | RelatedTo | R4B `SubscriptionTopic.language` maps as RelatedTo to R5 `SubscriptionTopic.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| SubscriptionTopic.lastReviewDate | SubscriptionTopic.lastReviewDate | Equivalent | R4B `SubscriptionTopic.lastReviewDate` maps as Equivalent to R5 `SubscriptionTopic.lastReviewDate` |
| SubscriptionTopic.meta | SubscriptionTopic.meta | Equivalent | R4B `SubscriptionTopic.meta` maps as Equivalent to R5 `SubscriptionTopic.meta` |
| SubscriptionTopic.modifierExtension | SubscriptionTopic.modifierExtension | RelatedTo | R4B `SubscriptionTopic.modifierExtension` maps as RelatedTo to R5 `SubscriptionTopic.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| SubscriptionTopic.notificationShape | SubscriptionTopic.notificationShape | Equivalent | R4B `SubscriptionTopic.notificationShape` maps as Equivalent to R5 `SubscriptionTopic.notificationShape` |
| SubscriptionTopic.notificationShape.extension | SubscriptionTopic.notificationShape.extension | RelatedTo | R4B `SubscriptionTopic.notificationShape.extension` maps as RelatedTo to R5 `SubscriptionTopic.notificationShape.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| SubscriptionTopic.notificationShape.id | SubscriptionTopic.notificationShape.id | Equivalent | R4B `SubscriptionTopic.notificationShape.id` maps as Equivalent to R5 `SubscriptionTopic.notificationShape.id` |
| SubscriptionTopic.notificationShape.include | SubscriptionTopic.notificationShape.include | Equivalent | R4B `SubscriptionTopic.notificationShape.include` maps as Equivalent to R5 `SubscriptionTopic.notificationShape.include` |
| SubscriptionTopic.notificationShape.modifierExtension | SubscriptionTopic.notificationShape.modifierExtension | RelatedTo | R4B `SubscriptionTopic.notificationShape.modifierExtension` maps as RelatedTo to R5 `SubscriptionTopic.notificationShape.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| SubscriptionTopic.notificationShape.resource | SubscriptionTopic.notificationShape.resource | Equivalent | R4B `SubscriptionTopic.notificationShape.resource` maps as Equivalent to R5 `SubscriptionTopic.notificationShape.resource` |
| SubscriptionTopic.notificationShape.revInclude | SubscriptionTopic.notificationShape.revInclude | Equivalent | R4B `SubscriptionTopic.notificationShape.revInclude` maps as Equivalent to R5 `SubscriptionTopic.notificationShape.revInclude` |
| SubscriptionTopic.publisher | SubscriptionTopic.publisher | Equivalent | R4B `SubscriptionTopic.publisher` maps as Equivalent to R5 `SubscriptionTopic.publisher` |
| SubscriptionTopic.purpose | SubscriptionTopic.purpose | Equivalent | R4B `SubscriptionTopic.purpose` maps as Equivalent to R5 `SubscriptionTopic.purpose` |
| SubscriptionTopic.resourceTrigger | SubscriptionTopic.resourceTrigger | Equivalent | R4B `SubscriptionTopic.resourceTrigger` maps as Equivalent to R5 `SubscriptionTopic.resourceTrigger` |
| SubscriptionTopic.resourceTrigger.description | SubscriptionTopic.resourceTrigger.description | Equivalent | R4B `SubscriptionTopic.resourceTrigger.description` maps as Equivalent to R5 `SubscriptionTopic.resourceTrigger.description` |
| SubscriptionTopic.resourceTrigger.extension | SubscriptionTopic.resourceTrigger.extension | RelatedTo | R4B `SubscriptionTopic.resourceTrigger.extension` maps as RelatedTo to R5 `SubscriptionTopic.resourceTrigger.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| SubscriptionTopic.resourceTrigger.fhirPathCriteria | SubscriptionTopic.resourceTrigger.fhirPathCriteria | Equivalent | R4B `SubscriptionTopic.resourceTrigger.fhirPathCriteria` maps as Equivalent to R5 `SubscriptionTopic.resourceTrigger.fhirPathCriteria` |
| SubscriptionTopic.resourceTrigger.id | SubscriptionTopic.resourceTrigger.id | Equivalent | R4B `SubscriptionTopic.resourceTrigger.id` maps as Equivalent to R5 `SubscriptionTopic.resourceTrigger.id` |
| SubscriptionTopic.resourceTrigger.modifierExtension | SubscriptionTopic.resourceTrigger.modifierExtension | RelatedTo | R4B `SubscriptionTopic.resourceTrigger.modifierExtension` maps as RelatedTo to R5 `SubscriptionTopic.resourceTrigger.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| SubscriptionTopic.resourceTrigger.queryCriteria | SubscriptionTopic.resourceTrigger.queryCriteria | Equivalent | R4B `SubscriptionTopic.resourceTrigger.queryCriteria` maps as Equivalent to R5 `SubscriptionTopic.resourceTrigger.queryCriteria` |
| SubscriptionTopic.resourceTrigger.queryCriteria.current | SubscriptionTopic.resourceTrigger.queryCriteria.current | Equivalent | R4B `SubscriptionTopic.resourceTrigger.queryCriteria.current` maps as Equivalent to R5 `SubscriptionTopic.resourceTrigger.queryCriteria.current` |
| SubscriptionTopic.resourceTrigger.queryCriteria.extension | SubscriptionTopic.resourceTrigger.queryCriteria.extension | RelatedTo | R4B `SubscriptionTopic.resourceTrigger.queryCriteria.extension` maps as RelatedTo to R5 `SubscriptionTopic.resourceTrigger.queryCriteria.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| SubscriptionTopic.resourceTrigger.queryCriteria.id | SubscriptionTopic.resourceTrigger.queryCriteria.id | Equivalent | R4B `SubscriptionTopic.resourceTrigger.queryCriteria.id` maps as Equivalent to R5 `SubscriptionTopic.resourceTrigger.queryCriteria.id` |
| SubscriptionTopic.resourceTrigger.queryCriteria.modifierExtension | SubscriptionTopic.resourceTrigger.queryCriteria.modifierExtension | RelatedTo | R4B `SubscriptionTopic.resourceTrigger.queryCriteria.modifierExtension` maps as RelatedTo to R5 `SubscriptionTopic.resourceTrigger.queryCriteria.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| SubscriptionTopic.resourceTrigger.queryCriteria.previous | SubscriptionTopic.resourceTrigger.queryCriteria.previous | Equivalent | R4B `SubscriptionTopic.resourceTrigger.queryCriteria.previous` maps as Equivalent to R5 `SubscriptionTopic.resourceTrigger.queryCriteria.previous` |
| SubscriptionTopic.resourceTrigger.queryCriteria.requireBoth | SubscriptionTopic.resourceTrigger.queryCriteria.requireBoth | Equivalent | R4B `SubscriptionTopic.resourceTrigger.queryCriteria.requireBoth` maps as Equivalent to R5 `SubscriptionTopic.resourceTrigger.queryCriteria.requireBoth` |
| SubscriptionTopic.resourceTrigger.queryCriteria.resultForCreate | SubscriptionTopic.resourceTrigger.queryCriteria.resultForCreate | Equivalent | R4B `SubscriptionTopic.resourceTrigger.queryCriteria.resultForCreate` maps as Equivalent to R5 `SubscriptionTopic.resourceTrigger.queryCriteria.resultForCreate` - resultForCreate has compatible required binding for code type: http://hl7.org/fhir/ValueSet/subscriptiontopic-cr-behavior|4.3.0 and http://hl7.org/fhir/ValueSet/subscriptiontopic-cr-behavior|5.0.0 (Equivalent) |
| SubscriptionTopic.resourceTrigger.queryCriteria.resultForDelete | SubscriptionTopic.resourceTrigger.queryCriteria.resultForDelete | Equivalent | R4B `SubscriptionTopic.resourceTrigger.queryCriteria.resultForDelete` maps as Equivalent to R5 `SubscriptionTopic.resourceTrigger.queryCriteria.resultForDelete` - resultForDelete has compatible required binding for code type: http://hl7.org/fhir/ValueSet/subscriptiontopic-cr-behavior|4.3.0 and http://hl7.org/fhir/ValueSet/subscriptiontopic-cr-behavior|5.0.0 (Equivalent) |
| SubscriptionTopic.resourceTrigger.resource | SubscriptionTopic.resourceTrigger.resource | Equivalent | R4B `SubscriptionTopic.resourceTrigger.resource` maps as Equivalent to R5 `SubscriptionTopic.resourceTrigger.resource` |
| SubscriptionTopic.resourceTrigger.supportedInteraction | SubscriptionTopic.resourceTrigger.supportedInteraction | Equivalent | R4B `SubscriptionTopic.resourceTrigger.supportedInteraction` maps as Equivalent to R5 `SubscriptionTopic.resourceTrigger.supportedInteraction` - supportedInteraction has compatible required binding for code type: http://hl7.org/fhir/ValueSet/interaction-trigger|4.3.0 and http://hl7.org/fhir/ValueSet/interaction-trigger|5.0.0 (Equivalent) |
| SubscriptionTopic.status | SubscriptionTopic.status | Equivalent | R4B `SubscriptionTopic.status` maps as Equivalent to R5 `SubscriptionTopic.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| SubscriptionTopic.text | SubscriptionTopic.text | Equivalent | R4B `SubscriptionTopic.text` maps as Equivalent to R5 `SubscriptionTopic.text` |
| SubscriptionTopic.title | SubscriptionTopic.title | Equivalent | R4B `SubscriptionTopic.title` maps as Equivalent to R5 `SubscriptionTopic.title` |
| SubscriptionTopic.url | SubscriptionTopic.url | Equivalent | R4B `SubscriptionTopic.url` maps as Equivalent to R5 `SubscriptionTopic.url` |
| SubscriptionTopic.useContext | SubscriptionTopic.useContext | Equivalent | R4B `SubscriptionTopic.useContext` maps as Equivalent to R5 `SubscriptionTopic.useContext` |
| SubscriptionTopic.version | SubscriptionTopic.version | Equivalent | R4B `SubscriptionTopic.version` maps as Equivalent to R5 `SubscriptionTopic.version` |

