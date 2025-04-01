Comparison of 
Generated at Tuesday, April 1, 2025 1:39:28 PM

### RiskAssessment

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | RiskAssessment |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/RiskAssessment` |
| Version | 4.3.0 |
| Description | An assessment of the likely outcome(s) for a patient or other subject as well as the likelihood of each outcome. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1758` |
| Database Snapshot Count | `35` |
| Database Differential Count | `24` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `RiskAssessment` | `RiskAssessment` | `RiskAssessment` | RiskAssessment | Potential outcomes for a subject with likelihood | 0..* | RiskAssessment |  |  |
| `RiskAssessment.basedOn` | `RiskAssessment.basedOn` | `basedOn` | RiskAssessment.basedOn | Request fulfilled by this assessment | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `RiskAssessment.basis` | `RiskAssessment.basis` | `basis` | RiskAssessment.basis | Information used in assessment | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `RiskAssessment.code` | `RiskAssessment.code` | `code` | RiskAssessment.code | Type of assessment | 0..1 | CodeableConcept |  |  |
| `RiskAssessment.condition` | `RiskAssessment.condition` | `condition` | RiskAssessment.condition | Condition assessed | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Condition) |  |  |
| `RiskAssessment.contained` | `RiskAssessment.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `RiskAssessment.encounter` | `RiskAssessment.encounter` | `encounter` | RiskAssessment.encounter | Where was assessment performed? | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `RiskAssessment.extension` | `RiskAssessment.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RiskAssessment.id` | `RiskAssessment.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `RiskAssessment.identifier` | `RiskAssessment.identifier` | `identifier` | RiskAssessment.identifier | Unique identifier for the assessment | 0..* | Identifier |  |  |
| `RiskAssessment.implicitRules` | `RiskAssessment.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `RiskAssessment.language` | `RiskAssessment.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `RiskAssessment.meta` | `RiskAssessment.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `RiskAssessment.method` | `RiskAssessment.method` | `method` | RiskAssessment.method | Evaluation mechanism | 0..1 | CodeableConcept | `Example` |  |
| `RiskAssessment.mitigation` | `RiskAssessment.mitigation` | `mitigation` | RiskAssessment.mitigation | How to reduce risk | 0..1 | string |  |  |
| `RiskAssessment.modifierExtension` | `RiskAssessment.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `RiskAssessment.note` | `RiskAssessment.note` | `note` | RiskAssessment.note | Comments on the risk assessment | 0..* | Annotation |  |  |
| `RiskAssessment.occurrence[x]` | `RiskAssessment.occurrence[x]` | `occurrence[x]` | RiskAssessment.occurrence[x] | When was assessment made? | 0..1 | dateTime, Period |  |  |
| `RiskAssessment.parent` | `RiskAssessment.parent` | `parent` | RiskAssessment.parent | Part of this occurrence | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `RiskAssessment.performer` | `RiskAssessment.performer` | `performer` | RiskAssessment.performer | Who did assessment? | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `RiskAssessment.prediction` | `RiskAssessment.prediction` | `prediction` | RiskAssessment.prediction | Outcome predicted | 0..* | BackboneElement |  |  |
| `RiskAssessment.prediction.extension` | `RiskAssessment.prediction.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `RiskAssessment.prediction.id` | `RiskAssessment.prediction.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `RiskAssessment.prediction.modifierExtension` | `RiskAssessment.prediction.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `RiskAssessment.prediction.outcome` | `RiskAssessment.prediction.outcome` | `outcome` | RiskAssessment.prediction.outcome | Possible outcome for the subject | 0..1 | CodeableConcept | `Example` |  |
| `RiskAssessment.prediction.probability[x]` | `RiskAssessment.prediction.probability[x]` | `probability[x]` | RiskAssessment.prediction.probability[x] | Likelihood of specified outcome | 0..1 | decimal, Range |  |  |
| `RiskAssessment.prediction.qualitativeRisk` | `RiskAssessment.prediction.qualitativeRisk` | `qualitativeRisk` | RiskAssessment.prediction.qualitativeRisk | Likelihood of specified outcome as a qualitative value | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/risk-probability` |
| `RiskAssessment.prediction.rationale` | `RiskAssessment.prediction.rationale` | `rationale` | RiskAssessment.prediction.rationale | Explanation of prediction | 0..1 | string |  |  |
| `RiskAssessment.prediction.relativeRisk` | `RiskAssessment.prediction.relativeRisk` | `relativeRisk` | RiskAssessment.prediction.relativeRisk | Relative likelihood | 0..1 | decimal |  |  |
| `RiskAssessment.prediction.when[x]` | `RiskAssessment.prediction.when[x]` | `when[x]` | RiskAssessment.prediction.when[x] | Timeframe or age range | 0..1 | Period, Range |  |  |
| `RiskAssessment.reasonCode` | `RiskAssessment.reasonCode` | `reasonCode` | RiskAssessment.reasonCode | Why the assessment was necessary? | 0..* | CodeableConcept |  |  |
| `RiskAssessment.reasonReference` | `RiskAssessment.reasonReference` | `reasonReference` | RiskAssessment.reasonReference | Why the assessment was necessary? | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Condition), Reference(http://hl7.org/fhir/StructureDefinition/DiagnosticReport), Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference), Reference(http://hl7.org/fhir/StructureDefinition/Observation) |  |  |
| `RiskAssessment.status` | `RiskAssessment.status` | `status` | RiskAssessment.status | registered \| preliminary \| final \| amended + | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/observation-status|4.3.0` |
| `RiskAssessment.subject` | `RiskAssessment.subject` | `subject` | RiskAssessment.subject | Who/what does assessment apply to? | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `RiskAssessment.text` | `RiskAssessment.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [RiskAssessment](/docs/R2/Resources/RiskAssessment.md)<br/> `http://hl7.org/fhir/StructureDefinition/RiskAssessment\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `152`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `318`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RiskAssessment](/docs/R3/Resources/RiskAssessment.md)<br/> `http://hl7.org/fhir/StructureDefinition/RiskAssessment\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `512`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `704`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RiskAssessment](/docs/R4/Resources/RiskAssessment.md)<br/> `http://hl7.org/fhir/StructureDefinition/RiskAssessment\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1607`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1608`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RiskAssessment](/docs/R4B/Resources/RiskAssessment.md)<br/> `http://hl7.org/fhir/StructureDefinition/RiskAssessment\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1037`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1266`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [RiskAssessment](/docs/R5/Resources/RiskAssessment.md)<br/> `http://hl7.org/fhir/StructureDefinition/RiskAssessment\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition RiskAssessment from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 RiskAssessment](/docs/R2/Resources/RiskAssessment.md)| Relationship | [R3 RiskAssessment](/docs/R3/Resources/RiskAssessment.md)| Relationship | [R4 RiskAssessment](/docs/R4/Resources/RiskAssessment.md)| Relationship | R4B RiskAssessment| Relationship | [R5 RiskAssessment](/docs/R5/Resources/RiskAssessment.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `RiskAssessment`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7657)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7658)| `RiskAssessment`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18157)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18158)| `RiskAssessment`| _Equivalent_<br/>(32790/32791)| **`RiskAssessment`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47118)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(47119)| `RiskAssessment`
| `RiskAssessment.id`| _Equivalent_<br/>(7659/7660)| `RiskAssessment.id`| _Equivalent_<br/>(18159/18160)| `RiskAssessment.id`| _Equivalent_<br/>(32792/32793)| **`RiskAssessment.id`**| _Equivalent_<br/>(47120/47121)| `RiskAssessment.id`
| `RiskAssessment.meta`| _Equivalent_<br/>(7661/7662)| `RiskAssessment.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18161)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18162)| `RiskAssessment.meta`| _Equivalent_<br/>(32794/32795)| **`RiskAssessment.meta`**| _Equivalent_<br/>(47122/47123)| `RiskAssessment.meta`
| `RiskAssessment.implicitRules`| _Equivalent_<br/>(7663/7664)| `RiskAssessment.implicitRules`| _Equivalent_<br/>(18163/18164)| `RiskAssessment.implicitRules`| _Equivalent_<br/>(32796/32797)| **`RiskAssessment.implicitRules`**| _Equivalent_<br/>(47124/47125)| `RiskAssessment.implicitRules`
| `RiskAssessment.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7665)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7666)| `RiskAssessment.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18165)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18166)| `RiskAssessment.language`| _Equivalent_<br/>(32798/32799)| **`RiskAssessment.language`**| _Equivalent_<br/>(47126/47127)| `RiskAssessment.language`
| `RiskAssessment.text`| _Equivalent_<br/>(7667/7668)| `RiskAssessment.text`| _Equivalent_<br/>(18167/18168)| `RiskAssessment.text`| _Equivalent_<br/>(32800/32801)| **`RiskAssessment.text`**| _Equivalent_<br/>(47128/47129)| `RiskAssessment.text`
| `RiskAssessment.contained`| _Equivalent_<br/>(7669/7670)| `RiskAssessment.contained`| _Equivalent_<br/>(18169/18170)| `RiskAssessment.contained`| _Equivalent_<br/>(32802/32803)| **`RiskAssessment.contained`**| _Equivalent_<br/>(47130/47131)| `RiskAssessment.contained`
| `RiskAssessment.extension`| _Equivalent_<br/>(7671/7672)| `RiskAssessment.extension`| _Equivalent_<br/>(18171/18172)| `RiskAssessment.extension`| _Equivalent_<br/>(32804/32805)| **`RiskAssessment.extension`**| _Equivalent_<br/>(47132/47133)| `RiskAssessment.extension`
| `RiskAssessment.modifierExtension`| _Equivalent_<br/>(7673/7674)| `RiskAssessment.modifierExtension`| _Equivalent_<br/>(18173/18174)| `RiskAssessment.modifierExtension`| _Equivalent_<br/>(32806/32807)| **`RiskAssessment.modifierExtension`**| _Equivalent_<br/>(47134/47135)| `RiskAssessment.modifierExtension`
| `RiskAssessment.identifier`| _Equivalent_<br/>(7681/7682)| `RiskAssessment.identifier`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18175)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18176)| `RiskAssessment.identifier`| _Equivalent_<br/>(32808/32809)| **`RiskAssessment.identifier`**| _Equivalent_<br/>(47136/47137)| `RiskAssessment.identifier`
| | | `RiskAssessment.basedOn`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18177)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18178)| `RiskAssessment.basedOn`| _Equivalent_<br/>(32810/32811)| **`RiskAssessment.basedOn`**| _Equivalent_<br/>(47138/47139)| `RiskAssessment.basedOn`
| | | `RiskAssessment.parent`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18179)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18180)| `RiskAssessment.parent`| _Equivalent_<br/>(32812/32813)| **`RiskAssessment.parent`**| _Equivalent_<br/>(47140/47141)| `RiskAssessment.parent`
| | | `RiskAssessment.status`| _Equivalent_<br/>(18181/18182)| `RiskAssessment.status`| _Equivalent_<br/>(32814/32815)| **`RiskAssessment.status`**| _Equivalent_<br/>(47142/47143)| `RiskAssessment.status`
| `RiskAssessment.method`| _Equivalent_<br/>(7683/7684)| `RiskAssessment.method`| _Equivalent_<br/>(18183/18184)| `RiskAssessment.method`| _Equivalent_<br/>(32816/32817)| **`RiskAssessment.method`**| _Equivalent_<br/>(47144/47145)| `RiskAssessment.method`
| | | `RiskAssessment.code`| _Equivalent_<br/>(18185/18186)| `RiskAssessment.code`| _Equivalent_<br/>(32818/32819)| **`RiskAssessment.code`**| _Equivalent_<br/>(47146/47147)| `RiskAssessment.code`
| `RiskAssessment.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7675)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7676)| `RiskAssessment.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18187)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18188)| `RiskAssessment.subject`| _Equivalent_<br/>(32820/32821)| **`RiskAssessment.subject`**| _Equivalent_<br/>(47148/47149)| `RiskAssessment.subject`
| `RiskAssessment.encounter`| →→→→ _RelatedTo_ →→→→ <br/>(403)<hr/>←←←← _RelatedTo_ ←←←← <br/>(746)| `RiskAssessment.context`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1277)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1660)| `RiskAssessment.encounter`| _Equivalent_<br/>(32822/32823)| **`RiskAssessment.encounter`**| _Equivalent_<br/>(47150/47151)| `RiskAssessment.encounter`
| `RiskAssessment.date`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(402)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(747)| `RiskAssessment.occurrence[x]`| _Equivalent_<br/>(18189/18190)| `RiskAssessment.occurrence[x]`| _Equivalent_<br/>(32824/32825)| **`RiskAssessment.occurrence[x]`**| _Equivalent_<br/>(47152/47153)| `RiskAssessment.occurrence[x]`
| `RiskAssessment.condition`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7677)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7678)| `RiskAssessment.condition`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18191)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18192)| `RiskAssessment.condition`| _Equivalent_<br/>(32826/32827)| **`RiskAssessment.condition`**| _Equivalent_<br/>(47154/47155)| `RiskAssessment.condition`
| `RiskAssessment.performer`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7679)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7680)| `RiskAssessment.performer`| →→→→ _RelatedTo_ →→→→ <br/>(18193)<hr/>←←←← _RelatedTo_ ←←←← <br/>(18194)| `RiskAssessment.performer`| _Equivalent_<br/>(32828/32829)| **`RiskAssessment.performer`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47156)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(47157)| `RiskAssessment.performer`
| | | `RiskAssessment.reason[x]`| →→→→ _RelatedTo_ →→→→ <br/>(1278)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1662)| `RiskAssessment.reasonCode`| _Equivalent_<br/>(32830/32831)| **`RiskAssessment.reasonCode`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1945)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2182)| `RiskAssessment.reason`
| | | `RiskAssessment.reason[x]`| →→→→ _RelatedTo_ →→→→ <br/>(1279)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1663)| `RiskAssessment.reasonReference`| _Equivalent_<br/>(32832/32833)| **`RiskAssessment.reasonReference`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1946)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2183)| `RiskAssessment.reason`
| `RiskAssessment.basis`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7685)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7686)| `RiskAssessment.basis`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(18195)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(18196)| `RiskAssessment.basis`| _Equivalent_<br/>(32834/32835)| **`RiskAssessment.basis`**| _Equivalent_<br/>(47158/47159)| `RiskAssessment.basis`
| `RiskAssessment.prediction`| _Equivalent_<br/>(7687/7688)| `RiskAssessment.prediction`| _Equivalent_<br/>(18197/18198)| `RiskAssessment.prediction`| _Equivalent_<br/>(32836/32837)| **`RiskAssessment.prediction`**| _Equivalent_<br/>(47160/47161)| `RiskAssessment.prediction`
| `RiskAssessment.prediction.id`| _Equivalent_<br/>(7689/7690)| `RiskAssessment.prediction.id`| _Equivalent_<br/>(18199/18200)| `RiskAssessment.prediction.id`| _Equivalent_<br/>(32838/32839)| **`RiskAssessment.prediction.id`**| _Equivalent_<br/>(47162/47163)| `RiskAssessment.prediction.id`
| `RiskAssessment.prediction.extension`| _Equivalent_<br/>(7691/7692)| `RiskAssessment.prediction.extension`| _Equivalent_<br/>(18201/18202)| `RiskAssessment.prediction.extension`| _Equivalent_<br/>(32840/32841)| **`RiskAssessment.prediction.extension`**| _Equivalent_<br/>(47164/47165)| `RiskAssessment.prediction.extension`
| `RiskAssessment.prediction.modifierExtension`| _Equivalent_<br/>(7693/7694)| `RiskAssessment.prediction.modifierExtension`| _Equivalent_<br/>(18203/18204)| `RiskAssessment.prediction.modifierExtension`| _Equivalent_<br/>(32842/32843)| **`RiskAssessment.prediction.modifierExtension`**| _Equivalent_<br/>(47166/47167)| `RiskAssessment.prediction.modifierExtension`
| `RiskAssessment.prediction.outcome`| _Equivalent_<br/>(7695/7696)| `RiskAssessment.prediction.outcome`| →→→→ _Equivalent_ →→→→ <br/>(18205)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(18206)| `RiskAssessment.prediction.outcome`| _Equivalent_<br/>(32844/32845)| **`RiskAssessment.prediction.outcome`**| _Equivalent_<br/>(47168/47169)| `RiskAssessment.prediction.outcome`
| `RiskAssessment.prediction.probability[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7697)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7698)| `RiskAssessment.prediction.probability[x]`| _Equivalent_<br/>(18207/18208)| `RiskAssessment.prediction.probability[x]`| _Equivalent_<br/>(32846/32847)| **`RiskAssessment.prediction.probability[x]`**| _Equivalent_<br/>(47170/47171)| `RiskAssessment.prediction.probability[x]`
| | | `RiskAssessment.prediction.qualitativeRisk`| _Equivalent_<br/>(18209/18210)| `RiskAssessment.prediction.qualitativeRisk`| _Equivalent_<br/>(32848/32849)| **`RiskAssessment.prediction.qualitativeRisk`**| _Equivalent_<br/>(47172/47173)| `RiskAssessment.prediction.qualitativeRisk`
| `RiskAssessment.prediction.relativeRisk`| _Equivalent_<br/>(7699/7700)| `RiskAssessment.prediction.relativeRisk`| _Equivalent_<br/>(18211/18212)| `RiskAssessment.prediction.relativeRisk`| _Equivalent_<br/>(32850/32851)| **`RiskAssessment.prediction.relativeRisk`**| _Equivalent_<br/>(47174/47175)| `RiskAssessment.prediction.relativeRisk`
| `RiskAssessment.prediction.when[x]`| _Equivalent_<br/>(7701/7702)| `RiskAssessment.prediction.when[x]`| _Equivalent_<br/>(18213/18214)| `RiskAssessment.prediction.when[x]`| _Equivalent_<br/>(32852/32853)| **`RiskAssessment.prediction.when[x]`**| _Equivalent_<br/>(47176/47177)| `RiskAssessment.prediction.when[x]`
| `RiskAssessment.prediction.rationale`| _Equivalent_<br/>(7703/7704)| `RiskAssessment.prediction.rationale`| _Equivalent_<br/>(18215/18216)| `RiskAssessment.prediction.rationale`| _Equivalent_<br/>(32854/32855)| **`RiskAssessment.prediction.rationale`**| _Equivalent_<br/>(47178/47179)| `RiskAssessment.prediction.rationale`
| `RiskAssessment.mitigation`| _Equivalent_<br/>(7705/7706)| `RiskAssessment.mitigation`| _Equivalent_<br/>(18217/18218)| `RiskAssessment.mitigation`| _Equivalent_<br/>(32856/32857)| **`RiskAssessment.mitigation`**| _Equivalent_<br/>(47180/47181)| `RiskAssessment.mitigation`
| | | `RiskAssessment.comment`| →→→→ _RelatedTo_ →→→→ <br/>(1276)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1661)| `RiskAssessment.note`| _Equivalent_<br/>(32858/32859)| **`RiskAssessment.note`**| _Equivalent_<br/>(47182/47183)| `RiskAssessment.note`
| *27 of 27 elements used* | | *34 of 34 elements used* | | *35 of 35 elements used* | | *35 of 35 elements used* | | *34 of 34 elements used* 

