Comparison of 
Generated at Friday, April 4, 2025 2:59:02 PM

### Evidence

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Evidence |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Evidence` |
| Version | 5.0.0 |
| Description | The Evidence Resource provides a machine-interpretable expression of an evidence concept including the evidence variables (e.g., population, exposures/interventions, comparators, outcomes, measured variables, confounding variables), the statistics, and the certainty of this evidence. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2305` |
| Database Snapshot Count | `104` |
| Database Differential Count | `75` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Evidence` | `Evidence` | `Evidence` | Evidence | Single evidence bit | 0..* | Evidence |  |  |
| `Evidence.approvalDate` | `Evidence.approvalDate` | `approvalDate` | Evidence.approvalDate | When the summary was approved by publisher | 0..1 | date |  |  |
| `Evidence.assertion` | `Evidence.assertion` | `assertion` | Evidence.assertion | Declarative description of the Evidence | 0..1 | markdown |  |  |
| `Evidence.author` | `Evidence.author` | `author` | Evidence.author | Who authored the content | 0..* | ContactDetail |  |  |
| `Evidence.certainty` | `Evidence.certainty` | `certainty` | Evidence.certainty | Certainty or quality of the evidence | 0..* | BackboneElement |  |  |
| `Evidence.certainty.description` | `Evidence.certainty.description` | `description` | Evidence.certainty.description | Textual description of certainty | 0..1 | markdown |  |  |
| `Evidence.certainty.extension` | `Evidence.certainty.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Evidence.certainty.id` | `Evidence.certainty.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Evidence.certainty.modifierExtension` | `Evidence.certainty.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Evidence.certainty.note` | `Evidence.certainty.note` | `note` | Evidence.certainty.note | Footnotes and/or explanatory notes | 0..* | Annotation |  |  |
| `Evidence.certainty.rater` | `Evidence.certainty.rater` | `rater` | Evidence.certainty.rater | Individual or group who did the rating | 0..1 | string |  |  |
| `Evidence.certainty.rating` | `Evidence.certainty.rating` | `rating` | Evidence.certainty.rating | Assessment or judgement of the aspect | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/certainty-rating` |
| `Evidence.certainty.subcomponent` | `Evidence.certainty.subcomponent` | `subcomponent` | Evidence.certainty.subcomponent | A domain or subdomain of certainty | 0..* | Evidence.certainty |  |  |
| `Evidence.certainty.type` | `Evidence.certainty.type` | `type` | Evidence.certainty.type | Aspect of certainty being rated | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/certainty-type` |
| `Evidence.citeAs[x]` | `Evidence.citeAs[x]` | `citeAs[x]` | Evidence.citeAs[x] | Citation for this evidence | 0..1 | markdown, Reference(http://hl7.org/fhir/StructureDefinition/Citation) |  |  |
| `Evidence.contact` | `Evidence.contact` | `contact` | Evidence.contact | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `Evidence.contained` | `Evidence.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Evidence.copyright` | `Evidence.copyright` | `copyright` | Evidence.copyright | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `Evidence.copyrightLabel` | `Evidence.copyrightLabel` | `copyrightLabel` | Evidence.copyrightLabel | Copyright holder and year(s) | 0..1 | string |  |  |
| `Evidence.date` | `Evidence.date` | `date` | Evidence.date | Date last changed | 0..1 | dateTime |  |  |
| `Evidence.description` | `Evidence.description` | `description` | Evidence.description | Description of the particular summary | 0..1 | markdown |  |  |
| `Evidence.editor` | `Evidence.editor` | `editor` | Evidence.editor | Who edited the content | 0..* | ContactDetail |  |  |
| `Evidence.endorser` | `Evidence.endorser` | `endorser` | Evidence.endorser | Who endorsed the content | 0..* | ContactDetail |  |  |
| `Evidence.experimental` | `Evidence.experimental` | `experimental` | Evidence.experimental | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `Evidence.extension` | `Evidence.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Evidence.id` | `Evidence.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Evidence.identifier` | `Evidence.identifier` | `identifier` | Evidence.identifier | Additional identifier for the summary | 0..* | Identifier |  |  |
| `Evidence.implicitRules` | `Evidence.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Evidence.language` | `Evidence.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `Evidence.lastReviewDate` | `Evidence.lastReviewDate` | `lastReviewDate` | Evidence.lastReviewDate | When the summary was last reviewed by the publisher | 0..1 | date |  |  |
| `Evidence.meta` | `Evidence.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Evidence.modifierExtension` | `Evidence.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Evidence.name` | `Evidence.name` | `name` | Evidence.name | Name for this summary (machine friendly) | 0..1 | string |  |  |
| `Evidence.note` | `Evidence.note` | `note` | Evidence.note | Footnotes and/or explanatory notes | 0..* | Annotation |  |  |
| `Evidence.publisher` | `Evidence.publisher` | `publisher` | Evidence.publisher | Name of the publisher/steward (organization or individual) | 0..1 | string |  |  |
| `Evidence.purpose` | `Evidence.purpose` | `purpose` | Evidence.purpose | Why this Evidence is defined | 0..1 | markdown |  |  |
| `Evidence.relatedArtifact` | `Evidence.relatedArtifact` | `relatedArtifact` | Evidence.relatedArtifact | Link or citation to artifact associated with the summary | 0..* | RelatedArtifact |  |  |
| `Evidence.reviewer` | `Evidence.reviewer` | `reviewer` | Evidence.reviewer | Who reviewed the content | 0..* | ContactDetail |  |  |
| `Evidence.statistic` | `Evidence.statistic` | `statistic` | Evidence.statistic | Values and parameters for a single statistic | 0..* | BackboneElement |  |  |
| `Evidence.statistic.attributeEstimate` | `Evidence.statistic.attributeEstimate` | `attributeEstimate` | Evidence.statistic.attributeEstimate | An attribute of the Statistic | 0..* | BackboneElement |  |  |
| `Evidence.statistic.attributeEstimate.attributeEstimate` | `Evidence.statistic.attributeEstimate.attributeEstimate` | `attributeEstimate` | Evidence.statistic.attributeEstimate.attributeEstimate | A nested attribute estimate; which is the attribute estimate of an attribute estimate | 0..* | Evidence.statistic.attributeEstimate |  |  |
| `Evidence.statistic.attributeEstimate.description` | `Evidence.statistic.attributeEstimate.description` | `description` | Evidence.statistic.attributeEstimate.description | Textual description of the attribute estimate | 0..1 | markdown |  |  |
| `Evidence.statistic.attributeEstimate.extension` | `Evidence.statistic.attributeEstimate.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Evidence.statistic.attributeEstimate.id` | `Evidence.statistic.attributeEstimate.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Evidence.statistic.attributeEstimate.level` | `Evidence.statistic.attributeEstimate.level` | `level` | Evidence.statistic.attributeEstimate.level | Level of confidence interval, e.g., 0.95 for 95% confidence interval | 0..1 | decimal |  |  |
| `Evidence.statistic.attributeEstimate.modifierExtension` | `Evidence.statistic.attributeEstimate.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Evidence.statistic.attributeEstimate.note` | `Evidence.statistic.attributeEstimate.note` | `note` | Evidence.statistic.attributeEstimate.note | Footnote or explanatory note about the estimate | 0..* | Annotation |  |  |
| `Evidence.statistic.attributeEstimate.quantity` | `Evidence.statistic.attributeEstimate.quantity` | `quantity` | Evidence.statistic.attributeEstimate.quantity | The singular quantity of the attribute estimate, for attribute estimates represented as single values; also used to report unit of measure | 0..1 | Quantity |  |  |
| `Evidence.statistic.attributeEstimate.range` | `Evidence.statistic.attributeEstimate.range` | `range` | Evidence.statistic.attributeEstimate.range | Lower and upper bound values of the attribute estimate | 0..1 | Range |  |  |
| `Evidence.statistic.attributeEstimate.type` | `Evidence.statistic.attributeEstimate.type` | `type` | Evidence.statistic.attributeEstimate.type | The type of attribute estimate, e.g., confidence interval or p value | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/attribute-estimate-type` |
| `Evidence.statistic.category` | `Evidence.statistic.category` | `category` | Evidence.statistic.category | Associated category for categorical variable | 0..1 | CodeableConcept |  |  |
| `Evidence.statistic.description` | `Evidence.statistic.description` | `description` | Evidence.statistic.description | Description of content | 0..1 | markdown |  |  |
| `Evidence.statistic.extension` | `Evidence.statistic.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Evidence.statistic.id` | `Evidence.statistic.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Evidence.statistic.modelCharacteristic` | `Evidence.statistic.modelCharacteristic` | `modelCharacteristic` | Evidence.statistic.modelCharacteristic | An aspect of the statistical model | 0..* | BackboneElement |  |  |
| `Evidence.statistic.modelCharacteristic.attributeEstimate` | `Evidence.statistic.modelCharacteristic.attributeEstimate` | `attributeEstimate` | Evidence.statistic.modelCharacteristic.attributeEstimate | An attribute of the statistic used as a model characteristic | 0..* | Evidence.statistic.attributeEstimate |  |  |
| `Evidence.statistic.modelCharacteristic.code` | `Evidence.statistic.modelCharacteristic.code` | `code` | Evidence.statistic.modelCharacteristic.code | Model specification | 1..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/statistic-model-code` |
| `Evidence.statistic.modelCharacteristic.extension` | `Evidence.statistic.modelCharacteristic.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Evidence.statistic.modelCharacteristic.id` | `Evidence.statistic.modelCharacteristic.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Evidence.statistic.modelCharacteristic.modifierExtension` | `Evidence.statistic.modelCharacteristic.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Evidence.statistic.modelCharacteristic.value` | `Evidence.statistic.modelCharacteristic.value` | `value` | Evidence.statistic.modelCharacteristic.value | Numerical value to complete model specification | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `Evidence.statistic.modelCharacteristic.variable` | `Evidence.statistic.modelCharacteristic.variable` | `variable` | Evidence.statistic.modelCharacteristic.variable | A variable adjusted for in the adjusted analysis | 0..* | BackboneElement |  |  |
| `Evidence.statistic.modelCharacteristic.variable.extension` | `Evidence.statistic.modelCharacteristic.variable.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Evidence.statistic.modelCharacteristic.variable.handling` | `Evidence.statistic.modelCharacteristic.variable.handling` | `handling` | Evidence.statistic.modelCharacteristic.variable.handling | continuous \| dichotomous \| ordinal \| polychotomous | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/variable-handling|5.0.0` |
| `Evidence.statistic.modelCharacteristic.variable.id` | `Evidence.statistic.modelCharacteristic.variable.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Evidence.statistic.modelCharacteristic.variable.modifierExtension` | `Evidence.statistic.modelCharacteristic.variable.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Evidence.statistic.modelCharacteristic.variable.valueCategory` | `Evidence.statistic.modelCharacteristic.variable.valueCategory` | `valueCategory` | Evidence.statistic.modelCharacteristic.variable.valueCategory | Description for grouping of ordinal or polychotomous variables | 0..* | CodeableConcept |  |  |
| `Evidence.statistic.modelCharacteristic.variable.valueQuantity` | `Evidence.statistic.modelCharacteristic.variable.valueQuantity` | `valueQuantity` | Evidence.statistic.modelCharacteristic.variable.valueQuantity | Discrete value for grouping of ordinal or polychotomous variables | 0..* | Quantity |  |  |
| `Evidence.statistic.modelCharacteristic.variable.valueRange` | `Evidence.statistic.modelCharacteristic.variable.valueRange` | `valueRange` | Evidence.statistic.modelCharacteristic.variable.valueRange | Range of values for grouping of ordinal or polychotomous variables | 0..* | Range |  |  |
| `Evidence.statistic.modelCharacteristic.variable.variableDefinition` | `Evidence.statistic.modelCharacteristic.variable.variableDefinition` | `variableDefinition` | Evidence.statistic.modelCharacteristic.variable.variableDefinition | Description of the variable | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/EvidenceVariable), Reference(http://hl7.org/fhir/StructureDefinition/Group) |  |  |
| `Evidence.statistic.modifierExtension` | `Evidence.statistic.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Evidence.statistic.note` | `Evidence.statistic.note` | `note` | Evidence.statistic.note | Footnotes and/or explanatory notes | 0..* | Annotation |  |  |
| `Evidence.statistic.numberAffected` | `Evidence.statistic.numberAffected` | `numberAffected` | Evidence.statistic.numberAffected | The number of participants affected | 0..1 | unsignedInt |  |  |
| `Evidence.statistic.numberOfEvents` | `Evidence.statistic.numberOfEvents` | `numberOfEvents` | Evidence.statistic.numberOfEvents | The number of events associated with the statistic | 0..1 | unsignedInt |  |  |
| `Evidence.statistic.quantity` | `Evidence.statistic.quantity` | `quantity` | Evidence.statistic.quantity | Statistic value | 0..1 | Quantity |  |  |
| `Evidence.statistic.sampleSize` | `Evidence.statistic.sampleSize` | `sampleSize` | Evidence.statistic.sampleSize | Number of samples in the statistic | 0..1 | BackboneElement |  |  |
| `Evidence.statistic.sampleSize.description` | `Evidence.statistic.sampleSize.description` | `description` | Evidence.statistic.sampleSize.description | Textual description of sample size for statistic | 0..1 | markdown |  |  |
| `Evidence.statistic.sampleSize.extension` | `Evidence.statistic.sampleSize.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Evidence.statistic.sampleSize.id` | `Evidence.statistic.sampleSize.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Evidence.statistic.sampleSize.knownDataCount` | `Evidence.statistic.sampleSize.knownDataCount` | `knownDataCount` | Evidence.statistic.sampleSize.knownDataCount | Number of participants with known results for measured variables | 0..1 | unsignedInt |  |  |
| `Evidence.statistic.sampleSize.modifierExtension` | `Evidence.statistic.sampleSize.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Evidence.statistic.sampleSize.note` | `Evidence.statistic.sampleSize.note` | `note` | Evidence.statistic.sampleSize.note | Footnote or explanatory note about the sample size | 0..* | Annotation |  |  |
| `Evidence.statistic.sampleSize.numberOfParticipants` | `Evidence.statistic.sampleSize.numberOfParticipants` | `numberOfParticipants` | Evidence.statistic.sampleSize.numberOfParticipants | Cumulative number of participants | 0..1 | unsignedInt |  |  |
| `Evidence.statistic.sampleSize.numberOfStudies` | `Evidence.statistic.sampleSize.numberOfStudies` | `numberOfStudies` | Evidence.statistic.sampleSize.numberOfStudies | Number of contributing studies | 0..1 | unsignedInt |  |  |
| `Evidence.statistic.statisticType` | `Evidence.statistic.statisticType` | `statisticType` | Evidence.statistic.statisticType | Type of statistic, e.g., relative risk | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/statistic-type` |
| `Evidence.status` | `Evidence.status` | `status` | Evidence.status | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status|5.0.0` |
| `Evidence.studyDesign` | `Evidence.studyDesign` | `studyDesign` | Evidence.studyDesign | The design of the study that produced this evidence | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/study-design` |
| `Evidence.synthesisType` | `Evidence.synthesisType` | `synthesisType` | Evidence.synthesisType | The method to combine studies | 0..1 | CodeableConcept | `Extensible` | `http://terminology.hl7.org/ValueSet/synthesis-type` |
| `Evidence.text` | `Evidence.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Evidence.title` | `Evidence.title` | `title` | Evidence.title | Name for this summary (human friendly) | 0..1 | string |  |  |
| `Evidence.url` | `Evidence.url` | `url` | Evidence.url | Canonical identifier for this evidence, represented as a globally unique URI | 0..1 | uri |  |  |
| `Evidence.useContext` | `Evidence.useContext` | `useContext` | Evidence.useContext | The context that the content is intended to support | 0..* | UsageContext |  |  |
| `Evidence.variableDefinition` | `Evidence.variableDefinition` | `variableDefinition` | Evidence.variableDefinition | Evidence variable such as population, exposure, or outcome | 1..* | BackboneElement |  |  |
| `Evidence.variableDefinition.description` | `Evidence.variableDefinition.description` | `description` | Evidence.variableDefinition.description | A text description or summary of the variable | 0..1 | markdown |  |  |
| `Evidence.variableDefinition.directnessMatch` | `Evidence.variableDefinition.directnessMatch` | `directnessMatch` | Evidence.variableDefinition.directnessMatch | low \| moderate \| high \| exact | 0..1 | CodeableConcept | `Extensible` | `http://terminology.hl7.org/ValueSet/directness` |
| `Evidence.variableDefinition.extension` | `Evidence.variableDefinition.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Evidence.variableDefinition.id` | `Evidence.variableDefinition.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Evidence.variableDefinition.intended` | `Evidence.variableDefinition.intended` | `intended` | Evidence.variableDefinition.intended | Definition of the intended variable related to the Evidence | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/EvidenceVariable), Reference(http://hl7.org/fhir/StructureDefinition/Group) |  |  |
| `Evidence.variableDefinition.modifierExtension` | `Evidence.variableDefinition.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Evidence.variableDefinition.note` | `Evidence.variableDefinition.note` | `note` | Evidence.variableDefinition.note | Footnotes and/or explanatory notes | 0..* | Annotation |  |  |
| `Evidence.variableDefinition.observed` | `Evidence.variableDefinition.observed` | `observed` | Evidence.variableDefinition.observed | Definition of the actual variable related to the statistic(s) | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/EvidenceVariable), Reference(http://hl7.org/fhir/StructureDefinition/Group) |  |  |
| `Evidence.variableDefinition.variableRole` | `Evidence.variableDefinition.variableRole` | `variableRole` | Evidence.variableDefinition.variableRole | population \| subpopulation \| exposure \| referenceExposure \| measuredVariable \| confounder | 1..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/variable-role` |
| `Evidence.version` | `Evidence.version` | `version` | Evidence.version | Business version of this summary | 0..1 | string |  |  |
| `Evidence.versionAlgorithm[x]` | `Evidence.versionAlgorithm[x]` | `versionAlgorithm[x]` | Evidence.versionAlgorithm[x] | How to compare versions | 0..1 | Coding, string | `Extensible` | `http://hl7.org/fhir/ValueSet/version-algorithm` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [Evidence](/docs/R4/Resources/Evidence.md)<br/> `http://hl7.org/fhir/StructureDefinition/Evidence\|4.0.1` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1485`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1486`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Evidence](/docs/R4B/Resources/Evidence.md)<br/> `http://hl7.org/fhir/StructureDefinition/Evidence\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `975`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1204`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Evidence](/docs/R5/Resources/Evidence.md)<br/> `http://hl7.org/fhir/StructureDefinition/Evidence\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Evidence from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | [R4 Evidence](/docs/R4/Resources/Evidence.md)| Relationship | [R4B Evidence](/docs/R4B/Resources/Evidence.md)| Relationship | R5 Evidence
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `Evidence`| _Equivalent_<br/>(26540/26541)| `Evidence`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(41342)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(41343)| **`Evidence`**
| | | | | `Evidence.id`| _Equivalent_<br/>(26542/26543)| `Evidence.id`| _Equivalent_<br/>(41344/41345)| **`Evidence.id`**
| | | | | `Evidence.meta`| _Equivalent_<br/>(26544/26545)| `Evidence.meta`| _Equivalent_<br/>(41346/41347)| **`Evidence.meta`**
| | | | | `Evidence.implicitRules`| _Equivalent_<br/>(26546/26547)| `Evidence.implicitRules`| _Equivalent_<br/>(41348/41349)| **`Evidence.implicitRules`**
| | | | | `Evidence.language`| _Equivalent_<br/>(26548/26549)| `Evidence.language`| _Equivalent_<br/>(41350/41351)| **`Evidence.language`**
| | | | | `Evidence.text`| _Equivalent_<br/>(26550/26551)| `Evidence.text`| _Equivalent_<br/>(41352/41353)| **`Evidence.text`**
| | | | | `Evidence.contained`| _Equivalent_<br/>(26552/26553)| `Evidence.contained`| _Equivalent_<br/>(41354/41355)| **`Evidence.contained`**
| | | | | `Evidence.extension`| _Equivalent_<br/>(26554/26555)| `Evidence.extension`| _Equivalent_<br/>(41356/41357)| **`Evidence.extension`**
| | | | | `Evidence.modifierExtension`| _Equivalent_<br/>(26556/26557)| `Evidence.modifierExtension`| _Equivalent_<br/>(41358/41359)| **`Evidence.modifierExtension`**
| | | | | `Evidence.url`| _Equivalent_<br/>(26558/26559)| `Evidence.url`| _Equivalent_<br/>(41360/41361)| **`Evidence.url`**
| | | | | `Evidence.identifier`| _Equivalent_<br/>(26560/26561)| `Evidence.identifier`| _Equivalent_<br/>(41362/41363)| **`Evidence.identifier`**
| | | | | `Evidence.version`| _Equivalent_<br/>(26562/26563)| `Evidence.version`| _Equivalent_<br/>(41364/41365)| **`Evidence.version`**
| | | | | | | | | **`Evidence.versionAlgorithm[x]`**
| | | | | | | | | **`Evidence.name`**
| | | | | `Evidence.title`| _Equivalent_<br/>(26565/26566)| `Evidence.title`| _Equivalent_<br/>(41366/41367)| **`Evidence.title`**
| | | | | | | `Evidence.citeAs[x]`| _Equivalent_<br/>(41368/41369)| **`Evidence.citeAs[x]`**
| | | | | `Evidence.status`| _Equivalent_<br/>(26569/26570)| `Evidence.status`| _Equivalent_<br/>(41370/41371)| **`Evidence.status`**
| | | | | | | | | **`Evidence.experimental`**
| | | | | `Evidence.date`| _Equivalent_<br/>(26571/26572)| `Evidence.date`| _Equivalent_<br/>(41372/41373)| **`Evidence.date`**
| | | | | `Evidence.approvalDate`| _Equivalent_<br/>(26585/26586)| `Evidence.approvalDate`| _Equivalent_<br/>(41376/41377)| **`Evidence.approvalDate`**
| | | | | `Evidence.lastReviewDate`| _Equivalent_<br/>(26587/26588)| `Evidence.lastReviewDate`| _Equivalent_<br/>(41378/41379)| **`Evidence.lastReviewDate`**
| | | | | `Evidence.publisher`| _Equivalent_<br/>(26573/26574)| `Evidence.publisher`| _Equivalent_<br/>(41380/41381)| **`Evidence.publisher`**
| | | | | `Evidence.contact`| _Equivalent_<br/>(26575/26576)| `Evidence.contact`| _Equivalent_<br/>(41382/41383)| **`Evidence.contact`**
| | | | | `Evidence.author`| _Equivalent_<br/>(26591/26592)| `Evidence.author`| _Equivalent_<br/>(41384/41385)| **`Evidence.author`**
| | | | | `Evidence.editor`| _Equivalent_<br/>(26593/26594)| `Evidence.editor`| _Equivalent_<br/>(41386/41387)| **`Evidence.editor`**
| | | | | `Evidence.reviewer`| _Equivalent_<br/>(26595/26596)| `Evidence.reviewer`| _Equivalent_<br/>(41388/41389)| **`Evidence.reviewer`**
| | | | | `Evidence.endorser`| _Equivalent_<br/>(26597/26598)| `Evidence.endorser`| _Equivalent_<br/>(41390/41391)| **`Evidence.endorser`**
| | | | | `Evidence.useContext`| _Equivalent_<br/>(26581/26582)| `Evidence.useContext`| _Equivalent_<br/>(41374/41375)| **`Evidence.useContext`**
| | | | | | | | | **`Evidence.purpose`**
| | | | | | | | | **`Evidence.copyright`**
| | | | | | | | | **`Evidence.copyrightLabel`**
| | | | | `Evidence.relatedArtifact`| _Equivalent_<br/>(26599/26600)| `Evidence.relatedArtifact`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(41392)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(41393)| **`Evidence.relatedArtifact`**
| | | | | `Evidence.description`| _Equivalent_<br/>(26577/26578)| `Evidence.description`| _Equivalent_<br/>(41394/41395)| **`Evidence.description`**
| | | | | | | `Evidence.assertion`| _Equivalent_<br/>(41396/41397)| **`Evidence.assertion`**
| | | | | `Evidence.note`| _Equivalent_<br/>(26579/26580)| `Evidence.note`| _Equivalent_<br/>(41398/41399)| **`Evidence.note`**
| | | | | | | `Evidence.variableDefinition`| _Equivalent_<br/>(41400/41401)| **`Evidence.variableDefinition`**
| | | | | | | `Evidence.variableDefinition.id`| _Equivalent_<br/>(41402/41403)| **`Evidence.variableDefinition.id`**
| | | | | | | `Evidence.variableDefinition.extension`| _Equivalent_<br/>(41404/41405)| **`Evidence.variableDefinition.extension`**
| | | | | | | `Evidence.variableDefinition.modifierExtension`| _Equivalent_<br/>(41406/41407)| **`Evidence.variableDefinition.modifierExtension`**
| | | | | | | `Evidence.variableDefinition.description`| _Equivalent_<br/>(41408/41409)| **`Evidence.variableDefinition.description`**
| | | | | | | `Evidence.variableDefinition.note`| _Equivalent_<br/>(41410/41411)| **`Evidence.variableDefinition.note`**
| | | | | | | `Evidence.variableDefinition.variableRole`| _Equivalent_<br/>(41412/41413)| **`Evidence.variableDefinition.variableRole`**
| | | | | | | `Evidence.variableDefinition.observed`| _Equivalent_<br/>(41414/41415)| **`Evidence.variableDefinition.observed`**
| | | | | | | `Evidence.variableDefinition.intended`| _Equivalent_<br/>(41416/41417)| **`Evidence.variableDefinition.intended`**
| | | | | | | `Evidence.variableDefinition.directnessMatch`| _Equivalent_<br/>(41418/41419)| **`Evidence.variableDefinition.directnessMatch`**
| | | | | | | `Evidence.synthesisType`| _Equivalent_<br/>(41420/41421)| **`Evidence.synthesisType`**
| | | | | | | | | **`Evidence.studyDesign`**
| | | | | | | `Evidence.statistic`| _Equivalent_<br/>(41423/41424)| **`Evidence.statistic`**
| | | | | | | `Evidence.statistic.id`| _Equivalent_<br/>(41425/41426)| **`Evidence.statistic.id`**
| | | | | | | `Evidence.statistic.extension`| _Equivalent_<br/>(41427/41428)| **`Evidence.statistic.extension`**
| | | | | | | `Evidence.statistic.modifierExtension`| _Equivalent_<br/>(41429/41430)| **`Evidence.statistic.modifierExtension`**
| | | | | | | `Evidence.statistic.description`| _Equivalent_<br/>(41431/41432)| **`Evidence.statistic.description`**
| | | | | | | `Evidence.statistic.note`| _Equivalent_<br/>(41433/41434)| **`Evidence.statistic.note`**
| | | | | | | `Evidence.statistic.statisticType`| _Equivalent_<br/>(41435/41436)| **`Evidence.statistic.statisticType`**
| | | | | | | `Evidence.statistic.category`| _Equivalent_<br/>(41437/41438)| **`Evidence.statistic.category`**
| | | | | | | `Evidence.statistic.quantity`| _Equivalent_<br/>(41439/41440)| **`Evidence.statistic.quantity`**
| | | | | | | `Evidence.statistic.numberOfEvents`| _Equivalent_<br/>(41441/41442)| **`Evidence.statistic.numberOfEvents`**
| | | | | | | `Evidence.statistic.numberAffected`| _Equivalent_<br/>(41443/41444)| **`Evidence.statistic.numberAffected`**
| | | | | | | `Evidence.statistic.sampleSize`| _Equivalent_<br/>(41445/41446)| **`Evidence.statistic.sampleSize`**
| | | | | | | `Evidence.statistic.sampleSize.id`| _Equivalent_<br/>(41447/41448)| **`Evidence.statistic.sampleSize.id`**
| | | | | | | `Evidence.statistic.sampleSize.extension`| _Equivalent_<br/>(41449/41450)| **`Evidence.statistic.sampleSize.extension`**
| | | | | | | `Evidence.statistic.sampleSize.modifierExtension`| _Equivalent_<br/>(41451/41452)| **`Evidence.statistic.sampleSize.modifierExtension`**
| | | | | | | `Evidence.statistic.sampleSize.description`| _Equivalent_<br/>(41453/41454)| **`Evidence.statistic.sampleSize.description`**
| | | | | | | `Evidence.statistic.sampleSize.note`| _Equivalent_<br/>(41455/41456)| **`Evidence.statistic.sampleSize.note`**
| | | | | | | `Evidence.statistic.sampleSize.numberOfStudies`| _Equivalent_<br/>(41457/41458)| **`Evidence.statistic.sampleSize.numberOfStudies`**
| | | | | | | `Evidence.statistic.sampleSize.numberOfParticipants`| _Equivalent_<br/>(41459/41460)| **`Evidence.statistic.sampleSize.numberOfParticipants`**
| | | | | | | `Evidence.statistic.sampleSize.knownDataCount`| _Equivalent_<br/>(41461/41462)| **`Evidence.statistic.sampleSize.knownDataCount`**
| | | | | | | `Evidence.statistic.attributeEstimate`| _Equivalent_<br/>(41463/41464)| **`Evidence.statistic.attributeEstimate`**
| | | | | | | `Evidence.statistic.attributeEstimate.id`| _Equivalent_<br/>(41465/41466)| **`Evidence.statistic.attributeEstimate.id`**
| | | | | | | `Evidence.statistic.attributeEstimate.extension`| _Equivalent_<br/>(41467/41468)| **`Evidence.statistic.attributeEstimate.extension`**
| | | | | | | `Evidence.statistic.attributeEstimate.modifierExtension`| _Equivalent_<br/>(41469/41470)| **`Evidence.statistic.attributeEstimate.modifierExtension`**
| | | | | | | `Evidence.statistic.attributeEstimate.description`| _Equivalent_<br/>(41471/41472)| **`Evidence.statistic.attributeEstimate.description`**
| | | | | | | `Evidence.statistic.attributeEstimate.note`| _Equivalent_<br/>(41473/41474)| **`Evidence.statistic.attributeEstimate.note`**
| | | | | | | `Evidence.statistic.attributeEstimate.type`| _Equivalent_<br/>(41475/41476)| **`Evidence.statistic.attributeEstimate.type`**
| | | | | | | `Evidence.statistic.attributeEstimate.quantity`| _Equivalent_<br/>(41477/41478)| **`Evidence.statistic.attributeEstimate.quantity`**
| | | | | | | `Evidence.statistic.attributeEstimate.level`| _Equivalent_<br/>(41479/41480)| **`Evidence.statistic.attributeEstimate.level`**
| | | | | | | `Evidence.statistic.attributeEstimate.range`| _Equivalent_<br/>(41481/41482)| **`Evidence.statistic.attributeEstimate.range`**
| | | | | | | `Evidence.statistic.attributeEstimate.attributeEstimate`| _Equivalent_<br/>(41483/41484)| **`Evidence.statistic.attributeEstimate.attributeEstimate`**
| | | | | | | `Evidence.statistic.modelCharacteristic`| _Equivalent_<br/>(41485/41486)| **`Evidence.statistic.modelCharacteristic`**
| | | | | | | `Evidence.statistic.modelCharacteristic.id`| _Equivalent_<br/>(41487/41488)| **`Evidence.statistic.modelCharacteristic.id`**
| | | | | | | `Evidence.statistic.modelCharacteristic.extension`| _Equivalent_<br/>(41489/41490)| **`Evidence.statistic.modelCharacteristic.extension`**
| | | | | | | `Evidence.statistic.modelCharacteristic.modifierExtension`| _Equivalent_<br/>(41491/41492)| **`Evidence.statistic.modelCharacteristic.modifierExtension`**
| | | | | | | `Evidence.statistic.modelCharacteristic.code`| _Equivalent_<br/>(41493/41494)| **`Evidence.statistic.modelCharacteristic.code`**
| | | | | | | `Evidence.statistic.modelCharacteristic.value`| _Equivalent_<br/>(41495/41496)| **`Evidence.statistic.modelCharacteristic.value`**
| | | | | | | `Evidence.statistic.modelCharacteristic.variable`| _Equivalent_<br/>(41497/41498)| **`Evidence.statistic.modelCharacteristic.variable`**
| | | | | | | `Evidence.statistic.modelCharacteristic.variable.id`| _Equivalent_<br/>(41499/41500)| **`Evidence.statistic.modelCharacteristic.variable.id`**
| | | | | | | `Evidence.statistic.modelCharacteristic.variable.extension`| _Equivalent_<br/>(41501/41502)| **`Evidence.statistic.modelCharacteristic.variable.extension`**
| | | | | | | `Evidence.statistic.modelCharacteristic.variable.modifierExtension`| _Equivalent_<br/>(41503/41504)| **`Evidence.statistic.modelCharacteristic.variable.modifierExtension`**
| | | | | | | `Evidence.statistic.modelCharacteristic.variable.variableDefinition`| _Equivalent_<br/>(41505/41506)| **`Evidence.statistic.modelCharacteristic.variable.variableDefinition`**
| | | | | | | `Evidence.statistic.modelCharacteristic.variable.handling`| _Equivalent_<br/>(41507/41508)| **`Evidence.statistic.modelCharacteristic.variable.handling`**
| | | | | | | `Evidence.statistic.modelCharacteristic.variable.valueCategory`| _Equivalent_<br/>(41509/41510)| **`Evidence.statistic.modelCharacteristic.variable.valueCategory`**
| | | | | | | `Evidence.statistic.modelCharacteristic.variable.valueQuantity`| _Equivalent_<br/>(41511/41512)| **`Evidence.statistic.modelCharacteristic.variable.valueQuantity`**
| | | | | | | `Evidence.statistic.modelCharacteristic.variable.valueRange`| _Equivalent_<br/>(41513/41514)| **`Evidence.statistic.modelCharacteristic.variable.valueRange`**
| | | | | | | `Evidence.statistic.modelCharacteristic.attributeEstimate`| _Equivalent_<br/>(41515/41516)| **`Evidence.statistic.modelCharacteristic.attributeEstimate`**
| | | | | | | `Evidence.certainty`| _Equivalent_<br/>(41517/41518)| **`Evidence.certainty`**
| | | | | | | `Evidence.certainty.id`| _Equivalent_<br/>(41519/41520)| **`Evidence.certainty.id`**
| | | | | | | `Evidence.certainty.extension`| _Equivalent_<br/>(41521/41522)| **`Evidence.certainty.extension`**
| | | | | | | `Evidence.certainty.modifierExtension`| _Equivalent_<br/>(41523/41524)| **`Evidence.certainty.modifierExtension`**
| | | | | | | `Evidence.certainty.description`| _Equivalent_<br/>(41525/41526)| **`Evidence.certainty.description`**
| | | | | | | `Evidence.certainty.note`| _Equivalent_<br/>(41527/41528)| **`Evidence.certainty.note`**
| | | | | | | `Evidence.certainty.type`| _Equivalent_<br/>(41529/41530)| **`Evidence.certainty.type`**
| | | | | | | `Evidence.certainty.rating`| _Equivalent_<br/>(41531/41532)| **`Evidence.certainty.rating`**
| | | | | | | `Evidence.certainty.rater`| _Equivalent_<br/>(41533/41534)| **`Evidence.certainty.rater`**
| | | | | | | `Evidence.certainty.subcomponent`| _Equivalent_<br/>(41535/41536)| **`Evidence.certainty.subcomponent`**
| | | | | *27 of 37 elements used* <br/>remaining elements:<br/>`Evidence.copyright`, `Evidence.effectivePeriod`, `Evidence.exposureBackground`, `Evidence.exposureVariant`, `Evidence.jurisdiction`, `Evidence.name`, `Evidence.outcome`, `Evidence.shortTitle`, `Evidence.subtitle`, `Evidence.topic`| | *97 of 98 elements used* <br/>remaining elements:<br/>`Evidence.studyType`| | *104 of 104 elements used* 

