Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:51 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Linkage |  | Identifies two or more records (resource instances) that refer to the same real-world "occurrence". | 17 | 6 |
| Target | Linkage |  | Identifies two or more records (resource instances) that refer to the same real-world "occurrence". | 17 | 6 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 13 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Linkage | Linkage | Equivalent | R5 `Linkage` maps as Equivalent to R4 `Linkage` |
| Linkage.active | Linkage.active | Equivalent | R5 `Linkage.active` maps as Equivalent to R4 `Linkage.active` |
| Linkage.author | Linkage.author | Equivalent | R5 `Linkage.author` maps as Equivalent to R4 `Linkage.author` |
| Linkage.contained | Linkage.contained | Equivalent | R5 `Linkage.contained` maps as Equivalent to R4 `Linkage.contained` |
| Linkage.extension | Linkage.extension | SourceIsBroaderThanTarget | R5 `Linkage.extension` maps as SourceIsBroaderThanTarget to R4 `Linkage.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Linkage.id | Linkage.id | Equivalent | R5 `Linkage.id` maps as Equivalent to R4 `Linkage.id` |
| Linkage.implicitRules | Linkage.implicitRules | Equivalent | R5 `Linkage.implicitRules` maps as Equivalent to R4 `Linkage.implicitRules` |
| Linkage.item | Linkage.item | Equivalent | R5 `Linkage.item` maps as Equivalent to R4 `Linkage.item` |
| Linkage.item.extension | Linkage.item.extension | SourceIsBroaderThanTarget | R5 `Linkage.item.extension` maps as SourceIsBroaderThanTarget to R4 `Linkage.item.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Linkage.item.id | Linkage.item.id | Equivalent | R5 `Linkage.item.id` maps as Equivalent to R4 `Linkage.item.id` |
| Linkage.item.modifierExtension | Linkage.item.modifierExtension | SourceIsBroaderThanTarget | R5 `Linkage.item.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Linkage.item.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Linkage.item.resource | Linkage.item.resource | Equivalent | R5 `Linkage.item.resource` maps as Equivalent to R4 `Linkage.item.resource` |
| Linkage.item.type | Linkage.item.type | Equivalent | R5 `Linkage.item.type` maps as Equivalent to R4 `Linkage.item.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/linkage-type|5.0.0 and http://hl7.org/fhir/ValueSet/linkage-type|4.0.1 (Equivalent) |
| Linkage.language | Linkage.language | RelatedTo | R5 `Linkage.language` maps as RelatedTo to R4 `Linkage.language` - language changed the binding strength from Required to Preferred |
| Linkage.meta | Linkage.meta | Equivalent | R5 `Linkage.meta` maps as Equivalent to R4 `Linkage.meta` |
| Linkage.modifierExtension | Linkage.modifierExtension | SourceIsBroaderThanTarget | R5 `Linkage.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Linkage.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Linkage.text | Linkage.text | Equivalent | R5 `Linkage.text` maps as Equivalent to R4 `Linkage.text` |

