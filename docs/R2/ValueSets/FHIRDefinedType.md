Comparison of 
Generated at Friday, April 4, 2025 2:58:32 PM

### FHIRDefinedType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| VS Name | FHIRDefinedType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/defined-types` |
| Version | 1.0.2 |
| Description | Either a resource or a data type. |
| Status | `Draft` |
| Has Escape Valve Code | `False` |
| Database Key | `114` |
| Database Concept Count | `142` |
| Database Active Concept Count | `142` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/ElementDefinition` | `ElementDefinition.type.code` | `http://hl7.org/fhir/ValueSet/defined-types` | `Required` | Name of Data type or Resource |
| `http://hl7.org/fhir/StructureDefinition/StructureDefinition` | `StructureDefinition.constrainedType` | `http://hl7.org/fhir/ValueSet/defined-types` | `Required` | Any datatype or resource, including abstract ones |
| `http://hl7.org/fhir/StructureDefinition/TestScript` | `TestScript.setup.action.operation.resource` | `http://hl7.org/fhir/ValueSet/defined-types` | `Required` | Resource type |
| `http://hl7.org/fhir/StructureDefinition/TestScript` | `TestScript.setup.action.assert.resource` | `http://hl7.org/fhir/ValueSet/defined-types` | `Required` | Resource type |

### Referenced Systems

