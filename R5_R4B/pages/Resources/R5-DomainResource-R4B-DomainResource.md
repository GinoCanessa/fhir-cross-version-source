Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | DomainResource |  | A resource that includes narrative, extensions, and contained resources. | 9 | 5 |
| Target | DomainResource |  | A resource that includes narrative, extensions, and contained resources. | 9 | 5 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 5 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| DomainResource | DomainResource | Equivalent | R5 `DomainResource` maps as Equivalent to R4B `DomainResource` |
| DomainResource.contained | DomainResource.contained | Equivalent | R5 `DomainResource.contained` maps as Equivalent to R4B `DomainResource.contained` |
| DomainResource.extension | DomainResource.extension | SourceIsBroaderThanTarget | R5 `DomainResource.extension` maps as SourceIsBroaderThanTarget to R4B `DomainResource.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| DomainResource.id | DomainResource.id | Equivalent | R5 `DomainResource.id` maps as Equivalent to R4B `DomainResource.id` |
| DomainResource.implicitRules | DomainResource.implicitRules | Equivalent | R5 `DomainResource.implicitRules` maps as Equivalent to R4B `DomainResource.implicitRules` |
| DomainResource.language | DomainResource.language | RelatedTo | R5 `DomainResource.language` maps as RelatedTo to R4B `DomainResource.language` - language changed the binding strength from Required to Preferred |
| DomainResource.meta | DomainResource.meta | Equivalent | R5 `DomainResource.meta` maps as Equivalent to R4B `DomainResource.meta` |
| DomainResource.modifierExtension | DomainResource.modifierExtension | SourceIsBroaderThanTarget | R5 `DomainResource.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `DomainResource.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| DomainResource.text | DomainResource.text | Equivalent | R5 `DomainResource.text` maps as Equivalent to R4B `DomainResource.text` |

