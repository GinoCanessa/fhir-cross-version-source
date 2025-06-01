### Lookup for FHIR R4 Provenance for use in FHIR R3

| Source Element | Usage | Target |
| -------------- | ----- | ------ |
| Provenance.id | UseElementSameName | Provenance.id |
| Provenance.meta | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Provenance.meta |
| Provenance.implicitRules | UseElementSameName | Provenance.implicitRules |
| Provenance.language | UseElementSameName | Provenance.language |
| Provenance.text | UseElementSameName | Provenance.text |
| Provenance.contained | UseElementSameName | Provenance.contained |
| Provenance.extension | UseElementSameName | Provenance.extension |
| Provenance.modifierExtension | UseElementSameName | Provenance.modifierExtension |
| Provenance.target | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Provenance.target |
| Provenance.occurred[x] | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Provenance.occurred |
| Provenance.recorded | UseElementSameName | Provenance.recorded |
| Provenance.policy | UseElementSameName | Provenance.policy |
| Provenance.location | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Provenance.location |
| Provenance.reason | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Provenance.reason |
| Provenance.activity | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Provenance.activity |
| Provenance.agent | UseElementSameName | Provenance.agent |
| Provenance.agent.id | UseElementSameName | Provenance.agent.id |
| Provenance.agent.extension | UseElementSameName | Provenance.agent.extension |
| Provenance.agent.modifierExtension | UseElementSameName | Provenance.agent.modifierExtension |
| Provenance.agent.type | UseElementRenamed | Provenance.agent.relatedAgentType |
| Provenance.agent.role | UseElementSameName | Provenance.agent.role |
| Provenance.agent.who | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Provenance.agent.who |
| Provenance.agent.onBehalfOf | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Provenance.agent.onBehalfOf |
| Provenance.entity | UseElementSameName | Provenance.entity |
| Provenance.entity.id | UseElementSameName | Provenance.entity.id |
| Provenance.entity.extension | UseElementSameName | Provenance.entity.extension |
| Provenance.entity.modifierExtension | UseElementSameName | Provenance.entity.modifierExtension |
| Provenance.entity.role | UseElementSameName | Provenance.entity.role |
| Provenance.entity.what | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Provenance.entity.what |
| Provenance.entity.agent | UseElementSameName | Provenance.entity.agent |
| Provenance.signature | UseExtension | http://hl7.org/fhir/4.0/StructureDefinition/extension-Provenance.signature |
