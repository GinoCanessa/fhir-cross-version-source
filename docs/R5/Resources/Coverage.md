Comparison of 
Generated at Monday, April 14, 2025 6:17:47 PM

### Coverage

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Coverage |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Coverage` |
| Version | 5.0.0 |
| Description | Financial instrument which may be used to reimburse or pay for health care products and services. Includes both insurance and self-payment. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2284` |
| Database Snapshot Count | `55` |
| Database Differential Count | `35` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Coverage` | `Coverage` | `Coverage` | Coverage | Insurance or medical plan or a payment agreement | 0..* | Coverage |  |  |
| `Coverage.beneficiary` | `Coverage.beneficiary` | `beneficiary` | Coverage.beneficiary | Plan beneficiary | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `Coverage.class` | `Coverage.class` | `class` | Coverage.class | Additional coverage classifications | 0..* | BackboneElement |  |  |
| `Coverage.class.extension` | `Coverage.class.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Coverage.class.id` | `Coverage.class.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Coverage.class.modifierExtension` | `Coverage.class.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Coverage.class.name` | `Coverage.class.name` | `name` | Coverage.class.name | Human readable description of the type and value | 0..1 | string |  |  |
| `Coverage.class.type` | `Coverage.class.type` | `type` | Coverage.class.type | Type of class such as 'group' or 'plan' | 1..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/coverage-class` |
| `Coverage.class.value` | `Coverage.class.value` | `value` | Coverage.class.value | Value associated with the type | 1..1 | Identifier |  |  |
| `Coverage.contained` | `Coverage.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Coverage.contract` | `Coverage.contract` | `contract` | Coverage.contract | Contract details | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Contract) |  |  |
| `Coverage.costToBeneficiary` | `Coverage.costToBeneficiary` | `costToBeneficiary` | Coverage.costToBeneficiary | Patient payments for services/products | 0..* | BackboneElement |  |  |
| `Coverage.costToBeneficiary.category` | `Coverage.costToBeneficiary.category` | `category` | Coverage.costToBeneficiary.category | Benefit classification | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/ex-benefitcategory` |
| `Coverage.costToBeneficiary.exception` | `Coverage.costToBeneficiary.exception` | `exception` | Coverage.costToBeneficiary.exception | Exceptions for patient payments | 0..* | BackboneElement |  |  |
| `Coverage.costToBeneficiary.exception.extension` | `Coverage.costToBeneficiary.exception.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Coverage.costToBeneficiary.exception.id` | `Coverage.costToBeneficiary.exception.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Coverage.costToBeneficiary.exception.modifierExtension` | `Coverage.costToBeneficiary.exception.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Coverage.costToBeneficiary.exception.period` | `Coverage.costToBeneficiary.exception.period` | `period` | Coverage.costToBeneficiary.exception.period | The effective period of the exception | 0..1 | Period |  |  |
| `Coverage.costToBeneficiary.exception.type` | `Coverage.costToBeneficiary.exception.type` | `type` | Coverage.costToBeneficiary.exception.type | Exception category | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/coverage-financial-exception` |
| `Coverage.costToBeneficiary.extension` | `Coverage.costToBeneficiary.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Coverage.costToBeneficiary.id` | `Coverage.costToBeneficiary.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Coverage.costToBeneficiary.modifierExtension` | `Coverage.costToBeneficiary.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Coverage.costToBeneficiary.network` | `Coverage.costToBeneficiary.network` | `network` | Coverage.costToBeneficiary.network | In or out of network | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/benefit-network` |
| `Coverage.costToBeneficiary.term` | `Coverage.costToBeneficiary.term` | `term` | Coverage.costToBeneficiary.term | Annual or lifetime | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/benefit-term` |
| `Coverage.costToBeneficiary.type` | `Coverage.costToBeneficiary.type` | `type` | Coverage.costToBeneficiary.type | Cost category | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/coverage-copay-type` |
| `Coverage.costToBeneficiary.unit` | `Coverage.costToBeneficiary.unit` | `unit` | Coverage.costToBeneficiary.unit | Individual or family | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/benefit-unit` |
| `Coverage.costToBeneficiary.value[x]` | `Coverage.costToBeneficiary.value[x]` | `value[x]` | Coverage.costToBeneficiary.value[x] | The amount or percentage due from the beneficiary | 0..1 | Money, Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `Coverage.dependent` | `Coverage.dependent` | `dependent` | Coverage.dependent | Dependent number | 0..1 | string |  |  |
| `Coverage.extension` | `Coverage.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Coverage.id` | `Coverage.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Coverage.identifier` | `Coverage.identifier` | `identifier` | Coverage.identifier | Business identifier(s) for this coverage | 0..* | Identifier |  |  |
| `Coverage.implicitRules` | `Coverage.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Coverage.insurancePlan` | `Coverage.insurancePlan` | `insurancePlan` | Coverage.insurancePlan | Insurance plan details | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/InsurancePlan) |  |  |
| `Coverage.insurer` | `Coverage.insurer` | `insurer` | Coverage.insurer | Issuer of the policy | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Coverage.kind` | `Coverage.kind` | `kind` | Coverage.kind | insurance \| self-pay \| other | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/coverage-kind|5.0.0` |
| `Coverage.language` | `Coverage.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `Coverage.meta` | `Coverage.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Coverage.modifierExtension` | `Coverage.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Coverage.network` | `Coverage.network` | `network` | Coverage.network | Insurer network | 0..1 | string |  |  |
| `Coverage.order` | `Coverage.order` | `order` | Coverage.order | Relative order of the coverage | 0..1 | positiveInt |  |  |
| `Coverage.paymentBy` | `Coverage.paymentBy` | `paymentBy` | Coverage.paymentBy | Self-pay parties and responsibility | 0..* | BackboneElement |  |  |
| `Coverage.paymentBy.extension` | `Coverage.paymentBy.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Coverage.paymentBy.id` | `Coverage.paymentBy.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Coverage.paymentBy.modifierExtension` | `Coverage.paymentBy.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Coverage.paymentBy.party` | `Coverage.paymentBy.party` | `party` | Coverage.paymentBy.party | Parties performing self-payment | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Coverage.paymentBy.responsibility` | `Coverage.paymentBy.responsibility` | `responsibility` | Coverage.paymentBy.responsibility | Party's responsibility | 0..1 | string |  |  |
| `Coverage.period` | `Coverage.period` | `period` | Coverage.period | Coverage start and end dates | 0..1 | Period |  |  |
| `Coverage.policyHolder` | `Coverage.policyHolder` | `policyHolder` | Coverage.policyHolder | Owner of the policy | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Coverage.relationship` | `Coverage.relationship` | `relationship` | Coverage.relationship | Beneficiary relationship to the subscriber | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/subscriber-relationship` |
| `Coverage.status` | `Coverage.status` | `status` | Coverage.status | active \| cancelled \| draft \| entered-in-error | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/fm-status|5.0.0` |
| `Coverage.subrogation` | `Coverage.subrogation` | `subrogation` | Coverage.subrogation | Reimbursement to insurer | 0..1 | boolean |  |  |
| `Coverage.subscriber` | `Coverage.subscriber` | `subscriber` | Coverage.subscriber | Subscriber to the policy | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Coverage.subscriberId` | `Coverage.subscriberId` | `subscriberId` | Coverage.subscriberId | ID assigned to the subscriber | 0..* | Identifier |  |  |
| `Coverage.text` | `Coverage.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Coverage.type` | `Coverage.type` | `type` | Coverage.type | Coverage category such as medical or accident | 0..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/coverage-type` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Coverage](/docs/R2/Resources/Coverage.md)<br/> `http://hl7.org/fhir/StructureDefinition/Coverage\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `92`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `259`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Coverage](/docs/R3/Resources/Coverage.md)<br/> `http://hl7.org/fhir/StructureDefinition/Coverage\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `442`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `638`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Coverage](/docs/R4/Resources/Coverage.md)<br/> `http://hl7.org/fhir/StructureDefinition/Coverage\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1447`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1448`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Coverage](/docs/R4B/Resources/Coverage.md)<br/> `http://hl7.org/fhir/StructureDefinition/Coverage\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `958`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1187`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [Coverage](/docs/R5/Resources/Coverage.md)<br/> `http://hl7.org/fhir/StructureDefinition/Coverage\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Coverage from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Coverage](/docs/R2/Resources/Coverage.md)| Relationship | [R3 Coverage](/docs/R3/Resources/Coverage.md)| Relationship | [R4 Coverage](/docs/R4/Resources/Coverage.md)| Relationship | [R4B Coverage](/docs/R4B/Resources/Coverage.md)| Relationship | R5 Coverage
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Coverage`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4341)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4342)| `Coverage`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12737)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12738)| `Coverage`| _Equivalent_<br/>(24974/24975)| `Coverage`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(40059)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40060)| **`Coverage`**
| `Coverage.id`| _Equivalent_<br/>(4343/4344)| `Coverage.id`| _Equivalent_<br/>(12739/12740)| `Coverage.id`| _Equivalent_<br/>(24976/24977)| `Coverage.id`| _Equivalent_<br/>(40061/40062)| **`Coverage.id`**
| `Coverage.meta`| _Equivalent_<br/>(4345/4346)| `Coverage.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12741)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12742)| `Coverage.meta`| _Equivalent_<br/>(24978/24979)| `Coverage.meta`| _Equivalent_<br/>(40063/40064)| **`Coverage.meta`**
| `Coverage.implicitRules`| _Equivalent_<br/>(4347/4348)| `Coverage.implicitRules`| _Equivalent_<br/>(12743/12744)| `Coverage.implicitRules`| _Equivalent_<br/>(24980/24981)| `Coverage.implicitRules`| _Equivalent_<br/>(40065/40066)| **`Coverage.implicitRules`**
| `Coverage.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4349)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4350)| `Coverage.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12745)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12746)| `Coverage.language`| _Equivalent_<br/>(24982/24983)| `Coverage.language`| _Equivalent_<br/>(40067/40068)| **`Coverage.language`**
| `Coverage.text`| _Equivalent_<br/>(4351/4352)| `Coverage.text`| _Equivalent_<br/>(12747/12748)| `Coverage.text`| _Equivalent_<br/>(24984/24985)| `Coverage.text`| _Equivalent_<br/>(40069/40070)| **`Coverage.text`**
| `Coverage.contained`| _Equivalent_<br/>(4353/4354)| `Coverage.contained`| _Equivalent_<br/>(12749/12750)| `Coverage.contained`| _Equivalent_<br/>(24986/24987)| `Coverage.contained`| _Equivalent_<br/>(40071/40072)| **`Coverage.contained`**
| `Coverage.extension`| _Equivalent_<br/>(4355/4356)| `Coverage.extension`| _Equivalent_<br/>(12751/12752)| `Coverage.extension`| _Equivalent_<br/>(24988/24989)| `Coverage.extension`| _Equivalent_<br/>(40073/40074)| **`Coverage.extension`**
| `Coverage.modifierExtension`| _Equivalent_<br/>(4357/4358)| `Coverage.modifierExtension`| _Equivalent_<br/>(12753/12754)| `Coverage.modifierExtension`| _Equivalent_<br/>(24990/24991)| `Coverage.modifierExtension`| _Equivalent_<br/>(40075/40076)| **`Coverage.modifierExtension`**
| `Coverage.bin`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(173)<hr/>←←←← __ ←←←← <br/>()| `Coverage.identifier`| _Equivalent_<br/>(12755/12756)| `Coverage.identifier`| _Equivalent_<br/>(24992/24993)| `Coverage.identifier`| _Equivalent_<br/>(40077/40078)| **`Coverage.identifier`**
| `Coverage.identifier`| →→→→ _Equivalent_ →→→→ <br/>(4365)<hr/>←←←← __ ←←←← <br/>()| `Coverage.identifier`| _Equivalent_<br/>(12755/12756)| `Coverage.identifier`| _Equivalent_<br/>(24992/24993)| `Coverage.identifier`| _Equivalent_<br/>(40077/40078)| **`Coverage.identifier`**
| | | `Coverage.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12757)<hr/>←←←← _Equivalent_ ←←←← <br/>(12758)| `Coverage.status`| _Equivalent_<br/>(24994/24995)| `Coverage.status`| _Equivalent_<br/>(40079/40080)| **`Coverage.status`**
| | | | | | | | | **`Coverage.kind`**
| | | | | | | | | **`Coverage.paymentBy`**
| | | | | | | | | **`Coverage.paymentBy.id`**
| | | | | | | | | **`Coverage.paymentBy.extension`**
| | | | | | | | | **`Coverage.paymentBy.modifierExtension`**
| | | | | | | | | **`Coverage.paymentBy.party`**
| | | | | | | | | **`Coverage.paymentBy.responsibility`**
| `Coverage.type`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4361)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4362)| `Coverage.type`| _Equivalent_<br/>(12759/12760)| `Coverage.type`| _Equivalent_<br/>(24996/24997)| `Coverage.type`| _Equivalent_<br/>(40081/40082)| **`Coverage.type`**
| | | `Coverage.policyHolder`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12761)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12762)| `Coverage.policyHolder`| _Equivalent_<br/>(24998/24999)| `Coverage.policyHolder`| _Equivalent_<br/>(40083/40084)| **`Coverage.policyHolder`**
| `Coverage.subscriber`| →→→→ _RelatedTo_ →→→→ <br/>(4371)<hr/>←←←← _RelatedTo_ ←←←← <br/>(4372)| `Coverage.subscriber`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12763)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12764)| `Coverage.subscriber`| _Equivalent_<br/>(25000/25001)| `Coverage.subscriber`| _Equivalent_<br/>(40085/40086)| **`Coverage.subscriber`**
| `Coverage`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4341)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4342)| `Coverage`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12737)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12738)| `Coverage`| _Equivalent_<br/>(24974/24975)| `Coverage`| →→→→ _Equivalent_ →→→→ <br/>(50111)<hr/>←←←← __ ←←←← <br/>()| **`Coverage.subscriberId`**
| `Coverage.subscriberId`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4363)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4364)| `Coverage.subscriberId`| _Equivalent_<br/>(12765/12766)| `Coverage.subscriberId`| _Equivalent_<br/>(25002/25003)| `Coverage.subscriberId`| →→→→ _RelatedTo_ →→→→ <br/>(40087)<hr/>←←←← __ ←←←← <br/>()| **`Coverage.subscriberId`**
| | | `Coverage.beneficiary`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12767)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12768)| `Coverage.beneficiary`| _Equivalent_<br/>(25004/25005)| `Coverage.beneficiary`| _Equivalent_<br/>(40089/40090)| **`Coverage.beneficiary`**
| `Coverage.dependent`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4367)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4368)| `Coverage.dependent`| _Equivalent_<br/>(12778/12779)| `Coverage.dependent`| _Equivalent_<br/>(25006/25007)| `Coverage.dependent`| _Equivalent_<br/>(40091/40092)| **`Coverage.dependent`**
| | | `Coverage.relationship`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(12769)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12770)| `Coverage.relationship`| _Equivalent_<br/>(25008/25009)| `Coverage.relationship`| _Equivalent_<br/>(40093/40094)| **`Coverage.relationship`**
| `Coverage.period`| _Equivalent_<br/>(4359/4360)| `Coverage.period`| _Equivalent_<br/>(12771/12772)| `Coverage.period`| _Equivalent_<br/>(25010/25011)| `Coverage.period`| _Equivalent_<br/>(40095/40096)| **`Coverage.period`**
| | | | | | | | | **`Coverage.insurer`**
| | | `Coverage.grouping`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(964)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1450)| `Coverage.class`| _Equivalent_<br/>(25014/25015)| `Coverage.class`| _Equivalent_<br/>(40098/40099)| **`Coverage.class`**
| | | | | `Coverage.class.id`| _Equivalent_<br/>(25016/25017)| `Coverage.class.id`| _Equivalent_<br/>(40100/40101)| **`Coverage.class.id`**
| | | | | `Coverage.class.extension`| _Equivalent_<br/>(25018/25019)| `Coverage.class.extension`| _Equivalent_<br/>(40102/40103)| **`Coverage.class.extension`**
| | | | | `Coverage.class.modifierExtension`| _Equivalent_<br/>(25020/25021)| `Coverage.class.modifierExtension`| _Equivalent_<br/>(40104/40105)| **`Coverage.class.modifierExtension`**
| | | | | `Coverage.class.type`| _Equivalent_<br/>(25022/25023)| `Coverage.class.type`| _Equivalent_<br/>(40106/40107)| **`Coverage.class.type`**
| | | | | `Coverage.class.value`| _Equivalent_<br/>(25024/25025)| `Coverage.class.value`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(40108)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40109)| **`Coverage.class.value`**
| | | | | `Coverage.class.name`| _Equivalent_<br/>(25026/25027)| `Coverage.class.name`| _Equivalent_<br/>(40110/40111)| **`Coverage.class.name`**
| | | `Coverage.order`| _Equivalent_<br/>(12780/12781)| `Coverage.order`| _Equivalent_<br/>(25028/25029)| `Coverage.order`| _Equivalent_<br/>(40112/40113)| **`Coverage.order`**
| `Coverage.network`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(4373)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4374)| `Coverage.network`| _Equivalent_<br/>(12782/12783)| `Coverage.network`| _Equivalent_<br/>(25030/25031)| `Coverage.network`| _Equivalent_<br/>(40114/40115)| **`Coverage.network`**
| | | | | `Coverage.costToBeneficiary`| _Equivalent_<br/>(25032/25033)| `Coverage.costToBeneficiary`| _Equivalent_<br/>(40116/40117)| **`Coverage.costToBeneficiary`**
| | | | | `Coverage.costToBeneficiary.id`| _Equivalent_<br/>(25034/25035)| `Coverage.costToBeneficiary.id`| _Equivalent_<br/>(40118/40119)| **`Coverage.costToBeneficiary.id`**
| | | | | `Coverage.costToBeneficiary.extension`| _Equivalent_<br/>(25036/25037)| `Coverage.costToBeneficiary.extension`| _Equivalent_<br/>(40120/40121)| **`Coverage.costToBeneficiary.extension`**
| | | | | `Coverage.costToBeneficiary.modifierExtension`| _Equivalent_<br/>(25038/25039)| `Coverage.costToBeneficiary.modifierExtension`| _Equivalent_<br/>(40122/40123)| **`Coverage.costToBeneficiary.modifierExtension`**
| | | | | `Coverage.costToBeneficiary.type`| _Equivalent_<br/>(25040/25041)| `Coverage.costToBeneficiary.type`| _Equivalent_<br/>(40124/40125)| **`Coverage.costToBeneficiary.type`**
| | | | | | | | | **`Coverage.costToBeneficiary.category`**
| | | | | | | | | **`Coverage.costToBeneficiary.network`**
| | | | | | | | | **`Coverage.costToBeneficiary.unit`**
| | | | | | | | | **`Coverage.costToBeneficiary.term`**
| | | | | `Coverage.costToBeneficiary.value[x]`| _Equivalent_<br/>(25042/25043)| `Coverage.costToBeneficiary.value[x]`| →→→→ _Equivalent_ →→→→ <br/>(40126)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(40127)| **`Coverage.costToBeneficiary.value[x]`**
| | | | | `Coverage.costToBeneficiary.exception`| _Equivalent_<br/>(25044/25045)| `Coverage.costToBeneficiary.exception`| _Equivalent_<br/>(40128/40129)| **`Coverage.costToBeneficiary.exception`**
| | | | | `Coverage.costToBeneficiary.exception.id`| _Equivalent_<br/>(25046/25047)| `Coverage.costToBeneficiary.exception.id`| _Equivalent_<br/>(40130/40131)| **`Coverage.costToBeneficiary.exception.id`**
| | | | | `Coverage.costToBeneficiary.exception.extension`| _Equivalent_<br/>(25048/25049)| `Coverage.costToBeneficiary.exception.extension`| _Equivalent_<br/>(40132/40133)| **`Coverage.costToBeneficiary.exception.extension`**
| | | | | `Coverage.costToBeneficiary.exception.modifierExtension`| _Equivalent_<br/>(25050/25051)| `Coverage.costToBeneficiary.exception.modifierExtension`| _Equivalent_<br/>(40134/40135)| **`Coverage.costToBeneficiary.exception.modifierExtension`**
| | | | | `Coverage.costToBeneficiary.exception.type`| _Equivalent_<br/>(25052/25053)| `Coverage.costToBeneficiary.exception.type`| _Equivalent_<br/>(40136/40137)| **`Coverage.costToBeneficiary.exception.type`**
| | | | | `Coverage.costToBeneficiary.exception.period`| _Equivalent_<br/>(25054/25055)| `Coverage.costToBeneficiary.exception.period`| _Equivalent_<br/>(40138/40139)| **`Coverage.costToBeneficiary.exception.period`**
| | | | | `Coverage.subrogation`| _Equivalent_<br/>(25056/25057)| `Coverage.subrogation`| _Equivalent_<br/>(40140/40141)| **`Coverage.subrogation`**
| `Coverage.contract`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4375)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4376)| `Coverage.contract`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12784)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12785)| `Coverage.contract`| _Equivalent_<br/>(25058/25059)| `Coverage.contract`| _Equivalent_<br/>(40142/40143)| **`Coverage.contract`**
| | | | | | | | | **`Coverage.insurancePlan`**
| *18 of 23 elements used* <br/>remaining elements:<br/>`Coverage.group`, `Coverage.issuer`, `Coverage.plan`, `Coverage.sequence`, `Coverage.subPlan`| | *23 of 40 elements used* <br/>remaining elements:<br/>`Coverage.grouping.class`, `Coverage.grouping.classDisplay`, `Coverage.grouping.extension`, `Coverage.grouping.group`, `Coverage.grouping.groupDisplay`, `Coverage.grouping.id`, `Coverage.grouping.modifierExtension`, `Coverage.grouping.plan`, `Coverage.grouping.planDisplay`, `Coverage.grouping.subClass`, `Coverage.grouping.subClassDisplay`, `Coverage.grouping.subGroup`, `Coverage.grouping.subGroupDisplay`, `Coverage.grouping.subPlan`, `Coverage.grouping.subPlanDisplay`, `Coverage.payor`, `Coverage.sequence`| | *42 of 43 elements used* <br/>remaining elements:<br/>`Coverage.payor`| | *42 of 43 elements used* <br/>remaining elements:<br/>`Coverage.payor`| | *55 of 55 elements used* 

