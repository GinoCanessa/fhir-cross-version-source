Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:50 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | CompartmentDefinition |  | A compartment definition that defines how resources are accessed on a server. | 33 | 22 |
| Target | CompartmentDefinition |  | A compartment definition that defines how resources are accessed on a server. | 29 | 18 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 4 |
Equivalent | 4 |
RelatedTo | 25 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| CompartmentDefinition | CompartmentDefinition | Equivalent | R5 `CompartmentDefinition` maps as Equivalent to R4 `CompartmentDefinition` |
| CompartmentDefinition.code | CompartmentDefinition.code | Equivalent | R5 `CompartmentDefinition.code` maps as Equivalent to R4 `CompartmentDefinition.code` - code has compatible required binding for code type: http://hl7.org/fhir/ValueSet/compartment-type|5.0.0 and http://hl7.org/fhir/ValueSet/compartment-type|4.0.1 (Equivalent) |
| CompartmentDefinition.contact | CompartmentDefinition.contact | Equivalent | R5 `CompartmentDefinition.contact` maps as Equivalent to R4 `CompartmentDefinition.contact` |
| CompartmentDefinition.contained | CompartmentDefinition.contained | Equivalent | R5 `CompartmentDefinition.contained` maps as Equivalent to R4 `CompartmentDefinition.contained` |
| CompartmentDefinition.date | CompartmentDefinition.date | Equivalent | R5 `CompartmentDefinition.date` maps as Equivalent to R4 `CompartmentDefinition.date` |
| CompartmentDefinition.description | CompartmentDefinition.description | Equivalent | R5 `CompartmentDefinition.description` maps as Equivalent to R4 `CompartmentDefinition.description` |
| CompartmentDefinition.experimental | CompartmentDefinition.experimental | Equivalent | R5 `CompartmentDefinition.experimental` maps as Equivalent to R4 `CompartmentDefinition.experimental` |
| CompartmentDefinition.extension | CompartmentDefinition.extension | SourceIsBroaderThanTarget | R5 `CompartmentDefinition.extension` maps as SourceIsBroaderThanTarget to R4 `CompartmentDefinition.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| CompartmentDefinition.id | CompartmentDefinition.id | Equivalent | R5 `CompartmentDefinition.id` maps as Equivalent to R4 `CompartmentDefinition.id` |
| CompartmentDefinition.implicitRules | CompartmentDefinition.implicitRules | Equivalent | R5 `CompartmentDefinition.implicitRules` maps as Equivalent to R4 `CompartmentDefinition.implicitRules` |
| CompartmentDefinition.language | CompartmentDefinition.language | RelatedTo | R5 `CompartmentDefinition.language` maps as RelatedTo to R4 `CompartmentDefinition.language` - language changed the binding strength from Required to Preferred |
| CompartmentDefinition.meta | CompartmentDefinition.meta | Equivalent | R5 `CompartmentDefinition.meta` maps as Equivalent to R4 `CompartmentDefinition.meta` |
| CompartmentDefinition.modifierExtension | CompartmentDefinition.modifierExtension | SourceIsBroaderThanTarget | R5 `CompartmentDefinition.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `CompartmentDefinition.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| CompartmentDefinition.name | CompartmentDefinition.name | Equivalent | R5 `CompartmentDefinition.name` maps as Equivalent to R4 `CompartmentDefinition.name` |
| CompartmentDefinition.publisher | CompartmentDefinition.publisher | Equivalent | R5 `CompartmentDefinition.publisher` maps as Equivalent to R4 `CompartmentDefinition.publisher` |
| CompartmentDefinition.purpose | CompartmentDefinition.purpose | Equivalent | R5 `CompartmentDefinition.purpose` maps as Equivalent to R4 `CompartmentDefinition.purpose` |
| CompartmentDefinition.resource | CompartmentDefinition.resource | Equivalent | R5 `CompartmentDefinition.resource` maps as Equivalent to R4 `CompartmentDefinition.resource` |
| CompartmentDefinition.resource.code | CompartmentDefinition.resource.code | Equivalent | R5 `CompartmentDefinition.resource.code` maps as Equivalent to R4 `CompartmentDefinition.resource.code` - code has compatible required binding for code type: http://hl7.org/fhir/ValueSet/resource-types|5.0.0 and http://hl7.org/fhir/ValueSet/resource-types|4.0.1 (Equivalent) |
| CompartmentDefinition.resource.documentation | CompartmentDefinition.resource.documentation | Equivalent | R5 `CompartmentDefinition.resource.documentation` maps as Equivalent to R4 `CompartmentDefinition.resource.documentation` |
| CompartmentDefinition.resource.endParam | - | DoesNotExistInTarget | R5 `CompartmentDefinition.resource.endParam` does not appear in the target and has no mapping for `CompartmentDefinition`. |
| CompartmentDefinition.resource.extension | CompartmentDefinition.resource.extension | SourceIsBroaderThanTarget | R5 `CompartmentDefinition.resource.extension` maps as SourceIsBroaderThanTarget to R4 `CompartmentDefinition.resource.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| CompartmentDefinition.resource.id | CompartmentDefinition.resource.id | Equivalent | R5 `CompartmentDefinition.resource.id` maps as Equivalent to R4 `CompartmentDefinition.resource.id` |
| CompartmentDefinition.resource.modifierExtension | CompartmentDefinition.resource.modifierExtension | SourceIsBroaderThanTarget | R5 `CompartmentDefinition.resource.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `CompartmentDefinition.resource.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| CompartmentDefinition.resource.param | CompartmentDefinition.resource.param | Equivalent | R5 `CompartmentDefinition.resource.param` maps as Equivalent to R4 `CompartmentDefinition.resource.param` |
| CompartmentDefinition.resource.startParam | - | DoesNotExistInTarget | R5 `CompartmentDefinition.resource.startParam` does not appear in the target and has no mapping for `CompartmentDefinition`. |
| CompartmentDefinition.search | CompartmentDefinition.search | Equivalent | R5 `CompartmentDefinition.search` maps as Equivalent to R4 `CompartmentDefinition.search` |
| CompartmentDefinition.status | CompartmentDefinition.status | Equivalent | R5 `CompartmentDefinition.status` maps as Equivalent to R4 `CompartmentDefinition.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.0.1 (Equivalent) |
| CompartmentDefinition.text | CompartmentDefinition.text | Equivalent | R5 `CompartmentDefinition.text` maps as Equivalent to R4 `CompartmentDefinition.text` |
| CompartmentDefinition.title | - | DoesNotExistInTarget | R5 `CompartmentDefinition.title` does not appear in the target and has no mapping for `CompartmentDefinition`. |
| CompartmentDefinition.url | CompartmentDefinition.url | Equivalent | R5 `CompartmentDefinition.url` maps as Equivalent to R4 `CompartmentDefinition.url` |
| CompartmentDefinition.useContext | CompartmentDefinition.useContext | Equivalent | R5 `CompartmentDefinition.useContext` maps as Equivalent to R4 `CompartmentDefinition.useContext` |
| CompartmentDefinition.version | CompartmentDefinition.version | Equivalent | R5 `CompartmentDefinition.version` maps as Equivalent to R4 `CompartmentDefinition.version` |
| CompartmentDefinition.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `CompartmentDefinition.versionAlgorithm[x]` does not appear in the target and has no mapping for `CompartmentDefinition`. |

