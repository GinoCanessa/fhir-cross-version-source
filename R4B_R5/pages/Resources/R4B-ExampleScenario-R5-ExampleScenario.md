Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ExampleScenario |  | Example of workflow instance. | 86 | 54 |
| Target | ExampleScenario |  | A walkthrough of a workflow showing the interaction between systems and the instances shared, possibly including the evolution of instances over time. | 95 | 63 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 11 |
Equivalent | 4 |
RelatedTo | 71 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ExampleScenario | ExampleScenario | Equivalent | R4B `ExampleScenario` maps as Equivalent to R5 `ExampleScenario` |
| ExampleScenario.actor | ExampleScenario.actor | Equivalent | R4B `ExampleScenario.actor` maps as Equivalent to R5 `ExampleScenario.actor` |
| ExampleScenario.actor.actorId | - | DoesNotExistInTarget | R4B `ExampleScenario.actor.actorId` does not appear in the target and has no mapping for `ExampleScenario`. |
| ExampleScenario.actor.description | ExampleScenario.actor.description | Equivalent | R4B `ExampleScenario.actor.description` maps as Equivalent to R5 `ExampleScenario.actor.description` |
| ExampleScenario.actor.extension | ExampleScenario.actor.extension | RelatedTo | R4B `ExampleScenario.actor.extension` maps as RelatedTo to R5 `ExampleScenario.actor.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ExampleScenario.actor.id | ExampleScenario.actor.id | Equivalent | R4B `ExampleScenario.actor.id` maps as Equivalent to R5 `ExampleScenario.actor.id` |
| ExampleScenario.actor.modifierExtension | ExampleScenario.actor.modifierExtension | RelatedTo | R4B `ExampleScenario.actor.modifierExtension` maps as RelatedTo to R5 `ExampleScenario.actor.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ExampleScenario.actor.name | - | DoesNotExistInTarget | R4B `ExampleScenario.actor.name` does not appear in the target and has no mapping for `ExampleScenario`. |
| ExampleScenario.actor.type | ExampleScenario.actor.type | Equivalent | R4B `ExampleScenario.actor.type` maps as Equivalent to R5 `ExampleScenario.actor.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/examplescenario-actor-type|4.3.0 and http://hl7.org/fhir/ValueSet/examplescenario-actor-type|5.0.0 (Equivalent) |
| ExampleScenario.contact | ExampleScenario.contact | Equivalent | R4B `ExampleScenario.contact` maps as Equivalent to R5 `ExampleScenario.contact` |
| ExampleScenario.contained | ExampleScenario.contained | Equivalent | R4B `ExampleScenario.contained` maps as Equivalent to R5 `ExampleScenario.contained` |
| ExampleScenario.copyright | ExampleScenario.copyright | Equivalent | R4B `ExampleScenario.copyright` maps as Equivalent to R5 `ExampleScenario.copyright` |
| ExampleScenario.date | ExampleScenario.date | Equivalent | R4B `ExampleScenario.date` maps as Equivalent to R5 `ExampleScenario.date` |
| ExampleScenario.experimental | ExampleScenario.experimental | Equivalent | R4B `ExampleScenario.experimental` maps as Equivalent to R5 `ExampleScenario.experimental` |
| ExampleScenario.extension | ExampleScenario.extension | RelatedTo | R4B `ExampleScenario.extension` maps as RelatedTo to R5 `ExampleScenario.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ExampleScenario.id | ExampleScenario.id | Equivalent | R4B `ExampleScenario.id` maps as Equivalent to R5 `ExampleScenario.id` |
| ExampleScenario.identifier | ExampleScenario.identifier | Equivalent | R4B `ExampleScenario.identifier` maps as Equivalent to R5 `ExampleScenario.identifier` |
| ExampleScenario.implicitRules | ExampleScenario.implicitRules | Equivalent | R4B `ExampleScenario.implicitRules` maps as Equivalent to R5 `ExampleScenario.implicitRules` |
| ExampleScenario.instance | ExampleScenario.instance | Equivalent | R4B `ExampleScenario.instance` maps as Equivalent to R5 `ExampleScenario.instance` |
| ExampleScenario.instance.containedInstance | ExampleScenario.instance.containedInstance | Equivalent | R4B `ExampleScenario.instance.containedInstance` maps as Equivalent to R5 `ExampleScenario.instance.containedInstance` |
| ExampleScenario.instance.containedInstance.extension | ExampleScenario.instance.containedInstance.extension | RelatedTo | R4B `ExampleScenario.instance.containedInstance.extension` maps as RelatedTo to R5 `ExampleScenario.instance.containedInstance.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ExampleScenario.instance.containedInstance.id | ExampleScenario.instance.containedInstance.id | Equivalent | R4B `ExampleScenario.instance.containedInstance.id` maps as Equivalent to R5 `ExampleScenario.instance.containedInstance.id` |
| ExampleScenario.instance.containedInstance.modifierExtension | ExampleScenario.instance.containedInstance.modifierExtension | RelatedTo | R4B `ExampleScenario.instance.containedInstance.modifierExtension` maps as RelatedTo to R5 `ExampleScenario.instance.containedInstance.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ExampleScenario.instance.containedInstance.resourceId | - | DoesNotExistInTarget | R4B `ExampleScenario.instance.containedInstance.resourceId` does not appear in the target and has no mapping for `ExampleScenario`. |
| ExampleScenario.instance.containedInstance.versionId | - | DoesNotExistInTarget | R4B `ExampleScenario.instance.containedInstance.versionId` does not appear in the target and has no mapping for `ExampleScenario`. |
| ExampleScenario.instance.description | ExampleScenario.instance.description | Equivalent | R4B `ExampleScenario.instance.description` maps as Equivalent to R5 `ExampleScenario.instance.description` |
| ExampleScenario.instance.extension | ExampleScenario.instance.extension | RelatedTo | R4B `ExampleScenario.instance.extension` maps as RelatedTo to R5 `ExampleScenario.instance.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ExampleScenario.instance.id | ExampleScenario.instance.id | Equivalent | R4B `ExampleScenario.instance.id` maps as Equivalent to R5 `ExampleScenario.instance.id` |
| ExampleScenario.instance.modifierExtension | ExampleScenario.instance.modifierExtension | RelatedTo | R4B `ExampleScenario.instance.modifierExtension` maps as RelatedTo to R5 `ExampleScenario.instance.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ExampleScenario.instance.name | - | DoesNotExistInTarget | R4B `ExampleScenario.instance.name` does not appear in the target and has no mapping for `ExampleScenario`. |
| ExampleScenario.instance.resourceId | - | DoesNotExistInTarget | R4B `ExampleScenario.instance.resourceId` does not appear in the target and has no mapping for `ExampleScenario`. |
| ExampleScenario.instance.resourceType | - | DoesNotExistInTarget | R4B `ExampleScenario.instance.resourceType` does not appear in the target and has no mapping for `ExampleScenario`. |
| ExampleScenario.instance.version | ExampleScenario.instance.version | Equivalent | R4B `ExampleScenario.instance.version` maps as Equivalent to R5 `ExampleScenario.instance.version` |
| ExampleScenario.instance.version.description | ExampleScenario.instance.version.description | Equivalent | R4B `ExampleScenario.instance.version.description` maps as Equivalent to R5 `ExampleScenario.instance.version.description` |
| ExampleScenario.instance.version.extension | ExampleScenario.instance.version.extension | RelatedTo | R4B `ExampleScenario.instance.version.extension` maps as RelatedTo to R5 `ExampleScenario.instance.version.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ExampleScenario.instance.version.id | ExampleScenario.instance.version.id | Equivalent | R4B `ExampleScenario.instance.version.id` maps as Equivalent to R5 `ExampleScenario.instance.version.id` |
| ExampleScenario.instance.version.modifierExtension | ExampleScenario.instance.version.modifierExtension | RelatedTo | R4B `ExampleScenario.instance.version.modifierExtension` maps as RelatedTo to R5 `ExampleScenario.instance.version.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ExampleScenario.instance.version.versionId | - | DoesNotExistInTarget | R4B `ExampleScenario.instance.version.versionId` does not appear in the target and has no mapping for `ExampleScenario`. |
| ExampleScenario.jurisdiction | ExampleScenario.jurisdiction | Equivalent | R4B `ExampleScenario.jurisdiction` maps as Equivalent to R5 `ExampleScenario.jurisdiction` |
| ExampleScenario.language | ExampleScenario.language | RelatedTo | R4B `ExampleScenario.language` maps as RelatedTo to R5 `ExampleScenario.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| ExampleScenario.meta | ExampleScenario.meta | Equivalent | R4B `ExampleScenario.meta` maps as Equivalent to R5 `ExampleScenario.meta` |
| ExampleScenario.modifierExtension | ExampleScenario.modifierExtension | RelatedTo | R4B `ExampleScenario.modifierExtension` maps as RelatedTo to R5 `ExampleScenario.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ExampleScenario.name | ExampleScenario.name | Equivalent | R4B `ExampleScenario.name` maps as Equivalent to R5 `ExampleScenario.name` |
| ExampleScenario.process | ExampleScenario.process | Equivalent | R4B `ExampleScenario.process` maps as Equivalent to R5 `ExampleScenario.process` |
| ExampleScenario.process.description | ExampleScenario.process.description | Equivalent | R4B `ExampleScenario.process.description` maps as Equivalent to R5 `ExampleScenario.process.description` |
| ExampleScenario.process.extension | ExampleScenario.process.extension | RelatedTo | R4B `ExampleScenario.process.extension` maps as RelatedTo to R5 `ExampleScenario.process.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ExampleScenario.process.id | ExampleScenario.process.id | Equivalent | R4B `ExampleScenario.process.id` maps as Equivalent to R5 `ExampleScenario.process.id` |
| ExampleScenario.process.modifierExtension | ExampleScenario.process.modifierExtension | RelatedTo | R4B `ExampleScenario.process.modifierExtension` maps as RelatedTo to R5 `ExampleScenario.process.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ExampleScenario.process.postConditions | ExampleScenario.process.postConditions | Equivalent | R4B `ExampleScenario.process.postConditions` maps as Equivalent to R5 `ExampleScenario.process.postConditions` |
| ExampleScenario.process.preConditions | ExampleScenario.process.preConditions | Equivalent | R4B `ExampleScenario.process.preConditions` maps as Equivalent to R5 `ExampleScenario.process.preConditions` |
| ExampleScenario.process.step | ExampleScenario.process.step | Equivalent | R4B `ExampleScenario.process.step` maps as Equivalent to R5 `ExampleScenario.process.step` |
| ExampleScenario.process.step.alternative | ExampleScenario.process.step.alternative | Equivalent | R4B `ExampleScenario.process.step.alternative` maps as Equivalent to R5 `ExampleScenario.process.step.alternative` |
| ExampleScenario.process.step.alternative.description | ExampleScenario.process.step.alternative.description | Equivalent | R4B `ExampleScenario.process.step.alternative.description` maps as Equivalent to R5 `ExampleScenario.process.step.alternative.description` |
| ExampleScenario.process.step.alternative.extension | ExampleScenario.process.step.alternative.extension | RelatedTo | R4B `ExampleScenario.process.step.alternative.extension` maps as RelatedTo to R5 `ExampleScenario.process.step.alternative.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ExampleScenario.process.step.alternative.id | ExampleScenario.process.step.alternative.id | Equivalent | R4B `ExampleScenario.process.step.alternative.id` maps as Equivalent to R5 `ExampleScenario.process.step.alternative.id` |
| ExampleScenario.process.step.alternative.modifierExtension | ExampleScenario.process.step.alternative.modifierExtension | RelatedTo | R4B `ExampleScenario.process.step.alternative.modifierExtension` maps as RelatedTo to R5 `ExampleScenario.process.step.alternative.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ExampleScenario.process.step.alternative.step | ExampleScenario.process.step.alternative.step | Equivalent | R4B `ExampleScenario.process.step.alternative.step` maps as Equivalent to R5 `ExampleScenario.process.step.alternative.step` |
| ExampleScenario.process.step.alternative.title | ExampleScenario.process.step.alternative.title | Equivalent | R4B `ExampleScenario.process.step.alternative.title` maps as Equivalent to R5 `ExampleScenario.process.step.alternative.title` |
| ExampleScenario.process.step.extension | ExampleScenario.process.step.extension | RelatedTo | R4B `ExampleScenario.process.step.extension` maps as RelatedTo to R5 `ExampleScenario.process.step.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ExampleScenario.process.step.id | ExampleScenario.process.step.id | Equivalent | R4B `ExampleScenario.process.step.id` maps as Equivalent to R5 `ExampleScenario.process.step.id` |
| ExampleScenario.process.step.modifierExtension | ExampleScenario.process.step.modifierExtension | RelatedTo | R4B `ExampleScenario.process.step.modifierExtension` maps as RelatedTo to R5 `ExampleScenario.process.step.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ExampleScenario.process.step.operation | ExampleScenario.process.step.operation | Equivalent | R4B `ExampleScenario.process.step.operation` maps as Equivalent to R5 `ExampleScenario.process.step.operation` |
| ExampleScenario.process.step.operation.description | ExampleScenario.process.step.operation.description | Equivalent | R4B `ExampleScenario.process.step.operation.description` maps as Equivalent to R5 `ExampleScenario.process.step.operation.description` |
| ExampleScenario.process.step.operation.extension | ExampleScenario.process.step.operation.extension | RelatedTo | R4B `ExampleScenario.process.step.operation.extension` maps as RelatedTo to R5 `ExampleScenario.process.step.operation.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ExampleScenario.process.step.operation.id | ExampleScenario.process.step.operation.id | Equivalent | R4B `ExampleScenario.process.step.operation.id` maps as Equivalent to R5 `ExampleScenario.process.step.operation.id` |
| ExampleScenario.process.step.operation.initiator | ExampleScenario.process.step.operation.initiator | Equivalent | R4B `ExampleScenario.process.step.operation.initiator` maps as Equivalent to R5 `ExampleScenario.process.step.operation.initiator` |
| ExampleScenario.process.step.operation.initiatorActive | ExampleScenario.process.step.operation.initiatorActive | Equivalent | R4B `ExampleScenario.process.step.operation.initiatorActive` maps as Equivalent to R5 `ExampleScenario.process.step.operation.initiatorActive` |
| ExampleScenario.process.step.operation.modifierExtension | ExampleScenario.process.step.operation.modifierExtension | RelatedTo | R4B `ExampleScenario.process.step.operation.modifierExtension` maps as RelatedTo to R5 `ExampleScenario.process.step.operation.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ExampleScenario.process.step.operation.name | - | DoesNotExistInTarget | R4B `ExampleScenario.process.step.operation.name` does not appear in the target and has no mapping for `ExampleScenario`. |
| ExampleScenario.process.step.operation.number | - | DoesNotExistInTarget | R4B `ExampleScenario.process.step.operation.number` does not appear in the target and has no mapping for `ExampleScenario`. |
| ExampleScenario.process.step.operation.receiver | ExampleScenario.process.step.operation.receiver | Equivalent | R4B `ExampleScenario.process.step.operation.receiver` maps as Equivalent to R5 `ExampleScenario.process.step.operation.receiver` |
| ExampleScenario.process.step.operation.receiverActive | ExampleScenario.process.step.operation.receiverActive | Equivalent | R4B `ExampleScenario.process.step.operation.receiverActive` maps as Equivalent to R5 `ExampleScenario.process.step.operation.receiverActive` |
| ExampleScenario.process.step.operation.request | ExampleScenario.process.step.operation.request | Equivalent | R4B `ExampleScenario.process.step.operation.request` maps as Equivalent to R5 `ExampleScenario.process.step.operation.request` |
| ExampleScenario.process.step.operation.response | ExampleScenario.process.step.operation.response | Equivalent | R4B `ExampleScenario.process.step.operation.response` maps as Equivalent to R5 `ExampleScenario.process.step.operation.response` |
| ExampleScenario.process.step.operation.type | ExampleScenario.process.step.operation.type | RelatedTo | R4B `ExampleScenario.process.step.operation.type` maps as RelatedTo to R5 `ExampleScenario.process.step.operation.type` - type added a binding requirement - Extensible http://hl7.org/fhir/ValueSet/testscript-operation-codes; type has change due to type change: R4B type string has no equivalent or mapped type in R5 type |
| ExampleScenario.process.step.pause | ExampleScenario.process.step.pause | Equivalent | R4B `ExampleScenario.process.step.pause` maps as Equivalent to R5 `ExampleScenario.process.step.pause` |
| ExampleScenario.process.step.process | ExampleScenario.process.step.process | RelatedTo | R4B `ExampleScenario.process.step.process` maps as RelatedTo to R5 `ExampleScenario.process.step.process` - process changed from array to scalar (max cardinality from * to 1) |
| ExampleScenario.process.title | ExampleScenario.process.title | Equivalent | R4B `ExampleScenario.process.title` maps as Equivalent to R5 `ExampleScenario.process.title` |
| ExampleScenario.publisher | ExampleScenario.publisher | Equivalent | R4B `ExampleScenario.publisher` maps as Equivalent to R5 `ExampleScenario.publisher` |
| ExampleScenario.purpose | ExampleScenario.purpose | Equivalent | R4B `ExampleScenario.purpose` maps as Equivalent to R5 `ExampleScenario.purpose` |
| ExampleScenario.status | ExampleScenario.status | Equivalent | R4B `ExampleScenario.status` maps as Equivalent to R5 `ExampleScenario.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| ExampleScenario.text | ExampleScenario.text | Equivalent | R4B `ExampleScenario.text` maps as Equivalent to R5 `ExampleScenario.text` |
| ExampleScenario.url | ExampleScenario.url | Equivalent | R4B `ExampleScenario.url` maps as Equivalent to R5 `ExampleScenario.url` |
| ExampleScenario.useContext | ExampleScenario.useContext | Equivalent | R4B `ExampleScenario.useContext` maps as Equivalent to R5 `ExampleScenario.useContext` |
| ExampleScenario.version | ExampleScenario.version | Equivalent | R4B `ExampleScenario.version` maps as Equivalent to R5 `ExampleScenario.version` |
| ExampleScenario.workflow | - | DoesNotExistInTarget | R4B `ExampleScenario.workflow` does not appear in the target and has no mapping for `ExampleScenario`. |

