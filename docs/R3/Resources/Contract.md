Comparison of 
Generated at Tuesday, April 1, 2025 1:39:16 PM

### Contract

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | Contract |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Contract` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for Contract Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `501` |
| Database Snapshot Count | `98` |
| Database Differential Count | `63` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Contract` | `Contract` | `Contract` | Contract | Legal Agreement | 0..* | Contract |  |  |
| `Contract.action` | `Contract.action` | `action` |  | Action stipulated by this Contract | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/contract-action` |
| `Contract.actionReason` | `Contract.actionReason` | `actionReason` |  | Rationale for the stiplulated action | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/v3-PurposeOfUse` |
| `Contract.agent` | `Contract.agent` | `agent` |  | Entity being ascribed responsibility | 0..* | BackboneElement |  |  |
| `Contract.agent.actor` | `Contract.agent.actor` | `actor` |  | Contract Agent Type | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Contract), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson), Reference(http://hl7.org/fhir/StructureDefinition/Substance) |  |  |
| `Contract.agent.extension` | `Contract.agent.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Contract.agent.id` | `Contract.agent.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Contract.agent.modifierExtension` | `Contract.agent.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Contract.agent.role` | `Contract.agent.role` | `role` |  | Role type of the agent | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/contract-actorrole` |
| `Contract.applies` | `Contract.applies` | `applies` |  | Effective time | 0..1 | Period |  |  |
| `Contract.authority` | `Contract.authority` | `authority` |  | Authority under which this Contract has standing | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `Contract.binding[x]` | `Contract.binding[x]` | `binding[x]` |  | Binding Contract | 0..1 | Attachment, Reference(http://hl7.org/fhir/StructureDefinition/Composition), Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference), Reference(http://hl7.org/fhir/StructureDefinition/QuestionnaireResponse) |  |  |
| `Contract.contained` | `Contract.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Contract.contentDerivative` | `Contract.contentDerivative` | `contentDerivative` |  | Content derived from the basal information | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/contract-content-derivative` |
| `Contract.decisionType` | `Contract.decisionType` | `decisionType` |  | Decision by Grantor | 0..1 | CodeableConcept | `Extensible` | `http://hl7.org/fhir/ValueSet/v3-ActConsentDirective` |
| `Contract.domain` | `Contract.domain` | `domain` |  | Domain in which this Contract applies | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Location) |  |  |
| `Contract.extension` | `Contract.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Contract.friendly` | `Contract.friendly` | `friendly` |  | Contract Friendly Language | 0..* | BackboneElement |  |  |
| `Contract.friendly.content[x]` | `Contract.friendly.content[x]` | `content[x]` |  | Easily comprehended representation of this Contract | 1..1 | Attachment, Reference(http://hl7.org/fhir/StructureDefinition/Composition), Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference), Reference(http://hl7.org/fhir/StructureDefinition/QuestionnaireResponse) |  |  |
| `Contract.friendly.extension` | `Contract.friendly.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Contract.friendly.id` | `Contract.friendly.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Contract.friendly.modifierExtension` | `Contract.friendly.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Contract.id` | `Contract.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Contract.identifier` | `Contract.identifier` | `identifier` |  | Contract number | 0..1 | Identifier |  |  |
| `Contract.implicitRules` | `Contract.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Contract.issued` | `Contract.issued` | `issued` |  | When this Contract was issued | 0..1 | dateTime |  |  |
| `Contract.language` | `Contract.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `Contract.legal` | `Contract.legal` | `legal` |  | Contract Legal Language | 0..* | BackboneElement |  |  |
| `Contract.legal.content[x]` | `Contract.legal.content[x]` | `content[x]` |  | Contract Legal Text | 1..1 | Attachment, Reference(http://hl7.org/fhir/StructureDefinition/Composition), Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference), Reference(http://hl7.org/fhir/StructureDefinition/QuestionnaireResponse) |  |  |
| `Contract.legal.extension` | `Contract.legal.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Contract.legal.id` | `Contract.legal.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Contract.legal.modifierExtension` | `Contract.legal.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Contract.meta` | `Contract.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Contract.modifierExtension` | `Contract.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Contract.rule` | `Contract.rule` | `rule` |  | Computable Contract Language | 0..* | BackboneElement |  |  |
| `Contract.rule.content[x]` | `Contract.rule.content[x]` | `content[x]` |  | Computable Contract Rules | 1..1 | Attachment, Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `Contract.rule.extension` | `Contract.rule.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Contract.rule.id` | `Contract.rule.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Contract.rule.modifierExtension` | `Contract.rule.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Contract.securityLabel` | `Contract.securityLabel` | `securityLabel` |  | Security Labels that define affected resources | 0..* | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/security-labels` |
| `Contract.signer` | `Contract.signer` | `signer` |  | Contract Signatory | 0..* | BackboneElement |  |  |
| `Contract.signer.extension` | `Contract.signer.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Contract.signer.id` | `Contract.signer.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Contract.signer.modifierExtension` | `Contract.signer.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Contract.signer.party` | `Contract.signer.party` | `party` |  | Contract Signatory Party | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `Contract.signer.signature` | `Contract.signer.signature` | `signature` |  | Contract Documentation Signature | 1..* | Signature |  |  |
| `Contract.signer.type` | `Contract.signer.type` | `type` |  | Contract Signatory Role | 1..1 | Coding | `Preferred` | `http://hl7.org/fhir/ValueSet/contract-signer-type` |
| `Contract.status` | `Contract.status` | `status` |  | amended \| appended \| cancelled \| disputed \| entered-in-error \| executable \| executed \| negotiable \| offered \| policy \| rejected \| renewed \| revoked \| resolved \| terminated | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/contract-status` |
| `Contract.subType` | `Contract.subType` | `subType` |  | Subtype within the context of type | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/contract-subtype` |
| `Contract.subject` | `Contract.subject` | `subject` |  | Contract Target Entity | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `Contract.term` | `Contract.term` | `term` |  | Contract Term List | 0..* | BackboneElement |  |  |
| `Contract.term.action` | `Contract.term.action` | `action` |  | Contract Term Activity | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/contract-action` |
| `Contract.term.actionReason` | `Contract.term.actionReason` | `actionReason` |  | Purpose for the Contract Term Action | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/v3-PurposeOfUse` |
| `Contract.term.agent` | `Contract.term.agent` | `agent` |  | Contract Term Agent List | 0..* | BackboneElement |  |  |
| `Contract.term.agent.actor` | `Contract.term.agent.actor` | `actor` |  | Contract Term Agent Subject | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Contract), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson), Reference(http://hl7.org/fhir/StructureDefinition/Substance) |  |  |
| `Contract.term.agent.extension` | `Contract.term.agent.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Contract.term.agent.id` | `Contract.term.agent.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Contract.term.agent.modifierExtension` | `Contract.term.agent.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Contract.term.agent.role` | `Contract.term.agent.role` | `role` |  | Type of the Contract Term Agent | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/contract-actorrole` |
| `Contract.term.applies` | `Contract.term.applies` | `applies` |  | Contract Term Effective Time | 0..1 | Period |  |  |
| `Contract.term.extension` | `Contract.term.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Contract.term.group` | `Contract.term.group` | `group` |  | Nested Contract Term Group | 0..* | Contract.term |  |  |
| `Contract.term.id` | `Contract.term.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Contract.term.identifier` | `Contract.term.identifier` | `identifier` |  | Contract Term Number | 0..1 | Identifier |  |  |
| `Contract.term.issued` | `Contract.term.issued` | `issued` |  | Contract Term Issue Date Time | 0..1 | dateTime |  |  |
| `Contract.term.modifierExtension` | `Contract.term.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Contract.term.securityLabel` | `Contract.term.securityLabel` | `securityLabel` |  | Security Labels that define affected terms | 0..* | Coding | `Extensible` | `http://hl7.org/fhir/ValueSet/security-labels` |
| `Contract.term.subType` | `Contract.term.subType` | `subType` |  | Contract Term Type specific classification | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/contract-term-subtype` |
| `Contract.term.text` | `Contract.term.text` | `text` |  | Human readable Contract term text | 0..1 | string |  |  |
| `Contract.term.topic` | `Contract.term.topic` | `topic` |  | Context of the Contract term | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `Contract.term.type` | `Contract.term.type` | `type` |  | Contract Term Type or Form | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/contract-term-type` |
| `Contract.term.valuedItem` | `Contract.term.valuedItem` | `valuedItem` |  | Contract Term Valued Item List | 0..* | BackboneElement |  |  |
| `Contract.term.valuedItem.effectiveTime` | `Contract.term.valuedItem.effectiveTime` | `effectiveTime` |  | Contract Term Valued Item Effective Tiem | 0..1 | dateTime |  |  |
| `Contract.term.valuedItem.entity[x]` | `Contract.term.valuedItem.entity[x]` | `entity[x]` |  | Contract Term Valued Item Type | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `Contract.term.valuedItem.extension` | `Contract.term.valuedItem.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Contract.term.valuedItem.factor` | `Contract.term.valuedItem.factor` | `factor` |  | Contract Term Valued Item Price Scaling Factor | 0..1 | decimal |  |  |
| `Contract.term.valuedItem.id` | `Contract.term.valuedItem.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Contract.term.valuedItem.identifier` | `Contract.term.valuedItem.identifier` | `identifier` |  | Contract Term Valued Item Number | 0..1 | Identifier |  |  |
| `Contract.term.valuedItem.modifierExtension` | `Contract.term.valuedItem.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Contract.term.valuedItem.net` | `Contract.term.valuedItem.net` | `net` |  | Total Contract Term Valued Item Value | 0..1 | Money |  |  |
| `Contract.term.valuedItem.points` | `Contract.term.valuedItem.points` | `points` |  | Contract Term Valued Item Difficulty Scaling Factor | 0..1 | decimal |  |  |
| `Contract.term.valuedItem.quantity` | `Contract.term.valuedItem.quantity` | `quantity` |  | Contract Term Valued Item Count | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `Contract.term.valuedItem.unitPrice` | `Contract.term.valuedItem.unitPrice` | `unitPrice` |  | Contract Term Valued Item fee, charge, or cost | 0..1 | Money |  |  |
| `Contract.text` | `Contract.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Contract.topic` | `Contract.topic` | `topic` |  | Context of the Contract | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `Contract.type` | `Contract.type` | `type` |  | Type or form | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/contract-type` |
| `Contract.valuedItem` | `Contract.valuedItem` | `valuedItem` |  | Contract Valued Item List | 0..* | BackboneElement |  |  |
| `Contract.valuedItem.effectiveTime` | `Contract.valuedItem.effectiveTime` | `effectiveTime` |  | Contract Valued Item Effective Tiem | 0..1 | dateTime |  |  |
| `Contract.valuedItem.entity[x]` | `Contract.valuedItem.entity[x]` | `entity[x]` |  | Contract Valued Item Type | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `Contract.valuedItem.extension` | `Contract.valuedItem.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Contract.valuedItem.factor` | `Contract.valuedItem.factor` | `factor` |  | Contract Valued Item Price Scaling Factor | 0..1 | decimal |  |  |
| `Contract.valuedItem.id` | `Contract.valuedItem.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Contract.valuedItem.identifier` | `Contract.valuedItem.identifier` | `identifier` |  | Contract Valued Item Number | 0..1 | Identifier |  |  |
| `Contract.valuedItem.modifierExtension` | `Contract.valuedItem.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Contract.valuedItem.net` | `Contract.valuedItem.net` | `net` |  | Total Contract Valued Item Value | 0..1 | Money |  |  |
| `Contract.valuedItem.points` | `Contract.valuedItem.points` | `points` |  | Contract Valued Item Difficulty Scaling Factor | 0..1 | decimal |  |  |
| `Contract.valuedItem.quantity` | `Contract.valuedItem.quantity` | `quantity` |  | Count of Contract Valued Items | 0..1 | Quantity[http://hl7.org/fhir/StructureDefinition/SimpleQuantity] |  |  |
| `Contract.valuedItem.unitPrice` | `Contract.valuedItem.unitPrice` | `unitPrice` |  | Contract Valued Item fee, charge, or cost | 0..1 | Money |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Contract](/docs/R2/Resources/Contract.md)<br/> `http://hl7.org/fhir/StructureDefinition/Contract\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `91`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `258`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Contract](/docs/R3/Resources/Contract.md)<br/> `http://hl7.org/fhir/StructureDefinition/Contract\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `441`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `637`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Contract](/docs/R4/Resources/Contract.md)<br/> `http://hl7.org/fhir/StructureDefinition/Contract\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1445`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1446`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Contract](/docs/R4B/Resources/Contract.md)<br/> `http://hl7.org/fhir/StructureDefinition/Contract\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `957`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1186`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Contract](/docs/R5/Resources/Contract.md)<br/> `http://hl7.org/fhir/StructureDefinition/Contract\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Contract from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 Contract](/docs/R2/Resources/Contract.md)| Relationship | R3 Contract| Relationship | [R4 Contract](/docs/R4/Resources/Contract.md)| Relationship | [R4B Contract](/docs/R4B/Resources/Contract.md)| Relationship | [R5 Contract](/docs/R5/Resources/Contract.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `Contract`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4177)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4178)| **`Contract`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12596)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12597)| `Contract`| _Equivalent_<br/>(24589/24590)| `Contract`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(39695)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(39696)| `Contract`
| `Contract.id`| _Equivalent_<br/>(4179/4180)| **`Contract.id`**| _Equivalent_<br/>(12598/12599)| `Contract.id`| _Equivalent_<br/>(24591/24592)| `Contract.id`| _Equivalent_<br/>(39697/39698)| `Contract.id`
| `Contract.meta`| _Equivalent_<br/>(4181/4182)| **`Contract.meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12600)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12601)| `Contract.meta`| _Equivalent_<br/>(24593/24594)| `Contract.meta`| _Equivalent_<br/>(39699/39700)| `Contract.meta`
| `Contract.implicitRules`| _Equivalent_<br/>(4183/4184)| **`Contract.implicitRules`**| _Equivalent_<br/>(12602/12603)| `Contract.implicitRules`| _Equivalent_<br/>(24595/24596)| `Contract.implicitRules`| _Equivalent_<br/>(39701/39702)| `Contract.implicitRules`
| `Contract.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4185)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(4186)| **`Contract.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12604)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(12605)| `Contract.language`| _Equivalent_<br/>(24597/24598)| `Contract.language`| _Equivalent_<br/>(39703/39704)| `Contract.language`
| `Contract.text`| _Equivalent_<br/>(4187/4188)| **`Contract.text`**| _Equivalent_<br/>(12606/12607)| `Contract.text`| _Equivalent_<br/>(24599/24600)| `Contract.text`| _Equivalent_<br/>(39705/39706)| `Contract.text`
| `Contract.contained`| _Equivalent_<br/>(4189/4190)| **`Contract.contained`**| _Equivalent_<br/>(12608/12609)| `Contract.contained`| _Equivalent_<br/>(24601/24602)| `Contract.contained`| _Equivalent_<br/>(39707/39708)| `Contract.contained`
| `Contract.extension`| _Equivalent_<br/>(4191/4192)| **`Contract.extension`**| _Equivalent_<br/>(12610/12611)| `Contract.extension`| _Equivalent_<br/>(24603/24604)| `Contract.extension`| _Equivalent_<br/>(39709/39710)| `Contract.extension`
| `Contract.modifierExtension`| _Equivalent_<br/>(4193/4194)| **`Contract.modifierExtension`**| _Equivalent_<br/>(12612/12613)| `Contract.modifierExtension`| _Equivalent_<br/>(24605/24606)| `Contract.modifierExtension`| _Equivalent_<br/>(39711/39712)| `Contract.modifierExtension`
| `Contract.identifier`| _Equivalent_<br/>(4195/4196)| **`Contract.identifier`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12614)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12615)| `Contract.identifier`| _Equivalent_<br/>(24607/24608)| `Contract.identifier`| _Equivalent_<br/>(39713/39714)| `Contract.identifier`
| | | **`Contract.status`**| _Equivalent_<br/>(12616/12617)| `Contract.status`| _Equivalent_<br/>(24613/24614)| `Contract.status`| _Equivalent_<br/>(39719/39720)| `Contract.status`
| `Contract.issued`| _Equivalent_<br/>(4197/4198)| **`Contract.issued`**| _Equivalent_<br/>(12618/12619)| `Contract.issued`| _Equivalent_<br/>(24623/24624)| `Contract.issued`| _Equivalent_<br/>(39729/39730)| `Contract.issued`
| `Contract.applies`| _Equivalent_<br/>(4199/4200)| **`Contract.applies`**| _Equivalent_<br/>(12620/12621)| `Contract.applies`| _Equivalent_<br/>(24625/24626)| `Contract.applies`| _Equivalent_<br/>(39731/39732)| `Contract.applies`
| `Contract.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4201)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4202)| **`Contract.subject`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12622)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12623)| `Contract.subject`| _Equivalent_<br/>(24629/24630)| `Contract.subject`| _Equivalent_<br/>(39735/39736)| `Contract.subject`
| | | **`Contract.topic`**| →→→→ _RelatedTo_ →→→→ <br/>(955)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1448)| `Contract.topic[x]`| _Equivalent_<br/>(24649/24650)| `Contract.topic[x]`| _Equivalent_<br/>(39755/39756)| `Contract.topic[x]`
| `Contract.authority`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4203)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4204)| **`Contract.authority`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12624)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12625)| `Contract.authority`| _Equivalent_<br/>(24631/24632)| `Contract.authority`| _Equivalent_<br/>(39737/39738)| `Contract.authority`
| `Contract.domain`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4205)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4206)| **`Contract.domain`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12626)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12627)| `Contract.domain`| _Equivalent_<br/>(24633/24634)| `Contract.domain`| _Equivalent_<br/>(39739/39740)| `Contract.domain`
| `Contract.type`| _Equivalent_<br/>(4207/4208)| **`Contract.type`**| _Equivalent_<br/>(12628/12629)| `Contract.type`| _Equivalent_<br/>(24651/24652)| `Contract.type`| _Equivalent_<br/>(39757/39758)| `Contract.type`
| `Contract.subType`| _Equivalent_<br/>(4209/4210)| **`Contract.subType`**| _Equivalent_<br/>(12630/12631)| `Contract.subType`| _Equivalent_<br/>(24653/24654)| `Contract.subType`| _Equivalent_<br/>(39759/39760)| `Contract.subType`
| `Contract.action`| _Equivalent_<br/>(4211/4212)| **`Contract.action`**| | | | | | | 
| `Contract.actionReason`| _Equivalent_<br/>(4213/4214)| **`Contract.actionReason`**| | | | | | | 
| | | **`Contract.decisionType`**| | | | | | | 
| | | **`Contract.contentDerivative`**| _Equivalent_<br/>(12632/12633)| `Contract.contentDerivative`| _Equivalent_<br/>(24621/24622)| `Contract.contentDerivative`| _Equivalent_<br/>(39727/39728)| `Contract.contentDerivative`
| | | **`Contract.securityLabel`**| | | | | | | 
| `Contract.actor`| _Equivalent_<br/>(166/580)| **`Contract.agent`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(937)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1449)| `Contract`| _Equivalent_<br/>(24589/24590)| `Contract`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(39695)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(39696)| `Contract`
| | | **`Contract.agent.id`**| | | | | | | 
| | | **`Contract.agent.extension`**| | | | | | | 
| | | **`Contract.agent.modifierExtension`**| | | | | | | 
| `Contract.actor.entity`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(167)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(581)| **`Contract.agent.actor`**| →→→→ _RelatedTo_ →→→→ <br/>(938)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1446)| `Contract.author`| _Equivalent_<br/>(24645/24646)| `Contract.author`| _Equivalent_<br/>(39751/39752)| `Contract.author`
| `Contract.actor.role`| _Equivalent_<br/>(168/582)| **`Contract.agent.role`**| | | | | | | 
| `Contract.signer`| _Equivalent_<br/>(4242/4243)| **`Contract.signer`**| _Equivalent_<br/>(12637/12638)| `Contract.signer`| _Equivalent_<br/>(24909/24910)| `Contract.signer`| _Equivalent_<br/>(40013/40014)| `Contract.signer`
| `Contract.signer.id`| _Equivalent_<br/>(4244/4245)| **`Contract.signer.id`**| _Equivalent_<br/>(12639/12640)| `Contract.signer.id`| _Equivalent_<br/>(24911/24912)| `Contract.signer.id`| _Equivalent_<br/>(40015/40016)| `Contract.signer.id`
| `Contract.signer.extension`| _Equivalent_<br/>(4246/4247)| **`Contract.signer.extension`**| _Equivalent_<br/>(12641/12642)| `Contract.signer.extension`| _Equivalent_<br/>(24913/24914)| `Contract.signer.extension`| _Equivalent_<br/>(40017/40018)| `Contract.signer.extension`
| `Contract.signer.modifierExtension`| _Equivalent_<br/>(4248/4249)| **`Contract.signer.modifierExtension`**| _Equivalent_<br/>(12643/12644)| `Contract.signer.modifierExtension`| _Equivalent_<br/>(24915/24916)| `Contract.signer.modifierExtension`| _Equivalent_<br/>(40019/40020)| `Contract.signer.modifierExtension`
| `Contract.signer.type`| _Equivalent_<br/>(4250/4251)| **`Contract.signer.type`**| _Equivalent_<br/>(12645/12646)| `Contract.signer.type`| _Equivalent_<br/>(24917/24918)| `Contract.signer.type`| _Equivalent_<br/>(40021/40022)| `Contract.signer.type`
| `Contract.signer.party`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4252)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4253)| **`Contract.signer.party`**| →→→→ _RelatedTo_ →→→→ <br/>(12647)<hr/>←←←← _RelatedTo_ ←←←← <br/>(12648)| `Contract.signer.party`| _Equivalent_<br/>(24919/24920)| `Contract.signer.party`| _Equivalent_<br/>(40023/40024)| `Contract.signer.party`
| `Contract.signer.signature`| →→→→ _RelatedTo_ →→→→ <br/>(4254)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4255)| **`Contract.signer.signature`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12649)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12650)| `Contract.signer.signature`| _Equivalent_<br/>(24921/24922)| `Contract.signer.signature`| _Equivalent_<br/>(40025/40026)| `Contract.signer.signature`
| `Contract.valuedItem`| _Equivalent_<br/>(4218/4219)| **`Contract.valuedItem`**| | | | | | | 
| `Contract.valuedItem.id`| _Equivalent_<br/>(4220/4221)| **`Contract.valuedItem.id`**| | | | | | | 
| `Contract.valuedItem.extension`| _Equivalent_<br/>(4222/4223)| **`Contract.valuedItem.extension`**| | | | | | | 
| `Contract.valuedItem.modifierExtension`| _Equivalent_<br/>(4224/4225)| **`Contract.valuedItem.modifierExtension`**| | | | | | | 
| `Contract.valuedItem.entity[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4226)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4227)| **`Contract.valuedItem.entity[x]`**| | | | | | | 
| `Contract.valuedItem.identifier`| _Equivalent_<br/>(4228/4229)| **`Contract.valuedItem.identifier`**| | | | | | | 
| `Contract.valuedItem.effectiveTime`| _Equivalent_<br/>(4230/4231)| **`Contract.valuedItem.effectiveTime`**| | | | | | | 
| `Contract.valuedItem.quantity`| _Equivalent_<br/>(4232/4233)| **`Contract.valuedItem.quantity`**| | | | | | | 
| `Contract.valuedItem.unitPrice`| →→→→ _RelatedTo_ →→→→ <br/>(4234)<hr/>←←←← _RelatedTo_ ←←←← <br/>(4235)| **`Contract.valuedItem.unitPrice`**| | | | | | | 
| `Contract.valuedItem.factor`| _Equivalent_<br/>(4236/4237)| **`Contract.valuedItem.factor`**| | | | | | | 
| `Contract.valuedItem.points`| _Equivalent_<br/>(4238/4239)| **`Contract.valuedItem.points`**| | | | | | | 
| `Contract.valuedItem.net`| →→→→ _RelatedTo_ →→→→ <br/>(4240)<hr/>←←←← _RelatedTo_ ←←←← <br/>(4241)| **`Contract.valuedItem.net`**| | | | | | | 
| `Contract.term`| _Equivalent_<br/>(4256/4257)| **`Contract.term`**| _Equivalent_<br/>(12655/12656)| `Contract.term`| _Equivalent_<br/>(24675/24676)| `Contract.term`| _Equivalent_<br/>(39781/39782)| `Contract.term`
| `Contract.term.id`| _Equivalent_<br/>(4258/4259)| **`Contract.term.id`**| _Equivalent_<br/>(12657/12658)| `Contract.term.id`| _Equivalent_<br/>(24677/24678)| `Contract.term.id`| _Equivalent_<br/>(39783/39784)| `Contract.term.id`
| `Contract.term.extension`| _Equivalent_<br/>(4260/4261)| **`Contract.term.extension`**| _Equivalent_<br/>(12659/12660)| `Contract.term.extension`| _Equivalent_<br/>(24679/24680)| `Contract.term.extension`| _Equivalent_<br/>(39785/39786)| `Contract.term.extension`
| `Contract.term.modifierExtension`| _Equivalent_<br/>(4262/4263)| **`Contract.term.modifierExtension`**| _Equivalent_<br/>(12661/12662)| `Contract.term.modifierExtension`| _Equivalent_<br/>(24681/24682)| `Contract.term.modifierExtension`| _Equivalent_<br/>(39787/39788)| `Contract.term.modifierExtension`
| `Contract.term.identifier`| _Equivalent_<br/>(4264/4265)| **`Contract.term.identifier`**| _Equivalent_<br/>(12663/12664)| `Contract.term.identifier`| _Equivalent_<br/>(24683/24684)| `Contract.term.identifier`| _Equivalent_<br/>(39789/39790)| `Contract.term.identifier`
| `Contract.term.issued`| _Equivalent_<br/>(4266/4267)| **`Contract.term.issued`**| _Equivalent_<br/>(12665/12666)| `Contract.term.issued`| _Equivalent_<br/>(24685/24686)| `Contract.term.issued`| _Equivalent_<br/>(39791/39792)| `Contract.term.issued`
| `Contract.term.applies`| _Equivalent_<br/>(4268/4269)| **`Contract.term.applies`**| _Equivalent_<br/>(12667/12668)| `Contract.term.applies`| _Equivalent_<br/>(24687/24688)| `Contract.term.applies`| _Equivalent_<br/>(39793/39794)| `Contract.term.applies`
| `Contract.term.type`| _Equivalent_<br/>(4270/4271)| **`Contract.term.type`**| _Equivalent_<br/>(12669/12670)| `Contract.term.type`| _Equivalent_<br/>(24691/24692)| `Contract.term.type`| _Equivalent_<br/>(39797/39798)| `Contract.term.type`
| `Contract.term.subType`| _Equivalent_<br/>(4272/4273)| **`Contract.term.subType`**| _Equivalent_<br/>(12671/12672)| `Contract.term.subType`| _Equivalent_<br/>(24693/24694)| `Contract.term.subType`| _Equivalent_<br/>(39799/39800)| `Contract.term.subType`
| `Contract.term.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(172)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(586)| **`Contract.term.topic`**| →→→→ _RelatedTo_ →→→→ <br/>(946)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1447)| `Contract.term.topic[x]`| _Equivalent_<br/>(24689/24690)| `Contract.term.topic[x]`| _Equivalent_<br/>(39795/39796)| `Contract.term.topic[x]`
| `Contract.term.action`| _Equivalent_<br/>(4274/4275)| **`Contract.term.action`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12673)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12674)| `Contract.term.action`| _Equivalent_<br/>(24843/24844)| `Contract.term.action`| _Equivalent_<br/>(39949/39950)| `Contract.term.action`
| `Contract.term.actionReason`| _Equivalent_<br/>(4276/4277)| **`Contract.term.actionReason`**| | | | | | | 
| | | **`Contract.term.securityLabel`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12675)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12676)| `Contract.term.securityLabel`| _Equivalent_<br/>(24697/24698)| `Contract.term.securityLabel`| _Equivalent_<br/>(39803/39804)| `Contract.term.securityLabel`
| `Contract.term.actor`| _Equivalent_<br/>(169/583)| **`Contract.term.agent`**| | | | | | | 
| | | **`Contract.term.agent.id`**| | | | | | | 
| | | **`Contract.term.agent.extension`**| | | | | | | 
| | | **`Contract.term.agent.modifierExtension`**| | | | | | | 
| `Contract.term.actor.entity`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(170)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(584)| **`Contract.term.agent.actor`**| | | | | | | 
| `Contract.term.actor.role`| _Equivalent_<br/>(171/585)| **`Contract.term.agent.role`**| | | | | | | 
| `Contract.term.text`| _Equivalent_<br/>(4281/4282)| **`Contract.term.text`**| _Equivalent_<br/>(12681/12682)| `Contract.term.text`| _Equivalent_<br/>(24695/24696)| `Contract.term.text`| _Equivalent_<br/>(39801/39802)| `Contract.term.text`
| `Contract.term.valuedItem`| _Equivalent_<br/>(4283/4284)| **`Contract.term.valuedItem`**| | | | | | | 
| `Contract.term.valuedItem.id`| _Equivalent_<br/>(4285/4286)| **`Contract.term.valuedItem.id`**| | | | | | | 
| `Contract.term.valuedItem.extension`| _Equivalent_<br/>(4287/4288)| **`Contract.term.valuedItem.extension`**| | | | | | | 
| `Contract.term.valuedItem.modifierExtension`| _Equivalent_<br/>(4289/4290)| **`Contract.term.valuedItem.modifierExtension`**| | | | | | | 
| `Contract.term.valuedItem.entity[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4291)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4292)| **`Contract.term.valuedItem.entity[x]`**| | | | | | | 
| `Contract.term.valuedItem.identifier`| _Equivalent_<br/>(4293/4294)| **`Contract.term.valuedItem.identifier`**| | | | | | | 
| `Contract.term.valuedItem.effectiveTime`| _Equivalent_<br/>(4295/4296)| **`Contract.term.valuedItem.effectiveTime`**| | | | | | | 
| `Contract.term.valuedItem.quantity`| _Equivalent_<br/>(4297/4298)| **`Contract.term.valuedItem.quantity`**| | | | | | | 
| `Contract.term.valuedItem.unitPrice`| →→→→ _RelatedTo_ →→→→ <br/>(4299)<hr/>←←←← _RelatedTo_ ←←←← <br/>(4300)| **`Contract.term.valuedItem.unitPrice`**| | | | | | | 
| `Contract.term.valuedItem.factor`| _Equivalent_<br/>(4301/4302)| **`Contract.term.valuedItem.factor`**| | | | | | | 
| `Contract.term.valuedItem.points`| _Equivalent_<br/>(4303/4304)| **`Contract.term.valuedItem.points`**| | | | | | | 
| `Contract.term.valuedItem.net`| →→→→ _RelatedTo_ →→→→ <br/>(4305)<hr/>←←←← _RelatedTo_ ←←←← <br/>(4306)| **`Contract.term.valuedItem.net`**| | | | | | | 
| `Contract.term.group`| _Equivalent_<br/>(4307/4308)| **`Contract.term.group`**| _Equivalent_<br/>(12687/12688)| `Contract.term.group`| _Equivalent_<br/>(24903/24904)| `Contract.term.group`| _Equivalent_<br/>(40007/40008)| `Contract.term.group`
| `Contract.binding[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4309)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4310)| **`Contract.binding[x]`**| | | | | | | 
| `Contract.friendly`| _Equivalent_<br/>(4311/4312)| **`Contract.friendly`**| _Equivalent_<br/>(12689/12690)| `Contract.friendly`| _Equivalent_<br/>(24923/24924)| `Contract.friendly`| _Equivalent_<br/>(40027/40028)| `Contract.friendly`
| `Contract.friendly.id`| _Equivalent_<br/>(4313/4314)| **`Contract.friendly.id`**| _Equivalent_<br/>(12691/12692)| `Contract.friendly.id`| _Equivalent_<br/>(24925/24926)| `Contract.friendly.id`| _Equivalent_<br/>(40029/40030)| `Contract.friendly.id`
| `Contract.friendly.extension`| _Equivalent_<br/>(4315/4316)| **`Contract.friendly.extension`**| _Equivalent_<br/>(12693/12694)| `Contract.friendly.extension`| _Equivalent_<br/>(24927/24928)| `Contract.friendly.extension`| _Equivalent_<br/>(40031/40032)| `Contract.friendly.extension`
| `Contract.friendly.modifierExtension`| _Equivalent_<br/>(4317/4318)| **`Contract.friendly.modifierExtension`**| _Equivalent_<br/>(12695/12696)| `Contract.friendly.modifierExtension`| _Equivalent_<br/>(24929/24930)| `Contract.friendly.modifierExtension`| _Equivalent_<br/>(40033/40034)| `Contract.friendly.modifierExtension`
| `Contract.friendly.content[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4319)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4320)| **`Contract.friendly.content[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12697)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12698)| `Contract.friendly.content[x]`| _Equivalent_<br/>(24931/24932)| `Contract.friendly.content[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(40035)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40036)| `Contract.friendly.content[x]`
| `Contract.legal`| _Equivalent_<br/>(4321/4322)| **`Contract.legal`**| _Equivalent_<br/>(12699/12700)| `Contract.legal`| _Equivalent_<br/>(24933/24934)| `Contract.legal`| _Equivalent_<br/>(40037/40038)| `Contract.legal`
| `Contract.legal.id`| _Equivalent_<br/>(4323/4324)| **`Contract.legal.id`**| _Equivalent_<br/>(12701/12702)| `Contract.legal.id`| _Equivalent_<br/>(24935/24936)| `Contract.legal.id`| _Equivalent_<br/>(40039/40040)| `Contract.legal.id`
| `Contract.legal.extension`| _Equivalent_<br/>(4325/4326)| **`Contract.legal.extension`**| _Equivalent_<br/>(12703/12704)| `Contract.legal.extension`| _Equivalent_<br/>(24937/24938)| `Contract.legal.extension`| _Equivalent_<br/>(40041/40042)| `Contract.legal.extension`
| `Contract.legal.modifierExtension`| _Equivalent_<br/>(4327/4328)| **`Contract.legal.modifierExtension`**| _Equivalent_<br/>(12705/12706)| `Contract.legal.modifierExtension`| _Equivalent_<br/>(24939/24940)| `Contract.legal.modifierExtension`| _Equivalent_<br/>(40043/40044)| `Contract.legal.modifierExtension`
| `Contract.legal.content[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4329)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4330)| **`Contract.legal.content[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12707)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12708)| `Contract.legal.content[x]`| _Equivalent_<br/>(24941/24942)| `Contract.legal.content[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(40045)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40046)| `Contract.legal.content[x]`
| `Contract.rule`| _Equivalent_<br/>(4331/4332)| **`Contract.rule`**| _Equivalent_<br/>(12709/12710)| `Contract.rule`| _Equivalent_<br/>(24943/24944)| `Contract.rule`| _Equivalent_<br/>(40047/40048)| `Contract.rule`
| `Contract.rule.id`| _Equivalent_<br/>(4333/4334)| **`Contract.rule.id`**| _Equivalent_<br/>(12711/12712)| `Contract.rule.id`| _Equivalent_<br/>(24945/24946)| `Contract.rule.id`| _Equivalent_<br/>(40049/40050)| `Contract.rule.id`
| `Contract.rule.extension`| _Equivalent_<br/>(4335/4336)| **`Contract.rule.extension`**| _Equivalent_<br/>(12713/12714)| `Contract.rule.extension`| _Equivalent_<br/>(24947/24948)| `Contract.rule.extension`| _Equivalent_<br/>(40051/40052)| `Contract.rule.extension`
| `Contract.rule.modifierExtension`| _Equivalent_<br/>(4337/4338)| **`Contract.rule.modifierExtension`**| _Equivalent_<br/>(12715/12716)| `Contract.rule.modifierExtension`| _Equivalent_<br/>(24949/24950)| `Contract.rule.modifierExtension`| _Equivalent_<br/>(40053/40054)| `Contract.rule.modifierExtension`
| `Contract.rule.content[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(4339)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(4340)| **`Contract.rule.content[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(12717)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(12718)| `Contract.rule.content[x]`| _Equivalent_<br/>(24951/24952)| `Contract.rule.content[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(40055)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40056)| `Contract.rule.content[x]`
| *86 of 92 elements used* | | *98 of 98 elements used* | | *57 of 183 elements used* | | *57 of 183 elements used* | | *57 of 181 elements used* 

