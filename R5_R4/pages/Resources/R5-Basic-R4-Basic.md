Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Basic |  | Basic is used for handling concepts not yet defined in FHIR, narrative-only resources that don't map to an existing resource, and custom resources not appropriate for inclusion in the FHIR specification. | 14 | 6 |
| Target | Basic |  | Basic is used for handling concepts not yet defined in FHIR, narrative-only resources that don't map to an existing resource, and custom resources not appropriate for inclusion in the FHIR specification. | 14 | 6 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 9 |
SourceIsBroaderThanTarget | 4 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Basic | Basic | Equivalent | R5 `Basic` maps as Equivalent to R4 `Basic` |
| Basic.author | Basic.author | SourceIsBroaderThanTarget | R5 `Basic.author` maps as SourceIsBroaderThanTarget to R4 `Basic.author` - author has change due to type change: R5 `author` `Reference` maps as SourceIsBroaderThanTarget for R4 `author` |
| Basic.code | Basic.code | Equivalent | R5 `Basic.code` maps as Equivalent to R4 `Basic.code` |
| Basic.contained | Basic.contained | Equivalent | R5 `Basic.contained` maps as Equivalent to R4 `Basic.contained` |
| Basic.created | Basic.created | SourceIsBroaderThanTarget | R5 `Basic.created` maps as SourceIsBroaderThanTarget to R4 `Basic.created` - created has change due to type change: R5 created dateTime has no equivalent or mapped type in R4 created |
| Basic.extension | Basic.extension | SourceIsBroaderThanTarget | R5 `Basic.extension` maps as SourceIsBroaderThanTarget to R4 `Basic.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| Basic.id | Basic.id | Equivalent | R5 `Basic.id` maps as Equivalent to R4 `Basic.id` |
| Basic.identifier | Basic.identifier | Equivalent | R5 `Basic.identifier` maps as Equivalent to R4 `Basic.identifier` |
| Basic.implicitRules | Basic.implicitRules | Equivalent | R5 `Basic.implicitRules` maps as Equivalent to R4 `Basic.implicitRules` |
| Basic.language | Basic.language | SourceIsNarrowerThanTarget | R5 `Basic.language` maps as SourceIsNarrowerThanTarget to R4 `Basic.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| Basic.meta | Basic.meta | Equivalent | R5 `Basic.meta` maps as Equivalent to R4 `Basic.meta` |
| Basic.modifierExtension | Basic.modifierExtension | SourceIsBroaderThanTarget | R5 `Basic.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `Basic.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| Basic.subject | Basic.subject | Equivalent | R5 `Basic.subject` maps as Equivalent to R4 `Basic.subject` |
| Basic.text | Basic.text | Equivalent | R5 `Basic.text` maps as Equivalent to R4 `Basic.text` |

