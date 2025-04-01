Comparison of 
Generated at Tuesday, April 1, 2025 1:39:13 PM

### Questionnaire

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | Questionnaire |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Questionnaire` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for Questionnaire Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `568` |
| Database Snapshot Count | `58` |
| Database Differential Count | `41` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Questionnaire` | `Questionnaire` | `Questionnaire` | Questionnaire | A structured set of questions | 0..* | Questionnaire |  |  |
| `Questionnaire.approvalDate` | `Questionnaire.approvalDate` | `approvalDate` |  | When the questionnaire was approved by publisher | 0..1 | date |  |  |
| `Questionnaire.code` | `Questionnaire.code` | `code` |  | Concept that represents the overall questionnaire | 0..* | Coding | `Example` | `http://hl7.org/fhir/ValueSet/questionnaire-questions` |
| `Questionnaire.contact` | `Questionnaire.contact` | `contact` |  | Contact details for the publisher | 0..* | ContactDetail |  |  |
| `Questionnaire.contained` | `Questionnaire.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Questionnaire.copyright` | `Questionnaire.copyright` | `copyright` |  | Use and/or publishing restrictions | 0..1 | markdown |  |  |
| `Questionnaire.date` | `Questionnaire.date` | `date` |  | Date this was last changed | 0..1 | dateTime |  |  |
| `Questionnaire.description` | `Questionnaire.description` | `description` |  | Natural language description of the questionnaire | 0..1 | markdown |  |  |
| `Questionnaire.effectivePeriod` | `Questionnaire.effectivePeriod` | `effectivePeriod` |  | When the questionnaire is expected to be used | 0..1 | Period |  |  |
| `Questionnaire.experimental` | `Questionnaire.experimental` | `experimental` |  | For testing purposes, not real usage | 0..1 | boolean |  |  |
| `Questionnaire.extension` | `Questionnaire.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Questionnaire.id` | `Questionnaire.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Questionnaire.identifier` | `Questionnaire.identifier` | `identifier` |  | Additional identifier for the questionnaire | 0..* | Identifier |  |  |
| `Questionnaire.implicitRules` | `Questionnaire.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Questionnaire.item` | `Questionnaire.item` | `item` |  | Questions and sections within the Questionnaire | 0..* | BackboneElement |  |  |
| `Questionnaire.item.code` | `Questionnaire.item.code` | `code` |  | Corresponding concept for this item in a terminology | 0..* | Coding | `Example` | `http://hl7.org/fhir/ValueSet/questionnaire-questions` |
| `Questionnaire.item.definition` | `Questionnaire.item.definition` | `definition` |  | ElementDefinition - details for the item | 0..1 | uri |  |  |
| `Questionnaire.item.enableWhen` | `Questionnaire.item.enableWhen` | `enableWhen` |  | Only allow data when | 0..* | BackboneElement |  |  |
| `Questionnaire.item.enableWhen.answer[x]` | `Questionnaire.item.enableWhen.answer[x]` | `answer[x]` |  | Value question must have | 0..1 | Attachment, boolean, Coding, date, dateTime, decimal, integer, Quantity, Reference(http://hl7.org/fhir/StructureDefinition/Resource), string, time, uri | `Example` | `http://hl7.org/fhir/ValueSet/questionnaire-answers` |
| `Questionnaire.item.enableWhen.extension` | `Questionnaire.item.enableWhen.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Questionnaire.item.enableWhen.hasAnswer` | `Questionnaire.item.enableWhen.hasAnswer` | `hasAnswer` |  | Enable when answered or not | 0..1 | boolean |  |  |
| `Questionnaire.item.enableWhen.id` | `Questionnaire.item.enableWhen.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Questionnaire.item.enableWhen.modifierExtension` | `Questionnaire.item.enableWhen.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Questionnaire.item.enableWhen.question` | `Questionnaire.item.enableWhen.question` | `question` |  | Question that determines whether item is enabled | 1..1 | string |  |  |
| `Questionnaire.item.extension` | `Questionnaire.item.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Questionnaire.item.id` | `Questionnaire.item.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Questionnaire.item.initial[x]` | `Questionnaire.item.initial[x]` | `initial[x]` |  | Default value when item is first rendered | 0..1 | Attachment, boolean, Coding, date, dateTime, decimal, integer, Quantity, Reference(http://hl7.org/fhir/StructureDefinition/Resource), string, time, uri | `Example` | `http://hl7.org/fhir/ValueSet/questionnaire-answers` |
| `Questionnaire.item.item` | `Questionnaire.item.item` | `item` |  | Nested questionnaire items | 0..* | Questionnaire.item |  |  |
| `Questionnaire.item.linkId` | `Questionnaire.item.linkId` | `linkId` |  | Unique id for item in questionnaire | 1..1 | string |  |  |
| `Questionnaire.item.maxLength` | `Questionnaire.item.maxLength` | `maxLength` |  | No more than this many characters | 0..1 | integer |  |  |
| `Questionnaire.item.modifierExtension` | `Questionnaire.item.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Questionnaire.item.option` | `Questionnaire.item.option` | `option` |  | Permitted answer | 0..* | BackboneElement |  |  |
| `Questionnaire.item.option.extension` | `Questionnaire.item.option.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Questionnaire.item.option.id` | `Questionnaire.item.option.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Questionnaire.item.option.modifierExtension` | `Questionnaire.item.option.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Questionnaire.item.option.value[x]` | `Questionnaire.item.option.value[x]` | `value[x]` |  | Answer value | 1..1 | Coding, date, integer, string, time | `Example` | `http://hl7.org/fhir/ValueSet/questionnaire-answers` |
| `Questionnaire.item.options` | `Questionnaire.item.options` | `options` |  | Valueset containing permitted answers | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/ValueSet) |  |  |
| `Questionnaire.item.prefix` | `Questionnaire.item.prefix` | `prefix` |  | E.g. "1(a)", "2.5.3" | 0..1 | string |  |  |
| `Questionnaire.item.readOnly` | `Questionnaire.item.readOnly` | `readOnly` |  | Don't allow human editing | 0..1 | boolean |  |  |
| `Questionnaire.item.repeats` | `Questionnaire.item.repeats` | `repeats` |  | Whether the item may repeat | 0..1 | boolean |  |  |
| `Questionnaire.item.required` | `Questionnaire.item.required` | `required` |  | Whether the item must be included in data results | 0..1 | boolean |  |  |
| `Questionnaire.item.text` | `Questionnaire.item.text` | `text` |  | Primary text for the item | 0..1 | string |  |  |
| `Questionnaire.item.type` | `Questionnaire.item.type` | `type` |  | group \| display \| boolean \| decimal \| integer \| date \| dateTime + | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/item-type` |
| `Questionnaire.jurisdiction` | `Questionnaire.jurisdiction` | `jurisdiction` |  | Intended jurisdiction for questionnaire (if applicable) | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `Questionnaire.language` | `Questionnaire.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `Questionnaire.lastReviewDate` | `Questionnaire.lastReviewDate` | `lastReviewDate` |  | When the questionnaire was last reviewed | 0..1 | date |  |  |
| `Questionnaire.meta` | `Questionnaire.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Questionnaire.modifierExtension` | `Questionnaire.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Questionnaire.name` | `Questionnaire.name` | `name` |  | Name for this questionnaire (computer friendly) | 0..1 | string |  |  |
| `Questionnaire.publisher` | `Questionnaire.publisher` | `publisher` |  | Name of the publisher (organization or individual) | 0..1 | string |  |  |
| `Questionnaire.purpose` | `Questionnaire.purpose` | `purpose` |  | Why this questionnaire is defined | 0..1 | markdown |  |  |
| `Questionnaire.status` | `Questionnaire.status` | `status` |  | draft \| active \| retired \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/publication-status` |
| `Questionnaire.subjectType` | `Questionnaire.subjectType` | `subjectType` |  | Resource that can be subject of QuestionnaireResponse | 0..* | code | `Required` | `http://hl7.org/fhir/ValueSet/resource-types` |
| `Questionnaire.text` | `Questionnaire.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Questionnaire.title` | `Questionnaire.title` | `title` |  | Name for this questionnaire (human friendly) | 0..1 | string |  |  |
| `Questionnaire.url` | `Questionnaire.url` | `url` |  | Logical URI to reference this questionnaire (globally unique) | 0..1 | uri |  |  |
| `Questionnaire.useContext` | `Questionnaire.useContext` | `useContext` |  | Context the content is intended to support | 0..* | UsageContext |  |  |
| `Questionnaire.version` | `Questionnaire.version` | `version` |  | Business version of the questionnaire | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Questionnaire](/docs/R2/Resources/Questionnaire.md)<br/> `http://hl7.org/fhir/StructureDefinition/Questionnaire\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `148`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `314`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Questionnaire](/docs/R3/Resources/Questionnaire.md)<br/> `http://hl7.org/fhir/StructureDefinition/Questionnaire\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `505`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `698`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Questionnaire](/docs/R4/Resources/Questionnaire.md)<br/> `http://hl7.org/fhir/StructureDefinition/Questionnaire\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1589`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1590`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Questionnaire](/docs/R4B/Resources/Questionnaire.md)<br/> `http://hl7.org/fhir/StructureDefinition/Questionnaire\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1030`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1259`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Questionnaire](/docs/R5/Resources/Questionnaire.md)<br/> `http://hl7.org/fhir/StructureDefinition/Questionnaire\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Questionnaire from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Questionnaire](/docs/R2/Resources/Questionnaire.md)| Relationship | R3 Questionnaire| Relationship | [R4 Questionnaire](/docs/R4/Resources/Questionnaire.md)| Relationship | [R4B Questionnaire](/docs/R4B/Resources/Questionnaire.md)| Relationship | [R5 Questionnaire](/docs/R5/Resources/Questionnaire.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Questionnaire`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7496)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7497)| **`Questionnaire`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17677)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17678)| `Questionnaire`| _Equivalent_<br/>(32071/32072)| `Questionnaire`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(46641)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(46642)| `Questionnaire`
| `Questionnaire.id`| _Equivalent_<br/>(7498/7499)| **`Questionnaire.id`**| _Equivalent_<br/>(17679/17680)| `Questionnaire.id`| _Equivalent_<br/>(32073/32074)| `Questionnaire.id`| _Equivalent_<br/>(46643/46644)| `Questionnaire.id`
| `Questionnaire.meta`| _Equivalent_<br/>(7500/7501)| **`Questionnaire.meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17681)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17682)| `Questionnaire.meta`| _Equivalent_<br/>(32075/32076)| `Questionnaire.meta`| _Equivalent_<br/>(46645/46646)| `Questionnaire.meta`
| `Questionnaire.implicitRules`| _Equivalent_<br/>(7502/7503)| **`Questionnaire.implicitRules`**| _Equivalent_<br/>(17683/17684)| `Questionnaire.implicitRules`| _Equivalent_<br/>(32077/32078)| `Questionnaire.implicitRules`| _Equivalent_<br/>(46647/46648)| `Questionnaire.implicitRules`
| `Questionnaire.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7504)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7505)| **`Questionnaire.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(17685)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(17686)| `Questionnaire.language`| _Equivalent_<br/>(32079/32080)| `Questionnaire.language`| _Equivalent_<br/>(46649/46650)| `Questionnaire.language`
| `Questionnaire.text`| _Equivalent_<br/>(7506/7507)| **`Questionnaire.text`**| _Equivalent_<br/>(17687/17688)| `Questionnaire.text`| _Equivalent_<br/>(32081/32082)| `Questionnaire.text`| _Equivalent_<br/>(46651/46652)| `Questionnaire.text`
| `Questionnaire.contained`| _Equivalent_<br/>(7508/7509)| **`Questionnaire.contained`**| _Equivalent_<br/>(17689/17690)| `Questionnaire.contained`| _Equivalent_<br/>(32083/32084)| `Questionnaire.contained`| _Equivalent_<br/>(46653/46654)| `Questionnaire.contained`
| `Questionnaire.extension`| _Equivalent_<br/>(7510/7511)| **`Questionnaire.extension`**| _Equivalent_<br/>(17691/17692)| `Questionnaire.extension`| _Equivalent_<br/>(32085/32086)| `Questionnaire.extension`| _Equivalent_<br/>(46655/46656)| `Questionnaire.extension`
| `Questionnaire.modifierExtension`| _Equivalent_<br/>(7512/7513)| **`Questionnaire.modifierExtension`**| _Equivalent_<br/>(17693/17694)| `Questionnaire.modifierExtension`| _Equivalent_<br/>(32087/32088)| `Questionnaire.modifierExtension`| _Equivalent_<br/>(46657/46658)| `Questionnaire.modifierExtension`
| | | **`Questionnaire.url`**| _Equivalent_<br/>(17695/17696)| `Questionnaire.url`| _Equivalent_<br/>(32089/32090)| `Questionnaire.url`| _Equivalent_<br/>(46659/46660)| `Questionnaire.url`
| `Questionnaire.identifier`| _Equivalent_<br/>(7514/7515)| **`Questionnaire.identifier`**| _Equivalent_<br/>(17697/17698)| `Questionnaire.identifier`| _Equivalent_<br/>(32091/32092)| `Questionnaire.identifier`| _Equivalent_<br/>(46661/46662)| `Questionnaire.identifier`
| `Questionnaire.version`| _Equivalent_<br/>(7516/7517)| **`Questionnaire.version`**| _Equivalent_<br/>(17699/17700)| `Questionnaire.version`| _Equivalent_<br/>(32093/32094)| `Questionnaire.version`| _Equivalent_<br/>(46663/46664)| `Questionnaire.version`
| | | **`Questionnaire.name`**| _Equivalent_<br/>(17701/17702)| `Questionnaire.name`| _Equivalent_<br/>(32095/32096)| `Questionnaire.name`| _Equivalent_<br/>(46665/46666)| `Questionnaire.name`
| | | **`Questionnaire.title`**| _Equivalent_<br/>(17703/17704)| `Questionnaire.title`| _Equivalent_<br/>(32097/32098)| `Questionnaire.title`| _Equivalent_<br/>(46667/46668)| `Questionnaire.title`
| `Questionnaire.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7518)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7519)| **`Questionnaire.status`**| _Equivalent_<br/>(17705/17706)| `Questionnaire.status`| _Equivalent_<br/>(32101/32102)| `Questionnaire.status`| _Equivalent_<br/>(46671/46672)| `Questionnaire.status`
| | | **`Questionnaire.experimental`**| _Equivalent_<br/>(17707/17708)| `Questionnaire.experimental`| _Equivalent_<br/>(32103/32104)| `Questionnaire.experimental`| _Equivalent_<br/>(46673/46674)| `Questionnaire.experimental`
| `Questionnaire.date`| _Equivalent_<br/>(7520/7521)| **`Questionnaire.date`**| _Equivalent_<br/>(17709/17710)| `Questionnaire.date`| _Equivalent_<br/>(32107/32108)| `Questionnaire.date`| _Equivalent_<br/>(46677/46678)| `Questionnaire.date`
| `Questionnaire.publisher`| _Equivalent_<br/>(7522/7523)| **`Questionnaire.publisher`**| _Equivalent_<br/>(17711/17712)| `Questionnaire.publisher`| _Equivalent_<br/>(32109/32110)| `Questionnaire.publisher`| _Equivalent_<br/>(46679/46680)| `Questionnaire.publisher`
| | | **`Questionnaire.description`**| _Equivalent_<br/>(17713/17714)| `Questionnaire.description`| _Equivalent_<br/>(32113/32114)| `Questionnaire.description`| _Equivalent_<br/>(46683/46684)| `Questionnaire.description`
| | | **`Questionnaire.purpose`**| _Equivalent_<br/>(17715/17716)| `Questionnaire.purpose`| _Equivalent_<br/>(32119/32120)| `Questionnaire.purpose`| _Equivalent_<br/>(46689/46690)| `Questionnaire.purpose`
| | | **`Questionnaire.approvalDate`**| _Equivalent_<br/>(17717/17718)| `Questionnaire.approvalDate`| _Equivalent_<br/>(32123/32124)| `Questionnaire.approvalDate`| _Equivalent_<br/>(46693/46694)| `Questionnaire.approvalDate`
| | | **`Questionnaire.lastReviewDate`**| _Equivalent_<br/>(17719/17720)| `Questionnaire.lastReviewDate`| _Equivalent_<br/>(32125/32126)| `Questionnaire.lastReviewDate`| _Equivalent_<br/>(46695/46696)| `Questionnaire.lastReviewDate`
| | | **`Questionnaire.effectivePeriod`**| _Equivalent_<br/>(17721/17722)| `Questionnaire.effectivePeriod`| _Equivalent_<br/>(32127/32128)| `Questionnaire.effectivePeriod`| _Equivalent_<br/>(46697/46698)| `Questionnaire.effectivePeriod`
| | | **`Questionnaire.useContext`**| _Equivalent_<br/>(17723/17724)| `Questionnaire.useContext`| _Equivalent_<br/>(32115/32116)| `Questionnaire.useContext`| _Equivalent_<br/>(46685/46686)| `Questionnaire.useContext`
| | | **`Questionnaire.jurisdiction`**| _Equivalent_<br/>(17725/17726)| `Questionnaire.jurisdiction`| _Equivalent_<br/>(32117/32118)| `Questionnaire.jurisdiction`| _Equivalent_<br/>(46687/46688)| `Questionnaire.jurisdiction`
| `Questionnaire.telecom`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(380)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(708)| **`Questionnaire.contact`**| _Equivalent_<br/>(17727/17728)| `Questionnaire.contact`| _Equivalent_<br/>(32111/32112)| `Questionnaire.contact`| _Equivalent_<br/>(46681/46682)| `Questionnaire.contact`
| | | **`Questionnaire.copyright`**| _Equivalent_<br/>(17729/17730)| `Questionnaire.copyright`| _Equivalent_<br/>(32121/32122)| `Questionnaire.copyright`| _Equivalent_<br/>(46691/46692)| `Questionnaire.copyright`
| | | **`Questionnaire.code`**| _Equivalent_<br/>(17731/17732)| `Questionnaire.code`| _Equivalent_<br/>(32129/32130)| `Questionnaire.code`| _Equivalent_<br/>(46699/46700)| `Questionnaire.code`
| `Questionnaire.subjectType`| →→→→ _Equivalent_ →→→→ <br/>(7524)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7525)| **`Questionnaire.subjectType`**| →→→→ _Equivalent_ →→→→ <br/>(17733)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17734)| `Questionnaire.subjectType`| →→→→ _Equivalent_ →→→→ <br/>(32105)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(32106)| `Questionnaire.subjectType`| →→→→ _Equivalent_ →→→→ <br/>(46675)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(46676)| `Questionnaire.subjectType`
| `Questionnaire.group`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(362)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(710)| **`Questionnaire.item`**| _Equivalent_<br/>(17735/17736)| `Questionnaire.item`| _Equivalent_<br/>(32131/32132)| `Questionnaire.item`| _Equivalent_<br/>(46701/46702)| `Questionnaire.item`
| `Questionnaire.group.question`| →→→→ _Equivalent_ →→→→ <br/>(366)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(710)| **`Questionnaire.item`**| _Equivalent_<br/>(17735/17736)| `Questionnaire.item`| _Equivalent_<br/>(32131/32132)| `Questionnaire.item`| _Equivalent_<br/>(46701/46702)| `Questionnaire.item`
| | | **`Questionnaire.item.id`**| _Equivalent_<br/>(17737/17738)| `Questionnaire.item.id`| _Equivalent_<br/>(32133/32134)| `Questionnaire.item.id`| _Equivalent_<br/>(46703/46704)| `Questionnaire.item.id`
| | | **`Questionnaire.item.extension`**| _Equivalent_<br/>(17739/17740)| `Questionnaire.item.extension`| _Equivalent_<br/>(32135/32136)| `Questionnaire.item.extension`| _Equivalent_<br/>(46705/46706)| `Questionnaire.item.extension`
| | | **`Questionnaire.item.modifierExtension`**| _Equivalent_<br/>(17741/17742)| `Questionnaire.item.modifierExtension`| _Equivalent_<br/>(32137/32138)| `Questionnaire.item.modifierExtension`| _Equivalent_<br/>(46707/46708)| `Questionnaire.item.modifierExtension`
| `Questionnaire.group.linkId`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(365)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(716)| **`Questionnaire.item.linkId`**| _Equivalent_<br/>(17743/17744)| `Questionnaire.item.linkId`| _Equivalent_<br/>(32139/32140)| `Questionnaire.item.linkId`| _Equivalent_<br/>(46709/46710)| `Questionnaire.item.linkId`
| `Questionnaire.group.question.linkId`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(369)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(716)| **`Questionnaire.item.linkId`**| _Equivalent_<br/>(17743/17744)| `Questionnaire.item.linkId`| _Equivalent_<br/>(32139/32140)| `Questionnaire.item.linkId`| _Equivalent_<br/>(46709/46710)| `Questionnaire.item.linkId`
| | | **`Questionnaire.item.definition`**| _Equivalent_<br/>(17745/17746)| `Questionnaire.item.definition`| _Equivalent_<br/>(32141/32142)| `Questionnaire.item.definition`| _Equivalent_<br/>(46711/46712)| `Questionnaire.item.definition`
| `Questionnaire.group.concept`| →→→→ _Equivalent_ →→→→ <br/>(363)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(712)| **`Questionnaire.item.code`**| _Equivalent_<br/>(17747/17748)| `Questionnaire.item.code`| _Equivalent_<br/>(32143/32144)| `Questionnaire.item.code`| _Equivalent_<br/>(46713/46714)| `Questionnaire.item.code`
| `Questionnaire.group.question.concept`| →→→→ _Equivalent_ →→→→ <br/>(367)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(712)| **`Questionnaire.item.code`**| _Equivalent_<br/>(17747/17748)| `Questionnaire.item.code`| _Equivalent_<br/>(32143/32144)| `Questionnaire.item.code`| _Equivalent_<br/>(46713/46714)| `Questionnaire.item.code`
| | | **`Questionnaire.item.prefix`**| _Equivalent_<br/>(17749/17750)| `Questionnaire.item.prefix`| _Equivalent_<br/>(32145/32146)| `Questionnaire.item.prefix`| _Equivalent_<br/>(46715/46716)| `Questionnaire.item.prefix`
| `Questionnaire.group.text`| →→→→ _Equivalent_ →→→→ <br/>(378)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(723)| **`Questionnaire.item.text`**| _Equivalent_<br/>(17751/17752)| `Questionnaire.item.text`| _Equivalent_<br/>(32147/32148)| `Questionnaire.item.text`| _Equivalent_<br/>(46717/46718)| `Questionnaire.item.text`
| `Questionnaire.group.question.text`| →→→→ _Equivalent_ →→→→ <br/>(374)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(723)| **`Questionnaire.item.text`**| _Equivalent_<br/>(17751/17752)| `Questionnaire.item.text`| _Equivalent_<br/>(32147/32148)| `Questionnaire.item.text`| _Equivalent_<br/>(46717/46718)| `Questionnaire.item.text`
| `Questionnaire.group.question.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(375)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(725)| **`Questionnaire.item.type`**| _Equivalent_<br/>(17753/17754)| `Questionnaire.item.type`| _Equivalent_<br/>(32149/32150)| `Questionnaire.item.type`| →→→→ _Equivalent_ →→→→ <br/>(1938)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2175)| `Questionnaire.item.type`
| `Questionnaire.group.question.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(375)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(725)| **`Questionnaire.item.type`**| _Equivalent_<br/>(17753/17754)| `Questionnaire.item.type`| _Equivalent_<br/>(32149/32150)| `Questionnaire.item.type`| →→→→ _Equivalent_ →→→→ <br/>(1938)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2175)| `Questionnaire.item.answerConstraint`
| | | **`Questionnaire.item.enableWhen`**| _Equivalent_<br/>(17755/17756)| `Questionnaire.item.enableWhen`| _Equivalent_<br/>(32151/32152)| `Questionnaire.item.enableWhen`| _Equivalent_<br/>(46719/46720)| `Questionnaire.item.enableWhen`
| | | **`Questionnaire.item.enableWhen.id`**| _Equivalent_<br/>(17757/17758)| `Questionnaire.item.enableWhen.id`| _Equivalent_<br/>(32153/32154)| `Questionnaire.item.enableWhen.id`| _Equivalent_<br/>(46721/46722)| `Questionnaire.item.enableWhen.id`
| | | **`Questionnaire.item.enableWhen.extension`**| _Equivalent_<br/>(17759/17760)| `Questionnaire.item.enableWhen.extension`| _Equivalent_<br/>(32155/32156)| `Questionnaire.item.enableWhen.extension`| _Equivalent_<br/>(46723/46724)| `Questionnaire.item.enableWhen.extension`
| | | **`Questionnaire.item.enableWhen.modifierExtension`**| _Equivalent_<br/>(17761/17762)| `Questionnaire.item.enableWhen.modifierExtension`| _Equivalent_<br/>(32157/32158)| `Questionnaire.item.enableWhen.modifierExtension`| _Equivalent_<br/>(46725/46726)| `Questionnaire.item.enableWhen.modifierExtension`
| | | **`Questionnaire.item.enableWhen.question`**| _Equivalent_<br/>(17763/17764)| `Questionnaire.item.enableWhen.question`| _Equivalent_<br/>(32159/32160)| `Questionnaire.item.enableWhen.question`| _Equivalent_<br/>(46727/46728)| `Questionnaire.item.enableWhen.question`
| | | **`Questionnaire.item.enableWhen.hasAnswer`**| →→→→ _RelatedTo_ →→→→ <br/>(1247)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1650)| `Questionnaire.item.enableWhen.operator`| _Equivalent_<br/>(32161/32162)| `Questionnaire.item.enableWhen.operator`| _Equivalent_<br/>(46729/46730)| `Questionnaire.item.enableWhen.operator`
| | | **`Questionnaire.item.enableWhen.hasAnswer`**| →→→→ _RelatedTo_ →→→→ <br/>(1247)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1650)| `Questionnaire.item.enableWhen.answer[x]`| _Equivalent_<br/>(32163/32164)| `Questionnaire.item.enableWhen.answer[x]`| _Equivalent_<br/>(46731/46732)| `Questionnaire.item.enableWhen.answer[x]`
| | | **`Questionnaire.item.enableWhen.answer[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1252)<hr/>←←←← _RelatedTo_ ←←←← <br/>(17765)| `Questionnaire.item.enableWhen.operator`| _Equivalent_<br/>(32161/32162)| `Questionnaire.item.enableWhen.operator`| _Equivalent_<br/>(46729/46730)| `Questionnaire.item.enableWhen.operator`
| `Questionnaire.group.required`| →→→→ _Equivalent_ →→→→ <br/>(377)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(721)| **`Questionnaire.item.required`**| _Equivalent_<br/>(17766/17767)| `Questionnaire.item.required`| _Equivalent_<br/>(32167/32168)| `Questionnaire.item.required`| _Equivalent_<br/>(46735/46736)| `Questionnaire.item.required`
| `Questionnaire.group.question.required`| →→→→ _Equivalent_ →→→→ <br/>(373)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(721)| **`Questionnaire.item.required`**| _Equivalent_<br/>(17766/17767)| `Questionnaire.item.required`| _Equivalent_<br/>(32167/32168)| `Questionnaire.item.required`| _Equivalent_<br/>(46735/46736)| `Questionnaire.item.required`
| `Questionnaire.group.repeats`| →→→→ _Equivalent_ →→→→ <br/>(376)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(719)| **`Questionnaire.item.repeats`**| _Equivalent_<br/>(17768/17769)| `Questionnaire.item.repeats`| _Equivalent_<br/>(32169/32170)| `Questionnaire.item.repeats`| _Equivalent_<br/>(46737/46738)| `Questionnaire.item.repeats`
| `Questionnaire.group.question.repeats`| →→→→ _Equivalent_ →→→→ <br/>(372)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(719)| **`Questionnaire.item.repeats`**| _Equivalent_<br/>(17768/17769)| `Questionnaire.item.repeats`| _Equivalent_<br/>(32169/32170)| `Questionnaire.item.repeats`| _Equivalent_<br/>(46737/46738)| `Questionnaire.item.repeats`
| | | **`Questionnaire.item.readOnly`**| _Equivalent_<br/>(17770/17771)| `Questionnaire.item.readOnly`| _Equivalent_<br/>(32171/32172)| `Questionnaire.item.readOnly`| _Equivalent_<br/>(46739/46740)| `Questionnaire.item.readOnly`
| | | **`Questionnaire.item.maxLength`**| _Equivalent_<br/>(17772/17773)| `Questionnaire.item.maxLength`| _Equivalent_<br/>(32173/32174)| `Questionnaire.item.maxLength`| _Equivalent_<br/>(46741/46742)| `Questionnaire.item.maxLength`
| `Questionnaire.group.question.options`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(371)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(718)| **`Questionnaire.item.options`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1251)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1647)| `Questionnaire.item.answerValueSet`| _Equivalent_<br/>(32175/32176)| `Questionnaire.item.answerValueSet`| _Equivalent_<br/>(46743/46744)| `Questionnaire.item.answerValueSet`
| `Questionnaire.group.question.option`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(370)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(717)| **`Questionnaire.item.option`**| _Equivalent_<br/>(1249/1645)| `Questionnaire.item.answerOption`| _Equivalent_<br/>(32177/32178)| `Questionnaire.item.answerOption`| _Equivalent_<br/>(46745/46746)| `Questionnaire.item.answerOption`
| | | **`Questionnaire.item.option.id`**| | | | | | | 
| | | **`Questionnaire.item.option.extension`**| | | | | | | 
| | | **`Questionnaire.item.option.modifierExtension`**| | | | | | | 
| | | **`Questionnaire.item.option.value[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1250)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1646)| `Questionnaire.item.answerOption.value[x]`| _Equivalent_<br/>(32185/32186)| `Questionnaire.item.answerOption.value[x]`| _Equivalent_<br/>(46753/46754)| `Questionnaire.item.answerOption.value[x]`
| | | **`Questionnaire.item.initial[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1248)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1649)| `Questionnaire.item.initial`| _Equivalent_<br/>(32189/32190)| `Questionnaire.item.initial`| _Equivalent_<br/>(46757/46758)| `Questionnaire.item.initial`
| `Questionnaire.group.group`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(364)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(714)| **`Questionnaire.item.item`**| _Equivalent_<br/>(17777/17778)| `Questionnaire.item.item`| _Equivalent_<br/>(32199/32200)| `Questionnaire.item.item`| _Equivalent_<br/>(46767/46768)| `Questionnaire.item.item`
| `Questionnaire.group.question.group`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(368)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(714)| **`Questionnaire.item.item`**| _Equivalent_<br/>(17777/17778)| `Questionnaire.item.item`| _Equivalent_<br/>(32199/32200)| `Questionnaire.item.item`| _Equivalent_<br/>(46767/46768)| `Questionnaire.item.item`
| *33 of 40 elements used* | | *58 of 58 elements used* | | *55 of 65 elements used* | | *55 of 65 elements used* | | *56 of 69 elements used* 

