Comparison of 
Generated at Thursday, April 3, 2025 8:18:26 AM

### StructureMap

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | StructureMap |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/StructureMap` |
| Version | 4.3.0 |
| Description | A Map of relationships between 2 structures that can be used to transform data. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1766` |
| Database Snapshot Count | `93` |
| Database Differential Count | `61` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `StructureMap` | `StructureMap` | `StructureMap` | StructureMap | A Map of relationships between 2 structures that can be used to transform data | 0..* | StructureMap |  |  |
| `StructureMap.contact` | `StructureMap.contact` | `contact` | StructureMap.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `StructureMap.contained` | `StructureMap.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `StructureMap.copyright` | `StructureMap.copyright` | `copyright` | StructureMap.copyright | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `StructureMap.date` | `StructureMap.date` | `date` | StructureMap.date | Date last changed | 0..1 | dateTime |  |  |
| `StructureMap.description` | `StructureMap.description` | `description` | StructureMap.description | Natural language description of the structure map | 0..1 | markdown |  |  |
| `StructureMap.experimental` | `StructureMap.experimental` | `experimental` | StructureMap.experimental | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `StructureMap.extension` | `StructureMap.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `StructureMap.group` | `StructureMap.group` | `group` | StructureMap.group | Named sections for reader convenience | 1..* | BackboneElement |  |  |
| `StructureMap.group.documentation` | `StructureMap.group.documentation` | `documentation` | StructureMap.group.documentation | Additional description/explanation for group | 0..1 | string |  |  |
| `StructureMap.group.extends` | `StructureMap.group.extends` | `extends` | StructureMap.group.extends | Another group that this group adds rules to | 0..1 | id |  |  |
| `StructureMap.group.extension` | `StructureMap.group.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `StructureMap.group.id` | `StructureMap.group.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `StructureMap.group.input` | `StructureMap.group.input` | `input` | StructureMap.group.input | Named instance provided when invoking the map | 1..* | BackboneElement |  |  |
| `StructureMap.group.input.documentation` | `StructureMap.group.input.documentation` | `documentation` | StructureMap.group.input.documentation | Documentation for this instance of data | 0..1 | string |  |  |
| `StructureMap.group.input.extension` | `StructureMap.group.input.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `StructureMap.group.input.id` | `StructureMap.group.input.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `StructureMap.group.input.mode` | `StructureMap.group.input.mode` | `mode` | StructureMap.group.input.mode | source \| target | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/map-input-mode|4.3.0` |
| `StructureMap.group.input.modifierExtension` | `StructureMap.group.input.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `StructureMap.group.input.name` | `StructureMap.group.input.name` | `name` | StructureMap.group.input.name | Name for this instance of data | 1..1 | id |  |  |
| `StructureMap.group.input.type` | `StructureMap.group.input.type` | `type` | StructureMap.group.input.type | Type for this instance of data | 0..1 | string |  |  |
| `StructureMap.group.modifierExtension` | `StructureMap.group.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `StructureMap.group.name` | `StructureMap.group.name` | `name` | StructureMap.group.name | Human-readable label | 1..1 | id |  |  |
| `StructureMap.group.rule` | `StructureMap.group.rule` | `rule` | StructureMap.group.rule | Transform Rule from source to target | 1..* | BackboneElement |  |  |
| `StructureMap.group.rule.dependent` | `StructureMap.group.rule.dependent` | `dependent` | StructureMap.group.rule.dependent | Which other rules to apply in the context of this rule | 0..* | BackboneElement |  |  |
| `StructureMap.group.rule.dependent.extension` | `StructureMap.group.rule.dependent.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `StructureMap.group.rule.dependent.id` | `StructureMap.group.rule.dependent.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `StructureMap.group.rule.dependent.modifierExtension` | `StructureMap.group.rule.dependent.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `StructureMap.group.rule.dependent.name` | `StructureMap.group.rule.dependent.name` | `name` | StructureMap.group.rule.dependent.name | Name of a rule or group to apply | 1..1 | id |  |  |
| `StructureMap.group.rule.dependent.variable` | `StructureMap.group.rule.dependent.variable` | `variable` | StructureMap.group.rule.dependent.variable | Variable to pass to the rule or group | 1..* | string |  |  |
| `StructureMap.group.rule.documentation` | `StructureMap.group.rule.documentation` | `documentation` | StructureMap.group.rule.documentation | Documentation for this instance of data | 0..1 | string |  |  |
| `StructureMap.group.rule.extension` | `StructureMap.group.rule.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `StructureMap.group.rule.id` | `StructureMap.group.rule.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `StructureMap.group.rule.modifierExtension` | `StructureMap.group.rule.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `StructureMap.group.rule.name` | `StructureMap.group.rule.name` | `name` | StructureMap.group.rule.name | Name of the rule for internal references | 1..1 | id |  |  |
| `StructureMap.group.rule.rule` | `StructureMap.group.rule.rule` | `rule` | StructureMap.group.rule.rule | Rules contained in this rule | 0..* | StructureMap.group.rule |  |  |
| `StructureMap.group.rule.source` | `StructureMap.group.rule.source` | `source` | StructureMap.group.rule.source | Source inputs to the mapping | 1..* | BackboneElement |  |  |
| `StructureMap.group.rule.source.check` | `StructureMap.group.rule.source.check` | `check` | StructureMap.group.rule.source.check | FHIRPath expression  - must be true or the mapping engine throws an error instead of completing | 0..1 | string |  |  |
| `StructureMap.group.rule.source.condition` | `StructureMap.group.rule.source.condition` | `condition` | StructureMap.group.rule.source.condition | FHIRPath expression  - must be true or the rule does not apply | 0..1 | string |  |  |
| `StructureMap.group.rule.source.context` | `StructureMap.group.rule.source.context` | `context` | StructureMap.group.rule.source.context | Type or variable this rule applies to | 1..1 | id |  |  |
| `StructureMap.group.rule.source.defaultValue[x]` | `StructureMap.group.rule.source.defaultValue[x]` | `defaultValue[x]` | StructureMap.group.rule.source.defaultValue[x] | Default value if no value exists | 0..1 | Address, Age, Annotation, Attachment, base64Binary, boolean, canonical, code, CodeableConcept, Coding, ContactDetail, ContactPoint, Contributor, Count, DataRequirement, date, dateTime, decimal, Distance, Dosage, Duration, Expression, HumanName, id, Identifier, instant, integer, markdown, Meta, Money, oid, ParameterDefinition, Period, positiveInt, Quantity, Range, Ratio, Reference, RelatedArtifact, SampledData, Signature, string, time, Timing, TriggerDefinition, unsignedInt, uri, url, UsageContext, uuid |  |  |
| `StructureMap.group.rule.source.element` | `StructureMap.group.rule.source.element` | `element` | StructureMap.group.rule.source.element | Optional field for this source | 0..1 | string |  |  |
| `StructureMap.group.rule.source.extension` | `StructureMap.group.rule.source.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `StructureMap.group.rule.source.id` | `StructureMap.group.rule.source.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `StructureMap.group.rule.source.listMode` | `StructureMap.group.rule.source.listMode` | `listMode` | StructureMap.group.rule.source.listMode | first \| not_first \| last \| not_last \| only_one | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/map-source-list-mode|4.3.0` |
| `StructureMap.group.rule.source.logMessage` | `StructureMap.group.rule.source.logMessage` | `logMessage` | StructureMap.group.rule.source.logMessage | Message to put in log if source exists (FHIRPath) | 0..1 | string |  |  |
| `StructureMap.group.rule.source.max` | `StructureMap.group.rule.source.max` | `max` | StructureMap.group.rule.source.max | Specified maximum cardinality (number or *) | 0..1 | string |  |  |
| `StructureMap.group.rule.source.min` | `StructureMap.group.rule.source.min` | `min` | StructureMap.group.rule.source.min | Specified minimum cardinality | 0..1 | integer |  |  |
| `StructureMap.group.rule.source.modifierExtension` | `StructureMap.group.rule.source.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `StructureMap.group.rule.source.type` | `StructureMap.group.rule.source.type` | `type` | StructureMap.group.rule.source.type | Rule only applies if source has this type | 0..1 | string |  |  |
| `StructureMap.group.rule.source.variable` | `StructureMap.group.rule.source.variable` | `variable` | StructureMap.group.rule.source.variable | Named context for field, if a field is specified | 0..1 | id |  |  |
| `StructureMap.group.rule.target` | `StructureMap.group.rule.target` | `target` | StructureMap.group.rule.target | Content to create because of this mapping rule | 0..* | BackboneElement |  |  |
| `StructureMap.group.rule.target.context` | `StructureMap.group.rule.target.context` | `context` | StructureMap.group.rule.target.context | Type or variable this rule applies to | 0..1 | id |  |  |
| `StructureMap.group.rule.target.contextType` | `StructureMap.group.rule.target.contextType` | `contextType` | StructureMap.group.rule.target.contextType | type \| variable | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/map-context-type|4.3.0` |
| `StructureMap.group.rule.target.element` | `StructureMap.group.rule.target.element` | `element` | StructureMap.group.rule.target.element | Field to create in the context | 0..1 | string |  |  |
| `StructureMap.group.rule.target.extension` | `StructureMap.group.rule.target.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `StructureMap.group.rule.target.id` | `StructureMap.group.rule.target.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `StructureMap.group.rule.target.listMode` | `StructureMap.group.rule.target.listMode` | `listMode` | StructureMap.group.rule.target.listMode | first \| share \| last \| collate | 0..* | code | `Required` | `http://hl7.org/fhir/ValueSet/map-target-list-mode|4.3.0` |
| `StructureMap.group.rule.target.listRuleId` | `StructureMap.group.rule.target.listRuleId` | `listRuleId` | StructureMap.group.rule.target.listRuleId | Internal rule reference for shared list items | 0..1 | id |  |  |
| `StructureMap.group.rule.target.modifierExtension` | `StructureMap.group.rule.target.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `StructureMap.group.rule.target.parameter` | `StructureMap.group.rule.target.parameter` | `parameter` | StructureMap.group.rule.target.parameter | Parameters to the transform | 0..* | BackboneElement |  |  |
| `StructureMap.group.rule.target.parameter.extension` | `StructureMap.group.rule.target.parameter.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `StructureMap.group.rule.target.parameter.id` | `StructureMap.group.rule.target.parameter.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `StructureMap.group.rule.target.parameter.modifierExtension` | `StructureMap.group.rule.target.parameter.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `StructureMap.group.rule.target.parameter.value[x]` | `StructureMap.group.rule.target.parameter.value[x]` | `value[x]` | StructureMap.group.rule.target.parameter.value[x] | Parameter value - variable or literal | 1..1 | boolean, decimal, id, integer, string |  |  |
| `StructureMap.group.rule.target.transform` | `StructureMap.group.rule.target.transform` | `transform` | StructureMap.group.rule.target.transform | create \| copy + | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/map-transform|4.3.0` |
| `StructureMap.group.rule.target.variable` | `StructureMap.group.rule.target.variable` | `variable` | StructureMap.group.rule.target.variable | Named context for field, if desired, and a field is specified | 0..1 | id |  |  |
| `StructureMap.group.typeMode` | `StructureMap.group.typeMode` | `typeMode` | StructureMap.group.typeMode | none \| types \| type-and-types | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/map-group-type-mode|4.3.0` |
| `StructureMap.id` | `StructureMap.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `StructureMap.identifier` | `StructureMap.identifier` | `identifier` | StructureMap.identifier | Additional identifier for the structure map | 0..* | Identifier |  |  |
| `StructureMap.implicitRules` | `StructureMap.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `StructureMap.import` | `StructureMap.import` | `import` | StructureMap.import | Other maps used by this map (canonical URLs) | 0..* | canonical(http://hl7.org/fhir/StructureDefinition/StructureMap) |  |  |
| `StructureMap.jurisdiction` | `StructureMap.jurisdiction` | `jurisdiction` | StructureMap.jurisdiction | Intended jurisdiction for structure map (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `StructureMap.language` | `StructureMap.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `StructureMap.meta` | `StructureMap.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `StructureMap.modifierExtension` | `StructureMap.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `StructureMap.name` | `StructureMap.name` | `name` | StructureMap.name | Name for this structure map (computer friendly) | 1..1 | string |  |  |
| `StructureMap.publisher` | `StructureMap.publisher` | `publisher` | StructureMap.publisher | Name of the publisher (organization or individual) | 0..1 | string |  |  |
| `StructureMap.purpose` | `StructureMap.purpose` | `purpose` | StructureMap.purpose | Why this structure map is defined | 0..1 | markdown |  |  |
| `StructureMap.status` | `StructureMap.status` | `status` | StructureMap.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|4.3.0` |
| `StructureMap.structure` | `StructureMap.structure` | `structure` | StructureMap.structure | Structure Definition used by this map | 0..* | BackboneElement |  |  |
| `StructureMap.structure.alias` | `StructureMap.structure.alias` | `alias` | StructureMap.structure.alias | Name for type in this map | 0..1 | string |  |  |
| `StructureMap.structure.documentation` | `StructureMap.structure.documentation` | `documentation` | StructureMap.structure.documentation | Documentation on use of structure | 0..1 | string |  |  |
| `StructureMap.structure.extension` | `StructureMap.structure.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `StructureMap.structure.id` | `StructureMap.structure.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `StructureMap.structure.mode` | `StructureMap.structure.mode` | `mode` | StructureMap.structure.mode | source \| queried \| target \| produced | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/map-model-mode|4.3.0` |
| `StructureMap.structure.modifierExtension` | `StructureMap.structure.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `StructureMap.structure.url` | `StructureMap.structure.url` | `url` | StructureMap.structure.url | Canonical reference to structure definition | 1..1 | canonical(http://hl7.org/fhir/StructureDefinition/StructureDefinition) |  |  |
| `StructureMap.text` | `StructureMap.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `StructureMap.title` | `StructureMap.title` | `title` | StructureMap.title | Name for this structure map (human friendly) | 0..1 | string |  |  |
| `StructureMap.url` | `StructureMap.url` | `url` | StructureMap.url | Canonical identifier for this structure map, represented as a URI (globally unique) | 1..1 | uri |  |  |
| `StructureMap.useContext` | `StructureMap.useContext` | `useContext` | StructureMap.useContext | The context that the content is intended to support | 0..* | UsageContext |  |  |
| `StructureMap.version` | `StructureMap.version` | `version` | StructureMap.version | Business version of the structure map | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [StructureMap](/docs/R3/Resources/StructureMap.md)<br/> `http://hl7.org/fhir/StructureDefinition/StructureMap\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `519`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `713`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [StructureMap](/docs/R4/Resources/StructureMap.md)<br/> `http://hl7.org/fhir/StructureDefinition/StructureMap\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1623`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1624`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [StructureMap](/docs/R4B/Resources/StructureMap.md)<br/> `http://hl7.org/fhir/StructureDefinition/StructureMap\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1045`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1274`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [StructureMap](/docs/R5/Resources/StructureMap.md)<br/> `http://hl7.org/fhir/StructureDefinition/StructureMap\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition StructureMap from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | [R3 StructureMap](/docs/R3/Resources/StructureMap.md)| Relationship | [R4 StructureMap](/docs/R4/Resources/StructureMap.md)| Relationship | R4B StructureMap| Relationship | [R5 StructureMap](/docs/R5/Resources/StructureMap.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `StructureMap`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18664)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18665)| `StructureMap`| _Equivalent_<br/>(33543/33544)| **`StructureMap`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47708)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47709)| `StructureMap`
| | | `StructureMap.id`| _Equivalent_<br/>(18666/18667)| `StructureMap.id`| _Equivalent_<br/>(33545/33546)| **`StructureMap.id`**| _Equivalent_<br/>(47710/47711)| `StructureMap.id`
| | | `StructureMap.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18668)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18669)| `StructureMap.meta`| _Equivalent_<br/>(33547/33548)| **`StructureMap.meta`**| _Equivalent_<br/>(47712/47713)| `StructureMap.meta`
| | | `StructureMap.implicitRules`| _Equivalent_<br/>(18670/18671)| `StructureMap.implicitRules`| _Equivalent_<br/>(33549/33550)| **`StructureMap.implicitRules`**| _Equivalent_<br/>(47714/47715)| `StructureMap.implicitRules`
| | | `StructureMap.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18672)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18673)| `StructureMap.language`| _Equivalent_<br/>(33551/33552)| **`StructureMap.language`**| _Equivalent_<br/>(47716/47717)| `StructureMap.language`
| | | `StructureMap.text`| _Equivalent_<br/>(18674/18675)| `StructureMap.text`| _Equivalent_<br/>(33553/33554)| **`StructureMap.text`**| _Equivalent_<br/>(47718/47719)| `StructureMap.text`
| | | `StructureMap.contained`| _Equivalent_<br/>(18676/18677)| `StructureMap.contained`| _Equivalent_<br/>(33555/33556)| **`StructureMap.contained`**| _Equivalent_<br/>(47720/47721)| `StructureMap.contained`
| | | `StructureMap.extension`| _Equivalent_<br/>(18678/18679)| `StructureMap.extension`| _Equivalent_<br/>(33557/33558)| **`StructureMap.extension`**| _Equivalent_<br/>(47722/47723)| `StructureMap.extension`
| | | `StructureMap.modifierExtension`| _Equivalent_<br/>(18680/18681)| `StructureMap.modifierExtension`| _Equivalent_<br/>(33559/33560)| **`StructureMap.modifierExtension`**| _Equivalent_<br/>(47724/47725)| `StructureMap.modifierExtension`
| | | `StructureMap.url`| _Equivalent_<br/>(18682/18683)| `StructureMap.url`| _Equivalent_<br/>(33561/33562)| **`StructureMap.url`**| _Equivalent_<br/>(47726/47727)| `StructureMap.url`
| | | `StructureMap.identifier`| _Equivalent_<br/>(18684/18685)| `StructureMap.identifier`| _Equivalent_<br/>(33563/33564)| **`StructureMap.identifier`**| _Equivalent_<br/>(47728/47729)| `StructureMap.identifier`
| | | `StructureMap.version`| _Equivalent_<br/>(18686/18687)| `StructureMap.version`| _Equivalent_<br/>(33565/33566)| **`StructureMap.version`**| _Equivalent_<br/>(47730/47731)| `StructureMap.version`
| | | `StructureMap.name`| _Equivalent_<br/>(18688/18689)| `StructureMap.name`| _Equivalent_<br/>(33567/33568)| **`StructureMap.name`**| _Equivalent_<br/>(47732/47733)| `StructureMap.name`
| | | `StructureMap.title`| _Equivalent_<br/>(18690/18691)| `StructureMap.title`| _Equivalent_<br/>(33569/33570)| **`StructureMap.title`**| _Equivalent_<br/>(47734/47735)| `StructureMap.title`
| | | `StructureMap.status`| _Equivalent_<br/>(18692/18693)| `StructureMap.status`| _Equivalent_<br/>(33571/33572)| **`StructureMap.status`**| _Equivalent_<br/>(47736/47737)| `StructureMap.status`
| | | `StructureMap.experimental`| _Equivalent_<br/>(18694/18695)| `StructureMap.experimental`| _Equivalent_<br/>(33573/33574)| **`StructureMap.experimental`**| _Equivalent_<br/>(47738/47739)| `StructureMap.experimental`
| | | `StructureMap.date`| _Equivalent_<br/>(18696/18697)| `StructureMap.date`| _Equivalent_<br/>(33575/33576)| **`StructureMap.date`**| _Equivalent_<br/>(47740/47741)| `StructureMap.date`
| | | `StructureMap.publisher`| _Equivalent_<br/>(18698/18699)| `StructureMap.publisher`| _Equivalent_<br/>(33577/33578)| **`StructureMap.publisher`**| _Equivalent_<br/>(47742/47743)| `StructureMap.publisher`
| | | `StructureMap.contact`| _Equivalent_<br/>(18700/18701)| `StructureMap.contact`| _Equivalent_<br/>(33579/33580)| **`StructureMap.contact`**| _Equivalent_<br/>(47744/47745)| `StructureMap.contact`
| | | `StructureMap.description`| _Equivalent_<br/>(18702/18703)| `StructureMap.description`| _Equivalent_<br/>(33581/33582)| **`StructureMap.description`**| _Equivalent_<br/>(47746/47747)| `StructureMap.description`
| | | `StructureMap.useContext`| _Equivalent_<br/>(18704/18705)| `StructureMap.useContext`| _Equivalent_<br/>(33583/33584)| **`StructureMap.useContext`**| _Equivalent_<br/>(47748/47749)| `StructureMap.useContext`
| | | `StructureMap.jurisdiction`| _Equivalent_<br/>(18706/18707)| `StructureMap.jurisdiction`| _Equivalent_<br/>(33585/33586)| **`StructureMap.jurisdiction`**| _Equivalent_<br/>(47750/47751)| `StructureMap.jurisdiction`
| | | `StructureMap.purpose`| _Equivalent_<br/>(18708/18709)| `StructureMap.purpose`| _Equivalent_<br/>(33587/33588)| **`StructureMap.purpose`**| _Equivalent_<br/>(47752/47753)| `StructureMap.purpose`
| | | `StructureMap.copyright`| _Equivalent_<br/>(18710/18711)| `StructureMap.copyright`| _Equivalent_<br/>(33589/33590)| **`StructureMap.copyright`**| _Equivalent_<br/>(47754/47755)| `StructureMap.copyright`
| | | `StructureMap.structure`| _Equivalent_<br/>(18712/18713)| `StructureMap.structure`| _Equivalent_<br/>(33591/33592)| **`StructureMap.structure`**| _Equivalent_<br/>(47756/47757)| `StructureMap.structure`
| | | `StructureMap.structure.id`| _Equivalent_<br/>(18714/18715)| `StructureMap.structure.id`| _Equivalent_<br/>(33593/33594)| **`StructureMap.structure.id`**| _Equivalent_<br/>(47758/47759)| `StructureMap.structure.id`
| | | `StructureMap.structure.extension`| _Equivalent_<br/>(18716/18717)| `StructureMap.structure.extension`| _Equivalent_<br/>(33595/33596)| **`StructureMap.structure.extension`**| _Equivalent_<br/>(47760/47761)| `StructureMap.structure.extension`
| | | `StructureMap.structure.modifierExtension`| _Equivalent_<br/>(18718/18719)| `StructureMap.structure.modifierExtension`| _Equivalent_<br/>(33597/33598)| **`StructureMap.structure.modifierExtension`**| _Equivalent_<br/>(47762/47763)| `StructureMap.structure.modifierExtension`
| | | `StructureMap.structure.url`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(18720)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18721)| `StructureMap.structure.url`| _Equivalent_<br/>(33599/33600)| **`StructureMap.structure.url`**| _Equivalent_<br/>(47764/47765)| `StructureMap.structure.url`
| | | `StructureMap.structure.mode`| _Equivalent_<br/>(18722/18723)| `StructureMap.structure.mode`| _Equivalent_<br/>(33601/33602)| **`StructureMap.structure.mode`**| _Equivalent_<br/>(47766/47767)| `StructureMap.structure.mode`
| | | `StructureMap.structure.alias`| _Equivalent_<br/>(18724/18725)| `StructureMap.structure.alias`| _Equivalent_<br/>(33603/33604)| **`StructureMap.structure.alias`**| _Equivalent_<br/>(47768/47769)| `StructureMap.structure.alias`
| | | `StructureMap.structure.documentation`| _Equivalent_<br/>(18726/18727)| `StructureMap.structure.documentation`| _Equivalent_<br/>(33605/33606)| **`StructureMap.structure.documentation`**| _Equivalent_<br/>(47770/47771)| `StructureMap.structure.documentation`
| | | `StructureMap.import`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(18728)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18729)| `StructureMap.import`| _Equivalent_<br/>(33607/33608)| **`StructureMap.import`**| _Equivalent_<br/>(47772/47773)| `StructureMap.import`
| | | `StructureMap.group`| _Equivalent_<br/>(18730/18731)| `StructureMap.group`| _Equivalent_<br/>(33609/33610)| **`StructureMap.group`**| _Equivalent_<br/>(47774/47775)| `StructureMap.group`
| | | `StructureMap.group.id`| _Equivalent_<br/>(18732/18733)| `StructureMap.group.id`| _Equivalent_<br/>(33611/33612)| **`StructureMap.group.id`**| _Equivalent_<br/>(47776/47777)| `StructureMap.group.id`
| | | `StructureMap.group.extension`| _Equivalent_<br/>(18734/18735)| `StructureMap.group.extension`| _Equivalent_<br/>(33613/33614)| **`StructureMap.group.extension`**| _Equivalent_<br/>(47778/47779)| `StructureMap.group.extension`
| | | `StructureMap.group.modifierExtension`| _Equivalent_<br/>(18736/18737)| `StructureMap.group.modifierExtension`| _Equivalent_<br/>(33615/33616)| **`StructureMap.group.modifierExtension`**| _Equivalent_<br/>(47780/47781)| `StructureMap.group.modifierExtension`
| | | `StructureMap.group.name`| _Equivalent_<br/>(18738/18739)| `StructureMap.group.name`| _Equivalent_<br/>(33617/33618)| **`StructureMap.group.name`**| _Equivalent_<br/>(47782/47783)| `StructureMap.group.name`
| | | `StructureMap.group.extends`| _Equivalent_<br/>(18740/18741)| `StructureMap.group.extends`| _Equivalent_<br/>(33619/33620)| **`StructureMap.group.extends`**| _Equivalent_<br/>(47784/47785)| `StructureMap.group.extends`
| | | `StructureMap.group.typeMode`| _Equivalent_<br/>(18742/18743)| `StructureMap.group.typeMode`| _Equivalent_<br/>(33621/33622)| **`StructureMap.group.typeMode`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47786)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(47787)| `StructureMap.group.typeMode`
| | | `StructureMap.group.documentation`| _Equivalent_<br/>(18744/18745)| `StructureMap.group.documentation`| _Equivalent_<br/>(33623/33624)| **`StructureMap.group.documentation`**| _Equivalent_<br/>(47788/47789)| `StructureMap.group.documentation`
| | | `StructureMap.group.input`| _Equivalent_<br/>(18746/18747)| `StructureMap.group.input`| _Equivalent_<br/>(33625/33626)| **`StructureMap.group.input`**| _Equivalent_<br/>(47790/47791)| `StructureMap.group.input`
| | | `StructureMap.group.input.id`| _Equivalent_<br/>(18748/18749)| `StructureMap.group.input.id`| _Equivalent_<br/>(33627/33628)| **`StructureMap.group.input.id`**| _Equivalent_<br/>(47792/47793)| `StructureMap.group.input.id`
| | | `StructureMap.group.input.extension`| _Equivalent_<br/>(18750/18751)| `StructureMap.group.input.extension`| _Equivalent_<br/>(33629/33630)| **`StructureMap.group.input.extension`**| _Equivalent_<br/>(47794/47795)| `StructureMap.group.input.extension`
| | | `StructureMap.group.input.modifierExtension`| _Equivalent_<br/>(18752/18753)| `StructureMap.group.input.modifierExtension`| _Equivalent_<br/>(33631/33632)| **`StructureMap.group.input.modifierExtension`**| _Equivalent_<br/>(47796/47797)| `StructureMap.group.input.modifierExtension`
| | | `StructureMap.group.input.name`| _Equivalent_<br/>(18754/18755)| `StructureMap.group.input.name`| _Equivalent_<br/>(33633/33634)| **`StructureMap.group.input.name`**| _Equivalent_<br/>(47798/47799)| `StructureMap.group.input.name`
| | | `StructureMap.group.input.type`| _Equivalent_<br/>(18756/18757)| `StructureMap.group.input.type`| _Equivalent_<br/>(33635/33636)| **`StructureMap.group.input.type`**| _Equivalent_<br/>(47800/47801)| `StructureMap.group.input.type`
| | | `StructureMap.group.input.mode`| _Equivalent_<br/>(18758/18759)| `StructureMap.group.input.mode`| _Equivalent_<br/>(33637/33638)| **`StructureMap.group.input.mode`**| _Equivalent_<br/>(47802/47803)| `StructureMap.group.input.mode`
| | | `StructureMap.group.input.documentation`| _Equivalent_<br/>(18760/18761)| `StructureMap.group.input.documentation`| _Equivalent_<br/>(33639/33640)| **`StructureMap.group.input.documentation`**| _Equivalent_<br/>(47804/47805)| `StructureMap.group.input.documentation`
| | | `StructureMap.group.rule`| _Equivalent_<br/>(18762/18763)| `StructureMap.group.rule`| _Equivalent_<br/>(33641/33642)| **`StructureMap.group.rule`**| →→→→ _Equivalent_ →→→→ <br/>(47806)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(47807)| `StructureMap.group.rule`
| | | `StructureMap.group.rule.id`| _Equivalent_<br/>(18764/18765)| `StructureMap.group.rule.id`| _Equivalent_<br/>(33643/33644)| **`StructureMap.group.rule.id`**| _Equivalent_<br/>(47808/47809)| `StructureMap.group.rule.id`
| | | `StructureMap.group.rule.extension`| _Equivalent_<br/>(18766/18767)| `StructureMap.group.rule.extension`| _Equivalent_<br/>(33645/33646)| **`StructureMap.group.rule.extension`**| _Equivalent_<br/>(47810/47811)| `StructureMap.group.rule.extension`
| | | `StructureMap.group.rule.modifierExtension`| _Equivalent_<br/>(18768/18769)| `StructureMap.group.rule.modifierExtension`| _Equivalent_<br/>(33647/33648)| **`StructureMap.group.rule.modifierExtension`**| _Equivalent_<br/>(47812/47813)| `StructureMap.group.rule.modifierExtension`
| | | `StructureMap.group.rule.name`| _Equivalent_<br/>(18770/18771)| `StructureMap.group.rule.name`| _Equivalent_<br/>(33649/33650)| **`StructureMap.group.rule.name`**| →→→→ _Equivalent_ →→→→ <br/>(47814)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(47815)| `StructureMap.group.rule.name`
| | | `StructureMap.group.rule.source`| _Equivalent_<br/>(18772/18773)| `StructureMap.group.rule.source`| _Equivalent_<br/>(33651/33652)| **`StructureMap.group.rule.source`**| _Equivalent_<br/>(47816/47817)| `StructureMap.group.rule.source`
| | | `StructureMap.group.rule.source.id`| _Equivalent_<br/>(18774/18775)| `StructureMap.group.rule.source.id`| _Equivalent_<br/>(33653/33654)| **`StructureMap.group.rule.source.id`**| _Equivalent_<br/>(47818/47819)| `StructureMap.group.rule.source.id`
| | | `StructureMap.group.rule.source.extension`| _Equivalent_<br/>(18776/18777)| `StructureMap.group.rule.source.extension`| _Equivalent_<br/>(33655/33656)| **`StructureMap.group.rule.source.extension`**| _Equivalent_<br/>(47820/47821)| `StructureMap.group.rule.source.extension`
| | | `StructureMap.group.rule.source.modifierExtension`| _Equivalent_<br/>(18778/18779)| `StructureMap.group.rule.source.modifierExtension`| _Equivalent_<br/>(33657/33658)| **`StructureMap.group.rule.source.modifierExtension`**| _Equivalent_<br/>(47822/47823)| `StructureMap.group.rule.source.modifierExtension`
| | | `StructureMap.group.rule.source.context`| _Equivalent_<br/>(18780/18781)| `StructureMap.group.rule.source.context`| _Equivalent_<br/>(33659/33660)| **`StructureMap.group.rule.source.context`**| _Equivalent_<br/>(47824/47825)| `StructureMap.group.rule.source.context`
| | | `StructureMap.group.rule.source.min`| _Equivalent_<br/>(18782/18783)| `StructureMap.group.rule.source.min`| _Equivalent_<br/>(33661/33662)| **`StructureMap.group.rule.source.min`**| _Equivalent_<br/>(47826/47827)| `StructureMap.group.rule.source.min`
| | | `StructureMap.group.rule.source.max`| _Equivalent_<br/>(18784/18785)| `StructureMap.group.rule.source.max`| _Equivalent_<br/>(33663/33664)| **`StructureMap.group.rule.source.max`**| _Equivalent_<br/>(47828/47829)| `StructureMap.group.rule.source.max`
| | | `StructureMap.group.rule.source.type`| _Equivalent_<br/>(18786/18787)| `StructureMap.group.rule.source.type`| _Equivalent_<br/>(33665/33666)| **`StructureMap.group.rule.source.type`**| _Equivalent_<br/>(47830/47831)| `StructureMap.group.rule.source.type`
| | | `StructureMap.group.rule.source.defaultValue[x]`| →→→→ _RelatedTo_ →→→→ <br/>(18788)<hr/>←←←← _RelatedTo_ ←←←← <br/>(18789)| `StructureMap.group.rule.source.defaultValue[x]`| _Equivalent_<br/>(33667/33668)| **`StructureMap.group.rule.source.defaultValue[x]`**| →→→→ _RelatedTo_ →→→→ <br/>(1849)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2092)| `StructureMap.group.rule.source.defaultValue`
| | | `StructureMap.group.rule.source.element`| _Equivalent_<br/>(18790/18791)| `StructureMap.group.rule.source.element`| _Equivalent_<br/>(33669/33670)| **`StructureMap.group.rule.source.element`**| _Equivalent_<br/>(47832/47833)| `StructureMap.group.rule.source.element`
| | | `StructureMap.group.rule.source.listMode`| _Equivalent_<br/>(18792/18793)| `StructureMap.group.rule.source.listMode`| _Equivalent_<br/>(33671/33672)| **`StructureMap.group.rule.source.listMode`**| _Equivalent_<br/>(47834/47835)| `StructureMap.group.rule.source.listMode`
| | | `StructureMap.group.rule.source.variable`| _Equivalent_<br/>(18794/18795)| `StructureMap.group.rule.source.variable`| _Equivalent_<br/>(33673/33674)| **`StructureMap.group.rule.source.variable`**| _Equivalent_<br/>(47836/47837)| `StructureMap.group.rule.source.variable`
| | | `StructureMap.group.rule.source.condition`| _Equivalent_<br/>(18796/18797)| `StructureMap.group.rule.source.condition`| _Equivalent_<br/>(33675/33676)| **`StructureMap.group.rule.source.condition`**| _Equivalent_<br/>(47838/47839)| `StructureMap.group.rule.source.condition`
| | | `StructureMap.group.rule.source.check`| _Equivalent_<br/>(18798/18799)| `StructureMap.group.rule.source.check`| _Equivalent_<br/>(33677/33678)| **`StructureMap.group.rule.source.check`**| _Equivalent_<br/>(47840/47841)| `StructureMap.group.rule.source.check`
| | | | | `StructureMap.group.rule.source.logMessage`| _Equivalent_<br/>(33679/33680)| **`StructureMap.group.rule.source.logMessage`**| _Equivalent_<br/>(47842/47843)| `StructureMap.group.rule.source.logMessage`
| | | `StructureMap.group.rule.target`| _Equivalent_<br/>(18800/18801)| `StructureMap.group.rule.target`| _Equivalent_<br/>(33681/33682)| **`StructureMap.group.rule.target`**| _Equivalent_<br/>(47844/47845)| `StructureMap.group.rule.target`
| | | `StructureMap.group.rule.target.id`| _Equivalent_<br/>(18802/18803)| `StructureMap.group.rule.target.id`| _Equivalent_<br/>(33683/33684)| **`StructureMap.group.rule.target.id`**| _Equivalent_<br/>(47846/47847)| `StructureMap.group.rule.target.id`
| | | `StructureMap.group.rule.target.extension`| _Equivalent_<br/>(18804/18805)| `StructureMap.group.rule.target.extension`| _Equivalent_<br/>(33685/33686)| **`StructureMap.group.rule.target.extension`**| _Equivalent_<br/>(47848/47849)| `StructureMap.group.rule.target.extension`
| | | `StructureMap.group.rule.target.modifierExtension`| _Equivalent_<br/>(18806/18807)| `StructureMap.group.rule.target.modifierExtension`| _Equivalent_<br/>(33687/33688)| **`StructureMap.group.rule.target.modifierExtension`**| _Equivalent_<br/>(47850/47851)| `StructureMap.group.rule.target.modifierExtension`
| | | `StructureMap.group.rule.target.context`| _Equivalent_<br/>(18808/18809)| `StructureMap.group.rule.target.context`| _Equivalent_<br/>(33689/33690)| **`StructureMap.group.rule.target.context`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47852)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47853)| `StructureMap.group.rule.target.context`
| | | `StructureMap.group.rule.target.contextType`| _Equivalent_<br/>(18810/18811)| `StructureMap.group.rule.target.contextType`| _Equivalent_<br/>(33691/33692)| **`StructureMap.group.rule.target.contextType`**| | | 
| | | `StructureMap.group.rule.target.element`| _Equivalent_<br/>(18812/18813)| `StructureMap.group.rule.target.element`| _Equivalent_<br/>(33693/33694)| **`StructureMap.group.rule.target.element`**| _Equivalent_<br/>(47855/47856)| `StructureMap.group.rule.target.element`
| | | `StructureMap.group.rule.target.variable`| _Equivalent_<br/>(18814/18815)| `StructureMap.group.rule.target.variable`| _Equivalent_<br/>(33695/33696)| **`StructureMap.group.rule.target.variable`**| _Equivalent_<br/>(47857/47858)| `StructureMap.group.rule.target.variable`
| | | `StructureMap.group.rule.target.listMode`| _Equivalent_<br/>(18816/18817)| `StructureMap.group.rule.target.listMode`| _Equivalent_<br/>(33697/33698)| **`StructureMap.group.rule.target.listMode`**| _Equivalent_<br/>(47859/47860)| `StructureMap.group.rule.target.listMode`
| | | `StructureMap.group.rule.target.listRuleId`| _Equivalent_<br/>(18818/18819)| `StructureMap.group.rule.target.listRuleId`| _Equivalent_<br/>(33699/33700)| **`StructureMap.group.rule.target.listRuleId`**| _Equivalent_<br/>(47861/47862)| `StructureMap.group.rule.target.listRuleId`
| | | `StructureMap.group.rule.target.transform`| _Equivalent_<br/>(18820/18821)| `StructureMap.group.rule.target.transform`| _Equivalent_<br/>(33701/33702)| **`StructureMap.group.rule.target.transform`**| _Equivalent_<br/>(47863/47864)| `StructureMap.group.rule.target.transform`
| | | `StructureMap.group.rule.target.parameter`| _Equivalent_<br/>(18822/18823)| `StructureMap.group.rule.target.parameter`| _Equivalent_<br/>(33703/33704)| **`StructureMap.group.rule.target.parameter`**| _Equivalent_<br/>(47865/47866)| `StructureMap.group.rule.target.parameter`
| | | `StructureMap.group.rule.target.parameter.id`| _Equivalent_<br/>(18824/18825)| `StructureMap.group.rule.target.parameter.id`| _Equivalent_<br/>(33705/33706)| **`StructureMap.group.rule.target.parameter.id`**| _Equivalent_<br/>(47867/47868)| `StructureMap.group.rule.target.parameter.id`
| | | `StructureMap.group.rule.target.parameter.extension`| _Equivalent_<br/>(18826/18827)| `StructureMap.group.rule.target.parameter.extension`| _Equivalent_<br/>(33707/33708)| **`StructureMap.group.rule.target.parameter.extension`**| _Equivalent_<br/>(47869/47870)| `StructureMap.group.rule.target.parameter.extension`
| | | `StructureMap.group.rule.target.parameter.modifierExtension`| _Equivalent_<br/>(18828/18829)| `StructureMap.group.rule.target.parameter.modifierExtension`| _Equivalent_<br/>(33709/33710)| **`StructureMap.group.rule.target.parameter.modifierExtension`**| _Equivalent_<br/>(47871/47872)| `StructureMap.group.rule.target.parameter.modifierExtension`
| | | `StructureMap.group.rule.target.parameter.value[x]`| _Equivalent_<br/>(18830/18831)| `StructureMap.group.rule.target.parameter.value[x]`| _Equivalent_<br/>(33711/33712)| **`StructureMap.group.rule.target.parameter.value[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47873)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47874)| `StructureMap.group.rule.target.parameter.value[x]`
| | | `StructureMap.group.rule.rule`| _Equivalent_<br/>(18832/18833)| `StructureMap.group.rule.rule`| _Equivalent_<br/>(33713/33714)| **`StructureMap.group.rule.rule`**| _Equivalent_<br/>(47875/47876)| `StructureMap.group.rule.rule`
| | | `StructureMap.group.rule.dependent`| _Equivalent_<br/>(18834/18835)| `StructureMap.group.rule.dependent`| _Equivalent_<br/>(33715/33716)| **`StructureMap.group.rule.dependent`**| _Equivalent_<br/>(47877/47878)| `StructureMap.group.rule.dependent`
| | | `StructureMap.group.rule.dependent.id`| _Equivalent_<br/>(18836/18837)| `StructureMap.group.rule.dependent.id`| _Equivalent_<br/>(33717/33718)| **`StructureMap.group.rule.dependent.id`**| _Equivalent_<br/>(47879/47880)| `StructureMap.group.rule.dependent.id`
| | | `StructureMap.group.rule.dependent.extension`| _Equivalent_<br/>(18838/18839)| `StructureMap.group.rule.dependent.extension`| _Equivalent_<br/>(33719/33720)| **`StructureMap.group.rule.dependent.extension`**| _Equivalent_<br/>(47881/47882)| `StructureMap.group.rule.dependent.extension`
| | | `StructureMap.group.rule.dependent.modifierExtension`| _Equivalent_<br/>(18840/18841)| `StructureMap.group.rule.dependent.modifierExtension`| _Equivalent_<br/>(33721/33722)| **`StructureMap.group.rule.dependent.modifierExtension`**| _Equivalent_<br/>(47883/47884)| `StructureMap.group.rule.dependent.modifierExtension`
| | | `StructureMap.group.rule.dependent.name`| _Equivalent_<br/>(18842/18843)| `StructureMap.group.rule.dependent.name`| _Equivalent_<br/>(33723/33724)| **`StructureMap.group.rule.dependent.name`**| _Equivalent_<br/>(47885/47886)| `StructureMap.group.rule.dependent.name`
| | | `StructureMap.group.rule.dependent.variable`| _Equivalent_<br/>(18844/18845)| `StructureMap.group.rule.dependent.variable`| _Equivalent_<br/>(33725/33726)| **`StructureMap.group.rule.dependent.variable`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1850)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2093)| `StructureMap.group.rule.dependent.parameter`
| | | `StructureMap.group.rule.documentation`| _Equivalent_<br/>(18846/18847)| `StructureMap.group.rule.documentation`| _Equivalent_<br/>(33727/33728)| **`StructureMap.group.rule.documentation`**| _Equivalent_<br/>(47887/47888)| `StructureMap.group.rule.documentation`
| | | *92 of 92 elements used* | | *93 of 93 elements used* | | *93 of 93 elements used* | | *92 of 100 elements used* <br/>remaining elements:<br/>`StructureMap.const`, `StructureMap.const.extension`, `StructureMap.const.id`, `StructureMap.const.modifierExtension`, `StructureMap.const.name`, `StructureMap.const.value`, `StructureMap.copyrightLabel`, `StructureMap.versionAlgorithm[x]`

