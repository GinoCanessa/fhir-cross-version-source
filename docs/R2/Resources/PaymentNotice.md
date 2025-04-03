Comparison of 
Generated at Thursday, April 3, 2025 8:18:06 AM

### PaymentNotice

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | PaymentNotice |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/PaymentNotice` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for PaymentNotice Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `110` |
| Database Snapshot Count | `19` |
| Database Differential Count | `11` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `PaymentNotice` | `PaymentNotice` | `PaymentNotice` | PaymentNotice | PaymentNotice request | 0..* | PaymentNotice |  |  |
| `PaymentNotice.contained` | `PaymentNotice.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `PaymentNotice.created` | `PaymentNotice.created` | `created` |  | Creation date | 0..1 | dateTime |  |  |
| `PaymentNotice.extension` | `PaymentNotice.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `PaymentNotice.id` | `PaymentNotice.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `PaymentNotice.identifier` | `PaymentNotice.identifier` | `identifier` |  | Business Identifier | 0..* | Identifier |  |  |
| `PaymentNotice.implicitRules` | `PaymentNotice.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `PaymentNotice.language` | `PaymentNotice.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `PaymentNotice.meta` | `PaymentNotice.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `PaymentNotice.modifierExtension` | `PaymentNotice.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `PaymentNotice.organization` | `PaymentNotice.organization` | `organization` |  | Responsible organization | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `PaymentNotice.originalRuleset` | `PaymentNotice.originalRuleset` | `originalRuleset` |  | Original version | 0..1 | Coding | `Example` | `http://hl7.org/fhir/ValueSet/ruleset` |
| `PaymentNotice.paymentStatus` | `PaymentNotice.paymentStatus` | `paymentStatus` |  | Status of the payment | 1..1 | Coding | `Example` | `http://hl7.org/fhir/ValueSet/payment-status` |
| `PaymentNotice.provider` | `PaymentNotice.provider` | `provider` |  | Responsible practitioner | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `PaymentNotice.request` | `PaymentNotice.request` | `request` |  | Request reference | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `PaymentNotice.response` | `PaymentNotice.response` | `response` |  | Response reference | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `PaymentNotice.ruleset` | `PaymentNotice.ruleset` | `ruleset` |  | Resource version | 0..1 | Coding | `Example` | `http://hl7.org/fhir/ValueSet/ruleset` |
| `PaymentNotice.target` | `PaymentNotice.target` | `target` |  | Insurer or Regulatory body | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `PaymentNotice.text` | `PaymentNotice.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [PaymentNotice](/docs/R2/Resources/PaymentNotice.md)<br/> `http://hl7.org/fhir/StructureDefinition/PaymentNotice\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `140`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `306`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [PaymentNotice](/docs/R3/Resources/PaymentNotice.md)<br/> `http://hl7.org/fhir/StructureDefinition/PaymentNotice\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `495`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `690`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [PaymentNotice](/docs/R4/Resources/PaymentNotice.md)<br/> `http://hl7.org/fhir/StructureDefinition/PaymentNotice\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1573`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1574`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [PaymentNotice](/docs/R4B/Resources/PaymentNotice.md)<br/> `http://hl7.org/fhir/StructureDefinition/PaymentNotice\|4.3.0` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1022`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1251`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [PaymentNotice](/docs/R5/Resources/PaymentNotice.md)<br/> `http://hl7.org/fhir/StructureDefinition/PaymentNotice\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition PaymentNotice from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 PaymentNotice| Relationship | [R3 PaymentNotice](/docs/R3/Resources/PaymentNotice.md)| Relationship | [R4 PaymentNotice](/docs/R4/Resources/PaymentNotice.md)| Relationship | [R4B PaymentNotice](/docs/R4B/Resources/PaymentNotice.md)| Relationship | [R5 PaymentNotice](/docs/R5/Resources/PaymentNotice.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`PaymentNotice`**| _Equivalent_<br/>(7040/7041)| `PaymentNotice`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16887)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16888)| `PaymentNotice`| _Equivalent_<br/>(31372/31373)| `PaymentNotice`| _Equivalent_<br/>(46036/46037)| `PaymentNotice`
| **`PaymentNotice.id`**| _Equivalent_<br/>(7042/7043)| `PaymentNotice.id`| _Equivalent_<br/>(16889/16890)| `PaymentNotice.id`| _Equivalent_<br/>(31374/31375)| `PaymentNotice.id`| _Equivalent_<br/>(46038/46039)| `PaymentNotice.id`
| **`PaymentNotice.meta`**| _Equivalent_<br/>(7044/7045)| `PaymentNotice.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16891)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16892)| `PaymentNotice.meta`| _Equivalent_<br/>(31376/31377)| `PaymentNotice.meta`| _Equivalent_<br/>(46040/46041)| `PaymentNotice.meta`
| **`PaymentNotice.implicitRules`**| _Equivalent_<br/>(7046/7047)| `PaymentNotice.implicitRules`| _Equivalent_<br/>(16893/16894)| `PaymentNotice.implicitRules`| _Equivalent_<br/>(31378/31379)| `PaymentNotice.implicitRules`| _Equivalent_<br/>(46042/46043)| `PaymentNotice.implicitRules`
| **`PaymentNotice.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7048)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7049)| `PaymentNotice.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16895)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(16896)| `PaymentNotice.language`| _Equivalent_<br/>(31380/31381)| `PaymentNotice.language`| _Equivalent_<br/>(46044/46045)| `PaymentNotice.language`
| **`PaymentNotice.text`**| _Equivalent_<br/>(7050/7051)| `PaymentNotice.text`| _Equivalent_<br/>(16897/16898)| `PaymentNotice.text`| _Equivalent_<br/>(31382/31383)| `PaymentNotice.text`| _Equivalent_<br/>(46046/46047)| `PaymentNotice.text`
| **`PaymentNotice.contained`**| _Equivalent_<br/>(7052/7053)| `PaymentNotice.contained`| _Equivalent_<br/>(16899/16900)| `PaymentNotice.contained`| _Equivalent_<br/>(31384/31385)| `PaymentNotice.contained`| _Equivalent_<br/>(46048/46049)| `PaymentNotice.contained`
| **`PaymentNotice.extension`**| _Equivalent_<br/>(7054/7055)| `PaymentNotice.extension`| _Equivalent_<br/>(16901/16902)| `PaymentNotice.extension`| _Equivalent_<br/>(31386/31387)| `PaymentNotice.extension`| _Equivalent_<br/>(46050/46051)| `PaymentNotice.extension`
| **`PaymentNotice.modifierExtension`**| _Equivalent_<br/>(7056/7057)| `PaymentNotice.modifierExtension`| _Equivalent_<br/>(16903/16904)| `PaymentNotice.modifierExtension`| _Equivalent_<br/>(31388/31389)| `PaymentNotice.modifierExtension`| _Equivalent_<br/>(46052/46053)| `PaymentNotice.modifierExtension`
| **`PaymentNotice.identifier`**| _Equivalent_<br/>(7058/7059)| `PaymentNotice.identifier`| _Equivalent_<br/>(16905/16906)| `PaymentNotice.identifier`| _Equivalent_<br/>(31390/31391)| `PaymentNotice.identifier`| _Equivalent_<br/>(46054/46055)| `PaymentNotice.identifier`
| **`PaymentNotice.ruleset`**| | | | | | | | | 
| **`PaymentNotice.originalRuleset`**| | | | | | | | | 
| **`PaymentNotice.created`**| _Equivalent_<br/>(7060/7061)| `PaymentNotice.created`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16913)<hr/>←←←← _Equivalent_ ←←←← <br/>(16914)| `PaymentNotice.created`| _Equivalent_<br/>(31398/31399)| `PaymentNotice.created`| _Equivalent_<br/>(46062/46063)| `PaymentNotice.created`
| **`PaymentNotice.target`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7062)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7063)| `PaymentNotice.target`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1217)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1622)| `PaymentNotice.recipient`| _Equivalent_<br/>(31408/31409)| `PaymentNotice.recipient`| _Equivalent_<br/>(46070/46071)| `PaymentNotice.recipient`
| **`PaymentNotice.provider`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7064)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7065)| `PaymentNotice.provider`| →→→→ _RelatedTo_ →→→→ <br/>(16915)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16916)| `PaymentNotice.provider`| _Equivalent_<br/>(31400/31401)| `PaymentNotice.provider`| _Equivalent_<br/>(1917/2155)| `PaymentNotice.reporter`
| **`PaymentNotice.organization`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7066)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7067)| `PaymentNotice.organization`| →→→→ _RelatedTo_ →→→→ <br/>(1215)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1621)| `PaymentNotice.provider`| _Equivalent_<br/>(31400/31401)| `PaymentNotice.provider`| _Equivalent_<br/>(1917/2155)| `PaymentNotice.reporter`
| **`PaymentNotice.request`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7068)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7069)| `PaymentNotice.request`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16909)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16910)| `PaymentNotice.request`| _Equivalent_<br/>(31394/31395)| `PaymentNotice.request`| _Equivalent_<br/>(46058/46059)| `PaymentNotice.request`
| **`PaymentNotice.response`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7070)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7071)| `PaymentNotice.response`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(16911)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(16912)| `PaymentNotice.response`| _Equivalent_<br/>(31396/31397)| `PaymentNotice.response`| _Equivalent_<br/>(46060/46061)| `PaymentNotice.response`
| **`PaymentNotice.paymentStatus`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(7072)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7073)| `PaymentNotice.paymentStatus`| _Equivalent_<br/>(16917/16918)| `PaymentNotice.paymentStatus`| _Equivalent_<br/>(31412/31413)| `PaymentNotice.paymentStatus`| _Equivalent_<br/>(46074/46075)| `PaymentNotice.paymentStatus`
| *19 of 19 elements used* | | *17 of 19 elements used* <br/>remaining elements:<br/>`PaymentNotice.status`, `PaymentNotice.statusDate`| | *16 of 21 elements used* <br/>remaining elements:<br/>`PaymentNotice.amount`, `PaymentNotice.payee`, `PaymentNotice.payment`, `PaymentNotice.paymentDate`, `PaymentNotice.status`| | *16 of 21 elements used* <br/>remaining elements:<br/>`PaymentNotice.amount`, `PaymentNotice.payee`, `PaymentNotice.payment`, `PaymentNotice.paymentDate`, `PaymentNotice.status`| | *16 of 21 elements used* <br/>remaining elements:<br/>`PaymentNotice.amount`, `PaymentNotice.payee`, `PaymentNotice.payment`, `PaymentNotice.paymentDate`, `PaymentNotice.status`

