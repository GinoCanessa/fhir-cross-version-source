Comparison of 
Generated at Tuesday, April 1, 2025 1:39:13 PM

### CodeSystem

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | CodeSystem |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/CodeSystem` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for CodeSystem Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `493` |
| Database Snapshot Count | `68` |
| Database Differential Count | `45` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `CodeSystem` | `CodeSystem` | `CodeSystem` | CodeSystem | A set of codes drawn from one or more code systems | 0..* | CodeSystem |  |  |
| `CodeSystem.caseSensitive` | `CodeSystem.caseSensitive` | `caseSensitive` |  | If code comparison is case sensitive | 0..1 | boolean |  |  |
| `CodeSystem.compositional` | `CodeSystem.compositional` | `compositional` |  | If code system defines a post-composition grammar | 0..1 | boolean |  |  |
| `CodeSystem.concept` | `CodeSystem.concept` | `concept` |  | Concepts in the code system | 0..* | BackboneElement |  |  |
| `CodeSystem.concept.code` | `CodeSystem.concept.code` | `code` |  | Code that identifies concept | 1..1 | code |  |  |
| `CodeSystem.concept.concept` | `CodeSystem.concept.concept` | `concept` |  | Child Concepts (is-a/contains/categorizes) | 0..* | CodeSystem.concept |  |  |
| `CodeSystem.concept.definition` | `CodeSystem.concept.definition` | `definition` |  | Formal definition | 0..1 | string |  |  |
| `CodeSystem.concept.designation` | `CodeSystem.concept.designation` | `designation` |  | Additional representations for the concept | 0..* | BackboneElement |  |  |
| `CodeSystem.concept.designation.extension` | `CodeSystem.concept.designation.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `CodeSystem.concept.designation.id` | `CodeSystem.concept.designation.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `CodeSystem.concept.designation.language` | `CodeSystem.concept.designation.language` | `language` |  | Human language of the designation | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `CodeSystem.concept.designation.modifierExtension` | `CodeSystem.concept.designation.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `CodeSystem.concept.designation.use` | `CodeSystem.concept.designation.use` | `use` |  | Details how this designation would be used | 0..1 | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/designation-use` |
| `CodeSystem.concept.designation.value` | `CodeSystem.concept.designation.value` | `value` |  | The text value for this designation | 1..1 | string |  |  |
| `CodeSystem.concept.display` | `CodeSystem.concept.display` | `display` |  | Text to display to the user | 0..1 | string |  |  |
| `CodeSystem.concept.extension` | `CodeSystem.concept.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `CodeSystem.concept.id` | `CodeSystem.concept.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `CodeSystem.concept.modifierExtension` | `CodeSystem.concept.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `CodeSystem.concept.property` | `CodeSystem.concept.property` | `property` |  | Property value for the concept | 0..* | BackboneElement |  |  |
| `CodeSystem.concept.property.code` | `CodeSystem.concept.property.code` | `code` |  | Reference to CodeSystem.property.code | 1..1 | code |  |  |
| `CodeSystem.concept.property.extension` | `CodeSystem.concept.property.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `CodeSystem.concept.property.id` | `CodeSystem.concept.property.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `CodeSystem.concept.property.modifierExtension` | `CodeSystem.concept.property.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `CodeSystem.concept.property.value[x]` | `CodeSystem.concept.property.value[x]` | `value[x]` |  | Value of the property for this concept | 1..1 | boolean, code, Coding, dateTime, integer, string |  |  |
| `CodeSystem.contact` | `CodeSystem.contact` | `contact` |  | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `CodeSystem.contained` | `CodeSystem.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `CodeSystem.content` | `CodeSystem.content` | `content` |  | not-present \| example \| fragment \| complete | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/codesystem-content-mode` |
| `CodeSystem.copyright` | `CodeSystem.copyright` | `copyright` |  | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `CodeSystem.count` | `CodeSystem.count` | `count` |  | Total concepts in the code system | 0..1 | unsignedInt |  |  |
| `CodeSystem.date` | `CodeSystem.date` | `date` |  | Date this was last changed | 0..1 | dateTime |  |  |
| `CodeSystem.description` | `CodeSystem.description` | `description` |  | Natural language description of the code system | 0..1 | markdown |  |  |
| `CodeSystem.experimental` | `CodeSystem.experimental` | `experimental` |  | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `CodeSystem.extension` | `CodeSystem.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `CodeSystem.filter` | `CodeSystem.filter` | `filter` |  | Filter that can be used in a value set | 0..* | BackboneElement |  |  |
| `CodeSystem.filter.code` | `CodeSystem.filter.code` | `code` |  | Code that identifies the filter | 1..1 | code |  |  |
| `CodeSystem.filter.description` | `CodeSystem.filter.description` | `description` |  | How or why the filter is used | 0..1 | string |  |  |
| `CodeSystem.filter.extension` | `CodeSystem.filter.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `CodeSystem.filter.id` | `CodeSystem.filter.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `CodeSystem.filter.modifierExtension` | `CodeSystem.filter.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `CodeSystem.filter.operator` | `CodeSystem.filter.operator` | `operator` |  | Operators that can be used with filter | 1..* | code | `Required` | `http://hl7.org/fhir/ValueSet/filter-operator` |
| `CodeSystem.filter.value` | `CodeSystem.filter.value` | `value` |  | What to use for the value | 1..1 | string |  |  |
| `CodeSystem.hierarchyMeaning` | `CodeSystem.hierarchyMeaning` | `hierarchyMeaning` |  | grouped-by \| is-a \| part-of \| classified-with | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/codesystem-hierarchy-meaning` |
| `CodeSystem.id` | `CodeSystem.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `CodeSystem.identifier` | `CodeSystem.identifier` | `identifier` |  | Additional identifier for the code system | 0..1 | Identifier |  |  |
| `CodeSystem.implicitRules` | `CodeSystem.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `CodeSystem.jurisdiction` | `CodeSystem.jurisdiction` | `jurisdiction` |  | Intended jurisdiction for code system (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `CodeSystem.language` | `CodeSystem.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `CodeSystem.meta` | `CodeSystem.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `CodeSystem.modifierExtension` | `CodeSystem.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `CodeSystem.name` | `CodeSystem.name` | `name` |  | Name for this code system (computer friendly) | 0..1 | string |  |  |
| `CodeSystem.property` | `CodeSystem.property` | `property` |  | Additional information supplied about each concept | 0..* | BackboneElement |  |  |
| `CodeSystem.property.code` | `CodeSystem.property.code` | `code` |  | Identifies the property on the concepts, and when referred to in operations | 1..1 | code |  |  |
| `CodeSystem.property.description` | `CodeSystem.property.description` | `description` |  | Why the property is defined, and/or what it conveys | 0..1 | string |  |  |
| `CodeSystem.property.extension` | `CodeSystem.property.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `CodeSystem.property.id` | `CodeSystem.property.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `CodeSystem.property.modifierExtension` | `CodeSystem.property.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `CodeSystem.property.type` | `CodeSystem.property.type` | `type` |  | code \| Coding \| string \| integer \| boolean \| dateTime | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/concept-property-type` |
| `CodeSystem.property.uri` | `CodeSystem.property.uri` | `uri` |  | Formal identifier for the property | 0..1 | uri |  |  |
| `CodeSystem.publisher` | `CodeSystem.publisher` | `publisher` |  | Name of the publisher (organization or individual) | 0..1 | string |  |  |
| `CodeSystem.purpose` | `CodeSystem.purpose` | `purpose` |  | Why this code system is defined | 0..1 | markdown |  |  |
| `CodeSystem.status` | `CodeSystem.status` | `status` |  | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status` |
| `CodeSystem.text` | `CodeSystem.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `CodeSystem.title` | `CodeSystem.title` | `title` |  | Name for this code system (human friendly) | 0..1 | string |  |  |
| `CodeSystem.url` | `CodeSystem.url` | `url` |  | Logical URI to reference this code system (globally unique) (Coding.system) | 0..1 | uri |  |  |
| `CodeSystem.useContext` | `CodeSystem.useContext` | `useContext` |  | Context the content is intended to support | 0..* | UsageContext |  |  |
| `CodeSystem.valueSet` | `CodeSystem.valueSet` | `valueSet` |  | Canonical URL for value set with entire code system | 0..1 | uri |  |  |
| `CodeSystem.version` | `CodeSystem.version` | `version` |  | Business version of the code system (Coding.version) | 0..1 | string |  |  |
| `CodeSystem.versionNeeded` | `CodeSystem.versionNeeded` | `versionNeeded` |  | If definitions are not stable | 0..1 | boolean |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ValueSet](/docs/R2/Resources/ValueSet.md)<br/> `http://hl7.org/fhir/StructureDefinition/ValueSet\|1.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `165`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `252`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CodeSystem](/docs/R3/Resources/CodeSystem.md)<br/> `http://hl7.org/fhir/StructureDefinition/CodeSystem\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `433`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `629`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CodeSystem](/docs/R4/Resources/CodeSystem.md)<br/> `http://hl7.org/fhir/StructureDefinition/CodeSystem\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1429`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1430`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CodeSystem](/docs/R4B/Resources/CodeSystem.md)<br/> `http://hl7.org/fhir/StructureDefinition/CodeSystem\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `949`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1178`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CodeSystem](/docs/R5/Resources/CodeSystem.md)<br/> `http://hl7.org/fhir/StructureDefinition/CodeSystem\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition CodeSystem from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 ValueSet](/docs/R2/Resources/ValueSet.md)| Relationship | R3 CodeSystem| Relationship | [R4 CodeSystem](/docs/R4/Resources/CodeSystem.md)| Relationship | [R4B CodeSystem](/docs/R4B/Resources/CodeSystem.md)| Relationship | [R5 CodeSystem](/docs/R5/Resources/CodeSystem.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | **`CodeSystem`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11859)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11860)| `CodeSystem`| _Equivalent_<br/>(23664/23665)| `CodeSystem`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(38993)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(38994)| `CodeSystem`
| | | **`CodeSystem.id`**| _Equivalent_<br/>(11861/11862)| `CodeSystem.id`| _Equivalent_<br/>(23666/23667)| `CodeSystem.id`| _Equivalent_<br/>(38995/38996)| `CodeSystem.id`
| | | **`CodeSystem.meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11863)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11864)| `CodeSystem.meta`| _Equivalent_<br/>(23668/23669)| `CodeSystem.meta`| _Equivalent_<br/>(38997/38998)| `CodeSystem.meta`
| | | **`CodeSystem.implicitRules`**| _Equivalent_<br/>(11865/11866)| `CodeSystem.implicitRules`| _Equivalent_<br/>(23670/23671)| `CodeSystem.implicitRules`| _Equivalent_<br/>(38999/39000)| `CodeSystem.implicitRules`
| | | **`CodeSystem.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11867)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11868)| `CodeSystem.language`| _Equivalent_<br/>(23672/23673)| `CodeSystem.language`| _Equivalent_<br/>(39001/39002)| `CodeSystem.language`
| | | **`CodeSystem.text`**| _Equivalent_<br/>(11869/11870)| `CodeSystem.text`| _Equivalent_<br/>(23674/23675)| `CodeSystem.text`| _Equivalent_<br/>(39003/39004)| `CodeSystem.text`
| | | **`CodeSystem.contained`**| _Equivalent_<br/>(11871/11872)| `CodeSystem.contained`| _Equivalent_<br/>(23676/23677)| `CodeSystem.contained`| _Equivalent_<br/>(39005/39006)| `CodeSystem.contained`
| | | **`CodeSystem.extension`**| _Equivalent_<br/>(11873/11874)| `CodeSystem.extension`| _Equivalent_<br/>(23678/23679)| `CodeSystem.extension`| _Equivalent_<br/>(39007/39008)| `CodeSystem.extension`
| | | **`CodeSystem.modifierExtension`**| _Equivalent_<br/>(11875/11876)| `CodeSystem.modifierExtension`| _Equivalent_<br/>(23680/23681)| `CodeSystem.modifierExtension`| _Equivalent_<br/>(39009/39010)| `CodeSystem.modifierExtension`
| | | **`CodeSystem.url`**| _Equivalent_<br/>(11877/11878)| `CodeSystem.url`| _Equivalent_<br/>(23682/23683)| `CodeSystem.url`| _Equivalent_<br/>(39011/39012)| `CodeSystem.url`
| | | **`CodeSystem.identifier`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11879)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11880)| `CodeSystem.identifier`| _Equivalent_<br/>(23684/23685)| `CodeSystem.identifier`| _Equivalent_<br/>(39013/39014)| `CodeSystem.identifier`
| | | **`CodeSystem.version`**| _Equivalent_<br/>(11881/11882)| `CodeSystem.version`| _Equivalent_<br/>(23686/23687)| `CodeSystem.version`| _Equivalent_<br/>(39015/39016)| `CodeSystem.version`
| | | **`CodeSystem.name`**| _Equivalent_<br/>(11883/11884)| `CodeSystem.name`| _Equivalent_<br/>(23688/23689)| `CodeSystem.name`| _Equivalent_<br/>(39017/39018)| `CodeSystem.name`
| | | **`CodeSystem.title`**| _Equivalent_<br/>(11885/11886)| `CodeSystem.title`| _Equivalent_<br/>(23690/23691)| `CodeSystem.title`| _Equivalent_<br/>(39019/39020)| `CodeSystem.title`
| | | **`CodeSystem.status`**| _Equivalent_<br/>(11887/11888)| `CodeSystem.status`| _Equivalent_<br/>(23692/23693)| `CodeSystem.status`| _Equivalent_<br/>(39021/39022)| `CodeSystem.status`
| | | **`CodeSystem.experimental`**| _Equivalent_<br/>(11889/11890)| `CodeSystem.experimental`| _Equivalent_<br/>(23694/23695)| `CodeSystem.experimental`| _Equivalent_<br/>(39023/39024)| `CodeSystem.experimental`
| | | **`CodeSystem.date`**| _Equivalent_<br/>(11891/11892)| `CodeSystem.date`| _Equivalent_<br/>(23696/23697)| `CodeSystem.date`| _Equivalent_<br/>(39025/39026)| `CodeSystem.date`
| | | **`CodeSystem.publisher`**| _Equivalent_<br/>(11893/11894)| `CodeSystem.publisher`| _Equivalent_<br/>(23698/23699)| `CodeSystem.publisher`| _Equivalent_<br/>(39027/39028)| `CodeSystem.publisher`
| | | **`CodeSystem.contact`**| _Equivalent_<br/>(11895/11896)| `CodeSystem.contact`| _Equivalent_<br/>(23700/23701)| `CodeSystem.contact`| _Equivalent_<br/>(39029/39030)| `CodeSystem.contact`
| | | **`CodeSystem.description`**| _Equivalent_<br/>(11897/11898)| `CodeSystem.description`| _Equivalent_<br/>(23702/23703)| `CodeSystem.description`| _Equivalent_<br/>(39031/39032)| `CodeSystem.description`
| | | **`CodeSystem.useContext`**| _Equivalent_<br/>(11899/11900)| `CodeSystem.useContext`| _Equivalent_<br/>(23704/23705)| `CodeSystem.useContext`| _Equivalent_<br/>(39033/39034)| `CodeSystem.useContext`
| | | **`CodeSystem.jurisdiction`**| _Equivalent_<br/>(11901/11902)| `CodeSystem.jurisdiction`| _Equivalent_<br/>(23706/23707)| `CodeSystem.jurisdiction`| _Equivalent_<br/>(39035/39036)| `CodeSystem.jurisdiction`
| | | **`CodeSystem.purpose`**| _Equivalent_<br/>(11903/11904)| `CodeSystem.purpose`| _Equivalent_<br/>(23708/23709)| `CodeSystem.purpose`| _Equivalent_<br/>(39037/39038)| `CodeSystem.purpose`
| | | **`CodeSystem.copyright`**| _Equivalent_<br/>(11905/11906)| `CodeSystem.copyright`| _Equivalent_<br/>(23710/23711)| `CodeSystem.copyright`| _Equivalent_<br/>(39039/39040)| `CodeSystem.copyright`
| | | **`CodeSystem.caseSensitive`**| _Equivalent_<br/>(11907/11908)| `CodeSystem.caseSensitive`| _Equivalent_<br/>(23712/23713)| `CodeSystem.caseSensitive`| _Equivalent_<br/>(39041/39042)| `CodeSystem.caseSensitive`
| | | **`CodeSystem.valueSet`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(11909)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11910)| `CodeSystem.valueSet`| _Equivalent_<br/>(23714/23715)| `CodeSystem.valueSet`| _Equivalent_<br/>(39043/39044)| `CodeSystem.valueSet`
| | | **`CodeSystem.hierarchyMeaning`**| _Equivalent_<br/>(11911/11912)| `CodeSystem.hierarchyMeaning`| _Equivalent_<br/>(23716/23717)| `CodeSystem.hierarchyMeaning`| _Equivalent_<br/>(39045/39046)| `CodeSystem.hierarchyMeaning`
| | | **`CodeSystem.compositional`**| _Equivalent_<br/>(11913/11914)| `CodeSystem.compositional`| _Equivalent_<br/>(23718/23719)| `CodeSystem.compositional`| _Equivalent_<br/>(39047/39048)| `CodeSystem.compositional`
| | | **`CodeSystem.versionNeeded`**| _Equivalent_<br/>(11915/11916)| `CodeSystem.versionNeeded`| _Equivalent_<br/>(23720/23721)| `CodeSystem.versionNeeded`| _Equivalent_<br/>(39049/39050)| `CodeSystem.versionNeeded`
| | | **`CodeSystem.content`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11917)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11918)| `CodeSystem.content`| _Equivalent_<br/>(23722/23723)| `CodeSystem.content`| _Equivalent_<br/>(39051/39052)| `CodeSystem.content`
| | | **`CodeSystem.count`**| _Equivalent_<br/>(11919/11920)| `CodeSystem.count`| _Equivalent_<br/>(23726/23727)| `CodeSystem.count`| _Equivalent_<br/>(39055/39056)| `CodeSystem.count`
| | | **`CodeSystem.filter`**| _Equivalent_<br/>(11921/11922)| `CodeSystem.filter`| _Equivalent_<br/>(23728/23729)| `CodeSystem.filter`| _Equivalent_<br/>(39057/39058)| `CodeSystem.filter`
| | | **`CodeSystem.filter.id`**| _Equivalent_<br/>(11923/11924)| `CodeSystem.filter.id`| _Equivalent_<br/>(23730/23731)| `CodeSystem.filter.id`| _Equivalent_<br/>(39059/39060)| `CodeSystem.filter.id`
| | | **`CodeSystem.filter.extension`**| _Equivalent_<br/>(11925/11926)| `CodeSystem.filter.extension`| _Equivalent_<br/>(23732/23733)| `CodeSystem.filter.extension`| _Equivalent_<br/>(39061/39062)| `CodeSystem.filter.extension`
| | | **`CodeSystem.filter.modifierExtension`**| _Equivalent_<br/>(11927/11928)| `CodeSystem.filter.modifierExtension`| _Equivalent_<br/>(23734/23735)| `CodeSystem.filter.modifierExtension`| _Equivalent_<br/>(39063/39064)| `CodeSystem.filter.modifierExtension`
| | | **`CodeSystem.filter.code`**| _Equivalent_<br/>(11929/11930)| `CodeSystem.filter.code`| _Equivalent_<br/>(23736/23737)| `CodeSystem.filter.code`| _Equivalent_<br/>(39065/39066)| `CodeSystem.filter.code`
| | | **`CodeSystem.filter.description`**| _Equivalent_<br/>(11931/11932)| `CodeSystem.filter.description`| _Equivalent_<br/>(23738/23739)| `CodeSystem.filter.description`| _Equivalent_<br/>(39067/39068)| `CodeSystem.filter.description`
| | | **`CodeSystem.filter.operator`**| _Equivalent_<br/>(11933/11934)| `CodeSystem.filter.operator`| _Equivalent_<br/>(23740/23741)| `CodeSystem.filter.operator`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(39069)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(39070)| `CodeSystem.filter.operator`
| | | **`CodeSystem.filter.value`**| _Equivalent_<br/>(11935/11936)| `CodeSystem.filter.value`| _Equivalent_<br/>(23742/23743)| `CodeSystem.filter.value`| _Equivalent_<br/>(39071/39072)| `CodeSystem.filter.value`
| | | **`CodeSystem.property`**| _Equivalent_<br/>(11937/11938)| `CodeSystem.property`| _Equivalent_<br/>(23744/23745)| `CodeSystem.property`| _Equivalent_<br/>(39073/39074)| `CodeSystem.property`
| | | **`CodeSystem.property.id`**| _Equivalent_<br/>(11939/11940)| `CodeSystem.property.id`| _Equivalent_<br/>(23746/23747)| `CodeSystem.property.id`| _Equivalent_<br/>(39075/39076)| `CodeSystem.property.id`
| | | **`CodeSystem.property.extension`**| _Equivalent_<br/>(11941/11942)| `CodeSystem.property.extension`| _Equivalent_<br/>(23748/23749)| `CodeSystem.property.extension`| _Equivalent_<br/>(39077/39078)| `CodeSystem.property.extension`
| | | **`CodeSystem.property.modifierExtension`**| _Equivalent_<br/>(11943/11944)| `CodeSystem.property.modifierExtension`| _Equivalent_<br/>(23750/23751)| `CodeSystem.property.modifierExtension`| _Equivalent_<br/>(39079/39080)| `CodeSystem.property.modifierExtension`
| | | **`CodeSystem.property.code`**| _Equivalent_<br/>(11945/11946)| `CodeSystem.property.code`| _Equivalent_<br/>(23752/23753)| `CodeSystem.property.code`| _Equivalent_<br/>(39081/39082)| `CodeSystem.property.code`
| | | **`CodeSystem.property.uri`**| _Equivalent_<br/>(11947/11948)| `CodeSystem.property.uri`| _Equivalent_<br/>(23754/23755)| `CodeSystem.property.uri`| _Equivalent_<br/>(39083/39084)| `CodeSystem.property.uri`
| | | **`CodeSystem.property.description`**| _Equivalent_<br/>(11949/11950)| `CodeSystem.property.description`| _Equivalent_<br/>(23756/23757)| `CodeSystem.property.description`| _Equivalent_<br/>(39085/39086)| `CodeSystem.property.description`
| | | **`CodeSystem.property.type`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11951)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11952)| `CodeSystem.property.type`| _Equivalent_<br/>(23758/23759)| `CodeSystem.property.type`| _Equivalent_<br/>(39087/39088)| `CodeSystem.property.type`
| | | **`CodeSystem.concept`**| _Equivalent_<br/>(11953/11954)| `CodeSystem.concept`| _Equivalent_<br/>(23760/23761)| `CodeSystem.concept`| _Equivalent_<br/>(39089/39090)| `CodeSystem.concept`
| | | **`CodeSystem.concept.id`**| _Equivalent_<br/>(11955/11956)| `CodeSystem.concept.id`| _Equivalent_<br/>(23762/23763)| `CodeSystem.concept.id`| _Equivalent_<br/>(39091/39092)| `CodeSystem.concept.id`
| | | **`CodeSystem.concept.extension`**| _Equivalent_<br/>(11957/11958)| `CodeSystem.concept.extension`| _Equivalent_<br/>(23764/23765)| `CodeSystem.concept.extension`| _Equivalent_<br/>(39093/39094)| `CodeSystem.concept.extension`
| | | **`CodeSystem.concept.modifierExtension`**| _Equivalent_<br/>(11959/11960)| `CodeSystem.concept.modifierExtension`| _Equivalent_<br/>(23766/23767)| `CodeSystem.concept.modifierExtension`| _Equivalent_<br/>(39095/39096)| `CodeSystem.concept.modifierExtension`
| | | **`CodeSystem.concept.code`**| _Equivalent_<br/>(11961/11962)| `CodeSystem.concept.code`| _Equivalent_<br/>(23768/23769)| `CodeSystem.concept.code`| _Equivalent_<br/>(39097/39098)| `CodeSystem.concept.code`
| | | **`CodeSystem.concept.display`**| _Equivalent_<br/>(11963/11964)| `CodeSystem.concept.display`| _Equivalent_<br/>(23770/23771)| `CodeSystem.concept.display`| _Equivalent_<br/>(39099/39100)| `CodeSystem.concept.display`
| | | **`CodeSystem.concept.definition`**| _Equivalent_<br/>(11965/11966)| `CodeSystem.concept.definition`| _Equivalent_<br/>(23772/23773)| `CodeSystem.concept.definition`| _Equivalent_<br/>(39101/39102)| `CodeSystem.concept.definition`
| | | **`CodeSystem.concept.designation`**| _Equivalent_<br/>(11967/11968)| `CodeSystem.concept.designation`| _Equivalent_<br/>(23774/23775)| `CodeSystem.concept.designation`| _Equivalent_<br/>(39103/39104)| `CodeSystem.concept.designation`
| | | **`CodeSystem.concept.designation.id`**| _Equivalent_<br/>(11969/11970)| `CodeSystem.concept.designation.id`| _Equivalent_<br/>(23776/23777)| `CodeSystem.concept.designation.id`| _Equivalent_<br/>(39105/39106)| `CodeSystem.concept.designation.id`
| | | **`CodeSystem.concept.designation.extension`**| _Equivalent_<br/>(11971/11972)| `CodeSystem.concept.designation.extension`| _Equivalent_<br/>(23778/23779)| `CodeSystem.concept.designation.extension`| _Equivalent_<br/>(39107/39108)| `CodeSystem.concept.designation.extension`
| | | **`CodeSystem.concept.designation.modifierExtension`**| _Equivalent_<br/>(11973/11974)| `CodeSystem.concept.designation.modifierExtension`| _Equivalent_<br/>(23780/23781)| `CodeSystem.concept.designation.modifierExtension`| _Equivalent_<br/>(39109/39110)| `CodeSystem.concept.designation.modifierExtension`
| | | **`CodeSystem.concept.designation.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11975)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(11976)| `CodeSystem.concept.designation.language`| _Equivalent_<br/>(23782/23783)| `CodeSystem.concept.designation.language`| _Equivalent_<br/>(39111/39112)| `CodeSystem.concept.designation.language`
| | | **`CodeSystem.concept.designation.use`**| _Equivalent_<br/>(11977/11978)| `CodeSystem.concept.designation.use`| _Equivalent_<br/>(23784/23785)| `CodeSystem.concept.designation.use`| _Equivalent_<br/>(39113/39114)| `CodeSystem.concept.designation.use`
| | | **`CodeSystem.concept.designation.value`**| _Equivalent_<br/>(11979/11980)| `CodeSystem.concept.designation.value`| _Equivalent_<br/>(23786/23787)| `CodeSystem.concept.designation.value`| _Equivalent_<br/>(39115/39116)| `CodeSystem.concept.designation.value`
| | | **`CodeSystem.concept.property`**| _Equivalent_<br/>(11981/11982)| `CodeSystem.concept.property`| _Equivalent_<br/>(23788/23789)| `CodeSystem.concept.property`| _Equivalent_<br/>(39117/39118)| `CodeSystem.concept.property`
| | | **`CodeSystem.concept.property.id`**| _Equivalent_<br/>(11983/11984)| `CodeSystem.concept.property.id`| _Equivalent_<br/>(23790/23791)| `CodeSystem.concept.property.id`| _Equivalent_<br/>(39119/39120)| `CodeSystem.concept.property.id`
| | | **`CodeSystem.concept.property.extension`**| _Equivalent_<br/>(11985/11986)| `CodeSystem.concept.property.extension`| _Equivalent_<br/>(23792/23793)| `CodeSystem.concept.property.extension`| _Equivalent_<br/>(39121/39122)| `CodeSystem.concept.property.extension`
| | | **`CodeSystem.concept.property.modifierExtension`**| _Equivalent_<br/>(11987/11988)| `CodeSystem.concept.property.modifierExtension`| _Equivalent_<br/>(23794/23795)| `CodeSystem.concept.property.modifierExtension`| _Equivalent_<br/>(39123/39124)| `CodeSystem.concept.property.modifierExtension`
| | | **`CodeSystem.concept.property.code`**| _Equivalent_<br/>(11989/11990)| `CodeSystem.concept.property.code`| _Equivalent_<br/>(23796/23797)| `CodeSystem.concept.property.code`| _Equivalent_<br/>(39125/39126)| `CodeSystem.concept.property.code`
| | | **`CodeSystem.concept.property.value[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(11991)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11992)| `CodeSystem.concept.property.value[x]`| _Equivalent_<br/>(23798/23799)| `CodeSystem.concept.property.value[x]`| _Equivalent_<br/>(39127/39128)| `CodeSystem.concept.property.value[x]`
| | | **`CodeSystem.concept.concept`**| _Equivalent_<br/>(11993/11994)| `CodeSystem.concept.concept`| _Equivalent_<br/>(23800/23801)| `CodeSystem.concept.concept`| _Equivalent_<br/>(39129/39130)| `CodeSystem.concept.concept`
| *0 of 103 elements used* | | *68 of 68 elements used* | | *68 of 69 elements used* | | *68 of 69 elements used* | | *68 of 81 elements used* 

