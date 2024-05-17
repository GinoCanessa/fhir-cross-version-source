Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | OperationDefinition |  | A formal computable definition of an operation (on the RESTful interface) or a named query (using the search interaction). | 64 | 44 |
| Target | OperationDefinition |  | A formal computable definition of an operation (on the RESTful interface) or a named query (using the search interaction). | 70 | 50 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 60 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| OperationDefinition | OperationDefinition | Equivalent | R4B `OperationDefinition` maps as Equivalent to R5 `OperationDefinition` |
| OperationDefinition.affectsState | OperationDefinition.affectsState | Equivalent | R4B `OperationDefinition.affectsState` maps as Equivalent to R5 `OperationDefinition.affectsState` |
| OperationDefinition.base | OperationDefinition.base | Equivalent | R4B `OperationDefinition.base` maps as Equivalent to R5 `OperationDefinition.base` |
| OperationDefinition.code | OperationDefinition.code | Equivalent | R4B `OperationDefinition.code` maps as Equivalent to R5 `OperationDefinition.code` |
| OperationDefinition.comment | OperationDefinition.comment | Equivalent | R4B `OperationDefinition.comment` maps as Equivalent to R5 `OperationDefinition.comment` |
| OperationDefinition.contact | OperationDefinition.contact | Equivalent | R4B `OperationDefinition.contact` maps as Equivalent to R5 `OperationDefinition.contact` |
| OperationDefinition.contained | OperationDefinition.contained | Equivalent | R4B `OperationDefinition.contained` maps as Equivalent to R5 `OperationDefinition.contained` |
| OperationDefinition.date | OperationDefinition.date | Equivalent | R4B `OperationDefinition.date` maps as Equivalent to R5 `OperationDefinition.date` |
| OperationDefinition.description | OperationDefinition.description | Equivalent | R4B `OperationDefinition.description` maps as Equivalent to R5 `OperationDefinition.description` |
| OperationDefinition.experimental | OperationDefinition.experimental | Equivalent | R4B `OperationDefinition.experimental` maps as Equivalent to R5 `OperationDefinition.experimental` |
| OperationDefinition.extension | OperationDefinition.extension | RelatedTo | R4B `OperationDefinition.extension` maps as RelatedTo to R5 `OperationDefinition.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| OperationDefinition.id | OperationDefinition.id | Equivalent | R4B `OperationDefinition.id` maps as Equivalent to R5 `OperationDefinition.id` |
| OperationDefinition.implicitRules | OperationDefinition.implicitRules | Equivalent | R4B `OperationDefinition.implicitRules` maps as Equivalent to R5 `OperationDefinition.implicitRules` |
| OperationDefinition.inputProfile | OperationDefinition.inputProfile | Equivalent | R4B `OperationDefinition.inputProfile` maps as Equivalent to R5 `OperationDefinition.inputProfile` |
| OperationDefinition.instance | OperationDefinition.instance | Equivalent | R4B `OperationDefinition.instance` maps as Equivalent to R5 `OperationDefinition.instance` |
| OperationDefinition.jurisdiction | OperationDefinition.jurisdiction | Equivalent | R4B `OperationDefinition.jurisdiction` maps as Equivalent to R5 `OperationDefinition.jurisdiction` |
| OperationDefinition.kind | OperationDefinition.kind | Equivalent | R4B `OperationDefinition.kind` maps as Equivalent to R5 `OperationDefinition.kind` - kind has compatible required binding for code type: http://hl7.org/fhir/ValueSet/operation-kind|4.3.0 and http://hl7.org/fhir/ValueSet/operation-kind|5.0.0 (Equivalent) |
| OperationDefinition.language | OperationDefinition.language | RelatedTo | R4B `OperationDefinition.language` maps as RelatedTo to R5 `OperationDefinition.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| OperationDefinition.meta | OperationDefinition.meta | Equivalent | R4B `OperationDefinition.meta` maps as Equivalent to R5 `OperationDefinition.meta` |
| OperationDefinition.modifierExtension | OperationDefinition.modifierExtension | RelatedTo | R4B `OperationDefinition.modifierExtension` maps as RelatedTo to R5 `OperationDefinition.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| OperationDefinition.name | OperationDefinition.name | Equivalent | R4B `OperationDefinition.name` maps as Equivalent to R5 `OperationDefinition.name` |
| OperationDefinition.outputProfile | OperationDefinition.outputProfile | Equivalent | R4B `OperationDefinition.outputProfile` maps as Equivalent to R5 `OperationDefinition.outputProfile` |
| OperationDefinition.overload | OperationDefinition.overload | Equivalent | R4B `OperationDefinition.overload` maps as Equivalent to R5 `OperationDefinition.overload` |
| OperationDefinition.overload.comment | OperationDefinition.overload.comment | Equivalent | R4B `OperationDefinition.overload.comment` maps as Equivalent to R5 `OperationDefinition.overload.comment` |
| OperationDefinition.overload.extension | OperationDefinition.overload.extension | RelatedTo | R4B `OperationDefinition.overload.extension` maps as RelatedTo to R5 `OperationDefinition.overload.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| OperationDefinition.overload.id | OperationDefinition.overload.id | Equivalent | R4B `OperationDefinition.overload.id` maps as Equivalent to R5 `OperationDefinition.overload.id` |
| OperationDefinition.overload.modifierExtension | OperationDefinition.overload.modifierExtension | RelatedTo | R4B `OperationDefinition.overload.modifierExtension` maps as RelatedTo to R5 `OperationDefinition.overload.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| OperationDefinition.overload.parameterName | OperationDefinition.overload.parameterName | Equivalent | R4B `OperationDefinition.overload.parameterName` maps as Equivalent to R5 `OperationDefinition.overload.parameterName` |
| OperationDefinition.parameter | OperationDefinition.parameter | Equivalent | R4B `OperationDefinition.parameter` maps as Equivalent to R5 `OperationDefinition.parameter` |
| OperationDefinition.parameter.binding | OperationDefinition.parameter.binding | Equivalent | R4B `OperationDefinition.parameter.binding` maps as Equivalent to R5 `OperationDefinition.parameter.binding` |
| OperationDefinition.parameter.binding.extension | OperationDefinition.parameter.binding.extension | RelatedTo | R4B `OperationDefinition.parameter.binding.extension` maps as RelatedTo to R5 `OperationDefinition.parameter.binding.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| OperationDefinition.parameter.binding.id | OperationDefinition.parameter.binding.id | Equivalent | R4B `OperationDefinition.parameter.binding.id` maps as Equivalent to R5 `OperationDefinition.parameter.binding.id` |
| OperationDefinition.parameter.binding.modifierExtension | OperationDefinition.parameter.binding.modifierExtension | RelatedTo | R4B `OperationDefinition.parameter.binding.modifierExtension` maps as RelatedTo to R5 `OperationDefinition.parameter.binding.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| OperationDefinition.parameter.binding.strength | OperationDefinition.parameter.binding.strength | Equivalent | R4B `OperationDefinition.parameter.binding.strength` maps as Equivalent to R5 `OperationDefinition.parameter.binding.strength` - strength has compatible required binding for code type: http://hl7.org/fhir/ValueSet/binding-strength|4.3.0 and http://hl7.org/fhir/ValueSet/binding-strength|5.0.0 (Equivalent) |
| OperationDefinition.parameter.binding.valueSet | OperationDefinition.parameter.binding.valueSet | Equivalent | R4B `OperationDefinition.parameter.binding.valueSet` maps as Equivalent to R5 `OperationDefinition.parameter.binding.valueSet` |
| OperationDefinition.parameter.documentation | OperationDefinition.parameter.documentation | SourceIsBroaderThanTarget | R4B `OperationDefinition.parameter.documentation` maps as SourceIsBroaderThanTarget to R5 `OperationDefinition.parameter.documentation` - documentation has change due to type change: R4B documentation string has no equivalent or mapped type in R5 documentation |
| OperationDefinition.parameter.extension | OperationDefinition.parameter.extension | RelatedTo | R4B `OperationDefinition.parameter.extension` maps as RelatedTo to R5 `OperationDefinition.parameter.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| OperationDefinition.parameter.id | OperationDefinition.parameter.id | Equivalent | R4B `OperationDefinition.parameter.id` maps as Equivalent to R5 `OperationDefinition.parameter.id` |
| OperationDefinition.parameter.max | OperationDefinition.parameter.max | Equivalent | R4B `OperationDefinition.parameter.max` maps as Equivalent to R5 `OperationDefinition.parameter.max` |
| OperationDefinition.parameter.min | OperationDefinition.parameter.min | Equivalent | R4B `OperationDefinition.parameter.min` maps as Equivalent to R5 `OperationDefinition.parameter.min` |
| OperationDefinition.parameter.modifierExtension | OperationDefinition.parameter.modifierExtension | RelatedTo | R4B `OperationDefinition.parameter.modifierExtension` maps as RelatedTo to R5 `OperationDefinition.parameter.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| OperationDefinition.parameter.name | OperationDefinition.parameter.name | Equivalent | R4B `OperationDefinition.parameter.name` maps as Equivalent to R5 `OperationDefinition.parameter.name` |
| OperationDefinition.parameter.part | OperationDefinition.parameter.part | Equivalent | R4B `OperationDefinition.parameter.part` maps as Equivalent to R5 `OperationDefinition.parameter.part` |
| OperationDefinition.parameter.referencedFrom | OperationDefinition.parameter.referencedFrom | Equivalent | R4B `OperationDefinition.parameter.referencedFrom` maps as Equivalent to R5 `OperationDefinition.parameter.referencedFrom` |
| OperationDefinition.parameter.referencedFrom.extension | OperationDefinition.parameter.referencedFrom.extension | RelatedTo | R4B `OperationDefinition.parameter.referencedFrom.extension` maps as RelatedTo to R5 `OperationDefinition.parameter.referencedFrom.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| OperationDefinition.parameter.referencedFrom.id | OperationDefinition.parameter.referencedFrom.id | Equivalent | R4B `OperationDefinition.parameter.referencedFrom.id` maps as Equivalent to R5 `OperationDefinition.parameter.referencedFrom.id` |
| OperationDefinition.parameter.referencedFrom.modifierExtension | OperationDefinition.parameter.referencedFrom.modifierExtension | RelatedTo | R4B `OperationDefinition.parameter.referencedFrom.modifierExtension` maps as RelatedTo to R5 `OperationDefinition.parameter.referencedFrom.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| OperationDefinition.parameter.referencedFrom.source | OperationDefinition.parameter.referencedFrom.source | Equivalent | R4B `OperationDefinition.parameter.referencedFrom.source` maps as Equivalent to R5 `OperationDefinition.parameter.referencedFrom.source` |
| OperationDefinition.parameter.referencedFrom.sourceId | OperationDefinition.parameter.referencedFrom.sourceId | Equivalent | R4B `OperationDefinition.parameter.referencedFrom.sourceId` maps as Equivalent to R5 `OperationDefinition.parameter.referencedFrom.sourceId` |
| OperationDefinition.parameter.searchType | OperationDefinition.parameter.searchType | Equivalent | R4B `OperationDefinition.parameter.searchType` maps as Equivalent to R5 `OperationDefinition.parameter.searchType` - searchType has compatible required binding for code type: http://hl7.org/fhir/ValueSet/search-param-type|4.3.0 and http://hl7.org/fhir/ValueSet/search-param-type|5.0.0 (Equivalent) |
| OperationDefinition.parameter.targetProfile | OperationDefinition.parameter.targetProfile | Equivalent | R4B `OperationDefinition.parameter.targetProfile` maps as Equivalent to R5 `OperationDefinition.parameter.targetProfile` |
| OperationDefinition.parameter.type | OperationDefinition.parameter.type | RelatedTo | R4B `OperationDefinition.parameter.type` maps as RelatedTo to R5 `OperationDefinition.parameter.type` - (type failed to compare required binding of http://hl7.org/fhir/ValueSet/all-types|4.3.0 and http://hl7.org/fhir/ValueSet/fhir-types|5.0.0) |
| OperationDefinition.parameter.use | OperationDefinition.parameter.use | Equivalent | R4B `OperationDefinition.parameter.use` maps as Equivalent to R5 `OperationDefinition.parameter.use` - use has compatible required binding for code type: http://hl7.org/fhir/ValueSet/operation-parameter-use|4.3.0 and http://hl7.org/fhir/ValueSet/operation-parameter-use|5.0.0 (Equivalent) |
| OperationDefinition.publisher | OperationDefinition.publisher | Equivalent | R4B `OperationDefinition.publisher` maps as Equivalent to R5 `OperationDefinition.publisher` |
| OperationDefinition.purpose | OperationDefinition.purpose | Equivalent | R4B `OperationDefinition.purpose` maps as Equivalent to R5 `OperationDefinition.purpose` |
| OperationDefinition.resource | OperationDefinition.resource | RelatedTo | R4B `OperationDefinition.resource` maps as RelatedTo to R5 `OperationDefinition.resource` - (resource failed to compare required binding of http://hl7.org/fhir/ValueSet/resource-types|4.3.0 and http://hl7.org/fhir/ValueSet/version-independent-all-resource-types|5.0.0) |
| OperationDefinition.status | OperationDefinition.status | Equivalent | R4B `OperationDefinition.status` maps as Equivalent to R5 `OperationDefinition.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| OperationDefinition.system | OperationDefinition.system | Equivalent | R4B `OperationDefinition.system` maps as Equivalent to R5 `OperationDefinition.system` |
| OperationDefinition.text | OperationDefinition.text | Equivalent | R4B `OperationDefinition.text` maps as Equivalent to R5 `OperationDefinition.text` |
| OperationDefinition.title | OperationDefinition.title | Equivalent | R4B `OperationDefinition.title` maps as Equivalent to R5 `OperationDefinition.title` |
| OperationDefinition.type | OperationDefinition.type | Equivalent | R4B `OperationDefinition.type` maps as Equivalent to R5 `OperationDefinition.type` |
| OperationDefinition.url | OperationDefinition.url | Equivalent | R4B `OperationDefinition.url` maps as Equivalent to R5 `OperationDefinition.url` |
| OperationDefinition.useContext | OperationDefinition.useContext | Equivalent | R4B `OperationDefinition.useContext` maps as Equivalent to R5 `OperationDefinition.useContext` |
| OperationDefinition.version | OperationDefinition.version | Equivalent | R4B `OperationDefinition.version` maps as Equivalent to R5 `OperationDefinition.version` |

