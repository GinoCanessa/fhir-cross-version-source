Comparison of 
Generated at Thursday, April 3, 2025 8:18:25 AM

### FHIRAllTypes

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | FHIRAllTypes |
| Canonical URL | `http://hl7.org/fhir/ValueSet/all-types` |
| Version | 4.3.0 |
| Description | A list of all the concrete types defined in this version of the FHIR specification - Abstract Types, Data Types and Resource Types. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `3523` |
| Database Concept Count | `209` |
| Database Active Concept Count | `209` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/DataRequirement` | `DataRequirement.type` | `http://hl7.org/fhir/ValueSet/all-types\|4.3.0` | `Required` | The type of the required data |
| `http://hl7.org/fhir/StructureDefinition/ParameterDefinition` | `ParameterDefinition.type` | `http://hl7.org/fhir/ValueSet/all-types\|4.3.0` | `Required` | What type of value |
| `http://hl7.org/fhir/StructureDefinition/OperationDefinition` | `OperationDefinition.parameter.type` | `http://hl7.org/fhir/ValueSet/all-types\|4.3.0` | `Required` | What type this parameter has |

### Referenced Systems

* `http://hl7.org/fhir/data-types`
* `http://hl7.org/fhir/resource-types`
* `http://hl7.org/fhir/abstract-types`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [FHIRAllTypes](/docs/R3/ValueSets/FHIRAllTypes.md)<br/> `http://hl7.org/fhir/ValueSet/all-types\|3.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1317`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1318`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [FHIRAllTypes](/docs/R4/ValueSets/FHIRAllTypes.md)<br/> `http://hl7.org/fhir/ValueSet/all-types\|4.0.1` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1373`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1374`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [FHIRAllTypes](/docs/R4B/ValueSets/FHIRAllTypes.md)<br/> `http://hl7.org/fhir/ValueSet/all-types\|4.3.0` | <br/>*no map*<br/><hr/><br/>*no map*<br/>| | 
### Code Mappings


#### Map Group 0

