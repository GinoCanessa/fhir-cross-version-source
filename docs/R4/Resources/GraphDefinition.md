Comparison of 
Generated at Friday, April 4, 2025 2:58:47 PM

### GraphDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | GraphDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/GraphDefinition` |
| Version | 4.0.1 |
| Description | A formal computable definition of a graph of resources - that is, a coherent set of resources that form a graph by following references. The Graph Definition resource defines a set and makes rules about the set. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1088` |
| Database Snapshot Count | `49` |
| Database Differential Count | `32` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `GraphDefinition` | `GraphDefinition` | `GraphDefinition` | GraphDefinition | Definition of a graph of resources | 0..* | GraphDefinition |  |  |
| `GraphDefinition.contact` | `GraphDefinition.contact` | `contact` | GraphDefinition.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `GraphDefinition.contained` | `GraphDefinition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `GraphDefinition.date` | `GraphDefinition.date` | `date` | GraphDefinition.date | Date last changed | 0..1 | dateTime |  |  |
| `GraphDefinition.description` | `GraphDefinition.description` | `description` | GraphDefinition.description | Natural language description of the graph definition | 0..1 | markdown |  |  |
| `GraphDefinition.experimental` | `GraphDefinition.experimental` | `experimental` | GraphDefinition.experimental | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `GraphDefinition.extension` | `GraphDefinition.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `GraphDefinition.id` | `GraphDefinition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `GraphDefinition.implicitRules` | `GraphDefinition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `GraphDefinition.jurisdiction` | `GraphDefinition.jurisdiction` | `jurisdiction` | GraphDefinition.jurisdiction | Intended jurisdiction for graph definition (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `GraphDefinition.language` | `GraphDefinition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `GraphDefinition.link` | `GraphDefinition.link` | `link` | GraphDefinition.link | Links this graph makes rules about | 0..* | BackboneElement |  |  |
| `GraphDefinition.link.description` | `GraphDefinition.link.description` | `description` | GraphDefinition.link.description | Why this link is specified | 0..1 | string |  |  |
| `GraphDefinition.link.extension` | `GraphDefinition.link.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `GraphDefinition.link.id` | `GraphDefinition.link.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `GraphDefinition.link.max` | `GraphDefinition.link.max` | `max` | GraphDefinition.link.max | Maximum occurrences for this link | 0..1 | string |  |  |
| `GraphDefinition.link.min` | `GraphDefinition.link.min` | `min` | GraphDefinition.link.min | Minimum occurrences for this link | 0..1 | integer |  |  |
| `GraphDefinition.link.modifierExtension` | `GraphDefinition.link.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `GraphDefinition.link.path` | `GraphDefinition.link.path` | `path` | GraphDefinition.link.path | Path in the resource that contains the link | 0..1 | string |  |  |
| `GraphDefinition.link.sliceName` | `GraphDefinition.link.sliceName` | `sliceName` | GraphDefinition.link.sliceName | Which slice (if profiled) | 0..1 | string |  |  |
| `GraphDefinition.link.target` | `GraphDefinition.link.target` | `target` | GraphDefinition.link.target | Potential target for the link | 0..* | BackboneElement |  |  |
| `GraphDefinition.link.target.compartment` | `GraphDefinition.link.target.compartment` | `compartment` | GraphDefinition.link.target.compartment | Compartment Consistency Rules | 0..* | BackboneElement |  |  |
| `GraphDefinition.link.target.compartment.code` | `GraphDefinition.link.target.compartment.code` | `code` | GraphDefinition.link.target.compartment.code | Patient \| Encounter \| RelatedPerson \| Practitioner \| Device | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/compartment-type|4.0.1` |
| `GraphDefinition.link.target.compartment.description` | `GraphDefinition.link.target.compartment.description` | `description` | GraphDefinition.link.target.compartment.description | Documentation for FHIRPath expression | 0..1 | string |  |  |
| `GraphDefinition.link.target.compartment.expression` | `GraphDefinition.link.target.compartment.expression` | `expression` | GraphDefinition.link.target.compartment.expression | Custom rule, as a FHIRPath expression | 0..1 | string |  |  |
| `GraphDefinition.link.target.compartment.extension` | `GraphDefinition.link.target.compartment.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `GraphDefinition.link.target.compartment.id` | `GraphDefinition.link.target.compartment.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `GraphDefinition.link.target.compartment.modifierExtension` | `GraphDefinition.link.target.compartment.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `GraphDefinition.link.target.compartment.rule` | `GraphDefinition.link.target.compartment.rule` | `rule` | GraphDefinition.link.target.compartment.rule | identical \| matching \| different \| custom | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/graph-compartment-rule|4.0.1` |
| `GraphDefinition.link.target.compartment.use` | `GraphDefinition.link.target.compartment.use` | `use` | GraphDefinition.link.target.compartment.use | condition \| requirement | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/graph-compartment-use|4.0.1` |
| `GraphDefinition.link.target.extension` | `GraphDefinition.link.target.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `GraphDefinition.link.target.id` | `GraphDefinition.link.target.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `GraphDefinition.link.target.link` | `GraphDefinition.link.target.link` | `link` | GraphDefinition.link.target.link | Additional links from target resource | 0..* | GraphDefinition.link |  |  |
| `GraphDefinition.link.target.modifierExtension` | `GraphDefinition.link.target.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `GraphDefinition.link.target.params` | `GraphDefinition.link.target.params` | `params` | GraphDefinition.link.target.params | Criteria for reverse lookup | 0..1 | string |  |  |
| `GraphDefinition.link.target.profile` | `GraphDefinition.link.target.profile` | `profile` | GraphDefinition.link.target.profile | Profile for the target resource | 0..1 | canonical(http://hl7.org/fhir/StructureDefinition/StructureDefinition) |  |  |
| `GraphDefinition.link.target.type` | `GraphDefinition.link.target.type` | `type` | GraphDefinition.link.target.type | Type of resource this link refers to | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/resource-types|4.0.1` |
| `GraphDefinition.meta` | `GraphDefinition.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `GraphDefinition.modifierExtension` | `GraphDefinition.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `GraphDefinition.name` | `GraphDefinition.name` | `name` | GraphDefinition.name | Name for this graph definition (computer friendly) | 1..1 | string |  |  |
| `GraphDefinition.profile` | `GraphDefinition.profile` | `profile` | GraphDefinition.profile | Profile on base resource | 0..1 | canonical(http://hl7.org/fhir/StructureDefinition/StructureDefinition) |  |  |
| `GraphDefinition.publisher` | `GraphDefinition.publisher` | `publisher` | GraphDefinition.publisher | Name of the publisher (organization or individual) | 0..1 | string |  |  |
| `GraphDefinition.purpose` | `GraphDefinition.purpose` | `purpose` | GraphDefinition.purpose | Why this graph definition is defined | 0..1 | markdown |  |  |
| `GraphDefinition.start` | `GraphDefinition.start` | `start` | GraphDefinition.start | Type of resource at which the graph starts | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/resource-types|4.0.1` |
| `GraphDefinition.status` | `GraphDefinition.status` | `status` | GraphDefinition.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|4.0.1` |
| `GraphDefinition.text` | `GraphDefinition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `GraphDefinition.url` | `GraphDefinition.url` | `url` | GraphDefinition.url | Canonical identifier for this graph definition, represented as a URI (globally unique) | 0..1 | uri |  |  |
| `GraphDefinition.useContext` | `GraphDefinition.useContext` | `useContext` | GraphDefinition.useContext | The context that the content is intended to support | 0..* | UsageContext |  |  |
| `GraphDefinition.version` | `GraphDefinition.version` | `version` | GraphDefinition.version | Business version of the graph definition | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [GraphDefinition](/docs/R3/Resources/GraphDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/GraphDefinition\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `464`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `658`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [GraphDefinition](/docs/R4/Resources/GraphDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/GraphDefinition\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1499`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1500`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [GraphDefinition](/docs/R4B/Resources/GraphDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/GraphDefinition\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `983`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1212`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [GraphDefinition](/docs/R5/Resources/GraphDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/GraphDefinition\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition GraphDefinition from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | [R3 GraphDefinition](/docs/R3/Resources/GraphDefinition.md)| Relationship | R4 GraphDefinition| Relationship | [R4B GraphDefinition](/docs/R4B/Resources/GraphDefinition.md)| Relationship | [R5 GraphDefinition](/docs/R5/Resources/GraphDefinition.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `GraphDefinition`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14564)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14565)| **`GraphDefinition`**| _Equivalent_<br/>(27592/27593)| `GraphDefinition`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(42576)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(42577)| `GraphDefinition`
| | | `GraphDefinition.id`| _Equivalent_<br/>(14566/14567)| **`GraphDefinition.id`**| _Equivalent_<br/>(27594/27595)| `GraphDefinition.id`| _Equivalent_<br/>(42578/42579)| `GraphDefinition.id`
| | | `GraphDefinition.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14568)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14569)| **`GraphDefinition.meta`**| _Equivalent_<br/>(27596/27597)| `GraphDefinition.meta`| _Equivalent_<br/>(42580/42581)| `GraphDefinition.meta`
| | | `GraphDefinition.implicitRules`| _Equivalent_<br/>(14570/14571)| **`GraphDefinition.implicitRules`**| _Equivalent_<br/>(27598/27599)| `GraphDefinition.implicitRules`| _Equivalent_<br/>(42582/42583)| `GraphDefinition.implicitRules`
| | | `GraphDefinition.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14572)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(14573)| **`GraphDefinition.language`**| _Equivalent_<br/>(27600/27601)| `GraphDefinition.language`| _Equivalent_<br/>(42584/42585)| `GraphDefinition.language`
| | | `GraphDefinition.text`| _Equivalent_<br/>(14574/14575)| **`GraphDefinition.text`**| _Equivalent_<br/>(27602/27603)| `GraphDefinition.text`| _Equivalent_<br/>(42586/42587)| `GraphDefinition.text`
| | | `GraphDefinition.contained`| _Equivalent_<br/>(14576/14577)| **`GraphDefinition.contained`**| _Equivalent_<br/>(27604/27605)| `GraphDefinition.contained`| _Equivalent_<br/>(42588/42589)| `GraphDefinition.contained`
| | | `GraphDefinition.extension`| _Equivalent_<br/>(14578/14579)| **`GraphDefinition.extension`**| _Equivalent_<br/>(27606/27607)| `GraphDefinition.extension`| _Equivalent_<br/>(42590/42591)| `GraphDefinition.extension`
| | | `GraphDefinition.modifierExtension`| _Equivalent_<br/>(14580/14581)| **`GraphDefinition.modifierExtension`**| _Equivalent_<br/>(27608/27609)| `GraphDefinition.modifierExtension`| _Equivalent_<br/>(42592/42593)| `GraphDefinition.modifierExtension`
| | | `GraphDefinition.url`| _Equivalent_<br/>(14582/14583)| **`GraphDefinition.url`**| _Equivalent_<br/>(27610/27611)| `GraphDefinition.url`| _Equivalent_<br/>(42594/42595)| `GraphDefinition.url`
| | | `GraphDefinition.version`| _Equivalent_<br/>(14584/14585)| **`GraphDefinition.version`**| _Equivalent_<br/>(27612/27613)| `GraphDefinition.version`| _Equivalent_<br/>(42596/42597)| `GraphDefinition.version`
| | | `GraphDefinition.name`| _Equivalent_<br/>(14586/14587)| **`GraphDefinition.name`**| _Equivalent_<br/>(27614/27615)| `GraphDefinition.name`| _Equivalent_<br/>(42598/42599)| `GraphDefinition.name`
| | | `GraphDefinition.status`| _Equivalent_<br/>(14588/14589)| **`GraphDefinition.status`**| _Equivalent_<br/>(27616/27617)| `GraphDefinition.status`| _Equivalent_<br/>(42600/42601)| `GraphDefinition.status`
| | | `GraphDefinition.experimental`| _Equivalent_<br/>(14590/14591)| **`GraphDefinition.experimental`**| _Equivalent_<br/>(27618/27619)| `GraphDefinition.experimental`| _Equivalent_<br/>(42602/42603)| `GraphDefinition.experimental`
| | | `GraphDefinition.date`| _Equivalent_<br/>(14592/14593)| **`GraphDefinition.date`**| _Equivalent_<br/>(27620/27621)| `GraphDefinition.date`| _Equivalent_<br/>(42604/42605)| `GraphDefinition.date`
| | | `GraphDefinition.publisher`| _Equivalent_<br/>(14594/14595)| **`GraphDefinition.publisher`**| _Equivalent_<br/>(27622/27623)| `GraphDefinition.publisher`| _Equivalent_<br/>(42606/42607)| `GraphDefinition.publisher`
| | | `GraphDefinition.contact`| _Equivalent_<br/>(14596/14597)| **`GraphDefinition.contact`**| _Equivalent_<br/>(27624/27625)| `GraphDefinition.contact`| _Equivalent_<br/>(42608/42609)| `GraphDefinition.contact`
| | | `GraphDefinition.description`| _Equivalent_<br/>(14598/14599)| **`GraphDefinition.description`**| _Equivalent_<br/>(27626/27627)| `GraphDefinition.description`| _Equivalent_<br/>(42610/42611)| `GraphDefinition.description`
| | | `GraphDefinition.useContext`| _Equivalent_<br/>(14600/14601)| **`GraphDefinition.useContext`**| _Equivalent_<br/>(27628/27629)| `GraphDefinition.useContext`| _Equivalent_<br/>(42612/42613)| `GraphDefinition.useContext`
| | | `GraphDefinition.jurisdiction`| _Equivalent_<br/>(14602/14603)| **`GraphDefinition.jurisdiction`**| _Equivalent_<br/>(27630/27631)| `GraphDefinition.jurisdiction`| _Equivalent_<br/>(42614/42615)| `GraphDefinition.jurisdiction`
| | | `GraphDefinition.purpose`| _Equivalent_<br/>(14604/14605)| **`GraphDefinition.purpose`**| _Equivalent_<br/>(27632/27633)| `GraphDefinition.purpose`| _Equivalent_<br/>(42616/42617)| `GraphDefinition.purpose`
| | | `GraphDefinition.start`| →→→→ _Equivalent_ →→→→ <br/>(14606)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14607)| **`GraphDefinition.start`**| →→→→ _Equivalent_ →→→→ <br/>(27634)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(27635)| `GraphDefinition.start`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(42618)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(42619)| `GraphDefinition.start`
| | | `GraphDefinition.profile`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(14608)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(14609)| **`GraphDefinition.profile`**| _Equivalent_<br/>(27636/27637)| `GraphDefinition.profile`| | | 
| | | `GraphDefinition.link`| _Equivalent_<br/>(14610/14611)| **`GraphDefinition.link`**| _Equivalent_<br/>(27638/27639)| `GraphDefinition.link`| _Equivalent_<br/>(42621/42622)| `GraphDefinition.link`
| | | `GraphDefinition.link.id`| _Equivalent_<br/>(14612/14613)| **`GraphDefinition.link.id`**| _Equivalent_<br/>(27640/27641)| `GraphDefinition.link.id`| _Equivalent_<br/>(42623/42624)| `GraphDefinition.link.id`
| | | `GraphDefinition.link.extension`| _Equivalent_<br/>(14614/14615)| **`GraphDefinition.link.extension`**| _Equivalent_<br/>(27642/27643)| `GraphDefinition.link.extension`| _Equivalent_<br/>(42625/42626)| `GraphDefinition.link.extension`
| | | `GraphDefinition.link.modifierExtension`| _Equivalent_<br/>(14616/14617)| **`GraphDefinition.link.modifierExtension`**| _Equivalent_<br/>(27644/27645)| `GraphDefinition.link.modifierExtension`| _Equivalent_<br/>(42627/42628)| `GraphDefinition.link.modifierExtension`
| | | `GraphDefinition.link.path`| →→→→ _Equivalent_ →→→→ <br/>(14618)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(14619)| **`GraphDefinition.link.path`**| _Equivalent_<br/>(27646/27647)| `GraphDefinition.link.path`| _Equivalent_<br/>(42629/42630)| `GraphDefinition.link.path`
| | | `GraphDefinition.link.sliceName`| _Equivalent_<br/>(14620/14621)| **`GraphDefinition.link.sliceName`**| _Equivalent_<br/>(27648/27649)| `GraphDefinition.link.sliceName`| _Equivalent_<br/>(42631/42632)| `GraphDefinition.link.sliceName`
| | | `GraphDefinition.link.min`| _Equivalent_<br/>(14622/14623)| **`GraphDefinition.link.min`**| _Equivalent_<br/>(27650/27651)| `GraphDefinition.link.min`| _Equivalent_<br/>(42633/42634)| `GraphDefinition.link.min`
| | | `GraphDefinition.link.max`| _Equivalent_<br/>(14624/14625)| **`GraphDefinition.link.max`**| _Equivalent_<br/>(27652/27653)| `GraphDefinition.link.max`| _Equivalent_<br/>(42635/42636)| `GraphDefinition.link.max`
| | | `GraphDefinition.link.description`| _Equivalent_<br/>(14626/14627)| **`GraphDefinition.link.description`**| _Equivalent_<br/>(27654/27655)| `GraphDefinition.link.description`| _Equivalent_<br/>(42637/42638)| `GraphDefinition.link.description`
| | | `GraphDefinition.link.target`| →→→→ _Equivalent_ →→→→ <br/>(14628)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(14629)| **`GraphDefinition.link.target`**| _Equivalent_<br/>(27656/27657)| `GraphDefinition.link.target`| | | 
| | | `GraphDefinition.link.target.id`| _Equivalent_<br/>(14630/14631)| **`GraphDefinition.link.target.id`**| _Equivalent_<br/>(27658/27659)| `GraphDefinition.link.target.id`| | | 
| | | `GraphDefinition.link.target.extension`| _Equivalent_<br/>(14632/14633)| **`GraphDefinition.link.target.extension`**| _Equivalent_<br/>(27660/27661)| `GraphDefinition.link.target.extension`| | | 
| | | `GraphDefinition.link.target.modifierExtension`| _Equivalent_<br/>(14634/14635)| **`GraphDefinition.link.target.modifierExtension`**| _Equivalent_<br/>(27662/27663)| `GraphDefinition.link.target.modifierExtension`| | | 
| | | `GraphDefinition.link.target.type`| →→→→ _Equivalent_ →→→→ <br/>(14636)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14637)| **`GraphDefinition.link.target.type`**| →→→→ _Equivalent_ →→→→ <br/>(27664)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(27665)| `GraphDefinition.link.target.type`| | | 
| | | | | **`GraphDefinition.link.target.params`**| _Equivalent_<br/>(27666/27667)| `GraphDefinition.link.target.params`| | | 
| | | `GraphDefinition.link.target.profile`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(14638)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(14639)| **`GraphDefinition.link.target.profile`**| _Equivalent_<br/>(27668/27669)| `GraphDefinition.link.target.profile`| | | 
| | | `GraphDefinition.link.target.compartment`| _Equivalent_<br/>(14640/14641)| **`GraphDefinition.link.target.compartment`**| _Equivalent_<br/>(27670/27671)| `GraphDefinition.link.target.compartment`| | | 
| | | `GraphDefinition.link.target.compartment.id`| _Equivalent_<br/>(14642/14643)| **`GraphDefinition.link.target.compartment.id`**| _Equivalent_<br/>(27672/27673)| `GraphDefinition.link.target.compartment.id`| | | 
| | | `GraphDefinition.link.target.compartment.extension`| _Equivalent_<br/>(14644/14645)| **`GraphDefinition.link.target.compartment.extension`**| _Equivalent_<br/>(27674/27675)| `GraphDefinition.link.target.compartment.extension`| | | 
| | | `GraphDefinition.link.target.compartment.modifierExtension`| _Equivalent_<br/>(14646/14647)| **`GraphDefinition.link.target.compartment.modifierExtension`**| _Equivalent_<br/>(27676/27677)| `GraphDefinition.link.target.compartment.modifierExtension`| | | 
| | | | | **`GraphDefinition.link.target.compartment.use`**| _Equivalent_<br/>(27678/27679)| `GraphDefinition.link.target.compartment.use`| | | 
| | | `GraphDefinition.link.target.compartment.code`| _Equivalent_<br/>(14648/14649)| **`GraphDefinition.link.target.compartment.code`**| _Equivalent_<br/>(27680/27681)| `GraphDefinition.link.target.compartment.code`| | | 
| | | `GraphDefinition.link.target.compartment.rule`| _Equivalent_<br/>(14650/14651)| **`GraphDefinition.link.target.compartment.rule`**| _Equivalent_<br/>(27682/27683)| `GraphDefinition.link.target.compartment.rule`| | | 
| | | `GraphDefinition.link.target.compartment.expression`| _Equivalent_<br/>(14652/14653)| **`GraphDefinition.link.target.compartment.expression`**| _Equivalent_<br/>(27684/27685)| `GraphDefinition.link.target.compartment.expression`| | | 
| | | `GraphDefinition.link.target.compartment.description`| _Equivalent_<br/>(14654/14655)| **`GraphDefinition.link.target.compartment.description`**| _Equivalent_<br/>(27686/27687)| `GraphDefinition.link.target.compartment.description`| | | 
| | | `GraphDefinition.link.target.link`| _Equivalent_<br/>(14656/14657)| **`GraphDefinition.link.target.link`**| _Equivalent_<br/>(27688/27689)| `GraphDefinition.link.target.link`| | | 
| | | *47 of 47 elements used* | | *49 of 49 elements used* | | *49 of 49 elements used* | | *31 of 56 elements used* <br/>remaining elements:<br/>`GraphDefinition.copyright`, `GraphDefinition.copyrightLabel`, `GraphDefinition.identifier`, `GraphDefinition.link.compartment`, `GraphDefinition.link.compartment.code`, `GraphDefinition.link.compartment.description`, `GraphDefinition.link.compartment.expression`, `GraphDefinition.link.compartment.extension`, `GraphDefinition.link.compartment.id`, `GraphDefinition.link.compartment.modifierExtension`, `GraphDefinition.link.compartment.rule`, `GraphDefinition.link.compartment.use`, `GraphDefinition.link.params`, `GraphDefinition.link.sourceId`, `GraphDefinition.link.targetId`, `GraphDefinition.node`, `GraphDefinition.node.description`, `GraphDefinition.node.extension`, `GraphDefinition.node.id`, `GraphDefinition.node.modifierExtension`, `GraphDefinition.node.nodeId`, `GraphDefinition.node.profile`, `GraphDefinition.node.type`, `GraphDefinition.title`, `GraphDefinition.versionAlgorithm[x]`

