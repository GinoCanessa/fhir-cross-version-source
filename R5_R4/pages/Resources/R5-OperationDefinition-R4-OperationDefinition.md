Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | OperationDefinition |  | A formal computable definition of an operation (on the RESTful interface) or a named query (using the search interaction). | 70 | 50 |
| Target | OperationDefinition |  | A formal computable definition of an operation (on the RESTful interface) or a named query (using the search interaction). | 64 | 44 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 6 |
Equivalent | 50 |
RelatedTo | 2 |
SourceIsBroaderThanTarget | 11 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| OperationDefinition | OperationDefinition | Equivalent | R5 `OperationDefinition` maps as Equivalent to R4 `OperationDefinition` |
| OperationDefinition.affectsState | OperationDefinition.affectsState | Equivalent | R5 `OperationDefinition.affectsState` maps as Equivalent to R4 `OperationDefinition.affectsState` |
| OperationDefinition.base | OperationDefinition.base | Equivalent | R5 `OperationDefinition.base` maps as Equivalent to R4 `OperationDefinition.base` |
| OperationDefinition.code | OperationDefinition.code | Equivalent | R5 `OperationDefinition.code` maps as Equivalent to R4 `OperationDefinition.code` |
| OperationDefinition.comment | OperationDefinition.comment | Equivalent | R5 `OperationDefinition.comment` maps as Equivalent to R4 `OperationDefinition.comment` |
| OperationDefinition.contact | OperationDefinition.contact | Equivalent | R5 `OperationDefinition.contact` maps as Equivalent to R4 `OperationDefinition.contact` |
| OperationDefinition.contained | OperationDefinition.contained | Equivalent | R5 `OperationDefinition.contained` maps as Equivalent to R4 `OperationDefinition.contained` |
| OperationDefinition.copyright | - | DoesNotExistInTarget | R5 `OperationDefinition.copyright` does not appear in the target and has no mapping for `OperationDefinition`. |
| OperationDefinition.copyrightLabel | - | DoesNotExistInTarget | R5 `OperationDefinition.copyrightLabel` does not appear in the target and has no mapping for `OperationDefinition`. |
| OperationDefinition.date | OperationDefinition.date | Equivalent | R5 `OperationDefinition.date` maps as Equivalent to R4 `OperationDefinition.date` |
| OperationDefinition.description | OperationDefinition.description | Equivalent | R5 `OperationDefinition.description` maps as Equivalent to R4 `OperationDefinition.description` |
| OperationDefinition.experimental | OperationDefinition.experimental | Equivalent | R5 `OperationDefinition.experimental` maps as Equivalent to R4 `OperationDefinition.experimental` |
| OperationDefinition.extension | OperationDefinition.extension | SourceIsBroaderThanTarget | R5 `OperationDefinition.extension` maps as SourceIsBroaderThanTarget to R4 `OperationDefinition.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| OperationDefinition.id | OperationDefinition.id | Equivalent | R5 `OperationDefinition.id` maps as Equivalent to R4 `OperationDefinition.id` |
| OperationDefinition.identifier | - | DoesNotExistInTarget | R5 `OperationDefinition.identifier` does not appear in the target and has no mapping for `OperationDefinition`. |
| OperationDefinition.implicitRules | OperationDefinition.implicitRules | Equivalent | R5 `OperationDefinition.implicitRules` maps as Equivalent to R4 `OperationDefinition.implicitRules` |
| OperationDefinition.inputProfile | OperationDefinition.inputProfile | Equivalent | R5 `OperationDefinition.inputProfile` maps as Equivalent to R4 `OperationDefinition.inputProfile` |
| OperationDefinition.instance | OperationDefinition.instance | Equivalent | R5 `OperationDefinition.instance` maps as Equivalent to R4 `OperationDefinition.instance` |
| OperationDefinition.jurisdiction | OperationDefinition.jurisdiction | Equivalent | R5 `OperationDefinition.jurisdiction` maps as Equivalent to R4 `OperationDefinition.jurisdiction` |
| OperationDefinition.kind | OperationDefinition.kind | Equivalent | R5 `OperationDefinition.kind` maps as Equivalent to R4 `OperationDefinition.kind` - kind has compatible required binding for code type: http://hl7.org/fhir/ValueSet/operation-kind|5.0.0 and http://hl7.org/fhir/ValueSet/operation-kind|4.0.1 (Equivalent) |
| OperationDefinition.language | OperationDefinition.language | SourceIsNarrowerThanTarget | R5 `OperationDefinition.language` maps as SourceIsNarrowerThanTarget to R4 `OperationDefinition.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| OperationDefinition.meta | OperationDefinition.meta | Equivalent | R5 `OperationDefinition.meta` maps as Equivalent to R4 `OperationDefinition.meta` |
| OperationDefinition.modifierExtension | OperationDefinition.modifierExtension | SourceIsBroaderThanTarget | R5 `OperationDefinition.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `OperationDefinition.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| OperationDefinition.name | OperationDefinition.name | Equivalent | R5 `OperationDefinition.name` maps as Equivalent to R4 `OperationDefinition.name` |
| OperationDefinition.outputProfile | OperationDefinition.outputProfile | Equivalent | R5 `OperationDefinition.outputProfile` maps as Equivalent to R4 `OperationDefinition.outputProfile` |
| OperationDefinition.overload | OperationDefinition.overload | Equivalent | R5 `OperationDefinition.overload` maps as Equivalent to R4 `OperationDefinition.overload` |
| OperationDefinition.overload.comment | OperationDefinition.overload.comment | Equivalent | R5 `OperationDefinition.overload.comment` maps as Equivalent to R4 `OperationDefinition.overload.comment` |
| OperationDefinition.overload.extension | OperationDefinition.overload.extension | SourceIsBroaderThanTarget | R5 `OperationDefinition.overload.extension` maps as SourceIsBroaderThanTarget to R4 `OperationDefinition.overload.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| OperationDefinition.overload.id | OperationDefinition.overload.id | Equivalent | R5 `OperationDefinition.overload.id` maps as Equivalent to R4 `OperationDefinition.overload.id` |
| OperationDefinition.overload.modifierExtension | OperationDefinition.overload.modifierExtension | SourceIsBroaderThanTarget | R5 `OperationDefinition.overload.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `OperationDefinition.overload.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| OperationDefinition.overload.parameterName | OperationDefinition.overload.parameterName | Equivalent | R5 `OperationDefinition.overload.parameterName` maps as Equivalent to R4 `OperationDefinition.overload.parameterName` |
| OperationDefinition.parameter | OperationDefinition.parameter | Equivalent | R5 `OperationDefinition.parameter` maps as Equivalent to R4 `OperationDefinition.parameter` |
| OperationDefinition.parameter.allowedType | - | DoesNotExistInTarget | R5 `OperationDefinition.parameter.allowedType` does not appear in the target and has no mapping for `OperationDefinition`. |
| OperationDefinition.parameter.binding | OperationDefinition.parameter.binding | Equivalent | R5 `OperationDefinition.parameter.binding` maps as Equivalent to R4 `OperationDefinition.parameter.binding` |
| OperationDefinition.parameter.binding.extension | OperationDefinition.parameter.binding.extension | SourceIsBroaderThanTarget | R5 `OperationDefinition.parameter.binding.extension` maps as SourceIsBroaderThanTarget to R4 `OperationDefinition.parameter.binding.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| OperationDefinition.parameter.binding.id | OperationDefinition.parameter.binding.id | Equivalent | R5 `OperationDefinition.parameter.binding.id` maps as Equivalent to R4 `OperationDefinition.parameter.binding.id` |
| OperationDefinition.parameter.binding.modifierExtension | OperationDefinition.parameter.binding.modifierExtension | SourceIsBroaderThanTarget | R5 `OperationDefinition.parameter.binding.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `OperationDefinition.parameter.binding.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| OperationDefinition.parameter.binding.strength | OperationDefinition.parameter.binding.strength | Equivalent | R5 `OperationDefinition.parameter.binding.strength` maps as Equivalent to R4 `OperationDefinition.parameter.binding.strength` - strength has compatible required binding for code type: http://hl7.org/fhir/ValueSet/binding-strength|5.0.0 and http://hl7.org/fhir/ValueSet/binding-strength|4.0.1 (Equivalent) |
| OperationDefinition.parameter.binding.valueSet | OperationDefinition.parameter.binding.valueSet | Equivalent | R5 `OperationDefinition.parameter.binding.valueSet` maps as Equivalent to R4 `OperationDefinition.parameter.binding.valueSet` |
| OperationDefinition.parameter.documentation | OperationDefinition.parameter.documentation | SourceIsBroaderThanTarget | R5 `OperationDefinition.parameter.documentation` maps as SourceIsBroaderThanTarget to R4 `OperationDefinition.parameter.documentation` - documentation has change due to type change: R5 documentation markdown has no equivalent or mapped type in R4 documentation |
| OperationDefinition.parameter.extension | OperationDefinition.parameter.extension | SourceIsBroaderThanTarget | R5 `OperationDefinition.parameter.extension` maps as SourceIsBroaderThanTarget to R4 `OperationDefinition.parameter.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| OperationDefinition.parameter.id | OperationDefinition.parameter.id | Equivalent | R5 `OperationDefinition.parameter.id` maps as Equivalent to R4 `OperationDefinition.parameter.id` |
| OperationDefinition.parameter.max | OperationDefinition.parameter.max | Equivalent | R5 `OperationDefinition.parameter.max` maps as Equivalent to R4 `OperationDefinition.parameter.max` |
| OperationDefinition.parameter.min | OperationDefinition.parameter.min | Equivalent | R5 `OperationDefinition.parameter.min` maps as Equivalent to R4 `OperationDefinition.parameter.min` |
| OperationDefinition.parameter.modifierExtension | OperationDefinition.parameter.modifierExtension | SourceIsBroaderThanTarget | R5 `OperationDefinition.parameter.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `OperationDefinition.parameter.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| OperationDefinition.parameter.name | OperationDefinition.parameter.name | Equivalent | R5 `OperationDefinition.parameter.name` maps as Equivalent to R4 `OperationDefinition.parameter.name` |
| OperationDefinition.parameter.part | OperationDefinition.parameter.part | Equivalent | R5 `OperationDefinition.parameter.part` maps as Equivalent to R4 `OperationDefinition.parameter.part` |
| OperationDefinition.parameter.referencedFrom | OperationDefinition.parameter.referencedFrom | Equivalent | R5 `OperationDefinition.parameter.referencedFrom` maps as Equivalent to R4 `OperationDefinition.parameter.referencedFrom` |
| OperationDefinition.parameter.referencedFrom.extension | OperationDefinition.parameter.referencedFrom.extension | SourceIsBroaderThanTarget | R5 `OperationDefinition.parameter.referencedFrom.extension` maps as SourceIsBroaderThanTarget to R4 `OperationDefinition.parameter.referencedFrom.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| OperationDefinition.parameter.referencedFrom.id | OperationDefinition.parameter.referencedFrom.id | Equivalent | R5 `OperationDefinition.parameter.referencedFrom.id` maps as Equivalent to R4 `OperationDefinition.parameter.referencedFrom.id` |
| OperationDefinition.parameter.referencedFrom.modifierExtension | OperationDefinition.parameter.referencedFrom.modifierExtension | SourceIsBroaderThanTarget | R5 `OperationDefinition.parameter.referencedFrom.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `OperationDefinition.parameter.referencedFrom.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| OperationDefinition.parameter.referencedFrom.source | OperationDefinition.parameter.referencedFrom.source | Equivalent | R5 `OperationDefinition.parameter.referencedFrom.source` maps as Equivalent to R4 `OperationDefinition.parameter.referencedFrom.source` |
| OperationDefinition.parameter.referencedFrom.sourceId | OperationDefinition.parameter.referencedFrom.sourceId | Equivalent | R5 `OperationDefinition.parameter.referencedFrom.sourceId` maps as Equivalent to R4 `OperationDefinition.parameter.referencedFrom.sourceId` |
| OperationDefinition.parameter.scope | - | DoesNotExistInTarget | R5 `OperationDefinition.parameter.scope` does not appear in the target and has no mapping for `OperationDefinition`. |
| OperationDefinition.parameter.searchType | OperationDefinition.parameter.searchType | Equivalent | R5 `OperationDefinition.parameter.searchType` maps as Equivalent to R4 `OperationDefinition.parameter.searchType` - searchType has compatible required binding for code type: http://hl7.org/fhir/ValueSet/search-param-type|5.0.0 and http://hl7.org/fhir/ValueSet/search-param-type|4.0.1 (Equivalent) |
| OperationDefinition.parameter.targetProfile | OperationDefinition.parameter.targetProfile | Equivalent | R5 `OperationDefinition.parameter.targetProfile` maps as Equivalent to R4 `OperationDefinition.parameter.targetProfile` |
| OperationDefinition.parameter.type | OperationDefinition.parameter.type | RelatedTo | R5 `OperationDefinition.parameter.type` maps as RelatedTo to R4 `OperationDefinition.parameter.type` - (type failed to compare required binding of http://hl7.org/fhir/ValueSet/fhir-types|5.0.0 and http://hl7.org/fhir/ValueSet/all-types|4.0.1); type has change due to type change: R5 `type` `code` maps as RelatedTo for R4 `type` |
| OperationDefinition.parameter.use | OperationDefinition.parameter.use | Equivalent | R5 `OperationDefinition.parameter.use` maps as Equivalent to R4 `OperationDefinition.parameter.use` - use has compatible required binding for code type: http://hl7.org/fhir/ValueSet/operation-parameter-use|5.0.0 and http://hl7.org/fhir/ValueSet/operation-parameter-use|4.0.1 (Equivalent) |
| OperationDefinition.publisher | OperationDefinition.publisher | Equivalent | R5 `OperationDefinition.publisher` maps as Equivalent to R4 `OperationDefinition.publisher` |
| OperationDefinition.purpose | OperationDefinition.purpose | Equivalent | R5 `OperationDefinition.purpose` maps as Equivalent to R4 `OperationDefinition.purpose` |
| OperationDefinition.resource | OperationDefinition.resource | RelatedTo | R5 `OperationDefinition.resource` maps as RelatedTo to R4 `OperationDefinition.resource` - (resource failed to compare required binding of http://hl7.org/fhir/ValueSet/version-independent-all-resource-types|5.0.0 and http://hl7.org/fhir/ValueSet/resource-types|4.0.1); resource has change due to type change: R5 `resource` `code` maps as RelatedTo for R4 `resource` |
| OperationDefinition.status | OperationDefinition.status | Equivalent | R5 `OperationDefinition.status` maps as Equivalent to R4 `OperationDefinition.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.0.1 (Equivalent) |
| OperationDefinition.system | OperationDefinition.system | Equivalent | R5 `OperationDefinition.system` maps as Equivalent to R4 `OperationDefinition.system` |
| OperationDefinition.text | OperationDefinition.text | Equivalent | R5 `OperationDefinition.text` maps as Equivalent to R4 `OperationDefinition.text` |
| OperationDefinition.title | OperationDefinition.title | Equivalent | R5 `OperationDefinition.title` maps as Equivalent to R4 `OperationDefinition.title` |
| OperationDefinition.type | OperationDefinition.type | Equivalent | R5 `OperationDefinition.type` maps as Equivalent to R4 `OperationDefinition.type` |
| OperationDefinition.url | OperationDefinition.url | Equivalent | R5 `OperationDefinition.url` maps as Equivalent to R4 `OperationDefinition.url` |
| OperationDefinition.useContext | OperationDefinition.useContext | Equivalent | R5 `OperationDefinition.useContext` maps as Equivalent to R4 `OperationDefinition.useContext` |
| OperationDefinition.version | OperationDefinition.version | Equivalent | R5 `OperationDefinition.version` maps as Equivalent to R4 `OperationDefinition.version` |
| OperationDefinition.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `OperationDefinition.versionAlgorithm[x]` does not appear in the target and has no mapping for `OperationDefinition`. |

