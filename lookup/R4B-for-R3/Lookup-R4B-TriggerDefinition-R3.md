### Lookup for FHIR R4B TriggerDefinition for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| TriggerDefinition.id | UseElementSameName | TriggerDefinition.id |
| TriggerDefinition.extension | UseElementSameName | TriggerDefinition.extension |
| TriggerDefinition.type | UseElementSameName | TriggerDefinition.type |
| TriggerDefinition.name | UseElementSameName | TriggerDefinition.eventName |
| TriggerDefinition.timing[x] | UseElementSameName | TriggerDefinition.eventTiming[x] |
| TriggerDefinition.data | UseElementSameName | TriggerDefinition.eventData |
| TriggerDefinition.condition | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-TriggerDefinition.condition |
