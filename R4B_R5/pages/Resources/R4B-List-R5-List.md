Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | List |  | A list is a curated collection of resources. | 29 | 18 |
| Target | List |  | A List is a curated collection of resources, for things such as problem lists, allergy lists, facility list, organization list, etc. | 29 | 18 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 25 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| List | List | Equivalent | R4B `List` maps as Equivalent to R5 `List` |
| List.code | List.code | Equivalent | R4B `List.code` maps as Equivalent to R5 `List.code` |
| List.contained | List.contained | Equivalent | R4B `List.contained` maps as Equivalent to R5 `List.contained` |
| List.date | List.date | Equivalent | R4B `List.date` maps as Equivalent to R5 `List.date` |
| List.emptyReason | List.emptyReason | Equivalent | R4B `List.emptyReason` maps as Equivalent to R5 `List.emptyReason` |
| List.encounter | List.encounter | Equivalent | R4B `List.encounter` maps as Equivalent to R5 `List.encounter` |
| List.entry | List.entry | Equivalent | R4B `List.entry` maps as Equivalent to R5 `List.entry` |
| List.entry.date | List.entry.date | Equivalent | R4B `List.entry.date` maps as Equivalent to R5 `List.entry.date` |
| List.entry.deleted | List.entry.deleted | Equivalent | R4B `List.entry.deleted` maps as Equivalent to R5 `List.entry.deleted` |
| List.entry.extension | List.entry.extension | RelatedTo | R4B `List.entry.extension` maps as RelatedTo to R5 `List.entry.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| List.entry.flag | List.entry.flag | Equivalent | R4B `List.entry.flag` maps as Equivalent to R5 `List.entry.flag` |
| List.entry.id | List.entry.id | Equivalent | R4B `List.entry.id` maps as Equivalent to R5 `List.entry.id` |
| List.entry.item | List.entry.item | Equivalent | R4B `List.entry.item` maps as Equivalent to R5 `List.entry.item` |
| List.entry.modifierExtension | List.entry.modifierExtension | RelatedTo | R4B `List.entry.modifierExtension` maps as RelatedTo to R5 `List.entry.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| List.extension | List.extension | RelatedTo | R4B `List.extension` maps as RelatedTo to R5 `List.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| List.id | List.id | Equivalent | R4B `List.id` maps as Equivalent to R5 `List.id` |
| List.identifier | List.identifier | Equivalent | R4B `List.identifier` maps as Equivalent to R5 `List.identifier` |
| List.implicitRules | List.implicitRules | Equivalent | R4B `List.implicitRules` maps as Equivalent to R5 `List.implicitRules` |
| List.language | List.language | RelatedTo | R4B `List.language` maps as RelatedTo to R5 `List.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| List.meta | List.meta | Equivalent | R4B `List.meta` maps as Equivalent to R5 `List.meta` |
| List.mode | List.mode | Equivalent | R4B `List.mode` maps as Equivalent to R5 `List.mode` - mode has compatible required binding for code type: http://hl7.org/fhir/ValueSet/list-mode|4.3.0 and http://hl7.org/fhir/ValueSet/list-mode|5.0.0 (Equivalent) |
| List.modifierExtension | List.modifierExtension | RelatedTo | R4B `List.modifierExtension` maps as RelatedTo to R5 `List.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| List.note | List.note | SourceIsNarrowerThanTarget | R4B `List.note` maps as SourceIsNarrowerThanTarget to R5 `List.note` - note has change due to type change: R4B `note` `Annotation` maps as SourceIsNarrowerThanTarget for R5 `note` |
| List.orderedBy | List.orderedBy | Equivalent | R4B `List.orderedBy` maps as Equivalent to R5 `List.orderedBy` |
| List.source | List.source | SourceIsNarrowerThanTarget | R4B `List.source` maps as SourceIsNarrowerThanTarget to R5 `List.source` - source has change due to type change: R4B `source` `Reference` maps as SourceIsNarrowerThanTarget for R5 `source` |
| List.status | List.status | Equivalent | R4B `List.status` maps as Equivalent to R5 `List.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/list-status|4.3.0 and http://hl7.org/fhir/ValueSet/list-status|5.0.0 (Equivalent) |
| List.subject | List.subject | RelatedTo | R4B `List.subject` maps as RelatedTo to R5 `List.subject` - subject changed from scalar to array (max cardinality from 1 to *); subject has change due to type change: R4B `subject` `Reference` maps as RelatedTo for R5 `subject` |
| List.text | List.text | Equivalent | R4B `List.text` maps as Equivalent to R5 `List.text` |
| List.title | List.title | Equivalent | R4B `List.title` maps as Equivalent to R5 `List.title` |

