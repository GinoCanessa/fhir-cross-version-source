Comparison of 
Generated at Tuesday, April 1, 2025 1:39:14 PM

### ExpansionProfile

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | ExpansionProfile |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ExpansionProfile` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for ExpansionProfile Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `521` |
| Database Snapshot Count | `66` |
| Database Differential Count | `37` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ExpansionProfile` | `ExpansionProfile` | `ExpansionProfile` | ExpansionProfile | Defines behaviour and contraints on the ValueSet Expansion operation | 0..* | ExpansionProfile |  |  |
| `ExpansionProfile.activeOnly` | `ExpansionProfile.activeOnly` | `activeOnly` |  | Include or exclude inactive concepts in the expansion | 0..1 | boolean |  |  |
| `ExpansionProfile.contact` | `ExpansionProfile.contact` | `contact` |  | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `ExpansionProfile.contained` | `ExpansionProfile.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ExpansionProfile.date` | `ExpansionProfile.date` | `date` |  | Date this was last changed | 0..1 | dateTime |  |  |
| `ExpansionProfile.description` | `ExpansionProfile.description` | `description` |  | Natural language description of the expansion profile | 0..1 | markdown |  |  |
| `ExpansionProfile.designation` | `ExpansionProfile.designation` | `designation` |  | When the expansion profile imposes designation contraints | 0..1 | BackboneElement |  |  |
| `ExpansionProfile.designation.exclude` | `ExpansionProfile.designation.exclude` | `exclude` |  | Designations to be excluded | 0..1 | BackboneElement |  |  |
| `ExpansionProfile.designation.exclude.designation` | `ExpansionProfile.designation.exclude.designation` | `designation` |  | The designation to be excluded | 0..* | BackboneElement |  |  |
| `ExpansionProfile.designation.exclude.designation.extension` | `ExpansionProfile.designation.exclude.designation.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ExpansionProfile.designation.exclude.designation.id` | `ExpansionProfile.designation.exclude.designation.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ExpansionProfile.designation.exclude.designation.language` | `ExpansionProfile.designation.exclude.designation.language` | `language` |  | Human language of the designation to be excluded | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `ExpansionProfile.designation.exclude.designation.modifierExtension` | `ExpansionProfile.designation.exclude.designation.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ExpansionProfile.designation.exclude.designation.use` | `ExpansionProfile.designation.exclude.designation.use` | `use` |  | What kind of Designation to exclude | 0..1 | Coding | `Required` | `http://hl7.org/fhir/ValueSet/designation-use` |
| `ExpansionProfile.designation.exclude.extension` | `ExpansionProfile.designation.exclude.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ExpansionProfile.designation.exclude.id` | `ExpansionProfile.designation.exclude.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ExpansionProfile.designation.exclude.modifierExtension` | `ExpansionProfile.designation.exclude.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ExpansionProfile.designation.extension` | `ExpansionProfile.designation.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ExpansionProfile.designation.id` | `ExpansionProfile.designation.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ExpansionProfile.designation.include` | `ExpansionProfile.designation.include` | `include` |  | Designations to be included | 0..1 | BackboneElement |  |  |
| `ExpansionProfile.designation.include.designation` | `ExpansionProfile.designation.include.designation` | `designation` |  | The designation to be included | 0..* | BackboneElement |  |  |
| `ExpansionProfile.designation.include.designation.extension` | `ExpansionProfile.designation.include.designation.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ExpansionProfile.designation.include.designation.id` | `ExpansionProfile.designation.include.designation.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ExpansionProfile.designation.include.designation.language` | `ExpansionProfile.designation.include.designation.language` | `language` |  | Human language of the designation to be included | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `ExpansionProfile.designation.include.designation.modifierExtension` | `ExpansionProfile.designation.include.designation.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ExpansionProfile.designation.include.designation.use` | `ExpansionProfile.designation.include.designation.use` | `use` |  | What kind of Designation to include | 0..1 | Coding | `Required` | `http://hl7.org/fhir/ValueSet/designation-use` |
| `ExpansionProfile.designation.include.extension` | `ExpansionProfile.designation.include.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ExpansionProfile.designation.include.id` | `ExpansionProfile.designation.include.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ExpansionProfile.designation.include.modifierExtension` | `ExpansionProfile.designation.include.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ExpansionProfile.designation.modifierExtension` | `ExpansionProfile.designation.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ExpansionProfile.displayLanguage` | `ExpansionProfile.displayLanguage` | `displayLanguage` |  | Specify the language for the display element of codes in the value set expansion | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `ExpansionProfile.excludeNested` | `ExpansionProfile.excludeNested` | `excludeNested` |  | Nested codes in the expansion or not | 0..1 | boolean |  |  |
| `ExpansionProfile.excludeNotForUI` | `ExpansionProfile.excludeNotForUI` | `excludeNotForUI` |  | Include or exclude codes which cannot be rendered in user interfaces in the value set expansion | 0..1 | boolean |  |  |
| `ExpansionProfile.excludePostCoordinated` | `ExpansionProfile.excludePostCoordinated` | `excludePostCoordinated` |  | Include or exclude codes which are post coordinated expressions in the value set expansion | 0..1 | boolean |  |  |
| `ExpansionProfile.excludedSystem` | `ExpansionProfile.excludedSystem` | `excludedSystem` |  | Systems/Versions to be exclude | 0..1 | BackboneElement |  |  |
| `ExpansionProfile.excludedSystem.extension` | `ExpansionProfile.excludedSystem.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ExpansionProfile.excludedSystem.id` | `ExpansionProfile.excludedSystem.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ExpansionProfile.excludedSystem.modifierExtension` | `ExpansionProfile.excludedSystem.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ExpansionProfile.excludedSystem.system` | `ExpansionProfile.excludedSystem.system` | `system` |  | The specific code system to be excluded | 1..1 | uri |  |  |
| `ExpansionProfile.excludedSystem.version` | `ExpansionProfile.excludedSystem.version` | `version` |  | Specific version of the code system referred to | 0..1 | string |  |  |
| `ExpansionProfile.experimental` | `ExpansionProfile.experimental` | `experimental` |  | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `ExpansionProfile.extension` | `ExpansionProfile.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ExpansionProfile.fixedVersion` | `ExpansionProfile.fixedVersion` | `fixedVersion` |  | Fix use of a code system to a particular version | 0..* | BackboneElement |  |  |
| `ExpansionProfile.fixedVersion.extension` | `ExpansionProfile.fixedVersion.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ExpansionProfile.fixedVersion.id` | `ExpansionProfile.fixedVersion.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ExpansionProfile.fixedVersion.mode` | `ExpansionProfile.fixedVersion.mode` | `mode` |  | default \| check \| override | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/system-version-processing-mode` |
| `ExpansionProfile.fixedVersion.modifierExtension` | `ExpansionProfile.fixedVersion.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ExpansionProfile.fixedVersion.system` | `ExpansionProfile.fixedVersion.system` | `system` |  | System to have its version fixed | 1..1 | uri |  |  |
| `ExpansionProfile.fixedVersion.version` | `ExpansionProfile.fixedVersion.version` | `version` |  | Specific version of the code system referred to | 1..1 | string |  |  |
| `ExpansionProfile.id` | `ExpansionProfile.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ExpansionProfile.identifier` | `ExpansionProfile.identifier` | `identifier` |  | Additional identifier for the expansion profile | 0..1 | Identifier |  |  |
| `ExpansionProfile.implicitRules` | `ExpansionProfile.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ExpansionProfile.includeDefinition` | `ExpansionProfile.includeDefinition` | `includeDefinition` |  | Include or exclude the value set definition in the expansion | 0..1 | boolean |  |  |
| `ExpansionProfile.includeDesignations` | `ExpansionProfile.includeDesignations` | `includeDesignations` |  | Whether the expansion should include concept designations | 0..1 | boolean |  |  |
| `ExpansionProfile.jurisdiction` | `ExpansionProfile.jurisdiction` | `jurisdiction` |  | Intended jurisdiction for expansion profile (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `ExpansionProfile.language` | `ExpansionProfile.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `ExpansionProfile.limitedExpansion` | `ExpansionProfile.limitedExpansion` | `limitedExpansion` |  | Controls behaviour of the value set expand operation when value sets are too large to be completely expanded | 0..1 | boolean |  |  |
| `ExpansionProfile.meta` | `ExpansionProfile.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ExpansionProfile.modifierExtension` | `ExpansionProfile.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ExpansionProfile.name` | `ExpansionProfile.name` | `name` |  | Name for this expansion profile (computer friendly) | 0..1 | string |  |  |
| `ExpansionProfile.publisher` | `ExpansionProfile.publisher` | `publisher` |  | Name of the publisher (organization or individual) | 0..1 | string |  |  |
| `ExpansionProfile.status` | `ExpansionProfile.status` | `status` |  | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status` |
| `ExpansionProfile.text` | `ExpansionProfile.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `ExpansionProfile.url` | `ExpansionProfile.url` | `url` |  | Logical URI to reference this expansion profile (globally unique) | 0..1 | uri |  |  |
| `ExpansionProfile.useContext` | `ExpansionProfile.useContext` | `useContext` |  | Context the content is intended to support | 0..* | UsageContext |  |  |
| `ExpansionProfile.version` | `ExpansionProfile.version` | `version` |  | Business version of the expansion profile | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [ExpansionProfile](/docs/R3/Resources/ExpansionProfile.md)<br/> `http://hl7.org/fhir/StructureDefinition/ExpansionProfile\|3.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `459`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `688`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Parameters](/docs/R4/Resources/Parameters.md)<br/> `http://hl7.org/fhir/StructureDefinition/Parameters\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1569`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1570`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Parameters](/docs/R4B/Resources/Parameters.md)<br/> `http://hl7.org/fhir/StructureDefinition/Parameters\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1060`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1289`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Parameters](/docs/R5/Resources/Parameters.md)<br/> `http://hl7.org/fhir/StructureDefinition/Parameters\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ExpansionProfile from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | R3 ExpansionProfile| Relationship | [R4 Parameters](/docs/R4/Resources/Parameters.md)| Relationship | [R4B Parameters](/docs/R4B/Resources/Parameters.md)| Relationship | [R5 Parameters](/docs/R5/Resources/Parameters.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | **`ExpansionProfile`**| | | | | | | 
| | | **`ExpansionProfile.id`**| | | | | | | 
| | | **`ExpansionProfile.meta`**| | | | | | | 
| | | **`ExpansionProfile.implicitRules`**| | | | | | | 
| | | **`ExpansionProfile.language`**| | | | | | | 
| | | **`ExpansionProfile.text`**| | | | | | | 
| | | **`ExpansionProfile.contained`**| | | | | | | 
| | | **`ExpansionProfile.extension`**| | | | | | | 
| | | **`ExpansionProfile.modifierExtension`**| | | | | | | 
| | | **`ExpansionProfile.url`**| | | | | | | 
| | | **`ExpansionProfile.identifier`**| | | | | | | 
| | | **`ExpansionProfile.version`**| | | | | | | 
| | | **`ExpansionProfile.name`**| | | | | | | 
| | | **`ExpansionProfile.status`**| | | | | | | 
| | | **`ExpansionProfile.experimental`**| | | | | | | 
| | | **`ExpansionProfile.date`**| | | | | | | 
| | | **`ExpansionProfile.publisher`**| | | | | | | 
| | | **`ExpansionProfile.contact`**| | | | | | | 
| | | **`ExpansionProfile.description`**| | | | | | | 
| | | **`ExpansionProfile.useContext`**| | | | | | | 
| | | **`ExpansionProfile.jurisdiction`**| | | | | | | 
| | | **`ExpansionProfile.fixedVersion`**| | | | | | | 
| | | **`ExpansionProfile.fixedVersion.id`**| | | | | | | 
| | | **`ExpansionProfile.fixedVersion.extension`**| | | | | | | 
| | | **`ExpansionProfile.fixedVersion.modifierExtension`**| | | | | | | 
| | | **`ExpansionProfile.fixedVersion.system`**| | | | | | | 
| | | **`ExpansionProfile.fixedVersion.version`**| | | | | | | 
| | | **`ExpansionProfile.fixedVersion.mode`**| | | | | | | 
| | | **`ExpansionProfile.excludedSystem`**| | | | | | | 
| | | **`ExpansionProfile.excludedSystem.id`**| | | | | | | 
| | | **`ExpansionProfile.excludedSystem.extension`**| | | | | | | 
| | | **`ExpansionProfile.excludedSystem.modifierExtension`**| | | | | | | 
| | | **`ExpansionProfile.excludedSystem.system`**| | | | | | | 
| | | **`ExpansionProfile.excludedSystem.version`**| | | | | | | 
| | | **`ExpansionProfile.includeDesignations`**| | | | | | | 
| | | **`ExpansionProfile.designation`**| | | | | | | 
| | | **`ExpansionProfile.designation.id`**| | | | | | | 
| | | **`ExpansionProfile.designation.extension`**| | | | | | | 
| | | **`ExpansionProfile.designation.modifierExtension`**| | | | | | | 
| | | **`ExpansionProfile.designation.include`**| | | | | | | 
| | | **`ExpansionProfile.designation.include.id`**| | | | | | | 
| | | **`ExpansionProfile.designation.include.extension`**| | | | | | | 
| | | **`ExpansionProfile.designation.include.modifierExtension`**| | | | | | | 
| | | **`ExpansionProfile.designation.include.designation`**| | | | | | | 
| | | **`ExpansionProfile.designation.include.designation.id`**| | | | | | | 
| | | **`ExpansionProfile.designation.include.designation.extension`**| | | | | | | 
| | | **`ExpansionProfile.designation.include.designation.modifierExtension`**| | | | | | | 
| | | **`ExpansionProfile.designation.include.designation.language`**| | | | | | | 
| | | **`ExpansionProfile.designation.include.designation.use`**| | | | | | | 
| | | **`ExpansionProfile.designation.exclude`**| | | | | | | 
| | | **`ExpansionProfile.designation.exclude.id`**| | | | | | | 
| | | **`ExpansionProfile.designation.exclude.extension`**| | | | | | | 
| | | **`ExpansionProfile.designation.exclude.modifierExtension`**| | | | | | | 
| | | **`ExpansionProfile.designation.exclude.designation`**| | | | | | | 
| | | **`ExpansionProfile.designation.exclude.designation.id`**| | | | | | | 
| | | **`ExpansionProfile.designation.exclude.designation.extension`**| | | | | | | 
| | | **`ExpansionProfile.designation.exclude.designation.modifierExtension`**| | | | | | | 
| | | **`ExpansionProfile.designation.exclude.designation.language`**| | | | | | | 
| | | **`ExpansionProfile.designation.exclude.designation.use`**| | | | | | | 
| | | **`ExpansionProfile.includeDefinition`**| | | | | | | 
| | | **`ExpansionProfile.activeOnly`**| | | | | | | 
| | | **`ExpansionProfile.excludeNested`**| | | | | | | 
| | | **`ExpansionProfile.excludeNotForUI`**| | | | | | | 
| | | **`ExpansionProfile.excludePostCoordinated`**| | | | | | | 
| | | **`ExpansionProfile.displayLanguage`**| | | | | | | 
| | | **`ExpansionProfile.limitedExpansion`**| | | | | | | 
| | | *66 of 66 elements used* | | *0 of 13 elements used* | | *0 of 13 elements used* | | *0 of 13 elements used* 

