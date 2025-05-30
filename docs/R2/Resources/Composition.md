Comparison of 
Generated at Monday, April 14, 2025 6:17:16 PM

### Composition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | Composition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Composition` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for Composition Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `56` |
| Database Snapshot Count | `46` |
| Database Differential Count | `29` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Composition` | `Composition` | `Composition` | Composition | A set of resources composed into a single coherent clinical statement with clinical attestation | 0..* | Composition |  |  |
| `Composition.attester` | `Composition.attester` | `attester` |  | Attests to accuracy of composition | 0..* | BackboneElement |  |  |
| `Composition.attester.extension` | `Composition.attester.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Composition.attester.id` | `Composition.attester.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Composition.attester.mode` | `Composition.attester.mode` | `mode` |  | personal \| professional \| legal \| official | 1..* | code | `Required` | `http://hl7.org/fhir/ValueSet/composition-attestation-mode` |
| `Composition.attester.modifierExtension` | `Composition.attester.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Composition.attester.party` | `Composition.attester.party` | `party` |  | Who attested the composition | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `Composition.attester.time` | `Composition.attester.time` | `time` |  | When composition attested | 0..1 | dateTime |  |  |
| `Composition.author` | `Composition.author` | `author` |  | Who and/or what authored the composition | 1..* | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Composition.class` | `Composition.class` | `class` |  | Categorization of Composition | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/doc-classcodes` |
| `Composition.confidentiality` | `Composition.confidentiality` | `confidentiality` |  | As defined by affinity domain | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/v3-Confidentiality` |
| `Composition.contained` | `Composition.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Composition.custodian` | `Composition.custodian` | `custodian` |  | Organization which maintains the composition | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Composition.date` | `Composition.date` | `date` |  | Composition editing time | 1..1 | dateTime |  |  |
| `Composition.encounter` | `Composition.encounter` | `encounter` |  | Context of the Composition | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `Composition.event` | `Composition.event` | `event` |  | The clinical service(s) being documented | 0..* | BackboneElement |  |  |
| `Composition.event.code` | `Composition.event.code` | `code` |  | Code(s) that apply to the event being documented | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/v3-ActCode` |
| `Composition.event.detail` | `Composition.event.detail` | `detail` |  | The event(s) being documented | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `Composition.event.extension` | `Composition.event.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Composition.event.id` | `Composition.event.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Composition.event.modifierExtension` | `Composition.event.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Composition.event.period` | `Composition.event.period` | `period` |  | The period covered by the documentation | 0..1 | Period |  |  |
| `Composition.extension` | `Composition.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Composition.id` | `Composition.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Composition.identifier` | `Composition.identifier` | `identifier` |  | Logical identifier of composition (version-independent) | 0..1 | Identifier |  |  |
| `Composition.implicitRules` | `Composition.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Composition.language` | `Composition.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `Composition.meta` | `Composition.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Composition.modifierExtension` | `Composition.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Composition.section` | `Composition.section` | `section` |  | Composition is broken into sections | 0..* | BackboneElement |  |  |
| `Composition.section.code` | `Composition.section.code` | `code` |  | Classification of section (recommended) | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/doc-section-codes` |
| `Composition.section.emptyReason` | `Composition.section.emptyReason` | `emptyReason` |  | Why the section is empty | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/list-empty-reason` |
| `Composition.section.entry` | `Composition.section.entry` | `entry` |  | A reference to data that supports this section | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `Composition.section.extension` | `Composition.section.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Composition.section.id` | `Composition.section.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Composition.section.mode` | `Composition.section.mode` | `mode` |  | working \| snapshot \| changes | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/list-mode` |
| `Composition.section.modifierExtension` | `Composition.section.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Composition.section.orderedBy` | `Composition.section.orderedBy` | `orderedBy` |  | Order of section entries | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/list-order` |
| `Composition.section.section` | `Composition.section.section` | `section` |  | Nested Section | 0..* | Composition.section |  |  |
| `Composition.section.text` | `Composition.section.text` | `text` |  | Text summary of the section, for human interpretation | 0..1 | Narrative |  |  |
| `Composition.section.title` | `Composition.section.title` | `title` |  | Label for section (e.g. for ToC) | 0..1 | string |  |  |
| `Composition.status` | `Composition.status` | `status` |  | preliminary \| final \| amended \| entered-in-error | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/composition-status` |
| `Composition.subject` | `Composition.subject` | `subject` |  | Who and/or what the composition is about | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `Composition.text` | `Composition.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Composition.title` | `Composition.title` | `title` |  | Human Readable name/title | 1..1 | string |  |  |
| `Composition.type` | `Composition.type` | `type` |  | Kind of composition (LOINC if possible) | 1..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/doc-typecodes` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Composition](/docs/R2/Resources/Composition.md)<br/> `http://hl7.org/fhir/StructureDefinition/Composition\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `88`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `255`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Composition](/docs/R3/Resources/Composition.md)<br/> `http://hl7.org/fhir/StructureDefinition/Composition\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `437`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `633`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Composition](/docs/R4/Resources/Composition.md)<br/> `http://hl7.org/fhir/StructureDefinition/Composition\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1437`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1438`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Composition](/docs/R4B/Resources/Composition.md)<br/> `http://hl7.org/fhir/StructureDefinition/Composition\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `953`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1182`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Composition](/docs/R5/Resources/Composition.md)<br/> `http://hl7.org/fhir/StructureDefinition/Composition\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Composition from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Composition| Relationship | [R3 Composition](/docs/R3/Resources/Composition.md)| Relationship | [R4 Composition](/docs/R4/Resources/Composition.md)| Relationship | [R4B Composition](/docs/R4B/Resources/Composition.md)| Relationship | [R5 Composition](/docs/R5/Resources/Composition.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Composition`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3832)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3833)| `Composition`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12197)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12198)| `Composition`| _Equivalent_<br/>(24017/24018)| `Composition`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(39321)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(39322)| `Composition`
| **`Composition.id`**| _Equivalent_<br/>(3834/3835)| `Composition.id`| _Equivalent_<br/>(12199/12200)| `Composition.id`| _Equivalent_<br/>(24019/24020)| `Composition.id`| _Equivalent_<br/>(39323/39324)| `Composition.id`
| **`Composition.meta`**| _Equivalent_<br/>(3836/3837)| `Composition.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12201)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12202)| `Composition.meta`| _Equivalent_<br/>(24021/24022)| `Composition.meta`| _Equivalent_<br/>(39325/39326)| `Composition.meta`
| **`Composition.implicitRules`**| _Equivalent_<br/>(3838/3839)| `Composition.implicitRules`| _Equivalent_<br/>(12203/12204)| `Composition.implicitRules`| _Equivalent_<br/>(24023/24024)| `Composition.implicitRules`| _Equivalent_<br/>(39327/39328)| `Composition.implicitRules`
| **`Composition.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3840)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(3841)| `Composition.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12205)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12206)| `Composition.language`| _Equivalent_<br/>(24025/24026)| `Composition.language`| _Equivalent_<br/>(39329/39330)| `Composition.language`
| **`Composition.text`**| _Equivalent_<br/>(3842/3843)| `Composition.text`| _Equivalent_<br/>(12207/12208)| `Composition.text`| _Equivalent_<br/>(24027/24028)| `Composition.text`| _Equivalent_<br/>(39331/39332)| `Composition.text`
| **`Composition.contained`**| _Equivalent_<br/>(3844/3845)| `Composition.contained`| _Equivalent_<br/>(12209/12210)| `Composition.contained`| _Equivalent_<br/>(24029/24030)| `Composition.contained`| _Equivalent_<br/>(39333/39334)| `Composition.contained`
| **`Composition.extension`**| _Equivalent_<br/>(3846/3847)| `Composition.extension`| _Equivalent_<br/>(12211/12212)| `Composition.extension`| _Equivalent_<br/>(24031/24032)| `Composition.extension`| _Equivalent_<br/>(39335/39336)| `Composition.extension`
| **`Composition.modifierExtension`**| _Equivalent_<br/>(3848/3849)| `Composition.modifierExtension`| _Equivalent_<br/>(12213/12214)| `Composition.modifierExtension`| _Equivalent_<br/>(24033/24034)| `Composition.modifierExtension`| _Equivalent_<br/>(39337/39338)| `Composition.modifierExtension`
| **`Composition.identifier`**| _Equivalent_<br/>(3850/3851)| `Composition.identifier`| _Equivalent_<br/>(12215/12216)| `Composition.identifier`| _Equivalent_<br/>(24035/24036)| `Composition.identifier`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(39339)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(39340)| `Composition.identifier`
| **`Composition.date`**| _Equivalent_<br/>(3852/3853)| `Composition.date`| _Equivalent_<br/>(12225/12226)| `Composition.date`| _Equivalent_<br/>(24047/24048)| `Composition.date`| _Equivalent_<br/>(39351/39352)| `Composition.date`
| **`Composition.type`**| _Equivalent_<br/>(3854/3855)| `Composition.type`| _Equivalent_<br/>(12219/12220)| `Composition.type`| _Equivalent_<br/>(24039/24040)| `Composition.type`| _Equivalent_<br/>(39343/39344)| `Composition.type`
| **`Composition.class`**| _Equivalent_<br/>(3856/3857)| `Composition.class`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(904)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1416)| `Composition.category`| _Equivalent_<br/>(24041/24042)| `Composition.category`| _Equivalent_<br/>(39345/39346)| `Composition.category`
| **`Composition.title`**| _Equivalent_<br/>(3858/3859)| `Composition.title`| _Equivalent_<br/>(12229/12230)| `Composition.title`| _Equivalent_<br/>(24051/24052)| `Composition.title`| _Equivalent_<br/>(39355/39356)| `Composition.title`
| **`Composition.status`**| _Equivalent_<br/>(3860/3861)| `Composition.status`| _Equivalent_<br/>(12217/12218)| `Composition.status`| _Equivalent_<br/>(24037/24038)| `Composition.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(39341)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(39342)| `Composition.status`
| **`Composition.confidentiality`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(3862)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(3863)| `Composition.confidentiality`| _Equivalent_<br/>(12231/12232)| `Composition.confidentiality`| _Equivalent_<br/>(24053/24054)| `Composition.confidentiality`| | | 
| **`Composition.subject`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3864)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3865)| `Composition.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12221)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12222)| `Composition.subject`| _Equivalent_<br/>(24043/24044)| `Composition.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(39347)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(39348)| `Composition.subject`
| **`Composition.author`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3866)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3867)| `Composition.author`| →→→→ _RelatedTo_ →→→→ <br/>(12227)<hr/>←←←← _RelatedTo_ ←←←← <br/>(12228)| `Composition.author`| _Equivalent_<br/>(24049/24050)| `Composition.author`| _Equivalent_<br/>(39353/39354)| `Composition.author`
| **`Composition.attester`**| _Equivalent_<br/>(3868/3869)| `Composition.attester`| _Equivalent_<br/>(12233/12234)| `Composition.attester`| _Equivalent_<br/>(24055/24056)| `Composition.attester`| _Equivalent_<br/>(39358/39359)| `Composition.attester`
| **`Composition.attester.id`**| _Equivalent_<br/>(3870/3871)| `Composition.attester.id`| _Equivalent_<br/>(12235/12236)| `Composition.attester.id`| _Equivalent_<br/>(24057/24058)| `Composition.attester.id`| _Equivalent_<br/>(39360/39361)| `Composition.attester.id`
| **`Composition.attester.extension`**| _Equivalent_<br/>(3872/3873)| `Composition.attester.extension`| _Equivalent_<br/>(12237/12238)| `Composition.attester.extension`| _Equivalent_<br/>(24059/24060)| `Composition.attester.extension`| _Equivalent_<br/>(39362/39363)| `Composition.attester.extension`
| **`Composition.attester.modifierExtension`**| _Equivalent_<br/>(3874/3875)| `Composition.attester.modifierExtension`| _Equivalent_<br/>(12239/12240)| `Composition.attester.modifierExtension`| _Equivalent_<br/>(24061/24062)| `Composition.attester.modifierExtension`| _Equivalent_<br/>(39364/39365)| `Composition.attester.modifierExtension`
| **`Composition.attester.mode`**| _Equivalent_<br/>(3876/3877)| `Composition.attester.mode`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(12241)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12242)| `Composition.attester.mode`| _Equivalent_<br/>(24063/24064)| `Composition.attester.mode`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(39366)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(39367)| `Composition.attester.mode`
| **`Composition.attester.time`**| _Equivalent_<br/>(3878/3879)| `Composition.attester.time`| _Equivalent_<br/>(12243/12244)| `Composition.attester.time`| _Equivalent_<br/>(24065/24066)| `Composition.attester.time`| _Equivalent_<br/>(39368/39369)| `Composition.attester.time`
| **`Composition.attester.party`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3880)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3881)| `Composition.attester.party`| →→→→ _RelatedTo_ →→→→ <br/>(12245)<hr/>←←←← _RelatedTo_ ←←←← <br/>(12246)| `Composition.attester.party`| _Equivalent_<br/>(24067/24068)| `Composition.attester.party`| _Equivalent_<br/>(39370/39371)| `Composition.attester.party`
| **`Composition.custodian`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3882)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3883)| `Composition.custodian`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12247)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12248)| `Composition.custodian`| _Equivalent_<br/>(24069/24070)| `Composition.custodian`| _Equivalent_<br/>(39372/39373)| `Composition.custodian`
| **`Composition.event`**| _Equivalent_<br/>(3884/3885)| `Composition.event`| _Equivalent_<br/>(12261/12262)| `Composition.event`| _Equivalent_<br/>(24083/24084)| `Composition.event`| _Equivalent_<br/>(39381/39382)| `Composition.event`
| **`Composition.event.id`**| _Equivalent_<br/>(3886/3887)| `Composition.event.id`| _Equivalent_<br/>(12263/12264)| `Composition.event.id`| _Equivalent_<br/>(24085/24086)| `Composition.event.id`| _Equivalent_<br/>(39383/39384)| `Composition.event.id`
| **`Composition.event.extension`**| _Equivalent_<br/>(3888/3889)| `Composition.event.extension`| _Equivalent_<br/>(12265/12266)| `Composition.event.extension`| _Equivalent_<br/>(24087/24088)| `Composition.event.extension`| _Equivalent_<br/>(39385/39386)| `Composition.event.extension`
| **`Composition.event.modifierExtension`**| _Equivalent_<br/>(3890/3891)| `Composition.event.modifierExtension`| _Equivalent_<br/>(12267/12268)| `Composition.event.modifierExtension`| _Equivalent_<br/>(24089/24090)| `Composition.event.modifierExtension`| _Equivalent_<br/>(39387/39388)| `Composition.event.modifierExtension`
| **`Composition.event.code`**| _Equivalent_<br/>(3892/3893)| `Composition.event.code`| _Equivalent_<br/>(12269/12270)| `Composition.event.code`| _Equivalent_<br/>(24091/24092)| `Composition.event.code`| | | 
| **`Composition.event.period`**| _Equivalent_<br/>(3894/3895)| `Composition.event.period`| _Equivalent_<br/>(12271/12272)| `Composition.event.period`| _Equivalent_<br/>(24093/24094)| `Composition.event.period`| _Equivalent_<br/>(39390/39391)| `Composition.event.period`
| **`Composition.event.detail`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3896)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3897)| `Composition.event.detail`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12273)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12274)| `Composition.event.detail`| _Equivalent_<br/>(24095/24096)| `Composition.event.detail`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(39392)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(39393)| `Composition.event.detail`
| **`Composition.encounter`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3898)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3899)| `Composition.encounter`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12223)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12224)| `Composition.encounter`| _Equivalent_<br/>(24045/24046)| `Composition.encounter`| _Equivalent_<br/>(39349/39350)| `Composition.encounter`
| **`Composition.section`**| _Equivalent_<br/>(3900/3901)| `Composition.section`| _Equivalent_<br/>(12275/12276)| `Composition.section`| _Equivalent_<br/>(24097/24098)| `Composition.section`| _Equivalent_<br/>(39394/39395)| `Composition.section`
| **`Composition.section.id`**| _Equivalent_<br/>(3902/3903)| `Composition.section.id`| _Equivalent_<br/>(12277/12278)| `Composition.section.id`| _Equivalent_<br/>(24099/24100)| `Composition.section.id`| _Equivalent_<br/>(39396/39397)| `Composition.section.id`
| **`Composition.section.extension`**| _Equivalent_<br/>(3904/3905)| `Composition.section.extension`| _Equivalent_<br/>(12279/12280)| `Composition.section.extension`| _Equivalent_<br/>(24101/24102)| `Composition.section.extension`| _Equivalent_<br/>(39398/39399)| `Composition.section.extension`
| **`Composition.section.modifierExtension`**| _Equivalent_<br/>(3906/3907)| `Composition.section.modifierExtension`| _Equivalent_<br/>(12281/12282)| `Composition.section.modifierExtension`| _Equivalent_<br/>(24103/24104)| `Composition.section.modifierExtension`| _Equivalent_<br/>(39400/39401)| `Composition.section.modifierExtension`
| **`Composition.section.title`**| _Equivalent_<br/>(3908/3909)| `Composition.section.title`| _Equivalent_<br/>(12283/12284)| `Composition.section.title`| _Equivalent_<br/>(24105/24106)| `Composition.section.title`| _Equivalent_<br/>(39402/39403)| `Composition.section.title`
| **`Composition.section.code`**| _Equivalent_<br/>(3910/3911)| `Composition.section.code`| _Equivalent_<br/>(12285/12286)| `Composition.section.code`| _Equivalent_<br/>(24107/24108)| `Composition.section.code`| _Equivalent_<br/>(39404/39405)| `Composition.section.code`
| **`Composition.section.text`**| _Equivalent_<br/>(3912/3913)| `Composition.section.text`| _Equivalent_<br/>(12287/12288)| `Composition.section.text`| _Equivalent_<br/>(24113/24114)| `Composition.section.text`| _Equivalent_<br/>(39410/39411)| `Composition.section.text`
| **`Composition.section.mode`**| _Equivalent_<br/>(3914/3915)| `Composition.section.mode`| _Equivalent_<br/>(12289/12290)| `Composition.section.mode`| _Equivalent_<br/>(24115/24116)| `Composition.section.mode`| | | 
| **`Composition.section.orderedBy`**| _Equivalent_<br/>(3916/3917)| `Composition.section.orderedBy`| _Equivalent_<br/>(12291/12292)| `Composition.section.orderedBy`| _Equivalent_<br/>(24117/24118)| `Composition.section.orderedBy`| _Equivalent_<br/>(39413/39414)| `Composition.section.orderedBy`
| **`Composition.section.entry`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(3918)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(3919)| `Composition.section.entry`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12293)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12294)| `Composition.section.entry`| _Equivalent_<br/>(24119/24120)| `Composition.section.entry`| _Equivalent_<br/>(39415/39416)| `Composition.section.entry`
| **`Composition.section.emptyReason`**| _Equivalent_<br/>(3920/3921)| `Composition.section.emptyReason`| _Equivalent_<br/>(12295/12296)| `Composition.section.emptyReason`| _Equivalent_<br/>(24121/24122)| `Composition.section.emptyReason`| _Equivalent_<br/>(39417/39418)| `Composition.section.emptyReason`
| **`Composition.section.section`**| _Equivalent_<br/>(3922/3923)| `Composition.section.section`| _Equivalent_<br/>(12297/12298)| `Composition.section.section`| _Equivalent_<br/>(24123/24124)| `Composition.section.section`| _Equivalent_<br/>(39419/39420)| `Composition.section.section`
| *46 of 46 elements used* | | *46 of 52 elements used* <br/>remaining elements:<br/>`Composition.relatesTo`, `Composition.relatesTo.code`, `Composition.relatesTo.extension`, `Composition.relatesTo.id`, `Composition.relatesTo.modifierExtension`, `Composition.relatesTo.target[x]`| | *46 of 54 elements used* <br/>remaining elements:<br/>`Composition.relatesTo`, `Composition.relatesTo.code`, `Composition.relatesTo.extension`, `Composition.relatesTo.id`, `Composition.relatesTo.modifierExtension`, `Composition.relatesTo.target[x]`, `Composition.section.author`, `Composition.section.focus`| | *46 of 54 elements used* <br/>remaining elements:<br/>`Composition.relatesTo`, `Composition.relatesTo.code`, `Composition.relatesTo.extension`, `Composition.relatesTo.id`, `Composition.relatesTo.modifierExtension`, `Composition.relatesTo.target[x]`, `Composition.section.author`, `Composition.section.focus`| | *43 of 51 elements used* <br/>remaining elements:<br/>`Composition.name`, `Composition.note`, `Composition.relatesTo`, `Composition.section.author`, `Composition.section.focus`, `Composition.url`, `Composition.useContext`, `Composition.version`

