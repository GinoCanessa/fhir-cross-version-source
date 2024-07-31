Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | DomainResource |  | A resource that includes narrative, extensions, and contained resources. | 9 | 5 |
| Target | DomainResource |  | A resource that includes narrative, extensions, and contained resources. | 9 | 5 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 6 |
SourceIsBroaderThanTarget | 2 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| DomainResource | DomainResource | Equivalent | R5 `DomainResource` maps as Equivalent to R4 `DomainResource` |
| DomainResource.contained | DomainResource.contained | Equivalent | R5 `DomainResource.contained` maps as Equivalent to R4 `DomainResource.contained` |
| DomainResource.extension | DomainResource.extension | SourceIsBroaderThanTarget | R5 `DomainResource.extension` maps as SourceIsBroaderThanTarget to R4 `DomainResource.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| DomainResource.id | DomainResource.id | Equivalent | R5 `DomainResource.id` maps as Equivalent to R4 `DomainResource.id` |
| DomainResource.implicitRules | DomainResource.implicitRules | Equivalent | R5 `DomainResource.implicitRules` maps as Equivalent to R4 `DomainResource.implicitRules` |
| DomainResource.language | DomainResource.language | SourceIsNarrowerThanTarget | R5 `DomainResource.language` maps as SourceIsNarrowerThanTarget to R4 `DomainResource.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| DomainResource.meta | DomainResource.meta | Equivalent | R5 `DomainResource.meta` maps as Equivalent to R4 `DomainResource.meta` |
| DomainResource.modifierExtension | DomainResource.modifierExtension | SourceIsBroaderThanTarget | R5 `DomainResource.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `DomainResource.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| DomainResource.text | DomainResource.text | Equivalent | R5 `DomainResource.text` maps as Equivalent to R4 `DomainResource.text` |

