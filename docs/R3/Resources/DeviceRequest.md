Comparison of 
Generated at Thursday, April 3, 2025 8:18:11 AM

### DeviceRequest

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | DeviceRequest |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/DeviceRequest` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for DeviceRequest Resource |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `508` |
| Database Snapshot Count | `35` |
| Database Differential Count | `24` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `DeviceRequest` | `DeviceRequest` | `DeviceRequest` | DeviceRequest | Medical device request | 0..* | DeviceRequest |  |  |
| `DeviceRequest.authoredOn` | `DeviceRequest.authoredOn` | `authoredOn` |  | When recorded | 0..1 | dateTime |  |  |
| `DeviceRequest.basedOn` | `DeviceRequest.basedOn` | `basedOn` |  | What request fulfills | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `DeviceRequest.code[x]` | `DeviceRequest.code[x]` | `code[x]` |  | Device requested | 1..1 | CodeableConcept, Reference(http://hl7.org/fhir/StructureDefinition/Device) | `Example` | `http://hl7.org/fhir/ValueSet/device-kind` |
| `DeviceRequest.contained` | `DeviceRequest.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `DeviceRequest.context` | `DeviceRequest.context` | `context` |  | Encounter or Episode motivating request | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter), Reference(http://hl7.org/fhir/StructureDefinition/EpisodeOfCare) |  |  |
| `DeviceRequest.definition` | `DeviceRequest.definition` | `definition` |  | Protocol or definition | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/ActivityDefinition), Reference(http://hl7.org/fhir/StructureDefinition/PlanDefinition) |  |  |
| `DeviceRequest.extension` | `DeviceRequest.extension` | `extension` | DomainResource.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `DeviceRequest.groupIdentifier` | `DeviceRequest.groupIdentifier` | `groupIdentifier` |  | Identifier of composite request | 0..1 | Identifier |  |  |
| `DeviceRequest.id` | `DeviceRequest.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `DeviceRequest.identifier` | `DeviceRequest.identifier` | `identifier` |  | External Request identifier | 0..* | Identifier |  |  |
| `DeviceRequest.implicitRules` | `DeviceRequest.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `DeviceRequest.intent` | `DeviceRequest.intent` | `intent` |  | proposal \| plan \| original-order \| encoded \| reflex-order | 1..1 | CodeableConcept | `Required` | `http://hl7.org/fhir/ValueSet/request-intent` |
| `DeviceRequest.language` | `DeviceRequest.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Extensible` | `http://hl7.org/fhir/ValueSet/languages` |
| `DeviceRequest.meta` | `DeviceRequest.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `DeviceRequest.modifierExtension` | `DeviceRequest.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DeviceRequest.note` | `DeviceRequest.note` | `note` |  | Notes or comments | 0..* | Annotation |  |  |
| `DeviceRequest.occurrence[x]` | `DeviceRequest.occurrence[x]` | `occurrence[x]` |  | Desired time or schedule for use | 0..1 | dateTime, Period, Timing |  |  |
| `DeviceRequest.performer` | `DeviceRequest.performer` | `performer` |  | Requested Filler | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/HealthcareService), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Patient), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner), Reference(http://hl7.org/fhir/StructureDefinition/RelatedPerson) |  |  |
| `DeviceRequest.performerType` | `DeviceRequest.performerType` | `performerType` |  | Fille role | 0..1 | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/participant-role` |
| `DeviceRequest.priorRequest` | `DeviceRequest.priorRequest` | `priorRequest` |  | What request replaces | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `DeviceRequest.priority` | `DeviceRequest.priority` | `priority` |  | Indicates how quickly the {{title}} should be addressed with respect to other requests | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/request-priority` |
| `DeviceRequest.reasonCode` | `DeviceRequest.reasonCode` | `reasonCode` |  | Coded Reason for request | 0..* | CodeableConcept | `Example` | `http://hl7.org/fhir/ValueSet/condition-code` |
| `DeviceRequest.reasonReference` | `DeviceRequest.reasonReference` | `reasonReference` |  | Linked Reason for request | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `DeviceRequest.relevantHistory` | `DeviceRequest.relevantHistory` | `relevantHistory` |  | Request provenance | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Provenance) |  |  |
| `DeviceRequest.requester` | `DeviceRequest.requester` | `requester` |  | Who/what is requesting diagnostics | 0..1 | BackboneElement |  |  |
| `DeviceRequest.requester.agent` | `DeviceRequest.requester.agent` | `agent` |  | Individual making the request | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Organization), Reference(http://hl7.org/fhir/StructureDefinition/Practitioner) |  |  |
| `DeviceRequest.requester.extension` | `DeviceRequest.requester.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `DeviceRequest.requester.id` | `DeviceRequest.requester.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `DeviceRequest.requester.modifierExtension` | `DeviceRequest.requester.modifierExtension` | `modifierExtension` | BackboneElement.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `DeviceRequest.requester.onBehalfOf` | `DeviceRequest.requester.onBehalfOf` | `onBehalfOf` |  | Organization agent is acting for | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Organization) |  |  |
| `DeviceRequest.status` | `DeviceRequest.status` | `status` |  | draft \| active \| suspended \| completed \| entered-in-error \| cancelled | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/request-status` |
| `DeviceRequest.subject` | `DeviceRequest.subject` | `subject` |  | Focus of request | 1..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device), Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Location), Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `DeviceRequest.supportingInfo` | `DeviceRequest.supportingInfo` | `supportingInfo` |  | Additional clinical information | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Resource) |  |  |
| `DeviceRequest.text` | `DeviceRequest.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| [DeviceUseRequest](/docs/R2/Resources/DeviceUseRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceUseRequest\|1.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `100`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `267`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceRequest](/docs/R3/Resources/DeviceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceRequest\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `449`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `644`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceRequest](/docs/R4/Resources/DeviceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceRequest\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1461`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1462`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceRequest](/docs/R4B/Resources/DeviceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceRequest\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `965`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1194`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [DeviceRequest](/docs/R5/Resources/DeviceRequest.md)<br/> `http://hl7.org/fhir/StructureDefinition/DeviceRequest\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition DeviceRequest from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| [R2 DeviceUseRequest](/docs/R2/Resources/DeviceUseRequest.md)| Relationship | R3 DeviceRequest| Relationship | [R4 DeviceRequest](/docs/R4/Resources/DeviceRequest.md)| Relationship | [R4B DeviceRequest](/docs/R4B/Resources/DeviceRequest.md)| Relationship | [R5 DeviceRequest](/docs/R5/Resources/DeviceRequest.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | **`DeviceRequest`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13008)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13009)| `DeviceRequest`| _Equivalent_<br/>(25795/25796)| `DeviceRequest`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(40683)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40684)| `DeviceRequest`
| | | **`DeviceRequest.id`**| _Equivalent_<br/>(13010/13011)| `DeviceRequest.id`| _Equivalent_<br/>(25797/25798)| `DeviceRequest.id`| _Equivalent_<br/>(40685/40686)| `DeviceRequest.id`
| | | **`DeviceRequest.meta`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13012)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13013)| `DeviceRequest.meta`| _Equivalent_<br/>(25799/25800)| `DeviceRequest.meta`| _Equivalent_<br/>(40687/40688)| `DeviceRequest.meta`
| | | **`DeviceRequest.implicitRules`**| _Equivalent_<br/>(13014/13015)| `DeviceRequest.implicitRules`| _Equivalent_<br/>(25801/25802)| `DeviceRequest.implicitRules`| _Equivalent_<br/>(40689/40690)| `DeviceRequest.implicitRules`
| | | **`DeviceRequest.language`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13016)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(13017)| `DeviceRequest.language`| _Equivalent_<br/>(25803/25804)| `DeviceRequest.language`| _Equivalent_<br/>(40691/40692)| `DeviceRequest.language`
| | | **`DeviceRequest.text`**| _Equivalent_<br/>(13018/13019)| `DeviceRequest.text`| _Equivalent_<br/>(25805/25806)| `DeviceRequest.text`| _Equivalent_<br/>(40693/40694)| `DeviceRequest.text`
| | | **`DeviceRequest.contained`**| _Equivalent_<br/>(13020/13021)| `DeviceRequest.contained`| _Equivalent_<br/>(25807/25808)| `DeviceRequest.contained`| _Equivalent_<br/>(40695/40696)| `DeviceRequest.contained`
| | | **`DeviceRequest.extension`**| _Equivalent_<br/>(13022/13023)| `DeviceRequest.extension`| _Equivalent_<br/>(25809/25810)| `DeviceRequest.extension`| _Equivalent_<br/>(40697/40698)| `DeviceRequest.extension`
| | | **`DeviceRequest.modifierExtension`**| _Equivalent_<br/>(13024/13025)| `DeviceRequest.modifierExtension`| _Equivalent_<br/>(25811/25812)| `DeviceRequest.modifierExtension`| _Equivalent_<br/>(40699/40700)| `DeviceRequest.modifierExtension`
| | | **`DeviceRequest.identifier`**| _Equivalent_<br/>(13026/13027)| `DeviceRequest.identifier`| _Equivalent_<br/>(25813/25814)| `DeviceRequest.identifier`| _Equivalent_<br/>(40701/40702)| `DeviceRequest.identifier`
| | | **`DeviceRequest.definition`**| | | | | | | 
| | | **`DeviceRequest.basedOn`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13028)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13029)| `DeviceRequest.basedOn`| _Equivalent_<br/>(25819/25820)| `DeviceRequest.basedOn`| _Equivalent_<br/>(40707/40708)| `DeviceRequest.basedOn`
| | | **`DeviceRequest.priorRequest`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13030)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13031)| `DeviceRequest.priorRequest`| _Equivalent_<br/>(25821/25822)| `DeviceRequest.priorRequest`| →→→→ _RelatedTo_ →→→→ <br/>(1768)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2011)| `DeviceRequest.replaces`
| | | **`DeviceRequest.groupIdentifier`**| _Equivalent_<br/>(13032/13033)| `DeviceRequest.groupIdentifier`| _Equivalent_<br/>(25823/25824)| `DeviceRequest.groupIdentifier`| _Equivalent_<br/>(40709/40710)| `DeviceRequest.groupIdentifier`
| | | **`DeviceRequest.status`**| _Equivalent_<br/>(13034/13035)| `DeviceRequest.status`| _Equivalent_<br/>(25825/25826)| `DeviceRequest.status`| _Equivalent_<br/>(40711/40712)| `DeviceRequest.status`
| | | **`DeviceRequest.intent`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13036)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13037)| `DeviceRequest.intent`| _Equivalent_<br/>(25827/25828)| `DeviceRequest.intent`| _Equivalent_<br/>(40713/40714)| `DeviceRequest.intent`
| | | **`DeviceRequest.priority`**| _Equivalent_<br/>(13038/13039)| `DeviceRequest.priority`| _Equivalent_<br/>(25829/25830)| `DeviceRequest.priority`| _Equivalent_<br/>(40715/40716)| `DeviceRequest.priority`
| `DeviceUseRequest.device`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(181)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(595)| **`DeviceRequest.code[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13040)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13041)| `DeviceRequest.code[x]`| _Equivalent_<br/>(25831/25832)| `DeviceRequest.code[x]`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1769)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2012)| `DeviceRequest.code`
| | | **`DeviceRequest.subject`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13042)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13043)| `DeviceRequest.subject`| _Equivalent_<br/>(25845/25846)| `DeviceRequest.subject`| _Equivalent_<br/>(40729/40730)| `DeviceRequest.subject`
| `DeviceUseRequest.encounter`| →→→→ _RelatedTo_ →→→→ <br/>(182)<hr/>←←←← _RelatedTo_ ←←←← <br/>(596)| **`DeviceRequest.context`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(995)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1482)| `DeviceRequest.encounter`| _Equivalent_<br/>(25847/25848)| `DeviceRequest.encounter`| _Equivalent_<br/>(40731/40732)| `DeviceRequest.encounter`
| `DeviceUseRequest.orderedOn`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(185)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(599)| **`DeviceRequest.occurrence[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13044)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13045)| `DeviceRequest.occurrence[x]`| _Equivalent_<br/>(25849/25850)| `DeviceRequest.occurrence[x]`| _Equivalent_<br/>(40733/40734)| `DeviceRequest.occurrence[x]`
| `DeviceUseRequest.timing[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(188)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(599)| **`DeviceRequest.occurrence[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13044)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13045)| `DeviceRequest.occurrence[x]`| _Equivalent_<br/>(25849/25850)| `DeviceRequest.occurrence[x]`| _Equivalent_<br/>(40733/40734)| `DeviceRequest.occurrence[x]`
| `DeviceUseRequest.recordedOn`| _Equivalent_<br/>(187/594)| **`DeviceRequest.authoredOn`**| _Equivalent_<br/>(13046/13047)| `DeviceRequest.authoredOn`| _Equivalent_<br/>(25851/25852)| `DeviceRequest.authoredOn`| _Equivalent_<br/>(40735/40736)| `DeviceRequest.authoredOn`
| | | **`DeviceRequest.requester`**| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(13048)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13049)| `DeviceRequest.requester`| _Equivalent_<br/>(25853/25854)| `DeviceRequest.requester`| _Equivalent_<br/>(40737/40738)| `DeviceRequest.requester`
| | | **`DeviceRequest.requester.id`**| | | | | | | 
| | | **`DeviceRequest.requester.extension`**| | | | | | | 
| | | **`DeviceRequest.requester.modifierExtension`**| | | | | | | 
| | | **`DeviceRequest.requester.agent`**| →→→→ _RelatedTo_ →→→→ <br/>(997)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1483)| `DeviceRequest.requester`| _Equivalent_<br/>(25853/25854)| `DeviceRequest.requester`| _Equivalent_<br/>(40737/40738)| `DeviceRequest.requester`
| | | **`DeviceRequest.requester.onBehalfOf`**| | | | | | | 
| | | **`DeviceRequest.performerType`**| _Equivalent_<br/>(13053/13054)| `DeviceRequest.performerType`| _Equivalent_<br/>(25855/25856)| `DeviceRequest.performerType`| | | 
| | | **`DeviceRequest.performer`**| →→→→ _RelatedTo_ →→→→ <br/>(13055)<hr/>←←←← _RelatedTo_ ←←←← <br/>(13056)| `DeviceRequest.performer`| _Equivalent_<br/>(25857/25858)| `DeviceRequest.performer`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(40740)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(40741)| `DeviceRequest.performer`
| `DeviceUseRequest.indication`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(183)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(600)| **`DeviceRequest.reasonCode`**| _Equivalent_<br/>(13057/13058)| `DeviceRequest.reasonCode`| _Equivalent_<br/>(25859/25860)| `DeviceRequest.reasonCode`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1770)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2013)| `DeviceRequest.reason`
| | | **`DeviceRequest.reasonReference`**| →→→→ _RelatedTo_ →→→→ <br/>(13059)<hr/>←←←← _RelatedTo_ ←←←← <br/>(13060)| `DeviceRequest.reasonReference`| _Equivalent_<br/>(25861/25862)| `DeviceRequest.reasonReference`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1771)<hr/>←←←← _RelatedTo_ ←←←← <br/>(2014)| `DeviceRequest.reason`
| | | **`DeviceRequest.supportingInfo`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13061)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13062)| `DeviceRequest.supportingInfo`| _Equivalent_<br/>(25865/25866)| `DeviceRequest.supportingInfo`| _Equivalent_<br/>(40744/40745)| `DeviceRequest.supportingInfo`
| `DeviceUseRequest.notes`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(184)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(597)| **`DeviceRequest.note`**| _Equivalent_<br/>(13063/13064)| `DeviceRequest.note`| _Equivalent_<br/>(25867/25868)| `DeviceRequest.note`| _Equivalent_<br/>(40746/40747)| `DeviceRequest.note`
| | | **`DeviceRequest.relevantHistory`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(13065)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(13066)| `DeviceRequest.relevantHistory`| _Equivalent_<br/>(25869/25870)| `DeviceRequest.relevantHistory`| _Equivalent_<br/>(40748/40749)| `DeviceRequest.relevantHistory`
| *7 of 22 elements used* <br/>remaining elements:<br/>`DeviceUseRequest`, `DeviceUseRequest.bodySite[x]`, `DeviceUseRequest.contained`, `DeviceUseRequest.extension`, `DeviceUseRequest.id`, `DeviceUseRequest.identifier`, `DeviceUseRequest.implicitRules`, `DeviceUseRequest.language`, `DeviceUseRequest.meta`, `DeviceUseRequest.modifierExtension`, `DeviceUseRequest.priority`, `DeviceUseRequest.prnReason`, `DeviceUseRequest.status`, `DeviceUseRequest.subject`, `DeviceUseRequest.text`| | *35 of 35 elements used* | | *29 of 38 elements used* <br/>remaining elements:<br/>`DeviceRequest.instantiatesCanonical`, `DeviceRequest.instantiatesUri`, `DeviceRequest.insurance`, `DeviceRequest.parameter`, `DeviceRequest.parameter.code`, `DeviceRequest.parameter.extension`, `DeviceRequest.parameter.id`, `DeviceRequest.parameter.modifierExtension`, `DeviceRequest.parameter.value[x]`| | *29 of 38 elements used* <br/>remaining elements:<br/>`DeviceRequest.instantiatesCanonical`, `DeviceRequest.instantiatesUri`, `DeviceRequest.insurance`, `DeviceRequest.parameter`, `DeviceRequest.parameter.code`, `DeviceRequest.parameter.extension`, `DeviceRequest.parameter.id`, `DeviceRequest.parameter.modifierExtension`, `DeviceRequest.parameter.value[x]`| | *27 of 40 elements used* <br/>remaining elements:<br/>`DeviceRequest.asNeeded`, `DeviceRequest.asNeededFor`, `DeviceRequest.doNotPerform`, `DeviceRequest.instantiatesCanonical`, `DeviceRequest.instantiatesUri`, `DeviceRequest.insurance`, `DeviceRequest.parameter`, `DeviceRequest.parameter.code`, `DeviceRequest.parameter.extension`, `DeviceRequest.parameter.id`, `DeviceRequest.parameter.modifierExtension`, `DeviceRequest.parameter.value[x]`, `DeviceRequest.quantity`

