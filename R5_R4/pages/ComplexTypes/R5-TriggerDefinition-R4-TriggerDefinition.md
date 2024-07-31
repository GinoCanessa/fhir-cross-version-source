Comparison of hl7.fhir.r5.core#5.0.0 and hl7.fhir.r4.core#4.0.1

| Side | Name | Title | Description | Snapshot | Differential |
| --- | --- | --- | --- | --- | --- |
| Source | TriggerDefinition |  | TriggerDefinition Type: A description of a triggering event. Triggering events can be named events, data events, or periodic, as determined by the type element. | 10 | 8 |
| Target | TriggerDefinition |  | Base StructureDefinition for TriggerDefinition Type: A description of a triggering event. Triggering events can be named events, data events, or periodic, as determined by the type element. | 8 | 6 |


Comparison Result: SourceIsBroaderThanTarget


### Mapping details

| Status | Count |
| ------ | ----- |
DoesNotExistInTarget | 2 |
Equivalent | 8 |


| Source | Target | Status | Message |
| ------ | ------ | ------ | ------- |
| TriggerDefinition | TriggerDefinition | Equivalent | R5 `TriggerDefinition` maps as Equivalent to R4 `TriggerDefinition` |
| TriggerDefinition.code | - | DoesNotExistInTarget | R5 `TriggerDefinition.code` does not appear in the target and has no mapping for `TriggerDefinition`. |
| TriggerDefinition.condition | TriggerDefinition.condition | Equivalent | R5 `TriggerDefinition.condition` maps as Equivalent to R4 `TriggerDefinition.condition` |
| TriggerDefinition.data | TriggerDefinition.data | Equivalent | R5 `TriggerDefinition.data` maps as Equivalent to R4 `TriggerDefinition.data` |
| TriggerDefinition.extension | TriggerDefinition.extension | Equivalent | R5 `TriggerDefinition.extension` maps as Equivalent to R4 `TriggerDefinition.extension` |
| TriggerDefinition.id | TriggerDefinition.id | Equivalent | R5 `TriggerDefinition.id` maps as Equivalent to R4 `TriggerDefinition.id` |
| TriggerDefinition.name | TriggerDefinition.name | Equivalent | R5 `TriggerDefinition.name` maps as Equivalent to R4 `TriggerDefinition.name` |
| TriggerDefinition.subscriptionTopic | - | DoesNotExistInTarget | R5 `TriggerDefinition.subscriptionTopic` does not appear in the target and has no mapping for `TriggerDefinition`. |
| TriggerDefinition.timing[x] | TriggerDefinition.timing[x] | Equivalent | R5 `TriggerDefinition.timing[x]` maps as Equivalent to R4 `TriggerDefinition.timing[x]` |
| TriggerDefinition.type | TriggerDefinition.type | Equivalent | R5 `TriggerDefinition.type` maps as Equivalent to R4 `TriggerDefinition.type` - type has compatible required binding for code type: http://hl7.org/fhir/ValueSet/trigger-type|5.0.0 and http://hl7.org/fhir/ValueSet/trigger-type|4.0.1 (Equivalent) |

