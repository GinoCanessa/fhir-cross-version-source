### Lookup for FHIR R4 AuditEvent for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| AuditEvent.id | UseElementSameName | AuditEvent.id |
| AuditEvent.meta | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-AuditEvent.meta |
| AuditEvent.implicitRules | UseElementSameName | AuditEvent.implicitRules |
| AuditEvent.language | UseElementSameName | AuditEvent.language |
| AuditEvent.text | UseElementSameName | AuditEvent.text |
| AuditEvent.contained | UseElementSameName | AuditEvent.contained |
| AuditEvent.extension | UseElementSameName | AuditEvent.extension |
| AuditEvent.modifierExtension | UseElementSameName | AuditEvent.modifierExtension |
| AuditEvent.type | UseElementSameName | AuditEvent.event.type |
| AuditEvent.subtype | UseElementSameName | AuditEvent.event.subtype |
| AuditEvent.action | UseElementSameName | AuditEvent.event.action |
| AuditEvent.period | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-AuditEvent.period |
| AuditEvent.recorded | UseElementSameName | AuditEvent.event.dateTime |
| AuditEvent.outcome | UseElementSameName | AuditEvent.event.outcome |
| AuditEvent.outcomeDesc | UseElementSameName | AuditEvent.event.outcomeDesc |
| AuditEvent.purposeOfEvent | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-AuditEvent.purposeOfEvent |
| AuditEvent.agent | UseElementSameName | AuditEvent.participant |
| AuditEvent.agent.id | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-AuditEvent.agent.id |
| AuditEvent.agent.extension | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-AuditEvent.agent.extension |
| AuditEvent.agent.modifierExtension | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-AuditEvent.agent.modifierExtension |
| AuditEvent.agent.type | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-AuditEvent.agent.type |
| AuditEvent.agent.role | UseElementSameName | AuditEvent.participant.role |
| AuditEvent.agent.who | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-AuditEvent.agent.who |
| AuditEvent.agent.altId | UseElementSameName | AuditEvent.participant.altId |
| AuditEvent.agent.name | UseElementSameName | AuditEvent.participant.name |
| AuditEvent.agent.requestor | UseElementSameName | AuditEvent.participant.requestor |
| AuditEvent.agent.location | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-AuditEvent.agent.location |
| AuditEvent.agent.policy | UseElementSameName | AuditEvent.participant.policy |
| AuditEvent.agent.media | UseElementSameName | AuditEvent.participant.media |
| AuditEvent.agent.network | UseElementSameName | AuditEvent.participant.network |
| AuditEvent.agent.network.id | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-AuditEvent.agent.network.id |
| AuditEvent.agent.network.extension | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-AuditEvent.agent.network.extension |
| AuditEvent.agent.network.modifierExtension | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-AuditEvent.agent.network.modifierExtension |
| AuditEvent.agent.network.address | UseElementSameName | AuditEvent.participant.network.address |
| AuditEvent.agent.network.type | UseElementSameName | AuditEvent.participant.network.type |
| AuditEvent.agent.purposeOfUse | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-AuditEvent.agent.purposeOfUse |
| AuditEvent.source | UseElementSameName | AuditEvent.source |
| AuditEvent.source.id | UseElementSameName | AuditEvent.source.id |
| AuditEvent.source.extension | UseElementSameName | AuditEvent.source.extension |
| AuditEvent.source.modifierExtension | UseElementSameName | AuditEvent.source.modifierExtension |
| AuditEvent.source.site | UseElementSameName | AuditEvent.source.site |
| AuditEvent.source.observer | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-AuditEvent.source.observer |
| AuditEvent.source.type | UseElementSameName | AuditEvent.source.type |
| AuditEvent.entity | UseElementSameName | AuditEvent.object |
| AuditEvent.entity.id | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-AuditEvent.entity.id |
| AuditEvent.entity.extension | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-AuditEvent.entity.extension |
| AuditEvent.entity.modifierExtension | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-AuditEvent.entity.modifierExtension |
| AuditEvent.entity.what | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-AuditEvent.entity.what |
| AuditEvent.entity.type | UseElementSameName | AuditEvent.object.type |
| AuditEvent.entity.role | UseElementSameName | AuditEvent.object.role |
| AuditEvent.entity.lifecycle | UseElementSameName | AuditEvent.object.lifecycle |
| AuditEvent.entity.securityLabel | UseElementSameName | AuditEvent.object.securityLabel |
| AuditEvent.entity.name | UseElementSameName | AuditEvent.object.name |
| AuditEvent.entity.description | UseElementSameName | AuditEvent.object.description |
| AuditEvent.entity.query | UseElementSameName | AuditEvent.object.query |
| AuditEvent.entity.detail | UseElementSameName | AuditEvent.object.detail |
| AuditEvent.entity.detail.id | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-AuditEvent.entity.detail.id |
| AuditEvent.entity.detail.extension | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-AuditEvent.entity.detail.extension |
| AuditEvent.entity.detail.modifierExtension | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-AuditEvent.entity.detail.modifierExtension |
| AuditEvent.entity.detail.type | UseElementSameName | AuditEvent.object.detail.type |
| AuditEvent.entity.detail.value[x] | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-AuditEvent.entity.detail.value |