* `http://hl7.org/fhir/data-types`
* `http://hl7.org/fhir/resource-types`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [FHIRDefinedType](/docs/R2/ValueSets/FHIRDefinedType.md)<br/> `http://hl7.org/fhir/ValueSet/defined-types\|1.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1290`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1291`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [FHIRDefinedType](/docs/R3/ValueSets/FHIRDefinedType.md)<br/> `http://hl7.org/fhir/ValueSet/defined-types\|3.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1321`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1322`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [FHIRDefinedType](/docs/R4/ValueSets/FHIRDefinedType.md)<br/> `http://hl7.org/fhir/ValueSet/defined-types\|4.0.1` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1465`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1466`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [FHIRDefinedType](/docs/R4B/ValueSets/FHIRDefinedType.md)<br/> `http://hl7.org/fhir/ValueSet/defined-types\|4.3.0` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set FHIRDefinedType from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| R2 FHIRDefinedType| Relationship | [R3 FHIRDefinedType](/docs/R3/ValueSets/FHIRDefinedType.md)| Relationship | [R4 FHIRDefinedType](/docs/R4/ValueSets/FHIRDefinedType.md)| Relationship | [R4B FHIRDefinedType](/docs/R4B/ValueSets/FHIRDefinedType.md)| Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R2** System: `http://hl7.org/fhir/data-types`
| **`Address`**| _Equivalent_ <br/>(11993/11994)| `Address`| _Equivalent_ <br/>(13204/13205)| `Address`| _Equivalent_ <br/>(15339/15340)| `Address`| | | 
| **`Age`**| _Equivalent_ <br/>(11995/11996)| `Age`| _Equivalent_ <br/>(13206/13207)| `Age`| _Equivalent_ <br/>(15341/15342)| `Age`| | | 
| **`Annotation`**| _Equivalent_ <br/>(11997/11998)| `Annotation`| _Equivalent_ <br/>(13208/13209)| `Annotation`| _Equivalent_ <br/>(15343/15344)| `Annotation`| | | 
| **`Attachment`**| _Equivalent_ <br/>(11999/12000)| `Attachment`| _Equivalent_ <br/>(13210/13211)| `Attachment`| _Equivalent_ <br/>(15345/15346)| `Attachment`| | | 
| **`BackboneElement`**| _Equivalent_ <br/>(12001/12002)| `BackboneElement`| _Equivalent_ <br/>(13212/13213)| `BackboneElement`| _Equivalent_ <br/>(15347/15348)| `BackboneElement`| | | 
| **`CodeableConcept`**| _Equivalent_ <br/>(12003/12004)| `CodeableConcept`| _Equivalent_ <br/>(13214/13215)| `CodeableConcept`| _Equivalent_ <br/>(15349/15350)| `CodeableConcept`| | | 
| **`Coding`**| _Equivalent_ <br/>(12005/12006)| `Coding`| _Equivalent_ <br/>(13216/13217)| `Coding`| _Equivalent_ <br/>(15351/15352)| `Coding`| | | 
| **`ContactPoint`**| _Equivalent_ <br/>(12007/12008)| `ContactPoint`| _Equivalent_ <br/>(13220/13221)| `ContactPoint`| _Equivalent_ <br/>(15355/15356)| `ContactPoint`| | | 
| **`Count`**| _Equivalent_ <br/>(12009/12010)| `Count`| _Equivalent_ <br/>(13224/13225)| `Count`| _Equivalent_ <br/>(15359/15360)| `Count`| | | 
| **`Distance`**| _Equivalent_ <br/>(12011/12012)| `Distance`| _Equivalent_ <br/>(13228/13229)| `Distance`| _Equivalent_ <br/>(15363/15364)| `Distance`| | | 
| **`Duration`**| _Equivalent_ <br/>(12013/12014)| `Duration`| _Equivalent_ <br/>(13232/13233)| `Duration`| _Equivalent_ <br/>(15367/15368)| `Duration`| | | 
| **`Element`**| _Equivalent_ <br/>(12015/12016)| `Element`| _Equivalent_ <br/>(13234/13235)| `Element`| _Equivalent_ <br/>(15369/15370)| `Element`| | | 
| **`ElementDefinition`**| _Equivalent_ <br/>(12017/12018)| `ElementDefinition`| _Equivalent_ <br/>(13236/13237)| `ElementDefinition`| _Equivalent_ <br/>(15371/15372)| `ElementDefinition`| | | 
| **`Extension`**| _Equivalent_ <br/>(12019/12020)| `Extension`| _Equivalent_ <br/>(13238/13239)| `Extension`| _Equivalent_ <br/>(15375/15376)| `Extension`| | | 
| **`HumanName`**| _Equivalent_ <br/>(12021/12022)| `HumanName`| _Equivalent_ <br/>(13240/13241)| `HumanName`| _Equivalent_ <br/>(15377/15378)| `HumanName`| | | 
| **`Identifier`**| _Equivalent_ <br/>(12023/12024)| `Identifier`| _Equivalent_ <br/>(13242/13243)| `Identifier`| _Equivalent_ <br/>(15379/15380)| `Identifier`| | | 
| **`Meta`**| _Equivalent_ <br/>(12025/12026)| `Meta`| _Equivalent_ <br/>(13244/13245)| `Meta`| _Equivalent_ <br/>(15383/15384)| `Meta`| | | 
| **`Money`**| _Equivalent_ <br/>(12027/12028)| `Money`| _Equivalent_ <br/>(13246/13247)| `Money`| _Equivalent_ <br/>(15385/15386)| `Money`| | | 
| **`Narrative`**| _Equivalent_ <br/>(12029/12030)| `Narrative`| _Equivalent_ <br/>(13248/13249)| `Narrative`| _Equivalent_ <br/>(15389/15390)| `Narrative`| | | 
| **`Period`**| _Equivalent_ <br/>(12031/12032)| `Period`| _Equivalent_ <br/>(13252/13253)| `Period`| _Equivalent_ <br/>(15393/15394)| `Period`| | | 
| **`Quantity`**| _Equivalent_ <br/>(12033/12034)| `Quantity`| _Equivalent_ <br/>(13254/13255)| `Quantity`| _Equivalent_ <br/>(15401/15402)| `Quantity`| | | 
| **`Range`**| _Equivalent_ <br/>(12035/12036)| `Range`| _Equivalent_ <br/>(13256/13257)| `Range`| _Equivalent_ <br/>(15403/15404)| `Range`| | | 
| **`Ratio`**| _Equivalent_ <br/>(12037/12038)| `Ratio`| _Equivalent_ <br/>(13258/13259)| `Ratio`| _Equivalent_ <br/>(15405/15406)| `Ratio`| | | 
| **`Reference`**| _Equivalent_ <br/>(12039/12040)| `Reference`| _Equivalent_ <br/>(13260/13261)| `Reference`| _Equivalent_ <br/>(15407/15408)| `Reference`| | | 
| **`SampledData`**| _Equivalent_ <br/>(12041/12042)| `SampledData`| _Equivalent_ <br/>(13264/13265)| `SampledData`| _Equivalent_ <br/>(15411/15412)| `SampledData`| | | 
| **`Signature`**| _Equivalent_ <br/>(12043/12044)| `Signature`| _Equivalent_ <br/>(13266/13267)| `Signature`| _Equivalent_ <br/>(15413/15414)| `Signature`| | | 
| **`SimpleQuantity`**| _Equivalent_ <br/>(12045/12046)| `SimpleQuantity`| _Equivalent_ <br/>(13268/13269)| `SimpleQuantity`| _Equivalent_ <br/>(15415/15416)| `SimpleQuantity`| | | 
| **`Timing`**| _Equivalent_ <br/>(12047/12048)| `Timing`| _Equivalent_ <br/>(13270/13271)| `Timing`| _Equivalent_ <br/>(15418/15419)| `Timing`| | | 
| **`base64Binary`**| _Equivalent_ <br/>(12049/12050)| `base64Binary`| _Equivalent_ <br/>(13276/13277)| `base64Binary`| _Equivalent_ <br/>(15424/15425)| `base64Binary`| | | 
| **`boolean`**| _Equivalent_ <br/>(12051/12052)| `boolean`| _Equivalent_ <br/>(13278/13279)| `boolean`| _Equivalent_ <br/>(15426/15427)| `boolean`| | | 
| **`code`**| _Equivalent_ <br/>(12053/12054)| `code`| _Equivalent_ <br/>(13280/13281)| `code`| _Equivalent_ <br/>(15430/15431)| `code`| | | 
| **`date`**| _Equivalent_ <br/>(12055/12056)| `date`| _Equivalent_ <br/>(13282/13283)| `date`| _Equivalent_ <br/>(15432/15433)| `date`| | | 
| **`dateTime`**| _Equivalent_ <br/>(12057/12058)| `dateTime`| _Equivalent_ <br/>(13284/13285)| `dateTime`| _Equivalent_ <br/>(15434/15435)| `dateTime`| | | 
| **`decimal`**| _Equivalent_ <br/>(12059/12060)| `decimal`| _Equivalent_ <br/>(13286/13287)| `decimal`| _Equivalent_ <br/>(15436/15437)| `decimal`| | | 
| **`id`**| _Equivalent_ <br/>(12061/12062)| `id`| _Equivalent_ <br/>(13288/13289)| `id`| _Equivalent_ <br/>(15438/15439)| `id`| | | 
| **`instant`**| _Equivalent_ <br/>(12063/12064)| `instant`| _Equivalent_ <br/>(13290/13291)| `instant`| _Equivalent_ <br/>(15440/15441)| `instant`| | | 
| **`integer`**| _Equivalent_ <br/>(12065/12066)| `integer`| _Equivalent_ <br/>(13292/13293)| `integer`| _Equivalent_ <br/>(15442/15443)| `integer`| | | 
| **`markdown`**| _Equivalent_ <br/>(12067/12068)| `markdown`| _Equivalent_ <br/>(13294/13295)| `markdown`| _Equivalent_ <br/>(15444/15445)| `markdown`| | | 
| **`oid`**| _Equivalent_ <br/>(12069/12070)| `oid`| _Equivalent_ <br/>(13296/13297)| `oid`| _Equivalent_ <br/>(15446/15447)| `oid`| | | 
| **`positiveInt`**| _Equivalent_ <br/>(12071/12072)| `positiveInt`| _Equivalent_ <br/>(13298/13299)| `positiveInt`| _Equivalent_ <br/>(15448/15449)| `positiveInt`| | | 
| **`string`**| _Equivalent_ <br/>(12073/12074)| `string`| _Equivalent_ <br/>(13300/13301)| `string`| _Equivalent_ <br/>(15450/15451)| `string`| | | 
| **`time`**| _Equivalent_ <br/>(12075/12076)| `time`| _Equivalent_ <br/>(13302/13303)| `time`| _Equivalent_ <br/>(15452/15453)| `time`| | | 
| **`unsignedInt`**| _Equivalent_ <br/>(12077/12078)| `unsignedInt`| _Equivalent_ <br/>(13304/13305)| `unsignedInt`| _Equivalent_ <br/>(15454/15455)| `unsignedInt`| | | 
| **`uri`**| _Equivalent_ <br/>(12079/12080)| `uri`| _Equivalent_ <br/>(13306/13307)| `uri`| _Equivalent_ <br/>(15456/15457)| `uri`| | | 
| **`uuid`**| _Equivalent_ <br/>(12081/12082)| `uuid`| _Equivalent_ <br/>(13308/13309)| `uuid`| _Equivalent_ <br/>(15460/15461)| `uuid`| | | 
| **`xhtml`**| _Equivalent_ <br/>(12083/12084)| `xhtml`| _Equivalent_ <br/>(13310/13311)| `xhtml`| _Equivalent_ <br/>(15462/15463)| `xhtml`| | | 
| <td colspan="8">**R2** System: `http://hl7.org/fhir/resource-types`
| **`Account`**| _Equivalent_ <br/>(12085/12086)| `Account`| _Equivalent_ <br/>(13312/13313)| `Account`| _Equivalent_ <br/>(15464/15465)| `Account`| | | 
| **`AllergyIntolerance`**| _Equivalent_ <br/>(12087/12088)| `AllergyIntolerance`| _Equivalent_ <br/>(13318/13319)| `AllergyIntolerance`| _Equivalent_ <br/>(15470/15471)| `AllergyIntolerance`| | | 
| **`Appointment`**| _Equivalent_ <br/>(12089/12090)| `Appointment`| _Equivalent_ <br/>(13320/13321)| `Appointment`| _Equivalent_ <br/>(15472/15473)| `Appointment`| | | 
| **`AppointmentResponse`**| _Equivalent_ <br/>(12091/12092)| `AppointmentResponse`| _Equivalent_ <br/>(13322/13323)| `AppointmentResponse`| _Equivalent_ <br/>(15474/15475)| `AppointmentResponse`| | | 
| **`AuditEvent`**| _Equivalent_ <br/>(12093/12094)| `AuditEvent`| _Equivalent_ <br/>(13324/13325)| `AuditEvent`| _Equivalent_ <br/>(15476/15477)| `AuditEvent`| | | 
| **`Basic`**| _Equivalent_ <br/>(12095/12096)| `Basic`| _Equivalent_ <br/>(13326/13327)| `Basic`| _Equivalent_ <br/>(15478/15479)| `Basic`| | | 
| **`Binary`**| _Equivalent_ <br/>(12097/12098)| `Binary`| _Equivalent_ <br/>(13328/13329)| `Binary`| _Equivalent_ <br/>(15480/15481)| `Binary`| | | 
| **`BodySite`**| _Equivalent_ <br/>(12099/12100)| `BodySite`| | | | | | | 
| **`Bundle`**| _Equivalent_ <br/>(12101/12102)| `Bundle`| _Equivalent_ <br/>(13331/13332)| `Bundle`| _Equivalent_ <br/>(15486/15487)| `Bundle`| | | 
| **`CarePlan`**| _Equivalent_ <br/>(12103/12104)| `CarePlan`| _Equivalent_ <br/>(13335/13336)| `CarePlan`| _Equivalent_ <br/>(15490/15491)| `CarePlan`| | | 
| **`Claim`**| _Equivalent_ <br/>(12105/12106)| `Claim`| _Equivalent_ <br/>(13341/13342)| `Claim`| _Equivalent_ <br/>(15500/15501)| `Claim`| | | 
| **`ClaimResponse`**| _Equivalent_ <br/>(12107/12108)| `ClaimResponse`| _Equivalent_ <br/>(13343/13344)| `ClaimResponse`| _Equivalent_ <br/>(15502/15503)| `ClaimResponse`| | | 
| **`ClinicalImpression`**| _Equivalent_ <br/>(12109/12110)| `ClinicalImpression`| _Equivalent_ <br/>(13345/13346)| `ClinicalImpression`| _Equivalent_ <br/>(15504/15505)| `ClinicalImpression`| | | 
| **`Communication`**| _Equivalent_ <br/>(12111/12112)| `Communication`| _Equivalent_ <br/>(13349/13350)| `Communication`| _Equivalent_ <br/>(15508/15509)| `Communication`| | | 
| **`CommunicationRequest`**| _Equivalent_ <br/>(12113/12114)| `CommunicationRequest`| _Equivalent_ <br/>(13351/13352)| `CommunicationRequest`| _Equivalent_ <br/>(15510/15511)| `CommunicationRequest`| | | 
| **`Composition`**| _Equivalent_ <br/>(12115/12116)| `Composition`| _Equivalent_ <br/>(13355/13356)| `Composition`| _Equivalent_ <br/>(15514/15515)| `Composition`| | | 
| **`ConceptMap`**| _Equivalent_ <br/>(12117/12118)| `ConceptMap`| _Equivalent_ <br/>(13357/13358)| `ConceptMap`| _Equivalent_ <br/>(15516/15517)| `ConceptMap`| | | 
| **`Condition`**| _Equivalent_ <br/>(12119/12120)| `Condition`| _Equivalent_ <br/>(13359/13360)| `Condition`| _Equivalent_ <br/>(15518/15519)| `Condition`| | | 
| **`Conformance`**| | | | | | | | | 
| **`Contract`**| _Equivalent_ <br/>(12122/12123)| `Contract`| _Equivalent_ <br/>(13363/13364)| `Contract`| _Equivalent_ <br/>(15522/15523)| `Contract`| | | 
| **`Coverage`**| _Equivalent_ <br/>(12124/12125)| `Coverage`| _Equivalent_ <br/>(13365/13366)| `Coverage`| _Equivalent_ <br/>(15524/15525)| `Coverage`| | | 
| **`DataElement`**| _Equivalent_ <br/>(12126/12127)| `DataElement`| | | | | | | 
| **`DetectedIssue`**| _Equivalent_ <br/>(12128/12129)| `DetectedIssue`| _Equivalent_ <br/>(13368/13369)| `DetectedIssue`| _Equivalent_ <br/>(15530/15531)| `DetectedIssue`| | | 
| **`Device`**| _Equivalent_ <br/>(12130/12131)| `Device`| _Equivalent_ <br/>(13370/13371)| `Device`| _Equivalent_ <br/>(15532/15533)| `Device`| | | 
| **`DeviceComponent`**| _Equivalent_ <br/>(12132/12133)| `DeviceComponent`| | | | | | | 
| **`DeviceMetric`**| _Equivalent_ <br/>(12134/12135)| `DeviceMetric`| _Equivalent_ <br/>(13373/13374)| `DeviceMetric`| _Equivalent_ <br/>(15536/15537)| `DeviceMetric`| | | 
| **`DeviceUseRequest`**| | | | | | | | | 
| **`DeviceUseStatement`**| _Equivalent_ <br/>(12137/12138)| `DeviceUseStatement`| _Equivalent_ <br/>(13377/13378)| `DeviceUseStatement`| _Equivalent_ <br/>(15540/15541)| `DeviceUseStatement`| | | 
| **`DiagnosticOrder`**| | | | | | | | | 
| **`DiagnosticReport`**| _Equivalent_ <br/>(12140/12141)| `DiagnosticReport`| _Equivalent_ <br/>(13379/13380)| `DiagnosticReport`| _Equivalent_ <br/>(15542/15543)| `DiagnosticReport`| | | 
| **`DocumentManifest`**| _Equivalent_ <br/>(12142/12143)| `DocumentManifest`| _Equivalent_ <br/>(13381/13382)| `DocumentManifest`| _Equivalent_ <br/>(15544/15545)| `DocumentManifest`| | | 
| **`DocumentReference`**| _Equivalent_ <br/>(12144/12145)| `DocumentReference`| _Equivalent_ <br/>(13383/13384)| `DocumentReference`| _Equivalent_ <br/>(15546/15547)| `DocumentReference`| | | 
| **`DomainResource`**| _Equivalent_ <br/>(12146/12147)| `DomainResource`| _Equivalent_ <br/>(13385/13386)| `DomainResource`| _Equivalent_ <br/>(15548/15549)| `DomainResource`| | | 
| **`EligibilityRequest`**| _Equivalent_ <br/>(12148/12149)| `EligibilityRequest`| | | | | | | 
| **`EligibilityResponse`**| _Equivalent_ <br/>(12150/12151)| `EligibilityResponse`| | | | | | | 
| **`Encounter`**| _Equivalent_ <br/>(12152/12153)| `Encounter`| _Equivalent_ <br/>(13389/13390)| `Encounter`| _Equivalent_ <br/>(15551/15552)| `Encounter`| | | 
| **`EnrollmentRequest`**| _Equivalent_ <br/>(12154/12155)| `EnrollmentRequest`| _Equivalent_ <br/>(13393/13394)| `EnrollmentRequest`| _Equivalent_ <br/>(15555/15556)| `EnrollmentRequest`| | | 
| **`EnrollmentResponse`**| _Equivalent_ <br/>(12156/12157)| `EnrollmentResponse`| _Equivalent_ <br/>(13395/13396)| `EnrollmentResponse`| _Equivalent_ <br/>(15557/15558)| `EnrollmentResponse`| | | 
| **`EpisodeOfCare`**| _Equivalent_ <br/>(12158/12159)| `EpisodeOfCare`| _Equivalent_ <br/>(13397/13398)| `EpisodeOfCare`| _Equivalent_ <br/>(15559/15560)| `EpisodeOfCare`| | | 
| **`ExplanationOfBenefit`**| _Equivalent_ <br/>(12160/12161)| `ExplanationOfBenefit`| _Equivalent_ <br/>(13400/13401)| `ExplanationOfBenefit`| _Equivalent_ <br/>(15569/15570)| `ExplanationOfBenefit`| | | 
| **`FamilyMemberHistory`**| _Equivalent_ <br/>(12162/12163)| `FamilyMemberHistory`| _Equivalent_ <br/>(13402/13403)| `FamilyMemberHistory`| _Equivalent_ <br/>(15571/15572)| `FamilyMemberHistory`| | | 
| **`Flag`**| _Equivalent_ <br/>(12164/12165)| `Flag`| _Equivalent_ <br/>(13404/13405)| `Flag`| _Equivalent_ <br/>(15573/15574)| `Flag`| | | 
| **`Goal`**| _Equivalent_ <br/>(12166/12167)| `Goal`| _Equivalent_ <br/>(13406/13407)| `Goal`| _Equivalent_ <br/>(15575/15576)| `Goal`| | | 
| **`Group`**| _Equivalent_ <br/>(12168/12169)| `Group`| _Equivalent_ <br/>(13410/13411)| `Group`| _Equivalent_ <br/>(15579/15580)| `Group`| | | 
| **`HealthcareService`**| _Equivalent_ <br/>(12170/12171)| `HealthcareService`| _Equivalent_ <br/>(13414/13415)| `HealthcareService`| _Equivalent_ <br/>(15583/15584)| `HealthcareService`| | | 
| **`ImagingObjectSelection`**| | | | | | | | | 
| **`ImagingStudy`**| _Equivalent_ <br/>(12173/12174)| `ImagingStudy`| _Equivalent_ <br/>(13417/13418)| `ImagingStudy`| _Equivalent_ <br/>(15585/15586)| `ImagingStudy`| | | 
| **`Immunization`**| _Equivalent_ <br/>(12175/12176)| `Immunization`| _Equivalent_ <br/>(13419/13420)| `Immunization`| _Equivalent_ <br/>(15587/15588)| `Immunization`| | | 
| **`ImmunizationRecommendation`**| _Equivalent_ <br/>(12177/12178)| `ImmunizationRecommendation`| _Equivalent_ <br/>(13421/13422)| `ImmunizationRecommendation`| _Equivalent_ <br/>(15591/15592)| `ImmunizationRecommendation`| | | 
| **`ImplementationGuide`**| _Equivalent_ <br/>(12179/12180)| `ImplementationGuide`| _Equivalent_ <br/>(13423/13424)| `ImplementationGuide`| _Equivalent_ <br/>(15593/15594)| `ImplementationGuide`| | | 
| **`List`**| _Equivalent_ <br/>(12181/12182)| `List`| _Equivalent_ <br/>(13429/13430)| `List`| _Equivalent_ <br/>(15603/15604)| `List`| | | 
| **`Location`**| _Equivalent_ <br/>(12183/12184)| `Location`| _Equivalent_ <br/>(13431/13432)| `Location`| _Equivalent_ <br/>(15605/15606)| `Location`| | | 
| **`Media`**| _Equivalent_ <br/>(12185/12186)| `Media`| _Equivalent_ <br/>(13437/13438)| `Media`| _Equivalent_ <br/>(15611/15612)| `Media`| | | 
| **`Medication`**| _Equivalent_ <br/>(12187/12188)| `Medication`| _Equivalent_ <br/>(13439/13440)| `Medication`| _Equivalent_ <br/>(15613/15614)| `Medication`| | | 
| **`MedicationAdministration`**| _Equivalent_ <br/>(12189/12190)| `MedicationAdministration`| _Equivalent_ <br/>(13441/13442)| `MedicationAdministration`| _Equivalent_ <br/>(15615/15616)| `MedicationAdministration`| | | 
| **`MedicationDispense`**| _Equivalent_ <br/>(12191/12192)| `MedicationDispense`| _Equivalent_ <br/>(13443/13444)| `MedicationDispense`| _Equivalent_ <br/>(15617/15618)| `MedicationDispense`| | | 
| **`MedicationOrder`**| | | | | | | | | 
| **`MedicationStatement`**| _Equivalent_ <br/>(12194/12195)| `MedicationStatement`| _Equivalent_ <br/>(13447/13448)| `MedicationStatement`| _Equivalent_ <br/>(15623/15624)| `MedicationStatement`| | | 
| **`MessageHeader`**| _Equivalent_ <br/>(12196/12197)| `MessageHeader`| _Equivalent_ <br/>(13451/13452)| `MessageHeader`| _Equivalent_ <br/>(15637/15638)| `MessageHeader`| | | 
| **`NamingSystem`**| _Equivalent_ <br/>(12198/12199)| `NamingSystem`| _Equivalent_ <br/>(13453/13454)| `NamingSystem`| _Equivalent_ <br/>(15641/15642)| `NamingSystem`| | | 
| **`NutritionOrder`**| _Equivalent_ <br/>(12200/12201)| `NutritionOrder`| _Equivalent_ <br/>(13455/13456)| `NutritionOrder`| _Equivalent_ <br/>(15643/15644)| `NutritionOrder`| | | 
| **`Observation`**| _Equivalent_ <br/>(12202/12203)| `Observation`| _Equivalent_ <br/>(13457/13458)| `Observation`| _Equivalent_ <br/>(15645/15646)| `Observation`| | | 
| **`OperationDefinition`**| _Equivalent_ <br/>(12204/12205)| `OperationDefinition`| _Equivalent_ <br/>(13459/13460)| `OperationDefinition`| _Equivalent_ <br/>(15649/15650)| `OperationDefinition`| | | 
| **`OperationOutcome`**| _Equivalent_ <br/>(12206/12207)| `OperationOutcome`| _Equivalent_ <br/>(13461/13462)| `OperationOutcome`| _Equivalent_ <br/>(15651/15652)| `OperationOutcome`| | | 
| **`Order`**| | | | | | | | | 
| **`OrderResponse`**| | | | | | | | | 
| **`Organization`**| _Equivalent_ <br/>(12210/12211)| `Organization`| _Equivalent_ <br/>(13463/13464)| `Organization`| _Equivalent_ <br/>(15653/15654)| `Organization`| | | 
| **`Parameters`**| _Equivalent_ <br/>(12212/12213)| `Parameters`| _Equivalent_ <br/>(13465/13466)| `Parameters`| _Equivalent_ <br/>(15657/15658)| `Parameters`| | | 
| **`Patient`**| _Equivalent_ <br/>(12214/12215)| `Patient`| _Equivalent_ <br/>(13467/13468)| `Patient`| _Equivalent_ <br/>(15659/15660)| `Patient`| | | 
| **`PaymentNotice`**| _Equivalent_ <br/>(12216/12217)| `PaymentNotice`| _Equivalent_ <br/>(13469/13470)| `PaymentNotice`| _Equivalent_ <br/>(15661/15662)| `PaymentNotice`| | | 
| **`PaymentReconciliation`**| _Equivalent_ <br/>(12218/12219)| `PaymentReconciliation`| _Equivalent_ <br/>(13471/13472)| `PaymentReconciliation`| _Equivalent_ <br/>(15663/15664)| `PaymentReconciliation`| | | 
| **`Person`**| _Equivalent_ <br/>(12220/12221)| `Person`| _Equivalent_ <br/>(13473/13474)| `Person`| _Equivalent_ <br/>(15665/15666)| `Person`| | | 
| **`Practitioner`**| _Equivalent_ <br/>(12222/12223)| `Practitioner`| _Equivalent_ <br/>(13477/13478)| `Practitioner`| _Equivalent_ <br/>(15669/15670)| `Practitioner`| | | 
| **`Procedure`**| _Equivalent_ <br/>(12224/12225)| `Procedure`| _Equivalent_ <br/>(13481/13482)| `Procedure`| _Equivalent_ <br/>(15673/15674)| `Procedure`| | | 
| **`ProcedureRequest`**| _Equivalent_ <br/>(12226/12227)| `ProcedureRequest`| | | | | | | 
| **`ProcessRequest`**| _Equivalent_ <br/>(12228/12229)| `ProcessRequest`| | | | | | | 
| **`ProcessResponse`**| _Equivalent_ <br/>(12230/12231)| `ProcessResponse`| | | | | | | 
| **`Provenance`**| _Equivalent_ <br/>(12232/12233)| `Provenance`| _Equivalent_ <br/>(13486/13487)| `Provenance`| _Equivalent_ <br/>(15675/15676)| `Provenance`| | | 
| **`Questionnaire`**| _Equivalent_ <br/>(12234/12235)| `Questionnaire`| _Equivalent_ <br/>(13488/13489)| `Questionnaire`| _Equivalent_ <br/>(15677/15678)| `Questionnaire`| | | 
| **`QuestionnaireResponse`**| _Equivalent_ <br/>(12236/12237)| `QuestionnaireResponse`| _Equivalent_ <br/>(13490/13491)| `QuestionnaireResponse`| _Equivalent_ <br/>(15679/15680)| `QuestionnaireResponse`| | | 
| **`ReferralRequest`**| _Equivalent_ <br/>(12238/12239)| `ReferralRequest`| | | | | | | 
| **`RelatedPerson`**| _Equivalent_ <br/>(12240/12241)| `RelatedPerson`| _Equivalent_ <br/>(13493/13494)| `RelatedPerson`| _Equivalent_ <br/>(15681/15682)| `RelatedPerson`| | | 
| **`Resource`**| _Equivalent_ <br/>(12242/12243)| `Resource`| _Equivalent_ <br/>(13501/13502)| `Resource`| _Equivalent_ <br/>(15693/15694)| `Resource`| | | 
| **`RiskAssessment`**| _Equivalent_ <br/>(12244/12245)| `RiskAssessment`| _Equivalent_ <br/>(13503/13504)| `RiskAssessment`| _Equivalent_ <br/>(15695/15696)| `RiskAssessment`| | | 
| **`Schedule`**| _Equivalent_ <br/>(12246/12247)| `Schedule`| _Equivalent_ <br/>(13505/13506)| `Schedule`| _Equivalent_ <br/>(15698/15699)| `Schedule`| | | 
| **`SearchParameter`**| _Equivalent_ <br/>(12248/12249)| `SearchParameter`| _Equivalent_ <br/>(13507/13508)| `SearchParameter`| _Equivalent_ <br/>(15700/15701)| `SearchParameter`| | | 
| **`Slot`**| _Equivalent_ <br/>(12250/12251)| `Slot`| _Equivalent_ <br/>(13511/13512)| `Slot`| _Equivalent_ <br/>(15704/15705)| `Slot`| | | 
| **`Specimen`**| _Equivalent_ <br/>(12252/12253)| `Specimen`| _Equivalent_ <br/>(13513/13514)| `Specimen`| _Equivalent_ <br/>(15706/15707)| `Specimen`| | | 
| **`StructureDefinition`**| _Equivalent_ <br/>(12254/12255)| `StructureDefinition`| _Equivalent_ <br/>(13515/13516)| `StructureDefinition`| _Equivalent_ <br/>(15710/15711)| `StructureDefinition`| | | 
| **`Subscription`**| _Equivalent_ <br/>(12256/12257)| `Subscription`| _Equivalent_ <br/>(13519/13520)| `Subscription`| _Equivalent_ <br/>(15714/15715)| `Subscription`| | | 
| **`Substance`**| _Equivalent_ <br/>(12258/12259)| `Substance`| _Equivalent_ <br/>(13521/13522)| `Substance`| _Equivalent_ <br/>(15716/15717)| `Substance`| | | 
| **`SupplyDelivery`**| _Equivalent_ <br/>(12260/12261)| `SupplyDelivery`| _Equivalent_ <br/>(13523/13524)| `SupplyDelivery`| _Equivalent_ <br/>(15724/15725)| `SupplyDelivery`| | | 
| **`SupplyRequest`**| _Equivalent_ <br/>(12262/12263)| `SupplyRequest`| _Equivalent_ <br/>(13525/13526)| `SupplyRequest`| _Equivalent_ <br/>(15726/15727)| `SupplyRequest`| | | 
| **`TestScript`**| _Equivalent_ <br/>(12264/12265)| `TestScript`| _Equivalent_ <br/>(13531/13532)| `TestScript`| _Equivalent_ <br/>(15734/15735)| `TestScript`| | | 
| **`ValueSet`**| _Equivalent_ <br/>(12266/12267)| `ValueSet`| _Equivalent_ <br/>(13533/13534)| `ValueSet`| _Equivalent_ <br/>(15736/15737)| `ValueSet`| | | 
| **`VisionPrescription`**| _Equivalent_ <br/>(12268/12269)| `VisionPrescription`| _Equivalent_ <br/>(13535/13536)| `VisionPrescription`| _Equivalent_ <br/>(15740/15741)| `VisionPrescription`| | | 
| *142 of 142 codes used* | | *135 of 173 codes used* <br/>remaining codes:<br/>`ContactDetail`, `Contributor`, `DataRequirement`, `Dosage`, `ParameterDefinition`, `RelatedArtifact`, `TriggerDefinition`, `UsageContext`, `ActivityDefinition`, `AdverseEvent`, `CapabilityStatement`, `CareTeam`, `ChargeItem`, `CodeSystem`, `CompartmentDefinition`, `Consent`, `DeviceRequest`, `Endpoint`, `ExpansionProfile`, `GraphDefinition`, `GuidanceResponse`, `ImagingManifest`, `Library`, `Linkage`, `Measure`, `MeasureReport`, `MedicationRequest`, `MessageDefinition`, `PlanDefinition`, `PractitionerRole`, `RequestGroup`, `ResearchStudy`, `ResearchSubject`, `Sequence`, `ServiceDefinition`, `StructureMap`, `Task`, `TestReport`| | *126 of 211 codes used* <br/>remaining codes:<br/>`ContactDetail`, `Contributor`, `DataRequirement`, `Dosage`, `Expression`, `MarketingStatus`, `MoneyQuantity`, `ParameterDefinition`, `Population`, `ProdCharacteristic`, `ProductShelfLife`, `RelatedArtifact`, `SubstanceAmount`, `TriggerDefinition`, `UsageContext`, `canonical`, `url`, `ActivityDefinition`, `AdverseEvent`, `BiologicallyDerivedProduct`, `BodyStructure`, `CapabilityStatement`, `CareTeam`, `CatalogEntry`, `ChargeItem`, `ChargeItemDefinition`, `CodeSystem`, `CompartmentDefinition`, `Consent`, `CoverageEligibilityRequest`, `CoverageEligibilityResponse`, `DeviceDefinition`, `DeviceRequest`, `EffectEvidenceSynthesis`, `Endpoint`, `EventDefinition`, `Evidence`, `EvidenceVariable`, `ExampleScenario`, `GraphDefinition`, `GuidanceResponse`, `ImmunizationEvaluation`, `InsurancePlan`, `Invoice`, `Library`, `Linkage`, `Measure`, `MeasureReport`, `MedicationKnowledge`, `MedicationRequest`, `MedicinalProduct`, `MedicinalProductAuthorization`, `MedicinalProductContraindication`, `MedicinalProductIndication`, `MedicinalProductIngredient`, `MedicinalProductInteraction`, `MedicinalProductManufactured`, `MedicinalProductPackaged`, `MedicinalProductPharmaceutical`, `MedicinalProductUndesirableEffect`, `MessageDefinition`, `MolecularSequence`, `ObservationDefinition`, `OrganizationAffiliation`, `PlanDefinition`, `PractitionerRole`, `RequestGroup`, `ResearchDefinition`, `ResearchElementDefinition`, `ResearchStudy`, `ResearchSubject`, `RiskEvidenceSynthesis`, `ServiceRequest`, `SpecimenDefinition`, `StructureMap`, `SubstanceNucleicAcid`, `SubstancePolymer`, `SubstanceProtein`, `SubstanceReferenceInformation`, `SubstanceSourceMaterial`, `SubstanceSpecification`, `Task`, `TerminologyCapabilities`, `TestReport`, `VerificationResult`| | *126 of 207 codes used* <br/>remaining codes:<br/>`CodeableReference`, `ContactDetail`, `Contributor`, `DataRequirement`, `Dosage`, `Expression`, `MarketingStatus`, `MoneyQuantity`, `ParameterDefinition`, `Population`, `ProdCharacteristic`, `ProductShelfLife`, `RatioRange`, `RelatedArtifact`, `TriggerDefinition`, `UsageContext`, `canonical`, `url`, `ActivityDefinition`, `AdministrableProductDefinition`, `AdverseEvent`, `BiologicallyDerivedProduct`, `BodyStructure`, `CapabilityStatement`, `CareTeam`, `CatalogEntry`, `ChargeItem`, `ChargeItemDefinition`, `Citation`, `ClinicalUseDefinition`, `CodeSystem`, `CompartmentDefinition`, `Consent`, `CoverageEligibilityRequest`, `CoverageEligibilityResponse`, `DeviceDefinition`, `DeviceRequest`, `Endpoint`, `EventDefinition`, `Evidence`, `EvidenceReport`, `EvidenceVariable`, `ExampleScenario`, `GraphDefinition`, `GuidanceResponse`, `ImmunizationEvaluation`, `Ingredient`, `InsurancePlan`, `Invoice`, `Library`, `Linkage`, `ManufacturedItemDefinition`, `Measure`, `MeasureReport`, `MedicationKnowledge`, `MedicationRequest`, `MedicinalProductDefinition`, `MessageDefinition`, `MolecularSequence`, `NutritionProduct`, `ObservationDefinition`, `OrganizationAffiliation`, `PackagedProductDefinition`, `PlanDefinition`, `PractitionerRole`, `RegulatedAuthorization`, `RequestGroup`, `ResearchDefinition`, `ResearchElementDefinition`, `ResearchStudy`, `ResearchSubject`, `ServiceRequest`, `SpecimenDefinition`, `StructureMap`, `SubscriptionStatus`, `SubscriptionTopic`, `SubstanceDefinition`, `Task`, `TerminologyCapabilities`, `TestReport`, `VerificationResult`| | 

