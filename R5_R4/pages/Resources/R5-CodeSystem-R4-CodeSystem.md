Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | CodeSystem |  | The CodeSystem resource is used to declare the existence of and describe a code system or code system supplement and its key properties, and optionally define a part or all of its content. | 81 | 58 |
| Target | CodeSystem |  | The CodeSystem resource is used to declare the existence of and describe a code system or code system supplement and its key properties, and optionally define a part or all of its content. | 69 | 46 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 12 |
Equivalent | 4 |
RelatedTo | 65 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| CodeSystem | CodeSystem | Equivalent | R5 `CodeSystem` maps as Equivalent to R4 `CodeSystem` |
| CodeSystem.approvalDate | - | DoesNotExistInTarget | R5 `CodeSystem.approvalDate` does not appear in the target and has no mapping for `CodeSystem`. |
| CodeSystem.author | - | DoesNotExistInTarget | R5 `CodeSystem.author` does not appear in the target and has no mapping for `CodeSystem`. |
| CodeSystem.caseSensitive | CodeSystem.caseSensitive | Equivalent | R5 `CodeSystem.caseSensitive` maps as Equivalent to R4 `CodeSystem.caseSensitive` |
| CodeSystem.compositional | CodeSystem.compositional | Equivalent | R5 `CodeSystem.compositional` maps as Equivalent to R4 `CodeSystem.compositional` |
| CodeSystem.concept | CodeSystem.concept | Equivalent | R5 `CodeSystem.concept` maps as Equivalent to R4 `CodeSystem.concept` |
| CodeSystem.concept.code | CodeSystem.concept.code | Equivalent | R5 `CodeSystem.concept.code` maps as Equivalent to R4 `CodeSystem.concept.code` |
| CodeSystem.concept.concept | CodeSystem.concept.concept | Equivalent | R5 `CodeSystem.concept.concept` maps as Equivalent to R4 `CodeSystem.concept.concept` |
| CodeSystem.concept.definition | CodeSystem.concept.definition | Equivalent | R5 `CodeSystem.concept.definition` maps as Equivalent to R4 `CodeSystem.concept.definition` |
| CodeSystem.concept.designation | CodeSystem.concept.designation | Equivalent | R5 `CodeSystem.concept.designation` maps as Equivalent to R4 `CodeSystem.concept.designation` |
| CodeSystem.concept.designation.additionalUse | - | DoesNotExistInTarget | R5 `CodeSystem.concept.designation.additionalUse` does not appear in the target and has no mapping for `CodeSystem`. |
| CodeSystem.concept.designation.extension | CodeSystem.concept.designation.extension | SourceIsBroaderThanTarget | R5 `CodeSystem.concept.designation.extension` maps as SourceIsBroaderThanTarget to R4 `CodeSystem.concept.designation.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| CodeSystem.concept.designation.id | CodeSystem.concept.designation.id | Equivalent | R5 `CodeSystem.concept.designation.id` maps as Equivalent to R4 `CodeSystem.concept.designation.id` |
| CodeSystem.concept.designation.language | CodeSystem.concept.designation.language | RelatedTo | R5 `CodeSystem.concept.designation.language` maps as RelatedTo to R4 `CodeSystem.concept.designation.language` - language changed the binding strength from Required to Preferred |
| CodeSystem.concept.designation.modifierExtension | CodeSystem.concept.designation.modifierExtension | SourceIsBroaderThanTarget | R5 `CodeSystem.concept.designation.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `CodeSystem.concept.designation.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| CodeSystem.concept.designation.use | CodeSystem.concept.designation.use | Equivalent | R5 `CodeSystem.concept.designation.use` maps as Equivalent to R4 `CodeSystem.concept.designation.use` |
| CodeSystem.concept.designation.value | CodeSystem.concept.designation.value | Equivalent | R5 `CodeSystem.concept.designation.value` maps as Equivalent to R4 `CodeSystem.concept.designation.value` |
| CodeSystem.concept.display | CodeSystem.concept.display | Equivalent | R5 `CodeSystem.concept.display` maps as Equivalent to R4 `CodeSystem.concept.display` |
| CodeSystem.concept.extension | CodeSystem.concept.extension | SourceIsBroaderThanTarget | R5 `CodeSystem.concept.extension` maps as SourceIsBroaderThanTarget to R4 `CodeSystem.concept.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| CodeSystem.concept.id | CodeSystem.concept.id | Equivalent | R5 `CodeSystem.concept.id` maps as Equivalent to R4 `CodeSystem.concept.id` |
| CodeSystem.concept.modifierExtension | CodeSystem.concept.modifierExtension | SourceIsBroaderThanTarget | R5 `CodeSystem.concept.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `CodeSystem.concept.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| CodeSystem.concept.property | CodeSystem.concept.property | Equivalent | R5 `CodeSystem.concept.property` maps as Equivalent to R4 `CodeSystem.concept.property` |
| CodeSystem.concept.property.code | CodeSystem.concept.property.code | Equivalent | R5 `CodeSystem.concept.property.code` maps as Equivalent to R4 `CodeSystem.concept.property.code` |
| CodeSystem.concept.property.extension | CodeSystem.concept.property.extension | SourceIsBroaderThanTarget | R5 `CodeSystem.concept.property.extension` maps as SourceIsBroaderThanTarget to R4 `CodeSystem.concept.property.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| CodeSystem.concept.property.id | CodeSystem.concept.property.id | Equivalent | R5 `CodeSystem.concept.property.id` maps as Equivalent to R4 `CodeSystem.concept.property.id` |
| CodeSystem.concept.property.modifierExtension | CodeSystem.concept.property.modifierExtension | SourceIsBroaderThanTarget | R5 `CodeSystem.concept.property.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `CodeSystem.concept.property.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| CodeSystem.concept.property.value[x] | CodeSystem.concept.property.value[x] | Equivalent | R5 `CodeSystem.concept.property.value[x]` maps as Equivalent to R4 `CodeSystem.concept.property.value[x]` |
| CodeSystem.contact | CodeSystem.contact | Equivalent | R5 `CodeSystem.contact` maps as Equivalent to R4 `CodeSystem.contact` |
| CodeSystem.contained | CodeSystem.contained | Equivalent | R5 `CodeSystem.contained` maps as Equivalent to R4 `CodeSystem.contained` |
| CodeSystem.content | CodeSystem.content | Equivalent | R5 `CodeSystem.content` maps as Equivalent to R4 `CodeSystem.content` - content has compatible required binding for code type: http://hl7.org/fhir/ValueSet/codesystem-content-mode|5.0.0 and http://hl7.org/fhir/ValueSet/codesystem-content-mode|4.0.1 (Equivalent) |
| CodeSystem.copyright | CodeSystem.copyright | Equivalent | R5 `CodeSystem.copyright` maps as Equivalent to R4 `CodeSystem.copyright` |
| CodeSystem.copyrightLabel | - | DoesNotExistInTarget | R5 `CodeSystem.copyrightLabel` does not appear in the target and has no mapping for `CodeSystem`. |
| CodeSystem.count | CodeSystem.count | Equivalent | R5 `CodeSystem.count` maps as Equivalent to R4 `CodeSystem.count` |
| CodeSystem.date | CodeSystem.date | Equivalent | R5 `CodeSystem.date` maps as Equivalent to R4 `CodeSystem.date` |
| CodeSystem.description | CodeSystem.description | Equivalent | R5 `CodeSystem.description` maps as Equivalent to R4 `CodeSystem.description` |
| CodeSystem.editor | - | DoesNotExistInTarget | R5 `CodeSystem.editor` does not appear in the target and has no mapping for `CodeSystem`. |
| CodeSystem.effectivePeriod | - | DoesNotExistInTarget | R5 `CodeSystem.effectivePeriod` does not appear in the target and has no mapping for `CodeSystem`. |
| CodeSystem.endorser | - | DoesNotExistInTarget | R5 `CodeSystem.endorser` does not appear in the target and has no mapping for `CodeSystem`. |
| CodeSystem.experimental | CodeSystem.experimental | Equivalent | R5 `CodeSystem.experimental` maps as Equivalent to R4 `CodeSystem.experimental` |
| CodeSystem.extension | CodeSystem.extension | SourceIsBroaderThanTarget | R5 `CodeSystem.extension` maps as SourceIsBroaderThanTarget to R4 `CodeSystem.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| CodeSystem.filter | CodeSystem.filter | Equivalent | R5 `CodeSystem.filter` maps as Equivalent to R4 `CodeSystem.filter` |
| CodeSystem.filter.code | CodeSystem.filter.code | Equivalent | R5 `CodeSystem.filter.code` maps as Equivalent to R4 `CodeSystem.filter.code` |
| CodeSystem.filter.description | CodeSystem.filter.description | Equivalent | R5 `CodeSystem.filter.description` maps as Equivalent to R4 `CodeSystem.filter.description` |
| CodeSystem.filter.extension | CodeSystem.filter.extension | SourceIsBroaderThanTarget | R5 `CodeSystem.filter.extension` maps as SourceIsBroaderThanTarget to R4 `CodeSystem.filter.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| CodeSystem.filter.id | CodeSystem.filter.id | Equivalent | R5 `CodeSystem.filter.id` maps as Equivalent to R4 `CodeSystem.filter.id` |
| CodeSystem.filter.modifierExtension | CodeSystem.filter.modifierExtension | SourceIsBroaderThanTarget | R5 `CodeSystem.filter.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `CodeSystem.filter.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| CodeSystem.filter.operator | CodeSystem.filter.operator | Equivalent | R5 `CodeSystem.filter.operator` maps as Equivalent to R4 `CodeSystem.filter.operator` - operator has compatible required binding for code type: http://hl7.org/fhir/ValueSet/filter-operator|5.0.0 and http://hl7.org/fhir/ValueSet/filter-operator|4.0.1 (Equivalent) |
| CodeSystem.filter.value | CodeSystem.filter.value | Equivalent | R5 `CodeSystem.filter.value` maps as Equivalent to R4 `CodeSystem.filter.value` |
| CodeSystem.hierarchyMeaning | CodeSystem.hierarchyMeaning | Equivalent | R5 `CodeSystem.hierarchyMeaning` maps as Equivalent to R4 `CodeSystem.hierarchyMeaning` - hierarchyMeaning has compatible required binding for code type: http://hl7.org/fhir/ValueSet/codesystem-hierarchy-meaning|5.0.0 and http://hl7.org/fhir/ValueSet/codesystem-hierarchy-meaning|4.0.1 (Equivalent) |
| CodeSystem.id | CodeSystem.id | Equivalent | R5 `CodeSystem.id` maps as Equivalent to R4 `CodeSystem.id` |
| CodeSystem.identifier | CodeSystem.identifier | Equivalent | R5 `CodeSystem.identifier` maps as Equivalent to R4 `CodeSystem.identifier` |
| CodeSystem.implicitRules | CodeSystem.implicitRules | Equivalent | R5 `CodeSystem.implicitRules` maps as Equivalent to R4 `CodeSystem.implicitRules` |
| CodeSystem.jurisdiction | CodeSystem.jurisdiction | Equivalent | R5 `CodeSystem.jurisdiction` maps as Equivalent to R4 `CodeSystem.jurisdiction` |
| CodeSystem.language | CodeSystem.language | RelatedTo | R5 `CodeSystem.language` maps as RelatedTo to R4 `CodeSystem.language` - language changed the binding strength from Required to Preferred |
| CodeSystem.lastReviewDate | - | DoesNotExistInTarget | R5 `CodeSystem.lastReviewDate` does not appear in the target and has no mapping for `CodeSystem`. |
| CodeSystem.meta | CodeSystem.meta | Equivalent | R5 `CodeSystem.meta` maps as Equivalent to R4 `CodeSystem.meta` |
| CodeSystem.modifierExtension | CodeSystem.modifierExtension | SourceIsBroaderThanTarget | R5 `CodeSystem.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `CodeSystem.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| CodeSystem.name | CodeSystem.name | Equivalent | R5 `CodeSystem.name` maps as Equivalent to R4 `CodeSystem.name` |
| CodeSystem.property | CodeSystem.property | Equivalent | R5 `CodeSystem.property` maps as Equivalent to R4 `CodeSystem.property` |
| CodeSystem.property.code | CodeSystem.property.code | Equivalent | R5 `CodeSystem.property.code` maps as Equivalent to R4 `CodeSystem.property.code` |
| CodeSystem.property.description | CodeSystem.property.description | Equivalent | R5 `CodeSystem.property.description` maps as Equivalent to R4 `CodeSystem.property.description` |
| CodeSystem.property.extension | CodeSystem.property.extension | SourceIsBroaderThanTarget | R5 `CodeSystem.property.extension` maps as SourceIsBroaderThanTarget to R4 `CodeSystem.property.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| CodeSystem.property.id | CodeSystem.property.id | Equivalent | R5 `CodeSystem.property.id` maps as Equivalent to R4 `CodeSystem.property.id` |
| CodeSystem.property.modifierExtension | CodeSystem.property.modifierExtension | SourceIsBroaderThanTarget | R5 `CodeSystem.property.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `CodeSystem.property.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| CodeSystem.property.type | CodeSystem.property.type | Equivalent | R5 `CodeSystem.property.type` maps as Equivalent to R4 `CodeSystem.property.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/concept-property-type|5.0.0 and http://hl7.org/fhir/ValueSet/concept-property-type|4.0.1 (Equivalent) |
| CodeSystem.property.uri | CodeSystem.property.uri | Equivalent | R5 `CodeSystem.property.uri` maps as Equivalent to R4 `CodeSystem.property.uri` |
| CodeSystem.publisher | CodeSystem.publisher | Equivalent | R5 `CodeSystem.publisher` maps as Equivalent to R4 `CodeSystem.publisher` |
| CodeSystem.purpose | CodeSystem.purpose | Equivalent | R5 `CodeSystem.purpose` maps as Equivalent to R4 `CodeSystem.purpose` |
| CodeSystem.relatedArtifact | - | DoesNotExistInTarget | R5 `CodeSystem.relatedArtifact` does not appear in the target and has no mapping for `CodeSystem`. |
| CodeSystem.reviewer | - | DoesNotExistInTarget | R5 `CodeSystem.reviewer` does not appear in the target and has no mapping for `CodeSystem`. |
| CodeSystem.status | CodeSystem.status | Equivalent | R5 `CodeSystem.status` maps as Equivalent to R4 `CodeSystem.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.0.1 (Equivalent) |
| CodeSystem.supplements | CodeSystem.supplements | Equivalent | R5 `CodeSystem.supplements` maps as Equivalent to R4 `CodeSystem.supplements` |
| CodeSystem.text | CodeSystem.text | Equivalent | R5 `CodeSystem.text` maps as Equivalent to R4 `CodeSystem.text` |
| CodeSystem.title | CodeSystem.title | Equivalent | R5 `CodeSystem.title` maps as Equivalent to R4 `CodeSystem.title` |
| CodeSystem.topic | - | DoesNotExistInTarget | R5 `CodeSystem.topic` does not appear in the target and has no mapping for `CodeSystem`. |
| CodeSystem.url | CodeSystem.url | Equivalent | R5 `CodeSystem.url` maps as Equivalent to R4 `CodeSystem.url` |
| CodeSystem.useContext | CodeSystem.useContext | Equivalent | R5 `CodeSystem.useContext` maps as Equivalent to R4 `CodeSystem.useContext` |
| CodeSystem.valueSet | CodeSystem.valueSet | Equivalent | R5 `CodeSystem.valueSet` maps as Equivalent to R4 `CodeSystem.valueSet` |
| CodeSystem.version | CodeSystem.version | Equivalent | R5 `CodeSystem.version` maps as Equivalent to R4 `CodeSystem.version` |
| CodeSystem.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `CodeSystem.versionAlgorithm[x]` does not appear in the target and has no mapping for `CodeSystem`. |
| CodeSystem.versionNeeded | CodeSystem.versionNeeded | Equivalent | R5 `CodeSystem.versionNeeded` maps as Equivalent to R4 `CodeSystem.versionNeeded` |

