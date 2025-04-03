Comparison of 
Generated at Thursday, April 3, 2025 8:18:06 AM

### Account

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | Account |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Account` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for Account Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `41` |
| Database Snapshot Count | `20` |
| Database Differential Count | `12` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Account` | `Account` | `Account` | Account |  | 0..* | Account |  |  |
| `Account.activePeriod` | `Account.activePeriod` | `activePeriod` |  | Valid from..to | 0..1 | Period |  |  |
| `Account.balance` | `Account.balance` | `balance` |  | How much is in account? | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/Money] |  |  |
| `Account.contained` | `Account.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Account.coveragePeriod` | `Account.coveragePeriod` | `coveragePeriod` |  | Transaction window | 0..1 | Period |  |  |
| `Account.currency` | `Account.currency` | `currency` |  | Base currency in which balance is tracked | 0..1 | Coding | `Example` | `http://www.iso.org/iso/home/standards/currency_codes` |
| `Account.description` | `Account.description` | `description` |  | Explanation of purpose/use | 0..1 | string |  |  |
| `Account.extension` | `Account.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Account.id` | `Account.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Account.identifier` | `Account.identifier` | `identifier` |  | Account number | 0..* | Identifier |  |  |
| `Account.implicitRules` | `Account.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Account.language` | `Account.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `Account.meta` | `Account.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Account.modifierExtension` | `Account.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Account.name` | `Account.name` | `name` |  | Human-readable label | 0..1 | string |  |  |
| `Account.owner` | `Account.owner` | `owner` |  | Who is responsible? | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Account.status` | `Account.status` | `status` |  | active \| inactive | 0..1 | code | `Preferred` | `http://hl7.org/fhir/ValueSet/account-status` |
| `Account.subject` | `Account.subject` | `subject` |  | What is account tied to? | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/HealthcareService), Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `Account.text` | `Account.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Account.type` | `Account.type` | `type` |  | E.g. patient, expense, depreciation | 0..1 | CodeableConcept | `Example` |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Account](/docs/R2/Resources/Account.md)<br/> `http://hl7.org/fhir/StructureDefinition/Account\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `72`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `238`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Account](/docs/R3/Resources/Account.md)<br/> `http://hl7.org/fhir/StructureDefinition/Account\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `415`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `611`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Account](/docs/R4/Resources/Account.md)<br/> `http://hl7.org/fhir/StructureDefinition/Account\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1387`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1388`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Account](/docs/R4B/Resources/Account.md)<br/> `http://hl7.org/fhir/StructureDefinition/Account\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `928`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1157`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Account](/docs/R5/Resources/Account.md)<br/> `http://hl7.org/fhir/StructureDefinition/Account\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Account from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Account| Relationship | [R3 Account](/docs/R3/Resources/Account.md)| Relationship | [R4 Account](/docs/R4/Resources/Account.md)| Relationship | [R4B Account](/docs/R4B/Resources/Account.md)| Relationship | [R5 Account](/docs/R5/Resources/Account.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Account`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(2895)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2896)| `Account`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(9890)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9891)| `Account`| _Equivalent_<br/>(21367/21368)| `Account`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36431)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36432)| `Account`
| **`Account.id`**| _Equivalent_<br/>(2897/2898)| `Account.id`| _Equivalent_<br/>(9892/9893)| `Account.id`| _Equivalent_<br/>(21369/21370)| `Account.id`| _Equivalent_<br/>(36433/36434)| `Account.id`
| **`Account.meta`**| _Equivalent_<br/>(2899/2900)| `Account.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9894)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9895)| `Account.meta`| _Equivalent_<br/>(21371/21372)| `Account.meta`| _Equivalent_<br/>(36435/36436)| `Account.meta`
| **`Account.implicitRules`**| _Equivalent_<br/>(2901/2902)| `Account.implicitRules`| _Equivalent_<br/>(9896/9897)| `Account.implicitRules`| _Equivalent_<br/>(21373/21374)| `Account.implicitRules`| _Equivalent_<br/>(36437/36438)| `Account.implicitRules`
| **`Account.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(2903)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2904)| `Account.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9898)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(9899)| `Account.language`| _Equivalent_<br/>(21375/21376)| `Account.language`| _Equivalent_<br/>(36439/36440)| `Account.language`
| **`Account.text`**| _Equivalent_<br/>(2905/2906)| `Account.text`| _Equivalent_<br/>(9900/9901)| `Account.text`| _Equivalent_<br/>(21377/21378)| `Account.text`| _Equivalent_<br/>(36441/36442)| `Account.text`
| **`Account.contained`**| _Equivalent_<br/>(2907/2908)| `Account.contained`| _Equivalent_<br/>(9902/9903)| `Account.contained`| _Equivalent_<br/>(21379/21380)| `Account.contained`| _Equivalent_<br/>(36443/36444)| `Account.contained`
| **`Account.extension`**| _Equivalent_<br/>(2909/2910)| `Account.extension`| _Equivalent_<br/>(9904/9905)| `Account.extension`| _Equivalent_<br/>(21381/21382)| `Account.extension`| _Equivalent_<br/>(36445/36446)| `Account.extension`
| **`Account.modifierExtension`**| _Equivalent_<br/>(2911/2912)| `Account.modifierExtension`| _Equivalent_<br/>(9906/9907)| `Account.modifierExtension`| _Equivalent_<br/>(21383/21384)| `Account.modifierExtension`| _Equivalent_<br/>(36447/36448)| `Account.modifierExtension`
| **`Account.identifier`**| _Equivalent_<br/>(2913/2914)| `Account.identifier`| _Equivalent_<br/>(9908/9909)| `Account.identifier`| _Equivalent_<br/>(21385/21386)| `Account.identifier`| _Equivalent_<br/>(36449/36450)| `Account.identifier`
| **`Account.name`**| _Equivalent_<br/>(2915/2916)| `Account.name`| _Equivalent_<br/>(9914/9915)| `Account.name`| _Equivalent_<br/>(21391/21392)| `Account.name`| _Equivalent_<br/>(36455/36456)| `Account.name`
| **`Account.type`**| _Equivalent_<br/>(2917/2918)| `Account.type`| _Equivalent_<br/>(9912/9913)| `Account.type`| _Equivalent_<br/>(21389/21390)| `Account.type`| _Equivalent_<br/>(36453/36454)| `Account.type`
| **`Account.status`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(2919)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(2920)| `Account.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9910)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9911)| `Account.status`| _Equivalent_<br/>(21387/21388)| `Account.status`| _Equivalent_<br/>(36451/36452)| `Account.status`
| **`Account.activePeriod`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(2)<hr/>←←←← _Equivalent_ ←←←← <br/>(460)| `Account.period`| _Equivalent_<br/>(798/1335)| `Account.servicePeriod`| _Equivalent_<br/>(21395/21396)| `Account.servicePeriod`| _Equivalent_<br/>(36459/36460)| `Account.servicePeriod`
| **`Account.activePeriod`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(2)<hr/>←←←← _Equivalent_ ←←←← <br/>(460)| `Account.active`| | | | | | | 
| **`Account.currency`**| | | | | | | | | 
| **`Account.balance`**| →→→→ _RelatedTo_ →→→→ <br/>(2921)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2922)| `Account.balance`| | | | | | | 
| **`Account.coveragePeriod`**| | | | | | | | | 
| **`Account.subject`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(2923)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2924)| `Account.subject`| →→→→ _RelatedTo_ →→→→ <br/>(9916)<hr/>←←←← _RelatedTo_ ←←←← <br/>(9917)| `Account.subject`| _Equivalent_<br/>(21393/21394)| `Account.subject`| _Equivalent_<br/>(36457/36458)| `Account.subject`
| **`Account.owner`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(2925)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2926)| `Account.owner`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9930)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9931)| `Account.owner`| _Equivalent_<br/>(21409/21410)| `Account.owner`| _Equivalent_<br/>(36473/36474)| `Account.owner`
| **`Account.description`**| _Equivalent_<br/>(2927/2928)| `Account.description`| _Equivalent_<br/>(9932/9933)| `Account.description`| _Equivalent_<br/>(21411/21412)| `Account.description`| _Equivalent_<br/>(36475/36476)| `Account.description`
| *20 of 20 elements used* | | *19 of 32 elements used* <br/>remaining elements:<br/>`Account.coverage`, `Account.coverage.coverage`, `Account.coverage.extension`, `Account.coverage.id`, `Account.coverage.modifierExtension`, `Account.coverage.priority`, `Account.guarantor`, `Account.guarantor.extension`, `Account.guarantor.id`, `Account.guarantor.modifierExtension`, `Account.guarantor.onHold`, `Account.guarantor.party`, `Account.guarantor.period`| | *17 of 31 elements used* <br/>remaining elements:<br/>`Account.coverage`, `Account.coverage.coverage`, `Account.coverage.extension`, `Account.coverage.id`, `Account.coverage.modifierExtension`, `Account.coverage.priority`, `Account.guarantor`, `Account.guarantor.extension`, `Account.guarantor.id`, `Account.guarantor.modifierExtension`, `Account.guarantor.onHold`, `Account.guarantor.party`, `Account.guarantor.period`, `Account.partOf`| | *17 of 31 elements used* <br/>remaining elements:<br/>`Account.coverage`, `Account.coverage.coverage`, `Account.coverage.extension`, `Account.coverage.id`, `Account.coverage.modifierExtension`, `Account.coverage.priority`, `Account.guarantor`, `Account.guarantor.extension`, `Account.guarantor.id`, `Account.guarantor.modifierExtension`, `Account.guarantor.onHold`, `Account.guarantor.party`, `Account.guarantor.period`, `Account.partOf`| | *17 of 67 elements used* <br/>remaining elements:<br/>`Account.balance`, `Account.balance.aggregate`, `Account.balance.amount`, `Account.balance.estimate`, `Account.balance.extension`, `Account.balance.id`, `Account.balance.modifierExtension`, `Account.balance.term`, `Account.billingStatus`, `Account.calculatedAt`, `Account.coverage`, `Account.coverage.coverage`, `Account.coverage.extension`, `Account.coverage.id`, `Account.coverage.modifierExtension`, `Account.coverage.priority`, `Account.currency`, `Account.diagnosis`, `Account.diagnosis.condition`, `Account.diagnosis.dateOfDiagnosis`, `Account.diagnosis.extension`, `Account.diagnosis.id`, `Account.diagnosis.modifierExtension`, `Account.diagnosis.onAdmission`, `Account.diagnosis.packageCode`, `Account.diagnosis.sequence`, `Account.diagnosis.type`, `Account.guarantor`, `Account.guarantor.extension`, `Account.guarantor.id`, `Account.guarantor.modifierExtension`, `Account.guarantor.onHold`, `Account.guarantor.party`, `Account.guarantor.period`, `Account.procedure`, `Account.procedure.code`, `Account.procedure.dateOfService`, `Account.procedure.device`, `Account.procedure.extension`, `Account.procedure.id`, `Account.procedure.modifierExtension`, `Account.procedure.packageCode`, `Account.procedure.sequence`, `Account.procedure.type`, `Account.relatedAccount`, `Account.relatedAccount.account`, `Account.relatedAccount.extension`, `Account.relatedAccount.id`, `Account.relatedAccount.modifierExtension`, `Account.relatedAccount.relationship`

