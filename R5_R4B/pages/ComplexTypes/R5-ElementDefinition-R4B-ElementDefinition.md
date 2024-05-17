Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | ElementDefinition |  | ElementDefinition Type: Captures constraints on each element within the resource, profile, or extension. | 95 | 74 |
| Target | ElementDefinition |  | Base StructureDefinition for ElementDefinition Type: Captures constraints on each element within the resource, profile, or extension. | 84 | 65 |


Comparison Result: SourceIsBroaderThanTarget


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 12 |
Equivalent | 43 |
SourceIsBroaderThanTarget | 40 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| ElementDefinition | ElementDefinition | Equivalent | R5 `ElementDefinition` maps as Equivalent to R4B `ElementDefinition` |
| ElementDefinition.alias | ElementDefinition.alias | Equivalent | R5 `ElementDefinition.alias` maps as Equivalent to R4B `ElementDefinition.alias` |
| ElementDefinition.base | ElementDefinition.base | Equivalent | R5 `ElementDefinition.base` maps as Equivalent to R4B `ElementDefinition.base` |
| ElementDefinition.base.extension | ElementDefinition.base.extension | Equivalent | R5 `ElementDefinition.base.extension` maps as Equivalent to R4B `ElementDefinition.base.extension` |
| ElementDefinition.base.id | ElementDefinition.base.id | Equivalent | R5 `ElementDefinition.base.id` maps as Equivalent to R4B `ElementDefinition.base.id` |
| ElementDefinition.base.max | ElementDefinition.base.max | Equivalent | R5 `ElementDefinition.base.max` maps as Equivalent to R4B `ElementDefinition.base.max` |
| ElementDefinition.base.min | ElementDefinition.base.min | Equivalent | R5 `ElementDefinition.base.min` maps as Equivalent to R4B `ElementDefinition.base.min` |
| ElementDefinition.base.path | ElementDefinition.base.path | Equivalent | R5 `ElementDefinition.base.path` maps as Equivalent to R4B `ElementDefinition.base.path` |
| ElementDefinition.binding | ElementDefinition.binding | Equivalent | R5 `ElementDefinition.binding` maps as Equivalent to R4B `ElementDefinition.binding` |
| ElementDefinition.binding.additional | - | DoesNotExistInTarget | R5 `ElementDefinition.binding.additional` does not appear in the target and has no mapping for `ElementDefinition`. |
| ElementDefinition.binding.additional.any | - | DoesNotExistInTarget | R5 `ElementDefinition.binding.additional.any` does not appear in the target and has no mapping for `ElementDefinition`. |
| ElementDefinition.binding.additional.documentation | - | DoesNotExistInTarget | R5 `ElementDefinition.binding.additional.documentation` does not appear in the target and has no mapping for `ElementDefinition`. |
| ElementDefinition.binding.additional.extension | - | DoesNotExistInTarget | R5 `ElementDefinition.binding.additional.extension` does not appear in the target and has no mapping for `ElementDefinition`. |
| ElementDefinition.binding.additional.id | - | DoesNotExistInTarget | R5 `ElementDefinition.binding.additional.id` does not appear in the target and has no mapping for `ElementDefinition`. |
| ElementDefinition.binding.additional.purpose | - | DoesNotExistInTarget | R5 `ElementDefinition.binding.additional.purpose` does not appear in the target and has no mapping for `ElementDefinition`. |
| ElementDefinition.binding.additional.shortDoco | - | DoesNotExistInTarget | R5 `ElementDefinition.binding.additional.shortDoco` does not appear in the target and has no mapping for `ElementDefinition`. |
| ElementDefinition.binding.additional.usage | - | DoesNotExistInTarget | R5 `ElementDefinition.binding.additional.usage` does not appear in the target and has no mapping for `ElementDefinition`. |
| ElementDefinition.binding.additional.valueSet | - | DoesNotExistInTarget | R5 `ElementDefinition.binding.additional.valueSet` does not appear in the target and has no mapping for `ElementDefinition`. |
| ElementDefinition.binding.description | ElementDefinition.binding.description | SourceIsBroaderThanTarget | R5 `ElementDefinition.binding.description` maps as SourceIsBroaderThanTarget to R4B `ElementDefinition.binding.description` - description has change due to type change: R5 description markdown has no equivalent or mapped type in R4B description |
| ElementDefinition.binding.extension | ElementDefinition.binding.extension | Equivalent | R5 `ElementDefinition.binding.extension` maps as Equivalent to R4B `ElementDefinition.binding.extension` |
| ElementDefinition.binding.id | ElementDefinition.binding.id | Equivalent | R5 `ElementDefinition.binding.id` maps as Equivalent to R4B `ElementDefinition.binding.id` |
| ElementDefinition.binding.strength | ElementDefinition.binding.strength | Equivalent | R5 `ElementDefinition.binding.strength` maps as Equivalent to R4B `ElementDefinition.binding.strength` - strength has compatible required binding for code type: http://hl7.org/fhir/ValueSet/binding-strength|5.0.0 and http://hl7.org/fhir/ValueSet/binding-strength|4.3.0 (Equivalent) |
| ElementDefinition.binding.valueSet | ElementDefinition.binding.valueSet | Equivalent | R5 `ElementDefinition.binding.valueSet` maps as Equivalent to R4B `ElementDefinition.binding.valueSet` |
| ElementDefinition.code | ElementDefinition.code | Equivalent | R5 `ElementDefinition.code` maps as Equivalent to R4B `ElementDefinition.code` |
| ElementDefinition.comment | ElementDefinition.comment | Equivalent | R5 `ElementDefinition.comment` maps as Equivalent to R4B `ElementDefinition.comment` |
| ElementDefinition.condition | ElementDefinition.condition | Equivalent | R5 `ElementDefinition.condition` maps as Equivalent to R4B `ElementDefinition.condition` |
| ElementDefinition.constraint | ElementDefinition.constraint | Equivalent | R5 `ElementDefinition.constraint` maps as Equivalent to R4B `ElementDefinition.constraint` |
| ElementDefinition.constraint.expression | ElementDefinition.constraint.expression | Equivalent | R5 `ElementDefinition.constraint.expression` maps as Equivalent to R4B `ElementDefinition.constraint.expression` |
| ElementDefinition.constraint.extension | ElementDefinition.constraint.extension | Equivalent | R5 `ElementDefinition.constraint.extension` maps as Equivalent to R4B `ElementDefinition.constraint.extension` |
| ElementDefinition.constraint.human | ElementDefinition.constraint.human | Equivalent | R5 `ElementDefinition.constraint.human` maps as Equivalent to R4B `ElementDefinition.constraint.human` |
| ElementDefinition.constraint.id | ElementDefinition.constraint.id | Equivalent | R5 `ElementDefinition.constraint.id` maps as Equivalent to R4B `ElementDefinition.constraint.id` |
| ElementDefinition.constraint.key | ElementDefinition.constraint.key | Equivalent | R5 `ElementDefinition.constraint.key` maps as Equivalent to R4B `ElementDefinition.constraint.key` |
| ElementDefinition.constraint.requirements | ElementDefinition.constraint.requirements | SourceIsBroaderThanTarget | R5 `ElementDefinition.constraint.requirements` maps as SourceIsBroaderThanTarget to R4B `ElementDefinition.constraint.requirements` - requirements has change due to type change: R5 requirements markdown has no equivalent or mapped type in R4B requirements |
| ElementDefinition.constraint.severity | ElementDefinition.constraint.severity | Equivalent | R5 `ElementDefinition.constraint.severity` maps as Equivalent to R4B `ElementDefinition.constraint.severity` - severity has compatible required binding for code type: http://hl7.org/fhir/ValueSet/constraint-severity|5.0.0 and http://hl7.org/fhir/ValueSet/constraint-severity|4.3.0 (Equivalent) |
| ElementDefinition.constraint.source | ElementDefinition.constraint.source | Equivalent | R5 `ElementDefinition.constraint.source` maps as Equivalent to R4B `ElementDefinition.constraint.source` |
| ElementDefinition.constraint.suppress | - | DoesNotExistInTarget | R5 `ElementDefinition.constraint.suppress` does not appear in the target and has no mapping for `ElementDefinition`. |
| ElementDefinition.contentReference | ElementDefinition.contentReference | Equivalent | R5 `ElementDefinition.contentReference` maps as Equivalent to R4B `ElementDefinition.contentReference` |
| ElementDefinition.defaultValue[x] | ElementDefinition.defaultValue[x] | SourceIsBroaderThanTarget | R5 `ElementDefinition.defaultValue[x]` maps as SourceIsBroaderThanTarget to R4B `ElementDefinition.defaultValue[x]` - defaultValue[x] has change due to type change: R5 defaultValue[x] integer64 has no equivalent or mapped type in R4B defaultValue[x]; defaultValue[x] has change due to type change: R5 type Availability does not exist in R4B; defaultValue[x] has change due to type change: R5 type ExtendedContactDetail does not exist in R4B; defaultValue[x] has change due to type change: R5 defaultValue[x] Meta has no equivalent or mapped type in R4B defaultValue[x] |
| ElementDefinition.definition | ElementDefinition.definition | Equivalent | R5 `ElementDefinition.definition` maps as Equivalent to R4B `ElementDefinition.definition` |
| ElementDefinition.example | ElementDefinition.example | Equivalent | R5 `ElementDefinition.example` maps as Equivalent to R4B `ElementDefinition.example` |
| ElementDefinition.example.extension | ElementDefinition.example.extension | Equivalent | R5 `ElementDefinition.example.extension` maps as Equivalent to R4B `ElementDefinition.example.extension` |
| ElementDefinition.example.id | ElementDefinition.example.id | Equivalent | R5 `ElementDefinition.example.id` maps as Equivalent to R4B `ElementDefinition.example.id` |
| ElementDefinition.example.label | ElementDefinition.example.label | Equivalent | R5 `ElementDefinition.example.label` maps as Equivalent to R4B `ElementDefinition.example.label` |
| ElementDefinition.example.value[x] | ElementDefinition.example.value[x] | SourceIsBroaderThanTarget | R5 `ElementDefinition.example.value[x]` maps as SourceIsBroaderThanTarget to R4B `ElementDefinition.example.value[x]` - value[x] has change due to type change: R5 value[x] integer64 has no equivalent or mapped type in R4B value[x]; value[x] has change due to type change: R5 type Availability does not exist in R4B; value[x] has change due to type change: R5 type ExtendedContactDetail does not exist in R4B; value[x] has change due to type change: R5 value[x] Meta has no equivalent or mapped type in R4B value[x] |
| ElementDefinition.extension | ElementDefinition.extension | Equivalent | R5 `ElementDefinition.extension` maps as Equivalent to R4B `ElementDefinition.extension` |
| ElementDefinition.fixed[x] | ElementDefinition.fixed[x] | SourceIsBroaderThanTarget | R5 `ElementDefinition.fixed[x]` maps as SourceIsBroaderThanTarget to R4B `ElementDefinition.fixed[x]` - fixed[x] has change due to type change: R5 fixed[x] integer64 has no equivalent or mapped type in R4B fixed[x]; fixed[x] has change due to type change: R5 type Availability does not exist in R4B; fixed[x] has change due to type change: R5 type ExtendedContactDetail does not exist in R4B; fixed[x] has change due to type change: R5 fixed[x] Meta has no equivalent or mapped type in R4B fixed[x] |
| ElementDefinition.id | ElementDefinition.id | Equivalent | R5 `ElementDefinition.id` maps as Equivalent to R4B `ElementDefinition.id` |
| ElementDefinition.isModifier | ElementDefinition.isModifier | Equivalent | R5 `ElementDefinition.isModifier` maps as Equivalent to R4B `ElementDefinition.isModifier` |
| ElementDefinition.isModifierReason | ElementDefinition.isModifierReason | Equivalent | R5 `ElementDefinition.isModifierReason` maps as Equivalent to R4B `ElementDefinition.isModifierReason` |
| ElementDefinition.isSummary | ElementDefinition.isSummary | Equivalent | R5 `ElementDefinition.isSummary` maps as Equivalent to R4B `ElementDefinition.isSummary` |
| ElementDefinition.label | ElementDefinition.label | Equivalent | R5 `ElementDefinition.label` maps as Equivalent to R4B `ElementDefinition.label` |
| ElementDefinition.mapping | ElementDefinition.mapping | Equivalent | R5 `ElementDefinition.mapping` maps as Equivalent to R4B `ElementDefinition.mapping` |
| ElementDefinition.mapping.comment | ElementDefinition.mapping.comment | SourceIsBroaderThanTarget | R5 `ElementDefinition.mapping.comment` maps as SourceIsBroaderThanTarget to R4B `ElementDefinition.mapping.comment` - comment has change due to type change: R5 comment markdown has no equivalent or mapped type in R4B comment |
| ElementDefinition.mapping.extension | ElementDefinition.mapping.extension | Equivalent | R5 `ElementDefinition.mapping.extension` maps as Equivalent to R4B `ElementDefinition.mapping.extension` |
| ElementDefinition.mapping.id | ElementDefinition.mapping.id | Equivalent | R5 `ElementDefinition.mapping.id` maps as Equivalent to R4B `ElementDefinition.mapping.id` |
| ElementDefinition.mapping.identity | ElementDefinition.mapping.identity | Equivalent | R5 `ElementDefinition.mapping.identity` maps as Equivalent to R4B `ElementDefinition.mapping.identity` |
| ElementDefinition.mapping.language | ElementDefinition.mapping.language | Equivalent | R5 `ElementDefinition.mapping.language` maps as Equivalent to R4B `ElementDefinition.mapping.language` - language using http://hl7.org/fhir/ValueSet/mimetypes is exempted and assumed equivalent |
| ElementDefinition.mapping.map | ElementDefinition.mapping.map | Equivalent | R5 `ElementDefinition.mapping.map` maps as Equivalent to R4B `ElementDefinition.mapping.map` |
| ElementDefinition.max | ElementDefinition.max | Equivalent | R5 `ElementDefinition.max` maps as Equivalent to R4B `ElementDefinition.max` |
| ElementDefinition.maxLength | ElementDefinition.maxLength | Equivalent | R5 `ElementDefinition.maxLength` maps as Equivalent to R4B `ElementDefinition.maxLength` |
| ElementDefinition.maxValue[x] | ElementDefinition.maxValue[x] | SourceIsBroaderThanTarget | R5 `ElementDefinition.maxValue[x]` maps as SourceIsBroaderThanTarget to R4B `ElementDefinition.maxValue[x]` - maxValue[x] has change due to type change: R5 maxValue[x] integer64 has no equivalent or mapped type in R4B maxValue[x] |
| ElementDefinition.meaningWhenMissing | ElementDefinition.meaningWhenMissing | Equivalent | R5 `ElementDefinition.meaningWhenMissing` maps as Equivalent to R4B `ElementDefinition.meaningWhenMissing` |
| ElementDefinition.min | ElementDefinition.min | Equivalent | R5 `ElementDefinition.min` maps as Equivalent to R4B `ElementDefinition.min` |
| ElementDefinition.minValue[x] | ElementDefinition.minValue[x] | SourceIsBroaderThanTarget | R5 `ElementDefinition.minValue[x]` maps as SourceIsBroaderThanTarget to R4B `ElementDefinition.minValue[x]` - minValue[x] has change due to type change: R5 minValue[x] integer64 has no equivalent or mapped type in R4B minValue[x] |
| ElementDefinition.modifierExtension | ElementDefinition.modifierExtension | Equivalent | R5 `ElementDefinition.modifierExtension` maps as Equivalent to R4B `ElementDefinition.modifierExtension` |
| ElementDefinition.mustHaveValue | - | DoesNotExistInTarget | R5 `ElementDefinition.mustHaveValue` does not appear in the target and has no mapping for `ElementDefinition`. |
| ElementDefinition.mustSupport | ElementDefinition.mustSupport | Equivalent | R5 `ElementDefinition.mustSupport` maps as Equivalent to R4B `ElementDefinition.mustSupport` |
| ElementDefinition.orderMeaning | ElementDefinition.orderMeaning | Equivalent | R5 `ElementDefinition.orderMeaning` maps as Equivalent to R4B `ElementDefinition.orderMeaning` |
| ElementDefinition.path | ElementDefinition.path | Equivalent | R5 `ElementDefinition.path` maps as Equivalent to R4B `ElementDefinition.path` |
| ElementDefinition.pattern[x] | ElementDefinition.pattern[x] | SourceIsBroaderThanTarget | R5 `ElementDefinition.pattern[x]` maps as SourceIsBroaderThanTarget to R4B `ElementDefinition.pattern[x]` - pattern[x] has change due to type change: R5 pattern[x] integer64 has no equivalent or mapped type in R4B pattern[x]; pattern[x] has change due to type change: R5 type Availability does not exist in R4B; pattern[x] has change due to type change: R5 type ExtendedContactDetail does not exist in R4B; pattern[x] has change due to type change: R5 pattern[x] Meta has no equivalent or mapped type in R4B pattern[x] |
| ElementDefinition.representation | ElementDefinition.representation | Equivalent | R5 `ElementDefinition.representation` maps as Equivalent to R4B `ElementDefinition.representation` - representation has compatible required binding for code type: http://hl7.org/fhir/ValueSet/property-representation|5.0.0 and http://hl7.org/fhir/ValueSet/property-representation|4.3.0 (Equivalent) |
| ElementDefinition.requirements | ElementDefinition.requirements | Equivalent | R5 `ElementDefinition.requirements` maps as Equivalent to R4B `ElementDefinition.requirements` |
| ElementDefinition.short | ElementDefinition.short | Equivalent | R5 `ElementDefinition.short` maps as Equivalent to R4B `ElementDefinition.short` |
| ElementDefinition.sliceIsConstraining | ElementDefinition.sliceIsConstraining | Equivalent | R5 `ElementDefinition.sliceIsConstraining` maps as Equivalent to R4B `ElementDefinition.sliceIsConstraining` |
| ElementDefinition.sliceName | ElementDefinition.sliceName | Equivalent | R5 `ElementDefinition.sliceName` maps as Equivalent to R4B `ElementDefinition.sliceName` |
| ElementDefinition.slicing | ElementDefinition.slicing | Equivalent | R5 `ElementDefinition.slicing` maps as Equivalent to R4B `ElementDefinition.slicing` |
| ElementDefinition.slicing.description | ElementDefinition.slicing.description | Equivalent | R5 `ElementDefinition.slicing.description` maps as Equivalent to R4B `ElementDefinition.slicing.description` |
| ElementDefinition.slicing.discriminator | ElementDefinition.slicing.discriminator | Equivalent | R5 `ElementDefinition.slicing.discriminator` maps as Equivalent to R4B `ElementDefinition.slicing.discriminator` |
| ElementDefinition.slicing.discriminator.extension | ElementDefinition.slicing.discriminator.extension | Equivalent | R5 `ElementDefinition.slicing.discriminator.extension` maps as Equivalent to R4B `ElementDefinition.slicing.discriminator.extension` |
| ElementDefinition.slicing.discriminator.id | ElementDefinition.slicing.discriminator.id | Equivalent | R5 `ElementDefinition.slicing.discriminator.id` maps as Equivalent to R4B `ElementDefinition.slicing.discriminator.id` |
| ElementDefinition.slicing.discriminator.path | ElementDefinition.slicing.discriminator.path | Equivalent | R5 `ElementDefinition.slicing.discriminator.path` maps as Equivalent to R4B `ElementDefinition.slicing.discriminator.path` |
| ElementDefinition.slicing.discriminator.type | ElementDefinition.slicing.discriminator.type | Equivalent | R5 `ElementDefinition.slicing.discriminator.type` maps as Equivalent to R4B `ElementDefinition.slicing.discriminator.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/discriminator-type|5.0.0 and http://hl7.org/fhir/ValueSet/discriminator-type|4.3.0 (Equivalent) |
| ElementDefinition.slicing.extension | ElementDefinition.slicing.extension | Equivalent | R5 `ElementDefinition.slicing.extension` maps as Equivalent to R4B `ElementDefinition.slicing.extension` |
| ElementDefinition.slicing.id | ElementDefinition.slicing.id | Equivalent | R5 `ElementDefinition.slicing.id` maps as Equivalent to R4B `ElementDefinition.slicing.id` |
| ElementDefinition.slicing.ordered | ElementDefinition.slicing.ordered | Equivalent | R5 `ElementDefinition.slicing.ordered` maps as Equivalent to R4B `ElementDefinition.slicing.ordered` |
| ElementDefinition.slicing.rules | ElementDefinition.slicing.rules | Equivalent | R5 `ElementDefinition.slicing.rules` maps as Equivalent to R4B `ElementDefinition.slicing.rules` - rules has compatible required binding for code type: http://hl7.org/fhir/ValueSet/resource-slicing-rules|5.0.0 and http://hl7.org/fhir/ValueSet/resource-slicing-rules|4.3.0 (Equivalent) |
| ElementDefinition.type | ElementDefinition.type | Equivalent | R5 `ElementDefinition.type` maps as Equivalent to R4B `ElementDefinition.type` |
| ElementDefinition.type.aggregation | ElementDefinition.type.aggregation | Equivalent | R5 `ElementDefinition.type.aggregation` maps as Equivalent to R4B `ElementDefinition.type.aggregation` - aggregation has compatible required binding for code type: http://hl7.org/fhir/ValueSet/resource-aggregation-mode|5.0.0 and http://hl7.org/fhir/ValueSet/resource-aggregation-mode|4.3.0 (Equivalent) |
| ElementDefinition.type.code | ElementDefinition.type.code | Equivalent | R5 `ElementDefinition.type.code` maps as Equivalent to R4B `ElementDefinition.type.code` |
| ElementDefinition.type.extension | ElementDefinition.type.extension | Equivalent | R5 `ElementDefinition.type.extension` maps as Equivalent to R4B `ElementDefinition.type.extension` |
| ElementDefinition.type.id | ElementDefinition.type.id | Equivalent | R5 `ElementDefinition.type.id` maps as Equivalent to R4B `ElementDefinition.type.id` |
| ElementDefinition.type.profile | ElementDefinition.type.profile | Equivalent | R5 `ElementDefinition.type.profile` maps as Equivalent to R4B `ElementDefinition.type.profile` |
| ElementDefinition.type.targetProfile | ElementDefinition.type.targetProfile | Equivalent | R5 `ElementDefinition.type.targetProfile` maps as Equivalent to R4B `ElementDefinition.type.targetProfile` |
| ElementDefinition.type.versioning | ElementDefinition.type.versioning | Equivalent | R5 `ElementDefinition.type.versioning` maps as Equivalent to R4B `ElementDefinition.type.versioning` - versioning has compatible required binding for code type: http://hl7.org/fhir/ValueSet/reference-version-rules|5.0.0 and http://hl7.org/fhir/ValueSet/reference-version-rules|4.3.0 (Equivalent) |
| ElementDefinition.valueAlternatives | - | DoesNotExistInTarget | R5 `ElementDefinition.valueAlternatives` does not appear in the target and has no mapping for `ElementDefinition`. |

