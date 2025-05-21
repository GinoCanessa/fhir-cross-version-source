### Lookup for FHIR R3 Provenance for use in FHIR R5

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Provenance.id | UseElementSameName | Provenance.id |
| Provenance.meta | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Provenance.meta |
| Provenance.implicitRules | UseElementSameName | Provenance.implicitRules |
| Provenance.language | UseElementSameName | Provenance.language |
| Provenance.text | UseElementSameName | Provenance.text |
| Provenance.contained | UseElementSameName | Provenance.contained |
| Provenance.extension | UseElementSameName | Provenance.extension |
| Provenance.modifierExtension | UseElementSameName | Provenance.modifierExtension |
| Provenance.target | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Provenance.target |
| Provenance.period | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Provenance.period |
| Provenance.recorded | UseElementSameName | Provenance.recorded |
| Provenance.policy | UseElementSameName | Provenance.policy |
| Provenance.location | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Provenance.location |
| Provenance.reason | UseElementRenamed | Provenance.authorization |
| Provenance.activity | UseElementSameName | Provenance.activity |
| Provenance.agent | UseElementSameName | Provenance.agent |
| Provenance.agent.id | UseElementSameName | Provenance.agent.id |
| Provenance.agent.extension | UseElementSameName | Provenance.agent.extension |
| Provenance.agent.modifierExtension | UseElementSameName | Provenance.agent.modifierExtension |
| Provenance.agent.role | UseElementSameName | Provenance.agent.role |
| Provenance.agent.who[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Provenance.agent.who |
| Provenance.agent.onBehalfOf[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Provenance.agent.onBehalfOf |
| Provenance.agent.relatedAgentType | UseElementRenamed | Provenance.agent.type |
| Provenance.entity | UseElementSameName | Provenance.entity |
| Provenance.entity.id | UseElementSameName | Provenance.entity.id |
| Provenance.entity.extension | UseElementSameName | Provenance.entity.extension |
| Provenance.entity.modifierExtension | UseElementSameName | Provenance.entity.modifierExtension |
| Provenance.entity.role | UseElementSameName | Provenance.entity.role |
| Provenance.entity.what[x] | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Provenance.entity.what |
| Provenance.entity.agent | UseElementSameName | Provenance.entity.agent |
| Provenance.signature | UseExtension | http://hl7.org/fhir/3.0/StructureDefinition/extension-Provenance.signature |
