Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Basic |  | Basic is used for handling concepts not yet defined in FHIR, narrative-only resources that don't map to an existing resource, and custom resources not appropriate for inclusion in the FHIR specification. | 14 | 6 |
| Target | Basic |  | Basic is used for handling concepts not yet defined in FHIR, narrative-only resources that don't map to an existing resource, and custom resources not appropriate for inclusion in the FHIR specification. | 14 | 6 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 10 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Basic | Basic | Equivalent | R4B `Basic` maps as Equivalent to R5 `Basic` |
| Basic.author | Basic.author | SourceIsNarrowerThanTarget | R4B `Basic.author` maps as SourceIsNarrowerThanTarget to R5 `Basic.author` - author has change due to type change: R4B `author` `Reference` maps as SourceIsNarrowerThanTarget for R5 `author` |
| Basic.code | Basic.code | Equivalent | R4B `Basic.code` maps as Equivalent to R5 `Basic.code` |
| Basic.contained | Basic.contained | Equivalent | R4B `Basic.contained` maps as Equivalent to R5 `Basic.contained` |
| Basic.created | Basic.created | SourceIsBroaderThanTarget | R4B `Basic.created` maps as SourceIsBroaderThanTarget to R5 `Basic.created` - created has change due to type change: R4B created date has no equivalent or mapped type in R5 created |
| Basic.extension | Basic.extension | RelatedTo | R4B `Basic.extension` maps as RelatedTo to R5 `Basic.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Basic.id | Basic.id | Equivalent | R4B `Basic.id` maps as Equivalent to R5 `Basic.id` |
| Basic.identifier | Basic.identifier | Equivalent | R4B `Basic.identifier` maps as Equivalent to R5 `Basic.identifier` |
| Basic.implicitRules | Basic.implicitRules | Equivalent | R4B `Basic.implicitRules` maps as Equivalent to R5 `Basic.implicitRules` |
| Basic.language | Basic.language | RelatedTo | R4B `Basic.language` maps as RelatedTo to R5 `Basic.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Basic.meta | Basic.meta | Equivalent | R4B `Basic.meta` maps as Equivalent to R5 `Basic.meta` |
| Basic.modifierExtension | Basic.modifierExtension | RelatedTo | R4B `Basic.modifierExtension` maps as RelatedTo to R5 `Basic.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Basic.subject | Basic.subject | Equivalent | R4B `Basic.subject` maps as Equivalent to R5 `Basic.subject` |
| Basic.text | Basic.text | Equivalent | R4B `Basic.text` maps as Equivalent to R5 `Basic.text` |

