Comparison of hl7.fhir.r4b.core#4.3.0 and hl7.fhir.r5.core#5.0.0
Generated at Thursday, May 16, 2024 11:17:04 AM

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | NamingSystem |  | A curated namespace that issues unique symbols within that namespace for the identification of concepts, people, devices, etc.  Represents a "System" used within the Identifier and Coding data types. | 30 | 19 |
| Target | NamingSystem |  | A curated namespace that issues unique symbols within that namespace for the identification of concepts, people, devices, etc.  Represents a "System" used within the Identifier and Coding data types. | 49 | 38 |


Comparison Result: RelatedTo


### Mapping details

| Status | Count |
| ------ | ----- |
Equivalent | 4 |
RelatedTo | 26 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| NamingSystem | NamingSystem | Equivalent | R4B `NamingSystem` maps as Equivalent to R5 `NamingSystem` |
| NamingSystem.contact | NamingSystem.contact | Equivalent | R4B `NamingSystem.contact` maps as Equivalent to R5 `NamingSystem.contact` |
| NamingSystem.contained | NamingSystem.contained | Equivalent | R4B `NamingSystem.contained` maps as Equivalent to R5 `NamingSystem.contained` |
| NamingSystem.date | NamingSystem.date | Equivalent | R4B `NamingSystem.date` maps as Equivalent to R5 `NamingSystem.date` |
| NamingSystem.description | NamingSystem.description | Equivalent | R4B `NamingSystem.description` maps as Equivalent to R5 `NamingSystem.description` |
| NamingSystem.extension | NamingSystem.extension | RelatedTo | R4B `NamingSystem.extension` maps as RelatedTo to R5 `NamingSystem.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| NamingSystem.id | NamingSystem.id | Equivalent | R4B `NamingSystem.id` maps as Equivalent to R5 `NamingSystem.id` |
| NamingSystem.implicitRules | NamingSystem.implicitRules | Equivalent | R4B `NamingSystem.implicitRules` maps as Equivalent to R5 `NamingSystem.implicitRules` |
| NamingSystem.jurisdiction | NamingSystem.jurisdiction | Equivalent | R4B `NamingSystem.jurisdiction` maps as Equivalent to R5 `NamingSystem.jurisdiction` |
| NamingSystem.kind | NamingSystem.kind | Equivalent | R4B `NamingSystem.kind` maps as Equivalent to R5 `NamingSystem.kind` - kind has compatible required binding for code type: http://hl7.org/fhir/ValueSet/namingsystem-type|4.3.0 and http://hl7.org/fhir/ValueSet/namingsystem-type|5.0.0 (Equivalent) |
| NamingSystem.language | NamingSystem.language | RelatedTo | R4B `NamingSystem.language` maps as RelatedTo to R5 `NamingSystem.language` - language made the binding required (from Preferred) for http://hl7.org/fhir/ValueSet/all-languages|5.0.0 |
| NamingSystem.meta | NamingSystem.meta | Equivalent | R4B `NamingSystem.meta` maps as Equivalent to R5 `NamingSystem.meta` |
| NamingSystem.modifierExtension | NamingSystem.modifierExtension | RelatedTo | R4B `NamingSystem.modifierExtension` maps as RelatedTo to R5 `NamingSystem.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| NamingSystem.name | NamingSystem.name | Equivalent | R4B `NamingSystem.name` maps as Equivalent to R5 `NamingSystem.name` |
| NamingSystem.publisher | NamingSystem.publisher | Equivalent | R4B `NamingSystem.publisher` maps as Equivalent to R5 `NamingSystem.publisher` |
| NamingSystem.responsible | NamingSystem.responsible | Equivalent | R4B `NamingSystem.responsible` maps as Equivalent to R5 `NamingSystem.responsible` |
| NamingSystem.status | NamingSystem.status | Equivalent | R4B `NamingSystem.status` maps as Equivalent to R5 `NamingSystem.status` - status has compatible required binding for code type: http://hl7.org/fhir/ValueSet/publication-status|4.3.0 and http://hl7.org/fhir/ValueSet/publication-status|5.0.0 (Equivalent) |
| NamingSystem.text | NamingSystem.text | Equivalent | R4B `NamingSystem.text` maps as Equivalent to R5 `NamingSystem.text` |
| NamingSystem.type | NamingSystem.type | RelatedTo | R4B `NamingSystem.type` maps as RelatedTo to R5 `NamingSystem.type` - type changed the binding strength from Extensible to Preferred |
| NamingSystem.uniqueId | NamingSystem.uniqueId | Equivalent | R4B `NamingSystem.uniqueId` maps as Equivalent to R5 `NamingSystem.uniqueId` |
| NamingSystem.uniqueId.comment | NamingSystem.uniqueId.comment | Equivalent | R4B `NamingSystem.uniqueId.comment` maps as Equivalent to R5 `NamingSystem.uniqueId.comment` |
| NamingSystem.uniqueId.extension | NamingSystem.uniqueId.extension | RelatedTo | R4B `NamingSystem.uniqueId.extension` maps as RelatedTo to R5 `NamingSystem.uniqueId.extension` - extension has change due to type change: R4B `extension` `Extension` maps as RelatedTo for R5 `extension` |
| NamingSystem.uniqueId.id | NamingSystem.uniqueId.id | Equivalent | R4B `NamingSystem.uniqueId.id` maps as Equivalent to R5 `NamingSystem.uniqueId.id` |
| NamingSystem.uniqueId.modifierExtension | NamingSystem.uniqueId.modifierExtension | RelatedTo | R4B `NamingSystem.uniqueId.modifierExtension` maps as RelatedTo to R5 `NamingSystem.uniqueId.modifierExtension` - modifierExtension has change due to type change: R4B `modifierExtension` `Extension` maps as RelatedTo for R5 `modifierExtension` |
| NamingSystem.uniqueId.period | NamingSystem.uniqueId.period | Equivalent | R4B `NamingSystem.uniqueId.period` maps as Equivalent to R5 `NamingSystem.uniqueId.period` |
| NamingSystem.uniqueId.preferred | NamingSystem.uniqueId.preferred | Equivalent | R4B `NamingSystem.uniqueId.preferred` maps as Equivalent to R5 `NamingSystem.uniqueId.preferred` |
| NamingSystem.uniqueId.type | NamingSystem.uniqueId.type | Equivalent | R4B `NamingSystem.uniqueId.type` maps as Equivalent to R5 `NamingSystem.uniqueId.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/namingsystem-identifier-type|4.3.0 and http://hl7.org/fhir/ValueSet/namingsystem-identifier-type|5.0.0 (Equivalent) |
| NamingSystem.uniqueId.value | NamingSystem.uniqueId.value | Equivalent | R4B `NamingSystem.uniqueId.value` maps as Equivalent to R5 `NamingSystem.uniqueId.value` |
| NamingSystem.usage | NamingSystem.usage | Equivalent | R4B `NamingSystem.usage` maps as Equivalent to R5 `NamingSystem.usage` |
| NamingSystem.useContext | NamingSystem.useContext | Equivalent | R4B `NamingSystem.useContext` maps as Equivalent to R5 `NamingSystem.useContext` |

