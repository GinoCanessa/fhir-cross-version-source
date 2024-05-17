Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | PlanDefinition |  | This resource allows for the definition of various types of plans as a sharable, consumable, and executable artifact. The resource is general enough to support the description of a broad range of clinical and non-clinical artifacts such as clinical decision support rules, order sets, protocols, and drug quality specifications. | 107 | 78 |
| Target | PlanDefinition |  | This resource allows for the definition of various types of plans as a sharable, consumable, and executable artifact. The resource is general enough to support the description of a broad range of clinical and non-clinical artifacts such as clinical decision support rules, order sets, protocols, and drug quality specifications. | 143 | 102 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 4 |
RelatedTo | 102 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| PlanDefinition | PlanDefinition | Equivalent | R4B `PlanDefinition` maps as Equivalent to R5 `PlanDefinition` |
| PlanDefinition.action | PlanDefinition.action | Equivalent | R4B `PlanDefinition.action` maps as Equivalent to R5 `PlanDefinition.action` |
| PlanDefinition.action.action | PlanDefinition.action.action | Equivalent | R4B `PlanDefinition.action.action` maps as Equivalent to R5 `PlanDefinition.action.action` |
| PlanDefinition.action.cardinalityBehavior | PlanDefinition.action.cardinalityBehavior | Equivalent | R4B `PlanDefinition.action.cardinalityBehavior` maps as Equivalent to R5 `PlanDefinition.action.cardinalityBehavior` - cardinalityBehavior has compatible required binding for code type: http://hl7.org/fhir/ValueSet/action-cardinality-behavior|4.3.0 and http://hl7.org/fhir/ValueSet/action-cardinality-behavior|5.0.0 (Equivalent) |
| PlanDefinition.action.code | PlanDefinition.action.code | RelatedTo | R4B `PlanDefinition.action.code` maps as RelatedTo to R5 `PlanDefinition.action.code` - code changed from array to scalar (max cardinality from * to 1) |
| PlanDefinition.action.condition | PlanDefinition.action.condition | Equivalent | R4B `PlanDefinition.action.condition` maps as Equivalent to R5 `PlanDefinition.action.condition` |
| PlanDefinition.action.condition.expression | PlanDefinition.action.condition.expression | SourceIsBroaderThanTarget | R4B `PlanDefinition.action.condition.expression` maps as SourceIsBroaderThanTarget to R5 `PlanDefinition.action.condition.expression` - expression has change due to type change: R4B `expression` `Expression` maps as SourceIsBroaderThanTarget for R5 `expression` |
| PlanDefinition.action.condition.extension | PlanDefinition.action.condition.extension | RelatedTo | R4B `PlanDefinition.action.condition.extension` maps as RelatedTo to R5 `PlanDefinition.action.condition.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| PlanDefinition.action.condition.id | PlanDefinition.action.condition.id | Equivalent | R4B `PlanDefinition.action.condition.id` maps as Equivalent to R5 `PlanDefinition.action.condition.id` |
| PlanDefinition.action.condition.kind | PlanDefinition.action.condition.kind | Equivalent | R4B `PlanDefinition.action.condition.kind` maps as Equivalent to R5 `PlanDefinition.action.condition.kind` - kind has compatible required binding for code type: http://hl7.org/fhir/ValueSet/action-condition-kind|4.3.0 and http://hl7.org/fhir/ValueSet/action-condition-kind|5.0.0 (Equivalent) |
| PlanDefinition.action.condition.modifierExtension | PlanDefinition.action.condition.modifierExtension | RelatedTo | R4B `PlanDefinition.action.condition.modifierExtension` maps as RelatedTo to R5 `PlanDefinition.action.condition.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| PlanDefinition.action.definition[x] | PlanDefinition.action.definition[x] | SourceIsNarrowerThanTarget | R4B `PlanDefinition.action.definition[x]` maps as SourceIsNarrowerThanTarget to R5 `PlanDefinition.action.definition[x]` - definition[x] has change due to type change: R4B `definition[x]` `canonical` maps as SourceIsNarrowerThanTarget for R5 `definition[x]` |
| PlanDefinition.action.description | PlanDefinition.action.description | SourceIsBroaderThanTarget | R4B `PlanDefinition.action.description` maps as SourceIsBroaderThanTarget to R5 `PlanDefinition.action.description` - description has change due to type change: R4B description string has no equivalent or mapped type in R5 description |
| PlanDefinition.action.documentation | PlanDefinition.action.documentation | Equivalent | R4B `PlanDefinition.action.documentation` maps as Equivalent to R5 `PlanDefinition.action.documentation` |
| PlanDefinition.action.dynamicValue | PlanDefinition.action.dynamicValue | Equivalent | R4B `PlanDefinition.action.dynamicValue` maps as Equivalent to R5 `PlanDefinition.action.dynamicValue` |
| PlanDefinition.action.dynamicValue.expression | PlanDefinition.action.dynamicValue.expression | SourceIsBroaderThanTarget | R4B `PlanDefinition.action.dynamicValue.expression` maps as SourceIsBroaderThanTarget to R5 `PlanDefinition.action.dynamicValue.expression` - expression has change due to type change: R4B `expression` `Expression` maps as SourceIsBroaderThanTarget for R5 `expression` |
| PlanDefinition.action.dynamicValue.extension | PlanDefinition.action.dynamicValue.extension | RelatedTo | R4B `PlanDefinition.action.dynamicValue.extension` maps as RelatedTo to R5 `PlanDefinition.action.dynamicValue.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| PlanDefinition.action.dynamicValue.id | PlanDefinition.action.dynamicValue.id | Equivalent | R4B `PlanDefinition.action.dynamicValue.id` maps as Equivalent to R5 `PlanDefinition.action.dynamicValue.id` |
| PlanDefinition.action.dynamicValue.modifierExtension | PlanDefinition.action.dynamicValue.modifierExtension | RelatedTo | R4B `PlanDefinition.action.dynamicValue.modifierExtension` maps as RelatedTo to R5 `PlanDefinition.action.dynamicValue.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| PlanDefinition.action.dynamicValue.path | PlanDefinition.action.dynamicValue.path | Equivalent | R4B `PlanDefinition.action.dynamicValue.path` maps as Equivalent to R5 `PlanDefinition.action.dynamicValue.path` |
| PlanDefinition.action.extension | PlanDefinition.action.extension | RelatedTo | R4B `PlanDefinition.action.extension` maps as RelatedTo to R5 `PlanDefinition.action.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| PlanDefinition.action.goalId | PlanDefinition.action.goalId | Equivalent | R4B `PlanDefinition.action.goalId` maps as Equivalent to R5 `PlanDefinition.action.goalId` |
| PlanDefinition.action.groupingBehavior | PlanDefinition.action.groupingBehavior | Equivalent | R4B `PlanDefinition.action.groupingBehavior` maps as Equivalent to R5 `PlanDefinition.action.groupingBehavior` - groupingBehavior has compatible required binding for code type: http://hl7.org/fhir/ValueSet/action-grouping-behavior|4.3.0 and http://hl7.org/fhir/ValueSet/action-grouping-behavior|5.0.0 (Equivalent) |
| PlanDefinition.action.id | PlanDefinition.action.id | Equivalent | R4B `PlanDefinition.action.id` maps as Equivalent to R5 `PlanDefinition.action.id` |
| PlanDefinition.action.input | PlanDefinition.action.input | SourceIsBroaderThanTarget | R4B `PlanDefinition.action.input` maps as SourceIsBroaderThanTarget to R5 `PlanDefinition.action.input` - input has change due to type change: R4B input DataRequirement has no equivalent or mapped type in R5 input |
| PlanDefinition.action.modifierExtension | PlanDefinition.action.modifierExtension | RelatedTo | R4B `PlanDefinition.action.modifierExtension` maps as RelatedTo to R5 `PlanDefinition.action.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| PlanDefinition.action.output | PlanDefinition.action.output | SourceIsBroaderThanTarget | R4B `PlanDefinition.action.output` maps as SourceIsBroaderThanTarget to R5 `PlanDefinition.action.output` - output has change due to type change: R4B output DataRequirement has no equivalent or mapped type in R5 output |
| PlanDefinition.action.participant | PlanDefinition.action.participant | Equivalent | R4B `PlanDefinition.action.participant` maps as Equivalent to R5 `PlanDefinition.action.participant` |
| PlanDefinition.action.participant.extension | PlanDefinition.action.participant.extension | RelatedTo | R4B `PlanDefinition.action.participant.extension` maps as RelatedTo to R5 `PlanDefinition.action.participant.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| PlanDefinition.action.participant.id | PlanDefinition.action.participant.id | Equivalent | R4B `PlanDefinition.action.participant.id` maps as Equivalent to R5 `PlanDefinition.action.participant.id` |
| PlanDefinition.action.participant.modifierExtension | PlanDefinition.action.participant.modifierExtension | RelatedTo | R4B `PlanDefinition.action.participant.modifierExtension` maps as RelatedTo to R5 `PlanDefinition.action.participant.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| PlanDefinition.action.participant.role | PlanDefinition.action.participant.role | Equivalent | R4B `PlanDefinition.action.participant.role` maps as Equivalent to R5 `PlanDefinition.action.participant.role` |
| PlanDefinition.action.participant.type | PlanDefinition.action.participant.type | Equivalent | R4B `PlanDefinition.action.participant.type` maps as Equivalent to R5 `PlanDefinition.action.participant.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/action-participant-type|4.3.0 and http://hl7.org/fhir/ValueSet/action-participant-type|5.0.0 (Equivalent) |
| PlanDefinition.action.precheckBehavior | PlanDefinition.action.precheckBehavior | Equivalent | R4B `PlanDefinition.action.precheckBehavior` maps as Equivalent to R5 `PlanDefinition.action.precheckBehavior` - precheckBehavior has compatible required binding for code type: http://hl7.org/fhir/ValueSet/action-precheck-behavior|4.3.0 and http://hl7.org/fhir/ValueSet/action-precheck-behavior|5.0.0 (Equivalent) |
| PlanDefinition.action.prefix | PlanDefinition.action.prefix | Equivalent | R4B `PlanDefinition.action.prefix` maps as Equivalent to R5 `PlanDefinition.action.prefix` |
| PlanDefinition.action.priority | PlanDefinition.action.priority | Equivalent | R4B `PlanDefinition.action.priority` maps as Equivalent to R5 `PlanDefinition.action.priority` - priority has compatible required binding for code type: http://hl7.org/fhir/ValueSet/request-priority|4.3.0 and http://hl7.org/fhir/ValueSet/request-priority|5.0.0 (Equivalent) |
| PlanDefinition.action.reason | PlanDefinition.action.reason | Equivalent | R4B `PlanDefinition.action.reason` maps as Equivalent to R5 `PlanDefinition.action.reason` |
| PlanDefinition.action.relatedAction | PlanDefinition.action.relatedAction | Equivalent | R4B `PlanDefinition.action.relatedAction` maps as Equivalent to R5 `PlanDefinition.action.relatedAction` |
| PlanDefinition.action.relatedAction.actionId | - | DoesNotExistInTarget | R4B `PlanDefinition.action.relatedAction.actionId` does not appear in the target and has no mapping for `PlanDefinition`. |
| PlanDefinition.action.relatedAction.extension | PlanDefinition.action.relatedAction.extension | RelatedTo | R4B `PlanDefinition.action.relatedAction.extension` maps as RelatedTo to R5 `PlanDefinition.action.relatedAction.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| PlanDefinition.action.relatedAction.id | PlanDefinition.action.relatedAction.id | Equivalent | R4B `PlanDefinition.action.relatedAction.id` maps as Equivalent to R5 `PlanDefinition.action.relatedAction.id` |
| PlanDefinition.action.relatedAction.modifierExtension | PlanDefinition.action.relatedAction.modifierExtension | RelatedTo | R4B `PlanDefinition.action.relatedAction.modifierExtension` maps as RelatedTo to R5 `PlanDefinition.action.relatedAction.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| PlanDefinition.action.relatedAction.offset[x] | PlanDefinition.action.relatedAction.offset[x] | Equivalent | R4B `PlanDefinition.action.relatedAction.offset[x]` maps as Equivalent to R5 `PlanDefinition.action.relatedAction.offset[x]` |
| PlanDefinition.action.relatedAction.relationship | PlanDefinition.action.relatedAction.relationship | Equivalent | R4B `PlanDefinition.action.relatedAction.relationship` maps as Equivalent to R5 `PlanDefinition.action.relatedAction.relationship` - relationship has compatible required binding for code type: http://hl7.org/fhir/ValueSet/action-relationship-type|4.3.0 and http://hl7.org/fhir/ValueSet/action-relationship-type|5.0.0 (Equivalent) |
| PlanDefinition.action.requiredBehavior | PlanDefinition.action.requiredBehavior | Equivalent | R4B `PlanDefinition.action.requiredBehavior` maps as Equivalent to R5 `PlanDefinition.action.requiredBehavior` - requiredBehavior has compatible required binding for code type: http://hl7.org/fhir/ValueSet/action-required-behavior|4.3.0 and http://hl7.org/fhir/ValueSet/action-required-behavior|5.0.0 (Equivalent) |
| PlanDefinition.action.selectionBehavior | PlanDefinition.action.selectionBehavior | Equivalent | R4B `PlanDefinition.action.selectionBehavior` maps as Equivalent to R5 `PlanDefinition.action.selectionBehavior` - selectionBehavior has compatible required binding for code type: http://hl7.org/fhir/ValueSet/action-selection-behavior|4.3.0 and http://hl7.org/fhir/ValueSet/action-selection-behavior|5.0.0 (Equivalent) |
| PlanDefinition.action.subject[x] | PlanDefinition.action.subject[x] | Equivalent | R4B `PlanDefinition.action.subject[x]` maps as Equivalent to R5 `PlanDefinition.action.subject[x]` |
| PlanDefinition.action.textEquivalent | PlanDefinition.action.textEquivalent | SourceIsBroaderThanTarget | R4B `PlanDefinition.action.textEquivalent` maps as SourceIsBroaderThanTarget to R5 `PlanDefinition.action.textEquivalent` - textEquivalent has change due to type change: R4B textEquivalent string has no equivalent or mapped type in R5 textEquivalent |
| PlanDefinition.action.timing[x] | PlanDefinition.action.timing[x] | SourceIsBroaderThanTarget | R4B `PlanDefinition.action.timing[x]` maps as SourceIsBroaderThanTarget to R5 `PlanDefinition.action.timing[x]` - timing[x] has change due to type change: R4B timing[x] dateTime has no equivalent or mapped type in R5 timing[x]; timing[x] has change due to type change: R4B timing[x] Period has no equivalent or mapped type in R5 timing[x] |
| PlanDefinition.action.title | PlanDefinition.action.title | Equivalent | R4B `PlanDefinition.action.title` maps as Equivalent to R5 `PlanDefinition.action.title` |
| PlanDefinition.action.transform | PlanDefinition.action.transform | Equivalent | R4B `PlanDefinition.action.transform` maps as Equivalent to R5 `PlanDefinition.action.transform` |
| PlanDefinition.action.trigger | PlanDefinition.action.trigger | Equivalent | R4B `PlanDefinition.action.trigger` maps as Equivalent to R5 `PlanDefinition.action.trigger` |
| PlanDefinition.action.type | PlanDefinition.action.type | Equivalent | R4B `PlanDefinition.action.type` maps as Equivalent to R5 `PlanDefinition.action.type` |
| PlanDefinition.approvalDate | PlanDefinition.approvalDate | Equivalent | R4B `PlanDefinition.approvalDate` maps as Equivalent to R5 `PlanDefinition.approvalDate` |
| PlanDefinition.author | PlanDefinition.author | Equivalent | R4B `PlanDefinition.author` maps as Equivalent to R5 `PlanDefinition.author` |
| PlanDefinition.contact | PlanDefinition.contact | Equivalent | R4B `PlanDefinition.contact` maps as Equivalent to R5 `PlanDefinition.contact` |
| PlanDefinition.contained | PlanDefinition.contained | Equivalent | R4B `PlanDefinition.contained` maps as Equivalent to R5 `PlanDefinition.contained` |
| PlanDefinition.copyright | PlanDefinition.copyright | Equivalent | R4B `PlanDefinition.copyright` maps as Equivalent to R5 `PlanDefinition.copyright` |
| PlanDefinition.date | PlanDefinition.date | Equivalent | R4B `PlanDefinition.date` maps as Equivalent to R5 `PlanDefinition.date` |
| PlanDefinition.description | PlanDefinition.description | Equivalent | R4B `PlanDefinition.description` maps as Equivalent to R5 `PlanDefinition.description` |
| PlanDefinition.editor | PlanDefinition.editor | Equivalent | R4B `PlanDefinition.editor` maps as Equivalent to R5 `PlanDefinition.editor` |
| PlanDefinition.effectivePeriod | PlanDefinition.effectivePeriod | Equivalent | R4B `PlanDefinition.effectivePeriod` maps as Equivalent to R5 `PlanDefinition.effectivePeriod` |
| PlanDefinition.endorser | PlanDefinition.endorser | Equivalent | R4B `PlanDefinition.endorser` maps as Equivalent to R5 `PlanDefinition.endorser` |
| PlanDefinition.experimental | PlanDefinition.experimental | Equivalent | R4B `PlanDefinition.experimental` maps as Equivalent to R5 `PlanDefinition.experimental` |
| PlanDefinition.extension | PlanDefinition.extension | RelatedTo | R4B `PlanDefinition.extension` maps as RelatedTo to R5 `PlanDefinition.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| PlanDefinition.goal | PlanDefinition.goal | Equivalent | R4B `PlanDefinition.goal` maps as Equivalent to R5 `PlanDefinition.goal` |
| PlanDefinition.goal.addresses | PlanDefinition.goal.addresses | Equivalent | R4B `PlanDefinition.goal.addresses` maps as Equivalent to R5 `PlanDefinition.goal.addresses` |
| PlanDefinition.goal.category | PlanDefinition.goal.category | Equivalent | R4B `PlanDefinition.goal.category` maps as Equivalent to R5 `PlanDefinition.goal.category` |
| PlanDefinition.goal.description | PlanDefinition.goal.description | Equivalent | R4B `PlanDefinition.goal.description` maps as Equivalent to R5 `PlanDefinition.goal.description` |
| PlanDefinition.goal.documentation | PlanDefinition.goal.documentation | Equivalent | R4B `PlanDefinition.goal.documentation` maps as Equivalent to R5 `PlanDefinition.goal.documentation` |
| PlanDefinition.goal.extension | PlanDefinition.goal.extension | RelatedTo | R4B `PlanDefinition.goal.extension` maps as RelatedTo to R5 `PlanDefinition.goal.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| PlanDefinition.goal.id | PlanDefinition.goal.id | Equivalent | R4B `PlanDefinition.goal.id` maps as Equivalent to R5 `PlanDefinition.goal.id` |
| PlanDefinition.goal.modifierExtension | PlanDefinition.goal.modifierExtension | RelatedTo | R4B `PlanDefinition.goal.modifierExtension` maps as RelatedTo to R5 `PlanDefinition.goal.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| PlanDefinition.goal.priority | PlanDefinition.goal.priority | Equivalent | R4B `PlanDefinition.goal.priority` maps as Equivalent to R5 `PlanDefinition.goal.priority` |
| PlanDefinition.goal.start | PlanDefinition.goal.start | Equivalent | R4B `PlanDefinition.goal.start` maps as Equivalent to R5 `PlanDefinition.goal.start` |
| PlanDefinition.goal.target | PlanDefinition.goal.target | Equivalent | R4B `PlanDefinition.goal.target` maps as Equivalent to R5 `PlanDefinition.goal.target` |
| PlanDefinition.goal.target.detail[x] | PlanDefinition.goal.target.detail[x] | Equivalent | R4B `PlanDefinition.goal.target.detail[x]` maps as Equivalent to R5 `PlanDefinition.goal.target.detail[x]` |
| PlanDefinition.goal.target.due | PlanDefinition.goal.target.due | Equivalent | R4B `PlanDefinition.goal.target.due` maps as Equivalent to R5 `PlanDefinition.goal.target.due` |
| PlanDefinition.goal.target.extension | PlanDefinition.goal.target.extension | RelatedTo | R4B `PlanDefinition.goal.target.extension` maps as RelatedTo to R5 `PlanDefinition.goal.target.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| PlanDefinition.goal.target.id | PlanDefinition.goal.target.id | Equivalent | R4B `PlanDefinition.goal.target.id` maps as Equivalent to R5 `PlanDefinition.goal.target.id` |
| PlanDefinition.goal.target.measure | PlanDefinition.goal.target.measure | Equivalent | R4B `PlanDefinition.goal.target.measure` maps as Equivalent to R5 `PlanDefinition.goal.target.measure` |
| PlanDefinition.goal.target.modifierExtension | PlanDefinition.goal.target.modifierExtension | RelatedTo | R4B `PlanDefinition.goal.target.modifierExtension` maps as RelatedTo to R5 `PlanDefinition.goal.target.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| PlanDefinition.id | PlanDefinition.id | Equivalent | R4B `PlanDefinition.id` maps as Equivalent to R5 `PlanDefinition.id` |
| PlanDefinition.identifier | PlanDefinition.identifier | Equivalent | R4B `PlanDefinition.identifier` maps as Equivalent to R5 `PlanDefinition.identifier` |
| PlanDefinition.implicitRules | PlanDefinition.implicitRules | Equivalent | R4B `PlanDefinition.implicitRules` maps as Equivalent to R5 `PlanDefinition.implicitRules` |
| PlanDefinition.jurisdiction | PlanDefinition.jurisdiction | Equivalent | R4B `PlanDefinition.jurisdiction` maps as Equivalent to R5 `PlanDefinition.jurisdiction` |
| PlanDefinition.language | PlanDefinition.language | RelatedTo | R4B `PlanDefinition.language` maps as RelatedTo to R5 `PlanDefinition.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| PlanDefinition.lastReviewDate | PlanDefinition.lastReviewDate | Equivalent | R4B `PlanDefinition.lastReviewDate` maps as Equivalent to R5 `PlanDefinition.lastReviewDate` |
| PlanDefinition.library | PlanDefinition.library | Equivalent | R4B `PlanDefinition.library` maps as Equivalent to R5 `PlanDefinition.library` |
| PlanDefinition.meta | PlanDefinition.meta | Equivalent | R4B `PlanDefinition.meta` maps as Equivalent to R5 `PlanDefinition.meta` |
| PlanDefinition.modifierExtension | PlanDefinition.modifierExtension | RelatedTo | R4B `PlanDefinition.modifierExtension` maps as RelatedTo to R5 `PlanDefinition.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| PlanDefinition.name | PlanDefinition.name | Equivalent | R4B `PlanDefinition.name` maps as Equivalent to R5 `PlanDefinition.name` |
| PlanDefinition.publisher | PlanDefinition.publisher | Equivalent | R4B `PlanDefinition.publisher` maps as Equivalent to R5 `PlanDefinition.publisher` |
| PlanDefinition.purpose | PlanDefinition.purpose | Equivalent | R4B `PlanDefinition.purpose` maps as Equivalent to R5 `PlanDefinition.purpose` |
| PlanDefinition.relatedArtifact | PlanDefinition.relatedArtifact | Equivalent | R4B `PlanDefinition.relatedArtifact` maps as Equivalent to R5 `PlanDefinition.relatedArtifact` |
| PlanDefinition.reviewer | PlanDefinition.reviewer | Equivalent | R4B `PlanDefinition.reviewer` maps as Equivalent to R5 `PlanDefinition.reviewer` |
| PlanDefinition.status | PlanDefinition.status | Equivalent | R4B `PlanDefinition.status` maps as Equivalent to R5 `PlanDefinition.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| PlanDefinition.subject[x] | PlanDefinition.subject[x] | RelatedTo | R4B `PlanDefinition.subject[x]` maps as RelatedTo to R5 `PlanDefinition.subject[x]` - subject[x] has change due to type change: R4B `subject[x]` `Reference` maps as SourceIsNarrowerThanTarget for R5 `subject[x]`; subject[x] has change due to type change: R4B `subject[x]` `canonical` maps as RelatedTo for R5 `subject[x]` |
| PlanDefinition.subtitle | PlanDefinition.subtitle | Equivalent | R4B `PlanDefinition.subtitle` maps as Equivalent to R5 `PlanDefinition.subtitle` |
| PlanDefinition.text | PlanDefinition.text | Equivalent | R4B `PlanDefinition.text` maps as Equivalent to R5 `PlanDefinition.text` |
| PlanDefinition.title | PlanDefinition.title | Equivalent | R4B `PlanDefinition.title` maps as Equivalent to R5 `PlanDefinition.title` |
| PlanDefinition.topic | PlanDefinition.topic | Equivalent | R4B `PlanDefinition.topic` maps as Equivalent to R5 `PlanDefinition.topic` |
| PlanDefinition.type | PlanDefinition.type | Equivalent | R4B `PlanDefinition.type` maps as Equivalent to R5 `PlanDefinition.type` |
| PlanDefinition.url | PlanDefinition.url | Equivalent | R4B `PlanDefinition.url` maps as Equivalent to R5 `PlanDefinition.url` |
| PlanDefinition.usage | PlanDefinition.usage | SourceIsBroaderThanTarget | R4B `PlanDefinition.usage` maps as SourceIsBroaderThanTarget to R5 `PlanDefinition.usage` - usage has change due to type change: R4B usage string has no equivalent or mapped type in R5 usage |
| PlanDefinition.useContext | PlanDefinition.useContext | Equivalent | R4B `PlanDefinition.useContext` maps as Equivalent to R5 `PlanDefinition.useContext` |
| PlanDefinition.version | PlanDefinition.version | Equivalent | R4B `PlanDefinition.version` maps as Equivalent to R5 `PlanDefinition.version` |

