Comparison of 
Generated at Monday, April 14, 2025 6:17:22 PM

### Coverage

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | Coverage |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Coverage` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for Coverage Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `502` |
| Database Snapshot Count | `40` |
| Database Differential Count | `29` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Coverage` | `Coverage` | `Coverage` | Coverage | Insurance or medical plan or a payment agreement | 0..* | Coverage |  |  |
| `Coverage.beneficiary` | `Coverage.beneficiary` | `beneficiary` |  | Plan Beneficiary | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `Coverage.contained` | `Coverage.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Coverage.contract` | `Coverage.contract` | `contract` |  | Contract details | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Contract) |  |  |
| `Coverage.dependent` | `Coverage.dependent` | `dependent` |  | Dependent number | 0..1 | string |  |  |
| `Coverage.extension` | `Coverage.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Coverage.grouping` | `Coverage.grouping` | `grouping` |  | Additional coverage classifications | 0..1 | BackboneElement |  |  |
| `Coverage.grouping.class` | `Coverage.grouping.class` | `class` |  | An identifier for the class | 0..1 | string |  |  |
| `Coverage.grouping.classDisplay` | `Coverage.grouping.classDisplay` | `classDisplay` |  | Display text for the class | 0..1 | string |  |  |
| `Coverage.grouping.extension` | `Coverage.grouping.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Coverage.grouping.group` | `Coverage.grouping.group` | `group` |  | An identifier for the group | 0..1 | string |  |  |
| `Coverage.grouping.groupDisplay` | `Coverage.grouping.groupDisplay` | `groupDisplay` |  | Display text for an identifier for the group | 0..1 | string |  |  |
| `Coverage.grouping.id` | `Coverage.grouping.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Coverage.grouping.modifierExtension` | `Coverage.grouping.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Coverage.grouping.plan` | `Coverage.grouping.plan` | `plan` |  | An identifier for the plan | 0..1 | string |  |  |
| `Coverage.grouping.planDisplay` | `Coverage.grouping.planDisplay` | `planDisplay` |  | Display text for the plan | 0..1 | string |  |  |
| `Coverage.grouping.subClass` | `Coverage.grouping.subClass` | `subClass` |  | An identifier for the subsection of the class | 0..1 | string |  |  |
| `Coverage.grouping.subClassDisplay` | `Coverage.grouping.subClassDisplay` | `subClassDisplay` |  | Display text for the subsection of the subclass | 0..1 | string |  |  |
| `Coverage.grouping.subGroup` | `Coverage.grouping.subGroup` | `subGroup` |  | An identifier for the subsection of the group | 0..1 | string |  |  |
| `Coverage.grouping.subGroupDisplay` | `Coverage.grouping.subGroupDisplay` | `subGroupDisplay` |  | Display text for the subsection of the group | 0..1 | string |  |  |
| `Coverage.grouping.subPlan` | `Coverage.grouping.subPlan` | `subPlan` |  | An identifier for the subsection of the plan | 0..1 | string |  |  |
| `Coverage.grouping.subPlanDisplay` | `Coverage.grouping.subPlanDisplay` | `subPlanDisplay` |  | Display text for the subsection of the plan | 0..1 | string |  |  |
| `Coverage.id` | `Coverage.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Coverage.identifier` | `Coverage.identifier` | `identifier` |  | The primary coverage ID | 0..* | Identifier |  |  |
| `Coverage.implicitRules` | `Coverage.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Coverage.language` | `Coverage.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `Coverage.meta` | `Coverage.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Coverage.modifierExtension` | `Coverage.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Coverage.network` | `Coverage.network` | `network` |  | Insurer network | 0..1 | string |  |  |
| `Coverage.order` | `Coverage.order` | `order` |  | Relative order of the coverage | 0..1 | positiveInt |  |  |
| `Coverage.payor` | `Coverage.payor` | `payor` |  | Identifier for the plan or agreement issuer | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Coverage.period` | `Coverage.period` | `period` |  | Coverage start and end dates | 0..1 | Period |  |  |
| `Coverage.policyHolder` | `Coverage.policyHolder` | `policyHolder` |  | Owner of the policy | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Coverage.relationship` | `Coverage.relationship` | `relationship` |  | Beneficiary relationship to the Subscriber | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/policyholder-relationship` |
| `Coverage.sequence` | `Coverage.sequence` | `sequence` |  | The plan instance or sequence counter | 0..1 | string |  |  |
| `Coverage.status` | `Coverage.status` | `status` |  | active \| cancelled \| draft \| entered-in-error | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/fm-status` |
| `Coverage.subscriber` | `Coverage.subscriber` | `subscriber` |  | Subscriber to the policy | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Coverage.subscriberId` | `Coverage.subscriberId` | `subscriberId` |  | ID assigned to the Subscriber | 0..1 | string |  |  |
| `Coverage.text` | `Coverage.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Coverage.type` | `Coverage.type` | `type` |  | Type of coverage such as medical or accident | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/coverage-type` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Coverage](/docs/R2/Resources/Coverage.md)<br/> `http://hl7.org/fhir/StructureDefinition/Coverage\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `92`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `259`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Coverage](/docs/R3/Resources/Coverage.md)<br/> `http://hl7.org/fhir/StructureDefinition/Coverage\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `442`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `638`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Coverage](/docs/R4/Resources/Coverage.md)<br/> `http://hl7.org/fhir/StructureDefinition/Coverage\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1447`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1448`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Coverage](/docs/R4B/Resources/Coverage.md)<br/> `http://hl7.org/fhir/StructureDefinition/Coverage\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `958`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1187`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Coverage](/docs/R5/Resources/Coverage.md)<br/> `http://hl7.org/fhir/StructureDefinition/Coverage\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Coverage from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Coverage](/docs/R2/Resources/Coverage.md)| Relationship | R3 Coverage| Relationship | [R4 Coverage](/docs/R4/Resources/Coverage.md)| Relationship | [R4B Coverage](/docs/R4B/Resources/Coverage.md)| Relationship | [R5 Coverage](/docs/R5/Resources/Coverage.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Coverage`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4341)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4342)| **`Coverage`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12737)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12738)| `Coverage`| _Equivalent_<br/>(24974/24975)| `Coverage`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(40059)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40060)| `Coverage`
| `Coverage`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4341)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4342)| **`Coverage`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12737)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12738)| `Coverage`| _Equivalent_<br/>(24974/24975)| `Coverage`| →→→→ _Equivalent_ →→→→ <br/>(50111)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2110)| `Coverage.subscriberId`
| `Coverage.id`| _Equivalent_<br/>(4343/4344)| **`Coverage.id`**| _Equivalent_<br/>(12739/12740)| `Coverage.id`| _Equivalent_<br/>(24976/24977)| `Coverage.id`| _Equivalent_<br/>(40061/40062)| `Coverage.id`
| `Coverage.meta`| _Equivalent_<br/>(4345/4346)| **`Coverage.meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12741)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12742)| `Coverage.meta`| _Equivalent_<br/>(24978/24979)| `Coverage.meta`| _Equivalent_<br/>(40063/40064)| `Coverage.meta`
| `Coverage.implicitRules`| _Equivalent_<br/>(4347/4348)| **`Coverage.implicitRules`**| _Equivalent_<br/>(12743/12744)| `Coverage.implicitRules`| _Equivalent_<br/>(24980/24981)| `Coverage.implicitRules`| _Equivalent_<br/>(40065/40066)| `Coverage.implicitRules`
| `Coverage.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4349)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4350)| **`Coverage.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12745)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12746)| `Coverage.language`| _Equivalent_<br/>(24982/24983)| `Coverage.language`| _Equivalent_<br/>(40067/40068)| `Coverage.language`
| `Coverage.text`| _Equivalent_<br/>(4351/4352)| **`Coverage.text`**| _Equivalent_<br/>(12747/12748)| `Coverage.text`| _Equivalent_<br/>(24984/24985)| `Coverage.text`| _Equivalent_<br/>(40069/40070)| `Coverage.text`
| `Coverage.contained`| _Equivalent_<br/>(4353/4354)| **`Coverage.contained`**| _Equivalent_<br/>(12749/12750)| `Coverage.contained`| _Equivalent_<br/>(24986/24987)| `Coverage.contained`| _Equivalent_<br/>(40071/40072)| `Coverage.contained`
| `Coverage.extension`| _Equivalent_<br/>(4355/4356)| **`Coverage.extension`**| _Equivalent_<br/>(12751/12752)| `Coverage.extension`| _Equivalent_<br/>(24988/24989)| `Coverage.extension`| _Equivalent_<br/>(40073/40074)| `Coverage.extension`
| `Coverage.modifierExtension`| _Equivalent_<br/>(4357/4358)| **`Coverage.modifierExtension`**| _Equivalent_<br/>(12753/12754)| `Coverage.modifierExtension`| _Equivalent_<br/>(24990/24991)| `Coverage.modifierExtension`| _Equivalent_<br/>(40075/40076)| `Coverage.modifierExtension`
| `Coverage.bin`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(173)<hr/>←←←← __ ←←←← <br/>()| **`Coverage.identifier`**| _Equivalent_<br/>(12755/12756)| `Coverage.identifier`| _Equivalent_<br/>(24992/24993)| `Coverage.identifier`| _Equivalent_<br/>(40077/40078)| `Coverage.identifier`
| `Coverage.identifier`| →→→→ _Equivalent_ →→→→ <br/>(4365)<hr/>←←←← __ ←←←← <br/>()| **`Coverage.identifier`**| _Equivalent_<br/>(12755/12756)| `Coverage.identifier`| _Equivalent_<br/>(24992/24993)| `Coverage.identifier`| _Equivalent_<br/>(40077/40078)| `Coverage.identifier`
| | | **`Coverage.status`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12757)<hr/>←←←← _Equivalent_ ←←←← <br/>(12758)| `Coverage.status`| _Equivalent_<br/>(24994/24995)| `Coverage.status`| _Equivalent_<br/>(40079/40080)| `Coverage.status`
| `Coverage.type`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4361)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4362)| **`Coverage.type`**| _Equivalent_<br/>(12759/12760)| `Coverage.type`| _Equivalent_<br/>(24996/24997)| `Coverage.type`| _Equivalent_<br/>(40081/40082)| `Coverage.type`
| | | **`Coverage.policyHolder`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12761)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12762)| `Coverage.policyHolder`| _Equivalent_<br/>(24998/24999)| `Coverage.policyHolder`| _Equivalent_<br/>(40083/40084)| `Coverage.policyHolder`
| `Coverage.subscriber`| →→→→ _RelatedTo_ →→→→ <br/>(4371)<hr/>←←←← _RelatedTo_ ←←←← <br/>(4372)| **`Coverage.subscriber`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12763)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12764)| `Coverage.subscriber`| _Equivalent_<br/>(25000/25001)| `Coverage.subscriber`| _Equivalent_<br/>(40085/40086)| `Coverage.subscriber`
| `Coverage.subscriberId`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4363)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4364)| **`Coverage.subscriberId`**| _Equivalent_<br/>(12765/12766)| `Coverage.subscriberId`| _Equivalent_<br/>(25002/25003)| `Coverage.subscriberId`| →→→→ _RelatedTo_ →→→→ <br/>(40087)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40088)| `Coverage.subscriberId`
| | | **`Coverage.beneficiary`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12767)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12768)| `Coverage.beneficiary`| _Equivalent_<br/>(25004/25005)| `Coverage.beneficiary`| _Equivalent_<br/>(40089/40090)| `Coverage.beneficiary`
| | | **`Coverage.relationship`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(12769)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12770)| `Coverage.relationship`| _Equivalent_<br/>(25008/25009)| `Coverage.relationship`| _Equivalent_<br/>(40093/40094)| `Coverage.relationship`
| `Coverage.period`| _Equivalent_<br/>(4359/4360)| **`Coverage.period`**| _Equivalent_<br/>(12771/12772)| `Coverage.period`| _Equivalent_<br/>(25010/25011)| `Coverage.period`| _Equivalent_<br/>(40095/40096)| `Coverage.period`
| `Coverage.issuer`| →→→→ _RelatedTo_ →→→→ <br/>(175)<hr/>←←←← _RelatedTo_ ←←←← <br/>(591)| **`Coverage.payor`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12773)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12774)| `Coverage.payor`| _Equivalent_<br/>(25012/25013)| `Coverage.payor`| | | 
| | | **`Coverage.grouping`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(964)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1450)| `Coverage.class`| _Equivalent_<br/>(25014/25015)| `Coverage.class`| _Equivalent_<br/>(40098/40099)| `Coverage.class`
| | | **`Coverage.grouping.id`**| | | | | | | 
| | | **`Coverage.grouping.extension`**| | | | | | | 
| | | **`Coverage.grouping.modifierExtension`**| | | | | | | 
| `Coverage.group`| _Equivalent_<br/>(174/587)| **`Coverage.grouping.group`**| | | | | | | 
| | | **`Coverage.grouping.groupDisplay`**| | | | | | | 
| | | **`Coverage.grouping.subGroup`**| | | | | | | 
| | | **`Coverage.grouping.subGroupDisplay`**| | | | | | | 
| `Coverage.plan`| _Equivalent_<br/>(176/588)| **`Coverage.grouping.plan`**| | | | | | | 
| | | **`Coverage.grouping.planDisplay`**| | | | | | | 
| `Coverage.subPlan`| _Equivalent_<br/>(177/589)| **`Coverage.grouping.subPlan`**| | | | | | | 
| | | **`Coverage.grouping.subPlanDisplay`**| | | | | | | 
| | | **`Coverage.grouping.class`**| | | | | | | 
| | | **`Coverage.grouping.classDisplay`**| | | | | | | 
| | | **`Coverage.grouping.subClass`**| | | | | | | 
| | | **`Coverage.grouping.subClassDisplay`**| | | | | | | 
| `Coverage.dependent`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4367)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4368)| **`Coverage.dependent`**| _Equivalent_<br/>(12778/12779)| `Coverage.dependent`| _Equivalent_<br/>(25006/25007)| `Coverage.dependent`| _Equivalent_<br/>(40091/40092)| `Coverage.dependent`
| `Coverage.sequence`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4369)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4370)| **`Coverage.sequence`**| | | | | | | 
| | | **`Coverage.order`**| _Equivalent_<br/>(12780/12781)| `Coverage.order`| _Equivalent_<br/>(25028/25029)| `Coverage.order`| _Equivalent_<br/>(40112/40113)| `Coverage.order`
| `Coverage.network`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4373)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4374)| **`Coverage.network`**| _Equivalent_<br/>(12782/12783)| `Coverage.network`| _Equivalent_<br/>(25030/25031)| `Coverage.network`| _Equivalent_<br/>(40114/40115)| `Coverage.network`
| `Coverage.contract`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4375)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4376)| **`Coverage.contract`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12784)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12785)| `Coverage.contract`| _Equivalent_<br/>(25058/25059)| `Coverage.contract`| _Equivalent_<br/>(40142/40143)| `Coverage.contract`
| *23 of 23 elements used* | | *40 of 40 elements used* | | *24 of 43 elements used* <br/>remaining elements:<br/>`Coverage.class.extension`, `Coverage.class.id`, `Coverage.class.modifierExtension`, `Coverage.class.name`, `Coverage.class.type`, `Coverage.class.value`, `Coverage.costToBeneficiary`, `Coverage.costToBeneficiary.exception`, `Coverage.costToBeneficiary.exception.extension`, `Coverage.costToBeneficiary.exception.id`, `Coverage.costToBeneficiary.exception.modifierExtension`, `Coverage.costToBeneficiary.exception.period`, `Coverage.costToBeneficiary.exception.type`, `Coverage.costToBeneficiary.extension`, `Coverage.costToBeneficiary.id`, `Coverage.costToBeneficiary.modifierExtension`, `Coverage.costToBeneficiary.type`, `Coverage.costToBeneficiary.value[x]`, `Coverage.subrogation`| | *24 of 43 elements used* <br/>remaining elements:<br/>`Coverage.class.extension`, `Coverage.class.id`, `Coverage.class.modifierExtension`, `Coverage.class.name`, `Coverage.class.type`, `Coverage.class.value`, `Coverage.costToBeneficiary`, `Coverage.costToBeneficiary.exception`, `Coverage.costToBeneficiary.exception.extension`, `Coverage.costToBeneficiary.exception.id`, `Coverage.costToBeneficiary.exception.modifierExtension`, `Coverage.costToBeneficiary.exception.period`, `Coverage.costToBeneficiary.exception.type`, `Coverage.costToBeneficiary.extension`, `Coverage.costToBeneficiary.id`, `Coverage.costToBeneficiary.modifierExtension`, `Coverage.costToBeneficiary.type`, `Coverage.costToBeneficiary.value[x]`, `Coverage.subrogation`| | *23 of 55 elements used* <br/>remaining elements:<br/>`Coverage.class.extension`, `Coverage.class.id`, `Coverage.class.modifierExtension`, `Coverage.class.name`, `Coverage.class.type`, `Coverage.class.value`, `Coverage.costToBeneficiary`, `Coverage.costToBeneficiary.category`, `Coverage.costToBeneficiary.exception`, `Coverage.costToBeneficiary.exception.extension`, `Coverage.costToBeneficiary.exception.id`, `Coverage.costToBeneficiary.exception.modifierExtension`, `Coverage.costToBeneficiary.exception.period`, `Coverage.costToBeneficiary.exception.type`, `Coverage.costToBeneficiary.extension`, `Coverage.costToBeneficiary.id`, `Coverage.costToBeneficiary.modifierExtension`, `Coverage.costToBeneficiary.network`, `Coverage.costToBeneficiary.term`, `Coverage.costToBeneficiary.type`, `Coverage.costToBeneficiary.unit`, `Coverage.costToBeneficiary.value[x]`, `Coverage.insurancePlan`, `Coverage.insurer`, `Coverage.kind`, `Coverage.paymentBy`, `Coverage.paymentBy.extension`, `Coverage.paymentBy.id`, `Coverage.paymentBy.modifierExtension`, `Coverage.paymentBy.party`, `Coverage.paymentBy.responsibility`, `Coverage.subrogation`

