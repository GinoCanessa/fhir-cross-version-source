Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Flag |  | Prospective warnings of potential issues when providing care to the patient. | 17 | 9 |
| Target | Flag |  | Prospective warnings of potential issues when providing care to the patient. | 17 | 9 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 13 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Flag | Flag | Equivalent | R5 `Flag` maps as Equivalent to R4B `Flag` |
| Flag.author | Flag.author | SourceIsBroaderThanTarget | R5 `Flag.author` maps as SourceIsBroaderThanTarget to R4B `Flag.author` - author has change due to type change: R5 `author` `Reference` maps as SourceIsBroaderThanTarget for R4B `author` |
| Flag.category | Flag.category | Equivalent | R5 `Flag.category` maps as Equivalent to R4B `Flag.category` |
| Flag.code | Flag.code | Equivalent | R5 `Flag.code` maps as Equivalent to R4B `Flag.code` |
| Flag.contained | Flag.contained | Equivalent | R5 `Flag.contained` maps as Equivalent to R4B `Flag.contained` |
| Flag.encounter | Flag.encounter | Equivalent | R5 `Flag.encounter` maps as Equivalent to R4B `Flag.encounter` |
| Flag.extension | Flag.extension | SourceIsBroaderThanTarget | R5 `Flag.extension` maps as SourceIsBroaderThanTarget to R4B `Flag.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| Flag.id | Flag.id | Equivalent | R5 `Flag.id` maps as Equivalent to R4B `Flag.id` |
| Flag.identifier | Flag.identifier | Equivalent | R5 `Flag.identifier` maps as Equivalent to R4B `Flag.identifier` |
| Flag.implicitRules | Flag.implicitRules | Equivalent | R5 `Flag.implicitRules` maps as Equivalent to R4B `Flag.implicitRules` |
| Flag.language | Flag.language | RelatedTo | R5 `Flag.language` maps as RelatedTo to R4B `Flag.language` - language changed the binding strength from Required to Preferred |
| Flag.meta | Flag.meta | Equivalent | R5 `Flag.meta` maps as Equivalent to R4B `Flag.meta` |
| Flag.modifierExtension | Flag.modifierExtension | SourceIsBroaderThanTarget | R5 `Flag.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `Flag.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| Flag.period | Flag.period | Equivalent | R5 `Flag.period` maps as Equivalent to R4B `Flag.period` |
| Flag.status | Flag.status | Equivalent | R5 `Flag.status` maps as Equivalent to R4B `Flag.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/flag-status|5.0.0 and http://hl7.org/fhir/ValueSet/flag-status|4.3.0 (Equivalent) |
| Flag.subject | Flag.subject | SourceIsBroaderThanTarget | R5 `Flag.subject` maps as SourceIsBroaderThanTarget to R4B `Flag.subject` - subject has change due to type change: R5 `subject` `Reference` maps as SourceIsBroaderThanTarget for R4B `subject` |
| Flag.text | Flag.text | Equivalent | R5 `Flag.text` maps as Equivalent to R4B `Flag.text` |

