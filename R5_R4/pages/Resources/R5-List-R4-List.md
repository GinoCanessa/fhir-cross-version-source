Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:51 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | List |  | A List is a curated collection of resources, for things such as problem lists, allergy lists, facility list, organization list, etc. | 29 | 18 |
| Target | List |  | A list is a curated collection of resources. | 29 | 18 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 25 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| List | List | Equivalent | R5 `List` maps as Equivalent to R4 `List` |
| List.code | List.code | Equivalent | R5 `List.code` maps as Equivalent to R4 `List.code` |
| List.contained | List.contained | Equivalent | R5 `List.contained` maps as Equivalent to R4 `List.contained` |
| List.date | List.date | Equivalent | R5 `List.date` maps as Equivalent to R4 `List.date` |
| List.emptyReason | List.emptyReason | Equivalent | R5 `List.emptyReason` maps as Equivalent to R4 `List.emptyReason` |
| List.encounter | List.encounter | Equivalent | R5 `List.encounter` maps as Equivalent to R4 `List.encounter` |
| List.entry | List.entry | Equivalent | R5 `List.entry` maps as Equivalent to R4 `List.entry` |
| List.entry.date | List.entry.date | Equivalent | R5 `List.entry.date` maps as Equivalent to R4 `List.entry.date` |
| List.entry.deleted | List.entry.deleted | Equivalent | R5 `List.entry.deleted` maps as Equivalent to R4 `List.entry.deleted` |
| List.entry.extension | List.entry.extension | SourceIsBroaderThanTarget | R5 `List.entry.extension` maps as SourceIsBroaderThanTarget to R4 `List.entry.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| List.entry.flag | List.entry.flag | Equivalent | R5 `List.entry.flag` maps as Equivalent to R4 `List.entry.flag` |
| List.entry.id | List.entry.id | Equivalent | R5 `List.entry.id` maps as Equivalent to R4 `List.entry.id` |
| List.entry.item | List.entry.item | Equivalent | R5 `List.entry.item` maps as Equivalent to R4 `List.entry.item` |
| List.entry.modifierExtension | List.entry.modifierExtension | SourceIsBroaderThanTarget | R5 `List.entry.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `List.entry.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| List.extension | List.extension | SourceIsBroaderThanTarget | R5 `List.extension` maps as SourceIsBroaderThanTarget to R4 `List.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| List.id | List.id | Equivalent | R5 `List.id` maps as Equivalent to R4 `List.id` |
| List.identifier | List.identifier | Equivalent | R5 `List.identifier` maps as Equivalent to R4 `List.identifier` |
| List.implicitRules | List.implicitRules | Equivalent | R5 `List.implicitRules` maps as Equivalent to R4 `List.implicitRules` |
| List.language | List.language | RelatedTo | R5 `List.language` maps as RelatedTo to R4 `List.language` - language changed the binding strength from Required to Preferred |
| List.meta | List.meta | Equivalent | R5 `List.meta` maps as Equivalent to R4 `List.meta` |
| List.mode | List.mode | Equivalent | R5 `List.mode` maps as Equivalent to R4 `List.mode` - mode has compatible required binding for code type: http://hl7.org/fhir/ValueSet/list-mode|5.0.0 and http://hl7.org/fhir/ValueSet/list-mode|4.0.1 (Equivalent) |
| List.modifierExtension | List.modifierExtension | SourceIsBroaderThanTarget | R5 `List.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `List.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| List.note | List.note | SourceIsBroaderThanTarget | R5 `List.note` maps as SourceIsBroaderThanTarget to R4 `List.note` - note has change due to type change: R5 `note` `Annotation` maps as SourceIsBroaderThanTarget for R4 `note` |
| List.orderedBy | List.orderedBy | Equivalent | R5 `List.orderedBy` maps as Equivalent to R4 `List.orderedBy` |
| List.source | List.source | SourceIsBroaderThanTarget | R5 `List.source` maps as SourceIsBroaderThanTarget to R4 `List.source` - source has change due to type change: R5 `source` `Reference` maps as SourceIsBroaderThanTarget for R4 `source` |
| List.status | List.status | Equivalent | R5 `List.status` maps as Equivalent to R4 `List.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/list-status|5.0.0 and http://hl7.org/fhir/ValueSet/list-status|4.0.1 (Equivalent) |
| List.subject | List.subject | RelatedTo | R5 `List.subject` maps as RelatedTo to R4 `List.subject` - subject changed from array to scalar (max cardinality from * to 1); subject has change due to type change: R5 `subject` `Reference` maps as RelatedTo for R4 `subject` |
| List.text | List.text | Equivalent | R5 `List.text` maps as Equivalent to R4 `List.text` |
| List.title | List.title | Equivalent | R5 `List.title` maps as Equivalent to R4 `List.title` |

