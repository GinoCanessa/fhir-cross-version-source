Comparison of 
Generated at Thursday, April 3, 2025 8:18:37 AM

### ServiceRequest

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | ServiceRequest |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ServiceRequest` |
| Version | 5.0.0 |
| Description | A record of a request for service such as diagnostic investigations, treatments, or operations to be performed. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2381` |
| Database Snapshot Count | `56` |
| Database Differential Count | `39` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ServiceRequest` | `ServiceRequest` | `ServiceRequest` | ServiceRequest | A request for a service to be performed | 0..* | ServiceRequest |  |  |
| `ServiceRequest.asNeeded[x]` | `ServiceRequest.asNeeded[x]` | `asNeeded[x]` | ServiceRequest.asNeeded[x] | Preconditions for service | 0..1 | boolean, CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/medication-as-needed-reason` |
| `ServiceRequest.authoredOn` | `ServiceRequest.authoredOn` | `authoredOn` | ServiceRequest.authoredOn | Date request signed | 0..1 | dateTime |  |  |
| `ServiceRequest.basedOn` | `ServiceRequest.basedOn` | `basedOn` | ServiceRequest.basedOn | What request fulfills | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/CarePlan), Reference(http://hl7.org/fhir/StructureDefinition/MedicationRequest), Reference(http://hl7.org/fhir/StructureDefinition/ServiceRequest) |  |  |
| `ServiceRequest.bodySite` | `ServiceRequest.bodySite` | `bodySite` | ServiceRequest.bodySite | Coded location on Body | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/body-site` |
| `ServiceRequest.bodyStructure` | `ServiceRequest.bodyStructure` | `bodyStructure` | ServiceRequest.bodyStructure | BodyStructure-based location on the body | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/BodyStructure) |  |  |
| `ServiceRequest.category` | `ServiceRequest.category` | `category` | ServiceRequest.category | Classification of service | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/servicerequest-category` |
| `ServiceRequest.code` | `ServiceRequest.code` | `code` | ServiceRequest.code | What is being requested/ordered | 0..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/ActivityDefinition), CodeableReference(http://hl7.org/fhir/StructureDefinition/PlanDefinition) | `Example` | `http://hl7.org/fhir/ValueSet/procedure-code` |
| `ServiceRequest.contained` | `ServiceRequest.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ServiceRequest.doNotPerform` | `ServiceRequest.doNotPerform` | `doNotPerform` | ServiceRequest.doNotPerform | True if service/procedure should not be performed | 0..1 | boolean |  |  |
| `ServiceRequest.encounter` | `ServiceRequest.encounter` | `encounter` | ServiceRequest.encounter | Encounter in which the request was created | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `ServiceRequest.extension` | `ServiceRequest.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ServiceRequest.focus` | `ServiceRequest.focus` | `focus` | ServiceRequest.focus | What the service request is about, when it is not about the subject of record | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `ServiceRequest.id` | `ServiceRequest.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ServiceRequest.identifier` | `ServiceRequest.identifier` | `identifier` | ServiceRequest.identifier | Identifiers assigned to this order | 0..* | Identifier |  |  |
| `ServiceRequest.implicitRules` | `ServiceRequest.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ServiceRequest.instantiatesCanonical` | `ServiceRequest.instantiatesCanonical` | `instantiatesCanonical` | ServiceRequest.instantiatesCanonical | Instantiates FHIR protocol or definition | 0..* | canonical(http://hl7.org/fhir/StructureDefinition/ActivityDefinition), canonical(http://hl7.org/fhir/StructureDefinition/PlanDefinition) |  |  |
| `ServiceRequest.instantiatesUri` | `ServiceRequest.instantiatesUri` | `instantiatesUri` | ServiceRequest.instantiatesUri | Instantiates external protocol or definition | 0..* | uri |  |  |
| `ServiceRequest.insurance` | `ServiceRequest.insurance` | `insurance` | ServiceRequest.insurance | Associated insurance coverage | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ClaimResponse), Reference(http://hl7.org/fhir/StructureDefinition/Coverage) |  |  |
| `ServiceRequest.intent` | `ServiceRequest.intent` | `intent` | ServiceRequest.intent | proposal \| plan \| directive \| order + | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/request-intent|5.0.0` |
| `ServiceRequest.language` | `ServiceRequest.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `ServiceRequest.location` | `ServiceRequest.location` | `location` | ServiceRequest.location | Requested location | 0..* | CodeableReference(http://hl7.org/fhir/StructureDefinition/Location) | `Example` | `http://terminology.hl7.org/ValueSet/v3-ServiceDeliveryLocationRoleType` |
| `ServiceRequest.meta` | `ServiceRequest.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ServiceRequest.modifierExtension` | `ServiceRequest.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ServiceRequest.note` | `ServiceRequest.note` | `note` | ServiceRequest.note | Comments | 0..* | Annotation |  |  |
| `ServiceRequest.occurrence[x]` | `ServiceRequest.occurrence[x]` | `occurrence[x]` | ServiceRequest.occurrence[x] | When service should occur | 0..1 | dateTime, Period, Timing |  |  |
| `ServiceRequest.orderDetail` | `ServiceRequest.orderDetail` | `orderDetail` | ServiceRequest.orderDetail | Additional order information | 0..* | BackboneElement |  |  |
| `ServiceRequest.orderDetail.extension` | `ServiceRequest.orderDetail.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ServiceRequest.orderDetail.id` | `ServiceRequest.orderDetail.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ServiceRequest.orderDetail.modifierExtension` | `ServiceRequest.orderDetail.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ServiceRequest.orderDetail.parameter` | `ServiceRequest.orderDetail.parameter` | `parameter` | ServiceRequest.orderDetail.parameter | The parameter details for the service being requested | 1..* | BackboneElement |  |  |
| `ServiceRequest.orderDetail.parameter.code` | `ServiceRequest.orderDetail.parameter.code` | `code` | ServiceRequest.orderDetail.parameter.code | The detail of the order being requested | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/servicerequest-orderdetail-parameter-code` |
| `ServiceRequest.orderDetail.parameter.extension` | `ServiceRequest.orderDetail.parameter.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ServiceRequest.orderDetail.parameter.id` | `ServiceRequest.orderDetail.parameter.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ServiceRequest.orderDetail.parameter.modifierExtension` | `ServiceRequest.orderDetail.parameter.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ServiceRequest.orderDetail.parameter.value[x]` | `ServiceRequest.orderDetail.parameter.value[x]` | `value[x]` | ServiceRequest.orderDetail.parameter.value[x] | The value for the order detail | 1..1 | boolean, CodeableConcept, Period, Quantity, Range, Ratio, string |  |  |
| `ServiceRequest.orderDetail.parameterFocus` | `ServiceRequest.orderDetail.parameterFocus` | `parameterFocus` | ServiceRequest.orderDetail.parameterFocus | The context of the order details by reference | 0..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/BiologicallyDerivedProduct), CodeableReference(http://hl7.org/fhir/StructureDefinition/Device), CodeableReference(http://hl7.org/fhir/StructureDefinition/DeviceDefinition), CodeableReference(http://hl7.org/fhir/StructureDefinition/DeviceRequest), CodeableReference(http://hl7.org/fhir/StructureDefinition/Medication), CodeableReference(http://hl7.org/fhir/StructureDefinition/MedicationRequest), CodeableReference(http://hl7.org/fhir/StructureDefinition/Substance), CodeableReference(http://hl7.org/fhir/StructureDefinition/SupplyRequest) |  |  |
| `ServiceRequest.patientInstruction` | `ServiceRequest.patientInstruction` | `patientInstruction` | ServiceRequest.patientInstruction | Patient or consumer-oriented instructions | 0..* | BackboneElement |  |  |
| `ServiceRequest.patientInstruction.extension` | `ServiceRequest.patientInstruction.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `ServiceRequest.patientInstruction.id` | `ServiceRequest.patientInstruction.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `ServiceRequest.patientInstruction.instruction[x]` | `ServiceRequest.patientInstruction.instruction[x]` | `instruction[x]` | ServiceRequest.patientInstruction.instruction[x] | Patient or consumer-oriented instructions | 0..1 | markdown, Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference) |  |  |
| `ServiceRequest.patientInstruction.modifierExtension` | `ServiceRequest.patientInstruction.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `ServiceRequest.performer` | `ServiceRequest.performer` | `performer` | ServiceRequest.performer | Requested performer | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/CareTeam), Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/HealthcareService), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `ServiceRequest.performerType` | `ServiceRequest.performerType` | `performerType` | ServiceRequest.performerType | Performer role | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/participant-role` |
| `ServiceRequest.priority` | `ServiceRequest.priority` | `priority` | ServiceRequest.priority | routine \| urgent \| asap \| stat | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/request-priority|5.0.0` |
| `ServiceRequest.quantity[x]` | `ServiceRequest.quantity[x]` | `quantity[x]` | ServiceRequest.quantity[x] | Service amount | 0..1 | Quantity, Range, Ratio |  |  |
| `ServiceRequest.reason` | `ServiceRequest.reason` | `reason` | ServiceRequest.reason | Explanation/Justification for procedure or service | 0..* | CodeableReference(http://hl7.org/fhir/StructureDefinition/Condition), CodeableReference(http://hl7.org/fhir/StructureDefinition/DetectedIssue), CodeableReference(http://hl7.org/fhir/StructureDefinition/DiagnosticReport), CodeableReference(http://hl7.org/fhir/StructureDefinition/DocumentReference), CodeableReference(http://hl7.org/fhir/StructureDefinition/Observation) | `Example` | `http://hl7.org/fhir/ValueSet/procedure-reason` |
| `ServiceRequest.relevantHistory` | `ServiceRequest.relevantHistory` | `relevantHistory` | ServiceRequest.relevantHistory | Request provenance | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Provenance) |  |  |
| `ServiceRequest.replaces` | `ServiceRequest.replaces` | `replaces` | ServiceRequest.replaces | What request replaces | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ServiceRequest) |  |  |
| `ServiceRequest.requester` | `ServiceRequest.requester` | `requester` | ServiceRequest.requester | Who/what is requesting service | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `ServiceRequest.requisition` | `ServiceRequest.requisition` | `requisition` | ServiceRequest.requisition | Composite Request ID | 0..1 | Identifier |  |  |
| `ServiceRequest.specimen` | `ServiceRequest.specimen` | `specimen` | ServiceRequest.specimen | Procedure Samples | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Specimen) |  |  |
| `ServiceRequest.status` | `ServiceRequest.status` | `status` | ServiceRequest.status | draft \| active \| on-hold \| revoked \| completed \| entered-in-error \| unknown | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/request-status|5.0.0` |
| `ServiceRequest.subject` | `ServiceRequest.subject` | `subject` | ServiceRequest.subject | Individual or Entity the service is ordered for | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `ServiceRequest.supportingInfo` | `ServiceRequest.supportingInfo` | `supportingInfo` | ServiceRequest.supportingInfo | Additional clinical information | 0..* | CodeableReference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `ServiceRequest.text` | `ServiceRequest.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DiagnosticOrder](/docs/R2/Resources/DiagnosticOrder.md)<br/> `http://hl7.org/fhir/StructureDefinition/DiagnosticOrder\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `102`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `321`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ProcedureRequest](/docs/R3/Resources/ProcedureRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ProcedureRequest\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `515`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `708`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ServiceRequest](/docs/R4/Resources/ServiceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ServiceRequest\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1613`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1614`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ServiceRequest](/docs/R4B/Resources/ServiceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ServiceRequest\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1040`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1269`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ServiceRequest](/docs/R5/Resources/ServiceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ServiceRequest\|5.0.0` 
| [ProcedureRequest](/docs/R2/Resources/ProcedureRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ProcedureRequest\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `155`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `321`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ProcedureRequest](/docs/R3/Resources/ProcedureRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ProcedureRequest\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `515`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `708`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ServiceRequest](/docs/R4/Resources/ServiceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ServiceRequest\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1613`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1614`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ServiceRequest](/docs/R4B/Resources/ServiceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ServiceRequest\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1040`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1269`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ServiceRequest](/docs/R5/Resources/ServiceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ServiceRequest\|5.0.0` 
| [ReferralRequest](/docs/R2/Resources/ReferralRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ReferralRequest\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `150`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `316`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ReferralRequest](/docs/R3/Resources/ReferralRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ReferralRequest\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `507`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `708`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ServiceRequest](/docs/R4/Resources/ServiceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ServiceRequest\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1613`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1614`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ServiceRequest](/docs/R4B/Resources/ServiceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ServiceRequest\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1040`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1269`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ServiceRequest](/docs/R5/Resources/ServiceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ServiceRequest\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ServiceRequest from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 DiagnosticOrder](/docs/R2/Resources/DiagnosticOrder.md)| Relationship | [R3 ProcedureRequest](/docs/R3/Resources/ProcedureRequest.md)| Relationship | [R4 ServiceRequest](/docs/R4/Resources/ServiceRequest.md)| Relationship | [R4B ServiceRequest](/docs/R4B/Resources/ServiceRequest.md)| Relationship | R5 ServiceRequest
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `ServiceRequest`| _Equivalent_<br/>(33052/33053)| `ServiceRequest`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47295)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47296)| **`ServiceRequest`**
| | | | | `ServiceRequest.id`| _Equivalent_<br/>(33054/33055)| `ServiceRequest.id`| _Equivalent_<br/>(47297/47298)| **`ServiceRequest.id`**
| | | | | `ServiceRequest.meta`| _Equivalent_<br/>(33056/33057)| `ServiceRequest.meta`| _Equivalent_<br/>(47299/47300)| **`ServiceRequest.meta`**
| | | | | `ServiceRequest.implicitRules`| _Equivalent_<br/>(33058/33059)| `ServiceRequest.implicitRules`| _Equivalent_<br/>(47301/47302)| **`ServiceRequest.implicitRules`**
| | | | | `ServiceRequest.language`| _Equivalent_<br/>(33060/33061)| `ServiceRequest.language`| _Equivalent_<br/>(47303/47304)| **`ServiceRequest.language`**
| | | | | `ServiceRequest.text`| _Equivalent_<br/>(33062/33063)| `ServiceRequest.text`| _Equivalent_<br/>(47305/47306)| **`ServiceRequest.text`**
| | | | | `ServiceRequest.contained`| _Equivalent_<br/>(33064/33065)| `ServiceRequest.contained`| _Equivalent_<br/>(47307/47308)| **`ServiceRequest.contained`**
| | | | | `ServiceRequest.extension`| _Equivalent_<br/>(33066/33067)| `ServiceRequest.extension`| _Equivalent_<br/>(47309/47310)| **`ServiceRequest.extension`**
| | | | | `ServiceRequest.modifierExtension`| _Equivalent_<br/>(33068/33069)| `ServiceRequest.modifierExtension`| _Equivalent_<br/>(47311/47312)| **`ServiceRequest.modifierExtension`**
| | | | | `ServiceRequest.identifier`| _Equivalent_<br/>(33070/33071)| `ServiceRequest.identifier`| _Equivalent_<br/>(47313/47314)| **`ServiceRequest.identifier`**
| | | | | `ServiceRequest.instantiatesCanonical`| _Equivalent_<br/>(33072/33073)| `ServiceRequest.instantiatesCanonical`| _Equivalent_<br/>(47315/47316)| **`ServiceRequest.instantiatesCanonical`**
| | | | | `ServiceRequest.instantiatesUri`| _Equivalent_<br/>(33074/33075)| `ServiceRequest.instantiatesUri`| _Equivalent_<br/>(47317/47318)| **`ServiceRequest.instantiatesUri`**
| | | | | `ServiceRequest.basedOn`| _Equivalent_<br/>(33076/33077)| `ServiceRequest.basedOn`| _Equivalent_<br/>(47319/47320)| **`ServiceRequest.basedOn`**
| | | | | `ServiceRequest.replaces`| _Equivalent_<br/>(33078/33079)| `ServiceRequest.replaces`| _Equivalent_<br/>(47321/47322)| **`ServiceRequest.replaces`**
| | | `ReferralRequest.groupIdentifier`| _Equivalent_<br/>(1259/1669)| `ServiceRequest.requisition`| _Equivalent_<br/>(33080/33081)| `ServiceRequest.requisition`| _Equivalent_<br/>(47323/47324)| **`ServiceRequest.requisition`**
| | | | | `ServiceRequest.status`| _Equivalent_<br/>(33082/33083)| `ServiceRequest.status`| _Equivalent_<br/>(47325/47326)| **`ServiceRequest.status`**
| | | | | `ServiceRequest.intent`| _Equivalent_<br/>(33084/33085)| `ServiceRequest.intent`| _Equivalent_<br/>(47327/47328)| **`ServiceRequest.intent`**
| | | `ReferralRequest.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1265)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1664)| `ServiceRequest.category`| _Equivalent_<br/>(33086/33087)| `ServiceRequest.category`| _Equivalent_<br/>(47329/47330)| **`ServiceRequest.category`**
| | | | | `ServiceRequest.priority`| _Equivalent_<br/>(33088/33089)| `ServiceRequest.priority`| _Equivalent_<br/>(47331/47332)| **`ServiceRequest.priority`**
| | | | | `ServiceRequest.doNotPerform`| _Equivalent_<br/>(33090/33091)| `ServiceRequest.doNotPerform`| _Equivalent_<br/>(47333/47334)| **`ServiceRequest.doNotPerform`**
| | | `ReferralRequest.serviceRequested`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1263)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1665)| `ServiceRequest.code`| _Equivalent_<br/>(33092/33093)| `ServiceRequest.code`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47335)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47336)| **`ServiceRequest.code`**
| | | | | `ServiceRequest.orderDetail`| _Equivalent_<br/>(33094/33095)| `ServiceRequest.orderDetail`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47337)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47338)| **`ServiceRequest.orderDetail`**
| | | | | | | | | **`ServiceRequest.orderDetail.id`**
| | | | | | | | | **`ServiceRequest.orderDetail.extension`**
| | | | | | | | | **`ServiceRequest.orderDetail.modifierExtension`**
| | | | | | | | | **`ServiceRequest.orderDetail.parameterFocus`**
| | | | | | | | | **`ServiceRequest.orderDetail.parameter`**
| | | | | | | | | **`ServiceRequest.orderDetail.parameter.id`**
| | | | | | | | | **`ServiceRequest.orderDetail.parameter.extension`**
| | | | | | | | | **`ServiceRequest.orderDetail.parameter.modifierExtension`**
| | | | | | | | | **`ServiceRequest.orderDetail.parameter.code`**
| | | | | | | | | **`ServiceRequest.orderDetail.parameter.value[x]`**
| | | | | `ServiceRequest.quantity[x]`| _Equivalent_<br/>(33096/33097)| `ServiceRequest.quantity[x]`| _Equivalent_<br/>(47339/47340)| **`ServiceRequest.quantity[x]`**
| | | | | `ServiceRequest.subject`| _Equivalent_<br/>(33098/33099)| `ServiceRequest.subject`| _Equivalent_<br/>(47341/47342)| **`ServiceRequest.subject`**
| | | | | | | | | **`ServiceRequest.focus`**
| | | `ReferralRequest.context`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1256)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1666)| `ServiceRequest.encounter`| _Equivalent_<br/>(33100/33101)| `ServiceRequest.encounter`| _Equivalent_<br/>(47343/47344)| **`ServiceRequest.encounter`**
| | | | | `ServiceRequest.occurrence[x]`| _Equivalent_<br/>(33102/33103)| `ServiceRequest.occurrence[x]`| _Equivalent_<br/>(47345/47346)| **`ServiceRequest.occurrence[x]`**
| | | | | `ServiceRequest.asNeeded[x]`| _Equivalent_<br/>(33104/33105)| `ServiceRequest.asNeeded[x]`| _Equivalent_<br/>(47347/47348)| **`ServiceRequest.asNeeded[x]`**
| | | | | `ServiceRequest.authoredOn`| _Equivalent_<br/>(33106/33107)| `ServiceRequest.authoredOn`| _Equivalent_<br/>(47349/47350)| **`ServiceRequest.authoredOn`**
| | | `ReferralRequest.requester.agent`| →→→→ _RelatedTo_ →→→→ <br/>(1261)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1668)| `ServiceRequest.requester`| _Equivalent_<br/>(33108/33109)| `ServiceRequest.requester`| _Equivalent_<br/>(47351/47352)| **`ServiceRequest.requester`**
| | | | | `ServiceRequest.performerType`| _Equivalent_<br/>(33110/33111)| `ServiceRequest.performerType`| _Equivalent_<br/>(47353/47354)| **`ServiceRequest.performerType`**
| | | `ReferralRequest.recipient`| →→→→ _RelatedTo_ →→→→ <br/>(1260)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1667)| `ServiceRequest.performer`| _Equivalent_<br/>(33112/33113)| `ServiceRequest.performer`| _Equivalent_<br/>(47355/47356)| **`ServiceRequest.performer`**
| | | | | `ServiceRequest.locationCode`| _Equivalent_<br/>(33114/33115)| `ServiceRequest.locationCode`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1949)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2186)| **`ServiceRequest.location`**
| | | | | `ServiceRequest.locationReference`| _Equivalent_<br/>(33116/33117)| `ServiceRequest.locationReference`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1950)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2186)| **`ServiceRequest.location`**
| | | | | `ServiceRequest.reasonCode`| _Equivalent_<br/>(33118/33119)| `ServiceRequest.reasonCode`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1951)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2188)| **`ServiceRequest.reason`**
| | | | | `ServiceRequest.reasonReference`| _Equivalent_<br/>(33120/33121)| `ServiceRequest.reasonReference`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1952)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2188)| **`ServiceRequest.reason`**
| | | | | `ServiceRequest.insurance`| _Equivalent_<br/>(33122/33123)| `ServiceRequest.insurance`| _Equivalent_<br/>(47357/47358)| **`ServiceRequest.insurance`**
| | | | | `ServiceRequest.supportingInfo`| _Equivalent_<br/>(33124/33125)| `ServiceRequest.supportingInfo`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47359)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47360)| **`ServiceRequest.supportingInfo`**
| | | | | `ServiceRequest.specimen`| _Equivalent_<br/>(33126/33127)| `ServiceRequest.specimen`| _Equivalent_<br/>(47361/47362)| **`ServiceRequest.specimen`**
| | | | | `ServiceRequest.bodySite`| _Equivalent_<br/>(33128/33129)| `ServiceRequest.bodySite`| _Equivalent_<br/>(47363/47364)| **`ServiceRequest.bodySite`**
| | | | | | | | | **`ServiceRequest.bodyStructure`**
| | | | | `ServiceRequest.note`| _Equivalent_<br/>(33130/33131)| `ServiceRequest.note`| _Equivalent_<br/>(47365/47366)| **`ServiceRequest.note`**
| | | | | `ServiceRequest.patientInstruction`| _Equivalent_<br/>(33132/33133)| `ServiceRequest.patientInstruction`| →→→→ _RelatedTo_ →→→→ <br/>(47367)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47368)| **`ServiceRequest.patientInstruction`**
| | | | | | | | | **`ServiceRequest.patientInstruction.id`**
| | | | | | | | | **`ServiceRequest.patientInstruction.extension`**
| | | | | | | | | **`ServiceRequest.patientInstruction.modifierExtension`**
| | | | | | | | | **`ServiceRequest.patientInstruction.instruction[x]`**
| | | | | `ServiceRequest.relevantHistory`| _Equivalent_<br/>(33134/33135)| `ServiceRequest.relevantHistory`| _Equivalent_<br/>(47369/47370)| **`ServiceRequest.relevantHistory`**
| *0 of 36 elements used* <br/>remaining elements:<br/>`DiagnosticOrder`, `DiagnosticOrder.contained`, `DiagnosticOrder.encounter`, `DiagnosticOrder.event`, `DiagnosticOrder.event.actor`, `DiagnosticOrder.event.dateTime`, `DiagnosticOrder.event.description`, `DiagnosticOrder.event.extension`, `DiagnosticOrder.event.id`, `DiagnosticOrder.event.modifierExtension`, `DiagnosticOrder.event.status`, `DiagnosticOrder.extension`, `DiagnosticOrder.id`, `DiagnosticOrder.identifier`, `DiagnosticOrder.implicitRules`, `DiagnosticOrder.item`, `DiagnosticOrder.item.bodySite`, `DiagnosticOrder.item.code`, `DiagnosticOrder.item.event`, `DiagnosticOrder.item.extension`, `DiagnosticOrder.item.id`, `DiagnosticOrder.item.modifierExtension`, `DiagnosticOrder.item.specimen`, `DiagnosticOrder.item.status`, `DiagnosticOrder.language`, `DiagnosticOrder.meta`, `DiagnosticOrder.modifierExtension`, `DiagnosticOrder.note`, `DiagnosticOrder.orderer`, `DiagnosticOrder.priority`, `DiagnosticOrder.reason`, `DiagnosticOrder.specimen`, `DiagnosticOrder.status`, `DiagnosticOrder.subject`, `DiagnosticOrder.supportingInformation`, `DiagnosticOrder.text`| | *6 of 40 elements used* <br/>remaining elements:<br/>`ProcedureRequest`, `ProcedureRequest.asNeeded[x]`, `ProcedureRequest.authoredOn`, `ProcedureRequest.basedOn`, `ProcedureRequest.bodySite`, `ProcedureRequest.category`, `ProcedureRequest.code`, `ProcedureRequest.contained`, `ProcedureRequest.context`, `ProcedureRequest.definition`, `ProcedureRequest.doNotPerform`, `ProcedureRequest.extension`, `ProcedureRequest.id`, `ProcedureRequest.identifier`, `ProcedureRequest.implicitRules`, `ProcedureRequest.intent`, `ProcedureRequest.language`, `ProcedureRequest.meta`, `ProcedureRequest.modifierExtension`, `ProcedureRequest.note`, `ProcedureRequest.occurrence[x]`, `ProcedureRequest.performer`, `ProcedureRequest.performerType`, `ProcedureRequest.priority`, `ProcedureRequest.reasonCode`, `ProcedureRequest.reasonReference`, `ProcedureRequest.relevantHistory`, `ProcedureRequest.replaces`, `ProcedureRequest.requester`, `ProcedureRequest.requester.agent`, `ProcedureRequest.requester.extension`, `ProcedureRequest.requester.id`, `ProcedureRequest.requester.modifierExtension`, `ProcedureRequest.requester.onBehalfOf`, `ProcedureRequest.requisition`, `ProcedureRequest.specimen`, `ProcedureRequest.status`, `ProcedureRequest.subject`, `ProcedureRequest.supportingInfo`, `ProcedureRequest.text`| | *42 of 42 elements used* | | *42 of 42 elements used* | | *56 of 56 elements used* 


