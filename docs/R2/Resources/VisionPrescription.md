Comparison of 
Generated at Tuesday, April 1, 2025 1:39:10 PM

### VisionPrescription

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | VisionPrescription |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/VisionPrescription` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for VisionPrescription Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `136` |
| Database Snapshot Count | `34` |
| Database Differential Count | `23` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `VisionPrescription` | `VisionPrescription` | `VisionPrescription` | VisionPrescription | Prescription for vision correction products for a patient | 0..* | VisionPrescription |  |  |
| `VisionPrescription.contained` | `VisionPrescription.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `VisionPrescription.dateWritten` | `VisionPrescription.dateWritten` | `dateWritten` |  | When prescription was authorized | 0..1 | dateTime |  |  |
| `VisionPrescription.dispense` | `VisionPrescription.dispense` | `dispense` |  | Vision supply authorization | 0..* | BackboneElement |  |  |
| `VisionPrescription.dispense.add` | `VisionPrescription.dispense.add` | `add` |  | Lens add | 0..1 | decimal |  |  |
| `VisionPrescription.dispense.axis` | `VisionPrescription.dispense.axis` | `axis` |  | Lens axis | 0..1 | integer |  |  |
| `VisionPrescription.dispense.backCurve` | `VisionPrescription.dispense.backCurve` | `backCurve` |  | Contact lens back curvature | 0..1 | decimal |  |  |
| `VisionPrescription.dispense.base` | `VisionPrescription.dispense.base` | `base` |  | up \| down \| in \| out | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/vision-base-codes` |
| `VisionPrescription.dispense.brand` | `VisionPrescription.dispense.brand` | `brand` |  | Lens add | 0..1 | string |  |  |
| `VisionPrescription.dispense.color` | `VisionPrescription.dispense.color` | `color` |  | Lens add | 0..1 | string |  |  |
| `VisionPrescription.dispense.cylinder` | `VisionPrescription.dispense.cylinder` | `cylinder` |  | Lens cylinder | 0..1 | decimal |  |  |
| `VisionPrescription.dispense.diameter` | `VisionPrescription.dispense.diameter` | `diameter` |  | Contact lens diameter | 0..1 | decimal |  |  |
| `VisionPrescription.dispense.duration` | `VisionPrescription.dispense.duration` | `duration` |  | Lens wear duration | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `VisionPrescription.dispense.extension` | `VisionPrescription.dispense.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `VisionPrescription.dispense.eye` | `VisionPrescription.dispense.eye` | `eye` |  | right \| left | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/vision-eye-codes` |
| `VisionPrescription.dispense.id` | `VisionPrescription.dispense.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `VisionPrescription.dispense.modifierExtension` | `VisionPrescription.dispense.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `VisionPrescription.dispense.notes` | `VisionPrescription.dispense.notes` | `notes` |  | Notes for coatings | 0..1 | string |  |  |
| `VisionPrescription.dispense.power` | `VisionPrescription.dispense.power` | `power` |  | Contact lens power | 0..1 | decimal |  |  |
| `VisionPrescription.dispense.prism` | `VisionPrescription.dispense.prism` | `prism` |  | Lens prism | 0..1 | decimal |  |  |
| `VisionPrescription.dispense.product` | `VisionPrescription.dispense.product` | `product` |  | Product to be supplied | 1..1 | Coding | `Example` | `http://hl7.org/fhir/ValueSet/vision-product` |
| `VisionPrescription.dispense.sphere` | `VisionPrescription.dispense.sphere` | `sphere` |  | Lens sphere | 0..1 | decimal |  |  |
| `VisionPrescription.encounter` | `VisionPrescription.encounter` | `encounter` |  | Created during encounter / admission / stay | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `VisionPrescription.extension` | `VisionPrescription.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `VisionPrescription.id` | `VisionPrescription.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `VisionPrescription.identifier` | `VisionPrescription.identifier` | `identifier` |  | Business identifier | 0..* | Identifier |  |  |
| `VisionPrescription.implicitRules` | `VisionPrescription.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `VisionPrescription.language` | `VisionPrescription.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `VisionPrescription.meta` | `VisionPrescription.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `VisionPrescription.modifierExtension` | `VisionPrescription.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `VisionPrescription.patient` | `VisionPrescription.patient` | `patient` |  | Who prescription is for | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `VisionPrescription.prescriber` | `VisionPrescription.prescriber` | `prescriber` |  | Who authorizes the vision product | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `VisionPrescription.reason[x]` | `VisionPrescription.reason[x]` | `reason[x]` |  | Reason or indication for writing the prescription | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Condition) |  |  |
| `VisionPrescription.text` | `VisionPrescription.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [VisionPrescription](/docs/R2/Resources/VisionPrescription.md)<br/> `http://hl7.org/fhir/StructureDefinition/VisionPrescription\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `166`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `332`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [VisionPrescription](/docs/R3/Resources/VisionPrescription.md)<br/> `http://hl7.org/fhir/StructureDefinition/VisionPrescription\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `528`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `724`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [VisionPrescription](/docs/R4/Resources/VisionPrescription.md)<br/> `http://hl7.org/fhir/StructureDefinition/VisionPrescription\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1645`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1646`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [VisionPrescription](/docs/R4B/Resources/VisionPrescription.md)<br/> `http://hl7.org/fhir/StructureDefinition/VisionPrescription\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1059`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1288`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [VisionPrescription](/docs/R5/Resources/VisionPrescription.md)<br/> `http://hl7.org/fhir/StructureDefinition/VisionPrescription\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition VisionPrescription from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 VisionPrescription| Relationship | [R3 VisionPrescription](/docs/R3/Resources/VisionPrescription.md)| Relationship | [R4 VisionPrescription](/docs/R4/Resources/VisionPrescription.md)| Relationship | [R4B VisionPrescription](/docs/R4B/Resources/VisionPrescription.md)| Relationship | [R5 VisionPrescription](/docs/R5/Resources/VisionPrescription.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`VisionPrescription`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8665)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8666)| `VisionPrescription`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(20025)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(20026)| `VisionPrescription`| _Equivalent_<br/>(35077/35078)| `VisionPrescription`| _Equivalent_<br/>(49487/49488)| `VisionPrescription`
| **`VisionPrescription.id`**| _Equivalent_<br/>(8667/8668)| `VisionPrescription.id`| _Equivalent_<br/>(20027/20028)| `VisionPrescription.id`| _Equivalent_<br/>(35079/35080)| `VisionPrescription.id`| _Equivalent_<br/>(49489/49490)| `VisionPrescription.id`
| **`VisionPrescription.meta`**| _Equivalent_<br/>(8669/8670)| `VisionPrescription.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(20029)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(20030)| `VisionPrescription.meta`| _Equivalent_<br/>(35081/35082)| `VisionPrescription.meta`| _Equivalent_<br/>(49491/49492)| `VisionPrescription.meta`
| **`VisionPrescription.implicitRules`**| _Equivalent_<br/>(8671/8672)| `VisionPrescription.implicitRules`| _Equivalent_<br/>(20031/20032)| `VisionPrescription.implicitRules`| _Equivalent_<br/>(35083/35084)| `VisionPrescription.implicitRules`| _Equivalent_<br/>(49493/49494)| `VisionPrescription.implicitRules`
| **`VisionPrescription.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8673)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(8674)| `VisionPrescription.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(20033)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(20034)| `VisionPrescription.language`| _Equivalent_<br/>(35085/35086)| `VisionPrescription.language`| _Equivalent_<br/>(49495/49496)| `VisionPrescription.language`
| **`VisionPrescription.text`**| _Equivalent_<br/>(8675/8676)| `VisionPrescription.text`| _Equivalent_<br/>(20035/20036)| `VisionPrescription.text`| _Equivalent_<br/>(35087/35088)| `VisionPrescription.text`| _Equivalent_<br/>(49497/49498)| `VisionPrescription.text`
| **`VisionPrescription.contained`**| _Equivalent_<br/>(8677/8678)| `VisionPrescription.contained`| _Equivalent_<br/>(20037/20038)| `VisionPrescription.contained`| _Equivalent_<br/>(35089/35090)| `VisionPrescription.contained`| _Equivalent_<br/>(49499/49500)| `VisionPrescription.contained`
| **`VisionPrescription.extension`**| _Equivalent_<br/>(8679/8680)| `VisionPrescription.extension`| _Equivalent_<br/>(20039/20040)| `VisionPrescription.extension`| _Equivalent_<br/>(35091/35092)| `VisionPrescription.extension`| _Equivalent_<br/>(49501/49502)| `VisionPrescription.extension`
| **`VisionPrescription.modifierExtension`**| _Equivalent_<br/>(8681/8682)| `VisionPrescription.modifierExtension`| _Equivalent_<br/>(20041/20042)| `VisionPrescription.modifierExtension`| _Equivalent_<br/>(35093/35094)| `VisionPrescription.modifierExtension`| _Equivalent_<br/>(49503/49504)| `VisionPrescription.modifierExtension`
| **`VisionPrescription.identifier`**| _Equivalent_<br/>(8683/8684)| `VisionPrescription.identifier`| _Equivalent_<br/>(20043/20044)| `VisionPrescription.identifier`| _Equivalent_<br/>(35095/35096)| `VisionPrescription.identifier`| _Equivalent_<br/>(49505/49506)| `VisionPrescription.identifier`
| **`VisionPrescription.dateWritten`**| _Equivalent_<br/>(8685/8686)| `VisionPrescription.dateWritten`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(20051)<hr/>←←←← _Equivalent_ ←←←← <br/>(20052)| `VisionPrescription.dateWritten`| _Equivalent_<br/>(35105/35106)| `VisionPrescription.dateWritten`| _Equivalent_<br/>(49515/49516)| `VisionPrescription.dateWritten`
| **`VisionPrescription.patient`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8687)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8688)| `VisionPrescription.patient`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(20047)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(20048)| `VisionPrescription.patient`| _Equivalent_<br/>(35101/35102)| `VisionPrescription.patient`| _Equivalent_<br/>(49511/49512)| `VisionPrescription.patient`
| **`VisionPrescription.prescriber`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8689)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8690)| `VisionPrescription.prescriber`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(20053)<hr/>←←←← _RelatedTo_ ←←←← <br/>(20054)| `VisionPrescription.prescriber`| _Equivalent_<br/>(35107/35108)| `VisionPrescription.prescriber`| _Equivalent_<br/>(49517/49518)| `VisionPrescription.prescriber`
| **`VisionPrescription.encounter`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8691)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8692)| `VisionPrescription.encounter`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(20049)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(20050)| `VisionPrescription.encounter`| _Equivalent_<br/>(35103/35104)| `VisionPrescription.encounter`| _Equivalent_<br/>(49513/49514)| `VisionPrescription.encounter`
| **`VisionPrescription.reason[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8693)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8694)| `VisionPrescription.reason[x]`| | | | | | | 
| **`VisionPrescription.dispense`**| _Equivalent_<br/>(8695/8696)| `VisionPrescription.dispense`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1316)<hr/>←←←← _Equivalent_ ←←←← <br/>(1689)| `VisionPrescription.lensSpecification`| _Equivalent_<br/>(35109/35110)| `VisionPrescription.lensSpecification`| _Equivalent_<br/>(49519/49520)| `VisionPrescription.lensSpecification`
| **`VisionPrescription.dispense.id`**| _Equivalent_<br/>(8697/8698)| `VisionPrescription.dispense.id`| | | | | | | 
| **`VisionPrescription.dispense.extension`**| _Equivalent_<br/>(8699/8700)| `VisionPrescription.dispense.extension`| | | | | | | 
| **`VisionPrescription.dispense.modifierExtension`**| _Equivalent_<br/>(8701/8702)| `VisionPrescription.dispense.modifierExtension`| | | | | | | 
| **`VisionPrescription.dispense.product`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(8703)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(8704)| `VisionPrescription.dispense.product`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1330)<hr/>←←←← _Equivalent_ ←←←← <br/>(1703)| `VisionPrescription.lensSpecification.product`| _Equivalent_<br/>(35117/35118)| `VisionPrescription.lensSpecification.product`| _Equivalent_<br/>(49527/49528)| `VisionPrescription.lensSpecification.product`
| **`VisionPrescription.dispense.eye`**| _Equivalent_<br/>(8705/8706)| `VisionPrescription.dispense.eye`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1326)<hr/>←←←← _Equivalent_ ←←←← <br/>(1698)| `VisionPrescription.lensSpecification.eye`| _Equivalent_<br/>(35119/35120)| `VisionPrescription.lensSpecification.eye`| _Equivalent_<br/>(49529/49530)| `VisionPrescription.lensSpecification.eye`
| **`VisionPrescription.dispense.sphere`**| _Equivalent_<br/>(8707/8708)| `VisionPrescription.dispense.sphere`| _Equivalent_<br/>(1331/1704)| `VisionPrescription.lensSpecification.sphere`| _Equivalent_<br/>(35121/35122)| `VisionPrescription.lensSpecification.sphere`| _Equivalent_<br/>(49531/49532)| `VisionPrescription.lensSpecification.sphere`
| **`VisionPrescription.dispense.cylinder`**| _Equivalent_<br/>(8709/8710)| `VisionPrescription.dispense.cylinder`| _Equivalent_<br/>(1323/1695)| `VisionPrescription.lensSpecification.cylinder`| _Equivalent_<br/>(35123/35124)| `VisionPrescription.lensSpecification.cylinder`| _Equivalent_<br/>(49533/49534)| `VisionPrescription.lensSpecification.cylinder`
| **`VisionPrescription.dispense.axis`**| _Equivalent_<br/>(8711/8712)| `VisionPrescription.dispense.axis`| _Equivalent_<br/>(1318/1691)| `VisionPrescription.lensSpecification.axis`| _Equivalent_<br/>(35125/35126)| `VisionPrescription.lensSpecification.axis`| _Equivalent_<br/>(49535/49536)| `VisionPrescription.lensSpecification.axis`
| **`VisionPrescription.dispense.prism`**| _Equivalent_<br/>(8713/8714)| `VisionPrescription.dispense.prism`| →→→→ _RelatedTo_ →→→→ <br/>(1329)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1701)| `VisionPrescription.lensSpecification.prism`| _Equivalent_<br/>(35127/35128)| `VisionPrescription.lensSpecification.prism`| _Equivalent_<br/>(49537/49538)| `VisionPrescription.lensSpecification.prism`
| **`VisionPrescription.dispense.base`**| _Equivalent_<br/>(8715/8716)| `VisionPrescription.dispense.base`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1320)<hr/>←←←← _Equivalent_ ←←←← <br/>(1702)| `VisionPrescription.lensSpecification.prism.base`| _Equivalent_<br/>(35137/35138)| `VisionPrescription.lensSpecification.prism.base`| _Equivalent_<br/>(49547/49548)| `VisionPrescription.lensSpecification.prism.base`
| **`VisionPrescription.dispense.add`**| _Equivalent_<br/>(8717/8718)| `VisionPrescription.dispense.add`| _Equivalent_<br/>(1317/1690)| `VisionPrescription.lensSpecification.add`| _Equivalent_<br/>(35139/35140)| `VisionPrescription.lensSpecification.add`| _Equivalent_<br/>(49549/49550)| `VisionPrescription.lensSpecification.add`
| **`VisionPrescription.dispense.power`**| _Equivalent_<br/>(8719/8720)| `VisionPrescription.dispense.power`| _Equivalent_<br/>(1328/1700)| `VisionPrescription.lensSpecification.power`| _Equivalent_<br/>(35141/35142)| `VisionPrescription.lensSpecification.power`| _Equivalent_<br/>(49551/49552)| `VisionPrescription.lensSpecification.power`
| **`VisionPrescription.dispense.backCurve`**| _Equivalent_<br/>(8721/8722)| `VisionPrescription.dispense.backCurve`| _Equivalent_<br/>(1319/1692)| `VisionPrescription.lensSpecification.backCurve`| _Equivalent_<br/>(35143/35144)| `VisionPrescription.lensSpecification.backCurve`| _Equivalent_<br/>(49553/49554)| `VisionPrescription.lensSpecification.backCurve`
| **`VisionPrescription.dispense.diameter`**| _Equivalent_<br/>(8723/8724)| `VisionPrescription.dispense.diameter`| _Equivalent_<br/>(1324/1696)| `VisionPrescription.lensSpecification.diameter`| _Equivalent_<br/>(35145/35146)| `VisionPrescription.lensSpecification.diameter`| _Equivalent_<br/>(49555/49556)| `VisionPrescription.lensSpecification.diameter`
| **`VisionPrescription.dispense.duration`**| _Equivalent_<br/>(8725/8726)| `VisionPrescription.dispense.duration`| _Equivalent_<br/>(1325/1697)| `VisionPrescription.lensSpecification.duration`| _Equivalent_<br/>(35147/35148)| `VisionPrescription.lensSpecification.duration`| _Equivalent_<br/>(49557/49558)| `VisionPrescription.lensSpecification.duration`
| **`VisionPrescription.dispense.color`**| _Equivalent_<br/>(8727/8728)| `VisionPrescription.dispense.color`| _Equivalent_<br/>(1322/1694)| `VisionPrescription.lensSpecification.color`| _Equivalent_<br/>(35149/35150)| `VisionPrescription.lensSpecification.color`| _Equivalent_<br/>(49559/49560)| `VisionPrescription.lensSpecification.color`
| **`VisionPrescription.dispense.brand`**| _Equivalent_<br/>(8729/8730)| `VisionPrescription.dispense.brand`| _Equivalent_<br/>(1321/1693)| `VisionPrescription.lensSpecification.brand`| _Equivalent_<br/>(35151/35152)| `VisionPrescription.lensSpecification.brand`| _Equivalent_<br/>(49561/49562)| `VisionPrescription.lensSpecification.brand`
| **`VisionPrescription.dispense.notes`**| →→→→ _RelatedTo_ →→→→ <br/>(456)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8731)| `VisionPrescription.dispense.note`| _Equivalent_<br/>(1327/1699)| `VisionPrescription.lensSpecification.note`| _Equivalent_<br/>(35153/35154)| `VisionPrescription.lensSpecification.note`| _Equivalent_<br/>(49563/49564)| `VisionPrescription.lensSpecification.note`
| *34 of 34 elements used* | | *34 of 35 elements used* | | *30 of 39 elements used* | | *30 of 39 elements used* | | *30 of 39 elements used* 

