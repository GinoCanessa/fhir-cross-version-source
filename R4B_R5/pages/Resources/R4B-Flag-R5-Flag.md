Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

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
| Flag | Flag | Equivalent | R4B `Flag` maps as Equivalent to R5 `Flag` |
| Flag.author | Flag.author | SourceIsNarrowerThanTarget | R4B `Flag.author` maps as SourceIsNarrowerThanTarget to R5 `Flag.author` - author has change due to type change: R4B `author` `Reference` maps as SourceIsNarrowerThanTarget for R5 `author` |
| Flag.category | Flag.category | Equivalent | R4B `Flag.category` maps as Equivalent to R5 `Flag.category` |
| Flag.code | Flag.code | Equivalent | R4B `Flag.code` maps as Equivalent to R5 `Flag.code` |
| Flag.contained | Flag.contained | Equivalent | R4B `Flag.contained` maps as Equivalent to R5 `Flag.contained` |
| Flag.encounter | Flag.encounter | Equivalent | R4B `Flag.encounter` maps as Equivalent to R5 `Flag.encounter` |
| Flag.extension | Flag.extension | RelatedTo | R4B `Flag.extension` maps as RelatedTo to R5 `Flag.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| Flag.id | Flag.id | Equivalent | R4B `Flag.id` maps as Equivalent to R5 `Flag.id` |
| Flag.identifier | Flag.identifier | Equivalent | R4B `Flag.identifier` maps as Equivalent to R5 `Flag.identifier` |
| Flag.implicitRules | Flag.implicitRules | Equivalent | R4B `Flag.implicitRules` maps as Equivalent to R5 `Flag.implicitRules` |
| Flag.language | Flag.language | RelatedTo | R4B `Flag.language` maps as RelatedTo to R5 `Flag.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| Flag.meta | Flag.meta | Equivalent | R4B `Flag.meta` maps as Equivalent to R5 `Flag.meta` |
| Flag.modifierExtension | Flag.modifierExtension | RelatedTo | R4B `Flag.modifierExtension` maps as RelatedTo to R5 `Flag.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| Flag.period | Flag.period | Equivalent | R4B `Flag.period` maps as Equivalent to R5 `Flag.period` |
| Flag.status | Flag.status | Equivalent | R4B `Flag.status` maps as Equivalent to R5 `Flag.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/flag-status|4.3.0 and http://hl7.org/fhir/ValueSet/flag-status|5.0.0 (Equivalent) |
| Flag.subject | Flag.subject | SourceIsNarrowerThanTarget | R4B `Flag.subject` maps as SourceIsNarrowerThanTarget to R5 `Flag.subject` - subject has change due to type change: R4B `subject` `Reference` maps as SourceIsNarrowerThanTarget for R5 `subject` |
| Flag.text | Flag.text | Equivalent | R4B `Flag.text` maps as Equivalent to R5 `Flag.text` |

