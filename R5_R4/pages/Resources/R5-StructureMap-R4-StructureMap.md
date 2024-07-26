Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:51 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | StructureMap |  | A Map of relationships between 2 structures that can be used to transform data. | 100 | 65 |
| Target | StructureMap |  | A Map of relationships between 2 structures that can be used to transform data. | 93 | 61 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 10 |
Equivalent | 4 |
RelatedTo | 86 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| StructureMap | StructureMap | Equivalent | R5 `StructureMap` maps as Equivalent to R4 `StructureMap` |
| StructureMap.const | - | DoesNotExistInTarget | R5 `StructureMap.const` does not appear in the target and has no mapping for `StructureMap`. |
| StructureMap.const.extension | - | DoesNotExistInTarget | R5 `StructureMap.const.extension` does not appear in the target and has no mapping for `StructureMap`. |
| StructureMap.const.id | - | DoesNotExistInTarget | R5 `StructureMap.const.id` does not appear in the target and has no mapping for `StructureMap`. |
| StructureMap.const.modifierExtension | - | DoesNotExistInTarget | R5 `StructureMap.const.modifierExtension` does not appear in the target and has no mapping for `StructureMap`. |
| StructureMap.const.name | - | DoesNotExistInTarget | R5 `StructureMap.const.name` does not appear in the target and has no mapping for `StructureMap`. |
| StructureMap.const.value | - | DoesNotExistInTarget | R5 `StructureMap.const.value` does not appear in the target and has no mapping for `StructureMap`. |
| StructureMap.contact | StructureMap.contact | Equivalent | R5 `StructureMap.contact` maps as Equivalent to R4 `StructureMap.contact` |
| StructureMap.contained | StructureMap.contained | Equivalent | R5 `StructureMap.contained` maps as Equivalent to R4 `StructureMap.contained` |
| StructureMap.copyright | StructureMap.copyright | Equivalent | R5 `StructureMap.copyright` maps as Equivalent to R4 `StructureMap.copyright` |
| StructureMap.copyrightLabel | - | DoesNotExistInTarget | R5 `StructureMap.copyrightLabel` does not appear in the target and has no mapping for `StructureMap`. |
| StructureMap.date | StructureMap.date | Equivalent | R5 `StructureMap.date` maps as Equivalent to R4 `StructureMap.date` |
| StructureMap.description | StructureMap.description | Equivalent | R5 `StructureMap.description` maps as Equivalent to R4 `StructureMap.description` |
| StructureMap.experimental | StructureMap.experimental | Equivalent | R5 `StructureMap.experimental` maps as Equivalent to R4 `StructureMap.experimental` |
| StructureMap.extension | StructureMap.extension | SourceIsBroaderThanTarget | R5 `StructureMap.extension` maps as SourceIsBroaderThanTarget to R4 `StructureMap.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| StructureMap.group | StructureMap.group | Equivalent | R5 `StructureMap.group` maps as Equivalent to R4 `StructureMap.group` |
| StructureMap.group.documentation | StructureMap.group.documentation | Equivalent | R5 `StructureMap.group.documentation` maps as Equivalent to R4 `StructureMap.group.documentation` |
| StructureMap.group.extends | StructureMap.group.extends | Equivalent | R5 `StructureMap.group.extends` maps as Equivalent to R4 `StructureMap.group.extends` |
| StructureMap.group.extension | StructureMap.group.extension | SourceIsBroaderThanTarget | R5 `StructureMap.group.extension` maps as SourceIsBroaderThanTarget to R4 `StructureMap.group.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| StructureMap.group.id | StructureMap.group.id | Equivalent | R5 `StructureMap.group.id` maps as Equivalent to R4 `StructureMap.group.id` |
| StructureMap.group.input | StructureMap.group.input | Equivalent | R5 `StructureMap.group.input` maps as Equivalent to R4 `StructureMap.group.input` |
| StructureMap.group.input.documentation | StructureMap.group.input.documentation | Equivalent | R5 `StructureMap.group.input.documentation` maps as Equivalent to R4 `StructureMap.group.input.documentation` |
| StructureMap.group.input.extension | StructureMap.group.input.extension | SourceIsBroaderThanTarget | R5 `StructureMap.group.input.extension` maps as SourceIsBroaderThanTarget to R4 `StructureMap.group.input.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| StructureMap.group.input.id | StructureMap.group.input.id | Equivalent | R5 `StructureMap.group.input.id` maps as Equivalent to R4 `StructureMap.group.input.id` |
| StructureMap.group.input.mode | StructureMap.group.input.mode | Equivalent | R5 `StructureMap.group.input.mode` maps as Equivalent to R4 `StructureMap.group.input.mode` - mode has compatible required binding for code type: http://hl7.org/fhir/ValueSet/map-input-mode|5.0.0 and http://hl7.org/fhir/ValueSet/map-input-mode|4.0.1 (Equivalent) |
| StructureMap.group.input.modifierExtension | StructureMap.group.input.modifierExtension | SourceIsBroaderThanTarget | R5 `StructureMap.group.input.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `StructureMap.group.input.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| StructureMap.group.input.name | StructureMap.group.input.name | Equivalent | R5 `StructureMap.group.input.name` maps as Equivalent to R4 `StructureMap.group.input.name` |
| StructureMap.group.input.type | StructureMap.group.input.type | Equivalent | R5 `StructureMap.group.input.type` maps as Equivalent to R4 `StructureMap.group.input.type` |
| StructureMap.group.modifierExtension | StructureMap.group.modifierExtension | SourceIsBroaderThanTarget | R5 `StructureMap.group.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `StructureMap.group.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| StructureMap.group.name | StructureMap.group.name | Equivalent | R5 `StructureMap.group.name` maps as Equivalent to R4 `StructureMap.group.name` |
| StructureMap.group.rule | StructureMap.group.rule | RelatedTo | R5 `StructureMap.group.rule` maps as RelatedTo to R4 `StructureMap.group.rule` - rule made the element mandatory; rule increased the minimum cardinality from 0 to 1 |
| StructureMap.group.rule.dependent | StructureMap.group.rule.dependent | Equivalent | R5 `StructureMap.group.rule.dependent` maps as Equivalent to R4 `StructureMap.group.rule.dependent` |
| StructureMap.group.rule.dependent.extension | StructureMap.group.rule.dependent.extension | SourceIsBroaderThanTarget | R5 `StructureMap.group.rule.dependent.extension` maps as SourceIsBroaderThanTarget to R4 `StructureMap.group.rule.dependent.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| StructureMap.group.rule.dependent.id | StructureMap.group.rule.dependent.id | Equivalent | R5 `StructureMap.group.rule.dependent.id` maps as Equivalent to R4 `StructureMap.group.rule.dependent.id` |
| StructureMap.group.rule.dependent.modifierExtension | StructureMap.group.rule.dependent.modifierExtension | SourceIsBroaderThanTarget | R5 `StructureMap.group.rule.dependent.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `StructureMap.group.rule.dependent.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| StructureMap.group.rule.dependent.name | StructureMap.group.rule.dependent.name | Equivalent | R5 `StructureMap.group.rule.dependent.name` maps as Equivalent to R4 `StructureMap.group.rule.dependent.name` |
| StructureMap.group.rule.dependent.parameter | - | DoesNotExistInTarget | R5 `StructureMap.group.rule.dependent.parameter` does not appear in the target and has no mapping for `StructureMap`. |
| StructureMap.group.rule.documentation | StructureMap.group.rule.documentation | Equivalent | R5 `StructureMap.group.rule.documentation` maps as Equivalent to R4 `StructureMap.group.rule.documentation` |
| StructureMap.group.rule.extension | StructureMap.group.rule.extension | SourceIsBroaderThanTarget | R5 `StructureMap.group.rule.extension` maps as SourceIsBroaderThanTarget to R4 `StructureMap.group.rule.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| StructureMap.group.rule.id | StructureMap.group.rule.id | Equivalent | R5 `StructureMap.group.rule.id` maps as Equivalent to R4 `StructureMap.group.rule.id` |
| StructureMap.group.rule.modifierExtension | StructureMap.group.rule.modifierExtension | SourceIsBroaderThanTarget | R5 `StructureMap.group.rule.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `StructureMap.group.rule.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| StructureMap.group.rule.name | StructureMap.group.rule.name | RelatedTo | R5 `StructureMap.group.rule.name` maps as RelatedTo to R4 `StructureMap.group.rule.name` - name made the element mandatory; name increased the minimum cardinality from 0 to 1 |
| StructureMap.group.rule.rule | StructureMap.group.rule.rule | Equivalent | R5 `StructureMap.group.rule.rule` maps as Equivalent to R4 `StructureMap.group.rule.rule` |
| StructureMap.group.rule.source | StructureMap.group.rule.source | Equivalent | R5 `StructureMap.group.rule.source` maps as Equivalent to R4 `StructureMap.group.rule.source` |
| StructureMap.group.rule.source.check | StructureMap.group.rule.source.check | Equivalent | R5 `StructureMap.group.rule.source.check` maps as Equivalent to R4 `StructureMap.group.rule.source.check` |
| StructureMap.group.rule.source.condition | StructureMap.group.rule.source.condition | Equivalent | R5 `StructureMap.group.rule.source.condition` maps as Equivalent to R4 `StructureMap.group.rule.source.condition` |
| StructureMap.group.rule.source.context | StructureMap.group.rule.source.context | Equivalent | R5 `StructureMap.group.rule.source.context` maps as Equivalent to R4 `StructureMap.group.rule.source.context` |
| StructureMap.group.rule.source.defaultValue | - | DoesNotExistInTarget | R5 `StructureMap.group.rule.source.defaultValue` does not appear in the target and has no mapping for `StructureMap`. |
| StructureMap.group.rule.source.element | StructureMap.group.rule.source.element | Equivalent | R5 `StructureMap.group.rule.source.element` maps as Equivalent to R4 `StructureMap.group.rule.source.element` |
| StructureMap.group.rule.source.extension | StructureMap.group.rule.source.extension | SourceIsBroaderThanTarget | R5 `StructureMap.group.rule.source.extension` maps as SourceIsBroaderThanTarget to R4 `StructureMap.group.rule.source.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| StructureMap.group.rule.source.id | StructureMap.group.rule.source.id | Equivalent | R5 `StructureMap.group.rule.source.id` maps as Equivalent to R4 `StructureMap.group.rule.source.id` |
| StructureMap.group.rule.source.listMode | StructureMap.group.rule.source.listMode | Equivalent | R5 `StructureMap.group.rule.source.listMode` maps as Equivalent to R4 `StructureMap.group.rule.source.listMode` - listMode has compatible required binding for code type: http://hl7.org/fhir/ValueSet/map-source-list-mode|5.0.0 and http://hl7.org/fhir/ValueSet/map-source-list-mode|4.0.1 (Equivalent) |
| StructureMap.group.rule.source.logMessage | StructureMap.group.rule.source.logMessage | Equivalent | R5 `StructureMap.group.rule.source.logMessage` maps as Equivalent to R4 `StructureMap.group.rule.source.logMessage` |
| StructureMap.group.rule.source.max | StructureMap.group.rule.source.max | Equivalent | R5 `StructureMap.group.rule.source.max` maps as Equivalent to R4 `StructureMap.group.rule.source.max` |
| StructureMap.group.rule.source.min | StructureMap.group.rule.source.min | Equivalent | R5 `StructureMap.group.rule.source.min` maps as Equivalent to R4 `StructureMap.group.rule.source.min` |
| StructureMap.group.rule.source.modifierExtension | StructureMap.group.rule.source.modifierExtension | SourceIsBroaderThanTarget | R5 `StructureMap.group.rule.source.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `StructureMap.group.rule.source.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| StructureMap.group.rule.source.type | StructureMap.group.rule.source.type | Equivalent | R5 `StructureMap.group.rule.source.type` maps as Equivalent to R4 `StructureMap.group.rule.source.type` |
| StructureMap.group.rule.source.variable | StructureMap.group.rule.source.variable | Equivalent | R5 `StructureMap.group.rule.source.variable` maps as Equivalent to R4 `StructureMap.group.rule.source.variable` |
| StructureMap.group.rule.target | StructureMap.group.rule.target | Equivalent | R5 `StructureMap.group.rule.target` maps as Equivalent to R4 `StructureMap.group.rule.target` |
| StructureMap.group.rule.target.context | StructureMap.group.rule.target.context | SourceIsBroaderThanTarget | R5 `StructureMap.group.rule.target.context` maps as SourceIsBroaderThanTarget to R4 `StructureMap.group.rule.target.context` - context has change due to type change: R5 context string has no equivalent or mapped type in R4 context |
| StructureMap.group.rule.target.element | StructureMap.group.rule.target.element | Equivalent | R5 `StructureMap.group.rule.target.element` maps as Equivalent to R4 `StructureMap.group.rule.target.element` |
| StructureMap.group.rule.target.extension | StructureMap.group.rule.target.extension | SourceIsBroaderThanTarget | R5 `StructureMap.group.rule.target.extension` maps as SourceIsBroaderThanTarget to R4 `StructureMap.group.rule.target.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| StructureMap.group.rule.target.id | StructureMap.group.rule.target.id | Equivalent | R5 `StructureMap.group.rule.target.id` maps as Equivalent to R4 `StructureMap.group.rule.target.id` |
| StructureMap.group.rule.target.listMode | StructureMap.group.rule.target.listMode | Equivalent | R5 `StructureMap.group.rule.target.listMode` maps as Equivalent to R4 `StructureMap.group.rule.target.listMode` - listMode has compatible required binding for code type: http://hl7.org/fhir/ValueSet/map-target-list-mode|5.0.0 and http://hl7.org/fhir/ValueSet/map-target-list-mode|4.0.1 (Equivalent) |
| StructureMap.group.rule.target.listRuleId | StructureMap.group.rule.target.listRuleId | Equivalent | R5 `StructureMap.group.rule.target.listRuleId` maps as Equivalent to R4 `StructureMap.group.rule.target.listRuleId` |
| StructureMap.group.rule.target.modifierExtension | StructureMap.group.rule.target.modifierExtension | SourceIsBroaderThanTarget | R5 `StructureMap.group.rule.target.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `StructureMap.group.rule.target.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| StructureMap.group.rule.target.parameter | StructureMap.group.rule.target.parameter | Equivalent | R5 `StructureMap.group.rule.target.parameter` maps as Equivalent to R4 `StructureMap.group.rule.target.parameter` |
| StructureMap.group.rule.target.parameter.extension | StructureMap.group.rule.target.parameter.extension | SourceIsBroaderThanTarget | R5 `StructureMap.group.rule.target.parameter.extension` maps as SourceIsBroaderThanTarget to R4 `StructureMap.group.rule.target.parameter.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| StructureMap.group.rule.target.parameter.id | StructureMap.group.rule.target.parameter.id | Equivalent | R5 `StructureMap.group.rule.target.parameter.id` maps as Equivalent to R4 `StructureMap.group.rule.target.parameter.id` |
| StructureMap.group.rule.target.parameter.modifierExtension | StructureMap.group.rule.target.parameter.modifierExtension | SourceIsBroaderThanTarget | R5 `StructureMap.group.rule.target.parameter.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `StructureMap.group.rule.target.parameter.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| StructureMap.group.rule.target.parameter.value[x] | StructureMap.group.rule.target.parameter.value[x] | SourceIsBroaderThanTarget | R5 `StructureMap.group.rule.target.parameter.value[x]` maps as SourceIsBroaderThanTarget to R4 `StructureMap.group.rule.target.parameter.value[x]` - value[x] has change due to type change: R5 value[x] date has no equivalent or mapped type in R4 value[x]; value[x] has change due to type change: R5 value[x] time has no equivalent or mapped type in R4 value[x]; value[x] has change due to type change: R5 value[x] dateTime has no equivalent or mapped type in R4 value[x] |
| StructureMap.group.rule.target.transform | StructureMap.group.rule.target.transform | Equivalent | R5 `StructureMap.group.rule.target.transform` maps as Equivalent to R4 `StructureMap.group.rule.target.transform` - transform has compatible required binding for code type: http://hl7.org/fhir/ValueSet/map-transform|5.0.0 and http://hl7.org/fhir/ValueSet/map-transform|4.0.1 (Equivalent) |
| StructureMap.group.rule.target.variable | StructureMap.group.rule.target.variable | Equivalent | R5 `StructureMap.group.rule.target.variable` maps as Equivalent to R4 `StructureMap.group.rule.target.variable` |
| StructureMap.group.typeMode | StructureMap.group.typeMode | RelatedTo | R5 `StructureMap.group.typeMode` maps as RelatedTo to R4 `StructureMap.group.typeMode` - typeMode made the element mandatory; typeMode increased the minimum cardinality from 0 to 1; typeMode has compatible required binding for code type: http://hl7.org/fhir/ValueSet/map-group-type-mode|5.0.0 and http://hl7.org/fhir/ValueSet/map-group-type-mode|4.0.1 (Equivalent) |
| StructureMap.id | StructureMap.id | Equivalent | R5 `StructureMap.id` maps as Equivalent to R4 `StructureMap.id` |
| StructureMap.identifier | StructureMap.identifier | Equivalent | R5 `StructureMap.identifier` maps as Equivalent to R4 `StructureMap.identifier` |
| StructureMap.implicitRules | StructureMap.implicitRules | Equivalent | R5 `StructureMap.implicitRules` maps as Equivalent to R4 `StructureMap.implicitRules` |
| StructureMap.import | StructureMap.import | Equivalent | R5 `StructureMap.import` maps as Equivalent to R4 `StructureMap.import` |
| StructureMap.jurisdiction | StructureMap.jurisdiction | Equivalent | R5 `StructureMap.jurisdiction` maps as Equivalent to R4 `StructureMap.jurisdiction` |
| StructureMap.language | StructureMap.language | RelatedTo | R5 `StructureMap.language` maps as RelatedTo to R4 `StructureMap.language` - language changed the binding strength from Required to Preferred |
| StructureMap.meta | StructureMap.meta | Equivalent | R5 `StructureMap.meta` maps as Equivalent to R4 `StructureMap.meta` |
| StructureMap.modifierExtension | StructureMap.modifierExtension | SourceIsBroaderThanTarget | R5 `StructureMap.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `StructureMap.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| StructureMap.name | StructureMap.name | Equivalent | R5 `StructureMap.name` maps as Equivalent to R4 `StructureMap.name` |
| StructureMap.publisher | StructureMap.publisher | Equivalent | R5 `StructureMap.publisher` maps as Equivalent to R4 `StructureMap.publisher` |
| StructureMap.purpose | StructureMap.purpose | Equivalent | R5 `StructureMap.purpose` maps as Equivalent to R4 `StructureMap.purpose` |
| StructureMap.status | StructureMap.status | Equivalent | R5 `StructureMap.status` maps as Equivalent to R4 `StructureMap.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.0.1 (Equivalent) |
| StructureMap.structure | StructureMap.structure | Equivalent | R5 `StructureMap.structure` maps as Equivalent to R4 `StructureMap.structure` |
| StructureMap.structure.alias | StructureMap.structure.alias | Equivalent | R5 `StructureMap.structure.alias` maps as Equivalent to R4 `StructureMap.structure.alias` |
| StructureMap.structure.documentation | StructureMap.structure.documentation | Equivalent | R5 `StructureMap.structure.documentation` maps as Equivalent to R4 `StructureMap.structure.documentation` |
| StructureMap.structure.extension | StructureMap.structure.extension | SourceIsBroaderThanTarget | R5 `StructureMap.structure.extension` maps as SourceIsBroaderThanTarget to R4 `StructureMap.structure.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| StructureMap.structure.id | StructureMap.structure.id | Equivalent | R5 `StructureMap.structure.id` maps as Equivalent to R4 `StructureMap.structure.id` |
| StructureMap.structure.mode | StructureMap.structure.mode | Equivalent | R5 `StructureMap.structure.mode` maps as Equivalent to R4 `StructureMap.structure.mode` - mode has compatible required binding for code type: http://hl7.org/fhir/ValueSet/map-model-mode|5.0.0 and http://hl7.org/fhir/ValueSet/map-model-mode|4.0.1 (Equivalent) |
| StructureMap.structure.modifierExtension | StructureMap.structure.modifierExtension | SourceIsBroaderThanTarget | R5 `StructureMap.structure.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `StructureMap.structure.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| StructureMap.structure.url | StructureMap.structure.url | Equivalent | R5 `StructureMap.structure.url` maps as Equivalent to R4 `StructureMap.structure.url` |
| StructureMap.text | StructureMap.text | Equivalent | R5 `StructureMap.text` maps as Equivalent to R4 `StructureMap.text` |
| StructureMap.title | StructureMap.title | Equivalent | R5 `StructureMap.title` maps as Equivalent to R4 `StructureMap.title` |
| StructureMap.url | StructureMap.url | Equivalent | R5 `StructureMap.url` maps as Equivalent to R4 `StructureMap.url` |
| StructureMap.useContext | StructureMap.useContext | Equivalent | R5 `StructureMap.useContext` maps as Equivalent to R4 `StructureMap.useContext` |
| StructureMap.version | StructureMap.version | Equivalent | R5 `StructureMap.version` maps as Equivalent to R4 `StructureMap.version` |
| StructureMap.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `StructureMap.versionAlgorithm[x]` does not appear in the target and has no mapping for `StructureMap`. |

