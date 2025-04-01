Comparison of 
Generated at Tuesday, April 1, 2025 1:39:09 PM

### ProcedureRequest

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | ProcedureRequest |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ProcedureRequest` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for ProcedureRequest Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `115` |
| Database Snapshot Count | `23` |
| Database Differential Count | `15` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ProcedureRequest` | `ProcedureRequest` | `ProcedureRequest` | ProcedureRequest | A request for a procedure to be performed | 0..* | ProcedureRequest |  |  |
| `ProcedureRequest.asNeeded[x]` | `ProcedureRequest.asNeeded[x]` | `asNeeded[x]` |  | Preconditions for procedure | 0..1 | boolean, CodeableConcept | `Example` |  |
| `ProcedureRequest.bodySite` | `ProcedureRequest.bodySite` | `bodySite` |  | What part of body to perform on | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/body-site` |
| `ProcedureRequest.code` | `ProcedureRequest.code` | `code` |  | What procedure to perform | 1..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/procedure-code` |
| `ProcedureRequest.contained` | `ProcedureRequest.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ProcedureRequest.encounter` | `ProcedureRequest.encounter` | `encounter` |  | Encounter request created during | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `ProcedureRequest.extension` | `ProcedureRequest.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ProcedureRequest.id` | `ProcedureRequest.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ProcedureRequest.identifier` | `ProcedureRequest.identifier` | `identifier` |  | Unique identifier for the request | 0..* | Identifier |  |  |
| `ProcedureRequest.implicitRules` | `ProcedureRequest.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ProcedureRequest.language` | `ProcedureRequest.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `ProcedureRequest.meta` | `ProcedureRequest.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ProcedureRequest.modifierExtension` | `ProcedureRequest.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ProcedureRequest.notes` | `ProcedureRequest.notes` | `notes` |  | Additional information about desired procedure | 0..* | Annotation |  |  |
| `ProcedureRequest.orderedOn` | `ProcedureRequest.orderedOn` | `orderedOn` |  | When request was created | 0..1 | dateTime |  |  |
| `ProcedureRequest.orderer` | `ProcedureRequest.orderer` | `orderer` |  | Who made request | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `ProcedureRequest.performer` | `ProcedureRequest.performer` | `performer` |  | Who should perform the procedure | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `ProcedureRequest.priority` | `ProcedureRequest.priority` | `priority` |  | routine \| urgent \| stat \| asap | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/procedure-request-priority` |
| `ProcedureRequest.reason[x]` | `ProcedureRequest.reason[x]` | `reason[x]` |  | Why procedure should occur | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Condition) | `Example` | `http://hl7.org/fhir/ValueSet/procedure-reason` |
| `ProcedureRequest.scheduled[x]` | `ProcedureRequest.scheduled[x]` | `scheduled[x]` |  | When procedure should occur | 0..1 | dateTime, Period, Timing |  |  |
| `ProcedureRequest.status` | `ProcedureRequest.status` | `status` |  | proposed \| draft \| requested \| received \| accepted \| in-progress \| completed \| suspended \| rejected \| aborted | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/procedure-request-status` |
| `ProcedureRequest.subject` | `ProcedureRequest.subject` | `subject` |  | Who the procedure should be done to | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `ProcedureRequest.text` | `ProcedureRequest.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ProcedureRequest](/docs/R2/Resources/ProcedureRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ProcedureRequest\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `155`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `321`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ProcedureRequest](/docs/R3/Resources/ProcedureRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ProcedureRequest\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `515`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `707`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ServiceRequest](/docs/R4/Resources/ServiceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ServiceRequest\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1613`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1614`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ServiceRequest](/docs/R4B/Resources/ServiceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ServiceRequest\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1040`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1269`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ServiceRequest](/docs/R5/Resources/ServiceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/ServiceRequest\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ProcedureRequest from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 ProcedureRequest| Relationship | [R3 ProcedureRequest](/docs/R3/Resources/ProcedureRequest.md)| Relationship | [R4 ServiceRequest](/docs/R4/Resources/ServiceRequest.md)| Relationship | [R4B ServiceRequest](/docs/R4B/Resources/ServiceRequest.md)| Relationship | [R5 ServiceRequest](/docs/R5/Resources/ServiceRequest.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`ProcedureRequest`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7307)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7308)| `ProcedureRequest`| | | | | | | 
| **`ProcedureRequest.id`**| _Equivalent_<br/>(7309/7310)| `ProcedureRequest.id`| | | | | | | 
| **`ProcedureRequest.meta`**| _Equivalent_<br/>(7311/7312)| `ProcedureRequest.meta`| | | | | | | 
| **`ProcedureRequest.implicitRules`**| _Equivalent_<br/>(7313/7314)| `ProcedureRequest.implicitRules`| | | | | | | 
| **`ProcedureRequest.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7315)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7316)| `ProcedureRequest.language`| | | | | | | 
| **`ProcedureRequest.text`**| _Equivalent_<br/>(7317/7318)| `ProcedureRequest.text`| | | | | | | 
| **`ProcedureRequest.contained`**| _Equivalent_<br/>(7319/7320)| `ProcedureRequest.contained`| | | | | | | 
| **`ProcedureRequest.extension`**| _Equivalent_<br/>(7321/7322)| `ProcedureRequest.extension`| | | | | | | 
| **`ProcedureRequest.modifierExtension`**| _Equivalent_<br/>(7323/7324)| `ProcedureRequest.modifierExtension`| | | | | | | 
| **`ProcedureRequest.identifier`**| _Equivalent_<br/>(7325/7326)| `ProcedureRequest.identifier`| | | | | | | 
| **`ProcedureRequest.subject`**| →→→→ _RelatedTo_ →→→→ <br/>(7327)<hr/>←←←← _RelatedTo_ ←←←← <br/>(7328)| `ProcedureRequest.subject`| | | | | | | 
| **`ProcedureRequest.code`**| _Equivalent_<br/>(7329/7330)| `ProcedureRequest.code`| | | | | | | 
| **`ProcedureRequest.bodySite`**| _Equivalent_<br/>(7331/7332)| `ProcedureRequest.bodySite`| | | | | | | 
| **`ProcedureRequest.reason[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(345)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(791)| `ProcedureRequest.reasonCode`| | | | | | | 
| **`ProcedureRequest.reason[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(345)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(791)| `ProcedureRequest.reasonReference`| | | | | | | 
| **`ProcedureRequest.scheduled[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(346)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(792)| `ProcedureRequest.occurrence[x]`| | | | | | | 
| **`ProcedureRequest.encounter`**| →→→→ _RelatedTo_ →→→→ <br/>(340)<hr/>←←←← _RelatedTo_ ←←←← <br/>(793)| `ProcedureRequest.context`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1237)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(17511)| `ServiceRequest.encounter`| _Equivalent_<br/>(33100/33101)| `ServiceRequest.encounter`| _Equivalent_<br/>(47343/47344)| `ServiceRequest.encounter`
| **`ProcedureRequest.performer`**| →→→→ _RelatedTo_ →→→→ <br/>(7333)<hr/>←←←← _RelatedTo_ ←←←← <br/>(7334)| `ProcedureRequest.performer`| | | | | | | 
| **`ProcedureRequest.status`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7335)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7336)| `ProcedureRequest.status`| | | | | | | 
| **`ProcedureRequest.notes`**| _Equivalent_<br/>(341/794)| `ProcedureRequest.note`| | | | | | | 
| **`ProcedureRequest.asNeeded[x]`**| _Equivalent_<br/>(7337/7338)| `ProcedureRequest.asNeeded[x]`| | | | | | | 
| **`ProcedureRequest.orderedOn`**| _Equivalent_<br/>(342/795)| `ProcedureRequest.authoredOn`| | | | | | | 
| **`ProcedureRequest.orderer`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(343)<hr/>←←←← _RelatedTo_ ←←←← <br/>(7339)| `ProcedureRequest.requester.agent`| →→→→ _RelatedTo_ →→→→ <br/>(1239)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(17519)| `ServiceRequest.requester`| _Equivalent_<br/>(33108/33109)| `ServiceRequest.requester`| _Equivalent_<br/>(47351/47352)| `ServiceRequest.requester`
| **`ProcedureRequest.priority`**| _Equivalent_<br/>(7340/7341)| `ProcedureRequest.priority`| | | | | | | 
| *23 of 23 elements used* | | *24 of 40 elements used* | | *2 of 42 elements used* | | *2 of 42 elements used* | | *2 of 56 elements used* 

