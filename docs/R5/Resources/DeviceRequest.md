Comparison of 
Generated at Tuesday, April 1, 2025 1:39:36 PM

### DeviceRequest

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | DeviceRequest |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/DeviceRequest` |
| Version | 5.0.0 |
| Description | Represents a request a device to be provided to a specific patient. The device may be an implantable device to be subsequently implanted, or an external assistive device, such as a walker, to be delivered and subsequently be used. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `2293` |
| Database Snapshot Count | `40` |
| Database Differential Count | `29` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `DeviceRequest` | `DeviceRequest` | `DeviceRequest` | DeviceRequest | Medical device request | 0..* | DeviceRequest |  |  |
| `DeviceRequest.asNeeded` | `DeviceRequest.asNeeded` | `asNeeded` | DeviceRequest.asNeeded | PRN status of request | 0..1 | boolean |  |  |
| `DeviceRequest.asNeededFor` | `DeviceRequest.asNeededFor` | `asNeededFor` | DeviceRequest.asNeededFor | Device usage reason | 0..1 | CodeableConcept |  |  |
| `DeviceRequest.authoredOn` | `DeviceRequest.authoredOn` | `authoredOn` | DeviceRequest.authoredOn | When recorded | 0..1 | dateTime |  |  |
| `DeviceRequest.basedOn` | `DeviceRequest.basedOn` | `basedOn` | DeviceRequest.basedOn | What request fulfills | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `DeviceRequest.code` | `DeviceRequest.code` | `code` | DeviceRequest.code | Device requested | 1..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/Device), CodeableReference(http://hl7.org/fhir/StructureDefinition/DeviceDefinition) | `Example` | `http://hl7.org/fhir/ValueSet/device-type` |
| `DeviceRequest.contained` | `DeviceRequest.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `DeviceRequest.doNotPerform` | `DeviceRequest.doNotPerform` | `doNotPerform` | DeviceRequest.doNotPerform | True if the request is to stop or not to start using the device | 0..1 | boolean |  |  |
| `DeviceRequest.encounter` | `DeviceRequest.encounter` | `encounter` | DeviceRequest.encounter | Encounter motivating request | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `DeviceRequest.extension` | `DeviceRequest.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceRequest.groupIdentifier` | `DeviceRequest.groupIdentifier` | `groupIdentifier` | DeviceRequest.groupIdentifier | Identifier of composite request | 0..1 | Identifier |  |  |
| `DeviceRequest.id` | `DeviceRequest.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `DeviceRequest.identifier` | `DeviceRequest.identifier` | `identifier` | DeviceRequest.identifier | External Request identifier | 0..* | Identifier |  |  |
| `DeviceRequest.implicitRules` | `DeviceRequest.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `DeviceRequest.instantiatesCanonical` | `DeviceRequest.instantiatesCanonical` | `instantiatesCanonical` | DeviceRequest.instantiatesCanonical | Instantiates FHIR protocol or definition | 0..* | canonical(http://hl7.org/fhir/StructureDefinition/ActivityDefinition), canonical(http://hl7.org/fhir/StructureDefinition/PlanDefinition) |  |  |
| `DeviceRequest.instantiatesUri` | `DeviceRequest.instantiatesUri` | `instantiatesUri` | DeviceRequest.instantiatesUri | Instantiates external protocol or definition | 0..* | uri |  |  |
| `DeviceRequest.insurance` | `DeviceRequest.insurance` | `insurance` | DeviceRequest.insurance | Associated insurance coverage | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ClaimResponse), Reference(http://hl7.org/fhir/StructureDefinition/Coverage) |  |  |
| `DeviceRequest.intent` | `DeviceRequest.intent` | `intent` | DeviceRequest.intent | proposal \| plan \| directive \| order \| original-order \| reflex-order \| filler-order \| instance-order \| option | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/request-intent|5.0.0` |
| `DeviceRequest.language` | `DeviceRequest.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages|5.0.0` |
| `DeviceRequest.meta` | `DeviceRequest.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `DeviceRequest.modifierExtension` | `DeviceRequest.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DeviceRequest.note` | `DeviceRequest.note` | `note` | DeviceRequest.note | Notes or comments | 0..* | Annotation |  |  |
| `DeviceRequest.occurrence[x]` | `DeviceRequest.occurrence[x]` | `occurrence[x]` | DeviceRequest.occurrence[x] | Desired time or schedule for use | 0..1 | dateTime, Period, Timing |  |  |
| `DeviceRequest.parameter` | `DeviceRequest.parameter` | `parameter` | DeviceRequest.parameter | Device details | 0..* | BackboneElement |  |  |
| `DeviceRequest.parameter.code` | `DeviceRequest.parameter.code` | `code` | DeviceRequest.parameter.code | Device detail | 0..1 | CodeableConcept | `Example` |  |
| `DeviceRequest.parameter.extension` | `DeviceRequest.parameter.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `DeviceRequest.parameter.id` | `DeviceRequest.parameter.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `DeviceRequest.parameter.modifierExtension` | `DeviceRequest.parameter.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored even if unrecognized | 0..* | Extension |  |  |
| `DeviceRequest.parameter.value[x]` | `DeviceRequest.parameter.value[x]` | `value[x]` | DeviceRequest.parameter.value[x] | Value of detail | 0..1 | boolean, CodeableConcept, Quantity, Range |  |  |
| `DeviceRequest.performer` | `DeviceRequest.performer` | `performer` | DeviceRequest.performer | Requested Filler | 0..1 | CodeableReference(http://hl7.org/fhir/StructureDefinition/CareTeam), CodeableReference(http://hl7.org/fhir/StructureDefinition/Device), CodeableReference(http://hl7.org/fhir/StructureDefinition/HealthcareService), CodeableReference(http://hl7.org/fhir/StructureDefinition/Organization), CodeableReference(http://hl7.org/fhir/StructureDefinition/Patient), CodeableReference(http://hl7.org/fhir/StructureDefinition/Practitioner), CodeableReference(http://hl7.org/fhir/StructureDefinition/PractitionerRole), CodeableReference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `DeviceRequest.priority` | `DeviceRequest.priority` | `priority` | DeviceRequest.priority | routine \| urgent \| asap \| stat | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/request-priority|5.0.0` |
| `DeviceRequest.quantity` | `DeviceRequest.quantity` | `quantity` | DeviceRequest.quantity | Quantity of devices to supply | 0..1 | integer |  |  |
| `DeviceRequest.reason` | `DeviceRequest.reason` | `reason` | DeviceRequest.reason | Coded/Linked Reason for request | 0..* | CodeableReference(http://hl7.org/fhir/StructureDefinition/Condition), CodeableReference(http://hl7.org/fhir/StructureDefinition/DiagnosticReport), CodeableReference(http://hl7.org/fhir/StructureDefinition/DocumentReference), CodeableReference(http://hl7.org/fhir/StructureDefinition/Observation) | `Example` | `http://hl7.org/fhir/ValueSet/condition-code` |
| `DeviceRequest.relevantHistory` | `DeviceRequest.relevantHistory` | `relevantHistory` | DeviceRequest.relevantHistory | Request provenance | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Provenance) |  |  |
| `DeviceRequest.replaces` | `DeviceRequest.replaces` | `replaces` | DeviceRequest.replaces | What request replaces | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/DeviceRequest) |  |  |
| `DeviceRequest.requester` | `DeviceRequest.requester` | `requester` | DeviceRequest.requester | Who/what submitted the device request | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/PractitionerRole) |  |  |
| `DeviceRequest.status` | `DeviceRequest.status` | `status` | DeviceRequest.status | draft \| active \| on-hold \| revoked \| completed \| entered-in-error \| unknown | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/request-status|5.0.0` |
| `DeviceRequest.subject` | `DeviceRequest.subject` | `subject` | DeviceRequest.subject | Focus of request | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `DeviceRequest.supportingInfo` | `DeviceRequest.supportingInfo` | `supportingInfo` | DeviceRequest.supportingInfo | Additional clinical information | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `DeviceRequest.text` | `DeviceRequest.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DeviceUseRequest](/docs/R2/Resources/DeviceUseRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceUseRequest\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `100`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `267`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceRequest](/docs/R3/Resources/DeviceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceRequest\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `449`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `644`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceRequest](/docs/R4/Resources/DeviceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceRequest\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1461`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1462`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceRequest](/docs/R4B/Resources/DeviceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceRequest\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `965`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1194`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceRequest](/docs/R5/Resources/DeviceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceRequest\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition DeviceRequest from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 DeviceUseRequest](/docs/R2/Resources/DeviceUseRequest.md)| Relationship | [R3 DeviceRequest](/docs/R3/Resources/DeviceRequest.md)| Relationship | [R4 DeviceRequest](/docs/R4/Resources/DeviceRequest.md)| Relationship | [R4B DeviceRequest](/docs/R4B/Resources/DeviceRequest.md)| Relationship | R5 DeviceRequest
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `DeviceRequest`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13008)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13009)| `DeviceRequest`| _Equivalent_<br/>(25795/25796)| `DeviceRequest`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(40683)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40684)| **`DeviceRequest`**
| | | `DeviceRequest.id`| _Equivalent_<br/>(13010/13011)| `DeviceRequest.id`| _Equivalent_<br/>(25797/25798)| `DeviceRequest.id`| _Equivalent_<br/>(40685/40686)| **`DeviceRequest.id`**
| | | `DeviceRequest.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13012)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13013)| `DeviceRequest.meta`| _Equivalent_<br/>(25799/25800)| `DeviceRequest.meta`| _Equivalent_<br/>(40687/40688)| **`DeviceRequest.meta`**
| | | `DeviceRequest.implicitRules`| _Equivalent_<br/>(13014/13015)| `DeviceRequest.implicitRules`| _Equivalent_<br/>(25801/25802)| `DeviceRequest.implicitRules`| _Equivalent_<br/>(40689/40690)| **`DeviceRequest.implicitRules`**
| | | `DeviceRequest.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13016)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(13017)| `DeviceRequest.language`| _Equivalent_<br/>(25803/25804)| `DeviceRequest.language`| _Equivalent_<br/>(40691/40692)| **`DeviceRequest.language`**
| | | `DeviceRequest.text`| _Equivalent_<br/>(13018/13019)| `DeviceRequest.text`| _Equivalent_<br/>(25805/25806)| `DeviceRequest.text`| _Equivalent_<br/>(40693/40694)| **`DeviceRequest.text`**
| | | `DeviceRequest.contained`| _Equivalent_<br/>(13020/13021)| `DeviceRequest.contained`| _Equivalent_<br/>(25807/25808)| `DeviceRequest.contained`| _Equivalent_<br/>(40695/40696)| **`DeviceRequest.contained`**
| | | `DeviceRequest.extension`| _Equivalent_<br/>(13022/13023)| `DeviceRequest.extension`| _Equivalent_<br/>(25809/25810)| `DeviceRequest.extension`| _Equivalent_<br/>(40697/40698)| **`DeviceRequest.extension`**
| | | `DeviceRequest.modifierExtension`| _Equivalent_<br/>(13024/13025)| `DeviceRequest.modifierExtension`| _Equivalent_<br/>(25811/25812)| `DeviceRequest.modifierExtension`| _Equivalent_<br/>(40699/40700)| **`DeviceRequest.modifierExtension`**
| | | `DeviceRequest.identifier`| _Equivalent_<br/>(13026/13027)| `DeviceRequest.identifier`| _Equivalent_<br/>(25813/25814)| `DeviceRequest.identifier`| _Equivalent_<br/>(40701/40702)| **`DeviceRequest.identifier`**
| | | | | `DeviceRequest.instantiatesCanonical`| _Equivalent_<br/>(25815/25816)| `DeviceRequest.instantiatesCanonical`| _Equivalent_<br/>(40703/40704)| **`DeviceRequest.instantiatesCanonical`**
| | | | | `DeviceRequest.instantiatesUri`| _Equivalent_<br/>(25817/25818)| `DeviceRequest.instantiatesUri`| _Equivalent_<br/>(40705/40706)| **`DeviceRequest.instantiatesUri`**
| | | `DeviceRequest.basedOn`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13028)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13029)| `DeviceRequest.basedOn`| _Equivalent_<br/>(25819/25820)| `DeviceRequest.basedOn`| _Equivalent_<br/>(40707/40708)| **`DeviceRequest.basedOn`**
| | | `DeviceRequest.priorRequest`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13030)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13031)| `DeviceRequest.priorRequest`| _Equivalent_<br/>(25821/25822)| `DeviceRequest.priorRequest`| →→→→ _RelatedTo_ →→→→ <br/>(1768)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2011)| **`DeviceRequest.replaces`**
| | | `DeviceRequest.groupIdentifier`| _Equivalent_<br/>(13032/13033)| `DeviceRequest.groupIdentifier`| _Equivalent_<br/>(25823/25824)| `DeviceRequest.groupIdentifier`| _Equivalent_<br/>(40709/40710)| **`DeviceRequest.groupIdentifier`**
| | | `DeviceRequest.status`| _Equivalent_<br/>(13034/13035)| `DeviceRequest.status`| _Equivalent_<br/>(25825/25826)| `DeviceRequest.status`| _Equivalent_<br/>(40711/40712)| **`DeviceRequest.status`**
| | | `DeviceRequest.intent`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13036)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13037)| `DeviceRequest.intent`| _Equivalent_<br/>(25827/25828)| `DeviceRequest.intent`| _Equivalent_<br/>(40713/40714)| **`DeviceRequest.intent`**
| | | `DeviceRequest.priority`| _Equivalent_<br/>(13038/13039)| `DeviceRequest.priority`| _Equivalent_<br/>(25829/25830)| `DeviceRequest.priority`| _Equivalent_<br/>(40715/40716)| **`DeviceRequest.priority`**
| | | | | | | | | **`DeviceRequest.doNotPerform`**
| `DeviceUseRequest.device`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(181)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(595)| `DeviceRequest.code[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13040)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13041)| `DeviceRequest.code[x]`| _Equivalent_<br/>(25831/25832)| `DeviceRequest.code[x]`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1769)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2012)| **`DeviceRequest.code`**
| | | | | | | | | **`DeviceRequest.quantity`**
| | | | | `DeviceRequest.parameter`| _Equivalent_<br/>(25833/25834)| `DeviceRequest.parameter`| _Equivalent_<br/>(40717/40718)| **`DeviceRequest.parameter`**
| | | | | `DeviceRequest.parameter.id`| _Equivalent_<br/>(25835/25836)| `DeviceRequest.parameter.id`| _Equivalent_<br/>(40719/40720)| **`DeviceRequest.parameter.id`**
| | | | | `DeviceRequest.parameter.extension`| _Equivalent_<br/>(25837/25838)| `DeviceRequest.parameter.extension`| _Equivalent_<br/>(40721/40722)| **`DeviceRequest.parameter.extension`**
| | | | | `DeviceRequest.parameter.modifierExtension`| _Equivalent_<br/>(25839/25840)| `DeviceRequest.parameter.modifierExtension`| _Equivalent_<br/>(40723/40724)| **`DeviceRequest.parameter.modifierExtension`**
| | | | | `DeviceRequest.parameter.code`| _Equivalent_<br/>(25841/25842)| `DeviceRequest.parameter.code`| _Equivalent_<br/>(40725/40726)| **`DeviceRequest.parameter.code`**
| | | | | `DeviceRequest.parameter.value[x]`| _Equivalent_<br/>(25843/25844)| `DeviceRequest.parameter.value[x]`| _Equivalent_<br/>(40727/40728)| **`DeviceRequest.parameter.value[x]`**
| | | `DeviceRequest.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13042)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13043)| `DeviceRequest.subject`| _Equivalent_<br/>(25845/25846)| `DeviceRequest.subject`| _Equivalent_<br/>(40729/40730)| **`DeviceRequest.subject`**
| `DeviceUseRequest.encounter`| →→→→ _RelatedTo_ →→→→ <br/>(182)<hr/>←←←← _RelatedTo_ ←←←← <br/>(596)| `DeviceRequest.context`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(995)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1482)| `DeviceRequest.encounter`| _Equivalent_<br/>(25847/25848)| `DeviceRequest.encounter`| _Equivalent_<br/>(40731/40732)| **`DeviceRequest.encounter`**
| `DeviceUseRequest.orderedOn`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(185)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(599)| `DeviceRequest.occurrence[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13044)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13045)| `DeviceRequest.occurrence[x]`| _Equivalent_<br/>(25849/25850)| `DeviceRequest.occurrence[x]`| _Equivalent_<br/>(40733/40734)| **`DeviceRequest.occurrence[x]`**
| `DeviceUseRequest.timing[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(188)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(599)| `DeviceRequest.occurrence[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13044)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13045)| `DeviceRequest.occurrence[x]`| _Equivalent_<br/>(25849/25850)| `DeviceRequest.occurrence[x]`| _Equivalent_<br/>(40733/40734)| **`DeviceRequest.occurrence[x]`**
| `DeviceUseRequest.recordedOn`| _Equivalent_<br/>(187/594)| `DeviceRequest.authoredOn`| _Equivalent_<br/>(13046/13047)| `DeviceRequest.authoredOn`| _Equivalent_<br/>(25851/25852)| `DeviceRequest.authoredOn`| _Equivalent_<br/>(40735/40736)| **`DeviceRequest.authoredOn`**
| | | `DeviceRequest.requester`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(13048)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1483)| `DeviceRequest.requester`| _Equivalent_<br/>(25853/25854)| `DeviceRequest.requester`| _Equivalent_<br/>(40737/40738)| **`DeviceRequest.requester`**
| | | `DeviceRequest.requester.agent`| →→→→ _RelatedTo_ →→→→ <br/>(997)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1483)| `DeviceRequest.requester`| _Equivalent_<br/>(25853/25854)| `DeviceRequest.requester`| _Equivalent_<br/>(40737/40738)| **`DeviceRequest.requester`**
| | | `DeviceRequest.performer`| →→→→ _RelatedTo_ →→→→ <br/>(13055)<hr/>←←←← _RelatedTo_ ←←←← <br/>(13056)| `DeviceRequest.performer`| _Equivalent_<br/>(25857/25858)| `DeviceRequest.performer`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(40740)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40741)| **`DeviceRequest.performer`**
| `DeviceUseRequest.indication`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(183)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(600)| `DeviceRequest.reasonCode`| _Equivalent_<br/>(13057/13058)| `DeviceRequest.reasonCode`| _Equivalent_<br/>(25859/25860)| `DeviceRequest.reasonCode`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1770)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2014)| **`DeviceRequest.reason`**
| | | `DeviceRequest.reasonReference`| →→→→ _RelatedTo_ →→→→ <br/>(13059)<hr/>←←←← _RelatedTo_ ←←←← <br/>(13060)| `DeviceRequest.reasonReference`| _Equivalent_<br/>(25861/25862)| `DeviceRequest.reasonReference`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1771)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2014)| **`DeviceRequest.reason`**
| | | | | | | | | **`DeviceRequest.asNeeded`**
| | | | | | | | | **`DeviceRequest.asNeededFor`**
| | | | | `DeviceRequest.insurance`| _Equivalent_<br/>(25863/25864)| `DeviceRequest.insurance`| _Equivalent_<br/>(40742/40743)| **`DeviceRequest.insurance`**
| | | `DeviceRequest.supportingInfo`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13061)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13062)| `DeviceRequest.supportingInfo`| _Equivalent_<br/>(25865/25866)| `DeviceRequest.supportingInfo`| _Equivalent_<br/>(40744/40745)| **`DeviceRequest.supportingInfo`**
| `DeviceUseRequest.notes`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(184)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(597)| `DeviceRequest.note`| _Equivalent_<br/>(13063/13064)| `DeviceRequest.note`| _Equivalent_<br/>(25867/25868)| `DeviceRequest.note`| _Equivalent_<br/>(40746/40747)| **`DeviceRequest.note`**
| | | `DeviceRequest.relevantHistory`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13065)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13066)| `DeviceRequest.relevantHistory`| _Equivalent_<br/>(25869/25870)| `DeviceRequest.relevantHistory`| _Equivalent_<br/>(40748/40749)| **`DeviceRequest.relevantHistory`**
| *7 of 22 elements used* | | *29 of 35 elements used* | | *37 of 38 elements used* | | *37 of 38 elements used* | | *40 of 40 elements used* 

