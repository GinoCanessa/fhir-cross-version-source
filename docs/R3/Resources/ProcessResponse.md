Comparison of 
Generated at Friday, April 4, 2025 2:58:39 PM

### ProcessResponse

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | ProcessResponse |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/ProcessResponse` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for ProcessResponse Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `566` |
| Database Snapshot Count | `27` |
| Database Differential Count | `16` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `ProcessResponse` | `ProcessResponse` | `ProcessResponse` | ProcessResponse | ProcessResponse resource | 0..* | ProcessResponse |  |  |
| `ProcessResponse.communicationRequest` | `ProcessResponse.communicationRequest` | `communicationRequest` |  | Request for additional information | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/CommunicationRequest) |  |  |
| `ProcessResponse.contained` | `ProcessResponse.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `ProcessResponse.created` | `ProcessResponse.created` | `created` |  | Creation date | 0..1 | dateTime |  |  |
| `ProcessResponse.disposition` | `ProcessResponse.disposition` | `disposition` |  | Disposition Message | 0..1 | string |  |  |
| `ProcessResponse.error` | `ProcessResponse.error` | `error` |  | Error code | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/adjudication-error` |
| `ProcessResponse.extension` | `ProcessResponse.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ProcessResponse.form` | `ProcessResponse.form` | `form` |  | Printed Form Identifier | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/forms` |
| `ProcessResponse.id` | `ProcessResponse.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `ProcessResponse.identifier` | `ProcessResponse.identifier` | `identifier` |  | Business Identifier | 0..* | Identifier |  |  |
| `ProcessResponse.implicitRules` | `ProcessResponse.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `ProcessResponse.language` | `ProcessResponse.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `ProcessResponse.meta` | `ProcessResponse.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `ProcessResponse.modifierExtension` | `ProcessResponse.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ProcessResponse.organization` | `ProcessResponse.organization` | `organization` |  | Authoring Organization | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `ProcessResponse.outcome` | `ProcessResponse.outcome` | `outcome` |  | Processing outcome | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/process-outcome` |
| `ProcessResponse.processNote` | `ProcessResponse.processNote` | `processNote` |  | Processing comments or additional requirements | 0..* | BackboneElement |  |  |
| `ProcessResponse.processNote.extension` | `ProcessResponse.processNote.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `ProcessResponse.processNote.id` | `ProcessResponse.processNote.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `ProcessResponse.processNote.modifierExtension` | `ProcessResponse.processNote.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `ProcessResponse.processNote.text` | `ProcessResponse.processNote.text` | `text` |  | Comment on the processing | 0..1 | string |  |  |
| `ProcessResponse.processNote.type` | `ProcessResponse.processNote.type` | `type` |  | display \| print \| printoper | 0..1 | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/note-type` |
| `ProcessResponse.request` | `ProcessResponse.request` | `request` |  | Request reference | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `ProcessResponse.requestOrganization` | `ProcessResponse.requestOrganization` | `requestOrganization` |  | Responsible organization | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `ProcessResponse.requestProvider` | `ProcessResponse.requestProvider` | `requestProvider` |  | Responsible Practitioner | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `ProcessResponse.status` | `ProcessResponse.status` | `status` |  | active \| cancelled \| draft \| entered-in-error | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/fm-status` |
| `ProcessResponse.text` | `ProcessResponse.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [ProcessResponse](/docs/R2/Resources/ProcessResponse.md)<br/> `http://hl7.org/fhir/StructureDefinition/ProcessResponse\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `146`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `312`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [ProcessResponse](/docs/R3/Resources/ProcessResponse.md)<br/> `http://hl7.org/fhir/StructureDefinition/ProcessResponse\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `503`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `720`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Task](/docs/R4/Resources/Task.md)<br/> `http://hl7.org/fhir/StructureDefinition/Task\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1633`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1634`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Task](/docs/R4B/Resources/Task.md)<br/> `http://hl7.org/fhir/StructureDefinition/Task\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `1053`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1282`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [Task](/docs/R5/Resources/Task.md)<br/> `http://hl7.org/fhir/StructureDefinition/Task\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition ProcessResponse from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 ProcessResponse](/docs/R2/Resources/ProcessResponse.md)| Relationship | R3 ProcessResponse| Relationship | [R4 Task](/docs/R4/Resources/Task.md)| Relationship | [R4B Task](/docs/R4B/Resources/Task.md)| Relationship | [R5 Task](/docs/R5/Resources/Task.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| `ProcessResponse`| _Equivalent_<br/>(7396/7397)| **`ProcessResponse`**| | | | | | | 
| `ProcessResponse.id`| _Equivalent_<br/>(7398/7399)| **`ProcessResponse.id`**| | | | | | | 
| `ProcessResponse.meta`| _Equivalent_<br/>(7400/7401)| **`ProcessResponse.meta`**| | | | | | | 
| `ProcessResponse.implicitRules`| _Equivalent_<br/>(7402/7403)| **`ProcessResponse.implicitRules`**| | | | | | | 
| `ProcessResponse.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7404)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7405)| **`ProcessResponse.language`**| | | | | | | 
| `ProcessResponse.text`| _Equivalent_<br/>(7406/7407)| **`ProcessResponse.text`**| | | | | | | 
| `ProcessResponse.contained`| _Equivalent_<br/>(7408/7409)| **`ProcessResponse.contained`**| | | | | | | 
| `ProcessResponse.extension`| _Equivalent_<br/>(7410/7411)| **`ProcessResponse.extension`**| | | | | | | 
| `ProcessResponse.modifierExtension`| _Equivalent_<br/>(7412/7413)| **`ProcessResponse.modifierExtension`**| | | | | | | 
| `ProcessResponse.identifier`| _Equivalent_<br/>(7414/7415)| **`ProcessResponse.identifier`**| | | | | | | 
| | | **`ProcessResponse.status`**| | | | | | | 
| `ProcessResponse.created`| _Equivalent_<br/>(7422/7423)| **`ProcessResponse.created`**| | | | | | | 
| `ProcessResponse.organization`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7424)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7425)| **`ProcessResponse.organization`**| | | | | | | 
| `ProcessResponse.request`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7416)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7417)| **`ProcessResponse.request`**| | | | | | | 
| `ProcessResponse.outcome`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(7418)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7419)| **`ProcessResponse.outcome`**| | | | | | | 
| `ProcessResponse.disposition`| _Equivalent_<br/>(7420/7421)| **`ProcessResponse.disposition`**| | | | | | | 
| `ProcessResponse.requestProvider`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7426)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7427)| **`ProcessResponse.requestProvider`**| | | | | | | 
| `ProcessResponse.requestOrganization`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7428)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(7429)| **`ProcessResponse.requestOrganization`**| | | | | | | 
| `ProcessResponse.form`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7430)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7431)| **`ProcessResponse.form`**| | | | | | | 
| `ProcessResponse.notes`| _Equivalent_<br/>(349/701)| **`ProcessResponse.processNote`**| | | | | | | 
| | | **`ProcessResponse.processNote.id`**| | | | | | | 
| | | **`ProcessResponse.processNote.extension`**| | | | | | | 
| | | **`ProcessResponse.processNote.modifierExtension`**| | | | | | | 
| `ProcessResponse.notes.type`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(351)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(703)| **`ProcessResponse.processNote.type`**| | | | | | | 
| `ProcessResponse.notes.text`| _Equivalent_<br/>(350/702)| **`ProcessResponse.processNote.text`**| | | | | | | 
| `ProcessResponse.error`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(7435)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(7436)| **`ProcessResponse.error`**| | | | | | | 
| | | **`ProcessResponse.communicationRequest`**| | | | | | | 
| *22 of 27 elements used* <br/>remaining elements:<br/>`ProcessResponse.notes.extension`, `ProcessResponse.notes.id`, `ProcessResponse.notes.modifierExtension`, `ProcessResponse.originalRuleset`, `ProcessResponse.ruleset`| | *27 of 27 elements used* | | *0 of 56 elements used* <br/>remaining elements:<br/>`Task`, `Task.authoredOn`, `Task.basedOn`, `Task.businessStatus`, `Task.code`, `Task.contained`, `Task.description`, `Task.encounter`, `Task.executionPeriod`, `Task.extension`, `Task.focus`, `Task.for`, `Task.groupIdentifier`, `Task.id`, `Task.identifier`, `Task.implicitRules`, `Task.input`, `Task.input.extension`, `Task.input.id`, `Task.input.modifierExtension`, `Task.input.type`, `Task.input.value[x]`, `Task.instantiatesCanonical`, `Task.instantiatesUri`, `Task.insurance`, `Task.intent`, `Task.language`, `Task.lastModified`, `Task.location`, `Task.meta`, `Task.modifierExtension`, `Task.note`, `Task.output`, `Task.output.extension`, `Task.output.id`, `Task.output.modifierExtension`, `Task.output.type`, `Task.output.value[x]`, `Task.owner`, `Task.partOf`, `Task.performerType`, `Task.priority`, `Task.reasonCode`, `Task.reasonReference`, `Task.relevantHistory`, `Task.requester`, `Task.restriction`, `Task.restriction.extension`, `Task.restriction.id`, `Task.restriction.modifierExtension`, `Task.restriction.period`, `Task.restriction.recipient`, `Task.restriction.repetitions`, `Task.status`, `Task.statusReason`, `Task.text`| | *0 of 56 elements used* <br/>remaining elements:<br/>`Task`, `Task.authoredOn`, `Task.basedOn`, `Task.businessStatus`, `Task.code`, `Task.contained`, `Task.description`, `Task.encounter`, `Task.executionPeriod`, `Task.extension`, `Task.focus`, `Task.for`, `Task.groupIdentifier`, `Task.id`, `Task.identifier`, `Task.implicitRules`, `Task.input`, `Task.input.extension`, `Task.input.id`, `Task.input.modifierExtension`, `Task.input.type`, `Task.input.value[x]`, `Task.instantiatesCanonical`, `Task.instantiatesUri`, `Task.insurance`, `Task.intent`, `Task.language`, `Task.lastModified`, `Task.location`, `Task.meta`, `Task.modifierExtension`, `Task.note`, `Task.output`, `Task.output.extension`, `Task.output.id`, `Task.output.modifierExtension`, `Task.output.type`, `Task.output.value[x]`, `Task.owner`, `Task.partOf`, `Task.performerType`, `Task.priority`, `Task.reasonCode`, `Task.reasonReference`, `Task.relevantHistory`, `Task.requester`, `Task.restriction`, `Task.restriction.extension`, `Task.restriction.id`, `Task.restriction.modifierExtension`, `Task.restriction.period`, `Task.restriction.recipient`, `Task.restriction.repetitions`, `Task.status`, `Task.statusReason`, `Task.text`| | *0 of 63 elements used* <br/>remaining elements:<br/>`Task`, `Task.authoredOn`, `Task.basedOn`, `Task.businessStatus`, `Task.code`, `Task.contained`, `Task.description`, `Task.doNotPerform`, `Task.encounter`, `Task.executionPeriod`, `Task.extension`, `Task.focus`, `Task.for`, `Task.groupIdentifier`, `Task.id`, `Task.identifier`, `Task.implicitRules`, `Task.input`, `Task.input.extension`, `Task.input.id`, `Task.input.modifierExtension`, `Task.input.type`, `Task.input.value[x]`, `Task.instantiatesCanonical`, `Task.instantiatesUri`, `Task.insurance`, `Task.intent`, `Task.language`, `Task.lastModified`, `Task.location`, `Task.meta`, `Task.modifierExtension`, `Task.note`, `Task.output`, `Task.output.extension`, `Task.output.id`, `Task.output.modifierExtension`, `Task.output.type`, `Task.output.value[x]`, `Task.owner`, `Task.partOf`, `Task.performer`, `Task.performer.actor`, `Task.performer.extension`, `Task.performer.function`, `Task.performer.id`, `Task.performer.modifierExtension`, `Task.priority`, `Task.reason`, `Task.relevantHistory`, `Task.requestedPerformer`, `Task.requestedPeriod`, `Task.requester`, `Task.restriction`, `Task.restriction.extension`, `Task.restriction.id`, `Task.restriction.modifierExtension`, `Task.restriction.period`, `Task.restriction.recipient`, `Task.restriction.repetitions`, `Task.status`, `Task.statusReason`, `Task.text`