This group is centered on the Value Set FHIRAllTypes from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| *No Map* | Relationship | [R3 FHIRAllTypes](/docs/R3/ValueSets/FHIRAllTypes.md)| Relationship | [R4 FHIRAllTypes](/docs/R4/ValueSets/FHIRAllTypes.md)| Relationship | R4B FHIRAllTypes| Relationship | *No Map* 
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/data-types`
| | | `Address`| _Equivalent_ <br/>(12821/12822)| `Address`| _Equivalent_ <br/>(14027/14028)| **`Address`**| | | 
| | | `Age`| _Equivalent_ <br/>(12823/12824)| `Age`| _Equivalent_ <br/>(14029/14030)| **`Age`**| | | 
| | | `Annotation`| _Equivalent_ <br/>(12825/12826)| `Annotation`| _Equivalent_ <br/>(14031/14032)| **`Annotation`**| | | 
| | | `Attachment`| _Equivalent_ <br/>(12827/12828)| `Attachment`| _Equivalent_ <br/>(14033/14034)| **`Attachment`**| | | 
| | | `BackboneElement`| _Equivalent_ <br/>(12829/12830)| `BackboneElement`| _Equivalent_ <br/>(14035/14036)| **`BackboneElement`**| | | 
| | | `CodeableConcept`| _Equivalent_ <br/>(12831/12832)| `CodeableConcept`| _Equivalent_ <br/>(14037/14038)| **`CodeableConcept`**| | | 
| | | | | | | **`CodeableReference`**| | | 
| | | `Coding`| _Equivalent_ <br/>(12833/12834)| `Coding`| _Equivalent_ <br/>(14039/14040)| **`Coding`**| | | 
| | | `ContactDetail`| _Equivalent_ <br/>(12835/12836)| `ContactDetail`| _Equivalent_ <br/>(14041/14042)| **`ContactDetail`**| | | 
| | | `ContactPoint`| _Equivalent_ <br/>(12837/12838)| `ContactPoint`| _Equivalent_ <br/>(14043/14044)| **`ContactPoint`**| | | 
| | | `Contributor`| _Equivalent_ <br/>(12839/12840)| `Contributor`| _Equivalent_ <br/>(14045/14046)| **`Contributor`**| | | 
| | | `Count`| _Equivalent_ <br/>(12841/12842)| `Count`| _Equivalent_ <br/>(14047/14048)| **`Count`**| | | 
| | | `DataRequirement`| _Equivalent_ <br/>(12843/12844)| `DataRequirement`| _Equivalent_ <br/>(14049/14050)| **`DataRequirement`**| | | 
| | | `Distance`| _Equivalent_ <br/>(12845/12846)| `Distance`| _Equivalent_ <br/>(14051/14052)| **`Distance`**| | | 
| | | `Dosage`| _Equivalent_ <br/>(12847/12848)| `Dosage`| _Equivalent_ <br/>(14053/14054)| **`Dosage`**| | | 
| | | `Duration`| _Equivalent_ <br/>(12849/12850)| `Duration`| _Equivalent_ <br/>(14055/14056)| **`Duration`**| | | 
| | | `Element`| _Equivalent_ <br/>(12851/12852)| `Element`| _Equivalent_ <br/>(14057/14058)| **`Element`**| | | 
| | | `ElementDefinition`| _Equivalent_ <br/>(12853/12854)| `ElementDefinition`| _Equivalent_ <br/>(14059/14060)| **`ElementDefinition`**| | | 
| | | | | `Expression`| _Equivalent_ <br/>(14061/14062)| **`Expression`**| | | 
| | | `Extension`| _Equivalent_ <br/>(12855/12856)| `Extension`| _Equivalent_ <br/>(14063/14064)| **`Extension`**| | | 
| | | `HumanName`| _Equivalent_ <br/>(12857/12858)| `HumanName`| _Equivalent_ <br/>(14065/14066)| **`HumanName`**| | | 
| | | `Identifier`| _Equivalent_ <br/>(12859/12860)| `Identifier`| _Equivalent_ <br/>(14067/14068)| **`Identifier`**| | | 
| | | | | `MarketingStatus`| _Equivalent_ <br/>(14069/14070)| **`MarketingStatus`**| | | 
| | | `Meta`| _Equivalent_ <br/>(12861/12862)| `Meta`| _Equivalent_ <br/>(14071/14072)| **`Meta`**| | | 
| | | `Money`| _Equivalent_ <br/>(12863/12864)| `Money`| _Equivalent_ <br/>(14073/14074)| **`Money`**| | | 
| | | | | `MoneyQuantity`| _Equivalent_ <br/>(14075/14076)| **`MoneyQuantity`**| | | 
| | | `Narrative`| _Equivalent_ <br/>(12865/12866)| `Narrative`| _Equivalent_ <br/>(14077/14078)| **`Narrative`**| | | 
| | | `ParameterDefinition`| _Equivalent_ <br/>(12867/12868)| `ParameterDefinition`| _Equivalent_ <br/>(14079/14080)| **`ParameterDefinition`**| | | 
| | | `Period`| _Equivalent_ <br/>(12869/12870)| `Period`| _Equivalent_ <br/>(14081/14082)| **`Period`**| | | 
| | | | | `Population`| _Equivalent_ <br/>(14083/14084)| **`Population`**| | | 
| | | | | `ProdCharacteristic`| _Equivalent_ <br/>(14085/14086)| **`ProdCharacteristic`**| | | 
| | | | | `ProductShelfLife`| _Equivalent_ <br/>(14087/14088)| **`ProductShelfLife`**| | | 
| | | `Quantity`| _Equivalent_ <br/>(12871/12872)| `Quantity`| _Equivalent_ <br/>(14089/14090)| **`Quantity`**| | | 
| | | `Range`| _Equivalent_ <br/>(12873/12874)| `Range`| _Equivalent_ <br/>(14091/14092)| **`Range`**| | | 
| | | `Ratio`| _Equivalent_ <br/>(12875/12876)| `Ratio`| _Equivalent_ <br/>(14093/14094)| **`Ratio`**| | | 
| | | | | | | **`RatioRange`**| | | 
| | | `Reference`| _Equivalent_ <br/>(12877/12878)| `Reference`| _Equivalent_ <br/>(14095/14096)| **`Reference`**| | | 
| | | `RelatedArtifact`| _Equivalent_ <br/>(12879/12880)| `RelatedArtifact`| _Equivalent_ <br/>(14097/14098)| **`RelatedArtifact`**| | | 
| | | `SampledData`| _Equivalent_ <br/>(12881/12882)| `SampledData`| _Equivalent_ <br/>(14099/14100)| **`SampledData`**| | | 
| | | `Signature`| _Equivalent_ <br/>(12883/12884)| `Signature`| _Equivalent_ <br/>(14101/14102)| **`Signature`**| | | 
| | | `SimpleQuantity`| _Equivalent_ <br/>(12885/12886)| `SimpleQuantity`| _Equivalent_ <br/>(14103/14104)| **`SimpleQuantity`**| | | 
| | | `Timing`| _Equivalent_ <br/>(12887/12888)| `Timing`| _Equivalent_ <br/>(14106/14107)| **`Timing`**| | | 
| | | `TriggerDefinition`| _Equivalent_ <br/>(12889/12890)| `TriggerDefinition`| _Equivalent_ <br/>(14108/14109)| **`TriggerDefinition`**| | | 
| | | `UsageContext`| _Equivalent_ <br/>(12891/12892)| `UsageContext`| _Equivalent_ <br/>(14110/14111)| **`UsageContext`**| | | 
| | | `base64Binary`| _Equivalent_ <br/>(12893/12894)| `base64Binary`| _Equivalent_ <br/>(14112/14113)| **`base64Binary`**| | | 
| | | `boolean`| _Equivalent_ <br/>(12895/12896)| `boolean`| _Equivalent_ <br/>(14114/14115)| **`boolean`**| | | 
| | | | | `canonical`| _Equivalent_ <br/>(14116/14117)| **`canonical`**| | | 
| | | `code`| _Equivalent_ <br/>(12897/12898)| `code`| _Equivalent_ <br/>(14118/14119)| **`code`**| | | 
| | | `date`| _Equivalent_ <br/>(12899/12900)| `date`| _Equivalent_ <br/>(14120/14121)| **`date`**| | | 
| | | `dateTime`| _Equivalent_ <br/>(12901/12902)| `dateTime`| _Equivalent_ <br/>(14122/14123)| **`dateTime`**| | | 
| | | `decimal`| _Equivalent_ <br/>(12903/12904)| `decimal`| _Equivalent_ <br/>(14124/14125)| **`decimal`**| | | 
| | | `id`| _Equivalent_ <br/>(12905/12906)| `id`| _Equivalent_ <br/>(14126/14127)| **`id`**| | | 
| | | `instant`| _Equivalent_ <br/>(12907/12908)| `instant`| _Equivalent_ <br/>(14128/14129)| **`instant`**| | | 
| | | `integer`| _Equivalent_ <br/>(12909/12910)| `integer`| _Equivalent_ <br/>(14130/14131)| **`integer`**| | | 
| | | `markdown`| _Equivalent_ <br/>(12911/12912)| `markdown`| _Equivalent_ <br/>(14132/14133)| **`markdown`**| | | 
| | | `oid`| _Equivalent_ <br/>(12913/12914)| `oid`| _Equivalent_ <br/>(14134/14135)| **`oid`**| | | 
| | | `positiveInt`| _Equivalent_ <br/>(12915/12916)| `positiveInt`| _Equivalent_ <br/>(14136/14137)| **`positiveInt`**| | | 
| | | `string`| _Equivalent_ <br/>(12917/12918)| `string`| _Equivalent_ <br/>(14138/14139)| **`string`**| | | 
| | | `time`| _Equivalent_ <br/>(12919/12920)| `time`| _Equivalent_ <br/>(14140/14141)| **`time`**| | | 
| | | `unsignedInt`| _Equivalent_ <br/>(12921/12922)| `unsignedInt`| _Equivalent_ <br/>(14142/14143)| **`unsignedInt`**| | | 
| | | `uri`| _Equivalent_ <br/>(12923/12924)| `uri`| _Equivalent_ <br/>(14144/14145)| **`uri`**| | | 
| | | | | `url`| _Equivalent_ <br/>(14146/14147)| **`url`**| | | 
| | | `uuid`| _Equivalent_ <br/>(12925/12926)| `uuid`| _Equivalent_ <br/>(14148/14149)| **`uuid`**| | | 
| | | `xhtml`| _Equivalent_ <br/>(12927/12928)| `xhtml`| _Equivalent_ <br/>(14150/14151)| **`xhtml`**| | | 
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/resource-types`
| | | `Resource`| _Equivalent_ <br/>(13118/13119)| `Resource`| _Equivalent_ <br/>(14381/14382)| **`Resource`**| | | 
| | | `Binary`| _Equivalent_ <br/>(12945/12946)| `Binary`| _Equivalent_ <br/>(14168/14169)| **`Binary`**| | | 
| | | `Bundle`| _Equivalent_ <br/>(12948/12949)| `Bundle`| _Equivalent_ <br/>(14174/14175)| **`Bundle`**| | | 
| | | `DomainResource`| _Equivalent_ <br/>(13002/13003)| `DomainResource`| _Equivalent_ <br/>(14236/14237)| **`DomainResource`**| | | 
| | | `Account`| _Equivalent_ <br/>(12929/12930)| `Account`| _Equivalent_ <br/>(14152/14153)| **`Account`**| | | 
| | | `ActivityDefinition`| _Equivalent_ <br/>(12931/12932)| `ActivityDefinition`| _Equivalent_ <br/>(14154/14155)| **`ActivityDefinition`**| | | 
| | | | | | | **`AdministrableProductDefinition`**| | | 
| | | `AdverseEvent`| _Equivalent_ <br/>(12933/12934)| `AdverseEvent`| _Equivalent_ <br/>(14156/14157)| **`AdverseEvent`**| | | 
| | | `AllergyIntolerance`| _Equivalent_ <br/>(12935/12936)| `AllergyIntolerance`| _Equivalent_ <br/>(14158/14159)| **`AllergyIntolerance`**| | | 
| | | `Appointment`| _Equivalent_ <br/>(12937/12938)| `Appointment`| _Equivalent_ <br/>(14160/14161)| **`Appointment`**| | | 
| | | `AppointmentResponse`| _Equivalent_ <br/>(12939/12940)| `AppointmentResponse`| _Equivalent_ <br/>(14162/14163)| **`AppointmentResponse`**| | | 
| | | `AuditEvent`| _Equivalent_ <br/>(12941/12942)| `AuditEvent`| _Equivalent_ <br/>(14164/14165)| **`AuditEvent`**| | | 
| | | `Basic`| _Equivalent_ <br/>(12943/12944)| `Basic`| _Equivalent_ <br/>(14166/14167)| **`Basic`**| | | 
| | | | | `BiologicallyDerivedProduct`| _Equivalent_ <br/>(14170/14171)| **`BiologicallyDerivedProduct`**| | | 
| | | | | `BodyStructure`| _Equivalent_ <br/>(14172/14173)| **`BodyStructure`**| | | 
| | | `CapabilityStatement`| _Equivalent_ <br/>(12950/12951)| `CapabilityStatement`| _Equivalent_ <br/>(14176/14177)| **`CapabilityStatement`**| | | 
| | | `CarePlan`| _Equivalent_ <br/>(12952/12953)| `CarePlan`| _Equivalent_ <br/>(14178/14179)| **`CarePlan`**| | | 
| | | `CareTeam`| _Equivalent_ <br/>(12954/12955)| `CareTeam`| _Equivalent_ <br/>(14180/14181)| **`CareTeam`**| | | 
| | | | | `CatalogEntry`| _Equivalent_ <br/>(14182/14183)| **`CatalogEntry`**| | | 
| | | `ChargeItem`| _Equivalent_ <br/>(12956/12957)| `ChargeItem`| _Equivalent_ <br/>(14184/14185)| **`ChargeItem`**| | | 
| | | | | `ChargeItemDefinition`| _Equivalent_ <br/>(14186/14187)| **`ChargeItemDefinition`**| | | 
| | | | | | | **`Citation`**| | | 
| | | `Claim`| _Equivalent_ <br/>(12958/12959)| `Claim`| _Equivalent_ <br/>(14188/14189)| **`Claim`**| | | 
| | | `ClaimResponse`| _Equivalent_ <br/>(12960/12961)| `ClaimResponse`| _Equivalent_ <br/>(14190/14191)| **`ClaimResponse`**| | | 
| | | `ClinicalImpression`| _Equivalent_ <br/>(12962/12963)| `ClinicalImpression`| _Equivalent_ <br/>(14192/14193)| **`ClinicalImpression`**| | | 
| | | | | | | **`ClinicalUseDefinition`**| | | 
| | | `CodeSystem`| _Equivalent_ <br/>(12964/12965)| `CodeSystem`| _Equivalent_ <br/>(14194/14195)| **`CodeSystem`**| | | 
| | | `Communication`| _Equivalent_ <br/>(12966/12967)| `Communication`| _Equivalent_ <br/>(14196/14197)| **`Communication`**| | | 
| | | `CommunicationRequest`| _Equivalent_ <br/>(12968/12969)| `CommunicationRequest`| _Equivalent_ <br/>(14198/14199)| **`CommunicationRequest`**| | | 
| | | `CompartmentDefinition`| _Equivalent_ <br/>(12970/12971)| `CompartmentDefinition`| _Equivalent_ <br/>(14200/14201)| **`CompartmentDefinition`**| | | 
| | | `Composition`| _Equivalent_ <br/>(12972/12973)| `Composition`| _Equivalent_ <br/>(14202/14203)| **`Composition`**| | | 
| | | `ConceptMap`| _Equivalent_ <br/>(12974/12975)| `ConceptMap`| _Equivalent_ <br/>(14204/14205)| **`ConceptMap`**| | | 
| | | `Condition`| _Equivalent_ <br/>(12976/12977)| `Condition`| _Equivalent_ <br/>(14206/14207)| **`Condition`**| | | 
| | | `Consent`| _Equivalent_ <br/>(12978/12979)| `Consent`| _Equivalent_ <br/>(14208/14209)| **`Consent`**| | | 
| | | `Contract`| _Equivalent_ <br/>(12980/12981)| `Contract`| _Equivalent_ <br/>(14210/14211)| **`Contract`**| | | 
| | | `Coverage`| _Equivalent_ <br/>(12982/12983)| `Coverage`| _Equivalent_ <br/>(14212/14213)| **`Coverage`**| | | 
| | | | | `CoverageEligibilityRequest`| _Equivalent_ <br/>(14214/14215)| **`CoverageEligibilityRequest`**| | | 
| | | | | `CoverageEligibilityResponse`| _Equivalent_ <br/>(14216/14217)| **`CoverageEligibilityResponse`**| | | 
| | | `DetectedIssue`| _Equivalent_ <br/>(12985/12986)| `DetectedIssue`| _Equivalent_ <br/>(14218/14219)| **`DetectedIssue`**| | | 
| | | `Device`| _Equivalent_ <br/>(12987/12988)| `Device`| _Equivalent_ <br/>(14220/14221)| **`Device`**| | | 
| | | | | `DeviceDefinition`| _Equivalent_ <br/>(14222/14223)| **`DeviceDefinition`**| | | 
| | | `DeviceMetric`| _Equivalent_ <br/>(12990/12991)| `DeviceMetric`| _Equivalent_ <br/>(14224/14225)| **`DeviceMetric`**| | | 
| | | `DeviceRequest`| _Equivalent_ <br/>(12992/12993)| `DeviceRequest`| _Equivalent_ <br/>(14226/14227)| **`DeviceRequest`**| | | 
| | | `DeviceUseStatement`| _Equivalent_ <br/>(12994/12995)| `DeviceUseStatement`| _Equivalent_ <br/>(14228/14229)| **`DeviceUseStatement`**| | | 
| | | `DiagnosticReport`| _Equivalent_ <br/>(12996/12997)| `DiagnosticReport`| _Equivalent_ <br/>(14230/14231)| **`DiagnosticReport`**| | | 
| | | `DocumentManifest`| _Equivalent_ <br/>(12998/12999)| `DocumentManifest`| _Equivalent_ <br/>(14232/14233)| **`DocumentManifest`**| | | 
| | | `DocumentReference`| _Equivalent_ <br/>(13000/13001)| `DocumentReference`| _Equivalent_ <br/>(14234/14235)| **`DocumentReference`**| | | 
| | | `Encounter`| _Equivalent_ <br/>(13006/13007)| `Encounter`| _Equivalent_ <br/>(14239/14240)| **`Encounter`**| | | 
| | | `Endpoint`| _Equivalent_ <br/>(13008/13009)| `Endpoint`| _Equivalent_ <br/>(14241/14242)| **`Endpoint`**| | | 
| | | `EnrollmentRequest`| _Equivalent_ <br/>(13010/13011)| `EnrollmentRequest`| _Equivalent_ <br/>(14243/14244)| **`EnrollmentRequest`**| | | 
| | | `EnrollmentResponse`| _Equivalent_ <br/>(13012/13013)| `EnrollmentResponse`| _Equivalent_ <br/>(14245/14246)| **`EnrollmentResponse`**| | | 
| | | `EpisodeOfCare`| _Equivalent_ <br/>(13014/13015)| `EpisodeOfCare`| _Equivalent_ <br/>(14247/14248)| **`EpisodeOfCare`**| | | 
| | | | | `EventDefinition`| _Equivalent_ <br/>(14249/14250)| **`EventDefinition`**| | | 
| | | | | `Evidence`| _Equivalent_ <br/>(14251/14252)| **`Evidence`**| | | 
| | | | | | | **`EvidenceReport`**| | | 
| | | | | `EvidenceVariable`| _Equivalent_ <br/>(14253/14254)| **`EvidenceVariable`**| | | 
| | | | | `ExampleScenario`| _Equivalent_ <br/>(14255/14256)| **`ExampleScenario`**| | | 
| | | `ExplanationOfBenefit`| _Equivalent_ <br/>(13017/13018)| `ExplanationOfBenefit`| _Equivalent_ <br/>(14257/14258)| **`ExplanationOfBenefit`**| | | 
| | | `FamilyMemberHistory`| _Equivalent_ <br/>(13019/13020)| `FamilyMemberHistory`| _Equivalent_ <br/>(14259/14260)| **`FamilyMemberHistory`**| | | 
| | | `Flag`| _Equivalent_ <br/>(13021/13022)| `Flag`| _Equivalent_ <br/>(14261/14262)| **`Flag`**| | | 
| | | `Goal`| _Equivalent_ <br/>(13023/13024)| `Goal`| _Equivalent_ <br/>(14263/14264)| **`Goal`**| | | 
| | | `GraphDefinition`| _Equivalent_ <br/>(13025/13026)| `GraphDefinition`| _Equivalent_ <br/>(14265/14266)| **`GraphDefinition`**| | | 
| | | `Group`| _Equivalent_ <br/>(13027/13028)| `Group`| _Equivalent_ <br/>(14267/14268)| **`Group`**| | | 
| | | `GuidanceResponse`| _Equivalent_ <br/>(13029/13030)| `GuidanceResponse`| _Equivalent_ <br/>(14269/14270)| **`GuidanceResponse`**| | | 
| | | `HealthcareService`| _Equivalent_ <br/>(13031/13032)| `HealthcareService`| _Equivalent_ <br/>(14271/14272)| **`HealthcareService`**| | | 
| | | `ImagingStudy`| _Equivalent_ <br/>(13034/13035)| `ImagingStudy`| _Equivalent_ <br/>(14273/14274)| **`ImagingStudy`**| | | 
| | | `Immunization`| _Equivalent_ <br/>(13036/13037)| `Immunization`| _Equivalent_ <br/>(14275/14276)| **`Immunization`**| | | 
| | | | | `ImmunizationEvaluation`| _Equivalent_ <br/>(14277/14278)| **`ImmunizationEvaluation`**| | | 
| | | `ImmunizationRecommendation`| _Equivalent_ <br/>(13038/13039)| `ImmunizationRecommendation`| _Equivalent_ <br/>(14279/14280)| **`ImmunizationRecommendation`**| | | 
| | | `ImplementationGuide`| _Equivalent_ <br/>(13040/13041)| `ImplementationGuide`| _Equivalent_ <br/>(14281/14282)| **`ImplementationGuide`**| | | 
| | | | | | | **`Ingredient`**| | | 
| | | | | `InsurancePlan`| _Equivalent_ <br/>(14283/14284)| **`InsurancePlan`**| | | 
| | | | | `Invoice`| _Equivalent_ <br/>(14285/14286)| **`Invoice`**| | | 
| | | `Library`| _Equivalent_ <br/>(13042/13043)| `Library`| _Equivalent_ <br/>(14287/14288)| **`Library`**| | | 
| | | `Linkage`| _Equivalent_ <br/>(13044/13045)| `Linkage`| _Equivalent_ <br/>(14289/14290)| **`Linkage`**| | | 
| | | `List`| _Equivalent_ <br/>(13046/13047)| `List`| _Equivalent_ <br/>(14291/14292)| **`List`**| | | 
| | | `Location`| _Equivalent_ <br/>(13048/13049)| `Location`| _Equivalent_ <br/>(14293/14294)| **`Location`**| | | 
| | | | | | | **`ManufacturedItemDefinition`**| | | 
| | | `Measure`| _Equivalent_ <br/>(13050/13051)| `Measure`| _Equivalent_ <br/>(14295/14296)| **`Measure`**| | | 
| | | `MeasureReport`| _Equivalent_ <br/>(13052/13053)| `MeasureReport`| _Equivalent_ <br/>(14297/14298)| **`MeasureReport`**| | | 
| | | `Media`| _Equivalent_ <br/>(13054/13055)| `Media`| _Equivalent_ <br/>(14299/14300)| **`Media`**| | | 
| | | `Medication`| _Equivalent_ <br/>(13056/13057)| `Medication`| _Equivalent_ <br/>(14301/14302)| **`Medication`**| | | 
| | | `MedicationAdministration`| _Equivalent_ <br/>(13058/13059)| `MedicationAdministration`| _Equivalent_ <br/>(14303/14304)| **`MedicationAdministration`**| | | 
| | | `MedicationDispense`| _Equivalent_ <br/>(13060/13061)| `MedicationDispense`| _Equivalent_ <br/>(14305/14306)| **`MedicationDispense`**| | | 
| | | | | `MedicationKnowledge`| _Equivalent_ <br/>(14307/14308)| **`MedicationKnowledge`**| | | 
| | | `MedicationRequest`| _Equivalent_ <br/>(13062/13063)| `MedicationRequest`| _Equivalent_ <br/>(14309/14310)| **`MedicationRequest`**| | | 
| | | `MedicationStatement`| _Equivalent_ <br/>(13064/13065)| `MedicationStatement`| _Equivalent_ <br/>(14311/14312)| **`MedicationStatement`**| | | 
| | | | | | | **`MedicinalProductDefinition`**| | | 
| | | `MessageDefinition`| _Equivalent_ <br/>(13066/13067)| `MessageDefinition`| _Equivalent_ <br/>(14323/14324)| **`MessageDefinition`**| | | 
| | | `MessageHeader`| _Equivalent_ <br/>(13068/13069)| `MessageHeader`| _Equivalent_ <br/>(14325/14326)| **`MessageHeader`**| | | 
| | | | | `MolecularSequence`| _Equivalent_ <br/>(14327/14328)| **`MolecularSequence`**| | | 
| | | `NamingSystem`| _Equivalent_ <br/>(13070/13071)| `NamingSystem`| _Equivalent_ <br/>(14329/14330)| **`NamingSystem`**| | | 
| | | `NutritionOrder`| _Equivalent_ <br/>(13072/13073)| `NutritionOrder`| _Equivalent_ <br/>(14331/14332)| **`NutritionOrder`**| | | 
| | | | | | | **`NutritionProduct`**| | | 
| | | `Observation`| _Equivalent_ <br/>(13074/13075)| `Observation`| _Equivalent_ <br/>(14333/14334)| **`Observation`**| | | 
| | | | | `ObservationDefinition`| _Equivalent_ <br/>(14335/14336)| **`ObservationDefinition`**| | | 
| | | `OperationDefinition`| _Equivalent_ <br/>(13076/13077)| `OperationDefinition`| _Equivalent_ <br/>(14337/14338)| **`OperationDefinition`**| | | 
| | | `OperationOutcome`| _Equivalent_ <br/>(13078/13079)| `OperationOutcome`| _Equivalent_ <br/>(14339/14340)| **`OperationOutcome`**| | | 
| | | `Organization`| _Equivalent_ <br/>(13080/13081)| `Organization`| _Equivalent_ <br/>(14341/14342)| **`Organization`**| | | 
| | | | | `OrganizationAffiliation`| _Equivalent_ <br/>(14343/14344)| **`OrganizationAffiliation`**| | | 
| | | | | | | **`PackagedProductDefinition`**| | | 
| | | `Patient`| _Equivalent_ <br/>(13084/13085)| `Patient`| _Equivalent_ <br/>(14347/14348)| **`Patient`**| | | 
| | | `PaymentNotice`| _Equivalent_ <br/>(13086/13087)| `PaymentNotice`| _Equivalent_ <br/>(14349/14350)| **`PaymentNotice`**| | | 
| | | `PaymentReconciliation`| _Equivalent_ <br/>(13088/13089)| `PaymentReconciliation`| _Equivalent_ <br/>(14351/14352)| **`PaymentReconciliation`**| | | 
| | | `Person`| _Equivalent_ <br/>(13090/13091)| `Person`| _Equivalent_ <br/>(14353/14354)| **`Person`**| | | 
| | | `PlanDefinition`| _Equivalent_ <br/>(13092/13093)| `PlanDefinition`| _Equivalent_ <br/>(14355/14356)| **`PlanDefinition`**| | | 
| | | `Practitioner`| _Equivalent_ <br/>(13094/13095)| `Practitioner`| _Equivalent_ <br/>(14357/14358)| **`Practitioner`**| | | 
| | | `PractitionerRole`| _Equivalent_ <br/>(13096/13097)| `PractitionerRole`| _Equivalent_ <br/>(14359/14360)| **`PractitionerRole`**| | | 
| | | `Procedure`| _Equivalent_ <br/>(13098/13099)| `Procedure`| _Equivalent_ <br/>(14361/14362)| **`Procedure`**| | | 
| | | `Provenance`| _Equivalent_ <br/>(13103/13104)| `Provenance`| _Equivalent_ <br/>(14363/14364)| **`Provenance`**| | | 
| | | `Questionnaire`| _Equivalent_ <br/>(13105/13106)| `Questionnaire`| _Equivalent_ <br/>(14365/14366)| **`Questionnaire`**| | | 
| | | `QuestionnaireResponse`| _Equivalent_ <br/>(13107/13108)| `QuestionnaireResponse`| _Equivalent_ <br/>(14367/14368)| **`QuestionnaireResponse`**| | | 
| | | | | | | **`RegulatedAuthorization`**| | | 
| | | `RelatedPerson`| _Equivalent_ <br/>(13110/13111)| `RelatedPerson`| _Equivalent_ <br/>(14369/14370)| **`RelatedPerson`**| | | 
| | | `RequestGroup`| _Equivalent_ <br/>(13112/13113)| `RequestGroup`| _Equivalent_ <br/>(14371/14372)| **`RequestGroup`**| | | 
| | | | | `ResearchDefinition`| _Equivalent_ <br/>(14373/14374)| **`ResearchDefinition`**| | | 
| | | | | `ResearchElementDefinition`| _Equivalent_ <br/>(14375/14376)| **`ResearchElementDefinition`**| | | 
| | | `ResearchStudy`| _Equivalent_ <br/>(13114/13115)| `ResearchStudy`| _Equivalent_ <br/>(14377/14378)| **`ResearchStudy`**| | | 
| | | `ResearchSubject`| _Equivalent_ <br/>(13116/13117)| `ResearchSubject`| _Equivalent_ <br/>(14379/14380)| **`ResearchSubject`**| | | 
| | | `RiskAssessment`| _Equivalent_ <br/>(13120/13121)| `RiskAssessment`| _Equivalent_ <br/>(14383/14384)| **`RiskAssessment`**| | | 
| | | `Schedule`| _Equivalent_ <br/>(13122/13123)| `Schedule`| _Equivalent_ <br/>(14386/14387)| **`Schedule`**| | | 
| | | `SearchParameter`| _Equivalent_ <br/>(13124/13125)| `SearchParameter`| _Equivalent_ <br/>(14388/14389)| **`SearchParameter`**| | | 
| | | | | `ServiceRequest`| _Equivalent_ <br/>(14390/14391)| **`ServiceRequest`**| | | 
| | | `Slot`| _Equivalent_ <br/>(13128/13129)| `Slot`| _Equivalent_ <br/>(14392/14393)| **`Slot`**| | | 
| | | `Specimen`| _Equivalent_ <br/>(13130/13131)| `Specimen`| _Equivalent_ <br/>(14394/14395)| **`Specimen`**| | | 
| | | | | `SpecimenDefinition`| _Equivalent_ <br/>(14396/14397)| **`SpecimenDefinition`**| | | 
| | | `StructureDefinition`| _Equivalent_ <br/>(13132/13133)| `StructureDefinition`| _Equivalent_ <br/>(14398/14399)| **`StructureDefinition`**| | | 
| | | `StructureMap`| _Equivalent_ <br/>(13134/13135)| `StructureMap`| _Equivalent_ <br/>(14400/14401)| **`StructureMap`**| | | 
| | | `Subscription`| _Equivalent_ <br/>(13136/13137)| `Subscription`| _Equivalent_ <br/>(14402/14403)| **`Subscription`**| | | 
| | | | | | | **`SubscriptionStatus`**| | | 
| | | | | | | **`SubscriptionTopic`**| | | 
| | | `Substance`| _Equivalent_ <br/>(13138/13139)| `Substance`| _Equivalent_ <br/>(14404/14405)| **`Substance`**| | | 
| | | | | | | **`SubstanceDefinition`**| | | 
| | | `SupplyDelivery`| _Equivalent_ <br/>(13140/13141)| `SupplyDelivery`| _Equivalent_ <br/>(14412/14413)| **`SupplyDelivery`**| | | 
| | | `SupplyRequest`| _Equivalent_ <br/>(13142/13143)| `SupplyRequest`| _Equivalent_ <br/>(14414/14415)| **`SupplyRequest`**| | | 
| | | `Task`| _Equivalent_ <br/>(13144/13145)| `Task`| _Equivalent_ <br/>(14416/14417)| **`Task`**| | | 
| | | | | `TerminologyCapabilities`| _Equivalent_ <br/>(14418/14419)| **`TerminologyCapabilities`**| | | 
| | | `TestReport`| _Equivalent_ <br/>(13146/13147)| `TestReport`| _Equivalent_ <br/>(14420/14421)| **`TestReport`**| | | 
| | | `TestScript`| _Equivalent_ <br/>(13148/13149)| `TestScript`| _Equivalent_ <br/>(14422/14423)| **`TestScript`**| | | 
| | | `ValueSet`| _Equivalent_ <br/>(13150/13151)| `ValueSet`| _Equivalent_ <br/>(14424/14425)| **`ValueSet`**| | | 
| | | | | `VerificationResult`| _Equivalent_ <br/>(14426/14427)| **`VerificationResult`**| | | 
| | | `VisionPrescription`| _Equivalent_ <br/>(13152/13153)| `VisionPrescription`| _Equivalent_ <br/>(14428/14429)| **`VisionPrescription`**| | | 
| | | `Parameters`| _Equivalent_ <br/>(13082/13083)| `Parameters`| _Equivalent_ <br/>(14345/14346)| **`Parameters`**| | | 
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/abstract-types`
| | | `Type`| _Equivalent_ <br/>(13154/13155)| `Type`| _Equivalent_ <br/>(14430/14431)| **`Type`**| | | 
| | | `Any`| _Equivalent_ <br/>(13156/13157)| `Any`| _Equivalent_ <br/>(14432/14433)| **`Any`**| | | 
| | | *162 of 175 codes used* <br/>remaining codes:<br/>`BodySite`, `DataElement`, `DeviceComponent`, `EligibilityRequest`, `EligibilityResponse`, `ExpansionProfile`, `ImagingManifest`, `ProcedureRequest`, `ProcessRequest`, `ProcessResponse`, `ReferralRequest`, `Sequence`, `ServiceDefinition`| | *194 of 213 codes used* <br/>remaining codes:<br/>`SubstanceAmount`, `EffectEvidenceSynthesis`, `MedicinalProduct`, `MedicinalProductAuthorization`, `MedicinalProductContraindication`, `MedicinalProductIndication`, `MedicinalProductIngredient`, `MedicinalProductInteraction`, `MedicinalProductManufactured`, `MedicinalProductPackaged`, `MedicinalProductPharmaceutical`, `MedicinalProductUndesirableEffect`, `RiskEvidenceSynthesis`, `SubstanceNucleicAcid`, `SubstancePolymer`, `SubstanceProtein`, `SubstanceReferenceInformation`, `SubstanceSourceMaterial`, `SubstanceSpecification`| | *209 of 209 codes used* | | 

