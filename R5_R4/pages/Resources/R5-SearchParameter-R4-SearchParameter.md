Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | SearchParameter |  | A search parameter that defines a named search item that can be used to search/filter on a resource. | 45 | 34 |
| Target | SearchParameter |  | A search parameter that defines a named search item that can be used to search/filter on a resource. | 40 | 29 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 6 |
Equivalent | 32 |
RelatedTo | 2 |
SourceIsBroaderThanTarget | 4 |
SourceIsNarrowerThanTarget | 1 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| SearchParameter | SearchParameter | Equivalent | R5 `SearchParameter` maps as Equivalent to R4 `SearchParameter` |
| SearchParameter.base | SearchParameter.base | RelatedTo | R5 `SearchParameter.base` maps as RelatedTo to R4 `SearchParameter.base` - (base failed to compare required binding of http://hl7.org/fhir/ValueSet/version-independent-all-resource-types|5.0.0 and http://hl7.org/fhir/ValueSet/resource-types|4.0.1); base has change due to type change: R5 `base` `code` maps as RelatedTo for R4 `base` |
| SearchParameter.chain | SearchParameter.chain | Equivalent | R5 `SearchParameter.chain` maps as Equivalent to R4 `SearchParameter.chain` |
| SearchParameter.code | SearchParameter.code | Equivalent | R5 `SearchParameter.code` maps as Equivalent to R4 `SearchParameter.code` |
| SearchParameter.comparator | SearchParameter.comparator | Equivalent | R5 `SearchParameter.comparator` maps as Equivalent to R4 `SearchParameter.comparator` - comparator has compatible required binding for code type: http://hl7.org/fhir/ValueSet/search-comparator|5.0.0 and http://hl7.org/fhir/ValueSet/search-comparator|4.0.1 (Equivalent) |
| SearchParameter.component | SearchParameter.component | Equivalent | R5 `SearchParameter.component` maps as Equivalent to R4 `SearchParameter.component` |
| SearchParameter.component.definition | SearchParameter.component.definition | Equivalent | R5 `SearchParameter.component.definition` maps as Equivalent to R4 `SearchParameter.component.definition` |
| SearchParameter.component.expression | SearchParameter.component.expression | Equivalent | R5 `SearchParameter.component.expression` maps as Equivalent to R4 `SearchParameter.component.expression` |
| SearchParameter.component.extension | SearchParameter.component.extension | SourceIsBroaderThanTarget | R5 `SearchParameter.component.extension` maps as SourceIsBroaderThanTarget to R4 `SearchParameter.component.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| SearchParameter.component.id | SearchParameter.component.id | Equivalent | R5 `SearchParameter.component.id` maps as Equivalent to R4 `SearchParameter.component.id` |
| SearchParameter.component.modifierExtension | SearchParameter.component.modifierExtension | SourceIsBroaderThanTarget | R5 `SearchParameter.component.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `SearchParameter.component.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| SearchParameter.constraint | - | DoesNotExistInTarget | R5 `SearchParameter.constraint` does not appear in the target and has no mapping for `SearchParameter`. |
| SearchParameter.contact | SearchParameter.contact | Equivalent | R5 `SearchParameter.contact` maps as Equivalent to R4 `SearchParameter.contact` |
| SearchParameter.contained | SearchParameter.contained | Equivalent | R5 `SearchParameter.contained` maps as Equivalent to R4 `SearchParameter.contained` |
| SearchParameter.copyright | - | DoesNotExistInTarget | R5 `SearchParameter.copyright` does not appear in the target and has no mapping for `SearchParameter`. |
| SearchParameter.copyrightLabel | - | DoesNotExistInTarget | R5 `SearchParameter.copyrightLabel` does not appear in the target and has no mapping for `SearchParameter`. |
| SearchParameter.date | SearchParameter.date | Equivalent | R5 `SearchParameter.date` maps as Equivalent to R4 `SearchParameter.date` |
| SearchParameter.derivedFrom | SearchParameter.derivedFrom | Equivalent | R5 `SearchParameter.derivedFrom` maps as Equivalent to R4 `SearchParameter.derivedFrom` |
| SearchParameter.description | SearchParameter.description | Equivalent | R5 `SearchParameter.description` maps as Equivalent to R4 `SearchParameter.description` |
| SearchParameter.experimental | SearchParameter.experimental | Equivalent | R5 `SearchParameter.experimental` maps as Equivalent to R4 `SearchParameter.experimental` |
| SearchParameter.expression | SearchParameter.expression | Equivalent | R5 `SearchParameter.expression` maps as Equivalent to R4 `SearchParameter.expression` |
| SearchParameter.extension | SearchParameter.extension | SourceIsBroaderThanTarget | R5 `SearchParameter.extension` maps as SourceIsBroaderThanTarget to R4 `SearchParameter.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| SearchParameter.id | SearchParameter.id | Equivalent | R5 `SearchParameter.id` maps as Equivalent to R4 `SearchParameter.id` |
| SearchParameter.identifier | - | DoesNotExistInTarget | R5 `SearchParameter.identifier` does not appear in the target and has no mapping for `SearchParameter`. |
| SearchParameter.implicitRules | SearchParameter.implicitRules | Equivalent | R5 `SearchParameter.implicitRules` maps as Equivalent to R4 `SearchParameter.implicitRules` |
| SearchParameter.jurisdiction | SearchParameter.jurisdiction | Equivalent | R5 `SearchParameter.jurisdiction` maps as Equivalent to R4 `SearchParameter.jurisdiction` |
| SearchParameter.language | SearchParameter.language | SourceIsNarrowerThanTarget | R5 `SearchParameter.language` maps as SourceIsNarrowerThanTarget to R4 `SearchParameter.language` - language changed the binding strength from Required to Preferred; language has change due to type change: R5 `language` `code` maps as SourceIsNarrowerThanTarget for R4 `language` |
| SearchParameter.meta | SearchParameter.meta | Equivalent | R5 `SearchParameter.meta` maps as Equivalent to R4 `SearchParameter.meta` |
| SearchParameter.modifier | SearchParameter.modifier | Equivalent | R5 `SearchParameter.modifier` maps as Equivalent to R4 `SearchParameter.modifier` - modifier has compatible required binding for code type: http://hl7.org/fhir/ValueSet/search-modifier-code|5.0.0 and http://hl7.org/fhir/ValueSet/search-modifier-code|4.0.1 (Equivalent) |
| SearchParameter.modifierExtension | SearchParameter.modifierExtension | SourceIsBroaderThanTarget | R5 `SearchParameter.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `SearchParameter.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| SearchParameter.multipleAnd | SearchParameter.multipleAnd | Equivalent | R5 `SearchParameter.multipleAnd` maps as Equivalent to R4 `SearchParameter.multipleAnd` |
| SearchParameter.multipleOr | SearchParameter.multipleOr | Equivalent | R5 `SearchParameter.multipleOr` maps as Equivalent to R4 `SearchParameter.multipleOr` |
| SearchParameter.name | SearchParameter.name | Equivalent | R5 `SearchParameter.name` maps as Equivalent to R4 `SearchParameter.name` |
| SearchParameter.processingMode | SearchParameter.xpathUsage | Equivalent | R5 `SearchParameter.processingMode` maps as Equivalent to R4 `SearchParameter.xpathUsage` - xpathUsage has compatible required binding for code type: http://hl7.org/fhir/ValueSet/search-processingmode|5.0.0 and http://hl7.org/fhir/ValueSet/search-xpath-usage|4.0.1 (Equivalent) |
| SearchParameter.publisher | SearchParameter.publisher | Equivalent | R5 `SearchParameter.publisher` maps as Equivalent to R4 `SearchParameter.publisher` |
| SearchParameter.purpose | SearchParameter.purpose | Equivalent | R5 `SearchParameter.purpose` maps as Equivalent to R4 `SearchParameter.purpose` |
| SearchParameter.status | SearchParameter.status | Equivalent | R5 `SearchParameter.status` maps as Equivalent to R4 `SearchParameter.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.0.1 (Equivalent) |
| SearchParameter.target | SearchParameter.target | RelatedTo | R5 `SearchParameter.target` maps as RelatedTo to R4 `SearchParameter.target` - (target failed to compare required binding of http://hl7.org/fhir/ValueSet/version-independent-all-resource-types|5.0.0 and http://hl7.org/fhir/ValueSet/resource-types|4.0.1); target has change due to type change: R5 `target` `code` maps as RelatedTo for R4 `target` |
| SearchParameter.text | SearchParameter.text | Equivalent | R5 `SearchParameter.text` maps as Equivalent to R4 `SearchParameter.text` |
| SearchParameter.title | - | DoesNotExistInTarget | R5 `SearchParameter.title` does not appear in the target and has no mapping for `SearchParameter`. |
| SearchParameter.type | SearchParameter.type | Equivalent | R5 `SearchParameter.type` maps as Equivalent to R4 `SearchParameter.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/search-param-type|5.0.0 and http://hl7.org/fhir/ValueSet/search-param-type|4.0.1 (Equivalent) |
| SearchParameter.url | SearchParameter.url | Equivalent | R5 `SearchParameter.url` maps as Equivalent to R4 `SearchParameter.url` |
| SearchParameter.useContext | SearchParameter.useContext | Equivalent | R5 `SearchParameter.useContext` maps as Equivalent to R4 `SearchParameter.useContext` |
| SearchParameter.version | SearchParameter.version | Equivalent | R5 `SearchParameter.version` maps as Equivalent to R4 `SearchParameter.version` |
| SearchParameter.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `SearchParameter.versionAlgorithm[x]` does not appear in the target and has no mapping for `SearchParameter`. |

