Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Group |  | Represents a defined collection of entities that may be discussed or acted upon collectively but which are not expected to act collectively, and are not formally or legally recognized; i.e. a collection of entities that isn't an Organization. | 33 | 19 |
| Target | Group |  | Represents a defined collection of entities that may be discussed or acted upon collectively but which are not expected to act collectively, and are not formally or legally recognized; i.e. a collection of entities that isn't an Organization. | 32 | 18 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 2 |
Equivalent | 4 |
RelatedTo | 27 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Group | Group | Equivalent | R5 `Group` maps as Equivalent to R4B `Group` |
| Group.active | Group.active | Equivalent | R5 `Group.active` maps as Equivalent to R4B `Group.active` |
| Group.characteristic | Group.characteristic | Equivalent | R5 `Group.characteristic` maps as Equivalent to R4B `Group.characteristic` |
| Group.characteristic.code | Group.characteristic.code | Equivalent | R5 `Group.characteristic.code` maps as Equivalent to R4B `Group.characteristic.code` |
| Group.characteristic.exclude | Group.characteristic.exclude | Equivalent | R5 `Group.characteristic.exclude` maps as Equivalent to R4B `Group.characteristic.exclude` |
| Group.characteristic.extension | Group.characteristic.extension | SourceIsBroaderThanTarget | R5 `Group.characteristic.extension` maps as SourceIsBroaderThanTarget to R4B `Group.characteristic.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Group.characteristic.id | Group.characteristic.id | Equivalent | R5 `Group.characteristic.id` maps as Equivalent to R4B `Group.characteristic.id` |
| Group.characteristic.modifierExtension | Group.characteristic.modifierExtension | SourceIsBroaderThanTarget | R5 `Group.characteristic.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Group.characteristic.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Group.characteristic.period | Group.characteristic.period | Equivalent | R5 `Group.characteristic.period` maps as Equivalent to R4B `Group.characteristic.period` |
| Group.characteristic.value[x] | Group.characteristic.value[x] | Equivalent | R5 `Group.characteristic.value[x]` maps as Equivalent to R4B `Group.characteristic.value[x]` |
| Group.code | Group.code | Equivalent | R5 `Group.code` maps as Equivalent to R4B `Group.code` |
| Group.contained | Group.contained | Equivalent | R5 `Group.contained` maps as Equivalent to R4B `Group.contained` |
| Group.description | - | DoesNotExistInTarget | R5 `Group.description` does not appear in the target and has no mapping for `Group`. |
| Group.extension | Group.extension | SourceIsBroaderThanTarget | R5 `Group.extension` maps as SourceIsBroaderThanTarget to R4B `Group.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Group.id | Group.id | Equivalent | R5 `Group.id` maps as Equivalent to R4B `Group.id` |
| Group.identifier | Group.identifier | Equivalent | R5 `Group.identifier` maps as Equivalent to R4B `Group.identifier` |
| Group.implicitRules | Group.implicitRules | Equivalent | R5 `Group.implicitRules` maps as Equivalent to R4B `Group.implicitRules` |
| Group.language | Group.language | RelatedTo | R5 `Group.language` maps as RelatedTo to R4B `Group.language` - language changed the binding strength from Required to Preferred |
| Group.managingEntity | Group.managingEntity | Equivalent | R5 `Group.managingEntity` maps as Equivalent to R4B `Group.managingEntity` |
| Group.member | Group.member | Equivalent | R5 `Group.member` maps as Equivalent to R4B `Group.member` |
| Group.member.entity | Group.member.entity | RelatedTo | R5 `Group.member.entity` maps as RelatedTo to R4B `Group.member.entity` - entity has change due to type change: R5 `entity` `Reference` maps as RelatedTo for R4B `entity` |
| Group.member.extension | Group.member.extension | SourceIsBroaderThanTarget | R5 `Group.member.extension` maps as SourceIsBroaderThanTarget to R4B `Group.member.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Group.member.id | Group.member.id | Equivalent | R5 `Group.member.id` maps as Equivalent to R4B `Group.member.id` |
| Group.member.inactive | Group.member.inactive | Equivalent | R5 `Group.member.inactive` maps as Equivalent to R4B `Group.member.inactive` |
| Group.member.modifierExtension | Group.member.modifierExtension | SourceIsBroaderThanTarget | R5 `Group.member.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Group.member.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Group.member.period | Group.member.period | Equivalent | R5 `Group.member.period` maps as Equivalent to R4B `Group.member.period` |
| Group.membership | - | DoesNotExistInTarget | R5 `Group.membership` does not appear in the target and has no mapping for `Group`. |
| Group.meta | Group.meta | Equivalent | R5 `Group.meta` maps as Equivalent to R4B `Group.meta` |
| Group.modifierExtension | Group.modifierExtension | SourceIsBroaderThanTarget | R5 `Group.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Group.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Group.name | Group.name | Equivalent | R5 `Group.name` maps as Equivalent to R4B `Group.name` |
| Group.quantity | Group.quantity | Equivalent | R5 `Group.quantity` maps as Equivalent to R4B `Group.quantity` |
| Group.text | Group.text | Equivalent | R5 `Group.text` maps as Equivalent to R4B `Group.text` |
| Group.type | Group.type | Equivalent | R5 `Group.type` maps as Equivalent to R4B `Group.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/group-type|5.0.0 and http://hl7.org/fhir/ValueSet/group-type|4.3.0 (Equivalent) |

