### Lookup for FHIR R5 TriggerDefinition for use in FHIR R4B

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| TriggerDefinition.id | UseElementSameName | TriggerDefinition.id |
| TriggerDefinition.extension | UseElementSameName | TriggerDefinition.extension |
| TriggerDefinition.type | UseElementSameName | TriggerDefinition.type |
| TriggerDefinition.name | UseElementSameName | TriggerDefinition.name |
| TriggerDefinition.code | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-TriggerDefinition.code |
| TriggerDefinition.subscriptionTopic | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-TriggerDefinition.subscriptionTopic |
| TriggerDefinition.timing[x] | UseElementSameName | TriggerDefinition.timing[x] |
| TriggerDefinition.data | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-TriggerDefinition.data |
| TriggerDefinition.condition | UseElementSameName | TriggerDefinition.condition |
