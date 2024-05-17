Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | CompartmentDefinition |  | A compartment definition that defines how resources are accessed on a server. | 29 | 18 |
| Target | CompartmentDefinition |  | A compartment definition that defines how resources are accessed on a server. | 33 | 22 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 25 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| CompartmentDefinition | CompartmentDefinition | Equivalent | R4B `CompartmentDefinition` maps as Equivalent to R5 `CompartmentDefinition` |
| CompartmentDefinition.code | CompartmentDefinition.code | Equivalent | R4B `CompartmentDefinition.code` maps as Equivalent to R5 `CompartmentDefinition.code` - code has compatible required binding for code type: http://hl7.org/fhir/ValueSet/compartment-type|4.3.0 and http://hl7.org/fhir/ValueSet/compartment-type|5.0.0 (Equivalent) |
| CompartmentDefinition.contact | CompartmentDefinition.contact | Equivalent | R4B `CompartmentDefinition.contact` maps as Equivalent to R5 `CompartmentDefinition.contact` |
| CompartmentDefinition.contained | CompartmentDefinition.contained | Equivalent | R4B `CompartmentDefinition.contained` maps as Equivalent to R5 `CompartmentDefinition.contained` |
| CompartmentDefinition.date | CompartmentDefinition.date | Equivalent | R4B `CompartmentDefinition.date` maps as Equivalent to R5 `CompartmentDefinition.date` |
| CompartmentDefinition.description | CompartmentDefinition.description | Equivalent | R4B `CompartmentDefinition.description` maps as Equivalent to R5 `CompartmentDefinition.description` |
| CompartmentDefinition.experimental | CompartmentDefinition.experimental | Equivalent | R4B `CompartmentDefinition.experimental` maps as Equivalent to R5 `CompartmentDefinition.experimental` |
| CompartmentDefinition.extension | CompartmentDefinition.extension | RelatedTo | R4B `CompartmentDefinition.extension` maps as RelatedTo to R5 `CompartmentDefinition.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| CompartmentDefinition.id | CompartmentDefinition.id | Equivalent | R4B `CompartmentDefinition.id` maps as Equivalent to R5 `CompartmentDefinition.id` |
| CompartmentDefinition.implicitRules | CompartmentDefinition.implicitRules | Equivalent | R4B `CompartmentDefinition.implicitRules` maps as Equivalent to R5 `CompartmentDefinition.implicitRules` |
| CompartmentDefinition.language | CompartmentDefinition.language | RelatedTo | R4B `CompartmentDefinition.language` maps as RelatedTo to R5 `CompartmentDefinition.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| CompartmentDefinition.meta | CompartmentDefinition.meta | Equivalent | R4B `CompartmentDefinition.meta` maps as Equivalent to R5 `CompartmentDefinition.meta` |
| CompartmentDefinition.modifierExtension | CompartmentDefinition.modifierExtension | RelatedTo | R4B `CompartmentDefinition.modifierExtension` maps as RelatedTo to R5 `CompartmentDefinition.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| CompartmentDefinition.name | CompartmentDefinition.name | Equivalent | R4B `CompartmentDefinition.name` maps as Equivalent to R5 `CompartmentDefinition.name` |
| CompartmentDefinition.publisher | CompartmentDefinition.publisher | Equivalent | R4B `CompartmentDefinition.publisher` maps as Equivalent to R5 `CompartmentDefinition.publisher` |
| CompartmentDefinition.purpose | CompartmentDefinition.purpose | Equivalent | R4B `CompartmentDefinition.purpose` maps as Equivalent to R5 `CompartmentDefinition.purpose` |
| CompartmentDefinition.resource | CompartmentDefinition.resource | Equivalent | R4B `CompartmentDefinition.resource` maps as Equivalent to R5 `CompartmentDefinition.resource` |
| CompartmentDefinition.resource.code | CompartmentDefinition.resource.code | Equivalent | R4B `CompartmentDefinition.resource.code` maps as Equivalent to R5 `CompartmentDefinition.resource.code` - code has compatible required binding for code type: http://hl7.org/fhir/ValueSet/resource-types|4.3.0 and http://hl7.org/fhir/ValueSet/resource-types|5.0.0 (Equivalent) |
| CompartmentDefinition.resource.documentation | CompartmentDefinition.resource.documentation | Equivalent | R4B `CompartmentDefinition.resource.documentation` maps as Equivalent to R5 `CompartmentDefinition.resource.documentation` |
| CompartmentDefinition.resource.extension | CompartmentDefinition.resource.extension | RelatedTo | R4B `CompartmentDefinition.resource.extension` maps as RelatedTo to R5 `CompartmentDefinition.resource.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| CompartmentDefinition.resource.id | CompartmentDefinition.resource.id | Equivalent | R4B `CompartmentDefinition.resource.id` maps as Equivalent to R5 `CompartmentDefinition.resource.id` |
| CompartmentDefinition.resource.modifierExtension | CompartmentDefinition.resource.modifierExtension | RelatedTo | R4B `CompartmentDefinition.resource.modifierExtension` maps as RelatedTo to R5 `CompartmentDefinition.resource.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| CompartmentDefinition.resource.param | CompartmentDefinition.resource.param | Equivalent | R4B `CompartmentDefinition.resource.param` maps as Equivalent to R5 `CompartmentDefinition.resource.param` |
| CompartmentDefinition.search | CompartmentDefinition.search | Equivalent | R4B `CompartmentDefinition.search` maps as Equivalent to R5 `CompartmentDefinition.search` |
| CompartmentDefinition.status | CompartmentDefinition.status | Equivalent | R4B `CompartmentDefinition.status` maps as Equivalent to R5 `CompartmentDefinition.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| CompartmentDefinition.text | CompartmentDefinition.text | Equivalent | R4B `CompartmentDefinition.text` maps as Equivalent to R5 `CompartmentDefinition.text` |
| CompartmentDefinition.url | CompartmentDefinition.url | Equivalent | R4B `CompartmentDefinition.url` maps as Equivalent to R5 `CompartmentDefinition.url` |
| CompartmentDefinition.useContext | CompartmentDefinition.useContext | Equivalent | R4B `CompartmentDefinition.useContext` maps as Equivalent to R5 `CompartmentDefinition.useContext` |
| CompartmentDefinition.version | CompartmentDefinition.version | Equivalent | R4B `CompartmentDefinition.version` maps as Equivalent to R5 `CompartmentDefinition.version` |

