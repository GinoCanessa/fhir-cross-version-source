### Lookup for FHIR R3 Provenance for use in FHIR R2

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Provenance.id | UseElementSameName | Provenance.id |
| Provenance.meta | UseElementSameName | Provenance.meta |
| Provenance.implicitRules | UseElementSameName | Provenance.implicitRules |
| Provenance.language | UseElementSameName | Provenance.language |
| Provenance.text | UseElementSameName | Provenance.text |
| Provenance.contained | UseElementSameName | Provenance.contained |
| Provenance.extension | UseElementSameName | Provenance.extension |
| Provenance.modifierExtension | UseElementSameName | Provenance.modifierExtension |
| Provenance.target | UseElementSameName | Provenance.target |
| Provenance.period | UseElementRenamed | Provenance.period |
| Provenance.recorded | UseElementSameName | Provenance.recorded |
| Provenance.policy | UseElementSameName | Provenance.policy |
| Provenance.location | UseElementSameName | Provenance.location |
| Provenance.reason | UseElementSameName | Provenance.reason |
| Provenance.activity | UseElementSameName | Provenance.activity |
| Provenance.agent | UseElementSameName | Provenance.agent |
| Provenance.agent.id | UseElementSameName | Provenance.agent.id |
| Provenance.agent.extension | UseElementSameName | Provenance.agent.extension |
| Provenance.agent.modifierExtension | UseElementSameName | Provenance.agent.modifierExtension |
| Provenance.agent.role | UseElementSameName | Provenance.agent.role |
| Provenance.agent.who[x] | UseElementRenamed | Provenance.agent.actor |
| Provenance.agent.onBehalfOf[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Provenance.agent.onBehalfOf |
| Provenance.agent.relatedAgentType | UseElementRenamed | Provenance.agent.relatedAgent.type |
| Provenance.entity | UseElementSameName | Provenance.entity |
| Provenance.entity.id | UseElementSameName | Provenance.entity.id |
| Provenance.entity.extension | UseElementSameName | Provenance.entity.extension |
| Provenance.entity.modifierExtension | UseElementSameName | Provenance.entity.modifierExtension |
| Provenance.entity.role | UseElementSameName | Provenance.entity.role |
| Provenance.entity.what[x] | UseElementRenamed | Provenance.entity.reference |
| Provenance.entity.agent | UseElementSameName | Provenance.entity.agent |
| Provenance.signature | UseElementSameName | Provenance.signature |
