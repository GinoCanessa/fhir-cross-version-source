Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | GraphDefinition |  | A formal computable definition of a graph of resources - that is, a coherent set of resources that form a graph by following references. The Graph Definition resource defines a set and makes rules about the set. | 56 | 39 |
| Target | GraphDefinition |  | A formal computable definition of a graph of resources - that is, a coherent set of resources that form a graph by following references. The Graph Definition resource defines a set and makes rules about the set. | 49 | 32 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 25 |
Equivalent | 4 |
RelatedTo | 27 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| GraphDefinition | GraphDefinition | Equivalent | R5 `GraphDefinition` maps as Equivalent to R4 `GraphDefinition` |
| GraphDefinition.contact | GraphDefinition.contact | Equivalent | R5 `GraphDefinition.contact` maps as Equivalent to R4 `GraphDefinition.contact` |
| GraphDefinition.contained | GraphDefinition.contained | Equivalent | R5 `GraphDefinition.contained` maps as Equivalent to R4 `GraphDefinition.contained` |
| GraphDefinition.copyright | - | DoesNotExistInTarget | R5 `GraphDefinition.copyright` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.copyrightLabel | - | DoesNotExistInTarget | R5 `GraphDefinition.copyrightLabel` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.date | GraphDefinition.date | Equivalent | R5 `GraphDefinition.date` maps as Equivalent to R4 `GraphDefinition.date` |
| GraphDefinition.description | GraphDefinition.description | Equivalent | R5 `GraphDefinition.description` maps as Equivalent to R4 `GraphDefinition.description` |
| GraphDefinition.experimental | GraphDefinition.experimental | Equivalent | R5 `GraphDefinition.experimental` maps as Equivalent to R4 `GraphDefinition.experimental` |
| GraphDefinition.extension | GraphDefinition.extension | SourceIsBroaderThanTarget | R5 `GraphDefinition.extension` maps as SourceIsBroaderThanTarget to R4 `GraphDefinition.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| GraphDefinition.id | GraphDefinition.id | Equivalent | R5 `GraphDefinition.id` maps as Equivalent to R4 `GraphDefinition.id` |
| GraphDefinition.identifier | - | DoesNotExistInTarget | R5 `GraphDefinition.identifier` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.implicitRules | GraphDefinition.implicitRules | Equivalent | R5 `GraphDefinition.implicitRules` maps as Equivalent to R4 `GraphDefinition.implicitRules` |
| GraphDefinition.jurisdiction | GraphDefinition.jurisdiction | Equivalent | R5 `GraphDefinition.jurisdiction` maps as Equivalent to R4 `GraphDefinition.jurisdiction` |
| GraphDefinition.language | GraphDefinition.language | RelatedTo | R5 `GraphDefinition.language` maps as RelatedTo to R4 `GraphDefinition.language` - language changed the binding strength from Required to Preferred |
| GraphDefinition.link | GraphDefinition.link | Equivalent | R5 `GraphDefinition.link` maps as Equivalent to R4 `GraphDefinition.link` |
| GraphDefinition.link.compartment | - | DoesNotExistInTarget | R5 `GraphDefinition.link.compartment` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.compartment.code | - | DoesNotExistInTarget | R5 `GraphDefinition.link.compartment.code` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.compartment.description | - | DoesNotExistInTarget | R5 `GraphDefinition.link.compartment.description` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.compartment.expression | - | DoesNotExistInTarget | R5 `GraphDefinition.link.compartment.expression` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.compartment.extension | - | DoesNotExistInTarget | R5 `GraphDefinition.link.compartment.extension` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.compartment.id | - | DoesNotExistInTarget | R5 `GraphDefinition.link.compartment.id` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.compartment.modifierExtension | - | DoesNotExistInTarget | R5 `GraphDefinition.link.compartment.modifierExtension` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.compartment.rule | - | DoesNotExistInTarget | R5 `GraphDefinition.link.compartment.rule` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.compartment.use | - | DoesNotExistInTarget | R5 `GraphDefinition.link.compartment.use` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.description | GraphDefinition.link.description | Equivalent | R5 `GraphDefinition.link.description` maps as Equivalent to R4 `GraphDefinition.link.description` |
| GraphDefinition.link.extension | GraphDefinition.link.extension | SourceIsBroaderThanTarget | R5 `GraphDefinition.link.extension` maps as SourceIsBroaderThanTarget to R4 `GraphDefinition.link.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| GraphDefinition.link.id | GraphDefinition.link.id | Equivalent | R5 `GraphDefinition.link.id` maps as Equivalent to R4 `GraphDefinition.link.id` |
| GraphDefinition.link.max | GraphDefinition.link.max | Equivalent | R5 `GraphDefinition.link.max` maps as Equivalent to R4 `GraphDefinition.link.max` |
| GraphDefinition.link.min | GraphDefinition.link.min | Equivalent | R5 `GraphDefinition.link.min` maps as Equivalent to R4 `GraphDefinition.link.min` |
| GraphDefinition.link.modifierExtension | GraphDefinition.link.modifierExtension | SourceIsBroaderThanTarget | R5 `GraphDefinition.link.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `GraphDefinition.link.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| GraphDefinition.link.params | - | DoesNotExistInTarget | R5 `GraphDefinition.link.params` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.path | GraphDefinition.link.path | Equivalent | R5 `GraphDefinition.link.path` maps as Equivalent to R4 `GraphDefinition.link.path` |
| GraphDefinition.link.sliceName | GraphDefinition.link.sliceName | Equivalent | R5 `GraphDefinition.link.sliceName` maps as Equivalent to R4 `GraphDefinition.link.sliceName` |
| GraphDefinition.link.sourceId | - | DoesNotExistInTarget | R5 `GraphDefinition.link.sourceId` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.targetId | - | DoesNotExistInTarget | R5 `GraphDefinition.link.targetId` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.meta | GraphDefinition.meta | Equivalent | R5 `GraphDefinition.meta` maps as Equivalent to R4 `GraphDefinition.meta` |
| GraphDefinition.modifierExtension | GraphDefinition.modifierExtension | SourceIsBroaderThanTarget | R5 `GraphDefinition.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `GraphDefinition.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| GraphDefinition.name | GraphDefinition.name | Equivalent | R5 `GraphDefinition.name` maps as Equivalent to R4 `GraphDefinition.name` |
| GraphDefinition.node | - | DoesNotExistInTarget | R5 `GraphDefinition.node` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.node.description | - | DoesNotExistInTarget | R5 `GraphDefinition.node.description` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.node.extension | - | DoesNotExistInTarget | R5 `GraphDefinition.node.extension` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.node.id | - | DoesNotExistInTarget | R5 `GraphDefinition.node.id` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.node.modifierExtension | - | DoesNotExistInTarget | R5 `GraphDefinition.node.modifierExtension` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.node.nodeId | - | DoesNotExistInTarget | R5 `GraphDefinition.node.nodeId` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.node.profile | - | DoesNotExistInTarget | R5 `GraphDefinition.node.profile` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.node.type | - | DoesNotExistInTarget | R5 `GraphDefinition.node.type` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.publisher | GraphDefinition.publisher | Equivalent | R5 `GraphDefinition.publisher` maps as Equivalent to R4 `GraphDefinition.publisher` |
| GraphDefinition.purpose | GraphDefinition.purpose | Equivalent | R5 `GraphDefinition.purpose` maps as Equivalent to R4 `GraphDefinition.purpose` |
| GraphDefinition.start | GraphDefinition.start | RelatedTo | R5 `GraphDefinition.start` maps as RelatedTo to R4 `GraphDefinition.start` - start made the element mandatory; start increased the minimum cardinality from 0 to 1; start added a required binding to http://hl7.org/fhir/ValueSet/resource-types|4.0.1; start has change due to type change: R5 start id has no equivalent or mapped type in R4 start |
| GraphDefinition.status | GraphDefinition.status | Equivalent | R5 `GraphDefinition.status` maps as Equivalent to R4 `GraphDefinition.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.0.1 (Equivalent) |
| GraphDefinition.text | GraphDefinition.text | Equivalent | R5 `GraphDefinition.text` maps as Equivalent to R4 `GraphDefinition.text` |
| GraphDefinition.title | - | DoesNotExistInTarget | R5 `GraphDefinition.title` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.url | GraphDefinition.url | Equivalent | R5 `GraphDefinition.url` maps as Equivalent to R4 `GraphDefinition.url` |
| GraphDefinition.useContext | GraphDefinition.useContext | Equivalent | R5 `GraphDefinition.useContext` maps as Equivalent to R4 `GraphDefinition.useContext` |
| GraphDefinition.version | GraphDefinition.version | Equivalent | R5 `GraphDefinition.version` maps as Equivalent to R4 `GraphDefinition.version` |
| GraphDefinition.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `GraphDefinition.versionAlgorithm[x]` does not appear in the target and has no mapping for `GraphDefinition`. |

