Comparison of 
Generated at Thursday, April 3, 2025 8:18:13 AM

### Measure

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | Measure |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Measure` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for Measure Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `539` |
| Database Snapshot Count | `75` |
| Database Differential Count | `55` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Measure` | `Measure` | `Measure` | Measure | A quality measure definition | 0..* | Measure |  |  |
| `Measure.approvalDate` | `Measure.approvalDate` | `approvalDate` |  | When the measure was approved by publisher | 0..1 | date |  |  |
| `Measure.clinicalRecommendationStatement` | `Measure.clinicalRecommendationStatement` | `clinicalRecommendationStatement` |  | Summary of clinical guidelines | 0..1 | markdown |  |  |
| `Measure.compositeScoring` | `Measure.compositeScoring` | `compositeScoring` |  | opportunity \| all-or-nothing \| linear \| weighted | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/composite-measure-scoring` |
| `Measure.contact` | `Measure.contact` | `contact` |  | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `Measure.contained` | `Measure.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Measure.contributor` | `Measure.contributor` | `contributor` |  | A content contributor | 0..* | Contributor |  |  |
| `Measure.copyright` | `Measure.copyright` | `copyright` |  | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `Measure.date` | `Measure.date` | `date` |  | Date this was last changed | 0..1 | dateTime |  |  |
| `Measure.definition` | `Measure.definition` | `definition` |  | Defined terms used in the measure documentation | 0..* | markdown |  |  |
| `Measure.description` | `Measure.description` | `description` |  | Natural language description of the measure | 0..1 | markdown |  |  |
| `Measure.disclaimer` | `Measure.disclaimer` | `disclaimer` |  | Disclaimer for use of the measure or its referenced content | 0..1 | markdown |  |  |
| `Measure.effectivePeriod` | `Measure.effectivePeriod` | `effectivePeriod` |  | When the measure is expected to be used | 0..1 | Period |  |  |
| `Measure.experimental` | `Measure.experimental` | `experimental` |  | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `Measure.extension` | `Measure.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Measure.group` | `Measure.group` | `group` |  | Population criteria group | 0..* | BackboneElement |  |  |
| `Measure.group.description` | `Measure.group.description` | `description` |  | Summary description | 0..1 | string |  |  |
| `Measure.group.extension` | `Measure.group.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Measure.group.id` | `Measure.group.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Measure.group.identifier` | `Measure.group.identifier` | `identifier` |  | Unique identifier | 1..1 | Identifier |  |  |
| `Measure.group.modifierExtension` | `Measure.group.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Measure.group.name` | `Measure.group.name` | `name` |  | Short name | 0..1 | string |  |  |
| `Measure.group.population` | `Measure.group.population` | `population` |  | Population criteria | 0..* | BackboneElement |  |  |
| `Measure.group.population.code` | `Measure.group.population.code` | `code` |  | initial-population \| numerator \| numerator-exclusion \| denominator \| denominator-exclusion \| denominator-exception \| measure-population \| measure-population-exclusion \| measure-observation | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/measure-population` |
| `Measure.group.population.criteria` | `Measure.group.population.criteria` | `criteria` |  | The name of a valid referenced CQL expression (may be namespaced) that defines this population criteria | 1..1 | string |  |  |
| `Measure.group.population.description` | `Measure.group.population.description` | `description` |  | The human readable description of this population criteria | 0..1 | string |  |  |
| `Measure.group.population.extension` | `Measure.group.population.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Measure.group.population.id` | `Measure.group.population.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Measure.group.population.identifier` | `Measure.group.population.identifier` | `identifier` |  | Unique identifier | 0..1 | Identifier |  |  |
| `Measure.group.population.modifierExtension` | `Measure.group.population.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Measure.group.population.name` | `Measure.group.population.name` | `name` |  | Short name | 0..1 | string |  |  |
| `Measure.group.stratifier` | `Measure.group.stratifier` | `stratifier` |  | Stratifier criteria for the measure | 0..* | BackboneElement |  |  |
| `Measure.group.stratifier.criteria` | `Measure.group.stratifier.criteria` | `criteria` |  | How the measure should be stratified | 0..1 | string |  |  |
| `Measure.group.stratifier.extension` | `Measure.group.stratifier.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Measure.group.stratifier.id` | `Measure.group.stratifier.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Measure.group.stratifier.identifier` | `Measure.group.stratifier.identifier` | `identifier` |  | The identifier for the stratifier used to coordinate the reported data back to this stratifier | 0..1 | Identifier |  |  |
| `Measure.group.stratifier.modifierExtension` | `Measure.group.stratifier.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Measure.group.stratifier.path` | `Measure.group.stratifier.path` | `path` |  | Path to the stratifier | 0..1 | string |  |  |
| `Measure.guidance` | `Measure.guidance` | `guidance` |  | Additional guidance for implementers | 0..1 | markdown |  |  |
| `Measure.id` | `Measure.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Measure.identifier` | `Measure.identifier` | `identifier` |  | Additional identifier for the measure | 0..* | Identifier |  |  |
| `Measure.implicitRules` | `Measure.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Measure.improvementNotation` | `Measure.improvementNotation` | `improvementNotation` |  | Improvement notation for the measure, e.g. higher score indicates better quality | 0..1 | string |  |  |
| `Measure.jurisdiction` | `Measure.jurisdiction` | `jurisdiction` |  | Intended jurisdiction for measure (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `Measure.language` | `Measure.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `Measure.lastReviewDate` | `Measure.lastReviewDate` | `lastReviewDate` |  | When the measure was last reviewed | 0..1 | date |  |  |
| `Measure.library` | `Measure.library` | `library` |  | Logic used by the measure | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Library) |  |  |
| `Measure.meta` | `Measure.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Measure.modifierExtension` | `Measure.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Measure.name` | `Measure.name` | `name` |  | Name for this measure (computer friendly) | 0..1 | string |  |  |
| `Measure.publisher` | `Measure.publisher` | `publisher` |  | Name of the publisher (organization or individual) | 0..1 | string |  |  |
| `Measure.purpose` | `Measure.purpose` | `purpose` |  | Why this measure is defined | 0..1 | markdown |  |  |
| `Measure.rateAggregation` | `Measure.rateAggregation` | `rateAggregation` |  | How is rate aggregation performed for this measure | 0..1 | string |  |  |
| `Measure.rationale` | `Measure.rationale` | `rationale` |  | Why does this measure exist | 0..1 | markdown |  |  |
| `Measure.relatedArtifact` | `Measure.relatedArtifact` | `relatedArtifact` |  | Additional documentation, citations, etc | 0..* | RelatedArtifact |  |  |
| `Measure.riskAdjustment` | `Measure.riskAdjustment` | `riskAdjustment` |  | How is risk adjustment applied for this measure | 0..1 | string |  |  |
| `Measure.scoring` | `Measure.scoring` | `scoring` |  | proportion \| ratio \| continuous-variable \| cohort | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/measure-scoring` |
| `Measure.set` | `Measure.set` | `set` |  | The measure set, e.g. Preventive Care and Screening | 0..1 | string |  |  |
| `Measure.status` | `Measure.status` | `status` |  | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status` |
| `Measure.supplementalData` | `Measure.supplementalData` | `supplementalData` |  | What other data should be reported with the measure | 0..* | BackboneElement |  |  |
| `Measure.supplementalData.criteria` | `Measure.supplementalData.criteria` | `criteria` |  | Expression describing additional data to be reported | 0..1 | string |  |  |
| `Measure.supplementalData.extension` | `Measure.supplementalData.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Measure.supplementalData.id` | `Measure.supplementalData.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Measure.supplementalData.identifier` | `Measure.supplementalData.identifier` | `identifier` |  | Identifier, unique within the measure | 0..1 | Identifier |  |  |
| `Measure.supplementalData.modifierExtension` | `Measure.supplementalData.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Measure.supplementalData.path` | `Measure.supplementalData.path` | `path` |  | Path to the supplemental data element | 0..1 | string |  |  |
| `Measure.supplementalData.usage` | `Measure.supplementalData.usage` | `usage` |  | supplemental-data \| risk-adjustment-factor | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/measure-data-usage` |
| `Measure.text` | `Measure.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Measure.title` | `Measure.title` | `title` |  | Name for this measure (human friendly) | 0..1 | string |  |  |
| `Measure.topic` | `Measure.topic` | `topic` |  | E.g. Education, Treatment, Assessment, etc | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/definition-topic` |
| `Measure.type` | `Measure.type` | `type` |  | process \| outcome \| structure \| patient-reported-outcome \| composite | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/measure-type` |
| `Measure.url` | `Measure.url` | `url` |  | Logical URI to reference this measure (globally unique) | 0..1 | uri |  |  |
| `Measure.usage` | `Measure.usage` | `usage` |  | Describes the clinical usage of the measure | 0..1 | string |  |  |
| `Measure.useContext` | `Measure.useContext` | `useContext` |  | Context the content is intended to support | 0..* | UsageContext |  |  |
| `Measure.version` | `Measure.version` | `version` |  | Business version of the measure | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [Measure](/docs/R3/Resources/Measure.md)<br/> `http://hl7.org/fhir/StructureDefinition/Measure\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `476`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `670`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Measure](/docs/R4/Resources/Measure.md)<br/> `http://hl7.org/fhir/StructureDefinition/Measure\|4.0.1` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1529`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1530`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Measure](/docs/R4B/Resources/Measure.md)<br/> `http://hl7.org/fhir/StructureDefinition/Measure\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1000`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1229`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Measure](/docs/R5/Resources/Measure.md)<br/> `http://hl7.org/fhir/StructureDefinition/Measure\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Measure from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | R3 Measure| Relationship | [R4 Measure](/docs/R4/Resources/Measure.md)| Relationship | [R4B Measure](/docs/R4B/Resources/Measure.md)| Relationship | [R5 Measure](/docs/R5/Resources/Measure.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | **`Measure`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15400)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15401)| `Measure`| _Equivalent_<br/>(29080/29081)| `Measure`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(43955)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(43956)| `Measure`
| | | **`Measure.id`**| _Equivalent_<br/>(15402/15403)| `Measure.id`| _Equivalent_<br/>(29082/29083)| `Measure.id`| _Equivalent_<br/>(43957/43958)| `Measure.id`
| | | **`Measure.meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15404)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15405)| `Measure.meta`| _Equivalent_<br/>(29084/29085)| `Measure.meta`| _Equivalent_<br/>(43959/43960)| `Measure.meta`
| | | **`Measure.implicitRules`**| _Equivalent_<br/>(15406/15407)| `Measure.implicitRules`| _Equivalent_<br/>(29086/29087)| `Measure.implicitRules`| _Equivalent_<br/>(43961/43962)| `Measure.implicitRules`
| | | **`Measure.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15408)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(15409)| `Measure.language`| _Equivalent_<br/>(29088/29089)| `Measure.language`| _Equivalent_<br/>(43963/43964)| `Measure.language`
| | | **`Measure.text`**| _Equivalent_<br/>(15410/15411)| `Measure.text`| _Equivalent_<br/>(29090/29091)| `Measure.text`| _Equivalent_<br/>(43965/43966)| `Measure.text`
| | | **`Measure.contained`**| _Equivalent_<br/>(15412/15413)| `Measure.contained`| _Equivalent_<br/>(29092/29093)| `Measure.contained`| _Equivalent_<br/>(43967/43968)| `Measure.contained`
| | | **`Measure.extension`**| _Equivalent_<br/>(15414/15415)| `Measure.extension`| _Equivalent_<br/>(29094/29095)| `Measure.extension`| _Equivalent_<br/>(43969/43970)| `Measure.extension`
| | | **`Measure.modifierExtension`**| _Equivalent_<br/>(15416/15417)| `Measure.modifierExtension`| _Equivalent_<br/>(29096/29097)| `Measure.modifierExtension`| _Equivalent_<br/>(43971/43972)| `Measure.modifierExtension`
| | | **`Measure.url`**| _Equivalent_<br/>(15418/15419)| `Measure.url`| _Equivalent_<br/>(29098/29099)| `Measure.url`| _Equivalent_<br/>(43973/43974)| `Measure.url`
| | | **`Measure.identifier`**| _Equivalent_<br/>(15420/15421)| `Measure.identifier`| _Equivalent_<br/>(29100/29101)| `Measure.identifier`| _Equivalent_<br/>(43975/43976)| `Measure.identifier`
| | | **`Measure.version`**| _Equivalent_<br/>(15422/15423)| `Measure.version`| _Equivalent_<br/>(29102/29103)| `Measure.version`| _Equivalent_<br/>(43977/43978)| `Measure.version`
| | | **`Measure.name`**| _Equivalent_<br/>(15424/15425)| `Measure.name`| _Equivalent_<br/>(29104/29105)| `Measure.name`| _Equivalent_<br/>(43979/43980)| `Measure.name`
| | | **`Measure.title`**| _Equivalent_<br/>(15426/15427)| `Measure.title`| _Equivalent_<br/>(29106/29107)| `Measure.title`| _Equivalent_<br/>(43981/43982)| `Measure.title`
| | | **`Measure.status`**| _Equivalent_<br/>(15428/15429)| `Measure.status`| _Equivalent_<br/>(29110/29111)| `Measure.status`| _Equivalent_<br/>(43985/43986)| `Measure.status`
| | | **`Measure.experimental`**| _Equivalent_<br/>(15430/15431)| `Measure.experimental`| _Equivalent_<br/>(29112/29113)| `Measure.experimental`| _Equivalent_<br/>(43987/43988)| `Measure.experimental`
| | | **`Measure.date`**| _Equivalent_<br/>(15432/15433)| `Measure.date`| _Equivalent_<br/>(29116/29117)| `Measure.date`| _Equivalent_<br/>(43991/43992)| `Measure.date`
| | | **`Measure.publisher`**| _Equivalent_<br/>(15434/15435)| `Measure.publisher`| _Equivalent_<br/>(29118/29119)| `Measure.publisher`| _Equivalent_<br/>(43993/43994)| `Measure.publisher`
| | | **`Measure.description`**| _Equivalent_<br/>(15436/15437)| `Measure.description`| _Equivalent_<br/>(29122/29123)| `Measure.description`| _Equivalent_<br/>(43997/43998)| `Measure.description`
| | | **`Measure.purpose`**| _Equivalent_<br/>(15438/15439)| `Measure.purpose`| _Equivalent_<br/>(29128/29129)| `Measure.purpose`| _Equivalent_<br/>(44003/44004)| `Measure.purpose`
| | | **`Measure.usage`**| _Equivalent_<br/>(15440/15441)| `Measure.usage`| _Equivalent_<br/>(29130/29131)| `Measure.usage`| _Equivalent_<br/>(44005/44006)| `Measure.usage`
| | | **`Measure.approvalDate`**| _Equivalent_<br/>(15442/15443)| `Measure.approvalDate`| _Equivalent_<br/>(29134/29135)| `Measure.approvalDate`| _Equivalent_<br/>(44009/44010)| `Measure.approvalDate`
| | | **`Measure.lastReviewDate`**| _Equivalent_<br/>(15444/15445)| `Measure.lastReviewDate`| _Equivalent_<br/>(29136/29137)| `Measure.lastReviewDate`| _Equivalent_<br/>(44011/44012)| `Measure.lastReviewDate`
| | | **`Measure.effectivePeriod`**| _Equivalent_<br/>(15446/15447)| `Measure.effectivePeriod`| _Equivalent_<br/>(29138/29139)| `Measure.effectivePeriod`| _Equivalent_<br/>(44013/44014)| `Measure.effectivePeriod`
| | | **`Measure.useContext`**| _Equivalent_<br/>(15448/15449)| `Measure.useContext`| _Equivalent_<br/>(29124/29125)| `Measure.useContext`| _Equivalent_<br/>(43999/44000)| `Measure.useContext`
| | | **`Measure.jurisdiction`**| _Equivalent_<br/>(15450/15451)| `Measure.jurisdiction`| _Equivalent_<br/>(29126/29127)| `Measure.jurisdiction`| _Equivalent_<br/>(44001/44002)| `Measure.jurisdiction`
| | | **`Measure.topic`**| _Equivalent_<br/>(15452/15453)| `Measure.topic`| _Equivalent_<br/>(29140/29141)| `Measure.topic`| _Equivalent_<br/>(44015/44016)| `Measure.topic`
| | | **`Measure.contributor`**| →→→→ _Equivalent_ →→→→ <br/>(29067)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1585)| `base64Binary`| | | | | 
| | | **`Measure.contributor`**| →→→→ _Equivalent_ →→→→ <br/>(29067)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1585)| `Measure.author`| _Equivalent_<br/>(29142/29143)| `Measure.author`| _Equivalent_<br/>(44017/44018)| `Measure.author`
| | | **`Measure.contributor`**| →→→→ _Equivalent_ →→→→ <br/>(29067)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1585)| `Measure.editor`| _Equivalent_<br/>(29144/29145)| `Measure.editor`| _Equivalent_<br/>(44019/44020)| `Measure.editor`
| | | **`Measure.contributor`**| →→→→ _Equivalent_ →→→→ <br/>(29067)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1585)| `Measure.reviewer`| _Equivalent_<br/>(29146/29147)| `Measure.reviewer`| _Equivalent_<br/>(44021/44022)| `Measure.reviewer`
| | | **`Measure.contributor`**| →→→→ _Equivalent_ →→→→ <br/>(29067)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1585)| `Measure.endorser`| _Equivalent_<br/>(29148/29149)| `Measure.endorser`| _Equivalent_<br/>(44023/44024)| `Measure.endorser`
| | | **`Measure.contact`**| _Equivalent_<br/>(15454/15455)| `Measure.contact`| _Equivalent_<br/>(29120/29121)| `Measure.contact`| _Equivalent_<br/>(43995/43996)| `Measure.contact`
| | | **`Measure.copyright`**| _Equivalent_<br/>(15456/15457)| `Measure.copyright`| _Equivalent_<br/>(29132/29133)| `Measure.copyright`| _Equivalent_<br/>(44007/44008)| `Measure.copyright`
| | | **`Measure.relatedArtifact`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15458)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15459)| `Measure.relatedArtifact`| _Equivalent_<br/>(29150/29151)| `Measure.relatedArtifact`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(44025)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(44026)| `Measure.relatedArtifact`
| | | **`Measure.library`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(15460)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15461)| `Measure.library`| _Equivalent_<br/>(29152/29153)| `Measure.library`| _Equivalent_<br/>(44027/44028)| `Measure.library`
| | | **`Measure.disclaimer`**| _Equivalent_<br/>(15462/15463)| `Measure.disclaimer`| _Equivalent_<br/>(29154/29155)| `Measure.disclaimer`| _Equivalent_<br/>(44029/44030)| `Measure.disclaimer`
| | | **`Measure.scoring`**| _Equivalent_<br/>(15464/15465)| `Measure.scoring`| _Equivalent_<br/>(29156/29157)| `Measure.scoring`| _Equivalent_<br/>(44031/44032)| `Measure.scoring`
| | | **`Measure.compositeScoring`**| _Equivalent_<br/>(15466/15467)| `Measure.compositeScoring`| _Equivalent_<br/>(29158/29159)| `Measure.compositeScoring`| _Equivalent_<br/>(44033/44034)| `Measure.compositeScoring`
| | | **`Measure.type`**| _Equivalent_<br/>(15468/15469)| `Measure.type`| _Equivalent_<br/>(29160/29161)| `Measure.type`| _Equivalent_<br/>(44035/44036)| `Measure.type`
| | | **`Measure.riskAdjustment`**| _Equivalent_<br/>(15470/15471)| `Measure.riskAdjustment`| _Equivalent_<br/>(29162/29163)| `Measure.riskAdjustment`| _Equivalent_<br/>(44037/44038)| `Measure.riskAdjustment`
| | | **`Measure.rateAggregation`**| _Equivalent_<br/>(15472/15473)| `Measure.rateAggregation`| _Equivalent_<br/>(29164/29165)| `Measure.rateAggregation`| _Equivalent_<br/>(44039/44040)| `Measure.rateAggregation`
| | | **`Measure.rationale`**| _Equivalent_<br/>(15474/15475)| `Measure.rationale`| _Equivalent_<br/>(29166/29167)| `Measure.rationale`| _Equivalent_<br/>(44041/44042)| `Measure.rationale`
| | | **`Measure.clinicalRecommendationStatement`**| _Equivalent_<br/>(15476/15477)| `Measure.clinicalRecommendationStatement`| _Equivalent_<br/>(29168/29169)| `Measure.clinicalRecommendationStatement`| _Equivalent_<br/>(44043/44044)| `Measure.clinicalRecommendationStatement`
| | | **`Measure.improvementNotation`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15478)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(15479)| `Measure.improvementNotation`| _Equivalent_<br/>(29170/29171)| `Measure.improvementNotation`| _Equivalent_<br/>(44045/44046)| `Measure.improvementNotation`
| | | **`Measure.definition`**| _Equivalent_<br/>(15480/15481)| `Measure.definition`| _Equivalent_<br/>(29172/29173)| `Measure.definition`| | | 
| | | **`Measure.guidance`**| _Equivalent_<br/>(15482/15483)| `Measure.guidance`| _Equivalent_<br/>(29174/29175)| `Measure.guidance`| _Equivalent_<br/>(44048/44049)| `Measure.guidance`
| | | **`Measure.set`**| | | | | | | 
| | | **`Measure.group`**| _Equivalent_<br/>(15484/15485)| `Measure.group`| _Equivalent_<br/>(29176/29177)| `Measure.group`| _Equivalent_<br/>(44050/44051)| `Measure.group`
| | | **`Measure.group.id`**| _Equivalent_<br/>(15486/15487)| `Measure.group.id`| _Equivalent_<br/>(29178/29179)| `Measure.group.id`| _Equivalent_<br/>(44052/44053)| `Measure.group.id`
| | | **`Measure.group.extension`**| _Equivalent_<br/>(15488/15489)| `Measure.group.extension`| _Equivalent_<br/>(29180/29181)| `Measure.group.extension`| _Equivalent_<br/>(44054/44055)| `Measure.group.extension`
| | | **`Measure.group.modifierExtension`**| _Equivalent_<br/>(15490/15491)| `Measure.group.modifierExtension`| _Equivalent_<br/>(29182/29183)| `Measure.group.modifierExtension`| _Equivalent_<br/>(44056/44057)| `Measure.group.modifierExtension`
| | | **`Measure.group.identifier`**| →→→→ _Equivalent_ →→→→ <br/>(29068)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1586)| `base64Binary`| | | | | 
| | | **`Measure.group.identifier`**| →→→→ _Equivalent_ →→→→ <br/>(29068)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1586)| `Measure.group.code`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(29184)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(29185)| `Measure.group.code`| _Equivalent_<br/>(44058/44059)| `Measure.group.code`
| | | **`Measure.group.name`**| | | | | | | 
| | | **`Measure.group.description`**| _Equivalent_<br/>(15492/15493)| `Measure.group.description`| _Equivalent_<br/>(29186/29187)| `Measure.group.description`| _Equivalent_<br/>(44060/44061)| `Measure.group.description`
| | | **`Measure.group.population`**| _Equivalent_<br/>(15494/15495)| `Measure.group.population`| _Equivalent_<br/>(29188/29189)| `Measure.group.population`| _Equivalent_<br/>(44062/44063)| `Measure.group.population`
| | | **`Measure.group.population.id`**| _Equivalent_<br/>(15496/15497)| `Measure.group.population.id`| _Equivalent_<br/>(29190/29191)| `Measure.group.population.id`| _Equivalent_<br/>(44064/44065)| `Measure.group.population.id`
| | | **`Measure.group.population.extension`**| _Equivalent_<br/>(15498/15499)| `Measure.group.population.extension`| _Equivalent_<br/>(29192/29193)| `Measure.group.population.extension`| _Equivalent_<br/>(44066/44067)| `Measure.group.population.extension`
| | | **`Measure.group.population.modifierExtension`**| _Equivalent_<br/>(15500/15501)| `Measure.group.population.modifierExtension`| _Equivalent_<br/>(29194/29195)| `Measure.group.population.modifierExtension`| _Equivalent_<br/>(44068/44069)| `Measure.group.population.modifierExtension`
| | | **`Measure.group.population.identifier`**| | | | | | | 
| | | **`Measure.group.population.code`**| _Equivalent_<br/>(15502/15503)| `Measure.group.population.code`| _Equivalent_<br/>(29196/29197)| `Measure.group.population.code`| _Equivalent_<br/>(44070/44071)| `Measure.group.population.code`
| | | **`Measure.group.population.name`**| | | | | | | 
| | | **`Measure.group.population.description`**| _Equivalent_<br/>(15504/15505)| `Measure.group.population.description`| _Equivalent_<br/>(29198/29199)| `Measure.group.population.description`| _Equivalent_<br/>(44072/44073)| `Measure.group.population.description`
| | | **`Measure.group.population.criteria`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(15506)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15507)| `Measure.group.population.criteria`| _Equivalent_<br/>(29200/29201)| `Measure.group.population.criteria`| →→→→ _Equivalent_ →→→→ <br/>(44074)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(44075)| `Measure.group.population.criteria`
| | | **`Measure.group.stratifier`**| _Equivalent_<br/>(15508/15509)| `Measure.group.stratifier`| _Equivalent_<br/>(29202/29203)| `Measure.group.stratifier`| _Equivalent_<br/>(44076/44077)| `Measure.group.stratifier`
| | | **`Measure.group.stratifier.id`**| _Equivalent_<br/>(15510/15511)| `Measure.group.stratifier.id`| _Equivalent_<br/>(29204/29205)| `Measure.group.stratifier.id`| _Equivalent_<br/>(44078/44079)| `Measure.group.stratifier.id`
| | | **`Measure.group.stratifier.extension`**| →→→→ _Equivalent_ →→→→ <br/>(15512)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15513)| `Measure.group.stratifier.extension`| _Equivalent_<br/>(29206/29207)| `Measure.group.stratifier.extension`| _Equivalent_<br/>(44080/44081)| `Measure.group.stratifier.extension`
| | | **`Measure.group.stratifier.modifierExtension`**| _Equivalent_<br/>(15514/15515)| `Measure.group.stratifier.modifierExtension`| _Equivalent_<br/>(29208/29209)| `Measure.group.stratifier.modifierExtension`| _Equivalent_<br/>(44082/44083)| `Measure.group.stratifier.modifierExtension`
| | | **`Measure.group.stratifier.identifier`**| →→→→ _Equivalent_ →→→→ <br/>(29069)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1587)| `base64Binary`| | | | | 
| | | **`Measure.group.stratifier.identifier`**| →→→→ _Equivalent_ →→→→ <br/>(29069)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1587)| `Measure.group.stratifier.code`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(29210)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(29211)| `Measure.group.stratifier.code`| _Equivalent_<br/>(44084/44085)| `Measure.group.stratifier.code`
| | | **`Measure.group.stratifier.criteria`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(15516)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15517)| `Measure.group.stratifier.criteria`| _Equivalent_<br/>(29214/29215)| `Measure.group.stratifier.criteria`| _Equivalent_<br/>(44088/44089)| `Measure.group.stratifier.criteria`
| | | **`Measure.group.stratifier.path`**| →→→→ _RelatedTo_ →→→→ <br/>(1154)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15518)| `Measure.group.stratifier.extension`| _Equivalent_<br/>(29206/29207)| `Measure.group.stratifier.extension`| _Equivalent_<br/>(44080/44081)| `Measure.group.stratifier.extension`
| | | **`Measure.supplementalData`**| _Equivalent_<br/>(15519/15520)| `Measure.supplementalData`| _Equivalent_<br/>(29230/29231)| `Measure.supplementalData`| _Equivalent_<br/>(44104/44105)| `Measure.supplementalData`
| | | **`Measure.supplementalData.id`**| _Equivalent_<br/>(15521/15522)| `Measure.supplementalData.id`| _Equivalent_<br/>(29232/29233)| `Measure.supplementalData.id`| _Equivalent_<br/>(44106/44107)| `Measure.supplementalData.id`
| | | **`Measure.supplementalData.extension`**| →→→→ _Equivalent_ →→→→ <br/>(15523)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15524)| `Measure.supplementalData.extension`| _Equivalent_<br/>(29234/29235)| `Measure.supplementalData.extension`| _Equivalent_<br/>(44108/44109)| `Measure.supplementalData.extension`
| | | **`Measure.supplementalData.modifierExtension`**| _Equivalent_<br/>(15525/15526)| `Measure.supplementalData.modifierExtension`| _Equivalent_<br/>(29236/29237)| `Measure.supplementalData.modifierExtension`| _Equivalent_<br/>(44110/44111)| `Measure.supplementalData.modifierExtension`
| | | **`Measure.supplementalData.identifier`**| →→→→ _Equivalent_ →→→→ <br/>(29078)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1588)| `base64Binary`| | | | | 
| | | **`Measure.supplementalData.identifier`**| →→→→ _Equivalent_ →→→→ <br/>(29078)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1588)| `Measure.supplementalData.code`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(29238)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(29239)| `Measure.supplementalData.code`| _Equivalent_<br/>(44112/44113)| `Measure.supplementalData.code`
| | | **`Measure.supplementalData.usage`**| _Equivalent_<br/>(15527/15528)| `Measure.supplementalData.usage`| _Equivalent_<br/>(29240/29241)| `Measure.supplementalData.usage`| _Equivalent_<br/>(44114/44115)| `Measure.supplementalData.usage`
| | | **`Measure.supplementalData.criteria`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(15529)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15530)| `Measure.supplementalData.criteria`| _Equivalent_<br/>(29244/29245)| `Measure.supplementalData.criteria`| _Equivalent_<br/>(44118/44119)| `Measure.supplementalData.criteria`
| | | **`Measure.supplementalData.path`**| →→→→ _RelatedTo_ →→→→ <br/>(1157)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(15531)| `Measure.supplementalData.extension`| _Equivalent_<br/>(29234/29235)| `Measure.supplementalData.extension`| _Equivalent_<br/>(44108/44109)| `Measure.supplementalData.extension`
| | | *75 of 75 elements used* | | *73 of 83 elements used* <br/>remaining elements:<br/>`Measure.group.stratifier.component`, `Measure.group.stratifier.component.code`, `Measure.group.stratifier.component.criteria`, `Measure.group.stratifier.component.description`, `Measure.group.stratifier.component.extension`, `Measure.group.stratifier.component.id`, `Measure.group.stratifier.component.modifierExtension`, `Measure.group.stratifier.description`, `Measure.subject[x]`, `Measure.subtitle`, `Measure.supplementalData.description`| | *72 of 83 elements used* <br/>remaining elements:<br/>`Measure.group.stratifier.component`, `Measure.group.stratifier.component.code`, `Measure.group.stratifier.component.criteria`, `Measure.group.stratifier.component.description`, `Measure.group.stratifier.component.extension`, `Measure.group.stratifier.component.id`, `Measure.group.stratifier.component.modifierExtension`, `Measure.group.stratifier.description`, `Measure.subject[x]`, `Measure.subtitle`, `Measure.supplementalData.description`| | *71 of 110 elements used* <br/>remaining elements:<br/>`Measure.basis`, `Measure.copyrightLabel`, `Measure.group.basis`, `Measure.group.improvementNotation`, `Measure.group.library`, `Measure.group.linkId`, `Measure.group.population.aggregateMethod`, `Measure.group.population.groupDefinition`, `Measure.group.population.inputPopulationId`, `Measure.group.population.linkId`, `Measure.group.rateAggregation`, `Measure.group.scoring`, `Measure.group.scoringUnit`, `Measure.group.stratifier.component`, `Measure.group.stratifier.component.code`, `Measure.group.stratifier.component.criteria`, `Measure.group.stratifier.component.description`, `Measure.group.stratifier.component.extension`, `Measure.group.stratifier.component.groupDefinition`, `Measure.group.stratifier.component.id`, `Measure.group.stratifier.component.linkId`, `Measure.group.stratifier.component.modifierExtension`, `Measure.group.stratifier.description`, `Measure.group.stratifier.groupDefinition`, `Measure.group.stratifier.linkId`, `Measure.group.subject[x]`, `Measure.group.type`, `Measure.scoringUnit`, `Measure.subject[x]`, `Measure.subtitle`, `Measure.supplementalData.description`, `Measure.supplementalData.linkId`, `Measure.term`, `Measure.term.code`, `Measure.term.definition`, `Measure.term.extension`, `Measure.term.id`, `Measure.term.modifierExtension`, `Measure.versionAlgorithm[x]`

