Comparison of 
Generated at Friday, April 4, 2025 2:58:49 PM

### GuidanceResponse

|      |     |
| ---: | --- |
| Package | hl7.fhir.r4.core@4.0.1 |
| Stucture Name | GuidanceResponse |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/GuidanceResponse` |
| Version | 4.0.1 |
| Description | A guidance response is the formal response to a guidance request, including any output parameters returned by the evaluation, as well as the description of any proposed actions to be taken. |
| Status | `Draft` |
| Artifact Class | `Resource` |
| Database Key | `1090` |
| Database Snapshot Count | `24` |
| Database Differential Count | `16` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `GuidanceResponse` | `GuidanceResponse` | `GuidanceResponse` | GuidanceResponse | The formal response to a guidance request | 0..* | GuidanceResponse |  |  |
| `GuidanceResponse.contained` | `GuidanceResponse.contained` | `contained` | DomainResource.contained | Contained, inline Resources | 0..* | Resource |  |  |
| `GuidanceResponse.dataRequirement` | `GuidanceResponse.dataRequirement` | `dataRequirement` | GuidanceResponse.dataRequirement | Additional required data | 0..* | DataRequirement |  |  |
| `GuidanceResponse.encounter` | `GuidanceResponse.encounter` | `encounter` | GuidanceResponse.encounter | Encounter during which the response was returned | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Encounter) |  |  |
| `GuidanceResponse.evaluationMessage` | `GuidanceResponse.evaluationMessage` | `evaluationMessage` | GuidanceResponse.evaluationMessage | Messages resulting from the evaluation of the artifact or artifacts | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/OperationOutcome) |  |  |
| `GuidanceResponse.extension` | `GuidanceResponse.extension` | `extension` | DomainResource.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `GuidanceResponse.id` | `GuidanceResponse.id` | `id` | Resource.id | Logical id of this artifact | 0..1 | id |  |  |
| `GuidanceResponse.identifier` | `GuidanceResponse.identifier` | `identifier` | GuidanceResponse.identifier | Business identifier | 0..* | Identifier |  |  |
| `GuidanceResponse.implicitRules` | `GuidanceResponse.implicitRules` | `implicitRules` | Resource.implicitRules | A set of rules under which this content was created | 0..1 | uri |  |  |
| `GuidanceResponse.language` | `GuidanceResponse.language` | `language` | Resource.language | Language of the resource content | 0..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/all-languages` |
| `GuidanceResponse.meta` | `GuidanceResponse.meta` | `meta` | Resource.meta | Metadata about the resource | 0..1 | Meta |  |  |
| `GuidanceResponse.modifierExtension` | `GuidanceResponse.modifierExtension` | `modifierExtension` | DomainResource.modifierExtension | Extensions that cannot be ignored | 0..* | Extension |  |  |
| `GuidanceResponse.module[x]` | `GuidanceResponse.module[x]` | `module[x]` | GuidanceResponse.module[x] | What guidance was requested | 1..1 | canonical, CodeableConcept, uri |  |  |
| `GuidanceResponse.note` | `GuidanceResponse.note` | `note` | GuidanceResponse.note | Additional notes about the response | 0..* | Annotation |  |  |
| `GuidanceResponse.occurrenceDateTime` | `GuidanceResponse.occurrenceDateTime` | `occurrenceDateTime` | GuidanceResponse.occurrenceDateTime | When the guidance response was processed | 0..1 | dateTime |  |  |
| `GuidanceResponse.outputParameters` | `GuidanceResponse.outputParameters` | `outputParameters` | GuidanceResponse.outputParameters | The output parameters of the evaluation, if any | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Parameters) |  |  |
| `GuidanceResponse.performer` | `GuidanceResponse.performer` | `performer` | GuidanceResponse.performer | Device returning the guidance | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Device) |  |  |
| `GuidanceResponse.reasonCode` | `GuidanceResponse.reasonCode` | `reasonCode` | GuidanceResponse.reasonCode | Why guidance is needed | 0..* | CodeableConcept |  |  |
| `GuidanceResponse.reasonReference` | `GuidanceResponse.reasonReference` | `reasonReference` | GuidanceResponse.reasonReference | Why guidance is needed | 0..* | Reference(http://hl7.org/fhir/StructureDefinition/Condition), Reference(http://hl7.org/fhir/StructureDefinition/DiagnosticReport), Reference(http://hl7.org/fhir/StructureDefinition/DocumentReference), Reference(http://hl7.org/fhir/StructureDefinition/Observation) |  |  |
| `GuidanceResponse.requestIdentifier` | `GuidanceResponse.requestIdentifier` | `requestIdentifier` | GuidanceResponse.requestIdentifier | The identifier of the request associated with this response, if any | 0..1 | Identifier |  |  |
| `GuidanceResponse.result` | `GuidanceResponse.result` | `result` | GuidanceResponse.result | Proposed actions, if any | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/CarePlan), Reference(http://hl7.org/fhir/StructureDefinition/RequestGroup) |  |  |
| `GuidanceResponse.status` | `GuidanceResponse.status` | `status` | GuidanceResponse.status | success \| data-requested \| data-required \| in-progress \| failure \| entered-in-error | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/guidance-response-status|4.0.1` |
| `GuidanceResponse.subject` | `GuidanceResponse.subject` | `subject` | GuidanceResponse.subject | Patient the request was performed for | 0..1 | Reference(http://hl7.org/fhir/StructureDefinition/Group), Reference(http://hl7.org/fhir/StructureDefinition/Patient) |  |  |
| `GuidanceResponse.text` | `GuidanceResponse.text` | `text` | DomainResource.text | Text summary of the resource, for human interpretation | 0..1 | Narrative |  |  |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [GuidanceResponse](/docs/R3/Resources/GuidanceResponse.md)<br/> `http://hl7.org/fhir/StructureDefinition/GuidanceResponse\|3.0.2` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `466`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`RelatedTo`<br/>- DBKey: `660`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [GuidanceResponse](/docs/R4/Resources/GuidanceResponse.md)<br/> `http://hl7.org/fhir/StructureDefinition/GuidanceResponse\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1503`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1504`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [GuidanceResponse](/docs/R4B/Resources/GuidanceResponse.md)<br/> `http://hl7.org/fhir/StructureDefinition/GuidanceResponse\|4.3.0` | →→→→→→→<br/>`RelatedTo`<br/>- DBKey: `985`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `1214`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [GuidanceResponse](/docs/R5/Resources/GuidanceResponse.md)<br/> `http://hl7.org/fhir/StructureDefinition/GuidanceResponse\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition GuidanceResponse from hl7.fhir.r4.core@4.0.1 (R4, key 3).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | [R3 GuidanceResponse](/docs/R3/Resources/GuidanceResponse.md)| Relationship | R4 GuidanceResponse| Relationship | [R4B GuidanceResponse](/docs/R4B/Resources/GuidanceResponse.md)| Relationship | [R5 GuidanceResponse](/docs/R5/Resources/GuidanceResponse.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `GuidanceResponse`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14721)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14722)| **`GuidanceResponse`**| _Equivalent_<br/>(27755/27756)| `GuidanceResponse`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(42719)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(42720)| `GuidanceResponse`
| | | `GuidanceResponse.id`| _Equivalent_<br/>(14723/14724)| **`GuidanceResponse.id`**| _Equivalent_<br/>(27757/27758)| `GuidanceResponse.id`| _Equivalent_<br/>(42721/42722)| `GuidanceResponse.id`
| | | `GuidanceResponse.meta`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14725)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14726)| **`GuidanceResponse.meta`**| _Equivalent_<br/>(27759/27760)| `GuidanceResponse.meta`| _Equivalent_<br/>(42723/42724)| `GuidanceResponse.meta`
| | | `GuidanceResponse.implicitRules`| _Equivalent_<br/>(14727/14728)| **`GuidanceResponse.implicitRules`**| _Equivalent_<br/>(27761/27762)| `GuidanceResponse.implicitRules`| _Equivalent_<br/>(42725/42726)| `GuidanceResponse.implicitRules`
| | | `GuidanceResponse.language`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14729)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(14730)| **`GuidanceResponse.language`**| _Equivalent_<br/>(27763/27764)| `GuidanceResponse.language`| _Equivalent_<br/>(42727/42728)| `GuidanceResponse.language`
| | | `GuidanceResponse.text`| _Equivalent_<br/>(14731/14732)| **`GuidanceResponse.text`**| _Equivalent_<br/>(27765/27766)| `GuidanceResponse.text`| _Equivalent_<br/>(42729/42730)| `GuidanceResponse.text`
| | | `GuidanceResponse.contained`| _Equivalent_<br/>(14733/14734)| **`GuidanceResponse.contained`**| _Equivalent_<br/>(27767/27768)| `GuidanceResponse.contained`| _Equivalent_<br/>(42731/42732)| `GuidanceResponse.contained`
| | | `GuidanceResponse.extension`| _Equivalent_<br/>(14735/14736)| **`GuidanceResponse.extension`**| _Equivalent_<br/>(27769/27770)| `GuidanceResponse.extension`| _Equivalent_<br/>(42733/42734)| `GuidanceResponse.extension`
| | | `GuidanceResponse.modifierExtension`| _Equivalent_<br/>(14737/14738)| **`GuidanceResponse.modifierExtension`**| _Equivalent_<br/>(27771/27772)| `GuidanceResponse.modifierExtension`| _Equivalent_<br/>(42735/42736)| `GuidanceResponse.modifierExtension`
| | | `GuidanceResponse.requestId`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1087)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1537)| **`GuidanceResponse.requestIdentifier`**| _Equivalent_<br/>(27773/27774)| `GuidanceResponse.requestIdentifier`| _Equivalent_<br/>(42737/42738)| `GuidanceResponse.requestIdentifier`
| | | `GuidanceResponse.identifier`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14739)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14740)| **`GuidanceResponse.identifier`**| _Equivalent_<br/>(27775/27776)| `GuidanceResponse.identifier`| _Equivalent_<br/>(42739/42740)| `GuidanceResponse.identifier`
| | | `GuidanceResponse.module`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1084)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1534)| **`GuidanceResponse.module[x]`**| _Equivalent_<br/>(27777/27778)| `GuidanceResponse.module[x]`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(42741)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(42742)| `GuidanceResponse.module[x]`
| | | `GuidanceResponse.status`| _Equivalent_<br/>(14741/14742)| **`GuidanceResponse.status`**| _Equivalent_<br/>(27779/27780)| `GuidanceResponse.status`| _Equivalent_<br/>(42743/42744)| `GuidanceResponse.status`
| | | `GuidanceResponse.subject`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14743)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14744)| **`GuidanceResponse.subject`**| _Equivalent_<br/>(27781/27782)| `GuidanceResponse.subject`| _Equivalent_<br/>(42745/42746)| `GuidanceResponse.subject`
| | | `GuidanceResponse.context`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1083)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1533)| **`GuidanceResponse.encounter`**| _Equivalent_<br/>(27783/27784)| `GuidanceResponse.encounter`| _Equivalent_<br/>(42747/42748)| `GuidanceResponse.encounter`
| | | `GuidanceResponse.occurrenceDateTime`| _Equivalent_<br/>(14745/14746)| **`GuidanceResponse.occurrenceDateTime`**| _Equivalent_<br/>(27785/27786)| `GuidanceResponse.occurrenceDateTime`| _Equivalent_<br/>(42749/42750)| `GuidanceResponse.occurrenceDateTime`
| | | `GuidanceResponse.performer`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14747)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14748)| **`GuidanceResponse.performer`**| _Equivalent_<br/>(27787/27788)| `GuidanceResponse.performer`| _Equivalent_<br/>(42751/42752)| `GuidanceResponse.performer`
| | | `GuidanceResponse.reason[x]`| →→→→ _RelatedTo_ →→→→ <br/>(1085)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1535)| **`GuidanceResponse.reasonCode`**| _Equivalent_<br/>(27789/27790)| `GuidanceResponse.reasonCode`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1883)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2124)| `GuidanceResponse.reason`
| | | `GuidanceResponse.reason[x]`| →→→→ _RelatedTo_ →→→→ <br/>(1086)<hr/>←←←← _RelatedTo_ ←←←← <br/>(1536)| **`GuidanceResponse.reasonReference`**| _Equivalent_<br/>(27791/27792)| `GuidanceResponse.reasonReference`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(1884)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(2125)| `GuidanceResponse.reason`
| | | `GuidanceResponse.note`| _Equivalent_<br/>(14749/14750)| **`GuidanceResponse.note`**| _Equivalent_<br/>(27793/27794)| `GuidanceResponse.note`| _Equivalent_<br/>(42753/42754)| `GuidanceResponse.note`
| | | `GuidanceResponse.evaluationMessage`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14751)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14752)| **`GuidanceResponse.evaluationMessage`**| _Equivalent_<br/>(27795/27796)| `GuidanceResponse.evaluationMessage`| →→→→ _SourceIsBroaderThanTarget_ →→→→ <br/>(42755)<hr/>←←←← _SourceIsNarrowerThanTarget_ ←←←← <br/>(42756)| `GuidanceResponse.evaluationMessage`
| | | `GuidanceResponse.outputParameters`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14753)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14754)| **`GuidanceResponse.outputParameters`**| _Equivalent_<br/>(27797/27798)| `GuidanceResponse.outputParameters`| _Equivalent_<br/>(42757/42758)| `GuidanceResponse.outputParameters`
| | | `GuidanceResponse.result`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14755)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14756)| **`GuidanceResponse.result`**| _Equivalent_<br/>(27799/27800)| `GuidanceResponse.result`| →→→→ _RelatedTo_ →→→→ <br/>(42759)<hr/>←←←← _RelatedTo_ ←←←← <br/>(42760)| `GuidanceResponse.result`
| | | `GuidanceResponse.dataRequirement`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(14757)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(14758)| **`GuidanceResponse.dataRequirement`**| _Equivalent_<br/>(27801/27802)| `GuidanceResponse.dataRequirement`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(42761)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(42762)| `GuidanceResponse.dataRequirement`
| | | *23 of 23 elements used* | | *24 of 24 elements used* | | *24 of 24 elements used* | | *23 of 23 elements used* 

