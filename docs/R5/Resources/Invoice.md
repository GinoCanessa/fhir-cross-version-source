Comparison of 
Generated at Thursday, April 3, 2025 8:18:34 AM

### Invoice

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | Invoice |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Invoice` |
| Version | 5.0.0 |
| Description | Invoice containing collected ChargeItems from an Account with calculated individual and total price for Billing purpose. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2329` |
| Database Snapshot Count | `39` |
| Database Differential Count | `25` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Invoice` | `Invoice` | `Invoice` | Invoice | Invoice containing ChargeItems from an Account | 0..* | Invoice |  |  |
| `Invoice.account` | `Invoice.account` | `account` | Invoice.account | Account that is being balanced | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Account) |  |  |
| `Invoice.cancelledReason` | `Invoice.cancelledReason` | `cancelledReason` | Invoice.cancelledReason | Reason for cancellation of this Invoice | 0..1 | string |  |  |
| `Invoice.contained` | `Invoice.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Invoice.creation` | `Invoice.creation` | `creation` | Invoice.creation | When posted | 0..1 | dateTime |  |  |
| `Invoice.date` | `Invoice.date` | `date` | Invoice.date | DEPRICATED | 0..1 | dateTime |  |  |
| `Invoice.extension` | `Invoice.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Invoice.id` | `Invoice.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Invoice.identifier` | `Invoice.identifier` | `identifier` | Invoice.identifier | Business Identifier for item | 0..* | Identifier |  |  |
| `Invoice.implicitRules` | `Invoice.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Invoice.issuer` | `Invoice.issuer` | `issuer` | Invoice.issuer | Issuing Organization of Invoice | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Invoice.language` | `Invoice.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `Invoice.lineItem` | `Invoice.lineItem` | `lineItem` | Invoice.lineItem | Line items of this Invoice | 0..* | BackboneElement |  |  |
| `Invoice.lineItem.chargeItem[x]` | `Invoice.lineItem.chargeItem[x]` | `chargeItem[x]` | Invoice.lineItem.chargeItem[x] | Reference to ChargeItem containing details of this line item or an inline billing code | 1..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/ChargeItem) |  |  |
| `Invoice.lineItem.extension` | `Invoice.lineItem.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Invoice.lineItem.id` | `Invoice.lineItem.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Invoice.lineItem.modifierExtension` | `Invoice.lineItem.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Invoice.lineItem.priceComponent` | `Invoice.lineItem.priceComponent` | `priceComponent` | Invoice.lineItem.priceComponent | Components of total line item price | 0..* | MonetaryComponent |  |  |
| `Invoice.lineItem.sequence` | `Invoice.lineItem.sequence` | `sequence` | Invoice.lineItem.sequence | Sequence number of line item | 0..1 | positiveInt |  |  |
| `Invoice.lineItem.serviced[x]` | `Invoice.lineItem.serviced[x]` | `serviced[x]` | Invoice.lineItem.serviced[x] | Service data or period | 0..1 | date, Period |  |  |
| `Invoice.meta` | `Invoice.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Invoice.modifierExtension` | `Invoice.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Invoice.note` | `Invoice.note` | `note` | Invoice.note | Comments made about the invoice | 0..* | Annotation |  |  |
| `Invoice.participant` | `Invoice.participant` | `participant` | Invoice.participant | Participant in creation of this Invoice | 0..* | BackboneElement |  |  |
| `Invoice.participant.actor` | `Invoice.participant.actor` | `actor` | Invoice.participant.actor | Individual who was involved | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Invoice.participant.extension` | `Invoice.participant.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `Invoice.participant.id` | `Invoice.participant.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `Invoice.participant.modifierExtension` | `Invoice.participant.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `Invoice.participant.role` | `Invoice.participant.role` | `role` | Invoice.participant.role | Type of involvement in creation of this Invoice | 0..1 | CodeableConcept |  |  |
| `Invoice.paymentTerms` | `Invoice.paymentTerms` | `paymentTerms` | Invoice.paymentTerms | Payment details | 0..1 | markdown |  |  |
| `Invoice.period[x]` | `Invoice.period[x]` | `period[x]` | Invoice.period[x] | Billing date or period | 0..1 | date, Period |  |  |
| `Invoice.recipient` | `Invoice.recipient` | `recipient` | Invoice.recipient | Recipient of this invoice | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Invoice.status` | `Invoice.status` | `status` | Invoice.status | draft \| issued \| balanced \| cancelled \| entered-in-error | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/invoice-status|5.0.0` |
| `Invoice.subject` | `Invoice.subject` | `subject` | Invoice.subject | Recipient(s) of goods and services | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `Invoice.text` | `Invoice.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Invoice.totalGross` | `Invoice.totalGross` | `totalGross` | Invoice.totalGross | Gross total of this Invoice | 0..1 | Money |  |  |
| `Invoice.totalNet` | `Invoice.totalNet` | `totalNet` | Invoice.totalNet | Net total of this Invoice | 0..1 | Money |  |  |
| `Invoice.totalPriceComponent` | `Invoice.totalPriceComponent` | `totalPriceComponent` | Invoice.totalPriceComponent | Components of Invoice total | 0..* | MonetaryComponent |  |  |
| `Invoice.type` | `Invoice.type` | `type` | Invoice.type | Type of Invoice | 0..1 | CodeableConcept |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | [Invoice](/docs/R4/Resources/Invoice.md)<br/> `http://hl7.org/fhir/StructureDefinition/Invoice\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1519`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1520`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Invoice](/docs/R4B/Resources/Invoice.md)<br/> `http://hl7.org/fhir/StructureDefinition/Invoice\|4.3.0` | →→→→→→→<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `994`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1223`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Invoice](/docs/R5/Resources/Invoice.md)<br/> `http://hl7.org/fhir/StructureDefinition/Invoice\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Invoice from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | *No Map* | Relationship | [R4 Invoice](/docs/R4/Resources/Invoice.md)| Relationship | [R4B Invoice](/docs/R4B/Resources/Invoice.md)| Relationship | R5 Invoice
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `Invoice`| _Equivalent_<br/>(28711/28712)| `Invoice`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(43595)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(43596)| **`Invoice`**
| | | | | `Invoice.id`| _Equivalent_<br/>(28713/28714)| `Invoice.id`| _Equivalent_<br/>(43597/43598)| **`Invoice.id`**
| | | | | `Invoice.meta`| _Equivalent_<br/>(28715/28716)| `Invoice.meta`| _Equivalent_<br/>(43599/43600)| **`Invoice.meta`**
| | | | | `Invoice.implicitRules`| _Equivalent_<br/>(28717/28718)| `Invoice.implicitRules`| _Equivalent_<br/>(43601/43602)| **`Invoice.implicitRules`**
| | | | | `Invoice.language`| _Equivalent_<br/>(28719/28720)| `Invoice.language`| _Equivalent_<br/>(43603/43604)| **`Invoice.language`**
| | | | | `Invoice.text`| _Equivalent_<br/>(28721/28722)| `Invoice.text`| _Equivalent_<br/>(43605/43606)| **`Invoice.text`**
| | | | | `Invoice.contained`| _Equivalent_<br/>(28723/28724)| `Invoice.contained`| _Equivalent_<br/>(43607/43608)| **`Invoice.contained`**
| | | | | `Invoice.extension`| _Equivalent_<br/>(28725/28726)| `Invoice.extension`| _Equivalent_<br/>(43609/43610)| **`Invoice.extension`**
| | | | | `Invoice.modifierExtension`| _Equivalent_<br/>(28727/28728)| `Invoice.modifierExtension`| _Equivalent_<br/>(43611/43612)| **`Invoice.modifierExtension`**
| | | | | `Invoice.identifier`| _Equivalent_<br/>(28729/28730)| `Invoice.identifier`| _Equivalent_<br/>(43613/43614)| **`Invoice.identifier`**
| | | | | `Invoice.status`| _Equivalent_<br/>(28731/28732)| `Invoice.status`| _Equivalent_<br/>(43615/43616)| **`Invoice.status`**
| | | | | `Invoice.cancelledReason`| _Equivalent_<br/>(28733/28734)| `Invoice.cancelledReason`| _Equivalent_<br/>(43617/43618)| **`Invoice.cancelledReason`**
| | | | | `Invoice.type`| _Equivalent_<br/>(28735/28736)| `Invoice.type`| _Equivalent_<br/>(43619/43620)| **`Invoice.type`**
| | | | | `Invoice.subject`| _Equivalent_<br/>(28737/28738)| `Invoice.subject`| _Equivalent_<br/>(43621/43622)| **`Invoice.subject`**
| | | | | `Invoice.recipient`| _Equivalent_<br/>(28739/28740)| `Invoice.recipient`| _Equivalent_<br/>(43623/43624)| **`Invoice.recipient`**
| | | | | `Invoice.date`| _Equivalent_<br/>(28741/28742)| `Invoice.date`| _Equivalent_<br/>(43625/43626)| **`Invoice.date`**
| | | | | | | | | **`Invoice.creation`**
| | | | | | | | | **`Invoice.period[x]`**
| | | | | `Invoice.participant`| _Equivalent_<br/>(28743/28744)| `Invoice.participant`| _Equivalent_<br/>(43627/43628)| **`Invoice.participant`**
| | | | | `Invoice.participant.id`| _Equivalent_<br/>(28745/28746)| `Invoice.participant.id`| _Equivalent_<br/>(43629/43630)| **`Invoice.participant.id`**
| | | | | `Invoice.participant.extension`| _Equivalent_<br/>(28747/28748)| `Invoice.participant.extension`| _Equivalent_<br/>(43631/43632)| **`Invoice.participant.extension`**
| | | | | `Invoice.participant.modifierExtension`| _Equivalent_<br/>(28749/28750)| `Invoice.participant.modifierExtension`| _Equivalent_<br/>(43633/43634)| **`Invoice.participant.modifierExtension`**
| | | | | `Invoice.participant.role`| _Equivalent_<br/>(28751/28752)| `Invoice.participant.role`| _Equivalent_<br/>(43635/43636)| **`Invoice.participant.role`**
| | | | | `Invoice.participant.actor`| _Equivalent_<br/>(28753/28754)| `Invoice.participant.actor`| _Equivalent_<br/>(43637/43638)| **`Invoice.participant.actor`**
| | | | | `Invoice.issuer`| _Equivalent_<br/>(28755/28756)| `Invoice.issuer`| _Equivalent_<br/>(43639/43640)| **`Invoice.issuer`**
| | | | | `Invoice.account`| _Equivalent_<br/>(28757/28758)| `Invoice.account`| _Equivalent_<br/>(43641/43642)| **`Invoice.account`**
| | | | | `Invoice.lineItem`| _Equivalent_<br/>(28759/28760)| `Invoice.lineItem`| _Equivalent_<br/>(43643/43644)| **`Invoice.lineItem`**
| | | | | `Invoice.lineItem.id`| _Equivalent_<br/>(28761/28762)| `Invoice.lineItem.id`| _Equivalent_<br/>(43645/43646)| **`Invoice.lineItem.id`**
| | | | | `Invoice.lineItem.extension`| _Equivalent_<br/>(28763/28764)| `Invoice.lineItem.extension`| _Equivalent_<br/>(43647/43648)| **`Invoice.lineItem.extension`**
| | | | | `Invoice.lineItem.modifierExtension`| _Equivalent_<br/>(28765/28766)| `Invoice.lineItem.modifierExtension`| _Equivalent_<br/>(43649/43650)| **`Invoice.lineItem.modifierExtension`**
| | | | | `Invoice.lineItem.sequence`| _Equivalent_<br/>(28767/28768)| `Invoice.lineItem.sequence`| _Equivalent_<br/>(43651/43652)| **`Invoice.lineItem.sequence`**
| | | | | | | | | **`Invoice.lineItem.serviced[x]`**
| | | | | `Invoice.lineItem.chargeItem[x]`| _Equivalent_<br/>(28769/28770)| `Invoice.lineItem.chargeItem[x]`| _Equivalent_<br/>(43653/43654)| **`Invoice.lineItem.chargeItem[x]`**
| | | | | `Invoice.lineItem.priceComponent`| _Equivalent_<br/>(28771/28772)| `Invoice.lineItem.priceComponent`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(43655)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(43656)| **`Invoice.lineItem.priceComponent`**
| | | | | `Invoice.totalPriceComponent`| _Equivalent_<br/>(28787/28788)| `Invoice.totalPriceComponent`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(43664)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(43665)| **`Invoice.totalPriceComponent`**
| | | | | `Invoice.totalNet`| _Equivalent_<br/>(28789/28790)| `Invoice.totalNet`| _Equivalent_<br/>(43666/43667)| **`Invoice.totalNet`**
| | | | | `Invoice.totalGross`| _Equivalent_<br/>(28791/28792)| `Invoice.totalGross`| _Equivalent_<br/>(43668/43669)| **`Invoice.totalGross`**
| | | | | `Invoice.paymentTerms`| _Equivalent_<br/>(28793/28794)| `Invoice.paymentTerms`| _Equivalent_<br/>(43670/43671)| **`Invoice.paymentTerms`**
| | | | | `Invoice.note`| _Equivalent_<br/>(28795/28796)| `Invoice.note`| _Equivalent_<br/>(43672/43673)| **`Invoice.note`**
| | | | | *36 of 43 elements used* <br/>remaining elements:<br/>`Invoice.lineItem.priceComponent.amount`, `Invoice.lineItem.priceComponent.code`, `Invoice.lineItem.priceComponent.extension`, `Invoice.lineItem.priceComponent.factor`, `Invoice.lineItem.priceComponent.id`, `Invoice.lineItem.priceComponent.modifierExtension`, `Invoice.lineItem.priceComponent.type`| | *36 of 43 elements used* <br/>remaining elements:<br/>`Invoice.lineItem.priceComponent.amount`, `Invoice.lineItem.priceComponent.code`, `Invoice.lineItem.priceComponent.extension`, `Invoice.lineItem.priceComponent.factor`, `Invoice.lineItem.priceComponent.id`, `Invoice.lineItem.priceComponent.modifierExtension`, `Invoice.lineItem.priceComponent.type`| | *39 of 39 elements used* 

