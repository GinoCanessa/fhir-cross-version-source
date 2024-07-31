Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ExampleScenario |  | A walkthrough of a workflow showing the interaction between systems and the instances shared, possibly including the evolution of instances over time. | 95 | 63 |
| Target | ExampleScenario |  | Example of workflow instance. | 86 | 54 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 11 |
Equivalent | 61 |
RelatedTo | 3 |
SourceIsBroaderThanTarget | 18 |
SourceIsNarrowerThanTarget | 2 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ExampleScenario | ExampleScenario | Equivalent | R5 `ExampleScenario` maps as Equivalent to R4 `ExampleScenario` |
| ExampleScenario.actor | ExampleScenario.actor | Equivalent | R5 `ExampleScenario.actor` maps as Equivalent to R4 `ExampleScenario.actor` |
| ExampleScenario.actor.description | ExampleScenario.actor.description | Equivalent | R5 `ExampleScenario.actor.description` maps as Equivalent to R4 `ExampleScenario.actor.description` |
| ExampleScenario.actor.extension | ExampleScenario.actor.extension | SourceIsBroaderThanTarget | R5 `ExampleScenario.actor.extension` maps as SourceIsBroaderThanTarget to R4 `ExampleScenario.actor.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ExampleScenario.actor.id | ExampleScenario.actor.id | Equivalent | R5 `ExampleScenario.actor.id` maps as Equivalent to R4 `ExampleScenario.actor.id` |
| ExampleScenario.actor.key | ExampleScenario.actor.actorId | Equivalent | R5 `ExampleScenario.actor.key` maps as Equivalent to R4 `ExampleScenario.actor.actorId` |
| ExampleScenario.actor.modifierExtension | ExampleScenario.actor.modifierExtension | SourceIsBroaderThanTarget | R5 `ExampleScenario.actor.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ExampleScenario.actor.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ExampleScenario.actor.title | ExampleScenario.actor.name | Equivalent | R5 `ExampleScenario.actor.title` maps as Equivalent to R4 `ExampleScenario.actor.name` |
| ExampleScenario.actor.type | ExampleScenario.actor.type | Equivalent | R5 `ExampleScenario.actor.type` maps as Equivalent to R4 `ExampleScenario.actor.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/examplescenario-actor-type|5.0.0 and http://hl7.org/fhir/ValueSet/examplescenario-actor-type|4.0.1 (Equivalent) |
| ExampleScenario.contact | ExampleScenario.contact | Equivalent | R5 `ExampleScenario.contact` maps as Equivalent to R4 `ExampleScenario.contact` |
| ExampleScenario.contained | ExampleScenario.contained | Equivalent | R5 `ExampleScenario.contained` maps as Equivalent to R4 `ExampleScenario.contained` |
| ExampleScenario.copyright | ExampleScenario.copyright | Equivalent | R5 `ExampleScenario.copyright` maps as Equivalent to R4 `ExampleScenario.copyright` |
| ExampleScenario.copyrightLabel | - | DoesNotExistInTarget | R5 `ExampleScenario.copyrightLabel` does not appear in the target and has no mapping for `ExampleScenario`. |
| ExampleScenario.date | ExampleScenario.date | Equivalent | R5 `ExampleScenario.date` maps as Equivalent to R4 `ExampleScenario.date` |
| ExampleScenario.description | - | DoesNotExistInTarget | R5 `ExampleScenario.description` does not appear in the target and has no mapping for `ExampleScenario`. |
| ExampleScenario.experimental | ExampleScenario.experimental | Equivalent | R5 `ExampleScenario.experimental` maps as Equivalent to R4 `ExampleScenario.experimental` |
| ExampleScenario.extension | ExampleScenario.extension | SourceIsBroaderThanTarget | R5 `ExampleScenario.extension` maps as SourceIsBroaderThanTarget to R4 `ExampleScenario.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ExampleScenario.id | ExampleScenario.id | Equivalent | R5 `ExampleScenario.id` maps as Equivalent to R4 `ExampleScenario.id` |
| ExampleScenario.identifier | ExampleScenario.identifier | Equivalent | R5 `ExampleScenario.identifier` maps as Equivalent to R4 `ExampleScenario.identifier` |
| ExampleScenario.implicitRules | ExampleScenario.implicitRules | Equivalent | R5 `ExampleScenario.implicitRules` maps as Equivalent to R4 `ExampleScenario.implicitRules` |
| ExampleScenario.instance | ExampleScenario.instance | Equivalent | R5 `ExampleScenario.instance` maps as Equivalent to R4 `ExampleScenario.instance` |
| ExampleScenario.instance.containedInstance | ExampleScenario.instance.containedInstance | Equivalent | R5 `ExampleScenario.instance.containedInstance` maps as Equivalent to R4 `ExampleScenario.instance.containedInstance` |
| ExampleScenario.instance.containedInstance.extension | ExampleScenario.instance.containedInstance.extension | SourceIsBroaderThanTarget | R5 `ExampleScenario.instance.containedInstance.extension` maps as SourceIsBroaderThanTarget to R4 `ExampleScenario.instance.containedInstance.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ExampleScenario.instance.containedInstance.id | ExampleScenario.instance.containedInstance.id | Equivalent | R5 `ExampleScenario.instance.containedInstance.id` maps as Equivalent to R4 `ExampleScenario.instance.containedInstance.id` |
| ExampleScenario.instance.containedInstance.instanceReference | ExampleScenario.instance.containedInstance.resourceId | Equivalent | R5 `ExampleScenario.instance.containedInstance.instanceReference` maps as Equivalent to R4 `ExampleScenario.instance.containedInstance.resourceId` |
| ExampleScenario.instance.containedInstance.modifierExtension | ExampleScenario.instance.containedInstance.modifierExtension | SourceIsBroaderThanTarget | R5 `ExampleScenario.instance.containedInstance.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ExampleScenario.instance.containedInstance.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ExampleScenario.instance.containedInstance.versionReference | ExampleScenario.instance.containedInstance.versionId | Equivalent | R5 `ExampleScenario.instance.containedInstance.versionReference` maps as Equivalent to R4 `ExampleScenario.instance.containedInstance.versionId` |
| ExampleScenario.instance.content | - | DoesNotExistInTarget | R5 `ExampleScenario.instance.content` does not appear in the target and has no mapping for `ExampleScenario`. |
| ExampleScenario.instance.description | ExampleScenario.instance.description | Equivalent | R5 `ExampleScenario.instance.description` maps as Equivalent to R4 `ExampleScenario.instance.description` |
| ExampleScenario.instance.extension | ExampleScenario.instance.extension | SourceIsBroaderThanTarget | R5 `ExampleScenario.instance.extension` maps as SourceIsBroaderThanTarget to R4 `ExampleScenario.instance.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ExampleScenario.instance.id | ExampleScenario.instance.id | Equivalent | R5 `ExampleScenario.instance.id` maps as Equivalent to R4 `ExampleScenario.instance.id` |
| ExampleScenario.instance.key | ExampleScenario.instance.resourceId | Equivalent | R5 `ExampleScenario.instance.key` maps as Equivalent to R4 `ExampleScenario.instance.resourceId` |
| ExampleScenario.instance.modifierExtension | ExampleScenario.instance.modifierExtension | SourceIsBroaderThanTarget | R5 `ExampleScenario.instance.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ExampleScenario.instance.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ExampleScenario.instance.structureProfile[x] | - | DoesNotExistInTarget | R5 `ExampleScenario.instance.structureProfile[x]` does not appear in the target and has no mapping for `ExampleScenario`. |
| ExampleScenario.instance.structureType | ExampleScenario.instance.resourceType | RelatedTo | R5 `ExampleScenario.instance.structureType` maps as RelatedTo to R4 `ExampleScenario.instance.resourceType` - resourceType made the binding required (from Extensible) for http://hl7.org/fhir/ValueSet/resource-types|4.0.1; resourceType has change due to type change: R5 structureType Coding has no equivalent or mapped type in R4 resourceType |
| ExampleScenario.instance.structureVersion | - | DoesNotExistInTarget | R5 `ExampleScenario.instance.structureVersion` does not appear in the target and has no mapping for `ExampleScenario`. |
| ExampleScenario.instance.title | ExampleScenario.instance.name | Equivalent | R5 `ExampleScenario.instance.title` maps as Equivalent to R4 `ExampleScenario.instance.name` |
| ExampleScenario.instance.version | ExampleScenario.instance.version | Equivalent | R5 `ExampleScenario.instance.version` maps as Equivalent to R4 `ExampleScenario.instance.version` |
| ExampleScenario.instance.version.content | - | DoesNotExistInTarget | R5 `ExampleScenario.instance.version.content` does not appear in the target and has no mapping for `ExampleScenario`. |
| ExampleScenario.instance.version.description | ExampleScenario.instance.version.description | RelatedTo | R5 `ExampleScenario.instance.version.description` maps as RelatedTo to R4 `ExampleScenario.instance.version.description` - description made the element mandatory; description increased the minimum cardinality from 0 to 1 |
| ExampleScenario.instance.version.extension | ExampleScenario.instance.version.extension | SourceIsBroaderThanTarget | R5 `ExampleScenario.instance.version.extension` maps as SourceIsBroaderThanTarget to R4 `ExampleScenario.instance.version.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ExampleScenario.instance.version.id | ExampleScenario.instance.version.id | Equivalent | R5 `ExampleScenario.instance.version.id` maps as Equivalent to R4 `ExampleScenario.instance.version.id` |
| ExampleScenario.instance.version.key | ExampleScenario.instance.version.versionId | Equivalent | R5 `ExampleScenario.instance.version.key` maps as Equivalent to R4 `ExampleScenario.instance.version.versionId` |
| ExampleScenario.instance.version.modifierExtension | ExampleScenario.instance.version.modifierExtension | SourceIsBroaderThanTarget | R5 `ExampleScenario.instance.version.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ExampleScenario.instance.version.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ExampleScenario.instance.version.title | - | DoesNotExistInTarget | R5 `ExampleScenario.instance.version.title` does not appear in the target and has no mapping for `ExampleScenario`. |
| ExampleScenario.jurisdiction | ExampleScenario.jurisdiction | Equivalent | R5 `ExampleScenario.jurisdiction` maps as Equivalent to R4 `ExampleScenario.jurisdiction` |
| ExampleScenario.language | ExampleScenario.language | SourceIsNarrowerThanTarget | R5 `ExampleScenario.language` maps as SourceIsNarrowerThanTarget to R4 `ExampleScenario.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| ExampleScenario.meta | ExampleScenario.meta | Equivalent | R5 `ExampleScenario.meta` maps as Equivalent to R4 `ExampleScenario.meta` |
| ExampleScenario.modifierExtension | ExampleScenario.modifierExtension | SourceIsBroaderThanTarget | R5 `ExampleScenario.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ExampleScenario.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ExampleScenario.name | ExampleScenario.name | Equivalent | R5 `ExampleScenario.name` maps as Equivalent to R4 `ExampleScenario.name` |
| ExampleScenario.process | ExampleScenario.process | Equivalent | R5 `ExampleScenario.process` maps as Equivalent to R4 `ExampleScenario.process` |
| ExampleScenario.process.description | ExampleScenario.process.description | Equivalent | R5 `ExampleScenario.process.description` maps as Equivalent to R4 `ExampleScenario.process.description` |
| ExampleScenario.process.extension | ExampleScenario.process.extension | SourceIsBroaderThanTarget | R5 `ExampleScenario.process.extension` maps as SourceIsBroaderThanTarget to R4 `ExampleScenario.process.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ExampleScenario.process.id | ExampleScenario.process.id | Equivalent | R5 `ExampleScenario.process.id` maps as Equivalent to R4 `ExampleScenario.process.id` |
| ExampleScenario.process.modifierExtension | ExampleScenario.process.modifierExtension | SourceIsBroaderThanTarget | R5 `ExampleScenario.process.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ExampleScenario.process.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ExampleScenario.process.postConditions | ExampleScenario.process.postConditions | Equivalent | R5 `ExampleScenario.process.postConditions` maps as Equivalent to R4 `ExampleScenario.process.postConditions` |
| ExampleScenario.process.preConditions | ExampleScenario.process.preConditions | Equivalent | R5 `ExampleScenario.process.preConditions` maps as Equivalent to R4 `ExampleScenario.process.preConditions` |
| ExampleScenario.process.step | ExampleScenario.process.step | Equivalent | R5 `ExampleScenario.process.step` maps as Equivalent to R4 `ExampleScenario.process.step` |
| ExampleScenario.process.step.alternative | ExampleScenario.process.step.alternative | Equivalent | R5 `ExampleScenario.process.step.alternative` maps as Equivalent to R4 `ExampleScenario.process.step.alternative` |
| ExampleScenario.process.step.alternative.description | ExampleScenario.process.step.alternative.description | Equivalent | R5 `ExampleScenario.process.step.alternative.description` maps as Equivalent to R4 `ExampleScenario.process.step.alternative.description` |
| ExampleScenario.process.step.alternative.extension | ExampleScenario.process.step.alternative.extension | SourceIsBroaderThanTarget | R5 `ExampleScenario.process.step.alternative.extension` maps as SourceIsBroaderThanTarget to R4 `ExampleScenario.process.step.alternative.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ExampleScenario.process.step.alternative.id | ExampleScenario.process.step.alternative.id | Equivalent | R5 `ExampleScenario.process.step.alternative.id` maps as Equivalent to R4 `ExampleScenario.process.step.alternative.id` |
| ExampleScenario.process.step.alternative.modifierExtension | ExampleScenario.process.step.alternative.modifierExtension | SourceIsBroaderThanTarget | R5 `ExampleScenario.process.step.alternative.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ExampleScenario.process.step.alternative.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ExampleScenario.process.step.alternative.step | ExampleScenario.process.step.alternative.step | Equivalent | R5 `ExampleScenario.process.step.alternative.step` maps as Equivalent to R4 `ExampleScenario.process.step.alternative.step` |
| ExampleScenario.process.step.alternative.title | ExampleScenario.process.step.alternative.title | Equivalent | R5 `ExampleScenario.process.step.alternative.title` maps as Equivalent to R4 `ExampleScenario.process.step.alternative.title` |
| ExampleScenario.process.step.extension | ExampleScenario.process.step.extension | SourceIsBroaderThanTarget | R5 `ExampleScenario.process.step.extension` maps as SourceIsBroaderThanTarget to R4 `ExampleScenario.process.step.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ExampleScenario.process.step.id | ExampleScenario.process.step.id | Equivalent | R5 `ExampleScenario.process.step.id` maps as Equivalent to R4 `ExampleScenario.process.step.id` |
| ExampleScenario.process.step.modifierExtension | ExampleScenario.process.step.modifierExtension | SourceIsBroaderThanTarget | R5 `ExampleScenario.process.step.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ExampleScenario.process.step.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ExampleScenario.process.step.number | - | DoesNotExistInTarget | R5 `ExampleScenario.process.step.number` does not appear in the target and has no mapping for `ExampleScenario`. |
| ExampleScenario.process.step.operation | ExampleScenario.process.step.operation | Equivalent | R5 `ExampleScenario.process.step.operation` maps as Equivalent to R4 `ExampleScenario.process.step.operation` |
| ExampleScenario.process.step.operation.description | ExampleScenario.process.step.operation.description | Equivalent | R5 `ExampleScenario.process.step.operation.description` maps as Equivalent to R4 `ExampleScenario.process.step.operation.description` |
| ExampleScenario.process.step.operation.extension | ExampleScenario.process.step.operation.extension | SourceIsBroaderThanTarget | R5 `ExampleScenario.process.step.operation.extension` maps as SourceIsBroaderThanTarget to R4 `ExampleScenario.process.step.operation.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ExampleScenario.process.step.operation.id | ExampleScenario.process.step.operation.id | Equivalent | R5 `ExampleScenario.process.step.operation.id` maps as Equivalent to R4 `ExampleScenario.process.step.operation.id` |
| ExampleScenario.process.step.operation.initiator | ExampleScenario.process.step.operation.initiator | Equivalent | R5 `ExampleScenario.process.step.operation.initiator` maps as Equivalent to R4 `ExampleScenario.process.step.operation.initiator` |
| ExampleScenario.process.step.operation.initiatorActive | ExampleScenario.process.step.operation.initiatorActive | Equivalent | R5 `ExampleScenario.process.step.operation.initiatorActive` maps as Equivalent to R4 `ExampleScenario.process.step.operation.initiatorActive` |
| ExampleScenario.process.step.operation.modifierExtension | ExampleScenario.process.step.operation.modifierExtension | SourceIsBroaderThanTarget | R5 `ExampleScenario.process.step.operation.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ExampleScenario.process.step.operation.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ExampleScenario.process.step.operation.receiver | ExampleScenario.process.step.operation.receiver | Equivalent | R5 `ExampleScenario.process.step.operation.receiver` maps as Equivalent to R4 `ExampleScenario.process.step.operation.receiver` |
| ExampleScenario.process.step.operation.receiverActive | ExampleScenario.process.step.operation.receiverActive | Equivalent | R5 `ExampleScenario.process.step.operation.receiverActive` maps as Equivalent to R4 `ExampleScenario.process.step.operation.receiverActive` |
| ExampleScenario.process.step.operation.request | ExampleScenario.process.step.operation.request | Equivalent | R5 `ExampleScenario.process.step.operation.request` maps as Equivalent to R4 `ExampleScenario.process.step.operation.request` |
| ExampleScenario.process.step.operation.response | ExampleScenario.process.step.operation.response | Equivalent | R5 `ExampleScenario.process.step.operation.response` maps as Equivalent to R4 `ExampleScenario.process.step.operation.response` |
| ExampleScenario.process.step.operation.title | ExampleScenario.process.step.operation.name | Equivalent | R5 `ExampleScenario.process.step.operation.title` maps as Equivalent to R4 `ExampleScenario.process.step.operation.name` |
| ExampleScenario.process.step.operation.type | ExampleScenario.process.step.operation.type | RelatedTo | R5 `ExampleScenario.process.step.operation.type` maps as RelatedTo to R4 `ExampleScenario.process.step.operation.type` - type removed a binding requirement - Extensible http://hl7.org/fhir/ValueSet/testscript-operation-codes; type has change due to type change: R5 type Coding has no equivalent or mapped type in R4 type |
| ExampleScenario.process.step.pause | ExampleScenario.process.step.pause | Equivalent | R5 `ExampleScenario.process.step.pause` maps as Equivalent to R4 `ExampleScenario.process.step.pause` |
| ExampleScenario.process.step.process | ExampleScenario.process.step.process | SourceIsNarrowerThanTarget | R5 `ExampleScenario.process.step.process` maps as SourceIsNarrowerThanTarget to R4 `ExampleScenario.process.step.process` - process changed from scalar to array (max cardinality from 1 to *) |
| ExampleScenario.process.step.workflow | - | DoesNotExistInTarget | R5 `ExampleScenario.process.step.workflow` does not appear in the target and has no mapping for `ExampleScenario`. |
| ExampleScenario.process.title | ExampleScenario.process.title | Equivalent | R5 `ExampleScenario.process.title` maps as Equivalent to R4 `ExampleScenario.process.title` |
| ExampleScenario.publisher | ExampleScenario.publisher | Equivalent | R5 `ExampleScenario.publisher` maps as Equivalent to R4 `ExampleScenario.publisher` |
| ExampleScenario.purpose | ExampleScenario.purpose | Equivalent | R5 `ExampleScenario.purpose` maps as Equivalent to R4 `ExampleScenario.purpose` |
| ExampleScenario.status | ExampleScenario.status | Equivalent | R5 `ExampleScenario.status` maps as Equivalent to R4 `ExampleScenario.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.0.1 (Equivalent) |
| ExampleScenario.text | ExampleScenario.text | Equivalent | R5 `ExampleScenario.text` maps as Equivalent to R4 `ExampleScenario.text` |
| ExampleScenario.title | - | DoesNotExistInTarget | R5 `ExampleScenario.title` does not appear in the target and has no mapping for `ExampleScenario`. |
| ExampleScenario.url | ExampleScenario.url | Equivalent | R5 `ExampleScenario.url` maps as Equivalent to R4 `ExampleScenario.url` |
| ExampleScenario.useContext | ExampleScenario.useContext | Equivalent | R5 `ExampleScenario.useContext` maps as Equivalent to R4 `ExampleScenario.useContext` |
| ExampleScenario.version | ExampleScenario.version | Equivalent | R5 `ExampleScenario.version` maps as Equivalent to R4 `ExampleScenario.version` |
| ExampleScenario.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `ExampleScenario.versionAlgorithm[x]` does not appear in the target and has no mapping for `ExampleScenario`. |

