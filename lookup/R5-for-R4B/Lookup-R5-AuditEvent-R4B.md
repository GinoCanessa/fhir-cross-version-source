### Lookup for FHIR R5 AuditEvent for use in FHIR R4B

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| AuditEvent.id | UseElementSameName | AuditEvent.id |
| AuditEvent.meta | UseElementSameName | AuditEvent.meta |
| AuditEvent.implicitRules | UseElementSameName | AuditEvent.implicitRules |
| AuditEvent.language | UseElementSameName | AuditEvent.language |
| AuditEvent.text | UseElementSameName | AuditEvent.text |
| AuditEvent.contained | UseElementSameName | AuditEvent.contained |
| AuditEvent.extension | UseElementSameName | AuditEvent.extension |
| AuditEvent.modifierExtension | UseElementSameName | AuditEvent.modifierExtension |
| AuditEvent.category | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.category |
| AuditEvent.code | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.code |
| AuditEvent.action | UseElementSameName | AuditEvent.action |
| AuditEvent.severity | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.severity |
| AuditEvent.occurred[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.occurred |
| AuditEvent.recorded | UseElementSameName | AuditEvent.recorded |
| AuditEvent.outcome | UseElementSameName | AuditEvent.outcome |
| AuditEvent.outcome.id | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.outcome.id |
| AuditEvent.outcome.extension | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.outcome.extension |
| AuditEvent.outcome.modifierExtension | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.outcome.modifierExtension |
| AuditEvent.outcome.code | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.outcome.code |
| AuditEvent.outcome.detail | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.outcome.detail |
| AuditEvent.authorization | UseElementRenamed | AuditEvent.purposeOfEvent |
| AuditEvent.basedOn | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.basedOn |
| AuditEvent.patient | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.patient |
| AuditEvent.encounter | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.encounter |
| AuditEvent.agent | UseElementSameName | AuditEvent.agent |
| AuditEvent.agent.id | UseElementSameName | AuditEvent.agent.id |
| AuditEvent.agent.extension | UseElementSameName | AuditEvent.agent.extension |
| AuditEvent.agent.modifierExtension | UseElementSameName | AuditEvent.agent.modifierExtension |
| AuditEvent.agent.type | UseElementSameName | AuditEvent.agent.type |
| AuditEvent.agent.role | UseElementSameName | AuditEvent.agent.role |
| AuditEvent.agent.who | UseOneOfElements | AuditEvent.agent.who,AuditEvent.agent.who |
| AuditEvent.agent.requestor | UseElementSameName | AuditEvent.agent.requestor |
| AuditEvent.agent.location | UseElementSameName | AuditEvent.agent.location |
| AuditEvent.agent.policy | UseElementSameName | AuditEvent.agent.policy |
| AuditEvent.agent.network[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.agent.network |
| AuditEvent.agent.authorization | UseElementRenamed | AuditEvent.agent.purposeOfUse |
| AuditEvent.source | UseElementSameName | AuditEvent.source |
| AuditEvent.source.id | UseElementSameName | AuditEvent.source.id |
| AuditEvent.source.extension | UseElementSameName | AuditEvent.source.extension |
| AuditEvent.source.modifierExtension | UseElementSameName | AuditEvent.source.modifierExtension |
| AuditEvent.source.site | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.source.site |
| AuditEvent.source.observer | UseElementSameName | AuditEvent.source.observer |
| AuditEvent.source.type | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.source.type |
| AuditEvent.entity | UseElementSameName | AuditEvent.entity |
| AuditEvent.entity.id | UseElementSameName | AuditEvent.entity.id |
| AuditEvent.entity.extension | UseElementSameName | AuditEvent.entity.extension |
| AuditEvent.entity.modifierExtension | UseElementSameName | AuditEvent.entity.modifierExtension |
| AuditEvent.entity.what | UseOneOfElements | AuditEvent.entity.what,AuditEvent.entity.what |
| AuditEvent.entity.role | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.entity.role |
| AuditEvent.entity.securityLabel | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.entity.securityLabel |
| AuditEvent.entity.query | UseElementSameName | AuditEvent.entity.query |
| AuditEvent.entity.detail | UseElementSameName | AuditEvent.entity.detail |
| AuditEvent.entity.detail.id | UseElementSameName | AuditEvent.entity.detail.id |
| AuditEvent.entity.detail.extension | UseElementSameName | AuditEvent.entity.detail.extension |
| AuditEvent.entity.detail.modifierExtension | UseElementSameName | AuditEvent.entity.detail.modifierExtension |
| AuditEvent.entity.detail.type | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.entity.detail.type |
| AuditEvent.entity.detail.value[x] | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.entity.detail.value |
| AuditEvent.entity.agent | UseExtension | http://hl7.org/fhir/5.0/StructureDefinition/extension-AuditEvent.entity.agent |
