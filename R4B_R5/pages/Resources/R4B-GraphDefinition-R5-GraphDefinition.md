Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | GraphDefinition |  | A formal computable definition of a graph of resources - that is, a coherent set of resources that form a graph by following references. The Graph Definition resource defines a set and makes rules about the set. | 49 | 32 |
| Target | GraphDefinition |  | A formal computable definition of a graph of resources - that is, a coherent set of resources that form a graph by following references. The Graph Definition resource defines a set and makes rules about the set. | 56 | 39 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 18 |
Equivalent | 4 |
RelatedTo | 27 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| GraphDefinition | GraphDefinition | Equivalent | R4B `GraphDefinition` maps as Equivalent to R5 `GraphDefinition` |
| GraphDefinition.contact | GraphDefinition.contact | Equivalent | R4B `GraphDefinition.contact` maps as Equivalent to R5 `GraphDefinition.contact` |
| GraphDefinition.contained | GraphDefinition.contained | Equivalent | R4B `GraphDefinition.contained` maps as Equivalent to R5 `GraphDefinition.contained` |
| GraphDefinition.date | GraphDefinition.date | Equivalent | R4B `GraphDefinition.date` maps as Equivalent to R5 `GraphDefinition.date` |
| GraphDefinition.description | GraphDefinition.description | Equivalent | R4B `GraphDefinition.description` maps as Equivalent to R5 `GraphDefinition.description` |
| GraphDefinition.experimental | GraphDefinition.experimental | Equivalent | R4B `GraphDefinition.experimental` maps as Equivalent to R5 `GraphDefinition.experimental` |
| GraphDefinition.extension | GraphDefinition.extension | RelatedTo | R4B `GraphDefinition.extension` maps as RelatedTo to R5 `GraphDefinition.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| GraphDefinition.id | GraphDefinition.id | Equivalent | R4B `GraphDefinition.id` maps as Equivalent to R5 `GraphDefinition.id` |
| GraphDefinition.implicitRules | GraphDefinition.implicitRules | Equivalent | R4B `GraphDefinition.implicitRules` maps as Equivalent to R5 `GraphDefinition.implicitRules` |
| GraphDefinition.jurisdiction | GraphDefinition.jurisdiction | Equivalent | R4B `GraphDefinition.jurisdiction` maps as Equivalent to R5 `GraphDefinition.jurisdiction` |
| GraphDefinition.language | GraphDefinition.language | RelatedTo | R4B `GraphDefinition.language` maps as RelatedTo to R5 `GraphDefinition.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| GraphDefinition.link | GraphDefinition.link | Equivalent | R4B `GraphDefinition.link` maps as Equivalent to R5 `GraphDefinition.link` |
| GraphDefinition.link.description | GraphDefinition.link.description | Equivalent | R4B `GraphDefinition.link.description` maps as Equivalent to R5 `GraphDefinition.link.description` |
| GraphDefinition.link.extension | GraphDefinition.link.extension | RelatedTo | R4B `GraphDefinition.link.extension` maps as RelatedTo to R5 `GraphDefinition.link.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| GraphDefinition.link.id | GraphDefinition.link.id | Equivalent | R4B `GraphDefinition.link.id` maps as Equivalent to R5 `GraphDefinition.link.id` |
| GraphDefinition.link.max | GraphDefinition.link.max | Equivalent | R4B `GraphDefinition.link.max` maps as Equivalent to R5 `GraphDefinition.link.max` |
| GraphDefinition.link.min | GraphDefinition.link.min | Equivalent | R4B `GraphDefinition.link.min` maps as Equivalent to R5 `GraphDefinition.link.min` |
| GraphDefinition.link.modifierExtension | GraphDefinition.link.modifierExtension | RelatedTo | R4B `GraphDefinition.link.modifierExtension` maps as RelatedTo to R5 `GraphDefinition.link.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| GraphDefinition.link.path | GraphDefinition.link.path | Equivalent | R4B `GraphDefinition.link.path` maps as Equivalent to R5 `GraphDefinition.link.path` |
| GraphDefinition.link.sliceName | GraphDefinition.link.sliceName | Equivalent | R4B `GraphDefinition.link.sliceName` maps as Equivalent to R5 `GraphDefinition.link.sliceName` |
| GraphDefinition.link.target | - | DoesNotExistInTarget | R4B `GraphDefinition.link.target` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.target.compartment | - | DoesNotExistInTarget | R4B `GraphDefinition.link.target.compartment` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.target.compartment.code | - | DoesNotExistInTarget | R4B `GraphDefinition.link.target.compartment.code` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.target.compartment.description | - | DoesNotExistInTarget | R4B `GraphDefinition.link.target.compartment.description` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.target.compartment.expression | - | DoesNotExistInTarget | R4B `GraphDefinition.link.target.compartment.expression` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.target.compartment.extension | - | DoesNotExistInTarget | R4B `GraphDefinition.link.target.compartment.extension` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.target.compartment.id | - | DoesNotExistInTarget | R4B `GraphDefinition.link.target.compartment.id` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.target.compartment.modifierExtension | - | DoesNotExistInTarget | R4B `GraphDefinition.link.target.compartment.modifierExtension` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.target.compartment.rule | - | DoesNotExistInTarget | R4B `GraphDefinition.link.target.compartment.rule` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.target.compartment.use | - | DoesNotExistInTarget | R4B `GraphDefinition.link.target.compartment.use` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.target.extension | - | DoesNotExistInTarget | R4B `GraphDefinition.link.target.extension` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.target.id | - | DoesNotExistInTarget | R4B `GraphDefinition.link.target.id` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.target.link | - | DoesNotExistInTarget | R4B `GraphDefinition.link.target.link` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.target.modifierExtension | - | DoesNotExistInTarget | R4B `GraphDefinition.link.target.modifierExtension` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.target.params | - | DoesNotExistInTarget | R4B `GraphDefinition.link.target.params` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.target.profile | - | DoesNotExistInTarget | R4B `GraphDefinition.link.target.profile` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.link.target.type | - | DoesNotExistInTarget | R4B `GraphDefinition.link.target.type` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.meta | GraphDefinition.meta | Equivalent | R4B `GraphDefinition.meta` maps as Equivalent to R5 `GraphDefinition.meta` |
| GraphDefinition.modifierExtension | GraphDefinition.modifierExtension | RelatedTo | R4B `GraphDefinition.modifierExtension` maps as RelatedTo to R5 `GraphDefinition.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| GraphDefinition.name | GraphDefinition.name | Equivalent | R4B `GraphDefinition.name` maps as Equivalent to R5 `GraphDefinition.name` |
| GraphDefinition.profile | - | DoesNotExistInTarget | R4B `GraphDefinition.profile` does not appear in the target and has no mapping for `GraphDefinition`. |
| GraphDefinition.publisher | GraphDefinition.publisher | Equivalent | R4B `GraphDefinition.publisher` maps as Equivalent to R5 `GraphDefinition.publisher` |
| GraphDefinition.purpose | GraphDefinition.purpose | Equivalent | R4B `GraphDefinition.purpose` maps as Equivalent to R5 `GraphDefinition.purpose` |
| GraphDefinition.start | GraphDefinition.start | RelatedTo | R4B `GraphDefinition.start` maps as RelatedTo to R5 `GraphDefinition.start` - start removed a binding requirement - Required http://hl7.org/fhir/ValueSet/resource-types|4.3.0; start has change due to type change: R4B start code has no equivalent or mapped type in R5 start |
| GraphDefinition.status | GraphDefinition.status | Equivalent | R4B `GraphDefinition.status` maps as Equivalent to R5 `GraphDefinition.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| GraphDefinition.text | GraphDefinition.text | Equivalent | R4B `GraphDefinition.text` maps as Equivalent to R5 `GraphDefinition.text` |
| GraphDefinition.url | GraphDefinition.url | Equivalent | R4B `GraphDefinition.url` maps as Equivalent to R5 `GraphDefinition.url` |
| GraphDefinition.useContext | GraphDefinition.useContext | Equivalent | R4B `GraphDefinition.useContext` maps as Equivalent to R5 `GraphDefinition.useContext` |
| GraphDefinition.version | GraphDefinition.version | Equivalent | R4B `GraphDefinition.version` maps as Equivalent to R5 `GraphDefinition.version` |

