Comparison of 
Generated at Thursday, April 3, 2025 8:18:07 AM

### OrderResponse

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | OrderResponse |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/OrderResponse` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for OrderResponse Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `106` |
| Database Snapshot Count | `16` |
| Database Differential Count | `8` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `OrderResponse` | `OrderResponse` | `OrderResponse` | OrderResponse | A response to an order | 0..* | OrderResponse |  |  |
| `OrderResponse.contained` | `OrderResponse.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `OrderResponse.date` | `OrderResponse.date` | `date` |  | When the response was made | 0..1 | dateTime |  |  |
| `OrderResponse.description` | `OrderResponse.description` | `description` |  | Additional description of the response | 0..1 | string |  |  |
| `OrderResponse.extension` | `OrderResponse.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `OrderResponse.fulfillment` | `OrderResponse.fulfillment` | `fulfillment` |  | Details of the outcome of performing the order | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `OrderResponse.id` | `OrderResponse.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `OrderResponse.identifier` | `OrderResponse.identifier` | `identifier` |  | Identifiers assigned to this order by the orderer or by the receiver | 0..* | Identifier |  |  |
| `OrderResponse.implicitRules` | `OrderResponse.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `OrderResponse.language` | `OrderResponse.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `OrderResponse.meta` | `OrderResponse.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `OrderResponse.modifierExtension` | `OrderResponse.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `OrderResponse.orderStatus` | `OrderResponse.orderStatus` | `orderStatus` |  | pending \| review \| rejected \| error \| accepted \| cancelled \| replaced \| aborted \| completed | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/order-status` |
| `OrderResponse.request` | `OrderResponse.request` | `request` |  | The order that this is a response to | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Order) |  |  |
| `OrderResponse.text` | `OrderResponse.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `OrderResponse.who` | `OrderResponse.who` | `who` |  | Who made the response | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [OrderResponse](/docs/R2/Resources/OrderResponse.md)<br/> `http://hl7.org/fhir/StructureDefinition/OrderResponse\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `136`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `302`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Task](/docs/R3/Resources/Task.md)<br/> `http://hl7.org/fhir/StructureDefinition/Task\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `524`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `718`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Task](/docs/R4/Resources/Task.md)<br/> `http://hl7.org/fhir/StructureDefinition/Task\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1633`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1634`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Task](/docs/R4B/Resources/Task.md)<br/> `http://hl7.org/fhir/StructureDefinition/Task\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1053`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1282`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Task](/docs/R5/Resources/Task.md)<br/> `http://hl7.org/fhir/StructureDefinition/Task\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition OrderResponse from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 OrderResponse| Relationship | [R3 Task](/docs/R3/Resources/Task.md)| Relationship | [R4 Task](/docs/R4/Resources/Task.md)| Relationship | [R4B Task](/docs/R4B/Resources/Task.md)| Relationship | [R5 Task](/docs/R5/Resources/Task.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`OrderResponse`**| | | | | | | | | 
| **`OrderResponse.id`**| | | | | | | | | 
| **`OrderResponse.meta`**| | | | | | | | | 
| **`OrderResponse.implicitRules`**| | | | | | | | | 
| **`OrderResponse.language`**| | | | | | | | | 
| **`OrderResponse.text`**| | | | | | | | | 
| **`OrderResponse.contained`**| | | | | | | | | 
| **`OrderResponse.extension`**| | | | | | | | | 
| **`OrderResponse.modifierExtension`**| | | | | | | | | 
| **`OrderResponse.identifier`**| | | | | | | | | 
| **`OrderResponse.request`**| →→→→ _RelatedTo_ →→→→ <br/>(315)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(6861)| `Task.basedOn`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(19192)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(19193)| `Task.basedOn`| _Equivalent_<br/>(34084/34085)| `Task.basedOn`| _Equivalent_<br/>(48507/48508)| `Task.basedOn`
| **`OrderResponse.date`**| _Equivalent_<br/>(312/6862)| `Task.authoredOn`| _Equivalent_<br/>(19218/19219)| `Task.authoredOn`| _Equivalent_<br/>(34112/34113)| `Task.authoredOn`| _Equivalent_<br/>(48535/48536)| `Task.authoredOn`
| **`OrderResponse.who`**| | | | | | | | | 
| **`OrderResponse.orderStatus`**| | | | | | | | | 
| **`OrderResponse.description`**| | | | | | | | | 
| **`OrderResponse.fulfillment`**| | | | | | | | | 
| *16 of 16 elements used* | | *2 of 57 elements used* <br/>remaining elements:<br/>`Task`, `Task.businessStatus`, `Task.code`, `Task.contained`, `Task.context`, `Task.definition[x]`, `Task.description`, `Task.executionPeriod`, `Task.extension`, `Task.focus`, `Task.for`, `Task.groupIdentifier`, `Task.id`, `Task.identifier`, `Task.implicitRules`, `Task.input`, `Task.input.extension`, `Task.input.id`, `Task.input.modifierExtension`, `Task.input.type`, `Task.input.value[x]`, `Task.intent`, `Task.language`, `Task.lastModified`, `Task.meta`, `Task.modifierExtension`, `Task.note`, `Task.output`, `Task.output.extension`, `Task.output.id`, `Task.output.modifierExtension`, `Task.output.type`, `Task.output.value[x]`, `Task.owner`, `Task.partOf`, `Task.performerType`, `Task.priority`, `Task.reason`, `Task.relevantHistory`, `Task.requester`, `Task.requester.agent`, `Task.requester.extension`, `Task.requester.id`, `Task.requester.modifierExtension`, `Task.requester.onBehalfOf`, `Task.restriction`, `Task.restriction.extension`, `Task.restriction.id`, `Task.restriction.modifierExtension`, `Task.restriction.period`, `Task.restriction.recipient`, `Task.restriction.repetitions`, `Task.status`, `Task.statusReason`, `Task.text`| | *2 of 56 elements used* <br/>remaining elements:<br/>`Task`, `Task.businessStatus`, `Task.code`, `Task.contained`, `Task.description`, `Task.encounter`, `Task.executionPeriod`, `Task.extension`, `Task.focus`, `Task.for`, `Task.groupIdentifier`, `Task.id`, `Task.identifier`, `Task.implicitRules`, `Task.input`, `Task.input.extension`, `Task.input.id`, `Task.input.modifierExtension`, `Task.input.type`, `Task.input.value[x]`, `Task.instantiatesCanonical`, `Task.instantiatesUri`, `Task.insurance`, `Task.intent`, `Task.language`, `Task.lastModified`, `Task.location`, `Task.meta`, `Task.modifierExtension`, `Task.note`, `Task.output`, `Task.output.extension`, `Task.output.id`, `Task.output.modifierExtension`, `Task.output.type`, `Task.output.value[x]`, `Task.owner`, `Task.partOf`, `Task.performerType`, `Task.priority`, `Task.reasonCode`, `Task.reasonReference`, `Task.relevantHistory`, `Task.requester`, `Task.restriction`, `Task.restriction.extension`, `Task.restriction.id`, `Task.restriction.modifierExtension`, `Task.restriction.period`, `Task.restriction.recipient`, `Task.restriction.repetitions`, `Task.status`, `Task.statusReason`, `Task.text`| | *2 of 56 elements used* <br/>remaining elements:<br/>`Task`, `Task.businessStatus`, `Task.code`, `Task.contained`, `Task.description`, `Task.encounter`, `Task.executionPeriod`, `Task.extension`, `Task.focus`, `Task.for`, `Task.groupIdentifier`, `Task.id`, `Task.identifier`, `Task.implicitRules`, `Task.input`, `Task.input.extension`, `Task.input.id`, `Task.input.modifierExtension`, `Task.input.type`, `Task.input.value[x]`, `Task.instantiatesCanonical`, `Task.instantiatesUri`, `Task.insurance`, `Task.intent`, `Task.language`, `Task.lastModified`, `Task.location`, `Task.meta`, `Task.modifierExtension`, `Task.note`, `Task.output`, `Task.output.extension`, `Task.output.id`, `Task.output.modifierExtension`, `Task.output.type`, `Task.output.value[x]`, `Task.owner`, `Task.partOf`, `Task.performerType`, `Task.priority`, `Task.reasonCode`, `Task.reasonReference`, `Task.relevantHistory`, `Task.requester`, `Task.restriction`, `Task.restriction.extension`, `Task.restriction.id`, `Task.restriction.modifierExtension`, `Task.restriction.period`, `Task.restriction.recipient`, `Task.restriction.repetitions`, `Task.status`, `Task.statusReason`, `Task.text`| | *2 of 63 elements used* <br/>remaining elements:<br/>`Task`, `Task.businessStatus`, `Task.code`, `Task.contained`, `Task.description`, `Task.doNotPerform`, `Task.encounter`, `Task.executionPeriod`, `Task.extension`, `Task.focus`, `Task.for`, `Task.groupIdentifier`, `Task.id`, `Task.identifier`, `Task.implicitRules`, `Task.input`, `Task.input.extension`, `Task.input.id`, `Task.input.modifierExtension`, `Task.input.type`, `Task.input.value[x]`, `Task.instantiatesCanonical`, `Task.instantiatesUri`, `Task.insurance`, `Task.intent`, `Task.language`, `Task.lastModified`, `Task.location`, `Task.meta`, `Task.modifierExtension`, `Task.note`, `Task.output`, `Task.output.extension`, `Task.output.id`, `Task.output.modifierExtension`, `Task.output.type`, `Task.output.value[x]`, `Task.owner`, `Task.partOf`, `Task.performer`, `Task.performer.actor`, `Task.performer.extension`, `Task.performer.function`, `Task.performer.id`, `Task.performer.modifierExtension`, `Task.priority`, `Task.reason`, `Task.relevantHistory`, `Task.requestedPerformer`, `Task.requestedPeriod`, `Task.requester`, `Task.restriction`, `Task.restriction.extension`, `Task.restriction.id`, `Task.restriction.modifierExtension`, `Task.restriction.period`, `Task.restriction.recipient`, `Task.restriction.repetitions`, `Task.status`, `Task.statusReason`, `Task.text`

