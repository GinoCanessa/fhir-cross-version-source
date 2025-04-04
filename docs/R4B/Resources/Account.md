Comparison of 
Generated at Friday, April 4, 2025 2:58:53 PM

### Account

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4b.core@4.3.0 |
| Stucture Name | Account |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Account` |
| Version | 4.3.0 |
| Description | A financial tool for tracking value accrued for a particular purpose.  In the healthcare field, used to track charges for a patient, cost centers, etc. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1638` |
| Database Snapshot Count | `31` |
| Database Differential Count | `17` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Account` | `Account` | `Account` | Account | Tracks balance, charges, for patient or cost center | 0..* | Account |  |  |
| `Account.contained` | `Account.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Account.coverage` | `Account.coverage` | `coverage` | Account.coverage | The party(s) that are responsible for covering the payment of this account, and what order should they be applied to the account | 0..* | BackboneElement |  |  |
| `Account.coverage.coverage` | `Account.coverage.coverage` | `coverage` | Account.coverage.coverage | The party(s), such as insurances, that may contribute to the payment of this account | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Coverage) |  |  |
| `Account.coverage.extension` | `Account.coverage.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Account.coverage.id` | `Account.coverage.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Account.coverage.modifierExtension` | `Account.coverage.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Account.coverage.priority` | `Account.coverage.priority` | `priority` | Account.coverage.priority | The priority of the coverage in the context of this account | 0..1 | positiveInt |  |  |
| `Account.description` | `Account.description` | `description` | Account.description | Explanation of purpose/use | 0..1 | string |  |  |
| `Account.extension` | `Account.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Account.guarantor` | `Account.guarantor` | `guarantor` | Account.guarantor | The parties ultimately responsible for balancing the Account | 0..* | BackboneElement |  |  |
| `Account.guarantor.extension` | `Account.guarantor.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Account.guarantor.id` | `Account.guarantor.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Account.guarantor.modifierExtension` | `Account.guarantor.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Account.guarantor.onHold` | `Account.guarantor.onHold` | `onHold` | Account.guarantor.onHold | Credit or other hold applied | 0..1 | boolean |  |  |
| `Account.guarantor.party` | `Account.guarantor.party` | `party` | Account.guarantor.party | Responsible entity | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Account.guarantor.period` | `Account.guarantor.period` | `period` | Account.guarantor.period | Guarantee account during | 0..1 | Period |  |  |
| `Account.id` | `Account.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Account.identifier` | `Account.identifier` | `identifier` | Account.identifier | Account number | 0..* | Identifier |  |  |
| `Account.implicitRules` | `Account.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Account.language` | `Account.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `Account.meta` | `Account.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Account.modifierExtension` | `Account.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Account.name` | `Account.name` | `name` | Account.name | Human-readable label | 0..1 | string |  |  |
| `Account.owner` | `Account.owner` | `owner` | Account.owner | Entity managing the Account | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Account.partOf` | `Account.partOf` | `partOf` | Account.partOf | Reference to a parent Account | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Account) |  |  |
| `Account.servicePeriod` | `Account.servicePeriod` | `servicePeriod` | Account.servicePeriod | Transaction window | 0..1 | Period |  |  |
| `Account.status` | `Account.status` | `status` | Account.status | active \| inactive \| entered-in-error \| on-hold \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/account-status|4.3.0` |
| `Account.subject` | `Account.subject` | `subject` | Account.subject | The entity that caused the expenses | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/HealthcareService), Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `Account.text` | `Account.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Account.type` | `Account.type` | `type` | Account.type | E.g. patient, expense, depreciation | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/account-type` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Account](/docs/R2/Resources/Account.md)<br/> `http://hl7.org/fhir/StructureDefinition/Account\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `72`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `238`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Account](/docs/R3/Resources/Account.md)<br/> `http://hl7.org/fhir/StructureDefinition/Account\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `415`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `611`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Account](/docs/R4/Resources/Account.md)<br/> `http://hl7.org/fhir/StructureDefinition/Account\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1387`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1388`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Account](/docs/R4B/Resources/Account.md)<br/> `http://hl7.org/fhir/StructureDefinition/Account\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `928`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1157`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Account](/docs/R5/Resources/Account.md)<br/> `http://hl7.org/fhir/StructureDefinition/Account\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Account from hl7.fhir.r4b.core@4.3.0 (R4B, key 4).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Account](/docs/R2/Resources/Account.md)| Relationship | [R3 Account](/docs/R3/Resources/Account.md)| Relationship | [R4 Account](/docs/R4/Resources/Account.md)| Relationship | R4B Account| Relationship | [R5 Account](/docs/R5/Resources/Account.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Account`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(2895)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2896)| `Account`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9890)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9891)| `Account`| _Equivalent_<br/>(21367/21368)| **`Account`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36431)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36432)| `Account`
| `Account.id`| _Equivalent_<br/>(2897/2898)| `Account.id`| _Equivalent_<br/>(9892/9893)| `Account.id`| _Equivalent_<br/>(21369/21370)| **`Account.id`**| _Equivalent_<br/>(36433/36434)| `Account.id`
| `Account.meta`| _Equivalent_<br/>(2899/2900)| `Account.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9894)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9895)| `Account.meta`| _Equivalent_<br/>(21371/21372)| **`Account.meta`**| _Equivalent_<br/>(36435/36436)| `Account.meta`
| `Account.implicitRules`| _Equivalent_<br/>(2901/2902)| `Account.implicitRules`| _Equivalent_<br/>(9896/9897)| `Account.implicitRules`| _Equivalent_<br/>(21373/21374)| **`Account.implicitRules`**| _Equivalent_<br/>(36437/36438)| `Account.implicitRules`
| `Account.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(2903)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2904)| `Account.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9898)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9899)| `Account.language`| _Equivalent_<br/>(21375/21376)| **`Account.language`**| _Equivalent_<br/>(36439/36440)| `Account.language`
| `Account.text`| _Equivalent_<br/>(2905/2906)| `Account.text`| _Equivalent_<br/>(9900/9901)| `Account.text`| _Equivalent_<br/>(21377/21378)| **`Account.text`**| _Equivalent_<br/>(36441/36442)| `Account.text`
| `Account.contained`| _Equivalent_<br/>(2907/2908)| `Account.contained`| _Equivalent_<br/>(9902/9903)| `Account.contained`| _Equivalent_<br/>(21379/21380)| **`Account.contained`**| _Equivalent_<br/>(36443/36444)| `Account.contained`
| `Account.extension`| _Equivalent_<br/>(2909/2910)| `Account.extension`| _Equivalent_<br/>(9904/9905)| `Account.extension`| _Equivalent_<br/>(21381/21382)| **`Account.extension`**| _Equivalent_<br/>(36445/36446)| `Account.extension`
| `Account.modifierExtension`| _Equivalent_<br/>(2911/2912)| `Account.modifierExtension`| _Equivalent_<br/>(9906/9907)| `Account.modifierExtension`| _Equivalent_<br/>(21383/21384)| **`Account.modifierExtension`**| _Equivalent_<br/>(36447/36448)| `Account.modifierExtension`
| `Account.identifier`| _Equivalent_<br/>(2913/2914)| `Account.identifier`| _Equivalent_<br/>(9908/9909)| `Account.identifier`| _Equivalent_<br/>(21385/21386)| **`Account.identifier`**| _Equivalent_<br/>(36449/36450)| `Account.identifier`
| `Account.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(2919)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2920)| `Account.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9910)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9911)| `Account.status`| _Equivalent_<br/>(21387/21388)| **`Account.status`**| _Equivalent_<br/>(36451/36452)| `Account.status`
| `Account.type`| _Equivalent_<br/>(2917/2918)| `Account.type`| _Equivalent_<br/>(9912/9913)| `Account.type`| _Equivalent_<br/>(21389/21390)| **`Account.type`**| _Equivalent_<br/>(36453/36454)| `Account.type`
| `Account.name`| _Equivalent_<br/>(2915/2916)| `Account.name`| _Equivalent_<br/>(9914/9915)| `Account.name`| _Equivalent_<br/>(21391/21392)| **`Account.name`**| _Equivalent_<br/>(36455/36456)| `Account.name`
| `Account.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(2923)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2924)| `Account.subject`| →→→→ _RelatedTo_ →→→→ <br/>(9916)<hr/>←←←← _RelatedTo_ ←←←← <br/>(9917)| `Account.subject`| _Equivalent_<br/>(21393/21394)| **`Account.subject`**| _Equivalent_<br/>(36457/36458)| `Account.subject`
| `Account.activePeriod`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1)<hr/>←←←← _Equivalent_ ←←←← <br/>(459)| `Account.period`| _Equivalent_<br/>(798/1335)| `Account.servicePeriod`| _Equivalent_<br/>(21395/21396)| **`Account.servicePeriod`**| _Equivalent_<br/>(36459/36460)| `Account.servicePeriod`
| | | `Account.coverage`| _Equivalent_<br/>(9918/9919)| `Account.coverage`| _Equivalent_<br/>(21397/21398)| **`Account.coverage`**| _Equivalent_<br/>(36461/36462)| `Account.coverage`
| | | `Account.coverage.id`| _Equivalent_<br/>(9920/9921)| `Account.coverage.id`| _Equivalent_<br/>(21399/21400)| **`Account.coverage.id`**| _Equivalent_<br/>(36463/36464)| `Account.coverage.id`
| | | `Account.coverage.extension`| _Equivalent_<br/>(9922/9923)| `Account.coverage.extension`| _Equivalent_<br/>(21401/21402)| **`Account.coverage.extension`**| _Equivalent_<br/>(36465/36466)| `Account.coverage.extension`
| | | `Account.coverage.modifierExtension`| _Equivalent_<br/>(9924/9925)| `Account.coverage.modifierExtension`| _Equivalent_<br/>(21403/21404)| **`Account.coverage.modifierExtension`**| _Equivalent_<br/>(36467/36468)| `Account.coverage.modifierExtension`
| | | `Account.coverage.coverage`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9926)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9927)| `Account.coverage.coverage`| _Equivalent_<br/>(21405/21406)| **`Account.coverage.coverage`**| _Equivalent_<br/>(36469/36470)| `Account.coverage.coverage`
| | | `Account.coverage.priority`| _Equivalent_<br/>(9928/9929)| `Account.coverage.priority`| _Equivalent_<br/>(21407/21408)| **`Account.coverage.priority`**| _Equivalent_<br/>(36471/36472)| `Account.coverage.priority`
| `Account.owner`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(2925)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2926)| `Account.owner`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9930)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9931)| `Account.owner`| _Equivalent_<br/>(21409/21410)| **`Account.owner`**| _Equivalent_<br/>(36473/36474)| `Account.owner`
| `Account.description`| _Equivalent_<br/>(2927/2928)| `Account.description`| _Equivalent_<br/>(9932/9933)| `Account.description`| _Equivalent_<br/>(21411/21412)| **`Account.description`**| _Equivalent_<br/>(36475/36476)| `Account.description`
| | | `Account.guarantor`| _Equivalent_<br/>(9934/9935)| `Account.guarantor`| _Equivalent_<br/>(21413/21414)| **`Account.guarantor`**| _Equivalent_<br/>(36477/36478)| `Account.guarantor`
| | | `Account.guarantor.id`| _Equivalent_<br/>(9936/9937)| `Account.guarantor.id`| _Equivalent_<br/>(21415/21416)| **`Account.guarantor.id`**| _Equivalent_<br/>(36479/36480)| `Account.guarantor.id`
| | | `Account.guarantor.extension`| _Equivalent_<br/>(9938/9939)| `Account.guarantor.extension`| _Equivalent_<br/>(21417/21418)| **`Account.guarantor.extension`**| _Equivalent_<br/>(36481/36482)| `Account.guarantor.extension`
| | | `Account.guarantor.modifierExtension`| _Equivalent_<br/>(9940/9941)| `Account.guarantor.modifierExtension`| _Equivalent_<br/>(21419/21420)| **`Account.guarantor.modifierExtension`**| _Equivalent_<br/>(36483/36484)| `Account.guarantor.modifierExtension`
| | | `Account.guarantor.party`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9942)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9943)| `Account.guarantor.party`| _Equivalent_<br/>(21421/21422)| **`Account.guarantor.party`**| _Equivalent_<br/>(36485/36486)| `Account.guarantor.party`
| | | `Account.guarantor.onHold`| _Equivalent_<br/>(9944/9945)| `Account.guarantor.onHold`| _Equivalent_<br/>(21423/21424)| **`Account.guarantor.onHold`**| _Equivalent_<br/>(36487/36488)| `Account.guarantor.onHold`
| | | `Account.guarantor.period`| _Equivalent_<br/>(9946/9947)| `Account.guarantor.period`| _Equivalent_<br/>(21425/21426)| **`Account.guarantor.period`**| _Equivalent_<br/>(36489/36490)| `Account.guarantor.period`
| | | | | `Account.partOf`| _Equivalent_<br/>(21427/21428)| **`Account.partOf`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1714)<hr/>←←←← _Equivalent_ ←←←← <br/>(1958)| `Account.relatedAccount.account`
| *17 of 20 elements used* <br/>remaining elements:<br/>`Account.balance`, `Account.coveragePeriod`, `Account.currency`| | *30 of 32 elements used* <br/>remaining elements:<br/>`Account.active`, `Account.balance`| | *31 of 31 elements used* | | *31 of 31 elements used* | | *31 of 67 elements used* <br/>remaining elements:<br/>`Account.balance`, `Account.balance.aggregate`, `Account.balance.amount`, `Account.balance.estimate`, `Account.balance.extension`, `Account.balance.id`, `Account.balance.modifierExtension`, `Account.balance.term`, `Account.billingStatus`, `Account.calculatedAt`, `Account.currency`, `Account.diagnosis`, `Account.diagnosis.condition`, `Account.diagnosis.dateOfDiagnosis`, `Account.diagnosis.extension`, `Account.diagnosis.id`, `Account.diagnosis.modifierExtension`, `Account.diagnosis.onAdmission`, `Account.diagnosis.packageCode`, `Account.diagnosis.sequence`, `Account.diagnosis.type`, `Account.procedure`, `Account.procedure.code`, `Account.procedure.dateOfService`, `Account.procedure.device`, `Account.procedure.extension`, `Account.procedure.id`, `Account.procedure.modifierExtension`, `Account.procedure.packageCode`, `Account.procedure.sequence`, `Account.procedure.type`, `Account.relatedAccount`, `Account.relatedAccount.extension`, `Account.relatedAccount.id`, `Account.relatedAccount.modifierExtension`, `Account.relatedAccount.relationship`

