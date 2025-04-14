Comparison of 
Generated at Monday, April 14, 2025 6:17:36 PM

### ResourceType

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| VS Name | ResourceType |
| Canonical URL | `http://hl7.org/fhir/ValueSet/resource-types` |
| Version | 4.3.0 |
| Description | One of the resource types defined as part of this version of FHIR. |
| Status | `Active` |
| Has Escape Valve Code | `False` |
| Database Key | `4070` |
| Database Concept Count | `143` |
| Database Active Concept Count | `143` |
### Bindings

| Source | Element | Binding | Strength | Element Short |
| ------ | ------- | ------- | -------- | ------------- |
| `http://hl7.org/fhir/StructureDefinition/Reference` | `Reference.type` | `http://hl7.org/fhir/ValueSet/resource-types` | `Extensible` | Type the reference refers to (e.g. "Patient") |
| `http://hl7.org/fhir/StructureDefinition/CapabilityStatement` | `CapabilityStatement.rest.resource.type` | `http://hl7.org/fhir/ValueSet/resource-types\|4.3.0` | `Required` | A resource type that is supported |
| `http://hl7.org/fhir/StructureDefinition/CompartmentDefinition` | `CompartmentDefinition.resource.code` | `http://hl7.org/fhir/ValueSet/resource-types\|4.3.0` | `Required` | Name of resource type |
| `http://hl7.org/fhir/StructureDefinition/ExampleScenario` | `ExampleScenario.instance.resourceType` | `http://hl7.org/fhir/ValueSet/resource-types\|4.3.0` | `Required` | The type of the resource |
| `http://hl7.org/fhir/StructureDefinition/GraphDefinition` | `GraphDefinition.start` | `http://hl7.org/fhir/ValueSet/resource-types\|4.3.0` | `Required` | Type of resource at which the graph starts |
| `http://hl7.org/fhir/StructureDefinition/GraphDefinition` | `GraphDefinition.link.target.type` | `http://hl7.org/fhir/ValueSet/resource-types\|4.3.0` | `Required` | Type of resource this link refers to |
| `http://hl7.org/fhir/StructureDefinition/ImplementationGuide` | `ImplementationGuide.global.type` | `http://hl7.org/fhir/ValueSet/resource-types\|4.3.0` | `Required` | Type this profile applies to |
| `http://hl7.org/fhir/StructureDefinition/MessageDefinition` | `MessageDefinition.focus.code` | `http://hl7.org/fhir/ValueSet/resource-types\|4.3.0` | `Required` | Type of resource |
| `http://hl7.org/fhir/StructureDefinition/OperationDefinition` | `OperationDefinition.resource` | `http://hl7.org/fhir/ValueSet/resource-types\|4.3.0` | `Required` | Types this operation applies to |
| `http://hl7.org/fhir/StructureDefinition/Questionnaire` | `Questionnaire.subjectType` | `http://hl7.org/fhir/ValueSet/resource-types\|4.3.0` | `Required` | Resource that can be subject of QuestionnaireResponse |
| `http://hl7.org/fhir/StructureDefinition/SearchParameter` | `SearchParameter.base` | `http://hl7.org/fhir/ValueSet/resource-types\|4.3.0` | `Required` | The resource type(s) this search parameter applies to |
| `http://hl7.org/fhir/StructureDefinition/SearchParameter` | `SearchParameter.target` | `http://hl7.org/fhir/ValueSet/resource-types\|4.3.0` | `Required` | Types of resource (if a resource reference) |
| `http://hl7.org/fhir/StructureDefinition/questionnaire-referenceResource` | `Extension.value[x]` | `http://hl7.org/fhir/ValueSet/resource-types` | `Required` | Value of extension |

### Referenced Systems

* `http://hl7.org/fhir/resource-types`
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ResourceType](/docs/R2/ValueSets/ResourceType.md)<br/> `http://hl7.org/fhir/ValueSet/resource-types\|1.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1305`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1306`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ResourceType](/docs/R3/ValueSets/ResourceType.md)<br/> `http://hl7.org/fhir/ValueSet/resource-types\|3.0.2` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1329`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1330`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ResourceType](/docs/R4/ValueSets/ResourceType.md)<br/> `http://hl7.org/fhir/ValueSet/resource-types\|4.0.1` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1715`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1716`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ResourceType](/docs/R4B/ValueSets/ResourceType.md)<br/> `http://hl7.org/fhir/ValueSet/resource-types\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1817`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1818`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ResourceType](/docs/R5/ValueSets/ResourceType.md)<br/> `http://hl7.org/fhir/ValueSet/resource-types\|5.0.0` 

### Code Mappings


#### Map Group 0

This group is centered on the Value Set ResourceType from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All codes from this value set are listed while other value sets only show contents that have relationships with those codes.

