### Lookup for FHIR R4 TriggerDefinition for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| TriggerDefinition.id | UseElementSameName | TriggerDefinition.id |
| TriggerDefinition.extension | UseElementSameName | TriggerDefinition.extension |
| TriggerDefinition.type | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-TriggerDefinition.type |
| TriggerDefinition.name | UseElementRenamed | TriggerDefinition.eventName |
| TriggerDefinition.timing[x] | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-TriggerDefinition.timing |
| TriggerDefinition.data | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-TriggerDefinition.data |
| TriggerDefinition.condition | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-TriggerDefinition.condition |
