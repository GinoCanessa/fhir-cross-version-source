Comparison of 
Generated at Monday, April 14, 2025 6:17:17 PM

### DeviceUseRequest

|      |     |
| ---: | --- |
| Package | hl7.fhir.r2.core@1.0.2 |
| Stucture Name | DeviceUseRequest |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/DeviceUseRequest` |
| Version | 1.0.2 |
| Description | Base StructureDefinition for DeviceUseRequest Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `67` |
| Database Snapshot Count | `22` |
| Database Differential Count | `14` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `DeviceUseRequest` | `DeviceUseRequest` | `DeviceUseRequest` | DeviceUseRequest | A request for a patient to use or be given a medical device | 0..* | DeviceUseRequest |  |  |
| `DeviceUseRequest.bodySite[x]` | `DeviceUseRequest.bodySite[x]` | `bodySite[x]` |  | Target body site | 0..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/BodySite) |  |  |
| `DeviceUseRequest.contained` | `DeviceUseRequest.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `DeviceUseRequest.device` | `DeviceUseRequest.device` | `device` |  | Device requested | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device) |  |  |
| `DeviceUseRequest.encounter` | `DeviceUseRequest.encounter` | `encounter` |  | Encounter motivating request | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `DeviceUseRequest.extension` | `DeviceUseRequest.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `DeviceUseRequest.id` | `DeviceUseRequest.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `DeviceUseRequest.identifier` | `DeviceUseRequest.identifier` | `identifier` |  | Request identifier | 0..* | Identifier |  |  |
| `DeviceUseRequest.implicitRules` | `DeviceUseRequest.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `DeviceUseRequest.indication` | `DeviceUseRequest.indication` | `indication` |  | Reason for request | 0..* | CodeableConcept |  |  |
| `DeviceUseRequest.language` | `DeviceUseRequest.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://tools.ietf.org/html/bcp47` |
| `DeviceUseRequest.meta` | `DeviceUseRequest.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `DeviceUseRequest.modifierExtension` | `DeviceUseRequest.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DeviceUseRequest.notes` | `DeviceUseRequest.notes` | `notes` |  | Notes or comments | 0..* | string |  |  |
| `DeviceUseRequest.orderedOn` | `DeviceUseRequest.orderedOn` | `orderedOn` |  | When ordered | 0..1 | dateTime |  |  |
| `DeviceUseRequest.priority` | `DeviceUseRequest.priority` | `priority` |  | routine \| urgent \| stat \| asap | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/device-use-request-priority` |
| `DeviceUseRequest.prnReason` | `DeviceUseRequest.prnReason` | `prnReason` |  | PRN | 0..* | CodeableConcept |  |  |
| `DeviceUseRequest.recordedOn` | `DeviceUseRequest.recordedOn` | `recordedOn` |  | When recorded | 0..1 | dateTime |  |  |
| `DeviceUseRequest.status` | `DeviceUseRequest.status` | `status` |  | proposed \| planned \| requested \| received \| accepted \| in-progress \| completed \| suspended \| rejected \| aborted | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/device-use-request-status` |
| `DeviceUseRequest.subject` | `DeviceUseRequest.subject` | `subject` |  | Focus of request | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `DeviceUseRequest.text` | `DeviceUseRequest.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
| `DeviceUseRequest.timing[x]` | `DeviceUseRequest.timing[x]` | `timing[x]` |  | Schedule for use | 0..1 | dateTime, Period, Timing |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DeviceUseRequest](/docs/R2/Resources/DeviceUseRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceUseRequest\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `100`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `267`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [DeviceRequest](/docs/R3/Resources/DeviceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceRequest\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `449`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `644`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [DeviceRequest](/docs/R4/Resources/DeviceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceRequest\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1461`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1462`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [DeviceRequest](/docs/R4B/Resources/DeviceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceRequest\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `965`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1194`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>- Identical: `False`<br/>←←←←←←←| [DeviceRequest](/docs/R5/Resources/DeviceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceRequest\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition DeviceUseRequest from hl7.fhir.r2.core@1.0.2 (R2, key 1).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| R2 DeviceUseRequest| Relationship | [R3 DeviceRequest](/docs/R3/Resources/DeviceRequest.md)| Relationship | [R4 DeviceRequest](/docs/R4/Resources/DeviceRequest.md)| Relationship | [R4B DeviceRequest](/docs/R4B/Resources/DeviceRequest.md)| Relationship | [R5 DeviceRequest](/docs/R5/Resources/DeviceRequest.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| **`DeviceUseRequest`**| | | | | | | | | 
| **`DeviceUseRequest.id`**| | | | | | | | | 
| **`DeviceUseRequest.meta`**| | | | | | | | | 
| **`DeviceUseRequest.implicitRules`**| | | | | | | | | 
| **`DeviceUseRequest.language`**| | | | | | | | | 
| **`DeviceUseRequest.text`**| | | | | | | | | 
| **`DeviceUseRequest.contained`**| | | | | | | | | 
| **`DeviceUseRequest.extension`**| | | | | | | | | 
| **`DeviceUseRequest.modifierExtension`**| | | | | | | | | 
| **`DeviceUseRequest.bodySite[x]`**| | | | | | | | | 
| **`DeviceUseRequest.status`**| | | | | | | | | 
| **`DeviceUseRequest.device`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(181)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(595)| `DeviceRequest.code[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13040)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13041)| `DeviceRequest.code[x]`| _Equivalent_<br/>(25831/25832)| `DeviceRequest.code[x]`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1769)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2012)| `DeviceRequest.code`
| **`DeviceUseRequest.encounter`**| →→→→ _RelatedTo_ →→→→ <br/>(182)<hr/>←←←← _RelatedTo_ ←←←← <br/>(596)| `DeviceRequest.context`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(995)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1482)| `DeviceRequest.encounter`| _Equivalent_<br/>(25847/25848)| `DeviceRequest.encounter`| _Equivalent_<br/>(40731/40732)| `DeviceRequest.encounter`
| **`DeviceUseRequest.identifier`**| | | | | | | | | 
| **`DeviceUseRequest.indication`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(183)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(600)| `DeviceRequest.reasonCode`| _Equivalent_<br/>(13057/13058)| `DeviceRequest.reasonCode`| _Equivalent_<br/>(25859/25860)| `DeviceRequest.reasonCode`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1770)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2013)| `DeviceRequest.reason`
| **`DeviceUseRequest.notes`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(184)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(597)| `DeviceRequest.note`| _Equivalent_<br/>(13063/13064)| `DeviceRequest.note`| _Equivalent_<br/>(25867/25868)| `DeviceRequest.note`| _Equivalent_<br/>(40746/40747)| `DeviceRequest.note`
| **`DeviceUseRequest.prnReason`**| | | | | | | | | 
| **`DeviceUseRequest.orderedOn`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(185)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(598)| `DeviceRequest.occurrence[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13044)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13045)| `DeviceRequest.occurrence[x]`| _Equivalent_<br/>(25849/25850)| `DeviceRequest.occurrence[x]`| _Equivalent_<br/>(40733/40734)| `DeviceRequest.occurrence[x]`
| **`DeviceUseRequest.recordedOn`**| _Equivalent_<br/>(187/594)| `DeviceRequest.authoredOn`| _Equivalent_<br/>(13046/13047)| `DeviceRequest.authoredOn`| _Equivalent_<br/>(25851/25852)| `DeviceRequest.authoredOn`| _Equivalent_<br/>(40735/40736)| `DeviceRequest.authoredOn`
| **`DeviceUseRequest.subject`**| | | | | | | | | 
| **`DeviceUseRequest.timing[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(188)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(599)| `DeviceRequest.occurrence[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13044)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13045)| `DeviceRequest.occurrence[x]`| _Equivalent_<br/>(25849/25850)| `DeviceRequest.occurrence[x]`| _Equivalent_<br/>(40733/40734)| `DeviceRequest.occurrence[x]`
| **`DeviceUseRequest.priority`**| | | | | | | | | 
| *22 of 22 elements used* | | *6 of 35 elements used* <br/>remaining elements:<br/>`DeviceRequest`, `DeviceRequest.basedOn`, `DeviceRequest.contained`, `DeviceRequest.definition`, `DeviceRequest.extension`, `DeviceRequest.groupIdentifier`, `DeviceRequest.id`, `DeviceRequest.identifier`, `DeviceRequest.implicitRules`, `DeviceRequest.intent`, `DeviceRequest.language`, `DeviceRequest.meta`, `DeviceRequest.modifierExtension`, `DeviceRequest.performer`, `DeviceRequest.performerType`, `DeviceRequest.priorRequest`, `DeviceRequest.priority`, `DeviceRequest.reasonReference`, `DeviceRequest.relevantHistory`, `DeviceRequest.requester`, `DeviceRequest.requester.agent`, `DeviceRequest.requester.extension`, `DeviceRequest.requester.id`, `DeviceRequest.requester.modifierExtension`, `DeviceRequest.requester.onBehalfOf`, `DeviceRequest.status`, `DeviceRequest.subject`, `DeviceRequest.supportingInfo`, `DeviceRequest.text`| | *6 of 38 elements used* <br/>remaining elements:<br/>`DeviceRequest`, `DeviceRequest.basedOn`, `DeviceRequest.contained`, `DeviceRequest.extension`, `DeviceRequest.groupIdentifier`, `DeviceRequest.id`, `DeviceRequest.identifier`, `DeviceRequest.implicitRules`, `DeviceRequest.instantiatesCanonical`, `DeviceRequest.instantiatesUri`, `DeviceRequest.insurance`, `DeviceRequest.intent`, `DeviceRequest.language`, `DeviceRequest.meta`, `DeviceRequest.modifierExtension`, `DeviceRequest.parameter`, `DeviceRequest.parameter.code`, `DeviceRequest.parameter.extension`, `DeviceRequest.parameter.id`, `DeviceRequest.parameter.modifierExtension`, `DeviceRequest.parameter.value[x]`, `DeviceRequest.performer`, `DeviceRequest.performerType`, `DeviceRequest.priorRequest`, `DeviceRequest.priority`, `DeviceRequest.reasonReference`, `DeviceRequest.relevantHistory`, `DeviceRequest.requester`, `DeviceRequest.status`, `DeviceRequest.subject`, `DeviceRequest.supportingInfo`, `DeviceRequest.text`| | *6 of 38 elements used* <br/>remaining elements:<br/>`DeviceRequest`, `DeviceRequest.basedOn`, `DeviceRequest.contained`, `DeviceRequest.extension`, `DeviceRequest.groupIdentifier`, `DeviceRequest.id`, `DeviceRequest.identifier`, `DeviceRequest.implicitRules`, `DeviceRequest.instantiatesCanonical`, `DeviceRequest.instantiatesUri`, `DeviceRequest.insurance`, `DeviceRequest.intent`, `DeviceRequest.language`, `DeviceRequest.meta`, `DeviceRequest.modifierExtension`, `DeviceRequest.parameter`, `DeviceRequest.parameter.code`, `DeviceRequest.parameter.extension`, `DeviceRequest.parameter.id`, `DeviceRequest.parameter.modifierExtension`, `DeviceRequest.parameter.value[x]`, `DeviceRequest.performer`, `DeviceRequest.performerType`, `DeviceRequest.priorRequest`, `DeviceRequest.priority`, `DeviceRequest.reasonReference`, `DeviceRequest.relevantHistory`, `DeviceRequest.requester`, `DeviceRequest.status`, `DeviceRequest.subject`, `DeviceRequest.supportingInfo`, `DeviceRequest.text`| | *6 of 40 elements used* <br/>remaining elements:<br/>`DeviceRequest`, `DeviceRequest.asNeeded`, `DeviceRequest.asNeededFor`, `DeviceRequest.basedOn`, `DeviceRequest.contained`, `DeviceRequest.doNotPerform`, `DeviceRequest.extension`, `DeviceRequest.groupIdentifier`, `DeviceRequest.id`, `DeviceRequest.identifier`, `DeviceRequest.implicitRules`, `DeviceRequest.instantiatesCanonical`, `DeviceRequest.instantiatesUri`, `DeviceRequest.insurance`, `DeviceRequest.intent`, `DeviceRequest.language`, `DeviceRequest.meta`, `DeviceRequest.modifierExtension`, `DeviceRequest.parameter`, `DeviceRequest.parameter.code`, `DeviceRequest.parameter.extension`, `DeviceRequest.parameter.id`, `DeviceRequest.parameter.modifierExtension`, `DeviceRequest.parameter.value[x]`, `DeviceRequest.performer`, `DeviceRequest.priority`, `DeviceRequest.quantity`, `DeviceRequest.relevantHistory`, `DeviceRequest.replaces`, `DeviceRequest.requester`, `DeviceRequest.status`, `DeviceRequest.subject`, `DeviceRequest.supportingInfo`, `DeviceRequest.text`

