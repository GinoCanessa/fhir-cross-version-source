Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ConceptMap |  | A statement of relationships from one set of concepts to one or more other concepts - either concepts in code systems, or data element/data element concepts, or classes in class models. | 65 | 42 |
| Target | ConceptMap |  | A statement of relationships from one set of concepts to one or more other concepts - either concepts in code systems, or data element/data element concepts, or classes in class models. | 101 | 69 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 10 |
Equivalent | 4 |
RelatedTo | 51 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ConceptMap | ConceptMap | Equivalent | R4B `ConceptMap` maps as Equivalent to R5 `ConceptMap` |
| ConceptMap.contact | ConceptMap.contact | Equivalent | R4B `ConceptMap.contact` maps as Equivalent to R5 `ConceptMap.contact` |
| ConceptMap.contained | ConceptMap.contained | Equivalent | R4B `ConceptMap.contained` maps as Equivalent to R5 `ConceptMap.contained` |
| ConceptMap.copyright | ConceptMap.copyright | Equivalent | R4B `ConceptMap.copyright` maps as Equivalent to R5 `ConceptMap.copyright` |
| ConceptMap.date | ConceptMap.date | Equivalent | R4B `ConceptMap.date` maps as Equivalent to R5 `ConceptMap.date` |
| ConceptMap.description | ConceptMap.description | Equivalent | R4B `ConceptMap.description` maps as Equivalent to R5 `ConceptMap.description` |
| ConceptMap.experimental | ConceptMap.experimental | Equivalent | R4B `ConceptMap.experimental` maps as Equivalent to R5 `ConceptMap.experimental` |
| ConceptMap.extension | ConceptMap.extension | RelatedTo | R4B `ConceptMap.extension` maps as RelatedTo to R5 `ConceptMap.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ConceptMap.group | ConceptMap.group | Equivalent | R4B `ConceptMap.group` maps as Equivalent to R5 `ConceptMap.group` |
| ConceptMap.group.element | ConceptMap.group.element | Equivalent | R4B `ConceptMap.group.element` maps as Equivalent to R5 `ConceptMap.group.element` |
| ConceptMap.group.element.code | ConceptMap.group.element.code | Equivalent | R4B `ConceptMap.group.element.code` maps as Equivalent to R5 `ConceptMap.group.element.code` |
| ConceptMap.group.element.display | ConceptMap.group.element.display | Equivalent | R4B `ConceptMap.group.element.display` maps as Equivalent to R5 `ConceptMap.group.element.display` |
| ConceptMap.group.element.extension | ConceptMap.group.element.extension | RelatedTo | R4B `ConceptMap.group.element.extension` maps as RelatedTo to R5 `ConceptMap.group.element.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ConceptMap.group.element.id | ConceptMap.group.element.id | Equivalent | R4B `ConceptMap.group.element.id` maps as Equivalent to R5 `ConceptMap.group.element.id` |
| ConceptMap.group.element.modifierExtension | ConceptMap.group.element.modifierExtension | RelatedTo | R4B `ConceptMap.group.element.modifierExtension` maps as RelatedTo to R5 `ConceptMap.group.element.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ConceptMap.group.element.target | ConceptMap.group.element.target | Equivalent | R4B `ConceptMap.group.element.target` maps as Equivalent to R5 `ConceptMap.group.element.target` |
| ConceptMap.group.element.target.code | ConceptMap.group.element.target.code | Equivalent | R4B `ConceptMap.group.element.target.code` maps as Equivalent to R5 `ConceptMap.group.element.target.code` |
| ConceptMap.group.element.target.comment | ConceptMap.group.element.target.comment | Equivalent | R4B `ConceptMap.group.element.target.comment` maps as Equivalent to R5 `ConceptMap.group.element.target.comment` |
| ConceptMap.group.element.target.dependsOn | ConceptMap.group.element.target.dependsOn | Equivalent | R4B `ConceptMap.group.element.target.dependsOn` maps as Equivalent to R5 `ConceptMap.group.element.target.dependsOn` |
| ConceptMap.group.element.target.dependsOn.display | - | DoesNotExistInTarget | R4B `ConceptMap.group.element.target.dependsOn.display` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.group.element.target.dependsOn.extension | ConceptMap.group.element.target.dependsOn.extension | RelatedTo | R4B `ConceptMap.group.element.target.dependsOn.extension` maps as RelatedTo to R5 `ConceptMap.group.element.target.dependsOn.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ConceptMap.group.element.target.dependsOn.id | ConceptMap.group.element.target.dependsOn.id | Equivalent | R4B `ConceptMap.group.element.target.dependsOn.id` maps as Equivalent to R5 `ConceptMap.group.element.target.dependsOn.id` |
| ConceptMap.group.element.target.dependsOn.modifierExtension | ConceptMap.group.element.target.dependsOn.modifierExtension | RelatedTo | R4B `ConceptMap.group.element.target.dependsOn.modifierExtension` maps as RelatedTo to R5 `ConceptMap.group.element.target.dependsOn.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ConceptMap.group.element.target.dependsOn.property | - | DoesNotExistInTarget | R4B `ConceptMap.group.element.target.dependsOn.property` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.group.element.target.dependsOn.system | - | DoesNotExistInTarget | R4B `ConceptMap.group.element.target.dependsOn.system` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.group.element.target.dependsOn.value | - | DoesNotExistInTarget | R4B `ConceptMap.group.element.target.dependsOn.value` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.group.element.target.display | ConceptMap.group.element.target.display | Equivalent | R4B `ConceptMap.group.element.target.display` maps as Equivalent to R5 `ConceptMap.group.element.target.display` |
| ConceptMap.group.element.target.equivalence | - | DoesNotExistInTarget | R4B `ConceptMap.group.element.target.equivalence` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.group.element.target.extension | ConceptMap.group.element.target.extension | RelatedTo | R4B `ConceptMap.group.element.target.extension` maps as RelatedTo to R5 `ConceptMap.group.element.target.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ConceptMap.group.element.target.id | ConceptMap.group.element.target.id | Equivalent | R4B `ConceptMap.group.element.target.id` maps as Equivalent to R5 `ConceptMap.group.element.target.id` |
| ConceptMap.group.element.target.modifierExtension | ConceptMap.group.element.target.modifierExtension | RelatedTo | R4B `ConceptMap.group.element.target.modifierExtension` maps as RelatedTo to R5 `ConceptMap.group.element.target.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ConceptMap.group.element.target.product | ConceptMap.group.element.target.product | Equivalent | R4B `ConceptMap.group.element.target.product` maps as Equivalent to R5 `ConceptMap.group.element.target.product` |
| ConceptMap.group.extension | ConceptMap.group.extension | RelatedTo | R4B `ConceptMap.group.extension` maps as RelatedTo to R5 `ConceptMap.group.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ConceptMap.group.id | ConceptMap.group.id | Equivalent | R4B `ConceptMap.group.id` maps as Equivalent to R5 `ConceptMap.group.id` |
| ConceptMap.group.modifierExtension | ConceptMap.group.modifierExtension | RelatedTo | R4B `ConceptMap.group.modifierExtension` maps as RelatedTo to R5 `ConceptMap.group.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ConceptMap.group.source | ConceptMap.group.source | SourceIsBroaderThanTarget | R4B `ConceptMap.group.source` maps as SourceIsBroaderThanTarget to R5 `ConceptMap.group.source` - source has change due to type change: R4B source uri has no equivalent or mapped type in R5 source |
| ConceptMap.group.sourceVersion | - | DoesNotExistInTarget | R4B `ConceptMap.group.sourceVersion` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.group.target | ConceptMap.group.target | SourceIsBroaderThanTarget | R4B `ConceptMap.group.target` maps as SourceIsBroaderThanTarget to R5 `ConceptMap.group.target` - target has change due to type change: R4B target uri has no equivalent or mapped type in R5 target |
| ConceptMap.group.targetVersion | - | DoesNotExistInTarget | R4B `ConceptMap.group.targetVersion` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.group.unmapped | ConceptMap.group.unmapped | Equivalent | R4B `ConceptMap.group.unmapped` maps as Equivalent to R5 `ConceptMap.group.unmapped` |
| ConceptMap.group.unmapped.code | ConceptMap.group.unmapped.code | Equivalent | R4B `ConceptMap.group.unmapped.code` maps as Equivalent to R5 `ConceptMap.group.unmapped.code` |
| ConceptMap.group.unmapped.display | ConceptMap.group.unmapped.display | Equivalent | R4B `ConceptMap.group.unmapped.display` maps as Equivalent to R5 `ConceptMap.group.unmapped.display` |
| ConceptMap.group.unmapped.extension | ConceptMap.group.unmapped.extension | RelatedTo | R4B `ConceptMap.group.unmapped.extension` maps as RelatedTo to R5 `ConceptMap.group.unmapped.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| ConceptMap.group.unmapped.id | ConceptMap.group.unmapped.id | Equivalent | R4B `ConceptMap.group.unmapped.id` maps as Equivalent to R5 `ConceptMap.group.unmapped.id` |
| ConceptMap.group.unmapped.mode | ConceptMap.group.unmapped.mode | SourceIsBroaderThanTarget | R4B `ConceptMap.group.unmapped.mode` maps as SourceIsBroaderThanTarget to R5 `ConceptMap.group.unmapped.mode` - mode has INCOMPATIBLE required binding for code type: http://hl7.org/fhir/ValueSet/conceptmap-unmapped-mode|4.3.0 and http://hl7.org/fhir/ValueSet/conceptmap-unmapped-mode|5.0.0 |
| ConceptMap.group.unmapped.modifierExtension | ConceptMap.group.unmapped.modifierExtension | RelatedTo | R4B `ConceptMap.group.unmapped.modifierExtension` maps as RelatedTo to R5 `ConceptMap.group.unmapped.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ConceptMap.group.unmapped.url | - | DoesNotExistInTarget | R4B `ConceptMap.group.unmapped.url` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.id | ConceptMap.id | Equivalent | R4B `ConceptMap.id` maps as Equivalent to R5 `ConceptMap.id` |
| ConceptMap.identifier | ConceptMap.identifier | RelatedTo | R4B `ConceptMap.identifier` maps as RelatedTo to R5 `ConceptMap.identifier` - identifier changed from scalar to array (max cardinality from 1 to *) |
| ConceptMap.implicitRules | ConceptMap.implicitRules | Equivalent | R4B `ConceptMap.implicitRules` maps as Equivalent to R5 `ConceptMap.implicitRules` |
| ConceptMap.jurisdiction | ConceptMap.jurisdiction | Equivalent | R4B `ConceptMap.jurisdiction` maps as Equivalent to R5 `ConceptMap.jurisdiction` |
| ConceptMap.language | ConceptMap.language | RelatedTo | R4B `ConceptMap.language` maps as RelatedTo to R5 `ConceptMap.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| ConceptMap.meta | ConceptMap.meta | Equivalent | R4B `ConceptMap.meta` maps as Equivalent to R5 `ConceptMap.meta` |
| ConceptMap.modifierExtension | ConceptMap.modifierExtension | RelatedTo | R4B `ConceptMap.modifierExtension` maps as RelatedTo to R5 `ConceptMap.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| ConceptMap.name | ConceptMap.name | Equivalent | R4B `ConceptMap.name` maps as Equivalent to R5 `ConceptMap.name` |
| ConceptMap.publisher | ConceptMap.publisher | Equivalent | R4B `ConceptMap.publisher` maps as Equivalent to R5 `ConceptMap.publisher` |
| ConceptMap.purpose | ConceptMap.purpose | Equivalent | R4B `ConceptMap.purpose` maps as Equivalent to R5 `ConceptMap.purpose` |
| ConceptMap.source[x] | - | DoesNotExistInTarget | R4B `ConceptMap.source[x]` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.status | ConceptMap.status | Equivalent | R4B `ConceptMap.status` maps as Equivalent to R5 `ConceptMap.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| ConceptMap.target[x] | - | DoesNotExistInTarget | R4B `ConceptMap.target[x]` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.text | ConceptMap.text | Equivalent | R4B `ConceptMap.text` maps as Equivalent to R5 `ConceptMap.text` |
| ConceptMap.title | ConceptMap.title | Equivalent | R4B `ConceptMap.title` maps as Equivalent to R5 `ConceptMap.title` |
| ConceptMap.url | ConceptMap.url | Equivalent | R4B `ConceptMap.url` maps as Equivalent to R5 `ConceptMap.url` |
| ConceptMap.useContext | ConceptMap.useContext | Equivalent | R4B `ConceptMap.useContext` maps as Equivalent to R5 `ConceptMap.useContext` |
| ConceptMap.version | ConceptMap.version | Equivalent | R4B `ConceptMap.version` maps as Equivalent to R5 `ConceptMap.version` |

