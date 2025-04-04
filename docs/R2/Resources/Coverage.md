Comparison of 
Generated at Friday, April 4, 2025 2:58:35 PM

### Coverage

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | Coverage |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Coverage` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for Coverage Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `61` |
| Database Snapshot Count | `23` |
| Database Differential Count | `15` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Coverage` | `Coverage` | `Coverage` | Coverage | Insurance or medical plan | 0..* | Coverage |  |  |
| `Coverage.bin` | `Coverage.bin` | `bin` |  | BIN Number | 0..1 | Identifier |  |  |
| `Coverage.contained` | `Coverage.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Coverage.contract` | `Coverage.contract` | `contract` |  | Contract details | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Contract) |  |  |
| `Coverage.dependent` | `Coverage.dependent` | `dependent` |  | The dependent number | 0..1 | positiveInt |  |  |
| `Coverage.extension` | `Coverage.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Coverage.group` | `Coverage.group` | `group` |  | An identifier for the group | 0..1 | string |  |  |
| `Coverage.id` | `Coverage.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Coverage.identifier` | `Coverage.identifier` | `identifier` |  | The primary coverage ID | 0..* | Identifier |  |  |
| `Coverage.implicitRules` | `Coverage.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Coverage.issuer` | `Coverage.issuer` | `issuer` |  | An identifier for the plan issuer | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Coverage.language` | `Coverage.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `Coverage.meta` | `Coverage.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Coverage.modifierExtension` | `Coverage.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Coverage.network` | `Coverage.network` | `network` |  | Insurer network | 0..1 | Identifier |  |  |
| `Coverage.period` | `Coverage.period` | `period` |  | Coverage start and end dates | 0..1 | Period |  |  |
| `Coverage.plan` | `Coverage.plan` | `plan` |  | An identifier for the plan | 0..1 | string |  |  |
| `Coverage.sequence` | `Coverage.sequence` | `sequence` |  | The plan instance or sequence counter | 0..1 | positiveInt |  |  |
| `Coverage.subPlan` | `Coverage.subPlan` | `subPlan` |  | An identifier for the subsection of the plan | 0..1 | string |  |  |
| `Coverage.subscriber` | `Coverage.subscriber` | `subscriber` |  | Plan holder information | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `Coverage.subscriberId` | `Coverage.subscriberId` | `subscriberId` |  | Subscriber ID | 0..1 | Identifier |  |  |
| `Coverage.text` | `Coverage.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Coverage.type` | `Coverage.type` | `type` |  | Type of coverage | 0..1 | Coding | `Example` | `http://hl7.org/fhir/ValueSet/v3-ActCoverageTypeCode` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Coverage](/docs/R2/Resources/Coverage.md)<br/> `http://hl7.org/fhir/StructureDefinition/Coverage\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `92`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `259`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Coverage](/docs/R3/Resources/Coverage.md)<br/> `http://hl7.org/fhir/StructureDefinition/Coverage\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `442`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `638`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Coverage](/docs/R4/Resources/Coverage.md)<br/> `http://hl7.org/fhir/StructureDefinition/Coverage\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1447`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1448`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Coverage](/docs/R4B/Resources/Coverage.md)<br/> `http://hl7.org/fhir/StructureDefinition/Coverage\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `958`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1187`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Coverage](/docs/R5/Resources/Coverage.md)<br/> `http://hl7.org/fhir/StructureDefinition/Coverage\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Coverage from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Coverage| Relationship | [R3 Coverage](/docs/R3/Resources/Coverage.md)| Relationship | [R4 Coverage](/docs/R4/Resources/Coverage.md)| Relationship | [R4B Coverage](/docs/R4B/Resources/Coverage.md)| Relationship | [R5 Coverage](/docs/R5/Resources/Coverage.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Coverage`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4341)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4342)| `Coverage`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12737)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12738)| `Coverage`| _Equivalent_<br/>(24974/24975)| `Coverage`| →→→→ _Equivalent_ →→→→ <br/>(50111)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2110)| `Coverage`
| **`Coverage`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4341)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4342)| `Coverage`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12737)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12738)| `Coverage`| _Equivalent_<br/>(24974/24975)| `Coverage`| →→→→ _Equivalent_ →→→→ <br/>(50111)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2110)| `Coverage.subscriberId`
| **`Coverage.id`**| _Equivalent_<br/>(4343/4344)| `Coverage.id`| _Equivalent_<br/>(12739/12740)| `Coverage.id`| _Equivalent_<br/>(24976/24977)| `Coverage.id`| _Equivalent_<br/>(40061/40062)| `Coverage.id`
| **`Coverage.meta`**| _Equivalent_<br/>(4345/4346)| `Coverage.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12741)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12742)| `Coverage.meta`| _Equivalent_<br/>(24978/24979)| `Coverage.meta`| _Equivalent_<br/>(40063/40064)| `Coverage.meta`
| **`Coverage.implicitRules`**| _Equivalent_<br/>(4347/4348)| `Coverage.implicitRules`| _Equivalent_<br/>(12743/12744)| `Coverage.implicitRules`| _Equivalent_<br/>(24980/24981)| `Coverage.implicitRules`| _Equivalent_<br/>(40065/40066)| `Coverage.implicitRules`
| **`Coverage.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4349)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4350)| `Coverage.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12745)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12746)| `Coverage.language`| _Equivalent_<br/>(24982/24983)| `Coverage.language`| _Equivalent_<br/>(40067/40068)| `Coverage.language`
| **`Coverage.text`**| _Equivalent_<br/>(4351/4352)| `Coverage.text`| _Equivalent_<br/>(12747/12748)| `Coverage.text`| _Equivalent_<br/>(24984/24985)| `Coverage.text`| _Equivalent_<br/>(40069/40070)| `Coverage.text`
| **`Coverage.contained`**| _Equivalent_<br/>(4353/4354)| `Coverage.contained`| _Equivalent_<br/>(12749/12750)| `Coverage.contained`| _Equivalent_<br/>(24986/24987)| `Coverage.contained`| _Equivalent_<br/>(40071/40072)| `Coverage.contained`
| **`Coverage.extension`**| _Equivalent_<br/>(4355/4356)| `Coverage.extension`| _Equivalent_<br/>(12751/12752)| `Coverage.extension`| _Equivalent_<br/>(24988/24989)| `Coverage.extension`| _Equivalent_<br/>(40073/40074)| `Coverage.extension`
| **`Coverage.modifierExtension`**| _Equivalent_<br/>(4357/4358)| `Coverage.modifierExtension`| _Equivalent_<br/>(12753/12754)| `Coverage.modifierExtension`| _Equivalent_<br/>(24990/24991)| `Coverage.modifierExtension`| _Equivalent_<br/>(40075/40076)| `Coverage.modifierExtension`
| **`Coverage.issuer`**| →→→→ _RelatedTo_ →→→→ <br/>(175)<hr/>←←←← _RelatedTo_ ←←←← <br/>(591)| `Coverage.payor`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12773)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12774)| `Coverage.payor`| _Equivalent_<br/>(25012/25013)| `Coverage.payor`| | | 
| **`Coverage.bin`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(173)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(590)| `Coverage.identifier`| _Equivalent_<br/>(12755/12756)| `Coverage.identifier`| _Equivalent_<br/>(24992/24993)| `Coverage.identifier`| _Equivalent_<br/>(40077/40078)| `Coverage.identifier`
| **`Coverage.period`**| _Equivalent_<br/>(4359/4360)| `Coverage.period`| _Equivalent_<br/>(12771/12772)| `Coverage.period`| _Equivalent_<br/>(25010/25011)| `Coverage.period`| _Equivalent_<br/>(40095/40096)| `Coverage.period`
| **`Coverage.type`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4361)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4362)| `Coverage.type`| _Equivalent_<br/>(12759/12760)| `Coverage.type`| _Equivalent_<br/>(24996/24997)| `Coverage.type`| _Equivalent_<br/>(40081/40082)| `Coverage.type`
| **`Coverage.subscriberId`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4363)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4364)| `Coverage.subscriberId`| _Equivalent_<br/>(12765/12766)| `Coverage.subscriberId`| _Equivalent_<br/>(25002/25003)| `Coverage.subscriberId`| →→→→ _RelatedTo_ →→→→ <br/>(40087)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40088)| `Coverage.subscriberId`
| **`Coverage.identifier`**| →→→→ _Equivalent_ →→→→ <br/>(4365)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4366)| `Coverage.identifier`| _Equivalent_<br/>(12755/12756)| `Coverage.identifier`| _Equivalent_<br/>(24992/24993)| `Coverage.identifier`| _Equivalent_<br/>(40077/40078)| `Coverage.identifier`
| **`Coverage.group`**| _Equivalent_<br/>(174/587)| `Coverage.grouping.group`| | | | | | | 
| **`Coverage.plan`**| _Equivalent_<br/>(176/588)| `Coverage.grouping.plan`| | | | | | | 
| **`Coverage.subPlan`**| _Equivalent_<br/>(177/589)| `Coverage.grouping.subPlan`| | | | | | | 
| **`Coverage.dependent`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4367)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4368)| `Coverage.dependent`| _Equivalent_<br/>(12778/12779)| `Coverage.dependent`| _Equivalent_<br/>(25006/25007)| `Coverage.dependent`| _Equivalent_<br/>(40091/40092)| `Coverage.dependent`
| **`Coverage.sequence`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4369)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4370)| `Coverage.sequence`| | | | | | | 
| **`Coverage.subscriber`**| →→→→ _RelatedTo_ →→→→ <br/>(4371)<hr/>←←←← _RelatedTo_ ←←←← <br/>(4372)| `Coverage.subscriber`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12763)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12764)| `Coverage.subscriber`| _Equivalent_<br/>(25000/25001)| `Coverage.subscriber`| _Equivalent_<br/>(40085/40086)| `Coverage.subscriber`
| **`Coverage.network`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4373)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4374)| `Coverage.network`| _Equivalent_<br/>(12782/12783)| `Coverage.network`| _Equivalent_<br/>(25030/25031)| `Coverage.network`| _Equivalent_<br/>(40114/40115)| `Coverage.network`
| **`Coverage.contract`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4375)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4376)| `Coverage.contract`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12784)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12785)| `Coverage.contract`| _Equivalent_<br/>(25058/25059)| `Coverage.contract`| _Equivalent_<br/>(40142/40143)| `Coverage.contract`
| *23 of 23 elements used* | | *22 of 40 elements used* <br/>remaining elements:<br/>`Coverage.beneficiary`, `Coverage.grouping`, `Coverage.grouping.class`, `Coverage.grouping.classDisplay`, `Coverage.grouping.extension`, `Coverage.grouping.groupDisplay`, `Coverage.grouping.id`, `Coverage.grouping.modifierExtension`, `Coverage.grouping.planDisplay`, `Coverage.grouping.subClass`, `Coverage.grouping.subClassDisplay`, `Coverage.grouping.subGroup`, `Coverage.grouping.subGroupDisplay`, `Coverage.grouping.subPlanDisplay`, `Coverage.order`, `Coverage.policyHolder`, `Coverage.relationship`, `Coverage.status`| | *18 of 43 elements used* <br/>remaining elements:<br/>`Coverage.beneficiary`, `Coverage.class`, `Coverage.class.extension`, `Coverage.class.id`, `Coverage.class.modifierExtension`, `Coverage.class.name`, `Coverage.class.type`, `Coverage.class.value`, `Coverage.costToBeneficiary`, `Coverage.costToBeneficiary.exception`, `Coverage.costToBeneficiary.exception.extension`, `Coverage.costToBeneficiary.exception.id`, `Coverage.costToBeneficiary.exception.modifierExtension`, `Coverage.costToBeneficiary.exception.period`, `Coverage.costToBeneficiary.exception.type`, `Coverage.costToBeneficiary.extension`, `Coverage.costToBeneficiary.id`, `Coverage.costToBeneficiary.modifierExtension`, `Coverage.costToBeneficiary.type`, `Coverage.costToBeneficiary.value[x]`, `Coverage.order`, `Coverage.policyHolder`, `Coverage.relationship`, `Coverage.status`, `Coverage.subrogation`| | *18 of 43 elements used* <br/>remaining elements:<br/>`Coverage.beneficiary`, `Coverage.class`, `Coverage.class.extension`, `Coverage.class.id`, `Coverage.class.modifierExtension`, `Coverage.class.name`, `Coverage.class.type`, `Coverage.class.value`, `Coverage.costToBeneficiary`, `Coverage.costToBeneficiary.exception`, `Coverage.costToBeneficiary.exception.extension`, `Coverage.costToBeneficiary.exception.id`, `Coverage.costToBeneficiary.exception.modifierExtension`, `Coverage.costToBeneficiary.exception.period`, `Coverage.costToBeneficiary.exception.type`, `Coverage.costToBeneficiary.extension`, `Coverage.costToBeneficiary.id`, `Coverage.costToBeneficiary.modifierExtension`, `Coverage.costToBeneficiary.type`, `Coverage.costToBeneficiary.value[x]`, `Coverage.order`, `Coverage.policyHolder`, `Coverage.relationship`, `Coverage.status`, `Coverage.subrogation`| | *17 of 55 elements used* <br/>remaining elements:<br/>`Coverage.beneficiary`, `Coverage.class`, `Coverage.class.extension`, `Coverage.class.id`, `Coverage.class.modifierExtension`, `Coverage.class.name`, `Coverage.class.type`, `Coverage.class.value`, `Coverage.costToBeneficiary`, `Coverage.costToBeneficiary.category`, `Coverage.costToBeneficiary.exception`, `Coverage.costToBeneficiary.exception.extension`, `Coverage.costToBeneficiary.exception.id`, `Coverage.costToBeneficiary.exception.modifierExtension`, `Coverage.costToBeneficiary.exception.period`, `Coverage.costToBeneficiary.exception.type`, `Coverage.costToBeneficiary.extension`, `Coverage.costToBeneficiary.id`, `Coverage.costToBeneficiary.modifierExtension`, `Coverage.costToBeneficiary.network`, `Coverage.costToBeneficiary.term`, `Coverage.costToBeneficiary.type`, `Coverage.costToBeneficiary.unit`, `Coverage.costToBeneficiary.value[x]`, `Coverage.insurancePlan`, `Coverage.insurer`, `Coverage.kind`, `Coverage.order`, `Coverage.paymentBy`, `Coverage.paymentBy.extension`, `Coverage.paymentBy.id`, `Coverage.paymentBy.modifierExtension`, `Coverage.paymentBy.party`, `Coverage.paymentBy.responsibility`, `Coverage.policyHolder`, `Coverage.relationship`, `Coverage.status`, `Coverage.subrogation`

