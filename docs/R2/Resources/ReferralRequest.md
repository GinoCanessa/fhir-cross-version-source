Comparison of 
Generated at Monday, April 14, 2025 6:17:18 PM

### ReferralRequest

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | ReferralRequest |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ReferralRequest` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for ReferralRequest Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `121` |
| Database Snapshot Count | `25` |
| Database Differential Count | `17` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ReferralRequest` | `ReferralRequest` | `ReferralRequest` | ReferralRequest | A request for referral or transfer of care | 0..* | ReferralRequest |  |  |
| `ReferralRequest.contained` | `ReferralRequest.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ReferralRequest.date` | `ReferralRequest.date` | `date` |  | Date of creation/activation | 0..1 | dateTime |  |  |
| `ReferralRequest.dateSent` | `ReferralRequest.dateSent` | `dateSent` |  | Date referral/transfer of care request is sent | 0..1 | dateTime |  |  |
| `ReferralRequest.description` | `ReferralRequest.description` | `description` |  | A textual description of the referral | 0..1 | string |  |  |
| `ReferralRequest.encounter` | `ReferralRequest.encounter` | `encounter` |  | Originating encounter | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `ReferralRequest.extension` | `ReferralRequest.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ReferralRequest.fulfillmentTime` | `ReferralRequest.fulfillmentTime` | `fulfillmentTime` |  | Requested service(s) fulfillment time | 0..1 | Period |  |  |
| `ReferralRequest.id` | `ReferralRequest.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ReferralRequest.identifier` | `ReferralRequest.identifier` | `identifier` |  | Business identifier | 0..* | Identifier |  |  |
| `ReferralRequest.implicitRules` | `ReferralRequest.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ReferralRequest.language` | `ReferralRequest.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `ReferralRequest.meta` | `ReferralRequest.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ReferralRequest.modifierExtension` | `ReferralRequest.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ReferralRequest.patient` | `ReferralRequest.patient` | `patient` |  | Patient referred to care or transfer | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `ReferralRequest.priority` | `ReferralRequest.priority` | `priority` |  | Urgency of referral / transfer of care request | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/diagnostic-order-priority` |
| `ReferralRequest.reason` | `ReferralRequest.reason` | `reason` |  | Reason for referral / transfer of care request | 0..1 | CodeableConcept | `Example` |  |
| `ReferralRequest.recipient` | `ReferralRequest.recipient` | `recipient` |  | Receiver of referral / transfer of care request | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `ReferralRequest.requester` | `ReferralRequest.requester` | `requester` |  | Requester of referral / transfer of care | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `ReferralRequest.serviceRequested` | `ReferralRequest.serviceRequested` | `serviceRequested` |  | Actions requested as part of the referral | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/c80-practice-codes` |
| `ReferralRequest.specialty` | `ReferralRequest.specialty` | `specialty` |  | The clinical specialty (discipline) that the referral is requested for | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/practitioner-specialty` |
| `ReferralRequest.status` | `ReferralRequest.status` | `status` |  | draft \| requested \| active \| cancelled \| accepted \| rejected \| completed | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/referralstatus` |
| `ReferralRequest.supportingInformation` | `ReferralRequest.supportingInformation` | `supportingInformation` |  | Additonal information to support referral or transfer of care request | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `ReferralRequest.text` | `ReferralRequest.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `ReferralRequest.type` | `ReferralRequest.type` | `type` |  | Referral/Transition of care request type | 0..1 | CodeableConcept | `Example` |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ReferralRequest](/docs/R2/Resources/ReferralRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ReferralRequest\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `150`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `316`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ReferralRequest](/docs/R3/Resources/ReferralRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ReferralRequest\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `507`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `708`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ServiceRequest](/docs/R4/Resources/ServiceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ServiceRequest\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1613`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1614`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ServiceRequest](/docs/R4B/Resources/ServiceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ServiceRequest\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1040`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1269`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [ServiceRequest](/docs/R5/Resources/ServiceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ServiceRequest\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ReferralRequest from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 ReferralRequest| Relationship | [R3 ReferralRequest](/docs/R3/Resources/ReferralRequest.md)| Relationship | [R4 ServiceRequest](/docs/R4/Resources/ServiceRequest.md)| Relationship | [R4B ServiceRequest](/docs/R4B/Resources/ServiceRequest.md)| Relationship | [R5 ServiceRequest](/docs/R5/Resources/ServiceRequest.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`ReferralRequest`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7573)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7574)| `ReferralRequest`| | | | | | | 
| **`ReferralRequest.id`**| _Equivalent_<br/>(7575/7576)| `ReferralRequest.id`| | | | | | | 
| **`ReferralRequest.meta`**| _Equivalent_<br/>(7577/7578)| `ReferralRequest.meta`| | | | | | | 
| **`ReferralRequest.implicitRules`**| _Equivalent_<br/>(7579/7580)| `ReferralRequest.implicitRules`| | | | | | | 
| **`ReferralRequest.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7581)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7582)| `ReferralRequest.language`| | | | | | | 
| **`ReferralRequest.text`**| _Equivalent_<br/>(7583/7584)| `ReferralRequest.text`| | | | | | | 
| **`ReferralRequest.contained`**| _Equivalent_<br/>(7585/7586)| `ReferralRequest.contained`| | | | | | | 
| **`ReferralRequest.extension`**| _Equivalent_<br/>(7587/7588)| `ReferralRequest.extension`| | | | | | | 
| **`ReferralRequest.modifierExtension`**| _Equivalent_<br/>(7589/7590)| `ReferralRequest.modifierExtension`| | | | | | | 
| **`ReferralRequest.status`**| →→→→ _Equivalent_ →→→→ <br/>(7591)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7592)| `ReferralRequest.status`| | | | | | | 
| **`ReferralRequest.identifier`**| _Equivalent_<br/>(7593/7594)| `ReferralRequest.identifier`| | | | | | | 
| **`ReferralRequest.date`**| _Equivalent_<br/>(395/740)| `ReferralRequest.authoredOn`| | | | | | | 
| **`ReferralRequest.type`**| _Equivalent_<br/>(7595/7596)| `ReferralRequest.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1265)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1664)| `ServiceRequest.category`| _Equivalent_<br/>(33086/33087)| `ServiceRequest.category`| _Equivalent_<br/>(47329/47330)| `ServiceRequest.category`
| **`ReferralRequest.specialty`**| _Equivalent_<br/>(7597/7598)| `ReferralRequest.specialty`| | | | | | | 
| **`ReferralRequest.priority`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7599)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7600)| `ReferralRequest.priority`| | | | | | | 
| **`ReferralRequest.patient`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(399)<hr/>←←←← _RelatedTo_ ←←←← <br/>(744)| `ReferralRequest.subject`| | | | | | | 
| **`ReferralRequest.requester`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(7601)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7602)| `ReferralRequest.requester`| | | | | | | 
| **`ReferralRequest.recipient`**| →→→→ _RelatedTo_ →→→→ <br/>(7603)<hr/>←←←← _RelatedTo_ ←←←← <br/>(7604)| `ReferralRequest.recipient`| →→→→ _RelatedTo_ →→→→ <br/>(1260)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1667)| `ServiceRequest.performer`| _Equivalent_<br/>(33112/33113)| `ServiceRequest.performer`| _Equivalent_<br/>(47355/47356)| `ServiceRequest.performer`
| **`ReferralRequest.encounter`**| →→→→ _RelatedTo_ →→→→ <br/>(397)<hr/>←←←← _RelatedTo_ ←←←← <br/>(741)| `ReferralRequest.context`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1256)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1666)| `ServiceRequest.encounter`| _Equivalent_<br/>(33100/33101)| `ServiceRequest.encounter`| _Equivalent_<br/>(47343/47344)| `ServiceRequest.encounter`
| **`ReferralRequest.dateSent`**| | | | | | | | | 
| **`ReferralRequest.reason`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(400)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(743)| `ReferralRequest.reasonCode`| | | | | | | 
| **`ReferralRequest.description`**| _Equivalent_<br/>(7605/7606)| `ReferralRequest.description`| | | | | | | 
| **`ReferralRequest.serviceRequested`**| _Equivalent_<br/>(7607/7608)| `ReferralRequest.serviceRequested`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1263)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(1665)| `ServiceRequest.code`| _Equivalent_<br/>(33092/33093)| `ServiceRequest.code`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(47335)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(47336)| `ServiceRequest.code`
| **`ReferralRequest.supportingInformation`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(401)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(745)| `ReferralRequest.supportingInfo`| | | | | | | 
| **`ReferralRequest.fulfillmentTime`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(398)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(742)| `ReferralRequest.occurrence[x]`| | | | | | | 
| *25 of 25 elements used* | | *24 of 37 elements used* <br/>remaining elements:<br/>`ReferralRequest.basedOn`, `ReferralRequest.definition`, `ReferralRequest.groupIdentifier`, `ReferralRequest.intent`, `ReferralRequest.note`, `ReferralRequest.reasonReference`, `ReferralRequest.relevantHistory`, `ReferralRequest.replaces`, `ReferralRequest.requester.agent`, `ReferralRequest.requester.extension`, `ReferralRequest.requester.id`, `ReferralRequest.requester.modifierExtension`, `ReferralRequest.requester.onBehalfOf`| | *4 of 42 elements used* <br/>remaining elements:<br/>`ServiceRequest`, `ServiceRequest.asNeeded[x]`, `ServiceRequest.authoredOn`, `ServiceRequest.basedOn`, `ServiceRequest.bodySite`, `ServiceRequest.contained`, `ServiceRequest.doNotPerform`, `ServiceRequest.extension`, `ServiceRequest.id`, `ServiceRequest.identifier`, `ServiceRequest.implicitRules`, `ServiceRequest.instantiatesCanonical`, `ServiceRequest.instantiatesUri`, `ServiceRequest.insurance`, `ServiceRequest.intent`, `ServiceRequest.language`, `ServiceRequest.locationCode`, `ServiceRequest.locationReference`, `ServiceRequest.meta`, `ServiceRequest.modifierExtension`, `ServiceRequest.note`, `ServiceRequest.occurrence[x]`, `ServiceRequest.orderDetail`, `ServiceRequest.patientInstruction`, `ServiceRequest.performerType`, `ServiceRequest.priority`, `ServiceRequest.quantity[x]`, `ServiceRequest.reasonCode`, `ServiceRequest.reasonReference`, `ServiceRequest.relevantHistory`, `ServiceRequest.replaces`, `ServiceRequest.requester`, `ServiceRequest.requisition`, `ServiceRequest.specimen`, `ServiceRequest.status`, `ServiceRequest.subject`, `ServiceRequest.supportingInfo`, `ServiceRequest.text`| | *4 of 42 elements used* <br/>remaining elements:<br/>`ServiceRequest`, `ServiceRequest.asNeeded[x]`, `ServiceRequest.authoredOn`, `ServiceRequest.basedOn`, `ServiceRequest.bodySite`, `ServiceRequest.contained`, `ServiceRequest.doNotPerform`, `ServiceRequest.extension`, `ServiceRequest.id`, `ServiceRequest.identifier`, `ServiceRequest.implicitRules`, `ServiceRequest.instantiatesCanonical`, `ServiceRequest.instantiatesUri`, `ServiceRequest.insurance`, `ServiceRequest.intent`, `ServiceRequest.language`, `ServiceRequest.locationCode`, `ServiceRequest.locationReference`, `ServiceRequest.meta`, `ServiceRequest.modifierExtension`, `ServiceRequest.note`, `ServiceRequest.occurrence[x]`, `ServiceRequest.orderDetail`, `ServiceRequest.patientInstruction`, `ServiceRequest.performerType`, `ServiceRequest.priority`, `ServiceRequest.quantity[x]`, `ServiceRequest.reasonCode`, `ServiceRequest.reasonReference`, `ServiceRequest.relevantHistory`, `ServiceRequest.replaces`, `ServiceRequest.requester`, `ServiceRequest.requisition`, `ServiceRequest.specimen`, `ServiceRequest.status`, `ServiceRequest.subject`, `ServiceRequest.supportingInfo`, `ServiceRequest.text`| | *4 of 56 elements used* <br/>remaining elements:<br/>`ServiceRequest`, `ServiceRequest.asNeeded[x]`, `ServiceRequest.authoredOn`, `ServiceRequest.basedOn`, `ServiceRequest.bodySite`, `ServiceRequest.bodyStructure`, `ServiceRequest.contained`, `ServiceRequest.doNotPerform`, `ServiceRequest.extension`, `ServiceRequest.focus`, `ServiceRequest.id`, `ServiceRequest.identifier`, `ServiceRequest.implicitRules`, `ServiceRequest.instantiatesCanonical`, `ServiceRequest.instantiatesUri`, `ServiceRequest.insurance`, `ServiceRequest.intent`, `ServiceRequest.language`, `ServiceRequest.location`, `ServiceRequest.meta`, `ServiceRequest.modifierExtension`, `ServiceRequest.note`, `ServiceRequest.occurrence[x]`, `ServiceRequest.orderDetail`, `ServiceRequest.orderDetail.extension`, `ServiceRequest.orderDetail.id`, `ServiceRequest.orderDetail.modifierExtension`, `ServiceRequest.orderDetail.parameter`, `ServiceRequest.orderDetail.parameter.code`, `ServiceRequest.orderDetail.parameter.extension`, `ServiceRequest.orderDetail.parameter.id`, `ServiceRequest.orderDetail.parameter.modifierExtension`, `ServiceRequest.orderDetail.parameter.value[x]`, `ServiceRequest.orderDetail.parameterFocus`, `ServiceRequest.patientInstruction`, `ServiceRequest.patientInstruction.extension`, `ServiceRequest.patientInstruction.id`, `ServiceRequest.patientInstruction.instruction[x]`, `ServiceRequest.patientInstruction.modifierExtension`, `ServiceRequest.performerType`, `ServiceRequest.priority`, `ServiceRequest.quantity[x]`, `ServiceRequest.reason`, `ServiceRequest.relevantHistory`, `ServiceRequest.replaces`, `ServiceRequest.requester`, `ServiceRequest.requisition`, `ServiceRequest.specimen`, `ServiceRequest.status`, `ServiceRequest.subject`, `ServiceRequest.supportingInfo`, `ServiceRequest.text`

