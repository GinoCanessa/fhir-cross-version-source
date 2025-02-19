Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ConceptMap |  | A statement of relationships from one set of concepts to one or more other concepts - either concepts in code systems, or data element/data element concepts, or classes in class models. | 101 | 69 |
| Target | ConceptMap |  | A statement of relationships from one set of concepts to one or more other concepts - either concepts in code systems, or data element/data element concepts, or classes in class models. | 65 | 42 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 41 |
Equivalent | 42 |
RelatedTo | 1 |
SourceIsBroaderThanTarget | 16 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ConceptMap | ConceptMap | Equivalent | R5 `ConceptMap` maps as Equivalent to R4 `ConceptMap` |
| ConceptMap.additionalAttribute | - | DoesNotExistInTarget | R5 `ConceptMap.additionalAttribute` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.additionalAttribute.code | - | DoesNotExistInTarget | R5 `ConceptMap.additionalAttribute.code` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.additionalAttribute.description | - | DoesNotExistInTarget | R5 `ConceptMap.additionalAttribute.description` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.additionalAttribute.extension | - | DoesNotExistInTarget | R5 `ConceptMap.additionalAttribute.extension` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.additionalAttribute.id | - | DoesNotExistInTarget | R5 `ConceptMap.additionalAttribute.id` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.additionalAttribute.modifierExtension | - | DoesNotExistInTarget | R5 `ConceptMap.additionalAttribute.modifierExtension` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.additionalAttribute.type | - | DoesNotExistInTarget | R5 `ConceptMap.additionalAttribute.type` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.additionalAttribute.uri | - | DoesNotExistInTarget | R5 `ConceptMap.additionalAttribute.uri` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.approvalDate | - | DoesNotExistInTarget | R5 `ConceptMap.approvalDate` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.author | - | DoesNotExistInTarget | R5 `ConceptMap.author` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.contact | ConceptMap.contact | Equivalent | R5 `ConceptMap.contact` maps as Equivalent to R4 `ConceptMap.contact` |
| ConceptMap.contained | ConceptMap.contained | Equivalent | R5 `ConceptMap.contained` maps as Equivalent to R4 `ConceptMap.contained` |
| ConceptMap.copyright | ConceptMap.copyright | Equivalent | R5 `ConceptMap.copyright` maps as Equivalent to R4 `ConceptMap.copyright` |
| ConceptMap.copyrightLabel | - | DoesNotExistInTarget | R5 `ConceptMap.copyrightLabel` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.date | ConceptMap.date | Equivalent | R5 `ConceptMap.date` maps as Equivalent to R4 `ConceptMap.date` |
| ConceptMap.description | ConceptMap.description | Equivalent | R5 `ConceptMap.description` maps as Equivalent to R4 `ConceptMap.description` |
| ConceptMap.editor | - | DoesNotExistInTarget | R5 `ConceptMap.editor` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.effectivePeriod | - | DoesNotExistInTarget | R5 `ConceptMap.effectivePeriod` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.endorser | - | DoesNotExistInTarget | R5 `ConceptMap.endorser` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.experimental | ConceptMap.experimental | Equivalent | R5 `ConceptMap.experimental` maps as Equivalent to R4 `ConceptMap.experimental` |
| ConceptMap.extension | ConceptMap.extension | SourceIsBroaderThanTarget | R5 `ConceptMap.extension` maps as SourceIsBroaderThanTarget to R4 `ConceptMap.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ConceptMap.group | ConceptMap.group | Equivalent | R5 `ConceptMap.group` maps as Equivalent to R4 `ConceptMap.group` |
| ConceptMap.group.element | ConceptMap.group.element | Equivalent | R5 `ConceptMap.group.element` maps as Equivalent to R4 `ConceptMap.group.element` |
| ConceptMap.group.element.code | ConceptMap.group.element.code | Equivalent | R5 `ConceptMap.group.element.code` maps as Equivalent to R4 `ConceptMap.group.element.code` |
| ConceptMap.group.element.display | ConceptMap.group.element.display | Equivalent | R5 `ConceptMap.group.element.display` maps as Equivalent to R4 `ConceptMap.group.element.display` |
| ConceptMap.group.element.extension | ConceptMap.group.element.extension | SourceIsBroaderThanTarget | R5 `ConceptMap.group.element.extension` maps as SourceIsBroaderThanTarget to R4 `ConceptMap.group.element.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ConceptMap.group.element.id | ConceptMap.group.element.id | Equivalent | R5 `ConceptMap.group.element.id` maps as Equivalent to R4 `ConceptMap.group.element.id` |
| ConceptMap.group.element.modifierExtension | ConceptMap.group.element.modifierExtension | SourceIsBroaderThanTarget | R5 `ConceptMap.group.element.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ConceptMap.group.element.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ConceptMap.group.element.noMap | - | DoesNotExistInTarget | R5 `ConceptMap.group.element.noMap` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.group.element.target | ConceptMap.group.element.target | Equivalent | R5 `ConceptMap.group.element.target` maps as Equivalent to R4 `ConceptMap.group.element.target` |
| ConceptMap.group.element.target.code | ConceptMap.group.element.target.code | Equivalent | R5 `ConceptMap.group.element.target.code` maps as Equivalent to R4 `ConceptMap.group.element.target.code` |
| ConceptMap.group.element.target.comment | ConceptMap.group.element.target.comment | Equivalent | R5 `ConceptMap.group.element.target.comment` maps as Equivalent to R4 `ConceptMap.group.element.target.comment` |
| ConceptMap.group.element.target.dependsOn | ConceptMap.group.element.target.dependsOn | Equivalent | R5 `ConceptMap.group.element.target.dependsOn` maps as Equivalent to R4 `ConceptMap.group.element.target.dependsOn` |
| ConceptMap.group.element.target.dependsOn.attribute | ConceptMap.group.element.target.dependsOn.property | SourceIsBroaderThanTarget | R5 `ConceptMap.group.element.target.dependsOn.attribute` maps as SourceIsBroaderThanTarget to R4 `ConceptMap.group.element.target.dependsOn.property` - property has change due to type change: R5 attribute code has no equivalent or mapped type in R4 property |
| ConceptMap.group.element.target.dependsOn.extension | ConceptMap.group.element.target.dependsOn.extension | SourceIsBroaderThanTarget | R5 `ConceptMap.group.element.target.dependsOn.extension` maps as SourceIsBroaderThanTarget to R4 `ConceptMap.group.element.target.dependsOn.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ConceptMap.group.element.target.dependsOn.id | ConceptMap.group.element.target.dependsOn.id | Equivalent | R5 `ConceptMap.group.element.target.dependsOn.id` maps as Equivalent to R4 `ConceptMap.group.element.target.dependsOn.id` |
| ConceptMap.group.element.target.dependsOn.modifierExtension | ConceptMap.group.element.target.dependsOn.modifierExtension | SourceIsBroaderThanTarget | R5 `ConceptMap.group.element.target.dependsOn.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ConceptMap.group.element.target.dependsOn.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ConceptMap.group.element.target.dependsOn.value[x] | ConceptMap.group.element.target.dependsOn.value | RelatedTo | R5 `ConceptMap.group.element.target.dependsOn.value[x]` maps as RelatedTo to R4 `ConceptMap.group.element.target.dependsOn.value` - value made the element mandatory; value increased the minimum cardinality from 0 to 1; value has change due to type change: R5 value[x] code has no equivalent or mapped type in R4 value; value has change due to type change: R5 value[x] Coding has no equivalent or mapped type in R4 value; value has change due to type change: R5 value[x] boolean has no equivalent or mapped type in R4 value; value has change due to type change: R5 value[x] Quantity has no equivalent or mapped type in R4 value |
| ConceptMap.group.element.target.dependsOn.valueSet | - | DoesNotExistInTarget | R5 `ConceptMap.group.element.target.dependsOn.valueSet` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.group.element.target.display | ConceptMap.group.element.target.display | Equivalent | R5 `ConceptMap.group.element.target.display` maps as Equivalent to R4 `ConceptMap.group.element.target.display` |
| ConceptMap.group.element.target.extension | ConceptMap.group.element.target.extension | SourceIsBroaderThanTarget | R5 `ConceptMap.group.element.target.extension` maps as SourceIsBroaderThanTarget to R4 `ConceptMap.group.element.target.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ConceptMap.group.element.target.id | ConceptMap.group.element.target.id | Equivalent | R5 `ConceptMap.group.element.target.id` maps as Equivalent to R4 `ConceptMap.group.element.target.id` |
| ConceptMap.group.element.target.modifierExtension | ConceptMap.group.element.target.modifierExtension | SourceIsBroaderThanTarget | R5 `ConceptMap.group.element.target.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ConceptMap.group.element.target.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ConceptMap.group.element.target.product | ConceptMap.group.element.target.product | Equivalent | R5 `ConceptMap.group.element.target.product` maps as Equivalent to R4 `ConceptMap.group.element.target.product` |
| ConceptMap.group.element.target.property | - | DoesNotExistInTarget | R5 `ConceptMap.group.element.target.property` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.group.element.target.property.code | - | DoesNotExistInTarget | R5 `ConceptMap.group.element.target.property.code` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.group.element.target.property.extension | - | DoesNotExistInTarget | R5 `ConceptMap.group.element.target.property.extension` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.group.element.target.property.id | - | DoesNotExistInTarget | R5 `ConceptMap.group.element.target.property.id` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.group.element.target.property.modifierExtension | - | DoesNotExistInTarget | R5 `ConceptMap.group.element.target.property.modifierExtension` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.group.element.target.property.value[x] | - | DoesNotExistInTarget | R5 `ConceptMap.group.element.target.property.value[x]` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.group.element.target.relationship | - | DoesNotExistInTarget | R5 `ConceptMap.group.element.target.relationship` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.group.element.target.valueSet | - | DoesNotExistInTarget | R5 `ConceptMap.group.element.target.valueSet` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.group.element.valueSet | - | DoesNotExistInTarget | R5 `ConceptMap.group.element.valueSet` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.group.extension | ConceptMap.group.extension | SourceIsBroaderThanTarget | R5 `ConceptMap.group.extension` maps as SourceIsBroaderThanTarget to R4 `ConceptMap.group.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ConceptMap.group.id | ConceptMap.group.id | Equivalent | R5 `ConceptMap.group.id` maps as Equivalent to R4 `ConceptMap.group.id` |
| ConceptMap.group.modifierExtension | ConceptMap.group.modifierExtension | SourceIsBroaderThanTarget | R5 `ConceptMap.group.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ConceptMap.group.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ConceptMap.group.source | ConceptMap.group.source | SourceIsBroaderThanTarget | R5 `ConceptMap.group.source` maps as SourceIsBroaderThanTarget to R4 `ConceptMap.group.source` - source has change due to type change: R5 source canonical has no equivalent or mapped type in R4 source |
| ConceptMap.group.target | ConceptMap.group.target | SourceIsBroaderThanTarget | R5 `ConceptMap.group.target` maps as SourceIsBroaderThanTarget to R4 `ConceptMap.group.target` - target has change due to type change: R5 target canonical has no equivalent or mapped type in R4 target |
| ConceptMap.group.unmapped | ConceptMap.group.unmapped | Equivalent | R5 `ConceptMap.group.unmapped` maps as Equivalent to R4 `ConceptMap.group.unmapped` |
| ConceptMap.group.unmapped.code | ConceptMap.group.unmapped.code | Equivalent | R5 `ConceptMap.group.unmapped.code` maps as Equivalent to R4 `ConceptMap.group.unmapped.code` |
| ConceptMap.group.unmapped.display | ConceptMap.group.unmapped.display | Equivalent | R5 `ConceptMap.group.unmapped.display` maps as Equivalent to R4 `ConceptMap.group.unmapped.display` |
| ConceptMap.group.unmapped.extension | ConceptMap.group.unmapped.extension | SourceIsBroaderThanTarget | R5 `ConceptMap.group.unmapped.extension` maps as SourceIsBroaderThanTarget to R4 `ConceptMap.group.unmapped.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| ConceptMap.group.unmapped.id | ConceptMap.group.unmapped.id | Equivalent | R5 `ConceptMap.group.unmapped.id` maps as Equivalent to R4 `ConceptMap.group.unmapped.id` |
| ConceptMap.group.unmapped.mode | ConceptMap.group.unmapped.mode | Equivalent | R5 `ConceptMap.group.unmapped.mode` maps as Equivalent to R4 `ConceptMap.group.unmapped.mode` - mode has compatible required binding for code type: http://hl7.org/fhir/ValueSet/conceptmap-unmapped-mode|5.0.0 and http://hl7.org/fhir/ValueSet/conceptmap-unmapped-mode|4.0.1 (Equivalent) |
| ConceptMap.group.unmapped.modifierExtension | ConceptMap.group.unmapped.modifierExtension | SourceIsBroaderThanTarget | R5 `ConceptMap.group.unmapped.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ConceptMap.group.unmapped.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ConceptMap.group.unmapped.otherMap | ConceptMap.group.unmapped.url | Equivalent | R5 `ConceptMap.group.unmapped.otherMap` maps as Equivalent to R4 `ConceptMap.group.unmapped.url` |
| ConceptMap.group.unmapped.relationship | - | DoesNotExistInTarget | R5 `ConceptMap.group.unmapped.relationship` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.group.unmapped.valueSet | - | DoesNotExistInTarget | R5 `ConceptMap.group.unmapped.valueSet` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.id | ConceptMap.id | Equivalent | R5 `ConceptMap.id` maps as Equivalent to R4 `ConceptMap.id` |
| ConceptMap.identifier | ConceptMap.identifier | SourceIsBroaderThanTarget | R5 `ConceptMap.identifier` maps as SourceIsBroaderThanTarget to R4 `ConceptMap.identifier` - identifier changed from array to scalar (max cardinality from * to 1) |
| ConceptMap.implicitRules | ConceptMap.implicitRules | Equivalent | R5 `ConceptMap.implicitRules` maps as Equivalent to R4 `ConceptMap.implicitRules` |
| ConceptMap.jurisdiction | ConceptMap.jurisdiction | Equivalent | R5 `ConceptMap.jurisdiction` maps as Equivalent to R4 `ConceptMap.jurisdiction` |
| ConceptMap.language | ConceptMap.language | SourceIsNarrowerThanTarget | R5 `ConceptMap.language` maps as SourceIsNarrowerThanTarget to R4 `ConceptMap.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| ConceptMap.lastReviewDate | - | DoesNotExistInTarget | R5 `ConceptMap.lastReviewDate` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.meta | ConceptMap.meta | Equivalent | R5 `ConceptMap.meta` maps as Equivalent to R4 `ConceptMap.meta` |
| ConceptMap.modifierExtension | ConceptMap.modifierExtension | SourceIsBroaderThanTarget | R5 `ConceptMap.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `ConceptMap.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| ConceptMap.name | ConceptMap.name | Equivalent | R5 `ConceptMap.name` maps as Equivalent to R4 `ConceptMap.name` |
| ConceptMap.property | - | DoesNotExistInTarget | R5 `ConceptMap.property` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.property.code | - | DoesNotExistInTarget | R5 `ConceptMap.property.code` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.property.description | - | DoesNotExistInTarget | R5 `ConceptMap.property.description` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.property.extension | - | DoesNotExistInTarget | R5 `ConceptMap.property.extension` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.property.id | - | DoesNotExistInTarget | R5 `ConceptMap.property.id` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.property.modifierExtension | - | DoesNotExistInTarget | R5 `ConceptMap.property.modifierExtension` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.property.system | - | DoesNotExistInTarget | R5 `ConceptMap.property.system` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.property.type | - | DoesNotExistInTarget | R5 `ConceptMap.property.type` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.property.uri | - | DoesNotExistInTarget | R5 `ConceptMap.property.uri` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.publisher | ConceptMap.publisher | Equivalent | R5 `ConceptMap.publisher` maps as Equivalent to R4 `ConceptMap.publisher` |
| ConceptMap.purpose | ConceptMap.purpose | Equivalent | R5 `ConceptMap.purpose` maps as Equivalent to R4 `ConceptMap.purpose` |
| ConceptMap.relatedArtifact | - | DoesNotExistInTarget | R5 `ConceptMap.relatedArtifact` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.reviewer | - | DoesNotExistInTarget | R5 `ConceptMap.reviewer` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.sourceScope[x] | ConceptMap.source[x] | Equivalent | R5 `ConceptMap.sourceScope[x]` maps as Equivalent to R4 `ConceptMap.source[x]` |
| ConceptMap.status | ConceptMap.status | Equivalent | R5 `ConceptMap.status` maps as Equivalent to R4 `ConceptMap.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.0.1 (Equivalent) |
| ConceptMap.targetScope[x] | ConceptMap.target[x] | Equivalent | R5 `ConceptMap.targetScope[x]` maps as Equivalent to R4 `ConceptMap.target[x]` |
| ConceptMap.text | ConceptMap.text | Equivalent | R5 `ConceptMap.text` maps as Equivalent to R4 `ConceptMap.text` |
| ConceptMap.title | ConceptMap.title | Equivalent | R5 `ConceptMap.title` maps as Equivalent to R4 `ConceptMap.title` |
| ConceptMap.topic | - | DoesNotExistInTarget | R5 `ConceptMap.topic` does not appear in the target and has no mapping for `ConceptMap`. |
| ConceptMap.url | ConceptMap.url | Equivalent | R5 `ConceptMap.url` maps as Equivalent to R4 `ConceptMap.url` |
| ConceptMap.useContext | ConceptMap.useContext | Equivalent | R5 `ConceptMap.useContext` maps as Equivalent to R4 `ConceptMap.useContext` |
| ConceptMap.version | ConceptMap.version | Equivalent | R5 `ConceptMap.version` maps as Equivalent to R4 `ConceptMap.version` |
| ConceptMap.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `ConceptMap.versionAlgorithm[x]` does not appear in the target and has no mapping for `ConceptMap`. |

