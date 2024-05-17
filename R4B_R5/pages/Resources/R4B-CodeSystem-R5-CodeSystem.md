Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | CodeSystem |  | The CodeSystem resource is used to declare the existence of and describe a code system or code system supplement and its key properties, and optionally define a part or all of its content. | 69 | 46 |
| Target | CodeSystem |  | The CodeSystem resource is used to declare the existence of and describe a code system or code system supplement and its key properties, and optionally define a part or all of its content. | 81 | 58 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 65 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| CodeSystem | CodeSystem | Equivalent | R4B `CodeSystem` maps as Equivalent to R5 `CodeSystem` |
| CodeSystem.caseSensitive | CodeSystem.caseSensitive | Equivalent | R4B `CodeSystem.caseSensitive` maps as Equivalent to R5 `CodeSystem.caseSensitive` |
| CodeSystem.compositional | CodeSystem.compositional | Equivalent | R4B `CodeSystem.compositional` maps as Equivalent to R5 `CodeSystem.compositional` |
| CodeSystem.concept | CodeSystem.concept | Equivalent | R4B `CodeSystem.concept` maps as Equivalent to R5 `CodeSystem.concept` |
| CodeSystem.concept.code | CodeSystem.concept.code | Equivalent | R4B `CodeSystem.concept.code` maps as Equivalent to R5 `CodeSystem.concept.code` |
| CodeSystem.concept.concept | CodeSystem.concept.concept | Equivalent | R4B `CodeSystem.concept.concept` maps as Equivalent to R5 `CodeSystem.concept.concept` |
| CodeSystem.concept.definition | CodeSystem.concept.definition | Equivalent | R4B `CodeSystem.concept.definition` maps as Equivalent to R5 `CodeSystem.concept.definition` |
| CodeSystem.concept.designation | CodeSystem.concept.designation | Equivalent | R4B `CodeSystem.concept.designation` maps as Equivalent to R5 `CodeSystem.concept.designation` |
| CodeSystem.concept.designation.extension | CodeSystem.concept.designation.extension | RelatedTo | R4B `CodeSystem.concept.designation.extension` maps as RelatedTo to R5 `CodeSystem.concept.designation.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| CodeSystem.concept.designation.id | CodeSystem.concept.designation.id | Equivalent | R4B `CodeSystem.concept.designation.id` maps as Equivalent to R5 `CodeSystem.concept.designation.id` |
| CodeSystem.concept.designation.language | CodeSystem.concept.designation.language | RelatedTo | R4B `CodeSystem.concept.designation.language` maps as RelatedTo to R5 `CodeSystem.concept.designation.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| CodeSystem.concept.designation.modifierExtension | CodeSystem.concept.designation.modifierExtension | RelatedTo | R4B `CodeSystem.concept.designation.modifierExtension` maps as RelatedTo to R5 `CodeSystem.concept.designation.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| CodeSystem.concept.designation.use | CodeSystem.concept.designation.use | Equivalent | R4B `CodeSystem.concept.designation.use` maps as Equivalent to R5 `CodeSystem.concept.designation.use` |
| CodeSystem.concept.designation.value | CodeSystem.concept.designation.value | Equivalent | R4B `CodeSystem.concept.designation.value` maps as Equivalent to R5 `CodeSystem.concept.designation.value` |
| CodeSystem.concept.display | CodeSystem.concept.display | Equivalent | R4B `CodeSystem.concept.display` maps as Equivalent to R5 `CodeSystem.concept.display` |
| CodeSystem.concept.extension | CodeSystem.concept.extension | RelatedTo | R4B `CodeSystem.concept.extension` maps as RelatedTo to R5 `CodeSystem.concept.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| CodeSystem.concept.id | CodeSystem.concept.id | Equivalent | R4B `CodeSystem.concept.id` maps as Equivalent to R5 `CodeSystem.concept.id` |
| CodeSystem.concept.modifierExtension | CodeSystem.concept.modifierExtension | RelatedTo | R4B `CodeSystem.concept.modifierExtension` maps as RelatedTo to R5 `CodeSystem.concept.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| CodeSystem.concept.property | CodeSystem.concept.property | Equivalent | R4B `CodeSystem.concept.property` maps as Equivalent to R5 `CodeSystem.concept.property` |
| CodeSystem.concept.property.code | CodeSystem.concept.property.code | Equivalent | R4B `CodeSystem.concept.property.code` maps as Equivalent to R5 `CodeSystem.concept.property.code` |
| CodeSystem.concept.property.extension | CodeSystem.concept.property.extension | RelatedTo | R4B `CodeSystem.concept.property.extension` maps as RelatedTo to R5 `CodeSystem.concept.property.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| CodeSystem.concept.property.id | CodeSystem.concept.property.id | Equivalent | R4B `CodeSystem.concept.property.id` maps as Equivalent to R5 `CodeSystem.concept.property.id` |
| CodeSystem.concept.property.modifierExtension | CodeSystem.concept.property.modifierExtension | RelatedTo | R4B `CodeSystem.concept.property.modifierExtension` maps as RelatedTo to R5 `CodeSystem.concept.property.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| CodeSystem.concept.property.value[x] | CodeSystem.concept.property.value[x] | Equivalent | R4B `CodeSystem.concept.property.value[x]` maps as Equivalent to R5 `CodeSystem.concept.property.value[x]` |
| CodeSystem.contact | CodeSystem.contact | Equivalent | R4B `CodeSystem.contact` maps as Equivalent to R5 `CodeSystem.contact` |
| CodeSystem.contained | CodeSystem.contained | Equivalent | R4B `CodeSystem.contained` maps as Equivalent to R5 `CodeSystem.contained` |
| CodeSystem.content | CodeSystem.content | Equivalent | R4B `CodeSystem.content` maps as Equivalent to R5 `CodeSystem.content` - content has compatible required binding for code type: http://hl7.org/fhir/ValueSet/codesystem-content-mode|4.3.0 and http://hl7.org/fhir/ValueSet/codesystem-content-mode|5.0.0 (Equivalent) |
| CodeSystem.copyright | CodeSystem.copyright | Equivalent | R4B `CodeSystem.copyright` maps as Equivalent to R5 `CodeSystem.copyright` |
| CodeSystem.count | CodeSystem.count | Equivalent | R4B `CodeSystem.count` maps as Equivalent to R5 `CodeSystem.count` |
| CodeSystem.date | CodeSystem.date | Equivalent | R4B `CodeSystem.date` maps as Equivalent to R5 `CodeSystem.date` |
| CodeSystem.description | CodeSystem.description | Equivalent | R4B `CodeSystem.description` maps as Equivalent to R5 `CodeSystem.description` |
| CodeSystem.experimental | CodeSystem.experimental | Equivalent | R4B `CodeSystem.experimental` maps as Equivalent to R5 `CodeSystem.experimental` |
| CodeSystem.extension | CodeSystem.extension | RelatedTo | R4B `CodeSystem.extension` maps as RelatedTo to R5 `CodeSystem.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| CodeSystem.filter | CodeSystem.filter | Equivalent | R4B `CodeSystem.filter` maps as Equivalent to R5 `CodeSystem.filter` |
| CodeSystem.filter.code | CodeSystem.filter.code | Equivalent | R4B `CodeSystem.filter.code` maps as Equivalent to R5 `CodeSystem.filter.code` |
| CodeSystem.filter.description | CodeSystem.filter.description | Equivalent | R4B `CodeSystem.filter.description` maps as Equivalent to R5 `CodeSystem.filter.description` |
| CodeSystem.filter.extension | CodeSystem.filter.extension | RelatedTo | R4B `CodeSystem.filter.extension` maps as RelatedTo to R5 `CodeSystem.filter.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| CodeSystem.filter.id | CodeSystem.filter.id | Equivalent | R4B `CodeSystem.filter.id` maps as Equivalent to R5 `CodeSystem.filter.id` |
| CodeSystem.filter.modifierExtension | CodeSystem.filter.modifierExtension | RelatedTo | R4B `CodeSystem.filter.modifierExtension` maps as RelatedTo to R5 `CodeSystem.filter.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| CodeSystem.filter.operator | CodeSystem.filter.operator | Equivalent | R4B `CodeSystem.filter.operator` maps as Equivalent to R5 `CodeSystem.filter.operator` - operator has compatible required binding for code type: http://hl7.org/fhir/ValueSet/filter-operator|4.3.0 and http://hl7.org/fhir/ValueSet/filter-operator|5.0.0 (Equivalent) |
| CodeSystem.filter.value | CodeSystem.filter.value | Equivalent | R4B `CodeSystem.filter.value` maps as Equivalent to R5 `CodeSystem.filter.value` |
| CodeSystem.hierarchyMeaning | CodeSystem.hierarchyMeaning | Equivalent | R4B `CodeSystem.hierarchyMeaning` maps as Equivalent to R5 `CodeSystem.hierarchyMeaning` - hierarchyMeaning has compatible required binding for code type: http://hl7.org/fhir/ValueSet/codesystem-hierarchy-meaning|4.3.0 and http://hl7.org/fhir/ValueSet/codesystem-hierarchy-meaning|5.0.0 (Equivalent) |
| CodeSystem.id | CodeSystem.id | Equivalent | R4B `CodeSystem.id` maps as Equivalent to R5 `CodeSystem.id` |
| CodeSystem.identifier | CodeSystem.identifier | Equivalent | R4B `CodeSystem.identifier` maps as Equivalent to R5 `CodeSystem.identifier` |
| CodeSystem.implicitRules | CodeSystem.implicitRules | Equivalent | R4B `CodeSystem.implicitRules` maps as Equivalent to R5 `CodeSystem.implicitRules` |
| CodeSystem.jurisdiction | CodeSystem.jurisdiction | Equivalent | R4B `CodeSystem.jurisdiction` maps as Equivalent to R5 `CodeSystem.jurisdiction` |
| CodeSystem.language | CodeSystem.language | RelatedTo | R4B `CodeSystem.language` maps as RelatedTo to R5 `CodeSystem.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| CodeSystem.meta | CodeSystem.meta | Equivalent | R4B `CodeSystem.meta` maps as Equivalent to R5 `CodeSystem.meta` |
| CodeSystem.modifierExtension | CodeSystem.modifierExtension | RelatedTo | R4B `CodeSystem.modifierExtension` maps as RelatedTo to R5 `CodeSystem.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| CodeSystem.name | CodeSystem.name | Equivalent | R4B `CodeSystem.name` maps as Equivalent to R5 `CodeSystem.name` |
| CodeSystem.property | CodeSystem.property | Equivalent | R4B `CodeSystem.property` maps as Equivalent to R5 `CodeSystem.property` |
| CodeSystem.property.code | CodeSystem.property.code | Equivalent | R4B `CodeSystem.property.code` maps as Equivalent to R5 `CodeSystem.property.code` |
| CodeSystem.property.description | CodeSystem.property.description | Equivalent | R4B `CodeSystem.property.description` maps as Equivalent to R5 `CodeSystem.property.description` |
| CodeSystem.property.extension | CodeSystem.property.extension | RelatedTo | R4B `CodeSystem.property.extension` maps as RelatedTo to R5 `CodeSystem.property.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| CodeSystem.property.id | CodeSystem.property.id | Equivalent | R4B `CodeSystem.property.id` maps as Equivalent to R5 `CodeSystem.property.id` |
| CodeSystem.property.modifierExtension | CodeSystem.property.modifierExtension | RelatedTo | R4B `CodeSystem.property.modifierExtension` maps as RelatedTo to R5 `CodeSystem.property.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| CodeSystem.property.type | CodeSystem.property.type | Equivalent | R4B `CodeSystem.property.type` maps as Equivalent to R5 `CodeSystem.property.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/concept-property-type|4.3.0 and http://hl7.org/fhir/ValueSet/concept-property-type|5.0.0 (Equivalent) |
| CodeSystem.property.uri | CodeSystem.property.uri | Equivalent | R4B `CodeSystem.property.uri` maps as Equivalent to R5 `CodeSystem.property.uri` |
| CodeSystem.publisher | CodeSystem.publisher | Equivalent | R4B `CodeSystem.publisher` maps as Equivalent to R5 `CodeSystem.publisher` |
| CodeSystem.purpose | CodeSystem.purpose | Equivalent | R4B `CodeSystem.purpose` maps as Equivalent to R5 `CodeSystem.purpose` |
| CodeSystem.status | CodeSystem.status | Equivalent | R4B `CodeSystem.status` maps as Equivalent to R5 `CodeSystem.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| CodeSystem.supplements | CodeSystem.supplements | Equivalent | R4B `CodeSystem.supplements` maps as Equivalent to R5 `CodeSystem.supplements` |
| CodeSystem.text | CodeSystem.text | Equivalent | R4B `CodeSystem.text` maps as Equivalent to R5 `CodeSystem.text` |
| CodeSystem.title | CodeSystem.title | Equivalent | R4B `CodeSystem.title` maps as Equivalent to R5 `CodeSystem.title` |
| CodeSystem.url | CodeSystem.url | Equivalent | R4B `CodeSystem.url` maps as Equivalent to R5 `CodeSystem.url` |
| CodeSystem.useContext | CodeSystem.useContext | Equivalent | R4B `CodeSystem.useContext` maps as Equivalent to R5 `CodeSystem.useContext` |
| CodeSystem.valueSet | CodeSystem.valueSet | Equivalent | R4B `CodeSystem.valueSet` maps as Equivalent to R5 `CodeSystem.valueSet` |
| CodeSystem.version | CodeSystem.version | Equivalent | R4B `CodeSystem.version` maps as Equivalent to R5 `CodeSystem.version` |
| CodeSystem.versionNeeded | CodeSystem.versionNeeded | Equivalent | R4B `CodeSystem.versionNeeded` maps as Equivalent to R5 `CodeSystem.versionNeeded` |

