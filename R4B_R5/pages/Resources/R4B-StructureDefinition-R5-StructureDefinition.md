Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | StructureDefinition |  | A definition of a FHIR structure. This resource is used to describe the underlying resources, data types defined in FHIR, and also for describing extensions and constraints on resources and data types. | 56 | 36 |
| Target | StructureDefinition |  | A definition of a FHIR structure. This resource is used to describe the underlying resources, data types defined in FHIR, and also for describing extensions and constraints on resources and data types. | 58 | 38 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 52 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| StructureDefinition | StructureDefinition | Equivalent | R4B `StructureDefinition` maps as Equivalent to R5 `StructureDefinition` |
| StructureDefinition.abstract | StructureDefinition.abstract | Equivalent | R4B `StructureDefinition.abstract` maps as Equivalent to R5 `StructureDefinition.abstract` |
| StructureDefinition.baseDefinition | StructureDefinition.baseDefinition | Equivalent | R4B `StructureDefinition.baseDefinition` maps as Equivalent to R5 `StructureDefinition.baseDefinition` |
| StructureDefinition.contact | StructureDefinition.contact | Equivalent | R4B `StructureDefinition.contact` maps as Equivalent to R5 `StructureDefinition.contact` |
| StructureDefinition.contained | StructureDefinition.contained | Equivalent | R4B `StructureDefinition.contained` maps as Equivalent to R5 `StructureDefinition.contained` |
| StructureDefinition.context | StructureDefinition.context | Equivalent | R4B `StructureDefinition.context` maps as Equivalent to R5 `StructureDefinition.context` |
| StructureDefinition.context.expression | StructureDefinition.context.expression | Equivalent | R4B `StructureDefinition.context.expression` maps as Equivalent to R5 `StructureDefinition.context.expression` |
| StructureDefinition.context.extension | StructureDefinition.context.extension | RelatedTo | R4B `StructureDefinition.context.extension` maps as RelatedTo to R5 `StructureDefinition.context.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| StructureDefinition.context.id | StructureDefinition.context.id | Equivalent | R4B `StructureDefinition.context.id` maps as Equivalent to R5 `StructureDefinition.context.id` |
| StructureDefinition.context.modifierExtension | StructureDefinition.context.modifierExtension | RelatedTo | R4B `StructureDefinition.context.modifierExtension` maps as RelatedTo to R5 `StructureDefinition.context.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| StructureDefinition.context.type | StructureDefinition.context.type | Equivalent | R4B `StructureDefinition.context.type` maps as Equivalent to R5 `StructureDefinition.context.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/extension-context-type|4.3.0 and http://hl7.org/fhir/ValueSet/extension-context-type|5.0.0 (Equivalent) |
| StructureDefinition.contextInvariant | StructureDefinition.contextInvariant | Equivalent | R4B `StructureDefinition.contextInvariant` maps as Equivalent to R5 `StructureDefinition.contextInvariant` |
| StructureDefinition.copyright | StructureDefinition.copyright | Equivalent | R4B `StructureDefinition.copyright` maps as Equivalent to R5 `StructureDefinition.copyright` |
| StructureDefinition.date | StructureDefinition.date | Equivalent | R4B `StructureDefinition.date` maps as Equivalent to R5 `StructureDefinition.date` |
| StructureDefinition.derivation | StructureDefinition.derivation | Equivalent | R4B `StructureDefinition.derivation` maps as Equivalent to R5 `StructureDefinition.derivation` - derivation has compatible required binding for code type: http://hl7.org/fhir/ValueSet/type-derivation-rule|4.3.0 and http://hl7.org/fhir/ValueSet/type-derivation-rule|5.0.0 (Equivalent) |
| StructureDefinition.description | StructureDefinition.description | Equivalent | R4B `StructureDefinition.description` maps as Equivalent to R5 `StructureDefinition.description` |
| StructureDefinition.differential | StructureDefinition.differential | Equivalent | R4B `StructureDefinition.differential` maps as Equivalent to R5 `StructureDefinition.differential` |
| StructureDefinition.differential.element | StructureDefinition.differential.element | RelatedTo | R4B `StructureDefinition.differential.element` maps as RelatedTo to R5 `StructureDefinition.differential.element` - element has change due to type change: R4B `element` `ElementDefinition` maps as RelatedTo for R5 `element` |
| StructureDefinition.differential.extension | StructureDefinition.differential.extension | RelatedTo | R4B `StructureDefinition.differential.extension` maps as RelatedTo to R5 `StructureDefinition.differential.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| StructureDefinition.differential.id | StructureDefinition.differential.id | Equivalent | R4B `StructureDefinition.differential.id` maps as Equivalent to R5 `StructureDefinition.differential.id` |
| StructureDefinition.differential.modifierExtension | StructureDefinition.differential.modifierExtension | RelatedTo | R4B `StructureDefinition.differential.modifierExtension` maps as RelatedTo to R5 `StructureDefinition.differential.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| StructureDefinition.experimental | StructureDefinition.experimental | Equivalent | R4B `StructureDefinition.experimental` maps as Equivalent to R5 `StructureDefinition.experimental` |
| StructureDefinition.extension | StructureDefinition.extension | RelatedTo | R4B `StructureDefinition.extension` maps as RelatedTo to R5 `StructureDefinition.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| StructureDefinition.fhirVersion | StructureDefinition.fhirVersion | Equivalent | R4B `StructureDefinition.fhirVersion` maps as Equivalent to R5 `StructureDefinition.fhirVersion` - fhirVersion has compatible required binding for code type: http://hl7.org/fhir/ValueSet/FHIR-version|4.3.0 and http://hl7.org/fhir/ValueSet/FHIR-version|5.0.0 (Equivalent) |
| StructureDefinition.id | StructureDefinition.id | Equivalent | R4B `StructureDefinition.id` maps as Equivalent to R5 `StructureDefinition.id` |
| StructureDefinition.identifier | StructureDefinition.identifier | Equivalent | R4B `StructureDefinition.identifier` maps as Equivalent to R5 `StructureDefinition.identifier` |
| StructureDefinition.implicitRules | StructureDefinition.implicitRules | Equivalent | R4B `StructureDefinition.implicitRules` maps as Equivalent to R5 `StructureDefinition.implicitRules` |
| StructureDefinition.jurisdiction | StructureDefinition.jurisdiction | Equivalent | R4B `StructureDefinition.jurisdiction` maps as Equivalent to R5 `StructureDefinition.jurisdiction` |
| StructureDefinition.keyword | StructureDefinition.keyword | Equivalent | R4B `StructureDefinition.keyword` maps as Equivalent to R5 `StructureDefinition.keyword` |
| StructureDefinition.kind | StructureDefinition.kind | Equivalent | R4B `StructureDefinition.kind` maps as Equivalent to R5 `StructureDefinition.kind` - kind has compatible required binding for code type: http://hl7.org/fhir/ValueSet/structure-definition-kind|4.3.0 and http://hl7.org/fhir/ValueSet/structure-definition-kind|5.0.0 (Equivalent) |
| StructureDefinition.language | StructureDefinition.language | RelatedTo | R4B `StructureDefinition.language` maps as RelatedTo to R5 `StructureDefinition.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| StructureDefinition.mapping | StructureDefinition.mapping | Equivalent | R4B `StructureDefinition.mapping` maps as Equivalent to R5 `StructureDefinition.mapping` |
| StructureDefinition.mapping.comment | StructureDefinition.mapping.comment | Equivalent | R4B `StructureDefinition.mapping.comment` maps as Equivalent to R5 `StructureDefinition.mapping.comment` |
| StructureDefinition.mapping.extension | StructureDefinition.mapping.extension | RelatedTo | R4B `StructureDefinition.mapping.extension` maps as RelatedTo to R5 `StructureDefinition.mapping.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| StructureDefinition.mapping.id | StructureDefinition.mapping.id | Equivalent | R4B `StructureDefinition.mapping.id` maps as Equivalent to R5 `StructureDefinition.mapping.id` |
| StructureDefinition.mapping.identity | StructureDefinition.mapping.identity | Equivalent | R4B `StructureDefinition.mapping.identity` maps as Equivalent to R5 `StructureDefinition.mapping.identity` |
| StructureDefinition.mapping.modifierExtension | StructureDefinition.mapping.modifierExtension | RelatedTo | R4B `StructureDefinition.mapping.modifierExtension` maps as RelatedTo to R5 `StructureDefinition.mapping.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| StructureDefinition.mapping.name | StructureDefinition.mapping.name | Equivalent | R4B `StructureDefinition.mapping.name` maps as Equivalent to R5 `StructureDefinition.mapping.name` |
| StructureDefinition.mapping.uri | StructureDefinition.mapping.uri | Equivalent | R4B `StructureDefinition.mapping.uri` maps as Equivalent to R5 `StructureDefinition.mapping.uri` |
| StructureDefinition.meta | StructureDefinition.meta | Equivalent | R4B `StructureDefinition.meta` maps as Equivalent to R5 `StructureDefinition.meta` |
| StructureDefinition.modifierExtension | StructureDefinition.modifierExtension | RelatedTo | R4B `StructureDefinition.modifierExtension` maps as RelatedTo to R5 `StructureDefinition.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| StructureDefinition.name | StructureDefinition.name | Equivalent | R4B `StructureDefinition.name` maps as Equivalent to R5 `StructureDefinition.name` |
| StructureDefinition.publisher | StructureDefinition.publisher | Equivalent | R4B `StructureDefinition.publisher` maps as Equivalent to R5 `StructureDefinition.publisher` |
| StructureDefinition.purpose | StructureDefinition.purpose | Equivalent | R4B `StructureDefinition.purpose` maps as Equivalent to R5 `StructureDefinition.purpose` |
| StructureDefinition.snapshot | StructureDefinition.snapshot | Equivalent | R4B `StructureDefinition.snapshot` maps as Equivalent to R5 `StructureDefinition.snapshot` |
| StructureDefinition.snapshot.element | StructureDefinition.snapshot.element | RelatedTo | R4B `StructureDefinition.snapshot.element` maps as RelatedTo to R5 `StructureDefinition.snapshot.element` - element has change due to type change: R4B `element` `ElementDefinition` maps as RelatedTo for R5 `element` |
| StructureDefinition.snapshot.extension | StructureDefinition.snapshot.extension | RelatedTo | R4B `StructureDefinition.snapshot.extension` maps as RelatedTo to R5 `StructureDefinition.snapshot.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| StructureDefinition.snapshot.id | StructureDefinition.snapshot.id | Equivalent | R4B `StructureDefinition.snapshot.id` maps as Equivalent to R5 `StructureDefinition.snapshot.id` |
| StructureDefinition.snapshot.modifierExtension | StructureDefinition.snapshot.modifierExtension | RelatedTo | R4B `StructureDefinition.snapshot.modifierExtension` maps as RelatedTo to R5 `StructureDefinition.snapshot.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| StructureDefinition.status | StructureDefinition.status | Equivalent | R4B `StructureDefinition.status` maps as Equivalent to R5 `StructureDefinition.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| StructureDefinition.text | StructureDefinition.text | Equivalent | R4B `StructureDefinition.text` maps as Equivalent to R5 `StructureDefinition.text` |
| StructureDefinition.title | StructureDefinition.title | Equivalent | R4B `StructureDefinition.title` maps as Equivalent to R5 `StructureDefinition.title` |
| StructureDefinition.type | StructureDefinition.type | Equivalent | R4B `StructureDefinition.type` maps as Equivalent to R5 `StructureDefinition.type` |
| StructureDefinition.url | StructureDefinition.url | Equivalent | R4B `StructureDefinition.url` maps as Equivalent to R5 `StructureDefinition.url` |
| StructureDefinition.useContext | StructureDefinition.useContext | Equivalent | R4B `StructureDefinition.useContext` maps as Equivalent to R5 `StructureDefinition.useContext` |
| StructureDefinition.version | StructureDefinition.version | Equivalent | R4B `StructureDefinition.version` maps as Equivalent to R5 `StructureDefinition.version` |

