Comparison of 
Generated at Monday, April 14, 2025 6:17:24 PM

### ResearchStudy

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | ResearchStudy |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ResearchStudy` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for ResearchStudy Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `573` |
| Database Snapshot Count | `35` |
| Database Differential Count | `24` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ResearchStudy` | `ResearchStudy` | `ResearchStudy` | ResearchStudy | Investigation to increase healthcare-related patient-independent knowledge | 0..* | ResearchStudy |  |  |
| `ResearchStudy.arm` | `ResearchStudy.arm` | `arm` |  | Defined path through the study for a subject | 0..* | BackboneElement |  |  |
| `ResearchStudy.arm.code` | `ResearchStudy.arm.code` | `code` |  | Categorization of study arm | 0..1 | CodeableConcept |  |  |
| `ResearchStudy.arm.description` | `ResearchStudy.arm.description` | `description` |  | Short explanation of study path | 0..1 | string |  |  |
| `ResearchStudy.arm.extension` | `ResearchStudy.arm.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ResearchStudy.arm.id` | `ResearchStudy.arm.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ResearchStudy.arm.modifierExtension` | `ResearchStudy.arm.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ResearchStudy.arm.name` | `ResearchStudy.arm.name` | `name` |  | Label for study arm | 1..1 | string |  |  |
| `ResearchStudy.category` | `ResearchStudy.category` | `category` |  | Classifications for the study | 0..* | CodeableConcept | `Example` |  |
| `ResearchStudy.contact` | `ResearchStudy.contact` | `contact` |  | Contact details for the study | 0..* | ContactDetail |  |  |
| `ResearchStudy.contained` | `ResearchStudy.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ResearchStudy.description` | `ResearchStudy.description` | `description` |  | What this is study doing | 0..1 | markdown |  |  |
| `ResearchStudy.enrollment` | `ResearchStudy.enrollment` | `enrollment` |  | Inclusion & exclusion criteria | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Group) |  |  |
| `ResearchStudy.extension` | `ResearchStudy.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ResearchStudy.focus` | `ResearchStudy.focus` | `focus` |  | Drugs, devices, conditions, etc. under study | 0..* | CodeableConcept | `Example` |  |
| `ResearchStudy.id` | `ResearchStudy.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ResearchStudy.identifier` | `ResearchStudy.identifier` | `identifier` |  | Business Identifier for study | 0..* | Identifier |  |  |
| `ResearchStudy.implicitRules` | `ResearchStudy.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ResearchStudy.jurisdiction` | `ResearchStudy.jurisdiction` | `jurisdiction` |  | Geographic region(s) for study | 0..* | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/jurisdiction` |
| `ResearchStudy.keyword` | `ResearchStudy.keyword` | `keyword` |  | Used to search for the study | 0..* | CodeableConcept | `Example` |  |
| `ResearchStudy.language` | `ResearchStudy.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `ResearchStudy.meta` | `ResearchStudy.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ResearchStudy.modifierExtension` | `ResearchStudy.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ResearchStudy.note` | `ResearchStudy.note` | `note` |  | Comments made about the event | 0..* | Annotation |  |  |
| `ResearchStudy.partOf` | `ResearchStudy.partOf` | `partOf` |  | Part of larger study | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ResearchStudy) |  |  |
| `ResearchStudy.period` | `ResearchStudy.period` | `period` |  | When the study began and ended | 0..1 | Period |  |  |
| `ResearchStudy.principalInvestigator` | `ResearchStudy.principalInvestigator` | `principalInvestigator` |  | The individual responsible for the study | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `ResearchStudy.protocol` | `ResearchStudy.protocol` | `protocol` |  | Steps followed in executing study | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/PlanDefinition) |  |  |
| `ResearchStudy.reasonStopped` | `ResearchStudy.reasonStopped` | `reasonStopped` |  | Reason for terminating study early | 0..1 | CodeableConcept |  |  |
| `ResearchStudy.relatedArtifact` | `ResearchStudy.relatedArtifact` | `relatedArtifact` |  | References and dependencies | 0..* | RelatedArtifact |  |  |
| `ResearchStudy.site` | `ResearchStudy.site` | `site` |  | Location involved in study execution | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `ResearchStudy.sponsor` | `ResearchStudy.sponsor` | `sponsor` |  | Organization responsible for the study | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `ResearchStudy.status` | `ResearchStudy.status` | `status` |  | draft \| in-progress \| suspended \| stopped \| completed \| entered-in-error | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/research-study-status` |
| `ResearchStudy.text` | `ResearchStudy.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `ResearchStudy.title` | `ResearchStudy.title` | `title` |  | Name for this study | 0..1 | string |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [ResearchStudy](/docs/R3/Resources/ResearchStudy.md)<br/> `http://hl7.org/fhir/StructureDefinition/ResearchStudy\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `510`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `702`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ResearchStudy](/docs/R4/Resources/ResearchStudy.md)<br/> `http://hl7.org/fhir/StructureDefinition/ResearchStudy\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1601`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1602`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ResearchStudy](/docs/R4B/Resources/ResearchStudy.md)<br/> `http://hl7.org/fhir/StructureDefinition/ResearchStudy\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1035`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1264`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ResearchStudy](/docs/R5/Resources/ResearchStudy.md)<br/> `http://hl7.org/fhir/StructureDefinition/ResearchStudy\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ResearchStudy from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | R3 ResearchStudy| Relationship | [R4 ResearchStudy](/docs/R4/Resources/ResearchStudy.md)| Relationship | [R4B ResearchStudy](/docs/R4B/Resources/ResearchStudy.md)| Relationship | [R5 ResearchStudy](/docs/R5/Resources/ResearchStudy.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | **`ResearchStudy`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18039)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18040)| `ResearchStudy`| _Equivalent_<br/>(32658/32659)| `ResearchStudy`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47009)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47010)| `ResearchStudy`
| | | **`ResearchStudy.id`**| _Equivalent_<br/>(18041/18042)| `ResearchStudy.id`| _Equivalent_<br/>(32660/32661)| `ResearchStudy.id`| _Equivalent_<br/>(47011/47012)| `ResearchStudy.id`
| | | **`ResearchStudy.meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18043)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18044)| `ResearchStudy.meta`| _Equivalent_<br/>(32662/32663)| `ResearchStudy.meta`| _Equivalent_<br/>(47013/47014)| `ResearchStudy.meta`
| | | **`ResearchStudy.implicitRules`**| _Equivalent_<br/>(18045/18046)| `ResearchStudy.implicitRules`| _Equivalent_<br/>(32664/32665)| `ResearchStudy.implicitRules`| _Equivalent_<br/>(47015/47016)| `ResearchStudy.implicitRules`
| | | **`ResearchStudy.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18047)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18048)| `ResearchStudy.language`| _Equivalent_<br/>(32666/32667)| `ResearchStudy.language`| _Equivalent_<br/>(47017/47018)| `ResearchStudy.language`
| | | **`ResearchStudy.text`**| _Equivalent_<br/>(18049/18050)| `ResearchStudy.text`| _Equivalent_<br/>(32668/32669)| `ResearchStudy.text`| _Equivalent_<br/>(47019/47020)| `ResearchStudy.text`
| | | **`ResearchStudy.contained`**| _Equivalent_<br/>(18051/18052)| `ResearchStudy.contained`| _Equivalent_<br/>(32670/32671)| `ResearchStudy.contained`| _Equivalent_<br/>(47021/47022)| `ResearchStudy.contained`
| | | **`ResearchStudy.extension`**| →→→→ _Equivalent_ →→→→ <br/>(18053)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18054)| `ResearchStudy.extension`| _Equivalent_<br/>(32672/32673)| `ResearchStudy.extension`| _Equivalent_<br/>(47023/47024)| `ResearchStudy.extension`
| | | **`ResearchStudy.modifierExtension`**| _Equivalent_<br/>(18055/18056)| `ResearchStudy.modifierExtension`| _Equivalent_<br/>(32674/32675)| `ResearchStudy.modifierExtension`| _Equivalent_<br/>(47025/47026)| `ResearchStudy.modifierExtension`
| | | **`ResearchStudy.identifier`**| _Equivalent_<br/>(18057/18058)| `ResearchStudy.identifier`| _Equivalent_<br/>(32676/32677)| `ResearchStudy.identifier`| _Equivalent_<br/>(47027/47028)| `ResearchStudy.identifier`
| | | **`ResearchStudy.title`**| _Equivalent_<br/>(18059/18060)| `ResearchStudy.title`| _Equivalent_<br/>(32678/32679)| `ResearchStudy.title`| _Equivalent_<br/>(47029/47030)| `ResearchStudy.title`
| | | **`ResearchStudy.protocol`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18061)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18062)| `ResearchStudy.protocol`| _Equivalent_<br/>(32680/32681)| `ResearchStudy.protocol`| _Equivalent_<br/>(47031/47032)| `ResearchStudy.protocol`
| | | **`ResearchStudy.partOf`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18063)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18064)| `ResearchStudy.partOf`| _Equivalent_<br/>(32682/32683)| `ResearchStudy.partOf`| _Equivalent_<br/>(47033/47034)| `ResearchStudy.partOf`
| | | **`ResearchStudy.status`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18065)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18066)| `ResearchStudy.status`| _Equivalent_<br/>(32684/32685)| `ResearchStudy.status`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47035)<hr/>←←←← _RelatedTo_ ←←←← <br/>(47036)| `ResearchStudy.status`
| | | **`ResearchStudy.category`**| _Equivalent_<br/>(18067/18068)| `ResearchStudy.category`| _Equivalent_<br/>(32690/32691)| `ResearchStudy.category`| | | 
| | | **`ResearchStudy.focus`**| _Equivalent_<br/>(18069/18070)| `ResearchStudy.focus`| _Equivalent_<br/>(32692/32693)| `ResearchStudy.focus`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47042)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47043)| `ResearchStudy.focus`
| | | **`ResearchStudy.contact`**| _Equivalent_<br/>(18071/18072)| `ResearchStudy.contact`| _Equivalent_<br/>(32696/32697)| `ResearchStudy.contact`| | | 
| | | **`ResearchStudy.relatedArtifact`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18073)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18074)| `ResearchStudy.relatedArtifact`| _Equivalent_<br/>(32698/32699)| `ResearchStudy.relatedArtifact`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47047)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47048)| `ResearchStudy.relatedArtifact`
| | | **`ResearchStudy.keyword`**| _Equivalent_<br/>(18075/18076)| `ResearchStudy.keyword`| _Equivalent_<br/>(32700/32701)| `ResearchStudy.keyword`| _Equivalent_<br/>(47049/47050)| `ResearchStudy.keyword`
| | | **`ResearchStudy.jurisdiction`**| →→→→ _RelatedTo_ →→→→ <br/>(1275)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18077)| `ResearchStudy.extension`| _Equivalent_<br/>(32672/32673)| `ResearchStudy.extension`| _Equivalent_<br/>(47023/47024)| `ResearchStudy.extension`
| | | **`ResearchStudy.jurisdiction`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1274)<hr/>←←←← _Equivalent_ ←←←← <br/>(1659)| `ResearchStudy.location`| _Equivalent_<br/>(32702/32703)| `ResearchStudy.location`| | | 
| | | **`ResearchStudy.description`**| _Equivalent_<br/>(18078/18079)| `ResearchStudy.description`| _Equivalent_<br/>(32704/32705)| `ResearchStudy.description`| _Equivalent_<br/>(47052/47053)| `ResearchStudy.description`
| | | **`ResearchStudy.enrollment`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18080)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18081)| `ResearchStudy.enrollment`| _Equivalent_<br/>(32706/32707)| `ResearchStudy.enrollment`| | | 
| | | **`ResearchStudy.period`**| _Equivalent_<br/>(18082/18083)| `ResearchStudy.period`| _Equivalent_<br/>(32708/32709)| `ResearchStudy.period`| _Equivalent_<br/>(47055/47056)| `ResearchStudy.period`
| | | **`ResearchStudy.sponsor`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18084)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18085)| `ResearchStudy.sponsor`| _Equivalent_<br/>(32710/32711)| `ResearchStudy.sponsor`| | | 
| | | **`ResearchStudy.principalInvestigator`**| →→→→ _RelatedTo_ →→→→ <br/>(18086)<hr/>←←←← _RelatedTo_ ←←←← <br/>(18087)| `ResearchStudy.principalInvestigator`| _Equivalent_<br/>(32712/32713)| `ResearchStudy.principalInvestigator`| | | 
| | | **`ResearchStudy.site`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18088)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18089)| `ResearchStudy.site`| _Equivalent_<br/>(32714/32715)| `ResearchStudy.site`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47059)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(47060)| `ResearchStudy.site`
| | | **`ResearchStudy.reasonStopped`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(18090)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18091)| `ResearchStudy.reasonStopped`| _Equivalent_<br/>(32716/32717)| `ResearchStudy.reasonStopped`| | | 
| | | **`ResearchStudy.note`**| _Equivalent_<br/>(18092/18093)| `ResearchStudy.note`| _Equivalent_<br/>(32718/32719)| `ResearchStudy.note`| _Equivalent_<br/>(47062/47063)| `ResearchStudy.note`
| | | **`ResearchStudy.arm`**| _Equivalent_<br/>(18094/18095)| `ResearchStudy.arm`| _Equivalent_<br/>(32720/32721)| `ResearchStudy.arm`| | | 
| | | **`ResearchStudy.arm.id`**| _Equivalent_<br/>(18096/18097)| `ResearchStudy.arm.id`| _Equivalent_<br/>(32722/32723)| `ResearchStudy.arm.id`| | | 
| | | **`ResearchStudy.arm.extension`**| _Equivalent_<br/>(18098/18099)| `ResearchStudy.arm.extension`| _Equivalent_<br/>(32724/32725)| `ResearchStudy.arm.extension`| | | 
| | | **`ResearchStudy.arm.modifierExtension`**| _Equivalent_<br/>(18100/18101)| `ResearchStudy.arm.modifierExtension`| _Equivalent_<br/>(32726/32727)| `ResearchStudy.arm.modifierExtension`| | | 
| | | **`ResearchStudy.arm.name`**| _Equivalent_<br/>(18102/18103)| `ResearchStudy.arm.name`| _Equivalent_<br/>(32728/32729)| `ResearchStudy.arm.name`| _Equivalent_<br/>(1939/2176)| `ResearchStudy.comparisonGroup.name`
| | | **`ResearchStudy.arm.code`**| _Equivalent_<br/>(1273/1658)| `ResearchStudy.arm.type`| _Equivalent_<br/>(32730/32731)| `ResearchStudy.arm.type`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1940)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2177)| `ResearchStudy.comparisonGroup.type`
| | | **`ResearchStudy.arm.description`**| _Equivalent_<br/>(18104/18105)| `ResearchStudy.arm.description`| _Equivalent_<br/>(32732/32733)| `ResearchStudy.arm.description`| _Equivalent_<br/>(1941/2178)| `ResearchStudy.comparisonGroup.description`
| | | *35 of 35 elements used* | | *35 of 44 elements used* <br/>remaining elements:<br/>`ResearchStudy.condition`, `ResearchStudy.objective`, `ResearchStudy.objective.extension`, `ResearchStudy.objective.id`, `ResearchStudy.objective.modifierExtension`, `ResearchStudy.objective.name`, `ResearchStudy.objective.type`, `ResearchStudy.phase`, `ResearchStudy.primaryPurposeType`| | *35 of 44 elements used* <br/>remaining elements:<br/>`ResearchStudy.condition`, `ResearchStudy.objective`, `ResearchStudy.objective.extension`, `ResearchStudy.objective.id`, `ResearchStudy.objective.modifierExtension`, `ResearchStudy.objective.name`, `ResearchStudy.objective.type`, `ResearchStudy.phase`, `ResearchStudy.primaryPurposeType`| | *24 of 89 elements used* <br/>remaining elements:<br/>`ResearchStudy.associatedParty`, `ResearchStudy.associatedParty.classifier`, `ResearchStudy.associatedParty.extension`, `ResearchStudy.associatedParty.id`, `ResearchStudy.associatedParty.modifierExtension`, `ResearchStudy.associatedParty.name`, `ResearchStudy.associatedParty.party`, `ResearchStudy.associatedParty.period`, `ResearchStudy.associatedParty.role`, `ResearchStudy.classifier`, `ResearchStudy.comparisonGroup`, `ResearchStudy.comparisonGroup.extension`, `ResearchStudy.comparisonGroup.id`, `ResearchStudy.comparisonGroup.intendedExposure`, `ResearchStudy.comparisonGroup.linkId`, `ResearchStudy.comparisonGroup.modifierExtension`, `ResearchStudy.comparisonGroup.observedGroup`, `ResearchStudy.condition`, `ResearchStudy.date`, `ResearchStudy.descriptionSummary`, `ResearchStudy.label`, `ResearchStudy.label.extension`, `ResearchStudy.label.id`, `ResearchStudy.label.modifierExtension`, `ResearchStudy.label.type`, `ResearchStudy.label.value`, `ResearchStudy.name`, `ResearchStudy.objective`, `ResearchStudy.objective.description`, `ResearchStudy.objective.extension`, `ResearchStudy.objective.id`, `ResearchStudy.objective.modifierExtension`, `ResearchStudy.objective.name`, `ResearchStudy.objective.type`, `ResearchStudy.outcomeMeasure`, `ResearchStudy.outcomeMeasure.description`, `ResearchStudy.outcomeMeasure.extension`, `ResearchStudy.outcomeMeasure.id`, `ResearchStudy.outcomeMeasure.modifierExtension`, `ResearchStudy.outcomeMeasure.name`, `ResearchStudy.outcomeMeasure.reference`, `ResearchStudy.outcomeMeasure.type`, `ResearchStudy.phase`, `ResearchStudy.primaryPurposeType`, `ResearchStudy.progressStatus`, `ResearchStudy.progressStatus.actual`, `ResearchStudy.progressStatus.extension`, `ResearchStudy.progressStatus.id`, `ResearchStudy.progressStatus.modifierExtension`, `ResearchStudy.progressStatus.period`, `ResearchStudy.progressStatus.state`, `ResearchStudy.recruitment`, `ResearchStudy.recruitment.actualGroup`, `ResearchStudy.recruitment.actualNumber`, `ResearchStudy.recruitment.eligibility`, `ResearchStudy.recruitment.extension`, `ResearchStudy.recruitment.id`, `ResearchStudy.recruitment.modifierExtension`, `ResearchStudy.recruitment.targetNumber`, `ResearchStudy.region`, `ResearchStudy.result`, `ResearchStudy.studyDesign`, `ResearchStudy.url`, `ResearchStudy.version`, `ResearchStudy.whyStopped`

