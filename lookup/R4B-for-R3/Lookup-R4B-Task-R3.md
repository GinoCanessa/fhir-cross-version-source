### Lookup for FHIR R4B Task for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Task.id | UseElementSameName | ProcessRequest.id |
| Task.meta | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Task.meta |
| Task.implicitRules | UseElementSameName | ProcessRequest.implicitRules |
| Task.language | UseElementSameName | ProcessRequest.language |
| Task.text | UseElementSameName | ProcessRequest.text |
| Task.contained | UseElementSameName | ProcessRequest.contained |
| Task.extension | UseElementSameName | ProcessRequest.extension |
| Task.modifierExtension | UseElementSameName | ProcessRequest.modifierExtension |
| Task.identifier | UseElementSameName | ProcessRequest.identifier |
| Task.instantiatesCanonical | UseElementSameName | Task.definition[x] |
| Task.instantiatesUri | UseElementSameName | Task.definition[x] |
| Task.basedOn | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Task.basedOn |
| Task.groupIdentifier | UseElementSameName | Task.groupIdentifier |
| Task.partOf | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Task.partOf |
| Task.status | UseElementSameName | Task.status |
| Task.statusReason | UseElementSameName | Task.statusReason |
| Task.businessStatus | UseElementSameName | Task.businessStatus |
| Task.intent | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Task.intent |
| Task.priority | UseElementSameName | Task.priority |
| Task.code | UseElementSameName | Task.code |
| Task.description | UseElementSameName | Task.description |
| Task.focus | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Task.focus |
| Task.for | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Task.for |
| Task.encounter | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Task.encounter |
| Task.executionPeriod | UseElementSameName | Task.executionPeriod |
| Task.authoredOn | UseElementSameName | Task.authoredOn |
| Task.lastModified | UseElementSameName | Task.lastModified |
| Task.requester | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Task.requester |
| Task.performerType | UseElementSameName | Task.performerType |
| Task.owner | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Task.owner |
| Task.location | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Task.location |
| Task.reasonCode | UseElementSameName | Task.reason |
| Task.reasonReference | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Task.reasonReference |
| Task.insurance | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Task.insurance |
| Task.note | UseElementSameName | Task.note |
| Task.relevantHistory | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Task.relevantHistory |
| Task.restriction | UseElementSameName | Task.restriction |
| Task.restriction.id | UseElementSameName | Task.restriction.id |
| Task.restriction.extension | UseElementSameName | Task.restriction.extension |
| Task.restriction.modifierExtension | UseElementSameName | Task.restriction.modifierExtension |
| Task.restriction.repetitions | UseElementSameName | Task.restriction.repetitions |
| Task.restriction.period | UseElementSameName | Task.restriction.period |
| Task.restriction.recipient | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Task.restriction.recipient |
| Task.input | UseElementSameName | Task.input |
| Task.input.id | UseElementSameName | Task.input.id |
| Task.input.extension | UseElementSameName | Task.input.extension |
| Task.input.modifierExtension | UseElementSameName | Task.input.modifierExtension |
| Task.input.type | UseElementSameName | Task.input.type |
| Task.input.value[x] | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Task.input.value |
| Task.output | UseElementSameName | Task.output |
| Task.output.id | UseElementSameName | Task.output.id |
| Task.output.extension | UseElementSameName | Task.output.extension |
| Task.output.modifierExtension | UseElementSameName | Task.output.modifierExtension |
| Task.output.type | UseElementSameName | Task.output.type |
| Task.output.value[x] | UseExtension | http://hl7.org/fhir/4.3/StructureDefinition/extension-Task.output.value |
