Comparison of 
Generated at Thursday, April 3, 2025 8:18:33 AM

### TriggerDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r5.core@5.0.0 |
| Stucture Name | TriggerDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/TriggerDefinition` |
| Version | 5.0.0 |
| Description | TriggerDefinition Type: A description of a triggering event. Triggering events can be named events, data events, or periodic, as determined by the type element. |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `2245` |
| Database Snapshot Count | `10` |
| Database Differential Count | `8` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `TriggerDefinition` | `TriggerDefinition` | `TriggerDefinition` | TriggerDefinition | Defines an expected trigger for a module | 0..* | TriggerDefinition |  |  |
| `TriggerDefinition.code` | `TriggerDefinition.code` | `code` | TriggerDefinition.code | Coded definition of the event | 0..1 | CodeableConcept |  |  |
| `TriggerDefinition.condition` | `TriggerDefinition.condition` | `condition` | TriggerDefinition.condition | Whether the event triggers (boolean expression) | 0..1 | Expression |  |  |
| `TriggerDefinition.data` | `TriggerDefinition.data` | `data` | TriggerDefinition.data | Triggering data of the event (multiple = 'and') | 0..* | DataRequirement |  |  |
| `TriggerDefinition.extension` | `TriggerDefinition.extension` | `extension` | Element.extension | Additional content defined by implementations | 0..* | Extension |  |  |
| `TriggerDefinition.id` | `TriggerDefinition.id` | `id` | Element.id | Unique id for inter-element referencing | 0..1 | id |  |  |
| `TriggerDefinition.name` | `TriggerDefinition.name` | `name` | TriggerDefinition.name | Name or URI that identifies the event | 0..1 | string |  |  |
| `TriggerDefinition.subscriptionTopic` | `TriggerDefinition.subscriptionTopic` | `subscriptionTopic` | TriggerDefinition.subscriptionTopic | What event | 0..1 | canonical(http://hl7.org/fhir/StructureDefinition/SubscriptionTopic) |  |  |
| `TriggerDefinition.timing[x]` | `TriggerDefinition.timing[x]` | `timing[x]` | TriggerDefinition.timing[x] | Timing of the event | 0..1 | date, dateTime, Reference(http://hl7.org/fhir/StructureDefinition/Schedule), Timing |  |  |
| `TriggerDefinition.type` | `TriggerDefinition.type` | `type` | TriggerDefinition.type | named-event \| periodic \| data-changed \| data-added \| data-modified \| data-removed \| data-accessed \| data-access-ended | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/trigger-type|5.0.0` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [TriggerDefinition](/docs/R3/ComplexTypes/TriggerDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/TriggerDefinition\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `413`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `609`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TriggerDefinition](/docs/R4/ComplexTypes/TriggerDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/TriggerDefinition\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1383`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1384`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TriggerDefinition](/docs/R4B/ComplexTypes/TriggerDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/TriggerDefinition\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `924`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1153`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TriggerDefinition](/docs/R5/ComplexTypes/TriggerDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/TriggerDefinition\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition TriggerDefinition from hl7.fhir.r5.core@5.0.0 (R5, key 5).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | [R3 TriggerDefinition](/docs/R3/ComplexTypes/TriggerDefinition.md)| Relationship | [R4 TriggerDefinition](/docs/R4/ComplexTypes/TriggerDefinition.md)| Relationship | [R4B TriggerDefinition](/docs/R4B/ComplexTypes/TriggerDefinition.md)| Relationship | R5 TriggerDefinition
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | `TriggerDefinition`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9859)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9860)| `TriggerDefinition`| _Equivalent_<br/>(21340/21341)| `TriggerDefinition`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36405)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36406)| **`TriggerDefinition`**
| | | `TriggerDefinition.id`| _Equivalent_<br/>(9861/9862)| `TriggerDefinition.id`| _Equivalent_<br/>(21342/21343)| `TriggerDefinition.id`| _Equivalent_<br/>(36407/36408)| **`TriggerDefinition.id`**
| | | `TriggerDefinition.extension`| _Equivalent_<br/>(9863/9864)| `TriggerDefinition.extension`| _Equivalent_<br/>(21344/21345)| `TriggerDefinition.extension`| _Equivalent_<br/>(36409/36410)| **`TriggerDefinition.extension`**
| | | `TriggerDefinition.type`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9865)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9866)| `TriggerDefinition.type`| _Equivalent_<br/>(21346/21347)| `TriggerDefinition.type`| _Equivalent_<br/>(36411/36412)| **`TriggerDefinition.type`**
| | | `TriggerDefinition.eventName`| _Equivalent_<br/>(1313/1687)| `TriggerDefinition.name`| _Equivalent_<br/>(21348/21349)| `TriggerDefinition.name`| _Equivalent_<br/>(36413/36414)| **`TriggerDefinition.name`**
| | | | | | | | | **`TriggerDefinition.code`**
| | | | | | | | | **`TriggerDefinition.subscriptionTopic`**
| | | `TriggerDefinition.eventTiming[x]`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1314)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1688)| `TriggerDefinition.timing[x]`| _Equivalent_<br/>(21350/21351)| `TriggerDefinition.timing[x]`| _Equivalent_<br/>(36415/36416)| **`TriggerDefinition.timing[x]`**
| | | `TriggerDefinition.eventData`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1312)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1686)| `TriggerDefinition.data`| _Equivalent_<br/>(21352/21353)| `TriggerDefinition.data`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36417)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36418)| **`TriggerDefinition.data`**
| | | | | `TriggerDefinition.condition`| _Equivalent_<br/>(21354/21355)| `TriggerDefinition.condition`| _Equivalent_<br/>(36419/36420)| **`TriggerDefinition.condition`**
| | | *7 of 7 elements used* | | *8 of 8 elements used* | | *8 of 8 elements used* | | *10 of 10 elements used* 

