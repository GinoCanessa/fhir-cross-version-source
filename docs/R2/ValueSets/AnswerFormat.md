Comparison of 
Generated at Monday, April 14, 2025 6:17:15 PM

### AnswerFormat

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | AnswerFormat |
| Canonical URL | `http://hl7.org/fhir/ValueSet/answer-format` |
| Version | 1.0.2 |
| Description | The expected format of an answer. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `20` |
| Database Concept Count | `15` |
| Database Active Concept Count | `15` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Questionnaire` | `Questionnaire.group.question.type` | `http://hl7.org/fhir/ValueSet/answer-format` | `Required` | boolean \| decimal \| integer \| date \| dateTime + |

### Referenced Systems

* `http://hl7.org/fhir/answer-format`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [AnswerFormat](/docs/R2/ValueSets/AnswerFormat.md)<br/> `http://hl7.org/fhir/ValueSet/answer-format\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `127`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `285`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [QuestionnaireItemType](/docs/R3/ValueSets/QuestionnaireItemType.md)<br/> `http://hl7.org/fhir/ValueSet/item-type\|3.0.2` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `486`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `709`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `True`<br/>←←←←←←←| [QuestionnaireItemType](/docs/R4/ValueSets/QuestionnaireItemType.md)<br/> `http://hl7.org/fhir/ValueSet/item-type\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1559`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1560`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [QuestionnaireItemType](/docs/R4B/ValueSets/QuestionnaireItemType.md)<br/> `http://hl7.org/fhir/ValueSet/item-type\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `970`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1231`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [QuestionnaireItemType](/docs/R5/ValueSets/QuestionnaireItemType.md)<br/> `http://hl7.org/fhir/ValueSet/item-type\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set AnswerFormat from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 AnswerFormat| Relationship | [R3 QuestionnaireItemType](/docs/R3/ValueSets/QuestionnaireItemType.md)| Relationship | [R4 QuestionnaireItemType](/docs/R4/ValueSets/QuestionnaireItemType.md)| Relationship | [R4B QuestionnaireItemType](/docs/R4B/ValueSets/QuestionnaireItemType.md)| Relationship | [R5 QuestionnaireItemType](/docs/R5/ValueSets/QuestionnaireItemType.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/answer-format`
| **`boolean`**| _Equivalent_ <br/>(1078/2485)| `boolean`| _Equivalent_ <br/>(4543/6853)| `boolean`| _Equivalent_ <br/>(16330/16331)| `boolean`| _Equivalent_ <br/>(9263/11580)| `boolean`
| **`decimal`**| _Equivalent_ <br/>(1083/2490)| `decimal`| _Equivalent_ <br/>(4547/6857)| `decimal`| _Equivalent_ <br/>(16332/16333)| `decimal`| _Equivalent_ <br/>(9267/11585)| `decimal`
| **`integer`**| _Equivalent_ <br/>(1074/2493)| `integer`| _Equivalent_ <br/>(4540/6850)| `integer`| _Equivalent_ <br/>(16334/16335)| `integer`| _Equivalent_ <br/>(9260/11588)| `integer`
| **`date`**| _Equivalent_ <br/>(1069/2487)| `date`| _Equivalent_ <br/>(4534/6844)| `date`| _Equivalent_ <br/>(16336/16337)| `date`| _Equivalent_ <br/>(9254/11583)| `date`
| **`dateTime`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1070)<hr/>←←←← _Equivalent_ ←←←← <br/>(2488) | `dateTime`| _Equivalent_ <br/>(4535/6845)| `dateTime`| _Equivalent_ <br/>(16338/16339)| `dateTime`| _Equivalent_ <br/>(9255/11584)| `dateTime`
| **`instant`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1076)<hr/>←←←← _Equivalent_ ←←←← <br/>(2489) | `dateTime`| _Equivalent_ <br/>(4535/6845)| `dateTime`| _Equivalent_ <br/>(16338/16339)| `dateTime`| _Equivalent_ <br/>(9255/11584)| `dateTime`
| **`time`**| _Equivalent_ <br/>(1080/2499)| `time`| _Equivalent_ <br/>(4545/6855)| `time`| _Equivalent_ <br/>(16340/16341)| `time`| _Equivalent_ <br/>(9265/11593)| `time`
| **`string`**| _Equivalent_ <br/>(1072/2497)| `string`| _Equivalent_ <br/>(4537/6847)| `string`| _Equivalent_ <br/>(16342/16343)| `string`| _Equivalent_ <br/>(9257/11591)| `string`
| **`text`**| →→→→ _Equivalent_ →→→→ <br/>(1082)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2491) | `display`| _Equivalent_ <br/>(4539/6849)| `display`| _Equivalent_ <br/>(16328/16329)| `display`| _Equivalent_ <br/>(9259/11586)| `display`
| **`text`**| →→→→ _Equivalent_ →→→→ <br/>(1081)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2498) | `text`| _Equivalent_ <br/>(4546/6856)| `text`| _Equivalent_ <br/>(16344/16345)| `text`| _Equivalent_ <br/>(9266/11592)| `text`
| **`url`**| _Equivalent_ <br/>(1075/2500)| `url`| _Equivalent_ <br/>(4541/6851)| `url`| _Equivalent_ <br/>(16346/16347)| `url`| _Equivalent_ <br/>(9261/11594)| `url`
| **`choice`**| _Equivalent_ <br/>(1084/2486)| `choice`| _Equivalent_ <br/>(4548/6858)| `choice`| _Equivalent_ <br/>(16348/16349)| `choice`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9268)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11581) | `coding`
| **`open-choice`**| _Equivalent_ <br/>(1073/2494)| `open-choice`| _Equivalent_ <br/>(4538/6848)| `open-choice`| _Equivalent_ <br/>(16350/16351)| `open-choice`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9258)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(11582) | `coding`
| **`attachment`**| _Equivalent_ <br/>(1079/2484)| `attachment`| _Equivalent_ <br/>(4544/6854)| `attachment`| _Equivalent_ <br/>(16352/16353)| `attachment`| _Equivalent_ <br/>(9264/11579)| `attachment`
| **`reference`**| _Equivalent_ <br/>(1077/2496)| `reference`| _Equivalent_ <br/>(4542/6852)| `reference`| _Equivalent_ <br/>(16354/16355)| `reference`| _Equivalent_ <br/>(9262/11590)| `reference`
| **`quantity`**| _Equivalent_ <br/>(1071/2495)| `quantity`| _Equivalent_ <br/>(4536/6846)| `quantity`| _Equivalent_ <br/>(16356/16357)| `quantity`| _Equivalent_ <br/>(9256/11589)| `quantity`
| *15 of 15 codes used* | | *15 of 16 codes used* <br/>remaining codes:<br/>`group`| | *15 of 16 codes used* <br/>remaining codes:<br/>`group`| | *15 of 17 codes used* <br/>remaining codes:<br/>`group`| | *14 of 16 codes used* <br/>remaining codes:<br/>`group`

