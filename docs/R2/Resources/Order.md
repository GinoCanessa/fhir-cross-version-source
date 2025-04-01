Comparison of 
Generated at Tuesday, April 1, 2025 1:39:08 PM

### Order

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | Order |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/Order` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for Order Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `105` |
| Database Snapshot Count | `22` |
| Database Differential Count | `11` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `Order` | `Order` | `Order` | Order | A request to perform an action | 0..* | Order |  |  |
| `Order.contained` | `Order.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `Order.date` | `Order.date` | `date` |  | When the order was made | 0..1 | dateTime |  |  |
| `Order.detail` | `Order.detail` | `detail` |  | What action is being ordered | 1..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `Order.extension` | `Order.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Order.id` | `Order.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `Order.identifier` | `Order.identifier` | `identifier` |  | Identifiers assigned to this order by the orderer or by the receiver | 0..* | Identifier |  |  |
| `Order.implicitRules` | `Order.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `Order.language` | `Order.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `Order.meta` | `Order.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `Order.modifierExtension` | `Order.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Order.reason[x]` | `Order.reason[x]` | `reason[x]` |  | Text - why the order was made | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Resource) | `Example` |  |
| `Order.source` | `Order.source` | `source` |  | Who initiated the order | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `Order.subject` | `Order.subject` | `subject` |  | Patient this order is about | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Substance) |  |  |
| `Order.target` | `Order.target` | `target` |  | Who is intended to fulfill the order | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `Order.text` | `Order.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `Order.when` | `Order.when` | `when` |  | When order should be fulfilled | 0..1 | BackboneElement |  |  |
| `Order.when.code` | `Order.when.code` | `code` |  | Code specifies when request should be done. The code may simply be a priority code | 0..1 | CodeableConcept | `Example` |  |
| `Order.when.extension` | `Order.when.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `Order.when.id` | `Order.when.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `Order.when.modifierExtension` | `Order.when.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `Order.when.schedule` | `Order.when.schedule` | `schedule` |  | A formal schedule | 0..1 | Timing |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [Order](/docs/R2/Resources/Order.md)<br/> `http://hl7.org/fhir/StructureDefinition/Order\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `135`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `301`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Task](/docs/R3/Resources/Task.md)<br/> `http://hl7.org/fhir/StructureDefinition/Task\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `524`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `718`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Task](/docs/R4/Resources/Task.md)<br/> `http://hl7.org/fhir/StructureDefinition/Task\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1633`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1634`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Task](/docs/R4B/Resources/Task.md)<br/> `http://hl7.org/fhir/StructureDefinition/Task\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1053`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1282`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Task](/docs/R5/Resources/Task.md)<br/> `http://hl7.org/fhir/StructureDefinition/Task\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition Order from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 Order| Relationship | [R3 Task](/docs/R3/Resources/Task.md)| Relationship | [R4 Task](/docs/R4/Resources/Task.md)| Relationship | [R4B Task](/docs/R4B/Resources/Task.md)| Relationship | [R5 Task](/docs/R5/Resources/Task.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`Order`**| | | | | | | | | 
| **`Order.id`**| | | | | | | | | 
| **`Order.meta`**| | | | | | | | | 
| **`Order.implicitRules`**| | | | | | | | | 
| **`Order.language`**| | | | | | | | | 
| **`Order.text`**| | | | | | | | | 
| **`Order.contained`**| | | | | | | | | 
| **`Order.extension`**| | | | | | | | | 
| **`Order.modifierExtension`**| | | | | | | | | 
| **`Order.identifier`**| | | | | | | | | 
| **`Order.date`**| _Equivalent_<br/>(304/774)| `Task.authoredOn`| _Equivalent_<br/>(19218/19219)| `Task.authoredOn`| _Equivalent_<br/>(34112/34113)| `Task.authoredOn`| _Equivalent_<br/>(48535/48536)| `Task.authoredOn`
| **`Order.subject`**| →→→→ _RelatedTo_ →→→→ <br/>(308)<hr/>←←←← _RelatedTo_ ←←←← <br/>(775)| `Task.focus`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19212)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19213)| `Task.focus`| _Equivalent_<br/>(34104/34105)| `Task.focus`| _Equivalent_<br/>(48527/48528)| `Task.focus`
| **`Order.source`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(307)<hr/>←←←← _RelatedTo_ ←←←← <br/>(777)| `Task.requester.agent`| →→→→ _RelatedTo_ →→→→ <br/>(1296)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1683)| `Task.requester`| _Equivalent_<br/>(34116/34117)| `Task.requester`| _Equivalent_<br/>(48539/48540)| `Task.requester`
| **`Order.target`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(309)<hr/>←←←← _RelatedTo_ ←←←← <br/>(778)| `Task.requester.agent`| →→→→ _RelatedTo_ →→→→ <br/>(1296)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1683)| `Task.requester`| _Equivalent_<br/>(34116/34117)| `Task.requester`| _Equivalent_<br/>(48539/48540)| `Task.requester`
| **`Order.reason[x]`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(306)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(776)| `Task.reason`| _Equivalent_<br/>(1295/1682)| `Task.reasonCode`| _Equivalent_<br/>(34124/34125)| `Task.reasonCode`| →→→→ _RelatedTo_ →→→→ <br/>(1954)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2190)| `Task.reason`
| **`Order.when`**| | | | | | | | | 
| **`Order.when.id`**| | | | | | | | | 
| **`Order.when.extension`**| | | | | | | | | 
| **`Order.when.modifierExtension`**| | | | | | | | | 
| **`Order.when.code`**| | | | | | | | | 
| **`Order.when.schedule`**| | | | | | | | | 
| **`Order.detail`**| | | | | | | | | 
| *22 of 22 elements used* | | *4 of 57 elements used* | | *4 of 56 elements used* | | *4 of 56 elements used* | | *4 of 63 elements used* 

