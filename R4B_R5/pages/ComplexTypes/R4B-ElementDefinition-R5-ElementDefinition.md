Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:03 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ElementDefinition |  | Base StructureDefinition for ElementDefinition Type: Captures constraints on each element within the resource, profile, or extension. | 84 | 65 |
| Target | ElementDefinition |  | ElementDefinition Type: Captures constraints on each element within the resource, profile, or extension. | 95 | 74 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 43 |
RelatedTo | 40 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ElementDefinition | ElementDefinition | Equivalent | R4B `ElementDefinition` maps as Equivalent to R5 `ElementDefinition` |
| ElementDefinition.alias | ElementDefinition.alias | Equivalent | R4B `ElementDefinition.alias` maps as Equivalent to R5 `ElementDefinition.alias` |
| ElementDefinition.base | ElementDefinition.base | Equivalent | R4B `ElementDefinition.base` maps as Equivalent to R5 `ElementDefinition.base` |
| ElementDefinition.base.extension | ElementDefinition.base.extension | Equivalent | R4B `ElementDefinition.base.extension` maps as Equivalent to R5 `ElementDefinition.base.extension` |
| ElementDefinition.base.id | ElementDefinition.base.id | Equivalent | R4B `ElementDefinition.base.id` maps as Equivalent to R5 `ElementDefinition.base.id` |
| ElementDefinition.base.max | ElementDefinition.base.max | Equivalent | R4B `ElementDefinition.base.max` maps as Equivalent to R5 `ElementDefinition.base.max` |
| ElementDefinition.base.min | ElementDefinition.base.min | Equivalent | R4B `ElementDefinition.base.min` maps as Equivalent to R5 `ElementDefinition.base.min` |
| ElementDefinition.base.path | ElementDefinition.base.path | Equivalent | R4B `ElementDefinition.base.path` maps as Equivalent to R5 `ElementDefinition.base.path` |
| ElementDefinition.binding | ElementDefinition.binding | Equivalent | R4B `ElementDefinition.binding` maps as Equivalent to R5 `ElementDefinition.binding` |
| ElementDefinition.binding.description | ElementDefinition.binding.description | SourceIsBroaderThanTarget | R4B `ElementDefinition.binding.description` maps as SourceIsBroaderThanTarget to R5 `ElementDefinition.binding.description` - description has change due to type change: R4B description string has no equivalent or mapped type in R5 description |
| ElementDefinition.binding.extension | ElementDefinition.binding.extension | Equivalent | R4B `ElementDefinition.binding.extension` maps as Equivalent to R5 `ElementDefinition.binding.extension` |
| ElementDefinition.binding.id | ElementDefinition.binding.id | Equivalent | R4B `ElementDefinition.binding.id` maps as Equivalent to R5 `ElementDefinition.binding.id` |
| ElementDefinition.binding.strength | ElementDefinition.binding.strength | Equivalent | R4B `ElementDefinition.binding.strength` maps as Equivalent to R5 `ElementDefinition.binding.strength` - strength has compatible required binding for code type: http://hl7.org/fhir/ValueSet/binding-strength|4.3.0 and http://hl7.org/fhir/ValueSet/binding-strength|5.0.0 (Equivalent) |
| ElementDefinition.binding.valueSet | ElementDefinition.binding.valueSet | Equivalent | R4B `ElementDefinition.binding.valueSet` maps as Equivalent to R5 `ElementDefinition.binding.valueSet` |
| ElementDefinition.code | ElementDefinition.code | Equivalent | R4B `ElementDefinition.code` maps as Equivalent to R5 `ElementDefinition.code` |
| ElementDefinition.comment | ElementDefinition.comment | Equivalent | R4B `ElementDefinition.comment` maps as Equivalent to R5 `ElementDefinition.comment` |
| ElementDefinition.condition | ElementDefinition.condition | Equivalent | R4B `ElementDefinition.condition` maps as Equivalent to R5 `ElementDefinition.condition` |
| ElementDefinition.constraint | ElementDefinition.constraint | Equivalent | R4B `ElementDefinition.constraint` maps as Equivalent to R5 `ElementDefinition.constraint` |
| ElementDefinition.constraint.expression | ElementDefinition.constraint.expression | Equivalent | R4B `ElementDefinition.constraint.expression` maps as Equivalent to R5 `ElementDefinition.constraint.expression` |
| ElementDefinition.constraint.extension | ElementDefinition.constraint.extension | Equivalent | R4B `ElementDefinition.constraint.extension` maps as Equivalent to R5 `ElementDefinition.constraint.extension` |
| ElementDefinition.constraint.human | ElementDefinition.constraint.human | Equivalent | R4B `ElementDefinition.constraint.human` maps as Equivalent to R5 `ElementDefinition.constraint.human` |
| ElementDefinition.constraint.id | ElementDefinition.constraint.id | Equivalent | R4B `ElementDefinition.constraint.id` maps as Equivalent to R5 `ElementDefinition.constraint.id` |
| ElementDefinition.constraint.key | ElementDefinition.constraint.key | Equivalent | R4B `ElementDefinition.constraint.key` maps as Equivalent to R5 `ElementDefinition.constraint.key` |
| ElementDefinition.constraint.requirements | ElementDefinition.constraint.requirements | SourceIsBroaderThanTarget | R4B `ElementDefinition.constraint.requirements` maps as SourceIsBroaderThanTarget to R5 `ElementDefinition.constraint.requirements` - requirements has change due to type change: R4B requirements string has no equivalent or mapped type in R5 requirements |
| ElementDefinition.constraint.severity | ElementDefinition.constraint.severity | Equivalent | R4B `ElementDefinition.constraint.severity` maps as Equivalent to R5 `ElementDefinition.constraint.severity` - severity has compatible required binding for code type: http://hl7.org/fhir/ValueSet/constraint-severity|4.3.0 and http://hl7.org/fhir/ValueSet/constraint-severity|5.0.0 (Equivalent) |
| ElementDefinition.constraint.source | ElementDefinition.constraint.source | Equivalent | R4B `ElementDefinition.constraint.source` maps as Equivalent to R5 `ElementDefinition.constraint.source` |
| ElementDefinition.constraint.xpath | - | DoesNotExistInTarget | R4B `ElementDefinition.constraint.xpath` does not appear in the target and has no mapping for `ElementDefinition`. |
| ElementDefinition.contentReference | ElementDefinition.contentReference | Equivalent | R4B `ElementDefinition.contentReference` maps as Equivalent to R5 `ElementDefinition.contentReference` |
| ElementDefinition.defaultValue[x] | ElementDefinition.defaultValue[x] | RelatedTo | R4B `ElementDefinition.defaultValue[x]` maps as RelatedTo to R5 `ElementDefinition.defaultValue[x]` - defaultValue[x] has change due to type change: R4B `defaultValue[x]` `integer` maps as SourceIsNarrowerThanTarget for R5 `defaultValue[x]`; defaultValue[x] has change due to type change: R4B `defaultValue[x]` `positiveInt` maps as SourceIsNarrowerThanTarget for R5 `defaultValue[x]`; defaultValue[x] has change due to type change: R4B `defaultValue[x]` `unsignedInt` maps as SourceIsNarrowerThanTarget for R5 `defaultValue[x]`; defaultValue[x] has change due to type change: R4B defaultValue[x] Contributor has no equivalent or mapped type in R5 defaultValue[x] |
| ElementDefinition.definition | ElementDefinition.definition | Equivalent | R4B `ElementDefinition.definition` maps as Equivalent to R5 `ElementDefinition.definition` |
| ElementDefinition.example | ElementDefinition.example | Equivalent | R4B `ElementDefinition.example` maps as Equivalent to R5 `ElementDefinition.example` |
| ElementDefinition.example.extension | ElementDefinition.example.extension | Equivalent | R4B `ElementDefinition.example.extension` maps as Equivalent to R5 `ElementDefinition.example.extension` |
| ElementDefinition.example.id | ElementDefinition.example.id | Equivalent | R4B `ElementDefinition.example.id` maps as Equivalent to R5 `ElementDefinition.example.id` |
| ElementDefinition.example.label | ElementDefinition.example.label | Equivalent | R4B `ElementDefinition.example.label` maps as Equivalent to R5 `ElementDefinition.example.label` |
| ElementDefinition.example.value[x] | ElementDefinition.example.value[x] | RelatedTo | R4B `ElementDefinition.example.value[x]` maps as RelatedTo to R5 `ElementDefinition.example.value[x]` - value[x] has change due to type change: R4B `value[x]` `integer` maps as SourceIsNarrowerThanTarget for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `positiveInt` maps as SourceIsNarrowerThanTarget for R5 `value[x]`; value[x] has change due to type change: R4B `value[x]` `unsignedInt` maps as SourceIsNarrowerThanTarget for R5 `value[x]`; value[x] has change due to type change: R4B value[x] Contributor has no equivalent or mapped type in R5 value[x] |
| ElementDefinition.extension | ElementDefinition.extension | Equivalent | R4B `ElementDefinition.extension` maps as Equivalent to R5 `ElementDefinition.extension` |
| ElementDefinition.fixed[x] | ElementDefinition.fixed[x] | RelatedTo | R4B `ElementDefinition.fixed[x]` maps as RelatedTo to R5 `ElementDefinition.fixed[x]` - fixed[x] has change due to type change: R4B `fixed[x]` `integer` maps as SourceIsNarrowerThanTarget for R5 `fixed[x]`; fixed[x] has change due to type change: R4B `fixed[x]` `positiveInt` maps as SourceIsNarrowerThanTarget for R5 `fixed[x]`; fixed[x] has change due to type change: R4B `fixed[x]` `unsignedInt` maps as SourceIsNarrowerThanTarget for R5 `fixed[x]`; fixed[x] has change due to type change: R4B fixed[x] Contributor has no equivalent or mapped type in R5 fixed[x] |
| ElementDefinition.id | ElementDefinition.id | Equivalent | R4B `ElementDefinition.id` maps as Equivalent to R5 `ElementDefinition.id` |
| ElementDefinition.isModifier | ElementDefinition.isModifier | Equivalent | R4B `ElementDefinition.isModifier` maps as Equivalent to R5 `ElementDefinition.isModifier` |
| ElementDefinition.isModifierReason | ElementDefinition.isModifierReason | Equivalent | R4B `ElementDefinition.isModifierReason` maps as Equivalent to R5 `ElementDefinition.isModifierReason` |
| ElementDefinition.isSummary | ElementDefinition.isSummary | Equivalent | R4B `ElementDefinition.isSummary` maps as Equivalent to R5 `ElementDefinition.isSummary` |
| ElementDefinition.label | ElementDefinition.label | Equivalent | R4B `ElementDefinition.label` maps as Equivalent to R5 `ElementDefinition.label` |
| ElementDefinition.mapping | ElementDefinition.mapping | Equivalent | R4B `ElementDefinition.mapping` maps as Equivalent to R5 `ElementDefinition.mapping` |
| ElementDefinition.mapping.comment | ElementDefinition.mapping.comment | SourceIsBroaderThanTarget | R4B `ElementDefinition.mapping.comment` maps as SourceIsBroaderThanTarget to R5 `ElementDefinition.mapping.comment` - comment has change due to type change: R4B comment string has no equivalent or mapped type in R5 comment |
| ElementDefinition.mapping.extension | ElementDefinition.mapping.extension | Equivalent | R4B `ElementDefinition.mapping.extension` maps as Equivalent to R5 `ElementDefinition.mapping.extension` |
| ElementDefinition.mapping.id | ElementDefinition.mapping.id | Equivalent | R4B `ElementDefinition.mapping.id` maps as Equivalent to R5 `ElementDefinition.mapping.id` |
| ElementDefinition.mapping.identity | ElementDefinition.mapping.identity | Equivalent | R4B `ElementDefinition.mapping.identity` maps as Equivalent to R5 `ElementDefinition.mapping.identity` |
| ElementDefinition.mapping.language | ElementDefinition.mapping.language | Equivalent | R4B `ElementDefinition.mapping.language` maps as Equivalent to R5 `ElementDefinition.mapping.language` - language using http://hl7.org/fhir/ValueSet/mimetypes is exempted and assumed equivalent |
| ElementDefinition.mapping.map | ElementDefinition.mapping.map | Equivalent | R4B `ElementDefinition.mapping.map` maps as Equivalent to R5 `ElementDefinition.mapping.map` |
| ElementDefinition.max | ElementDefinition.max | Equivalent | R4B `ElementDefinition.max` maps as Equivalent to R5 `ElementDefinition.max` |
| ElementDefinition.maxLength | ElementDefinition.maxLength | Equivalent | R4B `ElementDefinition.maxLength` maps as Equivalent to R5 `ElementDefinition.maxLength` |
| ElementDefinition.maxValue[x] | ElementDefinition.maxValue[x] | SourceIsNarrowerThanTarget | R4B `ElementDefinition.maxValue[x]` maps as SourceIsNarrowerThanTarget to R5 `ElementDefinition.maxValue[x]` - maxValue[x] has change due to type change: R4B `maxValue[x]` `integer` maps as SourceIsNarrowerThanTarget for R5 `maxValue[x]`; maxValue[x] has change due to type change: R4B `maxValue[x]` `positiveInt` maps as SourceIsNarrowerThanTarget for R5 `maxValue[x]`; maxValue[x] has change due to type change: R4B `maxValue[x]` `unsignedInt` maps as SourceIsNarrowerThanTarget for R5 `maxValue[x]` |
| ElementDefinition.meaningWhenMissing | ElementDefinition.meaningWhenMissing | Equivalent | R4B `ElementDefinition.meaningWhenMissing` maps as Equivalent to R5 `ElementDefinition.meaningWhenMissing` |
| ElementDefinition.min | ElementDefinition.min | Equivalent | R4B `ElementDefinition.min` maps as Equivalent to R5 `ElementDefinition.min` |
| ElementDefinition.minValue[x] | ElementDefinition.minValue[x] | SourceIsNarrowerThanTarget | R4B `ElementDefinition.minValue[x]` maps as SourceIsNarrowerThanTarget to R5 `ElementDefinition.minValue[x]` - minValue[x] has change due to type change: R4B `minValue[x]` `integer` maps as SourceIsNarrowerThanTarget for R5 `minValue[x]`; minValue[x] has change due to type change: R4B `minValue[x]` `positiveInt` maps as SourceIsNarrowerThanTarget for R5 `minValue[x]`; minValue[x] has change due to type change: R4B `minValue[x]` `unsignedInt` maps as SourceIsNarrowerThanTarget for R5 `minValue[x]` |
| ElementDefinition.modifierExtension | ElementDefinition.modifierExtension | Equivalent | R4B `ElementDefinition.modifierExtension` maps as Equivalent to R5 `ElementDefinition.modifierExtension` |
| ElementDefinition.mustSupport | ElementDefinition.mustSupport | Equivalent | R4B `ElementDefinition.mustSupport` maps as Equivalent to R5 `ElementDefinition.mustSupport` |
| ElementDefinition.orderMeaning | ElementDefinition.orderMeaning | Equivalent | R4B `ElementDefinition.orderMeaning` maps as Equivalent to R5 `ElementDefinition.orderMeaning` |
| ElementDefinition.path | ElementDefinition.path | Equivalent | R4B `ElementDefinition.path` maps as Equivalent to R5 `ElementDefinition.path` |
| ElementDefinition.pattern[x] | ElementDefinition.pattern[x] | RelatedTo | R4B `ElementDefinition.pattern[x]` maps as RelatedTo to R5 `ElementDefinition.pattern[x]` - pattern[x] has change due to type change: R4B `pattern[x]` `integer` maps as SourceIsNarrowerThanTarget for R5 `pattern[x]`; pattern[x] has change due to type change: R4B `pattern[x]` `positiveInt` maps as SourceIsNarrowerThanTarget for R5 `pattern[x]`; pattern[x] has change due to type change: R4B `pattern[x]` `unsignedInt` maps as SourceIsNarrowerThanTarget for R5 `pattern[x]`; pattern[x] has change due to type change: R4B pattern[x] Contributor has no equivalent or mapped type in R5 pattern[x] |
| ElementDefinition.representation | ElementDefinition.representation | Equivalent | R4B `ElementDefinition.representation` maps as Equivalent to R5 `ElementDefinition.representation` - representation has compatible required binding for code type: http://hl7.org/fhir/ValueSet/property-representation|4.3.0 and http://hl7.org/fhir/ValueSet/property-representation|5.0.0 (Equivalent) |
| ElementDefinition.requirements | ElementDefinition.requirements | Equivalent | R4B `ElementDefinition.requirements` maps as Equivalent to R5 `ElementDefinition.requirements` |
| ElementDefinition.short | ElementDefinition.short | Equivalent | R4B `ElementDefinition.short` maps as Equivalent to R5 `ElementDefinition.short` |
| ElementDefinition.sliceIsConstraining | ElementDefinition.sliceIsConstraining | Equivalent | R4B `ElementDefinition.sliceIsConstraining` maps as Equivalent to R5 `ElementDefinition.sliceIsConstraining` |
| ElementDefinition.sliceName | ElementDefinition.sliceName | Equivalent | R4B `ElementDefinition.sliceName` maps as Equivalent to R5 `ElementDefinition.sliceName` |
| ElementDefinition.slicing | ElementDefinition.slicing | Equivalent | R4B `ElementDefinition.slicing` maps as Equivalent to R5 `ElementDefinition.slicing` |
| ElementDefinition.slicing.description | ElementDefinition.slicing.description | Equivalent | R4B `ElementDefinition.slicing.description` maps as Equivalent to R5 `ElementDefinition.slicing.description` |
| ElementDefinition.slicing.discriminator | ElementDefinition.slicing.discriminator | Equivalent | R4B `ElementDefinition.slicing.discriminator` maps as Equivalent to R5 `ElementDefinition.slicing.discriminator` |
| ElementDefinition.slicing.discriminator.extension | ElementDefinition.slicing.discriminator.extension | Equivalent | R4B `ElementDefinition.slicing.discriminator.extension` maps as Equivalent to R5 `ElementDefinition.slicing.discriminator.extension` |
| ElementDefinition.slicing.discriminator.id | ElementDefinition.slicing.discriminator.id | Equivalent | R4B `ElementDefinition.slicing.discriminator.id` maps as Equivalent to R5 `ElementDefinition.slicing.discriminator.id` |
| ElementDefinition.slicing.discriminator.path | ElementDefinition.slicing.discriminator.path | Equivalent | R4B `ElementDefinition.slicing.discriminator.path` maps as Equivalent to R5 `ElementDefinition.slicing.discriminator.path` |
| ElementDefinition.slicing.discriminator.type | ElementDefinition.slicing.discriminator.type | Equivalent | R4B `ElementDefinition.slicing.discriminator.type` maps as Equivalent to R5 `ElementDefinition.slicing.discriminator.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/discriminator-type|4.3.0 and http://hl7.org/fhir/ValueSet/discriminator-type|5.0.0 (Equivalent) |
| ElementDefinition.slicing.extension | ElementDefinition.slicing.extension | Equivalent | R4B `ElementDefinition.slicing.extension` maps as Equivalent to R5 `ElementDefinition.slicing.extension` |
| ElementDefinition.slicing.id | ElementDefinition.slicing.id | Equivalent | R4B `ElementDefinition.slicing.id` maps as Equivalent to R5 `ElementDefinition.slicing.id` |
| ElementDefinition.slicing.ordered | ElementDefinition.slicing.ordered | Equivalent | R4B `ElementDefinition.slicing.ordered` maps as Equivalent to R5 `ElementDefinition.slicing.ordered` |
| ElementDefinition.slicing.rules | ElementDefinition.slicing.rules | Equivalent | R4B `ElementDefinition.slicing.rules` maps as Equivalent to R5 `ElementDefinition.slicing.rules` - rules has compatible required binding for code type: http://hl7.org/fhir/ValueSet/resource-slicing-rules|4.3.0 and http://hl7.org/fhir/ValueSet/resource-slicing-rules|5.0.0 (Equivalent) |
| ElementDefinition.type | ElementDefinition.type | Equivalent | R4B `ElementDefinition.type` maps as Equivalent to R5 `ElementDefinition.type` |
| ElementDefinition.type.aggregation | ElementDefinition.type.aggregation | Equivalent | R4B `ElementDefinition.type.aggregation` maps as Equivalent to R5 `ElementDefinition.type.aggregation` - aggregation has compatible required binding for code type: http://hl7.org/fhir/ValueSet/resource-aggregation-mode|4.3.0 and http://hl7.org/fhir/ValueSet/resource-aggregation-mode|5.0.0 (Equivalent) |
| ElementDefinition.type.code | ElementDefinition.type.code | Equivalent | R4B `ElementDefinition.type.code` maps as Equivalent to R5 `ElementDefinition.type.code` |
| ElementDefinition.type.extension | ElementDefinition.type.extension | Equivalent | R4B `ElementDefinition.type.extension` maps as Equivalent to R5 `ElementDefinition.type.extension` |
| ElementDefinition.type.id | ElementDefinition.type.id | Equivalent | R4B `ElementDefinition.type.id` maps as Equivalent to R5 `ElementDefinition.type.id` |
| ElementDefinition.type.profile | ElementDefinition.type.profile | Equivalent | R4B `ElementDefinition.type.profile` maps as Equivalent to R5 `ElementDefinition.type.profile` |
| ElementDefinition.type.targetProfile | ElementDefinition.type.targetProfile | Equivalent | R4B `ElementDefinition.type.targetProfile` maps as Equivalent to R5 `ElementDefinition.type.targetProfile` |
| ElementDefinition.type.versioning | ElementDefinition.type.versioning | Equivalent | R4B `ElementDefinition.type.versioning` maps as Equivalent to R5 `ElementDefinition.type.versioning` - versioning has compatible required binding for code type: http://hl7.org/fhir/ValueSet/reference-version-rules|4.3.0 and http://hl7.org/fhir/ValueSet/reference-version-rules|5.0.0 (Equivalent) |

