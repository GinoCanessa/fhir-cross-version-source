Comparison of 
Generated at Thursday, April 3, 2025 8:18:38 AM

### CoverageEligibilityRequest

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | CoverageEligibilityRequest |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityRequest` |
| Version | 5.0.0 |
| Description | The CoverageEligibilityRequest provides patient and insurance coverage information to an insurer for them to respond, in the form of an CoverageEligibilityResponse, with information regarding whether the stated coverage is valid and in-force and optionally to provide the insurance details of the policy. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2285` |
| Database Snapshot Count | `58` |
| Database Differential Count | `35` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `CoverageEligibilityRequest` | `CoverageEligibilityRequest` | `CoverageEligibilityRequest` | CoverageEligibilityRequest | CoverageEligibilityRequest resource | 0..* | CoverageEligibilityRequest |  |  |
| `CoverageEligibilityRequest.contained` | `CoverageEligibilityRequest.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `CoverageEligibilityRequest.created` | `CoverageEligibilityRequest.created` | `created` | CoverageEligibilityRequest.created | Creation date | 1..1 | dateTime |  |  |
| `CoverageEligibilityRequest.enterer` | `CoverageEligibilityRequest.enterer` | `enterer` | CoverageEligibilityRequest.enterer | Author | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `CoverageEligibilityRequest.event` | `CoverageEligibilityRequest.event` | `event` | CoverageEligibilityRequest.event | Event information | 0..* | BackboneElement |  |  |
| `CoverageEligibilityRequest.event.extension` | `CoverageEligibilityRequest.event.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `CoverageEligibilityRequest.event.id` | `CoverageEligibilityRequest.event.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `CoverageEligibilityRequest.event.modifierExtension` | `CoverageEligibilityRequest.event.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `CoverageEligibilityRequest.event.type` | `CoverageEligibilityRequest.event.type` | `type` | CoverageEligibilityRequest.event.type | Specific event | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/datestype` |
| `CoverageEligibilityRequest.event.when[x]` | `CoverageEligibilityRequest.event.when[x]` | `when[x]` | CoverageEligibilityRequest.event.when[x] | Occurance date or period | 1..1 | dateTime, Period |  |  |
| `CoverageEligibilityRequest.extension` | `CoverageEligibilityRequest.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `CoverageEligibilityRequest.facility` | `CoverageEligibilityRequest.facility` | `facility` | CoverageEligibilityRequest.facility | Servicing facility | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `CoverageEligibilityRequest.id` | `CoverageEligibilityRequest.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `CoverageEligibilityRequest.identifier` | `CoverageEligibilityRequest.identifier` | `identifier` | CoverageEligibilityRequest.identifier | Business Identifier for coverage eligiblity request | 0..* | Identifier |  |  |
| `CoverageEligibilityRequest.implicitRules` | `CoverageEligibilityRequest.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `CoverageEligibilityRequest.insurance` | `CoverageEligibilityRequest.insurance` | `insurance` | CoverageEligibilityRequest.insurance | Patient insurance information | 0..* | BackboneElement |  |  |
| `CoverageEligibilityRequest.insurance.businessArrangement` | `CoverageEligibilityRequest.insurance.businessArrangement` | `businessArrangement` | CoverageEligibilityRequest.insurance.businessArrangement | Additional provider contract number | 0..1 | string |  |  |
| `CoverageEligibilityRequest.insurance.coverage` | `CoverageEligibilityRequest.insurance.coverage` | `coverage` | CoverageEligibilityRequest.insurance.coverage | Insurance information | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Coverage) |  |  |
| `CoverageEligibilityRequest.insurance.extension` | `CoverageEligibilityRequest.insurance.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `CoverageEligibilityRequest.insurance.focal` | `CoverageEligibilityRequest.insurance.focal` | `focal` | CoverageEligibilityRequest.insurance.focal | Applicable coverage | 0..1 | boolean |  |  |
| `CoverageEligibilityRequest.insurance.id` | `CoverageEligibilityRequest.insurance.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `CoverageEligibilityRequest.insurance.modifierExtension` | `CoverageEligibilityRequest.insurance.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `CoverageEligibilityRequest.insurer` | `CoverageEligibilityRequest.insurer` | `insurer` | CoverageEligibilityRequest.insurer | Coverage issuer | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `CoverageEligibilityRequest.item` | `CoverageEligibilityRequest.item` | `item` | CoverageEligibilityRequest.item | Item to be evaluated for eligibiity | 0..* | BackboneElement |  |  |
| `CoverageEligibilityRequest.item.category` | `CoverageEligibilityRequest.item.category` | `category` | CoverageEligibilityRequest.item.category | Benefit classification | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/ex-benefitcategory` |
| `CoverageEligibilityRequest.item.detail` | `CoverageEligibilityRequest.item.detail` | `detail` | CoverageEligibilityRequest.item.detail | Product or service details | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `CoverageEligibilityRequest.item.diagnosis` | `CoverageEligibilityRequest.item.diagnosis` | `diagnosis` | CoverageEligibilityRequest.item.diagnosis | Applicable diagnosis | 0..* | BackboneElement |  |  |
| `CoverageEligibilityRequest.item.diagnosis.diagnosis[x]` | `CoverageEligibilityRequest.item.diagnosis.diagnosis[x]` | `diagnosis[x]` | CoverageEligibilityRequest.item.diagnosis.diagnosis[x] | Nature of illness or problem | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Condition) | `Example` | `http://hl7.org/fhir/ValueSet/icd-10` |
| `CoverageEligibilityRequest.item.diagnosis.extension` | `CoverageEligibilityRequest.item.diagnosis.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `CoverageEligibilityRequest.item.diagnosis.id` | `CoverageEligibilityRequest.item.diagnosis.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `CoverageEligibilityRequest.item.diagnosis.modifierExtension` | `CoverageEligibilityRequest.item.diagnosis.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `CoverageEligibilityRequest.item.extension` | `CoverageEligibilityRequest.item.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `CoverageEligibilityRequest.item.facility` | `CoverageEligibilityRequest.item.facility` | `facility` | CoverageEligibilityRequest.item.facility | Servicing facility | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `CoverageEligibilityRequest.item.id` | `CoverageEligibilityRequest.item.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `CoverageEligibilityRequest.item.modifier` | `CoverageEligibilityRequest.item.modifier` | `modifier` | CoverageEligibilityRequest.item.modifier | Product or service billing modifiers | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/claim-modifiers` |
| `CoverageEligibilityRequest.item.modifierExtension` | `CoverageEligibilityRequest.item.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `CoverageEligibilityRequest.item.productOrService` | `CoverageEligibilityRequest.item.productOrService` | `productOrService` | CoverageEligibilityRequest.item.productOrService | Billing, service, product, or drug code | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/service-uscls` |
| `CoverageEligibilityRequest.item.provider` | `CoverageEligibilityRequest.item.provider` | `provider` | CoverageEligibilityRequest.item.provider | Perfoming practitioner | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `CoverageEligibilityRequest.item.quantity` | `CoverageEligibilityRequest.item.quantity` | `quantity` | CoverageEligibilityRequest.item.quantity | Count of products or services | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `CoverageEligibilityRequest.item.supportingInfoSequence` | `CoverageEligibilityRequest.item.supportingInfoSequence` | `supportingInfoSequence` | CoverageEligibilityRequest.item.supportingInfoSequence | Applicable exception or supporting information | 0..* | positiveInt |  |  |
| `CoverageEligibilityRequest.item.unitPrice` | `CoverageEligibilityRequest.item.unitPrice` | `unitPrice` | CoverageEligibilityRequest.item.unitPrice | Fee, charge or cost per item | 0..1 | Money |  |  |
| `CoverageEligibilityRequest.language` | `CoverageEligibilityRequest.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `CoverageEligibilityRequest.meta` | `CoverageEligibilityRequest.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `CoverageEligibilityRequest.modifierExtension` | `CoverageEligibilityRequest.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `CoverageEligibilityRequest.patient` | `CoverageEligibilityRequest.patient` | `patient` | CoverageEligibilityRequest.patient | Intended recipient of products and services | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `CoverageEligibilityRequest.priority` | `CoverageEligibilityRequest.priority` | `priority` | CoverageEligibilityRequest.priority | Desired processing priority | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/process-priority` |
| `CoverageEligibilityRequest.provider` | `CoverageEligibilityRequest.provider` | `provider` | CoverageEligibilityRequest.provider | Party responsible for the request | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `CoverageEligibilityRequest.purpose` | `CoverageEligibilityRequest.purpose` | `purpose` | CoverageEligibilityRequest.purpose | auth-requirements \| benefits \| discovery \| validation | 1..* | code | `Required` | `http://hl7.org/fhir/ValueSet/eligibilityrequest-purpose|5.0.0` |
| `CoverageEligibilityRequest.serviced[x]` | `CoverageEligibilityRequest.serviced[x]` | `serviced[x]` | CoverageEligibilityRequest.serviced[x] | Estimated date or dates of service | 0..1 | date, Period |  |  |
| `CoverageEligibilityRequest.status` | `CoverageEligibilityRequest.status` | `status` | CoverageEligibilityRequest.status | active \| cancelled \| draft \| entered-in-error | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/fm-status|5.0.0` |
| `CoverageEligibilityRequest.supportingInfo` | `CoverageEligibilityRequest.supportingInfo` | `supportingInfo` | CoverageEligibilityRequest.supportingInfo | Supporting information | 0..* | BackboneElement |  |  |
| `CoverageEligibilityRequest.supportingInfo.appliesToAll` | `CoverageEligibilityRequest.supportingInfo.appliesToAll` | `appliesToAll` | CoverageEligibilityRequest.supportingInfo.appliesToAll | Applies to all items | 0..1 | boolean |  |  |
| `CoverageEligibilityRequest.supportingInfo.extension` | `CoverageEligibilityRequest.supportingInfo.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `CoverageEligibilityRequest.supportingInfo.id` | `CoverageEligibilityRequest.supportingInfo.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `CoverageEligibilityRequest.supportingInfo.information` | `CoverageEligibilityRequest.supportingInfo.information` | `information` | CoverageEligibilityRequest.supportingInfo.information | Data to be provided | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `CoverageEligibilityRequest.supportingInfo.modifierExtension` | `CoverageEligibilityRequest.supportingInfo.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `CoverageEligibilityRequest.supportingInfo.sequence` | `CoverageEligibilityRequest.supportingInfo.sequence` | `sequence` | CoverageEligibilityRequest.supportingInfo.sequence | Information instance identifier | 1..1 | positiveInt |  |  |
| `CoverageEligibilityRequest.text` | `CoverageEligibilityRequest.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [EligibilityRequest](/docs/R2/Resources/EligibilityRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/EligibilityRequest\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `94`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `261`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [EligibilityRequest](/docs/R3/Resources/EligibilityRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/EligibilityRequest\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `444`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `639`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CoverageEligibilityRequest](/docs/R4/Resources/CoverageEligibilityRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityRequest\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1449`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1450`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CoverageEligibilityRequest](/docs/R4B/Resources/CoverageEligibilityRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityRequest\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `959`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1188`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [CoverageEligibilityRequest](/docs/R5/Resources/CoverageEligibilityRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/CoverageEligibilityRequest\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition CoverageEligibilityRequest from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 EligibilityRequest](/docs/R2/Resources/EligibilityRequest.md)| Relationship | [R3 EligibilityRequest](/docs/R3/Resources/EligibilityRequest.md)| Relationship | [R4 CoverageEligibilityRequest](/docs/R4/Resources/CoverageEligibilityRequest.md)| Relationship | [R4B CoverageEligibilityRequest](/docs/R4B/Resources/CoverageEligibilityRequest.md)| Relationship | R5 CoverageEligibilityRequest
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `CoverageEligibilityRequest`| _Equivalent_<br/>(25109/25110)| `CoverageEligibilityRequest`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(40144)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40145)| **`CoverageEligibilityRequest`**
| | | | | `CoverageEligibilityRequest.id`| _Equivalent_<br/>(25111/25112)| `CoverageEligibilityRequest.id`| _Equivalent_<br/>(40146/40147)| **`CoverageEligibilityRequest.id`**
| | | | | `CoverageEligibilityRequest.meta`| _Equivalent_<br/>(25113/25114)| `CoverageEligibilityRequest.meta`| _Equivalent_<br/>(40148/40149)| **`CoverageEligibilityRequest.meta`**
| | | | | `CoverageEligibilityRequest.implicitRules`| _Equivalent_<br/>(25115/25116)| `CoverageEligibilityRequest.implicitRules`| _Equivalent_<br/>(40150/40151)| **`CoverageEligibilityRequest.implicitRules`**
| | | | | `CoverageEligibilityRequest.language`| _Equivalent_<br/>(25117/25118)| `CoverageEligibilityRequest.language`| _Equivalent_<br/>(40152/40153)| **`CoverageEligibilityRequest.language`**
| | | | | `CoverageEligibilityRequest.text`| _Equivalent_<br/>(25119/25120)| `CoverageEligibilityRequest.text`| _Equivalent_<br/>(40154/40155)| **`CoverageEligibilityRequest.text`**
| | | | | `CoverageEligibilityRequest.contained`| _Equivalent_<br/>(25121/25122)| `CoverageEligibilityRequest.contained`| _Equivalent_<br/>(40156/40157)| **`CoverageEligibilityRequest.contained`**
| | | | | `CoverageEligibilityRequest.extension`| _Equivalent_<br/>(25123/25124)| `CoverageEligibilityRequest.extension`| _Equivalent_<br/>(40158/40159)| **`CoverageEligibilityRequest.extension`**
| | | | | `CoverageEligibilityRequest.modifierExtension`| _Equivalent_<br/>(25125/25126)| `CoverageEligibilityRequest.modifierExtension`| _Equivalent_<br/>(40160/40161)| **`CoverageEligibilityRequest.modifierExtension`**
| | | | | `CoverageEligibilityRequest.identifier`| _Equivalent_<br/>(25127/25128)| `CoverageEligibilityRequest.identifier`| _Equivalent_<br/>(40162/40163)| **`CoverageEligibilityRequest.identifier`**
| | | | | `CoverageEligibilityRequest.status`| _Equivalent_<br/>(25129/25130)| `CoverageEligibilityRequest.status`| _Equivalent_<br/>(40164/40165)| **`CoverageEligibilityRequest.status`**
| | | | | `CoverageEligibilityRequest.priority`| _Equivalent_<br/>(25131/25132)| `CoverageEligibilityRequest.priority`| _Equivalent_<br/>(40166/40167)| **`CoverageEligibilityRequest.priority`**
| | | | | `CoverageEligibilityRequest.purpose`| _Equivalent_<br/>(25133/25134)| `CoverageEligibilityRequest.purpose`| _Equivalent_<br/>(40168/40169)| **`CoverageEligibilityRequest.purpose`**
| | | | | `CoverageEligibilityRequest.patient`| _Equivalent_<br/>(25135/25136)| `CoverageEligibilityRequest.patient`| _Equivalent_<br/>(40170/40171)| **`CoverageEligibilityRequest.patient`**
| | | | | | | | | **`CoverageEligibilityRequest.event`**
| | | | | | | | | **`CoverageEligibilityRequest.event.id`**
| | | | | | | | | **`CoverageEligibilityRequest.event.extension`**
| | | | | | | | | **`CoverageEligibilityRequest.event.modifierExtension`**
| | | | | | | | | **`CoverageEligibilityRequest.event.type`**
| | | | | | | | | **`CoverageEligibilityRequest.event.when[x]`**
| | | | | `CoverageEligibilityRequest.serviced[x]`| _Equivalent_<br/>(25137/25138)| `CoverageEligibilityRequest.serviced[x]`| _Equivalent_<br/>(40172/40173)| **`CoverageEligibilityRequest.serviced[x]`**
| | | | | `CoverageEligibilityRequest.created`| _Equivalent_<br/>(25139/25140)| `CoverageEligibilityRequest.created`| _Equivalent_<br/>(40174/40175)| **`CoverageEligibilityRequest.created`**
| | | | | `CoverageEligibilityRequest.enterer`| _Equivalent_<br/>(25141/25142)| `CoverageEligibilityRequest.enterer`| _Equivalent_<br/>(40176/40177)| **`CoverageEligibilityRequest.enterer`**
| `EligibilityRequest.organization`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4968)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4969)| `EligibilityRequest.organization`| →→→→ _RelatedTo_ →→→→ <br/>(1020)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1453)| `CoverageEligibilityRequest.provider`| _Equivalent_<br/>(25143/25144)| `CoverageEligibilityRequest.provider`| _Equivalent_<br/>(40178/40179)| **`CoverageEligibilityRequest.provider`**
| | | | | `CoverageEligibilityRequest.insurer`| _Equivalent_<br/>(25145/25146)| `CoverageEligibilityRequest.insurer`| _Equivalent_<br/>(40180/40181)| **`CoverageEligibilityRequest.insurer`**
| | | | | `CoverageEligibilityRequest.facility`| _Equivalent_<br/>(25147/25148)| `CoverageEligibilityRequest.facility`| _Equivalent_<br/>(40182/40183)| **`CoverageEligibilityRequest.facility`**
| | | | | `CoverageEligibilityRequest.supportingInfo`| _Equivalent_<br/>(25149/25150)| `CoverageEligibilityRequest.supportingInfo`| _Equivalent_<br/>(40184/40185)| **`CoverageEligibilityRequest.supportingInfo`**
| | | | | `CoverageEligibilityRequest.supportingInfo.id`| _Equivalent_<br/>(25151/25152)| `CoverageEligibilityRequest.supportingInfo.id`| _Equivalent_<br/>(40186/40187)| **`CoverageEligibilityRequest.supportingInfo.id`**
| | | | | `CoverageEligibilityRequest.supportingInfo.extension`| _Equivalent_<br/>(25153/25154)| `CoverageEligibilityRequest.supportingInfo.extension`| _Equivalent_<br/>(40188/40189)| **`CoverageEligibilityRequest.supportingInfo.extension`**
| | | | | `CoverageEligibilityRequest.supportingInfo.modifierExtension`| _Equivalent_<br/>(25155/25156)| `CoverageEligibilityRequest.supportingInfo.modifierExtension`| _Equivalent_<br/>(40190/40191)| **`CoverageEligibilityRequest.supportingInfo.modifierExtension`**
| | | | | `CoverageEligibilityRequest.supportingInfo.sequence`| _Equivalent_<br/>(25157/25158)| `CoverageEligibilityRequest.supportingInfo.sequence`| _Equivalent_<br/>(40192/40193)| **`CoverageEligibilityRequest.supportingInfo.sequence`**
| | | | | `CoverageEligibilityRequest.supportingInfo.information`| _Equivalent_<br/>(25159/25160)| `CoverageEligibilityRequest.supportingInfo.information`| _Equivalent_<br/>(40194/40195)| **`CoverageEligibilityRequest.supportingInfo.information`**
| | | | | `CoverageEligibilityRequest.supportingInfo.appliesToAll`| _Equivalent_<br/>(25161/25162)| `CoverageEligibilityRequest.supportingInfo.appliesToAll`| _Equivalent_<br/>(40196/40197)| **`CoverageEligibilityRequest.supportingInfo.appliesToAll`**
| | | | | `CoverageEligibilityRequest.insurance`| _Equivalent_<br/>(25163/25164)| `CoverageEligibilityRequest.insurance`| _Equivalent_<br/>(40198/40199)| **`CoverageEligibilityRequest.insurance`**
| | | | | `CoverageEligibilityRequest.insurance.id`| _Equivalent_<br/>(25165/25166)| `CoverageEligibilityRequest.insurance.id`| _Equivalent_<br/>(40200/40201)| **`CoverageEligibilityRequest.insurance.id`**
| | | | | `CoverageEligibilityRequest.insurance.extension`| _Equivalent_<br/>(25167/25168)| `CoverageEligibilityRequest.insurance.extension`| _Equivalent_<br/>(40202/40203)| **`CoverageEligibilityRequest.insurance.extension`**
| | | | | `CoverageEligibilityRequest.insurance.modifierExtension`| _Equivalent_<br/>(25169/25170)| `CoverageEligibilityRequest.insurance.modifierExtension`| _Equivalent_<br/>(40204/40205)| **`CoverageEligibilityRequest.insurance.modifierExtension`**
| | | | | `CoverageEligibilityRequest.insurance.focal`| _Equivalent_<br/>(25171/25172)| `CoverageEligibilityRequest.insurance.focal`| _Equivalent_<br/>(40206/40207)| **`CoverageEligibilityRequest.insurance.focal`**
| | | `EligibilityRequest.coverage`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1019)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1452)| `CoverageEligibilityRequest.insurance.coverage`| _Equivalent_<br/>(25173/25174)| `CoverageEligibilityRequest.insurance.coverage`| _Equivalent_<br/>(40208/40209)| **`CoverageEligibilityRequest.insurance.coverage`**
| | | `EligibilityRequest.businessArrangement`| _Equivalent_<br/>(1018/1451)| `CoverageEligibilityRequest.insurance.businessArrangement`| _Equivalent_<br/>(25175/25176)| `CoverageEligibilityRequest.insurance.businessArrangement`| _Equivalent_<br/>(40210/40211)| **`CoverageEligibilityRequest.insurance.businessArrangement`**
| | | | | `CoverageEligibilityRequest.item`| _Equivalent_<br/>(25177/25178)| `CoverageEligibilityRequest.item`| _Equivalent_<br/>(40212/40213)| **`CoverageEligibilityRequest.item`**
| | | | | `CoverageEligibilityRequest.item.id`| _Equivalent_<br/>(25179/25180)| `CoverageEligibilityRequest.item.id`| _Equivalent_<br/>(40214/40215)| **`CoverageEligibilityRequest.item.id`**
| | | | | `CoverageEligibilityRequest.item.extension`| _Equivalent_<br/>(25181/25182)| `CoverageEligibilityRequest.item.extension`| _Equivalent_<br/>(40216/40217)| **`CoverageEligibilityRequest.item.extension`**
| | | | | `CoverageEligibilityRequest.item.modifierExtension`| _Equivalent_<br/>(25183/25184)| `CoverageEligibilityRequest.item.modifierExtension`| _Equivalent_<br/>(40218/40219)| **`CoverageEligibilityRequest.item.modifierExtension`**
| | | | | `CoverageEligibilityRequest.item.supportingInfoSequence`| _Equivalent_<br/>(25185/25186)| `CoverageEligibilityRequest.item.supportingInfoSequence`| _Equivalent_<br/>(40220/40221)| **`CoverageEligibilityRequest.item.supportingInfoSequence`**
| | | | | `CoverageEligibilityRequest.item.category`| _Equivalent_<br/>(25187/25188)| `CoverageEligibilityRequest.item.category`| _Equivalent_<br/>(40222/40223)| **`CoverageEligibilityRequest.item.category`**
| | | | | `CoverageEligibilityRequest.item.productOrService`| _Equivalent_<br/>(25189/25190)| `CoverageEligibilityRequest.item.productOrService`| _Equivalent_<br/>(40224/40225)| **`CoverageEligibilityRequest.item.productOrService`**
| | | | | `CoverageEligibilityRequest.item.modifier`| _Equivalent_<br/>(25191/25192)| `CoverageEligibilityRequest.item.modifier`| _Equivalent_<br/>(40226/40227)| **`CoverageEligibilityRequest.item.modifier`**
| | | | | `CoverageEligibilityRequest.item.provider`| _Equivalent_<br/>(25193/25194)| `CoverageEligibilityRequest.item.provider`| _Equivalent_<br/>(40228/40229)| **`CoverageEligibilityRequest.item.provider`**
| | | | | `CoverageEligibilityRequest.item.quantity`| _Equivalent_<br/>(25195/25196)| `CoverageEligibilityRequest.item.quantity`| _Equivalent_<br/>(40230/40231)| **`CoverageEligibilityRequest.item.quantity`**
| | | | | `CoverageEligibilityRequest.item.unitPrice`| _Equivalent_<br/>(25197/25198)| `CoverageEligibilityRequest.item.unitPrice`| _Equivalent_<br/>(40232/40233)| **`CoverageEligibilityRequest.item.unitPrice`**
| | | | | `CoverageEligibilityRequest.item.facility`| _Equivalent_<br/>(25199/25200)| `CoverageEligibilityRequest.item.facility`| _Equivalent_<br/>(40234/40235)| **`CoverageEligibilityRequest.item.facility`**
| | | | | `CoverageEligibilityRequest.item.diagnosis`| _Equivalent_<br/>(25201/25202)| `CoverageEligibilityRequest.item.diagnosis`| _Equivalent_<br/>(40236/40237)| **`CoverageEligibilityRequest.item.diagnosis`**
| | | | | `CoverageEligibilityRequest.item.diagnosis.id`| _Equivalent_<br/>(25203/25204)| `CoverageEligibilityRequest.item.diagnosis.id`| _Equivalent_<br/>(40238/40239)| **`CoverageEligibilityRequest.item.diagnosis.id`**
| | | | | `CoverageEligibilityRequest.item.diagnosis.extension`| _Equivalent_<br/>(25205/25206)| `CoverageEligibilityRequest.item.diagnosis.extension`| _Equivalent_<br/>(40240/40241)| **`CoverageEligibilityRequest.item.diagnosis.extension`**
| | | | | `CoverageEligibilityRequest.item.diagnosis.modifierExtension`| _Equivalent_<br/>(25207/25208)| `CoverageEligibilityRequest.item.diagnosis.modifierExtension`| _Equivalent_<br/>(40242/40243)| **`CoverageEligibilityRequest.item.diagnosis.modifierExtension`**
| | | | | `CoverageEligibilityRequest.item.diagnosis.diagnosis[x]`| _Equivalent_<br/>(25209/25210)| `CoverageEligibilityRequest.item.diagnosis.diagnosis[x]`| _Equivalent_<br/>(40244/40245)| **`CoverageEligibilityRequest.item.diagnosis.diagnosis[x]`**
| | | | | `CoverageEligibilityRequest.item.detail`| _Equivalent_<br/>(25211/25212)| `CoverageEligibilityRequest.item.detail`| _Equivalent_<br/>(40246/40247)| **`CoverageEligibilityRequest.item.detail`**
| *1 of 16 elements used* <br/>remaining elements:<br/>`EligibilityRequest`, `EligibilityRequest.contained`, `EligibilityRequest.created`, `EligibilityRequest.extension`, `EligibilityRequest.id`, `EligibilityRequest.identifier`, `EligibilityRequest.implicitRules`, `EligibilityRequest.language`, `EligibilityRequest.meta`, `EligibilityRequest.modifierExtension`, `EligibilityRequest.originalRuleset`, `EligibilityRequest.provider`, `EligibilityRequest.ruleset`, `EligibilityRequest.target`, `EligibilityRequest.text`| | *3 of 24 elements used* <br/>remaining elements:<br/>`EligibilityRequest`, `EligibilityRequest.benefitCategory`, `EligibilityRequest.benefitSubCategory`, `EligibilityRequest.contained`, `EligibilityRequest.created`, `EligibilityRequest.enterer`, `EligibilityRequest.extension`, `EligibilityRequest.facility`, `EligibilityRequest.id`, `EligibilityRequest.identifier`, `EligibilityRequest.implicitRules`, `EligibilityRequest.insurer`, `EligibilityRequest.language`, `EligibilityRequest.meta`, `EligibilityRequest.modifierExtension`, `EligibilityRequest.patient`, `EligibilityRequest.priority`, `EligibilityRequest.provider`, `EligibilityRequest.serviced[x]`, `EligibilityRequest.status`, `EligibilityRequest.text`| | *52 of 52 elements used* | | *52 of 52 elements used* | | *58 of 58 elements used* 

