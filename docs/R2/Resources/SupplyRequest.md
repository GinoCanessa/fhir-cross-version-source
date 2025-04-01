Comparison of 
Generated at Tuesday, April 1, 2025 1:39:09 PM

### SupplyRequest

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | SupplyRequest |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/SupplyRequest` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for SupplyRequest Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `133` |
| Database Snapshot Count | `24` |
| Database Differential Count | `13` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `SupplyRequest` | `SupplyRequest` | `SupplyRequest` | SupplyRequest | Request for a medication, substance or device | 0..* | SupplyRequest |  |  |
| `SupplyRequest.contained` | `SupplyRequest.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `SupplyRequest.date` | `SupplyRequest.date` | `date` |  | When the request was made | 0..1 | dateTime |  |  |
| `SupplyRequest.extension` | `SupplyRequest.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `SupplyRequest.id` | `SupplyRequest.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `SupplyRequest.identifier` | `SupplyRequest.identifier` | `identifier` |  | Unique identifier | 0..1 | Identifier |  |  |
| `SupplyRequest.implicitRules` | `SupplyRequest.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `SupplyRequest.kind` | `SupplyRequest.kind` | `kind` |  | The kind of supply (central, non-stock, etc.) | 0..1 | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/supplyrequest-kind` |
| `SupplyRequest.language` | `SupplyRequest.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `SupplyRequest.meta` | `SupplyRequest.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `SupplyRequest.modifierExtension` | `SupplyRequest.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `SupplyRequest.orderedItem` | `SupplyRequest.orderedItem` | `orderedItem` |  | Medication, Substance, or Device requested to be supplied | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Medication), Reference(http://hl7.org/fhir/StructureDefinition/Substance) |  |  |
| `SupplyRequest.patient` | `SupplyRequest.patient` | `patient` |  | Patient for whom the item is supplied | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `SupplyRequest.reason[x]` | `SupplyRequest.reason[x]` | `reason[x]` |  | Why the supply item was requested | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Resource) | `Example` | `http://hl7.org/fhir/ValueSet/supplyrequest-reason` |
| `SupplyRequest.source` | `SupplyRequest.source` | `source` |  | Who initiated this order | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `SupplyRequest.status` | `SupplyRequest.status` | `status` |  | requested \| completed \| failed \| cancelled | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/supplyrequest-status` |
| `SupplyRequest.supplier` | `SupplyRequest.supplier` | `supplier` |  | Who is intended to fulfill the request | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `SupplyRequest.text` | `SupplyRequest.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `SupplyRequest.when` | `SupplyRequest.when` | `when` |  | When the request should be fulfilled | 0..1 | BackboneElement |  |  |
| `SupplyRequest.when.code` | `SupplyRequest.when.code` | `code` |  | Fulfilment code | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/supplyrequest-when` |
| `SupplyRequest.when.extension` | `SupplyRequest.when.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `SupplyRequest.when.id` | `SupplyRequest.when.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `SupplyRequest.when.modifierExtension` | `SupplyRequest.when.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `SupplyRequest.when.schedule` | `SupplyRequest.when.schedule` | `schedule` |  | Formal fulfillment schedule | 0..1 | Timing |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [SupplyRequest](/docs/R2/Resources/SupplyRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/SupplyRequest\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `162`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `329`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SupplyRequest](/docs/R3/Resources/SupplyRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/SupplyRequest\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `523`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `717`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SupplyRequest](/docs/R4/Resources/SupplyRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/SupplyRequest\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1631`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1632`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SupplyRequest](/docs/R4B/Resources/SupplyRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/SupplyRequest\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1052`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1281`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [SupplyRequest](/docs/R5/Resources/SupplyRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/SupplyRequest\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition SupplyRequest from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 SupplyRequest| Relationship | [R3 SupplyRequest](/docs/R3/Resources/SupplyRequest.md)| Relationship | [R4 SupplyRequest](/docs/R4/Resources/SupplyRequest.md)| Relationship | [R4B SupplyRequest](/docs/R4B/Resources/SupplyRequest.md)| Relationship | [R5 SupplyRequest](/docs/R5/Resources/SupplyRequest.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`SupplyRequest`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8107)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8108)| `SupplyRequest`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(19020)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19021)| `SupplyRequest`| _Equivalent_<br/>(33885/33886)| `SupplyRequest`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(48431)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(48432)| `SupplyRequest`
| **`SupplyRequest.id`**| _Equivalent_<br/>(8109/8110)| `SupplyRequest.id`| _Equivalent_<br/>(19022/19023)| `SupplyRequest.id`| _Equivalent_<br/>(33887/33888)| `SupplyRequest.id`| _Equivalent_<br/>(48433/48434)| `SupplyRequest.id`
| **`SupplyRequest.meta`**| _Equivalent_<br/>(8111/8112)| `SupplyRequest.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19024)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19025)| `SupplyRequest.meta`| _Equivalent_<br/>(33889/33890)| `SupplyRequest.meta`| _Equivalent_<br/>(48435/48436)| `SupplyRequest.meta`
| **`SupplyRequest.implicitRules`**| _Equivalent_<br/>(8113/8114)| `SupplyRequest.implicitRules`| _Equivalent_<br/>(19026/19027)| `SupplyRequest.implicitRules`| _Equivalent_<br/>(33891/33892)| `SupplyRequest.implicitRules`| _Equivalent_<br/>(48437/48438)| `SupplyRequest.implicitRules`
| **`SupplyRequest.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8115)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(8116)| `SupplyRequest.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19028)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(19029)| `SupplyRequest.language`| _Equivalent_<br/>(33893/33894)| `SupplyRequest.language`| _Equivalent_<br/>(48439/48440)| `SupplyRequest.language`
| **`SupplyRequest.text`**| _Equivalent_<br/>(8117/8118)| `SupplyRequest.text`| _Equivalent_<br/>(19030/19031)| `SupplyRequest.text`| _Equivalent_<br/>(33895/33896)| `SupplyRequest.text`| _Equivalent_<br/>(48441/48442)| `SupplyRequest.text`
| **`SupplyRequest.contained`**| _Equivalent_<br/>(8119/8120)| `SupplyRequest.contained`| _Equivalent_<br/>(19032/19033)| `SupplyRequest.contained`| _Equivalent_<br/>(33897/33898)| `SupplyRequest.contained`| _Equivalent_<br/>(48443/48444)| `SupplyRequest.contained`
| **`SupplyRequest.extension`**| →→→→ _Equivalent_ →→→→ <br/>(8121)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8122)| `SupplyRequest.extension`| _Equivalent_<br/>(19034/19035)| `SupplyRequest.extension`| _Equivalent_<br/>(33899/33900)| `SupplyRequest.extension`| _Equivalent_<br/>(48445/48446)| `SupplyRequest.extension`
| **`SupplyRequest.modifierExtension`**| _Equivalent_<br/>(8123/8124)| `SupplyRequest.modifierExtension`| _Equivalent_<br/>(19036/19037)| `SupplyRequest.modifierExtension`| _Equivalent_<br/>(33901/33902)| `SupplyRequest.modifierExtension`| _Equivalent_<br/>(48447/48448)| `SupplyRequest.modifierExtension`
| **`SupplyRequest.patient`**| →→→→ _Equivalent_ →→→→ <br/>(19006)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(773)| `base64Binary`| | | | | | | 
| **`SupplyRequest.patient`**| →→→→ _Equivalent_ →→→→ <br/>(19006)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(773)| `SupplyRequest.extension`| _Equivalent_<br/>(19034/19035)| `SupplyRequest.extension`| _Equivalent_<br/>(33899/33900)| `SupplyRequest.extension`| _Equivalent_<br/>(48445/48446)| `SupplyRequest.extension`
| **`SupplyRequest.source`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(429)<hr/>←←←← _RelatedTo_ ←←←← <br/>(772)| `SupplyRequest.requester.agent`| →→→→ _RelatedTo_ →→→→ <br/>(1291)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1679)| `SupplyRequest.requester`| _Equivalent_<br/>(33931/33932)| `SupplyRequest.requester`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(48475)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(48476)| `SupplyRequest.requester`
| **`SupplyRequest.date`**| _Equivalent_<br/>(426/769)| `SupplyRequest.authoredOn`| _Equivalent_<br/>(19051/19052)| `SupplyRequest.authoredOn`| _Equivalent_<br/>(33929/33930)| `SupplyRequest.authoredOn`| _Equivalent_<br/>(48473/48474)| `SupplyRequest.authoredOn`
| **`SupplyRequest.identifier`**| _Equivalent_<br/>(8125/8126)| `SupplyRequest.identifier`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19038)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19039)| `SupplyRequest.identifier`| _Equivalent_<br/>(33903/33904)| `SupplyRequest.identifier`| _Equivalent_<br/>(48449/48450)| `SupplyRequest.identifier`
| **`SupplyRequest.status`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8127)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8128)| `SupplyRequest.status`| _Equivalent_<br/>(19040/19041)| `SupplyRequest.status`| _Equivalent_<br/>(33905/33906)| `SupplyRequest.status`| _Equivalent_<br/>(48451/48452)| `SupplyRequest.status`
| **`SupplyRequest.kind`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(427)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(770)| `SupplyRequest.category`| _Equivalent_<br/>(19042/19043)| `SupplyRequest.category`| _Equivalent_<br/>(33907/33908)| `SupplyRequest.category`| _Equivalent_<br/>(48453/48454)| `SupplyRequest.category`
| **`SupplyRequest.orderedItem`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(8129)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8130)| `SupplyRequest.orderedItem`| →→→→ _RelatedTo_ →→→→ <br/>(1286)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1680)| `SupplyRequest`| _Equivalent_<br/>(33885/33886)| `SupplyRequest`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(48431)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(48432)| `SupplyRequest`
| **`SupplyRequest.supplier`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8131)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8132)| `SupplyRequest.supplier`| →→→→ _RelatedTo_ →→→→ <br/>(19058)<hr/>←←←← _RelatedTo_ ←←←← <br/>(19059)| `SupplyRequest.supplier`| _Equivalent_<br/>(33933/33934)| `SupplyRequest.supplier`| _Equivalent_<br/>(48477/48478)| `SupplyRequest.supplier`
| **`SupplyRequest.reason[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8133)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8134)| `SupplyRequest.reason[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1290)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1678)| `SupplyRequest.reasonCode`| _Equivalent_<br/>(33935/33936)| `SupplyRequest.reasonCode`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1852)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2095)| `SupplyRequest.reason`
| **`SupplyRequest.reason[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(8133)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(8134)| `SupplyRequest.reason[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1290)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1678)| `SupplyRequest.reasonReference`| _Equivalent_<br/>(33937/33938)| `SupplyRequest.reasonReference`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1853)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2096)| `SupplyRequest.reason`
| **`SupplyRequest.when`**| →→→→ _RelatedTo_ →→→→ <br/>(430)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(768)| `SupplyRequest`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(19020)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19021)| `SupplyRequest`| _Equivalent_<br/>(33885/33886)| `SupplyRequest`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(48431)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(48432)| `SupplyRequest`
| **`SupplyRequest.when.id`**| | | | | | | | | 
| **`SupplyRequest.when.extension`**| | | | | | | | | 
| **`SupplyRequest.when.modifierExtension`**| | | | | | | | | 
| **`SupplyRequest.when.code`**| | | | | | | | | 
| **`SupplyRequest.when.schedule`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(432)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(771)| `SupplyRequest.occurrence[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19049)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19050)| `SupplyRequest.occurrence[x]`| _Equivalent_<br/>(33927/33928)| `SupplyRequest.occurrence[x]`| _Equivalent_<br/>(48471/48472)| `SupplyRequest.occurrence[x]`
| *24 of 24 elements used* | | *19 of 31 elements used* | | *18 of 29 elements used* | | *18 of 29 elements used* | | *17 of 30 elements used* 

