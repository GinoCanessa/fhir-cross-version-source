Comparison of 
Generated at Monday, April 14, 2025 6:17:16 PM

### SearchParameter

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | SearchParameter |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/SearchParameter` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for SearchParameter Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `126` |
| Database Snapshot Count | `29` |
| Database Differential Count | `18` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `SearchParameter` | `SearchParameter` | `SearchParameter` | SearchParameter | Search Parameter for a resource | 1..1 | SearchParameter |  |  |
| `SearchParameter.base` | `SearchParameter.base` | `base` |  | The resource type this search parameter applies to | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/resource-types` |
| `SearchParameter.code` | `SearchParameter.code` | `code` |  | Code used in URL | 1..1 | code |  |  |
| `SearchParameter.contact` | `SearchParameter.contact` | `contact` |  | Contact details of the publisher | 0..* | BackboneElement |  |  |
| `SearchParameter.contact.extension` | `SearchParameter.contact.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `SearchParameter.contact.id` | `SearchParameter.contact.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `SearchParameter.contact.modifierExtension` | `SearchParameter.contact.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `SearchParameter.contact.name` | `SearchParameter.contact.name` | `name` |  | Name of a individual to contact | 0..1 | string |  |  |
| `SearchParameter.contact.telecom` | `SearchParameter.contact.telecom` | `telecom` |  | Contact details for individual or publisher | 0..* | ContactPoint |  |  |
| `SearchParameter.contained` | `SearchParameter.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `SearchParameter.date` | `SearchParameter.date` | `date` |  | Publication Date(/time) | 0..1 | dateTime |  |  |
| `SearchParameter.description` | `SearchParameter.description` | `description` |  | Documentation for  search parameter | 1..1 | string |  |  |
| `SearchParameter.experimental` | `SearchParameter.experimental` | `experimental` |  | If for testing purposes, not real usage | 0..1 | boolean |  |  |
| `SearchParameter.extension` | `SearchParameter.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `SearchParameter.id` | `SearchParameter.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `SearchParameter.implicitRules` | `SearchParameter.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `SearchParameter.language` | `SearchParameter.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `SearchParameter.meta` | `SearchParameter.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `SearchParameter.modifierExtension` | `SearchParameter.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `SearchParameter.name` | `SearchParameter.name` | `name` |  | Informal name for this search parameter | 1..1 | string |  |  |
| `SearchParameter.publisher` | `SearchParameter.publisher` | `publisher` |  | Name of the publisher (Organization or individual) | 0..1 | string |  |  |
| `SearchParameter.requirements` | `SearchParameter.requirements` | `requirements` |  | Why this search parameter is defined | 0..1 | string |  |  |
| `SearchParameter.status` | `SearchParameter.status` | `status` |  | draft \| active \| retired | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/conformance-resource-status` |
| `SearchParameter.target` | `SearchParameter.target` | `target` |  | Types of resource (if a resource reference) | 0..* | code | `Required` | `http://hl7.org/fhir/ValueSet/resource-types` |
| `SearchParameter.text` | `SearchParameter.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `SearchParameter.type` | `SearchParameter.type` | `type` |  | number \| date \| string \| token \| reference \| composite \| quantity \| uri | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/search-param-type` |
| `SearchParameter.url` | `SearchParameter.url` | `url` |  | Absolute URL used to reference this search parameter | 1..1 | uri |  |  |
| `SearchParameter.xpath` | `SearchParameter.xpath` | `xpath` |  | XPath that extracts the values | 0..1 | string |  |  |
| `SearchParameter.xpathUsage` | `SearchParameter.xpathUsage` | `xpathUsage` |  | normal \| phonetic \| nearby \| distance \| other | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/search-xpath-usage` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [SearchParameter](/docs/R2/Resources/SearchParameter.md)<br/> `http://hl7.org/fhir/StructureDefinition/SearchParameter\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `154`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `320`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [SearchParameter](/docs/R3/Resources/SearchParameter.md)<br/> `http://hl7.org/fhir/StructureDefinition/SearchParameter\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `514`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `706`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [SearchParameter](/docs/R4/Resources/SearchParameter.md)<br/> `http://hl7.org/fhir/StructureDefinition/SearchParameter\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1611`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1612`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [SearchParameter](/docs/R4B/Resources/SearchParameter.md)<br/> `http://hl7.org/fhir/StructureDefinition/SearchParameter\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1039`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1268`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [SearchParameter](/docs/R5/Resources/SearchParameter.md)<br/> `http://hl7.org/fhir/StructureDefinition/SearchParameter\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition SearchParameter from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 SearchParameter| Relationship | [R3 SearchParameter](/docs/R3/Resources/SearchParameter.md)| Relationship | [R4 SearchParameter](/docs/R4/Resources/SearchParameter.md)| Relationship | [R4B SearchParameter](/docs/R4B/Resources/SearchParameter.md)| Relationship | [R5 SearchParameter](/docs/R5/Resources/SearchParameter.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`SearchParameter`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7733)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7734)| `SearchParameter`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18270)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18271)| `SearchParameter`| _Equivalent_<br/>(32896/32897)| `SearchParameter`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47218)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47219)| `SearchParameter`
| **`SearchParameter.id`**| _Equivalent_<br/>(7735/7736)| `SearchParameter.id`| _Equivalent_<br/>(18272/18273)| `SearchParameter.id`| _Equivalent_<br/>(32898/32899)| `SearchParameter.id`| _Equivalent_<br/>(47220/47221)| `SearchParameter.id`
| **`SearchParameter.meta`**| _Equivalent_<br/>(7737/7738)| `SearchParameter.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18274)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18275)| `SearchParameter.meta`| _Equivalent_<br/>(32900/32901)| `SearchParameter.meta`| _Equivalent_<br/>(47222/47223)| `SearchParameter.meta`
| **`SearchParameter.implicitRules`**| _Equivalent_<br/>(7739/7740)| `SearchParameter.implicitRules`| _Equivalent_<br/>(18276/18277)| `SearchParameter.implicitRules`| _Equivalent_<br/>(32902/32903)| `SearchParameter.implicitRules`| _Equivalent_<br/>(47224/47225)| `SearchParameter.implicitRules`
| **`SearchParameter.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7741)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7742)| `SearchParameter.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18278)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18279)| `SearchParameter.language`| _Equivalent_<br/>(32904/32905)| `SearchParameter.language`| _Equivalent_<br/>(47226/47227)| `SearchParameter.language`
| **`SearchParameter.text`**| _Equivalent_<br/>(7743/7744)| `SearchParameter.text`| _Equivalent_<br/>(18280/18281)| `SearchParameter.text`| _Equivalent_<br/>(32906/32907)| `SearchParameter.text`| _Equivalent_<br/>(47228/47229)| `SearchParameter.text`
| **`SearchParameter.contained`**| _Equivalent_<br/>(7745/7746)| `SearchParameter.contained`| _Equivalent_<br/>(18282/18283)| `SearchParameter.contained`| _Equivalent_<br/>(32908/32909)| `SearchParameter.contained`| _Equivalent_<br/>(47230/47231)| `SearchParameter.contained`
| **`SearchParameter.extension`**| _Equivalent_<br/>(7747/7748)| `SearchParameter.extension`| _Equivalent_<br/>(18284/18285)| `SearchParameter.extension`| _Equivalent_<br/>(32910/32911)| `SearchParameter.extension`| _Equivalent_<br/>(47232/47233)| `SearchParameter.extension`
| **`SearchParameter.modifierExtension`**| _Equivalent_<br/>(7749/7750)| `SearchParameter.modifierExtension`| _Equivalent_<br/>(18286/18287)| `SearchParameter.modifierExtension`| _Equivalent_<br/>(32912/32913)| `SearchParameter.modifierExtension`| _Equivalent_<br/>(47234/47235)| `SearchParameter.modifierExtension`
| **`SearchParameter.url`**| _Equivalent_<br/>(7751/7752)| `SearchParameter.url`| _Equivalent_<br/>(18288/18289)| `SearchParameter.url`| _Equivalent_<br/>(32914/32915)| `SearchParameter.url`| _Equivalent_<br/>(47236/47237)| `SearchParameter.url`
| **`SearchParameter.name`**| _Equivalent_<br/>(7753/7754)| `SearchParameter.name`| _Equivalent_<br/>(18292/18293)| `SearchParameter.name`| _Equivalent_<br/>(32918/32919)| `SearchParameter.name`| _Equivalent_<br/>(47240/47241)| `SearchParameter.name`
| **`SearchParameter.status`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7755)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7756)| `SearchParameter.status`| _Equivalent_<br/>(18294/18295)| `SearchParameter.status`| _Equivalent_<br/>(32922/32923)| `SearchParameter.status`| _Equivalent_<br/>(47244/47245)| `SearchParameter.status`
| **`SearchParameter.experimental`**| _Equivalent_<br/>(7757/7758)| `SearchParameter.experimental`| _Equivalent_<br/>(18296/18297)| `SearchParameter.experimental`| _Equivalent_<br/>(32924/32925)| `SearchParameter.experimental`| _Equivalent_<br/>(47246/47247)| `SearchParameter.experimental`
| **`SearchParameter.publisher`**| _Equivalent_<br/>(7759/7760)| `SearchParameter.publisher`| _Equivalent_<br/>(18300/18301)| `SearchParameter.publisher`| _Equivalent_<br/>(32928/32929)| `SearchParameter.publisher`| _Equivalent_<br/>(47250/47251)| `SearchParameter.publisher`
| **`SearchParameter.contact`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(7761)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7762)| `SearchParameter.contact`| _Equivalent_<br/>(18302/18303)| `SearchParameter.contact`| _Equivalent_<br/>(32930/32931)| `SearchParameter.contact`| _Equivalent_<br/>(47252/47253)| `SearchParameter.contact`
| **`SearchParameter.contact.id`**| | | | | | | | | 
| **`SearchParameter.contact.extension`**| | | | | | | | | 
| **`SearchParameter.contact.modifierExtension`**| | | | | | | | | 
| **`SearchParameter.contact.name`**| | | | | | | | | 
| **`SearchParameter.contact.telecom`**| | | | | | | | | 
| **`SearchParameter.date`**| _Equivalent_<br/>(7768/7769)| `SearchParameter.date`| _Equivalent_<br/>(18298/18299)| `SearchParameter.date`| _Equivalent_<br/>(32926/32927)| `SearchParameter.date`| _Equivalent_<br/>(47248/47249)| `SearchParameter.date`
| **`SearchParameter.requirements`**| _Equivalent_<br/>(405/749)| `SearchParameter.purpose`| _Equivalent_<br/>(18308/18309)| `SearchParameter.purpose`| _Equivalent_<br/>(32938/32939)| `SearchParameter.purpose`| _Equivalent_<br/>(47260/47261)| `SearchParameter.purpose`
| **`SearchParameter.code`**| _Equivalent_<br/>(7770/7771)| `SearchParameter.code`| _Equivalent_<br/>(18310/18311)| `SearchParameter.code`| _Equivalent_<br/>(32940/32941)| `SearchParameter.code`| _Equivalent_<br/>(47262/47263)| `SearchParameter.code`
| **`SearchParameter.base`**| →→→→ _RelatedTo_ →→→→ <br/>(7772)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7773)| `SearchParameter.base`| →→→→ _Equivalent_ →→→→ <br/>(18312)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18313)| `SearchParameter.base`| →→→→ _Equivalent_ →→→→ <br/>(32942)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(32943)| `SearchParameter.base`| _Equivalent_<br/>(47264/47265)| `SearchParameter.base`
| **`SearchParameter.type`**| _Equivalent_<br/>(7774/7775)| `SearchParameter.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18314)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18315)| `SearchParameter.type`| _Equivalent_<br/>(32944/32945)| `SearchParameter.type`| _Equivalent_<br/>(47266/47267)| `SearchParameter.type`
| **`SearchParameter.description`**| _Equivalent_<br/>(7776/7777)| `SearchParameter.description`| _Equivalent_<br/>(18318/18319)| `SearchParameter.description`| _Equivalent_<br/>(32932/32933)| `SearchParameter.description`| _Equivalent_<br/>(47254/47255)| `SearchParameter.description`
| **`SearchParameter.xpath`**| _Equivalent_<br/>(7778/7779)| `SearchParameter.xpath`| _Equivalent_<br/>(18322/18323)| `SearchParameter.xpath`| _Equivalent_<br/>(32948/32949)| `SearchParameter.xpath`| | | 
| **`SearchParameter.xpathUsage`**| _Equivalent_<br/>(7780/7781)| `SearchParameter.xpathUsage`| _Equivalent_<br/>(18324/18325)| `SearchParameter.xpathUsage`| _Equivalent_<br/>(32950/32951)| `SearchParameter.xpathUsage`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1848)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2091)| `SearchParameter.processingMode`
| **`SearchParameter.target`**| →→→→ _Equivalent_ →→→→ <br/>(7782)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7783)| `SearchParameter.target`| →→→→ _Equivalent_ →→→→ <br/>(18326)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18327)| `SearchParameter.target`| →→→→ _Equivalent_ →→→→ <br/>(32952)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(32953)| `SearchParameter.target`| _Equivalent_<br/>(47271/47272)| `SearchParameter.target`
| *29 of 29 elements used* | | *24 of 38 elements used* <br/>remaining elements:<br/>`SearchParameter.chain`, `SearchParameter.comparator`, `SearchParameter.component`, `SearchParameter.component.definition`, `SearchParameter.component.expression`, `SearchParameter.component.extension`, `SearchParameter.component.id`, `SearchParameter.component.modifierExtension`, `SearchParameter.derivedFrom`, `SearchParameter.expression`, `SearchParameter.jurisdiction`, `SearchParameter.modifier`, `SearchParameter.useContext`, `SearchParameter.version`| | *24 of 40 elements used* <br/>remaining elements:<br/>`SearchParameter.chain`, `SearchParameter.comparator`, `SearchParameter.component`, `SearchParameter.component.definition`, `SearchParameter.component.expression`, `SearchParameter.component.extension`, `SearchParameter.component.id`, `SearchParameter.component.modifierExtension`, `SearchParameter.derivedFrom`, `SearchParameter.expression`, `SearchParameter.jurisdiction`, `SearchParameter.modifier`, `SearchParameter.multipleAnd`, `SearchParameter.multipleOr`, `SearchParameter.useContext`, `SearchParameter.version`| | *24 of 40 elements used* <br/>remaining elements:<br/>`SearchParameter.chain`, `SearchParameter.comparator`, `SearchParameter.component`, `SearchParameter.component.definition`, `SearchParameter.component.expression`, `SearchParameter.component.extension`, `SearchParameter.component.id`, `SearchParameter.component.modifierExtension`, `SearchParameter.derivedFrom`, `SearchParameter.expression`, `SearchParameter.jurisdiction`, `SearchParameter.modifier`, `SearchParameter.multipleAnd`, `SearchParameter.multipleOr`, `SearchParameter.useContext`, `SearchParameter.version`| | *23 of 45 elements used* <br/>remaining elements:<br/>`SearchParameter.chain`, `SearchParameter.comparator`, `SearchParameter.component`, `SearchParameter.component.definition`, `SearchParameter.component.expression`, `SearchParameter.component.extension`, `SearchParameter.component.id`, `SearchParameter.component.modifierExtension`, `SearchParameter.constraint`, `SearchParameter.copyright`, `SearchParameter.copyrightLabel`, `SearchParameter.derivedFrom`, `SearchParameter.expression`, `SearchParameter.identifier`, `SearchParameter.jurisdiction`, `SearchParameter.modifier`, `SearchParameter.multipleAnd`, `SearchParameter.multipleOr`, `SearchParameter.title`, `SearchParameter.useContext`, `SearchParameter.version`, `SearchParameter.versionAlgorithm[x]`

