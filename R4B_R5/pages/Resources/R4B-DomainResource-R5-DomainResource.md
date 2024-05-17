Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

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
| DomainResource | DomainResource | Equivalent | R4B `DomainResource` maps as Equivalent to R5 `DomainResource` |
| DomainResource.contained | DomainResource.contained | Equivalent | R4B `DomainResource.contained` maps as Equivalent to R5 `DomainResource.contained` |
| DomainResource.extension | DomainResource.extension | RelatedTo | R4B `DomainResource.extension` maps as RelatedTo to R5 `DomainResource.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| DomainResource.id | DomainResource.id | Equivalent | R4B `DomainResource.id` maps as Equivalent to R5 `DomainResource.id` |
| DomainResource.implicitRules | DomainResource.implicitRules | Equivalent | R4B `DomainResource.implicitRules` maps as Equivalent to R5 `DomainResource.implicitRules` |
| DomainResource.language | DomainResource.language | RelatedTo | R4B `DomainResource.language` maps as RelatedTo to R5 `DomainResource.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| DomainResource.meta | DomainResource.meta | Equivalent | R4B `DomainResource.meta` maps as Equivalent to R5 `DomainResource.meta` |
| DomainResource.modifierExtension | DomainResource.modifierExtension | RelatedTo | R4B `DomainResource.modifierExtension` maps as RelatedTo to R5 `DomainResource.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| DomainResource.text | DomainResource.text | Equivalent | R4B `DomainResource.text` maps as Equivalent to R5 `DomainResource.text` |

