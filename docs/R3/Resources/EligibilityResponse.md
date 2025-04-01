Comparison of 
Generated at Tuesday, April 1, 2025 1:39:14 PM

### EligibilityResponse

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | EligibilityResponse |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/EligibilityResponse` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for EligibilityResponse Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `515` |
| Database Snapshot Count | `50` |
| Database Differential Count | `30` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `EligibilityResponse` | `EligibilityResponse` | `EligibilityResponse` | EligibilityResponse | EligibilityResponse resource | 0..* | EligibilityResponse |  |  |
| `EligibilityResponse.contained` | `EligibilityResponse.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `EligibilityResponse.created` | `EligibilityResponse.created` | `created` |  | Creation date | 0..1 | dateTime |  |  |
| `EligibilityResponse.disposition` | `EligibilityResponse.disposition` | `disposition` |  | Disposition Message | 0..1 | string |  |  |
| `EligibilityResponse.error` | `EligibilityResponse.error` | `error` |  | Processing errors | 0..* | BackboneElement |  |  |
| `EligibilityResponse.error.code` | `EligibilityResponse.error.code` | `code` |  | Error code detailing processing issues | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/adjudication-error` |
| `EligibilityResponse.error.extension` | `EligibilityResponse.error.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `EligibilityResponse.error.id` | `EligibilityResponse.error.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `EligibilityResponse.error.modifierExtension` | `EligibilityResponse.error.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `EligibilityResponse.extension` | `EligibilityResponse.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `EligibilityResponse.form` | `EligibilityResponse.form` | `form` |  | Printed Form Identifier | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/forms` |
| `EligibilityResponse.id` | `EligibilityResponse.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `EligibilityResponse.identifier` | `EligibilityResponse.identifier` | `identifier` |  | Business Identifier | 0..* | Identifier |  |  |
| `EligibilityResponse.implicitRules` | `EligibilityResponse.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `EligibilityResponse.inforce` | `EligibilityResponse.inforce` | `inforce` |  | Coverage inforce indicator | 0..1 | boolean |  |  |
| `EligibilityResponse.insurance` | `EligibilityResponse.insurance` | `insurance` |  | Details by insurance coverage | 0..* | BackboneElement |  |  |
| `EligibilityResponse.insurance.benefitBalance` | `EligibilityResponse.insurance.benefitBalance` | `benefitBalance` |  | Benefits by Category | 0..* | BackboneElement |  |  |
| `EligibilityResponse.insurance.benefitBalance.category` | `EligibilityResponse.insurance.benefitBalance.category` | `category` |  | Type of services covered | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/benefit-category` |
| `EligibilityResponse.insurance.benefitBalance.description` | `EligibilityResponse.insurance.benefitBalance.description` | `description` |  | Description of the benefit or services covered | 0..1 | string |  |  |
| `EligibilityResponse.insurance.benefitBalance.excluded` | `EligibilityResponse.insurance.benefitBalance.excluded` | `excluded` |  | Excluded from the plan | 0..1 | boolean |  |  |
| `EligibilityResponse.insurance.benefitBalance.extension` | `EligibilityResponse.insurance.benefitBalance.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `EligibilityResponse.insurance.benefitBalance.financial` | `EligibilityResponse.insurance.benefitBalance.financial` | `financial` |  | Benefit Summary | 0..* | BackboneElement |  |  |
| `EligibilityResponse.insurance.benefitBalance.financial.allowed[x]` | `EligibilityResponse.insurance.benefitBalance.financial.allowed[x]` | `allowed[x]` |  | Benefits allowed | 0..1 | Money, string, unsignedInt |  |  |
| `EligibilityResponse.insurance.benefitBalance.financial.extension` | `EligibilityResponse.insurance.benefitBalance.financial.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `EligibilityResponse.insurance.benefitBalance.financial.id` | `EligibilityResponse.insurance.benefitBalance.financial.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `EligibilityResponse.insurance.benefitBalance.financial.modifierExtension` | `EligibilityResponse.insurance.benefitBalance.financial.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `EligibilityResponse.insurance.benefitBalance.financial.type` | `EligibilityResponse.insurance.benefitBalance.financial.type` | `type` |  | Deductable, visits, benefit amount | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/benefit-type` |
| `EligibilityResponse.insurance.benefitBalance.financial.used[x]` | `EligibilityResponse.insurance.benefitBalance.financial.used[x]` | `used[x]` |  | Benefits used | 0..1 | Money, unsignedInt |  |  |
| `EligibilityResponse.insurance.benefitBalance.id` | `EligibilityResponse.insurance.benefitBalance.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `EligibilityResponse.insurance.benefitBalance.modifierExtension` | `EligibilityResponse.insurance.benefitBalance.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `EligibilityResponse.insurance.benefitBalance.name` | `EligibilityResponse.insurance.benefitBalance.name` | `name` |  | Short name for the benefit | 0..1 | string |  |  |
| `EligibilityResponse.insurance.benefitBalance.network` | `EligibilityResponse.insurance.benefitBalance.network` | `network` |  | In or out of network | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/benefit-network` |
| `EligibilityResponse.insurance.benefitBalance.subCategory` | `EligibilityResponse.insurance.benefitBalance.subCategory` | `subCategory` |  | Detailed services covered within the type | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/benefit-subcategory` |
| `EligibilityResponse.insurance.benefitBalance.term` | `EligibilityResponse.insurance.benefitBalance.term` | `term` |  | Annual or lifetime | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/benefit-term` |
| `EligibilityResponse.insurance.benefitBalance.unit` | `EligibilityResponse.insurance.benefitBalance.unit` | `unit` |  | Individual or family | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/benefit-unit` |
| `EligibilityResponse.insurance.contract` | `EligibilityResponse.insurance.contract` | `contract` |  | Contract details | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Contract) |  |  |
| `EligibilityResponse.insurance.coverage` | `EligibilityResponse.insurance.coverage` | `coverage` |  | Updated Coverage details | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Coverage) |  |  |
| `EligibilityResponse.insurance.extension` | `EligibilityResponse.insurance.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `EligibilityResponse.insurance.id` | `EligibilityResponse.insurance.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `EligibilityResponse.insurance.modifierExtension` | `EligibilityResponse.insurance.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `EligibilityResponse.insurer` | `EligibilityResponse.insurer` | `insurer` |  | Insurer issuing the coverage | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `EligibilityResponse.language` | `EligibilityResponse.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `EligibilityResponse.meta` | `EligibilityResponse.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `EligibilityResponse.modifierExtension` | `EligibilityResponse.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `EligibilityResponse.outcome` | `EligibilityResponse.outcome` | `outcome` |  | complete \| error \| partial | 0..1 | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/remittance-outcome` |
| `EligibilityResponse.request` | `EligibilityResponse.request` | `request` |  | Eligibility reference | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/EligibilityRequest) |  |  |
| `EligibilityResponse.requestOrganization` | `EligibilityResponse.requestOrganization` | `requestOrganization` |  | Responsible organization | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `EligibilityResponse.requestProvider` | `EligibilityResponse.requestProvider` | `requestProvider` |  | Responsible practitioner | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `EligibilityResponse.status` | `EligibilityResponse.status` | `status` |  | active \| cancelled \| draft \| entered-in-error | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/fm-status` |
| `EligibilityResponse.text` | `EligibilityResponse.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [EligibilityResponse](/docs/R2/Resources/EligibilityResponse.md)<br/> `http://hl7.org/fhir/StructureDefinition/EligibilityResponse\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `95`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `262`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EligibilityResponse](/docs/R3/Resources/EligibilityResponse.md)<br/> `http://hl7.org/fhir/StructureDefinition/EligibilityResponse\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `445`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `640`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CoverageEligibilityResponse](/docs/R4/Resources/CoverageEligibilityResponse.md)<br/> `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityResponse\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1451`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1452`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CoverageEligibilityResponse](/docs/R4B/Resources/CoverageEligibilityResponse.md)<br/> `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityResponse\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `960`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1189`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CoverageEligibilityResponse](/docs/R5/Resources/CoverageEligibilityResponse.md)<br/> `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityResponse\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition EligibilityResponse from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 EligibilityResponse](/docs/R2/Resources/EligibilityResponse.md)| Relationship | R3 EligibilityResponse| Relationship | [R4 CoverageEligibilityResponse](/docs/R4/Resources/CoverageEligibilityResponse.md)| Relationship | [R4B CoverageEligibilityResponse](/docs/R4B/Resources/CoverageEligibilityResponse.md)| Relationship | [R5 CoverageEligibilityResponse](/docs/R5/Resources/CoverageEligibilityResponse.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `EligibilityResponse`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4970)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4971)| **`EligibilityResponse`**| | | | | | | 
| `EligibilityResponse.id`| _Equivalent_<br/>(4972/4973)| **`EligibilityResponse.id`**| | | | | | | 
| `EligibilityResponse.meta`| _Equivalent_<br/>(4974/4975)| **`EligibilityResponse.meta`**| | | | | | | 
| `EligibilityResponse.implicitRules`| _Equivalent_<br/>(4976/4977)| **`EligibilityResponse.implicitRules`**| | | | | | | 
| `EligibilityResponse.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4978)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4979)| **`EligibilityResponse.language`**| | | | | | | 
| `EligibilityResponse.text`| _Equivalent_<br/>(4980/4981)| **`EligibilityResponse.text`**| | | | | | | 
| `EligibilityResponse.contained`| _Equivalent_<br/>(4982/4983)| **`EligibilityResponse.contained`**| | | | | | | 
| `EligibilityResponse.extension`| _Equivalent_<br/>(4984/4985)| **`EligibilityResponse.extension`**| | | | | | | 
| `EligibilityResponse.modifierExtension`| _Equivalent_<br/>(4986/4987)| **`EligibilityResponse.modifierExtension`**| | | | | | | 
| `EligibilityResponse.identifier`| _Equivalent_<br/>(4988/4989)| **`EligibilityResponse.identifier`**| | | | | | | 
| | | **`EligibilityResponse.status`**| | | | | | | 
| `EligibilityResponse.created`| _Equivalent_<br/>(4996/4997)| **`EligibilityResponse.created`**| | | | | | | 
| `EligibilityResponse.requestProvider`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4998)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4999)| **`EligibilityResponse.requestProvider`**| →→→→ _RelatedTo_ →→→→ <br/>(1037)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1469)| `CoverageEligibilityResponse.requestor`| _Equivalent_<br/>(25286/25287)| `CoverageEligibilityResponse.requestor`| _Equivalent_<br/>(40278/40279)| `CoverageEligibilityResponse.requestor`
| `EligibilityResponse.requestOrganization`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(5000)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(5001)| **`EligibilityResponse.requestOrganization`**| →→→→ _RelatedTo_ →→→→ <br/>(1036)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1468)| `CoverageEligibilityResponse.requestor`| _Equivalent_<br/>(25286/25287)| `CoverageEligibilityResponse.requestor`| _Equivalent_<br/>(40278/40279)| `CoverageEligibilityResponse.requestor`
| `EligibilityResponse.request`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4990)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4991)| **`EligibilityResponse.request`**| | | | | | | 
| `EligibilityResponse.outcome`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4992)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4993)| **`EligibilityResponse.outcome`**| | | | | | | 
| `EligibilityResponse.disposition`| _Equivalent_<br/>(4994/4995)| **`EligibilityResponse.disposition`**| | | | | | | 
| `EligibilityResponse.organization`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(213)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(612)| **`EligibilityResponse.insurer`**| | | | | | | 
| | | **`EligibilityResponse.inforce`**| _Equivalent_<br/>(1021/1454)| `CoverageEligibilityResponse.insurance.inforce`| _Equivalent_<br/>(25306/25307)| `CoverageEligibilityResponse.insurance.inforce`| _Equivalent_<br/>(40298/40299)| `CoverageEligibilityResponse.insurance.inforce`
| | | **`EligibilityResponse.insurance`**| | | | | | | 
| | | **`EligibilityResponse.insurance.id`**| | | | | | | 
| | | **`EligibilityResponse.insurance.extension`**| | | | | | | 
| | | **`EligibilityResponse.insurance.modifierExtension`**| | | | | | | 
| | | **`EligibilityResponse.insurance.coverage`**| | | | | | | 
| | | **`EligibilityResponse.insurance.contract`**| | | | | | | 
| | | **`EligibilityResponse.insurance.benefitBalance`**| _Equivalent_<br/>(1022/1455)| `CoverageEligibilityResponse.insurance.item`| _Equivalent_<br/>(25310/25311)| `CoverageEligibilityResponse.insurance.item`| _Equivalent_<br/>(40302/40303)| `CoverageEligibilityResponse.insurance.item`
| | | **`EligibilityResponse.insurance.benefitBalance.id`**| | | | | | | 
| | | **`EligibilityResponse.insurance.benefitBalance.extension`**| | | | | | | 
| | | **`EligibilityResponse.insurance.benefitBalance.modifierExtension`**| | | | | | | 
| | | **`EligibilityResponse.insurance.benefitBalance.category`**| →→→→ _Equivalent_ →→→→ <br/>(1023)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1460)| `CoverageEligibilityResponse.insurance.item.category`| _Equivalent_<br/>(25318/25319)| `CoverageEligibilityResponse.insurance.item.category`| _Equivalent_<br/>(40310/40311)| `CoverageEligibilityResponse.insurance.item.category`
| | | **`EligibilityResponse.insurance.benefitBalance.subCategory`**| _Equivalent_<br/>(1032/1465)| `CoverageEligibilityResponse.insurance.item.productOrService`| _Equivalent_<br/>(25320/25321)| `CoverageEligibilityResponse.insurance.item.productOrService`| _Equivalent_<br/>(40312/40313)| `CoverageEligibilityResponse.insurance.item.productOrService`
| | | **`EligibilityResponse.insurance.benefitBalance.excluded`**| _Equivalent_<br/>(1025/1462)| `CoverageEligibilityResponse.insurance.item.excluded`| _Equivalent_<br/>(25326/25327)| `CoverageEligibilityResponse.insurance.item.excluded`| _Equivalent_<br/>(40318/40319)| `CoverageEligibilityResponse.insurance.item.excluded`
| | | **`EligibilityResponse.insurance.benefitBalance.name`**| _Equivalent_<br/>(1030/1463)| `CoverageEligibilityResponse.insurance.item.name`| _Equivalent_<br/>(25328/25329)| `CoverageEligibilityResponse.insurance.item.name`| _Equivalent_<br/>(40320/40321)| `CoverageEligibilityResponse.insurance.item.name`
| | | **`EligibilityResponse.insurance.benefitBalance.description`**| _Equivalent_<br/>(1024/1461)| `CoverageEligibilityResponse.insurance.item.description`| _Equivalent_<br/>(25330/25331)| `CoverageEligibilityResponse.insurance.item.description`| _Equivalent_<br/>(40322/40323)| `CoverageEligibilityResponse.insurance.item.description`
| | | **`EligibilityResponse.insurance.benefitBalance.network`**| _Equivalent_<br/>(1031/1464)| `CoverageEligibilityResponse.insurance.item.network`| _Equivalent_<br/>(25332/25333)| `CoverageEligibilityResponse.insurance.item.network`| _Equivalent_<br/>(40324/40325)| `CoverageEligibilityResponse.insurance.item.network`
| | | **`EligibilityResponse.insurance.benefitBalance.unit`**| _Equivalent_<br/>(1034/1467)| `CoverageEligibilityResponse.insurance.item.unit`| _Equivalent_<br/>(25334/25335)| `CoverageEligibilityResponse.insurance.item.unit`| _Equivalent_<br/>(40326/40327)| `CoverageEligibilityResponse.insurance.item.unit`
| | | **`EligibilityResponse.insurance.benefitBalance.term`**| _Equivalent_<br/>(1033/1466)| `CoverageEligibilityResponse.insurance.item.term`| _Equivalent_<br/>(25336/25337)| `CoverageEligibilityResponse.insurance.item.term`| _Equivalent_<br/>(40328/40329)| `CoverageEligibilityResponse.insurance.item.term`
| | | **`EligibilityResponse.insurance.benefitBalance.financial`**| _Equivalent_<br/>(1026/1456)| `CoverageEligibilityResponse.insurance.item.benefit`| _Equivalent_<br/>(25338/25339)| `CoverageEligibilityResponse.insurance.item.benefit`| _Equivalent_<br/>(40330/40331)| `CoverageEligibilityResponse.insurance.item.benefit`
| | | **`EligibilityResponse.insurance.benefitBalance.financial.id`**| | | | | | | 
| | | **`EligibilityResponse.insurance.benefitBalance.financial.extension`**| | | | | | | 
| | | **`EligibilityResponse.insurance.benefitBalance.financial.modifierExtension`**| | | | | | | 
| | | **`EligibilityResponse.insurance.benefitBalance.financial.type`**| _Equivalent_<br/>(1028/1458)| `CoverageEligibilityResponse.insurance.item.benefit.type`| _Equivalent_<br/>(25346/25347)| `CoverageEligibilityResponse.insurance.item.benefit.type`| _Equivalent_<br/>(40338/40339)| `CoverageEligibilityResponse.insurance.item.benefit.type`
| | | **`EligibilityResponse.insurance.benefitBalance.financial.allowed[x]`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1027)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1457)| `CoverageEligibilityResponse.insurance.item.benefit.allowed[x]`| _Equivalent_<br/>(25348/25349)| `CoverageEligibilityResponse.insurance.item.benefit.allowed[x]`| _Equivalent_<br/>(40340/40341)| `CoverageEligibilityResponse.insurance.item.benefit.allowed[x]`
| | | **`EligibilityResponse.insurance.benefitBalance.financial.used[x]`**| →→→→ _RelatedTo_ →→→→ <br/>(1029)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1459)| `CoverageEligibilityResponse.insurance.item.benefit.used[x]`| _Equivalent_<br/>(25350/25351)| `CoverageEligibilityResponse.insurance.item.benefit.used[x]`| _Equivalent_<br/>(40342/40343)| `CoverageEligibilityResponse.insurance.item.benefit.used[x]`
| | | **`EligibilityResponse.form`**| | | | | | | 
| | | **`EligibilityResponse.error`**| | | | | | | 
| | | **`EligibilityResponse.error.id`**| | | | | | | 
| | | **`EligibilityResponse.error.extension`**| | | | | | | 
| | | **`EligibilityResponse.error.modifierExtension`**| | | | | | | 
| | | **`EligibilityResponse.error.code`**| | | | | | | 
| *17 of 19 elements used* | | *50 of 50 elements used* | | *15 of 58 elements used* | | *15 of 58 elements used* | | *15 of 65 elements used* 

