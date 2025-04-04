Comparison of 
Generated at Friday, April 4, 2025 2:58:41 PM

### ProcedureRequest

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | ProcedureRequest |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ProcedureRequest` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for ProcedureRequest Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `564` |
| Database Snapshot Count | `40` |
| Database Differential Count | `29` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ProcedureRequest` | `ProcedureRequest` | `ProcedureRequest` | ProcedureRequest | A request for a procedure or diagnostic to be performed | 0..* | ProcedureRequest |  |  |
| `ProcedureRequest.asNeeded[x]` | `ProcedureRequest.asNeeded[x]` | `asNeeded[x]` |  | Preconditions for procedure or diagnostic | 0..1 | boolean, CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/medication-as-needed-reason` |
| `ProcedureRequest.authoredOn` | `ProcedureRequest.authoredOn` | `authoredOn` |  | Date request signed | 0..1 | dateTime |  |  |
| `ProcedureRequest.basedOn` | `ProcedureRequest.basedOn` | `basedOn` |  | What request fulfills | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `ProcedureRequest.bodySite` | `ProcedureRequest.bodySite` | `bodySite` |  | Location on Body | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/body-site` |
| `ProcedureRequest.category` | `ProcedureRequest.category` | `category` |  | Classification of procedure | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/procedure-category` |
| `ProcedureRequest.code` | `ProcedureRequest.code` | `code` |  | What is being requested/ordered | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/procedure-code` |
| `ProcedureRequest.contained` | `ProcedureRequest.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ProcedureRequest.context` | `ProcedureRequest.context` | `context` |  | Encounter or Episode during which request was created | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter), Reference(http://hl7.org/fhir/StructureDefinition/EpisodeOfCare) |  |  |
| `ProcedureRequest.definition` | `ProcedureRequest.definition` | `definition` |  | Protocol or definition | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ActivityDefinition), Reference(http://hl7.org/fhir/StructureDefinition/PlanDefinition) |  |  |
| `ProcedureRequest.doNotPerform` | `ProcedureRequest.doNotPerform` | `doNotPerform` |  | True if procedure should not be performed | 0..1 | boolean |  |  |
| `ProcedureRequest.extension` | `ProcedureRequest.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ProcedureRequest.id` | `ProcedureRequest.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ProcedureRequest.identifier` | `ProcedureRequest.identifier` | `identifier` |  | Identifiers assigned to this order | 0..* | Identifier |  |  |
| `ProcedureRequest.implicitRules` | `ProcedureRequest.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ProcedureRequest.intent` | `ProcedureRequest.intent` | `intent` |  | proposal \| plan \| order + | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/request-intent` |
| `ProcedureRequest.language` | `ProcedureRequest.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `ProcedureRequest.meta` | `ProcedureRequest.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ProcedureRequest.modifierExtension` | `ProcedureRequest.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ProcedureRequest.note` | `ProcedureRequest.note` | `note` |  | Comments | 0..* | Annotation |  |  |
| `ProcedureRequest.occurrence[x]` | `ProcedureRequest.occurrence[x]` | `occurrence[x]` |  | When procedure should occur | 0..1 | dateTime, Period, Timing |  |  |
| `ProcedureRequest.performer` | `ProcedureRequest.performer` | `performer` |  | Requested perfomer | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/HealthcareService), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `ProcedureRequest.performerType` | `ProcedureRequest.performerType` | `performerType` |  | Performer role | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/participant-role` |
| `ProcedureRequest.priority` | `ProcedureRequest.priority` | `priority` |  | routine \| urgent \| asap \| stat | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/request-priority` |
| `ProcedureRequest.reasonCode` | `ProcedureRequest.reasonCode` | `reasonCode` |  | Explanation/Justification for test | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/procedure-reason` |
| `ProcedureRequest.reasonReference` | `ProcedureRequest.reasonReference` | `reasonReference` |  | Explanation/Justification for test | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Condition), Reference(http://hl7.org/fhir/StructureDefinition/Observation) |  |  |
| `ProcedureRequest.relevantHistory` | `ProcedureRequest.relevantHistory` | `relevantHistory` |  | Request provenance | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Provenance) |  |  |
| `ProcedureRequest.replaces` | `ProcedureRequest.replaces` | `replaces` |  | What request replaces | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `ProcedureRequest.requester` | `ProcedureRequest.requester` | `requester` |  | Who/what is requesting procedure or diagnostic | 0..1 | BackboneElement |  |  |
| `ProcedureRequest.requester.agent` | `ProcedureRequest.requester.agent` | `agent` |  | Individual making the request | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `ProcedureRequest.requester.extension` | `ProcedureRequest.requester.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ProcedureRequest.requester.id` | `ProcedureRequest.requester.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ProcedureRequest.requester.modifierExtension` | `ProcedureRequest.requester.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ProcedureRequest.requester.onBehalfOf` | `ProcedureRequest.requester.onBehalfOf` | `onBehalfOf` |  | Organization agent is acting for | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `ProcedureRequest.requisition` | `ProcedureRequest.requisition` | `requisition` |  | Composite Request ID | 0..1 | Identifier |  |  |
| `ProcedureRequest.specimen` | `ProcedureRequest.specimen` | `specimen` |  | Procedure Samples | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Specimen) |  |  |
| `ProcedureRequest.status` | `ProcedureRequest.status` | `status` |  | draft \| active \| suspended \| completed \| entered-in-error \| cancelled | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/request-status` |
| `ProcedureRequest.subject` | `ProcedureRequest.subject` | `subject` |  | Individual the service is ordered for | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `ProcedureRequest.supportingInfo` | `ProcedureRequest.supportingInfo` | `supportingInfo` |  | Additional clinical information | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `ProcedureRequest.text` | `ProcedureRequest.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DiagnosticOrder](/docs/R2/Resources/DiagnosticOrder.md)<br/> `http://hl7.org/fhir/StructureDefinition/DiagnosticOrder\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `102`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `321`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ProcedureRequest](/docs/R3/Resources/ProcedureRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ProcedureRequest\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `515`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `707`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ServiceRequest](/docs/R4/Resources/ServiceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ServiceRequest\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1613`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1614`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ServiceRequest](/docs/R4B/Resources/ServiceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ServiceRequest\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1040`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1269`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ServiceRequest](/docs/R5/Resources/ServiceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ServiceRequest\|5.0.0` 
| [ProcedureRequest](/docs/R2/Resources/ProcedureRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ProcedureRequest\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `155`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `321`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ProcedureRequest](/docs/R3/Resources/ProcedureRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ProcedureRequest\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `515`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `707`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ServiceRequest](/docs/R4/Resources/ServiceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ServiceRequest\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1613`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1614`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ServiceRequest](/docs/R4B/Resources/ServiceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ServiceRequest\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1040`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1269`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ServiceRequest](/docs/R5/Resources/ServiceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ServiceRequest\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ProcedureRequest from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 DiagnosticOrder](/docs/R2/Resources/DiagnosticOrder.md)| Relationship | R3 ProcedureRequest| Relationship | [R4 ServiceRequest](/docs/R4/Resources/ServiceRequest.md)| Relationship | [R4B ServiceRequest](/docs/R4B/Resources/ServiceRequest.md)| Relationship | [R5 ServiceRequest](/docs/R5/Resources/ServiceRequest.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `ProcedureRequest`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7307)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7308)| **`ProcedureRequest`**| | | | | | | 
| `ProcedureRequest.id`| _Equivalent_<br/>(7309/7310)| **`ProcedureRequest.id`**| | | | | | | 
| `ProcedureRequest.meta`| _Equivalent_<br/>(7311/7312)| **`ProcedureRequest.meta`**| | | | | | | 
| `ProcedureRequest.implicitRules`| _Equivalent_<br/>(7313/7314)| **`ProcedureRequest.implicitRules`**| | | | | | | 
| `ProcedureRequest.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7315)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7316)| **`ProcedureRequest.language`**| | | | | | | 
| `ProcedureRequest.text`| _Equivalent_<br/>(7317/7318)| **`ProcedureRequest.text`**| | | | | | | 
| `ProcedureRequest.contained`| _Equivalent_<br/>(7319/7320)| **`ProcedureRequest.contained`**| | | | | | | 
| `ProcedureRequest.extension`| _Equivalent_<br/>(7321/7322)| **`ProcedureRequest.extension`**| | | | | | | 
| `ProcedureRequest.modifierExtension`| _Equivalent_<br/>(7323/7324)| **`ProcedureRequest.modifierExtension`**| | | | | | | 
| `ProcedureRequest.identifier`| _Equivalent_<br/>(7325/7326)| **`ProcedureRequest.identifier`**| | | | | | | 
| | | **`ProcedureRequest.definition`**| | | | | | | 
| | | **`ProcedureRequest.basedOn`**| | | | | | | 
| | | **`ProcedureRequest.replaces`**| | | | | | | 
| | | **`ProcedureRequest.requisition`**| | | | | | | 
| `ProcedureRequest.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7335)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7336)| **`ProcedureRequest.status`**| | | | | | | 
| | | **`ProcedureRequest.intent`**| | | | | | | 
| `ProcedureRequest.priority`| _Equivalent_<br/>(7340/7341)| **`ProcedureRequest.priority`**| | | | | | | 
| | | **`ProcedureRequest.doNotPerform`**| | | | | | | 
| | | **`ProcedureRequest.category`**| | | | | | | 
| `ProcedureRequest.code`| _Equivalent_<br/>(7329/7330)| **`ProcedureRequest.code`**| | | | | | | 
| `ProcedureRequest.subject`| →→→→ _RelatedTo_ →→→→ <br/>(7327)<hr/>←←←← _RelatedTo_ ←←←← <br/>(7328)| **`ProcedureRequest.subject`**| | | | | | | 
| `ProcedureRequest.encounter`| →→→→ _RelatedTo_ →→→→ <br/>(340)<hr/>←←←← _RelatedTo_ ←←←← <br/>(793)| **`ProcedureRequest.context`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1237)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17511)| `ServiceRequest.encounter`| _Equivalent_<br/>(33100/33101)| `ServiceRequest.encounter`| _Equivalent_<br/>(47343/47344)| `ServiceRequest.encounter`
| `ProcedureRequest.scheduled[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(346)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(792)| **`ProcedureRequest.occurrence[x]`**| | | | | | | 
| `ProcedureRequest.asNeeded[x]`| _Equivalent_<br/>(7337/7338)| **`ProcedureRequest.asNeeded[x]`**| | | | | | | 
| `ProcedureRequest.orderedOn`| _Equivalent_<br/>(342/795)| **`ProcedureRequest.authoredOn`**| | | | | | | 
| | | **`ProcedureRequest.requester`**| | | | | | | 
| | | **`ProcedureRequest.requester.id`**| | | | | | | 
| | | **`ProcedureRequest.requester.extension`**| | | | | | | 
| | | **`ProcedureRequest.requester.modifierExtension`**| | | | | | | 
| `ProcedureRequest.orderer`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(343)<hr/>←←←← _RelatedTo_ ←←←← <br/>(7339)| **`ProcedureRequest.requester.agent`**| →→→→ _RelatedTo_ →→→→ <br/>(1239)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(17519)| `ServiceRequest.requester`| _Equivalent_<br/>(33108/33109)| `ServiceRequest.requester`| _Equivalent_<br/>(47351/47352)| `ServiceRequest.requester`
| | | **`ProcedureRequest.requester.onBehalfOf`**| | | | | | | 
| | | **`ProcedureRequest.performerType`**| | | | | | | 
| `ProcedureRequest.performer`| →→→→ _RelatedTo_ →→→→ <br/>(7333)<hr/>←←←← _RelatedTo_ ←←←← <br/>(7334)| **`ProcedureRequest.performer`**| | | | | | | 
| `ProcedureRequest.reason[x]`| →→→→ _RelatedTo_ →→→→ <br/>(344)<hr/>←←←← _RelatedTo_ ←←←← <br/>(790)| **`ProcedureRequest.reasonCode`**| | | | | | | 
| `ProcedureRequest.reason[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(345)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(791)| **`ProcedureRequest.reasonReference`**| | | | | | | 
| | | **`ProcedureRequest.supportingInfo`**| | | | | | | 
| | | **`ProcedureRequest.specimen`**| | | | | | | 
| `ProcedureRequest.bodySite`| _Equivalent_<br/>(7331/7332)| **`ProcedureRequest.bodySite`**| | | | | | | 
| `ProcedureRequest.notes`| _Equivalent_<br/>(341/794)| **`ProcedureRequest.note`**| | | | | | | 
| | | **`ProcedureRequest.relevantHistory`**| | | | | | | 
| *23 of 36 elements used* <br/>remaining elements:<br/>`DiagnosticOrder`, `DiagnosticOrder.contained`, `DiagnosticOrder.encounter`, `DiagnosticOrder.event`, `DiagnosticOrder.event.actor`, `DiagnosticOrder.event.dateTime`, `DiagnosticOrder.event.description`, `DiagnosticOrder.event.extension`, `DiagnosticOrder.event.id`, `DiagnosticOrder.event.modifierExtension`, `DiagnosticOrder.event.status`, `DiagnosticOrder.extension`, `DiagnosticOrder.id`, `DiagnosticOrder.identifier`, `DiagnosticOrder.implicitRules`, `DiagnosticOrder.item`, `DiagnosticOrder.item.bodySite`, `DiagnosticOrder.item.code`, `DiagnosticOrder.item.event`, `DiagnosticOrder.item.extension`, `DiagnosticOrder.item.id`, `DiagnosticOrder.item.modifierExtension`, `DiagnosticOrder.item.specimen`, `DiagnosticOrder.item.status`, `DiagnosticOrder.language`, `DiagnosticOrder.meta`, `DiagnosticOrder.modifierExtension`, `DiagnosticOrder.note`, `DiagnosticOrder.orderer`, `DiagnosticOrder.priority`, `DiagnosticOrder.reason`, `DiagnosticOrder.specimen`, `DiagnosticOrder.status`, `DiagnosticOrder.subject`, `DiagnosticOrder.supportingInformation`, `DiagnosticOrder.text`| | *40 of 40 elements used* | | *2 of 42 elements used* <br/>remaining elements:<br/>`ServiceRequest`, `ServiceRequest.asNeeded[x]`, `ServiceRequest.authoredOn`, `ServiceRequest.basedOn`, `ServiceRequest.bodySite`, `ServiceRequest.category`, `ServiceRequest.code`, `ServiceRequest.contained`, `ServiceRequest.doNotPerform`, `ServiceRequest.extension`, `ServiceRequest.id`, `ServiceRequest.identifier`, `ServiceRequest.implicitRules`, `ServiceRequest.instantiatesCanonical`, `ServiceRequest.instantiatesUri`, `ServiceRequest.insurance`, `ServiceRequest.intent`, `ServiceRequest.language`, `ServiceRequest.locationCode`, `ServiceRequest.locationReference`, `ServiceRequest.meta`, `ServiceRequest.modifierExtension`, `ServiceRequest.note`, `ServiceRequest.occurrence[x]`, `ServiceRequest.orderDetail`, `ServiceRequest.patientInstruction`, `ServiceRequest.performer`, `ServiceRequest.performerType`, `ServiceRequest.priority`, `ServiceRequest.quantity[x]`, `ServiceRequest.reasonCode`, `ServiceRequest.reasonReference`, `ServiceRequest.relevantHistory`, `ServiceRequest.replaces`, `ServiceRequest.requisition`, `ServiceRequest.specimen`, `ServiceRequest.status`, `ServiceRequest.subject`, `ServiceRequest.supportingInfo`, `ServiceRequest.text`| | *2 of 42 elements used* <br/>remaining elements:<br/>`ServiceRequest`, `ServiceRequest.asNeeded[x]`, `ServiceRequest.authoredOn`, `ServiceRequest.basedOn`, `ServiceRequest.bodySite`, `ServiceRequest.category`, `ServiceRequest.code`, `ServiceRequest.contained`, `ServiceRequest.doNotPerform`, `ServiceRequest.extension`, `ServiceRequest.id`, `ServiceRequest.identifier`, `ServiceRequest.implicitRules`, `ServiceRequest.instantiatesCanonical`, `ServiceRequest.instantiatesUri`, `ServiceRequest.insurance`, `ServiceRequest.intent`, `ServiceRequest.language`, `ServiceRequest.locationCode`, `ServiceRequest.locationReference`, `ServiceRequest.meta`, `ServiceRequest.modifierExtension`, `ServiceRequest.note`, `ServiceRequest.occurrence[x]`, `ServiceRequest.orderDetail`, `ServiceRequest.patientInstruction`, `ServiceRequest.performer`, `ServiceRequest.performerType`, `ServiceRequest.priority`, `ServiceRequest.quantity[x]`, `ServiceRequest.reasonCode`, `ServiceRequest.reasonReference`, `ServiceRequest.relevantHistory`, `ServiceRequest.replaces`, `ServiceRequest.requisition`, `ServiceRequest.specimen`, `ServiceRequest.status`, `ServiceRequest.subject`, `ServiceRequest.supportingInfo`, `ServiceRequest.text`| | *2 of 56 elements used* <br/>remaining elements:<br/>`ServiceRequest`, `ServiceRequest.asNeeded[x]`, `ServiceRequest.authoredOn`, `ServiceRequest.basedOn`, `ServiceRequest.bodySite`, `ServiceRequest.bodyStructure`, `ServiceRequest.category`, `ServiceRequest.code`, `ServiceRequest.contained`, `ServiceRequest.doNotPerform`, `ServiceRequest.extension`, `ServiceRequest.focus`, `ServiceRequest.id`, `ServiceRequest.identifier`, `ServiceRequest.implicitRules`, `ServiceRequest.instantiatesCanonical`, `ServiceRequest.instantiatesUri`, `ServiceRequest.insurance`, `ServiceRequest.intent`, `ServiceRequest.language`, `ServiceRequest.location`, `ServiceRequest.meta`, `ServiceRequest.modifierExtension`, `ServiceRequest.note`, `ServiceRequest.occurrence[x]`, `ServiceRequest.orderDetail`, `ServiceRequest.orderDetail.extension`, `ServiceRequest.orderDetail.id`, `ServiceRequest.orderDetail.modifierExtension`, `ServiceRequest.orderDetail.parameter`, `ServiceRequest.orderDetail.parameter.code`, `ServiceRequest.orderDetail.parameter.extension`, `ServiceRequest.orderDetail.parameter.id`, `ServiceRequest.orderDetail.parameter.modifierExtension`, `ServiceRequest.orderDetail.parameter.value[x]`, `ServiceRequest.orderDetail.parameterFocus`, `ServiceRequest.patientInstruction`, `ServiceRequest.patientInstruction.extension`, `ServiceRequest.patientInstruction.id`, `ServiceRequest.patientInstruction.instruction[x]`, `ServiceRequest.patientInstruction.modifierExtension`, `ServiceRequest.performer`, `ServiceRequest.performerType`, `ServiceRequest.priority`, `ServiceRequest.quantity[x]`, `ServiceRequest.reason`, `ServiceRequest.relevantHistory`, `ServiceRequest.replaces`, `ServiceRequest.requisition`, `ServiceRequest.specimen`, `ServiceRequest.status`, `ServiceRequest.subject`, `ServiceRequest.supportingInfo`, `ServiceRequest.text`


#### Map Group 1

This group is centered on the Structure Definition ProcedureRequest from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 ProcedureRequest](/docs/R2/Resources/ProcedureRequest.md)| Relationship | R3 ProcedureRequest| Relationship | [R4 ServiceRequest](/docs/R4/Resources/ServiceRequest.md)| Relationship | [R4B ServiceRequest](/docs/R4B/Resources/ServiceRequest.md)| Relationship | [R5 ServiceRequest](/docs/R5/Resources/ServiceRequest.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `ProcedureRequest`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7307)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7308)| **`ProcedureRequest`**| | | | | | | 
| `ProcedureRequest.id`| _Equivalent_<br/>(7309/7310)| **`ProcedureRequest.id`**| | | | | | | 
| `ProcedureRequest.meta`| _Equivalent_<br/>(7311/7312)| **`ProcedureRequest.meta`**| | | | | | | 
| `ProcedureRequest.implicitRules`| _Equivalent_<br/>(7313/7314)| **`ProcedureRequest.implicitRules`**| | | | | | | 
| `ProcedureRequest.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7315)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7316)| **`ProcedureRequest.language`**| | | | | | | 
| `ProcedureRequest.text`| _Equivalent_<br/>(7317/7318)| **`ProcedureRequest.text`**| | | | | | | 
| `ProcedureRequest.contained`| _Equivalent_<br/>(7319/7320)| **`ProcedureRequest.contained`**| | | | | | | 
| `ProcedureRequest.extension`| _Equivalent_<br/>(7321/7322)| **`ProcedureRequest.extension`**| | | | | | | 
| `ProcedureRequest.modifierExtension`| _Equivalent_<br/>(7323/7324)| **`ProcedureRequest.modifierExtension`**| | | | | | | 
| `ProcedureRequest.identifier`| _Equivalent_<br/>(7325/7326)| **`ProcedureRequest.identifier`**| | | | | | | 
| | | **`ProcedureRequest.definition`**| | | | | | | 
| | | **`ProcedureRequest.basedOn`**| | | | | | | 
| | | **`ProcedureRequest.replaces`**| | | | | | | 
| | | **`ProcedureRequest.requisition`**| | | | | | | 
| `ProcedureRequest.status`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7335)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7336)| **`ProcedureRequest.status`**| | | | | | | 
| | | **`ProcedureRequest.intent`**| | | | | | | 
| `ProcedureRequest.priority`| _Equivalent_<br/>(7340/7341)| **`ProcedureRequest.priority`**| | | | | | | 
| | | **`ProcedureRequest.doNotPerform`**| | | | | | | 
| | | **`ProcedureRequest.category`**| | | | | | | 
| `ProcedureRequest.code`| _Equivalent_<br/>(7329/7330)| **`ProcedureRequest.code`**| | | | | | | 
| `ProcedureRequest.subject`| →→→→ _RelatedTo_ →→→→ <br/>(7327)<hr/>←←←← _RelatedTo_ ←←←← <br/>(7328)| **`ProcedureRequest.subject`**| | | | | | | 
| `ProcedureRequest.encounter`| →→→→ _RelatedTo_ →→→→ <br/>(340)<hr/>←←←← _RelatedTo_ ←←←← <br/>(793)| **`ProcedureRequest.context`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1237)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17511)| `ServiceRequest.encounter`| _Equivalent_<br/>(33100/33101)| `ServiceRequest.encounter`| _Equivalent_<br/>(47343/47344)| `ServiceRequest.encounter`
| `ProcedureRequest.scheduled[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(346)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(792)| **`ProcedureRequest.occurrence[x]`**| | | | | | | 
| `ProcedureRequest.asNeeded[x]`| _Equivalent_<br/>(7337/7338)| **`ProcedureRequest.asNeeded[x]`**| | | | | | | 
| `ProcedureRequest.orderedOn`| _Equivalent_<br/>(342/795)| **`ProcedureRequest.authoredOn`**| | | | | | | 
| | | **`ProcedureRequest.requester`**| | | | | | | 
| | | **`ProcedureRequest.requester.id`**| | | | | | | 
| | | **`ProcedureRequest.requester.extension`**| | | | | | | 
| | | **`ProcedureRequest.requester.modifierExtension`**| | | | | | | 
| `ProcedureRequest.orderer`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(343)<hr/>←←←← _RelatedTo_ ←←←← <br/>(7339)| **`ProcedureRequest.requester.agent`**| →→→→ _RelatedTo_ →→→→ <br/>(1239)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(17519)| `ServiceRequest.requester`| _Equivalent_<br/>(33108/33109)| `ServiceRequest.requester`| _Equivalent_<br/>(47351/47352)| `ServiceRequest.requester`
| | | **`ProcedureRequest.requester.onBehalfOf`**| | | | | | | 
| | | **`ProcedureRequest.performerType`**| | | | | | | 
| `ProcedureRequest.performer`| →→→→ _RelatedTo_ →→→→ <br/>(7333)<hr/>←←←← _RelatedTo_ ←←←← <br/>(7334)| **`ProcedureRequest.performer`**| | | | | | | 
| `ProcedureRequest.reason[x]`| →→→→ _RelatedTo_ →→→→ <br/>(344)<hr/>←←←← _RelatedTo_ ←←←← <br/>(790)| **`ProcedureRequest.reasonCode`**| | | | | | | 
| `ProcedureRequest.reason[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(345)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(791)| **`ProcedureRequest.reasonReference`**| | | | | | | 
| | | **`ProcedureRequest.supportingInfo`**| | | | | | | 
| | | **`ProcedureRequest.specimen`**| | | | | | | 
| `ProcedureRequest.bodySite`| _Equivalent_<br/>(7331/7332)| **`ProcedureRequest.bodySite`**| | | | | | | 
| `ProcedureRequest.notes`| _Equivalent_<br/>(341/794)| **`ProcedureRequest.note`**| | | | | | | 
| | | **`ProcedureRequest.relevantHistory`**| | | | | | | 
| *23 of 23 elements used* | | *40 of 40 elements used* | | *2 of 42 elements used* <br/>remaining elements:<br/>`ServiceRequest`, `ServiceRequest.asNeeded[x]`, `ServiceRequest.authoredOn`, `ServiceRequest.basedOn`, `ServiceRequest.bodySite`, `ServiceRequest.category`, `ServiceRequest.code`, `ServiceRequest.contained`, `ServiceRequest.doNotPerform`, `ServiceRequest.extension`, `ServiceRequest.id`, `ServiceRequest.identifier`, `ServiceRequest.implicitRules`, `ServiceRequest.instantiatesCanonical`, `ServiceRequest.instantiatesUri`, `ServiceRequest.insurance`, `ServiceRequest.intent`, `ServiceRequest.language`, `ServiceRequest.locationCode`, `ServiceRequest.locationReference`, `ServiceRequest.meta`, `ServiceRequest.modifierExtension`, `ServiceRequest.note`, `ServiceRequest.occurrence[x]`, `ServiceRequest.orderDetail`, `ServiceRequest.patientInstruction`, `ServiceRequest.performer`, `ServiceRequest.performerType`, `ServiceRequest.priority`, `ServiceRequest.quantity[x]`, `ServiceRequest.reasonCode`, `ServiceRequest.reasonReference`, `ServiceRequest.relevantHistory`, `ServiceRequest.replaces`, `ServiceRequest.requisition`, `ServiceRequest.specimen`, `ServiceRequest.status`, `ServiceRequest.subject`, `ServiceRequest.supportingInfo`, `ServiceRequest.text`| | *2 of 42 elements used* <br/>remaining elements:<br/>`ServiceRequest`, `ServiceRequest.asNeeded[x]`, `ServiceRequest.authoredOn`, `ServiceRequest.basedOn`, `ServiceRequest.bodySite`, `ServiceRequest.category`, `ServiceRequest.code`, `ServiceRequest.contained`, `ServiceRequest.doNotPerform`, `ServiceRequest.extension`, `ServiceRequest.id`, `ServiceRequest.identifier`, `ServiceRequest.implicitRules`, `ServiceRequest.instantiatesCanonical`, `ServiceRequest.instantiatesUri`, `ServiceRequest.insurance`, `ServiceRequest.intent`, `ServiceRequest.language`, `ServiceRequest.locationCode`, `ServiceRequest.locationReference`, `ServiceRequest.meta`, `ServiceRequest.modifierExtension`, `ServiceRequest.note`, `ServiceRequest.occurrence[x]`, `ServiceRequest.orderDetail`, `ServiceRequest.patientInstruction`, `ServiceRequest.performer`, `ServiceRequest.performerType`, `ServiceRequest.priority`, `ServiceRequest.quantity[x]`, `ServiceRequest.reasonCode`, `ServiceRequest.reasonReference`, `ServiceRequest.relevantHistory`, `ServiceRequest.replaces`, `ServiceRequest.requisition`, `ServiceRequest.specimen`, `ServiceRequest.status`, `ServiceRequest.subject`, `ServiceRequest.supportingInfo`, `ServiceRequest.text`| | *2 of 56 elements used* <br/>remaining elements:<br/>`ServiceRequest`, `ServiceRequest.asNeeded[x]`, `ServiceRequest.authoredOn`, `ServiceRequest.basedOn`, `ServiceRequest.bodySite`, `ServiceRequest.bodyStructure`, `ServiceRequest.category`, `ServiceRequest.code`, `ServiceRequest.contained`, `ServiceRequest.doNotPerform`, `ServiceRequest.extension`, `ServiceRequest.focus`, `ServiceRequest.id`, `ServiceRequest.identifier`, `ServiceRequest.implicitRules`, `ServiceRequest.instantiatesCanonical`, `ServiceRequest.instantiatesUri`, `ServiceRequest.insurance`, `ServiceRequest.intent`, `ServiceRequest.language`, `ServiceRequest.location`, `ServiceRequest.meta`, `ServiceRequest.modifierExtension`, `ServiceRequest.note`, `ServiceRequest.occurrence[x]`, `ServiceRequest.orderDetail`, `ServiceRequest.orderDetail.extension`, `ServiceRequest.orderDetail.id`, `ServiceRequest.orderDetail.modifierExtension`, `ServiceRequest.orderDetail.parameter`, `ServiceRequest.orderDetail.parameter.code`, `ServiceRequest.orderDetail.parameter.extension`, `ServiceRequest.orderDetail.parameter.id`, `ServiceRequest.orderDetail.parameter.modifierExtension`, `ServiceRequest.orderDetail.parameter.value[x]`, `ServiceRequest.orderDetail.parameterFocus`, `ServiceRequest.patientInstruction`, `ServiceRequest.patientInstruction.extension`, `ServiceRequest.patientInstruction.id`, `ServiceRequest.patientInstruction.instruction[x]`, `ServiceRequest.patientInstruction.modifierExtension`, `ServiceRequest.performer`, `ServiceRequest.performerType`, `ServiceRequest.priority`, `ServiceRequest.quantity[x]`, `ServiceRequest.reason`, `ServiceRequest.relevantHistory`, `ServiceRequest.replaces`, `ServiceRequest.requisition`, `ServiceRequest.specimen`, `ServiceRequest.status`, `ServiceRequest.subject`, `ServiceRequest.supportingInfo`, `ServiceRequest.text`

