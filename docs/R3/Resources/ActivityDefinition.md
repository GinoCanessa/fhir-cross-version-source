Comparison of 
Generated at Monday, April 14, 2025 6:17:23 PM

### ActivityDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | ActivityDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ActivityDefinition` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for ActivityDefinition Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `476` |
| Database Snapshot Count | `55` |
| Database Differential Count | `41` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ActivityDefinition` | `ActivityDefinition` | `ActivityDefinition` | ActivityDefinition | The definition of a specific activity to be taken, independent of any particular patient or context | 0..* | ActivityDefinition |  |  |
| `ActivityDefinition.approvalDate` | `ActivityDefinition.approvalDate` | `approvalDate` |  | When the activity definition was approved by publisher | 0..1 | date |  |  |
| `ActivityDefinition.bodySite` | `ActivityDefinition.bodySite` | `bodySite` |  | What part of body to perform on | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/body-site` |
| `ActivityDefinition.code` | `ActivityDefinition.code` | `code` |  | Detail type of activity | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/procedure-code` |
| `ActivityDefinition.contact` | `ActivityDefinition.contact` | `contact` |  | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `ActivityDefinition.contained` | `ActivityDefinition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ActivityDefinition.contributor` | `ActivityDefinition.contributor` | `contributor` |  | A content contributor | 0..* | Contributor |  |  |
| `ActivityDefinition.copyright` | `ActivityDefinition.copyright` | `copyright` |  | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `ActivityDefinition.date` | `ActivityDefinition.date` | `date` |  | Date this was last changed | 0..1 | dateTime |  |  |
| `ActivityDefinition.description` | `ActivityDefinition.description` | `description` |  | Natural language description of the activity definition | 0..1 | markdown |  |  |
| `ActivityDefinition.dosage` | `ActivityDefinition.dosage` | `dosage` |  | Detailed dosage instructions | 0..* | Dosage |  |  |
| `ActivityDefinition.dynamicValue` | `ActivityDefinition.dynamicValue` | `dynamicValue` |  | Dynamic aspects of the definition | 0..* | BackboneElement |  |  |
| `ActivityDefinition.dynamicValue.description` | `ActivityDefinition.dynamicValue.description` | `description` |  | Natural language description of the dynamic value | 0..1 | string |  |  |
| `ActivityDefinition.dynamicValue.expression` | `ActivityDefinition.dynamicValue.expression` | `expression` |  | An expression that provides the dynamic value for the customization | 0..1 | string |  |  |
| `ActivityDefinition.dynamicValue.extension` | `ActivityDefinition.dynamicValue.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ActivityDefinition.dynamicValue.id` | `ActivityDefinition.dynamicValue.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ActivityDefinition.dynamicValue.language` | `ActivityDefinition.dynamicValue.language` | `language` |  | Language of the expression | 0..1 | string |  |  |
| `ActivityDefinition.dynamicValue.modifierExtension` | `ActivityDefinition.dynamicValue.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ActivityDefinition.dynamicValue.path` | `ActivityDefinition.dynamicValue.path` | `path` |  | The path to the element to be set dynamically | 0..1 | string |  |  |
| `ActivityDefinition.effectivePeriod` | `ActivityDefinition.effectivePeriod` | `effectivePeriod` |  | When the activity definition is expected to be used | 0..1 | Period |  |  |
| `ActivityDefinition.experimental` | `ActivityDefinition.experimental` | `experimental` |  | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `ActivityDefinition.extension` | `ActivityDefinition.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ActivityDefinition.id` | `ActivityDefinition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ActivityDefinition.identifier` | `ActivityDefinition.identifier` | `identifier` |  | Additional identifier for the activity definition | 0..* | Identifier |  |  |
| `ActivityDefinition.implicitRules` | `ActivityDefinition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ActivityDefinition.jurisdiction` | `ActivityDefinition.jurisdiction` | `jurisdiction` |  | Intended jurisdiction for activity definition (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `ActivityDefinition.kind` | `ActivityDefinition.kind` | `kind` |  | Kind of resource | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/resource-types` |
| `ActivityDefinition.language` | `ActivityDefinition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `ActivityDefinition.lastReviewDate` | `ActivityDefinition.lastReviewDate` | `lastReviewDate` |  | When the activity definition was last reviewed | 0..1 | date |  |  |
| `ActivityDefinition.library` | `ActivityDefinition.library` | `library` |  | Logic used by the asset | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Library) |  |  |
| `ActivityDefinition.location` | `ActivityDefinition.location` | `location` |  | Where it should happen | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `ActivityDefinition.meta` | `ActivityDefinition.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ActivityDefinition.modifierExtension` | `ActivityDefinition.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ActivityDefinition.name` | `ActivityDefinition.name` | `name` |  | Name for this activity definition (computer friendly) | 0..1 | string |  |  |
| `ActivityDefinition.participant` | `ActivityDefinition.participant` | `participant` |  | Who should participate in the action | 0..* | BackboneElement |  |  |
| `ActivityDefinition.participant.extension` | `ActivityDefinition.participant.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ActivityDefinition.participant.id` | `ActivityDefinition.participant.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ActivityDefinition.participant.modifierExtension` | `ActivityDefinition.participant.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ActivityDefinition.participant.role` | `ActivityDefinition.participant.role` | `role` |  | E.g. Nurse, Surgeon, Parent, etc | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/action-participant-role` |
| `ActivityDefinition.participant.type` | `ActivityDefinition.participant.type` | `type` |  | patient \| practitioner \| related-person | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/action-participant-type` |
| `ActivityDefinition.product[x]` | `ActivityDefinition.product[x]` | `product[x]` |  | What's administered/supplied | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Medication), Reference(http://hl7.org/fhir/StructureDefinition/Substance) | `Example` | `http://hl7.org/fhir/ValueSet/medication-codes` |
| `ActivityDefinition.publisher` | `ActivityDefinition.publisher` | `publisher` |  | Name of the publisher (organization or individual) | 0..1 | string |  |  |
| `ActivityDefinition.purpose` | `ActivityDefinition.purpose` | `purpose` |  | Why this activity definition is defined | 0..1 | markdown |  |  |
| `ActivityDefinition.quantity` | `ActivityDefinition.quantity` | `quantity` |  | How much is administered/consumed/supplied | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `ActivityDefinition.relatedArtifact` | `ActivityDefinition.relatedArtifact` | `relatedArtifact` |  | Additional documentation, citations, etc | 0..* | RelatedArtifact |  |  |
| `ActivityDefinition.status` | `ActivityDefinition.status` | `status` |  | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status` |
| `ActivityDefinition.text` | `ActivityDefinition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `ActivityDefinition.timing[x]` | `ActivityDefinition.timing[x]` | `timing[x]` |  | When activity is to occur | 0..1 | dateTime, Period, Range, Timing |  |  |
| `ActivityDefinition.title` | `ActivityDefinition.title` | `title` |  | Name for this activity definition (human friendly) | 0..1 | string |  |  |
| `ActivityDefinition.topic` | `ActivityDefinition.topic` | `topic` |  | E.g. Education, Treatment, Assessment, etc | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/definition-topic` |
| `ActivityDefinition.transform` | `ActivityDefinition.transform` | `transform` |  | Transform to apply the template | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/StructureMap) |  |  |
| `ActivityDefinition.url` | `ActivityDefinition.url` | `url` |  | Logical URI to reference this activity definition (globally unique) | 0..1 | uri |  |  |
| `ActivityDefinition.usage` | `ActivityDefinition.usage` | `usage` |  | Describes the clinical usage of the asset | 0..1 | string |  |  |
| `ActivityDefinition.useContext` | `ActivityDefinition.useContext` | `useContext` |  | Context the content is intended to support | 0..* | UsageContext |  |  |
| `ActivityDefinition.version` | `ActivityDefinition.version` | `version` |  | Business version of the activity definition | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [ActivityDefinition](/docs/R3/Resources/ActivityDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ActivityDefinition\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `416`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `612`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ActivityDefinition](/docs/R4/Resources/ActivityDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ActivityDefinition\|4.0.1` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1389`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1390`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ActivityDefinition](/docs/R4B/Resources/ActivityDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ActivityDefinition\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `929`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1158`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ActivityDefinition](/docs/R5/Resources/ActivityDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/ActivityDefinition\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ActivityDefinition from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | R3 ActivityDefinition| Relationship | [R4 ActivityDefinition](/docs/R4/Resources/ActivityDefinition.md)| Relationship | [R4B ActivityDefinition](/docs/R4B/Resources/ActivityDefinition.md)| Relationship | [R5 ActivityDefinition](/docs/R5/Resources/ActivityDefinition.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | **`ActivityDefinition`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9948)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9949)| `ActivityDefinition`| _Equivalent_<br/>(21442/21443)| `ActivityDefinition`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36491)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36492)| `ActivityDefinition`
| | | **`ActivityDefinition.id`**| _Equivalent_<br/>(9950/9951)| `ActivityDefinition.id`| _Equivalent_<br/>(21444/21445)| `ActivityDefinition.id`| _Equivalent_<br/>(36493/36494)| `ActivityDefinition.id`
| | | **`ActivityDefinition.meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9952)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9953)| `ActivityDefinition.meta`| _Equivalent_<br/>(21446/21447)| `ActivityDefinition.meta`| _Equivalent_<br/>(36495/36496)| `ActivityDefinition.meta`
| | | **`ActivityDefinition.implicitRules`**| _Equivalent_<br/>(9954/9955)| `ActivityDefinition.implicitRules`| _Equivalent_<br/>(21448/21449)| `ActivityDefinition.implicitRules`| _Equivalent_<br/>(36497/36498)| `ActivityDefinition.implicitRules`
| | | **`ActivityDefinition.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9956)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9957)| `ActivityDefinition.language`| _Equivalent_<br/>(21450/21451)| `ActivityDefinition.language`| _Equivalent_<br/>(36499/36500)| `ActivityDefinition.language`
| | | **`ActivityDefinition.text`**| _Equivalent_<br/>(9958/9959)| `ActivityDefinition.text`| _Equivalent_<br/>(21452/21453)| `ActivityDefinition.text`| _Equivalent_<br/>(36501/36502)| `ActivityDefinition.text`
| | | **`ActivityDefinition.contained`**| _Equivalent_<br/>(9960/9961)| `ActivityDefinition.contained`| _Equivalent_<br/>(21454/21455)| `ActivityDefinition.contained`| _Equivalent_<br/>(36503/36504)| `ActivityDefinition.contained`
| | | **`ActivityDefinition.extension`**| _Equivalent_<br/>(9962/9963)| `ActivityDefinition.extension`| _Equivalent_<br/>(21456/21457)| `ActivityDefinition.extension`| _Equivalent_<br/>(36505/36506)| `ActivityDefinition.extension`
| | | **`ActivityDefinition.modifierExtension`**| _Equivalent_<br/>(9964/9965)| `ActivityDefinition.modifierExtension`| _Equivalent_<br/>(21458/21459)| `ActivityDefinition.modifierExtension`| _Equivalent_<br/>(36507/36508)| `ActivityDefinition.modifierExtension`
| | | **`ActivityDefinition.url`**| _Equivalent_<br/>(9966/9967)| `ActivityDefinition.url`| _Equivalent_<br/>(21460/21461)| `ActivityDefinition.url`| _Equivalent_<br/>(36509/36510)| `ActivityDefinition.url`
| | | **`ActivityDefinition.identifier`**| _Equivalent_<br/>(9968/9969)| `ActivityDefinition.identifier`| _Equivalent_<br/>(21462/21463)| `ActivityDefinition.identifier`| _Equivalent_<br/>(36511/36512)| `ActivityDefinition.identifier`
| | | **`ActivityDefinition.version`**| _Equivalent_<br/>(9970/9971)| `ActivityDefinition.version`| _Equivalent_<br/>(21464/21465)| `ActivityDefinition.version`| _Equivalent_<br/>(36513/36514)| `ActivityDefinition.version`
| | | **`ActivityDefinition.name`**| _Equivalent_<br/>(9972/9973)| `ActivityDefinition.name`| _Equivalent_<br/>(21466/21467)| `ActivityDefinition.name`| _Equivalent_<br/>(36515/36516)| `ActivityDefinition.name`
| | | **`ActivityDefinition.title`**| _Equivalent_<br/>(9974/9975)| `ActivityDefinition.title`| _Equivalent_<br/>(21468/21469)| `ActivityDefinition.title`| _Equivalent_<br/>(36517/36518)| `ActivityDefinition.title`
| | | **`ActivityDefinition.status`**| _Equivalent_<br/>(9976/9977)| `ActivityDefinition.status`| _Equivalent_<br/>(21472/21473)| `ActivityDefinition.status`| _Equivalent_<br/>(36521/36522)| `ActivityDefinition.status`
| | | **`ActivityDefinition.experimental`**| _Equivalent_<br/>(9978/9979)| `ActivityDefinition.experimental`| _Equivalent_<br/>(21474/21475)| `ActivityDefinition.experimental`| _Equivalent_<br/>(36523/36524)| `ActivityDefinition.experimental`
| | | **`ActivityDefinition.date`**| _Equivalent_<br/>(9980/9981)| `ActivityDefinition.date`| _Equivalent_<br/>(21478/21479)| `ActivityDefinition.date`| _Equivalent_<br/>(36527/36528)| `ActivityDefinition.date`
| | | **`ActivityDefinition.publisher`**| _Equivalent_<br/>(9982/9983)| `ActivityDefinition.publisher`| _Equivalent_<br/>(21480/21481)| `ActivityDefinition.publisher`| _Equivalent_<br/>(36529/36530)| `ActivityDefinition.publisher`
| | | **`ActivityDefinition.description`**| _Equivalent_<br/>(9984/9985)| `ActivityDefinition.description`| _Equivalent_<br/>(21484/21485)| `ActivityDefinition.description`| _Equivalent_<br/>(36533/36534)| `ActivityDefinition.description`
| | | **`ActivityDefinition.purpose`**| _Equivalent_<br/>(9986/9987)| `ActivityDefinition.purpose`| _Equivalent_<br/>(21490/21491)| `ActivityDefinition.purpose`| _Equivalent_<br/>(36539/36540)| `ActivityDefinition.purpose`
| | | **`ActivityDefinition.usage`**| _Equivalent_<br/>(9988/9989)| `ActivityDefinition.usage`| _Equivalent_<br/>(21492/21493)| `ActivityDefinition.usage`| _Equivalent_<br/>(36541/36542)| `ActivityDefinition.usage`
| | | **`ActivityDefinition.approvalDate`**| _Equivalent_<br/>(9990/9991)| `ActivityDefinition.approvalDate`| _Equivalent_<br/>(21496/21497)| `ActivityDefinition.approvalDate`| _Equivalent_<br/>(36545/36546)| `ActivityDefinition.approvalDate`
| | | **`ActivityDefinition.lastReviewDate`**| _Equivalent_<br/>(9992/9993)| `ActivityDefinition.lastReviewDate`| _Equivalent_<br/>(21498/21499)| `ActivityDefinition.lastReviewDate`| _Equivalent_<br/>(36547/36548)| `ActivityDefinition.lastReviewDate`
| | | **`ActivityDefinition.effectivePeriod`**| _Equivalent_<br/>(9994/9995)| `ActivityDefinition.effectivePeriod`| _Equivalent_<br/>(21500/21501)| `ActivityDefinition.effectivePeriod`| _Equivalent_<br/>(36549/36550)| `ActivityDefinition.effectivePeriod`
| | | **`ActivityDefinition.useContext`**| _Equivalent_<br/>(9996/9997)| `ActivityDefinition.useContext`| _Equivalent_<br/>(21486/21487)| `ActivityDefinition.useContext`| _Equivalent_<br/>(36535/36536)| `ActivityDefinition.useContext`
| | | **`ActivityDefinition.jurisdiction`**| _Equivalent_<br/>(9998/9999)| `ActivityDefinition.jurisdiction`| _Equivalent_<br/>(21488/21489)| `ActivityDefinition.jurisdiction`| _Equivalent_<br/>(36537/36538)| `ActivityDefinition.jurisdiction`
| | | **`ActivityDefinition.topic`**| _Equivalent_<br/>(10000/10001)| `ActivityDefinition.topic`| _Equivalent_<br/>(21502/21503)| `ActivityDefinition.topic`| _Equivalent_<br/>(36551/36552)| `ActivityDefinition.topic`
| | | **`ActivityDefinition.contributor`**| →→→→ __ →→→→ <br/>(799)<hr/>←←←← __ ←←←← <br/>()| `base64Binary`| | | | | 
| | | **`ActivityDefinition.contributor`**| →→→→ _Equivalent_ →→→→ <br/>(21431)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1336)| `ActivityDefinition.author`| _Equivalent_<br/>(21504/21505)| `ActivityDefinition.author`| _Equivalent_<br/>(36553/36554)| `ActivityDefinition.author`
| | | **`ActivityDefinition.contributor`**| →→→→ _Equivalent_ →→→→ <br/>(21432)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1337)| `ActivityDefinition.editor`| _Equivalent_<br/>(21506/21507)| `ActivityDefinition.editor`| _Equivalent_<br/>(36555/36556)| `ActivityDefinition.editor`
| | | **`ActivityDefinition.contributor`**| →→→→ _Equivalent_ →→→→ <br/>(21433)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1338)| `ActivityDefinition.reviewer`| _Equivalent_<br/>(21508/21509)| `ActivityDefinition.reviewer`| _Equivalent_<br/>(36557/36558)| `ActivityDefinition.reviewer`
| | | **`ActivityDefinition.contributor`**| →→→→ _Equivalent_ →→→→ <br/>(21434)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1339)| `ActivityDefinition.endorser`| _Equivalent_<br/>(21510/21511)| `ActivityDefinition.endorser`| _Equivalent_<br/>(36559/36560)| `ActivityDefinition.endorser`
| | | **`ActivityDefinition.contact`**| _Equivalent_<br/>(10002/10003)| `ActivityDefinition.contact`| _Equivalent_<br/>(21482/21483)| `ActivityDefinition.contact`| _Equivalent_<br/>(36531/36532)| `ActivityDefinition.contact`
| | | **`ActivityDefinition.copyright`**| _Equivalent_<br/>(10004/10005)| `ActivityDefinition.copyright`| _Equivalent_<br/>(21494/21495)| `ActivityDefinition.copyright`| _Equivalent_<br/>(36543/36544)| `ActivityDefinition.copyright`
| | | **`ActivityDefinition.relatedArtifact`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10006)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10007)| `ActivityDefinition.relatedArtifact`| _Equivalent_<br/>(21512/21513)| `ActivityDefinition.relatedArtifact`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36561)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36562)| `ActivityDefinition.relatedArtifact`
| | | **`ActivityDefinition.library`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(10008)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10009)| `ActivityDefinition.library`| _Equivalent_<br/>(21514/21515)| `ActivityDefinition.library`| _Equivalent_<br/>(36563/36564)| `ActivityDefinition.library`
| | | **`ActivityDefinition.kind`**| _Equivalent_<br/>(10010/10011)| `ActivityDefinition.kind`| _Equivalent_<br/>(21516/21517)| `ActivityDefinition.kind`| →→→→ _Equivalent_ →→→→ <br/>(36565)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36566)| `ActivityDefinition.kind`
| | | **`ActivityDefinition.code`**| _Equivalent_<br/>(10012/10013)| `ActivityDefinition.code`| _Equivalent_<br/>(21520/21521)| `ActivityDefinition.code`| _Equivalent_<br/>(36569/36570)| `ActivityDefinition.code`
| | | **`ActivityDefinition.timing[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10014)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10015)| `ActivityDefinition.timing[x]`| _Equivalent_<br/>(21528/21529)| `ActivityDefinition.timing[x]`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(36577)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36578)| `ActivityDefinition.timing[x]`
| | | **`ActivityDefinition.location`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10016)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10017)| `ActivityDefinition.location`| _Equivalent_<br/>(21530/21531)| `ActivityDefinition.location`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(36579)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36580)| `ActivityDefinition.location`
| | | **`ActivityDefinition.participant`**| _Equivalent_<br/>(10018/10019)| `ActivityDefinition.participant`| _Equivalent_<br/>(21532/21533)| `ActivityDefinition.participant`| _Equivalent_<br/>(36581/36582)| `ActivityDefinition.participant`
| | | **`ActivityDefinition.participant.id`**| _Equivalent_<br/>(10020/10021)| `ActivityDefinition.participant.id`| _Equivalent_<br/>(21534/21535)| `ActivityDefinition.participant.id`| _Equivalent_<br/>(36583/36584)| `ActivityDefinition.participant.id`
| | | **`ActivityDefinition.participant.extension`**| _Equivalent_<br/>(10022/10023)| `ActivityDefinition.participant.extension`| _Equivalent_<br/>(21536/21537)| `ActivityDefinition.participant.extension`| _Equivalent_<br/>(36585/36586)| `ActivityDefinition.participant.extension`
| | | **`ActivityDefinition.participant.modifierExtension`**| _Equivalent_<br/>(10024/10025)| `ActivityDefinition.participant.modifierExtension`| _Equivalent_<br/>(21538/21539)| `ActivityDefinition.participant.modifierExtension`| _Equivalent_<br/>(36587/36588)| `ActivityDefinition.participant.modifierExtension`
| | | **`ActivityDefinition.participant.type`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10026)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10027)| `ActivityDefinition.participant.type`| _Equivalent_<br/>(21540/21541)| `ActivityDefinition.participant.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36589)<hr/>←←←← _RelatedTo_ ←←←← <br/>(36590)| `ActivityDefinition.participant.type`
| | | **`ActivityDefinition.participant.role`**| _Equivalent_<br/>(10028/10029)| `ActivityDefinition.participant.role`| _Equivalent_<br/>(21542/21543)| `ActivityDefinition.participant.role`| _Equivalent_<br/>(36591/36592)| `ActivityDefinition.participant.role`
| | | **`ActivityDefinition.product[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10030)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10031)| `ActivityDefinition.product[x]`| →→→→ _RelatedTo_ →→→→ <br/>(21544)<hr/>←←←← _RelatedTo_ ←←←← <br/>(21545)| `ActivityDefinition.product[x]`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(36593)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(36594)| `ActivityDefinition.product[x]`
| | | **`ActivityDefinition.quantity`**| _Equivalent_<br/>(10032/10033)| `ActivityDefinition.quantity`| _Equivalent_<br/>(21546/21547)| `ActivityDefinition.quantity`| _Equivalent_<br/>(36595/36596)| `ActivityDefinition.quantity`
| | | **`ActivityDefinition.dosage`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10034)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10035)| `ActivityDefinition.dosage`| _Equivalent_<br/>(21548/21549)| `ActivityDefinition.dosage`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36597)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36598)| `ActivityDefinition.dosage`
| | | **`ActivityDefinition.bodySite`**| _Equivalent_<br/>(10036/10037)| `ActivityDefinition.bodySite`| _Equivalent_<br/>(21550/21551)| `ActivityDefinition.bodySite`| _Equivalent_<br/>(36599/36600)| `ActivityDefinition.bodySite`
| | | **`ActivityDefinition.transform`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(10038)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10039)| `ActivityDefinition.transform`| _Equivalent_<br/>(21558/21559)| `ActivityDefinition.transform`| _Equivalent_<br/>(36607/36608)| `ActivityDefinition.transform`
| | | **`ActivityDefinition.dynamicValue`**| _Equivalent_<br/>(10040/10041)| `ActivityDefinition.dynamicValue`| _Equivalent_<br/>(21560/21561)| `ActivityDefinition.dynamicValue`| _Equivalent_<br/>(36609/36610)| `ActivityDefinition.dynamicValue`
| | | **`ActivityDefinition.dynamicValue.id`**| _Equivalent_<br/>(10042/10043)| `ActivityDefinition.dynamicValue.id`| _Equivalent_<br/>(21562/21563)| `ActivityDefinition.dynamicValue.id`| _Equivalent_<br/>(36611/36612)| `ActivityDefinition.dynamicValue.id`
| | | **`ActivityDefinition.dynamicValue.extension`**| _Equivalent_<br/>(10044/10045)| `ActivityDefinition.dynamicValue.extension`| _Equivalent_<br/>(21564/21565)| `ActivityDefinition.dynamicValue.extension`| _Equivalent_<br/>(36613/36614)| `ActivityDefinition.dynamicValue.extension`
| | | **`ActivityDefinition.dynamicValue.modifierExtension`**| _Equivalent_<br/>(10046/10047)| `ActivityDefinition.dynamicValue.modifierExtension`| _Equivalent_<br/>(21566/21567)| `ActivityDefinition.dynamicValue.modifierExtension`| _Equivalent_<br/>(36615/36616)| `ActivityDefinition.dynamicValue.modifierExtension`
| | | **`ActivityDefinition.dynamicValue.description`**| | | | | | | 
| | | **`ActivityDefinition.dynamicValue.path`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10049)<hr/>←←←← _Equivalent_ ←←←← <br/>(10050)| `ActivityDefinition.dynamicValue.path`| _Equivalent_<br/>(21568/21569)| `ActivityDefinition.dynamicValue.path`| _Equivalent_<br/>(36617/36618)| `ActivityDefinition.dynamicValue.path`
| | | **`ActivityDefinition.dynamicValue.language`**| | | | | | | 
| | | **`ActivityDefinition.dynamicValue.expression`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(10052)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(10053)| `ActivityDefinition.dynamicValue.expression`| _Equivalent_<br/>(21570/21571)| `ActivityDefinition.dynamicValue.expression`| _Equivalent_<br/>(36619/36620)| `ActivityDefinition.dynamicValue.expression`
| | | *55 of 55 elements used* | | *57 of 65 elements used* <br/>remaining elements:<br/>`ActivityDefinition.doNotPerform`, `ActivityDefinition.intent`, `ActivityDefinition.observationRequirement`, `ActivityDefinition.observationResultRequirement`, `ActivityDefinition.priority`, `ActivityDefinition.profile`, `ActivityDefinition.specimenRequirement`, `ActivityDefinition.subject[x]`, `ActivityDefinition.subtitle`| | *56 of 65 elements used* <br/>remaining elements:<br/>`ActivityDefinition.doNotPerform`, `ActivityDefinition.intent`, `ActivityDefinition.observationRequirement`, `ActivityDefinition.observationResultRequirement`, `ActivityDefinition.priority`, `ActivityDefinition.profile`, `ActivityDefinition.specimenRequirement`, `ActivityDefinition.subject[x]`, `ActivityDefinition.subtitle`| | *56 of 71 elements used* <br/>remaining elements:<br/>`ActivityDefinition.asNeeded[x]`, `ActivityDefinition.copyrightLabel`, `ActivityDefinition.doNotPerform`, `ActivityDefinition.intent`, `ActivityDefinition.observationRequirement`, `ActivityDefinition.observationResultRequirement`, `ActivityDefinition.participant.function`, `ActivityDefinition.participant.typeCanonical`, `ActivityDefinition.participant.typeReference`, `ActivityDefinition.priority`, `ActivityDefinition.profile`, `ActivityDefinition.specimenRequirement`, `ActivityDefinition.subject[x]`, `ActivityDefinition.subtitle`, `ActivityDefinition.versionAlgorithm[x]`

