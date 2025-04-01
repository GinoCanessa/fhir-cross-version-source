Comparison of 
Generated at Tuesday, April 1, 2025 1:39:33 PM

### TerminologyCapabilities

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | TerminologyCapabilities |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/TerminologyCapabilities` |
| Version | 4.3.0 |
| Description | A TerminologyCapabilities resource documents a set of capabilities (behaviors) of a FHIR Terminology Server that may be used as a statement of actual server functionality or a statement of required or desired server implementation. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1775` |
| Database Snapshot Count | `88` |
| Database Differential Count | `50` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `TerminologyCapabilities` | `TerminologyCapabilities` | `TerminologyCapabilities` | TerminologyCapabilities | A statement of system capabilities | 0..* | TerminologyCapabilities |  |  |
| `TerminologyCapabilities.closure` | `TerminologyCapabilities.closure` | `closure` | TerminologyCapabilities.closure | Information about the [ConceptMap/$closure](conceptmap-operation-closure.html) operation | 0..1 | BackboneElement |  |  |
| `TerminologyCapabilities.closure.extension` | `TerminologyCapabilities.closure.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TerminologyCapabilities.closure.id` | `TerminologyCapabilities.closure.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TerminologyCapabilities.closure.modifierExtension` | `TerminologyCapabilities.closure.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TerminologyCapabilities.closure.translation` | `TerminologyCapabilities.closure.translation` | `translation` | TerminologyCapabilities.closure.translation | If cross-system closure is supported | 0..1 | boolean |  |  |
| `TerminologyCapabilities.codeSearch` | `TerminologyCapabilities.codeSearch` | `codeSearch` | TerminologyCapabilities.codeSearch | explicit \| all | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/code-search-support|4.3.0` |
| `TerminologyCapabilities.codeSystem` | `TerminologyCapabilities.codeSystem` | `codeSystem` | TerminologyCapabilities.codeSystem | A code system supported by the server | 0..* | BackboneElement |  |  |
| `TerminologyCapabilities.codeSystem.extension` | `TerminologyCapabilities.codeSystem.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TerminologyCapabilities.codeSystem.id` | `TerminologyCapabilities.codeSystem.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TerminologyCapabilities.codeSystem.modifierExtension` | `TerminologyCapabilities.codeSystem.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TerminologyCapabilities.codeSystem.subsumption` | `TerminologyCapabilities.codeSystem.subsumption` | `subsumption` | TerminologyCapabilities.codeSystem.subsumption | Whether subsumption is supported | 0..1 | boolean |  |  |
| `TerminologyCapabilities.codeSystem.uri` | `TerminologyCapabilities.codeSystem.uri` | `uri` | TerminologyCapabilities.codeSystem.uri | URI for the Code System | 0..1 | canonical(http://hl7.org/fhir/StructureDefinition/CodeSystem) |  |  |
| `TerminologyCapabilities.codeSystem.version` | `TerminologyCapabilities.codeSystem.version` | `version` | TerminologyCapabilities.codeSystem.version | Version of Code System supported | 0..* | BackboneElement |  |  |
| `TerminologyCapabilities.codeSystem.version.code` | `TerminologyCapabilities.codeSystem.version.code` | `code` | TerminologyCapabilities.codeSystem.version.code | Version identifier for this version | 0..1 | string |  |  |
| `TerminologyCapabilities.codeSystem.version.compositional` | `TerminologyCapabilities.codeSystem.version.compositional` | `compositional` | TerminologyCapabilities.codeSystem.version.compositional | If compositional grammar is supported | 0..1 | boolean |  |  |
| `TerminologyCapabilities.codeSystem.version.extension` | `TerminologyCapabilities.codeSystem.version.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TerminologyCapabilities.codeSystem.version.filter` | `TerminologyCapabilities.codeSystem.version.filter` | `filter` | TerminologyCapabilities.codeSystem.version.filter | Filter Properties supported | 0..* | BackboneElement |  |  |
| `TerminologyCapabilities.codeSystem.version.filter.code` | `TerminologyCapabilities.codeSystem.version.filter.code` | `code` | TerminologyCapabilities.codeSystem.version.filter.code | Code of the property supported | 1..1 | code |  |  |
| `TerminologyCapabilities.codeSystem.version.filter.extension` | `TerminologyCapabilities.codeSystem.version.filter.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TerminologyCapabilities.codeSystem.version.filter.id` | `TerminologyCapabilities.codeSystem.version.filter.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TerminologyCapabilities.codeSystem.version.filter.modifierExtension` | `TerminologyCapabilities.codeSystem.version.filter.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TerminologyCapabilities.codeSystem.version.filter.op` | `TerminologyCapabilities.codeSystem.version.filter.op` | `op` | TerminologyCapabilities.codeSystem.version.filter.op | Operations supported for the property | 1..* | code |  |  |
| `TerminologyCapabilities.codeSystem.version.id` | `TerminologyCapabilities.codeSystem.version.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TerminologyCapabilities.codeSystem.version.isDefault` | `TerminologyCapabilities.codeSystem.version.isDefault` | `isDefault` | TerminologyCapabilities.codeSystem.version.isDefault | If this is the default version for this code system | 0..1 | boolean |  |  |
| `TerminologyCapabilities.codeSystem.version.language` | `TerminologyCapabilities.codeSystem.version.language` | `language` | TerminologyCapabilities.codeSystem.version.language | Language Displays supported | 0..* | code |  |  |
| `TerminologyCapabilities.codeSystem.version.modifierExtension` | `TerminologyCapabilities.codeSystem.version.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TerminologyCapabilities.codeSystem.version.property` | `TerminologyCapabilities.codeSystem.version.property` | `property` | TerminologyCapabilities.codeSystem.version.property | Properties supported for $lookup | 0..* | code |  |  |
| `TerminologyCapabilities.contact` | `TerminologyCapabilities.contact` | `contact` | TerminologyCapabilities.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `TerminologyCapabilities.contained` | `TerminologyCapabilities.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `TerminologyCapabilities.copyright` | `TerminologyCapabilities.copyright` | `copyright` | TerminologyCapabilities.copyright | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `TerminologyCapabilities.date` | `TerminologyCapabilities.date` | `date` | TerminologyCapabilities.date | Date last changed | 1..1 | dateTime |  |  |
| `TerminologyCapabilities.description` | `TerminologyCapabilities.description` | `description` | TerminologyCapabilities.description | Natural language description of the terminology capabilities | 0..1 | markdown |  |  |
| `TerminologyCapabilities.expansion` | `TerminologyCapabilities.expansion` | `expansion` | TerminologyCapabilities.expansion | Information about the [ValueSet/$expand](valueset-operation-expand.html) operation | 0..1 | BackboneElement |  |  |
| `TerminologyCapabilities.expansion.extension` | `TerminologyCapabilities.expansion.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TerminologyCapabilities.expansion.hierarchical` | `TerminologyCapabilities.expansion.hierarchical` | `hierarchical` | TerminologyCapabilities.expansion.hierarchical | Whether the server can return nested value sets | 0..1 | boolean |  |  |
| `TerminologyCapabilities.expansion.id` | `TerminologyCapabilities.expansion.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TerminologyCapabilities.expansion.incomplete` | `TerminologyCapabilities.expansion.incomplete` | `incomplete` | TerminologyCapabilities.expansion.incomplete | Allow request for incomplete expansions? | 0..1 | boolean |  |  |
| `TerminologyCapabilities.expansion.modifierExtension` | `TerminologyCapabilities.expansion.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TerminologyCapabilities.expansion.paging` | `TerminologyCapabilities.expansion.paging` | `paging` | TerminologyCapabilities.expansion.paging | Whether the server supports paging on expansion | 0..1 | boolean |  |  |
| `TerminologyCapabilities.expansion.parameter` | `TerminologyCapabilities.expansion.parameter` | `parameter` | TerminologyCapabilities.expansion.parameter | Supported expansion parameter | 0..* | BackboneElement |  |  |
| `TerminologyCapabilities.expansion.parameter.documentation` | `TerminologyCapabilities.expansion.parameter.documentation` | `documentation` | TerminologyCapabilities.expansion.parameter.documentation | Description of support for parameter | 0..1 | string |  |  |
| `TerminologyCapabilities.expansion.parameter.extension` | `TerminologyCapabilities.expansion.parameter.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TerminologyCapabilities.expansion.parameter.id` | `TerminologyCapabilities.expansion.parameter.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TerminologyCapabilities.expansion.parameter.modifierExtension` | `TerminologyCapabilities.expansion.parameter.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TerminologyCapabilities.expansion.parameter.name` | `TerminologyCapabilities.expansion.parameter.name` | `name` | TerminologyCapabilities.expansion.parameter.name | Expansion Parameter name | 1..1 | code |  |  |
| `TerminologyCapabilities.expansion.textFilter` | `TerminologyCapabilities.expansion.textFilter` | `textFilter` | TerminologyCapabilities.expansion.textFilter | Documentation about text searching works | 0..1 | markdown |  |  |
| `TerminologyCapabilities.experimental` | `TerminologyCapabilities.experimental` | `experimental` | TerminologyCapabilities.experimental | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `TerminologyCapabilities.extension` | `TerminologyCapabilities.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TerminologyCapabilities.id` | `TerminologyCapabilities.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `TerminologyCapabilities.implementation` | `TerminologyCapabilities.implementation` | `implementation` | TerminologyCapabilities.implementation | If this describes a specific instance | 0..1 | BackboneElement |  |  |
| `TerminologyCapabilities.implementation.description` | `TerminologyCapabilities.implementation.description` | `description` | TerminologyCapabilities.implementation.description | Describes this specific instance | 1..1 | string |  |  |
| `TerminologyCapabilities.implementation.extension` | `TerminologyCapabilities.implementation.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TerminologyCapabilities.implementation.id` | `TerminologyCapabilities.implementation.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TerminologyCapabilities.implementation.modifierExtension` | `TerminologyCapabilities.implementation.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TerminologyCapabilities.implementation.url` | `TerminologyCapabilities.implementation.url` | `url` | TerminologyCapabilities.implementation.url | Base URL for the implementation | 0..1 | url |  |  |
| `TerminologyCapabilities.implicitRules` | `TerminologyCapabilities.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `TerminologyCapabilities.jurisdiction` | `TerminologyCapabilities.jurisdiction` | `jurisdiction` | TerminologyCapabilities.jurisdiction | Intended jurisdiction for terminology capabilities (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `TerminologyCapabilities.kind` | `TerminologyCapabilities.kind` | `kind` | TerminologyCapabilities.kind | instance \| capability \| requirements | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/capability-statement-kind|4.3.0` |
| `TerminologyCapabilities.language` | `TerminologyCapabilities.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `TerminologyCapabilities.lockedDate` | `TerminologyCapabilities.lockedDate` | `lockedDate` | TerminologyCapabilities.lockedDate | Whether lockedDate is supported | 0..1 | boolean |  |  |
| `TerminologyCapabilities.meta` | `TerminologyCapabilities.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `TerminologyCapabilities.modifierExtension` | `TerminologyCapabilities.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `TerminologyCapabilities.name` | `TerminologyCapabilities.name` | `name` | TerminologyCapabilities.name | Name for this terminology capabilities (computer friendly) | 0..1 | string |  |  |
| `TerminologyCapabilities.publisher` | `TerminologyCapabilities.publisher` | `publisher` | TerminologyCapabilities.publisher | Name of the publisher (organization or individual) | 0..1 | string |  |  |
| `TerminologyCapabilities.purpose` | `TerminologyCapabilities.purpose` | `purpose` | TerminologyCapabilities.purpose | Why this terminology capabilities is defined | 0..1 | markdown |  |  |
| `TerminologyCapabilities.software` | `TerminologyCapabilities.software` | `software` | TerminologyCapabilities.software | Software that is covered by this terminology capability statement | 0..1 | BackboneElement |  |  |
| `TerminologyCapabilities.software.extension` | `TerminologyCapabilities.software.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TerminologyCapabilities.software.id` | `TerminologyCapabilities.software.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TerminologyCapabilities.software.modifierExtension` | `TerminologyCapabilities.software.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TerminologyCapabilities.software.name` | `TerminologyCapabilities.software.name` | `name` | TerminologyCapabilities.software.name | A name the software is known by | 1..1 | string |  |  |
| `TerminologyCapabilities.software.version` | `TerminologyCapabilities.software.version` | `version` | TerminologyCapabilities.software.version | Version covered by this statement | 0..1 | string |  |  |
| `TerminologyCapabilities.status` | `TerminologyCapabilities.status` | `status` | TerminologyCapabilities.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|4.3.0` |
| `TerminologyCapabilities.text` | `TerminologyCapabilities.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `TerminologyCapabilities.title` | `TerminologyCapabilities.title` | `title` | TerminologyCapabilities.title | Name for this terminology capabilities (human friendly) | 0..1 | string |  |  |
| `TerminologyCapabilities.translation` | `TerminologyCapabilities.translation` | `translation` | TerminologyCapabilities.translation | Information about the [ConceptMap/$translate](conceptmap-operation-translate.html) operation | 0..1 | BackboneElement |  |  |
| `TerminologyCapabilities.translation.extension` | `TerminologyCapabilities.translation.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TerminologyCapabilities.translation.id` | `TerminologyCapabilities.translation.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TerminologyCapabilities.translation.modifierExtension` | `TerminologyCapabilities.translation.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TerminologyCapabilities.translation.needsMap` | `TerminologyCapabilities.translation.needsMap` | `needsMap` | TerminologyCapabilities.translation.needsMap | Whether the client must identify the map | 1..1 | boolean |  |  |
| `TerminologyCapabilities.url` | `TerminologyCapabilities.url` | `url` | TerminologyCapabilities.url | Canonical identifier for this terminology capabilities, represented as a URI (globally unique) | 0..1 | uri |  |  |
| `TerminologyCapabilities.useContext` | `TerminologyCapabilities.useContext` | `useContext` | TerminologyCapabilities.useContext | The context that the content is intended to support | 0..* | UsageContext |  |  |
| `TerminologyCapabilities.validateCode` | `TerminologyCapabilities.validateCode` | `validateCode` | TerminologyCapabilities.validateCode | Information about the [ValueSet/$validate-code](valueset-operation-validate-code.html) operation | 0..1 | BackboneElement |  |  |
| `TerminologyCapabilities.validateCode.extension` | `TerminologyCapabilities.validateCode.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TerminologyCapabilities.validateCode.id` | `TerminologyCapabilities.validateCode.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TerminologyCapabilities.validateCode.modifierExtension` | `TerminologyCapabilities.validateCode.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `TerminologyCapabilities.validateCode.translations` | `TerminologyCapabilities.validateCode.translations` | `translations` | TerminologyCapabilities.validateCode.translations | Whether translations are validated | 1..1 | boolean |  |  |
| `TerminologyCapabilities.version` | `TerminologyCapabilities.version` | `version` | TerminologyCapabilities.version | Business version of the terminology capabilities | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [TerminologyCapabilities](/docs/R4/Resources/TerminologyCapabilities.md)<br/> `http://hl7.org/fhir/StructureDefinition/TerminologyCapabilities\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1635`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1636`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TerminologyCapabilities](/docs/R4B/Resources/TerminologyCapabilities.md)<br/> `http://hl7.org/fhir/StructureDefinition/TerminologyCapabilities\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1054`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1283`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TerminologyCapabilities](/docs/R5/Resources/TerminologyCapabilities.md)<br/> `http://hl7.org/fhir/StructureDefinition/TerminologyCapabilities\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition TerminologyCapabilities from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | [R4 TerminologyCapabilities](/docs/R4/Resources/TerminologyCapabilities.md)| Relationship | R4B TerminologyCapabilities| Relationship | [R5 TerminologyCapabilities](/docs/R5/Resources/TerminologyCapabilities.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `TerminologyCapabilities`| _Equivalent_<br/>(34172/34173)| **`TerminologyCapabilities`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(48591)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(48592)| `TerminologyCapabilities`
| | | | | `TerminologyCapabilities.id`| _Equivalent_<br/>(34174/34175)| **`TerminologyCapabilities.id`**| _Equivalent_<br/>(48593/48594)| `TerminologyCapabilities.id`
| | | | | `TerminologyCapabilities.meta`| _Equivalent_<br/>(34176/34177)| **`TerminologyCapabilities.meta`**| _Equivalent_<br/>(48595/48596)| `TerminologyCapabilities.meta`
| | | | | `TerminologyCapabilities.implicitRules`| _Equivalent_<br/>(34178/34179)| **`TerminologyCapabilities.implicitRules`**| _Equivalent_<br/>(48597/48598)| `TerminologyCapabilities.implicitRules`
| | | | | `TerminologyCapabilities.language`| _Equivalent_<br/>(34180/34181)| **`TerminologyCapabilities.language`**| _Equivalent_<br/>(48599/48600)| `TerminologyCapabilities.language`
| | | | | `TerminologyCapabilities.text`| _Equivalent_<br/>(34182/34183)| **`TerminologyCapabilities.text`**| _Equivalent_<br/>(48601/48602)| `TerminologyCapabilities.text`
| | | | | `TerminologyCapabilities.contained`| _Equivalent_<br/>(34184/34185)| **`TerminologyCapabilities.contained`**| _Equivalent_<br/>(48603/48604)| `TerminologyCapabilities.contained`
| | | | | `TerminologyCapabilities.extension`| _Equivalent_<br/>(34186/34187)| **`TerminologyCapabilities.extension`**| _Equivalent_<br/>(48605/48606)| `TerminologyCapabilities.extension`
| | | | | `TerminologyCapabilities.modifierExtension`| _Equivalent_<br/>(34188/34189)| **`TerminologyCapabilities.modifierExtension`**| _Equivalent_<br/>(48607/48608)| `TerminologyCapabilities.modifierExtension`
| | | | | `TerminologyCapabilities.url`| _Equivalent_<br/>(34190/34191)| **`TerminologyCapabilities.url`**| _Equivalent_<br/>(48609/48610)| `TerminologyCapabilities.url`
| | | | | `TerminologyCapabilities.version`| _Equivalent_<br/>(34192/34193)| **`TerminologyCapabilities.version`**| _Equivalent_<br/>(48611/48612)| `TerminologyCapabilities.version`
| | | | | `TerminologyCapabilities.name`| _Equivalent_<br/>(34194/34195)| **`TerminologyCapabilities.name`**| _Equivalent_<br/>(48613/48614)| `TerminologyCapabilities.name`
| | | | | `TerminologyCapabilities.title`| _Equivalent_<br/>(34196/34197)| **`TerminologyCapabilities.title`**| _Equivalent_<br/>(48615/48616)| `TerminologyCapabilities.title`
| | | | | `TerminologyCapabilities.status`| _Equivalent_<br/>(34198/34199)| **`TerminologyCapabilities.status`**| _Equivalent_<br/>(48617/48618)| `TerminologyCapabilities.status`
| | | | | `TerminologyCapabilities.experimental`| _Equivalent_<br/>(34200/34201)| **`TerminologyCapabilities.experimental`**| _Equivalent_<br/>(48619/48620)| `TerminologyCapabilities.experimental`
| | | | | `TerminologyCapabilities.date`| _Equivalent_<br/>(34202/34203)| **`TerminologyCapabilities.date`**| _Equivalent_<br/>(48621/48622)| `TerminologyCapabilities.date`
| | | | | `TerminologyCapabilities.publisher`| _Equivalent_<br/>(34204/34205)| **`TerminologyCapabilities.publisher`**| _Equivalent_<br/>(48623/48624)| `TerminologyCapabilities.publisher`
| | | | | `TerminologyCapabilities.contact`| _Equivalent_<br/>(34206/34207)| **`TerminologyCapabilities.contact`**| _Equivalent_<br/>(48625/48626)| `TerminologyCapabilities.contact`
| | | | | `TerminologyCapabilities.description`| _Equivalent_<br/>(34208/34209)| **`TerminologyCapabilities.description`**| _Equivalent_<br/>(48627/48628)| `TerminologyCapabilities.description`
| | | | | `TerminologyCapabilities.useContext`| _Equivalent_<br/>(34210/34211)| **`TerminologyCapabilities.useContext`**| _Equivalent_<br/>(48629/48630)| `TerminologyCapabilities.useContext`
| | | | | `TerminologyCapabilities.jurisdiction`| _Equivalent_<br/>(34212/34213)| **`TerminologyCapabilities.jurisdiction`**| _Equivalent_<br/>(48631/48632)| `TerminologyCapabilities.jurisdiction`
| | | | | `TerminologyCapabilities.purpose`| _Equivalent_<br/>(34214/34215)| **`TerminologyCapabilities.purpose`**| _Equivalent_<br/>(48633/48634)| `TerminologyCapabilities.purpose`
| | | | | `TerminologyCapabilities.copyright`| _Equivalent_<br/>(34216/34217)| **`TerminologyCapabilities.copyright`**| _Equivalent_<br/>(48635/48636)| `TerminologyCapabilities.copyright`
| | | | | `TerminologyCapabilities.kind`| _Equivalent_<br/>(34218/34219)| **`TerminologyCapabilities.kind`**| _Equivalent_<br/>(48637/48638)| `TerminologyCapabilities.kind`
| | | | | `TerminologyCapabilities.software`| _Equivalent_<br/>(34220/34221)| **`TerminologyCapabilities.software`**| _Equivalent_<br/>(48639/48640)| `TerminologyCapabilities.software`
| | | | | `TerminologyCapabilities.software.id`| _Equivalent_<br/>(34222/34223)| **`TerminologyCapabilities.software.id`**| _Equivalent_<br/>(48641/48642)| `TerminologyCapabilities.software.id`
| | | | | `TerminologyCapabilities.software.extension`| _Equivalent_<br/>(34224/34225)| **`TerminologyCapabilities.software.extension`**| _Equivalent_<br/>(48643/48644)| `TerminologyCapabilities.software.extension`
| | | | | `TerminologyCapabilities.software.modifierExtension`| _Equivalent_<br/>(34226/34227)| **`TerminologyCapabilities.software.modifierExtension`**| _Equivalent_<br/>(48645/48646)| `TerminologyCapabilities.software.modifierExtension`
| | | | | `TerminologyCapabilities.software.name`| _Equivalent_<br/>(34228/34229)| **`TerminologyCapabilities.software.name`**| _Equivalent_<br/>(48647/48648)| `TerminologyCapabilities.software.name`
| | | | | `TerminologyCapabilities.software.version`| _Equivalent_<br/>(34230/34231)| **`TerminologyCapabilities.software.version`**| _Equivalent_<br/>(48649/48650)| `TerminologyCapabilities.software.version`
| | | | | `TerminologyCapabilities.implementation`| _Equivalent_<br/>(34232/34233)| **`TerminologyCapabilities.implementation`**| _Equivalent_<br/>(48651/48652)| `TerminologyCapabilities.implementation`
| | | | | `TerminologyCapabilities.implementation.id`| _Equivalent_<br/>(34234/34235)| **`TerminologyCapabilities.implementation.id`**| _Equivalent_<br/>(48653/48654)| `TerminologyCapabilities.implementation.id`
| | | | | `TerminologyCapabilities.implementation.extension`| _Equivalent_<br/>(34236/34237)| **`TerminologyCapabilities.implementation.extension`**| _Equivalent_<br/>(48655/48656)| `TerminologyCapabilities.implementation.extension`
| | | | | `TerminologyCapabilities.implementation.modifierExtension`| _Equivalent_<br/>(34238/34239)| **`TerminologyCapabilities.implementation.modifierExtension`**| _Equivalent_<br/>(48657/48658)| `TerminologyCapabilities.implementation.modifierExtension`
| | | | | `TerminologyCapabilities.implementation.description`| _Equivalent_<br/>(34240/34241)| **`TerminologyCapabilities.implementation.description`**| _Equivalent_<br/>(48659/48660)| `TerminologyCapabilities.implementation.description`
| | | | | `TerminologyCapabilities.implementation.url`| _Equivalent_<br/>(34242/34243)| **`TerminologyCapabilities.implementation.url`**| _Equivalent_<br/>(48661/48662)| `TerminologyCapabilities.implementation.url`
| | | | | `TerminologyCapabilities.lockedDate`| _Equivalent_<br/>(34244/34245)| **`TerminologyCapabilities.lockedDate`**| _Equivalent_<br/>(48663/48664)| `TerminologyCapabilities.lockedDate`
| | | | | `TerminologyCapabilities.codeSystem`| _Equivalent_<br/>(34246/34247)| **`TerminologyCapabilities.codeSystem`**| _Equivalent_<br/>(48665/48666)| `TerminologyCapabilities.codeSystem`
| | | | | `TerminologyCapabilities.codeSystem.id`| _Equivalent_<br/>(34248/34249)| **`TerminologyCapabilities.codeSystem.id`**| _Equivalent_<br/>(48667/48668)| `TerminologyCapabilities.codeSystem.id`
| | | | | `TerminologyCapabilities.codeSystem.extension`| _Equivalent_<br/>(34250/34251)| **`TerminologyCapabilities.codeSystem.extension`**| _Equivalent_<br/>(48669/48670)| `TerminologyCapabilities.codeSystem.extension`
| | | | | `TerminologyCapabilities.codeSystem.modifierExtension`| _Equivalent_<br/>(34252/34253)| **`TerminologyCapabilities.codeSystem.modifierExtension`**| _Equivalent_<br/>(48671/48672)| `TerminologyCapabilities.codeSystem.modifierExtension`
| | | | | `TerminologyCapabilities.codeSystem.uri`| _Equivalent_<br/>(34254/34255)| **`TerminologyCapabilities.codeSystem.uri`**| _Equivalent_<br/>(48673/48674)| `TerminologyCapabilities.codeSystem.uri`
| | | | | `TerminologyCapabilities.codeSystem.version`| _Equivalent_<br/>(34256/34257)| **`TerminologyCapabilities.codeSystem.version`**| _Equivalent_<br/>(48675/48676)| `TerminologyCapabilities.codeSystem.version`
| | | | | `TerminologyCapabilities.codeSystem.version.id`| _Equivalent_<br/>(34258/34259)| **`TerminologyCapabilities.codeSystem.version.id`**| _Equivalent_<br/>(48677/48678)| `TerminologyCapabilities.codeSystem.version.id`
| | | | | `TerminologyCapabilities.codeSystem.version.extension`| _Equivalent_<br/>(34260/34261)| **`TerminologyCapabilities.codeSystem.version.extension`**| _Equivalent_<br/>(48679/48680)| `TerminologyCapabilities.codeSystem.version.extension`
| | | | | `TerminologyCapabilities.codeSystem.version.modifierExtension`| _Equivalent_<br/>(34262/34263)| **`TerminologyCapabilities.codeSystem.version.modifierExtension`**| _Equivalent_<br/>(48681/48682)| `TerminologyCapabilities.codeSystem.version.modifierExtension`
| | | | | `TerminologyCapabilities.codeSystem.version.code`| _Equivalent_<br/>(34264/34265)| **`TerminologyCapabilities.codeSystem.version.code`**| _Equivalent_<br/>(48683/48684)| `TerminologyCapabilities.codeSystem.version.code`
| | | | | `TerminologyCapabilities.codeSystem.version.isDefault`| _Equivalent_<br/>(34266/34267)| **`TerminologyCapabilities.codeSystem.version.isDefault`**| _Equivalent_<br/>(48685/48686)| `TerminologyCapabilities.codeSystem.version.isDefault`
| | | | | `TerminologyCapabilities.codeSystem.version.compositional`| _Equivalent_<br/>(34268/34269)| **`TerminologyCapabilities.codeSystem.version.compositional`**| _Equivalent_<br/>(48687/48688)| `TerminologyCapabilities.codeSystem.version.compositional`
| | | | | `TerminologyCapabilities.codeSystem.version.language`| _Equivalent_<br/>(34270/34271)| **`TerminologyCapabilities.codeSystem.version.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(48689)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(48690)| `TerminologyCapabilities.codeSystem.version.language`
| | | | | `TerminologyCapabilities.codeSystem.version.filter`| _Equivalent_<br/>(34272/34273)| **`TerminologyCapabilities.codeSystem.version.filter`**| _Equivalent_<br/>(48691/48692)| `TerminologyCapabilities.codeSystem.version.filter`
| | | | | `TerminologyCapabilities.codeSystem.version.filter.id`| _Equivalent_<br/>(34274/34275)| **`TerminologyCapabilities.codeSystem.version.filter.id`**| _Equivalent_<br/>(48693/48694)| `TerminologyCapabilities.codeSystem.version.filter.id`
| | | | | `TerminologyCapabilities.codeSystem.version.filter.extension`| _Equivalent_<br/>(34276/34277)| **`TerminologyCapabilities.codeSystem.version.filter.extension`**| _Equivalent_<br/>(48695/48696)| `TerminologyCapabilities.codeSystem.version.filter.extension`
| | | | | `TerminologyCapabilities.codeSystem.version.filter.modifierExtension`| _Equivalent_<br/>(34278/34279)| **`TerminologyCapabilities.codeSystem.version.filter.modifierExtension`**| _Equivalent_<br/>(48697/48698)| `TerminologyCapabilities.codeSystem.version.filter.modifierExtension`
| | | | | `TerminologyCapabilities.codeSystem.version.filter.code`| _Equivalent_<br/>(34280/34281)| **`TerminologyCapabilities.codeSystem.version.filter.code`**| _Equivalent_<br/>(48699/48700)| `TerminologyCapabilities.codeSystem.version.filter.code`
| | | | | `TerminologyCapabilities.codeSystem.version.filter.op`| _Equivalent_<br/>(34282/34283)| **`TerminologyCapabilities.codeSystem.version.filter.op`**| _Equivalent_<br/>(48701/48702)| `TerminologyCapabilities.codeSystem.version.filter.op`
| | | | | `TerminologyCapabilities.codeSystem.version.property`| _Equivalent_<br/>(34284/34285)| **`TerminologyCapabilities.codeSystem.version.property`**| _Equivalent_<br/>(48703/48704)| `TerminologyCapabilities.codeSystem.version.property`
| | | | | `TerminologyCapabilities.codeSystem.subsumption`| _Equivalent_<br/>(34286/34287)| **`TerminologyCapabilities.codeSystem.subsumption`**| _Equivalent_<br/>(48705/48706)| `TerminologyCapabilities.codeSystem.subsumption`
| | | | | `TerminologyCapabilities.expansion`| _Equivalent_<br/>(34288/34289)| **`TerminologyCapabilities.expansion`**| _Equivalent_<br/>(48707/48708)| `TerminologyCapabilities.expansion`
| | | | | `TerminologyCapabilities.expansion.id`| _Equivalent_<br/>(34290/34291)| **`TerminologyCapabilities.expansion.id`**| _Equivalent_<br/>(48709/48710)| `TerminologyCapabilities.expansion.id`
| | | | | `TerminologyCapabilities.expansion.extension`| _Equivalent_<br/>(34292/34293)| **`TerminologyCapabilities.expansion.extension`**| _Equivalent_<br/>(48711/48712)| `TerminologyCapabilities.expansion.extension`
| | | | | `TerminologyCapabilities.expansion.modifierExtension`| _Equivalent_<br/>(34294/34295)| **`TerminologyCapabilities.expansion.modifierExtension`**| _Equivalent_<br/>(48713/48714)| `TerminologyCapabilities.expansion.modifierExtension`
| | | | | `TerminologyCapabilities.expansion.hierarchical`| _Equivalent_<br/>(34296/34297)| **`TerminologyCapabilities.expansion.hierarchical`**| _Equivalent_<br/>(48715/48716)| `TerminologyCapabilities.expansion.hierarchical`
| | | | | `TerminologyCapabilities.expansion.paging`| _Equivalent_<br/>(34298/34299)| **`TerminologyCapabilities.expansion.paging`**| _Equivalent_<br/>(48717/48718)| `TerminologyCapabilities.expansion.paging`
| | | | | `TerminologyCapabilities.expansion.incomplete`| _Equivalent_<br/>(34300/34301)| **`TerminologyCapabilities.expansion.incomplete`**| _Equivalent_<br/>(48719/48720)| `TerminologyCapabilities.expansion.incomplete`
| | | | | `TerminologyCapabilities.expansion.parameter`| _Equivalent_<br/>(34302/34303)| **`TerminologyCapabilities.expansion.parameter`**| _Equivalent_<br/>(48721/48722)| `TerminologyCapabilities.expansion.parameter`
| | | | | `TerminologyCapabilities.expansion.parameter.id`| _Equivalent_<br/>(34304/34305)| **`TerminologyCapabilities.expansion.parameter.id`**| _Equivalent_<br/>(48723/48724)| `TerminologyCapabilities.expansion.parameter.id`
| | | | | `TerminologyCapabilities.expansion.parameter.extension`| _Equivalent_<br/>(34306/34307)| **`TerminologyCapabilities.expansion.parameter.extension`**| _Equivalent_<br/>(48725/48726)| `TerminologyCapabilities.expansion.parameter.extension`
| | | | | `TerminologyCapabilities.expansion.parameter.modifierExtension`| _Equivalent_<br/>(34308/34309)| **`TerminologyCapabilities.expansion.parameter.modifierExtension`**| _Equivalent_<br/>(48727/48728)| `TerminologyCapabilities.expansion.parameter.modifierExtension`
| | | | | `TerminologyCapabilities.expansion.parameter.name`| _Equivalent_<br/>(34310/34311)| **`TerminologyCapabilities.expansion.parameter.name`**| _Equivalent_<br/>(48729/48730)| `TerminologyCapabilities.expansion.parameter.name`
| | | | | `TerminologyCapabilities.expansion.parameter.documentation`| _Equivalent_<br/>(34312/34313)| **`TerminologyCapabilities.expansion.parameter.documentation`**| _Equivalent_<br/>(48731/48732)| `TerminologyCapabilities.expansion.parameter.documentation`
| | | | | `TerminologyCapabilities.expansion.textFilter`| _Equivalent_<br/>(34314/34315)| **`TerminologyCapabilities.expansion.textFilter`**| _Equivalent_<br/>(48733/48734)| `TerminologyCapabilities.expansion.textFilter`
| | | | | `TerminologyCapabilities.codeSearch`| _Equivalent_<br/>(34316/34317)| **`TerminologyCapabilities.codeSearch`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(48735)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(48736)| `TerminologyCapabilities.codeSearch`
| | | | | `TerminologyCapabilities.validateCode`| _Equivalent_<br/>(34318/34319)| **`TerminologyCapabilities.validateCode`**| _Equivalent_<br/>(48737/48738)| `TerminologyCapabilities.validateCode`
| | | | | `TerminologyCapabilities.validateCode.id`| _Equivalent_<br/>(34320/34321)| **`TerminologyCapabilities.validateCode.id`**| _Equivalent_<br/>(48739/48740)| `TerminologyCapabilities.validateCode.id`
| | | | | `TerminologyCapabilities.validateCode.extension`| _Equivalent_<br/>(34322/34323)| **`TerminologyCapabilities.validateCode.extension`**| _Equivalent_<br/>(48741/48742)| `TerminologyCapabilities.validateCode.extension`
| | | | | `TerminologyCapabilities.validateCode.modifierExtension`| _Equivalent_<br/>(34324/34325)| **`TerminologyCapabilities.validateCode.modifierExtension`**| _Equivalent_<br/>(48743/48744)| `TerminologyCapabilities.validateCode.modifierExtension`
| | | | | `TerminologyCapabilities.validateCode.translations`| _Equivalent_<br/>(34326/34327)| **`TerminologyCapabilities.validateCode.translations`**| _Equivalent_<br/>(48745/48746)| `TerminologyCapabilities.validateCode.translations`
| | | | | `TerminologyCapabilities.translation`| _Equivalent_<br/>(34328/34329)| **`TerminologyCapabilities.translation`**| _Equivalent_<br/>(48747/48748)| `TerminologyCapabilities.translation`
| | | | | `TerminologyCapabilities.translation.id`| _Equivalent_<br/>(34330/34331)| **`TerminologyCapabilities.translation.id`**| _Equivalent_<br/>(48749/48750)| `TerminologyCapabilities.translation.id`
| | | | | `TerminologyCapabilities.translation.extension`| _Equivalent_<br/>(34332/34333)| **`TerminologyCapabilities.translation.extension`**| _Equivalent_<br/>(48751/48752)| `TerminologyCapabilities.translation.extension`
| | | | | `TerminologyCapabilities.translation.modifierExtension`| _Equivalent_<br/>(34334/34335)| **`TerminologyCapabilities.translation.modifierExtension`**| _Equivalent_<br/>(48753/48754)| `TerminologyCapabilities.translation.modifierExtension`
| | | | | `TerminologyCapabilities.translation.needsMap`| _Equivalent_<br/>(34336/34337)| **`TerminologyCapabilities.translation.needsMap`**| _Equivalent_<br/>(48755/48756)| `TerminologyCapabilities.translation.needsMap`
| | | | | `TerminologyCapabilities.closure`| _Equivalent_<br/>(34338/34339)| **`TerminologyCapabilities.closure`**| _Equivalent_<br/>(48757/48758)| `TerminologyCapabilities.closure`
| | | | | `TerminologyCapabilities.closure.id`| _Equivalent_<br/>(34340/34341)| **`TerminologyCapabilities.closure.id`**| _Equivalent_<br/>(48759/48760)| `TerminologyCapabilities.closure.id`
| | | | | `TerminologyCapabilities.closure.extension`| _Equivalent_<br/>(34342/34343)| **`TerminologyCapabilities.closure.extension`**| _Equivalent_<br/>(48761/48762)| `TerminologyCapabilities.closure.extension`
| | | | | `TerminologyCapabilities.closure.modifierExtension`| _Equivalent_<br/>(34344/34345)| **`TerminologyCapabilities.closure.modifierExtension`**| _Equivalent_<br/>(48763/48764)| `TerminologyCapabilities.closure.modifierExtension`
| | | | | `TerminologyCapabilities.closure.translation`| _Equivalent_<br/>(34346/34347)| **`TerminologyCapabilities.closure.translation`**| _Equivalent_<br/>(48765/48766)| `TerminologyCapabilities.closure.translation`
| | | | | *88 of 88 elements used* | | *88 of 88 elements used* | | *88 of 92 elements used* 

