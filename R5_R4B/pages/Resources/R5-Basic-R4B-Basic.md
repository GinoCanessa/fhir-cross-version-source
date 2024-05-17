Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

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
| Basic | Basic | Equivalent | R5 `Basic` maps as Equivalent to R4B `Basic` |
| Basic.author | Basic.author | SourceIsBroaderThanTarget | R5 `Basic.author` maps as SourceIsBroaderThanTarget to R4B `Basic.author` - author has change due to type change: R5 `author` `Reference` maps as SourceIsBroaderThanTarget for R4B `author` |
| Basic.code | Basic.code | Equivalent | R5 `Basic.code` maps as Equivalent to R4B `Basic.code` |
| Basic.contained | Basic.contained | Equivalent | R5 `Basic.contained` maps as Equivalent to R4B `Basic.contained` |
| Basic.created | Basic.created | SourceIsBroaderThanTarget | R5 `Basic.created` maps as SourceIsBroaderThanTarget to R4B `Basic.created` - created has change due to type change: R5 created dateTime has no equivalent or mapped type in R4B created |
| Basic.extension | Basic.extension | SourceIsBroaderThanTarget | R5 `Basic.extension` maps as SourceIsBroaderThanTarget to R4B `Basic.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Basic.id | Basic.id | Equivalent | R5 `Basic.id` maps as Equivalent to R4B `Basic.id` |
| Basic.identifier | Basic.identifier | Equivalent | R5 `Basic.identifier` maps as Equivalent to R4B `Basic.identifier` |
| Basic.implicitRules | Basic.implicitRules | Equivalent | R5 `Basic.implicitRules` maps as Equivalent to R4B `Basic.implicitRules` |
| Basic.language | Basic.language | RelatedTo | R5 `Basic.language` maps as RelatedTo to R4B `Basic.language` - language changed the binding strength from Required to Preferred |
| Basic.meta | Basic.meta | Equivalent | R5 `Basic.meta` maps as Equivalent to R4B `Basic.meta` |
| Basic.modifierExtension | Basic.modifierExtension | SourceIsBroaderThanTarget | R5 `Basic.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Basic.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Basic.subject | Basic.subject | Equivalent | R5 `Basic.subject` maps as Equivalent to R4B `Basic.subject` |
| Basic.text | Basic.text | Equivalent | R5 `Basic.text` maps as Equivalent to R4B `Basic.text` |

