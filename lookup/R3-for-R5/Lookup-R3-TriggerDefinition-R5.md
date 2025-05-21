### Lookup for FHIR R3 TriggerDefinition for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| TriggerDefinition.id | UseElementSameName | TriggerDefinition.id |
| TriggerDefinition.extension | UseElementSameName | TriggerDefinition.extension |
| TriggerDefinition.type | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-TriggerDefinition.type |
| TriggerDefinition.eventName | UseElementRenamed | TriggerDefinition.name |
| TriggerDefinition.eventTiming[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-TriggerDefinition.eventTiming |
| TriggerDefinition.eventData | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-TriggerDefinition.eventData |
