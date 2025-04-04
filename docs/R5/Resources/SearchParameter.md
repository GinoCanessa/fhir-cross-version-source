Comparison of 
Generated at Friday, April 4, 2025 2:59:02 PM

### SearchParameter

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | SearchParameter |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/SearchParameter` |
| Version | 5.0.0 |
| Description | A search parameter that defines a named search item that can be used to search/filter on a resource. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2380` |
| Database Snapshot Count | `45` |
| Database Differential Count | `34` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `SearchParameter` | `SearchParameter` | `SearchParameter` | SearchParameter | Search parameter for a resource | 0..* | SearchParameter |  |  |
| `SearchParameter.base` | `SearchParameter.base` | `base` | SearchParameter.base | The resource type(s) this search parameter applies to | 1..* | code | `Required` | `http://hl7.org/fhir/ValueSet/version-independent-all-resource-types|5.0.0` |
| `SearchParameter.chain` | `SearchParameter.chain` | `chain` | SearchParameter.chain | Chained names supported | 0..* | string |  |  |
| `SearchParameter.code` | `SearchParameter.code` | `code` | SearchParameter.code | Recommended name for parameter in search url | 1..1 | code |  |  |
| `SearchParameter.comparator` | `SearchParameter.comparator` | `comparator` | SearchParameter.comparator | eq \| ne \| gt \| lt \| ge \| le \| sa \| eb \| ap | 0..* | code | `Required` | `http://hl7.org/fhir/ValueSet/search-comparator|5.0.0` |
| `SearchParameter.component` | `SearchParameter.component` | `component` | SearchParameter.component | For Composite resources to define the parts | 0..* | BackboneElement |  |  |
| `SearchParameter.component.definition` | `SearchParameter.component.definition` | `definition` | SearchParameter.component.definition | Defines how the part works | 1..1 | canonical(http://hl7.org/fhir/StructureDefinition/SearchParameter) |  |  |
| `SearchParameter.component.expression` | `SearchParameter.component.expression` | `expression` | SearchParameter.component.expression | Subexpression relative to main expression | 1..1 | string |  |  |
| `SearchParameter.component.extension` | `SearchParameter.component.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SearchParameter.component.id` | `SearchParameter.component.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `SearchParameter.component.modifierExtension` | `SearchParameter.component.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `SearchParameter.constraint` | `SearchParameter.constraint` | `constraint` | SearchParameter.constraint | FHIRPath expression that constraints the usage of this SearchParamete | 0..1 | string |  |  |
| `SearchParameter.contact` | `SearchParameter.contact` | `contact` | SearchParameter.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `SearchParameter.contained` | `SearchParameter.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `SearchParameter.copyright` | `SearchParameter.copyright` | `copyright` | SearchParameter.copyright | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `SearchParameter.copyrightLabel` | `SearchParameter.copyrightLabel` | `copyrightLabel` | SearchParameter.copyrightLabel | Copyright holder and year(s) | 0..1 | string |  |  |
| `SearchParameter.date` | `SearchParameter.date` | `date` | SearchParameter.date | Date last changed | 0..1 | dateTime |  |  |
| `SearchParameter.derivedFrom` | `SearchParameter.derivedFrom` | `derivedFrom` | SearchParameter.derivedFrom | Original definition for the search parameter | 0..1 | canonical(http://hl7.org/fhir/StructureDefinition/SearchParameter) |  |  |
| `SearchParameter.description` | `SearchParameter.description` | `description` | SearchParameter.description | Natural language description of the search parameter | 1..1 | markdown |  |  |
| `SearchParameter.experimental` | `SearchParameter.experimental` | `experimental` | SearchParameter.experimental | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `SearchParameter.expression` | `SearchParameter.expression` | `expression` | SearchParameter.expression | FHIRPath expression that extracts the values | 0..1 | string |  |  |
| `SearchParameter.extension` | `SearchParameter.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `SearchParameter.id` | `SearchParameter.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `SearchParameter.identifier` | `SearchParameter.identifier` | `identifier` | SearchParameter.identifier | Additional identifier for the search parameter (business identifier) | 0..* | Identifier |  |  |
| `SearchParameter.implicitRules` | `SearchParameter.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `SearchParameter.jurisdiction` | `SearchParameter.jurisdiction` | `jurisdiction` | SearchParameter.jurisdiction | Intended jurisdiction for search parameter (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `SearchParameter.language` | `SearchParameter.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `SearchParameter.meta` | `SearchParameter.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `SearchParameter.modifier` | `SearchParameter.modifier` | `modifier` | SearchParameter.modifier | missing \| exact \| contains \| not \| text \| in \| not-in \| below \| above \| type \| identifier \| of-type \| code-text \| text-advanced \| iterate | 0..* | code | `Required` | `http://hl7.org/fhir/ValueSet/search-modifier-code|5.0.0` |
| `SearchParameter.modifierExtension` | `SearchParameter.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `SearchParameter.multipleAnd` | `SearchParameter.multipleAnd` | `multipleAnd` | SearchParameter.multipleAnd | Allow multiple parameters (and) | 0..1 | boolean |  |  |
| `SearchParameter.multipleOr` | `SearchParameter.multipleOr` | `multipleOr` | SearchParameter.multipleOr | Allow multiple values per parameter (or) | 0..1 | boolean |  |  |
| `SearchParameter.name` | `SearchParameter.name` | `name` | SearchParameter.name | Name for this search parameter (computer friendly) | 1..1 | string |  |  |
| `SearchParameter.processingMode` | `SearchParameter.processingMode` | `processingMode` | SearchParameter.processingMode | normal \| phonetic \| other | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/search-processingmode|5.0.0` |
| `SearchParameter.publisher` | `SearchParameter.publisher` | `publisher` | SearchParameter.publisher | Name of the publisher/steward (organization or individual) | 0..1 | string |  |  |
| `SearchParameter.purpose` | `SearchParameter.purpose` | `purpose` | SearchParameter.purpose | Why this search parameter is defined | 0..1 | markdown |  |  |
| `SearchParameter.status` | `SearchParameter.status` | `status` | SearchParameter.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|5.0.0` |
| `SearchParameter.target` | `SearchParameter.target` | `target` | SearchParameter.target | Types of resource (if a resource reference) | 0..* | code | `Required` | `http://hl7.org/fhir/ValueSet/version-independent-all-resource-types|5.0.0` |
| `SearchParameter.text` | `SearchParameter.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `SearchParameter.title` | `SearchParameter.title` | `title` | SearchParameter.title | Name for this search parameter (human friendly) | 0..1 | string |  |  |
| `SearchParameter.type` | `SearchParameter.type` | `type` | SearchParameter.type | number \| date \| string \| token \| reference \| composite \| quantity \| uri \| special | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/search-param-type|5.0.0` |
| `SearchParameter.url` | `SearchParameter.url` | `url` | SearchParameter.url | Canonical identifier for this search parameter, represented as a URI (globally unique) | 1..1 | uri |  |  |
| `SearchParameter.useContext` | `SearchParameter.useContext` | `useContext` | SearchParameter.useContext | The context that the content is intended to support | 0..* | UsageContext |  |  |
| `SearchParameter.version` | `SearchParameter.version` | `version` | SearchParameter.version | Business version of the search parameter | 0..1 | string |  |  |
| `SearchParameter.versionAlgorithm[x]` | `SearchParameter.versionAlgorithm[x]` | `versionAlgorithm[x]` | SearchParameter.versionAlgorithm[x] | How to compare versions | 0..1 | Coding, string | `Extensible` | `http://hl7.org/fhir/ValueSet/version-algorithm` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [SearchParameter](/docs/R2/Resources/SearchParameter.md)<br/> `http://hl7.org/fhir/StructureDefinition/SearchParameter\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `154`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `320`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SearchParameter](/docs/R3/Resources/SearchParameter.md)<br/> `http://hl7.org/fhir/StructureDefinition/SearchParameter\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `514`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `706`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SearchParameter](/docs/R4/Resources/SearchParameter.md)<br/> `http://hl7.org/fhir/StructureDefinition/SearchParameter\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1611`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1612`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SearchParameter](/docs/R4B/Resources/SearchParameter.md)<br/> `http://hl7.org/fhir/StructureDefinition/SearchParameter\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1039`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1268`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SearchParameter](/docs/R5/Resources/SearchParameter.md)<br/> `http://hl7.org/fhir/StructureDefinition/SearchParameter\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition SearchParameter from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 SearchParameter](/docs/R2/Resources/SearchParameter.md)| Relationship | [R3 SearchParameter](/docs/R3/Resources/SearchParameter.md)| Relationship | [R4 SearchParameter](/docs/R4/Resources/SearchParameter.md)| Relationship | [R4B SearchParameter](/docs/R4B/Resources/SearchParameter.md)| Relationship | R5 SearchParameter
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `SearchParameter`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7733)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7734)| `SearchParameter`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18270)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18271)| `SearchParameter`| _Equivalent_<br/>(32896/32897)| `SearchParameter`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47218)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47219)| **`SearchParameter`**
| `SearchParameter.id`| _Equivalent_<br/>(7735/7736)| `SearchParameter.id`| _Equivalent_<br/>(18272/18273)| `SearchParameter.id`| _Equivalent_<br/>(32898/32899)| `SearchParameter.id`| _Equivalent_<br/>(47220/47221)| **`SearchParameter.id`**
| `SearchParameter.meta`| _Equivalent_<br/>(7737/7738)| `SearchParameter.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18274)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18275)| `SearchParameter.meta`| _Equivalent_<br/>(32900/32901)| `SearchParameter.meta`| _Equivalent_<br/>(47222/47223)| **`SearchParameter.meta`**
| `SearchParameter.implicitRules`| _Equivalent_<br/>(7739/7740)| `SearchParameter.implicitRules`| _Equivalent_<br/>(18276/18277)| `SearchParameter.implicitRules`| _Equivalent_<br/>(32902/32903)| `SearchParameter.implicitRules`| _Equivalent_<br/>(47224/47225)| **`SearchParameter.implicitRules`**
| `SearchParameter.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7741)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7742)| `SearchParameter.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18278)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18279)| `SearchParameter.language`| _Equivalent_<br/>(32904/32905)| `SearchParameter.language`| _Equivalent_<br/>(47226/47227)| **`SearchParameter.language`**
| `SearchParameter.text`| _Equivalent_<br/>(7743/7744)| `SearchParameter.text`| _Equivalent_<br/>(18280/18281)| `SearchParameter.text`| _Equivalent_<br/>(32906/32907)| `SearchParameter.text`| _Equivalent_<br/>(47228/47229)| **`SearchParameter.text`**
| `SearchParameter.contained`| _Equivalent_<br/>(7745/7746)| `SearchParameter.contained`| _Equivalent_<br/>(18282/18283)| `SearchParameter.contained`| _Equivalent_<br/>(32908/32909)| `SearchParameter.contained`| _Equivalent_<br/>(47230/47231)| **`SearchParameter.contained`**
| `SearchParameter.extension`| _Equivalent_<br/>(7747/7748)| `SearchParameter.extension`| _Equivalent_<br/>(18284/18285)| `SearchParameter.extension`| _Equivalent_<br/>(32910/32911)| `SearchParameter.extension`| _Equivalent_<br/>(47232/47233)| **`SearchParameter.extension`**
| `SearchParameter.modifierExtension`| _Equivalent_<br/>(7749/7750)| `SearchParameter.modifierExtension`| _Equivalent_<br/>(18286/18287)| `SearchParameter.modifierExtension`| _Equivalent_<br/>(32912/32913)| `SearchParameter.modifierExtension`| _Equivalent_<br/>(47234/47235)| **`SearchParameter.modifierExtension`**
| `SearchParameter.url`| _Equivalent_<br/>(7751/7752)| `SearchParameter.url`| _Equivalent_<br/>(18288/18289)| `SearchParameter.url`| _Equivalent_<br/>(32914/32915)| `SearchParameter.url`| _Equivalent_<br/>(47236/47237)| **`SearchParameter.url`**
| | | | | | | | | **`SearchParameter.identifier`**
| | | `SearchParameter.version`| _Equivalent_<br/>(18290/18291)| `SearchParameter.version`| _Equivalent_<br/>(32916/32917)| `SearchParameter.version`| _Equivalent_<br/>(47238/47239)| **`SearchParameter.version`**
| | | | | | | | | **`SearchParameter.versionAlgorithm[x]`**
| `SearchParameter.name`| _Equivalent_<br/>(7753/7754)| `SearchParameter.name`| _Equivalent_<br/>(18292/18293)| `SearchParameter.name`| _Equivalent_<br/>(32918/32919)| `SearchParameter.name`| _Equivalent_<br/>(47240/47241)| **`SearchParameter.name`**
| | | | | | | | | **`SearchParameter.title`**
| | | `SearchParameter.derivedFrom`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(18316)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18317)| `SearchParameter.derivedFrom`| _Equivalent_<br/>(32920/32921)| `SearchParameter.derivedFrom`| _Equivalent_<br/>(47242/47243)| **`SearchParameter.derivedFrom`**
| `SearchParameter.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7755)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7756)| `SearchParameter.status`| _Equivalent_<br/>(18294/18295)| `SearchParameter.status`| _Equivalent_<br/>(32922/32923)| `SearchParameter.status`| _Equivalent_<br/>(47244/47245)| **`SearchParameter.status`**
| `SearchParameter.experimental`| _Equivalent_<br/>(7757/7758)| `SearchParameter.experimental`| _Equivalent_<br/>(18296/18297)| `SearchParameter.experimental`| _Equivalent_<br/>(32924/32925)| `SearchParameter.experimental`| _Equivalent_<br/>(47246/47247)| **`SearchParameter.experimental`**
| `SearchParameter.date`| _Equivalent_<br/>(7768/7769)| `SearchParameter.date`| _Equivalent_<br/>(18298/18299)| `SearchParameter.date`| _Equivalent_<br/>(32926/32927)| `SearchParameter.date`| _Equivalent_<br/>(47248/47249)| **`SearchParameter.date`**
| `SearchParameter.publisher`| _Equivalent_<br/>(7759/7760)| `SearchParameter.publisher`| _Equivalent_<br/>(18300/18301)| `SearchParameter.publisher`| _Equivalent_<br/>(32928/32929)| `SearchParameter.publisher`| _Equivalent_<br/>(47250/47251)| **`SearchParameter.publisher`**
| `SearchParameter.contact`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(7761)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7762)| `SearchParameter.contact`| _Equivalent_<br/>(18302/18303)| `SearchParameter.contact`| _Equivalent_<br/>(32930/32931)| `SearchParameter.contact`| _Equivalent_<br/>(47252/47253)| **`SearchParameter.contact`**
| `SearchParameter.description`| _Equivalent_<br/>(7776/7777)| `SearchParameter.description`| _Equivalent_<br/>(18318/18319)| `SearchParameter.description`| _Equivalent_<br/>(32932/32933)| `SearchParameter.description`| _Equivalent_<br/>(47254/47255)| **`SearchParameter.description`**
| | | `SearchParameter.useContext`| _Equivalent_<br/>(18304/18305)| `SearchParameter.useContext`| _Equivalent_<br/>(32934/32935)| `SearchParameter.useContext`| _Equivalent_<br/>(47256/47257)| **`SearchParameter.useContext`**
| | | `SearchParameter.jurisdiction`| _Equivalent_<br/>(18306/18307)| `SearchParameter.jurisdiction`| _Equivalent_<br/>(32936/32937)| `SearchParameter.jurisdiction`| _Equivalent_<br/>(47258/47259)| **`SearchParameter.jurisdiction`**
| `SearchParameter.requirements`| _Equivalent_<br/>(405/749)| `SearchParameter.purpose`| _Equivalent_<br/>(18308/18309)| `SearchParameter.purpose`| _Equivalent_<br/>(32938/32939)| `SearchParameter.purpose`| _Equivalent_<br/>(47260/47261)| **`SearchParameter.purpose`**
| | | | | | | | | **`SearchParameter.copyright`**
| | | | | | | | | **`SearchParameter.copyrightLabel`**
| `SearchParameter.code`| _Equivalent_<br/>(7770/7771)| `SearchParameter.code`| _Equivalent_<br/>(18310/18311)| `SearchParameter.code`| _Equivalent_<br/>(32940/32941)| `SearchParameter.code`| _Equivalent_<br/>(47262/47263)| **`SearchParameter.code`**
| `SearchParameter.base`| →→→→ _RelatedTo_ →→→→ <br/>(7772)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7773)| `SearchParameter.base`| →→→→ _Equivalent_ →→→→ <br/>(18312)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18313)| `SearchParameter.base`| →→→→ _Equivalent_ →→→→ <br/>(32942)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(32943)| `SearchParameter.base`| _Equivalent_<br/>(47264/47265)| **`SearchParameter.base`**
| `SearchParameter.type`| _Equivalent_<br/>(7774/7775)| `SearchParameter.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18314)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18315)| `SearchParameter.type`| _Equivalent_<br/>(32944/32945)| `SearchParameter.type`| _Equivalent_<br/>(47266/47267)| **`SearchParameter.type`**
| | | `SearchParameter.expression`| _Equivalent_<br/>(18320/18321)| `SearchParameter.expression`| _Equivalent_<br/>(32946/32947)| `SearchParameter.expression`| _Equivalent_<br/>(47268/47269)| **`SearchParameter.expression`**
| `SearchParameter.xpathUsage`| _Equivalent_<br/>(7780/7781)| `SearchParameter.xpathUsage`| _Equivalent_<br/>(18324/18325)| `SearchParameter.xpathUsage`| _Equivalent_<br/>(32950/32951)| `SearchParameter.xpathUsage`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1848)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2091)| **`SearchParameter.processingMode`**
| | | | | | | | | **`SearchParameter.constraint`**
| `SearchParameter.target`| →→→→ _Equivalent_ →→→→ <br/>(7782)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7783)| `SearchParameter.target`| →→→→ _Equivalent_ →→→→ <br/>(18326)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18327)| `SearchParameter.target`| →→→→ _Equivalent_ →→→→ <br/>(32952)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(32953)| `SearchParameter.target`| _Equivalent_<br/>(47271/47272)| **`SearchParameter.target`**
| | | | | `SearchParameter.multipleOr`| _Equivalent_<br/>(32954/32955)| `SearchParameter.multipleOr`| _Equivalent_<br/>(47273/47274)| **`SearchParameter.multipleOr`**
| | | | | `SearchParameter.multipleAnd`| _Equivalent_<br/>(32956/32957)| `SearchParameter.multipleAnd`| _Equivalent_<br/>(47275/47276)| **`SearchParameter.multipleAnd`**
| | | `SearchParameter.comparator`| _Equivalent_<br/>(18328/18329)| `SearchParameter.comparator`| _Equivalent_<br/>(32958/32959)| `SearchParameter.comparator`| _Equivalent_<br/>(47277/47278)| **`SearchParameter.comparator`**
| | | `SearchParameter.modifier`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18330)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18331)| `SearchParameter.modifier`| _Equivalent_<br/>(32960/32961)| `SearchParameter.modifier`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47279)<hr/>←←←← _RelatedTo_ ←←←← <br/>(47280)| **`SearchParameter.modifier`**
| | | `SearchParameter.chain`| _Equivalent_<br/>(18332/18333)| `SearchParameter.chain`| _Equivalent_<br/>(32962/32963)| `SearchParameter.chain`| _Equivalent_<br/>(47281/47282)| **`SearchParameter.chain`**
| | | `SearchParameter.component`| _Equivalent_<br/>(18334/18335)| `SearchParameter.component`| _Equivalent_<br/>(32964/32965)| `SearchParameter.component`| _Equivalent_<br/>(47283/47284)| **`SearchParameter.component`**
| | | `SearchParameter.component.id`| _Equivalent_<br/>(18336/18337)| `SearchParameter.component.id`| _Equivalent_<br/>(32966/32967)| `SearchParameter.component.id`| _Equivalent_<br/>(47285/47286)| **`SearchParameter.component.id`**
| | | `SearchParameter.component.extension`| _Equivalent_<br/>(18338/18339)| `SearchParameter.component.extension`| _Equivalent_<br/>(32968/32969)| `SearchParameter.component.extension`| _Equivalent_<br/>(47287/47288)| **`SearchParameter.component.extension`**
| | | `SearchParameter.component.modifierExtension`| _Equivalent_<br/>(18340/18341)| `SearchParameter.component.modifierExtension`| _Equivalent_<br/>(32970/32971)| `SearchParameter.component.modifierExtension`| _Equivalent_<br/>(47289/47290)| **`SearchParameter.component.modifierExtension`**
| | | `SearchParameter.component.definition`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(18342)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18343)| `SearchParameter.component.definition`| _Equivalent_<br/>(32972/32973)| `SearchParameter.component.definition`| _Equivalent_<br/>(47291/47292)| **`SearchParameter.component.definition`**
| | | `SearchParameter.component.expression`| _Equivalent_<br/>(18344/18345)| `SearchParameter.component.expression`| _Equivalent_<br/>(32974/32975)| `SearchParameter.component.expression`| _Equivalent_<br/>(47293/47294)| **`SearchParameter.component.expression`**
| *23 of 29 elements used* <br/>remaining elements:<br/>`SearchParameter.contact.extension`, `SearchParameter.contact.id`, `SearchParameter.contact.modifierExtension`, `SearchParameter.contact.name`, `SearchParameter.contact.telecom`, `SearchParameter.xpath`| | *37 of 38 elements used* <br/>remaining elements:<br/>`SearchParameter.xpath`| | *39 of 40 elements used* <br/>remaining elements:<br/>`SearchParameter.xpath`| | *39 of 40 elements used* <br/>remaining elements:<br/>`SearchParameter.xpath`| | *45 of 45 elements used* 

