Comparison of 
Generated at Friday, April 4, 2025 2:58:38 PM

### TriggerDefinition

|      |     |
| ---: | --- |
| Package | hl7.fhir.r3.core@3.0.2 |
| Stucture Name | TriggerDefinition |
| Canonical URL | `http://hl7.org/fhir/StructureDefinition/TriggerDefinition` |
| Version | 3.0.2 |
| Description | Base StructureDefinition for TriggerDefinition Type |
| Status | `Draft` |
| Artifact Class | `ComplexType` |
| Database Key | `473` |
| Database Snapshot Count | `7` |
| Database Differential Count | `5` |

### Elements

| Id | Path | Name | Base Path | Short | Cardinality | Collated Type | Binding Strength | Binding Value Set |
| -- | ---- | ---- | --------- | ----- | ----------- | ------------- | ---------------- | ----------------- |
| `TriggerDefinition` | `TriggerDefinition` | `TriggerDefinition` | TriggerDefinition | Defines an expected trigger for a module | 0..* | TriggerDefinition |  |  |
| `TriggerDefinition.eventData` | `TriggerDefinition.eventData` | `eventData` |  | Triggering data of the event | 0..1 | DataRequirement |  |  |
| `TriggerDefinition.eventName` | `TriggerDefinition.eventName` | `eventName` |  | Triggering event name | 0..1 | string |  |  |
| `TriggerDefinition.eventTiming[x]` | `TriggerDefinition.eventTiming[x]` | `eventTiming[x]` |  | Timing of the event | 0..1 | date, dateTime, Reference(http://hl7.org/fhir/StructureDefinition/Schedule), Timing |  |  |
| `TriggerDefinition.extension` | `TriggerDefinition.extension` | `extension` | Element.extension | Additional Content defined by implementations | 0..* | Extension |  |  |
| `TriggerDefinition.id` | `TriggerDefinition.id` | `id` | Element.id | xml:id (or equivalent in JSON) | 0..1 | id |  |  |
| `TriggerDefinition.type` | `TriggerDefinition.type` | `type` |  | named-event \| periodic \| data-added \| data-modified \| data-removed \| data-accessed \| data-access-ended | 1..1 | code | `Required` | `http://hl7.org/fhir/ValueSet/trigger-type` |
### Mapping Table

| R2 | Comparison | R3 | Comparison | R4 | Comparison | R4B | Comparison | R5
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | [TriggerDefinition](/docs/R3/ComplexTypes/TriggerDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/TriggerDefinition\|3.0.2` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `413`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `609`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TriggerDefinition](/docs/R4/ComplexTypes/TriggerDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/TriggerDefinition\|4.0.1` | →→→→→→→<br/>`Equivalent`<br/>- DBKey: `1383`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`Equivalent`<br/>- DBKey: `1384`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TriggerDefinition](/docs/R4B/ComplexTypes/TriggerDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/TriggerDefinition\|4.3.0` | →→→→→→→<br/>`SourceIsNarrowerThanTarget`<br/>- DBKey: `924`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>→→→→→→→<hr/>←←←←←←←<br/>`SourceIsBroaderThanTarget`<br/>- DBKey: `1153`<br/>- Reviewed: `n/a`<br/>- By: `n/a`<br/>←←←←←←←| [TriggerDefinition](/docs/R5/ComplexTypes/TriggerDefinition.md)<br/> `http://hl7.org/fhir/StructureDefinition/TriggerDefinition\|5.0.0` 

### Element Mappings


#### Map Group 0

This group is centered on the Structure Definition TriggerDefinition from hl7.fhir.r3.core@3.0.2 (R3, key 2).
All elements from this structure are listed while other structures only show contents that have relationships with those elements.

| *No Map* | Relationship | R3 TriggerDefinition| Relationship | [R4 TriggerDefinition](/docs/R4/ComplexTypes/TriggerDefinition.md)| Relationship | [R4B TriggerDefinition](/docs/R4B/ComplexTypes/TriggerDefinition.md)| Relationship | [R5 TriggerDefinition](/docs/R5/ComplexTypes/TriggerDefinition.md)
| --- | --- | --- | --- | --- | --- | --- | --- | ---
| | | **`TriggerDefinition`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9859)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9860)| `TriggerDefinition`| _Equivalent_<br/>(21340/21341)| `TriggerDefinition`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36405)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36406)| `TriggerDefinition`
| | | **`TriggerDefinition.id`**| _Equivalent_<br/>(9861/9862)| `TriggerDefinition.id`| _Equivalent_<br/>(21342/21343)| `TriggerDefinition.id`| _Equivalent_<br/>(36407/36408)| `TriggerDefinition.id`
| | | **`TriggerDefinition.extension`**| _Equivalent_<br/>(9863/9864)| `TriggerDefinition.extension`| _Equivalent_<br/>(21344/21345)| `TriggerDefinition.extension`| _Equivalent_<br/>(36409/36410)| `TriggerDefinition.extension`
| | | **`TriggerDefinition.type`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(9865)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(9866)| `TriggerDefinition.type`| _Equivalent_<br/>(21346/21347)| `TriggerDefinition.type`| _Equivalent_<br/>(36411/36412)| `TriggerDefinition.type`
| | | **`TriggerDefinition.eventName`**| _Equivalent_<br/>(1313/1687)| `TriggerDefinition.name`| _Equivalent_<br/>(21348/21349)| `TriggerDefinition.name`| _Equivalent_<br/>(36413/36414)| `TriggerDefinition.name`
| | | **`TriggerDefinition.eventTiming[x]`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1314)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1688)| `TriggerDefinition.timing[x]`| _Equivalent_<br/>(21350/21351)| `TriggerDefinition.timing[x]`| _Equivalent_<br/>(36415/36416)| `TriggerDefinition.timing[x]`
| | | **`TriggerDefinition.eventData`**| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(1312)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(1686)| `TriggerDefinition.data`| _Equivalent_<br/>(21352/21353)| `TriggerDefinition.data`| →→→→ _SourceIsNarrowerThanTarget_ →→→→ <br/>(36417)<hr/>←←←← _SourceIsBroaderThanTarget_ ←←←← <br/>(36418)| `TriggerDefinition.data`
| | | *7 of 7 elements used* | | *7 of 8 elements used* <br/>remaining elements:<br/>`TriggerDefinition.condition`| | *7 of 8 elements used* <br/>remaining elements:<br/>`TriggerDefinition.condition`| | *7 of 10 elements used* <br/>remaining elements:<br/>`TriggerDefinition.code`, `TriggerDefinition.condition`, `TriggerDefinition.subscriptionTopic`

