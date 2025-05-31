### Lookup for FHIR R3 TriggerDefinition for use in FHIR R4B

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| TriggerDefinition.id | UseElementSameName | TriggerDefinition.id |
| TriggerDefinition.extension | UseElementSameName | TriggerDefinition.extension |
| TriggerDefinition.type | UseElementSameName | TriggerDefinition.type |
| TriggerDefinition.eventName | UseElementRenamed | TriggerDefinition.name |
| TriggerDefinition.eventTiming[x] | UseElementRenamed | TriggerDefinition.timing[x] |
| TriggerDefinition.eventData | UseElementRenamed | TriggerDefinition.data |
