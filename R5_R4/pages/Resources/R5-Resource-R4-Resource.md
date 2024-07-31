Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | Resource |  | This is the base resource type for everything. | 5 | 5 |
| Target | Resource |  | This is the base resource type for everything. | 5 | 5 |


Comparison Result: SourceIsNarrowerThanTarget


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| Resource | Resource | Equivalent | R5 `Resource` maps as Equivalent to R4 `Resource` |
| Resource.id | Resource.id | Equivalent | R5 `Resource.id` maps as Equivalent to R4 `Resource.id` |
| Resource.implicitRules | Resource.implicitRules | Equivalent | R5 `Resource.implicitRules` maps as Equivalent to R4 `Resource.implicitRules` |
| Resource.language | Resource.language | SourceIsNarrowerThanTarget | R5 `Resource.language` maps as SourceIsNarrowerThanTarget to R4 `Resource.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| Resource.meta | Resource.meta | Equivalent | R5 `Resource.meta` maps as Equivalent to R4 `Resource.meta` |

