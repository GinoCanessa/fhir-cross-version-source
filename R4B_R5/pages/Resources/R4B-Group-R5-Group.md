Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Group |  | Represents a defined collection of entities that may be discussed or acted upon collectively but which are not expected to act collectively, and are not formally or legally recognized; i.e. a collection of entities that isn't an Organization. | 32 | 18 |
| Target | Group |  | Represents a defined collection of entities that may be discussed or acted upon collectively but which are not expected to act collectively, and are not formally or legally recognized; i.e. a collection of entities that isn't an Organization. | 33 | 19 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 1 |
Equivalent | 4 |
RelatedTo | 27 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Group | Group | Equivalent | R4B `Group` maps as Equivalent to R5 `Group` |
| Group.active | Group.active | Equivalent | R4B `Group.active` maps as Equivalent to R5 `Group.active` |
| Group.actual | - | DoesNotExistInTarget | R4B `Group.actual` does not appear in the target and has no mapping for `Group`. |
| Group.characteristic | Group.characteristic | Equivalent | R4B `Group.characteristic` maps as Equivalent to R5 `Group.characteristic` |
| Group.characteristic.code | Group.characteristic.code | Equivalent | R4B `Group.characteristic.code` maps as Equivalent to R5 `Group.characteristic.code` |
| Group.characteristic.exclude | Group.characteristic.exclude | Equivalent | R4B `Group.characteristic.exclude` maps as Equivalent to R5 `Group.characteristic.exclude` |
| Group.characteristic.extension | Group.characteristic.extension | RelatedTo | R4B `Group.characteristic.extension` maps as RelatedTo to R5 `Group.characteristic.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Group.characteristic.id | Group.characteristic.id | Equivalent | R4B `Group.characteristic.id` maps as Equivalent to R5 `Group.characteristic.id` |
| Group.characteristic.modifierExtension | Group.characteristic.modifierExtension | RelatedTo | R4B `Group.characteristic.modifierExtension` maps as RelatedTo to R5 `Group.characteristic.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Group.characteristic.period | Group.characteristic.period | Equivalent | R4B `Group.characteristic.period` maps as Equivalent to R5 `Group.characteristic.period` |
| Group.characteristic.value[x] | Group.characteristic.value[x] | Equivalent | R4B `Group.characteristic.value[x]` maps as Equivalent to R5 `Group.characteristic.value[x]` |
| Group.code | Group.code | Equivalent | R4B `Group.code` maps as Equivalent to R5 `Group.code` |
| Group.contained | Group.contained | Equivalent | R4B `Group.contained` maps as Equivalent to R5 `Group.contained` |
| Group.extension | Group.extension | RelatedTo | R4B `Group.extension` maps as RelatedTo to R5 `Group.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Group.id | Group.id | Equivalent | R4B `Group.id` maps as Equivalent to R5 `Group.id` |
| Group.identifier | Group.identifier | Equivalent | R4B `Group.identifier` maps as Equivalent to R5 `Group.identifier` |
| Group.implicitRules | Group.implicitRules | Equivalent | R4B `Group.implicitRules` maps as Equivalent to R5 `Group.implicitRules` |
| Group.language | Group.language | RelatedTo | R4B `Group.language` maps as RelatedTo to R5 `Group.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Group.managingEntity | Group.managingEntity | Equivalent | R4B `Group.managingEntity` maps as Equivalent to R5 `Group.managingEntity` |
| Group.member | Group.member | Equivalent | R4B `Group.member` maps as Equivalent to R5 `Group.member` |
| Group.member.entity | Group.member.entity | RelatedTo | R4B `Group.member.entity` maps as RelatedTo to R5 `Group.member.entity` - entity has change due to type change: R4B `entity` `Reference` maps as RelatedTo for R5 `entity` |
| Group.member.extension | Group.member.extension | RelatedTo | R4B `Group.member.extension` maps as RelatedTo to R5 `Group.member.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Group.member.id | Group.member.id | Equivalent | R4B `Group.member.id` maps as Equivalent to R5 `Group.member.id` |
| Group.member.inactive | Group.member.inactive | Equivalent | R4B `Group.member.inactive` maps as Equivalent to R5 `Group.member.inactive` |
| Group.member.modifierExtension | Group.member.modifierExtension | RelatedTo | R4B `Group.member.modifierExtension` maps as RelatedTo to R5 `Group.member.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Group.member.period | Group.member.period | Equivalent | R4B `Group.member.period` maps as Equivalent to R5 `Group.member.period` |
| Group.meta | Group.meta | Equivalent | R4B `Group.meta` maps as Equivalent to R5 `Group.meta` |
| Group.modifierExtension | Group.modifierExtension | RelatedTo | R4B `Group.modifierExtension` maps as RelatedTo to R5 `Group.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Group.name | Group.name | Equivalent | R4B `Group.name` maps as Equivalent to R5 `Group.name` |
| Group.quantity | Group.quantity | Equivalent | R4B `Group.quantity` maps as Equivalent to R5 `Group.quantity` |
| Group.text | Group.text | Equivalent | R4B `Group.text` maps as Equivalent to R5 `Group.text` |
| Group.type | Group.type | Equivalent | R4B `Group.type` maps as Equivalent to R5 `Group.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/group-type|4.3.0 and http://hl7.org/fhir/ValueSet/group-type|5.0.0 (Equivalent) |

