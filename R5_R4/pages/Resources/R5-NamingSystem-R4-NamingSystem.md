Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1
Generated at Thursday, July 25, 2024 3:56:51 PM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | NamingSystem |  | A curated namespace that issues unique symbols within that namespace for the identification of concepts, people, devices, etc.  Represents a "System" used within the Identifier and Coding data types. | 49 | 38 |
| Target | NamingSystem |  | A curated namespace that issues unique symbols within that namespace for the identification of concepts, people, devices, etc.  Represents a "System" used within the Identifier and Coding data types. | 30 | 19 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 19 |
Equivalent | 4 |
RelatedTo | 26 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| NamingSystem | NamingSystem | Equivalent | R5 `NamingSystem` maps as Equivalent to R4 `NamingSystem` |
| NamingSystem.approvalDate | - | DoesNotExistInTarget | R5 `NamingSystem.approvalDate` does not appear in the target and has no mapping for `NamingSystem`. |
| NamingSystem.author | - | DoesNotExistInTarget | R5 `NamingSystem.author` does not appear in the target and has no mapping for `NamingSystem`. |
| NamingSystem.contact | NamingSystem.contact | Equivalent | R5 `NamingSystem.contact` maps as Equivalent to R4 `NamingSystem.contact` |
| NamingSystem.contained | NamingSystem.contained | Equivalent | R5 `NamingSystem.contained` maps as Equivalent to R4 `NamingSystem.contained` |
| NamingSystem.copyright | - | DoesNotExistInTarget | R5 `NamingSystem.copyright` does not appear in the target and has no mapping for `NamingSystem`. |
| NamingSystem.copyrightLabel | - | DoesNotExistInTarget | R5 `NamingSystem.copyrightLabel` does not appear in the target and has no mapping for `NamingSystem`. |
| NamingSystem.date | NamingSystem.date | Equivalent | R5 `NamingSystem.date` maps as Equivalent to R4 `NamingSystem.date` |
| NamingSystem.description | NamingSystem.description | Equivalent | R5 `NamingSystem.description` maps as Equivalent to R4 `NamingSystem.description` |
| NamingSystem.editor | - | DoesNotExistInTarget | R5 `NamingSystem.editor` does not appear in the target and has no mapping for `NamingSystem`. |
| NamingSystem.effectivePeriod | - | DoesNotExistInTarget | R5 `NamingSystem.effectivePeriod` does not appear in the target and has no mapping for `NamingSystem`. |
| NamingSystem.endorser | - | DoesNotExistInTarget | R5 `NamingSystem.endorser` does not appear in the target and has no mapping for `NamingSystem`. |
| NamingSystem.experimental | - | DoesNotExistInTarget | R5 `NamingSystem.experimental` does not appear in the target and has no mapping for `NamingSystem`. |
| NamingSystem.extension | NamingSystem.extension | SourceIsBroaderThanTarget | R5 `NamingSystem.extension` maps as SourceIsBroaderThanTarget to R4 `NamingSystem.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| NamingSystem.id | NamingSystem.id | Equivalent | R5 `NamingSystem.id` maps as Equivalent to R4 `NamingSystem.id` |
| NamingSystem.identifier | - | DoesNotExistInTarget | R5 `NamingSystem.identifier` does not appear in the target and has no mapping for `NamingSystem`. |
| NamingSystem.implicitRules | NamingSystem.implicitRules | Equivalent | R5 `NamingSystem.implicitRules` maps as Equivalent to R4 `NamingSystem.implicitRules` |
| NamingSystem.jurisdiction | NamingSystem.jurisdiction | Equivalent | R5 `NamingSystem.jurisdiction` maps as Equivalent to R4 `NamingSystem.jurisdiction` |
| NamingSystem.kind | NamingSystem.kind | Equivalent | R5 `NamingSystem.kind` maps as Equivalent to R4 `NamingSystem.kind` - kind has compatible required binding for code type: http://hl7.org/fhir/ValueSet/namingsystem-type|5.0.0 and http://hl7.org/fhir/ValueSet/namingsystem-type|4.0.1 (Equivalent) |
| NamingSystem.language | NamingSystem.language | RelatedTo | R5 `NamingSystem.language` maps as RelatedTo to R4 `NamingSystem.language` - language changed the binding strength from Required to Preferred |
| NamingSystem.lastReviewDate | - | DoesNotExistInTarget | R5 `NamingSystem.lastReviewDate` does not appear in the target and has no mapping for `NamingSystem`. |
| NamingSystem.meta | NamingSystem.meta | Equivalent | R5 `NamingSystem.meta` maps as Equivalent to R4 `NamingSystem.meta` |
| NamingSystem.modifierExtension | NamingSystem.modifierExtension | SourceIsBroaderThanTarget | R5 `NamingSystem.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `NamingSystem.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| NamingSystem.name | NamingSystem.name | Equivalent | R5 `NamingSystem.name` maps as Equivalent to R4 `NamingSystem.name` |
| NamingSystem.publisher | NamingSystem.publisher | Equivalent | R5 `NamingSystem.publisher` maps as Equivalent to R4 `NamingSystem.publisher` |
| NamingSystem.purpose | - | DoesNotExistInTarget | R5 `NamingSystem.purpose` does not appear in the target and has no mapping for `NamingSystem`. |
| NamingSystem.relatedArtifact | - | DoesNotExistInTarget | R5 `NamingSystem.relatedArtifact` does not appear in the target and has no mapping for `NamingSystem`. |
| NamingSystem.responsible | NamingSystem.responsible | Equivalent | R5 `NamingSystem.responsible` maps as Equivalent to R4 `NamingSystem.responsible` |
| NamingSystem.reviewer | - | DoesNotExistInTarget | R5 `NamingSystem.reviewer` does not appear in the target and has no mapping for `NamingSystem`. |
| NamingSystem.status | NamingSystem.status | Equivalent | R5 `NamingSystem.status` maps as Equivalent to R4 `NamingSystem.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|5.0.0 and http://hl7.org/fhir/ValueSet/publication-status|4.0.1 (Equivalent) |
| NamingSystem.text | NamingSystem.text | Equivalent | R5 `NamingSystem.text` maps as Equivalent to R4 `NamingSystem.text` |
| NamingSystem.title | - | DoesNotExistInTarget | R5 `NamingSystem.title` does not appear in the target and has no mapping for `NamingSystem`. |
| NamingSystem.topic | - | DoesNotExistInTarget | R5 `NamingSystem.topic` does not appear in the target and has no mapping for `NamingSystem`. |
| NamingSystem.type | NamingSystem.type | RelatedTo | R5 `NamingSystem.type` maps as RelatedTo to R4 `NamingSystem.type` - type changed the binding strength from Preferred to Extensible |
| NamingSystem.uniqueId | NamingSystem.uniqueId | Equivalent | R5 `NamingSystem.uniqueId` maps as Equivalent to R4 `NamingSystem.uniqueId` |
| NamingSystem.uniqueId.authoritative | - | DoesNotExistInTarget | R5 `NamingSystem.uniqueId.authoritative` does not appear in the target and has no mapping for `NamingSystem`. |
| NamingSystem.uniqueId.comment | NamingSystem.uniqueId.comment | Equivalent | R5 `NamingSystem.uniqueId.comment` maps as Equivalent to R4 `NamingSystem.uniqueId.comment` |
| NamingSystem.uniqueId.extension | NamingSystem.uniqueId.extension | SourceIsBroaderThanTarget | R5 `NamingSystem.uniqueId.extension` maps as SourceIsBroaderThanTarget to R4 `NamingSystem.uniqueId.extension` - extension has change due to type change: R5 `extension` `Extension` maps as SourceIsBroaderThanTarget for R4 `extension` |
| NamingSystem.uniqueId.id | NamingSystem.uniqueId.id | Equivalent | R5 `NamingSystem.uniqueId.id` maps as Equivalent to R4 `NamingSystem.uniqueId.id` |
| NamingSystem.uniqueId.modifierExtension | NamingSystem.uniqueId.modifierExtension | SourceIsBroaderThanTarget | R5 `NamingSystem.uniqueId.modifierExtension` maps as SourceIsBroaderThanTarget to R4 `NamingSystem.uniqueId.modifierExtension` - modifierExtension has change due to type change: R5 `modifierExtension` `Extension` maps as SourceIsBroaderThanTarget for R4 `modifierExtension` |
| NamingSystem.uniqueId.period | NamingSystem.uniqueId.period | Equivalent | R5 `NamingSystem.uniqueId.period` maps as Equivalent to R4 `NamingSystem.uniqueId.period` |
| NamingSystem.uniqueId.preferred | NamingSystem.uniqueId.preferred | Equivalent | R5 `NamingSystem.uniqueId.preferred` maps as Equivalent to R4 `NamingSystem.uniqueId.preferred` |
| NamingSystem.uniqueId.type | NamingSystem.uniqueId.type | Equivalent | R5 `NamingSystem.uniqueId.type` maps as Equivalent to R4 `NamingSystem.uniqueId.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/namingsystem-identifier-type|5.0.0 and http://hl7.org/fhir/ValueSet/namingsystem-identifier-type|4.0.1 (Equivalent) |
| NamingSystem.uniqueId.value | NamingSystem.uniqueId.value | Equivalent | R5 `NamingSystem.uniqueId.value` maps as Equivalent to R4 `NamingSystem.uniqueId.value` |
| NamingSystem.url | - | DoesNotExistInTarget | R5 `NamingSystem.url` does not appear in the target and has no mapping for `NamingSystem`. |
| NamingSystem.usage | NamingSystem.usage | Equivalent | R5 `NamingSystem.usage` maps as Equivalent to R4 `NamingSystem.usage` |
| NamingSystem.useContext | NamingSystem.useContext | Equivalent | R5 `NamingSystem.useContext` maps as Equivalent to R4 `NamingSystem.useContext` |
| NamingSystem.version | - | DoesNotExistInTarget | R5 `NamingSystem.version` does not appear in the target and has no mapping for `NamingSystem`. |
| NamingSystem.versionAlgorithm[x] | - | DoesNotExistInTarget | R5 `NamingSystem.versionAlgorithm[x]` does not appear in the target and has no mapping for `NamingSystem`. |