| [R2 ResourceType](/docs/R2/ValueSets/ResourceType.md)| Relationship | [R3 ResourceType](/docs/R3/ValueSets/ResourceType.md)| Relationship | [R4 ResourceType](/docs/R4/ValueSets/ResourceType.md)| Relationship | R4B ResourceType| Relationship | [R5 ResourceType](/docs/R5/ValueSets/ResourceType.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| <td colspan="8">**R4B** System: `http://hl7.org/fhir/resource-types`
| `Resource`| _Equivalent_ <br/>(12721/12722)| `Resource`| _Equivalent_ <br/>(13778/13779)| `Resource`| _Equivalent_ <br/>(17359/17360)| **`Resource`**| | | 
| `Binary`| _Equivalent_ <br/>(12576/12577)| `Binary`| _Equivalent_ <br/>(13605/13606)| `Binary`| _Equivalent_ <br/>(17146/17147)| **`Binary`**| _Equivalent_ <br/>(18564/18565)| `Binary`
| `Bundle`| _Equivalent_ <br/>(12580/12581)| `Bundle`| _Equivalent_ <br/>(13608/13609)| `Bundle`| _Equivalent_ <br/>(17152/17153)| **`Bundle`**| _Equivalent_ <br/>(18566/18567)| `Bundle`
| `DomainResource`| _Equivalent_ <br/>(12625/12626)| `DomainResource`| _Equivalent_ <br/>(13662/13663)| `DomainResource`| _Equivalent_ <br/>(17214/17215)| **`DomainResource`**| | | 
| `Account`| _Equivalent_ <br/>(12564/12565)| `Account`| _Equivalent_ <br/>(13589/13590)| `Account`| _Equivalent_ <br/>(17130/17131)| **`Account`**| _Equivalent_ <br/>(18569/18570)| `Account`
| | | `ActivityDefinition`| _Equivalent_ <br/>(13591/13592)| `ActivityDefinition`| _Equivalent_ <br/>(17132/17133)| **`ActivityDefinition`**| _Equivalent_ <br/>(18571/18572)| `ActivityDefinition`
| | | | | | | **`AdministrableProductDefinition`**| _Equivalent_ <br/>(18573/18574)| `AdministrableProductDefinition`
| | | `AdverseEvent`| _Equivalent_ <br/>(13593/13594)| `AdverseEvent`| _Equivalent_ <br/>(17134/17135)| **`AdverseEvent`**| _Equivalent_ <br/>(18575/18576)| `AdverseEvent`
| `AllergyIntolerance`| _Equivalent_ <br/>(12566/12567)| `AllergyIntolerance`| _Equivalent_ <br/>(13595/13596)| `AllergyIntolerance`| _Equivalent_ <br/>(17136/17137)| **`AllergyIntolerance`**| _Equivalent_ <br/>(18577/18578)| `AllergyIntolerance`
| `Appointment`| _Equivalent_ <br/>(12568/12569)| `Appointment`| _Equivalent_ <br/>(13597/13598)| `Appointment`| _Equivalent_ <br/>(17138/17139)| **`Appointment`**| _Equivalent_ <br/>(18579/18580)| `Appointment`
| `AppointmentResponse`| _Equivalent_ <br/>(12570/12571)| `AppointmentResponse`| _Equivalent_ <br/>(13599/13600)| `AppointmentResponse`| _Equivalent_ <br/>(17140/17141)| **`AppointmentResponse`**| _Equivalent_ <br/>(18581/18582)| `AppointmentResponse`
| `AuditEvent`| _Equivalent_ <br/>(12572/12573)| `AuditEvent`| _Equivalent_ <br/>(13601/13602)| `AuditEvent`| _Equivalent_ <br/>(17142/17143)| **`AuditEvent`**| _Equivalent_ <br/>(18583/18584)| `AuditEvent`
| `Basic`| _Equivalent_ <br/>(12574/12575)| `Basic`| _Equivalent_ <br/>(13603/13604)| `Basic`| _Equivalent_ <br/>(17144/17145)| **`Basic`**| _Equivalent_ <br/>(18585/18586)| `Basic`
| | | | | `BiologicallyDerivedProduct`| _Equivalent_ <br/>(17148/17149)| **`BiologicallyDerivedProduct`**| _Equivalent_ <br/>(18587/18588)| `BiologicallyDerivedProduct`
| | | | | `BodyStructure`| _Equivalent_ <br/>(17150/17151)| **`BodyStructure`**| _Equivalent_ <br/>(18589/18590)| `BodyStructure`
| | | `CapabilityStatement`| _Equivalent_ <br/>(13610/13611)| `CapabilityStatement`| _Equivalent_ <br/>(17154/17155)| **`CapabilityStatement`**| _Equivalent_ <br/>(18591/18592)| `CapabilityStatement`
| `CarePlan`| _Equivalent_ <br/>(12582/12583)| `CarePlan`| _Equivalent_ <br/>(13612/13613)| `CarePlan`| _Equivalent_ <br/>(17156/17157)| **`CarePlan`**| _Equivalent_ <br/>(18593/18594)| `CarePlan`
| | | `CareTeam`| _Equivalent_ <br/>(13614/13615)| `CareTeam`| _Equivalent_ <br/>(17158/17159)| **`CareTeam`**| _Equivalent_ <br/>(18595/18596)| `CareTeam`
| | | | | `CatalogEntry`| _Equivalent_ <br/>(17160/17161)| **`CatalogEntry`**| | | 
| | | `ChargeItem`| _Equivalent_ <br/>(13616/13617)| `ChargeItem`| _Equivalent_ <br/>(17162/17163)| **`ChargeItem`**| _Equivalent_ <br/>(18598/18599)| `ChargeItem`
| | | | | `ChargeItemDefinition`| _Equivalent_ <br/>(17164/17165)| **`ChargeItemDefinition`**| _Equivalent_ <br/>(18600/18601)| `ChargeItemDefinition`
| | | | | | | **`Citation`**| _Equivalent_ <br/>(18602/18603)| `Citation`
| `Claim`| _Equivalent_ <br/>(12584/12585)| `Claim`| _Equivalent_ <br/>(13618/13619)| `Claim`| _Equivalent_ <br/>(17166/17167)| **`Claim`**| _Equivalent_ <br/>(18604/18605)| `Claim`
| `ClaimResponse`| _Equivalent_ <br/>(12586/12587)| `ClaimResponse`| _Equivalent_ <br/>(13620/13621)| `ClaimResponse`| _Equivalent_ <br/>(17168/17169)| **`ClaimResponse`**| _Equivalent_ <br/>(18606/18607)| `ClaimResponse`
| `ClinicalImpression`| _Equivalent_ <br/>(12588/12589)| `ClinicalImpression`| _Equivalent_ <br/>(13622/13623)| `ClinicalImpression`| _Equivalent_ <br/>(17170/17171)| **`ClinicalImpression`**| _Equivalent_ <br/>(18608/18609)| `ClinicalImpression`
| | | | | | | **`ClinicalUseDefinition`**| _Equivalent_ <br/>(18610/18611)| `ClinicalUseDefinition`
| | | `CodeSystem`| _Equivalent_ <br/>(13624/13625)| `CodeSystem`| _Equivalent_ <br/>(17172/17173)| **`CodeSystem`**| _Equivalent_ <br/>(18612/18613)| `CodeSystem`
| `Communication`| _Equivalent_ <br/>(12590/12591)| `Communication`| _Equivalent_ <br/>(13626/13627)| `Communication`| _Equivalent_ <br/>(17174/17175)| **`Communication`**| _Equivalent_ <br/>(18614/18615)| `Communication`
| `CommunicationRequest`| _Equivalent_ <br/>(12592/12593)| `CommunicationRequest`| _Equivalent_ <br/>(13628/13629)| `CommunicationRequest`| _Equivalent_ <br/>(17176/17177)| **`CommunicationRequest`**| _Equivalent_ <br/>(18616/18617)| `CommunicationRequest`
| | | `CompartmentDefinition`| _Equivalent_ <br/>(13630/13631)| `CompartmentDefinition`| _Equivalent_ <br/>(17178/17179)| **`CompartmentDefinition`**| _Equivalent_ <br/>(18618/18619)| `CompartmentDefinition`
| `Composition`| _Equivalent_ <br/>(12594/12595)| `Composition`| _Equivalent_ <br/>(13632/13633)| `Composition`| _Equivalent_ <br/>(17180/17181)| **`Composition`**| _Equivalent_ <br/>(18620/18621)| `Composition`
| `ConceptMap`| _Equivalent_ <br/>(12596/12597)| `ConceptMap`| _Equivalent_ <br/>(13634/13635)| `ConceptMap`| _Equivalent_ <br/>(17182/17183)| **`ConceptMap`**| _Equivalent_ <br/>(18622/18623)| `ConceptMap`
| `Condition`| _Equivalent_ <br/>(12598/12599)| `Condition`| _Equivalent_ <br/>(13636/13637)| `Condition`| _Equivalent_ <br/>(17184/17185)| **`Condition`**| _Equivalent_ <br/>(18624/18625)| `Condition`
| | | `Consent`| _Equivalent_ <br/>(13638/13639)| `Consent`| _Equivalent_ <br/>(17186/17187)| **`Consent`**| _Equivalent_ <br/>(18626/18627)| `Consent`
| `Contract`| _Equivalent_ <br/>(12601/12602)| `Contract`| _Equivalent_ <br/>(13640/13641)| `Contract`| _Equivalent_ <br/>(17188/17189)| **`Contract`**| _Equivalent_ <br/>(18628/18629)| `Contract`
| `Coverage`| _Equivalent_ <br/>(12603/12604)| `Coverage`| _Equivalent_ <br/>(13642/13643)| `Coverage`| _Equivalent_ <br/>(17190/17191)| **`Coverage`**| _Equivalent_ <br/>(18630/18631)| `Coverage`
| | | | | `CoverageEligibilityRequest`| _Equivalent_ <br/>(17192/17193)| **`CoverageEligibilityRequest`**| _Equivalent_ <br/>(18632/18633)| `CoverageEligibilityRequest`
| | | | | `CoverageEligibilityResponse`| _Equivalent_ <br/>(17194/17195)| **`CoverageEligibilityResponse`**| _Equivalent_ <br/>(18634/18635)| `CoverageEligibilityResponse`
| `DetectedIssue`| _Equivalent_ <br/>(12607/12608)| `DetectedIssue`| _Equivalent_ <br/>(13645/13646)| `DetectedIssue`| _Equivalent_ <br/>(17196/17197)| **`DetectedIssue`**| _Equivalent_ <br/>(18636/18637)| `DetectedIssue`
| `Device`| _Equivalent_ <br/>(12609/12610)| `Device`| _Equivalent_ <br/>(13647/13648)| `Device`| _Equivalent_ <br/>(17198/17199)| **`Device`**| _Equivalent_ <br/>(18638/18639)| `Device`
| | | | | `DeviceDefinition`| _Equivalent_ <br/>(17200/17201)| **`DeviceDefinition`**| _Equivalent_ <br/>(18640/18641)| `DeviceDefinition`
| `DeviceMetric`| _Equivalent_ <br/>(12613/12614)| `DeviceMetric`| _Equivalent_ <br/>(13650/13651)| `DeviceMetric`| _Equivalent_ <br/>(17202/17203)| **`DeviceMetric`**| _Equivalent_ <br/>(18642/18643)| `DeviceMetric`
| | | `DeviceRequest`| _Equivalent_ <br/>(13652/13653)| `DeviceRequest`| _Equivalent_ <br/>(17204/17205)| **`DeviceRequest`**| _Equivalent_ <br/>(18644/18645)| `DeviceRequest`
| `DeviceUseStatement`| _Equivalent_ <br/>(12616/12617)| `DeviceUseStatement`| _Equivalent_ <br/>(13654/13655)| `DeviceUseStatement`| _Equivalent_ <br/>(17206/17207)| **`DeviceUseStatement`**| | | 
| `DiagnosticReport`| _Equivalent_ <br/>(12619/12620)| `DiagnosticReport`| _Equivalent_ <br/>(13656/13657)| `DiagnosticReport`| _Equivalent_ <br/>(17208/17209)| **`DiagnosticReport`**| _Equivalent_ <br/>(18647/18648)| `DiagnosticReport`
| `DocumentManifest`| _Equivalent_ <br/>(12621/12622)| `DocumentManifest`| _Equivalent_ <br/>(13658/13659)| `DocumentManifest`| _Equivalent_ <br/>(17210/17211)| **`DocumentManifest`**| | | 
| `DocumentReference`| _Equivalent_ <br/>(12623/12624)| `DocumentReference`| _Equivalent_ <br/>(13660/13661)| `DocumentReference`| _Equivalent_ <br/>(17212/17213)| **`DocumentReference`**| _Equivalent_ <br/>(18650/18651)| `DocumentReference`
| `Encounter`| _Equivalent_ <br/>(12631/12632)| `Encounter`| _Equivalent_ <br/>(13666/13667)| `Encounter`| _Equivalent_ <br/>(17217/17218)| **`Encounter`**| _Equivalent_ <br/>(18652/18653)| `Encounter`
| | | `Endpoint`| _Equivalent_ <br/>(13668/13669)| `Endpoint`| _Equivalent_ <br/>(17219/17220)| **`Endpoint`**| _Equivalent_ <br/>(18654/18655)| `Endpoint`
| `EnrollmentRequest`| _Equivalent_ <br/>(12633/12634)| `EnrollmentRequest`| _Equivalent_ <br/>(13670/13671)| `EnrollmentRequest`| _Equivalent_ <br/>(17221/17222)| **`EnrollmentRequest`**| _Equivalent_ <br/>(18656/18657)| `EnrollmentRequest`
| `EnrollmentResponse`| _Equivalent_ <br/>(12635/12636)| `EnrollmentResponse`| _Equivalent_ <br/>(13672/13673)| `EnrollmentResponse`| _Equivalent_ <br/>(17223/17224)| **`EnrollmentResponse`**| _Equivalent_ <br/>(18658/18659)| `EnrollmentResponse`
| `EpisodeOfCare`| _Equivalent_ <br/>(12637/12638)| `EpisodeOfCare`| _Equivalent_ <br/>(13674/13675)| `EpisodeOfCare`| _Equivalent_ <br/>(17225/17226)| **`EpisodeOfCare`**| _Equivalent_ <br/>(18660/18661)| `EpisodeOfCare`
| | | | | `EventDefinition`| _Equivalent_ <br/>(17227/17228)| **`EventDefinition`**| _Equivalent_ <br/>(18662/18663)| `EventDefinition`
| | | | | `Evidence`| _Equivalent_ <br/>(17229/17230)| **`Evidence`**| _Equivalent_ <br/>(18664/18665)| `Evidence`
| | | | | | | **`EvidenceReport`**| _Equivalent_ <br/>(18666/18667)| `EvidenceReport`
| | | | | `EvidenceVariable`| _Equivalent_ <br/>(17231/17232)| **`EvidenceVariable`**| _Equivalent_ <br/>(18668/18669)| `EvidenceVariable`
| | | | | `ExampleScenario`| _Equivalent_ <br/>(17233/17234)| **`ExampleScenario`**| _Equivalent_ <br/>(18670/18671)| `ExampleScenario`
| `ExplanationOfBenefit`| _Equivalent_ <br/>(12639/12640)| `ExplanationOfBenefit`| _Equivalent_ <br/>(13677/13678)| `ExplanationOfBenefit`| _Equivalent_ <br/>(17235/17236)| **`ExplanationOfBenefit`**| _Equivalent_ <br/>(18672/18673)| `ExplanationOfBenefit`
| `FamilyMemberHistory`| _Equivalent_ <br/>(12641/12642)| `FamilyMemberHistory`| _Equivalent_ <br/>(13679/13680)| `FamilyMemberHistory`| _Equivalent_ <br/>(17237/17238)| **`FamilyMemberHistory`**| _Equivalent_ <br/>(18674/18675)| `FamilyMemberHistory`
| `Flag`| _Equivalent_ <br/>(12643/12644)| `Flag`| _Equivalent_ <br/>(13681/13682)| `Flag`| _Equivalent_ <br/>(17239/17240)| **`Flag`**| _Equivalent_ <br/>(18676/18677)| `Flag`
| `Goal`| _Equivalent_ <br/>(12645/12646)| `Goal`| _Equivalent_ <br/>(13683/13684)| `Goal`| _Equivalent_ <br/>(17241/17242)| **`Goal`**| _Equivalent_ <br/>(18678/18679)| `Goal`
| | | `GraphDefinition`| _Equivalent_ <br/>(13685/13686)| `GraphDefinition`| _Equivalent_ <br/>(17243/17244)| **`GraphDefinition`**| _Equivalent_ <br/>(18680/18681)| `GraphDefinition`
| `Group`| _Equivalent_ <br/>(12647/12648)| `Group`| _Equivalent_ <br/>(13687/13688)| `Group`| _Equivalent_ <br/>(17245/17246)| **`Group`**| _Equivalent_ <br/>(18682/18683)| `Group`
| | | `GuidanceResponse`| _Equivalent_ <br/>(13689/13690)| `GuidanceResponse`| _Equivalent_ <br/>(17247/17248)| **`GuidanceResponse`**| _Equivalent_ <br/>(18684/18685)| `GuidanceResponse`
| `HealthcareService`| _Equivalent_ <br/>(12649/12650)| `HealthcareService`| _Equivalent_ <br/>(13691/13692)| `HealthcareService`| _Equivalent_ <br/>(17249/17250)| **`HealthcareService`**| _Equivalent_ <br/>(18686/18687)| `HealthcareService`
| `ImagingStudy`| _Equivalent_ <br/>(12652/12653)| `ImagingStudy`| _Equivalent_ <br/>(13694/13695)| `ImagingStudy`| _Equivalent_ <br/>(17251/17252)| **`ImagingStudy`**| _Equivalent_ <br/>(18688/18689)| `ImagingStudy`
| `Immunization`| _Equivalent_ <br/>(12654/12655)| `Immunization`| _Equivalent_ <br/>(13696/13697)| `Immunization`| _Equivalent_ <br/>(17253/17254)| **`Immunization`**| _Equivalent_ <br/>(18690/18691)| `Immunization`
| | | | | `ImmunizationEvaluation`| _Equivalent_ <br/>(17255/17256)| **`ImmunizationEvaluation`**| _Equivalent_ <br/>(18692/18693)| `ImmunizationEvaluation`
| `ImmunizationRecommendation`| _Equivalent_ <br/>(12656/12657)| `ImmunizationRecommendation`| _Equivalent_ <br/>(13698/13699)| `ImmunizationRecommendation`| _Equivalent_ <br/>(17257/17258)| **`ImmunizationRecommendation`**| _Equivalent_ <br/>(18694/18695)| `ImmunizationRecommendation`
| `ImplementationGuide`| _Equivalent_ <br/>(12658/12659)| `ImplementationGuide`| _Equivalent_ <br/>(13700/13701)| `ImplementationGuide`| _Equivalent_ <br/>(17259/17260)| **`ImplementationGuide`**| _Equivalent_ <br/>(18696/18697)| `ImplementationGuide`
| | | | | | | **`Ingredient`**| _Equivalent_ <br/>(18698/18699)| `Ingredient`
| | | | | `InsurancePlan`| _Equivalent_ <br/>(17261/17262)| **`InsurancePlan`**| _Equivalent_ <br/>(18700/18701)| `InsurancePlan`
| | | | | `Invoice`| _Equivalent_ <br/>(17263/17264)| **`Invoice`**| _Equivalent_ <br/>(18702/18703)| `Invoice`
| | | `Library`| _Equivalent_ <br/>(13702/13703)| `Library`| _Equivalent_ <br/>(17265/17266)| **`Library`**| _Equivalent_ <br/>(18704/18705)| `Library`
| | | `Linkage`| _Equivalent_ <br/>(13704/13705)| `Linkage`| _Equivalent_ <br/>(17267/17268)| **`Linkage`**| _Equivalent_ <br/>(18706/18707)| `Linkage`
| `List`| _Equivalent_ <br/>(12660/12661)| `List`| _Equivalent_ <br/>(13706/13707)| `List`| _Equivalent_ <br/>(17269/17270)| **`List`**| _Equivalent_ <br/>(18708/18709)| `List`
| `Location`| _Equivalent_ <br/>(12662/12663)| `Location`| _Equivalent_ <br/>(13708/13709)| `Location`| _Equivalent_ <br/>(17271/17272)| **`Location`**| _Equivalent_ <br/>(18710/18711)| `Location`
| | | | | | | **`ManufacturedItemDefinition`**| _Equivalent_ <br/>(18712/18713)| `ManufacturedItemDefinition`
| | | `Measure`| _Equivalent_ <br/>(13710/13711)| `Measure`| _Equivalent_ <br/>(17273/17274)| **`Measure`**| _Equivalent_ <br/>(18714/18715)| `Measure`
| | | `MeasureReport`| _Equivalent_ <br/>(13712/13713)| `MeasureReport`| _Equivalent_ <br/>(17275/17276)| **`MeasureReport`**| _Equivalent_ <br/>(18716/18717)| `MeasureReport`
| `Media`| _Equivalent_ <br/>(12664/12665)| `Media`| _Equivalent_ <br/>(13714/13715)| `Media`| _Equivalent_ <br/>(17277/17278)| **`Media`**| | | 
| `Medication`| _Equivalent_ <br/>(12666/12667)| `Medication`| _Equivalent_ <br/>(13716/13717)| `Medication`| _Equivalent_ <br/>(17279/17280)| **`Medication`**| _Equivalent_ <br/>(18719/18720)| `Medication`
| `MedicationAdministration`| _Equivalent_ <br/>(12668/12669)| `MedicationAdministration`| _Equivalent_ <br/>(13718/13719)| `MedicationAdministration`| _Equivalent_ <br/>(17281/17282)| **`MedicationAdministration`**| _Equivalent_ <br/>(18721/18722)| `MedicationAdministration`
| `MedicationDispense`| _Equivalent_ <br/>(12670/12671)| `MedicationDispense`| _Equivalent_ <br/>(13720/13721)| `MedicationDispense`| _Equivalent_ <br/>(17283/17284)| **`MedicationDispense`**| _Equivalent_ <br/>(18723/18724)| `MedicationDispense`
| | | | | `MedicationKnowledge`| _Equivalent_ <br/>(17285/17286)| **`MedicationKnowledge`**| _Equivalent_ <br/>(18725/18726)| `MedicationKnowledge`
| | | `MedicationRequest`| _Equivalent_ <br/>(13722/13723)| `MedicationRequest`| _Equivalent_ <br/>(17287/17288)| **`MedicationRequest`**| _Equivalent_ <br/>(18727/18728)| `MedicationRequest`
| `MedicationStatement`| _Equivalent_ <br/>(12673/12674)| `MedicationStatement`| _Equivalent_ <br/>(13724/13725)| `MedicationStatement`| _Equivalent_ <br/>(17289/17290)| **`MedicationStatement`**| _Equivalent_ <br/>(18729/18730)| `MedicationStatement`
| | | | | | | **`MedicinalProductDefinition`**| _Equivalent_ <br/>(18731/18732)| `MedicinalProductDefinition`
| | | `MessageDefinition`| _Equivalent_ <br/>(13726/13727)| `MessageDefinition`| _Equivalent_ <br/>(17301/17302)| **`MessageDefinition`**| _Equivalent_ <br/>(18733/18734)| `MessageDefinition`
| `MessageHeader`| _Equivalent_ <br/>(12675/12676)| `MessageHeader`| _Equivalent_ <br/>(13728/13729)| `MessageHeader`| _Equivalent_ <br/>(17303/17304)| **`MessageHeader`**| _Equivalent_ <br/>(18735/18736)| `MessageHeader`
| | | | | `MolecularSequence`| _Equivalent_ <br/>(17305/17306)| **`MolecularSequence`**| _Equivalent_ <br/>(18737/18738)| `MolecularSequence`
| `NamingSystem`| _Equivalent_ <br/>(12677/12678)| `NamingSystem`| _Equivalent_ <br/>(13730/13731)| `NamingSystem`| _Equivalent_ <br/>(17307/17308)| **`NamingSystem`**| _Equivalent_ <br/>(18739/18740)| `NamingSystem`
| `NutritionOrder`| _Equivalent_ <br/>(12679/12680)| `NutritionOrder`| _Equivalent_ <br/>(13732/13733)| `NutritionOrder`| _Equivalent_ <br/>(17309/17310)| **`NutritionOrder`**| _Equivalent_ <br/>(18741/18742)| `NutritionOrder`
| | | | | | | **`NutritionProduct`**| _Equivalent_ <br/>(18743/18744)| `NutritionProduct`
| `Observation`| _Equivalent_ <br/>(12681/12682)| `Observation`| _Equivalent_ <br/>(13734/13735)| `Observation`| _Equivalent_ <br/>(17311/17312)| **`Observation`**| _Equivalent_ <br/>(18745/18746)| `Observation`
| | | | | `ObservationDefinition`| _Equivalent_ <br/>(17313/17314)| **`ObservationDefinition`**| _Equivalent_ <br/>(18747/18748)| `ObservationDefinition`
| `OperationDefinition`| _Equivalent_ <br/>(12683/12684)| `OperationDefinition`| _Equivalent_ <br/>(13736/13737)| `OperationDefinition`| _Equivalent_ <br/>(17315/17316)| **`OperationDefinition`**| _Equivalent_ <br/>(18749/18750)| `OperationDefinition`
| `OperationOutcome`| _Equivalent_ <br/>(12685/12686)| `OperationOutcome`| _Equivalent_ <br/>(13738/13739)| `OperationOutcome`| _Equivalent_ <br/>(17317/17318)| **`OperationOutcome`**| _Equivalent_ <br/>(18751/18752)| `OperationOutcome`
| `Organization`| _Equivalent_ <br/>(12689/12690)| `Organization`| _Equivalent_ <br/>(13740/13741)| `Organization`| _Equivalent_ <br/>(17319/17320)| **`Organization`**| _Equivalent_ <br/>(18753/18754)| `Organization`
| | | | | `OrganizationAffiliation`| _Equivalent_ <br/>(17321/17322)| **`OrganizationAffiliation`**| _Equivalent_ <br/>(18755/18756)| `OrganizationAffiliation`
| | | | | | | **`PackagedProductDefinition`**| _Equivalent_ <br/>(18757/18758)| `PackagedProductDefinition`
| `Patient`| _Equivalent_ <br/>(12693/12694)| `Patient`| _Equivalent_ <br/>(13744/13745)| `Patient`| _Equivalent_ <br/>(17325/17326)| **`Patient`**| _Equivalent_ <br/>(18759/18760)| `Patient`
| `PaymentNotice`| _Equivalent_ <br/>(12695/12696)| `PaymentNotice`| _Equivalent_ <br/>(13746/13747)| `PaymentNotice`| _Equivalent_ <br/>(17327/17328)| **`PaymentNotice`**| _Equivalent_ <br/>(18761/18762)| `PaymentNotice`
| `PaymentReconciliation`| _Equivalent_ <br/>(12697/12698)| `PaymentReconciliation`| _Equivalent_ <br/>(13748/13749)| `PaymentReconciliation`| _Equivalent_ <br/>(17329/17330)| **`PaymentReconciliation`**| _Equivalent_ <br/>(18763/18764)| `PaymentReconciliation`
| `Person`| _Equivalent_ <br/>(12699/12700)| `Person`| _Equivalent_ <br/>(13750/13751)| `Person`| _Equivalent_ <br/>(17331/17332)| **`Person`**| _Equivalent_ <br/>(18765/18766)| `Person`
| | | `PlanDefinition`| _Equivalent_ <br/>(13752/13753)| `PlanDefinition`| _Equivalent_ <br/>(17333/17334)| **`PlanDefinition`**| _Equivalent_ <br/>(18767/18768)| `PlanDefinition`
| `Practitioner`| _Equivalent_ <br/>(12701/12702)| `Practitioner`| _Equivalent_ <br/>(13754/13755)| `Practitioner`| _Equivalent_ <br/>(17335/17336)| **`Practitioner`**| _Equivalent_ <br/>(18769/18770)| `Practitioner`
| | | `PractitionerRole`| _Equivalent_ <br/>(13756/13757)| `PractitionerRole`| _Equivalent_ <br/>(17337/17338)| **`PractitionerRole`**| _Equivalent_ <br/>(18771/18772)| `PractitionerRole`
| `Procedure`| _Equivalent_ <br/>(12703/12704)| `Procedure`| _Equivalent_ <br/>(13758/13759)| `Procedure`| _Equivalent_ <br/>(17339/17340)| **`Procedure`**| _Equivalent_ <br/>(18773/18774)| `Procedure`
| `Provenance`| _Equivalent_ <br/>(12711/12712)| `Provenance`| _Equivalent_ <br/>(13763/13764)| `Provenance`| _Equivalent_ <br/>(17341/17342)| **`Provenance`**| _Equivalent_ <br/>(18775/18776)| `Provenance`
| `Questionnaire`| _Equivalent_ <br/>(12713/12714)| `Questionnaire`| _Equivalent_ <br/>(13765/13766)| `Questionnaire`| _Equivalent_ <br/>(17343/17344)| **`Questionnaire`**| _Equivalent_ <br/>(18777/18778)| `Questionnaire`
| `QuestionnaireResponse`| _Equivalent_ <br/>(12715/12716)| `QuestionnaireResponse`| _Equivalent_ <br/>(13767/13768)| `QuestionnaireResponse`| _Equivalent_ <br/>(17345/17346)| **`QuestionnaireResponse`**| _Equivalent_ <br/>(18779/18780)| `QuestionnaireResponse`
| | | | | | | **`RegulatedAuthorization`**| _Equivalent_ <br/>(18781/18782)| `RegulatedAuthorization`
| `RelatedPerson`| _Equivalent_ <br/>(12719/12720)| `RelatedPerson`| _Equivalent_ <br/>(13770/13771)| `RelatedPerson`| _Equivalent_ <br/>(17347/17348)| **`RelatedPerson`**| _Equivalent_ <br/>(18783/18784)| `RelatedPerson`
| | | `RequestGroup`| _Equivalent_ <br/>(13772/13773)| `RequestGroup`| _Equivalent_ <br/>(17349/17350)| **`RequestGroup`**| | | 
| | | | | `ResearchDefinition`| _Equivalent_ <br/>(17351/17352)| **`ResearchDefinition`**| | | 
| | | | | `ResearchElementDefinition`| _Equivalent_ <br/>(17353/17354)| **`ResearchElementDefinition`**| | | 
| | | `ResearchStudy`| _Equivalent_ <br/>(13774/13775)| `ResearchStudy`| _Equivalent_ <br/>(17355/17356)| **`ResearchStudy`**| _Equivalent_ <br/>(18788/18789)| `ResearchStudy`
| | | `ResearchSubject`| _Equivalent_ <br/>(13776/13777)| `ResearchSubject`| _Equivalent_ <br/>(17357/17358)| **`ResearchSubject`**| _Equivalent_ <br/>(18790/18791)| `ResearchSubject`
| `RiskAssessment`| _Equivalent_ <br/>(12723/12724)| `RiskAssessment`| _Equivalent_ <br/>(13780/13781)| `RiskAssessment`| _Equivalent_ <br/>(17361/17362)| **`RiskAssessment`**| _Equivalent_ <br/>(18792/18793)| `RiskAssessment`
| `Schedule`| _Equivalent_ <br/>(12725/12726)| `Schedule`| _Equivalent_ <br/>(13782/13783)| `Schedule`| _Equivalent_ <br/>(17364/17365)| **`Schedule`**| _Equivalent_ <br/>(18794/18795)| `Schedule`
| `SearchParameter`| _Equivalent_ <br/>(12727/12728)| `SearchParameter`| _Equivalent_ <br/>(13784/13785)| `SearchParameter`| _Equivalent_ <br/>(17366/17367)| **`SearchParameter`**| _Equivalent_ <br/>(18796/18797)| `SearchParameter`
| | | | | `ServiceRequest`| _Equivalent_ <br/>(17368/17369)| **`ServiceRequest`**| _Equivalent_ <br/>(18798/18799)| `ServiceRequest`
| `Slot`| _Equivalent_ <br/>(12729/12730)| `Slot`| _Equivalent_ <br/>(13788/13789)| `Slot`| _Equivalent_ <br/>(17370/17371)| **`Slot`**| _Equivalent_ <br/>(18800/18801)| `Slot`
| `Specimen`| _Equivalent_ <br/>(12731/12732)| `Specimen`| _Equivalent_ <br/>(13790/13791)| `Specimen`| _Equivalent_ <br/>(17372/17373)| **`Specimen`**| _Equivalent_ <br/>(18802/18803)| `Specimen`
| | | | | `SpecimenDefinition`| _Equivalent_ <br/>(17374/17375)| **`SpecimenDefinition`**| _Equivalent_ <br/>(18804/18805)| `SpecimenDefinition`
| `StructureDefinition`| _Equivalent_ <br/>(12733/12734)| `StructureDefinition`| _Equivalent_ <br/>(13792/13793)| `StructureDefinition`| _Equivalent_ <br/>(17376/17377)| **`StructureDefinition`**| _Equivalent_ <br/>(18806/18807)| `StructureDefinition`
| | | `StructureMap`| _Equivalent_ <br/>(13794/13795)| `StructureMap`| _Equivalent_ <br/>(17378/17379)| **`StructureMap`**| _Equivalent_ <br/>(18808/18809)| `StructureMap`
| `Subscription`| _Equivalent_ <br/>(12735/12736)| `Subscription`| _Equivalent_ <br/>(13796/13797)| `Subscription`| _Equivalent_ <br/>(17380/17381)| **`Subscription`**| _Equivalent_ <br/>(18810/18811)| `Subscription`
| | | | | | | **`SubscriptionStatus`**| _Equivalent_ <br/>(18812/18813)| `SubscriptionStatus`
| | | | | | | **`SubscriptionTopic`**| _Equivalent_ <br/>(18814/18815)| `SubscriptionTopic`
| `Substance`| _Equivalent_ <br/>(12737/12738)| `Substance`| _Equivalent_ <br/>(13798/13799)| `Substance`| _Equivalent_ <br/>(17382/17383)| **`Substance`**| _Equivalent_ <br/>(18816/18817)| `Substance`
| | | | | | | **`SubstanceDefinition`**| _Equivalent_ <br/>(18818/18819)| `SubstanceDefinition`
| `SupplyDelivery`| _Equivalent_ <br/>(12739/12740)| `SupplyDelivery`| _Equivalent_ <br/>(13800/13801)| `SupplyDelivery`| _Equivalent_ <br/>(17390/17391)| **`SupplyDelivery`**| _Equivalent_ <br/>(18820/18821)| `SupplyDelivery`
| `SupplyRequest`| _Equivalent_ <br/>(12741/12742)| `SupplyRequest`| _Equivalent_ <br/>(13802/13803)| `SupplyRequest`| _Equivalent_ <br/>(17392/17393)| **`SupplyRequest`**| _Equivalent_ <br/>(18822/18823)| `SupplyRequest`
| | | `Task`| _Equivalent_ <br/>(13804/13805)| `Task`| _Equivalent_ <br/>(17394/17395)| **`Task`**| _Equivalent_ <br/>(18824/18825)| `Task`
| | | | | `TerminologyCapabilities`| _Equivalent_ <br/>(17396/17397)| **`TerminologyCapabilities`**| _Equivalent_ <br/>(18826/18827)| `TerminologyCapabilities`
| | | `TestReport`| _Equivalent_ <br/>(13806/13807)| `TestReport`| _Equivalent_ <br/>(17398/17399)| **`TestReport`**| _Equivalent_ <br/>(18828/18829)| `TestReport`
| `TestScript`| _Equivalent_ <br/>(12743/12744)| `TestScript`| _Equivalent_ <br/>(13808/13809)| `TestScript`| _Equivalent_ <br/>(17400/17401)| **`TestScript`**| _Equivalent_ <br/>(18830/18831)| `TestScript`
| `ValueSet`| _Equivalent_ <br/>(12745/12746)| `ValueSet`| _Equivalent_ <br/>(13810/13811)| `ValueSet`| _Equivalent_ <br/>(17402/17403)| **`ValueSet`**| _Equivalent_ <br/>(18832/18833)| `ValueSet`
| | | | | `VerificationResult`| _Equivalent_ <br/>(17404/17405)| **`VerificationResult`**| _Equivalent_ <br/>(18834/18835)| `VerificationResult`
| `VisionPrescription`| _Equivalent_ <br/>(12747/12748)| `VisionPrescription`| _Equivalent_ <br/>(13812/13813)| `VisionPrescription`| _Equivalent_ <br/>(17406/17407)| **`VisionPrescription`**| _Equivalent_ <br/>(18836/18837)| `VisionPrescription`
| `Parameters`| _Equivalent_ <br/>(12691/12692)| `Parameters`| _Equivalent_ <br/>(13742/13743)| `Parameters`| _Equivalent_ <br/>(17323/17324)| **`Parameters`**| _Equivalent_ <br/>(18838/18839)| `Parameters`
| *80 of 96 codes used* <br/>remaining codes:<br/>`BodySite`, `Conformance`, `DataElement`, `DeviceComponent`, `DeviceUseRequest`, `DiagnosticOrder`, `EligibilityRequest`, `EligibilityResponse`, `ImagingObjectSelection`, `MedicationOrder`, `Order`, `OrderResponse`, `ProcedureRequest`, `ProcessRequest`, `ProcessResponse`, `ReferralRequest`| | *106 of 119 codes used* <br/>remaining codes:<br/>`BodySite`, `DataElement`, `DeviceComponent`, `EligibilityRequest`, `EligibilityResponse`, `ExpansionProfile`, `ImagingManifest`, `ProcedureRequest`, `ProcessRequest`, `ProcessResponse`, `ReferralRequest`, `Sequence`, `ServiceDefinition`| | *130 of 148 codes used* <br/>remaining codes:<br/>`EffectEvidenceSynthesis`, `MedicinalProduct`, `MedicinalProductAuthorization`, `MedicinalProductContraindication`, `MedicinalProductIndication`, `MedicinalProductIngredient`, `MedicinalProductInteraction`, `MedicinalProductManufactured`, `MedicinalProductPackaged`, `MedicinalProductPharmaceutical`, `MedicinalProductUndesirableEffect`, `RiskEvidenceSynthesis`, `SubstanceNucleicAcid`, `SubstancePolymer`, `SubstanceProtein`, `SubstanceReferenceInformation`, `SubstanceSourceMaterial`, `SubstanceSpecification`| | *143 of 143 codes used* | | *134 of 158 codes used* <br/>remaining codes:<br/>`ActorDefinition`, `ArtifactAssessment`, `BiologicallyDerivedProductDispense`, `ConditionDefinition`, `DeviceAssociation`, `DeviceDispense`, `DeviceUsage`, `EncounterHistory`, `FormularyItem`, `GenomicStudy`, `ImagingSelection`, `InventoryItem`, `InventoryReport`, `NutritionIntake`, `Permission`, `RequestOrchestration`, `Requirements`, `SubstanceNucleicAcid`, `SubstancePolymer`, `SubstanceProtein`, `SubstanceReferenceInformation`, `SubstanceSourceMaterial`, `TestPlan`, `Transport`

