Comparison of 
Generated at Thursday, April 3, 2025 8:18:13 AM

### DiagnosticReport

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | DiagnosticReport |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/DiagnosticReport` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for DiagnosticReport Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `510` |
| Database Snapshot Count | `36` |
| Database Differential Count | `22` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `DiagnosticReport` | `DiagnosticReport` | `DiagnosticReport` | DiagnosticReport | A Diagnostic report - a combination of request information, atomic results, images, interpretation, as well as formatted reports | 0..* | DiagnosticReport |  |  |
| `DiagnosticReport.basedOn` | `DiagnosticReport.basedOn` | `basedOn` |  | What was requested | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/CarePlan), Reference(http://hl7.org/fhir/StructureDefinition/ImmunizationRecommendation), Reference(http://hl7.org/fhir/StructureDefinition/MedicationRequest), Reference(http://hl7.org/fhir/StructureDefinition/NutritionOrder), Reference(http://hl7.org/fhir/StructureDefinition/ProcedureRequest), Reference(http://hl7.org/fhir/StructureDefinition/ReferralRequest) |  |  |
| `DiagnosticReport.category` | `DiagnosticReport.category` | `category` |  | Service category | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/diagnostic-service-sections` |
| `DiagnosticReport.code` | `DiagnosticReport.code` | `code` |  | Name/Code for this diagnostic report | 1..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/report-codes` |
| `DiagnosticReport.codedDiagnosis` | `DiagnosticReport.codedDiagnosis` | `codedDiagnosis` |  | Codes for the conclusion | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/clinical-findings` |
| `DiagnosticReport.conclusion` | `DiagnosticReport.conclusion` | `conclusion` |  | Clinical Interpretation of test results | 0..1 | string |  |  |
| `DiagnosticReport.contained` | `DiagnosticReport.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `DiagnosticReport.context` | `DiagnosticReport.context` | `context` |  | Health care event when test ordered | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter), Reference(http://hl7.org/fhir/StructureDefinition/EpisodeOfCare) |  |  |
| `DiagnosticReport.effective[x]` | `DiagnosticReport.effective[x]` | `effective[x]` |  | Clinically relevant time/time-period for report | 0..1 | dateTime, Period |  |  |
| `DiagnosticReport.extension` | `DiagnosticReport.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `DiagnosticReport.id` | `DiagnosticReport.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `DiagnosticReport.identifier` | `DiagnosticReport.identifier` | `identifier` |  | Business identifier for report | 0..* | Identifier |  |  |
| `DiagnosticReport.image` | `DiagnosticReport.image` | `image` |  | Key images associated with this report | 0..* | BackboneElement |  |  |
| `DiagnosticReport.image.comment` | `DiagnosticReport.image.comment` | `comment` |  | Comment about the image (e.g. explanation) | 0..1 | string |  |  |
| `DiagnosticReport.image.extension` | `DiagnosticReport.image.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `DiagnosticReport.image.id` | `DiagnosticReport.image.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `DiagnosticReport.image.link` | `DiagnosticReport.image.link` | `link` |  | Reference to the image source | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Media) |  |  |
| `DiagnosticReport.image.modifierExtension` | `DiagnosticReport.image.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DiagnosticReport.imagingStudy` | `DiagnosticReport.imagingStudy` | `imagingStudy` |  | Reference to full details of imaging associated with the diagnostic report | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ImagingManifest), Reference(http://hl7.org/fhir/StructureDefinition/ImagingStudy) |  |  |
| `DiagnosticReport.implicitRules` | `DiagnosticReport.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `DiagnosticReport.issued` | `DiagnosticReport.issued` | `issued` |  | DateTime this version was released | 0..1 | instant |  |  |
| `DiagnosticReport.language` | `DiagnosticReport.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `DiagnosticReport.meta` | `DiagnosticReport.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `DiagnosticReport.modifierExtension` | `DiagnosticReport.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DiagnosticReport.performer` | `DiagnosticReport.performer` | `performer` |  | Participants in producing the report | 0..* | BackboneElement |  |  |
| `DiagnosticReport.performer.actor` | `DiagnosticReport.performer.actor` | `actor` |  | Practitioner or Organization  participant | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `DiagnosticReport.performer.extension` | `DiagnosticReport.performer.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `DiagnosticReport.performer.id` | `DiagnosticReport.performer.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `DiagnosticReport.performer.modifierExtension` | `DiagnosticReport.performer.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DiagnosticReport.performer.role` | `DiagnosticReport.performer.role` | `role` |  | Type of performer | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/performer-role` |
| `DiagnosticReport.presentedForm` | `DiagnosticReport.presentedForm` | `presentedForm` |  | Entire report as issued | 0..* | Attachment |  |  |
| `DiagnosticReport.result` | `DiagnosticReport.result` | `result` |  | Observations - simple, or complex nested groups | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Observation) |  |  |
| `DiagnosticReport.specimen` | `DiagnosticReport.specimen` | `specimen` |  | Specimens this report is based on | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Specimen) |  |  |
| `DiagnosticReport.status` | `DiagnosticReport.status` | `status` |  | registered \| partial \| preliminary \| final + | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/diagnostic-report-status` |
| `DiagnosticReport.subject` | `DiagnosticReport.subject` | `subject` |  | The subject of the report - usually, but not always, the patient | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `DiagnosticReport.text` | `DiagnosticReport.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DiagnosticReport](/docs/R2/Resources/DiagnosticReport.md)<br/> `http://hl7.org/fhir/StructureDefinition/DiagnosticReport\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `103`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `269`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DiagnosticReport](/docs/R3/Resources/DiagnosticReport.md)<br/> `http://hl7.org/fhir/StructureDefinition/DiagnosticReport\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `451`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `646`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DiagnosticReport](/docs/R4/Resources/DiagnosticReport.md)<br/> `http://hl7.org/fhir/StructureDefinition/DiagnosticReport\|4.0.1` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1465`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1466`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DiagnosticReport](/docs/R4B/Resources/DiagnosticReport.md)<br/> `http://hl7.org/fhir/StructureDefinition/DiagnosticReport\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `967`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1196`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DiagnosticReport](/docs/R5/Resources/DiagnosticReport.md)<br/> `http://hl7.org/fhir/StructureDefinition/DiagnosticReport\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition DiagnosticReport from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 DiagnosticReport](/docs/R2/Resources/DiagnosticReport.md)| Relationship | R3 DiagnosticReport| Relationship | [R4 DiagnosticReport](/docs/R4/Resources/DiagnosticReport.md)| Relationship | [R4B DiagnosticReport](/docs/R4B/Resources/DiagnosticReport.md)| Relationship | [R5 DiagnosticReport](/docs/R5/Resources/DiagnosticReport.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `DiagnosticReport`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4706)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4707)| **`DiagnosticReport`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(13110)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(13111)| `DiagnosticReport`| _Equivalent_<br/>(25922/25923)| `DiagnosticReport`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(40772)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40773)| `DiagnosticReport`
| `DiagnosticReport.id`| _Equivalent_<br/>(4708/4709)| **`DiagnosticReport.id`**| _Equivalent_<br/>(13112/13113)| `DiagnosticReport.id`| _Equivalent_<br/>(25924/25925)| `DiagnosticReport.id`| _Equivalent_<br/>(40774/40775)| `DiagnosticReport.id`
| `DiagnosticReport.meta`| _Equivalent_<br/>(4710/4711)| **`DiagnosticReport.meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13114)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13115)| `DiagnosticReport.meta`| _Equivalent_<br/>(25926/25927)| `DiagnosticReport.meta`| _Equivalent_<br/>(40776/40777)| `DiagnosticReport.meta`
| `DiagnosticReport.implicitRules`| _Equivalent_<br/>(4712/4713)| **`DiagnosticReport.implicitRules`**| _Equivalent_<br/>(13116/13117)| `DiagnosticReport.implicitRules`| _Equivalent_<br/>(25928/25929)| `DiagnosticReport.implicitRules`| _Equivalent_<br/>(40778/40779)| `DiagnosticReport.implicitRules`
| `DiagnosticReport.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4714)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4715)| **`DiagnosticReport.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13118)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(13119)| `DiagnosticReport.language`| _Equivalent_<br/>(25930/25931)| `DiagnosticReport.language`| _Equivalent_<br/>(40780/40781)| `DiagnosticReport.language`
| `DiagnosticReport.text`| _Equivalent_<br/>(4716/4717)| **`DiagnosticReport.text`**| _Equivalent_<br/>(13120/13121)| `DiagnosticReport.text`| _Equivalent_<br/>(25932/25933)| `DiagnosticReport.text`| _Equivalent_<br/>(40782/40783)| `DiagnosticReport.text`
| `DiagnosticReport.contained`| _Equivalent_<br/>(4718/4719)| **`DiagnosticReport.contained`**| _Equivalent_<br/>(13122/13123)| `DiagnosticReport.contained`| _Equivalent_<br/>(25934/25935)| `DiagnosticReport.contained`| _Equivalent_<br/>(40784/40785)| `DiagnosticReport.contained`
| `DiagnosticReport.extension`| _Equivalent_<br/>(4720/4721)| **`DiagnosticReport.extension`**| _Equivalent_<br/>(13124/13125)| `DiagnosticReport.extension`| _Equivalent_<br/>(25936/25937)| `DiagnosticReport.extension`| _Equivalent_<br/>(40786/40787)| `DiagnosticReport.extension`
| `DiagnosticReport.modifierExtension`| _Equivalent_<br/>(4722/4723)| **`DiagnosticReport.modifierExtension`**| _Equivalent_<br/>(13126/13127)| `DiagnosticReport.modifierExtension`| _Equivalent_<br/>(25938/25939)| `DiagnosticReport.modifierExtension`| _Equivalent_<br/>(40788/40789)| `DiagnosticReport.modifierExtension`
| `DiagnosticReport.identifier`| _Equivalent_<br/>(4724/4725)| **`DiagnosticReport.identifier`**| _Equivalent_<br/>(13128/13129)| `DiagnosticReport.identifier`| _Equivalent_<br/>(25940/25941)| `DiagnosticReport.identifier`| _Equivalent_<br/>(40790/40791)| `DiagnosticReport.identifier`
| `DiagnosticReport.request`| →→→→ _RelatedTo_ →→→→ <br/>(205)<hr/>←←←← _RelatedTo_ ←←←← <br/>(603)| **`DiagnosticReport.basedOn`**| →→→→ _RelatedTo_ →→→→ <br/>(13130)<hr/>←←←← _RelatedTo_ ←←←← <br/>(13131)| `DiagnosticReport.basedOn`| _Equivalent_<br/>(25942/25943)| `DiagnosticReport.basedOn`| _Equivalent_<br/>(40792/40793)| `DiagnosticReport.basedOn`
| `DiagnosticReport.status`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4726)<hr/>←←←← _RelatedTo_ ←←←← <br/>(4727)| **`DiagnosticReport.status`**| _Equivalent_<br/>(13132/13133)| `DiagnosticReport.status`| _Equivalent_<br/>(25944/25945)| `DiagnosticReport.status`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(40794)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(40795)| `DiagnosticReport.status`
| `DiagnosticReport.category`| _Equivalent_<br/>(4728/4729)| **`DiagnosticReport.category`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13134)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13135)| `DiagnosticReport.category`| _Equivalent_<br/>(25946/25947)| `DiagnosticReport.category`| _Equivalent_<br/>(40796/40797)| `DiagnosticReport.category`
| `DiagnosticReport.code`| _Equivalent_<br/>(4730/4731)| **`DiagnosticReport.code`**| _Equivalent_<br/>(13136/13137)| `DiagnosticReport.code`| _Equivalent_<br/>(25948/25949)| `DiagnosticReport.code`| _Equivalent_<br/>(40798/40799)| `DiagnosticReport.code`
| `DiagnosticReport.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4732)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4733)| **`DiagnosticReport.subject`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13138)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13139)| `DiagnosticReport.subject`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(25950)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(25951)| `DiagnosticReport.subject`| →→→→ _RelatedTo_ →→→→ <br/>(40800)<hr/>←←←← _RelatedTo_ ←←←← <br/>(40801)| `DiagnosticReport.subject`
| `DiagnosticReport.encounter`| →→→→ _RelatedTo_ →→→→ <br/>(204)<hr/>←←←← _RelatedTo_ ←←←← <br/>(604)| **`DiagnosticReport.context`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1002)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1486)| `DiagnosticReport.encounter`| _Equivalent_<br/>(25952/25953)| `DiagnosticReport.encounter`| _Equivalent_<br/>(40802/40803)| `DiagnosticReport.encounter`
| `DiagnosticReport.effective[x]`| →→→→ _Equivalent_ →→→→ <br/>(4734)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4735)| **`DiagnosticReport.effective[x]`**| _Equivalent_<br/>(13140/13141)| `DiagnosticReport.effective[x]`| _Equivalent_<br/>(25954/25955)| `DiagnosticReport.effective[x]`| _Equivalent_<br/>(40804/40805)| `DiagnosticReport.effective[x]`
| `DiagnosticReport.issued`| →→→→ _Equivalent_ →→→→ <br/>(4736)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4737)| **`DiagnosticReport.issued`**| _Equivalent_<br/>(13142/13143)| `DiagnosticReport.issued`| _Equivalent_<br/>(25956/25957)| `DiagnosticReport.issued`| _Equivalent_<br/>(40806/40807)| `DiagnosticReport.issued`
| `DiagnosticReport.performer`| →→→→ _RelatedTo_ →→→→ <br/>(4738)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4739)| **`DiagnosticReport.performer`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(13144)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13145)| `DiagnosticReport.performer`| _Equivalent_<br/>(25958/25959)| `DiagnosticReport.performer`| _Equivalent_<br/>(40808/40809)| `DiagnosticReport.performer`
| | | **`DiagnosticReport.performer.id`**| | | | | | | 
| | | **`DiagnosticReport.performer.extension`**| | | | | | | 
| | | **`DiagnosticReport.performer.modifierExtension`**| | | | | | | 
| | | **`DiagnosticReport.performer.role`**| | | | | | | 
| | | **`DiagnosticReport.performer.actor`**| →→→→ _RelatedTo_ →→→→ <br/>(1006)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1490)| `DiagnosticReport.performer`| _Equivalent_<br/>(25958/25959)| `DiagnosticReport.performer`| _Equivalent_<br/>(40808/40809)| `DiagnosticReport.performer`
| `DiagnosticReport.specimen`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4740)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4741)| **`DiagnosticReport.specimen`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13149)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13150)| `DiagnosticReport.specimen`| _Equivalent_<br/>(25962/25963)| `DiagnosticReport.specimen`| _Equivalent_<br/>(40812/40813)| `DiagnosticReport.specimen`
| `DiagnosticReport.result`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4742)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4743)| **`DiagnosticReport.result`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13151)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13152)| `DiagnosticReport.result`| _Equivalent_<br/>(25964/25965)| `DiagnosticReport.result`| _Equivalent_<br/>(40814/40815)| `DiagnosticReport.result`
| `DiagnosticReport.imagingStudy`| →→→→ _RelatedTo_ →→→→ <br/>(4744)<hr/>←←←← _RelatedTo_ ←←←← <br/>(4745)| **`DiagnosticReport.imagingStudy`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13153)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13154)| `DiagnosticReport.imagingStudy`| _Equivalent_<br/>(25966/25967)| `DiagnosticReport.imagingStudy`| | | 
| `DiagnosticReport.image`| _Equivalent_<br/>(4746/4747)| **`DiagnosticReport.image`**| _Equivalent_<br/>(1003/1487)| `DiagnosticReport.media`| _Equivalent_<br/>(25968/25969)| `DiagnosticReport.media`| _Equivalent_<br/>(40817/40818)| `DiagnosticReport.media`
| `DiagnosticReport.image.id`| _Equivalent_<br/>(4748/4749)| **`DiagnosticReport.image.id`**| | | | | | | 
| `DiagnosticReport.image.extension`| _Equivalent_<br/>(4750/4751)| **`DiagnosticReport.image.extension`**| | | | | | | 
| `DiagnosticReport.image.modifierExtension`| _Equivalent_<br/>(4752/4753)| **`DiagnosticReport.image.modifierExtension`**| | | | | | | 
| `DiagnosticReport.image.comment`| _Equivalent_<br/>(4754/4755)| **`DiagnosticReport.image.comment`**| _Equivalent_<br/>(1004/1488)| `DiagnosticReport.media.comment`| _Equivalent_<br/>(25976/25977)| `DiagnosticReport.media.comment`| _Equivalent_<br/>(40825/40826)| `DiagnosticReport.media.comment`
| `DiagnosticReport.image.link`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4756)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4757)| **`DiagnosticReport.image.link`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1005)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1489)| `DiagnosticReport.media.link`| _Equivalent_<br/>(25978/25979)| `DiagnosticReport.media.link`| →→→→ _RelatedTo_ →→→→ <br/>(40827)<hr/>←←←← _RelatedTo_ ←←←← <br/>(40828)| `DiagnosticReport.media.link`
| `DiagnosticReport.conclusion`| _Equivalent_<br/>(4758/4759)| **`DiagnosticReport.conclusion`**| _Equivalent_<br/>(13158/13159)| `DiagnosticReport.conclusion`| _Equivalent_<br/>(25980/25981)| `DiagnosticReport.conclusion`| _Equivalent_<br/>(40829/40830)| `DiagnosticReport.conclusion`
| `DiagnosticReport.codedDiagnosis`| _Equivalent_<br/>(4760/4761)| **`DiagnosticReport.codedDiagnosis`**| _Equivalent_<br/>(1001/1485)| `DiagnosticReport.conclusionCode`| _Equivalent_<br/>(25982/25983)| `DiagnosticReport.conclusionCode`| _Equivalent_<br/>(40831/40832)| `DiagnosticReport.conclusionCode`
| `DiagnosticReport.presentedForm`| _Equivalent_<br/>(4762/4763)| **`DiagnosticReport.presentedForm`**| _Equivalent_<br/>(13160/13161)| `DiagnosticReport.presentedForm`| _Equivalent_<br/>(25984/25985)| `DiagnosticReport.presentedForm`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(40833)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40834)| `DiagnosticReport.presentedForm`
| *31 of 31 elements used* | | *36 of 36 elements used* | | *28 of 32 elements used* <br/>remaining elements:<br/>`DiagnosticReport.media.extension`, `DiagnosticReport.media.id`, `DiagnosticReport.media.modifierExtension`, `DiagnosticReport.resultsInterpreter`| | *28 of 32 elements used* <br/>remaining elements:<br/>`DiagnosticReport.media.extension`, `DiagnosticReport.media.id`, `DiagnosticReport.media.modifierExtension`, `DiagnosticReport.resultsInterpreter`| | *27 of 40 elements used* <br/>remaining elements:<br/>`DiagnosticReport.composition`, `DiagnosticReport.media.extension`, `DiagnosticReport.media.id`, `DiagnosticReport.media.modifierExtension`, `DiagnosticReport.note`, `DiagnosticReport.resultsInterpreter`, `DiagnosticReport.study`, `DiagnosticReport.supportingInfo`, `DiagnosticReport.supportingInfo.extension`, `DiagnosticReport.supportingInfo.id`, `DiagnosticReport.supportingInfo.modifierExtension`, `DiagnosticReport.supportingInfo.reference`, `DiagnosticReport.supportingInfo.type`

