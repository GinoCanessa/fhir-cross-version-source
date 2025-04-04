Comparison of 
Generated at Friday, April 4, 2025 2:58:34 PM

### DiagnosticOrder

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | DiagnosticOrder |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/DiagnosticOrder` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for DiagnosticOrder Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `69` |
| Database Snapshot Count | `36` |
| Database Differential Count | `22` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `DiagnosticOrder` | `DiagnosticOrder` | `DiagnosticOrder` | DiagnosticOrder | A request for a diagnostic service | 0..* | DiagnosticOrder |  |  |
| `DiagnosticOrder.contained` | `DiagnosticOrder.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `DiagnosticOrder.encounter` | `DiagnosticOrder.encounter` | `encounter` |  | The encounter that this diagnostic order is associated with | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `DiagnosticOrder.event` | `DiagnosticOrder.event` | `event` |  | A list of events of interest in the lifecycle | 0..* | BackboneElement |  |  |
| `DiagnosticOrder.event.actor` | `DiagnosticOrder.event.actor` | `actor` |  | Who recorded or did this | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `DiagnosticOrder.event.dateTime` | `DiagnosticOrder.event.dateTime` | `dateTime` |  | The date at which the event happened | 1..1 | dateTime |  |  |
| `DiagnosticOrder.event.description` | `DiagnosticOrder.event.description` | `description` |  | More information about the event and its context | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/diagnostic-order-event` |
| `DiagnosticOrder.event.extension` | `DiagnosticOrder.event.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `DiagnosticOrder.event.id` | `DiagnosticOrder.event.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `DiagnosticOrder.event.modifierExtension` | `DiagnosticOrder.event.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DiagnosticOrder.event.status` | `DiagnosticOrder.event.status` | `status` |  | proposed \| draft \| planned \| requested \| received \| accepted \| in-progress \| review \| completed \| cancelled \| suspended \| rejected \| failed | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/diagnostic-order-status` |
| `DiagnosticOrder.extension` | `DiagnosticOrder.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `DiagnosticOrder.id` | `DiagnosticOrder.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `DiagnosticOrder.identifier` | `DiagnosticOrder.identifier` | `identifier` |  | Identifiers assigned to this order | 0..* | Identifier |  |  |
| `DiagnosticOrder.implicitRules` | `DiagnosticOrder.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `DiagnosticOrder.item` | `DiagnosticOrder.item` | `item` |  | The items the orderer requested | 0..* | BackboneElement |  |  |
| `DiagnosticOrder.item.bodySite` | `DiagnosticOrder.item.bodySite` | `bodySite` |  | Location of requested test (if applicable) | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/body-site` |
| `DiagnosticOrder.item.code` | `DiagnosticOrder.item.code` | `code` |  | Code to indicate the item (test or panel) being ordered | 1..1 | CodeableConcept | `Preferred` | `http://hl7.org/fhir/ValueSet/diagnostic-requests` |
| `DiagnosticOrder.item.event` | `DiagnosticOrder.item.event` | `event` |  | Events specific to this item | 0..* | DiagnosticOrder.event |  |  |
| `DiagnosticOrder.item.extension` | `DiagnosticOrder.item.extension` | `extension` |  | Additional Content defined by implementations | 0..* | Extension |  |  |
| `DiagnosticOrder.item.id` | `DiagnosticOrder.item.id` | `id` |  | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `DiagnosticOrder.item.modifierExtension` | `DiagnosticOrder.item.modifierExtension` | `modifierExtension` |  | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DiagnosticOrder.item.specimen` | `DiagnosticOrder.item.specimen` | `specimen` |  | If this item relates to specific specimens | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Specimen) |  |  |
| `DiagnosticOrder.item.status` | `DiagnosticOrder.item.status` | `status` |  | proposed \| draft \| planned \| requested \| received \| accepted \| in-progress \| review \| completed \| cancelled \| suspended \| rejected \| failed | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/diagnostic-order-status` |
| `DiagnosticOrder.language` | `DiagnosticOrder.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `DiagnosticOrder.meta` | `DiagnosticOrder.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `DiagnosticOrder.modifierExtension` | `DiagnosticOrder.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DiagnosticOrder.note` | `DiagnosticOrder.note` | `note` |  | Other notes and comments | 0..* | Annotation |  |  |
| `DiagnosticOrder.orderer` | `DiagnosticOrder.orderer` | `orderer` |  | Who ordered the test | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `DiagnosticOrder.priority` | `DiagnosticOrder.priority` | `priority` |  | routine \| urgent \| stat \| asap | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/diagnostic-order-priority` |
| `DiagnosticOrder.reason` | `DiagnosticOrder.reason` | `reason` |  | Explanation/Justification for test | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/condition-code` |
| `DiagnosticOrder.specimen` | `DiagnosticOrder.specimen` | `specimen` |  | If the whole order relates to specific specimens | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Specimen) |  |  |
| `DiagnosticOrder.status` | `DiagnosticOrder.status` | `status` |  | proposed \| draft \| planned \| requested \| received \| accepted \| in-progress \| review \| completed \| cancelled \| suspended \| rejected \| failed | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/diagnostic-order-status` |
| `DiagnosticOrder.subject` | `DiagnosticOrder.subject` | `subject` |  | Who and/or what test is about | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `DiagnosticOrder.supportingInformation` | `DiagnosticOrder.supportingInformation` | `supportingInformation` |  | Additional clinical information | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Condition), Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference), Reference(http://hl7.org/fhir/StructureDefinition/Observation) |  |  |
| `DiagnosticOrder.text` | `DiagnosticOrder.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DiagnosticOrder](/docs/R2/Resources/DiagnosticOrder.md)<br/> `http://hl7.org/fhir/StructureDefinition/DiagnosticOrder\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `102`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `322`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ProcedureRequest](/docs/R3/Resources/ProcedureRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ProcedureRequest\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `515`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `707`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ServiceRequest](/docs/R4/Resources/ServiceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ServiceRequest\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1613`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1614`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ServiceRequest](/docs/R4B/Resources/ServiceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ServiceRequest\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1040`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1269`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ServiceRequest](/docs/R5/Resources/ServiceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ServiceRequest\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition DiagnosticOrder from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 DiagnosticOrder| Relationship | [R3 ProcedureRequest](/docs/R3/Resources/ProcedureRequest.md)| Relationship | [R4 ServiceRequest](/docs/R4/Resources/ServiceRequest.md)| Relationship | [R4B ServiceRequest](/docs/R4B/Resources/ServiceRequest.md)| Relationship | [R5 ServiceRequest](/docs/R5/Resources/ServiceRequest.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`DiagnosticOrder`**| | | | | | | | | 
| **`DiagnosticOrder.id`**| | | | | | | | | 
| **`DiagnosticOrder.meta`**| | | | | | | | | 
| **`DiagnosticOrder.implicitRules`**| | | | | | | | | 
| **`DiagnosticOrder.language`**| | | | | | | | | 
| **`DiagnosticOrder.text`**| | | | | | | | | 
| **`DiagnosticOrder.contained`**| | | | | | | | | 
| **`DiagnosticOrder.extension`**| | | | | | | | | 
| **`DiagnosticOrder.modifierExtension`**| | | | | | | | | 
| **`DiagnosticOrder.subject`**| | | | | | | | | 
| **`DiagnosticOrder.orderer`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(201)<hr/>←←←← _RelatedTo_ ←←←← <br/>(699)| `ProcedureRequest.requester.agent`| →→→→ _RelatedTo_ →→→→ <br/>(1239)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(17519)| `ServiceRequest.requester`| _Equivalent_<br/>(33108/33109)| `ServiceRequest.requester`| _Equivalent_<br/>(47351/47352)| `ServiceRequest.requester`
| **`DiagnosticOrder.identifier`**| | | | | | | | | 
| **`DiagnosticOrder.encounter`**| | | | | | | | | 
| **`DiagnosticOrder.reason`**| _Equivalent_<br/>(202/697)| `ProcedureRequest.reasonCode`| | | | | | | 
| **`DiagnosticOrder.supportingInformation`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(203)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(698)| `ProcedureRequest.reasonReference`| | | | | | | 
| **`DiagnosticOrder.specimen`**| | | | | | | | | 
| **`DiagnosticOrder.status`**| | | | | | | | | 
| **`DiagnosticOrder.priority`**| | | | | | | | | 
| **`DiagnosticOrder.event`**| | | | | | | | | 
| **`DiagnosticOrder.event.id`**| | | | | | | | | 
| **`DiagnosticOrder.event.extension`**| | | | | | | | | 
| **`DiagnosticOrder.event.modifierExtension`**| | | | | | | | | 
| **`DiagnosticOrder.event.status`**| | | | | | | | | 
| **`DiagnosticOrder.event.description`**| | | | | | | | | 
| **`DiagnosticOrder.event.dateTime`**| | | | | | | | | 
| **`DiagnosticOrder.event.actor`**| | | | | | | | | 
| **`DiagnosticOrder.item`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(195)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(694)| `ProcedureRequest`| | | | | | | 
| **`DiagnosticOrder.item.id`**| | | | | | | | | 
| **`DiagnosticOrder.item.extension`**| | | | | | | | | 
| **`DiagnosticOrder.item.modifierExtension`**| | | | | | | | | 
| **`DiagnosticOrder.item.code`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(197)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(696)| `ProcedureRequest.code`| | | | | | | 
| **`DiagnosticOrder.item.specimen`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(199)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(700)| `ProcedureRequest.specimen`| | | | | | | 
| **`DiagnosticOrder.item.bodySite`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(196)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(695)| `ProcedureRequest.bodySite`| | | | | | | 
| **`DiagnosticOrder.item.status`**| | | | | | | | | 
| **`DiagnosticOrder.item.event`**| | | | | | | | | 
| **`DiagnosticOrder.note`**| | | | | | | | | 
| *36 of 36 elements used* | | *7 of 40 elements used* <br/>remaining elements:<br/>`ProcedureRequest.asNeeded[x]`, `ProcedureRequest.authoredOn`, `ProcedureRequest.basedOn`, `ProcedureRequest.category`, `ProcedureRequest.contained`, `ProcedureRequest.context`, `ProcedureRequest.definition`, `ProcedureRequest.doNotPerform`, `ProcedureRequest.extension`, `ProcedureRequest.id`, `ProcedureRequest.identifier`, `ProcedureRequest.implicitRules`, `ProcedureRequest.intent`, `ProcedureRequest.language`, `ProcedureRequest.meta`, `ProcedureRequest.modifierExtension`, `ProcedureRequest.note`, `ProcedureRequest.occurrence[x]`, `ProcedureRequest.performer`, `ProcedureRequest.performerType`, `ProcedureRequest.priority`, `ProcedureRequest.relevantHistory`, `ProcedureRequest.replaces`, `ProcedureRequest.requester`, `ProcedureRequest.requester.extension`, `ProcedureRequest.requester.id`, `ProcedureRequest.requester.modifierExtension`, `ProcedureRequest.requester.onBehalfOf`, `ProcedureRequest.requisition`, `ProcedureRequest.status`, `ProcedureRequest.subject`, `ProcedureRequest.supportingInfo`, `ProcedureRequest.text`| | *1 of 42 elements used* <br/>remaining elements:<br/>`ServiceRequest`, `ServiceRequest.asNeeded[x]`, `ServiceRequest.authoredOn`, `ServiceRequest.basedOn`, `ServiceRequest.bodySite`, `ServiceRequest.category`, `ServiceRequest.code`, `ServiceRequest.contained`, `ServiceRequest.doNotPerform`, `ServiceRequest.encounter`, `ServiceRequest.extension`, `ServiceRequest.id`, `ServiceRequest.identifier`, `ServiceRequest.implicitRules`, `ServiceRequest.instantiatesCanonical`, `ServiceRequest.instantiatesUri`, `ServiceRequest.insurance`, `ServiceRequest.intent`, `ServiceRequest.language`, `ServiceRequest.locationCode`, `ServiceRequest.locationReference`, `ServiceRequest.meta`, `ServiceRequest.modifierExtension`, `ServiceRequest.note`, `ServiceRequest.occurrence[x]`, `ServiceRequest.orderDetail`, `ServiceRequest.patientInstruction`, `ServiceRequest.performer`, `ServiceRequest.performerType`, `ServiceRequest.priority`, `ServiceRequest.quantity[x]`, `ServiceRequest.reasonCode`, `ServiceRequest.reasonReference`, `ServiceRequest.relevantHistory`, `ServiceRequest.replaces`, `ServiceRequest.requisition`, `ServiceRequest.specimen`, `ServiceRequest.status`, `ServiceRequest.subject`, `ServiceRequest.supportingInfo`, `ServiceRequest.text`| | *1 of 42 elements used* <br/>remaining elements:<br/>`ServiceRequest`, `ServiceRequest.asNeeded[x]`, `ServiceRequest.authoredOn`, `ServiceRequest.basedOn`, `ServiceRequest.bodySite`, `ServiceRequest.category`, `ServiceRequest.code`, `ServiceRequest.contained`, `ServiceRequest.doNotPerform`, `ServiceRequest.encounter`, `ServiceRequest.extension`, `ServiceRequest.id`, `ServiceRequest.identifier`, `ServiceRequest.implicitRules`, `ServiceRequest.instantiatesCanonical`, `ServiceRequest.instantiatesUri`, `ServiceRequest.insurance`, `ServiceRequest.intent`, `ServiceRequest.language`, `ServiceRequest.locationCode`, `ServiceRequest.locationReference`, `ServiceRequest.meta`, `ServiceRequest.modifierExtension`, `ServiceRequest.note`, `ServiceRequest.occurrence[x]`, `ServiceRequest.orderDetail`, `ServiceRequest.patientInstruction`, `ServiceRequest.performer`, `ServiceRequest.performerType`, `ServiceRequest.priority`, `ServiceRequest.quantity[x]`, `ServiceRequest.reasonCode`, `ServiceRequest.reasonReference`, `ServiceRequest.relevantHistory`, `ServiceRequest.replaces`, `ServiceRequest.requisition`, `ServiceRequest.specimen`, `ServiceRequest.status`, `ServiceRequest.subject`, `ServiceRequest.supportingInfo`, `ServiceRequest.text`| | *1 of 56 elements used* <br/>remaining elements:<br/>`ServiceRequest`, `ServiceRequest.asNeeded[x]`, `ServiceRequest.authoredOn`, `ServiceRequest.basedOn`, `ServiceRequest.bodySite`, `ServiceRequest.bodyStructure`, `ServiceRequest.category`, `ServiceRequest.code`, `ServiceRequest.contained`, `ServiceRequest.doNotPerform`, `ServiceRequest.encounter`, `ServiceRequest.extension`, `ServiceRequest.focus`, `ServiceRequest.id`, `ServiceRequest.identifier`, `ServiceRequest.implicitRules`, `ServiceRequest.instantiatesCanonical`, `ServiceRequest.instantiatesUri`, `ServiceRequest.insurance`, `ServiceRequest.intent`, `ServiceRequest.language`, `ServiceRequest.location`, `ServiceRequest.meta`, `ServiceRequest.modifierExtension`, `ServiceRequest.note`, `ServiceRequest.occurrence[x]`, `ServiceRequest.orderDetail`, `ServiceRequest.orderDetail.extension`, `ServiceRequest.orderDetail.id`, `ServiceRequest.orderDetail.modifierExtension`, `ServiceRequest.orderDetail.parameter`, `ServiceRequest.orderDetail.parameter.code`, `ServiceRequest.orderDetail.parameter.extension`, `ServiceRequest.orderDetail.parameter.id`, `ServiceRequest.orderDetail.parameter.modifierExtension`, `ServiceRequest.orderDetail.parameter.value[x]`, `ServiceRequest.orderDetail.parameterFocus`, `ServiceRequest.patientInstruction`, `ServiceRequest.patientInstruction.extension`, `ServiceRequest.patientInstruction.id`, `ServiceRequest.patientInstruction.instruction[x]`, `ServiceRequest.patientInstruction.modifierExtension`, `ServiceRequest.performer`, `ServiceRequest.performerType`, `ServiceRequest.priority`, `ServiceRequest.quantity[x]`, `ServiceRequest.reason`, `ServiceRequest.relevantHistory`, `ServiceRequest.replaces`, `ServiceRequest.requisition`, `ServiceRequest.specimen`, `ServiceRequest.status`, `ServiceRequest.subject`, `ServiceRequest.supportingInfo`, `ServiceRequest.text`

