Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

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
| Linkage | Linkage | Equivalent | R4B `Linkage` maps as Equivalent to R5 `Linkage` |
| Linkage.active | Linkage.active | Equivalent | R4B `Linkage.active` maps as Equivalent to R5 `Linkage.active` |
| Linkage.author | Linkage.author | Equivalent | R4B `Linkage.author` maps as Equivalent to R5 `Linkage.author` |
| Linkage.contained | Linkage.contained | Equivalent | R4B `Linkage.contained` maps as Equivalent to R5 `Linkage.contained` |
| Linkage.extension | Linkage.extension | RelatedTo | R4B `Linkage.extension` maps as RelatedTo to R5 `Linkage.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Linkage.id | Linkage.id | Equivalent | R4B `Linkage.id` maps as Equivalent to R5 `Linkage.id` |
| Linkage.implicitRules | Linkage.implicitRules | Equivalent | R4B `Linkage.implicitRules` maps as Equivalent to R5 `Linkage.implicitRules` |
| Linkage.item | Linkage.item | Equivalent | R4B `Linkage.item` maps as Equivalent to R5 `Linkage.item` |
| Linkage.item.extension | Linkage.item.extension | RelatedTo | R4B `Linkage.item.extension` maps as RelatedTo to R5 `Linkage.item.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Linkage.item.id | Linkage.item.id | Equivalent | R4B `Linkage.item.id` maps as Equivalent to R5 `Linkage.item.id` |
| Linkage.item.modifierExtension | Linkage.item.modifierExtension | RelatedTo | R4B `Linkage.item.modifierExtension` maps as RelatedTo to R5 `Linkage.item.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Linkage.item.resource | Linkage.item.resource | Equivalent | R4B `Linkage.item.resource` maps as Equivalent to R5 `Linkage.item.resource` |
| Linkage.item.type | Linkage.item.type | Equivalent | R4B `Linkage.item.type` maps as Equivalent to R5 `Linkage.item.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/linkage-type|4.3.0 and http://hl7.org/fhir/ValueSet/linkage-type|5.0.0 (Equivalent) |
| Linkage.language | Linkage.language | RelatedTo | R4B `Linkage.language` maps as RelatedTo to R5 `Linkage.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Linkage.meta | Linkage.meta | Equivalent | R4B `Linkage.meta` maps as Equivalent to R5 `Linkage.meta` |
| Linkage.modifierExtension | Linkage.modifierExtension | RelatedTo | R4B `Linkage.modifierExtension` maps as RelatedTo to R5 `Linkage.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Linkage.text | Linkage.text | Equivalent | R4B `Linkage.text` maps as Equivalent to R5 `Linkage.text` |