#### Map Group 1

This group is centered on the Structure Definition ServiceRequest from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 ProcedureRequest](/docs/R2/Resources/ProcedureRequest.md)| Relationship | [R3 ProcedureRequest](/docs/R3/Resources/ProcedureRequest.md)| Relationship | [R4 ServiceRequest](/docs/R4/Resources/ServiceRequest.md)| Relationship | [R4B ServiceRequest](/docs/R4B/Resources/ServiceRequest.md)| Relationship | R5 ServiceRequest
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `ServiceRequest`| _Equivalent_<br/>(33052/33053)| `ServiceRequest`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47295)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47296)| **`ServiceRequest`**
| | | | | `ServiceRequest.id`| _Equivalent_<br/>(33054/33055)| `ServiceRequest.id`| _Equivalent_<br/>(47297/47298)| **`ServiceRequest.id`**
| | | | | `ServiceRequest.meta`| _Equivalent_<br/>(33056/33057)| `ServiceRequest.meta`| _Equivalent_<br/>(47299/47300)| **`ServiceRequest.meta`**
| | | | | `ServiceRequest.implicitRules`| _Equivalent_<br/>(33058/33059)| `ServiceRequest.implicitRules`| _Equivalent_<br/>(47301/47302)| **`ServiceRequest.implicitRules`**
| | | | | `ServiceRequest.language`| _Equivalent_<br/>(33060/33061)| `ServiceRequest.language`| _Equivalent_<br/>(47303/47304)| **`ServiceRequest.language`**
| | | | | `ServiceRequest.text`| _Equivalent_<br/>(33062/33063)| `ServiceRequest.text`| _Equivalent_<br/>(47305/47306)| **`ServiceRequest.text`**
| | | | | `ServiceRequest.contained`| _Equivalent_<br/>(33064/33065)| `ServiceRequest.contained`| _Equivalent_<br/>(47307/47308)| **`ServiceRequest.contained`**
| | | | | `ServiceRequest.extension`| _Equivalent_<br/>(33066/33067)| `ServiceRequest.extension`| _Equivalent_<br/>(47309/47310)| **`ServiceRequest.extension`**
| | | | | `ServiceRequest.modifierExtension`| _Equivalent_<br/>(33068/33069)| `ServiceRequest.modifierExtension`| _Equivalent_<br/>(47311/47312)| **`ServiceRequest.modifierExtension`**
| | | | | `ServiceRequest.identifier`| _Equivalent_<br/>(33070/33071)| `ServiceRequest.identifier`| _Equivalent_<br/>(47313/47314)| **`ServiceRequest.identifier`**
| | | | | `ServiceRequest.instantiatesCanonical`| _Equivalent_<br/>(33072/33073)| `ServiceRequest.instantiatesCanonical`| _Equivalent_<br/>(47315/47316)| **`ServiceRequest.instantiatesCanonical`**
| | | | | `ServiceRequest.instantiatesUri`| _Equivalent_<br/>(33074/33075)| `ServiceRequest.instantiatesUri`| _Equivalent_<br/>(47317/47318)| **`ServiceRequest.instantiatesUri`**
| | | | | `ServiceRequest.basedOn`| _Equivalent_<br/>(33076/33077)| `ServiceRequest.basedOn`| _Equivalent_<br/>(47319/47320)| **`ServiceRequest.basedOn`**
| | | | | `ServiceRequest.replaces`| _Equivalent_<br/>(33078/33079)| `ServiceRequest.replaces`| _Equivalent_<br/>(47321/47322)| **`ServiceRequest.replaces`**
| | | `ReferralRequest.groupIdentifier`| _Equivalent_<br/>(1259/1669)| `ServiceRequest.requisition`| _Equivalent_<br/>(33080/33081)| `ServiceRequest.requisition`| _Equivalent_<br/>(47323/47324)| **`ServiceRequest.requisition`**
| | | | | `ServiceRequest.status`| _Equivalent_<br/>(33082/33083)| `ServiceRequest.status`| _Equivalent_<br/>(47325/47326)| **`ServiceRequest.status`**
| | | | | `ServiceRequest.intent`| _Equivalent_<br/>(33084/33085)| `ServiceRequest.intent`| _Equivalent_<br/>(47327/47328)| **`ServiceRequest.intent`**
| | | `ReferralRequest.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1265)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1664)| `ServiceRequest.category`| _Equivalent_<br/>(33086/33087)| `ServiceRequest.category`| _Equivalent_<br/>(47329/47330)| **`ServiceRequest.category`**
| | | | | `ServiceRequest.priority`| _Equivalent_<br/>(33088/33089)| `ServiceRequest.priority`| _Equivalent_<br/>(47331/47332)| **`ServiceRequest.priority`**
| | | | | `ServiceRequest.doNotPerform`| _Equivalent_<br/>(33090/33091)| `ServiceRequest.doNotPerform`| _Equivalent_<br/>(47333/47334)| **`ServiceRequest.doNotPerform`**
| | | `ReferralRequest.serviceRequested`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1263)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1665)| `ServiceRequest.code`| _Equivalent_<br/>(33092/33093)| `ServiceRequest.code`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47335)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47336)| **`ServiceRequest.code`**
| | | | | `ServiceRequest.orderDetail`| _Equivalent_<br/>(33094/33095)| `ServiceRequest.orderDetail`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47337)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47338)| **`ServiceRequest.orderDetail`**
| | | | | | | | | **`ServiceRequest.orderDetail.id`**
| | | | | | | | | **`ServiceRequest.orderDetail.extension`**
| | | | | | | | | **`ServiceRequest.orderDetail.modifierExtension`**
| | | | | | | | | **`ServiceRequest.orderDetail.parameterFocus`**
| | | | | | | | | **`ServiceRequest.orderDetail.parameter`**
| | | | | | | | | **`ServiceRequest.orderDetail.parameter.id`**
| | | | | | | | | **`ServiceRequest.orderDetail.parameter.extension`**
| | | | | | | | | **`ServiceRequest.orderDetail.parameter.modifierExtension`**
| | | | | | | | | **`ServiceRequest.orderDetail.parameter.code`**
| | | | | | | | | **`ServiceRequest.orderDetail.parameter.value[x]`**
| | | | | `ServiceRequest.quantity[x]`| _Equivalent_<br/>(33096/33097)| `ServiceRequest.quantity[x]`| _Equivalent_<br/>(47339/47340)| **`ServiceRequest.quantity[x]`**
| | | | | `ServiceRequest.subject`| _Equivalent_<br/>(33098/33099)| `ServiceRequest.subject`| _Equivalent_<br/>(47341/47342)| **`ServiceRequest.subject`**
| | | | | | | | | **`ServiceRequest.focus`**
| | | `ReferralRequest.context`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1256)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1666)| `ServiceRequest.encounter`| _Equivalent_<br/>(33100/33101)| `ServiceRequest.encounter`| _Equivalent_<br/>(47343/47344)| **`ServiceRequest.encounter`**
| | | | | `ServiceRequest.occurrence[x]`| _Equivalent_<br/>(33102/33103)| `ServiceRequest.occurrence[x]`| _Equivalent_<br/>(47345/47346)| **`ServiceRequest.occurrence[x]`**
| | | | | `ServiceRequest.asNeeded[x]`| _Equivalent_<br/>(33104/33105)| `ServiceRequest.asNeeded[x]`| _Equivalent_<br/>(47347/47348)| **`ServiceRequest.asNeeded[x]`**
| | | | | `ServiceRequest.authoredOn`| _Equivalent_<br/>(33106/33107)| `ServiceRequest.authoredOn`| _Equivalent_<br/>(47349/47350)| **`ServiceRequest.authoredOn`**
| | | `ReferralRequest.requester.agent`| →→→→ _RelatedTo_ →→→→ <br/>(1261)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1668)| `ServiceRequest.requester`| _Equivalent_<br/>(33108/33109)| `ServiceRequest.requester`| _Equivalent_<br/>(47351/47352)| **`ServiceRequest.requester`**
| | | | | `ServiceRequest.performerType`| _Equivalent_<br/>(33110/33111)| `ServiceRequest.performerType`| _Equivalent_<br/>(47353/47354)| **`ServiceRequest.performerType`**
| | | `ReferralRequest.recipient`| →→→→ _RelatedTo_ →→→→ <br/>(1260)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1667)| `ServiceRequest.performer`| _Equivalent_<br/>(33112/33113)| `ServiceRequest.performer`| _Equivalent_<br/>(47355/47356)| **`ServiceRequest.performer`**
| | | | | `ServiceRequest.locationCode`| _Equivalent_<br/>(33114/33115)| `ServiceRequest.locationCode`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1949)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2186)| **`ServiceRequest.location`**
| | | | | `ServiceRequest.locationReference`| _Equivalent_<br/>(33116/33117)| `ServiceRequest.locationReference`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1950)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2186)| **`ServiceRequest.location`**
| | | | | `ServiceRequest.reasonCode`| _Equivalent_<br/>(33118/33119)| `ServiceRequest.reasonCode`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1951)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2188)| **`ServiceRequest.reason`**
| | | | | `ServiceRequest.reasonReference`| _Equivalent_<br/>(33120/33121)| `ServiceRequest.reasonReference`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1952)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2188)| **`ServiceRequest.reason`**
| | | | | `ServiceRequest.insurance`| _Equivalent_<br/>(33122/33123)| `ServiceRequest.insurance`| _Equivalent_<br/>(47357/47358)| **`ServiceRequest.insurance`**
| | | | | `ServiceRequest.supportingInfo`| _Equivalent_<br/>(33124/33125)| `ServiceRequest.supportingInfo`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47359)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47360)| **`ServiceRequest.supportingInfo`**
| | | | | `ServiceRequest.specimen`| _Equivalent_<br/>(33126/33127)| `ServiceRequest.specimen`| _Equivalent_<br/>(47361/47362)| **`ServiceRequest.specimen`**
| | | | | `ServiceRequest.bodySite`| _Equivalent_<br/>(33128/33129)| `ServiceRequest.bodySite`| _Equivalent_<br/>(47363/47364)| **`ServiceRequest.bodySite`**
| | | | | | | | | **`ServiceRequest.bodyStructure`**
| | | | | `ServiceRequest.note`| _Equivalent_<br/>(33130/33131)| `ServiceRequest.note`| _Equivalent_<br/>(47365/47366)| **`ServiceRequest.note`**
| | | | | `ServiceRequest.patientInstruction`| _Equivalent_<br/>(33132/33133)| `ServiceRequest.patientInstruction`| →→→→ _RelatedTo_ →→→→ <br/>(47367)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47368)| **`ServiceRequest.patientInstruction`**
| | | | | | | | | **`ServiceRequest.patientInstruction.id`**
| | | | | | | | | **`ServiceRequest.patientInstruction.extension`**
| | | | | | | | | **`ServiceRequest.patientInstruction.modifierExtension`**
| | | | | | | | | **`ServiceRequest.patientInstruction.instruction[x]`**
| | | | | `ServiceRequest.relevantHistory`| _Equivalent_<br/>(33134/33135)| `ServiceRequest.relevantHistory`| _Equivalent_<br/>(47369/47370)| **`ServiceRequest.relevantHistory`**
| *0 of 23 elements used* <br/>remaining elements:<br/>`ProcedureRequest`, `ProcedureRequest.asNeeded[x]`, `ProcedureRequest.bodySite`, `ProcedureRequest.code`, `ProcedureRequest.contained`, `ProcedureRequest.encounter`, `ProcedureRequest.extension`, `ProcedureRequest.id`, `ProcedureRequest.identifier`, `ProcedureRequest.implicitRules`, `ProcedureRequest.language`, `ProcedureRequest.meta`, `ProcedureRequest.modifierExtension`, `ProcedureRequest.notes`, `ProcedureRequest.orderedOn`, `ProcedureRequest.orderer`, `ProcedureRequest.performer`, `ProcedureRequest.priority`, `ProcedureRequest.reason[x]`, `ProcedureRequest.scheduled[x]`, `ProcedureRequest.status`, `ProcedureRequest.subject`, `ProcedureRequest.text`| | *6 of 40 elements used* <br/>remaining elements:<br/>`ProcedureRequest`, `ProcedureRequest.asNeeded[x]`, `ProcedureRequest.authoredOn`, `ProcedureRequest.basedOn`, `ProcedureRequest.bodySite`, `ProcedureRequest.category`, `ProcedureRequest.code`, `ProcedureRequest.contained`, `ProcedureRequest.context`, `ProcedureRequest.definition`, `ProcedureRequest.doNotPerform`, `ProcedureRequest.extension`, `ProcedureRequest.id`, `ProcedureRequest.identifier`, `ProcedureRequest.implicitRules`, `ProcedureRequest.intent`, `ProcedureRequest.language`, `ProcedureRequest.meta`, `ProcedureRequest.modifierExtension`, `ProcedureRequest.note`, `ProcedureRequest.occurrence[x]`, `ProcedureRequest.performer`, `ProcedureRequest.performerType`, `ProcedureRequest.priority`, `ProcedureRequest.reasonCode`, `ProcedureRequest.reasonReference`, `ProcedureRequest.relevantHistory`, `ProcedureRequest.replaces`, `ProcedureRequest.requester`, `ProcedureRequest.requester.agent`, `ProcedureRequest.requester.extension`, `ProcedureRequest.requester.id`, `ProcedureRequest.requester.modifierExtension`, `ProcedureRequest.requester.onBehalfOf`, `ProcedureRequest.requisition`, `ProcedureRequest.specimen`, `ProcedureRequest.status`, `ProcedureRequest.subject`, `ProcedureRequest.supportingInfo`, `ProcedureRequest.text`| | *42 of 42 elements used* | | *42 of 42 elements used* | | *56 of 56 elements used* 


#### Map Group 2

This group is centered on the Structure Definition ServiceRequest from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 ReferralRequest](/docs/R2/Resources/ReferralRequest.md)| Relationship | [R3 ReferralRequest](/docs/R3/Resources/ReferralRequest.md)| Relationship | [R4 ServiceRequest](/docs/R4/Resources/ServiceRequest.md)| Relationship | [R4B ServiceRequest](/docs/R4B/Resources/ServiceRequest.md)| Relationship | R5 ServiceRequest
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | | | `ServiceRequest`| _Equivalent_<br/>(33052/33053)| `ServiceRequest`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47295)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47296)| **`ServiceRequest`**
| | | | | `ServiceRequest.id`| _Equivalent_<br/>(33054/33055)| `ServiceRequest.id`| _Equivalent_<br/>(47297/47298)| **`ServiceRequest.id`**
| | | | | `ServiceRequest.meta`| _Equivalent_<br/>(33056/33057)| `ServiceRequest.meta`| _Equivalent_<br/>(47299/47300)| **`ServiceRequest.meta`**
| | | | | `ServiceRequest.implicitRules`| _Equivalent_<br/>(33058/33059)| `ServiceRequest.implicitRules`| _Equivalent_<br/>(47301/47302)| **`ServiceRequest.implicitRules`**
| | | | | `ServiceRequest.language`| _Equivalent_<br/>(33060/33061)| `ServiceRequest.language`| _Equivalent_<br/>(47303/47304)| **`ServiceRequest.language`**
| | | | | `ServiceRequest.text`| _Equivalent_<br/>(33062/33063)| `ServiceRequest.text`| _Equivalent_<br/>(47305/47306)| **`ServiceRequest.text`**
| | | | | `ServiceRequest.contained`| _Equivalent_<br/>(33064/33065)| `ServiceRequest.contained`| _Equivalent_<br/>(47307/47308)| **`ServiceRequest.contained`**
| | | | | `ServiceRequest.extension`| _Equivalent_<br/>(33066/33067)| `ServiceRequest.extension`| _Equivalent_<br/>(47309/47310)| **`ServiceRequest.extension`**
| | | | | `ServiceRequest.modifierExtension`| _Equivalent_<br/>(33068/33069)| `ServiceRequest.modifierExtension`| _Equivalent_<br/>(47311/47312)| **`ServiceRequest.modifierExtension`**
| | | | | `ServiceRequest.identifier`| _Equivalent_<br/>(33070/33071)| `ServiceRequest.identifier`| _Equivalent_<br/>(47313/47314)| **`ServiceRequest.identifier`**
| | | | | `ServiceRequest.instantiatesCanonical`| _Equivalent_<br/>(33072/33073)| `ServiceRequest.instantiatesCanonical`| _Equivalent_<br/>(47315/47316)| **`ServiceRequest.instantiatesCanonical`**
| | | | | `ServiceRequest.instantiatesUri`| _Equivalent_<br/>(33074/33075)| `ServiceRequest.instantiatesUri`| _Equivalent_<br/>(47317/47318)| **`ServiceRequest.instantiatesUri`**
| | | | | `ServiceRequest.basedOn`| _Equivalent_<br/>(33076/33077)| `ServiceRequest.basedOn`| _Equivalent_<br/>(47319/47320)| **`ServiceRequest.basedOn`**
| | | | | `ServiceRequest.replaces`| _Equivalent_<br/>(33078/33079)| `ServiceRequest.replaces`| _Equivalent_<br/>(47321/47322)| **`ServiceRequest.replaces`**
| | | `ReferralRequest.groupIdentifier`| _Equivalent_<br/>(1259/1669)| `ServiceRequest.requisition`| _Equivalent_<br/>(33080/33081)| `ServiceRequest.requisition`| _Equivalent_<br/>(47323/47324)| **`ServiceRequest.requisition`**
| | | | | `ServiceRequest.status`| _Equivalent_<br/>(33082/33083)| `ServiceRequest.status`| _Equivalent_<br/>(47325/47326)| **`ServiceRequest.status`**
| | | | | `ServiceRequest.intent`| _Equivalent_<br/>(33084/33085)| `ServiceRequest.intent`| _Equivalent_<br/>(47327/47328)| **`ServiceRequest.intent`**
| `ReferralRequest.type`| _Equivalent_<br/>(7595/7596)| `ReferralRequest.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1265)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1664)| `ServiceRequest.category`| _Equivalent_<br/>(33086/33087)| `ServiceRequest.category`| _Equivalent_<br/>(47329/47330)| **`ServiceRequest.category`**
| | | | | `ServiceRequest.priority`| _Equivalent_<br/>(33088/33089)| `ServiceRequest.priority`| _Equivalent_<br/>(47331/47332)| **`ServiceRequest.priority`**
| | | | | `ServiceRequest.doNotPerform`| _Equivalent_<br/>(33090/33091)| `ServiceRequest.doNotPerform`| _Equivalent_<br/>(47333/47334)| **`ServiceRequest.doNotPerform`**
| `ReferralRequest.serviceRequested`| _Equivalent_<br/>(7607/7608)| `ReferralRequest.serviceRequested`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1263)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1665)| `ServiceRequest.code`| _Equivalent_<br/>(33092/33093)| `ServiceRequest.code`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47335)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47336)| **`ServiceRequest.code`**
| | | | | `ServiceRequest.orderDetail`| _Equivalent_<br/>(33094/33095)| `ServiceRequest.orderDetail`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(47337)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47338)| **`ServiceRequest.orderDetail`**
| | | | | | | | | **`ServiceRequest.orderDetail.id`**
| | | | | | | | | **`ServiceRequest.orderDetail.extension`**
| | | | | | | | | **`ServiceRequest.orderDetail.modifierExtension`**
| | | | | | | | | **`ServiceRequest.orderDetail.parameterFocus`**
| | | | | | | | | **`ServiceRequest.orderDetail.parameter`**
| | | | | | | | | **`ServiceRequest.orderDetail.parameter.id`**
| | | | | | | | | **`ServiceRequest.orderDetail.parameter.extension`**
| | | | | | | | | **`ServiceRequest.orderDetail.parameter.modifierExtension`**
| | | | | | | | | **`ServiceRequest.orderDetail.parameter.code`**
| | | | | | | | | **`ServiceRequest.orderDetail.parameter.value[x]`**
| | | | | `ServiceRequest.quantity[x]`| _Equivalent_<br/>(33096/33097)| `ServiceRequest.quantity[x]`| _Equivalent_<br/>(47339/47340)| **`ServiceRequest.quantity[x]`**
| | | | | `ServiceRequest.subject`| _Equivalent_<br/>(33098/33099)| `ServiceRequest.subject`| _Equivalent_<br/>(47341/47342)| **`ServiceRequest.subject`**
| | | | | | | | | **`ServiceRequest.focus`**
| `ReferralRequest.encounter`| →→→→ _RelatedTo_ →→→→ <br/>(397)<hr/>←←←← _RelatedTo_ ←←←← <br/>(741)| `ReferralRequest.context`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1256)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1666)| `ServiceRequest.encounter`| _Equivalent_<br/>(33100/33101)| `ServiceRequest.encounter`| _Equivalent_<br/>(47343/47344)| **`ServiceRequest.encounter`**
| | | | | `ServiceRequest.occurrence[x]`| _Equivalent_<br/>(33102/33103)| `ServiceRequest.occurrence[x]`| _Equivalent_<br/>(47345/47346)| **`ServiceRequest.occurrence[x]`**
| | | | | `ServiceRequest.asNeeded[x]`| _Equivalent_<br/>(33104/33105)| `ServiceRequest.asNeeded[x]`| _Equivalent_<br/>(47347/47348)| **`ServiceRequest.asNeeded[x]`**
| | | | | `ServiceRequest.authoredOn`| _Equivalent_<br/>(33106/33107)| `ServiceRequest.authoredOn`| _Equivalent_<br/>(47349/47350)| **`ServiceRequest.authoredOn`**
| | | `ReferralRequest.requester.agent`| →→→→ _RelatedTo_ →→→→ <br/>(1261)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1668)| `ServiceRequest.requester`| _Equivalent_<br/>(33108/33109)| `ServiceRequest.requester`| _Equivalent_<br/>(47351/47352)| **`ServiceRequest.requester`**
| | | | | `ServiceRequest.performerType`| _Equivalent_<br/>(33110/33111)| `ServiceRequest.performerType`| _Equivalent_<br/>(47353/47354)| **`ServiceRequest.performerType`**
| `ReferralRequest.recipient`| →→→→ _RelatedTo_ →→→→ <br/>(7603)<hr/>←←←← _RelatedTo_ ←←←← <br/>(7604)| `ReferralRequest.recipient`| →→→→ _RelatedTo_ →→→→ <br/>(1260)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1667)| `ServiceRequest.performer`| _Equivalent_<br/>(33112/33113)| `ServiceRequest.performer`| _Equivalent_<br/>(47355/47356)| **`ServiceRequest.performer`**
| | | | | `ServiceRequest.locationCode`| _Equivalent_<br/>(33114/33115)| `ServiceRequest.locationCode`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1949)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2186)| **`ServiceRequest.location`**
| | | | | `ServiceRequest.locationReference`| _Equivalent_<br/>(33116/33117)| `ServiceRequest.locationReference`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1950)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2186)| **`ServiceRequest.location`**
| | | | | `ServiceRequest.reasonCode`| _Equivalent_<br/>(33118/33119)| `ServiceRequest.reasonCode`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1951)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2188)| **`ServiceRequest.reason`**
| | | | | `ServiceRequest.reasonReference`| _Equivalent_<br/>(33120/33121)| `ServiceRequest.reasonReference`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1952)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2188)| **`ServiceRequest.reason`**
| | | | | `ServiceRequest.insurance`| _Equivalent_<br/>(33122/33123)| `ServiceRequest.insurance`| _Equivalent_<br/>(47357/47358)| **`ServiceRequest.insurance`**
| | | | | `ServiceRequest.supportingInfo`| _Equivalent_<br/>(33124/33125)| `ServiceRequest.supportingInfo`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47359)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47360)| **`ServiceRequest.supportingInfo`**
| | | | | `ServiceRequest.specimen`| _Equivalent_<br/>(33126/33127)| `ServiceRequest.specimen`| _Equivalent_<br/>(47361/47362)| **`ServiceRequest.specimen`**
| | | | | `ServiceRequest.bodySite`| _Equivalent_<br/>(33128/33129)| `ServiceRequest.bodySite`| _Equivalent_<br/>(47363/47364)| **`ServiceRequest.bodySite`**
| | | | | | | | | **`ServiceRequest.bodyStructure`**
| | | | | `ServiceRequest.note`| _Equivalent_<br/>(33130/33131)| `ServiceRequest.note`| _Equivalent_<br/>(47365/47366)| **`ServiceRequest.note`**
| | | | | `ServiceRequest.patientInstruction`| _Equivalent_<br/>(33132/33133)| `ServiceRequest.patientInstruction`| →→→→ _RelatedTo_ →→→→ <br/>(47367)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47368)| **`ServiceRequest.patientInstruction`**
| | | | | | | | | **`ServiceRequest.patientInstruction.id`**
| | | | | | | | | **`ServiceRequest.patientInstruction.extension`**
| | | | | | | | | **`ServiceRequest.patientInstruction.modifierExtension`**
| | | | | | | | | **`ServiceRequest.patientInstruction.instruction[x]`**
| | | | | `ServiceRequest.relevantHistory`| _Equivalent_<br/>(33134/33135)| `ServiceRequest.relevantHistory`| _Equivalent_<br/>(47369/47370)| **`ServiceRequest.relevantHistory`**
| *4 of 25 elements used* <br/>remaining elements:<br/>`ReferralRequest`, `ReferralRequest.contained`, `ReferralRequest.date`, `ReferralRequest.dateSent`, `ReferralRequest.description`, `ReferralRequest.extension`, `ReferralRequest.fulfillmentTime`, `ReferralRequest.id`, `ReferralRequest.identifier`, `ReferralRequest.implicitRules`, `ReferralRequest.language`, `ReferralRequest.meta`, `ReferralRequest.modifierExtension`, `ReferralRequest.patient`, `ReferralRequest.priority`, `ReferralRequest.reason`, `ReferralRequest.requester`, `ReferralRequest.specialty`, `ReferralRequest.status`, `ReferralRequest.supportingInformation`, `ReferralRequest.text`| | *6 of 37 elements used* <br/>remaining elements:<br/>`ReferralRequest`, `ReferralRequest.authoredOn`, `ReferralRequest.basedOn`, `ReferralRequest.contained`, `ReferralRequest.definition`, `ReferralRequest.description`, `ReferralRequest.extension`, `ReferralRequest.id`, `ReferralRequest.identifier`, `ReferralRequest.implicitRules`, `ReferralRequest.intent`, `ReferralRequest.language`, `ReferralRequest.meta`, `ReferralRequest.modifierExtension`, `ReferralRequest.note`, `ReferralRequest.occurrence[x]`, `ReferralRequest.priority`, `ReferralRequest.reasonCode`, `ReferralRequest.reasonReference`, `ReferralRequest.relevantHistory`, `ReferralRequest.replaces`, `ReferralRequest.requester`, `ReferralRequest.requester.extension`, `ReferralRequest.requester.id`, `ReferralRequest.requester.modifierExtension`, `ReferralRequest.requester.onBehalfOf`, `ReferralRequest.specialty`, `ReferralRequest.status`, `ReferralRequest.subject`, `ReferralRequest.supportingInfo`, `ReferralRequest.text`| | *42 of 42 elements used* | | *42 of 42 elements used* | | *56 of 56 elements used* 

