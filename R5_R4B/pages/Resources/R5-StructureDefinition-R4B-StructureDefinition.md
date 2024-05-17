Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4b.core#4.3.0
Generated at Wednesday, May 15, 2024 11:14:36 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | StructureDefinition |  | A definition of a FHIR structure. This resource is used to describe the underlying resources, data types defined in FHIR, and also for describing extensions and constraints on resources and data types. | 58 | 38 |
| Target | StructureDefinition |  | A definition of a FHIR structure. This resource is used to describe the underlying resources, data types defined in FHIR, and also for describing extensions and constraints on resources and data types. | 56 | 36 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 2 |
Equivalent | 4 |
RelatedTo | 52 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| StructureDefinition | StructureDefinition | Equivalent | R5 `StructureDefinition` maps as Equivalent to R4B `StructureDefinition` |
| StructureDefinition.abstract | StructureDefinition.abstract | Equivalent | R5 `StructureDefinition.abstract` maps as Equivalent to R4B `StructureDefinition.abstract` |
| StructureDefinition.baseDefinition | StructureDefinition.baseDefinition | Equivalent | R5 `StructureDefinition.baseDefinition` maps as Equivalent to R4B `StructureDefinition.baseDefinition` |
| StructureDefinition.contact | StructureDefinition.contact | Equivalent | R5 `StructureDefinition.contact` maps as Equivalent to R4B `StructureDefinition.contact` |
| StructureDefinition.contained | StructureDefinition.contained | Equivalent | R5 `StructureDefinition.contained` maps as Equivalent to R4B `StructureDefinition.contained` |
| StructureDefinition.context | StructureDefinition.context | Equivalent | R5 `StructureDefinition.context` maps as Equivalent to R4B `StructureDefinition.context` |
| StructureDefinition.context.expression | StructureDefinition.context.expression | Equivalent | R5 `StructureDefinition.context.expression` maps as Equivalent to R4B `StructureDefinition.context.expression` |
| StructureDefinition.context.extension | StructureDefinition.context.extension | SourceIsBroaderThanTarget | R5 `StructureDefinition.context.extension` maps as SourceIsBroaderThanTarget to R4B `StructureDefinition.context.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| StructureDefinition.context.id | StructureDefinition.context.id | Equivalent | R5 `StructureDefinition.context.id` maps as Equivalent to R4B `StructureDefinition.context.id` |
| StructureDefinition.context.modifierExtension | StructureDefinition.context.modifierExtension | SourceIsBroaderThanTarget | R5 `StructureDefinition.context.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `StructureDefinition.context.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| StructureDefinition.context.type | StructureDefinition.context.type | Equivalent | R5 `StructureDefinition.context.type` maps as Equivalent to R4B `StructureDefinition.context.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/extension-context-type|5.0.0 and http://hl7.org/fhir/ValueSet/extension-context-type|4.3.0 (Equivalent) |
| StructureDefinition.contextInvariant | StructureDefinition.contextInvariant | Equivalent | R5 `StructureDefinition.contextInvariant` maps as Equivalent to R4B `StructureDefinition.contextInvariant` |
| StructureDefinition.copyright | StructureDefinition.copyright | Equivalent | R5 `StructureDefinition.copyright` maps as Equivalent to R4B `StructureDefinition.copyright` |
| StructureDefinition.copyrightLabel | - | DoesNotExistInTarget | R5 `StructureDefinition.copyrightLabel` does not appear in the target and has no mapping for `StructureDefinition`. |
| StructureDefinition.date | StructureDefinition.date | Equivalent | R5 `StructureDefinition.date` maps as Equivalent to R4B `StructureDefinition.date` |
| StructureDefinition.derivation | StructureDefinition.derivation | Equivalent | R5 `StructureDefinition.derivation` maps as Equivalent to R4B `StructureDefinition.derivation` - derivation has compatible required binding for code type: http://hl7.org/fhir/ValueSet/type-derivation-rule|5.0.0 and http://hl7.org/fhir/ValueSet/type-derivation-rule|4.3.0 (Equivalent) |
| StructureDefinition.description | StructureDefinition.description | Equivalent | R5 `StructureDefinition.description` maps as Equivalent to R4B `StructureDefinition.description` |
| StructureDefinition.differential | StructureDefinition.differential | Equivalent | R5 `StructureDefinition.differential` maps as Equivalent to R4B `StructureDefinition.differential` |
| StructureDefinition.differential.element | StructureDefinition.differential.element | SourceIsBroaderThanTarget | R5 `StructureDefinition.differential.element` maps as SourceIsBroaderThanTarget to R4B `StructureDefinition.differential.element` - element has change due to type change: R5 `element` `ElementDefinition` maps as SourceIsBroaderThanTarget for R4B `element` |
| StructureDefinition.differential.extension | StructureDefinition.differential.extension | SourceIsBroaderThanTarget | R5 `StructureDefinition.differential.extension` maps as SourceIsBroaderThanTarget to R4B `StructureDefinition.differential.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| StructureDefinition.differential.id | StructureDefinition.differential.id | Equivalent | R5 `StructureDefinition.differential.id` maps as Equivalent to R4B `StructureDefinition.differential.id` |
| StructureDefinition.differential.modifierExtension | StructureDefinition.differential.modifierExtension | SourceIsBroaderThanTarget | R5 `StructureDefinition.differential.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `StructureDefinition.differential.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| StructureDefinition.experimental | StructureDefinition.experimental | Equivalent | R5 `StructureDefinition.experimental` maps as Equivalent to R4B `StructureDefinition.experimental` |
| StructureDefinition.extension | StructureDefinition.extension | SourceIsBroaderThanTarget | R5 `StructureDefinition.extension` maps as SourceIsBroaderThanTarget to R4B `StructureDefinition.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| StructureDefinition.fhirVersion | StructureDefinition.fhirVersion | Equivalent | R5 `StructureDefinition.fhirVersion` maps as Equivalent to R4B `StructureDefinition.fhirVersion` - fhirVersion has compatible required binding for code type: http://hl7.org/fhir/ValueSet/FHIR-version|5.0.0 and http://hl7.org/fhir/ValueSet/FHIR-version|4.3.0 (Equivalent) |
| StructureDefinition.id | StructureDefinition.id | Equivalent | R5 `StructureDefinition.id` maps as Equivalent to R4B `StructureDefinition.id` |
| StructureDefinition.identifier | StructureDefinition.identifier | Equivalent | R5 `StructureDefinition.identifier` maps as Equivalent to R4B `StructureDefinition.identifier` |
| StructureDefinition.implicitRules | StructureDefinition.implicitRules | Equivalent | R5 `StructureDefinition.implicitRules` maps as Equivalent to R4B `StructureDefinition.implicitRules` |
| StructureDefinition.jurisdiction | StructureDefinition.jurisdiction | Equivalent | R5 `StructureDefinition.jurisdiction` maps as Equivalent to R4B `StructureDefinition.jurisdiction` |
| StructureDefinition.keyword | StructureDefinition.keyword | Equivalent | R5 `StructureDefinition.keyword` maps as Equivalent to R4B `StructureDefinition.keyword` |
| StructureDefinition.kind | StructureDefinition.kind | Equivalent | R5 `StructureDefinition.kind` maps as Equivalent to R4B `StructureDefinition.kind` - kind has compatible required binding for code type: http://hl7.org/fhir/ValueSet/structure-definition-kind|5.0.0 and http://hl7.org/fhir/ValueSet/structure-definition-kind|4.3.0 (Equivalent) |
| StructureDefinition.language | StructureDefinition.language | RelatedTo | R5 `StructureDefinition.language` maps as RelatedTo to R4B `StructureDefinition.language` - language changed the binding strength from Required to Preferred |
| StructureDefinition.mapping | StructureDefinition.mapping | Equivalent | R5 `StructureDefinition.mapping` maps as Equivalent to R4B `StructureDefinition.mapping` |
| StructureDefinition.mapping.comment | StructureDefinition.mapping.comment | Equivalent | R5 `StructureDefinition.mapping.comment` maps as Equivalent to R4B `StructureDefinition.mapping.comment` |
| StructureDefinition.mapping.extension | StructureDefinition.mapping.extension | SourceIsBroaderThanTarget | R5 `StructureDefinition.mapping.extension` maps as SourceIsBroaderThanTarget to R4B `StructureDefinition.mapping.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| StructureDefinition.mapping.id | StructureDefinition.mapping.id | Equivalent | R5 `StructureDefinition.mapping.id` maps as Equivalent to R4B `StructureDefinition.mapping.id` |
| StructureDefinition.mapping.identity | StructureDefinition.mapping.identity | Equivalent | R5 `StructureDefinition.mapping.identity` maps as Equivalent to R4B `StructureDefinition.mapping.identity` |
| StructureDefinition.mapping.modifierExtension | StructureDefinition.mapping.modifierExtension | SourceIsBroaderThanTarget | R5 `StructureDefinition.mapping.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `StructureDefinition.mapping.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| StructureDefinition.mapping.name | StructureDefinition.mapping.name | Equivalent | R5 `StructureDefinition.mapping.name` maps as Equivalent to R4B `StructureDefinition.mapping.name` |
| StructureDefinition.mapping.uri | StructureDefinition.mapping.uri | Equivalent | R5 `StructureDefinition.mapping.uri` maps as Equivalent to R4B `StructureDefinition.mapping.uri` |
| StructureDefinition.meta | StructureDefinition.meta | Equivalent | R5 `StructureDefinition.meta` maps as Equivalent to R4B `StructureDefinition.meta` |
| StructureDefinition.modifierExtension | StructureDefinition.modifierExtension | SourceIsBroaderThanTarget | R5 `StructureDefinition.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `StructureDefinition.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| StructureDefinition.name | StructureDefinition.name | Equivalent | R5 `StructureDefinition.name` maps as Equivalent to R4B `StructureDefinition.name` |
| StructureDefinition.publisher | StructureDefinition.publisher | Equivalent | R5 `StructureDefinition.publisher` maps as Equivalent to R4B `StructureDefinition.publisher` |
| StructureDefinition.purpose | StructureDefinition.purpose | Equivalent | R5 `StructureDefinition.purpose` maps as Equivalent to R4B `StructureDefinition.purpose` |
| StructureDefinition.snapshot | StructureDefinition.snapshot | Equivalent | R5 `StructureDefinition.snapshot` maps as Equivalent to R4B `StructureDefinition.snapshot` |
| StructureDefinition.snapshot.element | StructureDefinition.snapshot.element | SourceIsBroaderThanTarget | R5 `StructureDefinition.snapshot.element` maps as SourceIsBroaderThanTarget to R4B `StructureDefinition.snapshot.element` - element has change due to type change: R5 `element` `ElementDefinition` maps as SourceIsBroaderThanTarget for R4B `element` |
| StructureDefinition.snapshot.extension | StructureDefinition.snapshot.extension | SourceIsBroaderThanTarget | R5 `StructureDefinition.snapshot.extension` maps as SourceIsBroaderThanTarget to R4B `StructureDefinition.snapshot.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4B `extension` |
| StructureDefinition.snapshot.id | StructureDefinition.snapshot.id | Equivalent | R5 `StructureDefinition.snapshot.id` maps as Equivalent to R4B `StructureDefinition.snapshot.id` |
| StructureDefinition.snapshot.modifierExtension | StructureDefinition.snapshot.modifierExtension | SourceIsBroaderThanTarget | R5 `StructureDefinition.snapshot.modifierExtension` maps as SourceIsBroaderThanTarget to R4B `StructureDefinition.snapshot.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4B `modifierExtension` |
| StructureDefinition.status | StructureDefinition.status | Equivalent | R5 `StructureDefinition.status` maps as Equivalent to R4B `StructureDefinition.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.3.0 (Equivalent) |
| StructureDefinition.text | StructureDefinition.text | Equivalent | R5 `StructureDefinition.text` maps as Equivalent to R4B `StructureDefinition.text` |
| StructureDefinition.title | StructureDefinition.title | Equivalent | R5 `StructureDefinition.title` maps as Equivalent to R4B `StructureDefinition.title` |
| StructureDefinition.type | StructureDefinition.type | Equivalent | R5 `StructureDefinition.type` maps as Equivalent to R4B `StructureDefinition.type` |
| StructureDefinition.url | StructureDefinition.url | Equivalent | R5 `StructureDefinition.url` maps as Equivalent to R4B `StructureDefinition.url` |
| StructureDefinition.useContext | StructureDefinition.useContext | Equivalent | R5 `StructureDefinition.useContext` maps as Equivalent to R4B `StructureDefinition.useContext` |
| StructureDefinition.version | StructureDefinition.version | Equivalent | R5 `StructureDefinition.version` maps as Equivalent to R4B `StructureDefinition.version` |
| StructureDefinition.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `StructureDefinition.versionAlgorithm[x]` does not appear in the target and has no mapping for `StructureDefinition`. |

